# Test Run: Hungarian — Methodology Observations

**Status: tentative throughout.** The pipeline's second test-run language, chosen specifically to
apply the refined methodology from the Serbian/Croatian/Bosnian run (Markdown-first storage,
subagent-parallelized comprehensive-but-not-exhaustive extraction, the new morphological typology
guide) and see whether results actually improve, per the developer's own framing. Every finding
below is provisional until reviewed.

**Why this language, and what it's specifically testing:**
- Hungarian is **agglutinative** — the first test-run language to actually exercise the
  morpheme-breakdown convention and the "different typology than Serbian/Croatian/Bosnian's
  fusional case" comparison point flagged in `datasets/00_Word_Concept_and_Morphological_Typology_Guide.md`.
- First real test of `datasets/00_Reference_Extraction_Spec.md`'s subagent-parallelized method — the
  first test run's shard was produced manually, before that spec existed.
- First real test of the Markdown-first storage model producing genuinely new content (rather than
  a JSON→Markdown conversion of already-extracted material).

See `../datasets/Hungarian/00_Book_Triage_Catalog.md` for the source-material survey.

---

## Log

Entries added chronologically as the test run progresses.

---

### 2026-08-30 — Phase 0 triage, scaled deliberately

Hungarian's reference folder is **131 files, 2.6GB** — an order of magnitude larger than Serbian/
Croatian/Bosnian's 9 files. Rather than triaging all 131 files by hand (which the first test run's
own findings already flagged as not tractable at that granularity), triage was explicitly scoped to
the 35 top-level loose files, with the 6 audio-course-shaped subfolders deliberately deferred and
flagged rather than skipped silently. **This is itself a confirmation of the first test run's
finding** — the "comprehensive-but-not-exhaustive" principle had to be applied to *triage itself*,
not just extraction, once corpus size grew by 10x.

**Unanticipated discovery: a slang dictionary (`Magyar Szlengszótár.pdf`) sitting directly in
`source_reference/`.** The pipeline's phase model assumed `source_reference/` = grammar/vocabulary
reference (Phase 1) and `language_corpus/` = web-research-collected slang (Phase 2), as two cleanly
separated content types by folder. This book breaks that assumption — real slang content physically
located in the "reference" folder. Resolved for now by treating the phase distinction as being
about *content type*, not *which folder something sits in*: this book's eventual extraction belongs
conceptually in `language_corpus/Hungarian/`, even though it's read from `source_reference/`. See
`datasets/Hungarian/00_Book_Triage_Catalog.md`'s scope note. **Worth checking whether other
languages' reference folders hide similar corpus-type material** — this may not be a one-off.

**OCR/scan rate held steady at a comparable level to the first test run:** 4 of 8 individually-
checked top-level files (50%) had no usable text layer, close to Serbian/Croatian/Bosnian's ~56%.
Two data points now agree closely enough that this looks like a genuine, generalizable rate rather
than a fluke of one small corpus — worth treating as a standing planning assumption for the
remaining ~38 languages.

---

### 2026-08-30 — First real test of subagent-parallelized extraction: markedly better than the manual pass

Three subagents dispatched in parallel (Chapters 1-3, Chapter 5, Chapter 6 of Rounds' *Hungarian:
An Essential Grammar*, 2nd ed.), each given `datasets/00_Reference_Extraction_Spec.md` plus the
typology guide, following the developer's own framing that results might turn out better this time.
**They did.** Concrete comparison against the Serbian/Croatian/Bosnian manual pass:

| | SCB (manual, pre-spec) | Hungarian (subagent, per-spec) |
|---|---|---|
| Entries per pass | 20 (one lesson, ~2 pages) | ~65 / ~93 / ~115 across three chunks (~40 pages total) |
| Time/effort per entry | High — single-threaded manual reading | Three chunks ran concurrently; total wall-clock roughly one chunk's worth |
| Consistency | N/A (only one pass to compare) | All three subagents independently produced identical table structure, column conventions, and citation style without cross-communication — the shared spec did its job |
| Coverage-rule judgment calls | Not exercised (too small a sample) | Chapter 6's subagent correctly recognized its 28-page/23-case chunk needed a *representative* vocabulary sample rather than exhaustive cataloguing, and said so explicitly in its own coverage note rather than silently under- or over-delivering |
| Morpheme breakdowns | None needed (fusional language, none produced) | Real, well-formed breakdowns in all three files, including a genuine triple-morpheme-stack example (`gyerekeire` = stem + possessive linker + possessive-plural + sublative case) — the morphological typology guide's design validated against real agglutinative data for the first time |
| Checklist maintenance | Done manually afterward | Two of three subagents updated `00_Extraction_Checklist.md` themselves (Output files table, progress checkboxes) without being explicitly asked to in every dispatch — an emergent behavior worth relying on deliberately in future dispatch prompts rather than treating as incidental |

**This directly answers the developer's own framing question ("results might actually turn out
better"): yes, substantially.** The combination of a written spec + parallel dispatch + Markdown
output produced roughly 4-5x the content, in comparable or less wall-clock time, with better
internal consistency and honest self-reported coverage decisions, than the first test run's manual
approach.

**One process refinement worth carrying forward:** explicitly instruct every dispatch to update the
checklist's Output files table and progress checkboxes as part of its own task, rather than relying
on it happening incidentally (two of three did, one explicitly didn't and said so) — this removes a
manual coordination step entirely if made a standing instruction in the extraction spec itself.

---

### 2026-08-30 — Graphify run on real per-language content (first time, not just repo scaffolding)

Ran `/graphify datasets/Hungarian` — the first time this project's graphify integration has been
pointed at actual extracted-language content rather than the repo's own methodology docs. ~23,300
words across 5 files, well within normal size thresholds.

**Result: strong validation of the whole Markdown-first storage redesign.** 31 nodes, 56 edges, 6
communities, clean health (no dangling/missing/collapsed edges). One instruction to the semantic-
extraction subagent proved important: told explicitly *not* to create one node per vocabulary table
row (which would have produced 200+ near-duplicate nodes across the three files) and instead extract
grammar concepts/mechanisms plus a handful of illustrative examples — this produced a genuinely
useful, navigable graph rather than a vocabulary-table dump. **Worth adding this instruction to
`00_Reference_Extraction_Spec.md` or a graphify-specific note, since every future language's
`established/` content will have the same shape** (large vocabulary tables) and would hit the same
problem without it.

The **hyperedges are the clearest win**: graphify automatically surfaced "vowel harmony as a
cross-chapter governing mechanism," "agglutinative suffix-stacking demonstrated across all three
chapters," and "the Hungarian consonant-assimilation family" — cross-cutting patterns spanning all
three extraction files, discovered without any hand-authored index or manifest. This is exactly the
"organized summary... including numerical data... and addresses pointing to where the full corpus
is located" the developer asked the JSON layer to provide, produced here with zero bespoke JSON
authored by hand — confirms the storage-model decision from the first test run was correct in
practice, not just in theory.

The graph also correctly identified `Magyar Szlengszótár` (the slang dictionary) as a distinct
entity node cited from the triage catalog, preserving the Phase 1/Phase 2 boundary flag rather than
losing it in the graph.

---

---

### 2026-08-30 — Real bug: per-language graphify manifest save wrote to the wrong location

While finalizing the Hungarian graphify run, `graphify.detect.save_manifest(root='datasets/Hungarian', ...)` **wrote to the repo-root `graphify-out/manifest.json` instead of `datasets/Hungarian/graphify-out/manifest.json`**, because `save_manifest` resolves its output path relative to the *current working directory*, not the `root=` argument — and this session's Bash commands were run from the repo root throughout (for convenience, matching how every other step in this run used explicit `datasets/Hungarian/...` paths). This **overwrote and corrupted the repo-root manifest** (wiped its tracked entries for `.claude/settings.json`, `CLAUDE.md`, `README.md`, etc., replacing them with Hungarian's own file list) and left `datasets/Hungarian/graphify-out/manifest.json` missing entirely.

**Caught via `git status`/`git diff` before committing** — the corrupted root manifest showed as a large unexpected diff. Fixed by `git checkout -- graphify-out/manifest.json` (restoring the tracked good state) and re-running the manifest save with the working directory actually `cd`'d into `datasets/Hungarian/` first, matching what the `/graphify` skill's own instructions assume for a per-language run (its own Step 9 block explicitly notes `PROJECT_ROOT=$(pwd)` is meant to be the language folder, not fixed to the repo root).

**Lesson for every future per-language graphify run**: **`cd` into the language's own folder before running any step that calls `save_manifest`** (or more generally, don't assume passing `root=` as an argument is sufficient — some graphify internals key off CWD directly, not the passed argument). Always `git status`/`git diff` the repo-root `graphify-out/` after any per-language graphify run, specifically checking for accidental cross-contamination, before committing.

## Summary verdict for this test run

**Yes — results turned out better, on every axis checked.** More content per unit of effort
(subagent parallelization), a schema feature validated for the first time on real data (morpheme
breakdowns), a working organized-summary layer produced with no manual bookkeeping (graphify on
real content), and a new real-world edge case surfaced and handled sensibly (the slang dictionary in
the reference folder) rather than causing confusion. Everything above remains tentative pending
developer review, per the standing rule for test-run output.
