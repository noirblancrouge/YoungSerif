## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Verify that family names in the name table are consistent across all fonts in the family. Checks Typographic Family name (nameID 16) if present, otherwise uses Font Family name (nameID 1) <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-consistent-family-name">opentype/family/consistent_family_name</a></summary>
    <div>







* 🔥 **FAIL** <p>2 different Font Family names were found:</p>
<ul>
<li>
<p>'Young Serif SC' was found in:</p>
<ul>
<li>Young-SerifSC[wght].ttf (nameID 16)</li>
<li>Young-SerifSC-Italic[wght].ttf (nameID 16)</li>
</ul>
</li>
<li>
<p>'Young Serif' was found in:</p>
<ul>
<li>Young-Serif-Italic[wght].ttf (nameID 16)</li>
<li>Young-Serif[wght].ttf (nameID 16)</li>
</ul>
</li>
</ul>
 [code: inconsistent-family-name]



</div>
</details>
</div>
</details>

<details><summary>[13] Young-SerifSC[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure 'smcp' (small caps) lookups are defined before ligature lookups in the 'GSUB' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#smallcaps-before-ligatures">smallcaps_before_ligatures</a></summary>
    <div>







* 🔥 **FAIL** <p>'smcp' lookups are not defined before 'liga' lookups.</p>
 [code: feature-ordering]



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
<td align="left">The following base characters are missing from the font: ɔ, Ɔ, ɛ, Ɛ</td>
<td align="left">bm_Latn (Bambara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɔ, Ɔ, Ɛ, ɛ</td>
<td align="left">dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɛ, ɔ, ɛ, Ɔ</td>
<td align="left">fat_Latn (Fanti)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɓ, ɓ, ƴ, Ƴ, Ɗ, ɗ</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ƙ, Ƙ, Ɓ, Ɗ, ɓ, ƴ, Ƴ, ɗ</td>
<td align="left">ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɔ, ɛ, ɔ, Ɛ</td>
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
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŀ' and shaping the text 'ŀ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ď' and shaping the text 'ď' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ě' and shaping the text 'ě' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ň' and shaping the text 'ň' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ř' and shaping the text 'ř' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ť' and shaping the text 'ť' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ů' and shaping the text 'ů' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ľ' and shaping the text 'ľ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ł' and shaping the text 'ł' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŕ' and shaping the text 'ŕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">cs_Latn (Czech)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẃ' and shaping the text 'ẃ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẁ' and shaping the text 'ẁ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŵ' and shaping the text 'ŵ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẅ' and shaping the text 'ẅ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỳ' and shaping the text 'ỳ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŷ' and shaping the text 'ŷ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǿ' and shaping the text 'ǿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">da_Latn (Danish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ğ' and shaping the text 'ğ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ş' and shaping the text 'ş' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ſ' and shaping the text 'ſ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">de_Latn (German)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">es_Latn (Spanish)</td>
</tr>
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
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ą' and shaping the text 'ą' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ċ' and shaping the text 'ċ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ď' and shaping the text 'ď' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ð' and shaping the text 'ð' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ě' and shaping the text 'ě' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ė' and shaping the text 'ė' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ę' and shaping the text 'ę' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ğ' and shaping the text 'ğ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǧ' and shaping the text 'ǧ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ģ' and shaping the text 'ģ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ȟ' and shaping the text 'ȟ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ħ' and shaping the text 'ħ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'į' and shaping the text 'į' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǩ' and shaping the text 'ǩ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ķ' and shaping the text 'ķ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĺ' and shaping the text 'ĺ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ľ' and shaping the text 'ľ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ļ' and shaping the text 'ļ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ł' and shaping the text 'ł' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ň' and shaping the text 'ň' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ņ' and shaping the text 'ņ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ő' and shaping the text 'ő' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŕ' and shaping the text 'ŕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ř' and shaping the text 'ř' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ś' and shaping the text 'ś' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŝ' and shaping the text 'ŝ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ş' and shaping the text 'ş' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ș' and shaping the text 'ș' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ť' and shaping the text 'ť' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ţ' and shaping the text 'ţ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ț' and shaping the text 'ț' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŧ' and shaping the text 'ŧ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ů' and shaping the text 'ů' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ű' and shaping the text 'ű' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ų' and shaping the text 'ų' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ź' and shaping the text 'ź' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ż' and shaping the text 'ż' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'þ' and shaping the text 'þ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ř' and shaping the text 'ř' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ſ' and shaping the text 'ſ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǔ' and shaping the text 'ǔ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">hr_Latn (Croatian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ő' and shaping the text 'ő' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ű' and shaping the text 'ű' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">hu_Latn (Hungarian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ð' and shaping the text 'ð' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'þ' and shaping the text 'þ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">is_Latn (Icelandic)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">it_Latn (Italian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ą' and shaping the text 'ą' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ę' and shaping the text 'ę' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ė' and shaping the text 'ė' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'į' and shaping the text 'į' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ų' and shaping the text 'ų' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẽ' and shaping the text 'ẽ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĩ' and shaping the text 'ĩ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ũ' and shaping the text 'ũ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ģ' and shaping the text 'ģ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ķ' and shaping the text 'ķ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ļ' and shaping the text 'ļ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ņ' and shaping the text 'ņ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŗ' and shaping the text 'ŗ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">lv_Latn (Latvian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ċ' and shaping the text 'ċ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ġ' and shaping the text 'ġ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ħ' and shaping the text 'ħ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ż' and shaping the text 'ż' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">mt_Latn (Maltese)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǎ' and shaping the text 'ǎ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŧ' and shaping the text 'ŧ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĳ' and shaping the text 'ĳ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ą' and shaping the text 'ą' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ę' and shaping the text 'ę' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ł' and shaping the text 'ł' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ś' and shaping the text 'ś' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ź' and shaping the text 'ź' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ż' and shaping the text 'ż' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">pl_Latn (Polish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">pt_Latn (Portuguese)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ș' and shaping the text 'ș' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ț' and shaping the text 'ț' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ş' and shaping the text 'ş' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ţ' and shaping the text 'ţ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ro_Latn (Romanian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ď' and shaping the text 'ď' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĺ' and shaping the text 'ĺ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ľ' and shaping the text 'ľ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ň' and shaping the text 'ň' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŕ' and shaping the text 'ŕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ť' and shaping the text 'ť' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ő' and shaping the text 'ő' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ř' and shaping the text 'ř' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ű' and shaping the text 'ű' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sk_Latn (Slovak)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sq_Latn (Albanian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sr_Latn (Serbian (Latin))</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sv_Latn (Swedish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ğ' and shaping the text 'ğ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ş' and shaping the text 'ş' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">tr_Latn (Turkish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ả' and shaping the text 'ả' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ạ' and shaping the text 'ạ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ằ' and shaping the text 'ằ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẳ' and shaping the text 'ẳ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẵ' and shaping the text 'ẵ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ắ' and shaping the text 'ắ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ặ' and shaping the text 'ặ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ầ' and shaping the text 'ầ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẩ' and shaping the text 'ẩ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẫ' and shaping the text 'ẫ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ấ' and shaping the text 'ấ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ậ' and shaping the text 'ậ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẻ' and shaping the text 'ẻ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẽ' and shaping the text 'ẽ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẹ' and shaping the text 'ẹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ề' and shaping the text 'ề' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ể' and shaping the text 'ể' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ễ' and shaping the text 'ễ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ế' and shaping the text 'ế' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ệ' and shaping the text 'ệ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỉ' and shaping the text 'ỉ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĩ' and shaping the text 'ĩ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ị' and shaping the text 'ị' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỏ' and shaping the text 'ỏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ọ' and shaping the text 'ọ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ồ' and shaping the text 'ồ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ổ' and shaping the text 'ổ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỗ' and shaping the text 'ỗ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ố' and shaping the text 'ố' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ộ' and shaping the text 'ộ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ơ' and shaping the text 'ơ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ờ' and shaping the text 'ờ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ở' and shaping the text 'ở' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỡ' and shaping the text 'ỡ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ớ' and shaping the text 'ớ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ợ' and shaping the text 'ợ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ủ' and shaping the text 'ủ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ũ' and shaping the text 'ũ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ụ' and shaping the text 'ụ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ư' and shaping the text 'ư' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ừ' and shaping the text 'ừ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ử' and shaping the text 'ử' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ữ' and shaping the text 'ữ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ứ' and shaping the text 'ứ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ự' and shaping the text 'ự' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỳ' and shaping the text 'ỳ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỷ' and shaping the text 'ỷ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỹ' and shaping the text 'ỹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỵ' and shaping the text 'ỵ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">vi_Latn (Vietnamese)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">af_Latn (Afrikaans)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ɲ' and shaping the text 'ɲ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">bm_Latn (Bambara)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ɲ' and shaping the text 'ɲ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fat_Latn (Fanti) and tw_akuapem_Latn (Akuapem Twi)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ha_Latn (Hausa)</td>
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
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẹ' and shaping the text 'ẹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ị' and shaping the text 'ị' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ṅ' and shaping the text 'ṅ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ọ' and shaping the text 'ọ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ụ' and shaping the text 'ụ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ḿ' and shaping the text 'ḿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǹ' and shaping the text 'ǹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">lg_Latn (Ganda)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">om_Latn (Oromo), xh_Latn (Xhosa) and zu_Latn (Zulu)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sw_Latn (Swahili)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẹ' and shaping the text 'ẹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ḿ' and shaping the text 'ḿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǹ' and shaping the text 'ǹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ọ' and shaping the text 'ọ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ṣ' and shaping the text 'ṣ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">yo_Latn (Yoruba)</td>
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
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;YoungSerifSC[wght].ttf. Got Young-SerifSC[wght].ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- f_f_i</p>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 528 among a set of 12 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 500:
multiply</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni2735 (U+2735): L&lt;&lt;442.0,222.0&gt;--&lt;624.0,112.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;334.0,221.0&gt;--&lt;388.0,28.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;260.0,295.0&gt;--&lt;149.0,109.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;262.0,401.0&gt;--&lt;56.0,348.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;333.0,478.0&gt;--&lt;152.0,584.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;442.0,478.0&gt;--&lt;388.0,669.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;516.0,402.0&gt;--&lt;617.0,577.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;517.0,296.0&gt;--&lt;720.0,348.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



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







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, coptic, duployan, math, hebrew, old-permic, tifinagh, malayalam, canadian-aboriginal, syriac, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: coptic, todhri</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, duployan, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: gothic, thai, sunuwar, tifinagh, caucasian-albanian, syriac, cherokee</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2010 HYPHEN: try adding one of: kharoshthi, lisu, cham, coptic, kayah-li, sundanese, syloti-nagri, sora-sompeng, armenian, hebrew, kaithi, yi, arabic</li>
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
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, math, symbols, yi</li>
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
<li>U+2460 CIRCLED DIGIT ONE: try adding one of: mongolian, symbols, yi</li>
<li>U+2461 CIRCLED DIGIT TWO: try adding one of: mongolian, symbols, yi</li>
<li>U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, symbols, yi</li>
<li>U+2463 CIRCLED DIGIT FOUR: try adding one of: mongolian, symbols, yi</li>
<li>U+2464 CIRCLED DIGIT FIVE: try adding one of: mongolian, symbols, yi</li>
<li>U+2465 CIRCLED DIGIT SIX: try adding one of: mongolian, symbols, yi</li>
<li>U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi</li>
<li>U+2467 CIRCLED DIGIT EIGHT: try adding one of: mongolian, symbols, yi</li>
<li>U+2468 CIRCLED DIGIT NINE: try adding one of: mongolian, symbols, yi</li>
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
<li>U+25CC DOTTED CIRCLE: try adding one of: coptic, hebrew, rejang, hanunoo, thai, sogdian, tamil, kaithi, yi, mandaic, chakma, khudawadi, limbu, wancho, thaana, ahom, bassa-vah, mahajani, modi, sharada, kannada, syloti-nagri, sinhala, tirhuta, marchen, malayalam, tagbanwa, music, tagalog, devanagari, new-tai-lue, kayah-li, telugu, elbasan, gujarati, myanmar, cham, lao, tibetan, tai-tham, syriac, soyombo, buginese, zanabazar-square, grantha, gurmukhi, dogra, oriya, kharoshthi, newa, balinese, sundanese, bengali, lepcha, caucasian-albanian, meetei-mayek, phags-pa, warang-citi, masaram-gondi, duployan, javanese, old-permic, khojki, khmer, siddham, tai-le, tai-viet, math, tifinagh, manichaean, bhaiksuki, pahawh-hmong, takri, osage, nko, mende-kikakui, saurashtra, buhid, batak, brahmi, gunjala-gondi, mongolian, adlam, symbols, armenian, miao, hanifi-rohingya, canadian-aboriginal, psalter-pahlavi</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+2605 BLACK STAR: try adding symbols</li>
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
<li>U+2705 WHITE HEAVY CHECK MARK: not included in any glyphset definition</li>
<li>U+2713 CHECK MARK: try adding symbols</li>
<li>U+272F PINWHEEL STAR: try adding symbols</li>
<li>U+2735 EIGHT POINTED PINWHEEL STAR: try adding symbols</li>
<li>U+273F BLACK FLORETTE: try adding symbols</li>
<li>U+2740 WHITE FLORETTE: try adding symbols</li>
<li>U+274C CROSS MARK: try adding symbols</li>
<li>U+274E NEGATIVE SQUARED CROSS MARK: not included in any glyphset definition</li>
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
<li>U+277F DINGBAT NEGATIVE CIRCLED NUMBER TEN: try adding symbols</li>
<li>U+2789 DINGBAT CIRCLED SANS-SERIF NUMBER TEN: try adding symbols</li>
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
<li>U+E138 : not included in any glyphset definition</li>
<li>U+E139 : not included in any glyphset definition</li>
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
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* circle (U+25CB) has a counter-clockwise outer contour

* smileface (U+263A) has a counter-clockwise outer contour

* uni2460 (U+2460) has a counter-clockwise outer contour

* uni2461 (U+2461) has a counter-clockwise outer contour

* uni2462 (U+2462) has a counter-clockwise outer contour

* uni2463 (U+2463) has a counter-clockwise outer contour

* uni2464 (U+2464) has a counter-clockwise outer contour

* uni2465 (U+2465) has a counter-clockwise outer contour

* uni2466 (U+2466) has a counter-clockwise outer contour

* uni2467 (U+2467) has a counter-clockwise outer contour

* uni2468 (U+2468) has a counter-clockwise outer contour

* uni24B6 (U+24B6) has a counter-clockwise outer contour

* uni24B7 (U+24B7) has a counter-clockwise outer contour

* uni24B8 (U+24B8) has a counter-clockwise outer contour

* uni24B9 (U+24B9) has a counter-clockwise outer contour

* uni24BA (U+24BA) has a counter-clockwise outer contour

* uni24BB (U+24BB) has a counter-clockwise outer contour

* uni24BC (U+24BC) has a counter-clockwise outer contour

* uni24BD (U+24BD) has a counter-clockwise outer contour

* uni24BE (U+24BE) has a counter-clockwise outer contour

* uni24BF (U+24BF) has a counter-clockwise outer contour

* uni24C0 (U+24C0) has a counter-clockwise outer contour

* uni24C1 (U+24C1) has a counter-clockwise outer contour

* uni24C2 (U+24C2) has a counter-clockwise outer contour

* uni24C3 (U+24C3) has a counter-clockwise outer contour

* uni24C4 (U+24C4) has a counter-clockwise outer contour

* uni24C5 (U+24C5) has a counter-clockwise outer contour

* uni24C6 (U+24C6) has a counter-clockwise outer contour

* uni24C7 (U+24C7) has a counter-clockwise outer contour

* uni24C8 (U+24C8) has a counter-clockwise outer contour

* uni24C9 (U+24C9) has a counter-clockwise outer contour

* uni24CA (U+24CA) has a counter-clockwise outer contour

* uni24CB (U+24CB) has a counter-clockwise outer contour

* uni24CC (U+24CC) has a counter-clockwise outer contour

* uni24CD (U+24CD) has a counter-clockwise outer contour

* uni24CE (U+24CE) has a counter-clockwise outer contour

* uni24CF (U+24CF) has a counter-clockwise outer contour

* uni24D0 (U+24D0) has a counter-clockwise outer contour

* uni24D1 (U+24D1) has a counter-clockwise outer contour

* uni24D2 (U+24D2) has a counter-clockwise outer contour

* uni24D3 (U+24D3) has a counter-clockwise outer contour

* uni24D4 (U+24D4) has a counter-clockwise outer contour

* uni24D5 (U+24D5) has a counter-clockwise outer contour

* uni24D6 (U+24D6) has a counter-clockwise outer contour

* uni24D7 (U+24D7) has a counter-clockwise outer contour

* uni24D8 (U+24D8) has a counter-clockwise outer contour

* uni24D9 (U+24D9) has a counter-clockwise outer contour

* uni24DA (U+24DA) has a counter-clockwise outer contour

* uni24DB (U+24DB) has a counter-clockwise outer contour

* uni24DC (U+24DC) has a counter-clockwise outer contour

* uni24DD (U+24DD) has a counter-clockwise outer contour

* uni24DE (U+24DE) has a counter-clockwise outer contour

* uni24DF (U+24DF) has a counter-clockwise outer contour

* uni24E0 (U+24E0) has a counter-clockwise outer contour

* uni24E1 (U+24E1) has a counter-clockwise outer contour

* uni24E2 (U+24E2) has a counter-clockwise outer contour

* uni24E3 (U+24E3) has a counter-clockwise outer contour

* uni24E4 (U+24E4) has a counter-clockwise outer contour

* uni24E5 (U+24E5) has a counter-clockwise outer contour

* uni24E6 (U+24E6) has a counter-clockwise outer contour

* uni24E7 (U+24E7) has a counter-clockwise outer contour

* uni24E8 (U+24E8) has a counter-clockwise outer contour

* uni24E9 (U+24E9) has a counter-clockwise outer contour

* uni24EA (U+24EA) has a counter-clockwise outer contour

* uni2639 (U+2639) has a counter-clockwise outer contour

* uni2789 (U+2789) has a counter-clockwise outer contour

* uniFFFD (U+FFFD) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>
</div>
</details>

<details><summary>[13] Young-SerifSC-Italic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure 'smcp' (small caps) lookups are defined before ligature lookups in the 'GSUB' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#smallcaps-before-ligatures">smallcaps_before_ligatures</a></summary>
    <div>







* 🔥 **FAIL** <p>'smcp' lookups are not defined before 'liga' lookups.</p>
 [code: feature-ordering]



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
<td align="left">The following base characters are missing from the font: Ɛ, ɛ, Ɔ, ɔ</td>
<td align="left">bm_Latn (Bambara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɛ, ɔ, Ɔ, ɛ</td>
<td align="left">dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɛ, ɔ, ɛ, Ɔ</td>
<td align="left">fat_Latn (Fanti)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɗ, Ɓ, ƴ, Ƴ, ɗ, ɓ</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ƴ, Ɓ, Ɗ, Ƙ, ƙ, ƴ, ɗ, ɓ</td>
<td align="left">ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɛ, Ɛ, Ɔ, ɔ</td>
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
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŀ' and shaping the text 'ŀ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ď' and shaping the text 'ď' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ě' and shaping the text 'ě' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ň' and shaping the text 'ň' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ř' and shaping the text 'ř' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ť' and shaping the text 'ť' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ů' and shaping the text 'ů' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ľ' and shaping the text 'ľ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ł' and shaping the text 'ł' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŕ' and shaping the text 'ŕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">cs_Latn (Czech)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẃ' and shaping the text 'ẃ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẁ' and shaping the text 'ẁ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŵ' and shaping the text 'ŵ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẅ' and shaping the text 'ẅ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỳ' and shaping the text 'ỳ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŷ' and shaping the text 'ŷ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǿ' and shaping the text 'ǿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">da_Latn (Danish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ğ' and shaping the text 'ğ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ş' and shaping the text 'ş' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ſ' and shaping the text 'ſ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">de_Latn (German)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">es_Latn (Spanish)</td>
</tr>
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
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ą' and shaping the text 'ą' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ċ' and shaping the text 'ċ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ď' and shaping the text 'ď' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ð' and shaping the text 'ð' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ě' and shaping the text 'ě' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ė' and shaping the text 'ė' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ę' and shaping the text 'ę' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ğ' and shaping the text 'ğ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǧ' and shaping the text 'ǧ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ģ' and shaping the text 'ģ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ȟ' and shaping the text 'ȟ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ħ' and shaping the text 'ħ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'į' and shaping the text 'į' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǩ' and shaping the text 'ǩ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ķ' and shaping the text 'ķ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĺ' and shaping the text 'ĺ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ľ' and shaping the text 'ľ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ļ' and shaping the text 'ļ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ł' and shaping the text 'ł' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ň' and shaping the text 'ň' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ņ' and shaping the text 'ņ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ő' and shaping the text 'ő' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŕ' and shaping the text 'ŕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ř' and shaping the text 'ř' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ś' and shaping the text 'ś' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŝ' and shaping the text 'ŝ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ş' and shaping the text 'ş' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ș' and shaping the text 'ș' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ť' and shaping the text 'ť' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ţ' and shaping the text 'ţ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ț' and shaping the text 'ț' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŧ' and shaping the text 'ŧ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ů' and shaping the text 'ů' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ű' and shaping the text 'ű' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ų' and shaping the text 'ų' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ź' and shaping the text 'ź' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ż' and shaping the text 'ż' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'þ' and shaping the text 'þ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ř' and shaping the text 'ř' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ſ' and shaping the text 'ſ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǔ' and shaping the text 'ǔ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">hr_Latn (Croatian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ő' and shaping the text 'ő' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ű' and shaping the text 'ű' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">hu_Latn (Hungarian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ð' and shaping the text 'ð' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'þ' and shaping the text 'þ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">is_Latn (Icelandic)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">it_Latn (Italian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ą' and shaping the text 'ą' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ę' and shaping the text 'ę' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ė' and shaping the text 'ė' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'į' and shaping the text 'į' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ų' and shaping the text 'ų' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẽ' and shaping the text 'ẽ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĩ' and shaping the text 'ĩ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ũ' and shaping the text 'ũ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ģ' and shaping the text 'ģ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ķ' and shaping the text 'ķ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ļ' and shaping the text 'ļ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ņ' and shaping the text 'ņ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŗ' and shaping the text 'ŗ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">lv_Latn (Latvian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ċ' and shaping the text 'ċ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ġ' and shaping the text 'ġ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ħ' and shaping the text 'ħ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ż' and shaping the text 'ż' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">mt_Latn (Maltese)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǎ' and shaping the text 'ǎ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŧ' and shaping the text 'ŧ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĳ' and shaping the text 'ĳ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ą' and shaping the text 'ą' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ę' and shaping the text 'ę' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ł' and shaping the text 'ł' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ś' and shaping the text 'ś' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ź' and shaping the text 'ź' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ż' and shaping the text 'ż' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">pl_Latn (Polish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">pt_Latn (Portuguese)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ș' and shaping the text 'ș' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ț' and shaping the text 'ț' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ş' and shaping the text 'ş' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ţ' and shaping the text 'ţ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ro_Latn (Romanian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ď' and shaping the text 'ď' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĺ' and shaping the text 'ĺ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ľ' and shaping the text 'ľ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ň' and shaping the text 'ň' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŕ' and shaping the text 'ŕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ť' and shaping the text 'ť' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ő' and shaping the text 'ő' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ř' and shaping the text 'ř' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ű' and shaping the text 'ű' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sk_Latn (Slovak)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sq_Latn (Albanian)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'č' and shaping the text 'č' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ć' and shaping the text 'ć' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'š' and shaping the text 'š' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ž' and shaping the text 'ž' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sr_Latn (Serbian (Latin))</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sv_Latn (Swedish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ğ' and shaping the text 'ğ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ş' and shaping the text 'ş' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĕ' and shaping the text 'ĕ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĭ' and shaping the text 'ĭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŏ' and shaping the text 'ŏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ø' and shaping the text 'ø' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ß' and shaping the text 'ß' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŭ' and shaping the text 'ŭ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ÿ' and shaping the text 'ÿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">tr_Latn (Turkish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ả' and shaping the text 'ả' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ạ' and shaping the text 'ạ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ă' and shaping the text 'ă' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ằ' and shaping the text 'ằ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẳ' and shaping the text 'ẳ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẵ' and shaping the text 'ẵ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ắ' and shaping the text 'ắ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ặ' and shaping the text 'ặ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ầ' and shaping the text 'ầ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẩ' and shaping the text 'ẩ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẫ' and shaping the text 'ẫ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ấ' and shaping the text 'ấ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ậ' and shaping the text 'ậ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'đ' and shaping the text 'đ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẻ' and shaping the text 'ẻ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẽ' and shaping the text 'ẽ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẹ' and shaping the text 'ẹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ề' and shaping the text 'ề' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ể' and shaping the text 'ể' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ễ' and shaping the text 'ễ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ế' and shaping the text 'ế' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ệ' and shaping the text 'ệ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỉ' and shaping the text 'ỉ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ĩ' and shaping the text 'ĩ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ị' and shaping the text 'ị' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỏ' and shaping the text 'ỏ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'õ' and shaping the text 'õ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ọ' and shaping the text 'ọ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ồ' and shaping the text 'ồ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ổ' and shaping the text 'ổ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỗ' and shaping the text 'ỗ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ố' and shaping the text 'ố' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ộ' and shaping the text 'ộ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ơ' and shaping the text 'ơ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ờ' and shaping the text 'ờ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ở' and shaping the text 'ở' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỡ' and shaping the text 'ỡ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ớ' and shaping the text 'ớ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ợ' and shaping the text 'ợ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ủ' and shaping the text 'ủ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ũ' and shaping the text 'ũ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ụ' and shaping the text 'ụ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ư' and shaping the text 'ư' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ừ' and shaping the text 'ừ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ử' and shaping the text 'ử' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ữ' and shaping the text 'ữ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ứ' and shaping the text 'ứ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ự' and shaping the text 'ự' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỳ' and shaping the text 'ỳ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỷ' and shaping the text 'ỷ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỹ' and shaping the text 'ỹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ỵ' and shaping the text 'ỵ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">vi_Latn (Vietnamese)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ä' and shaping the text 'ä' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ë' and shaping the text 'ë' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ï' and shaping the text 'ï' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ö' and shaping the text 'ö' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ü' and shaping the text 'ü' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ý' and shaping the text 'ý' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'å' and shaping the text 'å' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ã' and shaping the text 'ã' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'æ' and shaping the text 'æ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'œ' and shaping the text 'œ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ç' and shaping the text 'ç' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">af_Latn (Afrikaans)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ɲ' and shaping the text 'ɲ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">bm_Latn (Bambara)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ɲ' and shaping the text 'ɲ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fat_Latn (Fanti) and tw_akuapem_Latn (Akuapem Twi)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ñ' and shaping the text 'ñ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'â' and shaping the text 'â' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ê' and shaping the text 'ê' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'î' and shaping the text 'î' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ô' and shaping the text 'ô' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'û' and shaping the text 'û' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ha_Latn (Hausa)</td>
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
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẹ' and shaping the text 'ẹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ị' and shaping the text 'ị' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ṅ' and shaping the text 'ṅ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ọ' and shaping the text 'ọ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ụ' and shaping the text 'ụ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ā' and shaping the text 'ā' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ē' and shaping the text 'ē' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ī' and shaping the text 'ī' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ḿ' and shaping the text 'ḿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǹ' and shaping the text 'ǹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ō' and shaping the text 'ō' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ū' and shaping the text 'ū' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ŋ' and shaping the text 'ŋ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">lg_Latn (Ganda)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">om_Latn (Oromo), xh_Latn (Xhosa) and zu_Latn (Zulu)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">sw_Latn (Swahili)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'a' and shaping the text 'a' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'á' and shaping the text 'á' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'à' and shaping the text 'à' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'b' and shaping the text 'b' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'd' and shaping the text 'd' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'e' and shaping the text 'e' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'é' and shaping the text 'é' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'è' and shaping the text 'è' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ẹ' and shaping the text 'ẹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'f' and shaping the text 'f' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'g' and shaping the text 'g' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'h' and shaping the text 'h' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'i' and shaping the text 'i' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'í' and shaping the text 'í' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ì' and shaping the text 'ì' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'j' and shaping the text 'j' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'k' and shaping the text 'k' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'l' and shaping the text 'l' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'm' and shaping the text 'm' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ḿ' and shaping the text 'ḿ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'n' and shaping the text 'n' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ń' and shaping the text 'ń' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ǹ' and shaping the text 'ǹ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'o' and shaping the text 'o' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ó' and shaping the text 'ó' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ò' and shaping the text 'ò' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ọ' and shaping the text 'ọ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'p' and shaping the text 'p' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'r' and shaping the text 'r' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 's' and shaping the text 's' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ṣ' and shaping the text 'ṣ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 't' and shaping the text 't' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'u' and shaping the text 'u' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ú' and shaping the text 'ú' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ù' and shaping the text 'ù' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'w' and shaping the text 'w' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'y' and shaping the text 'y' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'c' and shaping the text 'c' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'q' and shaping the text 'q' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'v' and shaping the text 'v' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'x' and shaping the text 'x' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'z' and shaping the text 'z' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">yo_Latn (Yoruba)</td>
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
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;YoungSerifSC-Italic[wght].ttf. Got Young-SerifSC-Italic[wght].ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- f_f_i</p>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 528 among a set of 12 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 500:
multiply</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni2735 (U+2735): L&lt;&lt;443.0,222.0&gt;--&lt;604.0,112.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;335.0,221.0&gt;--&lt;351.0,28.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;275.0,295.0&gt;--&lt;128.0,109.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;298.0,401.0&gt;--&lt;82.0,348.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;384.0,478.0&gt;--&lt;224.0,584.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;493.0,478.0&gt;--&lt;476.0,669.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;552.0,402.0&gt;--&lt;687.0,577.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;533.0,296.0&gt;--&lt;746.0,348.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



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







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, coptic, duployan, math, hebrew, old-permic, tifinagh, malayalam, canadian-aboriginal, syriac, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: coptic, todhri</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, duployan, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: gothic, thai, sunuwar, tifinagh, caucasian-albanian, syriac, cherokee</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2010 HYPHEN: try adding one of: kharoshthi, lisu, cham, coptic, kayah-li, sundanese, syloti-nagri, sora-sompeng, armenian, hebrew, kaithi, yi, arabic</li>
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
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, math, symbols, yi</li>
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
<li>U+2460 CIRCLED DIGIT ONE: try adding one of: mongolian, symbols, yi</li>
<li>U+2461 CIRCLED DIGIT TWO: try adding one of: mongolian, symbols, yi</li>
<li>U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, symbols, yi</li>
<li>U+2463 CIRCLED DIGIT FOUR: try adding one of: mongolian, symbols, yi</li>
<li>U+2464 CIRCLED DIGIT FIVE: try adding one of: mongolian, symbols, yi</li>
<li>U+2465 CIRCLED DIGIT SIX: try adding one of: mongolian, symbols, yi</li>
<li>U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi</li>
<li>U+2467 CIRCLED DIGIT EIGHT: try adding one of: mongolian, symbols, yi</li>
<li>U+2468 CIRCLED DIGIT NINE: try adding one of: mongolian, symbols, yi</li>
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
<li>U+25CC DOTTED CIRCLE: try adding one of: coptic, hebrew, rejang, hanunoo, thai, sogdian, tamil, kaithi, yi, mandaic, chakma, khudawadi, limbu, wancho, thaana, ahom, bassa-vah, mahajani, modi, sharada, kannada, syloti-nagri, sinhala, tirhuta, marchen, malayalam, tagbanwa, music, tagalog, devanagari, new-tai-lue, kayah-li, telugu, elbasan, gujarati, myanmar, cham, lao, tibetan, tai-tham, syriac, soyombo, buginese, zanabazar-square, grantha, gurmukhi, dogra, oriya, kharoshthi, newa, balinese, sundanese, bengali, lepcha, caucasian-albanian, meetei-mayek, phags-pa, warang-citi, masaram-gondi, duployan, javanese, old-permic, khojki, khmer, siddham, tai-le, tai-viet, math, tifinagh, manichaean, bhaiksuki, pahawh-hmong, takri, osage, nko, mende-kikakui, saurashtra, buhid, batak, brahmi, gunjala-gondi, mongolian, adlam, symbols, armenian, miao, hanifi-rohingya, canadian-aboriginal, psalter-pahlavi</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+2605 BLACK STAR: try adding symbols</li>
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
<li>U+2705 WHITE HEAVY CHECK MARK: not included in any glyphset definition</li>
<li>U+2713 CHECK MARK: try adding symbols</li>
<li>U+272F PINWHEEL STAR: try adding symbols</li>
<li>U+2735 EIGHT POINTED PINWHEEL STAR: try adding symbols</li>
<li>U+273F BLACK FLORETTE: try adding symbols</li>
<li>U+2740 WHITE FLORETTE: try adding symbols</li>
<li>U+274C CROSS MARK: try adding symbols</li>
<li>U+274E NEGATIVE SQUARED CROSS MARK: not included in any glyphset definition</li>
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
<li>U+277F DINGBAT NEGATIVE CIRCLED NUMBER TEN: try adding symbols</li>
<li>U+2789 DINGBAT CIRCLED SANS-SERIF NUMBER TEN: try adding symbols</li>
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
<li>U+E138 : not included in any glyphset definition</li>
<li>U+E139 : not included in any glyphset definition</li>
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
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* circle (U+25CB) has a counter-clockwise outer contour

* smileface (U+263A) has a counter-clockwise outer contour

* uni2460 (U+2460) has a counter-clockwise outer contour

* uni2461 (U+2461) has a counter-clockwise outer contour

* uni2462 (U+2462) has a counter-clockwise outer contour

* uni2463 (U+2463) has a counter-clockwise outer contour

* uni2464 (U+2464) has a counter-clockwise outer contour

* uni2465 (U+2465) has a counter-clockwise outer contour

* uni2466 (U+2466) has a counter-clockwise outer contour

* uni2467 (U+2467) has a counter-clockwise outer contour

* uni2468 (U+2468) has a counter-clockwise outer contour

* uni24B6 (U+24B6) has a counter-clockwise outer contour

* uni24B7 (U+24B7) has a counter-clockwise outer contour

* uni24B8 (U+24B8) has a counter-clockwise outer contour

* uni24B9 (U+24B9) has a counter-clockwise outer contour

* uni24BA (U+24BA) has a counter-clockwise outer contour

* uni24BB (U+24BB) has a counter-clockwise outer contour

* uni24BC (U+24BC) has a counter-clockwise outer contour

* uni24BD (U+24BD) has a counter-clockwise outer contour

* uni24BE (U+24BE) has a counter-clockwise outer contour

* uni24BF (U+24BF) has a counter-clockwise outer contour

* uni24C0 (U+24C0) has a counter-clockwise outer contour

* uni24C1 (U+24C1) has a counter-clockwise outer contour

* uni24C2 (U+24C2) has a counter-clockwise outer contour

* uni24C3 (U+24C3) has a counter-clockwise outer contour

* uni24C4 (U+24C4) has a counter-clockwise outer contour

* uni24C5 (U+24C5) has a counter-clockwise outer contour

* uni24C6 (U+24C6) has a counter-clockwise outer contour

* uni24C7 (U+24C7) has a counter-clockwise outer contour

* uni24C8 (U+24C8) has a counter-clockwise outer contour

* uni24C9 (U+24C9) has a counter-clockwise outer contour

* uni24CA (U+24CA) has a counter-clockwise outer contour

* uni24CB (U+24CB) has a counter-clockwise outer contour

* uni24CC (U+24CC) has a counter-clockwise outer contour

* uni24CD (U+24CD) has a counter-clockwise outer contour

* uni24CE (U+24CE) has a counter-clockwise outer contour

* uni24CF (U+24CF) has a counter-clockwise outer contour

* uni24D0 (U+24D0) has a counter-clockwise outer contour

* uni24D1 (U+24D1) has a counter-clockwise outer contour

* uni24D2 (U+24D2) has a counter-clockwise outer contour

* uni24D3 (U+24D3) has a counter-clockwise outer contour

* uni24D4 (U+24D4) has a counter-clockwise outer contour

* uni24D5 (U+24D5) has a counter-clockwise outer contour

* uni24D6 (U+24D6) has a counter-clockwise outer contour

* uni24D7 (U+24D7) has a counter-clockwise outer contour

* uni24D8 (U+24D8) has a counter-clockwise outer contour

* uni24D9 (U+24D9) has a counter-clockwise outer contour

* uni24DA (U+24DA) has a counter-clockwise outer contour

* uni24DB (U+24DB) has a counter-clockwise outer contour

* uni24DC (U+24DC) has a counter-clockwise outer contour

* uni24DD (U+24DD) has a counter-clockwise outer contour

* uni24DE (U+24DE) has a counter-clockwise outer contour

* uni24DF (U+24DF) has a counter-clockwise outer contour

* uni24E0 (U+24E0) has a counter-clockwise outer contour

* uni24E1 (U+24E1) has a counter-clockwise outer contour

* uni24E2 (U+24E2) has a counter-clockwise outer contour

* uni24E3 (U+24E3) has a counter-clockwise outer contour

* uni24E4 (U+24E4) has a counter-clockwise outer contour

* uni24E5 (U+24E5) has a counter-clockwise outer contour

* uni24E6 (U+24E6) has a counter-clockwise outer contour

* uni24E7 (U+24E7) has a counter-clockwise outer contour

* uni24E8 (U+24E8) has a counter-clockwise outer contour

* uni24E9 (U+24E9) has a counter-clockwise outer contour

* uni24EA (U+24EA) has a counter-clockwise outer contour

* uni2639 (U+2639) has a counter-clockwise outer contour

* uni2789 (U+2789) has a counter-clockwise outer contour

* uniFFFD (U+FFFD) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>
</div>
</details>

<details><summary>[15] Young-Serif-Italic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure 'smcp' (small caps) lookups are defined before ligature lookups in the 'GSUB' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#smallcaps-before-ligatures">smallcaps_before_ligatures</a></summary>
    <div>







* 🔥 **FAIL** <p>'smcp' lookups are not defined before 'liga' lookups.</p>
 [code: feature-ordering]



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
<td align="left">The following base characters are missing from the font: ɔ, Ɔ, Ɛ, ɛ</td>
<td align="left">bm_Latn (Bambara) and dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɛ, Ɔ, ɔ, ɛ</td>
<td align="left">fat_Latn (Fanti)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɓ, ƴ, Ƴ, Ɗ, ɗ, Ɓ</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɗ, ƙ, Ƴ, Ɓ, ƴ, ɓ, ɗ, Ƙ</td>
<td align="left">ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɛ, ɛ, ɔ, Ɔ</td>
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
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ſ' and shaping the text 'ſ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">de_Latn (German)</td>
</tr>
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
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fi_Latn (Finnish) and tr_Latn (Turkish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ſ' and shaping the text 'ſ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fr_Latn (French)</td>
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
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;YoungSerif-Italic[wght].ttf. Got Young-Serif-Italic[wght].ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 🔥 **FAIL** <p>Young Serif SC Light: OS/2 sTypoAscender is 930 when it should be 1046</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Young Serif SC Light: OS/2 sTypoDescender is -275 when it should be -366</p>
 [code: bad-typo-descender]



* 🔥 **FAIL** <p>Young Serif SC Light: hhea Ascender is 930 when it should be 1046</p>
 [code: bad-hhea-ascender]



* 🔥 **FAIL** <p>Young Serif SC Light: hhea Descender is -275 when it should be -366</p>
 [code: bad-hhea-descender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- f_f_i</p>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 528 among a set of 12 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 500:
multiply</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni2735 (U+2735): L&lt;&lt;443.0,222.0&gt;--&lt;604.0,112.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;335.0,221.0&gt;--&lt;351.0,28.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;275.0,295.0&gt;--&lt;128.0,109.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;298.0,401.0&gt;--&lt;82.0,348.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;384.0,478.0&gt;--&lt;224.0,584.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;493.0,478.0&gt;--&lt;476.0,669.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;552.0,402.0&gt;--&lt;687.0,577.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;533.0,296.0&gt;--&lt;746.0,348.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



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







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, coptic, duployan, math, hebrew, old-permic, tifinagh, malayalam, canadian-aboriginal, syriac, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: coptic, todhri</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, duployan, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: gothic, thai, sunuwar, tifinagh, caucasian-albanian, syriac, cherokee</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2010 HYPHEN: try adding one of: kharoshthi, lisu, cham, coptic, kayah-li, sundanese, syloti-nagri, sora-sompeng, armenian, hebrew, kaithi, yi, arabic</li>
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
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, math, symbols, yi</li>
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
<li>U+2460 CIRCLED DIGIT ONE: try adding one of: mongolian, symbols, yi</li>
<li>U+2461 CIRCLED DIGIT TWO: try adding one of: mongolian, symbols, yi</li>
<li>U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, symbols, yi</li>
<li>U+2463 CIRCLED DIGIT FOUR: try adding one of: mongolian, symbols, yi</li>
<li>U+2464 CIRCLED DIGIT FIVE: try adding one of: mongolian, symbols, yi</li>
<li>U+2465 CIRCLED DIGIT SIX: try adding one of: mongolian, symbols, yi</li>
<li>U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi</li>
<li>U+2467 CIRCLED DIGIT EIGHT: try adding one of: mongolian, symbols, yi</li>
<li>U+2468 CIRCLED DIGIT NINE: try adding one of: mongolian, symbols, yi</li>
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
<li>U+25CC DOTTED CIRCLE: try adding one of: coptic, hebrew, rejang, hanunoo, thai, sogdian, tamil, kaithi, yi, mandaic, chakma, khudawadi, limbu, wancho, thaana, ahom, bassa-vah, mahajani, modi, sharada, kannada, syloti-nagri, sinhala, tirhuta, marchen, malayalam, tagbanwa, music, tagalog, devanagari, new-tai-lue, kayah-li, telugu, elbasan, gujarati, myanmar, cham, lao, tibetan, tai-tham, syriac, soyombo, buginese, zanabazar-square, grantha, gurmukhi, dogra, oriya, kharoshthi, newa, balinese, sundanese, bengali, lepcha, caucasian-albanian, meetei-mayek, phags-pa, warang-citi, masaram-gondi, duployan, javanese, old-permic, khojki, khmer, siddham, tai-le, tai-viet, math, tifinagh, manichaean, bhaiksuki, pahawh-hmong, takri, osage, nko, mende-kikakui, saurashtra, buhid, batak, brahmi, gunjala-gondi, mongolian, adlam, symbols, armenian, miao, hanifi-rohingya, canadian-aboriginal, psalter-pahlavi</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+2605 BLACK STAR: try adding symbols</li>
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
<li>U+2705 WHITE HEAVY CHECK MARK: not included in any glyphset definition</li>
<li>U+2713 CHECK MARK: try adding symbols</li>
<li>U+272F PINWHEEL STAR: try adding symbols</li>
<li>U+2735 EIGHT POINTED PINWHEEL STAR: try adding symbols</li>
<li>U+273F BLACK FLORETTE: try adding symbols</li>
<li>U+2740 WHITE FLORETTE: try adding symbols</li>
<li>U+274C CROSS MARK: try adding symbols</li>
<li>U+274E NEGATIVE SQUARED CROSS MARK: not included in any glyphset definition</li>
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
<li>U+277F DINGBAT NEGATIVE CIRCLED NUMBER TEN: try adding symbols</li>
<li>U+2789 DINGBAT CIRCLED SANS-SERIF NUMBER TEN: try adding symbols</li>
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
<li>U+E138 : not included in any glyphset definition</li>
<li>U+E139 : not included in any glyphset definition</li>
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
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* circle (U+25CB) has a counter-clockwise outer contour

* smileface (U+263A) has a counter-clockwise outer contour

* uni2460 (U+2460) has a counter-clockwise outer contour

* uni2461 (U+2461) has a counter-clockwise outer contour

* uni2462 (U+2462) has a counter-clockwise outer contour

* uni2463 (U+2463) has a counter-clockwise outer contour

* uni2464 (U+2464) has a counter-clockwise outer contour

* uni2465 (U+2465) has a counter-clockwise outer contour

* uni2466 (U+2466) has a counter-clockwise outer contour

* uni2467 (U+2467) has a counter-clockwise outer contour

* uni2468 (U+2468) has a counter-clockwise outer contour

* uni24B6 (U+24B6) has a counter-clockwise outer contour

* uni24B7 (U+24B7) has a counter-clockwise outer contour

* uni24B8 (U+24B8) has a counter-clockwise outer contour

* uni24B9 (U+24B9) has a counter-clockwise outer contour

* uni24BA (U+24BA) has a counter-clockwise outer contour

* uni24BB (U+24BB) has a counter-clockwise outer contour

* uni24BC (U+24BC) has a counter-clockwise outer contour

* uni24BD (U+24BD) has a counter-clockwise outer contour

* uni24BE (U+24BE) has a counter-clockwise outer contour

* uni24BF (U+24BF) has a counter-clockwise outer contour

* uni24C0 (U+24C0) has a counter-clockwise outer contour

* uni24C1 (U+24C1) has a counter-clockwise outer contour

* uni24C2 (U+24C2) has a counter-clockwise outer contour

* uni24C3 (U+24C3) has a counter-clockwise outer contour

* uni24C4 (U+24C4) has a counter-clockwise outer contour

* uni24C5 (U+24C5) has a counter-clockwise outer contour

* uni24C6 (U+24C6) has a counter-clockwise outer contour

* uni24C7 (U+24C7) has a counter-clockwise outer contour

* uni24C8 (U+24C8) has a counter-clockwise outer contour

* uni24C9 (U+24C9) has a counter-clockwise outer contour

* uni24CA (U+24CA) has a counter-clockwise outer contour

* uni24CB (U+24CB) has a counter-clockwise outer contour

* uni24CC (U+24CC) has a counter-clockwise outer contour

* uni24CD (U+24CD) has a counter-clockwise outer contour

* uni24CE (U+24CE) has a counter-clockwise outer contour

* uni24CF (U+24CF) has a counter-clockwise outer contour

* uni24D0 (U+24D0) has a counter-clockwise outer contour

* uni24D1 (U+24D1) has a counter-clockwise outer contour

* uni24D2 (U+24D2) has a counter-clockwise outer contour

* uni24D3 (U+24D3) has a counter-clockwise outer contour

* uni24D4 (U+24D4) has a counter-clockwise outer contour

* uni24D5 (U+24D5) has a counter-clockwise outer contour

* uni24D6 (U+24D6) has a counter-clockwise outer contour

* uni24D7 (U+24D7) has a counter-clockwise outer contour

* uni24D8 (U+24D8) has a counter-clockwise outer contour

* uni24D9 (U+24D9) has a counter-clockwise outer contour

* uni24DA (U+24DA) has a counter-clockwise outer contour

* uni24DB (U+24DB) has a counter-clockwise outer contour

* uni24DC (U+24DC) has a counter-clockwise outer contour

* uni24DD (U+24DD) has a counter-clockwise outer contour

* uni24DE (U+24DE) has a counter-clockwise outer contour

* uni24DF (U+24DF) has a counter-clockwise outer contour

* uni24E0 (U+24E0) has a counter-clockwise outer contour

* uni24E1 (U+24E1) has a counter-clockwise outer contour

* uni24E2 (U+24E2) has a counter-clockwise outer contour

* uni24E3 (U+24E3) has a counter-clockwise outer contour

* uni24E4 (U+24E4) has a counter-clockwise outer contour

* uni24E5 (U+24E5) has a counter-clockwise outer contour

* uni24E6 (U+24E6) has a counter-clockwise outer contour

* uni24E7 (U+24E7) has a counter-clockwise outer contour

* uni24E8 (U+24E8) has a counter-clockwise outer contour

* uni24E9 (U+24E9) has a counter-clockwise outer contour

* uni24EA (U+24EA) has a counter-clockwise outer contour

* uni2639 (U+2639) has a counter-clockwise outer contour

* uni2789 (U+2789) has a counter-clockwise outer contour

* uniFFFD (U+FFFD) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>
</div>
</details>

<details><summary>[15] Young-Serif[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure 'smcp' (small caps) lookups are defined before ligature lookups in the 'GSUB' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#smallcaps-before-ligatures">smallcaps_before_ligatures</a></summary>
    <div>







* 🔥 **FAIL** <p>'smcp' lookups are not defined before 'liga' lookups.</p>
 [code: feature-ordering]



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
<td align="left">The following base characters are missing from the font: Ɛ, Ɔ, ɛ, ɔ</td>
<td align="left">bm_Latn (Bambara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɛ, ɛ, ɔ, Ɔ</td>
<td align="left">dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɔ, ɛ, Ɛ, ɔ</td>
<td align="left">fat_Latn (Fanti)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ƴ, ɗ, ƴ, Ɗ, ɓ, Ɓ</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɗ, Ƙ, Ƴ, ɓ, ƙ, Ɓ, ɗ, ƴ</td>
<td align="left">ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɔ, Ɛ, ɛ, Ɔ</td>
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
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ſ' and shaping the text 'ſ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">de_Latn (German)</td>
</tr>
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
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ı' and shaping the text 'ı' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fi_Latn (Finnish) and tr_Latn (Turkish)</td>
</tr>
<tr>
<td align="left">Small caps for Latin letters:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">When shaping the text 'ſ' and shaping the text 'ſ' with features: smcp, the output is expected to be different, but was the same</td>
<td align="left">fr_Latn (French)</td>
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
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;YoungSerif[wght].ttf. Got Young-Serif[wght].ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 🔥 **FAIL** <p>Young Serif SC Light: OS/2 sTypoAscender is 930 when it should be 1046</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Young Serif SC Light: OS/2 sTypoDescender is -275 when it should be -366</p>
 [code: bad-typo-descender]



* 🔥 **FAIL** <p>Young Serif SC Light: hhea Ascender is 930 when it should be 1046</p>
 [code: bad-hhea-ascender]



* 🔥 **FAIL** <p>Young Serif SC Light: hhea Descender is -275 when it should be -366</p>
 [code: bad-hhea-descender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- f_f_i</p>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 528 among a set of 12 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 500:
multiply</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni2735 (U+2735): L&lt;&lt;442.0,222.0&gt;--&lt;624.0,112.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;334.0,221.0&gt;--&lt;388.0,28.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;260.0,295.0&gt;--&lt;149.0,109.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;262.0,401.0&gt;--&lt;56.0,348.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;333.0,478.0&gt;--&lt;152.0,584.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;442.0,478.0&gt;--&lt;388.0,669.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;516.0,402.0&gt;--&lt;617.0,577.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;517.0,296.0&gt;--&lt;720.0,348.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



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







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, coptic, duployan, math, hebrew, old-permic, tifinagh, malayalam, canadian-aboriginal, syriac, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: coptic, todhri</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, duployan, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: gothic, thai, sunuwar, tifinagh, caucasian-albanian, syriac, cherokee</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2010 HYPHEN: try adding one of: kharoshthi, lisu, cham, coptic, kayah-li, sundanese, syloti-nagri, sora-sompeng, armenian, hebrew, kaithi, yi, arabic</li>
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
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, math, symbols, yi</li>
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
<li>U+2460 CIRCLED DIGIT ONE: try adding one of: mongolian, symbols, yi</li>
<li>U+2461 CIRCLED DIGIT TWO: try adding one of: mongolian, symbols, yi</li>
<li>U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, symbols, yi</li>
<li>U+2463 CIRCLED DIGIT FOUR: try adding one of: mongolian, symbols, yi</li>
<li>U+2464 CIRCLED DIGIT FIVE: try adding one of: mongolian, symbols, yi</li>
<li>U+2465 CIRCLED DIGIT SIX: try adding one of: mongolian, symbols, yi</li>
<li>U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi</li>
<li>U+2467 CIRCLED DIGIT EIGHT: try adding one of: mongolian, symbols, yi</li>
<li>U+2468 CIRCLED DIGIT NINE: try adding one of: mongolian, symbols, yi</li>
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
<li>U+25CC DOTTED CIRCLE: try adding one of: coptic, hebrew, rejang, hanunoo, thai, sogdian, tamil, kaithi, yi, mandaic, chakma, khudawadi, limbu, wancho, thaana, ahom, bassa-vah, mahajani, modi, sharada, kannada, syloti-nagri, sinhala, tirhuta, marchen, malayalam, tagbanwa, music, tagalog, devanagari, new-tai-lue, kayah-li, telugu, elbasan, gujarati, myanmar, cham, lao, tibetan, tai-tham, syriac, soyombo, buginese, zanabazar-square, grantha, gurmukhi, dogra, oriya, kharoshthi, newa, balinese, sundanese, bengali, lepcha, caucasian-albanian, meetei-mayek, phags-pa, warang-citi, masaram-gondi, duployan, javanese, old-permic, khojki, khmer, siddham, tai-le, tai-viet, math, tifinagh, manichaean, bhaiksuki, pahawh-hmong, takri, osage, nko, mende-kikakui, saurashtra, buhid, batak, brahmi, gunjala-gondi, mongolian, adlam, symbols, armenian, miao, hanifi-rohingya, canadian-aboriginal, psalter-pahlavi</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+2605 BLACK STAR: try adding symbols</li>
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
<li>U+2705 WHITE HEAVY CHECK MARK: not included in any glyphset definition</li>
<li>U+2713 CHECK MARK: try adding symbols</li>
<li>U+272F PINWHEEL STAR: try adding symbols</li>
<li>U+2735 EIGHT POINTED PINWHEEL STAR: try adding symbols</li>
<li>U+273F BLACK FLORETTE: try adding symbols</li>
<li>U+2740 WHITE FLORETTE: try adding symbols</li>
<li>U+274C CROSS MARK: try adding symbols</li>
<li>U+274E NEGATIVE SQUARED CROSS MARK: not included in any glyphset definition</li>
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
<li>U+277F DINGBAT NEGATIVE CIRCLED NUMBER TEN: try adding symbols</li>
<li>U+2789 DINGBAT CIRCLED SANS-SERIF NUMBER TEN: try adding symbols</li>
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
<li>U+E138 : not included in any glyphset definition</li>
<li>U+E139 : not included in any glyphset definition</li>
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
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* circle (U+25CB) has a counter-clockwise outer contour

* smileface (U+263A) has a counter-clockwise outer contour

* uni2460 (U+2460) has a counter-clockwise outer contour

* uni2461 (U+2461) has a counter-clockwise outer contour

* uni2462 (U+2462) has a counter-clockwise outer contour

* uni2463 (U+2463) has a counter-clockwise outer contour

* uni2464 (U+2464) has a counter-clockwise outer contour

* uni2465 (U+2465) has a counter-clockwise outer contour

* uni2466 (U+2466) has a counter-clockwise outer contour

* uni2467 (U+2467) has a counter-clockwise outer contour

* uni2468 (U+2468) has a counter-clockwise outer contour

* uni24B6 (U+24B6) has a counter-clockwise outer contour

* uni24B7 (U+24B7) has a counter-clockwise outer contour

* uni24B8 (U+24B8) has a counter-clockwise outer contour

* uni24B9 (U+24B9) has a counter-clockwise outer contour

* uni24BA (U+24BA) has a counter-clockwise outer contour

* uni24BB (U+24BB) has a counter-clockwise outer contour

* uni24BC (U+24BC) has a counter-clockwise outer contour

* uni24BD (U+24BD) has a counter-clockwise outer contour

* uni24BE (U+24BE) has a counter-clockwise outer contour

* uni24BF (U+24BF) has a counter-clockwise outer contour

* uni24C0 (U+24C0) has a counter-clockwise outer contour

* uni24C1 (U+24C1) has a counter-clockwise outer contour

* uni24C2 (U+24C2) has a counter-clockwise outer contour

* uni24C3 (U+24C3) has a counter-clockwise outer contour

* uni24C4 (U+24C4) has a counter-clockwise outer contour

* uni24C5 (U+24C5) has a counter-clockwise outer contour

* uni24C6 (U+24C6) has a counter-clockwise outer contour

* uni24C7 (U+24C7) has a counter-clockwise outer contour

* uni24C8 (U+24C8) has a counter-clockwise outer contour

* uni24C9 (U+24C9) has a counter-clockwise outer contour

* uni24CA (U+24CA) has a counter-clockwise outer contour

* uni24CB (U+24CB) has a counter-clockwise outer contour

* uni24CC (U+24CC) has a counter-clockwise outer contour

* uni24CD (U+24CD) has a counter-clockwise outer contour

* uni24CE (U+24CE) has a counter-clockwise outer contour

* uni24CF (U+24CF) has a counter-clockwise outer contour

* uni24D0 (U+24D0) has a counter-clockwise outer contour

* uni24D1 (U+24D1) has a counter-clockwise outer contour

* uni24D2 (U+24D2) has a counter-clockwise outer contour

* uni24D3 (U+24D3) has a counter-clockwise outer contour

* uni24D4 (U+24D4) has a counter-clockwise outer contour

* uni24D5 (U+24D5) has a counter-clockwise outer contour

* uni24D6 (U+24D6) has a counter-clockwise outer contour

* uni24D7 (U+24D7) has a counter-clockwise outer contour

* uni24D8 (U+24D8) has a counter-clockwise outer contour

* uni24D9 (U+24D9) has a counter-clockwise outer contour

* uni24DA (U+24DA) has a counter-clockwise outer contour

* uni24DB (U+24DB) has a counter-clockwise outer contour

* uni24DC (U+24DC) has a counter-clockwise outer contour

* uni24DD (U+24DD) has a counter-clockwise outer contour

* uni24DE (U+24DE) has a counter-clockwise outer contour

* uni24DF (U+24DF) has a counter-clockwise outer contour

* uni24E0 (U+24E0) has a counter-clockwise outer contour

* uni24E1 (U+24E1) has a counter-clockwise outer contour

* uni24E2 (U+24E2) has a counter-clockwise outer contour

* uni24E3 (U+24E3) has a counter-clockwise outer contour

* uni24E4 (U+24E4) has a counter-clockwise outer contour

* uni24E5 (U+24E5) has a counter-clockwise outer contour

* uni24E6 (U+24E6) has a counter-clockwise outer contour

* uni24E7 (U+24E7) has a counter-clockwise outer contour

* uni24E8 (U+24E8) has a counter-clockwise outer contour

* uni24E9 (U+24E9) has a counter-clockwise outer contour

* uni24EA (U+24EA) has a counter-clockwise outer contour

* uni2639 (U+2639) has a counter-clockwise outer contour

* uni2789 (U+2789) has a counter-clockwise outer contour

* uniFFFD (U+FFFD) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 19 | 38 | 336 | 33 | 467 | 0 | 
| 0% | 0% | 2% | 4% | 38% | 4% | 52% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
