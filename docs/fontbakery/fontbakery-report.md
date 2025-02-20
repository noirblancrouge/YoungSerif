## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[13] YoungSerif-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 295, but got 275 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɔ, ɛ, Ɛ, ɔ</td>
<td align="left">bm_Latn (Bambara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɔ, Ɛ, Ɔ, ɛ</td>
<td align="left">dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɛ, ɔ, Ɔ, Ɛ</td>
<td align="left">fat_Latn (Fanti)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɗ, ɓ, Ɓ, ɗ, Ƴ, ƴ</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ƴ, ƙ, Ɓ, Ƙ, ɓ, Ƴ, Ɗ, ɗ</td>
<td align="left">ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɔ, Ɛ, ɛ, ɔ</td>
<td align="left">tw_akuapem_Latn (Akuapem Twi)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɛ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɛ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɵ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɵ</td>
<td align="left">ig_Latn (Igbo)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 🔥 **FAIL** <p>Young Serif Regular: OS/2 sTypoAscender is 930 when it should be 1046</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Young Serif Regular: OS/2 sTypoDescender is -275 when it should be -366</p>
 [code: bad-typo-descender]



* 🔥 **FAIL** <p>Young Serif Regular: hhea Ascender is 930 when it should be 1046</p>
 [code: bad-hhea-ascender]



* 🔥 **FAIL** <p>Young Serif Regular: hhea Descender is -275 when it should be -366</p>
 [code: bad-hhea-descender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: uhorn	Contours detected: 2	Expected: 1

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

- Glyph name: uni1EED	Contours detected: 3	Expected: 2

- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: colonmonetary	Contours detected: 2	Expected: 1 or 3

- Glyph name: uniFFFC	Contours detected: 8	Expected: 22

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: colonmonetary	Contours detected: 2	Expected: 1 or 3

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: uhorn	Contours detected: 2	Expected: 1

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

- Glyph name: uni1EED	Contours detected: 3	Expected: 2

- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uniFFFC	Contours detected: 8	Expected: 22

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni2070.zero

- uni2080.zero

- zero.osf.zero
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, coptic, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, hebrew, tai-le, tifinagh, canadian-aboriginal, math, duployan, coptic, syriac, malayalam, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, duployan, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: thai, caucasian-albanian, sunuwar, gothic, cherokee, tifinagh, syriac</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, math, greek</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2010 HYPHEN: try adding one of: armenian, hebrew, syloti-nagri, sundanese, lisu, coptic, kayah-li, sora-sompeng, yi, kaithi, arabic, kharoshthi, cham</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+203D INTERROBANG: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+2048 QUESTION EXCLAMATION MARK: try adding mongolian</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2105 CARE OF: try adding math</li>
<li>U+2106 CADA UNA: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+21BA ANTICLOCKWISE OPEN CIRCLE ARROW: try adding math</li>
<li>U+21BB CLOCKWISE OPEN CIRCLE ARROW: try adding math</li>
<li>U+21C4 RIGHTWARDS ARROW OVER LEFTWARDS ARROW: try adding math</li>
<li>U+21C5 UPWARDS ARROW LEFTWARDS OF DOWNWARDS ARROW: try adding math</li>
<li>U+21E7 UPWARDS WHITE ARROW: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, math, yi, symbols</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2317 VIEWDATA SQUARE: try adding symbols</li>
<li>U+2318 PLACE OF INTEREST SIGN: try adding symbols</li>
<li>U+2325 OPTION KEY: try adding symbols</li>
<li>U+23CE RETURN SYMBOL: try adding symbols</li>
<li>U+23CF EJECT SYMBOL: try adding symbols</li>
<li>U+23E9 BLACK RIGHT-POINTING DOUBLE TRIANGLE: try adding symbols</li>
<li>U+23EA BLACK LEFT-POINTING DOUBLE TRIANGLE: try adding symbols</li>
<li>U+23ED BLACK RIGHT-POINTING DOUBLE TRIANGLE WITH VERTICAL BAR: try adding symbols</li>
<li>U+23EE BLACK LEFT-POINTING DOUBLE TRIANGLE WITH VERTICAL BAR: try adding symbols</li>
<li>U+23F5 BLACK MEDIUM RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+23F8 DOUBLE VERTICAL BAR: try adding symbols</li>
<li>U+23F9 BLACK SQUARE FOR STOP: try adding symbols</li>
<li>U+23FA BLACK CIRCLE FOR RECORD: try adding symbols</li>
<li>U+2460 CIRCLED DIGIT ONE: try adding one of: mongolian, yi, symbols</li>
<li>U+2461 CIRCLED DIGIT TWO: try adding one of: mongolian, yi, symbols</li>
<li>U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, yi, symbols</li>
<li>U+2463 CIRCLED DIGIT FOUR: try adding one of: mongolian, yi, symbols</li>
<li>U+2464 CIRCLED DIGIT FIVE: try adding one of: mongolian, yi, symbols</li>
<li>U+2465 CIRCLED DIGIT SIX: try adding one of: mongolian, yi, symbols</li>
<li>U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, yi, symbols</li>
<li>U+2467 CIRCLED DIGIT EIGHT: try adding one of: mongolian, yi, symbols</li>
<li>U+2468 CIRCLED DIGIT NINE: try adding one of: mongolian, yi, symbols</li>
<li>U+24B6 CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+24B7 CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+24B8 CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+24B9 CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+24BA CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+24BB CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+24BC CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+24BD CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+24BE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+24BF CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+24C0 CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+24C1 CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+24C2 CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+24C3 CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+24C4 CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+24C5 CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+24C6 CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+24C7 CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+24C8 CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+24C9 CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+24CA CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+24CB CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+24CC CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+24CD CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+24CE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+24CF CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+24D0 CIRCLED LATIN SMALL LETTER A: try adding symbols</li>
<li>U+24D1 CIRCLED LATIN SMALL LETTER B: try adding symbols</li>
<li>U+24D2 CIRCLED LATIN SMALL LETTER C: try adding symbols</li>
<li>U+24D3 CIRCLED LATIN SMALL LETTER D: try adding symbols</li>
<li>U+24D4 CIRCLED LATIN SMALL LETTER E: try adding symbols</li>
<li>U+24D5 CIRCLED LATIN SMALL LETTER F: try adding symbols</li>
<li>U+24D6 CIRCLED LATIN SMALL LETTER G: try adding symbols</li>
<li>U+24D7 CIRCLED LATIN SMALL LETTER H: try adding symbols</li>
<li>U+24D8 CIRCLED LATIN SMALL LETTER I: try adding symbols</li>
<li>U+24D9 CIRCLED LATIN SMALL LETTER J: try adding symbols</li>
<li>U+24DA CIRCLED LATIN SMALL LETTER K: try adding symbols</li>
<li>U+24DB CIRCLED LATIN SMALL LETTER L: try adding symbols</li>
<li>U+24DC CIRCLED LATIN SMALL LETTER M: try adding symbols</li>
<li>U+24DD CIRCLED LATIN SMALL LETTER N: try adding symbols</li>
<li>U+24DE CIRCLED LATIN SMALL LETTER O: try adding symbols</li>
<li>U+24DF CIRCLED LATIN SMALL LETTER P: try adding symbols</li>
<li>U+24E0 CIRCLED LATIN SMALL LETTER Q: try adding symbols</li>
<li>U+24E1 CIRCLED LATIN SMALL LETTER R: try adding symbols</li>
<li>U+24E2 CIRCLED LATIN SMALL LETTER S: try adding symbols</li>
<li>U+24E3 CIRCLED LATIN SMALL LETTER T: try adding symbols</li>
<li>U+24E4 CIRCLED LATIN SMALL LETTER U: try adding symbols</li>
<li>U+24E5 CIRCLED LATIN SMALL LETTER V: try adding symbols</li>
<li>U+24E6 CIRCLED LATIN SMALL LETTER W: try adding symbols</li>
<li>U+24E7 CIRCLED LATIN SMALL LETTER X: try adding symbols</li>
<li>U+24E8 CIRCLED LATIN SMALL LETTER Y: try adding symbols</li>
<li>U+24E9 CIRCLED LATIN SMALL LETTER Z: try adding symbols</li>
<li>U+24EA CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols</li>
<li>U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols</li>
<li>U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols</li>
<li>U+25C6 BLACK DIAMOND: try adding symbols</li>
<li>U+25C7 WHITE DIAMOND: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: miao, balinese, khudawadi, hanifi-rohingya, devanagari, tagalog, thaana, thai, tirhuta, sharada, hebrew, oriya, mahajani, buginese, bassa-vah, warang-citi, batak, adlam, syriac, tai-le, telugu, tai-viet, siddham, kannada, buhid, music, gunjala-gondi, tibetan, tai-tham, math, kaithi, grantha, new-tai-lue, chakma, soyombo, sundanese, canadian-aboriginal, yi, masaram-gondi, sogdian, bengali, gurmukhi, gujarati, lao, tifinagh, zanabazar-square, duployan, kayah-li, cham, psalter-pahlavi, modi, old-permic, malayalam, takri, pahawh-hmong, newa, mandaic, khojki, mende-kikakui, wancho, rejang, coptic, phags-pa, ahom, sinhala, mongolian, elbasan, marchen, limbu, tamil, javanese, nko, osage, dogra, khmer, kharoshthi, symbols, syloti-nagri, meetei-mayek, tagbanwa, hanunoo, bhaiksuki, brahmi, caucasian-albanian, armenian, lepcha, saurashtra, myanmar, manichaean</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+2606 WHITE STAR: try adding symbols</li>
<li>U+261A BLACK LEFT POINTING INDEX: try adding symbols</li>
<li>U+261B BLACK RIGHT POINTING INDEX: try adding symbols</li>
<li>U+261C WHITE LEFT POINTING INDEX: try adding symbols</li>
<li>U+261D WHITE UP POINTING INDEX: try adding symbols</li>
<li>U+261E WHITE RIGHT POINTING INDEX: try adding symbols</li>
<li>U+261F WHITE DOWN POINTING INDEX: try adding symbols</li>
<li>U+262F YIN YANG: try adding symbols</li>
<li>U+2639 WHITE FROWNING FACE: try adding symbols</li>
<li>U+263A WHITE SMILING FACE: try adding symbols</li>
<li>U+263B BLACK SMILING FACE: try adding symbols</li>
<li>U+2660 BLACK SPADE SUIT: try adding symbols</li>
<li>U+2663 BLACK CLUB SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+2666 BLACK DIAMOND SUIT: try adding symbols</li>
<li>U+2713 CHECK MARK: try adding symbols</li>
<li>U+272F PINWHEEL STAR: try adding symbols</li>
<li>U+2735 EIGHT POINTED PINWHEEL STAR: try adding symbols</li>
<li>U+273F BLACK FLORETTE: try adding symbols</li>
<li>U+2740 WHITE FLORETTE: try adding symbols</li>
<li>U+2766 FLORAL HEART: try adding symbols</li>
<li>U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols</li>
<li>U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols</li>
<li>U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols</li>
<li>U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols</li>
<li>U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols</li>
<li>U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols</li>
<li>U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols</li>
<li>U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols</li>
<li>U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols</li>
<li>U+2B1B BLACK LARGE SQUARE: try adding symbols</li>
<li>U+2B1C WHITE LARGE SQUARE: try adding symbols</li>
<li>U+2B98 THREE-D TOP-LIGHTED LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B99 THREE-D RIGHT-LIGHTED UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9A THREE-D TOP-LIGHTED RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9B THREE-D LEFT-LIGHTED DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9C BLACK LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9D BLACK UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9E BLACK RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9F BLACK DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+E133 : not included in any glyphset definition</li>
<li>U+E134 : not included in any glyphset definition</li>
<li>U+E135 : not included in any glyphset definition</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FFFC OBJECT REPLACEMENT CHARACTER: not included in any glyphset definition</li>
<li>U+1F150 NEGATIVE CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+1F151 NEGATIVE CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+1F152 NEGATIVE CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+1F153 NEGATIVE CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+1F154 NEGATIVE CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+1F155 NEGATIVE CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+1F156 NEGATIVE CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+1F157 NEGATIVE CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+1F158 NEGATIVE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+1F159 NEGATIVE CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+1F15A NEGATIVE CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+1F15B NEGATIVE CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+1F15C NEGATIVE CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+1F15D NEGATIVE CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+1F15E NEGATIVE CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+1F15F NEGATIVE CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+1F160 NEGATIVE CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+1F161 NEGATIVE CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+1F162 NEGATIVE CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+1F163 NEGATIVE CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+1F164 NEGATIVE CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+1F165 NEGATIVE CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+1F166 NEGATIVE CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+1F167 NEGATIVE CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+1F168 NEGATIVE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+1F169 NEGATIVE CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+1F500 TWISTED RIGHTWARDS ARROWS: not included in any glyphset definition</li>
<li>U+1F501 CLOCKWISE RIGHTWARDS AND LEFTWARDS OPEN CIRCLE ARROWS: not included in any glyphset definition</li>
<li>U+1F502 CLOCKWISE RIGHTWARDS AND LEFTWARDS OPEN CIRCLE ARROWS WITH CIRCLED ONE OVERLAY: not included in any glyphset definition</li>
<li>U+1F503 CLOCKWISE DOWNWARDS AND UPWARDS OPEN CIRCLE ARROWS: try adding symbols</li>
<li>U+1F504 ANTICLOCKWISE DOWNWARDS AND UPWARDS OPEN CIRCLE ARROWS: not included in any glyphset definition</li>
<li>U+1F5A2 BLACK UP POINTING BACKHAND INDEX: try adding symbols</li>
<li>U+1F5A3 BLACK DOWN POINTING BACKHAND INDEX: try adding symbols</li>
<li>U+1F7CF HEAVY EIGHT POINTED BLACK STAR: try adding symbols</li>
<li>U+1F7D3 HEAVY TWELVE POINTED BLACK STAR: try adding symbols</li>
<li>U+1F7D4 HEAVY TWELVE POINTED PINWHEEL STAR: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: j̑</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: j̉ j̏ j̛̉ j̛̏ j̛̑ j̣̉ j̣̏ j̣̑ j̤̉ j̤̏ j̤̑ j̦̉ j̦̏ j̦̑ j̧̉ j̧̏ j̧̑ j̨̉ j̨̏ j̨̑</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* dong (U+20AB): L&lt;&lt;370.0,439.0&gt;--&lt;370.0,495.0&gt;&gt; -&gt; L&lt;&lt;370.0,495.0&gt;--&lt;370.0,496.0&gt;&gt;

* u1F5A2 (U+1F5A2): L&lt;&lt;184.0,304.0&gt;--&lt;192.0,276.0&gt;&gt; -&gt; L&lt;&lt;192.0,276.0&gt;--&lt;201.0,243.0&gt;&gt;

* u1F5A2 (U+1F5A2): L&lt;&lt;186.0,239.0&gt;--&lt;177.0,271.0&gt;&gt; -&gt; L&lt;&lt;177.0,271.0&gt;--&lt;169.0,299.0&gt;&gt;

* u1F5A2 (U+1F5A2): L&lt;&lt;209.0,245.0&gt;--&lt;200.0,278.0&gt;&gt; -&gt; L&lt;&lt;200.0,278.0&gt;--&lt;192.0,306.0&gt;&gt;

* u1F5A2 (U+1F5A2): L&lt;&lt;270.0,474.0&gt;--&lt;271.0,471.0&gt;&gt; -&gt; L&lt;&lt;271.0,471.0&gt;--&lt;281.0,447.0&gt;&gt;

* u1F5A2 (U+1F5A2): L&lt;&lt;642.0,415.0&gt;--&lt;645.0,421.0&gt;&gt; -&gt; L&lt;&lt;645.0,421.0&gt;--&lt;650.0,433.0&gt;&gt;

* u1F5A2 (U+1F5A2): L&lt;&lt;643.0,438.0&gt;--&lt;640.0,432.0&gt;&gt; -&gt; L&lt;&lt;640.0,432.0&gt;--&lt;633.0,417.0&gt;&gt;

* u1F5A3 (U+1F5A3): L&lt;&lt;171.0,295.0&gt;--&lt;174.0,301.0&gt;&gt; -&gt; L&lt;&lt;174.0,301.0&gt;--&lt;181.0,316.0&gt;&gt;

* u1F5A3 (U+1F5A3): L&lt;&lt;172.0,318.0&gt;--&lt;169.0,312.0&gt;&gt; -&gt; L&lt;&lt;169.0,312.0&gt;--&lt;164.0,300.0&gt;&gt;

* u1F5A3 (U+1F5A3): L&lt;&lt;544.0,259.0&gt;--&lt;543.0,262.0&gt;&gt; -&gt; L&lt;&lt;543.0,262.0&gt;--&lt;533.0,286.0&gt;&gt;

* u1F5A3 (U+1F5A3): L&lt;&lt;605.0,488.0&gt;--&lt;614.0,455.0&gt;&gt; -&gt; L&lt;&lt;614.0,455.0&gt;--&lt;622.0,427.0&gt;&gt;

* u1F5A3 (U+1F5A3): L&lt;&lt;628.0,494.0&gt;--&lt;637.0,462.0&gt;&gt; -&gt; L&lt;&lt;637.0,462.0&gt;--&lt;645.0,434.0&gt;&gt;

* u1F5A3 (U+1F5A3): L&lt;&lt;630.0,429.0&gt;--&lt;622.0,457.0&gt;&gt; -&gt; L&lt;&lt;622.0,457.0&gt;--&lt;613.0,490.0&gt;&gt;

* u1F7D4 (U+1F7D4): L&lt;&lt;540.0,197.0&gt;--&lt;663.0,191.0&gt;&gt; -&gt; L&lt;&lt;663.0,191.0&gt;--&lt;663.0,191.0&gt;&gt;

* uni20AD (U+20AD): L&lt;&lt;485.0,361.0&gt;--&lt;487.0,361.0&gt;&gt; -&gt; L&lt;&lt;487.0,361.0&gt;--&lt;611.0,363.0&gt;&gt;

* uni261A (U+261A): L&lt;&lt;472.0,484.0&gt;--&lt;448.0,494.0&gt;&gt; -&gt; L&lt;&lt;448.0,494.0&gt;--&lt;445.0,495.0&gt;&gt;

* uni261A (U+261A): L&lt;&lt;486.0,115.0&gt;--&lt;498.0,120.0&gt;&gt; -&gt; L&lt;&lt;498.0,120.0&gt;--&lt;504.0,123.0&gt;&gt;

* uni261A (U+261A): L&lt;&lt;502.0,132.0&gt;--&lt;487.0,125.0&gt;&gt; -&gt; L&lt;&lt;487.0,125.0&gt;--&lt;481.0,122.0&gt;&gt;

* uni261A (U+261A): L&lt;&lt;613.0,573.0&gt;--&lt;641.0,565.0&gt;&gt; -&gt; L&lt;&lt;641.0,565.0&gt;--&lt;674.0,556.0&gt;&gt;

* uni261A (U+261A): L&lt;&lt;620.0,596.0&gt;--&lt;648.0,588.0&gt;&gt; -&gt; L&lt;&lt;648.0,588.0&gt;--&lt;680.0,579.0&gt;&gt;

* uni261A (U+261A): L&lt;&lt;676.0,564.0&gt;--&lt;643.0,573.0&gt;&gt; -&gt; L&lt;&lt;643.0,573.0&gt;--&lt;615.0,581.0&gt;&gt;

* uni261B (U+261B): L&lt;&lt;344.0,579.0&gt;--&lt;376.0,588.0&gt;&gt; -&gt; L&lt;&lt;376.0,588.0&gt;--&lt;404.0,596.0&gt;&gt;

* uni261B (U+261B): L&lt;&lt;350.0,556.0&gt;--&lt;383.0,565.0&gt;&gt; -&gt; L&lt;&lt;383.0,565.0&gt;--&lt;411.0,573.0&gt;&gt;

* uni261B (U+261B): L&lt;&lt;409.0,581.0&gt;--&lt;381.0,573.0&gt;&gt; -&gt; L&lt;&lt;381.0,573.0&gt;--&lt;348.0,564.0&gt;&gt;

* uni261B (U+261B): L&lt;&lt;520.0,123.0&gt;--&lt;526.0,120.0&gt;&gt; -&gt; L&lt;&lt;526.0,120.0&gt;--&lt;538.0,115.0&gt;&gt;

* uni261B (U+261B): L&lt;&lt;543.0,122.0&gt;--&lt;537.0,125.0&gt;&gt; -&gt; L&lt;&lt;537.0,125.0&gt;--&lt;522.0,132.0&gt;&gt;

* uni261B (U+261B): L&lt;&lt;579.0,495.0&gt;--&lt;576.0,494.0&gt;&gt; -&gt; L&lt;&lt;576.0,494.0&gt;--&lt;552.0,484.0&gt;&gt;

* uni261C (U+261C): L&lt;&lt;510.0,109.0&gt;--&lt;504.0,106.0&gt;&gt; -&gt; L&lt;&lt;504.0,106.0&gt;--&lt;492.0,101.0&gt;&gt;

* uni261C (U+261C): L&lt;&lt;620.0,596.0&gt;--&lt;648.0,588.0&gt;&gt; -&gt; L&lt;&lt;648.0,588.0&gt;--&lt;680.0,579.0&gt;&gt;

* uni261C (U+261C): L&lt;&lt;669.0,540.0&gt;--&lt;636.0,550.0&gt;&gt; -&gt; L&lt;&lt;636.0,550.0&gt;--&lt;609.0,558.0&gt;&gt;

* uni261C (U+261C): L&lt;&lt;798.0,149.0&gt;--&lt;838.0,150.0&gt;&gt; -&gt; L&lt;&lt;838.0,150.0&gt;--&lt;883.0,150.0&gt;&gt;

* uni261D (U+261D): L&lt;&lt;186.0,239.0&gt;--&lt;177.0,271.0&gt;&gt; -&gt; L&lt;&lt;177.0,271.0&gt;--&lt;169.0,299.0&gt;&gt;

* uni261D (U+261D): L&lt;&lt;207.0,310.0&gt;--&lt;215.0,283.0&gt;&gt; -&gt; L&lt;&lt;215.0,283.0&gt;--&lt;225.0,250.0&gt;&gt;

* uni261D (U+261D): L&lt;&lt;615.0,36.0&gt;--&lt;615.0,81.0&gt;&gt; -&gt; L&lt;&lt;615.0,81.0&gt;--&lt;616.0,121.0&gt;&gt;

* uni261D (U+261D): L&lt;&lt;664.0,427.0&gt;--&lt;659.0,415.0&gt;&gt; -&gt; L&lt;&lt;659.0,415.0&gt;--&lt;656.0,409.0&gt;&gt;

* uni261E (U+261E): L&lt;&lt;141.0,150.0&gt;--&lt;186.0,150.0&gt;&gt; -&gt; L&lt;&lt;186.0,150.0&gt;--&lt;226.0,149.0&gt;&gt;

* uni261E (U+261E): L&lt;&lt;344.0,579.0&gt;--&lt;376.0,588.0&gt;&gt; -&gt; L&lt;&lt;376.0,588.0&gt;--&lt;404.0,596.0&gt;&gt;

* uni261E (U+261E): L&lt;&lt;415.0,558.0&gt;--&lt;388.0,550.0&gt;&gt; -&gt; L&lt;&lt;388.0,550.0&gt;--&lt;355.0,540.0&gt;&gt;

* uni261E (U+261E): L&lt;&lt;532.0,101.0&gt;--&lt;520.0,106.0&gt;&gt; -&gt; L&lt;&lt;520.0,106.0&gt;--&lt;514.0,109.0&gt;&gt;

* uni261F (U+261F): L&lt;&lt;150.0,306.0&gt;--&lt;155.0,318.0&gt;&gt; -&gt; L&lt;&lt;155.0,318.0&gt;--&lt;158.0,324.0&gt;&gt;

* uni261F (U+261F): L&lt;&lt;199.0,697.0&gt;--&lt;199.0,652.0&gt;&gt; -&gt; L&lt;&lt;199.0,652.0&gt;--&lt;198.0,612.0&gt;&gt;

* uni261F (U+261F): L&lt;&lt;607.0,423.0&gt;--&lt;599.0,450.0&gt;&gt; -&gt; L&lt;&lt;599.0,450.0&gt;--&lt;589.0,483.0&gt;&gt;

* uni261F (U+261F): L&lt;&lt;628.0,494.0&gt;--&lt;637.0,462.0&gt;&gt; -&gt; L&lt;&lt;637.0,462.0&gt;--&lt;645.0,434.0&gt;&gt;

* uni272F (U+272F): L&lt;&lt;415.0,688.0&gt;--&lt;494.0,463.0&gt;&gt; -&gt; L&lt;&lt;494.0,463.0&gt;--&lt;502.0,443.0&gt;&gt;

* uni2735 (U+2735): L&lt;&lt;337.0,491.0&gt;--&lt;339.0,499.0&gt;&gt; -&gt; L&lt;&lt;339.0,499.0&gt;--&lt;379.0,686.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* ae (U+00E6): L&lt;&lt;346.0,-9.0&gt;--&lt;356.0,73.0&gt;&gt;/B&lt;&lt;356.0,73.0&gt;-&lt;344.0,42.0&gt;-&lt;312.5,15.5&gt;&gt; = 14.208302348654348

* aeacute (U+01FD): L&lt;&lt;346.0,-9.0&gt;--&lt;356.0,73.0&gt;&gt;/B&lt;&lt;356.0,73.0&gt;-&lt;344.0,42.0&gt;-&lt;312.5,15.5&gt;&gt; = 14.208302348654348

* club (U+2663): B&lt;&lt;382.0,247.0&gt;-&lt;368.0,293.0&gt;-&lt;366.0,369.0&gt;&gt;/B&lt;&lt;366.0,369.0&gt;-&lt;365.0,293.0&gt;-&lt;350.0,247.0&gt;&gt; = 2.2612840918455555

* heart (U+2665): B&lt;&lt;345.5,578.5&gt;-&lt;362.0,527.0&gt;-&lt;366.0,440.0&gt;&gt;/B&lt;&lt;366.0,440.0&gt;-&lt;371.0,527.0&gt;-&lt;387.0,578.5&gt;&gt; = 5.92167754747822

* p.blackCircled: B&lt;&lt;461.5,490.5&gt;-&lt;449.0,474.0&gt;-&lt;445.0,463.0&gt;&gt;/B&lt;&lt;445.0,463.0&gt;-&lt;449.0,497.0&gt;-&lt;450.5,511.0&gt;&gt; = 13.27326971414301

* spade (U+2660): B&lt;&lt;382.0,246.0&gt;-&lt;368.0,298.0&gt;-&lt;366.0,386.0&gt;&gt;/B&lt;&lt;366.0,386.0&gt;-&lt;364.0,298.0&gt;-&lt;350.0,246.0&gt;&gt; = 2.603905345157587

* uni24DF (U+24DF): B&lt;&lt;450.5,511.0&gt;-&lt;449.0,497.0&gt;-&lt;445.0,463.0&gt;&gt;/B&lt;&lt;445.0,463.0&gt;-&lt;449.0,474.0&gt;-&lt;461.5,490.5&gt;&gt; = 13.27326971414301

* uni262F (U+262F): B&lt;&lt;879.5,445.5&gt;-&lt;925.0,394.0&gt;-&lt;927.0,295.0&gt;&gt;/B&lt;&lt;927.0,295.0&gt;-&lt;928.0,303.0&gt;-&lt;928.0,311.0&gt;&gt; = 8.28234941703128

* uni2735 (U+2735): L&lt;&lt;288.0,307.0&gt;--&lt;187.0,147.0&gt;&gt;/L&lt;&lt;187.0,147.0&gt;--&lt;388.0,348.0&gt;&gt; = 12.737830703874106

* uni2735 (U+2735): L&lt;&lt;289.0,389.0&gt;--&lt;102.0,348.0&gt;&gt;/L&lt;&lt;102.0,348.0&gt;--&lt;388.0,348.0&gt;&gt; = 12.366497153214814

* uni2735 (U+2735): L&lt;&lt;346.0,249.0&gt;--&lt;388.0,63.0&gt;&gt;/L&lt;&lt;388.0,63.0&gt;--&lt;388.0,348.0&gt;&gt; = 12.724355685422363

* uni2735 (U+2735): L&lt;&lt;346.0,447.0&gt;--&lt;187.0,549.0&gt;&gt;/L&lt;&lt;187.0,549.0&gt;--&lt;388.0,348.0&gt;&gt; = 12.319445256636591

* uni2735 (U+2735): L&lt;&lt;430.0,448.0&gt;--&lt;388.0,634.0&gt;&gt;/L&lt;&lt;388.0,634.0&gt;--&lt;388.0,348.0&gt;&gt; = 12.724355685422363

* uni2735 (U+2735): L&lt;&lt;431.0,249.0&gt;--&lt;589.0,147.0&gt;&gt;/L&lt;&lt;589.0,147.0&gt;--&lt;388.0,348.0&gt;&gt; = 12.154941697222196

* uni2735 (U+2735): L&lt;&lt;488.0,308.0&gt;--&lt;674.0,348.0&gt;&gt;/L&lt;&lt;674.0,348.0&gt;--&lt;388.0,348.0&gt;&gt; = 12.13682445529227

* uni2735 (U+2735): L&lt;&lt;488.0,390.0&gt;--&lt;589.0,549.0&gt;&gt;/L&lt;&lt;589.0,549.0&gt;--&lt;388.0,348.0&gt;&gt; = 12.575465499744425
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u1F5A2 (U+1F5A2): L&lt;&lt;259.0,539.0&gt;--&lt;260.0,698.0&gt;&gt;

* u1F5A2 (U+1F5A2): L&lt;&lt;276.0,713.0&gt;--&lt;275.0,502.0&gt;&gt;

* u1F5A2 (U+1F5A2): L&lt;&lt;283.0,502.0&gt;--&lt;284.0,713.0&gt;&gt;

* u1F5A3 (U+1F5A3): L&lt;&lt;531.0,231.0&gt;--&lt;530.0,20.0&gt;&gt;

* u1F5A3 (U+1F5A3): L&lt;&lt;538.0,20.0&gt;--&lt;539.0,231.0&gt;&gt;

* u1F5A3 (U+1F5A3): L&lt;&lt;555.0,194.0&gt;--&lt;554.0,35.0&gt;&gt;

* uni2196 (U+2196): L&lt;&lt;50.0,300.0&gt;--&lt;52.0,633.0&gt;&gt;

* uni2197 (U+2197): L&lt;&lt;173.0,681.0&gt;--&lt;506.0,679.0&gt;&gt;

* uni2198 (U+2198): L&lt;&lt;537.0,379.0&gt;--&lt;535.0,46.0&gt;&gt;

* uni2199 (U+2199): L&lt;&lt;432.0,0.0&gt;--&lt;99.0,2.0&gt;&gt;

* uni261A (U+261A): L&lt;&lt;206.0,481.0&gt;--&lt;417.0,482.0&gt;&gt;

* uni261A (U+261A): L&lt;&lt;221.0,505.0&gt;--&lt;380.0,506.0&gt;&gt;

* uni261A (U+261A): L&lt;&lt;417.0,490.0&gt;--&lt;206.0,489.0&gt;&gt;

* uni261B (U+261B): L&lt;&lt;607.0,482.0&gt;--&lt;818.0,481.0&gt;&gt;

* uni261B (U+261B): L&lt;&lt;644.0,506.0&gt;--&lt;803.0,505.0&gt;&gt;

* uni261B (U+261B): L&lt;&lt;818.0,489.0&gt;--&lt;607.0,490.0&gt;&gt;

* uni261C (U+261C): L&lt;&lt;221.0,505.0&gt;--&lt;380.0,506.0&gt;&gt;

* uni261C (U+261C): L&lt;&lt;417.0,466.0&gt;--&lt;221.0,465.0&gt;&gt;

* uni261D (U+261D): L&lt;&lt;259.0,539.0&gt;--&lt;260.0,698.0&gt;&gt;

* uni261D (U+261D): L&lt;&lt;300.0,698.0&gt;--&lt;299.0,502.0&gt;&gt;

* uni261E (U+261E): L&lt;&lt;644.0,506.0&gt;--&lt;803.0,505.0&gt;&gt;

* uni261E (U+261E): L&lt;&lt;803.0,465.0&gt;--&lt;607.0,466.0&gt;&gt;

* uni261F (U+261F): L&lt;&lt;514.0,35.0&gt;--&lt;515.0,231.0&gt;&gt;

* uni261F (U+261F): L&lt;&lt;555.0,194.0&gt;--&lt;554.0,35.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 4 | 9 | 105 | 7 | 111 | 0 | 
| 0% | 0% | 2% | 4% | 44% | 3% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
