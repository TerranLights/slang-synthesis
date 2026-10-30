# Ilocano — resume checkpoint

**Started 2026-10-30, live/user-directed work** ("go ahead and do the triage and then run a full
data-extraction on Ilocano"). Triage already complete — see `00_Book_Triage_Catalog.md` (dated
2026-10-26). This is the first-ever Phase 1 extraction for Ilocano; no prior `established/`
content exists.

Source files staged in `source_reference/languages/Ilocano/`:
- **File 1**: "A reference grammar of Ilocano" (Carl Rubino, 1997 UCSB PhD dissertation), 549 PDF
  pages, **no text layer — vision-only**.
- **File 2**: "Ilocano dictionary and grammar Ilocano-English, English-Ilocano" (Carl Rubino, 2000,
  University of Hawaiʻi Press PALI series), 868 PDF pages, **real OCR text layer** (pdftotext
  usable for the dictionary body; vision recommended for the Grammar Outline section since it's
  denser/structurally complex).
- File 3 (duplicate scan of File 2, no text layer) deliberately NOT copied in — redundant.

## Structural reconnaissance (done 2026-10-30)

**File 1 page map** (PDF page = printed Arabic page + 26; front matter is roman-numbered i-xxii at
PDF pp.1-26):
| Printed | PDF | Section |
|---|---|---|
| i-vii | 1-7 | Title, UMI notice, approval, dedication, acknowledgments, CV |
| viii | 11 | Abstract |
| ix-xxii | 12-26 | Full detailed Table of Contents (short + long form) |
| 1 | 27 | Ch.1 Introduction |
| 10 | 36 | Ch.2 Phonology |
| 30 | 56 | Ch.3 Articles, Demonstratives and Case |
| 52 | 78 | Ch.4 Pronouns |
| 73 | 99 | Ch.5 Nouns |
| 121 | 147 | Ch.6 Adjectives |
| 170 | 196 | Ch.7 Numbers |
| 186 | 212 | Ch.8 Verbs (sections 1-3: Focus, affix summary, intransitive affixes) |
| 225 | 251 | Ch.8 §4 Transitive affixes |
| 252 | 278 | Ch.8 §5-16: Detransitivization, pa- causation, Aspect, irregular verbs, nominalizations, plurality |
| 320 | 346 | Ch.9 Adverbs |
| 384 | 410 | Ch.10 Existentials |
| 395 | 421 | Ch.11 Sentence types (Part II: Issues in Syntax begins) |
| 412 | 438 | Ch.12 Imperatives |
| 416 | 442 | Ch.13 Negation |
| 427 | 453 | Ch.14 Interrogativity |
| 444 | 470 | Ch.15 Transitivity and Voice |
| 452 | 478 | Ch.16 Reciprocals |
| 454 | 480 | Ch.17 Reflexives |
| 456 | 482 | Ch.18 Clause combining |
| 498 | 524 | Glossary |
| 511 | 537 | References |
| 513 | 539 | Map Appendix |
| 517 | 543 | Index |
| — | 549 | end of book |

**File 2 page map** (empirically probed via direct `pdftotext` content sampling, not the
badly-OCR-garbled TOC text):
| PDF pp. | Section |
|---|---|
| 1-19 | Front matter (incl. Internet Archive digitization notice ~p.10) |
| ~20-48 | Introduction, Phonology |
| ~48-85 | Grammar Outline proper |
| 88 | Abbreviations Used in This Dictionary |
| ~92-737 | Ilocano-English dictionary (alphabetical, confirmed via samples at a-, p-, s-, t-, w-, y- across the range) |
| ~738-840 | English-Ilocano dictionary (starts with "aloft" at p.740; confirmed via samples through p.800) |
| ~840-868 | Back matter: Traditional Ilocano Songs ("Kankanta Nga Iloko"), cultural appendix, back-cover blurb |

## Wave I1 — full extraction plan (19 files, 001-019)

**File 1 (Reference Grammar, vision-only, FULL coverage — matches the triage's priority ranking
for its deep academic/interlinear-glossing value):**
| # | Scope | PDF pp. |
|---|---|---|
| 001 | Front matter (Abstract, TOC) + Ch.1-2 (Introduction, Phonology) | 1-55 |
| 002 | Ch.3-4 (Articles/Demonstratives/Case, Pronouns) | 56-98 |
| 003 | Ch.5 (Nouns) | 99-146 |
| 004 | Ch.6 (Adjectives) | 147-195 |
| 005 | Ch.7 (Numbers) | 196-211 |
| 006 | Ch.8a (Focus/transitivity, verbal affix summary, intransitive affixes, transitive affixes) | 212-277 |
| 007 | Ch.8b (Detransitivization, pa- causation, Aspect, irregular verbs, nominalizations, plurality) | 278-345 |
| 008 | Ch.9 (Adverbs) | 346-409 |
| 009 | Ch.10-11 (Existentials, Sentence types) | 410-437 |
| 010 | Ch.12-14 (Imperatives, Negation, Interrogativity) | 438-469 |
| 011 | Ch.15-18 (Transitivity and Voice, Reciprocals, Reflexives, Clause combining) | 470-523 |
| 012 | Back matter: Glossary, References, Map Appendix, Index | 524-549 |

**File 2 (Dictionary and Grammar, PALI series):**
| # | Scope | PDF pp. | Method |
|---|---|---|---|
| 013 | Grammar Outline part 1 (Intro, Phonology) | 1-48 | vision (denser/structurally complex front matter) |
| 014 | Grammar Outline part 2 (Grammar Outline proper, Abbreviations key) | 49-91 | vision |
| 015 | Ilocano-English dictionary sample 1 | 92-307 | pdftotext, representative sampling across full sub-range |
| 016 | Ilocano-English dictionary sample 2 | 308-522 | pdftotext, representative sampling |
| 017 | Ilocano-English dictionary sample 3 (also confirm exact I-E/E-I boundary) | 523-737 | pdftotext, representative sampling |
| 018 | English-Ilocano dictionary sample (also confirm boundary with back matter) | 738-840 | pdftotext, representative sampling |
| 019 | Back matter: Traditional Ilocano Songs, cultural appendix | 840-868 | pdftotext/vision as needed |

Dictionary-sampling dispatches (015-019) are explicitly told to flag any Hawaii-related content
(the triage catalog already found Purgi, kanaka, Aloha, Haway entries, a demographic paragraph,
and a worked example sentence in File 2 during triage sampling) and any slang/informal/taboo
register entries, per this project's standing dictionary-sampling convention.

**Guardrails applied (lessons carried over from Korean K1-K6, Spanish Wave S1, and Hawaiian H1
incidents):** anti-forking/merge-ownership discipline (no internal sub-forking, each dispatched
agent owns only its assigned file numbers), Write-tool/bash-heredoc restriction, explicit
numbering discipline (001-019 only, no invented splits without checking disk first), structural
verification (12-column table header, no placeholder residue) required before trusting any "done"
report. This is live/user-directed work and is exempt from the repo's 3pm-4:59am operating-hours
law by nature (not self-scheduled).

## Incident: File 1 page-offset was off by one (discovered mid-wave 2026-10-30)

The dispatch plan above used **PDF page = printed page + 26** (derived from a single TOC-area
check). Two independent agents (002, 005) empirically found the true offset is **PDF page =
printed page + 25** — independently confirmed a third time by direct `Read` probe: printed p.170
(Ch.7 start) = PDF p.195 (195−170=25), not PDF p.196.

**Consequence:** every PDF-page boundary in the Wave I1 table above for File 1 (001-012) is
nominally 1 page too high relative to the *true* chapter start. Because each dispatched agent's
assigned range was computed with the same wrong offset, consecutive files' assigned ranges
land exactly on the true chapter boundaries with a built-in 1-page overlap at each seam (e.g.
file 001 assigned through PDF 55 = true Ch.3 p.1, and file 002 assigned starting PDF 56 = true
Ch.3 p.2) — overlap, not a gap, EXCEPT wherever an agent trusted the *dispatch's wrong boundary
language* (e.g. "stop at Ch.5, PDF p.98") rather than reading its own assigned PDF page range
literally. This creates a real risk of a 1-page gap at each chapter-label seam (first page of the
next chapter silently dropped) if an agent stopped one page early rather than reading through its
full assigned PDF range.

**Action required before closing steps:** once all of 001-012 land, audit every file-to-file seam
in `established/` by checking the last PDF page genuinely captured by file N against the first PDF
page genuinely captured by file N+1 (per each file's own preamble), and vision-spot-check any
seam that looks like it has a gap rather than an overlap. File 013-019 (File 2, which has its own
separately-confirmed empirical page map) are not affected by this issue.

**Seam 001/002 (PDF p.55, printed p.30, Ch.3 opening page) — CHECKED 2026-10-30, no real loss.**
File 001 stopped just before PDF p.55; file 002 (as literally dispatched) started at PDF p.56,
skipping p.55. Directly vision-read PDF p.55: it is Ch.3's own opening summary table (§3.1
Articles and Case — the core/oblique × personal/non-personal article paradigm: ti, dagiti, iti,
kadagiti, ken ni, ni, da, kada) plus 4 throwaway example sentences. Every one of those article
forms is already captured with fuller individual glosses in file 002 (from its later §3.7
treatment, p.36-38) — confirmed via grep. No patch needed for this seam. Remaining seams
(002/003, 003/004, ..., 011/012) still need the same check once those files land.

**Further offset complication (flagged by file 011), RESOLVED 2026-10-30:** files 011 and 012 both
described the Ch.18/Glossary boundary as "PDF p.524" (implying offset +26), but a direct vision
read of PDF pp.521-525 confirmed the offset is **+25 throughout this seam too** (PDF p.522 =
printed p.497, end of Ch.18 §18.4.4; PDF p.523 = printed p.498, the Glossary's own first page).
Both agents' self-reports were off by one page in their verbal description of the boundary (not
a real pagination artifact in the source) — this caused a genuine ~10-entry content gap (Glossary
entries *absolutive* through *affix*, the glossary's first page) that fell between file 011's
stopping point and file 012's starting point. **Patched directly by the orchestrating session**:
vision-read PDF p.523 and inserted the missing 10 entries at the top of file 012's Glossary table,
with a patch note documenting the fix. The +25 offset appears to hold consistently across the
entire 549-page book — file 004 and file 010 have now independently confirmed it at the Ch.6/Ch.7
and Ch.14/Ch.15 boundaries too. No further offset anomalies expected, but the seam audit below
should still spot-check remaining boundaries once all files land.

## Status: Wave I1 — IN PROGRESS, dispatched 2026-10-30

## Seam audit — COMPLETE 2026-10-30

Every true chapter-opening PDF page at a file-to-file boundary in File 1 (001-012) was checked
directly against the source PDF. Root cause of the pattern: agents on both sides of a boundary
independently discovered the true +25 offset and correctly stopped before/started after the
*next* chapter's opening page as they understood it — but since my original dispatch ranges were
computed with the wrong +26 offset, the literal "first page" each agent was told to start from was
already one page past the true chapter start, and several agents recognized the neighboring
chapter's content and excluded it as out-of-scope from both sides, leaving the true opening page
uncaptured by anyone. Results:

| Seam | True boundary | Status |
|---|---|---|
| 001/002 (Ch.2→Ch.3, PDF p.55) | printed p.30, §3.1 article paradigm | Checked — **non-substantive** (fully redundant with later §3.7 content already in file 002); no patch needed |
| 002/003 (Ch.4→Ch.5, PDF p.98) | printed p.73, §5 intro + §5.1 opening | **Patched** into file 003 |
| 003/004 (Ch.5→Ch.6, PDF p.146) | printed p.121, §6 intro | **Patched** into file 004 |
| 004/005 (Ch.6→Ch.7, PDF p.195) | printed p.170, §7.1 Cardinals | Clean — file 005 self-extended its start to include it |
| 005/006 (Ch.7→Ch.8, PDF p.211) | printed p.186, §8 intro + §8.1 opening | **Patched** into file 006 |
| 006/007 (mid-Ch.8 split, PDF p.277/278) | printed p.252/253 | Clean — real content is contiguous; only file 007's preamble had a cosmetic offset-labeling error (+26 instead of +25), **corrected** |
| 007/008 (Ch.8→Ch.9, PDF p.345) | printed p.320, Ch.9 intro + scope | **Patched** into file 008 |
| 008/009 (Ch.9→Ch.10, PDF p.409) | printed p.384, Ch.10 intro + §10.1 opening | **Patched** into file 009 |
| 009/010 (Ch.11→Ch.12, PDF p.437) | printed p.412, §12.1–12.2 | **Patched** into file 010 |
| 010/011 (Ch.14→Ch.15, PDF p.469) | printed p.444, §15.1 opening | **Patched** into file 011 |
| 011/012 (Ch.18→Glossary, PDF p.523) | printed p.498, Glossary's own first page (10 entries) | **Patched** into file 012 |

**8 substantive content patches made** (files 003, 004, 006, 008, 009, 010, 011, 012), each with an
inline "Patch note" documenting what was missing and why, sourced via direct vision-read of the
source PDF by the orchestrating session (not a dispatched agent). File 2 (013-019) was not affected
— its page map was independently empirically probed and had no equivalent systematic error.

## After Wave I1 lands — ALL DONE 2026-10-30

1. ~~Verify all 19 files structurally.~~ Done — all 19 passed header/placeholder checks; a full
   seam audit additionally caught and patched 8 one-page content gaps (see above).
2. ~~Resolve any numbering collisions.~~ None occurred — all 19 agents landed on their assigned
   numbers with no collisions.
3. ~~Create `00_Extraction_Checklist.md`.~~ Done — full per-file summary table, ~275,700 words.
4. ~~Build `datasets/Ilocano/graphify-out/`.~~ Done (first ever for this language) — 341 nodes,
   445 edges, 19 communities, built from 3 independently-dispatched chunks. 1 collapsed
   (undirected) edge out of 446 raw edges — negligible noise, consistent with every other
   language's graph in this project.
5. ~~Update `LANGUAGE_INDEX.md`, `datasets/00_Analysis_Index.md`, `ROADMAP.md`, and the Language
   Ledger artifact.~~ Done — Ilocano's row in `LANGUAGE_INDEX.md` flipped to Phase 1 complete, new
   row added to `00_Analysis_Index.md` (12th language), new completion paragraph in `ROADMAP.md`,
   and the Ledger's Ilocano row moved from Triaged to Complete with updated stat strip
   (1,573 files / ~8.9M words).
6. **Not yet done — ask the user before committing+pushing.**
