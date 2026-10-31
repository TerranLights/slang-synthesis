# Spanish — Established Vocabulary/Grammar: Teach Yourself Improve Your Spanish (near-full extraction)

**Source:** *Teach Yourself: Improve Your Spanish* (31-page PDF scanned via a Canon camera/scanner,
2011 scan timestamp, page rotation metadata 270°). Triage classified this as TEXT, but **that
classification is INCORRECT and was caught by the mandatory pre-write text-layer check**: `pdftotext`
does return non-empty output, but the extracted text is font-cipher/OCR garbage ("3 e3 / q qg / a / o /
tr / o" etc.) — completely unreadable, not usable prose. Treated as vision-required instead; `pdftoppm`
renders the pages correctly (the 270° rotation metadata is auto-applied by `pdftoppm`, producing
right-side-up images).

**CONFIRMED STRUCTURAL FINDING: this PDF is a "look inside" sampler/excerpt, not the complete book.**
Printed page footers jump non-sequentially between consecutive PDF pages (PDF page 9 → printed pp.58-
59; PDF page 10 → printed pp.60-61; PDF page 11 → printed pp.74-75 — a 13-printed-page jump between
consecutive PDF pages), and the unit numbering visible in the margins runs 01 through 12 across only
31 PDF pages. This is a promotional/sample excerpt pulling one or two representative page-spreads from
each of the full book's ~12 units (each PDF page = a 2-printed-page scanned spread), not a sequential
31-page book. Given this, the "fuller coverage" framing in the dispatch is especially apt: **all 31 PDF
pages (the entire available sampler) were vision-read**, which is a complete read of this PDF's actual
content, not a partial sample of a larger whole.

**Content format confirmed valuable, matching the dispatch's expectation:** each lesson excerpt is a
short dialogue followed by a boxed vocabulary list and (often) an explicit English-language register/
usage note — exactly the "concentrated register/common-error advice" format expected for a compact
"improve your Spanish" guide, comparable in spirit to Wave S1's *Correct Your Spanish Blunders*. One
genuine dialect/register warning was found (see `coger` below) plus a strong haul of colloquial filler
expressions, idioms, and exclamations not well represented elsewhere in this corpus's intermediate/
advanced-course sampling.

**Non-redundant-supplement note:** basic nuts-and-bolts grammar explanations shown alongside the
dialogues (impersonal se, perfect tense, imperative spelling changes c→qu/g→gu/g→j, si-clauses,
seguir/continuar + gerund) are NOT re-extracted in depth — already covered elsewhere in this corpus —
but a few register-relevant grammar notes are kept where they came with an explicit usage flag.

---

## Vocabulary — Register, Idioms, and Discourse Fillers (highest-value finds)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| coger | to take/catch/grab — ordinary everyday verb in Spain | verb | core | — | contemporary | Spain | national | grammar_reference | n/a | verified | **Explicit dialect/register warning given by the book itself**: "In certain Latin-American countries, notably Argentina, coger is a taboo word and it is better to avoid it. Tomar will be understood everywhere." Unit 7, printed p.92 |
| ¡qué va! | certainly not!, nonsense!, rubbish!, not at all! | interjection | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Explicitly flagged by the book as a high-frequency colloquial filler with context-dependent translation; Unit 1, printed p.4-5 |
| pero vamos | discourse filler, roughly "well..." (softening/hedging particle) | discourse filler | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Book's own note: "a word of high frequency in spoken Spanish, used as a filler in conversation, just as English uses the word well"; Unit 1, printed p.3 |
| lo que pasa es que... | what happens is that... / the thing is... | discourse filler | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Unit 3, printed p.29 |
| el colmo (de la incompetencia) | the last straw, the limit (of incompetence) | idiom | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | "¡Esto es el colmo de la incompetencia!"; Unit 8, printed p.109 |
| ¡no me digas! | you don't say!, no way! | interjection | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Unit 9, printed p.121 |
| ¡hombre! | interjection expressing surprise: "good heavens!", "well!" | interjection | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Unit 9/10, printed p.123, 138 |
| ¿de veras? | really? | interjection | core | — | contemporary | national | national | grammar_reference | n/a | verified | Unit 9, printed p.121 |
| ¡quién lo hubiera creído! | who would have thought it! | idiom | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Surprise-expression phrase bank; Unit 9, printed p.123 |
| con los brazos cruzados | idiom: twiddling one's thumbs, doing nothing (lit. "with arms crossed") | idiom | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | "no nos podemos quedar de brazos cruzados"; Unit 11, printed p.148 |
| ¡qué quiere que le diga! | what can I say!, what do you want me to say! | idiom | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Unit 11, printed p.149 |
| desde luego | certainly, of course | discourse phrase | core | — | contemporary | national | national | grammar_reference | n/a | verified | Unit 11, printed p.149 |
| fregar los cacharros | to do the washing-up/dishes | verb phrase | core | — | contemporary | national | national | grammar_reference | n/a | verified | Unit 12, printed p.160 |
| cotillear | to gossip | verb | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | "a cotillear y qué sé yo" (to gossip and whatnot); audio transcript appendix, Unit 9, printed p.206 |
| ¡qué sé yo! | what do I know!, and whatnot, or something like that | discourse filler | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Used as a vague-trailing-off filler after a list; printed p.206 |
| ¡ya era hora! | idiom: it was about time!, about time too! | idiom | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Transcript appendix, Unit 11, printed p.208 |
| me lo quedo | I'll take it (shopping fixed phrase) | phrase | core | — | contemporary | national | national | grammar_reference | n/a | verified | Unit 9, printed p.120 |
| ¿y qué tal? | colloquial: "how did it go?"/"how was it?" (meaning shifts with context) | discourse phrase | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | Book's own note flags this as a colloquial phrase whose translation depends entirely on context; Unit 5, printed p.59 |
| estoy constipado/a | I have a cold (NOT the English false friend "constipated") | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Classic Spanish/English false-friend trap, explicitly listed in the "describing other minor ailments" phrase bank; Unit 10, printed p.139 |

## Vocabulary — Lesson Topic Clusters (Units 1-3: daily life, leisure, work)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ¿qué sueles hacer? | what do you usually do? | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 1 title phrase; printed p.2 |
| vérselas con (uno) | to deal with (someone), to face up to (someone) | verb phrase | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | printed p.2 |
| gruñón/a | grumbling, grumpy (person) | adjective | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | printed p.2 |
| de un lado a otro | from one end to the other, back and forth | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.2 |
| o lo que sea | or whatever | phrase | colloquial | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.2 |
| a no ser que | unless | conjunction | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.2-3 |
| ser aficionado a | to be fond of, to like (a hobby/interest) | verb phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.3 |
| estar sujeto a | to be tied down (to a routine/schedule) | verb phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 1, printed p.4 |
| quiéralo o no | whether I like it or not | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.4 |
| ratos de ocio | leisure time | noun phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 2 title vocabulary; printed p.17 |
| tener la suerte de... | to be lucky enough to... | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.17 |
| polideportivo | municipal sports centre | noun | core | — | contemporary | national | national | grammar_reference | n/a | verified | printed p.17 |
| voy por negocios | I'm going on business | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 3, printed p.28 |
| maquinaria agrícola | agricultural machinery | noun phrase | technical | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.28 |
| artesanía | handicrafts | noun | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.28 |
| tocar (me ha tocado a mí) | to be one's turn ("it's my turn") | verb | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Idiomatic use of "tocar" distinct from its literal "to touch" meaning; printed p.28-29 |
| colega | colleague | noun | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.28 |

## Vocabulary — Lesson Topic Clusters (Units 5-7: vacations, housing, directions)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| merecer la pena | to be worth it | verb phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 5, printed p.58 |
| majo/a | nice, likeable | adjective | colloquial | — | contemporary | Spain (explicitly labeled "(Spain)" in the book's own vocabulary box) | regional | grammar_reference | n/a | verified | Book itself marks this as Spain-specific register, distinguishing it from pan-Hispanic synonyms; printed p.58 |
| por mi cuenta | by myself, independently, on my own | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.58 |
| contar/decir maravillas de... | to speak wonderfully of... (people or things) | verb phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.59 |
| falta mucho tiempo | there's still a long way to go (time-wise) | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Impersonal "faltar" construction; printed p.59-60 |
| está lloviendo a cántaros | it's pouring with rain (lit. "raining by the pitcher-full") | idiom | colloquial | — | contemporary | national | national | grammar_reference | n/a | verified | printed p.60 |
| ¡qué lástima! / ¡es una pena! | what a pity!, what a shame! | interjection | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.60 |
| ¡ojalá! | I hope so! (also: "if only!") | interjection | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.60-61 |
| disponible | available | adjective | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 6, printed p.74-77 |
| media pensión / pensión completa | half board / full board (hotel) | noun phrase | technical | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.75 |
| salir (special sense: to cost) | "to come to" (a price) — e.g. "Le saldría a ochenta euros," "¿Cuánto sale?" | verb (idiomatic use) | core | — | contemporary | national | national | grammar_reference | n/a | verified | Special, non-obvious use of "salir" distinct from its basic "to leave/go out" sense, explicitly flagged by the book; printed p.76 |
| inmobiliaria | real-estate/accommodation agency | noun | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.76 |
| cocina americana | open-plan kitchen (fixed real-estate term — NOT literally "American-style kitchen") | noun phrase | technical | — | contemporary | national | national | grammar_reference | n/a | verified | Real-estate-listing jargon; printed p.77 |
| ¿por dónde se va a...? | which way is it to...? (impersonal, very useful direction-asking form) | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Book explicitly calls this "a very useful form of asking the way"; Unit 7, printed p.95 |
| sigan todo recto | go straight on (formal plural command) | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.93-94 |
| estanco | tobacco shop (also sells stamps, a distinctly Spanish institution) | noun | core | — | contemporary | Spain | national | grammar_reference | n/a | verified | printed p.94 |
| no hay de qué | you're welcome, don't mention it | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.95 |

## Vocabulary — Lesson Topic Clusters (Units 8-10: services, consumer, health)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| prefijo | (telephone) dialing code | noun | technical | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 8, printed p.107 |
| marcar | to dial | verb | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.107 |
| abonado | subscriber | noun | technical | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.107 |
| entrega (a domicilio) | (home) delivery | noun phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.108 |
| bolso | handbag | noun | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 9, printed p.120 |
| oferta | special offer | noun | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.120 |
| en efectivo | (in) cash | noun phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.120 |
| beca | scholarship | noun | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.121 |
| tener ganas (de) | to want, to be longing to | verb phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.121 |
| taller de reparaciones | repair shop | noun phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.122 |
| presupuesto | estimate, quote | noun | technical | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.122 |
| estar conforme | to be in agreement | verb phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.122 |
| tener hora | to have an appointment | verb phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 10, printed p.137 |
| torcerse (un tobillo) | to sprain (an ankle) | verb | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.137 |
| esguince | sprain, twist | noun | technical | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.137 |
| hinchazón | swelling | noun | technical | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.137 |
| aún no se me pasa el dolor | the pain still hasn't gone away | phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.139 |
| he cogido un catarro/la gripe | I've caught a cold/the flu | phrase | core | — | contemporary | national (uses "coger" — see dialect warning above) | national | grammar_reference | n/a | verified | printed p.139 |

## Vocabulary — Units 11-12 and Transcript Appendix (society, environment, regional samples)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| medio ambiente | environment | noun phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Unit 11, printed p.147-148 |
| se viene dando un descenso | there has been a (gradual) decrease | phrase | formal | — | contemporary | national | transnational | grammar_reference | n/a | verified | "venir + gerund" construction for gradual change over time; printed p.147 |
| tomar medidas | to adopt/take measures | verb phrase | formal | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.148 |
| a mi juicio | in my opinion/judgment | phrase | formal | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.148 |
| machismo | social attitudes that discriminate against women in favor of men | noun | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | Explicit English gloss given by the book itself; Unit 12, printed p.160 |
| labores domésticas | housework | noun phrase | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.160 |
| bachillerato | Spanish secondary-school qualification/stage | noun | technical | — | contemporary | Spain | national | grammar_reference | n/a | verified | printed p.161-162 |
| tasa de natalidad | birth rate | noun phrase | technical | — | contemporary | national | transnational | grammar_reference | n/a | verified | printed p.163 |
| abrirse camino | idiom: to force/make one's way (figuratively: to succeed against obstacles) | idiom | core | — | contemporary | national | transnational | grammar_reference | n/a | verified | "la mujer se ha venido abriendo camino"; printed p.163 |
| dieta mediterránea | Mediterranean diet — explicitly discussed with real regional contrast (Andalucía/Levante fish-and-vegetable-based diet vs. meseta-central/north high-protein-and-fat diet) | noun phrase | technical | — | contemporary | Spain (regional contrast within Spain) | national | grammar_reference | n/a | verified | Radio-transcript appendix, Unit 10 content; printed p.207-208 — genuine dialect/regional-diet contrast, not just vocabulary |
| (weather-report register sample) | formal meteorological register: "nubosidad parcial," "humedad relativa," "temperaturas extremas," "décima" (tenths of a degree) | register sample | formal | — | contemporary | Santiago, Chile | national (Chile) | grammar_reference | n/a | verified | Radio El Conquistador, Santiago de Chile transcript — confirms this sampler includes genuine Latin American (Chilean) register material, not only Peninsular Spanish; printed p.203 |
| (radio advertisement register sample) | consumer-complaint hotline advertisement register, "La Romántica" radio station | register sample | colloquial-formal | — | contemporary | Veracruz, México | national (Mexico) | grammar_reference | n/a | verified | Transcript appendix, Unit 8 content — second confirmed Latin American (Mexican) regional sample in this book; printed p.205 |

