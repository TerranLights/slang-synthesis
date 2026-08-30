# Dutch — Reference Material Triage Catalog

**Status: tentative — third pipeline test run, applying the same methodology validated on
Serbian/Croatian/Bosnian and Hungarian.** See `../../methodology-observations/dutch_test_run.md`
for process notes.

**Folder naming note:** `source_reference/languages/Dutch/` is a near-empty placeholder (just a
`to_download.txt`). The real content lives in `source_reference/languages/Dutch (Nederlands)
Language Learning Pack/` — 84 files. This project's own `datasets/`/`language_corpus/` folders use
`Dutch` (the simpler, unambiguous folder-safe name) regardless of the source folder's own longer
name.

**Scope decision, consistent with the Hungarian run:** 84 files was not triaged exhaustively.
Focused on the grammar-reference cluster (files 22-32) and select others; the large blocks of
readers/fairy-tale texts (files 56-82, mostly Dutch translations of classic fairy tales — Assepoester
"Cinderella," Sneeuwwitje "Snow White," Roodkapje "Little Red Riding Hood," etc.) and the
travel-guide cluster (files 38-48) were not triaged — the fairy tales in particular are flagged as a
strong candidate for later `literary`/`archaic` register work, same as Serbian Folk Tales was
flagged for Serbian/Croatian/Bosnian.

---

## Top candidates triaged

| File | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `25 Dutch An Essential Grammar.pdf` | 294 | **Yes**, with a minor extraction quirk | **Highest** | Shetter & Van der Cruysse-Van Antwerpen, *Dutch: An Essential Grammar* (9th ed., Routledge) — same Routledge "Essential Grammar" series that worked well for Hungarian. 27 chapters, clean structure. First extraction target. |
| `27 Dutch A Comprehensive Grammar.pdf` | 454 | **Yes**, same quirk | High | Larger companion volume, same publisher family (Routledge Comprehensive Grammars). Deferred to a later pass. |
| `22 Basic Dutch A Grammar and Workbook.pdf` | 206 | **Yes** (clean, no quirk) | Medium | Real, clean text layer with no extraction artifacts at all — worth a look if `25`'s content runs out of value. |
| `83 The Phonology of Dutch.pdf` | 216 | **No** — image-only | Medium | Academic paper, would be directly useful for grounding the typology profile (parallels Hungarian's `ON-HUNGARIAN-MORPHOLOGY.pdf`), but needs vision-reading. Deferred. |
| `26 Dutch Reference Grammar.pdf` | 137 | **No** — image-only | Low-medium | Deferred behind `25`, which has equivalent-or-better content with a usable text layer. |
| `10 Colloquial Dutch.pdf` | 162 | **No** — image-only | Medium | "Colloquial" framing makes this a strong slang-adjacent candidate once vision-reading is applied — same pattern as the Serbian/Croatian/Bosnian "Colloquial" titles. Deferred. |

**Extraction quirk found in `25` and `27` (both same publisher/typesetting):** `pdftotext` prepends
a long run of stray digits (`1111\n2\n3\n4\n5\n6\n7\n8\n9\n1011\n1\n12111...`) to the start of every
page's extracted text — this appears to be page-margin ruler/registration marks from the book's own
print layout being caught by the extraction, not a sign of a corrupted or garbled text layer (the
real body text immediately following it is clean and fully readable). **Distinct from the earlier
"garbled OCR" failure mode** (`Teach Yourself Serbian.pdf` in the SCB run) — this is a real, clean
text layer with a cosmetic prefix artifact, not an unusable one. Subagents were told to ignore this
numeric noise and extract only the real body text.

## Priority order chosen for this test run

1. `25 Dutch An Essential Grammar.pdf` — **extraction started this pass**, subagent-parallelized per
   `../00_Reference_Extraction_Spec.md`, three chunks: Chapters 1-3 (foundational), Chapter 16
   (Colloquial speech and writing — chosen specifically to test whether a grammar reference's own
   "colloquial register" chapter can surface `usage_tier` diversity beyond `core`, a gap flagged in
   both prior test runs), Chapter 22 (Diminutives — a distinctly Dutch derivational-morphology
   feature worth documenting for the typology guide).
2. `83 The Phonology of Dutch.pdf` and `10 Colloquial Dutch.pdf` — flagged for a future
   vision-reading pass.
3. Everything else — deferred.
