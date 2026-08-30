# {{Language}} Slang Mechanics — Extraction Checklist

**When filling in `{{Language}}` below: use the folder-safe name (matching the actual
`datasets/<Language>/` directory name, e.g. `Serbian_Croatian_Bosnian`) in every file path, and the
natural display name (e.g. "Serbian/Croatian/Bosnian") in prose only. A naive find-and-replace of
`{{Language}}` with the display name will corrupt any path containing it — confirmed as a real bug
during the first test run, see `../../methodology-observations/serbian_croatian_bosnian_test_run.md`.

**Purpose:** analyze the actual mechanics of how {{Language}} slang forms and works, using the
corpus collected in `language_corpus/{{Language}}/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/{{Language}}/`. Findings here are what eventual synthesis
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

**{{Language}}:** *(not yet characterized)*

---

## Output files — Markdown, sharded by numbered file, not JSON

**Storage model.** All extracted content — raw reference data, mechanics analysis, synthesized
results — lives as **Markdown** (occasionally `.txt`), not hand-authored JSON. This matches how the
rest of this project's own methodology documentation works, and lets `/graphify` serve as the
organized-summary/pointer layer instead of a manually-maintained manifest (see Graphify section
below).

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real {{Language}} baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
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
| *(none yet)* | |

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

**Historical & geographic context — optional, fill in only when the source supports it.** Entries
carry `Attested Era`/`Attested Region`/`Geographic Scope` columns — see
[`../00_Historical_and_Geographic_Context_Guide.md`](../00_Historical_and_Geographic_Context_Guide.md).
`—` is a legitimate value, not a gap to guess-fill; false precision here is worse than an honest
unknown.

**Morphological composition.** For agglutinative/polysynthetic (or complex fusional) word-forms,
`established/` entries include a morpheme breakdown rather than treating the surface form as
atomic — see `../00_Word_Concept_and_Morphological_Typology_Guide.md`.

## Graphify

This language gets its own graph, scoped to `datasets/{{Language}}/` (separate from
`language_corpus/{{Language}}/`'s own graph). Run `/graphify datasets/{{Language}}` once there's
enough written here to be worth graphing — no need to do this before any content exists. Its
`graph.json` (nodes carrying `source_file`/`source_location`) is this language's organized-summary
and pointer layer — no separate hand-authored index needed. If a single language's graph itself
grows past graphify's own size warnings (2M words / 500 files), narrow further — e.g. graph
`established/`, `analysis/`, and `synthesized/` as separate runs rather than one combined pass.

## Mechanisms examined

- [ ] *(one bullet per mechanism or corpus subset examined — name the real linguistic phenomenon,
      cite the specific corpus entries it's drawn from, don't invent terminology that already
      exists in the linguistics literature)*

## Suggested next-session order

1. *(fill in)*
