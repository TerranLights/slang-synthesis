# Dutch Slang Mechanics — Extraction Checklist

**This is the pipeline's third test-run language — everything below is tentative until the
developer reviews it.** See `../../methodology-observations/dutch_test_run.md` for process findings
(comparing against the Serbian/Croatian/Bosnian and Hungarian runs) and `00_Book_Triage_Catalog.md`
(this folder) for the source-material survey. (`Dutch` is its own folder-safe name — no
display-name-vs-path-name split needed here.)

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
`language_corpus/Dutch/`'s own graph). Run `/graphify datasets/Dutch` once there's
enough written here to be worth graphing — no need to do this before any content exists. Its
`graph.json` (nodes carrying `source_file`/`source_location`) is this language's organized-summary
and pointer layer — no separate hand-authored index needed. If a single language's graph itself
grows past graphify's own size warnings (2M words / 500 files), narrow further — e.g. graph
`established/`, `analysis/`, and `synthesized/` as separate runs rather than one combined pass.

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
- [ ] Everything else in this book, and `83 The Phonology of Dutch.pdf` / `10 Colloquial Dutch.pdf`
      (both vision-read candidates) — not started, see `00_Book_Triage_Catalog.md`

## Suggested next-session order

1. Once the 3 parallel-subagent chunks land, compare against the Serbian/Croatian/Bosnian and
   Hungarian runs — see `../../methodology-observations/dutch_test_run.md`.
2. If Chapter 16 did surface non-`core` usage tiers, that's a real methodology finding worth
   promoting into the shared taxonomy discussion.
3. Decide a vision-reading approach for `83 The Phonology of Dutch.pdf` and `10 Colloquial
   Dutch.pdf` before attempting to extract from them.
