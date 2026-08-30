# Serbian, Croatian, Bosnian — Reference Material Triage Catalog

**Status: tentative — first-pass triage, part of the pipeline's first test run.** See
`methodology-observations/serbian_croatian_bosnian_test_run.md` for process notes.

**Purpose (per `ROADMAP.md` Phase 0):** survey what's actually in
`source_reference/languages/Serbian, Croatian, Bosnian/` before deep extraction — which titles are
highest-yield, and which are genuine text layers vs. image-only scans needing vision-based reading.

**Folder naming note:** the source folder is named `Serbian, Croatian, Bosnian` (with commas,
matching the census's national groupings). Filesystem-unsafe for our own folder names, so this
project's `language_corpus/` and `datasets/` folders use `Serbian_Croatian_Bosnian`
(underscore-joined) instead. Noted here so the naming choice isn't rediscovered later.

---

## Inventory

| File | Title | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|---|
| `01.Bosnian Croatian Serbian a Textbook With Exercises and Basic Grammar.pdf` | *Bosnian, Croatian, Serbian, a Textbook* (2nd ed.) — Ronelle Alexander & Ellen Elias-Bursać, U. Wisconsin Press, 2006/2010 | 531 | **Yes** (clean) | **Highest** | Explicitly tags vocabulary/dialogue lines with `[B]`/`[C]`/`[S]` variant markers throughout — directly usable for `attested_region`. First extraction target. |
| `11.Bosnian Croatian Serbian - A grammar & Social Commentary.pdf` | *Bosnian, Croatian, Serbian, a Grammar: With Sociolinguistic Commentary* — Ronelle Alexander, U. Wisconsin Press, 2006 | 489 | **Yes** (clean) | High | Companion volume to the Textbook above, same authorial team. "Sociolinguistic Commentary" framing may be directly useful for `usage_tier` distinctions later — worth checking its own TOC before starting. |
| `10.Serbian an essential grammar.pdf` | *Serbian: An Essential Grammar* — Routledge, 2005 | 337 | **Yes** (clean) | Medium | Serbian-only (not comparative), good for cross-checking Serbian-specific entries against the comparative textbook above. |
| `03.Colloquial Serbian and Croatian.pdf` | *Colloquial Serbian and Croatian* | 318 | **No** — sampled pp. 5-6, empty text layer | Medium (contingent on OCR/vision) | "Colloquial" framing makes this the most directly slang-adjacent of the reference set, but needs vision-based reading or OCR first. |
| `Colloquial Serbian/Colloquial Serbian.pdf` | *Colloquial Serbian* (separate title/edition from the one above) | 194 | **No** — sampled pp. 5-6, empty | Medium (contingent) | Distinct from `03.Colloquial Serbian and Croatian.pdf` — do not conflate; confirm actual title/author before extraction. |
| `12.Introduction to the Croatian and Serbian language.pdf` | *Introduction to the Croatian and Serbian Language* | 156 | **No** — sampled pp. 5-6, empty | Low-medium | Shorter intro text; lower priority than the two Alexander/Elias-Bursać volumes above. |
| `Teach Yourself Serbian/Teach Yourself Serbian.pdf` | *Teach Yourself Serbian* | 177 | **Garbled** — pdftotext returns OCR-corrupted symbol soup, not usable as-is | Low (needs vision reading, not OCR text) | The `.pdf`'s embedded text layer looks like a bad OCR pass, not a real text layer — treat as effectively image-only; needs vision-based reading like a scan, not `pdftotext`. |
| `29.Serbian Folk Tales.pdf` | *Vukove bajke* ("Vuk's Fairy Tales") | 240 | **No** — sampled, empty | Low for Phase 1 (grammar/vocab) — **flag for later**: folk tales are a strong candidate source for archaic/literary-tier vocabulary and possibly proto-slang idiom, worth returning to once the `literary`/`archaic` usage tiers need real examples. | Different genre from the grammar references — literary corpus, not grammar reference. |
| `01.Key to audio recordings.PDF` | Audio recordings key/index | 2 | Yes (trivial) | Low | Companion index for an audio course; no actual audio files present locally (`Teach Yourself Serbian audio/` folder contains only a `desktop.ini` placeholder, no real audio). Low standalone value. |

**Total: 9 real reference documents** (`desktop.ini` is Windows folder metadata, not content —
excluded).

## OCR/scan-handling flag (per `ROADMAP.md` Phase 1)

**5 of 9 files have no usable text layer**, roughly matching the ~55% rate this project should
expect to see repeated across other languages' reference material — worth tracking as a
methodology data point (see observations log). These need either OCR preprocessing or vision-based
page-by-page reading, both meaningfully more expensive per page than `pdftotext` extraction on the
two clean Alexander/Elias-Bursać volumes. Deferred for this test run's initial pass; flagged here
so a return pass has the list ready.

## Priority order chosen for this test run

1. `01.Bosnian Croatian Serbian a Textbook...` (clean text, explicit B/C/S tagging) — **extraction
   started this pass**
2. `11.Bosnian Croatian Serbian - A grammar & Social Commentary.pdf` (clean text, companion volume)
   — next
3. `10.Serbian an essential grammar.pdf` (clean text, single-variant cross-check)
4. Everything else — deferred pending OCR/vision-reading approach decision

## Tooling gotcha found during this triage (methodology note, see observations log)

`find ... -exec ls -lh {} \; | awk '{print $5, $NF}'` used during earlier scoping (before this
catalog existed) silently truncated every multi-word filename to its last space-separated token —
`"01.Bosnian Croatian Serbian a Textbook With Exercises and Basic Grammar.pdf"` printed as just
`"Grammar.pdf"`. This produced a materially wrong impression of what was in this folder before the
real triage pass corrected it. See the observations log for the full note — this is a reusable
lesson for triaging any other language's folder.
