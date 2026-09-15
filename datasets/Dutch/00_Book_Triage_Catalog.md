# Dutch — Reference Material Triage Catalog

**Status: full triage complete, 2026-09-14 — supersedes the earlier partial test-run triage.** The
original Dutch test run (see `../../methodology-observations/dutch_test_run.md`) only spot-checked
"top candidates" out of 84 files and extracted 3 chapters from one book. This is the first
exhaustive triage of the full corpus, matching the methodology used for every other completed
language.

**Folder note:** the source folder is `source_reference/languages/Dutch/` (2.1GB, 84 real files +
`to_download.txt` + 2 incomplete `.rar.part` downloads). This project's `datasets/`/`language_corpus/`
folders use the simpler `Dutch` name regardless of any longer name the source pack itself used
historically.

**Already extracted (test-run, kept as-is):** `established/001-003` cover Chapters 1-3, 16, and 22
of `25 Dutch An Essential Grammar.pdf` — do not re-extract these chapters.

---

## Scope filtering — excluded entirely

- **Non-English-metalanguage courses**: `30 Tata Bahasa Belanda Praktis.pdf` (Indonesian-medium —
  "Tata Bahasa" is Indonesian for "grammar"), `37 Kauderwelsch Niederländisch Wort für Wort.PDF`
  (German-medium — Kauderwelsch is a German-language phrasebook series).
- **Non-English bilingual dictionary**: `34 Kosmos mini woordenboek Nederlands-Zweeds.pdf`
  (Dutch-Swedish — no English side). The Dutch-English companion (`34 ...-Engels.pdf`) stays in
  scope.
- **Incomplete/corrupted downloads**: `35 The Rough Guide Phrasebook Dutch Audio.rar.part`,
  `36 In-Flight Dutch Learn Before You Land!.rar.part` — both are partial `.rar` archive fragments,
  not usable files.
- **Travel guides**: `40-48` (9 files) — Rough Guide, DK Eyewitness, and Frommer's guides to the
  Netherlands, Amsterdam, and Belgium/Luxembourg.
- **History/culture volumes**: `38 A Key to Dutch History`, `39 The UnDutchables` (a
  cultural-commentary book on Dutch national character, closer to Hungarian's contact-outside
  sociolinguistic-commentary volume than a language reference — deferred, not excluded outright,
  see Group C).
- **Duplicate formats of the same book**: `31 A Dutch Vocabulary.djvu` (PDF version has a real text
  layer, DJVU does not — use the PDF); `49 Reading Dutch...djvu` (neither format has a text layer;
  use the PDF for vision-reading, ignore the DJVU duplicate).

## In-scope material — grouped by text-layer status

### Group A — Clean text layer (Wave 1)

| File | Pages | Notes |
|---|---|---|
| `01 Teach Yourself Dutch Conversation.pdf` | 48 | Short conversational course |
| `02 Dutch for Dummies.pdf` | 395 | Large standard course |
| `04 Dutch Foundation Course.pdf` | 17 | Very short — likely a placement/intro booklet |
| `12 Routledge Intensive Dutch Course.pdf` | 434 | Large intensive course, same publisher family as `25`/`27` |
| `13 Levend Nederlands Een Cursus Nederlands voor Buitenlanders.pdf` | 243 | Dutch-medium course for foreigners |
| `19 Dutch Advanced Course.pdf` | 32 | Short, advanced-level — likely register-rich for its size |
| `22 Basic Dutch A Grammar and Workbook.pdf` | 206 | Routledge "Grammar and Workbook" series, clean (confirmed in original triage pass) |
| `23 Intermediate Dutch A Grammar and Workbook.pdf` | 213 | Sequel to `22`, same series |
| `27 Dutch A Comprehensive Grammar.pdf` | 454 | Companion to `25` (already partially extracted), same publisher family — same extraction quirk expected (stray digit-prefix noise, cosmetic only) |
| `28 Beter Nederlands Grammatical hulpboek voor anderstalingen.pdf` | 199 | Dutch-medium grammar reference for non-native speakers |
| `31 A Dutch Vocabulary.pdf` | 95 | Vocabulary reference |
| `34 Kosmos mini woordenboek Nederlands-Engels.pdf` | 366 | Dutch-English mini dictionary |
| `84 The Phonetics of English and Dutch.pdf` | 373 | Comparative phonetics — typology-grounding value, parallel to Hungarian's morphology paper |

**Extraction quirk (confirmed in the original test-run triage, applies to `25` and likely `27`,
same publisher):** `pdftotext` prepends stray page-margin ruler digits to each page — cosmetic
noise, not corruption. Instruct subagents to ignore it.

### Group B — No text layer at all (Wave 2, vision-reading)

| File | Pages | Notes |
|---|---|---|
| `03 Teach Yourself Beginner's Dutch.pdf` | 96 | Standard beginner course |
| `05 Dutch in 3 Months.pdf` | 131 | Standard course |
| `06 Speak Dutch Today.pdf` | 37 | Short course |
| `08 Learn Dutch!.pdf` | 97 | Standard course |
| `09 Teach Yourself Dutch.pdf` | 154 | Standard course (companion to the already-extracted `25`'s series style) |
| `10 Colloquial Dutch.pdf` | 162 | **High priority — "Colloquial" framing signals register content**, same pattern that worked for SCB's Colloquial titles |
| `15 Linguaphone - Cursus Nederlands.pdf` | 183 | Standard course |
| `17 Colloquial Dutch 2.pdf` | 218 | **High priority**, sequel to `10` |
| `18 Hugo advanced Dutch (Taking Dutch Further).pdf` | 104 | Advanced-level — likely register-rich |
| `24 Teach Yourself Dutch Grammar.pdf` | 129 | Grammar-focused companion to `09` |
| `26 Dutch Reference Grammar.pdf` | 137 | Deferred behind `25`/`27` in the original triage — now worth a look since those are confirmed extracted/queued |
| `32 Beyond the Dictionary in Dutch A Guide to Correct Word Usage.pdf` | 195 | Usage/near-synonym guide — directly register-relevant, parallel to Russian's near-synonym discrimination guides |
| `49 Reading Dutch Fifteen annotated stories from the Low Countries.pdf` | 90 | **A genuine language-learner reader with its own annotations** (not raw fiction) — in scope, register-relevant |
| `83 The Phonology of Dutch.pdf` | 216 | Academic phonology reference — typology-grounding |
| `16 Goed zo!.djvu` | — | Course book (djvu) |
| `29 Klare Taal Uitgebreide Basisgrammatica NT2.djvu` | — | "Clear Language: Extended Basic Grammar NT2" — Dutch-as-second-language grammar reference |

### Group C — Deferred (real value, lower priority given corpus scale)

- `39 The UnDutchables` — cultural-commentary book, possible parallel to Hungarian's sociolinguistic
  contact-outside volume; revisit if Wave 1/2 leave budget.
- `50 Anne Frank - Het Achterhuis.pdf` — a genuine literary/historical primary source, not a
  language course; likely too large and narrative-heavy to prioritize over course material.
- `56-82` (27 files) — Dutch translations of classic fairy tales (Assepoester/Cinderella,
  Sneeuwwitje/Snow White, Roodkapje/Little Red Riding Hood, etc.). Per the Russian Сказочник
  precedent, treat as a **representative-sampling candidate** (2-3 volumes), not exhaustive
  coverage, if pursued at all — these are unannotated fiction, lower yield per page than the
  language-course material above.
- `07 Dutch I Reading Booklet.pdf` + `07 Guide.pdf`, `11 De Delftse Methode...` (+ Workbook),
  `14/20/21 Code 1/2/3 Takenboek.pdf` — additional course/workbook material not yet triaged in
  detail; likely real value but deferred behind the higher-confidence Group A/B list above.

## Recommended Phase 1 extraction priority order

**Wave 1 — clean text (13 sources):** prioritize `27` (companion to the already-started `25`) and
`22`/`23` (clean Routledge series); `84` for typology grounding.

**Wave 2 — vision-reading (16 sources):** prioritize `10`/`17` (Colloquial Dutch 1 & 2, the
register flagship candidates) and `32` (usage/near-synonym guide) first.

**Wave 3 (optional, time-permitting):** Group C — the deferred workbook/reading-booklet cluster,
and a representative 2-3-volume sample of the fairy-tale series.

## Morphological typology (preliminary, per Phase 0 convention)

**Dutch: fusional/mildly analytic**, West Germanic — a two-way common/neuter gender article system
(de/het), a productive and highly regular diminutive suffix system (-je/-tje/-etje, already
identified as worth documenting in the original test-run's Chapter 22 extraction), separable-verb
constructions (a Germanic feature shared with German), and V2 word order. Register expressed
through jij/u (informal/formal second person, closer to French tu/vous than Korean's grammaticalized
system) plus lexical choice. Will be refined further once Wave 1 grammar extraction lands at scale.
