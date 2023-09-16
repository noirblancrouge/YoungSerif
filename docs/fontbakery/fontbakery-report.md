## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[7] YoungSerif-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1302, but got 1240 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- eight.subs

	- five.subs

	- four.subs

	- nine.subs

	- one.subs

	- seven.subs

	- six.subs

	- three.subs

	- two.subs

	- zero.subs
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni2206 (U+2206): L<<300.0,474.0>--<296.0,463.0>> -> L<<296.0,463.0>--<178.0,154.0>>

	* uni2206 (U+2206): L<<422.0,151.0>--<304.0,463.0>> -> L<<304.0,463.0>--<300.0,474.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* aacute (U+00E1): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* abreve (U+0103): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* acircumflex (U+00E2): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* adieresis (U+00E4): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* ae (U+00E6): L<<393.0,-10.0>--<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 13.991741900554299

	* aeacute (U+01FD): L<<393.0,-10.0>--<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 13.991741900554299

	* agrave (U+00E0): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* amacron (U+0101): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* aogonek (U+0105): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* aring (U+00E5): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* aringacute (U+01FB): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* at (U+0040): L<<606.0,-3.0>--<616.0,77.0>>/B<<616.0,77.0>-<611.0,64.0>-<595.5,42.5>> = 13.912494676520005

	* atilde (U+00E3): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579

	* d (U+0064): B<<397.5,35.0>-<400.0,57.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 10.73266455665575

	* dcaron (U+010F): B<<397.5,35.0>-<400.0,57.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 10.73266455665575

	* dcroat (U+0111): B<<397.5,35.0>-<400.0,57.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 10.73266455665575

	* dmacronbelow (U+1E0F): B<<397.5,35.0>-<400.0,57.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 10.73266455665575

	* ordfeminine (U+00AA): B<<335.0,370.0>-<337.0,386.0>-<339.0,397.0>>/B<<339.0,397.0>-<334.0,386.0>-<320.5,368.0>> = 14.139108311650501

	* uni1E0D (U+1E0D): B<<397.5,35.0>-<400.0,57.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 10.73266455665575

	* uni1EA1 (U+1EA1): B<<399.5,45.5>-<402.0,65.0>-<404.0,79.0>>/B<<404.0,79.0>-<399.0,66.0>-<382.5,44.0>> = 12.90740867126579 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 6 | 121 | 7 | 115 | 0 |
| 0% | 0% | 2% | 48% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
