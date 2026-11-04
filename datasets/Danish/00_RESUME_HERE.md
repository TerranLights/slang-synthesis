# Danish Phase 1 Extraction — Resume Point

**Started 2026-11-04 (overnight, unattended), per the user's explicit "full complete data-extraction
on the Scandinavian languages, continue through without me" instruction.** Scope is the "clearly in
scope" English-medium + native-literature pool from `00_Book_Triage_Catalog.md` §6-§7 (10 files) +
the Grundtvig "Danish Popular Tales" epub section flagged in §9b — **NOT** the §5 "flagged for your
ruling" Danish-medium-of-Danish pile (16 files). Same standing "flag, don't guess" rule applied to
Swedish's §5 and Norwegian's §5. **Note: unlike Swedish/Norwegian, Danish's flagged §5 pile contains
NO flagship slang/idiom candidate at all — this is a real, flagged gap in the corpus regardless of
how the medium ruling goes.**

**If this file still says "IN PROGRESS" when you read it, the extraction was interrupted — check
disk state in `established/` before re-dispatching anything.**

## Status: FULLY COMPLETE (2026-11-04) — extraction, graphify, checklist, and cross-language
tracking docs all done. Not committed/pushed — awaiting the user's return per the standing
"ask before git operations" rule, not overridden by tonight's "continue without me" instruction.

## Wave plan (10 in-scope files + 1 epub section)

- [x] Wave 1 — DONE, files 001-004, verified 12-column + placeholder clean. 2nd edition of
      Essential Grammar confirmed to add nothing new over the 1st (cosmetic differences only).
- [x] Wave 2 — DONE, files 005-007, verified 12-column + placeholder clean. Flagship finding:
      Colloquial Danish Unit 18's "Disagreeing and swearing" section — an explicit, asterisk-marked
      coarse-vs-harmless swearword catalog, the richest register-annotated content in the whole
      Danish corpus. **Partial result on 006 (Teach Yourself Danish)**: the source turned out to
      have NO real usable text layer despite the triage catalog's "confirmed TEXT layer" note
      (pdftotext returns unstructured garbage across all 141 pages even though the underlying scan
      renders clean and legible — a new PDF gotcha, now logged in
      `00_Reference_Extraction_Spec.md`). Only a representative sample was captured (pronunciation
      guide, Unit 1, Unit 17/18 idiom clusters); Units 2-16 were left unextracted and are being
      completed now in a follow-up dispatch. Also corrected: `Danish Course Book.pdf` (007) is
      Pimsleur-branded, not Univerb — fixed in the triage catalog.
- [x] Wave 2b (follow-up) — DONE. Completed Teach Yourself Danish Units 2-16 via vision-reading.
      Method: contact-sheet scan of all 97 relevant PDF-page spreads (PDF pp. 15-111) first, to
      pin down every unit's exact start/end PDF page by direct inspection (no gaps/overlaps), then
      5 parallel vision-reading subagents each assigned one pre-verified 3-unit block. All 5 reported
      full (not sampled) coverage, zero marginalia, and passed the mandatory 12-column check; merged
      into `006_teach_yourself_danish.md` with zero column-count mismatches across all 1,586 data rows
      (verified independently after merge, not just trusting subagent self-reports). The file was also
      restructured from one flat vocabulary table into per-unit sections (Front matter + Units 1-18)
      for consistency with the new per-unit fragments — the old flat-table rows (Units 1 and 18) were
      split and refiled by unit, not rewritten. **Unit 17 remains partial** (only the gå/komme idiom
      cluster + a noun-mismatch note, pp. 224-225, from the original Wave 2 sample) — out of scope for
      this dispatch, flagged in the file's own scope note for a future close-out pass. Flagship finding
      corroborated twice independently: the book's own commentary explicitly labels `nok, da, dog, jo,
      nu, vel, vist` as a colloquial unstressed-discourse-particle system (pp. 99, 211-213) — the
      richest register-marked find in this book, alongside an explicit colloquial-vs-formal
      demonstrative-reinforcement note (den/det/de + noun + her/der vs. denne/dette/disse, p. 88) and
      the molbohistorier regional-dialect-ridicule folklore (pp. 113, 121-123).
- [x] Wave 3 — DONE, files 008-009, verified 12-column + placeholder clean. H.C. Andersen sampled
      (introduction + 5 famous tales); Grundtvig's "Danish Popular Tales" section isolated cleanly
      from its sibling Finnish/Icelandic sections, flagship finding the *mon(s) tro* idiom tale.
- [x] Wave 2 close-out — Unit 17 gap in Teach Yourself Danish fully closed (a concurrent full-book
      rewrite landed mid-dispatch and already covered it; verified independently, all 18 units now
      complete).
- [x] Structural verification of every file (12-column + placeholder check) — DONE, all 9 files,
      zero defects
- [x] `/graphify datasets/Danish` rebuild — DONE. 158 nodes, 42 edges, 3 hyperedges, 120
      communities. Health check PERFECTLY clean: zero missing/dangling/self-loop/collapsed edges
      of any kind — the cleanest result of any language graphify rebuild in this project to date.
- [x] Extraction checklist created (`00_Extraction_Checklist.md`)
- [ ] Cross-language tracking docs updated — pending, doing now for all three languages together
- [ ] Commit (do NOT push without asking — standing rule, not overridden by tonight's instruction)

## Explicitly NOT extracted this pass

- §5's 16 Danish-medium-of-Danish files (Lisbet Thorborg pronunciation series, Kirsten Ahlburg's
  Parlør dansk pair, Lise Bostrup's Aktivt/Intensivt dansk course, 4 standalone items incl. Jokeren
  and Dansk fonetik i teori og praksis) — needs the user's explicit ruling first. No flagship
  slang/idiom title exists among them either, unlike Swedish/Norwegian's flagged piles.
- All excluded/non-content items per the triage catalog §1-§4 (9 wrong-metalanguage, 2 tourism).
- "English Workbook Basic course" — part of the in-scope Univerb bundle structurally, but confirmed
  to have zero Danish-language content; not worth a dispatch.

## Incident log

(none yet)
