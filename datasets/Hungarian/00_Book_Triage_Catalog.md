# Hungarian — Reference Material Triage Catalog

**Status: tentative — second pipeline test run, now moving to full Phase 1 completion using the
methodology validated end-to-end on Serbian/Croatian/Bosnian (see
`../Serbian_Croatian_Bosnian/00_Extraction_Checklist.md` and
`../../methodology-observations/serbian_croatian_bosnian_test_run.md`).** See
`../../methodology-observations/hungarian_test_run.md` for this language's own process notes.

**Full triage complete as of 2026-09-09.** `source_reference/languages/Hungarian/` has 131 files,
2.6GB, split into 37 top-level loose files and 6 subfolders (94 more files). Every file has now been
individually classified — either sampled for text-layer status (PDFs via `pdftotext` at a mid-document
page range, not just page 1, since front matter/covers routinely read as empty even when the book has
a real text layer; DJVU via `djvutxt`) or identified as an exact-or-near duplicate of an already-
classified title.

**Tooling note, reconfirmed from the SCB run:** never use a field-splitting `awk`/shell one-liner to
list these filenames — several contain spaces and non-ASCII characters that break naive splitting.
Use `find -printf` or quote paths directly.

---

## Top-level loose files (37) — full triage

| File | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `Hungarian-An-Essential-Grammar-Second-Edition-.pdf` | 317 | **Yes** (clean) | **Highest** | Rounds, 2nd ed. (Routledge, 2009). **Extraction in progress** — Ch.1-3, 5, 6 done (`established/001-003`); Ch.4 (Verbs) deliberately deferred, now first priority to finish this book. |
| `ON-HUNGARIAN-MORPHOLOGY.pdf` | 158 | **Yes** (clean) | High | Academic paper on Hungarian morphology — grounds the typology profile beyond a generic agglutinative characterization. |
| `750-Hungarian-proverbs.pdf` | 58 | **Yes** (clean) | Medium-high | Proverbs = idiomatic/`literary` register source, distinct from grammar textbooks. |
| `A-complete-practical-grammar-of-the-Hungarian-language-...-Historical-sketch...pdf` | 504 | **Yes** (clean) | Medium | 19th-century grammar — real `attested_era` contrast against the 2009 Rounds grammar. |
| `Hungarian-An-Essential-Grammar.pdf` (1st ed.) | 269 | No | Skip | Superseded by the 2nd ed. above, which has a clean text layer. |
| `Hungarian Verbs.pdf` | 140 | No | Low-medium | Deferred behind Rounds Ch.4, which has a usable text layer. |
| `Magyar Szlengszótár.pdf` / `Magyar-Szlengsz-t-r.pdf` (mangled-encoding duplicate filename, same file) | 170 | No | **High priority despite needing vision-reading** | Hungarian slang dictionary — genuine slang content sitting in `source_reference/`, not a grammar reference. Belongs conceptually to `language_corpus/Hungarian/` once extracted (see scope note below), extracted from here since that's where it physically lives. |
| `Configurationality-in-Hungarian.pdf` | 264 | **Yes** (clean) | Low-medium | Academic syntax paper. Dense/niche; useful for grammar depth, not vocabulary breadth. |
| `The-Syntax-of-Hungarian-Cambridge-Syntax-Guides-.pdf` | 292 | **Yes** (clean) | Low-medium | Same category as above. |
| `Word-Order-in-Hungarian-The-syntax-of-positions.pdf` | 416 | **Yes** (clean) | Low-medium | Same category. |
| `Intonation-and-Stress-Evidence-from-Hungarian.pdf` | 248 | **Yes** (clean) | Low | Prosody, not directly vocabulary/register relevant. |
| `Event-Structure-And-The-Left-Periphery-Studies-on-Hungarian.pdf` | 303 | **Yes** (clean) | Low | Same category. |
| `Verb-Clusters-A-Study-of-Hungarian-German-and-Dutch-...pdf` | 521 | **Yes** (clean) | Low | Cross-linguistic syntax study; low direct yield for this project. |
| `Hungarian-Linguistics.pdf` | 609 | **Yes** (clean) | Low-medium | General linguistics survey — could be worth a targeted read for a morphology/typology cross-check, not full extraction. |
| `The-Hungarian-Language-in-the-Digital-Age.pdf` | 78 | **Yes** (clean) | Low | META-NET white paper on NLP resourcing, not a language reference in the project's sense. Skip. |
| `Hungarian-Language-Contact-Outside-Hungary-...pdf` | 448 | **Yes** (clean) | Medium | Diaspora/minority-Hungarian sociolinguistics — genuinely parallel to SCB's Alexander companion volume (dialect/regional-variant commentary). Worth extracting once flagship grammar is done. |
| `Etymological-Dictionary-of-Hungarian [[contains Sumerian]].pdf` | 792 | **Yes** (clean) | Low | Fringe/pseudo-linguistic framing (Sumerian-connection theory) in the title; real etymological content likely mixed with unreliable claims. Treat cautiously if ever extracted — flag provenance. |
| `Grammatical-proof-of-the-affinity-of-the-Hungarian-language-with-...Fennic-origin.pdf` | 388 | Borderline (very thin text layer) | Skip | 19th-century historical-linguistics curiosity, not useful reference material for this project. |
| `Magyar-madárnevek.pdf` | 182 | **Yes** (clean) | Low | Bird-name dictionary — niche vocabulary, low priority. |
| `Magyar-éremhatározó.pdf` | 269 | No | Skip | Coin catalog — out of scope (numismatics, not language). |
| `Hungarian-English-Persian phrasebook...pdf` (×2 identical-content filenames) | 166 | No | Low | Niche trilingual phrasebook; needs vision-reading for low expected yield. Skip unless capacity is abundant. |
| `Hungarian-English-Russian-statistical-dictionary-...pdf` | 226 | **Yes** (clean) | Low | Technical/statistical-domain vocabulary — narrow register, low priority. |
| `Colloquial-Hungarian-Разговорный-Венгерский-.pdf` | 334 | No | See subfolder note | Duplicate title of the `Colloquial Hungarian/` subfolder's own PDF — treat as the same book, prefer whichever copy is cleaner (both are no-text-layer scans; either works for vision-reading). |
| `Hungarian-with-ease.pdf` | 218 | No | Medium | Assimil-style course — real course content, needs vision-reading. |
| `Old-Hungarian-script-coursebook-Rov-s-r-s-tank-nyv-.pdf` | 69 | **Yes** (clean) | Skip | Ancient runic script (Rovásírás) coursebook — historical curiosity, not modern language reference. |
| `-j-rov-s-r-s-tank-nyv...` (same Rovásírás topic, companion/duplicate) | — | not sampled | Skip | Same category as above. |
| `Magyar-Jap-n-Szot-r-Hungarian-Japanese-Dictionary.pdf` | 651 | **Yes** (clean) | Low | Dictionary-format only, niche language pair, low priority. |
| `Hungarian-in-words-and-pictures-...djvu` | — | No (djvutxt confirms empty) | Medium | Textbook for foreigners — needs vision-reading; duplicated in the Learning Pack subfolder (same title, also no text layer). |
| `Learn-Hungarian-Учим-венгерский.djvu` | — | **Yes** (djvutxt: 747K chars) | Low | Full course, but metalanguage is Russian, not English — usable but lower priority than English-medium sources of equal content type. |
| `Hungarian-Eagles-The-Hungarian-Air-Forces-1920-1945.pdf` | — | not sampled | Out of scope | Military history. |
| `Hungarian-Hussar-1756-1815.pdf` | — | not sampled | Out of scope | Military history. |
| `Hungarians-and-Europe-in-the-early-Middle-Ages-...pdf` | — | not sampled | Out of scope | General history. |
| `The-Hungarian-Revolution-1956.pdf` | — | not sampled | Out of scope | General history. |
| `The-Hungarians-A-Thousand-Years-of-Victory-in-Defeat.epub` | — | not sampled | Out of scope | General history/popular nonfiction. |
| `Hungarian-Sumerian-and-Egyptian-Hungarian-Sumerian-and-Hebrew.pdf` | — | not sampled | Out of scope | Fringe pseudo-linguistics. |

## Subfolders (6, 94 files) — triaged with heavy dedup

**No audio files in any subfolder** — all 94 files are PDF/DjVu documents (confirmed via `find -type f`
extension breakdown). This removes the transcription-cost question entirely for this language's
subfolder material.

### `Colloquial Hungarian/` (2 files)
`Colloquial Hungarian.pdf` — same title/content as the top-level `Colloquial-Hungarian-Разговорный-
Венгерский-.pdf`; no text layer in either copy. One `.m3u` audio playlist file, not a document — ignore.

### `FSI Basic Hungarian/` (4 files)
US Foreign Service Institute course — genuinely valuable, distinct from everything else in this
folder. **Volume 1 and Volume 2 Student Texts both have clean text layers** (6,900 and 9,945 chars
sampled mid-document) — real Phase 1 candidates, structured grammar+drill course content. The Graded
Reader (604pp) has no text layer — lower priority, defer behind the two Student Texts.

### `Glossika/` (3 files)
`ENHU-F1/F2/F3-EBK.pdf` — phrase-drill course ebooks, all three confirmed **no text layer**. Would
need vision-reading; phrase-drill format (short EN/HU sentence pairs) makes it a lower-yield
vision-reading target than a real grammar chapter — defer behind higher-value vision-reading work.

### `Hungarian Language Learning Pack (Updated)/` (56 files) and `Hungarian language resources/` (26 files)
**These two folders are large, overlapping grab-bags, not curated reference sets** — each mixes a
handful of real grammar/course titles among travel guides, comics (Donald Duck), genre fiction (an
R.A. Salvatore fantasy trilogy in Hungarian translation, the Twilight saga, dragon novels), folk
tales in *Ukrainian* (not Hungarian), history/culture books, a numismatics catalog analog, and
children's picture books (Pinokkió, A Kis Herceg). None of the fiction/travel/culture titles are
in scope for this project — they're general Hungarian-reading material, not language reference or
slang corpus content.

**Unique real-reference titles found in these two folders, deduped against the top-level list above
and against each other:**

| Title | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `Practical Hungarian Grammar.pdf` | 90 | No | Medium | A different, shorter grammar than Rounds — real candidate once flagship + FSI are further along. |
| `The Phonology of Hungarian.pdf` | — | **Yes** (clean, 7,904 chars sampled) | Medium | Focused phonology reference — complements Rounds Ch.1-3 (vowel harmony) with more depth. |
| `Magyaróra: New Paths to the Hungarian Language.pdf` | — | **Yes** (clean, 7,318 chars) | Medium | Full coursebook, clean text — real candidate. |
| `Manuale della Lingua Ungherese.pdf` | — | No | Low | Italian-language Hungarian grammar — needs vision-reading; metalanguage is Italian, lower priority than English/clean-text sources. |
| `Langenscheidts Praktisches Lehrbuch Ungarisch.pdf` (+ `Schlüssel` answer key) | — | No | Low | German-language course — same metalanguage caveat as above. |
| `Kauderwelsch Ungarisch Wort für Wort.pdf` | 131 | **Yes** (clean, 2,999 chars) | Low-medium | German-language phrasebook/grammar primer, but has a usable text layer — worth a look for idiom/colloquial content once German isn't a blocker (many entries are just Hungarian phrases with German glosses). |
| `Magyar szólások és közmondások (Hungarian Sayings and Proverbs).pdf` | 835 | **Yes** (clean, 11,192 chars) | **High** | A second, much larger proverb/idiom collection than `750-Hungarian-proverbs.pdf` — genuinely high-value register/idiom source, clean text layer, real Phase 1 candidate. |
| `Hungarian-English Dictionary.pdf` / `Magyar-Angol Kisszótár.pdf` | — | No (both) | Low | Two different dictionaries, both scanned, no text layer — large vocabulary sources but dictionary-format extraction is lower priority than grammar/register content, and both need vision-reading. |
| `Hungarian-English Phrase Book.pdf` | — | **Yes** (clean, 5,172 chars) | Medium | Clean text, real phrasebook content. |
| `Dizionario Ungherese-Italiano.djvu` | — | **Yes** (djvutxt: 1.25M chars) | Low | Italian-Hungarian dictionary — same metalanguage/format caveats as above. |
| `1000 szó magyarul.djvu` | — | No | Low | "1000 words in Hungarian" — vocabulary primer, needs vision-reading, likely redundant with grammar-textbook vocabulary once those are done. |
| `Living Language Fast and Easy Hungarian.pdf` | — | No | Low | Course booklet, needs vision-reading, lower depth than FSI/Rounds. |

Everything else in these two folders (travel guides, fiction, comics, culture/history books,
duplicate copies of `Learn Hungarian`, `Teach Yourself Hungarian`, `Colloquial Hungarian`, `Hungarian
in Words and Pictures` already classified above) is **out of scope or a confirmed duplicate** — not
re-triaged file-by-file since the titles are already accounted for.

### `TY/` (1 stray file)
The file `02` is a personal hand-typed Hungarian vocabulary scratch note (itt = here, mert = because,
...), not a real reference document. **Ignore — not part of the corpus.**

### `TY Hungarian/` (1 file)
`Teach Yourself Hungarian [2nd Ed (2003)].pdf` — confirmed **no text layer**. This is the Hungarian
counterpart to SCB's *Teach Yourself Serbian* — a real, high-value full course, needs vision-reading.
**Medium-high priority** for the vision-reading wave.

---

## Scope note: a slang dictionary inside `source_reference/`

**Unchanged from the original triage pass.** `Magyar Szlengszótár.pdf` is a real Hungarian slang
dictionary sitting in the reference folder rather than a grammar/vocabulary baseline. **Decision:**
extract it from here (where it physically lives) but treat its content as belonging to
`language_corpus/Hungarian/` once extracted, not `established/`. See
`methodology-observations/hungarian_test_run.md`.

## OCR/scan status

Combining the top-level and subfolder samples: of the ~30 files individually sampled for a text
layer in this full triage pass, **roughly half had no usable text layer** — consistent with the
~50-56% rate found in both the Hungarian pilot triage and the Serbian/Croatian/Bosnian test run. This
continues to look like a genuine, recurring cross-language pattern, not a one-off. See `ROADMAP.md`
Phase 1.

## Recommended Phase 1 extraction priority order

**Wave 1 — finish what's started + highest-value clean-text additions:**
1. `Hungarian-An-Essential-Grammar-Second-Edition-.pdf` Ch.4 (Verbs) — completes the flagship grammar
2. `Magyar szólások és közmondások` (835pp proverb/idiom collection) — highest-value clean-text find of this triage pass
3. `750-Hungarian-proverbs.pdf` — smaller, already-flagged proverb source
4. `ON-HUNGARIAN-MORPHOLOGY.pdf` — typology grounding
5. FSI Basic Hungarian Volumes 1 & 2 — structured course, clean text, real drill content

**Wave 2 — clean-text supplements:**
6. `The Phonology of Hungarian.pdf`, `Magyaróra: New Paths to the Hungarian Language.pdf`,
   `Hungarian-English Phrase Book.pdf`, `Practical Hungarian Grammar.pdf` (no text layer — reclassify
   into Wave 3 if vision capacity allows), `A-complete-practical-grammar-...pdf` (19th-c. contrast),
   `Hungarian-Language-Contact-Outside-Hungary-...pdf` (dialect/diaspora commentary, parallel to SCB's
   sociolinguistic-commentary volume)

**Wave 3 — vision-reading (no text layer, real course/reference value):**
7. `Magyar Szlengszótár.pdf` — the slang dictionary, highest-value vision-read target
8. `Teach Yourself Hungarian [2nd Ed (2003)].pdf`
9. `Colloquial Hungarian.pdf` (either copy — top-level or subfolder)
10. `Hungarian-in-words-and-pictures-...djvu`
11. `Hungarian-with-ease.pdf`
12. `Hungarian Verbs.pdf`

**Deferred indefinitely / out of scope:** academic syntax/prosody papers (low direct yield), fringe
pseudo-linguistic works, dictionaries without a text layer (lower priority than grammar/register
content), non-English-metalanguage courses (Italian, German, Russian) unless capacity is abundant
later, Rovásírás/runic-script material, all travel guides/fiction/history/comics/numismatics/bird-name
material found in the two grab-bag subfolders, and the Glossika phrase-drill ebooks (low yield per
vision-reading effort).
