# Spanish — Established Vocabulary/Grammar: *Introducción a la lingüística hispánica* (2nd ed.) — Full-Book Extraction (Ch.1–8)

**Source:** José Ignacio Hualde, Antxon Olarrea, Anna María Escobar, Catherine E. Travis,
*Introducción a la lingüística hispánica* (2nd edition, Cambridge University Press, 2009/2010).
University-level hispanic-linguistics textbook (not a pedagogical teaching grammar), written
entirely in Spanish. 570 PDF pages, confirmed real `pdftotext` text layer throughout (no
font-substitution cipher, no vision-reading needed). Printed page numbers run 1–554 (roman-numeral
front matter i–xiv precedes); PDF-page-to-printed-page offset is a constant **+16** (printed page
N = PDF page N+16) for the main body, verified empirically by direct inspection of PDF pages 1–20
against their printed folios (chapter 1 begins on PDF page 17 = printed page 1).

Book structure (author per chapter):
1. **Cap. 1** — La lingüística: ciencia cognitiva (Olarrea), printed pp. 1–44
2. **Cap. 2** — Los sonidos de la lengua: fonética y fonología (Hualde), printed pp. 45–122
3. **Cap. 3** — La estructura de las palabras: morfología (Escobar & Hualde), printed pp. 123–200
4. **Cap. 4** — La estructura de la oración: sintaxis (Olarrea), printed pp. 201–278
5. **Cap. 5** — Historia de la lengua española (Hualde), printed pp. 279–338
6. **Cap. 6** — El estudio del significado: semántica y pragmática (Travis), printed pp. 340–389
7. **Cap. 7** — Variación lingüística en español (Escobar), printed pp. 391–444
8. **Cap. 8** — El español en los Estados Unidos (Escobar), printed pp. 445–502
(Glosario, Bibliografía, and general index follow; not separately extracted as source content.)

## Coverage note — non-redundant-supplement reasoning per chapter (auditable, per dispatch instructions)

This project already has 59 established Spanish files from pedagogical teaching grammars
(conjugation paradigms, basic/advanced grammar, voseo, subjunctive triggers, idiom catalogs —
all forms-level pedagogical content). Differentiated effort applied as follows:

- **Ch.1 (cognitive-science framing):** FULL extraction. No prior Spanish source in this project
  covers language-acquisition theory, neurolinguistics, or the Chomskyan competence/performance
  framework. Treated as genuinely new territory despite being more "theory of linguistics" than
  "facts about Spanish" — it supplies conceptual vocabulary (afasia, bioprograma, hipótesis
  innatista, etc.) that may matter for later mechanics-analysis work and is explicitly in scope per
  the dispatch brief.
- **Ch.2 (fonética y fonología):** FULL extraction, flagship chapter. No prior source gives
  IPA-level phonetic/phonological description of Spanish (consonant/vowel inventories, allophone
  rules, distinctive features, syllabification, stress, intonation). Extracted thoroughly per the
  dispatch brief.
- **Ch.3 (morfología):** NON-REDUNDANT SUPPLEMENT. Verb paradigms, subjunctive forms, pronoun
  forms, and basic noun/adjective agreement are already extensively covered by the pedagogical
  grammars (e.g. `005_practice_makes_perfect_basic_spanish_grammar.md`,
  `006_practice_makes_perfect_advanced_spanish_grammar.md`,
  `007_practice_makes_perfect_spanish_irregular_verbs.md`, the `008*_verb_tenses` files, the
  `009*_vocabulary` files). This chapter is extracted only for structurally new content a
  pedagogical source would never present: the formal morpheme/root/affix framework, the
  bound/free-morpheme and derivational/inflectional distinctions, the systematic typology of
  Spanish word-formation processes (nominalization, adjectivization, verbalization,
  adverbialization, prefixation, compounding types each with a named structural pattern, e.g.
  *hombre rana* N+N→N, *pelirrojo* N+Adj→Adj), abbreviation/acronym formation, and the
  hierarchical (tree-structure) representation of word structure. Specific regular verb paradigm
  tables and subjunctive trigger lists are explicitly skipped as redundant.
- **Ch.4 (sintaxis):** NON-REDUNDANT SUPPLEMENT. Basic sentence types, `se`-construction usage
  lists, and the subjunctive reference table substantially overlap prior extraction. This chapter
  is extracted for the formal constituent-structure / X-bar-theoretic analysis (phrase-structure
  rules, subcategorization, the four `se` construction types analyzed structurally rather than as a
  usage list, and the formal classification of simple vs. compound sentences) that no pedagogical
  source formalizes this way.
- **Ch.5 (historia del español):** SUBSTANTIVE extraction, proportionate. New territory relative
  to this project's pedagogical grammars; a different angle from dedicated history-of-Spanish books
  being extracted in a sibling dispatch (Penny/Pountain), so independently worth covering, but kept
  to the chapter's own proportion of the book (not exhaustively line-by-line).
- **Ch.6 (semántica y pragmática):** SUBSTANTIVE extraction — new in the 2nd edition, genuinely new
  territory (semantic relations, semantic roles, deixis, speech acts, Grice's cooperative principle).
- **Ch.7 (variación lingüística en español) and Ch.8 (español en los Estados Unidos):** FULL/HIGH-
  VALUE extraction. This is exactly the explicit dialectal/regional/sociolinguistic annotation the
  extraction spec flags as highest priority. Every explicitly named regional/national variant is
  captured with Attested Region / Geographic Scope filled in.

**Vision-reading guard:** not applicable — source has a confirmed real, clean `pdftotext` text
layer throughout; no vision-reading was performed and no marginalia was encountered.

**Copyright discipline:** all explanatory content below is paraphrase/analysis in my own words;
only short illustrative Spanish phrases/examples are quoted directly, consistent with
`00_Reference_Extraction_Spec.md`. No vocabulary box, table, or passage is bulk-reproduced.

---

## Vocabulary

Note: this book is a linguistics textbook, not a word-list/phrasebook — its "vocabulary" is
overwhelmingly technical/metalinguistic terminology (terms *about* language) rather than
general-purpose lexical items. All rows below use `Usage Tier = technical.linguistics` unless noted,
`Source Type = grammar_reference`, `Transcription Confidence = n/a`, `Vision Reading Confidence =
n/a`, `Weight/Frequency = —`, and `Attested Era = contemporary (source published 2009/2010)` unless
a specific historical period is indicated (historia chapter). `Attested Region`/`Geographic Scope`
are filled in only where the book explicitly marks a dialectal/regional variant.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| competencia | tacit mental knowledge of one's own language (Chomsky's "competence") | noun | technical.linguistics | — | contemporary (source published 2009/2010) | — | — | grammar_reference | n/a | n/a | Contrasted with *actuación*; distinct from Saussure's *lengua* (p.9). |
| actuación | concrete use/performance of language (Chomsky's "performance") | noun | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.9. |
| lengua | the language system shared by a speech community (Saussure's *langue*) | noun | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.9; distinguished from *habla* and *lenguaje*. |
| habla | concrete use of *la lengua* by speakers (Saussure's *parole*) | noun | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.9. |
| lenguaje | the human faculty of language in general (Saussure's *langage*) | noun | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.9; distinct from a particular *lengua*. |
| gramática universal | the innate set of principles common to all human languages, present at birth | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.20; core innatist-hypothesis construct. |
| hipótesis innatista | the innatist hypothesis: language acquisition driven by an innate linguistic faculty | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.19. |
| argumento de la pobreza de estímulos | poverty-of-stimulus argument: the gap between fragmentary child input and the complex grammar acquired | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.22. |
| pidgin | a simplified contact language with no native speakers, arising between groups without a shared language | noun | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.25; example cited: Chinook Jargon, Basque–Icelandic pidgin ("for ju mala gisona" = "eres un mal hombre"). |
| lengua criolla | a creole: a pidgin nativized by a generation of child learners, becoming a fully complex language | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.25; Bickerton's "bioprogram" hypothesis cited. |
| periodo crítico | critical period for first-language acquisition, after which full native acquisition becomes very difficult/impossible | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.28; Genie case cited as evidence. |
| afasia | aphasia: a language disorder resulting from brain injury | noun | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.31. |
| afasia de Broca | Broca's aphasia: agrammatic, labored speech production with largely intact comprehension | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.32; example transcript quoted in Tabla 1.2 (not reproduced here, only paraphrased pattern). |
| afasia de Wernicke | Wernicke's aphasia: fluent but semantically/lexically erroneous speech, with comprehension deficits | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.33. |
| afasia anómica | anomic aphasia: difficulty retrieving specific words, substituted with gesture/circumlocution | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.33. |
| Trastornos Específicos del Lenguaje | Specific Language Impairment: a probably-hereditary cluster of grammatical deficits unrelated to intelligence | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.35. |
| modelos conexionistas | connectionist models: computational models of general learning mechanisms, proposed as an alternative to innate grammar modules | noun phrase | technical.linguistics | — | contemporary (2009/2010) | — | — | grammar_reference | n/a | n/a | p.38. |
| castellano | "Castilian" — older name for the Spanish language, from the medieval Kingdom of Castile | noun | regional | — | contemporary (2009/2010) | Peru, Chile, Argentina (preferred term); Spain's bilingual regions (preferred there specifically to contrast with Basque/Catalan/Galician) | national | grammar_reference | n/a | n/a | p.40; contrasted with *español*. |
| español | "Spanish" — the more recent, now-dominant name for the language | noun | regional | — | contemporary (2009/2010) | Mexico, Puerto Rico (preferred term) | national | grammar_reference | n/a | n/a | p.40. |

## Grammar points — Capítulo 1: La lingüística: ciencia cognitiva (pp. 1–44)

### Prescriptive vs. descriptive grammar (pp. 2–4)

Traditional grammar (from classical India/Greece onward) is fundamentally prescriptive: it
codifies the "correct" way to speak, privileges written over spoken language, assumes language
reached a historical peak of perfection (e.g. Spanish Golden Age literature), and maps logical
categories onto grammatical ones (substance→noun, accident→adjective). Modern descriptive
linguistics instead documents how language is actually used, treating stigmatized forms (e.g.
*"me se ha olvidado"* instead of the prescribed *"se me ha olvidado"*) as sociolinguistic facts
about which social groups favor which variants, not as corruption. The book explicitly states no
dialect or register is intrinsically better/worse than another (Peninsular vs. Mexican Spanish,
British vs. Australian English) — language change is neither decline nor improvement, just
inevitable; only dead languages stop changing.

### Historical arc: comparative/historical linguistics → structuralism → generativism (pp. 4–6)

Late 18th century: discovery of the Sanskrit–European genealogical connection launched comparative/
historical ("diachronic") linguistics. Early 20th century: Saussure shifted focus to synchronic
description and to language as a system of signs whose units gain identity only by relation/
opposition to other units. Mid-20th century in the US: focus on indigenous/non-Indoeuropean
languages forced new descriptive tools; Sapir and Whorf explored linguistic relativity (language
structure shaping thought). 1950s: decline of behaviorism and Chomsky's critique of it launched
generative grammar as the dominant modern paradigm.

### The linguistic sign (Saussure) — arbitrariness vs. iconicity (pp. 6–8)

A linguistic sign has two parts: *significante* (the sound sequence) and *significado* (the
concept). The significante–significado link is essentially **arbitrary** — compare Sp. *árbol*,
Eng. *tree*, Basque *zuhaitz* for the same concept. Opposed to arbitrary is **motivado**/iconic
signaling (e.g. a pictorial road sign of children holding hands). Even onomatopoeia, the most
iconic case in language, is only partly iconic since it still varies by language (Sp. rooster cry
*kikirikí*/*kokorikó* vs. Eng. *cock-a-doodle-doo*).

### Design features distinguishing human language from animal communication (pp. 14–17)

The book lists eight features, following a Hockett-style design-features framework, illustrated
against bee dance communication, primate alarm calls, etc.:
1. **Arbitrariedad** (arbitrariness) — most linguistic signs lack a natural signifier–referent link.
2. **Desplazamiento** (displacement) — ability to refer to events distant in time/space; animal
   signaling is almost always tied to the immediate stimulus (a dog cannot communicate "I want to
   go for a walk in Istanbul tomorrow at three").
3. **Articulación dual** (duality of patterning) — meaningless sound units (phonemes) combine into
   meaningful units (words); e.g. Spanish /pan/ has three meaningless phonemes that combine into one
   meaningful word.
4. **Productividad** (productivity) — infinite capacity to produce/understand new utterances from a
   finite inventory; animal systems have a fixed, finite repertoire.
5. **Prevaricación** (prevarication, i.e. the capacity to lie) — most animal systems lack this,
   though some primates have been observed falsely emitting predator-alarm calls to keep rivals away
   from food.
6. **Reflexividad** (reflexivity) — language can refer to itself (the metalinguistic function,
   citing Jakobson); e.g. *"'un' es un artículo indeterminado"*.
7. **Unidades discretas** (discreteness) — language uses a small set of sharply contrasting discrete
   units (phonemes), unlike the continuous/analog signaling (grunt intensity, etc.) typical of animal
   communication; *"liiiibro"* does not denote a bigger/heavier book in any natural language.
8. **Creatividad** (creativity) — utterances are not bound to external/internal stimuli the way
   animal communication largely is; speakers routinely produce and understand novel sentences.

### Ape language experiments (pp. 17–19)

Surveyed as evidence for/against whether non-human animals can acquire language: Viki (chimp,
1940s, learned 4 spoken English words — defeated by vocal-tract limits); Washoe (ASL, ~130 signs,
taught 31 to another chimp Lulis, combined signs e.g. "bebé mío", "más fruta"); Nim Chimpsky (~125
ASL signs but never produced non-repetitive >2-sign combinations, 40% pure imitation); Koko (gorilla,
11 years of ASL training, novel compounds like "pulsera-dedo" for "ring" or "tigre-blanco" for
"zebra"); Kanzi/Panbanisha (bonobos, lexigram keyboard, ability ~ 2.5-year-old human child, trainer
claims spontaneous rule invention). The book notes the methodological dispute: critics treat these
as circus-trick-level behaviorist conditioning; trainers counter that linguists apply a double
standard (two-sign combinations count as "incipient syntax" in a human child but not in an ape).

### Innateness-hypothesis evidence (pp. 19–28)

Four lines of argument the book presents for the innatist hypothesis:
(i) **Universality** — not just that all cultures have language, but that languages share deep
    structural universals (subject/predicate, constraints on question formation — e.g. no language
    allows forming *"¿Qué tocas y el piano?"* from *"Toco la guitarra y el piano"*, despite its
    logical coherence).
(ii) **Poverty of stimulus** — the gap between the fragmentary/degenerate input children receive and
     the rich grammar they end up with; children acquire ~9–10 new words/day and are not explicitly
     corrected for grammar (parents correct truth-value, not grammaticality). Children's own
     overregularization errors (*"saliré"* for *"saldré"*, *"esté"* for *"estuve"*) show rule-governed
     generalization rather than pure imitation, and children never make certain *logically*
     available errors (e.g. fronting the wrong auxiliary across a relative clause boundary) that an
     analogy-based learner should sometimes make.
(iii) **Pidgins and creoles** — Bickerton's "bioprogram" argument: creolization adds grammatical
      structure (e.g. object-agreement marking, consistent word order) absent from the input pidgin,
      within a single generation, suggesting access to an innate structural template when input is
      degenerate.
(iv) **Stages of acquisition** — language develops through cross-linguistically uniform,
     biologically-timed stages (see Tabla 1.1 summarized below), analogous to other biologically
     constrained behaviors with critical periods (e.g. visual-cortex tuning in kittens, birdsong
     learning in canaries).

**Stages of first-language acquisition (Tabla 1.1, paraphrased, pp. 28–29):** newborns recognize
native-language rhythm/melody; ~3 months, laryngeal descent enables sound variety; up to 6 months
infants are "universal phonologists"; 6–10 months babbling (*ba-ba, ma-ma, pa-pa*); 10 months,
infants recognize only their own language's phonemes; 12 months, combine distinct syllables;
18 months, first words (no morphology yet — object/person names, then actions/routines); 18–24
months, vocabulary explosion (~1 new word every 2 hours until puberty; comprehension precedes
production); 18–30 months, telegraphic two-word stage, always correctly ordered
(agent-action-object-indirect.object-location), missing grammatical morphemes (prepositions, plural
*-s*, past *-aba*); 30–42 months, abrupt onset of recursive, complex structures (passives, questions,
comparatives, double negation, gender/number marking) with characteristic overregularization errors
(*"andé"* for *"anduve"*, *"hací"* for *"hice"*).

### Critical period hypothesis (pp. 27–29)

Adults rarely achieve native mastery of a second language, especially its phonetics/phonology
("foreign accent"). "Motherese"/caretaker-speech explanations are rejected (some cultures don't
address infants directly yet children still pass through the same stages). Age-of-immigration
studies cited: ages 3–6 → native-level grammaticality judgments; ages 8–15 → markedly worse; 17+ →
worst, with no further decline by age within that adult group. **Genie** (isolated from language
until age 13) is presented as key supporting evidence: she never progressed past simple noun-phrase
strings years after exposure began, despite otherwise intact cognition — used both to argue for a
language-specific cognitive module and for the existence of a critical period.

### Neurolinguistics: lateralization and aphasia types (pp. 31–36)

Language is predominantly left-hemisphere-lateralized (Broca, 1861, based on frontal-lobe lesion
patients). Evidence cited beyond lesion studies: hemispherectomy patients retain language only when
the left hemisphere is preserved; dual-task interference (finger-tapping with the right hand, which
is controlled by the contralateral left hemisphere, disrupts speech-imitation more than tapping with
the left hand). Three aphasia types distinguished (table example transcripts paraphrased, not
quoted): **afasia de Broca** (agrammatic — labored, telegraphic, missing function words, difficulty
with passive-sentence comprehension since it depends on grammatical cues like *por*); **afasia de
Wernicke** (fluent, well-articulated, but riddled with lexical/semantic substitution errors, with
comprehension deficits); **afasia anómica** (word-finding difficulty only, compensated by gesture/
circumlocution). None of the three produces total loss of cognition generally — used as evidence
for language as an independent cognitive module. **Trastornos Específicos del Lenguaje** (a
probably-hereditary cluster of narrow grammatical deficits, e.g. missing subject-verb agreement
morphology, more frequent in males, concordant in twins) are distinguished from lesion-based
aphasias as separate genetic evidence. Modern neuroimaging (MRI, PET, ERP) is noted as superseding
pure lesion-correlation methods, revealing that most linguistic functions are not cleanly localized
to single cortical regions.

### Critiques of the Chomskyan model (pp. 36–39)

Four critiques are surveyed: (1) restricting the field's object of study to *competencia* excludes
genuinely interesting phenomena (discourse structure, context–meaning relations, processing
difficulty) that psycholinguistic performance studies illuminate. (2) Over-reliance on introspective
grammaticality judgments as the primary data source is methodologically contested; other data
sources (speech-perception experiments, aphasic speech, acquisition data, dialect surveys) should
be integrated. (3) The innateness claim is under-specified — critics argue poverty-of-stimulus data
are not unequivocal, that a unique-to-humans trait need not imply direct single-gene genetic control,
and that Specific Language Impairment data may instead reflect a general deficit in rapid
sequential-information processing rather than a language-specific module. (4) The claim that
language is an autonomous cognitive module is contested by **modelos conexionistas**
(connectionist models), which attempt to derive grammar-like constraints from general learning
mechanisms rather than an innate, language-specific module.

### General vs. particular linguistics; naming the language (pp. 39–42)

The book frames itself as moving from *lingüística general* (chapter 1's universal-language-faculty
questions) to *lingüística particular* — the study of one specific language (Spanish/Castilian) in
the remaining chapters. **Naming note (relevant to regional/register annotation):** *castellano* is
the older name (from the medieval Kingdom of Castile); *español* became dominant as Castile's
political power expanded. The book explicitly states regional preference: *castellano* is preferred
in Peru, Chile, Argentina, and within Spain's own bilingual regions (Basque Country, Catalonia,
Galicia) specifically to contrast with the co-official regional language; *español* is preferred in
Mexico and Puerto Rico. English usage of "Castilian Spanish" (≈ Peninsular norm) vs. "Latin American
Spanish" does not map cleanly onto the Spanish-language *castellano*/*español* distinction. The book
adopts *español peninsular* / *español latinoamericano*, and finer labels (*español centronorteño*,
*español andaluz*, *español mexicano*, *español paraguayo*, *español andino*, etc.) for the rest of
the book — this terminological framework is the one followed in Ch. 7–8 below.

---

## Chapter 2 — Los sonidos de la lengua: fonética y fonología (pp. 45–122) — FLAGSHIP CHAPTER

This is the single highest-value chapter in the book for this project: a full IPA-based phonetic/
phonological description of Spanish, saturated with explicit dialectal annotation. Extracted in
full detail. Author: José Ignacio Hualde.

### Core concepts: fonema, alófono, transcription conventions (pp. 45–52)

A **fonema** is a contrastive, meaningless sound unit (phonemes combine to build meaningful
lexical units — *pan* = /p/+/a/+/n/). A **par mínimo** (minimal pair) is the diagnostic tool for
establishing phonemic contrast (e.g. *peso*/*beso* shows /p/≠/b/). Spanish has 5 vowel phonemes and
fewer than 20 consonant phonemes (exact count dialect-dependent). Spanish orthography is largely
(not perfectly) phonemic — e.g. the *u* in *guerra* and the *h* in *hormiga* represent no sound; *j*,
word-initial *g* (before e/i), and *x* (in *México*) all represent the single phoneme /x/. The book
uses IPA with two self-declared deviations: /r̄/ for the "strong r" (trill) to distinguish from /ɾ/
(tap), and an acute accent on every stressed syllable (not just orthographically accented ones).

An **alófono** is a concrete phonetic realization/variant of a phoneme (written in brackets [ ]
vs. phonemic slashes / /). Classic example: Sp. /d/ has an occlusive allophone [d] (after pause/
nasal) and an approximant allophone [ð] (intervocalic) — e.g. *dedo* → [déðo]. A **transcripción
fonética estrecha** (narrow) includes fine allophonic detail; **amplia** (broad) includes only the
main allophones. Phonemic contrasts in one language can be mere allophonic variation in another
(Sp. /d/~[ð] is one phoneme; Eng. /d/ vs. /ð/ in *dough* vs. *though* are two phonemes) — this
cross-linguistic-asymmetry point (also illustrated with Eng. /t/~[ɾ] "flapping" vs. Sp. /ɾ/ as an
independent phoneme) is the book's running pedagogical device throughout the chapter.

### Variación libre vs. distribución complementaria (pp. 51–52)

Two allophones are in **distribución complementaria** when they occur in mutually exclusive
contexts (e.g. dialectal [ŋ] word-finally vs. [n] elsewhere). Two allophones are in **variación
libre** when they can occur in the identical context without meaning change — the book notes true
free variation is rare; most apparent cases (e.g. Spanish /s/-aspiration [s]~[h], English /t/
flapping) are really **variación estilística** (stylistic variation correlating with formality), not
truly free. A case of genuinely unconditioned free variation cited: some Chilean speakers alternate
[ʃ]~[tʃ] for *ch* with no stylistic value.

### Classification parameters — consonants: point/manner/voicing (pp. 53–65)

**Point of articulation** (punto de articulación): bilabial [p,b,m], labiodental [f], (ápico)dental
[t,d], (ápico)alveolar [n,l,ɾ,r̄], (predorso-)alveolar [s̄] (the general Spanish-American/southern-
Spain articulation of /s/, vs. ápicoalveolar [ś] in northern-central Spain — the book explicitly
flags this as a dialectal articulatory split even where the orthographic/phonemic outcome is
identical), (predorso-)palatoalveolar/prepalatal [tʃ], (dorso)palatal [ɲ,ʝ,ʎ], (dorso)velar [k,g,x].

**Manner of articulation** (modo de articulación): oclusivas (stop: full closure + release) [p,t,k,
b,d,g]; fricativas (continuous turbulent airflow) [f,s,θ,ʃ,x]; africadas (stop+fricative release)
[tʃ]; aproximantes (narrowed but non-turbulent channel) [b̞,ð,ɣ] — the allophones of /b,d,g/;
nasales [m,n,ɲ,ŋ]; laterales [l]; vibrantes, split into simple (single tap) [ɾ] and múltiple
(2-3 taps) [r̄]. Cover terms: **líquidas** = laterals+vibrants; **resonantes/sonorantes** =
nasals+liquids; **obstruyentes** = stops+fricatives+affricates.

**Voicing** (sonoridad): sonoro (voiced, vocal-cord vibration) vs. sordo (voiceless). Spanish
voiceless stops are never aspirated (unlike English word-initial/stressed-intervocalic [pʰ]) — a
systematic single-allophone-per-phoneme contrast with English's two-allophone pattern.

### Vowel classification (pp. 65–66, 88–90)

Three parameters: tongue height (alta /i,u/, media /e,o/, baja /a/), frontness (anterior /i,e/,
central /a/, posterior /o,u/), and lip rounding (redondeada /o,u/ vs. no redondeada /i,e,a/ — noted
as a redundant feature in Spanish, unlike French/German which have front rounded vowels, or
Japanese's unrounded back high vowel). Spanish vowels are **pure** (non-diphthongizing) and hold
their timbre in unstressed syllables, unlike English, Catalan, or Portuguese reduced/diphthongized
vowels. English has 10-11 vowel phonemes (tense/lax pairs, a central /ʌ/, two low vowels
/æ/,/ɑ/) vs. Spanish's 5 — explicitly framed as cross-linguistic contrast for L2-pedagogy purposes
but presented as a formal phonological fact, not a usage tip.

### Phoneme-by-phoneme consonant inventory with dialectal allophony (pp. 67–87) — HIGH DIALECTAL VALUE

This is the single richest block of explicit regional/dialectal annotation in the chapter (see
Vocabulary table below for a tabulated digest of named phenomena):

- **Oclusivas sordas /p,t,k/**: never aspirated (contra English); /k/ fronted before /i,e/. Peninsular
  Spanish /t/ is dental (English alveolar). Caribbean/Peninsular colloquial speech can partially/fully
  voice intervocalic /p,t,k/.
- **Oclusivas sonoras /b,d,g/**: oclusiva allophone after pause/nasal; **aproximante** [b̞,ð,ɣ]
  (not simply "fricative" — the book is explicit that insufficient friction is produced) elsewhere,
  with a detailed allophone-distribution table by preceding segment (Tabla 2.7): after /l/, /d/ stays
  occlusive but /b,g/ go approximant (asymmetry explained by /l,d/ sharing a point of articulation);
  Central American/Colombian dialects generalize occlusives after all consonants. **-ado participle
  /d/-elision** ([kantáo]) is widespread colloquial Spain/parts-of-Latin-America, judged "vulgar" esp.
  in Latin America; fuller intervocalic /d/-elision (*comido*→[komío]) found in Andalusia/Caribbean.
  Word-final /d/ (verdad, etc.) varies by region: soft approximant/elided generally; [t] in
  Catalonia/Valencia and emphatic South American speech; voiceless [θ] in north/central Spain.
  Syllable-final stop devoicing/voicing is neutralized entirely (*apto* ~ [ábto]~[ápto], formalized
  as archiphoneme /P/). Cuba/Dominican Republic/Colombia show emphatic velarization of syllable-final
  stops (*submarino*→[suɣmaríno]); north/central Spain devoices final /g/ to [x] (*digno*→[díxno])
  and some sociolects pronounce syllable-final *c* as [θ] (*dictado*→[diθtáðo]); some Mexican
  speakers merge /ks/,/ps/→/ts/ (*Pepsi*→[pétsi]).
- **Fricativas sordas**: /f/ (labiodental; a bilabial [ɸ] variant attested in "diverse zones");
  **/θ/ interdental exists only in Spain** (north/central) — minimal pairs *ves*/*vez* ([bés]/[béθ]);
  **/s/** articulation itself splits dialectally: ápicoalveolar in northern Spain vs. predorso-alveolar
  in the rest of the Spanish-speaking world (symbols [ś] vs [s̄] in dialectology, though the book
  collapses both to [s] in its own transcriptions); voicing assimilation [z] before voiced consonant
  in north/central Spain and Mexico (*desde*→[dézðe]); **s-aspiration/elision** ([s]→[h]/∅ before
  consonant or finally) is "characteristic of Caribbean and Andalusian Spanish, but found in other
  areas too" (*mosca*→[móhka]); **/x/** ranges from uvular [X] (north Spain) to soft laryngeal [h]
  (parts of Andalusia/Caribbean) to a Chilean palatalized [ç] before front vowels (*gente*→[çénte]).
- **La obstruyente palatal (/ʝ/) — yeísmo/lleísmo/žeísmo, HIGH DIALECTAL VALUE**: general Spanish has
  one palatal obstruent phoneme /ʝ/ (for both *y* and *ll*) with an approximant/fricative allophone
  [ʝ] (intervocalic) and an occlusive/affricate allophone [ɟ] (after nasal/lateral). **Lleísmo**
  (a separate lateral phoneme /ʎ/, contrasting *cayó*≠*calló*) survives only in rural Spain and the
  Andes (Bolivia, Peru, Ecuador, Colombia) plus Paraguay, and is receding even there among younger
  speakers. **Žeísmo**: in parts of Argentina/Uruguay, both *y* and *ll* are realized as a strident
  prepalatal fricative [ʒ] (*playa*→[pláʒa]), with devoicing to [ʃ] spreading among young Buenos
  Aires speakers (*playa*→[pláʃa]). Crucially, žeísta dialects preserve a **minimal pair based purely
  on etymological spelling**: *hierba* [i̯éɾba] (with semivowel, from historic *hi-*) vs. *yerba*
  (*mate*) [ʒéɾba] (full fricative) — an orthography-driven phonemic split unique to this dialect
  area.
- **Consonantes africadas /tʃ/**: fronts to alveolar [ts] in parts of Chile and (recently) among
  young speakers in the Basque Country; fully palatal "ch adherente" [c] in the Canary Islands;
  de-affrication to fricative [ʃ] in northern Mexico, parts of Andalusia, Panama, and Chile. Marginal
  phoneme /ts/ (spelled *tz*) in *quetzal* and some Mexican/Central-American toponyms.
- **Consonantes nasales**: 3 phonemes /m,n,ɲ/, neutralized word-finally to /n/ (**neutralización de
  nasales**); velarization of word-final /n/→[ŋ] is "widespread across large zones of both Latin
  America and Spain" but absent from the socially dominant dialects of Spain, Mexico, Argentina; full
  place-assimilation before a following consonant (**asimilación de nasales**, Tabla 2.9).
- **Consonantes laterales**: single phoneme /l/ generally (never velarized, unlike English's
  clear/dark [l] allophony); /ʎ/ survives only in the lleísta zones above (Andes: Bolivia, parts of
  Peru/Ecuador/Colombia, plus Paraguay and parts of Spain).
- **Consonantes vibrantes**: /ɾ/ (tap) vs. /r̄/ (trill) contrast only intervocalically within a word
  (*caro*/*carro*); neutralized elsewhere per Tabla 2.10. Dialectal variants: voiceless/weakened
  final /ɾ/ in Mexico (socially variable); fricative alveolar [ř] in Andean regions and parts of
  Argentina; dorsal/uvular trill [ʁ] in parts of Puerto Rico (resembling north-Spain /x/); pre-aspirated
  apical [ɦr] in the Dominican Republic/Caribbean; coarticulated /tɾ/→[tɹ] (resembling English "tr")
  in Chile, Costa Rica, and parts of Navarre/La Rioja. **Neutralización de líquidas** (lateral/
  vibrant merger before consonant or word-finally, so *harto*=*alto*) found in parts of Andalusia
  (merging to [ɾ]) and Puerto Rico (merging to [l]-like realizations).

### Archifonema (pp. 85–87, Prague School concept, starred/optional section)

Where two phonemes' contrast is fully neutralized in a given position, the Prague-School-derived
**archifonema** (capital-letter notation, e.g. /N/, /R/, /P/) represents the neutralization result
rather than assigning the segment to one phoneme or the other. Worked Spanish examples: /N/ for the
three-way nasal neutralization pre-consonantally (*énfasis*=/éNfasis/) — though the book argues
word-final neutralization actually resolves in favor of /n/ specifically (shown by paradigmatic
alternation: *algún* → *alguna*); /R/ for the tap/trill neutralization outside intervocalic position
(though the book similarly argues this resolves to /ɾ/ word/morpheme-finally, by the same
alternation logic — *amor* → *amores* always [ɾ]); /P/ for final-stop sonority neutralization
(*apto* = /áPto/).

### Vowel sequences: diphthongs, hiatos, triphthongs (pp. 88–95)

**Diptongo** (two vowels in one syllable, one of them reduced to a semivowel [i̯] or [u̯]) vs.
**hiato** (two vowels in separate syllables). Diphthongs split into **crecientes** (rising:
semivowel+vowel, e.g. [i̯a, u̯e]) and **decrecientes** (falling: vowel+semivowel, e.g. [ai̯, eu̯]).
Spanish has more diphthong types than English, including rising diphthongs rare in English
(*San Diego* = 3 Spanish syllables vs. 4 English ones). A non-high+non-high vowel sequence is always
hiatus (*poeta, teatro*); when one vowel is high (i/u) and unstressed, it's normally a diphthong,
with the orthographic accent specifically marking the exceptional hiatus reading (*María, oído* vs.
*Mario, pie*) — **this orthographic-accent rule is the formal mechanism, not an arbitrary spelling
convention**. Dialectal note: some (mainly Peninsular) speakers maintain a phonemic hiatus/diphthong
contrast even without orthographic marking in unstressed-high-vowel contexts (*huida* [u.í.ða], 3
syllables, vs. *cuida* [kui̯.ða], 2 syllables) — extent of this contrast in Latin America is
explicitly flagged by the book as undetermined. **Triptongos** (semivowel+vowel+semivowel, e.g.
*buey*, *Paraguay*) are rare, occurring mainly in now-archaic *vosotros* verb forms.

### Section 5.4 ¿Un fonema menos? — starred, two competing phonological analyses (pp. 96–97)

Presents a genuine unresolved debate: should /ʝ/ be an independent consonant phoneme (análisis A),
or is it simply a strengthened allophone of the vowel/semivowel /i/ requiring only a syllable-
boundary diacritic in a handful of exceptional words like *deshielo* vs. *desierto* (análisis B)?
The book presents both analyses side by side (Tablas 2.18–2.19) without adjudicating, explicitly
flagging it as "uno de los puntos más debatidos en el análisis fonológico de la lengua española."
Note: análisis B does not extend to žeísta dialects (Argentina) which have a genuine 3-way contrast.

### La contracción silábica: sinalefa and sinéresis (pp. 98–100)

In fast/colloquial speech, vowel hiatuses reduce to one syllable — **sinalefa** across word
boundaries (*mi amigo* → [mi̯amíɣo]), **sinéresis** within a word (*toalla* → [toa̯ʝa]). Rule: if the
two vowels differ in height, the higher one becomes the semivowel; if equal height, generally the
first becomes the semivowel; identical vowels can reduce to one. This reduction is formally counted
in Spanish poetic meter (worked examples from Espronceda's "Canción del pirata" and Miguel
Hernández's "Nanas de la cebolla" are cited and syllable-counted in the source, not reproduced here
verbatim). In extreme cases, sinéresis can shift stress onto the more open vowel of the resulting
diphthong (*serían* → [serjã́n]).

### Syllabification principles (pp. 100–103)

VCV always syllabifies V.CV (consonant attaches to the following vowel). VCCV syllabifies V.CCV if
the cluster is a legal word-initial cluster in Spanish (stop/f + liquid: /pr,tr,kr,fr,pl,kl,fl,br,
dr,gr,bl,gl/, notably **not** /dl/, and /tl/ only in Mexican Nahuatl-derived words) — otherwise
VC.CV. Three+ consonant clusters follow the same "maximal legal word-initial sequence" principle,
explicitly contrasted with English: Spanish disallows word-initial /st-/, /sp-/, so *insiste*
syllabifies in.sis.te not *in.si.ste, and *instruye* → ins.tru.ye. Cross-word resyllabification:
word-final consonant + following word-initial vowel resyllabify together (*los amigos* →
[lo.sa.mí.gos]) — this does NOT apply before a semivowel-initial word like *hierba* (*las hierbas* ≠
*la salas* despite looking parallel), giving the book's minimal-pair-style illustration *la hierba*
vs. *la sierva*.

### Stress (acentuación) — prosodic patterns and orthographic rules (pp. 103–111)

**Acento prosódico** (phonetic stress) vs. **acento ortográfico** (the written accent mark) are
explicitly distinguished — the orthographic mark only appears on some stressed syllables. Three
stress-position classes, all within a strict "three-syllable window" from the word's end: **agudas/
oxítonas** (final-syllable stress), **llanas/paroxítonas** (penultimate), **esdrújulas/
proparoxítonas** (antepenultimate) — no other pattern is possible in Spanish (hypothetical
4th-from-end stress patterns are categorically impossible). Constraint: no esdrújula word has a
closed (consonant-final) or diphthong-containing penultimate syllable (hence *alófono* but not
*\*alómorfo*) — traced to Latin stress rules (Ch.5), with exceptions only in foreign-origin names/
loans (*Wáshington*, *Frómista*). Verb stress follows separate, largely morphological rules distinct
from noun/adjective stress: present tense stress is always penultimate except *vosotros* (final);
no verb is ever antepenultimate-stressed in the present (contra nouns: *número* vs. verb *numero*);
**estar** is the lone irregular exception (*estoy, estás, está* — traced to the loss of Latin initial
unstressed *e-*: *stāt* > *está*). Preterite/imperfect and future/conditional show **acento
morfológico** ("columnar" stress fixed to a specific morpheme — the syllable right after the root
for preterite/imperfect, the syllable starting with the future/conditional *-r-* marker — rather
than counted from the word's end).

**Orthographic accent rules (7.2, pp. 108–111)**: (i) all esdrújulas are written with an accent;
(ii) llana words ending in a consonant other than -n/-s are accented (the -n/-s exception exists
because those consonants are usually plural/verbal-person markers, and marking them would be
orthographically uneconomical); (iii) polysyllabic agudas ending in a vowel, -n, or -s are accented;
(iv) a set of special rules disambiguates hiatus from diphthong using the accent specifically when
stress falls on a high vowel adjacent to another vowel (*María* vs. *Mario*) — but the hiatus/
diphthong contrast is NOT marked when both vowels are high (*huida* and *cuida* are both unaccented
despite a syllable-count difference for some speakers); (v) **acento diacrítico** distinguishes
otherwise-identical word pairs (Tabla 2.24: *más*/*mas*, *mí*/*mi*, *él*/*el*, *qué*/*que*, *tú*/*tu*,
*té*/*te*, *sí*/*si*, *sé*/*se*, *aún*/*aun*), and marks interrogative/exclamative pronouns
(*qué, quién, cuál, cuánto, cuándo, cómo*) including in indirect questions.

### Intonation (section 8, pp. 111–118)

Declarative sentences: non-final stressed syllables carry a sharp low-to-high rise beginning at the
tonic syllable; the sentence-final stressed syllable instead peaks *within* the tonic syllable and
falls on the post-tonic — i.e. **sentence-final declaratives are characterized by a tonal fall
starting from the last stressed syllable**. A sustained (non-falling) final tone marks continuation
(*llegaron mis amigos, pero no mi abuelo*). **Information-structure/intonation interface**: Spanish
default word order places known information before new information; the known-information
constituent's final syllable carries a tonal peak (*¿Quién viene mañana?* → *Mañana viene MARÍA*,
peak on *-ne*). When new information is fronted for contrastive emphasis, a special marked contour
applies — wide pitch excursion on the emphasized word's stressed syllable, followed by a sustained
fall to the end (*No, MARÍA viene mañana*). **Interrogatives** (8.3): total/yes-no questions
generally show a final rise (low tone on the last stressed syllable, rise on the post-tonic) — but
with notable dialectal variation: **Caribbean Spanish uses a circumflex (rising-then-falling)
contour as its unmarked question intonation**, which can cause speakers of other dialects to
mis-hear Caribbean questions as statements; similar falling-type question contours (though
structurally different) also occur in northwest Spain (Asturias, Galicia) and Argentina. Pronominal
(wh-)questions use the same falling contour as declaratives, with the peak on the question word
itself; a final rise in a wh-question instead signals insistence/uncertainty.

### Relation between stress and intonation (section 9, p. 118)

The stressed syllable functions as an "anchor point" for the tonal melody rather than always being
the highest-pitched syllable itself — what defines tonic status is the *potential* to anchor a
tonal movement (a rise, or in interrogatives a low-then-rise), not a fixed pitch height. Not every
lexically stressed syllable in a sentence is tonally individuated — emphasis can be reduced or
omitted on non-final/de-emphasized words. Secondary stress (e.g. two syllables before the tonic, in
formal/broadcast registers) is also tonally marked in careful speech.

---

## Vocabulary — Chapter 2 dialectal/phonological terms (high regional-annotation value)

All rows: `Part of Speech = noun (technical term)`, `Usage Tier = technical.linguistics`,
`Source Type = grammar_reference`, `Transcription Confidence = n/a`, `Vision Reading Confidence =
n/a`, `Weight/Frequency = —`, `Attested Era = contemporary (source published 2009/2010)`.

| Term | Gloss | Attested Region | Geographic Scope | Notes |
|---|---|---|---|---|
| seseo | pronunciation of orthographic z/c(e,i) as [s] rather than [θ] | all of Latin America, Canary Islands, parts of southern Spain | transnational | The general-Latin-American norm; contrasted with distinción (p.46-74). |
| distinción (s/θ) | maintenance of the /s/–/θ/ phonemic contrast (ves≠vez) | north and central Spain | regional | p.74; minimal pairs ves/vez, rosa/roza. |
| yeísmo | merger of /ʝ/ and /ʎ/ into a single non-lateral palatal phoneme (cayó=calló) | vast majority of the Spanish-speaking world today | transnational | p.76; described as the now-dominant, still-spreading norm. |
| lleísmo | retention of a separate lateral palatal phoneme /ʎ/ (cayó≠calló) | rural Spain; Andes (Bolivia, parts of Peru/Ecuador/Colombia); Paraguay | regional | p.76; explicitly noted as receding, mainly among older/rural speakers. |
| žeísmo | realization of /ʝ/ as a strident prepalatal fricative [ʒ] | parts of Argentina and Uruguay | regional | p.76; devoicing to [ʃ] spreading among young Buenos Aires speakers. |
| aspiración de /s/ | realization of syllable/word-final /s/ as [h] or its full elision | Andalusia, Canary Islands, Caribbean Spanish, "and other areas" | regional (wide, non-contiguous) | pp.51, 74; stylistically conditioned — [h]/elision more informal, [s] more formal in some varieties. |
| velarización (nasal) | realization of word-final /n/ as [ŋ] | "widespread zones of both Latin America and Spain," but absent from the socially dominant varieties of Spain, Mexico, Argentina | transnational | p.78. |
| neutralización de líquidas | merger of lateral /l/ and vibrant /ɾ/ before consonant/word-finally (harto=alto) | parts of Andalusia (→[ɾ]); Puerto Rico (→[l]-like) | regional | p.82. |
| ch → [ts] (fronting) | fronting of the affricate /tʃ/ to alveolar [ts] | parts of Chile; recently also young speakers in the Basque Country | regional | p.77. |
| ch adherente | fully palatal articulation [c] of /tʃ/ | Canary Islands | regional | p.77. |
| ch → [ʃ] (de-affrication) | loss of the occlusive element of /tʃ/, yielding fricative [ʃ] | northern Mexico, parts of Andalusia, Panama, Chile | regional | p.77. |
| /x/ uvular [X] | strongly-fricated uvular/postvelar realization of /x/ | north of Spain | regional | p.75. |
| /x/ laryngeal [h] | soft laryngeal realization of /x/ | parts of Andalusia and the Caribbean | regional | p.75. |
| /x/ palatalized [ç] | palatal fricative realization of /x/ before front vowels/semivowels | Chile | regional | p.75; gente→[çénte]. |
| coarticulated /tɾ/ → [tɹ] | /tɾ/ cluster coarticulated to resemble English "tr" | Chile, Costa Rica; parts of Navarre (Ribera del Ebro) and La Rioja in Spain | regional | p.82. |
| vibrante dorsal/uvular [ʁ] | dorsal/uvular (rather than apical) realization of the multiple trill | parts of Puerto Rico | regional | p.81-82; resembles north-Spain /x/. |
| pre-aspirated apical trill [ɦr] | pre-aspirated voiced apical realization of /r̄/ | Dominican Republic and other parts of the Caribbean | regional | p.82. |
| fricative alveolar [ř] (trill variant) | fricative-alveolar realization of the vibrant | Andean region; parts of Argentina | regional | p.81. |
| apertura vocálica ante /s/ aspirada | extra-opening of mid vowels before aspirated/elided final /s/, preserving the singular/plural distinction (libro vs. libros) even once /s/ itself is lost | eastern Andalusia (Granada area), Murcia | regional | p.89 — a genuinely striking phonological compensation strategy worth flagging for the mechanics-analysis phase. |
| -ado participle /d/-elision | elision of intervocalic /d/ in -ado participles (cantado→[kantáo]) | Spain and parts of Latin America (colloquial); judged more stigmatized in Latin America | transnational | p.71. |
| intervocalic /d/-elision (general) | broader elision of intervocalic /d/ beyond -ado (comido→[komío], todo→[tó]) | Andalusia, parts of the Caribbean, other regions | regional | p.71-72. |

## Chapter 3 — La estructura de las palabras: morfología (pp. 123–200) — NON-REDUNDANT SUPPLEMENT

Author: Anna María Escobar & José Ignacio Hualde. Per the dispatch's non-redundant-supplement
rule: **section 2 (flexión nominal/verbal — gender/number/verb-paradigm inflection) is almost
entirely SKIPPED** as it duplicates conjugation/agreement paradigms already thoroughly covered by
`005_practice_makes_perfect_basic_spanish_grammar.md`, `006_..._advanced_spanish_grammar.md`,
`007_..._irregular_verbs.md`, and the `008*_verb_tenses`/`009*_vocabulary` files. **Section 1
(basic morphological concepts), section 3 (derivation), section 4 (compounding), section 5
(abbreviation/acronyms), and section 6 (hierarchical word structure) are extracted in full** — this
is the formal morphological-analysis framework (root/affix/base, derivational typology,
compounding structural types, truncation/clipping processes) that no pedagogical grammar in this
project's corpus presents, and which the mechanics-analysis phase can use directly.

### Basic concepts (section 1, pp. 123–136)

**Concepto de palabra**: the book flags genuine edge cases in defining "word" for Spanish — clitic
pronouns are one orthographic word pre-verbally but written fused post-verbally (*se lo quiere
vender* vs. *quiere vendérselo*, both 4 morphological words); compounds like *hombre rana* fail the
"sum of parts" semantic test and block insertion (*\*un hombre bastante rana*); *-mente* adverbs
carry two lexical stresses and can be "shared" across a coordination (*lenta y cuidadosamente*);
contractions *del*, *al* are one phonological word but two syntactic/morphological words.

**Distributional (not notional) definitions of word classes** — explicitly framed as more useful
than the traditional logic-based noun=substance/adjective=accident definitions: a noun is "whatever
can follow *el/la*" (so *destrucción* is a noun despite denoting an action); a verb is "whatever
conjugates for tense/aspect" and can follow *no* or *Prefiero que...*; an adjective is "whatever can
follow *muy* and inflects for gender/number" (*azul* can nominalize: *el azul*); adverbs follow
*muy* but never inflect (*rápidamente*, *cerca*). Open classes (N, Adj, V) vs. closed classes
(prepositions, conjunctions, pronouns) — the book notes closed-class membership is exhaustively
listable, open-class is not (gives *chavista*, *tajabarda* as spontaneously coinable open-class
items).

**Morfema** = minimal meaningful unit; **raíz** (root) vs. **afijo** (affix, always bound);
**sufijo**/**prefijo** by position; **parasíntesis** = simultaneous prefix+suffix attachment where
neither affix alone attaches to that base (*en-tristec-er* from *triste*, since neither *\*entriste*
nor *\*entristecer*-minus-prefix *\*tristecer* exist independently). **Base** = what an affix
attaches to (root, or root+other affixes) — *región-al-ismo* has base *región* for *-al*, then base
*regional* for *-ismo*. **Morfemas léxicos** (real-world-referring: all N/Adj/V roots) vs.
**morfemas gramaticales** (system-internal: pronouns, conjunctions, prepositions, all affixes).

**Sufijos derivativos vs. flexivos** — five formal diagnostics given: (i) derivation changes the
referent (*higo*→*higuera* "fig tree," not the fruit); inflection doesn't (*perro*→*perros* still
dogs); (ii) derivation can change word class, inflection never does; (iii) inflection is fully
general/productive (every noun pluralizes by regular rule), derivation is lexically restricted
(*alto*→*altura*, *gordo*→*gordura*, but *delgado*→*delgadez* not *\*delgadura*; no adjective
derives from *edificio*); (iv) only inflection has syntactic relevance (agreement); (v) formal
test: unstressed final noun/adjective vowels (-o/-a/-e) are themselves inflectional suffixes, not
part of the root, shown by their disappearance before a derivational suffix (*libro*→*libr-ero*,
*mesa*→*mes-ero*) — **except** *-mente* adverbs, which uniquely retain a gender vowel between root
and derivational suffix, attaching to the feminine adjective form specifically, a historical relic
of the Latin phrase *mente* ("with a X mind") now grammaticalized as a suffix.

**Palabras simples / derivadas / compuestas**: three-way structural typology. Note on
**interfijos** (empty linking elements with no independent meaning, inserted between root and a
known suffix) — e.g. *cafe-t-era* (not *\*cafeera*), *pan-ad-ero* (not the expected *\*panero*,
by analogy to *fruta→frutero*).

**Morfemas libres y ligados**: Spanish differs structurally from English in that most Spanish
noun/adjective/verb roots are **bound** — they cannot surface without an inflectional suffix
(*\*gat* is impossible; only *gato, gata, gatuno*; verb roots almost never appear bare except
irregular imperatives like *ven, sal, pon*) — contrasted explicitly with English, where most roots
surface as free independent words (*cat, good, sell*). This is a structural typological fact likely
relevant to mechanics-analysis work on word-formation constraints.

**Alomorfos**: allomorph is to morpheme as allophone is to phoneme. Phonologically-conditioned
example: plural suffix /-s/~/-es/. Purely morphologically-conditioned example: preterite-stem
allomorphy (*poner*→*pus-*, *tener*→*tuv-*, *ser*→*fu-*) unpredictable from phonology alone.

### Derivation (section 3, pp. 166–188) — EXTRACTED IN FULL, high slang-formation relevance

**General properties of Spanish derivational morphology** (pp. 166-168): root-form alternations
under derivation are irregular in distribution (diphthong-reduction in unstressed syllables
applies inconsistently: *cuento*→*cuentista* keeps the diphthong but *bueno*→*bondad* reduces it);
some root allomorphy is a frozen relic of Latin-vs.-vernacular doublets (*joven/juvenil*,
*vida/vital*, *leche/lácteo*, *frente/afrontar*, *dedo/digital*, *humo/fumar*, *hijo/filial* — the
derived form is phonologically closer to Latin, the base form has undergone more sound change,
foreshadowing Ch.5's historical material); **interfijos** recur as a structural wrinkle throughout;
derivational suffix choice is lexically arbitrary and not fully predictable (*primavera→primaveral,
otoño→otoñal, invierno→invernal* but *verano→veraniego*, not *\*veranal*).

**Sufijos emotivos/apreciativos (diminutive/augmentative/pejorative) — HIGH VALUE for slang
mechanics, with explicit dialectal distribution**:
- **Diminutive -ito/a** (with allomorphs -cito/-ecito): primary meaning small size; secondary
  meanings — affection (*mi abuelita*), lesser importance/quality (*librito*, *abogadito*), and
  politeness/humility hedging (*¿una tacita de café?*, *¿un ratito?*) — can also carry irony
  (*¡Vaya una nochecita!*). Productive even on adverbs (*ahorita, cerquita, lejitos, despacito*) and,
  in heavy-diminutive-use dialects, even on numerals/pronouns/non-finite verb forms (*unito,
  dosito, ellita, callandito*).
  - **Dialectal note**: diminutive-use *intensity* itself varies regionally — "particularly
    frequent in the Andean region and Mexico," extending to numerals/pronouns there.
  - **Alternative diminutive -illo**: "particularly frequent in Andalusia and parts of South
    America."
  - **Alternative diminutive -ico**: "frequently used in Central America, Colombia, the Caribbean,
    Extremadura, and Aragón."
  - Minor diminutives: **-ín/a, -ete/a, -uelo/a** (less used).
- **Augmentative -ón/a, -ote/a, -azo/a** (primary meaning large size; secondary: admiration or
  disdain/exaggeration, e.g. *¡Tienes un jefazo!* vs. *Juan es un animalote*).
  - **-azo is "more widespread in South America."**
  - **-ote is "more common in Mexico."**
  - (Note: augmentative -azo is distinct from the homophonous "blow/hit with N" suffix -azo, e.g.
    *guantazo* "hit with a glove.")
- **Pejorative-only suffixes**: -ucho/a, -acho/a, -ajo, -ejo/a, -aco/a, -ongo/a (e.g.
  *perro→perrucho*, *casa→casucha*, *pueblo→poblacho*); also -oide in its pejorative extension
  (*sentimentaloide*).
- **Lexicalized emotive-suffix forms with opaque/shifted meaning**: *caja→cajón*, *rata→ratón*,
  *paño→pañuelo*, *cama→camilla*, *lente→lenteja*, *color→colorete* — the diminutive/augmentative
  connection is etymologically real but synchronically opaque to speakers; flagged because this is
  exactly the kind of semantic drift the slang-synthesis pipeline models.

**Nominalización** (3.2, pp. 172–178): three types by base —
- **Denominal N→N**: -ada (*burrada* "donkey-like act," *cucharada* "spoonful," *puñalada* "stab
  wound" — three distinct subsenses of one suffix: action-typical-of-N, "fits-in-N" measure, and
  "blow with N"), -aje (collective: *plumaje*; social relation: *vasallaje*), -al/-ar (locative
  collective, esp. "place abundant in plant N": *pinar, naranjal*), -azo ("blow with N," distinct
  from augmentative -azo), -ero/a (occupation, *frutero*; or container/place, idiosyncratically
  gendered: *frutero* the bowl but *ensaladera* the salad bowl), -ería (establishment/trade,
  *librería*), -ista (profession/affiliation/tendency, gender-flexible: *el/la pianista*), -ismo
  (doctrine/ideology: *capitalismo, machismo*, can attach to proper names: *leninismo*).
- **Deadjectival Adj→N** ("quality of being Adj"): -dad/-idad/-edad/-tad (*crueldad, falsedad,
  lealtad* — the -tad allomorph is irregular/limited), -ería (mostly pejorative qualities:
  *tontería*), -ez/-eza (*rojez, nobleza*), -ia (regularly from -nte/-nto adjectives via -nt-e/-o→
  -nc-ia: *elegante→elegancia*), -ura/-or (near-interchangeable: *blancor~blancura*), -(i)tud
  (*lentitud, juventud*).
- **Deverbal V→N**: two subtypes — "action/effect of V" (bare thematic-vowel nominalization with no
  derivational suffix at all, e.g. *buscar→busca, combatir→combate, cargar→cargo*; also petrified
  past participles used as nouns, *dictado, caída, vista*; plus suffixes -ción/-sión, -dura,
  -ncia/-nza, -miento/-mento) and "agent" (-dor/a, which can double as "place where V typically
  happens," *comedor* = both "big eater" and "dining room"; -nte, mostly yields adjectives rather
  than nouns in practice).

**Adjetivación** (3.3, pp. 178–183): — note the **gentilicios (demonyms) section is itself
dialectal/geographic-naming data worth flagging**, since it's exactly the kind of regional
onomastic pattern the extraction spec treats as high-value:
- **Gentilicio suffixes** (demonym-forming, from place names), with strong regional specialization
  in which suffix attaches where: -ano/a (*boliviano, mexicano, americano* — one of the most
  productive), -ense (*costarricense, canadiense, estadounidense* — also very productive), -eño/a
  (*puertorriqueño, brasileño, salvadoreño* — also very productive), -és/a (*francés, portugués,
  danés* — also very productive), **-(t)eco/a used exclusively for Mexican and Central American
  place names** (*guatemalteco, yucateco, zapoteco*), **-í used specifically for North African and
  Asian demonyms** (*marroquí, iraní, paquistaní, israelí*), plus many single/limited-use suffixes
  (-ino/a, -eno/a, -ín/a, -ita, -eta, -ota, -ica, -enco/a, -al, -o/a as in *paraguayo, uruguayo*).
  Demonym form is explicitly flagged as **unpredictable from the toponym** — irregular stem changes
  (*Madrid→madrileño*, *Buenos Aires→bonaerense*, *Ávila→abulense*, *Salamanca→salmantino*,
  *Polonia→polaco*), totally unrelated roots in extreme cases (*Badajoz→pacense* from Latin *Pax
  Augusta*; *San Sebastián→donostiarra*, borrowing the Basque demonym for Donostia), and even two
  places sharing a name can diverge (*Cuenca, Ecuador→cuencano* vs. *Cuenca, Spain→conquense*).
- Adjectives from personal proper names: -iano/a (*kantiano, chomskyano*), -ista (*marxista*,
  ambiguous between "partisan of" and merely "related to"), -ico (preaccenting: *platónico*),
  -esco/a ("in the manner of": *quijotesco*).
- Common-noun-based adjective suffixes: -al/-ar, -ero/a, -il, -ico/a (preaccenting, heavy technical
  use), -oso/a, -udo/a (often pejorative/exaggerative: *orejudo* = "has disproportionately big
  ears," not neutrally "has ears").
- Deverbal adjectives: -ble (highly productive, "can/should be V-ed"), -nte, -dor/a, -(t)ivo/a,
  -(t)orio/a.
- Deadjectival Adj→Adj: mainly color-approximation suffixes, lexically idiosyncratic and
  non-interchangeable (*verdoso* but not *\*rojoso*; *rojizo* but not *\*verdizo*; *azulado* but not
  *\*amarillado*) — *blanco→blancuzco/blanquecino*, *negro→negruzco*, *amarillo→amarillento*.
- Deadverbial Adv→Adj: a small closed set (*cerca→cercano, lejos→lejano, tarde→tardío*).

**Verbalización** (3.4, pp. 183–185): bare N/Adj→V (always 1st conjugation, no derivational suffix
at all beyond the infinitive inflection itself: *alfombra→alfombrar*); the **productive modern
process uses derivational -e-**, "especially with loanwords" (*lonchear, parquear, faxear* — i.e.
this is the live mechanism for incorporating English loanwords as Spanish verbs, directly relevant
to contact-induced slang formation); **parasíntesis** (simultaneous prefix+suffix, formally defined
with the *des-/a-/en-* prefix set: *desplumar, amotinar, empapelar* — crucially *neither* the bare
prefixed form nor the bare suffixed form exists alone, e.g. no *\*rojecer* nor *\*enrojo* exists
independent of *enrojecer*); -ific(ar)/-iz(ar) (*ejemplificar, modernizar* — productive); the
2nd-conjugation-forming -ec(er) suffix (adjective-only base, usually with en-/re- prefix:
*enrojecer, envejecer, enloquecer*).

**Adverbialización** (3.5, p. 185): the single productive rule, -mente on the feminine adjective
form, with the morphological peculiarities already noted in section 1 (double stress, suppressible
in coordination: *piadosa, caritativa y bondadosamente*) — traced to its historic origin as the
syntactic phrase *[adjective] + mente* ("with an X mind").

**Prefijación** (3.6, pp. 185–188): prefixes never change word class in Spanish (unlike many
suffixes). Organized by meaning class:
- **Negative**: in-/i- (im- before p/b, i- before l/r: *ilícito*), des- (with allomorph di-:
  *difamar*), a-/an- (*anormal, analfabeto*).
- **Locative/temporal/comitative**: ante-, anti-, circun-, con-/co-, contra-, en-/in- (careful: not
  to be confused with the negative in-), intro-/intra-/entro-, inter-/entre-, ex- (two senses:
  "outward" vs. "former"), extra- (also "to a high degree": *extrafino*), peri-, pre-, pos(t)-,
  retro-, so-/sub-/infra-, sobre-/super-/hiper- (super- generally positive evaluative, hiper- can
  mean "excessive degree," shown by *hipermercado* outranking *supermercado* in size), tra(n)s-,
  ultra-.
- **Valorative/quantity**: re- (two unrelated functions depending on base type — "very/highly" on
  adjective/adverb bases, with a reinforced form *requete-*, competing with *archi-, extra-,
  super-*; vs. "do again" on verb bases); negative-evaluative so- forms (*infrahumano,
  subdesarrollo*) and c(u)asi-/medio/semi-; a full Greek/Latin numeral-prefix inventory for "one"
  through "many/few/big/small" (*uni-, bi-, tri-, cuadri-, quin(qu)-, sex-/hex-, pluri-, multi-/
  poli-, macro-/maxi-/mega-, micro-/mini-*).
- **Other**: auto- (ambiguous between "self" and, via clipping from *automóvil*, "motor vehicle" —
  the book notes *auto* itself became an independent clipped noun: *he comprado un auto nuevo*),
  homo-, hetero-, neo-, proto-, (p)seudo-, vice-/vi-.

### Compounding (section 4, pp. 188–194) — EXTRACTED IN FULL, structural typology

The book gives Spanish a notably smaller compounding inventory than English/Germanic, organized by
structural type (the N+N head-directionality point is a genuinely useful structural contrast
worth flagging):

**Noun compounds**: 
- **N+N→N (*hombre rana* type)**: head is the FIRST noun (opposite of English — compare *mujer
  araña* vs. English "spider-woman," *pez espada* vs. "swordfish") — shown both semantically (a
  *hombre rana* is a kind of man, not a kind of frog) and morphosyntactically (gender agrees with
  the first noun: *el hombre rana*). Exceptions calqued from English put the head second (*ciencia
  ficción*, *drogadicto*) or Greco-Latin technical compounds (*termodinámica*); rare coordinative
  double-headed type (*compraventa* = "compra y venta"). Pluralization differs by lexicalization
  degree: syntagmatic (space-separated) compounds pluralize the first member (*hombres rana*); fully
  fused orthographic compounds pluralize at the end (*telarañas*, even though semantically "webs of
  spider" not "web of spiders").
- **V+N→N (*lavaplatos* type)**: highly productive (*abrelatas, sacapuntas, rascacielos,
  salvavidas*); EXOCENTRIC — the head is external/implicit, not literally present in the compound
  (*el abrelatas* = "the [tool] that opens cans"); can stack (*limpiaparabrisas* = V+[V+N], built
  from *parabrisas* not from a nonexistent *\*limpiaparar* — explicit evidence for hierarchical,
  not merely linear, word-internal structure).
- **N+Adj→N (*hierbabuena* type)**: less productive (*camposanto, aguardiente, nochebuena*).
- **Adj+N→N (*buenaventura* type)**: less productive still (*cortocircuito, altavoz, mediodía*).
- **Adv+N→N (*bienvenida* type)**: rare, adverb is always *bien*/*mal*, second element usually
  deverbal (*bienvenida, malhechor, bienaventuranza*).
- **Prep+N→N (*sinvergüenza* type)**: very rare (*sinnúmero, sinvergüenza*, the humorous *la
  sinhueso* "the tongue," lit. "the boneless one").
- **Greco-Latin technical-root compounds (*morfología* type)**: combinatory roots of Greek/Latin
  origin (ántropo-, bio-, crono-, demo-, filo-, fono-, geo-, grafo-, logo-, metro-, tele-, termo-,
  etc.) that the book argues are genuinely roots rather than affixes, since they can occur in either
  initial or final position (*fonólogo* vs. *gramófono*) and serve as derivational bases themselves
  (*biótico, antropoide*).
- **Synthetic sentence-compounds (*sabelotodo* type)**: rare but structurally striking — an entire
  clause nominalized as one word: *sabelotodo* ← *(él) sabe lo todo*, *metomentodo* ← *(yo) me meto
  en todo*, *correveidile* ← *corre, ve y dile*, *hazmerreír* ← *hazme reír*, *tentempié* ← *tente en
  pie* (a snack "to keep you on your feet"). *Vaivén* (similar structure) is probably a
  Portuguese/Catalan borrowing (*vai e vem*).

**Adjective compounds**:
- **N+Adj→Adj (*pelirrojo* type)**: body-part noun + linking -i- + descriptive adjective, productive
  within its narrow domain of physical description (*carilargo, ojinegro, boquiabierto, patizambo*)
  — EXOCENTRIC, paraphrasable "someone who has N that is Adj." Some lexicalized with metaphorical
  meaning: *manirroto* "spendthrift" (not "broken-handed"), *alicaído* "depressed" (not
  "droopy-winged"), *peliagudo* "very difficult/tricky."
- **Adj+Adj→Adj**: two subtypes — color-blend compounds with linking -i- (*verdinegro,
  blanquiazul*, essentially the same -i- pattern as N+Adj above — not all color adjectives can be
  first members: no *\*azuli-* or *\*amarilli-*); and nationality-compound adjectives using a special
  learned "-o" form for all but the last member (*franco-italiana, hispano-portuguesas,
  anglo-franco-alemán*) — explicitly parallel to the phonological-terminology compounds like
  *labiodental* and to extended uses (*político-financieras, socioeconómicas*). **Orthographic
  hyphenation can be semantically contrastive**: hyphenated *hispano-americano* (a treaty BETWEEN
  Spain and America) vs. fused *hispanoamericano* (belonging TO Spanish America).
- **Adj+N→Adj (*azul turquesa* type)**: color-name + shade-defining noun, invariant for
  agreement (*camisas amarillo limón*, not *\*amarillas limón*).
- **Adv+Adj→Adj**: small set, adverb + deverbal adjective (*altisonante, malavenido*).

**Verb compounds**: the book states flatly **Spanish has NO productive compound-verb-formation
process** — unlike Catalan, which productively compounds N+V. Only two unproductive residual types
survive: **N+V→V** (*maniatar* "to tie the hands," historically from a participle, now nearly the
only living example; *mantener*'s "hold in the hands" sense is now opaque) and **Adv+V→V**, almost
entirely *mal-* compounds (*maldecir, malgastar, malinterpretar*; rare *bien-* forms: *bendecir,
menospreciar*). The book notes explicitly that two verb roots can never combine into one compound
verb in Spanish, even though the result would be logically coherent and more economical (hypothetical
*\*comprivenden* for *compran y venden*) — **this is a hard structural gap in Spanish word-formation,
not an accidental gap**, worth flagging for mechanics-analysis work on what slang-coinage space is
and isn't structurally available.

### Other morphological processes (section 5, pp. 194–196) — EXTRACTED IN FULL, direct slang-formation relevance

**Acortamiento/truncation ("characteristic of informal speech, and youth speech")**: the dominant
pattern keeps the first two syllables with stress moved to the first (*profesor→profe,
universidad→uni, policía→poli, bicicleta→bici, cocaína→coca, televisión→tele, director→dire,
saxofón→saxo*). Some truncations have fully lost their informal register and become the unmarked
default form (*foto, moto, cine, taxi, radio* ← *fotografía, motocicleta, cinematógrafo, taxímetro,
radiofonía*); others remain registrally marked but are broadly accepted (*kilo, auto*). **Explicit
regional restriction**: *zoo* (← *zoológico*) is common even in formal register in Spain but not
used in Latin America. Phrase-level truncation also occurs, very informal (*por favor→porfa*).
Truncating the word-INITIAL part instead (rarer) occurs in *hermano→mano*.

**Hipocorísticos (nickname formation)**, with named phonological processes: ending substituted by
/-i/ (*Javier→Javi, Nicolás→Nico*), loss of postvocalic consonants, /f/→/p/ substitution,
alveolar/dental consonants → /tʃ/ substitution (*Francisco→Pancho, Ignacio→Nacho, Jesús→Chus,
Marcela→Chela*), and medial-syllable deletion keeping first+last (*Pilar→Pili, Manuel→Manolo*).
Anomalous/opaque cases: *Pepe* ← *José* (via an older form *Josep*), *Curro* ← *Francisco*.

**Lunfardo (Buenos Aires slang register) — explicit named regional slang mechanism, HIGH VALUE**:
the book names a distinct morphological process found specifically in lunfardo — **syllable-order
reversal (a form of verlan/backslang)**: *amigo→gomia*, *café con leche→feca con chele*. This is
flagged by name as belonging to a specific regional popular register, exactly the kind of
register-tagged mechanism the slang-synthesis project models directly.

**Siglas (acronyms/initialisms)**: function syntactically as nouns; gender/number is inherited from
the first noun of the unabbreviated phrase (*la ONU*, *el SIDA*) — for acronyms of foreign-origin
names, gender is either calqued from the Spanish translation (*la UNESCO*, *el IRA*) or assigned by
the acronym's own phonological ending as if it were an ordinary Spanish noun (*la ETA*, treated as a
simple loanword). Pronunciation rule: acronyms with syllabifiable vowel-consonant sequences are
pronounced as ordinary words (*OPEP*→[opép]); all-consonant acronyms are spelled out letter-by-letter
(*CD*→"cedé," *PNV*→"peneúve"); partially-syllabifiable acronyms can be partly spelled, partly
pronounced (*PSOE*→[pesóe]) or fully spelled even when partly syllabifiable (*OLP*→[oelepé]). Plural
is often marked by doubling the initial letter (*EEUU*, *SSRRMM*). Acronyms can serve as bases for
further derivation (*PRI→priísta*, *PC→pecero*, *SIDA→sidático/sidoso*) and ordinary countable
acronyms pluralize normally (*los ovnis, tres CDs*).

### Hierarchical word structure (section 6, pp. 196–198)

Core claim: word-internal structure is **hierarchical, not linear** — directly tied back to Ch.1's
"articulación dual"/duality-of-patterning design feature, generalized up one more level (sounds→
morphemes→words→phrases→sentences, each level combining hierarchically into the next). Worked
example: *increíble* could in principle be built two ways — (i) prefix *in-* attaches first to the
verb *creer* (yielding a nonexistent verb *\*increer*), then *-ble* attaches; or (ii) *-ble* attaches
first to *creer* (yielding the real adjective *creíble*), then *in-* attaches to that. The book
argues (ii) is the only linguistically real analysis, because Spanish productively prefixes *in-* to
already-formed adjectives, but has no productive process of prefixing *in-* directly to bare verb
roots to form other verbs. **This is presented as a general methodological principle**: a
word-formation tree should be justified by which intermediate stage is an independently well-formed
word in the broader pattern of the language, not merely by linear morpheme order.

### Vocabulary — Chapter 3 derivational suffixes with explicit dialectal/registral distribution

| Term | Gloss | Part of Speech | Usage Tier | Attested Region | Geographic Scope | Notes |
|---|---|---|---|---|---|---|
| -illo/a (diminutive) | diminutive suffix alternative to -ito | suffix | regional | Andalusia; parts of South America | regional | p.169. |
| -ico/a (diminutive) | diminutive suffix alternative to -ito | suffix | regional | Central America, Colombia, the Caribbean, Extremadura, Aragón | regional | p.169. |
| -azo/a (augmentative) | augmentative suffix (distinct from the homophonous "blow with N" suffix) | suffix | regional | South America | regional | p.170. |
| -ote/a (augmentative) | augmentative suffix | suffix | regional | Mexico | regional | p.170. |
| diminutive-heavy register | heavy/extended diminutive use including on numerals, pronouns, non-finite verb forms (unito, ellita, callandito) | register pattern | regional | Andean region; Mexico | regional | p.170 — a usage-INTENSITY dialectal pattern, not just a suffix-choice one. |
| -(t)eco/a (gentilicio) | demonym suffix restricted to Mexican/Central American place names | suffix | regional | Mexico and Central America | regional | p.179; guatemalteco, yucateco, zapoteco. |
| -í (gentilicio) | demonym suffix restricted to North African/Asian place names | suffix | regional | North Africa, Asia (as source toponyms) | n/a (suffix usage domain, not speaker region) | p.179; marroquí, iraní, paquistaní, israelí. |
| zoo (truncation of zoológico) | zoo | noun | colloquial (register-neutral in one dialect) | Spain | national | p.195; "común ... incluso en registros formales, pero no en Latinoamérica." |
| lunfardo | Buenos Aires popular/slang register characterized by syllable-order reversal word formation | noun (register name) | slang | Buenos Aires, Argentina | regional | p.195; amigo→gomia, café con leche→feca con chele. |

## Chapter 4 — La estructura de la oración: sintaxis (pp. 201–278) — NON-REDUNDANT SUPPLEMENT

Author: Antxon Olarrea. Per the dispatch's non-redundant-supplement rule: basic sentence-type lists
and the subjunctive reference appendix (Apéndice 2: "Subjuntivo: cuadro de referencia," p.272) are
**SKIPPED** as fully redundant with this project's extensive subjunctive-trigger coverage
(`006_practice_makes_perfect_advanced_spanish_grammar.md` and others already catalogue subjunctive
triggers exhaustively). **Extracted in full: the formal constituent-structure/X-bar-theoretic
machinery (phrase-structure rules, subcategorization, transformations/movement, word order and
information structure), and the structural (not merely descriptive) analysis of predicate types —
especially the eight-way structural analysis of *se* — and the formal subordinate-clause typology**,
none of which any pedagogical grammar in this project's corpus presents at this level of structural
formalization.

### Constituent structure: diagnostics and phrase types (section 2, pp. 203–217)

**Structural ambiguity and constituency tests**: the book establishes two diagnostic tests for
whether a word sequence forms a syntactic constituent — **substitution** (replaceable by a single
proform, e.g. *él* for *mi hermano*) and **movement** (frontable as a unit; only constituents can be
isolated as answers to a question). Worked example: *Mi hermano vio a un niño con un telescopio* is
genuinely structurally ambiguous (telescope-carrying child vs. brother using a telescope to see),
and each reading is diagnosed by which substitution/movement/question-answer pattern is
grammatical.

**Sintagma (phrase) types and núcleo (head)**: SN (noun phrase), SV (verb phrase), SAdj (adjective
phrase), SAdv (adverb phrase), SPrep (prepositional phrase) — each phrase takes its category from
its head. **Determinante (Det)** is the cover category for articles, possessives, and quantifiers
(the book flags quantifiers as a distinct subtype since they can themselves follow another
determiner: *los dos estudiantes*).

**Reglas de reescritura sintagmática (phrase-structure rules)**: formal rewrite rules (O→SN SV;
SN→Det N (SPrep); SV→V (SN) (SPrep), etc.) explicitly justified as capturing four properties any
syntactic theory must explain: word order, hierarchical constituent structure, structural ambiguity,
and **recursion** — demonstrated with the genuinely unbounded SPrep→Prep SN / SN→Det N (SPrep)
mutual-recursion pair (*el color del pomo de la puerta de la casa del hermano de Juan...*), plus two
more recursive rules: coordination (SX→SX Conj SX, for any category X) and clausal embedding
(O'→COMP O, generating *Digo que Juan dice que... que...*).

**Subcategorización (lexical subcategorization)**: each verb's argument structure is treated as a
lexical fact that the phrase-structure component must respect — e.g. *poner* requires three
arguments (a *quién*, a *qué*, a *dónde*), so *\*Puse el libro* (missing the locative) and *\*Juan
puso en la mesa* (missing the direct object) are ungrammatical regardless of phrase-structure
well-formedness. This lexical requirement is what wh-movement (below) has to "satisfy via a trace"
rather than violate.

**Transformations/movement**: Qu- (wh-)movement is formally analyzed as displacement of an
interrogative phrase from its lexically-required argument position to COMP, leaving a **huella**
(trace, notated with coindexed subscripts) in the original position — e.g. *¿Quéᵢ pusiste [hᵢ] en el
garaje?* The book extends this to explain real ambiguity (*¿Cuándo dijo Juan que María había ido a
visitarlo?* is ambiguous between the trace attaching to the matrix or embedded clause — two distinct
possible answers) and to **island constraints**: movement cannot cross two or more **nudos cíclicos
(cyclic nodes/islands)** — in Spanish, SN and O' — explaining the ungrammaticality of *\*¿Dónde le
ha gustado a Juan la idea de que vayamos?* (extraction would cross both an SN and an O').

**Clitic movement/clitic-as-agreement analysis**: clitics (unstressed direct/indirect object
pronouns) can surface in multiple positions relative to the verb (*quisiera poder seguirlo haciendo*
~ *lo quisiera poder seguir haciendo*), suggesting movement-with-trace — but the book argues this
analysis breaks down under **clitic doubling** (*le hablé a Juan*, where both *le* and its doubled
NP *a Juan* are simultaneously present, impossible under a strict movement-leaves-a-gap model). The
book's resolution: **clitics are agreement morphemes, not moved pronouns** — paralleling subject-
verb agreement — supported by five converging arguments: (i) clitic-verb cohesion is as tight as
verb-inflection cohesion (orthographic separation, *se lo dio* vs. *dáselo*, is purely conventional);
(ii) no intonational pause between clitic and verb; (iii) nothing can be inserted between clitic and
verb (*\*se lo no dio*); (iv) when a doubled argument and its clitic can't both surface, the clitic
(the "agreement" element) is the one that's retained, exactly like verbal agreement; (v) cross-
linguistic parallel — Basque and polysynthetic languages like Navajo show verb agreement with direct
and indirect objects too, not just subjects. This directly supports a **pro**-subject/pro-object
null-pronoun analysis for sentences like *Se lo dije* (three distinct null pronominal arguments, each
identified by its corresponding agreement morpheme on the verb).

**X-bar theory (teoría de la X-barra / X⁰)** (pp. 225–238): presented as a universal template for
phrase structure, motivated explicitly by two problems with a raw phrase-structure-rule approach:
(i) it cannot explain how children acquire syntax so fast if the target grammar needs an enormous,
language-specific rule list; (ii) it offers no account of cross-linguistic universals. The X-bar
schema: SX → (Especificador) X'; X' → X' Adjunto; X' → X Complemento — i.e. every phrase has a head,
an optional specifier, and distinguishes **complementos** (lexically subcategorized arguments, always
SPrep for nouns) from **adjuntos** (unselected modifiers, which can stack recursively and be SAdj or
SPrep). **Cross-linguistic typological claim**: languages differ from each other, under this theory,
only in the relative linear order of head vs. specifier/complement/adjunct — illustrated with a Basque
example showing specifier-final, complement-final ordering opposite to Spanish's specifier-initial
pattern, i.e. this is presented as a genuinely comparative-typological tool, not Spanish-specific.

**Complement vs. adjunct diagnostic within the NP** (three rules, pp. 230–231): (i) only **deverbal
nouns** (derived from a verb, e.g. *destrucción*) and **sustantivos icónicos** (nouns like *libro,
foto, cuadro, mapa* that can express a "topic/subject-matter" relation) take true complements — for
deverbal nouns the complement SPrep expresses what would be the base verb's direct object (*la
destrucción de Roma*); for iconic nouns, the "topic/theme" SPrep is the complement and any
author/owner SPrep is merely an adjunct (*el libro de física [complement] de Feynman [adjunct] de
Julio [adjunct]*); (ii) any other noun's modifiers are always adjuncts, however many stack (*la mesa
de Juan, de madera, de trabajo, de Italia...*); (iii) adjuncts to a noun are SAdj or SPrep;
complements are always SPrep.

### Word order (section 2.8, pp. 238–244)

Spanish is explicitly contrasted with English as a comparatively **free-word-order language**:
alongside canonical SVO, VSO and VOS orders are both grammatical (*Ha leído Juan la novela* / *Ha
leído la novela Juan*). Two independent families of triggers for non-SVO order are distinguished:

**(i) Structural triggers** forcing post-verbal subjects regardless of information structure — six
named classes: interrogatives/exclamatives (*¿Qué ha leído Juan?*, with the book noting an explicit
Caribbean-Spanish exception allowing *¿Qué Juan ha leído?*); psychological/"backwards" verbs like
*gustar, doler, encantar*; unaccusative intransitives whose subject is not an agent (*llegar, crecer*
— explicitly contrasted with agentive intransitives like *reír, estornudar*, which don't trigger
this); the small verb class *faltar, suceder, ocurrir, sobrar* (indefinite subjects, always
post-verbal); certain *se*-constructions (cross-referenced to 3.1.3); and bare (determiner-less)
plural subjects (*Han aparecido nuevos estudiantes* / *\*Estudiantes han aparecido*).

**(ii) Information-structure triggers**, tied directly back to Ch.2's intonation material: the
default principle orders **tema/tópico** (known information) before **rema/foco/comentario** (new
information); since subject and topic usually coincide, SVO is the unmarked default, but when the
*subject itself* is the new information it moves to the end (*¿Quién viene mañana?* → *Mañana viene
MARÍA*). Two distinct, formally different fronting operations for emphasis are distinguished:
**rematización/topicalización** (fronting new information itself — forces subject-verb inversion,
allows only ONE fronted constituent, gets an obligatorily contrastive reading, and a specific
emphatic intonation contour) vs. **tematización/dislocación a la izquierda** (left-dislocating known
information for expressive emphasis — leaves the subject in its normal preverbal slot, requires
**clitic doubling** of the dislocated element, permits fronting MULTIPLE constituents at once, and
is set off by a comma/pause). This is a genuinely formal four-point structural contrast between two
superficially similar-looking Spanish fronting constructions that a pedagogical grammar would not
distinguish this precisely.

### Sentence definition and simple-sentence classification (section 3.1, pp. 244–254)

The book flags the classic "what is a sentence" problem as genuinely unsolved (200+ historical
definitions exist) and that intuitively sentence-like fragments lack a verb (*¡Fuego!, La sal, por
favor*) — adopts a working formal definition: "the predicative unit built around a conjugated verb."
**Diagnostic for "simple" vs. "compound" sentence despite surface multiple-verb appearance**: a
multi-verb string (auxiliary+main verb, modal+infinitive, or a periphrasis like *ir a + infinitive*,
*acabar de + infinitive*, *seguir + gerund*) still counts as ONE simple sentence if **clitic climbing**
is possible (*Fernanda está mirándola* ↔ *Fernanda la está mirando*) — contrasted with genuine
subordination, where climbing is ungrammatical (*Lamento que la odies* but never *\*La lamento que
odies*). This clitic-climbing test is a genuinely formal (not notional) diagnostic a pedagogical
grammar would not supply.

**Predicate-type classification, with structural tests, not just a list**:
- **Copulativas** (*ser, estar, ponerse, quedarse, mantenerse* + attribute): diagnosed by whether the
  attribute can be replaced by the clitic *lo* (*Guillermo es el jefe → Él lo es*) — true copulas
  (*ser, estar, parecer*) pass this test; **pseudocopulativas** (*ponerse, quedarse, mantenerse*)
  fail it but instead allow attribute-replacement by *así*.
- **Predicación secundaria** (secondary predication): distinguished from true copulas by an
  omissibility test — *Los niños estaban tranquilos* cannot drop the adjective (*\*Los niños
  estaban*), but *Los niños dormían tranquilos* can (*Los niños dormían*), showing the verb alone
  (not the adjective) carries the main predication in the second case. Can target either the subject
  or the direct object, the latter called a **cláusula reducida** (reduced clause): *Vi [a Juan
  borracho]*, *María compró [barato el disco]*.
- **Transitivity hierarchy**: intransitive (no complement) vs. transitive (takes a direct object,
  replaceable by accusative clitic *lo/la/los/las*) vs. **ditransitivo** (two complements, the
  indirect one replaceable/doubled by dative *le/les* — *gustar, doler, faltar, sobrar, molestar,
  encantar, fascinar* take ONLY an indirect-object-type complement, diagnosed by the dative-vs.-
  accusative clitic form) vs. **verbo preposicional** (obligatory PP complement that resists
  pronominalization entirely: *equivaler a, carecer de, consistir en* — *\*Este libro lo carece* is
  ungrammatical in a way a plain transitive wouldn't be).
- **Reflexive vs. reciprocal**, structurally distinguished by which paraphrase-PP can be added (*a sí
  mismo* for reflexive vs. *el uno al otro* for reciprocal) — with a three-way lexical split: **se
  léxico inherente** (verbs that exist ONLY in reflexive form: *jactarse, quejarse, arrepentirse* —
  no bare *\*jactar*), **se léxico opcional/no-inherente** (*dormir/dormirse, reír/reírse, ir/irse* —
  *se* adds an emphatic/telic nuance), and ordinary action verbs used reflexively (*bañar/bañarse*).
- **Pasiva** (*ser* + past participle, subject = theme not agent) vs. **pasiva-refleja** (*se* +
  active 3rd-person verb, agent optionally marked by *de/por*: *Se firmó la paz (por los
  embajadores)*) — explicitly distinguished from *estar* + participle, which is NOT a true passive
  but denotes the resultant state of a completed action (*La puerta fue cerrada* [event] vs. *La
  puerta estaba cerrada* [resultant state]).
- **Impersonales**, three distinct subtypes: weather verbs (*llover, nevar* — no plausible agent at
  all); *haber/ser/hacer* impersonals (*hay, hace calor, es tarde*); and **impersonal se** (*se come
  bien aquí*), which — unlike pasiva-refleja — never agrees in number with its complement and never
  licenses an agentive PP, but can nonetheless take a personal object marked with *a*, which is then
  pronominalized with the DATIVE clitic *le/les* rather than accusative *lo/la* in most dialects (*Se
  convocó a los asistentes → Se les convocó*) — a genuinely striking and little-known structural
  quirk worth flagging. All impersonal-*se*/weather/haber subjects are analyzed as a **pro
  impersonal/expletivo**, distinct from the ordinary referential *pro* used for dropped personal
  subjects (cross-referenced to the *pro*-drop discussion in section 2.6). A fourth impersonal
  strategy uses overt *uno* + reflexive verb (*Uno se acostumbra a todo*).

### The eight uses of *se* (section 3.1.3, pp. 255–258) — HIGH STRUCTURAL VALUE

The book gives an explicit, numbered eight-way structural taxonomy of Spanish *se* (far more granular
than any pedagogical treatment), each formally distinguished:
1. **Variante contextual de le/les** (dative-clitic allomorph before a 3rd-person accusative clitic:
   *le lo di* is ungrammatical → *se lo di*).
2. **Se reflexivo** (*Se afeita*).
3. **Se recíproco** (*Se despreciaban el uno al otro*).
4. **Se impersonal** (*Se come bien aquí* — see above).
5. **Se dativo de interés / se télico** (adds a completive/totality nuance to an already-transitive
   verb: *Comí una hamburguesa* [possibly partial] vs. *Me comí una hamburguesa* [necessarily all of
   it] — the book extends this to an "emphatic se" on certain intransitives, *dormirse, morirse,
   irse, reírse*, which sits on a blurry boundary with lexical *se*).
6. **Se pasivo-reflejo** (*Se venden casas baratas*).
7. **Se medio (voz media)** — a genuinely distinct fourth reading from reflexive/reciprocal/passive:
   no human agent at all, implicit or explicit, is present even conceptually (*El barco se hundió* =
   "the boat sank" [on its own], contrasted with the passive-reflexive reading "the boat was sunk [by
   the enemy]"). The book notes real structural ambiguity across all three non-reflexive se-readings
   in a single sentence like *El coche se movió* (reflexive/pasiva-refleja/voz media, each with a
   different English translation), and gives two genuine disambiguation heuristics: (a) an agentive
   *por*-phrase is compatible ONLY with pasiva-refleja, never voz media; (b) adding a purpose clause
   implying agent intent (*para despejar la calle*) favors the pasiva-refleja reading, while a
   **preverbal** subject NP favors the voz-media reading and a **postverbal** one favors the implicit-
   agent (pasiva-refleja) reading (*La puerta se cerró (con el viento)* [media] vs. *Se cerró la
   puerta (para que no entrara nadie más)* [pasiva-refleja]) — a subtle word-order-based
   disambiguation heuristic not found in pedagogical treatments.
8. **Se léxico** (verbs requiring *se* inherently or idiosyncratically, already covered under
   reflexives above, e.g. *jactarse*).

### Compound sentences: coordination and subordination (section 3.2, pp. 258–271)

**Coordination** types by conjunction: copulativa (*y, e, ni*), disyuntiva (*o, u*), adversativa
(*pero, mas, sino que* — limited to exactly two conjuncts). **Semantic/pragmatic compatibility
constraints on coordination** are explicitly flagged as real grammatical constraints, not just
stylistic oddities: cannot coordinate a declarative with an interrogative, two clauses with
incompatible tense values, two informationally-unrelated clauses, or two clauses in reversed
logical/chronological order (*\*El suicida se mató y saltó al vacío*, wrong causal order).
Coordination with no overt conjunction is **yuxtaposición** (*No vino a clase, estaba enfermo*).

**Subordination**, three types by the syntactic position/function the subordinate clause occupies
(parallel to N/Adj/Adv):
- **Subordinadas sustantivas/completivas** (occupy N-like positions: subject, direct object,
  prepositional object, noun/adjective complement). Finite (indicative/subjunctive, introduced by
  *que*) vs. non-finite (infinitive, no complementante). **Mood selection is tied to the matrix
  verb's assertive status**: assertive verbs (*decir, creer, pensar* — strong or weak assertion) take
  indicative complements, and strong vs. weak assertives behave differently under negation (*No creo
  que Juan lo sepa* [subjunctive forced] vs. *No digo que Juan lo sabe/sepa* [either mood possible]);
  non-assertive verbs (volition: *querer, desear*; influence: *ordenar, obligar*; factive: *lamentar,
  sentir*) take subjunctive. Both classes freely allow infinitival complements. **A genuinely subtle
  diagnostic**: subjunctive and infinitive completives (but never indicative ones) may optionally be
  preceded by the article *el* (*Me sorprendió el que llegara tarde* / *el llegar tan tarde*, but never
  *\*el que Juan llegará tarde*). Interrogative/exclamative indirect completives also exist, introduced
  by *si* (total) or a Qu-word (partial).
- **Subordinadas adjetivas/de relativo**: modify an antecedent NP; the relative pronoun occupies COMP
  via movement, leaving a trace, and cannot be duplicated by an added overt argument in its original
  position (*\*Las personas con quienes hablé con ellas*). **Full relative-pronoun inventory with
  individually specified formal properties**: *que* (featurally unmarked, can appear without an
  antecedent only when preceded by the article: *(Los) que llegaron tarde*); *quien* ([+human]
  [±plural], has independent referential autonomy, can appear antecedent-less); *el cual* (marked for
  gender/number but lacks referential autonomy, cannot appear without an antecedent); *cuyo*
  (possessive relative adjective, always requires an explicit antecedent); *cuanto* (a quantifier
  needing no antecedent, patterns like *el cual*). **Restrictivas (especificativas) vs. apositivas
  (explicativas)**, distinguished by (i) intonation/comma-marking, (ii) semantic effect (restrictive
  narrows the antecedent's reference; appositive doesn't alter it at all), (iii) mood freedom
  (restrictives allow indicative/subjunctive/infinitive depending on the antecedent's
  specific/non-specific status; appositives allow ONLY indicative), and (iv) antecedent restrictions
  (restrictives cannot take a proper name, pronoun, or full clause as antecedent — appositives can).
  **Infinitival relatives** exist too, with a narrowly restricted licensing environment (object of a
  small verb class: *buscar, encontrar, tener, necesitar, querer* + a non-specific antecedent: *Busco
  un amigo en quien confiar*).
- **Subordinadas adverbiales**: nine traditionally named subtypes — temporales, locativas, modales,
  causales, finales, condicionales, concesivas, comparativas, consecutivas — each with its own
  licensed nexus set and, notably, its own **mood-selection profile**: finales require subjunctive
  exclusively, and in a tense later than the matrix (*para que los niños se distraigan*, never
  *\*se distrajeran/\*se distraen*); condicionales mark a three-way possibility/improbability/
  impossibility distinction purely through verb tense/mood (*Si hace buen tiempo...* / *Si hiciera...*
  / *Si hubiera hecho...*); concesivas allow either mood depending on whether the stated objection is
  presented as real or merely possible, which is also what formally distinguishes them from
  superficially similar **adversativas** (*pero*-clauses, which allow indicative only) — plus a
  distinct word-order freedom (concesivas can precede or follow the main clause; adversativas cannot
  precede: *\*Pero no lo entendió se lo leyó todo*).

---

## Chapter 5 — Historia de la lengua española (pp. 279–338) — SUBSTANTIVE, PROPORTIONATE

Author: José Ignacio Hualde. New territory relative to this project's pedagogical grammars; a
different angle from the dedicated history-of-Spanish books in a sibling dispatch (Penny/Pountain),
so covered independently but proportionately rather than exhaustively — within-chapter emphasis
placed on content with downstream relevance to dialectology/sociolinguistics (sound-law origins of
seseo/ceceo/yeísmo, voseo history, loanword strata) over the driest step-by-step sound-law catalog
and the medieval-text/Judeo-Spanish/Aragonese/Galician close-reading exercises (pp.309–318, 331–335),
which are only summarized here rather than reproduced in full philological detail.

### Why Spanish has the alternations it has; patrimonial words vs. cultismos (pp. 279–292)

Spanish descends from spoken Latin via uninterrupted oral transmission (not from written/Classical
Latin). Sister Romance languages from the same source: Portuguese/Galician, Catalan, French,
Occitan (incl. Gascon, Provençal — "today endangered"), Italian, Romansh/Grisón (spoken in Swiss
valleys), Romanian. Core mechanism of language splitting: political fragmentation after Rome's fall
→ broken communication → regionally divergent sound/dialect changes → eventual mutual
unintelligibility = separate languages.

**Palabras patrimoniales (inherited by continuous oral transmission, hence heavily
sound-changed) vs. cultismos (borrowed later directly from written/Classical Latin, with minimal
adaptation)** — the SAME Latin word sometimes gives Spanish a doublet pair via both routes:
*directa→derecha* (patrimonial) vs. *directa→directa* (cultismo); *strictu→estrecho* vs. *strictu→
estricto*; *delicātu→delgado* vs. *delicātu→delicado*; *focu→fuego* vs. *focu→foco*. **Structural
asymmetry with English, worth flagging for the mechanics phase**: in English, learned (Latinate)
vocabulary and everyday (Germanic) vocabulary come from genuinely different source languages
(*hand/manual, tooth/dental, night/nocturnal*), whereas in Spanish BOTH the everyday and the learned
member of such pairs are Latin — just transmitted via two different historical channels
(*mano/manual, diente/dental, noche/nocturno*). This explains why English-Spanish cognate
relationships cluster so heavily around the LEARNED vocabulary tier specifically.

### Pre-Roman languages of Hispania (pp. 281–286)

Basque (euskera) is the only pre-Roman language to survive to the present (spoken in Navarre, the
Basque Autonomous Community, and the French Basque Country); all others (Iberian, Celtiberian,
Lusitanian, Tartessian) were replaced by Latin. Basque influence on Spanish is explicitly
characterized as small: two possible phonological influences on medieval Castilian (aspiration of
Latin *f-*; early loss of voiced sibilants), a handful of loanwords (*izquierda* "left," replacing
the Latin-derived *siniestra* once it acquired negative connotations; *aquelarre* "witches' coven,"
from Basque *aker* "billy-goat" + *larre* "meadow"), and many Basque-origin surnames (*etxe* "house,"
*mendi* "mountain," etc. — e.g. *Iturbide* "path to the spring," *Echevarría* "the new house"). The
Iberian script (part-alphabet, part-syllabary, no separate signs for voiced/voiceless stop pairs or
for stops independent of a following vowel) is covered as a starred/optional topic; the book is
explicit that phonological/structural similarities between Basque and Iberian (both lack
word-initial liquid+stop clusters, both have 5 vowels, two rhotics, two sibilants) do NOT prove
genetic relatedness — attempts to decode Iberian via Basque have failed.

### Indo-European family and Latin's place in it (pp. 286–288)

Proto-Indo-European (~6,000 years ago) is the reconstructed common ancestor of most European
languages plus Iranian/Indic languages. Latin belongs to the Italic branch (with extinct sister
languages Oscan, Umbrian, Faliscan). Non-Indo-European languages of modern Western/Central Europe:
Basque (no known relatives) and the Finno-Ugric languages (Finnish, Estonian, Hungarian — Hungarian
arrived in Europe only in the 9th century with the Magyar migration from Central Asia).

### How Latin fragmented into Ibero-Romance, and why Castilian specifically spread (pp. 288–291)

Medieval dialect continuum existed in the north (Galician→Asturian dialects→Castilian; Aragonese
Pyrenean valleys shade from Castilian-like to Catalan-like going west-to-east) but NOT further
south, where transitions between Portuguese/Spanish/Catalan are abrupt — explained by the **Arab
conquest (711) and the Reconquista**: Romance speech under Arab rule (**mozárabe**, from Arabic
*musta'rab* "Arabized") persisted for centuries in places like Toledo under Romance-Arabic
bilingualism, but both mozárabe and Arabic receded as northern Christian kingdoms pushed south, each
carrying ITS OWN northern Romance variety southward in a wedge shape — Castilian specifically
originates as one dialect among many, local to the area just north of Burgos, which spread
disproportionately far south and eventually displaced competitors because of Castile's political/
military fortunes. **Present-day co-official/regional languages of Spain, explicitly enumerated with
status and speaker base**: Galician (co-official in Galicia; also the distinct *fala de Xálima* in
Extremadura); Asturian-Leonese (official protection in Asturias, few native speakers, rural; a form
of Leonese also spoken with official recognition in Miranda do Douro, Portugal); Basque (co-official
in the Basque Autonomous Community; legal recognition also in parts of Navarre; also spoken in
French Basque Country); Aragonese (today only in some Pyrenean valleys); Catalan (co-official in
Catalonia, Valencia, Balearic Islands; official language of Andorra; also in French Catalonia and
Alghero/L'Alguer, Sardinia); Aranés (a variety of Gascon Occitan, ~5,000 speakers in the Vall
d'Aran, Catalonia, many trilingual in Aranés/Catalan/Spanish). Also noted: Portuguese (Portugal) and
English (Gibraltar) as non-Spanish official languages elsewhere on the Peninsula.

**Americas colonization and the Andalusian-origin hypothesis**: ships to the New World departed from
Seville, and prospective emigrants had to stay in this Andalusian city for extended periods —
proposed (not certain) explanation for why Latin American Spanish shares Andalusian features,
notably the absence of the /ʎ/ phoneme (yeísmo) and widespread /s/-aspiration.

### Medieval sound changes with direct dialectological payoff (pp. 293–298)

**Medieval aspirated /h/, from Latin f-**: words now spelled with a silent *h-* but pronounced
[f-] in Latin went through an intermediate medieval [h-] stage (*farina→[hariná]→harina [así harina
pronounced without h today]*), traced via cognate cultismos (*hilo/filamento, harina/farináceo,
hormiga/formicario*) and comparison with sister Romance languages that KEPT Latin /f-/ (Sp. *hacer*
vs. Port. *fazer*, Fr. *faire*, It. *fare*, Cat. *fer*). Some modern dialects still preserve this
aspiration, now merged with /x/ (*cante jondo* = "cante hondo"; *jalar*~*halar*; the place name *La
Jolla* = "La Hoya" with aspiration preserved). A SEPARATE, purely orthographic *h-* (never aspirated,
ever) appears before word-initial *ue-/ua-/ui-* diphthongs (*huele, huérfano, hueso, hueco* — compare
non-diphthong relatives *olemos, orfanato, óseo, oquedad*), traced to the historical Latin
non-distinction between letters U and V, where *h-* was adopted purely to mark that an initial
*ue-* sequence was a diphthong (vowel value) rather than a consonant+vowel sequence.

**Medieval sibilant system and its two divergent modern outcomes — directly explains Ch.2's seseo/
ceceo/distinción split**: medieval Castilian had FOUR fricative/affricate sibilant phonemes contrastive
by voicing: /s/ vs. /z/ (apicoalveolar fricatives, contrastive only intervocalically, spelled
-ss-/-s-) and /ts/ vs. /dz/ (dental affricates, spelled c/ç vs. z), plus a prepalatal pair /ʃ/ vs.
/ʒ/ (spelled x vs. j/g(e,i)/i). Two changes (desafricación + ensordecimiento of voiced members)
started in northern Castile and spread south, but were still maintained in Toledo/Seville speech as
late as the late 15th century, and **are STILL maintained today in Judeo-Spanish (Sephardic Spanish)
spoken by descendants of Jews expelled from Spain in 1492** — a striking living fossil of the
medieval system. **North/central Peninsular outcome**: the resulting three close fricatives (/ś/
apicoalveolar, /s̄/ predorso from the old affricates, /ʃ/) pulled apart further — predorso /s̄/ fronted
to interdental /θ/ (giving the "distinción" z/c(e,i) = /θ/ vs. s = /s/ system), and /ʃ/ backed to
velar /x/. **Andalusian/Latin-American outcome**: all four medieval sibilants (plus their
voiced/voiceless and affricate/fricative distinctions) collapsed into ONE phoneme /s/ — this is the
direct historical origin of seseo — while the prepalatal pair similarly merged to one voiceless
sound that in parts of Andalusia backed all the way to laryngeal /h/ (merging with the f->h
aspiration above). **The theoretical debate over seseo's origin is explicitly presented as
unresolved**: the "Andalucista" theory (seseo spread to the Americas via the numerical dominance of
Andalusian colonists and the Seville departure point) competes with an independent-parallel-
development account (the colonial contact situation mixed speakers of several different medieval
sibilant systems, and the simplest system — full merger — won out through dialect-contact
leveling).

### Main Latin-to-Spanish sound changes (section 8.2, pp. 298–305) — systematic, numbered rule list

Presented as rule-numbered lists (v1–v5 for vowels, c1–c9 for consonants), each with worked examples
and a "do the next one yourself" exercise format (answers not reproduced here per copyright
discipline):
- **v1**: Latin short high vowels lower to mid (ŭ>o, ĭ>e): *manu>mano, lupu>lobo*.
- **v2**: Latin short mid vowels ě/ŏ diphthongize to [i̯e]/[ue̯] under stress: *terra>tierra,
  focu>fuego* — blocked by a following palatal that closes the vowel first (*nocte>noche* not
  *\*nueche*; *oculu>cast.med. /óʒo/* not *\*uéʒo* — though Leonese/Aragonese dialects DO show
  *güello, fuella* with the diphthong, a dialect-specific divergence worth flagging).
- **v3**: word-final -e drops after a single dental/alveolar consonant: *pane>pan* (but is retained
  in the plural, *panes*, since it's no longer word-final there) — explaining synchronic
  singular/plural alternations.
- **v4**: diphthong au>o: *tauru>toro* (cf. cultismo *taurino*), *auru>oro* (cf. *áureo*),
  *causa>cosa*.
- **v5**: Latin stress position (penultimate if closed/long, else antepenultimate) often triggers
  loss of the pretonic/posttonic vowel: *tabula>tabla* (cf. cultismo *tabular*), *fabulari>hablar*
  (cf. *fábula*), *civitate>cast.med. cibdad>ciudad*. Two special resulting clusters get their own
  sub-rules: *-mine>-mne>-mre (disimilación)>-mbre (epéntesis)*: *homine>hombre* (cf. *homínido*);
  *-cul->/k'l/>cast.med. /ʒ/>esp.mod. /x/*: *speculu>espejo*.
- **c1**: Latin geminate consonants simplify (unlike Italian, which keeps them) — EXCEPT the three
  alveolar resonant geminates, which instead PALATALIZE: *-nn->ñ* (*annu>año*), *-ll->/ʎ/* (merging
  with /ʝ/ in yeísta dialects: *caballu>caballo*), *-rr-* stays as the trill (vs. simple *-r-*).
- **c2**: intervocalic voiceless stops voice: *lupu>lobo, petra>piedra*. Combined with c1, this means
  any surviving intervocalic /p,t,k/ in a patrimonial word must trace back to a Latin GEMINATE
  (*cūpa>cuba* vs. *cuppa>copa* — a minimal-pair-style demonstration). **No historical /v/ phoneme
  in Old Castilian**: medieval Castilian instead opposed an occlusive /b/ (from Latin intervocalic
  /p/: *lupu>lobo*) to an approximant /b̞/ (from Latin /b/ and prevocalic /u/: *caballu>cavallo
  [kabáʎo]*) — later these two became positional allophones of one phoneme, as in modern Spanish.
- **c3**: intervocalic voiced stops frequently drop entirely: *frigidu>frío, digitu>dedo*.
- **c4**: /k/ before a front vowel palatalizes: *k>cast.med. /ts/>esp.mod. /θ/ (north/center) or /s/
  (elsewhere)* — **this is explicitly identified as the historical origin of the orthographic c/c
  split (hard vs. soft c)**, since Latin *c* was always [k].
- **c5**: word-initial *f-* before a vowel aspirates in medieval Castilian, then drops entirely in
  modern Spanish (except before [u̯]: *fuego, hogar* both survive from *focu*, one via each sound
  law's blocking environment) — cross-referenced to the aspirated-/h/ discussion above.
- **c6**: word-initial *pl-, cl-* (and sometimes *fl-*) > *ll- /ʎ/*: *pluvia>lluvia, clamare>llamar,
  flamma>llama* (cf. cultismo *inflamable*).
- **c7**: syllable-final /k/ before another consonant weakens to [i̯], which then palatalizes a
  following consonant: the *-ct-* cluster → /tʃ/ (*nocte>/nói̯te/>noche*, cf. cultismo *nocturno*;
  *lacte>leche*, cf. *lácteo*; *directu>derecho*, cf. *directo*); the *-x- (/ks/)* cluster similarly
  palatalizes and ultimately velarizes: *axe>/ákse/>...>eje*, cf. cultismo *axial*.
- **c8**: *li-, le-* before a vowel → palatalization+delateralization chain ending in modern /x/:
  *fīlia>.../ʎa/>cast.med. /ʒa/>.../xa/ hija*, cf. cultismo *filial*; same outcome for the *-cul-*
  cluster (already noted in v5): *oculu>cast.med. /óʒo/>moderno ojo*, cf. cultismos *oculista,
  binocular*.
- **c9**: *ni-, ne-* before a vowel → ñ: *vinea>viña, hispania>España*, cf. cultismo *hispánico*.
- **Metátesis** (sound-order swap), triggered by dispreferred consonant sequences: *teneru>*tienro
  (regular)→tierno* (metathesis); *spatula>*espadla (regular)→espalda* (metathesis).

**Cross-Romance comparative payoff, explicitly tabulated in the book's own exercises**: the *-ct-,
-x-* outcomes above distinguish Spanish *noche, ocho, pecho, derecho, hecho, leche* from Portuguese
*noite, oito, peito, direito, feito, leite* (palatalization stopped earlier) and Italian *notte,
otto, petto, diretto, fatto, latte* (simple assimilation, no palatalization at all) — the same
Latin input diverging three ways across the three languages, a genuinely illustrative three-way
minimal comparison.

### Standardization history (section 13, pp. 318–320)

Alfonso X "el Sabio" (r. 1252–84) is credited with the first real Castilian written norm (unifying
prior chaotic orthographic/morphological variation across scribes), via a massive royal translation/
compilation program (law, history, astronomy, mineralogy) — notably using GALICIAN for his own
lyric poetry (the *Cantigas*) while using Castilian for the technical/scholarly corpus, incorporating
Arabic loanwords for technical vocabulary (*alquimia, álgebra, algoritmo, cero*). This orthography
lasted until the 16th century, when it began to go stale as the sibilant system (above) kept
evolving out from under it. A second normalizing wave came with the printing press (16th c.); the
Real Academia Española (founded 18th c.) established the modern fixed norm, though RAE norms have
themselves changed since — illustrated with a striking primary-source pair of quotes: the 1792 RAE
grammar insisting b/v be kept orthographically distinct "porque hay muchas voces que...varían de
significación" (giving *balido* "bleating" vs. *valido* "favored" as a minimal pair under an
imagined distinct pronunciation) vs. the 2005 RAE explicitly stating there is NO pronunciation
difference between b/v at all today, confirming the distinction is purely etymological/orthographic
convention with no phonetic reality — a genuinely interesting case of a prescriptive institution's
own claims shifting with better linguistic understanding.

### Arabic influence (section 14, pp. 320–321) — HIGH VALUE lexical-stratum data

Visigothic influence (5th–8th c. Germanic rulers) was minimal — a few proper names (*Alfonso,
Rodrigo*) and possibly the patronymic suffix *-ez* (*Rodríguez, Álvarez*). **Arabic influence (711
onward) is far larger**, with the Arabic article *al-* (consonant assimilates only to an apical
following consonant) recognizable at the start of hundreds of loanwords, organized by domain:
agriculture/foodstuffs (*alcachofa, albaricoque, azúcar, aceite, algodón, alfalfa, zanahoria,
albóndiga, almíbar, jarabe, azafrán*); domestic life (*almohada, alfombra, alcoba, alféizar,
almirez, alfiler*); civil/military organization (*alcantarilla, alcázar, almena, albañil, aduana,
almacén, alquiler, aldea, alcalde, alguacil, alférez, almirante*); science/mathematics, reflecting
Arabic civilization's higher medieval cultural level (*álgebra, alquimia, alambique, alcohol,
algoritmo, guarismo, cifra, cero*); basic function words (*ojalá* ← *wa-ša'a llāh* "and may God
will it"; the preposition *hasta*). **Algarabía** "racket, chaos" is literally the old name for the
Arabic language itself (*al-'arabiyya*) — a nice example of "foreign language sounds like chaotic
noise" semantic drift. Toponymic stratum: *Guad-* ← Arabic *wadi* "river" (*Guadalajara* "river of
stones," *Guadalquivir* "great river," *Guadalupe* "river Lupe/Lope").

### Amerindian-language influence (section 15, pp. 321–323) — HIGH VALUE lexical-stratum + regional data

Four major source languages, each with its own domain and (crucially) its own REGIONAL distribution
in the modern language — this is explicit lexical-regionalism data:
- **Náhuatl** (Aztec empire; ~800,000 speakers today): general-Spanish loans *tomate, chocolate,
  aguacate, cacahuete/cacahuate, chicle, coyote, ocelote, zopilote, petate, milpa, tamal, nopal*;
  MEXICO-ONLY items *guajolote* ("pavo"), *cuate* ("chico"), *elote* ("mazorca"). Contact-induced
  phonological structure: Mexican Spanish's /tl-/ cluster (*Tlaxcala, tlapalería*) is attributed
  directly to Náhuatl substrate influence — a genuine phonotactic, not just lexical, contact effect.
- **Quechua** (Inca empire; ~8 million speakers, mainly Peru/Bolivia/Ecuador): *llama, vicuña,
  guanaco, alpaca, cóndor, puma, mate, papa, pampa, guano, puna*; regionally limited *guagua*
  ("bebé"), *palta* ("aguacate"). **Phonological contact effect**: Andean Spanish's comparatively
  strong retention of /ʎ/ (lleísmo) is attributed to contact with Quechua and Aymara, both of which
  have this phoneme.
- **Guaraní** (co-official in Paraguay, Tupí-Guaraní family): *jaguar, ñandú, tapir, tiburón, tucán,
  mandioca, tapioca* — the hydronym *Yguazú* ("Iguazú") literally = "agua" + *guasu* "grande."
- **Caribbean (Taíno/Arawak, Carib)**: the FIRST Amerindian loans into Spanish historically
  (*cacique, caníbal, canoa, piragua, hamaca, huracán, maíz, iguana*).
- **Explicit regional-synonym competition data**: *aguacate* (Náhuatl, general) vs. *palta*
  (Quechua, much of South America); *cacahuete/cacahuate* (Náhuatl) vs. *maní* (Arawak, Caribbean);
  *chile* (Náhuatl) vs. *ají* (Arawak) — three cases of the SAME referent carrying different regional
  names depending on which contact language dominated that area.

### English-Spanish etymological relations (section 16, pp. 323–324)

Three distinct channels explain Spanish/English lexical similarity, worth distinguishing precisely:
(i) both languages independently borrowed the same cultismo from written Latin (*strict/estricto,
capital/capital*); (ii) English borrowed many Latin-origin words via Norman French specifically
(*mountain, river, face, very*); (iii) genuine Proto-Indo-European cognates with NO borrowing at all,
just parallel inheritance with different sound changes in each branch (Sp. *pez* ← Lat. *piscis* vs.
Eng. *fish* ← Germanic *fisk*, both ← PIE **pisk*, reflecting the regular Germanic p→f shift also seen
in *pie/foot, padre/father, por/for*; similarly *cuerno/horn* ← PIE **korn*, reflecting Germanic k→h).
Direct Spanish-to-English loans, mostly from American West contact: *sombrero, embargo, cargo,
patio, burro, mosquito, rodeo, siesta*, and adapted forms *desperado* (←*desesperado*), *buckaroo*
(←*vaquero*), *vanilla* (←*vainilla*), *lasso* (←*lazo*). Direct English-to-Spanish loans (recent,
by domain): tech/science (*software, radar, estrés*), sports (*fútbol, béisbol, tenis*), fashion
(*bikini, jersey, minifalda, champú*), commerce (*boom, stock*) — explicitly flagged as an
ever-growing category "por motivos culturales obvios," directly relevant to this project's
loanword-integration interest. Older Germanic-origin loans into Spanish, parallel to but independent
of the English cognates: *guerra/war, yelmo/helmet, robar/rob, rico/rich*.

### Linguistic change and dialectal variation today (section 17, pp. 324–331) — HIGH VALUE, direct companion to Ch.2/Ch.7

A four-way comparative dialect study (Madrid, Mexico City, Buenos Aires, San Juan PR), explicitly
historicizing each Ch.2 phonological feature:

**Phonological/phonetic comparison (17.1)**:
- Seseo's medieval origin re-stated with the "Andalucista vs. independent-development" debate noted
  above as genuinely unresolved scholarly controversy.
- Yeísmo: already general in colonial Seville and most of Latin America; the loss of /ʎ/ is "a
  change in progress, now completed in the youngest generations in almost all areas where it had
  persisted" (north Spain, the Andean region, Paraguay).
- **Rehilamiento** (strident [ʒ] pronunciation of y/ll, Buenos Aires-characteristic) is NOT
  exclusively Argentine — also occurs in some Mexican speech specifically after /s/ (*las llaves*→
  [lazʒábes]); its further devoicing [ʒ]>[ʃ] (Buenos Aires-in-progress) is explicitly noted to risk
  REDUCED MUTUAL INTELLIGIBILITY with dialects where [ʃ] instead comes from de-affricated *ch*
  (Andalusia, north Mexico, Panama, Chile — i.e. two historically unrelated sound changes converging
  on the same surface output, a genuine homophony-across-dialects hazard).
- **/s/-aspiration intensity ranked across the four cities**: Puerto Rico (most extensive — aspirates
  pre-consonantally AND word-finally before pause AND before a following vowel) > Buenos Aires
  (pre-consonantal only) > Madrid (colloquial-register only, mainly before /p,k/) > Mexico City
  (essentially none — "a conservative dialect in this respect," compensating instead with unstressed
  vowel reduction/devoicing before /s/: *buenas noch's*). A further regional variant aspirates
  word-INITIAL /s/ (New Mexico, parts of Central America): *la semana→[la hemána]*.
- **/n/ velarization**: present in San Juan, absent (mostly) in the other three cities; a rare,
  geographically scattered [m]-final variant (Yucatán, Valle del Cauca Colombia, Tucumán Argentina)
  is explicitly flagged as independent parallel development given the disconnected geography.
- **Rhotic variation**: lateral/rhotic neutralization at syllable-final position widespread in Puerto
  Rico, the Caribbean, the Canaries, and Andalusia (one historical source, Andalusian-origin
  diffusion hypothesized); a dorsal/uvular, possibly voiceless or fricative, realization of the
  trill in parts of Puerto Rico (humorously, "Ramón" can sound like "jamón") — paralleled by similar
  apical-to-dorsal rhotic shifts in French, Portuguese, and German historically, explicitly flagged
  as NOT found on the Peninsula, i.e. a genuine Caribbean-Spanish-specific innovation; a preaspirated
  [ɦr] variant also Caribbean-specific and not found in Spain.
- **/x/ "stridency scale" across the four dialects**: Madrid > Buenos Aires > Mexico City > San Juan
  (explained by the same north/south split noted in the aspirated-/h/ history above — Peninsular
  /ʃ/ backed gradually to /x/, while the southern branch jumped straight to [h], merging with the
  f->h aspiration).
- **/d/-elision**: frequent in colloquial Madrid speech and sometimes San Juan, firmly retained in
  Mexican and Buenos Aires speech — the book notes this was likely MORE widespread historically and
  has since been socially stigmatized and has RETREATED in Latin America while gaining social
  acceptance in Spain — a genuine divergent-sociolinguistic-trajectory case, not a simple retention/
  innovation split.

**Morphological/syntactic/lexical comparison (17.2)**:
- **Second-person pronoun systems, with full historical derivation of usted/vos/voseo**: Latin had
  only *tū* (sg.) / *vōs* (pl.); *vōs* began to be used as a singular deferential form under the
  Empire (the system still found in French *tu*/*vous*); Spanish grammaticalized *vos otros* as a
  new plural pronoun (paralleled, but without the obligatory "otros"/"autres"/"altri" element, in
  French *vous autres* and Italian *voi altri*); meanwhile singular *vos* kept losing formality until
  it was perceived as equivalent to *tú*, so a NEW deferential form was created from *vuestra merced*
  (→ *vuesarced* → *usted*) — in Don Quijote, Quijote uses both *tú* and *vos* to Sancho, who
  addresses him with *vuestra merced*, capturing the three-form system mid-transition. The
  **metropolitan resolution** (Madrid, and cities with close metropolitan contact like Mexico City
  and Lima) eliminated *vos* entirely; peripheral areas either kept all three with new nuanced
  distinctions, or (opposite outcome, as in Argentina) eliminated *tú* instead, leaving **voseo**
  as the sole informal singular. **Argentine voseo's verb forms derive from old *vosotros* forms by
  monophthongization** (*vos sos, cantás, perdés, salís* ← *vosotros sois, cantáis, perdéis, salís*),
  with an etymologically MIXED pronoun paradigm — subject/prepositional-object *vos*, but clitic
  object *te*, possessive *tu* (*vos te levantás; te lo doy a vos; acá tenés tu libro*). General
  Latin-American voseo (outside Argentina, where *tú* has vanished entirely) typically COEXISTS
  with *tú*, with *vos* marking greater intimacy in the register continuum.
- **Leísmo/laísmo/loísmo**: Madrid shows leísmo with [+human, +masculine] direct objects; most of
  Latin America (Mexico, Puerto Rico, Buenos Aires) keeps the "etymological" system — EXCEPT Ecuador,
  which extends leísmo to ALL direct-object types. Historically, **both systems coexisted from the
  very earliest Castilian texts** — leísmo is not a modern innovation relative to the "etymological"
  system, both are equally old.
- A pluralizing innovation in Mexico/parts of Latin America: adding /-s/ to a clitic cluster to mark
  a plural indirect object when *le/les* have both neutralized to *se* (*esto se los digo a
  ustedes*).
- Puerto Rican syntactic innovation: no obligatory subject-verb inversion in partial (wh-)
  questions — *¿Qué tú dices?* (cross-referencing Ch.4's structural-trigger list, which flagged
  exactly this inversion as normally obligatory, with a Caribbean exception already noted there).
- **Lexical regionalisms for "kid/child" and informal address terms, explicitly contrasted across the
  four cities**: *chaval* (Madrid), *pibe* (Buenos Aires), *cuate* (Mexico); discourse particles
  *che* (Argentina), *órale* (Mexico), *vale/tío* (Madrid); a fully opaque-to-outsiders colloquial
  sentence is cited as illustration of register-specific slang density: *el laburo no da guita*
  ("work doesn't pay" — Buenos Aires lunfardo-adjacent register, *laburo* "work," *guita* "money").

### Galician text sample (section 18.3, p. 334) — brief note

A short Galician folk tale (fox and eagle) with parallel Castilian translation is given as a
close-reading exercise to spot sound correspondences (Galician *nh* = velar nasal /ŋ/ intervocalically;
*x* = /ʃ/, as in Aragonese and Old Castilian). Not reproduced here beyond this structural note, per
copyright discipline — the Judeo-Spanish and Aragonese ("cheso") parallel-text sections (18.1–18.2,
pp. 331–334) are similarly only noted as present, not extracted in detail, consistent with this
chapter's "substantive but proportionate" treatment.

---

## Chapter 6 — El estudio del significado: semántica y pragmática (pp. 340–389) — SUBSTANTIVE, new in 2nd ed.

Author: Catherine E. Travis. Genuinely new territory for this project (no prior Spanish source
covers formal semantics/pragmatics); extracted substantively.

### Basic concepts: types of meaning (section 1, pp. 341–344)

**Significado referencial (reference)** is explicitly argued to be insufficient as a theory of
meaning, via four arguments: (i) co-referential expressions differ in meaning (*Pedro / mi hermano /
el presidente de México* can share a referent but communicate different things — classic example:
*Lucero de la Mañana* and *Lucero de la Tarde* both refer to Venus but aren't identical in meaning);
(ii) some meaningful expressions have no referent at all (*hada, unicornio*; greetings *hola,
adiós*; connectives *pero, y, si, porque*); (iii) **deícticos** (*yo, aquí, ahora*) have a referent
that shifts with context while their meaning stays stable; (iv) meaning reflects speaker
*conceptualización*, not an objective real-world referent — worked example: *tomate* is botanically
a fruit but is conceptualized/used as a *verdura* in ordinary Spanish (you'd never say "tomates y
otras frutas"). **Sentido (sense)**, defined relationally (a word's meaning in relation to other
words in the language — the network of category/co-hyponym/associated-word relations), is adopted
as the book's working notion of meaning, since it avoids all four problems above. **Subjetividad**
(affective/subjective meaning): illustrated with the diminutive as Spanish's dedicated
affective-meaning morpheme (*Pedrito/mi hermanito* = affection; *el presidentito* = diminishing/
dismissive) and near-synonym pairs that differ only in evaluative loading (*barato* "cheap" implies
possible poor quality, *económico* doesn't; *oler* "to smell" is valence-neutral, *apestar* "to
stink" is inherently negative — "algo puede oler rico pero no apestar rico").

### Conceptualization as the object of semantic analysis (section 1.2, p. 343)

Worked discourse example (*Mi papá perdió una gran parte de la mañana en el autobús*) used to show
that virtually every lexical choice in an ordinary sentence encodes a speaker conceptualization:
*papá* vs. *padre* (formality), *perdió* vs. *pasó* (the "time is valuable, can be lost/spent/saved/
invested" conceptual metaphor — cf. *el tiempo es oro*), *una gran parte de la mañana* (an implicit
workday-centered time frame), *en el autobús* (presupposes the bus as a mode of transport in
motion, not parked). Methodological upshot: semantic analysis proceeds by examining collocational/
distributional evidence (what a word combines with, what contexts it occurs in, how it relates to
other words), since conceptualization itself is not directly observable.

### Semantic relations (section 2, pp. 345–358)

Seven relations covered systematically:

- **Sinonimia**: total synonymy is "very rare, perhaps nonexistent" in any language; partial
  synonymy (shared core meaning, differing connotation) is the norm — worked pairs: *padre/papá*
  (formality), *habitación/cuarto* (formality, but NOT fully interchangeable: *el cuarto de baño* is
  a *cuarto* but never a *habitación*), *despacio/lento* (control/agentivity: *despacio* implies
  deliberate control and often "carefully," hence occurs preferentially with human subjects; *lento*
  occurs with non-human subjects too, e.g. falling leaves/snow), *simular/fingir* (*simular* is
  usable with legitimate/positive purpose, e.g. a flight *simulador*; *fingir* is not), *elegir/
  escoger* (*elegir* specifically for vote-based selection, hence *elecciones* not *\*escogencias*).

- **Antonimia**, three structurally distinct subtypes, each with its own formal diagnostics: (a)
  **gradual** (*alto/bajo, frío/caliente*) — scalar, admits intermediate points and degree
  modification (*muy alto, friísimo*), and is reference-point-relative (an 8-year-old can be "tall"
  relative to a 6-year-old but "short" relative to a 10-year-old); (b) **complementaria**
  (*vivo/muerto, presente/ausente*) — mutually exclusive AND jointly exhaustive over their domain
  (every living being is either alive or dead, no third option), hence resists scalar modification
  (*\*muy muerto*) and reference-point relativity; (c) **recíproca/conversa** (*encima de/debajo de,
  padre/hijo, vender/comprar*) — defined by an inherent relational dimension where one term logically
  entails the other (if X is above Y, Y is below X) but, unlike complementary antonyms, does NOT
  exhaust the domain (if the book isn't on top of the table, it isn't necessarily underneath it
  either — could be beside it).

- **Hiponimia**: X is a hipónimo of Y when X's meaning is included in Y's (*gato* is hipónimo of
  *animal*; *animal* is the hiperónimo/superordinado). Multi-level hierarchies exist (*labrador* is
  hipónimo of *perro*, which is hipónimo of *animal*). A superordinate term names a **campo
  semántico** (semantic field) — a cluster of shared defining features. **Striking cross-linguistic
  worked example, directly germane to this project's cross-language conceptualization interest**:
  *tomate* and *aguacate* are hipónimos of *verdura* (not *fruta*) in everyday Spanish despite
  botanical fruit status, but *aguacate* ("avocado") is conceptualized as hipónimo of *fruta* in
  Brazilian Portuguese (eaten with sugar, in desserts) — explicit three-way diagrammed contrast
  (Spanish folk taxonomy vs. Portuguese folk taxonomy vs. scientific taxonomy) demonstrating that
  semantic category membership is conceptual/cultural, not given by objective botanical fact.

- **Incompatibilidad**: co-hyponyms of the same semantic field mutually exclude each other without
  being antonyms (*gato/perro/caballo*; colors *rojo/azul/verde/negro*). The book flags the
  antonymy/incompatibility boundary as genuinely fuzzy for pairs like *blanco/negro* (binary
  opposition, or just two members of a larger set with intermediate members like *gris*?) — and
  notes most "gradual antonyms" could equally be reanalyzed as incompatibility within a larger
  scalar set (*helado–frío–tibio–templado–caliente–hirviente*). Incompatibility is defined
  relative to a semantic field specifically to avoid a trivial/uninformative universal
  incompatibility (gato is also "incompatible" with rosa, cama, nube, but that's not informative
  since they share no features at all).

- **Homonimia**: same pronunciation (and often spelling), semantically UNRELATED meanings —
  distinguished as **absoluta** (identical grammatically, hence genuinely ambiguous in some
  contexts: *duelo₁* "duel" / *duelo₂* "grief"; *banco₁* "bench" / *banco₂* "bank" — the latter pair
  flagged as historically related via the use of benches/stools as trading tables, yet still
  classified as homonymy since speakers today perceive no semantic connection) vs. **parcial**
  (grammatically distinguished by gender: *cura₁* [m.] "priest" / *cura₂* [f.] "cure"; *papa₁* [m.]
  "Pope" / *papa₂* [f.] "potato" — also *capital, frente, corte*; or by word class: *don₁* "title of
  respect" (noun) vs. *don₂* "talent/gift" (noun, different sense) vs. the homonymous verb form
  *don* elsewhere). **Homófonos** are a homonymy subtype differing in spelling but not pronunciation
  (*votar*/"vote" vs. *botar*/"throw away"; *te*/"you" vs. *té*/"tea").

- **Polisemia**: ONE word, multiple semantically-RELATED senses (contrast with homonymy's
  unrelated-senses-same-form). Worked example: *simple* has at least 4 related senses (single-
  substance, single-part, easy/uncomplicated, bland/tasteless) — all traceable to a shared core
  notion of "lacking complexity/additional elements." The book explicitly notes **dictionaries
  formally encode the homonymy/polysemy distinction** by giving homonyms separate numbered entries
  (with superscripts) vs. polysemous senses as sub-definitions within one entry — and that RAE's own
  lexicographic choices on this boundary (worked examples: *corto, plata, piso*) are "debatable,"
  i.e. the homonymy/polysemy line is a genuine analytical judgment call, not a bright line given by
  the data.

- **Extensión metafórica**: the most common mechanism for polysemy — one salient feature of a
  source concept is transferred to a target domain. Animal-based metaphors for human traits are
  flagged as cross-linguistically common but culturally specific in which feature is salient
  (*cochino* "pig" → "dirty/messy person," based on the culturally-assumed salient trait of
  pig-filthiness — explicitly noted as NOT necessarily the salient trait in every culture; *burro* →
  "ignorant person"; *zorro* → "cunning person"). Body-part-based metaphor is a second
  highly-productive domain (*pie* "foot" → *el pie de la montaña* [bottom-of-X], *de pies a cabeza*
  [totality, extremes-of-body], *ir a pie* [means of locomotion], *pie* as a unit of length
  [size-based]; *mano* → *mano de obra* "manual labor" [paradoxically narrower than "work done with
  hands" literally would suggest — office work, painting, surgery are also hand-work but aren't
  called *trabajo manual*]; *ojo* → *ojo de la aguja* "eye of a needle" [shape-based]; *pata* →
  *pata de una mesa* "table leg" [shape AND function-based, since it supports the object like an
  animal's leg supports it]). **Two fully systematic conceptual-metaphor domains are singled out as
  book-length-worthy observations**: (i) TIME IS SPACE, future-is-ahead/past-is-behind, with time
  conceived as moving toward the speaker (*de hoy en adelante, el porvenir* [future=ahead]; *una
  semana atrás, el pasado* [past=behind]; the verbs *pasar* "to pass" for the past and *venir* "to
  come" for the future, and *ir* used to form the periphrastic future, are flagged as themselves
  metaphor-internal vocabulary) — the book states it is "difícil encontrar expresiones de tiempo que
  no se basen en esta metáfora" in Spanish; (ii) MORE IS UP / LESS IS DOWN, extended from literal
  verticality to price (*subir/bajar el precio*), rank (*ascender/descender de categoría*), age
  (*menor/mayor de edad*), educational level (*enseñanza media/superior*), and social class (*alta
  sociedad/clase baja*). The book frames metaphorical extension as occupying a genuine **continuum
  between polysemy and homonymy** — formally it's polysemy (same etymological root, one sense
  derived from the other), but because metaphor often transfers only a single salient feature across
  a genuine domain boundary (animal→human, body-part→inanimate-object, space→time), the
  relatedness can feel attenuated enough that classification becomes genuinely debatable case by
  case (worked example given: is *cochino*-the-animal and *cochino*-the-person-insult one polysemous
  word or two homonymous ones? The book declines to give a single answer, presenting it as a
  continuum, not a dichotomy.)

### Semantic roles (section 3, pp. 363–370)

Framed via the classic three-way paraphrase set *Juan abrió la puerta con la llave / La llave abrió
la puerta / La puerta fue abierta* — same semantic roles (Juan=agente, puerta=paciente, llave=
instrumento) mapped onto different SYNTACTIC roles across the three sentences, demonstrating role
and syntactic function are independent levels. Nine roles covered, each with its syntactic-position
flexibility mapped out explicitly (a genuinely systematic role-inventory a pedagogical grammar would
never present):
- **Agente**: initiates the action, typically animate, typically subject but also occurs as the
  *por*-phrase in passives, and can be the sole argument of an agentive intransitive (*correr,
  bailar, trabajar*).
- **Paciente**: affected, undergoes externally-visible change; can be animate or inanimate; most
  commonly direct object or passive/pasiva-refleja subject (*las empanadas se vendieron*); the book
  flags *nacer/morir* subjects as paciente, not agente, since the single participant didn't initiate
  the event.
- **Experimentante**: undergoes an internal (not externally visible) sensory/mental/emotional state
  — occurs as subject with perception/cognition verbs (*ver, pensar, saber*), as subject with
  *se*-marked emotion verbs (*María se asustó*) but as DIRECT OBJECT with the same verb unmarked
  transitively (*el ruido asustó a María*), and as INDIRECT OBJECT with *gustar*-type verbs (*a María
  le gusta el chocolate*) but as SUBJECT with near-synonymous ordinary transitives (*María adora el
  chocolate*) — a clean demonstration that one semantic role maps to three different syntactic
  positions depending purely on which verb/construction is chosen.
- **Instrumento vs. Causa**, formally distinguished (not just a vocabulary list): an instrument
  presupposes an (even if unexpressed) external agent using it; a cause has effect with NO external
  agent at all, typically weather/environmental (*el viento abrió la puerta* [causa] vs. *Juan abrió
  la puerta con el viento* [impossible/odd] vs. *una piedra mató a Roberta* = causa if from a natural
  landslide, but = instrumento if someone used the rock to kill her — same sentence, role determined
  by real-world construal, not syntax).
- **Recipiente vs. Beneficiario**, formally distinguished via **el dativo de interés** (a
  genuinely under-described Spanish-specific construction): recipiente = direct receiver of
  something, typically indirect object (*le dieron un ramo de flores a Jimena*); beneficiario =
  affected only peripherally/emotionally, NOT a direct event participant, marked by a dative clitic
  formally identical to an indirect object but with no literal transfer occurring (*se nos
  descompuso el televisor* — "our TV broke, [and this affects us emotionally]"; *¿se te murió el
  gato?*; *se me llevaron el último pedazo de pastel*, where the speaker is NOT the recipient of the
  cake-taking, just negatively affected by it). The two can co-occur and are then easy to tell apart:
  *el fotógrafo me le tomó varias fotos a la niña* has agente (*el fotógrafo*), paciente (*varias
  fotos*), recipiente (*la niña*), AND beneficiario (*me*) all in one clause.
- **Locativo y temporal**: spatial/temporal roles, flexible across subject, direct/indirect object,
  and PP-object positions depending on verb choice (*Nueva York es muy frío en el invierno* [locativo
  as subject] vs. *hace mucho frío en Nueva York* [locativo as PP-object]).

### Deixis (section 4, pp. 370–374+)

Defined (Greek *deiktikos* "that which points/indicates") via the classic undecipherable-note
example (*Yo te espero aquí en una hora* found on the street — uninterpretable without context
despite every word being perfectly understood). Four types: **personal** (*yo, te* — pronouns and
verbal person/number inflection are the two main Spanish expression mechanisms), **espacial**
(*aquí*), **temporal** (*en una hora*; extended discussion of how subordinate-clause reference points
can shift the deictic anchor away from the speech moment itself — *antes de que me llamaran* vs.
*después de que me llamaron* use subordinating conjunctions PLUS mood/tense morphology to redundantly
mark event order; cross-referenced to Ch.3's tense/aspect/mood discussion), and **textual** (deixis
to discourse-internal referents/events, noted but not detailed in the portion extracted).

### Discourse pragmatics (section 5, pp. 380–389)

**Oración vs. enunciado**: sentence (grammatical unit, subject+predicate, from Ch.4) is distinguished
from **enunciado** (utterance — a communicative unit/contribution to interaction, which can be a full
sentence, a sentence fragment, or even a non-sentential interjection like *¡qué frío!* or *brrr*).
The same utterance form can serve multiple communicative functions depending on context (*hace frío
aquí* can inform, request a window be closed, complain, invite someone in, or offer a coat) — and
conversely the same function can be realized by different grammatical forms (declarative/
interrogative/imperative versions of a window-closing request).

**Actos de habla (speech acts)**: **verbos performativos** are verbs whose utterance CONSTITUTES the
act named (*lo sentencio a quince años*, said by a judge in court; *los declaro marido y mujer*, said
by a priest) — formally restricted to present-indicative, 1st-person-singular subject (*¡siéntate!*
cannot be performative by definition, but *te ordeno que te sientes* can be — though not every
present-indicative-1sg sentence is performative: *yo me siento* "I sit down" is not, since saying it
doesn't constitute the sitting). Most speech acts, however, have NO performative verb at all
(*¡Siéntate!* is still a speech act — an order — despite naming no verb of ordering).

**Three-part structure of a speech act**: **acto locutivo** (the literal grammatical/semantic
content — *¿me puedes pasar la sal?* as literally a question about the hearer's ability); **acto
ilocutivo** (what the speaker INTENDS to do with the utterance — here, a request); **acto
perlocutivo** (the actual EFFECT achieved, explicitly NOT under the speaker's control — the hearer
might comply, refuse, take it as an insult about the food, etc. — crucially, the speech act's
identity as a request does not depend on which perlocutionary effect actually results).

**Five-way illocutionary act taxonomy**: **directivos** (get someone to do something: *pedir,
mandar, ordenar, suplicar, rogar* — differing in authority level; also *sugerir, recomendar,
aconsejar*, framed as for the hearer's benefit); **compromisivos** (commit the SPEAKER to future
action: *prometer, comprometerse, jurar* — *amenazar* "to threaten" is explicitly flagged as hybrid,
functioning as both compromisivo [speaker commits to an action] AND directivo [conditional on the
hearer's behavior], demonstrating the five categories are not mutually exclusive in practice);
**expresivos** (express the speaker's psychological state: *felicitar, disculparse, agradecer, dar
el pésame, dar la bienvenida, despedirse, saludar*); **declaraciones** (institutional acts that
change the state of the world by being uttered, contingent on real-world felicity conditions —
speaker authority, correct participants, proper procedure: *bendecir, excomulgar, casar, declarar
[la guerra], despedir [del trabajo], arrestar, sentenciar, condenar*); **asertivos** (describe a
state of the world, hence the only category that can be TRUE or FALSE — *aseverar, afirmar,
describir, opinar, explicar, argumentar, concluir* — explicitly noted as the category that most
often DISGUISES its real illocutionary force, since an assertion like *la jirafa es de África* can
on different occasions function as pure information, as an explanation, or as an indirect
suggestion to go see giraffes at the zoo).

**El principio de la cooperación (Grice)**: the tacit agreement to cooperate in conversation,
formalized as four maxims — **cantidad** (give as much information as required, no more); **calidad**
(be truthful, don't assert what you believe false or lack evidence for); **relación** (be relevant);
**manera** (be clear, avoid obscurity/ambiguity, be brief, be orderly). Violations (apparent or real)
generate **implicaturas conversacionales** — worked examples: *Geraldo tiene dos hijos* implicates
"no more than two" via the quantity maxim (though strictly compatible with Geraldo having five);
narrative-conjunction *y* implicates temporal/causal sequence via the manner maxim, so *Diego se
murió y fue alcanzado por un rayo* reads as backwards and odd. **Grice's key insight, explicitly
stated**: the maxims are not a prescriptive ideal speakers must follow — they are a *default
assumption* hearers use to recover meaning even when a maxim is apparently violated, by inferring
whichever implicature would restore cooperative compliance (three worked dialogue examples showing
how an apparently irrelevant/insufficient answer is reinterpreted as maximally cooperative once the
implicature is supplied). The **quality maxim is explicitly flagged as the most fundamental** (since
communication is worthless if truthfulness can't be assumed at all) but is nonetheless routinely and
acceptably overridden for politeness (*estuvo deliciosa la cena* after a barely-edible meal) — a
genuine, named exception to the "most important maxim," worth flagging for any later analysis of
politeness-driven indirectness in the target-conlang's pragmatics.

---

## Chapter 7 — Variación lingüística en español (pp. 391–444) — HIGH VALUE, FULL EXTRACTION

Author: Anna María Escobar. This is the single most dialectologically dense chapter in the book
outside Ch.2, and is treated as top priority per the dispatch brief: every explicitly-named
regional/national variant below should be read with implicit `Attested Region` = the region(s)
named, `Geographic Scope` = regional/national/transnational as appropriate, `Attested Era` =
contemporary (source published 2009/2010) unless otherwise noted, `Source Type` = grammar_reference.

### Framing: types of variation, dialect, register (section 1, pp. 391–397)

Spanish is spoken on four continents: officially in 18 American countries plus Puerto Rico and parts
of the US; in Spain; in Africa (Equatorial Guinea, Ceuta/Melilla, informally in northern Morocco);
in Asia as a minority language (Israel, the Philippines). **Three axes of linguistic variation**
are distinguished: histórica/diacrónica, social/diastrática, regional/diatópica. **Dialecto** =
regionally-defined variety, mapped via **isoglosas** (the discipline: **dialectología**).
**Sociolecto** = socially-defined variety (age, sex, socioeconomic status, ethnicity, religion);
class-correlated sociolects are named **acrolecto** (upper class), **mesolecto** (middle),
**basilecto** (lower). **Registro** = situationally-defined variety (context/interlocutor/topic,
along an informal-formal continuum) — studied by **sociolingüística**. Note on relativity: what
counts as "formal" varies by country (Costa Rican children address parents with *usted*; Peruvian
children use *tú* with parents — a formality-register fact that is itself dialectally variable, not
a fixed universal). **Norma culta oral / variedad educada oral** (the oral prestige norm,
acrolect-adjacent) is explicitly NOT a single pan-Hispanic standard — Spanish, Argentine,
Venezuelan, and Mexican educated norms are all distinct from each other.

### Spain (section 2.1, pp. 397–404)

Two principal Peninsular dialects: **centronorteño** ("Castilian" in the strict sense — what
English calls "Castilian Spanish") and **andaluz**, plus a transitional "área intermedia" the
Atlas Lingüístico de la Península Ibérica (ALPI) identifies between them, and separately the
**canario** dialect (Canary Islands) and the diaspora **judeoespañol/sefardí** (expelled 1492).
ALPI's defining isoglosses (Tabla 7.1): -d- elision in -ado suffixes; word-final -d elision;
intervocalic -d- elision (except -ado); post-vocalic -s- aspiration; final -z elision/aspiration;
aspirated vs. non-aspirated /x/; /ʎ/-/ʝ/ distinction; final -r elision; final -l elision; /s/-/θ/
distinction.

**Centronorteño** (considered relatively conservative): apicoalveolar /s/, /s/-/θ/ distinction,
/ʝ/-/ʎ/ contrast ("in retreat, not found among younger speakers" — repeating Ch.2's point).
Non-conservative features: /d/-elision in -ado and word-finally (*ciudad→[θiuðá]*), sometimes
realized as [ð̞] rather than fully dropped. Morphological: *vosotros* for informal 2pl (*ustedes*
reserved for formal 2pl); **leísmo** (direct-object *le* for masculine human referents: *Ahí está
Juan. Le veo* but *el libro lo veo*); 2pl imperative formed with the infinitive in casual speech
(*¡Comer todo!* for *¡Comed todo!*); present perfect for recent/present-relevant past (*María ha
venido esta mañana*) vs. preterite for more remote past (*Juan vino ayer*). **Sociolinguistic
micro-study, Valladolid/Logroño/Soria (Klein 2000)**: FIVE distinct pronominal-case systems
tabulated explicitly (sistema de caso [etymological]; leísmo animado masculino; leísmo animado e
inanimado masculino; leísmo animado + laísmo; leísmo animado + loísmo) — Valladolid uses
leísmo+laísmo broadly across class/sex with NO negative connotation (a genuine regional norm, not a
stigmatized error); Logroño prefers the case system but leísmo is spreading among upper-class
women, while laísmo/inanimate leísmo carry negative connotation there; Soria prefers the case
system, other systems variably stigmatized — explicit point that whether a given pronoun system
counts as "dialectal norm" vs. "stigmatized error" is itself regionally variable. **Rural
Cantabria study (Holmquist 1985, Ucieda village)**: word-final unstressed /-o/→[-u] is an archaic
retained feature, correlated with being an older male in a traditional rural occupation
(farming/shepherding) — younger, more urban-contact speakers show it less, "in possible process of
disappearance" — a clean worked example of age/occupation-correlated sociolinguistic variable
decline.

**Andaluz** (formed 13th–16th c. from northern Castilian): **seseo** (Seville, Córdoba, central
Andalusia) vs. **ceceo** (southern Andalusia and Almería — [θ] used for BOTH *s* and *z/c*, so
*casa* and *caza* both → [káθa]) vs. **distinción** (preserved in the northern/intermediate zone,
though with predorsal rather than apicoalveolar /s/) — three-way split within Andalusian Spanish
itself, not just a simple seseo-everywhere generalization. Other features: yeísmo; wider-context
intervocalic /d/-elision than centronorteño; final-nasal velarization with vowel nasalization;
retained aspiration from Latin /f/ (*humo, hambre* — "also in Extremadura, Cantabria, Asturias");
de-affrication of /tʃ/→[ʃ]; /l/-/ɾ/ neutralization syllable-finally; esdrújula stress in 1pl present
subjunctive in parts of Andalusia (*váyamos, véngamos* — explicitly cross-referenced as shared with
southwestern US Spanish, Ch.8 preview). Morphological: *ustedes* used instead of *vosotros* but WITH
*vosotros*-type verb-form alternation (*ustedes podéis/pueden*); negative-reinforcing *más* preposed
(*más nada, más nunca* — shared with the Caribbean).

**Canario**: shares most Andalusian features (seseo, s/x-aspiration, yeísmo, n-velarization,
intervocalic-d omission) plus intervocalic voiceless-stop voicing (*los zapatos→[losabádoh]*) and a
more palatal/retracted *ch* — both features ALSO found in Cuba and parts of the Caribbean (strong
evidence for the historical emigration-route connection noted in Ch.5). Also uses *ustedes* (not
*vosotros*) WITH Latin-American-style verb agreement (unlike Andalusia's mixed pattern above).

### Hispanoamérica (section 2.2, pp. 405–412)

**Six broad dialect zones** (explicitly flagged as one classification among several competing
ones; some scholars split Mexican/Central American, some merge Paraguayan with Argentine/
Uruguayan): caribeño, mexicano/centroamericano, andino (highland Venezuela/Colombia/Ecuador/
Peru/Bolivia/north Argentina), paraguayo, argentino/uruguayo ("porteño"), chileno. Classification
is explicitly based on three isoglosses — syllable-final /s/ realization ([s] retained, [h]
aspirated, or elided), syllable-final /ɾ/ realization (tap, lateralized, or asibilated [ř]), and the
/ʝ/-/ʎ/ distinction — cross-tabulated against each zone's dominant substrate/contact language in
Tabla 7.4 (reproduced in essence below):

| Zone | final /s/ | implosive /ɾ/ | /ʝ/ vs /ʎ/ | substrate language |
|---|---|---|---|---|
| Caribeño | [h] or elided | [ɾ], [l], or elided | yeísmo | Arawak (extinct) |
| Mexicano/CA | retained | [ř] | yeísmo | Náhuatl, Maya |
| Andino | retained | [ɾ] | distinction kept | Quechua, Aymara |
| Paraguayo | retained | [ř] | distinction kept | Guaraní |
| Argentino | [h] or elided | [ɾ] | yeísmo (→[ʒ]) | Guaraní, Mapudungun |
| Chileno | [h] or elided | [ɾ] | yeísmo | Mapudungun, Aymara |

**Additional phonological features by zone** (not already in Ch.2): trill velarization [ʁ] in
Puerto Rico; tap lateralization in implosive position, Caribbean (esp. Puerto Rico, Dominican
Republic: *verdad→[belðá]*); vowel nasalization near nasals in the Caribbean (parallel to
Andalusia); nasal velarization in the Caribbean, Yucatán, Central America, and the Andean zone BUT
NOT the Southern Cone (Paraguay/Argentina-Uruguay/Chile); retained /f/→aspiration in Puerto Rico,
Dominican Republic, Panama (less in Chile); voiced stops staying occlusive post-consonantally in
parts of Central America/Colombia/Andean zone; unstressed-vowel loss especially in Mexico and the
Andean zone (*todos→[toðs]*); hiatus→diphthong especially in Mexico/Andean zone (general across
most of Latin America: *real>rial, poema>puema, peón>pión*); trill asibilation in the Andean zone
and parts of Central America (Costa Rica, Guatemala), word-final tap asibilation specifically in
Mexico. **Southern Cone specifics**: word-final /d/ devoicing to [t] in Paraguay (*usted>ustet*);
/x/→[ç] before front vowels in Chile; yeísmo realized as [ʒ] in Argentina.

**Morphological dialectal features**: /-se/ plural marker in some Dominican sociolects
(*cafés>cafése*); extended diminutive use especially Mexico/Andean zone (*callandito, dositos,
ahisito, unito, ellita*); discourse-functional *le* in Mexican expressions (*híjole, ándale pues,
échale, órale*); **voseo** (popularly associated with Argentina but geographically much broader:
Central America, parts of Venezuela/Colombia, Bolivia, Chile); *che* in Paraguay/Argentina; leísmo
animado in the Andean zone, Paraguay, parts of the Caribbean; article+proper-name in Chile
(*la Tere, la Susana* — paralleled with Catalan usage, already noted); *-sen* reflexive-imperative
ending in the Caribbean (*siéntensen, vístansen* — also dialectal in Spain).

**Syntactic dialectal features**: no subject-pronoun inversion in Caribbean questions (*¿Qué tú
dices?*); preposed infinitive-subject after *para* in Venezuela/Panama/Caribbean (*para yo poder
venir*); indefinite-article+possessive, Old-Spanish-like, in Central America (*una mi amiga, un su
caballo*); *hasta* marking START rather than endpoint in Mexico/Central America (*abre hasta las
nueve* = "doesn't open until nine," i.e. opens exactly then, NOT "open until 9"); present
subjunctive replacing imperfect subjunctive in subordinates, Mexico/Andean zone (*quise que venga*
for *viniera*); present indicative replacing present subjunctive, same zones (*no creo que viene*
for *venga*); animate-determinate direct-object doubling in Chile, porteño (Buenos Aires),
Andean zone (*la vi a tu hermana*); preposition *en* before locative adverbs in the Andean zone (*en
aquí, en su delante*).

**Lexical strata (Tabla 7.6)**, four distinct categories worth distinguishing precisely: (i)
**arcaísmos** — words archaic in Peninsular Spanish but still live in Latin America (*amarrar,
gaveta, mata, botar, alcanzar, calentura, candela, bravo, liviano*); (ii) **préstamos** from
Amerindian languages, organized by source (Arawak/Taíno: *ají, barbacoa, cacique, hamaca, canoa,
maíz, tabaco, huracán, loro, caimán*; Náhuatl: *cuate, chamaco, elote, tomate, chocolate, chicle,
aguacate, cacahuete, tiza*; Quechua: *papa, palta, puna, chacra, choclo, soroche, cóndor, cancha,
ñato, alpaca*; Mapudungun: *poncho, guata*; Guaraní: *jaguar, tapioca, petunia, tucán, mangangá*);
(iii) **afronegrismos** (*banana(o), bemba, cachimbo, mucama, dengue, guandú, milonga,
bochinche*); (iv) **regionalismos** by country, explicitly tagged (mexicanismos: *chambear
"trabajar," alberca "piscina," amolar "dañar," caco "ladrón"*; peruanismos: *calato "desnudo," pata
"amigo," chato "bajo," huachafo "cursi," ñeque "tacaño"*; venezolanismos: *arrecho "molesto,"
chévere "bueno," chamo "muchacho," cuaima "ser listo"*; argentinismos: *barrilete "cometa," campera
"chaqueta," pelado "calvo," atorrante "un vago"*).

**Sociolinguistic variation case studies, Mexico City vs. Cuzco (asibilated /ɾ/)**: Perissinotto
(1975), Mexico City — 68.2% asibilation rate overall; women asibilate more than men; all age
groups asibilate frequently but youngest most; middle class slightly more than other classes;
NO negative connotation attached — concluded to be an EXPANDING feature. De los Heros (1997),
Cuzco — asibilation used mainly by men, rarely upper class; explicit attitude study found ALL
speakers assign negative connotation to it — concluded to be STABLE/RECEDING, unlike Mexico City.
**Explicit methodological point**: the same phonetic variable can be sociolinguistically
stigmatized in one dialect and unmarked/spreading in another — the variable's trajectory depends
on social perception, not just its phonetic nature.

### El judeoespañol / español sefardí (section 2.3, pp. 413–415) — full feature table + primary text

Two emigration routes after the 1492 expulsion: France/Italy/Low Countries, and
North Africa/Mediterranean/Ottoman territories (contact with Turkish, Bulgarian, Greek, Serbian,
plus Hebrew/Arabic already known from the Peninsula). **Shares seseo and yeísmo with modern
Spanish-American varieties**, but preserves older features as archaisms AND developed its own
independent post-exile innovations (Tabla 7.7, reproduced below):
- **Archaisms**: /v/ as a distinct phoneme; aspiration of Latin /f/; the voiced sibilant /z/ (*bezo,
  kaza*); the prepalatal affricate/fricative /dʒ~ʒ/ (affricate word-initially: *djénte* "gente";
  fricative medially: *mujer, ija*); voiceless prepalatal /ʃ/ corresponding to Old Castilian
  orthographic *x*.
- **Post-exile innovations**: neutralization of /ɾ/ vs. /r̄/ intervocalically (*perro [péɾo] = pero
  [péɾo]*); mid-vowel raising in unstressed position ([e]>[i], [o]>[u]: *rudiya "rodilla," muchu
  "mucho," sinyor*); diphthong reduction (*aristokrasiya, djugeves* "jueves"); metathesis of *-rd-*
  → *-dr-* (*akodrar* "acordar," *vedri* "verde," *godru* "gordo" — this specific metathesis
  pattern is noted as originating in Istanbul and spreading to the whole eastern-Mediterranean
  dialect zone); clitic-order inversion (OD-before-OI, reversed from standard Spanish); possessor
  preposed in genitive phrases (*de Moiz el padre* = "el padre de Moisés"); diminutive *-ico*
  (*ijiko, kazika*); reflexive plural *-sen* (*en biéndosen* "viéndose"); plural 3rd-person
  possessive even with a plural possessor (*sus kaza* "su casa," *sus padre* "su padre"); -ar-verb
  preterite endings borrowed from the -er/-ir conjugation (*cantí "canté," cantimos "cantamos"*).
- **Loanword strata by contact language** (Arabic: *alhad* "domingo," *alhajé* "menudillo de res";
  Hebrew: *dayyán* "juez," *shalom* "paz, hola"; Turkish: *skuralichas* "pendientes," *paras*
  "dinero"; French: *orozo* "feliz," *jandarme* "policía," *musiú* "señor").
- Israeli Judeo-Spanish specifically has been losing some archaic features (aspirated /f/, dental
  affricates) through contact with South American Spanish immigrant communities there — a case of
  one diaspora variety being re-leveled by contact with mainstream Spanish, worth flagging.
- **Primary-text sample explicitly present in the source** (Lettre Sépharade magazine, "La tia de
  Sulucha i las charukas") is a two-woman dialogue entirely in Judeo-Spanish with an attached
  glossary of its own Turkish/French loanwords (*meldar* "leer" [archaism], *haberes* "noticias"
  [Turkish], *dedikodus* "chismes" [Turkish], *charuka* "pantuflas" [Turkish]) — not reproduced
  verbatim here per copyright discipline, but flagged as a genuine primary-source parallel-text
  resource the book itself provides.

### El afroespañol (section 2.4, pp. 415–417) — brief but real feature list + poem sample

Contact languages: Kikongo, Kimbundu, Yoruba, Igbo, Ewe (West African). Named Afro-Spanish-speaking
communities: Villa Mella (Dominican Republic), Portobelo (Panama), Chocó (Colombia), Chincha
(Peru), Barlovento (Venezuela), Esmeraldas (Ecuador), Yungas (Bolivia). Features: /tʃ/,/ʝ/ → /ɲ/
(*chato>ñato, llamar>ñamar*); final-/s/ omission (*somos>somo*); /ɾ/ lateralization syllable-finally
(*carta>[kálta]*); /ɾ/-omission in infinitives (*cantar>cantá*); /l/,/ɾ/ weakening word-finally
(*mal>ma, mar>ma*); /ɾ/→[d] (*entero>entedo*) — book explicitly notes "many of these features are
also found in Caribbean Spanish and Andalusian Spanish," i.e. overlapping rather than exclusive
markers. Morphosyntactic: double negation (*nosotros no vamos no*); no subject-inversion in
questions (*¿qué tú quieres?*). A sample décima by Afro-Peruvian poet Nicomédes Santa Cruz
("Meme neguito," 1960) is present in the source as an illustrative text, not reproduced verbatim
here. Equatorial Guinea (former Spanish African colony) has Spanish as an official language,
spoken as an L2 by a majority-Bantu-L1 population; Spanish also spoken in Ceuta/Melilla and,
unofficially, northern Morocco.

### Language contact in Spain (section 3.1, pp. 417–426)

Diglossia exists to varying degrees between Spanish and Catalan, Basque/Euskera, Galician
(co-official), and Aranés/Asturian-Leonese/Aragonese (lesser, more symbolic recognition).

**Castellano-catalán contact (3.1.1)**, largest contact zone numerically (6.3M residents, 2001):
historical arc from the 15th-c. Castile-Aragon union through Franco-era suppression to co-official
status post-1978. Catalan-accented Spanish phonological features: intervocalic word-final-/s/
voicing (*lo[z] unos*); word-final /d/ devoicing to [t] (*amista[t], verda[t]*); /l/ velarization;
[v] for orthographic *v* in Valencia/Balearics/Campo de Tarragona; stressed vowels opening,
unstressed vowels neutralizing (mirroring Catalan's own vowel system). **Morphosyntactic — the
deixis-system transfer is flagged as the single most interesting feature**: Catalan's deictic
system differs from Spanish's in mapping *aquí/este/venir/traer* to the LISTENER's location as well
as the speaker's, so Catalan-dominant bilinguals extend this into their Spanish (*¿Está la María
aquí?* asked BY PHONE, where monolingual Spanish would expect *ahí*; *ya vengo* for *ya voy*) — this
is explicitly presented as a genuine semantic/deictic-system contact transfer, not merely a lexical
one. Also: article+proper-name (*la Montse*, the Catalan norm — also found in general colloquial
speech elsewhere and in Chile); periphrastic possessive preferred over pronominal-with-adverb
(*delante mío > delante de mí*); **dequeísmo** (*digo de que vengas*); double negation *tampoco no*;
preference for synthetic future (*iré a Mallorca*) — though this specific feature is noted as
DECLINING in one regional study (Castellón).

**Castellano-gallego contact (3.1.2)**: Galician's genetic/political status (dialect of Portuguese
vs. independent language) is explicitly flagged as containing BOTH linguistic and emotional/
identity criteria, i.e. a genuinely contested classification the book doesn't adjudicate. Detailed
age-stratified usage data (Tabla 7.8, Real Academia Galega) shows a generational U-shape:
"only Galician" use is much higher in the 45–54 cohort (34%) than 15–24 (19%), suggesting language
shift among the young, BUT the "more Galician"/mixed-use categories suggest growing bilingualism
rather than simple loss — explicit methodological point that raw monolingual-retention numbers
alone can mask a more complex revitalization-via-bilingualism pattern. **Three-dialect sociolectal
study of Vigo (Vidal Figueroa 1997)**, quoted in the original Galician (not translated here per
copyright, but the finding is: traditional rural Galician and urban Castilian are genuinely
distinct with under half their phonological segments shared and no detectable interference between
them in monolingual speakers, while educated urban Galician shows a "paradoxical" high degree of
phonological similarity to Castilian despite the different language labels — i.e. the
prestige/standardized variety of Galician has phonologically converged toward Spanish much more
than the traditional rural variety has). Castellano-de-Galicia features: final-/n/ velarization
and final-mid-vowel-raising (shared with Asturias); **gheada** (velar/aspirated [x]~[h] for /g/:
*gota>[xóta]~[hóta]*, transferred from Galician into Spanish by Galician-dominant speakers);
diminutive *-iño* preference (*gatiño*); preterite where Madrid would use present perfect (*hoy vi a
Juan*); post-verbal clitic position in Galician-dominant speakers (*dijístemelo*); Galician *-ra*
form used as a Spanish pluscuamperfecto indicativo (*Cuando llegué ellos ya terminaran* = "ya
habían terminado").

**Castellano-vasco contact (3.1.3)**: oldest documented contact (Glosas Emilianenses, the earliest
surviving Castilian text, written by a bilingual monk who also glossed in Basque; Basque words
appear in the Poema de Mio Cid and Gonzalo de Berceo). 2006 sociolinguistic survey data (Tabla 7.9)
shows a clear generational REVERSAL — bilingualism rising sharply among youth (57.5% ages 16-24 vs.
25% over 65) while Spanish monolingualism ("erdaldunes") falls correspondingly (17.6% vs. 66%),
attributed to Basque-government language policy and identity pride — contrasted explicitly with the
Andean-Quechua language-shift trajectory described later in the same chapter (opposite direction).
Castellano-del-País-Vasco morphosyntactic features: frequent preverbal placement of the direct
object/other complements (*Cebollas enteras dice que le metían*); preverbal affirmative *ya*
immediately before the verb (*Ya trajo* = "sí que lo trajo"); omission of inanimate object
pronouns (*—¿Compraste los sobres? —Sí, compré*); leísmo animado extended to BOTH genders (*A
Angélica le vi*) plus clitic doubling (*Le veo a Juan*); conditional replacing imperfect subjunctive
in the if-clause of conditionals (*Si le vería yo le preguntaría*). Phonological: trill
distribution follows Basque patterns (multiple trill generalized in pre/post-consonantal position,
even word-finally before a vowel for bilinguals: *por eso [por̄éso]*). **Codeswitching** is
explicitly described as common in informal bilingual contexts, with named PRAGMATIC functions
(topic-marking, authority-stance, joking-vs-seriousness, direct quotation in the other language) —
a worked Basque-Spanish mixed-sentence example is given in the source (not reproduced verbatim
here). Lexical contact: Basque diminutive *-txu* on proper names (*Javiertxu, Begotxu*) and
gentilicio-forming *-tarra* (*Bilbotarra, Donostiarra*) borrowed into Spanish.

**Internal migration in Spain (3.1.4)**: post-1990s immigration shift from internal south-to-north
migration toward Latin-American immigration, predominantly from the ANDEAN dialect zone
(Bolivia, Ecuador, Argentina, Colombia, Peru, in that order 2000-2005) concentrating in Catalonia,
Madrid, Valencia, Andalusia — with Catalonia (a bilingual region) receiving the largest share. A
Barcelona case study (Marshall 2007) found young Latin American immigrant women who are fluent in
Catalan still codeswitch into Spanish specifically for EMOTIVE lexical items (*vaina, chévere*)
even while speaking Catalan — framed as an identity-marking strategy, i.e. codeswitching serving
an affective/identity function distinct from simple lexical gap-filling.

### Spanish and Amerindian languages in Hispanoamérica (section 3.2, pp. 426–436)

Quantified Amerindian-language populations: Quechua (8-12 million, Colombia to Argentina via
Ecuador/Peru/Bolivia — the most-spoken indigenous language of the Americas); Maya languages
(~6 million, Yucatán/Chiapas Mexico + Guatemala); Guaraní (~5 million, Paraguay + border areas);
Aymara (~2 million, southern Peru/Bolivia around Lake Titicaca + NW Argentina/NE Chile); Náhuatl
(~1.5 million, Mexico); Mapudungun (<0.5 million, southern Chile/SW Argentina). Per-country
indigenous-language counts given explicitly (Peru 83, Colombia 74, Mexico 68, Venezuela 38,
Bolivia 35, Guatemala 24, Ecuador 22, Argentina 21, Paraguay 19, Chile 6) — Caribbean countries and
Uruguay have NONE. Also noted: non-Amerindian contact languages in specific countries — English in
Mexico/Panama; Garífuna (English-lexifier creole) in Guatemala's Atlantic coast; Limón Creole
(English-lexifier) in Costa Rica's Atlantic coast; Samaná English and Haitian Creole in the
Dominican Republic; Brazilian Portuguese and German-speaking populations in Paraguay; Portuguese in
Uruguay (yielding the **portuñol** contact variety); German in Chile's Los Lagos region.

**Maya contact (3.2.1)**, Mexico (Yucatán/Quintana Roo/Campeche/Chiapas) and Guatemala
(20 of 22 indigenous languages there are Mayan). Phonological: final /n/→bilabial [m] (*pan→[pám]*);
initial /f/→[p] (*feliz→[pelís]*); /s/ tends to be RETAINED, stressed vowels lengthen. Morphosyntactic:
superlative reduplication (*riquisisísimo*); redundant possessive (*su casa de Juan*); redundant
3rd-person object clitic (*Lo llamé a Juan*); extended diminutive (shared with the Andean zone);
indefinite article before possessive (*un mi sombrero*).

**Guaraní contact (3.2.2)**, Paraguay — 89% of the population is Spanish-Guaraní bilingual (Spanish
official, Guaraní national language), despite 19 indigenous languages total in-country. **Jopara**
is the named mixed Guaraní-Spanish register, "spreading especially among young speakers," occurring
in BOTH speech and writing, with documented discourse-particle borrowings from Guaraní into Spanish:
reportative *ndaje* ("se dice, según dicen"), affirmative *voi* ("pues, luego"), past-affirmative
*ra'e* ("había sido"), emphatic *-ite*, diminutive *-i* (*virumi* "platita"). Dialectal features:
asibilation of both final and multiple trill; /ʎ/-/ʝ/ distinction MAINTAINED despite Guaraní itself
lacking the lateral palatal — with /ʝ/ realized as an occlusive/affricate [ɟ] in all positions, a
feature explicitly attributed to Guaraní influence (*mayo [máɟo]*, so *cayó [kaɟó]* vs. *calló
[kaʎó]* remain distinct). Morphosyntactic (Granda 1988): gender-neutralized/invariant articles *la*
(sg.)/*lo* (pl.) (*la señor ministro*); redundant possessive; *todo+ya* emphatic completive (*Ya
trabajé todo ya*); reinforcing double negation (*Nada no te dije*); subjunctive replacing
conditional in if-then apodoses (*Si tuviera plata, comprara esa casa*); determiner+possessive+N
stacking (*un mi amigo*). Voseo and porteño *che* also occur in Paraguay.

**Quechua/Aymara contact (3.2.3)** — the named "español andino" dialect, concentrated Ecuador/
Peru/Bolivia. Explicit scholarly consensus noted: Andean indigenous languages are generally
considered to be undergoing LANGUAGE SHIFT toward Spanish (attributed to non-rising monolingual
rates, inter-dialect Quechua intelligibility problems, Spanish use even in Quechua-dominant homes,
and rural-to-urban migration since the 1950s) — BUT the chapter also notes a counter-trend: as
migrants move to cities, Quechua (and in places Aymara) is becoming more widely used THERE too,
diffusing beyond its traditional rural base. Government support ranked Bolivia > Ecuador > Peru.
Ecuador-specific feature: a focus-marking particle *-ga*, not found in Peru — flagged as a case
where "Andean Spanish" is not phonologically/morphosyntactically monolithic across countries, only
broadly similar. Common Andean features (Escobar 2000): trill asibilation (shared Costa
Rica/Guatemala/Paraguay); unstressed-vowel loss (shared Mexico); /o/→[u], /e/→[i] in Quechua-dominant
speakers' Spanish (explicitly attributed to Quechua's 3-vowel system — *señor→[siɲúř], niño→[níɲu]*);
extended diminutive (shared Mexico); redundant direct-object pronoun (shared Southern Cone: *lo
visité a mi papá*); redundant possessive; demonstrative+possessive+N stacking (*este mi ganado*);
conditional-for-subjunctive in if-clauses (*Si tendría dinero, compraría* — explicitly cross-
referenced as ALSO occurring in Basque-contact Spanish, i.e. two historically unrelated contact
situations independently producing the same morphosyntactic substitution); object/adverbial/PP
fronting to sentence-initial position (*Harto hemos correteado*); object-pronoun omission (*—¿Sabes
que el señor Quispe se murió? —No he sabido*); **pluscuamperfecto for reported/indirect knowledge**
(*Juan había vivido en Lima* can mean "[I've heard that] Juan lived in Lima" — an evidentiality-
marking extension of a tense form, genuinely striking and worth flagging for mechanics-analysis
work on evidentiality). **Lima norma-culta innovation note (Escobar 2007)**: several of these
contact-induced features (reportative pluscuamperfecto; present-perfect used for emotionally
significant past events without the usual recency restriction, *mi padre ha muerto en 1980*;
English-like progressive-as-simple-present *estar+gerundio*, *¿en qué parte de los Estados Unidos
está viviendo Susana?*; dequeísmo in nominal contexts, *la razón era de que tenía novia*) have
PENETRATED the educated/prestige norm of Lima itself — not just rural or migrant speech — supporting
Escobar's proposed reframing of internal Latin American rural-to-urban migration as "contacto de
lenguas encubierto" (covert language contact), since conventional dialect-contact framing misses
these more semantic/discursive (vs. purely phonological/lexical) transfer effects.

**Fronterizo** (Uruguay-Brazil border Portuguese-Spanish contact variety): nasalized vowels, /v/
and voiced /z/ as phonemes — explicitly NOT a single uniform variety but "a series of varieties"
closer to Spanish or Portuguese depending on speaker/region.

**Internal migration in Hispanoamérica (3.2.4)**: urbanization rates given per country (Uruguay
93%, Argentina 91%, Chile 88%, Brazil 84%, Mexico/Peru 76%, Ecuador 63%, Bolivia 64%, Paraguay 58%,
Guatemala 47%) — the more rural/indigenous-population countries are also the less urbanized ones.
Mexico-specific: migration flows from poorer, more-indigenous southern states to the center/north
(especially Mexico City, 20 million residents), driven by work/family/health-safety factors;
migrants are younger (22-23) than non-migrants (27-28). External Hispanic emigration (2005):
~25 million total, 18 million in the US, 4 million within Latin America/Caribbean, ~1 million in
Spain — chiefly from Mexico, Colombia, the Caribbean, with Argentina/Venezuela/Andean countries
also contributing.

### Spanish-based creole and pidgin languages (section 3.3, pp. 436–439)

Creoles arise from pidgins (recapping Ch.1's pidgin/creole discussion) in European-colonial forced-
labor contexts; pidgins themselves are described with concrete structural correlates (no verb
conjugation, no gender/number agreement, no subordination, a minimal pronoun set, CV/V syllable
structure only). **Palenquero** (San Basilio de Palenque, Colombian Caribbean coast) — spoken by
descendants of escaped 16th-c. African slaves; isolated for centuries, now endangered as increased
Spanish contact (for sugar-industry work) erodes it, though experiencing a cultural
(if not linguistic-vitality) revival via music; influenced by both African AND Amerindian
languages, not just Spanish. **Papiamento** (Aruba/Bonaire/Curaçao, official alongside Dutch) — a
Portuguese-Spanish-lexifier creole with heavy Dutch influence; shows mixed-source grammar (Spanish-
style present participle *-ando/-iendo*; Dutch *wordu* "to become" OR Spanish *ser* for passive,
depending on sub-variety; *ta* in verb phrases traceable to either Spanish or Portuguese) — explicitly
noted to have internal variation BETWEEN the three islands' varieties. **Chavacano/Chabacano**
(Philippines, Zamboanga variety most prominent, Mindanao) — named but not detailed in the extracted
portion. **Media lengua** (San Miguel de Salcedo, Ecuador) is explicitly distinguished from the
above as a non-creolized PIDGINIZED variety with NO native speakers: ~90% Spanish-derived lexicon
but Quechua phonological/morphosyntactic structure, mutually UNINTELLIGIBLE to both Quechua speakers
from elsewhere and ordinary Spanish speakers — a striking real-world case of near-total
lexicon/grammar decoupling across two unrelated source languages, worth flagging directly for this
project's own derived-conlang-synthesis methodology as a real-world precedent for borrowing a
donor language's vocabulary wholesale while running it through a structurally unrelated
substrate grammar.

---

## Chapter 8 — El español en los Estados Unidos (pp. 445–502) — HIGH VALUE, FULL EXTRACTION

Author: Anna María Escobar. New in the 2nd edition. Per the dispatch brief, treated as high-value
for its dialectal/sociolinguistic content; the purely demographic/census-statistics material
(sections 1–2) is summarized rather than exhaustively reproduced (hundreds of census percentages
add little to a linguistics-focused extraction), while the linguistic-feature and language-contact
sections (3–6) are extracted in full detail.

### Sociohistorical background and demographics (sections 1–2, pp. 445–460) — summarized

Spanish presence in US territory predates the Mexican-American War by centuries: St. Augustine, FL
(1565, the first Spanish settlement in what is now the US); Santa Fe (1609); Tucson-area missions
(1692, 1700); San Antonio (1718); San Diego/San Francisco/Los Angeles (1769–1781). Spain lost
Louisiana (1800) and sold Florida (1821); Mexican independence (1821) transferred the rest; Texas
independence/annexation (1836/1845); the Mexican-American War and Treaty of Guadalupe-Hidalgo
(1848) transferred roughly half of Mexico's territory to the US with NO language-rights provision
for the new Spanish-speaking citizens — the book frames this explicitly as the origin point of
Spanish speakers' "second-class" sociolinguistic status in the new territories. Puerto Rico ceded by
Spain to the US (1898), Commonwealth status from 1952. **Three major immigration-origin groups**
(Tabla 8.1), each with a distinct migration history and demographic profile: Mexican (66% of
Latinos, youngest average age 24.4, waves tied to the 1910 Revolution/Bracero Program/1965
Immigration Reform Act), Puerto Rican (9%, circular migration pattern, US citizens since 1917),
Cuban (4%, oldest average age 40.3 and highest economic resources, three waves tied to
pre-1959/Batista-flight/Mariel-1980 political refugee status). A fourth catch-all category
(Dominican, Central American, South American) has grown since the 1980s–90s, driven by civil wars
(Nicaragua, El Salvador, Honduras, Guatemala) and economic crisis. By 2007 Latinos were 15.1% of
the US population (45.5 million) and the largest minority group; projected 24.4% by 2050. Regional
settlement concentrates in states that were formerly Mexican territory (highest: New Mexico 44.7%,
California 35.9%, Texas 35.6%) plus Florida, New York, New Jersey, Illinois. Latino population is
notably younger (27.3 years average, 2006) than the US population overall (36.5 years).

### Dialectal and sociolectal linguistic characteristics (section 3, pp. 460–471) — FULL EXTRACTION

**Language-use framing**: ~50% of US Latino households use Spanish (alone or with English) at home
nationally, rising to 68.9–91.9% in border/high-concentration areas (El Paso, Laredo, East LA,
Hialeah FL) — the book explicitly argues against a simple "Spanish is being lost" reading of
national-aggregate data, since locally-concentrated usage remains very high. **Silva-Corvalán's
generational framework** (Tabla 8.15) is given as the standard analytic tool: first/second/third
generation defined by birthplace, parents' birthplace, age of arrival, and residence length —
explicitly NOT equivalent to Spanish-monolingual-education status (since bilingual ed. is rare for
most informants). Otheguy/Zentella/Livert (2007, New York) found a need to further split first-
generation speakers by residence length (under 5 years vs. over 10), since long-resident first-
generation speakers' Spanish itself CHANGES through contact with other Spanish dialects in the US —
a genuinely important methodological point (dialect leveling happens even within "first
generation," not only across generations).

**Rural/popular pan-Latin-American features found in US Spanish** (Tabla 8.16, cf. Espinosa 1911,
Lipski 2008): intervocalic /ʝ/ weakening (*gallina→[gaína], silla→[sía]*); unstressed-vowel loss
(*acabar→cabar*); mid/high vowel variation (*entender→intender*); stress shift (*háblemos,
váyamos*); -ado→-au (*comprado→comprau*); irregular-participle regularization (*abrir:abrido*);
verb-paradigm regularization (*pudo→pudió*); [x] for [f] (*jue* for *fue*); popular forms/archaisms
(*naiden, trujo, mesmo, asina, vido, agora*). **Isleño** (St. Bernard Parish, Louisiana, descended
from late-18th-c. Canary Islands immigrants, now endangered — Lestrade's study found the CULTURE
transmitting to younger generations even as the LANGUAGE itself loses ground, a genuine
culture/language decoupling worth flagging): sporadic intervocalic voiced-stop omission
(*todito→toíto*), [b]/[v] alternation, final unstressed mid-vowel raising, Andalusian/Canarian
features (s-aspiration, l/r neutralization); morphologically, *los* for 1pl subject (*nos
vamos→los vamos*) and *-nos* for *-mos* (*fuéranos*) — ALSO found in Mexican-American Spanish;
syntactically, preverbal subject pronoun in questions (Caribbean-like: *¿cómo tú dices?*) and
preposed infinitive subjects (*pa un niño nacé*).

**Mexican-American Spanish specifics** (vs. other US Latino groups): phonological — implosive /s/
retention; hiatus→diphthong (*cohete→[ku̯éte]*); diphthong monophthongization (*tienen→tenen,
pues→pos*); /tʃ/→[ʃ] fricativization (*muchacho→[muʃáʃo]*, esp. New Mexico/Texas border and
characteristic of northern Mexican Spanish); /x/ aspiration (*México→[méhiko]*); intervocalic /ʝ/
omission near /i,e/ (*silla→[sía]*); epenthetic final [-e] after stressed-liquid-final syllables,
specifically traditional New Mexican Spanish (*Isabel→[isabéle], comer→[koméɾe]*); word-initial
/s/-aspiration, also specifically traditional New Mexican (*la semana→[lahemána]*); /e/→[i] after
/tʃ/ (*noche→[nóʃi]*). **Archaic /v/ phoneme** preserved specifically in New Mexico/southern
Colorado Spanish (*vivo [vívo], había < ant. hauia*) — alongside a SEPARATE, modern [v]
reintroduced via English contact (*valor, recibir* ← English "receive") — explicitly flagged as two
historically unrelated sources of [v] coexisting in the same dialect, a genuinely subtle point.
Morphological: 1pl subjunctive -mos→-nos with stress shift (*vayamos→váyanos*); extended -nos in
other 1pl forms (*íbanos, estábanos*); *estar* used where other varieties require *ser*
(*está soltero*); -ir preterite conjugated as -er (*salimos→salemos*); diphthong regularization in
1pl (*piensamos, sientimos*); -n added to 1pl imperatives before a clitic (*dénmelo→démenlo*);
extended *estar+gerundio* for simple present (*estoy oyendo*); gerund-as-adjective/nominalized
gerund (*las compañeras enseñando español*; *lo que hace es comparando precios*); *imperfect of
ir+participle* for pluperfect (*había comido→iba comido*); extended *qué* in questions (*¿qué te
llamas?*); extended passive use; *que*-omission in nominal subordinates (*Yo creo Ø inventaron el
nombre*); *para+subject pronoun+infinitive* (*No hay tiempo para yo poder comprar algo*); redundant
possessive (*les lavó la cara→lavó sus caras*); preference for preterite/imperfect over the full
tense system and *ir+infinitive* for future; imperfect preferred with state verbs, preterite with
activity verbs; *hasta* marking event-START (cross-referencing Ch.7's Mexican/Central American
feature). **Mexican lexical items**: *güero* (rubio), *chamaco* (niño), *lana* (dinero), *popote*
(sorbete), *papalote* (cometa), *híjole* (asombro), *ándale* (¡vamos!) — with a footnoted scholarly
reanalysis (Cacoullos 2002) that *le* in Mexican Spanish has GRAMMATICALIZED beyond a pronoun into a
discourse intensifier that attaches even to intransitive verbs (*córrele, ándale, échale*).

**Puerto Rican/Caribbean features in the US**: s-aspiration/omission (*mismo→[míhmo]*); /x/
weakening; /n/ velarization; /ɾ/-/l/ neutralization/lateralization (*por favor→pol favol*); liquid
omission (*comer→comé*); velarized multiple trill [ʁ] (*carro [káʁo]*); Dominican /-se/ plural
marker. Morphosyntactic: preverbal subject pronoun in questions (*¿qué tú quieres?*); *para+subject
pronoun+infinitive*; preposed *más* before negatives (*más nadie, más nunca*).

**Central American features, broken down BY COUNTRY (high specificity, worth preserving
distinctly)**: shared features — *vos* for *tú*, nasal velarization; lexical: *chele* (rubio),
*pisto* (dinero), *cipote* (niño pequeño). **Guatemalans**: final/pre-/s/ pronunciation + unstressed-
vowel reduction near /s/ (*pres(i)dente*); affective *usted* in informal/rural contexts alongside
rural *vos*/urban *tú*; indefinite-article+possessive+N (shared with Hondurans/Salvadorans: *una mi
amiga*); lexical *patojo* (niño), *canche* (rubio), *chompipe* (pavo), *chapín* (guatemalteco).
**Salvadorans**: final-/s/ aspiration (Caribbean-like) PLUS word-initial /s/-aspiration (shared with
Hondurans: *[h]emana*); word-internal syllable-initial /s/→[y] (*casa→[káya]*); lexical *cipote*,
*caites* (sandalias). **Nicaraguans**: prefer *tú* over *vos* (unlike most of the region); final-/s/
and /x/ aspiration (shared with Salvadorans/Hondurans/Caribbean); lexical *reales* (dinero),
*chavalo/chigüín* (niño), *chunches* (cosas).

**Caló/Pachuco — HIGH VALUE named US-specific slang register, full vocabulary table** (pp. 469–471):
originally a young-men's in-group speech style (now also used by young women) in the Southwest,
associated with a broader non-linguistic subculture (fashion, cars, music). The book explicitly
addresses the **variety-vs.-jargon classification question**: a true sociolect/variety has features
at every linguistic level (phonological, morphological, syntactic, lexical); a mere jerga/argot/
jargon is lexical-only — caló/pachuco is presented as having BOTH substantial lexical content and
real morphosyntactic features, hence closer to a genuine sociolect than a simple slang wordlist,
though this classification is explicitly noted as having been debated in the scholarship.
**Etymological origin**: ultimately traceable to Spanish Romani (gitano/Caló) brought from Spain,
but the modern US variety is its own independent development, drawing on colloquial Mexican/New
Mexican/Texan Spanish plus English; diffused outward from El Paso across the Southwest. **Lexicon**
mixes English loans (*chante/cantón* "casa" ← Eng. "shanty"; *rol* "automóvil" ← "roll"; *flicas*
"películas" ← "flickers/movies") with caló-proper coinages (*entacucharse* "vestirse elegantemente,"
*frajo* "cigarrillo," *gacho* "malo," *liquellar* "mirar") AND semantically-shifted general-Spanish
words (Tabla 8.17: *al alba*→"alerta," *clavar*→"robar," *refinar*→"comer," *el mono*→"la película,"
*carnal*→"hermano," *alba*→"excelente," *chupar*→"fumar," *garras*→"ropa," *suave*→"bueno,"
*lisa*→"camisa" — explicitly the semantic-shift category most relevant to this project's own
slang-formation-mechanics modeling). Morphosyntactic feature: named discourse markers specific to
the register (*nel* "no," *ve* "oye," *sabe qué* — illustrated with an untranslated original Barker
1975 dialogue sample, not reproduced here per copyright discipline).

### Dialect contact (section 3.2, pp. 471–476)

Named US contact zones by dialect pairing: LA/Houston — Mexican vs. Central American (esp. Salvadoran
/Guatemalan), with Central American s-aspiration and *vos* competing against Mexican features; Miami
— Cuban vs. South American (esp. Colombian) and Central American (Nicaraguan/Honduran), influence
direction "not yet clear"; Chicago — Mexican vs. Puerto Rican, Guatemalan, and Ecuadorian (Andean);
New York — Puerto Rican/Dominican (Caribbean) vs. Mexican and South American (esp. Colombian);
smaller cities — Lorain OH and Kennett Square PA (Puerto Rican vs. Mexican contact, also documented).
**Koinización/convergencia lingüística**: dialect contact in the US is explicitly framed as driving
toward a leveled "koiné" variety that sheds dialect-marking features from any single source
dialect — named and theorized (Otheguy & Zentella 2007), not just described impressionistically, as
an active process across multiple US cities, not only the largest ones.

### Spanish-English contact features (section 4, pp. 476–482) — HIGH VALUE for borrowing mechanics

**Grammatical loan-suffixes from OTHER contact languages, offered as comparison class**: Basque
*-tarra* for gentilicios in Basque-contact Spanish (cross-referencing Ch.7); Quechua diminutive
*-cha* (*mamacha*) and plural *-kuna* (*ovejakuna*) in Andean Spanish; Guaraní diminutive *-í*
(*Joseí*) and plural *-kuéra* (*amigokuéra*) in Paraguayan Spanish — establishing that borrowed
bound morphology is a cross-linguistically real phenomenon in Spanish contact situations generally,
not unique to English contact.

**English-origin discourse markers in US Spanish**: high-frequency borrowed connectives *and, so,
y'know, anyway, but, I mean, well*. Torres (2003) study of NY Puerto Rican 2nd/3rd-generation
speech finds *and* (clause-initial connector), *so* (introduces a result/conclusion), and *y'know*
(marks interlocutor engagement/evaluation) — frequency of discourse-marker borrowing rises with
generation (2nd gen: 31–50% of relevant contexts; 3rd gen: 49–76%), correlating with English
dominance. Torres & Potowski (2009), comparing *so* vs. native *entonces* in Chicago Mexican/Puerto
Rican/Mexican-Puerto Rican speech, found *so* more frequent among Puerto Ricans and
Mexican-Puerto Ricans than pure Mexicans, independent of generation — i.e. ethnic-group identity
affects borrowing rate independently of generational English-dominance.

**Calco gramatical / transferencia de patrón de uso** (grammatical calquing / usage-pattern
transfer — explicitly distinguished from borrowing a form/sound, since here only a RULE or
STRUCTURE transfers): Silva-Corvalán's (1994) LA Mexican-Spanish list — *que*-omission (*Te ruego
Ø me lo envíes*); redundant subject pronouns (*Mañana nosotros vamos a visitarte*); redundant
possessives (*Nos lavamos nuestras manos*); discourse *ahora* (a Spanish word used with a new,
English-influenced discourse function). Additional documented patterns: gerund-as-adjective/
nominalized gerund; extended passive (*Las flores fueron traídas desde lejos*); *para+subject
pronoun+infinitive*; REDUCED subjunctive use (*Me habló como si no pasó nada* for *hubiera
pasado*). The book is explicit that English's causal role in favoring these patterns is NOT firmly
established — they could be contact-accelerated internal-Spanish tendencies rather than pure
calques, a genuine methodological caveat worth preserving.

**Codeswitching — full typology, Poplack's formal constraints, and literary parody text**:
Poplack & Meechan's (1995) definition quoted (juxtaposed sentences/fragments, each internally
consistent with its own lexifier language's morphology/syntax). **Three types** (Poplack 1980):
**interoracional** (switch between clauses: *...when she asked me ¿qué te pasa, hija?*);
**intraoracional** (switch within a clause: *There was a guy, you know que he se montó*);
**marcador discursivo** (discourse-marker switch, borderline borrowing/switching: *y'know, le
pregunté...*). **Two formal constraints governing intrasentential switching** (directly useful for
modeling contact-grammar limits in the slang-synthesis pipeline): (i) **free morpheme constraint**
— the morphophonology of the two languages cannot mix WITHIN a single word (predicts the
non-occurrence of hypothetical forms like *\*eat-iando*, an English root + Spanish gerund suffix);
(ii) **equivalence constraint** — a switch point is only licensed where the word order of both
languages coincides at that point, with five named licit switch-point types (subject-NP/predicate
boundary; copula/predicate-adjective boundary; verb/complement-clause boundary; subordinating-
conjunction/clause boundary; noun/relative-clause boundary) and explicitly marked ILLICIT switch
points (clitic pronoun+finite verb split across languages; subject pronoun+finite verb split;
auxiliary *haber*+participle split; negator+finite verb split; interrogative pronoun+finite verb
split) — these ungrammatical combinations are given with asterisked examples in the source. Finding:
intrasentential codeswitching specifically correlates with HIGH dominance in BOTH languages, not
low competence in either — i.e. codeswitching of this type is a skilled bilingual phenomenon, not a
deficiency marker. Pragmatic functions of codeswitching (non-exhaustive, Gumperz/Poplack/Myers-
Scotton): topic shift, emphasis, reported speech, added/parenthetical information, clarification/
translation, metalinguistic commentary. **Ilan Stavans' "Spanglish" translation of the opening of
Don Quijote** is present in the source as a pedagogical exercise text (reproduced with an attached
critical quote from Lipski calling out its syntactic code-switching violations and its register-
stereotyping implications that "only uneducated people speak Spanglish") — flagged here as existing
in the source but not reproduced verbatim per copyright discipline; the pedagogical point made is
that a deliberately exaggerated "Spanglish" text can and should be checked against Poplack's actual
empirical switch-point constraints, and often fails them.

### Macrosociolingüístico factors in maintenance/loss (section 5, pp. 482–491) — summarized with key findings

Silva-Corvalán's generalization: Spanish is maintained at the COMMUNITY level but lost at the
INDIVIDUAL level from the third generation onward. **Zentella's (1997a) longitudinal El Bloque (NYC)
study**: children's eventual bilingual competence level is predicted by whether their PARENTS spoke
Spanish to each other and to the child in childhood — parents using English or mixed input predicted
English-dominant/monolingual children — i.e. home language ecology in early childhood is the single
most load-bearing predictor identified. Potowski's (2008a) Chicago study of Mexican-Puerto Rican
mixed-heritage children found they retain the MOTHER's dialect features specifically, with
Spanish-maintenance declining each generation regardless. Zentella and Valdés both stress that
raw "competence level" is too coarse a measure — WHICH variety (rural/popular Spanish vs.
standardized Spanish vs. codeswitching-heavy Spanish; and on the English side, Puerto Rican/Chicano/
Hispanicized English vs. African American Vernacular English vs. standard English) a speaker
commands is equally important, and tied to social-network structure. **Diglossia debate**: the
classic Fishman (1972)/Ferguson (1959) claim that stable bilingualism requires diglossic functional
separation between the two languages is explicitly tested and found NOT to hold in a specific US
case — the McAllen-Edinburg, Texas border-town longitudinal study (Mejías, Anderson-Mejías & Carlson
2003, a 20-year follow-up of Mejías & Anderson 1988) found fully bilingual young people with NO
functional division between English/Spanish use, attributed to regional economic growth and
Spanish's entry into local politics, higher education, and press — and found a MOTIVATION SHIFT
over the 20 years: 1980s students maintained Spanish for communicative/instrumental reasons
(talking to grandparents), 2000s students framed it as linguistic/cultural LOYALTY instead — a
genuine attitudinal-shift finding across one generation in one community, worth flagging.
**Macro-level maintenance factors enumerated** (Tabla 8.19): government language policy; bilingual
education availability; use in public/social services (hospitals, banks, libraries, churches, social
welfare offices); media presence (TV, radio, press, internet); presence in courts (incl.
translators); economic integration (ability to use Spanish AT WORK while still supporting a family);
Anglophone community attitudes toward Spanish speakers. **English-only movement** history: no
federal language-rights provision accompanied the Treaty of Guadalupe-Hidalgo; California's 1849
constitution REQUIRED Spanish-language law publication, but was reversed by 1878–79 to English-only;
corporate English-only mandates (e.g. Ford) from the early 20th century; the 1968 Bilingual
Education Act (first federal funding for bilingual programs); *Lau v. Nichols* (1974 Supreme Court
case establishing a right to native-language instruction on educational-equity grounds); the 2001
No Child Left Behind Act, which the book explicitly frames as having WEAKENED the prior bilingual-
education mandate via English-only standardized testing requirements tied to federal funding
decisions. By 2008 only 9 states required bilingual-education provision (Texas, New York, Florida,
Illinois, Colorado, New Mexico, Michigan, Oklahoma, Nebraska); 30 states have English as the
official state language despite 92% of residents already speaking English "very well" per census
criteria — the book flags this juxtaposition (official-English laws in a population that is already
overwhelmingly English-proficient) as revealing the symbolic/political rather than practical-
necessity character of such laws.

---
