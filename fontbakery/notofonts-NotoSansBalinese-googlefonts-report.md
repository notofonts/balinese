## FontBakery report

fontbakery version: 0.12.6



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansBalinese[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansBalinese/googlefonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[10] NotoSansBalinese[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni1B3C (U+1B3C)</p>
 [code: mark-chars]



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
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- _128

- cereg2

- cereg3

- cereg5

- nonmarkingreturn

- uni1B1A.2.nya

- uni1B3A.5

- uni1B3E001
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* uni1B13 (U+1B13) has a counter-clockwise outer contour

* uni1B13 (U+1B13) has a counter-clockwise outer contour

* uni1B13.ra_uni1B2D.conj.wa has a counter-clockwise outer contour

* uni1B13.ra_uni1B2D.conj.wa has a counter-clockwise outer contour

* uni1B13.td has a counter-clockwise outer contour

* uni1B13.td has a counter-clockwise outer contour

* uni1B14 (U+1B14) has a counter-clockwise outer contour

* uni1B14 (U+1B14) has a counter-clockwise outer contour

* uni1B18 (U+1B18) has a counter-clockwise outer contour

* uni1B18.td has a counter-clockwise outer contour

* uni1B1D (U+1B1D) has a counter-clockwise outer contour

* uni1B1E (U+1B1E) has a counter-clockwise outer contour

* uni1B26 (U+1B26) has a counter-clockwise outer contour

* uni1B26 (U+1B26) has a counter-clockwise outer contour

* uni1B26.td has a counter-clockwise outer contour

* uni1B26.td has a counter-clockwise outer contour

* uni1B32 (U+1B32) has a counter-clockwise outer contour

* uni1B32.td has a counter-clockwise outer contour

* uni1B45 (U+1B45) has a counter-clockwise outer contour

* uni1B45 (U+1B45) has a counter-clockwise outer contour

* uni1B45.td has a counter-clockwise outer contour

* uni1B45.td has a counter-clockwise outer contour

* uni1B46 (U+1B46) has a counter-clockwise outer contour

* uni1B46 (U+1B46) has a counter-clockwise outer contour

* uni1B46.td has a counter-clockwise outer contour

* uni1B46.td has a counter-clockwise outer contour

* uni1B4A (U+1B4A) has a counter-clockwise outer contour

* uni1B4A.td has a counter-clockwise outer contour

* uni1B4B (U+1B4B) has a counter-clockwise outer contour

* uni1B4B.td has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Yala (Latn, 200,000 speakers), Mango (Latn, 77,000 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Nzakara (Latn, 50,000 speakers), Nateni (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Zapotec (Latn, 490,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Koonzime (Latn, 40,000 speakers), Vute (Latn, 21,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dutch (Latn, 31,709,104 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Southern Kisi (Latn, 360,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), Aghem (Latn, 38,843 speakers), Mundani (Latn, 34,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Basaa (Latn, 332,940 speakers).</p>
 [code: soft-dotted]



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
<li>U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, malayalam, tai-le, canadian-aboriginal, math, tifinagh, old-permic, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>balinese</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



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
| 0 | 0 | 2 | 9 | 97 | 7 | 136 | 0 | 
| 0% | 0% | 1% | 4% | 39% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
