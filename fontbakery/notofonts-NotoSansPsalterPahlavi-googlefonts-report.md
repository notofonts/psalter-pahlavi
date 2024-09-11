## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[2] NotoSansPsalterPahlavi-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check tabular widths don't have kerning. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Kerning between uni00A0 and zero is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between zero and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between uni00A0 and one is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between uni00A0 and two is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between two and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between uni00A0 and three is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between three and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between uni00A0 and four is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between four and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between uni00A0 and five is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between five and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between uni00A0 and six is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between six and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between uni00A0 and seven is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between seven and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between uni00A0 and eight is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between eight and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between uni00A0 and nine is 1, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between nine and uni00A0 is 1, should be 0</p>
 [code: has-tabular-kerning]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 944, but got 737 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[12] NotoSansPsalterPahlavi-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that texts shape as per expectation <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>qa/shaping_tests/psalter-pahlavi.json: Expected and actual shaping not matching</p>
<ul>
<li>
<p>Shaping did not match: 𐮮𐮬𐮫 𐮯𐮬𐮫 (#1, see examples in Unicode standard)</p>
<pre><code>Expected: None
Got     : threepp=6+910|fourpp.alt=5+1159|hundredpp=4+1248|space=3+260|threepp=2+910|fourpp.alt.fina=1+1159|twentypp.init=0+567
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -554 6213 1291" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g66" d="M90.0,-220.0Q74.0,-220.0 61.5,-214.5Q49.0,-209.0 49.0,-199.0Q49.0,-198.0 49.0,-196.0Q49.0,-194.0 50.0,-192.0L158.0,417.0Q160.0,429.0 175.0,434.0Q190.0,439.0 207.0,439.0Q222.0,439.0 234.0,434.5Q246.0,430.0 246.0,419.0Q246.0,416.0 244.0,406.0L187.0,84.0L339.0,84.0Q373.0,84.0 392.5,99.5Q412.0,115.0 419.0,157.0L465.0,416.0Q467.0,429.0 481.5,434.0Q496.0,439.0 511.0,439.0Q528.0,439.0 541.0,433.5Q554.0,428.0 554.0,418.0Q554.0,416.0 553.0,411.0L508.0,160.0Q500.0,116.0 482.0,84.0L647.0,84.0Q681.0,84.0 700.5,99.5Q720.0,115.0 727.0,157.0L773.0,416.0Q775.0,429.0 789.0,434.0Q803.0,439.0 818.0,439.0Q835.0,439.0 848.0,433.5Q861.0,428.0 861.0,418.0Q861.0,413.0 860.0,411.0L815.0,160.0Q802.0,85.0 759.0,42.5Q716.0,0.0 635.0,0.0L172.0,0.0L137.0,-197.0Q135.0,-208.0 121.0,-214.0Q107.0,-220.0 90.0,-220.0Z"/> <path id="g80" d="M47.0,0.0Q37.0,0.0 30.5,10.0Q24.0,20.0 24.0,36.0Q24.0,55.0 32.0,69.5Q40.0,84.0 57.0,84.0L63.0,84.0Q96.0,84.0 116.0,99.5Q136.0,115.0 143.0,157.0L188.0,416.0Q190.0,429.0 204.5,434.0Q219.0,439.0 234.0,439.0Q251.0,439.0 263.5,433.5Q276.0,428.0 276.0,418.0Q276.0,417.0 276.0,415.0Q276.0,413.0 275.0,411.0L231.0,160.0Q227.0,138.0 220.5,119.0Q214.0,100.0 206.0,84.0L343.0,84.0Q375.0,84.0 393.5,100.5Q412.0,117.0 419.0,157.0L465.0,416.0Q467.0,429.0 481.5,434.0Q496.0,439.0 511.0,439.0Q528.0,439.0 540.5,433.5Q553.0,428.0 553.0,418.0Q553.0,417.0 553.0,415.0Q553.0,413.0 552.0,411.0L508.0,160.0Q500.0,116.0 482.0,84.0L621.0,84.0Q653.0,84.0 672.0,100.5Q691.0,117.0 698.0,157.0L744.0,416.0Q746.0,429.0 760.0,434.0Q774.0,439.0 789.0,439.0Q806.0,439.0 819.0,433.5Q832.0,428.0 832.0,418.0Q832.0,416.0 831.0,411.0L786.0,160.0Q782.0,138.0 775.5,119.0Q769.0,100.0 761.0,84.0L896.0,84.0Q930.0,84.0 949.5,99.5Q969.0,115.0 976.0,157.0L1022.0,416.0Q1024.0,429.0 1038.0,434.0Q1052.0,439.0 1067.0,439.0Q1084.0,439.0 1097.0,433.5Q1110.0,428.0 1110.0,418.0Q1110.0,415.0 1109.0,411.0L1064.0,160.0Q1051.0,85.0 1008.0,42.5Q965.0,0.0 884.0,0.0L47.0,0.0Z"/> <path id="g70" d="M493.0,0.0Q482.0,0.0 476.0,13.0Q470.0,26.0 470.0,42.0Q470.0,58.0 475.5,71.0Q481.0,84.0 493.0,84.0L713.0,84.0Q749.0,84.0 762.0,95.0Q775.0,106.0 775.0,124.0Q775.0,138.0 769.5,156.0Q764.0,174.0 757.0,193.0L677.0,407.0Q675.0,413.0 675.0,416.0Q675.0,426.0 684.0,432.5Q693.0,439.0 715.0,439.0Q733.0,439.0 745.5,432.5Q758.0,426.0 762.0,416.0L844.0,196.0Q855.0,167.0 861.5,142.0Q868.0,117.0 868.0,95.0Q868.0,49.0 832.0,24.5Q796.0,0.0 707.0,0.0L493.0,0.0ZM48.0,-148.0Q37.0,-148.0 30.5,-134.5Q24.0,-121.0 24.0,-105.0Q24.0,-90.0 30.0,-77.0Q36.0,-64.0 48.0,-64.0L270.0,-64.0Q309.0,-64.0 324.0,-54.0Q339.0,-44.0 339.0,-27.0Q339.0,-16.0 334.5,-1.5Q330.0,13.0 323.0,29.0L293.0,105.0Q284.0,127.0 279.0,143.5Q274.0,160.0 274.0,175.0Q274.0,196.0 287.5,215.5Q301.0,235.0 335.0,259.0L536.0,401.0Q540.0,404.0 546.0,404.0Q560.0,404.0 574.0,390.0Q588.0,376.0 588.0,359.0Q588.0,341.0 571.0,330.0L392.0,203.0Q361.0,180.0 361.0,162.0Q361.0,155.0 364.0,145.5Q367.0,136.0 371.0,125.0L417.0,1.0Q423.0,-16.0 426.5,-32.0Q430.0,-48.0 430.0,-62.0Q430.0,-102.0 397.5,-125.0Q365.0,-148.0 294.0,-148.0L48.0,-148.0ZM751.0,-195.0Q671.0,-195.0 620.5,-188.0Q570.0,-181.0 543.5,-173.0Q517.0,-165.0 508.0,-161.0Q498.0,-156.0 491.0,-146.0Q484.0,-136.0 484.0,-120.0Q484.0,-105.0 490.0,-92.0Q496.0,-79.0 508.0,-79.0Q513.0,-79.0 523.5,-80.5Q534.0,-82.0 546.0,-86.0Q569.0,-93.0 616.0,-102.0Q663.0,-111.0 749.0,-111.0Q869.0,-111.0 941.0,-87.0Q1013.0,-63.0 1047.0,-16.0Q1081.0,31.0 1086.0,99.0Q974.0,99.0 928.0,138.5Q882.0,178.0 882.0,241.0Q882.0,298.0 918.0,337.5Q954.0,377.0 1020.0,377.0Q1087.0,377.0 1130.5,322.0Q1174.0,267.0 1174.0,162.0L1174.0,131.0Q1174.0,40.0 1129.5,-34.0Q1085.0,-108.0 992.0,-151.5Q899.0,-195.0 751.0,-195.0ZM1086.0,176.0Q1086.0,224.0 1068.5,258.5Q1051.0,293.0 1011.0,293.0Q995.0,293.0 980.5,281.0Q966.0,269.0 966.0,244.0Q966.0,227.0 975.5,211.0Q985.0,195.0 1011.0,185.5Q1037.0,176.0 1086.0,176.0Z"/> <path id="g3" d=""/> <path id="g81" d="M47.0,0.0Q37.0,0.0 30.5,10.0Q24.0,20.0 24.0,36.0Q24.0,55.0 32.0,69.5Q40.0,84.0 57.0,84.0L63.0,84.0Q96.0,84.0 116.0,99.5Q136.0,115.0 143.0,157.0L188.0,416.0Q190.0,429.0 204.5,434.0Q219.0,439.0 234.0,439.0Q251.0,439.0 263.5,433.5Q276.0,428.0 276.0,418.0Q276.0,417.0 276.0,415.0Q276.0,413.0 275.0,411.0L231.0,160.0Q227.0,138.0 220.5,119.0Q214.0,100.0 206.0,84.0L343.0,84.0Q375.0,84.0 393.5,100.5Q412.0,117.0 419.0,157.0L465.0,416.0Q467.0,429.0 481.5,434.0Q496.0,439.0 511.0,439.0Q528.0,439.0 540.5,433.5Q553.0,428.0 553.0,418.0Q553.0,417.0 553.0,415.0Q553.0,413.0 552.0,411.0L508.0,160.0Q500.0,116.0 482.0,84.0L621.0,84.0Q653.0,84.0 672.0,100.5Q691.0,117.0 698.0,157.0L744.0,416.0Q746.0,429.0 760.0,434.0Q774.0,439.0 789.0,439.0Q806.0,439.0 819.0,433.5Q832.0,428.0 832.0,418.0Q832.0,416.0 831.0,411.0L786.0,160.0Q782.0,138.0 775.5,119.0Q769.0,100.0 761.0,84.0L896.0,84.0Q930.0,84.0 949.5,99.5Q969.0,115.0 976.0,157.0L1022.0,416.0Q1024.0,429.0 1038.0,434.0Q1052.0,439.0 1067.0,439.0Q1084.0,439.0 1097.0,433.5Q1110.0,428.0 1110.0,418.0Q1110.0,415.0 1109.0,411.0L1064.0,160.0Q1056.0,116.0 1039.0,84.0L1175.0,84.0Q1187.0,84.0 1192.5,71.0Q1198.0,58.0 1198.0,42.0Q1198.0,26.0 1192.0,13.0Q1186.0,0.0 1175.0,0.0L47.0,0.0Z"/> <path id="g87" d="M-16.0,0.0Q-27.0,0.0 -33.0,13.0Q-39.0,26.0 -39.0,42.0Q-39.0,58.0 -33.5,71.0Q-28.0,84.0 -16.0,84.0L32.0,84.0L32.0,84.0Q49.0,83.0 65.5,80.5Q82.0,78.0 100.0,75.0Q124.0,71.0 150.5,67.0Q177.0,63.0 208.0,63.0Q315.0,63.0 371.0,91.0Q427.0,119.0 427.0,191.0Q427.0,222.0 414.0,238.0Q401.0,254.0 382.5,260.0Q364.0,266.0 347.0,266.0Q331.0,266.0 316.0,261.0Q301.0,256.0 287.0,250.0Q276.0,246.0 265.0,242.5Q254.0,239.0 243.0,239.0Q207.0,239.0 207.0,271.0Q207.0,294.0 221.5,309.0Q236.0,324.0 259.0,332.5Q282.0,341.0 306.5,344.0Q331.0,347.0 350.0,347.0Q411.0,347.0 448.0,326.0Q485.0,305.0 501.5,272.5Q518.0,240.0 518.0,205.0Q518.0,139.0 493.0,95.0Q468.0,51.0 424.0,25.5Q380.0,0.0 323.0,-10.5Q266.0,-21.0 201.0,-21.0Q161.0,-21.0 126.0,-16.5Q91.0,-12.0 63.0,-7.0Q46.0,-4.0 32.0,-2.0Q18.0,0.0 8.0,0.0L-16.0,0.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g66"/> </g> <g transform="translate(910,0)"> <use href="#g80"/> </g> <g transform="translate(2069,0)"> <use href="#g70"/> </g> <g transform="translate(3317,0)"> <use href="#g3"/> </g> <g transform="translate(3577,0)"> <use href="#g66"/> </g> <g transform="translate(4487,0)"> <use href="#g81"/> </g> <g transform="translate(5646,0)"> <use href="#g87"/> </g> </svg></p>
</li>
</ul>
 [code: shaping-regression]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- acutecomb

- gravecomb

- tildecomb

- uni0302

- uni0304

- uni0306

- uni0307

- uni0308

- uni030A

- uni030B

- uni030C

- uni0326

- uni0327

- uni0328
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 322:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansPsalterPahlavi/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, tai-le, tifinagh, coptic, canadian-aboriginal, old-permic, math</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>psalter-pahlavi</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoSansPsalterPahlavi-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Southern Kisi (Latn, 360,000 speakers), Mfumte (Latn, 79,000 speakers), Sar (Latn, 500,000 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers), Fur (Latn, 1,230,163 speakers), Koonzime (Latn, 40,000 speakers), Cicipu (Latn, 44,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Bafut (Latn, 158,146 speakers), Igbo (Latn, 27,823,640 speakers), Makaa (Latn, 221,000 speakers), Zapotec (Latn, 490,000 speakers), Aghem (Latn, 38,843 speakers), Ebira (Latn, 2,200,000 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ejagham (Latn, 120,000 speakers), Mundani (Latn, 34,000 speakers), Dan (Latn, 1,099,244 speakers), Ngbaka (Latn, 1,020,000 speakers), Yala (Latn, 200,000 speakers), Vute (Latn, 21,000 speakers), Ekpeye (Latn, 226,000 speakers), Gulay (Latn, 250,478 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Dii (Latn, 71,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* hepp (U+10B84): L&lt;&lt;439.0,304.0&gt;--&lt;423.0,479.0&gt;&gt; -&gt; L&lt;&lt;423.0,479.0&gt;--&lt;423.0,480.0&gt;&gt;

* hepp (U+10B84): L&lt;&lt;511.0,479.0&gt;--&lt;558.0,-32.0&gt;&gt; -&gt; L&lt;&lt;558.0,-32.0&gt;--&lt;558.0,-34.0&gt;&gt;

* hepp.fina: L&lt;&lt;439.0,304.0&gt;--&lt;423.0,479.0&gt;&gt; -&gt; L&lt;&lt;423.0,479.0&gt;--&lt;423.0,480.0&gt;&gt;

* hepp.fina: L&lt;&lt;555.0,0.0&gt;--&lt;558.0,-32.0&gt;&gt; -&gt; L&lt;&lt;558.0,-32.0&gt;--&lt;558.0,-34.0&gt;&gt;

* mempp.init: L&lt;&lt;-16.0,84.0&gt;--&lt;56.0,84.0&gt;&gt; -&gt; L&lt;&lt;56.0,84.0&gt;--&lt;56.0,84.0&gt;&gt;

* mempp.init: L&lt;&lt;56.0,84.0&gt;--&lt;56.0,84.0&gt;&gt; -&gt; L&lt;&lt;56.0,84.0&gt;--&lt;61.0,84.0&gt;&gt;

* mempp.init: L&lt;&lt;56.0,84.0&gt;--&lt;61.0,84.0&gt;&gt; -&gt; L&lt;&lt;61.0,84.0&gt;--&lt;103.0,84.0&gt;&gt;

* mempp.medi: L&lt;&lt;-16.0,84.0&gt;--&lt;56.0,84.0&gt;&gt; -&gt; L&lt;&lt;56.0,84.0&gt;--&lt;56.0,84.0&gt;&gt;

* mempp.medi: L&lt;&lt;56.0,84.0&gt;--&lt;56.0,84.0&gt;&gt; -&gt; L&lt;&lt;56.0,84.0&gt;--&lt;61.0,84.0&gt;&gt;

* mempp.medi: L&lt;&lt;56.0,84.0&gt;--&lt;61.0,84.0&gt;&gt; -&gt; L&lt;&lt;61.0,84.0&gt;--&lt;103.0,84.0&gt;&gt;

* shinpp.init: L&lt;&lt;-16.0,84.0&gt;--&lt;32.0,84.0&gt;&gt; -&gt; L&lt;&lt;32.0,84.0&gt;--&lt;32.0,84.0&gt;&gt;

* tenpp.init: L&lt;&lt;-16.0,84.0&gt;--&lt;32.0,84.0&gt;&gt; -&gt; L&lt;&lt;32.0,84.0&gt;--&lt;32.0,84.0&gt;&gt;

* tenpp.medi: L&lt;&lt;-16.0,84.0&gt;--&lt;32.0,84.0&gt;&gt; -&gt; L&lt;&lt;32.0,84.0&gt;--&lt;32.0,84.0&gt;&gt;

* twentypp.init: L&lt;&lt;-16.0,84.0&gt;--&lt;32.0,84.0&gt;&gt; -&gt; L&lt;&lt;32.0,84.0&gt;--&lt;32.0,84.0&gt;&gt;

* twentypp.medi: L&lt;&lt;-16.0,84.0&gt;--&lt;32.0,84.0&gt;&gt; -&gt; L&lt;&lt;32.0,84.0&gt;--&lt;32.0,84.0&gt;&gt;

* yodhpp (U+10B88): L&lt;&lt;486.0,198.0&gt;--&lt;500.0,23.0&gt;&gt; -&gt; L&lt;&lt;500.0,23.0&gt;--&lt;500.0,21.0&gt;&gt;

* yodhpp (U+10B88): L&lt;&lt;59.0,21.0&gt;--&lt;59.0,23.0&gt;&gt; -&gt; L&lt;&lt;59.0,23.0&gt;--&lt;72.0,194.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* alefpp.init: B&lt;&lt;104.0,16.0&gt;-&lt;74.0,3.0&gt;-&lt;32.0,0.0&gt;&gt;/L&lt;&lt;32.0,0.0&gt;--&lt;32.0,0.0&gt;&gt; = 4.085616779974888
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 5 | 9 | 116 | 6 | 115 | 0 | 
| 0% | 0% | 2% | 4% | 46% | 2% | 46% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
