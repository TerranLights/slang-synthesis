# Norwegian — Established Grammar/Phonology: The Phonology of Norwegian (full-book survey)

**Source:** Gjert Kristoffersen, *The Phonology of Norwegian* (Oxford University Press, "The
Phonology of the World's Languages" series, first published 2000, paperback 2007). Full-book
survey covering Chapters 1-12 (pp. 1-347; References pp. 348-360 and Index pp. 361-383 not
extracted). Source file: `13 The Phonology of Norwegian.pdf`.

**Coverage note:** this is a dense, 383-page academic generative-phonology monograph (written
within the Lexical Phonology framework, with substantial Autosegmental/Metrical-Theory and
Optimality-Theory-adjacent formal apparatus — feature-geometry trees, OT-style rule derivations,
F0/formant acoustic measurements, extensive citation of the prior Norwegian-phonology literature).
Per the coverage rule's "comprehensive but not exhaustive" + paraphrase-don't-reproduce instruction,
this file extracts and paraphrases the **descriptive phonological facts** the author establishes
(phoneme inventory, phonotactic/syllable structure, stress assignment, the tonal-accent system,
orthography-to-sound correspondence, explicit dialectal/sociolinguistic variation) chapter by
chapter, while deliberately not reproducing the book's own formal derivational machinery (feature
trees, rule formalisms, acoustic-measurement tables/graphs) — those serve the author's theoretical
argument, not this project's need for the underlying descriptive system. Every grammar point below
is paraphrased in this extractor's own words, with short illustrative IPA/orthographic examples
only, never the book's own explanatory prose reproduced at length. Page citations refer to the
book's own printed pagination (not PDF page numbers).

**Text-layer note:** this PDF has a genuine, clean text layer (confirmed via `pdftotext -layout`,
cross-checked against directly-rendered title/TOC pages) — no vision-reading was required for any
of the content below, so the vision-reading marginalia guard does not apply to this file. (Isolated
ligature/font artifacts, e.g. "Kristofffersen" for "Kristoffersen" and a handful of dropped IPA
glyphs that render as blank space in the raw text extraction, were cross-checked against context
and are noted inline only where an entry's own reading is genuinely uncertain.)

**First-ever Norwegian extraction for this project** — this file is Wave 1's phonology/sociolinguistics
anchor; `001_norwegian_verbs_and_essentials_of_grammar.md` and `002_practical_norwegian_grammar.md`
cover morphosyntax from two other Wave 1 sources in parallel.

---

## Vocabulary

*(A phonology monograph is not a word-list source — its "vocabulary" is illustrative example words
cited to demonstrate a phonological point, not a pedagogical core-vocabulary set. Rows below are
exactly the words the source itself uses as evidence, selected to cover its major phonological
contrasts and its few explicitly flagged colloquial/register items.)*

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| tak | 'roof' | noun | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | /tɑk/ → [³tɑk]; monovocalic root example (p.42); single postvocalic consonant after long vowel |
| takk | 'thank(s)' | noun/interjection | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Minimal pair with *tak*: doubled consonant letter signals the preceding stressed vowel is short, [³tɑk] vs. long [³tɑːk] in *tak* (orthographic principle, p.342) |
| kake | 'cake' | noun | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | /kake/ → [²kɑ.kə]; bivocalic root (p.42); disyllabic, ends in unstressed -e, which per the orthography chapter (p.343) usually signals accent 2 |
| Lise / lyse / luse / lose / lese / løse / låse / lase | woman's name / 'to light' / 'to delouse' / 'to steer' / 'to read' / 'to solve' / 'to lock' / 'rag' | mixed (name/verb/noun) | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Minimal-pair set establishing all 9 long stressed vowel phonemes /i y ʉ u e ø o (æ) ɑ/ (p.13) |
| sin / synd / sunn / ond / send / sønn / sånn / sand | poss. pron. / 'sin' / 'healthy' / 'wicked' / 'send' (imp.) / 'son' / 'such' / 'sand' | mixed | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Parallel minimal-pair set for the corresponding short vowel phonemes (p.13); note /sun/ is systematically missing/near-impossible, a gap the author flags explicitly |
| møl | (no good English equivalent — "a noun used in informal speech to characterize things or states of affairs that the speaker strongly dislikes") | noun | **colloquial** | — | contemporary (source published 2000) | Eastern/Northern Norwegian dialects | regional | grammar_reference | n/a | n/a | **Flagged explicitly as informal/colloquial by the source itself** (p.24, fn.25). One of the few lexical items where only the retroflex flap [ɽ] is possible, with *no* alternation to [r] — contrasts minimally with *mør* 'tender' [møɾ]. The author notes that in the upper-class Oslo sociolect where the flap is sociolinguistically banned, this word is "simply not available" to those speakers |
| kjei | 'girl' (rare) | noun | **colloquial** | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | **Marked "(coll.)" directly by the source** (p.347, fn.11) — a rare colloquial word, also spellable *kei*; cited as the sole exception to the rule that the digraph spelling *j* never precedes the diphthong *ei* |
| flott | 'good' / 'fine' / 'smart' | adjective | colloquial | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Cited (p.345) opposite *flått* 'tick' (zool.) as a homophone pair ([³flɔt]) distinguished only in writing — the gloss "good" given by the source itself suggests informal/evaluative use rather than a neutral descriptive sense |
| bord | 'table' | noun | core | — | contemporary (source published 2000) | Eastern Norwegian (retroflex-flap dialects) | regional | grammar_reference | n/a | n/a | [³buɾ] or [³buː] — alternates between tap [ɾ] and the vocalized/flap outcome depending on speaker/sociolect (p.24); contrasts with homograph *bord* 'border (on a garment)' [bɔrd] |
| hvitvin | 'white wine' | noun (compound) | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Compound of *hvit* 'white' + *vin* 'wine'; illustrates the Compound Stress Rule — primary stress stays on the first member, the second member's stress is demoted to secondary (p.184) |
| sakspapir | 'document pertaining to a specific subject' | noun (compound) | technical | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Compound of *sak*+*s* (linking -s) + *papir* 'paper'; same Compound Stress Rule pattern as *hvitvin*, illustrating a linking consonant inserted between compound members (p.184) |
| leken (def. sg. of *lek* 'play') / leken ('playful', adj.) | 'the play' / 'playful' | noun / adjective | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Minimal pair for tonal accent conditioned purely by morphological category: [³leːkn̩] (accent 1, def. sg. of the noun) vs. [²leːkn̩] (accent 2, the derived adjective) — identical segments, different accent (p.236) |
| målet / male | 'the goal' / 'to paint' | noun / verb | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | [³moːlə] (accent 1) vs. [²mɑːlə] (accent 2); the book's own worked F0-contour example pair for accent 1 vs. accent 2 (p.237) |
| ball / ball | 'dance' / 'round object' | noun | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Homographic/homophonous root pair cited to show that compound-accent behavior is **not** predictable from a stem's segmental shape alone — the two "ball"s pattern differently as compound first members (p.265) |
| kjære / tjære | 'dear' / 'tar' | adjective / noun | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Fully homophonous [²çæːɾə] despite distinct spelling (*kj-* vs. *tj-*) — both converge on the palatal fricative [ç]; spelling choice is purely etymological, not synchronically predictable (p.346) |
| sjø / ski / skje | 'sea' / 'ski' / 'spoon' | noun | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | All realize the retroflex/postalveolar sibilant [ʂ] despite three different spellings (*sj-, sk-, skj-*), reflecting historical palatalization of /s/ before /j/ or /ç/ (p.346) |
| dusj | 'shower' | noun | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | [³duʂ]; postvocalic *sj* spelling for [ʂ], cited alongside loanword spellings *sh*, *ch*, *sch*, *g*, *j* that all converge on the same sound (p.347) |
| og / òg | 'and' / 'too, also' | conjunction / adverb | core | — | contemporary (source published 2000) | Urban East Norwegian (Oslo area) | regional | grammar_reference | n/a | n/a | Near-homograph pair distinguished only by an optional grave accent on *òg*, which must be pronounced stressed/accented, unlike the normally-reduced, unstressed *og* (p.347) |

## Grammar points

### Two written norms: Bokmål and Nynorsk (pp. 2-6)

Norwegian has two official written standards, not one. **Bokmål** ("book language", formerly
*Riksmål*) evolved by incrementally reforming written Danish (the sole written/administrative
language in Norway through nearly 400 years of union with Denmark) to better reflect
middle/upper-class urban Norwegian pronunciation, via a series of spelling reforms (1907, 1917,
1938). **Nynorsk** ("new Norwegian", formerly *Landsmål*) was instead constructed from scratch in
the mid-1800s by Ivar Aasen from a comparative survey of conservative rural Western/Central-Southern
Norwegian dialects, deliberately favoring forms that preserved continuity with Old Norse over the
geographically most common variant (e.g. choosing the def. sg. feminine ending *-i* over the far
more common dialectal [ɑ] because it was historically closer to Old Norse *-in*). Both were granted
equal official status in 1885/1929. Roughly 85% of Norwegians use Bokmål, 15% Nynorsk; Nynorsk has
never taken hold in any town and remains rural, strongest in central/western Southern Norway. Each
norm further subdivides into a **radical** and a **conservative subnorm** (with many individual
forms assigned "main form" vs. "secondary form" status by the Norwegian Language Council,
*Norsk Språkråd*) — most actual users of either norm gravitate to a moderate middle ground rather
than the extremes. Worth flagging for this project: this is an explicit, source-documented
*register-of-formality-within-a-standard* system (radical/conservative subnorms), independent of
the separate colloquial/dialectal registers discussed below.

### No officially recognized spoken norm; Urban East Norwegian (UEN) (pp. 6-10)

Unlike most European languages, Norwegian has **no official spoken standard** — Norsk Språkråd's
explicit policy is that every dialect-rooted pronunciation is equally legitimate, and even major
dictionaries give no pronunciation guidance at all. In practice, however, an *unofficial* spoken
standard exists: **Standard Østnorsk** ("Standard East Norwegian"), associated with educated,
middle-class speech of the Oslo region, used in theatre, broadcasting, and as the variety most
commonly taught to foreigners. Because this variety cannot be precisely delimited from the wider
urban dialect continuum around it, the book instead describes the broader cluster it calls **UEN
(Urban East Norwegian)** — the variety this entire monograph documents. UEN is itself historically a
blend of two formerly distinct sociolects: **Dano-Norwegian (DN)**, the 19th-century speech of the
educated classes (closer to Danish — two-gender noun system, no feminine/masculine distinction,
monophthongs where dialects had diphthongs, avoidance of the retroflex flap), and the vernacular
East Norwegian dialects of the lower urban classes (three-gender system, retroflex flap, tonal
accents). Modern UEN speakers mix features from both, with the balance shifting by register, social
background, and speech style — i.e. the same speaker code-switches along this axis depending on
formality.

### Dialect groups and the geography of tonal accent (pp. 234-236)

Norwegian dialects split broadly into **East Norwegian** and **West Norwegian** groups. This
correlates strongly with how the tonal-accent system (below) is phonetically realized: East
Norwegian dialects (including UEN) are "**low-tone**" dialects (accent 1 = low tone on the stressed
syllable), while most West Norwegian dialects, including the town of Bergen itself, are
"**high-tone**" dialects (accent 1 = high tone on the stressed syllable) — the two patterns are
phonological mirror images of each other. A minority of areas **lack the tonal-accent contrast
altogether**: the area around Bergen's rural hinterland, the Brønnøy area north of Trondheim, and
most of the two northernmost counties (Troms and Finnmark) — the latter plausibly due to substrate
influence from the Finno-Ugric Sami language. The same tonal-accent phenomenon is found in most of
Swedish (also absent in Finland Swedish and parts of northern Sweden) and is historically related to
the Danish **stød** (a glottal-constriction feature most Danish dialects have instead of true tonal
accent). Icelandic and Faroese have neither feature. This is exactly the kind of explicit
dialectal/regional annotation this project's coverage rule prioritizes — Norwegian's prosodic system
is areally Scandinavian, not a UEN-only quirk, and any conlang slang-synthesis work drawing on
Norwegian prosody should know this is a shared North Germanic (minus Icelandic/Faroese) feature.

### Vowel inventory (pp. 13-20)

UEN has 9 contrastive long and 9 contrastive short stressed-syllable vowel phonemes: long
**i, y, ʉ, u, e, ø, o, (æ), ɑ**; short **i, y, ʉ, u, ɛ, œ, ɔ, (æ), ɑ**. Long and short pairs are not
simply quantity variants of one quality — e.g. long *e* [eː] and short *e* [ɛ] differ in quality as
well as length, and the author argues this difference reduces fully to length/environment rather
than an independent tenseness feature. Two points are typologically notable: (1) **[æ] is a marginal
phoneme**, patterning mostly as a conditioned allophone of /e/ before /r/ and /l/ (*lære* 'to teach',
*tverr* 'cross' adj.) and in the diphthongs /ej/, /ew/ (*vei* 'road', *sau* 'sheep'), rather than a
fully independent phoneme; (2) Norwegian (and Swedish) has a **fourth high vowel**, the central
rounded [ʉ] often called "Swedish u" — UEN's realization is phonetically distinct from the Swedish
cognate (monophthongal vs. diphthongized/more fronted in Standard Spoken Swedish) despite sharing
the same IPA symbol in most sources. Diphthongs are analyzed as short vowel + glide (/j/ or /w/),
not as a separate vowel class.

### Consonant inventory and the retroflex series (pp. 21-26)

UEN's consonant inventory: stops /p b t d ʈ ɖ k g/, nasals /m n ɳ ŋ/, fricatives /f s ʂ ç h/,
liquids /ɾ l ɽ ɭ/, approximants /ʋ w j/. Two typologically salient features: (1) **laryngeal
contrast is primarily aspiration, not voicing**, word-initially and at stressed-syllable onsets
(*bil* 'car' [bil] vs. *pil* 'arrow' [pʰil]) — the contrast neutralizes to voiceless unaspirated
after /s/, so *hans biller* 'his beetles' and *han spiller* 'he plays' are homophonous; (2) a full
**retroflex series** /ʈ ɖ ɳ ʂ ɽ ɭ/ exists alongside the plain coronals, historically derived from
/r/ + coronal-consonant sequences — this is the single most analyzed topic in the Norwegian
phonological literature besides tonal accent, per the author's own literature review (p.10-11). The
**retroflex flap [ɽ]** specifically is sociolinguistically marked: it's found in Eastern/Northern
dialects (and some Swedish dialects), alternates lexically with [ɾ] (from historical /rð/) or with
[l] (from historical /l/) in most words that carry it, but is categorically absent from some
upper-class Oslo speech for sociolinguistic reasons — meaning a handful of words (like the flagged
colloquial *møl* above) that require it are simply unavailable to speakers of that sociolect. A live
sound change is also noted: the palatal fricative /ç/ (*kj*) and the postalveolar/retroflex sibilant
/ʂ/ (*sj/skj*) are **merging into a single sound** among younger speakers in Bergen, Stavanger, and
Oslo — an explicitly flagged ongoing change, not a static system.

### Phonotactics: root types (pp. 41-43)

The lexicon's roots are classified into three structural types useful for understanding Norwegian
word shape: **monovocalic roots** (one vowel; monosyllabic or — when ending in obstruent/sonorant +
syllabic sonorant — surface-disyllabic, e.g. *tak* 'roof', *sykkel* 'bicycle'), **bivocalic roots**
(two vowels, typically CVCV(C) shape, e.g. *kake* 'cake', *bakke* 'hillside'), and **longer roots**
(three+ syllables, exclusively loanwords, e.g. *elefant* 'elephant', *apokalypse* 'apocalypse') whose
consonant clusters are drawn from the same inventory established by the first two types — i.e.
loanword phonotactics don't introduce genuinely new cluster types, just longer strings of the same
building blocks.

### Syllable weight and the vowel-length/gemination alternation (pp. 116-118)

Norwegian stress is **weight-sensitive**: a stressed syllable must be bimoraic (heavy) — this is
treated as an exceptionless surface generalization (apart from a few archaic "level-stress dialects"
that preserve an Old Norse-type system allowing light stressed syllables). This single constraint is
the mechanism behind a very visible Norwegian/orthographic pattern: a stressed syllable achieves its
required second mora **either** via vowel length ([haːt]) **or** via gemination of the following
consonant ([hatt]) — which strategy a given root uses is not predictable and must be lexically
specified, but the surface result is that **double consonant in writing always signals a short
preceding stressed vowel**, and (with some lexical exceptions) single consonant signals a long one.
This is the practical orthographic rule most Norwegian learners are taught (*tak* 'roof' [tɑːk] vs.
*takk* 'thanks' [tɑk]).

### Main stress assignment: native words vs. loanwords vs. names (pp. 148-150)

Three distinct stress patterns coexist for simplex (non-compound) words: (1) **Native simplex
words** take stress on the initial (root) syllable, unconditionally — *sykkel* 'bicycle', *kake*
'cake'. (2) **Personal names** mostly also take initial stress when disyllabic, but **shift to
penultimate stress when trisyllabic** (*Andréas*, *Kristóffer*, *Elíse*) — a distinct pattern from
ordinary native words, conditioned by the fact that names lack an identifiable "root syllable" with
semantic weight. (3) **Loanwords** are the most complex case: stress falls somewhere within a
**three-syllable window at the right edge** of the word (the same "window" pattern found in most
other Germanic languages), with the exact position governed by syllable weight rather than simple
syllable-counting from an edge — i.e. loanword stress is phonologically rule-governed, not
arbitrary/memorized, but the rule is sensitive to weight, not just position.

### Compound stress (pp. 181-184)

In a compound of two independently-stressable members, the **first member keeps primary stress**
and the **second member's stress is demoted to secondary** (tonal accent is lost on the demoted
member, but vowel length/consonant gemination — the segmental correlates of its original stress —
are preserved, serving as a diagnostic that a "secondary stress" position really is an underlying
stress position). This is the **Compound Stress Rule (CSR)**: a strict left-headed pattern, e.g.
*hvítvìn* 'white wine' (< *hvit* 'white' + *vin* 'wine') and *sákspapìr* 'document' (< *sak* 'case' +
linking *-s-* + *papir* 'paper'), where ´ marks primary and ` marks secondary stress.

### Tonal accents: accent 1 vs. accent 2 (pp. 233-273)

**The single most distinctive feature of Norwegian (and Swedish) phonology, and the one with the
deepest literature.** Most Norwegian dialects (with the geographic exceptions noted above)
contrastively use pitch on primary-stressed syllables, distinguishing two melodies conventionally
called **accent 1** and **accent 2**. Because accent 2 requires a disyllabic-or-larger domain
following the stressed syllable, the contrast is only possible in words of two or more syllables —
true monosyllables are predictably accent 1 (with a rare dialectal exception, "circumflex accent," in
parts of Trøndelag/North Norway). In UEN (East Norwegian, "low-tone"), accent 1 is realized as a
*low* tone on the stressed syllable followed by a *high* tone on the following syllable (melody LH);
accent 2 adds an *extra* initial high tone before that same LH sequence (melody HLH, i.e. essentially
"accent 1 plus a preceding H"). West Norwegian "high-tone" dialects like Bergen realize the *mirror
image* (HL for accent 1, LHL for accent 2). **Historical origin:** the contrast descends from a
predictable Old Norse monosyllabic-vs-disyllabic tonal pattern; it became contrastive once originally
monosyllabic words became surface-disyllabic (via epenthesis, e.g. Old Norse *vápn* > modern *våpen*
'weapon') while *keeping* the old monosyllabic melody (now accent 1), creating a contrast against
"genuinely" disyllabic words (now accent 2) — and a second, much larger source of accent-1 disyllables
came from Old Norse's suffixed definite article developing out of an originally syntactically
independent clitic. **Distribution:** in underlying (non-compound) forms accent is partly predictable
by morphological category — e.g. essentially all adjectives ending in a syllabic /n/ take accent 2
(100% in the author's own 459-word database), while accent 2 is comparatively rare in nouns (~10%)
of the same structural shape — and partly must be lexically marked. **In compounds**, a polysyllabic
first member transmits its own independent accent; a monosyllabic first member's accent is
lexically fixed per-root (82.5% consistency in the author's 617-root database) and is **not
predictable from the root's segmental shape alone** — the homographic pair *ball* 'dance' vs. *ball*
'round object' pattern differently as compound stems, which is the clearest possible evidence that
accent-inducing is a genuinely lexical/morphological property, not a phonological default. **For
morphology**, individual suffixes are independently classified as accent-2-inducing, accent-neutral,
or (rarely) accent-1-inducing, cross-cut by whether that influence is "dominant" (overrides the
stem) or "recessive" (yields to the stem) — i.e. Norwegian's tonal-accent system interacts with
derivational/inflectional morphology in much the same layered way its segmental phonology does.

### Orthography-to-phonology correspondence (pp. 340-347)

The Norwegian alphabet has 29 letters (9 vowels: *a e i o u y æ ø å*; 20 consonants), identical in
Bokmål and Nynorsk; *c q w x z* are "foreign" letters confined to loanwords. Several systematic,
non-obvious correspondences are worth flagging for any conlang-spelling-system design: (1) the
**double-consonant-signals-short-vowel** rule described above under syllable weight, with the
irregular exception that word-final *m* is never doubled regardless of preceding vowel length
(*grim* 'ugly' [ɾim] short vs. *lim* 'glue' [liːm] long — both spelled with single *m*, disambiguated
only in inflected forms); (2) **silent consonants** are common and lexically conditioned: *d* after a
stressed vowel is often silent (*blod* 'blood' [bluː]) but not always (*bad* 'bath' [bɑːd] obligatory
/d/) and sometimes optional (*blad* 'leaf', both [blɑː] and [blɑːd] heard); *g* is silent in the
*-ig/-lig* adjectival suffixes and in several lexicalized words (*fugl* 'bird', *også* 'too'); *h* is
always silent before another consonant (*hjelp* 'help' [jɛlp], *hval* 'whale' [ʋɑːl]); the neuter
definite-singular suffix *-et*'s *t* is silent (*huset* 'the house' [huːsə]) but the segmentally
identical past-tense/participle *-et* suffix's *t* is pronounced; (3) **digraph/etymological
spelling for merged sounds**: [ç] is spelled *kj* or *tj* depending purely on etymology (fully
homophonous *kjære* 'dear' / *tjære* 'tar'); [ʂ] is spelled *sj*, *sk(j)* (before front vowels), or —
in loanwords — *sh*, *ch*, *sch*, *g*, or *j*, again with no synchronic rule predicting which; (4)
**diacritics are rare**, used mainly in unassimilated loanword spellings and occasionally (grave/
acute/circumflex) to disambiguate an otherwise-homographic pair (*for* 'for'/'moved quickly' (pret.)
vs. *fòr*/*får* 'furrow' vs. *fôr* 'lining, fodder'; *og* 'and' vs. *òg* 'too'). **Tonal accent is
never marked in the orthography**, though word-final unstressed *-e* on a disyllabic word is a fairly
reliable (not absolute) cue for accent 2.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
