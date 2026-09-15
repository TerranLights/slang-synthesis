# Test Run: Spanish — Methodology Observations

**Status: tentative** (per the standing policy in `00_Index.md` — not yet reviewed/confirmed).

**Context.** Spanish is the fifth language to reach full Phase 1 completion, after Serbian/
Croatian/Bosnian, Hungarian, Korean, and Russian, and the first to cover one of the 5 GINI-
represented Spanish-speaking nations (Spain, Mexico, Argentina, Chile, Uruguay — no dominance
hierarchy among them). This run followed immediately after Russian's much larger push, and serves
as a useful contrast point: a small, clean corpus completed in a single continuous session rather
than spanning multiple usage-limit resets.

---

## Log

### 2026-09-14 — Full triage: the smallest, cleanest corpus yet

`source_reference/languages/Spanish/` held 189MB (133 PDF files + 1 EPUB) — by a wide margin the
smallest and cleanest corpus this project has triaged, and a sharp contrast to Russian's 3.6GB/
~75%-scanned corpus completed the day before. Only 3 of ~15 distinct sources lacked a text layer.
Scope filtering excluded a misfiled Japanese grammar book sitting in the Spanish folder, two
torrent-site junk files, an empty audio-only course folder (Michel Thomas — Spanish, presumably
audio that was never present or already removed), and duplicate-format copies of the same book
(Madrigal's Magic Key existed as two byte-identical PDFs plus an EPUB).

**`Learning.Spanish.Like.Crazy.All.3.Levels/` turned out to be the flagship register source** — a
structured beginner-to-advanced course with *built-in* slang and insult lessons as part of its own
curriculum (`Insultos_01.pdf`, `insultosvulgares.pdf` in Level I; two dedicated Bonus Slang Lessons
in Level II). This is the first time a course's own creators, rather than a separate dedicated
slang dictionary, built explicit vulgar/slang content into the main curriculum — a genuinely
different sourcing pattern from Hungarian's *Magyar Szlengszótár* or Russian's *Dermo!*, both of
which were separate specialist dictionaries.

### 2026-09-14 — Wave 1 & 2: both waves closed in a single session

Given the corpus's small size, both waves were dispatched and completed within a few hours rather
than the multi-day pushes Russian and Korean required. 12 Wave 1 subagents and 4 Wave 2 subagents
(3 vision-read sources plus one continuation) ran with zero usage-limit disruptions — the first
Phase 1 push in this project's history to complete without a single session/weekly-limit event
interrupting a dispatch. This is likely a function of corpus size (a ~350,000-word total corpus is
roughly a quarter of Russian's Wave 1 alone) rather than anything methodologically different.

**A genuine "is this a duplicate?" question resolved the opposite way expected.** Level III of
Learning Spanish Like Crazy has two overlapping-numbered lesson series (`Leccion##-final.pdf` and
`Spanish_Lesson_##.pdf`, both spanning lessons 61+). The dispatch instructed the subagent to check
for duplication before assuming either redundancy or full extraction was warranted — spot-checking
found the two series cover the **same lesson numbers with entirely different dialogue content and
grammar sequencing** (e.g. Lección 61 in one series covers future-perfect via a First Communion
dialogue; the same-numbered lesson in the other series covers conditional-perfect via a
quinceañera-party dialogue). Both series were extracted in full. This is a useful counter-example to
the "two files with overlapping numbering are probably the same content" assumption that held for
Korean's and Hungarian's actual duplicate-edition cases — the check-first discipline correctly
avoided both over-assuming redundancy and under-covering genuinely distinct content.

**A real content gap surfaced and got filled through convergent, independent discovery.** No Wave 1
source gave more than passing treatment to the Spanish subjunctive mood — arguably one of the
language's most structurally important features. Both Wave 2 vision-read sources (*Practice Makes
Perfect Complete Spanish Grammar* and *Easy Spanish Step-by-Step*) independently flagged this same
gap and filled it in detail, and the *Learning Spanish Like Crazy* Level III course was
independently found (during the graphify rebuild) to also teach the imperfect subjunctive at
length. Three unrelated pedagogical lineages treating the same feature as load-bearing is a strong
structural signal, not a coincidence of author overlap — and it was caught specifically because the
non-redundant-supplement pattern requires each new source to be checked against what's already
extracted, which surfaces gaps as a side effect of checking for overlap.

### 2026-09-14 — Graphify rebuild: clean on the first pass

The 61-file corpus (~350,000 words) was split into 3 semantic-extraction chunks. Result: 132 nodes,
156 edges, 31 communities, zero dangling/missing/collapsed edges — clean on the very first health
check, unlike Russian's rebuild (which caught one fabricated edge). Given the much smaller chunk
count (3 vs. Russian's 13), fewer chunks means fewer opportunities for a subagent to reference a
plausible-but-nonexistent cross-chunk node ID — worth noting as a plausible (not yet proven)
explanation for why smaller corpora may see cleaner first-pass health checks than very large ones.

---

## Summary verdict for this test run

The full pipeline completed end-to-end in a single continuous push with zero usage-limit
disruptions, confirming that the run-length and disruption patterns seen in Russian's push were a
function of corpus size and OCR-burden, not an inherent property of the methodology. The
check-first duplicate-detection discipline correctly identified a case where apparent duplication
(same lesson numbers, two file series) was actually two genuinely distinct sets of lesson content —
a useful counter-example showing the check-first pattern cuts both ways (catching real duplicates
in Korean/Hungarian, correctly rejecting a false duplicate hypothesis here). The independent,
convergent discovery of a major grammar-feature gap (the subjunctive mood) across three unrelated
sources during ordinary non-redundant-supplement checking demonstrates that gap-checking has real
analytical value beyond just avoiding wasted extraction effort.
