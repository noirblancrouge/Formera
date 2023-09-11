## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[15] Formera-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure that the font can be rasterized by FreeType. (derived from com.adobe.fonts/check/freetype_rasterizer) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.adobe.fonts/check/freetype_rasterizer">com.adobe.fonts/check/freetype_rasterizer</a>)</summary><div>


* 💔 **ERROR** Failed with UnboundLocalError: local variable 'FT_Exception' referenced before assignment
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have components which are themselves components. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyf_nested_components">com.google.fonts/check/glyf_nested_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have components which themselves are component glyphs:
	* uni1EA0
	* uni1E0C
	* uni1E0E
	* uni1EB8
	* uni0122
	* uni1E2A
	* uni1E24
	* uni1ECA
	* uni0136
	* uni013B
	* uni1E36
	* uni1E3A
	* uni1E42
	* uni0145
	* uni1E46
	* uni1E48
	* uni1ECC
	* uni0156
	* uni1E5A
	* uni1E5E
	* uni0218
	* uni1E62
	* uni1E68
	* uni021A
	* uni1E6C
	* uni1E6E
	* uni1EE4
	* uni1E92
	* uni1EA1
	* uni1E0D
	* uni1E0F
	* uni1EB9
	* uni1E2B
	* uni1E25
	* uni1ECB
	* uni0137
	* uni013C
	* uni1E37
	* uni1E3B
	* uni1E43
	* uni0146
	* uni1E47
	* uni1E49
	* uni1ECD
	* uni0157
	* uni1E5B
	* uni1E5F
	* uni0219
	* uni1E63
	* uni1E69
	* uni021B
	* uni1E6D
	* uni1E6F
	* uni1EE5
	* uni1E93
	* onehalf
	* onequarter
	* threequarters
	* uni2070
	* uni00B9
	* uni00B2
	* uni00B3
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* quotedblbase and IJacute [code: found-nested-components]
</div></details><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command.

# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x02BC (MODIFIER LETTER APOSTROPHE)


	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- eight.subs

	- five.subs

	- four.subs

	- ijacute

	- nine.subs

	- one.subs

	- prime

	- seven.subs

	- six.subs

	- three.subs

	- two.subs

	- uni00690307 

	- zero.subs
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: macron	Contours detected: 2	Expected: 1

	- Glyph name: uni00B5	Contours detected: 2	Expected: 1

	- Glyph name: onequarter	Contours detected: 5	Expected: 3 or 4

	- Glyph name: onehalf	Contours detected: 4	Expected: 3

	- Glyph name: threequarters	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aring	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: Imacron	Contours detected: 3	Expected: 2

	- Glyph name: imacron	Contours detected: 3	Expected: 2

	- Glyph name: iogonek	Contours detected: 1	Expected: 2 or 3

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 3	Expected: 4

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni0304	Contours detected: 2	Expected: 1

	- Glyph name: uni0331	Contours detected: 2	Expected: 1

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1

	- Glyph name: uni1E0E	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0F	Contours detected: 4	Expected: 3

	- Glyph name: uni1E14	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E16	Contours detected: 4	Expected: 3

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E3A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E3B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E48	Contours detected: 3	Expected: 2

	- Glyph name: uni1E49	Contours detected: 4	Expected: 2

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5E	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5F	Contours detected: 4	Expected: 2

	- Glyph name: uni1E6E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E6F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: fraction	Contours detected: 2	Expected: 1

	- Glyph name: uni2105	Contours detected: 5	Expected: 4

	- Glyph name: uni2113	Contours detected: 4	Expected: 2

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Imacron	Contours detected: 3	Expected: 2

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: aeacute	Contours detected: 3	Expected: 4

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: aring	Contours detected: 3	Expected: 4

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: fraction	Contours detected: 2	Expected: 1

	- Glyph name: imacron	Contours detected: 3	Expected: 2

	- Glyph name: iogonek	Contours detected: 1	Expected: 2 or 3

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: macron	Contours detected: 2	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: onehalf	Contours detected: 4	Expected: 3

	- Glyph name: onequarter	Contours detected: 5	Expected: 3 or 4

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: threequarters	Contours detected: 5	Expected: 3 or 4

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni00B5	Contours detected: 2	Expected: 1

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni0304	Contours detected: 2	Expected: 1

	- Glyph name: uni0331	Contours detected: 2	Expected: 1

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1

	- Glyph name: uni1E0E	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0F	Contours detected: 4	Expected: 3

	- Glyph name: uni1E14	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E16	Contours detected: 4	Expected: 3

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E3A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E3B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E48	Contours detected: 3	Expected: 2

	- Glyph name: uni1E49	Contours detected: 4	Expected: 2

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5E	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5F	Contours detected: 4	Expected: 2

	- Glyph name: uni1E6E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E6F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: uni2105	Contours detected: 5	Expected: 4 

	- Glyph name: uni2113	Contours detected: 4	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font have a DSIG table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig">com.google.fonts/check/dsig</a>)</summary><div>


* ⚠ **WARN** This font has a digital signature (DSIG table) which is only required - even if only a placeholder - on old programs like MS Office 2013 in order to work properly.
The current recommendation is to completely remove the DSIG table. [code: found-DSIG]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* approxequal (U+2248): L<<331.0,182.0>--<356.0,180.0>>/L<<356.0,180.0>--<352.0,180.0>> = 4.573921259900818

	* approxequal (U+2248): L<<331.0,372.0>--<356.0,370.0>>/L<<356.0,370.0>--<352.0,370.0>> = 4.573921259900818

	* approxequal (U+2248): L<<356.0,180.0>--<352.0,180.0>>/L<<352.0,180.0>--<369.0,177.0>> = 10.00797980144135

	* approxequal (U+2248): L<<356.0,370.0>--<352.0,370.0>>/L<<352.0,370.0>--<369.0,367.0>> = 10.00797980144135

	* asciitilde (U+007E): L<<338.0,224.0>--<363.0,222.0>>/L<<363.0,222.0>--<359.0,222.0>> = 4.573921259900818

	* asciitilde (U+007E): L<<363.0,222.0>--<359.0,222.0>>/L<<359.0,222.0>--<376.0,219.0>> = 10.00797980144135

	* copyright (U+00A9): B<<649.0,203.0>-<655.0,218.0>-<655.0,216.0>>/L<<655.0,216.0>--<656.0,223.0>> = 8.13010235415596

	* copyright (U+00A9): L<<514.0,439.0>--<513.0,418.0>>/B<<513.0,418.0>-<513.0,421.0>-<505.0,429.0>> = 2.726310993906212

	* currency (U+00A4): B<<450.0,202.0>-<450.0,194.0>-<461.0,192.0>>/L<<461.0,192.0>--<460.0,192.0>> = 10.304846468766044

	* currency (U+00A4): L<<239.0,129.0>--<242.0,129.0>>/L<<242.0,129.0>--<212.0,135.0>> = 11.309932474020195

	* currency (U+00A4): L<<276.0,127.0>--<239.0,129.0>>/L<<239.0,129.0>--<242.0,129.0>> = 3.0940580589171134

	* currency (U+00A4): L<<295.0,573.0>--<319.0,570.0>>/L<<319.0,570.0>--<318.0,570.0>> = 7.125016348901757

	* currency (U+00A4): L<<319.0,570.0>--<318.0,570.0>>/L<<318.0,570.0>--<330.0,567.0>> = 14.036243467926484

	* currency (U+00A4): L<<438.0,535.0>--<512.0,608.0>>/B<<512.0,608.0>-<511.0,607.0>-<518.0,601.0>> = 0.3897611953170412

	* dagger (U+2020): L<<179.0,775.0>--<178.0,775.0>>/L<<178.0,775.0>--<184.0,776.0>> = 9.462322208025613

	* degree (U+00B0): B<<243.0,697.0>-<283.0,699.0>-<278.0,699.0>>/B<<278.0,699.0>-<295.0,695.0>-<314.0,695.0>> = 13.240519915187184

	* divide (U+00F7): L<<468.0,329.0>--<467.0,307.0>>/B<<467.0,307.0>-<467.0,309.0>-<464.0,309.0>> = 2.6025622024998034

	* equal (U+003D): L<<443.0,278.0>--<462.0,277.0>>/L<<462.0,277.0>--<460.0,277.0>> = 3.012787504183286

	* equal (U+003D): L<<468.0,258.0>--<467.0,236.0>>/B<<467.0,236.0>-<467.0,238.0>-<464.0,238.0>> = 2.6025622024998034

	* estimated (U+212E): L<<203.0,613.0>--<206.0,616.0>>/L<<206.0,616.0>--<184.0,599.0>> = 7.3057595333108205

	* estimated (U+212E): L<<215.0,622.0>--<203.0,613.0>>/L<<203.0,613.0>--<206.0,616.0>> = 8.13010235415596

	* estimated (U+212E): L<<388.0,695.0>--<408.0,692.0>>/L<<408.0,692.0>--<407.0,692.0>> = 8.530765609948139

	* estimated (U+212E): L<<408.0,692.0>--<407.0,692.0>>/L<<407.0,692.0>--<421.0,691.0>> = 4.085616779974888

	* estimated (U+212E): L<<587.0,149.0>--<607.0,175.0>>/L<<607.0,175.0>--<606.0,174.0>> = 7.431407971172489

	* estimated (U+212E): L<<591.0,94.0>--<594.0,97.0>>/L<<594.0,97.0>--<576.0,80.0>> = 1.6365770416166923

	* estimated (U+212E): L<<600.0,102.0>--<591.0,94.0>>/L<<591.0,94.0>--<594.0,97.0>> = 3.3664606634298315

	* guillemotright (U+00BB): B<<307.0,270.0>-<321.0,253.0>-<320.0,254.0>>/B<<320.0,254.0>-<333.0,245.0>-<345.0,228.0>> = 10.304846468765973

	* infinity (U+221E): L<<208.0,443.0>--<209.0,443.0>>/B<<209.0,443.0>-<197.0,444.0>-<187.5,446.0>> = 4.763641690726144

	* infinity (U+221E): L<<545.0,239.0>--<544.0,238.0>>/L<<544.0,238.0>--<552.0,244.0>> = 8.13010235415596

	* integral (U+222B): L<<222.0,-182.0>--<222.0,-183.0>>/L<<222.0,-183.0>--<229.0,-152.0>> = 12.724355685422363

	* lslash (U+0142): L<<159.0,473.0>--<160.0,464.0>>/B<<160.0,464.0>-<160.0,475.0>-<159.0,473.0>> = 6.340191745909908

	* minus (U+2212): L<<32.0,342.0>--<33.0,349.0>>/B<<33.0,349.0>-<33.0,348.0>-<40.0,349.0>> = 8.13010235415596

	* minus (U+2212): L<<443.0,349.0>--<468.0,348.0>>/B<<468.0,348.0>-<466.0,348.0>-<468.0,340.0>> = 2.2906100426384346

	* minus (U+2212): L<<57.0,307.0>--<30.0,310.0>>/B<<30.0,310.0>-<32.0,310.0>-<32.0,318.0>> = 6.340191745909908

	* minute (U+2032): L<<30.0,511.0>--<31.0,518.0>>/L<<31.0,518.0>--<31.0,517.0>> = 8.13010235415596

	* minute (U+2032): L<<31.0,518.0>--<31.0,517.0>>/L<<31.0,517.0>--<35.0,542.0>> = 9.090276920822312

	* multiply (U+00D7): B<<255.0,293.0>-<250.0,298.0>-<251.0,299.0>>/L<<251.0,299.0>--<228.0,280.0>> = 5.4403320310054815

	* notequal (U+2260): B<<179.0,222.5>-<184.0,237.0>-<185.0,237.0>>/L<<185.0,237.0>--<159.0,239.0>> = 4.398705354995508

	* notequal (U+2260): B<<293.0,460.0>-<299.0,475.0>-<299.0,472.0>>/B<<299.0,472.0>-<300.0,476.0>-<307.0,488.0>> = 14.036243467926484

	* notequal (U+2260): L<<30.0,258.0>--<33.0,278.0>>/B<<33.0,278.0>-<33.0,276.0>-<56.0,278.0>> = 8.530765609948096

	* numbersign (U+0023): L<<448.0,313.0>--<449.0,313.0>>/B<<449.0,313.0>-<439.0,312.0>-<433.0,299.0>> = 5.710593137499633

	* numbersign (U+0023): L<<468.0,315.0>--<448.0,313.0>>/L<<448.0,313.0>--<449.0,313.0>> = 5.710593137499633

	* paragraph (U+00B6): L<<372.0,455.0>--<371.0,462.0>>/L<<371.0,462.0>--<371.0,461.0>> = 8.13010235415596

	* paragraph (U+00B6): L<<67.0,614.0>--<74.0,620.0>>/L<<74.0,620.0>--<73.0,619.0>> = 4.398705354995508

	* paragraph (U+00B6): L<<74.0,620.0>--<73.0,619.0>>/L<<73.0,619.0>--<87.0,630.0>> = 6.842773412630916

	* partialdiff (U+2202): L<<274.0,396.0>--<277.0,396.0>>/L<<277.0,396.0>--<259.0,399.0>> = 9.462322208025613

	* partialdiff (U+2202): L<<304.0,392.0>--<274.0,396.0>>/L<<274.0,396.0>--<277.0,396.0>> = 7.594643368591397

	* partialdiff (U+2202): L<<340.0,50.0>--<345.0,54.0>>/L<<345.0,54.0>--<344.0,53.0>> = 6.34019174590985

	* partialdiff (U+2202): L<<345.0,54.0>--<344.0,53.0>>/B<<344.0,53.0>-<354.0,62.0>-<354.0,60.0>> = 3.0127875041831653

	* partialdiff (U+2202): L<<90.0,222.0>--<90.0,225.0>>/L<<90.0,225.0>--<89.0,196.0>> = 1.9749340108819595

	* partialdiff (U+2202): L<<91.0,239.0>--<90.0,222.0>>/L<<90.0,222.0>--<90.0,225.0>> = 3.3664606634298315

	* percent (U+0025): B<<202.0,456.0>-<219.0,464.0>-<216.0,461.0>>/L<<216.0,461.0>--<239.0,479.0>> = 6.952957468173817

	* percent (U+0025): L<<119.0,620.0>--<120.0,621.0>>/L<<120.0,621.0>--<98.0,604.0>> = 7.3057595333108205

	* percent (U+0025): L<<150.0,451.0>--<154.0,450.0>>/L<<154.0,450.0>--<153.0,450.0>> = 14.036243467926484

	* percent (U+0025): L<<154.0,450.0>--<153.0,450.0>>/L<<153.0,450.0>--<170.0,448.0>> = 6.709836807756896

	* percent (U+0025): L<<391.0,204.0>--<391.0,205.0>>/L<<391.0,205.0>--<390.0,201.0>> = 14.036243467926484

	* percent (U+0025): L<<391.0,205.0>--<390.0,201.0>>/L<<390.0,201.0>--<390.0,204.0>> = 14.036243467926484

	* percent (U+0025): L<<485.0,206.0>--<486.0,207.0>>/L<<486.0,207.0>--<482.0,204.0>> = 8.13010235415596

	* percent (U+0025): L<<486.0,207.0>--<482.0,204.0>>/L<<482.0,204.0>--<485.0,207.0>> = 8.13010235415596

	* perthousand (U+2030): L<<118.0,619.0>--<120.0,621.0>>/L<<120.0,621.0>--<98.0,604.0>> = 7.3057595333108205

	* perthousand (U+2030): L<<516.0,13.0>--<519.0,16.0>>/B<<519.0,16.0>-<507.0,7.0>-<495.0,4.0>> = 8.13010235415596

	* perthousand (U+2030): L<<537.0,31.0>--<516.0,13.0>>/L<<516.0,13.0>--<519.0,16.0>> = 4.398705354995591

	* perthousand (U+2030): L<<707.0,201.0>--<710.0,204.0>>/L<<710.0,204.0>--<689.0,187.0>> = 6.009005957494474

	* perthousand (U+2030): L<<712.0,205.0>--<707.0,201.0>>/L<<707.0,201.0>--<710.0,204.0>> = 6.340191745909908

	* pi (U+03C0): B<<415.0,366.0>-<408.0,366.0>-<408.0,367.0>>/L<<408.0,367.0>--<406.0,343.0>> = 4.763641690726144

	* pi (U+03C0): L<<122.0,-3.0>--<99.0,0.0>>/L<<99.0,0.0>--<101.0,0.0>> = 7.431407971172489

	* pi (U+03C0): L<<366.0,101.0>--<363.0,133.0>>/L<<363.0,133.0>--<363.0,132.0>> = 5.355825042855143

	* plus (U+002B): L<<229.0,523.0>--<230.0,531.0>>/B<<230.0,531.0>-<230.0,530.0>-<250.0,530.0>> = 7.1250163489018075

	* plus (U+002B): L<<232.0,127.0>--<227.0,128.0>>/L<<227.0,128.0>--<230.0,128.0>> = 11.309932474020195

	* plus (U+002B): L<<418.0,348.0>--<443.0,349.0>>/L<<443.0,349.0>--<442.0,349.0>> = 2.2906100426384346

	* plus (U+002B): L<<443.0,349.0>--<442.0,349.0>>/B<<442.0,349.0>-<456.0,350.0>-<461.0,349.0>> = 4.085616779974799

	* plusminus (U+00B1): L<<228.0,309.0>--<227.0,314.0>>/L<<227.0,314.0>--<227.0,313.0>> = 11.309932474020227

	* plusminus (U+00B1): L<<250.0,559.0>--<271.0,558.0>>/B<<271.0,558.0>-<270.0,558.0>-<271.0,536.0>> = 2.726310993906212

	* plusminus (U+00B1): L<<42.0,75.0>--<30.0,76.0>>/B<<30.0,76.0>-<33.0,76.0>-<33.0,95.0>> = 4.763641690726144

	* plusminus (U+00B1): L<<468.0,95.0>--<467.0,73.0>>/B<<467.0,73.0>-<467.0,76.0>-<443.0,76.0>> = 2.6025622024998034

	* product (U+220F): B<<567.0,-194.0>-<578.0,-209.0>-<577.0,-209.0>>/L<<577.0,-209.0>--<594.0,-210.0>> = 3.3664606634298315

	* product (U+220F): L<<430.0,-230.0>--<433.0,-209.0>>/B<<433.0,-209.0>-<433.0,-210.0>-<456.0,-210.0>> = 8.13010235415596

	* product (U+220F): L<<452.0,-253.0>--<430.0,-250.0>>/B<<430.0,-250.0>-<433.0,-250.0>-<430.0,-240.0>> = 7.765166018425308

	* radical (U+221A): L<<187.0,91.0>--<193.0,64.0>>/L<<193.0,64.0>--<193.0,68.0>> = 12.52880770915152

	* radical (U+221A): L<<401.0,747.0>--<402.0,754.0>>/L<<402.0,754.0>--<402.0,753.0>> = 8.13010235415596

	* radical (U+221A): L<<644.0,828.0>--<669.0,827.0>>/B<<669.0,827.0>-<667.0,827.0>-<669.0,810.0>> = 2.2906100426384346

	* radical (U+221A): L<<87.0,354.0>--<110.0,353.0>>/B<<110.0,353.0>-<109.0,353.0>-<112.0,348.0>> = 2.489552921999128

	* registered (U+00AE): L<<674.0,280.0>--<675.0,304.0>>/L<<675.0,304.0>--<675.0,303.0>> = 2.3859440303887243

	* registered (U+00AE): L<<675.0,304.0>--<675.0,303.0>>/L<<675.0,303.0>--<677.0,319.0>> = 7.1250163489018075

	* second (U+2033): L<<211.0,511.0>--<212.0,518.0>>/L<<212.0,518.0>--<212.0,517.0>> = 8.13010235415596

	* second (U+2033): L<<212.0,518.0>--<212.0,517.0>>/L<<212.0,517.0>--<216.0,542.0>> = 9.090276920822312

	* second (U+2033): L<<31.0,511.0>--<32.0,518.0>>/L<<32.0,518.0>--<32.0,517.0>> = 8.13010235415596

	* second (U+2033): L<<32.0,518.0>--<32.0,517.0>>/L<<32.0,517.0>--<36.0,542.0>> = 9.090276920822312

	* uni00B5 (U+00B5): L<<386.0,75.0>--<387.0,76.0>>/L<<387.0,76.0>--<378.0,68.0>> = 3.3664606634298315

	* uni00B5 (U+00B5): L<<69.0,-156.0>--<69.0,-157.0>>/B<<69.0,-157.0>-<68.0,-147.0>-<70.0,-145.0>> = 5.710593137499633

	* uni00B5 (U+00B5): L<<70.0,-166.0>--<69.0,-155.0>>/L<<69.0,-155.0>--<69.0,-156.0>> = 5.1944289077348

	* uni03A9 (U+03A9): L<<371.0,630.0>--<374.0,630.0>>/L<<374.0,630.0>--<362.0,632.0>> = 9.462322208025613

	* uni03A9 (U+03A9): L<<398.0,626.0>--<371.0,630.0>>/L<<371.0,630.0>--<374.0,630.0>> = 8.426969021480636

	* uni03A9 (U+03A9): L<<587.0,292.0>--<589.0,314.0>>/L<<589.0,314.0>--<589.0,313.0>> = 5.1944289077348

	* uni03A9 (U+03A9): L<<589.0,313.0>--<592.0,337.0>>/L<<592.0,337.0>--<592.0,336.0>> = 7.1250163489018075

	* uni03A9 (U+03A9): L<<589.0,314.0>--<589.0,313.0>>/L<<589.0,313.0>--<592.0,337.0>> = 7.1250163489018075

	* uni03A9 (U+03A9): L<<592.0,337.0>--<592.0,336.0>>/L<<592.0,336.0>--<593.0,366.0>> = 1.9091524329963898

	* uni03BC (U+03BC): L<<386.0,75.0>--<387.0,76.0>>/L<<387.0,76.0>--<378.0,68.0>> = 3.3664606634298315

	* uni03BC (U+03BC): L<<69.0,-156.0>--<69.0,-157.0>>/B<<69.0,-157.0>-<68.0,-147.0>-<70.0,-145.0>> = 5.710593137499633

	* uni03BC (U+03BC): L<<70.0,-166.0>--<69.0,-155.0>>/L<<69.0,-155.0>--<69.0,-156.0>> = 5.1944289077348

	* uni1E9E (U+1E9E): L<<375.0,-5.0>--<376.0,-5.0>>/L<<376.0,-5.0>--<343.0,-3.0>> = 3.468229258917096

	* uni1E9E (U+1E9E): L<<385.0,-6.0>--<375.0,-5.0>>/L<<375.0,-5.0>--<376.0,-5.0>> = 5.710593137499633

	* uni2113 (U+2113): L<<200.0,97.0>--<197.0,86.0>>/B<<197.0,86.0>-<198.0,88.0>-<199.0,80.0>> = 11.309932474020195

	* uni2113 (U+2113): L<<274.0,560.0>--<279.0,600.0>>/L<<279.0,600.0>--<279.0,591.0>> = 7.1250163489018075

	* uni2113 (U+2113): L<<312.0,-6.0>--<314.0,-6.0>>/L<<314.0,-6.0>--<310.0,-7.0>> = 14.036243467926484

	* uni2113 (U+2113): L<<314.0,-6.0>--<310.0,-7.0>>/L<<310.0,-7.0>--<312.0,-6.0>> = 12.528807709151463

	* uni2113 (U+2113): L<<357.0,491.0>--<356.0,485.0>>/L<<356.0,485.0>--<356.0,487.0>> = 9.462322208025613

	* uni2113 (U+2113): L<<368.0,22.0>--<386.0,37.0>>/L<<386.0,37.0>--<383.0,35.0>> = 6.115503566285384

	* uni2113 (U+2113): L<<386.0,37.0>--<383.0,35.0>>/L<<383.0,35.0>--<400.0,48.0>> = 3.715289105428815

	* uni2126 (U+2126): L<<371.0,630.0>--<374.0,630.0>>/L<<374.0,630.0>--<362.0,632.0>> = 9.462322208025613

	* uni2126 (U+2126): L<<398.0,626.0>--<371.0,630.0>>/L<<371.0,630.0>--<374.0,630.0>> = 8.426969021480636

	* uni2126 (U+2126): L<<587.0,292.0>--<589.0,314.0>>/L<<589.0,314.0>--<589.0,313.0>> = 5.1944289077348

	* uni2126 (U+2126): L<<589.0,313.0>--<592.0,337.0>>/L<<592.0,337.0>--<592.0,336.0>> = 7.1250163489018075

	* uni2126 (U+2126): L<<589.0,314.0>--<589.0,313.0>>/L<<589.0,313.0>--<592.0,337.0>> = 7.1250163489018075

	* uni2126 (U+2126): L<<592.0,337.0>--<592.0,336.0>>/L<<592.0,336.0>--<593.0,366.0>> = 1.9091524329963898

	* uni2325 (U+2325): L<<51.0,478.0>--<52.0,484.0>>/L<<52.0,484.0>--<52.0,483.0>> = 9.462322208025613

	* uni2B1B (U+2B1B): L<<51.0,274.0>--<51.0,273.0>>/B<<51.0,273.0>-<50.0,284.0>-<52.0,286.0>> = 5.1944289077348

	* uni2B1B (U+2B1B): L<<52.0,267.0>--<51.0,274.0>>/L<<51.0,274.0>--<51.0,273.0>> = 8.13010235415596

	* uni2B1B (U+2B1B): L<<72.0,-121.0>--<60.0,-120.0>>/L<<60.0,-120.0>--<62.0,-120.0>> = 4.763641690726144 

	* uni2B1C (U+2B1C): L<<55.0,494.0>--<52.0,519.0>>/L<<52.0,519.0>--<52.0,518.0>> = 6.842773412630916 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* t (U+0074): L<<109.0,322.0>--<108.0,56.0>>

	* tcaron (U+0165): L<<109.0,322.0>--<108.0,56.0>>

	* thorn (U+00FE): L<<109.0,540.0>--<108.0,401.0>>

	* uni0163 (U+0163): L<<109.0,322.0>--<108.0,56.0>>

	* uni018F (U+018F): L<<491.0,288.0>--<375.0,289.0>>

	* uni021B (U+021B): L<<109.0,322.0>--<108.0,56.0>>

	* uni1E6D (U+1E6D): L<<109.0,322.0>--<108.0,56.0>>

	* uni1E6F (U+1E6F): L<<109.0,322.0>--<108.0,56.0>>

	* uni1E97 (U+1E97): L<<109.0,322.0>--<108.0,56.0>>

	* uni1E9E (U+1E9E): L<<124.0,571.0>--<123.0,416.0>> 

	* uni2015 (U+2015): L<<443.0,405.0>--<565.0,404.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] Formera-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure that the font can be rasterized by FreeType. (derived from com.adobe.fonts/check/freetype_rasterizer) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.adobe.fonts/check/freetype_rasterizer">com.adobe.fonts/check/freetype_rasterizer</a>)</summary><div>


* 💔 **ERROR** Failed with UnboundLocalError: local variable 'FT_Exception' referenced before assignment
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Formera | Formera |
| Subfamily Name | Regular | Regular |
| Full Name | Formera Regular | Formera Regular |
| Poscript Name | Formera-Regular | Formera-Regular |
| Typographic Family Name | Formera | N/A |
| Typographic Subfamily Name | Regular | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have components which are themselves components. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyf_nested_components">com.google.fonts/check/glyf_nested_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have components which themselves are component glyphs:
	* uni1EA0
	* uni1E0C
	* uni1E0E
	* uni1EB8
	* uni0122
	* uni1E2A
	* uni1E24
	* uni1ECA
	* uni0136
	* uni013B
	* uni1E36
	* uni1E3A
	* uni1E42
	* uni0145
	* uni1E46
	* uni1E48
	* uni1ECC
	* uni0156
	* uni1E5A
	* uni1E5E
	* uni0218
	* uni1E62
	* uni1E68
	* uni021A
	* uni1E6C
	* uni1E6E
	* uni1EE4
	* uni1E92
	* uni1EA1
	* uni1E0D
	* uni1E0F
	* uni1EB9
	* uni1E2B
	* uni1E25
	* uni1ECB
	* uni0137
	* uni013C
	* uni1E37
	* uni1E3B
	* uni1E43
	* uni0146
	* uni1E47
	* uni1E49
	* uni1ECD
	* uni0157
	* uni1E5B
	* uni1E5F
	* uni0219
	* uni1E63
	* uni1E69
	* uni021B
	* uni1E6D
	* uni1E6F
	* uni1EE5
	* uni1E93
	* onehalf
	* onequarter
	* threequarters
	* uni2070
	* uni00B9
	* uni00B2
	* uni00B3
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* quotedblbase and IJacute [code: found-nested-components]
</div></details><details><summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted">com.google.fonts/check/integer_ppem_if_hinted</a>)</summary><div>


* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command.

# create virtualenv
python3 -m venv venv
# activate virtualenv
source venv/bin/activate
# install gftools
pip install git+https://www.github.com/googlefonts/tools [code: bad-flags]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ į̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x02BC (MODIFIER LETTER APOSTROPHE)


	- 0x1E34 (LATIN CAPITAL LETTER K WITH LINE BELOW)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- eight.subs

	- five.subs

	- four.subs

	- ijacute

	- nine.subs

	- one.subs

	- prime

	- seven.subs

	- six.subs

	- three.subs

	- two.subs

	- uni00690307 

	- zero.subs
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aring	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: iogonek	Contours detected: 1	Expected: 2 or 3

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 3	Expected: 4

	- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5F	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: ae	Contours detected: 2	Expected: 3

	- Glyph name: aeacute	Contours detected: 3	Expected: 4

	- Glyph name: aring	Contours detected: 3	Expected: 4

	- Glyph name: iogonek	Contours detected: 1	Expected: 2 or 3

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5B	Contours detected: 3	Expected: 2 

	- Glyph name: uni1E5F	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 500 among a set of 12 math glyphs.
The following math glyphs have a different width, though:

Width = 600:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font have a DSIG table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/dsig.html#com.google.fonts/check/dsig">com.google.fonts/check/dsig</a>)</summary><div>


* ⚠ **WARN** This font has a digital signature (DSIG table) which is only required - even if only a placeholder - on old programs like MS Office 2013 in order to work properly.
The current recommendation is to completely remove the DSIG table. [code: found-DSIG]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ampersand (U+0026): L<<286.0,469.0>--<290.0,472.0>>/L<<290.0,472.0>--<289.0,471.0>> = 8.13010235415596

	* ampersand (U+0026): L<<290.0,472.0>--<289.0,471.0>>/L<<289.0,471.0>--<301.0,481.0>> = 5.19442890773487

	* ampersand (U+0026): L<<419.0,543.0>--<418.0,534.0>>/L<<418.0,534.0>--<418.0,537.0>> = 6.340191745909908

	* copyright (U+00A9): L<<236.0,468.0>--<255.0,485.0>>/L<<255.0,485.0>--<254.0,484.0>> = 3.1798301198642793

	* copyright (U+00A9): L<<255.0,485.0>--<254.0,484.0>>/L<<254.0,484.0>--<262.0,491.0>> = 3.8140748342902824

	* copyright (U+00A9): L<<382.0,619.0>--<385.0,619.0>>/L<<385.0,619.0>--<356.0,620.0>> = 1.9749340108819595

	* copyright (U+00A9): L<<393.0,618.0>--<382.0,619.0>>/L<<382.0,619.0>--<385.0,619.0>> = 5.1944289077348

	* copyright (U+00A9): L<<583.0,62.0>--<586.0,65.0>>/L<<586.0,65.0>--<563.0,49.0>> = 10.175510843043194

	* copyright (U+00A9): L<<604.0,81.0>--<583.0,62.0>>/L<<583.0,62.0>--<586.0,65.0>> = 2.862405226111779

	* currency (U+00A4): B<<515.0,620.0>-<530.0,620.0>-<533.0,637.0>>/L<<533.0,637.0>--<533.0,636.0>> = 10.007979801441312

	* currency (U+00A4): L<<314.0,592.0>--<338.0,589.0>>/L<<338.0,589.0>--<337.0,589.0>> = 7.125016348901757

	* currency (U+00A4): L<<338.0,589.0>--<337.0,589.0>>/L<<337.0,589.0>--<362.0,583.0>> = 13.495733280795811

	* currency (U+00A4): L<<58.0,379.0>--<61.0,402.0>>/L<<61.0,402.0>--<61.0,401.0>> = 7.431407971172489

	* currency (U+00A4): L<<61.0,402.0>--<61.0,401.0>>/L<<61.0,401.0>--<67.0,426.0>> = 13.495733280795811

	* degree (U+00B0): B<<273.0,745.0>-<317.0,747.0>-<311.0,747.0>>/B<<311.0,747.0>-<329.0,743.0>-<349.0,743.0>> = 12.528807709151492

	* estimated (U+212E): L<<321.0,-19.0>--<324.0,-19.0>>/L<<324.0,-19.0>--<296.0,-16.0>> = 6.115503566285384

	* estimated (U+212E): L<<328.0,-20.0>--<321.0,-19.0>>/L<<321.0,-19.0>--<324.0,-19.0>> = 8.13010235415596

	* infinity (U+221E): L<<376.0,441.0>--<396.0,458.0>>/L<<396.0,458.0>--<395.0,457.0>> = 4.635463426902695

	* infinity (U+221E): L<<396.0,458.0>--<395.0,457.0>>/L<<395.0,457.0>--<407.0,466.0>> = 8.13010235415596

	* k (U+006B): B<<280.0,195.0>-<322.0,150.0>-<321.0,151.0>>/B<<321.0,151.0>-<326.0,143.0>-<333.0,133.5>> = 12.994616791916483

	* kgreenlandic (U+0138): B<<289.0,195.0>-<331.0,150.0>-<330.0,151.0>>/B<<330.0,151.0>-<335.0,143.0>-<342.0,133.5>> = 12.994616791916483

	* logicalnot (U+00AC): B<<417.0,-3.0>-<394.0,-3.0>-<397.0,0.0>>/L<<397.0,0.0>--<394.0,-2.0>> = 11.309932474020227

	* minute (U+2032): L<<43.0,602.0>--<46.0,627.0>>/L<<46.0,627.0>--<46.0,626.0>> = 6.842773412630916

	* minute (U+2032): L<<46.0,627.0>--<46.0,626.0>>/L<<46.0,626.0>--<47.0,649.0>> = 2.489552921999128

	* multiply (U+00D7): L<<267.0,397.0>--<281.0,414.0>>/L<<281.0,414.0>--<280.0,413.0>> = 5.527540151656193

	* multiply (U+00D7): L<<281.0,414.0>--<280.0,413.0>>/B<<280.0,413.0>-<286.0,421.0>-<294.0,426.0>> = 8.13010235415596

	* numbersign (U+0023): L<<403.0,71.0>--<399.0,53.0>>/B<<399.0,53.0>-<399.0,57.0>-<392.0,34.0>> = 12.528807709151492

	* o (U+006F): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* oacute (U+00F3): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* obreve (U+014F): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* ocircumflex (U+00F4): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* odieresis (U+00F6): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* ograve (U+00F2): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* ohungarumlaut (U+0151): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* omacron (U+014D): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* oslash (U+00F8): B<<375.0,123.0>-<390.0,141.0>-<389.0,140.0>>/B<<389.0,140.0>-<405.0,159.0>-<413.5,172.5>> = 4.899092453787774

	* oslashacute (U+01FF): B<<375.0,123.0>-<390.0,141.0>-<389.0,140.0>>/B<<389.0,140.0>-<405.0,159.0>-<413.5,172.5>> = 4.899092453787774

	* otilde (U+00F5): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* paragraph (U+00B6): L<<385.0,586.0>--<385.0,585.0>>/B<<385.0,585.0>-<384.0,594.0>-<386.0,596.0>> = 6.340191745909908

	* paragraph (U+00B6): L<<386.0,575.0>--<385.0,586.0>>/L<<385.0,586.0>--<385.0,585.0>> = 5.1944289077348

	* partialdiff (U+2202): L<<135.0,668.0>--<153.0,665.0>>/L<<153.0,665.0>--<152.0,665.0>> = 9.462322208025613

	* partialdiff (U+2202): L<<153.0,665.0>--<152.0,665.0>>/B<<152.0,665.0>-<162.0,664.0>-<177.0,659.0>> = 5.710593137499633

	* percent (U+0025): L<<623.0,24.0>--<626.0,27.0>>/L<<626.0,27.0>--<603.0,10.0>> = 8.530765609948139

	* percent (U+0025): L<<631.0,31.0>--<623.0,24.0>>/L<<623.0,24.0>--<626.0,27.0>> = 3.8140748342902824

	* perthousand (U+2030): B<<558.0,56.0>-<574.0,62.0>-<572.0,60.0>>/L<<572.0,60.0>--<580.0,67.0>> = 3.814074834290187

	* perthousand (U+2030): B<<607.0,100.0>-<610.0,109.0>-<610.0,107.0>>/B<<610.0,107.0>-<611.0,123.0>-<614.0,123.0>> = 3.576334374997269

	* perthousand (U+2030): L<<457.0,177.0>--<457.0,178.0>>/L<<457.0,178.0>--<454.0,166.0>> = 14.036243467926484

	* plusminus (U+00B1): L<<211.0,270.0>--<211.0,269.0>>/B<<211.0,269.0>-<210.0,280.0>-<212.0,282.0>> = 5.1944289077348

	* plusminus (U+00B1): L<<212.0,262.0>--<211.0,270.0>>/L<<211.0,270.0>--<211.0,269.0>> = 7.125016348901757

	* plusminus (U+00B1): L<<287.0,197.0>--<286.0,171.0>>/B<<286.0,171.0>-<286.0,174.0>-<261.0,174.0>> = 2.2025981617658017

	* plusminus (U+00B1): L<<30.0,343.0>--<30.0,342.0>>/B<<30.0,342.0>-<28.0,355.0>-<32.0,355.0>> = 8.746162262555211

	* product (U+220F): L<<101.0,337.0>--<98.0,360.0>>/L<<98.0,360.0>--<98.0,359.0>> = 7.431407971172489

	* product (U+220F): L<<257.0,-228.0>--<256.0,-253.0>>/B<<256.0,-253.0>-<256.0,-250.0>-<231.0,-250.0>> = 2.2906100426384346

	* product (U+220F): L<<28.0,-251.0>--<20.0,-250.0>>/L<<20.0,-250.0>--<23.0,-250.0>> = 7.125016348901757

	* product (U+220F): L<<412.0,-206.0>--<415.0,-183.0>>/B<<415.0,-183.0>-<415.0,-184.0>-<438.0,-184.0>> = 7.431407971172489

	* product (U+220F): L<<495.0,-95.0>--<494.0,-87.0>>/L<<494.0,-87.0>--<494.0,-88.0>> = 7.125016348901757

	* registered (U+00AE): B<<473.0,64.0>-<488.0,70.0>-<486.0,68.0>>/B<<486.0,68.0>-<491.0,72.0>-<494.0,72.0>> = 6.34019174590985

	* registered (U+00AE): L<<564.0,45.0>--<567.0,48.0>>/L<<567.0,48.0>--<554.0,37.0>> = 4.763641690726066

	* registered (U+00AE): L<<587.0,62.0>--<564.0,45.0>>/L<<564.0,45.0>--<567.0,48.0>> = 8.530765609948139

	* second (U+2033): L<<223.0,602.0>--<226.0,627.0>>/L<<226.0,627.0>--<226.0,626.0>> = 6.842773412630916

	* second (U+2033): L<<226.0,627.0>--<226.0,626.0>>/L<<226.0,626.0>--<227.0,649.0>> = 2.489552921999128

	* second (U+2033): L<<43.0,602.0>--<46.0,627.0>>/L<<46.0,627.0>--<46.0,626.0>> = 6.842773412630916

	* second (U+2033): L<<46.0,627.0>--<46.0,626.0>>/L<<46.0,626.0>--<47.0,649.0>> = 2.489552921999128

	* summation (U+2211): L<<529.0,534.0>--<519.0,535.0>>/B<<519.0,535.0>-<521.0,535.0>-<521.0,537.0>> = 5.710593137499633

	* uni00B5 (U+00B5): L<<383.0,316.0>--<380.0,339.0>>/L<<380.0,339.0>--<380.0,338.0>> = 7.431407971172489

	* uni0137 (U+0137): B<<280.0,195.0>-<322.0,150.0>-<321.0,151.0>>/B<<321.0,151.0>-<326.0,143.0>-<333.0,133.5>> = 12.994616791916483

	* uni01EB (U+01EB): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* uni03A9 (U+03A9): L<<122.0,596.0>--<145.0,617.0>>/L<<145.0,617.0>--<144.0,616.0>> = 2.6025622024998034

	* uni03A9 (U+03A9): L<<145.0,617.0>--<144.0,616.0>>/L<<144.0,616.0>--<155.0,625.0>> = 5.710593137499696

	* uni03A9 (U+03A9): L<<410.0,-3.0>--<377.0,0.0>>/B<<377.0,0.0>-<379.0,0.0>-<379.0,10.0>> = 5.1944289077348

	* uni03A9 (U+03A9): L<<610.0,71.0>--<641.0,70.0>>/B<<641.0,70.0>-<639.0,70.0>-<641.0,62.0>> = 1.8476102659945155

	* uni03BC (U+03BC): L<<383.0,316.0>--<380.0,339.0>>/L<<380.0,339.0>--<380.0,338.0>> = 7.431407971172489

	* uni1E4D (U+1E4D): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* uni1E4F (U+1E4F): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* uni1E51 (U+1E51): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* uni1E53 (U+1E53): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* uni1ECD (U+1ECD): B<<363.0,123.0>-<378.0,141.0>-<377.0,140.0>>/B<<377.0,140.0>-<393.0,159.0>-<401.5,172.5>> = 4.899092453787774

	* uni2113 (U+2113): L<<186.0,303.0>--<189.0,307.0>>/L<<189.0,307.0>--<188.0,306.0>> = 8.13010235415596

	* uni2113 (U+2113): L<<188.0,114.0>--<189.0,122.0>>/L<<189.0,122.0>--<189.0,121.0>> = 7.1250163489018075

	* uni2113 (U+2113): L<<189.0,122.0>--<189.0,121.0>>/L<<189.0,121.0>--<192.0,151.0>> = 5.710593137499633

	* uni2113 (U+2113): L<<390.0,26.0>--<393.0,29.0>>/L<<393.0,29.0>--<375.0,14.0>> = 5.1944289077348

	* uni2113 (U+2113): L<<407.0,39.0>--<390.0,26.0>>/L<<390.0,26.0>--<393.0,29.0>> = 7.594643368591495

	* uni2116 (U+2116): B<<1118.0,355.0>-<1133.0,373.0>-<1132.0,372.0>>/B<<1132.0,372.0>-<1148.0,391.0>-<1156.5,404.5>> = 4.899092453787774

	* uni2126 (U+2126): L<<122.0,596.0>--<145.0,617.0>>/L<<145.0,617.0>--<144.0,616.0>> = 2.6025622024998034

	* uni2126 (U+2126): L<<145.0,617.0>--<144.0,616.0>>/L<<144.0,616.0>--<155.0,625.0>> = 5.710593137499696

	* uni2126 (U+2126): L<<410.0,-3.0>--<377.0,0.0>>/B<<377.0,0.0>-<379.0,0.0>-<379.0,10.0>> = 5.1944289077348

	* uni2126 (U+2126): L<<610.0,71.0>--<641.0,70.0>>/B<<641.0,70.0>-<639.0,70.0>-<641.0,62.0>> = 1.8476102659945155

	* uni2318 (U+2318): L<<144.0,-51.0>--<175.0,-54.0>>/L<<175.0,-54.0>--<174.0,-54.0>> = 5.527540151656126

	* uni2318 (U+2318): L<<175.0,-54.0>--<174.0,-54.0>>/L<<174.0,-54.0>--<200.0,-52.0>> = 4.398705354995508

	* uni2325 (U+2325): L<<330.0,459.0>--<333.0,484.0>>/B<<333.0,484.0>-<333.0,483.0>-<338.0,488.0>> = 6.842773412630916

	* uni2325 (U+2325): L<<364.0,409.0>--<339.0,412.0>>/B<<339.0,412.0>-<341.0,412.0>-<336.0,417.0>> = 6.842773412630916

	* uni2B1B (U+2B1B): L<<52.0,471.0>--<52.0,470.0>>/B<<52.0,470.0>-<51.0,482.0>-<54.0,482.0>> = 4.763641690726144

	* uni2B1B (U+2B1B): L<<53.0,461.0>--<52.0,471.0>>/L<<52.0,471.0>--<52.0,470.0>> = 5.710593137499633 

	* uni2B1C (U+2B1C): B<<167.0,501.0>-<154.0,501.0>-<154.0,503.0>>/L<<154.0,503.0>--<151.0,481.0>> = 7.765166018425354 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* H (U+0048): L<<66.0,551.0>--<65.0,667.0>>

	* Hcircumflex (U+0124): L<<66.0,551.0>--<65.0,667.0>>

	* f_i (U+FB01): L<<67.0,46.0>--<66.0,169.0>>

	* m (U+006D): L<<117.0,450.0>--<242.0,449.0>>

	* seven (U+0037): L<<473.0,516.0>--<603.0,515.0>>

	* uni1E24 (U+1E24): L<<66.0,551.0>--<65.0,667.0>>

	* uni1E2A (U+1E2A): L<<66.0,551.0>--<65.0,667.0>> 

	* uni1E43 (U+1E43): L<<117.0,450.0>--<242.0,449.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 2 | 7 | 23 | 236 | 16 | 191 | 0 |
| 0% | 1% | 5% | 50% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
