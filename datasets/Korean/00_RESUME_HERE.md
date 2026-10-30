# Korean — external-drive stash extraction: resume checkpoint

**Started 2026-10-29, live/user-directed work** ("next is to do a full data-extraction for
Korean" — a direct continuation of the external-drive stash triaged 2026-10-19, documented in
`00_Book_Triage_Catalog.md`'s "Supplementary stash triage" section). Korean's original 17-file
corpus is already Phase 1 complete (`established/001`-`029`); this wave extracts the newly-found
85-file/3.0GB external stash on top of it. Not bound by a blanket pre-approval — same wave-by-wave
dispatch discipline as the original Korean Phase 1 run.

**If you are resuming this after an interruption (context limit, usage-limit reset, session
restart): read this whole file before doing anything else. Do not re-dispatch a wave marked
`DONE` below. Do not re-run the two resolved triage questions (see `00_Book_Triage_Catalog.md`) —
they are settled.**

## Pre-resolved triage questions (do not redo)

1. **`Intermediate College Korean.pdf` (external copy) — confirmed duplicate.** MD5-identical
   (`928673c9b878b5e70686b0638a73d08f`, 376pp) to the already-extracted
   `source_reference/languages/Korean/10.Intermediate college Korean.pdf`. **Skip entirely.** The
   known pp.225-376 gap from Phase 1 stays open; this stash cannot close it.
2. **`Korean 5 to 12 Integrated Resource Package.pdf` — mostly excluded, two appendices kept.**
   277pp total; pp.1-214 are BC Ministry of Education curriculum/administrative prose (excluded).
   **Appendix E "Common Words as Graded by Semantic Categories"** = PDF pages 215-258 (1,396
   graded vocabulary items, 27 semantic categories). **Appendix F "Basic Structural Patterns
   Graded by Complexity"** = PDF pages 259-277 (145 basic sentence patterns). Dispatch only this
   215-277 page range.

## Numbering

Original Korean Phase 1 corpus ends at `established/029`. This wave starts at `030`.

## Known Korean-specific PDF gotchas (from Phase 1 — check every file, don't assume uniformity)

1. **`+36266` fixed-offset cipher**: `real_codepoint = (extracted_codepoint + 36266) mod 65536`.
   Confirmed 4x in Phase 1 (Routledge/Cambridge titles). **Try this decode first** on any file that
   reports a text layer but renders garbled Hangul — can save a vision-reading pass entirely.
2. **Undecodable CID-font corruption**, no ToUnicode mapping — real vision-reading/Tesseract
   (`kor` model) required.
3. **Per-glyph bogus-CMap corruption** across many font subsets, each mapping to unrelated
   Latin-1/symbol chars — no single offset works, vision-reading required.
4. **Genuine romanization-only sources** (e.g. audio-companion booklets) are a legitimate design
   choice, not a corruption — don't force a Hangul-decode search on a source that's romanization
   by design.
5. A quick `pdftotext -f 1 -l 3 file.pdf - | wc -c` of ~3 or less almost always means no text
   layer at all (confirmed on this wave's own triage pass: `Beginner's Korean`, `Collins Korean
   Phrasebook`, `Easy to Learn Korean Language`, `H.B. Lee - Korean Grammar`, `Tense and Aspect in
   Korean`, `A Korean Grammar on Semantic-Pragmatic Principles` all returned 3 — go straight to
   vision-reading/cipher-check, don't waste time re-probing).

Standard rules apply from `../00_Reference_Extraction_Spec.md`: comprehensive-but-not-exhaustive
coverage, non-redundant-supplement check against existing `established/001`-`029` for any
overlapping grammar territory, copyright discipline (paraphrase + short illustrative quotes only),
vision-reading marginalia guard, output format per `_TEMPLATE/established/001_TEMPLATE.md`.
**Subagents must never run `graphify` themselves** — that happens once, after all waves land.

## Wave plan

All paths below are under `/media/kuroskalacs/Home-Theater/w-lang/Korean/` unless noted. Mark each
wave `DONE` with the date once its established files are confirmed written to disk.

### Wave K1 — flagship sources (030-034) — **DONE 2026-10-29**

All 5 items complete. Highlights: 030 Dirty Korean Everyday Slang (668 entries, clean text),
031 Korean Honorifics and Politeness (non-redundant-supplement scoped against existing honorific
coverage), 032 Making Out in Korean (456 entries, fully vision-read, zero text layer, one
documented scan gap at printed pp.32-33), 033 Let's Learn Korean Northern Dialect (flagship DPRK
find — 두음법칙 non-application as the standout systematic North/South contrast, fully vision-read
via a 16-chunk merge), 034 Korean 5-to-12 IRP Appendices E+F (145/145 grammar patterns, ~422-item
representative vocabulary sample of 1,396 total).

| # | File | Pages | Note |
|---|---|---|---|
| 030 | `04 Dictionaries, Phrasebooks, Vocabulary/Dirty Korean Everyday Slang.pdf` | 177pp | flagship slang, clean text |
| 031 | `03 Grammar, Workbooks, Usage/10 Korean Honorifics and Politeness in Second Language Learning.pdf` | 329pp | flagship academic, clean text, Lucien Brown |
| 032 | `04 Dictionaries, Phrasebooks, Vocabulary/Making Out in Korean.pdf` | 51pp | flagship slang, no text layer |
| 033 | `03 Grammar, Workbooks, Usage/13 Let's Learn Korean (Northern Dialect).pdf` | 462pp | flagship regional/dialect, no text layer |
| 034 | `06 Video Courses+Miscellaneous/Korean 5 to 12 Integrated Resource Package.pdf` | PDF pp.215-277 only (Appendix E+F) | clean text; ignore pp.1-214 |

### Incident: rogue sub-forking corrupted 033, created a wrongly-numbered 035 (2026-10-29)

The agent dispatched for item 033 (*Let's Learn Korean (Northern Dialect)*, 462pp no-text-layer
scan) parallelized its vision-reading internally via 16 of its own forked sub-agents — reasonable
in principle, not something it was told to do explicitly, but a legitimate technical choice for a
page-range split. However 3 of those 16 forks (self-identified as the "Pronunciation," "Grammar
Lessons 1-2," and "Korean-English vocab part 2" chunks) ignored their scratch-file-only scope and
each wrote their own independent full-book "merge" straight to the `established/` deliverable
path. Net effect: `established/033` was silently overwritten at least twice (last-write-wins race),
and one fork created a wrongly-numbered `established/035_lets_learn_korean_northern_dialect_full.md`
that collided with Wave K2's reserved number for `035_integrated_korean_beginning_1.md`.

**No content was lost** — all 16 scratch chunks in
`/tmp/.../scratchpad/korean_northern/chunks/` survived intact (confirmed on disk). **Fix applied:**
both rogue full-book merges were moved (not deleted) to
`/tmp/.../scratchpad/korean_northern/rogue_backups/` for reference, freeing the `035` number back
up, and a fresh cleanup agent — explicitly forbidden from using the Agent tool / forking — was
dispatched to rebuild one canonical merge from the 16 scratch chunks (resolving the 8 duplicate-
named-pair chunks by comparing content, not guessing) into `established/033`.

**Lesson for future dispatches of large no-text-layer sources in this project:** when a dispatch
prompt says "work through it in logical sections, produce ONE output file" for a large vision-
reading job, add an explicit line forbidding the agent from using the Agent tool / forking
sub-agents itself, or if parallelization really is wanted, explicitly designate which single
sub-step does the final merge-and-write to the deliverable path and tell every other sub-step by
name that it is scratch-only. This was not an issue on any other wave so far (English's chunk-
splitting during its graphify run used explicit human-dispatched sub-chunks, not an agent
self-forking) — it is specific to handing one large page-range job to a single subagent and
trusting it to self-organize internally.

**Update 2026-10-29, second occurrence:** the same pattern recurred independently on item 039
(*Korean Course Seoul University Vol. 2*, 319pp) — its agent dispatched 6 of its own forks for
page-range batches, and 2 of them again ignored scope and a "do not write files" instruction,
overwriting the target `established/039` file in sequence with non-compliant (5-6 column instead
of 12-column) content. **This time the top-level agent caught it itself** before reporting
completion: it cross-verified content against two other forks' independent reports, normalized the
whole file to the correct 12-column template via a script, and confirmed all 33 lessons present
and sequential before finishing. No orchestrator intervention was needed — confirmed clean on
disk (1,469 lines, 126,061 bytes, correct header format verified).

**Pattern now confirmed twice** (033, 039) — any single-subagent dispatch for a large book
apparently tends to self-fork for page-range parallelization, and some fraction of those forks
exceed scope and race to overwrite the deliverable. **For Wave K3 onward, add this line verbatim
to every dispatch prompt:** "If you parallelize this work via your own sub-agents/forks, every
fork except the one responsible for the final merge must be told explicitly, by name, that it is
writing a SCRATCH file only and must never touch the `established/` deliverable path — and you
(the top-level agent) must personally verify the final merged file's structure and column format
before reporting completion, not trust the last writer blindly." Still holding off on fully
trusting any "done" status until the file is read/verified directly; a file existing with a
plausible size is no longer sufficient evidence of real completion for a large-book dispatch —
the live agent may still have running forks.

### Wave K2 — SNU/Integrated course series (035-040) — **DONE 2026-10-29**

All 6 items complete and verified on disk (structure/column-format checked directly, not just
file-existence). Two more rogue-forking incidents occurred (039, mid-run) and both were either
caught by the orchestrator (033, already logged above) or self-corrected by the top-level agent
before reporting done (039). 037 dispatched its own 11 sub-forks cleanly and merged them itself
with no incident. See the incident notes above for the anti-forking instruction now added to every
Wave K3+ dispatch.

### Wave K2 — SNU/Integrated course series (035-040) [original plan, superseded by DONE note above]

| # | File | Pages |
|---|---|---|
| 035 | `01 Beginners Courses/Integrated Korean Beginning Level 1. Textbook.pdf` | 331pp |
| 036 | `01 Beginners Courses/Integrated Korean Beginning Level 2. Textbook.pdf` | 348pp |
| 037 | `01 Beginners Courses/Korean Level 1 (Seoul National University Language Education Institute).pdf` | 306pp |
| 038 | `01 Beginners Courses/Korean Level 2 (Seoul National University Language Education Institute).pdf` | 184pp |
| 039 | `02 Intermediate-Advanced Courses/Korean Course Seoul University Vol. 2.pdf` | 319pp |
| 040 | `02 Intermediate-Advanced Courses/Korean Course Seoul University Vol. 3.pdf` | 348pp |

### Incident: College Korean agent used wrong numbers, ignored its assigned filename (2026-10-29)

The agent dispatched for item 044 (*College Korean*, Rogers/You/Richards) ignored the explicit
instruction to write exactly one file to `established/044_college_korean.md`, and instead split
its output into two files and wrote them to `established/041_college_korean_part1.md` and
`established/042_college_korean_part2.md` — both already reserved for *other* Wave K3 books
(SNU Vol. 4 and My Korean 1 respectively). No actual data was overwritten (different full
filenames each time — `041_college_korean_part1.md` vs. the in-flight `041_korean_course_snu_vol4.md`,
etc.), but it created a numbering-prefix collision. **Fixed by the orchestrator**: renamed to
`044_college_korean_part1.md` and `046_college_korean_part2.md` (the two nearest free slots after
`045_korean_for_dummies.md`, already correctly occupied), fixed both files' internal cross-
references to each other, and **shifted Waves K4/K5/K6 forward by one number each** to keep
`046` clear for this second part (see renumbered tables below — K4 is now 047-052, K5 is now
053-058, K6 is now 059-065). **Lesson for future dispatches:** an agent splitting a long book into
multiple output files on its own initiative, without checking in, is a third variant of the same
underlying problem as the rogue-forking incidents above — add an explicit line to future dispatch
prompts: "If you need to split the output into multiple files, STOP and use the exact filename
given; if genuinely necessary, pick the next free number(s) after the highest-numbered file
currently in `established/` and say so explicitly in your report — never reuse a number this
dispatch didn't assign you."

### Wave K3 — remaining SNU vol + My Korean + College Korean (041-046, originally 041-045 — see incident note above) — **DONE 2026-10-29**

All 6 files complete and verified directly on disk (table structure, lesson/unit sequencing, no
placeholder text) — 041 SNU Vol. 4 (35 lessons, 2,524 lines), 042 My Korean 1 (1,212 lines, 13
tables), 043 My Korean 2 (730 lines), 044/046 College Korean parts 1-2 (split due to the incident
above), 045 Korean for Dummies (547 lines). Wave K4 is scheduled via cron to begin at 3:02pm
2026-10-29 using the shifted 047-052 numbering.

| # | File | Pages |
|---|---|---|
| 041 | `02 Intermediate-Advanced Courses/Korean Course Seoul University Vol. 4.pdf` | 381pp |
| 042 | `01 Beginners Courses/My Korean 1.pdf` | 471pp |
| 043 | `01 Beginners Courses/My Korean 2.pdf` | 509pp |
| 044 | `01 Beginners Courses/College Korean.pdf` (part 1: front matter + Lessons 1-15) | 380pp total — Rogers/You/Richards, confirmed distinct from "Intermediate College Korean" |
| 045 | `01 Beginners Courses/Korean for Dummies.pdf` + `01 Beginners Courses/Korean for Dummies Cheat Sheet.PDF` | 387pp + 2pp, one file |
| 046 | `01 Beginners Courses/College Korean.pdf` (part 2: Lessons 16-26 + back matter) | see 044 — split into two files, numbers non-contiguous due to the incident above |

### Incident: History of the Korean Language split used a reserved-but-unwritten number (2026-10-29)

The agent dispatched for item 049 (*A History of the Korean Language*, 348pp) also split its
output into two files (the book, merged, came to ~640KB — well beyond any prior established
file). It correctly checked the `established/` directory for free numbers before picking one, saw
`050` already on disk (Modern Conversational Korean) and avoided it — but `051` and `052` were
*reserved* for two other Wave K4 items (Tense and Aspect, Semantic-Pragmatic Grammar) that simply
hadn't finished writing yet, so they looked "free" from a disk-only check. It wrote part 2 to
`051_history_of_korean_language_part2.md`, which the orchestrator caught and fixed before either
of the two legitimately-reserved agents landed: renamed to `053_history_of_korean_language_part2.md`
(the next number not claimed by *any* currently-dispatched Wave K4 item, written or not), fixed
both files' cross-references, and **shifted Waves K5/K6 forward by one more number each**
(K5 is now 054-059, K6 is now 060-066; see renumbered tables below).

**Lesson, refined again:** "pick the next free number" isn't enough when other agents in the same
wave are still running — a number can be *reserved* by an in-flight sibling dispatch without yet
existing on disk. Future dispatch prompts needing the filename-discipline guardrail should name
every other number *currently assigned in this same wave's dispatch*, not just say "check what's
on disk."

### Incident: LOALL Korean (047) multi-part split also hit the reserved-number trap (2026-10-29)

Item 047 (*Korean*, LOALL v.4, Suk-Jin Chang) also grew too large for one file — a 266pp academic
structural-linguistic monograph vision-read in 13 chunks (zero text layer throughout). Its first part
(`established/047_korean_loas_library.md`, Chapters 1–3) had already landed with a footer planning a
5-part split at files `051`–`054` — the same reserved-but-unwritten-number trap as the History-of-
Korean-language incident above, this time self-inflicted by a prior pass through this exact book rather
than a different Wave K4 item colliding with it. Caught before parts 2–4 were written: `051`/`052` are
reserved for *Tense and Aspect in Korean*/*A Korean Grammar on Semantic-Pragmatic Principles* (both
still in-flight at dispatch time), `050` is already *Modern Conversational Korean*, and `051` had
separately already been landed-and-renumbering-pending for *A History of the Korean Language* part 2
(see above — that file is still physically at `051` on disk pending its own rename to `053`, which has
not yet been executed as of this writing; do not write anything new to `051` or `053` without
re-checking both books' status first).

**Fix applied:** the remaining 3 parts (Ch. 4+5 merged into one Part 2, Ch. 6 as Part 3, Ch. 7+Appendix+
Notes as Part 4 — consolidating the originally-planned 5-way split into 4) were written to **`067`/
`068`/`069`** (originally attempted at `066`-`068`, but Wave K6 had concurrently been reshifted to claim
`066` while this was in progress — caught and renumbered up by one more before any collision landed).
File 047's own footer was corrected to point at the real numbers. **Book 047 (all 4 parts: `047`,
`067`, `068`, `069`) is now fully extracted end to end** — 13 vision-reading chunks merged, ~776
vocabulary entries total across all 4 parts, no content lost.

**Second, more serious collision caught in the same pass:** a **separate, independent duplicate full-book
merge** of this exact same source had *also* landed concurrently — written to `051_korean_loas_library_
part2_word_classes.md`, `052_korean_loas_library_part3_sentences.md`, and
`053_korean_loas_library_part4_extended_sentences.md` (a 5-part split plan, missing its own Part 5 for
Ch.7+Appendix+Notes — incomplete). These three files **collided by number** (though not by exact
filename, so nothing was silently overwritten) with three already-completed, legitimately-numbered Wave
K4 books: `051_tense_and_aspect_in_korean.md`, `052_korean_semantic_pragmatic_grammar.md`, and
`053_history_of_korean_language_part2.md` (itself the already-renamed survivor of the earlier
049/051→053 incident above). Since the duplicate LOALL merge was both a true duplicate (same 13 source
scratch chunks as the complete 047/067/068/069 version) and incomplete (3 of its own planned 5 parts),
it was moved — not deleted — to
`/tmp/.../scratchpad/korean_loall_duplicate_backup/` for reference, and `051`/`052`/`053` now correctly
hold only their one rightful book each. **Update, minutes later:** the duplicate dispatch's missing
Part 5 (`054_korean_loas_library_part5_discourse_appendix.md`, Ch.7+Appendix+Notes) then landed too,
colliding with Wave K5's reserved `054` (Lonely Planet Korean Phrasebook) — moved to the same backup
folder. The duplicate dispatch appears to now be fully stopped/complete; re-check the established/
directory for any further `*loas_library*` strays before dispatching anything else near these numbers.

**Lesson, extended twice more:** (1) the reserved-number problem isn't limited to two agents colliding
*concurrently* on a fresh number — a single book's own prior-session split plan can go stale if other
wave items claim numbers in the interim; re-read the *current* `established/` directory listing and
this file's wave tables fresh before writing any multi-part split's later parts, don't trust a plan
written in an earlier part's own footer. (2) **A single Wave K4 item (047) can itself be picked up by
two independent dispatches** if a user-resumed session and a cron-scheduled wave both target the same
book without checking whether the other is already in flight — before merging a large multi-chunk
book's scratch output into `established/`, grep the directory for any other file already referencing
the same source title, not just check the numbers you intend to claim.

### Incident: a fourth self-forking collision, on 047 (2026-10-29)

The agent dispatched for item 047 (*Korean*, Chang, London Oriental and African Language Library)
hit the same underlying failure mode as 033/039/College-Korean a fourth time: one of its own 13
internal forks independently produced a full-book duplicate merge and wrote it to
`established/051`-`053` — colliding with three *already-completed* Wave K4 files at those exact
numbers (Tense and Aspect, Semantic-Pragmatic Grammar, History of the Korean Language part 2).
Unlike the earlier incidents, **the top-level agent caught and resolved this itself** before
reporting completion: it moved the rogue duplicate aside to a scratch backup (not deleted), wrote
its own legitimate Parts 2-4 to `established/067`-`069` instead (the next numbers not claimed by
any in-flight K4/K5/K6 item per this document), and documented the whole thing in a closing
numbering note inside `047_korean_loas_library.md` itself. The orchestrator verified all four
parts (047, 067-069) are structurally clean, non-overlapping in content (Chapters 1-3 / 4-5 / 6 /
7+Appendix+Notes), and fixed one remaining stale cross-reference inside `047`.

**No cascade needed this time** — `067`-`069` falls safely outside every currently-planned wave
range (K4 047-053, K5 054-059, K6 060-066), so K5/K6 numbering is unaffected. **Pattern now
confirmed four times** (033, 039, College Korean, 047/LOAS Library) — self-forking for large
no-text-layer books reliably produces at least one rogue full-book duplicate merge. The anti-
forking guardrail added after the second incident reduces the blast radius (agents now catch and
self-correct rather than leaving corrupted output for the orchestrator to find) but does not
prevent the underlying behavior — worth treating as expected/designed-around rather than something
further prompt engineering will fully eliminate.

### Wave K4 — academic linguistic descriptions (047-053 + 067-069 overflow, originally 046-051) — **DONE 2026-10-29**

All 6 dispatched items complete and verified: 047/067-069 (Korean, LOAS Library — split 4 ways
after a self-forking incident, see above), 048 (Cambridge Language Surveys), 049/053 (History of
the Korean Language — split 2 ways, also an incident, see above), 050 (Modern Conversational
Korean), 051 (Tense and Aspect), 052 (Semantic-Pragmatic Grammar). Wave K5 dispatched immediately
after per the user's standing instruction (2026-10-29) not to pause for confirmation between waves.

K3 (041-046) was re-verified structurally complete (all 6 files, correct 12-column headers, zero
placeholder hits) before this wave was dispatched. All 6 Wave K4 source paths were double-checked
against the live filesystem before dispatch. Every dispatch prompt included the anti-forking/
merge-ownership guardrail and the filename-discipline line from the incident notes above.

| # | File | Pages | Note |
|---|---|---|---|
| 047 | `03 Grammar, Workbooks, Usage/07 Korean (London Oriental and African Language Library).pdf` | 266pp | pre-dispatch note said "clean text" — **actually zero text layer, fully vision-read** (13-chunk merge); **DONE 2026-10-29**, 4 parts: `047`/`067`/`068`/`069` |
| 048 | `03 Grammar, Workbooks, Usage/08 The Korean Language (Cambridge Language Surveys).pdf` | 462pp | clean text |
| 049 | `03 Grammar, Workbooks, Usage/12 A History of the Korean Language.pdf` (part 1) | 348pp total | clean text, typology-grounding value; split into two files, part 2 at 053 (non-contiguous due to the incident above) |
| 050 | `01 Beginners Courses/Modern Conversational Korean.pdf` | 378pp | clean text |
| 051 | `03 Grammar, Workbooks, Usage/09 Tense and Aspect in Korean.pdf` | 194pp | **no text layer** — vision/cipher-check first |
| 052 | `03 Grammar, Workbooks, Usage/11 A Korean Grammar on Semantic-Pragmatic Principles.pdf` | 284pp | **no text layer** — vision/cipher-check first |

### Wave K5 — phrasebooks, Hanyang series, small beginner titles (054-059, originally 052-057 — shifted +2, see both incident notes above) — **DONE 2026-10-29**

All 6 items complete and verified on disk. 057 (*Essential Korean*) was the last piece to land:
118pp, zero embedded fonts/zero text layer (confirmed via `pdffonts`), fully vision-read across 31
topical chapters — 1,998 vocabulary/expression rows, single file (404KB). **New PDF gotcha found and
fixed on 057**: the raw source PDF's page tree is corrupted/ambiguous — `pdftoppm` rendered the exact
same page index to genuinely different content across repeated invocations (confirmed via md5sum
mismatches), traced to likely `pdfsam-console` processing (its own `Creator` tag). Fixed by
`mutool clean -gggg -s`, which produced a fully deterministic copy (3 repeated renders of the same
page then matched exactly) — all vision-reading for 057 was done from that repaired copy, with every
page's printed page number visually cross-checked against an empirically-verified offset formula
(zero deviation across 10+ checkpoints). *Essential Korean CD contents.pdf* was checked and confirmed
to be a bare CD-track-number index mirroring the book's own TOC — no extractable content, correctly
skipped. One stray-marginalia instance found (p.169) and excluded. Non-redundant-supplement scoping
applied: the book's "Speech Levels & Speech Styles" essay was skipped as redundant with
`established/031`; the general native/Sino-Korean numeral+classifier explanation was skipped as
redundant with 10 prior established files, but all numeral/classifier *vocabulary* was still kept in
full, plus several narrower grammar notes not previously captured (만-grouping omission rule,
유월/시월 irregular month readings, 색/색깔 color-suffix exception rule, kinship
referring-vs-addressing marking, senses/emotions 3-way statement/question/honorific-question
paradigm, and others — see the file's own Grammar points section).

| # | File | Pages | Note |
|---|---|---|---|
| 054 | `04 Dictionaries, Phrasebooks, Vocabulary/Lonely Planet Korean Phrasebook.pdf` | 308pp | clean text; check for a slang/colloquialism callout section (cf. Japanese's Rough Guide phrasebook) |
| 055 | `04 Dictionaries, Phrasebooks, Vocabulary/Collins Korean Phrasebook.pdf` | 129pp | **no text layer** |
| 056 | `01 Beginners Courses/Hanyang Korean 1 Grammar & Patterns.pdf` + `...Textbook.pdf` + `...Writing Practice.pdf` | 24+252+129pp | one combined course, 3 files — Writing Practice likely mostly drill, skim for any new vocab/grammar only |
| 057 | `01 Beginners Courses/Essential Korean.pdf` + `01 Beginners Courses/Essential Korean CD contents.pdf` | 118pp + 4pp | CD contents likely low-value track list |
| 058 | `01 Beginners Courses/Beginner's Korean.pdf` | 262pp | **no text layer** |
| 059 | `04 Dictionaries, Phrasebooks, Vocabulary/Easy to Learn Korean Language.pdf` | 53pp | **no text layer** |

### Incident: an agent died silently with no notification at all (2026-10-29)

The agent dispatched for item 060 (*H.B. Lee, Korean Grammar*) produced 5 of its 6 planned chunks
(A-E, in `/tmp/.../scratchpad/hblee_korean_grammar/chunks/`), then simply stopped — no completion
notification, no failure notification, task-id gone from the harness's tracking entirely when
checked via `TaskOutput(block=false)`. The orchestrator had wrongly assumed it was still working
based on stale-but-plausible chunk timestamps; **the user caught this** by noting the UI's live-
subagent indicator showed nothing running, which prompted the actual check. This is a new failure
mode distinct from every prior incident this wave (those were all rogue-forking/numbering problems
from agents that *did* report back) — a genuine silent death with zero signal.

**Fix:** redispatched a fresh agent, pointed directly at the 5 surviving chunks, instructed to
verify them, produce only the missing 6th chunk, and merge — not restart the whole book. Also
told it explicitly not to disappear without a final report.

**Lesson:** a stale-but-plausible scratch-directory timestamp is not evidence a dispatch is still
alive — if asked to check, verify via `TaskOutput(task_id, block=false)` (returns "No task found"
for a dead/vanished task) rather than inferring liveness from file mtimes alone. Trust the user's
own observation of the live-subagent UI over an inferred guess.

### Wave K6 — H.B. Lee, DLI series, Pathfinder series (060-066, originally 058-064 — shifted +2) — **DONE 2026-10-29**

All 7 items complete and verified: 060 (H.B. Lee, recovered from a silent-death incident — see
above), 061/062 (DLI Advanced Course Vol I/II — Vol II turned out to be a partial 84pp excerpt,
documented honestly), 063 (DLI Headstart), 064 (DLI Headstart Cultural Notes), 065 (Pathfinder
Beginning — Workbook correctly skipped as pure drill), 066 (Pathfinder Low Intermediate — same).

## ALL SIX WAVES (K1-K6) COMPLETE — 2026-10-29

Final shape: established/030-069, 40 files from an originally-planned 35 items (the extra 5 came
from legitimate book splits plus the 067-069 overflow — see the incident notes throughout this
document for exactly why each split happened). Remaining steps before this wave is fully closed
out: (1) update `00_Extraction_Checklist.md` with a per-book summary table, (2) rebuild
`datasets/Korean/graphify-out/`, (3) update `LANGUAGE_INDEX.md`/`ROADMAP.md`/the Language Ledger
artifact, (4) commit+push once the user asks for it.

| # | File | Pages | Note |
|---|---|---|---|
| 060 | `03 Grammar, Workbooks, Usage/04 H.B. Lee - Korean Grammar.pdf` | 117pp | **no text layer** |
| 061 | `02 Intermediate-Advanced Courses/Korean Advanced Course. Volume I (Defence language Institute).pdf` | 191pp | no text layer |
| 062 | `02 Intermediate-Advanced Courses/Korean Advanced Course. Volume II (Defence language Institute).pdf` | 84pp | no text layer |
| 063 | `01 Beginners Courses/DLI Korean Headstart.pdf` | 490pp | no text layer |
| 064 | `01 Beginners Courses/DLI Korean Headstart Cultural Notes.pdf` | 42pp | no text layer |
| 065 | `01 Beginners Courses/Pathfinder in Korean Beginning Student Book.pdf` + `...Beginning Workbook.pdf` | 159+179pp | DJVU-adjacent/no text layer (student book is PDF, workbook is PDF too — both likely scanned) |
| 066 | `01 Beginners Courses/Pathfinder in Korean Low Intermediate Student Book.djvu` + `...Low Intermediate Workbook.djvu` | 210+252pp | **DJVU format, no text layer** — convert or vision-read directly from djvu |

## After all waves land

1. Update `00_Extraction_Checklist.md` with a summary table (per-book, not per-part-file) for all
   35 new items, same pattern as English's checklist.
2. Rebuild `datasets/Korean/graphify-out/` (`cd datasets/Korean/` first) — 29 existing + 35 new =
   expect a substantially denser graph. Watch for the 64K-output-token-cap gotcha on dense chunks;
   split to 5-6 files per chunk if any dispatch fails.
3. Update `LANGUAGE_INDEX.md` (Korean's "Phase 1 complete" line — file/word counts),
   `ROADMAP.md` (note the stash's completion), and the Language Ledger artifact
   (`https://claude.ai/code/artifact/5a88e09a-56cb-4bf8-8de3-a41d597f97cc`) — Korean's "Expanding"
   tag can likely come off once this lands, pending whether any further Korean material remains
   open.
4. Update memory `hawaiian_language_priorities.md` and `korean_phase1_complete.md` (supersede with
   a new note, same pattern as `hungarian_phase1_complete.md` → test-run memory).
