---
layout: sidebar
sidebar: s1
version: "v3"
title: "att.scoreDef.log"
---
<div class="classSpec att">
   <h3 id="att.scoreDef.log">att.scoreDef.log</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Logical domain attributes for scoreDef in the CMN repertoire. The values set in these
            attributes act as score-wide defaults for attributes that are not set in descendant
            elements.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.shared</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Members</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a> (direct member of att.scoreDef.log)
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <div class="attributeDef"><span class="attribute"><strong>@beam.group</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Provides an example of how automated beaming (including secondary beams) is to be
                  performed.</span>
               Value of datatype <span style="font-weight: 500;">string</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beaming.log.html">att.beaming.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@beam.rests</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates whether automatically-drawn beams should include rests shorter than a
                  quarter note duration.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.boolean.html">data.BOOLEAN</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beaming.log.html">att.beaming.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@clef.dis</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Records the amount of octave displacement to be applied to the clef.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.octave.dis.html">data.OCTAVE.DIS</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.cleffing.log.html">att.cleffing.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@clef.dis.place</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Records the direction of octave displacement to be applied to the clef.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.place.html">data.PLACE</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.cleffing.log.html">att.cleffing.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@clef.line</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains a default value for the position of the clef. The value must be in the
                  range between 1 and the number of lines on the staff. The numbering of lines starts
                  with
                  the lowest line of the staff.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.clefline.html">data.CLEFLINE</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.cleffing.log.html">att.cleffing.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@clef.shape</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Encodes a value for the clef symbol.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.clefshape.html">data.CLEFSHAPE</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.cleffing.log.html">att.cleffing.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@dur.default</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains a default duration in those situations when the first note, rest, chord,
                  etc. in a measure does not have a duration specified.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.duration.html">data.DURATION</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.duration.default.html">att.duration.default</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@key.accid</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains an accidental for the tonic key, if one is required, e.g., if key.pname
                  equals 'c' and key.accid equals 's', then a tonic of C# is indicated.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.accidental.implicit.html">data.ACCIDENTAL.IMPLICIT</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.keysigdefault.log.html">att.keySigDefault.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@key.mode</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates major, minor, or other tonality.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.mode.html">data.MODE</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.keysigdefault.log.html">att.keySigDefault.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@key.pname</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Holds the pitch name of the tonic key, e.g. 'c' for the key of C.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.pitchname.html">data.PITCHNAME</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.keysigdefault.log.html">att.keySigDefault.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@key.sig</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates where the key lies in the circle of fifths.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.keysignature.html">data.KEYSIGNATURE</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.keysigdefault.log.html">att.keySigDefault.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@key.sig.mixed</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Mixed key signatures, e.g. those consisting of a mixture of flats and sharps (Read,
                  p. 143, ex. 9-39), and key signatures with unorthodox placement of the accidentals
                  (Read, p. 141) must be indicated by setting the key.sig attribute to 'mixed' and
                  providing explicit key signature information in the key.sig.mixed attribute or in
                  the
                  &lt;keySig&gt; element. It is intended that key.sig.mixed contain a series of tokens
                  with each token containing pitch name, accidental, and octave, such as 'a4 c5s e5f'
                  that
                  indicate what key accidentals should be rendered and where they should be placed.</span>
               One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.keysigtoken.html">data.KEYSIGTOKEN</a>, separated by spaces.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.keysigdefault.log.html">att.keySigDefault.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@mensur.dot</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Determines if a dot is to be added to the base symbol.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.boolean.html">data.BOOLEAN</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensural.log.html">att.mensural.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@mensur.sign</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">The base symbol in the mensuration sign/time signature of mensural notation.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.mensurationsign.html">data.MENSURATIONSIGN</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensural.log.html">att.mensural.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@mensur.slash</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates the number lines added to the mensuration sign. For example, one slash is
                  added for what we now call 'alla breve'.</span>
               Value of datatype <span style="font-weight: 500;">positiveInteger</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensural.log.html">att.mensural.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@meter.count</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Captures the number of beats in a measure, that is, the top number of the meter
                  signature. It must contain a decimal number or an additive expression that evaluates
                  to
                  a decimal number, such as 2+3.</span>
               Value of datatype <span style="font-weight: 500;">
                  a string matching the following regular expression: "\d+(\.\d+)?(\s*\+\s*\d+(\.\d+)?)*"
                  </span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.metersigdefault.log.html">att.meterSigDefault.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@meter.unit</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains the number indicating the beat unit, that is, the bottom number of the
                  meter signature.</span>
               Value of datatype <span style="font-weight: 500;">decimal</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.metersigdefault.log.html">att.meterSigDefault.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@modusmaior</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Describes the maxima-long relationship.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.modusmaior.html">data.MODUSMAIOR</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensural.shared.html">att.mensural.shared</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@modusminor</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Describes the long-breve relationship.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.modusminor.html">data.MODUSMINOR</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensural.shared.html">att.mensural.shared</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@num.default</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Along with numbase.default, describes the default duration as a ratio. num.default
                  is the first value in the ratio.</span>
               Value of datatype <span style="font-weight: 500;">positiveInteger</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.duration.default.html">att.duration.default</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@numbase.default</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Along with num.default, describes the default duration as a ratio. numbase.default
                  is the second value in the ratio.</span>
               Value of datatype <span style="font-weight: 500;">positiveInteger</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.duration.default.html">att.duration.default</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@octave.default</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains a default octave specification for use when the first note, rest, chord,
                  etc. in a measure does not have an octave value specified.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.octave.html">data.OCTAVE</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.octavedefault.html">att.octavedefault</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@prolatio</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Describes the semibreve-minim relationship.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.prolatio.html">data.PROLATIO</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensural.shared.html">att.mensural.shared</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@proport.num</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Together, proport.num and proport.numbase specify a proportional change as a ratio,
                  e.g., 1:3. Proport.num is for the first value in the ratio.</span>
               Value of datatype <span style="font-weight: 500;">positiveInteger</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensural.log.html">att.mensural.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@proport.numbase</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Together, proport.num and proport.numbase specify a proportional change as a ratio,
                  e.g., 1:3. Proport.numbase is for the second value in the ratio.</span>
               Value of datatype <span style="font-weight: 500;">positiveInteger</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensural.log.html">att.mensural.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@tempus</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Describes the breve-semibreve relationship.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.tempus.html">data.TEMPUS</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mensural.shared.html">att.mensural.shared</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@trans.diat</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Records the amount of diatonic pitch shift, e.g., C to C♯ = 0, C to D♭ = 1,
                  necessary to calculate the sounded pitch from the written one.</span>
               Value of datatype <span style="font-weight: 500;">decimal</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.transposition.html">att.transposition</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@trans.semi</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Records the amount of pitch shift in semitones, e.g., C to C♯ = 1, C to D♭ = 1,
                  necessary to calculate the sounded pitch from the written one.</span>
               Value of datatype <span style="font-weight: 500;">decimal</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.transposition.html">att.transposition</a></span></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classes&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.cleffing.log.html">att.cleffing.log</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.duration.default.html">att.duration.default</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.keysigdefault.log.html">att.keySigDefault.log</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.metersigdefault.log.html">att.meterSigDefault.log</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.octavedefault.html">att.octavedefault</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.transposition.html">att.transposition</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.scoredef.log.cmn.html">att.scoreDef.log.cmn</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.scoredef.log.mensural.html">att.scoreDef.log.mensural</a>"</span></span>/&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/classes&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>