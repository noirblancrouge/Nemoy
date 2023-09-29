## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[7] Nemoy-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=847.0,Y=1.5 (should be at baseline 0?)

	* at (U+0040): X=710.5,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=540.5,Y=-2.0 (should be at baseline 0?)

	* V (U+0056): X=430.5,Y=-2.0 (should be at baseline 0?)

	* V (U+0056): X=349.5,Y=-2.0 (should be at baseline 0?)

	* g (U+0067): X=540.5,Y=-2.0 (should be at baseline 0?)

	* v (U+0076): X=430.5,Y=-2.0 (should be at baseline 0?)

	* v (U+0076): X=349.5,Y=-2.0 (should be at baseline 0?)

	* exclamdown (U+00A1): X=127.0,Y=750.0 (should be at cap-height 751?)

	* exclamdown (U+00A1): X=234.0,Y=750.0 (should be at cap-height 751?)

	* exclamdown (U+00A1): X=127.0,Y=750.0 (should be at cap-height 751?)

	* ordmasculine (U+00BA): X=131.5,Y=750.5 (should be at cap-height 751?)

	* ordmasculine (U+00BA): X=283.5,Y=750.5 (should be at cap-height 751?)

	* questiondown (U+00BF): X=414.0,Y=1.5 (should be at baseline 0?)

	* questiondown (U+00BF): X=370.0,Y=753.0 (should be at cap-height 751?)

	* questiondown (U+00BF): X=263.0,Y=753.0 (should be at cap-height 751?)

	* questiondown (U+00BF): X=370.0,Y=753.0 (should be at cap-height 751?)

	* Gcircumflex (U+011C): X=540.5,Y=-2.0 (should be at baseline 0?)

	* gcircumflex (U+011D): X=540.5,Y=-2.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=540.5,Y=-2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=540.5,Y=-2.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=540.5,Y=-2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=540.5,Y=-2.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=540.5,Y=-2.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=540.5,Y=-2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=299.0,Y=-249.0 (should be at descender -250?)

	* scedilla (U+015F): X=299.0,Y=-249.0 (should be at descender -250?)

	* uni0162 (U+0162): X=343.0,Y=-249.0 (should be at descender -250?)

	* uni0163 (U+0163): X=343.0,Y=-249.0 (should be at descender -250?)

	* Uogonek (U+0172): X=292.0,Y=-248.5 (should be at descender -250?)

	* Uogonek (U+0172): X=491.0,Y=-2.0 (should be at baseline 0?)

	* uogonek (U+0173): X=292.0,Y=-248.5 (should be at descender -250?)

	* uogonek (U+0173): X=491.0,Y=-2.0 (should be at baseline 0?)

	* Gcaron (U+01E6): X=540.5,Y=-2.0 (should be at baseline 0?)

	* gcaron (U+01E7): X=540.5,Y=-2.0 (should be at baseline 0?)

	* breve (U+02D8): X=173.0,Y=752.0 (should be at cap-height 751?)

	* breve (U+02D8): X=193.0,Y=752.0 (should be at cap-height 751?)

	* uni0306 (U+0306): X=173.0,Y=752.0 (should be at cap-height 751?)

	* uni0306 (U+0306): X=193.0,Y=752.0 (should be at cap-height 751?)

	* uni0331 (U+0331): X=103.0,Y=-248.0 (should be at descender -250?)

	* uni0331 (U+0331): X=238.0,Y=-248.0 (should be at descender -250?)

	* uni03A9 (U+03A9): X=371.0,Y=750.0 (should be at cap-height 751?)

	* uni03BC (U+03BC): X=310.5,Y=-1.0 (should be at baseline 0?)

	* Dmacronbelow (U+1E0E): X=309.0,Y=-248.0 (should be at descender -250?)

	* Dmacronbelow (U+1E0E): X=444.0,Y=-248.0 (should be at descender -250?)

	* dmacronbelow (U+1E0F): X=309.0,Y=-248.0 (should be at descender -250?)

	* dmacronbelow (U+1E0F): X=444.0,Y=-248.0 (should be at descender -250?)

	* uni1E1C (U+1E1C): X=325.0,Y=-249.0 (should be at descender -250?)

	* uni1E1D (U+1E1D): X=325.0,Y=-249.0 (should be at descender -250?)

	* uni1E20 (U+1E20): X=540.5,Y=-2.0 (should be at baseline 0?)

	* uni1E21 (U+1E21): X=540.5,Y=-2.0 (should be at baseline 0?)

	* Lmacronbelow (U+1E3A): X=253.0,Y=-248.0 (should be at descender -250?)

	* Lmacronbelow (U+1E3A): X=388.0,Y=-248.0 (should be at descender -250?)

	* lmacronbelow (U+1E3B): X=253.0,Y=-248.0 (should be at descender -250?)

	* lmacronbelow (U+1E3B): X=388.0,Y=-248.0 (should be at descender -250?)

	* Nmacronbelow (U+1E48): X=328.0,Y=-248.0 (should be at descender -250?)

	* Nmacronbelow (U+1E48): X=463.0,Y=-248.0 (should be at descender -250?)

	* nmacronbelow (U+1E49): X=328.0,Y=-248.0 (should be at descender -250?)

	* nmacronbelow (U+1E49): X=463.0,Y=-248.0 (should be at descender -250?)

	* uni1E4C (U+1E4C): X=576.0,Y=1251.0 (should be at ascender 1250?)

	* uni1E4C (U+1E4C): X=576.0,Y=1249.0 (should be at ascender 1250?)

	* uni1E4D (U+1E4D): X=576.0,Y=1251.0 (should be at ascender 1250?)

	* uni1E4D (U+1E4D): X=576.0,Y=1249.0 (should be at ascender 1250?)

	* Rmacronbelow (U+1E5E): X=282.0,Y=-248.0 (should be at descender -250?)

	* Rmacronbelow (U+1E5E): X=417.0,Y=-248.0 (should be at descender -250?)

	* rmacronbelow (U+1E5F): X=282.0,Y=-248.0 (should be at descender -250?)

	* rmacronbelow (U+1E5F): X=417.0,Y=-248.0 (should be at descender -250?)

	* Tmacronbelow (U+1E6E): X=296.0,Y=-248.0 (should be at descender -250?)

	* Tmacronbelow (U+1E6E): X=431.0,Y=-248.0 (should be at descender -250?)

	* tmacronbelow (U+1E6F): X=296.0,Y=-248.0 (should be at descender -250?)

	* tmacronbelow (U+1E6F): X=431.0,Y=-248.0 (should be at descender -250?)

	* uni1E78 (U+1E78): X=526.0,Y=1251.0 (should be at ascender 1250?)

	* uni1E78 (U+1E78): X=526.0,Y=1249.0 (should be at ascender 1250?)

	* uni1E79 (U+1E79): X=526.0,Y=1251.0 (should be at ascender 1250?)

	* uni1E79 (U+1E79): X=526.0,Y=1249.0 (should be at ascender 1250?)

	* dagger (U+2020): X=309.0,Y=-2.0 (should be at baseline 0?)

	* daggerdbl (U+2021): X=309.0,Y=-2.0 (should be at baseline 0?)

	* uniE000 (U+E000): X=0.0,Y=752.0 (should be at cap-height 751?)

	* uniE000 (U+E000): X=752.0,Y=752.0 (should be at cap-height 751?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* IJ (U+0132): L<<1013.0,691.0>--<1013.0,246.0>> -> L<<1013.0,246.0>--<1013.0,245.0>>

	* IJacute (U+E133): L<<1013.0,691.0>--<1013.0,246.0>> -> L<<1013.0,246.0>--<1013.0,245.0>>

	* J (U+004A): L<<568.0,691.0>--<568.0,246.0>> -> L<<568.0,246.0>--<568.0,245.0>>

	* Jcircumflex (U+0134): L<<568.0,691.0>--<568.0,246.0>> -> L<<568.0,246.0>--<568.0,245.0>>

	* fi (U+FB01): L<<128.0,751.0>--<630.0,751.0>> -> L<<630.0,751.0>--<631.0,751.0>>

	* fi (U+FB01): L<<630.0,751.0>--<631.0,751.0>> -> L<<631.0,751.0>--<631.0,751.0>>

	* fi (U+FB01): L<<631.0,751.0>--<631.0,751.0>> -> L<<631.0,751.0>--<895.0,751.0>>

	* fi (U+FB01): L<<694.0,614.0>--<631.0,614.0>> -> L<<631.0,614.0>--<630.0,614.0>>

	* ij (U+0133): L<<1013.0,691.0>--<1013.0,246.0>> -> L<<1013.0,246.0>--<1013.0,245.0>>

	* ijacute (U+E134): L<<1013.0,691.0>--<1013.0,246.0>> -> L<<1013.0,246.0>--<1013.0,245.0>>

	* integral (U+222B): L<<160.0,38.0>--<219.0,304.0>> -> L<<219.0,304.0>--<279.0,571.0>>

	* integral (U+222B): L<<403.0,543.0>--<343.0,277.0>> -> L<<343.0,277.0>--<284.0,11.0>>

	* j (U+006A): L<<568.0,691.0>--<568.0,246.0>> -> L<<568.0,246.0>--<568.0,245.0>>

	* jcircumflex (U+0135): L<<568.0,691.0>--<568.0,246.0>> -> L<<568.0,246.0>--<568.0,245.0>>

	* section (U+00A7): L<<347.0,137.0>--<349.0,137.0>> -> L<<349.0,137.0>--<512.0,137.0>>

	* uni0237 (U+0237): L<<568.0,691.0>--<568.0,246.0>> -> L<<568.0,246.0>--<568.0,245.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<1187.0,276.0>--<810.0,277.0>>

	* AEacute (U+01FC): L<<1187.0,276.0>--<810.0,277.0>>

	* E (U+0045): L<<582.0,276.0>--<205.0,277.0>>

	* Eacute (U+00C9): L<<582.0,276.0>--<205.0,277.0>>

	* Ebreve (U+0114): L<<582.0,276.0>--<205.0,277.0>>

	* Ecaron (U+011A): L<<582.0,276.0>--<205.0,277.0>>

	* Ecircumflex (U+00CA): L<<582.0,276.0>--<205.0,277.0>>

	* Edieresis (U+00CB): L<<582.0,276.0>--<205.0,277.0>>

	* Edotaccent (U+0116): L<<582.0,276.0>--<205.0,277.0>>

	* Egrave (U+00C8): L<<582.0,276.0>--<205.0,277.0>>

	* Emacron (U+0112): L<<582.0,276.0>--<205.0,277.0>>

	* Eogonek (U+0118): L<<582.0,276.0>--<205.0,277.0>>

	* F (U+0046): L<<551.0,282.0>--<205.0,281.0>>

	* OE (U+0152): L<<1210.0,276.0>--<833.0,277.0>>

	* ae (U+00E6): L<<1187.0,276.0>--<810.0,277.0>>

	* aeacute (U+01FD): L<<1187.0,276.0>--<810.0,277.0>>

	* dollar (U+0024): L<<255.0,-126.0>--<256.0,0.0>>

	* dollar (U+0024): L<<393.0,0.0>--<392.0,-128.0>>

	* e (U+0065): L<<582.0,276.0>--<205.0,277.0>>

	* eacute (U+00E9): L<<582.0,276.0>--<205.0,277.0>>

	* ebreve (U+0115): L<<582.0,276.0>--<205.0,277.0>>

	* ecaron (U+011B): L<<582.0,276.0>--<205.0,277.0>>

	* ecircumflex (U+00EA): L<<582.0,276.0>--<205.0,277.0>>

	* edieresis (U+00EB): L<<582.0,276.0>--<205.0,277.0>>

	* edotaccent (U+0117): L<<582.0,276.0>--<205.0,277.0>>

	* egrave (U+00E8): L<<582.0,276.0>--<205.0,277.0>>

	* emacron (U+0113): L<<582.0,276.0>--<205.0,277.0>>

	* eogonek (U+0119): L<<582.0,276.0>--<205.0,277.0>>

	* f (U+0066): L<<551.0,282.0>--<205.0,281.0>>

	* oe (U+0153): L<<1210.0,276.0>--<833.0,277.0>>

	* uni1E14 (U+1E14): L<<582.0,276.0>--<205.0,277.0>>

	* uni1E15 (U+1E15): L<<582.0,276.0>--<205.0,277.0>>

	* uni1E16 (U+1E16): L<<582.0,276.0>--<205.0,277.0>>

	* uni1E17 (U+1E17): L<<582.0,276.0>--<205.0,277.0>>

	* uni1E1C (U+1E1C): L<<582.0,276.0>--<205.0,277.0>>

	* uni1E1D (U+1E1D): L<<582.0,276.0>--<205.0,277.0>>

	* uni1EB8 (U+1EB8): L<<582.0,276.0>--<205.0,277.0>>

	* uni1EB9 (U+1EB9): L<<582.0,276.0>--<205.0,277.0>>

	* uni1EBC (U+1EBC): L<<582.0,276.0>--<205.0,277.0>>

	* uni1EBD (U+1EBD): L<<582.0,276.0>--<205.0,277.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] Nemoy-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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

	* G (U+0047): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* Gbreve (U+011E): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* Gcaron (U+01E6): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* Gcircumflex (U+011C): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* Gdotaccent (U+0120): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* dollar (U+0024): L<<291.0,750.0>--<291.0,751.0>> -> L<<291.0,751.0>--<291.0,893.0>>

	* g (U+0067): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* gbreve (U+011F): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* gcaron (U+01E7): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* gcircumflex (U+011D): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* gdotaccent (U+0121): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* integral (U+222B): L<<192.0,31.0>--<251.0,297.0>> -> L<<251.0,297.0>--<311.0,564.0>>

	* integral (U+222B): L<<371.0,550.0>--<311.0,284.0>> -> L<<311.0,284.0>--<252.0,18.0>>

	* uni0122 (U+0122): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* uni0123 (U+0123): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* uni019D (U+019D): L<<68.0,-193.0>--<68.0,27.0>> -> L<<68.0,27.0>--<68.0,31.0>>

	* uni019D (U+019D): L<<68.0,27.0>--<68.0,31.0>> -> L<<68.0,31.0>--<68.0,701.0>>

	* uni0259 (U+0259): L<<49.0,361.0>--<49.0,361.0>> -> L<<49.0,361.0>--<49.0,361.0>>

	* uni0259 (U+0259): L<<81.0,393.0>--<81.0,393.0>> -> L<<81.0,393.0>--<82.0,393.0>>

	* uni0259 (U+0259): L<<81.0,393.0>--<82.0,393.0>> -> L<<82.0,393.0>--<764.0,393.0>>

	* uni0272 (U+0272): L<<68.0,-193.0>--<68.0,27.0>> -> L<<68.0,27.0>--<68.0,31.0>>

	* uni0272 (U+0272): L<<68.0,27.0>--<68.0,31.0>> -> L<<68.0,31.0>--<68.0,701.0>>

	* uni1E20 (U+1E20): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>>

	* uni1E21 (U+1E21): L<<829.0,362.0>--<829.0,361.0>> -> L<<829.0,361.0>--<829.0,360.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* G (U+0047): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* Gbreve (U+011E): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* Gcaron (U+01E6): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* Gcircumflex (U+011C): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* Gdotaccent (U+0120): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* braceleft (U+007B): B<<49.0,382.0>-<49.0,383.0>-<49.0,382.0>>/B<<49.0,382.0>-<51.0,395.0>-<60.0,403.0>> = 8.746162262555211

	* braceright (U+007D): B<<252.0,403.0>-<261.0,395.0>-<262.0,382.0>>/B<<262.0,382.0>-<262.0,383.0>-<262.0,382.0>> = 4.398705354995508

	* g (U+0067): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* gbreve (U+011F): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* gcaron (U+01E7): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* gcircumflex (U+011D): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* gdotaccent (U+0121): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* uni0122 (U+0122): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* uni0123 (U+0123): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* uni1E20 (U+1E20): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484

	* uni1E21 (U+1E21): B<<829.0,364.5>-<829.0,364.0>-<829.0,366.0>>/B<<829.0,366.0>-<830.0,362.0>-<829.0,362.0>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<1226.0,279.0>--<810.0,280.0>>

	* AE (U+00C6): L<<915.0,345.0>--<1226.0,344.0>>

	* AEacute (U+01FC): L<<1226.0,279.0>--<810.0,280.0>>

	* AEacute (U+01FC): L<<915.0,345.0>--<1226.0,344.0>>

	* E (U+0045): L<<239.0,345.0>--<550.0,344.0>>

	* E (U+0045): L<<550.0,279.0>--<134.0,280.0>>

	* Eacute (U+00C9): L<<239.0,345.0>--<550.0,344.0>>

	* Eacute (U+00C9): L<<550.0,279.0>--<134.0,280.0>>

	* Ebreve (U+0114): L<<239.0,345.0>--<550.0,344.0>>

	* Ebreve (U+0114): L<<550.0,279.0>--<134.0,280.0>>

	* Ecaron (U+011A): L<<239.0,345.0>--<550.0,344.0>>

	* Ecaron (U+011A): L<<550.0,279.0>--<134.0,280.0>>

	* Ecircumflex (U+00CA): L<<239.0,345.0>--<550.0,344.0>>

	* Ecircumflex (U+00CA): L<<550.0,279.0>--<134.0,280.0>>

	* Edieresis (U+00CB): L<<239.0,345.0>--<550.0,344.0>>

	* Edieresis (U+00CB): L<<550.0,279.0>--<134.0,280.0>>

	* Edotaccent (U+0116): L<<239.0,345.0>--<550.0,344.0>>

	* Edotaccent (U+0116): L<<550.0,279.0>--<134.0,280.0>>

	* Egrave (U+00C8): L<<239.0,345.0>--<550.0,344.0>>

	* Egrave (U+00C8): L<<550.0,279.0>--<134.0,280.0>>

	* Emacron (U+0112): L<<239.0,345.0>--<550.0,344.0>>

	* Emacron (U+0112): L<<550.0,279.0>--<134.0,280.0>>

	* Eogonek (U+0118): L<<239.0,345.0>--<550.0,344.0>>

	* Eogonek (U+0118): L<<550.0,279.0>--<134.0,280.0>>

	* F (U+0046): L<<540.0,282.0>--<134.0,281.0>>

	* OE (U+0152): L<<1249.0,279.0>--<833.0,280.0>>

	* OE (U+0152): L<<938.0,345.0>--<1249.0,344.0>>

	* ae (U+00E6): L<<1226.0,279.0>--<810.0,280.0>>

	* ae (U+00E6): L<<915.0,345.0>--<1226.0,344.0>>

	* aeacute (U+01FD): L<<1226.0,279.0>--<810.0,280.0>>

	* aeacute (U+01FD): L<<915.0,345.0>--<1226.0,344.0>>

	* dollar (U+0024): L<<291.0,-127.0>--<292.0,0.0>>

	* dollar (U+0024): L<<357.0,0.0>--<356.0,-127.0>>

	* e (U+0065): L<<239.0,345.0>--<550.0,344.0>>

	* e (U+0065): L<<550.0,279.0>--<134.0,280.0>>

	* eacute (U+00E9): L<<239.0,345.0>--<550.0,344.0>>

	* eacute (U+00E9): L<<550.0,279.0>--<134.0,280.0>>

	* ebreve (U+0115): L<<239.0,345.0>--<550.0,344.0>>

	* ebreve (U+0115): L<<550.0,279.0>--<134.0,280.0>>

	* ecaron (U+011B): L<<239.0,345.0>--<550.0,344.0>>

	* ecaron (U+011B): L<<550.0,279.0>--<134.0,280.0>>

	* ecircumflex (U+00EA): L<<239.0,345.0>--<550.0,344.0>>

	* ecircumflex (U+00EA): L<<550.0,279.0>--<134.0,280.0>>

	* edieresis (U+00EB): L<<239.0,345.0>--<550.0,344.0>>

	* edieresis (U+00EB): L<<550.0,279.0>--<134.0,280.0>>

	* edotaccent (U+0117): L<<239.0,345.0>--<550.0,344.0>>

	* edotaccent (U+0117): L<<550.0,279.0>--<134.0,280.0>>

	* egrave (U+00E8): L<<239.0,345.0>--<550.0,344.0>>

	* egrave (U+00E8): L<<550.0,279.0>--<134.0,280.0>>

	* emacron (U+0113): L<<239.0,345.0>--<550.0,344.0>>

	* emacron (U+0113): L<<550.0,279.0>--<134.0,280.0>>

	* eogonek (U+0119): L<<239.0,345.0>--<550.0,344.0>>

	* eogonek (U+0119): L<<550.0,279.0>--<134.0,280.0>>

	* f (U+0066): L<<540.0,282.0>--<134.0,281.0>>

	* oe (U+0153): L<<1249.0,279.0>--<833.0,280.0>>

	* oe (U+0153): L<<938.0,345.0>--<1249.0,344.0>>

	* uni1E14 (U+1E14): L<<239.0,345.0>--<550.0,344.0>>

	* uni1E14 (U+1E14): L<<550.0,279.0>--<134.0,280.0>>

	* uni1E15 (U+1E15): L<<239.0,345.0>--<550.0,344.0>>

	* uni1E15 (U+1E15): L<<550.0,279.0>--<134.0,280.0>>

	* uni1E16 (U+1E16): L<<239.0,345.0>--<550.0,344.0>>

	* uni1E16 (U+1E16): L<<550.0,279.0>--<134.0,280.0>>

	* uni1E17 (U+1E17): L<<239.0,345.0>--<550.0,344.0>>

	* uni1E17 (U+1E17): L<<550.0,279.0>--<134.0,280.0>>

	* uni1E1C (U+1E1C): L<<239.0,345.0>--<550.0,344.0>>

	* uni1E1C (U+1E1C): L<<550.0,279.0>--<134.0,280.0>>

	* uni1E1D (U+1E1D): L<<239.0,345.0>--<550.0,344.0>>

	* uni1E1D (U+1E1D): L<<550.0,279.0>--<134.0,280.0>>

	* uni1EB8 (U+1EB8): L<<239.0,345.0>--<550.0,344.0>>

	* uni1EB8 (U+1EB8): L<<550.0,279.0>--<134.0,280.0>>

	* uni1EB9 (U+1EB9): L<<239.0,345.0>--<550.0,344.0>>

	* uni1EB9 (U+1EB9): L<<550.0,279.0>--<134.0,280.0>>

	* uni1EBC (U+1EBC): L<<239.0,345.0>--<550.0,344.0>>

	* uni1EBC (U+1EBC): L<<550.0,279.0>--<134.0,280.0>>

	* uni1EBD (U+1EBD): L<<239.0,345.0>--<550.0,344.0>>

	* uni1EBD (U+1EBD): L<<550.0,279.0>--<134.0,280.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] Nemoy-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* IJ (U+0132): L<<929.0,223.0>--<929.0,223.0>> -> L<<929.0,223.0>--<929.0,223.0>>

	* IJacute (U+E133): L<<929.0,223.0>--<929.0,223.0>> -> L<<929.0,223.0>--<929.0,223.0>>

	* J (U+004A): L<<532.0,223.0>--<532.0,223.0>> -> L<<532.0,223.0>--<532.0,223.0>>

	* Jcircumflex (U+0134): L<<532.0,223.0>--<532.0,223.0>> -> L<<532.0,223.0>--<532.0,223.0>>

	* dollar (U+0024): L<<273.0,748.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,893.0>>

	* ij (U+0133): L<<929.0,223.0>--<929.0,223.0>> -> L<<929.0,223.0>--<929.0,223.0>>

	* ijacute (U+E134): L<<929.0,223.0>--<929.0,223.0>> -> L<<929.0,223.0>--<929.0,223.0>>

	* integral (U+222B): L<<176.0,34.0>--<235.0,301.0>> -> L<<235.0,301.0>--<295.0,568.0>>

	* integral (U+222B): L<<387.0,547.0>--<327.0,280.0>> -> L<<327.0,280.0>--<268.0,14.0>>

	* j (U+006A): L<<532.0,223.0>--<532.0,223.0>> -> L<<532.0,223.0>--<532.0,223.0>>

	* jcircumflex (U+0135): L<<532.0,223.0>--<532.0,223.0>> -> L<<532.0,223.0>--<532.0,223.0>>

	* partialdiff (U+2202): L<<439.0,250.0>--<439.0,255.0>> -> L<<439.0,255.0>--<439.0,257.0>>

	* section (U+00A7): L<<333.0,101.0>--<334.0,101.0>> -> L<<334.0,101.0>--<554.0,101.0>>

	* uni0237 (U+0237): L<<532.0,223.0>--<532.0,223.0>> -> L<<532.0,223.0>--<532.0,223.0>>

	* uni0259 (U+0259): L<<49.0,365.0>--<49.0,365.0>> -> L<<49.0,365.0>--<49.0,365.0>>

	* uni0259 (U+0259): L<<99.0,416.0>--<99.0,416.0>> -> L<<99.0,416.0>--<726.0,416.0>>

	* uni0259 (U+0259): L<<99.0,416.0>--<99.0,416.0>> -> L<<99.0,416.0>--<99.0,416.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Dcaron (U+010E): B<<351.0,868.0>-<348.0,865.0>-<345.0,863.0>>/B<<345.0,863.0>-<347.0,864.0>-<346.0,863.5>> = 7.125016348901757

	* Ecaron (U+011A): B<<379.0,868.0>-<377.0,865.0>-<374.0,863.0>>/B<<374.0,863.0>-<375.0,864.0>-<374.5,863.5>> = 11.309932474020195

	* Gcaron (U+01E6): B<<479.0,868.0>-<476.0,865.0>-<473.0,863.0>>/B<<473.0,863.0>-<475.0,864.0>-<474.0,863.5>> = 7.125016348901757

	* Ncaron (U+0147): B<<416.0,868.0>-<413.0,865.0>-<410.0,863.0>>/B<<410.0,863.0>-<412.0,864.0>-<411.5,863.5>> = 7.125016348901757

	* Rcaron (U+0158): B<<345.0,868.0>-<342.0,865.0>-<339.0,863.0>>/B<<339.0,863.0>-<341.0,864.0>-<340.0,863.5>> = 7.125016348901757

	* Scaron (U+0160): B<<354.0,868.0>-<351.0,865.0>-<348.0,863.0>>/B<<348.0,863.0>-<350.0,864.0>-<349.0,863.5>> = 7.125016348901757

	* Tcaron (U+0164): B<<398.0,868.0>-<395.0,865.0>-<392.0,863.0>>/B<<392.0,863.0>-<394.0,864.0>-<393.0,863.5>> = 7.125016348901757

	* Wcircumflex (U+0174): B<<451.5,1014.5>-<452.0,1014.0>-<451.0,1015.0>>/B<<451.0,1015.0>-<454.0,1013.0>-<456.0,1010.0>> = 11.309932474020195

	* Zcaron (U+017D): B<<365.0,868.0>-<362.0,865.0>-<359.0,863.0>>/B<<359.0,863.0>-<361.0,864.0>-<360.5,863.5>> = 7.125016348901757

	* dcaron (U+010F): B<<351.0,868.0>-<348.0,865.0>-<345.0,863.0>>/B<<345.0,863.0>-<347.0,864.0>-<346.0,863.5>> = 7.125016348901757

	* ecaron (U+011B): B<<379.0,868.0>-<377.0,865.0>-<374.0,863.0>>/B<<374.0,863.0>-<375.0,864.0>-<374.5,863.5>> = 11.309932474020195

	* gcaron (U+01E7): B<<479.0,868.0>-<476.0,865.0>-<473.0,863.0>>/B<<473.0,863.0>-<475.0,864.0>-<474.0,863.5>> = 7.125016348901757

	* ncaron (U+0148): B<<416.0,868.0>-<413.0,865.0>-<410.0,863.0>>/B<<410.0,863.0>-<412.0,864.0>-<411.5,863.5>> = 7.125016348901757

	* rcaron (U+0159): B<<345.0,868.0>-<342.0,865.0>-<339.0,863.0>>/B<<339.0,863.0>-<341.0,864.0>-<340.0,863.5>> = 7.125016348901757

	* scaron (U+0161): B<<354.0,868.0>-<351.0,865.0>-<348.0,863.0>>/B<<348.0,863.0>-<350.0,864.0>-<349.0,863.5>> = 7.125016348901757

	* tcaron (U+0165): B<<398.0,868.0>-<395.0,865.0>-<392.0,863.0>>/B<<392.0,863.0>-<394.0,864.0>-<393.0,863.5>> = 7.125016348901757

	* uni1E66 (U+1E66): B<<354.0,868.0>-<351.0,865.0>-<348.0,863.0>>/B<<348.0,863.0>-<350.0,864.0>-<349.0,863.5>> = 7.125016348901757

	* uni1E67 (U+1E67): B<<354.0,868.0>-<351.0,865.0>-<348.0,863.0>>/B<<348.0,863.0>-<350.0,864.0>-<349.0,863.5>> = 7.125016348901757

	* wcircumflex (U+0175): B<<451.5,1014.5>-<452.0,1014.0>-<451.0,1015.0>>/B<<451.0,1015.0>-<454.0,1013.0>-<456.0,1010.0>> = 11.309932474020195

	* zcaron (U+017E): B<<365.0,868.0>-<362.0,865.0>-<359.0,863.0>>/B<<359.0,863.0>-<361.0,864.0>-<360.5,863.5>> = 7.125016348901757 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<1207.0,278.0>--<810.0,279.0>>

	* AE (U+00C6): L<<978.0,380.0>--<1207.0,379.0>>

	* AEacute (U+01FC): L<<1207.0,278.0>--<810.0,279.0>>

	* AEacute (U+01FC): L<<978.0,380.0>--<1207.0,379.0>>

	* E (U+0045): L<<337.0,380.0>--<566.0,379.0>>

	* E (U+0045): L<<566.0,278.0>--<169.0,279.0>>

	* Eacute (U+00C9): L<<337.0,380.0>--<566.0,379.0>>

	* Eacute (U+00C9): L<<566.0,278.0>--<169.0,279.0>>

	* Ebreve (U+0114): L<<337.0,380.0>--<566.0,379.0>>

	* Ebreve (U+0114): L<<566.0,278.0>--<169.0,279.0>>

	* Ecaron (U+011A): L<<337.0,380.0>--<566.0,379.0>>

	* Ecaron (U+011A): L<<566.0,278.0>--<169.0,279.0>>

	* Ecircumflex (U+00CA): L<<337.0,380.0>--<566.0,379.0>>

	* Ecircumflex (U+00CA): L<<566.0,278.0>--<169.0,279.0>>

	* Edieresis (U+00CB): L<<337.0,380.0>--<566.0,379.0>>

	* Edieresis (U+00CB): L<<566.0,278.0>--<169.0,279.0>>

	* Edotaccent (U+0116): L<<337.0,380.0>--<566.0,379.0>>

	* Edotaccent (U+0116): L<<566.0,278.0>--<169.0,279.0>>

	* Egrave (U+00C8): L<<337.0,380.0>--<566.0,379.0>>

	* Egrave (U+00C8): L<<566.0,278.0>--<169.0,279.0>>

	* Emacron (U+0112): L<<337.0,380.0>--<566.0,379.0>>

	* Emacron (U+0112): L<<566.0,278.0>--<169.0,279.0>>

	* Eogonek (U+0118): L<<337.0,380.0>--<566.0,379.0>>

	* Eogonek (U+0118): L<<566.0,278.0>--<169.0,279.0>>

	* F (U+0046): L<<546.0,282.0>--<169.0,281.0>>

	* OE (U+0152): L<<1000.0,380.0>--<1229.0,379.0>>

	* OE (U+0152): L<<1229.0,278.0>--<832.0,279.0>>

	* ae (U+00E6): L<<1207.0,278.0>--<810.0,279.0>>

	* ae (U+00E6): L<<978.0,380.0>--<1207.0,379.0>>

	* aeacute (U+01FD): L<<1207.0,278.0>--<810.0,279.0>>

	* aeacute (U+01FD): L<<978.0,380.0>--<1207.0,379.0>>

	* dollar (U+0024): L<<273.0,-126.0>--<274.0,0.0>>

	* dollar (U+0024): L<<375.0,0.0>--<374.0,-128.0>>

	* e (U+0065): L<<337.0,380.0>--<566.0,379.0>>

	* e (U+0065): L<<566.0,278.0>--<169.0,279.0>>

	* eacute (U+00E9): L<<337.0,380.0>--<566.0,379.0>>

	* eacute (U+00E9): L<<566.0,278.0>--<169.0,279.0>>

	* ebreve (U+0115): L<<337.0,380.0>--<566.0,379.0>>

	* ebreve (U+0115): L<<566.0,278.0>--<169.0,279.0>>

	* ecaron (U+011B): L<<337.0,380.0>--<566.0,379.0>>

	* ecaron (U+011B): L<<566.0,278.0>--<169.0,279.0>>

	* ecircumflex (U+00EA): L<<337.0,380.0>--<566.0,379.0>>

	* ecircumflex (U+00EA): L<<566.0,278.0>--<169.0,279.0>>

	* edieresis (U+00EB): L<<337.0,380.0>--<566.0,379.0>>

	* edieresis (U+00EB): L<<566.0,278.0>--<169.0,279.0>>

	* edotaccent (U+0117): L<<337.0,380.0>--<566.0,379.0>>

	* edotaccent (U+0117): L<<566.0,278.0>--<169.0,279.0>>

	* egrave (U+00E8): L<<337.0,380.0>--<566.0,379.0>>

	* egrave (U+00E8): L<<566.0,278.0>--<169.0,279.0>>

	* emacron (U+0113): L<<337.0,380.0>--<566.0,379.0>>

	* emacron (U+0113): L<<566.0,278.0>--<169.0,279.0>>

	* eogonek (U+0119): L<<337.0,380.0>--<566.0,379.0>>

	* eogonek (U+0119): L<<566.0,278.0>--<169.0,279.0>>

	* f (U+0066): L<<546.0,282.0>--<169.0,281.0>>

	* oe (U+0153): L<<1000.0,380.0>--<1229.0,379.0>>

	* oe (U+0153): L<<1229.0,278.0>--<832.0,279.0>>

	* uni1E14 (U+1E14): L<<337.0,380.0>--<566.0,379.0>>

	* uni1E14 (U+1E14): L<<566.0,278.0>--<169.0,279.0>>

	* uni1E15 (U+1E15): L<<337.0,380.0>--<566.0,379.0>>

	* uni1E15 (U+1E15): L<<566.0,278.0>--<169.0,279.0>>

	* uni1E16 (U+1E16): L<<337.0,380.0>--<566.0,379.0>>

	* uni1E16 (U+1E16): L<<566.0,278.0>--<169.0,279.0>>

	* uni1E17 (U+1E17): L<<337.0,380.0>--<566.0,379.0>>

	* uni1E17 (U+1E17): L<<566.0,278.0>--<169.0,279.0>>

	* uni1E1C (U+1E1C): L<<337.0,380.0>--<566.0,379.0>>

	* uni1E1C (U+1E1C): L<<566.0,278.0>--<169.0,279.0>>

	* uni1E1D (U+1E1D): L<<337.0,380.0>--<566.0,379.0>>

	* uni1E1D (U+1E1D): L<<566.0,278.0>--<169.0,279.0>>

	* uni1EB8 (U+1EB8): L<<337.0,380.0>--<566.0,379.0>>

	* uni1EB8 (U+1EB8): L<<566.0,278.0>--<169.0,279.0>>

	* uni1EB9 (U+1EB9): L<<337.0,380.0>--<566.0,379.0>>

	* uni1EB9 (U+1EB9): L<<566.0,278.0>--<169.0,279.0>>

	* uni1EBC (U+1EBC): L<<337.0,380.0>--<566.0,379.0>>

	* uni1EBC (U+1EBC): L<<566.0,278.0>--<169.0,279.0>>

	* uni1EBD (U+1EBD): L<<337.0,380.0>--<566.0,379.0>>

	* uni1EBD (U+1EBD): L<<566.0,278.0>--<169.0,279.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] Nemoy-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Acircumflex (U+00C2): L<<323.0,895.0>--<325.0,897.0>> -> L<<325.0,897.0>--<398.0,971.0>>

	* Ccircumflex (U+0108): L<<347.0,897.0>--<349.0,899.0>> -> L<<349.0,899.0>--<422.0,973.0>>

	* Ecircumflex (U+00CA): L<<235.0,895.0>--<237.0,897.0>> -> L<<237.0,897.0>--<310.0,971.0>>

	* Gcircumflex (U+011C): L<<347.0,895.0>--<349.0,897.0>> -> L<<349.0,897.0>--<422.0,971.0>>

	* Hcircumflex (U+0124): L<<252.0,895.0>--<254.0,897.0>> -> L<<254.0,897.0>--<327.0,971.0>>

	* IJ (U+0132): L<<804.0,189.0>--<804.0,189.0>> -> L<<804.0,189.0>--<804.0,189.0>>

	* IJacute (U+E133): L<<804.0,189.0>--<804.0,189.0>> -> L<<804.0,189.0>--<804.0,189.0>>

	* Icircumflex (U+00CE): L<<121.0,895.0>--<123.0,897.0>> -> L<<123.0,897.0>--<196.0,971.0>>

	* J (U+004A): L<<478.0,189.0>--<478.0,189.0>> -> L<<478.0,189.0>--<478.0,189.0>>

	* Jcircumflex (U+0134): L<<190.0,895.0>--<192.0,897.0>> -> L<<192.0,897.0>--<265.0,971.0>>

	* Jcircumflex (U+0134): L<<478.0,189.0>--<478.0,189.0>> -> L<<478.0,189.0>--<478.0,189.0>>

	* Ocircumflex (U+00D4): L<<347.0,895.0>--<349.0,897.0>> -> L<<349.0,897.0>--<422.0,971.0>>

	* Scircumflex (U+015C): L<<214.0,895.0>--<216.0,897.0>> -> L<<216.0,897.0>--<289.0,971.0>>

	* Ucircumflex (U+00DB): L<<252.0,895.0>--<254.0,897.0>> -> L<<254.0,897.0>--<327.0,971.0>>

	* Wcircumflex (U+0174): L<<296.0,895.0>--<298.0,897.0>> -> L<<298.0,897.0>--<371.0,970.0>>

	* Ycircumflex (U+0176): L<<286.0,895.0>--<288.0,897.0>> -> L<<288.0,897.0>--<361.0,971.0>>

	* acircumflex (U+00E2): L<<323.0,895.0>--<325.0,897.0>> -> L<<325.0,897.0>--<398.0,971.0>>

	* caron (U+02C7): L<<115.0,661.0>--<42.0,735.0>> -> L<<42.0,735.0>--<40.0,737.0>>

	* ccircumflex (U+0109): L<<347.0,897.0>--<349.0,899.0>> -> L<<349.0,899.0>--<422.0,973.0>>

	* circumflex (U+02C6): L<<40.0,690.0>--<42.0,692.0>> -> L<<42.0,692.0>--<115.0,766.0>>

	* ecircumflex (U+00EA): L<<235.0,895.0>--<237.0,897.0>> -> L<<237.0,897.0>--<310.0,971.0>>

	* gcircumflex (U+011D): L<<347.0,895.0>--<349.0,897.0>> -> L<<349.0,897.0>--<422.0,971.0>>

	* hcircumflex (U+0125): L<<252.0,895.0>--<254.0,897.0>> -> L<<254.0,897.0>--<327.0,971.0>>

	* icircumflex (U+00EE): L<<121.0,895.0>--<123.0,897.0>> -> L<<123.0,897.0>--<196.0,971.0>>

	* ij (U+0133): L<<804.0,189.0>--<804.0,189.0>> -> L<<804.0,189.0>--<804.0,189.0>>

	* ijacute (U+E134): L<<804.0,189.0>--<804.0,189.0>> -> L<<804.0,189.0>--<804.0,189.0>>

	* integral (U+222B): L<<200.0,29.0>--<259.0,296.0>> -> L<<259.0,296.0>--<319.0,563.0>>

	* integral (U+222B): L<<363.0,552.0>--<303.0,285.0>> -> L<<303.0,285.0>--<244.0,19.0>>

	* j (U+006A): L<<478.0,189.0>--<478.0,189.0>> -> L<<478.0,189.0>--<478.0,189.0>>

	* jcircumflex (U+0135): L<<190.0,895.0>--<192.0,897.0>> -> L<<192.0,897.0>--<265.0,971.0>>

	* jcircumflex (U+0135): L<<478.0,189.0>--<478.0,189.0>> -> L<<478.0,189.0>--<478.0,189.0>>

	* ocircumflex (U+00F4): L<<347.0,895.0>--<349.0,897.0>> -> L<<349.0,897.0>--<422.0,971.0>>

	* scircumflex (U+015D): L<<214.0,895.0>--<216.0,897.0>> -> L<<216.0,897.0>--<289.0,971.0>>

	* ucircumflex (U+00FB): L<<252.0,895.0>--<254.0,897.0>> -> L<<254.0,897.0>--<327.0,971.0>>

	* uni019D (U+019D): L<<68.0,-193.0>--<68.0,22.0>> -> L<<68.0,22.0>--<68.0,23.0>>

	* uni019D (U+019D): L<<68.0,22.0>--<68.0,23.0>> -> L<<68.0,23.0>--<68.0,714.0>>

	* uni0237 (U+0237): L<<478.0,189.0>--<478.0,189.0>> -> L<<478.0,189.0>--<478.0,189.0>>

	* uni0259 (U+0259): L<<72.0,382.0>--<72.0,382.0>> -> L<<72.0,382.0>--<73.0,382.0>>

	* uni0259 (U+0259): L<<72.0,382.0>--<73.0,382.0>> -> L<<73.0,382.0>--<782.0,382.0>>

	* uni0272 (U+0272): L<<68.0,-193.0>--<68.0,22.0>> -> L<<68.0,22.0>--<68.0,23.0>>

	* uni0272 (U+0272): L<<68.0,22.0>--<68.0,23.0>> -> L<<68.0,23.0>--<68.0,714.0>>

	* uni0302 (U+0302): L<<40.0,690.0>--<42.0,692.0>> -> L<<42.0,692.0>--<115.0,766.0>>

	* uni030C (U+030C): L<<115.0,661.0>--<42.0,735.0>> -> L<<42.0,735.0>--<40.0,737.0>>

	* wcircumflex (U+0175): L<<296.0,895.0>--<298.0,897.0>> -> L<<298.0,897.0>--<371.0,970.0>>

	* ycircumflex (U+0177): L<<286.0,895.0>--<288.0,897.0>> -> L<<288.0,897.0>--<361.0,971.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ncaron (U+0147): B<<366.0,866.0>-<364.0,863.0>-<361.0,861.0>>/B<<361.0,861.0>-<362.0,862.0>-<361.5,861.5>> = 11.309932474020195

	* Rcaron (U+0158): B<<289.0,866.0>-<286.0,863.0>-<283.0,861.0>>/B<<283.0,861.0>-<285.0,862.0>-<284.0,861.5>> = 7.125016348901757

	* Scaron (U+0160): B<<325.0,866.0>-<322.0,863.0>-<319.0,861.0>>/B<<319.0,861.0>-<321.0,862.0>-<320.0,861.5>> = 7.125016348901757

	* Tcaron (U+0164): B<<369.0,866.0>-<366.0,863.0>-<363.0,861.0>>/B<<363.0,861.0>-<365.0,862.0>-<364.0,861.5>> = 7.125016348901757

	* Wcircumflex (U+0174): B<<404.0,975.0>-<405.0,974.0>-<403.0,976.0>>/B<<403.0,976.0>-<406.0,974.0>-<409.0,970.0>> = 11.309932474020195

	* Zcaron (U+017D): B<<344.0,866.0>-<341.0,863.0>-<338.0,861.0>>/B<<338.0,861.0>-<340.0,862.0>-<339.0,861.5>> = 7.125016348901757

	* ncaron (U+0148): B<<366.0,866.0>-<364.0,863.0>-<361.0,861.0>>/B<<361.0,861.0>-<362.0,862.0>-<361.5,861.5>> = 11.309932474020195

	* rcaron (U+0159): B<<289.0,866.0>-<286.0,863.0>-<283.0,861.0>>/B<<283.0,861.0>-<285.0,862.0>-<284.0,861.5>> = 7.125016348901757

	* scaron (U+0161): B<<325.0,866.0>-<322.0,863.0>-<319.0,861.0>>/B<<319.0,861.0>-<321.0,862.0>-<320.0,861.5>> = 7.125016348901757

	* tcaron (U+0165): B<<369.0,866.0>-<366.0,863.0>-<363.0,861.0>>/B<<363.0,861.0>-<365.0,862.0>-<364.0,861.5>> = 7.125016348901757

	* uni1E66 (U+1E66): B<<325.0,866.0>-<322.0,863.0>-<319.0,861.0>>/B<<319.0,861.0>-<321.0,862.0>-<320.0,861.5>> = 7.125016348901757

	* uni1E67 (U+1E67): B<<325.0,866.0>-<322.0,863.0>-<319.0,861.0>>/B<<319.0,861.0>-<321.0,862.0>-<320.0,861.5>> = 7.125016348901757

	* wcircumflex (U+0175): B<<404.0,975.0>-<405.0,974.0>-<403.0,976.0>>/B<<403.0,976.0>-<406.0,974.0>-<409.0,970.0>> = 11.309932474020195

	* zcaron (U+017E): B<<344.0,866.0>-<341.0,863.0>-<338.0,861.0>>/B<<338.0,861.0>-<340.0,862.0>-<339.0,861.5>> = 7.125016348901757 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<884.0,328.0>--<1236.0,327.0>>

	* AEacute (U+01FC): L<<884.0,328.0>--<1236.0,327.0>>

	* E (U+0045): L<<190.0,328.0>--<542.0,327.0>>

	* Eacute (U+00C9): L<<190.0,328.0>--<542.0,327.0>>

	* Ebreve (U+0114): L<<190.0,328.0>--<542.0,327.0>>

	* Ecaron (U+011A): L<<190.0,328.0>--<542.0,327.0>>

	* Ecircumflex (U+00CA): L<<190.0,328.0>--<542.0,327.0>>

	* Edieresis (U+00CB): L<<190.0,328.0>--<542.0,327.0>>

	* Edotaccent (U+0116): L<<190.0,328.0>--<542.0,327.0>>

	* Egrave (U+00C8): L<<190.0,328.0>--<542.0,327.0>>

	* Emacron (U+0112): L<<190.0,328.0>--<542.0,327.0>>

	* Eogonek (U+0118): L<<190.0,328.0>--<542.0,327.0>>

	* OE (U+0152): L<<906.0,328.0>--<1258.0,327.0>>

	* ae (U+00E6): L<<884.0,328.0>--<1236.0,327.0>>

	* aeacute (U+01FD): L<<884.0,328.0>--<1236.0,327.0>>

	* dollar (U+0024): L<<300.0,-127.0>--<301.0,0.0>>

	* dollar (U+0024): L<<348.0,0.0>--<347.0,-127.0>>

	* e (U+0065): L<<190.0,328.0>--<542.0,327.0>>

	* eacute (U+00E9): L<<190.0,328.0>--<542.0,327.0>>

	* ebreve (U+0115): L<<190.0,328.0>--<542.0,327.0>>

	* ecaron (U+011B): L<<190.0,328.0>--<542.0,327.0>>

	* ecircumflex (U+00EA): L<<190.0,328.0>--<542.0,327.0>>

	* edieresis (U+00EB): L<<190.0,328.0>--<542.0,327.0>>

	* edotaccent (U+0117): L<<190.0,328.0>--<542.0,327.0>>

	* egrave (U+00E8): L<<190.0,328.0>--<542.0,327.0>>

	* emacron (U+0113): L<<190.0,328.0>--<542.0,327.0>>

	* eogonek (U+0119): L<<190.0,328.0>--<542.0,327.0>>

	* oe (U+0153): L<<906.0,328.0>--<1258.0,327.0>>

	* uni1E14 (U+1E14): L<<190.0,328.0>--<542.0,327.0>>

	* uni1E15 (U+1E15): L<<190.0,328.0>--<542.0,327.0>>

	* uni1E16 (U+1E16): L<<190.0,328.0>--<542.0,327.0>>

	* uni1E17 (U+1E17): L<<190.0,328.0>--<542.0,327.0>>

	* uni1E1C (U+1E1C): L<<190.0,328.0>--<542.0,327.0>>

	* uni1E1D (U+1E1D): L<<190.0,328.0>--<542.0,327.0>>

	* uni1EB8 (U+1EB8): L<<190.0,328.0>--<542.0,327.0>>

	* uni1EB9 (U+1EB9): L<<190.0,328.0>--<542.0,327.0>>

	* uni1EBC (U+1EBC): L<<190.0,328.0>--<542.0,327.0>>

	* uni1EBD (U+1EBD): L<<190.0,328.0>--<542.0,327.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] Nemoy-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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

	- Glyph name: uni25CC	Contours detected: 20	Expected: 16or12

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
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Ccedilla (U+00C7): L<<389.0,-154.0>--<389.0,-153.0>> -> L<<389.0,-153.0>--<389.0,9.0>>

	* S (U+0053): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* Sacute (U+015A): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* Scaron (U+0160): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* Scedilla (U+015E): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* Scedilla (U+015E): L<<290.0,-150.0>--<290.0,-149.0>> -> L<<290.0,-149.0>--<290.0,13.0>>

	* Scircumflex (U+015C): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* Thorn (U+00DE): L<<277.0,157.0>--<99.0,157.0>> -> L<<99.0,157.0>--<98.0,157.0>>

	* Thorn (U+00DE): L<<277.0,656.0>--<99.0,656.0>> -> L<<99.0,656.0>--<98.0,656.0>>

	* Thorn (U+00DE): L<<98.0,186.0>--<99.0,186.0>> -> L<<99.0,186.0>--<277.0,186.0>>

	* Thorn (U+00DE): L<<98.0,686.0>--<99.0,686.0>> -> L<<99.0,686.0>--<277.0,686.0>>

	* ccedilla (U+00E7): L<<389.0,-154.0>--<389.0,-153.0>> -> L<<389.0,-153.0>--<389.0,9.0>>

	* cedilla (U+00B8): L<<78.0,-161.0>--<78.0,-160.0>> -> L<<78.0,-160.0>--<78.0,2.0>>

	* dollar (U+0024): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* integral (U+222B): L<<208.0,27.0>--<267.0,294.0>> -> L<<267.0,294.0>--<327.0,561.0>>

	* integral (U+222B): L<<355.0,554.0>--<295.0,287.0>> -> L<<295.0,287.0>--<236.0,21.0>>

	* s (U+0073): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* sacute (U+015B): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* scaron (U+0161): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* scedilla (U+015F): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* scedilla (U+015F): L<<290.0,-150.0>--<290.0,-149.0>> -> L<<290.0,-149.0>--<290.0,13.0>>

	* scircumflex (U+015D): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* section (U+00A7): L<<118.0,186.0>--<123.0,182.0>> -> L<<123.0,182.0>--<307.0,29.0>>

	* section (U+00A7): L<<289.0,357.0>--<294.0,353.0>> -> L<<294.0,353.0>--<672.0,39.0>>

	* thorn (U+00FE): L<<277.0,157.0>--<99.0,157.0>> -> L<<99.0,157.0>--<98.0,157.0>>

	* thorn (U+00FE): L<<277.0,656.0>--<99.0,656.0>> -> L<<99.0,656.0>--<98.0,656.0>>

	* thorn (U+00FE): L<<98.0,186.0>--<99.0,186.0>> -> L<<99.0,186.0>--<277.0,186.0>>

	* thorn (U+00FE): L<<98.0,686.0>--<99.0,686.0>> -> L<<99.0,686.0>--<277.0,686.0>>

	* uni0162 (U+0162): L<<334.0,-150.0>--<334.0,-149.0>> -> L<<334.0,-149.0>--<334.0,13.0>>

	* uni0163 (U+0163): L<<334.0,-150.0>--<334.0,-149.0>> -> L<<334.0,-149.0>--<334.0,13.0>>

	* uni0218 (U+0218): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni0219 (U+0219): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni0259 (U+0259): L<<63.0,371.0>--<64.0,371.0>> -> L<<64.0,371.0>--<64.0,371.0>>

	* uni0259 (U+0259): L<<64.0,371.0>--<64.0,371.0>> -> L<<64.0,371.0>--<800.0,371.0>>

	* uni0327 (U+0327): L<<78.0,-161.0>--<78.0,-160.0>> -> L<<78.0,-160.0>--<78.0,2.0>>

	* uni1E08 (U+1E08): L<<389.0,-154.0>--<389.0,-153.0>> -> L<<389.0,-153.0>--<389.0,9.0>>

	* uni1E09 (U+1E09): L<<389.0,-154.0>--<389.0,-153.0>> -> L<<389.0,-153.0>--<389.0,9.0>>

	* uni1E1C (U+1E1C): L<<271.0,-150.0>--<271.0,-149.0>> -> L<<271.0,-149.0>--<271.0,13.0>>

	* uni1E1D (U+1E1D): L<<271.0,-150.0>--<271.0,-149.0>> -> L<<271.0,-149.0>--<271.0,13.0>>

	* uni1E60 (U+1E60): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni1E61 (U+1E61): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni1E62 (U+1E62): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni1E63 (U+1E63): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni1E64 (U+1E64): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni1E65 (U+1E65): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni1E66 (U+1E66): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni1E67 (U+1E67): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni1E68 (U+1E68): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>>

	* uni1E69 (U+1E69): L<<157.0,357.0>--<162.0,353.0>> -> L<<162.0,353.0>--<540.0,39.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ccedilla (U+00C7): B<<389.5,-157.0>-<389.0,-156.0>-<390.0,-158.0>>/B<<390.0,-158.0>-<388.0,-153.0>-<389.0,-154.0>> = 4.763641690726066

	* Scedilla (U+015E): B<<290.5,-153.0>-<290.0,-152.0>-<291.0,-154.0>>/B<<291.0,-154.0>-<289.0,-149.0>-<290.0,-150.0>> = 4.763641690726066

	* ccedilla (U+00E7): B<<389.5,-157.0>-<389.0,-156.0>-<390.0,-158.0>>/B<<390.0,-158.0>-<388.0,-153.0>-<389.0,-154.0>> = 4.763641690726066

	* cedilla (U+00B8): B<<78.5,-164.0>-<78.0,-163.0>-<79.0,-165.0>>/B<<79.0,-165.0>-<77.0,-160.0>-<78.0,-161.0>> = 4.763641690726066

	* scedilla (U+015F): B<<290.5,-153.0>-<290.0,-152.0>-<291.0,-154.0>>/B<<291.0,-154.0>-<289.0,-149.0>-<290.0,-150.0>> = 4.763641690726066

	* uni0162 (U+0162): B<<334.5,-153.0>-<334.0,-152.0>-<335.0,-154.0>>/B<<335.0,-154.0>-<333.0,-149.0>-<334.0,-150.0>> = 4.763641690726066

	* uni0163 (U+0163): B<<334.5,-153.0>-<334.0,-152.0>-<335.0,-154.0>>/B<<335.0,-154.0>-<333.0,-149.0>-<334.0,-150.0>> = 4.763641690726066

	* uni0327 (U+0327): B<<78.5,-164.0>-<78.0,-163.0>-<79.0,-165.0>>/B<<79.0,-165.0>-<77.0,-160.0>-<78.0,-161.0>> = 4.763641690726066

	* uni1E08 (U+1E08): B<<389.5,-157.0>-<389.0,-156.0>-<390.0,-158.0>>/B<<390.0,-158.0>-<388.0,-153.0>-<389.0,-154.0>> = 4.763641690726066

	* uni1E09 (U+1E09): B<<389.5,-157.0>-<389.0,-156.0>-<390.0,-158.0>>/B<<390.0,-158.0>-<388.0,-153.0>-<389.0,-154.0>> = 4.763641690726066

	* uni1E1C (U+1E1C): B<<271.5,-153.0>-<271.0,-152.0>-<272.0,-154.0>>/B<<272.0,-154.0>-<270.0,-149.0>-<271.0,-150.0>> = 4.763641690726066

	* uni1E1D (U+1E1D): B<<271.5,-153.0>-<271.0,-152.0>-<272.0,-154.0>>/B<<272.0,-154.0>-<270.0,-149.0>-<271.0,-150.0>> = 4.763641690726066 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* dollar (U+0024): L<<309.0,-127.0>--<310.0,0.0>>

	* dollar (U+0024): L<<339.0,0.0>--<338.0,-127.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 5 | 30 | 602 | 36 | 509 | 0 |
| 0% | 0% | 3% | 51% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
