# Serbian/Croatian/Bosnian Slang Mechanics — Extraction Checklist

**This is the pipeline's first test-run language — everything below is tentative until the
developer reviews it.** See `../../methodology-observations/serbian_croatian_bosnian_test_run.md`
for process findings (including the full bridge-scale-test writeup), and `00_Book_Triage_Catalog.md`
(this folder) for the source-material survey.

**Purpose:** analyze the actual mechanics of how Serbian/Croatian/Bosnian slang forms and works,
using the corpus collected in `language_corpus/Serbian_Croatian_Bosnian/` and, where useful, the
grammar/vocabulary reference in `source_reference/languages/Serbian, Croatian, Bosnian/`. Findings
here are what eventual synthesis work (deriving invented slang for the sci-fi setting) will be
grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[~]` partially done · `[ ]` not
yet done.

---

## Morphological typology

**Serbian/Croatian/Bosnian: fusional.** Grammatical categories (case, number, gender) are merged
into single, non-separable affixes rather than agglutinated as distinct stacked morphemes — e.g.
`mòje` (neuter possessive "my") fuses possession, gender, and number into one ending, not separable
into individually-meaningful pieces the way an agglutinative language's morphology would be. **Held
across the full-book bridge-scale extraction** (Lessons 1-20 plus appendices and the full glossary,
~8,450 vocabulary rows) — no agglutinative or polysynthetic behavior turned up anywhere, no morpheme
breakdowns were needed in any of the 32 output files. See
`../00_Word_Concept_and_Morphological_Typology_Guide.md`.

---

## Output files — Markdown, sharded by numbered file

**Status: full-book bridge-scale extraction complete for the flagship Alexander & Elias-Bursać
textbook** (chosen as this project's first "very large single book" scale test — see the
methodology-observations log). 32 files, ~8,450 vocabulary rows, ~338,000 words total.

| Directory | File | Contents |
|---|---|---|
| `established/` | `001_lesson01_basics.md` | Original manual test-run sample of Lesson 1 (20 entries) — **superseded** by `003_lesson01_complete.md`, kept for methodology history. |
| `established/` | `002_lesson01_magner_vision_test.md` | Magner's *Introduction to the Croatian and Serbian Language*, Lesson 1 (86 entries) — this project's **vision-reading test** (scanned, no text layer), medium-high confidence, retrofitted `Vision Reading Confidence` column. |
| `established/` | `003_lesson01_complete.md` | Alexander & Elias-Bursać, Lesson 1 (Prva lekcija), full re-extraction (181 rows) — supersedes `001`. |
| `established/` | `004_lesson02.md` | Lesson 2 (Druga lekcija) — 204 rows. |
| `established/` | `005_lesson03.md` | Lesson 3 (Treća lekcija) — 127 rows. |
| `established/` | `006_lesson04.md` | Lesson 4 (Četvrta lekcija) — 204 rows. |
| `established/` | `007_lesson05.md` | Lesson 5 (Peta lekcija) — 285 rows; a real `pdftotext` column-scrambling bug was caught and self-corrected (see observations log). |
| `established/` | `008_lesson06.md` | Lesson 6 (Šesta lekcija) — 237 rows. |
| `established/` | `009_lesson07.md` | Lesson 7 (Sedma lekcija) — 160 rows; **source explicitly labels a phrase "Amusing slang usage"** (`Ma moj!`) — first source-self-labeled slang in the project. |
| `established/` | `010_lesson08.md` | Lesson 8 (Osma lekcija) — 90 rows. |
| `established/` | `011_lesson09.md` | Lesson 9 (Deveta lekcija) — 179 rows; **explicit Belgrade slang (`kèva` "Mom") and teen slang (`stara`/`stari`/`starci`)**, plus regional colloquial family-term variation across 4 cities/regions. |
| `established/` | `012_lesson10.md` | Lesson 10 (Deseta lekcija) — 230 rows. |
| `established/` | `013_lesson11.md` | Lesson 11 (Jedanaesta lekcija) — 239 rows. |
| `established/` | `014_lesson12.md` | Lesson 12 (Dvanaesta lekcija) — 186 rows. |
| `established/` | `015_lesson13.md` | Lesson 13 (Trinaesta lekcija) — 178 rows. |
| `established/` | `016_lesson14.md` | Lesson 14 (Četrnaesta lekcija) — 200 rows. |
| `established/` | `017_lesson15.md` | Lesson 15 (Petnaesta lekcija) — 133 rows; a possible source erratum (reversed `[B]`/`[C]` tag) verified against the page image and recorded faithfully rather than "corrected." |
| `established/` | `018_lesson16.md` + `018_lesson16_vocab2.md` + `018_lesson16_vocab3.md` | Lesson 16 (Šesnaesta lekcija) — 110+77+125 = 312 rows; the subagent split its own output into 3 files unprompted once it grew large, correctly following the "don't let a file grow unbounded" rule on its own initiative. |
| `established/` | `019_lesson17.md` | Lesson 17 (Sedamnaesta lekcija) — 139 rows. |
| `established/` | `020_lesson18.md` | Lesson 18 (Osamnaesta lekcija) — 157 rows; reading/poetry-comprehension lesson, thinner grammar section flagged transparently rather than padded. |
| `established/` | `021_lesson19.md` | Lesson 19 (Devetnaesta lekcija) — 205 rows; **first `archaic` and `regional` usage-tier entries in the project** (Montenegrin dialect forms explicitly glossed in an epic-poem excerpt). |
| `established/` | `022_lesson20.md` | Lesson 20 (Dvadeseta lekcija, final lesson) — 302 rows, a graded reading with 8 vocabulary boxes. |
| `established/` | `023_appendices1-6_grammar_reference.md` | Appendices 1-6, consolidated grammar-reference tables — 106 rows. |
| `established/` | `024_appendix9_verb_types.md` | Appendix 9, verb-type classification — 23 rows. |
| `established/` | `025_appendices7-8_literary_readings.md` | Appendices 7-8, two copyrighted short stories (Albahari, Bazdulj) — vocabulary-only extraction, no plot/prose reproduction — 95 rows. **Contains the single most important finding of this test run: a footnoted syllable-switching slang-formation mechanism** (`vozdra`<`zdravo`, `žemka`<`kažem`), with regional (Sarajevo/Zagreb) and historical (1960s Zagreb) attestation. |
| `established/` | `026_glossary_bcs_english_part1.md` | BCS-English Glossary, part 1 of 5 (A through hvala) — 809 rows. First `taboo` (explicitly "vulg." in source), `colloquial`, `literary` (poetic), and `technical.grammar`/`technical.linguistics` dot-notation entries in the project. |
| `established/` | `027_glossary_bcs_english_part2.md` | Glossary part 2 (hvala through napasti) — 798 rows. |
| `established/` | `028_glossary_bcs_english_part3.md` | Glossary part 3 (napadati through posvetiti) — 792 rows. |
| `established/` | `029_glossary_bcs_english_part4.md` | Glossary part 4 (posvećujem se through stalan) — 801 rows. |
| `established/` | `030_glossary_bcs_english_part5.md` | Glossary part 5 (stalo through Ž, end of glossary) — 972 rows. |
| `established/` | `031_socioling_ch21_intro_writing_standardization.md` | Alexander, *Grammar: With Sociolinguistic Commentary*, Ch. 21 — writing-system history, standardization to 1974 — 19 rows. |
| `established/` | `032_socioling_ch22_dialect_differences.md` | Ch. 22, "Dialect Differences" — 111 rows across two source-curated tables (ekavian/ijekavian/ikavian pronunciation chart, 42-pair East/West lexical list). **The single highest-value chapter in this book for this project's purposes** — direct, explicitly-labeled regional/national lexical data plus the source's own argument that vocabulary (not alphabet/pronunciation/grammar) is the real B/C/S differentiator. |
| `established/` | `033_socioling_ch23_bosnian.md` | Ch. 23, "Bosnia" — 27 rows (Ottoman-loanword doublets, the Bosnian/Bosniak naming dispute); sensitive 1990s political content handled source-attributed, not editorialized, matching the Kosovo-note discipline from `006_lesson04.md`. |
| `established/` | `034_socioling_ch24_croatian.md` | Ch. 24, "Croatia" — 20 rows (dialect-faction nicknames, purist coinages, named standardization documents); WWII-era NDH language-policy history handled with the same neutral, source-attributed discipline. |
| `established/` | `035_socioling_ch25_serbian_montenegro.md` | Ch. 25, "Serbia"/"Montenegro" — 22 rows, including the Nikčević 1997 Montenegrin-orthography proposals (ś/ź/з). **Confirms and substantially deepens the Lesson 8/19 Montenegrin finding** with real scholarly nuance (claimed distinguishing features are shared East Herzegovinian dialect features, not exclusively Montenegrin, per the source's own verdict). |
| `established/` | `036_socioling_ch26_one_or_more_languages.md` | Ch. 26 (final chapter), the author's own "one language or more than one" synthesis — 7 rows, deliberately thin. Contains a load-bearing meta-finding: the source states its own `[B]`/`[C]`/`[S]` tagging convention is a simplification of a frequency gradient, not a hard categorical split — relevant to how every `Usage Tier`/`Attested Region` tag drawn from this book should be read. |
| `analysis/` | *(none yet)* | Phase 3 not started — gated on `language_corpus/Serbian_Croatian_Bosnian/` reaching `in progress`. |
| `synthesized/` | *(none yet)* | Phase 5 not started. |

**Deliberately excluded from extraction** (per `00_Book_Triage_Catalog.md`): Appendix 10 (answer key
— drill content, per the coverage rule), the English-BCS reverse glossary (redundant with the
BCS-English glossary already extracted), and the Index (no content value).

**No `_index.json` manifest** — this table is the human-readable index. `/graphify
datasets/Serbian_Croatian_Bosnian` provides the machine-queryable pointer/summary layer.

---

## Field/column conventions

**Usage-tier / slang-type categorization.** `established/` vocabulary tables carry a `Usage Tier`
column — see `../00_Usage_Tier_Taxonomy.md`. At full-book scale, real diversity emerged:
`core` (the vast majority), `colloquial`, `formal`, `slang` (explicitly source-labeled twice —
Lesson 7, Lesson 9), `taboo` (explicitly "vulg." in the glossary), `literary` (poetic-marked
glossary entries, plus the literary-appendix vocabulary), `archaic`, and `regional` (Montenegrin
dialect forms). Dictionaries/glossaries turned out to be an even richer source of tier diversity
than "colloquial" chapters (the Dutch test run's finding) — a dictionary's whole purpose is marking
register, so it does so far more explicitly and frequently than a teaching grammar's prose.

**Transcription risk carries through** from `language_corpus/` sources — see
[`../../language_corpus/00_Source_Reliability_Guide.md`](../../language_corpus/00_Source_Reliability_Guide.md).
Not yet relevant here since no corpus collection has begun.

**Vision-reading risk.** `established/002_lesson01_magner_vision_test.md` remains this project's
vision-reading test (a scanned, no-text-layer book), medium-high confidence, retrofitted `Vision
Reading Confidence` column. All 35 other files in this language have a real text layer, so `Vision
Reading Confidence` is `n/a` throughout them. See `../00_Reference_Extraction_Spec.md`'s
Vision-reading guard section. This will change once the vision-only books (`03.Colloquial Serbian
and Croatian.pdf`, `Colloquial Serbian/Colloquial Serbian.pdf`, the rest of Magner, `29.Serbian Folk
Tales.pdf`, `Teach Yourself Serbian.pdf`) are extracted.

**Historical & geographic context.** `Attested Era`/`Attested Region`/`Geographic Scope` columns —
see [`../00_Historical_and_Geographic_Context_Guide.md`](../00_Historical_and_Geographic_Context_Guide.md).
Exercised extensively at full-book scale via the source's own `[B]`/`[C]`/`[S]` and `[E]`/`[J]`
(Ekavian/Ijekavian) tagging, plus explicit Montenegrin-dialect and city-specific-slang attribution
(Belgrade, Zagreb, Sarajevo).

**PDF text-extraction gotchas found at this scale** (see observations log for full detail — worth
knowing before extracting any other two-column-glossary-style source): (1) `pdftotext -layout` can
scramble multi-column vocabulary-table layouts, requiring cross-checking against page context; (2)
`pdftotext -layout` on a genuinely two-column dictionary/glossary page interleaves left/right column
text on shared lines, requiring per-column bounding-box extraction (`-x`/`-W` or left/right crops)
instead; (3) a third-party "Advanced PDF Repair" tool's own processing artifacts can introduce
additional column-reconstruction noise on top of the above.

## Graphify

This language gets its own graph, scoped to `datasets/Serbian_Croatian_Bosnian/` (separate from
`language_corpus/Serbian_Croatian_Bosnian/`'s own graph). **Rebuilt at full-book scale** (34 files,
~340,000 words) — see `graphify-out/` in this folder. Semantic extraction was itself split into 2
subagent chunks (17 files each), the first real test of graphify's own multi-chunk dispatch in this
project.

**Before re-running: `cd` into `datasets/Serbian_Croatian_Bosnian/` first, don't run graphify's own
Python calls from the repo root with only a `root=` argument.** Confirmed real bug (Hungarian test
run): `save_manifest()` and likely other graphify internals resolve output paths relative to the
*working directory*, not `root=` — running from the repo root can silently corrupt the repo-root
`graphify-out/manifest.json`. **After running, always check `git status`/`git diff` on the repo-root
`graphify-out/` before committing.** See `../00_Reference_Extraction_Spec.md` for the full writeup.

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun. However, the syllable-switching slang mechanism found in `025_appendices7-8_literary_
      readings.md` is flagged as an obvious first candidate once Phase 3 begins.)*

## Reference extraction progress (Phase 1)

- [x] `01.Bosnian Croatian Serbian a Textbook...` — **full book complete** (all 20 lessons +
      Appendices 1-6, 9, 7-8 + full BCS-English glossary, 32 files, ~8,450 rows). This is the
      project's first full-book bridge-scale extraction — see
      `../../methodology-observations/serbian_croatian_bosnian_test_run.md` for the full writeup.
- [~] `11.Bosnian Croatian Serbian - A grammar & Social Commentary.pdf` — **Sociolinguistic
      Commentary half complete** (Chapters 21-26, all 6 files, 206 rows — deliberately extracted
      first, ahead of the much larger Grammar half, per the register/sociolinguistic-chapter-
      prioritization finding from the Dutch test run: this section is genuinely new content, not
      covered by the companion textbook, and is directly Usage-Tier/Attested-Region-relevant).
      **Grammar half (Chapters 1-20, ~378 pages) not yet started** — largely overlaps in scope with
      the already-extracted flagship textbook (same author team, explicitly designed as companion
      volumes), so extraction should focus on material genuinely deeper/different from what
      `established/003-024` already cover, not re-derive the same basics.
- [ ] `10.Serbian an essential grammar.pdf` — not started
- [x] `12.Introduction to the Croatian and Serbian language.pdf` (Magner) — Lesson 1 only (86 entries
      in `established/002_lesson01_magner_vision_test.md`), vision-reading test. Not extended to the
      rest of this book — deferred behind the now-complete flagship textbook.
- [ ] `12.Introduction to the Croatian and Serbian language.pdf` (Magner) — Lessons 2-30 not yet done
- [ ] `03.Colloquial Serbian and Croatian.pdf` (318p) and `Colloquial Serbian/Colloquial Serbian.pdf`
      (194p) — both vision-only (no text layer), both flagged high-value by their "colloquial"
      framing per `00_Book_Triage_Catalog.md`; not yet started.
- [ ] `29.Serbian Folk Tales.pdf` (240p, vision-only) — literary/archaic-tier corpus, deferred per the
      triage catalog until the `literary`/`archaic` usage tiers need more real examples (they now
      have some — see Ch. 23-25 above and `025_appendices7-8_literary_readings.md` — worth
      revisiting this call).
- [ ] `Teach Yourself Serbian/Teach Yourself Serbian.pdf` (177p, garbled OCR text layer — needs
      vision reading, not `pdftotext`) — not started, low priority per the triage catalog.
- [ ] `01.Key to audio recordings.PDF` (2p, trivial) — low value, not started.

**Correction to a stale claim in this section (found during the follow-on extraction pass):**
Phase 0 triage for this language is already complete — see `00_Book_Triage_Catalog.md`, which
covers all 9 real reference documents (2 of which live in subfolders: `Colloquial Serbian/` and
`Teach Yourself Serbian/`, each containing one book). There is no separate set of "6 untriaged
audio-course subfolders" for this language — that claim, which appeared in an earlier version of
this section, was inaccurate (likely conflated with the Hungarian language folder's own 6 deferred
subfolders, a genuinely different situation). Corrected here so it doesn't get repeated.

**Resolved methodology questions (see `../00_Reference_Extraction_Spec.md` and
`../../methodology-observations/serbian_croatian_bosnian_test_run.md`):** coverage is
comprehensive-but-not-exhaustive (every grammar point, every distinct vocabulary item, every
regional annotation; skip repeated drills — except dense glossaries, which get genuinely exhaustive
treatment since they have no padding to skip); extraction is subagent-parallelized, chunked by
lesson/chapter; **confirmed working at bridge-test scale (28 chunks, up from the previously-tested
3)** — see the observations log for the full verdict on readiness for full-language-folder-scale
extraction across all 40+ languages.

## Suggested next-session order

**Goal: full-language-folder extraction for this language** (see
`methodology-observations/serbian_croatian_bosnian_test_run.md`'s bridge-scale-test verdict —
methodology validated for this, budgeting wave-based dispatch per `00_Reference_Extraction_Spec.md`).

1. **In progress:** `11.Bosnian Croatian Serbian - A grammar & Social Commentary.pdf`'s Grammar half
   (Chapters 1-20, ~378 pages) — the Sociolinguistic Commentary half (Ch. 21-26) is done. This is the
   largest remaining chunk of clean-text-layer material for this language; dispatch in waves per the
   20-concurrent-subagent cap (roughly 2 waves of ~10 chapters each, or similar), watching for
   content overlap with the already-extracted flagship textbook (same author team, explicitly
   designed as companion volumes) — favor material that's genuinely deeper/different.
2. `10.Serbian an essential grammar.pdf` (337 pages, clean text, Serbian-only — good for
   cross-checking Serbian-specific entries against the comparative textbook).
3. Decide a vision-reading approach for the 5 remaining vision-only/garbled-OCR books (`03.Colloquial
   Serbian and Croatian.pdf`, `Colloquial Serbian/Colloquial Serbian.pdf`, Magner's remaining ~29
   lessons, `29.Serbian Folk Tales.pdf`, `Teach Yourself Serbian.pdf`) — the two "Colloquial"-titled
   books are flagged high-value by their register framing despite the vision-reading cost.
   `01.Key to audio recordings.PDF` (trivial, 2 pages) can be picked up cheaply alongside any of the
   above.
4. Once all 9 real reference documents are extracted (or explicitly deferred with reason), this
   language's Phase 1 is genuinely complete — update `ROADMAP.md`/`00_Analysis_Index.md` to reflect
   that milestone explicitly, since it would be the first language to reach it.
5. Given the full corpus now available, Phase 3 (mechanics analysis) could plausibly begin once
   `language_corpus/Serbian_Croatian_Bosnian/` reaches `in progress` — the syllable-switching slang
   mechanism alone is a strong first analysis target.
