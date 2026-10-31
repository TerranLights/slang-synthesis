# Spanish — Established Vocabulary/Grammar: Webster's New World Spanish Grammar Handbook (full-book extraction)

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook*, 1st Edition (Wiley, 2005). 387
PDF pages. **Correction to the project's original triage catalog**, which flagged this source as
having a "sparse text layer": independently re-verified and found to have a genuinely RICH, clean
text layer throughout (embedded subset Type 1C fonts, strong accented-character extraction confirmed
across the whole book — 1,000+ á, 2,000+ í, 240+ ñ, etc.). No vision-reading was needed anywhere in
this book; extracted in full via `pdftotext -layout` across PDF pages 1–372 (the back-matter index,
pp. 366–387, is pure page-number cross-reference with no extractable content and was skipped per the
coverage rule), split across three dispatch chunks (pp. 1–130, 131–260, 261–387) that are combined
here into one file, each kept as its own "Part" below with its own detailed source/scope note.

**Coverage note:** every grammar point and every distinct vocabulary item from this book's Parts I–XV
plus its Appendix B thematic vocabulary lists, plus every explicit dialectal/regional annotation the
source itself marks (Spain vs. Latin America usage splits, and specific-country vocabulary variants
within Latin America). Repeated drill exercises and duplicate example sentences that don't introduce
new vocabulary or grammar are skipped; Appendix A's ~80 pages of regular/stem-changing/irregular verb
conjugation charts were skipped as fully redundant with this corpus's existing `007`/`008`/`008b`/`008c`
verb-tense files (exemplar verb names listed for audit trail instead of reproducing the tables), as
was the book's own English grammatical-terminology glossary (not Spanish-language content).

**Non-redundant-supplement handling (applies across all three parts):** this Spanish corpus already
has 15 base established files (001–015) covering standard pedagogical grammar comprehensively. Each
part below states explicitly what was treated as "previously covered, not re-extracted" (basic
articles, basic regular-verb present tense, days/months, basic numerals, short-form possessives, full
compound-tense/mood paradigm charts already in 008b/008c, basic adjective agreement, basic negation,
full verb-conjugation paradigm charts) versus kept in full (ordinals/fractions, the full article
use/omission rule set, noun-gender exceptions, long-form possessives, the complete pronoun system
including its Spain/Latin-America dialectal split, virtually the entire verb-tense/mood apparatus
including the preterit perfect and sequence-of-tenses/conditional-sentence tables not found in any
prior file, the full command/imperative system, infinitive-derivational morphology, the entire
preposition/conjunction system, the relative-pronoun system, a curated set of colloquial reflexive-
verb idioms of direct relevance to the slang-synthesis project, and Appendix B's ~30 thematic
vocabulary categories in full, since a different author's own vocabulary examples are not redundant
by default per the extraction spec).

**Notable dialectal/register findings:** explicit Spain-vs-Latin-America split for the direct-object
pronoun *le* (Spain) vs. *lo* (Latin America); an explicit note that *vosotros* is Spain-primary but
"widely used in Argentina," contradicting a flat Spain/Latin-America generalization; an explicit
regional vocabulary split for everyday terms (peanut: Spain/Mexico vs. rest of Latin America; green
beans and boulevard/zócalo: Mexico-specific; rubber: Latin America generally vs. Colombia/Peru
specifically); an indefinite-*se* passive-voice nuance (using *le/les* rather than *lo/los* for a
masculine human direct object) not previously captured in `008c`'s existing passive-voice summary.
Several source-side typos/misprints are noted inline in Part 3 rather than silently corrected.

---

## Spanish — Established Vocabulary/Grammar: Webster's New World Spanish Grammar Handbook, Parts I–II (Everyday Necessities; Markers, Nouns, Possession, and Personal Pronouns)

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook* (1st ed., Wiley, 2005),
ISBN 978-0-7645-7897-7, printed pp. 1–50 (Part I "Everyday Necessities": Numbers, Dates and More,
The Weather, Time; Part II "Markers, Nouns, Possession, and Personal Pronouns": Markers, Nouns,
Possession, Personal Pronouns). This is the first of two files covering this subagent's assigned
PDF page range (1–130, printed pp. 1–115); Parts III–V (Simple Tenses; Simple Moods; Gerunds and
Progressive Tenses) are in `022_chunk1b.md`.

**Correction to prior triage confirmed:** this source has a genuinely rich, clean PDF text layer
throughout this range. `pdftotext -f N -l M -layout` extracted every page cleanly — no column
scrambling, no font-substitution cipher, no marginalia of any kind. Cross-checked several vocabulary
boxes (numbers, demonstrative adjective/pronoun tables, feminine-ending tables) for layout
corruption; none found. No vision-reading was needed anywhere in this range.

**Non-redundant-supplement scope note.** Skimmed `005_practice_makes_perfect_basic_spanish_grammar.md`
(beginner workbook, Lessons 1–50) and `009_practice_makes_perfect_spanish_vocabulary.md`
("Preliminary matters" unit) before extracting, per dispatch instructions. **Skipped as
redundant** (already fully captured in 005/009, not re-extracted here): days of the week, months of
the year, cardinal numbers 0–100, basic definite/indefinite article gender-number paradigm tables,
basic subject pronoun paradigm (yo/tú/él.../nosotros...), basic possessive-adjective short forms
(005 Lesson 14), the alphabet/cognate material. **Kept as genuinely new or deeper** (this file's
actual content): ordinal numbers, fractions, multiples, weather/temperature/season vocabulary, time
telling and 24-hour-clock conventions, date-related vocabulary, the definite/indefinite article USE
and OMISSION rules (not just the paradigm), the geographical-names-with-definite-article list,
demonstrative adjective/pronoun full paradigms + the "pejorative when postposed" and "former/latter"
usages, noun gender beyond the basic -o/-a rule (thematic-group masculine nouns, feminine-ending
suffix groups, same-noun-both-genders, distinct-gender-pair nouns, gender-changes-meaning nouns,
epicene animal names), plural-formation exceptions, possessive LONG forms and possessive pronouns
(not covered by 005's short-form-only treatment), and the full personal/prepositional/object pronoun
system (prepositional pronoun forms, direct/indirect object pronoun tables including the explicit
Spain-vs-Latin-America le/lo split, verbs requiring direct vs. indirect objects, the personal *a*,
gustar-type verbs, double object pronouns, pronoun-placement/accent rules). This file's vocabulary
table therefore skews toward phrase-level and thematic-list items rather than isolated nouns, since
that is what is genuinely new here.

**High-value dialectal/register finding (flagged per spec, never skip):** this source explicitly
marks (1) the Spain-vs-Latin-America split for direct object pronoun **le** (Spain, for "him"/formal
"you") vs. **lo** (Latin America, for the same referents) — p. 45 — and (2) that **vosotros** is used
primarily in Spain, only rarely in Latin America generally, but is explicitly noted as **widely used
in Argentina** — p. 43. Both are captured as Attested Region-tagged vocabulary/grammar-note entries
below.

**Whole-section source attributes** (apply unless otherwise noted): Source Type = `grammar_reference`;
Attested Era = "contemporary (source published 2005)"; Transcription Confidence = `n/a`; Vision
Reading Confidence = `n/a` (real text layer throughout).

---

### Vocabulary

#### Ordinal numbers, fractions, multiples (pp. 7-11)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| primero, segundo, tercero, cuarto, quinto, sexto, séptimo, octavo, noveno, décimo | 1st-10th | ordinal adj. | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | ordinals only used through 10th; cardinals replace them afterward, p. 7 |
| el primer piso / el tercer ascensor | the first floor / the third elevator | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | primero/tercero drop final -o before masc. sing. noun, p. 8 |
| medio(a) / la mitad de | half | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | medio is adj. (agrees w/ noun); la mitad is the noun form, p. 9 |
| un tercio, un cuarto, dos tercios, tres cuartos, cuatro quintos, un sexto...un décimo | 1/3, 1/4, 2/3, 3/4, 4/5, 1/6...1/10 | fraction (noun) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | numerator=cardinal, denominator=ordinal through tenths, p. 9 |
| un doceavo, un quinceavo, un veinteavo, un treintavo | 1/12, 1/15, 1/20, 1/30 | fraction (noun) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | fractions beyond 10ths add -avo to the cardinal, p. 9 |
| una vez, dos veces, cinco veces | once, twice, five times | numeral phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | vez/veces + cardinal number for multiples of occurrence, p. 10 |
| solo(a), doble, triple | single, double, triple | adjective/noun/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | multiples usable as adj., noun, or adverb: "Comimos doble" = "We ate twice as much," p. 10 |

#### Weather, temperature, seasons (pp. 14-16)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Hace mal/buen tiempo. | It's bad/nice weather. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 14 |
| Hay nubes. / Está nublado. | It's cloudy. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 14 |
| Hace frío. / Hace fresco. / Hace calor. | It's cold / cool / hot. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 14-15 |
| Hay niebla (neblina). | It's foggy. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 15 |
| Hay humedad. | It's humid. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 15 |
| Hay relámpagos. / Truena. / Hay granizo. | There's lightning. / It's thundering. / There's hail. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 15 |
| Está cubierto. | It's overcast. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 15 |
| Hay lluvias torrenciales. / Hay un aguacero. | It's pouring. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | two synonymous "pouring" idioms, p. 15 |
| Llueve. / Está lloviendo. / Está lluvioso. / Está lloviznando. / Hay lloviznas. | It's raining / showery / drizzling. / There are showers. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | gradation of rain intensity, p. 15 |
| Nieva. / Está nevando. | It's snowing. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 15 |
| Hace sol. / Está soleado. | It's sunny. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | two synonymous phrasings, p. 15 |
| Hace viento. | It's windy. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 15 |
| ¿Cuál es la temperatura? / Hay una temperatura de ___ grados. | What's the temperature? / The temperature is ___ degrees. | phrase | core/formal | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | formal variant noted explicitly, p. 15 |
| menos (dos grados) | minus (two degrees) | preposition | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | used for sub-zero temps, p. 15 |
| el invierno, la primavera, el verano, el otoño | winter, spring, summer, autumn/fall | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 16 |

**Southern Hemisphere cultural note (p. 16):** the source explicitly flags that south of the Equator
(e.g. Argentina) the seasons are reversed relative to the U.S./Spain -- a geographic/climatic fact
the book presents as essential context for weather vocabulary, not a linguistic claim per se, but
relevant to this project's later geographic-scope modeling.

#### Time-telling and dates (pp. 16-19, 13-14)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Es la una. / Son las + cardinal. | It's one o'clock. / It's ___ o'clock. | phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | singular vs. plural "to be" for telling time, p. 16 |
| las X y cuarto / y media / menos cuarto | quarter past X / half past X / quarter to X | time phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | medio->media agrees w/ hora; cuarto shows no agreement (noun), p. 18 |
| Faltar + minutes + para + next hour | time-before-the-hour alt. construction | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | e.g. "Falta un minuto para la medianoche" = "It's 11:59," p. 17 |
| de la madrugada / de la mañana | a.m. (early morning) / a.m. (later morning) | adverbial phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | two-way a.m. split not present in English, p. 18 |
| el mediodía / la medianoche | noon / midnight | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 17 |
| 0 h 10, 17 horas, 23 h 45 (24-hour clock forms) | 12:10 a.m., 5:00 p.m., 11:45 p.m. | numeral convention | core/formal | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | 24-hr clock "commonly used... for schedules and timetables" per source, midnight = hour 0, p. 18 |
| un segundo, un minuto, un cuarto de hora, una media hora, una hora | a second, a minute, a quarter hour, a half hour, an hour | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 18 |
| a eso de la una / en punto / a tiempo / de retraso | at about 1:00 / sharp / on time / late (arriving) | adverbial phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 19 |
| temprano / tarde (time) / a menudo | early / late / often | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 19 |
| hace (time) que | ago / for (time), used with duration | adverbial construction | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 19; distinct from simple "hace" (ago), also listed p. 13 |
| la víspera | eve | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 13 |
| anteayer / pasado mañana | day before yesterday / day after tomorrow | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | symmetric pair, p. 13 |
| de hoy en una semana / de mañana en dos semanas | a week from today / two weeks from tomorrow | adverbial phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 13-14 |
| último(a) / pasado(a) / próximo(a) | last (in a series) / last (most recent) / next | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | source explicitly distinguishes two different senses of "last," p. 14 |

**Note on punctuation (p. 6, used throughout numbers/dates):** Spanish generally inverts
English's comma/period convention for large numbers and decimals (Spanish 5.000 = English 5,000;
Spanish 0,80 = English 0.80) -- noted here as a standing convention rather than a vocabulary item,
since it governs how every numeral in this book's own examples should be read. September also has
the doublet spelling **septiembre or setiembre** (p. 12), the one month name with a documented
variant -- not previously captured.

#### Geographical names requiring the definite article (p. 24)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| los Alpes, los Andes, la América Central/del Norte/del Sur, la Argentina, el Atlántico, el Brasil, el Canadá, el Cairo, la China, el Ebro, el Ecuador, el Escorial, los Estados Unidos, la Florida, el Guadalquivir, la Habana, el Japón, el Mediterráneo, el Orinoco, el Pacífico, el Paraguay, el Perú, la República Dominicana, el Salvador, el Uruguay | (geographical proper names) | proper noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | source is explicit there are "no hard-and-fast rules" for which place names take the article and current colloquial usage often drops it anyway -- this list is the commonly-articled set, not an absolute rule, p. 24 |

#### Feminine noun-ending suffix groups (p. 32)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| la amistad, la verdad, la felicidad, la caridad (-ad) | friendship, truth, happiness, charity | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | one of six parallel feminine-suffix sets, p. 32 |
| la serie, la especie, la planicie, la superficie (-ie) | series, species, plain, area | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 32 |
| la sensación, la nación, la revolución, la lección (-ción) | sensation, nation, revolution, lesson | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 32 |
| la tensión, la comisión, la misión, la procesión (-sión) | tension, commission, mission, procession | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 32 |
| la salud, la virtud, la aptitud, la juventud (-ud) | health, virtue, aptitude, youth | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 32 |
| la legumbre, la costumbre, la certidumbre, la muchedumbre (-umbre) | vegetable, custom, certainty, crowd | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 32 |

#### Gender-irregular / gender-distinct noun sets (pp. 30-35)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| el coraje, el fuselaje, el garaje, el pasaje, el personaje, el traje (-aje) | courage, fuselage, garage, passage, character, suit | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | -aje nouns are masc. despite ending in -e, p. 30 |
| el clima, el drama, el idioma, el poema, el problema, el programa, el sistema, el telegrama, el tema (-ma, Greek-derived) | climate, drama, language, poem, problem, program, system, telegram, theme | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | masc. despite -a ending; Greek derivation, p. 30-31 |
| el atleta, el cometa, el planeta, el poeta (-eta, Greek-derived) | athlete, comet, planet, poet | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 31 |
| el abrelatas, el parabrisas | can opener, windshield | noun (m., compound) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | compound nouns are masc., p. 32 |
| la persona, la víctima | the person, the victim | noun (f., always) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | always feminine regardless of referent's sex: "Juan es una persona muy simpática," p. 32 |
| el bebé | the baby | noun (m., always) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | always masc. regardless of referent's sex: "Marta es un bebé," p. 33 |
| el profesor/la profesora, el francés/la francesa, el alemán/la alemana | teacher, Frenchman/woman, German person | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | -or/-és/-n nouns add -a for fem.; accent drops on the fem. form, p. 33 |
| el/la artista, astronauta, ciclista, dentista, estudiante, joven, mártir, periodista, telefonista, testigo, violinista | artist, astronaut, cyclist, dentist, student, youth, martyr, journalist, operator, witness, violinist | noun (invariant, marker changes) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | identical form both genders, article/marker indicates gender, p. 33 |
| el actor/la actriz, el caballo/la yegua, el duque/la duquesa, el emperador/la emperatriz, el gallo/la gallina, el héroe/la heroína, el hombre/la mujer, el marido/la esposa, el poeta/la poetisa, el príncipe/la princesa, el rey/la reina, el yerno/la nuera | actor/actress, horse/mare, duke/duchess, emperor/empress, rooster/hen, hero/heroine, man/woman, husband/wife, poet (m/f), prince/princess, king/queen, son-in-law/daughter-in-law | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | fully distinct masc./fem. noun forms, p. 34 |
| el capital/la capital, el cura/la cura, el frente/la frente, el guía/la guía, el orden/la orden, el papa/la papa, el policía/la policía | capital(money)/capital(city), priest/cure, front/forehead, male guide/female-guide-or-guidebook, order(sequence)/order(command), pope/potato, police officer/police force-or-policewoman | noun pair, gender-changes-meaning | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | same spelling, different meaning depending on grammatical gender -- high-value false-friend pattern; "El papa comía la papa" cited as the book's own illustrative pun, p. 34 |
| la cigüeña, el mosquito, la jirafa, la hiena, el cóndor, el murciélago, la ballena, la ardilla, la serpiente, la víbora, la avispa, el rinoceronte, la oruga, el tiburón | stork, mosquito, giraffe, hyena, condor, bat, whale, squirrel, snake, viper, wasp, rhinoceros, caterpillar, shark | noun (epicene, one gender covers both sexes) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | animal names use one fixed grammatical gender regardless of the animal's actual sex, p. 35 |
| las vacaciones, las matemáticas, las gafas | vacation, mathematics, eyeglasses | noun (always plural) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 37 |

#### Possessive pronouns and prepositional pronouns (pp. 40-44)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| el mío/la mía/los míos/las mías | mine | possessive pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | definite article + long possessive-adjective form; article drops after ser, p. 40-41 |
| el suyo/la suya... | his/hers/yours(formal)/theirs | possessive pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | ambiguous; disambiguated with el de + él/ella/Ud., p. 41 |
| conmigo, contigo, consigo | with me, with you, with him/her/you(self) | prepositional pronoun (fused) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | mí/ti/sí fuse irregularly with con, p. 44 |
| para sí | for himself/herself/themselves | prepositional pronoun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | reflexive use, singular or plural, p. 44 |
| ello | it (neuter, refers to an idea) | pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Sueño en ello" = "I dream about it," p. 44 |

#### Verbs requiring a non-English-matching object type, and gustar-type verbs (pp. 45-48)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| buscar, escuchar, esperar, llamar, pagar, mirar | to look for, to listen to, to wait/hope for, to call, to pay for, to look at | verb (requires DIRECT object in Spanish, indirect in English) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 45 |
| aconsejar, contar, contestar, dar, decir, devolver, enviar, escribir, explicar, mandar, ofrecer, pagar, pedir, perdonar, preguntar, prestar, prohibir, prometer, recordar, regalar, telefonear | to advise, relate, answer, give, tell, return, send, write, explain, send, offer, pay, ask, forgive, ask, lend, forbid, promise, remind, give(gift), phone | verb (requires INDIRECT object) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | perdonar/recordar take indirect object only when a direct object is also present, p. 47 |
| aburrir, agradar, bastar, caer bien, convenir, disgustar, doler, encantar, entusiasmar, faltar, fascinar, fastidiar, hacer daño, importar, interesar, molestar, parecer, quedar, resultar, sentar bien/mal, sobrar, sorprender, tocar | to bore, please, be enough, like, suit, upset, hurt, adore, enthuse, lack/need, fascinate, annoy, harm, matter, interest, bother, seem, remain/have-left, result, appreciate/upset, be-left-over, surprise, be-one's-turn | verb (gustar-type: Spanish indirect object = English subject) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | 23-verb list; "Me gustan los perros" = "I like dogs" (dogs is the Spanish grammatical subject), p. 48 |

---

### Grammar points

#### Using and omitting definite articles (pp. 22-27)

Beyond the basic el/la/los/las paradigm (already captured elsewhere), the source gives an extensive,
explicit list of environments requiring vs. omitting the definite article -- most of this is new
relative to the beginner-workbook treatment. **Required** before: nouns in a general/abstract sense
("Me gusta el chocolate"), the cardinal number in a date or clock time, expressions of time, season
names (except optionally after *en*), day-of-week names (except after *ser* when stating the day),
weights/measures expressing "per," language names (except directly after *hablar*, *en*, *de* -- and
even there the article may be added back for emphasis: "Hablamos bien el español"), certain
geographical names (see vocabulary list above), titles (except addressing someone directly, and
except *don/doña*, *Santo/San/Santa*), parts of the body/clothing when the possessor is clear, last
names (plural), and ship names. **Omitted** before: nouns in apposition unless modified or
family/business-relationship, an unmodified noun expressing a class/occupation/nationality/religion
(added back once modified: "Su abogado es colombiano" vs. "Su abogado es un colombiano famoso"), and
certain quantifier-like words that take the indefinite article pattern in English (*otro*, *cierto*,
*tal*, *cien*, *mil* + noun -- no article at all, unlike English "another," "a certain," "such a").
**The neuter article *lo*** has no plural and is used before a masc./fem. adjective functioning as an
abstract noun ("Lo peligroso le encanta") or before adjective/adverb + *que* to mean "how" ("¿Ves lo
bella que es?"); *a lo* + adjective/noun means "in the manner of" ("Él comía a lo bestia," p. 26).
**Contraction**: *a* + *el* -> *al*; *de* + *el* -> *del*, except when *el* is part of a proper title
(p. 26).

#### Demonstrative adjectives and pronouns (pp. 28-30)

A three-way distance system (este/ese/aquel roughly "near speaker" / "not near speaker" / "far from
both speaker and listener") rather than English's two-way this/that. Demonstrative adjectives placed
*after* the noun convey a pejorative meaning ("Las muchachas esas no hacen nada" roughly "those
[blasted] girls"). Demonstrative *pronouns* (replacing noun+adjective) are distinguished from the
adjectives by a written accent, though the source notes current usage increasingly drops the accent
when unambiguous. Masculine/feminine demonstrative pronouns in a sequence distinguish "the former"
(éste/ésta, the item named second-to-last, i.e. nearer in the sentence) from "the latter" (aquél,
named first) -- opposite of what English speakers might assume from word order. The neuter forms
(esto, eso, aquello) refer to ideas/concepts, not physical nouns. In relative clauses, special reduced
demonstrative pronouns (el, los, la, las, lo + de/que) replace the full éste/ése/aquél forms ("Yo tomo
el tren de las ocho y ella toma el de las nueve").

#### Noun gender beyond -o/-a (pp. 30-35)

Masculine by thematic group regardless of ending: numbers, day names, month names, compass points,
tree names, river/lake/mountain/sea names, musical note names, compound nouns (full lists in
vocabulary section above). The exceptions to the basic -o-is-masculine/-a-is-feminine rule (*la
mano*, *la radio* as feminine despite -o; *el mapa* as masculine despite -a) are explicitly flagged
by the source as irregular rather than silently listed as regular. **Masculine article before
stressed-initial-a/ha feminine nouns** is a genuinely separate phenomenon from the (already
documented) agua/águila pattern: "El agua está fría," "Tengo un hambre de lobo" -- the noun stays
grammatically feminine (adjectives agree feminine) even though the article is masculine, purely to
avoid a vowel collision (p. 28).

#### Plural-formation exceptions (pp. 36-37)

Beyond the basic vowel+s/consonant+es rule: accented-vowel-final nouns just add -s (el café -> los
cafés); -z nouns change z->c before -es (el pez -> los peces); some -n/-s nouns add or drop an accent
to preserve stress (el joven -> los jóvenes; el inglés -> los ingleses); unstressed-final-s nouns are
invariable in the plural (el jueves -> los jueves); compound nouns never change (el rascacielos -> los
rascacielos). **Mixed-gender plural rule**: when referring to two people of different sexes, the
masculine plural form covers both (el hijo + la hija -> los hijos "the children"; el señor Cruz + la
señora Cruz -> los señores Cruz "the Cruzes") -- p. 37.

#### Possession beyond short-form possessive adjectives (pp. 37-42)

Possession via *de* reverses English word order (possessed-item + de + possessor) and never uses an
apostrophe; "whose" is *¿De quién es?* (singular answer) / *¿De quiénes son?* (plural answer), with
the verb agreeing with the item possessed, not the possessor. To avoid repeating a possessed noun,
Spanish replaces it with the matching definite article + *de*: "Mi profesora y la de mi hermano" (My
teacher and my brother's). **Long-form possessive adjectives** (mío, tuyo, suyo, nuestro, vuestro,
suyo + gender/number) are postposed, after the noun ("el libro mío"), unlike the preposed short
forms -- genuinely new material relative to 005's short-form-only lesson. **Possessive pronouns**
combine the definite article + the long possessive-adjective form (el mío, la tuya, los suyos...) and
replace a possessed noun entirely ("Tu madre es profesora y la mía es doctora"); the article is
dropped after *ser* ("Este paraguas es tuyo"). Ambiguous *su/suyo* forms (which can mean
his/her/your-formal/their) are disambiguated with the definite article + *de* + él/ella/Ud./ellos.

#### Subject pronoun regional usage (p. 43)

The source makes two explicit regional claims about subject pronouns worth flagging as the kind of
sociolinguistic data this project prioritizes: **vosotros/vosotras** is the informal plural "you"
used primarily in Spain, "only rarely" in Latin America generally -- *but* the source separately
notes it is "widely used in Argentina," contradicting a flat Spain-only generalization. **Usted/
ustedes** (Uds.) is used throughout the Spanish-speaking world for formal address and replaces
vosotros/as in Latin America generally.

#### Prepositional and object pronouns (pp. 43-50)

**Prepositional pronouns** mostly mirror subject pronouns (mí, ti, él/ella/Ud.(sí), nosotros,
vosotros, ellos/ellas, Uds.) except that *yo*->*mí* and *tú*->*ti* change form; these three (mí, ti,
sí) additionally fuse irregularly with *con* (conmigo/contigo/consigo) rather than simply following
it (see vocabulary). **Direct object pronouns**: the third-person masculine singular/plural forms
show an explicit Spain/Latin-America split -- *le/les* in Spain, *lo/los* in Latin America, for
"him"/formal "you" -- both glossed by the source itself as regional preferences, not free variants
(p. 45). **The personal *a*** has no English equivalent and marks a direct object as referring to a
person, pet, indefinite person, or (increasingly obsolete usage) unmodified geographic name; it is
never used with *tener* ("Tengo un hermano," no *a*). **Indirect object pronouns** (me, te, le/les,
nos, os) are used even when the indirect-object noun itself is also stated, unlike English ("Leo el
libro a mis hijas. Les leo el libro."). **Gustar-type verbs** (23-verb list in vocabulary) invert the
subject/object relationship relative to their English translations -- the Spanish indirect object is
the semantic experiencer that English makes the subject. **Double object pronouns**: indirect
precedes direct; when both are third-person, *le/les* becomes *se* before *lo/la/los/las*, with
*a Ud./a él/a ella* etc. optionally added back to disambiguate the now-generic *se* ("Yo se los
ofrezco a él"). **Positioning/accent rules**: pronouns normally precede a conjugated verb, but may
attach to an infinitive or gerund (adding an accent three vowels back from the end when attached);
with affirmative commands, pronouns attach and generally add an accent the same way; with negative
commands, pronouns precede the verb as usual. When two pronouns attach to an infinitive, count back
three vowels for the accent; when two attach to a gerund or affirmative command, generally (not
always) count back four vowels.

---


---

## Spanish — Established Vocabulary/Grammar: Webster's New World Spanish Grammar Handbook, Parts III-V (Simple Tenses; Simple Moods; Gerunds and Progressive Tenses)

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook* (1st ed., Wiley, 2005),
ISBN 978-0-7645-7897-7, printed pp. 51-115 (Part III "Simple Tenses": Present, Preterit, Imperfect,
Future; Part IV "Simple Moods": Mood overview, Conditional, Present Subjunctive, Imperfect
Subjunctive; Part V "Gerunds and Progressive Tenses"). This is the second of two files covering this
subagent's assigned PDF page range (1-130, printed pp. 1-115); Parts I-II are in `022_chunk1.md`,
which also carries the full triage/redundancy/source-quality notes shared by both files -- see that
file for the PDF-text-layer confirmation and the vosotros/le-lo dialectal findings. Whole-section
source attributes also carry over unchanged: Source Type = `grammar_reference`; Attested Era =
"contemporary (source published 2005)"; Transcription/Vision Reading Confidence = `n/a` throughout
(clean text layer, no vision-reading needed anywhere in this range).

**Non-redundant-supplement scope note (specific to this file).** This range is almost entirely verb
morphology/syntax -- the territory most likely to overlap with 005 (basic present-tense regular
verbs), 007 (`practice_makes_perfect_spanish_irregular_verbs`), and 008/008b/008c (`...verb_tenses`).
Per dispatch instructions this subagent skimmed only 005 and 009, not 007/008 -- so the redundancy
call below is made against 005's beginner-level treatment specifically, and the claim of novelty for
material that might also appear in 007/008 is **not independently verified against those files**;
flagging this explicitly per the spec's auditability requirement rather than silently assuming no
overlap. **Skipped as redundant with 005:** the basic -ar/-er/-ir regular present-tense paradigm
table itself (hablar/comer/vivir), the basic ser/estar paradigms, and the basic subject-pronoun-
indicates-ending point. **Kept as genuinely new or more systematic** relative to 005's scattered
lesson-by-lesson approach: the full categorized present-tense spelling-change verb system (c->zc,
c->z, g->j, gu->g, each with its own multi-verb list), the full stem-changing verb category system
(six -ar/-er/-ir patterns + -iar/-uar/-uir, each with verb lists), the three-tier irregular-verb
classification (yo-only / yo+tú+él+ellos / nearly-all-forms), the seven explicit uses of the present
tense (including the haber+de / haber+que obligation constructions and the hacer-duration
construction), the ten verb-pairs-with-different-connotations list (conocer/saber,
deber/tener que, etc. -- a genuine false-friend-style semantic-distinction set), the full preterit
spelling/stem-change category system, the five-category irregular preterit classification, the
preterit-vs-imperfect verb-meaning-shift table (conocer/poder/querer/saber/tener change meaning
depending on tense), the two preterit/imperfect-cue adverbial vocabulary lists, future/conditional
irregular-stem categories, the entire Simple Moods part (mood overview, conditional uses including
the past-conjecture and courtesy uses, present subjunctive formation + the ~90 combined trigger
items across impersonal expressions/verbs/adjectives/conjunctions/indefinites, avoiding-the-
subjunctive rules, imperfect subjunctive formation + its politeness use), and the entire Gerunds and
Progressive Tenses part (gerund formation including irregular/stem-changing gerunds, the eight
motion verbs besides *estar* that form progressives and the semantic nuance each contributes, and
the "verbs not used in the progressive" caveat).

---

### Vocabulary

Most of this range's content is grammatical apparatus (verb paradigms, trigger-word lists for the
subjunctive) rather than free-standing vocabulary items, so the vocabulary table below is shorter
than Parts I-II's; the bulk of this file's content is in the Grammar points section, including
extensive verb/trigger-word lists that are presented there as part of each rule rather than
duplicated in table form.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| más tarde, después, en un rato, dentro de poco, pronto | later, afterward, in a while, in a short time, soon | adverb/adverbial phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | time expressions that let the present tense substitute for the future, p. 81 |
| anoche, anteayer, ayer, de repente, el mes/año pasado, el otro día, finalmente, por fin, primero, un día, una vez/dos veces | last night, day before yesterday, yesterday, suddenly, last month/year, the other day, finally, finally, at first, one day, once/twice | adverb/adverbial phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | words that cue the PRETERIT (single, bounded past event), p. 79-80 |
| a menudo, a veces, antiguamente, cada día/semana/mes/año, con frecuencia, de vez en cuando, en general, frecuentemente, generalmente, habitualmente, normalmente, todo el tiempo, todos los días, usualmente | often, sometimes, formerly, every day/week/month/year, frequently, from time to time, generally, frequently, generally, habitually, normally, all the time, every day, usually | adverb/adverbial phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | words that cue the IMPERFECT (ongoing/habitual past), p. 80 |
| ojalá que | if only / I wish / I hope | interjection/conjunction | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | triggers subjunctive; with imperfect subjunctive specifically expresses a hypothetical wish, p. 98, 107 |
| tal vez, quizás | perhaps | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | both trigger subjunctive under doubt, indicative under certainty — a doublet with identical syntactic behavior, p. 98 |
| como si | as if | conjunction | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | always triggers imperfect subjunctive, p. 107 |

---

### Grammar points

#### The present tense: spelling-change verbs (pp. 53-56)

A spelling change is needed only in the *yo* form, to preserve the verb's original consonant sound
once -o is added: vowel+**cer/cir** changes c->zc (conocer -> conozco; also aparecer, crecer,
establecer, merecer, nacer, obedecer, obscurecer, ofrecer, parecer, producir, reconocer, reducir,
reproducir, traducir); consonant+**cer/cir** changes c->z (ejercer -> ejerzo; also convencer, fruncir,
vencer, zurcir); **-ger/-gir** changes g->j (escoger -> escojo, dirigir -> dirijo; also coger,
proteger, recoger, afligir, exigir, infligir, surgir); **-guir** changes gu->g (distinguir ->
distingo; also extinguir). A small set of verbs (colegir, corregir, elegir, conseguir, seguir)
combine a spelling change with a stem change and must be learned as a fused pattern (e.g. elegir ->
elijo, eliges, elige, elegimos, elegís, eligen), p. 62.

#### The present tense: stem-changing verbs, by category (pp. 56-63)

Internal vowel changes affect yo/tú/él/ellos forms only (nosotros/vosotros stay unchanged): **-ar
e->ie** (cerrar; also atravesar, comenzar, despertar, empezar, encerrar, enterrar, helar, negar,
nevar, pensar, plegar, quebrar, recomendar, sentar, sosegar, temblar, tentar); **-ar o->ue**
(recordar, jugar [u->ue]; also acordar, acostar, almorzar, aprobar, colgar, contar, costar,
encontrar, forzar, mostrar, probar, sonar, soñar, tronar, enjugar); **-er e->ie** (querer; also
defender, descender, encender, entender, perder); **-er o->ue** (poder; also doler, envolver, llover,
morder, mover, resolver, revolver, soler, volver); **-ir e->i** (pedir; also competir, despedir,
expedir, gemir, medir, repetir, servir, vestir); **-ir e->ie** (mentir; also advertir, consentir,
convertir, divertir, herir, preferir, referir, sentir, sugerir); **-ir o->ue** (dormir; also morir);
**some -iar i->í** (enviar; also confiar, criar, desviar, espiar, esquiar, fiar, fotografiar, guiar,
rociar, vaciar, variar); **some -uar u->ú** (continuar; also acentuar, actuar, efectuar, evaluar,
habituar, perpetuar, situar, valuar); **-uir (not -guir) adds y after u** (construir; also concluir,
contribuir, destruir, disminuir, distribuir, excluir, huir, incluir, influir, instituir, instruir,
obstruir, sustituir).

#### The present tense: irregular verbs, by category (pp. 63-64)

Three tiers of irregularity, from narrowest to broadest: **yo-form only** (caber->quepo,
caer->caigo, dar->doy, hacer->hago, poner->pongo, saber->sé, salir->salgo, traer->traigo,
valer->valgo, ver->veo); **yo/tú/él/ellos irregular, nosotros/vosotros regular** (decir: digo, dices,
dice, decimos, decís, dicen; estar; oler: huelo, hueles, huele, olemos, oléis, huelen; tener; venir);
**irregular in most or all forms** (haber, ir, oír, reír, ser).

#### Using the present tense: seven functions (pp. 64-65)

Beyond expressing a present action, the present tense also expresses: a habit/custom; a near-future
action when used to ask for instructions ("¿Lo repito más despacio?" = "Shall I repeat it?"); a
near-future action generally ("Te telefoneo esta noche" = "I'll call you tonight"); an action begun
in the past and continuing into the present, via *hacer* ("¿Cuántos años hace que estudias el
español? Hace un año"); existence, via *haber* ("¿Qué hay en su bolsillo? No hay nada"); obligation,
via *haber de* ("Hemos de lavar el coche" = "We have to wash the car") and impersonal obligation via
*haber que* ("Hay que estudiar para salir bien" = "One must study to succeed") — **haber de vs. haber
que is a genuine obligation-marking distinction (personal vs. impersonal "must") not previously
captured**; and habitual action via *soler* ("Yo suelo cenar a las siete").

#### Ten verb pairs with distinct Spanish connotations under one English gloss (pp. 65-67)

A systematic false-friend-style list, high value for later register/mechanics analysis: **conocer**
(to be acquainted with a person/place/thing) vs. **saber** (to know a fact or know how to do
something); **deber** (moral obligation) vs. **tener que** (practical necessity); **dejar** (to leave
an item behind) vs. **salir** (to leave a place); **estar** (health, location, temporary
state/condition, progressive tense) vs. **ser** (inherent quality, identity, time/date/place of an
event, impersonal concepts, the passive); **gastar** (to spend money) vs. **pasar** (to spend time);
**jugar a** (to play a sport/game) vs. **tocar** (to play an instrument); **llevar** (to take a
person/thing somewhere, to carry) vs. **tomar** (to pick something up and carry it); **pedir** (to
request/ask for something) vs. **preguntar** (to ask a question); **poder** (to have the ability) vs.
**saber** (to know how); **volver** (to return/come back, physical) vs. **devolver** (to return an
item to its owner).

#### The preterit: spelling-change and stem-change categories (pp. 67-73)

**-car/-gar/-zar** verbs change only in the *yo* form (c->qu, g->gu, z->c respectively: buscar->busqué,
llegar->llegué, empezar->empecé), each with a multi-verb list matching the present-tense spelling-
change lists already given. **Verbs that change i to y**: stem-ending-in-vowel -er/-ir verbs (except
traer and -guir verbs) change i->y in the third-person singular/plural (leer->leyó/leyeron,
oír->oyó/oyeron, construir->concluyó/concluyeron), with í (written accent) replacing i in the other
persons; creer patterns like leer. **reír and sonreír** change e->i in third person and additionally
add an accent to tú/nosotros/vosotros forms (reí, reíste, rió, reímos, reísteis, rieron) — a double
irregularity (stem change + accent pattern) not reducible to either the i->y rule or the stem-change
rule alone. **Stem-changing -ir verbs** show a *different, reduced* vowel change in the preterit than
in the present: mentir (present e->ie) only changes e->i in preterit third person (mintió,
mintieron); pedir (present e->i) keeps e->i in preterit too; dormir (present o->ue) changes o->u in
preterit third person (durmió, durmieron) — the preterit stem-change pattern is narrower
(third-person-only) than the present-tense pattern (yo/tú/él/ellos), a genuine asymmetry worth
flagging for mechanics analysis.

#### The preterit: irregular verbs, by category (pp. 73-74)

Five categories of irregular preterit stem: **i-stem** (decir->dije, venir->vine, querer->quise,
hacer->hice, satisfacer->satisfice); **u-stem** (caber->cupe, haber->hube, saber->supe); **uv-stem**
(andar->anduve, estar->estuve); **j-stem** (traer->traje, decir->dije, conducir->conduje, and all
-ducir verbs pattern like conducir); **dar/ver** (identical endings: di/vi, diste/viste, dio/vio...);
**ser/ir** (fully identical preterit forms in all persons: fui, fuiste, fue, fuimos, fuisteis,
fueron — a genuine, total homophony/homography between two otherwise-unrelated verbs, resolved only
by context).

#### Using the preterit (p. 75)

Five functions: an action that began at a specific past time; an action completed at a specific past
time; any other completed past action; a series of completed past actions within a definite past
timeframe; and an action that occurred a specific counted number of times.

#### The imperfect: formation, irregulars, and uses (pp. 75-81)

Only three verbs are irregular in the imperfect: **ir** (iba, ibas, iba, íbamos, ibais, iban), **ser**
(era, eras, era, éramos, erais, eran), **ver** (veía, veías, veía, veíamos, veíais, veían) — a
strikingly small irregular set compared to other tenses. Seven uses: ongoing/continuous past action
regardless of completion; repeated/habitual past action; an action continuing for an unspecified
period; describing people/places/things/conditions/states of mind in the past; two simultaneous past
actions; a past situation interrupted by a preterit-expressed event; and a past action that began and
continued, via *hacer* ("¿Cuánto tiempo hacía que estudiabas el español? Hacía tres años" — the
imperfect analog of the present-tense *hacer*-duration construction already noted above).

#### Preterit vs. imperfect: the comparison and the meaning-shift verbs (pp. 77-80)

The source's own summary framing: preterit = "what happened and was finished"; imperfect = "what was
happening, used to happen, or would happen over time." Five verbs **change meaning** depending on
which past tense is used — a genuinely high-value aspectual phenomenon: **conocer** (preterit = met
for the first time; imperfect = knew for some time); **poder** (preterit = finally managed to;
imperfect = was generally able to); **querer** (preterit affirmative = tried to; preterit negative =
refused to; imperfect = wanted for a while); **saber** (preterit = found out; imperfect = knew for a
while); **tener** (preterit = received; imperfect = was carrying/had on hand). "Would" is ambiguous in
English and maps to three different Spanish forms depending on sense: imperfect for "used to"
("Cuando era joven, iba a la biblioteca los sábados"), conditional for hypothetical "would do under
conditions" ("Si hiciera buen tiempo, yo iría a la piscina"), and the preterit of *querer* for "was/
wasn't willing to" ("Yo no quise ir al centro").

#### The future tense: irregular stems, by category (pp. 81-83)

All future (and, per Part IV, conditional) irregular stems fall into three categories, replacing the
infinitive itself rather than just changing the ending: **drop final -e** (caber->cabr-, haber->habr-,
poder->podr-, querer->querr-, saber->sabr-); **drop -e/-i and insert -d-** (poner->pondr-,
salir->saldr-, tener->tendr-, valer->valdr-, venir->vendr-); **fully irregular stem** (decir->dir-,
hacer->har-). Using the future (p. 83): predicting a future event; and — the more distinctive use —
expressing wonder, probability, or conjecture **about the present** ("¿Cuántos años tendrá?" = "I
wonder how old she is"; "Será Ana" = "It must be Ann") — an epistemic-modal use of a nominally future
tense, worth flagging as a cross-linguistically interesting mechanism for later mechanics analysis.

#### Mood: a five-way system (p. 85)

The source frames Spanish as having five moods: indicative (fact/question across preterit/
imperfect/present/future), conditional (what would happen under conditions), subjunctive (wishing,
doubt, emotion, etc.), imperative (commands), and infinitive (the unconjugated "to" form). Also
noted: verbs with an infinitive-form accent (reír, oír) **drop that accent** in the future tense and
the conditional mood specifically (reirá, not reírá) — a small but systematic orthographic rule.

#### The conditional: formation and uses (pp. 86-89)

Formed from the same irregular stems as the future (see above) plus the imperfect endings used for
-er/-ir verbs. Four uses beyond the basic "would" sense: expressing what would happen under
hypothetical circumstances (paired with the imperfect subjunctive in the *si*-clause); expressing a
future-relative-to-a-past-event action (reported speech: "Mi amigo me dijo que nosotros nos
divertiríamos mucho"); expressing wonder/probability/conjecture **about the past**, the conditional's
exact analog to the future's present-conjecture use ("¿Qué tiempo haría cuando ellos salieron?" = "I
wonder what the weather was like"; "Llovería" = "It must have been raining"); and expressing
courtesy/kindness/modesty ("Me gustaría acompañarte" = "I would like to go with you").

#### The present subjunctive: formation across verb categories (pp. 89-94)

Formed by dropping -o from the present-tense *yo* form and adding subjunctive endings. The
spelling-change categories (-car/-gar/-zar, consonant/vowel+cer/cir, -ger/-gir, -guir) and the
yo-form-irregular categories reuse the **same stem** already established for the preterit (for
-car/-gar/-zar) or the irregular present yo-form (for the rest) — i.e. the present subjunctive is not
an independently-memorized system but derives mechanically from forms already learned elsewhere, a
structural economy worth flagging. Stem-changing verbs follow the present-tense pattern in
yo/tú/él/ellos but — unlike the present indicative — the nosotros/vosotros forms of **-ir** stem-
changers (though not -ar/-er ones) also shift partially (e.g. mentir: nosotros present "mentimos" but
subjunctive "mintamos," pulling toward the *i*). Six verbs are **completely irregular** and must be
memorized outright: dar (dé, des, dé, demos, deis, den), estar, haber, ir, saber, ser.

#### Using the present subjunctive: the trigger inventory (pp. 94-104)

The subjunctive is required when an independent clause joined by *que* to a dependent clause shows
wishing/wanting/emotion/doubt/need/command/supposition, with the independent-clause verb in present/
future/command form. The source provides four parallel, large trigger-word inventories, presented
here as grammar apparatus (register: predominantly a written/formal register device) rather than
duplicated as individual vocabulary rows given their sheer number and formulaic structure:

- **~40 impersonal expressions requiring the subjunctive** (mostly *es* + adjective + *que*, or a
  fixed third-person-verb phrase), e.g. *basta que*, *conviene que*, *es absurdo/aconsejable/
  asombroso/bueno/conveniente/curioso/difícil/divertido/dudoso/esencial/extraño/fácil/imperativo/
  importante/imposible/improbable/increíble/indispensable/injusto/interesante/irónico/justo/
  lamentable/malo/mejor/menester/natural/necesario/posible/preciso/preferible/probable/raro/
  sorprendente/suficiente/urgente/útil que*, *es lástima*, *importa que*, *más vale que*, *parece
  mentira que*, *puede ser que* (pp. 95-97). A contrasting **8-item list requiring the indicative**
  instead (es cierto, es claro, es evidente, es exacto, es obvio, es seguro, es verdad, parece) —
  these express certainty rather than doubt, and flip to requiring the subjunctive when *negated or
  questioned* ("No es claro que él gane el concurso"). *Tal vez*/*quizás* ("perhaps") pattern the same
  way: subjunctive under real doubt, indicative under the speaker's own certainty.
- **~35 verbs requiring the subjunctive** in their dependent clause, grouped by the semantic classes
  advice/command/demand/desire/doubt/disbelief/denial/emotion/hope/permission/preference/
  prohibition/request/suggestion/wishing/wanting: aconsejar, alegrarse(de), avergonzarse de, decir
  (only when = "to order"), dejar, desear, dudar, enfadarse, enojarse, esperar, exigir, hacer,
  insistir(en), lamentar, mandar, necesitar, negar, ojalá que, ordenar, pedir, permitir, preferir,
  prohibir, querer, reclamar, recomendar, requerir, rogar, sentir, solicitar, sorprenderse de,
  sugerir, suplicar, temer, tener miedo de (pp. 98-99). *Dudar* and *negar* flip to expressing
  certainty (indicative) when used negatively ("No dudo que él es fuerte"); *creer*/*pensar* likewise
  only trigger the subjunctive when negated or questioned, not in plain affirmative use (p. 100).
- **16 emotion/feeling adjectives after *estar* + de que**: alegre, asombrado(a), asustado(a),
  avergonzado(a), contento(a), encantado(a), enfadado(a), enojado(a), fastidiado(a), feliz,
  furioso(a), infeliz, irritado(a), lisonjeado(a), orgulloso(a), triste (p. 100).
- **9 conjunctions that ALWAYS require the subjunctive** (purely because the event they introduce is
  inherently hypothetical/unfulfilled): a condición de que, a menos que, a no ser que, antes de que,
  con tal que, en caso de que, para que, por miedo a que, sin que (p. 101). A separate **10-item list
  that takes subjunctive OR indicative** depending on whether the speaker frames the event as still
  uncertain (future, subjunctive) or already settled (past/present fact, indicative): así que, aunque,
  cuando, de manera que, de modo que, después de que, en cuanto, hasta que, luego que, mientras(que),
  tan pronto como (p. 101-102) — the source's own minimal-pair examples (same conjunction, same verb,
  subjunctive vs. indicative) make the uncertainty-vs-fact distinction explicit rather than a free
  stylistic choice.
- **Indefinite/-quiera compounds**: comoquiera, cualquier(a), cuandoquiera, (a-)dondequiera, por +
  adjective/adverb + que, quienquiera always trigger the subjunctive (p. 102-103).
- The subjunctive is also used in **relative clauses** where the antecedent is indefinite,
  nonexistent, or not-yet-attained ("Busco a un hombre que pueda reparar mi televisor" — such a man's
  existence is unclear) vs. the indicative when the antecedent clearly exists ("Tengo un coche que es
  muy deportivo"), and in **third-person commands** ("¡Viva la libertad!").

#### Avoiding the subjunctive (pp. 103-104)

When both clauses share the same subject, *que* is dropped and the infinitive substitutes for the
subjunctive ("Yo prefiero acompañarte" rather than "...que yo me acompañe"). This substitution is
explicitly licensed with *dejar*, *hacer*, *mandar*, *permitir*, *prohibir*, and with conjunctions when
both clauses share a subject. Awkward relative-clause subjunctive constructions can also simply be
avoided via a simpler adjective-first phrasing ("Quiero encontrar un hombre sensible" instead of "...
que sea sensible").

#### The imperfect subjunctive: formation and the politeness use (pp. 104-107)

Formed by dropping *-ron* from the third-person-plural preterit and adding **either** of two parallel
endings sets, *-ra* or *-se* (hablara/hablase, hablaras/hablases...) — the source presents these as
free stylistic alternates throughout, not as a regional or register split (no dialectal claim is made
here, unlike some other sources' -ra/-se treatments; flagged explicitly since the absence of a claim
is itself worth noting rather than silently assuming one). Used in the same trigger environments as
the present subjunctive, but when the independent-clause verb is imperfect/preterit/conditional
rather than present/future. **Politeness use**: the *-ra* form of *deber*, *querer*, and *poder*
substitutes for the conditional to soften a statement — "Debieras estudiar más" (You should study
more), "Quisiera verte a menudo" (I would like to see you often), "Pudiera sentarse" (You may sit) —
a genuine register-softening mechanism distinct from the tense's basic hypothetical function. Also
triggers after *como si* ("as if": "Me miraba como si fuera estúpido") and after *ojalá que* for a
hypothetical (as opposed to achievable) wish ("Ojalá que mi madre supiera cocinar" = "If only my
mother knew how to cook").

#### Gerund formation, including irregulars (pp. 109-112)

Regular formation: -ar infinitives -> -ando; -er/-ir infinitives -> -iendo. When an -er/-ir stem ends
in a vowel, i becomes y before -endo (caer->cayendo, creer->creyendo, distribuir->distribuyendo,
leer->leyendo, oír->oyendo, traer->trayendo). Stem-changing -ir verbs show the *reduced* vowel change
in the gerund that matches their third-person preterit pattern, not their present-tense pattern:
e->ie or e->i verbs both reduce to i in the gerund (mentir->mintiendo, pedir->pidiendo,
preferir->prefiriendo), while o->ue reduces to u (dormir->durmiendo, morir->muriendo) — the same
"preterit-style narrowing" already noted for the preterit stem-change tables above, now shown to
extend to the gerund as a third parallel case. Only three verbs have fully **irregular** gerunds: ir
-> yendo (source notes "has very limited use"), poder -> pudiendo (also "limited use"), reír ->
riendo. The gerund functions adjectivally/adverbially (answering "how?" — "¿Cómo pasa Ud. el verano?
Lo pasa viajando") and, unlike English, is **never** used as a noun subject — the infinitive fills
that role instead ("Jugar al tenis es un deporte muy divertido," not a gerund).

#### Progressive tenses: eight motion verbs beyond *estar* (pp. 112-115)

Progressive constructions are usually built with *estar* + gerund, but the source identifies **eight
additional motion/continuation verbs** that form progressives with distinct nuances of their own,
each contributing meaning beyond simple "is/was/will be doing": **andar** ("to walk," conveys aimless
or extended ongoing action: "Yo ando buscando mi perro" = "I'm walking along looking for my dog");
**continuar** (explicit continuation: "El niño continúa llorando"); **ir** (gradual change over time:
"Sus ideas van cambiando" = "Her ideas are [gradually] changing"); **llegar** (arriving in a state:
"¿Por qué llegas sonriendo?" = "Why do you arrive smiling?"); **quedarse** (remaining in an ongoing
state: "Los muchachos se quedan jugando"); **salir** (departing in a state: "Ella sale riendo" = "She
leaves laughing"); **seguir** (continuation, near-synonym of continuar: "Nosotros seguimos
estudiando"); **venir** (arriving while doing: "Ellas vienen corriendo"). **Important caveat**: these
eight verbs' *own* progressive (i.e. "andar" used reflexively about itself, "ir" about going) is NOT
formed with their own gerund — "andar andando" is not used; instead the plain tense/mood is used
("Ellos andan por la ciudad," "Las muchachas iban al cine") — a genuine gap/constraint in the
progressive system worth flagging, since it means the progressive-forming verb list is not
recursively self-applicable. Present, past (preterit vs. imperfect progressive — mirroring the
basic preterit/imperfect aspectual split exactly), future, and conditional progressives are all
formed by conjugating *estar* (or one of the eight) in the matching simple tense/mood and adding the
gerund; the conditional progressive's hypothetical *si*-clause itself requires the imperfect
subjunctive, directly cross-referencing Part IV's conditional-sentence material. The gerund commonly
follows **command forms of *seguir* and *continuar* specifically** ("Sigan Uds. tocando la guitarra" /
"Continúe Ud. estudiando") as an idiomatic command pattern. Pronoun placement with gerunds (direct/
indirect/reflexive) follows the same precede-the-conjugated-verb-or-attach-to-the-gerund-with-an-
accent rule already established in Parts II-III for infinitives and commands.

---


---

## Spanish — Established Vocabulary/Grammar: Webster's New World Spanish Grammar Handbook, Part VI–VIII (Compound Tenses, Compound Moods, The Imperative)

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook*, 1st edition (Wiley, 2005),
PDF pp. 131–152 ≈ printed pp. 116–152 (Part VI "Compound Tenses" through Part VIII "The Imperative").
Extraction correction: originally triaged as "sparse text layer" but independently re-verified as a
genuine, clean `pdftotext -layout` text layer — no vision-reading was needed, no font-substitution or
column-scrambling artifacts detected in this range.

**Coverage note — non-redundant supplement.** This Spanish corpus already has two prior verb-system
references: `007_practice_makes_perfect_spanish_irregular_verbs.md` (principal-parts method covering
every mood/tense of ~90 verbs, including a dedicated subjunctive/imperative/perfect-tenses treatment)
and `008_/008b_/008c_practice_makes_perfect_spanish_verb_tenses.md` (a tense-by-tense workbook that
already fully tabulates the present perfect, pluperfect, future perfect, conditional perfect, present
perfect subjunctive, and pluperfect subjunctive, each with full six-person paradigm tables). Webster's
covers the *same* compound-tense/mood territory with its own worked examples and formation tables.
**Treated as redundant and NOT re-tabulated:** the present perfect, pluperfect, future perfect, and
conditional perfect indicative paradigms (haber + past participle, all six persons) — already fully
captured in 008b/008c with equivalent tables — and the present perfect/pluperfect subjunctive paradigms
— already in 008c. Only brief grammar-point summaries are given below for these, with illustrative
examples drawn from Webster's own (non-overlapping) example sentences where they add a genuinely new
usage nuance. **Kept and expanded as genuinely new or deeper:** the preterit perfect tense (not
tabulated in any prior established/ file — 007 only mentioned it exists), the "deber de + perfect
infinitive" probability construction, the systematic sequence-of-tenses-in-the-subjunctive table, the
systematic real-vs-contrary-to-fact conditional-sentence table, the perfect infinitive, three additional
irregular past participles not in 007's list (*freír→frito, proveer→provisto, satisfacer→satisfecho*),
and the full command (imperative) system — Webster's dedicates ~16 systematic pages to formal/informal/
vosotros/indirect commands with per-verb-type tables and object-pronoun/accent placement rules, which is
substantially more thorough than 007's one-paragraph treatment ("imperatives are borrowed subjunctive
forms," Ch. 4) and is captured in full below, including an explicit regional/dialectal annotation
(vosotros vs. Uds. commands) the source itself marks.

---

### Vocabulary

Column defaults for this file: **Attested Era** = "contemporary (source published 2005)"; **Source
Type** = `grammar_reference`; **Transcription Confidence** = `n/a`; **Vision Reading Confidence** =
`n/a` (clean text layer). **Attested Region** / **Geographic Scope** are filled in only on the one row
below carrying the source's own explicit regional annotation.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| freír | to fry | verb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Irregular past participle *frito*; not in 007's 12-verb irregular-participle list |
| proveer | to provide | verb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Irregular past participle *provisto*; not in 007's list |
| satisfacer | to satisfy | verb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Irregular past participle *satisfecho*; not in 007's list |
| apenas, cuando, después (de) que, así que, en cuanto, luego que, tan pronto como | hardly/scarcely, when, after, as soon as (×4 synonyms) | conjunction set | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | The expressions the source says typically trigger the preterit perfect in literary/historic register (p. 122) |
| deber de + [perfect infinitive] | must have (done) | modal construction | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Alternative to the future perfect for past probability/conjecture; contrasts with bare *deber* "ought to" |
| vosotros (command forms) | you-all (informal plural command) | pronoun/verb form | core | — | contemporary (source published 2005) | Spain | national | grammar_reference | n/a | n/a | Explicit source annotation: "Vosotros commands are used primarily in Spain, whereas Uds. commands are used in Latin American Spanish-speaking countries" (p. 139) |
| Ud./Uds. | you (formal sg./pl.) — standard abbreviations | abbreviation | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| hube, hubiste, hubo, hubimos, hubisteis, hubieron (+ participle) | preterit perfect of haber | verb paradigm (auxiliary) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Forms the preterit perfect; rare register, see grammar point |
| que + [3rd-person present subjunctive] | let (indirect command) | grammatical construction | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | *Que prepare Elena el postre* = "Let Elena prepare the dessert" |
| vamos a + [infinitive] | let's (do) | idiom | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | One of two ways to express "let's," alongside the nosotros-subjunctive form |

### Grammar points

#### Present perfect, pluperfect, future perfect, conditional perfect (pp. 116–128)

Previously covered in full (all six-person paradigms) by `008b_.../008c_...`. Webster's presents the
same haber + past participle formula for each; its only added nuance: *deber de* + the perfect
infinitive (haber + past participle) can substitute for the future perfect to express past probability
— *Deben de haber llegado tarde* ("They must have arrived late") — a construction not previously
flagged in the established/ files.

#### The past participle, including 3 irregular forms new to this corpus (pp. 118–120)

Regular formation (-ar→-ado, -er/-ir→-ido) and the accent-requiring group (caer→caído, creer→creído,
leer→leído, oír→oído, reír→reído, sonreír→sonreído, traer→traído) match prior coverage. The irregular-
participle list mostly duplicates 007's twelve (abrir, cubrir, decir, escribir, hacer, morir, poner,
resolver, romper, ver, volver) but adds three verbs 007 did not list: *freír→frito*, *proveer→provisto*,
*satisfacer→satisfecho*. As a verbal (after haber) the participle is invariable; as an adjective it
agrees in gender/number with the noun it modifies (*montañas cubiertas de nieve*).

#### The preterit perfect — genuinely new to this corpus (pp. 120–123)

Formed with the preterit of haber (hube, hubiste, hubo, hubimos, hubisteis, hubieron) + past participle,
expressing an action that had just ended in the past (*Cuando el presidente hubo terminado su discurso,
todo el mundo aplaudió* — "When the president had finished his speech, everyone clapped"). The source
flags this as used mainly in literary/historic writing, typically after a specific set of temporal
expressions (apenas, cuando, después de que, así que, en cuanto, luego que, tan pronto como — see
Vocabulary). In conversational/informal register, the pluperfect or simple preterit replaces it. Not
tabulated in any prior established/ file; 007 only named it in passing as "the preterit anterior... rare
in speech."

#### Present perfect subjunctive and pluperfect subjunctive (pp. 128–130)

Previously covered in full by 008c. No new paradigm content; Webster's own examples are different
sentences illustrating the same usage (doubt/emotion triggering the present perfect subjunctive;
pluperfect subjunctive after *como si* "as if" and *ojalá que* "if only," for contrary-to-fact wishes).

#### Sequence of tenses in the subjunctive — a systematic cross-reference table new to this corpus (p. 131)

A compact rule not previously stated this explicitly in established/: the tense of the *main*-clause
verb determines which subjunctive family is required in the dependent clause. **Present indicative,
present perfect, future, or a command in the main clause → present subjunctive or present perfect
subjunctive in the dependent clause. Preterit, imperfect, conditional, or pluperfect in the main clause
→ imperfect subjunctive or pluperfect subjunctive in the dependent clause.** Demonstrated across all
six main-clause tenses with the same dependent-clause verb (mandar que + hablar), making the mapping
unusually easy to verify against.

#### Conditional sentences: real vs. contrary-to-fact — systematic table new to this corpus (pp. 132–134)

A si-clause plus a main/result clause, split into two systems: **real conditions** (certain/likely to
occur) use the indicative (any tense) or the imperative in both clauses. **Contrary-to-fact
conditions**: present-time counterfactuals use the imperfect subjunctive (-ra or -se form) in the si
clause + the conditional (or imperfect subjunctive, -ra form only) in the result clause; past-time
counterfactuals use the pluperfect subjunctive (-ra or -se form) in the si clause + the conditional
perfect (or pluperfect subjunctive, -ra form only) in the result clause. This conditional-perfect usage
was previously named in 007 (Ch. 12) only via one example sentence; this is the first systematic table
of the full real/contrary-to-fact split in established/.

#### The perfect infinitive — new to this corpus (p. 134)

Formed with the bare infinitive *haber* + past participle, used after a preposition (usually *por*):
*Ella se enoja por no haber recibido el puesto* ("She becomes angry for not having received the job").
Distinct from, but related to, the *deber de* + perfect-infinitive probability construction noted above.

#### Formal (Ud./Uds.) commands (pp. 135–139)

Formed from the present subjunctive third-person singular/plural: drop the final -o from the present
yo-form and add -e/-en (for -ar verbs) or -a/-an (for -er/-ir verbs). This rule holds uniformly across
regular, spelling-change (-car/-gar/-zar verbs use the preterit yo-form minus -é, same as present-
subjunctive formation generally; all other spelling-change and stem-changing verbs use the ordinary
yo-form-minus-o rule), and irregular-yo-form verbs (caber, caer, decir, hacer, oír, poner, salir, tener,
traer, valer, venir, ver). A short list of commands must be memorized outright rather than derived: dar
→ dé(n), estar → esté(n), ir → vaya(n), saber → sepa(n), ser → sea(n). Negative commands simply add *no*
before the same form. Written convention: an inverted exclamation point opens an emphatic command,
matching the regular one at the end (*¡No coman tanto!*).

#### Informal tú commands (pp. 139–145)

**Affirmative**: formed by dropping the final -s from the present-tense tú form (= the present-tense
él/ella/Ud. form) for regular, spelling-change, and stem-changing verbs alike. A small closed set of
irregular verbs instead takes a unique monosyllabic form: decir→di, hacer→haz, ir→ve, poner→pon,
salir→sal, ser→sé, tener→ten, valer→val, venir→ven. Note: ver's and ir's singular informal commands are
identical in form (*ve*), disambiguated only by context. **Negative**: uniformly uses the tú form of the
present subjunctive for every verb class, including the irregular set above (no digas, no hagas, no
vayas, etc.) — negative tú commands have no irregular forms of their own even where the affirmative
does. The subject pronoun tú is generally omitted in either polarity.

#### Informal vosotros commands — explicit regional annotation (pp. 145–150)

**Affirmative**: formed by dropping the infinitive's final -r and adding -d, uniformly across every verb
class including irregulars (decir→decid, ir→id, ser→sed, etc.) — unlike the tú paradigm, there is no
irregular-affirmative subset here. **Negative**: uniformly uses the vosotros form of the present
subjunctive. **Explicit regional note the source itself marks**: vosotros commands are used primarily in
Spain, while Latin American Spanish-speaking countries use Uds. commands for both formal and informal
plural address — directly paralleling the vosotros/ustedes split already flagged as a grammar point in
`008_...` (Ch. 1), now confirmed specifically for the imperative mood as well.

#### Indirect commands and "let's" (pp. 150–151)

Indirect commands use *Que* ("let") + third-person present subjunctive, with any object pronoun always
preceding the verb (*Que lo haga Jorge* — "Let Jorge do it"). "Let's"/"Let us" has two forms: *vamos a*
+ infinitive (affirmative) or *no vayamos a* + infinitive (negative), or the nosotros present-subjunctive
form directly (*Comamos* — "Let's eat"). The reflexive "let's" (e.g. *Levantémonos*) drops the nosotros
ending's final -s before attaching the reflexive pronoun; the reflexive vosotros affirmative command
drops its final -d before the reflexive pronoun, adding an accent before -os when attached to an -ir
reflexive verb (*Sentaos*, but *Desvestíos* with the accent).

#### Object pronouns and accent placement with commands (pp. 151–152)

Object/reflexive pronouns attach to the end of affirmative commands and precede negative commands
(*Léelo* vs. *No lo leas*). Accent rule: when one pronoun attaches to a multi-syllable affirmative
command form, count back three vowels from the end and add an accent (*Póngase*); a monosyllabic command
form needs no accent (*Ponlo*). A diphthong counts as one vowel, with the accent falling on the second
vowel of the pair (*Siéntese*) — except *traer*, whose command form (*Tráiganlo*) is an explicitly
flagged exception to that diphthong-counting rule. When two pronouns attach together, count back four
vowels (*Dígamelo*; again, *traer* is the flagged exception: *Tráiganoslos*).

---


---

## Spanish — Established Vocabulary/Grammar: Webster's New World Spanish Grammar Handbook, Part IX–X (Infinitives; Prepositions and Conjunctions)

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook*, 1st edition (Wiley, 2005),
PDF pp. ~153–182 ≈ printed pp. 153–182 (Part IX "Infinitives" through Part X "Prepositions and
Conjunctions"). Same clean text layer as `022_chunk2.md`; no vision-reading needed.

**Coverage note — non-redundant supplement.** Unlike the verb-tense/mood territory in `022_chunk2.md`,
this book's Parts IX and X cover ground **not previously extracted anywhere in this corpus** — prior
Spanish established/ files (007, 008/008b/008c) are verb-conjugation-focused and do not address
infinitive syntax, derivational morphology from infinitives, the preposition system, or the conjunction
system at all. Everything below is genuinely new; nothing was skipped as redundant in this file.

---

### Vocabulary

Column defaults: **Attested Era** = "contemporary (source published 2005)"; **Attested Region** = `—`;
**Geographic Scope** = `—`; **Source Type** = `grammar_reference`; **Transcription Confidence** = `n/a`;
**Vision Reading Confidence** = `n/a`.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| al + [infinitive] | upon (doing) | grammatical construction | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | *Al llegar a casa, leí mi correo* |
| conseguir, lograr | to succeed in, manage to | verb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Both take a bare infinitive directly |
| soler | to be used to, be accustomed to | verb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Takes a bare infinitive directly; otherwise unremarked-on elsewhere in this corpus |
| pretender | to attempt | verb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Takes bare infinitive; false-friend risk vs. English "pretend" worth flagging for later mechanics analysis |
| acostumbrarse a, atreverse a, decidirse a, negarse a, ponerse a | to become accustomed to; to dare; to decide; to refuse; to begin | reflexive verb + a | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Members of the "verbs requiring a before infinitive" class |
| acabar de, arrepentirse de, cansarse de, dejar de, terminar de, tratar de | to have just; to regret; to tire of; to stop; to finish; to try to | verb + de | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | "Verbs requiring de before infinitive" class; *acabar de* + inf. = recent-past idiom ("to have just") |
| consentir en, empeñarse en, insistir en, tardar en | to consent to; to insist on; to insist on; to delay in | verb + en | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | "Verbs requiring en before infinitive" class |
| amenazar con, contar con, soñar con | to threaten to; to count on; to dream of | verb + con | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | "Verbs requiring con before infinitive" class |
| el abuso, el acento, la ayuda, el baño, el beso, el camino, la causa, el daño, el descanso, la falta | abuse, accent, help, bathroom, kiss, path, cause, harm, rest, mistake | noun (deverbal, stem+o/a) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Nouns derived from -ar infinitive stems; e.g. *bañar*→*el baño*, *faltar*→*la falta* |
| la animación, la circulación, la combinación, la declaración, la fascinación, la limitación | animation, circulation/traffic, combination, declaration, fascination, limitation | noun (deverbal, -ción) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | *circulación* also idiomatically = "traffic" |
| el alojamiento, el comportamiento, el embotellamiento, el enfrentamiento, el movimiento, el sufrimiento | accommodation, behavior, traffic jam, confrontation, movement, suffering | noun (deverbal, -miento) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | -cer verbs (and *mover*) change stem e→i before -miento: *conocer*→*el conocimiento*, *crecer*→*el crecimiento*, *establecer*→*el establecimiento* |
| la coexistencia, la coincidencia, la competencia, la correspondencia, la dependencia, la impaciencia, la sugerencia | coexistence, coincidence, competence, correspondence, dependence, impatience, suggestion | noun (deverbal, -encia) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | t→c alternation where needed to preserve the sound (e.g. *competer*→*competencia*) |
| el/la caminante, el/la correspondiente, el/la demandante, el/la gobernante, el/la habitante, el/la ignorante, el/la participante | walker, correspondent (pen pal), plaintiff, governor/ruler, inhabitant, ignorant person, participant | noun (deverbal, -ante/-iente, "one who") | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | -ante for -ar verbs, -iente for -er/-ir verbs |
| convertible, creíble, dirigible, imaginable, lavable, notable, preferible, razonable, recomendable, tolerable | convertible, credible, steerable, imaginable, washable, notable, preferable, reasonable, advisable, tolerable | adjective (deverbal, -able/-ible) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | -able for -ar verbs, -ible for -er/-ir verbs |
| a eso de, a fuerza de, a pesar de, a tiempo, a través de, acerca de, además de, alrededor de, ante, cerca de, debajo de, delante de, dentro de, detrás de, encima de, enfrente de, frente a, fuera de, hacia, lejos de, sobre, tras | about (+time); by perservering; in spite of; on time; across/through; about; besides; around; before/in the presence of; near; beneath; in front of; inside; behind; above/on top of; opposite; in front of; outside of; toward; far; over/above/on; after | preposition / prepositional phrase | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Common-prepositions list; *ante* vs. *antes (de)* distinguished (location/presence vs. time) |
| a causa de, a fines de, a la derecha (de), a la izquierda (de), a principios de, al aire libre, de hoy en adelante, de otro modo, de vez en cuando, en efecto, en la esquina de | because of; at the end of; on/to the right (of); on/to the left (of); at the beginning of; in the open air; from today on; otherwise; from time to time; in fact; on the corner of | prepositional idiom | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| no obstante, por consiguiente, por lo tanto, sin embargo, con todo, excepto que, fuera de | however/nonetheless; consequently/therefore; so/therefore; however/nevertheless; in spite of; except that; aside from | conjunctive expression | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Multi-word units functioning as conjunctions |
| pero, sino | but (general/"however"); but (negative-contrast "but rather") | coordinating conjunction | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Not previously distinguished in this corpus; see grammar point |
| apenas, así pues, así que, aunque, como, conque, cuando, de manera que, de modo que, luego, luego que, mientras, porque, pues, puesto que, si, ya que | as soon as; so; so that; although; like/since/as; so/so...then; when; so that; so that; therefore; so; while; because; then; since/as; if; since | subordinating conjunction | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Several require subjunctive for future time reference (aunque, cuando, mientras, así que, de modo/manera que) but indicative for present/past — see grammar point |

### Grammar points

#### The infinitive as noun and adjective (pp. 153–154, 160)

An infinitive functions as a noun: as sentence subject (*Estudiar no es muy divertido* — where English
would use a gerund, "Studying isn't..."), with the definite article *el* optionally prefixed for emphasis
(*(El) Trabajar es necesario*); as direct object of a verb (*Quiero ir a la fiesta*); as predicate noun
referring back to the subject (*Mi sueño es llegar a ser médico*); and as object of a preposition (see
below). An infinitive is negated by placing *no* directly before it, with any other negative word
following (*Es importante no olvidar esa fecha*). As an adjective, an infinitive can modify a noun
directly (*Tengo mucho trabajo que hacer*).

#### Verbs taking a bare infinitive directly, and the preposition-governed classes (pp. 154–159)

A sizeable closed class of verbs (conseguir, creer, deber, decidir, dejar, desear, esperar, hacer,
impedir, intentar, lograr, mandar, merecer, necesitar, oír, olvidar, parecer, pensar, permitir, poder,
preferir, pretender, procurar, prohibir, prometer, querer, recordar, saber, sentir, soler, temer, ver)
takes an infinitive directly as object with no linking preposition. Four other closed classes instead
require a specific preposition before the infinitive — **a** (acercarse, acostumbrarse, animar, aprender,
apresurarse, aspirar, atreverse, ayudar, comenzar, convidar, correr, decidirse, dedicarse, disponerse,
echarse, empezar, enseñar, invitar, ir, llegar, negarse, obligar, oponerse, ponerse, prepararse,
principiar, regresar, resignarse, salir, venir, volver), **de** (acabar, acordarse, alegrarse,
arrepentirse, cansarse, cesar, dejar, disfrutar, encargarse, gozar, ocuparse, olvidarse, terminar, tratar
de), **en** (consentir, consistir, convenir, empeñarse, insistir, pensar, tardar), and **con** (amenazar,
conformarse, contar, soñar). Crucial rule governing when to switch from this verb+preposition+infinitive
construction to the subjunctive instead: if both clauses share the same subject, the infinitive
construction holds; if there are two *different* subjects, *que* is required after the preposition and
the subjunctive replaces the infinitive (*Consiente en vernos* "He agrees to see us" vs. *Consiente en
que nosotros lo veamos* "He agrees that we can see him").

#### The infinitive as object of a preposition (pp. 155–156)

A longer list of prepositions take an infinitive as object: a, al ("upon"), antes de, con, de, después
de, en, en lugar de/en vez de, hasta, para, sin — each with its own example (*Al llegar a casa, leí mi
correo electrónico*; *Ella trabajó hasta dormirse*).

#### Nouns and adjectives derived from infinitives (pp. 160–165)

Five derivational patterns for deriving nouns from infinitives, each with its own ending and a
productivity note: **stem + -o/-a** (mostly concrete-result nouns: bañar→el baño); **-ción** (abstract
action/result nouns, from -ar verbs: declarar→la declaración); **-miento** (from -ar/-er/-ir verbs,
with -cer verbs and *mover* irregularly softening the stem vowel e→i before attaching: conocer→el
conocimiento, crecer→el crecimiento); **-encia** (from -ar/-er/-ir verbs, with a t→c consonant
alternation to preserve pronunciation where needed: competer→la competencia); and **-ante/-iente**
("one who does X" agent nouns: -ante for -ar verbs, -iente for -er/-ir verbs: gobernar→el/la gobernante).
A separate pattern derives **adjectives**: -able (from -ar verbs) or -ible (from -er/-ir verbs) meaning
roughly "-able": lavar→lavable, creer→creíble.

#### The perfect infinitive, cross-referenced (p. 165)

Already captured as its own grammar point in `022_chunk2.md` (Part IX's closing section, haber +
participle after a preposition, usually *por*) — not re-stated here to avoid duplication.

#### Prepositions: structural role and the common inventory (pp. 167–169)

Prepositions link noun-to-noun, verb-to-verb, verb-to-noun, and verb-to-pronoun. *A* and *de* contract
with the masculine singular article *el* to form *al* and *del* respectively. A long common-prepositions
list is given (see Vocabulary) distinguishing near-synonyms by register/nuance, e.g. *ante* ("before, in
the presence of," more formal/abstract) vs. *antes (de)* ("before," temporal).

#### Detailed uses of a, de, en, hasta, para, and por (pp. 169–176)

Each of six high-frequency prepositions gets its own multi-sense breakdown, the most elaborate being
**para vs. por** (both translate English "for" but never interchangeably): *para* covers destination/
direction, a recipient, future time, purpose/goal, an object's function, qualifying comparisons ("for an
American, she speaks very well"), and opinion ("to me..."); *por* covers motion-through, means/manner,
substitution/"in exchange for," duration, an indefinite time period, place, approximation, "on behalf
of," choice, representation, reason, multiplication, "by the"/"per," an incomplete action followed by an
infinitive, estimation/opinion ("we took her for the teacher"), the agent in a *ser*-passive construction
(cross-referenced forward to Part XV), and the specific set of motion verbs (enviar, ir, mandar,
preguntar, regresar, venir, volver) that take *por* + noun to mean "for" in the sense of "go/send/ask
for" something. The **personal a** is restated here (person, pronoun-referring-to-person, or pet as
direct object; current usage tends to drop it before an unmodified geographic proper name) — this
duplicates ground `008_...` Ch. 5 already covered in depth, so only the geographic-name nuance is new.

#### Coordinating conjunctions: y/e, o/u, ni, pero, sino, que (pp. 178–179)

*Y* ("and") becomes *e* before a word starting with i- or hi- (*Carlota e Inés*); *o* ("or") becomes *u*
before a word starting with o- or ho- (*uno u otro*) — both are phonological euphony rules, not
previously documented in this corpus for these specific conjunctions. *Pero* expresses "but" generally
(and can mean "however"); *sino* expresses "but" only after a negative statement, to show contradiction
or "but rather" (*No bebo café sino té*) — comparisons under *sino* must match parts of speech (noun vs.
noun, adjective vs. adjective, infinitive vs. infinitive).

#### Subordinating conjunctions and the indicative/subjunctive split by time reference (pp. 179–182)

A list of ~16 subordinating conjunctions (see Vocabulary), several of which share a single governing
rule not previously stated in this corpus: *aunque* ("although"), *cuando* ("when"), *mientras*
("while"), and the *así que/de modo que/de manera que* ("so that") family take the **indicative** for
present/past actions but the **subjunctive** for future actions (*Aunque es español, habla muy bien el
inglés* [indicative, present fact] vs. *Yo lo haré aunque no me guste* [subjunctive, future/hypothetical
disposition]). Other conjunctions in the list (apenas, como, conque, luego, porque, pues, puesto que, ya
que) take the indicative unconditionally. *Si* ("if") is cross-referenced to the Conditional Sentences
grammar point already captured in `022_chunk2.md`.

---


---

## Spanish — Established Vocabulary/Grammar: Webster's New World Spanish Grammar Handbook, Part XI–XII (Interrogatives and Exclamations; Negatives, Indefinites, and Relative Pronouns)

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook*, 1st edition (Wiley, 2005),
PDF pp. ~183–206 ≈ printed pp. 183–206 (Part XI "Interrogatives and Exclamations" through Part XII
"Negatives, Indefinites, and Relative Pronouns"). Same clean text layer; no vision-reading needed.

**Coverage note — non-redundant supplement.** `005_practice_makes_perfect_basic_spanish_grammar.md`
already covers basic interrogatives (Lesson 12) and double negatives (Lesson 35) at an introductory
level, and `008_practice_makes_perfect_spanish_verb_tenses.md` Ch. 1 covers simple yes/no and
information-question formation. **Treated as redundant and compressed:** the core interrogative-word
inventory (¿qué?, ¿cuándo?, ¿dónde?, etc.) and the basic no/nunca/nada negative set — these are restated
only where Webster's adds a rule or distinction not in the prior files. **Kept and captured in full as
genuinely new or substantially deeper:** the systematic ¿qué? vs. ¿cuál(es)? contrast, the four distinct
ways to ask a yes/no question (including the ¿verdad?/¿está bien? tag questions, not seen elsewhere in
this corpus), exclamation formation, the full negative/indefinite pronoun-adjective-adverb-conjunction
system (far more systematic than 005's single "double negatives" lesson), the negative-prefix
derivational pattern, and — entirely new to this corpus — the relative pronoun system (que, quien(es),
el/la cual(es), lo que, lo cual, cuyo), which no prior Spanish established/ file has addressed at all.

---

### Vocabulary

Column defaults: **Attested Era** = "contemporary (source published 2005)"; **Attested Region** = `—`;
**Geographic Scope** = `—`; **Source Type** = `grammar_reference`; **Transcription Confidence** = `n/a`;
**Vision Reading Confidence** = `n/a`.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ¿(no es) verdad? | isn't that so? / right? | tag question | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Placed at end of a statement; not in prior established/ files |
| ¿está bien? | is that okay? / all right? | tag question | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| ¿cuál(es)? | which one(s)? / what? | interrogative pronoun | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | See ¿Qué? vs. ¿Cuál(es)? grammar point below |
| ¿para qué? | why? (for what purpose) | interrogative adverb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Contrasts with ¿por qué? (reason) — answered with *para*, not *porque* |
| ¡Qué de! | how many! | exclamation | literary | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Source notes this as equivalent to, but more literary/less common than, ¡cuánto(s)! |
| ¡Cuán! | how! (+ adjective/adverb) | exclamation | literary | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Explicitly flagged by the source as literary register, unlike the everyday ¡Qué!/¡Cómo! |
| nadie, nada, ningún(a/os/as), nunca, jamás, tampoco | nobody, nothing, none/not any, never, never(-ever), neither/not-either | negative pronoun/adjective/adverb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Core negative-word inventory; see grammar point for double/triple-negative word order |
| cualquiera, quien(es)quiera | anyone/anybody, whoever | indefinite pronoun | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Not previously in this corpus's vocabulary |
| alguno(a/os/as), cierto(a/os/as), tal(es), cada, cualquier(a), otro(a/os/as) | some/any, certain, such, each/every, any, other/another | indefinite adjective | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Each paired with a *ninguno*-family negative counterpart in the source |
| ya, todavía (aún), siempre, también, más de + [quantity] | already, still, always, also/too, more than + quantity | indefinite adverb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Each paired with a negative counterpart (todavía no, ya no, nunca/jamás, tampoco, no...más de) |
| anti-, contra-, des-, dis-, in- (im- before p) | (negative-forming prefixes) | derivational prefix | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | e.g. cómodo→incómodo, armar→desarmar, capacidad→discapacidad, espionaje→contraespionaje |
| de nada, de ningún modo, de ninguna manera, no cabe duda, no es para tanto, no hay remedio, ni siquiera, sin novedad | you're welcome, certainly not, by no means, there's no doubt, it's not such a big deal, it can't be helped, not even, nothing new | negative idiom/expression | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Idiom cluster; several (no es para tanto, no hay remedio) are higher-register colloquial fixed phrases |
| que | who(m)/which/that | relative pronoun | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Most frequent relative pronoun; refers to people or things |
| quien/quienes | who(m) | relative pronoun | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | People only; no accent when used as a relative (vs. accented interrogative ¿quién?) |
| el/la/los/las cual(es), el/la/los/las que | who/which | relative pronoun | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Used mainly after multi-syllable prepositions, or to disambiguate between two possible antecedents |
| lo que | that which, what | relative pronoun (neuter) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Refers to an idea/concept with no stated antecedent |
| lo cual | which | relative pronoun (neuter) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Refers to a previously mentioned idea; used less often than *lo que*, mainly after a prepositional phrase |
| cuyo(a/os/as) | whose | relative adjective | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Agrees with the thing possessed, not the possessor |
| como, donde, cuanto, cuando (as relative-pronoun substitutes) | how, where, how much, when | adverb (relative-pronoun function) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Source explicitly labels this "popular usage" substitution for que/lo que/el cual |

### Grammar points

#### Four ways to ask a yes/no question (pp. 183–184)

Beyond simple rising intonation (marked in writing with ¿...?), Spanish offers two tag-question forms
not previously documented in this corpus — ¿(no es) verdad? ("isn't that so?/right?") and the more casual
¿está bien? ("is that okay?") — plus word-order inversion (subject noun/pronoun swaps after the
conjugated verb, with the subject usually omitted once the verb form makes it clear: *¿Necesitas algo?*).
When a conjugated verb is followed by an infinitive, the subject tends to move after the infinitive
instead (*¿Va a patinar Arturo?*).

#### ¿Qué? vs. ¿Cuál(es)? (pp. 185–188)

A rule not previously drawn this precisely in this corpus: **¿Qué?** before a verb asks for a
definition/description/opinion/explanation (*¿Qué piensas de mi idea?*); before a noun it means "which?"
or "what?" and is invariable (*¿Qué CD estás escuchando?*). **¿Cuál(es)?**, which agrees in number with
its referent, is used instead when the question is followed by the verb *ser* or by a preposition, and
asks about a choice/selection among options (*¿Cuál es su número de teléfono?*). ¿Cuánto(a/os/as)?
(agrees in gender/number, precedes a counted/measured noun) and its invariable pronoun counterpart
¿cuánto? (verb agrees with the referent noun) round out the quantity-asking interrogatives.

#### Exclamations (pp. 191–192)

¡Qué! ("what a!"/"how!") expresses a quality and can be intensified with *más* or *tan* between the noun
and adjective (*¡Qué muchacha tan bonita!*). ¡Cuánto(a)!/¡Cuántos(as)! express quantity, agreeing in
gender and number/singular-plural respectively. ¡Cómo! expresses manner. Two forms are explicitly flagged
by the source as literary/less common: ¡Qué de! (equivalent to ¡Cuánto!) and ¡Cuán! (used with adjectives/
adverbs "in a literary sense").

#### Negative words and double/triple negation word order (pp. 193–196)

Core negative set: no, nada, nadie, ni...ni, ningún(a/os/as), nunca/jamás, tampoco. Key word-order rule:
Spanish freely allows double and triple negatives in a single clause — if *no* is one of the negatives
used, it precedes the conjugated verb and the other negative(s) follow; if *no* is dropped, the other
negative word itself moves to precede the verb (*No come nada* or *Nada come* — both mean "He's not
eating anything"). A negative preceded by a preposition keeps that preposition even when fronted (*No
busco a nadie* or *A nadie busco*). The negatives nadie/nada/ninguno/nunca/jamás are specifically used
(not as true negation) after comparatives, after sin/antes (de/que), and in questions anticipating a
negative answer (*Te quiero más que nunca* — "I love you more than ever"). As an adjective, *ninguno(a)*
may be replaced by the more emphatic post-noun *alguno(a)* in a negative sentence (*No tenemos solución
alguna*).

#### Negative prefixes (pp. 196–197)

A derivational pattern not previously in this corpus: anti-, contra-, des-, dis-, and in- (im- before p)
attach to an affirmative word to negate it — cómodo→incómodo, armar→desarmar, capacidad→discapacidad,
democrático→antidemocrático, el espionaje→el contraespionaje.

#### Indefinites and their negative counterparts (pp. 198–200)

A systematic pairing not previously drawn out in this corpus, across pronouns (alguien/nadie,
algo/nada, alguno/ninguno, cualquiera/nadie-ninguno, quien(es)quiera/nadie-ninguno, todo/nada, todo el
mundo/nadie-ninguno), adjectives (alguno, cierto, uno, mucho, tal, cada, cualquier, todo, otro — each
negated by the appropriate form of *ninguno*), adverbs (ya/todavía no, todavía-aún/ya no, siempre/
nunca-jamás, también/tampoco-ni...tampoco, más de+quantity/no...más de+quantity), and conjunctions
(o...o/ni...ni). For o...o and ni...ni, the first *o*/*ni* is optional and each part precedes the
stressed word.

#### Relative pronouns — entirely new to this corpus (pp. 201–206)

No prior Spanish established/ file addresses relative pronouns. The system: **que** (most frequent;
people or things; subject, object, or object of a/en/con/de when referring to things) — *El Prado es un
museo que visito a menudo*. **quien/quienes** (people only; subject, direct/indirect object, or object of
a/en/con/de when referring to people; carries no accent as a relative, unlike interrogative ¿quién?) —
can replace *que* to introduce a non-restrictive clause, and requires the personal *a* when used as a
direct object. **el/la/los/las cual(es)** and **el/la/los/las que** (people or things; used mainly after
prepositions longer than one syllable, or to disambiguate when more than one antecedent is possible — if
there are two possible antecedents, the cual/que form refers to "the former" and quien/que refers to "the
latter"). **lo que** (neuter, "that which"/"what," no antecedent — can refer to an implicit idea never
explicitly stated) vs. **lo cual** (neuter, "which," refers back to an already-stated idea, used less
often, mainly after a prepositional phrase). **cuyo(a/os/as)** ("whose," possessive adjective, agrees
with the thing possessed rather than the possessor). The source separately flags a colloquial/"popular
usage" pattern: como, donde, cuanto, and (less commonly) cuando can substitute for que/lo que/el cual in
informal speech (*Esta es la escuela en que (donde) estudié*) — a register-tagged usage note worth
flagging for later slang-mechanics analysis.

---


---

## Spanish — Established Vocabulary/Grammar: Webster's New World Spanish Grammar Handbook, Part XIII–XV (Reflexive Verbs; Adjectives, Adverbs, and Comparisons; The Passive Voice [opening])

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook*, 1st edition (Wiley, 2005),
PDF pp. ~207–260 ≈ printed pp. 207–245 (Part XIII "Reflexive Verbs," Part XIV "Adjectives, Adverbs, and
Comparisons," and the opening of Part XV "The Passive Voice," which continues past this dispatch's page
range — "The Passive Voice with Ser" is captured in full, but the Part continues afterward with
alternative passive constructions not reached in PDF page 260). Same clean text layer; no vision-reading
needed. This is the final file in the 022 dispatch range (PDF pp. 131–260).

**Coverage note — non-redundant supplement.** Two different redundancy situations apply in this file:

1. **Reflexive verbs** (Part XIII) substantially overlap `008b_practice_makes_perfect_spanish_verb_tenses.md`
   Ch. 10, which already covers reflexive pronoun placement, the broader-than-English reflexive scope,
   body-part-reflexive article usage, and a handful of idiomatic reflexive senses. **Skipped as
   redundant:** the basic reflexive-pronoun-placement rules in simple tenses (already in 008b) and the
   small reflexive-verb list 008b already gave. **Kept as new:** Webster's much larger ~130-entry common-
   reflexive-verb list (vs. 008b's ~20), the explicit split into three distinct *uses* of reflexivity
   (different reflexive/non-reflexive meanings, reflexive-in-Spanish-but-not-English, reciprocal actions,
   passive actions) which 008b did not organize this way, one explicit regional annotation not seen
   before (*apurarse* = "to worry" generally but "to hurry" specifically in Latin American countries),
   and — most valuably for this project's purposes — a ~30-entry table of **idiomatic expressions built
   on reflexive verbs**, several of which are colloquial-register fixed phrases (e.g. *dársela (con
   queso) a alguien* "to fool someone," *andarse con chiquitas* "to beat around the bush," *venderse como
   rosquilla* "to sell like hotcakes") not found in any prior established/ file.

2. **Adjectives/adverbs/comparisons** (Part XIV) substantially overlap
   `005_practice_makes_perfect_basic_spanish_grammar.md` (Lessons 9–10, 26–29), which already covers
   basic adjective gender/number agreement and introductory comparatives. **Skipped as redundant:** the
   basic -o/-a gender-agreement table, the plain vowel/consonant pluralization rule, and introductory
   tan...como/más...que comparison patterns. **Kept as new:** adjective positioning rules (before vs.
   after the noun, and the specific before/after meaning-shift list — grande/gran, viejo/antiguo, etc. —
   not in 005), apocopation/shortened adjective forms (buen, mal, gran, cien, San), the full irregular
   comparative/superlative paradigm (mejor/peor/mayor/menor and their distinct syntactic behavior from
   más grande/más pequeño), the absolute superlative in -ísimo with its spelling-change irregularities,
   and the "than" (que vs. de vs. de lo que) disambiguation rules — none of which 005 reaches at its
   introductory level.

The final section, **The Passive Voice with Ser**, is entirely new to this corpus (no prior file
addresses the Spanish passive construction).

---

### Vocabulary

Column defaults: **Attested Era** = "contemporary (source published 2005)"; **Source Type** =
`grammar_reference`; **Transcription Confidence** = `n/a`; **Vision Reading Confidence** = `n/a`.
**Attested Region**/**Geographic Scope** filled in only on the row carrying the source's explicit
regional annotation.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| apurarse | to get upset, worry; to hurry | reflexive verb | core | — | contemporary (source published 2005) | Latin America | transnational | grammar_reference | n/a | n/a | Explicit source annotation: "to hurry" sense is specifically Latin American (p. 209); general sense elsewhere is "to worry/get upset" |
| conducirse (comportarse), engañarse, fijarse (en), hacerse (a/con), tratarse (de) | to behave; to be mistaken/to deceive oneself; to notice; to become; to concern/be a matter of | reflexive verb | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | A sample of ~130-entry common-reflexive-verb list; full list not reproduced per copyright discipline |
| abalanzarse, sincerarse (con), suicidarse | to rush forward; to be honest (with); to commit suicide | reflexive verb (reflexive-only, non-reflexive in English) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Verbs reflexive in Spanish with no natural reflexive English equivalent |
| aburrirse como una ostra | to be bored stiff | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Lit. "to be bored like an oyster" |
| andarse con chiquitas, andarse por las ramas | to beat around the bush; to go off on tangents | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| dársela (con queso) a alguien | to fool someone, pull a fast one on someone | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| darse por vencido, darse prisa, darse cuenta de | to throw in the towel; to hurry; to realize | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| encontrarse con la horma de su zapato | to meet one's match | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| estrujarse el cerebro (la mollera), romperse la cabeza | to rack one's brain (×2 synonyms) | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| guardarse un as en la manga | to have an ace up one's sleeve | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| meterse en belenes | to get into trouble | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| traerse algún manejo sucio | to be up to something shady | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| venderse como rosquilla | to sell like hotcakes | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Lit. "to sell like a [ring-shaped pastry]" |
| ponerse de mil colores | to become bright red (with embarrassment) | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | Lit. "to turn a thousand colors" |
| soltarse la melena | to let one's hair down | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| hacérsele agua la boca a (alguien) | to make someone's mouth water | idiom (reflexive-based) | colloquial | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a |  |
| gran(de), buen(o), mal(o), primer(o), tercer(o), algún(o), ningún(o), cien(to), San(to) | great/good/bad/first/third/some/no/hundred/saint (apocopated forms) | adjective (apocopated) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | See Shortened Forms grammar point |
| mejor(es), peor(es), mayor(es), menor(es) | better, worse, older/greater, younger/lesser | adjective (irregular comparative) | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | See Irregular Comparatives grammar point |
| -ísimo/-ísima/-ísimos/-ísimas | (absolute superlative suffix, "very ___") | suffix | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | n/a | c→qu, g→gu, ble→bil, z→c before attaching, where applicable |

### Grammar points

#### Uses of reflexive verbs — the four-way split (pp. 214–217)

Webster's organizes reflexive usage into four distinct categories not previously split out this way in
this corpus: (1) verbs with **different meanings reflexive vs. non-reflexive** (e.g. *aburrir* "to bore"
vs. *aburrirse* "to become bored"; *casar* "to marry [off]" vs. *casarse* "to get married"; *parecer* "to
seem" vs. *parecerse a* "to look like"); (2) verbs **reflexive in Spanish but non-reflexive in English**
(abalanzarse "to rush forward," sincerarse "to be honest," suicidarse "to commit suicide" — no natural
reflexive gloss exists in English for these); (3) **reciprocal actions** ("each other"/"one another"),
using the plural reflexive form, optionally clarified/emphasized with *uno a otro* or *el uno al otro*
(*Se escriben todas las noches* — "They e-mail each other every night"); (4) **passive actions**, where a
third-person reflexive construction expresses a passive sense when the subject is a thing and no agent
is named (*Aquí se habla español* — "Spanish is spoken here") — this se-passive is a different mechanism
from the *ser* + participle passive captured below, and is explicitly cross-referenced by the source as
an alternative.

#### Idiomatic expressions built on reflexive verbs (pp. 217–218)

A ~30-entry table of fixed idioms using reflexive verb forms, many colloquial-register and genuinely
slang-adjacent — see Vocabulary for the most distinctive entries (aburrirse como una ostra, dársela con
queso a alguien, andarse con chiquitas/por las ramas, venderse como rosquilla, traerse algún manejo
sucio). This is new, high-value content for this project's slang-synthesis purposes that no prior
Spanish established/ file has captured — idiom structure (reflexive verb + fixed complement) is itself a
productive pattern worth noting for later mechanics analysis.

#### Adjective positioning and meaning shift (pp. 227–229)

Descriptive adjectives normally *follow* the noun in Spanish (*una casa grande*), but an adjective
emphasizing an inherent/essential characteristic can precede it for emphasis (*la blanca nieve* — snow's
whiteness treated as inherent). Limiting adjectives (numbers, possessives, demonstratives, quantity
words like alguno/cada/más/menos/otro/poco/tanto/todo/varios) generally precede the noun. A specific,
closed set of adjectives **change meaning** depending on position, with the pre-noun sense generally more
figurative/non-literal and the post-noun sense more literal: *antiguo* (una antigua costumbre "a former
custom" vs. una costumbre antigua "an ancient custom"); *cierto* ("a certain/indefinite" vs. "a true");
*grande/gran* ("great [in character]" vs. "big [in size]" — see also apocopation below); *mismo* ("the
same" vs. "the [thing] itself"); *nuevo* ("new to the owner" vs. "brand new"); *pobre* ("unfortunate" vs.
"without money"); *simple* ("silly" vs. "simple"); *triste* ("sad/wretched" vs. "unhappy"); *viejo* ("old
[dear acquaintance]" vs. "old [elderly]"). *Bueno* and *malo* are explicitly noted as exceptions —
meaning does not shift with position for these two.

#### Shortened (apocopated) adjective forms (pp. 229–230)

A derivational/phonological pattern: *uno, bueno, malo, primero, tercero, alguno, ninguno* drop their
final -o before a masculine singular noun (un buen libro, el primer piso), with an accent added to
algún/ningún to preserve stress. The shortened form reverts to the full form when separated from its
noun by a preposition (*Uno de mis amigas me espera*). *Grande* shortens to *gran* before any gender
noun (not just masculine) when it means "great/important" rather than "big" — *una gran señora* vs. *esa
señora es grande*. *Ciento* shortens to *cien* before any noun and before *mil*/*millones*, but not
before any other number or before multiples of 100. *Santo* shortens to *San* before a masculine saint's
name, except names beginning *To-* or *Do-* (so *Santo Domingo*, *Santo Tomás*, but *San José*).

#### Lo + adjective/adverb (pp. 231, 236)

The neuter article *lo* placed before a masculine singular adjective creates an abstract noun-phrase
subject (*Lo importante es aprender una lengua extranjera* — "The important thing is..."); the same
construction works before an adverb of quantity (*Lo poco que me dieron no es suficiente*).

#### Irregular comparatives and superlatives (pp. 241–242)

A closed set of adjectives has suppletive (non-regular) comparative/superlative forms rather than the
regular más/menos + adjective pattern: bueno→mejor(es)→el/la mejor; malo→peor(es)→el/la peor;
viejo→mayor(es) (age/status sense: "older," not size); joven→menor(es) (age/status: "younger"). *Grande*
and *pequeño* have **two parallel comparative systems** with different meanings: *más grande*/*más
pequeño* compare physical size, while *mayor*/*menor* compare age or status (*Mi hermana mayor* = "my
older sister," not "my bigger sister"). Syntactically, *mejor* and *peor* generally precede the noun they
modify, while *mayor* and *menor* generally follow it. The adverbs *bien*/*mal* compare irregularly the
same way their adjective counterparts do: bien→mejor, mal→peor.

#### The absolute superlative in -ísimo (pp. 240–241)

Formed by adding -ísimo/-ísima/-ísimos/-ísimas to an adjective (dropping a final vowel first), equivalent
in meaning to muy + adjective (*gordísimos* = "very fat"). Four spelling-change irregularities apply
before the suffix: -co/-ca → -qu- (cómico→comiquísimo), -go/-ga → -gu- (largo→larguísimo, by the pattern
shown with grande→grandísima, though note grande itself doesn't drop a stem consonant), -ble → -bil-
(amable→amabilísimo), and -z → -c- (feliz→felicísimo). For adverbs, -mente attaches to the feminine
singular -ísima form (lenta→lentísimamente).

#### "Than" in comparisons: que vs. de vs. de lo que (pp. 238–239)

A disambiguation rule not previously in this corpus: ordinarily *que* expresses "than." Before a bare
number, *de* is used instead in an affirmative sentence (*Recibí más de cincuenta dólares* — but *que* is
still used if the sentence is negative: *No recibí más que cien dólares*). When a comparison spans two
different verbs sharing one object noun, *de* + definite article + *que* is used (*Ahorro más dinero del
que gana mi hermano* — "I save more money than my brother earns"). When an adjective or adverb (not a
shared-object noun) is being compared across two different verbs, the invariable *de lo que* is used
instead (*Ella es más inteligente de lo que piensa Ud.*).

#### The passive voice with ser (pp. 243–245)

Formed as subject + ser (any tense) + past participle + por + agent (*Este libro fue escrito por Gail
Stein*); the participle agrees in gender/number with the subject, functioning as an adjective rather
than an invariable verbal form (contrast with the haber-based compound tenses, where the participle
never agrees). Demonstrated across all five simple tenses/moods (present, preterit, imperfect, future,
conditional) and all four compound tenses (present perfect, pluperfect, future perfect, conditional
perfect) reached within this page range — the compound-tense passive uses invariable compound forms of
*ser* (*ha sido*, *había sido*, etc.) with the agreeing participle following. Prepositional pronouns
after *por* follow the standard set (mí, ti, él, ella, Ud., nosotros, vosotros, ellos, ellas, Uds.). A
specific exception: *de* (not *por*) introduces the agent when the past participle expresses feeling/
emotion rather than action (*El presidente era temido de todo el mundo* — "The president was feared by
everyone," vs. action-verb passives which always take *por*). This section continues past PDF page 260
with further passive-voice material (likely alternative constructions beyond *ser*) not reached by this
dispatch's assigned range — flagged here for whichever subsequent chunk picks up printed page 246
onward.

---


---

## Spanish — Established Vocabulary/Grammar: Webster's New World Spanish Grammar Handbook — Final Chunk (Passive-Voice Tail, Glossary, Appendices A–B, pp. 246–365)

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook* (1st ed., Wiley, 2005), pp. 246–365 (PDF pages 261–372 of 387; the book's own back-matter Index, pp. 366–387, is pure page-number cross-reference with no extractable content and is skipped per the coverage rule).

**Correction to original triage note:** this source was flagged "sparse text layer" in triage but is in fact a clean, genuine text layer; extracted via plain `pdftotext -layout` (no vision-reading needed). No multi-column scrambling was observed in this range — the two-column vocabulary boxes in Appendix B render cleanly under `-layout`, cross-checked against a non-`-layout` pass on a sample of pages with no discrepancies found.

**Non-redundant-supplement scope decision (explicit, per spec):** Before extracting, skimmed `008c_practice_makes_perfect_spanish_verb_tenses.md` (covers the se-passive and ser+participle passive already, plus a full verb-conjugation-chart appendix) and `009b/009c/009d_practice_makes_perfect_spanish_vocabulary.md` (thematic vocabulary chapters: family, house, animals, foods, places in town, school, professions, clothing, colors, materials) since these are the two most topically relevant prior extractions for this chunk's content (verb-paradigm grammar + thematic vocabulary respectively).

- **Skipped as redundant:** This handbook's **Appendix A** (pp. 258–339) — full regular/-AR/-ER/-IR, stem-changing (18 subtypes), spelling-change (13 subtypes), and irregular-verb (23 verbs) conjugation charts across every tense/mood. This is a verb-paradigm *grammar point*, and 007 (`practice_makes_perfect_spanish_irregular_verbs`, via its "principal parts" method covering all six present-indicative irregularity types and the four preterit irregularity patterns) and 008c's own "Appendix A — verb conjugation charts" already give this project full, systematic paradigm coverage. Reproducing ~80 more pages of the same model-verb-per-category charts would be pure duplication. For audit-trail purposes only, the model verbs this handbook's Appendix A charts (not reproduced) are: regular `amar`/`correr`/`decidir`; spelling-change `secar`, `apagar`, `atestiguar`, `avanzar`, `guiar`, `actuar`, `parecer`, `convencer`, `proteger`, `traducir`, `esparcir`, `exigir`, `destruir`, `extinguir`, `leer`; stem-changing `recomendar`, `encontrar`, `revolcar`, `plegar`, `colgar`, `jugar`, `empezar`, `almorzar`, `avergonzar`, `entender`, `morder`, `sentir`, `adquirir`, `dormir`, `servir`, `elegir`, `seguir`; irregular `andar`, `caber`, `caer`, `dar`, `decir`, `estar`, `haber`, `hacer`, `ir`, `oír`, `oler`, `poder`, `poner`, `querer`, `reír`, `saber`, `salir`, `ser`, `tener`, `traer`, `valer`, `venir`, `ver`. No new irregularity type or exemplar verb outside this standard set was found.
- **Skipped as low-value:** The handbook's own English-language grammatical-terminology **Glossary** (pp. 250–255, e.g. "absolute superlative," "gerund," "subjunctive") is metalanguage definitions for the book's own part-labeling system, not Spanish-language vocabulary or a new grammar point — not useful for this project's purposes and not reproduced.
- **Kept and why:** The tail end of the **Passive Voice** chapter (pp. 246–249, "Substitute Constructions for the Passive") adds a genuinely new nuance not captured in 008c's passive-voice summary — see Grammar points below. **Appendix B, "Spanish Vocabulary"** (pp. 339–365) is a ~30-category thematic English–Spanish vocabulary appendix. Per this project's explicit standing rule that "a different author's own examples are not redundant by default" and vocabulary items are extracted in full regardless of topical overlap with prior sources (unlike grammar-point paradigms), **every distinct vocabulary item in Appendix B is extracted below**, split across `022_chunk3.md`/`022_chunk3b.md`/`022_chunk3c.md` for file-size management. Categories with no term-level hits anywhere in the existing corpus when spot-checked (Jewelry/Jewels, Sports/Playing Fields/Equipment, Computer Terms, Nature, Musical Instruments, Travel/Car Parts, Table Setting/Quantities) are confirmed wholly new; categories with partial overlap with the 009 vocabulary-book series (Family, House, Animals, Foods, Places in Town, School, Professions, Clothing, Colors) are still fully extracted per the above rule, since this handbook's own organization, synonym sets, and explicit regional/dialectal tags (flagged inline below) differ from 009's.
- **Explicit dialectal/regional annotations found** (never skipped per spec): peanut (`el cacahuete` Spain/Mexico vs. `el maní` Latin America); green beans (`los ejotes`, Mexico); boulevard (`el zócalo`, Mexico); rubber (`el hule`, Latin America; `el jebe`, Colombia/Peru). All flagged in the vocabulary table's Attested Region column below.

---

### Grammar points

#### Substitute constructions for the passive: the indefinite *se*, and object-pronoun case with a person as the "patient" (pp. 246–247)

Supplements 008c's existing se-passive/ser-passive summary with a nuance not previously captured. Spanish prefers a `se`-reflexive construction over the true passive when the agent is unmentioned/unimplied and the logical subject is a thing (`Se vende este coche` = "This car is for sale," verb agreeing with the following noun subject). Beyond that, the pronoun `se` has a second, non-reflexive use as an **indefinite subject** meaning "one/people/they/you," restricted to third-person-singular verb forms regardless of what follows: `se dice` ("it is said"), `se cree` ("it is believed"), `se sabe` ("it is known"). An active third-person-plural form without `se` (`Dicen que...`, `Creen que...`) is an equally valid, often-preferred alternative to either construction.

The genuinely new nuance: when `se` is used and the person being acted upon is a **person** rather than a thing (agent still unmentioned), the person is grammatically a direct object — but the handbook specifies the **indirect-object forms `le`/`les`** are used instead of the expected direct-object `lo`/`los` for masculine referents (feminine still uses `la`/`las` as expected): `Se ayudará al hombre` → `Se le ayudará` ("He will be helped"); `Se sorprendió a los niños` → `Se les sorprendió` ("They were surprised"); but `Se obedece a la profesora` → `Se la obedece` ("She is obeyed"). This asymmetric masculine le/les-for-direct-object pattern in the indefinite-se-with-a-person construction is not covered in 008c's existing passive-voice summary.

### Vocabulary

**Appendix B, "Spanish Vocabulary" (pp. 339–365), continues across `022_chunk3.md` → `022_chunk3b.md` → `022_chunk3c.md`.** This file covers: The Family, The House, Animals and Insects, Foods (all subcategories). All entries share Source Type `grammar_reference`, Weight/Frequency `—` (no frequency-dictionary basis), Attested Era `contemporary (source published 2005)`, Transcription Confidence `n/a`, Vision Reading Confidence `n/a` (real text layer, no vision-reading needed) unless noted otherwise — abbreviated below as "(defaults)".

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| el novio / la novia | boyfriend / girlfriend | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "The Family," p. 339; cf. 009b (redundant but kept per non-redundant-supplement rule) |
| el hermano / la hermana | brother / sister | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el cuñado / la cuñada | brother-in-law / sister-in-law | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el niño / la niña | child | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el primo / la prima | cousin | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el padre / la madre | father / mother | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el suegro / la suegra | father-in-law / mother-in-law | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el padrino / la padrina | godfather / godmother | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; 009b has `la madrina` for godmother — this handbook's `la padrina` is a less-common feminization variant worth flagging |
| el abuelo / la abuela | grandfather / grandmother | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el nieto / la nieta | grandson / granddaughter | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el esposo / la esposa | husband / wife | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el sobrino / la sobrina | nephew / niece | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el hijo / la hija | son / daughter | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el yerno / la nuera | son-in-law / daughter-in-law | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el hermanastro / la hermanastra | stepbrother / stepsister | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b's -astro/-astra productive-suffix note |
| el padrastro / la madrastra | stepfather / stepmother | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b, 013c |
| el hijastro / la hijastra | stepson / stepdaughter | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el tío / la tía | uncle / aunt | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b |
| el bisabuelo / la bisabuela | great-grandfather / great-grandmother | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 339; cf. 009b's bis- productive-prefix note |
| el apartamento | apartment | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "The House — Places," p. 340 |
| el edificio de apartamentos | apartment building | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el desván, el ático, el entretecho | attic | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340; three synonyms given |
| el jardín | backyard, garden | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el balcón | balcony | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el sótano | basement | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el (cuarto de) baño | bathroom | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la bañera | bathtub | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el dormitorio, la habitación | bedroom | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el techo | ceiling, roof | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340; same word covers both glosses |
| el armario | closet, wardrobe | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340; same word covers both glosses |
| el patio | courtyard, patio | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el estudio | den, study | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el lavabo, el fregadero | sink (bathroom/kitchen) | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340; two distinct words by room |
| el comedor | dining room | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la puerta | door | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el ascensor | elevator | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la chimenea | fireplace | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el suelo | floor | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el garaje | garage | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la planta baja | ground floor | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el pasillo | hall | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la casa | house | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la cocina | kitchen | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la lavandería | laundry room | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el césped | lawn | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la sala | living room | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el dueño | owner | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la ducha | shower | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la(s) escalera(s) | stair(s) | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el piso | story (floor) | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la terraza | terrace | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la pared | wall | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la ventana | window | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el sillón | armchair | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Furnishings," p. 340 |
| la cama | bed | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| el librero | bookcase | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 340 |
| la moqueta, la alfombra | carpet, rug | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341; two distinct words |
| la silla | chair | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el reloj | clock | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341; also "watch" under Jewelry |
| la cortina | curtain | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el tocador, la cómoda | dresser | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| la lámpara | lamp | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el espejo | mirror | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el buró | nightstand | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el cuadro, la pintura | painting, picture | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el sofá | sofa | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| la mesa | table | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el guardarropa | wardrobe | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341; second synonym beyond el armario |
| la cámara, la máquina fotográfica | camera | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Appliances and Electronics," p. 341 |
| el ventilador de aspas, el ventilador hélice | ceiling fan | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| la secadora | clothes dryer | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el ordenador, la computadora | computer | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341; Spain vs. Latin America register implied but not explicitly tagged by source here |
| el lavaplatos | dishwasher | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el lector de DVD | DVD player | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el ventilador | fan | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el congelador | freezer | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el secador | hair dryer | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el horno de microondas | microwave oven | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el monitor | monitor | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| la impresora | printer | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el refrigerador | refrigerator | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el lavaplatos, el estéreo | stereo | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| la estufa | stove | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el televisor | television set | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| el video | VCR | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341; dated technology term, book published 2005 |
| la lavadora | washing machine | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| cuidar/guardar a los niños | to babysit | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Household Chores," p. 341 |
| limpiar la casa | to clean the house | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| quitar la mesa | to clear the table | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| cocinar | to cook | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| hacer los quehaceres domésticos | to do housework | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| lavar la ropa | to do laundry | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| sacudir los muebles | to dust | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| ir al centro | to go downtown | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| ir de compras | to go shopping | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| planchar la ropa | to iron | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| hacer la cama, tender la cama | to make the bed | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342; source's own layout shows these two forms squeezed together (likely a line-wrap artifact, not one compound word) |
| to pay the bills / pagar las cuentas | to pay the bills | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| to mow the lawn / cortar el césped | to mow the lawn | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| to prepare the meals / preparar las comidas | to prepare the meals | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| to repair / reparar | to repair | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 341 |
| poner la mesa | to set the table | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| ordenar | to straighten | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| sacar la basura | to take out garbage | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| pasar la aspiradora | to vacuum | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| lavar el coche | to wash the car | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| lavar los platos | to wash the dishes | verb phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el oso | bear | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Animals and Insects," p. 342 |
| la abeja | bee | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el pájaro, el ave | bird | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el toro | bull | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el gato | cat | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el pollo | chicken | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342; also under Poultry/Meats as the food term |
| la vaca | cow | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el cocodrilo | crocodile | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el ciervo | deer | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el perro | dog | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el delfín | dolphin | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el burro | donkey | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el pato | duck | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342; also under Poultry |
| el elefante | elephant | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el pez | fish | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342; `el pescado` is the food-fish term, see Foods |
| el zorro | fox | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| la jirafa | giraffe | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| la cabra | goat | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el gorila | gorilla | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el jején | gnat | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| la gallina | hen | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el caballo | horse | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el canguro | kangaroo | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el leopardo | leopard | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el león | lion | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el mono | monkey | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el mosquito | mosquito | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| la pantera | panther | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el cochino | pig | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342; `el puerco` is the food/pork term, see Foods |
| el conejo | rabbit | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el gallo | rooster | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el tiburón | shark | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| la oveja | sheep | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| la serpiente | snake | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| la araña | spider | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| la ardilla | squirrel | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el cisne | swan | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| el tigre | tiger | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342 |
| la tortuga | tortoise, turtle | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342; same word for both glosses |
| el pavo | turkey | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 342; also under Poultry |
| la ballena | whale | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el lobo | wolf | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| la cebra | zebra | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el tocino | bacon | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Foods — Meats," p. 343 |
| la carne de vaca | beef | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el jamón | ham | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| la hamburguesa | hamburger | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el cordero | lamb | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el hígado | liver | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343; same word also under Body parts |
| la carne | meat | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el puerco | pork | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el rosbíf | roast beef | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343; English loanword |
| las salchichas | sausages | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el bistec | steak | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343; English loanword ("beefsteak") |
| el churrasco | steak (BBQ) | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343; a grilled/barbecued-steak style term, common in Argentine/Southern Cone usage though not explicitly region-tagged here |
| el estofado, el guisado | stew | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| la ternera | veal | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el ganso | goose | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Poultry," p. 343 |
| la carne de ave | fowl | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el venado | venison | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| la anchoa | anchovy | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Fish and Seafood," p. 343 |
| la merluza | bass | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| las almejas | clams | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el bacalao | codfish | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el cangrejo | crab | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el pescado | fish (food) | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343; contrast `el pez` (live animal) |
| la platija | flounder | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el pargo colorado | red snapper | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el salmón | salmon | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| las sardinas | sardines | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| las vieiras | scallops | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| los mariscos | seafood | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| los camarones, las gambas | shrimp | noun (pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343; `camarones` Latin America, `gambas` Spain by general knowledge, though source itself doesn't tag the split explicitly here |
| el lenguado | sole | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 343 |
| el mero | grouper | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el calamar | squid | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la langosta | lobster | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el pez espada | swordfish | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| los mejillones | mussels | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la trucha | trout | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| las ostras | oysters | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el atún | tuna | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la alcachofa | artichoke | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Vegetables," p. 344 |
| los espárragos | asparagus | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| las judías, las habichuelas | beans (green) | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| los ejotes | green beans | noun (m. pl.) | core | — | contemporary (2005) | Mexico | national | grammar_reference | n/a | n/a | p. 344; explicitly tagged "(Mexico)" in source |
| las remolachas | beets | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el brócoli (el brécol) | broccoli | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la zanahoria | carrot | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la coliflor | cauliflower | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el apio | celery | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el maíz | corn | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el pepino | cucumber | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la berenjena | eggplant | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el ajo | garlic | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344; also under Dairy/Condiments |
| le lechuga | lettuce | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344; source prints article as "le" — likely a typo for "la," flagged not corrected |
| el champiñón | mushroom | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la cebolla | onion | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| las arvejas, los guisantes | peas | noun (pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la pimienta | pepper (spice) | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344; note the Vegetables list's "pepper" entry actually glosses the spice, not the vegetable — likely a source layout artifact, flagged |
| la papa, la patata | potato | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344; `papa` Latin America, `patata` Spain by general knowledge, not explicitly tagged here |
| el arroz | rice | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la ensalada | salad | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la soja | soy | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la semilla de soja | soybean | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344; source prints "semila" (missing second l) |
| la espinaca | spinach | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la papa dulce | sweet potato | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el tomate | tomato | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el nabo | turnip | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la verdura | vegetable | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el calabacín | zucchini | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la almendra | almond | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Fruits and Nuts," p. 344 |
| la manzana | apple | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el albaricoque | apricot | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| el aguacate | avocado | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 344 |
| la banana | banana | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el cacahuete, el maní | peanut | noun (m.) | core | — | contemporary (2005) | Spain, Mexico (cacahuete); Latin America (maní) | transnational | grammar_reference | n/a | n/a | p. 345; explicit regional split given by source, see opening coverage note |
| el mirtilo, el arándano azul | blueberry | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la pera | pear | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el anacardo | cashew | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la pacana | pecan | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la cereza | cherry | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la piña | pineapple | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la castaña | chestnut | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el plátano | plantain | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el coco | coconut | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la ciruela | plum | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el arándano rojo y agrio | cranberry | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345; descriptive compound ("red and sour blueberry-type fruit") |
| la ciruela pasa | prune | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la fruta | fruit | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la pasa, la uva seca | raisin | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la uva | grape | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la frambuesa, la mora | raspberry | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la toronja, el pomelo | grapefruit | noun (f./m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la fresa | strawberry | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la avellana | hazelnut | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la mandarina | tangerine | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el limón | lemon | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la nuez | walnut | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la lima | lime | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la sandía | watermelon | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la mantequilla | butter | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Dairy Products and Condiments," p. 345 |
| el queso | cheese | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la crema | cream | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| los huevos | eggs | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la harina | flour | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la mayonesa | mayonnaise | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la mostaza | mustard | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el aceite | oil | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345; also under Car Parts (motor oil) |
| el orégano | oregano | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la pimienta (black), el pimiento/el ají (red) | pepper (black/red) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345; `el ají` widely regional (Latin America) though not explicitly tagged here |
| la sacarina | saccharin | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la sal | salt | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la mermelada | jam, jelly | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| la salsa de tomate | ketchup | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el jarabe de arce | maple syrup | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el azúcar | sugar | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el vinagre | vinegar | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| el yogur | yogurt | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 345 |
| huevos fritos | fried eggs | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Eggs," p. 346 |
| huevos duros | hard-boiled eggs | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| huevos escalfados | poached eggs | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| una tortilla | an omelette | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346; note false-friend risk — `tortilla` ≠ Mexican flatbread sense here |
| huevos revueltos | scrambled eggs | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| huevos pasados por agua | soft-boiled eggs | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| huevos con chorizo | eggs with spicy sausage | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| huevos rancheros | eggs with spicy tomato sauce (fried) | noun phrase | regional | — | contemporary (2005) | Mexico (implied, not explicitly tagged) | — | grammar_reference | n/a | n/a | p. 346; a specifically Mexican dish name, though source doesn't add an explicit region tag here |
| el flan | caramel custard | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Breads and Desserts," p. 346 |
| la galleta | cracker | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el pan | bread | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el bollo | bun | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el pastel, la torta | cake | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346; `el pastel` also glosses "pie" in this same list — ambiguous overlap in source |
| la galletita | cookie | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el postre | dessert | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| la gelatina | gelatin | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el helado | ice cream | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el marzapán | marzipan | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el merengue | meringue | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el pastel | pie | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346; see cake entry above re: overlap |
| la natilla, el pudín | pudding | noun (f./m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el arroz con leche | rice pudding | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| los panecillos | rolls | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el sándwich | sandwich | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346; English loanword |
| el bizcocho | sponge cake | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el helado con frutas, jarabes o nueces; la copa de helado | sundae | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| la tarta | tart | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| la cerveza | beer | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Beverages," p. 346 |
| el champán | champagne | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el chocolate | (hot) chocolate | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| la sidra | cider | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el café | coffee | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346; also "cafe" (place) under Places in Town |
| el café descafeinado | decaffeinated coffee | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el té herbario | herbal tea | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el jugo (de naranja) | juice (orange) | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| la limonada | lemonade | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| la leche | milk | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| la batida, la licuada | milkshake | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| la gaseosa | soda | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| la sopa | soup | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346; listed here under Beverages, oddly, rather than Foods — source's own categorization |
| el té | tea | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el agua (mineral/con gas/sin gas) | (mineral/carbonated/noncarbonated) water | noun (f., irregular gender-agreement noun) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346; three distinct modified forms |
| el vino | wine | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 346 |
| el desayuno | breakfast | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Meals," p. 347 |
| el almuerzo | lunch | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| la cena | dinner | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| la merienda | snack | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el tazón | bowl | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Table Setting," p. 347 |
| el pimentero | pepper shaker | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| la garrafa | carafe | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el cubierto | place setting | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| la taza | cup | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el salero | salt shaker | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el plato | dinner plate | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el platillo | saucer | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el tenedor | fork | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| la sopera | soup dish | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el vaso | glass | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| la cuchara | soup spoon | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el cuchillo | knife | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el mantel | tablecloth | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el menú | menu | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| la cucharita | teaspoon | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| la servilleta | napkin | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| la copa | wine glass | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| el molinillo de pimienta | pepper mill | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| un saco de | a bag of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Quantities," p. 347 |
| doscientos gramos de, una media libra de | a half pound of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| una tableta de, una barra de | a bar of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| un pomo de, un frasco de | a jar of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| una botella de | a bottle of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| un paquete de | a package of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| una caja de | a box of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| quinientos gramos de, una libra de | a pound of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| una lata de | a can of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| un litro de | a quart of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| una docena de | a dozen of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |
| un trozo de | a slice of | quantifier phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 347 |

**Continues in `022_chunk3b.md`** (Parts of the Body, Places in Town, School and the Classroom, School Subjects and Activities, Professions, Leisure Time, Computer Terms, Musical Instruments, Sports, Playing Fields, Equipment).

---


---

## Spanish — Established Vocabulary: Webster's New World Spanish Grammar Handbook — Final Chunk, Appendix B continued (pp. 348–357)

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook* (1st ed., Wiley, 2005), Appendix B "Spanish Vocabulary," pp. 348–357. Continues `022_chunk3.md` (see that file's header for the full source citation, triage correction, and non-redundant-supplement scope decision — applies identically here). Covers: Parts of the Body, Places in Town, School and the Classroom, School Subjects and Activities, Professions, Leisure Time (Hobbies, Computer Terms, Musical Instruments, Sports, Playing Fields, Equipment).

All entries share Source Type `grammar_reference`, Weight/Frequency `—`, Attested Era `contemporary (2005)`, Transcription Confidence `n/a`, Vision Reading Confidence `n/a` unless noted otherwise.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| el tobillo | ankle | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Parts of the Body," p. 348 |
| el corazón | heart | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el brazo | arm | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la cadera | hip | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la espalda | back | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; also "back" of clothing, see Parts of Clothing |
| la rodilla | knee | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la barba | beard | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la pierna | leg | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la sangre | blood | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el labio | lip | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el cuerpo | body | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el hígado | liver | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; also under Foods/Meats |
| el cerebro | brain | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el pulmón | lung | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la pantorrilla | calf | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la boca | mouth | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la mejilla | cheek | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el músculo | muscle | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el pecho | chest | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el bigote, el mostacho | mustache | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la barbilla | chin | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la uña | nail (body) | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la oreja | ear | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el cuello | neck | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; also collar of clothing, see Parts of Clothing |
| el codo | elbow | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la nariz | nose | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el ojo | eye | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el hombro | shoulder | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la ceja | eyebrow | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la piel | skin | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; also "fur" under Materials |
| la pastaña | eyelash | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; source spells this "pastaña" — likely a typo for "pestaña" |
| el estómago | stomach | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el párpado | eyelid | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el muslo | thigh | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la cara | face | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la garganta | throat | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el dedo | finger | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la lengua | tongue | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; also "language" in general usage, not noted by source here |
| el dedo del pie | toe | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; literally "foot-finger" |
| el pie | foot | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el diente | tooth | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la frente | forehead | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la cintura, la talle | waist | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; also under Parts of Clothing |
| el cabello, el pelo | hair | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la mano | hand | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la muñeca | wrist | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; also means "doll" in general usage, not noted by source here |
| la cabeza | head | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el aeropuerto | airport | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Places in Town," p. 348; also under Travel |
| el monumento | monument | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| la avenida | avenue | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348 |
| el cine | movie theater | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 348; also "the movies" under Leisure/Hobbies |
| la panadería | bakery | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el museo | museum | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el banco | bank | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also "bench," see School vocabulary — same word, two senses in this appendix |
| el barrio | neighborhood | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la librería | bookstore | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; false-friend risk vs. "library" (= la biblioteca, School vocab) |
| el quiosco de periódicos | newsstand | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el bulevar; el zócalo | boulevard | noun (m.) | regional | — | contemporary (2005) | Mexico (el zócalo) | national | grammar_reference | n/a | n/a | p. 349; `el zócalo` explicitly tagged "(Mexico)" by source — note `zócalo` more commonly denotes a central town square in Mexican usage generally, source's specific gloss here is "boulevard" |
| el parque | park | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el edificio | building | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la pastelería | pastry shop | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la carnicería | butcher shop | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la comisaría | police station | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el café | cafe | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; same word as "coffee," see Beverages |
| el correo | post office | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la tienda del fotógrafo | camera shop | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la tienda de discos | record store | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la catedral | cathedral | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el restaurante | restaurant | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la iglesia | church | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el camino | road | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also under Travel |
| la tienda de ropa | clothing store | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la escuela | school | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also under School vocabulary |
| el palacio de justicia | courthouse | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la acera | sidewalk | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el almacén | department store | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el rascacielos | skyscraper | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; invariable compound (lit. "scrape-skies") |
| el centro | downtown | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la tienda de recuerdos | souvenir shop | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la farmacia | drugstore | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la plaza | square | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la tintorería | dry cleaner's | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el estadio | stadium | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also under Playing Fields |
| la fábrica | factory | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la estación | station | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also "train station" under Travel |
| la florería | florist | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la estatua | statue | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la gasolinera | gas station | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la tienda | store | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la bodega | grocery store | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la calle | street | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el gimnasio | gym | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also under School and Playing Fields |
| el suburbio | suburb | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la carretera | highway | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also under Travel |
| el supermercado | supermarket | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el hospital | hospital | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la piscina | swimming pool | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also under Playing Fields |
| el hotel | hotel | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el teatro | theater | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also under Leisure/Hobbies |
| la joyería | jewelry store | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la tabaquería | tobacco store | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la lavandería | laundry | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; same word as "laundry room," see House vocab |
| el pueblo | town | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la marroquinería | leather goods store | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el ayuntamiento | town hall | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la biblioteca | library | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349; also under School vocab |
| la juguetería | toy store | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el centro comercial | mall | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| la universidad | university | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el mercado | market | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el centro juvenil | youth center | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 349 |
| el colegio | academy | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "School and the Classroom," p. 350; also means "(private) school" in general usage |
| la escuela intermedia (entre la primaria y la secundaria) | middle school | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; explanatory gloss, not a fixed single term |
| la respuesta | answer | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el cuaderno | notebook | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la mochila | backpack | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| los apuntes | notes | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el bolígrafo | ballpoint pen | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; also "la pluma (el bolígrafo)" listed separately below as a synonym pair |
| la página | page | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el timbre | bell | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el papel | paper | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el banco | bench | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; homonym of "bank," see Places in Town |
| la pluma (el bolígrafo) | pen (ballpoint) | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el libro | book | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el lápiz | pencil | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la cantina | cafeteria | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la poesía | poetry | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la calculadora | calculator | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el director | principal | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; also "manager," see Professions |
| el calendario | calendar | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el profesor, la profesora | professor | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; also "teacher" below, same word |
| la tiza | chalk | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el alumno, el estudiante | pupil | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la pizarra | chalkboard | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la pregunta | question | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la clase | class | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la prueba | quiz | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la sala de clase | classroom | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la lectura | reading | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el ordenador, la computadora | computer | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; repeated verbatim from Appliances and Electronics |
| la hora de recreo | recess | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el consejero | counselor | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la regla | rule, ruler | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; one word, two glosses given separately by source |
| el creyón | crayon | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; English loanword adapted |
| el pupitre | (student) desk | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el diccionario | dictionary | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| los útiles | school supplies | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la escuela elemental, la primaria | elementary school | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; source spells it "elementrary" — typo |
| las tijeras | scissors | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la goma | eraser | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350; also "rubber"/"tire," see Materials/Car Parts |
| la falta | error | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la frase, la oración | sentence | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el ejercicio | exercise | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| el (la) alumno(a), el (la) estudiante | student | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la explicación | explanation | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la materia | subject | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 350 |
| la nota | grade | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el resumen | summary | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la gramática | grammar | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el (la) profesor(a) | teacher | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el gimnasio | gym | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351; repeated, listed also under Places in Town |
| el examen | test | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la escuela de segunda enseñanza, la secundaria | high school | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el profesor particular, la profesora particular | tutor | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la tarea | homework | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el vocabulario | vocabulary | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el laboratorio | laboratory | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la palabra | word | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la lección | lesson | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el trabajo | work | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el mapa | map | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el álgebra | algebra | noun (f., irregular gender) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "School Subjects and Activities," p. 351 |
| la geometría | geometry | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el arte | art | noun (m./f., varies) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la educación física | gym (subject) | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la artesanía | arts and crafts | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la historia | history | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351; source prints "historia" as the English gloss "historia" too — layout artifact, meant to read "history" |
| la banda | band | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el latín | Latin | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la biología | biology | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| las matemáticas | math | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el cálculo | calculus | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la música | music | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la química | chemistry | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la orquesta | orchestra | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el coro | chorus | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la física | physics | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el círculo | club | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la ciencia | science | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la informática | computer science | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| las artes industriales | shop (subject) | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el diseño | drawing | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el español | Spanish | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el inglés | English | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el equipo | team | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351; also "equipment," see Equipment category |
| el francés | French | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la tecnología | technology | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| la geografía | geography | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 351 |
| el contable (el contador) / la contable (la contadora) | accountant | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Professions," p. 352; two synonym pairs given |
| el actor / la actriz | actor / actress | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el artista / la artista | artist | noun (m./f., invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el atleta / la atleta | athlete | noun (m./f., invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el panadero / la panadera | baker | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el peluquero / la peluquera | barber, hairstylist | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352; same word glossed twice for two English senses |
| el hombre de negocios / la mujer de negocios | businessperson | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352; source misprints feminine form as "mujer de necocios" |
| el carnicero / la carnicera | butcher | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el cajero / la cajera | cashier | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el cocinero / la cocinera | cook | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el dentista / la dentista | dentist | noun (m./f., invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el diseñador / la diseñadora | designer | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el médico / la médica | doctor | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el electricista / la electricista | electrician | noun (m./f., invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el ingeniero / la ingeniera | engineer | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el campesino / la campesina | farmer | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el bombero / la bombera | firefighter | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el aeromozo / la aeromoza, la azafata | flight attendant | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352; two feminine synonyms given |
| el empleado del gobierno / la empleada del gobierno | government employee | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el joyero / la joyera | jeweler | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el juez / la juez | judge | noun (m./f., invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el obrero / la obrera | laborer | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el abogado / la abogada | lawyer | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el cartero / la cartera | mail carrier | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352; `la cartera` also means "wallet," see Apparel |
| el director, el gerente / la directora, la gerente | manager | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352; two synonym pairs |
| el mecánico / la mecánica | mechanic | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el comerciante / la comerciante | merchant | noun (m./f., invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 352 |
| el músico / la música | musician | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353; feminine form homonymous with "music" |
| el enfermero / la enfermera | nurse | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el pintor / la pintora | painter | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el farmaceútico / la farmaceútica | pharmacist | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el piloto / la pilota | pilot | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el poeta / la poetisa | poet | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el policía / la policía | police officer | noun (m./f., invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el presidente / la presidenta | president | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el programador / la programadora | programmer | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el investigador / la investigadora | researcher | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el dependiente / la dependiente | salesperson | noun (m./f., invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el científico / la científica | scientist | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el secretario / la secretaria | secretary | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el mozo, el mesero / la moza, la mesera | server | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el soldado / la soldada | soldier | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el profesor / la profesora | teacher | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353; repeated from School vocab |
| el camarero, el mesero, el mozo / la camarera, la mesera, la moza | waiter/waitress | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353; three synonym pairs |
| el escritor / la escritora | writer | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el ballet | ballet | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Leisure Time — Hobbies and Other Leisure Activities," p. 353 |
| la playa | beach | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353; also under Playing Fields/Nature |
| el cine | movies | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353; same word as "movie theater," Places in Town |
| la ópera | opera | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| los naipes | cards | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el desfile | parade | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el concierto | concert | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el picnic | picnic | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353; English loanword |
| el campo | country, field | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353; also under Nature/Playing Fields |
| la obra teatral | play | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| el baile | dance | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| la exposición | show | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 353 |
| la feria | fair | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el teatro | theater | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; repeated from Places in Town |
| la caminata | hike | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el paseo | walk | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la fiesta | holiday | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; also commonly means "party" in general usage |
| el parque zoológico | zoo | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la montaña | mountain | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; also under Nature/Playing Fields |
| arrancar | to boot (computer) | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Computer Terms," p. 354 |
| el control | joystick | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el byte, el coteto | byte | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; "el coteto" is an unusual calque not seen elsewhere in this corpus |
| la tecla | key (keyboard) | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el CD | CD | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el teclado | keyboard | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| chascar | to click | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; unusual verb choice — "hacer clic" is the more common form elsewhere, flagged as this source's own variant |
| la computadora portátil | laptop | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la computadora, el ordenador | computer | noun (f./m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; repeated |
| la memoria | memory | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la informática | computer science | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; repeated from School Subjects |
| fusionar | to merge | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la unidad central | CPU | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el modem | modem | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el cursor | cursor | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la carta-madre | motherboard | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; unusual term, "la placa madre" more standard elsewhere — flagged as this source's own variant |
| el ciberespacio | cyberspace | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el ratón | mouse (computer) | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la base de datos | database | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la red | network | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; also "net" under Equipment |
| la disquetera | disk drive | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| bajar, descargar | to download | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| apretar | to press | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el DVD | DVD | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| barrer | to scan | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; ordinary meaning "to sweep," repurposed here |
| el correo electrónico | e-mail | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el scanner | scanner | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; English loanword, unassimilated spelling |
| la dirección de correo electrónico | e-mail address | noun phrase | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; source misprints as "diréccion" |
| la pantalla | screen | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el disco duro | hard disk | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el buscador | search engine | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el hardware equipo, el soporte físico | hardware | noun phrase | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; direct loanword plus two calques |
| el logicial | software | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; unusual Francophone-style calque — "el software" more common elsewhere, flagged as this source's own variant |
| la página inicial | home page | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la cinta de seguridad | tape backup | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el icono | icon | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| la teleraña | Web | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354; source's spelling of "telaraña" (spiderweb), used as the calque for (World Wide) Web |
| el recado instantáneo | instant message | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el procesador de textos | word processor | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 354 |
| el internet | Internet | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el acordeón | accordion | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Musical Instruments," p. 355 |
| el cuerno | horn | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el violoncelo | cello | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el oboe | oboe | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el clarinete | clarinet | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el piano | piano | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el tambor | drum | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el piccolo | piccolo | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la batería | drum set | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355; also "battery," see Car Parts |
| el saxofón | saxophone | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la flauta | flute | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el trombón | trombone | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la guitarra | guitar | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la trompeta | trumpet | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la arpa | harp | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el violín | violin | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| los aeróbicos | aerobics | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Sports," p. 355 |
| el jai alai | jai alai | noun (m.) | regional | — | contemporary (2005) | Basque Country (sport's origin, not source-tagged) | — | grammar_reference | n/a | n/a | p. 355; Basque pelota sport, borrowed term |
| el atletismo | athletics | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el trotar (el footing) | jogging | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355; "footing" is an English-derived loanword used idiosyncratically for jogging |
| las carreras de coches | auto racing | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el alpinismo | mountain climbing | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el béisbol | baseball | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el ping-pong | Ping-Pong | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el culturismo | body-building | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el patinaje sobre ruedas | roller skating | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| los bolos | bowling | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la navegación | sailing | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el piragüismo | canoeing | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el buceo | scuba diving, diving | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355; same word listed twice by source for two English glosses |
| el ciclismo | cycling | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el patinaje sobre plancha, el monopatín | skateboarding | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la pesca de altura | deep-sea fishing | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el esquí | skiing | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la pesca | fishing | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el fútbol | soccer | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el fútbol americano | football (American) | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el surf | surfing | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el golf | golf | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la natación | swimming | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el hockey | hockey | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el tenis | tennis | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la caza | hunting | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la carrera | track | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| las carreras de caballos | horse racing | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el volibol | volleyball | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la equitación | horseback riding | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el esquí acuático | waterskiing | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el patinaje sobre hielo | ice skating | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| el windsurf | windsurfing | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 355 |
| la playa | beach | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Playing Fields," p. 356; repeated |
| el parque | park | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; repeated |
| el campo | course (golf), field | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| la piscina | pool | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; repeated |
| la cancha | court | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| la pista | rink, slope, track | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; one word, three sport-specific English glosses |
| el gimnasio | gymnasium | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; repeated |
| la montaña | mountain | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; repeated |
| el océano | ocean | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; also under Nature |
| el estadio | stadium | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; repeated from Places in Town |
| el mar | sea | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| la bola | ball (football, soccer) | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Equipment," p. 356 |
| los tenis | jogging shoes | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; same word also glosses "sneakers," see Apparel |
| la pelota | ball (baseball, jai alai, tennis) | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| el traje de trotar | jogging suit | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| el balón | ball (basketball) | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| las rodilleras | knee pads | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| el bate | bat | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| el guante | mitt | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; also plural "gloves," Apparel |
| el traje de baño | bathing suit | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; repeated under Apparel |
| la red | net | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; repeated from Computer Terms (polysemous: net/network) |
| la bicicleta | bicycle | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; repeated under Travel |
| los palos (ski) | poles (ski) | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| el barco | boat | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; also under Travel |
| el puck, el disco | puck | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| las botas (ski) | boots (ski) | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| la raqueta | racket | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| la canoa | canoe | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| el fusil, el rifle | rifle | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| el yelmo | diver's helmet | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| la plancha de vela | sailboard | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| la escafandra | diving suit, wet suit | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; same word for both glosses, listed twice by source |
| la plancha de ruedas, el monopatín | skateboard | noun (f./m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| la caña de pesca | fishing rod | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| los patines | skates | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| las aletas | flippers | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| las ataduras | ski bindings | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| las gafas de esquí | goggles (ski) | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| los esquís | skis | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| las gafas submarinas | goggles (swimming) | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| los esquís acuáticos | water-skis | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| los palos de golf | golf clubs | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| el acuaplano | surfboard | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356 |
| el casco | helmet | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 356; also "hull," not noted by source here |

**Continues in `022_chunk3c.md`** (Nature, Apparel, Materials, Parts of Clothing, Clothing Descriptions, Colors, Jewelry, Jewels, Travel and Transportation, Car Parts, Countries, The Continents, The Weather).

---


---

## Spanish — Established Vocabulary: Webster's New World Spanish Grammar Handbook — Final Chunk, Appendix B concluded (pp. 357–365)

**Source:** Gail Stein, *Webster's New World Spanish Grammar Handbook* (1st ed., Wiley, 2005), Appendix B "Spanish Vocabulary," pp. 357–365 — the final content pages of the book (its back-matter Index, pp. 366–387, is skipped per the coverage rule; see `022_chunk3.md`'s header for the full source citation, triage correction, and non-redundant-supplement scope decision). Completes Appendix B begun in `022_chunk3.md`/`022_chunk3b.md`: Nature, Apparel (Articles of Clothing, Materials, Parts of Clothing, Clothing Descriptions, Colors, Jewelry, Jewels), Travel and Transportation, Car Parts, Countries, The Continents, The Weather. **This is the end of the book's extractable content — the Webster's New World Spanish Grammar Handbook is now fully extracted across files 022/022_chunk2*/022_chunk3*.**

All entries share Source Type `grammar_reference`, Weight/Frequency `—`, Attested Era `contemporary (2005)`, Transcription Confidence `n/a`, Vision Reading Confidence `n/a` unless noted otherwise.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| la bahía, el golfo | bay | noun (f./m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Nature," p. 357 |
| el océano | ocean | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; repeated |
| la capa de ozono | ozone layer | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la nube | cloud | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el planeta | planet | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la costa | coast | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la planta | plant | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; also means "floor/story" in general usage ("la planta baja"), see House vocab |
| el campo | country, field | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; repeated |
| la charca | pond | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el desierto | desert | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la lluvia | rain | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la tierra | earth | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el río | river | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la flor | flower | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la arena | sand | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la niebla | fog | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el/la mar | sea | noun (m./f., varies) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; dual-gender noun, source notes both articles |
| la selva | forest | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; more precisely "jungle/rainforest" in general usage, glossed "forest" here — contrast `el bosque` "woods" below |
| el cielo | sky | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la hierba | grass | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la nieve | snow | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la isla | island | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la estrella | star | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la colina | hill | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el arroyo | stream | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la laguna | lagoon | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el sol | sun | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el lago | lake | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el árbol | tree | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el paisaje | landscape | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la cáscada | waterfall | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; source spells it "cáscada" — likely a typo for "cascada" |
| la hoja | leaf | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el viento | wind | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la luna | moon | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el bosque | woods | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; contrast `la selva` "forest/jungle" above |
| la montaña | mountain | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; repeated |
| el mundo | world | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el traje de baño | bathing suit | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Apparel — Articles of Clothing," p. 357; repeated |
| el jersey | pullover | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el cinturón | belt | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| el impermeable, la gabardina | raincoat | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; `la gabardine` repeated as "gabardine" fabric below under Materials |
| la blusa | blouse | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la bata | robe | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| las botas | boots | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357; repeated from Equipment (ski boots) |
| las sandalias | sandals | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 357 |
| la ropa | clothing | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la bufanda | scarf | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el abrigo | coat, overcoat | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358; same word for both glosses, listed twice by source; also "windbreaker" compound below |
| la camisa | shirt | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el vestido | dress | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el zapato | shoe | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el traje de noche | evening gown | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| los pantalones cortos | shorts | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| los guantes | gloves | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la falda | skirt | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el pañuelo | handkerchief | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el faldellín (half), la combinación (full) | slip | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358; two distinct garments by length |
| el sombrero | hat | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| los tenis | sneakers | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358; same word as "jogging shoes," Equipment |
| la chaqueta | jacket | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| los calcetines | socks | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| los vaqueros (los jeans) | jeans | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la chaqueta de esport | sports coat | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358; "esport" spelling (vs. "deporte/deportiva") looks like an Anglicism/typo |
| la ropa interior feminina | lingerie | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358; source misspells "femenina" as "feminina" |
| las medias | stockings | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| los mitones | mittens | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el suéter | sweater | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la camisa de dormir | night shirt | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la corbata | tie | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| las pijamas/piyamas | pajamas | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358; two spelling variants given |
| la camiseta | T-shirt | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el pantalón | pants | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el paraguas | umbrella | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el traje de pantalones | pantsuit | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la ropa interior | underwear | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| las pantimedias | pantyhose | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el chaleco | vest | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el bolsillo | pocket | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358; also under Parts of Clothing |
| la cartera | wallet | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358; same word as "mail carrier" (f.), Professions |
| la bolsa | pocketbook | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el abrigo contra el viento | windbreaker | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la alpaca | alpaca | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Materials," p. 358; source misprints article as "lla" |
| el cuero | leather | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la angora | angora | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el lino | linen | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la cachemira | cashmere | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la microfibra | microfiber | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| la pana | corduroy | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el nilón | nylon | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el algodón | cotton | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358 |
| el sintético | polyester | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 358; generic "synthetic" used for the specific fiber |
| la tela tejana | denim | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| la goma, el caucho, el hule, el jebe | rubber | noun (f./m.) | regional | — | contemporary (2005) | Latin America (el hule); Colombia, Peru (el jebe) | transnational | grammar_reference | n/a | n/a | p. 359; explicit regional split given by source across four synonyms, see opening coverage note |
| la franela | flannel | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el raso | satin | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el forro polar | fleece | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| la seda | silk | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| la piel | fur | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359; same word as "skin," Body parts |
| la gamusa | suede | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359; more standard spelling is "gamuza" |
| la gabardina | gabardine | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359; same word as "raincoat" above |
| el tafetán | taffeta | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el tejido de punto | knit | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el terciopelo | velvet | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el encaje | lace | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| la lana | wool | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el atrás, la espalda | back (clothing) | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Parts of Clothing," p. 359 |
| el forro | lining | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el bolsillo anterior | back pocket | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el pliegue, la pinza | pleat | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el botón | button | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el bolsillo | pocket | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359; repeated |
| el cuello | collar | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359; same word as "neck," Body parts |
| los cordones | shoelaces | noun (m. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el puño (shirt), la vuelta/el doblez (pants) | cuff | noun (m./f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359; two distinct terms by garment type |
| el bolsillo de lado | side pocket | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| la bragueta | fly | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| la manga | sleeve | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el frente | front | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el broche de presión | snap | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el tacón | heel | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| la cintura | waist | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359; repeated from Body parts |
| el bajo, el ruedo | hem | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| el cierre | zipper | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| holgado(a) | baggy | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Clothing Descriptions," p. 359 |
| modesto(a) | modest | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| casual | casual | adjective (invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| estrecho(a) | narrow | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359; same adjective also glosses "tight (clothing)" below |
| elegante | dressy | adjective (invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| corto(a) | short | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| etiquetero(a) | formal | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| pequeño(a) | small | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 359 |
| largo(a) | long | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| deportivo(a) | sporty | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| hogado(a), suelto(a) | loose | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360; "hogado(a)" is likely a typo for "holgado(a)," matching the "baggy" entry above |
| estrecho(a) (clothing), apretado(a) (shoes) | tight | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360; two distinct terms by garment type |
| chillón(ona) | loud | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| ancho(a) | wide | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| escotado(a) | low-cut | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| beige | beige | adjective (invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Colors," p. 360 |
| verde oliva | olive green | adjective phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| negro | black | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| anaranjado(a) | orange | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| azul (azul marino) | blue (navy blue) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| rosado | pink | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| café, marrón, pardo | brown | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360; three synonyms |
| morado | purple | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| granate | burgundy | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360; same word as "garnet" (noun), Jewels |
| rojo | red | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| marrón | chestnut | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360; same word also glosses "brown" above |
| color salmón | salmon (color) | adjective phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| color café | coffee (color) | adjective phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| marrón claro | tan | adjective phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| gris | gray | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| violeta | violet | adjective (invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| verde | green | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| blanco | white | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| caqui | khaki | adjective (invariable) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| amarillo | yellow | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| rojo oscuro | maroon | adjective phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| la pulsera | bracelet | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Jewelry," p. 360 |
| el broche | pin | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| la cadena | chain | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| la sortija | ring (jeweled) | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| el arete | earring | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| el anillo | ring (plain) | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| el oro | gold | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| la plata | silver | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| el collar | necklace | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360 |
| el reloj | watch | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 360; same word as "clock," House/Furnishings |
| la amatista | amethyst | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Jewels," p. 361 |
| el ónix | onyx | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el aguamarina | aquamarine | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el ópalo | opal | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el diamante | diamond | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| las perlas | pearls | noun (f. pl.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la esmeralda | emerald | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el rubí | ruby | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la granate | garnet | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; same word also glosses "burgundy" (adjective) above; note standard gender is masculine "el granate" — this source prints feminine, flagged as a possible error |
| el zafiro | sapphire | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el marfíl | ivory | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el topacio | topaz | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el jade | jade | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la turquesa | turquoise | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el avión | airplane | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Travel and Transportation," p. 361 |
| el cohete | rocket | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el aeropuerto | airport | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; repeated |
| la ruta | route | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la bicicleta | bicycle | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; repeated |
| el sedán | sedan | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el barco | boat | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; repeated |
| la nave, el buque, el barco | ship | noun (f./m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; three synonyms |
| el autobús | bus | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el transbordador espacial | space shuttle | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el terminal de autobuses | bus terminal | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el metro | subway | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el automóvil, el coche, el carro (deportivo) | car (sports) | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; `el coche`/`el carro` regional variants (Spain vs. Latin America) by general knowledge, not explicitly tagged by source here; source misprints "deportivio" |
| el taxi | taxi | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el convertible, el descapotable | convertible | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el boleto, el billete | ticket | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; `boleto` Latin America, `billete` Spain by general knowledge, not explicitly tagged here |
| el vuelo | flight | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la ventanilla | ticket window | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la autopista | freeway | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el peaje | toll | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la puerta | gate | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; same word as "door," House vocab |
| un camión articulado | trailer truck | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la carretera | highway | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; repeated |
| el tren | train | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| una minicamioneta | minivan | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la estación | train station | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; repeated (polysemous with "station" generally) |
| la motocicleta, la moto | motorcycle | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el viajero | traveler | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el pasajero | passenger | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el viaje | trip | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la furgoneta | pickup truck | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el camión | truck | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el muelle | pier | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la camioneta | van | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| el ferrocarril | railroad | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361 |
| la rueda | wheel | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; repeated under Car Parts |
| el camino | road | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 361; repeated |
| el acelerador | accelerator | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "Car Parts," p. 362 |
| la capota | hood (car) | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| la bolsa de aire | air bag | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| la bocina | horn (car) | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el acondicionador de aire | air conditioner | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el contacto | ignition | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| los frenos anti-bloqueantes | anti-lock brakes | noun (m. pl.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| la placa de matrícula | license plate | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| la batería | battery | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362; same word as "drum set," Musical Instruments |
| el motor | motor | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| la luz de freno | brake light | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el aceite | oil | noun (m.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362; repeated from Dairy/Condiments |
| los frenos | brakes | noun (m. pl.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el radiador | radiator | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el parachoques | bumper | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el portaequipajes | roof rack | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el carburador | carburetor | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el volante | steering wheel | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el embrague | clutch pedal | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el esterio | stereo (car) | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362; source spells this "esterio" — likely a typo for "estéreo" |
| el tirador de puerta | door handle | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el techo corredizo | sunroof | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el ventilador | fan (car) | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362; repeated from Appliances |
| el faro trasero | taillight | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el guardafango | fender | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| la goma, la llanta | tire | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362; same word "goma" also glosses "eraser" and "rubber" elsewhere |
| la gasolina | gasoline | noun (f.) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| la transmisión | transmission | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362; source misprints as "tansmisión" |
| el tanque | gas tank | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el baúl | trunk (car) | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el cambio de velocidades | gear shift | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el direccional | turn signal | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| la guantera | glove compartment | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| la rueda | wheel | noun (f.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362; repeated |
| el freno de mano | hand brake | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el limpia parabrisas | windshield wiper | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| el faro delantero | headlight | noun (m.) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 362 |
| Argelia | Algeria | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | "Countries," p. 362 |
| la Argentina | Argentina | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Austria | Austria | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Bélgica | Belgium | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Bélice | Belize | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Bolivia | Bolivia | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| el Brasil | Brazil | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| el Canadá | Canada | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Chile | Chile | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| China | China | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Colombia | Colombia | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Costa Rica | Costa Rica | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Cuba | Cuba | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Dinamarca | Denmark | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| la República Dominicana | Dominican Republic | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| el Ecuador | Ecuador | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Egipto | Egypt | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| El Salvador | El Salvador | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Inglaterra | England | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Finlandia | Finland | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Francia | France | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Alemania | Germany | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Grecia | Greece | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Guatemala | Guatemala | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Haití | Haiti | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Honduras | Honduras | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Hungría | Hungary | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| India | India | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Irlanda | Ireland | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Israel | Israel | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Italia | Italy | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| el Japón | Japan | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| Líbano | Lebanon | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 362 |
| México (Méjico) | Mexico | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363; two spellings given, the archaic "Méjico" alongside the modern standard |
| el Marruecos | Morocco | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| los Países Bajos | the Netherlands | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Nicaragua | Nicaragua | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Noruega | Norway | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Panamá | Panama | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Paraguay | Paraguay | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| el Perú | Peru | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Polonia | Poland | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Portugal | Portugal | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Puerto Rico | Puerto Rico | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Rumanía | Romania | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Rusia | Russia | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Escocia | Scotland | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| España | Spain | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Suecia | Sweden | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Suiza | Switzerland | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Túnez | Tunisia | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Turquía | Turkey | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| los Estados Unidos | United States | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| el Uruguay | Uruguay | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| Venezuela | Venezuela | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363 |
| África | Africa | proper noun | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | "The Continents," p. 363 |
| la Antártica | Antarctica | proper noun | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p. 363 |
| Asia | Asia | proper noun | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p. 363 |
| Australia | Australia | proper noun | core | — | contemporary (2005) | — | national | grammar_reference | n/a | n/a | p. 363; listed as a continent by the source, though it's conventionally also a country |
| Europa | Europe | proper noun | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p. 363 |
| Norte América, La América del Norte | North America | proper noun | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p. 363; two phrasing variants given |
| Sud América, la América del Sur | South America | proper noun | core | — | contemporary (2005) | — | transnational | grammar_reference | n/a | n/a | p. 363; two phrasing variants given |
| Hace mal tiempo | It's bad weather | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | "The Weather," p. 364 |
| Está cubierto | It's overcast | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364; same expression also glosses "It's cloudy" below |
| Hace buen tiempo | It's beautiful weather | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Hay lluvias torrenciales | It's pouring | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Está cubierto, Está nubloso | It's cloudy | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364; two synonym expressions |
| Llueve, Está lloviendo | It's raining | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364; simple present vs. progressive variants |
| Hace frío | It's cold | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Está lluvioso | It's showery | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Hace fresco | It's cool | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Nieva, Está nevando | It's snowing | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Hay granizo | It's hailing | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Hace sol | It's sunny | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Hace calor | It's hot | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Truena | It's thundering | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Hay humedad | It's humid | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Hace viento | It's windy | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |
| Hay relámpagos | It's lightning | expression | core | — | contemporary (2005) | — | — | grammar_reference | n/a | n/a | p. 364 |

---

### Grammar points

*(None in this file beyond the vocabulary appendix content above — all grammar-point content for this handbook's final chunk is in `022_chunk3.md`. This file and `022_chunk3b.md` are vocabulary-only continuations.)*

---


---


## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
