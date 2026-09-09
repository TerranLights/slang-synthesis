# Hungarian Slang Mechanics — Extraction Checklist

**This is the pipeline's second test-run language — everything below is tentative until the
developer reviews it.** See `../../methodology-observations/hungarian_test_run.md` for process
findings (comparing against the first, Serbian/Croatian/Bosnian, test run) and
`00_Book_Triage_Catalog.md` (this folder) for the source-material survey. (`Hungarian` is its own
folder-safe name — no display-name-vs-path-name split needed here, unlike Serbian/Croatian/Bosnian.)

**Purpose:** analyze the actual mechanics of how Hungarian slang forms and works, using the
corpus collected in `language_corpus/Hungarian/` and, where useful, the grammar/vocabulary
reference in `source_reference/languages/Hungarian/`. Findings here are what eventual synthesis
work (deriving invented slang for the sci-fi setting) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

---

## Morphological typology

*(Fill in during Phase 0 triage, before extraction begins — see
`../00_Word_Concept_and_Morphological_Typology_Guide.md`. What is this language's approach to the
concept of a "word"? Isolating / agglutinative / fusional / polysynthetic / a mix — with one or two
concrete examples if available. This affects how `established/` vocabulary entries should be
recorded and how `morphological_play` should be interpreted in `analysis/`.)*

**Hungarian: agglutinative, but not uniformly so across subsystems.** Grammatical relationships
(case, possession, plurality, tense, definiteness) are marked by stacking separable,
individually-meaningful suffixes onto a stem, governed by **vowel harmony** (a suffix's vowel
changes to match the stem's own front/back and rounded/unrounded vowel quality — see the grammar's
own Chapter 3; per Kornai's *On Hungarian Morphology*, this is not simple binary front/back but a
binary/ternary/quaternary system with 5 stem classes, I-V). The case system (Chapter 6 of the
Rounds grammar) covers an unusually large inventory (17 cases) expressed via suffixation rather
than prepositions as in English — though Kornai argues the formalis case (`-ként`) is structurally
peripheral (no harmonic alternation, never obligatorily governed), a useful model for judging
whether a given Hungarian slang marker is a "full" case-like element or a marginal one.

**Concrete stacking example** (`established/003`): `gyerekeire` = `gyerek` (child) + `-ei` (plural)
+ `-re` (sublative case, "onto") — a triple-stack, each piece independently identifiable, matching
the Word-Concept guide's Finnish example.

**Subsystems are NOT equally agglutinative** — Kornai's own count: the nominal possessive paradigm
comes close to pure agglutination (7 suffixes vs. a ~3.6 theoretical minimum) and includes a rare
genuine infix (`-i-`, plural-possession marker) in an otherwise prefix/infix-free language; the
verbal paradigm (person/tense/mood/definiteness), by contrast, sits only "roughly halfway between
agglutinating and inflecting" (17 regular + 9 irregular suffixes vs. a 12-suffix theoretical
minimum).

**A productive "lowering" diacritic reveals hidden structure via suffix-stacking**: many suffixes
(1st/2nd sg. possessive, past/imperative/conditional markers, the `-as/-es/-os/-ös` derivational
suffix) carry a "lowering" property that turns an ordinary stem into a lowering stem — visible only
once a *further* suffix stacks on top (`rum` → `rumom` → `rumomat`, not `*rumomot`). Lexicalization
can strip this marking again: `házas` ("married," lexicalized) loses the diacritic its derivational
suffix carries, while the same suffix freshly composed (`házasakat`, literal non-idiomatic use)
keeps it. This natural-vs-derived-word-formation distinction has real morphological teeth and is a
plausible mechanism for future `morphological_play` slang analysis.

**Derivational vs. inflectional suffix ordering differs qualitatively**: reordering two
derivational suffixes changes meaning (e.g. potential+causative ≠ causative+potential — see
`established/005`'s `olvastathat`/`olvasgathat`); reordering inflectional suffix classes does not
(order is fixed but semantically arbitrary). See `established/007` and `established/008` for the
full analysis this is drawn from.

---

## Output files — Markdown, sharded by numbered file, not JSON

**Storage model.** All extracted content — raw reference data, mechanics analysis, synthesized
results — lives as **Markdown** (occasionally `.txt`), not hand-authored JSON. This matches how the
rest of this project's own methodology documentation works, and lets `/graphify` serve as the
organized-summary/pointer layer instead of a manually-maintained manifest (see Graphify section
below).

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real Hungarian baseline — vocabulary/grammar tables extracted per lesson/chapter/section, per `00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group), narrative writeup + examples table | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output, one file per batch. **Explicitly provisional** — revise via each term's own Revision History subsection, never silent overwrite | `001_<batch>.md`, ... |

Copy `_TEMPLATE/established/001_TEMPLATE.md`, `_TEMPLATE/analysis/001_TEMPLATE.md`,
`_TEMPLATE/synthesized/001_TEMPLATE.md` as starting points. **Don't let a single file grow
unbounded** — split into a new numbered file once one gets unwieldy to read/diff, same discipline
used in `language_corpus/`. **No `_index.json` manifest to maintain** — this checklist's own
`## Output files` table (below) is the human-readable index; `/graphify` (see below) is the
machine-queryable one.

Fill this table in as files are created:

| File | Contents |
|---|---|
| `established/001_chapters1-3_phonology_vowel_harmony.md` | Rounds, *Hungarian: An Essential Grammar* (2nd ed., 2009), Chapters 1-3 (Alphabet, Pronunciation, Vowel Harmony), pp. 3-12. ~65 vocabulary items, 14 grammar-point subsections, morpheme breakdowns for consonant-lengthening pairs and all ten of Chapter 3's vowel-harmony worked examples. |
| `established/002_chapter5_nouns.md` | Rounds, *Hungarian: An Essential Grammar* (2nd ed., 2009), Chapter 5 "Nouns," pp. 76–85: articles (definite/indefinite/zero), suffix stacking & vowel harmony, noun stem classes (vowel-final, low-vowel, v-stem, `-alom/-elem`, fleeting-vowel, regular) and their plural formation, singular/plural usage rules. ~100 vocabulary items, morpheme breakdowns for representative stem-alternation examples. |
| `established/007_on_hungarian_morphology_part1.md` | Kornai, *On Hungarian Morphology* (dissertation, 1986/2007 pdf), Preface + Ch. 1-3 (Introduction, Phonology, Words and Paradigms), PDF pp. 1-81. Academic paper, not a teaching grammar — prioritizes the paper's own theoretical/analytical content over vocabulary: the tridirectional I/A/U vowel-feature system, the five-way vowel-harmony stem classification (Classes I-V) and the "lowering stem" diagnostic (productive suffixes can turn a regular stem into a lowering stem, revealed only by a further suffix — see `rumomat`, `tökömet` morpheme breakdowns), neutral-vowel transparency/vacillation, and the paper's definition of lexical category via inflectional paradigm rather than meaning (with a worked morphosyntactic-feature-tree account of defective paradigms). ~50 vocabulary items including the source's own explicit ECH/SLH register and dialectal-epenthesis annotations. |
| `established/003_chapter6_case_system.md` | Rounds, *Hungarian: An Essential Grammar* (2nd ed., 2009), Chapter 6 "The Case System," pp. 86-113: all 23 Hungarian cases (grammatical, locative, oblique, less-productive), verb/case government, plural declension. ~115 representative vocabulary items (deliberately not exhaustive — case coverage prioritized over cataloguing every declension-table word), 11 morpheme breakdowns including a triple-stack example (`gyerekeire`). |
| `established/017_fsi_vol2_units17-20.md` | Koski & Mihalyfy (ed. Hodge), *FSI Hungarian Basic Course, Units 13-24* (Vol. 2, 1964), Units 17-20, pp. 367-453: illness/hospital, buying a used car & traffic law, burglary/police/court system, sports & barbershop talk. ~250 vocabulary items, full Notes on Grammar for all 4 units (subjunctive formation & assimilation, `-ért`/`-e`, subordinate-clause introducers, indefinite/negative compound pronouns, `-hat/-het`, fractions, `-an/-en`, diminutives, `-s` adjectival suffix, `-talan/-telen` privative family, `mag(a)-`, reflexive-verb suffixes, participial `-ó/-ő`/`-t/-tt`/`-va/-ve`, deverbal-noun suffixes), all 4 units' proverb (Közmondások) blocks reproduced in full, 8 morpheme breakdowns. Notable colloquial-register finds: informal discourse particles (`hiszen`, `pláne`, `apropó`, `dehogy`, `sőt`), the `Jézus-Mária` exclamation, diminutives-as-affection, and the loanword sports colloquialism `futballmeccs`. |
| `established/014_fsi_vol1_units05-08.md` | Koski & Mihalyfy, *Hungarian Basic Course* (FSI, 1962), Units 5-8, printed pp. 85-178 (PDF pp. 98-191): dinner-party/sightseeing/friend-visit/diplomatic-reception dialogues; grammar covers -ban/-ben vs -ba/-be, irregular verbs (enni/menni/venni/inni/vinni/jönni), nincs/nincsenek negation, postpositions, definite vs. indefinite verb conjugation (major topic), verbal prefix meg-, the full possessive-suffix paradigm (major topic, Unit 7), ik-verbs, the infinitive, -ból/-ből and -n/-on/-en/-ön, and Hungarian's forward-referencing time-telling system with an explicit colloquial-register note on how non-round times are actually spoken. ~230 vocabulary items across 4 units, 5 morpheme breakdowns, one flagged Cold War-era political/historical content point (Unit 7, on writers under the Communist regime). Vision Reading Confidence n/a throughout (OCR'd text layer, not vision-read; noise localized to prose/footers, not vocabulary lines). |
| `established/010_szolasok_kozmondasok_part2.md` | *Magyar szólások és közmondások* (Hungarian Sayings and Proverbs), 835-page numbered proverb/idiom dictionary, PDF pp. 211-420 (entries f1028-l783, headword groups fül/füst/fürj → G → GY → H → I → J → K → ló, ~5,595 entries exist in this page range alone). Deliberate 50-entry sample, not exhaustive — prioritized figurative derivation, explicit register tags (rég/táj/nép/biz/durva/tréf/ritk/elavulóban), and recurring idiom-formation patterns (placename-anchored fixed similes, a homophone pun, bread/hair-knot status metonymy, drinking euphemisms). Establishes a register-tag → Usage Tier mapping for this book (rég→archaic, táj→regional, nép/biz→colloquial, durva→taboo) to be reused by future Szólások chunks. |
| `established/008_on_hungarian_morphology_part2.md` | Kornai, *On Hungarian Morphology* (dissertation), §4 "Inflectional Morphology" + §5 Bibliography (not extractable), PDF pp. 81–158. Academic paper — prioritizes theoretical/analytical content over vocabulary: full verbal-paradigm analysis (finds Hungarian's verbal system only "roughly halfway between agglutinating and inflecting," ~17+9 suffixes needed vs. a 12-suffix theoretical minimum), derivational- vs. inflectional-suffix ordering (reordering changes meaning only for derivational suffixes), the ik-verb class as a memorized paradigm marker, the full 17-case system tabulated with per-case harmonic arity and the formalis case (`-ként`) argued as structurally peripheral, Low-Vowel-Lengthening vs. Vowel-Drop as lexically- (not phonologically-) governed alternations, the possessive paradigm as Hungarian's most cleanly agglutinative subsystem (includes a rare genuine infix, `-i-`), explicit S/D dialectal variation in the familiar-plural `-ék`, and closed-class inventory sizes from the paper's own computational implementation (11,420 noun stems, 2,498 verb stems, 835 adverbials, 129 connectives, and a 214-item "exclamations/curses/performatives" class — flagged for future `language_corpus/` collection). ~40 vocabulary items (mostly paradigm-illustration stems), 5 morpheme breakdowns.  |
| `established/006_750_hungarian_proverbs.md` | Paczolay Gyula, *750 magyar közmondás / 750 Hungarian proverbs* (1991), the entire 58-page bilingual proverb dictionary — exhaustive, all 750 numbered entries. New `literary.proverb` Usage Tier subcategory (not yet promoted to the shared taxonomy). ~184 entries carry an explicit quoted figurative meaning distinct from the literal gloss; ~60 also carry a parenthetical English idiom-equivalent. Notes flag recurring literal→figurative derivation patterns (animal-domain metaphor productivity as the single most common source imagery, body-part/bodily-state metonymy, household-object imagery for social/economic judgment) worth a dedicated future `analysis/` pass. |
| `established/013_fsi_vol1_units01-04.md` | Koski & Mihályfy, *FSI Hungarian Basic Course* (Foreign Service Institute, 1962), Volume 1, Units 1-4, pp. 1-84 (of 279). Dialogue/drill audio-lingual course, not a reference grammar — Basic Sentences vocabulary plus Notes on Pronunciation/Grammar for each unit. ~396 vocabulary entries. Highest-value finding: the source's own explicit three-tier `te` (intimate/colloquial) / `maga` (neutral polite) / `ön` (formal, source-flagged as already declining in 1962 usage) second-person register system. Also flags two socialist-era institutional-vocabulary items (`MASZEK` "private-sector business," `Úttörő Áruház` "Pioneer Store") and an explicit colloquial-register note on indefinite-article omission. No `[B]`/`[C]`/`[S]`-style dialectal tags present (single-dialect course). |
| `established/015_fsi_vol1_units09-12.md` | FSI *Hungarian Basic Course*, Volume 1 (Student Text), Units 9-12 (the last unit range of Volume 1), printed pp. 179-265 (of 279). ~292 vocabulary entries (Basic Sentences glosses + unit-closing Narrative glossaries + a handful of drill-only-introduced items), full paraphrase of all 14 lettered grammar points across the 4 units (dative case & the "to have" construction, plural-possessive morphology, double negatives, the `-ra/-ról/-tól` suffix family, the full past-tense verb-class system, present/past tense-usage divergence from English, `-ig` vs. `-hoz/-hez/-höz`, the possessive-suffix "ago" construction, verbal prefixes, the future tense, demonstrative-suffix paradigm, `tudni` vs. `ismerni`, `kérni` vs. `kérdezni`, ordinal numbers/date expressions). Notable findings: `kulák` (Communist-era pejorative for "wealthy peasant," left untranslated in the source's own English gloss), `pálinka` and other informal-life vocabulary appearing only in unit-closing narratives (not the structured dialog drills), and a Unit 12 dialog passage voicing a real if mild socioeconomic critique (workers' wages vs. cost of living) inside a U.S. government-produced Cold War course. No explicit dialectal tags in this source (single standard-register course). |
| `established/004_chapter4_verbs_part1.md` | Rounds, *Hungarian: An Essential Grammar* (2nd ed., 2009), Chapter 4 "Verbs," pp. 15-45 (of ~90): verb stems and `-ik` verbs, the definite/indefinite conjugation system (incl. the seven definiteness-triggering environments and the `-lak/-lek` 1sg-subject/2sg-object slot), all four core paradigms (present, past, subjunctive/imperative, conditional) with their stem-class-conditioned marker alternations, the periphrastic future (`fog`, `lesz`), and the non-finite forms (present/past/future participles, adverbial participle, infinitive) through §4.4.4 — stops at the clean boundary just before §4.4.5 Declined infinitives. ~165 vocabulary items (near-exhaustive on verbs, the chapter's organizing category), 10 morpheme breakdowns covering subjunctive-marker assimilation, the 1sg-subject/2sg-object portmanteau ending, and the periphrastic past conditional. Explicit archaic/colloquial register tags on specific `-ik`-verb inflectional endings (not standalone vocabulary) are flagged in the grammar-points prose. Part 2 (§4.4.5 onward, incl. §4.5 derivational endings and coverbs) not yet done. |
| `established/018_fsi_vol2_units21-24.md` | Koski & Mihályfy (ed. Hodge), *FSI Hungarian Basic Course, Units 13-24* (Vol. 2, 1964), Units 21-24 — the volume's final four units, printed pp. 455-559 (PDF pp. 198-302): Hungary's geography (Unit 21), cultural life/arts (Unit 22), state administration (Unit 23), economic life (Unit 24). ~200 vocabulary items including two full narrative-glossary blocks (Unit 21's history-of-Hungary narrative). All grammar points paraphrased: causative-verb formation & agent marking, `való`/`levő`, emphatic prefixes, a word-formation-suffix reference list (Unit 21); the full familiar (tegező) 2nd-person paradigm and the `-lak/-lek` portmanteau suffix, plus a `tetszik`/`izlik`/`jólesik`/`rosszul esik` dative-experiencer verb cluster (Unit 22); verbal-prefix and frequentative-verb reference lists, 6 additional derivational suffixes, numeral+possessive-suffix constructions (Unit 23); and Unit 24's single grammar section, which the source itself frames as a shift from "fundamental patterns" to idiomatic/figurative expressions — ~25 verb-particle idioms captured (`bele-`/`neki-` preverb clusters, `szaván fog`, `sokba kerül`, `rossz szemmel néz`, etc.). Strongest explicit register content found in the Hungarian corpus to date: Unit 22 is the course's first formal introduction of the informal tegező register (vs. the polite maga/ön forms drilled elsewhere), motivated by two young friends' dialogue (`szervusz`, `Isten hozott`). The volume's closing cumulative Hungarian-English Word List (pp. 562-606) was inspected and found to be a pure alphabetized index of vocabulary already covered across the whole course — not separately extracted, per the coverage rule's back-matter guidance. |
| `established/005_chapter4_verbs_part2.md` | Rounds, *Hungarian: An Essential Grammar* (2nd ed., 2009), Chapter 4 "Verbs" Part 2, printed pp. 40-75 (of ~90): §4.3.10 (future tense `fog`/`lesz`) through §4.7 (coverbs) — the rest of the chapter after Part 1. 524 vocabulary rows (near-exhaustive on verbs), including the full irregular-verb-stem inventory and a near-exhaustive coverb catalogue. 8 morpheme breakdowns, including the pattern where potential/causative/frequentative derivational endings each redefine the verb's stem type so a second ending stacks onto the *new* stem. Coverb semantics finding: `meg`- vs. `el`- form a systematic "expected/nice change" vs. "unfortunate change" contrast on the same verb; `le`- alone spans six semantic clusters from literal "off" to purely pejorative. Chapter 4 is now fully extracted (Parts 1+2). |
| `established/009_szolasok_kozmondasok_part1.md` | *Magyar szólások és közmondások* (O. Nagy Gábor, 4th ed. 1985), PDF pp. 1-210 (of 835), entries #1-~1008, keyword span abaúj/ábécé/ablak through fül. 47-entry sample (deliberately non-exhaustive — thousands of entries in this range). Recurring patterns: single-keyword idiom clusters (20+ idioms off one headword), "bőr" (skin) as a euphemism domain for both death and financial exploitation, a reusable "understands X like [animal] understands [authority]" template, and a rare negative data point — only 2 of ~1000 scanned entries carry the true-slang `argó` tag. New Usage Tier subcategories `colloquial.folk` (nép) and `colloquial.familiar` (biz). Flags the "cigány" (Roma) keyword cluster as attested-but-ethnically-biased period folklore rather than neutral data. |
| `established/011_szolasok_kozmondasok_part3.md` | *Magyar szólások és közmondások*, PDF pp. 421-625 (of 835), entry-number ranges l784-893/m579-663/o274-289 & ö1-39/p316-402/r94-168/sz568-652 & sz1244-1298 (book restarts numbering per letter), keyword span ló/lúd through szűr. 49-entry sample. The source prints its own precise register-abbreviation legend (rég/táj/nép/biz/argó/vál/Sp/ritk), fully mapped to this project's Usage Tier taxonomy including a new `colloquial.folk` (nép) subcategory distinct from `regional`. Patterns: register-doubled proverb variants (same figurative frame, a `durva`-tagged coarse lexical swap at one slot — a concrete `taboo_inversion` model), dense domain-metaphor clusters (draft-animal/poultry husbandry, clothing-as-status), entries tagged both `argó` and archaic simultaneously (slang aging out rather than graduating to core), and a naturalized loanword idiom (`reszkíroz` < risk). |
| `established/012_szolasok_kozmondasok_part4.md` | *Magyar szólások és közmondások*, PDF pp. 626-705 held content (pp. 706-835 back matter: index/TOC/colophon, correctly skipped), tail of SZ through Z/ZS. 50-entry sample. Two confirmed `argó` (true slang) entries — t254 "Leadja a tejet" (sexual euphemism) and z37 "Szintén zenész" (opaque occupational slang) — the highest-value slang finds from this dictionary. Patterns: livestock/farm-animal domain as extremely productive metaphor source (cow ~40 entries, hen ~44), "handed an object" as a recurring job-dismissal euphemism template, rhyme-paired proverbs as a mnemonic device, and two apparent cross-linguistic idiom universals (glass houses/stones; cat/pig-in-a-sack). This is Part 4 of 4 — *Magyar szólások és közmondások* extraction is now complete (Parts 1-4, ~196 sampled entries total across the 835-page dictionary). |
| `established/016_fsi_vol2_units13-16.md` | Koski & Mihályfy (ed. Hodge), *FSI Hungarian Basic Course, Units 13-24* (Vol. 2, 1964), Units 13-16, printed pp. 267-366 (PDF pp. 10-109). 339 vocabulary table rows (400+ distinct items), 7 morpheme breakdowns. Two full Közmondások (proverb) lists (Units 15-16, 13 proverbs). Explicit colloquial-register grammar notes: Unit 14's colloquial `-ik` suffixation marking a preferred item among a pair, Unit 16's colloquial preference for singular `-é` over plural `-éi` even for plural referents. Discourse particles (`ugye`, `hát`, `puff`), idioms (`vénasszonyok nyara` "Indian summer," `mi az ördög`), and a socialist-era institutional-vocabulary cluster tagged `Attested Era: socialist Hungary (source published 1964)`. |

---

## Field/column conventions

**Usage-tier / slang-type categorization.** `established/` vocabulary tables carry a `Usage Tier`
column (e.g. `core`, `technical`, `taboo`, `slang`, ...) — see `../00_Usage_Tier_Taxonomy.md` for
the shared vocabulary, kept consistent across languages so findings are comparable. `analysis/` and
`synthesized/` entries carry `Slang Type` and `Derived From Tiers` tags, capturing which
standard-language tier(s) a given slang-formation mechanism actually draws from. **Every tier/type
is extensible with dot-notation subcategories** (`technical.medical`) — use them freely as real
data surfaces distinctions worth keeping, and promote a subcategory into the shared taxonomy doc
once it recurs across 2+ languages.

**Transcription risk carries through.** Any `analysis/` example drawn from a corpus entry that was
itself sourced from a subtitle/transcript keeps that entry's `Source Type` and `Transcription
Confidence` — see
[`../../language_corpus/00_Source_Reliability_Guide.md`](../../language_corpus/00_Source_Reliability_Guide.md).
Don't build a mechanism finding on a `low_confidence` example without saying so.

**Vision-reading risk.** All three `established/` files here were extracted from a source with a
real text layer, so `Vision Reading Confidence` is `n/a` throughout (retrofitted when this column
was added to the project schema, after the Serbian/Croatian/Bosnian vision-reading test). Once this
language's own scanned/no-text-layer sources (`Hungarian-An-Essential-Grammar.pdf` 1st ed.,
`Hungarian Verbs.pdf`, `Magyar Szlengszótár.pdf`) are extracted, apply the real three-tier scale and
the marginalia guard — see `../00_Reference_Extraction_Spec.md`.

**Historical & geographic context — optional, fill in only when the source supports it.** Entries
carry `Attested Era`/`Attested Region`/`Geographic Scope` columns — see
[`../00_Historical_and_Geographic_Context_Guide.md`](../00_Historical_and_Geographic_Context_Guide.md).
`—` is a legitimate value, not a gap to guess-fill; false precision here is worse than an honest
unknown.

**Morphological composition.** For agglutinative/polysynthetic (or complex fusional) word-forms,
`established/` entries include a morpheme breakdown rather than treating the surface form as
atomic — see `../00_Word_Concept_and_Morphological_Typology_Guide.md`.

## Graphify

This language gets its own graph, scoped to `datasets/Hungarian/` (separate from
`language_corpus/Hungarian/`'s own graph). **Already run once** (see `graphify-out/` in this
folder) — re-run after adding more content. Its `graph.json` (nodes carrying
`source_file`/`source_location`) is this language's organized-summary and pointer layer — no
separate hand-authored index needed. If a single language's graph itself grows past graphify's own
size warnings (2M words / 500 files), narrow further — e.g. graph `established/`, `analysis/`, and
`synthesized/` as separate runs rather than one combined pass.

**Before re-running: `cd` into `datasets/Hungarian/` first, don't run graphify's own Python calls
from the repo root with only a `root=` argument.** Confirmed real bug during this language's own
test run: `save_manifest()` and likely other graphify internals resolve output paths relative to the
*working directory*, not `root=` — running from the repo root silently corrupted the repo-root
`graphify-out/manifest.json` the first time this was run (caught and fixed via `git diff` before
committing). **After running, always check `git status`/`git diff` on the repo-root `graphify-out/`
before committing.** See `../00_Reference_Extraction_Spec.md` for the full writeup.

## Mechanisms examined

- [ ] *(not started — Phase 1 reference extraction only so far, Phase 3 mechanics analysis has not
      begun)*

## Reference extraction progress (Phase 1)

Extracting from `Hungarian-An-Essential-Grammar-Second-Edition-.pdf` (Rounds, 2nd ed., 2009),
subagent-parallelized per `../00_Reference_Extraction_Spec.md` — the first real test of that method
(the Serbian/Croatian/Bosnian run's shard was done manually, before the spec existed).

- [x] Chapters 1-3 (Alphabet, Pronunciation, Vowel Harmony) — written to `established/001_chapters1-3_phonology_vowel_harmony.md`
- [x] Chapter 5 (Nouns) — written to `established/002_chapter5_nouns.md`
- [x] Chapter 6 (Case system) — written to `established/003_chapter6_case_system.md`
- [x] Chapter 4 (Verbs) — Part 1 written to `established/004_chapter4_verbs_part1.md`, Part 2 to
      `established/005_chapter4_verbs_part2.md`. Rounds' *Hungarian: An Essential Grammar* (2nd ed.)
      is now fully extracted end-to-end.
- [x] `750-Hungarian-proverbs.pdf` — full 750-entry collection written to `established/006_750_hungarian_proverbs.md`
- [x] `ON-HUNGARIAN-MORPHOLOGY.pdf` — Part 1 (`established/007`) and Part 2 (`established/008`),
      full 158-page academic paper extracted.
- [ ] `A-complete-practical-grammar-...pdf` — Wave 2, not started
- [x] *Magyar szólások és közmondások* (835-page proverb/idiom dictionary, O. Nagy Gábor 1985) —
      all 4 parts done (`established/009-012`), ~196 sampled entries total. Deliberately
      non-exhaustive sampling per the dispatch instructions, not full transcription.
- [ ] `Magyar Szlengszótár.pdf` (slang dictionary) — Wave 3 (vision-reading); see
      `00_Book_Triage_Catalog.md`'s scope note on the Phase 1/Phase 2 boundary question this file
      raises
- [x] `FSI Basic Hungarian` (Koski & Mihályfy, 1962/1964, two-volume 24-unit audio-lingual course) —
      Volume 1 (Units 1-12) written to `established/013-015`; Volume 2 (Units 13-24) written to
      `established/016-018`. Full course now extracted end-to-end.
- [ ] `The Phonology of Hungarian.pdf`, `Magyaróra: New Paths to the Hungarian Language.pdf`,
      `Hungarian-English Phrase Book.pdf`, `Practical Hungarian Grammar.pdf`,
      `Hungarian-Language-Contact-Outside-Hungary-...pdf` — Wave 2, not started
- [ ] Wave 3 vision-reading sources (`Magyar Szlengszótár.pdf`, `Teach Yourself Hungarian [2nd Ed]`,
      `Colloquial Hungarian.pdf`, `Hungarian-in-words-and-pictures-...djvu`, `Hungarian-with-ease.pdf`,
      `Hungarian Verbs.pdf`) — not started

**Wave 1 status: complete.** All 5 Wave 1 sources fully extracted (18 `established/` files total,
001-018). See `00_Book_Triage_Catalog.md` for the full Wave 1/2/3 priority breakdown and the
deferred/out-of-scope material list.

## Suggested next-session order

1. Wave 2: clean-text supplements (phonology reference, Magyaróra coursebook, phrase book, the
   older 19th-century grammar for `attested_era` contrast, the diaspora/dialect-contact volume).
2. Wave 3: vision-reading pass, starting with `Magyar Szlengszótár.pdf` (highest-value target) and
   `Teach Yourself Hungarian [2nd Ed]`.
3. Rebuild `datasets/Hungarian/graphify-out/` once Waves 2-3 land, following the same
   cross-chunk-edge-fabrication-avoidance discipline validated on the SCB run.
