# Norwegian Phase 1 Extraction — Resume Point

**Started 2026-11-04 (overnight, unattended), per the user's explicit "full complete data-extraction
on the Scandinavian languages, continue through without me" instruction.** Scope is the "clearly in
scope" English-medium + native-literature pool from `00_Book_Triage_Catalog.md` §6-§7 (27 files) —
**NOT** the §5 "flagged for your ruling" Norwegian/German/Portuguese-medium-of-Norwegian pile (41
files, incl. three flagship slang/idiom candidates: `Hva vi sier`, `Katta i sekken`, `Sånn kan du si
det`). That pile is intentionally left unextracted pending the user's explicit ruling — same
standing "flag, don't guess" rule applied to Swedish's §5.

**If this file still says "IN PROGRESS" when you read it, the extraction was interrupted — check
disk state in `established/` before re-dispatching anything.**

## Status: FULLY COMPLETE (2026-11-04) — extraction, graphify, checklist, and cross-language
tracking docs all done. Not committed/pushed — awaiting the user's return per the standing
"ask before git operations" rule, not overridden by tonight's "continue without me" instruction.

## Wave plan (27 net in-scope files)

- [x] Wave 1 — DONE, files 001-003, verified 12-column + placeholder clean. Confirmed the two
      "Essential"/"Practical" grammar editions are the same Strandskogen work.
- [x] Wave 2 — DONE, files 004-006, verified 12-column + placeholder clean. Flagship findings:
      Haugen covers both Bokmål/Nynorsk with rich register-tag system (pop./dial./derog./fam.);
      Kirkeby is confirmed Bokmål-only, with S/RS/T/neds./vulg. register tags incl. a double-tagged
      ethnic slur the dictionary itself flags as offensive. Engelsk-Norsk Ordbok's "poor OCR" turned
      out to be genuine character-soup garbage, not a decodable cipher — handled via vision fallback.
- [x] Wave 3A — DONE, files 007-012 (with sub-splits), ~181,800 words, verified clean. Flagship
      finding: Colloquial Norwegian (011) has a full asterisk-marked vulgar/taboo set in Lesson 18
      (Hold kjeft!, Tosk!, Drittsekk!, Pokker/Fanden/Satan/Helvete!) plus a note on Norwegians using
      borrowed English obscenities unaware of their offensiveness; Teach Yourself Norwegian (010)
      has its own indexed "Slang words" heading.
- [x] Wave 3B — DONE, files 013-017, 111,775 words, verified clean (014's part 4 legitimately
      prose-only, no table). One source-status correction: Linguaphone pair + Så snakker vi Norsk
      turned out 100% vision-only despite the dispatch brief's text-layer assumption.
- [ ] Wave 4 — Tier 5 native literature (Norske folke-eventyr I/II, Jomfruen på Glassberget, Kurt
      blir grusom, Framtidslandet) + Historical Dictionary of Norway
- [x] Wave 4 — DONE, files 018-023, ~21,500 words, verified clean. Flagship: Kurt blir grusom
      (modern colloquial register), Framtidslandet's unmarked Bokmål/Nynorsk code-switching,
      Jomfruen på Glassberget correctly flagged as a 1909/1943-revised selection not raw folklore.
- [x] Structural verification of every file (12-column + placeholder check) — DONE, all 36 files,
      zero defects
- [x] `/graphify datasets/Norwegian` rebuild — DONE. 313 nodes, 320 edges, 6 hyperedges, 20
      communities. Health check clean: 0 missing/dangling/self-loop, 1 negligible undirected
      collapse out of 321 raw edges.
- [x] Extraction checklist created (`00_Extraction_Checklist.md`)
- [ ] Cross-language tracking docs updated — pending, batching with Swedish/Danish at the end
- [ ] Commit (do NOT push without asking — standing rule, not overridden by tonight's instruction)

## NORWEGIAN IS FULLY DONE (extraction + graphify). Moving to Danish next.

## Explicitly NOT extracted this pass

- §5's 41 Norwegian/German/Portuguese-medium-of-Norwegian files (incl. all 3 flagship slang/idiom
  candidates: `Hva vi sier - og hva vi mener`, `Katta i sekken og andre uttrykk`, `Sånn kan du si
  det`) — needs the user's explicit ruling first. Note: if this ruling goes against extraction, this
  project ends up with zero Nynorsk-standard material (per the triage's §8 note) — flag this
  specifically when the ruling is eventually sought.
- All excluded/non-content items per the triage catalog §1-§4 (incl. the 10-file Faroese
  misidentification in `04 Reading Books`, and `02 Gramatica Essencial de Noruegues` — a Portuguese
  third copy of an already-English-covered grammar).

## Incident log

- **2026-11-04, Wave 1.** One piece of handwritten marginalia found on `001` (Janus) and correctly
  excluded per standing policy. `002` (Practical Norwegian Grammar) has two genuine scan-gap page
  ranges, noted inline rather than silently skipped — review if a deeper pass on this source is ever
  wanted.
