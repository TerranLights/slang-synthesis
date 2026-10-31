# Spanish — Established Vocabulary/Grammar: El Punto en Cuestión (sampled, garbled-OCR text layer)

**Source:** *El Punto en Cuestión* (intermediate-advanced reading/vocabulary course built around
adapted press clippings from Spanish and Latin American magazines/newspapers — El País Semanal,
El Comercio (Ecuador), El Correo Gallego, Cristina La Revista (México), Entre Estudiantes, La
Farola, Mía, El Mundo, La Nación (Argentina), El País (Colombia/España), El Tiempo (Colombia),
Tiempo de Viajar, El Universo (Ecuador), Visión, Noticias de Abya Yala, Noticias Latin América,
Oficina de Turismo de México, Revista de la Oficina de Información Diplomática, El Semanal,
Greenpeace, and comic strips by Quino, Mariscal, and others), 102 pages, 15 numbered units
(syllabus runs roughly: 1 Lengua y cultura, 2 Deporte y aventura, 3 Adicciones y excesos,
4 Televisión, 5 Tecnociencia, 6 Mujeres [en la política y el trabajo], 7 [Pueblos indígenas
amenazados / artesanía], 8 Ciudades y vivienda, 9 Prensa del corazón, 10 [Turismo/ecoturismo],
11 Lugares de leyenda [Machu Picchu], 12 Teletrabajo, 13 De fiesta, 14 Delincuencia, 15 Vida en
familia), each pairing a reading-comprehension topic with a named grammar point (verbs of
obligation; nouns ending in `-ómano`; compound words; interrogative pronouns; verbs with...;
the present perfect; infinitive as subject; passive voice; the imperfect; the preterite/
pluperfect; the simple future; present subjunctive for wishes/prohibition/request/permission/
advice/order; present subjunctive with subordinate clauses; type-2 conditional sentences).

## PDF extraction gotcha: a text layer that is present but badly OCR-garbled (new gotcha type)

**`pdftotext` on this file does produce non-empty text (correctly triaged as "TEXT," not
vision-required), but the text is NOT clean** — this is a distinct failure mode from the
font-substitution ciphers and CID-embedded-font cases already documented in
`00_Reference_Extraction_Spec.md`. Symptoms, confirmed by direct sampling across pages 5, 7, and
the full `-layout` extraction: (1) **word-spacing is pervasively lost or wrong**, with runs of
words fused together ("diariosemanalesymensuales," "comopersonaquetrabajeelcompo") and other
runs broken mid-word; (2) **accented/special characters are inconsistently substituted** — `ñ`
most often renders as `õ` ("España" → "Espaõa") but sometimes as plain `n` ("año" → "ano"), and
assorted other glyph noise appears in low-value decorative/sidebar text (pull-quotes, photo
captions, ad copy) that is frequently unrecoverable gibberish. This is consistent with a
page-scanned, OCR'd source whose underlying OCR engine produced a poor word-segmentation pass —
not a 1:1 substitution cipher, so no fixed decode table applies; also not an empty/no-text-layer
case, so full vision-reading was not undertaken either. **Practical approach taken:** rather than
attempting word-by-word reconstruction of dense running prose (which would be extremely
labor-intensive and error-prone across 102 pages), extraction focused on the book's own
"AMPLÍA TU VOCABULARIO" boxes (8 found via `grep` across the whole book) — short, two-column
headword-gloss lists that survive this kind of corruption far better than dense prose, because
each entry is short and strongly self-disambiguating from Spanish morphology/semantics even with
spacing noise — plus a few short, clearly-legible grammar callout boxes and one explicitly
on-topic dialect-comparison box in Unit 1. **Dense narrative reading-comprehension prose was NOT
reconstructed line-by-line and is not represented below** — this is a sampled, non-exhaustive
extraction, not a full-book pass. No handwritten marginalia was found (not applicable — this is
a text-layer, not vision-read, source).

**Confidence handling:** `Transcription Confidence` is set `verified` only for entries cross-
checked against the box's own context and unambiguous, recognizable Spanish morphology (the
large majority below). A small number of items with genuine residual ambiguity in the garbled
source are marked `plausible_unverified` and explicitly flagged in their Notes column — per the
"default to the riskier assumption when uncertain" principle, these are flagged rather than
silently presented as certain. `Vision Reading Confidence` is `n/a` throughout (this is a
text-layer source, however garbled, not a vision-read one).

## Direct hit on this project's own Peninsular-vs-Latin-American interest

Unit 1's grammar point is explicitly titled **"Diferencias lingüísticas entre España y
Latinoamérica"** (Linguistic differences between Spain and Latin America) — this is the clearest,
most directly on-topic content found in this entire Wave 4 dispatch for the project's
stated interest in building out Peninsular-vs-LatAm dialect coverage. See the first vocabulary
block below and the grammar point section.

## Vocabulary / Grammar

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| autobús (España) / camión (México) / colectivo (Argentina) / guagua (Venezuela) / góndola (Perú) | bus | noun (regional synonym set) | regional | — | contemporary | Spain / Mexico / Argentina / Venezuela / Peru | transnational | grammar_reference | verified | n/a | [REGIONAL] From Unit 1's explicit "Diferencias lingüísticas entre España y Latinoamérica" box, given as the book's own worked example of pan-Hispanic regional lexical variation for a single everyday concept, five ways. |
| vosotros (used for 2nd pl. informal) vs. ustedes (used for all 2nd pl. in LatAm) | you (plural, informal register) | pronoun (grammar point) | core | — | contemporary | Spain vs. Latin America | transnational | grammar_reference | verified | n/a | [REGIONAL] Explicit minimal pair given in-text: a Latin American greets friends/colleagues/siblings with "Hola, ¿cómo están ustedes?" while a Spaniard says "Hola, ¿cómo estáis?" — the book's own direct illustration of the same `vosotros`/`ustedes` split independently documented in established/087's Grammar reference appendix from a different (Peninsular-authored) source; cross-source convergence on this being THE headline Spain/LatAm grammatical marker. |
| Real Academia Española (la RAE) | the Royal Spanish Academy (language-regulating institution) | proper noun phrase (f) | formal | — | contemporary | Spain (pan-Hispanic authority) | transnational | grammar_reference | verified | n/a | Described in-text as the institution that sets the rules (orthography, grammar, punctuation, lexicon, correct usage) of the Spanish language; book poses a discussion question asking whether such institutions are necessary. |
| Primer Congreso Internacional de la Lengua Española | First International Congress of the Spanish Language | proper noun phrase (m) | formal | — | historical (held in Zacatecas, Mexico; article datelined contemporary to the 2000s-era book) | Mexico (pan-Hispanic delegates) | transnational | grammar_reference | verified | n/a | Adapted news article: over 100 linguists/writers/journalists/filmmakers/business and media technicians from ~20 countries met in Zacatecas; the King of Spain and the Mexican president both spoke, including on "el respeto por sus variantes nacionales y regionales" (respect for the language's national and regional variants) — explicit acknowledgment of pan-Hispanic dialect diversity as a live policy topic. |
| realismo magico | magical realism (literary movement/term) | noun phrase (m) | literary | — | 20th century (movement); contemporary (source) | Latin America | transnational | grammar_reference | verified | n/a | Glossed in-text as "mezclar realidad y fantasía" (to mix reality and fantasy); book pairs the term with a matching exercise of LatAm authors (Laura Esquivel, Isabel Allende, Gabriel García Márquez) and their novels (Crónica de una muerte anunciada; Como agua para chocolate; La casa de los espíritus; Cien años de soledad; Eva Luna; La ley del amor). |
| comarca | district, territory, province | noun (f) | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 2 (Deporte y aventura) "Amplía tu vocabulario" box; glossed "territorio, provincia." |
| idóneo | ideal, suitable | adjective | formal | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "ideal." |
| lancha | small boat, launch | noun (f) | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "embarcación." |
| piraguas | canoes/kayaks | noun (fpl) | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "canoas." |
| tirarse de | to throw/hurl oneself from | verb phrase | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "lanzarse de." |
| se tumba | lies face-down | verb phrase (reflexive) | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "se pone boca abajo." |
| Viejo Continente | the Old World (i.e. Europe) | noun phrase (m, periphrasis) | literary | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed simply "Europa" — a journalistic/literary periphrasis for the continent. |
| -ómano (suffix family): cocainómano, heroinómano, toxicómano, melómano, mitómano, cleptómano | cocaine addict, heroin addict, drug addict, music lover/"melomaniac", pathological liar/"mythomaniac", kleptomaniac | noun (productive derivational suffix) | formal/clinical | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 3's named grammar point ("Sustantivos acabados en -ómano," confirmed against the TOC listing "-adicto y -mono" which this sampling clarifies is actually `-ómano`, not `-mono`/`-mano` as the badly garbled TOC text alone suggested). A clean, productive agentive-obsession suffix family — directly relevant to this project's own slang-derivation-mechanism interests (morphological_play-type derivation from a bound Greek-origin suffix). |
| estar colgado/a (coloq.) | to be hooked/addicted | verb phrase (idiom) | colloquial | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 3 box; glossed "estás obsesionada" in the example sentence "estás colgada." |
| tragaperras | slot machines (lit. "coin-swallowers") | noun (fpl, compound) | colloquial | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 3 box; glossed "las máquinas de juego." Transparent verb-stem + noun compound (`traga-` from `tragar`, "to swallow," + `-perras`, "pesetas/coins"). |
| borrachera | drunkenness, hangover (the state resulting from excess drinking) | noun (f) | colloquial | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 3 box; glossed in-text as "resultado de beber alcohol en exceso." |
| desinhibirme | to lose my inhibitions | verb (reflexive) | formal | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 3 box; glossed "perder las inhibiciones," in context of alcohol's social effects. |
| drogas de diseño (como el speed) | designer drugs (such as speed) | noun phrase (fpl) | colloquial | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 3 box; glossed "drogas sintéticas como el speed" — notable for the direct English loanword `speed` used unglossed in the Spanish source itself (borrowing-type slang derivation, already in active use in the source language). |
| teleaudiencia / televidente | TV audience / TV viewer | noun (f / m-f, compound) | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 4 (Televisión) compound-word grammar-point list; `tele-` (television) + `audiencia`/`vidente`. |
| abrebotellas / sacacorchos / cortaúñas / guardaespaldas | bottle-opener / corkscrew / nail clippers / bodyguard | noun (m, compound, invariable in number) | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same compound-word list (verb-stem + plural-noun compounds: `abre-`+`botellas`, `saca-`+`corchos`, `corta-`+`uñas`, `guarda-`+`espaldas`); book's own exercise also elicits `rascacielos` (skyscraper), `sofá cama` (sofa bed), `mediodía` (noon), `portaequipajes` (luggage rack) via a fill-in matching exercise. |
| compraventa / pelirrojo / medianoche / pasatiempo | buying-and-selling / redheaded / midnight / pastime | noun/adjective (compound, "por fusión") | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Explicit grammar-point examples of the "por fusión" compound type (noun+noun: compraventa; noun+adjective: pelirrojo; adjective+noun: medianoche; verb+noun: pasatiempo). |
| hombre rana → hombres rana | frogman/diver → frogmen/divers | noun phrase (m, compound, "por unión") | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | plausible_unverified | n/a | Grammar point: for "por unión" (juxtaposition-type) noun+noun compounds, only the FIRST noun takes the plural marker (los hombres rana, not "los hombres ranas"). Flagged `plausible_unverified`: the specific headword in the garbled source reads as "hombrerona," which is almost certainly OCR noise for "hombre rana" given the stated noun+noun compound-type context and the well-known status of this exact example in Spanish pedagogical grammar, but the raw string itself could not be independently cross-checked against a second clean occurrence in this source. |
| taurino | relating to bullfighting | adjective | formal | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 6 (Mujeres) box; glossed "relativo al mundo de los toros." |
| hostil | hostile, unfavorable | adjective | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "contrario, poco favorable." |
| prensa del corazón | gossip/tabloid press (lit. "press of the heart") | noun phrase (f, named register) | colloquial | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 9's own named register category, glossed in-text as press that "se ocupa de la vida privada de personajes públicos del mundo del espectáculo y de la alta sociedad" (covers the private lives of celebrities and high society); named Spanish gossip magazines given: Hola, Diez Minutos, Semana, Pronto; Mexican equivalent Alarma (sensationalist, sells over a million copies). |
| tío/a (coloq.) [reconstruction uncertain] | guy/dude, girl (colloquial address term) | noun (m/f) | slang | — | contemporary | Spain | national | grammar_reference | low_confidence | n/a | A fashion/appearance-unit vocabulary box glosses a headword rendered in the garbled source as "tiola" with "individuo, persona" — strongly suggestive of the well-known Peninsular slang `tío`/`tía` ("guy"/"girl," explicitly marked `(coloq.)` in-text) given the gloss and register, but the exact headword could not be confirmed letter-for-letter against the source, so this entry is flagged `low_confidence` rather than presented as certain. If confirmed in a future cleaner pass, this would be a second independent attestation (alongside common knowledge of the term) of this iconic Peninsular colloquialism. |
| gomina | hair gel/pomade | noun (f) | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same appearance-unit box; glossed "crema para fijar el pelo." |
| acera | sidewalk, pavement | noun (f) | core | — | contemporary | Spain | national | grammar_reference | verified | n/a | [REGIONAL] Glossed "parte de la calle destinada a los peatones." This is the Peninsular term already flagged as contrasting with Latin American `vereda` in established/002 (vereda = pavement, [REGIONAL] vs. acera in Spain) — this source independently confirms `acera` as the Peninsular member of that pair, now attested from a second, independent source. |
| marquesina | bus shelter | noun (f) | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "cubierta para la parada del bus." |
| llevar más razón que un santo | to be absolutely right (lit. "to carry more reason than a saint") | idiom | colloquial | — | contemporary | Spain | national | grammar_reference | verified | n/a | [REGIONAL] Glossed in-text as "tener toda la razón, ser correcto en lo que dice" — a vivid, culturally Catholic-inflected Peninsular idiom with no equivalent previously flagged in this corpus. |
| apestado/a | pariah, shunned (lit. "plagued," i.e. treated as diseased) | adjective (participial) | colloquial | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Appearance-unit box; glossed "infectado de una enfermedad," used figuratively for someone shunned for how they dress/look. |
| erigido | erected, built | adjective (participial) | formal | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 11 (Lugares de leyenda / Machu Picchu) box; glossed "construido." |
| alfarería | pottery | noun (f) | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "cerámica." |
| apogeo | peak, golden age | noun (m) | formal | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "esplendor, época dorada." |
| Acllas | consecrated virgins (Inca religious role) | proper noun (fpl, Quechua loanword) | technical.historical | — | historical (Inca era); term used in a contemporary pedagogical text | Peru (Inca Andean) | regional | grammar_reference | verified | n/a | Glossed in-text "vírgenes consagradas" — a Quechua-origin term for a specific Inca religious institution (the "Chosen Women"), borrowed directly into the Spanish-language reading text; a genuine non-Hispanic substrate loanword distinct from any Peninsular/LatAm Spanish-internal contrast. |
| andino/a | Andean | adjective | core | — | contemporary | Peru / Andean region | regional | grammar_reference | verified | n/a | Same Machu Picchu unit box; glossed "de los Andes." |
| toque de queda | curfew | noun phrase (m) | formal | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Unit 14 (Delincuencia) box; glossed in-text as "tiempo después del cual las personas deben permanecer en sus casas hasta el día siguiente" — reading text discusses a real curfew imposed in Cali, Colombia, against juvenile delinquency. |
| deambular | to wander (without a set direction) | verb | formal | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "caminar sin dirección determinada." |
| ocioso/a | idle (doing nothing) | adjective | core | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "que no hace nada." |
| se desprende de | it follows/can be deduced from | verb phrase (impersonal) | formal | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "se deduce de," used of protest reports. |
| delincuencial | criminal (adjective) | adjective | formal | — | contemporary | Spain (pan-Hispanic) | transnational | grammar_reference | verified | n/a | Same box; glossed "criminal(es)." |

## Grammar points

### Diferencias lingüísticas entre España y Latinoamérica (Unit 1's own named grammar point)

The book devotes an explicit grammar/vocabulary callout box in Unit 1 to Spain-vs-Latin-America
variation, built around two concrete axes:

1. **Lexical**: the word for "bus" varies by country — `autobús` (Spain), `camión` (Mexico),
   `colectivo` (Argentina), `la guagua` (Venezuela), `la góndola` (Peru) — framed as representative
   of broader everyday-vocabulary divergence across the Spanish-speaking world, not an exhaustive
   list.
2. **Grammatical**: the `vosotros` (Spain) vs. `ustedes` (all of Latin America) split for 2nd-
   person-plural informal address, illustrated with a direct minimal-pair greeting: Latin American
   "Hola, ¿cómo están ustedes?" vs. Peninsular "Hola, ¿cómo estáis?"

A follow-on matching exercise pairs additional country-tagged colloquial words (at least Mexico
and Argentina are represented) with Peninsular equivalents, but the specific word-pairs in that
exercise were too badly OCR-garbled in this source to transcribe with any confidence and are
deliberately NOT included in the table above (per this file's "default to the riskier assumption
when uncertain" handling) — a future cleaner re-extraction pass (vision-reading the relevant
page) could recover them if this book is revisited.

### Compound-word formation: "por fusión" vs. "por unión"

Unit 4's grammar point distinguishes two compounding patterns: **"por fusión"** (true fusion,
where the compound behaves as a normal noun for pluralization — `comproventa`/`compraventa`,
`pelirrojo`, `medianoche`, `pasatiempo`) vs. **"por unión"** (juxtaposition of two nouns where only
the first noun pluralizes — `hombre rana` → `hombres rana`, not `hombres ranas`). This is a clean,
general Spanish word-formation rule, independently useful for any downstream compound-slang
derivation work in this project's mechanics-analysis phase.

## Relationship to other Spanish `established/` files

The `vosotros`/`ustedes` Spain-vs-LatAm split documented here from a Latin-American/general-
market-oriented textbook independently corroborates the same split documented in established/087
(a Peninsular-authored textbook's full `vosotros` conjugation tables) and in established/002's
LatAm-side regional-annotation glossary passes — now attested from three independent source
angles. The `acera` (Spain) vs. `vereda` (Latin America) pavement/sidewalk pair is likewise now
attested from a second independent source beyond established/002. This file's drug/addiction
`-ómano` suffix family and its `tragaperras`/`estar colgado` colloquialisms are new to this
corpus and have no prior established/ coverage.
