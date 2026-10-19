# Japanese Slang Mechanics — Extraction Checklist

**Full Phase 1 triage complete 2026-10-13.** See `00_Book_Triage_Catalog.md` for the source-material
survey — by far the largest corpus this project has triaged (8.9GB, 619 files, ~180+ in-scope
sources after scope filtering). Unlike every prior language, the large majority of in-scope material
has no usable text layer at all (CJK script defeats OCR far more consistently than any Latin/
Cyrillic-script language handled so far), so waves are organized by content category rather than by
text-layer status.

**Purpose:** analyze the actual mechanics of how Japanese slang forms and works, using the
corpus collected in `language_corpus/Japanese/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Japanese/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

---

## Morphological typology

**Japanese: agglutinative, with a unique multi-script writing system** — see
`00_Book_Triage_Catalog.md`'s morphological typology note for the preliminary profile (hiragana/
katakana/kanji mixed-script system, no word-boundary spacing in standard text, heavily agglutinative
verb/adjective conjugation, grammaticalized keigo honorific/politeness system). Refine here once
Wave 1/2 extraction lands with real worked examples.

---

## Output files — Markdown, sharded by numbered file, not JSON

Same storage model as every other language in this project — see `../00_Reference_Extraction_Spec.md`.

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Japanese baseline — vocabulary/grammar tables extracted per lesson/chapter/section | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings (Phase 3, not started) | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output (Phase 6, not started) | `001_<batch>.md`, ... |

Fill this table in as files are created:

| File | Contents |
|---|---|
| *(pending Wave 1 dispatch)* | |

## Field/column conventions

Same shared conventions as every other language — `Usage Tier`, `Attested Era`/`Attested Region`/
`Geographic Scope`, `Transcription Confidence`/`Vision Reading Confidence`, morpheme breakdowns
where relevant. See `../00_Reference_Extraction_Spec.md`. **New for Japanese**: vocabulary entries
should record the writing-system form actually used (kanji/hiragana/katakana) alongside romanization
and gloss, since script choice itself carries register/semantic information in Japanese (e.g.
katakana for loanwords or emphatic/slangy effect) in a way no prior language in this project has
needed to track.

## Graphify

This language gets its own graph, scoped to `datasets/Japanese/`. Not yet run — build after waves
land, likely in stages given the corpus's unprecedented scale (may need multiple incremental
`--update` runs rather than one single full build, given graphify's own 2,000,000-word/500-file
size-warning threshold could plausibly be approached by this language alone). **Must `cd` into
`datasets/Japanese/` first, never run graphify's Python calls from the repo root.**

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun)*

## Reference extraction progress (Phase 1)

- [x] Wave 1 — Writing System foundation (27 source files → 61 `established/` files,
      ~277,000 words). Full extraction for compact/lesson-structured sources; representative
      sampling for oversized kanji-dictionary-style references, per this project's standing
      practice. See commit history for the full per-source breakdown.
- [x] Wave 2 — Grammar, Workbooks, Usage (42 source files → 145 `established/` files,
      ~390,000 words). Full extraction for compact/lesson-structured sources (including the
      complete 10-volume Nihongo Notes series, ~740 essays); representative sampling for oversized
      grammar/sentence-pattern dictionaries. Recovered from a weekly usage-limit interruption that
      left several Nihongo Notes volumes untouched despite one file's inaccurate self-reported
      completion claim — caught via disk audit, not assumed. See commit history for the full
      per-source breakdown.
- [x] Wave 3 — Audio Courses, Textbooks (~65 source files → established/070-089, ~64
      established files, recovering cleanly from two separate session-limit interruptions mid-
      wave via disk-state verification rather than re-extraction). Full extraction for
      compact/lesson-structured sources; representative sampling for oversized courses (Nakama,
      Ultimate Japanese Advanced, Teach Yourself Japanese Complete Course, etc.). Notable finds:
      Japanese in Mangaland's register-tagged vocabulary index surfaced a yakuza/underworld slang
      cluster; Nakama Ch.8 consolidated a 6-way evidentiality register table; Ultimate Japanese
      Advanced documented an in-progress generational slang shift (やったぞ); Teach Yourself
      Japanese's Unit 22 is a dedicated informal-speech/dialect/insult unit. Two new extraction
      gotchas catalogued: undecodable CID-font corruption with no stable cipher (Teach Yourself
      Phone Japanese), and a fully text-layer-less 446-page scan with zero embedded fonts
      (Ultimate Japanese Advanced). See commit history for the full per-source breakdown.
- [x] Wave 4 — Vocabulary/Dictionaries (full `05.Vocabulary, Expressions, Idioms/` +
      `07.Dictionaries, Phrasebooks/` folders → established/090-102, ~85 established files).
      Full extraction for compact/lesson-structured and dictionary-style sources where feasible;
      representative sampling for the 2 flagged oversized dictionaries (NTC's New Japanese-English
      Character Dictionary, 2217pp; The Kodansha Kanji Learner's Dictionary, 1054pp) and other
      large flat-list references (VocabuLearn series, Nihongo Hyogen Bunkei Jiten). **Two flagship
      slang-dictionary pairs fully extracted**: Dirty Japanese/Zakennayo! (~1,218 rows) and Making
      Out In Japanese/More Making Out In Japanese (~1,677 rows), with explicit gendered-register
      tagging and a documented Kantō/Kansai regional split on vulgar vocabulary (omanko/omeko,
      baka/aho). Other notable finds: a regular sound-symbolism/mimetic-derivation system
      (korokoro/gorogoro voicing alternation, 5 verb-suffix + 3 na-adjective-suffix patterns)
      directly reusable for slang synthesis; the Rough Guide phrasebook's self-labeled 28-term
      slang/colloquialism section; a productive 100-word→1,000-idea combinatorial template
      (Instant Japanese); a genuine byte-identical duplicate-file pair caught before double
      extraction (Nihongo Hyogen Bunkei Jiten). One new extraction gotcha catalogued: genuinely
      non-monotonic page ordering within a single scanned PDF (Zakennayo!), distinct from the
      prior two-pages-per-spread gotcha. One live numbering collision (`098` claimed by two
      concurrent dispatches) resolved cleanly by routing the later source to the next free slot
      (`102`). See commit history for the full per-source breakdown.
- [x] Wave 5 — Children's Books, Readers (tiered: 6 Tier-1 literary readers extracted in full/
      deep-sampled, Tier-2 picture books representatively sampled, Tier-3 "Light Novels" folder
      confirmed empty and skipped → established/103-107, 11 established files). **Tier 1** (6
      books, the triage catalog's original "~4" estimate undercounted the subfolder — 2 more
      genuine literary readers turned up on disk): Breaking into Japanese Literature + Exploring
      Japanese Literature (~315 rows, 10 Sōseki/Akutagawa/Kawabata/Mishima/Tanizaki stories
      sampled; the "Read Real Japanese" family resolved into 3 genuinely distinct books despite
      overlapping titles via direct colophon comparison (~146 rows, 32 grammar subsections, 23
      stories/chapters); Moons, Months and Seasons extracted in full (~780 rows, complete 12-month
      back-glossary). **Tier 2** (representative sample per standing Russian Сказочник/Dutch
      fairy-tale precedent): graded readers sampled across all 3 difficulty levels (surfaced the
      series' own publisher-stated difficulty/register-shift table — furigana density and
      です/ます→である/のだ register both tighten level-by-level); one Favorite Stories title
      (Kaguyahime, 62 rows) — also resolved a suspected duplicate-edition question (the two
      standalone top-level PDFs turned out to be genuinely distinct hand-drawn-vs-commercial
      editions of the same folk tales, not duplicates). **Tier 3**: confirmed zero actual content
      (cover thumbnails only), skipped entirely as planned. New gotcha: block-scale non-monotonic
      PDF page ordering (Reading Japanese with a Smile), a second instance of the pattern first
      seen on *Zakennayo!* in Wave 4. See commit history for the full per-source breakdown.
- [ ] Wave 6 — Society/Culture gems + remaining course material (~10 files)
