# Hungarian — Established Grammar/Vocabulary: *On Hungarian Morphology* (Kornai), Section 4 "Inflectional Morphology" through Bibliography

**Source:** András Kornai, *On Hungarian Morphology* (Linguistica, Series A: Studia et Dissertationes
14, Linguistics Institute of the Hungarian Academy of Sciences, Budapest; originally a 1990s MIT PhD
dissertation), PDF pages 81–158 of 158 (printed pages ~80–157), covering the end of §3 (feature-system
wrap-up), all of §4 "Inflectional Morphology" (§4.1 Conjugation, §4.2 Declension, §4.3 Implementation —
Two-Level/KIMMO computational morphology, §4.4 Conclusion), and §5 Bibliography (pp. 148–157, not
extractable — a reference list only). A sibling subagent covers PDF pages 1–80 (phonology, feature
system, earlier chapters) in a companion file; this file picks up exactly where that one's assigned range
ends, verified by direct inspection of PDF page 81 (which opens mid-paragraph on "4 Inflectional
morphology," a clean section boundary).

**Source-genre note.** Unlike this project's other Hungarian sources (Rounds' pedagogical grammar,
already covered in `established/001`–`003`), this is a formal generative/autosegmental-phonology
dissertation aimed at theoretical linguists, not language learners. Per this dispatch's own instructions,
this file prioritizes the paper's own morphological generalizations, worked paradigms, and productivity/
allomorphy claims as grammar-point prose — the vocabulary table is deliberately secondary and thin,
since the source is almost entirely metalinguistic argumentation about *how* Hungarian's morphology
works, not a running vocabulary of everyday words. Most "vocabulary" here consists of paradigm-stem
words (`vár`, `kér`, `tűr`, etc.) that exist to illustrate a rule, not free-standing lexical items in the
pedagogical-grammar sense.

**Coverage note.** Every substantive morphological generalization, worked paradigm, and productivity/
allomorphy claim in this range is captured below. Deliberately **not** reproduced: the paper's own
formal notation (autosegmental feature-geometry diagrams, timing-tier/CV-skeleton trees, Two-Level
Morphology rule syntax) — these are theoretical apparatus for deriving the surface forms, not
independently useful data for this project; the substantive claims those formalisms are arguing for are
paraphrased in prose instead. Also skipped as non-extractable: the closing §5 Bibliography (pure
reference list, pp. 148–157).

**Vision-reading note:** not applicable — this PDF has a genuine text layer (`pdftotext -layout`
extracted cleanly); no vision-reading was needed for this range.

**PDF-corruption gotcha (worth flagging for future extractions from this same host):** an earlier
extraction pass of this same page range, written to a shared `/tmp/full.txt` scratch file, was silently
overwritten mid-task by a concurrent sibling subagent's own `pdftotext` output for a *different* source
document — the two processes share `/tmp` on the same machine. Re-extracting into this project's
dedicated per-session scratchpad directory (rather than a generic shared temp path) resolved it and
produced a stable, verified 3,196-line/26,324-word extraction ending cleanly at the bibliography. Future
subagents on this project should write scratch extraction files to their own session scratchpad, not a
bare `/tmp/<name>.txt`, to avoid this exact collision.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| vár | 'wait' | verb | core | — | contemporary (source: dissertation-era, Linguistica series) | — | — | grammar_reference | n/a | n/a | one of the paper's three primary conjugation-paradigm illustration verbs (regular, vowel-final stem). See Morpheme Breakdown/Grammar points §4.1. p. 81 (PDF) |
| kér | 'ask (for)' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | second primary paradigm verb, parallel to `vár` but front-vowel harmonic class. p. 82 (PDF) |
| tűr | 'suffer, endure' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | third primary paradigm verb, front-rounded harmonic class. p. 82 (PDF) |
| lát | 'see' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | illustrates the t-final stem class and the C(imp) `t+j → ss` alternation (`lássak`, not `*látjak`); contrasted with `tart` 'keep', which instead affricates to `tarts`. pp. 95–99 (PDF) |
| told | 'lengthen' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | illustrates the CC-final stem class, with dialectal optionality of the epenthetic vowel marked `%(a)` throughout its paradigm (e.g. `told%(a)sz`). pp. 96–97 (PDF) |
| zongorázik | 'play the piano' | verb (ik-verb) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | the paper's ik-verb paradigm example; citation form itself carries `-ik`. pp. 97, 103 (PDF) |
| eszik | 'eat' | verb (ik-verb) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cited as a frequent transitive ik-verb that most Educated Colloquial Hungarian (ECH) speakers use with the "correct" Standard Literary Hungarian (SLH) 1sg form despite the ik-rule being only optional in ECH — argued to be memorized whole rather than rule-derived. p. 103 (PDF) |
| iszik | 'drink' | verb (ik-verb) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | paired with `eszik` as the paper's example of a frequent, irregular, memorized ik-verb. p. 103 (PDF) |
| áll | 'stay, stand' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 3sg.past.indef `állt` vs. lexicalized past-participle-as-adjective `állott` 'stale' — cited as showing the past-participle-final-t rule has been reanalyzed/lexicalized separately from the live verbal paradigm. p. 98 (PDF) |
| hall | 'hear' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | geminate-`l`-final stem taking the `-ott` allomorph (an exception to the elsewhere pattern where such stems would take bare `-t`). p. 98 (PDF) |
| marad | 'remain' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | -Vd-final stem taking bare `-t` rather than `-ott` — cited as the counter-exception showing the elision rule's exceptions run in both directions. p. 98 (PDF) |
| tanít | 'teach' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | single-consonant-final stem that nonetheless triggers epenthesis in the infinitive (`tanítani`, *`tanítni`) — argued to have an underlying final CC (an extra empty C-slot) despite its single surface consonant. pp. 100–101 (PDF) |
| lő | 'shoot' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | "abstract w-stem" verb: 1sg `lövök`, not `*lők` — v-epenthesis parallel to the noun v-stems (`ló`→`lovak`) covered in `established/002`. p. 108 (PDF) |
| nő | 'grow' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | second w-stem verb example: 1sg `növök`, not `*nők`. p. 108 (PDF) |
| ugrik | 'jump' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | vowel-drop verbal stem: imperative `ugorj` vs. 3sg.def `ugrom` — cited alongside `-ik` class stems as needing nonstandard CV representations. p. 108 (PDF) |
| úr | 'master, lord' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class I possessive-paradigm example stem; full 12-cell paradigm reproduced in Grammar points. See Morpheme Breakdown. p. 111 (PDF) |
| sógor | 'brother-in-law' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class II possessive-paradigm example stem (fleeting/unstable-vowel type). p. 111 (PDF) |
| ember | 'man, person' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class III possessive-paradigm example stem. p. 111 (PDF) |
| hölgy | 'lady' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class IV possessive-paradigm example stem (front-rounded harmonic class). p. 111 (PDF) |
| őr | 'guard' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class V possessive-paradigm example stem. p. 111 (PDF) |
| zár | 'lock' | noun/verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | minimal-pair evidence that nominal and verbal paradigms are distinguishable at the floating-length level: nom.pl `zárak` vs. 1sg.pres.indef `zárok`; 1sg-possessed `záram` vs. 1sg.pres.def `zárom`. p. 89 (PDF) |
| nyár | 'summer' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | vowel-shortening accusative stem: `nyarat`, not `*nyárat` — contrasted minimally with `gyár` (below), which does not shorten. p. 106 (PDF) |
| gyár | 'factory' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | non-shortening accusative stem: `gyárat`, not `*gyarat` — the paper's minimal-pair evidence that vowel shortening before the accusative is lexically, not phonologically, governed. p. 106 (PDF) |
| iker | 'twin' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | vowel-drop accusative stem: `ikret`. Minimal-paired against `siker` (below) for the same lexical-governance argument as `nyár`/`gyár`. p. 106 (PDF) |
| siker | 'success' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | non-vowel-drop accusative stem: `sikert`, not `*sikret`. p. 106 (PDF) |
| cukor | 'sugar' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | listed among stems with an unstable stem-internal vowel that is NOT predictably `o` by default — acc. `cukrot`, sue. `cukron`, elative `cukorból` (only ACC/SUE trigger vowel-drop). p. 107 (PDF) |
| sátor | 'tent' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | unstable-vowel stem: acc. `sátrat`. p. 107 (PDF) |
| kazal | 'haystack' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | unstable-vowel stem: acc. `kazlat`. p. 107 (PDF) |
| bajusz | 'mustache' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | unstable-vowel stem: acc. `bajszot` — cited specifically to disprove a "default vowel is always o" analysis, since the dropped vowel here is not o. p. 107 (PDF) |
| kebel | 'bosom' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | unstable-vowel stem: acc. `keblet`. p. 107 (PDF) |
| tükör | 'mirror' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | unstable-vowel stem: acc. `tükröt` (also appears as a fleeting-vowel plural example in `established/002`, pl. `tükrök`). p. 107 (PDF) |
| lélek | 'soul' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | flagged as the one stem requiring BOTH the shortening rule and the vowel-drop rule simultaneously: `lelket` (acc.), `lelken` (sue.), `lélekig` (terminative, unaffected). p. 107 (PDF) |
| varjú | 'crow' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | alternates `varjú`/`varjat` — cited alongside `borjú` as needing a floating-length-deletion rule. p. 108 (PDF) |
| borjú | 'calf' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | alternates `borjú`/`borjat`; also `borja` (possessed) — the "borjú class" additionally has an unassociated (floating) `j` that fuses with a following suffix `-j-`, described as an OCP-like effect. pp. 108, 112 (PDF) |
| idő | 'time' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | one of a small closed set of nouns (with `borjú`, `ajtó`, "perhaps a dozen others") requiring a floating rather than fully-linked final long vowel; 3sg-possessed `ideje`. p. 112 (PDF) |
| ajtó | 'door' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | same floating-vowel closed class; 3sg-possessed `ajtaja`; plural-possessed shows genuine three-way dialectal vacillation `ajtói` ~ `%ajtai` ~ `%ajtajai` 'its doors'. p. 112 (PDF) |
| eskü | 'oath' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | superessive `eskün`, illustrating that short high/rounded stem-final vowels (i, u, ü) select the bare `-n` allomorph rather than a linking vowel. p. 109 (PDF) |
| baba | 'doll' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | superessive `babán` — worked example of the SUE-allomorph-selection algorithm (checks vowel length, then A-tier feature). p. 109 (PDF) |
| pince | 'cellar' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | superessive `pincén` — simplest case, vowel-doubling-to-gemination. p. 109 (PDF) |
| Péter | 'Peter (name)' | proper noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | used throughout the anaphoric-possessive-é discussion: `Péteréi` 'more than one of something possessed by Peter' vs. `Péterék` 'the Péter family/household' — worked semantic contrast; also `%Péteréé` 'something belonging to something belonging to Peter' cited as a dialectal iterated-é form. pp. 113, 115 (PDF) |
| Kovács / Horváth | (Hungarian surnames) | proper noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | `Kovácsék` 'the Kovács family' (also appears independently in `established/002`, p. 77) and `Horváthék könyve`/`*könyvük` 'the book of the Horváth family' — evidence that a plural-noun possessor triggers 3sg (not 3pl) agreement on the possessed item, unlike a 3pl pronoun possessor (`az ő könyvük` 'their book'). p. 113 (PDF) |
| leg- | superlative prefix | prefix | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Hungarian's only true prefix (besides the derived `leges-`); combines with adjectives, e.g. `legnagyobb` 'biggest' (also independently attested in `established/002`, p. 85). See Grammar points §4.1/§4.3. p. 113 (PDF) |
| leges- | ultra-superlative prefix | prefix | core | — | contemporary | — | — | grammar_reference | n/a | n/a | derived from `leg-` + `-as/es/os/ös`; iterable: `legeslegeslegeslegnagyobb` 'the very very very greatest.' p. 84 (PDF, cross-ref) / p. 125 (PDF, ULTRA0 lexicon) |
| magas | 'tall' | adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | sample entry from the paper's own computational adjective lexicon (LEXICON A) print-out — shown as a worked example of the entry format `stem ContClass "gloss-code-string"`. p. 119 (PDF) |
| fess | 'dapper, natty' | adjective | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | listed as a sample adjective-lexicon entry; separately, `fess` (verb) 'paint 1sg.imp.def' appears as a minimal-pair example for the t+j→ss assimilation rule (`festjük`/`fessük` 'paint 1pl.pres.def/imp.def'). pp. 99, 119 (PDF) |
| mászik | 'climb' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | `mássz` 2sg.imp.indef — worked example distinguishing consonant-cluster-conditioned affrication from full assimilation. pp. 98–99 (PDF) |
| oszt | 'deal (cards)' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | `ossz` 2sg.imp.indef — the special case where a preceding coronal fricative blocks affrication and yields apparent t-deletion instead. p. 99 (PDF) |

### Morpheme breakdown

> **legeslegeslegeslegnagyobb** = leges- (ultra-superlative, iterated ×3) + leg- (superlative) + nagy
> ("big") + obb (comparative) — "the very very very greatest." The paper's own worked illustration that
> Hungarian's degree system is formally *open*: `leges-` can be prefixed indefinitely, each iteration
> adding one degree of intensification, unlike the closed superlative/comparative system alone. p. 85
> (PDF, cross-referenced from §3; the mechanism itself, `leg`/`leges` as a productive ROOT-lexicon
> loop, is formally implemented at p. 125 PDF, LEXICON ULTRA0/ULTRA/SUP).

> **ismerősömhöz**-style suffix stacking, generalized: the paper's own worked possessive-paradigm
> table (28) shows that a single stem like **úr** ("master") can take, in sequence: (person/number of
> possessor) + (number of possessed) — e.g. **uraitok** = úr + ai (plural-possession marker "more than
> one urad") + tok (2pl possessor, "your (pl.)") = "your (pl.) masters." Five parallel stem classes are
> tabulated (úr, sógor, ember, hölgy, őr), each showing the identical 12-cell person×number×number
> paradigm, differing only in their harmonic-vowel and stem-alternation behavior — direct, source-
> internal confirmation of the productive, fully regular nature of Hungarian possessive suffix-stacking
> beyond the single worked examples already captured in `established/002`. p. 111 (PDF)

> **Péteréi** = Péter + é (anaphoric "something possessed by," non-attributive possessive) + i (plural
> marker on the possessed item, "more than one of") — "(more than one of) (something possessed by)
> Péter," i.e., "Peter's [things]" (plural, non-attributive). Source's own worked semantic decomposition,
> explicitly contrasted with the next entry to show that two suffix combinations with near-identical
> paraphrases nonetheless have distinct internal bracketing/derivational histories. pp. 114–115 (PDF)

> **Péterék** = Péter + ék (family/associative suffix, "more than one of + something possessed by," but
> lexicalized as a single portmanteau rather than compositional é+k) — "the Péter family/household."
> The source argues `ék` cannot be treated as freely compositional `é + k` in every dialect: in "dialect D"
> `ék` is in complementary distribution with the ordinary plural-possessed markers, while in "dialect S"
> it patterns more regularly as literal `é+k`, except that `ék` additionally carries an extra semantic
> restriction (denotes only humans/families) that a fully compositional `é+k` would not predict — so the
> complex form still has to be listed in the lexicon as its own entry regardless of dialect. pp. 113–115 (PDF)

> **ideje** = idő ("time," small closed class with an unlinked/floating final long vowel) + je (3sg
> possessive, allomorph selected because the stem's final vowel is floating rather than fully associated)
> — "its time." Source's own example of a phonologically-driven allomorph choice (`je`, not the
> otherwise-expected bare linking pattern) triggered by an idiosyncratic, lexically-marked stem property
> shared by only a dozen or so nouns (`idő`, `borjú`, `ajtó`, ...). p. 112 (PDF)

## Grammar points

### 4.1.1 Two competing typological analyses of the verbal paradigm — "agglutinating minimum" vs. observed complexity

The paper opens its inflectional-morphology chapter by tabulating the full paradigmatic forms of three
regular verb stems (`vár` "wait," `kér` "ask," `tűr` "suffer") across present/past/imperative/conditional
mood, singular/plural number, and indefinite/definite conjugation — 16 cells × 3 stems, plus a parallel
"infinitival conjugation" (the form a verb takes with auxiliaries like `kell` "must") and an "implicative"
paradigm used specifically when the subject is 1sg and the object is 2nd person (`várlak` "I [wait] for
you"). This yields 64 distinct paradigmatic word-forms per stem. Kornai then asks how many of these
forms are genuinely decomposable into separable, single-function morphemes — testing Hungarian's
reputation as a paradigm case of "agglutinating" morphology (citing Hall 1944) against a strict count. p.
81–83 (PDF)

**Key finding — Hungarian is only "roughly halfway between agglutinating and inflecting."** A fully
agglutinative system with the observed set of oppositions (3 persons + 4 tense/mood values + 2 numbers
+ 2 definiteness values, plus the special 1st-subject/2nd-object portmanteau `-lAk`) would need a
theoretical minimum of 12 "pure" suffixes to generate all 52 relevant paradigmatic forms (log₂-style
combinatorial minimum). The system Kornai actually derives requires 17 regular suffixes plus 9 further
irregular ones — roughly *twice* the theoretical agglutinative minimum. He attributes this gap partly to
genuine irregular/suppletive formations, and partly to the fact that only *one* clean structural split could
be established in the morphosyntactic tree: tense/mood suffixes form one class, person/number/
definiteness suffixes form a second, and only these two classes are independently combinable — there is
no further splitting of, say, definiteness from person/number into separately-suffixable pieces, because
no single morpheme carrying only `+definite` can be isolated (argued at length via the behavior of the
`ja/i` suffix, pp. 92–93 PDF). **Typological upshot for this project's typology profile:** Hungarian's real
agglutinative "purity" is uneven across subsystems — the paper separately finds the *possessive* system
(nominal, not verbal) comes much closer to the pure agglutinative minimum (7 suffixes needed vs. a
theoretical minimum of ~3.6 for the 12-cell paradigm — see §4.2 below), so slang-mechanics analysis
should not assume uniform "how agglutinative is Hungarian" across all its subsystems; verbal
person/tense/definiteness marking is measurably less cleanly agglutinative than nominal possessive
marking. pp. 92–94, 113 (PDF)

### 4.1.2 Derivational suffix order is meaningful; inflectional suffix order is fixed and meaningless

A sharp, source-stated generalization: with *inflectional* suffixes, the linear order of the tense/mood
class relative to the person/number/definiteness class is fixed and carries no independent meaning (either
ordering would generate the same surface forms with the same meanings, so the actual Hungarian order
is a matter of historical convention, not grammar-internal necessity). With *derivational* suffixes,
by contrast, reordering the same morphemes changes the meaning. The paper's own worked example:
`sajtó cserélgetteti az edzővel a játékosokat` ("the press makes the coach repeatedly change the
players," frequentative-then-factitive order) vs. `sajtó cseréltetgeti az edzővel a játékosokat` ("the press
repeatedly makes the coach change the players," factitive-then-frequentative order) — same two
derivational suffixes (`-gat/-get` frequentative-repetitive, `-tat/-tet` factitive/causative), reversed order,
distinct scope of the repetition. **This is a genuinely useful, source-grounded distinction for
`morphological_play` analysis later:** inflectional-suffix reordering in Hungarian should read as simply
ungrammatical/nonce, while derivational-suffix reordering is a live, meaning-bearing grammatical
resource a slang-formation process could plausibly exploit (reordering two independently-attested
derivational suffixes for a different nuance is "playing within the rules," not breaking them). pp. 93–94
(PDF)

### 4.1.3 The ik-verb class: a memorized paradigm-marking feature, not a live phonological rule

Hungarian has a well-known irregular verb class (`ik`-verbs, e.g. `zongorázik` "play the piano," `eszik`
"eat," `iszik` "drink") whose citation form (3sg.pres.indef) ends in `-ik` rather than the otherwise-
expected zero ending, and which optionally (in Educated Colloquial Hungarian, ECH) or obligatorily (in
Standard Literary Hungarian, SLH) replace the ordinary 1sg.pres.indef ending with the 1sg.pres.**def**
ending instead. Kornai's key argument: rather than encoding "ik-ness" as an abstract diacritic feature on
the stem, the relevant irregular rules should be stored as part of the lexical entry of the morpheme `ik`
itself — because (a) `ik`-class membership is learnable from a single exposure to the (very frequent)
citation form, so it stays stable across generations, while (b) the *rule* that swaps the 1sg ending is hard
to learn (especially since most `ik`-verbs are intransitive, so the relevant contrast rarely even surfaces)
and is exactly the piece that shows dialectal loss/optionality in ECH. This is offered as an explanation for
why "most ECH speakers always use the SLH forms with the most frequent transitive ik-verbs like eszik
… or iszik," even though they don't reliably apply the same rule productively elsewhere — a piece-by-
piece memorization pattern rather than genuine rule application (with an explicit analogy to child
language acquisition, citing Berko 1958 and Bowerman 1982). p. 102–103 (PDF)

### 4.1.4 Stem-final consonant alternations before the past-tense/participle `-t`: majority rule with a lexically-governed exception set

Past-tense and past-participle `-t` triggers a VC-insertion (`-ott/-ett/-ött`) after most stems ending in an
obstruent + liquid/nasal/glide cluster, to break up an otherwise-illegal consonant cluster (worked as rule
(14) in the source, not reproduced here). This is a genuine majority pattern, but Kornai is explicit that it
has real, lexically-idiosyncratic exceptions running in *both* directions: most `-Vd`-final stems
(`marad` "remain") take the *bare* `-t` where the rule would predict insertion, while some geminate-`r`/`l`
stems (`hall` "hear") take the inserted `-ott` even though their shape doesn't obviously require it, and at
least one stem (`száll` "fly") genuinely vacillates between the two forms. The number of stems showing
this kind of idiosyncrasy "runs well into the hundreds." Methodological note directly relevant to future
Hungarian slang analysis: **the source treats a synchronically productive-looking phonological rule and
a large, real exception class as coexisting, not as evidence the rule is illusory** — this is offered as a
general modeling stance, not just a fact about `-t`-insertion. pp. 97–98 (PDF)

### 4.1.5 The t+j → ss/affrication alternation and its own conditioning hierarchy

When the imperative-mood morpheme (whose underlying form ends in a floating "yotized" `j`-like
element) attaches to a stem ending in `-t`, the outcome depends on what precedes the `-t`: (a) after a
vowel or another coronal fricative, `t+j` fully assimilates to a geminate fricative/affricate — `lát` "see" →
`lássak` (not `*látjak`); `oszt` "deal" → `ossz`; `fest` "paint" → `fess`; (b) after most other consonants,
assimilation stops short of complete fusion and instead affricates — `tart` "keep" → `tarts` (not
`*tass`). The source explicitly frames this as a genuine allomorphy hierarchy conditioned by the identity
of the segment immediately preceding stem-final `-t`, not a single uniform sandhi rule; it further notes
that in substandard/informal dialects the morphologically-conditioned version of this rule can be lost,
producing forms like `%üssük`/`%fessük` for both present and imperative 1pl.def where standard ECH
keeps `ütjük`/`üssük` distinct — an explicit, source-marked register/dialect split worth flagging as a real
colloquial-vs.-standard data point. pp. 98–99 (PDF)

### 4.1.6 Epenthesis before the infinitive marker `-ni`, including "hidden" consonant-cluster stems

The infinitive suffix `-ni` triggers an epenthetic linking vowel after any stem ending in a genuine
consonant cluster (`CC`). More interestingly, a handful of single-consonant-final stems *also* trigger this
epenthesis even though their surface form shows only one final consonant — e.g. `tanít` "teach" →
`tanítani`, not `*tanítni`. Kornai's analysis (following Vágó 1987): such stems are represented
underlyingly with an extra, empty consonant slot after the final vowel, i.e., the same abstract
"hidden cluster" representation independently needed to explain why these stems also resist the t+j→ss
full-assimilation pattern in imperative forms (`taníts`, patterning with `tart`-class stems rather than
`lát`-class ones). This is a case where two independently-observed alternations converge on the same
underlying representation — a useful example of "surface-invisible" morphological structure for a
language whose slang formation might exploit similarly hidden regularities. pp. 100–101 (PDF)

### 4.2.1 The case system: a full 17-way case inventory, ranked by "how case-like" each case actually is

The paper tabulates all of Hungarian's 17 core case endings in a single unified structural format (its own
table (27), not reproduced verbatim, only its content paraphrased here): nominative (zero), accusative
(`-t`, quaternary vowel `at/et/ot/öt`), dative (`-nak/-nek`), instrumental (`-val/-vel`), causal-final
(`-ért`), translative (`-vá/-vé`), superessive (`-on/-en/-ön`), sublative (`-ra/-re`), delative (`-ról/-ről`),
inessive (`-ban/-ben`), elative (`-ból/-ből`), illative (`-ba/-be`), adessive (`-nál/-nél`), allative
(`-hoz/-hez/-höz`), ablative (`-tól/-től`), terminative (`-ig`), and formalis (`-ként`). This is directly
comparable to, and independently confirms without contradicting, the 23-case inventory already
tabulated from Rounds' pedagogical grammar in `established/003` (the smaller count here reflects that
this source treats a few of Rounds' additional cases as "peripheral"/marginal rather than omitting them
outright — see next point). p. 110 (PDF)

**The formalis case (`-ként` "as, in the capacity of") is argued to be structurally peripheral within the
case system**, on four independent, source-stated criteria that most other cases satisfy and `-ként` fails:
(1) it does not participate in ordinary vowel harmony (it has a single, non-alternating vowel, unlike every
other harmonically-alternating case ending); (2) it does not trigger Low Vowel Lengthening, the one
general phonological process the paper argues should otherwise be stored once at the shared `CASE` tree-
node rather than repeated per-case, because virtually every other case does trigger it; (3) it has no special
case-marked pronoun form (`nekem`, `neked`... for dative; `engem`, `téged`... for accusative), unlike most
cases; (4) it is never syntactically obligatory in any verb's case-frame (`szerepel vmi-ként` "acts as
sg./plays the role of sg." is cited as its typical, always-optional context), whereas most cases are
obligatorily governed by at least some verbs. This is offered as a worked case study in how a "case
ending" can be formally present in the paradigm while gradiently less case-like than its neighbors — a
genuinely reusable analytic move for evaluating whether some other tag/marker in Hungarian slang
should be treated as a "real" case-like element or a peripheral, semi-grammaticalized one. pp. 105–107
(PDF)

### 4.2.2 Vowel harmony's alternation-arity varies by case, and is not case-system-uniform

The paper explicitly enumerates which harmonic alternation pattern each case ending follows: the
accusative is *quaternary* (four-way: `at/et/ot/öt`); the allative and superessive are *ternary*
(`hoz/hez/höz`, `on/en/ön`); the dative, instrumental, sublative, and inessive are *binary* `a/e`; the
delative, elative, and ablative are binary `ó/ő`; the adessive and translative are binary `á/é`; the
terminative, causal-final, and formalis do not alternate at all. This directly refines the general "suffixes
come in harmonic variants" statement already captured (from a different, pedagogical source) in
`established/002` §5.2.2 — the useful addition here is that the *number* of harmonic variants (2, 3, or 4)
is itself a per-case fact, not a single uniform binary/ternary/quaternary system across the whole case
inventory. p. 106 (PDF)

### 4.2.3 Low Vowel Lengthening and Vowel Drop: two related-looking but lexically distinct alternations

Case-suffixation (specifically the accusative and superessive) can trigger either of two surface changes
in a stem's own final vowel: (a) **vowel shortening/lengthening** — a stem's final long vowel shortens
before certain suffixes, or (viewed the other way) a short stem-final `a`/`e` lengthens to `á`/`é` before most
consonant-initial case suffixes (`lámpa`→`lámpát` type patterns, already covered from the pedagogical
source in `established/002`); (b) **vowel drop** — an entirely separate, stem-internal (non-final) vowel is
lost when certain suffixes attach (`cukor` "sugar" → accusative `cukrot`, superessive `cukron`, but elative
`cukorból` with the vowel retained). The source is explicit that these look superficially similar (both
"delete a vowel slot") but are **lexically, not phonologically, conditioned**, demonstrated by true
minimal pairs where the shape alone can't predict the behavior: `gyár`/`gyárat` ("factory," no shortening)
vs. `nyár`/`nyarat` ("summer," shortens); `siker`/`sikert` ("success," no drop) vs. `iker`/`ikret` ("twin,"
drops). Only the accusative and superessive cases trigger vowel-drop; other cases on the same stem
retain the internal vowel (`cukorból`, not `*cukrból`). This is a clean, source-grounded example of true
lexical idiosyncrasy layered on top of otherwise-regular Hungarian case morphology — directly useful
for `analysis/` when distinguishing genuinely productive-but-irregular alternation from wholesale
memorization. pp. 106–108 (PDF)

### 4.2.4 The possessive paradigm is Hungarian's closest approach to a "pure" agglutinative system

The paper tabulates a full 12-cell possessive paradigm (1st/2nd/3rd person possessor × singular/plural
possessor × singular/plural possessed) across five representative noun-stem classes (`úr` "master,"
`sógor` "brother-in-law," `ember` "man," `hölgy` "lady," `őr` "guard" — chosen to span the different
harmonic/stem-alternation classes already established for plain nouns in `established/002`). Unlike the
verbal system (§4.1.1 above), Kornai finds the possessive system requires only 7 suffixes to generate all
12 forms, against a theoretical minimum of log₂(12) ≈ 3.58 — "roughly the same degree of agglutination
… in both the verbal and possessive systems" is the paper's own summary phrase, but the possessive
paradigm additionally analyzes cleanly with a genuinely infixed plural-possession marker `-i-` (following
Antal 1959/1963 against competing analyses by Mel'cuk 1972 and Rácz 1974, both discussed and
rejected in the source) — Hungarian is explicitly noted as otherwise having essentially no infixes
(its only prefix at all being the superlative `leg-`), making this `-i-` a genuinely rare morphological
device within the language's own system. pp. 110–113 (PDF)

**Dialectal variation in the "familiar plural" `ék`.** The associative/family-collective suffix `-ék`
("the [X] family/household," e.g. `Kovácsék` "the Kovácses," `Péterék`) shows genuine, source-surveyed
dialectal splitting in its distribution relative to the ordinary plural-possessed markers: in "dialect D," `ék`
is in complementary distribution with plural-possessed forms; in "dialect S," `ék` instead patterns as if
freely compositional (`é` "belonging-to" + `k` "plural"), appearing after singular-possessor/plural-
possessed markers where dialect D blocks it, and being blocked instead after plural-possessor/singular-
possessed markers where dialect D allows it. The source is careful to flag this dialect split as based on
its author's own informal survey, not yet extensively field-tested (citing Labov 1975's methodological
caution about uncorroborated "idiosyncratic dialects"), and concludes neither dialect's analysis is
"deeper" than the other — both are coherent solutions to the same underlying puzzle, coexisting because
they converge on identical surface forms for the most frequently-used combinations. **Register/dialect
flag, explicit in source:** this is a genuine attested register/dialect distinction, not a hedge — worth
treating as real comparative sociolinguistic data if Hungarian slang corpus work later turns up `ék`-
suffixed forms. pp. 113–115 (PDF)

### 4.3 Two-Level (KIMMO) computational implementation — closed-class inventory sizes, not reproduced in formal detail

The paper's final technical section describes two computational implementations of Hungarian
morphology built on Koskenniemi's (1983) Two-Level Morphology formalism (a finite-state
lexicon-plus-rules system, distinct from the autosegmental-phonology framework used in the rest of the
dissertation). The formal machinery itself (finite-automaton sublexicons, "Continuation Classes," the
Two-Level rule notation with its lexical:surface correspondence pairs) is not extracted here as it is purely
an implementation detail, not new linguistic content about Hungarian — **but the closed-class inventory
sizes the source reports along the way are useful data points for corpus-scale expectations:**

- **11,420 noun stems**, **2,498 verb stems**, and **2,727 adjective stems** in the lexicon (from "ablak to
  zsuzsu," "abajgat to zsuppol," and "abesszin to zsörtös" respectively) — the paper's own working
  estimate of Hungarian's productive open-class lexical stem inventory as implemented, not a claim about
  the language's true vocabulary size. p. 116, 119, 133 (PDF)
- **835 adverbials** ("abbeli to vulgo"), **129 connectives** (fully enumerated in the source — a genuinely
  useful closed-class list, e.g. `hogy` "that," `mert` "because," `noha` "although," `ugyanis` "namely,"
  `viszont` "however," `sőt` "moreover," and colloquial-register-flavored connectives like `mégiscsak`
  "still, after all" and `úgyse(m)` "won't/doesn't anyway"), and — **most relevant to future slang-corpus
  work** — **214 "exclamations, curses, and other performatives"** in a dedicated closed-class lexicon
  (labeled `ARGH` in the source's own implementation, spanning alphabetically from `agyő` to `zsupsz`,
  neither individually enumerated nor glossed in this page range). **Flag for `language_corpus/Hungarian/`
  collection work:** a formal linguistic source independently confirms that Hungarian treats curses/
  exclamations/performatives as a distinct, sizeable (214-item) closed lexical class worth its own
  category — this is exactly the kind of `taboo`/`slang`-tier material this project's corpus phase should
  prioritize collecting, though this source itself does not list the actual 214 items. pp. 126–128 (PDF)
- **Numeral morphology follows a strict three-digit recursive pattern** (hundreds-tens-units, e.g. `hat` +
  `száz` + `kilenc` + `ven` + `hét` = 697, literally "six-hundred-nine-ty-seven"), implemented as a looping
  chain of sublexicons that also generates ordinals (`második` "second" is lexically irregular; all higher
  round-number ordinals are regular, `kettedik` not `*negyvenmásodik` for "forty-second") and fractions
  (`egyed` "-th/oneth," `harmad` "third," etc., productively suffixable up to arbitrarily large denominators,
  e.g. `ezernégyszáznegyvenegyed` "1/1441"). This is new information beyond what `established/001-003`
  captured about numerals, and confirms numerals are a fully regular, rule-governed (not
  memorized-list) subsystem in Hungarian, aside from a small set of irregular low numbers (`kettő`/`két`
  "two" is treated as lexically special throughout, feeding a genuinely separate sublexicon branch from
  the regular pattern). pp. 120–124 (PDF)

### 4.4 Conclusion — the paper's own stated theoretical upshot (paraphrased, not the theory itself)

Kornai's closing self-summary states two "twin principles" driving the whole analysis: **parsimony**
(using a minimal, uniform set of primitive descriptive devices across phonology and morphosyntax
alike) and **uniformity** (rules and lexical entries are stored and applied by the same general mechanism,
following Lexical Phonology's idea that lexical entries are themselves a kind of maximally-specific
"identity rule"). The practically useful takeaway for this project, independent of the specific generative
framework: the paper's own final assessment is that Hungarian is genuinely a *mixed* system — "roughly
halfway between agglutinating and inflecting" for its verbal paradigm specifically (§4.1.1 above), while
its nominal possessive paradigm is comparatively far more cleanly agglutinative (§4.2.4 above), and its
case system, while formally uniform in a single 17-case table, contains at least one demonstrably
peripheral/less-fully-grammaticalized member (`-ként`, §4.2.1). **This should directly inform the
language's "Morphological Typology" note in `00_Extraction_Checklist.md`: "agglutinative" is not a
uniform label across all of Hungarian's subsystems — it holds most cleanly for possessive/case
nominal morphology, and least cleanly for verbal person/tense/definiteness marking**, which this
academic source's own quantitative analysis (12 theoretical-minimum suffixes vs. 17+9 actually
needed) treats as a genuinely intermediate, partially-fusional system rather than a textbook-clean
agglutinative one. pp. 146–148 (PDF)

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of the source's own formal
diagrams, rule tableaux, or extended argumentative prose. Worked paradigm tables and closed-class
inventories above are re-summarized/re-tabulated in this project's own words and format, not copied
verbatim from the source's typesetting. See `00_Reference_Extraction_Spec.md`.
