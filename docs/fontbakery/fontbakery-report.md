## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[14] Panamera-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1500. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1680 when it should be at least 1800 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1916, but got 1280 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 651, but got 400 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- uni01CE.ss01

	- uni030C.alt

	- whiteCtircle
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 900 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 1001:
logicalnot

Width = 1230:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<213.0,1050.0>--<213.0,666.0>> -> L<<213.0,666.0>--<202.0,553.0>>

	* d (U+0064): L<<704.0,0.0>--<704.0,108.0>> -> L<<704.0,108.0>--<711.0,186.0>>

	* d (U+0064): L<<714.0,555.0>--<704.0,666.0>> -> L<<704.0,666.0>--<704.0,1050.0>>

	* dcaron (U+010F): L<<704.0,0.0>--<704.0,108.0>> -> L<<704.0,108.0>--<711.0,186.0>>

	* dcaron (U+010F): L<<714.0,555.0>--<704.0,666.0>> -> L<<704.0,666.0>--<704.0,1050.0>>

	* dcroat (U+0111): L<<704.0,0.0>--<704.0,108.0>> -> L<<704.0,108.0>--<711.0,186.0>>

	* dcroat (U+0111): L<<714.0,555.0>--<704.0,666.0>> -> L<<704.0,666.0>--<704.0,852.0>>

	* dmacronbelow (U+1E0F): L<<704.0,0.0>--<704.0,108.0>> -> L<<704.0,108.0>--<711.0,186.0>>

	* dmacronbelow (U+1E0F): L<<714.0,555.0>--<704.0,666.0>> -> L<<704.0,666.0>--<704.0,1050.0>>

	* exclam (U+0021): L<<172.0,324.0>--<142.0,889.0>> -> L<<142.0,889.0>--<142.0,1096.0>>

	* exclam (U+0021): L<<323.0,1096.0>--<323.0,889.0>> -> L<<323.0,889.0>--<294.0,324.0>>

	* exclamdown (U+00A1): L<<142.0,-286.0>--<142.0,-79.0>> -> L<<142.0,-79.0>--<172.0,486.0>>

	* exclamdown (U+00A1): L<<294.0,486.0>--<323.0,-79.0>> -> L<<323.0,-79.0>--<323.0,-286.0>>

	* g (U+0067): L<<704.0,6.0>--<704.0,120.0>> -> L<<704.0,120.0>--<710.0,184.0>>

	* g (U+0067): L<<711.0,565.0>--<704.0,642.0>> -> L<<704.0,642.0>--<704.0,750.0>>

	* gbreve (U+011F): L<<704.0,6.0>--<704.0,120.0>> -> L<<704.0,120.0>--<710.0,184.0>>

	* gbreve (U+011F): L<<711.0,565.0>--<704.0,642.0>> -> L<<704.0,642.0>--<704.0,750.0>>

	* gcaron (U+01E7): L<<704.0,6.0>--<704.0,120.0>> -> L<<704.0,120.0>--<710.0,184.0>>

	* gcaron (U+01E7): L<<711.0,565.0>--<704.0,642.0>> -> L<<704.0,642.0>--<704.0,750.0>>

	* gcircumflex (U+011D): L<<704.0,6.0>--<704.0,120.0>> -> L<<704.0,120.0>--<710.0,184.0>>

	* gcircumflex (U+011D): L<<711.0,565.0>--<704.0,642.0>> -> L<<704.0,642.0>--<704.0,750.0>>

	* gdotaccent (U+0121): L<<704.0,6.0>--<704.0,120.0>> -> L<<704.0,120.0>--<710.0,184.0>>

	* gdotaccent (U+0121): L<<711.0,565.0>--<704.0,642.0>> -> L<<704.0,642.0>--<704.0,750.0>>

	* p (U+0070): L<<202.0,198.0>--<213.0,84.0>> -> L<<213.0,84.0>--<213.0,-300.0>>

	* q (U+0071): L<<704.0,-300.0>--<704.0,84.0>> -> L<<704.0,84.0>--<714.0,196.0>>

	* q (U+0071): L<<711.0,565.0>--<704.0,642.0>> -> L<<704.0,642.0>--<704.0,750.0>>

	* thorn (U+00FE): L<<189.0,147.0>--<195.0,69.0>> -> L<<195.0,69.0>--<195.0,-321.0>>

	* thorn (U+00FE): L<<195.0,1177.0>--<195.0,672.0>> -> L<<195.0,672.0>--<189.0,592.0>>

	* uni0123 (U+0123): L<<704.0,6.0>--<704.0,120.0>> -> L<<704.0,120.0>--<710.0,184.0>>

	* uni0123 (U+0123): L<<711.0,565.0>--<704.0,642.0>> -> L<<704.0,642.0>--<704.0,750.0>>

	* uni1E0D (U+1E0D): L<<704.0,0.0>--<704.0,108.0>> -> L<<704.0,108.0>--<711.0,186.0>>

	* uni1E0D (U+1E0D): L<<714.0,555.0>--<704.0,666.0>> -> L<<704.0,666.0>--<704.0,1050.0>>

	* uni1E21 (U+1E21): L<<704.0,6.0>--<704.0,120.0>> -> L<<704.0,120.0>--<710.0,184.0>>

	* uni1E21 (U+1E21): L<<711.0,565.0>--<704.0,642.0>> -> L<<704.0,642.0>--<704.0,750.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<948.0,0.0>--<948.0,309.0>>/B<<948.0,309.0>-<940.0,219.0>-<897.5,147.5>> = 5.0796078600145425

	* Gbreve (U+011E): L<<948.0,0.0>--<948.0,309.0>>/B<<948.0,309.0>-<940.0,219.0>-<897.5,147.5>> = 5.0796078600145425

	* Gcaron (U+01E6): L<<948.0,0.0>--<948.0,309.0>>/B<<948.0,309.0>-<940.0,219.0>-<897.5,147.5>> = 5.0796078600145425

	* Gcircumflex (U+011C): L<<948.0,0.0>--<948.0,309.0>>/B<<948.0,309.0>-<940.0,219.0>-<897.5,147.5>> = 5.0796078600145425

	* Gdotaccent (U+0120): L<<948.0,0.0>--<948.0,309.0>>/B<<948.0,309.0>-<940.0,219.0>-<897.5,147.5>> = 5.0796078600145425

	* b (U+0062): B<<301.5,40.0>-<233.0,96.0>-<205.0,187.0>>/L<<205.0,187.0>--<213.0,108.0>> = 11.32033664668834

	* b (U+0062): L<<213.0,666.0>--<202.0,553.0>>/B<<202.0,553.0>-<230.0,649.0>-<300.0,709.0>> = 10.70025744500241

	* d (U+0064): B<<615.0,710.0>-<685.0,651.0>-<714.0,555.0>>/L<<714.0,555.0>--<704.0,666.0>> = 11.66080680207051

	* d (U+0064): L<<704.0,108.0>--<711.0,186.0>>/B<<711.0,186.0>-<682.0,95.0>-<613.5,40.0>> = 12.5479176568006

	* dcaron (U+010F): B<<615.0,710.0>-<685.0,651.0>-<714.0,555.0>>/L<<714.0,555.0>--<704.0,666.0>> = 11.66080680207051

	* dcaron (U+010F): L<<704.0,108.0>--<711.0,186.0>>/B<<711.0,186.0>-<682.0,95.0>-<613.5,40.0>> = 12.5479176568006

	* dcroat (U+0111): B<<615.0,710.0>-<685.0,651.0>-<714.0,555.0>>/L<<714.0,555.0>--<704.0,666.0>> = 11.66080680207051

	* dcroat (U+0111): L<<704.0,108.0>--<711.0,186.0>>/B<<711.0,186.0>-<682.0,95.0>-<613.5,40.0>> = 12.5479176568006

	* dmacronbelow (U+1E0F): B<<615.0,710.0>-<685.0,651.0>-<714.0,555.0>>/L<<714.0,555.0>--<704.0,666.0>> = 11.66080680207051

	* dmacronbelow (U+1E0F): L<<704.0,108.0>--<711.0,186.0>>/B<<711.0,186.0>-<682.0,95.0>-<613.5,40.0>> = 12.5479176568006

	* f (U+0066): L<<13.0,752.0>--<202.0,752.0>>/B<<202.0,752.0>-<148.0,764.0>-<114.0,806.0>> = 12.528807709151492

	* g (U+0067): B<<613.5,710.5>-<682.0,655.0>-<711.0,565.0>>/L<<711.0,565.0>--<704.0,642.0>> = 12.66566516294425

	* g (U+0067): L<<704.0,120.0>--<710.0,184.0>>/B<<710.0,184.0>-<680.0,93.0>-<610.5,37.5>> = 12.89002948472302

	* gbreve (U+011F): B<<613.5,710.5>-<682.0,655.0>-<711.0,565.0>>/L<<711.0,565.0>--<704.0,642.0>> = 12.66566516294425

	* gbreve (U+011F): L<<704.0,120.0>--<710.0,184.0>>/B<<710.0,184.0>-<680.0,93.0>-<610.5,37.5>> = 12.89002948472302

	* gcaron (U+01E7): B<<613.5,710.5>-<682.0,655.0>-<711.0,565.0>>/L<<711.0,565.0>--<704.0,642.0>> = 12.66566516294425

	* gcaron (U+01E7): L<<704.0,120.0>--<710.0,184.0>>/B<<710.0,184.0>-<680.0,93.0>-<610.5,37.5>> = 12.89002948472302

	* gcircumflex (U+011D): B<<613.5,710.5>-<682.0,655.0>-<711.0,565.0>>/L<<711.0,565.0>--<704.0,642.0>> = 12.66566516294425

	* gcircumflex (U+011D): L<<704.0,120.0>--<710.0,184.0>>/B<<710.0,184.0>-<680.0,93.0>-<610.5,37.5>> = 12.89002948472302

	* gdotaccent (U+0121): B<<613.5,710.5>-<682.0,655.0>-<711.0,565.0>>/L<<711.0,565.0>--<704.0,642.0>> = 12.66566516294425

	* gdotaccent (U+0121): L<<704.0,120.0>--<710.0,184.0>>/B<<710.0,184.0>-<680.0,93.0>-<610.5,37.5>> = 12.89002948472302

	* p (U+0070): B<<300.0,41.5>-<230.0,101.0>-<202.0,198.0>>/L<<202.0,198.0>--<213.0,84.0>> = 10.589824983137806

	* p (U+0070): L<<213.0,642.0>--<205.0,563.0>>/B<<205.0,563.0>-<233.0,654.0>-<301.5,710.0>> = 11.32033664668834

	* q (U+0071): B<<613.5,710.5>-<682.0,655.0>-<711.0,565.0>>/L<<711.0,565.0>--<704.0,642.0>> = 12.66566516294425

	* q (U+0071): L<<704.0,84.0>--<714.0,196.0>>/B<<714.0,196.0>-<685.0,100.0>-<615.0,41.0>> = 11.706526373848634

	* uni0122 (U+0122): L<<948.0,0.0>--<948.0,309.0>>/B<<948.0,309.0>-<940.0,219.0>-<897.5,147.5>> = 5.0796078600145425

	* uni0123 (U+0123): B<<613.5,710.5>-<682.0,655.0>-<711.0,565.0>>/L<<711.0,565.0>--<704.0,642.0>> = 12.66566516294425

	* uni0123 (U+0123): L<<704.0,120.0>--<710.0,184.0>>/B<<710.0,184.0>-<680.0,93.0>-<610.5,37.5>> = 12.89002948472302

	* uni1E0D (U+1E0D): B<<615.0,710.0>-<685.0,651.0>-<714.0,555.0>>/L<<714.0,555.0>--<704.0,666.0>> = 11.66080680207051

	* uni1E0D (U+1E0D): L<<704.0,108.0>--<711.0,186.0>>/B<<711.0,186.0>-<682.0,95.0>-<613.5,40.0>> = 12.5479176568006

	* uni1E20 (U+1E20): L<<948.0,0.0>--<948.0,309.0>>/B<<948.0,309.0>-<940.0,219.0>-<897.5,147.5>> = 5.0796078600145425

	* uni1E21 (U+1E21): B<<613.5,710.5>-<682.0,655.0>-<711.0,565.0>>/L<<711.0,565.0>--<704.0,642.0>> = 12.66566516294425

	* uni1E21 (U+1E21): L<<704.0,120.0>--<710.0,184.0>>/B<<710.0,184.0>-<680.0,93.0>-<610.5,37.5>> = 12.89002948472302 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Atilde (U+00C3): L<<462.0,1188.0>--<344.0,1189.0>>

	* D (U+0044): L<<227.0,933.0>--<226.0,118.0>>

	* D (U+0044): L<<358.0,934.0>--<227.0,933.0>>

	* Dcaron (U+010E): L<<227.0,933.0>--<226.0,118.0>>

	* Dcaron (U+010E): L<<358.0,934.0>--<227.0,933.0>>

	* Dcroat (U+0110): L<<543.0,934.0>--<411.0,933.0>>

	* Dmacronbelow (U+1E0E): L<<227.0,933.0>--<226.0,118.0>>

	* Dmacronbelow (U+1E0E): L<<358.0,934.0>--<227.0,933.0>>

	* Eth (U+00D0): L<<543.0,934.0>--<411.0,933.0>>

	* IJ (U+0132): L<<1145.0,1050.0>--<1146.0,340.0>>

	* Itilde (U+0128): L<<97.0,1188.0>--<-21.0,1189.0>>

	* J (U+004A): L<<768.0,1050.0>--<769.0,340.0>>

	* Jcircumflex (U+0134): L<<768.0,1050.0>--<769.0,340.0>>

	* Lslash (U+0141): L<<67.0,472.0>--<66.0,593.0>>

	* M (U+004D): L<<1029.0,1051.0>--<1216.0,1050.0>>

	* M (U+004D): L<<80.0,1050.0>--<267.0,1051.0>>

	* Ntilde (U+00D1): L<<389.0,1188.0>--<271.0,1189.0>>

	* Otilde (U+00D5): L<<530.0,1188.0>--<412.0,1189.0>>

	* R (U+0052): L<<393.0,530.0>--<228.0,529.0>>

	* Racute (U+0154): L<<393.0,530.0>--<228.0,529.0>>

	* Rcaron (U+0158): L<<393.0,530.0>--<228.0,529.0>>

	* Rmacronbelow (U+1E5E): L<<393.0,530.0>--<228.0,529.0>>

	* U (U+0055): L<<70.0,330.0>--<72.0,1050.0>>

	* U (U+0055): L<<862.0,1050.0>--<864.0,330.0>>

	* Uacute (U+00DA): L<<70.0,330.0>--<72.0,1050.0>>

	* Uacute (U+00DA): L<<862.0,1050.0>--<864.0,330.0>>

	* Ubreve (U+016C): L<<70.0,330.0>--<72.0,1050.0>>

	* Ubreve (U+016C): L<<862.0,1050.0>--<864.0,330.0>>

	* Ucircumflex (U+00DB): L<<70.0,330.0>--<72.0,1050.0>>

	* Ucircumflex (U+00DB): L<<862.0,1050.0>--<864.0,330.0>>

	* Udieresis (U+00DC): L<<70.0,330.0>--<72.0,1050.0>>

	* Udieresis (U+00DC): L<<862.0,1050.0>--<864.0,330.0>>

	* Ugrave (U+00D9): L<<70.0,330.0>--<72.0,1050.0>>

	* Ugrave (U+00D9): L<<862.0,1050.0>--<864.0,330.0>>

	* Uhungarumlaut (U+0170): L<<70.0,330.0>--<72.0,1050.0>>

	* Uhungarumlaut (U+0170): L<<862.0,1050.0>--<864.0,330.0>>

	* Umacron (U+016A): L<<70.0,330.0>--<72.0,1050.0>>

	* Umacron (U+016A): L<<862.0,1050.0>--<864.0,330.0>>

	* Uogonek (U+0172): L<<70.0,330.0>--<72.0,1050.0>>

	* Uogonek (U+0172): L<<862.0,1050.0>--<864.0,330.0>>

	* Uring (U+016E): L<<70.0,330.0>--<72.0,1050.0>>

	* Uring (U+016E): L<<862.0,1050.0>--<864.0,330.0>>

	* Utilde (U+0168): L<<376.0,1188.0>--<258.0,1189.0>>

	* Utilde (U+0168): L<<70.0,330.0>--<72.0,1050.0>>

	* Utilde (U+0168): L<<862.0,1050.0>--<864.0,330.0>>

	* a (U+0061): L<<265.0,541.0>--<106.0,542.0>>

	* aacute (U+00E1): L<<265.0,541.0>--<106.0,542.0>>

	* abreve (U+0103): L<<265.0,541.0>--<106.0,542.0>>

	* acircumflex (U+00E2): L<<265.0,541.0>--<106.0,542.0>>

	* adieresis (U+00E4): L<<265.0,541.0>--<106.0,542.0>>

	* ae (U+00E6): L<<265.0,541.0>--<106.0,542.0>>

	* aeacute (U+01FD): L<<265.0,541.0>--<106.0,542.0>>

	* agrave (U+00E0): L<<265.0,541.0>--<106.0,542.0>>

	* amacron (U+0101): L<<265.0,541.0>--<106.0,542.0>>

	* aogonek (U+0105): L<<265.0,541.0>--<106.0,542.0>>

	* approxequal (U+2248): L<<700.0,700.0>--<828.0,699.0>>

	* aring (U+00E5): L<<265.0,541.0>--<106.0,542.0>>

	* aringacute (U+01FB): L<<265.0,541.0>--<106.0,542.0>>

	* asciitilde (U+007E): L<<700.0,565.0>--<828.0,564.0>>

	* at (U+0040): L<<596.0,535.0>--<431.0,536.0>>

	* atilde (U+00E3): L<<265.0,541.0>--<106.0,542.0>>

	* atilde (U+00E3): L<<324.0,888.0>--<206.0,889.0>>

	* b (U+0062): L<<66.0,0.0>--<64.0,1050.0>>

	* d (U+0064): L<<853.0,1050.0>--<851.0,0.0>>

	* dcaron (U+010F): L<<853.0,1050.0>--<851.0,0.0>>

	* dcroat (U+0111): L<<852.0,852.0>--<851.0,0.0>>

	* dmacronbelow (U+1E0F): L<<853.0,1050.0>--<851.0,0.0>>

	* eng (U+014B): L<<669.0,0.0>--<670.0,449.0>>

	* f (U+0066): L<<156.0,1.0>--<158.0,639.0>>

	* fi (U+FB01): L<<13.0,752.0>--<186.0,751.0>>

	* fi (U+FB01): L<<156.0,1.0>--<158.0,639.0>>

	* fi (U+FB01): L<<324.0,752.0>--<786.0,751.0>>

	* fi (U+FB01): L<<786.0,907.0>--<615.0,908.0>>

	* four (U+0034): L<<535.0,322.0>--<48.0,323.0>>

	* g (U+0067): L<<851.0,750.0>--<853.0,6.0>>

	* gbreve (U+011F): L<<851.0,750.0>--<853.0,6.0>>

	* gcaron (U+01E7): L<<851.0,750.0>--<853.0,6.0>>

	* gcircumflex (U+011D): L<<851.0,750.0>--<853.0,6.0>>

	* gdotaccent (U+0121): L<<851.0,750.0>--<853.0,6.0>>

	* itilde (U+0129): L<<103.0,888.0>--<-15.0,889.0>>

	* lslash (U+0142): L<<103.0,473.0>--<102.0,593.0>>

	* n (U+006E): L<<669.0,0.0>--<670.0,449.0>>

	* nacute (U+0144): L<<669.0,0.0>--<670.0,449.0>>

	* napostrophe (U+0149): L<<941.0,0.0>--<942.0,449.0>>

	* ncaron (U+0148): L<<669.0,0.0>--<670.0,449.0>>

	* nmacronbelow (U+1E49): L<<669.0,0.0>--<670.0,449.0>>

	* ntilde (U+00F1): L<<337.0,888.0>--<219.0,889.0>>

	* ntilde (U+00F1): L<<669.0,0.0>--<670.0,449.0>>

	* onequarter (U+00BC): L<<905.0,195.0>--<610.0,196.0>>

	* otilde (U+00F5): L<<353.0,888.0>--<235.0,889.0>>

	* p (U+0070): L<<64.0,-300.0>--<66.0,750.0>>

	* q (U+0071): L<<851.0,750.0>--<853.0,-300.0>>

	* radical (U+221A): L<<432.0,-17.0>--<312.0,-18.0>>

	* registered (U+00AE): L<<508.0,593.0>--<507.0,294.0>>

	* thorn (U+00FE): L<<46.0,-321.0>--<48.0,1177.0>>

	* threequarters (U+00BE): L<<905.0,195.0>--<610.0,196.0>>

	* tilde (U+02DC): L<<472.0,888.0>--<354.0,889.0>>

	* tildecomb (U+0303): L<<472.0,888.0>--<354.0,889.0>>

	* uni0123 (U+0123): L<<851.0,750.0>--<853.0,6.0>>

	* uni0146 (U+0146): L<<669.0,0.0>--<670.0,449.0>>

	* uni0156 (U+0156): L<<393.0,530.0>--<228.0,529.0>>

	* uni018F (U+018F): L<<78.0,559.0>--<945.0,563.0>>

	* uni0233 (U+0233): L<<15.0,750.0>--<179.0,751.0>>

	* uni0272 (U+0272): L<<669.0,0.0>--<670.0,449.0>>

	* uni1E0C (U+1E0C): L<<227.0,933.0>--<226.0,118.0>>

	* uni1E0C (U+1E0C): L<<358.0,934.0>--<227.0,933.0>>

	* uni1E0D (U+1E0D): L<<853.0,1050.0>--<851.0,0.0>>

	* uni1E21 (U+1E21): L<<851.0,750.0>--<853.0,6.0>>

	* uni1E42 (U+1E42): L<<1029.0,1051.0>--<1216.0,1050.0>>

	* uni1E42 (U+1E42): L<<80.0,1050.0>--<267.0,1051.0>>

	* uni1E45 (U+1E45): L<<669.0,0.0>--<670.0,449.0>>

	* uni1E47 (U+1E47): L<<669.0,0.0>--<670.0,449.0>>

	* uni1E4C (U+1E4C): L<<530.0,1188.0>--<412.0,1189.0>>

	* uni1E4D (U+1E4D): L<<353.0,888.0>--<235.0,889.0>>

	* uni1E4E (U+1E4E): L<<530.0,1188.0>--<412.0,1189.0>>

	* uni1E4F (U+1E4F): L<<353.0,888.0>--<235.0,889.0>>

	* uni1E5A (U+1E5A): L<<393.0,530.0>--<228.0,529.0>>

	* uni1E78 (U+1E78): L<<376.0,1188.0>--<258.0,1189.0>>

	* uni1E78 (U+1E78): L<<70.0,330.0>--<72.0,1050.0>>

	* uni1E78 (U+1E78): L<<862.0,1050.0>--<864.0,330.0>>

	* uni1E79 (U+1E79): L<<349.0,888.0>--<231.0,889.0>>

	* uni1E7A (U+1E7A): L<<70.0,330.0>--<72.0,1050.0>>

	* uni1E7A (U+1E7A): L<<862.0,1050.0>--<864.0,330.0>>

	* uni1E8F (U+1E8F): L<<15.0,750.0>--<179.0,751.0>>

	* uni1EA1 (U+1EA1): L<<265.0,541.0>--<106.0,542.0>>

	* uni1EBC (U+1EBC): L<<424.0,1188.0>--<306.0,1189.0>>

	* uni1EBD (U+1EBD): L<<371.0,888.0>--<253.0,889.0>>

	* uni1EE4 (U+1EE4): L<<70.0,330.0>--<72.0,1050.0>>

	* uni1EE4 (U+1EE4): L<<862.0,1050.0>--<864.0,330.0>>

	* uni1EF8 (U+1EF8): L<<389.0,1188.0>--<271.0,1189.0>>

	* uni1EF9 (U+1EF9): L<<15.0,750.0>--<179.0,751.0>>

	* uni1EF9 (U+1EF9): L<<326.0,888.0>--<208.0,889.0>>

	* uni2074 (U+2074): L<<324.0,788.0>--<29.0,789.0>>

	* uni2084 (U+2084): L<<324.0,195.0>--<29.0,196.0>>

	* utilde (U+0169): L<<349.0,888.0>--<231.0,889.0>>

	* y (U+0079): L<<15.0,750.0>--<179.0,751.0>>

	* yacute (U+00FD): L<<15.0,750.0>--<179.0,751.0>>

	* ycircumflex (U+0177): L<<15.0,750.0>--<179.0,751.0>>

	* ydieresis (U+00FF): L<<15.0,750.0>--<179.0,751.0>>

	* yen (U+00A5): L<<176.0,526.0>--<367.0,527.0>>

	* yen (U+00A5): L<<589.0,527.0>--<770.0,526.0>>

	* ygrave (U+1EF3): L<<15.0,750.0>--<179.0,751.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[15] Panamera-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Thin'. Expected OS/2 usWeightClass is 100, got 220. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1500. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1680 when it should be at least 1800 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1916, but got 1280 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 651, but got 400 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- uni01CE.ss01

	- uni030C.alt

	- whiteCtircle
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: copyright	Contours detected: 4	Expected: 3

	- Glyph name: ordmasculine	Contours detected: 1	Expected: 2or3

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: copyright	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ordmasculine	Contours detected: 1	Expected: 2or3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 900 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 1001:
logicalnot

Width = 1230:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* exclam (U+0021): L<<227.0,320.0>--<198.0,920.0>> -> L<<198.0,920.0>--<198.0,1097.0>>

	* exclam (U+0021): L<<266.0,1097.0>--<267.0,920.0>> -> L<<267.0,920.0>--<239.0,320.0>>

	* exclamdown (U+00A1): L<<198.0,-287.0>--<198.0,-110.0>> -> L<<198.0,-110.0>--<227.0,490.0>>

	* exclamdown (U+00A1): L<<239.0,490.0>--<267.0,-110.0>> -> L<<267.0,-110.0>--<266.0,-287.0>>

	* thorn (U+00FE): L<<87.0,303.0>--<98.0,168.0>> -> L<<98.0,168.0>--<98.0,-369.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<568.0,684.5>-<515.0,634.0>-<432.0,617.0>>/B<<432.0,617.0>-<618.0,616.0>-<717.0,539.0>> = 11.883227674796064

	* G (U+0047): L<<1005.0,0.0>--<1005.0,392.0>>/B<<1005.0,392.0>-<980.0,212.0>-<871.5,102.5>> = 7.907162702958464

	* Gbreve (U+011E): L<<1005.0,0.0>--<1005.0,392.0>>/B<<1005.0,392.0>-<980.0,212.0>-<871.5,102.5>> = 7.907162702958464

	* Gcaron (U+01E6): L<<1005.0,0.0>--<1005.0,392.0>>/B<<1005.0,392.0>-<980.0,212.0>-<871.5,102.5>> = 7.907162702958464

	* Gcircumflex (U+011C): L<<1005.0,0.0>--<1005.0,392.0>>/B<<1005.0,392.0>-<980.0,212.0>-<871.5,102.5>> = 7.907162702958464

	* Gdotaccent (U+0120): L<<1005.0,0.0>--<1005.0,392.0>>/B<<1005.0,392.0>-<980.0,212.0>-<871.5,102.5>> = 7.907162702958464

	* at (U+0040): B<<998.0,100.5>-<975.0,154.0>-<978.0,249.0>>/B<<978.0,249.0>-<966.0,145.0>-<924.0,85.5>> = 4.773205332685956

	* b (U+0062): B<<169.5,136.5>-<128.0,204.0>-<111.0,276.0>>/L<<111.0,276.0>--<120.0,200.0>> = 6.531292449371166

	* b (U+0062): L<<120.0,575.0>--<108.0,465.0>>/B<<108.0,465.0>-<124.0,539.0>-<166.5,609.0>> = 5.9746396629550205

	* d (U+0064): B<<694.5,612.0>-<737.0,543.0>-<753.0,470.0>>/L<<753.0,470.0>--<741.0,575.0>> = 5.8426906640572716

	* d (U+0064): L<<741.0,200.0>--<750.0,272.0>>/B<<750.0,272.0>-<732.0,201.0>-<690.0,134.5>> = 7.100947549849925

	* dcaron (U+010F): B<<694.5,612.0>-<737.0,543.0>-<753.0,470.0>>/L<<753.0,470.0>--<741.0,575.0>> = 5.8426906640572716

	* dcaron (U+010F): L<<741.0,200.0>--<750.0,272.0>>/B<<750.0,272.0>-<732.0,201.0>-<690.0,134.5>> = 7.100947549849925

	* dcroat (U+0111): B<<694.5,612.0>-<737.0,543.0>-<753.0,470.0>>/L<<753.0,470.0>--<741.0,575.0>> = 5.8426906640572716

	* dcroat (U+0111): L<<741.0,200.0>--<750.0,272.0>>/B<<750.0,272.0>-<732.0,201.0>-<690.0,134.5>> = 7.100947549849925

	* dmacronbelow (U+1E0F): B<<694.5,612.0>-<737.0,543.0>-<753.0,470.0>>/L<<753.0,470.0>--<741.0,575.0>> = 5.8426906640572716

	* dmacronbelow (U+1E0F): L<<741.0,200.0>--<750.0,272.0>>/B<<750.0,272.0>-<732.0,201.0>-<690.0,134.5>> = 7.100947549849925

	* f (U+0066): L<<14.0,752.0>--<284.0,752.0>>/B<<284.0,752.0>-<214.0,763.0>-<171.5,793.5>> = 8.93059010041899

	* g (U+0067): B<<691.0,615.0>-<733.0,548.0>-<750.0,477.0>>/L<<750.0,477.0>--<741.0,551.0>> = 6.530859193542142

	* g (U+0067): L<<741.0,192.0>--<751.0,272.0>>/B<<751.0,272.0>-<733.0,201.0>-<690.5,134.0>> = 7.100947549849925

	* gbreve (U+011F): B<<691.0,615.0>-<733.0,548.0>-<750.0,477.0>>/L<<750.0,477.0>--<741.0,551.0>> = 6.530859193542142

	* gbreve (U+011F): L<<741.0,192.0>--<751.0,272.0>>/B<<751.0,272.0>-<733.0,201.0>-<690.5,134.0>> = 7.100947549849925

	* gcaron (U+01E7): B<<691.0,615.0>-<733.0,548.0>-<750.0,477.0>>/L<<750.0,477.0>--<741.0,551.0>> = 6.530859193542142

	* gcaron (U+01E7): L<<741.0,192.0>--<751.0,272.0>>/B<<751.0,272.0>-<733.0,201.0>-<690.5,134.0>> = 7.100947549849925

	* gcircumflex (U+011D): B<<691.0,615.0>-<733.0,548.0>-<750.0,477.0>>/L<<750.0,477.0>--<741.0,551.0>> = 6.530859193542142

	* gcircumflex (U+011D): L<<741.0,192.0>--<751.0,272.0>>/B<<751.0,272.0>-<733.0,201.0>-<690.5,134.0>> = 7.100947549849925

	* gdotaccent (U+0121): B<<691.0,615.0>-<733.0,548.0>-<750.0,477.0>>/L<<750.0,477.0>--<741.0,551.0>> = 6.530859193542142

	* gdotaccent (U+0121): L<<741.0,192.0>--<751.0,272.0>>/B<<751.0,272.0>-<733.0,201.0>-<690.5,134.0>> = 7.100947549849925

	* p (U+0070): B<<166.5,142.0>-<124.0,212.0>-<108.0,286.0>>/L<<108.0,286.0>--<120.0,176.0>> = 5.9746396629550205

	* p (U+0070): L<<120.0,551.0>--<110.0,473.0>>/B<<110.0,473.0>-<128.0,545.0>-<169.5,612.5>> = 6.730483934615673

	* partialdiff (U+2202): B<<682.5,629.5>-<742.0,574.0>-<776.0,479.0>>/B<<776.0,479.0>-<754.0,678.0>-<689.5,819.5>> = 13.383432236181612

	* q (U+0071): B<<691.0,615.0>-<733.0,548.0>-<750.0,477.0>>/L<<750.0,477.0>--<741.0,551.0>> = 6.530859193542142

	* q (U+0071): L<<741.0,176.0>--<753.0,281.0>>/B<<753.0,281.0>-<737.0,208.0>-<694.5,139.0>> = 5.8426906640572716

	* r (U+0072): L<<117.0,750.0>--<117.0,473.0>>/B<<117.0,473.0>-<132.0,565.0>-<179.0,628.5>> = 9.260221531171469

	* racute (U+0155): L<<117.0,750.0>--<117.0,473.0>>/B<<117.0,473.0>-<132.0,565.0>-<179.0,628.5>> = 9.260221531171469

	* rcaron (U+0159): L<<117.0,750.0>--<117.0,473.0>>/B<<117.0,473.0>-<132.0,565.0>-<179.0,628.5>> = 9.260221531171469

	* rmacronbelow (U+1E5F): L<<117.0,750.0>--<117.0,473.0>>/B<<117.0,473.0>-<132.0,565.0>-<179.0,628.5>> = 9.260221531171469

	* thorn (U+00FE): B<<145.5,143.0>-<102.0,219.0>-<87.0,303.0>>/L<<87.0,303.0>--<98.0,168.0>> = 5.466417545722214

	* thorn (U+00FE): L<<98.0,530.0>--<86.0,419.0>>/B<<86.0,419.0>-<101.0,505.0>-<144.5,582.5>> = 3.723745574705754

	* u (U+0075): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* uacute (U+00FA): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* ubreve (U+016D): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* ucircumflex (U+00FB): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* udieresis (U+00FC): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* ugrave (U+00F9): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* uhungarumlaut (U+0171): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* umacron (U+016B): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* uni0122 (U+0122): L<<1005.0,0.0>--<1005.0,392.0>>/B<<1005.0,392.0>-<980.0,212.0>-<871.5,102.5>> = 7.907162702958464

	* uni0123 (U+0123): B<<691.0,615.0>-<733.0,548.0>-<750.0,477.0>>/L<<750.0,477.0>--<741.0,551.0>> = 6.530859193542142

	* uni0123 (U+0123): L<<741.0,192.0>--<751.0,272.0>>/B<<751.0,272.0>-<733.0,201.0>-<690.5,134.0>> = 7.100947549849925

	* uni0157 (U+0157): L<<117.0,750.0>--<117.0,473.0>>/B<<117.0,473.0>-<132.0,565.0>-<179.0,628.5>> = 9.260221531171469

	* uni03A9 (U+03A9): B<<928.5,115.5>-<876.0,64.0>-<807.0,50.0>>/L<<807.0,50.0>--<1113.0,50.0>> = 11.469530332866904

	* uni03A9 (U+03A9): L<<23.0,50.0>--<338.0,50.0>>/B<<338.0,50.0>-<270.0,67.0>-<220.5,109.5>> = 14.036243467926457

	* uni1E0D (U+1E0D): B<<694.5,612.0>-<737.0,543.0>-<753.0,470.0>>/L<<753.0,470.0>--<741.0,575.0>> = 5.8426906640572716

	* uni1E0D (U+1E0D): L<<741.0,200.0>--<750.0,272.0>>/B<<750.0,272.0>-<732.0,201.0>-<690.0,134.5>> = 7.100947549849925

	* uni1E20 (U+1E20): L<<1005.0,0.0>--<1005.0,392.0>>/B<<1005.0,392.0>-<980.0,212.0>-<871.5,102.5>> = 7.907162702958464

	* uni1E21 (U+1E21): B<<691.0,615.0>-<733.0,548.0>-<750.0,477.0>>/L<<750.0,477.0>--<741.0,551.0>> = 6.530859193542142

	* uni1E21 (U+1E21): L<<741.0,192.0>--<751.0,272.0>>/B<<751.0,272.0>-<733.0,201.0>-<690.5,134.0>> = 7.100947549849925

	* uni1E5B (U+1E5B): L<<117.0,750.0>--<117.0,473.0>>/B<<117.0,473.0>-<132.0,565.0>-<179.0,628.5>> = 9.260221531171469

	* uni1E79 (U+1E79): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* uni1E7B (U+1E7B): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* uni1EE5 (U+1EE5): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* uni2106 (U+2106): L<<1402.0,2.0>--<1402.0,203.0>>/B<<1402.0,203.0>-<1386.0,133.0>-<1340.0,86.0>> = 12.875001559612462

	* uni2126 (U+2126): B<<928.5,115.5>-<876.0,64.0>-<807.0,50.0>>/L<<807.0,50.0>--<1113.0,50.0>> = 11.469530332866904

	* uni2126 (U+2126): L<<23.0,50.0>--<338.0,50.0>>/B<<338.0,50.0>-<270.0,67.0>-<220.5,109.5>> = 14.036243467926457

	* uogonek (U+0173): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* uring (U+016F): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132

	* utilde (U+0169): L<<732.0,2.0>--<732.0,242.0>>/B<<732.0,242.0>-<713.0,159.0>-<658.0,102.5>> = 12.893744044882132 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* IJ (U+0132): L<<1010.0,1050.0>--<1011.0,278.0>>

	* J (U+004A): L<<719.0,1050.0>--<720.0,278.0>>

	* Jcircumflex (U+0134): L<<719.0,1050.0>--<720.0,278.0>>

	* R (U+0052): L<<336.0,603.0>--<123.0,602.0>>

	* Racute (U+0154): L<<336.0,603.0>--<123.0,602.0>>

	* Rcaron (U+0158): L<<336.0,603.0>--<123.0,602.0>>

	* Rmacronbelow (U+1E5E): L<<336.0,603.0>--<123.0,602.0>>

	* U (U+0055): L<<836.0,1050.0>--<837.0,314.0>>

	* U (U+0055): L<<96.0,314.0>--<98.0,1050.0>>

	* Uacute (U+00DA): L<<836.0,1050.0>--<837.0,314.0>>

	* Uacute (U+00DA): L<<96.0,314.0>--<98.0,1050.0>>

	* Ubreve (U+016C): L<<836.0,1050.0>--<837.0,314.0>>

	* Ubreve (U+016C): L<<96.0,314.0>--<98.0,1050.0>>

	* Ucircumflex (U+00DB): L<<836.0,1050.0>--<837.0,314.0>>

	* Ucircumflex (U+00DB): L<<96.0,314.0>--<98.0,1050.0>>

	* Udieresis (U+00DC): L<<836.0,1050.0>--<837.0,314.0>>

	* Udieresis (U+00DC): L<<96.0,314.0>--<98.0,1050.0>>

	* Ugrave (U+00D9): L<<836.0,1050.0>--<837.0,314.0>>

	* Ugrave (U+00D9): L<<96.0,314.0>--<98.0,1050.0>>

	* Uhungarumlaut (U+0170): L<<836.0,1050.0>--<837.0,314.0>>

	* Uhungarumlaut (U+0170): L<<96.0,314.0>--<98.0,1050.0>>

	* Umacron (U+016A): L<<836.0,1050.0>--<837.0,314.0>>

	* Umacron (U+016A): L<<96.0,314.0>--<98.0,1050.0>>

	* Uogonek (U+0172): L<<836.0,1050.0>--<837.0,314.0>>

	* Uogonek (U+0172): L<<96.0,314.0>--<98.0,1050.0>>

	* Uring (U+016E): L<<836.0,1050.0>--<837.0,314.0>>

	* Uring (U+016E): L<<96.0,314.0>--<98.0,1050.0>>

	* Utilde (U+0168): L<<836.0,1050.0>--<837.0,314.0>>

	* Utilde (U+0168): L<<96.0,314.0>--<98.0,1050.0>>

	* b (U+0062): L<<80.0,0.0>--<78.0,1050.0>>

	* d (U+0064): L<<783.0,1050.0>--<782.0,0.0>>

	* dcaron (U+010F): L<<783.0,1050.0>--<782.0,0.0>>

	* dcroat (U+0111): L<<783.0,912.0>--<782.0,0.0>>

	* dmacronbelow (U+1E0F): L<<783.0,1050.0>--<782.0,0.0>>

	* exclam (U+0021): L<<266.0,1097.0>--<267.0,920.0>>

	* exclamdown (U+00A1): L<<267.0,-110.0>--<266.0,-287.0>>

	* f (U+0066): L<<176.0,2.0>--<177.0,719.0>>

	* fi (U+FB01): L<<176.0,2.0>--<177.0,719.0>>

	* fi (U+FB01): L<<273.0,752.0>--<710.0,750.0>>

	* four (U+0034): L<<582.0,377.0>--<53.0,378.0>>

	* g (U+0067): L<<782.0,750.0>--<783.0,-3.0>>

	* gbreve (U+011F): L<<782.0,750.0>--<783.0,-3.0>>

	* gcaron (U+01E7): L<<782.0,750.0>--<783.0,-3.0>>

	* gcircumflex (U+011D): L<<782.0,750.0>--<783.0,-3.0>>

	* gdotaccent (U+0121): L<<782.0,750.0>--<783.0,-3.0>>

	* onequarter (U+00BC): L<<934.0,228.0>--<613.0,229.0>>

	* p (U+0070): L<<78.0,-300.0>--<80.0,750.0>>

	* q (U+0071): L<<782.0,750.0>--<783.0,-300.0>>

	* thorn (U+00FE): L<<57.0,-369.0>--<59.0,1224.0>>

	* threequarters (U+00BE): L<<934.0,228.0>--<613.0,229.0>>

	* uni0123 (U+0123): L<<782.0,750.0>--<783.0,-3.0>>

	* uni0156 (U+0156): L<<336.0,603.0>--<123.0,602.0>>

	* uni018F (U+018F): L<<42.0,509.0>--<999.0,507.0>>

	* uni1E0D (U+1E0D): L<<783.0,1050.0>--<782.0,0.0>>

	* uni1E21 (U+1E21): L<<782.0,750.0>--<783.0,-3.0>>

	* uni1E5A (U+1E5A): L<<336.0,603.0>--<123.0,602.0>>

	* uni1E78 (U+1E78): L<<836.0,1050.0>--<837.0,314.0>>

	* uni1E78 (U+1E78): L<<96.0,314.0>--<98.0,1050.0>>

	* uni1E7A (U+1E7A): L<<836.0,1050.0>--<837.0,314.0>>

	* uni1E7A (U+1E7A): L<<96.0,314.0>--<98.0,1050.0>>

	* uni1EE4 (U+1EE4): L<<836.0,1050.0>--<837.0,314.0>>

	* uni1EE4 (U+1EE4): L<<96.0,314.0>--<98.0,1050.0>>

	* uni2074 (U+2074): L<<353.0,821.0>--<32.0,822.0>>

	* uni2084 (U+2084): L<<353.0,228.0>--<32.0,229.0>>

	* yen (U+00A5): L<<135.0,488.0>--<390.0,489.0>>

	* yen (U+00A5): L<<438.0,489.0>--<690.0,488.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[17] Panamera-Heavy.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Heavy'. Expected OS/2 usWeightClass is 400, got 800. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1500. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Panamera Heavy | Panamera Heavy |
| Subfamily Name | Regular | Regular |
| Full Name | Panamera Heavy | Panamera Heavy Regular |
| Poscript Name | Panamera-Heavy | PanameraHeavy-Regular |
| Typographic Family Name | Panamera | N/A |
| Typographic Subfamily Name | Heavy | N/A | [code: bad-names]
* ⚠ **WARN** Regular missing from full name [code: lacks-regular]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1680 when it should be at least 1800 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1916, but got 1280 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 651, but got 400 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- uni01CE.ss01

	- uni030C.alt

	- whiteCtircle
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ampersand	Contours detected: 5	Expected: 1, 2or3

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: at	Contours detected: 4	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1or2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: ampersand	Contours detected: 5	Expected: 1, 2or3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: at	Contours detected: 4	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 900 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 1001:
logicalnot

Width = 1230:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=798.0,Y=-1.0 (should be at baseline 0?)

	* numbersign (U+0023): X=521.0,Y=-1.0 (should be at baseline 0?)

	* numbersign (U+0023): X=357.0,Y=-1.0 (should be at baseline 0?)

	* numbersign (U+0023): X=80.0,Y=-1.0 (should be at baseline 0?)

	* ampersand (U+0026): X=949.0,Y=1.0 (should be at baseline 0?)

	* ampersand (U+0026): X=687.5,Y=0.5 (should be at baseline 0?)

	* colon (U+003A): X=48.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=357.0,Y=-1.0 (should be at baseline 0?)

	* question (U+003F): X=257.5,Y=1051.5 (should be at cap-height 1050?)

	* M (U+004D): X=413.0,Y=1052.0 (should be at cap-height 1050?)

	* M (U+004D): X=1041.0,Y=1052.0 (should be at cap-height 1050?)

	* f (U+0066): X=11.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=110.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=428.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=624.0,Y=752.0 (should be at x-height 750?)

	* h (U+0068): X=413.0,Y=748.5 (should be at x-height 750?)

	* cent (U+00A2): X=455.0,Y=-1.0 (should be at baseline 0?)

	* cent (U+00A2): X=522.0,Y=-1.0 (should be at baseline 0?)

	* uni00B5 (U+00B5): X=542.0,Y=2.0 (should be at baseline 0?)

	* divide (U+00F7): X=290.0,Y=-1.0 (should be at baseline 0?)

	* divide (U+00F7): X=600.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=586.0,Y=-398.0 (should be at descender -400?)

	* uni0136 (U+0136): X=502.0,Y=-398.0 (should be at descender -400?)

	* uni0137 (U+0137): X=430.0,Y=-398.0 (should be at descender -400?)

	* uni013B (U+013B): X=470.0,Y=-398.0 (should be at descender -400?)

	* uni013C (U+013C): X=206.0,Y=-398.0 (should be at descender -400?)

	* uni0145 (U+0145): X=476.0,Y=-398.0 (should be at descender -400?)

	* uni0146 (U+0146): X=406.0,Y=-398.0 (should be at descender -400?)

	* uni0156 (U+0156): X=524.0,Y=-398.0 (should be at descender -400?)

	* uni0157 (U+0157): X=406.0,Y=-398.0 (should be at descender -400?)

	* uni0218 (U+0218): X=439.0,Y=-398.0 (should be at descender -400?)

	* uni0219 (U+0219): X=361.0,Y=-398.0 (should be at descender -400?)

	* uni021A (U+021A): X=500.0,Y=-398.0 (should be at descender -400?)

	* uni021B (U+021B): X=374.0,Y=-398.0 (should be at descender -400?)

	* uni0326 (U+0326): X=404.0,Y=-398.0 (should be at descender -400?)

	* uni03BC (U+03BC): X=542.0,Y=2.0 (should be at baseline 0?)

	* uni1E42 (U+1E42): X=413.0,Y=1052.0 (should be at cap-height 1050?)

	* uni1E42 (U+1E42): X=1041.0,Y=1052.0 (should be at cap-height 1050?)

	* trademark (U+2122): X=773.0,Y=1049.0 (should be at cap-height 1050?)

	* trademark (U+2122): X=1053.0,Y=1049.0 (should be at cap-height 1050?)

	* estimated (U+212E): X=591.0,Y=-1.0 (should be at baseline 0?)

	* estimated (U+212E): X=790.0,Y=1051.5 (should be at cap-height 1050?)

	* integral (U+222B): X=742.5,Y=1048.0 (should be at cap-height 1050?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<309.0,96.0>--<317.0,5.0>> -> L<<317.0,5.0>--<317.0,0.0>>

	* b (U+0062): L<<317.0,1050.0>--<317.0,770.0>> -> L<<317.0,770.0>--<307.0,644.0>>

	* d (U+0064): L<<662.0,0.0>--<662.0,5.0>> -> L<<662.0,5.0>--<670.0,99.0>>

	* d (U+0064): L<<672.0,640.0>--<662.0,770.0>> -> L<<662.0,770.0>--<662.0,1050.0>>

	* dcaron (U+010F): L<<662.0,0.0>--<662.0,5.0>> -> L<<662.0,5.0>--<670.0,99.0>>

	* dcaron (U+010F): L<<672.0,640.0>--<662.0,770.0>> -> L<<662.0,770.0>--<662.0,1050.0>>

	* dcroat (U+0111): L<<662.0,0.0>--<662.0,5.0>> -> L<<662.0,5.0>--<670.0,99.0>>

	* dcroat (U+0111): L<<672.0,640.0>--<662.0,770.0>> -> L<<662.0,770.0>--<662.0,785.0>>

	* dmacronbelow (U+1E0F): L<<662.0,0.0>--<662.0,5.0>> -> L<<662.0,5.0>--<670.0,99.0>>

	* dmacronbelow (U+1E0F): L<<672.0,640.0>--<662.0,770.0>> -> L<<662.0,770.0>--<662.0,1050.0>>

	* exclam (U+0021): L<<110.0,329.0>--<78.0,854.0>> -> L<<78.0,854.0>--<78.0,1095.0>>

	* exclam (U+0021): L<<387.0,1095.0>--<386.0,854.0>> -> L<<386.0,854.0>--<356.0,329.0>>

	* exclamdown (U+00A1): L<<356.0,481.0>--<386.0,-44.0>> -> L<<386.0,-44.0>--<387.0,-285.0>>

	* exclamdown (U+00A1): L<<78.0,-285.0>--<78.0,-44.0>> -> L<<78.0,-44.0>--<110.0,481.0>>

	* g (U+0067): L<<662.0,15.0>--<662.0,38.0>> -> L<<662.0,38.0>--<668.0,100.0>>

	* g (U+0067): L<<670.0,650.0>--<662.0,746.0>> -> L<<662.0,746.0>--<662.0,750.0>>

	* gbreve (U+011F): L<<662.0,15.0>--<662.0,38.0>> -> L<<662.0,38.0>--<668.0,100.0>>

	* gbreve (U+011F): L<<670.0,650.0>--<662.0,746.0>> -> L<<662.0,746.0>--<662.0,750.0>>

	* gcaron (U+01E7): L<<662.0,15.0>--<662.0,38.0>> -> L<<662.0,38.0>--<668.0,100.0>>

	* gcaron (U+01E7): L<<670.0,650.0>--<662.0,746.0>> -> L<<662.0,746.0>--<662.0,750.0>>

	* gcircumflex (U+011D): L<<662.0,15.0>--<662.0,38.0>> -> L<<662.0,38.0>--<668.0,100.0>>

	* gcircumflex (U+011D): L<<670.0,650.0>--<662.0,746.0>> -> L<<662.0,746.0>--<662.0,750.0>>

	* gdotaccent (U+0121): L<<662.0,15.0>--<662.0,38.0>> -> L<<662.0,38.0>--<668.0,100.0>>

	* gdotaccent (U+0121): L<<670.0,650.0>--<662.0,746.0>> -> L<<662.0,746.0>--<662.0,750.0>>

	* p (U+0070): L<<307.0,107.0>--<317.0,-19.0>> -> L<<317.0,-19.0>--<317.0,-300.0>>

	* p (U+0070): L<<317.0,750.0>--<317.0,746.0>> -> L<<317.0,746.0>--<309.0,654.0>>

	* q (U+0071): L<<662.0,-300.0>--<662.0,-19.0>> -> L<<662.0,-19.0>--<672.0,111.0>>

	* q (U+0071): L<<670.0,650.0>--<662.0,746.0>> -> L<<662.0,746.0>--<662.0,750.0>>

	* thorn (U+00FE): L<<303.0,1124.0>--<303.0,831.0>> -> L<<303.0,831.0>--<306.0,788.0>>

	* uni0123 (U+0123): L<<662.0,15.0>--<662.0,38.0>> -> L<<662.0,38.0>--<668.0,100.0>>

	* uni0123 (U+0123): L<<670.0,650.0>--<662.0,746.0>> -> L<<662.0,746.0>--<662.0,750.0>>

	* uni1E0D (U+1E0D): L<<662.0,0.0>--<662.0,5.0>> -> L<<662.0,5.0>--<670.0,99.0>>

	* uni1E0D (U+1E0D): L<<672.0,640.0>--<662.0,770.0>> -> L<<662.0,770.0>--<662.0,1050.0>>

	* uni1E21 (U+1E21): L<<662.0,15.0>--<662.0,38.0>> -> L<<662.0,38.0>--<668.0,100.0>>

	* uni1E21 (U+1E21): L<<670.0,650.0>--<662.0,746.0>> -> L<<662.0,746.0>--<662.0,750.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ccedilla (U+00C7): L<<647.0,11.0>--<602.0,-63.0>>/B<<602.0,-63.0>-<611.0,-48.0>-<635.0,-36.5>> = 0.340366963517503

	* G (U+0047): L<<882.0,0.0>--<882.0,194.0>>/B<<882.0,194.0>-<879.0,144.0>-<848.0,98.0>> = 3.4336303624505082

	* Gbreve (U+011E): L<<882.0,0.0>--<882.0,194.0>>/B<<882.0,194.0>-<879.0,144.0>-<848.0,98.0>> = 3.4336303624505082

	* Gcaron (U+01E6): L<<882.0,0.0>--<882.0,194.0>>/B<<882.0,194.0>-<879.0,144.0>-<848.0,98.0>> = 3.4336303624505082

	* Gcircumflex (U+011C): L<<882.0,0.0>--<882.0,194.0>>/B<<882.0,194.0>-<879.0,144.0>-<848.0,98.0>> = 3.4336303624505082

	* Gdotaccent (U+0120): L<<882.0,0.0>--<882.0,194.0>>/B<<882.0,194.0>-<879.0,144.0>-<848.0,98.0>> = 3.4336303624505082

	* Scedilla (U+015E): L<<502.0,11.0>--<457.0,-63.0>>/B<<457.0,-63.0>-<466.0,-48.0>-<490.0,-36.5>> = 0.340366963517503

	* at (U+0040): B<<500.0,0.0>-<438.0,22.0>-<398.0,60.0>>/B<<398.0,60.0>-<451.0,-22.0>-<535.0,-68.0>> = 13.592538962175178

	* ccedilla (U+00E7): L<<487.0,11.0>--<442.0,-63.0>>/B<<442.0,-63.0>-<451.0,-48.0>-<475.0,-36.5>> = 0.340366963517503

	* cedilla (U+00B8): L<<497.0,11.0>--<452.0,-63.0>>/B<<452.0,-63.0>-<461.0,-48.0>-<485.0,-36.5>> = 0.340366963517503

	* nine (U+0039): B<<414.5,387.0>-<418.0,392.0>-<425.0,392.0>>/B<<425.0,392.0>-<334.0,403.0>-<254.5,447.5>> = 6.892423122485113

	* scedilla (U+015F): L<<424.0,11.0>--<379.0,-63.0>>/B<<379.0,-63.0>-<388.0,-48.0>-<412.0,-36.5>> = 0.340366963517503

	* uni0122 (U+0122): L<<882.0,0.0>--<882.0,194.0>>/B<<882.0,194.0>-<879.0,144.0>-<848.0,98.0>> = 3.4336303624505082

	* uni0162 (U+0162): L<<563.0,11.0>--<518.0,-63.0>>/B<<518.0,-63.0>-<527.0,-48.0>-<551.0,-36.5>> = 0.340366963517503

	* uni0163 (U+0163): L<<437.0,11.0>--<392.0,-63.0>>/B<<392.0,-63.0>-<401.0,-48.0>-<425.0,-36.5>> = 0.340366963517503

	* uni0327 (U+0327): L<<497.0,11.0>--<452.0,-63.0>>/B<<452.0,-63.0>-<461.0,-48.0>-<485.0,-36.5>> = 0.340366963517503

	* uni1E08 (U+1E08): L<<647.0,11.0>--<602.0,-63.0>>/B<<602.0,-63.0>-<611.0,-48.0>-<635.0,-36.5>> = 0.340366963517503

	* uni1E09 (U+1E09): L<<487.0,11.0>--<442.0,-63.0>>/B<<442.0,-63.0>-<451.0,-48.0>-<475.0,-36.5>> = 0.340366963517503

	* uni1E1C (U+1E1C): L<<551.0,11.0>--<506.0,-63.0>>/B<<506.0,-63.0>-<515.0,-48.0>-<539.0,-36.5>> = 0.340366963517503

	* uni1E1D (U+1E1D): L<<467.0,11.0>--<422.0,-63.0>>/B<<422.0,-63.0>-<431.0,-48.0>-<455.0,-36.5>> = 0.340366963517503

	* uni1E20 (U+1E20): L<<882.0,0.0>--<882.0,194.0>>/B<<882.0,194.0>-<879.0,144.0>-<848.0,98.0>> = 3.4336303624505082

	* uni2079 (U+2079): B<<251.5,827.5>-<254.0,831.0>-<258.0,831.0>>/B<<258.0,831.0>-<202.0,837.0>-<154.0,864.0>> = 6.115503566285384

	* uni2089 (U+2089): B<<251.5,234.5>-<254.0,238.0>-<258.0,238.0>>/B<<258.0,238.0>-<202.0,244.0>-<154.0,271.0>> = 6.115503566285384 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* IJ (U+0132): L<<1295.0,1050.0>--<1297.0,408.0>>

	* J (U+004A): L<<822.0,1050.0>--<824.0,408.0>>

	* Jcircumflex (U+0134): L<<822.0,1050.0>--<824.0,408.0>>

	* Lslash (U+0141): L<<45.0,402.0>--<44.0,621.0>>

	* M (U+004D): L<<1041.0,1052.0>--<1380.0,1050.0>>

	* M (U+004D): L<<74.0,1050.0>--<413.0,1052.0>>

	* U (U+0055): L<<39.0,348.0>--<41.0,1050.0>>

	* U (U+0055): L<<893.0,1050.0>--<894.0,348.0>>

	* Uacute (U+00DA): L<<39.0,348.0>--<41.0,1050.0>>

	* Uacute (U+00DA): L<<893.0,1050.0>--<894.0,348.0>>

	* Ubreve (U+016C): L<<39.0,348.0>--<41.0,1050.0>>

	* Ubreve (U+016C): L<<893.0,1050.0>--<894.0,348.0>>

	* Ucircumflex (U+00DB): L<<39.0,348.0>--<41.0,1050.0>>

	* Ucircumflex (U+00DB): L<<893.0,1050.0>--<894.0,348.0>>

	* Udieresis (U+00DC): L<<39.0,348.0>--<41.0,1050.0>>

	* Udieresis (U+00DC): L<<893.0,1050.0>--<894.0,348.0>>

	* Ugrave (U+00D9): L<<39.0,348.0>--<41.0,1050.0>>

	* Ugrave (U+00D9): L<<893.0,1050.0>--<894.0,348.0>>

	* Uhungarumlaut (U+0170): L<<39.0,348.0>--<41.0,1050.0>>

	* Uhungarumlaut (U+0170): L<<893.0,1050.0>--<894.0,348.0>>

	* Umacron (U+016A): L<<39.0,348.0>--<41.0,1050.0>>

	* Umacron (U+016A): L<<893.0,1050.0>--<894.0,348.0>>

	* Uogonek (U+0172): L<<39.0,348.0>--<41.0,1050.0>>

	* Uogonek (U+0172): L<<893.0,1050.0>--<894.0,348.0>>

	* Uring (U+016E): L<<39.0,348.0>--<41.0,1050.0>>

	* Uring (U+016E): L<<893.0,1050.0>--<894.0,348.0>>

	* Utilde (U+0168): L<<39.0,348.0>--<41.0,1050.0>>

	* Utilde (U+0168): L<<893.0,1050.0>--<894.0,348.0>>

	* a (U+0061): L<<366.0,471.0>--<114.0,470.0>>

	* aacute (U+00E1): L<<366.0,471.0>--<114.0,470.0>>

	* abreve (U+0103): L<<366.0,471.0>--<114.0,470.0>>

	* acircumflex (U+00E2): L<<366.0,471.0>--<114.0,470.0>>

	* adieresis (U+00E4): L<<366.0,471.0>--<114.0,470.0>>

	* ae (U+00E6): L<<366.0,471.0>--<114.0,470.0>>

	* aeacute (U+01FD): L<<366.0,471.0>--<114.0,470.0>>

	* agrave (U+00E0): L<<366.0,471.0>--<114.0,470.0>>

	* amacron (U+0101): L<<366.0,471.0>--<114.0,470.0>>

	* aogonek (U+0105): L<<366.0,471.0>--<114.0,470.0>>

	* aring (U+00E5): L<<366.0,471.0>--<114.0,470.0>>

	* aringacute (U+01FB): L<<366.0,471.0>--<114.0,470.0>>

	* at (U+0040): L<<672.0,465.0>--<395.0,467.0>>

	* atilde (U+00E3): L<<366.0,471.0>--<114.0,470.0>>

	* b (U+0062): L<<48.0,0.0>--<47.0,1050.0>>

	* d (U+0064): L<<930.0,1050.0>--<929.0,0.0>>

	* dcaron (U+010F): L<<930.0,1050.0>--<929.0,0.0>>

	* dcroat (U+0111): L<<930.0,785.0>--<929.0,0.0>>

	* dmacronbelow (U+1E0F): L<<930.0,1050.0>--<929.0,0.0>>

	* eng (U+014B): L<<441.0,-253.0>--<440.0,-90.0>>

	* eng (U+014B): L<<599.0,0.0>--<600.0,438.0>>

	* exclam (U+0021): L<<387.0,1095.0>--<386.0,854.0>>

	* exclamdown (U+00A1): L<<386.0,-44.0>--<387.0,-285.0>>

	* f (U+0066): L<<134.0,0.0>--<135.0,548.0>>

	* fi (U+FB01): L<<134.0,0.0>--<135.0,548.0>>

	* fi (U+FB01): L<<872.0,810.0>--<578.0,809.0>>

	* four (U+0034): L<<44.0,260.0>--<45.0,443.0>>

	* g (U+0067): L<<929.0,750.0>--<930.0,15.0>>

	* gbreve (U+011F): L<<929.0,750.0>--<930.0,15.0>>

	* gcaron (U+01E7): L<<929.0,750.0>--<930.0,15.0>>

	* gcircumflex (U+011D): L<<929.0,750.0>--<930.0,15.0>>

	* gdotaccent (U+0121): L<<929.0,750.0>--<930.0,15.0>>

	* lslash (U+0142): L<<641.0,783.0>--<642.0,567.0>>

	* n (U+006E): L<<599.0,0.0>--<600.0,438.0>>

	* nacute (U+0144): L<<599.0,0.0>--<600.0,438.0>>

	* napostrophe (U+0149): L<<1036.0,0.0>--<1037.0,438.0>>

	* ncaron (U+0148): L<<599.0,0.0>--<600.0,438.0>>

	* nmacronbelow (U+1E49): L<<599.0,0.0>--<600.0,438.0>>

	* ntilde (U+00F1): L<<599.0,0.0>--<600.0,438.0>>

	* p (U+0070): L<<47.0,-300.0>--<48.0,750.0>>

	* q (U+0071): L<<929.0,750.0>--<930.0,-300.0>>

	* thorn (U+00FE): L<<33.0,-268.0>--<35.0,1124.0>>

	* two (U+0032): L<<26.0,0.0>--<27.0,174.0>>

	* uni0123 (U+0123): L<<929.0,750.0>--<930.0,15.0>>

	* uni0146 (U+0146): L<<599.0,0.0>--<600.0,438.0>>

	* uni019D (U+019D): L<<-84.0,-253.0>--<-85.0,-90.0>>

	* uni0272 (U+0272): L<<599.0,0.0>--<600.0,438.0>>

	* uni1E0D (U+1E0D): L<<930.0,1050.0>--<929.0,0.0>>

	* uni1E21 (U+1E21): L<<929.0,750.0>--<930.0,15.0>>

	* uni1E42 (U+1E42): L<<1041.0,1052.0>--<1380.0,1050.0>>

	* uni1E42 (U+1E42): L<<74.0,1050.0>--<413.0,1052.0>>

	* uni1E45 (U+1E45): L<<599.0,0.0>--<600.0,438.0>>

	* uni1E47 (U+1E47): L<<599.0,0.0>--<600.0,438.0>>

	* uni1E78 (U+1E78): L<<39.0,348.0>--<41.0,1050.0>>

	* uni1E78 (U+1E78): L<<893.0,1050.0>--<894.0,348.0>>

	* uni1E7A (U+1E7A): L<<39.0,348.0>--<41.0,1050.0>>

	* uni1E7A (U+1E7A): L<<893.0,1050.0>--<894.0,348.0>>

	* uni1EA1 (U+1EA1): L<<366.0,471.0>--<114.0,470.0>>

	* uni1EE4 (U+1EE4): L<<39.0,348.0>--<41.0,1050.0>>

	* uni1EE4 (U+1EE4): L<<893.0,1050.0>--<894.0,348.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[15] Panamera-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1500. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1680 when it should be at least 1800 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1916, but got 1280 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 651, but got 400 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- uni01CE.ss01

	- uni030C.alt

	- whiteCtircle
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 900 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 1001:
logicalnot

Width = 1230:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* colon (U+003A): X=68.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=337.0,Y=-1.0 (should be at baseline 0?)

	* M (U+004D): X=365.0,Y=1052.0 (should be at cap-height 1050?)

	* M (U+004D): X=1037.0,Y=1052.0 (should be at cap-height 1050?)

	* f (U+0066): X=11.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=140.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=411.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=603.0,Y=752.0 (should be at x-height 750?)

	* sterling (U+00A3): X=375.0,Y=1051.0 (should be at cap-height 1050?)

	* plusminus (U+00B1): X=54.0,Y=-1.0 (should be at baseline 0?)

	* plusminus (U+00B1): X=845.0,Y=-1.0 (should be at baseline 0?)

	* uni00B2 (U+00B2): X=179.0,Y=1048.0 (should be at cap-height 1050?)

	* Atilde (U+00C3): X=538.0,Y=1278.5 (should be at ascender 1280?)

	* Ntilde (U+00D1): X=437.0,Y=1278.5 (should be at ascender 1280?)

	* Otilde (U+00D5): X=548.0,Y=1278.5 (should be at ascender 1280?)

	* divide (U+00F7): X=311.0,Y=-1.0 (should be at baseline 0?)

	* divide (U+00F7): X=580.0,Y=-1.0 (should be at baseline 0?)

	* Itilde (U+0128): X=148.0,Y=1278.5 (should be at ascender 1280?)

	* Lcaron (U+013D): X=645.0,Y=1052.0 (should be at cap-height 1050?)

	* Utilde (U+0168): X=394.0,Y=1278.5 (should be at ascender 1280?)

	* uni1E42 (U+1E42): X=365.0,Y=1052.0 (should be at cap-height 1050?)

	* uni1E42 (U+1E42): X=1037.0,Y=1052.0 (should be at cap-height 1050?)

	* uni1E4C (U+1E4C): X=548.0,Y=1278.5 (should be at ascender 1280?)

	* uni1E4E (U+1E4E): X=548.0,Y=1278.5 (should be at ascender 1280?)

	* uni1E78 (U+1E78): X=394.0,Y=1278.5 (should be at ascender 1280?)

	* uni1EBC (U+1EBC): X=457.0,Y=1278.5 (should be at ascender 1280?)

	* uni1EF8 (U+1EF8): X=455.0,Y=1278.5 (should be at ascender 1280?)

	* trademark (U+2122): X=773.0,Y=1049.0 (should be at cap-height 1050?)

	* trademark (U+2122): X=1053.0,Y=1049.0 (should be at cap-height 1050?)

	* product (U+220F): X=2.0,Y=1049.0 (should be at cap-height 1050?)

	* product (U+220F): X=1031.0,Y=1049.0 (should be at cap-height 1050?)

	* summation (U+2211): X=90.0,Y=1049.0 (should be at cap-height 1050?)

	* summation (U+2211): X=1017.0,Y=1049.0 (should be at cap-height 1050?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<274.0,126.0>--<282.0,39.0>> -> L<<282.0,39.0>--<282.0,0.0>>

	* b (U+0062): L<<282.0,1050.0>--<282.0,735.0>> -> L<<282.0,735.0>--<272.0,612.0>>

	* d (U+0064): L<<675.0,0.0>--<675.0,39.0>> -> L<<675.0,39.0>--<683.0,124.0>>

	* d (U+0064): L<<685.0,615.0>--<675.0,735.0>> -> L<<675.0,735.0>--<675.0,1050.0>>

	* dcaron (U+010F): L<<675.0,0.0>--<675.0,39.0>> -> L<<675.0,39.0>--<683.0,124.0>>

	* dcaron (U+010F): L<<685.0,615.0>--<675.0,735.0>> -> L<<675.0,735.0>--<675.0,1050.0>>

	* dcroat (U+0111): L<<675.0,0.0>--<675.0,39.0>> -> L<<675.0,39.0>--<683.0,124.0>>

	* dcroat (U+0111): L<<685.0,615.0>--<675.0,735.0>> -> L<<675.0,735.0>--<675.0,807.0>>

	* dmacronbelow (U+1E0F): L<<675.0,0.0>--<675.0,39.0>> -> L<<675.0,39.0>--<683.0,124.0>>

	* dmacronbelow (U+1E0F): L<<685.0,615.0>--<675.0,735.0>> -> L<<675.0,735.0>--<675.0,1050.0>>

	* exclam (U+0021): L<<131.0,327.0>--<99.0,866.0>> -> L<<99.0,866.0>--<99.0,1095.0>>

	* exclam (U+0021): L<<366.0,1095.0>--<365.0,866.0>> -> L<<365.0,866.0>--<335.0,327.0>>

	* exclamdown (U+00A1): L<<335.0,483.0>--<365.0,-56.0>> -> L<<365.0,-56.0>--<366.0,-285.0>>

	* exclamdown (U+00A1): L<<99.0,-285.0>--<99.0,-56.0>> -> L<<99.0,-56.0>--<131.0,483.0>>

	* g (U+0067): L<<683.0,626.0>--<675.0,711.0>> -> L<<675.0,711.0>--<675.0,750.0>>

	* gbreve (U+011F): L<<683.0,626.0>--<675.0,711.0>> -> L<<675.0,711.0>--<675.0,750.0>>

	* gcaron (U+01E7): L<<683.0,626.0>--<675.0,711.0>> -> L<<675.0,711.0>--<675.0,750.0>>

	* gcircumflex (U+011D): L<<683.0,626.0>--<675.0,711.0>> -> L<<675.0,711.0>--<675.0,750.0>>

	* gdotaccent (U+0121): L<<683.0,626.0>--<675.0,711.0>> -> L<<675.0,711.0>--<675.0,750.0>>

	* p (U+0070): L<<272.0,139.0>--<282.0,15.0>> -> L<<282.0,15.0>--<282.0,-300.0>>

	* p (U+0070): L<<282.0,750.0>--<282.0,711.0>> -> L<<282.0,711.0>--<274.0,624.0>>

	* q (U+0071): L<<675.0,-300.0>--<675.0,15.0>> -> L<<675.0,15.0>--<685.0,135.0>>

	* q (U+0071): L<<683.0,626.0>--<675.0,711.0>> -> L<<675.0,711.0>--<675.0,750.0>>

	* uni0123 (U+0123): L<<683.0,626.0>--<675.0,711.0>> -> L<<675.0,711.0>--<675.0,750.0>>

	* uni1E0D (U+1E0D): L<<675.0,0.0>--<675.0,39.0>> -> L<<675.0,39.0>--<683.0,124.0>>

	* uni1E0D (U+1E0D): L<<685.0,615.0>--<675.0,735.0>> -> L<<675.0,735.0>--<675.0,1050.0>>

	* uni1E21 (U+1E21): L<<683.0,626.0>--<675.0,711.0>> -> L<<675.0,711.0>--<675.0,750.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ccedilla (U+00C7): L<<634.0,11.0>--<586.0,-73.0>>/B<<586.0,-73.0>-<597.0,-59.0>-<619.0,-49.5>> = 8.412345290426844

	* Scedilla (U+015E): L<<495.0,11.0>--<447.0,-73.0>>/B<<447.0,-73.0>-<458.0,-59.0>-<480.0,-49.5>> = 8.412345290426844

	* ccedilla (U+00E7): L<<481.0,11.0>--<433.0,-73.0>>/B<<433.0,-73.0>-<444.0,-59.0>-<466.0,-49.5>> = 8.412345290426844

	* cedilla (U+00B8): L<<489.0,11.0>--<441.0,-73.0>>/B<<441.0,-73.0>-<452.0,-59.0>-<474.0,-49.5>> = 8.412345290426844

	* scedilla (U+015F): L<<414.0,11.0>--<366.0,-73.0>>/B<<366.0,-73.0>-<377.0,-59.0>-<399.0,-49.5>> = 8.412345290426844

	* uni0162 (U+0162): L<<552.0,11.0>--<504.0,-73.0>>/B<<504.0,-73.0>-<515.0,-59.0>-<537.0,-49.5>> = 8.412345290426844

	* uni0163 (U+0163): L<<430.0,11.0>--<382.0,-73.0>>/B<<382.0,-73.0>-<393.0,-59.0>-<415.0,-49.5>> = 8.412345290426844

	* uni0327 (U+0327): L<<489.0,11.0>--<441.0,-73.0>>/B<<441.0,-73.0>-<452.0,-59.0>-<474.0,-49.5>> = 8.412345290426844

	* uni1E08 (U+1E08): L<<634.0,11.0>--<586.0,-73.0>>/B<<586.0,-73.0>-<597.0,-59.0>-<619.0,-49.5>> = 8.412345290426844

	* uni1E09 (U+1E09): L<<481.0,11.0>--<433.0,-73.0>>/B<<433.0,-73.0>-<444.0,-59.0>-<466.0,-49.5>> = 8.412345290426844

	* uni1E1C (U+1E1C): L<<543.0,11.0>--<495.0,-73.0>>/B<<495.0,-73.0>-<506.0,-59.0>-<528.0,-49.5>> = 8.412345290426844

	* uni1E1D (U+1E1D): L<<466.0,11.0>--<418.0,-73.0>>/B<<418.0,-73.0>-<429.0,-59.0>-<451.0,-49.5>> = 8.412345290426844 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* D (U+0044): L<<306.0,878.0>--<305.0,173.0>>

	* Dcaron (U+010E): L<<306.0,878.0>--<305.0,173.0>>

	* Dcroat (U+0110): L<<510.0,375.0>--<509.0,173.0>>

	* Dmacronbelow (U+1E0E): L<<306.0,878.0>--<305.0,173.0>>

	* Eth (U+00D0): L<<510.0,375.0>--<509.0,173.0>>

	* IJ (U+0132): L<<1245.0,1050.0>--<1247.0,386.0>>

	* J (U+004A): L<<804.0,1050.0>--<806.0,386.0>>

	* Jcircumflex (U+0134): L<<804.0,1050.0>--<806.0,386.0>>

	* M (U+004D): L<<1037.0,1052.0>--<1326.0,1050.0>>

	* M (U+004D): L<<75.0,1050.0>--<365.0,1052.0>>

	* U (U+0055): L<<50.0,342.0>--<51.0,1050.0>>

	* U (U+0055): L<<882.0,1050.0>--<884.0,342.0>>

	* Uacute (U+00DA): L<<50.0,342.0>--<51.0,1050.0>>

	* Uacute (U+00DA): L<<882.0,1050.0>--<884.0,342.0>>

	* Ubreve (U+016C): L<<50.0,342.0>--<51.0,1050.0>>

	* Ubreve (U+016C): L<<882.0,1050.0>--<884.0,342.0>>

	* Ucircumflex (U+00DB): L<<50.0,342.0>--<51.0,1050.0>>

	* Ucircumflex (U+00DB): L<<882.0,1050.0>--<884.0,342.0>>

	* Udieresis (U+00DC): L<<50.0,342.0>--<51.0,1050.0>>

	* Udieresis (U+00DC): L<<882.0,1050.0>--<884.0,342.0>>

	* Ugrave (U+00D9): L<<50.0,342.0>--<51.0,1050.0>>

	* Ugrave (U+00D9): L<<882.0,1050.0>--<884.0,342.0>>

	* Uhungarumlaut (U+0170): L<<50.0,342.0>--<51.0,1050.0>>

	* Uhungarumlaut (U+0170): L<<882.0,1050.0>--<884.0,342.0>>

	* Umacron (U+016A): L<<50.0,342.0>--<51.0,1050.0>>

	* Umacron (U+016A): L<<882.0,1050.0>--<884.0,342.0>>

	* Uogonek (U+0172): L<<50.0,342.0>--<51.0,1050.0>>

	* Uogonek (U+0172): L<<882.0,1050.0>--<884.0,342.0>>

	* Uring (U+016E): L<<50.0,342.0>--<51.0,1050.0>>

	* Uring (U+016E): L<<882.0,1050.0>--<884.0,342.0>>

	* Utilde (U+0168): L<<50.0,342.0>--<51.0,1050.0>>

	* Utilde (U+0168): L<<882.0,1050.0>--<884.0,342.0>>

	* at (U+0040): L<<647.0,488.0>--<407.0,489.0>>

	* b (U+0062): L<<54.0,0.0>--<53.0,1050.0>>

	* d (U+0064): L<<905.0,1050.0>--<903.0,0.0>>

	* dcaron (U+010F): L<<905.0,1050.0>--<903.0,0.0>>

	* dcroat (U+0111): L<<905.0,807.0>--<903.0,0.0>>

	* dmacronbelow (U+1E0F): L<<905.0,1050.0>--<903.0,0.0>>

	* eng (U+014B): L<<622.0,0.0>--<623.0,441.0>>

	* exclam (U+0021): L<<366.0,1095.0>--<365.0,866.0>>

	* exclamdown (U+00A1): L<<365.0,-56.0>--<366.0,-285.0>>

	* f (U+0066): L<<141.0,0.0>--<143.0,578.0>>

	* fi (U+FB01): L<<141.0,0.0>--<143.0,578.0>>

	* four (U+0034): L<<500.0,280.0>--<45.0,281.0>>

	* g (U+0067): L<<903.0,750.0>--<905.0,12.0>>

	* gbreve (U+011F): L<<903.0,750.0>--<905.0,12.0>>

	* gcaron (U+01E7): L<<903.0,750.0>--<905.0,12.0>>

	* gcircumflex (U+011D): L<<903.0,750.0>--<905.0,12.0>>

	* gdotaccent (U+0121): L<<903.0,750.0>--<905.0,12.0>>

	* lslash (U+0142): L<<629.0,768.0>--<630.0,584.0>>

	* n (U+006E): L<<622.0,0.0>--<623.0,441.0>>

	* nacute (U+0144): L<<622.0,0.0>--<623.0,441.0>>

	* napostrophe (U+0149): L<<1005.0,0.0>--<1006.0,441.0>>

	* ncaron (U+0148): L<<622.0,0.0>--<623.0,441.0>>

	* nmacronbelow (U+1E49): L<<622.0,0.0>--<623.0,441.0>>

	* ntilde (U+00F1): L<<622.0,0.0>--<623.0,441.0>>

	* p (U+0070): L<<53.0,-300.0>--<54.0,750.0>>

	* q (U+0071): L<<903.0,750.0>--<905.0,-300.0>>

	* thorn (U+00FE): L<<38.0,-286.0>--<39.0,1142.0>>

	* uni0123 (U+0123): L<<903.0,750.0>--<905.0,12.0>>

	* uni0146 (U+0146): L<<622.0,0.0>--<623.0,441.0>>

	* uni0272 (U+0272): L<<622.0,0.0>--<623.0,441.0>>

	* uni1E0C (U+1E0C): L<<306.0,878.0>--<305.0,173.0>>

	* uni1E0D (U+1E0D): L<<905.0,1050.0>--<903.0,0.0>>

	* uni1E21 (U+1E21): L<<903.0,750.0>--<905.0,12.0>>

	* uni1E42 (U+1E42): L<<1037.0,1052.0>--<1326.0,1050.0>>

	* uni1E42 (U+1E42): L<<75.0,1050.0>--<365.0,1052.0>>

	* uni1E45 (U+1E45): L<<622.0,0.0>--<623.0,441.0>>

	* uni1E47 (U+1E47): L<<622.0,0.0>--<623.0,441.0>>

	* uni1E78 (U+1E78): L<<50.0,342.0>--<51.0,1050.0>>

	* uni1E78 (U+1E78): L<<882.0,1050.0>--<884.0,342.0>>

	* uni1E7A (U+1E7A): L<<50.0,342.0>--<51.0,1050.0>>

	* uni1E7A (U+1E7A): L<<882.0,1050.0>--<884.0,342.0>>

	* uni1EE4 (U+1EE4): L<<50.0,342.0>--<51.0,1050.0>>

	* uni1EE4 (U+1EE4): L<<882.0,1050.0>--<884.0,342.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[14] Panamera-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1500. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1680 when it should be at least 1800 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1916, but got 1280 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 651, but got 400 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- uni01CE.ss01

	- uni030C.alt

	- whiteCtircle
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 900 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 1001:
logicalnot

Width = 1230:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* exclam (U+0021): L<<193.0,323.0>--<164.0,901.0>> -> L<<164.0,901.0>--<164.0,1097.0>>

	* exclam (U+0021): L<<302.0,1097.0>--<301.0,901.0>> -> L<<301.0,901.0>--<273.0,323.0>>

	* exclamdown (U+00A1): L<<164.0,-286.0>--<164.0,-90.0>> -> L<<164.0,-90.0>--<193.0,488.0>>

	* exclamdown (U+00A1): L<<273.0,488.0>--<301.0,-90.0>> -> L<<301.0,-90.0>--<302.0,-286.0>>

	* thorn (U+00FE): L<<150.0,206.0>--<158.0,107.0>> -> L<<158.0,107.0>--<158.0,-339.0>>

	* thorn (U+00FE): L<<158.0,1195.0>--<158.0,618.0>> -> L<<158.0,618.0>--<150.0,526.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<970.0,0.0>--<970.0,340.0>>/B<<970.0,340.0>-<959.0,239.0>-<912.0,160.5>> = 6.215635899702654

	* Gbreve (U+011E): L<<970.0,0.0>--<970.0,340.0>>/B<<970.0,340.0>-<959.0,239.0>-<912.0,160.5>> = 6.215635899702654

	* Gcaron (U+01E6): L<<970.0,0.0>--<970.0,340.0>>/B<<970.0,340.0>-<959.0,239.0>-<912.0,160.5>> = 6.215635899702654

	* Gcircumflex (U+011C): L<<970.0,0.0>--<970.0,340.0>>/B<<970.0,340.0>-<959.0,239.0>-<912.0,160.5>> = 6.215635899702654

	* Gdotaccent (U+0120): L<<970.0,0.0>--<970.0,340.0>>/B<<970.0,340.0>-<959.0,239.0>-<912.0,160.5>> = 6.215635899702654

	* b (U+0062): B<<271.0,51.5>-<198.0,120.0>-<170.0,218.0>>/L<<170.0,218.0>--<178.0,143.0>> = 9.856867746727668

	* b (U+0062): L<<178.0,632.0>--<167.0,523.0>>/B<<167.0,523.0>-<186.0,592.0>-<225.0,648.0>> = 9.632916367396664

	* d (U+0064): B<<625.0,698.5>-<700.0,627.0>-<729.0,524.0>>/L<<729.0,524.0>--<718.0,632.0>> = 9.909119193256174

	* d (U+0064): L<<718.0,143.0>--<726.0,217.0>>/B<<726.0,217.0>-<697.0,119.0>-<624.0,51.0>> = 10.314278094506019

	* dcaron (U+010F): B<<625.0,698.5>-<700.0,627.0>-<729.0,524.0>>/L<<729.0,524.0>--<718.0,632.0>> = 9.909119193256174

	* dcaron (U+010F): L<<718.0,143.0>--<726.0,217.0>>/B<<726.0,217.0>-<697.0,119.0>-<624.0,51.0>> = 10.314278094506019

	* dcroat (U+0111): B<<625.0,698.5>-<700.0,627.0>-<729.0,524.0>>/L<<729.0,524.0>--<718.0,632.0>> = 9.909119193256174

	* dcroat (U+0111): L<<718.0,143.0>--<726.0,217.0>>/B<<726.0,217.0>-<697.0,119.0>-<624.0,51.0>> = 10.314278094506019

	* dmacronbelow (U+1E0F): B<<625.0,698.5>-<700.0,627.0>-<729.0,524.0>>/L<<729.0,524.0>--<718.0,632.0>> = 9.909119193256174

	* dmacronbelow (U+1E0F): L<<718.0,143.0>--<726.0,217.0>>/B<<726.0,217.0>-<697.0,119.0>-<624.0,51.0>> = 10.314278094506019

	* f (U+0066): L<<13.0,752.0>--<233.0,752.0>>/B<<233.0,752.0>-<160.0,765.0>-<121.5,813.5>> = 10.09750438407527

	* g (U+0067): B<<624.0,699.5>-<697.0,632.0>-<726.0,533.0>>/L<<726.0,533.0>--<718.0,608.0>> = 10.238325356369803

	* g (U+0067): L<<718.0,147.0>--<726.0,216.0>>/B<<726.0,216.0>-<696.0,117.0>-<621.5,49.0>> = 10.244938285423522

	* gbreve (U+011F): B<<624.0,699.5>-<697.0,632.0>-<726.0,533.0>>/L<<726.0,533.0>--<718.0,608.0>> = 10.238325356369803

	* gbreve (U+011F): L<<718.0,147.0>--<726.0,216.0>>/B<<726.0,216.0>-<696.0,117.0>-<621.5,49.0>> = 10.244938285423522

	* gcaron (U+01E7): B<<624.0,699.5>-<697.0,632.0>-<726.0,533.0>>/L<<726.0,533.0>--<718.0,608.0>> = 10.238325356369803

	* gcaron (U+01E7): L<<718.0,147.0>--<726.0,216.0>>/B<<726.0,216.0>-<696.0,117.0>-<621.5,49.0>> = 10.244938285423522

	* gcircumflex (U+011D): B<<624.0,699.5>-<697.0,632.0>-<726.0,533.0>>/L<<726.0,533.0>--<718.0,608.0>> = 10.238325356369803

	* gcircumflex (U+011D): L<<718.0,147.0>--<726.0,216.0>>/B<<726.0,216.0>-<696.0,117.0>-<621.5,49.0>> = 10.244938285423522

	* gdotaccent (U+0121): B<<624.0,699.5>-<697.0,632.0>-<726.0,533.0>>/L<<726.0,533.0>--<718.0,608.0>> = 10.238325356369803

	* gdotaccent (U+0121): L<<718.0,147.0>--<726.0,216.0>>/B<<726.0,216.0>-<696.0,117.0>-<621.5,49.0>> = 10.244938285423522

	* p (U+0070): B<<225.0,103.0>-<186.0,159.0>-<167.0,227.0>>/L<<167.0,227.0>--<178.0,119.0>> = 9.79536200418838

	* p (U+0070): L<<178.0,608.0>--<170.0,532.0>>/B<<170.0,532.0>-<198.0,631.0>-<271.0,699.0>> = 9.783397571362698

	* q (U+0071): B<<624.0,699.5>-<697.0,632.0>-<726.0,533.0>>/L<<726.0,533.0>--<718.0,608.0>> = 10.238325356369803

	* q (U+0071): L<<718.0,119.0>--<729.0,226.0>>/B<<729.0,226.0>-<700.0,123.0>-<625.0,52.0>> = 9.855145279732705

	* r (U+0072): L<<180.0,750.0>--<180.0,535.0>>/B<<180.0,535.0>-<197.0,607.0>-<240.5,657.5>> = 13.284866484902187

	* racute (U+0155): L<<180.0,750.0>--<180.0,535.0>>/B<<180.0,535.0>-<197.0,607.0>-<240.5,657.5>> = 13.284866484902187

	* rcaron (U+0159): L<<180.0,750.0>--<180.0,535.0>>/B<<180.0,535.0>-<197.0,607.0>-<240.5,657.5>> = 13.284866484902187

	* rmacronbelow (U+1E5F): L<<180.0,750.0>--<180.0,535.0>>/B<<180.0,535.0>-<197.0,607.0>-<240.5,657.5>> = 13.284866484902187

	* thorn (U+00FE): B<<205.5,94.0>-<168.0,147.0>-<150.0,206.0>>/L<<150.0,206.0>--<158.0,107.0>> = 12.346224626875745

	* thorn (U+00FE): L<<158.0,618.0>--<150.0,526.0>>/B<<150.0,526.0>-<168.0,586.0>-<205.5,639.5>> = 11.729503505883319

	* uni0122 (U+0122): L<<970.0,0.0>--<970.0,340.0>>/B<<970.0,340.0>-<959.0,239.0>-<912.0,160.5>> = 6.215635899702654

	* uni0123 (U+0123): B<<624.0,699.5>-<697.0,632.0>-<726.0,533.0>>/L<<726.0,533.0>--<718.0,608.0>> = 10.238325356369803

	* uni0123 (U+0123): L<<718.0,147.0>--<726.0,216.0>>/B<<726.0,216.0>-<696.0,117.0>-<621.5,49.0>> = 10.244938285423522

	* uni0157 (U+0157): L<<180.0,750.0>--<180.0,535.0>>/B<<180.0,535.0>-<197.0,607.0>-<240.5,657.5>> = 13.284866484902187

	* uni1E0D (U+1E0D): B<<625.0,698.5>-<700.0,627.0>-<729.0,524.0>>/L<<729.0,524.0>--<718.0,632.0>> = 9.909119193256174

	* uni1E0D (U+1E0D): L<<718.0,143.0>--<726.0,217.0>>/B<<726.0,217.0>-<697.0,119.0>-<624.0,51.0>> = 10.314278094506019

	* uni1E20 (U+1E20): L<<970.0,0.0>--<970.0,340.0>>/B<<970.0,340.0>-<959.0,239.0>-<912.0,160.5>> = 6.215635899702654

	* uni1E21 (U+1E21): B<<624.0,699.5>-<697.0,632.0>-<726.0,533.0>>/L<<726.0,533.0>--<718.0,608.0>> = 10.238325356369803

	* uni1E21 (U+1E21): L<<718.0,147.0>--<726.0,216.0>>/B<<726.0,216.0>-<696.0,117.0>-<621.5,49.0>> = 10.244938285423522

	* uni1E5B (U+1E5B): L<<180.0,750.0>--<180.0,535.0>>/B<<180.0,535.0>-<197.0,607.0>-<240.5,657.5>> = 13.284866484902187 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* D (U+0044): L<<342.0,961.0>--<187.0,960.0>>

	* Dcaron (U+010E): L<<342.0,961.0>--<187.0,960.0>>

	* Dcroat (U+0110): L<<362.0,422.0>--<361.0,90.0>>

	* Dcroat (U+0110): L<<517.0,961.0>--<362.0,960.0>>

	* Dmacronbelow (U+1E0E): L<<342.0,961.0>--<187.0,960.0>>

	* Eth (U+00D0): L<<362.0,422.0>--<361.0,90.0>>

	* Eth (U+00D0): L<<517.0,961.0>--<362.0,960.0>>

	* IJ (U+0132): L<<1093.0,1050.0>--<1095.0,316.0>>

	* J (U+004A): L<<749.0,1050.0>--<751.0,316.0>>

	* Jcircumflex (U+0134): L<<749.0,1050.0>--<751.0,316.0>>

	* M (U+004D): L<<1024.0,1051.0>--<1161.0,1050.0>>

	* M (U+004D): L<<82.0,1050.0>--<217.0,1051.0>>

	* U (U+0055): L<<80.0,324.0>--<82.0,1050.0>>

	* U (U+0055): L<<852.0,1050.0>--<853.0,324.0>>

	* Uacute (U+00DA): L<<80.0,324.0>--<82.0,1050.0>>

	* Uacute (U+00DA): L<<852.0,1050.0>--<853.0,324.0>>

	* Ubreve (U+016C): L<<80.0,324.0>--<82.0,1050.0>>

	* Ubreve (U+016C): L<<852.0,1050.0>--<853.0,324.0>>

	* Ucircumflex (U+00DB): L<<80.0,324.0>--<82.0,1050.0>>

	* Ucircumflex (U+00DB): L<<852.0,1050.0>--<853.0,324.0>>

	* Udieresis (U+00DC): L<<80.0,324.0>--<82.0,1050.0>>

	* Udieresis (U+00DC): L<<852.0,1050.0>--<853.0,324.0>>

	* Ugrave (U+00D9): L<<80.0,324.0>--<82.0,1050.0>>

	* Ugrave (U+00D9): L<<852.0,1050.0>--<853.0,324.0>>

	* Uhungarumlaut (U+0170): L<<80.0,324.0>--<82.0,1050.0>>

	* Uhungarumlaut (U+0170): L<<852.0,1050.0>--<853.0,324.0>>

	* Umacron (U+016A): L<<80.0,324.0>--<82.0,1050.0>>

	* Umacron (U+016A): L<<852.0,1050.0>--<853.0,324.0>>

	* Uogonek (U+0172): L<<80.0,324.0>--<82.0,1050.0>>

	* Uogonek (U+0172): L<<852.0,1050.0>--<853.0,324.0>>

	* Uring (U+016E): L<<80.0,324.0>--<82.0,1050.0>>

	* Uring (U+016E): L<<852.0,1050.0>--<853.0,324.0>>

	* Utilde (U+0168): L<<80.0,324.0>--<82.0,1050.0>>

	* Utilde (U+0168): L<<852.0,1050.0>--<853.0,324.0>>

	* a (U+0061): L<<231.0,565.0>--<104.0,566.0>>

	* aacute (U+00E1): L<<231.0,565.0>--<104.0,566.0>>

	* abreve (U+0103): L<<231.0,565.0>--<104.0,566.0>>

	* acircumflex (U+00E2): L<<231.0,565.0>--<104.0,566.0>>

	* adieresis (U+00E4): L<<231.0,565.0>--<104.0,566.0>>

	* ae (U+00E6): L<<231.0,565.0>--<104.0,566.0>>

	* aeacute (U+01FD): L<<231.0,565.0>--<104.0,566.0>>

	* agrave (U+00E0): L<<231.0,565.0>--<104.0,566.0>>

	* amacron (U+0101): L<<231.0,565.0>--<104.0,566.0>>

	* aogonek (U+0105): L<<231.0,565.0>--<104.0,566.0>>

	* aring (U+00E5): L<<231.0,565.0>--<104.0,566.0>>

	* aringacute (U+01FB): L<<231.0,565.0>--<104.0,566.0>>

	* at (U+0040): L<<571.0,558.0>--<443.0,559.0>>

	* atilde (U+00E3): L<<231.0,565.0>--<104.0,566.0>>

	* b (U+0062): L<<71.0,0.0>--<70.0,1050.0>>

	* cent (U+00A2): L<<473.0,1049.0>--<474.0,914.0>>

	* d (U+0064): L<<826.0,1050.0>--<824.0,0.0>>

	* dcaron (U+010F): L<<826.0,1050.0>--<824.0,0.0>>

	* dcroat (U+0111): L<<826.0,875.0>--<824.0,0.0>>

	* dmacronbelow (U+1E0F): L<<826.0,1050.0>--<824.0,0.0>>

	* exclam (U+0021): L<<302.0,1097.0>--<301.0,901.0>>

	* exclamdown (U+00A1): L<<301.0,-90.0>--<302.0,-286.0>>

	* f (U+0066): L<<164.0,2.0>--<166.0,669.0>>

	* fi (U+FB01): L<<13.0,752.0>--<198.0,751.0>>

	* fi (U+FB01): L<<164.0,2.0>--<166.0,669.0>>

	* fi (U+FB01): L<<304.0,752.0>--<757.0,751.0>>

	* fi (U+FB01): L<<757.0,940.0>--<627.0,941.0>>

	* four (U+0034): L<<553.0,342.0>--<50.0,344.0>>

	* g (U+0067): L<<824.0,750.0>--<826.0,2.0>>

	* gbreve (U+011F): L<<824.0,750.0>--<826.0,2.0>>

	* gcaron (U+01E7): L<<824.0,750.0>--<826.0,2.0>>

	* gcircumflex (U+011D): L<<824.0,750.0>--<826.0,2.0>>

	* gdotaccent (U+0121): L<<824.0,750.0>--<826.0,2.0>>

	* onequarter (U+00BC): L<<916.0,207.0>--<611.0,208.0>>

	* p (U+0070): L<<70.0,-300.0>--<71.0,750.0>>

	* q (U+0071): L<<824.0,750.0>--<826.0,-300.0>>

	* thorn (U+00FE): L<<50.0,-339.0>--<52.0,1195.0>>

	* threequarters (U+00BE): L<<916.0,207.0>--<611.0,208.0>>

	* uni0123 (U+0123): L<<824.0,750.0>--<826.0,2.0>>

	* uni018F (U+018F): L<<64.0,540.0>--<966.0,542.0>>

	* uni1E0C (U+1E0C): L<<342.0,961.0>--<187.0,960.0>>

	* uni1E0D (U+1E0D): L<<826.0,1050.0>--<824.0,0.0>>

	* uni1E21 (U+1E21): L<<824.0,750.0>--<826.0,2.0>>

	* uni1E42 (U+1E42): L<<1024.0,1051.0>--<1161.0,1050.0>>

	* uni1E42 (U+1E42): L<<82.0,1050.0>--<217.0,1051.0>>

	* uni1E78 (U+1E78): L<<80.0,324.0>--<82.0,1050.0>>

	* uni1E78 (U+1E78): L<<852.0,1050.0>--<853.0,324.0>>

	* uni1E7A (U+1E7A): L<<80.0,324.0>--<82.0,1050.0>>

	* uni1E7A (U+1E7A): L<<852.0,1050.0>--<853.0,324.0>>

	* uni1EA1 (U+1EA1): L<<231.0,565.0>--<104.0,566.0>>

	* uni1EE4 (U+1EE4): L<<80.0,324.0>--<82.0,1050.0>>

	* uni1EE4 (U+1EE4): L<<852.0,1050.0>--<853.0,324.0>>

	* uni2074 (U+2074): L<<335.0,800.0>--<30.0,801.0>>

	* uni2084 (U+2084): L<<335.0,207.0>--<30.0,208.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[15] Panamera-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1500. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1680 when it should be at least 1800 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1916, but got 1280 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 651, but got 400 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- uni01CE.ss01

	- uni030C.alt

	- whiteCtircle
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 900 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 1001:
logicalnot

Width = 1230:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=556.0,Y=1051.0 (should be at cap-height 1050?)

	* colon (U+003A): X=151.0,Y=-1.0 (should be at baseline 0?)

	* colon (U+003A): X=254.0,Y=-1.0 (should be at baseline 0?)

	* at (U+0040): X=810.5,Y=-0.5 (should be at baseline 0?)

	* f (U+0066): X=171.0,Y=2.0 (should be at baseline 0?)

	* f (U+0066): X=14.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=264.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=196.0,Y=1050.5 (should be at cap-height 1050?)

	* f (U+0066): X=342.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=519.0,Y=752.0 (should be at x-height 750?)

	* f (U+0066): X=237.0,Y=2.0 (should be at baseline 0?)

	* g (U+0067): X=732.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=800.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=782.0,Y=2.0 (should be at baseline 0?)

	* h (U+0068): X=716.0,Y=2.0 (should be at baseline 0?)

	* m (U+006D): X=1409.0,Y=2.0 (should be at baseline 0?)

	* m (U+006D): X=1343.0,Y=2.0 (should be at baseline 0?)

	* m (U+006D): X=767.0,Y=2.0 (should be at baseline 0?)

	* m (U+006D): X=701.0,Y=2.0 (should be at baseline 0?)

	* m (U+006D): X=141.0,Y=2.0 (should be at baseline 0?)

	* m (U+006D): X=75.0,Y=2.0 (should be at baseline 0?)

	* u (U+0075): X=780.0,Y=2.0 (should be at baseline 0?)

	* u (U+0075): X=714.0,Y=2.0 (should be at baseline 0?)

	* y (U+0079): X=92.0,Y=752.0 (should be at x-height 750?)

	* cent (U+00A2): X=401.0,Y=1049.0 (should be at cap-height 1050?)

	* cent (U+00A2): X=461.0,Y=1049.0 (should be at cap-height 1050?)

	* sterling (U+00A3): X=129.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=807.0,Y=-1.0 (should be at baseline 0?)

	* paragraph (U+00B6): X=423.0,Y=1052.0 (should be at cap-height 1050?)

	* paragraph (U+00B6): X=674.0,Y=1052.0 (should be at cap-height 1050?)

	* paragraph (U+00B6): X=900.0,Y=1052.0 (should be at cap-height 1050?)

	* paragraph (U+00B6): X=960.0,Y=1052.0 (should be at cap-height 1050?)

	* divide (U+00F7): X=396.0,Y=-1.0 (should be at baseline 0?)

	* divide (U+00F7): X=499.0,Y=-1.0 (should be at baseline 0?)

	* ugrave (U+00F9): X=780.0,Y=2.0 (should be at baseline 0?)

	* ugrave (U+00F9): X=714.0,Y=2.0 (should be at baseline 0?)

	* uacute (U+00FA): X=780.0,Y=2.0 (should be at baseline 0?)

	* uacute (U+00FA): X=714.0,Y=2.0 (should be at baseline 0?)

	* ucircumflex (U+00FB): X=780.0,Y=2.0 (should be at baseline 0?)

	* ucircumflex (U+00FB): X=714.0,Y=2.0 (should be at baseline 0?)

	* udieresis (U+00FC): X=780.0,Y=2.0 (should be at baseline 0?)

	* udieresis (U+00FC): X=714.0,Y=2.0 (should be at baseline 0?)

	* Abreve (U+0102): X=494.0,Y=1278.0 (should be at ascender 1280?)

	* Ebreve (U+0114): X=500.0,Y=1278.0 (should be at ascender 1280?)

	* gcircumflex (U+011D): X=732.0,Y=-1.0 (should be at baseline 0?)

	* gcircumflex (U+011D): X=800.0,Y=-1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=576.0,Y=1278.0 (should be at ascender 1280?)

	* gbreve (U+011F): X=732.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=800.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=732.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=800.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=732.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=800.0,Y=-1.0 (should be at baseline 0?)

	* hcircumflex (U+0125): X=782.0,Y=2.0 (should be at baseline 0?)

	* hcircumflex (U+0125): X=716.0,Y=2.0 (should be at baseline 0?)

	* hbar (U+0127): X=782.0,Y=2.0 (should be at baseline 0?)

	* hbar (U+0127): X=716.0,Y=2.0 (should be at baseline 0?)

	* Ibreve (U+012C): X=155.0,Y=1278.0 (should be at ascender 1280?)

	* Obreve (U+014E): X=621.0,Y=1278.0 (should be at ascender 1280?)

	* utilde (U+0169): X=780.0,Y=2.0 (should be at baseline 0?)

	* utilde (U+0169): X=714.0,Y=2.0 (should be at baseline 0?)

	* umacron (U+016B): X=780.0,Y=2.0 (should be at baseline 0?)

	* umacron (U+016B): X=714.0,Y=2.0 (should be at baseline 0?)

	* Ubreve (U+016C): X=467.0,Y=1278.0 (should be at ascender 1280?)

	* ubreve (U+016D): X=780.0,Y=2.0 (should be at baseline 0?)

	* ubreve (U+016D): X=714.0,Y=2.0 (should be at baseline 0?)

	* uring (U+016F): X=780.0,Y=2.0 (should be at baseline 0?)

	* uring (U+016F): X=714.0,Y=2.0 (should be at baseline 0?)

	* uhungarumlaut (U+0171): X=780.0,Y=2.0 (should be at baseline 0?)

	* uhungarumlaut (U+0171): X=714.0,Y=2.0 (should be at baseline 0?)

	* uogonek (U+0173): X=780.0,Y=2.0 (should be at baseline 0?)

	* uogonek (U+0173): X=714.0,Y=2.0 (should be at baseline 0?)

	* gcaron (U+01E7): X=732.0,Y=-1.0 (should be at baseline 0?)

	* gcaron (U+01E7): X=800.0,Y=-1.0 (should be at baseline 0?)

	* uni1E1C (U+1E1C): X=500.0,Y=1278.0 (should be at ascender 1280?)

	* uni1E21 (U+1E21): X=732.0,Y=-1.0 (should be at baseline 0?)

	* uni1E21 (U+1E21): X=800.0,Y=-1.0 (should be at baseline 0?)

	* uni1E25 (U+1E25): X=782.0,Y=2.0 (should be at baseline 0?)

	* uni1E25 (U+1E25): X=716.0,Y=2.0 (should be at baseline 0?)

	* uni1E2B (U+1E2B): X=782.0,Y=2.0 (should be at baseline 0?)

	* uni1E2B (U+1E2B): X=716.0,Y=2.0 (should be at baseline 0?)

	* uni1E43 (U+1E43): X=1409.0,Y=2.0 (should be at baseline 0?)

	* uni1E43 (U+1E43): X=1343.0,Y=2.0 (should be at baseline 0?)

	* uni1E43 (U+1E43): X=767.0,Y=2.0 (should be at baseline 0?)

	* uni1E43 (U+1E43): X=701.0,Y=2.0 (should be at baseline 0?)

	* uni1E43 (U+1E43): X=141.0,Y=2.0 (should be at baseline 0?)

	* uni1E43 (U+1E43): X=75.0,Y=2.0 (should be at baseline 0?)

	* uni1E79 (U+1E79): X=780.0,Y=2.0 (should be at baseline 0?)

	* uni1E79 (U+1E79): X=714.0,Y=2.0 (should be at baseline 0?)

	* uni1E7B (U+1E7B): X=780.0,Y=2.0 (should be at baseline 0?)

	* uni1E7B (U+1E7B): X=714.0,Y=2.0 (should be at baseline 0?)

	* uni1EE5 (U+1EE5): X=780.0,Y=2.0 (should be at baseline 0?)

	* uni1EE5 (U+1EE5): X=714.0,Y=2.0 (should be at baseline 0?)

	* uni2106 (U+2106): X=1463.0,Y=2.0 (should be at baseline 0?)

	* uni2106 (U+2106): X=1408.0,Y=2.0 (should be at baseline 0?)

	* uni2116 (U+2116): X=1278.0,Y=1049.0 (should be at cap-height 1050?)

	* trademark (U+2122): X=773.0,Y=1049.0 (should be at cap-height 1050?)

	* trademark (U+2122): X=1053.0,Y=1049.0 (should be at cap-height 1050?)

	* fi (U+FB01): X=237.0,Y=2.0 (should be at baseline 0?)

	* fi (U+FB01): X=171.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* exclam (U+0021): L<<213.0,321.0>--<185.0,912.0>> -> L<<185.0,912.0>--<185.0,1097.0>>

	* exclam (U+0021): L<<280.0,1097.0>--<280.0,912.0>> -> L<<280.0,912.0>--<252.0,321.0>>

	* exclamdown (U+00A1): L<<185.0,-287.0>--<185.0,-102.0>> -> L<<185.0,-102.0>--<213.0,489.0>>

	* exclamdown (U+00A1): L<<252.0,489.0>--<280.0,-102.0>> -> L<<280.0,-102.0>--<280.0,-287.0>>

	* thorn (U+00FE): L<<111.0,265.0>--<122.0,144.0>> -> L<<122.0,144.0>--<122.0,-357.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): L<<992.0,0.0>--<992.0,372.0>>/B<<992.0,372.0>-<977.0,259.0>-<926.0,173.5>> = 7.5614284276669235

	* Gbreve (U+011E): L<<992.0,0.0>--<992.0,372.0>>/B<<992.0,372.0>-<977.0,259.0>-<926.0,173.5>> = 7.5614284276669235

	* Gcaron (U+01E6): L<<992.0,0.0>--<992.0,372.0>>/B<<992.0,372.0>-<977.0,259.0>-<926.0,173.5>> = 7.5614284276669235

	* Gcircumflex (U+011C): L<<992.0,0.0>--<992.0,372.0>>/B<<992.0,372.0>-<977.0,259.0>-<926.0,173.5>> = 7.5614284276669235

	* Gdotaccent (U+0120): L<<992.0,0.0>--<992.0,372.0>>/B<<992.0,372.0>-<977.0,259.0>-<926.0,173.5>> = 7.5614284276669235

	* at (U+0040): B<<1020.0,48.0>-<966.0,96.0>-<966.0,225.0>>/B<<966.0,225.0>-<952.0,132.0>-<911.0,77.5>> = 8.560889571164587

	* b (U+0062): B<<194.0,118.5>-<153.0,179.0>-<134.0,249.0>>/L<<134.0,249.0>--<143.0,177.0>> = 8.06082091329955

	* b (U+0062): L<<143.0,597.0>--<132.0,494.0>>/B<<132.0,494.0>-<150.0,565.0>-<191.5,628.0>> = 8.13010235415596

	* d (U+0064): B<<683.5,628.0>-<725.0,565.0>-<743.0,494.0>>/L<<743.0,494.0>--<732.0,597.0>> = 8.13010235415596

	* d (U+0064): L<<732.0,177.0>--<741.0,249.0>>/B<<741.0,249.0>-<722.0,179.0>-<681.0,118.5>> = 8.06082091329955

	* dcaron (U+010F): B<<683.5,628.0>-<725.0,565.0>-<743.0,494.0>>/L<<743.0,494.0>--<732.0,597.0>> = 8.13010235415596

	* dcaron (U+010F): L<<732.0,177.0>--<741.0,249.0>>/B<<741.0,249.0>-<722.0,179.0>-<681.0,118.5>> = 8.06082091329955

	* dcroat (U+0111): B<<683.5,628.0>-<725.0,565.0>-<743.0,494.0>>/L<<743.0,494.0>--<732.0,597.0>> = 8.13010235415596

	* dcroat (U+0111): L<<732.0,177.0>--<741.0,249.0>>/B<<741.0,249.0>-<722.0,179.0>-<681.0,118.5>> = 8.06082091329955

	* dmacronbelow (U+1E0F): B<<683.5,628.0>-<725.0,565.0>-<743.0,494.0>>/L<<743.0,494.0>--<732.0,597.0>> = 8.13010235415596

	* dmacronbelow (U+1E0F): L<<732.0,177.0>--<741.0,249.0>>/B<<741.0,249.0>-<722.0,179.0>-<681.0,118.5>> = 8.06082091329955

	* f (U+0066): L<<14.0,752.0>--<264.0,752.0>>/B<<264.0,752.0>-<172.0,766.0>-<129.5,821.0>> = 8.652541791114704

	* g (U+0067): B<<681.0,632.0>-<722.0,571.0>-<740.0,502.0>>/L<<740.0,502.0>--<732.0,573.0>> = 8.192126239801764

	* g (U+0067): L<<732.0,174.0>--<741.0,247.0>>/B<<741.0,247.0>-<722.0,178.0>-<680.0,117.0>> = 8.367153015045465

	* gbreve (U+011F): B<<681.0,632.0>-<722.0,571.0>-<740.0,502.0>>/L<<740.0,502.0>--<732.0,573.0>> = 8.192126239801764

	* gbreve (U+011F): L<<732.0,174.0>--<741.0,247.0>>/B<<741.0,247.0>-<722.0,178.0>-<680.0,117.0>> = 8.367153015045465

	* gcaron (U+01E7): B<<681.0,632.0>-<722.0,571.0>-<740.0,502.0>>/L<<740.0,502.0>--<732.0,573.0>> = 8.192126239801764

	* gcaron (U+01E7): L<<732.0,174.0>--<741.0,247.0>>/B<<741.0,247.0>-<722.0,178.0>-<680.0,117.0>> = 8.367153015045465

	* gcircumflex (U+011D): B<<681.0,632.0>-<722.0,571.0>-<740.0,502.0>>/L<<740.0,502.0>--<732.0,573.0>> = 8.192126239801764

	* gcircumflex (U+011D): L<<732.0,174.0>--<741.0,247.0>>/B<<741.0,247.0>-<722.0,178.0>-<680.0,117.0>> = 8.367153015045465

	* gdotaccent (U+0121): B<<681.0,632.0>-<722.0,571.0>-<740.0,502.0>>/L<<740.0,502.0>--<732.0,573.0>> = 8.192126239801764

	* gdotaccent (U+0121): L<<732.0,174.0>--<741.0,247.0>>/B<<741.0,247.0>-<722.0,178.0>-<680.0,117.0>> = 8.367153015045465

	* p (U+0070): B<<191.5,122.0>-<150.0,185.0>-<132.0,257.0>>/L<<132.0,257.0>--<143.0,153.0>> = 7.998560946503584

	* p (U+0070): L<<143.0,573.0>--<135.0,502.0>>/B<<135.0,502.0>-<153.0,571.0>-<194.0,632.0>> = 8.192126239801764

	* q (U+0071): B<<681.0,632.0>-<722.0,571.0>-<740.0,502.0>>/L<<740.0,502.0>--<732.0,573.0>> = 8.192126239801764

	* q (U+0071): L<<732.0,153.0>--<743.0,257.0>>/B<<743.0,257.0>-<725.0,185.0>-<683.5,122.0>> = 7.998560946503584

	* r (U+0072): L<<141.0,750.0>--<141.0,497.0>>/B<<141.0,497.0>-<157.0,581.0>-<203.0,639.5>> = 10.784297867562596

	* racute (U+0155): L<<141.0,750.0>--<141.0,497.0>>/B<<141.0,497.0>-<157.0,581.0>-<203.0,639.5>> = 10.784297867562596

	* rcaron (U+0159): L<<141.0,750.0>--<141.0,497.0>>/B<<141.0,497.0>-<157.0,581.0>-<203.0,639.5>> = 10.784297867562596

	* rmacronbelow (U+1E5F): L<<141.0,750.0>--<141.0,497.0>>/B<<141.0,497.0>-<157.0,581.0>-<203.0,639.5>> = 10.784297867562596

	* thorn (U+00FE): B<<169.0,124.0>-<128.0,191.0>-<111.0,265.0>>/L<<111.0,265.0>--<122.0,144.0>> = 7.743627409451608

	* thorn (U+00FE): L<<122.0,564.0>--<111.0,460.0>>/B<<111.0,460.0>-<127.0,536.0>-<168.0,604.0>> = 5.8509755182050345

	* uni0122 (U+0122): L<<992.0,0.0>--<992.0,372.0>>/B<<992.0,372.0>-<977.0,259.0>-<926.0,173.5>> = 7.5614284276669235

	* uni0123 (U+0123): B<<681.0,632.0>-<722.0,571.0>-<740.0,502.0>>/L<<740.0,502.0>--<732.0,573.0>> = 8.192126239801764

	* uni0123 (U+0123): L<<732.0,174.0>--<741.0,247.0>>/B<<741.0,247.0>-<722.0,178.0>-<680.0,117.0>> = 8.367153015045465

	* uni0157 (U+0157): L<<141.0,750.0>--<141.0,497.0>>/B<<141.0,497.0>-<157.0,581.0>-<203.0,639.5>> = 10.784297867562596

	* uni1E0D (U+1E0D): B<<683.5,628.0>-<725.0,565.0>-<743.0,494.0>>/L<<743.0,494.0>--<732.0,597.0>> = 8.13010235415596

	* uni1E0D (U+1E0D): L<<732.0,177.0>--<741.0,249.0>>/B<<741.0,249.0>-<722.0,179.0>-<681.0,118.5>> = 8.06082091329955

	* uni1E20 (U+1E20): L<<992.0,0.0>--<992.0,372.0>>/B<<992.0,372.0>-<977.0,259.0>-<926.0,173.5>> = 7.5614284276669235

	* uni1E21 (U+1E21): B<<681.0,632.0>-<722.0,571.0>-<740.0,502.0>>/L<<740.0,502.0>--<732.0,573.0>> = 8.192126239801764

	* uni1E21 (U+1E21): L<<732.0,174.0>--<741.0,247.0>>/B<<741.0,247.0>-<722.0,178.0>-<680.0,117.0>> = 8.367153015045465

	* uni1E5B (U+1E5B): L<<141.0,750.0>--<141.0,497.0>>/B<<141.0,497.0>-<157.0,581.0>-<203.0,639.5>> = 10.784297867562596 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* IJ (U+0132): L<<1043.0,1050.0>--<1044.0,293.0>>

	* J (U+004A): L<<731.0,1050.0>--<732.0,293.0>>

	* Jcircumflex (U+0134): L<<731.0,1050.0>--<732.0,293.0>>

	* R (U+0052): L<<350.0,585.0>--<149.0,584.0>>

	* Racute (U+0154): L<<350.0,585.0>--<149.0,584.0>>

	* Rcaron (U+0158): L<<350.0,585.0>--<149.0,584.0>>

	* Rmacronbelow (U+1E5E): L<<350.0,585.0>--<149.0,584.0>>

	* U (U+0055): L<<842.0,1050.0>--<843.0,318.0>>

	* U (U+0055): L<<90.0,318.0>--<92.0,1050.0>>

	* Uacute (U+00DA): L<<842.0,1050.0>--<843.0,318.0>>

	* Uacute (U+00DA): L<<90.0,318.0>--<92.0,1050.0>>

	* Ubreve (U+016C): L<<842.0,1050.0>--<843.0,318.0>>

	* Ubreve (U+016C): L<<90.0,318.0>--<92.0,1050.0>>

	* Ucircumflex (U+00DB): L<<842.0,1050.0>--<843.0,318.0>>

	* Ucircumflex (U+00DB): L<<90.0,318.0>--<92.0,1050.0>>

	* Udieresis (U+00DC): L<<842.0,1050.0>--<843.0,318.0>>

	* Udieresis (U+00DC): L<<90.0,318.0>--<92.0,1050.0>>

	* Ugrave (U+00D9): L<<842.0,1050.0>--<843.0,318.0>>

	* Ugrave (U+00D9): L<<90.0,318.0>--<92.0,1050.0>>

	* Uhungarumlaut (U+0170): L<<842.0,1050.0>--<843.0,318.0>>

	* Uhungarumlaut (U+0170): L<<90.0,318.0>--<92.0,1050.0>>

	* Umacron (U+016A): L<<842.0,1050.0>--<843.0,318.0>>

	* Umacron (U+016A): L<<90.0,318.0>--<92.0,1050.0>>

	* Uogonek (U+0172): L<<842.0,1050.0>--<843.0,318.0>>

	* Uogonek (U+0172): L<<90.0,318.0>--<92.0,1050.0>>

	* Uring (U+016E): L<<842.0,1050.0>--<843.0,318.0>>

	* Uring (U+016E): L<<90.0,318.0>--<92.0,1050.0>>

	* Utilde (U+0168): L<<842.0,1050.0>--<843.0,318.0>>

	* Utilde (U+0168): L<<90.0,318.0>--<92.0,1050.0>>

	* b (U+0062): L<<77.0,0.0>--<75.0,1050.0>>

	* cent (U+00A2): L<<461.0,1049.0>--<462.0,915.0>>

	* d (U+0064): L<<800.0,1050.0>--<798.0,0.0>>

	* dcaron (U+010F): L<<800.0,1050.0>--<798.0,0.0>>

	* dcroat (U+0111): L<<800.0,897.0>--<798.0,0.0>>

	* dmacronbelow (U+1E0F): L<<800.0,1050.0>--<798.0,0.0>>

	* f (U+0066): L<<171.0,2.0>--<173.0,699.0>>

	* fi (U+FB01): L<<171.0,2.0>--<173.0,699.0>>

	* fi (U+FB01): L<<285.0,752.0>--<728.0,750.0>>

	* four (U+0034): L<<570.0,363.0>--<51.0,365.0>>

	* g (U+0067): L<<798.0,750.0>--<800.0,-1.0>>

	* gbreve (U+011F): L<<798.0,750.0>--<800.0,-1.0>>

	* gcaron (U+01E7): L<<798.0,750.0>--<800.0,-1.0>>

	* gcircumflex (U+011D): L<<798.0,750.0>--<800.0,-1.0>>

	* gdotaccent (U+0121): L<<798.0,750.0>--<800.0,-1.0>>

	* onequarter (U+00BC): L<<926.0,220.0>--<612.0,221.0>>

	* p (U+0070): L<<75.0,-300.0>--<77.0,750.0>>

	* q (U+0071): L<<798.0,750.0>--<800.0,-300.0>>

	* registered (U+00AE): L<<491.0,624.0>--<490.0,294.0>>

	* thorn (U+00FE): L<<54.0,-357.0>--<56.0,1212.0>>

	* threequarters (U+00BE): L<<926.0,220.0>--<612.0,221.0>>

	* uni0123 (U+0123): L<<798.0,750.0>--<800.0,-1.0>>

	* uni0156 (U+0156): L<<350.0,585.0>--<149.0,584.0>>

	* uni1E0D (U+1E0D): L<<800.0,1050.0>--<798.0,0.0>>

	* uni1E21 (U+1E21): L<<798.0,750.0>--<800.0,-1.0>>

	* uni1E5A (U+1E5A): L<<350.0,585.0>--<149.0,584.0>>

	* uni1E78 (U+1E78): L<<842.0,1050.0>--<843.0,318.0>>

	* uni1E78 (U+1E78): L<<90.0,318.0>--<92.0,1050.0>>

	* uni1E7A (U+1E7A): L<<842.0,1050.0>--<843.0,318.0>>

	* uni1E7A (U+1E7A): L<<90.0,318.0>--<92.0,1050.0>>

	* uni1EE4 (U+1EE4): L<<842.0,1050.0>--<843.0,318.0>>

	* uni1EE4 (U+1EE4): L<<90.0,318.0>--<92.0,1050.0>>

	* uni2074 (U+2074): L<<345.0,813.0>--<31.0,814.0>>

	* uni2084 (U+2084): L<<345.0,220.0>--<31.0,221.0>>

	* yen (U+00A5): L<<145.0,497.0>--<384.0,498.0>>

	* yen (U+00A5): L<<474.0,498.0>--<709.0,497.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 6 | 21 | 63 | 721 | 37 | 567 | 0 |
| 0% | 1% | 4% | 51% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
