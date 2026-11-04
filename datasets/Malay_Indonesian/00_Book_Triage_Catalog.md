# Malay, Indonesian — Book Triage Catalog

**Triage complete, 2026-11-03.** First-ever triage for Malay and Indonesian in this project, per
the `TepenianLanguage` handoff (Indonesian is a "second-era" / Tepenian-stage contributing-language
candidate, associated domain idea "agriculture"; Malaysia is a separate, smaller GINI-census nation
not currently flagged by that handoff). **Triage only — no extraction dispatched, nothing written to
`established/`.**

**This is two distinct, closely related standardized languages sharing one folder, not one
language** — the same pattern this project used for Serbian/Croatian/Bosnian
(`datasets/Serbian_Croatian_Bosnian/00_Book_Triage_Catalog.md`). Every file below is tagged
**Malay**, **Indonesian**, **Both** (genuinely covers both varieties), or **Unclear** (neither —
wrong-language contamination), confirmed from the file's own title/copyright page, not inferred
from the filename or collection-folder name.

**Note on a prior draft:** a less-thorough catalog already existed at `datasets/Malay-Indonesian/`
(hyphenated path — distinct from this corrected underscore path, which is the one specified for this
pass) before this triage began, dated today. That draft did not split Malay from Indonesian at all
(the single requirement this handoff emphasizes most), computed no md5 hashes, and — critically — did
not render a single vision-only file, instead inferring every vision-only title's identity from its
filename. Rendering every vision-only file for this pass caught a real error in that inference
approach: `47 Modern Indonesian Literary Reader.pdf` is not English-medium as its filename and the
prior draft both implied — its actual title page reads "Chrestomathie der modernen indonesischen
Literatur" (Rosemarie Simon-Bärwinkel, VEB Verlag Enzyklopädie, Leipzig, 1972) — it is **German-medium**
and belongs in the wrong-metalanguage exclusion group, not the clearly-in-scope pool. This version
also found an in-repo audio companion stash the prior draft's "no `source_reference/languages/`
folder exists for this language" claim missed (see §7), and computed md5 hashes confirming zero
duplicate files anywhere in the harvest.

**Location:** External drive `/media/kuroskalacs/Home-Theater/w-lang/Malay-Indonesian/` (confirmed
mounted) — **60 files, 1.8GB**. Confirmed absent from the two in-repo unsorted stashes (`lang
transfer bay/` has a `Malayalam` folder — an unrelated Dravidian language of India, a false-positive
substring match, not Malay — and no Malay/Indonesian folder; `xx--stash/LibGen Lang/` has no hits
beyond that same false positive). One genuine in-repo item was found and is cataloged separately in
§7: a 31-file audio companion stash under `source_reference/languages/Complete Series
(Books-Audio)/Teach Yourself - Indonesian/`.

**Raw harvest data:** `.triage_raw.tsv` (60 rows: folder, file, size_mb, pages, text_layer, md5,
language_tag). `language_tag` is `Malay`/`Indonesian`/`Both`/`Unclear` for every content file; the
one non-content row (`00 Book List.JPG`) is tagged `N/A` since it isn't language material at all.

**How titles and language tags were identified:** every title was confirmed from its own
title/copyright page — text-layer PDFs and DJVUs via `pdftotext`/`djvutxt`, and **every one of the
28 vision-only PDF/DJVU files individually rendered** (`pdftoppm` for PDFs, `ddjvu`+Pillow for DJVUs)
and read visually, not inferred from filename. **Checked for duplicates by filename and md5 across
all 60 files: zero md5 collisions** — every file is byte-unique, including same-title scan pairs
(`10 Malay for Everyone` PDF vs DJVU; `11 Учебник малайского` PDF vs DJVU) which are confirmed
different scans, not duplicates.

---

## Headline numbers

| | Malay | Indonesian | Both | Unclear | Total |
|---|---|---|---|---|---|
| **Files, by language_tag** (59 content files; excludes the 1 non-content JPG) | **11** | **43** | **4** | **1** | **59** |
| Of which excluded — wrong metalanguage | 2 | 10 | 1 | — | 13 |
| Of which excluded — pure tourism | 4 | 2 | — | — | 6 (1 Russian-medium tourism item double-counted under wrong-metalanguage, not counted twice here) |
| Of which excluded — wrong-language-entirely (Javanese) | — | — | — | 1 | 1 |
| Of which flagged for your ruling (non-English-medium-of-itself) | 0 | 1 | 0 | — | 1 |
| Of which clearly in scope, no ruling needed | 5 | 30 | 3 | — | 38 |
| **Flagship slang/colloquial titles** | **0 (gap)** | **3** | — | — | 3 |

| | |
|---|---|
| Total files harvested | **60** (57 PDF/DJVU + 2 `.doc` + 1 `.JPG`) |
| Text layer present (of 57 PDF/DJVU) | **29 (51%)** |
| Vision-read required (of 57 PDF/DJVU) | **28 (49%)** — all 28 individually rendered and read |
| Duplicate files (by md5) | **none** — all 60 files are byte-unique |
| Packed archives not yet opened | none found |
| Bulk usage-corpus material | none found |
| Frequency dictionary/list found | **none** |
| Audio (not extraction target) | 31 `.m4a` files, in-repo only (not on the external drive) — see §7 |
| Non-content assets | 1 JPG (collector's own folder-listing screenshot) + 1 near-empty `.doc` |
| Wrong-language-entirely contamination | **1 file** — `54 Lehrbuch des modernen Djawanisch.pdf` is a German-medium textbook of **Javanese**, not Malay or Indonesian; a second Javanese *chapter* is also bundled (not a separate file) inside the otherwise in-scope `55 Malay-Indonesian & Javanese` academic chapter — see §3 |

Check: Malay 11 + Indonesian 43 + Both 4 + Unclear 1 = 59 content files + 1 non-content JPG = 60. ✓

---

## 1. EXCLUDE — wrong metalanguage (13 files)

**Russian-medium (7 files)** — confirmed by Cyrillic title text via rendering or `pdftotext`:

| File | language_tag | Confirmation |
|---|---|---|
| `33 Большой индонезийско-русский словарь.pdf` | Indonesian | Rendered cover: "БОЛЬШОЙ ИНДОНЕЗИЙСКО-РУССКИЙ СЛОВАРЬ / KAMUS BESAR BAHASA INDONESIA-RUSIA" — "Big Indonesian-Russian Dictionary," vol. 1 (spine marked "1" / "А-Л") |
| `33 Русско-индонезийский словарь.pdf` | Indonesian | Rendered title page: "KAMUS RUSIA-INDONESIA / РУССКО-ИНДОНЕЗИЙСКИЙ СЛОВАРЬ," ~27,000 words, Moscow, 1972 |
| `39 Бали (Журнал Золотой глобус).djvu` | Indonesian | Rendered cover: "ЗОЛОТОЙ ГЛОБУС / БАЛИ — Остров тысячи храмов" — a Russian DVD-collection travel magazine about Bali, not a language resource at all; also excluded as tourism (§2) |
| `20 Грамматика индонезийского литературного языка.djvu` | Indonesian | Rendered cover: "А. К. Оглоблин — ГРАММАТИКА ИНДОНЕЗИЙСКОГО ЛИТЕРАТУРНОГО ЯЗЫКА" ("Grammar of the Indonesian Literary Language"), St. Petersburg University Press |
| `11 Учебник малайского (малайзийского) языка.djvu` and `.pdf` (×2) | Malay | Rendered cover: "Т.В. Дорофеева, Е.С. Кукушкина — УЧЕБНИК МАЛАЙСКОГО (МАЛАЙЗИЙСКОГО) ЯЗЫКА" ("Textbook of the Malay (Malaysian) Language"), Moscow State University, Institute of Asian and African Studies |
| `28 Разговорник и грамматика индонезийского и малайского языка.doc` | Both | Not opened directly (binary OLE `.doc`, cp1251/Cyrillic codepage confirmed via file metadata; 8,212 words / 46,809 characters — real content, not empty); title itself is Russian: "Phrasebook and Grammar of the Indonesian and Malay Language" |

**German-medium (3 files):**

| File | language_tag | Confirmation |
|---|---|---|
| `26 Kauderwelsch Indonesisch Wort fur Wort.pdf` | Indonesian | `pdftotext`-read: German-medium throughout, same Reise Know-How Kauderwelsch series excluded for the same reason in this project's Scandinavian-language triages |
| `47 Modern Indonesian Literary Reader.pdf` | Indonesian | **Rendered — the one correction to the prior draft, see the note at the top of this catalog.** Actual title: "Chrestomathie der modernen indonesischen Literatur," by Rosemarie Simon-Bärwinkel, VEB Verlag Enzyklopädie, Leipzig, 1972 (East German imprint). The English-sounding filename does not reflect the book's actual medium. |
| `54 Lehrbuch des modernen Djawanisch.pdf` | Unclear | Rendered: "HERRFURTH — LEHRBUCH DES MODERNEN DJAWANISCH." German-medium **and** a different language entirely — "Djawanisch" is Javanese, not Malay or Indonesian. Doubly excluded: wrong metalanguage and wrong target language — see §3. |

**French-medium (3 files):**

| File | language_tag | Confirmation |
|---|---|---|
| `05 Méthode d'indonésien.pdf` | Indonesian | Rendered: "MÉTHODE D'INDONÉSIEN," Pierre Labrousse, Collection Langues-INALCO, L'Asiathèque, 1997 |
| `21 Introduction à l'indonésien.pdf` | Indonesian | Rendered: "INTRODUCTION A L'INDONESIEN," Denys Lombard, 3rd revised edition, Archipel, 1991 |
| `22 Parlons indonésien Langues et culture d'Indonésie.pdf` | Indonesian | Rendered: "PARLONS INDONESIEN," L'Harmattan, 1997 — same "Parlons" series pattern already excluded in this project's other triages |

---

## 2. EXCLUDE — out of scope, pure tourism (6 files, 1 overlapping with §1)

| File | language_tag | Confirmation |
|---|---|---|
| `36 Bali & Lombok (DK Eyewitness Travel Guides).pdf` | Indonesian | Rendered: standard DK Eyewitness Travel series, same standing exclusion as every other language's DK Eyewitness titles in this project |
| `37 Frommer's Bali & Lombok.pdf` | Indonesian | `pdftotext`-confirmed: standard Frommer's commercial travel guide |
| `44 Malaysia and Singapore (DK Eyewitness Travel Guides).pdf` | Malay | `pdftotext`-confirmed: "EYEWITNESS TRAVEL MALAYSIA & SINGAPORE" |
| `45 Frommer's Singapore & Malaysia.pdf` | Malay | `pdftotext`-confirmed: standard Frommer's commercial travel guide |
| `39 Бали (Журнал Золотой глобус).djvu` | Indonesian | Also listed in §1 — a Russian DVD-collection travel magazine, excluded on both grounds |

Per the collector's own Book List screenshot (§7), three further Lonely Planet tourism titles
(`38 Lonely Planet Bali & Lombok`, `40 Lonely Planet Indonesia`, `46 Lonely Planet Malaysia,
Singapore & Brunei`) were in the original collection but **did not make it onto this drive** — not
counted here since they aren't present to triage.

---

## 3. Wrong-language-entirely contamination (1 file + 1 bundled chapter)

Per the standing instruction to check for other Southeast Asian languages accidentally bundled into
a "Malay-Indonesian" folder (the pattern this project's Norwegian/Faroese triage caught):

- **`54 Lehrbuch des modernen Djawanisch.pdf`** (132p, vision) — confirmed by rendering: this is a
  German-medium textbook of **Javanese** ("Djawanisch"), a related but distinct Austronesian language
  of central/eastern Java, not Malay or Indonesian. Tagged `Unclear` in the TSV. Excluded on two
  independent grounds (wrong metalanguage and wrong target language).
- **`55 Malay-Indonesian & Javanese (The World's Major Languages).pdf`** (42p, TEXT, tagged `Both`) —
  this single PDF bundles **two separate academic chapters** from the same reference volume: a
  Malay-Indonesian chapter (Uri Tadmor, confirmed via `pdftotext` as the opening content, roughly the
  first half) and a **second, separate Javanese chapter** starting partway through (confirmed via
  `pdftotext` — a "Javanese" section header appears partway through the extracted text, with its own
  introduction, "Javanese is one of the Austronesian languages..."). **Only the Malay-Indonesian
  chapter is in scope for this project; the bundled Javanese chapter should not be dispatched
  alongside it** if this file is ever pulled into extraction — same "don't dispatch the whole file
  when only part is on-topic" caution as prior languages' multi-section sources (e.g. Danish's
  folklore epub).

No other wrong-language contamination was found — every other file confirmed Malay- or
Indonesian-subject-matter is genuinely about one or both of those languages.

---

## 4. Non-content assets and audio companions (2 files on the drive; audio found in-repo, see §7)

- **`00 Book List.JPG`** — **read directly**: a screenshot of the original collector's own folder
  listing (filenames with file-type icons). Confirms the drive's numbering scheme and reveals several
  items from the collector's original inventory that did **not** make it onto this drive: 8 audio
  companions (`01 TY Indonesian Audio`, `02 Colloquial Indonesian Audio`, `03 Basic Indonesian
  Audio`, `04 Linguaphone Audio`, `08 TY Malay Audio`, `09 Colloquial Malay Audio`, `11 Учебник
  малайского Audio`, and 4 CDs for `50 Listening Comprehension...`), plus 4 numbered titles never
  copied over at all: `38 Lonely Planet Bali & Lombok`, `40 Lonely Planet Indonesia`, `46 Lonely
  Planet Malaysia, Singapore & Brunei`, `53 Indonesian School Textbooks`. Same "most audio companions
  weren't copied over" pattern seen in other languages' Book List screenshots in this project.
- **`06 Indonesian Compact Booklet.doc`** — checked via file metadata: 1 page, 1 word, 7 characters.
  Effectively empty, same pattern as other languages' identically-named placeholder files in this
  project. Tagged Indonesian by title, but not extractable as-is.

---

## 5. FLAGGED FOR YOUR RULING — non-English-medium-of-itself (1 file)

Same recurring open question this project has hit for nearly every language triaged so far: a
non-English-medium reference work of the language itself is never silently excluded or silently kept
— it's flagged here instead. **Not excluded, not kept — a decision is needed.**

- **`34 Kamus Bahasa Indonesia.pdf`** (1,844 pages, TEXT, language_tag `Indonesian`) — `pdftotext`-
  confirmed: a genuine, substantial **monolingual Indonesian dictionary** (Indonesian words defined
  in Indonesian), produced by the editorial team of Indonesia's national language body (credited
  editors: Dendy Sugono as Pemimpin Redaksi, with a full editorial team — this reads as the official
  *Kamus Besar Bahasa Indonesia*-style reference, redistributed here under a "UZ-TRANSLATIONS"
  digitization credit). At 1,844 pages this is both the single largest file in the entire harvest and
  very likely the most authoritative dictionary present — comparable in scale to Korean's and
  Spanish's oversized dictionaries, which needed this project's representative-sampling convention.
  **No Malay-medium-of-Malay title was found anywhere in this harvest** — this is the only file in
  the flagged-ruling category.

---

## 6. What's clearly in scope — category overview (38 files, no ruling needed)

### 6a. Malay (5 files)

**Flagship slang/colloquial-register candidates: none found.** This is a real gap — unlike
Indonesian (§6b), no dedicated Malay idiom/slang/informal-register title exists anywhere in this
60-file harvest. Flag this explicitly if the Tepenian handoff cares about Malay-specific colloquial
coverage.

**Courses:**
- `08 Teach Yourself Malay.pdf` (155p, vision) — rendered and confirmed: standard Routledge Teach
  Yourself series.
- `09 Colloquial Malay.pdf` (154p, vision) — rendered and confirmed: "Colloquial Malay — A Complete
  Language Course," Zaharah Othman and Sutanto Atmosumarto, Routledge.
- `10 Malay for Everyone.pdf` + `.djvu` (328p / 325p, both vision, **not** byte-identical — md5-
  checked, different scans of the same title by Othman Sulaiman, Pelanduk Publications; verify both
  before picking a dispatch source).

**Reading/writing skills:**
- `12 Write Malay.pdf` (196p, vision) — rendered and confirmed: "Write Malay — An Introduction to the
  Modern Written Language for English-speaking Malaysians," Edward S King, Times Books International.

### 6b. Indonesian (30 files)

**Flagship slang/colloquial-register candidates (3 — the strongest flagship group of any language
in this harvest):**
- **`30 Informal Indonesian.pdf`** — rendered and confirmed: "A comprehensive dictionary of Informal
  Indonesian including current slang and dialect expressions," Australian College of English. The
  clearest flagship slang title in this entire stash.
- **`29 Indonesian Idioms and Expressions.pdf`** — rendered and confirmed: "Colloquial Indonesian at
  Work," Christopher Torchia.
- **`25 Colloquial Jakartan Indonesian.pdf`** — Routledge Colloquial series, specifically the Jakarta
  urban-vernacular register rather than standard Indonesian.

**Reference grammars (English-medium, confirmed):**
`18 Indonesian: A Comprehensive Grammar.pdf`, `19 Indonesian Reference Grammar.pdf`, `17
Understanding Indonesian Grammar.pdf` (all three by James Neil Sneddon — three distinct, non-
duplicate titles, same "don't assume near-identical titles are the same book" caution as other
languages in this project), `23 The Indonesian Language — Its History and Role in Modern Society.pdf`
(also Sneddon).

**Large dictionaries (English-medium, will need representative sampling given size):**
`31 The Learner's Dictionary of Today's Indonesian.pdf` (1,175p), `32 A Comprehensive Indonesian-
English Dictionary.pdf` (1,125p).

**Courses:** `01 Teach Yourself Complete Indonesian.pdf` (210p, TEXT) and `01 Teach Yourself
Indonesian.pdf` (308p, vision) — **two genuinely different editions, not duplicates** (different page
counts, different md5); `02 Colloquial Indonesian.pdf`, `03 Basic Indonesian: An Introductory
Coursebook.pdf`, `04 Linguaphone Indonesian Course.pdf`, `07 Indonesian Basic Course.pdf` (Defense
Language Institute), `13 Bagus Sekali! 3 Textbook.pdf`, `14 Keren! 3 & 4 Indonesian Course Book.pdf`,
`27 Introducing Indonesian.pdf`.

**Academic/sociolinguistic reference (English-medium):**
`41 Historical Dictionary of Indonesia.pdf`, `42 A History of Modern Indonesia.pdf` (M.C. Ricklefs),
`24 Indonesia (Language and National Identity in Asia).pdf`, `35 Indonesian Bahasa
Familiarization.pdf` (DLI country profile).

**Readers/usage-adjacent material (English-medium, authentic-text pedagogy):**
`51 Nah Baca 1` and `Nah Baca 2` (Reading Packet + Workbooks, "Authentic Indonesian Readings" series,
University of Hawai'i — 3 files), `49 Indonesian Newspaper Reader.pdf` (rendered: Foreign Service
Institute, 1968, 250 reading selections), `15 Vocabulary Building in Indonesian: An Advanced
Reader.pdf` (rendered: Soenjono Dardjowidjojo, Ohio University Monographs in International Studies).

**Culture/literature (English-medium):**
`48 Contemporary Indonesian Poetry.pdf` (Harry Aveling translation/anthology), `43 Cooking The
Indonesian Way.pdf` (rendered to confirm title — this file's embedded text layer is a **font-cipher
garble**, same gotcha previously found in this project's CJK-script books; confirmed English-medium
only by rendering the cover and later pages, not by `pdftotext`), `52 Marty J. Reep — Winston T.
Tikus.pdf` (a bilingual English/Indonesian children's book — genuine parallel-text material).

### 6c. Both — genuinely covers Malay and Indonesian together (3 files)

- **`16 A Student's Grammar of Malay and Indonesian.pdf`** (218p, vision) — rendered and confirmed:
  Malcolm W. Mintz, EPB Publishers. A single comparative grammar, not two bundled books.
- **`50 Listening Comprehension Selections from Malaysian and Indonesian History.pdf`** (137p,
  vision) — rendered and confirmed: Malcolm W. Mintz, EPB Publishers — companion/follow-on title
  explicitly cross-referenced inside `08 Teach Yourself Malay.pdf`'s own back matter.
- **`55 Malay-Indonesian & Javanese (The World's Major Languages).pdf`** (42p, TEXT) — the Malay-
  Indonesian chapter only (Uri Tadmor); its bundled Javanese chapter is out of scope — see §3.

---

## 7. The in-repo audio companion stash (not previously documented for this language)

`source_reference/languages/Complete Series (Books-Audio)/Teach Yourself - Indonesian/` — **31
`.m4a` files** (CD 1: 17 tracks, CD 2: 14 tracks), the audio companion to the Teach Yourself
Indonesian course (most likely `01 Teach Yourself Indonesian.pdf` given the numbered-unit track
titles like "1-15 Ind_ 8 Asking The Way," which align with that edition's chapter structure). Counted
only, per this project's standing audio convention — not an extraction target. This stash was missed
by the prior draft's claim that "no `source_reference/languages/` folder exists for this language on
the SSD" — that claim was true for text content but missed this audio-only folder.

---

## 8. Priority tiers

### 8a. Malay (5 in-scope files)

**Tier 1 — reference grammars & academic linguistics:** none Malay-only (the comparative `16 A
Student's Grammar of Malay and Indonesian` is tiered under §8c instead). `24 Malaysia and Brunei
(Language and National Identity in Asia).pdf` and `24 Singapore (Language and National Identity in
Asia).pdf` (both excluded from the 59-content-file in-scope count above because they're thin,
20-25-page academic chapters rather than standalone Malay resources, but both English-medium and
on-topic) would sit here if pulled in — note the Singapore chapter's connection to Malay specifically
is weaker/more indirect than the Malaysia/Brunei chapter's, since Singapore's chapter surveys a
multilingual national-identity policy (English/Mandarin/Malay/Tamil), not Malay specifically.

**Tier 2 — vocab/dictionary/idiom/slang:** **none** — the thinnest Tier 2 of any language triaged in
this project so far for either variety. No Malay-specific dictionary or slang/idiom title exists
anywhere in this 60-file harvest (the only dictionaries present are Indonesian-only or Russian-
medium exclusions).

**Tier 3 — verbs & reading/writing skills:** `12 Write Malay` — the only Malay-specific
reading/writing-skills title.

**Tier 4 — course series (lowest priority, highest cost):** `08 Teach Yourself Malay`, `09 Colloquial
Malay`, `10 Malay for Everyone` (pick one scan as primary).

**Tier 5 — graded readers:** **none found** — no Malay-specific graded reader or native-literature
title exists in this harvest.

### 8b. Indonesian (30 in-scope files)

**Tier 1 — reference grammars & academic linguistics:** `18 Indonesian: A Comprehensive Grammar`,
`19 Indonesian Reference Grammar`, `17 Understanding Indonesian Grammar` (all Sneddon — treat as a
coherent three-volume set from one author, not independent dispatches), `23 The Indonesian Language`,
`41 Historical Dictionary of Indonesia`, `42 A History of Modern Indonesia`, `35 Indonesian Bahasa
Familiarization` (cheap country-profile primer), `24 Indonesia (Language and National Identity in
Asia)`. If the §5 ruling favors inclusion, `34 Kamus Bahasa Indonesia` would be the largest and most
authoritative addition to this tier (needs representative sampling given its 1,844 pages).

**Tier 2 — vocab/dictionary/idiom/slang (flagship category):** `30 Informal Indonesian` (clearest
flagship), `29 Indonesian Idioms and Expressions`, `25 Colloquial Jakartan Indonesian`, `31 The
Learner's Dictionary of Today's Indonesian`, `32 A Comprehensive Indonesian-English Dictionary` (both
oversized dictionaries need representative sampling).

**Tier 3 — verbs & reading/writing skills:** `15 Vocabulary Building in Indonesian: An Advanced
Reader`. No standalone verb-conjugation reference was found outside the Tier 1 grammars.

**Tier 4 — course series (lowest priority, highest cost):** `01 Teach Yourself Complete Indonesian`
and `01 Teach Yourself Indonesian` (two editions, dispatch one as primary), `02 Colloquial
Indonesian`, `03 Basic Indonesian: An Introductory Coursebook`, `04 Linguaphone Indonesian Course`,
`07 Indonesian Basic Course`, `13 Bagus Sekali! 3`, `14 Keren! 3 & 4`, `27 Introducing Indonesian`.

**Tier 5 — graded readers / native-literature-adjacent:** `51 Nah Baca 1` + `Nah Baca 2` (Reading
Packet + Workbooks), `49 Indonesian Newspaper Reader`, `48 Contemporary Indonesian Poetry`, `52
Marty J. Reep — Winston T. Tikus` (bilingual children's reader), `43 Cooking The Indonesian Way`
(culture-adjacent, lowest priority of this tier given the font-cipher text layer and recipe-genre
content).

### 8c. Both (3 in-scope files)

**Tier 1:** `16 A Student's Grammar of Malay and Indonesian`, `55 Malay-Indonesian & Javanese`
(Malay-Indonesian chapter only — see §3 for the bundled Javanese chapter to exclude from dispatch).

**Tier 3:** `50 Listening Comprehension Selections from Malaysian and Indonesian History`.

No Both-tagged Tier 2, 4, or 5 material exists — every dictionary, slang title, course, and graded
reader in this harvest commits to one variety or the other, not both at once.

---

## 9. Extraction notes

- **28 of 57 PDF/DJVU files needed vision reading (49%), and all 28 were individually rendered and
  read for this pass** — a moderate vision-dependency ratio, in the same range as this project's
  Dutch and German triages.
- **The §5 ruling covers exactly 1 file** (`34 Kamus Bahasa Indonesia`, 1,844p) — proportionally the
  smallest ruling group of any language triaged in this project so far, but the single file involved
  is unusually large.
- **No Malay-specific slang/idiom/dictionary title exists at all** (§8a Tier 2 is empty) — this is a
  real, flaggable gap if Malay-specific colloquial coverage matters to the Tepenian handoff,
  especially set against Indonesian's comparatively strong 3-title flagship slang group (§6b).
- **`47 Modern Indonesian Literary Reader.pdf` is German-medium, not English-medium** — this is the
  one correction to the prior draft at `datasets/Malay-Indonesian/` (hyphenated path); it belongs in
  §1 (wrong metalanguage), not the in-scope pool. Anyone who already saw that draft should note this
  change.
- **`54 Lehrbuch des modernen Djawanisch.pdf` is Javanese, not Malay or Indonesian** — correctly
  excluded by the prior draft too, but worth restating: this is wrong-language contamination, not
  just a metalanguage issue.
- **`55 Malay-Indonesian & Javanese` bundles an in-scope Malay-Indonesian chapter with an out-of-
  scope Javanese chapter in the same 42-page file** — dispatch only the first (Tadmor) chapter if
  this file is ever extracted.
- **No md5 duplicates anywhere in the 60-file harvest.** Two same-title scan pairs (`10 Malay for
  Everyone` and `11 Учебник малайского`, each PDF+DJVU) are confirmed different scans, not duplicate
  files — spot-check both before committing to one as the dispatch source.
- **No frequency dictionary or frequency list was found** anywhere in this harvest for either
  language.
- **31 in-repo audio `.m4a` files exist as a Teach Yourself Indonesian companion** (§7) — not
  previously documented for this language pair, not an extraction target.
- Scratch render files used for this triage (title/copyright-page renders for all 28 vision-only
  files, the inventory TSV, and the font-cipher spot-check on `43 Cooking The Indonesian Way`) have
  been deleted per the project's disk-space instruction; nothing was written to the external drive.
