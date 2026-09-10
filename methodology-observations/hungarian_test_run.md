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

---

### 2026-08-30 — Two findings from this run formalized into official process docs

Following a later audit of what had been *confirmed* across all test runs but never actually
*promoted* into a process doc a future session would read before starting work: (1) the
`save_manifest()` CWD bug now has a standing warning in `00_Reference_Extraction_Spec.md`,
`_TEMPLATE/00_Extraction_Checklist.md`'s Graphify section, and this language's own checklist — not
just this historical log entry; (2) the "check for corpus-type material hiding in a reference
folder" principle (the slang-dictionary discovery) is now a standing Phase 0 triage instruction in
`ROADMAP.md`, not just a one-off note in this language's own triage catalog.

---

### 2026-09-09 — Full Phase 1 push: complete triage, three extraction waves, graphify rebuild

**This entry covers the entire push that brought Hungarian to full Phase 1 completion** — the
second language in the project to reach this milestone, following the methodology validated
end-to-end on Serbian/Croatian/Bosnian. Final scale: 53 `established/` files (~475,000 words, up
from the 3-file/~273-entry test-run start), plus 4 files in `language_corpus/Hungarian/` for the
slang dictionary. `graphify-out/` rebuilt clean over the full corpus: 229 nodes, 332 edges, 10
communities, zero dangling/missing/collapsed edges (`language_corpus/Hungarian/` got its own
separate graph: 60 nodes, 109 edges, 8 communities, also clean).

**A full triage pass came first, and it had to handle a genuinely messier corpus than SCB's.**
Hungarian's `source_reference/` folder is 131 files/2.6GB — an order of magnitude larger than SCB's
9 files — split into 37 top-level loose files and 6 subfolders. Two of those subfolders
(`Hungarian Language Learning Pack (Updated)`, `Hungarian language resources`) turned out to be
large grab-bags mixing a handful of real reference titles among travel guides, comics (Donald
Duck), genre fiction (an R.A. Salvatore fantasy trilogy in Hungarian translation, the Twilight
saga), folk tales in *Ukrainian* (not Hungarian), and children's picture books — none of that
non-reference material was extracted, and the dedup-and-filter pass to separate real titles from
noise is now itself a reusable technique (documented in `datasets/Hungarian/
00_Book_Triage_Catalog.md`) for any other language's messy subfolders. ~50% of individually-sampled
files had no usable text layer, consistent with both prior test runs' rates — this is now
unambiguously the norm across languages, not a Hungarian-specific quirk.

**Extraction proceeded in three priority waves** (Wave 1: clean-text highest-value — finishing
Rounds' grammar, both proverb dictionaries, the morphology paper, the FSI course; Wave 2: remaining
clean-text supplements — the Phonology reference, the 1,324-page Magyaróra coursebook, the
phrasebook, the 1853 grammar, the diaspora-Hungarian volume; Wave 3: vision-reading — the slang
dictionary, Teach Yourself Hungarian, Colloquial Hungarian, Hungarian in Words and Pictures,
Hungarian with Ease, Hungarian Verbs, Practical Hungarian Grammar). This wave structure, proposed
and approved before dispatch began, made the "should we scope small or go for everything" decision
explicit rather than ad hoc, and meant later triage information (the true 1,324-page size of
Magyaróra, for instance) could be absorbed into the existing plan rather than blowing up scope
unpredictably.

**New gotchas found and promoted into `00_Reference_Extraction_Spec.md`:**

1. **Extraction subagents must never run graphify themselves.** One subagent, tasked only with
   extracting a single book chapter, independently ran `graphify update .` at the end of its own
   turn "per the project's CLAUDE.md convention" — but its actual working directory was the repo
   root, not `datasets/Hungarian/`, so it silently dumped a whole-repo scan into the SCB-scoped
   root graph (a ~52,000-line diff to the root `graphify-out/graph.json`). Caught via `git status`
   before committing and fully reverted; no data was lost, but this is the second confirmed
   incident of the CWD-relative-path bug, this time triggered by a subagent's own initiative rather
   than an orchestrator mistake. **Fix:** every extraction dispatch prompt must now explicitly
   state that graph rebuilds happen separately, after a whole wave lands, not by individual
   per-file subagents.
2. **A book can be genuinely, drastically larger than its triage-time page-count estimate.**
   Magyaróra was catalogued as a coursebook during triage; on actual inspection it turned out to be
   a 1,324-page compiled volume bundling a grammar reference with a large, separately-authored set
   of magyarora.com website worksheets across multiple proficiency levels plus an answer key. Same
   fix as the oversized proverb dictionary earlier in this project: representative sampling across
   early/mid/late ranges, explicitly documented as non-exhaustive, rather than either skipping the
   source or attempting full coverage of an unexpectedly huge book.
3. **Two-printed-pages-per-scan confirmed again, on yet more books** — the slang dictionary and
   Hungarian with Ease both scan two printed pages per PDF image, while Teach Yourself Hungarian and
   Colloquial Hungarian (both vision-read in the same wave) turned out to be flat single-page scans.
   The lesson holds: verify per-book, every time, never assume from one confirmed instance that a
   whole wave shares the same scan convention.
4. **A "completed" subagent status does not guarantee its output file was actually written.**
   Across two separate session-limit interruptions during Wave 3, several subagents reported
   `status: completed` with a result that read as mid-task ("I'll wait for the render-completion
   notification before continuing") rather than a real summary — and in every one of these cases,
   the target file was genuinely missing from disk. **Always verify the output file exists on disk
   before trusting a "completed" status**, not just for `status: failed` notifications.

**Standout content findings, directly relevant to future Phase 3 mechanics analysis:**

- **A whole inflectional class carrying an explicit colloquial/"uneducated" register contrast**
  (the `-ik`-verb 1st-person-singular ending, Teach Yourself Hungarian) — a register split on a
  grammatical *paradigm slot*, not just a lexical item pair, a category of finding this project
  hadn't seen clearly before in any language.
- **A courtesy third address register** (`tetszik`+infinitive, alongside the already-known
  `te`/`maga`/`ön` three-way system) with asymmetric response rules and a gender-conditioned
  exception — Hungarian's politeness system turns out to be at least four-way, not three.
- **A five-step vulgarity ladder on a single question frame** (`ki a fene?/franc?/picsa?/szar?/
  túró?`, the slang dictionary) and a **three-tier "drunk" ladder** (`ittas`/`részeg`/`piás`,
  Magyaróra) — two independent, cleanly graded register scales on different semantic domains.
- **Productive derivational-suffix stacking on verb stems** (potential, causative, and frequentative
  endings each redefining the stem so a further suffix stacks onto the *new* stem — Rounds' grammar,
  Kornai's dissertation) recurring across at least four independently-authored sources (Kornai's
  dissertation, Rounds' grammar, Hungarian Verbs, Hungarian with Ease) as the single most productive
  slang-adjacent morphological mechanism this language's grammar-reference material keeps surfacing.
- **Convergent sound change across unrelated contact situations**: the `gyerek`→`dzserek`
  consonant-affrication pattern is independently attested in Vojvodina Hungarian (Serbian contact),
  Oberwart Hungarian (German contact), and American Hungarian (English contact) — three genuinely
  unrelated language-contact situations converging on the same phonological outcome, a strong
  natural-language precedent for how contact-induced sound change might be modeled in the
  conlang-derivation work later in this project.
- **A single typological-synthesis chapter reframing three "separate" findings as one mechanism**:
  de Groot's Ch.11 in the Fenyvesi volume shows that overt-pronoun preference, possessive-suffix
  loss, and definite/indefinite-conjugation collapse — reported independently in three earlier
  chapters about three different countries — are all instances of one underlying
  Appositional→Free-Pronoun person-marking cycle, accelerated by contact with already-Free-Pronoun
  languages. A model for how this project's own eventual mechanics-analysis phase might unify
  scattered per-source findings into a smaller number of real generative mechanisms.
- **A cross-source register disagreement, left unresolved rather than silently picked one side**:
  Hungarian in Words and Pictures marks `szia` as "very familiar, young people" but gives
  `szervusz(tok)` with no age qualifier; Teach Yourself Hungarian explicitly calls `szervusz`
  "now old-fashioned." Flagged for a future cross-source register-reconciliation pass rather than
  resolved by picking whichever source extracted first — a good example of the project's own
  discipline of recording disagreement as data, not noise.

**Status: Hungarian Phase 1 is complete.** Next steps for this language are Phase 2 (continuing
web-collected slang corpus work, building on the `language_corpus/Hungarian/` slang-dictionary
sample already in place) or Phase 3 (mechanics analysis), not further Phase 1 extraction. Everything
above remains tentative pending developer review, same as every prior entry in this log.
