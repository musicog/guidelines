---
layout: sidebar
sidebar: s1
version: "v4"
title: "att.bracketSpan.vis"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.bracketSpan.vis">att.bracketSpan.vis</h3>
      <div class="specs">
         <div class="desc">Visual domain attributes.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.visual</div>
         </div>
         <div class="facet attributes" id="attributes">
            <div class="label">Attributes</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="attributes_compact_tab" href="#attributes" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="full" id="attributes_full_tab" href="#attributes" class="displayTab">full definition</a></li>
                  <li class="tab-item"><a data-display="class" id="attributes_class_tab" href="#attributes" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="attributes_module_tab" href="#attributes" class="displayTab">by module</a></li>
               </ul>
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="symbolDef Provides a way of pointing to a user-defined symbol. It must contain a reference to an ID of a element elsewhere in the document.">altsym</span>, <span class="ident attribute" title="Used to indicate visual appearance. Do not confuse this with the musical term 'color' as used in pre-CMN notation.">color</span>, <span class="ident attribute" title="Records the horizontal adjustment of a feature's programmatically-determined end point.">endho</span>, <span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined end point.">endto</span>, <span class="ident attribute" title="Records a vertical adjustment of a feature's programmatically-determined end point.">endvo</span>, <span class="ident attribute" title="Contains the name of a font-family.">fontfam</span>, <span class="ident attribute" title="Holds the name of a font.">fontname</span>, <span class="ident attribute" title="Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch, relative terms, e.g., &#34;small&#34;, &#34;larger&#34;, etc., or percentage values relative to &#34;normal&#34; size, e.g., &#34;125%&#34;.">fontsize</span>, <span class="ident attribute" title="Records the style of a font, i.e, italic, oblique, or normal.">fontstyle</span>, <span class="ident attribute" title="Used to indicate bold type.">fontweight</span>, <span class="ident attribute" title="glyph.name glyph.num A name or label associated with the controlled vocabulary from which the value of or is taken.">glyph.auth</span>, <span class="ident attribute" title="Glyph name.">glyph.name</span>, <span class="ident attribute" title="Numeric glyph reference in hexadecimal notation, e.g. &#34;#xE000&#34; or &#34;U+E000&#34;. N.B. SMuFL version 1.18 uses the range U+E000 - U+ECBF.">glyph.num</span>, <span class="ident attribute" title="glyph.name glyph.num The web-accessible location of the controlled vocabulary from which the value of or is taken.">glyph.uri</span>, <span class="ident attribute" title="Records a horizontal adjustment to a feature's programmatically-determined location in terms of staff interline distance; that is, in units of 1/2 the distance between adjacent staff lines.">ho</span>, <span class="ident attribute" title="Symbol rendered at end of line.">lendsym</span>, <span class="ident attribute" title="Holds the relative size of the line-end symbol.">lendsym.size</span>, <span class="ident attribute" title="Describes the line style of a line.">lform</span>, <span class="ident attribute" title="Describes the number of segments into which a dashed or dotted line may be divided, or the number of &#34;peaks&#34; of a wavy line; a pair of space-separated values (minimum and maximum, respectively) provides a range between which a rendering system-supplied value may fall, while a single value indicates a fixed amount of space; that is, the minimum and maximum values are equal.">lsegs</span>, <span class="ident attribute" title="Symbol rendered at start of line.">lstartsym</span>, <span class="ident attribute" title="Holds the relative size of the line-start symbol.">lstartsym.size</span>, <span class="ident attribute" title="Width of a line.">lwidth</span>, <span class="ident attribute" title="Records the horizontal adjustment of a feature's programmatically-determined start point.">startho</span>, <span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined start point.">startto</span>, <span class="ident attribute" title="Records a vertical adjustment of a feature's programmatically-determined start point.">startvo</span>, <span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined location in terms of musical time; that is, beats.">to</span>, <span class="ident attribute" title="Records the vertical adjustment of a feature's programmatically-determined location in terms of staff interline distance; that is, in units of 1/2 the distance between adjacent staff lines.">vo</span>, <span class="ident attribute" title="Encodes an x coordinate for a feature in an output coordinate system. When it is necessary to record the placement of a feature in a facsimile image, use the facs attribute.">x</span>, <span class="ident attribute" title="Encodes the optional 2nd x coordinate.">x2</span>, <span class="ident attribute" title="Encodes a y coordinate for a feature in an output coordinate system. When it is necessary to record the placement of a feature in a facsimile image, use the facs attribute.">y</span>, <span class="ident attribute" title="Encodes the optional 2nd y coordinate.">y2</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.usersymbols"><span class="ident attribute" title="symbolDef Provides a way of pointing to a user-defined symbol. It must contain a reference to an ID of a element elsewhere in the document.">altsym</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Provides a way of pointing to a user-defined symbol. It must contain a reference to
                        an
                        ID of a <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/symboldef.html">symbolDef</a> element elsewhere in the document.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to indicate visual appearance. Do not confuse this with the musical term 'color' as used in pre-CMN notation.">color</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to indicate visual appearance. Do not confuse this with the musical term 'color'
                        as used in pre-CMN notation.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.color.html">data.COLOR</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the horizontal adjustment of a feature's programmatically-determined end point.">endho</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the horizontal adjustment of a feature's programmatically-determined end
                        point.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined end point.">endto</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a timestamp adjustment of a feature's programmatically-determined end
                        point.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tstampoffset.html">data.TSTAMPOFFSET</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a vertical adjustment of a feature's programmatically-determined end point.">endvo</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a vertical adjustment of a feature's programmatically-determined end
                        point.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains the name of a font-family.">fontfam</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains the name of a font-family.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontfamily.html">data.FONTFAMILY</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the name of a font.">fontname</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the name of a font.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontname.html">data.FONTNAME</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch, relative terms, e.g., &#34;small&#34;, &#34;larger&#34;, etc., or percentage values relative to &#34;normal&#34; size, e.g., &#34;125%&#34;.">fontsize</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch,
                        relative terms, e.g., "small", "larger", etc., or percentage values relative to "normal"
                        size, e.g., "125%". </span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontsize.html">data.FONTSIZE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the style of a font, i.e, italic, oblique, or normal.">fontstyle</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the style of a font, i.e, italic, oblique, or normal.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontstyle.html">data.FONTSTYLE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to indicate bold type.">fontweight</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to indicate bold type.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontweight.html">data.FONTWEIGHT</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="glyph.name glyph.num A name or label associated with the controlled vocabulary from which the value of or is taken.">glyph.auth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A name or label associated with the controlled vocabulary from which the value of
                        <span class="att">glyph.name</span> or <span class="att">glyph.num</span> is taken.</span><span class="attributeValues">
                        Allowed values are:
                        "<span style="font-weight: 500;">smufl</span>" <i>(Standard Music Font Layout.)</i></span></div>
                  <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="Glyph name.">glyph.name</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Glyph name.</span><span class="attributeValues">
                        Value of datatype <span style="font-weight: 500;">string</span>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="Numeric glyph reference in hexadecimal notation, e.g. &#34;#xE000&#34; or &#34;U+E000&#34;. N.B. SMuFL version 1.18 uses the range U+E000 - U+ECBF.">glyph.num</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Numeric glyph reference in hexadecimal notation, e.g. "#xE000" or "U+E000". N.B. SMuFL
                        version 1.18 uses the range U+E000 - U+ECBF.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.hexnum.html">data.HEXNUM</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="glyph.name glyph.num The web-accessible location of the controlled vocabulary from which the value of or is taken.">glyph.uri</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">The web-accessible location of the controlled vocabulary from which the value of
                        <span class="att">glyph.name</span> or <span class="att">glyph.num</span> is taken.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a horizontal adjustment to a feature's programmatically-determined location in terms of staff interline distance; that is, in units of 1/2 the distance between adjacent staff lines.">ho</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a horizontal adjustment to a feature's programmatically-determined location
                        in
                        terms of staff interline distance; that is, in units of 1/2 the distance between adjacent
                        staff lines.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Symbol rendered at end of line.">lendsym</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Symbol rendered at end of line.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linestartendsymbol.html">data.LINESTARTENDSYMBOL</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the relative size of the line-end symbol.">lendsym.size</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the relative size of the line-end symbol.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontsizescale.html">data.FONTSIZESCALE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes the line style of a line.">lform</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the line style of a line.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.lineform.html">data.LINEFORM</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes the number of segments into which a dashed or dotted line may be divided, or the number of &#34;peaks&#34; of a wavy line; a pair of space-separated values (minimum and maximum, respectively) provides a range between which a rendering system-supplied value may fall, while a single value indicates a fixed amount of space; that is, the minimum and maximum values are equal.">lsegs</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the number of segments into which a dashed or dotted line may be divided,
                        or
                        the number of "peaks" of a wavy line; a pair of space-separated values (minimum and
                        maximum, respectively) provides a range between which a rendering system-supplied
                        value
                        may fall, while a single value indicates a fixed amount of space; that is, the minimum
                        and
                        maximum values are equal.</span><span class="attributeValues">
                        One or two values of datatype <span style="font-weight: 500;">
                           a positive integer no smaller than 2</span>, separated by a space.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Symbol rendered at start of line.">lstartsym</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Symbol rendered at start of line.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linestartendsymbol.html">data.LINESTARTENDSYMBOL</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the relative size of the line-start symbol.">lstartsym.size</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the relative size of the line-start symbol.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontsizescale.html">data.FONTSIZESCALE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Width of a line.">lwidth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Width of a line.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linewidth.html">data.LINEWIDTH</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the horizontal adjustment of a feature's programmatically-determined start point.">startho</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the horizontal adjustment of a feature's programmatically-determined start
                        point.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined start point.">startto</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a timestamp adjustment of a feature's programmatically-determined start
                        point.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tstampoffset.html">data.TSTAMPOFFSET</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a vertical adjustment of a feature's programmatically-determined start point.">startvo</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a vertical adjustment of a feature's programmatically-determined start
                        point.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined location in terms of musical time; that is, beats.">to</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a timestamp adjustment of a feature's programmatically-determined location
                        in
                        terms of musical time; that is, beats.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tstampoffset.html">data.TSTAMPOFFSET</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the vertical adjustment of a feature's programmatically-determined location in terms of staff interline distance; that is, in units of 1/2 the distance between adjacent staff lines.">vo</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the vertical adjustment of a feature's programmatically-determined location
                        in
                        terms of staff interline distance; that is, in units of 1/2 the distance between adjacent
                        staff lines.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes an x coordinate for a feature in an output coordinate system. When it is necessary to record the placement of a feature in a facsimile image, use the facs attribute.">x</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes an x coordinate for a feature in an output coordinate system. When it is
                        necessary to record the placement of a feature in a facsimile image, use the facs
                        attribute.</span><span class="attributeValues">
                        Value of datatype <span style="font-weight: 500;">decimal</span>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes the optional 2nd x coordinate.">x2</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the optional 2nd x coordinate.</span><span class="attributeValues">
                        Value of datatype <span style="font-weight: 500;">decimal</span>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes a y coordinate for a feature in an output coordinate system. When it is necessary to record the placement of a feature in a facsimile image, use the facs attribute.">y</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes a y coordinate for a feature in an output coordinate system. When it is
                        necessary to record the placement of a feature in a facsimile image, use the facs
                        attribute.</span><span class="attributeValues">
                        Value of datatype <span style="font-weight: 500;">decimal</span>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes the optional 2nd y coordinate.">y2</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the optional 2nd y coordinate.</span><span class="attributeValues">
                        Value of datatype <span style="font-weight: 500;">decimal</span>.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.altSym">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.altsym.html">att.altSym</a></label><span class="classDesc">(MEI.usersymbols) Attributes supplying pointers to user-defined symbols.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.usersymbols"><span class="ident attribute" title="symbolDef Provides a way of pointing to a user-defined symbol. It must contain a reference to an ID of a element elsewhere in the document.">altsym</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Provides a way of pointing to a user-defined symbol. It must contain a reference to
                              an
                              ID of a <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/symboldef.html">symbolDef</a> element elsewhere in the document.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.color">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.color.html">att.color</a></label><span class="classDesc">(MEI.shared) Visual color attributes.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to indicate visual appearance. Do not confuse this with the musical term 'color' as used in pre-CMN notation.">color</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to indicate visual appearance. Do not confuse this with the musical term 'color'
                              as used in pre-CMN notation.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.color.html">data.COLOR</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.extSym">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.extsym.html">att.extSym</a></label><span class="classDesc">(MEI.externalsymbols) Attributes used to associate MEI features with corresponding
                           glyphs in an externally-defined standard such as SMuFL.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="glyph.name glyph.num A name or label associated with the controlled vocabulary from which the value of or is taken.">glyph.auth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A name or label associated with the controlled vocabulary from which the value of
                              <span class="att">glyph.name</span> or <span class="att">glyph.num</span> is taken.</span><span class="attributeValues">
                              Allowed values are:
                              "<span style="font-weight: 500;">smufl</span>" <i>(Standard Music Font Layout.)</i></span></div>
                        <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="Glyph name.">glyph.name</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Glyph name.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">string</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="Numeric glyph reference in hexadecimal notation, e.g. &#34;#xE000&#34; or &#34;U+E000&#34;. N.B. SMuFL version 1.18 uses the range U+E000 - U+ECBF.">glyph.num</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Numeric glyph reference in hexadecimal notation, e.g. "#xE000" or "U+E000". N.B. SMuFL
                              version 1.18 uses the range U+E000 - U+ECBF.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.hexnum.html">data.HEXNUM</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="glyph.name glyph.num The web-accessible location of the controlled vocabulary from which the value of or is taken.">glyph.uri</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">The web-accessible location of the controlled vocabulary from which the value of
                              <span class="att">glyph.name</span> or <span class="att">glyph.num</span> is taken.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.lineRend">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linerend.html">att.lineRend</a></label><span class="classDesc">(MEI.shared) Attributes that record the visual rendition of lines.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Symbol rendered at end of line.">lendsym</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Symbol rendered at end of line.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linestartendsymbol.html">data.LINESTARTENDSYMBOL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the relative size of the line-end symbol.">lendsym.size</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the relative size of the line-end symbol.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontsizescale.html">data.FONTSIZESCALE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Symbol rendered at start of line.">lstartsym</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Symbol rendered at start of line.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linestartendsymbol.html">data.LINESTARTENDSYMBOL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the relative size of the line-start symbol.">lstartsym.size</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the relative size of the line-start symbol.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontsizescale.html">data.FONTSIZESCALE</a>.
                              </span></div>
                        <div class="classBox" title="att.lineRend.base">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linerend.base.html">att.lineRend.base</a></label><span class="classDesc">(MEI.shared) Attributes that record the basic visual rendition of lines.</span></div>
                           <div class="classContent">
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes the line style of a line.">lform</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the line style of a line.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.lineform.html">data.LINEFORM</a>.
                                    </span></div>
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes the number of segments into which a dashed or dotted line may be divided, or the number of &#34;peaks&#34; of a wavy line; a pair of space-separated values (minimum and maximum, respectively) provides a range between which a rendering system-supplied value may fall, while a single value indicates a fixed amount of space; that is, the minimum and maximum values are equal.">lsegs</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the number of segments into which a dashed or dotted line may be divided,
                                    or
                                    the number of "peaks" of a wavy line; a pair of space-separated values (minimum and
                                    maximum, respectively) provides a range between which a rendering system-supplied
                                    value
                                    may fall, while a single value indicates a fixed amount of space; that is, the minimum
                                    and
                                    maximum values are equal.</span><span class="attributeValues">
                                    One or two values of datatype <span style="font-weight: 500;">
                                       a positive integer no smaller than 2</span>, separated by a space.
                                    </span></div>
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Width of a line.">lwidth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Width of a line.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linewidth.html">data.LINEWIDTH</a>.
                                    </span></div>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="classBox" title="att.typography">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.typography.html">att.typography</a></label><span class="classDesc">(MEI.shared) Typographical attributes.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains the name of a font-family.">fontfam</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains the name of a font-family.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontfamily.html">data.FONTFAMILY</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the name of a font.">fontname</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the name of a font.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontname.html">data.FONTNAME</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch, relative terms, e.g., &#34;small&#34;, &#34;larger&#34;, etc., or percentage values relative to &#34;normal&#34; size, e.g., &#34;125%&#34;.">fontsize</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch,
                              relative terms, e.g., "small", "larger", etc., or percentage values relative to "normal"
                              size, e.g., "125%". </span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontsize.html">data.FONTSIZE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the style of a font, i.e, italic, oblique, or normal.">fontstyle</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the style of a font, i.e, italic, oblique, or normal.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontstyle.html">data.FONTSTYLE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to indicate bold type.">fontweight</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to indicate bold type.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontweight.html">data.FONTWEIGHT</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.visualOffset">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset.html">att.visualOffset</a></label><span class="classDesc">(MEI.shared) Visual offset attributes. Some items may have their location recorded
                           in terms of offsets from their programmatically-determined location. The ho attribute
                           records the horizontal offset while vo records the vertical. The to attribute holds
                           a timestamp offset, the most common use of which is as an alternative to the ho attribute.</span></div>
                     <div class="classContent">
                        <div class="classBox" title="att.visualOffset.ho">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset.ho.html">att.visualOffset.ho</a></label><span class="classDesc">(MEI.shared) Horizontal offset attributes.</span></div>
                           <div class="classContent">
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a horizontal adjustment to a feature's programmatically-determined location in terms of staff interline distance; that is, in units of 1/2 the distance between adjacent staff lines.">ho</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a horizontal adjustment to a feature's programmatically-determined location
                                    in
                                    terms of staff interline distance; that is, in units of 1/2 the distance between adjacent
                                    staff lines.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                                    </span></div>
                           </div>
                        </div>
                        <div class="classBox" title="att.visualOffset.to">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset.to.html">att.visualOffset.to</a></label><span class="classDesc">(MEI.shared) Horizontal offset attributes specified in terms of time.</span></div>
                           <div class="classContent">
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined location in terms of musical time; that is, beats.">to</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a timestamp adjustment of a feature's programmatically-determined location
                                    in
                                    terms of musical time; that is, beats.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tstampoffset.html">data.TSTAMPOFFSET</a>.
                                    </span></div>
                           </div>
                        </div>
                        <div class="classBox" title="att.visualOffset.vo">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset.vo.html">att.visualOffset.vo</a></label><span class="classDesc">(MEI.shared) Vertical offset attributes.</span></div>
                           <div class="classContent">
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the vertical adjustment of a feature's programmatically-determined location in terms of staff interline distance; that is, in units of 1/2 the distance between adjacent staff lines.">vo</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the vertical adjustment of a feature's programmatically-determined location
                                    in
                                    terms of staff interline distance; that is, in units of 1/2 the distance between adjacent
                                    staff lines.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                                    </span></div>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="classBox" title="att.visualOffset2">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset2.html">att.visualOffset2</a></label><span class="classDesc">(MEI.shared) Visual offset attributes. Some items may have their location recorded
                           in terms of pairs of offsets from their programmatically-determined location. The
                           startho and endho attributes record the horizontal offsets of the start and end points
                           of the item, respectively. Similarly, the startvo and endvo attributes record the
                           vertical offsets of the start and end points of the item. The startto and endto attributes
                           hold timestamp offsets, the most common use of which is as alternatives to the ho
                           attributes.</span></div>
                     <div class="classContent">
                        <div class="classBox" title="att.visualOffset2.ho">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset2.ho.html">att.visualOffset2.ho</a></label><span class="classDesc">(MEI.shared) Horizontal offset requiring a pair of attributes.</span></div>
                           <div class="classContent">
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the horizontal adjustment of a feature's programmatically-determined start point.">startho</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the horizontal adjustment of a feature's programmatically-determined start
                                    point.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                                    </span></div>
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the horizontal adjustment of a feature's programmatically-determined end point.">endho</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the horizontal adjustment of a feature's programmatically-determined end
                                    point.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                                    </span></div>
                           </div>
                        </div>
                        <div class="classBox" title="att.visualOffset2.to">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset2.to.html">att.visualOffset2.to</a></label><span class="classDesc">(MEI.shared) Horizontal offset attributes requiring a pair of attributes specified
                                 in terms of time.</span></div>
                           <div class="classContent">
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined start point.">startto</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a timestamp adjustment of a feature's programmatically-determined start
                                    point.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tstampoffset.html">data.TSTAMPOFFSET</a>.
                                    </span></div>
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined end point.">endto</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a timestamp adjustment of a feature's programmatically-determined end
                                    point.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tstampoffset.html">data.TSTAMPOFFSET</a>.
                                    </span></div>
                           </div>
                        </div>
                        <div class="classBox" title="att.visualOffset2.vo">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset2.vo.html">att.visualOffset2.vo</a></label><span class="classDesc">(MEI.shared) Vertical offset attributes requiring a pair of attributes.</span></div>
                           <div class="classContent">
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a vertical adjustment of a feature's programmatically-determined start point.">startvo</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a vertical adjustment of a feature's programmatically-determined start
                                    point.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                                    </span></div>
                              <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a vertical adjustment of a feature's programmatically-determined end point.">endvo</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a vertical adjustment of a feature's programmatically-determined end
                                    point.</span><span class="attributeValues">
                                    Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                                    </span></div>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="classBox" title="att.xy">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.xy.html">att.xy</a></label><span class="classDesc">(MEI.shared) Output coordinate attributes. Some elements may have their exact rendered
                           *output* coordinates recorded. x and y attributes indicate where to place the rendered
                           output. Recording the coordinates of a feature in a facsimile requires the use of
                           the facs attribute.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes an x coordinate for a feature in an output coordinate system. When it is necessary to record the placement of a feature in a facsimile image, use the facs attribute.">x</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes an x coordinate for a feature in an output coordinate system. When it is
                              necessary to record the placement of a feature in a facsimile image, use the facs
                              attribute.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes a y coordinate for a feature in an output coordinate system. When it is necessary to record the placement of a feature in a facsimile image, use the facs attribute.">y</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes a y coordinate for a feature in an output coordinate system. When it is
                              necessary to record the placement of a feature in a facsimile image, use the facs
                              attribute.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="att.xy2">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.xy2.html">att.xy2</a></label><span class="classDesc">(MEI.shared) Output coordinate attributes. Some elements may need 2 coordinate pairs
                           to record their rendered *output* coordinates. The attributes indicate where to place
                           the rendered output. Recording the coordinates of a feature in a facsimile requires
                           the use of the facs attribute.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes the optional 2nd x coordinate.">x2</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the optional 2nd x coordinate.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes the optional 2nd y coordinate.">y2</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the optional 2nd y coordinate.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.externalsymbols">
                     <div class="classHeading"><label class="classLabel">MEI.externalsymbols</label><span class="classDesc">External symbols component declarations.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="glyph.name glyph.num A name or label associated with the controlled vocabulary from which the value of or is taken.">glyph.auth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">A name or label associated with the controlled vocabulary from which the value of
                              <span class="att">glyph.name</span> or <span class="att">glyph.num</span> is taken.</span><span class="attributeValues">
                              Allowed values are:
                              "<span style="font-weight: 500;">smufl</span>" <i>(Standard Music Font Layout.)</i></span></div>
                        <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="Glyph name.">glyph.name</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Glyph name.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">string</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="Numeric glyph reference in hexadecimal notation, e.g. &#34;#xE000&#34; or &#34;U+E000&#34;. N.B. SMuFL version 1.18 uses the range U+E000 - U+ECBF.">glyph.num</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Numeric glyph reference in hexadecimal notation, e.g. "#xE000" or "U+E000". N.B. SMuFL
                              version 1.18 uses the range U+E000 - U+ECBF.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.hexnum.html">data.HEXNUM</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.externalsymbols"><span class="ident attribute" title="glyph.name glyph.num The web-accessible location of the controlled vocabulary from which the value of or is taken.">glyph.uri</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">The web-accessible location of the controlled vocabulary from which the value of
                              <span class="att">glyph.name</span> or <span class="att">glyph.num</span> is taken.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc">Component declarations that are shared between two or more modules.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to indicate visual appearance. Do not confuse this with the musical term 'color' as used in pre-CMN notation.">color</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to indicate visual appearance. Do not confuse this with the musical term 'color'
                              as used in pre-CMN notation.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.color.html">data.COLOR</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the horizontal adjustment of a feature's programmatically-determined end point.">endho</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the horizontal adjustment of a feature's programmatically-determined end
                              point.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined end point.">endto</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a timestamp adjustment of a feature's programmatically-determined end
                              point.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tstampoffset.html">data.TSTAMPOFFSET</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a vertical adjustment of a feature's programmatically-determined end point.">endvo</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a vertical adjustment of a feature's programmatically-determined end
                              point.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Contains the name of a font-family.">fontfam</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Contains the name of a font-family.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontfamily.html">data.FONTFAMILY</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the name of a font.">fontname</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the name of a font.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontname.html">data.FONTNAME</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch, relative terms, e.g., &#34;small&#34;, &#34;larger&#34;, etc., or percentage values relative to &#34;normal&#34; size, e.g., &#34;125%&#34;.">fontsize</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch,
                              relative terms, e.g., "small", "larger", etc., or percentage values relative to "normal"
                              size, e.g., "125%". </span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontsize.html">data.FONTSIZE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the style of a font, i.e, italic, oblique, or normal.">fontstyle</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the style of a font, i.e, italic, oblique, or normal.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontstyle.html">data.FONTSTYLE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Used to indicate bold type.">fontweight</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Used to indicate bold type.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontweight.html">data.FONTWEIGHT</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a horizontal adjustment to a feature's programmatically-determined location in terms of staff interline distance; that is, in units of 1/2 the distance between adjacent staff lines.">ho</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a horizontal adjustment to a feature's programmatically-determined location
                              in
                              terms of staff interline distance; that is, in units of 1/2 the distance between adjacent
                              staff lines.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Symbol rendered at end of line.">lendsym</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Symbol rendered at end of line.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linestartendsymbol.html">data.LINESTARTENDSYMBOL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the relative size of the line-end symbol.">lendsym.size</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the relative size of the line-end symbol.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontsizescale.html">data.FONTSIZESCALE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes the line style of a line.">lform</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the line style of a line.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.lineform.html">data.LINEFORM</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Describes the number of segments into which a dashed or dotted line may be divided, or the number of &#34;peaks&#34; of a wavy line; a pair of space-separated values (minimum and maximum, respectively) provides a range between which a rendering system-supplied value may fall, while a single value indicates a fixed amount of space; that is, the minimum and maximum values are equal.">lsegs</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the number of segments into which a dashed or dotted line may be divided,
                              or
                              the number of "peaks" of a wavy line; a pair of space-separated values (minimum and
                              maximum, respectively) provides a range between which a rendering system-supplied
                              value
                              may fall, while a single value indicates a fixed amount of space; that is, the minimum
                              and
                              maximum values are equal.</span><span class="attributeValues">
                              One or two values of datatype <span style="font-weight: 500;">
                                 a positive integer no smaller than 2</span>, separated by a space.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Symbol rendered at start of line.">lstartsym</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Symbol rendered at start of line.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linestartendsymbol.html">data.LINESTARTENDSYMBOL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Holds the relative size of the line-start symbol.">lstartsym.size</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Holds the relative size of the line-start symbol.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.fontsizescale.html">data.FONTSIZESCALE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Width of a line.">lwidth</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Width of a line.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.linewidth.html">data.LINEWIDTH</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the horizontal adjustment of a feature's programmatically-determined start point.">startho</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the horizontal adjustment of a feature's programmatically-determined start
                              point.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined start point.">startto</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a timestamp adjustment of a feature's programmatically-determined start
                              point.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tstampoffset.html">data.TSTAMPOFFSET</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a vertical adjustment of a feature's programmatically-determined start point.">startvo</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a vertical adjustment of a feature's programmatically-determined start
                              point.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records a timestamp adjustment of a feature's programmatically-determined location in terms of musical time; that is, beats.">to</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records a timestamp adjustment of a feature's programmatically-determined location
                              in
                              terms of musical time; that is, beats.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tstampoffset.html">data.TSTAMPOFFSET</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Records the vertical adjustment of a feature's programmatically-determined location in terms of staff interline distance; that is, in units of 1/2 the distance between adjacent staff lines.">vo</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Records the vertical adjustment of a feature's programmatically-determined location
                              in
                              terms of staff interline distance; that is, in units of 1/2 the distance between adjacent
                              staff lines.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurementrel.html">data.MEASUREMENTREL</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes an x coordinate for a feature in an output coordinate system. When it is necessary to record the placement of a feature in a facsimile image, use the facs attribute.">x</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes an x coordinate for a feature in an output coordinate system. When it is
                              necessary to record the placement of a feature in a facsimile image, use the facs
                              attribute.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes the optional 2nd x coordinate.">x2</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the optional 2nd x coordinate.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes a y coordinate for a feature in an output coordinate system. When it is necessary to record the placement of a feature in a facsimile image, use the facs attribute.">y</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes a y coordinate for a feature in an output coordinate system. When it is
                              necessary to record the placement of a feature in a facsimile image, use the facs
                              attribute.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Encodes the optional 2nd y coordinate.">y2</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Encodes the optional 2nd y coordinate.</span><span class="attributeValues">
                              Value of datatype <span style="font-weight: 500;">decimal</span>.
                              </span></div>
                     </div>
                  </div>
                  <div class="classBox" title="MEI.usersymbols">
                     <div class="classHeading"><label class="classLabel">MEI.usersymbols</label><span class="classDesc">User-defined symbols component declarations.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.usersymbols"><span class="ident attribute" title="symbolDef Provides a way of pointing to a user-defined symbol. It must contain a reference to an ID of a element elsewhere in the document.">altsym</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Provides a way of pointing to a user-defined symbol. It must contain a reference to
                              an
                              ID of a <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/symboldef.html">symbolDef</a> element elsewhere in the document.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                              </span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet availableAt" id="availableAt">
            <div class="label">Available at</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="availableAt_compact_tab" href="#availableAt" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="class" id="availableAt_class_tab" href="#availableAt" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="availableAt_module_tab" href="#availableAt" class="displayTab">by module</a></li>
               </ul>
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="Marks a sequence of notational events grouped by a bracket."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/bracketspan.html">bracketSpan</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.bracketSpan.vis">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.bracketspan.vis.html">att.bracketSpan.vis</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.cmn"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/bracketspan.html">bracketSpan</a><span class="elementDesc">Marks a sequence of notational events grouped by a bracket.</span></div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.cmn">
                     <div class="classHeading"><label class="classLabel">MEI.cmn</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.cmn"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/bracketspan.html">bracketSpan</a><span class="elementDesc">Marks a sequence of notational events grouped by a bracket.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.bracketSpan.vis"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.visual"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Visual domain attributes.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;classes&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.altsym.html">att.altSym</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.color.html">att.color</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.extsym.html">att.extSym</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linerend.html">att.lineRend</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.typography.html">att.typography</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset.html">att.visualOffset</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.visualoffset2.html">att.visualOffset2</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.xy.html">att.xy</a>"</span></span>/&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;memberOf
                                 <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.xy2.html">att.xy2</a>"</span></span>/&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/classes&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/classSpec&gt;</span></div></code></div>
            </div>
         </div>
      </div><script type="text/javascript">
            
            var tabbedFacets = document.querySelectorAll('.facet ul.tab');
            
            var tabClick = function(e) {
                var style = e.target.getAttribute('data-display');
                var facetId = e.target.parentNode.parentNode.parentNode.parentNode.id;
                setTabs(facetId,style)
            }
            
            for(var facetUl of tabbedFacets) {
                var facetElem = facetUl.parentNode.parentNode;
                var facetId = facetElem.id;
                var storageName = 'meiSpecs_' + facetId + '_display';
                var defaultValue = facetUl.children[0].children[0].getAttribute('data-display');
                
                if(localStorage.getItem(storageName) === null) {
                    setTabs(facetElem.id,defaultValue);
                } else {
                    setTabs(facetElem.id,localStorage.getItem(storageName));
                }
                
                var tabs = facetUl.querySelectorAll('.tab-item a');
                
                for(var tab of tabs) {
                    tab.addEventListener('click',tabClick);
                }
                
            }
            
            function setTabs(facetId,style) {
                
                var storageName = 'meiSpecs_' + facetId + '_display';
                localStorage.setItem(storageName,style);
                
                var facetElem = document.getElementById(facetId);
                
                var oldTab = facetElem.querySelector('.displayTab.active');
                oldTab.classList.remove('active');
                
                var newTab = document.getElementById(facetId + '_' + style + '_tab');
                newTab.classList.add('active');
                
                var oldBox = facetElem.querySelector('.active.facetTabbedContent');
                oldBox.classList.remove('active');
                oldBox.style.display = 'none';
                
                var newBox = document.getElementById(facetId + '_tabbedContent_' + style);
                newBox.classList.add('active');
                newBox.style.display = 'block';
                
            }
        </script></div>
</div>