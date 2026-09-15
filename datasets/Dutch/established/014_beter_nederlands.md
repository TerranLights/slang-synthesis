# Dutch — Established Vocabulary/Grammar: *Beter Nederlands: Grammaticaal hulpboek voor anderstaligen* (full book)

**Source:** *Beter Nederlands: Grammaticaal hulpboek voor anderstaligen* ("Better Dutch: Grammar
Aid for Non-Native Speakers"), a Dutch-medium grammar workbook, 199 PDF pages (printed pagination
runs to roughly p. 206, including the appendix). `source_reference/languages/Dutch/28 Beter
Nederlands Grammatical hulpboek voor anderstalingen.pdf`. Extracted via `pdftotext -layout` — the
PDF has a genuine (if OCR-scarred) text layer; no vision-reading was needed. Full 199-page range
covered in this single file, per dispatch instructions, rather than split into a numbered-file
series, because the book's own content — outside the appendix noted below — is almost entirely
grammar exposition with drill exercises, not large vocabulary blocks; splitting it would have
produced several very thin files.

**Coverage note.** This is a workbook: the overwhelming majority of its bulk is fill-in-the-blank
and substitution drills. Per the coverage rule, drills that don't introduce new vocabulary or
grammar beyond what's already captured are skipped; every distinct grammar point and every
register/usage annotation the book itself makes is captured below, paraphrased rather than quoted.

**Non-redundant-supplement scope decision** (checked against `established/001` "Chapters 1–3:
Pronunciation, Spelling, The Plural," `002` "Chapter 16: Colloquial speech," and `003` "Chapter 22:
Diminutives" — all three from the *other* Dutch grammar reference already in this project, Shetter &
Van der Cruysse-Van Antwerpen's *Dutch: An Essential Grammar*):

- **Skipped as substantially redundant:** this book's own appendix chapter "Het meervoud van
  zelfstandige naamwoorden" (pp. 177–183) reworks the same `-en`/`-s`/vowel-length/`-eren` plural
  system `001` already tabulates in more depth (irregular-plural lists overlap almost entry-for-
  entry: `blad→bladen`, `schip→schepen`, `stad→steden`, the `-heid→-heden` pattern). Not
  re-extracted as a vocabulary table; only the two genuinely new items this pass adds are noted
  under Grammar Points below (the `f`/`v`→`ven` and `s`→`zen` devoicing-consonant plural rule
  stated with a fuller "a Dutch word never ends in v or z" generalization than `001` gives, and the
  compound-linking-morpheme spelling rules `-e-`/`-en-` and `-s-`/`-ss-`, which `001` does not cover
  at all since those aren't plural morphology per se).
- **Kept as genuinely new, not covered by 001–003:** the diminutive material in this book (§2.4,
  one short paragraph, p. 32) is far thinner than `003`'s dedicated diminutive chapter and adds
  nothing `003` doesn't already have in more depth — skipped for that reason, not redundancy with
  001.
- **Everything else in this book is new territory** relative to 001–003: those three files never
  touch question-word syntax, articles, adjective agreement, negation, the full verb system (modal
  verbs, imperative, reflexives, separable verbs, progressive aspect), pronouns, numerals,
  prepositions, tense *usage* (as opposed to tense *formation*), or main-/subordinate-clause word
  order. All of that is extracted in full below.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| jij / je | "you" (sg., stressed/unstressed) | pronoun | core | — | contemporary (source published; undated in this printing) | — | — | grammar_reference | n/a | n/a | subject pronoun; used with friends, family, peers, and generally between young people even as strangers |
| u | "you" (sg./pl., formal) | pronoun | formal | — | — | — | — | grammar_reference | n/a | n/a | used for strangers/people with whom the speaker has no personal relationship; book frames the `jij/je`–`u` split as social distance, not just number |
| hem / haar / het | "him" / "her" / "it" (object) | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | `het` doubles as the generic object pronoun after verbs like *zien, begrijpen, denken, geloven* regardless of the antecedent's real gender/number |
| hen / hun / ze | "them" (object, personal) | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | `hen` = direct object or after a preposition; `hun` = indirect object without a preposition; `ze` is the everyday spoken cover term for both, avoiding the hen/hun distinction |
| er + preposition (erover, ermee, ertoe, erin, ...) | pronominal adverb replacing preposition + "it/them" (for things, never people) | pronoun/adverb | core | — | — | — | — | grammar_reference | n/a | n/a | mandatory substitution: a thing after a preposition can never surface as `het`/`ze`; contrast personal `over hem/haar/hen` |
| jouw / je / uw | "your" (stressed/unstressed/formal) | pronoun (possessive) | core/formal | — | — | — | — | grammar_reference | n/a | n/a | same stressed/unstressed split as jij/je |
| zo'n | "such a" (singular, countable) | determiner | colloquial | — | — | — | — | grammar_reference | n/a | n/a | contraction of *zo een*; contrasts with plural/mass `zulk(e)` |
| iets/niets/wat + adj. + -s | "something/nothing/what + adj." | construction | core | — | — | — | — | grammar_reference | n/a | n/a | e.g. *iets lekkers* "something tasty" — the adjective obligatorily takes -s in this indefinite-pronoun + adjective frame |
| ieder(e) / elk(e) | "every, each" (singular noun) | determiner | core | — | — | — | — | grammar_reference | n/a | n/a | contrasts with plural `alle` and mass-noun `al het/de` |
| iedereen / allemaal / allen / alles | "everyone" / "all (of them), altogether" / "all" (persons, no head noun) / "everything" | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | `allen` (persons) vs. `alle` (things) when no head noun follows is a distinction the book explicitly marks |
| men | "one" (impersonal, formal register) | pronoun | formal | — | — | — | — | grammar_reference | n/a | n/a | book glosses `men` as the formal-register counterpart of impersonal `je`; `ze` covers "unspecified people" in the everyday spoken equivalent |
| beide(n) / allebei / alle twee | "both" | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | `beide` takes -n only for persons with no following noun; contrasted explicitly with `samen` ("together," not "both") |
| hoeven (te) | "need to, have to" (negative-polarity modal) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | grammatically restricted: only usable when the clause already contains a negator (*niet, geen, nooit, niemand, niets, nergens, nauwelijks*); infinitive after it takes *te*, unlike *moeten* |
| nauwelijks | "hardly, scarcely" | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | glossed as "almost not/nothing/nobody/nowhere/never" depending on context — a near-negator, functionally close to *bijna niet/niets* |
| laten (+ infinitive) | "to have (something) done, to let/have someone else do it" | verb | core | — | — | — | — | grammar_reference | n/a | n/a | two distinct senses drilled separately: (1) causative "not doing the action oneself" (*ze laat haar auto repareren*); (2) proposal-initiating "Laten we..." ("Let's...") — glossed as more forceful than a *zullen*-proposal |
| zullen (proposal/promise use) | modal marking a promise, arrangement, or (in question form) a proposal | verb | core | — | — | — | — | grammar_reference | n/a | n/a | book explicitly contrasts *zullen*-proposals (leaves room for a counter-plan) with *laten*-proposals (more insistent) |
| aan het ... zijn | progressive/durative construction ("to be in the middle of doing X") | construction | core | — | — | — | — | grammar_reference | n/a | n/a | usable for present or past durative actions; contrasted with the *houdingswerkwoord* + *te* construction below as adding no stance/posture information |
| zitten/staan/liggen/lopen/hangen + te + infinitive | posture-verb progressive ("to be sitting/standing/lying/walking/hanging doing X") | construction | core | — | — | — | — | grammar_reference | n/a | n/a | called *houdingswerkwoorden* ("posture verbs") in the source; adds physical stance information the plain *aan het...zijn* progressive lacks |
| om ... te + infinitive | purpose clause ("in order to") | construction | core | — | — | — | — | grammar_reference | n/a | n/a | also used as a complement of adjectives/nouns expressing suitability, e.g. *leuk om naar te kijken* "nice to watch" |
| die / dat / deze / dit | demonstrative pronouns (distal/proximal, de-word/het-word) | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | also substitute for personal pronouns *hij/zij/het/ze* when picking something out with contrastive emphasis, per the book's own worked comparison |
| die / dat / waar (relative) | relative pronouns ("that, which, where") | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | `die` = de-word/plural/personal-name antecedent, `dat` = het-word antecedent, `wat` = whole-clause antecedent, `waar` (+prep.) = locative/thing antecedent standing in for a stranded preposition |
| tientje | a ten-euro note/amount ("a tenner") | noun (diminutive) | colloquial | — | contemporary (source published) | Netherlands | national | grammar_reference | n/a | n/a | numeral diminutive cited alongside *nulletje* ("little zero") and *zesje* (a school grade of 6/10) as evidence numerals take diminutive suffixes with their own idiomatic senses |
| zesje | a grade of 6 out of 10 (a bare pass) | noun (diminutive) | colloquial | — | contemporary (source published) | Netherlands | national | grammar_reference | n/a | n/a | see *tientje* note — school-grading register sense layered onto the plain numeral |
| Dat gaat je niets aan | "That's none of your business" | idiom | colloquial | — | — | — | — | grammar_reference | n/a | n/a | one of a cluster of fixed retorts to *Waarom?* the book lists together: *Dat zijn jouw/mijn zaken (niet)*, *Dat zeg ik liever niet* |
| een hekel hebben aan | "to dislike, have an aversion to" | idiom (verb + fixed prep.) | core | — | — | — | — | grammar_reference | n/a | n/a | listed with *last hebben van*, *zin hebben in*, *bang zijn voor*, *blij zijn met* as fixed noun/adjective + preposition collocations to be learned as units, distinct from the plain verb+preposition list (*denken aan, dromen over, houden van*, etc.) |
| gebeiteld zitten (not attested — omitted) | — | — | — | — | — | — | — | — | — | — |
| beginnen / beloven / durven / proberen / weigeren | modal-like control verbs taking `te` + infinitive | verb | core | — | — | — | — | grammar_reference | n/a | n/a | book flags that all but *durven* also exist as ordinary transitive "action" verbs (*Het feest begint*; *hij beloofde het kind een cadeau*) — the `te`-infinitive use is a distinct construction, not a separate lexeme |
| zich vergissen / zich haasten / zich schamen / zich verbazen / zich herinneren | inherently reflexive verbs | verb | core | — | — | — | — | grammar_reference | n/a | n/a | book's own closed list of verbs that are *always* reflexive, contrasted with optionally-reflexive verbs like *zich wassen* (also plain-transitive *iets wassen*) |
| beroepsziekte / stationsstraat / tandartsstoel | "occupational disease" / "station street" / "dentist's chair" | noun (compound) | technical | — | — | — | — | grammar_reference | n/a | n/a | worked examples for the linking-*s* spelling rule (see Grammar Points, Compound-linking spelling) |
| kop koffie / kopje thee | "a cup of coffee" / "a little cup of tea" | noun phrase | colloquial | — | — | — | — | grammar_reference | n/a | n/a | book notes that café/social usage of bare *"een koffie"* is shorthand for *een kopje/kop koffie* — a register note on ellipsis, not a distinct lexeme |
| komen (kwam/kwamen, is gekomen) | "to come" | verb (irregular, high-frequency) | core | — | — | — | — | grammar_reference | n/a | n/a | one of the ~90 irregular-verb principal-part sets tabulated in the book's closing appendix (pp. 202–206); *hebben*-vs-*zijn* auxiliary is marked per verb throughout that list |
| zijn (was/waren, is geweest) | "to be" | verb (irregular, high-frequency) | core | — | — | — | — | grammar_reference | n/a | n/a | see note above |
| hebben (had/hadden, heeft gehad) | "to have" | verb (irregular, high-frequency) | core | — | — | — | — | grammar_reference | n/a | n/a | see note above |
| gaan (ging/gingen, is gegaan) | "to go" | verb (irregular, high-frequency) | core | — | — | — | — | grammar_reference | n/a | n/a | see note above; doubles as the future-marking auxiliary (*gaan* + infinitive) |
| doen (deed/deden, heeft gedaan) | "to do" | verb (irregular, high-frequency) | core | — | — | — | — | grammar_reference | n/a | n/a | see note above |
| kunnen/mogen/moeten/willen/zullen (modal principal parts: kon/mocht/moest/wilde-wou/zou) | modal-verb past-tense forms | verb (irregular) | core | — | — | — | — | grammar_reference | n/a | n/a | full modal paradigm drilled across §6.3; *willen*'s colloquial past *wou* (alongside formal *wilde*) is the one modal past form the book itself flags as register-variable |
| eten/geven/lezen/schrijven/drinken/lopen/liggen/zitten/vinden/spreken/nemen/kopen/vragen/zien/weten/staan/slapen/helpen/houden | a working set of very-high-frequency irregular verbs | verb (irregular) | core | — | — | — | — | grammar_reference | n/a | n/a | drawn from the book's own "learn these by heart first" star-marked subset (pp. 202–206) of its ~140-entry irregular-verb list; principal parts given in Grammar Points below rather than repeated per-row |

## Grammar points

### Part A — Word classes

#### 1. Question words (Ch. 1)
A full interrogative-word inventory, each with its own syntactic quirks: *wie* (people) and *wat*
(things/animals) both optionally take *er* immediately after the finite verb when they are the
clause's subject (*Wie is er aan de beurt?*), except *er* is **blocked** after copular *zijn/worden*
(*Wie is dat?*, never *Wie is er dat?*) and is optional (not required) when the clause already has
*daar/hier*. Neither *wie* nor *wat* can follow a preposition directly — Dutch instead fronts
*waar* + preposition or splits it as *waar... + preposition* at clause end (*Waarin/Waar...in*,
*Waarmee/Waar...mee*, *Waartoe/Waar...toe* — note the irregular linking consonant in the last two).
*Waar* itself is ambiguous between place and "thing" senses with certain verbs (*Waar wacht je?* =
place; *Waar wacht je op?* = the thing waited for) — the book drills this as a genuine
comprehension trap. *Wanneer* covers both temporal ("when") and conditional ("under what
circumstance") questions, with the answering *als*-clause always verb-final. *Hoe* covers manner
and (with an adjective) degree/quantity (*hoe laat, hoe oud, hoe vaak*). *Welk(e)* selects among a
known set and agrees like an adjective (*welke* before de-words/plurals, *welk* before het-words).
*Waarom* elicits an *omdat*-clause reason. *Wat voor (een)* asks about *kind/sort*, with *een*
usable only when the noun is countable.

#### 2. Nouns (Ch. 2) — de/het assignment, redundant plural coverage skipped
Beyond the plural-formation material already covered by `established/001` (skipped here as
redundant, see the header note), this chapter adds explicit **de/het assignment heuristics** not
found in `001`: person names and most animal names are *de*-words; nouns ending in *-ing* are
*de*-words; diminutives are always *het*-words; and — the one genuinely new generalization —
language/city/country names are *het*-words but are used **without** an article in ordinary
reference (*Nederland*, *het Engels*) and take the article only in marked/special constructions
(*het Nederland van de 17e eeuw* "the Netherlands of the 17th century"). Proper names of people take
no article at all.

#### 3. Articles (Ch. 3)
*De/het* mark a definite, already-identified referent; both collapse to *de* in the plural
regardless of gender. The indefinite article *een* marks a not-yet-identified singular referent;
plural indefinites and non-countable/mass singular nouns (*thee, koffie, water*) take **no**
article at all — there is no Dutch equivalent of "some." A distinct rule (§3.4) governs sentences
that front an **indefinite subject** with *er*: *Er zit een kat in de tuin* vs. *Een kat vangt
vogels* — the *er*-fronted version narrates a specific occurrence, the bare-indefinite-subject
version states a generic property true of the whole class. This is presented as a genuine
minimal-pair distinction, not free variation.

#### 4. Adjectives and adverbs (Ch. 4)
The core *-e* inflection rule ("buiging") is stated as three cascading yes/no questions: is the
noun plural (always +*e*)? Does a determiner like *die/dit/mijn* precede a singular noun (always
+*e*)? Is the article *een* or none, and is the noun a de-word (+*e*) or het-word (no *-e*, e.g. *een
nieuw boek*)? Adjectives ending in a vowel or in *-en* never take *-e* regardless (*prima
resultaten*, *het open raam*). Distinct sub-rules apply to: (a) predicative adjectives after
*zijn/worden*, which never inflect; (b) exclamations with bare *Wat + adjective!* (no *-e*) vs. *Wat
een + adjective-e + noun!*; (c) **material adjectives** derived from a substance noun — a Dutch-
origin material takes *-en* (*goud → gouden ring*), an "international" borrowed material noun is used
unchanged as the adjective (*plastic tas*), and material adjectives never inflect further, with the
one flagged exception that *rubber* has fully naturalized enough to also license the native
*-en* pattern (*rubberen*); (d) **past/present participles used adjectively** follow the ordinary
*-e* rule when they end in *-d/-t* (*de gerepareerde stofzuiger*) but never inflect when they end in
*-en* (*het gebakken ei*); (e) **substantivized adjectives** (an adjective standing in for an omitted
noun, e.g. *een dove* "a deaf person") take *-n* when the omitted referent is a plural of persons,
but no *-n* when it's things. Comparison: comparative is stem+*-er* (dan for the standard of
comparison), with stems already ending in *-r* taking *-der* instead (*duur → duurder*);
superlative is *de/het* + stem+*-st(e)*. Four suppletive comparison triples are flagged as
must-memorize: *goed/beter/best*, *graag/liever/liefst*, *veel/meer/meest*,
*weinig/minder/minst*. An *aller-* prefix intensifies a superlative into an absolute/elative
sense (*de allermooiste* "the most beautiful of all," vs. *de mooiste ter wereld* "the most
beautiful in the world" for an explicitly bounded comparison set).

#### 5. Negation (Ch. 5)
*Geen* negates an indefinite noun phrase that would otherwise take *een* or no article; *niet*
negates everything else (a finite verb, an adjective/adverb, a prepositional phrase, or — with
contrastive stress — any specific constituent). Placement rules for *niet* are given per
constituent type: before a clause-final verb cluster; before the adjective/adverb/PP it scopes
over; and, in a subordinate clause, before the verb rather than at the very end. *Niets, niemand,
nergens, nooit* are presented as the lexicalized negations of *iets, iemand, ergens, ooit*
respectively, with explicit converse pairs (*niets↔alles, niemand↔iedereen, nergens↔overal,
nooit↔altijd*). *Nauwelijks* ("hardly") is treated as a near-negator glossable as *bijna
niet/niets/niemand/nergens/nooit* depending on what it modifies — genuinely new comparative-negation
vocabulary not covered elsewhere in this project's Dutch material. A separate discourse-particle
cluster (*nog niet/geen* "not yet," *niet meer/geen ... meer* "no longer," *wel* as a bare
polarity-reversing particle in short answers) rounds out the "and more" subsection.

#### 6. Verbs (Ch. 6) — the largest chapter
Covers, in order: (a) the four principal verb forms (infinitive, present-tense finite forms,
participle, present participle) and the regular/irregular split; (b) the **imperative**, whose
bare form equals the verb stem, with *jij* (never *je*) or polite *u* optionally added as an overt
subject, and a written-register plural imperative in stem+*-t*; the book gives a genuinely useful
pragmatic gloss on imperative particles — bare *kom* reads as strict/commanding (used with children
or animals), *kom maar* signals the action is being permitted for the addressee's benefit, *kom
eens* signals the speaker wants it, and *kom toch* signals impatience; the bare infinitive is also
used as a command register, typically toward children, pets, or in police/official instructions;
(c) **auxiliary/modal verbs**: *hebben* vs. *zijn* as perfect-tense auxiliaries is governed partly
by a closed list of *zijn*-verbs to memorize (*beginnen, blijven, gaan, gebeuren, groeien, komen,
slagen, vallen, verdwijnen, worden, zijn*) and partly by an **action-vs-directed-motion** contrast for
verbs of motion (*wandelen, fietsen, vliegen, lopen, rijden, varen, reizen, rennen*): plain durative
motion takes *hebben* (*Ik heb gisteren gefietst* — just cycled around), but motion construed with a
goal/direction (*naar, via, langs* + destination) takes *zijn* (*Ik ben naar Delft gefietst*); (d)
the five core modals *moeten/kunnen/willen/mogen/zullen* with their distinct meanings (obligation,
possibility, desire, permission, promise-or-proposal) and the idiomatic drop of a redundant
*gaan/hebben* infinitive after them (*Ik moet naar school [gaan]*) which the book notes sounds
"odd" to Dutch ears if spelled out; *hoeven* is the negative-polarity-only counterpart of *moeten*,
requiring an existing negator in the clause and taking *te* before its infinitival complement,
unlike the other modals; (e) *gaan* as future auxiliary (action not yet begun) and *laten* in two
senses — causative delegation ("have X done") and, fronted, an insistent proposal-marker contrasted
explicitly with a *zullen*-question-proposal; (f) *beginnen/beloven/durven/proberen/weigeren* +
*te*-infinitive, all of which double as plain transitive "action" verbs outside this construction;
(g) the **posture-verb progressive** (*zitten/staan/liggen/lopen/hangen* + *te* + infinitive),
contrasted with the plainer *aan het ... zijn* progressive as adding physical-stance information the
latter lacks; (h) **reflexive verbs**, split into an always-reflexive closed set (*zich haasten,
zich schamen, zich vergissen, zich verbazen, zich herinneren*) and optionally-reflexive verbs whose
reflexive and plain-transitive readings differ in meaning (*zich wassen* "wash oneself" vs. *iets
wassen* "wash something"), with *zelf* addable for emphasis (*mezelf, jezelf, zichzelf*); (i)
**separable verbs** (*scheidbare werkwoorden*): separability is predictable from stress — first-
syllable stress usually separable (*'aankomen*), stress on the verb itself usually inseparable
(*onder'zoeken*) — with the separable particle moving to clause-final position in simple present/
past tense, the *-ge-* infix landing between particle and verb stem in the participle, and *te*
landing in the same medial slot for modal+separable-verb combinations (*Hij probeerde het gordijn
op te hangen*).

#### 7. Pronouns (Ch. 7)
Full paradigms for subject (*ik/jij-je-u/hij-zij-ze-het/wij-we/jullie/zij-ze*), object
(*mij-me/jou-je-u/hem-haar-het/ons/jullie/hun-hen-ze*), and possessive
(*mijn/jouw-je-uw/zijn-haar-zijn/ons-onze/jullie/hun*) pronouns, each with the same
stressed-vs-unstressed allomorphy (*jij* vs. *je*, etc.) and the same *jij/je*-vs-*u* social-distance
split noted under Vocabulary. Gender assignment for third-person pronouns follows natural gender for
people and, per the dictionary's own *m/v/o* marking, grammatical gender for de-words standing for
things (masculine de-words → *hij*; feminine de-words → *zij/ze*; het-words → *het*), with weather
verbs taking obligatory dummy *het* as subject. The *hem/haar/het* vs. *hen/hun/ze* split for
personal objects, and the mandatory *er* + preposition substitution for non-personal objects after a
preposition, are covered in Vocabulary above. Demonstratives (*die/dat/deze/dit*) split along the
same de-word/het-word axis as articles, with *deze/dit* for near-deictic reference and *die/dat* for
far-deictic or contrastive reference, and can substitute for personal pronouns with contrastive
force. *Zo'n* (singular countable) vs. *zulk(e)* (plural or mass) is a genuinely distinct
determiner pair the book introduces from scratch (not covered in 001–003). Indefinite pronouns
*iets/niets/iemand/niemand/ergens/nergens/ooit/nooit/iedereen/alles* form a tight paired system
(positive/negative) with the *voorzetsel + alles/iets/niets = overal/ergens/nergens + voorzetsel*
substitution rule layered on top. *Elk(e)/ieder(e)* (singular), *alle* (plural), and *al de/al het*
(mass or "all of a specified set") are kept grammatically distinct, as are *iedereen* (person,
singular verb agreement), *allemaal* (predicate-position "altogether"), *allen* (personless plural
of *alle*, persons only), and *alles* (things, singular verb agreement). *Men/je/ze* form a
formality-graded triple for impersonal "one/people in general," with *men* explicitly marked
formal register. Reflexive pronouns (*me/je/zich/ons*) follow the same person-based paradigm as
possessives. Relative pronouns *die/dat* pick the de-word/het-word/plural/personal-name split
already familiar from the demonstrative system, *wat* refers back to an entire preceding clause
rather than a single noun, and *waar* (+ preposition) is required wherever a preposition would
otherwise need to attach to *die/dat* referring to a place or thing (never to a person).

#### 8. Numerals (Ch. 8)
Cardinal numbers 13–99 name the last digit first (*eenentwintig* = "one-and-twenty"); from 100 up,
the largest unit is named first, with an optional *en* insertable only in the 101–112 (and
1001–1012) range. Numbers 1100–9999 have two co-existing pronunciations (*elfhonderd* vs. *duizend
honderd*). Year numbers group as two-plus-two digits with *honderd* optionally elidable
(*negentien(honderd) drieënnegentig*); a year with a medial zero instead names the full thousands
figure. Currency amounts state euros then cents, dropping the word *euro* itself when cents follow
(*drie vijfentwintig* = €3,25); a round amount keeps *euro*. Fractions state numerator then
denominator, with the denominator grammatically an ordinal number; ½ and 1½ are lexically special
(*een half/halve*, *anderhalf*), and ¼/¾ have a colloquial *kwart* alternative alongside the regular
ordinal-based form. Decimals name the whole-number part as a cardinal and the decimal part as an
ordinal, with a leading zero never pronounced. Numerals pluralize with *-en* (*met z'n vijven*
"the five of us," *honderden mensen*) and take diminutives with their own idiomatic senses —
*nulletje, zesje, tientje* — captured in Vocabulary above. Ordinal numbers are formed with *-de*
(most cases) or *-ste* (numbers ending in a sibilant-cluster/most tens, and all numbers ≥20), with
irregular *eerste, derde*; an "indefinite ordinal" set (*middelste, laatste, hoeveelste, zoveelste*)
covers "middle-most," "last," "which-numbered" (for asking a date), and "umpteenth."

#### 9. Prepositions (Ch. 9)
Presented as three closed sets by semantic domain — place (*achter, bij, boven, in, naast, onder,
op, tussen, voor*), direction (*door, langs, naar, over, uit, via*), and time (*in, om, na, op,
sinds, tijdens, van...tot, voor*) — plus a fixed time-expression convention (year/month take *in*,
day takes *op*, clock time takes *om*). A large closed list of **verb + fixed preposition**
collocations (*bellen met, denken aan, dromen over, houden van, kijken naar, krijgen van, luisteren
naar, praten met/tegen/over, vragen aan, wachten op*) is explicitly flagged as vocabulary to
memorize as inseparable units, extended to a parallel list of **noun/adjective + fixed
preposition** collocations (*last hebben van, een hekel hebben aan, zin hebben in, bang zijn voor,
blij zijn met*) — captured under Vocabulary above. Preposition-stranding with question words and
pronouns for non-personal referents is systematized as *waar+preposition* (interrogative) /
*er+preposition* (pronominal), covered under Pronouns and Question Words above; personal referents
instead keep the preposition with *wie* or the ordinary personal pronoun.

### Part B — Talking about the past and future

#### Tense choice in narrative (not covered by 001–003)
The book's most distinctive contribution beyond bare tense *formation* is an explicit discourse-
level account of tense *choice* when narrating: describing **past situations, actions, and habits**
uses either the *onvoltooid verleden tijd* (simple past) for description/habit/sequential action,
or the *voltooid tegenwoordige tijd* (present perfect) for a single completed occurrence or an
"already accomplished" situation — the two are not interchangeable registers of the same meaning but
mark **discourse function** (ongoing background vs. punctual foregrounded event). A further layer,
the *voltooid verleden tijd* (past perfect), marks an event understood as prior to a past reference
point already established by a surrounding simple-past or present-perfect clause — canonically after
*nadat, voordat, toen* and in indirect-speech *dat*-clauses reporting what someone had said about an
even earlier past. For the future, plain present tense (with a time adverbial) and *gaan* +
infinitive are treated as near-equivalent defaults, while *zullen* + infinitive is reserved for
utterances that specifically carry the force of a promise/arrangement or, in question form, a
proposal — *a promise/proposal is only made in the first person* (*ik*/*wij*), never on someone
else's behalf.

### Part C — Clause structure

#### Main-clause word order
Dutch main clauses are verb-second: whatever occupies the first slot (subject, or any fronted
adverbial/object), the finite verb occupies the second slot, with the subject sliding to third
position (**inversion**) whenever something other than the subject is fronted. Beyond the finite
verb's fixed second slot, remaining constituents order loosely by information type: a more general
time expression precedes a more precise one (*morgen om 4 uur*, not the reverse); manner adverbials
follow time adverbials and precede a with-preposition phrase describing manner; short adverbs of
time/immediacy (*gisteren, straks, nu*) cluster close to the finite verb while longer prepositional
phrases drift toward clause end. Clause-final position is reserved for: any non-finite verb(s)
(participle/infinitive), a separable verb's stranded particle, and the negator *niet* in its
verb-scoping use. A noun-phrase direct object precedes all of these and precedes an indirect object
introduced by a preposition (though the indirect object can also precede it); a **pronominal**
(rather than full-NP) direct or indirect object instead cliffhangs immediately after the finite
verb, with the two orders (pronoun-indirect-then-pronoun-direct vs. the reverse with a preposition)
both grammatical depending on whether the indirect object keeps its preposition. Reflexive pronouns
follow the same "immediately after the finite verb / immediately after the subject under inversion"
placement rule as pronominal objects generally.

#### Subordinate clauses
Every subordinate clause is introduced by an overt linking word and pushes its finite verb (and any
other verb forms) to clause-final position, with the subject sitting immediately after the linking
word. *Omdat* introduces a reason-clause; its near-synonym *want* is explicitly **not** a subordinator
— a *want*-clause is syntactically a second main clause (verb stays second, not final), a genuine
syntax/semantics mismatch the book flags directly. *Als* introduces a conditional (and, distinctly
from *wanneer*, cannot introduce a plain temporal question — *wanneer* covers both "when" and "under
what condition," but a following subordinate clause with *als* is specifically conditional). *Dat*
introduces indirect-speech/perception complement clauses and carries no lexical meaning of its own;
it marks that what follows is being reported rather than asserted directly by the current speaker.
*Of* introduces indirect yes/no-questions and clauses of uncertainty, again with no inherent
meaning of its own — but critically, an indirect question containing its own question word
(*hoe, waar, wanneer, wie, welke, wat*) uses **no** subordinator at all; *of* appears only when the
original question had no question word. The *dat*-vs-*of* choice tracks a genuine
epistemic distinction the book states explicitly: *dat* when the reported content is treated as
certain/known, *of* when it is being treated as still open/uncertain. Relative (*bijvoeglijke
bijzinnen*) clauses attach to a preceding noun with *die* (de-word/plural/personal antecedent),
*dat* (het-word antecedent), or *waar* (+ preposition, for place or for a stranded preposition on a
thing-antecedent) — paralleling the demonstrative-pronoun gender split throughout the rest of the
book.

### Appendix — Spelling rules not previously captured

#### *ei* vs. *ij*
Both spellings are pronounced identically in nearly all positions (near-unpredictable spelling,
"check the dictionary" is the book's own advice), but several sub-patterns are given: word-final
noun-forming *-ij* is consistently a de-word suffix (*kledij, aanstellerij, razernij*); all personal
pronouns spell this vowel *-ij-* (*jij, gij, zij, hij, wij, mij, mijn, zijn*); word-final *-ei* is
fixed in the suffixes *-heid, -leí, -teit* (all yielding de-words); and irregular verbs whose past
tense has the vowel pattern *-ee-/-e-* (*begreep/begrepen, kreeg/kregen*) have an infinitive spelled
with *-ij-* (*begrijpen, krijgen*) — with the caveat that some *ij*-spelled verbs are nonetheless
weak/regular in the past tense (*hijgen → hijgde*, not a strong-verb pattern).

#### *ou(w)* vs. *au(w)*
Similarly near-unpredictable; *ou* is by far the more common spelling for the /au/ sound. One
reliable sub-rule: a word-final /au/ is followed by a written *-w* except after *kou, nou, zou,
hou(d), wou, jou* — a small closed exception list.

#### Compound-linking spelling: *-e-* vs. *-en-*
When two nouns combine into a compound and an interconnecting schwa-vowel is pronounced, the
spelling depends on the **first** element's own plural: if the first noun's own plural is formed
with *-en*, write *-en-* in the compound link (*hond → honden* ⟹ *hondenhok*); if the first noun's
plural can be either *-s* or *-n* (*gemeente, keuzeprogramma*), or if it has no *-n*-type plural at
all (*garage, horloge* — plurals in *-s* only, or no plural), write plain *-e-* (*garagedeur,
gemeenteraad*). A small named-entity exception set (*koninginnedag*, *zonneschijn*) reflects there
being only one queen/one sun referred to, and a plant-name exception set (*paardebloem,
kattekruid*) is flagged by the book itself as likely to be regularized away in future spelling
reform.

#### Compound-linking spelling: *-s-* vs. *-ss-* (and other sibilant spellings)
When a compound's first element does not itself end in *-s* but an audible linking /s/ is heard
before a second element that does **not** begin with a sibilant, write a single *-s-*
(*bakkersvrouw, moederskind, liefdesgedicht*). When the first element ends in *-s* **and** the
second begins with *s*, write *-ss-* (*tandartsstoel, jongensschool*). When the first element does
not end in *-s* but the second begins with a sibilant (*s, z, ch, j*), the linking morpheme is still
present but its spelling is idiosyncratic per compound — sometimes *-s-*, sometimes *-ss-*,
sometimes *-sz-, -sch-,* or *-sj-* (*tuinslang, Stationsstraat, levensstijl, beroepsziekte,
scheepsjournaal, stationschef*). The book's own diagnostic for whether the linking-s morpheme is
present at all: substitute a related compound whose second element does *not* start with a
sibilant and check whether an /s/ is heard before it (*stationsplein* confirms the linking -s- that
carries through to *Stationsstraat*/*stationschef*).

### Appendix — Irregular verb list (pp. 202–206)
A ~140-entry reference table of principal parts (infinitive, simple-past enkelvoud/meervoud where
irregular, past participle with its *hebben*/*zijn* auxiliary marked), explicitly star-marking a
~90-verb "learn these first" high-frequency subset. Structurally this is a lexicon appendix rather
than a grammar point, and per copyright discipline is not reproduced in bulk here; the ~20
highest-frequency starred verbs are captured individually in the Vocabulary table above with a
pointer back to this appendix rather than duplicated in full. Two cross-cutting patterns worth
noting for later mechanics analysis: (1) a meaningful subset of motion/change verbs is marked with
**both** auxiliaries depending on the action-vs.-directed-motion distinction already covered under
Ch. 6 (*breken, drijven, dringen, duiken, glijden, klimmen, schuiven, springen, stuiven, treden,
trekken, varen, vliegen, zwemmen*, among others) — i.e., this auxiliary-selection ambiguity is
lexically pervasive, not confined to the handful of verbs drilled in the chapter itself; (2) modal
*willen*'s past tense is the one form in the entire appendix given two competing variants,
*wilde* and colloquial *wou* — the appendix's only explicit register-variant flag in an otherwise
uniform reference list.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. The irregular-verb
appendix and the plural-noun appendix in particular were treated as reference lexicons to describe
and sample from, not to transcribe.
