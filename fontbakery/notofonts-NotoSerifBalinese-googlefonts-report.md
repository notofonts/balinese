## FontBakery report

fontbakery version: 0.13.2





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSerifBalinese-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- uni1B43 (U+1B43)</p>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[13] NotoSerifBalinese-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking font version fields (head and name table). <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-font-version">opentype/font_version</a></summary>
    <div>







* 🔥 **FAIL** <p>head version is &quot;2.00700&quot; while name version string (for platform 3, encoding 1) is &quot;Version 2.006; ttfautohint (v1.8.4.7-5d5b)&quot;.</p>
 [code: mismatch]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-has-article">googlefonts/description/has_article</a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-non-mark-chars">opentype/gdef_non_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+1B43</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if uppercase glyphs are vertically centered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#caps-vertically-centered">caps_vertically_centered</a></summary>
    <div>







* ⚠️ **WARN** <p>Uppercase glyphs are not vertically centered in the em box.</p>
 [code: vertical-metrics-not-centered]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni1B2D.sub.alt

- uni1B2E.sub.NEW
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifBalinese/googlefonts/ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, tai-le, tifinagh, canadian-aboriginal, duployan, hebrew, todhri, old-permic, malayalam, syriac, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>balinese</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_TransLatin_Arabic glyphset:</p>
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
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
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
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
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
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
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
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* uni1B01 (U+1B01): X=-368.0,Y=716.0 (should be at cap-height 714?)

* uni1B01 (U+1B01): X=-368.0,Y=716.0 (should be at cap-height 714?)

* uni1B13 (U+1B13): X=585.5,Y=0.5 (should be at baseline 0?)

* uni1B1D (U+1B1D): X=308.0,Y=1.0 (should be at baseline 0?)

* uni1B26 (U+1B26): X=583.5,Y=0.5 (should be at baseline 0?)

* uni1B45 (U+1B45): X=686.5,Y=0.5 (should be at baseline 0?)

* uni1B45 (U+1B45): X=563.0,Y=2.0 (should be at baseline 0?)

* uni1B45 (U+1B45): X=360.0,Y=-2.0 (should be at baseline 0?)

* uni1B46 (U+1B46): X=583.5,Y=0.5 (should be at baseline 0?)

* uni1B46 (U+1B46): X=460.0,Y=2.0 (should be at baseline 0?)

* uni1B48 (U+1B48): X=336.0,Y=-1.0 (should be at baseline 0?)

* uni1B49 (U+1B49): X=336.0,Y=-1.0 (should be at baseline 0?)

* uni1B4A (U+1B4A): X=385.0,Y=-2.0 (should be at baseline 0?)

* uni1B5A (U+1B5A): X=1088.0,Y=-1.0 (should be at baseline 0?)

* uni1B5B (U+1B5B): X=847.0,Y=-2.0 (should be at baseline 0?)

* uni1B5E (U+1B5E): X=344.5,Y=1.0 (should be at baseline 0?)

* uni1B5F (U+1B5F): X=593.5,Y=1.0 (should be at baseline 0?)

* uni1B5F (U+1B5F): X=344.5,Y=1.0 (should be at baseline 0?)

* uni1B74 (U+1B74): X=540.0,Y=-1.0 (should be at baseline 0?)

* uni1B74 (U+1B74): X=111.0,Y=-1.0 (should be at baseline 0?)

* uni1B76 (U+1B76): X=528.0,Y=-1.0 (should be at baseline 0?)

* uni1B76 (U+1B76): X=99.0,Y=-1.0 (should be at baseline 0?)

* uni1B29.sub.u: X=-214.0,Y=-727.0 (should be at descender -726?)

* uni1B21.sub.u: X=-214.0,Y=-727.0 (should be at descender -726?)

* uni1B16.sub.u: X=-214.0,Y=-727.0 (should be at descender -726?)

* uni1B261B35: X=587.5,Y=2.0 (should be at baseline 0?)

* uni1B131B35: X=587.5,Y=2.0 (should be at baseline 0?)

* uni1B3A.2: X=-106.0,Y=-727.0 (should be at descender -726?)

* uni1B361B42: X=-273.0,Y=1068.0 (should be at ascender 1069?)

* uni1B361B021B42: X=-386.0,Y=1068.0 (should be at ascender 1069?)

* uni1B371B03: X=-57.0,Y=712.0 (should be at cap-height 714?)

* uni1B421B02: X=-642.0,Y=715.5 (should be at cap-height 714?)

* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

* Oslash (U+00D8): X=454.5,Y=715.5 (should be at cap-height 714?)

* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

* parenleft (U+0028): X=314.0,Y=715.0 (should be at cap-height 714?)

* parenright (U+0029): X=32.0,Y=715.0 (should be at cap-height 714?)

* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

* quotedblleft (U+201C): X=420.0,Y=715.0 (should be at cap-height 714?)

* quotedblleft (U+201C): X=220.0,Y=715.0 (should be at cap-height 714?)

* quoteleft (U+2018): X=220.0,Y=715.0 (should be at cap-height 714?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
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
| 0 | 0 | 3 | 11 | 106 | 5 | 111 | 0 | 
| 0% | 0% | 1% | 5% | 45% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
