# Romanian — Methodology Observations

**Status: confirmed.** Seventh language to reach full Phase 1 completion, after Serbian/Croatian/
Bosnian, Hungarian, Korean, Russian, Spanish, and Dutch. Unlike most prior languages, there was no
separate "test run" phase for Romanian — the triage and full extraction were both done in one
continuous push, since the corpus (5 files, 54MB) was small enough that a staged test-run/full-push
split wasn't warranted.

See `../datasets/Romanian/00_Book_Triage_Catalog.md` for the source-material survey.

---

## Log

### 2026-10-04 — Smallest corpus triaged yet, completed with zero disruptions

At 54MB across 5 real files (plus one incomplete torrent-download fragment, excluded), this is by
a wide margin the smallest corpus this project has triaged — smaller than Spanish's 189MB/133-file
corpus by more than 3x. Given the scale, Wave 1 (3 clean-text sources) and Wave 2 (2 vision-read
sources) were dispatched together in a single batch of 5 parallel subagents rather than staged in
two separate waves, and the entire extraction — plus a follow-up continuation for the one source
that didn't finish in its first dispatch — completed in roughly 2.5 hours with **zero usage-limit
disruptions**, the second language (after Spanish) to reach full Phase 1 completion without a
single session/weekly-limit interruption. This continues to support the working hypothesis from
Spanish's run that disruption frequency tracks corpus size/OCR-burden, not anything methodology-
specific.

### 2026-10-04 — A silent, non-decodable diacritic-dropping failure mode, distinct from prior ciphers

*Colloquial Romanian*'s PDF has a genuine text layer, but `pdftotext` silently drops all five
Romanian diacritics (ă, â, î, ș/ş, ț/ţ) rather than substituting them with a wrong-but-consistent
character — e.g. "Bună ziua" extracts as "Buna ziua," not as some decodable cipher character. This
is meaningfully different from every prior font-cipher/mojibake gotcha found across Hungarian,
Korean, and Russian (all of which involved *wrong* characters appearing, recoverable by decoding a
substitution pattern) — here the correct information is simply *absent*, recoverable only by
reconstructing from standard orthography using general language knowledge, not by any mechanical
decode. The dispatched subagent handled this correctly: it reconstructed diacritics from known
Romanian spelling and explicitly flagged the reconstruction (rather than silently presenting
reconstructed spelling as a verified transcription) in the file's opening note, which all sibling
chunk files of the same book then referenced. Worth promoting into
`00_Reference_Extraction_Spec.md` as a sixth text-layer failure category — distinct from the
existing "clean-with-cosmetic-artifact" and "garbled-OCR" categories, since neither of those
involves *silent character loss with no artifact at all*.

### 2026-10-04 — TOC-undercounting confirmed a third time running

*Introduction to Romanian* (the vision-read DJVU source) turned out to have 24 lessons, not the 21
initially estimated from a coarse page-count guess. This is the third language-scale push in a row
to catch this exact failure mode (after Dutch's Routledge Intensive Dutch Course and Hugo Advanced
Dutch both undercounting their own unit/lesson totals) — three independent confirmations across two
different languages now argue this should move from "known gotcha" to a **mandatory verification
step**: any vision-read or page-count-estimated source must have its actual unit/lesson/chapter
count confirmed against its own table of contents before a dispatch is marked complete, not merely
assumed from an initial page-count-derived guess. The subagent handled the discovery correctly —
caught it mid-dispatch, documented the correction inline, and continued extracting through the
actual Lesson XXIV rather than stopping at the originally-assumed XXI.

### 2026-10-04 — Graphify build clean on the first pass at small corpus scale

The 80-file corpus (78 established + 2 meta files) split into 4 semantic-extraction chunks, merged
with zero health-check warnings on the first pass — consistent with the Spanish/Dutch pattern that
fewer chunks correlates with cleaner first-pass health checks (4 chunks here, same order of
magnitude as Spanish's 3). The resulting 11-community label set skewed toward one-book-per-few-
communities given only 5 source books total, but still surfaced one genuine cross-book pattern: a
register-conditioned colloquial clipping/reduction mechanism (numeral `-sprezece`→`-șpe`, `nu`→`n-`,
`voi`→`oi`, demonstrative leveling) recurring independently across multiple of the 5 sources,
consistent with the kind of cross-source convergence this project's graphify layer has now
surfaced in every language from Spanish onward.

---

## Summary verdict for this push

Romanian confirms two things at once: first, that a genuinely small corpus (5 files) can complete
the full Phase 1 pipeline — triage, extraction, graphify rebuild, status docs — in a single
continuous session with no disruptions, the fastest full-language push in the project's history by
elapsed time. Second, that even at this small scale, the project's recurring failure modes still
surface: a *new* silent-diacritic-loss text-layer gotcha (distinct from every prior font-cipher
case) and a *third* independent TOC-undercounting discovery, both handled correctly by the
dispatched subagents without being told in advance to watch for them. Phase 1 is complete: 78
`established/` files, ~251,000 words, graphify clean on the first pass.
