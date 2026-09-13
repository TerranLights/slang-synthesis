# Slang Mechanics Analysis Index

**Purpose.** Tracks, per real-world language, whether its collected slang corpus has been
analyzed for the *mechanics* of how the slang actually forms and works — semantic shift,
phonological reduction/clipping, borrowing/code-switching, taboo inversion, metaphor productivity,
morphological play, register-marking, etc. — and where that analysis lives. This is the second
stage of the pipeline (see the repo `README.md`), downstream of `language_corpus/`.

**Status legend:**
- `not started` — no analysis has begun (may also mean corpus collection itself hasn't finished —
  check `language_corpus/00_Corpus_Collection_Index.md` first)
- `in progress` — partially analyzed, see the language's own `00_Extraction_Checklist.md`
- `complete` — mechanics analysis finished and ready to inform synthesis work

**Folder convention.** Each language in progress or complete gets its own folder here:
`datasets/<Language>/`, containing a `00_Extraction_Checklist.md` (tracks which mechanisms have
been examined, which corpus entries they were drawn from, what's still unexamined) plus numbered
output files (`01_...md`, `02_...md`, ...) holding the actual mechanics writeups — one per
mechanism or per coherent finding, in the same narrative style as the extraction files elsewhere
in this project family (quote real examples, name the actual linguistic phenomenon, don't invent
terminology that already exists). Copy `_TEMPLATE/` to start a new language.

**Prerequisite column — refined during the first test run (2026-08-30), see
`methodology-observations/serbian_croatian_bosnian_test_run.md`.** The `analysis/` and
`synthesized/` shards genuinely need `language_corpus/` to be at least `in progress` first. **The
`established/` shard does not** — it's populated from `source_reference/` grammar/vocabulary
material (Phase 1), which has no dependency on the slang corpus (Phase 3) at all. In practice this
means a language's `datasets/<Language>/` folder can show real progress (an `established/` shard)
before its `language_corpus/<Language>/` folder has anything in it — this is expected, not a
violation of the sequencing rule, as long as `analysis/`/`synthesized/` stay empty until the corpus
catches up.

**Scaling.** Content (`established/`, `analysis/`, `synthesized/`) lives as sharded Markdown files,
not JSON and not single monolithic files — see the per-language `00_Extraction_Checklist.md` and
`00_Reference_Extraction_Spec.md` for the numbering/chunking convention. Each language also gets its
**own** `graphify-out/` scoped to `datasets/<Language>/`, never one repo-wide graph — this is the
organized-summary/pointer layer over the Markdown content, not a separately hand-authored one. If a
single language's own graph outgrows graphify's size warnings, narrow further by graphing
`established/`, `analysis/`, and `synthesized/` separately.

---

## Status by language

| Language | Corpus status (see language_corpus index) | Analysis status | Folder |
|---|---|---|---|
| Serbian/Croatian/Bosnian | not started | **Phase 1 complete** — first language in the entire project to reach this milestone. `established/` has 115 Markdown files covering all 9 real reference documents (~850,000 words total): the flagship BCS textbook, its sociolinguistic-commentary and grammar companion volumes, Hammond's *Serbian: An Essential Grammar*, Magner's full 30-lesson course, both Hawkesworth "Colloquial" volumes, the *Srpske narodne bajke* folk-tale anthology, and Norris & Ribnikar's *Teach Yourself Serbian*; own `graphify-out/` rebuilt over the full corpus (453 nodes, 561 edges, 29 communities, zero dangling/missing edges); see `methodology-observations/serbian_croatian_bosnian_test_run.md` for full-language-folder-scale findings and `00_Extraction_Checklist.md` for the per-book breakdown; `analysis/`/`synthesized/` correctly empty pending Phase 3 (`language_corpus/`) progress | `datasets/Serbian_Croatian_Bosnian/` |
| Hungarian | in progress (Phase 3 slang-corpus started) | **Phase 1 complete** — second language in the project to reach this milestone, after Serbian/Croatian/Bosnian. `established/` has 53 Markdown files (~475,000 words) covering Rounds' *Hungarian: An Essential Grammar*, Kornai's *On Hungarian Morphology*, two proverb/idiom dictionaries, the two-volume FSI Basic Hungarian course, Siptár & Törkenczy's *Phonology of Hungarian*, the 1,324-page Magyaróra coursebook (sampled), the Davies phrasebook, an 1853 grammar (attested-era contrast), the Fenyvesi-edited *Hungarian Language Contact Outside Hungary* (11 chapters), *Teach Yourself Hungarian*, *Colloquial Hungarian*, *Hungarian in Words and Pictures* (sampled), *Hungarian with Ease*, *Hungarian Verbs*, and *Practical Hungarian Grammar*; own `graphify-out/` rebuilt over the full corpus (229 nodes, 332 edges, 10 communities, zero dangling/missing edges); see `00_Extraction_Checklist.md` for the per-book breakdown and `00_Book_Triage_Catalog.md` for the full triage/priority record; `synthesized/` correctly empty pending Phase 4 progress | `datasets/Hungarian/` |
| Korean | not started | **Phase 1 complete** — third language in the project to reach this milestone, after Serbian/Croatian/Bosnian and Hungarian, and the first from a non-Indo-European, non-Latin-script family. `established/` has 29 Markdown files (~400,000+ words) covering the Basic/Intermediate/Continuing Korean graded grammar series (Byon; King & Yeon), Choo & Kwak's *Using Korean: A Guide to Contemporary Usage*, Jae Jung Song's *The Korean Language: Structure, Use and Context*, *Intermediate College Korean* (partial, pp.1-224 of 376), *The Sounds of Korean: A Pronunciation Guide*, *Teach Yourself Korean*, *Korean Through English 1*, *Active Korean 1*, *In Flight Korean*, *Korean Grammar for International Learners* (both parts), both *Colloquial Korean* editions (one confirmed exact-duplicate scan), *Living Language Korean Course*, *Elementary Korean* (partial, pp.1-50 + pp.196-409 of 429), and four representative samples from Martin/Lee/Chang's 962-page *A Korean-English Dictionary*; own `graphify-out/` rebuilt over the full corpus (200 nodes, 277 edges, 13 communities, zero dangling/missing/collapsed edges); see `00_Extraction_Checklist.md` for the per-book breakdown and `00_Book_Triage_Catalog.md` for the full triage/priority record; two known non-blocking gaps (*Intermediate College Korean* pp.225-376, *Elementary Korean* pp.51-195) left open per honest partial-completion reporting; `analysis/`/`synthesized/` correctly empty pending Phase 3/4 progress | `datasets/Korean/` |
| Russian | in progress (Phase 3 corpus collection started: `Dermo!` slang dictionary, ~22,000 words) | **Phase 1 complete** — fourth language in the project to reach this milestone, after Serbian/Croatian/Bosnian, Hungarian, and Korean, and by a wide margin the largest single-language corpus this project has processed. `established/` has 281 Markdown files (~1,360,000 words) from a 204-file/3.6GB source corpus (the largest and most heterogeneous triaged so far, ~75% scanned image-only — the highest proportion of any language). Covers the full core grammar-reference set (Wade, Timberlake, Schaum's, Dunn & Khairov, and a dozen more), the register flagship *Using Russian: A Guide to Contemporary Usage*, the slang flagship *Streetwise Russian* (~340 entries, criminal/prison-argot throughline), and dozens of course books, specialist grammars, and thematic readers; own `graphify-out/` rebuilt over the full corpus (769 nodes, 894 edges, 42 communities, zero dangling/missing/collapsed edges after one fabricated cross-chunk edge was found and removed); recovered cleanly from three separate usage-limit disruptions across the run; a record 8 distinct Cyrillic PDF-corruption gotchas found and promoted to the extraction spec; five known non-blocking partial-coverage gaps (*Teach Yourself Russian* Units 14-20, *Everything in its Time* Section 12 onward, *Russian Grammar in Literary Contexts* Units 9-25, *Rossiya den segodnyashniy* Chapters 11-25, plus a deliberate 3-of-20-volume sample of the Сказочник folk-tale series) left open per honest partial-completion reporting; see `00_Extraction_Checklist.md` for the full per-book breakdown and `00_Book_Triage_Catalog.md` for the triage/priority record; `synthesized/` correctly empty pending Phase 4 progress | `datasets/Russian/` |
| Dutch | not started *(test-run language)* | not started — `established/` has 3 Markdown files (Phase 1, ~290 entries across 3 chapters chosen for typological/register diversity — foundational, colloquial, diminutives; confirmed real Usage Tier diversity beyond `core`, tentative); own `graphify-out/` built; `analysis/`/`synthesized/` correctly empty pending `language_corpus/` progress | `datasets/Dutch/` |

---

## Maintenance rule

**When a language's mechanics analysis begins, add its folder here and flip status to `in
progress` in the same commit.** Keep this index and `language_corpus/00_Corpus_Collection_Index.md`
consistent — a language should never show `complete` corpus here without an actual row, and never
show analysis progress beyond what the corpus supports.
