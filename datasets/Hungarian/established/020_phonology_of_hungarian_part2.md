# Hungarian — Established Grammar/Vocabulary: *The Phonology of Hungarian* (Siptár & Törkenczy),
Part III "Processes" — Chapters 6–9 (end of book)

**Source:** Péter Siptár and Miklós Törkenczy, *The Phonology of Hungarian* (Oxford University Press,
"The Phonology of the World's Languages" series, 2000/2007 printing), PDF pages 172–338 of 338
(printed pages ~157–296), covering all of Part III "Processes": Chapter 6 "Processes Involving Vowels"
(§6.1 Vowel Harmony, §6.2 Lengthening and Shortening Processes), Chapter 7 "Processes Involving
Consonants" (§7.1 Palatalization, §7.2 Sibilant Rules, §7.3 Voicing Assimilation and Devoicing, §7.4
Processes Involving Nasals and Liquids), Chapter 8 "Processes Conditioned by Syllable Structure" (§8.1
Vowel ~ Zero Alternations, §8.2 Alternations Involving Consonants), and Chapter 9 "Surface Processes"
(§9.1–9.5, fast-speech phenomena), through the end of the book's substantive content. A sibling
subagent covers PDF pages 1–170 (Parts I–II: introduction, segment inventories, syllable structure/
phonotactics) in a companion file; this file picks up exactly where that one's assigned range ends,
verified by direct inspection: PDF page 171 is a blank leaf ("This page intentionally left blank")
immediately followed by the Part III divider, and PDF page 172 opens cleanly on "6 / PROCESSES
INVOLVING VOWELS," a clean chapter boundary confirmed by direct page rendering, not arithmetic
estimation.

**Source-genre note.** Like `established/007`–`008` (Kornai's *On Hungarian Morphology*), this is a
formal generative-phonology monograph aimed at theoretical linguists, not a pedagogical grammar.
Per this dispatch's own instructions and following the Kornai precedent, this file prioritizes the book's
own phonological generalizations, rule interactions, and worked alternation patterns as grammar-point
prose over building a large flat vocabulary table. The vocabulary table below is deliberately thin and
consists almost entirely of paradigm/minimal-pair illustration words (e.g. `nyár`/`gyár`, `torony`/
`szurony`/`szörny`) that exist to demonstrate a phonological point, not free-standing lexical entries in
the pedagogical-grammar sense.

**Coverage note.** Every substantive phonological generalization, rule interaction, and alternation
pattern in Chapters 6–9 is captured below, in prose paraphrase. Deliberately **not** reproduced: the
book's own formal autosegmental feature-geometry diagrams, rule schemas, and skeletal-tier
derivations (dozens of numbered rule statements like "Link DOR," "v-delink," "C-spread," "Degemination
I/II/III") — these are the theoretical machinery used to *derive* the surface alternations, not
independently useful data for this project; the substantive empirical claims those formalisms encode
are paraphrased in prose instead, with representative example words kept. Also skipped as
non-extractable back matter: "Suggested Reading" (an annotated bibliography, PDF pp. ~317–320),
"References" (a reference list, PDF pp. ~321–336), and the "Index" (PDF pp. ~337–338) — none of this
is substantive content, confirmed by direct inspection.

**Vision-reading note:** not applicable — this PDF has a genuine text layer (`pdftotext -layout`
extracted cleanly, ~63,000 words across the assigned range); no vision-reading was needed. One
extraction gotcha worth flagging: `pdfinfo` on this file reports repeated "Dictionary key must be a
name object" syntax-error warnings (a malformed PDF object unrelated to the text layer) — these are
harmless noise and did not affect `pdftotext` output quality; they can be safely ignored on any future
pass over this same source file.

**Relationship to prior Hungarian coverage.** This source complements, and in places directly refines,
vowel-harmony and consonant-alternation content already captured from Rounds' pedagogical grammar
(`established/001`) and from Kornai's *On Hungarian Morphology* (`established/007`–`008`). Where this
source adds genuinely new analytical depth — not just a second worked example of an already-covered
pattern — that is flagged explicitly in the Grammar points below (see especially §8.1, which gives a
formal underlying-representation account of the vowel~zero alternations that Kornai's paper treated
more descriptively).

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ház | 'house' | noun | core | — | contemporary (source published 2000/2007) | — | — | grammar_reference | n/a | n/a | pure-DOR (back-harmonic) stem, the book's primary vowel-harmony paradigm example: ház-unk, ház-tól, ház-nak, ház-hoz. §6.1 |
| tűz | 'fire' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | pure-LAB (front-rounded) harmonic stem, paired with ház to illustrate Link Place vs. Link DOR. §6.1 |
| víz | 'water' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | pure-COR (front-unrounded/neutral) harmonic stem; also the FSVS (Final Stem Vowel Shortening) paradigm example víz/vizet (acc.). §6.1, §9.1 |
| piros | 'red' | adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | COR+DOR stem (e.g. telefon-class): illustrates a stem whose front vowel(s) are linked to COR while a floating DOR seeks the first back-harmonic vowel slot. §6.1 |
| telefon | 'telephone' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | multi-syllable COR+DOR stem; cited alongside `pirosító` 'rouge' to show DOR must be able to "skip" an intervening front vowel and land on a later one — evidence DOR is lexically unlinked/floating rather than prelinked. §6.1 |
| nüansz | 'nuance' | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | LAB+DOR "complex harmonic" loanword stem: both place features prelinked to prevent wrong internal associations (*nuansz) and prevent LAB leaking onto suffixes (*öregök-type errors). §6.1 |
| öreg | 'old' | adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | LAB+COR complex neutral stem, contrasted with nüansz's LAB+DOR to show COR (unlike DOR) does not spread onto an already-LAB vowel. §6.1 |
| szemölcs | 'wart' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | COR+LAB stem where COR (unlike in nüansz/öreg) is left unlinked so it can skip the labial vowel and reach suffix vowels. §6.1 |
| sofőr | 'driver' | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | DOR+LAB loanword stem; its front-rounded vowel is exceptionally specified as [COR, LAB] to block DOR from spreading onto it (blocked by the *[COR,DOR] constraint). §6.1 |
| papír | 'paper' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | DOR+COR "transparent" stem: DOR skips the coronal vowel entirely and only links to a following suffix vowel, if any. §6.1 |
| híd | 'bridge' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | DOR+COR "antiharmonic" stem: no placeless vowel inside the stem for DOR to attach to, so DOR links solely to the suffix vowel. §6.1 |
| kódex | 'codex' | noun | technical | — | contemporary | — | — | grammar_reference | n/a | n/a | DOR+COR "opaque" loanword stem: unlike papír/híd, both DOR and COR are linked within the stem itself, blocking further spreading. §6.1 |
| dzsungel | 'jungle' | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | genuinely vacillating stem with two coexisting underlying representations (papír-type and kódex-type), producing real speaker-to-speaker variation (dzsungelben ~ dzsungelban). §6.1, §9.1 |
| alma | 'apple' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Low Vowel Lengthening (LVL) paradigm example: short stem-final /a/ obligatorily lengthens to /á/ before any suffix (almát, not *almat). §6.2.1 |
| nyár | 'summer' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Stem Vowel Shortening (SVS) minimal-pair stem: nyár/nyarat (acc.) shortens; directly parallels the same nyár/gyár contrast already captured from Kornai (`established/008`) but here given a full autosegmental (empty-X-slot) account rather than a diacritic-marking one. §6.2.2 |
| gyár | 'factory' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | non-shortening SVS counterpart to nyár: gyár/gyárat (acc.), all skeletal slots underlyingly filled. §6.2.2 |
| látja | 'sees it' | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | lexical palatalization paradigm example (3sg def.): /t+j/ → [tyː], contrasted with postlexical palatalization which never fuses trigger and target. §7.1.1 |
| üt / üss | 'hit' / 'hit!' (imp.) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | short-vowel t-final verb; imperative üss shows full t-Assimilation to the obstruentized /j/, contrasted with hajts/önts (affrication) and ossz/fess (t-deletion). §7.2.1 |
| önt / önts | 'pour' / 'pour!' (imp.) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | sonorant+t-final verb; imperative önts shows the /j/ first obstruentized then affricated to [tʃ], the book's revised (non-t-palatalization) analysis of this whole class. §7.2.1 |
| oszt / ossz | 'divide' / 'divide!' (imp.) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | s-final verb; imperative ossz shows t-Deletion (stem-final /t/ simply deletes before /j/, which then assimilates to the preceding /s/). §7.2.1 |
| szívtől | 'from a/the heart' | noun+case | core | — | contemporary | — | — | grammar_reference | n/a | n/a | worked example of coda /v/ undergoing devoicing to [f] — the book's central evidence that /v/ is underlyingly unspecified for [son] (behaves as sonorant in onset, obstruent in coda). §7.3 |
| hatvan | 'sixty' | numeral | core | — | contemporary | — | — | grammar_reference | n/a | n/a | shows /v/ failing to trigger voicing on a preceding obstruent (*[hɔdvɔn]), part of the same onset/coda-asymmetry argument as szívtől. §7.3 |
| ember | 'man, person' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | worked example of regular Nasal Place Assimilation of the underspecified nasal /N/ to a following labial ([εmbεr]); also independently attested in `established/008`'s possessive paradigm. §7.4.1 |
| bokor | 'bush' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | the book's primary "epenthetic" stem-internal vowel~zero example: bokor (isolation) / bokor-ban (C-suffix) / bokr-ok (V-suffix); reanalyzed as underlyingly -CVdC (a defective, not absent, vowel), not a genuine CC-final stem. §8.1.1, §8.1.4.1–2 |
| torony | 'tower' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | the key member of the book's three-way minimal-triplet argument (torony 'epenthetic' ~ szurony 'stable-vowel' ~ szörny 'genuinely CC-final'), showing vowel~zero alternation is not phonotactically predictable from surface shape alone. §8.1.1, §8.1.4.1–2 |
| szurony | 'bayonet' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | non-alternating counterpart to torony (both surface as CVCVC in isolation, but szurony's final vowel is a genuine "full" vowel that never disappears: szurony-ok, not *szurny-ok). §8.1.1, §8.1.4.1–2 |
| szörny | 'monster' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | genuinely CC-final stem (no alternation at all: szörny-ek, szörny-et), the third member of the torony/szurony/szörny triplet. §8.1.1, §8.1.4.1–2 |
| csukl-ik | 'hiccup' (3sg pres. indef.) | verb (ik-verb) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | "defective" bound stem ending in a genuinely ill-formed coda cluster that is never broken up by epenthesis (*csukol-j is impossible) — the book's argument against treating all vowel~zero stems as underlyingly epenthetic. §8.1.1 |
| ház-ak | 'houses' | noun+plural | core | — | contemporary | — | — | grammar_reference | n/a | n/a | "lowering" stem: plural linking vowel surfaces low [ɔ], not mid [o], contrasted minimally with non-lowering gáz-ok. §8.1.3 |
| gáz-ok | 'gases' | noun+plural | core | — | contemporary | — | — | grammar_reference | n/a | n/a | non-lowering counterpart to ház-ak: plural linking vowel stays mid [o]. §8.1.3 |
| retek | 'radish' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | second core 'epenthetic'-stem example (retek/retek-ben/retk-ek), used throughout §8.1 alongside bokor and kölyök. §8.1.1–8.1.4 |
| csap-pal | 'with a tap' (instr.) | noun+case | core | — | contemporary | — | — | grammar_reference | n/a | n/a | alternating v-suffix example: -val assimilates fully to a single stem-final consonant, producing a geminate. §8.2.1 |
| domb-bal | 'with a hill' (instr.) | noun+case | core | — | contemporary | — | — | grammar_reference | n/a | n/a | alternating v-suffix after a cluster-final stem: no true geminate arises (the spreading rule's structural description isn't met), giving apparent "degemination" for free. §8.2.1 |
| hatvan | 'sixty' | numeral | core | — | contemporary | — | — | grammar_reference | n/a | n/a | non-alternating v-suffix -van (an analytic, not synthetic, suffix): retains /v/ even after a consonant-final stem, contrasted with alternating hattal 'with six'. §8.2.1 |
| cseh | 'Czech' | adjective/noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | the book's sole remaining consistent example of the (claimed to be moribund) h~zero alternation type: cseh / cseh-es [tʃεhεʃ] / cseh-től [tʃεtøːl] (h deletes preconsonantally/finally). §8.2.2 |
| doh | 'musty smell' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | the productive, open-class h~x alternation type argued to be the true synchronic pattern in Educated Colloquial Hungarian (ECH): doh / doh-os [dohoʃ] / doh-tól [doxtoːl]. §8.2.2 |
| méh | 'bee' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cited as a stem actively reclassifying from the old cseh-type to the productive doh-type in ECH speech ([meː] ~ [meːx]), offered as live sound-change-in-progress evidence. §8.2.2 |
| autó | 'car' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | monomorphemic vowel-hiatus example that resists Hiatus deletion (not a derived environment) and is instead optionally realized as a diphthong [ɔˑutoː] in casual speech. §9.1, §9.3 |
| balra | 'to the left' | adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | liquid-deletion-with-compensatory-lengthening example: /l/ deletes most readily of the three liquids, [bɔːrɔ]. §7.4.2, §9.2 |
| leány | 'girl' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | hiatus that is NOT filled ([lɛjaːɲ] impossible source form aside — surfaces without a glide), contrasted with hiány 'lack' [hijaːɲ] which obligatorily fills, illustrating that hiatus-filling is governed by vowel quality (high coronal /i, iː/ trigger it obligatorily) not simply by adjacency. §9.3 |
| áll | 'stand' / 'chin' | verb/noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | central worked example throughout §9.4's degemination discussion: word-final geminate that degeminates obligatorily before any following consonant (áll-t, áll-hat) but survives utterance-finally and intervocalically. §9.4 |
| lambda | 'lambda' (math.) | noun | technical | — | contemporary | — | — | grammar_reference | n/a | n/a | Fast Cluster Simplification (FCS) example: middle consonant of a CCC cluster optionally deletes in fast speech when conditions are met ([lɔmbdɔ] ~ [lɔmdɔ]). §9.5 |
| centrum | 'centre' | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | FCS-blocking counterexample: deletion is blocked because C3 (/r/) is a continuant, one of three formal conditions on the rule identified in this chapter. §9.5 |

## Grammar points

### 6.1 Vowel harmony reanalyzed with three independently spreading place features (COR/LAB/DOR)

The book's central contribution to vowel-harmony analysis (going beyond the more traditional
backness-only or "Element I" accounts cited in the literature) is that *all three* place features —
coronal (COR, roughly frontness), labial (LAB, rounding), and dorsal (DOR, roughly backness) — are
independently capable of linking to an unassociated vowel slot or spreading onto an adjacent one, not
just DOR/backness as in most earlier treatments. Two general mechanisms are proposed: **Link**
(a floating feature associates, unboundedly within a phonological word, to *any* number of
placeless V-slots it can reach) and **Spread** (an already-linked feature extends onto one *immediately
adjacent* V-slot only). A general constraint bans any vowel from simultaneously bearing both COR and
DOR (no vowel can be articulated with both the front and back of the tongue), and bans [+open1]
(low) combined with LAB (no low front rounded vowels in Hungarian) — together these two constraints,
plus a default rule assigning COR to any vowel left placeless after Link/Spread apply, derive the observed
harmonic behavior of every stem class without needing separate stipulated rules per class. **Refinement
of prior coverage:** this substantially deepens the vowel-harmony content already captured from Rounds
(`established/001`) by giving a mechanistic account of *why* certain stem-internal vowel sequences
(pure-DOR ház-type, pure-LAB tűz-type, pure-COR víz-type, and six further "complex"/"opaque"/
"antiharmonic"/"transparent" combination classes — see the Vocabulary table above for worked
examples of each) harmonize the way they do, rather than just tabulating the alternation patterns. pp.
157–170 (PDF)

### 6.2.1 Low Vowel Lengthening (LVL): morpheme-final short low vowels always lengthen before a suffix

Underlyingly short word-final /a/ or /e/ obligatorily lengthens to /á/ or /é/ whenever any suffix
(synthetic or analytic) attaches — alma → almát, epe → epés. This is formalized as insertion of an empty
timing slot after the vowel, onto which the vowel's own melody spreads (rather than as height/backness
change), and it applies as many times as its structural description is met within a single derivation (óra
→ órája → óráját). Crucially, LVL does **not** apply across a genuine compound or independent-word
boundary (balta⎥nyél 'hatchet handle' keeps its short a), which lets the book use LVL's behavior as
independent evidence for whether a given suffix (e.g. -kor 'at (the time of)', -képp 'as') starts a new
phonological-word domain or is transparent to processes from the stem's own domain. Two systematic
exception classes are flagged explicitly: the multiplicative suffix -szor/-szer/-ször and the productive
noun-forming suffix -ság/-ség both undergo ordinary vowel harmony but never trigger LVL, while
terminative -ig and causal-final -ért trigger LVL despite not harmonizing at all — the book states outright
that no principled account of this residual exception set exists in the literature. pp. 170–173 (PDF)

### 6.2.2 Stem Vowel Shortening (SVS): an autosegmental account of the nyár/gyár-type lexical split

Refining the same nyár/gyár lexical-idiosyncrasy pattern already captured from Kornai's paper
(`established/008` §4.2.3), this source gives a full formal representational account rather than treating it
as a diacritic. Both stem types are represented with four skeletal (timing) slots, but a shortening stem
like nyár has one slot left underlyingly empty, onto which the preceding vowel's melody spreads by
default — unless a deletion rule removes that empty slot first, yielding the short surface form (nyarat).
A non-shortening stem like gyár has all four slots filled from the start, so no deletion site exists and the
long vowel survives unsuffixed (gyárat, not *gyarat). The book further distinguishes Final Stem Vowel
Shortening (FSVS, stem-edge, triggered only by a closed, arbitrarily marked set of vowel-initial suffixes)
from Internal Stem Vowel Shortening (ISVS, can affect any syllable of a polysyllabic stem, e.g. szintézis
'synthesis' → szintetikus 'synthetic', and is only triggered by *derivational*, never inflectional, suffixes)
— and explicitly floats the possibility that ISVS may not be a live phonological process at all, but simply
an accident of related-but-non-derived items coexisting in the lexicon. pp. 173–176 (PDF)

### 7.1 Palatalization comes in two distinct types: obligatory lexical fusion vs. optional postlexical adjacency

Hungarian palatalizes dental consonants (/t d n l/) before a following palatal (/ty dy ny j/) in two
formally distinct ways. **Lexical palatalization** (látja [laːtyːɔ] 'sees it') fully fuses trigger and target into
a single long palatal segment and is obligatory. **Postlexical (surface) palatalization** (átjáró [aːtjaːroː]
~ [aːtyjaːroː] 'passage') never fuses the two segments (no coalescence), is optional/rate-dependent, and
can be triggered by any palatal stop/nasal, not just /j/. The book's own final analysis collapses both into a
single generalized "Palatalization" rule (obligatory in its lexical applications, optional postlexically) plus
a separate "Palatal j-Assimilation" rule that supplies the fusion step only within the lexical component.
/l/ is treated as a formal outlier: it does not palatalize before palatal stops/nasals the way /t d n/ do
(only before /j/ specifically, via its own dedicated "full assimilation" rule), which is offered as evidence
that /l/ must be represented as [+continuant] in the underlying feature system rather than grouped with
the true stops. pp. 177–198 (PDF)

### 7.2.1 The imperative of t-final verbs is reanalyzed as obstruentization of the imperative /j/, not palatalization of stem-final /t/

This is presented as a genuine departure from the classical generative treatment (Vago 1980a) of a
well-known three-way alternation: üt 'hit' → üss (short-vowel stems, full [ʃː]), önt 'pour' → önts
(sonorant+t stems, affricate [tʃ]), oszt 'divide' → ossz / fest 'paint' → fess (obstruent-final stems,
outright /t/-deletion). Rather than deriving these as three different fates of the stem-final /t/, the book
argues the imperative /j/ itself first obstruentizes into a voiceless palatal fricative, which then either
undergoes further affrication (giving the önts/hajts type), full assimilation to a preceding short-vowel
/t/ (giving the üss type), or simple deletion-then-reassimilation (giving the ossz/fess type). This
reanalysis is motivated by the independently attested class of "hidden-cluster" stems (tanít-type,
already noted from Kornai in `established/008` §4.1.6) that resist full assimilation the same way
sonorant+t stems do — the book treats this as convergent evidence for a shared underlying property
rather than coincidence, and explicitly notes a stigmatized colloquial extension ("suk-sükölés") where the
same rule wrongly generalizes into indicative forms (lássa 'he sees it' for standard látja) — an explicit,
source-marked register/prescriptive-stigma flag worth noting for future slang-corpus work on Hungarian
non-standard morphophonology. pp. 183–198 (PDF)

### 7.2.2–7.2.3 Postlexical sibilant/affrication rules form a speed-graded continuum, not a binary choice

A cluster of related postlexical rules (Strident Place Assimilation, Stop+Strident Place Assimilation,
Fricative Affrication, Stop+Affricate Place Assimilation) together predict that the *same* underlying
sequence can surface in multiple distinct ways depending on speech rate/formality, with intermediate
stages genuinely attested, not just endpoints. The book's central illustrative case, ötször 'five times'
(/t/+/s/), can surface as formal [ötsör] (no rule), moderately casual [öt-tsör] (partial affrication only), or
casual [ötsːör] (full coalescence into a long affricate) — and the analysis is explicitly designed so that
rule ordering among these need not be stipulated, since each rule's own optionality independently
predicts the full range of attested surface forms. A useful register-flagged generalization: word-internal
coalescence (nehézség → [neheːʃːeːg] rather than [-hess-]) is normally avoided in guarded/formal speech
but standard in colloquial speech, *except* in semantically opaque/lexicalized forms (egészség 'health')
where the coalesced form is obligatory even in the most formal register — a genuine phonology/lexical-
opacity interaction worth flagging for slang-corpus annotation (a fused pronunciation can itself signal
lexicalization/opacity, not just casualness). pp. 188–198 (PDF)

### 7.3 Voicing assimilation is directional (right-to-left) and privative, with /v/ as a structurally unspecified segment

Hungarian obstruent clusters agree in voicing with their rightmost member (a genuine, obligatory,
non-rate-dependent rule, unlike most other postlexical processes in this book). The analysis is built on a
*privative* [voice] feature (only voiced obstruents carry a laryngeal node at all; voiceless obstruents and
all sonorants simply lack one), which lets the book avoid abstract intermediate "Duke of York" derivations
that a binary [±voice] framework would otherwise require. The single most striking empirical fact
built into this section is the **Janus-faced behavior of /v/**: in onset position it patterns exactly like a
sonorant (does not trigger voicing on a preceding obstruent: hatvan 'sixty', not *[hɔdvɔn]), but in coda
position it patterns exactly like an obstruent (undergoes devoicing: szívtől 'from a heart' → [siːftøːl]).
The book's solution is to leave /v/ underlyingly unspecified for the feature [sonorant] altogether, with
late phonetic-implementation rules assigning it [+son] in onsets and [–son] in codas — a clean example
of a single segment straddling the sonorant/obstruent divide by structural position rather than lexical
idiosyncrasy. A related process, progressive devoicing of imperative /j/ in word-final consonant clusters
(lopj [lopç] 'steal!', dobj [dobΔ] 'throw!', with the specific voicing outcome dependent on what precedes),
is worked through in detail as a showcase of how obstruentization-without-added-voicing vs.
obstruentization-with-added-voicing must be distinguished rule by rule to fit the twelve logically possible
contexts. pp. 198–212 (PDF)

### 7.4 Nasal place assimilation and liquid deletion are largely optional, rate/register-graded processes

The underspecified nasal /N/ (posited as a genuinely placeless nasal archiphoneme, distinct from fully
specified /m/ and /ny/) undergoes obligatory Nasal Place Assimilation morpheme-internally and across
synthetic-suffix boundaries (ember [εmbεr], lámpa [laːmpɔ]), but the same process is only *optional*
across compound and phrase boundaries, where casual/colloquial speech shows genuine gradient
variability. A further, more casual-register process can bleed place assimilation entirely: before a
continuant, N deletes with compensatory nasalization of the preceding vowel instead of assimilating in
place (tanszer 'school equipment' → [tɑ̃ːsεr], bűnjel 'corpus delicti' → [byːɲεl]). Liquid deletion (of /l/,
/r/, and — patterning with the other two liquids for this and several other processes — /j/) is presented
as a genuine casual-speech continuum: /l/ deletes most readily of the three (balra → [bɔːrɔ]), producing
compensatory lengthening of the preceding vowel when it was short. This is directly useful corroboration
for `language_corpus/Hungarian/` collection work: several of these casual/colloquial forms (bűnjel-type
nasalized vowels, balra-type liquid-dropped forms) would show up as non-standard orthographic
spellings or transcription artifacts in informal written slang/subtitle sources, and this source gives a
principled phonological account of exactly which environments license them. pp. 207–213 (PDF)

### 8.1 The central theoretical move: a formal underlying distinction between "full" and "defective" vowels

This is the single most significant refinement this source adds beyond what `established/007`–`008`
(Kornai) already captured about Hungarian's pervasive vowel~zero alternation (unstable/"epenthetic"
vowels, linking vowels, lowering). Where Kornai's paper treats these largely as a set of morphologically
governed allomorphy rules, this book gives a fully phonological account built on a formal underlying
contrast between **full vowels** (Vf — minimally specified with a genuine vocalic/root node) and
**defective vowels** (Vd — an empty timing slot with no segmental melody at all, only phonetically
realized if it is later "licensed" by successfully syllabifying inside a closed syllable, via a rule the book
calls Default V). Under this analysis:
- **"Epenthetic" stems are reanalyzed as NOT ending in a genuine consonant cluster at all.** A stem
  like `torony` 'tower' is claimed to be underlyingly `-CVdC#` (a single final consonant preceded by a
  defective vowel), not `-CC#` as most prior accounts (including Vago 1980a and even some of Kornai's
  own assumptions) had claimed. This is argued from a three-way minimal-triplet contrast: `torony`
  ('epenthetic': -ok suffixed torny-ok) vs. `szurony` 'bayonet' (non-alternating: szurony-ok, never
  *szurny-ok) vs. `szörny` 'monster' (genuinely CC-final: szörny-ek, no alternation possible at all). The
  book shows at length that no purely phonotactic account (treating the vowel~zero pattern as
  epenthesis breaking up an otherwise-illegal cluster, or as deletion of an ordinary vowel) can
  distinguish these three classes, since the same surface consonant clusters occur both as licit
  non-alternating codas (szörny) and as the "repaired" alternant of an epenthetic stem (torony) —
  only a genuine three-way underlying representational distinction (Vd vs. Vf vs. no vowel at all) can
  capture the pattern.
- **Suffixes are formally split into "Type A" (underlyingly vowel-initial: plural -Vk, superessive -Vn,
  1sg possessive -Vm) and "Type B" (underlyingly consonant-initial: accusative -t, past tense -tt/-t)**,
  and the vowel~zero alternation each shows is derived automatically from syllabification interacting
  with the Hungarian syllable template, not stipulated per-suffix. Type A suffixes' initial vowel is a full
  vowel that simply deletes by a general Hiatus-resolution rule after another vowel; Type B suffixes are
  bare consonants that trigger insertion of a defective vowel (an empty timing slot, "overparsing") only
  when the preceding stem-final consonant cannot otherwise form a well-formed syllable coda with them.
- **Lowering** (the ház-ak/gáz-ok mid-vs-low linking-vowel contrast) is likewise given a formal
  representational source: lowering stems and lowering suffixes both carry an extra, floating [+open1]
  feature plus a morpheme-final defective vowel, and only an unstable (defective) vowel can ever be the
  target of lowering — the already-stable superessive suffix (-on/-en/-ön) is shown to be a genuine
  formal exception, since it is unstable (undergoes the ordinary vowel~zero alternation) but never
  lowers, distinguishing "unstable" and "lowerable" as two independently varying properties rather than
  a single package.
This whole apparatus is a genuinely deeper, source-independent confirmation (via a completely different
theoretical framework) that Hungarian's vowel~zero system is real, systematic, and only partially
morphologically arbitrary — directly useful for `analysis/morphological_play` work distinguishing which
parts of this system a slang-formation process could plausibly exploit productively (the syllabification-
driven Type A/B alternation) versus which parts are pure lexical idiosyncrasy that would have to be
memorized per-item (which specific stems are "epenthetic" or "lowering"). pp. 213–277 (PDF)

### 8.2.1 The alternating v-suffixes (-val/-vel, -vá/-vé) are reanalyzed via a generalized consonant-spreading rule, not an abstract /w/

Refining prior generative treatments that posited an abstract underlying /w/ segment for these two
"chameleon" case suffixes (which surface with a /v/ after vowel-final stems but fully assimilate to the
stem-final consonant otherwise: csap-pal 'with a tap' [pː], méz-zel 'with honey' [zː], kar-ral 'with an
arm' [rː]), the book proposes they begin with an empty timing slot that a generalized rule ("C-spread,"
the same mechanism independently needed for the past-tense suffix's own apparent "gemination")
fills by copying the stem-final consonant's melody — but *only* when that consonant is itself preceded
by a full vowel. This single condition automatically predicts, with no separate degemination rule needed,
that cluster-final stems (domb-bal 'with a hill' → [dombɔl], not a geminate *[domb-bɔl]) simply never
undergo the spreading in the first place. Two non-alternating v-suffixes (-van/-ven '-ty' as in hatvan
'sixty', deverbal -va/-ve 'while ...-ing') are shown to behave completely differently (retaining /v/ even
after consonant-final stems) because they are *analytic* rather than *synthetic* suffixes — directly
reinforcing the analytic/synthetic suffix-boundary distinction already established elsewhere in this
source. pp. 269–274 (PDF)

### 8.2.2 The h~zero and h~x alternations: a claimed sound change in progress

Hungarian's h-final stems show two competing alternation patterns: `cseh`-type (h alternates with zero:
cseh [tʃε] ~ cseh-es [tʃεhεʃ]) and `doh`-type (h alternates with a velar fricative [x]: doh [dox] ~ doh-os
[dohoʃ]). Contrary to most prior accounts (which treated /h/ as underlying and cseh as the regular,
productive pattern), this source argues from present-day Educated Colloquial Hungarian (ECH) evidence
that the **doh type is now the productive, synchronically real pattern**, while cseh-type alternation is a
fossilized suppletive-allomorphy relic surviving reliably in only a single lexical item (cseh itself) — most
traditionally-cseh-type stems (juh 'sheep', méh 'bee', düh 'anger', rüh 'scabies') now show real
inter- and even intra-speaker variation, all new loanwords and acronyms ending in orthographic h are
uniformly doh-type (Hezbollah → [hεdzbolːɔx], APEH 'tax office' → [ɔpεx]), and the underlying segment
is re-analyzed as /x/ (not /h/), with [h] itself derived by a place-deletion ("weakening") rule rather than
the reverse. **Explicit, source-marked register/sound-change flag:** this is presented as a genuine,
observable diachronic shift within a single living register (ECH), not a stable dialect split — worth
flagging for any future work on real-time Hungarian phonological change relevant to slang/informal
registers, since new coinages and borrowings are explicitly predicted (by the book's own productivity
argument) to default to the doh pattern. pp. 274–277 (PDF)

### 9.1–9.2 Surface vowel-duration vacillation and compensatory lengthening are systematically distinguished from lexical alternations

Chapter 9 catalogs casual/fast-speech phenomena and is careful throughout to distinguish (i) genuine
inter-speaker variation rooted in different underlying lexical representations (szính/szí:nész 'actor',
tejfel/tejföl 'sour cream') from (ii) postlexical, non-structure-preserving rule optionality that produces
vacillation even within a single speaker's own usage (nem-final long-vowel shortening: általános →
[ɔltɔlaːnoʃ], keeping vowel quality unchanged, unlike genuine lexical FSVS shortening which *does*
change vowel quality toward the corresponding short vowel's timbre). Compensatory lengthening from
liquid or nasal deletion (balra → [bɔːrɔ]; színház → nasalized [sĩːɦaːz]) is shown to never change vowel
quality, and — a clean minimal-pair illustration — the deletion of /n/ vs. /l/ in the near-minimal pair
szánhat 'may pity' / szállhat 'may fly' shows that nasality-on-the-vowel can become the *sole* surviving
phonetic trace distinguishing two underlying forms once both consonants are independently likely to
delete and neither produces observable extra length (since the preceding vowel is already long). pp.
278–283 (PDF)

### 9.3 Hiatus filling is governed by vowel height/backness, not simply by adjacency

Vowel hiatus sequences surviving into the postlexical phonology (i.e., ones not eliminated by the lexical
Hiatus rule discussed in §8.1.4.2) are optionally "repaired" with an inserted glide, but *whether* filling
happens, and how obligatorily, depends systematically on the quality of the vowel adjacent to the
hiatus: hiatus is **obligatorily** filled (with [j]) whenever one of the two vowels is high and coronal (/i/
or /iː/: hiány [hijaːɲ] 'lack'); it is **optionally** filled when one of the vowels is /eː/, with an asymmetry
depending on which side the /eː/ is on; and hiatus is **never** filled (no glide ever inserted) when both
vowels are rounded, back, or low, in any combination (ráadás 'encore' [raːɔdaːʃ], never *[raːjɔdaːʃ]).
This gives a clean phonetically-grounded generalization (front unrounded high vowels are the most
natural glide sources) rather than a language-particular stipulation. pp. 282–286 (PDF)

### 9.4 Degemination is not one rule but three, operating at three different derivational levels

The book distinguishes (i) an obligatory word-level rule that degeminates *derived* true geminates
created by certain lexical assimilation processes (e.g. the [tʃː] that would otherwise arise from full
t+j assimilation in önts-type imperatives, which surfaces short as [tʃ]); (ii) a postlexical rule,
Degemination II, that applies obligatorily word-internally but only optionally and gradiently (weakening
across increasingly "strong" syntactic/prosodic boundaries and increasingly formal registers) across
word/phrase boundaries; and (iii) a phonetic-implementation-level rule, Degemination III, that
optionally shortens *fake* geminates (sequences of two underlyingly-separate identical consonants
that have phonetically merged into a single long segment) with a probability that gradiently depends on
the flanking consonant's manner class — most likely to degeminate next to an obstruent, least likely
next to a liquid. A genuinely useful register data point: the book gives a graded table (obstruent >
nasal > liquid flanking context) predicting the *relative likelihood* of degemination in fast/casual
speech, which is directly transferable to any future transcription-confidence work on Hungarian
casual-speech or subtitle-sourced slang corpus material, where such reduced/degeminated
pronunciations are likely to show up as non-standard spellings. pp. 286–293 (PDF)

### 9.5 Fast Cluster Simplification (FCS): a three-consonant-cluster reduction rule with three independently necessary conditions

In fast/casual speech, the middle consonant of certain CCC clusters can delete (lambda [lɔmbdɔ] ~
[lɔmdɔ]), but the book shows through systematic minimal comparison that this is not free variation: FCS
requires simultaneously that (i) the target (middle) consonant is a plosive, not a fricative/affricate
(C2 ≠ [–son, +cont]); (ii) the following consonant (C3) is itself non-continuant ([–cont]) — clusters like
centrum [tsεntrum] never simplify because /r/ is a continuant; and (iii) the preceding consonant (C1) is
not a continuant sonorant — clusters like partner never simplify for the same structural reason. All
three conditions must hold simultaneously; violating any one blocks the rule regardless of the others.
The book explicitly rejects a competing syllable-structure-based account (that FCS applies only when the
resulting onset would otherwise be ill-formed) using counterexamples like handlé 'second-hand dealer'
([hɔndleː], never *[hɔnleː]) where the syllable-structure account wrongly predicts simplification should
be possible. pp. 293–296 (PDF)

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of the source's own formal
autosegmental diagrams, rule tableaux, or extended argumentative prose. Worked example words and
generalizations above are re-summarized/re-paraphrased in this project's own words, not copied
verbatim from the source's typesetting. See `00_Reference_Extraction_Spec.md`.
