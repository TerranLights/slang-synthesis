# Roadmap

**Purpose.** The reference material alone (`source_reference/`) is 70GB+ across 40+ languages —
not a "do it all at once" task. This roadmap sequences the work into phases and flags concerns
that only become obvious partway in, so effort goes where it actually pays off instead of grinding
uniformly through everything.

**Status legend:** `not started` · `in progress` · `complete`. Update this file's phase statuses as
work actually begins/finishes — same discipline as the per-language indexes.

**See also `methodology-observations/`** — a running record of findings about the *methodology
itself* (schema gaps, tooling gotchas, open process questions), separate from this file's
phase/task tracking. Check it before starting work on a phase that already has entries.

**See also `LANGUAGE_INDEX.md`** — the master roster of every language this project covers or will
cover, organized by language family, with the highest-priority languages (the 43 nations
represented in the Inner Tepenia GDD sci-fi setting's own Gini-adjusted census) flagged. Use it
alongside Phase 0.5 below to decide which language to work on next.

---

## Phase 0 — Triage pass (not full extraction)

**Status: in progress — Serbian/Croatian/Bosnian (test-run language) done, tentative.** See
`datasets/Serbian_Croatian_Bosnian/00_Book_Triage_Catalog.md` and
`methodology-observations/serbian_croatian_bosnian_test_run.md`. Finding worth flagging here: of 9
real reference files triaged, only 3 had a clean, usable text layer — **roughly 56% needed
OCR/vision-based reading**, a much higher rate than "some of the files" implied below. If this
generalizes, OCR/vision-reading capacity should be budgeted as a default expectation for Phase 1,
not an occasional exception.

Before deep-extracting any single book, survey what's actually in each
`source_reference/languages/<Language>/` folder: which titles look highest-yield (a real grammar >
a phrasebook > an audio-course companion booklet), and — critically — **which are genuine text
layers vs. image-only scans** that will need vision-based reading rather than text extraction (some
of the `.djvu` files especially are likely to be scans; the Inner Tepenia GDD repo hit this with an
image-only PDF that had to be read visually).

**Also actively check for corpus-type material hiding among the grammar references — don't assume a
"reference" folder contains only Phase 1 material.** Confirmed during the Hungarian test run: a
Hungarian slang dictionary (`Magyar Szlengszótár.pdf`) was found sitting directly in
`source_reference/languages/Hungarian/`, not in `language_corpus/`. The Phase 1 (`source_reference/`)
vs. Phase 2 (`language_corpus/`) distinction is about *content type* (grammar/vocab reference vs.
slang corpus), not strictly about which folder a file physically sits in — a title containing words
like "slang," "colloquial," "argot," or the local-language equivalent is worth flagging during
triage even though it lives among grammar books, since its eventual extraction belongs conceptually
in `language_corpus/<Language>/`. Don't rely on this being a repeatable stroke of luck — it may not
recur for most languages, but the triage pass should still look for it every time.

**Output:** a `Book_TOC_Master_Reference.md`-style catalog per language — what exists, format,
scan-vs-text-layer status, and a rough priority call — *before* any checklist work in
`datasets/<Language>/` or `language_corpus/<Language>/` begins. This is cheap and prevents burning
hours deep-extracting a book that turns out low-value.

**New sub-concern, discovered 2026-10-26: check removable/external media, not just
`source_reference/`, before calling a language's material inventory complete.** A full sweep of
the external drive at `/media/kuroskalacs/Home-Theater/w-lang/` (27 language folders, ~70GB) found
undocumented supplementary stashes for languages already in `source_reference/` (Serbian/Croatian/
Bosnian, Hungarian, Swedish, Slovenian, Cantonese, Danish, Icelandic, Kazakh, Mongolian, Tibetan,
Irish, Swahili), closed or softened 9 of the 14 GINI-priority acquisition gaps (Portuguese,
Norwegian, Polish, Ukrainian, Bulgarian, Indonesian, Malay, Thai, Vietnamese all have real material
there, just not yet staged), and surfaced 6 languages never before in the project's roster at all
(Arabic, Hindi-Urdu, Catalan, Nepali, Cambodian/Khmer, Basque). Full detail in `LANGUAGE_INDEX.md`'s
"External-drive sweep, 2026-10-26" section. This was only caught because Korean's "complete" status
got questioned directly — **before trusting any language's status as final, check whether its
external-drive folder has been triaged, not just its in-repo one.**

## Phase 0.5 — Language priority tiering

**Status: partially resolved as of 2026-09-09 — see `LANGUAGE_INDEX.md`.** The real-world
language → in-universe-relevance mapping this phase needed now exists in usable form: the Inner
Tepenia GDD repo's own worldbuilding census (`Upper_Earth_Immigration_Composition.md`'s
Gini-adjusted effective-population table) names 43 real-world nations that actually populate the
sci-fi setting's Antarctic exile cities. `LANGUAGE_INDEX.md` maps those 43 nations to ~18 distinct
languages (several nations sharing a language, e.g. English/Spanish) and flags them 🔴 HIGH
PRIORITY across the full language roster — this is Tier 1 in all but name.

**Not fully resolved:** the GINI census gives population *weight*, not fine-grained per-city or
per-faction narrative relevance beyond "these are the real nations represented" — and 14 of the 43
nations' primary languages have no `source_reference/` material yet (see `LANGUAGE_INDEX.md`'s gap
list), so acquisition is still a prerequisite for those before Phase 1 can start on them. Tiering
*within* the 43 (which of them matters most *first*) and tiering the ~40 remaining non-GINI
languages both remain open — do incrementally (tier the next language right before starting it)
rather than all up front.

## Phase 1 — Reference extraction (grammar/vocab)

**Status: Phase 1 complete for Serbian/Croatian/Bosnian — the first language in the entire
40+-language project to reach this milestone.** All 9 real reference documents have been fully
extracted: 115 `established/` files, ~850,000 words, covering the flagship BCS textbook, its
sociolinguistic-commentary and grammar companion volumes, Hammond's essential grammar, Magner's
full 30-lesson course, both Hawkesworth "Colloquial" volumes, the Serbian Folk Tales anthology, and
Norris & Ribnikar's Teach Yourself Serbian — see `datasets/Serbian_Croatian_Bosnian/established/`,
`00_Extraction_Checklist.md`, and the methodology-observations log for full detail. The `/graphify`
knowledge graph over the full corpus stands at 453 nodes / 561 edges / 29 communities with zero
dangling or missing edges. **The two open questions below, raised early in this pass, are now
effectively answered by the completed run: exhaustive per-book extraction plus subagent-parallelized
dispatch (with wave-based chunking under the 20-concurrent-agent cap) proved tractable across an
entire language's reference corpus, not just a single lesson.**

**Hungarian reached the same milestone next — the second language in the project to complete
Phase 1.** Its reference folder was an order of magnitude larger and messier than SCB's (131 files/
2.6GB with two grab-bag subfolders mixing real reference material into travel guides, fiction, and
comics), so a full triage-and-dedup pass was run first (see `datasets/Hungarian/
00_Book_Triage_Catalog.md`) before extraction proceeded in three priority waves. Result: 53
`established/` files, ~475,000 words, covering 16 real reference sources including two proverb/
idiom dictionaries, the two-volume FSI Basic Hungarian course, a 19th-century grammar (attested-era
contrast against the modern one), an 1,324-page compiled coursebook (handled via representative
sampling, the same discipline used on oversized dictionaries), and the dedicated Hungarian slang
dictionary (*Magyar Szlengszótár*, fully sampled A-Z and routed to `language_corpus/Hungarian/`
rather than `established/`, per the Phase 1/Phase 2 content-type boundary this language's earlier
triage pass first surfaced). The `/graphify` graph over the full corpus stands at 229 nodes / 332
edges / 10 communities with zero dangling/missing edges. **This run reconfirmed the exhaustive-
extraction-plus-subagent-dispatch approach at a genuinely messier, larger scale than SCB, and
surfaced a new gotcha: an extraction subagent independently running `graphify update` from the
wrong working directory can corrupt the repo-root graph — now an explicit prohibition in
`datasets/00_Reference_Extraction_Spec.md`.**

**Korean reached the same milestone third — the third language in the project to complete Phase 1,
and the first from a non-Indo-European, non-Latin-script family.** Its reference folder held 17
files (~532MB) nested across 3 subfolders, with 6 of 17 (~35%) lacking a usable text layer —
consistent with the OCR/vision-reading burden now expected as the norm rather than the exception.
Result: 29 `established/` files, ~400,000+ words, covering the Basic/Intermediate/Continuing Korean
graded grammar series, Choo & Kwak's *Using Korean: A Guide to Contemporary Usage* (the strongest
register/slang-showcase source), Jae Jung Song's *The Korean Language* (the six-level speech-system
flagship source), a dedicated pronunciation/phonology reference, five vision-read course books, and
four representative samples from Martin/Lee/Chang's 962-page *A Korean-English Dictionary* (whose
lexicographic register-tag apparatus — `[VULGAR]/[SLANG]/[JOCULAR]/[DEROGATORY]/[DIAL.]/[ARCHAIC]`
— and isotope/para-intensive sound-symbolism notation turned out to be a standout structural find).
The `/graphify` graph over the full corpus stands at 200 nodes / 277 edges / 13 communities with
zero dangling/missing/collapsed edges. Two known, explicitly-documented non-blocking gaps remain:
*Intermediate College Korean* pp.225-376 and *Elementary Korean* pp.51-195, both left open after
honest partial-completion reporting flagged them mid-run rather than silently under-covering. **This
run surfaced four distinct CJK/Hangul-specific PDF font-corruption mechanisms** (a decodable
`+36266` fixed-offset codepoint cipher confirmed across multiple publishers, undecodable CID-font
corruption with no ToUnicode mapping, per-glyph bogus-CMap corruption across ~20 font subsets in one
title, and a legitimately Hangul-free romanization-only source that is a design choice rather than a
corruption) — all four promoted into `datasets/00_Reference_Extraction_Spec.md` as a standing
gotcha for future non-Latin-script languages.

**Russian reached the same milestone fourth — the fourth language to complete Phase 1, and by a
wide margin the largest single-language corpus this project has processed.** Its reference folder
held 204 files (~3.6GB) with ~75% scanned image-only (the highest proportion of any language
triaged so far, well above SCB/Hungarian/Korean's 35-56%). Result: 281 `established/` files,
~1,360,000 words — more than the next three completed languages combined — covering the full core
grammar-reference set (Wade, Timberlake, Schaum's, Dunn & Khairov, and a dozen more), the register
flagship (*Using Russian: A Guide to Contemporary Usage*), the slang flagship (*Streetwise
Russian*, ~340 entries with a documented criminal/prison-argot throughline), a dedicated slang
dictionary (*Dermo! The Real Russian Tolstoi Never Used*, correctly routed to
`language_corpus/Russian/` rather than `established/` per the Hungarian slang-dictionary precedent),
and dozens of course books, specialist grammars, and thematic readers. The `/graphify` graph over
the full corpus stands at 769 nodes / 894 edges / 42 communities with zero dangling/missing/
collapsed edges after one fabricated cross-chunk edge (out of 895, found via the standard health
check) was identified and removed before commit. **This run recovered cleanly from three separate
usage-limit disruptions** (two session-limit events, one larger weekly-limit event affecting up to
6 of 8 chunks in a single batch) using the same disk-state-verification-before-redispatch discipline
established in Korean's Wave 2 — in every case, actual file contents on disk were checked before
assuming a "failed" chunk needed full redispatch, and several turned out to be genuinely complete
despite the failure tag. **A record eight distinct Cyrillic PDF-corruption gotchas were found and
promoted into `datasets/00_Reference_Extraction_Spec.md`** — keyboard-layout ciphers, cp1251-as-
latin1 mojibake, stress-mark-only corruption, single-letter-pair homoglyph swaps, non-decodable
many-to-one OCR garbling, and (new to Russian) target-language content embedded as per-word/per-page
raster images inside an otherwise-genuine text layer. Known, explicitly-flagged non-blocking gaps:
*Teach Yourself Russian* (Units 14-20 of 20), *Everything in its Time* (Section 12 onward),
*Russian Grammar in Literary Contexts* (Units 9-25 of 25), *Rossiya den segodnyashniy* (Chapters
11-25 of 25), and the 20-volume Сказочник folk-tale series (deliberately sampled at 3 of 20 volumes
per the triage decision, not a gap).

**Spanish reached the same milestone fifth — the fifth language to complete Phase 1, and the first
one of the 5 GINI-represented Spanish-speaking nations (Spain, Mexico, Argentina, Chile, Uruguay,
no dominance hierarchy among them) to have its reference material extracted.** Its reference folder
was by far the smallest and cleanest of any language yet (189MB, 133 PDF files + 1 EPUB, only 3 of
~15 distinct sources lacking a text layer) — a useful contrast point after Russian's unusually messy
3.6GB corpus. Result: 59 `established/` files, ~350,000 words, covering two Colloquial Spanish of
Latin America course books (one with a fully worked voseo paradigm), Madrigal's Magic Key to
Spanish (a 740-page mnemonic-based grammar with an explicit Mexican-slang appendix), five Practice
Makes Perfect references, Easy Spanish Step-by-Step, Schaum's Outline of Spanish Grammar, and all
three levels of *Learning Spanish Like Crazy* — a course with dedicated built-in insult/vulgar-
language lessons and two dedicated slang lessons, the register flagship for this language. The
`/graphify` graph over the full corpus stands at 132 nodes / 156 edges / 31 communities with zero
dangling/missing/collapsed edges on the first pass. **A genuine cross-source convergence emerged**:
the Spanish subjunctive mood — missing from every early-extracted source — turned out to be
independently taught as a major structural feature by three unrelated pedagogical lineages within
the same corpus, exactly the kind of structural confirmation later synthesis work should weight
heavily. One known, explicitly-flagged non-blocking gap remains: *Practice Makes Perfect Spanish
Vocabulary* (Units 4-10 of 10, an unusually vocabulary-dense ~10,000-word book).

**Spanish's full 16GB external-drive stash was extracted 2026-10-30 — nearly tripling the corpus
in a single continuous run of 5 waves (S1 + 2-5), ~104 net-new files across 19 parallel dispatch
groups total, all individually structurally verified by the orchestrating session rather than
trusted on self-report alone.** Wave S1 finished the Tier 1 reference-grammar/linguistics cluster;
Wave 2 covered phrasebooks, idiom dictionaries, and two large dictionary samples (McGraw-Hill's
1,831pp encyclopedic dictionary, a synonym/antonym/paronym dictionary); Wave 3 covered grammar
workbooks and verb references, including a 3-level Spanish-medium graded series (*Uso de la
Gramática Española*) whose subjunctive-mastery progression was tracked explicitly across levels;
Wave 4 covered vocabulary dictionaries and intermediate/advanced courses; Wave 5 took a
deliberately selective (not exhaustive) pass over beginner courses and graded fiction readers,
using a different extraction methodology for the readers — pedagogical-apparatus-first, with thin
honest writeups for the one reader (a plain, unannotated *El Principito* translation) that had none.
Flagship finds from the expansion: three independent sources converging on *concha*'s
Southern-Cone-specific taboo status; the *coger*/*chingar* regional taboo-inversion pattern
confirmed repeatedly across phrasebooks, dictionaries, and course books; the full *vosotros*
paradigm corroborated across three sources as the standout Peninsular-vs-Latin-America grammatical
marker; a 16th-century *La Celestina* student edition confirmed as genuine annotated
archaic-register content, distinct from the modern-Spanish material everywhere else in the corpus;
an explicit reggaetón jerga glossary (pichaera, guerlas, guillao, perrear, rankeao) found inside a
graded reader; and a confirmed 100%-duplicate finding (a standalone business glossary re-published
word-for-word inside a later textbook) honestly documented with zero new content extracted, rather
than silently padded. Several dispatched agents self-caught and fixed real bugs before reporting
(an abandoned 6-column table header reverting to an old convention, uppercase node IDs during the
later graphify rebuild, a misattributed cross-reference) — each independently re-verified by the
orchestrating session, not just trusted. The `/graphify` graph was fully rebuilt over the new
175-file, ~1,360,000-word corpus: 2,326 nodes, 2,596 edges, 255 communities (92 individually
labeled), with only 4 dangling and 2 collapsed edges out of 2,602 raw — honestly-flagged
low-confidence cross-chunk references from the 30-chunk extraction dispatch, negligible and
consistent with every other language's graph in this project.

**Dutch reached Phase 1 completion sixth**, continuing from an earlier partial test run (3
`established/` files from one book) rather than starting from scratch — the full 84-file/2.1GB
corpus was re-triaged from scratch first, since the original pass had only spot-checked "top
candidates." Result: 167 `established/` files, ~813,000 words, covering all 13 Wave 1 clean-text
sources and all 16 Wave 2 vision-read sources identified in the full triage. Two session-limit
interruptions during Wave 2 left partial files with explicit continuation notes rather than lost
work — both were fully closed via targeted follow-up dispatches, continuing from the exact page/
lesson boundary each partial file's own closing note recorded, rather than re-extracting from
scratch. The `/graphify` graph over the full corpus stands at 678 nodes / 837 edges / 50
communities with zero dangling/missing/collapsed edges on the first pass. Register/slang
highlights: an explicit youth-slang register list and a four-tier toilet-terminology formality
ladder (both from *Colloquial Dutch 2*), a Belgenmop/Hollandermop regional joke tradition, and a
graph-surfaced "unstressed material erosion" pattern (apostrophe elision, z'n/d'r contractions,
separable-verb stress-shift) found independently across multiple unrelated sources. One known,
explicitly-flagged non-blocking gap remains: *Linguaphone Cursus Nederlands*'s own vocabulary
booklet, lessons 34-50 plus its phonology appendix and closing dictionaries.

**Romanian reached Phase 1 completion seventh — the smallest corpus the project has triaged yet**
(5 real files, 54MB). Completed in a single continuous push with zero usage-limit disruptions, the
second language (after Spanish) to do so. Result: 78 `established/` files, ~251,000 words,
covering all 5 in-scope sources: *Colloquial Romanian* (flagship case-system coverage — the full
nominative/accusative and genitive/dative syncretism, postposed definite article, `pe`-marked
differential object marking), *Romanian: An Essential Grammar*, an academic grammar reference
(numerals as its signature strength), *Teach Yourself Romanian*, and *Introduction to Romanian*
(vision-read from a DJVU scan that turned out to have 24 lessons, not the 21 initially estimated).
The `/graphify` graph stands at 290 nodes / 416 edges / 11 communities with zero dangling/missing/
collapsed edges on the first pass. Register/slang highlights: explicit "(very coll.)"/"(slang)"
source tags on *cică* (hearsay marker), *nasol*/*mișto*, and *șmecher*; numeral clipping
(`-sprezece`→`-șpe`); taboo-avoidance naming (*cel cu coarne* for "devil"); a living dialectal
simple-perfect tense in Oltenia/Banat; and a three-way register-stratified future-tense system (`o
să` / `am să` / `voi`).

**Japanese reached Phase 1 completion eighth — by far the largest corpus this project has
processed** (619 source files, 8.9GB), and the first language where the large majority of in-scope
material had no usable text layer at all (CJK OCR defeats text extraction far more consistently
than any Latin/Cyrillic-script language handled so far), so the 6 extraction waves were organized
by content category rather than by text-layer status. Result: 420 `established/` files, ~1,840,000
words, covering Writing System foundations, Grammar/Workbooks/Usage, Audio Courses/Textbooks,
Vocabulary/Dictionaries, tiered Children's Books/Readers, and Society/Culture gems + remaining
course material. Recovered cleanly from multiple session-limit interruptions via disk-state
verification, including one case where a subagent's own self-reported "fully complete" claim was
false (a Nihongo Notes volume genuinely incomplete despite its own closing note claiming full
coverage) — caught only by cross-checking volume/page citation tags, not by trusting the
self-report. Flagship slang sources fully extracted: Dirty Japanese/Zakennayo! (~1,218 rows) and
Making Out In Japanese/sequel (~1,677 rows), both with explicit gendered-register tagging and a
documented Kantō/Kansai regional split on vulgar vocabulary (omanko/omeko, baka/aho); the Kinki
region dialect dictionary (~265 rows) found the Kyoto -haru honorific losing its gender-skew
through overuse and a systematic Wakayama z→d sound shift; Womansword documented a repeatable
euphemism-treadmill mechanism (BG→OL, torukojo→sopu redi). The `/graphify` graph stands at 2,302
nodes / 2,303 edges / 792 communities (80 substantively labeled) — one semantic-extraction chunk
initially over-extracted at vocabulary-row granularity (3,297 nodes for 22 files) and was redone to
match the project's node-density convention; a minor health-check note (18 dangling cross-document
edges, ~31 collapsed duplicates out of 2,352) was surfaced honestly rather than hidden, as expected
noise from 20 independently-dispatched extraction chunks.

**Tagalog reached Phase 1 completion ninth — the first Austronesian-family language this project
has extracted.** Corpus (25 files, 303MB) was staged on an external drive and copied into this
project's standard `source_reference/` tree before extraction began. Result: 41 `established/`
files, ~256,000 words, covering all 5 Wave 1 clean-text and 9 Wave 2 vision-read sources identified
in Phase 0 triage. Every verbal-affix vocabulary entry carries an explicit trigger/focus (voice)
tag — actor/object/locative/instrumental/beneficiary/causative — the core grammatical mechanism
distinguishing Tagalog's non-concatenative, verb-centered morphosyntax from every agglutinative
language this project has handled before (a single root like *luto* "cook" surfaces as 5+ distinct
lexical forms depending purely on which argument is grammatically focused). Flagship slang source
*Making Out in Tagalog* fully extracted (382 rows, genuinely vulgar/intimate register preserved and
tagged, not sanitized — a mid-extraction silent image-read failure was caught and the entire book
re-verified page-by-page before finalizing). Notable cross-source findings: a productive
English-loanword-plus-native-affixation slang mechanism cross-confirmed across three independent
sources (nag-eenjoy, nagsuicide, mag-aapologize); a linked face/politeness concept cluster (utang
na loob/pakikisama/amor propio/hiya); a genuine sociolinguistic argument distinguishing "Filipino"
from "Tagalog" as structurally distinct varieties tied to trigger-affix choice; a documented
two-era polysemy case ("abuso") from a native-speaker essay on English-root Filipinization. The
`/graphify` graph stands at 179 nodes / 309 edges / 11 communities with zero dangling/missing/
collapsed edges on the first pass. Recovered cleanly from a session-limit interruption via
disk-state verification (two courses had actually completed in full before the interrupt, contrary
to the failure notification); resolved a three-way file-numbering collision between two
independent dispatch groups by renumbering to free slots.

**English reached Phase 1 completion tenth — driven by the sibling `TepenianHawaiian` project's
need for English as a required structural donor to its English/Japanese/Tagalog pidgin-origin
conlang, and the only one of those three not already done.** Never triaged before this pass. Two
major style authorities (*The Chicago Manual of Style*, 16th ed.; *New Oxford Style Manual*) were
added to the source folder mid-triage by the developer and became the highest-priority sources —
CMOS's chapter 5 "Grammar and Usage" is written by Bryan A. Garner, directly resolving an open
"favor American English" request, and Oxford's chapter 21 "US and British English" turned out to
be the project's single richest explicit American/British register-contrast source (every one of
its ~228 entries individually tagged by variety rather than one blanket region tag). Result: 259
`established/` files across three waves — Wave 0 (CMOS's and Oxford's language-content chapters,
55 chunks), the original 21-file ESL collection plus the 1,446-page *Grammar of English Grammars*
(1851) and the Concise Anglo-Saxon Dictionary, and the full 18-file Old English pack (76 more
chunks). One source, `Comprehensive Grammar[A4].pdf`, turned out on inspection to be a misfiled
Yip & Rimmington *Chinese: A Comprehensive Grammar* despite its English-sounding filename and
chapter titles — excluded, not extracted, the same metalanguage-contamination discipline every
other language's triage has needed at least once. A new PDF-encoding gotcha recurred across 15+ of
the 55 Wave 0 chunks and was promoted to the shared extraction spec: CMOS's PDF renders non-ASCII
characters as UTF-8-read-as-Latin-1 mojibake, always recoverable from surrounding context. The
`/graphify` graph (first ever for this language) stands at 3,517 nodes / 4,187 edges / 252
communities, built from 24 independently-dispatched extraction chunks — the densest Old English
material needed splitting down to 5-6 files per chunk after repeatedly hitting the model's
64,000-output-token response cap at larger sizes, a new scaling gotcha for any future
oversized/dense-content language. One collapsed (undirected) edge out of 4,188 raw edges, the
usual negligible noise from many independently-dispatched chunks. Flagship register/slang finds:
a dedicated 2006 primary-source chapter deliberately mixing period American slang with authorial
glosses (*ain't*, *rad*, *phat*, *the bee's knees*, *411*); Goold Brown's own 1851 list of terms he
flagged as improper/slang, the project's earliest dated English slang data point; and — directly
relevant to the sibling Hawaiian project — a 9-way parallel comparison of the same biblical passage
tracked from Old English through to Bislama, a real English-lexifier pidgin, inside *From Old
English to Standard English*.

**Korean's known external-drive stash (triaged 2026-10-19, third language to reach Phase 1 — see
above) was fully extracted 2026-10-29, closing out Korean's last open expansion.** 35 originally-
planned items grew to 40 new `established/` files (`030`-`069`) after several books split into
multiple parts — either because a source was too large for one file, or because a dispatched
agent's own internal sub-forking went out of scope and the orchestrator had to resolve a numbering
collision (this happened four separate times across the six dispatch waves, K1-K6, plus one agent
that died silently with no completion/failure notification at all and had to be resumed from its
surviving partial output — the full incident-by-incident account lives in
`datasets/Korean/00_RESUME_HERE.md`). Korean's `established/` corpus now stands at 69 files total,
~1,217,000 words. Flagship/register finds: a genuine North Korean (DPRK) government-published
textbook with the 두음법칙 (initial-sound-law) non-application as its standout systematic North/
South contrast; a 1984 Defense Language Institute course carrying the project's first full
US-military register (rank ladder, named installations); a complete 24-entry body-part idiom
curriculum cross-verified against its own source index; and a first systematic hanja (Sino-Korean
character) curriculum for this language. The `/graphify` graph grew from Phase 1's 200 nodes/277
edges/13 communities to 845 nodes/957 edges/80 communities, zero dangling/missing/collapsed edges
on the health check, built from 7 independently-dispatched chunks under the same node-density
discipline (concepts/mechanisms, never one node per vocabulary-table row) used on every other
language's graph.

**Hawaiian (ʻŌlelo Hawaiʻi) reached Phase 1 completion 2026-10-30 — the first non-GINI-census
language this project has extracted, done entirely to close a long-open acquisition gap for the
sibling `TepenianHawaiian` project's foundation-vocabulary needs.** The user sourced the exact two
titles that gap had been waiting on — Pukui & Elbert's *Hawaiian Dictionary* (Revised and Enlarged
Edition, 1986, 3,695pp, clean text layer) and their *Hawaiian Grammar* (1979/2001, 214pp,
vision-read) — and triage-to-extraction ran in a single session the same day. `established/` has
11 files (~96,000 words): the Grammar's full 12 chapters across 4 files, plus a deliberate
representative sample of the Dictionary across 6 files (Hawaiian-English and English-Hawaiian
directions, plus the front-matter abbreviation key) — at 3,695 pages this is by far the largest
dictionary this project has sampled, roughly 4x the previous largest. Flagship finds: *kake*, a
genuine chiefly secret/play-language cryptolect cognate with Marquesan "stammer"; the dictionary's
own canonical 11-item "slang" example list, independently cross-confirmed by re-tags elsewhere in
the text; named island/district-specific insult epithets, one tied to a legendary sorcerer; the
full Polynesian a/o possessive-class system worked through with 13 minimal pairs and a genuine
cross-chapter syntactic override (fronting via the particle *ai* forces a-class regardless of a
noun's normal lexical class); and the sole explicit "(vulgar)" tag in the whole Grammar landing on
*ʻŌkole maluna*. A clean negative finding, documented rather than silently skipped: the
dictionary's own table of contents lists two appendices (a gods/demigods glossary, a given-names
list) that an exhaustive multi-angle search confirmed are genuinely absent from this particular
digitized edition. The `/graphify` graph (first ever for this language) stands at 232 nodes, 271
edges, 31 communities, zero dangling/missing/collapsed edges.

**Ilocano reached Phase 1 completion 2026-10-30 — the twelfth language in the project, extracted
to serve the sibling `TepenianHawaiian` project's documented interest in real-world Ilocano-Hawaiʻi
plantation-era contact history.** Triage was already complete from an earlier session; the two
needed source files (Carl Rubino's 1997 UCSB dissertation *A Reference Grammar of Ilocano*, 549pp,
no text layer, and his 2000 UH Press *Ilocano Dictionary and Grammar*, 868pp, real OCR text layer)
were staged and extracted the same day. `established/` has 19 files (~275,700 words): the
dissertation's all 18 chapters plus front/back matter vision-read in full across 12 files, and the
dictionary's pedagogical Grammar Outline vision-read in full across 2 files plus a representative
sample of its Ilocano-English/English-Ilocano dictionary body across 5 files. A genuine full-corpus
seam audit — prompted by several dispatched agents independently discovering the true PDF-to-printed
page offset (+25, not the dispatch's assumed +26) — caught 8 one-page content gaps that had fallen
into the cracks between consecutive extraction files at exactly the chapters' own opening pages
(each neighboring file recognized the next chapter's first page and excluded it as out of scope,
leaving nobody responsible for it); all 8 were individually re-verified against the source PDF and
patched directly, documented in full in `datasets/Ilocano/00_RESUME_HERE.md`'s seam-audit table.
Flagship finds: the *maki-* comitative verb cluster (seven named sub-derivations with no
counterpart yet found in this project's Tagalog trigger-system material); reduplication
multiplexing five distinct grammatical jobs, richer than Tagalog's three-way system; an 8×8 table
of historically fused ergative×absolutive pronoun portmanteaus; a dual native/Spanish numeral
system where Spanish-loan ordinals retain Spanish grammatical gender agreement despite Ilocano
having no native gender system; and explicit Hawaiʻi-contact data — both narrative (the
dissertation's statement that one-fifth of Hawaiʻi's population is Ilocano-descended) and lexical
(dictionary entries *Aloha*, *Haway*/*Hawayano*, and *kanaka* tagged "Hawaiian use only"). The
dictionary samples also surfaced substantial slang/taboo register material, including an explicit
ethnic slur the dictionary itself flags as derogatory (*panggalatot*, toward Pangasinan speakers).
The `/graphify` graph (first ever for this language) was built from 3 independently-dispatched
chunks under the same node-density discipline used on every other language's graph.

1. **Exhaustive vs. representative extraction per book/language.** Manually extracting even 20
   well-sourced entries from ~2 pages of a 531-page book took a substantial single pass — exhaustive
   coverage of every book, for every language, at this granularity does not appear tractable in
   reasonable time. Whether Phase 1 should aim for full coverage or deliberately-sampled
   representative coverage per book is an open decision.
2. **Manual vs. subagent-parallelized extraction.** Whether extraction work should be dispatched to
   parallel subagents (the way `/graphify`'s own semantic-extraction step does) rather than done as
   one continuous manual read-through — this could materially change the tractability math for
   question 1.

**These two questions directly bear on the "all reference extraction must complete, for every
language, before any web research begins" sequencing rule** — that rule's practicality depends on
how expensive exhaustive Phase 1 extraction actually turns out to be. Not resolved yet; the
sequencing-rule decision itself also remains explicitly deferred (see conversation history).

**Prove the pipeline on one or two flagship languages first — do not fan out to many languages in
parallel before the schema/shard/OCR approach is actually validated end-to-end.** Catching a
schema problem, a bad shard-size assumption, or an OCR/scan-handling gap on language #1 is cheap;
catching it after 15 languages are already partway through is not. *(Confirmed valuable by the test
run — see the index-prerequisite-rule and OCR-prevalence findings, both caught during Phase 0/1 on
just one language.)*

**OCR/scan handling is its own concern**, not a detail to improvise per-book. Flag in the Phase 0
catalog which books need vision-based reading vs. have a usable text layer — this changes
extraction cost per book substantially and should inform Phase 0.5 prioritization too (a
Tier-1 language whose best source is a 400-page image-only scan is a different effort estimate
than one with clean text-layer PDFs). **Add a third category, found during the test run: a text
layer can be *present but garbled* (bad OCR baked into the PDF itself) — functionally equivalent to
no text layer, but easy to miss if a triage pass only checks "text layer exists: yes/no."** A fourth
category found during the Dutch test run: a text layer can be *clean and fully usable but carry a
cosmetic artifact* (e.g. page-margin ruler/registration-mark noise prepended to extracted text) —
distinguishable from garbled OCR by checking that real, clean body text follows immediately after;
tell extraction subagents to simply ignore such noise rather than treating the file as unusable.

**Copyright discipline.** Reference material is copyrighted grammars/dictionaries. Extraction
stays in the same mode already modeled by the Inner Tepenia GDD repo's book extractions: selective
quotes + paraphrase + analysis connecting real material to project needs — never bulk reproduction
of a book's content into this repo.

**Prioritize register/colloquial-focused chapters, not just sequential coverage.** Confirmed during
the Dutch test run: grammar-reference extraction otherwise skews almost entirely to `core` usage
tier (teaching grammars are definitionally basic vocabulary) — but a book's own "colloquial speech,"
"informal register," or sociolinguistic-commentary chapters reliably surface real `Usage Tier`
diversity (`colloquial`, `formal`, etc.) that foundational chapters don't. When triaging a language's
reference material, actively look for and prioritize these chapters/sections over same-length chunks
of purely foundational grammar — they're disproportionately valuable for this project's specific
purposes.

**Budget wave-based dispatch for any full-book/full-language extraction.** Confirmed during the
Serbian/Croatian/Bosnian bridge-scale test (one full 531-page book, 28 extraction chunks): there is a
**hard platform ceiling of 20 concurrent subagents**. A dispatch plan involving more than ~15-18
concurrent chunks gets excess `Agent` calls flatly rejected, not queued — plan waves (with headroom
below 20) up front rather than discovering the cap mid-run. See
`datasets/00_Reference_Extraction_Spec.md`'s "Dispatch scale and concurrency limits" section for the
full guidance, including the check-first duplicate-prevention instruction this makes necessary and
the serialized-checklist-update rule for parallelism above n=3.

## Phase 2 — Web scraping (general, frequency-tagged)

**Status: not started.** Renumbered 2026-09-09 — this used to be bundled with slang-corpus curation
as a single "Phase 2." It is now split into two phases because the two jobs are genuinely different
in kind: this phase is broad, general-usage web collection (not filtered to slang up front), and
Phase 3 is the curation/filtering pass that turns raw scrape into an actual slang corpus.

**What this phase collects:** vocabulary and phrasing scraped from the web for a given language,
tagged by **frequency of use** as it's collected — not just "does this term exist" but "how often
does it actually show up" across whatever sources get scraped. This frequency signal is what lets
Phase 3 later distinguish load-bearing slang from a one-off nonce usage, and lets Phase 4's
mechanics analysis weight findings by real-world productivity rather than treating every entry as
equally significant.

**Mandatory: keep a scrape log per language/source, so nothing gets scraped and counted twice.**
Every scraping pass must record what was already pulled (source, date, URL/identifier, and enough
of a fingerprint to detect the same content resurfacing under a different URL) before scraping
further — re-scraping the same forum thread or subtitle file a second time and double-counting its
frequency contribution would silently corrupt the frequency data this whole phase exists to
produce. Exact schema (a manifest file per language, a hash-based dedup index, etc.) is not yet
decided — treat "some durable, checked-before-every-scrape log" as the hard requirement, the
specific format as an open implementation choice.

Web-scraping mechanics are their own concern, separate from the linguistic content itself: rate
limits, ToS respect, and — critically — **which platforms are actually worth the time varies by
language and region** and is itself worth researching before committing hours per language (this
is exactly what `language_corpus/00_Source_Reliability_Guide.md`'s platform reliability registry
exists to accumulate for subtitle/transcript sources specifically; the same "which platforms are
actually good for this language" question applies more broadly to general web sources too).

Subtitle/transcript mining (a rich source, with real risk — see the reliability guide) sits inside
this phase, not as a separate one.

**Not yet built:** the folder/schema this phase's raw output actually lives in. `language_corpus/`
already exists but is now Phase 3's curated-corpus folder, not this phase's raw-scrape staging
area — a separate location or a clearly-separated subdirectory is needed before real scraping work
starts, so raw frequency-tagged scrape data and curated slang entries don't get mixed in the same
files.

## Phase 3 — Slang corpus (curation)

**Status: not started.** See `language_corpus/00_Corpus_Collection_Index.md` for live status. This
is where `language_corpus/<Language>/` as it already exists in this repo belongs — the curated,
sourced, tiered slang corpus, filtered and organized out of Phase 2's raw frequency-tagged scrape
(once Phase 2 exists) plus any slang-dictionary-type material already found sitting in
`source_reference/` during Phase 0/1 triage (e.g. Hungarian's *Magyar Szlengszótár*, Kövecses
2009 — extracted directly since it was a real, physically-present book, ahead of Phase 2 existing).

Frequency-of-use data carried over from Phase 2 (once that phase exists) should inform each
corpus entry's `Weight/Frequency` field with real signal, not a guess.

## Phase 4 — Mechanics analysis

**Status: not started.** See `datasets/00_Analysis_Index.md` for live status. Gated per-language on
that language's Phase 3 corpus being at least `in progress`.

## Phase 5 — Cross-language comparative pass

**Status: not started — blocked on Phase 4 producing real data for 2+ languages.**

Once a handful of languages have real `analysis/` data, look across them: which `slang_type`s (see
`datasets/00_Usage_Tier_Taxonomy.md`) recur across languages vs. stay language-specific, which
usage-tier subcategories show up repeatedly and deserve promotion to the shared taxonomy, and
whether any genuinely universal slang-formation patterns emerge vs. patterns that are artifacts of
one language/culture. This is where the taxonomy's "promote once 2+ languages show it" rule
actually gets exercised for real, rather than staying theoretical.

## Phase 6 — Synthesis

**Status: not started.** Already schema-scaffolded (`datasets/<Language>/synthesized/`). Feeds the
actual sci-fi conlang/culture work, which likely lives partly outside this repo in wherever the
fictional cultures themselves are defined (cross-reference once that connection point is decided).

## Cross-cutting: QA / spot-check cadence

**Not a one-time step — an ongoing discipline once Phase 3+ produces real entries.** Periodically
re-verify a sample of flagged (`low_confidence`, `plausible_unverified`) entries, especially any
that fed into a `synthesized/` term — don't let a flagged-but-never-revisited entry quietly become
load-bearing for creative work downstream. See
`language_corpus/00_Source_Reliability_Guide.md`'s maintenance rule for the resolve-in-place
convention.

---

## Maintenance rule

Update this file's phase statuses as work actually begins/finishes. If a new cross-cutting concern
surfaces during actual extraction/research work (the way OCR-handling and platform-reliability did
during scaffolding), add it here rather than letting it stay implicit tribal knowledge.
