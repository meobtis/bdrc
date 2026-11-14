# bdrc

Sanskrit e-texts from the [Buddhist Digital Resource Center](https://www.bdrc.io) (BDRC), converted to Markdown for the
[MEOBTIS](https://meobtis.github.io) index of Buddhist texts in Sanskrit.

BDRC publishes its e-texts as open data in the [OpenPecha-Data](https://github.com/Openpecha-Data) GitHub organisation,
one repository per e-text. All 9,804 repositories were scanned; the 785 whose text is predominantly Sanskrit in
Devanāgarī (90) or Roman transliteration (695) are converted here, with every volume of a text in one file. The text is
unchanged; each file's front matter gives the title, editor, publisher and year (where BDRC records them), the
original collection the e-text came from (GRETIL or DSBC, where stated), and the OpenPecha-Data repository it was
taken from (`bdrc_id`).

Some e-texts are the same text as one in GRETIL, DSBC or SARIT, which BDRC mirrors; they are kept as BDRC publishes them.
Sanskrit that BDRC holds as Tibetan-script transliteration or as OCR inside Tibetan-language volumes is not converted
here.

Each file has `language` (`sa` unless BDRC's metadata says otherwise: some are the Tibetan (Wylie), English, Pāli or Gāndhārī layer of a critical edition, kept for completeness) and `buddhist: true` or `false`; the MEOBTIS index lists the Sanskrit Buddhist ones.

See [CATALOG.md](CATALOG.md) for the list.
