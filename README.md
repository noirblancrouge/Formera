# Formera

[![][Fontbakery]](https://noirblancrouge.github.io/Formera/fontbakery/fontbakery-report.html)
[![][Universal]](https://noirblancrouge.github.io/Formera/fontbakery/fontbakery-report.html)
[![][Outline Checks]](https://noirblancrouge.github.io/Formera/fontbakery/fontbakery-report.html)
[![][Font File Checks]](https://noirblancrouge.github.io/Formera/fontbakery/fontbakery-report.html)
[![][OpenType Specification Checks]](https://noirblancrouge.github.io/Formera/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Formera/badges/overall.json
[Outline Checks]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Formera/badges/OutlineChecks.json
[Font File Checks]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Formera/badges/FontFileChecks.json
[Universal]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Formera/badges/UniversalProfileChecks.json
[OpenType Specification Checks]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/Formera/badges/OpenTypeSpecificationChecks.json

![Cover](https://raw.githubusercontent.com/noirblancrouge/Formera/master/documentation/images/formera.jpg)

Formera (AKA Futura Renner) family is a digital version of Futura lead character belonging to the typography department of Ecole Nationale Supérieure des Arts de la Cambre, and probably the first draft of Futura as we know it.

We first printed the full set of lead characters, and then we vectorized these prints. The outlines irregularities are obtained by this method.

«No other similar is known. It is undoubtedly the very first (1927). It is distinguished by m &amp; n absolutely straight; by an r which is a bar followed by a point.» — Translated quotes by Fernand Baudin, 1971.

![Specimen](https://raw.githubusercontent.com/noirblancrouge/Formera/master/documentation/images/formera-charset.jpg)

## ChangeLog

When you make modifications, be sure to add a description of your changes,
following the format of the other entries, to the start of this section.

14 Feb 2025 (Bastien Sozeau)
- Add glyphs according to the standards of the NBR glyphset

12 Sep 2023 (Bastien Sozeau)
- Update according GF specs - Small fixes

8 Sep 2023 (Bastien Sozeau)
- Add glyphs, review anchors position, cleanup drawing

5 Sep 2023 (Bastien Sozeau)
- Change name to Formera

5 Sep 2023 (Bastien Sozeau)
- Update License, cleanup drawing, add glyphs

04 Feb 2019 (Bastien Sozeau)
- Update Euro sign, add some missing characters
- Update License, add real sources

17 Jan 2011 (Bastien Sozeau)
- Initital release.

## Bio

Bastien Sozeau is the founder of NoirBlancRouge, an independent type foundry based in Paris since 2019. Specializing in retail and custom typefaces, Bastien has crafted unique fonts for renowned brands such as Kipling, Christian Louboutin and The Olympic Museum. Beyond their commercial work, NoirBlancRouge has also been actively involved in designing free and open-source typefaces since 2013.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at [noirblancrouge.github.io/Formera](https://noirblancrouge.github.io/Formera).

## License

Developed by [NoirBlancRouge Type Foundry](https://noirblancrouge.com) (Originally distributed by graphic design studio [Uplaod](https://uplaod.fr)), Formera is open source and licensed under OFL, the SIL Open Font License allows the licensed fonts to be used, studied, modified and redistributed freely as long as they are not sold by themselves.

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
