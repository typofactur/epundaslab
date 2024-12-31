## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Verify that family names in the name table are consistent across all fonts in the family. Checks Typographic Family name (nameID 16) if present, otherwise uses Font Family name (nameID 1) <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>2 different Font Family names were found:</p>
<ul>
<li>
<p>'Epunda Slab Italic' was found in:</p>
<ul>
<li>EpundaSlab-Italic[wght].ttf (nameID 16)</li>
</ul>
</li>
<li>
<p>'Epunda Slab' was found in:</p>
<ul>
<li>EpundaSlab[wght].ttf (nameID 16)</li>
</ul>
</li>
</ul>
 [code: inconsistent-family-name]



</div>
</details>
</div>
</details>

<details><summary>[15] EpundaSlab-Italic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name ID 1 (Family Name) must not contain 'Italic'.</p>
 [code: bad-familyname]



* 🔥 **FAIL** <p>Name ID 16 (Typographic Family Name) must not contain 'Italic'.</p>
 [code: bad-typographicfamilyname]



* 🔥 **FAIL** <p>Name ID 17 (Typographic Subfamily Name) must contain 'Italic'.</p>
 [code: bad-typographicsubfamilyname]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Epunda Slab Italic Light SemiBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 272 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Epunda Slab Italic Light SemiBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 272 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Epunda Slab Italic Light ExtraBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 276 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Epunda Slab Italic Light ExtraBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 276 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;EpundaSlabItalic[wght].ttf. Got EpundaSlab-Italic[wght].ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
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
<td align="left">Epunda Slab Italic Light</td>
<td align="left">Epunda Slab Italic Light</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left"><strong>Italic</strong></td>
<td align="left"><strong>Regular</strong></td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Epunda Slab Italic Light</td>
<td align="left">Epunda Slab Italic Light</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">EpundaSlabItalic-Light</td>
<td align="left">EpundaSlabItalic-Light</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left">Epunda Slab Italic</td>
<td align="left">Epunda Slab Italic</td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left">Light</td>
<td align="left">Light</td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour order differs in glyph 'colon': [0, 1] in wght=300, [1, 0] in wght=900.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 600 among a set of 9 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 601:
divide, minus, plusminus</p>
<p>Width = 558:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- _serif.C.BR

- _serif.C.TR

- _serif.E.TR

- _serif.I.BL

- _serif.I.BR

- _serif.I.TL

- _serif.I.TR

- _serif.S.BL

- _serif.S.BR

- _serif.Spur

- _serif.T.TL

- _serif.T.TR

- _serif.Z.BR

- _serif.a.TL

- _serif.r.TR

- _serif.s.BL

- _serif.s.BR

- _serif.s.TR

- unbenannt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, coptic, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, canadian-aboriginal, hebrew, duployan, math, syriac, tifinagh, old-permic, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, caucasian-albanian, thai, cherokee, syriac, tifinagh, gothic</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, greek, elbasan</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: limbu, tai-viet, tagalog, hanunoo, mongolian, khudawadi, new-tai-lue, thai, gurmukhi, kharoshthi, syriac, balinese, tifinagh, tirhuta, gujarati, saurashtra, hanifi-rohingya, thaana, bengali, arabic, masaram-gondi, cham, modi, pahawh-hmong, tai-tham, takri, sundanese, khmer, batak, newa, tai-le, tagbanwa, phags-pa, kannada, buhid, dogra, kaithi, tamil, psalter-pahlavi, syloti-nagri, meetei-mayek, telugu, yi, kayah-li, duployan, grantha, gunjala-gondi, oriya, mandaic, siddham, lao, malayalam, rejang, avestan, zanabazar-square, devanagari, javanese, khojki, hatran, manichaean, nko, sinhala, tibetan, sogdian, hebrew, bhaiksuki, chakma, warang-citi, lepcha, mahajani, brahmi, myanmar, buginese, sharada</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: limbu, tai-viet, tagalog, hanunoo, mongolian, khudawadi, new-tai-lue, old-hungarian, thai, gurmukhi, kharoshthi, syriac, balinese, tifinagh, tirhuta, gujarati, saurashtra, hanifi-rohingya, thaana, bengali, arabic, masaram-gondi, cham, modi, pahawh-hmong, tai-tham, takri, sundanese, khmer, batak, newa, tai-le, tagbanwa, phags-pa, kannada, buhid, dogra, kaithi, tamil, psalter-pahlavi, syloti-nagri, meetei-mayek, telugu, yi, kayah-li, duployan, grantha, gunjala-gondi, oriya, mandaic, siddham, lao, malayalam, rejang, avestan, zanabazar-square, devanagari, javanese, khojki, nko, manichaean, sinhala, tibetan, sogdian, hebrew, bhaiksuki, chakma, warang-citi, lepcha, mahajani, brahmi, myanmar, buginese, sharada</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, thaana, arabic, hebrew, syriac, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, thaana, hebrew, syriac, phags-pa</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
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
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, tai-tham, math, yi</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mongolian, marchen, miao, saurashtra, hanifi-rohingya, cham, tai-tham, khmer, kannada, canadian-aboriginal, kaithi, telugu, psalter-pahlavi, gunjala-gondi, mandaic, malayalam, rejang, symbols, manichaean, lepcha, myanmar, osage, limbu, tai-viet, khudawadi, caucasian-albanian, math, gurmukhi, kharoshthi, balinese, old-permic, gujarati, masaram-gondi, takri, batak, tagbanwa, dogra, kayah-li, wancho, armenian, zanabazar-square, devanagari, sinhala, bhaiksuki, buginese, sharada, tagalog, new-tai-lue, music, thai, syriac, tifinagh, tirhuta, bengali, pahawh-hmong, newa, mende-kikakui, buhid, elbasan, meetei-mayek, yi, duployan, grantha, siddham, adlam, nko, sogdian, hebrew, chakma, warang-citi, mahajani, oriya, coptic, hanunoo, soyombo, ahom, bassa-vah, thaana, modi, sundanese, tai-le, tamil, lao, khojki, javanese, tibetan, phags-pa, brahmi, syloti-nagri</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-traditional, japanese, yi, chinese-simplified, phags-pa, nushu, chinese-hongkong</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: chinese-simplified, japanese</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF08 FULLWIDTH LEFT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF09 FULLWIDTH RIGHT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3B FULLWIDTH LEFT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3D FULLWIDTH RIGHT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF5B FULLWIDTH LEFT CURLY BRACKET: try adding one of: yi, chinese-simplified, math, japanese</li>
<li>U+FF5D FULLWIDTH RIGHT CURLY BRACKET: try adding one of: yi, chinese-simplified, math, japanese</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* bracketleft (U+005B) has a counter-clockwise outer contour

* bracketright (U+005D) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guilsinglleft (U+2039) has a counter-clockwise outer contour

* guilsinglright (U+203A) has a counter-clockwise outer contour

* uniFF01 (U+FF01) has a counter-clockwise outer contour

* uniFF3B (U+FF3B) has a counter-clockwise outer contour

* uniFF3D (U+FF3D) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



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

<details><summary>[11] EpundaSlab[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 250 font units wide, non-breaking space named (uni00A0) is 200 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour order differs in glyph 'colon': [0, 1] in wght=300, [1, 0] in wght=900.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- _serif.C.BR

- _serif.C.TR

- _serif.E.TR

- _serif.I.BL

- _serif.I.BR

- _serif.I.TL

- _serif.I.TR

- _serif.S.BL

- _serif.S.BR

- _serif.Spur

- _serif.T.TL

- _serif.T.TR

- _serif.Z.BR

- _serif.a.TL

- _serif.r.TR

- _serif.s.BL

- _serif.s.BR

- _serif.s.TR

- unbenannt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, coptic, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, canadian-aboriginal, hebrew, duployan, math, syriac, tifinagh, old-permic, todhri, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, caucasian-albanian, thai, cherokee, syriac, tifinagh, gothic</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, greek, elbasan</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: limbu, tai-viet, tagalog, hanunoo, mongolian, khudawadi, new-tai-lue, thai, gurmukhi, kharoshthi, syriac, balinese, tifinagh, tirhuta, gujarati, saurashtra, hanifi-rohingya, thaana, bengali, arabic, masaram-gondi, cham, modi, pahawh-hmong, tai-tham, takri, sundanese, khmer, batak, newa, tai-le, tagbanwa, phags-pa, kannada, buhid, dogra, kaithi, tamil, psalter-pahlavi, syloti-nagri, meetei-mayek, telugu, yi, kayah-li, duployan, grantha, gunjala-gondi, oriya, mandaic, siddham, lao, malayalam, rejang, avestan, zanabazar-square, devanagari, javanese, khojki, hatran, manichaean, nko, sinhala, tibetan, sogdian, hebrew, bhaiksuki, chakma, warang-citi, lepcha, mahajani, brahmi, myanmar, buginese, sharada</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: limbu, tai-viet, tagalog, hanunoo, mongolian, khudawadi, new-tai-lue, old-hungarian, thai, gurmukhi, kharoshthi, syriac, balinese, tifinagh, tirhuta, gujarati, saurashtra, hanifi-rohingya, thaana, bengali, arabic, masaram-gondi, cham, modi, pahawh-hmong, tai-tham, takri, sundanese, khmer, batak, newa, tai-le, tagbanwa, phags-pa, kannada, buhid, dogra, kaithi, tamil, psalter-pahlavi, syloti-nagri, meetei-mayek, telugu, yi, kayah-li, duployan, grantha, gunjala-gondi, oriya, mandaic, siddham, lao, malayalam, rejang, avestan, zanabazar-square, devanagari, javanese, khojki, nko, manichaean, sinhala, tibetan, sogdian, hebrew, bhaiksuki, chakma, warang-citi, lepcha, mahajani, brahmi, myanmar, buginese, sharada</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, thaana, arabic, hebrew, syriac, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, thaana, hebrew, syriac, phags-pa</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
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
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, tai-tham, math, yi</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mongolian, marchen, miao, saurashtra, hanifi-rohingya, cham, tai-tham, khmer, kannada, canadian-aboriginal, kaithi, telugu, psalter-pahlavi, gunjala-gondi, mandaic, malayalam, rejang, symbols, manichaean, lepcha, myanmar, osage, limbu, tai-viet, khudawadi, caucasian-albanian, math, gurmukhi, kharoshthi, balinese, old-permic, gujarati, masaram-gondi, takri, batak, tagbanwa, dogra, kayah-li, wancho, armenian, zanabazar-square, devanagari, sinhala, bhaiksuki, buginese, sharada, tagalog, new-tai-lue, music, thai, syriac, tifinagh, tirhuta, bengali, pahawh-hmong, newa, mende-kikakui, buhid, elbasan, meetei-mayek, yi, duployan, grantha, siddham, adlam, nko, sogdian, hebrew, chakma, warang-citi, mahajani, oriya, coptic, hanunoo, soyombo, ahom, bassa-vah, thaana, modi, sundanese, tai-le, tamil, lao, khojki, javanese, tibetan, phags-pa, brahmi, syloti-nagri</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-traditional, japanese, yi, chinese-simplified, phags-pa, nushu, chinese-hongkong</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: chinese-simplified, japanese</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF08 FULLWIDTH LEFT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF09 FULLWIDTH RIGHT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3B FULLWIDTH LEFT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3D FULLWIDTH RIGHT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF5B FULLWIDTH LEFT CURLY BRACKET: try adding one of: yi, chinese-simplified, math, japanese</li>
<li>U+FF5D FULLWIDTH RIGHT CURLY BRACKET: try adding one of: yi, chinese-simplified, math, japanese</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* bracketleft (U+005B) has a counter-clockwise outer contour

* bracketright (U+005D) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guilsinglleft (U+2039) has a counter-clockwise outer contour

* guilsinglright (U+203A) has a counter-clockwise outer contour

* uniFF01 (U+FF01) has a counter-clockwise outer contour

* uniFF3B (U+FF3B) has a counter-clockwise outer contour

* uniFF3D (U+FF3D) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



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
| 0 | 0 | 6 | 21 | 185 | 15 | 257 | 0 | 
| 0% | 0% | 1% | 4% | 38% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
