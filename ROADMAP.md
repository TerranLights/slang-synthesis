# Roadmap

**Purpose.** The reference material alone (`source_reference/`) is 70GB+ across 40+ languages —
not a "do it all at once" task. This roadmap sequences the work into phases and flags concerns
that only become obvious partway in, so effort goes where it actually pays off instead of grinding
uniformly through everything.

**Status legend:** `not started` · `in progress` · `complete`. Update this file's phase statuses as
work actually begins/finishes — same discipline as the per-language indexes.

**See also `methodology-observations/`** — a running record of findings about the *methodology
itself* (schema gaps, tooling gotchas, open process questions), separate from this file's
phase/task tracking. Check it before starting work on a phase that already has entries.

**See also `LANGUAGE_INDEX.md`** — the master roster of every language this project covers or will
cover, organized by language family, with the highest-priority languages (the 43 nations
represented in the Inner Tepenia GDD sci-fi setting's own Gini-adjusted census) flagged. Use it
alongside Phase 0.5 below to decide which language to work on next.

---

## Phase 0 — Triage pass (not full extraction)

**Status: in progress — Serbian/Croatian/Bosnian (test-run language) done, tentative.** See
`datasets/Serbian_Croatian_Bosnian/00_Book_Triage_Catalog.md` and
`methodology-observations/serbian_croatian_bosnian_test_run.md`. Finding worth flagging here: of 9
real reference files triaged, only 3 had a clean, usable text layer — **roughly 56% needed
OCR/vision-based reading**, a much higher rate than "some of the files" implied below. If this
generalizes, OCR/vision-reading capacity should be budgeted as a default expectation for Phase 1,
not an occasional exception.

Before deep-extracting any single book, survey what's actually in each
`source_reference/languages/<Language>/` folder: which titles look highest-yield (a real grammar >
a phrasebook > an audio-course companion booklet), and — critically — **which are genuine text
layers vs. image-only scans** that will need vision-based reading rather than text extraction (some
of the `.djvu` files especially are likely to be scans; the Inner Tepenia GDD repo hit this with an
image-only PDF that had to be read visually).

**Also actively check for corpus-type material hiding among the grammar references — don't assume a
"reference" folder contains only Phase 1 material.** Confirmed during the Hungarian test run: a
Hungarian slang dictionary (`Magyar Szlengszótár.pdf`) was found sitting directly in
`source_reference/languages/Hungarian/`, not in `language_corpus/`. The Phase 1 (`source_reference/`)
vs. Phase 2 (`language_corpus/`) distinction is about *content type* (grammar/vocab reference vs.
slang corpus), not strictly about which folder a file physically sits in — a title containing words
like "slang," "colloquial," "argot," or the local-language equivalent is worth flagging during
triage even though it lives among grammar books, since its eventual extraction belongs conceptually
in `language_corpus/<Language>/`. Don't rely on this being a repeatable stroke of luck — it may not
recur for most languages, but the triage pass should still look for it every time.

**Output:** a `Book_TOC_Master_Reference.md`-style catalog per language — what exists, format,
scan-vs-text-layer status, and a rough priority call — *before* any checklist work in
`datasets/<Language>/` or `language_corpus/<Language>/` begins. This is cheap and prevents burning
hours deep-extracting a book that turns out low-value.

## Phase 0.5 — Language priority tiering

**Status: partially resolved as of 2026-09-09 — see `LANGUAGE_INDEX.md`.** The real-world
language → in-universe-relevance mapping this phase needed now exists in usable form: the Inner
Tepenia GDD repo's own worldbuilding census (`Upper_Earth_Immigration_Composition.md`'s
Gini-adjusted effective-population table) names 43 real-world nations that actually populate the
sci-fi setting's Antarctic exile cities. `LANGUAGE_INDEX.md` maps those 43 nations to ~18 distinct
languages (several nations sharing a language, e.g. English/Spanish) and flags them 🔴 HIGH
PRIORITY across the full language roster — this is Tier 1 in all but name.

**Not fully resolved:** the GINI census gives population *weight*, not fine-grained per-city or
per-faction narrative relevance beyond "these are the real nations represented" — and 14 of the 43
nations' primary languages have no `source_reference/` material yet (see `LANGUAGE_INDEX.md`'s gap
list), so acquisition is still a prerequisite for those before Phase 1 can start on them. Tiering
*within* the 43 (which of them matters most *first*) and tiering the ~40 remaining non-GINI
languages both remain open — do incrementally (tier the next language right before starting it)
rather than all up front.

## Phase 1 — Reference extraction (grammar/vocab)

**Status: Phase 1 complete for Serbian/Croatian/Bosnian — the first language in the entire
40+-language project to reach this milestone.** All 9 real reference documents have been fully
extracted: 115 `established/` files, ~850,000 words, covering the flagship BCS textbook, its
sociolinguistic-commentary and grammar companion volumes, Hammond's essential grammar, Magner's
full 30-lesson course, both Hawkesworth "Colloquial" volumes, the Serbian Folk Tales anthology, and
Norris & Ribnikar's Teach Yourself Serbian — see `datasets/Serbian_Croatian_Bosnian/established/`,
`00_Extraction_Checklist.md`, and the methodology-observations log for full detail. The `/graphify`
knowledge graph over the full corpus stands at 453 nodes / 561 edges / 29 communities with zero
dangling or missing edges. **The two open questions below, raised early in this pass, are now
effectively answered by the completed run: exhaustive per-book extraction plus subagent-parallelized
dispatch (with wave-based chunking under the 20-concurrent-agent cap) proved tractable across an
entire language's reference corpus, not just a single lesson.**

**Hungarian reached the same milestone next — the second language in the project to complete
Phase 1.** Its reference folder was an order of magnitude larger and messier than SCB's (131 files/
2.6GB with two grab-bag subfolders mixing real reference material into travel guides, fiction, and
comics), so a full triage-and-dedup pass was run first (see `datasets/Hungarian/
00_Book_Triage_Catalog.md`) before extraction proceeded in three priority waves. Result: 53
`established/` files, ~475,000 words, covering 16 real reference sources including two proverb/
idiom dictionaries, the two-volume FSI Basic Hungarian course, a 19th-century grammar (attested-era
contrast against the modern one), an 1,324-page compiled coursebook (handled via representative
sampling, the same discipline used on oversized dictionaries), and the dedicated Hungarian slang
dictionary (*Magyar Szlengszótár*, fully sampled A-Z and routed to `language_corpus/Hungarian/`
rather than `established/`, per the Phase 1/Phase 2 content-type boundary this language's earlier
triage pass first surfaced). The `/graphify` graph over the full corpus stands at 229 nodes / 332
edges / 10 communities with zero dangling/missing edges. **This run reconfirmed the exhaustive-
extraction-plus-subagent-dispatch approach at a genuinely messier, larger scale than SCB, and
surfaced a new gotcha: an extraction subagent independently running `graphify update` from the
wrong working directory can corrupt the repo-root graph — now an explicit prohibition in
`datasets/00_Reference_Extraction_Spec.md`.**

1. **Exhaustive vs. representative extraction per book/language.** Manually extracting even 20
   well-sourced entries from ~2 pages of a 531-page book took a substantial single pass — exhaustive
   coverage of every book, for every language, at this granularity does not appear tractable in
   reasonable time. Whether Phase 1 should aim for full coverage or deliberately-sampled
   representative coverage per book is an open decision.
2. **Manual vs. subagent-parallelized extraction.** Whether extraction work should be dispatched to
   parallel subagents (the way `/graphify`'s own semantic-extraction step does) rather than done as
   one continuous manual read-through — this could materially change the tractability math for
   question 1.

**These two questions directly bear on the "all reference extraction must complete, for every
language, before any web research begins" sequencing rule** — that rule's practicality depends on
how expensive exhaustive Phase 1 extraction actually turns out to be. Not resolved yet; the
sequencing-rule decision itself also remains explicitly deferred (see conversation history).

**Prove the pipeline on one or two flagship languages first — do not fan out to many languages in
parallel before the schema/shard/OCR approach is actually validated end-to-end.** Catching a
schema problem, a bad shard-size assumption, or an OCR/scan-handling gap on language #1 is cheap;
catching it after 15 languages are already partway through is not. *(Confirmed valuable by the test
run — see the index-prerequisite-rule and OCR-prevalence findings, both caught during Phase 0/1 on
just one language.)*

**OCR/scan handling is its own concern**, not a detail to improvise per-book. Flag in the Phase 0
catalog which books need vision-based reading vs. have a usable text layer — this changes
extraction cost per book substantially and should inform Phase 0.5 prioritization too (a
Tier-1 language whose best source is a 400-page image-only scan is a different effort estimate
than one with clean text-layer PDFs). **Add a third category, found during the test run: a text
layer can be *present but garbled* (bad OCR baked into the PDF itself) — functionally equivalent to
no text layer, but easy to miss if a triage pass only checks "text layer exists: yes/no."** A fourth
category found during the Dutch test run: a text layer can be *clean and fully usable but carry a
cosmetic artifact* (e.g. page-margin ruler/registration-mark noise prepended to extracted text) —
distinguishable from garbled OCR by checking that real, clean body text follows immediately after;
tell extraction subagents to simply ignore such noise rather than treating the file as unusable.

**Copyright discipline.** Reference material is copyrighted grammars/dictionaries. Extraction
stays in the same mode already modeled by the Inner Tepenia GDD repo's book extractions: selective
quotes + paraphrase + analysis connecting real material to project needs — never bulk reproduction
of a book's content into this repo.

**Prioritize register/colloquial-focused chapters, not just sequential coverage.** Confirmed during
the Dutch test run: grammar-reference extraction otherwise skews almost entirely to `core` usage
tier (teaching grammars are definitionally basic vocabulary) — but a book's own "colloquial speech,"
"informal register," or sociolinguistic-commentary chapters reliably surface real `Usage Tier`
diversity (`colloquial`, `formal`, etc.) that foundational chapters don't. When triaging a language's
reference material, actively look for and prioritize these chapters/sections over same-length chunks
of purely foundational grammar — they're disproportionately valuable for this project's specific
purposes.

**Budget wave-based dispatch for any full-book/full-language extraction.** Confirmed during the
Serbian/Croatian/Bosnian bridge-scale test (one full 531-page book, 28 extraction chunks): there is a
**hard platform ceiling of 20 concurrent subagents**. A dispatch plan involving more than ~15-18
concurrent chunks gets excess `Agent` calls flatly rejected, not queued — plan waves (with headroom
below 20) up front rather than discovering the cap mid-run. See
`datasets/00_Reference_Extraction_Spec.md`'s "Dispatch scale and concurrency limits" section for the
full guidance, including the check-first duplicate-prevention instruction this makes necessary and
the serialized-checklist-update rule for parallelism above n=3.

## Phase 2 — Web scraping (general, frequency-tagged)

**Status: not started.** Renumbered 2026-09-09 — this used to be bundled with slang-corpus curation
as a single "Phase 2." It is now split into two phases because the two jobs are genuinely different
in kind: this phase is broad, general-usage web collection (not filtered to slang up front), and
Phase 3 is the curation/filtering pass that turns raw scrape into an actual slang corpus.

**What this phase collects:** vocabulary and phrasing scraped from the web for a given language,
tagged by **frequency of use** as it's collected — not just "does this term exist" but "how often
does it actually show up" across whatever sources get scraped. This frequency signal is what lets
Phase 3 later distinguish load-bearing slang from a one-off nonce usage, and lets Phase 4's
mechanics analysis weight findings by real-world productivity rather than treating every entry as
equally significant.

**Mandatory: keep a scrape log per language/source, so nothing gets scraped and counted twice.**
Every scraping pass must record what was already pulled (source, date, URL/identifier, and enough
of a fingerprint to detect the same content resurfacing under a different URL) before scraping
further — re-scraping the same forum thread or subtitle file a second time and double-counting its
frequency contribution would silently corrupt the frequency data this whole phase exists to
produce. Exact schema (a manifest file per language, a hash-based dedup index, etc.) is not yet
decided — treat "some durable, checked-before-every-scrape log" as the hard requirement, the
specific format as an open implementation choice.

Web-scraping mechanics are their own concern, separate from the linguistic content itself: rate
limits, ToS respect, and — critically — **which platforms are actually worth the time varies by
language and region** and is itself worth researching before committing hours per language (this
is exactly what `language_corpus/00_Source_Reliability_Guide.md`'s platform reliability registry
exists to accumulate for subtitle/transcript sources specifically; the same "which platforms are
actually good for this language" question applies more broadly to general web sources too).

Subtitle/transcript mining (a rich source, with real risk — see the reliability guide) sits inside
this phase, not as a separate one.

**Not yet built:** the folder/schema this phase's raw output actually lives in. `language_corpus/`
already exists but is now Phase 3's curated-corpus folder, not this phase's raw-scrape staging
area — a separate location or a clearly-separated subdirectory is needed before real scraping work
starts, so raw frequency-tagged scrape data and curated slang entries don't get mixed in the same
files.

## Phase 3 — Slang corpus (curation)

**Status: not started.** See `language_corpus/00_Corpus_Collection_Index.md` for live status. This
is where `language_corpus/<Language>/` as it already exists in this repo belongs — the curated,
sourced, tiered slang corpus, filtered and organized out of Phase 2's raw frequency-tagged scrape
(once Phase 2 exists) plus any slang-dictionary-type material already found sitting in
`source_reference/` during Phase 0/1 triage (e.g. Hungarian's *Magyar Szlengszótár*, Kövecses
2009 — extracted directly since it was a real, physically-present book, ahead of Phase 2 existing).

Frequency-of-use data carried over from Phase 2 (once that phase exists) should inform each
corpus entry's `Weight/Frequency` field with real signal, not a guess.

## Phase 4 — Mechanics analysis

**Status: not started.** See `datasets/00_Analysis_Index.md` for live status. Gated per-language on
that language's Phase 3 corpus being at least `in progress`.

## Phase 5 — Cross-language comparative pass

**Status: not started — blocked on Phase 4 producing real data for 2+ languages.**

Once a handful of languages have real `analysis/` data, look across them: which `slang_type`s (see
`datasets/00_Usage_Tier_Taxonomy.md`) recur across languages vs. stay language-specific, which
usage-tier subcategories show up repeatedly and deserve promotion to the shared taxonomy, and
whether any genuinely universal slang-formation patterns emerge vs. patterns that are artifacts of
one language/culture. This is where the taxonomy's "promote once 2+ languages show it" rule
actually gets exercised for real, rather than staying theoretical.

## Phase 6 — Synthesis

**Status: not started.** Already schema-scaffolded (`datasets/<Language>/synthesized/`). Feeds the
actual sci-fi conlang/culture work, which likely lives partly outside this repo in wherever the
fictional cultures themselves are defined (cross-reference once that connection point is decided).

## Cross-cutting: QA / spot-check cadence

**Not a one-time step — an ongoing discipline once Phase 3+ produces real entries.** Periodically
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
