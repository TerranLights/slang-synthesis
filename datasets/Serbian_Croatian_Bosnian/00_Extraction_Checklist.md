# Serbian/Croatian/Bosnian Slang Mechanics — Extraction Checklist

**This is the pipeline's first test-run language — everything below is tentative until the
developer reviews it.** See `methodology-observations/serbian_croatian_bosnian_test_run.md` for
process findings, and `00_Book_Triage_Catalog.md` (this folder) for the source-material survey.

**Purpose:** analyze the actual mechanics of how Serbian/Croatian/Bosnian slang forms and works, using the
corpus collected in `language_corpus/Serbian/Croatian/Bosnian/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Serbian/Croatian/Bosnian/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

---

## Output files

| File | Contents |
|---|---|
| `01_....md` | *(fill in as mechanisms are examined — e.g. semantic shift, phonological reduction/clipping, borrowing/code-switching, taboo inversion, metaphor productivity, morphological play, register-marking)* |

---

## Structured JSON outputs — sharded, not flat files

**Scale warning:** given how much raw material this project draws on (dozens of languages, each
potentially thousands of slang terms and mechanism entries), a single `established.json` or
`synthesized.json` per language will not hold up — it becomes an unreviewable diff and a single
oversized graphify node. **Every structured output is therefore a directory of shards, not one
file:**

| Directory | Contents | Shard target size |
|---|---|---|
| `established/` | The real Serbian/Croatian/Bosnian baseline — vocabulary/grammar entries with frequency and weighting | ~300 entries/shard |
| `analysis/` | Structured mechanics findings, one entry per mechanism, cross-referencing corpus entries and `.md` writeups | ~100 entries/shard |
| `synthesized/` | Derived in-universe slang output. **Explicitly provisional** — revise via `revision_history`, never silent overwrite | ~200 entries/shard |

Each directory has an `_index.json` manifest (list of shard files, per-shard entry counts,
`last_updated`) and numbered shard files (`001_...json`, `002_...json`, ...), grouped by whatever
split makes sense for that language (semantic domain, register, mechanism family, alphabetical
range — pick one and note the convention in the manifest). **When a shard approaches its target
size, start a new one rather than letting it grow unbounded** — update `_index.json` in the same
commit. Copy the `_TEMPLATE/established/`, `_TEMPLATE/analysis/`, `_TEMPLATE/synthesized/`
directories (each holding an `_index.json` + one example shard) when starting a language.

**Usage-tier / slang-type categorization.** `established/` entries carry a `usage_tier` field
(e.g. `core`, `technical`, `taboo`, `slang`, ...) — see `datasets/00_Usage_Tier_Taxonomy.md` for
the shared vocabulary, which is meant to stay consistent across languages so findings are
comparable. `analysis/` and `synthesized/` entries carry `slang_type` and `derived_from_tiers`,
capturing which standard-language tier(s) a given slang-formation mechanism actually draws from —
this is how "different types of slang derive from different areas of standard language" gets
tracked concretely rather than staying an impression. **Every tier/type in the taxonomy is
extensible with dot-notation subcategories** (`"technical.medical"`) — use them freely as real data
surfaces distinctions worth keeping, and promote a subcategory into the shared taxonomy doc once
it recurs across 2+ languages.

**Transcription risk carries through.** Any `analysis/` example drawn from a corpus entry that was
itself sourced from a subtitle/transcript keeps that entry's `source_type` and
`transcription_confidence` — see
[`language_corpus/00_Source_Reliability_Guide.md`](../../language_corpus/00_Source_Reliability_Guide.md).
Don't build a mechanism finding on a `low_confidence` example without saying so; a mechanism whose
only supporting example is an unverified AI-transcript guess is itself weak evidence, not settled.

**Historical & geographic context — optional, fill in only when the source supports it.** Entries
carry `attested_era`/`attested_region`/`geographic_scope` fields — see
[`00_Historical_and_Geographic_Context_Guide.md`](../00_Historical_and_Geographic_Context_Guide.md).
`null` is a legitimate value, not a gap to guess-fill; false precision here is worse than an honest
unknown. When enough entries do carry real era/region data, watch for patterns worth flagging (a
`slang_type` that's actually region-bound, a mechanism that went dormant after a certain era).

## Graphify

This language gets its own graph, scoped to `datasets/Serbian/Croatian/Bosnian/` (separate from
`language_corpus/Serbian/Croatian/Bosnian/`'s own graph). Run `/graphify datasets/Serbian/Croatian/Bosnian` once there's
enough written here to be worth graphing — no need to do this before any content exists. If a
single language's graph itself grows past graphify's own size warnings (2M words / 500 files), that
is itself a signal to narrow further — e.g. graph `established/`, `analysis/`, and `synthesized/`
as separate runs rather than one combined pass.

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun; see `established/` for current progress)*

## Reference extraction progress (Phase 1)

- [x] `01.Bosnian Croatian Serbian a Textbook...` — Lesson 1 only (20 entries in
      `established/001_lesson01_basics.json`), tentative
- [ ] `01.Bosnian Croatian Serbian a Textbook...` — Lessons 2-20 not yet done
- [ ] `11.Bosnian Croatian Serbian - A grammar & Social Commentary.pdf` — not started
- [ ] `10.Serbian an essential grammar.pdf` — not started
- [ ] Remaining 5 books — deferred, see `00_Book_Triage_Catalog.md` (OCR/vision-reading needed for
      most of them)

**Open methodology question, not yet resolved:** whether Phase 1 extraction should aim for
exhaustive per-book coverage or representative sampling, and whether it should be parallelized via
subagents — see the methodology-observations log's "most consequential finding" entry. Continuing
with sampled, single-pass extraction for now pending that decision.

## Suggested next-session order

1. Read the developer's decision on exhaustive-vs-sampled and parallelized-vs-manual extraction
   (flagged in methodology observations) before continuing further Phase 1 work at scale.
2. If continuing manually: Lesson 2 of the Textbook, or move to
   `11.Bosnian Croatian Serbian - A grammar & Social Commentary.pdf` for its sociolinguistic
   commentary angle (likely useful for `usage_tier` data beyond `core`).
3. Decide an OCR/vision-reading approach for the 6 books without a usable text layer before
   attempting to extract from them.
