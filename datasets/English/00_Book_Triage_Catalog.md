# English — Reference Material Triage Catalog

**Status: Phase 0 triage complete, 2026-10-26.** English has never been triaged or extracted in
this project before. It has just become first-priority because a sibling project,
`TepenianHawaiian`, is synthesizing a constructed language ("Modern Hawaiian") that starts as a
pidgin of **English, Japanese, and Tagalog** — English is the only one of the three structural
source languages not yet touched here. Japanese and Tagalog both already have full Phase 1
extractions in this repo; this catalog exists to bring English's source material up to the same
starting line.

Two separate source folders exist, both already in the repo, covering two different eras/registers
of the same language:

1. `source_reference/languages/English Grammar Ebook collection/` — **modern English**, the
   directly relevant stage for Hawaiian's pidgin-origin need. 21 real files (17 top-level + 4 inside
   one subfolder), ignoring `info.png`, `Info.txt`, `Thumbs.db`. (The dispatch brief estimated 22;
   direct inspection counts 21 — see file list below. Not a meaningful discrepancy, just a
   correction.)
2. `source_reference/languages/Old English Language Learning Pack/` — **historical English**
   (Old English/Anglo-Saxon through general history-of-English material), a different era/register
   entirely. 18 real files, confirmed against the brief's count. Triaged but treated as lower
   priority — Hawaiian's need is for English as it exists now, not its 5th-10th-century ancestor —
   though several files turn out to carry real, usable modern-English linguistic-description content
   alongside the historical content, flagged below.

No `graphify` command was run (forbidden for subagents in this repo). No `established/` files were
created. Nothing outside `datasets/English/` was modified.

**Update, 2026-10-27 — folder reorganized, 2 new foremost-priority files added by the developer.**
The `English Grammar Ebook collection` is now split into two subfolders:

- `foremost primary resources/` — **new**, 2 files, both major style/usage authorities rather than
  ESL teaching grammars (see the new section below). This is a real priority signal from the
  developer, not just a filing choice — both jump straight to Tier 0.
- `secondary resources/` — the original 21-file set from the 2026-10-26 pass, unchanged in content,
  just relocated one level deeper. All page counts, text-layer findings, and file names below are
  unaffected by the move; only the path prefix changed (add `secondary resources/` before each
  filename in the table below).

**Directly resolves the open "favor American English" item from the prior conversation turn**: one
of the two new files, *The Chicago Manual of Style* (16th ed.), has its grammar content written by
**Bryan A. Garner** — the same author as *Garner's Modern American Usage*, the standalone book
previously identified as a candidate acquisition. His CMOS chapter is the real, in-hand equivalent
of that still-unacquired book, at comparable authority. See the new file-list section below for the
verified page range and the companion file's (New Oxford Style Manual) British-vs-American
asymmetry.

---

## Headline numbers

| | `foremost primary resources/` (new, 2026-10-27) | `secondary resources/` (= the original English Grammar Ebook collection) | Old English Language Learning Pack |
|---|---|---|---|
| Real files | 2 | 21 (17 top-level + 4 in 1 subfolder) | 18 (17 top-level + 1 in 1 subfolder) |
| Confirmed real text layer | 2 of 2 | 14 of 21 | 13 of 18 (12 PDFs + 1 `.doc`) |
| Total pages | 3,354 (928 + 2,426) | — | — |
| Est. extractable words, in-scope sections only | ≈86,500 (CMOS ch. 5 Grammar and Usage, 259pp) + Oxford's New Hart's Rules Part One, ~430pp, not yet word-counted — see notes below; **do not estimate from total page count, most of both books is out of this project's scope** | — | — |

| | English Grammar Ebook collection (`secondary resources/`) | Old English Language Learning Pack |
|---|---|---|
| Real files | 21 (17 top-level + 4 in 1 subfolder) | 18 (17 top-level + 1 in 1 subfolder) |
| Confirmed real text layer | 14 of 21 | 13 of 18 (12 PDFs + 1 `.doc`) |
| Confirmed scan-only / no usable text layer | 5 of 21 (+ 2 are a format-duplicate pair) | 5 of 18 |
| Non-PDF format | 1 (`.doc`, readable — see below) | 1 (`.doc`, effectively textless — see below) |
| Format-duplicate pairs (same work, different file type/scan) | 2 pairs (function-based intro PDF+EPUB ×2 volumes; Grammar/English Grammar_Practice for Upper Intermediate Students scan ×2 copies) | 0 confirmed |
| Est. extractable words (clean-text files only, ~250 words/page) | **≈1.32M words** (≈1.16M from 4,645 PDF pages + 161,807 exact-counted words from the Cambridge `.doc`) | **≈918k words** (3,671 PDF pages) |
| Pages needing vision-reading/OCR before any extraction | 981 pages across 5 files (771 after dedup) + the 96MB near-textless `.doc` | 566 pages across 5 files + the 96MB near-textless `.doc` |
| Audio-only content found | 0 — both `CD 1/` and `CD 2/` folders under the Old English audio subfolder are **empty directories**, no actual audio files present | — |

---

## Full file list — `foremost primary resources/` (new, 2026-10-27)

| File | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `The Chicago Manual of Style [16th Edition] - University of Chicago Press Staff (2010).pdf` | 2,427 per `pdftotext` (PDF page count ≫ the ~1,026-page print 16th edition — not yet explained; could be a double-spaced/accessibility rendering or an expanded digital edition; not a scan-doubling artifact since the text layer is clean and single-column throughout) | **Yes — confirmed clean across the full document**, 2026-10-27. Full chapter map built from the book's own table of contents and verified against its own running headers (every chapter boundary below is a confirmed PDF page number, not an estimate). Systematic word-count sampling every 40 pages (61 sample points across all 2,427 pages) found only one page below 15 words — p.1521, confirmed by direct inspection to be a genuinely blank page (not a text-layer failure) between figures in chapter 11. No hidden scan-only stretch anywhere in the book. | **Tier 0 — highest priority in the entire English catalog** | **The single most valuable American-English source in this project to date.** Full chapter map (PDF page numbers): 1 Books and Journals 8–145 · 2 Manuscript Prep/Editing/Proofreading 146–294 · 3 Illustrations and Tables 295–407 · 4 Rights/Permissions/Copyright 408–515 · **5 Grammar and Usage (Bryan A. Garner) 516–774** · 6 Punctuation 775–905 · 7 Spelling/Compounds 906–998 · 8 Names and Terms 999–1201 · 9 Numbers 1202–1270 · 10 Abbreviations 1271–1358 · 11 Foreign Languages 1359–1523 · 12 Mathematics in Type 1524–1604 · 13 Quotations and Dialogue 1605–1685 · 14 Documentation I (Notes/Bibliography) 1686–2028 · 15 Documentation II (Author-Date) 2029–2090 · 16 Indexes 2091–2240 · Appendix A Production/Digital Technology 2241–2301 · Appendix B Glossary 2302–end. Chapter 5 is written by **Bryan A. Garner** — the same authority as the standalone *Garner's Modern American Usage* flagged as a candidate acquisition in the prior session; that acquisition is no longer necessary on current evidence. Chapters 6–11 and 13 (Punctuation, Spelling, Names and Terms, Numbers, Abbreviations, Foreign Languages, Quotations and Dialogue) are all genuine usage/register content, not pure production mechanics — real candidates for extraction alongside chapter 5. Chapters 1–4, 12, 14–16, and both appendices are publishing-industry production mechanics (manuscript prep, illustration layout, mathematical typesetting, citation-format rules, indexing mechanics) with no real English-language content to extract — triaged and mapped, but see the open scope question below before committing to extracting them anyway. |
| `New Oxford Style Manual - Oxford University Press (2016).pdf` | 929 per `pdftotext` | **Yes — confirmed clean across the full document**, 2026-10-27. Full chapter map built the same way as CMOS above, all 21 Part-One chapter boundaries confirmed via the book's own "CHAPTER N" running headers. Systematic word-count sampling every 15 pages (62 sample points) found no scan-only stretch anywhere. | **Tier 0 — highest priority, but note the nationality mismatch below** | This is **British**, not American — two parts in one continuous volume: **Part One, *New Hart's Rules*** (style/grammar rules, PDF pp.19–440) and **Part Two, the *New Oxford Dictionary for Writers and Editors*** (a usage/spelling dictionary, PDF pp.441–929). Full Part One chapter map (PDF page numbers): 1 The parts of a book 19 · 2 Preparing copy 44 · 3 Spelling and hyphenation 66 · 4 Punctuation 87 · 5 Capitalization 112 · 6 Names 125 · 7 Italic/roman/type treatments 145 · 8 Work titles in text 154 · 9 Quotations and direct speech 178 · 10 Abbreviations and symbols 192 · 11 Numbers and dates 204 · **12 Languages 223** · 13 Law and legal references 271 · 14 Science/mathematics/computing 284 · 15 Lists and tables 317 · 16 Illustrations and artwork 334 · 17 Notes and references 348 · 18 Bibliography 366 · 19 Indexing 395 · 20 Copyright and other publishing responsibilities 413 · **21 US and British English 425–440**. There is **no dedicated grammar chapter** the way CMOS has one — grammar content is distributed across chapters 3–12 instead. **Chapter 21, "US and British English" (only 16 pages, 425–440), is a genuine flagship find**: an explicit, focused American-vs-British contrast chapter, exactly the kind of register-divergence content this project's slang/register work values most — higher real priority than the chapter-count position suggests. Chapters 1–2, 7–8, 13–20 are production mechanics (bibliography formats, legal citation, typesetting, indexing) with no real language content. |

## Full file list — English Grammar Ebook collection (`secondary resources/`)

| File | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `Cambridge English Grammar In Use (Intermediate incl Answers)[A4].doc` | n/a (legacy `.doc`) | **Yes** — real, substantial (161,807 words via LibreOffice `--convert-to txt`; matches the file's own embedded metadata of 129,731 words reasonably closely) | **Highest** | Raymond Murphy's *English Grammar in Use*, 2nd ed. — a flagship, globally-used reference. **Format gotcha confirmed**: this is a genuine legacy Composite-Document-File `.doc`, not a corrupted file; `pdftotext`-style tools don't apply — convert via `soffice --headless --convert-to txt` (or equivalent) rather than treating it as unreadable. One cosmetic artifact: a Korean-language OCR-service stamp ("제작기관: 실로암시각장애인복지관" — "Produced by: Silloam Welfare Center for the Visually Impaired") plus a stray "@ff" glyph sit right after the title page — cosmetic, must be filtered, not extracted as content. |
| `Comprehensive Grammar[A4].pdf` | 436 | **Yes** (clean, verified mid-document) | **Highest** | A serious academic-register functional grammar (semantic categories: nouns/nominalizations, reference, plurality, etc. — Quirk/Greenbaum-school terminology). Strongest candidate for systematic grammar-point coverage beyond teaching-grammar level. |
| `English Grammar - A function-based introduction. Volume I.pdf` (in subfolder) | 340 | **Yes** (clean, verified mid-document) | **Highest** | Same functional-grammar tradition as Comprehensive Grammar above; likely meaningful non-redundant-supplement value once both are extracted. **Duplicate format**: the same subfolder also holds `Vol 1 - English Grammar - A function-based introduction.epub` — same work, EPUB container (6 split HTML chapter files inside) instead of PDF. Extract from the PDF; the EPUB is redundant. |
| `English Grammar - A function-based introduction. Volume II.pdf` (in subfolder) | 379 | **Yes** (clean, verified mid-document) | **Highest** | Same as above. **Duplicate format**: `Vol 2 - English Grammar - A function-based introduction.epub` is the same work in EPUB. Extract from the PDF. |
| `When Bad Grammar Happens to Good People[A4].pdf` | 256 | **Yes** (clean, verified mid-document) | **High — register-adjacent** | Ann Batko, 2004. Despite the title sounding slang/colloquial-focused, this is a conventional "avoid common errors" usage guide — moods, adjective agreement, etc. Its value is that it explicitly frames many entries as *common-but-nonstandard* usage contrasted with the "correct" form, which is directly useful register-contrast material (what educated modern English treats as an error vs. acceptable informal variant), not the same as a dedicated slang/colloquial source but genuinely above pure foundational-grammar value. |
| `Beyond Snobbery_Grammar Need not be Cruel to be Cool[A4].pdf` | 12 | **Yes** (clean, but see note) | **Medium — register commentary, not a reference** | June Casagrande's *ChangeThis* manifesto (a short promotional essay format, not a book chapter). It is genuinely about grammar-snobbery/prescriptivism-vs-descriptivism attitudes — exactly the register-adjacent topic the title promises — but it is argumentative prose, not a structured source with a vocabulary/grammar-point table to extract from. **Cosmetic-artifact gotcha**: the PDF is a *ChangeThis*-platform reader wrapper — every page's extracted text is polluted with UI chrome ("Save to disk [ help ]", "Hide/Show menus", "next", page-navigation icons, "No 28.04") interleaved with the real prose. Usable, but strip the UI chrome line-by-line rather than bulk-extracting. Low yield (12 pages) regardless. |
| `English Grammar for the Utterly Confused[A4].pdf` | 258 | **Yes** (clean, verified mid-document) | Medium-high | Conventional teaching grammar, clean text throughout. |
| `English Grammar Workbook for Dummies[A4].pdf` | 321 | **Yes** (clean, verified mid-document) | Medium | Workbook (drill-heavy per the spec's coverage-rule caveat — expect to skip repeated exercises). Cosmetic-only artifact: the cover page renders its title one giant character per line ("r/a/m/m/a/r/G/h/s/i…") — purely a stylized cover graphic, not real body text; does not affect the actual content pages. |
| `Complete Idiot's Guide to Grammar & Style, 2nd Ed (2003)[A4].pdf` | 432 | **Yes** (clean, verified mid-document) | Medium | Covers both grammar and style/writing-craft — broader than a pure grammar reference. |
| `Grammar and Usage for Better Writing (2004)[A4].pdf` | 270 | **Yes** (clean, verified mid-document) | Medium | AMSCO school-publications textbook; usage-and-writing focus, similar register value to the above. |
| `New Grammar Practice (Pre-intermediate with key)[A4].pdf` | 182 | **Yes** (clean, verified mid-document) | Medium | Workbook, pre-intermediate level — lower grammar-point density expected, per coverage-rule guidance. |
| `Basic English Grammar, Book 1[A4].pdf` | 159 | **Yes** (clean, verified mid-document) | Medium-low | Beginner workbook, explicitly aimed at younger students — foundational, low novel-content density expected. |
| `Basic English Grammar, Book 2[A4].pdf` | 154 | **Yes** (clean, verified mid-document) | Medium-low | Sequel to Book 1, same profile. |
| `The Grammar of English Grammars[A4].pdf` | 1446 | **Yes** (clean, Project Gutenberg plain-text transcription — very clean) | **Low for this project's current need, but flagged** | Goold Brown, 1851 — a monumental 19th-century prescriptive grammar. By far the largest file in this folder. Its register is 19th-century prescriptive, not modern colloquial English, so it's a poor match for Hawaiian's *modern*-English pidgin-origin need specifically — but it's a legitimate, large, clean-text historical-English source if this project ever wants an Early-Modern/19th-century stage for English itself (conceptually adjacent to the Old English pack's purpose, just a later era). Hold rather than prioritize. |
| `English Grammar_Practice for Upper Intermediate Students (2000)[A4].pdf` | 210 | **No** — confirmed scan-only despite an initial false positive (see gotcha below) | Medium — vision-read, **likely redundant**, see duplicate note | |
| `Grammar Practice for Upper Intermediate Students[A4].pdf` | 209 | **No** — confirmed scan-only (pure JBIG2/JPEG page-image PDF, no fonts at all per `pdffonts`) | Medium — vision-read | **Duplicate work, confirmed**: both files above are almost certainly the same book (Michael Vince's *Grammar Practice for Upper-Intermediate Students*, Macmillan) — same near-identical page count (210 vs. 209, the 1-page difference being the junk wrapper below), same scan profile. Vision-read one copy, not both. |
| `Grammar in Use_Reference and Practice for Intermediate Students of English[A4].pdf` | 147 | **No** — confirmed scan-only despite an initial false positive (see gotcha below) | Medium-high — vision-read | Likely the US-edition Murphy companion to the already-extractable UK-edition Cambridge `.doc` above (different unit numbering/content, not a straight duplicate of it — worth a direct comparison once both are read, but not assumed identical). |
| `Essential Grammar in Use_Supplementary Exercises[A4].pdf` | 113 | **No** — confirmed scan-only (pure JPEG/CCITT page images, no fonts) | Low-medium — vision-read, workbook | Supplementary-exercises companion volume; drill-heavy, lower expected yield once vision-read. |
| `Longman English Grammar Practice Intermediate_Self- Study Ed[A4].pdf` | 302 | **No** — confirmed scan-only (no fonts, no text on any sampled page) | Low-medium — vision-read, workbook | |

### New gotcha confirmed this pass: web-portal wrapper masks a scan-only PDF as having a text layer

**`English Grammar_Practice for Upper Intermediate Students (2000)[A4].pdf` and `Grammar in Use_Reference and Practice for Intermediate Students of English[A4].pdf` both initially looked text-bearing** (370 words extracted from pages 1-5 of each) — but that text is a **GetPedia.com web-portal wrapper page** (a scraped "Welcome to GetPedia.com: The Online Information Resource" directory-listing page, identical boilerplate in both files, confirmed via `grep -c "GetPedia"` returning 6 hits in each and nowhere else in the collection) prepended to what is otherwise a genuine scan-only book. Every sampled page beyond the wrapper (pages 15 through 200, at 10-page intervals) returned 0 words, and `pdfimages -list` confirms a full-page 300dpi JBIG2 scan image on every single page. **Lesson for extraction dispatch: don't trust a nonzero word count from only the first few pages as proof a PDF has a real text layer — sample across the full page range, and watch specifically for an injected web-scrape/portal page that can make an otherwise fully scan-only book look superficially text-bearing.** This is a new variant of the cosmetic-artifact-vs-real-text-layer distinction this project already tracks, not previously seen in this form.

### `.doc` format gotcha — two very different outcomes for legacy `.doc` files in this triage

Both English-era folders contain one legacy Composite-Document-File `.doc` (confirmed via `file`,
not a renamed/corrupted PDF). They turned out to be opposite cases:

- **Cambridge `.doc` (English Grammar collection) — fully readable, substantial text.** Its own
  embedded OLE metadata (`Number of Words: 129731`, `Number of Characters: 739467`) already
  signaled real content despite a misleading `Number of Pages: 1` field (a stale/unmaintained
  legacy-`.doc` metadata field, not a real page count — don't trust it). `soffice --headless
  --convert-to txt` converts it cleanly to a 161,807-word plain-text file. **Verdict: readable and
  extractable, just needs a `.doc`→text conversion step instead of `pdftotext`.**
- **`03 A Guide to Old English.doc` (Old English pack) — effectively textless despite being 96MB.**
  Its own embedded metadata reports `Number of Words: 28, Number of Characters: 160` — and this
  turned out to be accurate, not stale: converting it with the same LibreOffice pipeline produces a
  17-byte output file (just a byte-order-mark and blank lines). The 96MB file size is explained by
  **at least 174 embedded JPEG images** (confirmed via a raw byte scan for JPEG SOI markers) — this
  is a Word document used purely as a container for ~174 scanned page images, with no real text
  layer at all. **Verdict: effectively a scan-only source wearing a `.doc` extension; needs full
  vision-reading of the embedded images, not text conversion, and is a new format/gotcha variant
  worth watching for on any future `.doc` source — check the file's own OLE metadata word/character
  count before assuming a `.doc` converts cleanly just because another `.doc` in the same batch
  did.**

---

## Full file list — Old English Language Learning Pack

| File | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `18 A Concise Anglo-Saxon Dictionary.pdf` | 473 | **Yes, but garbled** — see gotcha below | Medium-high (dictionary, sample not exhaustive) | Largest reference in the pack; genuinely has a text layer but needs the two-column-dictionary and special-character gotchas below resolved before trusting any extracted entry. |
| `08 The Germanic Languages (Routledge).pdf` | 648 | **Yes** (clean, verified mid-document) | High | Comparative-Germanic linguistic-description volume — useful typological grounding (Old English in its Germanic family context), and the largest clean-text file in the pack. |
| `12 The Syntax of Early English.pdf` | 361 | **Yes** (clean, verified mid-document) | High | Directly structural/syntactic — likely the best match in this pack for grammar-point extraction in the usual sense. |
| `11 The History of English A Student's Guide.pdf` | 241 | **Yes** (clean, verified mid-document) | **High — spans into modern English** | Despite sitting in the Old English pack, a "history of English" survey by its nature covers Old → Middle → Early Modern → Modern English — likely the single best bridge file in this pack toward the project's actual modern-English need; worth checking its later chapters specifically. |
| `10 The English Language  A Historical Introduction.pdf` | 322 | **Yes** (clean, verified mid-document) | **High — spans into modern English** | Same profile as above — a historical-introduction survey, likely covers through to contemporary English in its later chapters. |
| `09 From Old English to Standard English.pdf` | 118 | **No** — confirmed scan-only | **High priority despite being vision-read** | Title explicitly promises the Old-English-to-Standard-(Modern)-English bridge this project actually needs; worth the vision-reading cost. |
| `02 Beginning Old English.pdf` | 264 | **Yes** (clean) | Medium-high | Teaching grammar for Old English itself; also contains direct Old English textual excerpts (see special-character gotcha below) and modern-English literary-translation discussion (sampled a Beowulf-translation comparison chapter). |
| `06 Old English A Linguistic Introduction.pdf` | 213 | **Yes** (clean, verified mid-document) | Medium-high | Linguistic-description volume, parallel in kind to Korean's and Dutch's "linguistic introduction"-titled sources that worked well previously. |
| `13 Reading Old English Texts.pdf` | 243 | **Yes** (clean, verified mid-document) | Medium | Primary-text reader with scholarly commentary (sampled discussion of oral-formulaic composition, Beowulf/Christ III citations) — real Old English quotations embedded, same special-character risk as above. |
| `16 A Critical Companion to Beowulf.pdf` | 417 | **Yes** (clean, verified mid-document) | Medium | Literary-critical, not primarily linguistic — lower grammar/vocabulary yield expected but may carry register-relevant discussion of translation choices. |
| `04 An Introduction to Old English.pdf` | 174 | **Yes** (clean, verified mid-document) | Medium | Another teaching grammar — apply non-redundant-supplement pattern against `02 Beginning Old English.pdf` once both are extracted. |
| `14 Old English Literature A Short Introduction.pdf` | 162 | **Yes** (clean, verified mid-document) | Low-medium | Literary survey, lower linguistic yield expected. |
| `15 The Poetics of Old English.pdf` | 153 | **Yes** (clean, verified mid-document) | Low-medium | Poetics/prosody-focused — niche value, possibly useful for understanding Old English's own register/style stratification if ever revisited. |
| `05 An Old English Grammar.pdf` | 90 | **No** — confirmed scan-only | Medium — vision-read | Despite the generic title, likely a compact dedicated grammar; worth the vision-reading cost if Old English is ever prioritized for real extraction. |
| `07 Old English and Its Closest Relatives.pdf` | 151 | **No** — confirmed scan-only | Low-medium — vision-read | Comparative-Germanic angle, overlaps conceptually with `08 The Germanic Languages` above (which has a clean text layer) — apply non-redundant-supplement logic, probably skip or sample lightly. |
| `17 Beowulf (Black Cat Publishing).pdf` | 57 | **No** — confirmed scan-only | Low — vision-read | A graded/simplified Beowulf reader edition (publisher known for simplified-reader series) — primary-text/literary, not a grammar reference; low priority regardless of format. |
| `Teach Yourself Old English Audio/Teach Yourself Old English.pdf` | 150 | **No** — confirmed scan-only | Medium — vision-read | The actual course book. **Audio-content check**: the sibling `CD 1/` and `CD 2/` folders in the same subfolder are confirmed **empty directories** — no actual audio files present despite the folder name, so there is no audio to transcribe here at all, only this PDF. |
| `03 A Guide to Old English.doc` | n/a (96MB, ~174 embedded JPEG images, ~0 real text) | **No** — see `.doc` gotcha above | Low — vision-read of embedded images only, high effort/low-certainty payoff | |

### New gotcha confirmed this pass: special Old English characters (þ/ð) corrupt even where the surrounding text layer is clean

Sampled directly from `02 Beginning Old English.pdf` (pages 132-137, a Beowulf-translation
discussion quoting the original Old English): macron-marked vowels (ā, ī, ē) and æ render
correctly, but **thorn (þ) and eth (ð) do not** — e.g. a line that should almost certainly read
something like "ðā þæt lyft-floga" / similar renders as "lā ƒ lyft-floga" and "Wæs êæs wyrmes" in
the raw extraction, with þ consistently appearing as "ƒ" and ð consistently appearing as "ê" in
this sample. This is the same *fixed-substitution-cipher-on-a-subset-of-special-characters* pattern
already catalogued for Cyrillic and CJK sources in `00_Reference_Extraction_Spec.md`, just not
previously seen on Old English's þ/ð. **Only confirmed in this one file/sample so far — per this
project's standing discipline, verify per-file (and per page-range, since Russian's Wave 1 found
ciphers that vary within a single file) before trusting any þ/ð in any Old English source's
extracted text, rather than assuming this specific "ƒ"/"ê" mapping holds elsewhere.**

### Confirmed gotcha recurrence: two-column dictionary scrambling, `18 A Concise Anglo-Saxon Dictionary.pdf`

Sampled pages 236-241: entries are visibly cross-contaminated mid-line (e.g. "llmw6rlg weary of
limb" sits beside "Ust mf. art, cleverness..." with no clear boundary, and OCR-character
substitution compounds the problem — "6" appearing mid-word where a macron almost certainly
belongs, "Ж" appearing where "Æ" almost certainly belongs). This is the exact two-column-glossary
interleaving gotcha already documented in `00_Reference_Extraction_Spec.md` (Serbian/Croatian/
Bosnian), now confirmed on an Old English source too — **extract this dictionary via column-aware
bounding-box extraction, not a single `pdftotext -layout` pass, and treat any apparent special
character as suspect until cross-checked against a known headword.**

### Numbering gap

Files are numbered `02` through `18` at the top level — there is no `01`. Nothing is missing from
the delivered folder; the pack's original compiler apparently never included (or numbered)
whatever would have been file `01`. Not a gotcha, just noted so a future dispatcher doesn't go
looking for a nonexistent file.

---

## OCR/scan status summary

**English Grammar Ebook collection: 5 of 21 files (~24%) have no usable text layer**, lower than
every language this project has triaged so far (Korean ~35%, SCB ~56%, Hungarian ~50%). Two of
those 5 are a confirmed duplicate pair of the same work, so realistically only 4 distinct works
need vision-reading.

**Old English Language Learning Pack: 5 of 18 files (~28%) have no usable text layer**, plus the
96MB `.doc` which is scan-only in substance despite its format. Consistent with this project's
running observation that roughly a quarter to a half of any given corpus needs vision-reading
rather than clean text extraction.

---

## Morphological typology (preliminary, per Phase 0 convention)

**English: predominantly isolating/analytic**, in sharp contrast to every agglutinative language
this project has extracted so far (Korean, Hungarian, Japanese, Tagalog's non-concatenative
trigger system). Grammatical relationships are carried mostly by word order, auxiliary verbs, and
a small closed set of inflectional suffixes (plural `-s`, past tense `-ed`, possessive `-'s`,
progressive `-ing`, comparative `-er`/`-est`) rather than by stacking bound morphemes onto a stem.
This matters directly for the Hawaiian-pidgin sibling project: a pidgin typically strips away the
donor languages' morphology toward a simpler, more isolating grammar — English's own already-low
morphological complexity (relative to Japanese's agglutination and Tagalog's
trigger/focus system) likely makes English the *structurally simplest* of the three donor
languages to absorb into a pidgin base, which is worth flagging explicitly for whoever does the
mechanics-analysis phase once extraction begins. No morpheme-breakdown convention is needed for
most English vocabulary extraction (simple, non-composed lexical items are the norm) — reserve it
for genuinely compound/derived forms where an atomic gloss would hide real structure (e.g.
un-believ-able, un-friend-ly).

---

## Priority tiers

**Tier 0 — style/usage authorities, dispatch before everything else (full chapter map confirmed 2026-10-27):**
- `foremost primary resources/The Chicago Manual of Style [16th Edition]...pdf` — ch.5 Grammar and Usage (pp.516–774) first, then chs. 6, 7, 8, 9, 10, 11, 13 (Punctuation, Spelling, Names and Terms, Numbers, Abbreviations, Foreign Languages, Quotations and Dialogue — all genuine usage/register content). Chapters 1–4, 12, 14–16, and both appendices are production mechanics with no language content — **see the open scope question below on whether to extract these anyway for completeness.**
- `foremost primary resources/New Oxford Style Manual - Oxford University Press (2016).pdf` — ch.21 US and British English (pp.425–440) first — a genuine explicit register-contrast flagship despite being short — then chs. 3–6, 9–12 (Spelling/hyphenation, Punctuation, Capitalization, Names, Quotations, Abbreviations, Numbers, Languages). Chapters 1–2, 7–8, 13–20, and the dictionary half (Part Two) are production mechanics / dictionary-scale — **same open scope question applies.**

**Open scope question, not yet resolved — see note to the developer below:** this catalog identifies which chapters of both books carry real English-language content vs. pure publishing-industry production mechanics (citation formats, typesetting, indexing). Per this project's standing convention (used for every other oversized/low-value source so far — dictionaries sampled not exhaustive, fiction excluded, tourism guides excluded), the production-mechanics chapters would normally be held/skipped rather than extracted. Whether to extract them anyway, for completeness, is a developer decision — not assumed either way here.

**Tier 1 — comprehensive modern-grammar references (highest value, dispatch first):**
- `Cambridge English Grammar In Use (Intermediate incl Answers)[A4].doc` — flagship, via `.doc`→text conversion
- `Comprehensive Grammar[A4].pdf`
- `English Grammar - A function-based introduction. Volume I.pdf` + `Volume II.pdf` (PDFs only — skip the duplicate EPUBs)

**Tier 2 — register-adjacent and historical-to-modern bridge material:**
- `When Bad Grammar Happens to Good People[A4].pdf` (common-error/register-contrast value)
- `Grammar in Use_Reference and Practice for Intermediate Students of English[A4].pdf` (vision-read; likely a US-edition Murphy companion, not a straight duplicate of the Cambridge `.doc`)
- `11 The History of English A Student's Guide.pdf` and `10 The English Language A Historical Introduction.pdf` (Old English pack, but both survey through to modern English — check their later chapters specifically for directly modern-English-relevant content)
- `Beyond Snobbery_Grammar Need not be Cruel to be Cool[A4].pdf` (short, but genuinely register-attitude content once the UI-chrome artifact is stripped)

**Tier 3 — solid supplementary references and workbooks (apply non-redundant-supplement dispatch once Tier 1 is extracted):**
- `English Grammar for the Utterly Confused[A4].pdf`, `English Grammar Workbook for Dummies[A4].pdf`, `Complete Idiot's Guide to Grammar & Style, 2nd Ed (2003)[A4].pdf`, `Grammar and Usage for Better Writing (2004)[A4].pdf`, `New Grammar Practice (Pre-intermediate with key)[A4].pdf`, `Basic English Grammar, Book 1[A4].pdf` + `Book 2[A4].pdf`
- Old English pack's clean-text linguistic-description volumes: `08 The Germanic Languages`, `12 The Syntax of Early English`, `02 Beginning Old English`, `06 Old English A Linguistic Introduction`, `13 Reading Old English Texts`, `04 An Introduction to Old English`, `16 A Critical Companion to Beowulf`

**Tier 4 — vision-reading required (dispatch last, highest per-file cost):**
- English Grammar collection: `Grammar Practice for Upper Intermediate Students[A4].pdf` (one copy only — skip the GetPedia-wrapped duplicate), `Essential Grammar in Use_Supplementary Exercises[A4].pdf`, `Longman English Grammar Practice Intermediate_Self- Study Ed[A4].pdf`
- Old English pack: `09 From Old English to Standard English.pdf` (worth prioritizing within this tier — directly bridges to modern English), `05 An Old English Grammar.pdf`, `07 Old English and Its Closest Relatives.pdf`, `Teach Yourself Old English Audio/Teach Yourself Old English.pdf`, `17 Beowulf (Black Cat Publishing).pdf`, `03 A Guide to Old English.doc` (lowest priority in this tier — embedded-image vision-reading of a 96MB container for uncertain payoff)

**Tier 5 — hold / low priority for the current (modern-English) need:**
- `The Grammar of English Grammars[A4].pdf` (huge, clean, but 19th-century prescriptive register — not a good match for a modern pidgin-origin need; revisit only if this project later wants a dedicated Early-Modern/19th-century English stage)
- `18 A Concise Anglo-Saxon Dictionary.pdf` (real value for Old English specifically, but needs the two-column + þ/ð decode work resolved first and is dictionary-scale — sample, don't exhaustively transcribe, same treatment as every other language's dictionary-scale sources)
- `14 Old English Literature A Short Introduction.pdf`, `15 The Poetics of Old English.pdf` (literary/niche, low linguistic yield expected)

---

## Recommended wave structure

**Wave 0 — style/usage authorities, language-content chapters (full chapter map confirmed 2026-10-27, dispatch before Wave 1):**
0a. CMOS ch.5 Grammar and Usage, PDF pp.516–774 (highest priority in this wave)
0b. Oxford ch.21 US and British English, PDF pp.425–440 (short but a genuine flagship register-contrast find)
0c. CMOS chs. 6–11 and 13 (Punctuation, Spelling, Names and Terms, Numbers, Abbreviations, Foreign Languages, Quotations and Dialogue), PDF pp.775–1523 and 1605–1685
0d. Oxford chs. 3–6 and 9–12 (Spelling/hyphenation, Punctuation, Capitalization, Names, Quotations, Abbreviations, Numbers, Languages), PDF pp.66–157 and 178–270

**Wave 0b — production-mechanics chapters of both books, pending a scope decision (see the open question above):** CMOS chs. 1–4, 12, 14–16, Appendices A–B; Oxford chs. 1–2, 7–8, 13–20 and the full dictionary (Part Two). Not scheduled until the developer confirms whether to extract these for completeness or hold them per the project's usual low-value-content convention.

**Wave 1 — flagship modern-grammar references, clean text (dispatch first, highest confidence):**
1. `Cambridge English Grammar In Use (Intermediate incl Answers)[A4].doc` (`.doc`→text conversion)
2. `Comprehensive Grammar[A4].pdf`
3. `English Grammar - A function-based introduction. Volume I.pdf`
4. `English Grammar - A function-based introduction. Volume II.pdf`

**Wave 2 — register-adjacent + remaining clean-text supplements:**
5. `When Bad Grammar Happens to Good People[A4].pdf`
6. `Beyond Snobbery_Grammar Need not be Cruel to be Cool[A4].pdf` (strip UI chrome)
7. `English Grammar for the Utterly Confused[A4].pdf`
8. `English Grammar Workbook for Dummies[A4].pdf`
9. `Complete Idiot's Guide to Grammar & Style, 2nd Ed (2003)[A4].pdf`
10. `Grammar and Usage for Better Writing (2004)[A4].pdf`
11. `New Grammar Practice (Pre-intermediate with key)[A4].pdf`
12. `Basic English Grammar, Book 1[A4].pdf` + `Book 2[A4].pdf` (non-redundant-supplement pattern against Waves 1-2's foundational content by this point)

**Wave 3 — vision-reading, English Grammar collection:**
13. `Grammar in Use_Reference and Practice for Intermediate Students of English[A4].pdf`
14. `Grammar Practice for Upper Intermediate Students[A4].pdf` (one copy; skip the GetPedia-wrapped duplicate)
15. `Essential Grammar in Use_Supplementary Exercises[A4].pdf`
16. `Longman English Grammar Practice Intermediate_Self- Study Ed[A4].pdf`

**Wave 4 — Old English pack, clean-text, prioritizing the modern-English bridge volumes:**
17. `11 The History of English A Student's Guide.pdf`
18. `10 The English Language  A Historical Introduction.pdf`
19. `08 The Germanic Languages (Routledge).pdf`
20. `12 The Syntax of Early English.pdf`
21. `02 Beginning Old English.pdf` (watch for þ/ð cipher)
22. `06 Old English A Linguistic Introduction.pdf`
23. `13 Reading Old English Texts.pdf` (watch for þ/ð cipher)
24. `04 An Introduction to Old English.pdf` (non-redundant-supplement vs. #21)
25. `16 A Critical Companion to Beowulf.pdf`
26. `14 Old English Literature A Short Introduction.pdf`
27. `15 The Poetics of Old English.pdf`

**Wave 5 — Old English pack, vision-reading:**
28. `09 From Old English to Standard English.pdf` (prioritize within this wave)
29. `05 An Old English Grammar.pdf`
30. `07 Old English and Its Closest Relatives.pdf`
31. `Teach Yourself Old English Audio/Teach Yourself Old English.pdf`
32. `17 Beowulf (Black Cat Publishing).pdf`

**Wave 6 — hold/low-priority, dispatch only if the project later decides to deepen English coverage beyond Hawaiian's immediate pidgin-origin need:**
33. `The Grammar of English Grammars[A4].pdf` (1446pp — plan multiple sub-chunk files per the spec's "don't let a single file grow unbounded" rule if ever dispatched)
34. `18 A Concise Anglo-Saxon Dictionary.pdf` (sampled, not exhaustive; resolve two-column + þ/ð cipher first)
35. `03 A Guide to Old English.doc` (embedded-image vision-reading; lowest-confidence payoff in the whole catalog)

This is now a 37-item plan across 7 waves (added Wave 0, 2 items, 2026-10-27), well within the
platform's 20-concurrent-subagent ceiling if each wave above is dispatched as its own batch (the
largest wave, Wave 4, is 11 items — safe headroom below the cap even run as a single wave).
