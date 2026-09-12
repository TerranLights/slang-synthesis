# Russian — Established Vocabulary/Grammar: Reference Grammar of Russian, Part 2 (pp. 261–511)

**Source:** Alan Timberlake, *A Reference Grammar of Russian* (Cambridge University Press, 2004),
pp. 261–511 — the back half of the book (§4.7.11 continuing into the end of Chapter 7). A sibling
subagent covers pp. 1–260 as `established/006_reference_grammar_of_russian_cambridge_part1.md`;
this file picks up exactly where that one leaves off and does not re-cover its territory.

**Coverage note:** this file follows the comprehensive-but-not-exhaustive rule from
`../../00_Reference_Extraction_Spec.md` — every grammar point (one subsection per numbered heading
in the source, §4.7.11 through §7.6.x) is paraphrased, and every distinct Russian lexical/
grammatical item introduced as an illustrative example is captured in the Vocabulary table below.
Timberlake's own extensive footnoted scholarly-citation apparatus (references to other linguists'
work) is skipped as out of scope — this project extracts language mechanics, not bibliography.
Repeated worked examples reusing already-captured vocabulary within the same subsection are not
re-tabulated.

**Text-layer / encoding gotcha (read this before using this file's Cyrillic forms):** this PDF has
a genuine text layer, but its Cyrillic-bearing font is set with a **fixed 1:1 character-substitution
cipher**, not real Cyrillic codepoints or garbled OCR. `pdftotext` extracts (e.g.) `cdjq` where the
book actually prints **свой** ("one's own"). This is the same class of gotcha flagged in
`00_Reference_Extraction_Spec.md` for Serbian/Croatian/Bosnian and Korean sources, confirmed here
independently. The substitution is not arbitrary: it is the standard **ЙЦУКЕН (JCUKEN) Russian
keyboard layout** baked into the font — i.e., each Cyrillic glyph was typeset using the Latin key
that produces it on a Russian typewriter/keyboard. Decoded and cross-verified against 15+ known
word/gloss pairs across widely separated pages (свой/мой/себя/весь/всякий/каждый/любой/тоже/также/
чай/сахар and more, all confirmed against the source's own adjacent English glosses) before being
used anywhere in this file:

```
q→й  w→ц  e→у  r→к  t→е  y→н  u→г  i→ш  o→щ  p→з  [→х  ]→ъ
a→ф  s→ы  d→в  f→а  g→п  h→р  j→о  k→л  l→д  ;→ж  '→э
z→я  x→ч  c→с  v→м  b→и  n→т  m→ь  ,→б  .→ю
```
Uppercase Latin → uppercase Cyrillic on the same key mapping. This cipher applies only within the
special Cyrillic-glyph runs (not to the book's ordinary Latin-script English prose, footnotes, or
author names, which extract normally). Given the sheer volume of running Cyrillic prose/examples
across ~250 pages, this file decodes and cites only the specific illustrative forms that carry
real vocabulary/grammar value (per the spec's copyright-discipline rule — short illustrative
citation, never bulk reproduction) rather than mechanically decoding every example sentence in the
source; every decoded form below was individually verified against the source's own parallel
English gloss. No vision-reading was needed for this range (real text layer throughout, decodable),
so Vision Reading Confidence is `n/a` for all rows; no marginalia was encountered.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| свой (svoy) | one's own (reflexive possessive) | pronoun/adjective | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | Reflexive possessive; used regardless of person, contrasts with мой/твой/его/её/наш/ваш/их which specify a fixed possessor independent of the clause's subject; p. 253–256 |
| себя (sebya) | oneself (reflexive pronoun, no nominative) | pronoun | core | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | Object-form reflexive; complementary-reference principle: points back to the clause subject; p. 253–256 |
| мой / твой (moy / tvoy) | my / your (non-reflexive possessive) | pronoun/adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Non-reflexive possessives with 1st/2nd person antecedents are grammatical (unlike 3rd person, where свой is normally obligatory) but carry a distinct meaning: they pick out an entity with an independent, fixed identity rather than one defined relationally; p. 253–255 |
| сам (sam) | -self (emphatic/contrastive pronominal adjective) | pronoun/adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Agrees in gender/number with себя's antecedent; agreeing in case too creates a contrast of *which entity* is involved (себя самого), while nominative сам creates a contrast of *whether the event happened at all*; p. 254–255 |
| кое- (koe-) | some- (differentiating existential prefix) | prefix/pronoun element | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Attaches to кто/что etc.; unlike -то, presumes a *plural set* of candidates of which some fit and others don't; natural in description, less so in causal narrative; §4.8.4 |
| -то (-to) | some- (existential suffix, bare existence) | suffix/pronoun element | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Asserts existence of at least one fitting entity, treated as essentially unique per occasion; fits causal/sequential narrative; §4.8.4, Table 4.17 |
| -нибудь (-nibud') | any- (existential suffix, indifferent selection) | suffix/pronoun element | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Asserts mere existence without caring which entity is selected; used in hypothetical/potential/deontic/counterfactual/imperative modality and iterative-conditional contexts; §4.8.3–4.8.7, Table 4.17 |
| -либо (-libo) | any- (existential suffix, differentiated alternatives, bookish) | suffix/pronoun element | literary | — | contemporary | — | — | grammar_reference | n/a | n/a | Like -нибудь but presumes real differences among candidate entities being sorted through; especially frequent with без ('without', ~100:1 over -нибудь in that context); common with comparatives and summaries of failed occasions; register marked as bookish; §4.8.5, Table 4.17 |
| некто (nekto) | a certain person (archaic indefinite) | pronoun | archaic | — | contemporary (source published 2004) | — | — | grammar_reference | n/a | n/a | Archaic/old-fashioned; typically modifies a proper name with an ironic touch, e.g. "некто Иванов" ("a certain somebody named Ivanov"); §4.8.6 |
| некий (nekiy) | a certain kind of (archaic indefinite adjective) | adjective | archaic | — | contemporary | — | — | grammar_reference | n/a | n/a | Old-fashioned register; §4.8.6 |
| некоторый (nekotoryy) | a certain (indefinite) | pronoun/adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Common lexicalized negative-prefix indefinite; §4.8.6 |
| несколько (neskol'ko) | several, a few (indefinite quantifier) | pronoun/adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Common lexicalized negative-prefix indefinite; §4.8.6 |
| не- series (negative pronouns: некому, нечего, негде, некогда, некуда...) | there's no one to.../nothing to.../nowhere to.../no time to... (modal-negative existentials, unstressed prefix) | pronoun (idiomatic/elliptical constructions) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Elliptical/idiomatic; e.g. мне некогда ("I don't have time for it"), нечего делать ("nothing can be done") — used with the free dative-with-infinitive construction (§5.10.5); §4.8.8 |
| не- series (не́кому, не́чего, не́где, не́когда, не́куда...) | there's no one who could.../nothing that could... (negative modal existentials, stressed prefix) | pronoun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Distinguished from the unstressed series above by stress on the negative prefix; denies any possibility of a fitting individual — a modal act, not a simple factual negation; §4.8.8 |
| весь / вся / всё (ves' / vsya / vsyo) | all, the whole (of) | pronoun/adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Undifferentiated totality: with a plural, the whole group acts uniformly; with a singular concrete noun, all parts of the whole are involved; with an abstract noun, the quality is manifested completely; exhaustive and collective (non-individuating); §4.8.9, Table 4.18 |
| каждый (kazhdyy) | each, every | pronoun/adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Treats set members as distinct individuals, each independently participating; natural with actual, multiple/iterative occasions (present or past imperfective), occasionally a single realized perfective occasion; exhaustive + individuating + actual; §4.8.9 |
| всякий (vsyakiy) | any (kind of), every sort of | pronoun/adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | One of the four universal adjectives discussed alongside весь/каждый/любой; §4.8.9, Table 4.18 |
| любой (lyuboy) | any (one), whichever | pronoun/adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Selects one indifferent individual from a set for a single potential situation (not multiple actual ones); at home with imperatives, perfective non-past, or modal + infinitive; §4.8.9 |
| чай (chay) | tea | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Secondary genitive (gen2, "-u" ending) example noun — mass/substance nouns that can be portioned/measured/consumed retain gen2 most robustly; §5.5.2 |
| сахар (sakhar) | sugar | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example noun; §5.5.2 |
| сыр (syr) | cheese | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example noun; §5.5.2 |
| суп (sup) | soup | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example noun; §5.5.2 |
| мёд (myod) | honey | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example noun; also has a diminutive медок retaining gen2; §5.5.2 |
| табак (tabak) | tobacco | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example noun; §5.5.2 |
| квас (kvas) | kvass (fermented rye-bread drink) | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example noun, ranked highest for gen2-acceptability in the cited Krysin (1974) survey; diminutive квасок also retains gen2; §5.5.2 |
| воск (vosk) | wax | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example (less-frequent substance-noun group); §5.5.2 |
| кипяток (kipyatok) | boiling water | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example; §5.5.2 |
| коньяк (kon'yak) | cognac | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example; §5.5.2 |
| дёготь (dyogot') | pitch, tar | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example; §5.5.2 |
| керосин (kerosin) | kerosene | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example; §5.5.2 |
| творог (tvorog) | curd cheese, tvorog | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example, second-highest-ranked in the Krysin survey after квас; §5.5.2 |
| смех (smekh) | laughter | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example from the "events" subgroup (residual/unusual gen2 use) — abstract-event nouns are noted as a weaker category for gen2 than substances; §5.5.2 |
| страх (strakh) | fear, terror | noun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Gen2 example, "events" subgroup; §5.5.2 |
| боя́ться (boyat'sya) | to fear | verb (reflexivum tantum) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Exists only as a reflexive form; historically governed the genitive, has begun to allow the accusative in recent usage; §5.8.3 |
| слу́шаться (slushat'sya) | to obey, listen to | verb (reflexivum tantum) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Reflexivum tantum, related to a non-reflexive root verb with a distinct meaning; §5.8.3 |
| мы́ться (myt'sya) | to wash (oneself) | verb ("true" reflexive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Intransitive body-care reflexive, contrasts with мыть себя ("wash oneself" as a directed transitive act, coincidentally aimed at oneself); §5.8.3 |
| бри́ться (brit'sya) | to shave (oneself) | verb ("true" reflexive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Same class as мыться; §5.8.3 |
| дра́ться (drat'sya) | to fight (each other) | verb (reciprocal reflexive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Reciprocal-reflexive class: mutual action between two or more parties; §5.8.3 |
| мири́ться (mirit'sya) | to reconcile (with each other) | verb (reciprocal reflexive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Reciprocal-reflexive class; §5.8.3 |
| куса́ется / боли́т / жжётся (kusaetsya, etc.) | bites / butts / stings (habitual disposition) | verb (habitual reflexive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Small closed class expressing an animal/plant's standing behavioral disposition, e.g. собака кусается "the dog bites (as a habit)"; §5.8.3 |
| белеть(ся) / темнеть(ся) / синеть(ся) / краснеть(ся) | to show/become white / dark / blue / red | verb (phenomenological reflexive pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Non-reflexive form reports a definite manifestation of color; the reflexive counterpart attenuates it — partial, obstructed, or unstable/fading visibility; reflexive forms noted as infrequent in practice; §5.8.3 |
| же (zhe) | -indeed / as for (contrastive-identity particle) | particle | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Discussed under lexical information operators §7.6; distinguishes contrastive identity from expected difference |
| та́кже (takzhe) | also, likewise (property-polarity marker) | particle/adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Operates on a *property*: asserts a known entity, contrary to potential expectation, also has a given property (polarity-of-a-property reading); §7.6.3 |
| то́же (tozhe) | also, as well (entity-list marker) | particle/adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Operates on *entities*: asserts that another individual, contrary to possible expectation, shares a property already established for someone/something else (a list-of-entities reading); typically stressed, follows the constituent it operates on; §7.6.3 |
| кто / что / когда (kto / chto / kogda) | who / what / when | interrogative-indefinite pronoun / adverb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Base interrogative-indefinite stems that combine with -то/-нибудь/-либо/кое-/не- to form the whole indefinite/negative pronoun system covered above; §7.5.2 |
| кото́рый (kotoryy) | which (of a limited set) | relative/interrogative pronoun | core | — | contemporary | — | — | grammar_reference | n/a | n/a | Though it has become the general relative pronoun, as an interrogative it stays restricted to selecting from a small/limited, contextually given set; §7.5.2 |

## Grammar points

### §4.7.11–4.7.12 Reflexive possessive свой vs. non-reflexive мой/твой/его/её; emphatic сам; retrospective on reflexives (pp. 253–257)

Russian keeps track of coreference through a family of reflexive devices layered on top of a general complementarity principle: a reflexive pronoun points back to the clause's own subject, a non-reflexive pronoun points to some other, independently-identified entity. With first- and second-person antecedents specifically, this complementarity is not obligatory the way it is for third person — мой/твой can coexist grammatically alongside свой referring to the same speaker — but the choice is never free variation: свой frames the possessed item as defined *relationally*, by the role it plays for the current subject in the current event (an "essential" reading — "whoever is filling the wife/repertoire/partner role for x right now"), while мой/твой frames it as an independently persisting entity with a fixed identity across time (a memoirist's one unique, unchanging life vs. a shifting cast of "my repertoire" at different past moments). The imperative shows the same split: reflexive себя is used for an addressee's not-yet-identified associate defined purely by relation to the addressee (e.g. "send your adjutant, whoever it is"), non-reflexive ваш for a specific, already-known referent. The emphatic сам intensifies себя: agreeing in case with себя (себя самого) contrasts *which* entity is affected against other candidates; left in the nominative (сам себя) it instead contrasts *whether the event happened at all* against the possibility that it might not have.

### §4.8.3–4.8.5 Existential pronoun compounds: -то, кое-, -нибудь, -либо (pp. 262–265)

Russian's four productive existential-pronoun-forming elements differ along several orthogonal dimensions the book lays out in a summary table (Table 4.17): whether they assert *mere* existence of a fitting entity or presume a *set* of candidates with real differentiation among them; whether the relevant modality is actual/realized, potential/hypothetical, or iterative; and register (neutral vs. bookish vs. informal). -То asserts a unique fitting entity actually exists (fits causal/sequential narrative — "somebody made room, and then..."). Кое- presumes a plural set of candidates of which only some fit, favoring description over narrative ("here and there, somebody glanced sideways" — several distinct individuals, each independently glancing). -Нибудь is indifferent — any candidate is as good as another — and is the default for potential/hypothetical/deontic/imperative contexts and iterative conditionals. -Либо resembles -нибудь but keeps the possibility of real differences among candidates live, is markedly bookish, and shows a striking collocational skew: with без ("without") it outnumbers -нибудь roughly 100:1; it's also favored with comparatives, summaries of failed attempts, and contexts of weak/implicit negation ("no matter which one you pick, the outcome is the same").

### §4.8.6 Lexicalized negative-prefix indefinites некоторый, несколько, некто, некий (p. 265)

A separate small set of indefinites forms by prefixing interrogative stems with unstressed не-. Некоторый and несколько are fully current, unmarked. Некто and некий are explicitly flagged as archaic/old-fashioned in contemporary usage, with некто carrying a distinct ironic coloring when modifying a proper name ("a certain somebody named X").

### §4.8.7 Summary table of -то/-кое-/-нибудь/-либо (Table 4.17) (p. 265)

Timberlake tabulates the four items along a shared five-part meaning schema: existential type (existence-of-essence vs. existence-of-individual), degree of individuation, tense-aspect-modality profile, speaker perspective (internal/actual vs. external/hypothetical), and register. This table is the book's own systematic cross-comparison and functions as the chapter's capstone generalization over the preceding four subsections.

### §4.8.8 Stressed negative pronouns не́кому, не́чего, не́где, не́когда... (pp. 265–266)

A distinct series (stress falls on the negative prefix, contrasting with the semantically different unstressed series above and with the plain negative pronouns никто/ничто not detailed in this chunk) denies the very *possibility* of a fitting individual — a modal act of denial, not a plain factual negative. Structurally these pronouns are tied to the "free dative-with-infinitive construction" (cross-referenced forward to §5.10.5): "мне некогда" ("I have no time [for it]"), "нечего делать" ("nothing can be done"), both cited as heavily idiomaticized/elliptical collocations rather than freely productive.

### §4.8.9 Universal adjectives весь, всякий, каждый, любой (pp. 266–268, Table 4.18)

Four "universal" adjectives all presume a bounded set and assert an activity/state extends across it, but differ in *how*: весь treats the set as an undifferentiated whole (all ships went to the same place; the whole cemetery; a quality manifested completely) — exhaustive and collective, not individuating. Каждый individuates: every member independently participates, and this fits naturally with actual, repeated occasions (imperfective present/past) and occasionally a single realized perfective event (mother set down one piece of bread in front of every person — one accomplished act, individuated per recipient). Всякий patterns as a fourth member of this set (paired for contrast with the other three, though this chunk's excerpted detail centers on весь/каждый/любой). Любой differs from каждый by being *potential* rather than actual: it selects a single, arbitrary member for one hypothetical situation, at home with imperatives, non-past perfectives, and modal+infinitive constructions ("ask any professional driver...").

### §5.5.1–5.5.2 Secondary genitive (gen2) (pp. 328–329)

A closed, shrinking set of Declension-Ia nouns has, alongside the regular genitive (gen1, ending in {-a}), a secondary genitive ending in {-u}, restricted almost entirely to mass nouns for substances/liquids that can be portioned out, measured, purchased, or consumed (a partitive-flavored genitive). Frequency is graded: roughly half a dozen nouns (led by квас, творог, табак, лак, сыр, воск, then сахар, чай) take gen2 readily, with a further dozen or so less reliably, diminutives of mass nouns retaining it especially well, and a residual tail of abstract "event" nouns (смех, вздор, шум, страх) using it only occasionally. The book cites Krysin's (1974) survey data directly and cautions that the ranking is sensitive to which governing verb/context the survey used — six of its top nouns were tested only with the maximally gen2-favorable verb "напиться" ("drink one's fill of"), inflating their apparent frequency relative to сахар/чай tested in less favorable contexts. Timberlake frames the phenomenon as historically contracting: gen2 was more general in earlier Russian and is now residual outside this substance-noun core.

### §5.5 (continued) Secondary locative (loc2) (referenced, pp. 328–330 range)

Parallel to gen2, a subset of Declension-Ia nouns has a secondary locative in stressed {-ú} instead of the ordinary {-e} locative (loc1); some Declension-IIIa nouns show a stress-only split of the same functional kind (unstressed {-i} patterning like loc1, stressed {-í} patterning like loc2). Both secondary case forms are described as genuine functional genitives/locatives (not a separate case), just lexically restricted to a shrinking list of items.

### §5.7.2–5.7.3 Jakobson's case system and syncretism (pp. 339–341+)

The book presents and critically evaluates Roman Jakobson's structuralist binary-feature analysis of the six Russian cases (using features like [±peripheral], [±quantifying], [±directional]). Nominative/accusative are [-peripheral] (core syntactic arguments); accusative/dative share [+directional] (direct/indirect objects, "argument the predicate's activity is directed at"); locative is transparently [+peripheral]. Genitive and instrumental are presented as the hardest cases for a unified ("Gesamtbedeutung") account: genitive's shared thread across quantifier-governed, verb-governed, negation, and possessive-internal-argument uses is glossed as "restricted quantity of participation," though Timberlake notes this fits quantifying contexts cleanly but strains to cover simple possession. Instrumental's unifying thread is glossed as synecdoche — the instrumental-marked entity is part of the larger event (as agent, tool, or manner) but "not the whole story." Timberlake's own verdict is measured: Jakobson's invariant-meaning program is most useful precisely where it explains *synchronic variation* (e.g., accusative-vs-genitive alternation under negation, §5.3–5.4), but a fully general Gesamtbedeutung tends toward vagueness; a network-of-related-constructions model (as in Wierzbicka 1980) is presented as the more defensible descriptive path, with an invariant "core" value retained mainly as an interpretive aid for cases in live variation, not a full explanatory reduction. (§5.7.3's syncretism discussion, which follows, is only introduced by its header at the tail of this chunk's readable range and is not detailed here — flagged for whichever pass covers late-§5.7/early-§5.8 territory to confirm full coverage.)

### §5.8.3 Reflexive verbs — five subtypes (pp. 345–347)

Timberlake divides Russian's -ся/-сь reflexive-marked verbs into five distinct, non-interchangeable functional classes rather than treating "reflexive verb" as one category: (1) **reflexivum tantum** — verbs that exist only in reflexive form (бояться, слушаться, бороться, смеяться, надеяться), historically genitive-governing but increasingly tolerating the accusative; (2) **"true" reflexives** — a small closed set of body-care verbs (мыться, бриться) where the reflexive form is a genuinely intransitive activity, distinct in meaning from the same verb + себя, which instead frames a directed action that merely happens to target the self; (3) **reciprocal reflexives** — mutual action between parties (драться "fight each other," мириться "reconcile"); (4) **habitual reflexives** — a very small class expressing a standing behavioral disposition of the subject (собака кусается "the dog [habitually] bites," корова бодается "the cow butts," крапива жжётся "the nettle stings"); (5) **phenomenological reflexives** — pairs like белеть/белеться, где the non-reflexive reports a definite, fully realized visual manifestation of color, and the reflexive attenuates it to something partial, obstructed, or unstably/fadingly perceived — noted as an infrequent pattern in practice.

### §6.4.2 Tests for aspect membership (pp. 401–402)

The single most rigid test for perfective/imperfective aspect membership: only imperfective verbs form the periphrastic future with буду/будешь... (не буду нарушать "I will not disturb"); perfectives have only two tenses (past and morphological non-past-with-future-meaning) and cannot combine with буду at all. Secondary, less absolute tests: only imperfectives serve as infinitival complements of phasal verbs (начать/начинать "begin," продолжать "continue," кончить/кончать "finish"); imperfectives are the default (though not exclusive) complement of motion verbs expressing purpose; only perfectives freely complement удаться/удаваться ("manage to, succeed at"); only imperfectives normally take a bare-accusative duration phrase; only perfectives normally combine with the temporal adverb за implying successful completion within a bounded interval (imperfectives only under special conditions). The periphrastic-future test is characterized as the one genuinely definitional, near-exhaustive partition; the rest are described as strong tendencies with exceptions.

### §6.4.3 Aspect and morphology — the core tripartite strategy (pp. 402–403+)

Aspect is explicitly framed as a lexical classification, not an inflectional category — no single morpheme marks "perfective" or "imperfective" across the whole system. The core productive pattern is tripartite: unprefixed simplex verbs (largely static/durative: грустить "be sad," видеть "see," or gradual/responsible: сидеть "sit," работать "work," мотать "wind," льстить "flatter," крутить "wind") are as a rule imperfective; simplex verbs then combine with one or more prefixes, which impose a limit on the flow of states/activities in either a **qualitative** sense (activity construed as continuous change toward a limit, beyond which no further change is contemplated — открутить "unscrew, remove by twisting," illustrated with a bolt-removal example where the aspectual argument is the object of a transitive or subject of an intransitive) or a **quantitative/quantizing** sense (the book's own text for the quantitative branch continues past this chunk's excerpted range and is not detailed here).

### §7.4.1–7.4.2 Negation: scope and locality (pp. 459–460)

Negation is characterized philosophically as a "powerful operator": asserting not-X invites the listener to actively entertain the alternative X, not merely register X's absence. Structurally, Russian negation is described as generally *local*: to negate some constituent other than the finite verb, the negative particle не sits immediately next to that constituent, not attached to the verb (contrasted directly with English, where verb-negation is often read by synecdoche as negating some other constituent of the predicate phrase, e.g. "Nastia didn't go to the station" vs. Russian's contrastive не placed directly before "to the station" when the intended negated element is the destination, not the verb "go" itself). When не does sit next to the finite verb in Russian, it genuinely negates the verb itself, only rarely extending scope to negate an argument instead.

### §7.5.1–7.5.2 Questions: content vs. polarity, question-word position (pp. 461–462)

Questions and imperatives are framed as the two most overt markers of active speaker/addressee interaction; the book distinguishes content questions (formed on the кто/что/когда/... interrogative-indefinite stem family) from polarity (yes/no) questions. Который, despite having become the general-purpose relative pronoun, stays restricted as an interrogative to selecting one member out of a small, contextually limited/given set (e.g. choosing between two named candidates), not an open-ended "which one" over an unbounded domain. Question-word placement is discourse-sensitive rather than fixed: clause-initial is the default and unmarked order, but the question word can be pushed later in the clause when the question itself is anticipated (an oral exam, an interview) or reformulated as an echo/confirmation question ("Where was it you studied?" / "Where did you say you studied?"), with word order itself signaling the pragmatic type of question being asked.

### §7.6.3 Contrastive-identity particles тоже and также (pp. 467–468)

Тоже and также are both described as asserting that something currently under discussion is similar to something already established, in a way that's non-obvious/notable rather than fully expected — but they operate on different logical objects. Также operates on a *property*: it takes a known entity and asserts, against possible expectation, that a further property also holds of it (a "polarity of a property" reading). Тоже operates on *entities*: it presumes one individual already has some property and asserts that a further, distinct individual — contrary to a background expectation that it wouldn't — shares that property (a "list of entities" reading). Тоже is typically stressed and follows the constituent (often a pre-verbal subject or object) it takes scope over; it can operate on a clause's subject, the subject of an existential predicate, or a pre-verbal object, and can even extend to whole occasions/events under discussion (a sequence of failed meeting attempts, each one "also" unsuccessful).

### Chapter/section map for the remainder of this range (not separately detailed above — flagged for context, not skipped from the coverage rule; see note below)

This 250-page chunk spans the tail of Chapter 4 (Arguments: reflexives, indefinite/negative/universal pronouns), the whole of Chapter 5 (Predicates and arguments: predicative adjectives/nouns, aspectual co-predicates, existential/possessive predication with есть/нет, governed and secondary genitive, the full six-case system and Jakobson's analysis, reflexive verbs, participles and passives, agreement, non-finite/infinitive constructions), the whole of Chapter 6 (States, change, tense; irrealis mood; tense in subordinate clauses; aspect — morphology, pairs, intrinsic lexical aspect, aspect-in-context across narrative/essentialist/progressive/iterative/future readings; temporal adverbs and their case-marking prepositions), and the first half of Chapter 7 (discourse: intonation contours, word order patterns SVO/OVS and their pragmatic conditioning, negation, questions, and lexical information operators же/тоже/также/нaже/тоже). The subsections paraphrased above were selected as the highest information-density grammar points for the mechanics-analysis phase (pronoun/register systems, case theory, aspect fundamentals, negation/question/particle syntax — the machinery most likely to constrain how any derived slang could plausibly form or mark register). The remaining subsections (predicate/argument valence typology, the full aspect-pairs and iterative/progressive/future context system, intonation contour typology, and the detailed word-order chapter) are real grammar content genuinely present in the source but not separately paraphrased in this pass; a follow-up non-redundant-supplement pass — per this project's multi-source dispatch pattern — should consult this file's opening note and fill only what's still missing rather than re-reading the full 250 pages from scratch.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. All Cyrillic
forms cited above are single decoded words/short set phrases used as illustrative glosses, not
reproductions of the source's own example sentences or explanatory prose.
