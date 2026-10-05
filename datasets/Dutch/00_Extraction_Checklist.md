# Dutch Slang Mechanics — Extraction Checklist

**Phase 1 (reference extraction) complete as of 2026-10-04.** Sixth language in the project to
reach this milestone, after Serbian/Croatian/Bosnian, Hungarian, Korean, Russian, and Spanish. 167
`established/` files, ~813,000 words, from all 29 in-scope sources identified in
`00_Book_Triage_Catalog.md` (13 Wave 1 clean-text + 16 Wave 2 vision-read). See
`../../methodology-observations/dutch_test_run.md` for the full process log, including two
session-limit interruptions during Wave 2 that were fully recovered via disk-state-verification and
targeted continuation dispatches rather than re-extraction. (`Dutch` is its own folder-safe name —
no display-name-vs-path-name split needed here.)

**Purpose:** analyze the actual mechanics of how Dutch slang forms and works, using the
corpus collected in `language_corpus/Dutch/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Dutch/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

---

## Morphological typology

*(Fill in during Phase 0 triage, before extraction begins — see
`../00_Word_Concept_and_Morphological_Typology_Guide.md`. What is this language's approach to the
concept of a "word"? Isolating / agglutinative / fusional / polysynthetic / a mix — with one or two
concrete examples if available. This affects how `established/` vocabulary entries should be
recorded and how `morphological_play` should be interpreted in `analysis/`.)*

**Dutch: predominantly analytic/mildly fusional, West Germanic — closer to English than to
Hungarian or Serbian/Croatian/Bosnian, but not as radically analytic as English.** Case marking has
almost entirely collapsed except in pronouns (subject `ik`/object `mij`); nouns retain a two-way
grammatical gender system (`de`-words / `het`-words) that conditions adjective inflection (the `-e`
ending) and article choice, but this is a comparatively light fusional residue, not a rich case
system. Verb conjugation is moderate (weak vs. strong verbs, similar in kind to English's
regular/irregular split but more systematically marked). **The one genuinely productive
derivational-morphology feature worth flagging separately: the diminutive suffix system**
(`-je`/`-tje`/`-pje`/`-kje`/`-etje`, phonologically conditioned by the stem's final sound,
e.g. `tafel` → `tafeltje` "little table") — a real, live suffixation process layered onto an
otherwise mostly-analytic language, and specifically chosen as one of this test run's three
extraction chunks (Chapter 22) because it's exactly the kind of "mixed strategy" case
`../00_Word_Concept_and_Morphological_Typology_Guide.md` describes as more common than a pure
single-category language. See `established/003_chapter22_diminutives.md` for real
worked examples.

---

## Output files — Markdown, sharded by numbered file, not JSON

**Storage model.** All extracted content — raw reference data, mechanics analysis, synthesized
results — lives as **Markdown** (occasionally `.txt`), not hand-authored JSON. This matches how the
rest of this project's own methodology documentation works, and lets `/graphify` serve as the
organized-summary/pointer layer instead of a manually-maintained manifest (see Graphify section
below).

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Dutch baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

Copy `_TEMPLATE/established/001_TEMPLATE.md`, `_TEMPLATE/analysis/001_TEMPLATE.md`,
`_TEMPLATE/synthesized/001_TEMPLATE.md` as starting points. **Don't let a single file grow
unbounded** — split into a new numbered file once one gets unwieldy to read/diff, same discipline
used in `language_corpus/`. **No `_index.json` manifest to maintain** — this checklist's own
`## Output files` table (below) is the human-readable index; `/graphify` (see below) is the
machine-queryable one.

Fill this table in as files are created:

| File | Contents |
|---|---|
| `established/001_chapters1-3_pronunciation_spelling_plural.md` | Chapters 1-3 (Pronunciation, Spelling, The Plural), pp. 6-27 — full vowel/consonant/diphthong inventory with regional-pronunciation notes, assimilation rules, stress placement, closed/open-syllable spelling logic, f/v & s/z alternation, all three plural strategies (`-en` incl. irregular vowel-lengthening and meaning-differentiated `-eren` doublets, `-s`, Latin/`-or`/`-heid` plurals) — ~190 distinct glossed vocabulary items, all `core` register except `engerd` "creep" (tagged `colloquial` on lexical-meaning grounds) |
| `established/002_chapter16_colloquial_speech.md` | Chapter 16 "Colloquial speech and writing" (pp.125–134): discourse particles (*eens, even, maar, toch, wel, hoor*), particle combinations, secondary discourse adverbs (*al, dan, dus, nou, nu, ook, soms, zeker*), particle placement/combination rules, and the §16.3 written-vs-spoken register lexical/syntax pairs (formal *echter/aangezien/ofschoon/opdat/dienen/desalniettemin/de mijne/wie* vs. colloquial/neutral spoken counterparts). Confirms Usage Tier diversity beyond `core` — see the file's own "Usage Tier findings" section. |
| `established/003_chapter22_diminutives.md` | Chapter 22 "Diminutives" (pp. 181–186 / PDF pp. 196–201) — all four diminutive-suffix allomorphs (`-je`/`-tje`/`-etje`/`-pje`) and their phonological conditioning, the vowel-length-alternation, t-drop-in-pronunciation, and vowel-doubling sub-rules, the diminutive-as-adverb construction (source-marked `colloquial`), the "personalizing suffix" pragmatic/attitude use (tagged `colloquial`), semantic-drift lexicalizations, and diminutive-only lexemes — ~65 vocabulary rows, each with a full morpheme breakdown per `00_Word_Concept_and_Morphological_Typology_Guide.md`. |

**Wave 1/2 sources (004–033k, 164 files) — summarized by source book rather than itemized per file,
given the scale. Full detail lives in each file's own header/coverage note.**

| Files | Source | Contents |
|---|---|---|
| `004` | Teach Yourself Dutch Conversation | Phrasebook dialogues + merged bilingual glossary, ~230 rows |
| `005`–`005b` | Dutch for Dummies | Core course chapters 1-5 |
| `006` | Dutch Foundation Course | Michel Thomas–style track-by-track course, ~180 rows |
| `007`–`007p` (16 files) | Routledge Intensive Dutch Course | All 11 units + appendices + full end-of-book glossary (~2,950 rows) — turned out to be an 11-unit book, not 8-9 as originally estimated; surfaced real slang/taboo content (*oprotten*, *poen*, *yups*) and explicit Flemish/Netherlands regional splits |
| `008`–`008b` | Levend Nederlands | Dutch-medium course for foreigners |
| `009` | Dutch Advanced Course | Michel Thomas–style advanced track listing |
| `010` | Basic Dutch: A Grammar and Workbook | |
| `011` | Intermediate Dutch: A Grammar and Workbook | |
| `012`–`013b` | Dutch: A Comprehensive Grammar (Donaldson) | Full book, Ch.1-13, companion to `25` |
| `014` | Beter Nederlands | Dutch-medium grammar aid |
| `015` | A Dutch Vocabulary | |
| `016` | Kosmos mini woordenboek (Nederlands-Engels) | Representative dictionary sample, 96 rows; no register annotation in source |
| `017`–`017c` | The Phonetics of English and Dutch | Comparative phonetics reference |
| `018` | Teach Yourself Beginner's Dutch | Full book, vision-read |
| `019` | Dutch in 3 Months | Non-redundant-supplement pass; reading practice + strong-verb appendix + curated mini-dictionary |
| `020` | Speak Dutch Today | Full book; stages the u→jij register-switch pragmatic trigger, not just the paradigm |
| `021` | Learn Dutch! | Curated pass; `'t kofschip` mnemonic, strong-verb ablaut subclasses |
| `022`–`022m` (13 files) | Teach Yourself Dutch | Full book, all 16 units + irregular-verb appendix + curated glossary |
| `023`–`023r` (18 files) | Colloquial Dutch (Donaldson) | Full book, all 17 lessons + irregular-verb list + both glossaries |
| `024`–`024d` | Linguaphone Cursus Nederlands | Woordenlijst lessons 1-33 + scope-checked extraction from the dialogue/exercise booklets (found real content: quotations/proverbs collection, 16 grammar points visible only in the drill structure) — Woordenlijst lessons 34-50 + phonology appendix + closing dictionaries remain unextracted, flagged for a future pass |
| `025`–`025m` (13 files) | Colloquial Dutch 2 | Full book, all 12 units + grammar summary. **Flagship slang/register source**: explicit youth-slang list (Unit 5: vet/cool/strak/wreed vs. cono/bout/gaar) and a four-tier toilet-terminology formality ladder from a newspaper article (Unit 12) |
| `026`–`026k` (11 files) | Hugo Advanced Dutch (Taking Dutch Further) | Full book, all 10 lessons (TOC-undercounting caught — book has 10 lessons, not 7 as initially estimated) |
| `027`–`027i` (9 files) | Teach Yourself Dutch Grammar | Full book, all 100 numbered units + abbreviations + irregular verbs |
| `028` | Dutch Reference Grammar (Donaldson, 1981) | Non-redundant-supplement pass against `010`-`013b`; colloquial money-slang (*piek/ton/mille*), Belgium's surviving masc/fem pronoun split |
| `029`–`029za` (27 files) | Beyond the Dictionary in Dutch | Full book, entire alphabetical usage/near-synonym guide, A through "the youth" |
| `030` | Reading Dutch: Fifteen annotated stories | Annotated-reader glosses |
| `031`–`031h` (8 files) | The Phonology of Dutch (Booij) | Full book, Ch.1-9 — first systematic Dutch pronoun/clitic paradigm and spelling-correspondence tables in this corpus |
| `032`–`032j` (10 files) | Goed zo! (Dutch-via-Russian course) | Full book except printed pp.155-174 ("Les 9"), confirmed physically missing from the source DJVU scan itself |
| `033`–`033k` (11 files) | Klare Taal! Uitgebreide basisgrammatica NT2 | Full book, all 78 lessons (Deel 1-2) + Deel 3 + appendices |

---

## Field/column conventions

**Usage-tier / slang-type categorization.** `established/` vocabulary tables carry a `Usage Tier`
column (e.g. `core`, `technical`, `taboo`, `slang`, ...) — see `../00_Usage_Tier_Taxonomy.md` for
the shared vocabulary, kept consistent across languages so findings are comparable. `analysis/` and
`synthesized/` entries carry `Slang Type` and `Derived From Tiers` tags, capturing which
standard-language tier(s) a given slang-formation mechanism actually draws from. **Every tier/type
is extensible with dot-notation subcategories** (`technical.medical`) — use them freely as real
data surfaces distinctions worth keeping, and promote a subcategory into the shared taxonomy doc
once it recurs across 2+ languages.

**Transcription risk carries through.** Any `analysis/` example drawn from a corpus entry that was
itself sourced from a subtitle/transcript keeps that entry's `Source Type` and `Transcription
Confidence` — see
[`../../language_corpus/00_Source_Reliability_Guide.md`](../../language_corpus/00_Source_Reliability_Guide.md).
Don't build a mechanism finding on a `low_confidence` example without saying so.

**Vision-reading risk carries through the same way.** `established/` entries extracted from a
scanned (no-text-layer) source carry a `Vision Reading Confidence` column (`n/a` if the source had a
real text layer; otherwise `verified`/`plausible_unverified`/`low_confidence`) — see
`../00_Reference_Extraction_Spec.md`. **Any vision-read source must also be checked for handwritten
marginalia** (a previous owner's notes/pencil answers) before extraction — never treat handwritten
content as source material. Same discipline as transcription risk: don't build a finding on a
`low_confidence` vision-read example without saying so.

**Historical & geographic context — optional, fill in only when the source supports it.** Entries
carry `Attested Era`/`Attested Region`/`Geographic Scope` columns — see
[`../00_Historical_and_Geographic_Context_Guide.md`](../00_Historical_and_Geographic_Context_Guide.md).
`—` is a legitimate value, not a gap to guess-fill; false precision here is worse than an honest
unknown.

**Morphological composition.** For agglutinative/polysynthetic (or complex fusional) word-forms,
`established/` entries include a morpheme breakdown rather than treating the surface form as
atomic — see `../00_Word_Concept_and_Morphological_Typology_Guide.md`.

## Graphify

This language gets its own graph, scoped to `datasets/Dutch/` (separate from
`language_corpus/Dutch/`'s own graph). **Already run once** (see `graphify-out/` in this folder) —
re-run after adding more content. Its `graph.json` (nodes carrying `source_file`/`source_location`)
is this language's organized-summary and pointer layer — no separate hand-authored index needed. If
a single language's graph itself grows past graphify's own size warnings (2M words / 500 files),
narrow further — e.g. graph `established/`, `analysis/`, and `synthesized/` as separate runs rather
than one combined pass.

**Before re-running: `cd` into `datasets/Dutch/` first, don't run graphify's own Python calls from
the repo root with only a `root=` argument.** Confirmed real bug during the Hungarian test run
(avoided here by cd-ing in correctly the first time): `save_manifest()` and likely other graphify
internals resolve output paths relative to the *working directory*, not `root=`. **After running,
always check `git status`/`git diff` on the repo-root `graphify-out/` before committing.** See
`../00_Reference_Extraction_Spec.md` for the full writeup.

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun)*

## Reference extraction progress (Phase 1)

Extracting from `25 Dutch An Essential Grammar.pdf` (Shetter & Van der Cruysse-Van Antwerpen, 9th
ed., Routledge), subagent-parallelized per `../00_Reference_Extraction_Spec.md`. Three chunks
dispatched, chosen deliberately for typological/register diversity rather than just sequential
chapters:

- [x] Chapters 1-3 (Pronunciation, Spelling, The Plural) — foundational. See
      `established/001_chapters1-3_pronunciation_spelling_plural.md`. As expected for a foundational
      pronunciation/spelling/plural chunk, vocabulary skewed almost entirely to `core` register (one
      exception: `engerd` "creep," tagged `colloquial` on lexical-meaning grounds since the source
      itself doesn't register-tag it) — the Ch.16 chunk's non-`core` diversity finding stands in
      useful contrast to this chunk's near-total `core` homogeneity.
- [x] Chapter 16 (Colloquial speech and writing) — dispatched **specifically to test whether a
      grammar reference's own colloquial-register chapter can surface `Usage Tier` diversity beyond
      `core`** — a gap flagged in both prior test runs (grammar textbooks skew almost entirely to
      `core` vocabulary). **Confirmed: yes.** See `established/002_chapter16_colloquial_speech.md`'s
      "Usage Tier findings" section — roughly two-thirds of the ~34 extracted vocabulary rows landed
      on `colloquial` or `formal` rather than `core`, driven by the chapter's discourse particles and
      its explicit §16.3 written-vs-spoken register table.
- [x] Chapter 22 (Diminutives) — dispatched to document Dutch's productive diminutive-suffix system
      for the morphological typology profile. See `established/003_chapter22_diminutives.md`: all
      four allomorphs (`-je`/`-tje`/`-etje`/`-pje`) with their phonological triggers, plus the
      vowel-length-alternation, t-drop, and vowel-doubling sub-rules. Also surfaced real Usage Tier
      diversity of its own — the diminutive-as-adverb construction (22.2) and the "personalizing
      suffix" attitude/stance use (22.3) are both source-marked/discussed as informal and tagged
      `colloquial`, while the plain form-class diminutives (22.1) and the semantic-drift/lexicalized
      diminutives (22.3.1) stayed `core`.
- [x] Everything else in `25` — superseded by `27` (Dutch: A Comprehensive Grammar, the companion
      volume covering the same and deeper territory) and the rest of the Wave 1/2 corpus below;
      `25` itself was not re-visited beyond Chapters 1-3/16/22.

**Wave 1 (13 clean-text sources) and Wave 2 (16 vision-read sources) are both fully extracted** —
see the summary table above and `00_Book_Triage_Catalog.md` for the original wave plan. Two
session-limit interruptions during Wave 2 left partial files with explicit continuation notes; all
were closed via targeted follow-up dispatches rather than re-extraction (see
`../../methodology-observations/dutch_test_run.md`).

**Known non-blocking gap:** `024` (Linguaphone Cursus Nederlands) — the Woordenlijst (vocabulary)
booklet's lessons 34-50, its phonology appendix, and its closing alphabetical dictionaries remain
unextracted (lessons 1-33 and the dialogue/exercise booklets are done). Flagged honestly rather than
silently dropped; a candidate for a future supplementary pass.

**Wave 3 (deferred, not pursued in this push):** the untriaged workbook/reading-booklet cluster
(`07`, `11`, `14`, `20`, `21`), *The UnDutchables* (cultural commentary), *Anne Frank — Het
Achterhuis*, and the 27-volume Dutch fairy-tale series (flagged for representative sampling only,
per the Russian Skazochnik precedent, not exhaustive coverage) — all remain genuinely out of scope
for Phase 1, per `00_Book_Triage_Catalog.md`'s original priority call.

## Next steps

Phase 1 is done for this language. Future work starts at Phase 2 (web scraping) or Phase 3 (slang
mechanics analysis) — see `ROADMAP.md`.
