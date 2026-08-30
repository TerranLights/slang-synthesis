# Slang Corpus Collection Index

**Purpose.** Tracks, per real-world language, whether a slang corpus has been collected via web
research and where it lives. Mirrors the maintenance discipline used elsewhere for book
extraction: **when a language's corpus collection starts or finishes, update this file in the
same commit.** A corpus nobody can find is a corpus that gets collected twice.

**Status legend:**
- `not started` — no corpus collection has begun
- `in progress` — partially collected, see the language's own `00_Extraction_Checklist.md`
- `complete` — corpus collection finished for this language (analysis may still be pending, see
  `datasets/00_Analysis_Index.md`)

**Folder convention.** Each language in progress or complete gets its own folder here:
`language_corpus/<Language>/`, containing a `00_Extraction_Checklist.md` (tracks web sources
consulted, slang terms/phrases found, what's still missing) plus numbered output files
(`01_...md`, `02_...md`, ...) holding the actual collected corpus. Copy `_TEMPLATE/` to start a
new language.

**Reference column.** Cross-references whether standard grammar/vocabulary reference material for
that language already exists in `source_reference/languages/` — corpus collection can proceed
without it, but analysis (see `datasets/`) benefits from having it.

**Scaling.** Don't let corpus content pile into one or two giant files — split by register/domain/
era/source and start new numbered files as existing ones get unwieldy (see the per-language
`00_Extraction_Checklist.md`). Each language gets its **own** `graphify-out/` scoped to
`language_corpus/<Language>/`, never one repo-wide graph.

---

## Status by language

| Language | Reference available? | Corpus status | Folder |
|---|---|---|---|
| Akkadian | yes | not started | — |
| Albanian | yes | not started | — |
| Armenian | yes | not started | — |
| Avestan | yes (unsorted) | not started | — |
| Cantonese | yes | not started | — |
| Danish | yes | not started | — |
| Dutch | yes | not started | — |
| English (Old English) | yes | not started | — |
| Esperanto | yes | not started | — |
| Estonian | yes | not started | — |
| Finnish | yes | not started | — |
| French | yes | not started | — |
| Greek (Modern) | yes | not started | — |
| Greek (Ancient/TTC) | yes | not started | — |
| Hebrew | yes | not started | — |
| Hungarian | yes | not started | — |
| Icelandic | yes | not started | — |
| Irish | yes | not started | — |
| Italian | yes | not started | — |
| Japanese | yes | not started | — |
| Kazakh | yes | not started | — |
| Korean | yes | not started | — |
| Kurdish | yes | not started | — |
| Latvian | yes | not started | — |
| Lithuanian | yes | not started | — |
| Mandarin | yes | not started | — |
| Middle Egyptian | yes | not started | — |
| Mongolian | yes | not started | — |
| Nahuatl | yes | not started | — |
| Persian | yes | not started | — |
| Quechua | yes | not started | — |
| Romanian | yes | not started | — |
| Russian | yes | not started | — |
| Sanskrit | yes | not started | — |
| Serbian/Croatian/Bosnian | yes | not started *(test-run language — Phase 1 reference extraction in progress in `datasets/`, Phase 2 corpus collection not yet started; see `methodology-observations/serbian_croatian_bosnian_test_run.md`)* | `language_corpus/Serbian_Croatian_Bosnian/` |
| Slovene | yes | not started | — |
| Spanish | yes | not started | — |
| Sumerian | yes | not started | — |
| Swahili | yes | not started | — |
| Swedish | yes | not started | — |
| Syriac (Classical) | yes | not started | — |
| Tamil | yes | not started | — |
| Tibetan | yes | not started | — |
| Turkish | yes | not started | — |

**Note on `source_reference/languages/`:** several entries there are stray top-level files rather
than per-language folders (`chiar.jpg`, `Ocean of Milk, Ocean of Blood...pdf` and `Secret History
of the Mongols...pdf` — both belong under Mongolian, `Romanian collection.zip.gz` — likely
redundant with the `Romanian/` folder, `xx--stash`, `Complete Series (Books-Audio)`, `lang
transfer bay`, `Michel Thomas`). Not reorganized as part of this scaffolding pass — flagged here so
a future pass doesn't rediscover the mess from scratch.

---

## Maintenance rule

**When a language's corpus collection begins, add its folder here and flip status to `in
progress` in the same commit.** When it's marked `complete`, cross-check whether
`datasets/00_Analysis_Index.md` needs a corresponding row started.
