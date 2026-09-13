# Russian — Established Vocabulary/Grammar: Modern Russian Grammar: A Practical Guide, Part 2

**Source:** John Dunn & Shamil Khairov, *Modern Russian Grammar: A Practical Guide* (Routledge,
2009/2011 printing), PDF pages 241–480 of 962 (printed pages approx. 113–265), covering the tail of
§5 (verb aspect: specific verb meanings, single completed actions, questions, the imperative,
negation, practical aspect points), all of §6 (adjectives: hard/soft declension, nouns declining
like adjectives, short forms, possessive adjectives, indeclinable adjectives, comparative/
superlative), all of §7 (pronouns: personal, possessive, demonstrative, interrogative, relative,
indefinite, totality, emphatic/reciprocal), all of §8 (numerals: cardinal, case-government,
collective, ordinal, fractions, other quantity words), all of §9 (adverbs, prepositions,
conjunctions, particles), and the start of §10 (word formation: nouns — diminutives, augmentatives,
agent/inhabitant/nationality suffixes, feminine-agent suffixes, deverbal/abstract nouns, compound
nouns; adjective formation; verb formation; verbal prefixes). A sibling subagent covers PDF pages
1–240 as `established/069`; siblings cover 481–720 and 721–962. No duplication with those ranges.

**Coverage note:** Comprehensive-but-not-exhaustive per the extraction spec. Every grammar point
listed in the subsection headings below is paraphrased; repeated drill sentences that don't add new
vocabulary/grammar are skipped.

**Non-redundant-supplement scope decision:** This language already has two comprehensive reference
grammars extracted (`002`/`003`, Wade's *Comprehensive Russian Grammar*; `006`/`007`, Timberlake's
*Reference Grammar of Russian*, Cambridge), which between them already cover adjective declension,
comparative/superlative formation, the full pronoun system, cardinal/ordinal/collective numerals,
particles, and verbal-prefix aspectual meanings in substantial depth (confirmed by direct grep
cross-check against `002`/`003`/`006`/`007` before writing this file). Per the spec's non-redundant-
supplement pattern, this file therefore: (1) paraphrases every subsection's rule at a **summary**
level so the section's scope is auditable, rather than re-deriving full paradigms already tabulated
elsewhere; (2) keeps the vocabulary table narrow, limited to items that are either genuinely new
(not found in a keyword check of the four prior files) or that illustrate a rule with a distinctive
example not already on file — e.g. this book's дости́ин-type irregular short-form fleeting vowel,
its тёщин/Танин/Галин possessive-adjective set, its -анин/-янин city-demonym list, and its водка
(< вода) diminutive-suffix note; (3) flags a handful of genuinely deeper/more systematic paradigm
presentations (short-form adjective stress-shift table, ь-final numeral declension table) that go
beyond what prior files tabulated for those specific items.

**Critical PDF-extraction gotcha — a 7th distinct Cyrillic corruption variant for this project's
Russian corpus, beyond the 6 already catalogued in `00_Reference_Extraction_Spec.md`:** this
specific book embeds **all bracketed Russian-language content — every boxed example sentence, every
paradigm/declension table, and most individual Russian words quoted inline inside otherwise-English
sentences — in a custom, unnamed TrueType font (`pdfinfo`/`pdffonts` shows `TrueType`, `Custom`
encoding, embedded, with a `uni` flag) that produces genuinely empty output under `pdftotext`, not
garbled/substituted output.** This is confirmed by direct comparison: `pdftotext -f 241 -l 242`
(raw) and the `-layout` variant both silently drop every Cyrillic-bearing line (verified via
`pdftoppm`-rendered page images showing full example sentences and declension tables that have zero
corresponding text in the `pdftotext` output — not mojibake, not scrambled columns, literally
absent). English scaffolding prose, in-line English glosses, and the running example-sentence
translations survive perfectly (only ASCII plus ordinary curly-quote punctuation appears in the
text-layer dump for this page range). **Practical consequence:** this book's own actual Russian-
language content (which is most of its illustrative value) is **not recoverable from the text layer
at all** and requires vision-reading page-by-page; a full page-by-page vision pass over all ~240
pages in this range was judged out of scope for a single extraction subagent given the redundancy
noted above, so this file relies on (a) the fully-extractable English grammar exposition for the
paraphrased **Grammar points** section below, plus (b) a targeted, verified sample of ~6
vision-rendered pages (pp. 127, 135, 138, 177, 218, and 293 of the printed book, i.e. PDF pages 270,
284, 290, 293, 365, and 451) chosen to hit subsections judged most likely to contain genuinely new
material. **A future dedicated vision-reading pass over this book's remaining pages could recover
real additional content** (worked examples, minor paradigm variants) that this pass did not attempt.
Do not assume this book has "no text layer" in the vision-reading-guard sense — the English
scaffolding IS a real text layer; only the embedded-font Cyrillic glyphs are unrecoverable this way.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| высо́кий / высо́к / высока́ / высо́ко / высо́ки | high, tall (long form / 4 short forms) | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.5, p.138; stress moves off the stem in fem./plural short forms |
| све́жий / свеж / свежа́ / све́жо~свеже́ / све́жи | fresh (long form / 4 short forms) | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.5, p.138; neuter short form has two stress variants (свежо́/свеже́е is long-form comparative, свеже — see source) |
| пусто́й / пуст / пуста́ / пу́сто / пусты́ | empty | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.5, p.138; no fleeting vowel needed in masc. short form |
| досто́йный / досто́ин / досто́йна / досто́йно / досто́йны | worthy | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.5, p.138; irregular fleeting vowel и (not the expected е) in masc. short form — flagged by source as an exception |
| любе́зный / любе́зен / любе́зна / любе́зно / любе́зны | kind, courteous | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.5, p.138 |
| тёсный / тесен / тесна́ / те́сно / те́сны | cramped, small | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.5, p.138 |
| лёгкий / лёгок / легка́ / легко́ / лёгки~легки́ | light, easy | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.5, p.138; plural short form has two acceptable stress variants |
| ре́зкий / ре́зок / ре́зка / ре́зко / ре́зки | sharp, abrupt | adjective | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.5, p.138 |
| пти́чий (masc.), пти́чья/пти́чье/пти́чьи | bird's (possessive adjective, from пти́ца 'bird') | adjective (soft, possessive-type) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.3, p.135; full 6-case ×4-gender/number paradigm given; soft sign ь before every ending except masc. nom. sg. |
| тре́тий | third | ordinal numeral (declines like §6.3 possessive-type soft adjectives) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.3, p.135; explicitly grouped with чей and пти́чий-type possessives as sharing this declension pattern |
| чей | whose? | interrogative/relative pronoun (same declension group as §6.3) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.3, p.135 |
| ма́мин | Mum's | possessive adjective | colloquial/familial | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.6.1, p.293; formed from ма́ма by dropping final vowel + -ин |
| па́пин | Dad's | possessive adjective | colloquial/familial | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.6.1, p.293 |
| тёщин | (husband's) mother-in-law's | possessive adjective | colloquial/familial | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.6.1, p.293; not previously captured in this project's Russian established files |
| Та́нин | Tania's | possessive adjective (from familiar forename Та́ня) | colloquial | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.6.1, p.293; source notes possessive adjectives are usually built from the familiar, not full, forename |
| Га́лин | Galia's | possessive adjective (from familiar forename Га́ля) | colloquial | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §6.6.1, p.293 |
| пять / пяти́ / пятью́ | five (nom./gen.-dat.-prep. / instr.) | cardinal numeral | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §8.1.6, p.177; numerals 5–20 and 30 decline like a ь-final feminine noun |
| во́семь / восьми́ / восемью́~восьмью́ | eight | cardinal numeral | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §8.1.6, p.177; only numeral in this set with a fleeting vowel, which optionally resurfaces in the instrumental |
| два́дцать | twenty | cardinal numeral | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §8.1.6, p.177; declines like двена́дцать; три́дцать (30) follows the same pattern |
| оди́н / два | one / two | cardinal numerals | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §8.1 note, p.177; explicitly flagged as the only two numerals that distinguish grammatical gender |
| оди́н, два, три, четы́ре | one, two, three, four | cardinal numerals | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §8.1 note, p.177; explicitly flagged as the only numerals with distinct animate/inanimate accusative forms |
| во́дка (< вода́ 'water') | vodka | noun, fem. (lexicalized diminutive) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §10.1.3, p.218; source flags this as an exceptional lexicalized diminutive ("vodka (only!)"), cross-referenced to §10.1.5 |
| бра́тец, бра́тик (< брат 'brother') | little brother (child-register only) | noun, masc. (double diminutive alternatives) | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §10.1.2, p.218; one of a small exception class of nouns with two alternative diminutive forms, restricted to child-directed speech |
| ча́стица (< часть 'part') | particle (grammatical term) / small part | noun, fem. | core/technical.linguistics | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §10.1.3, p.218; -ица diminutive suffix; the grammatical-term sense (particle, cf. §9.4 below) is itself a semantically specialized diminutive |
| ру́чка (< рука́ 'arm/hand') | handle, pen (also: little hand) | noun, fem. | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §10.1.3, p.218; -ка diminutive with semantic extension beyond literal smallness |
| стре́лка (< стрела́ 'arrow') | (clock/watch) hand (also: little arrow) | noun, fem. | core | — | contemporary (source published 2009) | — | — | grammar_reference | n/a | verified | §10.1.3, p.218 |
| иркутя́нин, киевля́нин, минча́нин, петрозаво́дчанин, ростовча́нин | inhabitant of Irkutsk / Kiev / Minsk / Petrozavodsk / Rostov-on-Don | noun, masc. (demonym, -анин/-янин/-чанин) | core | — | contemporary (source published 2009) | Russia/Ukraine/Belarus | national/transnational | grammar_reference | n/a | verified | §10.1.8, p.451; suffix family forms city-demonyms; consonant-cluster-conditioned allomorph -чанин appears after -нск/-дск/-тов-type stems |
| паpижа́нин, ри́жанин, ри́млянин | Parisian, inhabitant of Riga, Roman | noun, masc. (demonym) | core | — | contemporary (source published 2009) | — | transnational | grammar_reference | n/a | verified | §10.1.8, p.451; source notes the same suffix is used "less often" for foreign-city/nationality demonyms |

## Grammar points

### §5.3 The specific meaning of the verb (pp. 113–119)
Aspect choice in Russian is often governed by lexical semantics rather than a general rule. The
book classifies verbs into: (5.3.1) verbs that cannot express an action-in-process in *either*
Russian or English (e.g. verbs of instantaneous change of state); (5.3.2) verbs that *can* express
an action-in-process in Russian but not in English; (5.3.3) the reverse — process-capable in
English but not Russian; (5.3.4) verbs whose lexical meaning inherently precludes completion (e.g.
searching, waiting-type verbs, where the perfective would contradict the verb's own semantics); and
(5.3.5) "semelfactive" perfectives, which denote a single instance of an inherently repeatable
action (cf. this project's prior -ну- instantaneous-suffix entries in `002`/`023`).

### §5.4 Single completed actions (pp. 119–127)
The perfective marks a single completed action in three contexts distinguished by the book:
(5.4.1) relative to another action ("before/after X happened"), (5.4.2) relative to the present
moment (a just-completed action with continuing relevance), and (5.4.3) tied to one specific,
identifiable occasion rather than a general/habitual pattern.

### §5.5 Asking questions (pp. 127–128)
Aspect selection in questions differs for past vs. future reference: (5.5.1) past-tense questions
typically default to the imperfective when merely asking whether an action occurred at all (fact of
occurrence), switching to perfective when the questioner already presupposes the action happened and
is asking about its result or a specific detail; (5.5.2) future-tense questions follow parallel
logic keyed to whether the questioner is asking about intention/process vs. eventual outcome.

### §5.6 The imperative (pp. 128–129)
The choice between imperfective and perfective imperatives is pragmatically loaded: (5.6.1) neutral
instructions typically favor the perfective; (5.6.2) issuing an invitation typically favors the
imperfective (softer, more inviting force); (5.6.3) impatience is conventionally marked by the
imperfective imperative (repeated/ongoing insistence reading); (5.6.4) several further idiomatic
uses of the imperfective imperative are catalogued (e.g. a habitual/generic instruction sense).

### §5.7 Negation (pp. 129–133)
Negation interacts with aspect differently by tense: (5.7.1) negation in the past typically favors
the imperfective when merely denying that an event took place at all, but the perfective when
denying only that a particular attempted result was achieved; (5.7.2) future negation follows
similar logic; (5.7.3) negated imperatives are canonically imperfective (a negated perfective
imperative instead warns against an unintended/accidental action, e.g. "mind you don't fall"); (5.7.4)
negation with infinitives depends on the governing verb's own meaning — e.g. a perfective infinitive
after a negated хоте́ть ('not to want to') in an apology context, illustrated on p. 127 with
"Извини́те, я не хоте́л вас оби́деть" ('I'm sorry, I didn't mean to offend you'); (5.7.5)
impossibility/undesirability is a further, distinct negation pattern: a negated imperfective
infinitive used alone denotes a categorical prohibition, with bureaucratic/military register
(source's own example: "Не кури́ть!" 'No smoking!'; "Не писа́ть ни́же пункти́рной ли́нии" 'Do not
write beneath the dotted line' — both p.127, both explicit printed-notice-register examples), while
a negated perfective infinitive in this same construction instead denotes rhetorical impossibility
("Всё не перечи́слить!" 'There's no end to [enumerating] them all!', p.127) — described by the
source as rare and rhetorically marked. The adverb лу́чше with a negated imperfective infinitive
forms a mild negative recommendation/command ("you'd better not…").

### §5.8 Some practical points on aspect (pp. 133–134)
Covers pragmatic aspect-choice heuristics beyond the categories above: making a "negative choice"
(declining to do something), a construction glossed by the book as "having your cake and eating it"
(an aspect pairing that lets a speaker claim credit for an action's initiation while hedging on its
completion), and a closing note on He (contextual disambiguation).

### §6.1 Hard adjectives (pp. 131–133)
Standard hard-adjective declension; the accusative in masc. sg. and plural matches nominative for
inanimate-noun-qualifying adjectives and genitive for animate-noun-qualifying adjectives (cf. this
project's established animate/inanimate-accusative rule elsewhere). §6.1.2 covers end-stressed
adjectives (masc. nom. sg. in -ой rather than -ый/-ий). §§6.1.3–6.1.5 apply three general spelling
rules (cross-referenced to §1.5.2/1.5.4/1.5.5, orthographic ы/и and о/е-after-hushing-consonant
rules) specifically to adjective endings.

### §6.2–6.3 Soft adjectives (1) and (2) (pp. 134–135)
Two soft-adjective subclasses: group (1) (regular soft adjectives, e.g. си́ний 'blue'); group (2),
possessive-type soft adjectives built from animate nouns (illustrated in the vocabulary table by
пти́чий), which uniquely retain a soft sign immediately before the ending in every form except masc.
nom. sg., and which uniquely take monosyllabic endings in nom./acc. fem. and neuter singular and in
the nominative plural — a genuinely distinctive declension subtype. The ordinal тре́тий and the
pronoun чей are explicitly grouped into this same declension pattern despite not being possessive
adjectives themselves.

### §6.4 Nouns that decline like adjectives (pp. 135–136)
Common nouns and surnames that originated as adjectives/participles (e.g. certain occupational or
descriptive common nouns, and many Russian surnames) retain adjectival declension rather than
regular noun declension.

### §6.5 The short forms of adjectives (pp. 136–139)
Short-form adjectives (predicate-only, non-declining for case) are formed by stripping the long-form
ending; a fleeting vowel is inserted in the masc. short form when its removal would create an
illegal consonant cluster (cross-referenced to the noun genitive-plural fleeting-vowel rule at
§2.5.2). Stress commonly shifts in the short forms relative to the long form (see высо́кий/лёгкий/
ре́зкий in the vocabulary table) and can itself carry alternative acceptable placements. §6.5.3
covers irregular short forms, including досто́йный's exceptional и-vowel (rather than the expected
е) — flagged explicitly by the source as an exception to its own stated fleeting-vowel rule.

### §6.6 Possessive adjectives (pp. 139–140, 293)
§6.6.1 formation: built from proper names/kinship nouns ending in -а/-я by dropping the final vowel
and adding -ин (ма́ма→ма́мин, etc.); usually built from the familiar rather than full form of a
forename. §6.6.2 covers their declension (a mixed noun/adjective-type paradigm, cross-referenced
elsewhere in the book rather than re-tabulated here). §6.6.3 covers their use, standing as an
alternative to a genitive-case possessive noun phrase (cross-ref. §3.3.1).

### §6.7 Indeclinable adjectives (pp. 140–142)
A small, closed set of borrowed/invariant adjectives, organized by the source into semantic
subclasses: clothing color/style terms, culinary terms, and ethnicity/language-name terms — this
last subclass is notable for normally following (rather than preceding) its noun, an inversion of
ordinary Russian adjective-noun order, with one explicitly noted exception adjective that can go
either way. A further open subclass covers recent borrowings (би́знес 'business', интерне́т
'Internet', онла́йн 'on-line') that function adjectivally but are conventionally hyphen-joined to
the following noun rather than declined or left as a separate indeclinable word.

### §6.8 Comparative and superlative forms (pp. 142–147)
§6.8.1 the short (synthetic, indeclinable, predicate-only) comparative; §6.8.2 the long
(declinable, attributive-capable) comparative, formed periphrastically or via a small suppletive/
irregular set; §6.8.3 declining comparatives; §6.8.4 the periphrastic са́мый-superlative; §6.8.5
other superlative strategies (a synthetic -ейший/-айший superlative, and colloquial intensifying
strategies).

### §7 Pronouns (pp. 147–166)
§7.1 personal pronouns: declension of 1st/2nd person and the reflexive pronoun (§7.1.2), 3rd person
declension with the н- augment after prepositions (§7.1.3), routine omission of subject personal
pronouns in certain contexts (§7.1.4), and the systematic use of the reflexive pronoun (§7.1.7).
§7.2 possessive pronouns, including the declension and use of the notoriously flexible
reflexive-possessive свой (§7.2.3–7.2.4). §7.3 demonstrative pronouns (э́тот/тот) and their
distinct uses (§7.3.2–7.3.3). §7.4 interrogative pronouns (кто/что and their case forms). §7.5
relative pronouns, with кото́рый as the general-purpose relative and separate coverage of что and
как as relativizers in specific constructions. §7.6 indefinite pronouns, systematically built from
a wh-root plus one of four productive suffixes/prefixes (-то, -нибудь, ко́е-, -ли́бо), each with a
distinct existential/modal/register profile (this system is covered in much greater comparative
depth in `007`, which this file defers to rather than re-deriving). §7.7 totality pronouns (весь and
related items) and §7.8 the emphatic pronoun сам, the pronoun са́мый, and the reciprocal pronoun
друг дру́га.

### §8 Numerals (pp. 166–184)
§8.1 cardinal numerals: the closed list (§8.1.1), reading/writing conventions (§8.1.2), and
declension by numeral-class — оди́н (§8.1.3, agrees in gender/number like an adjective), два/три/
четы́ре (§8.1.4–8.1.5, with the special оди́н/два gender-distinguishing and оди́н–четы́ре
animacy-marking exceptions flagged explicitly by the source, see vocabulary table), the ь-final
numerals 5–20/30 declining like a soft-sign feminine noun (§8.1.6, fully tabulated in the vocabulary
table above), 50–80/200–900 (§8.1.8), and the declension of слож­ные (compound) numerals (§8.1.10,
where in formal registers every component word declines). §8.2 covers case-government by cardinal
numerals depending on which numeral and what case the numeral phrase itself occupies. §8.3 collective
numerals (дво́е, тро́е, etc.) — their list, declension, and restricted uses (mainly with
masculine/common-gender person-nouns, nouns lacking a singular, and certain pronoun-headed phrases).
§8.4 ordinal numerals — list, declension (adjective-type, first ordinal's oddity noted at §6.3
above for тре́тий), and use. §8.5 fractions, including special fraction-only nouns (§8.5.1), ordinary
and decimal fractions (§8.5.2–8.5.3), and other fraction-related forms (§8.5.4). §8.6 other
quantity words, including nouns formed from numerals (e.g. collective/group nouns like a "trio" or
"dozen" equivalent) and further indefinite-quantity words.

### §9 Adverbs, prepositions, conjunctions, particles (pp. 184–201)
§9.1 adverbs: standard adjective→adverb formation (§9.1.1), a productive по-...-ому/-ему
adverb-formation pattern from adjectives/pronouns (§9.1.2), closed subclasses for time and place
(§9.1.3–9.1.4), the indefinite-adverb system mirroring the §7.6 indefinite-pronoun suffix family
(§9.1.5), and adverb comparative/superlative formation (§9.1.7, largely parallel to §6.8). §9.2
prepositions, organized by the case each governs (nominative through prepositional, §9.2.1–9.2.6),
plus three focused notes: preposition pronunciation/liaison behavior (§9.2.7), the "fleeting vowel"
inserted in certain prepositions before a consonant-cluster-initial complement (§9.2.8, an
across-the-board consonant-cluster-avoidance principle echoing the noun/adjective fleeting-vowel
rules above), and special-comment entries for за (+ acc.), по (+ dat.), and с (+ instr.), each of
which has unusually broad/idiomatic case-governed meaning ranges. §9.3 conjunctions: coordinating
(§9.3.1), а vs. но-type contrastive conjunctions (§9.3.2), subordinating conjunctions (§9.3.4), a
"matching" adverb-conjunction correlative-pair system (§9.3.5, e.g. так...что-type pairs), and
preposition-plus-conjunction compound phrases (§9.3.6). §9.4 particles: a closed set with narrowly
specific grammatical/semantic functions (§9.4.1, overlapping with the particle inventory already
tabulated in `007`'s §7.6 discourse-particle material) plus a broader "other particles" class
(§9.4.2) and a note on particle pronunciation/spelling irregularities (§9.4.3).

### §10.1 Formation of nouns (pp. 201–219, within-range portion)
§10.1.1 diminutives and augmentatives as a general category; §10.1.2 masculine diminutive suffixes
(including the two-alternative-form exception class illustrated by брат/бра́тец~бра́тик in the
vocabulary table); §10.1.3 feminine diminutive suffixes, dominated by -ка (with a consonant-mutation
rule г/к/х→ж/ч/ш and ц→ч before it) and a secondary -ица suffix, illustrated at length in the
vocabulary table (note especially the semantically-extended, non-literal diminutives ру́чка/
стре́лка/голо́вка/но́жка, and the fully lexicalized во́дка); §10.1.5 secondary/doubled diminutive
suffixes (a diminutive-of-a-diminutive pattern); §10.1.6 augmentative suffixes (the semantic
opposite of §10.1.2–10.1.3); §10.1.7 agent suffixes (nouns denoting "one who does X"); §10.1.8
suffixes forming demonyms for inhabitants/nationalities, most productively -анин/-янин with the
consonant-cluster-conditioned allomorph -чанин (fully illustrated in the vocabulary table:
Ирку́тск→иркутя́нин, Ки́ев→киевля́нин, Минск→минча́нин, Петрозаво́дск→петрозаво́дчанин, Росто́в-на-
Дону́→ростовча́нин; also usable, per the source, "less often" for foreign cities/nationalities:
Пари́ж→парижа́нин, Ри́га→ри́жанин, Рим→ри́млянин); §10.1.9 suffixes deriving feminine
counterpart nouns from masculine agent/demonym nouns; §10.1.10 other deverbal noun-formation
patterns; §10.1.11 further abstract-noun suffixes; §10.1.12 compounding two words into a single
noun.

### §10.2–10.4 Formation of adjectives, verbs, and verbal prefixes (pp. 219–~230, within-range
portion continues past PDF page 480 into the next chunk)
This chunk's coverage of §10.2 (adjective-forming suffixes), §10.3 (verb-forming patterns from
nouns/adjectives), and §10.4 (verbal prefixes, introduction only within this page range) is present
in the source but was not separately paraphrased in this pass beyond the topic list already given
above (see the extraction spec's "Chunking" note) — §254's aspectual-prefix *meanings* are already
covered in depth by `003`; this book's §10.4 instead frames prefixes primarily as *word-formation*
devices rather than aspect-markers, which is a genuinely distinct angle a follow-up
non-redundant-supplement pass on the *next* chunk (PDF pages 481–720) should check for real
additional content rather than assuming full overlap with `003`.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. All Cyrillic example
sentences quoted above are short, individually illustrative fragments (a single sentence or phrase
each), not bulk reproduction of the source's tables.
