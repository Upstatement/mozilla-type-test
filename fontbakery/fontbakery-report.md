## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[2] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Fonts have consistent underline thickness? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-underline-thickness">opentype/family/underline_thickness</a></summary>
    <div>







* 🔥 **FAIL** <p>Thickness of the underline is not the same across this family. In order to fix this, please make sure that the underlineThickness value is the same in the 'post' table of all of this family font files.
Detected underlineThickness values are:
fonts/ttf/MozillaHeadline-ExpandedExtraLight.ttf: 48
fonts/ttf/MozillaHeadline-Bold.ttf: 90
fonts/ttf/MozillaHeadline-ExtraLightItalic.ttf: 46
fonts/ttf/MozillaHeadline-ExtraLight.ttf: 46
fonts/ttf/MozillaHeadline-CondensedBold.ttf: 86
fonts/ttf/MozillaHeadline-CondensedExtraLight.ttf: 44
fonts/ttf/MozillaHeadline-ExpandedBold.ttf: 94
fonts/ttf/MozillaHeadline-BoldItalic.ttf: 90</p>
 [code: inconsistent-underline-thickness]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure VFs have 'ital' STAT axis. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-STAT-ital-axis">opentype/STAT/ital_axis</a></summary>
    <div>







* 🔥 **FAIL** <p>Font fonts/ttf/MozillaHeadline-ExpandedExtraLight.ttf has no STAT table</p>
 [code: no-stat]



* 🔥 **FAIL** <p>Font fonts/ttf/MozillaHeadline-ExtraLightItalic.ttf has no STAT table</p>
 [code: no-stat]



* 🔥 **FAIL** <p>Font fonts/ttf/MozillaHeadline-Bold.ttf has no STAT table</p>
 [code: no-stat]



* 🔥 **FAIL** <p>Font fonts/ttf/MozillaHeadline-BoldItalic.ttf has no STAT table</p>
 [code: no-stat]



</div>
</details>
</div>
</details>

<details><summary>[19] MozillaHeadline-ExpandedExtraLight.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Does full font name begin with the font family name? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-name-match-familyname-fullfont">opentype/name/match_familyname_fullfont</a></summary>
    <div>







* 🔥 **FAIL** <p>On the 'name' table, the full font name 'Mozilla Headline ExtraLight' does not begin with the font family name 'Mozilla Slab Headline Expanded ExLight' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1.</p>
 [code: mismatch-font-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1110, but got 944 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024, The Mozilla Foundation&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Licensed under the Open Font License, version 1.1 or later.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;MozillaHeadline-ExtraLight.ttf. Got MozillaHeadline-ExpandedExtraLight.ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Mozilla Slab Headline Expanded ExLight</strong></td>
<td align="left"><strong>Mozilla Headline ExtraLight</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Mozilla Headline ExtraLight</td>
<td align="left">Mozilla Headline ExtraLight</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>MozillaHeadlineExp-ExtraLight</strong></td>
<td align="left"><strong>MozillaHeadline-ExtraLight</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left">Mozilla Headline</td>
<td align="left">Mozilla Headline</td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left">ExtraLight</td>
<td align="left">ExtraLight</td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: uni2153	Contours detected: 4	Expected: 3

- Glyph name: uni2154	Contours detected: 4	Expected: 1 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-family-and-style-max-length">name/family_and_style_max_length</a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'MozillaHeadlineExp-ExtraLight' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- j_acutecomb

- uni004A0301

- uni0308.case.narrow
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, old-permic, coptic, duployan, canadian-aboriginal, tifinagh, hebrew, math, syriac, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, symbols, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+1F409 DRAGON: not included in any glyphset definition</li>
<li>U+1F432 DRAGON FACE: not included in any glyphset definition</li>
<li>U+1F4BB PERSONAL COMPUTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* u1F409 (U+1F409): X=148.0,Y=0.5 (should be at baseline 0?)

* u1F432 (U+1F432): X=148.0,Y=0.5 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* exclam (U+0021): L&lt;&lt;130.0,174.0&gt;--&lt;113.0,636.0&gt;&gt; -&gt; L&lt;&lt;113.0,636.0&gt;--&lt;113.0,690.0&gt;&gt;

* exclam (U+0021): L&lt;&lt;185.0,690.0&gt;--&lt;185.0,636.0&gt;&gt; -&gt; L&lt;&lt;185.0,636.0&gt;--&lt;168.0,174.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;113.0,-156.0&gt;--&lt;113.0,-102.0&gt;&gt; -&gt; L&lt;&lt;113.0,-102.0&gt;--&lt;130.0,360.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;168.0,360.0&gt;--&lt;185.0,-102.0&gt;&gt; -&gt; L&lt;&lt;185.0,-102.0&gt;--&lt;185.0,-156.0&gt;&gt;

* exclamdown.case: L&lt;&lt;113.0,0.0&gt;--&lt;113.0,54.0&gt;&gt; -&gt; L&lt;&lt;113.0,54.0&gt;--&lt;130.0,516.0&gt;&gt;

* exclamdown.case: L&lt;&lt;168.0,516.0&gt;--&lt;185.0,54.0&gt;&gt; -&gt; L&lt;&lt;185.0,54.0&gt;--&lt;185.0,0.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* G (U+0047) contains a short segment L&lt;&lt;689.0,128.0&gt;--&lt;665.0,128.0&gt;&gt;

* IJ (U+0132) contains a short segment L&lt;&lt;222.0,277.0&gt;--&lt;222.0,273.0&gt;&gt;

* Iacute_J.loclNLD contains a short segment L&lt;&lt;222.0,277.0&gt;--&lt;222.0,273.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;504.0,112.0&gt;--&lt;528.0,112.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;846.0,632.0&gt;--&lt;822.0,632.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;208.0,632.0&gt;--&lt;184.0,632.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;612.0,130.0&gt;--&lt;636.0,130.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;208.0,618.0&gt;--&lt;184.0,618.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;612.0,130.0&gt;--&lt;636.0,130.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;208.0,618.0&gt;--&lt;184.0,618.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;612.0,130.0&gt;--&lt;636.0,130.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;208.0,618.0&gt;--&lt;184.0,618.0&gt;&gt;

* uni1E9E (U+1E9E) contains a short segment L&lt;&lt;476.0,394.0&gt;--&lt;501.0,394.0&gt;&gt;

* U (U+0055) contains a short segment L&lt;&lt;639.0,104.0&gt;--&lt;615.0,104.0&gt;&gt;

* Uacute (U+00DA) contains a short segment L&lt;&lt;639.0,104.0&gt;--&lt;615.0,104.0&gt;&gt;

* Ucircumflex (U+00DB) contains a short segment L&lt;&lt;639.0,104.0&gt;--&lt;615.0,104.0&gt;&gt;

* Udieresis (U+00DC) contains a short segment L&lt;&lt;639.0,104.0&gt;--&lt;615.0,104.0&gt;&gt;

* Ugrave (U+00D9) contains a short segment L&lt;&lt;639.0,104.0&gt;--&lt;615.0,104.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;310.0,58.0&gt;--&lt;334.0,58.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;798.0,58.0&gt;--&lt;822.0,58.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;577.0,572.0&gt;--&lt;553.0,572.0&gt;&gt;

* X (U+0058) contains a short segment L&lt;&lt;384.0,383.0&gt;--&lt;408.0,383.0&gt;&gt;

* X (U+0058) contains a short segment L&lt;&lt;406.0,325.0&gt;--&lt;382.0,325.0&gt;&gt;

* N.ss03 contains a short segment L&lt;&lt;602.0,130.0&gt;--&lt;626.0,130.0&gt;&gt;

* N.ss03 contains a short segment L&lt;&lt;198.0,618.0&gt;--&lt;174.0,618.0&gt;&gt;

* Nacute.ss03 contains a short segment L&lt;&lt;602.0,130.0&gt;--&lt;626.0,130.0&gt;&gt;

* Nacute.ss03 contains a short segment L&lt;&lt;198.0,618.0&gt;--&lt;174.0,618.0&gt;&gt;

* Ntilde.ss03 contains a short segment L&lt;&lt;602.0,130.0&gt;--&lt;626.0,130.0&gt;&gt;

* Ntilde.ss03 contains a short segment L&lt;&lt;198.0,618.0&gt;--&lt;174.0,618.0&gt;&gt;

* uni1E9E.ss03 contains a short segment L&lt;&lt;445.0,394.0&gt;--&lt;470.0,394.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;514.0,112.0&gt;--&lt;538.0,112.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;856.0,632.0&gt;--&lt;832.0,632.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;218.0,632.0&gt;--&lt;194.0,632.0&gt;&gt;

* ae (U+00E6) contains a short segment L&lt;&lt;467.0,312.0&gt;--&lt;467.0,331.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;171.0,446.0&gt;--&lt;195.0,446.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;279.0,56.0&gt;--&lt;303.0,56.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;709.0,56.0&gt;--&lt;733.0,56.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;517.0,418.0&gt;--&lt;493.0,418.0&gt;&gt;

* ordfeminine (U+00AA) contains a short segment L&lt;&lt;331.0,554.0&gt;--&lt;331.0,563.0&gt;&gt;

* three (U+0033) contains a short segment L&lt;&lt;132.0,231.0&gt;--&lt;132.0,229.0&gt;&gt;

* uni2153 (U+2153) contains a short segment L&lt;&lt;545.0,102.0&gt;--&lt;545.0,101.0&gt;&gt;

* uni2154 (U+2154) contains a short segment L&lt;&lt;579.0,102.0&gt;--&lt;579.0,101.0&gt;&gt;

* threequarters (U+00BE) contains a short segment L&lt;&lt;111.0,470.0&gt;--&lt;111.0,469.0&gt;&gt;

* uni2083 (U+2083) contains a short segment L&lt;&lt;111.0,102.0&gt;--&lt;111.0,101.0&gt;&gt;

* uni00B3 (U+00B3) contains a short segment L&lt;&lt;111.0,470.0&gt;--&lt;111.0,469.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;220.0,546.0&gt;--&lt;226.0,550.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;252.0,550.0&gt;--&lt;258.0,546.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;265.0,522.0&gt;--&lt;263.0,515.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;243.0,499.0&gt;--&lt;235.0,499.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;213.0,515.0&gt;--&lt;211.0,522.0&gt;&gt;

* at (U+0040) contains a short segment L&lt;&lt;599.0,335.0&gt;--&lt;599.0,349.0&gt;&gt;

* ampersand (U+0026) contains a short segment L&lt;&lt;548.0,80.0&gt;--&lt;525.0,80.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;142.0,69.0&gt;--&lt;142.0,67.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;529.0,523.0&gt;--&lt;529.0,525.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;701.0,400.0&gt;--&lt;717.0,400.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;880.0,641.0&gt;--&lt;863.0,641.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;554.0,641.0&gt;--&lt;537.0,641.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;210.0,493.0&gt;--&lt;216.0,498.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;254.0,498.0&gt;--&lt;260.0,493.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;245.0,493.0&gt;--&lt;251.0,498.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;289.0,498.0&gt;--&lt;295.0,493.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;251.0,192.0&gt;--&lt;245.0,197.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;295.0,197.0&gt;--&lt;289.0,192.0&gt;&gt;

* estimated (U+212E) contains a short segment B&lt;&lt;213.0,335.0&gt;-&lt;203.0,335.0&gt;-&lt;203.0,325.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;147.0,314.0&gt;-&lt;146.0,329.0&gt;-&lt;146.0,345.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;216.0,344.0&gt;-&lt;216.0,328.0&gt;-&lt;217.0,314.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;357.0,362.0&gt;--&lt;381.0,362.0&gt;&gt;

* uni2126 (U+2126) contains a short segment L&lt;&lt;253.0,58.0&gt;--&lt;253.0,82.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[19] MozillaHeadline-CondensedExtraLight.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Does full font name begin with the font family name? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-name-match-familyname-fullfont">opentype/name/match_familyname_fullfont</a></summary>
    <div>







* 🔥 **FAIL** <p>On the 'name' table, the full font name 'Mozilla Headline ExtraLight' does not begin with the font family name 'Mozilla Headline Condensed ExLight' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1.</p>
 [code: mismatch-font-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1110, but got 944 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024, The Mozilla Foundation&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Licensed under the Open Font License, version 1.1 or later.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;MozillaHeadline-ExtraLight.ttf. Got MozillaHeadline-CondensedExtraLight.ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Mozilla Headline Condensed ExLight</strong></td>
<td align="left"><strong>Mozilla Headline ExtraLight</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Mozilla Headline ExtraLight</td>
<td align="left">Mozilla Headline ExtraLight</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>MozillaHeadlineCnd-ExtraLight</strong></td>
<td align="left"><strong>MozillaHeadline-ExtraLight</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left">Mozilla Headline</td>
<td align="left">Mozilla Headline</td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left">ExtraLight</td>
<td align="left">ExtraLight</td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: uni2153	Contours detected: 4	Expected: 3

- Glyph name: uni2154	Contours detected: 4	Expected: 1 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-family-and-style-max-length">name/family_and_style_max_length</a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'MozillaHeadlineCnd-ExtraLight' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- j_acutecomb

- uni004A0301

- uni0308.case.narrow
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, old-permic, coptic, duployan, canadian-aboriginal, tifinagh, hebrew, math, syriac, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, symbols, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+1F409 DRAGON: not included in any glyphset definition</li>
<li>U+1F432 DRAGON FACE: not included in any glyphset definition</li>
<li>U+1F4BB PERSONAL COMPUTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Oslash (U+00D8): X=308.5,Y=689.5 (should be at cap-height 690?)

* Oslash (U+00D8): X=171.0,Y=0.5 (should be at baseline 0?)

* aring (U+00E5): X=204.0,Y=688.0 (should be at cap-height 690?)

* aring.ss01: X=207.0,Y=688.0 (should be at cap-height 690?)

* u1F409 (U+1F409): X=148.0,Y=0.5 (should be at baseline 0?)

* u1F432 (U+1F432): X=148.0,Y=0.5 (should be at baseline 0?)

* uni030A (U+030A): X=200.0,Y=688.0 (should be at cap-height 690?)

* ring (U+02DA): X=200.0,Y=688.0 (should be at cap-height 690?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* exclam (U+0021): L&lt;&lt;133.0,690.0&gt;--&lt;133.0,639.0&gt;&gt; -&gt; L&lt;&lt;133.0,639.0&gt;--&lt;119.0,162.0&gt;&gt;

* exclam (U+0021): L&lt;&lt;84.0,162.0&gt;--&lt;70.0,639.0&gt;&gt; -&gt; L&lt;&lt;70.0,639.0&gt;--&lt;70.0,690.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;119.0,372.0&gt;--&lt;133.0,-105.0&gt;&gt; -&gt; L&lt;&lt;133.0,-105.0&gt;--&lt;133.0,-156.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;70.0,-156.0&gt;--&lt;70.0,-105.0&gt;&gt; -&gt; L&lt;&lt;70.0,-105.0&gt;--&lt;84.0,372.0&gt;&gt;

* exclamdown.case: L&lt;&lt;119.0,528.0&gt;--&lt;133.0,51.0&gt;&gt; -&gt; L&lt;&lt;133.0,51.0&gt;--&lt;133.0,0.0&gt;&gt;

* exclamdown.case: L&lt;&lt;70.0,0.0&gt;--&lt;70.0,51.0&gt;&gt; -&gt; L&lt;&lt;70.0,51.0&gt;--&lt;84.0,528.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* Aogonek (U+0104) contains a short segment L&lt;&lt;355.0,0.0&gt;--&lt;348.0,0.0&gt;&gt;

* G (U+0047) contains a short segment L&lt;&lt;349.0,477.0&gt;--&lt;349.0,484.0&gt;&gt;

* G (U+0047) contains a short segment L&lt;&lt;367.0,83.0&gt;--&lt;349.0,83.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;325.0,155.0&gt;--&lt;343.0,155.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;537.0,635.0&gt;--&lt;520.0,635.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;147.0,635.0&gt;--&lt;129.0,635.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;351.0,200.0&gt;--&lt;369.0,200.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;142.0,618.0&gt;--&lt;124.0,618.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;351.0,200.0&gt;--&lt;369.0,200.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;142.0,618.0&gt;--&lt;124.0,618.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;351.0,200.0&gt;--&lt;369.0,200.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;142.0,618.0&gt;--&lt;124.0,618.0&gt;&gt;

* U (U+0055) contains a short segment L&lt;&lt;359.0,78.0&gt;--&lt;341.0,78.0&gt;&gt;

* Uacute (U+00DA) contains a short segment L&lt;&lt;359.0,78.0&gt;--&lt;341.0,78.0&gt;&gt;

* Ucircumflex (U+00DB) contains a short segment L&lt;&lt;359.0,78.0&gt;--&lt;341.0,78.0&gt;&gt;

* Udieresis (U+00DC) contains a short segment L&lt;&lt;359.0,78.0&gt;--&lt;341.0,78.0&gt;&gt;

* Ugrave (U+00D9) contains a short segment L&lt;&lt;359.0,78.0&gt;--&lt;341.0,78.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;185.0,55.0&gt;--&lt;203.0,55.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;465.0,55.0&gt;--&lt;483.0,55.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;342.0,492.0&gt;--&lt;324.0,492.0&gt;&gt;

* X (U+0058) contains a short segment L&lt;&lt;226.0,381.0&gt;--&lt;244.0,381.0&gt;&gt;

* X (U+0058) contains a short segment L&lt;&lt;242.0,327.0&gt;--&lt;224.0,327.0&gt;&gt;

* Aogonek.ss03 contains a short segment L&lt;&lt;351.0,0.0&gt;--&lt;344.0,0.0&gt;&gt;

* N.ss03 contains a short segment L&lt;&lt;346.0,200.0&gt;--&lt;364.0,200.0&gt;&gt;

* N.ss03 contains a short segment L&lt;&lt;137.0,618.0&gt;--&lt;119.0,618.0&gt;&gt;

* Nacute.ss03 contains a short segment L&lt;&lt;346.0,200.0&gt;--&lt;364.0,200.0&gt;&gt;

* Nacute.ss03 contains a short segment L&lt;&lt;137.0,618.0&gt;--&lt;119.0,618.0&gt;&gt;

* Ntilde.ss03 contains a short segment L&lt;&lt;346.0,200.0&gt;--&lt;364.0,200.0&gt;&gt;

* Ntilde.ss03 contains a short segment L&lt;&lt;137.0,618.0&gt;--&lt;119.0,618.0&gt;&gt;

* U.ss03 contains a short segment L&lt;&lt;354.0,78.0&gt;--&lt;336.0,78.0&gt;&gt;

* Uacute.ss03 contains a short segment L&lt;&lt;354.0,78.0&gt;--&lt;336.0,78.0&gt;&gt;

* Ucircumflex.ss03 contains a short segment L&lt;&lt;354.0,78.0&gt;--&lt;336.0,78.0&gt;&gt;

* Udieresis.ss03 contains a short segment L&lt;&lt;354.0,78.0&gt;--&lt;336.0,78.0&gt;&gt;

* Ugrave.ss03 contains a short segment L&lt;&lt;354.0,78.0&gt;--&lt;336.0,78.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;331.0,155.0&gt;--&lt;349.0,155.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;543.0,635.0&gt;--&lt;525.0,635.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;152.0,635.0&gt;--&lt;134.0,635.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;118.0,461.0&gt;--&lt;136.0,461.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;177.0,53.0&gt;--&lt;195.0,53.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;438.0,53.0&gt;--&lt;456.0,53.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;324.0,344.0&gt;--&lt;307.0,344.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;165.0,577.0&gt;--&lt;171.0,581.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;197.0,581.0&gt;--&lt;203.0,577.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;210.0,553.0&gt;--&lt;208.0,546.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;188.0,530.0&gt;--&lt;180.0,530.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;158.0,546.0&gt;--&lt;156.0,553.0&gt;&gt;

* ampersand (U+0026) contains a short segment L&lt;&lt;359.0,151.0&gt;--&lt;376.0,151.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;489.0,422.0&gt;--&lt;501.0,422.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;610.0,646.0&gt;--&lt;598.0,646.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;390.0,646.0&gt;--&lt;378.0,646.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;159.0,490.0&gt;--&lt;165.0,495.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;197.0,495.0&gt;--&lt;203.0,490.0&gt;&gt;

* estimated (U+212E) contains a short segment B&lt;&lt;192.0,335.0&gt;-&lt;182.0,335.0&gt;-&lt;182.0,325.0&gt;&gt;

* dollar (U+0024) contains a short segment L&lt;&lt;331.0,459.0&gt;--&lt;331.0,479.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;96.0,323.0&gt;-&lt;96.0,333.0&gt;-&lt;96.0,345.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;205.0,379.0&gt;--&lt;223.0,379.0&gt;&gt;

* uni2126 (U+2126) contains a short segment L&lt;&lt;163.0,55.0&gt;--&lt;163.0,73.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[15] MozillaHeadline-Bold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1110, but got 944 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024, The Mozilla Foundation&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Licensed under the Open Font License, version 1.1 or later.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: uni2153	Contours detected: 4	Expected: 3

- Glyph name: uni2154	Contours detected: 4	Expected: 1 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- j_acutecomb

- uni004A0301

- uni0308.case.narrow
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, old-permic, coptic, duployan, canadian-aboriginal, tifinagh, hebrew, math, syriac, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, symbols, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+1F409 DRAGON: not included in any glyphset definition</li>
<li>U+1F432 DRAGON FACE: not included in any glyphset definition</li>
<li>U+1F4BB PERSONAL COMPUTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* g.ss02: X=195.0,Y=2.0 (should be at baseline 0?)

* braceleft (U+007B): X=92.0,Y=-1.0 (should be at baseline 0?)

* braceleft (U+007B): X=92.0,Y=691.0 (should be at cap-height 690?)

* braceright (U+007D): X=269.0,Y=691.0 (should be at cap-height 690?)

* braceright (U+007D): X=269.0,Y=-1.0 (should be at baseline 0?)

* u1F409 (U+1F409): X=148.0,Y=0.5 (should be at baseline 0?)

* u1F432 (U+1F432): X=148.0,Y=0.5 (should be at baseline 0?)

* dollar (U+0024): X=256.0,Y=-2.0 (should be at baseline 0?)

* dollar (U+0024): X=254.0,Y=692.0 (should be at cap-height 690?)

* dollar (U+0024): X=360.0,Y=692.0 (should be at cap-height 690?)

* dollar (U+0024): X=362.0,Y=-2.0 (should be at baseline 0?)

* uni00B5 (U+00B5): X=209.0,Y=2.0 (should be at baseline 0?)

* tildecomb.case: X=127.0,Y=691.0 (should be at cap-height 690?)

* tildecomb.case: X=35.0,Y=691.0 (should be at cap-height 690?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* exclam (U+0021): L&lt;&lt;208.0,690.0&gt;--&lt;208.0,583.0&gt;&gt; -&gt; L&lt;&lt;208.0,583.0&gt;--&lt;173.0,191.0&gt;&gt;

* exclam (U+0021): L&lt;&lt;88.0,191.0&gt;--&lt;54.0,583.0&gt;&gt; -&gt; L&lt;&lt;54.0,583.0&gt;--&lt;54.0,690.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;173.0,343.0&gt;--&lt;208.0,-49.0&gt;&gt; -&gt; L&lt;&lt;208.0,-49.0&gt;--&lt;208.0,-156.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;54.0,-156.0&gt;--&lt;54.0,-49.0&gt;&gt; -&gt; L&lt;&lt;54.0,-49.0&gt;--&lt;88.0,343.0&gt;&gt;

* exclamdown.case: L&lt;&lt;173.0,499.0&gt;--&lt;208.0,107.0&gt;&gt; -&gt; L&lt;&lt;208.0,107.0&gt;--&lt;208.0,0.0&gt;&gt;

* exclamdown.case: L&lt;&lt;54.0,0.0&gt;--&lt;54.0,107.0&gt;&gt; -&gt; L&lt;&lt;54.0,107.0&gt;--&lt;88.0,499.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* G (U+0047) contains a short segment L&lt;&lt;479.0,466.0&gt;--&lt;479.0,489.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;429.0,263.0&gt;--&lt;462.0,263.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;676.0,568.0&gt;--&lt;643.0,568.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;244.0,568.0&gt;--&lt;211.0,568.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;265.0,119.0&gt;--&lt;297.0,119.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;659.0,119.0&gt;--&lt;692.0,119.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;492.0,443.0&gt;--&lt;459.0,443.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;438.0,263.0&gt;--&lt;470.0,263.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;684.0,568.0&gt;--&lt;651.0,568.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;252.0,568.0&gt;--&lt;220.0,568.0&gt;&gt;

* ae (U+00E6) contains a short segment L&lt;&lt;347.0,322.0&gt;--&lt;347.0,342.0&gt;&gt;

* ae (U+00E6) contains a short segment L&lt;&lt;513.0,239.0&gt;--&lt;513.0,228.0&gt;&gt;

* c (U+0063) contains a short segment L&lt;&lt;383.0,348.0&gt;--&lt;383.0,362.0&gt;&gt;

* cacute (U+0107) contains a short segment L&lt;&lt;383.0,348.0&gt;--&lt;383.0,362.0&gt;&gt;

* ccedilla (U+00E7) contains a short segment L&lt;&lt;383.0,348.0&gt;--&lt;383.0,362.0&gt;&gt;

* e (U+0065) contains a short segment L&lt;&lt;185.0,239.0&gt;--&lt;185.0,228.0&gt;&gt;

* eacute (U+00E9) contains a short segment L&lt;&lt;185.0,239.0&gt;--&lt;185.0,228.0&gt;&gt;

* ecircumflex (U+00EA) contains a short segment L&lt;&lt;185.0,239.0&gt;--&lt;185.0,228.0&gt;&gt;

* edieresis (U+00EB) contains a short segment L&lt;&lt;185.0,239.0&gt;--&lt;185.0,228.0&gt;&gt;

* egrave (U+00E8) contains a short segment L&lt;&lt;185.0,239.0&gt;--&lt;185.0,228.0&gt;&gt;

* eogonek (U+0119) contains a short segment L&lt;&lt;185.0,239.0&gt;--&lt;185.0,228.0&gt;&gt;

* oe (U+0153) contains a short segment L&lt;&lt;578.0,239.0&gt;--&lt;578.0,228.0&gt;&gt;

* s (U+0073) contains a short segment L&lt;&lt;172.0,172.0&gt;--&lt;172.0,161.0&gt;&gt;

* s (U+0073) contains a short segment L&lt;&lt;356.0,362.0&gt;--&lt;356.0,373.0&gt;&gt;

* sacute (U+015B) contains a short segment L&lt;&lt;172.0,172.0&gt;--&lt;172.0,161.0&gt;&gt;

* sacute (U+015B) contains a short segment L&lt;&lt;356.0,362.0&gt;--&lt;356.0,373.0&gt;&gt;

* scaron (U+0161) contains a short segment L&lt;&lt;172.0,172.0&gt;--&lt;172.0,161.0&gt;&gt;

* scaron (U+0161) contains a short segment L&lt;&lt;356.0,362.0&gt;--&lt;356.0,373.0&gt;&gt;

* g.ss02 contains a short segment L&lt;&lt;195.0,4.0&gt;--&lt;195.0,2.0&gt;&gt;

* six (U+0036) contains a short segment L&lt;&lt;424.0,495.0&gt;--&lt;424.0,509.0&gt;&gt;

* nine (U+0039) contains a short segment L&lt;&lt;198.0,195.0&gt;--&lt;198.0,181.0&gt;&gt;

* uni2153 (U+2153) contains a short segment L&lt;&lt;507.0,107.0&gt;--&lt;507.0,100.0&gt;&gt;

* uni2154 (U+2154) contains a short segment L&lt;&lt;534.0,107.0&gt;--&lt;534.0,100.0&gt;&gt;

* threequarters (U+00BE) contains a short segment L&lt;&lt;132.0,475.0&gt;--&lt;132.0,468.0&gt;&gt;

* uni2083 (U+2083) contains a short segment L&lt;&lt;132.0,107.0&gt;--&lt;132.0,100.0&gt;&gt;

* uni00B3 (U+00B3) contains a short segment L&lt;&lt;132.0,475.0&gt;--&lt;132.0,468.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;199.0,526.0&gt;--&lt;205.0,530.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;231.0,530.0&gt;--&lt;237.0,526.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;244.0,502.0&gt;--&lt;242.0,495.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;222.0,479.0&gt;--&lt;214.0,479.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;192.0,495.0&gt;--&lt;190.0,502.0&gt;&gt;

* at (U+0040) contains a short segment L&lt;&lt;488.0,344.0&gt;--&lt;488.0,358.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;372.5,416.5&gt;-&lt;357.0,401.0&gt;-&lt;357.0,383.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;183.0,80.0&gt;--&lt;183.0,68.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;392.0,518.0&gt;--&lt;392.0,530.0&gt;&gt;

* copyright (U+00A9) contains a short segment L&lt;&lt;495.0,414.0&gt;--&lt;495.0,427.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;173.0,491.0&gt;--&lt;180.0,497.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;249.0,497.0&gt;--&lt;256.0,491.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;280.0,497.0&gt;--&lt;286.0,491.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;286.0,199.0&gt;--&lt;280.0,193.0&gt;&gt;

* estimated (U+212E) contains a short segment B&lt;&lt;205.0,335.0&gt;-&lt;195.0,335.0&gt;-&lt;195.0,325.0&gt;&gt;

* cent (U+00A2) contains a short segment L&lt;&lt;389.0,348.0&gt;--&lt;389.0,361.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;103.0,333.0&gt;-&lt;103.0,338.0&gt;-&lt;103.0,345.0&gt;&gt;

* Euro (U+20AC) contains a short segment L&lt;&lt;530.0,474.0&gt;--&lt;530.0,493.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;235.0,260.0&gt;--&lt;231.0,268.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;385.0,268.0&gt;--&lt;381.0,260.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[16] MozillaHeadline-ExtraLightItalic.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1110, but got 944 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024, The Mozilla Foundation&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Licensed under the Open Font License, version 1.1 or later.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Mozilla Headline ExtraLight</td>
<td align="left">Mozilla Headline ExtraLight</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Italic</td>
<td align="left">Italic</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Mozilla Headline ExtraLight Italic</td>
<td align="left">Mozilla Headline ExtraLight Italic</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>MozillaHeadline-ExtraLightIt</strong></td>
<td align="left"><strong>MozillaHeadline-ExtraLightItalic</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left">Mozilla Headline</td>
<td align="left">Mozilla Headline</td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left">ExtraLight Italic</td>
<td align="left">ExtraLight Italic</td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: uni2153	Contours detected: 4	Expected: 3

- Glyph name: uni2154	Contours detected: 4	Expected: 1 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-family-and-style-max-length">name/family_and_style_max_length</a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'MozillaHeadline-ExtraLightIt' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- j_acutecomb

- uni004A0301

- uni0308.case.narrow
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, old-permic, coptic, duployan, canadian-aboriginal, tifinagh, hebrew, math, syriac, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, symbols, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+1F409 DRAGON: not included in any glyphset definition</li>
<li>U+1F432 DRAGON FACE: not included in any glyphset definition</li>
<li>U+1F4BB PERSONAL COMPUTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Aogonek (U+0104): X=489.0,Y=1.0 (should be at baseline 0?)

* Aogonek.ss03: X=483.0,Y=1.0 (should be at baseline 0?)

* aring (U+00E5): X=376.5,Y=692.0 (should be at cap-height 690?)

* h (U+0068): X=192.0,Y=532.0 (should be at x-height 534?)

* aring.ss01: X=384.5,Y=692.0 (should be at cap-height 690?)

* u1F409 (U+1F409): X=148.0,Y=0.5 (should be at baseline 0?)

* u1F432 (U+1F432): X=148.0,Y=0.5 (should be at baseline 0?)

* cent (U+00A2): X=220.0,Y=-2.0 (should be at baseline 0?)

* dollar (U+0024): X=237.0,Y=-2.0 (should be at baseline 0?)

* dollar (U+0024): X=405.0,Y=692.0 (should be at cap-height 690?)

* radical (U+221A): X=145.0,Y=-1.0 (should be at baseline 0?)

* radical (U+221A): X=504.0,Y=691.0 (should be at cap-height 690?)

* radical (U+221A): X=568.0,Y=691.0 (should be at cap-height 690?)

* radical (U+221A): X=256.0,Y=-1.0 (should be at baseline 0?)

* radical (U+221A): X=145.0,Y=-1.0 (should be at baseline 0?)

* uni00B5 (U+00B5): X=110.0,Y=1.5 (should be at baseline 0?)

* uni030A (U+030A): X=303.5,Y=692.0 (should be at cap-height 690?)

* ring (U+02DA): X=303.5,Y=692.0 (should be at cap-height 690?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* exclam (U+0021): L&lt;&lt;236.0,690.0&gt;--&lt;227.0,637.0&gt;&gt; -&gt; L&lt;&lt;227.0,637.0&gt;--&lt;133.0,169.0&gt;&gt;

* exclam (U+0021): L&lt;&lt;96.0,169.0&gt;--&lt;159.0,637.0&gt;&gt; -&gt; L&lt;&lt;159.0,637.0&gt;--&lt;168.0,690.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;166.0,365.0&gt;--&lt;103.0,-103.0&gt;&gt; -&gt; L&lt;&lt;103.0,-103.0&gt;--&lt;94.0,-156.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;26.0,-156.0&gt;--&lt;35.0,-103.0&gt;&gt; -&gt; L&lt;&lt;35.0,-103.0&gt;--&lt;129.0,365.0&gt;&gt;

* exclamdown.case: L&lt;&lt;192.0,521.0&gt;--&lt;129.0,53.0&gt;&gt; -&gt; L&lt;&lt;129.0,53.0&gt;--&lt;120.0,0.0&gt;&gt;

* exclamdown.case: L&lt;&lt;52.0,0.0&gt;--&lt;61.0,53.0&gt;&gt; -&gt; L&lt;&lt;61.0,53.0&gt;--&lt;155.0,521.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[16] MozillaHeadline-ExtraLight.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1110, but got 944 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024, The Mozilla Foundation&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Licensed under the Open Font License, version 1.1 or later.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: uni2153	Contours detected: 4	Expected: 3

- Glyph name: uni2154	Contours detected: 4	Expected: 1 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- j_acutecomb

- uni004A0301

- uni0308.case.narrow
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, old-permic, coptic, duployan, canadian-aboriginal, tifinagh, hebrew, math, syriac, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, symbols, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+1F409 DRAGON: not included in any glyphset definition</li>
<li>U+1F432 DRAGON FACE: not included in any glyphset definition</li>
<li>U+1F4BB PERSONAL COMPUTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* h (U+0068): X=147.5,Y=532.0 (should be at x-height 534?)

* u1F409 (U+1F409): X=148.0,Y=0.5 (should be at baseline 0?)

* u1F432 (U+1F432): X=148.0,Y=0.5 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* exclam (U+0021): L&lt;&lt;112.0,169.0&gt;--&lt;96.0,637.0&gt;&gt; -&gt; L&lt;&lt;96.0,637.0&gt;--&lt;96.0,690.0&gt;&gt;

* exclam (U+0021): L&lt;&lt;165.0,690.0&gt;--&lt;165.0,637.0&gt;&gt; -&gt; L&lt;&lt;165.0,637.0&gt;--&lt;149.0,169.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;149.0,365.0&gt;--&lt;165.0,-103.0&gt;&gt; -&gt; L&lt;&lt;165.0,-103.0&gt;--&lt;165.0,-156.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;96.0,-156.0&gt;--&lt;96.0,-103.0&gt;&gt; -&gt; L&lt;&lt;96.0,-103.0&gt;--&lt;112.0,365.0&gt;&gt;

* exclamdown.case: L&lt;&lt;149.0,521.0&gt;--&lt;165.0,53.0&gt;&gt; -&gt; L&lt;&lt;165.0,53.0&gt;--&lt;165.0,0.0&gt;&gt;

* exclamdown.case: L&lt;&lt;96.0,0.0&gt;--&lt;96.0,53.0&gt;&gt; -&gt; L&lt;&lt;96.0,53.0&gt;--&lt;112.0,521.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* ampersand (U+0026): L&lt;&lt;449.0,101.0&gt;--&lt;268.0,337.0&gt;&gt;/L&lt;&lt;268.0,337.0&gt;--&lt;269.0,335.0&gt;&gt; = 10.921320642383275
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* Aogonek (U+0104) contains a short segment L&lt;&lt;533.0,0.0&gt;--&lt;530.0,0.0&gt;&gt;

* C (U+0043) contains a short segment L&lt;&lt;543.0,453.0&gt;--&lt;543.0,463.0&gt;&gt;

* Cacute (U+0106) contains a short segment L&lt;&lt;543.0,453.0&gt;--&lt;543.0,463.0&gt;&gt;

* Ccedilla (U+00C7) contains a short segment L&lt;&lt;543.0,453.0&gt;--&lt;543.0,463.0&gt;&gt;

* G (U+0047) contains a short segment L&lt;&lt;538.0,477.0&gt;--&lt;538.0,480.0&gt;&gt;

* G (U+0047) contains a short segment L&lt;&lt;564.0,111.0&gt;--&lt;542.0,111.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;435.0,129.0&gt;--&lt;456.0,129.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;726.0,633.0&gt;--&lt;705.0,633.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;184.0,633.0&gt;--&lt;163.0,633.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;511.0,157.0&gt;--&lt;532.0,157.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;182.0,618.0&gt;--&lt;161.0,618.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;511.0,157.0&gt;--&lt;532.0,157.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;182.0,618.0&gt;--&lt;161.0,618.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;511.0,157.0&gt;--&lt;532.0,157.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;182.0,618.0&gt;--&lt;161.0,618.0&gt;&gt;

* S (U+0053) contains a short segment L&lt;&lt;123.0,231.0&gt;--&lt;123.0,222.0&gt;&gt;

* S (U+0053) contains a short segment L&lt;&lt;496.0,459.0&gt;--&lt;496.0,467.0&gt;&gt;

* Sacute (U+015A) contains a short segment L&lt;&lt;123.0,231.0&gt;--&lt;123.0,222.0&gt;&gt;

* Sacute (U+015A) contains a short segment L&lt;&lt;496.0,459.0&gt;--&lt;496.0,467.0&gt;&gt;

* Scaron (U+0160) contains a short segment L&lt;&lt;123.0,231.0&gt;--&lt;123.0,222.0&gt;&gt;

* Scaron (U+0160) contains a short segment L&lt;&lt;496.0,459.0&gt;--&lt;496.0,467.0&gt;&gt;

* uni1E9E (U+1E9E) contains a short segment L&lt;&lt;403.0,391.0&gt;--&lt;416.0,391.0&gt;&gt;

* U (U+0055) contains a short segment L&lt;&lt;530.0,94.0&gt;--&lt;509.0,94.0&gt;&gt;

* Uacute (U+00DA) contains a short segment L&lt;&lt;530.0,94.0&gt;--&lt;509.0,94.0&gt;&gt;

* Ucircumflex (U+00DB) contains a short segment L&lt;&lt;530.0,94.0&gt;--&lt;509.0,94.0&gt;&gt;

* Udieresis (U+00DC) contains a short segment L&lt;&lt;530.0,94.0&gt;--&lt;509.0,94.0&gt;&gt;

* Ugrave (U+00D9) contains a short segment L&lt;&lt;530.0,94.0&gt;--&lt;509.0,94.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;262.0,57.0&gt;--&lt;283.0,57.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;669.0,57.0&gt;--&lt;690.0,57.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;486.0,541.0&gt;--&lt;464.0,541.0&gt;&gt;

* X (U+0058) contains a short segment L&lt;&lt;323.0,382.0&gt;--&lt;344.0,382.0&gt;&gt;

* X (U+0058) contains a short segment L&lt;&lt;342.0,326.0&gt;--&lt;321.0,326.0&gt;&gt;

* Aogonek.ss03 contains a short segment L&lt;&lt;527.0,0.0&gt;--&lt;525.0,0.0&gt;&gt;

* N.ss03 contains a short segment L&lt;&lt;503.0,157.0&gt;--&lt;524.0,157.0&gt;&gt;

* N.ss03 contains a short segment L&lt;&lt;174.0,618.0&gt;--&lt;153.0,618.0&gt;&gt;

* Nacute.ss03 contains a short segment L&lt;&lt;503.0,157.0&gt;--&lt;524.0,157.0&gt;&gt;

* Nacute.ss03 contains a short segment L&lt;&lt;174.0,618.0&gt;--&lt;153.0,618.0&gt;&gt;

* Ntilde.ss03 contains a short segment L&lt;&lt;503.0,157.0&gt;--&lt;524.0,157.0&gt;&gt;

* Ntilde.ss03 contains a short segment L&lt;&lt;174.0,618.0&gt;--&lt;153.0,618.0&gt;&gt;

* uni1E9E.ss03 contains a short segment L&lt;&lt;378.0,391.0&gt;--&lt;392.0,391.0&gt;&gt;

* U.ss03 contains a short segment L&lt;&lt;522.0,94.0&gt;--&lt;501.0,94.0&gt;&gt;

* Uacute.ss03 contains a short segment L&lt;&lt;522.0,94.0&gt;--&lt;501.0,94.0&gt;&gt;

* Ucircumflex.ss03 contains a short segment L&lt;&lt;522.0,94.0&gt;--&lt;501.0,94.0&gt;&gt;

* Udieresis.ss03 contains a short segment L&lt;&lt;522.0,94.0&gt;--&lt;501.0,94.0&gt;&gt;

* Ugrave.ss03 contains a short segment L&lt;&lt;522.0,94.0&gt;--&lt;501.0,94.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;443.0,129.0&gt;--&lt;465.0,129.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;735.0,633.0&gt;--&lt;713.0,633.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;192.0,633.0&gt;--&lt;171.0,633.0&gt;&gt;

* ae (U+00E6) contains a short segment L&lt;&lt;458.0,261.0&gt;--&lt;458.0,247.0&gt;&gt;

* e (U+0065) contains a short segment L&lt;&lt;122.0,261.0&gt;--&lt;122.0,247.0&gt;&gt;

* eacute (U+00E9) contains a short segment L&lt;&lt;122.0,261.0&gt;--&lt;122.0,247.0&gt;&gt;

* ecircumflex (U+00EA) contains a short segment L&lt;&lt;122.0,261.0&gt;--&lt;122.0,247.0&gt;&gt;

* edieresis (U+00EB) contains a short segment L&lt;&lt;122.0,261.0&gt;--&lt;122.0,247.0&gt;&gt;

* egrave (U+00E8) contains a short segment L&lt;&lt;122.0,261.0&gt;--&lt;122.0,247.0&gt;&gt;

* eogonek (U+0119) contains a short segment L&lt;&lt;122.0,261.0&gt;--&lt;122.0,247.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;150.0,452.0&gt;--&lt;172.0,452.0&gt;&gt;

* oe (U+0153) contains a short segment L&lt;&lt;522.0,261.0&gt;--&lt;522.0,247.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;239.0,55.0&gt;--&lt;261.0,55.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;604.0,55.0&gt;--&lt;626.0,55.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;442.0,389.0&gt;--&lt;421.0,389.0&gt;&gt;

* three (U+0033) contains a short segment L&lt;&lt;122.0,231.0&gt;--&lt;122.0,222.0&gt;&gt;

* five (U+0035) contains a short segment L&lt;&lt;140.0,231.0&gt;--&lt;140.0,222.0&gt;&gt;

* uni2153 (U+2153) contains a short segment L&lt;&lt;476.0,102.0&gt;--&lt;476.0,97.0&gt;&gt;

* uni2154 (U+2154) contains a short segment L&lt;&lt;503.0,102.0&gt;--&lt;503.0,97.0&gt;&gt;

* threequarters (U+00BE) contains a short segment L&lt;&lt;101.0,470.0&gt;--&lt;101.0,465.0&gt;&gt;

* uni2083 (U+2083) contains a short segment L&lt;&lt;101.0,102.0&gt;--&lt;101.0,97.0&gt;&gt;

* uni00B3 (U+00B3) contains a short segment L&lt;&lt;101.0,470.0&gt;--&lt;101.0,465.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;199.0,558.0&gt;--&lt;205.0,562.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;231.0,562.0&gt;--&lt;237.0,558.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;244.0,534.0&gt;--&lt;242.0,527.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;222.0,511.0&gt;--&lt;214.0,511.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;192.0,527.0&gt;--&lt;190.0,534.0&gt;&gt;

* at (U+0040) contains a short segment L&lt;&lt;524.0,333.0&gt;--&lt;524.0,359.0&gt;&gt;

* ampersand (U+0026) contains a short segment L&lt;&lt;487.0,154.0&gt;--&lt;508.0,154.0&gt;&gt;

* ampersand (U+0026) contains a short segment L&lt;&lt;268.0,337.0&gt;--&lt;269.0,335.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;127.0,69.0&gt;--&lt;127.0,68.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;446.0,525.0&gt;--&lt;446.0,526.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;619.0,409.0&gt;--&lt;633.0,409.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;775.0,643.0&gt;--&lt;760.0,643.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;490.0,643.0&gt;--&lt;475.0,643.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;190.0,492.0&gt;--&lt;196.0,497.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;232.0,497.0&gt;--&lt;238.0,492.0&gt;&gt;

* estimated (U+212E) contains a short segment B&lt;&lt;205.0,335.0&gt;-&lt;195.0,335.0&gt;-&lt;195.0,325.0&gt;&gt;

* dollar (U+0024) contains a short segment L&lt;&lt;120.0,231.0&gt;--&lt;120.0,222.0&gt;&gt;

* dollar (U+0024) contains a short segment L&lt;&lt;494.0,459.0&gt;--&lt;494.0,467.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;128.0,317.0&gt;-&lt;127.0,331.0&gt;-&lt;127.0,345.0&gt;&gt;

* sterling (U+00A3) contains a short segment L&lt;&lt;487.0,459.0&gt;--&lt;487.0,473.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;298.0,369.0&gt;--&lt;320.0,369.0&gt;&gt;

* uni2126 (U+2126) contains a short segment L&lt;&lt;218.0,57.0&gt;--&lt;218.0,79.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[17] MozillaHeadline-CondensedBold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1110, but got 944 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024, The Mozilla Foundation&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Licensed under the Open Font License, version 1.1 or later.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;MozillaHeadline-Bold.ttf. Got MozillaHeadline-CondensedBold.ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Mozilla Headline</td>
<td align="left">Mozilla Headline</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Bold</td>
<td align="left">Bold</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Mozilla Headline Bold</td>
<td align="left">Mozilla Headline Bold</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>MozillaHeadlineCnd-Bold</strong></td>
<td align="left"><strong>MozillaHeadline-Bold</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: uni2153	Contours detected: 4	Expected: 3

- Glyph name: uni2154	Contours detected: 4	Expected: 1 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- j_acutecomb

- uni004A0301

- uni0308.case.narrow
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, old-permic, coptic, duployan, canadian-aboriginal, tifinagh, hebrew, math, syriac, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, symbols, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+1F409 DRAGON: not included in any glyphset definition</li>
<li>U+1F432 DRAGON FACE: not included in any glyphset definition</li>
<li>U+1F4BB PERSONAL COMPUTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Oslash (U+00D8): X=307.0,Y=692.0 (should be at cap-height 690?)

* Oslash (U+00D8): X=173.0,Y=-2.0 (should be at baseline 0?)

* Q (U+0051): X=179.0,Y=-2.0 (should be at baseline 0?)

* Q (U+0051): X=296.0,Y=2.0 (should be at baseline 0?)

* g (U+0067): X=394.0,Y=-1.0 (should be at baseline 0?)

* braceleft (U+007B): X=239.0,Y=691.0 (should be at cap-height 690?)

* braceleft (U+007B): X=197.0,Y=691.0 (should be at cap-height 690?)

* braceleft (U+007B): X=197.0,Y=-1.0 (should be at baseline 0?)

* braceleft (U+007B): X=239.0,Y=-1.0 (should be at baseline 0?)

* braceright (U+007D): X=24.0,Y=-1.0 (should be at baseline 0?)

* braceright (U+007D): X=66.0,Y=-1.0 (should be at baseline 0?)

* braceright (U+007D): X=66.0,Y=691.0 (should be at cap-height 690?)

* braceright (U+007D): X=24.0,Y=691.0 (should be at cap-height 690?)

* bracketleft (U+005B): X=221.0,Y=691.0 (should be at cap-height 690?)

* bracketleft (U+005B): X=159.0,Y=691.0 (should be at cap-height 690?)

* bracketleft (U+005B): X=159.0,Y=-1.0 (should be at baseline 0?)

* bracketleft (U+005B): X=221.0,Y=-1.0 (should be at baseline 0?)

* bracketright (U+005D): X=23.0,Y=-1.0 (should be at baseline 0?)

* bracketright (U+005D): X=85.0,Y=-1.0 (should be at baseline 0?)

* bracketright (U+005D): X=85.0,Y=691.0 (should be at cap-height 690?)

* bracketright (U+005D): X=23.0,Y=691.0 (should be at cap-height 690?)

* u1F409 (U+1F409): X=148.0,Y=0.5 (should be at baseline 0?)

* u1F432 (U+1F432): X=148.0,Y=0.5 (should be at baseline 0?)

* dollar (U+0024): X=172.0,Y=-1.0 (should be at baseline 0?)

* dollar (U+0024): X=173.0,Y=691.0 (should be at cap-height 690?)

* dollar (U+0024): X=261.0,Y=691.0 (should be at cap-height 690?)

* dollar (U+0024): X=260.0,Y=-1.0 (should be at baseline 0?)

* uni00B5 (U+00B5): X=164.0,Y=-2.0 (should be at baseline 0?)

* tildecomb.case: X=144.0,Y=691.0 (should be at cap-height 690?)

* tildecomb.case: X=70.0,Y=691.0 (should be at cap-height 690?)

* breve (U+02D8): X=163.0,Y=692.0 (should be at cap-height 690?)

* breve (U+02D8): X=237.0,Y=692.0 (should be at cap-height 690?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* exclam (U+0021): L&lt;&lt;166.0,690.0&gt;--&lt;166.0,592.0&gt;&gt; -&gt; L&lt;&lt;166.0,592.0&gt;--&lt;139.0,170.0&gt;&gt;

* exclam (U+0021): L&lt;&lt;64.0,170.0&gt;--&lt;38.0,592.0&gt;&gt; -&gt; L&lt;&lt;38.0,592.0&gt;--&lt;38.0,690.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;139.0,364.0&gt;--&lt;166.0,-58.0&gt;&gt; -&gt; L&lt;&lt;166.0,-58.0&gt;--&lt;166.0,-156.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;38.0,-156.0&gt;--&lt;38.0,-58.0&gt;&gt; -&gt; L&lt;&lt;38.0,-58.0&gt;--&lt;64.0,364.0&gt;&gt;

* exclamdown.case: L&lt;&lt;139.0,520.0&gt;--&lt;166.0,98.0&gt;&gt; -&gt; L&lt;&lt;166.0,98.0&gt;--&lt;166.0,0.0&gt;&gt;

* exclamdown.case: L&lt;&lt;38.0,0.0&gt;--&lt;38.0,98.0&gt;&gt; -&gt; L&lt;&lt;38.0,98.0&gt;--&lt;64.0,520.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* M (U+004D) contains a short segment L&lt;&lt;322.0,284.0&gt;--&lt;346.0,284.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;498.0,577.0&gt;--&lt;475.0,577.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;190.0,577.0&gt;--&lt;166.0,577.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;187.0,112.0&gt;--&lt;211.0,112.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;461.0,112.0&gt;--&lt;485.0,112.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;346.0,437.0&gt;--&lt;322.0,437.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;328.0,284.0&gt;--&lt;351.0,284.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;504.0,577.0&gt;--&lt;480.0,577.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;195.0,577.0&gt;--&lt;172.0,577.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;150.0,437.0&gt;--&lt;174.0,437.0&gt;&gt;

* germandbls (U+00DF) contains a short segment L&lt;&lt;210.0,405.0&gt;--&lt;231.0,405.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;178.0,109.0&gt;--&lt;202.0,109.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;433.0,109.0&gt;--&lt;457.0,109.0&gt;&gt;

* w (U+0077) contains a short segment L&lt;&lt;327.0,300.0&gt;--&lt;304.0,300.0&gt;&gt;

* g.ss02 contains a short segment L&lt;&lt;155.0,4.0&gt;--&lt;155.0,0.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;165.0,549.0&gt;--&lt;171.0,553.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;197.0,553.0&gt;--&lt;203.0,549.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;210.0,525.0&gt;--&lt;208.0,518.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;188.0,502.0&gt;--&lt;180.0,502.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;158.0,518.0&gt;--&lt;156.0,525.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;302.0,427.5&gt;-&lt;292.0,416.0&gt;-&lt;292.0,396.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;488.0,481.0&gt;--&lt;503.0,481.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;593.0,619.0&gt;--&lt;578.0,619.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;410.0,619.0&gt;--&lt;395.0,619.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;148.0,485.0&gt;--&lt;155.0,491.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;207.0,491.0&gt;--&lt;214.0,485.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;230.0,491.0&gt;--&lt;236.0,487.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;236.0,203.0&gt;--&lt;230.0,199.0&gt;&gt;

* estimated (U+212E) contains a short segment B&lt;&lt;192.0,335.0&gt;-&lt;182.0,335.0&gt;-&lt;182.0,325.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;77.0,335.0&gt;-&lt;77.0,340.0&gt;-&lt;77.0,345.0&gt;&gt;

* breve (U+02D8) contains a short segment L&lt;&lt;163.0,694.0&gt;--&lt;163.0,692.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[16] MozillaHeadline-ExpandedBold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1110, but got 944 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024, The Mozilla Foundation&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Licensed under the Open Font License, version 1.1 or later.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;MozillaHeadline-Bold.ttf. Got MozillaHeadline-ExpandedBold.ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Mozilla Headline</td>
<td align="left">Mozilla Headline</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Bold</td>
<td align="left">Bold</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Mozilla Headline Bold</td>
<td align="left">Mozilla Headline Bold</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>MozillaHeadlineExp-Bold</strong></td>
<td align="left"><strong>MozillaHeadline-Bold</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: uni2153	Contours detected: 4	Expected: 3

- Glyph name: uni2154	Contours detected: 4	Expected: 1 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- j_acutecomb

- uni004A0301

- uni0308.case.narrow
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, old-permic, coptic, duployan, canadian-aboriginal, tifinagh, hebrew, math, syriac, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, symbols, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+1F409 DRAGON: not included in any glyphset definition</li>
<li>U+1F432 DRAGON FACE: not included in any glyphset definition</li>
<li>U+1F4BB PERSONAL COMPUTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* g (U+0067): X=455.0,Y=1.0 (should be at baseline 0?)

* u1F409 (U+1F409): X=148.0,Y=0.5 (should be at baseline 0?)

* u1F432 (U+1F432): X=148.0,Y=0.5 (should be at baseline 0?)

* dollar (U+0024): X=310.0,Y=-2.0 (should be at baseline 0?)

* dollar (U+0024): X=306.0,Y=692.0 (should be at cap-height 690?)

* dollar (U+0024): X=422.0,Y=692.0 (should be at cap-height 690?)

* dollar (U+0024): X=426.0,Y=-2.0 (should be at baseline 0?)

* uni0308.case: X=6.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case: X=174.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case: X=6.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case: X=226.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case: X=394.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case: X=226.0,Y=688.0 (should be at cap-height 690?)

* uni0307.case: X=114.0,Y=688.0 (should be at cap-height 690?)

* uni0307.case: X=286.0,Y=688.0 (should be at cap-height 690?)

* uni0307.case: X=114.0,Y=688.0 (should be at cap-height 690?)

* tildecomb.case: X=117.0,Y=691.0 (should be at cap-height 690?)

* tildecomb.case: X=13.0,Y=691.0 (should be at cap-height 690?)

* uni0308.case.narrow: X=23.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case.narrow: X=184.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case.narrow: X=23.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case.narrow: X=216.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case.narrow: X=377.0,Y=688.0 (should be at cap-height 690?)

* uni0308.case.narrow: X=216.0,Y=688.0 (should be at cap-height 690?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* IJ (U+0132) contains a short segment L&lt;&lt;284.0,288.0&gt;--&lt;284.0,283.0&gt;&gt;

* Iacute_J.loclNLD contains a short segment L&lt;&lt;284.0,288.0&gt;--&lt;284.0,283.0&gt;&gt;

* three (U+0033) contains a short segment L&lt;&lt;201.0,242.0&gt;--&lt;201.0,240.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;220.0,511.0&gt;--&lt;226.0,515.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;252.0,515.0&gt;--&lt;258.0,511.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;265.0,487.0&gt;--&lt;263.0,480.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;243.0,464.0&gt;--&lt;235.0,464.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;213.0,480.0&gt;--&lt;211.0,487.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;417.0,409.5&gt;-&lt;398.0,392.0&gt;-&lt;398.0,375.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;205.0,80.0&gt;--&lt;205.0,78.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;469.0,518.0&gt;--&lt;469.0,520.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;189.0,494.0&gt;--&lt;196.0,500.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;276.0,500.0&gt;--&lt;283.0,494.0&gt;&gt;

* estimated (U+212E) contains a short segment B&lt;&lt;213.0,335.0&gt;-&lt;203.0,335.0&gt;-&lt;203.0,325.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;120.0,332.0&gt;-&lt;120.0,338.0&gt;-&lt;120.0,345.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;120.0,345.0&gt;-&lt;120.0,359.0&gt;-&lt;121.0,372.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;287.0,372.0&gt;-&lt;286.0,361.0&gt;-&lt;286.0,348.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;286.0,342.0&gt;-&lt;286.0,336.0&gt;-&lt;286.0,332.0&gt;&gt;

* sterling (U+00A3) contains a short segment L&lt;&lt;527.0,448.0&gt;--&lt;527.0,461.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;287.0,261.0&gt;--&lt;277.0,276.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;459.0,276.0&gt;--&lt;449.0,261.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[17] MozillaHeadline-BoldItalic.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1110, but got 944 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024, The Mozilla Foundation&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Licensed under the Open Font License, version 1.1 or later.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Mozilla Headline</td>
<td align="left">Mozilla Headline</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Bold Italic</td>
<td align="left">Bold Italic</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Mozilla Headline Bold Italic</td>
<td align="left">Mozilla Headline Bold Italic</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>MozillaHeadline-BoldIt</strong></td>
<td align="left"><strong>MozillaHeadline-BoldItalic</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: at	Contours detected: 3	Expected: 2

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: uni2153	Contours detected: 4	Expected: 3

- Glyph name: uni2154	Contours detected: 4	Expected: 1 or 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: at	Contours detected: 3	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fl	Contours detected: 1	Expected: 2

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: onehalf	Contours detected: 4	Expected: 3

- Glyph name: percent	Contours detected: 6	Expected: 4 or 5

- Glyph name: perthousand	Contours detected: 8	Expected: 6 or 7
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- j_acutecomb

- uni004A0301

- uni0308.case.narrow
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, old-permic, coptic, duployan, canadian-aboriginal, tifinagh, hebrew, math, syriac, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, symbols, yi, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+1F409 DRAGON: not included in any glyphset definition</li>
<li>U+1F432 DRAGON FACE: not included in any glyphset definition</li>
<li>U+1F4BB PERSONAL COMPUTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* ae (U+00E6): X=503.0,Y=0.5 (should be at baseline 0?)

* g (U+0067): X=155.0,Y=2.0 (should be at baseline 0?)

* three (U+0033): X=452.0,Y=688.0 (should be at cap-height 690?)

* eight (U+0038): X=190.0,Y=2.0 (should be at baseline 0?)

* eight (U+0038): X=463.0,Y=688.5 (should be at cap-height 690?)

* quotedblleft (U+201C): X=438.0,Y=689.0 (should be at cap-height 690?)

* quotedblleft (U+201C): X=362.0,Y=689.0 (should be at cap-height 690?)

* quotedblleft (U+201C): X=438.0,Y=689.0 (should be at cap-height 690?)

* quotedblleft (U+201C): X=257.0,Y=689.0 (should be at cap-height 690?)

* quotedblleft (U+201C): X=181.0,Y=689.0 (should be at cap-height 690?)

* quotedblleft (U+201C): X=257.0,Y=689.0 (should be at cap-height 690?)

* u1F409 (U+1F409): X=148.0,Y=0.5 (should be at baseline 0?)

* u1F432 (U+1F432): X=148.0,Y=0.5 (should be at baseline 0?)

* dollar (U+0024): X=212.0,Y=2.0 (should be at baseline 0?)

* dollar (U+0024): X=430.0,Y=688.0 (should be at cap-height 690?)

* radical (U+221A): X=77.0,Y=-1.0 (should be at baseline 0?)

* radical (U+221A): X=324.0,Y=-1.0 (should be at baseline 0?)

* radical (U+221A): X=77.0,Y=-1.0 (should be at baseline 0?)

* tildecomb.case: X=198.0,Y=691.0 (should be at cap-height 690?)

* tildecomb.case: X=105.0,Y=691.0 (should be at cap-height 690?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* exclam (U+0021): L&lt;&lt;279.0,690.0&gt;--&lt;261.0,583.0&gt;&gt; -&gt; L&lt;&lt;261.0,583.0&gt;--&lt;160.0,191.0&gt;&gt;

* exclam (U+0021): L&lt;&lt;76.0,191.0&gt;--&lt;107.0,583.0&gt;&gt; -&gt; L&lt;&lt;107.0,583.0&gt;--&lt;125.0,690.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;-17.0,-156.0&gt;--&lt;0.0,-49.0&gt;&gt; -&gt; L&lt;&lt;0.0,-49.0&gt;--&lt;102.0,343.0&gt;&gt;

* exclamdown (U+00A1): L&lt;&lt;185.0,343.0&gt;--&lt;155.0,-49.0&gt;&gt; -&gt; L&lt;&lt;155.0,-49.0&gt;--&lt;137.0,-156.0&gt;&gt;

* exclamdown.case: L&lt;&lt;211.0,499.0&gt;--&lt;181.0,107.0&gt;&gt; -&gt; L&lt;&lt;181.0,107.0&gt;--&lt;163.0,0.0&gt;&gt;

* exclamdown.case: L&lt;&lt;9.0,0.0&gt;--&lt;26.0,107.0&gt;&gt; -&gt; L&lt;&lt;26.0,107.0&gt;--&lt;128.0,499.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* at (U+0040): L&lt;&lt;491.0,286.0&gt;--&lt;499.0,334.0&gt;&gt;/L&lt;&lt;499.0,334.0&gt;--&lt;489.0,279.0&gt;&gt; = 0.8425242607405454

* at (U+0040): L&lt;&lt;499.0,334.0&gt;--&lt;489.0,279.0&gt;&gt;/L&lt;&lt;489.0,279.0&gt;--&lt;491.0,286.0&gt;&gt; = 5.640549432156892
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* AE (U+00C6) contains a short segment L&lt;&lt;440.0,570.0&gt;--&lt;439.0,569.0&gt;&gt;

* G (U+0047) contains a short segment L&lt;&lt;510.0,466.0&gt;--&lt;514.0,489.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;425.0,263.0&gt;--&lt;458.0,263.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;726.0,569.0&gt;--&lt;693.0,569.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;295.0,569.0&gt;--&lt;262.0,569.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;235.0,119.0&gt;--&lt;267.0,119.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;629.0,119.0&gt;--&lt;662.0,119.0&gt;&gt;

* W (U+0057) contains a short segment L&lt;&lt;521.0,443.0&gt;--&lt;488.0,443.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;432.0,263.0&gt;--&lt;464.0,263.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;734.0,569.0&gt;--&lt;702.0,569.0&gt;&gt;

* M.ss04 contains a short segment L&lt;&lt;303.0,569.0&gt;--&lt;270.0,569.0&gt;&gt;

* ae (U+00E6) contains a short segment L&lt;&lt;355.0,318.0&gt;--&lt;359.0,340.0&gt;&gt;

* ae (U+00E6) contains a short segment L&lt;&lt;509.0,239.0&gt;--&lt;507.0,229.0&gt;&gt;

* c (U+0063) contains a short segment L&lt;&lt;395.0,348.0&gt;--&lt;397.0,363.0&gt;&gt;

* cacute (U+0107) contains a short segment L&lt;&lt;395.0,348.0&gt;--&lt;397.0,363.0&gt;&gt;

* ccedilla (U+00E7) contains a short segment L&lt;&lt;395.0,348.0&gt;--&lt;397.0,363.0&gt;&gt;

* e (U+0065) contains a short segment L&lt;&lt;180.0,239.0&gt;--&lt;178.0,229.0&gt;&gt;

* eacute (U+00E9) contains a short segment L&lt;&lt;180.0,239.0&gt;--&lt;178.0,229.0&gt;&gt;

* ecircumflex (U+00EA) contains a short segment L&lt;&lt;180.0,239.0&gt;--&lt;178.0,229.0&gt;&gt;

* edieresis (U+00EB) contains a short segment L&lt;&lt;180.0,239.0&gt;--&lt;178.0,229.0&gt;&gt;

* egrave (U+00E8) contains a short segment L&lt;&lt;180.0,239.0&gt;--&lt;178.0,229.0&gt;&gt;

* eogonek (U+0119) contains a short segment L&lt;&lt;180.0,239.0&gt;--&lt;178.0,229.0&gt;&gt;

* g (U+0067) contains a short segment L&lt;&lt;155.0,4.0&gt;--&lt;155.0,2.0&gt;&gt;

* oe (U+0153) contains a short segment L&lt;&lt;573.0,239.0&gt;--&lt;571.0,229.0&gt;&gt;

* s (U+0073) contains a short segment L&lt;&lt;157.0,172.0&gt;--&lt;155.0,158.0&gt;&gt;

* s (U+0073) contains a short segment L&lt;&lt;371.0,362.0&gt;--&lt;373.0,376.0&gt;&gt;

* sacute (U+015B) contains a short segment L&lt;&lt;157.0,172.0&gt;--&lt;155.0,158.0&gt;&gt;

* sacute (U+015B) contains a short segment L&lt;&lt;371.0,362.0&gt;--&lt;373.0,376.0&gt;&gt;

* scaron (U+0161) contains a short segment L&lt;&lt;157.0,172.0&gt;--&lt;155.0,158.0&gt;&gt;

* scaron (U+0161) contains a short segment L&lt;&lt;371.0,362.0&gt;--&lt;373.0,376.0&gt;&gt;

* six (U+0036) contains a short segment L&lt;&lt;460.0,495.0&gt;--&lt;462.0,510.0&gt;&gt;

* nine (U+0039) contains a short segment L&lt;&lt;188.0,195.0&gt;--&lt;185.0,180.0&gt;&gt;

* uni2153 (U+2153) contains a short segment L&lt;&lt;482.0,107.0&gt;--&lt;481.0,101.0&gt;&gt;

* uni2154 (U+2154) contains a short segment L&lt;&lt;509.0,107.0&gt;--&lt;508.0,101.0&gt;&gt;

* threequarters (U+00BE) contains a short segment L&lt;&lt;169.0,475.0&gt;--&lt;168.0,469.0&gt;&gt;

* uni2083 (U+2083) contains a short segment L&lt;&lt;107.0,107.0&gt;--&lt;106.0,101.0&gt;&gt;

* uni00B3 (U+00B3) contains a short segment L&lt;&lt;169.0,475.0&gt;--&lt;168.0,469.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;242.0,525.0&gt;--&lt;249.0,529.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;275.0,529.0&gt;--&lt;280.0,525.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;283.0,501.0&gt;--&lt;280.0,494.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;257.0,478.0&gt;--&lt;249.0,478.0&gt;&gt;

* asterisk (U+002A) contains a short segment L&lt;&lt;230.0,494.0&gt;--&lt;229.0,501.0&gt;&gt;

* at (U+0040) contains a short segment L&lt;&lt;500.0,339.0&gt;--&lt;503.0,357.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;152.0,80.0&gt;--&lt;150.0,67.0&gt;&gt;

* section (U+00A7) contains a short segment L&lt;&lt;434.0,518.0&gt;--&lt;436.0,531.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;210.0,491.0&gt;--&lt;218.0,496.0&gt;&gt;

* dagger (U+2020) contains a short segment L&lt;&lt;288.0,496.0&gt;--&lt;294.0,491.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;318.0,496.0&gt;--&lt;324.0,491.0&gt;&gt;

* daggerdbl (U+2021) contains a short segment L&lt;&lt;198.0,194.0&gt;--&lt;192.0,199.0&gt;&gt;

* estimated (U+212E) contains a short segment B&lt;&lt;205.0,335.0&gt;-&lt;195.0,335.0&gt;-&lt;195.0,325.0&gt;&gt;

* cent (U+00A2) contains a short segment L&lt;&lt;402.0,348.0&gt;--&lt;404.0,362.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;118.0,362.0&gt;-&lt;119.0,367.0&gt;-&lt;120.0,371.0&gt;&gt;

* Euro (U+20AC) contains a short segment L&lt;&lt;562.0,475.0&gt;--&lt;566.0,499.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;233.0,260.0&gt;--&lt;230.0,268.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;386.0,268.0&gt;--&lt;381.0,261.0&gt;&gt;

* breve (U+02D8) contains a short segment L&lt;&lt;223.0,701.0&gt;--&lt;223.0,700.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_logo contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;409.0,252.0&gt;--&lt;441.0,252.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;648.0,569.0&gt;--&lt;616.0,569.0&gt;&gt;

* mozilla_wordmark contains a short segment L&lt;&lt;234.0,569.0&gt;--&lt;202.0,569.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 46 | 91 | 856 | 43 | 733 | 0 | 
| 0% | 0% | 3% | 5% | 48% | 2% | 41% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
