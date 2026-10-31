# Spanish — Established Vocabulary/Reference: 75 Temas de Español

**Source:** *75 Temas de Español* (255 pp., text-layer PDF), a Spanish-language textbook
structured as 75 themed topic units, apparently produced for Russian-speaking learners (title
page and per-unit glosses carry Cyrillic back-translations; the Cyrillic text itself fails to
extract cleanly — `pdftotext` throws "Unknown character collection 'PDFXC30-Indentity0'" and the
Russian glosses come through as blank or garbled lines, a font-cipher-adjacent gotcha distinct
from the CJK font-cipher pattern seen in other languages' corpora). The Spanish-language text
layer itself is clean and reliable. Despite living in the "Graded Readers" folder, this is not
narrative fiction — it is organized exactly like a themed vocabulary/culture reader-reference, so
it was triaged and extracted as a **reference work**, consistent with the wave's instruction to
treat confirmed non-fiction readers this way.

**Structure:** each of the ~75 topic units pairs a short Spanish-language reading passage (1–2
pages) with a **"Vocabulario" box** (a bulleted list of key terms tagged by part of speech — m/f/
adj/vt/vi/adv — with a Russian gloss that does not survive extraction), followed by comprehension
questions ("Responde a las preguntas") and translation drills ("Traduce"). 67 "Vocabulario"
headers were found via `grep` across the extracted text. Topics span autobiography/family,
hobbies and sports, Spanish geography and cities, the Camino de Santiago pilgrimage, Spanish
political history (the Transición, 1975–1982), pre-Columbian history (the Inca empire), Latin
American geography (Cuba), the Spanish economy, ecology (Doñana National Park), social customs
and etiquette, festivals, Sephardic Jewish and Roma history in Spain, Spanish literature (Don
Quijote), and folk tales.

**Extraction approach:** given 67 vocabulary boxes across 255 pages (likely 700+ total terms),
this file is a **representative, topic-diverse sample** (~150 terms) rather than an exhaustive
transcription of every box — consistent with how large single-source textbooks are handled
elsewhere in this corpus (e.g. the `010`–`013` family samples representative units rather than
every page). Sampled roughly every 5th vocabulary box, spread evenly from early to late in the
book, to maximize topic coverage. Because the book's own glosses (Russian) do not survive
extraction, the English glosses below are supplied directly by the extractor from the Spanish
source term, not transcribed from the book.

**Checked against existing corpus:** no prior Spanish `established/` file is organized as a
themed reader with this topic range (Camino de Santiago, Inca empire, Doñana, Transición-era
politics, Sephardic/Roma history are not covered elsewhere in this corpus). Core grammar/everyday
vocabulary overlaps with the `079_must_know_spanish_4000_words.md` / `082_using_spanish_vocabulary.md`
general-vocabulary files are expected and not flagged individually; this file's value is the
topic-specific and culture-specific vocabulary layer, not basic core words.

**Notable find:** the custom-and-etiquette unit includes the colloquial idiom **hacer la pelota**
("to suck up to/flatter someone," lit. "to make the ball") — flagged explicitly in the source text
as a culturally distinctive Spanish social behavior ("los españoles pueden hacer un poco la
pelota"). This is a genuine informal-register idiom, distinct from the book's otherwise neutral/
formal register.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Bachillerato | Spanish secondary-school qualification/diploma (ages ~16–18) | noun (m) | core | high | contemporary | Spain | Spain-specific (education system term) | grammar_reference | verified | n/a | unit on education/future plans (p. ~8) |
| entrar en | to enter, enroll in (a program, field) | verb phrase | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | education/hobbies unit |
| hacer ilusión | to be exciting/appealing (to someone), to look forward to | idiom | core | medium | contemporary | Spain | pan-Hispanic | grammar_reference | verified | n/a | common Peninsular idiom of anticipation |
| traductor | translator | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | careers/future-plans unit |
| intérprete | interpreter | noun (m/f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | careers/future-plans unit |
| práctico | practical | adjective | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| practicar | to practice (a sport/skill) | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | hobbies/sports unit |
| sueño | dream | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| preferencia | preference | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| hispano | Hispanic | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| aficionado | fan, enthusiast | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | sports unit |
| natación | swimming | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| parabólica | satellite dish | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | "compramos una parabólica" (to watch football) |
| piscina | swimming pool | noun (f) | core | high | contemporary | Spain | pan-Hispanic (alberca in Mexico) | grammar_reference | verified | n/a | dialect note: alberca is the Mexican equivalent |
| plan | plan | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| destino | destination; fate | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Camino de Santiago unit |
| peregrino | pilgrim | noun (m) | core | medium | contemporary | Spain | pan-Hispanic | grammar_reference | verified | n/a | Camino de Santiago pilgrimage unit |
| atraer | to attract | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| acoger | to welcome, take in | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| rodear | to surround | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| caminante | walker, traveler on foot | noun (m) | literary/formal | low | contemporary | Spain | pan-Hispanic | grammar_reference | verified | n/a | Camino de Santiago context |
| monja | nun | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| universitario | university-related; university student | adjective/noun | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| mayoría | majority | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | also recurs in politics unit |
| fundar | to found, establish | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| obispo | bishop | noun (m) | formal | low | contemporary | Spain | pan-Hispanic | grammar_reference | verified | n/a | Camino de Santiago/church-history context |
| descubrimiento | discovery | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| milagroso | miraculous | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | legend of Santiago's tomb discovery |
| tumba | tomb | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| restos | remains | noun (m, pl) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| Matamoros | "Moor-slayer" (epithet of Santiago/St. James) | proper noun (epithet) | formal/historical | low | historical (medieval legend, as retold contemporarily) | Spain | Spain-specific | grammar_reference | verified | n/a | Santiago Matamoros, Reconquista legend |
| guiar | to guide | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| discípulo | disciple | noun (m) | formal | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | religious/historical context |
| robar | to steal | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| asesinar | to murder, assassinate | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| iniciar | to begin, initiate | verb (vt) | core/formal | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| latín | Latin (language) | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| alojamiento | lodging, accommodation | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | pilgrim-route context |
| olla | (cooking) pot | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| monarquía | monarchy | noun (f) | formal | medium | contemporary | Spain | pan-Hispanic | grammar_reference | verified | n/a | Transición-era politics unit |
| príncipe | prince | noun (m) | core | medium | contemporary | Spain | pan-Hispanic | grammar_reference | verified | n/a | |
| reinar | to reign | verb (vi) | formal | low | contemporary | Spain | pan-Hispanic | grammar_reference | verified | n/a | |
| transición | transition | noun (f) | formal | high | contemporary | Spain | pan-Hispanic | grammar_reference | verified | n/a | capitalized "la Transición" = Spain's 1975–82 democratic transition |
| objetivo | objective, goal | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| implantar | to implement, establish | verb (vt) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| presentar | to present | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| representativo | representative (adj.) | adjective | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | political-systems context |
| mantener | to maintain | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| ley | law | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | recurs in both politics and etiquette units |
| institución | institution | noun (f) | formal | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| opuesto | opposite, opposed | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| órgano | organ, body (institutional sense) | noun (m) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | "órgano del Estado" sense |
| optar por | to opt for | verb phrase | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| llevar a cabo | to carry out | idiom/verb phrase | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | very common formal-register collocation |
| partiendo de | starting from | verb phrase (gerund) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| intermedio | intermediate | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| evitar | to avoid | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| imperio | empire | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Inca empire history unit |
| apogeo | peak, height (of power) | noun (m) | formal/literary | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | "el apogeo del imperio" |
| sagrado | sacred | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| respetar | to respect | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| incluir | to include | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| difundir | to spread, disseminate | verb (vt) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| escritura | writing, script | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Inca quipu/writing-systems context |
| nudo | knot | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | quipu (Inca knot-recording system) context |
| anotación | annotation, notation | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| romano | Roman | adjective/noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | comparison to Roman road/administrative network |
| unidad | unit | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| tamaño | size | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| mediante | by means of | preposition/adverb | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| jerarquía | hierarchy | noun (f) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Inca social-structure context |
| extenso | extensive | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| red | network | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Inca road network |
| irrigación | irrigation | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| intrincado | intricate | adjective | formal/literary | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| calabaza | pumpkin, squash | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | also recurs in Camino de Santiago unit as pilgrim symbol |
| cacahuete | peanut | noun (m) | core | medium | contemporary | Spain | pan-Hispanic (cacahuate in Mexico) | grammar_reference | verified | n/a | dialect note: cacahuate in Mexican Spanish |
| criar | to raise, breed | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| conejillo de Indias | guinea pig | noun phrase (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic (esp. Andean food context) | grammar_reference | verified | n/a | Andean/Inca food-animal context |
| llanura | plain, flatland | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Cuba geography unit |
| suelo | soil, ground | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| fértil | fertile | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| favorable | favorable | adjective | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| escenario | setting, scenario; stage | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| pino | pine tree | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Isla de Pinos (Cuba) context |
| langosta | lobster; locust | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | two-meanings-in-one-word note (crustacean/insect) |
| esponja | sponge | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Caribbean marine-life context |
| refugio | refuge, shelter | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| cárcel | prison | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| crecimiento | growth | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Spanish-economy unit |
| servicio | service | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| fuente | source; fountain | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| ingreso | income | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| maquinaria | machinery | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| secano | dry-farmed/unirrigated land | noun (m) | specialized | low | contemporary | Spain | Spain-specific agricultural term | grammar_reference | verified | n/a | agriculture-specific vocabulary |
| regadío | irrigated land | noun (m) | specialized | low | contemporary | Spain | Spain-specific agricultural term | grammar_reference | verified | n/a | paired with secano as a Spain-specific agricultural contrast pair |
| cereales | grains, cereals | noun (m, pl) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| cebada | barley | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| vid | grapevine | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| aprovechamiento | utilization | noun (m) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| riego | irrigation | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| adaptar | to adapt | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| consumir | to consume | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| hortaliza | vegetable (garden produce) | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| alimenticio | food-related, nutritional | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| conectar | to connect | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| ganadería | livestock farming | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| litoral | coast, coastline | noun (m) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| atún | tuna | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| pesquero | fishing (adj., of fishing industry) | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| cobre | copper | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| siderúrgico | iron-and-steel (adj., of steel industry) | adjective | specialized | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | industry-specific term |
| coincidir | to coincide | verb (vi) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Doñana National Park ecology unit |
| patrimonio | heritage | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | "Patrimonio Mundial" = UNESCO World Heritage |
| condicionar | to condition, determine | verb (vt) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| forestal | forest (adj.) | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| afrontar | to confront, face | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| riesgo | risk | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| deterioro | deterioration | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| especie | species | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| extinción | extinction | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| emisión | emission | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| valioso | valuable | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| espacio | space | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | "espacio natural protegido" sense |
| humedal | wetland | noun (m) | specialized | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | ecology-specific term |
| vulnerabilidad | vulnerability | noun (f) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| incendio | fire (wildfire) | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| marisma | marsh, salt marsh | noun (f) | specialized | low | contemporary | Spain | Spain-specific (Doñana marshland) | grammar_reference | verified | n/a | defining feature of Doñana's landscape |
| rito / ritual | rite / ritual | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | customs/etiquette unit |
| cotidiano | everyday, daily | adjective | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| riguroso | rigorous, strict | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| hacer el ridículo | to make a fool of oneself | idiom | colloquial | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| hacer la pelota | to suck up to/flatter someone, lit. "to make the ball" | idiom | colloquial/slang | medium | contemporary | Spain | Spain-specific (Peninsular idiom) | grammar_reference | verified | n/a | FLAGSHIP FIND — text explicitly frames this as a distinctive Spanish social habit: "los españoles pueden hacer un poco la pelota," empty flattery as a social lubricant |
| cumplir | to comply, fulfill | verb (vi/vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| comportarse | to behave | verb (reflexive) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| requerir | to require | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| manifestar | to express, manifest | verb (vt) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| abrazarse | to hug (each other) | verb (reflexive/reciprocal) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | greeting-customs context |
| dar una palmada | to clap, pat | idiom/verb phrase | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| rozar | to brush against, graze | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | personal-space/greeting-customs context |
| mucho gusto | pleased to meet you | fixed expression | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | standard introduction formula |
| felicitar | to congratulate | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| funerales | funeral(s) | noun (m, pl) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| dar el pésame | to give (one's) condolences | idiom/verb phrase | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | funeral-etiquette set phrase |
| difunto | the deceased | noun (m) | formal | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| útil | useful | adjective | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| estornudar | to sneeze | verb (vi) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | etiquette unit — sneezing customs |
| de mala educación | rude, bad manners | idiom/adj. phrase | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| aclimatación | acclimatization | noun (f) | formal | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | modernization/adaptation-themed unit |
| matiz | nuance | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| fascinación | fascination | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| declarar | to declare | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| cheque sin fondos | bounced check (check without funds) | noun phrase (m) | specialized | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | banking/legal term |
| delito | crime, offense | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| trámite | procedure, formality (bureaucratic) | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| atender | to attend to | verb (vi/vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| recetar | to prescribe | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | medical context |
| ingenio | ingenuity, wit | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| burlar | to deceive, outwit | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| rellenar | to fill in/out (a form) | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| tapón irrellenable | non-refillable cap/stopper | noun phrase (m) | specialized | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | consumer-goods context |
| judío | Jewish; Jew | adjective/noun | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Sephardic-Jewish-history-in-Spain unit |
| malinterpretación | misinterpretation | noun (f) | formal | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| gitano | Roma person ("gypsy," dated/sometimes-pejorative term still in common use) | noun (m) | core | medium | contemporary | Spain | Spain-specific (Roma/Gitano history in Spain) | grammar_reference | verified | n/a | usage-caution note: term carries mixed connotations depending on context/speaker; source text uses it neutrally in a historical-demographic sense |
| pertenecer | to belong | verb (vi) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| trasladarse | to move, relocate | verb (reflexive) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | also recurs in family/autobiography unit |
| expulsar | to expel | verb (vt) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | historical context: 1492 Jewish expulsion |
| punto de destino | destination point | noun phrase (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| núcleo | nucleus, core (of a community/settlement) | noun (m) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| manifestación | demonstration; manifestation | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| mezcla | mixture | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | cultural-mixing context |
| auge | boom, peak | noun (m) | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| nómada | nomadic | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Roma-history context |
| ingenioso | ingenious | adjective | core/literary | medium | contemporary (literary reference to Golden Age classic) | Spain | pan-Hispanic | grammar_reference | verified | n/a | Don Quijote unit — echoes the novel's full title "El ingenioso hidalgo..." |
| editar | to publish, edit | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| culto | cultured, learned | adjective | formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| continuación | continuation, sequel | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Don Quijote Part II context |
| sátira | satire | noun (f) | formal/literary | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| caballería | chivalry; knighthood | noun (f) | formal/literary | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | "novelas de caballería" — chivalric romance genre Don Quijote parodies |
| novela policíaca | detective novel | noun phrase (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | genre-comparison context |
| pretexto | pretext | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| protagonista | protagonist | noun (m/f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| escudero | squire | noun (m) | literary | low | contemporary | Spain | pan-Hispanic | grammar_reference | verified | n/a | Sancho Panza's role as Don Quijote's escudero |
| impulso | impulse | noun (m) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| limitarse | to limit oneself | verb (reflexive) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| sentido común | common sense | noun phrase (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| sustituir | to substitute, replace | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| procurar | to try to, endeavor | verb (vt) | core/formal | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| justo | just, fair | adjective | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| desesperación | despair | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| fe | faith | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| tosco | coarse, crude | adjective | core/literary | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| comilón | big eater, glutton | noun (m) | colloquial | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | Sancho Panza's characterization |
| ejemplar | exemplary | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| fidelidad | fidelity, loyalty | noun (f) | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| compartir | to share | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| Érase una vez | Once upon a time | fixed expression | core/literary | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | folk-tale unit (an "Appointment in Samarra"-type story set in Ispahán/Baghdad); standard Spanish fairy-tale opener |
| criado | servant | noun (m) | core/literary | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| mercader | merchant | noun (m) | literary | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | more literary register than comerciante |
| gesto | gesture | noun (m) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| asustar | to frighten | verb (vt) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| amo | master | noun (m) | core/literary | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| veloz | swift, fast | adjective | literary | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | more literary register than rápido |
| remoto | remote, far-off | adjective | core | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| huir | to flee | verb (vi) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| amenaza | threat | noun (f) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| compadecerse de | to take pity on | verb (reflexive + prep) | formal/literary | low | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| partir | to depart | verb (vi) | core/literary | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| suceder | to happen | verb (vi) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| acercarse | to approach | verb (reflexive) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | |
| asombro | astonishment | noun (m) | core/literary | medium | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | the folk tale's twist hinges on this word ("un gesto... de asombro," not of threat — Death is surprised to see the servant far from where fate decreed) |
| llevarse | to take away | verb (vt, reflexive-benefactive) | core | high | contemporary | pan-Hispanic | pan-Hispanic | grammar_reference | verified | n/a | "esta noche debo llevarme... a tu criado" — Death's line, the tale's punchline setup |
