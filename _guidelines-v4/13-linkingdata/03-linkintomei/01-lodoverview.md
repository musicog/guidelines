---
sectionid: lodOverview
title: "Overview"
version: "v4"
---

### Turning identifiers into URIs

As in any XML schema, each element within the MEI hierarchy may be provided with an identifier using the **@xml:id** attribute. The value of this attribute should be unique within a given document (per the [xml:id]("https://www.w3.org/TR/xml-id") specification); this allows **@xml:id** values to act as link target anchors, as described in section *TODO-CROSSREF?*13.2.2.1.

Beyond creating references within and across MEI documents, this provides a mechanism for linking to elements within MEI documents from any information resource hosted on the Web. By suffixing the **@xml:id** of a given MEI element to its containing document's URI followed by a hash mark (`#`) as a so-called [fragment identifier](https://tools.ietf.org/html/rfc3986#section-3.5), a URI corresponding to the MEI element is created. 

To illustrate, consider the [sample encoding](https://github.com/music-encoding/sample-encodings) of [Franz Schubert's Der Lindenbaum](https://github.com/music-encoding/sample-encodings/blob/master/MEI_4.0/Music/Complete_examples/Schubert_Lindenbaum.mei). The URI of the MEI file encoding this piece, available from the Music Encoding Initiative's sample-encodings GitHub repository, is:

`https://raw.githubusercontent.com/music-encoding/sample-encodings/master/MEI_4.0/Music/Complete_examples/Schubert_Lindenbaum.mei`

The **@xml:id** attribute value for the first measure encoded within this MEI file is `d1e15`. In order to create a URI for this measure, we simply append this value to the MEI file's URI, using a hash mark:

`https://raw.githubusercontent.com/music-encoding/sample-encodings/master/MEI_4.0/Music/Complete_examples/Schubert_Lindenbaum.mei#d1e15`

We can use this URI to refer to the first measure of *this particular copy* of *this particular encoding* of Schubert's piece from anywhere on the Web. Such URIs can be dereferenced by a Web client (using a HTTP request) in order to obtain a copy of the corresponding encoding. Note that fragment identifiers are [reserved for client-side processing](https://tools.ietf.org/html/rfc7230#section-5.1), meaning that they are stripped from HTTP requests. Thus, the entire MEI document is returned when you [click on this link to the example measure's URI](https://raw.githubusercontent.com/music-encoding/sample-encodings/master/MEI_4.0/Music/Complete_examples/Schubert_Lindenbaum.mei#d1e15) in your web browser.

### Linked Data: describing music with URIs

[Linked Data](https://www.w3.org/DesignIssues/LinkedData.html) is a way of publishing structured assertions about relationships between data. Whereas URIs are broadly used to create 'web links' interlinking *documents* on the Web, the Linked Data approach can be used to interlink *data* within a *semantic* Web -- semantic because the *meaning* of each asserted relationship is represented in a machine-readable form.

Assertions are structured as (*subject*, *predicate*, *object*) triples, according to the [Resource Description Framework](https://www.w3.org/TR/rdf-primer/). Each part of these triples (the subject, predicate, and object) may be identified by a URI, which can be dereferenced in order to obtain further information. The object of one triple may be the subject of another, interlinking triples into a wider Web of data. 

Consider the following example. [Wikidata](https://www.wikidata.org) is a free and open knowledge base providing linked data on a wide variety of topics. Each described entity and relationship is provided with a URI, which can be dereferenced to obtain more information. Schubert's *Der Lindenbaum* has the following URI: [http://www.wikidata.org/entity/Q451214](http://www.wikidata.org/entity/Q451214). If you click on the link to this URI in your web browser, you will find human-readable information on this piece. However, if you dereference the URI using an HTTP GET call, for example through the widely-used `curl` command-line utility, you can request a machine-readable RDF representation of the same information:

`$ curl -L -H "Accept:text/turtle" http://www.wikidata.org/entity/Q451214`

This will return a huge amount of information, including the following small excerpt:

```
@prefix wd: <http://www.wikidata.org/entity/> .
@prefix wdt: <http://www.wikidata.org/prop/direct/> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .
@prefix schema: <http://schema.org/> .
  
wd:Q451214 schema:name "Am Brunnen vor dem Tore"@de ;
  skos:altLabel "Der Lindenbaum"@de ;
  wdt:P86 wd:Q7312 .
```

This information is formatted in the [turtle](https://www.w3.org/TR/turtle/) format, a *serialisation* of RDF. Other serialisations are available - you can try some out by replacing `text/turtle` in the curl command above with application/rdf+xml (for [RDF XML](https://www.w3.org/TR/rdf-syntax-grammar/)), or application/ld+json (for [JSON-LD](https://www.w3.org/TR/json-ld/)). In each case, precisely the same *information* (formatted according to the chosen serialisation) is returned. 

The turtle excerpt above contains three RDF triples. The *subject* of each triple is `wd:Q451214` -- the semicolon is a syntactic convenience of the turtle serialisation that means "the next triple will share this triple's subject". The `@prefix` information at the beginning of the output is a further turtle-specific convenience to shorten URIs in the remainder of the response (for the benefit of human readers). They simply provide a means of turning shortened identifiers like `wd:Q451214` into full URIs like `http://www.wikidata.org/entity/Q451214`. 

The excerpt asserts that the (German) name of the entity with URI `http://www.wikidata.org/entity/Q451214` is "Am Brunnen vor dem Tore" and that "Der Lindenbaum" is an alternative label for the same entity. It also tells us that:

`wd:Q451214 wdt:P86 wd:Q7312 .`

Dereferencing the URIs [http://www.wikidata.org/prop/direct/P86](http://www.wikidata.org/prop/direct/P86) and [http://www.wikidata.org/entity/Q7312](http://www.wikidata.org/entity/Q7312), using your web browser or a curl command similar to the one above, will reveal that this triple asserts that *Der Lindenbaum* was composed by Franz Schubert. 

Of course, this sort of information can be stored much more simply in the MEI header. However, because we are now working with a Web of data, we can move further afield. Crawling through this Web by dereferencing first Schubert ([wd:Q7312](http://www.wikidata.org/entity/Q7312)) and then the predicates and objects associated with him, we find him to be a citizen ([wdt:P27](http://www.wikidata.org/prop/direct/P27')) of the Austrian Empire ([wd:Q131964](http://www.wikidata.org/entity/Q131964)), born in ([wdt:P19](http://www.wikidata.org/prop/direct/P19')) Himmelpfortgrund ([wd:Q687026](https://www.wikidata.org/entity/Q687026)) located in the administrative territorial entity (([wdt:P131](http://www.wikidata.org/prop/direct/P131')) of Alsergrund ([wd:Q257780](https://www.wikidata.org/entity/Q257780)), which has an elevation above sea level ([P2044](https://www.wikidata.org/prop/direct/P2044)) of 179 metres. 

This somewhat contrived example is intended to illustrate the breadth and depth of information that can be discovered, cross-referenced, and interlinked with music information using the linked data approach.

### MEI elements as linked data

