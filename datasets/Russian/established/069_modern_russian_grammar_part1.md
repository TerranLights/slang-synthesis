# Russian — *Modern Russian Grammar: A Practical Guide* (Part 1 of 4)

**Source:** John Dunn and Shamil Khairov, *Modern Russian Grammar: A Practical Guide*
(Routledge Modern Grammars series), Routledge, 2009. 962 pages total.
**This file covers PDF pages 1–240** (front matter + Part A, Chapters 1–5: Sounds and
spelling; Nouns; Case; Verbs; Aspects of the verb, through roughly printed page 112 of
131, i.e. partway into Chapter 5's discussion of aspect usage). Sibling files cover pages
241–480, 481–720 and 721–962.

## Coverage note — critical PDF-extraction limitation (read before using this file)

This source's dispatch described it as a "confirmed clean text layer PDF" based on
sampling — that sampling looked at English narrative prose only. On closer inspection
of the actual grammar content, **this book uses a CID-embedded TrueType font
(`TimesNewRoman`, Identity-H encoding, `uni=no` in `pdffonts` output) with no usable
ToUnicode mapping for the Russian-language example material.** Unlike the various
Cyrillic font-substitution *ciphers* documented elsewhere in this project's Russian
corpus (keyboard-layout swaps, cp1251-as-latin1, arbitrary 1:1 substitution, homoglyph
swaps — see `00_Reference_Extraction_Spec.md`), this is the **non-decodable** case the
spec also documents: `pdftotext` does not garble these glyphs into wrong-but-consistent
characters, it silently **drops them entirely**. Verified directly: extracting a content
page (e.g. printed p.3, PDF p.27) and scanning every character in the output for
codepoints above U+007F (excluding ordinary typographic quotes/dashes) returns **zero
non-ASCII characters** — not even a placeholder. This affects every Russian-language
example word, table, and transliteration chart in the assigned page range; English
narrative prose, English translations of Russian examples, and any transliterated form
that the authors typed directly in Latin letters within running text (e.g. kinship terms
like *ziat'*, *shurin*, *dever'* in 3.3.1) all survive intact.

Practical effect on this extraction:
- **Grammar-point prose (paraphrased rules, functions, classifications) is fully
  recoverable** and is the bulk of this file's content — the coverage rule's "every
  grammar point" requirement is met.
- **The Vocabulary table is necessarily thin.** Where the source's own Cyrillic word is
  missing from the text layer, no invented Cyrillic has been supplied — fabricating a
  specific headword from memory when the actual source text is unrecoverable would
  violate this project's accuracy discipline (the wrong word could easily be substituted
  for what the authors actually chose). Only the handful of terms the authors themselves
  rendered in Latin letters survive and are tabulated below.
- **Recommendation for the checklist maintainer:** if fuller vocabulary/example capture
  from this specific book is wanted later, it requires a vision-reading pass (rendering
  pages to images), not further `pdftotext` attempts — no fixed offset or substitution
  cipher exists to recover this font's mapping, matching the spec's "some CID-embedded
  fonts have no usable ToUnicode mapping at all" case.

## Non-redundant-supplement scope note

Russian already has extensive grammar coverage from `002/003` (Wade, *A Comprehensive
Russian Grammar*), `006/007` (Timberlake, *A Reference Grammar of Russian*), `001n`
(*A Basic Modern Russian Grammar*), `012/013` (Schaum's Outline), and others. Chapters
1–5 of this book (sounds/spelling, nouns, case, verbs, aspect) cover exactly the same
grammatical territory as those. This book's genuine differentiator is Dunn & Khairov's
**functional/communicative organizing principle** (explicit in their own introduction:
Part A = structures, Part B = functions — establishing identity, establishing contact,
asking questions, coming and going, communication strategies, etc.), which this page
range does not yet reach (Part B begins at printed p.277, well past page 240). Within
Part A, what's kept below is:
- Rules, exceptions, and classifications not obviously duplicated by the phrasing in
  prior established/ files (e.g. the vowel-reduction transcription symbols α/ə, the
  "stress unit" concept spanning multiple words, the four-way classification of
  aspect-choice situations, the productive/unproductive verb-class taxonomy's specific
  class count).
- Genuinely distinct usage nuances (e.g. the жаль/жалко accusative-vs-genitive-vs-object
  distinction, the definite/indefinite accusative-vs-genitive alternation with verbs like
  ждать/просить/хотеть/требовать).
Skipped as redundant: exhaustive declension paradigm tables (endings-by-case-by-gender),
which prior sources already tabulate in full and which this book presents identically
without new information given the text-layer gap prevents even reading the endings here.

---

## Vocabulary

Only terms the source itself renders in Latin letters (transliterated proper names,
kinship terms glossed inline) survive text extraction; the source's Cyrillic headwords
for these same items were not recoverable (see coverage note above).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ziat' | husband of one's sister ("brother-in-law") | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | Cyrillic headword (зять) not recoverable from text layer; Latin form is the authors' own transliteration, given inline (3.3.1) |
| shurin | brother of one's wife ("brother-in-law") | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | Cyrillic headword (шурин) not recoverable from text layer |
| dever' | brother of one's husband ("brother-in-law") | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | Cyrillic headword (деверь) not recoverable from text layer |
| solianka | a thick soup with meat or fish and vegetables | noun | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | n/a | Given by the authors in italicized transliteration within an English example sentence (3.2); Cyrillic form (солянка) not recoverable |

The book's own transliteration-system chapter (1.6) is itself a genuinely useful
resource (Library of Congress system, its acknowledged ambiguities, and departures from
it for well-established names like *Tchaikovsky*, *Yeltsin*, *Gorbachev*/*Gorbachov*),
but its worked examples are presented as parallel Cyrillic/Latin tables that did not
survive extraction — only the discursive notes around them did (captured as a grammar
point below).

## Grammar points

### 1. Sounds and spelling (Chapter 1)

**1.1–1.2 Alphabet and consonants.** Russian's 33-letter Cyrillic alphabet: 21 consonant
letters, 10 vowel letters, and 2 letters (soft sign, hard sign) with no sound value of
their own. Most Russian consonants form hard/soft pairs distinguished by palatalization
(the middle of the tongue raised toward the hard palate for the soft member); a handful
of consonants are always hard, and a couple are always soft. Hardness/softness is
phonemically distinctive — minimal pairs exist that differ only in this feature (the
book gives several near-homophone sets built this way, e.g. distinguishing 'was' from
'true story' and past-tense forms of 'to hit/beat' purely by which consonants are hard
vs. soft — the specific Cyrillic words are not recoverable from this file's text layer).

**1.3–1.4 Vowels and stress.** Stress in Russian is described as *free* (can fall on any
syllable) and *mobile* (can shift to a different syllable across different forms of the
same word) — illustrated with the noun for 'head' showing stress movement across its
paradigm. Because stress is mobile and meaning-distinguishing, the book uses the acute
accent (′) throughout to mark it (except in a few passages deliberately reproducing
normal, unmarked print). Single-syllable words are not normally marked for stress unless
the syllable is carrying stress for an adjacent word (see "stress units" below); a word
can carry two stress marks when the language genuinely allows two accepted pronunciations
(the example given: a past-tense feminine verb form meaning 'she was born', where either
of two stress placements is standard).

The book gives a genuinely useful **phonetic-transcription notation for degrees of
unstressed-vowel reduction** not seen framed this way elsewhere in this corpus: it uses
the symbol **α** for a reduced-but-still-distinct short vowel (comparable to the vowel
in the Scottish "Mac/Mc" prefix, or the first vowel of "candelabra"), and **ə** (schwa)
for a fully neutral reduced vowel (the second/final vowel of "candelabra"). Rules given:
unstressed *a* and *o* reduce to α in the syllable immediately before stress or at the
very start of a word, and to ə everywhere else unstressed; unstressed *e* and (the
"soft" e-like vowel) reduce to a short *i*-like sound before the stress and to ə after
it. Other unstressed vowels are simply shortened without a quality change.

A **"stress unit"** can span more than one word — most commonly a preposition +
following noun, or a word plus an adjacent unstressed particle — in which case vowel
reduction rules apply across the whole unit as if it were one word. Weaker **secondary
stress** (marked with a grave accent, `) can occur in multi-syllable prepositions or
compounds, and always precedes the main stress. (This "stress unit"/secondary-stress
framing, with its own diacritic conventions, is more systematically laid out here than
in this corpus's prior grammar extractions and is worth flagging to `analysis/` if
stress-mobility mechanics become relevant to slang-formation work.)

**1.5 Spelling rules.** Russian spelling is described as not strictly phonetic but far
more predictable than English spelling. Key rule areas (endings-focused, and thus mostly
requiring the actual Cyrillic to illustrate, which is not recoverable here): the letter
ë is used only in stressed syllables (hence stress is never separately marked on words
containing it); spelling-rule constraints after the "always-hard"/"always-soft" sibilant
and other consonant classes (governing which vowel letters can follow them); rules for
capitalization; and rules for the use of inverted commas (quotation marks) — notably,
the book gives an example of the *same* headword changing between animate and
inanimate depending on whether it denotes a historical figure (Spartacus, animate) or an
organization named after him (the "Spartak" sports society, inanimate) — the
organizational sense is conventionally written in quotation marks precisely to signal
this shift (cross-referenced from the animacy section, 2.4).

**1.6 Transliteration and transcription.** The book distinguishes *transliteration*
(substituting the nearest English letters so a reader can reconstruct Russian spelling)
from *transcription* (substituting letters to reconstruct pronunciation), and states it
uses the Library of Congress transliteration system throughout except where explicitly
noted. Two acknowledged ambiguities/exceptions: (1) an unstressed "e" spelling used
instead of "ë" is usually transliterated as plain *e*, so a name spelled with ë stressed
becomes e.g. "Gorbachëv" while the same name's ë-less spelling becomes "Gorbachev"; (2)
the LC system uses "i" for two distinct Russian letters, creating real ambiguity. In less
formal contexts, departures are treated as acceptable: dropping the apostrophe used for
the soft sign, or favoring an English spelling that better represents pronunciation or
that has simply become conventional (e.g. "Yeltsin", "Yaroslavl", "Tchaikovsky" — the
last explicitly noted as based on a 19th-century French transliteration convention, not
the modern LC system). A separate, reverse direction — representing *English* words and
names in Russian — is treated as effectively a transcription problem rather than a
transliteration one, because English spelling-to-sound correspondence is too irregular;
the book notes this transcription is historically modeled on "a British film actor of
the 1930s" pronunciation and gives conventions for sounds absent from Russian (h, j/soft
g, and the two "th" sounds), noting the convention for English "h" survives mainly in
long-established proper names (their example: the Russian rendering of "Harold").

### 2. Nouns (Chapter 2)

**2.1–2.2 Number and case overview.** Standard Russian noun categories: number (some
nouns are singular-only, others plural-only), the six-case system (nominative,
genitive, dative, accusative, instrumental, prepositional), gender, animacy.

**2.3 Gender.** Grammatical gender only partially tracks biological sex — a genuinely
useful point the book makes with unusually direct examples: there exist a small number
of *neuter* nouns that can denote persons or animals. The only fully reliable indicator
of a noun's grammatical gender, per the authors, is the ending taken by an accompanying
adjective or pronoun — the noun's own ending is a strong but imperfect predictor.
General correlations given: consonant/soft-sign endings → usually masculine; -a/-я
endings → usually feminine, *except* when the referent is specifically male (masculine
despite the ending) or can be either sex (masculine by default, feminine only when the
referent is specifically female); -о/-е/-ё/-мя endings → usually neuter. Nouns ending in
the soft sign are the genuinely ambiguous case (some masculine, some feminine), but the
book gives sub-rules that resolve much of this ambiguity: soft-sign nouns denoting an
occupation/role are masculine; month names are masculine; abstract nouns formed with
certain soft-sign-preceding suffix patterns are feminine (as are several other named
suffix classes) — beyond these patterned subsets, gender for soft-sign nouns has to be
learned lexically.

**2.4 Animacy.** Animate = denotes a human or animal; affects accusative-case
morphology specifically (animate nouns take an accusative identical to the genitive;
inanimate nouns take an accusative identical to the nominative — true in the singular
for masculine nouns of the relevant declension types, and true for *all* genders in the
plural). The chapter's most genuinely interesting content is its documented animacy
exceptions, which don't reduce to "common sense" the way the authors claim most cases
do: a word for "corpse" is grammatically *inanimate* while a near-synonym for "dead man"
is *animate*; a word for "doll/puppet" is animate; the chess piece "queen" is a masculine
animate noun; and — most strikingly — a single noun can flip animacy class *by sense*:
one word is animate when it means "person" but inanimate when it means "face" (same
headword, different lexical sense); similarly the same proper-name headword is animate
denoting the historical figure Spartacus but inanimate denoting the "Spartak" sports
organization named after him (see the quotation-mark cross-reference above, 1.5.8).

**2.5 The fleeting vowel.** A vowel (normally e, ë, or o) that appears in some
inflected forms of a word but is absent from others — most significant for noun
declension, but the book cross-references its appearance in verb and adjective
paradigms too (4.5.3, 4.7.3, 4.7.13, 6.5.1), treating it as one unified phenomenon
recurring across word classes rather than a noun-only quirk.

**2.6–2.11 Declension-type detail and non-standard endings.** The book catalogs, beyond
the standard declension endings (redundant with prior sources and not independently
verifiable here without the Cyrillic tables), several **non-standard ending phenomena**
worth flagging by name even without their specific paradigms: a "second genitive"
ending (distinct from the standard genitive singular, used in certain masculine nouns —
cross-referenced at 2.7.1), a "second prepositional" ending (2.7.2), and a "zero
ending" pattern in the genitive plural (2.7.4, i.e. some noun classes take no overt
suffix at all in genitive plural). Also covered: non-standard nominative-plural and
genitive-plural endings for neuter -o/-e nouns (2.8.5–2.8.6); several distinct
"non-standard declension types" including nouns with irregular plural stems, and — a
genuinely notable closed class — **nouns where the singular and plural forms are
totally different** (i.e. suppletive number, 2.11.7), plus nouns that exist only in the
plural and so have their own, gender-neutral declension pattern (2.11.8).

**2.12 Surnames.** Russian surnames ending in a particular common surname-suffix
pattern decline with dedicated surname-specific endings (distinct from ordinary
adjective declension); other surnames ending in a consonant or soft sign follow their
own rules.

**2.13 Indeclinable nouns.** The book treats "which nouns are indeclinable" as a
genuine open question needing its own criteria (2.13.1) rather than a short fixed list,
and separately addresses how to determine the *gender* of a noun that has no case
endings to signal gender via agreement (2.13.2) — gender assignment for indeclinables
has to rely on other cues (e.g. semantic class, or the gender of a Russian hypernym for
the borrowed concept).

**2.14 Abbreviations and acronyms.** Covered as its own subsystem: whether an
abbreviation/acronym declines at all, and if so how (2.14.1), and how its grammatical
gender is determined (2.14.2) — typically by the gender of the abbreviation's own head
noun when spelled out in full, a mechanism directly relevant to how new
initialism-based slang or brand-derived terms might later be integrated grammatically
in the conlang-synthesis phase.

### 3. Case (Chapter 3)

**3.0 Framing.** The authors motivate the case system by analogy to the three surviving
case-like forms of the English pronoun "he" (he/him/his for subject/object-or-post-
preposition/possessive), then note the Russian system is far more elaborate: six cases,
applying not just to nouns but to adjectives, pronouns and numerals, with functions per
case that are "in many instances neither obvious nor logical." This chapter is scoped to
each case's *principal* functions only; further use-in-context detail is deferred to
Part B (functions), out of this page range.

**3.1 Nominative.** Used as the dictionary-citation form (nouns cited in nominative
singular, or nominative plural for plural-only nouns; adjectives/pronouns/the numeral
"one" cited in nominative singular masculine); as the subject of a finite verb (with an
explicit note that Russian word order does not require the subject to precede the
verb); as the complement in equational/definitional sentences lacking an explicit
copula, and sometimes even with an explicit copula-like verb when the complement is an
adjective; and — a function some learner grammars skip — as the case used when directly
addressing a person by name or title (vocative-like use of the nominative).

**3.2 Accusative.** Principal function: direct object. A specific idiomatic-register
note: when ordering food/drink or asking for a specific person on the phone, Russian
uses the accusative even with no verb present in the sentence at all (elliptical
accusative, e.g. "[accusative noun for what you want], please" as a complete
restaurant-ordering utterance) — flagged as directly relevant to conversational-register
mechanics.

**3.3 Genitive.** The chapter gives an unusually thorough functional breakdown: (a)
genitive between two adjacent nouns for possession-in-the-strict-sense, for
relationship terms (this is where the ziat'/shurin/dever' kinship-term triad above
comes from — Russian has three distinct dedicated words corresponding to the single
English "brother-in-law," disambiguated by whose sibling/spouse is meant), for
functions/positions/titles, for part-of-whole constructions, and — in two-noun
constructions — genitive can mark either the performer of an action (subjective
genitive) or the object of an action (objective genitive), with the ambiguity resolved
only by context/meaning, not by form; (b) genitive for quantity expressions (measure
words like "a loaf of," "a litre of") and partitive/indefinite-quantity constructions
("some" tea, "some" money); (c) genitive with negated forms of "to be"-type verbs to
express absence/non-existence, and genitive as an alternative to accusative for the
direct object of a negated verb generally (cross-referenced to a fuller treatment at
15.5, out of this page range); (d) an extensive list of verbs that *require* a genitive
object (fear, wish/desire in salutations — the book notes several genitive-based
farewell formulas rest on an implied, unspoken verb "I wish," including an explicitly
flagged internet/email-register semi-humorous greeting equivalent to "good whatever
time of day it is"); a usage note that in more informal/colloquial registers, some of
these normally-genitive-taking verbs can instead take an accusative object, especially
when the object is animate or a proper name — directly relevant register-variation data.

**3.3.5 The accusative/genitive alternation.** A cluster of verbs (wait for, ask/request,
want, demand) can take either case, with a fairly clean semantic rule stated: accusative
tends to mark a definite object (especially if animate), genitive an indefinite/abstract
one. A verb meaning "to cost" is given its own sub-rule: accusative when the object is a
specific sum of money, genitive otherwise (its example: "winning the championship cost
him a broken rib" — genitive, non-monetary cost). Genuinely deeper than a flat
case-government list.

**3.4 Dative.** Indirect object (recipient of something given/communicated); the person
to whom permission is given or refused; the *logical subject of an infinitive* (since
infinitives, being non-finite, can never take a nominative subject — any "subject" of an
infinitive clause surfaces in the dative instead, e.g. impersonal "you should get proper
rest" constructions); and the dative as the core participant-marking case for a wide
range of impersonal constructions generally (verb, where present, appears in a fixed
3rd-singular/neuter-past form with no nominative subject at all). A genuinely
fine-grained usage note is given for a pair of near-synonymous verbs both translatable
as "feel sorry for" vs. a related verb meaning "to begrudge": the "feel sorry for" verbs
take an accusative object, while the "begrudge" sense of the third verb can take either
genitive or accusative — a three-way case-government distinction across near-synonyms
that is a plausible register/nuance seed for later mechanics analysis.

### 4. Verbs (Chapter 4)

**4.1–4.2 Infinitive and aspect.** Introduces the imperfective/perfective aspect system
(nearly every Russian verb belongs to one aspect or the other) and classifies aspectual
pairs by formation type: unprefixed pairs, pairs where the imperfective is unprefixed
and the perfective is formed by prefixation, pairs where *both* members share the same
prefix, pairs where the two aspect-partners are historically/formally unrelated
(suppletive pairs), and a named set of exceptions to the general "every verb pairs up"
principle.

**4.3–4.5 Tense formation.** Present tense (imperfective-only; endings-based, not
independently verifiable here without Cyrillic); future tense, split cleanly by aspect
(imperfective future is periphrastic/analytic, perfective future is morphologically
identical in form to the present-tense conjugation pattern but perfective in meaning —
implied by the chapter's own imperfective/perfective sub-split, 4.4.1/4.4.2); past tense
formation, with its own subsection for stems ending in a consonant (4.5.2) and a named
single "irregular past tense form" (4.5.3, presumably connecting to the fleeting-vowel
cross-reference noted in 2.5.0).

**4.6–4.7 Verb-class taxonomy.** The book organizes verb conjugation not around the
traditional two-conjugation split alone but around a **productive/unproductive class
system**: four *productive* classes (three for first-conjugation verbs, one for second-
conjugation verbs) that new verbs entering the language still join, versus a much larger,
closed set of **unproductive classes** — at least thirteen distinct unproductive classes
of first-conjugation verbs are individually enumerated (4.7.1 through 4.7.14, with one
class number apparently skipped/renumbered — 4.7.12 does not appear in this chunk's
heading list), plus two further unproductive classes specific to second-conjugation
verbs. This granular a productive/unproductive split, with this many named subclasses,
is more systematic than the verb-classification schemes captured from prior sources in
this corpus and may be worth a dedicated `analysis/` cross-reference if verb-derivation
productivity becomes relevant to modeling how new (in-universe) slang verbs would be
expected to conjugate.

**4.8 Irregular verbs** — a distinct, presumably small closed list, separate from the
regular unproductive classes above.

**4.9 Imperative,** split by grammatical person: second-person singular, second-person
plural, and a third-person imperative construction (typically periphrastic in Russian,
formed with a particle plus a third-person verb form, consistent with general Slavic
imperative typology).

**4.10 Conditional (subjunctive).** Treated as a single mood category (Russian does not
formally distinguish conditional from subjunctive mood the way some European languages
do — both map onto one construction).

**4.11 Gerunds,** split by aspect: imperfective gerund (roughly, "while doing") vs.
perfective gerund (roughly, "having done") — each aspect's gerund formation given its
own subsection.

**4.12 Participles,** split into four types by voice and tense: present active, past
active, present passive, past passive — the standard four-way Russian participle
system, presented compactly here without full paradigms (endings require Cyrillic not
recoverable in this file).

**4.13 Transitivity and reflexivity.** Transitive vs. intransitive verbs, and reflexive
verbs (formed from a base verb plus a fixed reflexive-marking suffix) treated as a
distinct grammatical category with its own functional range beyond literal reflexivity
(cross-referencing forward into passive-voice formation, see 4.14 below).

**4.14 Active and passive voice.** The passive voice is treated separately for each
aspect: imperfective passives (4.14.2) and perfective passives (4.14.3) are formed by
different mechanisms — consistent with the general cross-linguistic pattern that
Russian's periphrastic/reflexive-marker passive strategies differ by aspect, though the
book's specific mechanism-by-mechanism claims aren't independently checkable here
without the (unrecoverable) Cyrillic examples.

### 5. Aspects of the verb — usage (Chapter 5, partial: through printed p.112 of 131)

**5.0 Framing.** The authors give an explicit, quotable single-sentence account of the
aspect distinction, while flagging its own limits: *"the perfective aspect is used when
an action or state is considered from the point of view of its boundaries (beginning,
end or both), while the imperfective is used in all other circumstances"* — offered as
"as good a single-sentence statement... as any," with an explicit acknowledgment that it
will sometimes fail to predict actual usage. They motivate the general difficulty of
aspect for English speakers via three reasons: (1) aspect has to be chosen almost every
time a verb is used (extending even to gerunds and some participles, not just finite
forms); (2) the imperfective/perfective distinction doesn't line up with any single
English tense-aspect distinction — a past-tense imperfective verb can correspond to any
of English "I read / I have read / I did read / I had read / I was reading / I used to
read / I would read," while a past-tense perfective verb can correspond to the first four
of those but not the progressive/habitual ones; (3) no short rule can cover every case.

**A genuinely useful, reusable four-way taxonomy of aspect-choice situations** (5.0,
elaborated across the rest of the chapter): (1) only one aspect is grammatically
possible at all; (2) either aspect is possible but *changes the sentence's meaning*; (3)
one aspect is preferred but the other would not cause a misunderstanding, only sound
slightly off; (4) either aspect works with no meaningful difference at all. Only
categories 1 and 2 carry real risk of a grammatically unacceptable or misunderstood
sentence — a genuinely practical framing for grading how much any given
aspect-related "error" in synthesized in-universe dialogue would actually matter.

**5.1 Situations with no real choice** (infinitive-governed). The infinitive must be
imperfective when governed by: (a) a verb of beginning/continuing/stopping an action
(begin to, break off, continue, finish, stop, give up); (b) a predicate expressing that
an action is undesirable or pointless (shouldn't, not worth [X]-ing, pointless to,
no point in, doesn't make sense to); (c) a small fixed list of other governing verbs
(including one meaning "to know how to" / "to be able to [skill-based]"). Conversely,
the infinitive must be *perfective* when governed by a small set of perfective verbs
themselves (e.g. "let's [go do X]," "I'll manage to call in," "he managed to find"), with
a specific note that the "manage to" verb is impersonal and takes its logical subject in
the dative (directly cross-referencing the impersonal-dative pattern from 3.4.3/11.2.2 —
a nice concrete tie between the case chapter and the aspect chapter).

**5.2.1 Incomplete actions.** A verb denoting an action treated as *incomplete* — ongoing,
interruptible, or backgrounded relative to another event — is imperfective; incompleteness
can be explicit (an interrupting event stated in the sentence) or simply implied by
context (e.g. a list of things one did over an evening, framed as ongoing activities
rather than discrete completed accomplishments).

**5.2.x Repeated actions (partial, cuts off at the page-240 boundary).** When a sentence
combines a finite verb and an infinitive in a repeated-action context, aspect choice
depends on *which* of the two verbs denotes the repeated action, not a fixed rule for
the sentence as a whole — illustrated with a minimal pair: "he advised me [perfective,
once] to drink [imperfective, repeatedly] a litre of water daily" vs. "every time we met
[imperfective, repeated] he advised [perfective, single each time] me to write my
autobiography" — same two verbs, aspects swapped, because the locus of repetition
swapped. Separately, a perfective verb can still describe a *series* of repeated actions
when that series is conceptualized as a single completed event/unit — either as a tight
chain of quick, sequential actions, or as a summed-up total achievement over a stated
period (the book's own example: "she has published over 200 articles... in the last ten
years" — a perfective encompassing many repetitions, reframed as one cumulative
outcome). This chapter's discussion continues past the page-240 cutoff for this file;
the remainder is left to the sibling file covering pages 241–480.

---

*No changes made to `00_Extraction_Checklist.md` or `graphify-out/` by this subagent, per
dispatch instructions — both are left for the orchestrator's serialized follow-up pass.*
