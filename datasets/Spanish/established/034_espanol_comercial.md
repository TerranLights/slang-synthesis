# Spanish — Established Vocabulary/Grammar: *Proyecto en... Español Comercial* (full book, all 8 units + Principios Generales + Proyecto Final)

**Source:** Aurora Centellas Rodrigo, *Proyecto en... Español Comercial* (Editorial Edinumen, Madrid —
original edition 1997, this "edición revisada y actualizada" 2001; the course won the INNOVALINGUA
prize at EXPOLINGUA-97). 179 PDF pages, no OCR-countable front/back matter beyond covers. Monolingual
Spanish-for-business-Spanish-learners task-based course, structured as a Principios Generales
intro lesson + 8 thematic units (Unidad 1 Empresa y empresarios · Unidad 2 Productos y mercado ·
Unidad 3 Recursos Humanos · Unidad 4 Márketing, publicidad y distribución · Unidad 5 El sistema
fiscal. Impuestos · Unidad 6 Bancos y finanzas · Unidad 7 Mercados financieros. La Bolsa · Unidad 8
Negociaciones) + Proyecto Final appendix + source-text bibliography + transcripts/answer-key section.

**Vision-reading guard — this source has NO text layer at all (confirmed via `pdftotext`/`pdfimages`:
every page is a single 150dpi grayscale raster image, scanned with VueScan).** Rather than
page-by-page manual vision-reading, the orchestrator rendered all 179 pages to images
(`pdftoppm -gray -r 150`) and ran Tesseract OCR with the Spanish (`spa`) trained-data model
(downloaded for this session since the environment only ships `eng`/`osd`) across the full book,
then read the resulting OCR text in chunks. This is the same underlying operation as vision-reading
(recovering text from raster pages) via a faster, cross-checkable automated pass rather than
describing images one at a time. **OCR quality assessment:** running prose (the course's many
explanatory/reading texts and all "Contenidos Gramaticales" boxes) OCR'd cleanly and consistently —
accented characters (á é í ó ú ñ ¿ ¡) rendered correctly throughout, cross-checked against the same
recurring terms appearing in multiple independent contexts (vocabulary-introduction exercises,
reading texts, and the book's own answer-key/"Claves" section, which independently restates many
term definitions — a strong cross-check the spec recommends). **Garbled/unusable OCR, excluded from
this extraction:** purely graphical pages (the Principios Generales questionnaire's checkbox grid,
several bar-chart/diagram labels in Unidad 6, a stylized word-cloud exercise layout in Unidad 1 and
Unidad 4) — these produced nonsense OCR strings (stray symbols, fragments) that are clearly scanner
noise on graphics, not misread text, and were not treated as content. **No handwritten marginalia
was found or suspected anywhere in this scan** — the source is a clean, unmarked library/publisher
scan with no evidence of a previous owner's annotations; all excluded material is the OCR-on-graphics
noise described above, not handwriting.

**Coverage note.** This is a task-based course with heavy pedagogical padding (fill-in-the-blank
exercises, true/false drills, group-discussion prompts, role-play tasks) — per the coverage rule,
these are skipped wholesale. What's extracted: (1) every explicit vocabulary-introduction list the
course gives per unit (the "Algo de vocabulario sobre..." boxes, cross-checked against the answer-key
section's definitions where available), (2) every "Contenidos Gramaticales" explanation box — this
course gives one per unit, each a genuine grammar explanation with business-register example
sentences, not just a drill, (3) the explicit business-correspondence structural/formulaic content
(letter anatomy, salutation/closing formulae, abbreviations, acta/informe document structures).

**Non-redundant-supplement note.** Every core grammar point this book names (ser/estar, relative
pronouns, future/conditional, subjunctive mood in its many functions, past-tense contrast, por/para)
is already covered in the 15 pre-existing general Spanish files (`001`-`015`). **This file does not
re-derive those paradigms.** What's captured instead, per point, is: (a) the business-register example
sentences themselves (new content — a different author's independent examples per the spec's
non-redundancy guidance), and (b) genuinely finer-grained usage nuances this particular course states
explicitly that a general teaching grammar is less likely to spell out — e.g. the mood-shifts-with-
word-order rule for "quizá/tal vez/probablemente" (indicative before the verb = higher-probability
reading, subjunctive before the verb = lower-probability reading, always indicative if the adverb
follows the verb), "puede que" taking any of the four subjunctive tenses, the subject-type-dependent
split between "estar por + infinitivo" (desire/intention with a personal subject vs. "sin" with a
non-personal one) and "estar para + infinitivo" ("a punto de"), and the unusually thorough
business-example breakdown of "por" vs. "para" into many discrete sub-uses. Where a point is wholly
identical to the general paradigm with no new nuance or example value, it's omitted here rather than
repeated.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| *empresa* | firm, business, enterprise | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Course's own working definition: "unidad económica en donde se combinan los factores básicos... capital, trabajo y recursos naturales... con el objeto de producir e intercambiar bienes y servicios" (Unidad 1). |
| *empresario, -a* | entrepreneur, business owner | noun | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Explicitly contrasted with *directivo* (see below): historically conflated with the capitalist who both risks capital and manages; the course notes the two roles increasingly diverge. |
| *directivo, -a* | manager, executive | noun | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | The salaried professional manager who is delegated the organizing function by the capital-provider; may receive "participación de beneficios" (profit share) per contract. |
| *socio, -a* | (business) partner | noun | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *capital* | capital | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | One of the four classic "factores de producción" the course names throughout (capital, trabajo, recursos naturales, espíritu empresarial). |
| *trabajo* | labor | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *recursos naturales* | natural resources | noun phrase (m.pl.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *espíritu empresarial* | entrepreneurial spirit/drive | noun phrase (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Fourth classic factor of production alongside capital/trabajo/recursos naturales; remunerated via *beneficios* (profits), per the course's own schema. |
| *producción* | production | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *beneficio* | profit | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *lucro* | profit, lucre | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | Answer-key gloss: "crear ganancias." |
| *valor añadido* | value added | noun phrase (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Course's central definitional term for Unidad 1: produced "cuando transforma unos bienes en otros bienes o servicios que tienen un valor más alto que los de partida"; framed as the firm's "fin social." |
| *sociedad mercantil* | commercial company/corporation | noun phrase (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *patrimonio* | (net) assets, estate | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Also recurs in Unidad 5 as a specific tax base (*Impuesto sobre el Patrimonio*). |
| *asesor, -a de empresa* | business consultant/advisor | noun phrase | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | Student-generated example definition in the text: "persona que aconseja a otra emitiendo un dictamen o juicio." |
| *organigrama* | organizational chart | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *valor* | value; price | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *demanda* | demand | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *oferta* | supply; offer | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *consumo* | consumption | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *precio* | price | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *rendimiento* | yield, output, return | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *distribución* | distribution | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *productividad* | productivity | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *mercancía* | merchandise, goods | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *consumidor, -a* | consumer | noun | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *monopolio* | monopoly | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *mayorista* | wholesaler | noun | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Paired with *minorista* and the adverbial phrases below in the answer-key's "mercado" word cluster. |
| *minorista* | retailer | noun | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *al por mayor* | wholesale | adv. phrase | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *al por menor* | retail | adv. phrase | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *proveedor, -a* | supplier | noun | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *competencia* | competition | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Unidad 2 distinguishes *competencia perfecta* vs. *competencia imperfecta* as named concepts. |
| *coste* | cost | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *renta* | income, rent, revenue | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Reused with a distinct tax-specific sense in Unidad 5 (*Impuesto sobre la Renta*). |
| *rentabilidad* | profitability | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *regla de oro (de la productividad)* | "golden rule" (of productivity) | idiom/noun phrase | technical.business | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | Named concept glossed in the answer key as "producir mejor, en menor tiempo y con un coste reducido"; the same "regla de oro" framing recurs for *negociación* in Unidad 8. |
| *contrato* | contract | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *empleo* | employment, job | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *prestaciones* | benefits (employment) | noun (f.pl.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *convenio* | (collective bargaining) agreement | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *currículum vitae* | curriculum vitae, résumé | noun phrase (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Unidad 3's dedicated "Correspondencia comercial" topic is CV structure/conventions. |
| *sueldo* | salary | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *retribución* | remuneration, pay | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *puesto* | position, job | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *plantilla* | staff, payroll (workforce) | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *márketing* | marketing | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Spelled with tilde-k "márketing" throughout this Spain-published source (vs. the unadapted English "marketing" spelling seen elsewhere) — a book-specific orthographic choice worth flagging rather than treating as a typo. |
| *eslogan* | slogan | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *cartel* | poster | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *tríptico* | tri-fold brochure | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *díptico* | bi-fold brochure/flyer | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *folleto* | pamphlet, flyer | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *publirreportaje* | advertorial | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | Compound of *publicidad* + *reportaje*; course lists it among advertising-format vocabulary without further gloss. |
| *patrocinio* | sponsorship | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *cuña (publicitaria)* | radio/TV advertising spot | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | Appears pluralized ("cuñas") in a list of advertising media/formats alongside *folleto*, *exhibidores*. |
| *exhibidor* | (retail) display stand | noun (m.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *tasa* | fee, duty (for a specific government service) | noun (f.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | Explicitly contrasted with *impuesto*: a *tasa* is paid for a specific service received (e.g. driving-license exam, waste collection), unlike a general tax. Course gives this contrast its own dedicated exercise. |
| *impuesto* | tax | noun (m.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | — |
| *tributo* | tax, levy (umbrella term) | noun (m.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | plausible_unverified | — |
| *contribuyente* | taxpayer | noun | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | — |
| *exención* | (tax) exemption | noun (f.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | plausible_unverified | — |
| *elusión (fiscal)* | tax avoidance | noun (f.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | low_confidence | OCR of this specific term was legible but not independently cross-checked elsewhere in the running text. |
| *evasión (fiscal)* | tax evasion | noun (f.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | low_confidence | Same caveat as *elusión* — listed adjacent to it in the same vocabulary box, not independently re-encountered. |
| *deducción* | (tax) deduction | noun (f.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | plausible_unverified | — |
| *gravamen* | levy, tax burden (on a specific item) | noun (m.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | plausible_unverified | — |
| *IVA (Impuesto sobre el Valor Añadido)* | VAT | noun (m., acronym) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | Course explains the cascading-but-netted mechanism explicitly: taxing total sale value at each stage while allowing the seller to reclaim VAT paid on inputs, avoiding the complexity of computing value-added per transaction directly. |
| *IRPF (Impuesto sobre la Renta de las Personas Físicas)* | personal income tax | noun (m., acronym) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | — |
| *Impuesto sobre el Patrimonio* | wealth/net-worth tax | noun phrase (m.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | One of the three named *impuestos directos* alongside IRPF and the corporate-profits tax. |
| *Impuesto sobre Beneficios de Sociedades* | corporate profits tax | noun phrase (m.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | Course states the flat rate applied at the time of writing: "un tipo único del 35% sobre los beneficios obtenidos" — this specific figure is era-bound (1997/2001), not necessarily current. |
| *cotizaciones sociales* | social-security contributions | noun phrase (f.pl.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | Course gives specific contribution-split figures as of writing: employer ≈23.5%, employee ≈4.5% of salary. |
| *ingresos públicos* | public revenue | noun phrase (m.pl.) | technical.fiscal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | Course's own three-way taxonomy: *tributos* (incl. taxes, *tasas*, special contributions), *cotizaciones sociales*, and *otros ingresos* (lottery/gambling revenue, public-enterprise dividends, privatization proceeds, EU structural funds). |
| *activo real* | real asset | noun phrase (m.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Explicitly contrasted with *activo financiero*: an asset with intrinsic value in itself (housing, a car, furniture). |
| *activo financiero* | financial asset | noun phrase (m.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Has little/no intrinsic value but represents a claim (e.g. a banknote, a share, a government bond) — course's own analogy: a banknote "en sí no pasa de ser un trozo de papel." |
| *pasivo financiero* | financial liability | noun phrase (m.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Defined relationally: another party's *activo financiero* held against this economic subject is this subject's *pasivo financiero*. |
| *cheque* | check (banking) | noun (m.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *transferencia (bancaria)* | (bank) transfer | noun (f.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *pagaré* | promissory note | noun (m.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *letra de cambio* | bill of exchange | noun phrase (f.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | Unidad 7's dedicated "Correspondencia comercial" document type. |
| *préstamo hipotecario* | mortgage loan | noun phrase (m.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *tipo de interés* | interest rate | noun phrase (m.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Course explicitly contrasts fixed (*fijo*) vs. variable (*variable*) rate loans, plus a hybrid *préstamo mixto* type, as consumer-facing distinctions. |
| *TAE (Tasa Anual Equivalente)* | APR (annual percentage rate) | noun phrase (f., acronym) | technical.finance | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | Course explicitly recommends asking for the TAE rather than the nominal rate when comparing loan offers — a real consumer-advice register point. |
| *comisión de apertura* | loan origination fee | noun phrase (f.) | technical.finance | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | Flagged by the course as a "trampa del márketing" (marketing trap): a lower advertised rate can be offset by a higher origination fee, netting to the same real cost. |
| *mercado financiero* | financial market | noun phrase (m.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *bolsa* | stock exchange | noun (f.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *acción* | share, stock | noun (f.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *obligación* | bond | noun (f.) | technical.finance | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | plausible_unverified | — |
| *confianza* | trust | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Unidad 8's central term: course's own working definition, "la confianza es el resultado de una relación, no su punto de partida" — framed as the precondition for any negotiation and directly proportional to the stakes/risk involved. |
| *negociación* | negotiation | noun (f.) | technical.business | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *acta* | (meeting) minutes | noun (f.) | technical.business / formal | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Course gives the full structural schema: encabezamiento (place/date/time, attendee list with titles, purpose) → cuerpo (interventions by name, agreements reached, forward-looking objectives) → closing formula "Por no haber más asuntos que tratar" + signatures. |
| *informe* | (business) report | noun (m.) | technical.business / formal | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Course's schema: always addressed upward to a superior, internal-only; structure = título → autor → exposición del tema → valoración/sugerencias/conclusión. |
| *membrete* | letterhead | noun (m.) | formal | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Part of the course's full anatomized business-letter structure (see Grammar points section). |
| *antefirma* | "visto bueno" countersignature line | noun (f.) | formal | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | A reviewing superior's sign-off mark placed above the actual signature on business correspondence — a structural convention not obviously guessable from the word's parts. |
| *Muy señor(es) nuestro(s):* | "Dear Sir(s)," (opening salutation) | formulaic phrase | formal | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | Most formal of three salutation options the course lists (alongside "Muy señor(es) mío(s):" and "Señoras y señores:"). |
| *Le(s) saluda(mos) muy atentamente,* | "Yours sincerely," (closing) | formulaic phrase | formal | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | — |
| *Suyo affmo.* | "Yours affectionately/faithfully" (closing, abbreviated) | formulaic phrase | formal | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | *affmo.* = *afectísimo*; course lists this alongside several other closing registers from fairly neutral to warmer. |
| *s/ref. / n/ref.* | "your ref." / "our ref." | abbreviation | formal | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | *s/ref.* = *su referencia*; *n/ref.* = *nuestra referencia* — standard business-letter header abbreviations. |
| *cte.* | "inst." (of the current month) | abbreviation | formal | — | contemporary (source published 1997/2001) | — | — | grammar_reference | n/a | verified | = *corriente*; seen in the course's own sample letter: "su atta. del 22 del cte." |
| *S.A. / S.L.* | Inc./plc. / LLC-equivalent (corporate suffixes) | abbreviation | formal | — | contemporary (source published 1997/2001) | Spain | national | grammar_reference | n/a | verified | *Sociedad Anónima* / *Sociedad Limitada* — Spain's two standard company-type suffixes. |

## Grammar points

*(Core paradigms for every point below are already established in files `001`-`015`. Only the
business-register example value and genuinely new usage nuances are captured here — see the
non-redundant-supplement note above.)*

### Ser/estar, business-register examples (Unidad 1)

Course organizes ser/estar entirely around business examples rather than the usual general-purpose
set: *ser* for profession ("Ellos son empresarios"), destination/purpose ("La carta es para informar
a los empleados"), passive-of-action with a resulting state framing ("La empresa es gestionada por un
individuo"); *estar* for location, *estar + gerundio* (action in progress: "Los directivos están
pensando en cambiar la organización"), passive-of-state ("La empresa está gestionada de forma
colectiva" — contrasted directly against the *ser* passive above as the same event viewed as an
ongoing condition rather than the action itself), and *estar con* for moral support ("Las secretarias
están con el director"). **Genuinely new nuance:** the course draws an explicit subject-type split for
*estar por/para + infinitivo* not phrased this way in the general files — with a **personal** subject,
*estar por + infinitivo* expresses desire/intention ("tener ganas de"); with a **non-personal**
subject, the same construction instead means roughly "not yet done" ("estar sin": "La empresa está por
ampliar" = the company has not yet expanded). *Estar para + infinitivo* separately means "a punto de"
(about to).

### Relative pronouns, business-register examples (Unidad 1)

Full set (que, el/la/lo cual, quien/quienes, cuyo/a/os/as, cuanto/a/os/as, como, cuando, donde) given
with business examples; the course's own usage notes worth flagging: *el cual* etc. is explicitly
marked as the less-preferred, more formal alternative to *que* ("No conviene abusar de su uso; se
prefiere que"); *cuyo* is marked as typically written/formal register; *cuanto* ("todo lo que") is
marked as *culto o formal*.

### Future, conditional, and probability/hypothesis expressions (Unidad 2)

Beyond the basic future/conditional paradigm, the course gives a genuinely useful **certainty
gradient** for probability adverbs not always spelled out explicitly in general grammars: with
*quizá, tal vez, probablemente, posiblemente* placed **before** the verb, indicative signals a
*higher* degree of probability and subjunctive a *lower* degree ("Probablemente llegan/lleguen a un
acuerdo" — the indicative version reads as more confident); placed **after** the verb, only
indicative is possible. *Puede que* ("it may be that") can govern any of the four subjunctive tenses
(present, perfect, imperfect, pluscuamperfect) with the choice tracking the time-reference of the
possibility, not just the present. Past hypothesis can be expressed with either the conditional
perfect or the pluscuamperfect subjunctive with no meaning difference ("Ellos no habrían
cerrado/hubieran cerrado aquel negocio").

### Causal clauses (Unidad 2)

*Porque* (cause) vs. the corrective double structure *no porque... sino porque* ("not because X but
because Y") is given its own named slot with a business example: "La concentración de la producción
funciona no porque promueva complejidad sino porque promueve la simplicidad y la disciplina" — a
genuinely useful discourse-correction pattern.

### Past-tense contrasts and the impersonal construction (Unidad 3)

Standard pretérito perfecto/indefinido/imperfecto/pluscuamperfecto contrasts, with one nuance worth
flagging: the course gives *pretérito perfecto del verbo ser* a specific evaluative function
("valorar un acontecimiento... reciente": "Las medidas tomadas han sido muy positivas"). The
**impersonal construction** with *se* + singular verb for an unspecified/suppressed subject is framed
specifically through job-listing register ("Se necesita director comercial", "Se requiere
disponibilidad para viajar") — this is a register-identifying pattern (classified-ad/job-posting
Spanish) worth noting for the mechanics-analysis phase.

### Subjunctive with opinion/communication/sense verbs, and with volition/command verbs (Unidad 4)

Two parallel structures given explicit polarity-conditioned rules: (1) *V1 + que + V2*, where V2 is
**indicative** if V1 (a verb of opinion: pensar, opinar, considerar; of communication: decir, contar,
explicar; of the senses: ver, oír, observar) is affirmative, but **subjunctive** if V1 is negated
("Creo que todos están interesados" vs. "No creo que todos estén interesados"). (2) For
volition/command verbs (querer, desear, pedir, exigir, ordenar), V2 is subjunctive when the two
clauses have **different subjects**, but collapses to a plain infinitive when the subject is the
**same** across both clauses ("El consumidor quiere que el comercio sea..." [different subjects] vs.
"Los comerciantes desean evitar la recesión" [same subject, infinitive, no subjunctive needed]).

### Si-conditionals, full tense-pairing (Unidad 4)

Course gives a clean two-row paired table: **probable** condition = "Si + presente/pretérito perfecto
→ presente/futuro/imperativo" in the main clause; **improbable/impossible** condition = "Si +
imperfect subjunctive → simple conditional" or "Si + pluscuamperfect subjunctive → compound
conditional" in the main clause. Business example for the impossible-condition pairing: "Si no hubiera
habido reducción de costes e incremento del valor del consumo, no se habría adquirido una ventaja
competitiva."

### Subjunctive in temporal clauses (Unidad 5)

*Cuando / cada vez que / siempre que / hasta que / mientras* + **indicative** for a habitual/past
action; the identical connectors + **subjunctive** for a future action — the same connector set,
distinguished purely by mood depending on time-reference ("Cuando un ciudadano abone... paga una
tasa" [habitual, indicative] vs. "...pagará una tasa" [future, subjunctive]). *Antes de que* always
takes subjunctive.

### Reported speech / estilo indirecto, verb-tense correspondence table (Unidad 5)

Genuinely useful full correspondence table for shifting direct to indirect speech, organized by the
**tense of the reporting verb**: with a past reporting verb (dijo/decía/había dicho), reported
statements shift present→imperfect and future→conditional in the embedded clause. Separately, for
reported **commands/requests**, the embedded mood is always subjunctive, but the *tense* of that
subjunctive again depends on the reporting verb's tense: present/present-perfect/future reporting
verb → present subjunctive in the embedded clause; past reporting verb → imperfect subjunctive. Fiscal
examples throughout: "'El IVA es un impuesto indirecto' → ...que era un impuesto indirecto";
"'Cumplid como contribuyentes' → ...que cumplamos/cumpliéramos como contribuyentes" (present vs. past
reporting verb, respectively).

### Subjunctive with "aunque" (concessive) (Unidad 7)

*Aunque* + indicative for a known/experienced/verified fact; *aunque* + subjunctive for an
unverified/not-yet-experienced one — same connector, mood alone carries the epistemic distinction
("Aunque conceden un préstamo..." [a known current practice] vs. "Aunque concedan un préstamo..."
[a hypothetical/not-yet-confirmed one]).

### Subjunctive in consecutive clauses (Unidad 7)

*Tanto que / tan + adj. + que / de (tal) modo, forma, manera que* take indicative; *así que, por lo
tanto, por consiguiente, luego* take indicative, but *de ahí que* specifically triggers subjunctive —
flagged because it's the one consecutive connector in the set that doesn't pattern with the others.

### Prepositions de/desde/a/en/para/por, full business-register breakdown (Unidad 8)

The course's final grammar box is an unusually granular preposition-by-preposition breakdown, each
subdivided into many discrete functions with a dedicated business example apiece — far more
fine-grained than a typical general-grammar preposition chapter. Selected nuances beyond the basic
functions (possession, origin, material, time, space — already covered generally): *de* + modal
fixed phrases (*de pie, de golpe, de repente...*); *desde* for a precise starting point without a
paired *hasta* ("Estamos negociando con esa empresa desde septiembre"); *a* for periodicity ("viaja
cinco veces al mes") and for price-as-rate ("El dólar está a ciento cuarenta pesetas" — note: pre-euro
example, dating the source); *para* for an approximate future deadline ("Firmaré el contrato para
junio") and, unusually, three idiomatic *para* + noun/pronoun constructions meaning "despite"
("Para llevar un mes en la compañía, lo hace muy bien"), "of little importance" ("Para lo que ha
servido invertir, mejor no haber hecho nada"), and ironic/genuine positive valuation ("Para buenas
ideas, las de tu jefe"); *por* for substitution/"in place of" ("el subdirector por el director, él
está de viaje") and the medium-of-transport sense ("Enviaron todos los pedidos por tren").

### Business-letter structure (Unidad 1, "Lo que se escribe sobre...")

Full three-part anatomy given explicitly: **Inicio** (membrete, encabezamiento, destinatario, nombre,
dirección, población, fecha, referencia y asunto) → **Cuerpo** (introducción, asunto principal,
asuntos secundarios) → **Final** (despedida, antefirma y firma, posdata, anexos). The course notes
specific formatting conventions tied to each slot (date goes top-right, population name set off from
the rest by a comma; salutation sits left-aligned followed by a colon; closing sits left-aligned
followed by a comma preceding the signature) — this is exactly the kind of explicit formal-register
structural framing the project's business-Spanish cluster is expected to carry.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
