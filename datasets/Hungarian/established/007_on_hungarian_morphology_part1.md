# Hungarian — Established Grammar/Vocabulary: On Hungarian Morphology, Part 1 (Ch. 0–3)

**Source:** András Kornai, *On Hungarian Morphology* (doctoral dissertation, 1986; Version 3.0 pdf,
2007), Preface + Ch. 1 "Introduction," Ch. 2 "Phonology," Ch. 3 "Words and Paradigms." PDF pages
1–81 (printed pages 1–80). This is an academic autosegmental-phonology dissertation, not a teaching
grammar — its value for this project is theoretical/analytical (the paper's own generalizations about
Hungarian's morphological system), not a large vocabulary sample.

**Chunk boundary note.** The assigned range was PDF pages 1–80; the actual chapter boundary falls
one page later, at PDF page 81/printed page 80 (the last line of §3.2, "...the category system, and
in particular the minor categories might vary from one language to the next"). Chapter 4 ("Inflectional
morphology": conjugation, declension, the two-level implementation) begins cleanly on PDF page 82/
printed page 81 and is left to the sibling chunk (pages 82–158) rather than split mid-chapter. Printed
page numbers run one behind PDF page numbers throughout this file (PDF page = printed page + 1),
verified directly against the book's own footer page numbers, not assumed from `pdfinfo`.

**Coverage note.** This source has a clean, real text layer (`pdftotext -layout`); no vision-reading was
needed and no marginalia risk applies. Per the coverage rule, the chapter's **grammar-point content is
prioritized over a large flat vocabulary table** — this is specifically an academic paper on Hungarian
morphology, so its own worked examples and cross-analysis generalizations (vowel-harmony stem
classes, the "lowering stem" diagnostic, the definition of lexical category via inflectional paradigm)
are the highest-value content, more so than cataloguing every example word. Extensive formal
apparatus (feature geometry trees, autosegmental tier diagrams, the two competing three-feature vs.
four-feature analyses, most literature-comparison passages) is paraphrased/summarized rather than
reproduced — this is both a copyright-discipline requirement and a practical one, since these
diagrams don't survive plain-text extraction anyway. Repeated worked derivations that illustrate the
same point as an already-captured one are skipped.

**Register/dialect annotation (explicit in source — must-capture per coverage rule).** The source
consistently distinguishes **ECH** ("Educated Colloquial Hungarian") from **SLH** ("Standard Literary
Hungarian") as two named registers, and separately flags **dialectal** forms (marked as such, often
contrasted directly against the ECH equivalent) and forms marked **%** (marginal/regionally-flavored
acceptability, e.g. "decidedly *vidéki* 'rural' flavor for Budapest speakers"). These annotations are
captured in the vocabulary table's Notes column and in the morpheme breakdown below (dialectal
consonant-epenthesis forms).

**Morphological typology note.** Hungarian is agglutinative (see `../00_Extraction_Checklist.md`).
This source's central technical contribution is showing that Hungarian **vowel harmony is not a
simple binary front/back phenomenon** — it has binary, ternary, *and* quaternary alternation classes
that are governed by the same suffix, and that a stem's true harmonic class is often only revealed once
a *second* suffix is stacked on a first (see "Lowering stems" grammar point below and the Morpheme
Breakdown section). This is exactly the kind of suffix-stacking-reveals-hidden-structure pattern the
project's Word-Concept guide describes for agglutinative languages, so it's recorded here in unusual
depth.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| apa / epe | 'father' / 'bile' | noun | core | — | contemporary (source published 2007, based on 1986 thesis) | — | — | grammar_reference | n/a | n/a | source's own minimal-pair argument that Hungarian a/e differ only in the backness autosegment, both realized as archiphoneme ApA. p. 9 |
| vért / vért | 'blood-ACC' / 'armor' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | minimal pair cited (Tálos, p.c.) as evidence against a marginal phoneme [a]/[e]. p. 15 |
| arra / ara | 'that way' / 'bride' | adverb/noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | minimal pair (Nádasdy, p.c.) suggested as evidence *for* a marginal short [a]/[e]; source retains the traditional 14-vowel system regardless. p. 15 |
| kor / kór | 'age' / 'sickness' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | minimal pair establishing vowel length as distinctive. p. 29 |
| tél / telet | 'winter' / 'winter-ACC' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Stem Shortening example: long stem vowel shortens before ACC/DAT (not SUE). p. 29 |
| nyár / nyarat | 'summer' / 'summer-ACC' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Stem Shortening example. p. 29 |
| tűz / tüzet | 'fire' / 'fire-ACC' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Stem Shortening example. p. 29 |
| víz / vizet | 'water' / 'water-ACC' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Stem Shortening example. p. 29 |
| nyúl / nyulat | 'rabbit' / 'rabbit-ACC' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Stem Shortening example. p. 29 |
| bab | 'bean' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class II (regular back-vowel) paradigm citation form; see Morpheme Breakdown for full paradigm. pp. 30, 35 |
| hit | 'belief' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class III (regular neutral-vowel) paradigm citation form. pp. 30–31, 35 |
| tök | 'pumpkin' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class V (regular front-vowel) paradigm citation form; also the source's running example of a "lowering" possessive form (tököm/tökömet vs. *tökömöt). pp. 30–31, 39, 60 |
| hölgy | 'lady' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class IV (exceptional front-vowel/lowering) paradigm citation form: hölgyek (PL), hölgyhöz (ALL, not *hölgyhez) — the source's central example distinguishing Class IV from Class III. pp. 35, 37 |
| ház | 'house' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class I (exceptional back-vowel/lowering) paradigm citation form: házak, házhoz, háznak, háztól, házunk. p. 35 |
| ló | 'horse' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class I stem with additional v-stem alternation: lovak (PL) vs. lóhoz, lónak (no v). p. 35 |
| híd | 'bridge' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | exceptional neutral-vowel (í) stem behaving as Class I: hidak, hídhoz, hídnak (not *hídnek) — classic "abstract vowel" example from the vowel-harmony literature. pp. 35, 43 |
| zsír | 'fat, grease' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | exceptional neutral-vowel (í) stem behaving as Class II: zsírok (not *zsírak) — contrasted directly with híd to show two distinct kinds of exceptional í. p. 43 |
| cél | 'goal' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | only e/é-vowel stem patterning like zsír (Class II): célok, not *célak. p. 43 |
| héj | 'crust, shell' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | exceptional é-stem behaving as Class I: héjak, héjhoz. p. 43 |
| rum | 'rum' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class II stem; source's second worked "lowering-only-under-suffixation" example: rumom, rumot, but rumomat (not *rumomot) — see Morpheme Breakdown. p. 38 |
| lyuk | 'hole' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class I stem cited as evidence that the +U feature of the stem vowel and the harmonic -U diacritic must be represented on separate tiers. pp. 33, 35, 44 |
| had | 'army' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class I citation form throughout the vowel-harmony discussion: hadak, hadhoz, hadnak, hadtól, hadunk. pp. 30, 35 |
| féij / érv | 'head' / 'argument' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | fej: Class III citation form (fejek, fejhez, fejnek); érv: Class III citation form (argument). p. 35 |
| bőr | 'skin' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class V citation form throughout: bőrök, bőrhöz, bőrnek, bőrtől, bőrünk. p. 35 |
| bűn | 'sin, crime' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class V citation form: bűnök, bűnhöz, bűnnek. p. 35 |
| füst | 'smoke' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class V citation form; also cited in 2.4 as a "hard counterexample" to the mirror-image syllable rule (füst has coda "st" without a corresponding onset "ts"). pp. 35, 51 |
| sült | 'roast' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class IV citation form: sültek, sülthöz (not *sülthez), *sültöt unacceptable. pp. 35, 43 |
| tőgy | 'udder' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Class IV citation form; accusative %tőgyöt flagged as marginal/regional ("vidéki" flavor for Budapest speakers, but perhaps acceptable in some dialects). pp. 35, 36 |
| szónok | 'orator' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | derived with -nok/-nök 'professional characterized by' from szó 'word' — cited as a binary-harmony suffix example, not itself the focus. p. 30 |
| nagy láb / nagy lábú | 'big foot' / 'having big feet' | noun phrase / adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | worked example of the binary-harmony suffix -ú/-ű 'having'. p. 30 |
| öt / ötöd / ötödöt | 'five' / 'fifth' / 'fifth-ACC' | numeral / ordinal-fraction / — | core | — | contemporary | — | — | grammar_reference | n/a | n/a | source's own worked example of the quaternary fraction-forming suffix -ad/-ed/-od/-öd, contrasted with the possessive -ad/-ed/-od/-öd to show suffix identity ≠ harmonic-marking identity; see Morpheme Breakdown. p. 39 |
| hat / hatod / hatodot | 'six' / 'sixth' / 'sixth-ACC' | numeral / ordinal-fraction / — | core | — | contemporary | — | — | grammar_reference | n/a | n/a | fraction-suffix paradigm example. p. 39 |
| nyolc / nyolcad / nyolcadat | 'eight' / 'eighth' / 'eighth-ACC' | numeral / ordinal-fraction / — | core | — | contemporary | — | — | grammar_reference | n/a | n/a | fraction-suffix paradigm example; note nyolcadat (ACC) takes the a-alternant, unlike the fraction forms of öt/hat, because -ad/-ed/-od/-öd here is the 2SG possessive, not the fraction suffix (minimal pair with nyolcadot). p. 39 |
| házas / házasok / házasakat | 'married' / 'married-PL' / (lexicalized vs. re-derived plurals) | adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | derived with -as/-es/-os/-ös 'having'; source's central example that morphosyntactic "lowering" marking can be *lost* when a derived form is lexicalized (házasok, not *házasak) but *retained* when the same form is freshly re-derived compositionally (házasakat in "A kertes könyveket... a házasakat pedig balra" 'put those [about] houses to the left'). p. 44 |
| arany / Arany | 'gold' / (surname, poet Arany János) | noun / proper noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | parallel lexicalization-loses-marking example: aranyak 'gold pieces' (common noun, lexicalized, lost -U marking) vs. Aranyok 'books of/by Arany' (derived fresh from the proper name, keeps regular Class II marking). p. 46 |
| piros / pír | 'red (color term, derived)' / 'red, redness (primary root)' | adjective/noun / noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | pirosak 'red(adj)-PL' vs. pirosok 'red(n. i.e. "the color red")-PL' — same "derived form re-enters lexicon and loses exceptional marking" pattern as házas/arany. p. 46 |
| itt / ott | 'here' / 'there' | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | one item of the pervasive Hungarian proximal/distal pro-form system, cited as evidence for the featural classification of u/ü/o/ö vs. i. p. 32 |
| ez / az | 'this' / 'that' | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | proximal/distal pro-form pair. p. 32 |
| így / úgy | 'this way' / 'that way' | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | proximal/distal pro-form pair. p. 32 |
| ide / oda | 'to here' / 'to there' | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | proximal/distal pro-form pair, part of the 3-way to/at/from directional paradigm ide/itt/innen. pp. 77–78 |
| innen / onnan | 'from here' / 'from there' | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | pro-form pair. p. 77 |
| ilyen / olyan | 'like this' / 'like that' | adjective/pronoun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | pro-form pair. p. 77 |
| ekkora / akkora | 'this size' / 'that size' | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | pro-form pair. p. 77 |
| ennyi / annyi | 'this much' / 'that much' | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | pro-form pair. p. 77 |
| alá / alatt / alól | 'to under' / 'under' / 'from under' | postposition | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 3-way directional (to/at/from) postposition series. p. 78 |
| elé / előtt / elől | 'to the front of' / 'in front of' / 'from the front of' | postposition | core | — | contemporary | — | — | grammar_reference | n/a | n/a | 3-way directional postposition series. p. 78 |
| -ba/-ban/-ból, -ra/-on/-ról, -hoz/-nál/-tól | 'into/in/from in', 'onto/on/from on', 'to/at/from' | case suffix (locative series) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | the 3-way directional opposition realized as case-suffix series (illative/inessive/elative; sublative/superessive/delative; allative/adessive/ablative). p. 78 |
| hova / hol / honnan | 'where to' / 'where' / 'where from' | adverb (interrogative) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | interrogative member of the 3-way directional pro-form paradigm. p. 78 |
| ptrücsök | 'cricket' (dialectal) | noun | regional | — | contemporary (source published 2007; citing dialect data from B. Lőrinczy 1979) | Hungarian dialects (unspecified, per B. Lőrinczy's dialectological corpus) | regional | grammar_reference | n/a | n/a | dialectal consonant-epenthesis form; ECH equivalent explicitly given as `prücsök`. Source's own worked case for autosegmental desynchronization producing epenthetic /t/. p. 27 |
| tüsténtkedik | 'bustle' (dialectal) | verb | regional | — | contemporary | Hungarian dialects | regional | grammar_reference | n/a | n/a | dialectal epenthesis; ECH `tüsténkedik`. Shows the opposite desynchronization direction from ptrücsök (place node lags manner node). p. 28 |
| istmét | 'again' (dialectal) | adverb | regional | — | contemporary | Hungarian dialects | regional | grammar_reference | n/a | n/a | dialectal epenthesis; ECH `ismét`. Shows desynchronization at a lower-tier node (⟨anterior⟩, under place). p. 28 |
| partfűm | 'perfume' (dialectal) | noun | regional | — | contemporary | Hungarian dialects | regional | grammar_reference | n/a | n/a | dialectal epenthesis; ECH `parfűm`. One of a class not explained by the general desynchronization account — involves epenthesis before f/v specifically. p. 28 |
| péndz | 'money' (dialectal) | noun | regional | — | contemporary | Hungarian dialects | regional | grammar_reference | n/a | n/a | dialectal epenthesis; SLH `pénz`. Epenthetic /d/ from a different tier-lag (⟨continuant⟩ lags ⟨sonorant⟩). p. 28 |
| brindza | 'coach' (dialectal, single exception) | noun | regional | — | contemporary | Hungarian dialects | regional | grammar_reference | n/a | n/a | flagged as the sole apparent counterexample to the ban on word-initial/post-consonantal dz — the d here is argued to be epenthetic, like péndz. p. 28 |
| szónok, testvér, büszke | 'orator' / 'brother (of)' / 'proud (of)' | noun / predicate noun / predicate adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | testvér and büszke cited as the source's examples of predicate nominals that (exceptionally) govern a complement, motivating a separate lexical category from ordinary noun/adjective (which by definition never govern). p. 79 |
| egymás | 'each other' | pronoun (reciprocal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cited as a one-member lexical category: potentially +CASE +ANP, actually +D −POS — no other Hungarian word shares this exact inflectional profile. p. 79 |
| katonáék | 'the army (family/group sense)' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | the only Hungarian noun lexicalized with the "familiar plural" -ék feature (+FAM) as an inherent property rather than derived productively. p. 74 |
| sógor | 'brother-in-law' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | the source's running example noun for the full possessive+case paradigm tree (14-way opposition); see Morpheme Breakdown. p. 71 |

### Morpheme breakdown

> **rumomat** = rum ("rum," Class II stem, regularly takes the *o*-alternant) + om (1SG possessive,
> "my") + at (accusative). Source's own central worked example for why "lowering" behavior can be
> triggered by a *second* suffix even on a stem that shows no lowering with the plural/dative alone:
> `rum` → `rumom` "my rum," `rumot` "rum-ACC" (both regular Class II), but the possessed accusative
> is `rumomat`, never the expected regular `*rumomot`. The possessive suffix `-om` itself carries a
> "lowering" (+ML/floating −U) diacritic that only becomes visible once a further quaternary suffix
> (here accusative `-at/-et/-ot/-öt`) attaches *after* it — the possessive form is a lowering stem for
> the purposes of anything suffixed onto *it*, even though the possessive suffix itself attached
> regularly to a non-lowering stem. p. 38

> **tökömet** = tök ("pumpkin," Class V stem, regularly takes the *ö*-alternant) + öm (1SG
> possessive) + et (accusative) — parallel case to rumomat: `tököm` "my pumpkin" and `tököt`
> "pumpkin-ACC" are both regular, but the possessed accusative is `tökömet`, never `*tökömöt` or
> `*tökömhez`. Demonstrates the same "possessive suffix silently carries lowering marking for
> whatever comes after it" generalization for a front-vowel (Class V→ ML) stem. p. 38

> **ötödöt** = öt ("five") + öd (fraction-forming suffix "-th," here the *ternary* ö-alternant,
> matching the accusative's own alternant selection for this stem) + öt (accusative, itself
> quaternary but surfacing as ö here) — contrasted with **nyolcadat** = nyolc ("eight") + ad
> (fraction suffix) + at (accusative, a-alternant) *only when* -ad/-ed/-od/-öd is functioning as the
> 2SG possessive rather than the fraction suffix. The source's point: the *same* surface suffix shape
> -ad/-ed/-od/-öd does or doesn't carry the "lowering" diacritic depending on which morpheme it
> actually is (fraction-forming vs. 2SG possessive) — morphological identity, not surface phonology,
> determines whether a following quaternary suffix lowers. p. 39

> **házasakat** = ház ("house") + as (denominal "having" suffix, itself lowering-marked) + ak
> (plural, showing the *a*-alternant because -as retained its lowering diacritic in this freshly
> re-derived, non-lexicalized use) + at (accusative) — contrasted with the *lexicalized* adjective
> **házas** ("married") whose plural is the regular **házasok**, not *házasak*, because the lexicalized
> form has lost the -as suffix's lowering diacritic. Same surface morpheme sequence, two different
> outcomes, depending on whether the form is stored whole in the lexicon (loses marking) or generated
> compositionally each time (keeps marking). p. 44

> **sógorotokék** *(not itself in the source's text but constructible from its own paradigm tree, (4)
> on p. 71)* = sógor ("brother-in-law") + otok (2PL possessive, "your [pl.]") + ék (familiar-plural
> "and family/friends of") — illustrates the source's point that the possessive-affix system marks
> *both* the person/number of the possessor *and* (via the separate -ék slot) whether the possessed
> referent is being extended to "X and their group." The full paradigm in (4) cross-classifies:
> possessive-marked forms (om/od/a/unk/otok/uk, optionally + infixed -i- for plural possession, optionally
> + -ék for the familiar-plural sense, or -é/-éi for the anaphoric-possessive sense) against the full
> case-suffix column (nak, val, ért, vá, on, ra, ról, ban, ból, ba, nál, hoz, tól, ig, ként) — a
> genuinely large stacking space on one stem, all individually glossable. p. 71

## Grammar points

### 1. Theoretical framework: the generative lexicon and the Lexical Integrity Hypothesis

Kornai frames the whole study around the **Lexical Integrity Hypothesis (LIH)**: syntax cannot see or
alter the internal phonological/morphological content of a word, so every word-form syntax uses must
come from the lexicon. Combined with the **Principle of Brevity** (Chomsky & Halle 1968) — the
lexicon should list only what's unpredictable — this forces the lexicon to be treated as a *generative*
component (producing an in-principle-infinite set of well-formed words from a finite store of
morphemes + rules) rather than a static list. The dissertation's stated goal is to find the smallest
possible inventory of representations/operations (features, association, delinking, feature
insertion/deletion) that can generate the whole attested Hungarian word-stock — this is the
methodological throughline for everything that follows, including the vowel-harmony analysis. pp. 5–9

### 2. Vowel feature system: I / A / U (the "tridirectional" analysis)

Rather than adopting the standard SPE feature set for Hungarian's 14 vowels, Kornai derives a
three-feature system (**I**, **A**, **U**) purely from the *pattern of harmonic alternation itself*,
not from phonetic articulation. The logic: **binary** alternations (a/e, á/é, o/ö, ó/ő, u/ü, ú/ű)
show that back vowels {a,o,u} pattern against {e,i,ö,ü} — this defines feature **I**. **Quaternary**
alternations (the suffix set at/et/ot/öt "ACC," ak/ek/ok/ök "PL," am/em/om/öm "1SG POS," as/es/os/ös
"having") show {a,e,o,ö} patterning against {i,u,ü} — this defines feature **A**. **Ternary**
alternations (hoz/hez/höz "ALL," on/en/ön "SUE") plus the proximal/distal pro-form system (itt/ott,
ez/az, így/úgy, etc.) together justify a third feature **U** that separates {i,e} from {ö,ü} and
places {o,u} with the front-rounded pair rather than with i — via a "maximal contrast" argument (pro-form pairs should be maximally distinct in feature composition). A key finding: **á and é differ
from a and e only in length**, not in height or roundness — argued from two independent quantity
processes, **Low Vowel Lengthening** (apa→apát, epe→epét) and **Stem Shortening** (tél→telet,
nyár→nyarat, tűz→tüzet, víz→vizet, nyúl→nyulat), both of which are shown to be unified processes that
would break if a/á or e/é differed in any feature besides length. pp. 9–11, 29–33

**An alternative four-feature analysis is developed in the Appendix (2.6)** using standard SPE-style
features (back/high/low/round) plus underspecification, largely to allow archiphonemes to be
represented by simply leaving a feature blank rather than requiring floating/core-specified diacritics.
Kornai explicitly does not adjudicate between the two systems within this dissertation — he compares
their respective costs (the three-feature system needs both floating negative features *and*
core-specification as separate diacritic devices; the four-feature system needs an extra feature,
⟨low⟩, whose synchronic motivation is otherwise weak) and leaves the choice open pending further
evidence, particularly from the possessive paradigm (covered in the sibling chunk's Ch. 4). pp.
57–66

### 3. The five-way stem classification (Classes I–V) and "lowering" stems

This is the paper's central empirical contribution. Every non-vacillating Hungarian noun/adjective
stem falls into one of five classes, defined by *which alternant of the quaternary suffix* (plural
-ak/ek/ok/ök used as the diagnostic) it selects:

- **Class I** — exceptional back-vowel stems, take the *a*-alternant (e.g. `ház`→`házak`, `ló`→`lovak`,
  `híd`→`hidak`). Large (500+ monomorphemic stems) but historically closed — no new loanwords join it.
- **Class II** — regular back-vowel stems, take the *o*-alternant (e.g. `bab`→`babok`, `rum`→`rumok`).
  Open/productive — all new back-vowel loanwords default here.
- **Class III** — regular neutral-vowel stems, take the *e*-alternant in both ternary and quaternary
  suffixes (e.g. `hit`→`hitek`, `hithez` not `*hithöz`).
- **Class IV** — exceptional front-vowel stems, take the *e*-alternant quaternary but the *ö*-alternant
  ternary (e.g. `hölgy`→`hölgyek` but `hölgyhöz` not `*hölgyhez`). Small (~20 monomorphemic stems),
  closed.
- **Class V** — regular front-vowel stems, take the *ö*-alternant throughout (e.g. `tök`→`tökök`,
  `tökhöz`). Open/productive — all new front-vowel loanwords default here.

Class I and Class IV are argued to share a single underlying diacritic, which Kornai calls **ML**
("minor lowering," following but revising Vágó 1975/1980): it lowers and unrounds the following
quaternary vowel, deriving *a* from an underlying o-type archiphoneme (Class I) or *e* from an
underlying ö-type archiphoneme (Class IV). Kornai's key refinement over the prior literature (Vágó)
is showing that **ML/lowering is not a fixed property of a fixed 1,000-word list** — it's a
productive diacritic that many *productive* suffixes (1st/2nd singular possessive, past tense,
imperative, conditional markers, and the derivational suffix -as/-es/-os/-ös) themselves carry,
so that a perfectly regular Class II or Class V stem becomes a "lowering stem" the moment one of
these suffixes attaches, revealed only by what comes *after* that suffix (see `rumomat`, `tökömet`
in the Morpheme Breakdown). This means lowering behavior is "open" in exactly the sense that matters
for a productive agglutinative grammar, even though the set of *underived* lowering roots is closed.
pp. 33–46

### 4. Neutral vowels: transparency and vacillation

Neutral vowels (i, í, e, é) can show three distinct harmonic behaviors depending on which class they
appear in (unlike back/front vowels, which show only two), and their behavior in **polysyllabic
stems** is genuinely gradient rather than categorical. The generalization Kornai proposes (as a
"pretheoretical, probabilistic model," explicitly provisional): scan the stem's vowels **right to
left**; the first non-neutral vowel encountered decides front/back harmony; if *two or more* neutral
vowels precede a back vowel, the stem tends (not absolutely) to default to front suffixes anyway,
with roughly 80% probability per additional neutral vowel scanned. He explicitly cautions that
**existing generalizations in the literature about vacillating stems are less reliable than usually
assumed**, and that genuinely exceptional-but-non-vacillating stems (Classes I and IV) are more
methodologically tractable research objects than vacillation itself, because dictionary data can
settle class membership unambiguously while vacillation requires controlling for register, stress,
and speaker variation the field hasn't yet controlled for. pp. 61–65

### 5. Consonant feature geometry (brief)

Consonants are organized in a tree (root → laryngeal / supralaryngeal → manner / place), following
Clements 1985, rather than the flat "star" geometry used for vowels — because consonantal features
don't spread across a whole word the way vowel-harmony features do. One specific empirical argument
is reproduced: **dz is analyzed as a sequence of two phonemes** (not one phonemic unit), based on its
distributional restrictions (never word-initial, never after a consonant) and on dialectal epenthesis
data (`péndz`, `bendzin`) that the source's autosegmental desynchronization mechanism otherwise
explains cleanly. **dzs**, by contrast, is granted full phonemic status. pp. 22–29

### 6. Syllable structure: the "mirror rule" mostly holds, with principled exceptions

The traditional claim that Hungarian onset clusters are the systematic mirror image of coda clusters
(if PQ is a possible onset, QP is a possible coda and vice versa) is tested against a large consonant
cluster inventory and found to hold to a first approximation, governed by a **sonority hierarchy**
(m > l/n > j > r, established empirically rather than assumed universally). Genuine, non-eliminable
counterexamples remain — `füst` "smoke," `szaft` "gravy," `recept` "prescription," `akt` "nude" all
have codas (`-st, -ft, -pt, -kt`) with no onset mirror — and Kornai treats these as real, not
artifacts of insufficiently curated data (contra earlier claims that excluding foreign/inflected
words would make the mirror rule exceptionless). pp. 47–52

### 7. Cliticization and the definite article as evidence for inflectional definiteness

A brief but consequential argument: since the definite article `a/az` is shown (citing Kornai 1985a)
to attach only to bare nouns or noun+adjective/numeral phrases, never to full NPs, it must be
**proclitic** rather than a syntactically independent word. Because Hungarian verbs also show
subject-object "definite" vs. "indefinite" conjugation agreement (previewed here, developed in Ch. 4
of the sibling chunk), this is used as evidence that **definiteness is itself an inflectional
category in Hungarian**, not just a property expressed by an independent article word. p. 53–54

### 8. What is a "word"? — operational definitions

Kornai works through five classical operational tests for wordhood (Bloomfield's minimal free forms,
Bloch's maximal stable forms, Matthews' maximal fixed-order/non-recursive domains, Postal's anaphoric
islands) and notes they don't logically have to coincide, but empirically do for the overwhelming
majority of cases in the languages that have been checked — this convergence is what gives "word" its
explanatory value at all, rather than being a theoretical primitive. p. 67

### 9. Lexical categories are defined by paradigm, not meaning

This is the chapter's central methodological claim and arguably the paper's second major contribution
alongside the vowel-harmony analysis: **two stems belong to the same lexical category if and only if
their paradigms (the full set of inflectional affix-combinations they can take) are identical** —
*not* by traditional "class-meaning" definitions (Bloomfield's classic critique of "noun = name of a
person, place, or thing" is quoted directly) and *not* by external syntactic distribution. Consequences
Kornai draws out explicitly:
- A purely isolating language (no inflectional affixes at all) would have every word fall into the
  same category under this definition — morphology-based categorization only does work in languages
  where words carry inflection, so **"the complexity of the category system is directly proportional
  to the average number of morphemes per word."**
- Applied to Hungarian, this yields a working feature set — **PERS, LOC, D(efiniteness), TENSE, CASE,
  DEG(ree), GOVT** — that cross-classifies the major categories (table (8), p. 79): Adverbial has none
  of these marked; Noun is [+PERS +D +CASE]; Adjective is [+PERS +CASE +DEG]; Verb is [+PERS +D
  +TENSE +GOVT]; Postposition is [+PERS +LOC +GOVT]; Infinitive is [+PERS +GOVT]; Participle is
  [+TENSE +GOVT].
- **"Predicate nominals" like `testvér` ('brother of') or `büszke` ('proud of') are deliberately
  excluded from the Noun/Adjective categories** as here defined, because true nouns/adjectives never
  govern a complement — words that look nominal/adjectival but do govern something get their own
  minor category that shares every feature but GOVT with the ordinary noun/adjective class. This
  formal move is offered as the explanation for why the traditional dictionary classification and this
  paradigm-based one still agree for >99% of the ~35,000 nouns checked against the Debrecen Thesaurus —
  the ~1% mismatch is attributed mostly to idiom-only words like `farkaskasza` ("wolf-scythe").
pp. 68–80

### 10. Morphosyntactic features are arranged in trees, not flat matrices — and this predicts defective paradigms

Kornai's second formal device: morphosyntactic features (e.g. the possessive/case system of a noun)
are organized as **trees**, with the constraint that **only marked ("+") values can dominate (have
daughters under) other features** — e.g. person/number of a possessor (ME/YOU/PL) is only meaningful
once you're already in the +POS branch. This isn't just notational: it makes a testable prediction
about **defective paradigms** — a noun lexicalized as inherently lacking some paradigmatic slot (e.g.
`bá` "old man," lexicalized as −POS, i.e. never takes a possessive suffix; `katonáék` "the army,"
lexicalized as +FAM) should correspond to exactly the "natural classes" the tree geometry permits, no
more and no fewer. Checked against Papp (1975)'s catalog of ~300 genuinely defective Hungarian nouns,
this prediction largely holds — every attested defect pattern (−POS, −POS/−PL, −POS/+PL, +POS/−PL,
+POS/+PL) corresponds to a class the tree structure allows, and gaps in the attested combinations
(no noun lexicalized with the anaphoric-possessive ANP feature; no true singularia tantum) are treated
as a genuine, non-accidental empirical finding rather than a data-collection artifact. pp. 70–75

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. Formal apparatus (autosegmental tier diagrams, feature-geometry trees,
rule derivations) is summarized in prose rather than reproduced, consistent with this discipline and
with the fact that such diagrams do not survive plain-text extraction reliably. See
`00_Reference_Extraction_Spec.md`.
