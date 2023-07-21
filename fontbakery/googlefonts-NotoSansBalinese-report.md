## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansBalinese/googlefonts/ttf', 'fonts/NotoSansBalinese/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Sans Balinese' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[12] NotoSansBalinese-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1381, but got 1363 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1B05
	* uni1B0D
	* uni1B0E
	* uni1B0E.conj
	* uni1B11
	* uni1B12
	* uni1B13
	* uni1B13.conj
	* uni1B13.ra
	* uni1B13.ra_uni1B2D.conj.wa and 119 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _128

	- cereg2

	- cereg3

	- cereg5

	- nonmarkingreturn

	- uni1B1A.2.nya

	- uni1B3A.5 

	- uni1B3E001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni1B3C (U+1B3C) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=413.5,Y=698.5 (should be at cap-height 700?)

	* six (U+0036): X=241.5,Y=698.5 (should be at cap-height 700?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

	* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?)

	* e (U+0065): X=432.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=555.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=295.0,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=288.5,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=481.0,Y=536.5 (should be at x-height 536?) 

	* 39 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni1B22 (U+1B22): L<<374.0,0.0>--<374.0,0.0>> -> L<<374.0,0.0>--<374.0,0.0>>

	* uni1B24 (U+1B24): L<<662.0,546.0>--<662.0,546.0>> -> L<<662.0,546.0>--<662.0,546.0>> 

	* uni1B47 (U+1B47): L<<374.0,0.0>--<373.0,0.0>> -> L<<373.0,0.0>--<372.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726 

	* 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansBalinese-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1381, but got 1363 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1B05
	* uni1B0E.conj
	* uni1B10
	* uni1B13
	* uni1B13.conj
	* uni1B13.ra
	* uni1B13.ra_uni1B2D.conj.wa
	* uni1B13.td
	* uni1B14
	* uni1B14.conj and 58 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Balinese Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _128

	- cereg2

	- cereg3

	- cereg5

	- nonmarkingreturn

	- uni1B1A.2.nya

	- uni1B3A.5 

	- uni1B3E001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni1B3C (U+1B3C) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=136.0,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=243.5,Y=699.5 (should be at cap-height 700?)

	* nine (U+0039): X=95.0,Y=-1.0 (should be at baseline 0?)

	* at (U+0040): X=553.0,Y=1.0 (should be at baseline 0?)

	* S (U+0053): X=137.5,Y=-0.5 (should be at baseline 0?)

	* a (U+0061): X=188.5,Y=535.5 (should be at x-height 536?)

	* c (U+0063): X=384.0,Y=-2.0 (should be at baseline 0?)

	* e (U+0065): X=416.0,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=124.5,Y=-1.5 (should be at baseline 0?)

	* w (U+0077): X=280.0,Y=1.0 (should be at baseline 0?) 

	* 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni1B16 (U+1B16): L<<996.0,-10.0>--<996.0,-10.0>> -> L<<996.0,-10.0>--<996.0,-10.0>>

	* uni1B1E (U+1B1E): L<<364.0,0.0>--<364.0,0.0>> -> L<<364.0,0.0>--<364.0,0.0>>

	* uni1B24 (U+1B24): L<<641.0,546.0>--<641.0,546.0>> -> L<<641.0,546.0>--<641.0,546.0>>

	* uni1B29 (U+1B29): L<<368.0,89.0>--<368.0,89.0>> -> L<<368.0,89.0>--<368.0,89.0>>

	* uni1B29 (U+1B29): L<<368.0,89.0>--<368.0,89.0>> -> L<<368.0,89.0>--<414.0,89.0>>

	* uni1B2D (U+1B2D): L<<566.0,546.0>--<566.0,546.0>> -> L<<566.0,546.0>--<567.0,546.0>>

	* uni1B2D (U+1B2D): L<<566.0,546.0>--<567.0,546.0>> -> L<<567.0,546.0>--<567.0,546.0>> 

	* uni1B2D (U+1B2D): L<<567.0,546.0>--<567.0,546.0>> -> L<<567.0,546.0>--<567.0,546.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178

	* Wacute (U+1E82): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178

	* Wcircumflex (U+0174): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178

	* Wdieresis (U+1E84): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178 

	* Wgrave (U+1E80): B<<476.0,548.5>-<470.0,575.0>-<468.0,587.0>>/B<<468.0,587.0>-<467.0,575.0>-<462.0,548.5>> = 14.22596389875178 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansBalinese-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1381, but got 1363 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/balinese.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansBalinese/googlefonts/ttf/NotoSansBalinese-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/balinese.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ᬓ᬴᭄ᬔᬃᬓ᬴ᬃ</span> (Issue #12)</li>


<pre>Expected: uni1B13=0+1205|uni1B34_uni1B03=0@-465,-19+0|uni1B14.conj=0+0|uni1B13=5+1205|uni1B34_uni1B03=5@-465,-19+0</pre>



<pre>Got     : uni1B13=0+1205|uni1B34=0@-388,-40+0|uni1B14.conj=0+0|uni1B03=0+0|uni1B13=5+1205|uni1B34_uni1B03=5@-465,-19+0</pre>



<pre>                                ++++++++    ^^^  ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2410 3201" transform="matrix(1 0 0 -1 0 0)">
<path d="M60.0,394.0Q60.0,460.0 97.0,503.0Q134.0,546.0 210.0,546.0Q348.0,546.0 348.0,380.0L348.0,244.0L409.0,244.0L409.0,251.0Q409.0,340.0 439.0,406.0Q469.0,472.0 528.5,509.0Q588.0,546.0 677.0,546.0Q758.0,546.0 809.5,516.5Q861.0,487.0 880.0,442.0L880.0,536.0L993.0,536.0Q1145.0,536.0 1145.0,383.0L1145.0,0.0L1064.0,0.0L1064.0,387.0Q1064.0,466.0 991.0,466.0L949.0,466.0L949.0,0.0L868.0,0.0L868.0,236.0Q868.0,347.0 818.5,410.5Q769.0,474.0 676.0,474.0Q582.0,474.0 534.5,412.5Q487.0,351.0 487.0,235.0Q556.0,225.0 608.0,207.5Q660.0,190.0 689.0,160.5Q718.0,131.0 718.0,84.0Q718.0,38.0 686.5,14.0Q655.0,-10.0 611.0,-10.0Q573.0,-10.0 536.0,8.0Q499.0,26.0 470.0,59.0Q454.0,78.0 438.5,107.5Q423.0,137.0 415.0,179.0L348.0,179.0L348.0,104.0Q348.0,51.0 321.0,20.5Q294.0,-10.0 243.0,-10.0Q189.0,-10.0 160.0,21.5Q131.0,53.0 131.0,101.0Q131.0,160.0 172.0,196.5Q213.0,233.0 271.0,240.0L271.0,384.0Q271.0,431.0 255.5,452.5Q240.0,474.0 207.0,474.0Q171.0,474.0 153.5,451.0Q136.0,428.0 136.0,387.0Q136.0,335.0 160.0,269.0L103.0,242.0Q60.0,324.0 60.0,394.0ZM202.0,102.0Q202.0,86.0 210.5,71.5Q219.0,57.0 239.0,57.0Q271.0,57.0 271.0,98.0L271.0,172.0Q202.0,154.0 202.0,102.0ZM496.0,167.0Q503.0,136.0 521.0,111.0Q539.0,86.0 562.5,71.0Q586.0,56.0 608.0,56.0Q625.0,56.0 634.5,64.5Q644.0,73.0 644.0,86.0Q644.0,111.0 607.5,133.0Q571.0,155.0 496.0,167.0Z" transform="translate(0, 1338)"/>
<path d="M-389.0,832.0Q-389.0,849.0 -376.5,861.0Q-364.0,873.0 -347.0,873.0Q-332.0,873.0 -319.0,861.0Q-306.0,849.0 -306.0,832.0Q-306.0,813.0 -319.0,802.0Q-332.0,791.0 -347.0,791.0Q-364.0,791.0 -376.5,802.5Q-389.0,814.0 -389.0,832.0ZM-455.0,716.0Q-455.0,733.0 -442.5,745.0Q-430.0,757.0 -413.0,757.0Q-398.0,757.0 -385.0,745.0Q-372.0,733.0 -372.0,716.0Q-372.0,697.0 -385.0,686.0Q-398.0,675.0 -413.0,675.0Q-430.0,675.0 -442.5,686.5Q-455.0,698.0 -455.0,716.0ZM-321.0,716.0Q-321.0,733.0 -308.5,745.0Q-296.0,757.0 -279.0,757.0Q-264.0,757.0 -251.0,745.0Q-238.0,733.0 -238.0,716.0Q-238.0,697.0 -251.0,686.0Q-264.0,675.0 -279.0,675.0Q-296.0,675.0 -308.5,686.5Q-321.0,698.0 -321.0,716.0Z" transform="translate(817, 1298)"/>
<path d="M-181.0,-435.0L-181.0,-303.0Q-181.0,-233.0 -219.5,-198.5Q-258.0,-164.0 -323.0,-164.0Q-397.0,-164.0 -438.5,-207.5Q-480.0,-251.0 -487.0,-316.0L-482.0,-316.0Q-417.0,-316.0 -366.0,-327.0Q-315.0,-338.0 -285.5,-365.0Q-256.0,-392.0 -256.0,-441.0Q-256.0,-490.0 -289.0,-518.5Q-322.0,-547.0 -376.0,-547.0Q-419.0,-547.0 -457.0,-528.5Q-495.0,-510.0 -521.5,-473.0Q-548.0,-436.0 -556.0,-381.0L-607.0,-381.0L-607.0,-401.0Q-607.0,-477.0 -640.5,-512.0Q-674.0,-547.0 -727.0,-547.0Q-778.0,-547.0 -809.0,-517.5Q-840.0,-488.0 -840.0,-444.0Q-840.0,-392.0 -798.5,-361.0Q-757.0,-330.0 -686.0,-323.0L-686.0,-246.0Q-686.0,-202.0 -702.0,-182.5Q-718.0,-163.0 -748.0,-163.0Q-776.0,-163.0 -791.5,-181.0Q-807.0,-199.0 -807.0,-229.0Q-807.0,-245.0 -803.5,-260.5Q-800.0,-276.0 -796.0,-287.0L-848.0,-310.0Q-858.0,-291.0 -866.5,-266.5Q-875.0,-242.0 -875.0,-214.0Q-875.0,-155.0 -837.5,-123.5Q-800.0,-92.0 -742.0,-92.0Q-680.0,-92.0 -643.5,-127.5Q-607.0,-163.0 -607.0,-236.0L-607.0,-317.0L-557.0,-317.0Q-551.0,-259.0 -523.0,-207.5Q-495.0,-156.0 -444.5,-124.0Q-394.0,-92.0 -320.0,-92.0Q-261.0,-92.0 -211.0,-115.0Q-161.0,-138.0 -130.5,-183.5Q-100.0,-229.0 -100.0,-297.0L-100.0,-433.0Q-100.0,-475.0 -70.0,-475.0Q-42.0,-475.0 -3.5,-437.5Q35.0,-400.0 82.0,-330.0L137.0,-367.0Q82.0,-456.0 29.5,-501.5Q-23.0,-547.0 -81.0,-547.0Q-126.0,-547.0 -153.5,-519.0Q-181.0,-491.0 -181.0,-435.0ZM-464.0,-383.0L-484.0,-383.0Q-475.0,-430.0 -447.0,-456.5Q-419.0,-483.0 -382.0,-483.0Q-354.0,-483.0 -342.5,-470.5Q-331.0,-458.0 -331.0,-442.0Q-331.0,-417.0 -361.5,-400.0Q-392.0,-383.0 -464.0,-383.0ZM-686.0,-411.0L-686.0,-386.0Q-718.0,-391.0 -744.0,-404.5Q-770.0,-418.0 -770.0,-447.0Q-770.0,-462.0 -760.5,-473.0Q-751.0,-484.0 -732.0,-484.0Q-713.0,-484.0 -699.5,-470.0Q-686.0,-456.0 -686.0,-411.0Z" transform="translate(1205, 1338)"/>
<path d="M-15.0,624.0Q-197.0,624.0 -304.0,691.0Q-411.0,759.0 -444.0,895.0L-375.0,925.0Q-343.0,804.0 -257.0,742.0Q-213.0,711.0 -153.5,695.0Q-94.0,679.0 -15.0,679.0L-15.0,624.0Z" transform="translate(1205, 1338)"/>
<path d="M60.0,394.0Q60.0,460.0 97.0,503.0Q134.0,546.0 210.0,546.0Q348.0,546.0 348.0,380.0L348.0,244.0L409.0,244.0L409.0,251.0Q409.0,340.0 439.0,406.0Q469.0,472.0 528.5,509.0Q588.0,546.0 677.0,546.0Q758.0,546.0 809.5,516.5Q861.0,487.0 880.0,442.0L880.0,536.0L993.0,536.0Q1145.0,536.0 1145.0,383.0L1145.0,0.0L1064.0,0.0L1064.0,387.0Q1064.0,466.0 991.0,466.0L949.0,466.0L949.0,0.0L868.0,0.0L868.0,236.0Q868.0,347.0 818.5,410.5Q769.0,474.0 676.0,474.0Q582.0,474.0 534.5,412.5Q487.0,351.0 487.0,235.0Q556.0,225.0 608.0,207.5Q660.0,190.0 689.0,160.5Q718.0,131.0 718.0,84.0Q718.0,38.0 686.5,14.0Q655.0,-10.0 611.0,-10.0Q573.0,-10.0 536.0,8.0Q499.0,26.0 470.0,59.0Q454.0,78.0 438.5,107.5Q423.0,137.0 415.0,179.0L348.0,179.0L348.0,104.0Q348.0,51.0 321.0,20.5Q294.0,-10.0 243.0,-10.0Q189.0,-10.0 160.0,21.5Q131.0,53.0 131.0,101.0Q131.0,160.0 172.0,196.5Q213.0,233.0 271.0,240.0L271.0,384.0Q271.0,431.0 255.5,452.5Q240.0,474.0 207.0,474.0Q171.0,474.0 153.5,451.0Q136.0,428.0 136.0,387.0Q136.0,335.0 160.0,269.0L103.0,242.0Q60.0,324.0 60.0,394.0ZM202.0,102.0Q202.0,86.0 210.5,71.5Q219.0,57.0 239.0,57.0Q271.0,57.0 271.0,98.0L271.0,172.0Q202.0,154.0 202.0,102.0ZM496.0,167.0Q503.0,136.0 521.0,111.0Q539.0,86.0 562.5,71.0Q586.0,56.0 608.0,56.0Q625.0,56.0 634.5,64.5Q644.0,73.0 644.0,86.0Q644.0,111.0 607.5,133.0Q571.0,155.0 496.0,167.0Z" transform="translate(1205, 1338)"/>
<path d="M-439.0,832.0Q-439.0,849.0 -426.5,861.0Q-414.0,873.0 -397.0,873.0Q-382.0,873.0 -369.0,861.0Q-356.0,849.0 -356.0,832.0Q-356.0,813.0 -369.0,802.0Q-382.0,791.0 -397.0,791.0Q-414.0,791.0 -426.5,802.5Q-439.0,814.0 -439.0,832.0ZM-505.0,716.0Q-505.0,733.0 -492.5,745.0Q-480.0,757.0 -463.0,757.0Q-448.0,757.0 -435.0,745.0Q-422.0,733.0 -422.0,716.0Q-422.0,697.0 -435.0,686.0Q-448.0,675.0 -463.0,675.0Q-480.0,675.0 -492.5,686.5Q-505.0,698.0 -505.0,716.0ZM-371.0,716.0Q-371.0,733.0 -358.5,745.0Q-346.0,757.0 -329.0,757.0Q-314.0,757.0 -301.0,745.0Q-288.0,733.0 -288.0,716.0Q-288.0,697.0 -301.0,686.0Q-314.0,675.0 -329.0,675.0Q-346.0,675.0 -358.5,686.5Q-371.0,698.0 -371.0,716.0ZM-28.0,612.0Q-103.0,616.0 -163.0,656.0Q-223.0,696.0 -262.5,761.0Q-302.0,826.0 -315.0,905.0L-244.0,920.0Q-231.0,818.0 -173.5,752.5Q-116.0,687.0 -22.0,668.0L-28.0,612.0Z" transform="translate(1945, 1319)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2410 3201" transform="matrix(1 0 0 -1 0 0)">
<path d="M60.0,394.0Q60.0,460.0 97.0,503.0Q134.0,546.0 210.0,546.0Q348.0,546.0 348.0,380.0L348.0,244.0L409.0,244.0L409.0,251.0Q409.0,340.0 439.0,406.0Q469.0,472.0 528.5,509.0Q588.0,546.0 677.0,546.0Q758.0,546.0 809.5,516.5Q861.0,487.0 880.0,442.0L880.0,536.0L993.0,536.0Q1145.0,536.0 1145.0,383.0L1145.0,0.0L1064.0,0.0L1064.0,387.0Q1064.0,466.0 991.0,466.0L949.0,466.0L949.0,0.0L868.0,0.0L868.0,236.0Q868.0,347.0 818.5,410.5Q769.0,474.0 676.0,474.0Q582.0,474.0 534.5,412.5Q487.0,351.0 487.0,235.0Q556.0,225.0 608.0,207.5Q660.0,190.0 689.0,160.5Q718.0,131.0 718.0,84.0Q718.0,38.0 686.5,14.0Q655.0,-10.0 611.0,-10.0Q573.0,-10.0 536.0,8.0Q499.0,26.0 470.0,59.0Q454.0,78.0 438.5,107.5Q423.0,137.0 415.0,179.0L348.0,179.0L348.0,104.0Q348.0,51.0 321.0,20.5Q294.0,-10.0 243.0,-10.0Q189.0,-10.0 160.0,21.5Q131.0,53.0 131.0,101.0Q131.0,160.0 172.0,196.5Q213.0,233.0 271.0,240.0L271.0,384.0Q271.0,431.0 255.5,452.5Q240.0,474.0 207.0,474.0Q171.0,474.0 153.5,451.0Q136.0,428.0 136.0,387.0Q136.0,335.0 160.0,269.0L103.0,242.0Q60.0,324.0 60.0,394.0ZM202.0,102.0Q202.0,86.0 210.5,71.5Q219.0,57.0 239.0,57.0Q271.0,57.0 271.0,98.0L271.0,172.0Q202.0,154.0 202.0,102.0ZM496.0,167.0Q503.0,136.0 521.0,111.0Q539.0,86.0 562.5,71.0Q586.0,56.0 608.0,56.0Q625.0,56.0 634.5,64.5Q644.0,73.0 644.0,86.0Q644.0,111.0 607.5,133.0Q571.0,155.0 496.0,167.0Z" transform="translate(0, 1338)"/>
<path d="M-439.0,832.0Q-439.0,849.0 -426.5,861.0Q-414.0,873.0 -397.0,873.0Q-382.0,873.0 -369.0,861.0Q-356.0,849.0 -356.0,832.0Q-356.0,813.0 -369.0,802.0Q-382.0,791.0 -397.0,791.0Q-414.0,791.0 -426.5,802.5Q-439.0,814.0 -439.0,832.0ZM-505.0,716.0Q-505.0,733.0 -492.5,745.0Q-480.0,757.0 -463.0,757.0Q-448.0,757.0 -435.0,745.0Q-422.0,733.0 -422.0,716.0Q-422.0,697.0 -435.0,686.0Q-448.0,675.0 -463.0,675.0Q-480.0,675.0 -492.5,686.5Q-505.0,698.0 -505.0,716.0ZM-371.0,716.0Q-371.0,733.0 -358.5,745.0Q-346.0,757.0 -329.0,757.0Q-314.0,757.0 -301.0,745.0Q-288.0,733.0 -288.0,716.0Q-288.0,697.0 -301.0,686.0Q-314.0,675.0 -329.0,675.0Q-346.0,675.0 -358.5,686.5Q-371.0,698.0 -371.0,716.0ZM-28.0,612.0Q-103.0,616.0 -163.0,656.0Q-223.0,696.0 -262.5,761.0Q-302.0,826.0 -315.0,905.0L-244.0,920.0Q-231.0,818.0 -173.5,752.5Q-116.0,687.0 -22.0,668.0L-28.0,612.0Z" transform="translate(740, 1319)"/>
<path d="M-181.0,-435.0L-181.0,-303.0Q-181.0,-233.0 -219.5,-198.5Q-258.0,-164.0 -323.0,-164.0Q-397.0,-164.0 -438.5,-207.5Q-480.0,-251.0 -487.0,-316.0L-482.0,-316.0Q-417.0,-316.0 -366.0,-327.0Q-315.0,-338.0 -285.5,-365.0Q-256.0,-392.0 -256.0,-441.0Q-256.0,-490.0 -289.0,-518.5Q-322.0,-547.0 -376.0,-547.0Q-419.0,-547.0 -457.0,-528.5Q-495.0,-510.0 -521.5,-473.0Q-548.0,-436.0 -556.0,-381.0L-607.0,-381.0L-607.0,-401.0Q-607.0,-477.0 -640.5,-512.0Q-674.0,-547.0 -727.0,-547.0Q-778.0,-547.0 -809.0,-517.5Q-840.0,-488.0 -840.0,-444.0Q-840.0,-392.0 -798.5,-361.0Q-757.0,-330.0 -686.0,-323.0L-686.0,-246.0Q-686.0,-202.0 -702.0,-182.5Q-718.0,-163.0 -748.0,-163.0Q-776.0,-163.0 -791.5,-181.0Q-807.0,-199.0 -807.0,-229.0Q-807.0,-245.0 -803.5,-260.5Q-800.0,-276.0 -796.0,-287.0L-848.0,-310.0Q-858.0,-291.0 -866.5,-266.5Q-875.0,-242.0 -875.0,-214.0Q-875.0,-155.0 -837.5,-123.5Q-800.0,-92.0 -742.0,-92.0Q-680.0,-92.0 -643.5,-127.5Q-607.0,-163.0 -607.0,-236.0L-607.0,-317.0L-557.0,-317.0Q-551.0,-259.0 -523.0,-207.5Q-495.0,-156.0 -444.5,-124.0Q-394.0,-92.0 -320.0,-92.0Q-261.0,-92.0 -211.0,-115.0Q-161.0,-138.0 -130.5,-183.5Q-100.0,-229.0 -100.0,-297.0L-100.0,-433.0Q-100.0,-475.0 -70.0,-475.0Q-42.0,-475.0 -3.5,-437.5Q35.0,-400.0 82.0,-330.0L137.0,-367.0Q82.0,-456.0 29.5,-501.5Q-23.0,-547.0 -81.0,-547.0Q-126.0,-547.0 -153.5,-519.0Q-181.0,-491.0 -181.0,-435.0ZM-464.0,-383.0L-484.0,-383.0Q-475.0,-430.0 -447.0,-456.5Q-419.0,-483.0 -382.0,-483.0Q-354.0,-483.0 -342.5,-470.5Q-331.0,-458.0 -331.0,-442.0Q-331.0,-417.0 -361.5,-400.0Q-392.0,-383.0 -464.0,-383.0ZM-686.0,-411.0L-686.0,-386.0Q-718.0,-391.0 -744.0,-404.5Q-770.0,-418.0 -770.0,-447.0Q-770.0,-462.0 -760.5,-473.0Q-751.0,-484.0 -732.0,-484.0Q-713.0,-484.0 -699.5,-470.0Q-686.0,-456.0 -686.0,-411.0Z" transform="translate(1205, 1338)"/>
<path d="M60.0,394.0Q60.0,460.0 97.0,503.0Q134.0,546.0 210.0,546.0Q348.0,546.0 348.0,380.0L348.0,244.0L409.0,244.0L409.0,251.0Q409.0,340.0 439.0,406.0Q469.0,472.0 528.5,509.0Q588.0,546.0 677.0,546.0Q758.0,546.0 809.5,516.5Q861.0,487.0 880.0,442.0L880.0,536.0L993.0,536.0Q1145.0,536.0 1145.0,383.0L1145.0,0.0L1064.0,0.0L1064.0,387.0Q1064.0,466.0 991.0,466.0L949.0,466.0L949.0,0.0L868.0,0.0L868.0,236.0Q868.0,347.0 818.5,410.5Q769.0,474.0 676.0,474.0Q582.0,474.0 534.5,412.5Q487.0,351.0 487.0,235.0Q556.0,225.0 608.0,207.5Q660.0,190.0 689.0,160.5Q718.0,131.0 718.0,84.0Q718.0,38.0 686.5,14.0Q655.0,-10.0 611.0,-10.0Q573.0,-10.0 536.0,8.0Q499.0,26.0 470.0,59.0Q454.0,78.0 438.5,107.5Q423.0,137.0 415.0,179.0L348.0,179.0L348.0,104.0Q348.0,51.0 321.0,20.5Q294.0,-10.0 243.0,-10.0Q189.0,-10.0 160.0,21.5Q131.0,53.0 131.0,101.0Q131.0,160.0 172.0,196.5Q213.0,233.0 271.0,240.0L271.0,384.0Q271.0,431.0 255.5,452.5Q240.0,474.0 207.0,474.0Q171.0,474.0 153.5,451.0Q136.0,428.0 136.0,387.0Q136.0,335.0 160.0,269.0L103.0,242.0Q60.0,324.0 60.0,394.0ZM202.0,102.0Q202.0,86.0 210.5,71.5Q219.0,57.0 239.0,57.0Q271.0,57.0 271.0,98.0L271.0,172.0Q202.0,154.0 202.0,102.0ZM496.0,167.0Q503.0,136.0 521.0,111.0Q539.0,86.0 562.5,71.0Q586.0,56.0 608.0,56.0Q625.0,56.0 634.5,64.5Q644.0,73.0 644.0,86.0Q644.0,111.0 607.5,133.0Q571.0,155.0 496.0,167.0Z" transform="translate(1205, 1338)"/>
<path d="M-439.0,832.0Q-439.0,849.0 -426.5,861.0Q-414.0,873.0 -397.0,873.0Q-382.0,873.0 -369.0,861.0Q-356.0,849.0 -356.0,832.0Q-356.0,813.0 -369.0,802.0Q-382.0,791.0 -397.0,791.0Q-414.0,791.0 -426.5,802.5Q-439.0,814.0 -439.0,832.0ZM-505.0,716.0Q-505.0,733.0 -492.5,745.0Q-480.0,757.0 -463.0,757.0Q-448.0,757.0 -435.0,745.0Q-422.0,733.0 -422.0,716.0Q-422.0,697.0 -435.0,686.0Q-448.0,675.0 -463.0,675.0Q-480.0,675.0 -492.5,686.5Q-505.0,698.0 -505.0,716.0ZM-371.0,716.0Q-371.0,733.0 -358.5,745.0Q-346.0,757.0 -329.0,757.0Q-314.0,757.0 -301.0,745.0Q-288.0,733.0 -288.0,716.0Q-288.0,697.0 -301.0,686.0Q-314.0,675.0 -329.0,675.0Q-346.0,675.0 -358.5,686.5Q-371.0,698.0 -371.0,716.0ZM-28.0,612.0Q-103.0,616.0 -163.0,656.0Q-223.0,696.0 -262.5,761.0Q-302.0,826.0 -315.0,905.0L-244.0,920.0Q-231.0,818.0 -173.5,752.5Q-116.0,687.0 -22.0,668.0L-28.0,612.0Z" transform="translate(1945, 1319)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1B05
	* uni1B10
	* uni1B1A.conj.u
	* uni1B1B
	* uni1B1B.td
	* uni1B23.conj.ya.u
	* uni1B24.conj.u
	* uni1B2D.conj.ya
	* uni1B31.conj
	* uni1B31.conj.ra and 13 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _128

	- cereg2

	- cereg3

	- cereg5

	- nonmarkingreturn

	- uni1B1A.2.nya

	- uni1B3A.5 

	- uni1B3E001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni1B3C (U+1B3C) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni1B16 (U+1B16): L<<948.0,-10.0>--<948.0,-10.0>> -> L<<948.0,-10.0>--<948.0,-10.0>>

	* uni1B1E (U+1B1E): L<<359.0,0.0>--<359.0,0.0>> -> L<<359.0,0.0>--<359.0,0.0>>

	* uni1B2D (U+1B2D): L<<558.0,546.0>--<558.0,546.0>> -> L<<558.0,546.0>--<558.0,546.0>>

	* uni1B2D (U+1B2D): L<<558.0,546.0>--<558.0,546.0>> -> L<<558.0,546.0>--<559.0,546.0>> 

	* uni1B2D (U+1B2D): L<<558.0,546.0>--<559.0,546.0>> -> L<<559.0,546.0>--<559.0,546.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni1B18 (U+1B18): L<<597.0,-10.0>--<597.0,-10.0>>/B<<597.0,-10.0>-<544.0,-9.0>-<500.0,22.0>> = 1.080924186660573 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansBalinese-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1381, but got 1363 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni1B05
	* uni1B0E.conj
	* uni1B10
	* uni1B13
	* uni1B13.conj
	* uni1B13.ra
	* uni1B13.ra_uni1B2D.conj.wa
	* uni1B13.td
	* uni1B14
	* uni1B14.conj and 97 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Balinese SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _128

	- cereg2

	- cereg3

	- cereg5

	- nonmarkingreturn

	- uni1B1A.2.nya

	- uni1B3A.5 

	- uni1B3E001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni1B3C (U+1B3C) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=406.0,Y=699.5 (should be at cap-height 700?)

	* three (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* six (U+0036): X=242.5,Y=699.5 (should be at cap-height 700?)

	* nine (U+0039): X=89.0,Y=-2.0 (should be at baseline 0?)

	* at (U+0040): X=437.0,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=485.0,Y=-2.0 (should be at baseline 0?)

	* G (U+0047): X=530.5,Y=0.5 (should be at baseline 0?)

	* c (U+0063): X=389.0,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=424.0,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=126.5,Y=-2.0 (should be at baseline 0?) 

	* 65 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni1B16 (U+1B16): L<<1044.0,-10.0>--<1044.0,-10.0>> -> L<<1044.0,-10.0>--<1044.0,-10.0>>

	* uni1B18 (U+1B18): L<<626.0,-10.0>--<626.0,-10.0>> -> L<<626.0,-10.0>--<626.0,-10.0>>

	* uni1B1E (U+1B1E): L<<368.0,0.0>--<368.0,0.0>> -> L<<368.0,0.0>--<368.0,0.0>>

	* uni1B24 (U+1B24): L<<652.0,546.0>--<652.0,546.0>> -> L<<652.0,546.0>--<652.0,546.0>> 

	* uni1B2D (U+1B2D): L<<575.0,546.0>--<575.0,546.0>> -> L<<575.0,546.0>--<575.0,546.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929

	* W (U+0057): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929

	* Wacute (U+1E82): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929

	* Wcircumflex (U+0174): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929

	* Wdieresis (U+1E84): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<258.0,184.5>-<264.0,152.0>-<267.0,127.0>>/B<<267.0,127.0>-<270.0,153.0>-<276.0,185.5>> = 13.424718067808929 

	* Wgrave (U+1E80): B<<678.0,183.5>-<684.0,151.0>-<687.0,127.0>>/B<<687.0,127.0>-<690.0,152.0>-<696.0,184.5>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansBalinese[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1381, but got 1363 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _128

	- cereg2

	- cereg3

	- cereg5

	- nonmarkingreturn

	- uni1B1A.2.nya

	- uni1B3A.5 

	- uni1B3E001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni1B3C (U+1B3C) [code: mark-chars]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 4 | 18 | 42 | 567 | 32 | 499 | 0 |
| 0% | 2% | 4% | 49% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
