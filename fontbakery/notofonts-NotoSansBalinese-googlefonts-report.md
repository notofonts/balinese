## FontBakery report

fontbakery version: 0.12.6



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansBalinese-SemiBold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansBalinese/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>

<details><summary>[1] NotoSansBalinese-Medium.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansBalinese/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>

<details><summary>[1] NotoSansBalinese-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansBalinese/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>

<details><summary>[1] NotoSansBalinese-Bold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansBalinese/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[12] NotoSansBalinese-SemiBold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1381, but got 1363 instead</p>
 [code: ascent]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uni1B16 (U+1B16): L&lt;&lt;1044.0,-10.0&gt;--&lt;1044.0,-10.0&gt;&gt; -&gt; L&lt;&lt;1044.0,-10.0&gt;--&lt;1044.0,-10.0&gt;&gt;

* uni1B16.ra: L&lt;&lt;1295.0,-10.0&gt;--&lt;1295.0,-10.0&gt;&gt; -&gt; L&lt;&lt;1295.0,-10.0&gt;--&lt;1295.0,-10.0&gt;&gt;

* uni1B18 (U+1B18): L&lt;&lt;626.0,-10.0&gt;--&lt;626.0,-10.0&gt;&gt; -&gt; L&lt;&lt;626.0,-10.0&gt;--&lt;626.0,-10.0&gt;&gt;

* uni1B18.ra: L&lt;&lt;910.0,-10.0&gt;--&lt;910.0,-10.0&gt;&gt; -&gt; L&lt;&lt;910.0,-10.0&gt;--&lt;910.0,-10.0&gt;&gt;

* uni1B1B.conj.td: L&lt;&lt;328.0,230.0&gt;--&lt;328.0,230.0&gt;&gt; -&gt; L&lt;&lt;328.0,230.0&gt;--&lt;328.0,230.0&gt;&gt;

* uni1B1E (U+1B1E): L&lt;&lt;368.0,0.0&gt;--&lt;368.0,0.0&gt;&gt; -&gt; L&lt;&lt;368.0,0.0&gt;--&lt;368.0,0.0&gt;&gt;

* uni1B1E.ra: L&lt;&lt;639.0,0.0&gt;--&lt;639.0,0.0&gt;&gt; -&gt; L&lt;&lt;639.0,0.0&gt;--&lt;639.0,0.0&gt;&gt;

* uni1B24 (U+1B24): L&lt;&lt;652.0,546.0&gt;--&lt;652.0,546.0&gt;&gt; -&gt; L&lt;&lt;652.0,546.0&gt;--&lt;652.0,546.0&gt;&gt;

* uni1B24.ra: L&lt;&lt;1004.0,546.0&gt;--&lt;1004.0,546.0&gt;&gt; -&gt; L&lt;&lt;1004.0,546.0&gt;--&lt;1004.0,546.0&gt;&gt;

* uni1B24.td: L&lt;&lt;644.0,546.0&gt;--&lt;644.0,546.0&gt;&gt; -&gt; L&lt;&lt;644.0,546.0&gt;--&lt;644.0,546.0&gt;&gt;

* uni1B2D (U+1B2D): L&lt;&lt;575.0,546.0&gt;--&lt;575.0,546.0&gt;&gt; -&gt; L&lt;&lt;575.0,546.0&gt;--&lt;575.0,546.0&gt;&gt;

* uni1B2D.ra: L&lt;&lt;872.0,546.0&gt;--&lt;872.0,546.0&gt;&gt; -&gt; L&lt;&lt;872.0,546.0&gt;--&lt;872.0,546.0&gt;&gt;

* uni1B2E.td: L&lt;&lt;380.0,0.0&gt;--&lt;380.0,0.0&gt;&gt; -&gt; L&lt;&lt;380.0,0.0&gt;--&lt;380.0,0.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): B&lt;&lt;258.0,184.5&gt;-&lt;264.0,152.0&gt;-&lt;267.0,127.0&gt;&gt;/B&lt;&lt;267.0,127.0&gt;-&lt;270.0,153.0&gt;-&lt;276.0,185.5&gt;&gt; = 13.424718067808929

* W (U+0057): B&lt;&lt;678.0,183.5&gt;-&lt;684.0,151.0&gt;-&lt;687.0,127.0&gt;&gt;/B&lt;&lt;687.0,127.0&gt;-&lt;690.0,152.0&gt;-&lt;696.0,184.5&gt;&gt; = 13.967789761532726

* Wacute (U+1E82): B&lt;&lt;258.0,184.5&gt;-&lt;264.0,152.0&gt;-&lt;267.0,127.0&gt;&gt;/B&lt;&lt;267.0,127.0&gt;-&lt;270.0,153.0&gt;-&lt;276.0,185.5&gt;&gt; = 13.424718067808929

* Wacute (U+1E82): B&lt;&lt;678.0,183.5&gt;-&lt;684.0,151.0&gt;-&lt;687.0,127.0&gt;&gt;/B&lt;&lt;687.0,127.0&gt;-&lt;690.0,152.0&gt;-&lt;696.0,184.5&gt;&gt; = 13.967789761532726

* Wcircumflex (U+0174): B&lt;&lt;258.0,184.5&gt;-&lt;264.0,152.0&gt;-&lt;267.0,127.0&gt;&gt;/B&lt;&lt;267.0,127.0&gt;-&lt;270.0,153.0&gt;-&lt;276.0,185.5&gt;&gt; = 13.424718067808929

* Wcircumflex (U+0174): B&lt;&lt;678.0,183.5&gt;-&lt;684.0,151.0&gt;-&lt;687.0,127.0&gt;&gt;/B&lt;&lt;687.0,127.0&gt;-&lt;690.0,152.0&gt;-&lt;696.0,184.5&gt;&gt; = 13.967789761532726

* Wdieresis (U+1E84): B&lt;&lt;258.0,184.5&gt;-&lt;264.0,152.0&gt;-&lt;267.0,127.0&gt;&gt;/B&lt;&lt;267.0,127.0&gt;-&lt;270.0,153.0&gt;-&lt;276.0,185.5&gt;&gt; = 13.424718067808929

* Wdieresis (U+1E84): B&lt;&lt;678.0,183.5&gt;-&lt;684.0,151.0&gt;-&lt;687.0,127.0&gt;&gt;/B&lt;&lt;687.0,127.0&gt;-&lt;690.0,152.0&gt;-&lt;696.0,184.5&gt;&gt; = 13.967789761532726

* Wgrave (U+1E80): B&lt;&lt;258.0,184.5&gt;-&lt;264.0,152.0&gt;-&lt;267.0,127.0&gt;&gt;/B&lt;&lt;267.0,127.0&gt;-&lt;270.0,153.0&gt;-&lt;276.0,185.5&gt;&gt; = 13.424718067808929

* Wgrave (U+1E80): B&lt;&lt;678.0,183.5&gt;-&lt;684.0,151.0&gt;-&lt;687.0,127.0&gt;&gt;/B&lt;&lt;687.0,127.0&gt;-&lt;690.0,152.0&gt;-&lt;696.0,184.5&gt;&gt; = 13.967789761532726

* uni1B30.td: B&lt;&lt;758.0,493.5&gt;-&lt;796.0,465.0&gt;-&lt;821.0,414.0&gt;&gt;/L&lt;&lt;821.0,414.0&gt;--&lt;820.0,416.0&gt;&gt; = 0.45113854678600357
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Vute (Latn, 21,000 speakers), Sar (Latn, 500,000 speakers), Dan (Latn, 1,099,244 speakers), Dutch (Latn, 31,709,104 speakers), South Central Banda (Latn, 244,000 speakers), Aghem (Latn, 38,843 speakers), Kom (Latn, 360,685 speakers), Avokaya (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Makaa (Latn, 221,000 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Bete-Bendi (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Gulay (Latn, 250,478 speakers), Navajo (Latn, 166,319 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Fur (Latn, 1,230,163 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Koonzime (Latn, 40,000 speakers), Yala (Latn, 200,000 speakers).</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, malayalam, canadian-aboriginal, old-permic, syriac, tai-le, math, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>balinese</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



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

<details><summary>[14] NotoSansBalinese-Medium.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1381, but got 1363 instead</p>
 [code: ascent]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* uni1B1D (U+1B1D): X=322.0,Y=1.0 (should be at baseline 0?)

* uni1B45 (U+1B45): X=597.0,Y=-2.0 (should be at baseline 0?)

* uni1B48 (U+1B48): X=323.0,Y=2.0 (should be at baseline 0?)

* uni1B5A (U+1B5A): X=134.0,Y=1.0 (should be at baseline 0?)

* uni1B63 (U+1B63): X=163.0,Y=1.5 (should be at baseline 0?)

* uni1B7D (U+1B7D): X=684.0,Y=-0.5 (should be at baseline 0?)

* uni1B341B36: X=-714.0,Y=702.0 (should be at cap-height 700?)

* uni1B341B36: X=-574.5,Y=702.0 (should be at cap-height 700?)

* uni1B341B361B03: X=-755.0,Y=698.0 (should be at cap-height 700?)

* uni1B341B361B03: X=-755.0,Y=698.0 (should be at cap-height 700?)

* uni1B361B00: X=-438.0,Y=699.5 (should be at cap-height 700?)

* uni1B371B00: X=-438.0,Y=699.5 (should be at cap-height 700?)

* uni1B371B03: X=-699.0,Y=698.0 (should be at cap-height 700?)

* uni1B371B03: X=-699.0,Y=698.0 (should be at cap-height 700?)

* uni1B371B03: X=-485.0,Y=699.0 (should be at cap-height 700?)

* uni1B23.conj: X=-160.0,Y=1.0 (should be at baseline 0?)

* uni1B23.conj: X=-60.0,Y=1.0 (should be at baseline 0?)

* uni1B2F.conj.1: X=-160.0,Y=1.0 (should be at baseline 0?)

* uni1B2F.conj.1: X=-60.0,Y=1.0 (should be at baseline 0?)

* uni1B1D.td: X=340.0,Y=1.0 (should be at baseline 0?)

* uni1B45.td: X=590.0,Y=1.0 (should be at baseline 0?)

* uni1B47.td: X=484.0,Y=-1.0 (should be at baseline 0?)

* uni1B1D.ra: X=590.0,Y=1.0 (should be at baseline 0?)

* uni1B45.ra: X=849.0,Y=1.0 (should be at baseline 0?)

* uni1B48.ra: X=592.0,Y=2.0 (should be at baseline 0?)

* uni1E9E (U+1E9E): X=341.0,Y=-1.5 (should be at baseline 0?)

* S (U+0053): X=137.5,Y=-0.5 (should be at baseline 0?)

* Sacute (U+015A): X=137.5,Y=-0.5 (should be at baseline 0?)

* Scaron (U+0160): X=137.5,Y=-0.5 (should be at baseline 0?)

* Scedilla (U+015E): X=137.5,Y=-0.5 (should be at baseline 0?)

* uni0218 (U+0218): X=137.5,Y=-0.5 (should be at baseline 0?)

* a (U+0061): X=188.5,Y=535.5 (should be at x-height 536?)

* abreve (U+0103): X=215.0,Y=698.5 (should be at cap-height 700?)

* abreve (U+0103): X=355.0,Y=699.5 (should be at cap-height 700?)

* ae (U+00E6): X=726.5,Y=-1.0 (should be at baseline 0?)

* at (U+0040): X=553.0,Y=1.0 (should be at baseline 0?)

* breve (U+02D8): X=135.0,Y=698.5 (should be at cap-height 700?)

* breve (U+02D8): X=275.0,Y=699.5 (should be at cap-height 700?)

* uni0306 (U+0306): X=-71.0,Y=698.5 (should be at cap-height 700?)

* uni0306 (U+0306): X=69.0,Y=699.5 (should be at cap-height 700?)

* c (U+0063): X=384.0,Y=-2.0 (should be at baseline 0?)

* cacute (U+0107): X=384.0,Y=-2.0 (should be at baseline 0?)

* ccaron (U+010D): X=384.0,Y=-2.0 (should be at baseline 0?)

* ccedilla (U+00E7): X=384.0,Y=-2.0 (should be at baseline 0?)

* cdotaccent (U+010B): X=384.0,Y=-2.0 (should be at baseline 0?)

* e (U+0065): X=416.0,Y=-1.0 (should be at baseline 0?)

* eacute (U+00E9): X=416.0,Y=-1.0 (should be at baseline 0?)

* ecaron (U+011B): X=416.0,Y=-1.0 (should be at baseline 0?)

* ecircumflex (U+00EA): X=416.0,Y=-1.0 (should be at baseline 0?)

* edieresis (U+00EB): X=416.0,Y=-1.0 (should be at baseline 0?)

* edotaccent (U+0117): X=416.0,Y=-1.0 (should be at baseline 0?)

* egrave (U+00E8): X=416.0,Y=-1.0 (should be at baseline 0?)

* emacron (U+0113): X=416.0,Y=-1.0 (should be at baseline 0?)

* Euro (U+20AC): X=470.5,Y=-1.5 (should be at baseline 0?)

* gbreve (U+011F): X=230.0,Y=698.5 (should be at cap-height 700?)

* gbreve (U+011F): X=370.0,Y=699.5 (should be at cap-height 700?)

* germandbls (U+00DF): X=334.0,Y=-1.5 (should be at baseline 0?)

* nine (U+0039): X=95.0,Y=-1.0 (should be at baseline 0?)

* oe (U+0153): X=799.5,Y=-1.0 (should be at baseline 0?)

* questiondown (U+00BF): X=127.0,Y=1.0 (should be at baseline 0?)

* questiondown (U+00BF): X=27.0,Y=-2.0 (should be at baseline 0?)

* s (U+0073): X=125.0,Y=-1.5 (should be at baseline 0?)

* sacute (U+015B): X=125.0,Y=-1.5 (should be at baseline 0?)

* scaron (U+0161): X=125.0,Y=-1.5 (should be at baseline 0?)

* scedilla (U+015F): X=125.0,Y=-1.5 (should be at baseline 0?)

* uni0219 (U+0219): X=125.0,Y=-1.5 (should be at baseline 0?)

* six (U+0036): X=243.5,Y=699.5 (should be at cap-height 700?)

* three (U+0033): X=136.0,Y=-1.0 (should be at baseline 0?)

* w (U+0077): X=280.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=160.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=647.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=524.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=280.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=160.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=647.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=524.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=280.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=160.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=647.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=524.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=280.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=160.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=647.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=524.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=280.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=160.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=647.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=524.0,Y=1.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uni1B16 (U+1B16): L&lt;&lt;996.0,-10.0&gt;--&lt;996.0,-10.0&gt;&gt; -&gt; L&lt;&lt;996.0,-10.0&gt;--&lt;996.0,-10.0&gt;&gt;

* uni1B16.ra: L&lt;&lt;1236.0,-10.0&gt;--&lt;1236.0,-10.0&gt;&gt; -&gt; L&lt;&lt;1236.0,-10.0&gt;--&lt;1236.0,-10.0&gt;&gt;

* uni1B1B.conj.td: L&lt;&lt;299.0,242.0&gt;--&lt;299.0,242.0&gt;&gt; -&gt; L&lt;&lt;299.0,242.0&gt;--&lt;299.0,242.0&gt;&gt;

* uni1B1E (U+1B1E): L&lt;&lt;364.0,0.0&gt;--&lt;364.0,0.0&gt;&gt; -&gt; L&lt;&lt;364.0,0.0&gt;--&lt;364.0,0.0&gt;&gt;

* uni1B1E.ra: L&lt;&lt;618.0,0.0&gt;--&lt;618.0,0.0&gt;&gt; -&gt; L&lt;&lt;618.0,0.0&gt;--&lt;618.0,0.0&gt;&gt;

* uni1B24 (U+1B24): L&lt;&lt;641.0,546.0&gt;--&lt;641.0,546.0&gt;&gt; -&gt; L&lt;&lt;641.0,546.0&gt;--&lt;641.0,546.0&gt;&gt;

* uni1B24.ra: L&lt;&lt;973.0,546.0&gt;--&lt;973.0,546.0&gt;&gt; -&gt; L&lt;&lt;973.0,546.0&gt;--&lt;973.0,546.0&gt;&gt;

* uni1B24.td: L&lt;&lt;627.0,546.0&gt;--&lt;627.0,546.0&gt;&gt; -&gt; L&lt;&lt;627.0,546.0&gt;--&lt;627.0,546.0&gt;&gt;

* uni1B29 (U+1B29): L&lt;&lt;368.0,89.0&gt;--&lt;368.0,89.0&gt;&gt; -&gt; L&lt;&lt;368.0,89.0&gt;--&lt;368.0,89.0&gt;&gt;

* uni1B29 (U+1B29): L&lt;&lt;368.0,89.0&gt;--&lt;368.0,89.0&gt;&gt; -&gt; L&lt;&lt;368.0,89.0&gt;--&lt;414.0,89.0&gt;&gt;

* uni1B29.ra: L&lt;&lt;670.0,89.0&gt;--&lt;670.0,89.0&gt;&gt; -&gt; L&lt;&lt;670.0,89.0&gt;--&lt;671.0,89.0&gt;&gt;

* uni1B29.ra: L&lt;&lt;670.0,89.0&gt;--&lt;671.0,89.0&gt;&gt; -&gt; L&lt;&lt;671.0,89.0&gt;--&lt;716.0,89.0&gt;&gt;

* uni1B2D (U+1B2D): L&lt;&lt;566.0,546.0&gt;--&lt;566.0,546.0&gt;&gt; -&gt; L&lt;&lt;566.0,546.0&gt;--&lt;567.0,546.0&gt;&gt;

* uni1B2D (U+1B2D): L&lt;&lt;566.0,546.0&gt;--&lt;567.0,546.0&gt;&gt; -&gt; L&lt;&lt;567.0,546.0&gt;--&lt;567.0,546.0&gt;&gt;

* uni1B2D (U+1B2D): L&lt;&lt;567.0,546.0&gt;--&lt;567.0,546.0&gt;&gt; -&gt; L&lt;&lt;567.0,546.0&gt;--&lt;567.0,546.0&gt;&gt;

* uni1B2D.ra: L&lt;&lt;833.0,546.0&gt;--&lt;833.0,546.0&gt;&gt; -&gt; L&lt;&lt;833.0,546.0&gt;--&lt;834.0,546.0&gt;&gt;

* uni1B2D.ra: L&lt;&lt;833.0,546.0&gt;--&lt;834.0,546.0&gt;&gt; -&gt; L&lt;&lt;834.0,546.0&gt;--&lt;834.0,546.0&gt;&gt;

* uni1B2D.ra: L&lt;&lt;834.0,546.0&gt;--&lt;834.0,546.0&gt;&gt; -&gt; L&lt;&lt;834.0,546.0&gt;--&lt;834.0,546.0&gt;&gt;

* uni1B2E.td: L&lt;&lt;357.0,0.0&gt;--&lt;357.0,0.0&gt;&gt; -&gt; L&lt;&lt;357.0,0.0&gt;--&lt;357.0,0.0&gt;&gt;

* uni1B31.conj.td: L&lt;&lt;374.0,179.0&gt;--&lt;374.0,185.0&gt;&gt; -&gt; L&lt;&lt;374.0,185.0&gt;--&lt;374.0,244.0&gt;&gt;

* uni1B45.td: L&lt;&lt;992.0,263.0&gt;--&lt;992.0,260.0&gt;&gt; -&gt; L&lt;&lt;992.0,260.0&gt;--&lt;992.0,0.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): B&lt;&lt;476.0,548.5&gt;-&lt;470.0,575.0&gt;-&lt;468.0,587.0&gt;&gt;/B&lt;&lt;468.0,587.0&gt;-&lt;467.0,575.0&gt;-&lt;462.0,548.5&gt;&gt; = 14.22596389875178

* Wacute (U+1E82): B&lt;&lt;476.0,548.5&gt;-&lt;470.0,575.0&gt;-&lt;468.0,587.0&gt;&gt;/B&lt;&lt;468.0,587.0&gt;-&lt;467.0,575.0&gt;-&lt;462.0,548.5&gt;&gt; = 14.22596389875178

* Wcircumflex (U+0174): B&lt;&lt;476.0,548.5&gt;-&lt;470.0,575.0&gt;-&lt;468.0,587.0&gt;&gt;/B&lt;&lt;468.0,587.0&gt;-&lt;467.0,575.0&gt;-&lt;462.0,548.5&gt;&gt; = 14.22596389875178

* Wdieresis (U+1E84): B&lt;&lt;476.0,548.5&gt;-&lt;470.0,575.0&gt;-&lt;468.0,587.0&gt;&gt;/B&lt;&lt;468.0,587.0&gt;-&lt;467.0,575.0&gt;-&lt;462.0,548.5&gt;&gt; = 14.22596389875178

* Wgrave (U+1E80): B&lt;&lt;476.0,548.5&gt;-&lt;470.0,575.0&gt;-&lt;468.0,587.0&gt;&gt;/B&lt;&lt;468.0,587.0&gt;-&lt;467.0,575.0&gt;-&lt;462.0,548.5&gt;&gt; = 14.22596389875178
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* uni1B23.conj.ya.td: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B23.conj.ya.u: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B23.conj.ya.uu: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B23.conj.ya: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B26.conj.ya.td: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B26.conj.ya.u: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B26.conj.ya.uu: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B26.conj.ya: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B2C.conj.2: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B2C.conj.td.2: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B2C.conj.u.2: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B2C.conj.uu.2: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B2F.conj.2: L&lt;&lt;-323.0,-575.0&gt;--&lt;-160.0,-574.0&gt;&gt;

* uni1B2F.conj.ya.td: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B2F.conj.ya.u: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B2F.conj.ya.uu: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B2F.conj.ya: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B49.conj.ya.td: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B49.conj.ya.u: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B49.conj.ya.uu: L&lt;&lt;-115.0,-575.0&gt;--&lt;48.0,-574.0&gt;&gt;

* uni1B49.conj.ya: L&lt;&lt;-118.0,-575.0&gt;--&lt;45.0,-574.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Vute (Latn, 21,000 speakers), Sar (Latn, 500,000 speakers), Dan (Latn, 1,099,244 speakers), Dutch (Latn, 31,709,104 speakers), South Central Banda (Latn, 244,000 speakers), Aghem (Latn, 38,843 speakers), Kom (Latn, 360,685 speakers), Avokaya (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Makaa (Latn, 221,000 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Bete-Bendi (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Gulay (Latn, 250,478 speakers), Navajo (Latn, 166,319 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Fur (Latn, 1,230,163 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Koonzime (Latn, 40,000 speakers), Yala (Latn, 200,000 speakers).</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, malayalam, canadian-aboriginal, old-permic, syriac, tai-le, math, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>balinese</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



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

<details><summary>[13] NotoSansBalinese-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1381, but got 1363 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that texts shape as per expectation <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>qa/shaping_tests/balinese.json: Expected and actual shaping not matching</p>
<ul>
<li>
<p>Shaping did not match: ᬓ᬴᭄ᬔᬃᬓ᬴ᬃ (Issue #12)</p>
<pre><code>Expected: None
Got     : uni1B13=0+1205|uni1B34=0@-388,-40+0|uni1B14.conj=0+0|uni1B03=0+0|uni1B13=5+1205|uni1B341B03=5@-465,-19+0
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -939 2470 2302" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g24" d="M60.0,394.0Q60.0,460.0 97.0,503.0Q134.0,546.0 210.0,546.0Q348.0,546.0 348.0,380.0L348.0,244.0L409.0,244.0L409.0,251.0Q409.0,340.0 439.0,406.0Q469.0,472.0 528.5,509.0Q588.0,546.0 677.0,546.0Q758.0,546.0 809.5,516.5Q861.0,487.0 880.0,442.0L880.0,536.0L993.0,536.0Q1145.0,536.0 1145.0,383.0L1145.0,0.0L1064.0,0.0L1064.0,387.0Q1064.0,466.0 991.0,466.0L949.0,466.0L949.0,0.0L868.0,0.0L868.0,236.0Q868.0,347.0 818.5,410.5Q769.0,474.0 676.0,474.0Q582.0,474.0 534.5,412.5Q487.0,351.0 487.0,235.0Q556.0,225.0 608.0,207.5Q660.0,190.0 689.0,160.5Q718.0,131.0 718.0,84.0Q718.0,38.0 686.5,14.0Q655.0,-10.0 611.0,-10.0Q573.0,-10.0 536.0,8.0Q499.0,26.0 470.0,59.0Q454.0,78.0 438.5,107.5Q423.0,137.0 415.0,179.0L348.0,179.0L348.0,104.0Q348.0,51.0 321.0,20.5Q294.0,-10.0 243.0,-10.0Q189.0,-10.0 160.0,21.5Q131.0,53.0 131.0,101.0Q131.0,160.0 172.0,196.5Q213.0,233.0 271.0,240.0L271.0,384.0Q271.0,431.0 255.5,452.5Q240.0,474.0 207.0,474.0Q171.0,474.0 153.5,451.0Q136.0,428.0 136.0,387.0Q136.0,335.0 160.0,269.0L103.0,242.0Q60.0,324.0 60.0,394.0ZM202.0,102.0Q202.0,86.0 210.5,71.5Q219.0,57.0 239.0,57.0Q271.0,57.0 271.0,98.0L271.0,172.0Q202.0,154.0 202.0,102.0ZM496.0,167.0Q503.0,136.0 521.0,111.0Q539.0,86.0 562.5,71.0Q586.0,56.0 608.0,56.0Q625.0,56.0 634.5,64.5Q644.0,73.0 644.0,86.0Q644.0,111.0 607.5,133.0Q571.0,155.0 496.0,167.0Z"/> <path id="g58" d="M-389.0,832.0Q-389.0,849.0 -376.5,861.0Q-364.0,873.0 -347.0,873.0Q-332.0,873.0 -319.0,861.0Q-306.0,849.0 -306.0,832.0Q-306.0,813.0 -319.0,802.0Q-332.0,791.0 -347.0,791.0Q-364.0,791.0 -376.5,802.5Q-389.0,814.0 -389.0,832.0ZM-455.0,716.0Q-455.0,733.0 -442.5,745.0Q-430.0,757.0 -413.0,757.0Q-398.0,757.0 -385.0,745.0Q-372.0,733.0 -372.0,716.0Q-372.0,697.0 -385.0,686.0Q-398.0,675.0 -413.0,675.0Q-430.0,675.0 -442.5,686.5Q-455.0,698.0 -455.0,716.0ZM-321.0,716.0Q-321.0,733.0 -308.5,745.0Q-296.0,757.0 -279.0,757.0Q-264.0,757.0 -251.0,745.0Q-238.0,733.0 -238.0,716.0Q-238.0,697.0 -251.0,686.0Q-264.0,675.0 -279.0,675.0Q-296.0,675.0 -308.5,686.5Q-321.0,698.0 -321.0,716.0Z"/> <path id="g178" d="M-181.0,-435.0L-181.0,-303.0Q-181.0,-233.0 -219.5,-198.5Q-258.0,-164.0 -323.0,-164.0Q-397.0,-164.0 -438.5,-207.5Q-480.0,-251.0 -487.0,-316.0L-482.0,-316.0Q-417.0,-316.0 -366.0,-327.0Q-315.0,-338.0 -285.5,-365.0Q-256.0,-392.0 -256.0,-441.0Q-256.0,-490.0 -289.0,-518.5Q-322.0,-547.0 -376.0,-547.0Q-419.0,-547.0 -457.0,-528.5Q-495.0,-510.0 -521.5,-473.0Q-548.0,-436.0 -556.0,-381.0L-607.0,-381.0L-607.0,-401.0Q-607.0,-477.0 -640.5,-512.0Q-674.0,-547.0 -727.0,-547.0Q-778.0,-547.0 -809.0,-517.5Q-840.0,-488.0 -840.0,-444.0Q-840.0,-392.0 -798.5,-361.0Q-757.0,-330.0 -686.0,-323.0L-686.0,-246.0Q-686.0,-202.0 -702.0,-182.5Q-718.0,-163.0 -748.0,-163.0Q-776.0,-163.0 -791.5,-181.0Q-807.0,-199.0 -807.0,-229.0Q-807.0,-245.0 -803.5,-260.5Q-800.0,-276.0 -796.0,-287.0L-848.0,-310.0Q-858.0,-291.0 -866.5,-266.5Q-875.0,-242.0 -875.0,-214.0Q-875.0,-155.0 -837.5,-123.5Q-800.0,-92.0 -742.0,-92.0Q-680.0,-92.0 -643.5,-127.5Q-607.0,-163.0 -607.0,-236.0L-607.0,-317.0L-557.0,-317.0Q-551.0,-259.0 -523.0,-207.5Q-495.0,-156.0 -444.5,-124.0Q-394.0,-92.0 -320.0,-92.0Q-261.0,-92.0 -211.0,-115.0Q-161.0,-138.0 -130.5,-183.5Q-100.0,-229.0 -100.0,-297.0L-100.0,-433.0Q-100.0,-475.0 -70.0,-475.0Q-42.0,-475.0 -3.5,-437.5Q35.0,-400.0 82.0,-330.0L137.0,-367.0Q82.0,-456.0 29.5,-501.5Q-23.0,-547.0 -81.0,-547.0Q-126.0,-547.0 -153.5,-519.0Q-181.0,-491.0 -181.0,-435.0ZM-464.0,-383.0L-484.0,-383.0Q-475.0,-430.0 -447.0,-456.5Q-419.0,-483.0 -382.0,-483.0Q-354.0,-483.0 -342.5,-470.5Q-331.0,-458.0 -331.0,-442.0Q-331.0,-417.0 -361.5,-400.0Q-392.0,-383.0 -464.0,-383.0ZM-686.0,-411.0L-686.0,-386.0Q-718.0,-391.0 -744.0,-404.5Q-770.0,-418.0 -770.0,-447.0Q-770.0,-462.0 -760.5,-473.0Q-751.0,-484.0 -732.0,-484.0Q-713.0,-484.0 -699.5,-470.0Q-686.0,-456.0 -686.0,-411.0Z"/> <path id="g8" d="M-15.0,624.0Q-197.0,624.0 -304.0,691.0Q-411.0,759.0 -444.0,895.0L-375.0,925.0Q-343.0,804.0 -257.0,742.0Q-213.0,711.0 -153.5,695.0Q-94.0,679.0 -15.0,679.0L-15.0,624.0Z"/> <path id="g144" d="M-439.0,832.0Q-439.0,849.0 -426.5,861.0Q-414.0,873.0 -397.0,873.0Q-382.0,873.0 -369.0,861.0Q-356.0,849.0 -356.0,832.0Q-356.0,813.0 -369.0,802.0Q-382.0,791.0 -397.0,791.0Q-414.0,791.0 -426.5,802.5Q-439.0,814.0 -439.0,832.0ZM-505.0,716.0Q-505.0,733.0 -492.5,745.0Q-480.0,757.0 -463.0,757.0Q-448.0,757.0 -435.0,745.0Q-422.0,733.0 -422.0,716.0Q-422.0,697.0 -435.0,686.0Q-448.0,675.0 -463.0,675.0Q-480.0,675.0 -492.5,686.5Q-505.0,698.0 -505.0,716.0ZM-371.0,716.0Q-371.0,733.0 -358.5,745.0Q-346.0,757.0 -329.0,757.0Q-314.0,757.0 -301.0,745.0Q-288.0,733.0 -288.0,716.0Q-288.0,697.0 -301.0,686.0Q-314.0,675.0 -329.0,675.0Q-346.0,675.0 -358.5,686.5Q-371.0,698.0 -371.0,716.0ZM-28.0,612.0Q-103.0,616.0 -163.0,656.0Q-223.0,696.0 -262.5,761.0Q-302.0,826.0 -315.0,905.0L-244.0,920.0Q-231.0,818.0 -173.5,752.5Q-116.0,687.0 -22.0,668.0L-28.0,612.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g24"/> </g> <g transform="translate(817,-40)"> <use href="#g58"/> </g> <g transform="translate(1205,0)"> <use href="#g178"/> </g> <g transform="translate(1205,0)"> <use href="#g8"/> </g> <g transform="translate(1205,0)"> <use href="#g24"/> </g> <g transform="translate(1945,-19)"> <use href="#g144"/> </g> </svg></p>
</li>
</ul>
 [code: shaping-regression]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uni1B16 (U+1B16): L&lt;&lt;948.0,-10.0&gt;--&lt;948.0,-10.0&gt;&gt; -&gt; L&lt;&lt;948.0,-10.0&gt;--&lt;948.0,-10.0&gt;&gt;

* uni1B16.ra: L&lt;&lt;1177.0,-10.0&gt;--&lt;1177.0,-10.0&gt;&gt; -&gt; L&lt;&lt;1177.0,-10.0&gt;--&lt;1177.0,-10.0&gt;&gt;

* uni1B1E (U+1B1E): L&lt;&lt;359.0,0.0&gt;--&lt;359.0,0.0&gt;&gt; -&gt; L&lt;&lt;359.0,0.0&gt;--&lt;359.0,0.0&gt;&gt;

* uni1B1E.ra: L&lt;&lt;596.0,0.0&gt;--&lt;596.0,0.0&gt;&gt; -&gt; L&lt;&lt;596.0,0.0&gt;--&lt;596.0,0.0&gt;&gt;

* uni1B2D (U+1B2D): L&lt;&lt;558.0,546.0&gt;--&lt;558.0,546.0&gt;&gt; -&gt; L&lt;&lt;558.0,546.0&gt;--&lt;558.0,546.0&gt;&gt;

* uni1B2D (U+1B2D): L&lt;&lt;558.0,546.0&gt;--&lt;558.0,546.0&gt;&gt; -&gt; L&lt;&lt;558.0,546.0&gt;--&lt;559.0,546.0&gt;&gt;

* uni1B2D (U+1B2D): L&lt;&lt;558.0,546.0&gt;--&lt;559.0,546.0&gt;&gt; -&gt; L&lt;&lt;559.0,546.0&gt;--&lt;559.0,546.0&gt;&gt;

* uni1B2D.ra: L&lt;&lt;795.0,546.0&gt;--&lt;795.0,546.0&gt;&gt; -&gt; L&lt;&lt;795.0,546.0&gt;--&lt;795.0,546.0&gt;&gt;

* uni1B2D.ra: L&lt;&lt;795.0,546.0&gt;--&lt;795.0,546.0&gt;&gt; -&gt; L&lt;&lt;795.0,546.0&gt;--&lt;796.0,546.0&gt;&gt;

* uni1B2D.ra: L&lt;&lt;795.0,546.0&gt;--&lt;796.0,546.0&gt;&gt; -&gt; L&lt;&lt;796.0,546.0&gt;--&lt;796.0,546.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni1B18 (U+1B18): L&lt;&lt;597.0,-10.0&gt;--&lt;597.0,-10.0&gt;&gt;/B&lt;&lt;597.0,-10.0&gt;-&lt;544.0,-9.0&gt;-&lt;500.0,22.0&gt;&gt; = 1.080924186660573

* uni1B18.ra: L&lt;&lt;865.0,-10.0&gt;--&lt;865.0,-10.0&gt;&gt;/B&lt;&lt;865.0,-10.0&gt;-&lt;812.0,-9.0&gt;-&lt;768.0,22.0&gt;&gt; = 1.080924186660573

* uni1B3A.3: B&lt;&lt;-34.5,-784.0&gt;-&lt;-75.0,-817.0&gt;-&lt;-149.0,-826.0&gt;&gt;/L&lt;&lt;-149.0,-826.0&gt;--&lt;-149.0,-826.0&gt;&gt; = 6.934348901269559

* uni1B3A.3: L&lt;&lt;-149.0,-826.0&gt;--&lt;-149.0,-826.0&gt;&gt;/B&lt;&lt;-149.0,-826.0&gt;-&lt;-175.0,-829.0&gt;-&lt;-203.0,-829.0&gt;&gt; = 6.581944655178027

* uni1B3A.5: B&lt;&lt;-34.5,-784.0&gt;-&lt;-75.0,-817.0&gt;-&lt;-149.0,-826.0&gt;&gt;/L&lt;&lt;-149.0,-826.0&gt;--&lt;-149.0,-826.0&gt;&gt; = 6.934348901269559

* uni1B3A.5: L&lt;&lt;-149.0,-826.0&gt;--&lt;-149.0,-826.0&gt;&gt;/B&lt;&lt;-149.0,-826.0&gt;-&lt;-175.0,-829.0&gt;-&lt;-203.0,-829.0&gt;&gt; = 6.581944655178027
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Vute (Latn, 21,000 speakers), Sar (Latn, 500,000 speakers), Dan (Latn, 1,099,244 speakers), Dutch (Latn, 31,709,104 speakers), South Central Banda (Latn, 244,000 speakers), Aghem (Latn, 38,843 speakers), Kom (Latn, 360,685 speakers), Avokaya (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Makaa (Latn, 221,000 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Bete-Bendi (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Gulay (Latn, 250,478 speakers), Navajo (Latn, 166,319 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Fur (Latn, 1,230,163 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Koonzime (Latn, 40,000 speakers), Yala (Latn, 200,000 speakers).</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, malayalam, canadian-aboriginal, old-permic, syriac, tai-le, math, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>balinese</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



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

<details><summary>[13] NotoSansBalinese-Bold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1381, but got 1363 instead</p>
 [code: ascent]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* uni1B14 (U+1B14): X=1089.0,Y=-1.0 (should be at baseline 0?)

* uni1B1D (U+1B1D): X=576.0,Y=1.0 (should be at baseline 0?)

* uni1B1D (U+1B1D): X=296.0,Y=2.0 (should be at baseline 0?)

* uni1B1F (U+1B1F): X=410.5,Y=1.0 (should be at baseline 0?)

* uni1B2F (U+1B2F): X=493.5,Y=0.5 (should be at baseline 0?)

* uni1B48 (U+1B48): X=325.0,Y=2.0 (should be at baseline 0?)

* uni1B57 (U+1B57): X=964.0,Y=701.0 (should be at cap-height 700?)

* uni1B63 (U+1B63): X=79.5,Y=2.0 (should be at baseline 0?)

* uni1B361B00: X=-229.0,Y=698.5 (should be at cap-height 700?)

* uni1B361B00: X=-321.0,Y=699.0 (should be at cap-height 700?)

* uni1B361B03: X=-555.0,Y=698.0 (should be at cap-height 700?)

* uni1B371B00: X=-229.0,Y=698.5 (should be at cap-height 700?)

* uni1B371B00: X=-321.0,Y=699.0 (should be at cap-height 700?)

* uni1B371B00: X=-251.0,Y=701.0 (should be at cap-height 700?)

* uni1B23.conj: X=-197.0,Y=1.0 (should be at baseline 0?)

* uni1B23.conj: X=-60.0,Y=1.0 (should be at baseline 0?)

* uni1B2F.conj.1: X=-197.0,Y=1.0 (should be at baseline 0?)

* uni1B2F.conj.1: X=-60.0,Y=1.0 (should be at baseline 0?)

* uni1B19.td: X=701.0,Y=1.0 (should be at baseline 0?)

* uni1B1D.td: X=631.0,Y=2.0 (should be at baseline 0?)

* uni1B1D.td: X=355.0,Y=2.0 (should be at baseline 0?)

* uni1B22.td: X=487.5,Y=0.5 (should be at baseline 0?)

* uni1B2E.td: X=406.0,Y=1.0 (should be at baseline 0?)

* uni1B2F.td: X=542.5,Y=0.5 (should be at baseline 0?)

* uni1B49.td: X=486.0,Y=-1.0 (should be at baseline 0?)

* uni1B14.ra: X=1384.0,Y=-1.0 (should be at baseline 0?)

* uni1B1B.ra: X=1061.0,Y=-1.0 (should be at baseline 0?)

* uni1B1D.ra: X=883.0,Y=1.0 (should be at baseline 0?)

* uni1B1D.ra: X=603.0,Y=2.0 (should be at baseline 0?)

* uni1B1F.ra: X=704.5,Y=1.0 (should be at baseline 0?)

* uni1B2F.ra: X=808.5,Y=0.5 (should be at baseline 0?)

* uni1B48.ra: X=665.0,Y=2.0 (should be at baseline 0?)

* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

* Cacute (U+0106): X=482.0,Y=-1.0 (should be at baseline 0?)

* Ccaron (U+010C): X=482.0,Y=-1.0 (should be at baseline 0?)

* Ccedilla (U+00C7): X=482.0,Y=-1.0 (should be at baseline 0?)

* Cdotaccent (U+010A): X=482.0,Y=-1.0 (should be at baseline 0?)

* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

* Gbreve (U+011E): X=527.5,Y=1.0 (should be at baseline 0?)

* uni0122 (U+0122): X=527.5,Y=1.0 (should be at baseline 0?)

* Gdotaccent (U+0120): X=527.5,Y=1.0 (should be at baseline 0?)

* uni1E9E (U+1E9E): X=371.5,Y=-1.0 (should be at baseline 0?)

* Oslash (U+00D8): X=686.0,Y=701.0 (should be at cap-height 700?)

* ae (U+00E6): X=758.0,Y=-0.5 (should be at baseline 0?)

* ae (U+00E6): X=311.0,Y=0.5 (should be at baseline 0?)

* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?)

* cacute (U+0107): X=394.5,Y=-0.5 (should be at baseline 0?)

* ccaron (U+010D): X=394.5,Y=-0.5 (should be at baseline 0?)

* ccedilla (U+00E7): X=394.5,Y=-0.5 (should be at baseline 0?)

* cdotaccent (U+010B): X=394.5,Y=-0.5 (should be at baseline 0?)

* degree (U+00B0): X=123.5,Y=702.0 (should be at cap-height 700?)

* e (U+0065): X=432.5,Y=-0.5 (should be at baseline 0?)

* eacute (U+00E9): X=432.5,Y=-0.5 (should be at baseline 0?)

* ecaron (U+011B): X=432.5,Y=-0.5 (should be at baseline 0?)

* ecircumflex (U+00EA): X=432.5,Y=-0.5 (should be at baseline 0?)

* edieresis (U+00EB): X=432.5,Y=-0.5 (should be at baseline 0?)

* edotaccent (U+0117): X=432.5,Y=-0.5 (should be at baseline 0?)

* egrave (U+00E8): X=432.5,Y=-0.5 (should be at baseline 0?)

* emacron (U+0113): X=432.5,Y=-0.5 (should be at baseline 0?)

* g (U+0067): X=555.0,Y=-1.0 (should be at baseline 0?)

* gbreve (U+011F): X=555.0,Y=-1.0 (should be at baseline 0?)

* uni0123 (U+0123): X=555.0,Y=-1.0 (should be at baseline 0?)

* gdotaccent (U+0121): X=555.0,Y=-1.0 (should be at baseline 0?)

* h (U+0068): X=295.0,Y=537.0 (should be at x-height 536?)

* m (U+006D): X=288.5,Y=537.0 (should be at x-height 536?)

* m (U+006D): X=481.0,Y=536.5 (should be at x-height 536?)

* m (U+006D): X=627.5,Y=537.0 (should be at x-height 536?)

* n (U+006E): X=291.5,Y=537.0 (should be at x-height 536?)

* oe (U+0153): X=816.5,Y=-0.5 (should be at baseline 0?)

* questiondown (U+00BF): X=22.0,Y=-1.0 (should be at baseline 0?)

* six (U+0036): X=241.5,Y=698.5 (should be at cap-height 700?)

* two (U+0032): X=413.5,Y=698.5 (should be at cap-height 700?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uni1B15.td: L&lt;&lt;913.0,259.0&gt;--&lt;913.0,250.0&gt;&gt; -&gt; L&lt;&lt;913.0,250.0&gt;--&lt;913.0,0.0&gt;&gt;

* uni1B1B.conj.td: L&lt;&lt;358.0,217.0&gt;--&lt;358.0,217.0&gt;&gt; -&gt; L&lt;&lt;358.0,217.0&gt;--&lt;358.0,217.0&gt;&gt;

* uni1B21.td: L&lt;&lt;884.0,242.0&gt;--&lt;884.0,241.0&gt;&gt; -&gt; L&lt;&lt;884.0,241.0&gt;--&lt;884.0,0.0&gt;&gt;

* uni1B22 (U+1B22): L&lt;&lt;374.0,0.0&gt;--&lt;374.0,0.0&gt;&gt; -&gt; L&lt;&lt;374.0,0.0&gt;--&lt;374.0,0.0&gt;&gt;

* uni1B22.ra: L&lt;&lt;693.0,0.0&gt;--&lt;693.0,0.0&gt;&gt; -&gt; L&lt;&lt;693.0,0.0&gt;--&lt;693.0,0.0&gt;&gt;

* uni1B24 (U+1B24): L&lt;&lt;662.0,546.0&gt;--&lt;662.0,546.0&gt;&gt; -&gt; L&lt;&lt;662.0,546.0&gt;--&lt;662.0,546.0&gt;&gt;

* uni1B24.ra: L&lt;&lt;1034.0,546.0&gt;--&lt;1034.0,546.0&gt;&gt; -&gt; L&lt;&lt;1034.0,546.0&gt;--&lt;1034.0,546.0&gt;&gt;

* uni1B24.td: L&lt;&lt;662.0,546.0&gt;--&lt;662.0,546.0&gt;&gt; -&gt; L&lt;&lt;662.0,546.0&gt;--&lt;662.0,546.0&gt;&gt;

* uni1B2E.td: L&lt;&lt;404.0,0.0&gt;--&lt;404.0,0.0&gt;&gt; -&gt; L&lt;&lt;404.0,0.0&gt;--&lt;404.0,0.0&gt;&gt;

* uni1B30.td: L&lt;&lt;887.0,259.0&gt;--&lt;887.0,250.0&gt;&gt; -&gt; L&lt;&lt;887.0,250.0&gt;--&lt;887.0,0.0&gt;&gt;

* uni1B47 (U+1B47): L&lt;&lt;374.0,0.0&gt;--&lt;373.0,0.0&gt;&gt; -&gt; L&lt;&lt;373.0,0.0&gt;--&lt;372.0,0.0&gt;&gt;

* uni1B47.ra: L&lt;&lt;664.0,0.0&gt;--&lt;663.0,0.0&gt;&gt; -&gt; L&lt;&lt;663.0,0.0&gt;--&lt;662.0,0.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* W (U+0057): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* W (U+0057): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726

* Wacute (U+1E82): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* Wacute (U+1E82): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* Wacute (U+1E82): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726

* Wcircumflex (U+0174): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* Wcircumflex (U+0174): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* Wcircumflex (U+0174): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726

* Wdieresis (U+1E84): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* Wdieresis (U+1E84): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* Wdieresis (U+1E84): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726

* Wgrave (U+1E80): B&lt;&lt;266.0,196.0&gt;-&lt;272.0,161.0&gt;-&lt;275.0,137.0&gt;&gt;/B&lt;&lt;275.0,137.0&gt;-&lt;278.0,162.0&gt;-&lt;284.0,196.5&gt;&gt; = 13.967789761532726

* Wgrave (U+1E80): B&lt;&lt;489.0,505.5&gt;-&lt;485.0,529.0&gt;-&lt;483.0,542.0&gt;&gt;/B&lt;&lt;483.0,542.0&gt;-&lt;482.0,529.0&gt;-&lt;477.5,505.5&gt;&gt; = 13.144867617550734

* Wgrave (U+1E80): B&lt;&lt;683.0,196.0&gt;-&lt;689.0,161.0&gt;-&lt;692.0,137.0&gt;&gt;/B&lt;&lt;692.0,137.0&gt;-&lt;695.0,162.0&gt;-&lt;701.0,196.5&gt;&gt; = 13.967789761532726

* uni1B2E.td: L&lt;&lt;404.0,0.0&gt;--&lt;404.0,0.0&gt;&gt;/B&lt;&lt;404.0,0.0&gt;-&lt;173.0,1.0&gt;-&lt;173.0,190.0&gt;&gt; = 0.24803212815535178
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Vute (Latn, 21,000 speakers), Sar (Latn, 500,000 speakers), Dan (Latn, 1,099,244 speakers), Dutch (Latn, 31,709,104 speakers), South Central Banda (Latn, 244,000 speakers), Aghem (Latn, 38,843 speakers), Kom (Latn, 360,685 speakers), Avokaya (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Makaa (Latn, 221,000 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Bete-Bendi (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Gulay (Latn, 250,478 speakers), Navajo (Latn, 166,319 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Fur (Latn, 1,230,163 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Koonzime (Latn, 40,000 speakers), Yala (Latn, 200,000 speakers).</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, malayalam, canadian-aboriginal, old-permic, syriac, tai-le, math, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>balinese</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



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
| 0 | 0 | 13 | 43 | 458 | 21 | 415 | 0 | 
| 0% | 0% | 1% | 5% | 48% | 2% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
