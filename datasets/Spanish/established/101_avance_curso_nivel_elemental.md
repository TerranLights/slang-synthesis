# Avance: Curso de Español, Nivel Elemental (Equipo Pragma / Verónica Moreno et al., SGEL, Spain)

Source: "Avance Curso de Español Nivel Elemental.pdf", 181pp, Spanish-medium beginner course.

## CRITICAL TEXT-LAYER GOTCHA — triage misclassification found and corrected

The triage classified this PDF as TEXT, and `pdftotext` does extract a text layer from every page.
However, that text layer is **badly OCR-corrupted** throughout: missing/misplaced word-spacing,
character substitutions, and dropped diacritics make it unreliable for extraction (sample from p.52:
"rc-l co NT EI N DosG RA M AT tc AL E s T E D E L VE R B OGU ST A A" for what is actually a clean,
well-laid-out table headed "CONTENIDOS GRAMATICALES: El verbo gustar"). This was confirmed consistent
across samples from pages 5, 10, 50, 51, 100, and 150 — not an isolated glitch. Per this project's
established font-cipher/bad-OCR gotcha pattern, **this file was reclassified as requiring vision
reading** despite its TEXT triage tag. All content below was read directly from `pdftoppm`-rendered
page images (150 dpi), not from the garbled text layer. Transcription Confidence is therefore `n/a`
throughout this file; Vision Reading Confidence is set per entry.

## Scope note and redundancy assessment

Per dispatch guidance, this book was flagged as a Spanish-medium beginner course worth checking for
complementary (not redundant) content against this corpus's existing Spanish-medium series (Uso de la
Gramática, Gramática práctica, etc., established/068-074). The 12-unit grammar progression itself
(ser/estar, present tense, gustar, preterite/imperfect, imperative, future) is standard and was NOT
separately extracted — it duplicates material already covered extensively.

What IS distinctive, and is the flagship finding of this book: **every one of the 12 units ends with
a dedicated "Eso no se dice / Se dice" (That's not said / It's said [this way]) box** — a paired
wrong-form/correct-form feature flagging common learner errors (overwhelmingly English-L1-interference
calques), rendered with the wrong form struck through in the page image. This is a distinctly
different genre from this corpus's existing error-focused reference (033_correct_your_spanish_
blunders.md, a broader standalone blunders book) — here the errors are small, unit-by-unit, and tied
tightly to that unit's specific grammar topic, so they read as a worked diagnostic of exactly which
mistake a learner at that stage of this specific course is expected to make. A targeted grep against
033 and the rest of the corpus for this book's specific wrong-forms (pasear en, gracias para todo,
un medio kilo, por la primera vez, etc.) found no overlap — this error set is additive, not duplicate.
Also distinctive: a compact "confusable verbs" vocabulary note (saber/conocer/encontrar/poder/tocar/
poner) with an explicit usage callout that directly reinforces/explains one of the Unit 12 corrections.

## The 12 "Eso no se dice / Se dice" (learner-error) pairs, by unit

Each row's "Term" is the book's flagged WRONG form (as struck through in the source image); the Gloss
field states what the error is wrong about and gives the corrected form from the same "Se dice" box.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Es no / Martina es una directora | WRONG; correct: "No es" / "Martina es directora" | learner-error pair (negation word order; profession w/o article) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 1, p.26; two separate errors in one box: no-placement before copula, and indefinite article wrongly added before an unmodified profession noun after ser |
| Es bien / En los miércoles voy al cine | WRONG; correct: "Está bien" / "Los miércoles voy al cine" | learner-error pair (ser/estar; preposition+days of week) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 2, p.38; "bien" as a state takes estar not ser; habitual day-of-week adverbials take no preposition in Spanish (unlike English "on Wednesdays") |
| Pasear en... / Isabel es 22 años | WRONG; correct: "Pasear por..." / "Isabel tiene 22 años" | learner-error pair (wrong preposition with pasear; ser/tener for age) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 3, p.50; pasear takes por, not en; age is expressed with tener, not ser (classic English-calque error, "to be X years" vs. "to have X years") |
| Tan mucho / Es depende | WRONG; correct: "Tanto" / "Depende" | learner-error pair (adverb form; verbless impersonal expression) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 4, p.62; "tan mucho" is a redundant/non-standard double intensifier where tanto alone is correct; depende is impersonal and takes no ser |
| Un otro... / Creo no. / Creo sí. | WRONG; correct: "Otro..." / "Creo que no." / "Creo que sí." | learner-error pair (article+otro; missing que after creo) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 5, p.76; otro never takes an indefinite article (un/una) directly before it in Spanish, unlike English "another"; creer que is obligatory before sí/no |
| Después tres horas / Un medio kilo | WRONG; correct: "Después de tres horas" / "Medio kilo" | learner-error pair (missing preposition de; article+medio) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 6, p.88; después requires de before a following noun phrase; medio as a quantifier ("half a kilo") takes no indefinite article |
| Como así / Tengo cumpleaños | WRONG; correct: "Así" / "Es mi cumpleaños" | learner-error pair (redundant como; tener misused for "it's my birthday") | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 7, p.100; como is redundant before así when meaning "like this/so"; "it's my birthday" uses ser (es mi cumpleaños), not tener |
| Serioso / Cinco millón pesetas | WRONG; correct: "Serio" / "Cinco millones de pesetas" | learner-error pair (false suffix derivation; number+currency agreement) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 8, p.112; "serioso" is a fabricated form (English "serious" + Spanish -oso suffix pattern misapplied) — serio is already the correct adjective; millón pluralizes to millones and requires de before the following noun |
| ¿Es posible para mí de...? / ¿Puedo tener una fotocopia? | WRONG; correct: "¿Puedo...?" / "¿Puede(s) hacerme una fotocopia?" | learner-error pair (calqued politeness formula; tener misused for "to get something made") | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 9, p.126; "¿es posible para mí de...?" is a direct English-syntax calque where poder + infinitive is idiomatic; "tener una fotocopia" wrongly uses tener where hacer(me) (lit. "make me") is required for a service request |
| Gracias para todo / Me lavo mis manos | WRONG; correct: "Gracias por todo" / "Me lavo las manos" | learner-error pair (por vs. para; possessive vs. definite article with body parts) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 10, p.138; "thanks for" takes por, not para; reflexive constructions with body parts use the definite article (las manos), not a possessive (mis manos) — classic cross-linguistic body-part/possession contrast |
| Son a las diez. / Hoy me ha llamado Juan y hablaba con él casi una hora. | WRONG; correct: "Son las diez." / "Hoy me ha llamado Juan y he hablado con él casi una hora." | learner-error pair (extraneous "a" with son+time; imperfect misused where present perfect is required) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 11, p.150; stating the current time with son/es takes no preposition a; a recently-completed, bounded action anchored to "today" (hoy) calls for the present perfect (he hablado), not the imperfect (hablaba) |
| Por la primera vez. / Nunca he encontrado personas como así. | WRONG; correct: "Por primera vez." / "Nunca he conocido personas así." | learner-error pair (article+ordinal fixed phrase; encontrar vs. conocer for "to meet [for the first time]"; redundant como) | pedagogical (flagged error) | medium | null | null | pan-Hispanic | grammar_reference | n/a | verified | Unit 12, p.162; "por primera vez" is a fixed phrase that takes no article; conocer (not encontrar) is the correct verb for meeting a person for the first time — directly corroborated by this unit's own vocabulary note below; como is again redundant before así |

## Confusable-verbs vocabulary note (Unit 12, p.157)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| saber | to know how to (do something) / to know facts (dónde, quién, qué, cómo...) | verb | neutral | high | null | null | pan-Hispanic | grammar_reference | n/a | verified | book's own gloss: "(hacer) cosas + dónde, quién, qué, cómo, etcétera" |
| conocer | to know/be acquainted with (people, cities, countries) — including to meet someone for the first time | verb | neutral | high | null | null | pan-Hispanic | grammar_reference | n/a | verified | explicit "¡OJO!" callout in source: "Usamos conocer y no encontrar cuando vemos a alguien por primera vez" (we use conocer, not encontrar, when we see someone for the first time), with worked example "Esta mañana hemos conocido a la nueva monitora de gimnasia" |
| encontrar | to find (things; or to run into a person after searching, or by chance) | verb | neutral | high | null | null | pan-Hispanic | grammar_reference | n/a | verified | explicitly contrasted with conocer — encontrar is for things, or for people already known when run into by chance/after searching, NOT for first-time meetings |
| poder | to be able to / to have the possibility of doing something | verb | neutral | high | null | null | pan-Hispanic | grammar_reference | n/a | verified | |
| tocar | to play (a musical instrument) | verb | neutral | high | null | null | pan-Hispanic | grammar_reference | n/a | verified | |
| poner | to turn on / operate (electrical appliances) | verb | neutral | high | null | null | pan-Hispanic | grammar_reference | n/a | verified | book's gloss: "hacer funcionar aparatos eléctricos" |
