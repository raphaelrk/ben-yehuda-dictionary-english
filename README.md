# Ben-Yehuda's Hebrew dictionary in English (volumes 1–5, א–ל)

<!-- coverage:start -->
6,127 of the 9,560 entries in volumes 1–5 of Eliezer Ben-Yehuda's *A Complete Dictionary of
Ancient and Modern Hebrew* (מילון הלשון העברית הישנה והחדשה), each with its Hebrew text and an
English translation.

**This is a partial release:** 64% of the entries and 79% of the text of volumes 1–5 so far.
Volumes 6–16 (מ–ת, 12,688 entries) are not included.
<!-- coverage:end -->

**This is an AI translation and no human expert has reviewed it.** Check the Hebrew before
relying on it, and see [KNOWN_ISSUES.md](KNOWN_ISSUES.md).

## The data

`data/entries.jsonl` has one JSON object per line (UTF-8, about 30 MB and growing):

| Field | Meaning |
|---|---|
| `id` | Entry id: `Ben Yehuda Dictionary\|<headword>\|` |
| `headword` | Headword as given in the source |
| `he` | Hebrew paragraphs |
| `en` | English paragraphs; `en[i]` translates `he[i]` |
| `translated` | Date of the translation (YYYY-MM-DD) |

```python
import json
entries = {e["headword"]: e for e in map(json.loads, open("data/entries.jsonl", encoding="utf-8"))}
print(entries["אָמֵן"]["en"][0])
```

Headwords carry a Roman numeral where the dictionary has homographs (for example `דִּין I`).
In the English, text in `[Note: …]` is a footnote that the digitized source prints inside the
entry. Ben-Yehuda's marks `*` and `°` are kept where the source has them.

## Where the Hebrew comes from

The dictionary was typed and proofread by the volunteers of
[Project Ben-Yehuda](https://benyehuda.org/dict/24412), which marks it public domain
(נחלת הכלל), and is served by [Sefaria](https://www.sefaria.org/Ben_Yehuda_Dictionary). We
took the text from Sefaria's dictionary API in November 2026. Some entries include short
Project Ben-Yehuda notes about misprints in the original.

Scans of the printed volumes are at the National Library of Israel (linked from
[Hebrew Wikipedia](https://he.wikipedia.org/wiki/מילון_בן-יהודה)) and the
[Internet Archive](https://archive.org/details/a-complete-dictionary-of-ancient-and-modern-hebrew-eliezer-ben-yehuda-images).
We did not compare the digital text with the scans. In at least six entries (דָּגָה I, זוֹל,
חָלַץ II, חֹשֶׁךְ, יָעַד, כְּבֵדֻת) the source appears to repeat one reference in place of many
different ones; the English follows the source.

## Why only volumes 1–5

The dictionary has 17 volumes (16 plus an introduction), published from 1908 to 1959.
Ben-Yehuda died in 1922. Five volumes had appeared by then, covering **א** through **לתת**,
that is, the letters א–ל. He and his assistant Moshe Bar-Nissim, who prepared much of the
German, French and English glossing, both died long enough ago (1922 and 1926) for copyright
terms of life plus 70 years to have ended. The volumes also predate 1931, so they are in the
public domain in the United States.

Volume 6 onward (מ–ת) appeared after his death. Moshe Zvi Segal (d. 1968) and Naftali Herz
Tur-Sinai (d. 1973) edited volumes 8–16 and wrote entries themselves, and their work may still
be protected. Volumes 6 and 7 were largely Ben-Yehuda's own and may well be free too, but we
drew the line where the case is clearest. This is our reading, not legal advice. Volume
history: [Hebrew Wikipedia](https://he.wikipedia.org/wiki/מילון_בן-יהודה).

## What has been translated so far

The translations began for an interlinear Hebrew prayer book, so the entries that match a word or
root in it were done first. The rest of volumes 1–5 is being added.

## How the English was made

Anthropic's Claude translated the entries from 22 November 2026, in batches shared among many
parallel AI workers following the same written rules:

- Translate each entry in full: every sense, quotation and source reference, in the printed
  order.
- Keep the dictionary's own German, French and English glosses.
- Expand source abbreviations (ברכ' → Berakhot) only when confident; otherwise leave them in
  Hebrew.
- Keep references as printed, even when they look misprinted.
- Leave quotations in Arabic, German and other languages in the script they are printed in.
- Keep Hebrew forms that the entry is discussing, and lists of related words, in Hebrew.
- Add no explanations, etymologies or interpretations.

A script checked that each entry had one English paragraph per Hebrew paragraph and that no
paragraph was suspiciously short or long. We also searched for placeholder text, dropped
references and leftover Hebrew, and repaired what we found. These checks catch missing text,
not wrong translations.

The rules were tightened as work went on, so the result is not uniform. Expect:

- Abbreviations expanded wrongly or inconsistently, and some left unexpanded.
- Some misprinted references silently corrected in early batches; most are kept as printed.
- Occasional added glosses, brackets or vowel points, and some notes not marked as notes.
- Medieval poetry and piyyut translated literally or approximately.
- Biblical and rabbinic quotations translated afresh or in familiar wording, not from one
  named published translation.

## License and citation

The compilers waive all their rights in the English translation and this compilation under
[CC0 1.0](LICENSE): use it for anything, including commercially, with no conditions. The Hebrew
text is in the public domain, as explained above; CC0 here makes no claim over it.

As a courtesy, not a condition, please cite it, and say that the English is an unreviewed AI
translation:

> *Ben-Yehuda's Hebrew Dictionary in English (volumes 1–5, א–ל)*. AI translation, 2026.
> https://github.com/raphaelrk/ben-yehuda-dictionary-english. Hebrew: Eliezer Ben-Yehuda,
> *A Complete Dictionary of Ancient and Modern Hebrew*, vols. 1–5; digitized by Project
> Ben-Yehuda, via Sefaria.

Please also credit Project Ben-Yehuda's volunteers and Sefaria. Neither is affiliated with this
project or has endorsed it. Corrections are welcome as issues or pull requests.
