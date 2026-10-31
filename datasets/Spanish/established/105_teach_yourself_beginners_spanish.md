# Spanish — Established Vocabulary/Grammar: *Teach Yourself Beginner's Spanish*

**Source:** Teach Yourself series, *Beginner's Spanish*, 202-page PDF. 21-unit course: Units 1-11
are function-based (greetings, self-introduction, asking where people are from, numbers/addresses,
describing states, family, transport, requests, preferences) and must be studied in order; Units
12-20 are topic-based (houses, leisure, travel, health, shopping, food/drink, practical matters,
weather) and can be taken in any order; Unit 21 is a closing "tying things together" unit.

**Text-layer status — triage classification confirmed but quality caveat required:** `pdftotext`
does extract text throughout (triage's "TEXT" label is technically correct — this is not a
page-image scan), but the embedded text layer is **badly corrupted by an OCR/font-substitution
problem** distinct from and more pervasive than the font-cipher issues already documented
elsewhere in this corpus (034, 091 in this language folder). Specific, consistent failure
patterns observed across many sampled pages: "th" digraphs render as "ú" or "ú/th" hybrids
("the"→"úe," "that"→"úat"), question/exclamation marks at the start of Spanish sentences are
dropped or substituted with stray letters ("¿Dónde..."→"gDónde..." or "a'..."), "ll" and accented
vowels are frequently misrecognized, and line-wrapping is erratic even in plain English
front-matter and table-of-contents text. This is a genuine transcription-reliability problem, not
a one-off artifact — **the entire book's text layer should be treated as low-confidence** and
specific Spanish-language claims below were only included where they could be confidently
reconstructed from the garbled OCR using standard Spanish orthography and real-world knowledge of
Spanish signage/vocabulary conventions (method and reasoning given inline per entry). No vision
re-read was performed for this book, given (a) the severe time cost of re-OCR'ing 202 pages for a
book whose grammar content is overwhelmingly redundant with this corpus's existing basic-grammar
cluster, and (b) the distinctive content found (signage register, dialect note, gender-meaning-
shift pairs) survived reconstruction well enough to extract confidently despite the corruption.

**Redundancy assessment:** Units 1-11's function-based grammar (ser/estar, articles, demonstrative
pronouns, question formation, possession, numbers, basic tenses) and most of Units 12-20's topic
grammar (comparatives, shopping/restaurant/travel phrase drills) duplicate this corpus's extensive
existing beginner-grammar and phrasebook material (001-022, 039-041, 053-058) — **not
re-extracted**. What follows is genuinely distinctive: a public-signage phrase bank (Unit 21, a
register — official/notice Spanish — not well represented elsewhere in this corpus's mostly
conversational phrasebooks), an explicit dialect/register note about regional Spanish and
Catalan/Basque bilingual areas, a telephone-answering convention note, and two gender-meaning-
shift lexical minimal pairs.

**Entry count:** 16 rows — a deliberately small, high-confidence sample given the transcription
reliability caveat above, prioritizing quality/certainty over volume per this corpus's "honest
partial coverage over forced padding" convention.

---

## Public Signage Register (Unit 21, "signs and lettering you see in the street")

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| No tocar / No fumar | Do not touch / No smoking | imperative/sign phrase | formal (public-notice register) | — | contemporary | — | pan-Hispanic | grammar_reference | low | n/a | OCR rendered these cleanly (rare for this source); straightforward prohibition-sign infinitive-as-imperative pattern |
| No aparcar. Llamamos grúa. | "No parking. We call the tow truck." | sign phrase | formal (public-notice register) | — | contemporary | — | Spain (source's own regional focus) | grammar_reference | low | n/a | OCR: "No apaÌrar. Llamamos gÍúa." — reconstructed via standard Spanish orthography (aparcar, grúa); source's own parenthetical gloss confirms "(lit. we call the crane)" for grúa |
| No pisar el césped | Keep off the grass | sign phrase | formal (public-notice register) | — | contemporary | — | pan-Hispanic | grammar_reference | low | n/a | OCR: "No pf6aÍ êl césped" — reconstructed from the standard Spanish park-sign formula and the clearly legible "césped" (grass/lawn) |
| Privado / Prohibido el paso | Private / No entry | sign phrase | formal (public-notice register) | — | contemporary | — | pan-Hispanic | grammar_reference | low | n/a | OCR: "Pt'Nado" / "PrDhibldoêl pâso" — reconstructed with high confidence as standard signage formulas |
| Empujad/Tirad | Push/Pull (on doors) | sign phrase | formal (public-notice register) | — | contemporary | — | Spain (vosotros-form imperative, a peninsular-Spanish marker) | grammar_reference | low | n/a | Notable: uses the vosotros imperative form (Empujad, not Empuje/Empujen), consistent with this being a peninsular-Spanish-focused course; distinguishes it from Latin American signage which would use usted/ustedes forms |
| Introdúzcase la moneda en la ranura. / Prepare la moneda exacta. | "Insert the money in the slot." / "Have the correct/exact change ready." | sign/instruction phrase | formal (public-notice register) | — | contemporary | — | pan-Hispanic | grammar_reference | low | n/a | Vending-machine/pay-phone instruction register; OCR reconstructed via standard orthography |
| Peatón, circule por la izquierda. | "Pedestrian — walk on the left." | sign phrase | formal (public-notice register) | — | contemporary | — | Spain | grammar_reference | low | n/a | Road/path signage for pedestrians; notable as a reversed convention relative to vehicle traffic |
| En batería / En línea (en cordón) | parking side-by-side (perpendicular/angled) / parking end-to-end (parallel) — two named parking-configuration terms | noun phrase (technical/signage) | formal (public-notice register) | — | contemporary | — | Spain | grammar_reference | low | n/a | A genuinely non-obvious technical-signage distinction unlikely to appear in conversational phrasebooks |
| Entrada/Salida, Sin salida, Abierto/Cerrado, No funciona, Se vende | Entrance/Exit, No exit, Open/Closed, Out of order, For sale | sign phrase set | formal (public-notice register) | — | contemporary | — | pan-Hispanic | grammar_reference | low | n/a | Core storefront/facility signage cluster, cleanly OCR'd |
| Cerrado por vacaciones / Cerrado por descanso del personal | Closed for annual holiday / Closed for staff rest day | sign phrase | formal (public-notice register) | — | contemporary | — | Spain | grammar_reference | low | n/a | Reflects Spanish small-business closure conventions (annual vacation closures, staff rest-day closures) distinct from US retail norms |
| Agua potable / (agua no potable) | Drinking water / (non-drinking water) | sign phrase | formal (public-notice register) | — | contemporary | — | pan-Hispanic | grammar_reference | low | n/a | Safety-relevant signage pair |
| Hecho a mano / De artesanía | Hand-made / Craft-made | sign/label phrase | formal (retail-notice register) | — | contemporary | — | pan-Hispanic | grammar_reference | low | n/a | Product-label pair, offered by the source as near-synonyms |
| No se admiten reclamaciones | "Goods are non-returnable." | sign phrase | formal (public-notice/legal register) | — | contemporary | — | Spain | grammar_reference | low | n/a | OCR: "No sê admlts rccfamaclonss" — reconstructed with moderate confidence from standard retail-disclaimer phrasing; genuinely distinctive legal/commercial register not found elsewhere in this corpus's phrasebooks |
| Paso de peatones / Ambulatorio | Pedestrian crossing / Out-patients' clinic | sign phrase / noun | formal (public-notice register) | — | contemporary | — | Spain | grammar_reference | low | n/a | OCR: "Pago d€ p€aton€s" for the first — reconstructed as "Paso de peatones" (the OCR's "Pago" is almost certainly a misread of "Paso"); "Ambulatorio" false-friend-adjacent for English speakers (not "ambulatory" in the medical-mobility sense, but a type of public outpatient clinic) |

## Dialect/Register Note and Lexical Gender-Shift Pairs

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| explicit dialect/register note: Catalán, Basque, and standard Castilian | The book states plainly that Spanish is not the only language heard in Spain — Catalán is heard (and seen on street signs/shop names) in the northeast (Cataluña), Basque further northwest in the Pyrenees — and that the "standard Spanish" taught in the book is Castilian, "fundamentally the language of old Castile," with the clearest ordinary-speaker Spanish said to be heard in the Burgos/Soria region | sociolinguistic note | — | — | contemporary | Spain (Castile/Burgos-Soria vs. Cataluña vs. Basque Country) | national | grammar_reference | low | n/a | A genuinely explicit register/dialect note (scope-guidance item b) — most beginner courses in this corpus simply teach "Spanish" without naming which regional/standard variety or acknowledging co-official regional languages; Unit 21, OCR-reconstructed but the content itself is unambiguous |
| oiga vs. diga/dígame | Telephone-answering convention: oiga (lit. "listen!") is used when trying to get through on the phone or to attract someone's attention (a more polite "psst"); diga/dígame ("speak!") is said when picking up a ringing phone | phrase usage note | core | — | contemporary | Spain | national | grammar_reference | low | n/a | Unit 14; a specific telephone-etiquette convention not captured by this corpus's general phone-vocabulary entries elsewhere |
| la policía vs. el policía | la policía = the police (force/institution); el policía = a policeman (the person) — a gender-determines-meaning minimal pair | noun (gender-meaning-shift pair) | core | — | contemporary | — | pan-Hispanic | grammar_reference | low | n/a | Unit 14; source draws the parallel explicitly with la guía (guidebook/directory) vs. el guía (a male guide, the person) as a second instance of the same pattern — worth flagging for a synthesis pipeline since this is a productive gender-meaning-shift category in Spanish, not an isolated exception |
| incendio vs. fuego vs. hoguera | incendio = an accidental fire/blaze (e.g. a building fire); fuego = fire in general (the more common/everyday word); hoguera = a bonfire — a three-way register/specificity distinction within "fire" vocabulary | noun set (register distinction) | core | — | contemporary | — | pan-Hispanic | grammar_reference | low | n/a | Unit 14, emergency-services vocabulary context (alongside bomberos "firemen," avería "breakdown"); source explicitly flags fuego as "the more common word," positioning incendio as the more formal/specific term used for reporting an actual fire emergency |

**Skipped as redundant (per scope guidance):** Units 1-11's function-based grammar (ser/estar,
articles, demonstratives, possession, basic question formation, numbers), and the bulk of Units
12-20's topic-vocabulary drills (housing, leisure, travel directions, shopping, food/restaurant,
weather) which substantially overlap this corpus's existing beginner-grammar and phrasebook
material. Given this book's severe OCR-corruption problem, no attempt was made to reconstruct
grammar-point explanations in full prose — only self-contained, independently-verifiable
vocabulary/phrase items were extracted.
