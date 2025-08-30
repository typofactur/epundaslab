----

# Epunda Slab

[![][Fontbakery]](https://typofactur.github.io/epundaslab/fontbakery/fontbakery-report.html)
[![][Universal]](https://typofactur.github.io/epundaslab/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://typofactur.github.io/epundaslab/fontbakery/fontbakery-report.html)
[![][Shaping]](https://typofactur.github.io/epundaslab/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundaslab%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundaslab%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundaslab%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundaslab%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftypofactur%2Fepundaslab%2Fgh-pages%2Fbadges%2FUniversal.json

Epunda Slab is the perfect companion of Epunda Sans. The sturdy, angled serifs give the font a robust and traditional look.

Epundas Sans is a variable font with a weight axis that ranges from Light (300) to Black (900).

![Sample Image](documentation/epundaslab_cover.png)
![Sample Image](documentation/epundaslab_alphabet.png)
![Sample Image](documentation/epundaslabitalic_alphabet.png)
![Sample Image](documentation/epundaslab_monster.png)
![Sample Image](documentation/epundaslab_tomato.png)
![Sample Image](documentation/epundaslab_algusto.png)
![Sample Image](documentation/epundaslab_spicy.png)

## About

typofactur is a German type foundry run by the graphic designer Simon Atzbach.
Find out more at https://typofactur.de

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://typofactur.github.io/epundaslab.git.

## Changelog

**25 December 2024. Version 1.002**
- initial commit
- analog to Epunda Sans
- including Italic

**31 December 2024. Version 1.100**
- kerning with kern on

**04 January 2025. Version 1.101**
- contour order colon
- width math signs
- no softhyphen
- dcroat
- serifs not exported
- path direction brackets, exclams, guillemots
- kerning f+i, f+l
- caret position ligatures fi and fl
- contour order guillemotright

**02 March 2025. Version 1.102**
- commaturnedabovecomb
- Aogonek, Eogonek, Iogonek, Uogonek, aogonek, eogonek, uogonek
- caroncomb.alt
- kerning Lcaron, dcaron, lcaron, tcaron
- Ldot, ldot added
- Dcroat = Eth
- kerning with Kern On

**29 June 2025. Version 1.103**
- lozenge added
- .notdef added

**30 August 2025. Version 1.200**
- version number for June 29 in README corrected in 1.103
- Regular a: master compatibility fixed (alternatives deleted)
- Regular a.salt metrics right
- Regular amacron modified
- Regular e: master compatibility fixed (alternatives deleted)
- Regular g: master compatibility fixed (alternatives deleted)
- Regular g.salt2 deleted
- Italic a: master compatibility fixed (alternatives deleted)
- Italic a.salt
- Italic amacron modified
- Italic e: master compatibility fixed (alternatives deleted)
- Italic e.salt
- Italic g: master compatibility fixed (alternatives deleted)
- Italic g.ss02: master compatibility fixed (alternatives deleted)
- abreve.ss01 and ss02
- abreve.ss01
- acaron.ss01
- acircumflex.ss01
- acircumflexdotbelow.ss01
- adieresis.ss01 and ss02
- adotbelow.ss01 and ss02
- agrave.ss01 and ss02
- amacron.ss01 and ss02
- aogonek.ss01 and ss02
- aring.ss01 and ss02
- atilde.ss01 and ss02
- style set 3 width alternative e
- AE with serifs
- ae.ss03
- Italic ae modified
- eacute.ss03
- ecaron.ss03
- ecedilla.ss03
- ecircumflex.ss03
- ecircumflexdotbelow.ss03
- edieresis.ss03
- edotaccent.ss03
- edotbelow.ss03
- egrave.ss03
- emacron.ss03
- eogonek.ss03
- etilde.ss03
- gbreve.ss01 and ss02
- gcaron.ss01 and ss02
- gcircumflex.ss01 and ss02
- gcommaaccent.ss01 and ss02
- gdotaccent.ss01 and ss02
- gmacron.ss01 and ss02
- gstroke.ss01 and ss02
- gstroke modified
- deleted unexported glyphs
- k.salt deleted
- Gstroke with serif
- Italic a.ss01 = double-storey
- Italic g.ss01 = double-storey
- e.ogonek position
- Macute corrected

**30 August 2025. Version 1.300**
- Italic: missing k added


## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at https://openfontlicense.org

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
