# Nemoy

[![][Fontbakery]](https://noirblancrouge.github.io/Nemoy/fontbakery/fontbakery-report.html)
[![][Universal]](https://noirblancrouge.github.io/Nemoy/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://noirblancrouge.github.io/Nemoy/fontbakery/fontbakery-report.html)
[![][Outline Checks]](https://noirblancrouge.github.io/Nemoy/fontbakery/fontbakery-report.html)
[![][Shaping]](https://noirblancrouge.github.io/Nemoy/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Nemoy/badges/overall.json
[GF Profile]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Nemoy/badges/GoogleFonts.json
[Outline Checks]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Nemoy/badges/OutlineChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Nemoy/badges/ShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Nemoy/badges/UniversalProfileChecks.json

![Cover](https://raw.githubusercontent.com/noirblancrouge/Nemoy/master/documentation/images/nemoy.jpg)

Nemoy is a geometric display font family. It comes in five weights, from Light to Heavy, contains a full glyphs set, including multilingual support, openType features and also a variable font version.

The Nemoy font as originally been designed for a student project about Philip K. Dick, mostly for books cover titles, but Nemoy can be used for a wide range of projects.

![Specimen](https://raw.githubusercontent.com/noirblancrouge/Nemoy/master/documentation/images/nemoy-variable.gif)

![Specimen](https://raw.githubusercontent.com/noirblancrouge/Nemoy/master/documentation/images/nemoy-charset.jpg)

## ChangeLog

When you make modifications, be sure to add a description of your changes,
following the format of the other entries, to the start of this section.

27 Jul 2023 (Bastien Sozeau)
- Add glyphs, add variable version, overall cleanup and full redesign

29 Jul 2010 (Bastien Sozeau)
- Initial release.

## Bio

Bastien Sozeau is the founder of NoirBlancRouge, an independent type foundry based in Paris since 2019. Specializing in retail and custom typefaces, Bastien has crafted unique fonts for renowned brands such as Kipling, Christian Louboutin and The Olympic Museum. Beyond their commercial work, NoirBlancRouge has also been actively involved in designing free and open-source typefaces since 2013.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at [noirblancrouge.github.io/Nemoy](https://noirblancrouge.github.io/Nemoy).

## License

Developed by [NoirBlancRouge Type Foundry](https://noirblancrouge.com) (Originally distributed by graphic design studio [Uplaod](https://uplaod.fr)), Nemoy is open source and licensed under OFL, the SIL Open Font License allows the licensed fonts to be used, studied, modified and redistributed freely as long as they are not sold by themselves.

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.