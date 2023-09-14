## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[8] Nemoy-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2825, but got 1900 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 875, but got 560 instead [code: descent]
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

	- IJacute
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: comma	Contours detected: 2	Expected: 1

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: eight	Contours detected: 4	Expected: 3

	- Glyph name: semicolon	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: grave	Contours detected: 2	Expected: 1

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: uni00B2	Contours detected: 2	Expected: 1

	- Glyph name: uni00B3	Contours detected: 2	Expected: 1

	- Glyph name: acute	Contours detected: 2	Expected: 1

	- Glyph name: uni00B9	Contours detected: 2	Expected: 1

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: threequarters	Contours detected: 5	Expected: 3or4

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: Egrave	Contours detected: 4	Expected: 2

	- Glyph name: Eacute	Contours detected: 4	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Igrave	Contours detected: 3	Expected: 2

	- Glyph name: Iacute	Contours detected: 3	Expected: 2

	- Glyph name: Icircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ntilde	Contours detected: 3	Expected: 2

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Yacute	Contours detected: 4	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: igrave	Contours detected: 3	Expected: 2

	- Glyph name: iacute	Contours detected: 3	Expected: 2

	- Glyph name: icircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: yacute	Contours detected: 4	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 4	Expected: 2

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: Gcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: Jcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Lacute	Contours detected: 4	Expected: 2

	- Glyph name: lacute	Contours detected: 4	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 4	Expected: 2

	- Glyph name: nacute	Contours detected: 4	Expected: 2

	- Glyph name: uni0145	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: Ncaron	Contours detected: 4	Expected: 2

	- Glyph name: ncaron	Contours detected: 4	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Racute	Contours detected: 5	Expected: 3

	- Glyph name: racute	Contours detected: 5	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 4	Expected: 2

	- Glyph name: Rcaron	Contours detected: 5	Expected: 3

	- Glyph name: rcaron	Contours detected: 5	Expected: 2

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Tcaron	Contours detected: 3	Expected: 2

	- Glyph name: tcaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 4	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: Gcaron	Contours detected: 4	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

	- Glyph name: AEacute	Contours detected: 6	Expected: 3

	- Glyph name: aeacute	Contours detected: 6	Expected: 4

	- Glyph name: Oslashacute	Contours detected: 5	Expected: 4

	- Glyph name: oslashacute	Contours detected: 5	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: circumflex	Contours detected: 2	Expected: 1

	- Glyph name: caron	Contours detected: 2	Expected: 1

	- Glyph name: gravecomb	Contours detected: 2	Expected: 1

	- Glyph name: acutecomb	Contours detected: 2	Expected: 1

	- Glyph name: uni0302	Contours detected: 2	Expected: 1

	- Glyph name: uni030C	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 4	Expected: 2

	- Glyph name: uni1E14	Contours detected: 5	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E16	Contours detected: 5	Expected: 3

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2E	Contours detected: 5	Expected: 4

	- Glyph name: uni1E2F	Contours detected: 5	Expected: 4

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: Lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: Nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: rmacronbelow	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 5	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: wgrave	Contours detected: 5	Expected: 2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: Ygrave	Contours detected: 4	Expected: 2

	- Glyph name: ygrave	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: quotesinglbase	Contours detected: 2	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 4	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: trademark	Contours detected: 4	Expected: 2

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: AEacute	Contours detected: 6	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: Eacute	Contours detected: 4	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 4	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Egrave	Contours detected: 4	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gcaron	Contours detected: 4	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: Iacute	Contours detected: 3	Expected: 2

	- Glyph name: Icircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Igrave	Contours detected: 3	Expected: 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: Lacute	Contours detected: 4	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 4	Expected: 2

	- Glyph name: Ncaron	Contours detected: 4	Expected: 2

	- Glyph name: Ntilde	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oslashacute	Contours detected: 5	Expected: 4

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 5	Expected: 3

	- Glyph name: Rcaron	Contours detected: 5	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Tcaron	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 4	Expected: 2

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: acute	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 6	Expected: 4

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: cacute	Contours detected: 3	Expected: 2

	- Glyph name: caron	Contours detected: 2	Expected: 1

	- Glyph name: ccaron	Contours detected: 3	Expected: 2

	- Glyph name: ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: circumflex	Contours detected: 2	Expected: 1

	- Glyph name: comma	Contours detected: 2	Expected: 1

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eight	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: grave	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: iacute	Contours detected: 3	Expected: 2

	- Glyph name: icircumflex	Contours detected: 3	Expected: 2

	- Glyph name: igrave	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 4	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 4	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 4	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: oslashacute	Contours detected: 5	Expected: 4

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: quotedblbase	Contours detected: 4	Expected: 2

	- Glyph name: quotesinglbase	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 5	Expected: 2

	- Glyph name: rcaron	Contours detected: 5	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: semicolon	Contours detected: 3	Expected: 2

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: tcaron	Contours detected: 3	Expected: 2

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: threequarters	Contours detected: 5	Expected: 3or4

	- Glyph name: trademark	Contours detected: 4	Expected: 2

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 4	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni0302	Contours detected: 2	Expected: 1

	- Glyph name: uni030C	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 4	Expected: 2

	- Glyph name: uni1E14	Contours detected: 5	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E16	Contours detected: 5	Expected: 3

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2E	Contours detected: 5	Expected: 4

	- Glyph name: uni1E2F	Contours detected: 5	Expected: 4

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 5	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 5	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 5	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 4	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 4	Expected: 2

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: zacute	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<1811.0,671.0>--<2531.0,670.0>>

	* AE (U+00C6): L<<2531.0,573.0>--<1659.0,574.0>>

	* AEacute (U+01FC): L<<1811.0,671.0>--<2531.0,670.0>>

	* AEacute (U+01FC): L<<2531.0,573.0>--<1659.0,574.0>>

	* E (U+0045): L<<1109.0,573.0>--<237.0,574.0>>

	* E (U+0045): L<<389.0,671.0>--<1109.0,670.0>>

	* Eacute (U+00C9): L<<1109.0,573.0>--<237.0,574.0>>

	* Eacute (U+00C9): L<<389.0,671.0>--<1109.0,670.0>>

	* Ebreve (U+0114): L<<1109.0,573.0>--<237.0,574.0>>

	* Ebreve (U+0114): L<<389.0,671.0>--<1109.0,670.0>>

	* Ecaron (U+011A): L<<1109.0,573.0>--<237.0,574.0>>

	* Ecaron (U+011A): L<<389.0,671.0>--<1109.0,670.0>>

	* Ecircumflex (U+00CA): L<<1109.0,573.0>--<237.0,574.0>>

	* Ecircumflex (U+00CA): L<<389.0,671.0>--<1109.0,670.0>>

	* Edieresis (U+00CB): L<<1109.0,573.0>--<237.0,574.0>>

	* Edieresis (U+00CB): L<<389.0,671.0>--<1109.0,670.0>>

	* Edotaccent (U+0116): L<<1109.0,573.0>--<237.0,574.0>>

	* Edotaccent (U+0116): L<<389.0,671.0>--<1109.0,670.0>>

	* Egrave (U+00C8): L<<1109.0,573.0>--<237.0,574.0>>

	* Egrave (U+00C8): L<<389.0,671.0>--<1109.0,670.0>>

	* Emacron (U+0112): L<<1109.0,573.0>--<237.0,574.0>>

	* Emacron (U+0112): L<<389.0,671.0>--<1109.0,670.0>>

	* Eogonek (U+0118): L<<1109.0,573.0>--<237.0,574.0>>

	* Eogonek (U+0118): L<<389.0,671.0>--<1109.0,670.0>>

	* F (U+0046): L<<1101.0,578.0>--<237.0,577.0>>

	* OE (U+0152): L<<1856.0,671.0>--<2576.0,670.0>>

	* OE (U+0152): L<<2576.0,573.0>--<1704.0,574.0>>

	* ae (U+00E6): L<<1811.0,671.0>--<2531.0,670.0>>

	* ae (U+00E6): L<<2531.0,573.0>--<1659.0,574.0>>

	* aeacute (U+01FD): L<<1811.0,671.0>--<2531.0,670.0>>

	* aeacute (U+01FD): L<<2531.0,573.0>--<1659.0,574.0>>

	* asterisk (U+002A): L<<463.0,1818.0>--<462.0,1628.0>>

	* e (U+0065): L<<1109.0,573.0>--<237.0,574.0>>

	* e (U+0065): L<<389.0,671.0>--<1109.0,670.0>>

	* eacute (U+00E9): L<<1109.0,573.0>--<237.0,574.0>>

	* eacute (U+00E9): L<<389.0,671.0>--<1109.0,670.0>>

	* ebreve (U+0115): L<<1109.0,573.0>--<237.0,574.0>>

	* ebreve (U+0115): L<<389.0,671.0>--<1109.0,670.0>>

	* ecaron (U+011B): L<<1109.0,573.0>--<237.0,574.0>>

	* ecaron (U+011B): L<<389.0,671.0>--<1109.0,670.0>>

	* ecircumflex (U+00EA): L<<1109.0,573.0>--<237.0,574.0>>

	* ecircumflex (U+00EA): L<<389.0,671.0>--<1109.0,670.0>>

	* edieresis (U+00EB): L<<1109.0,573.0>--<237.0,574.0>>

	* edieresis (U+00EB): L<<389.0,671.0>--<1109.0,670.0>>

	* edotaccent (U+0117): L<<1109.0,573.0>--<237.0,574.0>>

	* edotaccent (U+0117): L<<389.0,671.0>--<1109.0,670.0>>

	* egrave (U+00E8): L<<1109.0,573.0>--<237.0,574.0>>

	* egrave (U+00E8): L<<389.0,671.0>--<1109.0,670.0>>

	* emacron (U+0113): L<<1109.0,573.0>--<237.0,574.0>>

	* emacron (U+0113): L<<389.0,671.0>--<1109.0,670.0>>

	* eogonek (U+0119): L<<1109.0,573.0>--<237.0,574.0>>

	* eogonek (U+0119): L<<389.0,671.0>--<1109.0,670.0>>

	* f (U+0066): L<<1101.0,578.0>--<237.0,577.0>>

	* oe (U+0153): L<<1856.0,671.0>--<2576.0,670.0>>

	* oe (U+0153): L<<2576.0,573.0>--<1704.0,574.0>>

	* onehalf (U+00BD): L<<343.0,1296.0>--<342.0,452.0>>

	* onequarter (U+00BC): L<<343.0,1296.0>--<342.0,452.0>>

	* uni1E14 (U+1E14): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1E14 (U+1E14): L<<389.0,671.0>--<1109.0,670.0>>

	* uni1E15 (U+1E15): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1E15 (U+1E15): L<<389.0,671.0>--<1109.0,670.0>>

	* uni1E16 (U+1E16): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1E16 (U+1E16): L<<389.0,671.0>--<1109.0,670.0>>

	* uni1E17 (U+1E17): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1E17 (U+1E17): L<<389.0,671.0>--<1109.0,670.0>>

	* uni1E1C (U+1E1C): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1E1C (U+1E1C): L<<389.0,671.0>--<1109.0,670.0>>

	* uni1E1D (U+1E1D): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1E1D (U+1E1D): L<<389.0,671.0>--<1109.0,670.0>>

	* uni1EB8 (U+1EB8): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1EB8 (U+1EB8): L<<389.0,671.0>--<1109.0,670.0>>

	* uni1EB9 (U+1EB9): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1EB9 (U+1EB9): L<<389.0,671.0>--<1109.0,670.0>>

	* uni1EBC (U+1EBC): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1EBC (U+1EBC): L<<389.0,671.0>--<1109.0,670.0>>

	* uni1EBD (U+1EBD): L<<1109.0,573.0>--<237.0,574.0>>

	* uni1EBD (U+1EBD): L<<389.0,671.0>--<1109.0,670.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[7] Nemoy-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2825, but got 1900 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 875, but got 560 instead [code: descent]
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

	- IJacute
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: comma	Contours detected: 2	Expected: 1

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: eight	Contours detected: 4	Expected: 3

	- Glyph name: semicolon	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: grave	Contours detected: 2	Expected: 1

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: uni00B2	Contours detected: 2	Expected: 1

	- Glyph name: uni00B3	Contours detected: 2	Expected: 1

	- Glyph name: acute	Contours detected: 2	Expected: 1

	- Glyph name: uni00B9	Contours detected: 2	Expected: 1

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: threequarters	Contours detected: 5	Expected: 3or4

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: Egrave	Contours detected: 4	Expected: 2

	- Glyph name: Eacute	Contours detected: 4	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Igrave	Contours detected: 3	Expected: 2

	- Glyph name: Iacute	Contours detected: 3	Expected: 2

	- Glyph name: Icircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ntilde	Contours detected: 3	Expected: 2

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Yacute	Contours detected: 4	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: igrave	Contours detected: 3	Expected: 2

	- Glyph name: iacute	Contours detected: 3	Expected: 2

	- Glyph name: icircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: yacute	Contours detected: 4	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 4	Expected: 2

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: Gcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: uni0122	Contours detected: 4	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: Jcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: uni0136	Contours detected: 4	Expected: 2or3

	- Glyph name: uni0137	Contours detected: 4	Expected: 2or3

	- Glyph name: Lacute	Contours detected: 4	Expected: 2

	- Glyph name: lacute	Contours detected: 4	Expected: 2

	- Glyph name: uni013B	Contours detected: 4	Expected: 2

	- Glyph name: uni013C	Contours detected: 4	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 4	Expected: 2

	- Glyph name: nacute	Contours detected: 4	Expected: 2

	- Glyph name: uni0145	Contours detected: 4	Expected: 2

	- Glyph name: uni0146	Contours detected: 4	Expected: 2

	- Glyph name: Ncaron	Contours detected: 4	Expected: 2

	- Glyph name: ncaron	Contours detected: 4	Expected: 2

	- Glyph name: napostrophe	Contours detected: 4	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Racute	Contours detected: 5	Expected: 3

	- Glyph name: racute	Contours detected: 5	Expected: 2

	- Glyph name: uni0156	Contours detected: 5	Expected: 3

	- Glyph name: uni0157	Contours detected: 5	Expected: 2

	- Glyph name: Rcaron	Contours detected: 5	Expected: 3

	- Glyph name: rcaron	Contours detected: 5	Expected: 2

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Tcaron	Contours detected: 3	Expected: 2

	- Glyph name: tcaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 4	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: Gcaron	Contours detected: 4	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

	- Glyph name: AEacute	Contours detected: 6	Expected: 3

	- Glyph name: aeacute	Contours detected: 6	Expected: 4

	- Glyph name: Oslashacute	Contours detected: 5	Expected: 4

	- Glyph name: oslashacute	Contours detected: 5	Expected: 4

	- Glyph name: uni0218	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni021A	Contours detected: 3	Expected: 2

	- Glyph name: uni021B	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: circumflex	Contours detected: 2	Expected: 1

	- Glyph name: caron	Contours detected: 2	Expected: 1

	- Glyph name: gravecomb	Contours detected: 2	Expected: 1

	- Glyph name: acutecomb	Contours detected: 2	Expected: 1

	- Glyph name: uni0302	Contours detected: 2	Expected: 1

	- Glyph name: uni030C	Contours detected: 2	Expected: 1

	- Glyph name: uni0312	Contours detected: 2	Expected: 1

	- Glyph name: uni0326	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 4	Expected: 2

	- Glyph name: uni1E14	Contours detected: 5	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E16	Contours detected: 5	Expected: 3

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2E	Contours detected: 5	Expected: 4

	- Glyph name: uni1E2F	Contours detected: 5	Expected: 4

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: Lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: Nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: rmacronbelow	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 5	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: wgrave	Contours detected: 5	Expected: 2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: Ygrave	Contours detected: 4	Expected: 2

	- Glyph name: ygrave	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: quoteleft	Contours detected: 2	Expected: 1

	- Glyph name: quoteright	Contours detected: 2	Expected: 1

	- Glyph name: quotesinglbase	Contours detected: 2	Expected: 1

	- Glyph name: quotedblleft	Contours detected: 4	Expected: 2

	- Glyph name: quotedblright	Contours detected: 4	Expected: 2

	- Glyph name: quotedblbase	Contours detected: 4	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: trademark	Contours detected: 4	Expected: 2

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: AEacute	Contours detected: 6	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: Eacute	Contours detected: 4	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 4	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Egrave	Contours detected: 4	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gcaron	Contours detected: 4	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: Iacute	Contours detected: 3	Expected: 2

	- Glyph name: Icircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Igrave	Contours detected: 3	Expected: 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: Lacute	Contours detected: 4	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 4	Expected: 2

	- Glyph name: Ncaron	Contours detected: 4	Expected: 2

	- Glyph name: Ntilde	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oslashacute	Contours detected: 5	Expected: 4

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 5	Expected: 3

	- Glyph name: Rcaron	Contours detected: 5	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Tcaron	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 4	Expected: 2

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: acute	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 6	Expected: 4

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: cacute	Contours detected: 3	Expected: 2

	- Glyph name: caron	Contours detected: 2	Expected: 1

	- Glyph name: ccaron	Contours detected: 3	Expected: 2

	- Glyph name: ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: circumflex	Contours detected: 2	Expected: 1

	- Glyph name: comma	Contours detected: 2	Expected: 1

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eight	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: grave	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: hcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: iacute	Contours detected: 3	Expected: 2

	- Glyph name: icircumflex	Contours detected: 3	Expected: 2

	- Glyph name: igrave	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 4	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 4	Expected: 2

	- Glyph name: napostrophe	Contours detected: 4	Expected: 2

	- Glyph name: ncaron	Contours detected: 4	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: oslashacute	Contours detected: 5	Expected: 4

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: quotedblbase	Contours detected: 4	Expected: 2

	- Glyph name: quotedblleft	Contours detected: 4	Expected: 2

	- Glyph name: quotedblright	Contours detected: 4	Expected: 2

	- Glyph name: quoteleft	Contours detected: 2	Expected: 1

	- Glyph name: quoteright	Contours detected: 2	Expected: 1

	- Glyph name: quotesinglbase	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 5	Expected: 2

	- Glyph name: rcaron	Contours detected: 5	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: semicolon	Contours detected: 3	Expected: 2

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: tcaron	Contours detected: 3	Expected: 2

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: threequarters	Contours detected: 5	Expected: 3or4

	- Glyph name: trademark	Contours detected: 4	Expected: 2

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uni0122	Contours detected: 4	Expected: 2

	- Glyph name: uni0136	Contours detected: 4	Expected: 2or3

	- Glyph name: uni0137	Contours detected: 4	Expected: 2or3

	- Glyph name: uni013B	Contours detected: 4	Expected: 2

	- Glyph name: uni013C	Contours detected: 4	Expected: 2

	- Glyph name: uni0145	Contours detected: 4	Expected: 2

	- Glyph name: uni0146	Contours detected: 4	Expected: 2

	- Glyph name: uni0156	Contours detected: 5	Expected: 3

	- Glyph name: uni0157	Contours detected: 5	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: uni0218	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni021A	Contours detected: 3	Expected: 2

	- Glyph name: uni021B	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni0302	Contours detected: 2	Expected: 1

	- Glyph name: uni030C	Contours detected: 2	Expected: 1

	- Glyph name: uni0312	Contours detected: 2	Expected: 1

	- Glyph name: uni0326	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 4	Expected: 2

	- Glyph name: uni1E14	Contours detected: 5	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E16	Contours detected: 5	Expected: 3

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2E	Contours detected: 5	Expected: 4

	- Glyph name: uni1E2F	Contours detected: 5	Expected: 4

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 5	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 5	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 5	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 4	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 4	Expected: 2

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: zacute	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[8] Nemoy-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2825, but got 1900 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 875, but got 560 instead [code: descent]
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

	- IJacute
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: eight	Contours detected: 4	Expected: 3

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: uni00B2	Contours detected: 2	Expected: 1

	- Glyph name: uni00B3	Contours detected: 2	Expected: 1

	- Glyph name: uni00B9	Contours detected: 2	Expected: 1

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: threequarters	Contours detected: 5	Expected: 3or4

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ntilde	Contours detected: 3	Expected: 2

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 3	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: Ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: racute	Contours detected: 4	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 4	Expected: 2

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: rcaron	Contours detected: 4	Expected: 2

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Zacute	Contours detected: 3	Expected: 2

	- Glyph name: zacute	Contours detected: 3	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Zcaron	Contours detected: 3	Expected: 2

	- Glyph name: zcaron	Contours detected: 3	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: Gcaron	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 5	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 4	Expected: 3

	- Glyph name: uni1E16	Contours detected: 4	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: Lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: Nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: rmacronbelow	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: trademark	Contours detected: 4	Expected: 2

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: AEacute	Contours detected: 5	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gcaron	Contours detected: 3	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 3	Expected: 2

	- Glyph name: Ncaron	Contours detected: 3	Expected: 2

	- Glyph name: Ntilde	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: Zacute	Contours detected: 3	Expected: 2

	- Glyph name: Zcaron	Contours detected: 3	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: eight	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 4	Expected: 2

	- Glyph name: rcaron	Contours detected: 4	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: three	Contours detected: 2	Expected: 1

	- Glyph name: threequarters	Contours detected: 5	Expected: 3or4

	- Glyph name: trademark	Contours detected: 4	Expected: 2

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 4	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 4	Expected: 3

	- Glyph name: uni1E16	Contours detected: 4	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: zacute	Contours detected: 3	Expected: 2

	- Glyph name: zcaron	Contours detected: 3	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<1874.0,706.0>--<2511.0,705.0>>

	* AE (U+00C6): L<<2511.0,572.0>--<1658.0,573.0>>

	* AEacute (U+01FC): L<<1874.0,706.0>--<2511.0,705.0>>

	* AEacute (U+01FC): L<<2511.0,572.0>--<1658.0,573.0>>

	* E (U+0045): L<<1126.0,572.0>--<273.0,573.0>>

	* E (U+0045): L<<489.0,706.0>--<1126.0,705.0>>

	* Eacute (U+00C9): L<<1126.0,572.0>--<273.0,573.0>>

	* Eacute (U+00C9): L<<489.0,706.0>--<1126.0,705.0>>

	* Ebreve (U+0114): L<<1126.0,572.0>--<273.0,573.0>>

	* Ebreve (U+0114): L<<489.0,706.0>--<1126.0,705.0>>

	* Ecaron (U+011A): L<<1126.0,572.0>--<273.0,573.0>>

	* Ecaron (U+011A): L<<489.0,706.0>--<1126.0,705.0>>

	* Ecircumflex (U+00CA): L<<1126.0,572.0>--<273.0,573.0>>

	* Ecircumflex (U+00CA): L<<489.0,706.0>--<1126.0,705.0>>

	* Edieresis (U+00CB): L<<1126.0,572.0>--<273.0,573.0>>

	* Edieresis (U+00CB): L<<489.0,706.0>--<1126.0,705.0>>

	* Edotaccent (U+0116): L<<1126.0,572.0>--<273.0,573.0>>

	* Edotaccent (U+0116): L<<489.0,706.0>--<1126.0,705.0>>

	* Egrave (U+00C8): L<<1126.0,572.0>--<273.0,573.0>>

	* Egrave (U+00C8): L<<489.0,706.0>--<1126.0,705.0>>

	* Emacron (U+0112): L<<1126.0,572.0>--<273.0,573.0>>

	* Emacron (U+0112): L<<489.0,706.0>--<1126.0,705.0>>

	* Eogonek (U+0118): L<<1126.0,572.0>--<273.0,573.0>>

	* Eogonek (U+0118): L<<489.0,706.0>--<1126.0,705.0>>

	* F (U+0046): L<<1106.0,578.0>--<273.0,577.0>>

	* OE (U+0152): L<<1920.0,706.0>--<2557.0,705.0>>

	* OE (U+0152): L<<2557.0,572.0>--<1704.0,573.0>>

	* ae (U+00E6): L<<1874.0,706.0>--<2511.0,705.0>>

	* ae (U+00E6): L<<2511.0,572.0>--<1658.0,573.0>>

	* aeacute (U+01FD): L<<1874.0,706.0>--<2511.0,705.0>>

	* aeacute (U+01FD): L<<2511.0,572.0>--<1658.0,573.0>>

	* asterisk (U+002A): L<<499.0,1352.0>--<498.0,1206.0>>

	* e (U+0065): L<<1126.0,572.0>--<273.0,573.0>>

	* e (U+0065): L<<489.0,706.0>--<1126.0,705.0>>

	* eacute (U+00E9): L<<1126.0,572.0>--<273.0,573.0>>

	* eacute (U+00E9): L<<489.0,706.0>--<1126.0,705.0>>

	* ebreve (U+0115): L<<1126.0,572.0>--<273.0,573.0>>

	* ebreve (U+0115): L<<489.0,706.0>--<1126.0,705.0>>

	* ecaron (U+011B): L<<1126.0,572.0>--<273.0,573.0>>

	* ecaron (U+011B): L<<489.0,706.0>--<1126.0,705.0>>

	* ecircumflex (U+00EA): L<<1126.0,572.0>--<273.0,573.0>>

	* ecircumflex (U+00EA): L<<489.0,706.0>--<1126.0,705.0>>

	* edieresis (U+00EB): L<<1126.0,572.0>--<273.0,573.0>>

	* edieresis (U+00EB): L<<489.0,706.0>--<1126.0,705.0>>

	* edotaccent (U+0117): L<<1126.0,572.0>--<273.0,573.0>>

	* edotaccent (U+0117): L<<489.0,706.0>--<1126.0,705.0>>

	* egrave (U+00E8): L<<1126.0,572.0>--<273.0,573.0>>

	* egrave (U+00E8): L<<489.0,706.0>--<1126.0,705.0>>

	* emacron (U+0113): L<<1126.0,572.0>--<273.0,573.0>>

	* emacron (U+0113): L<<489.0,706.0>--<1126.0,705.0>>

	* eogonek (U+0119): L<<1126.0,572.0>--<273.0,573.0>>

	* eogonek (U+0119): L<<489.0,706.0>--<1126.0,705.0>>

	* f (U+0066): L<<1106.0,578.0>--<273.0,577.0>>

	* oe (U+0153): L<<1920.0,706.0>--<2557.0,705.0>>

	* oe (U+0153): L<<2557.0,572.0>--<1704.0,573.0>>

	* one (U+0031): L<<429.0,133.0>--<430.0,1008.0>>

	* onehalf (U+00BD): L<<373.0,1281.0>--<372.0,474.0>>

	* onequarter (U+00BC): L<<373.0,1281.0>--<372.0,474.0>>

	* uni1E14 (U+1E14): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1E14 (U+1E14): L<<489.0,706.0>--<1126.0,705.0>>

	* uni1E15 (U+1E15): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1E15 (U+1E15): L<<489.0,706.0>--<1126.0,705.0>>

	* uni1E16 (U+1E16): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1E16 (U+1E16): L<<489.0,706.0>--<1126.0,705.0>>

	* uni1E17 (U+1E17): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1E17 (U+1E17): L<<489.0,706.0>--<1126.0,705.0>>

	* uni1E1C (U+1E1C): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1E1C (U+1E1C): L<<489.0,706.0>--<1126.0,705.0>>

	* uni1E1D (U+1E1D): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1E1D (U+1E1D): L<<489.0,706.0>--<1126.0,705.0>>

	* uni1EB8 (U+1EB8): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1EB8 (U+1EB8): L<<489.0,706.0>--<1126.0,705.0>>

	* uni1EB9 (U+1EB9): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1EB9 (U+1EB9): L<<489.0,706.0>--<1126.0,705.0>>

	* uni1EBC (U+1EBC): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1EBC (U+1EBC): L<<489.0,706.0>--<1126.0,705.0>>

	* uni1EBD (U+1EBD): L<<1126.0,572.0>--<273.0,573.0>>

	* uni1EBD (U+1EBD): L<<489.0,706.0>--<1126.0,705.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[9] Nemoy-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2825, but got 1900 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 875, but got 560 instead [code: descent]
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

	- IJacute
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: uni00B2	Contours detected: 2	Expected: 1

	- Glyph name: uni00B9	Contours detected: 2	Expected: 1

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ntilde	Contours detected: 3	Expected: 2

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 3	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: Ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: racute	Contours detected: 4	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 4	Expected: 2

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: rcaron	Contours detected: 4	Expected: 2

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Zacute	Contours detected: 3	Expected: 2

	- Glyph name: zacute	Contours detected: 3	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Zcaron	Contours detected: 3	Expected: 2

	- Glyph name: zcaron	Contours detected: 3	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: Gcaron	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 5	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 4	Expected: 3

	- Glyph name: uni1E16	Contours detected: 4	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: Lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: Nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: rmacronbelow	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: AEacute	Contours detected: 5	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gcaron	Contours detected: 3	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 3	Expected: 2

	- Glyph name: Ncaron	Contours detected: 3	Expected: 2

	- Glyph name: Ntilde	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: Zacute	Contours detected: 3	Expected: 2

	- Glyph name: Zcaron	Contours detected: 3	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 4	Expected: 2

	- Glyph name: rcaron	Contours detected: 4	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 4	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 4	Expected: 3

	- Glyph name: uni1E16	Contours detected: 4	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 3	Expected: 2

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: zacute	Contours detected: 3	Expected: 2

	- Glyph name: zcaron	Contours detected: 3	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* G (U+0047): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* G (U+0047): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* Gbreve (U+011E): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* Gbreve (U+011E): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* Gcaron (U+01E6): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* Gcaron (U+01E6): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* Gcircumflex (U+011C): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* Gcircumflex (U+011C): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* Gdotaccent (U+0120): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* Gdotaccent (U+0120): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* IJ (U+0132): L<<2075.0,1416.0>--<2075.0,503.0>> -> L<<2075.0,503.0>--<2075.0,502.0>>

	* J (U+004A): L<<1164.0,1416.0>--<1164.0,503.0>> -> L<<1164.0,503.0>--<1164.0,502.0>>

	* Jcircumflex (U+0134): L<<1164.0,1416.0>--<1164.0,503.0>> -> L<<1164.0,503.0>--<1164.0,502.0>>

	* dollar (U+0024): L<<805.0,0.0>--<805.0,-1.0>> -> L<<805.0,-1.0>--<802.0,-263.0>>

	* g (U+0067): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* g (U+0067): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* gbreve (U+011F): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* gbreve (U+011F): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* gcaron (U+01E7): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* gcaron (U+01E7): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* gcircumflex (U+011D): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* gcircumflex (U+011D): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* gdotaccent (U+0121): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* gdotaccent (U+0121): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* ij (U+0133): L<<2075.0,1416.0>--<2075.0,503.0>> -> L<<2075.0,503.0>--<2075.0,502.0>>

	* integral (U+222B): L<<327.0,78.0>--<449.0,623.0>> -> L<<449.0,623.0>--<571.0,1169.0>>

	* integral (U+222B): L<<825.0,1113.0>--<703.0,567.0>> -> L<<703.0,567.0>--<581.0,22.0>>

	* j (U+006A): L<<1164.0,1416.0>--<1164.0,503.0>> -> L<<1164.0,503.0>--<1164.0,502.0>>

	* jcircumflex (U+0135): L<<1164.0,1416.0>--<1164.0,503.0>> -> L<<1164.0,503.0>--<1164.0,502.0>>

	* section (U+00A7): L<<710.0,280.0>--<715.0,280.0>> -> L<<715.0,280.0>--<1049.0,280.0>>

	* uni0122 (U+0122): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* uni0122 (U+0122): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* uni0123 (U+0123): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* uni0123 (U+0123): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* uni0237 (U+0237): L<<1164.0,1416.0>--<1164.0,503.0>> -> L<<1164.0,503.0>--<1164.0,502.0>>

	* uni1E20 (U+1E20): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* uni1E20 (U+1E20): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>>

	* uni1E21 (U+1E21): L<<1699.0,758.0>--<1699.0,757.0>> -> L<<1699.0,757.0>--<1699.0,756.0>>

	* uni1E21 (U+1E21): L<<1699.0,759.0>--<1699.0,758.0>> -> L<<1699.0,758.0>--<1699.0,757.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<2431.0,565.0>--<1660.0,568.0>>

	* AEacute (U+01FC): L<<2431.0,565.0>--<1660.0,568.0>>

	* E (U+0045): L<<1191.0,565.0>--<420.0,568.0>>

	* Eacute (U+00C9): L<<1191.0,565.0>--<420.0,568.0>>

	* Ebreve (U+0114): L<<1191.0,565.0>--<420.0,568.0>>

	* Ecaron (U+011A): L<<1191.0,565.0>--<420.0,568.0>>

	* Ecircumflex (U+00CA): L<<1191.0,565.0>--<420.0,568.0>>

	* Edieresis (U+00CB): L<<1191.0,565.0>--<420.0,568.0>>

	* Edotaccent (U+0116): L<<1191.0,565.0>--<420.0,568.0>>

	* Egrave (U+00C8): L<<1191.0,565.0>--<420.0,568.0>>

	* Emacron (U+0112): L<<1191.0,565.0>--<420.0,568.0>>

	* Eogonek (U+0118): L<<1191.0,565.0>--<420.0,568.0>>

	* F (U+0046): L<<1128.0,577.0>--<420.0,574.0>>

	* OE (U+0152): L<<2478.0,565.0>--<1707.0,568.0>>

	* ae (U+00E6): L<<2431.0,565.0>--<1660.0,568.0>>

	* aeacute (U+01FD): L<<2431.0,565.0>--<1660.0,568.0>>

	* e (U+0065): L<<1191.0,565.0>--<420.0,568.0>>

	* eacute (U+00E9): L<<1191.0,565.0>--<420.0,568.0>>

	* ebreve (U+0115): L<<1191.0,565.0>--<420.0,568.0>>

	* ecaron (U+011B): L<<1191.0,565.0>--<420.0,568.0>>

	* ecircumflex (U+00EA): L<<1191.0,565.0>--<420.0,568.0>>

	* edieresis (U+00EB): L<<1191.0,565.0>--<420.0,568.0>>

	* edotaccent (U+0117): L<<1191.0,565.0>--<420.0,568.0>>

	* egrave (U+00E8): L<<1191.0,565.0>--<420.0,568.0>>

	* emacron (U+0113): L<<1191.0,565.0>--<420.0,568.0>>

	* eogonek (U+0119): L<<1191.0,565.0>--<420.0,568.0>>

	* f (U+0066): L<<1128.0,577.0>--<420.0,574.0>>

	* oe (U+0153): L<<2478.0,565.0>--<1707.0,568.0>>

	* one (U+0031): L<<426.0,280.0>--<427.0,901.0>>

	* one (U+0031): L<<707.0,1367.0>--<706.0,280.0>>

	* onehalf (U+00BD): L<<322.0,563.0>--<323.0,939.0>>

	* onehalf (U+00BD): L<<493.0,1222.0>--<492.0,563.0>>

	* onequarter (U+00BC): L<<322.0,563.0>--<323.0,939.0>>

	* onequarter (U+00BC): L<<493.0,1222.0>--<492.0,563.0>>

	* uni00B9 (U+00B9): L<<258.0,563.0>--<259.0,939.0>>

	* uni00B9 (U+00B9): L<<429.0,1222.0>--<428.0,563.0>>

	* uni1E14 (U+1E14): L<<1191.0,565.0>--<420.0,568.0>>

	* uni1E15 (U+1E15): L<<1191.0,565.0>--<420.0,568.0>>

	* uni1E16 (U+1E16): L<<1191.0,565.0>--<420.0,568.0>>

	* uni1E17 (U+1E17): L<<1191.0,565.0>--<420.0,568.0>>

	* uni1E1C (U+1E1C): L<<1191.0,565.0>--<420.0,568.0>>

	* uni1E1D (U+1E1D): L<<1191.0,565.0>--<420.0,568.0>>

	* uni1EB8 (U+1EB8): L<<1191.0,565.0>--<420.0,568.0>>

	* uni1EB9 (U+1EB9): L<<1191.0,565.0>--<420.0,568.0>>

	* uni1EBC (U+1EBC): L<<1191.0,565.0>--<420.0,568.0>>

	* uni1EBD (U+1EBD): L<<1191.0,565.0>--<420.0,568.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[8] Nemoy-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2825, but got 1900 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 875, but got 560 instead [code: descent]
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

	- IJacute
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: uni00B2	Contours detected: 2	Expected: 1

	- Glyph name: uni00B9	Contours detected: 2	Expected: 1

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ntilde	Contours detected: 4	Expected: 2

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: ntilde	Contours detected: 4	Expected: 2

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: Itilde	Contours detected: 3	Expected: 2

	- Glyph name: itilde	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 3	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: Ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: racute	Contours detected: 4	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 4	Expected: 2

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: rcaron	Contours detected: 4	Expected: 2

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Zacute	Contours detected: 3	Expected: 2

	- Glyph name: zacute	Contours detected: 3	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Zcaron	Contours detected: 3	Expected: 2

	- Glyph name: zcaron	Contours detected: 3	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: Gcaron	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 5	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: tilde	Contours detected: 2	Expected: 1

	- Glyph name: tildecomb	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 4	Expected: 3

	- Glyph name: uni1E16	Contours detected: 4	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: Lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: Nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: rmacronbelow	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 4	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: trademark	Contours detected: 4	Expected: 2

	- Glyph name: AE	Contours detected: 4	Expected: 2

	- Glyph name: AEacute	Contours detected: 5	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Eng	Contours detected: 2	Expected: 1

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1or2

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: Gcaron	Contours detected: 3	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 4	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

	- Glyph name: Itilde	Contours detected: 3	Expected: 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Ldot	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: N	Contours detected: 2	Expected: 1

	- Glyph name: Nacute	Contours detected: 3	Expected: 2

	- Glyph name: Ncaron	Contours detected: 3	Expected: 2

	- Glyph name: Ntilde	Contours detected: 4	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: W	Contours detected: 3	Expected: 1or2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: Z	Contours detected: 2	Expected: 1

	- Glyph name: Zacute	Contours detected: 3	Expected: 2

	- Glyph name: Zcaron	Contours detected: 3	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3or5

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: five	Contours detected: 2	Expected: 1

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: hbar	Contours detected: 4	Expected: 1

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: i	Contours detected: 1	Expected: 2

	- Glyph name: itilde	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: ldot	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: onehalf	Contours detected: 5	Expected: 3

	- Glyph name: onequarter	Contours detected: 5	Expected: 3or4

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: q	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 3	Expected: 2

	- Glyph name: questiondown	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 4	Expected: 2

	- Glyph name: rcaron	Contours detected: 4	Expected: 2

	- Glyph name: registered	Contours detected: 5	Expected: 3or4

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: section	Contours detected: 5	Expected: 2

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: sterling	Contours detected: 3	Expected: 1or2

	- Glyph name: tilde	Contours detected: 2	Expected: 1

	- Glyph name: trademark	Contours detected: 4	Expected: 2

	- Glyph name: two	Contours detected: 2	Expected: 1

	- Glyph name: uni0122	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0145	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 4	Expected: 2

	- Glyph name: uni019D	Contours detected: 2	Expected: 1

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E14	Contours detected: 4	Expected: 3

	- Glyph name: uni1E16	Contours detected: 4	Expected: 3

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E20	Contours detected: 3	Expected: 2

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E37	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 4	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E44	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E46	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 4	Expected: 2

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 3	Expected: 2

	- Glyph name: uni1E93	Contours detected: 3	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uni1EB8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECB	Contours detected: 2	Expected: 3

	- Glyph name: uni1EF8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 4	Expected: 2

	- Glyph name: uni2116	Contours detected: 5	Expected: 3or4

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: zacute	Contours detected: 3	Expected: 2

	- Glyph name: zcaron	Contours detected: 3	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<2003.0,778.0>--<2471.0,775.0>>

	* AE (U+00C6): L<<2471.0,568.0>--<1660.0,570.0>>

	* AEacute (U+01FC): L<<2003.0,778.0>--<2471.0,775.0>>

	* AEacute (U+01FC): L<<2471.0,568.0>--<1660.0,570.0>>

	* E (U+0045): L<<1158.0,568.0>--<347.0,570.0>>

	* E (U+0045): L<<690.0,778.0>--<1158.0,775.0>>

	* Eacute (U+00C9): L<<1158.0,568.0>--<347.0,570.0>>

	* Eacute (U+00C9): L<<690.0,778.0>--<1158.0,775.0>>

	* Ebreve (U+0114): L<<1158.0,568.0>--<347.0,570.0>>

	* Ebreve (U+0114): L<<690.0,778.0>--<1158.0,775.0>>

	* Ecaron (U+011A): L<<1158.0,568.0>--<347.0,570.0>>

	* Ecaron (U+011A): L<<690.0,778.0>--<1158.0,775.0>>

	* Ecircumflex (U+00CA): L<<1158.0,568.0>--<347.0,570.0>>

	* Ecircumflex (U+00CA): L<<690.0,778.0>--<1158.0,775.0>>

	* Edieresis (U+00CB): L<<1158.0,568.0>--<347.0,570.0>>

	* Edieresis (U+00CB): L<<690.0,778.0>--<1158.0,775.0>>

	* Edotaccent (U+0116): L<<1158.0,568.0>--<347.0,570.0>>

	* Edotaccent (U+0116): L<<690.0,778.0>--<1158.0,775.0>>

	* Egrave (U+00C8): L<<1158.0,568.0>--<347.0,570.0>>

	* Egrave (U+00C8): L<<690.0,778.0>--<1158.0,775.0>>

	* Emacron (U+0112): L<<1158.0,568.0>--<347.0,570.0>>

	* Emacron (U+0112): L<<690.0,778.0>--<1158.0,775.0>>

	* Eogonek (U+0118): L<<1158.0,568.0>--<347.0,570.0>>

	* Eogonek (U+0118): L<<690.0,778.0>--<1158.0,775.0>>

	* F (U+0046): L<<1117.0,577.0>--<347.0,575.0>>

	* OE (U+0152): L<<2049.0,778.0>--<2517.0,775.0>>

	* OE (U+0152): L<<2517.0,568.0>--<1706.0,570.0>>

	* ae (U+00E6): L<<2003.0,778.0>--<2471.0,775.0>>

	* ae (U+00E6): L<<2471.0,568.0>--<1660.0,570.0>>

	* aeacute (U+01FD): L<<2003.0,778.0>--<2471.0,775.0>>

	* aeacute (U+01FD): L<<2471.0,568.0>--<1660.0,570.0>>

	* e (U+0065): L<<1158.0,568.0>--<347.0,570.0>>

	* e (U+0065): L<<690.0,778.0>--<1158.0,775.0>>

	* eacute (U+00E9): L<<1158.0,568.0>--<347.0,570.0>>

	* eacute (U+00E9): L<<690.0,778.0>--<1158.0,775.0>>

	* ebreve (U+0115): L<<1158.0,568.0>--<347.0,570.0>>

	* ebreve (U+0115): L<<690.0,778.0>--<1158.0,775.0>>

	* ecaron (U+011B): L<<1158.0,568.0>--<347.0,570.0>>

	* ecaron (U+011B): L<<690.0,778.0>--<1158.0,775.0>>

	* ecircumflex (U+00EA): L<<1158.0,568.0>--<347.0,570.0>>

	* ecircumflex (U+00EA): L<<690.0,778.0>--<1158.0,775.0>>

	* edieresis (U+00EB): L<<1158.0,568.0>--<347.0,570.0>>

	* edieresis (U+00EB): L<<690.0,778.0>--<1158.0,775.0>>

	* edotaccent (U+0117): L<<1158.0,568.0>--<347.0,570.0>>

	* edotaccent (U+0117): L<<690.0,778.0>--<1158.0,775.0>>

	* egrave (U+00E8): L<<1158.0,568.0>--<347.0,570.0>>

	* egrave (U+00E8): L<<690.0,778.0>--<1158.0,775.0>>

	* emacron (U+0113): L<<1158.0,568.0>--<347.0,570.0>>

	* emacron (U+0113): L<<690.0,778.0>--<1158.0,775.0>>

	* eogonek (U+0119): L<<1158.0,568.0>--<347.0,570.0>>

	* eogonek (U+0119): L<<690.0,778.0>--<1158.0,775.0>>

	* f (U+0066): L<<1117.0,577.0>--<347.0,575.0>>

	* oe (U+0153): L<<2049.0,778.0>--<2517.0,775.0>>

	* oe (U+0153): L<<2517.0,568.0>--<1706.0,570.0>>

	* one (U+0031): L<<635.0,1416.0>--<634.0,207.0>>

	* onehalf (U+00BD): L<<433.0,1251.0>--<432.0,518.0>>

	* onequarter (U+00BC): L<<433.0,1251.0>--<432.0,518.0>>

	* uni00B9 (U+00B9): L<<259.0,518.0>--<260.0,971.0>>

	* uni00B9 (U+00B9): L<<385.0,1251.0>--<384.0,518.0>>

	* uni1E14 (U+1E14): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1E14 (U+1E14): L<<690.0,778.0>--<1158.0,775.0>>

	* uni1E15 (U+1E15): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1E15 (U+1E15): L<<690.0,778.0>--<1158.0,775.0>>

	* uni1E16 (U+1E16): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1E16 (U+1E16): L<<690.0,778.0>--<1158.0,775.0>>

	* uni1E17 (U+1E17): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1E17 (U+1E17): L<<690.0,778.0>--<1158.0,775.0>>

	* uni1E1C (U+1E1C): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1E1C (U+1E1C): L<<690.0,778.0>--<1158.0,775.0>>

	* uni1E1D (U+1E1D): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1E1D (U+1E1D): L<<690.0,778.0>--<1158.0,775.0>>

	* uni1EB8 (U+1EB8): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1EB8 (U+1EB8): L<<690.0,778.0>--<1158.0,775.0>>

	* uni1EB9 (U+1EB9): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1EB9 (U+1EB9): L<<690.0,778.0>--<1158.0,775.0>>

	* uni1EBC (U+1EBC): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1EBC (U+1EBC): L<<690.0,778.0>--<1158.0,775.0>>

	* uni1EBD (U+1EBD): L<<1158.0,568.0>--<347.0,570.0>>

	* uni1EBD (U+1EBD): L<<690.0,778.0>--<1158.0,775.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 5 | 35 | 602 | 31 | 509 | 0 |
| 0% | 0% | 3% | 51% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
