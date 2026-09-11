# Test Run: Korean — Methodology Observations

**Status: tentative** (per the standing policy in `00_Index.md` — not yet reviewed/confirmed).

**Context.** Korean is the third language to reach full Phase 1 completion, after
Serbian/Croatian/Bosnian and Hungarian, and the first from a non-Indo-European, non-Latin-script
family in this project. It is also one of the 43 Inner Tepenia GDD Gini-index high-priority
languages. This run followed the same full-triage-then-3-wave-extraction methodology validated on
SCB and Hungarian, with no scope redirects mid-run.

---

## Log

### 2026-09-10/11 — Full triage: subfoldered corpus, agglutinative typology confirmed

`source_reference/languages/Korean/` held 17 real files (~532MB) — 16 PDFs + 1 DJVU — spread across
top-level files and 3 subfolders (`Colloquial Korean/`, `Teach Yourself Korean/`, `The Sounds of
Korean - A Pronunciation Guide/`). This reconfirmed a known tooling gotcha from prior languages:
`find -printf '%f'` (basename only) misattributes numbered-prefix files inside subfolders to the
wrong title; `find -printf '%p'` (full relative path) is required. 6 of 17 files (~35%) had no
usable text layer — lower than SCB's ~56% and Hungarian's ~50%, but still a substantial minority,
reinforcing that OCR/vision-reading capacity should be budgeted as a default Phase 1 expectation,
not an exception.

Two duplicate/overlapping-title situations were flagged at triage and correctly resolved during
extraction: two "Colloquial Korean" editions in the same subfolder (143pp vs. 289pp — confirmed
during Wave 3 to be the exact same 1996 Routledge scan, not different editions, via
ISBN/TOC/content spot-check — zero duplicate content extracted, by design), and the
Basic/Intermediate/Continuing Korean trio vs. *Intermediate College Korean* (real core-grammar
overlap, handled via the non-redundant-supplement pattern).

Korean's typology was correctly flagged at triage as agglutinative — case, topic-marking,
honorifics, tense, mood, and connectives all stack as particles/suffixes onto a stem, comparable to
Hungarian/Japanese/Turkish — with an additional structural feature not seen in any prior language
this project has extracted: an elaborate **speech-level/honorific system woven into verb endings
themselves**, not just vocabulary choice. This was correctly predicted at triage to be a major
register-relevant finding, and it was — see below.

### 2026-09-10/11 — Three-wave extraction: 29 established/ files, ~400,000+ words

Extraction proceeded in the same 3-wave structure used for Hungarian (Wave 1: core grammar +
register-focused clean text; Wave 2: remaining clean-text supplements; Wave 3: vision-reading), with
user approval given once per wave (not blanket-approved up front the way Hungarian's Waves 2-3
were). Final state: 29 `established/` files, ~400,000+ words, across all 16 real source files
(one file — the "Colloquial Korean" short edition — correctly produced a duplicate-finding note
rather than a vocabulary table).

**Flagship cross-book finding:** the six-level speech/honorific system (문세영 style: plain,
intimate, familiar, semi-formal, polite, deferential) recurs independently across at least 5 of the
29 files — Jae Jung Song's *The Korean Language* (dedicated structural treatment), *Korean Grammar
for International Learners* (subject-honorification relative-status arithmetic — speaker→subject→
listener triangulation), *Using Korean* (contemporary-register showcase), and several of the course
books via honorific/plain lexical doublets. The graphify rebuild's God Nodes list independently
surfaced this as the #2 and #3 most-connected nodes in the entire 200-node graph, without being told
to look for it — matching the pattern seen in Dutch (register-focused chapters surfacing genuine
cross-chapter patterns unprompted) and Hungarian (te/maga/ön register system).

**Standout content find, distinct from the grammar corpus:** Martin/Lee/Chang's 962-page *A
Korean-English Dictionary* (1967) carries a genuinely rich lexicographic apparatus — explicit
register tags (`[VULGAR]/[SLANG]/[JOCULAR]/[DEROGATORY]/[DIAL.]/[ARCHAIC]` and variants across the
4 sampled sections) plus an "isotope/para-intensive" sound-symbolism notation system unique to this
source. Four representative samples were taken across the full 962 pages (the same discipline used
on Hungarian's oversized dictionaries) rather than full transcription. This content was correctly
kept in `established/` rather than routed to `language_corpus/Korean/`, since it is lexicographic
*annotation* (a structural finding about how the language marks register) rather than raw slang
corpus text — a slightly different judgment call than Hungarian's *Magyar Szlengszótár*, which
*was* routed to Phase 3 because it is itself a slang corpus, not a general dictionary with register
tags. This is a real content-type distinction worth carrying forward explicitly: **a general
dictionary with register annotation stays in Phase 1; a dedicated slang dictionary goes to Phase 3**,
even though both are technically "dictionaries."

### 2026-09-10/11 — Four distinct CJK/Hangul-specific PDF font-corruption mechanisms found

This is the most significant new methodology finding from this run, and the first time a
non-Latin-script language has been pushed through the pipeline. Four genuinely different corruption
mechanisms turned up across the 6 no-text-layer files, now promoted into
`datasets/00_Reference_Extraction_Spec.md` as a standing gotcha:

1. **Decodable fixed-offset codepoint cipher.** `real_codepoint = (extracted_codepoint + 36266) mod
   65536`. Cross-confirmed 4+ times across Routledge and Cambridge publisher titles — once this
   pattern is recognized, a whole title's "corrupted" text layer becomes mechanically recoverable
   without vision-reading at all, which is a real cost-saver if it generalizes to other languages'
   PDFs from the same publishers/scan pipelines.
2. **Undecodable CID-font corruption with no ToUnicode mapping at all.** No arithmetic trick
   recovers this — genuine vision-reading/OCR is required.
3. **Per-glyph bogus-CMap corruption across ~20 separate font subsets** in a single title
   (*Intermediate College Korean*) — each subset needing its own mapping, which is why this file
   ended up only partially covered (pp.1-224 of 376; pp.225-376 left as a known, flagged gap rather
   than forcing a rushed or silently-incomplete extraction).
4. **Legitimately Hangul-free, romanization-only source** (*In Flight Korean*) — not a corruption at
   all, a deliberate design choice for a phrasebook aimed at non-readers of Hangul. Worth
   distinguishing explicitly from the first three so a future extraction pass doesn't waste time
   trying to "fix" a source that was never broken.

**Open question, not yet resolved:** now that mechanism 1 is confirmed for *Intermediate Korean*
Units 16-25, should *Basic Korean* Units 1-15 (extracted earlier under a different, unresolved
corruption read) be re-decoded to check whether the same cipher applies? Flagged in the graphify
node itself rather than silently assumed — left open per the "don't fabricate cross-chunk
certainty" discipline.

### 2026-09-11 — Two incident types recurred from Hungarian's Wave 2, both handled the same way

**Orphaned background OCR job.** A subagent extracting *Intermediate College Korean* pt.2 launched
its own background OCR job across all 186 assigned pages and reported "completed" with a monitor
watching for results — but the harness's completion of that turn orphaned the job, leaving no
output file. Caught by explicit `ls`/file-existence verification rather than trusting the
"completed" status alone (the same discipline documented after SCB and Hungarian). Fixed by
redispatching with an explicit instruction to work in 10-15-page synchronous batches, writing
incrementally, never launching one giant background job — this instruction should be treated as a
standing default for all future vision-reading dispatches, not a one-off fix.

**Mass session-limit failures.** Multiple chunks failed simultaneously, twice, with "You've hit your
session limit" errors during Wave 2. Both times resolved by checking actual file existence on disk
(not trusting status alone) to determine which chunks genuinely needed retry vs. had already
produced real output, then redispatching only the genuinely-missing/incomplete ones once the
session limit reset. No content was lost or silently duplicated either time.

### 2026-09-11 — Graphify rebuild: clean health check, first non-Latin-script graph

Full corpus (29 `established/` files + 2 meta docs, ~364,308 words per `detect`) rebuilt across 4
parallel semantic-extraction chunks. Result: 200 nodes, 277 edges, 12 hyperedges, 13 communities.
Health-check diagnostic (`diagnose_extraction`) reported zero dangling-endpoint, missing-endpoint,
self-loop, or collapsed edges — the "subagents never fabricate cross-chunk edge targets" discipline
held cleanly for a 4th consecutive language rebuild. One chunk-1 node
(`korean_font_substitution_cipher_36266`) explicitly logged the Basic-Korean-re-decode open question
in its own rationale text rather than asserting an unverified cross-chunk edge — a good example of
the discipline working as intended rather than just avoiding errors by omission.

---

## Summary verdict for this test run

The triage-then-3-wave methodology and the subagent-parallelized dispatch pattern both continue to
generalize cleanly to a third language, including one with a materially different script and
typology from the first two. The two incident types that recurred (orphaned background jobs, mass
session-limit failures) are now expected, known-recoverable failure modes rather than surprises —
both were caught by the same file-existence-over-status-trust discipline within one dispatch cycle
each. The one genuinely new finding — CJK/Hangul font-cipher taxonomy — is Korean-specific but the
underlying lesson (PDF text-layer corruption can be a decodable arithmetic cipher, not just a hard
OCR wall) is worth checking for on any future non-Latin-script language before assuming vision-
reading is the only option.
