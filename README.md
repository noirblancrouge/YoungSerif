# Young Serif

[![][Fontbakery]](https://noirblancrouge.github.io/YoungSerif/fontbakery/fontbakery-report.html)
[![][Universal]](https://noirblancrouge.github.io/YoungSerif/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://noirblancrouge.github.io/YoungSerif/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://noirblancrouge.github.io/YoungSerif/fontbakery/fontbakery-report.html)
[![][Shaping]](https://noirblancrouge.github.io/YoungSerif/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/YoungSerif/fontbakery/overall.json
[GF Profile]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/YoungSerif/fontbakery/GoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/YoungSerif/fontbakery/OutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/YoungSerif/fontbakery/ShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https://noirblancrouge.github.io/YoungSerif/fontbakery/Universal.json

![Cover](https://raw.githubusercontent.com/noirblancrouge/YoungSerif/master/documentation/images/young-serif.jpg)

Young Serif is a heavy weight old style serif typeface, taking inspiration from Plantin Infant or ITC Italian Old Style. 
The lowercase b and f feature rounded curves, adding a tender and generous quality to this font.

![Specimen](https://raw.githubusercontent.com/noirblancrouge/YoungSerif/master/documentation/images/young-serif-charset.jpg)

## ChangeLog

When you make modifications, be sure to add a description of your changes,
following the format of the other entries, to the start of this section.

26 July 2023 (Emma Marichal)
- Update according GF specs - Small fixes

24 Mar 2023 (Bastien Sozeau)
- Update License, cleanup drawing, add glyphs

04 Feb 2019 (Bastien Sozeau)
- Update License, add real sources

17 Jan 2013 (Bastien Sozeau)
- Initital release.

## Bio

Bastien Sozeau is the founder of NoirBlancRouge, an independent type foundry based in Paris since 2019. Specializing in retail and custom typefaces, Bastien has crafted unique fonts for renowned brands such as Kipling, Christian Louboutin and The Olympic Museum. Beyond their commercial work, NoirBlancRouge has also been actively involved in designing free and open-source typefaces since 2013.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at [noirblancrouge.github.io/YoungSerif](https://noirblancrouge.github.io/YoungSerif).

## License

Developed by [NoirBlancRouge Type Foundry](https://noirblancrouge.com) (Originally distributed by graphic design studio [Uplaod](https://uplaod.fr)), Young Serif is open source and licensed under OFL, the SIL Open Font License allows the licensed fonts to be used, studied, modified and redistributed freely as long as they are not sold by themselves.

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.