# Tagalog — Ninth Language to Reach Phase 1 Completion

**Status: confirmed.** The first Austronesian-family language this project has extracted. Corpus
(25 files, 303MB) was staged on an external drive and copied into this project's standard
`source_reference/` tree before extraction began. Result: 41 `established/` files, ~256,000 words.

## A genuinely different morphological typology

Every prior language in this project (Serbian/Croatian/Bosnian, Hungarian, Korean, Russian,
Spanish, Dutch, Romanian, Japanese) was either fusional/inflecting or agglutinative in a way where
affixes stack linearly onto a stable root. Tagalog is neither: it's **non-concatenative and
verb-centered**. A single root takes a *different* affix per trigger/focus category rather than
stacking affixes — the same root (e.g. *luto* "cook") surfaces as 5+ distinct lexical forms
depending purely on which argument (actor, object, locative, instrumental/conveyance, beneficiary,
causative) is grammatically focused. Argument roles live entirely in invariant pre-nominal markers
plus verbal trigger affixes, not in noun case or word order. **New Tagalog-specific column
convention adopted project-wide for this language**: every verbal-affix vocabulary entry records
its trigger/focus category explicitly, parallel to how Japanese entries record script form.

Reduplication does at least four distinct grammatical jobs (verbal aspect, adjectival
intensification/plurality, habitual-adverb derivation, a formally distinct "moderative" function),
and recurs independently on non-verbal items too (sari-sari, halo-halo, turo-turo). The *ka-*
morpheme surfaces with at least four unrelated grammatical functions — flagged as an open question
for later mechanics work, not resolved here.

## A genuine sociolinguistic distinction found in a closing essay

Basic Tagalog for Foreigners' closing essay (Isagani R. Cruz, "Ano ang Pagkaiba ng Filipino sa
Tagalog?") gives a real, citable argument that "Filipino" and "Tagalog" are structurally distinct
varieties, with concrete divergence in exactly the -um-/mag- and i-/-an trigger choices the book
itself teaches as "Tagalog." Folded into the language's typology note rather than treated as a
one-off curiosity.

## A caught silent image-read failure

During the Making Out in Tagalog extraction, the dispatched subagent discovered partway through
that an earlier batch of image reads had silently failed — the tool returned "media removed:
request limit" placeholders instead of actual page content, while vocabulary notes had already
been drafted as if the pages had been seen. The subagent stopped, discarded everything unverified,
and re-read every single page of the 91-page book individually before recording anything. **Worth
flagging upstream**: large batched image-read calls in this harness can silently drop content
without raising an error — future vision-reading dispatches should watch for this rather than
trust a large batch returned cleanly.

## A session-limit interruption that looked worse than it was

The final Wave 2 dispatch (Teach Yourself Tagalog + Living Language Tagalog + Headstart Cultural
Notes) hit a session-limit reset mid-task and reported failure. Disk-state verification found that
both courses had actually completed in full before the interrupt — each file ended with the
standard closing boilerplate and covered every unit/lesson the source contained. Only the
Cultural Notes booklet, genuinely untouched, needed a follow-up dispatch. **Same lesson as
Japanese's Nihongo Notes incident, inverted**: check disk state before assuming a failure
notification means the work is actually incomplete, the same discipline applied in the other
direction.

## A three-way file-numbering collision

Two independent dispatch groups both used `003`, `004`, and `005` as output-file prefixes (the
Tagalog Grammar dispatch's own natural 5-file sequence `001`-`005`, vs. Headstart for the
Philippines, Diccionario Ingles-Español-Tagalog, and Making Out in Tagalog each independently
starting their own numbering at the same point). Resolved by keeping the Tagalog Grammar series
contiguous as `001`-`005` and renumbering the other three families to free slots (`010`-`013`),
fixing their internal cross-references with `sed` afterward. Consistent with how Japanese's `098`
collision was resolved earlier in the project — route the later-landing family to the next free
slot rather than disturbing the one already using the contested number.

## Flagship findings

- **Making Out in Tagalog** (382 rows) fully extracted — genuinely vulgar/intimate register
  preserved and tagged, not sanitized, with explicit synonym clusters kept intact (12 variants for
  one anatomical term rather than thinned out).
- A productive **English-loanword-plus-native-affixation slang mechanism** cross-confirmed across
  three independent sources (nag-eenjoy, nagsuicide, mag-aapologize, magseks, ka-deyt) — a single
  mechanism spanning registers from casual slang to tender/romantic language.
- A linked **face/politeness concept cluster** (utang na loob/pakikisama/amor propio/hiya) flagged
  as a strong Phase 3 mechanics candidate.
- A documented **two-era polysemy case** ("abuso," carrying two non-overlapping senses from two
  different borrowing eras) from a native-speaker essay critiquing English-root Filipinization in
  tabloid headlines (Advanced Tagalog Reader) — real primary-source evidence of borrowing/affix-
  compatibility mechanics, not a textbook's abstraction.
- A living generational word-clipping process (older rural ikámo/ikáko vs. younger sabi ko/sabi
  nilá), explicitly documented as such by Basic Tagalog for Foreigners' own Contractions appendix.

## Graphify

179 nodes, 309 edges, 11 communities, zero health-check issues on the first pass (no dangling/
missing/collapsed edges) — a markedly tighter, more cohesive structure than Japanese's fragmented
792-community graph, consistent with Tagalog's much smaller scale and the dense cross-referencing
in the trigger/focus grammar material (three independent sources converging on the same mechanism,
captured as a hyperedge).
