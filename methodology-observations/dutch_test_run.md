# Test Run: Dutch — Methodology Observations

**Status: tentative throughout.** The pipeline's third test-run language, chosen to add a third
typological data point — Dutch is predominantly analytic/mildly fusional (West Germanic, closer to
English), distinct from Serbian/Croatian/Bosnian's fusional case system and Hungarian's
agglutinative case-stacking — and to specifically test whether a grammar reference's own
"colloquial register" content can surface `Usage Tier` diversity beyond `core`, a gap both prior
runs flagged but neither tested directly.

See `../datasets/Dutch/00_Book_Triage_Catalog.md` for the source-material survey.

---

## Log

Entries added chronologically as the test run progresses.

---

### 2026-08-30 — Phase 0 triage: a new, cosmetic-only text-layer failure mode found

Triaged the grammar-reference cluster of `Dutch (Nederlands) Language Learning Pack/` (84 files, not
exhaustively triaged — same deliberate scoping as the Hungarian run). Found a **fourth text-layer
category**, distinct from the three already known (clean / none / garbled-OCR): two Routledge
grammar volumes (`25 Dutch An Essential Grammar.pdf`, `27 Dutch A Comprehensive Grammar.pdf`) have a
**real, clean, fully usable text layer with a cosmetic artifact prepended to every page** — a long
run of stray digits (`1111\n2\n3\n4\n5\n6\n7\n8\n9\n1011...`) that turned out to be page-margin
ruler/registration-mark noise from the book's own print layout, not corrupted OCR. Distinguished
this from the earlier "garbled OCR" case (`Teach Yourself Serbian.pdf`) by checking further into the
page — the real body text immediately follows and is clean. **Told dispatched subagents to simply
ignore the numeric prefix; this worked without issue** in two of three chunks. Interestingly, the
third subagent (Chapter 22) reported the artifact **did not appear at all** in its assigned page
range — suggesting it's inconsistent even within one book, possibly tied to specific page layouts
(chapter-opener pages vs. body pages) rather than a blanket per-page issue. Worth updating the
triage taxonomy to five categories: clean / none / garbled-OCR / clean-with-cosmetic-artifact /
(implicitly) inconsistent-within-book.

---

### 2026-08-30 — Chosen deliberately to test the "colloquial chapter" hypothesis — confirmed

Both prior test runs flagged the same gap: grammar-reference extraction skews almost entirely to
`Usage Tier: core`, since teaching grammars are definitionally basic/standard vocabulary, and true
tier diversity was expected to only emerge from Phase 2 (web research). This run tested that
directly by deliberately choosing a chapter titled "Colloquial speech and writing" (Ch. 16) and a
chapter about diminutives (Ch. 22, where affective/attitude-marking usage was hypothesized to skew
non-core) as two of the three chunks, alongside a foundational chunk (Ch. 1-3) as a control.

**Result: confirmed, clearly.** Ch. 1-3 (control): ~190 entries, all `core` except one
(`engerd` "creep," tagged `colloquial` on lexical-meaning grounds). Ch. 16: **roughly two-thirds of
~34 entries landed on `colloquial` or `formal`** — and this is the first file in the entire project
to use `formal` at all. Ch. 22: a meaningful subset of diminutive examples tagged `colloquial` where
the source itself explicitly frames them as affective/attitude-marking (e.g. `zon→zonnetje`,
`taal→taaltje`) versus `core` for the plain form-class and lexicalized-drift diminutives
(`dubbel→dubbeltje` "10-cent coin").

**This resolves the open gap from both prior runs**: usage-tier diversity is *not* exclusively a
Phase 2 phenomenon — a grammar reference's own register-focused or sociolinguistic-commentary
chapters can and do surface it, **if such chapters are deliberately sought out and prioritized**
rather than extracted in strict page order. Worth promoting this into `ROADMAP.md` Phase 1 guidance:
when triaging a language's reference material, actively look for and prioritize chapters/sections
with titles like "colloquial," "informal," "register," "spoken vs. written," or similar — they are
disproportionately valuable for this project's specific purposes compared to a same-length chunk of
purely foundational grammar.

---

### 2026-08-30 — Parallel subagents safely handled a shared-file race condition, unprompted

All three subagents were instructed to update the same shared file
(`datasets/Dutch/00_Extraction_Checklist.md`) as part of their own task — a genuine concurrent-write
scenario, since they ran in parallel. **Two of the three subagents explicitly detected that the
checklist had already been modified by a sibling subagent between their own Read and Edit, and
re-read the current file before applying their edit rather than blindly overwriting** — both said so
explicitly in their completion reports. No content was lost; the final checklist correctly reflects
all three chunks' contributions. This was not explicitly instructed (the dispatch prompts said
"update the checklist," not "check for concurrent edits first") — it's an emergent, self-protective
behavior worth relying on rather than treating as luck, though **not a guarantee**: future dispatches
with many more parallel subagents writing to the same shared file should still be watched for
this, and if a real collision is ever found, the checklist-update instruction may need to be
serialized (e.g. done in a single follow-up pass rather than by every subagent independently) rather
than assumed always-safe at higher parallelism.

---

### 2026-08-30 — A refined judgment call: phonetic/allophonic variation is not `Attested Region`

The Chapters 1-3 subagent encountered Dutch consonant pronunciation that varies by region
(Netherlands vs. Flanders realizations of g/v/w/r) and correctly did **not** tag these as
`Attested Region`/`Geographic Scope` — instead documenting the variation in the `Notes` column, with
an explicit rationale: this is *phonetic/allophonic realization variance* on words that are
otherwise nationally current and identical in spelling/meaning, not the kind of source-marked
*lexical* regionality the `Attested Region` column was designed for (the B/C/S `[B]`/`[C]`/`[S]`
tags on genuinely different words/forms being the canonical case). **This is a real, useful
refinement of the column's scope** that wasn't explicit in the guide before: `Attested Region` is
for regionally-restricted *forms/lexemes*, not for *pronunciation* variation of an otherwise
single, shared form. Worth adding this distinction explicitly to
`00_Historical_and_Geographic_Context_Guide.md` so future dispatches don't have to independently
re-derive it.

---

### 2026-08-30 — Graphify run: found a real cross-chapter linguistic pattern unprompted

Ran `/graphify datasets/Dutch` (39 nodes, 61 edges, 5 communities, clean health). Applied the same
"don't create one node per vocabulary row" instruction confirmed necessary during the Hungarian run
— worked again, producing a small, navigable graph. This run's own dispatch specifically asked the
semantic-extraction subagent to watch for cross-chapter register patterns, and it found two real
hyperedges:

1. **"Colloquial/Register Marking Recurs Across the Particles and Diminutives Chapters"** — directly
   confirms this run's central finding (Ch. 16 and Ch. 22 both independently surfaced non-`core`
   Usage Tier data) as a structural graph pattern, not just a coincidence noticed by two separate
   subagents.
2. **"Vowel Length Tracks Morphological Form Across Plural and Diminutive Formation"** — genuinely
   new, not something either extraction dispatch was told to look for: Dutch's closed/open-syllable
   spelling logic (Ch. 1-3), the irregular vowel-lengthening plural pattern (Ch. 1-3), and the
   diminutive vowel-length-alternation rule (Ch. 22) are three separately-extracted grammar points
   that turn out to be expressions of the same underlying phonological principle. This is exactly
   the kind of cross-cutting discovery the graphify-as-organized-summary-layer design was meant to
   surface, and it took finding it *automatically*, across content two different subagents extracted
   independently, to make it visible — neither extraction subagent could have noticed this alone.

**This is the strongest evidence yet that the storage-model redesign (Markdown content +
graphify-as-summary-layer) delivers real analytical value**, not just organizational tidiness — a
genuine, previously-undocumented linguistic connection emerged from the pipeline's own structure.

---

## Summary verdict for this test run

**Confirms the Hungarian run's positive verdict and adds a major new finding of its own.**
Subagent-parallelized, spec-driven extraction continues to work reliably (including handling a
genuine concurrent-write race condition on a shared file without being told to). The deliberate
choice to target register-specific chapters, rather than sequential coverage, **directly resolved
the "usage-tier diversity is missing from Phase 1" gap** both prior runs had flagged — this is now a
confirmed, actionable finding promoted into `ROADMAP.md` Phase 1 guidance. A fourth text-layer
failure category was found (clean-but-cosmetically-noisy) and handled without issue. A useful
column-scope refinement (`Attested Region` vs. phonetic variation) was captured into the shared
guide. And graphify surfaced a genuine cross-chapter linguistic discovery neither individual
extraction dispatch could have found alone. Everything above remains tentative pending developer
review, per the standing rule for test-run output.
