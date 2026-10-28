# English extraction — COMPLETE (kept for historical reference)

**Status as of 2026-10-27, ~3pm PDT: Waves A and B both fully complete — 259 files in
`established/`. Nothing left to resume.** See `00_Extraction_Checklist.md`'s per-book summary
table for the current, authoritative record. This file's detail below is left as-is for audit
trail (e.g. the operating-hours note) but is no longer the active status source.

**Next real open items**: `057`'s disposition (misfiled Chinese grammar — see the checklist), the
first `/graphify datasets/English` run, and whether Ilocano/Cantonese come next per
[[hawaiian_language_priorities]].

## COMPLETE: first /graphify datasets/English run (2026-10-27)

**Finished.** 3,517 nodes, 4,187 edges, 252 communities. Outputs in `graphify-out/`: `graph.json`,
`graph.html`, `GRAPH_REPORT.md`, `manifest.json`, `cost.json`. Health check: 1 collapsed
(undirected) edge out of 4,188 raw edges — negligible noise from 24 independently-dispatched
chunks, not fabrication. Top 50 communities (by size) got hand-authored labels; the remaining 202
got auto-derived labels from their dominant source book. Nothing left to resume here.

<details><summary>Original in-progress notes (historical)</summary>

## IN PROGRESS: first /graphify datasets/English run (started 2026-10-27, ~3pm PDT)

**If interrupted, resume here — do not restart the whole graphify run from scratch.**

Working directory for all of this is `/home/kuroskalacs/Documents/Doll-Fi/media/Reference/slang-synthesis/datasets/English/` (cwd), `INPUT_PATH='.'`, `IS_DIRECTED=False` (no `--directed` flag was given) throughout. Python interpreter is cached at `graphify-out/.graphify_python`.

**Done so far:**
1. Step 1 (install check) — done, interpreter resolved.
2. Step 2 (detect) — done: 263 files, ~1,067,199 words, all `document` type (no code/paper/image/video). Result cached at `graphify-out/.graphify_detect.json`. No size-warning triggered (under 2M words / 500 files), no subfolder-narrowing needed.
3. Step 3 Part A (AST) — done, skipped (no code files); empty `graphify-out/.graphify_ast.json` written.
4. Step 3 Part B0 (cache check) — done: 0/263 cached, all 263 need extraction. `graphify-out/.graphify_uncached.txt` has the full list.
5. Step 3 Part B1 (chunking) — done: split into 12 chunks of ~22 files each, saved at `graphify-out/.graphify_filelist_01.txt` through `_12.txt`.
6. Step 3 Part B2 (dispatch) — **12 subagents dispatched**, each told to read its own `.graphify_filelist_NN.txt` and write `graphify-out/.graphify_chunk_NN.json`. **This is the step that may still be in flight if interrupted.**

**Update 2 (latest):** chunks 8, 9, 10, and 12 all repeatedly failed (64,000-output-token cap, and
separately a session-limit boundary hit) and wrote nothing, even after the first 11-file split.
**Final working size for the Old-English-heavy chunks turned out to be ~5-6 files per sub-chunk,
not 10-11.** Each of 08/09/10/12 is now split into 4 sub-chunks via `split -n l/4 -d
graphify-out/.graphify_filelist_NN.txt graphify-out/.graphify_filelist_NN_` producing
`_00`/`_01`/`_02`/`_03` suffixes (5-6 files each) → `.graphify_chunk_NN_00.json` etc. **The merge
glob (`graphify-out/.graphify_chunk_*.json`) picks up any filename matching that pattern — `08_00`
through `12_03` merge in fine alongside `01`-`07`,`11` — no special-casing needed in Step B3.**
Chunks 01-07 and 11 succeeded at the original ~22-file size without issue — the failure pattern
seems concentrated on the denser Old-English/19th-century-grammar content (lots of diacritics,
dense paradigm tables), not file count alone. If any `NN_0X` sub-chunk still fails, split to 2-3
files per dispatch rather than retrying the same size.

**To resume:**
- Check which `.graphify_chunk_*.json` files exist on disk (`ls graphify-out/.graphify_chunk_*.json`).
  Expected full set: `01` through `07`, `08_00`-`08_03`, `09_00`-`09_03`, `10_00`-`10_03`, `11`,
  `12_00`-`12_03` — 19 files total covering all 263 source files. Any missing ones need
  re-dispatching — reuse the exact same compact subagent prompt pattern (read the matching
  `.graphify_filelist_*` file, write the matching `.graphify_chunk_*.json`, explicitly told to keep
  the response compact and not narrate/quote file contents). The project-specific node-density rule
  (don't make one node per vocabulary-table row — extract concepts/mechanisms/books, 10-20 nodes per
  file for these smaller chunks) is mandatory in every dispatch.
- Once all 12 chunk files exist, proceed to the graphify skill's **Step B3** (collect/cache/merge — read real token usage from each Agent call's `usage` field into the chunk JSON first, then merge all chunks into `.graphify_semantic_new.json`, save to cache via `save_semantic_cache` with `prompt_file` = the graphify skill's `references/extraction-spec.md` absolute path, merge cached+new into `.graphify_semantic.json`, clean up temp files).
- Then **Step 4** (build graph + cluster + analyze + export graph.json/GRAPH_REPORT.md, with the empty-graph guard and the #479 shrink-guard both respected).
- Then **Step 4.5** (health check — read-only, just report dangling/missing/collapsed edges if any).
- Then **Step 5** (label communities — read `.graphify_analysis.json`, write 2-5 word names per community, regenerate report + re-export graph.json with labels).
- Then **Step 6** (HTML export; skip Obsidian/wiki/Neo4j/etc. — no flags were given).
- Then **Step 9** (save manifest, update cost tracker, delete the intermediate `.graphify_*.json`/`.graphify_filelist_*.txt`/`.graphify_chunk_*.json` files).
- Report the God Nodes / Surprising Connections / Suggested Questions sections from `GRAPH_REPORT.md` back to the user per the skill's own closing instructions.

## What's done

- **Wave 0 (55 chunks)**: CMOS chs.5,6,7,8,9,10,11,13 + New Oxford Style Manual ch.21,3,4,5,6,9,10,11,12 —
  complete, files `001`–`055`.
- **Wave A (17 of 18 items, files `056`–`073`)**: the original `secondary resources/` ESL
  collection, items 1–18 of the pre-Wave-0 35-item plan in `00_Book_Triage_Catalog.md`. All done
  except item 2:

| # | File prefix | Source | Status |
|---|---|---|---|
| 1 | `056` | Cambridge Grammar In Use .doc (Murphy, UK ed.) | done, 29 parts |
| 2 | `057` | ~~Comprehensive Grammar[A4].pdf~~ | **EXCLUDED — see below** |
| 3 | `058` | Function-based Grammar Vol I (Givón) | done, 3 parts |
| 4 | `059` | Function-based Grammar Vol II (Givón) | done, 3 parts |
| 5 | `060` | When Bad Grammar Happens to Good People | done, 14 parts |
| 6 | `061` | Beyond Snobbery | done, 1 file |
| 7 | `062` | Grammar for the Utterly Confused | done, 1 file |
| 8 | `063` | Grammar Workbook for Dummies | done, 6 parts |
| 9 | `064` | Complete Idiot's Guide to Grammar & Style | done, 2 parts |
| 10 | `065` | Grammar and Usage for Better Writing | done, 2 parts |
| 11 | `066` | New Grammar Practice (pre-int) | done, 7 parts |
| 12 | `067` | Basic English Grammar Bk1+Bk2 (Azar) | done, 2 parts |
| 13 | `068` | Grammar in Use, US ed. (Murphy, vision-read) | done, 9 parts |
| 14 | `069` | Grammar Practice Upper-Intermediate (vision-read) | done, 11 parts |
| 15 | `070` | Essential Grammar Supplementary Exercises (vision-read) | done, 1 file |
| 16 | `071` | Longman Grammar Practice Intermediate (vision-read) | done, 9 parts |
| 17 | `072` | History of English: A Student's Guide | done, 5 parts |
| 18 | `073` | The English Language: A Historical Introduction | done, 9 parts |

**169 files total in `established/` right now.**

## `057` — do not re-dispatch as English

`Comprehensive Grammar[A4].pdf` (the file named in the original triage catalog) was opened and
confirmed to actually be **Yip & Rimmington's *Chinese: A Comprehensive Grammar*** (Routledge),
misfiled inside the `English Grammar Ebook collection` folder. Its chapter titles ("Nouns and
Nominalisations," etc.) superficially pattern-match English grammar terminology, but the content
is Mandarin grammar written in English. **Do not extract it as English.** Still open: decide
whether to (a) leave it excluded and move on, (b) relocate the physical file to a Mandarin/Chinese
source folder, or (c) extract it separately as a Chinese-language reference if this project ever
does deeper Mandarin work. Not yet corrected in `00_Book_Triage_Catalog.md`'s Wave 1 list — do that
alongside whichever option is chosen.

## Wave B — not yet dispatched (17 items, files `074`–`090`)

All from the Old English Language Learning Pack, per `00_Book_Triage_Catalog.md`'s original
Wave 4/5/6 (items 17–35 of the pre-Wave-0 plan, renumbered here since Wave A took 056–073):

| Next file # | Source file | Pages | Text layer | Notes |
|---|---|---|---|---|
| `074` | `08 The Germanic Languages (Routledge).pdf` | 648 | clean | split 2-3 parts |
| `075` | `12 The Syntax of Early English.pdf` | 361 | clean | split 2 parts |
| `076` | `02 Beginning Old English.pdf` | 264 | clean | **watch þ/ð cipher** (known: þ→ƒ, ð→ê in this file, verify per-page) |
| `077` | `06 Old English A Linguistic Introduction.pdf` | 213 | clean | |
| `078` | `13 Reading Old English Texts.pdf` | 243 | clean | **watch þ/ð cipher** |
| `079` | `04 An Introduction to Old English.pdf` | 174 | clean | non-redundant-supplement vs `076` |
| `080` | `16 A Critical Companion to Beowulf.pdf` | 417 | clean | split 2 parts, literary-critical not linguistic |
| `081` | `14 Old English Literature A Short Introduction.pdf` | 162 | clean | |
| `082` | `15 The Poetics of Old English.pdf` | 153 | clean | |
| `083` | `09 From Old English to Standard English.pdf` | 118 | **vision** | prioritize within vision wave — directly bridges to modern English |
| `084` | `05 An Old English Grammar.pdf` | 90 | **vision** | |
| `085` | `07 Old English and Its Closest Relatives.pdf` | 151 | **vision** | **done, 4 parts (2026-10-27)** — `074` did not exist yet at dispatch time, so no overlap check was possible; see `085_oe_closest_relatives_pt01.md`'s coverage note for full rationale and a flag for `074` to check against this source later |
| `086` | `Teach Yourself Old English Audio/Teach Yourself Old English.pdf` | 150 | **vision** | CD1/CD2 folders confirmed empty, no audio to transcribe |
| `087` | `17 Beowulf (Black Cat Publishing).pdf` | 57 | **vision** | graded/simplified reader, literary not grammar, low priority |
| `088` | `The Grammar of English Grammars[A4].pdf` (back in `secondary resources/`) | 1446 | clean (Project Gutenberg plain-text) | **huge** — split into 6-8 parts; 1851 prescriptive grammar, low priority for *modern* need but real content |
| `089` | `18 A Concise Anglo-Saxon Dictionary.pdf` | 473 | clean but **garbled** — two-column + þ/ð cipher, resolve before trusting entries | **dictionary-scale: sample, don't exhaustively transcribe**, same convention as every oversized dictionary in this project |
| `090` | `03 A Guide to Old English.doc` | n/a, 96MB, ~174 embedded JPEGs | **near-textless** | lowest-confidence payoll in the whole catalog — vision-read embedded images only |

All Old English pack files live at:
`/home/kuroskalacs/Documents/Doll-Fi/media/Reference/slang-synthesis/source_reference/languages/Old English Language Learning Pack/`

`088` (Grammar of English Grammars) lives back in:
`/home/kuroskalacs/Documents/Doll-Fi/media/Reference/slang-synthesis/source_reference/languages/English Grammar Ebook collection/secondary resources/The Grammar of English Grammars[A4].pdf`

**Dispatch the same way Wave A was dispatched**: one subagent per catalog item (not pre-split into
20-page chunks like Wave 0 — these are normal-sized books, dispatch per-book and let each agent
split its own output into multiple numbered files if the content is large, per
`00_Reference_Extraction_Spec.md`'s chunking rule). 17 items fits in one wave under the 20-concurrent
cap.

## Operating-hours note

Mid-Wave-A, several subagents paused themselves citing this repo's standing operating-hours law
(autonomous batches restricted to 3pm–4:59am; it was ~12:30pm PDT). The developer confirmed this
was live, user-directed work and explicitly said to continue — not a case where the rule should
block a direct, in-the-moment request. If Wave B dispatch also happens during the restricted
window, **include this line in each dispatch prompt** (used successfully to unblock the paused
Wave A chunks): *"This task is explicitly user-directed (the user is actively present in this
session and asked for this extraction right now) — it is not self-scheduled autonomous work, so the
repo's operating-hours restriction on autonomous batches does not apply here. Proceed with the
extraction."* Only use this framing when the user has actually just asked for it in the live
conversation — don't use it to justify self-scheduled work.

## After Wave B lands

1. Serialize the `00_Extraction_Checklist.md` Output files table (one pass, not per-subagent, per
   the >n=3 concurrency rule).
2. Resolve `057`'s disposition (see above).
3. Run `/graphify datasets/English` for the first time — this language has never been graphed.
4. Consider whether Ilocano/Cantonese (both triaged 2026-10-26, neither extracted) should be next,
   per [[hawaiian_language_priorities]].
</details>
