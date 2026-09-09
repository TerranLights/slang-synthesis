# Hungarian — Established Grammar/Vocabulary: The Phonology of Hungarian, Part 1
# (Ch. 1–5: Introduction, Preliminaries, The Vowel System, The Consonant System,
# Phonotactics)

**Source:** Péter Siptár and Miklós Törkenczy, *The Phonology of Hungarian* (The Phonology of the
World's Languages series, Oxford University Press, 2000, paperback 2007). PDF pages 1–168 of 338
(front matter through the end of Chapter 5). This is a rule-based generative/autosegmental academic
phonology reference describing Educated Colloquial Hungarian (ECH) — its value for this project is
theoretical/analytical (the authors' own generalizations and worked argumentation), not a large
vocabulary sample, exactly as the coverage note for `007_on_hungarian_morphology_part1.md` (Kornai)
established for this kind of source.

**Chunk boundary note.** The assigned range was PDF pages 1–170. The actual clean boundary falls two
pages earlier: PDF page 168 (printed page 153) is the last content page of §5.4.2 and the end of
Part II ("Systems," Chapters 3–5); PDF page 169 is blank, PDF page 170 is the "PART III" divider
page, PDF page 171 is blank, and PDF page 172 begins Chapter 6 ("Processes Involving Vowels") —
the start of Part III. This is a maximally clean structural boundary (end of a book Part, not just a
chapter), verified by direct page-by-page inspection (PDF page = printed page + 15, confirmed against
the book's own footer numbers at several points, not assumed from `pdfinfo`). Chapter 6 onward is
left to the sibling chunk.

**Coverage note.** `pdftotext -layout` produced a clean, complete text layer for the whole range; no
vision-reading was needed. Per the coverage rule for academic phonology references, **grammar-point
content (the authors' own argumentation, generalizations, and theoretical claims) is prioritized over
a large flat vocabulary table** — this book is packed with cluster-inventory tables, minimal pairs,
and derivational-suffix catalogs that are illustrative material for a single point rather than
independent lexical items worth separate rows; only a representative, non-exhaustive sample is
tabulated below, and large derivational-suffix/cluster tables (Tables 1–4, 12–17 in the source) are
paraphrased rather than reproduced. Extensive formal apparatus (feature-geometry tree diagrams,
syllable-template diagrams, autosegmental association-line diagrams) is described in prose per the
copyright/plain-text-survival discipline already established in `007_on_hungarian_morphology_part1.md`.

**Relationship to prior Hungarian coverage.** This source substantially overlaps in territory with
Kornai's *On Hungarian Morphology* (`007`) on vowel harmony and with Rounds's teaching-grammar
chapters, but goes considerably deeper and is more recent/more standard as a reference (this is *the*
canonical English-language phonology of Hungarian). Genuinely new material relative to `007` includes:
the Clements/Hume unary-feature (LAB/COR/DOR + aperture) representation of the vowel system (Kornai
used a three-feature I/A/U system derived purely from harmonic alternation, not tied to a specific
feature framework); the full empirical vowel-harmony stem-class typology with quantified corpus
counts (Table 11) and the "mixed vacillating" vs. "mixed disharmonic" distinction, which is more
fine-grained than Kornai's Class I–V system covered in `007`; the consonant system chapters (stops,
fricatives, affricates, sonorants, the dz/dzs analysis) which `007` only touched briefly; and the
entire phonotactics/syllable-structure chapter (no complex onsets, complex-but-appendix-augmented
codas, the minimal-word constraint, the VVCC morpheme-structure constraint), which is new territory
for this project's Hungarian coverage. Not re-extracted here: general agglutinative-morphology
background (already covered from `007`), which this book's §2.4 covers more briefly and for
different (phonological) purposes.

**Morphological typology note.** Hungarian is agglutinative (see `../00_Extraction_Checklist.md`).
This source repeatedly grounds its phonological claims in the analytic/synthetic suffix distinction
(a novel two-way cross-cutting classification, not the traditional *jel*/*rag* split) because that
distinction predicts *which* phonological processes can see across a given morpheme boundary — this
is itself a significant grammar point, recorded in full below.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| agy / ágy | 'brain' / 'bed' | noun | core | — | contemporary (source published 2000/2007, describing ECH) | Budapest (ECH) | — | grammar_reference | n/a | n/a | minimal pair establishing short /a/ [ç] vs. long /á/ [a˘] as a length-only contrast in the Clements/Hume feature analysis. p. 51 |
| ken / kén | 'smear' / 'sulphur' | verb / noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | minimal pair for e/é; used to argue é/e and á/a are true long/short pairs despite surface quality differences. p. 53 |
| víz / vizek | 'water' / 'waters' | noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | canonical Final Stem Vowel Shortening (FSVS) example: long stem vowel shortens before plural/accusative but not before "on" (superessive). pp. 56, 59 |
| kéz / kezek | 'hand' / 'hands' | noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | FSVS example; also cited as an "unrounding" counterexample check in ch. 3.1.2. p. 58 |
| akadémia / akadémikus | 'academy' / 'academic' | noun / adjective | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | Internal Stem Vowel Shortening (ISVS) example: shortening triggered only by (Latinate) derivational suffixes, never by inflection, and always in the antepenultimate or earlier syllable. p. 58 |
| tu⁄z ‘fire’ / víz ‘water’ / ház ‘house’ | 'fire' / 'water' / 'house' | noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | the three canonical stem-class citation forms (Class IA-f, IIA-f, IA-b) used throughout the vowel-harmony section for dative/ablative paradigm illustration. pp. 66–68 |
| sofo⁄r | 'driver' | noun | core | — | contemporary; loanword | Budapest (ECH) | — | grammar_reference | n/a | n/a | canonical "complex/disharmonic" stem (Class IB–f): back + front-rounded vowels co-occur; suffix selection follows the *last* harmonic vowel (front), not the whole-stem majority. p. 67 |
| híd / hídnak | 'bridge' / 'bridge-dat' | noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | canonical "antiharmonic" stem (Class IIA-b): all-neutral-vowel stem that nonetheless (idiosyncratically) selects back-vowel suffixes; ~60 such stems exist, mostly with i/í. p. 68 |
| kódex / kódexben | 'codex' / 'codex-iness' | noun | core | — | contemporary; loanword | Budapest (ECH) | — | grammar_reference | n/a | n/a | "mixed disharmonic" stem: looks like the papír type (back + neutral) but takes front suffixes because its final e is opaque, not transparent. p. 70 |
| papír / papírnak | 'paper' / 'paper-dat' | noun | core | — | contemporary; loanword | Budapest (ECH) | — | grammar_reference | n/a | n/a | canonical "complex neutral" stem (Class IIB-b): shows that neutral vowels are genuinely transparent to harmony, since the preceding back vowel (not the final í) governs suffix choice. p. 68 |
| haver | 'pal' | noun | colloquial | — | contemporary; loanword (Yiddish/Hebrew via Slavic) | Budapest (ECH) | — | grammar_reference | n/a | n/a | one of the small closed set of stems demonstrating final /e/ is genuinely neutral (haver-nak, not *haver-nek), contrasted with kódex/november where /e/ is opaque. p. 69 |
| dzsungel | 'jungle' | noun | core | — | contemporary; loanword | Budapest (ECH) | — | grammar_reference | n/a | n/a | "mixed vacillating" stem: dzsungel-ben/dzsungel-ban both occur, showing final /e/ can be optionally transparent or opaque for the same speaker. p. 69 |
| lopsz | 'you steal (2sg)' | verb form | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | worked example of a coda cluster (/ps/) violating sonority sequencing (government) because the -sz suffix is phonotactically independent of the stem — evidence for the "appendix" subsyllabic constituent. p. 115 |
| madzag / vadzab | 'string' / 'wild oats' | noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | minimal-pair-style contrast used to argue underlying /dz/ does not exist as a phoneme: madzag's [dz˘] is a true (morpheme-internal) geminate from /d-z/ coalescence, vadzab's [d-z] straddles a compound boundary and stays a cluster. p. 88 |
| tyúk / gyár | 'hen' / 'factory' | noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | cited to argue /ty dy/ are phonologically stops (not affricates), based on unreleased pre-stop allophones and resistance-to-OCP-fusion behavior distinguishing them from true affricates like /ts/, /c&/. p. 82 |
| ajtó / fjord | 'door' / 'fjord' | noun | core | — | contemporary; fjord is a loanword | Budapest (ECH) | — | grammar_reference | n/a | n/a | minimal-pair-style syllabification argument that /j/ must be a distinct segment from /i/ (a liquid, not the vowel /i/ occupying a non-nuclear slot). p. 90 |
| kapja / kapszula | '3sg gets it' / 'capsule' | verb form / noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | representative pair for the obstruent-cluster voicing-agreement generalization: adjacent obstruents (word-internal or across boundaries) must share voicing. p. 77 |
| akta / spektrum | 'file' / 'spectrum' | noun | core | — | contemporary; loanwords | Budapest (ECH) | — | grammar_reference | n/a | n/a | central data point for the "no complex onsets" argument: -kt- occurs medially (akta) but -tk- has no matching -tkC- three-consonant cluster the way English -kt-/-ktr- does, showing Hungarian lacks true branching onsets. pp. 101–102 |
| bú / falu | 'sorrow' / 'village' | noun | core | — | contemporary | Budapest (ECH); dialect variation noted (Innovative vs. Conservative ECH) | regional (ECH-internal register split) | grammar_reference | n/a | n/a | central minimal-word-constraint data: monosyllabic high-vowel-final stems are always long (bú), polysyllabic ones vary by speaker generation between long/short (falu), motivating the bimoraic Stem/Wordmin = μμ constraint. pp. 144–146 |
| sír / vár-t | 'grave' / '3sg waited (past)' | noun / verb form | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | central VVCC morpheme-structure-constraint data: monomorphemic long vowel + CC is banned except before /e˘, a˘/ (sír-t, vár-t show the constraint doesn't apply across a morpheme boundary at all). pp. 150–153 |
| tökör / tükör | 'mirror' | noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | example vowel-inventory item for the front-rounded harmonic ("IA-f") class. p. 66 |
| bika / kordé | 'bull' / 'cart' | noun | core | — | contemporary | Budapest (ECH) | — | grammar_reference | n/a | n/a | "mixed stem" examples cited as neutral-vowel-plus-back-vowel co-occurrence within a monomorphemic stem, motivating the front-unrounded-vowels-are-harmonically-neutral analysis. p. 63 |
| pénz / benzin | 'money' / 'petrol' | noun | core | — | contemporary; loanwords | Budapest (ECH) | — | grammar_reference | n/a | n/a | source's own example of intrusive/epenthetic [d] in /nz/ clusters (parallel to the dialectal péndz form Kornai's `007` cited as dialectal — this source treats the ECH form itself as containing an optional intrusive stop, not dialectal deviation). p. 87 |

### Morpheme breakdown

> **rumomat**-type alternations are not directly discussed in this source (see `007` for Kornai's
> treatment); this source's own comparable worked example is **vár-ná-lak** = vár ("wait for") + ná
> (conditional marker, front/back-alternating and low-vowel-lengthening-derived from -na/ne/ná/né)
> + lak (a fused 1sg-subject/2sg-object portmanteau ending, replacing the ordinary indefinite 1sg
> ending -k when the object is 2nd person) = "I would wait for you." Illustrates that Hungarian verbal
> morphology has a genuinely irregular portmanteau slot (the "-lak/-lek" 1→2 object form) layered on
> top of the otherwise fully regular four-paradigm (present/past/conditional/imperative) × two-way
> (definite/indefinite) agglutinative system. p. 36, footnote 17

> **vizet** (accusative of víz 'water') = víz (Class-IIA-f harmonic-neutral stem, underlyingly long
> /i˘/) + et (accusative, front-vowel alternant since víz's transparent /i˘/ passes through to select
> front harmony) — but crucially the stem vowel itself has shortened (í → i) because víz is listed
> among the FSVS ("Final Stem Vowel Shortening") nominal stems (Table 9): the *same* accusative
> suffixation event triggers both vowel-harmony suffix selection and stem-vowel shortening, two
> formally independent processes converging on one surface form. pp. 56–59

> **futósí** = futó ("running," present participle of fut 'run') + sí ("ski") — a compound, hence two
> separate analytic domains for both vowel harmony *and* the domain-final-vowel-length constraint.
> This is why the long í of sí survives even though it is polysyllabic *within the whole word*: the
> minimal-word/bimoraicity constraint (Stem/Wordmin = μμ) is evaluated per-stem, not per-orthographic-word,
> and sí is itself a free monosyllabic stem whose long vowel is protected. Contrast with monomorphemic
> polysyllabic falu ("village"), whose final short u shows generational vacillation precisely because
> there is no compound-boundary protection. pp. 144–146

---

## Grammar points

### 1. Framework: derivational Lexical Phonology with an analytic/synthetic domain distinction

The book adopts a rule-based (not Optimality-Theoretic, Declarative, or Government-Phonology)
derivational framework, explicitly for descriptive-coverage reasons rather than theoretical
preference: Hungarian phonology (outside vowel harmony) was under-described in the international
literature at the time of writing, and non-derivational frameworks' assumptions were "still in a
state of flux," making a broadly accessible derivational treatment more useful. The central formal
device introduced in Ch. 1 (used throughout the whole book) is a new **analytic vs. synthetic**
suffix distinction, borrowed in spirit from Government Phonology's opaque/transparent domain
boundaries but applied more broadly: analytic morphological boundaries (compounds, preverbs, and
some suffixes like -ban/-ben 'in') are opaque to phonotactic/syllabification interaction, while
synthetic suffixes (like -t/-ot/-et/-öt 'acc.') are transparent to it. This cross-cuts the
traditional derivational/inflectional distinction and the traditional *jel*/*rag* classification —
a suffix's analytic/synthetic status is determined by its phonological behavior, not its
morphosyntactic category. Rule application is organized into two ordered lexical "Blocks"
(roughly Level 1/Level 2 in classical Lexical Phonology terms), with Block 1 rules subject to a
Derived Environment Constraint (not the classical Strict Cycle Condition) and an extended syllable
template (including the appendix, see grammar point 8) becoming available only in Block 2. pp. 3–12

### 2. Feature geometry: Clements/Hume unary place features shared across vowels and consonants

The book adopts a version of the Clements and Hume (1995) feature-geometric model in which vowels
and consonants share the *same* unary place-articulator features — LAB (labial), COR (coronal),
DOR (dorsal) — rather than the classical SPE split where vowel place is [±back]/[±round] and
consonant place is [±coronal]/[±anterior]. This is empirically motivated (not just elegant): front
vowels pattern with coronal consonants for **COR harmony** (a front vowel's COR spreads onto a
following vowel bypassing an intervening consonant's own COR node, because vowel-COR and
consonant-COR sit on different *planes* of the same tier and don't cross-block each other) — the
worked example is *megy-ek* [mεdyεk] 'I go' where the stem e's COR spreads past the palatal gy's COR
onto the suffix vowel, vs. *vagy-ok* [vçdyok] 'I am' where a back vowel is unaffected by the
following consonant's COR. pp. 7–9

### 3. The Hungarian vowel inventory: 14 phonemic vowels, no true diphthongs

The lexical vowel inventory is 14 items (7 short/long pairs by spelling), reducible to a 3-height ×
3-place (COR/LAB/DOR) × [±long] unary system once /á/ and /é/ are analyzed as differing from /a/
and /e/ *only* in length (their surface height/roundness differences are attributed to phonetic
implementation, not underlying feature content) — argued from Low Vowel Lengthening and Stem Vowel
Shortening both needing to be uniform quantity-only processes (see grammar points 4–5). Four
"marginal vowels" occur only in restricted contexts. The book argues at length, using two
independent diagnostic tests (yes/no-question intonation placement and the "bird language" ludling
that doubles each syllable's nucleus), that surface [ai̯]/[au̯]-type sequences in words like *ajtó*
'door' and *autó* 'car' are **not** underlying diphthongs: *j*-final sequences are consonant+vowel
(since /j/ is independently shown to be a consonant — see grammar point 7), and *au*-type sequences
are either a genuine (surface-only) rising diphthong for some speakers or a vowel-hiatus-plus-glide-
formation-rule for others, but never an underlying nucleus-internal unit — standard Hungarian has
**no lexical diphthongs**. pp. 15–18

### 4. Low Vowel Lengthening (LVL): morpheme-final short low vowels must lengthen before a suffix

A short low vowel (a, e) that is morpheme-final becomes long (á, é) whenever a suffix follows,
regardless of word class or whether the vowel belongs to the stem or an earlier suffix (*fa* 'tree'
→ *fá-t* 'tree-acc'; *tart-ja* 'holds it' → *tart-já-k* 'they hold it'). Formalized as a negative
filter banning [+open1] at the right edge of a stem before a following segment. A set of apparent
counterexamples (compound-internal position, some derivational suffixes like *-szerü⁄*, temporal
adverbial *-kor*) shows the lengthening is sensitive to the analytic/synthetic distinction and is
deferred to the dynamic (process) analysis in the sibling chunk's Ch. 6. pp. 56–58

### 5. Stem Vowel Shortening (SVS): Final (FSVS) vs. Internal (ISVS)

A long stem vowel can shorten before certain suffixes. **FSVS** applies only to the final syllable
of mono-/bisyllabic stems, is triggered by (mostly) inflectional suffixes, primarily affects low
vowels (á, é), is largely idiosyncratic per-stem (a fixed, tabulated list — Table 9 — of ~90
monomorphemic nouns, mostly monosyllabic), and **every FSVS stem is also a "lowering" stem**
(requires the /a/ rather than /o/ linking-vowel alternant before the accusative — cross-referenced
to the sibling chunk's §8.1.3). **ISVS** can affect any syllable, is triggered only by (bisyllabic,
vowel-initial, harmonically non-alternating, mostly Latinate) derivational suffixes like *-ista,
-izál, -ikus, -itás*, and always targets the antepenultimate-or-earlier syllable (a "Trisyllabic
Shortening" pattern, explicitly compared to English) — except the monosyllabic suffix *-ál*, which
targets the penult. The two patterns are argued to be phonologically the *same* underlying
alternation (long → short) differing only in domain/triggering-suffix-class, which is itself
evidence for treating /á, é/ as length-only variants of /a, e/ (a quality-based analysis would need
two unrelated processes — see also grammar point 10). pp. 58–63

### 6. Vowel harmony: neutral/transparent vowels and the five-way stem-class typology

Vowel harmony's domain is the phonological word (stem + all suffixes); compounds and preverb+verb
combinations each contain as many independent harmonic domains as they have stem morphemes.
Front unrounded vowels (i, í, e, é) are analyzed as **harmonically neutral**, not front-harmonic:
they co-occur freely with back vowels in monomorphemic stems and — crucially — they let harmony
*pass through* them (are transparent) to a following suffix, distinguishing them from the small
closed set of genuinely disharmonic stems. Stems are cross-classified into a 2×2 typology
(harmonic/neutral × simple/complex) yielding five practically distinct behaviors, tabulated
exhaustively in the source's Table 11: **IA** simple harmonic (regular, one backness value plus
optional neutral vowels — the majority pattern); **IB** complex/"disharmonic" harmonic (back +
front-rounded co-occur in one stem, e.g. *sofo⁄r*; suffix choice follows the *last* harmonic vowel);
**IIA** simple neutral, itself split into the regular front-suffix-taking majority and a closed
~60-item "antiharmonic" minority (e.g. *híd*) that idiosyncratically takes back suffixes despite
having only neutral vowels; **IIB** complex neutral (neutral final vowel, harmonic vowel earlier —
split into **üveg**-type, where transparency is unfalsifiable either way, and **papír**-type, where
transparency is the *only* possible explanation, since a back vowel precedes an all-neutral tail
that nonetheless takes back suffixes). Rounding harmony (the o/ö/e three-way suffix alternation) is
argued to be a genuinely distinct, much simpler subsystem: no stem-internal disharmony analog
exists, no neutral vowels exist for it, and no antiharmonic stems exist for it (except indirectly,
through "lowering" stems' quaternary alternants — cross-referenced to Ch. 8 in the sibling chunk).
pp. 63–74

### 7. The status of /e/ and the "mixed" stem sub-patterns (vacillating vs. disharmonic)

Whether short /e/ is harmonically neutral is treated as the single most contested empirical question
in the vowel-harmony literature, and the book takes a data-driven middle position: /e/ is *primarily*
neutral (supported by its articulatory features and by the small closed *haver*-class), but a
distinct closed subclass of stems (*kódex, november, operett, oxigén*) show it is **opaque** —
acting as if it were a harmonic vowel that "restarts" the domain — while yet another subclass
(*dzsungel, konkrét, analízis*) genuinely **vacillates** between the two behaviors, sometimes even
for a single speaker. The three-way split (neutral / opaque-disharmonic / vacillating) correlates
systematically with two factors: the height of the final neutral vowel (i/í almost always neutral;
é mixed; e most often opaque or vacillating) and whether the stem has one vs. two-or-more trailing
neutral-vowel syllables (summarized in the source's own cross-tabulation, its Table (37)). This
finding is more fine-grained than Kornai's treatment in `007` (which flagged /e/'s ambiguous status
but did not work out the full three-way empirical split). pp. 69–72

### 8. No branching onsets in Hungarian; word-initial/medial clusters are "appendix + onset" edge structures

Using Blevins's (1995) parametric typology of syllable types, the book argues Hungarian sets
**Complex Onset = NO** despite superficially abundant word-initial CC/CCC clusters (*prém, ptózis*):
the diagnostic evidence is that Hungarian, unlike English, systematically lacks the *medial* CCC
clusters a true branching-onset language should show wherever the corresponding CC cluster exists
word-medially (English has both *-kt-* (vector) and *-ktr-* (electronic); Hungarian has *-kt-*
(akta) but no matching *-tkC-* alongside its attested *-tk-* (atka)). The ~300 monomorphemic words
with genuine medial -CCC- clusters are treated as accidental residue of source-language phonotactics
in loanwords, not evidence for branching onsets. All word-initial and word-medial consonant clusters
are instead analyzed as an unsyllabified consonant plus a following simplex onset, licensed by a
special subsyllabic constituent called the **appendix** — a formal device borrowed from the
permissive (as opposed to Government-Phonology-style strict) approach to "edge effects." pp. 96–103

### 9. Complex codas exist but are strictly binary; extra consonants are appendix material, not coda

Unlike onsets, Hungarian codas *can* branch (Complex Coda = YES), but only up to two consonants; any
apparent word-final CCC or CCCC cluster is analyzed as a genuine binary coda plus one or more
appendix consonants. The clearest diagnostic evidence is that three specific suffixes — definite
imperative *-d*, indefinite imperative *-j*, and 2sg present indefinite *-sz* — attach freely to
*any* stem regardless of what consonant(s) the stem ends in, routinely creating clusters that violate
sonority sequencing/government (*lopsz* 'you steal', with /p/ less sonorous than /s/ in violation of
the expected coda-internal sonority profile) — behavior that only makes sense if these suffix
consonants sit outside the coda proper, in a final appendix position mirroring the initial appendix
of grammar point 8. This closes the phonotactic argument that Hungarian syllable structure has *no*
genuine complex onsets or complex-beyond-binary codas once edge effects are factored out — a
significant, well-evidenced typological claim about the language. pp. 105–121

### 10. Morpheme Structure Constraints: the bimoraic minimal-stem/word and the VVCC ban

Two closing MSCs (constraints holding within the morpheme domain, distinct from syllable structure
constraints proper) round out Part II and connect directly back to the vowel-length material of
Chapter 3. First, **domain-final short mid vowels (o, ö) are categorically banned** — the constraint
holds at the right edge of any stem, not just the whole word, and even loanwords ending in o/ö are
automatically lengthened on borrowing. Second, **domain-final high vowels (i, í, u, ú, ü, ü⁄)**
pattern by a **bimoraic minimal-word constraint** (Stem/Wordmin = μμ): monosyllabic high-vowel-final
stems are *always* long (*bú* 'sorrow'), but polysyllabic ones show a real, book-documented three-way
sociolinguistic split across Innovative/Intermediate/Conservative ECH speaker generations (short
uniformly / optionally long / long uniformly, respectively) — an explicit, source-marked case of
live sound change captured mid-progress. Third, a closing **morpheme structure constraint bans long
vowels (other than /e˘, a˘/) before a tautomorphemic consonant cluster** (*VVCC domain: morpheme,
condition: VV ≠ /e˘, a˘/*) — and the book argues explicitly that /e˘/ and /a˘/'s privileged exemption
is *not* an arbitrary stipulation but falls directly out of treating them as underlyingly
[+open1,+open2] rather than genuinely long (the same representational choice — length-only,
quality-predictable-from-length — that unified Low Vowel Lengthening and Stem Vowel Shortening in
Chapter 3): reversing that representational choice would fragment LVL and SVS back into two
unrelated, vowel-specific processes, which the authors treat as decisive evidence against the
alternative analysis. This is the strongest explicit thread in the whole assigned chunk tying vowel
harmony/length material (Ch. 3) to phonotactics (Ch. 5) — flagged as directly relevant to future
Hungarian slang-mechanics analysis, since it shows the featural representation of a single vowel
pair predicting *three* independently-observable surface constraints at once. pp. 143–153

### 11. Consonant system highlights: /j/ as liquid not glide; /ty dy/ as stops not affricates; no
underlying /dz/

Three focused segmental-classification arguments recur through Ch. 4, each argued from converging
distributional/alternation evidence rather than asserted: (i) **/j/ is a consonantal liquid**, not a
glide or the vowel /i/ in non-nuclear position — evidenced by syllabification minimal pairs (*mágia*
vs. *máglya*) that are only representable if /i/ and /j/ are segmentally distinct, by /j/'s ability to
trigger l-palatalization and undergo j-assimilation as a consonantal target/trigger, and by its
fricative allophones ([ç]/[ʝ]) in coda position, which are easier to derive from an underlying
[+cons] segment. (ii) **/ty dy/ are phonologically stops, not affricates** — despite variable
surface affrication depending on stress/rate/style, they show unreleased pre-stop allophones (like
stops, unlike affricates) and undergo obligatory OCP-driven fusion across word boundaries in casual
speech (again patterning with stops, not with genuine affricates like /ts, c&/, which resist such
fusion in careful speech). (iii) **No underlying /dz/ exists as a phoneme** — all surface [dz] is
derived either by voice assimilation of /ts/, by optional stop-epenthesis in /nz/ clusters (*pénz*,
*benzin* — notably the *undialectal*, standard-ECH version of exactly the epenthesis pattern Kornai's
`007` recorded as dialectal for related forms like *péndz*), or by coalescence of an underlying /d-z/
cluster into a true geminate affricate — with the /d-z&/ vs. /dz&/ (the "dzs" case) status left more
genuinely unresolved, favoring gradual lexical diffusion from cluster to unitary-phoneme status.
pp. 82–89

### 12. Word order: topic + comment, not a fixed SVO/SOV type

A brief but important non-phonological grammar point carried in Ch. 2 for later cross-reference:
Hungarian cannot be classified in the standard SVO/SOV typology (all combinations occur depending on
definiteness/topicality), but its apparent "free word order" is not truly free — following É. Kiss
(1987), the book adopts a topic+comment structural analysis where a sentence's immediate constituents
are (i) one or more topics, (ii) an optional focus position immediately before the verb (which can
be filled by a focused constituent, a wh-word, a negative particle, or one of several "verb modifier"
types — preverbs, bare-noun objects, result/goal adverbials), and (iii) the verb plus a postverbal
remainder. Whatever fills the focus slot renders the verb itself stressless, and only a genuinely
*focused* element in that slot makes the whole comment an eradicating-stress domain — this ties
directly into the stress/intonation system (§2.3) recorded separately below. pp. 43–48

### 13. Stress and intonation: fixed initial word stress, but a rich independent sentence-level system

Word-level: Hungarian words are (with a few marked exception classes — certain interjections,
compound numerals, exclamations, corrective-focus answers) invariably stressed on the initial
syllable regardless of morphological complexity, and the book explicitly rejects the widely-cited
claim (Hammond 1987 et al.) that Hungarian shows a regular superimposed trochaic/"cola" secondary-
stress rhythm, arguing native-speaker intuition does not support it and that it is phonologically
inert even if it exists physically. Sentence-level: stress is governed by two independent
phenomena layered on top of word stress — **enclisis** (certain function words obligatorily join the
stress domain of the preceding word) and **stress eradication** (a focused constituent's stress
"erases" all following lexical stresses within its domain until the next eradicating stress or
sentence end), the latter producing a systematic ambiguity between flat (neutral) and eradicating
(contrastive/emphatic) prosody that is only disambiguated by adding further material to the sentence.
Following Varga (1996), the book catalogs eleven distinct "character contours" (pitch-contour types,
not simple high/low binaries) organized into front-falling, sustained, and end-falling groups, each
with productive phonetic variants depending on how many syllables are available to spread the
contour over. pp. 21–26

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary/cluster tables,
derivational-suffix catalogs, or explanatory prose. Large illustrative tables (word lists, cluster
inventories, conjugation paradigms) are described/summarized rather than reproduced in full, per
`00_Reference_Extraction_Spec.md`.
