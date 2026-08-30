# Roadmap

**Purpose.** The reference material alone (`source_reference/`) is 70GB+ across 40+ languages —
not a "do it all at once" task. This roadmap sequences the work into phases and flags concerns
that only become obvious partway in, so effort goes where it actually pays off instead of grinding
uniformly through everything.

**Status legend:** `not started` · `in progress` · `complete`. Update this file's phase statuses as
work actually begins/finishes — same discipline as the per-language indexes.

---

## Phase 0 — Triage pass (not full extraction)

**Status: not started.**

Before deep-extracting any single book, survey what's actually in each
`source_reference/languages/<Language>/` folder: which titles look highest-yield (a real grammar >
a phrasebook > an audio-course companion booklet), and — critically — **which are genuine text
layers vs. image-only scans** that will need vision-based reading rather than text extraction (some
of the `.djvu` files especially are likely to be scans; the Inner Tepenia GDD repo hit this with an
image-only PDF that had to be read visually).

**Output:** a `Book_TOC_Master_Reference.md`-style catalog per language — what exists, format,
scan-vs-text-layer status, and a rough priority call — *before* any checklist work in
`datasets/<Language>/` or `language_corpus/<Language>/` begins. This is cheap and prevents burning
hours deep-extracting a book that turns out low-value.

## Phase 0.5 — Language priority tiering

**Status: not started — blocked on input.**

40+ languages are staged. Working through them in alphabetical or arbitrary order wastes effort on
ones that may never matter to the actual story. Needs a short ranking (Tier 1 / 2 / 3) of which
real-world languages most directly inform specific in-universe cultures/factions, so Phase 1+
sequencing is driven by narrative need rather than folder order.

**Requires:** a mapping of real-world languages → in-universe cultures/factions, which lives in
creative/setting knowledge outside this repo's current scope. Revisit once that's available, or do
it incrementally (tier the next language right before starting it, rather than all 40+ up front).

## Phase 1 — Reference extraction (grammar/vocab)

**Status: not started.** See `datasets/00_Analysis_Index.md` and
`language_corpus/00_Corpus_Collection_Index.md` for live per-language status once this begins.

**Prove the pipeline on one or two flagship languages first — do not fan out to many languages in
parallel before the schema/shard/OCR approach is actually validated end-to-end.** Catching a
schema problem, a bad shard-size assumption, or an OCR/scan-handling gap on language #1 is cheap;
catching it after 15 languages are already partway through is not.

**OCR/scan handling is its own concern**, not a detail to improvise per-book. Flag in the Phase 0
catalog which books need vision-based reading vs. have a usable text layer — this changes
extraction cost per book substantially and should inform Phase 0.5 prioritization too (a
Tier-1 language whose best source is a 400-page image-only scan is a different effort estimate
than one with clean text-layer PDFs).

**Copyright discipline.** Reference material is copyrighted grammars/dictionaries. Extraction
stays in the same mode already modeled by the Inner Tepenia GDD repo's book extractions: selective
quotes + paraphrase + analysis connecting real material to project needs — never bulk reproduction
of a book's content into this repo.

## Phase 2 — Web research / slang corpus collection

**Status: not started.** See `language_corpus/00_Corpus_Collection_Index.md` for live status.

Web-scraping mechanics are their own concern, separate from the linguistic content itself: rate
limits, ToS respect, and — critically — **which platforms are actually worth the time varies by
language and region** and is itself worth researching before committing hours per language (this
is exactly what `language_corpus/00_Source_Reliability_Guide.md`'s platform reliability registry
exists to accumulate for subtitle/transcript sources specifically; the same "which platforms are
actually good for this language" question applies more broadly to slang-forum/dictionary sources
too).

Subtitle/transcript mining (a rich source, with real risk — see the reliability guide) sits inside
this phase, not as a separate one.

## Phase 3 — Mechanics analysis

**Status: not started.** See `datasets/00_Analysis_Index.md` for live status. Gated per-language on
that language's Phase 2 corpus being at least `in progress`.

## Phase 4 — Cross-language comparative pass

**Status: not started — blocked on Phase 3 producing real data for 2+ languages.**

Once a handful of languages have real `analysis/` data, look across them: which `slang_type`s (see
`datasets/00_Usage_Tier_Taxonomy.md`) recur across languages vs. stay language-specific, which
usage-tier subcategories show up repeatedly and deserve promotion to the shared taxonomy, and
whether any genuinely universal slang-formation patterns emerge vs. patterns that are artifacts of
one language/culture. This is where the taxonomy's "promote once 2+ languages show it" rule
actually gets exercised for real, rather than staying theoretical.

## Phase 5 — Synthesis

**Status: not started.** Already schema-scaffolded (`datasets/<Language>/synthesized/`). Feeds the
actual sci-fi conlang/culture work, which likely lives partly outside this repo in wherever the
fictional cultures themselves are defined (cross-reference once that connection point is decided).

## Cross-cutting: QA / spot-check cadence

**Not a one-time step — an ongoing discipline once Phase 2+ produces real entries.** Periodically
re-verify a sample of flagged (`low_confidence`, `plausible_unverified`) entries, especially any
that fed into a `synthesized/` term — don't let a flagged-but-never-revisited entry quietly become
load-bearing for creative work downstream. See
`language_corpus/00_Source_Reliability_Guide.md`'s maintenance rule for the resolve-in-place
convention.

---

## Maintenance rule

Update this file's phase statuses as work actually begins/finishes. If a new cross-cutting concern
surfaces during actual extraction/research work (the way OCR-handling and platform-reliability did
during scaffolding), add it here rather than letting it stay implicit tribal knowledge.
