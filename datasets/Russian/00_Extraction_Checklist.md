# Russian Slang Mechanics — Extraction Checklist

**Purpose:** analyze the actual mechanics of how Russian slang forms and works, using the corpus
collected in `language_corpus/Russian/` and, where useful, the grammar/vocabulary reference in
`source_reference/languages/Russian/`. Findings here are what eventual synthesis work (deriving
invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

**Full triage:** see `00_Book_Triage_Catalog.md` — 204-file, ~3.6GB corpus, the largest and most
heterogeneous this project has processed. ~75% of files are scanned image-only with no text layer
(the highest proportion of any language triaged so far). Extraction proceeds in 3 waves; Wave 3
(vision-reading) is expected to span multiple sessions given its scale (~45 prioritized sources).

---

## Morphological typology

**Russian: fusional (inflectional), six-case system** (nominative, genitive, dative, accusative,
instrumental, prepositional), case/number/gender fused into single noun/adjective/pronoun endings
rather than agglutinatively stacked. Verbal aspect (perfective/imperfective) is a further dimension
often realized via suppletion/prefixation. Register expressed via ты/вы (T-V pronoun system) plus
lexical choice, not dedicated honorific morphology. To be refined with real morpheme-breakdown
examples once extraction lands.

---

## Output files — Markdown, sharded by numbered file, not JSON

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Russian baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

### Output files table

**Wave 1 complete (2026-09-12): 47 files, ~641,000 words, 15 distinct sources (Group A, clean text
layer) after dedup.** This alone already exceeds Hungarian's and Korean's full Phase 1 word counts.

| File(s) | Contents |
|---|---|
| `001_..._001n_basic_modern_russian_grammar.md` | *A Basic Modern Russian Grammar* — full 195p, 14-part split |
| `002/003_comprehensive_russian_grammar_part1/2.md` | Terence Wade, *A Comprehensive Russian Grammar* (Blackwell, 3rd ed.) — full 632p, 2-part split |
| `004_seelrc_russian_reference_grammar.md` | Edna Andrews, *Russian* (SEELRC 2001) — full 141p structural/phonological reference grammar |
| `005/005b_intermediate_russian_grammar_workbook.md` | *Intermediate Russian: A Grammar and Workbook* — full 239p, 2-part split |
| `006/007_reference_grammar_of_russian_cambridge_part1/2.md` | Alan Timberlake, *A Reference Grammar of Russian* (Cambridge 2004) — full 511p, 2-part split |
| `008/009_russian_self_teaching_guide_part1/2.md` | Kathryn Szczepanska, *Russian: A Self-Teaching Guide* (Wiley 2005) — full 313p, 2-part split |
| `010/011_colloquial_russian_2_part1/2.md` | *Colloquial Russian 2* (Le Fleming & Kay, Routledge 2003) — full 353p, 2-part split |
| `012/013_russian_grammar_schaums_outlines_part1/2.md` | *Schaum's Outline of Russian Grammar* (2nd ed., Levine 2009) — full 361p, 2-part split |
| `014_newspaper_russian_vocabulary.md` | *Newspaper Russian: A Vocabulary of Administrative and Commercial Idiom* — full 133p, register-specific vocabulary, 1,719 entries |
| `015_russkiy_bez_granits_grammar.md` | *Русский без границ* Grammar volume — full 192p |
| `016/017/018_big_silver_book_of_russian_verbs_part1/2/3.md` | Jack E. Franke, *The Big Silver Book of Russian Verbs* — full 673p verb-conjugation dictionary, 3-part split |
| `019/020/021(+b/c/d/e)_using_russian_vocabulary_part1/2/3.md` | Terence Wade, *Using Russian Vocabulary* (Cambridge 2009) — full 636p, 3-part split (part 3 further split per-unit) |
| `022/023/024_using_russian_contemporary_usage_part1/2/3.md` | Offord & Gogolitsyna, *Using Russian: A Guide to Contemporary Usage* — full 529p, **the register flagship source**, 3-part split |
| `025_lets_speak_russian.md` | Glazunova, *Давайте говорить по-русски* (5th ed. 2003) — 160p DJVU, vision-read (non-decodable OCR garbling) |
| `026/027_teach_yourself_russian_grammar_part1/2.md` | Daphne West, *Teach Yourself Russian Grammar* — full 216p DJVU, 2-part split |
| `028_russkie_glagoly_dvizheniya_s_pristavkami.md` | *Русские глаголы движения с приставками* — full 162p, prefixed motion-verb specialist reference |
| `029_kogda_ne_pomogayut_slovari_part1.md` | *Когда не помогают словари*, Part I — full 206p lexical/collocation practicum |

---

## Field/column conventions

Same shared conventions as every other language in this project — Usage Tier
(`../00_Usage_Tier_Taxonomy.md`), Transcription/Vision-Reading Confidence, Attested Era/Region
(`../00_Historical_and_Geographic_Context_Guide.md`), morpheme breakdown
(`../00_Word_Concept_and_Morphological_Typology_Guide.md`). See `_TEMPLATE/00_Extraction_Checklist.md`
for the full writeup of each.

## Graphify

This language gets its own graph, scoped to `datasets/Russian/`. Run `/graphify datasets/Russian`
once Wave 1 lands. **`cd` into `datasets/Russian/` first** — never run graphify's Python calls from
the repo root. Verify `git status` on the repo-root `graphify-out/` after every run.

## Mechanisms examined

- [ ] *(to be filled in once established/ has enough content to analyze)*

## Suggested next-session order

1. Complete Wave 1 (Group A clean-text sources, 15 distinct sources after dedup).
2. Wave 2 (Group B clean-text supplements) — apply non-redundant-supplement pattern heavily, several
   titles likely overlap Wave 1's core grammars.
3. Wave 3 (Group C vision-reading, ~45 prioritized sources) — start with *Streetwise Russian* and
   *Dermo!* given direct slang relevance; expect this wave to span multiple sessions.
4. Graphify rebuild once Wave 3 substantially lands.
