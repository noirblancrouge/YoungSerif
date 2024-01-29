## FontBakery report

fontbakery version: 0.10.2

<details><summary><b>[8] YoungSerif-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Young Serif Regular: OS/2 sTypoAscender is 930 when it should be 1046 [code: bad-typo-ascender]
* 🔥 **FAIL** Young Serif Regular: OS/2 sTypoDescender is -275 when it should be -366 [code: bad-typo-descender]
* 🔥 **FAIL** Young Serif Regular: hhea Ascender is 930 when it should be 1046 [code: bad-hhea-ascender]
* 🔥 **FAIL** Young Serif Regular: hhea Descender is -275 when it should be -366 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.2, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02BD MODIFIER LETTER REVERSED COMMA: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02CC MODIFIER LETTER LOW VERTICAL LINE: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, old-permic, tifinagh, tai-le, malayalam, syriac, math, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, tifinagh, caucasian-albanian, cherokee, syriac
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: sora-sompeng, kharoshthi, sundanese, lisu, yi, cham, coptic, kayah-li, kaithi, syloti-nagri
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2105 CARE OF: not included in any glyphset definition
 * U+2106 CADA UNA: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+21E7 UPWARDS WHITE ARROW: try adding symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+2219 BULLET OPERATOR: try adding one of: yi, tai-tham, symbols, math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+2317 VIEWDATA SQUARE: try adding symbols
 * U+2318 PLACE OF INTEREST SIGN: try adding symbols
 * U+2325 OPTION KEY: try adding symbols
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: gujarati, sundanese, lao, malayalam, adlam, thai, hanunoo, kharoshthi, limbu, javanese, manichaean, miao, balinese, sinhala, gunjala-gondi, takri, ahom, syloti-nagri, tai-viet, caucasian-albanian, myanmar, newa, siddham, new-tai-lue, oriya, thaana, buhid, telugu, sogdian, tagbanwa, symbols, chakma, syriac, cham, music, mahajani, brahmi, masaram-gondi, mende-kikakui, rejang, coptic, bassa-vah, hanifi-rohingya, lepcha, buginese, hebrew, modi, mandaic, mongolian, grantha, zanabazar-square, wancho, tagalog, khmer, bengali, math, pahawh-hmong, tifinagh, tibetan, batak, kannada, soyombo, osage, gurmukhi, meetei-mayek, psalter-pahlavi, kayah-li, old-permic, phags-pa, bhaiksuki, sharada, tai-le, kaithi, nko, tirhuta, dogra, yi, khudawadi, marchen, devanagari, duployan, tamil, elbasan, khojki
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+2B1B BLACK LARGE SQUARE: try adding symbols
 * U+2B1C WHITE LARGE SQUARE: try adding symbols
 * U+2B98 THREE-D TOP-LIGHTED LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols
 * U+2B99 THREE-D RIGHT-LIGHTED UPWARDS EQUILATERAL ARROWHEAD: try adding symbols
 * U+2B9A THREE-D TOP-LIGHTED RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols
 * U+2B9B THREE-D LEFT-LIGHTED DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols
 * U+2B9C BLACK LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols
 * U+2B9D BLACK UPWARDS EQUILATERAL ARROWHEAD: try adding symbols
 * U+2B9E BLACK RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols
 * U+2B9F BLACK DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols
 * U+E133 : not included in any glyphset definition
 * U+E134 : not included in any glyphset definition
 * U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition
 * U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition
 * U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* AEacute
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Amacron
	* Aogonek
	* Aring
	* Aringacute
	* Atilde
	* B
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* D
	* Dcaron
	* Dcroat
	* Dmacronbelow
	* E
	* Eacute
	* Ebreve
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Eth
	* Euro
	* F
	* G
	* Gbreve
	* Gcaron
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Ibreve
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Itilde
	* J
	* Jcircumflex
	* K
	* L
	* Lacute
	* Lcaron
	* Ldot
	* Lmacronbelow
	* Lslash
	* M
	* N
	* Nacute
	* Ncaron
	* Nmacronbelow
	* Ntilde
	* O
	* OE
	* Oacute
	* Obreve
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohungarumlaut
	* Omacron
	* Oslash
	* Oslashacute
	* Otilde
	* P
	* Q
	* R
	* Racute
	* Rcaron
	* Rmacronbelow
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* T
	* Tbar
	* Tcaron
	* Thorn
	* Tmacronbelow
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* a
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* aeacute
	* agrave
	* amacron
	* ampersand
	* aogonek
	* approxequal
	* aring
	* aringacute
	* asciicircum
	* asciitilde
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* bar
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* breve
	* brokenbar
	* bullet
	* c
	* cacute
	* caron
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cedilla
	* cent
	* circle
	* circumflex
	* colon
	* comma
	* copyright
	* currency
	* d
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* dieresis
	* divide
	* dmacronbelow
	* dollar
	* dotlessi
	* e
	* eacute
	* ebreve
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.lf
	* eight.numr
	* eight.tf
	* eight.tosf
	* ellipsis
	* emacron
	* emdash
	* emptyset
	* endash
	* eng
	* eogonek
	* equal
	* estimated
	* eth
	* exclam
	* exclamdown
	* f
	* f_f
	* f_f_i
	* f_f_ij
	* f_f_l
	* f_i
	* f_l
	* figuredash
	* filledbox
	* five
	* five.dnom
	* five.lf
	* five.numr
	* five.tf
	* five.tosf
	* florin
	* four
	* four.dnom
	* four.lf
	* four.numr
	* four.tf
	* four.tosf
	* fraction
	* g
	* gbreve
	* gcaron
	* gcircumflex
	* gdotaccent
	* germandbls
	* greater
	* greaterequal
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* hbar
	* hcircumflex
	* hungarumlaut
	* hyphen
	* i
	* i.loclTRK
	* iacute
	* ibreve
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* iogonek
	* itilde
	* j
	* jcircumflex
	* k
	* kgreenlandic
	* l
	* lacute
	* lcaron
	* ldot
	* less
	* lessequal
	* lmacronbelow
	* logicalnot
	* lozenge
	* lslash
	* m
	* minus
	* multiply
	* n
	* nacute
	* napostrophe
	* ncaron
	* nine
	* nine.dnom
	* nine.lf
	* nine.numr
	* nine.tf
	* nine.tosf
	* nmacronbelow
	* notequal
	* ntilde
	* numbersign
	* o
	* oacute
	* obreve
	* ocircumflex
	* odieresis
	* oe
	* ogonek
	* ograve
	* ohungarumlaut
	* omacron
	* one
	* one.dnom
	* one.lf
	* one.numr
	* one.tf
	* one.tosf
	* onehalf
	* onequarter
	* ordfeminine
	* ordmasculine
	* oslash
	* oslashacute
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* perthousand
	* pi
	* plus
	* plusminus
	* product
	* q
	* question
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
	* quotesinglbase
	* r
	* racute
	* radical
	* rcaron
	* registered
	* ring
	* rmacronbelow
	* s
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* second
	* section
	* semicolon
	* seven
	* seven.dnom
	* seven.lf
	* seven.numr
	* seven.tf
	* seven.tosf
	* six
	* six.dnom
	* six.lf
	* six.numr
	* six.tf
	* six.tosf
	* slash
	* sterling
	* summation
	* t
	* tbar
	* tcaron
	* thorn
	* three
	* three.dnom
	* three.lf
	* three.numr
	* three.tf
	* three.tosf
	* threequarters
	* tilde
	* tildecomb
	* tmacronbelow
	* trademark
	* triagdn
	* triagup
	* two
	* two.dnom
	* two.lf
	* two.numr
	* two.tf
	* two.tosf
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhungarumlaut
	* umacron
	* underscore
	* uni004A0301
	* uni006A0301
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni018F
	* uni019D
	* uni01EA
	* uni01EB
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0232
	* uni0233
	* uni0237
	* uni0259
	* uni0272
	* uni0302
	* uni0306
	* uni0308
	* uni030A
	* uni030B
	* uni030C
	* uni0327
	* uni0328
	* uni032E
	* uni0394
	* uni03A9
	* uni03BC
	* uni1E08
	* uni1E09
	* uni1E0C
	* uni1E0D
	* uni1E14
	* uni1E15
	* uni1E16
	* uni1E17
	* uni1E1C
	* uni1E1D
	* uni1E20
	* uni1E21
	* uni1E24
	* uni1E25
	* uni1E2A
	* uni1E2B
	* uni1E2E
	* uni1E2F
	* uni1E36
	* uni1E37
	* uni1E42
	* uni1E43
	* uni1E44
	* uni1E45
	* uni1E46
	* uni1E47
	* uni1E4C
	* uni1E4D
	* uni1E4E
	* uni1E4F
	* uni1E50
	* uni1E51
	* uni1E52
	* uni1E53
	* uni1E5A
	* uni1E5B
	* uni1E60
	* uni1E61
	* uni1E62
	* uni1E63
	* uni1E64
	* uni1E65
	* uni1E66
	* uni1E67
	* uni1E68
	* uni1E69
	* uni1E6C
	* uni1E6D
	* uni1E78
	* uni1E79
	* uni1E7A
	* uni1E7B
	* uni1E8E
	* uni1E8F
	* uni1E92
	* uni1E93
	* uni1E97
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EB8
	* uni1EB9
	* uni1EBC
	* uni1EBD
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1EE4
	* uni1EE5
	* uni1EF8
	* uni1EF9
	* uni2010
	* uni2015
	* uni2070
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2087
	* uni2088
	* uni2089
	* uni2105
	* uni2106
	* uni2113
	* uni2116
	* uni2126
	* uni21E7
	* uni2206
	* uni2215
	* uni2219
	* uni2317
	* uni2318
	* uni2325
	* uni25A1
	* uni25B3
	* uni25B6
	* uni25B7
	* uni25BD
	* uni25C0
	* uni25C1
	* uni25C6
	* uni25C7
	* uni25CF
	* uni2B1B
	* uni2B1C
	* uni2B98
	* uni2B99
	* uni2B9A
	* uni2B9B
	* uni2B9C
	* uni2B9D
	* uni2B9E
	* uni2B9F
	* uogonek
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.dnom.zero
	* zero.lf
	* zero.lf.zero
	* zero.numr
	* zero.numr.zero
	* zero.tf
	* zero.tf.zero
	* zero.tosf
	* zero.tosf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ae (U+00E6): L<<346.0,-9.0>--<356.0,73.0>>/B<<356.0,73.0>-<344.0,42.0>-<312.5,15.5>> = 14.208302348654348

	* aeacute (U+01FD): L<<346.0,-9.0>--<356.0,73.0>>/B<<356.0,73.0>-<344.0,42.0>-<312.5,15.5>> = 14.208302348654348 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 1 | 2 | 5 | 119 | 8 | 119 | 0 |
| 0% | 1% | 2% | 47% | 3% | 47% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
