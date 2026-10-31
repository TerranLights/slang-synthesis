# Camino al español: A Comprehensive Course in Spanish (de Andrés Martínez, Ariza Bruce, Cook, Díez-Bonet, Trippett; Cambridge University Press, 2004)

Source: "Camino al espanol A Comprehensive Course in Spanish.pdf", 451pp. Text-layer PDF, confirmed
clean via `pdftotext` sampling and a full-text dump (front matter, TOC, and multiple unit samples) —
triage classification (TEXT) upheld. Minor accent-rendering quirk: some í/á/ó render as the bare
combining form (e.g. "Dı́ez-Bonet," "tı́mido") rather than the precomposed character — cosmetic only,
does not affect legibility or extraction accuracy.

## Scope note and redundancy assessment

This is a UK-university-authored (Sheffield/Plymouth), 20-unit classroom course built around four
integrated skills (listening/speaking/reading/writing) and explicitly designed by a mixed-nationality
author team (two Peninsular Spanish speakers, one Colombian, two English) to foreground **Peninsular
vs. Latin American contrasts** throughout — stated as a design goal in the Introduction ("We give
specific guidance on the main differences in pronunciation and usage between Peninsular and Latin
American Spanish").

In practice, checking this book's specific dialect-contrast content against the existing corpus
(grep across established/001-099) found that most of the headline contrasts it raises — vosotros vs.
ustedes, coger's regional taboo-avoidance split, seseo/yeísmo, and lexical doublets like
patatas/papas, tomates/jitomates, melocotones/duraznos — are **already present in multiple existing
files** (e.g. 001_colloquial_spanish_latin_america.md, the Rough Guide phrasebooks, 039-041). So this
book's dialect framing, while well-organized, is substantially redundant at the level of individual
facts. What is extracted below is narrowed to the handful of points stated with more specificity or
in a different form here than elsewhere found:
1. A **time-boundary specification** for buenos días/buenas tardes/buenas noches tied to the later
   Spanish lunch/active-day schedule — more precise than the generic greeting-word glosses usually
   given.
2. ¿Dígame? as the conventional **Spain-specific phone-answering greeting**.
3. The **familiar plural imperative** formation split: Spain forms it by replacing infinitive -r with
   -d (hablad, bebed, batid); Latin America has no distinct familiar-plural imperative form and uses
   the polite (ustedes) imperative instead — a grammatical-morphology-level contrast, not just lexical.
4. Argentina named specifically (not just "parts of Latin America") as a locus of coger-avoidance in
   favor of tomar/agarrar — sharper regional specificity than Demystified's "most of Latin America."
5. el estanco as a named, licensed Spain-specific retail institution (tobacco + stamps + newspapers).

Overall: low-to-moderate distinctive value — this book's core contribution (systematic Peninsular/
Latin American contrast) duplicates ground already covered; only the above specifics were new enough
to warrant extraction, so this file is intentionally kept brief.

## Distinctive contrastive/pragmatic points

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| buenos días / buenas tardes / buenas noches (time boundaries) | good morning / good afternoon-evening / good night | greeting phrase set | neutral | high | null | Spain (timing specifics) | regional | grammar_reference | verified | n/a | book specifies: buenas tardes is infrequent before 2pm (late Spanish lunch), buenas noches tends to start after 9pm and can open OR close a night out (Hola, buenas noches = "good evening"; Adiós, buenas noches = "good night") |
| adiós (as a passing greeting) | goodbye (also used as a complete greeting when passing someone) | discourse particle | colloquial | medium | null | null | pan-Hispanic | grammar_reference | verified | n/a | book notes adiós is "very frequently used as a complete greeting," often with a hand wave, when passing someone rather than only at parting |
| ¿Dígame? | Hello? (answering the phone) | discourse formula | neutral/formal | medium | null | Spain | regional | grammar_reference | verified | n/a | book glosses this specifically as "used in Spain when answering the phone"; functionally parallel to but distinct in form from other Hispanophone phone greetings (¿Aló?, ¿Bueno?) attested elsewhere in corpus |
| el estanco | licensed tobacco shop (also sells stamps, postcards, newspapers, magazines) | noun (masc.) | neutral | medium | null | Spain | regional | grammar_reference | verified | n/a | named, licensed retail category specific to Spain; no direct equivalent institution named for Latin America in this source |
| familiar plural imperative: -d suffix (Spain) vs. ustedes-form substitution (Latin America) | forming the "you-all, informal" command | verb morphology (imperative, 2nd person plural) | neutral | high | null | Spain vs. Latin America (split) | regional | grammar_reference | verified | n/a | Spain: infinitive final -r → -d (hablar→hablad, beber→bebed, batir→batid); Latin America: no distinct familiar-plural imperative exists at all — speakers use the formal/polite (ustedes) imperative form instead (hablar→hablen, beber→beban, batir→batan) |
| coger (avoidance in Argentina specifically) | to take/grab (verb avoided in Argentina due to vulgar/sexual secondary sense) | verb | vulgar-avoidant / regional | high | null | Argentina (named specifically) | regional | grammar_reference | verified | n/a | book names Argentina specifically (not just "Latin America" broadly) as a locus where coger is avoided in favor of tomar/agarrar — corroborates and sharpens the same finding already logged from Spanish Demystified (established/099) |
