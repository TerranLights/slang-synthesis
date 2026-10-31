# Spanish — Established Vocabulary/Grammar: Gramática didáctica del español (representative-sample extraction)

**Source:** Leonardo Gómez Torrego, *Gramática didáctica del español*, Ediciones SM (Brazilian-
licensed edition, São Paulo, 2005), ISBN 85-7675-066-X. **The metalanguage of this source is Spanish
itself** — a systematic academic/didactic Spanish-for-Spanish-speakers reference grammar, the only
source in this corpus of that kind. Vocabulary glosses below were supplied in English by the
extracting agents in the normal Vocabulary-table format.

**CONFIRMED: no text layer at all** (pure page-images; `pdftotext`/PyMuPDF return empty across the
whole file). Every entry below was vision-read from `pdftoppm`-rendered page images.

**CRITICAL LAYOUT FINDING, empirically verified and held with zero drift across six independent
dispatch chunks:** each PDF page of this file is a **two-printed-page spread** (the scan shows two
physical book pages side by side in one image), not one PDF page = one printed page. The formula
`printed_left = 2×(PDF_page−1)`, `printed_right = printed_left+1` was cross-checked against the
book's own visible footer page numbers repeatedly and held exactly. The PDF's nominal page count of
272 therefore corresponds to a real printed-page count of roughly **540–550** — this is, by a wide
margin, the largest single reference work in this wave (confirmed: the PDF's very last page shows
printed index pages "542–543").

**CONFIRMED MARGINALIA — excluded throughout, not extracted as content:** this specific scanned copy
is a former library book, carrying a recurring institutional ownership stamp ("ESCOLA IRMÃ
ELIZABETH... BIBLIOTECA LUIZ CONRADO DE LORENA E SÁ, SERRA TALHADA-PE") plus a handwritten catalog
number and date, found scattered across the earliest pages and recurring intermittently (confirmed
sightings on printed pages in the 2–7, 131, 137, 162, 179, and 223 range). Applied the extraction
spec's vision-reading marginalia guard throughout — all such stamps/handwriting were excluded and
flagged per-chunk. No content was ever extracted from a stamp or handwritten mark. A separate, benign
scanning artifact (faint double-exposure "ghost" duplicate-scans of a few individual leaves, verified
via contrast-stretching and mirror-flip tests to rule out genuine backside bleed-through) was also
found and excluded on a handful of pages (printed ~202–203, ~415) without any content loss, since a
clean duplicate scan of the same leaf was available immediately adjacent each time.

**SCOPE — this is a deliberate REPRESENTATIVE SAMPLE, not a full-book extraction.** Given this book's
true size (~540–550 printed pages of dense academic grammar — phonetics/orthography, full morphology
by word class, and formal syntax, each covered in a depth no beginner-pedagogical source in this
corpus attempts), literal wall-to-wall vision-reading was judged impractical for this wave. This
follows the same representative-sampling convention already used elsewhere in this project for other
oversized reference works (e.g. the ~1,831-page Diccionario Enciclopédico McGraw-Hill). **Six
PDF-page ranges were deliberately selected to span the book's major structural divisions**, each
extracted AS COMPREHENSIVELY AS THE NORMAL COVERAGE RULE REQUIRES within its own range:

| Part | PDF pages | Printed pages | Content |
|---|---|---|---|
| A | 1–20 | ~2–39 | Intro/Morphology overview (prefixes/suffixes/compounds); El sustantivo through §2.1.5 (género) |
| B | 21–40 | 40–79 | El sustantivo concluded (número, casos especiales); El adjetivo (grado, apócope, posición, ser/estar); Los determinativos (artículo, demostrativos, posesivos) |
| C | 60–80 | 118–159 | Pronombres concluded (relativos, interrogativos, indefinidos); El verbo begins (formas no personales, imperativo, valores pragmáticos de los tiempos, tipología de irregularidad) |
| D | 95–115 | 188–229 | El verbo concluded (perífrasis verbales, pasiva); El adverbio (completo); Las preposiciones (completo) |
| E | 160–180 | 318–359 | Sintaxis: Oraciones y grupos — sustantivas, adjetivas/relativas, adverbiales (hasta concesivas) |
| F | 198–218 | 394–435 | Fonética/Fonología concluded (alófonos, sílaba, diptongos, acentuación, entonación); Ortografía begins (h/b/v/w, extensas familias de homófonos) |

**This sample intentionally leaves real gaps** — most prominently PDF pp.41–59 (rest of determinantes
and start of pronombres), pp.81–94 (verb-irregularity detail), pp.116–159 (bulk of sintaxis on simple
clauses), pp.181–197 (concessive/other remaining clause types), and pp.219–272 (bulk of ortografía
plus all remaining chapters) were not sampled in this wave. A future dispatch wanting denser coverage
of this specific source should target those gaps first.

**Non-redundant-supplement handling (applies across all six parts):** this Spanish corpus's base
established files (001–015) are pedagogical/conversational grammars with essentially no phonetics/
orthography or formal-syntax depth — most of this source's content was treated as genuinely new
rather than redundant. Where a part's content did overlap existing beginner-level paradigms (e.g.
bare article/demonstrative/possessive surface forms, regular conjugation paradigms, basic ser/estar),
each part states explicitly what was skipped as "previously covered, not re-extracted" versus kept
(this source's much deeper terminological, exception-list, and academic-register content, which
beginner workbooks never formalize).

**Notable findings:** a genuinely new derivational-morphology apparatus not found in any prior Spanish
established file (interfijos, parasintéticas, sufijos de significado — confirmed absent via grep
against the full existing corpus before inclusion); a three-way género común/ambiguo/epiceno
classification system; multiple explicit regional/dialectal annotations (Canarias/Hispanoamérica
ustedes; scarce pretérito perfecto in Galicia/Asturias/Canarias/Hispanoamérica; Basque-area
conditional-for-subjunctive substandard usage; León/Galicia -ra-as-pluscuamperfecto dialectalism; a
northwestern-Spain article+apocopated-possessive dialectalism; a Hispanoamérica/southern-
Peninsula/Canary-Islands adverb+possessive feature); two explicit colloquial-register "Norma" box
annotations (*de que* flagged vulgar/dialectal when meaning "when"; *a la que*/*en lo que* flagged
exclusively colloquial).

---

## Spanish — Established Vocabulary/Grammar: Gramática didáctica del español, Capítulo 1 (Introducción, §1.1 Partes de la Gramática / La Morfología) + Capítulo 2 §2.1 El sustantivo (§§2.1.1–2.1.5)

**Source:** Leonardo Gómez Torrego, *Gramática didáctica del español* (Ediciones SM; Brazilian-licensed edition, Ediçoes SM, São Paulo, 2005), ISBN 85-7675-066-X. Metalanguage is Spanish itself (academic/didactic Spanish-for-Spanish-speakers reference grammar). Chunk A of 6 covering PDF pages 1-20 of a 272-PDF-page / ~543-printed-page scan, representative-sampled per orchestrator scope decision (full wall-to-wall extraction of this book is impractical; 6 chunks sample different structural sections).

**No text layer** — pure page-image scan (confirmed via `pdftotext`/PyMuPDF, both return empty). Extracted entirely via vision-reading of pages rendered at 150dpi (`pdftoppm`).

**Page-spread gotcha confirmed and resolved:** each PDF page is a two-printed-page spread, not one PDF page = one printed page. Empirically verified (not assumed) by cross-referencing content against the book's own índice (table of contents) page numbers: PDF page 9's right-hand page reads "La Morfología: objeto de estudio" matching índice entry "1.1.2 ... 16", giving the formula **printed_left = 2×(PDF_page − 1), printed_right = printed_left + 1** for PDF page ≥ 2 (PDF page 1 is the unnumbered cover). This chunk's PDF pages 1-20 therefore correspond to **printed pages ~2-39** (cover/front matter unnumbered through printed page 39).

**Marginalia found and excluded:** this scanned copy is a former Brazilian school library holding (Escola Irmã Elizabeth, Ensino de 1º Grau, SEE-PE; Biblioteca Luiz Conrado de Lorena, Serra Talhada-PE). Printed/typeset library ownership stamps (multiple rectangular ink stamps reading "ESCOLA IRMÁ ELIZABETH," "BIBLIOTECA...," catalog/inscription numbers) appear on PDF pages 2, 3, 6, 7, 19/20 (left margins and corners). A handwritten pen annotation (a small loose mark) appears near the "Presentación" page (PDF page 2, right side) and a handwritten catalog number "14" plus a handwritten date "26.04.06" appear on PDF page 2 (left side, under the CIP block). None of this is the book's own printed content — all excluded from extraction per the vision-reading guard. No handwritten exercise answers or underlining were found in this range (the range is front matter + early expository prose, not drill pages).

**Coverage note — non-redundant-supplement check performed:** searched all 29 existing Spanish `established/` files (grep for `heteronimia`, `parasintéticas`, `interfijo`, `sufijos de significado`, and gender/number coverage generally) before extracting. **Zero hits** for the derivational-morphology apparatus (prefix/suffix typology, interfijos, parasintéticas, heteronimia) — none of the existing pedagogical grammars (Practice Makes Perfect, Madrigal's, Colloquial Spanish, Learning Spanish Like Crazy, Easy Spanish Step by Step, Schaum's, Using Spanish, etc.) cover this material at this depth. **Nothing was skipped as redundant in this chunk** — the entire range (academic morphological theory + the start of the sustantivo chapter, including heteronimia and gender-marking patterns well beyond "basic gender/number rules") is genuinely new depth not present elsewhere in the corpus, confirming the dispatch's prediction. Basic sustantivo examples that overlap trivially with beginner material (e.g. that *libro* is masculine, *mesa* is feminine) are captured only where they illustrate a specific grammatical point (e.g. the género-inherente-vs-dependiente-on-termination distinction), not as standalone redundant drill.

---

### Vocabulary

Because this range is a systematic morphological catalog (prefixes, suffixes, interfijos, compound-word types) rather than a thematic word list, vocabulary entries below are organized as **morphemes/affixes** (the actual lexical/grammatical units the source is teaching) with their most illustrative example word(s) noted in the Notes column, followed by **lexical items** proper from the §2.1 sustantivo chapter (heteronimia pairs, gender-desinence pairs, homonyms, etc.) which are genuine standalone vocabulary.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| *pan* (morfema léxico) | bread (root morpheme) | noun root | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | plausible_unverified | Illustrates lexeme/raíz: common to *panadería, panecillo, empanada* (p.14/§1.1.1.1). |
| in-/im-/i- | 'not' (negation prefix) | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Polysemous: also means 'inside' in *inhumar, innato*. Ex: *infinito, imposible, ilegible* (p.20/§1.1.2.5). |
| archi- | intensifier 'very/extremely' | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *archimillonario* (p.20). |
| extra- | intensifier | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *extraordinario* (p.20). |
| híper- | intensifier | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *hipersensible* (p.20). |
| re- | intensifier (also 'again'/'backward') | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Polysemous: 'volver a' in *releer*, 'hacia atrás' in *recular*, intensifier in *relimpio* (p.19-20/§1.1.2.4-5). |
| requete- | intensifier (colloquial-leaning) | prefix | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *requeteguapo, requetelimpio* (p.20). |
| súper- | intensifier | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *superelegante, superfino* (p.20). |
| des- | reversive/negative prefix | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *deshacer, desenterrar, descomponer* (p.19). Doubled: *desenterrar, descomponer* show prefix stacking. |
| a-/an- | privative 'without' | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *amoral* (p.19); does not change word category (*moral*→*amoral*, both adjectives, p.20). |
| multi- | 'many' (modern category-shifting prefix) | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Modernly appears to turn nouns into adjectives: *productos multiuso, línea multiservicio* (p.20). |
| anti- | 'against' (modern category-shifting prefix) | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *producto antiarrugas, sistema antirrobo* (p.20). |
| post- | 'after' (modern category-shifting prefix) | prefix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *tratamiento postparto, faros antiniebla* (p.20). |
| xeno- | 'foreign' (Greek-origin compositional element) | combining form | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *xenofobia* 'odio a lo extranjero' (p.19/§1.1.2.3). |
| -fobia | 'fear/hatred of' | combining form | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Pairs with *xeno-* → *xenofobia*; source debates whether such Greek/Latin-origin elements are prefixes/suffixes or independent "elementos compositivos" since both halves were autonomous words in Greek/Latin (p.19-20). |
| -algia | 'pain' (Greek-origin element, disputed prefix/suffix status) | combining form | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *lumbalgia, neuralgia* 'dolor nervioso' (p.20). |
| -illa/-illo | diminutive/word-forming suffix (non-derivational-category example) | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *mesilla* (p.19/§1.1.2.4, derivadas class); also reappears as a dialectal diminutive form, see below. |
| -ero/-era | agentive/locative suffix, polysemous | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | *lechero* = 'persona que vende leche' (agent) vs *monedero* = 'lugar donde se guardan monedas' (place) — same suffix, different meaning depending on base (p.21/§1.1.2.8). Cross-checked: also appears in the gentilicio/profession lists on pp.23-24. |
| -ista | agentive/profession suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *cartería → cartero → cartista* chain context (p.19); also profession list *modista, empresario/empresaria* (p.24). |
| -eza | abstract-quality-forming suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Ex. *belleza* (root+tema example, p.18/§1.1.2.1) and *cart-er-ista, bell-eza* derivational chain (p.19). |
| -e (deverbal) | verb→noun suffix, category-changing | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *acusar→acuse, ajustar→ajuste, cesar→cese* (p.21/§1.1.2.8, "obligatorio" class). |
| -ezno/-ezna | non-category-changing suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *lobo→lobezno* (p.21); also listed under "crías de animales" (p.25) as *lobezno, lobezna*. |
| -al (locative/collective) | non-category-changing suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *percha→perchero* uses *-ero*; *-al* ex. *trigal, peral, instrumental* (p.21, 23, 24 — polysemous across lists: lugar, árbol, colectividad). |
| -áceo/-ácea | 'resembling, -ish' (semejanza) | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *grisáceo* (p.21 and again p.25 under "Semejanza"). |
| -ísimo/-ísima | intensifying/superlative potestativo suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *importantísimo*: expressive intensifier, never changes category (p.22/§1.1.2.8). |
| -azo/-aza (apreciativo) | expressive/admirative suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *ojazos*: expresses admiración, not a new concept (p.22). Distinct from the homonymous "golpe" sense of *-azo* (*frenazo*, p.24) and the aumentativo sense (*buenazo*, p.23). |
| -ita/-ito (potestativo) | affective diminutive suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *mesita*: affective value (p.22); also the dialectal-neutral diminutive form listed p.23 (*abuelito, abuelita*). |
| manitas / un manitas | potestativo-turned-obligatorio noun (handyman) | noun | colloquial | — | contemporary (2005) | Spain (unspecified further) | — | grammar_reference | n/a | plausible_unverified | ATENCIÓN box (p.22): a potestativo suffix becomes obligatorio when the whole word gains a genuinely new meaning — *un manitas* = 'a handyman', not just 'small hands'. |
| carota / un carota | potestativo-turned-obligatorio noun (shameless person) | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Same ATENCIÓN box; *un carota* ≈ 'a brazen/shameless person' (augmentative of *cara* 'face' reanalyzed as a fixed insult-noun). |
| manazas / un manazas | potestativo-turned-obligatorio noun (clumsy person) | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Same ATENCIÓN box; *un manazas* ≈ 'a clumsy/heavy-handed person'. |
| -ales (sufijo familiar) | familiar/ironic-register suffix | suffix | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | low_confidence | *vivales, frescales*: irony/disdain with marked familiar register (p.23/§1.1.2.8 "Familiares"). Small print in scan; base-word segmentation read with some uncertainty. |
| -eras (sufijo familiar) | familiar/ironic-register suffix | suffix | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | low_confidence | *guaperas*: same familiar/ironic class as *-ales* (p.23). |
| -olis (sufijo familiar) | familiar/ironic-register suffix | suffix | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | low_confidence | *finolis*: same familiar/ironic class (p.23). |
| -ete/-eta | diminutive (neutral) | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *guapete, guapeta* (p.23). |
| -illo/-illa (diminutivo) | diminutive (neutral) | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *ratillo, chiquilla* (p.23). |
| -uelo/-uela | diminutive (neutral) | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *tontuelo, tontuela* (p.23). |
| -ico/-ica | diminutive, dialectal | suffix | regional | — | contemporary (2005) | Spain/Latin America, zonas dialectales (unspecified which) | regional | grammar_reference | n/a | plausible_unverified | *ratico, ratica* — source explicitly marks this whole group "en zonas dialectales" (p.23), one of the few explicit regional annotations in this range. |
| -ín/-ina (diminutivo) | diminutive, dialectal | suffix | regional | — | contemporary (2005) | zonas dialectales (unspecified) | regional | grammar_reference | n/a | plausible_unverified | *pobrín, tontina* (p.23), same dialectal note as *-ico/-ica*. |
| -iño/-iña | diminutive, dialectal | suffix | regional | — | contemporary (2005) | zonas dialectales (unspecified; this ending is strongly associated with Galician-influenced Spanish, but the source itself does not name the region) | regional | grammar_reference | n/a | plausible_unverified | *pobriño, pobriña* (p.23), same dialectal note. |
| -uco/-uca | diminutive, dialectal | suffix | regional | — | contemporary (2005) | zonas dialectales (unspecified) | regional | grammar_reference | n/a | plausible_unverified | *papeluco, casuca* (p.23), same dialectal note. |
| -azo/-aza (aumentativo) | augmentative | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *buenazo, buenaza* (p.23). |
| -ón/-ona | augmentative | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *grandón, grandona* (p.23). |
| -ote/-ota | augmentative | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *grandote, grandota* (p.23). |
| -ajo/-aja | despective (disdain) | suffix | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *pequeñajo, pequeñaja* (p.23). |
| -ejo/-eja | despective (disdain) | suffix | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | *pillejo, calleja* (p.23). |
| -acho/-astro/-ato/-ica/-orrio/-orro/-ucho/-zuelo/-zuela | despective, low-productivity variants | suffix | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | low_confidence | Source lists these together as "poco productivos": *ricacho, poetastro, cegato, acusica, villorrio, secorro, feúcho, reyezuelo/mujerzuela* (p.23). Grouped as one row for table economy; small print, read with moderate confidence. |
| -ano/-ana, -eno/-ena, -ense, -eño/-eña, -és/-esa, -í, -ín/-ina, -ino/-ina, -ita, -o/-a, -ol/-ola | gentilicio (origin/provenance) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Full paradigm (p.24/§1.1.2.9 "Origen y procedencia"): *asturiano, chileno, almeriense, madrileño, genovés, marroquí, mallorquín, granadino, israelita, sueco, español*. Cross-checked: this gentilicio-suffix set is independently corroborated by regional/dialectal naming patterns seen across other established Spanish files. |
| -ada, -ado, -aje, -al, -ambre, -amen, -amenta, -erío, -ería, -io | colectividad (collective-noun) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *yeguada, profesorado, equipaje, instrumental, pelambre, velamen, cornamenta, caserío, palabrería, gentío* (p.24). |
| -ada, -ado, -al, -ar, -ario, -dromo, -edo, -ería, -ía, -orio, -eda, -era, -ero, -teca | lugar (place) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *embajada, condado, trigal, encinar, campanario, canódromo, viñedo, consejería, peluquería, consultorio, rosaleda, gasolinera, trastero, discoteca* (p.24-25). |
| -a, -ado, -anza, -aje, -ata, -ato, -azgo, -azón, -ción, -da, -do, -dura, -e, -eo, -ería, -ía, -idad, -mento, -miento, -o, -toria | acción o efecto (action/result) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Large paradigm, ex. *marcha, revelado, tardanza, patinaje, caminata, asesinato, hallazgo, quemazón, grabación, salida, silbido, mordedura, ajuste, tapeo, cacería, habladuría, caducidad, ligamento, pensamiento, olvido, dedicatoria* (p.25). |
| -ado, -ato, -ero/-era, -ario/-aria, -azgo, -ía | profesión, dignidad o cargo suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *secretariado, decanato, ingeniero/ingeniera, empresario/empresaria, modista, maestrazgo, alcaldía* (p.25). |
| -dor/-dora, -nte, -or, -ín/-ina, -ero/-era | actor o agente suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *narrador/narradora, traficante, cantor, bailarín/bailarina, panadero/panadera* (p.25). |
| -az, -dad, -ería, -ez, -eza, -ia, -ía, -icia, -idad, -or, -tud, -umbre, -ura | cualidad (quality) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *vivaz, bondad, tontería, idiotez, agudeza, contumacia, majadería, malicia, tenacidad, dulzor, amplitud, mansedumbre, finura* (p.25). |
| -áceo, -ado, -eo, -uzco | semejanza (resemblance) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *grisáceo, rosado, marmóreo, parduzco* (p.25). |
| -ato, -ezno/-ezna, -in(o)/-ina, -ucho | crías de animales (animal-young) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *lobato, lobezno/lobezna, palomino/palomina, aguilucho* (p.25). |
| -esco, -í, -icio, -iego, -íneo, -ista, -il, -ino | relación o pertenencia (relation) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *novelesco, alfonsí, alimenticio, mujeriego, apolíneo, madridista, infantil, canino* (p.25-26). |
| -dera, -dor/-dora | instrumento (instrument) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *regadera, secador/secadora* (p.26). |
| -ada, -azo | golpe o acción violenta suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *pedrada, frenazo* (p.26). |
| -al, -ano, -ero, -o | árbol (tree) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *peral, manzano, membrillero, guindo* (p.26). |
| -oso, -udo | abundancia (abundance) suffixes | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *tramposo, barbudo* (p.26). |
| -avo | partición (fraction) suffix | suffix | technical.math | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *doceavo* (p.26). |
| -ismo | doctrina/sistema/movimiento suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *romanticismo*; also reused for deporte (*atletismo*) and actitud (*egoísmo*) senses (p.26) — same suffix, three distinct meaning categories per the source's own classification. |
| -ancia | actitud (attitude) suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Ex. *vagancia* (p.26). |
| -mente | modalidad (manner-adverb) suffix | suffix | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Ex. *fácilmente* (p.26); flagged in an ATENCIÓN box as ambiguous between derivational suffix and compound-word status, since *-mente* was historically the noun *mente* (p.27). |
| interfijo (general) | meaningless linking segment between root and suffix/prefix | morphological element | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §1.1.2.10 (p.26): ex. *sol-ec-ito, caf-el-ito, pan-ec-illo, te-t-era, chup-et-ón, ris-ot-ada, joven-z-uelo, en-s-anchar*. Sometimes disambiguates homonymy: *solito* (from *solo*) vs *solecito* (diminutive of *sol*); *manotada* vs *manada*; *chupetón* vs *chupón*. |
| palabra compuesta (general) | compound word | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §1.1.2.11-12 (p.27). Subtypes by raíz: no phonetic change (*bocacalle, guardaespaldas, medialuna, sacacorchos, tiovivo, videojuego*); graphic change (*dieciséis*); phonetic change (*agridulce, carricoche, veintiséis, verdinegro*); clitic-incorporating (*entrégaselo*); Greek/Latin-root compounds (*audiómetro, autógrafo, misoginia, xenofobia*); hyphenated co-equal compounds (*físico-químico, teórico-práctico, anglo-egipcio*, where only the second element agrees in concord, e.g. *cuestión teórico-práctica*). |
| sacacorchos / abrelatas / tirachinas | corkscrew / can-opener / slingshot | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §1.1.2.12 (p.27) compound-classification example: verbo+sustantivo type. |
| correveidile | gossip/tattle-tale (lit. 'run-see-and-tell-him') | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Verbo+verbo (+pronombre+conjunción) compound type (p.27); vivid colloquial formation worth flagging for later slang-mechanics comparison. |
| ambidextro | ambidextrous | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Determinativo+adjetivo compound type (p.27). |
| avemaría | Hail Mary | noun/interjection | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Interjección+sustantivo compound type: *¡ave! + María* (p.27). |
| padrenuestro | the Lord's Prayer (Our Father) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | Sustantivo+posesivo compound type (p.27), the only example given in this category. |
| horterada / amiguismo / aperturismo | tacky/tasteless act / cronyism / (political) openness-ism | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.1.2 (p.33): offered as examples of recently-coined sustantivos, illustrating that the sustantivo class is "abierta" (open/productive). *Horterada* and *amiguismo* in particular lean colloquial/pejorative register. |
| joven / anciano / español | young person / elderly person / Spaniard (vs. adjective 'young/elderly/Spanish') | noun or adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.1.3 (p.33): words that function as sustantivo or adjetivo depending on combinatorial context — sustantivo in *los jóvenes, ese anciano, muchos españoles*; adjetivo in *muy joven, tan anciano, muy español*. |
| alameda / pinar / ejército / rebaño | poplar grove / pine wood / army / flock-herd | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.2.2 (p.35) sustantivos colectivos. Only compatible with postposed *numeroso* (*rebaño numeroso*, not *\*alameda numerosa*) when functioning as a true syntactic colectivo. |
| álamo / pino / soldado / oveja | poplar / pine / soldier / sheep | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.2.2 (p.35) sustantivos individuales, paired against the colectivos above. |
| Antonio / Duero / Himalaya / París | (proper names: person / river / mountain range / city) | proper noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.2.3 (p.35) nombres propios — "etiquetas identificativas," individualize without classifying/signifying. |
| la Caballé / la Pardo Bazán | (surnames of famous women, with article) | proper noun | core | — | contemporary (2005) | Spain | national | grammar_reference | n/a | plausible_unverified | Norma box (p.35): exception to the "no article with personal proper nouns" rule — a popular usage for famous people's surnames. *Victoria de los Ángeles* "la Caballé" (opera singer) and "la Pardo Bazán" (novelist Emilia Pardo Bazán) are the implied referents, though the source gives only the bare surnames. |
| hombre / río / montaña / ciudad | man / river / mountain / city | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.2.3 (p.35) sustantivos comunes, contrasted with nombres propios above. |
| la pared / el muro / el ordenador | the wall (fem.) / the wall (masc.) / the computer (masc.) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.1 (p.38): género gramatical inherente with no biological-sex correlate — illustrates género ≠ sexo. |
| la ardilla macho / la ardilla hembra | male squirrel / female squirrel | noun phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.1 (p.38): sexo differentiated lexically (*macho/hembra*) while the sustantivo *ardilla* itself keeps fixed feminine grammatical gender regardless of the animal's actual sex. |
| chico / chica | boy / girl | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.1 (p.38): paradigm case of género dependiente de la terminación (gender determined by the ending, not lexically fixed). |
| casa / margarita (fem. -a) vs. mapa / pijama (masc. -a) | house / daisy vs. map / pyjamas | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.1.5.2 (p.39) table: explicit counter-paradigm showing -a-ending nouns are not always feminine. Cross-checked against the general rule stated immediately above the table (p.38) that "la mayoría" of -a/-o nouns follow gender but "esta correspondencia no es válida en todos los casos." |
| mano / nao (fem. -o) vs. banco / armario (masc. -o) | hand / (archaic) ship vs. bank / wardrobe | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Same table (p.39), -o-ending counter-paradigm. *Nao* is itself a dated/literary term for 'ship,' flagged here as a lexical item worth an `archaic`-leaning usage note even though the source itself doesn't tag it as such. |
| chico-chica / gato-gata / perro-perra | boy-girl / male cat-female cat / male dog-female dog | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): -o/-a desinencia pattern for sex-differentiated animate nouns. |
| nene-nena / jefe-jefa | baby boy-baby girl / male boss-female boss | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): -e/-a desinencia pattern. |
| concejal-concejala / señor-señora | councilman-councilwoman / man-woman (Mr./Mrs.) | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): zero-marked masculine / -a-marked feminine pattern. |
| abad-abadesa / alcalde-alcaldesa / tigre-tigresa | abbot-abbess / mayor (m/f) / tiger-tigress | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): -esa feminine desinencia, one of the "otras desinencias" beyond the basic -o/-a pattern. |
| sacerdote-sacerdotisa / poeta-poetisa / papa-papisa | priest-priestess / poet (m/f) / pope-popess | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): -isa feminine desinencia. |
| héroe-heroína / gallo-gallina / rey-reina / jabalí-jabalina | hero-heroine / rooster-hen / king-queen / wild boar-female wild boar | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): -ina feminine desinencia. |
| emperador-emperatriz / actor-actriz | emperor-empress / actor-actress | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): -triz feminine desinencia. |
| padre-madre / hombre-mujer / varón-hembra | father-mother / man-woman / male-female | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): heteronimia — gender/sex opposition expressed by wholly different word roots rather than a shared desinencia. Explicitly named and defined as a technical term ("Este fenómeno se denomina heteronimia") — this term itself does not appear in any other established Spanish file. |
| padrino-madrina / yerno-nuera | godfather-godmother / son-in-law-daughter-in-law | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39), further heteronimia examples. |
| caballero-dama / buey(toro)-vaca / carnero-oveja | gentleman-lady / ox(bull)-cow / ram-ewe | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39), further heteronimia examples, including an animal-husbandry set. |
| caballo-yegua | horse-mare | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39), heteronimia. |
| cesto-cesta / cubo-cuba / jarro-jarra | basket (large/small) / bucket-vat / jug (large/small) | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): -o/-a opposition repurposed for size/shape distinction rather than sex — masculine member is typically the smaller/narrower referent. |
| manzano-manzana / guindo-guinda / naranjo-naranja | apple tree-apple / sour cherry tree-sour cherry / orange tree-orange | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39): -o/-a opposition repurposed for the tree/fruit distinction (masculine = tree, feminine = fruit) — a highly systematic and productive pattern worth flagging for the mechanics-analysis phase. |
| el/la editorial / el/la frente / el/la corte / el/la orden / el/la cólera / el/la coma | (publishing house/editorial essay) / (front line/forehead) / (court/cutting) / (religious order/command) / (anger/cholera) / (comma/coma) | noun (homonym pair) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.5.2 (p.39, final line of this chunk's range): sustantivos homónimos — same form, unrelated meanings distinguished purely by the grammatical gender of the accompanying determiner. Source explicitly names this "sustantivos homónimos." |

### Grammar points

#### Partes de la Gramática (§1.1.1, p.14-15)

The author lays out his own organizing scheme for the whole book up front: Gramática = Morfología + Sintaxis (+ Fonología/Fonética, included here as a "complemento gramatical" even though strictly it studies phonemes rather than grammar; + Ortografía for the same reason). Semántica (meaning) is explicitly *not* a part of Grammar proper but "impregna" (permeates) it throughout — the author stresses that meaning, form, and function are three distinguishable but interlocking planes, and that a word's semantics (e.g. *libro* denoting a physical object vs. *destrucción* denoting an action/result, because it derives from a transitive verb) can have real syntactic consequences (e.g. *destrucción* can take a complemento agente, *libro* cannot). "Función" in this grammar always means syntactic function (sujeto, complemento directo, etc.), not semantic/thematic roles (paciente, lugar, instrumento) — though the author notes informational categories like tópico/tema/rema can also be treated syntactically.

#### La Morfología: objeto de estudio (§1.1.2, p.16-27) — overview

This is the book's full theoretical apparatus for word-internal structure, presented before any specific word class is discussed. It is considerably more systematic than typical pedagogical-grammar treatments of "word formation."

**Morfemas y sus clases.** A *morfema* (= *monema*) is the minimal meaningful unit a word can be broken into. The *morfema léxico* (= *lexema* = raíz) carries the core shared meaning across a word family (*pan* in *panadería, panecillo, empanada*). The *tema morfológico* is what remains once flexive morphemes (gender/number/person/etc.) are stripped — it may or may not coincide with the raíz (*bell-o*: raíz=tema; *rica-chon-es*: raíz≠tema, since the tema includes the derivational affix *-chon-*). *Morfemas desinenciales/flexivos* mark gender, number, person, tense, mood, aspect; these can have a *marca cero* (zero marking) when a value is unmarked but still oppositional (e.g. singular *niño* has Ø where plural has *-s*). *Morfemas afijales/derivativos* (= afijos) precede or follow the raíz and lack independent existence as free words.

**Dos tipos de Morfología.** (1) *Morfología flexiva*: covers only grammatical meanings of género/número (nouns, adjectives, determinatives, some pronouns) and número/persona/tiempo/modo/aspecto (verbs) — these meanings are called desinencias, and oppositions between them are *flexión*. (2) *Morfología derivativa y compositiva*: covers afijos (prefixes/suffixes beyond flexión) and multi-root compounds. An ATENCIÓN box (p.18) flags that flexión can be marked with a zero form — *niño* has Ø for masculine gender-agreement-triggering and Ø for singular number, each opposed to overt *-s*/*-a* elsewhere in the paradigm.

**Elementos compositivos** (p.19) are components with independent word-status (can stand alone, possibly with minor variation) or that were independent words in Latin/Greek, e.g. *carricoche* (carro+coche) vs. *xenofobia* (xeno='extranjero' + fobia='temer/odiar'). The source explicitly flags unresolved disagreement among grammarians about whether elements like *auto-* in *autocontrol* or *-algia* in *lumbalgia* should count as prefijo/sufijo or as elementos compositivos — when *both* halves of a compound were autonomous Greek/Latin words (e.g. *xeno-* + *-fobia*), the source prefers calling the whole thing "elementos compositivos" rather than prefix+root.

**Clases de palabras por morfemas afijales** (p.19-20): *primitivas* (raíz only, no afijos/elementos compositivos: *pan, coche, leche, mar*); *prefijadas* (prefix + raíz: *infinito, amoral, relanzar, deshacer*); *derivadas* (raíz + suffix: *mesilla, cartero, carterista, belleza*); *compuestas* (two+ raíces: *vierteaguas, aguanieve, guardapolvos, chupatintas*); *parasintéticas*, which the source presents as ambiguous between two readings — either words combining two+ elementos compositivos plus a sufijo at once (*misacantano, barriobajero, quinceañero*), or words where prefix+suffix are added simultaneously such that neither alone would yield a real word (*alma→desalmado*, *viejo→envejecer* — note *\*desalmo* and *\*envejer* don't exist alone). A historical note: a word can have been compound historically but now feels primitive (*antojo* < *ante+oculum* > *ant(e)ojo*, now felt as unanalyzable).

**Los prefijos** (§1.1.2.5, p.20): afijos preceding the raíz/tema, lacking autonomy. Can stack (*des-en-terrar, des-com-poner*). Generally do *not* change word category (*enterrar*[verb]→*desenterrar*[verb]; *juicio*[noun]→*prejuicio*[noun]; *moral*[adj]→*amoral/inmoral*[adj]) — but the source flags a modern exception: *multi-, anti-, post-* appear to convert nouns into adjectives (*producto multiuso, sistema antirrobo, tratamiento postparto*). Prefixes often add genuinely new meaning (*re-* = 'volver a' in *releer*, 'hacia atrás' in *recular*, pure intensifier in *relimpio*) — i.e. prefixes can be polysemous even within the same form. Some prefixes attach only to bound roots that never occur free (*recular* ⇐ *\*cular*; *inhumar* ⇐ *\*humar*; *impertérrito* ⇐ *\*térrito*; *inmersión* ⇐ *\*mersión*) — these bound roots are recoverable only by comparing cognate family members (*recular→culo*, *inhumar→humus*, *impertérrito→terror*, *inmersión→emerger*).

**Los sufijos** (§1.1.2.6-9, p.21-26): afijos following the raíz/tema, sometimes chaining (*ros-al-eda, españ-ol-ada, cristi-an-dad, informat-iza-ción*). Two broad classes: (A) **sufijos de significado gramatical** — these are simply the non-finite verb-form markers: infinitive *-r* (*ama-r*), gerundio *-ndo* (*ama-ndo*), participio *-do* (*ama-do*); purely aspectual, no lexical content of their own. (B) **sufijos de significado no gramatical**, which subdivide into:
  - *Obligatorios*: create a genuinely new concept distinct from the raíz's own meaning (*lechero* = 'persona que vende leche', not just 'related to leche'; same suffix *-ero* yields 'lugar' in *monedero*). Often change category (*-e* turns verbs into nouns: *acusar→acuse*), but not always (*lobo→lobezno*, *percha→perchero*, *rosa→rosal*, *gris→grisáceo* keep category).
  - *Potestativos* (= apreciativos): don't create new concepts, only add affective/expressive nuance to the base meaning, and *never* change category. Subtypes: **diminutivos** (affective — *abuelita* shows cariño; or apelativo/conative, aimed at moving the listener — *momentito* signals impatience-avoidance, *limosnita* tries to move the interlocutor to pity); **aumentativos** (aumento/admiración/engrandecimiento, sometimes mixed with rechazo/desprecio/cariño); **despectivos** (always desprecio, sometimes mixed with affection); **familiares** (irony/disdain with a markedly colloquial/familiar register — distinguished from ordinary despectivos by that register marking specifically); **superlativos** (cross-referenced to the adjective chapter, §2.2.3, outside this chunk's range). An ATENCIÓN box (p.23) notes a potestativo suffix can become *obligatorio* when the resulting whole word takes on a genuinely new, non-compositional meaning: *manitas→un manitas* ('handyman'), *carota→un carota*, *manazas→un manazas* are no longer "just" affective diminutive/augmentative forms of *manos/cara* — they denote fixed social-type nouns.

**Significado de los sufijos obligatorios** (§1.1.2.9, p.24-26) catalogs, by semantic category, the (very large) set of obligatorio-suffix families: origen/procedencia (gentilicios), colectividad, lugar, acción o efecto, profesión/dignidad/cargo, actor o agente, cualidad, semejanza, crías de animales, relación o pertenencia, instrumento, golpe/acción violenta (real or metaphorical), árbol, abundancia, partición, doctrina/sistema/movimiento, deporte, actitud, modalidad. Multiple categories reuse the same surface suffix with different meanings depending on the base (e.g. *-ismo* covers doctrina/movimiento *romanticismo*, deporte *atletismo*, and actitud *egoísmo* as three distinct senses of one suffix; *-azo* covers golpe *frenazo*, aumentativo *buenazo*, and the unrelated apreciativo-intensifier sense *ojazos* seen earlier). An ATENCIÓN box (p.27) flags *-mente* as genuinely ambiguous in status — it can be analyzed either as a fully grammaticalized derivational suffix (modalidad) or as a compound-word second element (since *mente* was historically an independent noun), and such words keep stress/intensity on *each* component (*fácilmente* has two stress peaks), unlike ordinary suffixation.

#### Interfijos (§1.1.2.10, p.26)

Occasionally, meaningless linking segments appear between a raíz and a sufijo, or (more rarely) between a prefijo and a raíz within the tema. These are not morphemes (they carry no meaning of their own in most cases) but rather "elementos de enlace dentro de la palabra": *sol-ec-ito, cafe-l-ito, pan-ec-illo, te-t-era, chup-et-ón, ris-ot-ada, joven-z-uelo, en-s-anchar*. In some cases the interfijo's presence vs. absence disambiguates otherwise-homonymous derivations: *solito* (← *solo* 'alone') vs. *solecito* (← *sol* 'sun', diminutive); *manotada* vs. *manada*; *chupetón* vs. *chupón*.

#### Las palabras compuestas: clasificación por raíces y por categorías (§1.1.2.11-12, p.27)

By raíz type: (1) two+ Spanish raíces with no phonetic change beyond unstressing the first element (*bocacalle, guardaespaldas, medialuna, sacacorchos, tiovivo, videojuego*); (2) compounds with a graphic change (*diez+y+seis→dieciséis*); (3) compounds with phonetic change beyond unstressing (*agridulce, carricoche, veintiséis, verdinegro*); (4) compounds where the first element stays stressed — these are verb+clitic-pronoun fusions (*entrega+se+lo→entrégaselo*); (5) compounds from two roots that were independent words in Latin/Greek, which typically undergo adaptation changes (*audiómetro, autógrafo, misoginia, xenofobia*); (6) hyphenated compounds of Spanish lexemes that each keep their own stressed syllable, written with a hyphen, where **only the second component agrees in concord** (*cuestión teórico-práctica*, not *\*teórica-práctica*): *físico-químico, teórico-práctico, anglo-egipcio*.

By syntactic category of the two components, the source gives an extensive worked taxonomy (verbo+sustantivo: *sacacorchos, abrelatas, tirachinas, correcalles, tirachinas*; sustantivo+sustantivo: *bocacalle, bocamanga, carricoche, motobomba*; sustantivo+adjetivo: *tiovivo, caradura, pelirrojo, cornicorto, vinagre*; adjetivo+adjetivo: *agridulce, verdinegro*; verbo+verbo, with or without a conjunction: *correveidile, vaivén, comecome*; cardinal+cardinal: *dieciséis, veintidós*; cardinal+sustantivo: *milhojas, ciempiés*; adverbio+sustantivo/adjetivo: *biempensante, maleducado, bienhechor*; adverbio+verbo: *maleducar, malmeter, maldecir*; preposición+sustantivo+adjetivo: *enhorabuena*; preposición+pronombre+adjetivo: *ensimismar* (← en-sí-mismo); determinativo+adjetivo: *ambidextro*; adjetivo+sustantivo: *medialuna, mediodía, altamar, salvoconducto, altavoz*; interjección+sustantivo: *avemaría*; sustantivo+posesivo: *padrenuestro*).

#### El sustantivo: definición tradicional y sus límites (§2.1.1.1, p.32)

The traditional semantic definition (a word designating persons, animals, or things with independent existence, real or abstract) is presented and then explicitly critiqued: "cosas" is too vague, since a sustantivo can denote objetos físicos (*libro, mesa*), cualidades (*belleza, caridad*), acciones (*movimiento, agitación*), situaciones/propiedades (*imaginación, creencia*), sentimientos (*alegría, odio*), tiempo (*mediodía, semana*), relación (*amigo, vecino*), número (*docena, centenar*) — and adjectives/verbs can also denote qualities/actions, so semantics alone can't cleanly separate word classes. The author concludes purely formal (combinatorial) criteria are needed instead.

#### Características combinatorias del sustantivo (§2.1.1.2, p.33)

Formal diagnostics: a sustantivo (1) can combine with the article and other determinativos (*la mesa, mi libro, ese movimiento, mucha belleza*); (2) can always combine with the full (non-apocopated) cuantificador forms *mucho/mucha/muchos/muchas, cuanto, tanto, cuánto* (*mucho daño, tantos insultos, cuánta gente*) — by contrast adjectives and most adverbs only take the apocopated forms *muy, tan, cuán* (*muy bueno, tan seguro, ¡cuán simpático!*; *muy cerca, tan lejos, ¡cuán lejos!* — never *\*mucho rápido, \*cuánto lejos*). Sustantivos are always tonic words and belong to an open class — newly coined words like *horterada, amiguismo, aperturismo* are themselves sustantivos.

#### Palabras que pueden funcionar como sustantivos y como adjetivos (§2.1.1.3, p.33)

Some words (*joven, anciano, español*) are sustantivo or adjetivo purely depending on their combinatorial context in a given sentence, not on any inherent lexical specification: sustantivo in *los jóvenes, ese anciano, muchos españoles*; adjetivo in *muy joven, tan anciano, muy español*. The combinatorial diagnostics above are what decide the category, not a fixed lexical listing.

#### Clases de sustantivos (1): abstractos/concretos, individuales/colectivos (§2.1.2.1-2, p.34-35)

Abstractos/concretos is flagged as a "lógico-filosófica" classification of limited grammatical use — it fails to classify words like *viento, semana, luz* cleanly. Individuales/colectivos: traditionally semantic (*alameda, pinar, ejército, rebaño* = colectivos; *álamo, pino, soldado, oveja* = individuales), but the source notes only sustantivos that can combine *in the singular* with postposed *numeroso* count as colectivos syntactically (*rebaño numeroso*, not *\*alameda numerosa* / *\*pinar numeroso*) — the determinative/prenominal use of *numeroso* ("abundante," as in *numerosas familias*) is a different, unrelated construction.

#### Sustantivos comunes y nombres propios (§2.1.2.3, p.35)

Nombres propios individualize a referent without classifying/signifying it — they function as identifying labels (*Antonio, Duero, Himalaya, París*: covering personal names, rivers, mountain ranges, cities). A **Norma** box states the general rule that Spanish personal proper names do not combine with an article (*\*la María, \*el Manolo, \*la Rocío* are "vulgar"/non-standard), with two carve-outs: (a) when the proper name is itself further specified/restricted (*el Manolo del otro día*, *la Rocío de la que te hablé*), the article becomes necessary; (b) a popular usage allows the article before certain famous people's surnames (*la Caballé, la Pardo Bazán*). Nombres propios also cover apodos/alias, antonomasia-based common-noun-as-proper-noun uses (*El Salvador* for Jesucristo), topónimos, named rivers/seas, titles of works, and institution/company names. Sustantivos comunes are everything else, not individualizing a referent (*hombre, río, montaña, ciudad*).

#### Sustantivos animados y no animados (§2.1.2.4, p.35)

A purely semantic distinction (living referents vs. non-living) that nonetheless has real syntactic consequences: certain verbs take a complemento directo with an animate subject but a complemento indirecto with an inanimate one, illustrated with *asustar*: *Juan asustó a María → la asustó* (CD, animate causer) vs. *A María le asusta la vida* (CI, inanimate causer) — i.e. a kind of differential-object-marking-adjacent pattern keyed to the animacy of the *causer*, not the affected party.

#### Sustantivos contables y no contables (§2.1.3, p.36)

Contables: compatible with cardinal numerals (*tres libros*), can pluralize freely, combine with plural cuantificadores without lexical-meaning shift. No contables: reject cardinal numerals and plain pluralization (*\*dos petróleos, \*varias platas, \*tres aguas* are ungrammatical) *unless* reinterpreted as naming distinct classes/varieties (*Estos dos petróleos son los mejores* ≈ "these two kinds of petroleum"); combine with *mucho, poco, bastante, tanto* but not their plurals (*mucha fe*, not *\*muchas fes*; *mucha arena*, not *\*muchas arenas*). Functionally, no-contables can appear as a bare complemento directo (*Quiero agua*, but not *\*Quiero pájaro*) and as the bare subject of pasiva refleja / *ser*+participio constructions without a determinative (*Se encontró oro* vs. *\*Se encontró libro*; *Fue encontrado carbón* vs. *\*Fue encontrada carpeta*) — singular contables lack this behavior.

#### El sustantivo desde el punto de vista funcional (§2.1.4, p.37)

The sustantivo (or its larger group) functions as **núcleo of a grupo nominal** — the element toward which determinativos, adjectives, prepositional/clausal modifiers all converge (*El libro pequeño de Juan que leíste ayer*). It can also independently fill the sentence-level functions of sujeto, complemento directo, complemento indirecto, and complemento de régimen (*Me apetece agua* / *Prefiero pan* / *Di el vaso a Mario* / *Hablaron de política*); complemento circunstancial, with or without a preposition (*Te veré el jueves* / *Lo comía con ansia*; *Estuve en casa* / *Lo hizo sin ganas*); complemento agente (of a participle or of another sustantivo), introduced by *por* or *de* (*Odiado por/de los hombres*; *La entrega de los rehenes por los secuestradores*); and atributo (*Juan es médico*). Finally a sustantivo can complement another sustantivo (directly, as an aposición — *Ciudad dormitorio* — or via a preposition — *La casa de Juan*), an adjective (*Lleno de satisfacción*), or an adverb (*Cerca de casa*).

#### El género en el sustantivo (§2.1.5.1-2, p.38-39)

Género is a grammatical feature, sexo a biological one; they frequently diverge. Inanimate-referent nouns have a fixed, arbitrary "género inherente" with no sex correlate (*la pared* fem., *el muro* masc., *el ordenador* masc. — none of these designate sexed entities), manifested only via concordance with determinatives/adjectives, never via the noun's own ending. Some sex-differentiated animate referents are nonetheless named by a single gender-invariant noun, with sex expressed lexically instead (*la ardilla macho / la ardilla hembra* — *ardilla* 'squirrel' stays grammatically feminine regardless of the animal's actual sex). Other animate nouns instead have "género dependiente de la terminación" (*chico/chica*), where the ending itself carries the gender distinction. The book immediately qualifies the popular -o=masc./-a=fem. heuristic with a counter-paradigm table: *casa, margarita* (fem., end in -a) vs. *mapa, pijama* (masc., end in -a); *mano, nao* (fem., end in -o) vs. *banco, armario* (masc., end in -o) — "esta correspondencia no es válida en todos los casos." Beyond -o/-a, other feminine desinencias are given: *-esa* (*abad-abadesa, alcalde-alcaldesa, tigre-tigresa*), *-isa* (*sacerdote-sacerdotisa, poeta-poetisa, papa-papisa*), *-ina* (*héroe-heroína, gallo-gallina, rey-reina, jabalí-jabalina*), *-triz* (*emperador-emperatriz, actor-actriz*). Separately, **heteronimia** is named and defined as a distinct phenomenon from desinencial marking: sex/gender opposition realized through *entirely different lexical roots* rather than a shared base plus differing endings (*padre-madre, hombre-mujer, varón-hembra, padrino-madrina, caballero-dama, caballo-yegua, yerno-nuera, buey(toro)-vaca, carnero-oveja*). The -o/-a opposition is also shown to be reused, on certain inanimate nouns, for two unrelated semantic distinctions rather than sex: size/shape (*cesto-cesta, cubo-cuba, jarro-jarra*, masculine typically smaller/narrower) and tree-vs-fruit (*manzano-manzana, guindo-guinda, naranjo-naranja*, masculine = tree). Finally, this range ends on **sustantivos homónimos**: words with identical form but unrelated meanings distinguished purely by which grammatical gender co-occurs with them (*el/la editorial, el/la frente, el/la corte, el/la orden, el/la cólera, el/la coma*) — the source gives the bare pairs without glossing the individual meanings, so readers must supply the sense split themselves (e.g. *el frente* 'battle front' vs. *la frente* 'forehead'; *el cólera* 'the disease cholera' vs. *la cólera* 'anger'; *el coma* 'a medical coma' vs. *la coma* 'the punctuation comma').

---


---

## Spanish — Established Vocabulary/Grammar: Gramática didáctica del español, Chunk B (PDF pp.21-40 / printed pp.40-79)

**Source:** Leonardo Gómez Torrego, *Gramática didáctica del español*, Ediciones SM (Brazilian-licensed edition, São Paulo, 2005), ISBN 85-7675-066-X. PDF pages 21-40, corresponding to printed pages 40-79 per the formula `printed_left = 2×(PDF_page−1)`, `printed_right = printed_left+1`, verified against the book's own footer page numbers (footer "78" visible on PDF page 40's left half, matching the formula exactly). This is chunk B of a 6-chunk representative sample of this ~540-page academic reference grammar; chunk A (PDF 1-20, printed ~2-39) covered §1.1 (Morfología overview) through §2.1.5 (El género en el sustantivo, ending p.39). This chunk picks up immediately after at §2.1.6 and continues through §2.1.7-8 (número del sustantivo), all of §2.2 (El adjetivo), and §2.3.1-6 of §2.3 (Los determinativos: terminología, artículo, demostrativos, posesivos), ending partway through the determinativos chapter (cuyo, p.79). Chunk C (PDF 60-80) picks up later at §2.4.8-13 (pronoun subsections).

**Vision-read from a scan, no text layer** — `pdftoppm -r 150` render, each PDF page a two-printed-page spread, both halves read as separate printed pages.

**Marginalia found and excluded:** the confirmed institutional library ownership stamp — "ESCOLA IRMÃ ELIZABETH... BIBLIOTECA LUIZ CONRADO DE LORENA E SÁ, SERRA TALHADA-PE" plus an accompanying catalog-number stamp — appears in the margin of PDF page 36 (printed p.70/71, bottom-right area). It is clearly a rubber-stamped institutional mark, not book content, and is excluded entirely from this extraction. No handwritten marginalia (pencil/pen annotation) was found anywhere in this chunk's range. "Ghost" bleed-through of adjacent-page text showing faintly on otherwise-blank section-divider pages (PDF pp.25, 33 left halves) was also encountered — these are scanning/paper-translucency artifacts, not marginalia, and are likewise not extracted as content (the two true section-divider pages, printed p.49 "El adjetivo" and printed p.65 "Los determinativos," contributed only their chapter titles, already captured in the structural outline above).

**Non-redundant-supplement scope decision.** This Spanish corpus already has 15 base established files; basic paradigms (article/demonstrative/possessive surface forms: *el/la/los/las*, *este/ese/aquel*, *mi/tu/su*, comparative *más/menos/tan*, basic ser/estar-with-adjective distinction) are virtually certain to already be covered by the pedagogical grammars (005, 014, etc.) and are **not re-extracted as bare paradigms** — only the deeper/more systematic material this academic grammar adds is captured in full:
- The three-way **sustantivo común/ambiguo/epiceno-en-cuanto-al-género** classification (not a typical pedagogical-grammar topic).
- The full, systematic **número del sustantivo** rule-set (plural formation by ending type, extranjerismos, sustantivos latinos, *singularia/pluralia tantum*, prescriptive-norm boxes) — kept in full as more exhaustive than a typical textbook's treatment.
- **Grado del adjetivo**: the full comparativo/superlativo sintético system (*mejor/peor/mayor/menor/inferior/superior*; *óptimo/pésimo/mínimo/máximo/ínfimo/supremo*) with explicit prescriptive norms (*\*más mayor* incorrect) — kept, this systematic synthetic-form treatment with its own prescriptive apparatus is unlikely to be matched by a pedagogical grammar.
- **Adjetivo + ser/estar**: this source's unusually extensive catalog of meaning-changing adjective pairs is kept in full even though basic ser/estar-with-adjectives is already covered elsewhere in this corpus (006, 013g's leísmo-adjacent notes, 015's own *ser*/*estar* catalog per its established file) — see note under that grammar point for the specific overlap call.
- The book's own **determinativo vs. adjetivo / determinante / actualizador vs. modificador terminology debate** (§2.3 Terminología) — purely this author's theoretical apparatus, not found in pedagogical grammars, kept in full.
- Apócope rules, posición-del-adjetivo meaning shifts, artículo's enfático/posesivo/interrogative-equivalent uses, demostrativo combinatoria, and posesivo apocopado/pleno functional split (actualizador vs. modificador vs. atributo) and *cuyo* prescriptive norms — all kept, these go well beyond the "here are the possessive pronoun forms" level of a pedagogical grammar.
- Bare morphological paradigms (list of article forms, demonstrative forms, possessive forms by person) are named but not exhaustively re-tabulated as vocabulary rows, since they duplicate material any basic Spanish reference already has.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| el/la estudiante / el/la coleccionista / el/la artista / el/la pianista / el/la telefonista / el/la comparsa / el/la burócrata / el/la logopeda / el/la paciente / el/la cantante / el/la amante | (student / collector / artist / pianist / telephone operator / extra-actor / bureaucrat / speech therapist / patient / singer / lover) | noun (comunes en cuanto al género) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.6.1 (p.40-41): nouns lacking a dedicated gender form — sex is marked only via the article/determinative, not the noun's own ending. Source explicitly rejects "género común" as a name, prefers "comunes en cuanto al género." |
| jefe-jefa / nene-nena / sastre-sastra / el/la testigo / el/la bachiller / el/la soprano / el/la contralto / el/la conserje / el/la mártir | (boss / baby / tailor + feminine-marked counterparts; witness / high-school graduate / soprano / contralto / caretaker / martyr, gender-invariant) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.6.1 (p.40): mixed set — some -e-ending nouns do have a dedicated feminine (jefa), others stay invariant (bachiller never desdobla). |
| ministro-ministra / notario-notaria / arquitecto-arquitecta / ingeniero-ingeniera / filólogo-filóloga / médico-médica / abogado-abogada / perito-perita | (minister/notary/architect/engineer/philologist/doctor/lawyer/expert-appraiser, title/profession pairs) | noun pair | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.6.1 (p.40): title/profession nouns that have "modernamente" split into distinct masc./fem. forms, having formerly been comunes en cuanto al género — an explicit language-change-in-progress note. The RAE is cited (ATENCIÓN box) as recognizing *modista/modisto* as a reverse case: traditionally common-gender, now also split, with the masc. form *modisto* flagged as an exception to the general -ista = comunes rule. |
| el/la juez / jueza | (judge, m./f.) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.6.1 ATENCIÓN (p.41): RAE registers *juez* as común en cuanto al género but also accepts the innovated feminine *jueza*. |
| el/la mar / azúcar blanquillo/blanquilla / el/la armazón / el/la acné / el/la maratón / el arte (dórico) → las bellas artes | (sea; a sugar term; framework/structure; acne; marathon; "art" shifting masc.→fem. between singular and plural) | noun (ambiguos en cuanto al género) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.6.2 (p.41): nouns taking masculine or feminine determinatives/adjectives interchangeably with no semantic difference (register/style differences aside) — a genuinely distinct phenomenon from común-en-cuanto-al-género, since these nouns DO have inherent gender, it's just unstable. *el arte dórico* vs. *las bellas artes* shows the ambiguity can also split by number. |
| gorila / rata / víbora / cuervo / elefante / cría (animal) | (gorilla / rat / viper / crow / elephant / young animal) | noun (epiceno) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.6.3 (p.41): inherently masc. or fem. nouns for animals/people that don't distinguish actual sex (*el gorila* is grammatically masc. regardless of the animal's sex). Source stresses "epiceno" names a semantic trait of the noun, not a grammatical gender — contra "gramática tradicional." |
| pastel-pasteles / canon-cánones / altar-altares / compás-compases / autobús-autobuses / carcax-carcaxes / tesis-tesis / tórax-tórax / convoy-convoyes / rey-reyes / ley-leyes / buey-bueyes / ay-ayes / virrey-virreyes / jersey-jerséis / paipay-paipáis / rentoy-rentóis | (pastry/canon/altar/compass-pl/bus/quiver + plurals; thesis/thorax invariant; convoy/king/law/ox/"ouch"/viceroy-pl; jersey/fan/card-game-term with exceptional -éis plural) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.7.2 (p.42-43): systematic plural-formation rules by final segment — consonant-final take -es; agudo -s/-x take -es; llano/esdrújulo -s/-x are invariant; -y takes -es converting y→consonant, except jersey/paipay/rentoy keep the y and take -es as -éis. |
| casa-casas / coche-coches / amigo-amigos / sofá-sofás / café-cafés / buró-burós / jabalí-jabalíes / alhelí-alhelíes / israelí-israelíes / esquí-esquís / bisturí-bisturís / hindú-hindús(o hindúes) / zulú-zulús(o zulúes) / menú-menús / vermú-vermús / champú-champús / iglú-iglús(o iglúes) | (house/car/friend; sofa/café/bureau — stressed á/é/ó take -s; wild.boar/mallow/israeli — stressed -í traditionally -es, increasingly -s; ski/scalpel now -s; hindu/zulu/menu/vermouth/shampoo/igloo — stressed -ú vacillates -s/-es) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.7.2 (p.42-43): the full atonic/tonic-vowel-ending plural subsystem, including the explicit "tiende cada vez más a formarse con -s" register-change note for -í nouns. |
| régimen-regímenes / espécimen-especímenes / carácter-caracteres | (regime/specimen/character — the three nouns whose stress shifts in the plural) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.7.3 Norma box (p.43): "Plurales con cambio de acento" — closed list of exactly three Spanish nouns where pluralization relocates the tonic syllable. |
| el/los déficit / superávit / memorándum / curriculum→currículum(no castellanized) vs. currículo→currículos (castellanized) / referendo→referendos | (deficit/surplus/memorandum — invariant Latin plurals when unadapted; curriculum both as invariant Latin loan and as adapted Spanish word; referendum adapted) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.8.2 (p.45): RAE-recognized Latin nouns keep invariant plural unless castellanized, in which case they pluralize normally; book explicitly flags *\*déficits, \*superávits, \*memorándums, \*quórums, \*ultimátums, \*desiderátums, \*currículums, \*referéndums* as inadvisable incorrect plurals. |
| cenit / caos / sed / cariz — vs. — (las) andas / víveres / nupcias / exequias | (zenith/chaos/thirst/aspect = singularia tantum; funeral-bier/provisions/nuptials/funeral-rites = pluralia tantum) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.8.3 (p.45): closed semantic classes of number-defective nouns. |
| funeral/funerales · barba/barbas · paz/paces — vs. — tijera/tijeras · nariz/narices · tenaza/tenazas — vs. — gafas · prismáticos · anteojos | (funeral; beard; peace — sg/pl near-synonymous; scissors/nose(nostrils)/pincers — sg or pl name the same single symmetrical object; glasses/binoculars/spectacles — ONLY plural names the single object) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.8.3 (p.45): three-way contrast — ordinary near-synonymous sg/pl, "two symmetrical parts" nouns where sg or pl both work for one object, and the subtype where only the plural does (a variant of pluralia tantum). *Son dos vinos distintos* illustrates a 4th pattern: no-contable nouns pluralized = "kinds of X," a meaning shift not a true count. |
| álbum→álbumes(no *álbunes) / guardia civil→guardias civiles(no *guardiaciviles) / hipérbaton→hipérbatos(no *hiperbatones/*hipérbatons) / malentendido→malentendidos(no *malos entendidos) / chotis→invariable / reloj→relojes(no *relós) / cacahué→cacahués(no *cacahueses) / tic→tics(no *tiques) | (album/civil-guard/hyperbaton/misunderstanding/a dance-name/watch/peanut/tic — each with a commonly-made plural error named and corrected) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.1.8.3 Norma box (p.45): "Plurales que presentan dificultad" — a curated list of specific prescriptive corrections, genuinely new prescriptive-norm content. |
| peatonal / interactivo / parolímpico / cibernético | (pedestrian-only / interactive / Paralympic / cybernetic) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.1.1 (p.50): the book's own examples of "recent" adjectives, offered as evidence adjectives form an open class — itself a dateable snapshot of 2005-era neologisms. |
| un triángulo isósceles→dos triángulos isósceles / una entrada gratis→dos entradas gratis | (isosceles triangle(s); free ticket(s) — both adjectives invariant in the plural) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.1.2 (p.51): exception to adjective pluralization — non-agudo adjectives ending in -s stay invariant. |
| lingüístico / social / musical / ocular — madrileño / canario / abulense / ruso — siguiente / último / anterior / postrero | (linguistic/social/musical/ocular = relación-pertenencia; Madrid-native/Canarian/Ávila-native/Russian = gentilicios; next/last/previous/final = cuasideterminativos) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.1.3 (p.51): the book's three-way semantic subclassification of adjectives beyond plain calificativos, with cuasideterminativos flagged as a fuzzy category bordering on determinative meaning. |
| mejor / peor / mayor / menor / inferior / superior | (better/worse/bigger(elder)/smaller(younger)/lower/higher — Spanish's synthetic Latin-derived comparatives) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.2.4 (p.53): comparativos sintéticos — inherently comparative, hence incompatible with más/menos/tan. Norma box (p.53) explains the well-known prescriptive error *\*más mayor*, with the carve-out that *mayor* referring to age (not size) DOES tolerate *tan mayor* / *más mayor* because Peninsular Spanish lacks a true grado-positivo adjective for that specific semantic field; also distinguishes *los más mayores* (a few extra years within a presupposed group) from *los mayores* (adults/near-adults). |
| óptimo / pésimo / mínimo / máximo / ínfimo / supremo | (best/worst/smallest/biggest/lowest/highest — synthetic Latin-derived superlatives) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.3.3 (p.55): superlativos sintéticos, derived from bueno→mejor→óptimo etc.; function as superlativos absolutos (*calificaciones óptimas*). §2.2.4.3 (p.57) flags *\*muy óptimo / \*optimísimo* as incorrect for the same reason as *\*más mayor*; also flags *inferior/superior/anterior/posterior* as comparativo-derived forms that colloquially behave as positives (*muy inferior*, *muy anterior*), and flags *principal/culminante/álgido/absoluto/eterno/infinito* as calificativos with inherently superlative meaning that reject all grade marking (Norma box: *\*un cuidado muy absoluto*, *\*la parte más principal*, but idiomatic exceptions like *el más mínimo caso*, *llegó a ultimísima hora* ARE accepted). |
| pobrísimo/paupérrimo · altísimo · novísimo | (very poor via two superlative routes; very tall; very new) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.3.1 (p.54): -ísimo/-érrimo suffixation, or adverbial substitutes — está bien dormido, extraordinariamente pobre, enormemente amable, horriblemente cansado, verdaderamente viejo, impresionantemente caros, increíblemente cariñoso, horrorosamente feo. |
| fortísimo/novísimo/bonísimo/certísimo/recentísimo/valentísimo/calentísimo (culto) — vs. — fuertísimo/nuevísimo/recientísimo/ciertísimo/buenísimo (coloquial) | (strong/new/good/certain/recent/brave/hot — learned-register superlatives that don't diphthongize vs. everyday-register ones that do) | adjective | core | — | contemporary (2005) | formal / colloquial (register split explicitly marked by source) | national | grammar_reference | n/a | plausible_unverified | §2.2.4.1 (p.56): adjectives with ue/ie diphthongs don't diphthongize in the learned superlative; the coloquial diphthongized forms ARE named as frequent, but *\*valentísimo* and *\*calentísimo* are flagged as unused even informally — a genuine register/acceptability distinction the source itself marks. |
| amabilísimo / notabilísimo / sapientísimo — cursilísimo (interfijo -li-) — simplísimo / simplicísimo (two accepted superlatives) | (very kind/notable/wise — built on the Latin root, not the Castilian one; very "cursi"/tacky with a linking -li-; "simple" has two accepted superlative forms) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.4.1 (p.56): -ble-ending and sabio-type adjectives suffix onto the Latin root rather than the Castilian surface form. |
| libérrimo/célebérrimo/nigérrimo/paupérrimo/misérrimo/acérrimo/pulquérrimo/aspérrimo — negrísimo/pobrísimo/asperísimo (double-accepted) | (free/famous/black/poor/miserable/staunch/neat/harsh, each via the learned -érrimo suffix on a Latin root; three of these also accept -ísimo) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.4.1 (p.56): closed list of -érrimo superlatives; only negro/pobre/áspero double as -ísimo too. |
| muy próximo(no *proximísimo) / muy anterior(no *anteriorísimo) / muy heroico(no *heroicísimo) / muy ciego(no *ceguísimo) / muy católico(no *catolicísimo) / muy nimio(no *nimísimo) | (very close/previous/heroic/blind/Catholic/trivial — adjectives taking muy but rejecting -ísimo) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.4.2 (p.57): a distinct gap class from the "no grade at all" adjectives — these DO grade, but only adverbially, never by suffix. |
| un pobre hombre('desgraciado') / un hombre pobre('sin dinero') — un simple soldado('sin graduación') / un soldado simple('tonto') — cierta cosa('alguna') / cosa cierta('verdadera') — un gran hombre('que destaca') / un hombre grande('de tamaño') — un nuevo coche('otro coche') / un coche nuevo('sin usar') | (poor-wretched vs. poor-penniless; mere-soldier vs. simple-minded soldier; "certain(some)" vs. "certain(verified)"; "great" vs. "big/tall"; "another" vs. "unused") | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.6.2 (p.61): the canonical pre-/post-nominal meaning-shift set, given with unusually explicit paraphrased glosses for each half of all five pairs — a genuinely systematic, fully-glossed version of a pattern other sources in this corpus likely only sketch with 1-2 examples. |
| el libre albedrío / la vía férrea(no *la férrea vía) | (free will; railway — adjective+noun units with permanently fixed word order) | adjective+noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.6.3 (p.61): adjetivos en posición fija — the adjective and noun together form a frozen conceptual unit, unlike ordinary explicativo/especificativo adjectives, which remain reorderable. |
| ser alto/estar alto · ser calvo/estar calvo · ser despierto('listo')/estar despierto('no dormido') · ser delicado('sensible')/estar delicado('mal de salud') · ser débil('apocado')/estar débil('sin fuerzas físicas') · ser listo('inteligente')/estar listo('preparado') · ser orgulloso('con exceso de satisfacción propia')/estar orgulloso('con satisfacción') · ser negro('de raza negra')/estar negro('irritado') · ser nuevo('sin estrenar')/estar nuevo('usado sin parecerlo') · ser católico('de religión católica')/no estar católico('estar mal de salud') · ser vivo('listo')/estar vivo('no muerto') · ser interesado('egoísta')/estar interesado('tener interés') | (tall/bald/awake-shrewd/sensitive-unwell/apocado-weak/clever-ready/vain-pleased/Black-irritated/unused-unworn-but-used/Catholic-well/sharp-alive/selfish-interested, each pair contrasting ser vs. estar with a wholly distinct lexical meaning) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.2.7.3 (p.63): this corpus's 015 (Schaum's) is noted elsewhere as having "a concise catalog of ser/estar meaning-changing adjectives" — this is a genuinely independent, differently-selected and more fully-glossed list (12 pairs vs. a plausibly shorter catalog), kept in full per the non-redundant-supplement rule as independently valuable rather than assumed identical without checking. Distinguished from the simpler case earlier on the same page (*es alto/está alto*, *es calvo/está calvo* — same core meaning, inherent-vs-acquired-state distinction only) and from §2.2.7.1's sujetos-oracionales-only-with-ser set (*es necesario/posible/probable/importante/distinto/normal/obligado/común/evidente/seguro/absurdo/propio*) and §2.2.7.2's estar-only/post-participle set (*cansada, roto, sentado, acabado, lleno, vacío, (bien) considerado*). |
| la hache / la a / la AFE (Asociación de Futbolistas Españoles) — el ama / el hacha / el hambre / el aula (sg.) → las amas / las hachas / las hambres / las aulas (pl.) | (letter-names "h"/"a"; an acronym "AFE" that keeps *la* despite the a-tónica rule, because letter-names and feminine acronyms are the stated exceptions; "mistress/axe/hunger/classroom" switching el↔la between singular and plural) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.2.1 Norma box (p.69): the well-known a-/ha- tónica article rule, with the specific exceptions (letter names, feminine given names starting with tonic a-, feminine acronyms starting with tonic a-) fully enumerated — more complete than a typical pedagogical-grammar mention. |
| todos los viernes / todo el terreno — los tres bolígrafos / las segundas partes / los pocos alumnos — los otros tres alumnos / los tres primeros alumnos | ("every Friday"/"the whole terrain" — article preceded only by todo/toda; article followed by cardinal+ordinal+indefinido, stackable) | determinative phrase | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.2.3 (p.69): combinatorial rule — article can follow only *todo* (and variants) among determinatives, but can itself be followed by (and stacked with) numerals and several indefinidos (*muchos, pocos, varios, otros, demás*). |
| lo bueno / lo importante / lo curioso / lo destacable | (the good part / the important thing / the curious part / the noteworthy part) | determiner+adjective (sustantivado) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.3.1 (p.72): neuter article *lo* sustantivizing adjectives into abstract-value expressions. |
| ¡Lo grande que es esta casa! / ¡Lo listas que son estas niñas! / ¡Lo simpática que es esta mujer! / ¡Lo lejos que está! / ¡Lo bien que canta! / ¡Es de lo más tonto! / ¡Está de lo más insoportable! / ¡La de agua que cayó! | (exclamative "how big this house is!" etc.; "he's the dumbest!"; colloquial-emphatic "the amount of rain that fell!") | construction | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.3.2 (p.73): valor enfático of *lo* (and, per the source, of the other article forms too: *¡Hay que ver el calor que hace!* = "Hace mucho calor.") — including the *la de + sustantivo* emphatic-quantity coloquial construction (elided from *la cantidad de*), explicitly marked "propia del coloquio." |
| Cerró los ojos(sus ojos) / La mujer a la que se le murió el marido(su marido) | ("closed [the=his/her] eyes"; "the woman whose [the=her] husband died" — article standing in for a possessive) | construction | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.3.2 (p.73): valor posesivo of the article, recoverable from context/situation/cultural knowledge rather than morphologically marked. |
| Dime el dinero que llevas.(≈ cuánto dinero llevas) / No sé la chaqueta que me he puesto.(≈ qué chaqueta me he puesto) | ("tell me the money you're carrying" ≈ how much; "I don't know the jacket I put on" ≈ which") | construction | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.3.2 (p.73): article with a value equivalent to interrogatives cuánto/qué, marked "propio del coloquio." |
| esta/esa/aquella casa · Esta casa es cómoda / Esa casa es cómoda / Aquellos años son inolvidables | (this/that(near-listener)/that(far-from-both) house, with the book's own glosses: este = near speaker in space or time; ese = near listener in space or time; aquel = far from both speaker and listener in both space and time) | determiner | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.4.1 (p.74): the three-way deictic system tied explicitly to the roles of hablante/oyente, a more explicit discourse-anchored account than a simple "this/that/that over there" gloss. |
| la chica esa / esos tus ojos / esos tres amigos / todos esos niños / en tal ocasión(≈ en esa ocasión) / el tal Andrés / esa tal Rosario | ("that girl (dismissive)"; "those eyes of yours"; "those three friends"; "all those children"; "on such an occasion"; "that so-called Andrés/Rosario") | determiner | core / colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.4.3-4 (p.75): demonstratives following a noun require the article (*la chica esa*, never *\*estos los niños* preceding); combine with posesivos/numerales/some indefinidos but always preceding them, except *todo* which precedes the demonstrative; *tal/tales* as a demonstrative in its own right, and *el tal X / la tal X* marked as carrying a despective connotation when combined with another demonstrative. |
| mi pequeña hija / mi entonces marido / Siempre hablan mal de mi hijo(determinativo posesivo) vs. Siempre hablan mal de mí, hijo(pronombre personal, written with tilde) | ("my little daughter"; "my then-husband" — adjective/adverb intercalated inside a possessive phrase; the mi/mí minimal pair distinguishing unstressed possessive from stressed personal pronoun by the written accent alone) | determiner / pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.5.1 ATENCIÓN box (p.76): a genuinely useful orthographic-disambiguation note (mi vs. mí) not generally foregrounded in basic textbooks at this level of explicitness. |
| *la mi pelota / *la su casa | (ungrammatical in standard Spanish: article + apocopated possessive) | construction | regional | — | contemporary (2005) | northwest Spain (noroeste español) | regional | grammar_reference | n/a | plausible_unverified | §2.3.5 Norma box (p.77): explicit regional/dialectal annotation — article+apocopated-possessive combination is a real dialectal feature of northwestern Spain but excluded from the norma culta. This is exactly the kind of explicit regional tag the extraction spec flags as high priority. |
| la casa es mía / los hijos son nuestros / Esa casa es más mía que tuya / Ese gesto es muy mío | (the house is mine; the children are ours; "that house is more mine than yours"; "that gesture is very [typically] me") | determiner (pleno, atributo function) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.6.1 (p.78): plena possessives in predicate/atributo position can themselves take grading adverbs (*más mía*, *muy mío*) — a distinctly adjective-like behavior the source highlights. |
| *delante mío/mía / *cerca nuestro/nuestra / *detrás tuyo/tuya (incorrect in standard register) — delante de mí / cerca de vosotros / detrás de ti (standard) | (ungrammatical adverb+possessive combos vs. the correct adverb+de+pronoun form) | construction | colloquial / regional | — | contemporary (2005) | Hispanoamérica; southern Peninsular Spain; Canary Islands (per source) | regional | grammar_reference | n/a | plausible_unverified | §2.3.6.1 Norma box (p.78): explicitly flagged as frequent in those varieties despite being non-standard — a second explicit regional/register annotation in this chunk. |
| cuyo padre / cuyos hijos / cuya madre / cuyas hijas · aquel hombre cuyos hijos... (antecedent-agreement mismatch shown graphically) | (whose father/children/mother/daughters — possessive relative, agreeing with the POSSESSED noun, not the antecedent) | determiner (relativo posesivo) | core / formal | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.6.2 (p.79): *cuyo* as a determinativo relativo with posesivo meaning, atonic, always preceding and agreeing with the noun it introduces while relating (without agreement) to an antecedent elsewhere in the sentence. |
| *Devolví ese libro que sus páginas estaban en blanco(debe ser: cuyas páginas) / *Vino a verme un señor a mi casa, cuyo señor me dijo...(debe ser: quien me dijo) — en cuyo caso / con cuyo objeto / a cuyo fin(censured demonstrative-like uses, prefer: en ese/tal caso, etc.) | (two named prescriptive errors around *cuyo*: using *que...sus* instead of *cuyo*, and using *cuyo* as a near-demonstrative with no real possessive sense) | construction | core / formal | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | §2.3.6.2 Norma box (p.79): "Uso de cuyo" — explicit prescriptive-error catalog, a genuinely new normative-usage layer. |

### Grammar points

#### Los géneros común, ambiguo y epiceno (§2.1.6.1-3, p.40-41)

The book sharpens the traditional single "género común" label into three distinct phenomena, insisting on "comunes/ambiguos en cuanto al género" as more accurate terminology than "de género común/ambiguo" (since these are not literal additional genders). **Comunes en cuanto al género**: nouns lacking any gender-marked form of their own, which nonetheless need to differentiate referent sex — done purely through the article/determinative (*el/la estudiante*). Productively comunes: all *-ista* nouns, person-denoting nouns ending in *-a*, and most nouns ending in *-e* (though many *-e* nouns actually do have a feminine form instead: *jefe-jefa*, *nene-nena*, *sastre-sastra*). A historically active subclass — title/profession nouns — has been "modernamente" desdoblado into masc./fem. pairs that used to be común (*ministro-ministra*, *médico-médica*, etc.), though *bachiller* resists this split. An ATENCIÓN box notes the RAE records *juez* as común but also now accepts the innovated *jueza*. **Ambiguos en cuanto al género**: unlike comunes nouns (no inherent gender at all), these DO have an inherent gender, but usage lets them take masculine or feminine determinatives/adjectives interchangeably with no semantic difference, only possible register/style nuance (*el/la mar*); the ambiguity can also be keyed to number rather than free variation (*el arte dórico* but *las bellas artes*). **Epicenos**: inherently fixed-gender nouns for people/animals that semantically don't distinguish sex (*el gorila* is grammatically masculine regardless of the animal's actual sex). The book explicitly corrects "la gramática tradicional," which called this "género epiceno" — epiceno is a semantic trait of certain nouns, not a genuine grammatical gender. A closing ATENCIÓN box notes dictionaries mark m./f. and com./amb. abbreviations but never mark the epiceno trait, since it isn't grammatical.

#### El número del sustantivo: formación y casos especiales (§2.1.7.1-3, §2.1.8.1-3, p.42-45)

Number is binary (singular/plural); singular is the unmarked form, plural is marked by *-s*/*-es*. Formation rules, organized by the noun's final segment: **vowel-final** — unstressed vowel → *-s* (*casa→casas*); vowel stressed *á/é/ó* → *-s* (*sofá→sofás*); vowel stressed *-í* → traditionally *-es* (*jabalí→jabalíes*) but increasingly just *-s* (*esquí→esquís*) — an explicit in-progress sound/register change the book flags; stressed *-ú* vacillates between *-s* and *-es* with some words (*hindú*) accepting both and others (*menú, vermú, champú*) taking only *-s*. **Consonant-final** — any consonant other than *-s/-x* → *-es* (*pastel→pasteles*); agudo nouns ending in *-s/-x* → *-es* (*compás→compases*); llano/esdrújulo nouns ending in *-s/-x* → invariant (*la tesis→las tesis*); *-y*-final nouns convert *y* to a consonant and add *-es* (*rey→reyes*), except *jersey, paipay, rentoy*, which keep the *y* and take *-éis*. **Casos especiales**: vowel-letter-names pluralize with *-es* (*a→aes*); *yo/no/sí* as nouns pluralize *-es* (*yo→yoes*); solfège note-names have their own idiosyncratic plural set (*do→dos, re→res, mi→mis, fa→fas, sol→soles, la→las, si→sis*). A Norma box lists the closed three-item set where the plural shifts stress: *régimen→regímenes, espécimen→especímenes, carácter→caracteres*. **Palabras extranjeras**: vowel-final loanwords follow normal rules (*boutique→boutiques*); consonant-final loans in *-l/-n/-d/-z/-r/-s/-x* (last two only if agudo) normally take *-es* (*eslogan→eslóganes*), though some vacillate (*best-seller/best-sellers*); other consonant-final loans simply add *-s* (*los complots*), with *club→clubes* an RAE-recommended exception and *sándwich→sándwiches* increasingly generalized. **Sustantivos latinos**: unadapted RAE-recognized Latin nouns stay invariant except for the accent mark (*el/los déficit, el/los superávit, el/los memorándum*); adapted ones follow normal rules (*currículo→currículos*); an ATENCIÓN box flags *currículum*'s learned-register Latin plural *currícula* as exceptional, and the main Norma box lists specific inadvisable hypercorrected plurals (*\*déficits, \*superávits, \*memorándums,* etc.) alongside the parallel case of *desiderátum→desiderata*. **Otras cuestiones**: *singularia tantum* (*cenit, caos, sed, cariz*) and *pluralia tantum* (*andas, víveres, nupcias, exequias*) are closed semantic classes; some nouns show no real sg./pl. meaning difference (*funeral/funerales*); "two symmetrical parts" nouns can take either number for one object (*tijera/tijeras*) or sometimes only the plural for one object (*gafas, prismáticos, anteojos* — itself classed as a pluralia tantum variant); non-contable nouns pluralized can shift to a "kind/variety" meaning (*Son dos vinos distintos*). A closing Norma box catalogs specific commonly-mispluralized nouns with their corrections (*álbum→álbumes* not *\*álbunes*; *guardia civil→guardias civiles* not *\*guardiaciviles*; *hipérbaton→hipérbatos*; *reloj→relojes* not *\*relós*; *chotis* invariant; *cacahué→cacahués*; *tic→tics* not *\*tiques*).

#### El adjetivo: características y clasificación semántica (§2.2.1.1-3, p.50-51)

Adjectives are always tonic words, belong to an open class (illustrated with 2005-era neologisms: *peatonal, interactivo, parolímpico, cibernético*), take their gender/number entirely from the noun they agree with, and — unlike nouns — never co-occur directly with determinatives (*\*mi alegre*) except when sustantivado (*el malo*). Adjectives capable of semantic gradation combine only with the apocopated adverbial forms *tan/cuan/cuán/muy*, never the full forms *tanto/cuanto/cuánto/mucho* (whose presence signals sustantivación: *¿Qué hace tanto bueno por aquí?*). Formally, adjectives split into **de una sola terminación** (invariant for gender: *azul, alegre, breve, común, policial*) and **de dos terminaciones** (gender-marked: *bonito/bonita, español/española, chiquitín/chiquitina*); pluralization follows the same -s/-es split as nouns, with an explicit exception for non-agudo adjectives ending in -s (*un triángulo isósceles → dos triángulos isósceles*, invariant) and for *gratis*. Semantically, the traditional "expresses quality" definition is critiqued as inexact (plenty of nouns denote quality too: *bondad, belleza, valor*) and the book offers a finer breakdown: **calificativos** (*bueno, malo, inteligente, valiente*), **de relación o pertenencia** (*lingüístico, social, musical, ocular*), **gentilicios** (*madrileño, canario, abulense, ruso*), and **cuasideterminativos**, whose meaning sits close to that of determinatives (*siguiente, último, anterior, postrero*) — explicitly flagged as a non-exhaustive list, since some adjectives shift class by context.

#### Grado del adjetivo: positivo, comparativo, superlativo (§2.2.2.1-4, §2.2.3.1-3, §2.2.4.1-3, p.52-57)

Grade is a genuinely adjective-specific formal feature nouns lack (with the carve-out that relational/origin adjectives and some cuasideterminativos don't grade either). **Positivo**: ungraded baseline (*Juan es bueno*). **Comparativo**: cuantificado by *más/menos/tan* or the locution *igual de*, in three varieties — superioridad (*más...que*), inferioridad (*menos...que*), igualdad (*tan...como* / *igual de...que*). **Superlativo**: two kinds. *Absoluto* (top of a scale, via *muy* or -ísimo/-érrimo suffixation, or via adverbial substitutes like *extraordinariamente, enormemente, impresionantemente*); *relativo* (compares against a set, via *artículo+más/menos+adjetivo* or *artículo+comparativo sintético* — *el mejor de todos*), requiring an explicit or implicit *de+complemento*. The book makes the striking observation that superlativo relativo sentences (*María es la más lista de todos sus hermanos*) don't actually entail María being lista in any absolute sense, only least-tonta relative to the group — "el superlativo relativo debería llamarse comparativo de excelencia." **Formación del superlativo por derivación**: mostly -ísimo/-ísima, with learned-register non-diphthongization for *ue/ie*-diphthong adjectives (*fortísimo, novísimo, certísimo* vs. the colloquially-frequent-but-accepted diphthongized *fuertísimo, nuevísimo, ciertísimo* — though *\*valentísimo/\*calentísimo* never occur even colloquially); some adjectives suffix onto their Latin root instead of the Castilian surface form (*amabilísimo, notabilísimo, sapientísimo*); *cursi* takes a linking interfijo (*cursilísimo*); *simple* has two accepted forms (*simplísimo, simplicísimo*); a closed -érrimo list exists (*libérrimo, célebérrimo, nigérrimo, paupérrimo, misérrimo, acérrimo, pulquérrimo, aspérrimo*), three of which also double as -ísimo (*negrísimo, pobrísimo, asperísimo*). Some adjectives take *muy* but reject the suffix entirely (*muy próximo* but never *\*proximísimo*; similarly *anterior, heroico, ciego, católico, nimio*). **Comparativos y superlativos sintéticos**: Spanish retains direct Latin-comparative forms (*mejor, peor, mayor, menor, inferior, superior*) and Latin-superlative forms (*óptimo, pésimo, mínimo, máximo, ínfimo, supremo*), both of which are in principle incompatible with ordinary grade marking (*\*más mejor, \*muy óptimo, \*optimísimo*) precisely because they already encode grade morphologically. The book carves out two genuine exceptions, both given extended prescriptive-norm treatment: (1) *mayor* referring to age (not size) lacks any true grado-positivo adjective in Peninsular Spanish, so *tan mayor*/*más mayor* are tolerated when the meaning genuinely differs from plain *mayor* (*Cuando seas más mayor irás al cole* ≠ *cuando seas mayor irás a la mili*; *los más mayores* ≠ *los mayores*) — but *\*más mayor* referring to size is never acceptable (*las mesas más mayores* must be *las mesas más grandes*); (2) several comparativo-derived forms (*inferior, superior, anterior, posterior*) have drifted to behave as ordinary positives in casual Spanish, hence tolerate *muy* (*muy inferior, muy anterior*). A final closed set of calificativos carries inherently superlative meaning and rejects grading altogether (*principal, culminante, álgido, absoluto, eterno, infinito*), with a Norma box flagging *\*un cuidado muy absoluto* / *\*la parte más principal* as errors, while noting idiomatic exceptions persist for expressive effect (*el más mínimo caso, llegó a ultimísima hora*) and that doubling two grade-markers on one adjective is never acceptable (*\*muy listísimo*).

#### Funciones y apócope del adjetivo (§2.2.5.1-3, p.58-59)

Adjectives complement the noun either **directly** (modificador/complemento del sustantivo function, pre- or post-posed: *alto porcentaje* / *porcentaje alto*) or **indirectly**, via a verb, as **atributo** or **predicativo** (*Juan está triste*; *Tu hija salió ilesa*), always agreeing with the noun referenced. **Apócope**: certain adjectives drop a final vowel/syllable before the noun. *Grande→gran* before any singular noun (masc. or fem.) unless preceded by *más* (*gran hombre, gran mujer*, but *la más grande oportunidad*). *Bueno/malo→buen/mal* only before masculine singular nouns, not feminine (*buen hombre* but *buena mujer*). *Santo→San* only before masculine proper names, never before common nouns or feminine proper names (*San Pedro* but *santo varón, Santa Lucía*), and not before names starting *To-/Do-* (*Santo Tomás, Santo Domingo*). **El adjetivo y los determinativos**: an adjective co-occurring with a determinative (especially the article) signals sustantivación (*Me gusta el rojo*; *Los buenos tendrán su recompensa*) — though determinatives can also simply precede the adjective while syntactically governing the noun instead, not the adjective (*mi preciosa hija*, *los grandes autores*). Virtually all adjectives can be sustantivized with neuter *lo*, except those denoting qualities applicable only to persons (*lo bueno, lo pequeño* are fine; *\*lo ileso, \*lo contento, \*lo adulto* are not). A separate, functionally distinct use of *lo* + adjective + *que* acts as an intensifier equivalent to an exclamative *qué* rather than a true sustantivador (*lo fuertes que son → qué fuertes son*), with the adjective still agreeing with its noun (*lo lista que es esa chica*).

#### Posición del adjetivo (§2.2.6.1-3, p.60-61)

**Pospuesto** (adjetivo especificativo): normally narrows/delimits the noun's reference (*Quiero una corbata azul* — not red or white), though some preposed adjectives can also carry specificative value (*un pequeño detalle*). Relational and gentilicio adjectives are always postposed, never preposed (*viviendas sociales*, not *\*sociales viviendas*; *pintor español*, not *\*español pintor*); certain other adjectives always precede instead (*un mero trámite*, not *\*un trámite mero*). **Antepuesto** (adjetivo explicativo/epíteto): typically adds a merely explanatory note without delimiting reference (*la blanca pared, la verde hierba*); some explicativos name an inherent quality of the noun (*la blanca nieve, el negro carbón*), others attribute something not strictly part of the noun's denoted reality (*las polvorientas encinas, su esbelta figura*). A postposed adjective set off by pauses/commas is likewise explicativo, not specificativo — contrasting *El chico simpático se acercó a mí* (specifying which chico) with *El chico, simpático, se acercó a mí* (merely describing the one chico already identified); postposed adjectives can also be purely descriptive without being comma-set-off (*El cielo azul nos envolvió en una atmósfera diáfana*). **Meaning shift by position**: a closed, fully-glossed set of adjectives change meaning depending on pre- vs. post-nominal position: *pobre* ('wretched' pre- vs. 'penniless' post-), *simple* ('non-graduated' pre- vs. 'foolish' post-), *cierto* ('some' pre- vs. 'verified/true' post-), *gran(de)* ('outstanding' pre- vs. 'physically large' post-), *nuevo* ('another' pre- vs. 'unused' post-). **Posición fija**: certain adjective+noun combinations form a frozen conceptual unit with unchangeable word order (*el libre albedrío*; *la vía férrea*, never *\*la férrea vía*) — distinct from ordinary explicativo/especificativo adjectives, which remain reorderable. A Norma box separately covers concordance when one adjective modifies multiple coordinated nouns: singular same-gender nouns → plural adjective of that gender; singular different-gender nouns → plural masculine adjective; plural nouns → plural adjective by the same gender rules; only when the combined nouns denote a single unified referent can the adjective stay singular (*lengua y literatura española*, alongside the still-valid plural *lengua y literatura españolas*).

#### Adjetivos con ser y estar (§2.2.7.1-3, p.62-63)

Three distinct subclasses. **Only with *ser***: relational/procedencia adjectives (*El problema es político*, never *\*está político*; *Soy extremeño*, never *\*estoy extremeño*), and adjectives taking a full oracional (clausal) subject (*es necesario, posible, probable, importante, distinto, normal, obligado, común, evidente, seguro, absurdo, propio*) — *estar* becomes impossible specifically when the subject is a clause (*Es obligado que llueva*, never *\*está obligado que llueva*). **Only with *estar***: adjectives denoting a result — participles outside passive constructions always pattern this way (*Ana está cansada*, never *... es cansada*; *El jarrón está roto*; *El bebé está sentado*; *El trabajo está acabado*) — though some participle+*ser* combinations are independently grammatical because they shift to a genuinely different meaning (*estar (bien) considerado* 'to be respected' vs. *ser considerado* 'to be a considerate/thoughtful person'); other *estar*-only adjectives were historically irregular participles (*contento, satisfecho*) or simply carry participial, resultative meaning without being true participles (*está lleno, está vacío*, never *\*es lleno/vacío*). **Compatible with both, meaning shift**: many adjectives take both copulas with a real semantic difference. With *ser*, the adjective denotes an inherent quality (*Aurora es alegre* — a trait of her character) or a more-or-less-permanent classifying feature placing the subject in a category (*Pedro es soltero*). With *estar*, the same adjective denotes an acquired quality, the product of a real or imagined change (*Pedro está soltero* implies a contrast with a possible *casado* state; *Aurora está alegre* refers to her mood right now). Beyond that general pattern, a specific closed set of adjectives carries two genuinely unrelated lexical meanings depending on the copula, fully enumerated: *despierto* ('shrewd'/'not asleep'), *delicado* ('sensitive'/'in poor health'), *débil* ('timid/apocado'/'physically weak'), *listo* ('intelligent'/'ready'), *orgulloso* ('vain, excessively self-satisfied'/'pleased, satisfied'), *negro* ('of Black race'/'irritated'), *nuevo* ('unused'/'used but looking new'), *católico* ('of the Catholic faith'/negated: 'unwell' — *no estar católico*), *vivo* ('sharp-witted'/'alive, not dead'), *interesado* ('selfish'/'genuinely interested').

#### Terminología de los determinativos (§2.3 intro, p.66-67)

Before covering the determinative subclasses, the book lays out an unusually explicit terminological self-positioning relative to other grammarians' frameworks — itself a window into this author's theoretical choices rather than a neutral fact about Spanish. "Determinativo" in this grammar partially overlaps with "determinante" as used elsewhere, but here "determinante" is reserved for only the subset functioning as **actualizadores** — the function whereby a determinative enables a noun to serve as preverbal subject (*\*mesa tiene seis patas* is ungrammatical, but *la/mi/esta/alguna/una mesa tiene seis patas* works). "Actualizador" is synonymous with what other grammars call "presentador"; some grammarians instead use "determinante" for this function, or treat it as a full word-class label. By contrast, "**modificador**" names the function of complementing a noun without actualizing capacity, equally applicable to an adjective's or an adverb's complementation (*la mesa grande*, *la gran actriz*) — elsewhere called "adyacente" or "complemento del nombre/adjetivo/adverbio." When a determinative's actualizador-vs-modificador function isn't being distinguished terminologically, both get grouped as "adjuntos," "adyacentes," or "complementos del sustantivo." The book also flags that its own "artículo" corresponds to what other grammars call "artículo definido/determinado" — those other frameworks additionally posit "artículos indefinidos/indeterminados" (*un, una, unos, unas*), a category this grammar rejects outright, classing those forms instead as **determinativos indefinidos**. Finally, some grammarians treat the article as a bound morpheme of the noun itself (alongside gender/número), not a separate determinativo word class at all — the book notes this view without adopting it. An ATENCIÓN box (p.67) adds two sujeto-without-determinative exceptions beyond the proper-name case already known: no-contable nouns in postverbal position in certain contexts need no actualizing determinative (*Se encontró petróleo*; *Fue quemada gasolina* — but not *\*Se encontró libro*, a contable noun), and any plural noun, since plural number itself has actualizing capacity (*Se encontraron libros*; *Fueron quemadas sillas*).

#### Características generales de los determinativos (§2.3.1.1, p.68)

Determinatives form a **clase cerrada** (unlike adjectives' open class) — a fixed inventory that cannot admit new members. They always precede adjectives within the nominal group and never follow them (*estas hermosas casas*, never *\*hermosas estas casas*). They generally reject combination with cuantificadores (*\*muy aquel, \*más algunos*) — except *poco* (and variants), *más*, and *menos*, which can combine with grading adverbs (*muy poca gente, mucha más gente, mucho menos calor*), understood as instances of a "determinativo complejo" where *más/menos* remain omissible (*mucha gente*). Only when a determinative is itself used as an adjective can it take grading (*muy otro* ≈ 'muy distinto'). Determinatives preposed to common nouns let those nouns function as preverbal subjects in singular (*Mi libro tiene cien páginas*, not *\*Libro tiene cien páginas*; *Esa virtud se llama caridad*) — this actualizing capacity is the determinative's defining significative role, fixing/delimiting the noun's reference (*casa* vs. *esa casa, mi casa, una casa, la casa*). Aside from *mucho/poco*, determinatives generally reject both suffixes and prefixes and grading adverbs (*\*tuyísimo, \*algunísimo*, vs. the acceptable *muchísimo, poquísimo*). The full class inventory named here: **artículos**, **demostrativos**, **posesivos** (apocopados and plenos), **numerales** (cardinales and ordinales), **indefinidos**, **distributivos**, and **interrogativos y exclamativos** — each cross-referenced to its own later subsection.

#### El determinativo artículo (§2.3.2.1-3, §2.3.3.1-2, p.69-73)

**Características**: always precedes the noun/sustantivized phrase, is always atonic (leans phonetically on the following tonic word: *el vino* vs. stressed *él vino*), and always functions as actualizador (*\*Libro me gusta* vs. *El libro me gusta*). Forms: masculino *el*, femenino *la* (with the variant *el* before tonic a-/ha-), masculino plural *los*, femenino plural *las*, neutro *lo*. A dedicated Norma box fully enumerates the a-/ha-tónica rule: singular feminine nouns starting with tonic *a-/ha-* (accented or not) take *el* instead of *la* (*el ama, el hacha, el hambre, el aula*) — this *el* is historically a feminine variant (from Latin *illam*), not a masculine form, confirmed by the plural reverting to normal *las* (*las amas, las hachas*); if any word intervenes between article and noun, *la* is used instead (*el agua cristalina → la cristalina agua*); exceptions to the whole rule: letter-names *hache/a* always take *la* (*la hache, la a*), feminine given names starting with tonic *a-* always take *la* (*La Ana que me presentaste*), and feminine acronyms/siglas starting with tonic *a-* always take *la* (*la AFE*). **Significado**: the article delimits and individualizes/identifies what the noun denotes; can carry **valor deíctico** (pointing to a concrete referent already introduced: *Ayer vino a verme un alumno. Cuando el alumno se dirigió a mí...*) or **valor generalizador** (introducing concepts known via shared world-knowledge rather than referring to one specific instance: *El hombre es mortal*; *Tengo ganas de ir a la playa*, where *playa* isn't any one specific beach). **Combinatoria**: always precedes the noun but allows intervening adjectives/adverbs/prepositional groups (*la antigua casa*; *la en otros tiempos mujer del año*); the article itself is never preceded by another determinative except *todo/toda/todos/todas* (*todos los viernes, todo el terreno*); it CAN be followed by numerals (cardinal/ordinal) and some indefinidos (*muchos, pocos, varios, otros, demás* and variants), stackably (*los otros tres alumnos, los tres primeros alumnos*). **Sustantivación**: neuter *lo* sustantivizes adjectives with an abstract-value reading (*lo bueno, lo importante*); can also precede prepositional groups or full clauses (*lo de ayer; lo que me dijiste ayer*) — though this could alternatively be analyzed as *lo* itself being a pronoun heading a nominal group rather than a true sustantivizer. Masculine/feminine article forms sustantivize equally, with an implied/elided antecedent noun recoverable from context or shared knowledge (*el de ayer, la que me presentaste, los buenos, las azules*); fuller sustantivización shows up idiomatically (*No hagas el ridículo; Me gusta el dulce; No te hagas la tonta; Se hicieron los locos*). **Valor enfático**: *lo* intensifying an adjective of any gender/number (*¡Lo grande que es esta casa!; ¡Lo listas que son estas niñas!*) or an adverb (*¡Lo lejos que está!*); also in *ser/estar + de lo + comparativo* constructions (*¡Es de lo más tonto!*); this emphatic function isn't exclusive to *lo* — other article forms carry it too (*¡Hay que ver el calor que hace! → Hace mucho calor*); by elision of *cantidad*, *la* + *de* forms a colloquial emphatic-quantity locution (*¡La de agua que cayó!*). **Valor posesivo**: the article standing in for an understood possessive, recoverable from context (*Cerró los ojos* ≈ sus ojos; *La mujer a la que se le murió el marido* ≈ su marido). **Equivalencia con interrogativos**: in colloquial register, article+noun can carry the force of *cuánto* or *qué* (*Dime el dinero que llevas* ≈ cuánto dinero llevas; *No sé la chaqueta que me he puesto* ≈ qué chaqueta).

#### Determinativos demostrativos (§2.3.4.1-4, p.74-75)

**Características**: a three-element gender system, but only masculine and feminine forms (*este/esta, ese/esa, aquel/aquella* and plurals) function as true determinativos — the neuter forms (*esto, eso, aquello*) are always pronouns, never determinatives. Demonstratives are deictic/señaladores, used to point in space, time, or discourse context (*ese lápiz* = space; *aquellos años* = time; *Me gusta esa palabra: alborada* = context). The three-way system is explicitly tied to the roles of the communicative act's participants: *este* marks proximity to the speaker (space or time); *ese* marks proximity to the listener (space or time); *aquel* marks distance from both speaker and listener (space and time). The neuter forms can carry **valor anafórico** (referring back to something already said: *«Tú no trabajas nada»: eso fue lo que dijo*) or **valor catafórico** (referring forward to something about to be said: *Quiero esto: que vengas a verme*). **Funciones**: preceding a noun, demonstratives are actualizadores, just like the article, and likewise let any sustantivo function as preverbal subject (*Esta casa fue de mi abuela*, not *\*casa fue de mi abuela*); following a noun, they become modificadores instead, with the article now serving as actualizador (*La canción esa me encantó*); without any accompanying noun, they become pronouns performing ordinary nominal functions (sujeto, CD, etc.: *Ese no me gusta*). **Combinatoria**: preceding a noun, demonstratives never combine with the article (*\*estos los niños*); following a noun, they require it (*la chica esa*). They combine with posesivos, numerales, and some indefinidos (*poco, otro, mucho*) but always precede them, with the sole exception of *todo* (and variants), which precedes the demonstrative instead (*esos tus ojos, esos tres amigos, todos esos niños*). **Tal/tales**: function as demonstratives when preceding a noun, agreeing in number and carrying deictic force roughly equivalent to *ese* (*en tal ocasión ≈ en esa ocasión*); act as actualizadores, never combine with the article, and generally don't combine with other determinatives except another demonstrative, in which case the combination (*el tal Andrés, esa tal Rosario*) carries a despective connotation. A closing Norma box notes demonstratives with actualizador function before feminine nouns starting with tonic *a-/ha-* take the normal feminine form, NOT the article's *el*-substitution rule (*esa aula*, not *\*ese aula*; *esta hambre*, not *\*este hambre*).

#### Los determinativos posesivos (§2.3.5.1, §2.3.6.1-2, p.76-79)

**Formas apocopadas vs. plenas**: apocopadas — singular *mi, tu, su*, plural *mis, tus, sus* — are always atonic (leaning on the following word, becoming tonic only for emphasis: *¡Mi madre!*), and allow adjectives/adverbs/prepositional groups to intervene between them and the noun (*mi pequeña hija, mi entonces marido*). An ATENCIÓN box flags the orthographic minimal pair *mi* (unstressed possessive determinative, no tilde) vs. *mí* (stressed personal pronoun, tilde required): *Siempre hablan mal de mi hijo* (possessive) vs. *Siempre hablan mal de mí, hijo* (pronoun, vocative comma). *Mi/tu* refer to exactly one possessor regardless of number; *su/sus* can refer to one or several possessors (*su libro* = of him/her/them/usted/ustedes). Formas plenas — *mío/a(s), tuyo/a(s), suyo/a(s), nuestro/a(s), vuestro/a(s)* — are always tonic, follow the noun, and when the noun is singular require the noun to be actualized by another determinative (*El libro mío se perdió*). Apocopadas combine with no other determinative except *otro* and *mucho* (and the demonstrative), plus numerals, and can follow *todo* (*esos tus ojos, mis otros dos hijos, Todo mi esfuerzo*). A Norma box flags article+apocopated-possessive (*\*la mi pelota, \*la su casa*) as a genuine but non-standard dialectal feature of northwestern Spain, excluded from the norma culta. *Suyo* (and variants) can refer to one or several possessors; *nuestro/vuestro* (and variants) always refer to more than one possessor. Possessives, like personal pronouns, carry the grammatical category of **persona**: 1ª *mi(s), mío/a(s), nuestro/a(s)*; 2ª *tu(s), tuyo/a(s), vuestro/a(s)*; 3ª *su(s), suyo/a(s)*. Unlike the article and demonstratives, possessives form only a two-way (not three-way) gender system — no neuter possessive determinative exists. **Funciones**: apocopadas are always actualizadores, letting the noun serve as preverbal subject (*Mi coche es azul*, not *\*coche es azul*); plenas *mío/tuyo/suyo* are always modificadores (*el libro blanco → el libro tuyo*); *nuestro/vuestro* can function as either actualizador or modificador depending on position (*nuestra casa* actualizador; *la casa nuestra* modificador). Plenas (tonic) forms can additionally function as atributo in a predicate (*La casa es mía*; *Los hijos son nuestros*), either bare or sustantivized with the article, where sustantivized use carries an identifying sense (*Esa casa es la nuestra*; *Ese libro es el suyo*); in atributo function, plenas take grading adverbs like an ordinary adjective (*Esa casa es más mía que tuya; Ese gesto es muy mío*). The sustantivized neuter forms (*lo mío, lo tuyo, lo suyo, lo nuestro, lo vuestro*) can carry an emphatic-quantitative sense with certain verbs (*Ese hombre sufre lo suyo ≈ sufre mucho*). A Norma box states possessives never directly accompany adverbs (*\*delante mío/mía, \*cerca nuestro/nuestra, \*detrás tuyo/tuya* are non-standard, though frequent in Hispanoamérica, southern Peninsular Spain, and the Canary Islands per the source); the standard form requires *adverbio + de + pronombre tónico* (*delante de mí, cerca de vosotros, detrás de ti*). **El posesivo relativo *cuyo***: atonic, always functions as actualizador, always precedes and agrees in gender/number with the noun it introduces (*cuyo padre, cuyas hijas*) while relating — without agreement — to an antecedent elsewhere in the sentence (*aquel hombre cuyos hijos...*); incompatible with demonstratives and the indefinido *todo* (and variants), but compatible with numerals (*cuyo segundo hijo*). It adds a relativo grammatical value atop its possessive meaning, hence "determinativa relativa con significado posesivo," and can reference one or several possessors. A closing Norma box catalogs two named prescriptive errors: substituting *que...su(s)* or the article for *cuyo* (*\*Devolví ese libro que sus páginas estaban en blanco*, should be *cuyas páginas*), and using *cuyo* with no genuine possessive sense, as a near-demonstrative (*\*Vino a verme un señor a mi casa, cuyo señor me dijo...*, should be *quien me dijo*) — including a set of censured demonstrative-like fixed phrases (*en cuyo caso, con cuyo objeto, a cuyo fin*), for which the book recommends *en ese/tal caso*, etc. Before feminine nouns starting with tonic *a-/ha-*, *cuyo* takes its normal feminine form, not an *el*-style substitution (*cuya agua*, not *\*cuyo agua*).

---


---

## Spanish — Established Vocabulary/Grammar: Gramática didáctica del español, Chunk C (02.4.8–02.4.13 Pronombres cont'd; 02.5.1–02.5.14 El verbo, overview through irregularity typology)

**Source:** Leonardo Gómez Torrego, *Gramática didáctica del español*, Ediciones SM (Brazilian-licensed
edition, São Paulo, 2005), ISBN 85-7675-066-X. PDF pages 60–80 of
`03.Reference Grammars/Gramatica Didactica Del Espanol.pdf`, corresponding to **printed pages 118–159**
(verified against this book's own printed footer numbers: PDF p.60 footer shows "118"/"119", formula
`printed_left = 2×(PDF_page−1)`, `printed_right = printed_left+1` confirmed page-by-page through the
whole range, no drift found). Metalanguage is Spanish itself (as noted in the dispatch); glosses below
are English translations supplied by this extraction.

**Vision-read, no text layer** (confirmed — rendered via `pdftoppm -r 150`, each PDF page a two-printed-
page spread). **Marginalia found and excluded:** an institutional library ownership stamp — "ESCOLA IRMÃ
ELIZABETH / ENSINO DE 1º GRAU / SEE-PE / INSC. 70500 / BIBLIOTECA LUIZ CONRADO DE LORENA E SÁ / SERRA
TALHADA-PE" — recurs at the bottom of printed pages 131 (PDF p.66) and 137 (PDF p.68). This is a printed
rubber-stamp, not handwritten, but it is a previous institutional owner's mark, not the book's own
content, and was excluded from extraction per the vision-reading guard. No handwritten marginalia (pencil
notes, underlining, filled-in exercise answers) was found anywhere in this range.

**Non-redundant-supplement scope note.** Skimmed `007_practice_makes_perfect_spanish_irregular_verbs.md`
(irregular-verb-focused) before extracting, and grepped the full `established/` corpus for prior coverage
of this chunk's pronoun topics. **Skipped as redundant:** the basic existence/forms of the relative
pronouns `que`, `quien(es)`, `el cual`/`la cual`/`lo cual`, and `cuyo` — already tabulated with core
glosses in `006_practice_makes_perfect_advanced_spanish_grammar.md` (§Relative pronoun system, p.333) and
mentioned in `002`, `015`, `034`. Also skipped: plain regular `-ar/-er/-ir` conjugation paradigm tables
(fully covered in `007`/`008`/`014`) and the basic demonstrative-pronoun inventory (`este/ese/aquel`),
already standard content across the corpus. **Kept as genuinely new:** this source's far more granular
*syntactic function* breakdown of each relative pronoun (sujeto/CD/CI/CC/complemento de régimen/
modificador, with the `norma` boxes' explicit error patterns for each), the `proadjetivo`/`proadverbio`
analysis of `que` with ponderative `lo`, `dativo ético` and `voz media` (not found anywhere else in the
corpus), the peninsular-vs-Canarias/Hispanoamérica `tú`/`vosotros` vs `ustedes` split, the full
terminology-equivalence table for verb tense names across grammatical traditions (Bello-style terms like
`copretérito`, `antepresente`), the per-tense *pragmatic value* taxonomy (gnomic present, historic
present, courtesy imperfect, etc. — far beyond what the "Practice Makes Perfect" series' drill-oriented
books cover), the systematic root-irregularity-mechanism typology (§2.5.13), and four explicit regional/
dialectal annotations not previously captured anywhere in this corpus (Canarias/Hispanoamérica `ustedes`;
Galicia/Asturias/Canarias/Hispanoamérica's scarce `pretérito perfecto`; the Basque-Country-area
conditional-for-subjunctive substandard usage; and the León/Galicia `-ra`-as-pluscuamperfecto
dialectalism). **Printed page range actually covered: 118–159** (full range assigned, nothing further
sampled within it).

---

### Vocabulary

Note: this chunk's "vocabulary" is overwhelmingly academic/grammatical metalanguage (the book's own
terminology for grammatical concepts) rather than everyday lexical items, consistent with its genre. Each
entry below cites the printed page(s) where it is introduced/discussed.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| dativo ético (de interés) | "ethical dative" — a non-argument `me`/`te`/etc. clitic marking the speaker's (or addressee's) emotional stake in an action, removable without ungrammaticality | grammatical term | technical.linguistics | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | plausible_unverified | p.118–119; ex. *No te me caigas*, *La policía se me lo llevó* |
| voz media | "middle voice" — a reflexive-form clitic that marks something happened *to* the subject without the clitic being a true direct/indirect object; semantic rather than syntactic category per this source | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.119; ex. *El puente se ha hundido*, *La piedra se ha movido* |
| tú con valor generalizador | generalizing `tú` — `tú`/`te`/`ti` referring to "anyone," not the addressee; author flags it as exclusively colloquial | grammatical term / usage note | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.119 |
| proadjetivo / proadverbio | "pro-adjective" / "pro-adverb" — the relative `que` when its antecedent is itself an adjective or adverb rather than a noun (e.g. in *lo + adjective/adverb + que*) | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.120–121; ex. *Lo grande que es esta casa* ("How big this house is" ≈ *Es muy grande*); ponderative `lo + que` is explicitly said to equal exclamatives *qué/cuán* |
| prooración | "pro-clause"/"pro-sentence" — `que` or `lo cual` substituting not a noun but a whole preceding clause | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.121; ex. *Vino a verme, que (lo cual) no es poco* |
| relativo complejo | "complex relative" — the variants `el que/la que/lo que/los que/las que`, used where dropping the article is optional | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.122 |
| artículo sustantivador | "nominalizing article" — the article preceding `que` when a noun is omissible between them (distinguished from the complex relative above) | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.122; ex. *El que busca halla* → *El individuo que busca halla* |
| determinativo relativo | term applied to `cuyo/-a/-os/-as`: a possessive determiner-with-antecedent, explicitly **not** classed as a true relative pronoun (its function is that of an actualizador, not a noun-substitute) | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.121 (ATENCIÓN box) |
| pronombre interrogativo-exclamativo | cover term for `quién`, `qué`, `cuánto/-a/-os/-as` when used in exclamative as well as interrogative function | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.127 |
| *cuálo / cuála | vulgar/dialectal interrogative forms, condemned by the norm (correct form: `cuál`) | pronoun (substandard) | taboo | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.126, in a "Norma" box; asterisk is the source's own ungrammaticality marker |
| pronombre del discurso | "discourse pronoun" — a determiner (e.g. `mucho`, `otro`, `ninguno`, `cierto`) that becomes a pronoun specifically when it appears without an accompanying noun in context | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.128–129, applies to both indefinites and demonstratives |
| para nada | negative adverbial locution ("not at all"), formed from `nada` + `para`, used as a stand-alone negative reply | fixed phrase | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.128 |
| copretérito | Bello-tradition name for the indicative pretérito imperfecto (`cantaba`) | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.133 terminology table |
| antepresente | Bello-tradition name for indicative pretérito perfecto (`he cantado`); also for the *subjunctive* pretérito perfecto (`haya cantado`) | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.133 |
| antecopretérito | Bello-tradition name for indicative pretérito pluscuamperfecto (`había cantado`) | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.133 |
| antepretérito | Bello-tradition name for indicative pretérito anterior (`hube cantado`); also for subjunctive pretérito imperfecto (`cantara`/`cantase`) under a different equivalence line in the same table | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.133 |
| pospretérito | Bello-tradition name for indicative condicional simple (`cantaría`) | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.133 |
| antepospretérito | Bello-tradition name for indicative condicional compuesto (`habría cantado`) | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.133 |
| verbo unipersonal | this source's term for what other grammars call "verbo impersonal" (e.g. weather verbs) | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.133, cross-ref §2.5.17 (outside this chunk's range) |
| verbo pseudorreflexivo | alternate term (used by "other grammars," per this source) for what this book calls a verbo pronominal | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.133 |
| verbo desinente / verbo permanente | alternate terms (used by "other grammars") for, respectively, verbos perfectivos and verbos imperfectivos | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.133 |
| verbo atributivo | alternate term for verbo copulativo | grammatical term (terminology variant) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.133 |
| presente gnómico | the present tense used for timeless/universal statements (e.g. *Dos por cuatro son ocho*, *La ballena es un mamífero*) | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.148 |
| presente histórico | the present tense narrating past events as if current, common in literary narrative and also in colloquial storytelling | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.148; also cited as the preferred tense (with pretérito indefinido) for narration generally, p.150 |
| presente por futuro | present tense substituting for the future, to present upcoming events as closer/more certain | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.148; ex. *El próximo año voy a Madrid a estudiar* |
| valor de cierre (pretérito imperfecto) | the imperfect used as a literary "closing" narrative device, functionally replacing a preterite, typically with perfective verbs (`llegar`, `morir`) | grammatical term | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.149; ex. *A los tres años, el general moría de una forma misteriosa* → *...murió...* |
| futuro en el pasado (imperfecto) | the imperfect used to refer to something that, from a past vantage point, was slated for the future | grammatical term | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.149; ex. *¿No dijiste que el partido era mañana?* |
| perfectos fuertes | "strong preterites" — a subclass of pretérito indefinido whose 1st/3rd-person-singular ending is atonic `-e`/`-o` rather than the regular stressed `-í`/`-ió` (e.g. `pude`, `pudo`, `hice`, `hizo`) | grammatical term | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.158 |
| cierre de timbre vocálico | "vowel-timbre closing" — the root-vowel-irregularity mechanism where tonic/atonic `e→i`, `o→u`, `a→e` (e.g. `pedir→pido`, `dormir→durmamos`, `caber→quepo`) | grammatical term (irregularity typology) | technical.linguistics | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.157 |
| ustedes (como forma familiar y de respeto) | in Canarian and all Hispanic-American Spanish, `ustedes` serves as both the familiar and the respect 2nd-person plural, replacing peninsular `vosotros/-as`/`os` entirely | pronoun / regional usage note | regional | — | contemporary (2005) | Canarias; Hispanoamérica | transnational | grammar_reference | n/a | verified | p.119 |
| condicional por pretérito imperfecto de subjuntivo (en prótasis) | substandard regionalism: using the conditional tense inside an `si`-clause or concessive subordinate clause where standard Spanish requires the subjunctive (e.g. *\*Si vendrías, te lo diría*) | regional/substandard syntax | regional | — | contemporary (2005) | País Vasco y zonas limítrofes | regional | grammar_reference | n/a | verified | p.153, in a "Norma" box explicitly marked incorrect by the standard but attested as a real colloquial regionalism |
| -ra como pluscuamperfecto de indicativo / pretérito indefinido | archaism/dialectalism: using the `-ra` subjunctive-imperfect form with indicative pluscuamperfecto or simple-preterite value (e.g. *lo que me dijera* = *lo que me había dicho*); said to be common in journalistic register generally, but the *-se* equivalent of this usage is flagged as more clearly incorrect | regional/archaic syntax | archaic | — | contemporary (2005) | zonas leonesas y gallegas | regional | grammar_reference | n/a | verified | p.155 |
| pretérito perfecto (escasez regional) | the indicative pretérito perfecto (`he cantado`) is markedly rare in regional Spanish, replaced functionally by the pretérito indefinido | tense / regional distribution note | regional | — | contemporary (2005) | Galicia; Asturias; Canarias; Hispanoamérica | transnational | grammar_reference | n/a | verified | p.151; source adds that hypercorrect use of pretérito perfecto in place of indefinido also occurs in these zones |

### Grammar points

#### §2.4.8 Other characteristics of personal pronouns (p.118–119)

- **Pronouns with `mismo`/`solo` and with `todo`/cardinals.** Personal pronouns normally reject
  adjectives/determiners, but the quasi-determiners `mismo` and `solo` (and their inflected forms) are a
  marked exception (*yo mismo*, *tú solo*), and plural tonic pronouns combine with `todo` and cardinal
  numerals (*todos nosotros*, *nosotros tres*). Intensive `todo` can even precede tonic `yo/tú/él`
  (*Toda yo estaba mojada*).
- **Generalizing `tú`.** See vocabulary entry above.
- **Dativo ético.** See vocabulary entry above.
- **Familiar vs. respect pronouns.** Peninsular Spanish uses `tú`/`vosotros,-as` (tuteo) for familiar
  address and `usted`/`ustedes` for respect; Canarian and all Hispanic-American Spanish collapse this to
  `ustedes` for both registers (see vocabulary entry).
- **Voz media.** See vocabulary entry above.
- **Norma box — `lo`/`los`/`le` errors.** The source flags two errors as regional: (1) in parts of
  Hispanic America and Canarias, failing to pluralize direct-object `lo` when the indirect object is
  invariant `se` (e.g. saying *se lo entregué* for intended *se los entregué*); (2) fixing indirect-object
  `le` as singular even when its plural referent appears cataphorically afterward (e.g. *Quiero decirle a
  todos ustedes que...* instead of *decirles*). Not region-tagged beyond "algunas zonas de
  Hispanoamérica y de Canarias."

#### §2.4.9–2.4.11 Relative pronouns: syntactic-function detail beyond prior corpus coverage (p.119–125)

The basic `que`/`quien(es)`/`el cual` forms are already in `006`; this source adds a fuller account of
**the specific syntactic functions each relative can realize within its own adjective clause** — sujeto,
complemento directo, complemento indirecto, complemento circunstancial, complemento de régimen,
modificador del sustantivo/adjetivo, atributo — illustrated one function at a time for both `que` and
`quien(es)` (p.122, 124).

- **`que`: core properties.** Atonic, invariable in gender/number; antecedent may be explicit or implicit
  (when implicit and known/generic, `que` must be preceded by the matching article, which nominalizes the
  whole adjective clause: *La mujer que viene es mi madre* → *La que viene es mi madre*).
- **`lo que`.** When `lo` precedes relative `que`, the true antecedent is the neuter `lo` itself (acting as
  head of the noun phrase), not an implicit noun — though the source notes some grammarians instead treat
  this `lo` as a nominalizing neuter article.
- **Relativo complejo vs. artículo sustantivador.** See vocabulary entries. Key test: if a noun could fit
  between the article and `que`, it's an artículo sustantivador configuration, not a true complex relative.
- **`lo que` as "cuánto."** When equivalent to `lo cual` or to `cuánto`, `lo que` is a complex relative
  (ex. *No sé lo que me cuesta* = *No sé cuánto me cuesta*).
- **Norma box — preposition placement before `que`.** When the antecedent is a temporal noun not itself
  needing a preposition, `en` before relative `que` is optional (*El año (en) que te conocí*); when the
  antecedent's own preposition is required, it's obligatory before the relative too (*El momento en que te
  conocí*, never `*el momento que te conocí`). Also optional when the antecedent already carries the same
  preposition in a restrictive clause (*Con la chica (con) la que salgo...*). But obligatory in an
  emphatic cleft construction with `ser`, even though Hispanic America frequently drops it there (*Fue por
  Juan por el que me enteré*, vs. the Hispanic-American-common `*fue por Juan que me enteré`).
- **`quien`/`quienes`.** Tonic variant with number but not gender; frequently has an implicit, indefinite
  antecedent (*Quien mal anda, mal acaba*). Norma box: `quien` must agree in number with its antecedent
  (`*a quien` for a plural antecedent is wrong; must be `a quienes`), and its antecedent must be a person
  (or personified animal/thing) — `*Fue el poste quien repelió el balón` is wrong; must be `el que`.
- **`el cual`/`la cual`/`lo cual`/`los cuales`/`las cuales`.** Always tonic; article is fused into one
  grammatical unit with the pronoun; varies in gender and number; can appear without article/atonically
  only in concessive constructions (*Sean cuales (las que) sean sus razones...*); can only appear without
  a preposition in *explicative* (non-restrictive) clauses (*He vendido mi coche, el cual no podía correr
  más de cien kilómetros por hora*); in specificative clauses it requires a preceding preposition; can be
  preceded by `todo/-a/-os/-as`; can never head a clause without an explicit antecedent (`*El cual quiera
  dinero...` is wrong — must be *El que quiera dinero...*).
- **Norma box — `que` and `el cual` are not interchangeable.** Substituting `el cual` for a bare,
  non-prepositional `que` in a specificative clause breaks the sentence (`*los libros los cuales he leído`
  is wrong for *los libros que he leído*), nor are they interchangeable when `el cual` has demonstrative/
  personal value or when the clause is headed by `el/la/lo que` itself.

#### §2.4.12 Interrogative and demonstrative pronouns (p.126–127) — brief supplement

Core forms (`cuál(es)`, `quién(es)`, `qué`, `cuánto/-a/-os/-as`) are standard and already covered
elsewhere in the corpus; new here: the **"pronombres interrogativos del discurso"** category (forms that
act as pronouns only when their noun is omitted in context — `qué`, `cuánto/-a/-os/-as`), the
interrogative-exclamative double function (vocabulary entry above), and the Norma box flagging `*cuálo`/
`*cuála` as vulgar/dialectal (vocabulary entry above) plus two common errors: using `qué` where an adverb
(`[a]dónde`) is needed, and dropping a preposition the verb requires in a follow-up question.

#### §2.4.13 Indefinite pronouns (p.128–129) — brief supplement

Distinguishes **pronombres indefinidos propiamente dichos** (`nadie`, `alguien`, `nada`, `algo`,
`quienquiera`, `quienesquiera` — never combine with a noun) from **pronombres del discurso** (determiners
like `mucho`, `otro`, `ninguno`, `cierto` that become pronouns only when used without an accompanying
noun in context). New points beyond basic negation-word coverage already in the corpus: `nadie`/`nada`
don't need a second negator when preverbal, but do when postverbal (*Nadie quiso comer* vs. *No quiso
comer nada*); the `para nada` negative locution (vocabulary entry); partitive `de nada` (*Aquí no falta de
nada*); `algo`/`nada` can themselves function as adverbs rather than pronouns depending on position
(*No te quiero nada* = adverbial); `todo` as pronoun is compatible with atonic object clitics (*Lo sé
todo*, *Los vi a todos*) and with a partitive `de` (*Aquí hay de todo*); `cada uno`/`cada cual` are also
classed as indefinite pronouns.

---

#### §2.5 Terminología — tense-name equivalence table (p.133)

High-value reference table: this source gives the full cross-walk between its own (RAE-style) tense
names and the Bello/Spanish-American grammatical tradition's names, for both indicative and subjunctive,
plus alternate terms for several verb-class categories. See the Bello-terminology vocabulary entries
above (`copretérito`, `antepresente`, `antecopretérito`, `antepretérito`, `pospretérito`,
`antepospretérito`) and the terminology-variant entries for `unipersonal`/`impersonal`,
`pronominal`/`pseudorreflexivo`, `perfectivo`/`desinente`, `imperfectivo`/`permanente`, and
`copulativo`/`atributivo`. Non-personal verb forms are also called "formas nominales," "verboides," or
"formas derivadas" in other grammars, per this source.

#### §2.5.1 The verb: general characteristics (p.134)

- **Form.** Verb = raíz (lexeme) + desinencias; desinencias encode tiempo, modo, aspecto, persona,
  número, frequently several amalgamated into one ending (worked example: *cantábamos* = *cant-* (root) +
  *-á-* (1st-conjugation theme vowel) + *-ba-* (past tense + imperfective aspect + indicative mood,
  amalgamated) + *-mos* (1st person + plural, amalgamated)). Occasionally the amalgamation is total and
  not analyzable into separable morphemes at all (*soy* fuses the root of *ser* with 1st-sg-present-
  indicative meaning inseparably).
- **Function.** The verb is always the syntactic nucleus of the predicate; may or may not take
  complements.
- **Simple vs. compound forms (§2.5.1.2).** Simple forms = root + desinencias directly (presents,
  imperfects, indefinido, simple futures, simple conditional, imperative forms, simple infinitive/
  gerund/participle). Compound forms = auxiliary `haber` (carrying the desinencias) + participle of the
  main verb (perfects, pluscuamperfectos, pretérito anterior, compound futures, compound conditional,
  compound infinitive/gerund).

#### §2.5.2 Non-personal forms: the infinitive (p.136–137)

- Non-personal forms (infinitive, gerund, participle) carry no person, number, or mood meaning; they only
  oppose each other by aspect/tense.
- Infinitive formed with `-r` via the theme vowel: `-a-` (1st conj.), `-e-` (2nd conj.), `-i-` (3rd
  conj.). Simple and compound forms exist (*cantar* / *haber cantado*); the compound infinitive always
  indicates anteriority to a given moment, and also carries a recriminating-apelative use (*¡Pues haberlo
  dicho!*, "You should've said so!").
- Infinitives share traits with nouns (can take determiners/modifiers, some fully nominalize with number
  opposition: *el deber/los deberes*, *el andar/los andares*) and with verbs (can take the full range of
  complements and an explicit subject, and head their own non-finite clauses). Can be preceded by a
  preposition (*Al arrancar...*, *Por no hablar...*, *De saberlo...*).
- ATENCIÓN box: atonic object clitics complementing an infinitive always postpose and fuse into one
  graphic word with it, however many clitics (*preguntárselo*).
- Norma box: the infinitive cannot function as the main (finite) verb of a sentence — a frequent error in
  public announcements (`*Comunicar, señoras y señores, que...` should be *les comunicamos...*).

#### §2.5.3 Non-personal forms: the gerund (p.138–139)

- Formed with `-ndo` via theme vowel: `-a-` (1st conj.), `-ie-` (2nd and 3rd conj., both). Simple and
  compound forms exist.
- Shares traits with adverbs (its most proper function is complemento circunstancial: *Salí corriendo*)
  and with verbs (can take the full range of complements and an explicit subject: *Estando yo dormido,
  llegaron ellos*). Can also act adjectivally, complementing a noun as a kind of predicative (*Vi una hoja
  cayendo del árbol*), including in captions/non-sentential text (*El Papa besando suelo español*).
- Aspectual meaning with imperfective verbs: duration — the action viewed in its unfolding, not its start
  or end (*Vimos una mosca volando*); as a consequence, the simple gerund marks simultaneity with another
  action (*Leyendo el periódico, me quedé dormido* = *Mientras leía...*).
- The gerund cannot be preceded by a preposition, with one archaic exception: `en` + gerund for immediacy
  (*En acabando la música, salió* = *En cuanto acabó la música, salió* — flagged as archaic today).
- Some gerunds admit the `-ito` diminutive (*callandito*, *andandito*).
- Norma box — incorrect gerund uses: (1) the "gerundio de posterioridad" is non-standard when the gerund
  is simple, since simple gerund always marks simultaneity, not sequence (`*El coche volcó muriendo sus
  tres ocupantes` should be two separate clauses) — only acceptable when the posteriority is near-
  immediate (*Salió dando un portazo* is fine); (2) a gerund cannot complement a non-action-verb's noun as
  if a restrictive relative clause (`*Se necesita secretaria sabiendo inglés` should be *que sepa inglés*;
  similarly for *conteniendo*/*regulando* → *que contiene*/*que regula*); (3) gerunds cannot complement a
  noun as indirect object, complemento circunstancial, or complemento de régimen (`*Di una limosna a un
  hombre pidiendo en la acera` should be *que pedía*).

#### §2.5.4 Non-personal forms: the participle (p.140–141)

- Formed with `-do` via theme vowel: `-a-` (1st conj.), `-i-` (2nd and 3rd conj., both). Some irregular
  verbs instead use `-to`/`-cho`/`-so` (*escrito*, *dicho*, *impreso*).
- **Double participles.** A set of verbs (*atender, despertar, freír, imprimir, proveer, prender, soltar,
  teñir, torcer*...) have both a regular and an irregular participle (*atendido/atento*,
  *despertado/despierto*, *freído/frito*, etc.). ATENCIÓN box: when a verb has both, the **irregular form
  normally functions only as an adjective, never as a true verb form** (`*he soltado` is fine but
  `*he suelto` is not), **except** for *freír*, *proveer*, and *imprimir*, whose irregular participles can
  function as *either* adjective or verb (*he freído* / *he frito*, both valid; though the irregular
  *frito* is now more common than regular *freído*, which feels archaic). With regular+irregular pairs,
  only the irregular form is used adjectivally (*Comí patatas fritas*, *Iba provisto de víveres*).
- Shares traits with adjectives (gender/number agreement with the noun it modifies; gradable with
  degree adverbs or the `-ísimo` superlative suffix: *una niña recién nacida*, *preocupadísimo*) and with
  verbs (participates in compound tenses and passive constructions and other verbal periphrases: *he
  venido*, *fueron vistos*, *te tengo dicho*; can head an absolute clause with its own subject: *Muerto el
  perro, se acabó la rabia*; in compound tenses/periphrases takes the complements proper to the base verb;
  transitive-verb participles can take a complemento agente: *La carta fue firmada por todos*).
- Transitive-verb participles usually carry passive meaning (*un libro muy leído*), with exceptions where
  the sense is instead active/experiential (*un hombre muy leído* = "a well-read man," i.e. "who has read
  a lot," not "who has been read a lot"; *una persona considerada* = "who is considerate of others," not
  "who is considered [by others]"; *un hombre entendido* = "knowledgeable," i.e. "who understands").

#### §2.5.5 Morphemes of person, number, and mood (p.142–143)

- Three persons, tied to the roles of the speech act (1st = speaker's yo, 2nd = addressee's tú, 3rd =
  neither). Person is usually amalgamated with number in a single desinence (*-mos* = 1st person +
  plural); regular verbs mostly use a fixed desinence per person (*-is* = 2nd pl.; *-mos* = 1st pl.).
  Verb number always agrees with the oracional subject.
- **Three moods: indicativo, subjuntivo, imperativo.**
  - *Indicativo*: real/objective content the speaker presents as certain; the only mood compatible with
    interrogative sentences (*¿Cantas?*/*¿Cantaste?* are fine; `*¿Cantes?`/`*¿Hayas cantado?` are not).
  - *Subjuntivo*: desires, possibilities, unrealities — the speaker presents the content as fiction
    (*¡Ojalá llueva!*, *Tal vez me case*). Beyond this core semantic difference, subordination context
    also governs mood choice: assertive predicates (*creer, pensar, estar seguro*) take indicative when
    affirmative but subjunctive when the assertion itself is negated (*Creo que he ganado* vs. *No creo
    que hayas ganado*); factive predicates and predicates of desire/request/command (*lamentar, rogar,
    pedir, desear*) always take subjunctive in their complement regardless of polarity (*Lamento que hayas
    perdido*; `*lamento que habéis perdido` is wrong); finality connectives and the *inespecificidad* of
    indefinite `un/una` also force subjunctive (*Para que seas feliz*; *Busco un libro que sea
    interesante*).
  - *Imperativo*: belongs exclusively to the conative/apelative function — giving orders/requests to the
    addressee (*Ven*, *Callad*, *Mira*). Can never appear in subordinate clauses except reported direct
    speech (`*Me dicen que estad contentos` is wrong; must be *Me dicen que estéis contentos*).
  - ATENCIÓN box: some grammarians treat the simple and compound conditional as a fourth mood ("potencial"),
    since they express doubt/possibility.

#### §2.5.6 The imperative mood (p.144–145)

- **Morphological-and-syntactic imperative** (familiar/tuteo register): 2nd-sg. has a zero desinential
  mark (*canta*, *ven*); 2nd-pl. uses `-d` (*cantad*, *venid*). ATENCIÓN: no 3rd-person imperative form is
  justified morphologically or syntactically (`*cante (él)`/`*canten (ellos)` are simply present-
  subjunctive forms, and imperative — being strictly conative — can by definition only target a 2nd
  person); 2nd-pl. in `-d` is exclusive to peninsular Spanish.
- **Purely syntactic imperative** (respect/usted register, and 1st-pl.): defined by the rule that atonic
  object clitics must *follow* a true imperative verb — forms like *démelo (usted)*, *dénmelo (ustedes)*,
  which morphologically coincide with present subjunctive, count as imperative precisely because of this
  clitic-postposition behavior; this same logic licenses a 1st-person-plural imperative (*digámoselo*,
  *separémonos*), and extends to the `-se` passive/impersonal construction when postposed (*Rómpase en
  caso de incendio*).
- ATENCIÓN: *ir*/*irse* have two competing 1st-pl. syntactic-imperative forms, *vayámonos* and the far
  more common *vámonos*.
- **Norma box — imperative usage errors:** (1) pronouns can never precede the respect/syntactic imperative
  (`*Me dé una aspirina` → *déme una aspirina*); (2) 1st-pl. syntactic imperative drops final `-s` before
  `-nos`/`-se` (*marchémonos*, not `*marchémosnos`); (3) no negative imperative exists in Spanish at all —
  negative commands always use subjunctive (`*no hablad` → *no habléis*); (4) colloquially but
  incorrectly, an infinitive-looking `-r` form is substituted for 2nd-pl. familiar imperative (`*Callar,
  niños` → *callad, niños*); (5) for pronominal/reflexive verbs, the familiar-plural imperative drops the
  `-d` before the clitic rather than keeping both consonants (*callaos*, not `*callaros`/`*callados`;
  *poneos*, not `*poneros`/`*ponedos`) — the lone exception that keeps the `-d` is *irse*'s 2nd-pl. form
  *idos* (not `*íos`); (6) the bare infinitive does validly carry imperative force when preceded by `a` or
  when addressing a general public rather than a specific interlocutor (*Niños, a dormir*; *Girar a la
  derecha*, a traffic-sign instruction; *No tocar, peligro de muerte*); (7) `*oyes`/`*ves` are vulgar for
  the correct imperatives `oye`/`ve`.

#### §2.5.7 Aspect and tense (p.146–147)

- **Aspect**: perfective (action presented as finished) vs. imperfective (not finished), independent of
  tense; often amalgamated into the same desinence as tense/mood (*cantaba*'s `-ba` = past + imperfective
  + indicative, simultaneously). All compound conjugation forms, plus the pretérito indefinido, mark
  perfective aspect; every other simple form is imperfective. Certain verbal periphrases also mark aspect
  (cross-ref §2.5.20, outside this chunk).
- **Tense with reference to the speaker** ("ahora" as a fuzzy zone, not a point) vs. **tense with
  reference to another verbal action** (simultaneidad/anterioridad/posterioridad relative to another
  event, not to the speaker) — the latter applies in both indicative and subjunctive, though more
  confusedly/imprecisely in the subjunctive.
- **§2.5.7.3 full tense-and-mood inventory**: indicative has 9 simple/compound tenses (presente,
  pretérito perfecto, imperfecto, pluscuamperfecto, indefinido, anterior, futuro imperfecto, futuro
  perfecto, condicional simple, condicional compuesto); subjunctive has 6 (presente, pretérito perfecto,
  imperfecto, pluscuamperfecto, futuro imperfecto, futuro perfecto) — this is a clean enumeration, useful
  as a checklist, though the paradigm forms themselves are already tabulated at length in `007`/`008`.

#### §2.5.8 Present and imperfect indicative: usage values (p.148–149)

A pragmatics-of-tense-use catalogue substantially deeper than the "Practice Makes Perfect" series'
drill-oriented coverage. **Present indicative values:** presente inmediato (near-future sense: *Ahora
mismo subo*), presente habitual (repeated/ongoing action spanning the speaker's temporal zone: *Todos los
días voy al colegio*), **presente gnómico** (see vocabulary), **presente histórico** (see vocabulary),
**presente por futuro** (see vocabulary), presente con valor imperativo (exclamatory presente used as a
command: *¡Ahora mismo te vas de aquí!* = *Vete de aquí*). **Pretérito imperfecto values:** base meaning =
an action prior to the speaker's "now," viewed mid-course rather than at its end (contrast with
indefinido); valor reiterativo (supported by context words like *siempre*, *a veces*, *todos los días*);
valor de conato/disposición ("was about to," e.g. *Ya me levantaba cuando oí la explosión*); as a
colloquial variant of the simple conditional in the apodosis of a conditional sentence (*Si me tocara la
lotería, me compraba una casa* = *...me compraría...*); valor de cortesía with verbs like *querer*,
*poder* (*Quería pedirle un favor* ≈ *Quiero pedirle un favor*, softened) — the source notes this
courtesy use isn't limited to those two verbs; valor de fantasía in children's pretend-play (*Yo era un
príncipe y tú un dragón*); **valor de cierre** and **futuro en el pasado** (see vocabulary entries).

#### §2.5.9 Other indicative preterites (p.150–151)

- **Pretérito indefinido.** Events in a past zone presented as finished; the finishedness is what
  distinguishes it from the imperfecto (*Juan estaba ayer en Ávila* vs. *Juan estuvo ayer en Ávila* — the
  first doesn't consider whether the "being there" ended, the second presents it as completed). Preferred
  tense (with presente histórico) for narration (*Ayer me levanté a las ocho, desayuné, salí a la calle y
  cogí un taxi...*).
- **Pretérito perfecto.** Past events connected to the speaker's present temporal zone; difference from
  indefinido illustrated with *Este año lo hemos pasado mal* (this year, still ongoing) vs. *El año pasado
  lo pasamos mal* (a finished past year). The connection to "now" can be purely psychological/emotional
  rather than strictly temporal (*Hace tres años que ha muerto mi padre*, where the death's effects still
  resonate for the speaker, vs. the more neutral *Hace tres años que murió mi padre*); this same
  present-relevance logic explains its use for a near-future (*En un minuto he acabado*). **Regional
  distribution**: see vocabulary entry (Galicia/Asturias/Canarias/Hispanoamérica).
- **Pretérito pluscuamperfecto.** Always needs another action/temporal reference point, relative to which
  it marks anteriority (*Cuando tú llegaste, yo ya había salido*).
- **Pretérito anterior.** Marks anteriority to another past action with an added sense of immediacy (*En
  cuanto lo hubo dicho, se marchó* = *Nada más decirlo...*); almost always co-occurs with specific
  connective phrases (*en cuanto, después que, luego que, así que, no bien, cuando, tan pronto como*);
  explicitly flagged as rare/archaic today, replaced by indefinido or pluscuamperfecto in ordinary use.

#### §2.5.10 Futures and conditionals: usage values (p.152–153)

- **Futuro imperfecto**: base future-event meaning; valor de probabilidad/potencial (*Ahora serán las
  cinco* ≈ *Posiblemente sean las cinco*); valor imperativo in certain (often negative) commands (*No
  matarás*); valor intensificador in exclamatives with suspended intonation, turning the future into an
  intensifier of a negative quality/insult (*¡Será sinvergüenza...!*, *¡Tendrá cara...!*).
- **Futuro perfecto**: future-with-anteriority-to-another-action (*Cuando tú vengas, yo ya habré limpiado
  la casa*); also carries the probability/potential value, sometimes blended with the anteriority sense
  (*Si el suelo está mojado, habrá llovido*).
- **Condicional simple**: normally marks an action posterior to another action; also expresses potential
  modality (*Serían las cinco cuando llegó* ≈ *Probablemente eran las cinco...*); also a courtesy variant
  (*¿Le importaría darme fuego?*, *Deberías ayudarle*).
- **Condicional compuesto**: action posterior to another but from a past vantage; compatible in discourse
  with pluscuamperfecto subjunctive or compound infinitives paired with the simple conditional, which
  itself pairs with imperfect subjunctive (*Si hubieras venido, te lo habría dado*; *En el caso de
  haberlo sabido, te lo habría dicho*).
- **Norma box — conditional in conditional/concessive subordinate clauses.** Using the conditional tense
  inside the prótasis of a conditional or concessive sentence is non-standard (`*Si vendrías, te lo
  diría` → *si vinieras...*; `*Aunque lo habría sabido, no te lo hubiera dicho` → *aunque lo hubiera
  sabido...*); likewise substandard after subordinating `que` where imperfect subjunctive is required
  (`*Me pidieron que tendría paciencia` → *que tuviera paciencia*). See vocabulary entry for this
  pattern's regional attestation (País Vasco).

#### §2.5.11 Subjunctive temporal forms (p.154–155)

- Subjunctive tense meaning is less precise than indicative's: the same form can carry present, past, or
  future value depending purely on context, not on the form itself (presente subjunctive: *Tal vez esté
  mi padre en casa* [present] vs. *Tal vez venga mi padre* [future]; pretérito imperfecto subjunctive can
  likewise read as past, present, or future, illustrated three ways).
- In subordination, subjunctive forms foreground anteriority/simultaneity/posteriority relative to the
  main verb rather than absolute tense (*Me dijeron que me casara* = posteriority to *dijeron*, regardless
  of whether the marrying ever actually happened; *Me gustaría que estuviera mi madre en casa en este
  momento* = simultaneity; *Lamento que te hayan suspendido* = anteriority).
- In conditional/concessive sentences specifically, pluscuamperfecto subjunctive marks irreality and
  imperfecto subjunctive can mark possibility (*Si hubieras aprobado, te hubiera (habría) comprado la
  moto* [irrealidad] vs. *Si aprobaras, te compraría la moto* [posibilidad]).
- **Futuro de subjuntivo** is explicitly archaic, surviving mainly in set sayings/proverbs and
  juridical-administrative register (*Adonde fueres, haz lo que vieres*); in current use its old values
  are expressed instead by: presente subjuntivo or imperfecto subjuntivo (for futuro imperfecto de
  subjuntivo), and pluscuamperfecto subjuntivo (for futuro perfecto de subjuntivo).
- **ATENCIÓN — `-ra` vs. `-se` imperfecto subjuntivo forms.** Generally equivalent, *except*: (1) when
  `-ra` is used with pluscuamperfecto-indicativo or pretérito-indefinido value (see the Norma box and
  vocabulary entry: a León/Galicia dialectalism, also now common journalistically with indefinido value,
  where `-se` in the same role is markedly worse: `*El que fuese presidente del Gobierno...` is flagged
  far more rejectable than the already-nonstandard `-ra` equivalent); (2) in courtesy uses with *querer*/
  *deber*, only `-ra` is possible, never `-se` (*Quisiera (querría) pedirle un favor* — `*quisiese` would
  not work here). Also noted as archaic-but-not-incorrect: using `-ra` in a conditional sentence's apodosis
  in place of the simple conditional (*Si lloviera, lo agradeciera muchísimo* — today: *...lo
  agradecería...*).

#### §2.5.12 Regular conjugation: overview (p.156)

Just the three-conjugation inventory (`-ar`/`-er`/`-ir`, with *amar*/*temer*/*partir* as the book's model
verbs) — full paradigm tables are cross-referenced to §2.5.16, outside this chunk's range, and are already
exhaustively covered by `007`/`008`/`014`, so not re-extracted. New here is a **Norma box of standard-
register corrections**: 2nd-sg. pretérito indefinido ends in `-ste`, never `-stes` (`*dijistes` →
*dijiste*); `*supon`, `*dijon`, `*vinon` (for *supieron/dijeron/vinieron*) are flagged explicitly as
dialectal and vulgar, outside cultured Castilian norms; `*cantemos`/`*acabemos` as substandard variants of
indefinido *cantamos*/*acabamos* (distinct from the subjunctive/imperative forms that happen to look
identical) are also flagged vulgar.

#### §2.5.13 Root irregularities: a systematic mechanism typology (p.157)

A verb is irregular, per this source, whenever it shows any phonic variation in its root or desinences
relative to the regular model verbs. The root-irregularity mechanisms are explicitly enumerated as a
closed taxonomy — more systematic than the case-by-case irregular-verb lists already in `007`:

1. **Diphthongization** — tonic `-e-`/`-i-` → `-ie-`; tonic `-o-`/`-u-` → `-ue-` (*pensar→pienso*,
   *adquirir→adquiero*, *soltar→suelto*, *jugar→juego*).
2. **Cierre de timbre vocálico** — see vocabulary entry (*pedir→pido*, *dormir→durmamos*, *caber→quepo*).
3. **Consonant change** (*hacer→hago*, *saber→supe*).
4. **Consonant addition** (*conocer→conozco*, *traer→traigo*) — ATENCIÓN box: in *conozco*, *merezco*
   etc. the added consonant is phonemically `/k/` spelled `c`, not `z` (which is just the graphic variant
   of interdental `/θ/`), a spelling-vs-phonology clarification.
5. **Vowel-and-consonant addition** (*andar→anduve/anduviera*, *estar→estuve/estuviera*).
6. **Suppression of an element** (*hacer→ha(ce)ré*, *poner→pon(e)*).
7. **Suppression of a vowel + addition of a consonant** (*poner→pon(e)dré*, *valer→val(e)dré*).
8. **Multiple roots** — verbs with several distinct suppletive roots: *ir* (*i-*, *v-*, *fu-*) and *ser*
   (*s-*, *e-*, *fu-*, *er-*).

ATENCIÓN box: purely graphic changes with no phonic change are explicitly *not* counted as
irregularities (*vencer→venzo*, *regar→regué*); an intervocalic `-i-` hardening to `y` is also classed
this way (*leer→*leió→leyó*, *creer→*creió→creyó*); also notes accent-pattern-only irregularities
(contrast regular *auxilio/auxilias/auxilia*, *concilio/concilias/concilia* with irregular
*ansío/ansías/ansía*, *chirrío/chirrías/chirría*, *rocío/rocías/rocía* — same spelling pattern, different
stress).

#### §2.5.14 Desinential irregularities and irregular-conjugation norms (p.158–159)

- **Perfectos fuertes.** See vocabulary entry.
- Some verbs add `-y` to the 1st-sg. present-indicative ending, and to *haber*'s 3rd-sg. (*doy, soy,
  estoy, voy, hay*).
- Irregular participles with `-to`/`-cho`/`-so` endings (*escrito, roto, dicho, hecho, impreso*).
- **Norma box — specific irregular-verb corrections:** `satisfacer` conjugates like `hacer` (`*satisfací`,
  `*satisfaciera` are wrong; correct: *satisfice*, *satisficiera*); `prever` conjugates like `ver`
  (`*preveer`, `*preveyó` are wrong; correct: *prever*, *previó*); `bendecir`/`maldecir` conjugate like
  `decir` **except** in the future, conditional, imperative, and participle, which are regular
  (*bendeciré, bendeciría, bendice (tú), bendecido* — not the `decir`-pattern *diré/diría/di/dicho*).
- **Norma box — vulgar irregular-verb forms:** `*apreto, *frego, *aprete, *fregue` for correct *aprieto,
  friego, apriete, friegue*; the gerund of *ir* is *yendo*, and `*iendo` is vulgar; `*quedré`/`*quedría`
  are very vulgar for *querré*/*querría*.
- §2.5.14.2 previews the book's irregular-verb conjugation tables (outside this chunk's range) and flags
  two cross-cutting rules worth noting: `-uar` verbs form hiatus (tonic `ú`, with written accent) except
  those ending in `-cuar`/`-guar`, which always diphthongize (*adecuo*, *evacuo*, *averiguo* — though the
  hiatus variants `*licúo` etc. are also noted as being in normal use despite the rule); and that some
  double-participle verbs have a non-verbal second participle (purely adjectival, e.g. *suelto*,
  *despierto*) which the book's irregular-verb table does not track as a true second verbal participle.

---


---

## Spanish — Established Vocabulary/Grammar: Gramática didáctica del español, Chunk D (verb classification tail, el adverbio, las preposiciones)

**Source:** Leonardo Gómez Torrego, *Gramática didáctica del español*, Ediciones SM (Brazilian-licensed
edition, São Paulo, 2005), ISBN 85-7675-066-X. Metalanguage is Spanish itself; glosses below are
supplied by the extracting agent. Vision-read (no text layer) via `pdftoppm` renders at 150 dpi
(one 300 dpi re-render for a degraded page).

**Scope covered:** PDF pages 95–115 of the source file, which — per the empirically-verified
two-printed-pages-per-spread formula (`printed_left = 2×(PDF_page−1)`) — correspond to **printed
pages 188–229**. This picks up immediately after chunk C's coverage of §02.5 "El verbo" overview
material and covers:
- §02.5.17–02.5.22 (pp. 188–199): the tail of **el verbo** — verb classification by mode of action
  and syntax, perífrasis verbales (all three lessons), and the *ser* + participio / passive-voice
  construction.
- pp. 200–201: ejercicios (drills) — skipped per coverage rule, no new content.
- §02.6.1–02.6.6 (pp. 202–213): the complete **el adverbio** chapter.
- pp. 214–217: ejercicios + chapter-transition pages — skipped/noted (see below).
- §02.7.1–02.7.4 (pp. 218–227): the complete **las preposiciones** chapter.
- pp. 226–229: ejercicios (drills, skipped) and the opening title page of §02.8 **las conjunciones**
  (content begins on the next PDF page, outside this chunk's assigned range — left for the next
  chunk).

**Non-redundant-supplement scope decision.** Per dispatch instructions, briefly skimmed
`014_practice_makes_perfect_complete_spanish_grammar.md` for baseline comparison before extracting.
014's own coverage note confirms it only treats adverbs/prepositions/conjunctions incidentally,
inside its subjunctive-mood and indefinite/negative-word sections (a handful of adverb-clause
conjunctions, degree adverbs like *algo/nada*, a few modal adverbs) — it has **no systematic
classification of adverbs or prepositions at all**. The existing 15-file Spanish corpus as a whole
has no dedicated adverb or preposition chapter. This chunk's content is therefore almost entirely
new, non-redundant territory, exactly as the dispatch anticipated — **kept in full**, nothing
skipped as redundant except the verb-classification material that substantially overlaps with
standard transitive/intransitive/reflexive coverage already present in 005/006/014 (noted inline
below where it applies, kept anyway because this source's treatment — e.g. *bipersonales*,
*unipersonales* as a formal subclass of *defectivos*, the four-way perfectivo/imperfectivo +
modo-de-acción vs. aspecto distinction — is more systematic than anything in the existing corpus).

**Marginalia found/excluded.** The recurring institutional library ownership stamp previously
confirmed by sibling subagents appears once in this chunk's range, bottom-right corner of printed
page 223 (PDF page 112, right half): "ESCOLA IRMÃ ELIZABETH — ENSINO DE 1º GRAU — SEE-PE — INSC.
708010 — BIBLIOTECA LUIZ CONRADO DE LORENA E SÁ — SERRA TALHADA-PE". Confirmed print/rubber-stamp
ink over the printed page, not handwritten — excluded from extraction as source content per the
vision-reading guard (it is institutional marginalia, not book content, regardless of medium).

**PDF-scan gotcha found (new, not previously documented for this book).** PDF page 102 (printed
202–203) is a **severely degraded duplicate scan of the same leaf** as PDF page 103 (printed
204–205) — both pages open with the identical §2.6.1 "El adverbio" / "Características formales del
adverbio" text (same three bullets verbatim: palabras tónicas / palabras invariables / significado
léxico pleno). Page 102's scan is extremely low-contrast (near-invisible printed text, confirmed
via percentile contrast-stretching and a mirror-flip test that ruled out backside bleed-through as
the cause — it is simply a very faint exposure of the same content, not a different page). Because
page 103 renders cleanly and carries identical content, page 102 was treated as a redundant
duplicate and not separately force-extracted — no content was lost. The same faint-duplicate-preview
pattern recurred twice more at smaller scale: PDF page 109's right half (printed 217, "02.7 Las
preposiciones" chapter-opening text) duplicates page 110's clean §2.7.1 content, and PDF page 115's
right half (printed 229, "02.8 Las conjunciones" chapter-opening text) previews content whose clean
version falls in the next chunk's range. Worth flagging for other subagents working this book: a
chapter-opening spread sometimes appears once very faintly (as a kind of divider/preview) and then
again cleanly on the very next leaf — check before spending extraction effort on a badly-scanned
chapter-opening page.

**Vision Reading Confidence:** `verified` for all entries below except where flagged — nearly all
of this chunk's content was read from cleanly legible, well-contrasted printed pages (102/204–227
onward render at full legibility). No `low_confidence` entries were needed.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| verbo perfectivo (desinente) | perfective verb — denotes conclusion/endpoint of the action (e.g. *morir, llegar, entrar*) | grammatical term | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.17.1 p. 188; contrasted with *modo de acción* (lexical) vs. *aspecto* (grammatical/desinential) |
| verbo imperfectivo (permanente) | imperfective verb — denotes duration (e.g. *pasear, cantar, amar*) | grammatical term | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.17.1 p. 188; a perfective verb used in an imperfective-aspect tense can shift meaning (*disparaba* = reiterative; *llegaba/se moría* = imminent/about-to) |
| verbo defectivo | defective verb — lacks a complete conjugation paradigm (e.g. *abolir* only in -i- forms; *soler* has no future/conditional; *balbucir* lacks -zc- forms) | grammatical term | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.17.2 p. 188 |
| verbo unipersonal (impersonal) | unipersonal verb — conjugates only in 3rd person singular (weather verbs: *tronar, nevar, granizar, relampaguear, amanecer, atardecer, anochecer, haber*) | grammatical term | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.17.2 p. 188; a figurative/metaphorical use can break the unipersonal restriction: *Amanecimos en Madrid*, *Llueven las críticas* |
| verbo bipersonal | bipersonal verb — conjugates only in 3rd person singular and plural because its meaning is incompatible with personal subjects (*suceder, acontecer, acaecer, atañer*) | grammatical term | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.17.2 p. 189; subclass of defectivo distinct from unipersonal, not previously captured in existing corpus |
| verbo pronominal (reflexivo/pseudorreflexivo) | pronominal verb — always conjugated with its clitic pronoun, which carries no nominal function (*arrepentirse, quejarse, vanagloriarse* = pronoun-only; *dormirse/dormir, marcharse/marchar* = optional, with meaning shift) | grammatical term | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.17.3 p. 189; *Se está durmiendo* (incoative: beginning to sleep) vs. *Está durmiendo* (durative: is sleeping) |
| *clasificar(se), recuperar(se), marchar(se)* (norma box) | error pattern: pronominal verbs used as non-pronominal, and vice versa | verb usage note | colloquial | — | contemporary (2005) | Spain (regional note on *marcho* for *me marcho*) | regional | grammar_reference | n/a | verified | Norma box p. 189: *solo clasifican los tres primeros* should be *se clasifican*; *el jugador recupera* should be *se recupera*; *marcho* for *me marcho* flagged explicitly regional; *no me recuerdo de* (should be *no recuerdo*) is the reverse error |
| verbo transitivo | transitive verb — takes a direct object; forms *oraciones transitivas* | grammatical term | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.18.1 p. 190 |
| verbo intransitivo | intransitive verb — no direct object; forms *oraciones intransitivas* | grammatical term | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.18.1 p. 190; many verbs normally one class can flip (*Comí patatas* [transitive] → *Comí a las tres* [intransitive]) |
| incautarse, cesar, dimitir, estallar, explotar, urgir, quedar | intransitive verbs used incorrectly as transitive (norma box) | verb usage note | colloquial | — | contemporary (2005) | Spain (press/cultured-sector use noted for *cesar*) | regional | grammar_reference | n/a | verified | p. 190; *cesaron al director* ("fired") now frequent even in educated press use despite being non-standard; *quedar* transitive (*me quedo tu libro*, *lo quedé en casa*) explicitly labeled dialectal |
| entrenar, suspender | transitive verbs used incorrectly as intransitive (norma box) | verb usage note | colloquial | — | contemporary (2005) | Spain | regional | grammar_reference | n/a | verified | p. 191; *los jugadores entrenan* / *he suspendido en matemáticas* flagged non-standard but "ya arraigados en el uso" (already entrenched) |
| verbo copulativo (atributivo) | copulative verb — links subject to an attribute; canonically *ser, estar, parecer* (also *ponerse, quedarse*, etc.) | grammatical term | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.18.2 p. 191; *ser*/*estar* are NOT copulative when they don't link an attribute (*El accidente fue ayer*, *Juan está en Madrid*) |
| verbo auxiliar | auxiliary verb — forms compound tenses (*haber*) or verbal periphrases; carries the desinences, selects no subjects/complements itself | grammatical term | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.18.3 p. 191; same verb can be auxiliary or full verb: *haber* in *había venido* / *ha de llover* (auxiliary) vs. *había poca gente* (full verb) |
| perífrasis verbal | verbal periphrasis — syntactic construction of 2+ verbs, at least one auxiliary, the last in a non-personal form (infinitive/gerund/participle), all forming one predicate nucleus | grammatical term | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.19.1 pp. 192–193; non-personal forms select subjects/complements, not the auxiliary; auxiliary-auxiliated union can be direct (*puede llover*) or via preposition (*empieza a llover*) or *que* (*tiene que llover*) |
| acabar de + infinitivo | perfective: completion of a process, or immediacy of a just-completed action | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.20 p. 194; negated form adds indecision nuance: *No acaba de decidirme* |
| dejar de + infinitivo | perfective: interruption of a process (not necessarily definitive) | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 194 |
| tener + participio | perfective: repeated action in the past (with indirect + direct object) | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 194; ex. *Te tengo dicho que te calles* |
| llegar a + infinitivo | perfective: culmination of a process | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 194 |
| ir a + infinitivo | incoative/ingressive: beginning or imminence of action; ALSO: inopportunity (with auxiliary in pretérito indefinido), astonishment/denial in exclamatives, and modal probability | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | pp. 194–195; *Me fueron a suspender cuando menos lo esperaba* (inopportunity); *¡Quién lo iba a decir!* (astonishment); *Juan va a haber salido* (probability) — four distinct meanings for one periphrasis, notable polysemy |
| estar para + infinitivo | incoative/ingressive: imminence | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 194 |
| estar a punto de + infinitivo | incoative/ingressive: imminence | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 194 |
| empezar a + infinitivo | incoative/ingressive: beginning | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195 |
| ponerse a + infinitivo | incoative/ingressive: beginning | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195 |
| echarse a + infinitivo | incoative/ingressive: beginning (abrupt) | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195; *El niño se echó a llorar* |
| explotar (romper) a + infinitivo | incoative/ingressive: abrupt beginning | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195 |
| soler + infinitivo | iterative/frequentative: frequency | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195 |
| volver a + infinitivo | iterative/frequentative: repetition | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195 |
| estar + gerundio | durative/progressive: action in transcourse | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195; NOT always a periphrasis — if the gerund is replaceable by *lo*, *estar* is the main verb (*La sopa está ardiendo → Lo está*) |
| andar + gerundio | durative/progressive: duration + frequency combined | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195 |
| seguir (continuar) + gerundio | durative/progressive | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195 |
| llevar + gerundio | durative/progressive | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 195; *Llevo pensándolo varios días* |
| tener que + infinitivo | modal: obligation/necessity (also: probability, in a different reading) | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.21.1 p. 196 |
| haber de + infinitivo | modal: obligation/necessity; also future-time meaning | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 196 |
| haber que + infinitivo | modal: obligation/necessity (impersonal) | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 196 |
| deber + infinitivo | modal: obligation — contrasted explicitly with *deber de* (norma box) | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 196; Norma box: *Pedro debe ser buen chico* = obligation vs. *Pedro debe de ser buen chico* = probability — a prescriptive distinction increasingly blurred in use |
| poder + infinitivo | modal: possibility/probability; also capacitación/permiso | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 196 |
| deber de + infinitivo | modal: probability | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 196 |
| querer + infinitivo | modal: possibility (meteorological use) | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 196; *Hoy quiere llover* |
| venir a + infinitivo | modal: approximation | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 196 |
| venir + gerundio | modal: approximation | periphrasis | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 196 |
| locución verbal (vs. perífrasis) | verbal locution — a fixed multi-word unit where ≥1 word is a verb, functioning as one predicate nucleus, but WITHOUT auxiliary/principal structure (unlike periphrasis); the whole unit selects subjects/complements; often reducible to one verb | grammatical term | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.21.3 pp. 196–197; examples: *caer en la cuenta, echar de menos, echar en cara, darse cuenta, tener en cuenta, hacer añicos, echar a perder (= estropear), dar de lado (= marginar)*; also *dejar(se) caer* (= tirar/tirarse) and lexicalized imperative-origin locutions *vete/vaya a saber* |
| caer (transitivo, dialectal) | non-standard transitive use of *caer* for *dejar caer* | verb usage note | regional | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Norma box p. 197: *Ten cuidado, no lo caigas* flagged dialectal/non-standard for *no lo dejes caer* |
| oración pasiva (ser + participio) | passive construction: subject(paciente) + ser+participio(predicate nucleus) + complemento agente (often implicit) | grammatical term | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.5.22 pp. 198–199; active↔passive conversion: agent complement → subject, verb loses *ser*, subject → direct object |
| ahí | there (bisyllabic, oxytone/aguda) | adverb (lugar) | core | — | contemporary (2005) | Spain (pronunciation norm) | — | grammar_reference | n/a | verified | Norma box §2.6.1 p. 204: must not be pronounced as monosyllabic/llana *[ái]* — correct is *ahí [a-í] está*, not *\*ahí [ái] está* |
| muy, tan, cuán | apocopated degree adverbs — complement ONLY adjectives or other adverbs, never anything else | adverb (cuantificador) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.6.1.3 p. 205 |
| medio | "half/partly" — complements ONLY adjectives or participles | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 205; ex. *medio tonta, medio muerta, medio dormida* |
| media (as adverb) | incorrect adverbial use of the feminine form *media* in place of invariable *medio* | adverb usage error | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Norma box p. 205: *\*María estaba media muerta* flagged incorrect for *medio muerta* |
| recién | "just/recently" — in Spain complements ONLY participles (*recién nacido/visto/llegada*); in Hispanoamérica also complements verbs in personal form (*recién salió, llegó recién, recién vino*) | adverb | regional | — | contemporary (2005) | Spain vs. Hispanoamérica (explicit split) | transnational | grammar_reference | n/a | verified | p. 205 — explicit dialectal split the source itself marks; high-value regional annotation |
| casi | "almost" — unusually flexible, can complement adjective (as cuantificador), sustantivo, numeral cardinal, indefinido, or verbo | adverb (cuantificador) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 205; *casi limpio/poeta/mil pesetas/todos/me caigo* — five distinct complement types for one word |
| adelante (as *\*alante*) | coloquial-vulgar deformation of *adelante*; "*alante*" is NOT a standard adverb | adverb usage error | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Norma box p. 205 |
| así | "like this/so" — modo adverb, but also cantidad (with gesture) and deseo adverb; adjectivizes before a noun | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.6.2.1 p. 206, §2.6.4.1 p. 210, §2.6.6.1 p. 213; *así de alto* (requires an accompanying hand gesture to be understood — a genuinely gesture-dependent construction), *Había así de gente*, *Así te parta un rayo* (deseo), *Una casa así gusta a cualquiera* (adjectivized) |
| harto | adjective ("fed up") vs. adverb (cuantificador, "quite/rather") | adjective/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.6.4.2 p. 211; *Estoy harto* (adj.) vs. *Es harto probable* (adv.) |
| regular | adjective ("regular/so-so") vs. adverb | adjective/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 211; *Una situación regular* (adj.) vs. *Estuvimos regular* (adv.) |
| mucho, poco, bastante, demasiado, más, menos, tanto, cuanto | determinativo indefinido / pronombre indefinido when nominal; adverb when complementing an intransitive verb or an already-complemented transitive verb | determiner/pronoun/adverb (triple category) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 211; *Hay mucho hielo* (determ.) / *Dinero, tengo mucho* (pron.) / *Te quiero mucho* (adv.) |
| todo | determinativo / pronombre / adverb | determiner/pronoun/adverb (triple category) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 211; *Todo hombre* / *Lo tengo todo* / *Estaban todo contentos* |
| bueno, seguro | adverbs of affirmation ONLY when meaning "affirmative/certainly"; otherwise adjectives | adjective/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 211; *—¿Quieres venir? —Bueno* / *Mañana llueve seguro* (adv.) vs. *Este jarabe es bueno* / *Estoy seguro de que...* (adj.) |
| según | adverb (rare, elliptical: *—¿Te parece caro? —Según...*) vs. preposition (*Según la ley...*) | adverb/preposition | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 211, cross-referenced again at §2.7.3.1 p. 222 |
| mejor, peor | adverbs ONLY as comparatives of *bien*/*mal*; otherwise adjectives | adjective/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 211; *Yo canto bien, pero tú mejor* (adv.) vs. *Alicia se compró el mejor coche* (adj.) |
| solo | adverb when = *solamente*; adjective in all other uses | adjective/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 211; *Tengo solo diez años* (adv.) vs. *Me siento solo* (adj.) |
| bajo | adverb / adjective / preposition / verb (four-way category, context-dependent) | adverb/adjective/preposition/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 211; *Habla más bajo* (adv.) / *Hombre bajo* (adj.) / *Bajo la mesa*, atonic (prep.) / *Bajo siempre las escaleras andando* (verb — from *bajar*) |
| qué (adverbial use) | interrogative-exclamative *qué* is an adverb only when it modifies an adjective or adverb | adverb/determiner/pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.6.6.1 p. 213; *¡Qué feliz soy!*, *¡Qué lejos está!* vs. determinative (*¿Qué libro es ese?*) or pronoun (*¿Qué comes?*) |
| aún | tonic (tilde) when temporal ("still/yet"); atonic (no tilde) when inclusive (= *incluso*/*también*, equivalent to *aun*) | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 213; *Aún no ha llegado* (temporal, tonic) vs. *Me lo dijeron mis primos y aun mis padres* (inclusive, atonic) |
| lo que (= cuánto) | relative sequence *lo que* functions adverbially when equivalent to *cuánto* | relative/adverbial locution | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 213; *No sabes lo que sufro* → *...cuánto sufro* |
| locución adverbial | fixed multi-word unit functioning as a single adverb (e.g. *a oscuras, de pronto, desde luego, sin ton ni son, a lo mejor, tal vez, puede que, habla de veras, de verdad, de miedo, la mar de, cantidad de*) | grammatical term | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.6.5 pp. 212–213; some include *de* + cuantificador function (*la mar de inteligente, cantidad de barato*) |
| enseguida/en seguida, deprisa/de prisa, enfrente/en frente | adverbs with free one-word/two-word spelling variation | adverb (orthographic variant) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Norma box p. 212 |
| donde (preceded by *a*) | *adonde* written as one word when it has an explicit antecedent, two words (*a donde*) when it doesn't | adverb (orthographic rule) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 212; *Voy a la casa adonde suelen ir mis padres* vs. *Voy a donde tú quieras que vaya* |
| no (as valor de prefijo) | *no* functions as a negating prefix when it precedes a noun introduced by the article | adverb (prefixal use) | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.6.6.1 p. 213; *la no violencia, la no intervención, los no alineados* — institutional/political register |
| cerquita, enseguidita, prontito, ahorita, despacito, deprisita | adverbs + diminutive suffixes | adverb (morphology) | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.6.2.3 p. 207; *ahorita* notably has wide Latin-American colloquial currency beyond this grammar's scope |
| arribota, abajote, lejotes | adverbs + augmentative suffixes | adverb (morphology) | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 207 |
| cerquísima, lejísimos, malísimamente, tardísimo | adverbs + superlative *-ísimo/-ísima* | adverb (morphology) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 207 |
| estupendísimamente, lentísimamente, realísimamente, rapidísimamente, amabilísimamente, recentísimamente | *-mente* adverbs with *-ísima* infixed between the adjectival root and the *-mente* suffix (double-morpheme superlative) | adverb (morphology) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 207; morphologically notable: *amable → amabilísimamente*, *reciente → recentísimamente* — superlative marking survives even on adjectives invariable for gender |
| peatonalmente, informáticamente | newly-coined *-mente* adverbs, offered as evidence the *-mente* subclass is a productive/open class unlike adverbs generally (a closed class) | adverb (morphology) | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.6.2.4 p. 207 |
| a, ante, bajo, con, contra, de, desde, durante, en, entre, hacia, hasta, mediante, para, por, según, sin, sobre, tras | the full standard Spanish preposition paradigm (19 items) | preposition | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.7.1.1 p. 218; a closed class, atonic except *según*; *durante*/*mediante* included for meeting all functional preposition criteria despite historically being present participles |
| cabe | archaic preposition = "junto a" (next to) | preposition | archaic | — | contemporary (2005, book notes archaism) | Spain | — | grammar_reference | n/a | verified | §2.7.2.1 p. 220; must not be confused with the verb form *cabe* (from *caber*): *no cabe duda* |
| so | archaic preposition = "bajo" (under); survives only in fixed locutions (*so pena de, so capa de, so pretexto de*) | preposition | archaic | — | contemporary (2005, book notes archaism) | Spain | — | grammar_reference | n/a | verified | p. 220; must be distinguished from intensifying *so* in insults (*so tonto, so boba* — etymologically from Latin *senior* → Sp. *señor* → *seor/sor/so*, i.e. "so tonto" = ironic "señor tonto") and from the onomatopoeic interjection *¡so!* used to stop animals — three unrelated homophonous *so*'s, genuinely novel etymological finding not in existing corpus |
| pro | preposition, restricted cultismo use | preposition | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 220; *asociación pro derechos humanos, cupón pro ciegos* |
| vía | preposition, added to the paradigm; two registers | preposition | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 220 (general use: *tren... vía Medina*) and p. 221 (second sense belongs to legal/administrative/institutional/political register: *vía sindicatos, vía satélite*) |
| donde, cuando, como (preposicional) | relative/conjunctive adverbs acting AS prepositions when introducing nouns (and, for *como*, also adjectives) | adverb-as-preposition | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.7.2.1 p. 221; *Voy donde tu amigo, Trabaja como camarero, Me tienen como tonto (= por tonto)* |
| conmigo, contigo, consigo | 1st/2nd/3rd person "with-me/you/him(self)" — *con* fuses into one word with *mi/ti/si* + *-go* (< Latin *cum*: *mecum>migo, tecum>tigo, secum>sigo*) | pronoun (fused with preposition) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | Atención box §2.7.2.2 p. 221; etymological note — the *con* (companionship) sense is doubly marked, both in *con-* and in the *-cum* origin of *-go* |
| cocina a gas, camisa a rayas | galicismos sintácticos (non-standard noun+*a*+noun complement pattern, calqued from French) | noun phrase usage error | colloquial | — | contemporary (2005) | Spain | — | grammar_reference | n/a | verified | Norma box §2.7.4 p. 225: should be *de gas*, *de rayas*; contrasted with now-accepted *avión a reacción, olla a presión* |
| problema a resolver | galicismo: noun + *a* + infinitive complement | noun phrase usage error | colloquial | — | contemporary (2005) | Spain | — | grammar_reference | n/a | verified | p. 225; preferred *problema que hay que resolver* |
| contra / entre (cantidad, vulgar) | *contra* and *entre* used with a quantity/correlative meaning ("the more...") in place of *cuanto* | preposition usage error | colloquial | — | contemporary (2005) | Spain | — | grammar_reference | n/a | verified | p. 225: *\*Contra más estudio, más sé* / *\*Entre más estudio, más sé* both flagged vulgar, correct is *Cuanto más estudio...* |
| dequeísmo | insertion of *de* before conjunction *que* where no element of the sentence requires it (*\*Opino de que..., \*Me consta de que...*) | syntactic phenomenon (named) | colloquial | — | contemporary (2005) | Hispanoamérica and much of Spain (explicit) | transnational | grammar_reference | n/a | verified | p. 225; explicit dialectal-spread note, named/labeled phenomenon — high extraction value |
| queísmo | suppression of a preposition before *que* where an element of the sentence requires it (*\*Estoy seguro que vamos a ganar*, for *seguro de que*) | syntactic phenomenon (named) | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 225; labeled "incorrect but excusable in colloquial speech" — softer judgment than dequeísmo |
| a nivel de | locución prepositiva — non-standard outside restricted senses (*a nivel de calle, a nivel de profesorado*) | locución prepositiva usage error | colloquial | — | contemporary (2005) | Spain | — | grammar_reference | n/a | verified | p. 225 |
| en base a | locución prepositiva — only justified in legal/administrative register | locución prepositiva | formal | — | contemporary (2005) | Spain | — | grammar_reference | n/a | verified | p. 225 |
| a causa de, a fin de, de cara a, de acuerdo con, respecto de, en relación con, con relación a, junto a, acerca de | locuciones prepositivas (multi-word units ending in a true preposition) | locución prepositiva | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.7.4.2 p. 224; some are substitutable for a single preposition (*a causa de la lluvia → por la lluvia*), others have no one-word equivalent (*junto a la ventana*) |
| a por | agrupación preposicional — combination of two prepositions functioning as one complex nexus | preposición agrupada | regional | — | contemporary (2005) | Spain, frequent across all sociocultural levels; unknown in Hispanoamérica (explicit) | regional | grammar_reference | n/a | verified | Norma box §2.7.4 p. 225 — explicit dialectal split the source itself marks: considered incorrect by the RAE yet useful because it disambiguates (*voy a por mi hijo* unambiguously "go fetch my son" vs. ambiguous *voy por mi hijo*); a rare case of the source defending a prescriptively-disfavored form on functional grounds |
| para con, de por sí | other agrupaciones preposicionales | preposición agrupada | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.7.4.1 p. 224; *Es bueno para con sus amigos, Es bueno de por sí* |
| hasta | preposition (limit in time/space: *hasta mañana, hasta Madrid*) vs. adverb (intensive-inclusive, synonym of *incluso*: *Hasta Juan lo sabe*) | preposition/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.7.3.2 p. 222; diagnostic: combines with tonic *mí/ti* when preposition (*Llegó hasta mí*), with *yo/tú* when adverb (*Hasta yo lo sé*) |
| entre | preposition requiring a plural-content term (morphological plural, coordination, collective noun, or uncountable-as-collective noun); discutible as preposition when meaning "collaboration" rather than "interiority" | preposition | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | §2.7.3.3 pp. 222–223; unlike other prepositions it combines with tonic *tú/yo* (not *ti/mí*); in the "colaboration" sense it can be analyzed as an atonic adverb-subject rather than a true preposition (*Entre los dos lo escribieron* — *entre* bracketed as adv./subject in the source's own syntactic diagram) |

### Grammar points

#### Verb classification by mode of action and syntax (§2.5.17–18, pp. 188–191)

Gómez Torrego draws a careful distinction, missing from the existing corpus's treatment of verb
classes, between *modo de acción* (a verb's own lexical meaning — perfective vs. imperfective) and
*aspecto* (grammatical meaning carried by desinences or periphrases). A perfective verb (*morir,
llegar*) used in an imperfective-aspect tense can produce special readings: *disparaba* becomes
reiterative, *Pedro se moría sin remedio* shifts to "was about to die." Defective verbs
(*abolir, soler, balbucir*) lack full paradigms; a formally distinct subclass, *unipersonales*
(weather verbs, 3rd singular only: *tronar, nevar, amanecer*...), can still break its own restriction
figuratively (*Llueven las críticas*). A further, previously-uncaptured subclass is *bipersonales*
(*suceder, acontecer, acaecer, atañer*) — 3rd person singular AND plural only, because their meaning
is incompatible with personal subjects altogether, not merely restricted to weather.

On the syntactic axis, transitive/intransitive status is fluid (*Comí patatas* → *Comí a las tres*),
and the source documents a set of real-world prescriptive battlegrounds: some intransitive verbs
drift into transitive use (*incautarse un arsenal*, *cesar al director* — flagged frequent even in
"cultured" press use despite being non-standard; *estallar/explotar una bomba* should use causative
*hacer estallar*; *quedar* transitive flagged explicitly dialectal), and the mirror-image error also
occurs (transitive *entrenar*/*suspender* used intransitively, now "already entrenched in usage"
despite being incorrect). Copulative verbs (*ser, estar, parecer*, plus *ponerse, quedarse*) are
copulative only when linking subject to attribute — *ser*/*estar* used otherwise (*El accidente fue
ayer*) are not. Auxiliary verbs carry all desinences and select no subjects/complements of their own;
the same verb form can be auxiliary or full verb depending on context (*había venido* vs. *había poca
gente*).

#### Verbal periphrases: structure and the full three-part taxonomy (§2.5.19–21, pp. 192–197)

A periphrasis is defined strictly: two or more verbs, at least one auxiliary and the last auxiliated
in a non-personal form (infinitive/gerund/participle), together forming ONE predicate nucleus — not
a subordinate clause. The non-personal forms, not the auxiliary, select the sentence's subjects and
complements (*El niño se puso a llorar* vs. ungrammatical *\*el tren se puso a llorar* for a train
"starting" in a non-living sense), and the auxiliated verb cannot be swapped for an equivalent
nominal/clausal substitute without changing meaning (*Tengo que comprar un piso*, not *\*lo tengo*)
— this substitution test is the source's main diagnostic for distinguishing true periphrasis from a
superficially similar non-periphrastic construction (worked example: *Pedro va a trabajar... al
colegio* is NOT periphrastic because *va* selects its own complement *al colegio* and the infinitive
is independently substitutable — *Va a eso todos los días* — while *Pedro va a trabajar un rato* IS
periphrastic in the right context). Passives are affected only on the main verb, not any periphrastic
*ser* auxiliary.

Periphrases subdivide by the form of the auxiliated verb (infinitive / gerund / participle) and then,
orthogonally, by meaning — two broad semantic groups:

- **Referred to the verbal action itself:** perfective (completion/interruption: *acabar de, dejar
  de, tener + participio, llegar a*), incoative/ingressive (beginning or imminence: *ir a, estar para,
  estar a punto de, empezar a, ponerse a, echarse a, explotar(romper) a*), iterative/frequentative
  (*soler, volver a*), and durative/progressive (*estar, andar, seguir/continuar, llevar* + gerundio
  — the last four forming a "least-to-most" intensity scale the book orders explicitly: durative <
  progressive).
- **Referred to modality / the speaker's attitude:** obligation-necessity (*tener que, haber de,
  haber que, deber*), possibility-probability (*poder, deber de, tener que, querer*), approximation
  (*venir a, venir + gerundio*), and a notably polysemous case: *ir a + infinitivo* alone carries at
  least four distinct readings depending on tense/context (incoative in the simple present; a
  flavor of "inopportunity" when the auxiliary is in pretérito indefinido, *Me fueron a suspender
  cuando menos lo esperaba*; astonishment/denial in exclamatives, *¡Quién lo iba a decir!*; and
  modal probability, *Juan va a haber salido*).

A prescriptive norma box sharpens *deber + infinitivo* (obligation) against *deber de + infinitivo*
(probability) — a minimal pair the book treats as a real, still-live distinction worth defending
despite widespread blurring in actual usage.

Locuciones verbales (*caer en la cuenta, echar de menos/en cara, darse/tener cuenta, hacer añicos,
echar a perder, dar a conocer/entender, dar de lado*) are explicitly distinguished from periphrases
on three grounds: no auxiliary/principal split exists (the whole unit selects subjects/complements);
the non-personal form inside a locution is NOT freely substitutable by another form (*echar a perder*
but never *\*echar a ganar*); and a locution typically paraphrases to one single verb (*echar a
perder → estropear*, *dar de lado → marginar*), unlike a periphrasis. Some locutions are themselves
frozen former periphrases (*vete/vaya a saber*).

#### The *ser* + participio construction: periphrasis, attributive clause, or something in between (§2.5.22, pp. 198–199)

The book stages a genuine grammatical-theory dispute rather than presenting a single settled answer:
some grammarians treat *ser + participio* as a unitary periphrasis (the whole thing is the predicate
nucleus, so Spanish would have no syntactic passive at all, only a semantically passive reading);
others treat it as an ordinary attributive (copulative) construction, where *ser* alone is the
predicate nucleus and the participle (+ agent) is simply the attribute. Gómez Torrego's own position
is an explicitly intermediate one: the construction shows BOTH attributive-clause traits (the
participle is conmutable by *lo*, and can take grade markers like an adjective: *Juan fue aplaudido →
lo fue*, *Juan fue muy aplaudido*) AND periphrasis traits (the *lo*-substitution is sometimes
impossible or forced when there's an agent complement; when a verb has both a regular and an
irregular participle, only the regular one permits the passive construction — *el ganado fue
soltado*, never *\*soltado* [irregular] in this slot — which the book reads as evidence the
participle here is functioning as a verb, not an adjective; adjectival participles in true
attributive clauses are always conmutable by *cómo* and permit the cleft/ecuacional emphatic
structure, which genuine passive participles resist: *¿Cómo es Juan? Listo es lo que es Juan* works,
but *?El discurso leído por el diputado es lo que fue* is marked odd). Passive sentences themselves
are formally defined (sujeto paciente + núcleo ser+participio + complemento agente, often implicit)
and the active↔passive transformation rule is given explicitly (agent complement becomes subject;
verb drops *ser*, agrees with new subject; old subject becomes direct object).

#### El adverbio: formal characteristics and functions (§2.6.1, pp. 202–205)

Adverbs are defined by three formal traits: they are tonic words (except *tan* and the relative
adverbs *donde/cuando/como/cuanto*, plus *cual*), invariable (no desinences), and lexically full
(independently definable in a dictionary — distinguishing them from pure function words). Adverbs
never perform the nominal functions of subject, direct/indirect object, régimen complement, or agent
complement; their characteristic role is complemento circunstancial of a verb, though many also
function as modifiers of an adjective or another adverb (most typically the quantifier adverbs: *muy
guapa, muy cerca*). A separate class — "oracional" complements — includes attributos oracionales
(*Afortunadamente, lo puedo contar*), adverbios de modalidad (*Quizá se vaya papá*), adverbios tópicos
(*Técnicamente, el equipo jugó bien*), and complementos circunstanciales de la enunciación
(*Francamente, estoy cansado*) — four distinct discourse-level adverb functions operating over the
whole clause rather than a single constituent within it.

A useful single-vs-multiple-function distinction: *muy/tan/cuán* complement only adjectives/adverbs;
*medio* complements only adjectives/participles; *recién* in Spain complements only participles but
in Hispanoamérica extends to personal verb forms (*recién salió*) — an explicit, source-marked
dialectal split. By contrast *casi* can complement five different word classes (adjective, noun,
numeral, indefinite, verb), making it unusually promiscuous for a Spanish adverb.

#### Further complement/affix/openness properties of adverbs (§2.6.2, pp. 206–207)

Many adverbs take their own complements headed by a preposition or a clause (*después de la derrota,
detrás de la fuente*); *así* is a special case — followed by *de + adjective*, it becomes a
quantifier and genuinely requires an accompanying hand gesture from the speaker to be interpretable
(*Juan era así de alto*, *Había así de gente en la plaza*) — a rare case of a grammatical
construction whose felicity depends on co-speech gesture, worth flagging for any later
mechanics-analysis phase on gesture-dependent slang. Some adverbs take an appositive complement
(*allá lejos, allí en Francia, mañana jueves, hoy día de San Juan*); others (*no, sí, acaso, quizá(s),
alegremente, tampoco*) cannot be complemented at all.

Certain adjectives "freeze" into the masculine singular form and function as adverbs when they serve
as a verb's circumstantial complement (*Hablaba muy bajo, Marchad rápido, Lo pasamos estupendo,
Jugaron muy duro, Lo pasamos fatal, Juegan sucio*) — adjective-to-adverb conversion via morphological
freezing, a distinct mechanism from the productive *-mente* derivation.

Adverbs mostly resist affixation, but a real subset takes diminutive suffixes (*cerquita,
enseguidita, prontito, ahorita, despacito, deprisita*) and augmentatives (*arribota, abajote,
lejotes*). Several take superlative marking, either via *muy* (periphrastic: *muy lejos, muy
posiblemente*) or via the suffix *-ísimo/-ísima* (*cerquísima, tardísimo*); notably, *-mente* adverbs
form their superlative by infixing *-ísima* between the adjectival root and *-mente* itself
(*estupendísimamente*, *rapidísimamente*) — a double-morpheme derivational pattern — and this
infixed feminine superlative even survives on adjectives that are otherwise invariable for gender
(*amable → amabilísimamente*, *reciente → recentísimamente*), which is a genuinely striking
morphological fact: gender-invariant adjectives still carry a "ghost" feminine agreement inside their
adverbial superlative.

Adverbs as a whole are classed as a *closed* lexical category, with one explicit exception: the
*-mente* subclass (built on an adjective's feminine form + the noun *mente*, grammaticalized as a
suffix) is an *open*, fully productive subclass — illustrated with two then-recent coinages,
*peatonalmente* and *informáticamente*, formed from the (at-the-time-recent) adjectives *peatonal*
and *informático*.

#### Classification of adverbs: formal and semantic (§2.6.3, pp. 208–209)

Formally, two subtypes stand out: *adverbios relativos* (*donde, cuando, cuanto, como*) relate to an
explicit or implicit antecedent, are atonic, and double as subordinating nexuses for relative clauses
while also serving as circumstantial complements within them (*Esa es la calle donde vivo*); *adverbios
interrogativos* (*dónde, cómo, cuándo, cuánto*) appear in direct questions or indirect interrogative
subordinate clauses, and are analyzed by some grammarians as simply a variant of the relatives.

The traditional semantic classification lists twelve classes with representative members: lugar
(*aquí, allí, allá, lejos, (a)delante, atrás, (a)dentro, adonde, donde, ahí, cerca, dónde, arriba,
encima, detrás*), tiempo (*hoy, mañana, luego, ya, todavía, aún, constantemente, recientemente,
nunca, ayer, ahora, enseguida, recién, mientras, temprano, antes, después, cuando*), modo (*así,
bien, mal, mejor, peor, igual, cual, como, según*, plus most *-mente* adverbs), afirmación (*sí,
también, claro, bueno, efectivamente, naturalmente, seguro, evidentemente, verdaderamente*),
negación (*no, tampoco, nada, nunca, jamás*), cantidad (*nada, mucho, poco, apenas, demasiado, más,
menos, tan, muy, bastante, casi, justo, todo, cuanto, sobremanera*), deseo (*ojalá, así*), duda/
posibilidad/probabilidad (*quizá(s), igual, acaso, posiblemente, probablemente, seguramente*),
exclusión/inclusión/adición (*sólo/solo, solamente, únicamente, aun, además, incluso, inclusive,
exclusive, exclusivamente*), identidad (*mismamente, mismo, precisamente, cabalmente, propiamente,
concretamente*), exclamación (*qué, cuán*), and a residual "otros" group that resists clean
categorization (*viceversa, justo, justamente, contrariamente, siquiera, consecuentemente*) — the
book itself flags this last group as not fitting any semantic subclass cleanly, which is itself a
useful signal about the limits of the traditional classification.

#### Observations complicating the adverb classification (§2.6.4, pp. 210–211)

The book immediately qualifies its own taxonomy: many adverbs genuinely belong to more than one
semantic class depending on context (*igual* = modo or duda/probabilidad; *nunca/jamás* = tiempo AND
negación simultaneously; *nada* = negación AND cantidad; *así* = modo, cantidad, AND deseo; *bien* =
modo AND cantidad), and a set of *-mente* adverbs of manner (*horriblemente, terriblemente,
extraordinariamente, absolutamente, increíblemente, horrorosamente*) systematically convert from
modo to cantidad (cuantificador) specifically when placed before an adjective or another adverb
(*horriblemente feo* = intensifier, not manner).

A second layer of complication: several of the words treated above as adverbs also belong to entirely
different grammatical categories depending on context — *harto* and *regular* alternate
adjective/adverb; *mucho/poco/bastante/demasiado/más/menos/tanto/cuanto* alternate determinativo
indefinido / pronombre indefinido / adverb depending on whether they modify a noun, stand alone
nominally, or complement a (sufficiently saturated) verb; *todo* alternates the same three ways;
*bueno* and *seguro* are adverbs of affirmation only in their "yes/certainly" sense, otherwise
ordinary adjectives; *según* alternates adverb (rare, elliptical) and preposition; *mejor/peor* are
adverbs only as the suppletive comparatives of *bien/mal*, otherwise adjectives; *solo* is adverb
only when equivalent to *solamente*; and *bajo* spans FOUR categories (adverb/adjective/preposition/
verb-form-of-*bajar*) depending on context — the single most grammatically polyvalent word the
chunk's range documents.

#### Locuciones adverbiales and remaining adverb peculiarities (§2.6.5–6, pp. 212–213)

A locución adverbial is an indivisible multi-word unit functioning as a single adverb (*a oscuras, de
pronto, desde luego*); most serve as complemento circunstancial exactly like a single adverb (*Lo
hice sin ton ni son*), but a distinct subset instead carries oracional/modal force (*a lo mejor, tal
vez, puede que*), and another subset functions as a cuantificador complementing an adjective/adverb/
noun, sometimes incorporating a trailing *de* (*la mar de inteligente, cantidad de barato*). A norma
box notes some adverbs/locutions have free one-word/two-word spelling (*enseguida/en seguida,
deprisa/de prisa, enfrente/en frente*), and that *donde* fuses with a preceding *a* into one word
(*adonde*) only when an explicit antecedent is present.

Remaining peculiarities: certain adverbs of affirmation can themselves introduce a subordinate clause
via *que*, behaving almost verb-like (*Sí que lo sé* ≈ *Digo que lo sé*); the relative adverbs
*donde/cuando/como/cuanto* (atonic) plus the tonic *según* can introduce subordinate clauses, earning
the label "adverbios conjuntivos"; certain place/time adverbs following a noun take on a
near-prepositional value (*calle abajo, río arriba, campo atrás*); *no* functions as a negating
prefix before an article-headed noun in institutional/political register (*la no violencia, la no
intervención*); *así* and *bien* adjectivize when modifying a noun directly (*Una casa así gusta a
cualquiera*, *Un chico bien* — the latter a register-marked colloquialism for a "proper/posh" young
man, worth flagging as adjacent to slang territory though the book doesn't itself label it as such);
exclamative-interrogative *qué* is only adverbial when modifying an adjective/adverb, not when
functioning as determiner or pronoun; the relative sequence *lo que* is adverbial when it paraphrases
*cuánto*; and *aún* carries a tilde when temporal (tonic) but drops it when inclusive/atonic
(equivalent to *también*/*incluso*) — a orthographic-prosodic minimal pair worth noting for any later
phonological-mechanics work.

#### Las preposiciones: general characteristics, function, and the three grades of meaning (§2.7.1, pp. 218–219)

Spanish has a fixed, closed preposition paradigm of 19 members (*a, ante, bajo, con, contra, de,
desde, durante, en, entre, hacia, hasta, mediante, para, por, según, sin, sobre, tras*) — *durante*
and *mediante* are included despite originating as Latin present participles because they meet every
functional criterion for prepositionhood. Prepositions are atonic (except *según*), invariable, and
can never act with syntactic autonomy except in metalinguistic statements (*De es una preposición*)
or a few fossilized colloquial expressions (*—Estoy enfadado. —¿Por?*). Their function is purely
relational: linking a syntactically autonomous word to another, never themselves filling a nominal
slot (subject, direct/indirect/régimen/agent complement). Prepositions differ from subordinating
conjunctions precisely in what they can introduce: conjunctions subordinate clauses with a personal
verb form; prepositions subordinate nouns, pronouns, noun phrases, adjective phrases, non-personal-
verb clauses, adverbs, or adverb phrases — never a personal-verb clause directly (*Necesito que seas
mi amigo* works; *\*necesito de seas mi amigo* does not). A preposition can only reach a personal-verb
clause by first fusing with *que* or *si* (*Lo hice para que vinierais*) — and the book traces two of
these fusions historically into full subordinating conjunctions in their own right: *por* + *que* →
*porque*, *con* + *que* → *conque*. Prepositions also fuse with relative pronouns/adverbs to introduce
relative clauses (*Lo he hecho para quienes me lo han pedido*), with the preposition's meaning
actually attaching to the antecedent embedded in the relative.

On meaning, the book distinguishes three grades: prepositions with an inherent (sometimes figurative)
meaning of their own (*sin* = absence/lack, *bajo* = inferior position/submission, *sobre* = "on top
of"/"about"/approximation, *tras* = posterior location, *ante* = "in the presence of"/"with respect
to"); prepositions whose meaning is deduced from context — the same preposition shifting sense
entirely by what it attaches to (*con* = compañía in *Estoy con Juan*, instrumento in *Lo corté con el
cuchillo*, modo in *Me miró con malos ojos*); and prepositions that in certain constructions carry NO
lexical meaning at all, functioning as pure grammatical markers — personal *a* before a direct object
referring to a person (*Vi a Pedro*) and *de* in certain appositive-style proper-name constructions
(*la calle de Alcalá*, interchangeable with the de-less *la calle Alcalá*).

#### Archaic, marginal, and newly-admitted prepositions; combination with conjunctions (§2.7.2, pp. 220–221)

Two prepositions, *cabe* ("junto a") and *so* ("bajo"), are now archaic outside fixed expressions; *so*
survives productively only inside locutions (*so pena de, so capa de, so pretexto de*). A genuinely
novel etymological finding, not previously captured anywhere in the existing Spanish corpus: the
intensifying *so* found before insults (*so tonto, so boba*) is historically unrelated to the archaic
preposition — it descends from Latin *senior* via the same sound-change lineage that produced *señor*
itself (*señor → seor → sor → so*), so "*so tonto*" is etymologically "*señor tonto*" used ironically;
this *so* is in turn distinct from the onomatopoeic interjection *¡so!* used to halt animals — three
unrelated homophonous *so* forms converging on one spelling, a rich seam for later mechanics-analysis
work on taboo-adjacent intensifiers.

*Durante* and *mediante*, though historically Latin present participles, are folded into the
preposition paradigm proper because they satisfy every functional test (*durante la guerra* ≈ *en la
guerra*; *mediante su ayuda* ≈ *con su ayuda*). The paradigm can be further extended with the
restricted-register *pro* (a learned Latin borrowing: *asociación pro derechos humanos*) and *vía*,
which the book documents in two distinct registers: general/transportation use (*tren... vía Medina*)
and legal/administrative/institutional/political use (*vía sindicatos, vía satélite*).

The relative/conjunctive adverbs *donde, cuando, como* act as prepositions proper when introducing a
noun (and *como* also an adjective): *Voy donde tu amigo*, *Trabaja como camarero*, *Me tienen como
tonto* (paraphrasable *por tonto*). Most prepositions combine productively with the subordinating
conjunction *que* (worked through for all of *a, con, de, desde, en, hasta, para, por, sin*), but a
distinct subset — *ante, bajo, contra, durante, hacia, mediante, sobre, tras* — cannot, precisely
because they never introduce personal-verb clauses in the first place. A separate etymological note:
*conmigo/contigo/consigo* are not simply *con* + pronoun but a historical fusion of the oblique
pronouns *mí/ti/sí* with a *-go* element descending from Latin *cum* itself (*mecum > migo*, etc.) —
meaning the "with" sense is, synchronically invisible but historically real, doubly marked in these
three forms.

#### The preposition *según*, *hasta*, and *entre* in detail (§2.7.3, pp. 222–223)

*Según* is argued NOT to be a true preposition in several uses: accompanying a verb (*según dicen*)
or a tonic pronoun where a verb seems elided (*según tú, según él*) — its combinability with tonic
*tú/yo* rather than oblique *ti/mí* is read as a diagnostic of non-prepositional status, since true
prepositions (except *entre*) take *ti/mí*. Its preposition-hood is clearest when it governs a noun
phrase or nominalized clause (*según tu opinión, según lo dicho*).

*Hasta* carries a genuine limit-in-time/space meaning as a preposition (*hasta mañana, hasta Madrid*)
but converts to an adverb, synonymous with *incluso*, in its intensive-inclusive sense (*Hasta Juan lo
sabe*); the same *ti/mí* vs. *tú/yo* diagnostic separates the two readings (*Llegó hasta mí*
[preposition] vs. *Hasta yo lo sé* [adverb]). The book notes some grammarians reject the adverbial
analysis on autonomy grounds but concedes other recognized adverbs lack full syntactic autonomy too,
and offers a reconciling reading: the apparently-adverbial use can also be analyzed as a preposition
marking an implicit enumeration's endpoint/goal (*Esto lo saben todos mis amigos... hasta Pedro* =
*Pedro* as the terminal item of an implied list).

*Entre* is syntactically unusual among prepositions in requiring its term to carry PLURAL content,
which can be satisfied morphologically (*entre ellos*), by coordination (*entre Juan y Pedro*), by a
collective noun (*entre el rebaño*), or even by an uncountable noun conceived as made of particles
(*entre el agua, entre la arena*). *Entre* is unambiguously prepositional when it means interiority,
but its status is explicitly called into question when it means collaboration (*Entre mi primo y yo
pudimos hacerlo*) — in this sense it combines with tonic *tú/yo* (not *ti/mí*, like no other true
preposition except itself), can sometimes be dropped without damaging the sentence (*Este trabajo lo
hemos hecho (entre) Juan y yo*), and the book's own worked syntactic diagram analyzes *entre* in
*Entre los dos lo escribieron* as an adverb modifying an implicit subject, rather than as a true
preposition at all — the clearest case in this chunk's range of the source laying out a live, unresolved
analytical disagreement rather than a settled rule.

#### Grouped prepositions, locuciones prepositivas, and prescriptive norms (§2.7.4, pp. 224–227)

Two or more prepositions can combine into a single complex nexus (*para con, de por sí*) — distinct
from a case like *hasta de ti*, where *hasta* is simply functioning as an adverb and no true grouping
exists. Locuciones prepositivas (*a causa de, a fin de, de cara a, de acuerdo con, respecto de, en
relación con, con relación a, junto a, acerca de*) are multi-word units ending in a genuine
preposition; some substitute cleanly for a single preposition (*a causa de la lluvia → por la
lluvia*), others have no one-preposition equivalent (*junto a la ventana*). Adverbs of place/time
followed by *de* (*encima de la mesa, detrás de la puerta*) behave equivalently but are formally
analyzed as adverbial phrases headed by the adverb, not as true locuciones prepositivas, despite
functional equivalence to *sobre*/*tras*.

A long prescriptive norma box closes the chapter with several named usage phenomena worth flagging
for later sociolinguistic/register work: the agrupación *a por*, unknown in Hispanoamérica but
frequent at every sociocultural level in Spain including the press, is considered incorrect by the
RAE yet the book itself defends it as functionally useful because it disambiguates (*voy a por mi
hijo* unambiguously "go fetch," vs. genuinely ambiguous *voy por mi hijo*) — a rare instance of the
source taking the descriptive side against its own prescriptive instinct. *Galicismos sintácticos*
(French-calqued noun+*a*+noun or noun+*a*+infinitive patterns: *\*cocina a gas, \*camisa a rayas,
problema a resolver*) are flagged non-standard, though some have already been fully accepted (*avión
a reacción, olla a presión*). Using *contra* or *entre* with a quantity/correlative sense in place of
*cuanto* (*\*Contra/Entre más estudio, más sé*) is labeled vulgar. Two named, opposite syntactic
phenomena are given explicit regional notes: **dequeísmo** (spurious *de* before *que*: *\*Opino de
que va a llover*) is frequent in Hispanoamérica and much of Spain though rare in educated written
usage; **queísmo** (missing a preposition before *que* where one is grammatically required: *\*Estoy
seguro que vamos a ganar*) is judged incorrect but more readily excused in colloquial speech. Finally,
*a nivel de* outside restricted senses and *en base a* outside legal/administrative register are both
flagged non-standard, and the extension of *en* to mean *dentro de* (*\*En unos segundos estamos con
ustedes*) is likewise non-standard despite being "already extended in cultured usage."

---


---

## Spanish — Established Grammar: Oraciones Subordinadas (Subordinate Clauses) — Sustantivas, Adjetivas, Adverbiales

**Source:** Leonardo Gómez Torrego, *Gramática didáctica del español*, Ediciones SM (Brazilian-licensed
edition, São Paulo, 2005), ISBN 85-7675-066-X. Metalanguage is Spanish itself (not a learner's grammar
with English glosses). Section 03.3, units 1 through 19 (partial — unit 19 continues past this chunk's
end). Chunk E of 6 in Wave S1's representative-sample dispatch of this ~540+-printed-page reference.

**PDF page range actually read:** 160–180 (render range as assigned).
**Printed page range actually covered:** 318–359 (verified empirically — see offset note below).

**Printed-page offset verification:** this PDF is a two-printed-page-per-image spread scan. The
dispatch-supplied formula `printed_left = 2×(PDF_page−1)`, `printed_right = printed_left+1` was
cross-checked directly against the book's own printed folios visible at the bottom of each rendered
page (e.g. PDF page 165 shows printed folios "328"/"329" at the foot of its two halves, matching the
formula exactly: 2×164=328). Confirmed reliable across the whole chunk; no non-monotonic-ordering or
alternate-offset anomalies found in this range.

**Non-redundant-supplement check against existing corpus:** skimmed `014_practice_makes_perfect_complete_spanish_grammar.md`
(the existing Spanish established file most likely to overlap, per dispatch instruction) by grepping
for subordinada/oraciones/clause/sustantiva/adjetiva/adverbial. Confirmed 014's "The subjunctive mood"
section (its Units 13–15) covers noun-clause / adverb-clause / adjective-clause subjunctive-vs-indicative
*triggers* (a WEIRDO-style mood-selection list) — a pedagogical, mood-centered treatment. This chunk's
content is a different axis entirely: Gómez Torrego's formal syntactic *classification* of subordinate
clauses by grammatical function (subject, direct object, indirect object, régimen complement,
circumstantial complement, noun/adjective/adverb modifier) with full constituency-tree-style worked
examples, functional tests (pronoun substitution: sustituir por *eso*/*esas cosas*), and explicit
"Norma" usage-correctness boxes (dequeísmo, queísmo) not present in 014 at all. **Nothing in this
chunk was skipped as redundant with 014 or any other established file** — the entire syntactic-typology
content is new to this corpus. One page (PDF 160, printed 318–319) of end-of-prior-chapter drill
exercises ("Grupos sintácticos," exercises 1–17) was skipped per the standard coverage rule — pure
exercise prompts introducing no new vocabulary or grammar point beyond what the prior (unextracted)
chapter already covered.

**Marginalia found and excluded (vision-reading guard):** a previous-owner library ownership stamp —
"ESCOLA IRMÃ ELIZABETH / ENSINO DE 1º GRAU / SEE-PE / INSC. 703010 / BIBLIOTECA LUIZ CONRADO DE LORENA
E SÁ / CERRA TALHADA-PE" — recurs at least twice in this range, bottom-right of PDF page 162 (printed
323) and bottom-right of PDF page 179 (printed 355). Clearly a rubber-stamp impression, not typeset
book content; excluded entirely from extraction, consistent with the sibling-chunk finding already
flagged in the dispatch. No handwritten pen/pencil marginalia was found in this range (only the stamp).

**Vision Reading Confidence, whole-chunk note:** this source has no text layer at all (confirmed vision-
read only). All example sentences and terminology below were read directly off clean, well-lit, high-
contrast typeset pages — no faded print, binding-gutter shadow, or unusual font was encountered in this
range. Default confidence for all rows below is `plausible_unverified` (vision-read, internally
consistent, not independently cross-checked against a second source) unless noted otherwise per row;
several terms are `verified` because they recur identically across multiple pages in this chunk.

**Content shape note:** this is a pure-syntax academic chapter — it has very little lexical vocabulary
in the usual sense (no thematic word lists). What *is* lexical and table-worthy is the closed set of
subordinating nexos (conjunctions, relative pronouns/adverbs) and a battery of technical grammatical
terminology introduced for the first time in this corpus. Both are captured in the Vocabulary table
below; the bulk of this chunk's value is in the Grammar points section.

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| oración sustantiva | noun clause (a subordinate clause that functions as a noun/noun phrase would) | noun phrase (grammatical term) | technical.grammar | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | defined 3.3.1.1 p. 322: substitutable by a pronoun (*eso*); recurs as a governing term throughout |
| oración adjetiva | adjective clause (relative clause functioning as a noun modifier) | noun phrase (grammatical term) | technical.grammar | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | defined 3.3.8–3.3.10, pp. 338–341; traditionally equated with "relative clause" but book explicitly distinguishes the two categories (not all relatives are adjectives, not all adjectives are relatives) |
| oración adverbial | adverb clause (substitutable by an adverb) | noun phrase (grammatical term) | technical.grammar | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | defined 3.3 terminology box p. 320 and 3.3.11 p. 342; book narrows traditional scope — only clauses genuinely substitutable by an adverb count |
| oración compleja | complex sentence (one predicate subordinates another clause) | noun phrase (grammatical term) | technical.grammar | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 320; explicitly distinguished from *conjunto oracional* |
| conjunto oracional | sentence-conjunct (two+ full clauses joined by coordination or subordination, not true subordination of one predicate into another) | noun phrase (grammatical term) | technical.grammar | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 320; subtypes: *por coordinación* / *por subordinación* |
| nexo | linking element (conjunction, relative pronoun, or relative adverb introducing a subordinate clause) | noun (grammatical term) | technical.grammar | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | used pervasively; a nexo can be bifunctional — both a subordinator and a constituent within its own clause (true of all relative pronouns/adverbs) |
| que (conjunción) | that (subordinating conjunction, no independent syntactic function in its clause) | conjunction | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | the default noun-clause nexo; contrasted explicitly with the homographic relative *que* |
| si (en interrogativas indirectas) | if/whether (subordinator introducing an indirect yes/no question) | conjunction | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 322–326; explicitly distinguished from conditional *si* — the ATENCIÓN box on p. 322 gives the pronoun-substitution test: *No dijo si era bueno → No lo dijo* (substitutable, hence sustantiva) vs. *Me lo dirá si soy bueno* (not substitutable — conditional) |
| qué / quién / cómo / dónde / cuándo / cuánto (interrogativos) | what/who/how/where/when/how much (interrogative pronouns/adverbs heading indirect questions) | pronoun/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | these are bifunctional nexos: subordinator + a syntactic function (CD, CC, etc.) inside their own clause, e.g. *cómo* = CC of *había averiguado* in *No quiso decirme cómo lo había averiguado* |
| donde / cuando / como (relativos adverbiales) | where/when/as (relative adverbs, as opposed to their homographic interrogative-tónico counterparts dónde/cuándo/cómo) | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | unstressed relative forms vs. stressed interrogative forms is an explicit orthographic/functional minimal pair the book drills (3.3.3 ATENCIÓN box, p. 326–327; 3.3.12 ATENCIÓN box, p. 345) |
| quien / quienes / el cual (y variantes) | who/whom / the which (relative pronouns that can head headless/antecedent-less noun clauses or specificative/explicative adjective clauses) | pronoun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | 3.3.9–9.2, pp. 338–339: *quien/quienes* always explicative unless preceded by a preposition (then also specificative); *el cual* is the only relative that tolerates an intervening word/phrase between itself and its antecedent |
| cuyo (y variantes) | whose (possessive relative, adjective-like agreement with the possessed noun) | pronoun (possessive relative) | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 339; can be specificative or explicative; never sustantivada (unlike *que*/*quien*); separable from its antecedent in partitive structures, e.g. *dos de cuyas hojas son ilegibles* |
| porque / como / pues / puesto que / ya que / dado que / comoquiera que / toda vez que | because / as / for / since / given that / whatever the case (causal subordinating conjunctions) | conjunction | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | closed list given p. 352; book splits causals into *del enunciado* (cause of the event) vs. *de la enunciación* (cause of the speech act itself — answers "why do you say X" not "why did X happen") |
| aunque / así / si bien / por más que / y eso que / bien que / aun cuando | although / even so / even if / however much / and that too / even when (concessive subordinators) | conjunction | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p. 358; book explicitly classifies concessives as NOT adverbial (cannot be substituted by an adverb) — a deliberate departure from traditional grammar, flagged in its own ATENCIÓN box |
| para / a / por (+ que) ; a fin de que / con vistas a / miras a / en orden a | so that / in order to (final/purpose-clause nexos — prepositions and prepositional locutions) | preposition / locution | core | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p. 356; final clauses take subjunctive-with-*que* or bare infinitive, NEVER indicative — stated as an absolute rule |
| mientras | while / as long as (temporal/simultaneity conjunction; the one temporal nexo with independent syntactic mobility) | conjunction/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 346: uniquely among temporal nexos, *mientras* can be fronted, postposed, or parenthetically inserted with full syntactic autonomy — contrasted explicitly with *cuando*, which cannot |
| dequeísmo | "de-ísm" (register/correctness label for erroneous insertion of *de* before a *que*-clause not governed by a verb requiring *de*) | noun (metalinguistic/usage label) | technical.grammar | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | recurs in 3 separate "Norma" boxes (pp. 329, 331, 335) as a recognized prescriptive error category — e.g. *Me alegro que... (correct) vs. *Estoy seguro que...→ de que... / marked incorrect with an asterisk in every example |
| queísmo | "que-ísm" (register/correctness label for erroneous omission of a required preposition before subordinating *que*) | noun (metalinguistic/usage label) | technical.grammar | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p. 331 Norma box: *Me acuerdo que era tarde (incorrect, se dice: de que era tarde); pp. 335 — companion/opposite error to dequeísmo |
| de que (con valor de cuando, uso vulgar/dialectal) | "de que" used with the meaning "when" | locution | regional | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | explicitly labeled "vulgar o dialectal" by the book, p. 349 Norma box — example *De que termine la clase, hablamos un rato* marked with an asterisk as nonstandard; rare explicit register/regional tag in this chunk |
| a la que / en lo que (como locuciones conjuntivas temporales) | "at the point that" / "while" — colloquial temporal locutions equivalent to *al + infinitive* / *mientras* | locution | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | labeled "de uso popular exclusivamente" (exclusively popular/colloquial register), p. 349 Norma box — a second explicit register tag |
| fijarse (imperativo, con elisión de "en") | to notice/pay attention (imperative use where the required preposition *en* is colloquially dropped) | verb (idiomatic imperative) | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p. 335 ATENCIÓN box: *fijarse* in the imperative takes on an interjection-like value, so dropping *en* is normal usage (*¡Fijaos qué cosas dice!* rather than the "fuller" *en qué cosas dice*) — book marks this with a "(?)" rather than an asterisk, i.e. tolerated/natural rather than flatly incorrect |

### Grammar points

#### Terminology: oración adverbial, oración compuesta vs. oración compleja/conjunto oracional (3.3, p. 320)

The book flags three terminology departures from "traditional grammar" up front, in a dedicated
Terminología box:

- **Adverbial clauses, redefined.** Traditional grammar lumps causal, final, conditional, concessive,
  comparative, and consecutive clauses in with adverbials simply because they all serve as
  *complemento circunstancial* (circumstantial complement) — and assumes that function is exclusive
  to the adverb category. This grammar does **not** assume that equivalence: circumstantial-complement
  function can also be filled by prepositional constructions or bare noun phrases (*Escribí la carta
  con un bolígrafo* — prepositional construction; *El año pasado tuvimos más suerte* — noun phrase,
  neither one an adverb). Consequently, a circumstantial-complement clause is only classified
  *adverbial* when it is genuinely substitutable by an adverb; it is *sustantiva* when substitutable by
  a noun/pronoun; and it is **neither** adjectival nor adverbial nor substantive when it resists both
  substitutions (the book's examples: conditionals, concessives).
- **Oración compuesta vs. oración compleja / conjunto oracional.** Traditional grammar calls any
  sentence with more than one verb "oración compuesta" (compound sentence). This grammar splits that
  single bucket into two distinct structures: an **oración compleja** is one where a clause
  *subordinates to* / complements an element of the whole utterance (*Tengo ganas de que me visites* —
  the *that*-clause complements *ganas*); a **conjunto oracional** is an utterance containing more than
  one full, independent-predicate clause related either by coordination (*Tengo frío pero no me pongo
  el abrigo*) or by subordination-of-one-clause-to-another-as-a-whole (*Aunque tiene frío, no se pone
  el abrigo*) — crucially, in a *conjunto oracional por subordinación*, the subordinate clause modifies
  the *entire other clause*, not a single element within it, which is the structural test that
  separates it from an *oración compleja*.

#### 3.3.1 — Oraciones sustantivas (noun clauses): concept, nexos, and the substitution test (pp. 322–323)

A noun clause is one that functions exactly as a noun, noun phrase, or pronoun would within a complex
sentence — and as such must always be substitutable by a pronoun (test example: *Quiero que vengas →
Quiero eso*). Noun clauses are marked by one of several nexo types:

- **que / si (or que si combined).** *que* is the default noun-clause subordinator; *si* introduces an
  *interrogativa indirecta* (indirect question) corresponding to a yes/no question (*¿Ha venido Juan? →
  No sé si ha venido Juan*). The book's ATENCIÓN box (p. 322) stresses the pronoun-substitution test as
  the way to distinguish a noun clause with *si* from a superficially identical **conditional** clause
  with *si* (conditionals never substitute with a pronoun): *No dijo si era bueno → No lo dijo* (noun
  clause) vs. *Me lo dirá si soy bueno → Me lo dirá en ese caso* (conditional, substituted by an
  adverbial phrase, not a pronoun).
- **An interrogative pronoun or adverb** that also carries its own independent syntactic function
  within its own clause (bifunctional nexo) — e.g. *cómo* in *No quiso decirme cómo lo había averiguado*
  is simultaneously the subordinator AND the circumstantial complement of *había averiguado*. These are
  likewise indirect questions, but corresponding to a *partial* (wh-) question rather than a yes/no one.
- **The conjunctive adverb como**, specifically when the subordinate clause depends on the verb *ver*
  (*Vas a ver como no le gusta → Lo vas a ver*).
- **No nexo at all** is also possible (*No quiso decírnoslo*; *Te ruego me envíes más papel*).

#### 3.3.1.2–1.3 — Functions of noun clauses; noun clauses as subject (pp. 323–325)

Noun clauses can fill any function an ordinary noun/noun phrase/pronoun can: subject, direct object
(CD), indirect object (CI), régimen complement (CR, preposition-governed), circumstantial complement
(CC), noun-modifier, adjective-modifier, adverb-modifier.

For **subject-function noun clauses**, the defining test (and the thing that most needs active
checking) is substitution by *eso*, then by the plural noun phrase *esas cosas* — if substituting
changes the main verb's number (singular→plural agreement with the clause), the clause genuinely is
the subject (*Me preocupa que llueva mañana → Me preocupa eso → Me preocupan esas cosas*, verb number
shifts, confirming subject status). If the verb's number does **not** shift under this substitution,
the clause is in fact a direct object, not a subject, despite superficially similar surface word order
(*Deseo que llueva mañana → Deseo eso → Deseo esas cosas*, verb stays singular — this is CD, not
subject). Subject noun clauses can also be headed by the article *el* placed directly before *que*,
which reinforces the clause's noun-like status (*El que haya tanta gente me molesta*).

#### 3.3.2 — Subject noun clauses: nexos, obligatory/optional anteposition, dequeísmo (pp. 324–325)

Subject noun clauses are introduced by *que*/*si* (as above), by interrogative pronouns/adverbs, or —
when the clause has an infinitive core — by no nexo at all (*Me gusta bailar*). Positionally, they
usually follow the predicate, but can front for emphasis (*Que lo vean le avergüenza* ← *Le avergüenza
que lo vean*); with a handful of verbs (*significar, suponer, equivaler*) fronting is **obligatory**,
not optional. With a *ser + atributo* predicate, postposition is normal and fronting is rare/marked
("(?)" rated by the book — e.g. *Que tienes razón es evidente* is questionable next to the unmarked
*Es evidente que tienes razón*). A distinct subtype has the subject clause referring to a predicate
whose own verb is simply absent from the sentence (elliptical, typically after an exclamatory
adjective/noun like *¡Lástima que no hayas ganado!* or *¡Qué pena (es) que no vengas!*).

**Norma: dequeísmo in subject clauses.** Because a subject is never preceded by a preposition, any
subject noun clause preceded by *de* is an error (a subtype of *dequeísmo*): `*Me consta de que había
más gente` is wrong — correct is `Me consta que había más gente`. Same for `*Resulta de que nadie lo
sabía` and `*Es fácil de que llueva`.

#### 3.3.3 — Noun clauses as direct object (CD); estilo directo/indirecto (pp. 326–329)

CD noun clauses always depend on the predicate's verb (never on another clause) and belong to the verb
phrase; they always substitute with *lo*. Introductory patterns: *que* when not an indirect question;
*si* when it is one; the combined nexo *que si* is specifically licensed with *preguntar* and *decir*
(the latter in its "ask" sense) — *Me preguntaron (dijeron) que si quería ir con ellos*. An ATENCIÓN box
flags a minimal-pair trap: the unstressed conjunctive adverb *cuando* introduces adjective (relative)
clauses, while the stressed interrogative *cuándo* introduces noun (interrogativa indirecta) clauses —
same surface word, different accent, different clause type (*Dime cuándo has llegado* = noun clause vs.
*Te lo diré cuando llegues* = temporal relative clause). The same stressed/unstressed split applies to
*dónde*/*donde* and *cómo*/*como*.

CD clauses with an infinitive core take no nexo (*Me permitían tocar el piano*); if the infinitival
clause is itself an indirect question it can still take *si* or an interrogative (*No sé si ir a casa*;
*No sé qué decir*). With certain verbs of request/opinion/feeling, *que* can be dropped even with a
finite verb (*Te ruego me disculpes*; *Siento no hayáis recibido el paquete*).

**Estilo directo vs. estilo indirecto (3.3.4).** Direct-speech clauses reproduce someone's exact words
(written convention: quotation marks + colon, or an em-dash in literary dialogue) and function as CD.
Indirect-speech clauses reproduce the *idea* without the exact words, require the subordinating
conjunction *que*, and often force tense/pronoun/deictic shifts (*consecutio temporum*) — *El
Presidente dijo: "Hoy hemos tenido algunos problemas" → El Presidente dijo que ayer (ellos) habían
tenido algunos problemas.* Some grammarians treat direct-speech clauses as *yuxtapuestas* (juxtaposed)
or appositive rather than genuinely subordinate, since they lack a subordinating nexo. In colloquial
register, repeating *que* after a parenthetical interruption is common: *El profesor dijo que, si
queríamos, (que) nos podíamos ir.*

**Norma boxes (p. 329):** (1) *que* and direct-speech framing are strictly incompatible despite being
"relatively frequent in journalistic language" — `*El Presidente dijo que "hoy hemos tenido
problemas"` is flagged wrong. (2) Since the CD-of-a-thing is always built without a preposition, *de*
before subordinating *que* here is dequeísmo: `*Me aconsejaron de que no me acercara`, `*Todos pensamos
de que el diputado no tenía razón` are both marked incorrect.

#### 3.3.5 — Noun clauses as indirect object (CI) and régimen complement (CR) (pp. 330–331)

**CI noun clauses** are rare — few verbs take a clausal indirect object — introduced by *que*/*si*,
always substitutable by the clitic *le* (*No di importancia a que no me llamaran para la reunión → No
le di importancia a eso*). **CR noun clauses** (the régimen/preposition-governed complement) are always
preceded by a preposition and introduced by *que*/*si*; they too substitute by a noun/pronoun (*Me
alegro de que hayáis venido → Me alegro de eso*; infinitive version: *Me alegro de haber hecho el
examen*). With verbs like *dudar*, the infinitive clause can additionally take *si* (*A veces dudo de
si ir o no a la empresa*). The book notes that, strictly, these functions (CI, CR) are really carried
by the whole prepositional construction, not the bare clause.

**Norma: preposition vs. complement-de-régimen box (p. 331).** Two paired errors: (1) *queísmo* —
dropping a verb's genuinely required preposition before *que* is wrong (`*Me alegro que hayáis venido`
→ correct: *de que hayáis venido*; similarly `*Me acuerdo que era tarde`, `*Insistió que teníamos que
ir`, `*Confío que me echéis una mano`); (2) *dequeísmo* — inserting *de* where the verb does not
actually require it, confusing it with the conjunction-introducing *que*, is the opposite error
(`*Confío de que vengáis pronto` → correct: *en que vengáis pronto*; similarly `*Me fijé de que tenía
una mancha...`, `*Insistió de que fuéramos a su casa`). A further ATENCIÓN notes *fijarse* in the
imperative behaves almost like an interjection, so colloquially dropping its *en* (*¡Fijaos qué cosas
dice!* instead of the fuller *en qué cosas dice*) is marked "(?)" — tolerated, not flatly wrong like the
asterisked dequeísmo/queísmo examples.

#### 3.3.6–7 — Noun clauses as CC and as modifiers of noun/adjective/adverb (pp. 332–335)

A noun clause can modify/complement the **circumstantial-complement slot** (most CC clauses are
adverbial, but these sustantiva-type CC clauses are substitutable by a noun/pronoun instead, always
preceded by a preposition except when infinitival): *Se aprobó sin que nadie protestara → ... sin la
protesta de nadie*; such clauses carry semantic values the book labels modo, finalidad, causa, concesión
depending on the governing preposition (*para que* = finalidad; *porque* = causa; *a pesar de que* =
concesión). An ATENCIÓN notes some CC-sustantiva clauses are simultaneously substitutable by an adverb
too (*Lo hice sin que nadie me ayudara → Lo hice sin ayuda → Lo hice así*) — genuinely double-classified.

A noun clause can also modify the **head noun of a noun phrase** (*Tengo esperanzas de que me
aprueben → Tengo esperanzas de eso*), introduced by *que* (always preposition-governed) or by *si*
(indirect-question type: *Tengo la duda de si habrán conseguido llegar*), or with an infinitive and no
nexo (*Tengo ganas de decírselo a todo el mundo*). Structurally the book notes these clauses are, "at
an earlier stratum," really the *término* (object) of a preposition within a prepositional
construction that itself modifies the noun.

Parallel structures modify an **adjective head** (*Estoy seguro de que no os habéis enfadado → Estoy
seguro de eso*; infinitival: *Es reacia a aparecer en televisión*) or an **adverb head** (*Salimos
después de que habíamos comido → Salimos después de eso*). **Norma (p. 334):** dropping the required
preposition before *que* in noun- or adjective-modifier clauses is dequeísmo's mirror error — queísmo
again: `*Estoy seguro que no os habéis enfadado` should be *de que...*; `*Tengo la seguridad que me van
a premiar` should be *de que...*.

**3.3.7.3 — other noun-clause types.** Clauses that complement pronouns like *lo, esto, aquello, eso*
heading a noun phrase count as noun clauses even though they cannot themselves be pronoun-substituted
(they equate to a noun instead): *Lo de que me aburrí no te lo crees tú → Lo de mi aburrimiento...*.
Also noun clauses: those in **apposition** (no preposition) to a noun/pronoun — *Me dijeron una
mentira: que les habían robado.*

#### 3.3.8 — Adjective (relative) clauses: specificative vs. explicative (pp. 336–337)

Adjective clauses function as a noun modifier without a preposition, nearly always headed by a relative
pronoun or adverb (with a small set of bifunctional exceptions at 3.3.10). The book flags explicitly
that **"adjective clause" and "clause of relative" are traditionally conflated but do not always
coincide** — some relative clauses are not adjectives (see 3.3.10) and some adjectives are not relative
clauses (see 3.3.10.2).

- **Specificative (restrictive)** adjective clauses narrow/delimit the referential scope of the
  antecedent noun, form a single prosodic group with it (no pause), and can themselves take an
  infinitive core with *haber*/*tener* antecedent-dropping, in which case the relative shifts toward an
  interrogative form (*No tenemos sitio donde ir → No tenemos dónde ir*; *No hay nada que comer → No
  hay qué comer*).
- **Explicative (non-restrictive)** adjective clauses merely add information about the already-fully-
  referenced antecedent, can be dropped without affecting reference, are always set off by pauses/commas,
  and are read with lowered pitch (*Esa chica, que se llama Ana, fue la primera del curso*).

#### 3.3.9 — Relative clauses without an antecedent; quien/el cual/cuyo behavior (pp. 338–339)

Relative clauses with no overt antecedent are introduced by the article + *que* (*el que, la que...*)
or by *quien/quienes/cuanto* (and variants), which absorb/presuppose the article themselves; these are
structurally adjective clauses that have been **nominalized** (sustantivadas) — *cuyo* and *el cual*
never undergo this nominalization. Antecedent-less adjective-sustantivadas can fill any noun function:
subject (*El que busca halla*), CD (*conocí a quien es mi mujer*), CI (*escribir la carta a quien tú
sabes*), CR (*me acuerdo mucho del que tú hablas tanto*), CC (*como de lo que gano con las clases*),
atributo (*Ese chico es el que necesitamos*), noun-modifier, adjective-modifier. Some grammarians treat
the forms *el/la/lo/los/las* here as pronouns heading a noun phrase rather than articles — the clause
is then just their modifier.

Adverb-relative clauses with no antecedent (*cuando, donde, como*) are adverbial, not adjectival,
substituting by an adverb (*Cuando juegues, me lo dices → Entonces, me lo dices*).

**3.3.9.2 — distributional rules for quien/el cual/cuyo:** *quien/quienes/el cual* occur in explicative
clauses by default; they only occur in specificative clauses when preceded by a preposition (*Esta es
la chica con quien (la cual) salgo*). With a proper-noun or tonic-pronoun antecedent, **only**
explicative clauses are grammatical (*Ana, que es una alumna ejemplar, será premiada*). Only *el cual*
(among relatives) tolerates an intervening word/phrase between itself and its antecedent (*Aquellos
niños se echaron a llorar, los cuales, más tarde, se marcharon*). *Cuyo* can be either specificative
(*Vino a verme una mujer cuyo marido me conocía*) or explicative (*La hija de Juan, cuya casa está
próxima a la mía, salió para París*), and both *el cual* and *cuyo* can be separated from their
antecedent inside partitive structures (*ninguno de los cuales*; *dos de cuyas hojas*).

#### 3.3.10 — Relative clauses that are NOT adjectives; adjective clauses that are NOT relatives (pp. 340–341)

A relative clause complementing an **adjective or adverb** (not a noun) is not an adjective clause,
since adjectives themselves aren't modified by other adjectives (*De bueno que es, todo el mundo
abusa*; *Ahora que no hay nadie, puedes hablarme*) — here *que* functions as a *proadjetivo* or
*proadverbio* rather than a true pronoun. A relative clause whose antecedent is **an entire other
clause** (not a noun) is likewise not adjectival, since adjectives modify nouns, not clauses — these
form near-coordinate "conjuntos oracionales por subordinación" instead (*Mi hijo ha aprobado, lo que me
hace muy feliz*; here the relative is the compound *lo que*, not bare *que*).

Conversely, some non-relative constructions are adjective-like without being relative clauses: certain
verb-*que*-clause idioms function as a predicate attribute exactly like an adjective would (*Pedro está
que rabia → Pedro está rabioso*; *La cosa está que arde → La cosa está mala*) — close kin to intensive
consecutive clauses (3.3.24, outside this chunk's range). Gerund, infinitive, and participle clauses
modifying a noun are also adjectival-but-non-relative (*María siempre aparece en público sonriendo →
...sonriente*; *Tengo una cámara de hacer fotos → ...que hace fotos*; *Vi un hombre dormido debajo de un
árbol → ...que dormía*).

#### 3.3.11–12 — Adverbial clauses: typology; locative and modal subtypes (pp. 342–345)

Adverbial clauses are those genuinely substitutable by an adverb and filling the CC function most
characteristic of adverbs. Not every CC-filling clause qualifies: some CC clauses substitute by a noun
instead (noun-clauses-as-CC, 3.3.6) and some (conditionals, concessives) substitute by **neither**
category. The book's full subtype list for CC-function clauses: *de lugar* (locative), *de modo*
(modal), *de tiempo* (temporal), *causales*, *finales* (final), *condicionales* (conditional),
*concesivas* (concessive), *algunas consecutivas* (some consecutives) — of which only locative, modal,
and temporal (plus some causal/final cases) are treated as genuinely adverbial by substitution; causal
and final are often noun-clauses-as-CC instead (per 3.3.6); conditional and concessive are explicitly
classified as **neither** adverbial nor substantive (flagged in dedicated ATENCIÓN boxes at 3.3.18 and
3.3.19).

**Locative adverbial clauses (3.3.11.3)** are always headed by the relative adverb *donde*, alone or
with a preposition, and substitute by a locative adverb (*Fui donde estaba tu hijo → Fui allí*). *Según*
can also head a locative-adverbial-like clause (*La cafetería está según sales a mano izquierda*). An
ATENCIÓN box warns not to confuse these with adjective clauses with *donde* (which always have an overt
noun antecedent: *Esta es la casa donde vivo*) or with *dónde*-headed indirect questions, which are noun
clauses (*Ignoro por dónde caminan → Lo ignoro*).

**Modal adverbial clauses (3.3.12)** indicate manner, headed most often by the relative adverb *como*,
optionally combined with *si* into the single complex nexo *como si* (*Encontré a Juan como si
estuviera enfermo → Lo encontré así*); other nexos include *según*, *conforme*, the now-literary *cual*,
and the fixed locution *tal y como*. These clauses frequently drop their verb while remaining
recoverable (*según las normas* ← *según dicen las normas*). *Según* and *como* can combine into the
single syntactically-autonomous unit *según como* (*Según como se presente el día, saldremos al campo
o no*; the two words are independently coordinable: *—¿Piensas presentarte al examen? —Según y como*).
When set off by a pause, a modal clause functions as CC of the **whole other clause** (a conjunto
oracional, not a true adverbial-of-a-verb) rather than CC of a single verb (*Tus amigos, como
preveíamos, se fueron al cine*). An ATENCIÓN box again distinguishes the adjective-complementing use
of *como* (with an overt antecedent like *modo*: *No he visto el modo como lo pintó*) and the
indirect-question use of *cómo* (noun clause: *Dime cómo te ha ido → Dímelo*) from the genuinely
adverbial use.

#### 3.3.13–14 — Temporal adverbial clauses (pp. 346–349)

Temporal clauses substitute by a temporal adverb or noun phrase with temporal value, and can express
**simultaneity** (nexos: *mientras, cuando, según, conforme, a medida que, al tiempo que, al par que, a
la vez que* — *siempre* or *cada vez* added to any of these layers in a sense of repetition),
**anteriority** (*cuando, tan pronto como, una vez que, apenas, así que, nada más que, no bien, en
cuanto* — usually *immediate* anteriority), or **posteriority** (most commonly expressed with *cuando*:
*Cuando salga el sol, yo ya estaré levantado*).

*Mientras* is syntactically unique among temporal nexos in being able to front, postpose, or insert
parenthetically with full autonomy (*Mientras recoges las cosas, yo voy a la compra* → *Yo voy a la
compra mientras* → *Yo, mientras, voy a la compra* → *Mientras, yo voy a la compra*) — *cuando* cannot
do this. Antecedent-less *mientras*/*cuando* clauses can themselves sit inside a prepositional
construction (*Eso lo sé desde cuando era niño*). *Cuando* clauses ARE adjectival whenever an explicit
antecedent is present (*Ése fue el momento cuando te conocí*) and behave as noun clauses in
*atributivas* constructions (*Cuando llegue a casa será el momento de felicitarlo → Ese será el
momento...*) — distinguished from the genuinely adverbial, antecedent-less use, and again from the
noun-clause (interrogativa indirecta) use (*No sé cuándo llegará → No lo sé*).

Temporal clauses can also be absorbed as the **modifier within a temporal adverbial group** headed by
*antes, después, luego* (*antes que lo dices*; with the alternative preposition-plus-clause form *antes
de que*, *después de que*, *luego que/luego de que* — the book states explicitly both *X que* and *X de
que* variants are equally valid), or as the **term of a temporal prepositional construction** headed by
*desde*/*hasta* (*Desde que pasó aquello tenemos miedo*) — with debate among grammarians over whether
the *que* here is a plain conjunction or a relative absorbing an implicit antecedent (*Desde (el momento
[en]) que pasó aquello...*), which would make these antecedent-less clauses adjectives-adverbialized
rather than true adverbials.

**Norma: usage box (p. 349), four distinct register/correctness notes — high-value explicit annotation:**
1. The relative adverb *cuando* is **incompatible with future or conditional tense** — `*Cuando vendrás,
   te daré el dinero` is wrong (correct: *cuando vengas*); `*Te dije que cuando vendrías te daría el
   dinero` is wrong (correct: *cuando vinieras*).
2. The sequences *a la que* and *en lo que* as temporal conjunctive locutions are **"de uso popular
   exclusivamente"** (exclusively colloquial/popular register) — *A la que sales del colegio...*
   (preferred: *al salir del colegio...*); *En lo que yo escribo esta carta...* (preferred: *mientras
   yo escribo...*).
3. The locution *de que* meaning "cuando" is **"vulgar o dialectal"** — `*De que termine la clase,
   hablamos un rato` (correct: *cuando termine la clase...*).
4. *Mientras* must not be used with **contrastive** value — `*mi padre es médico, mientras el tuyo es
   arquitecto` should be *mientras que* instead.

#### 3.3.15 — Cláusulas absolutas and other non-finite temporal expressions (pp. 350–351)

Absolute clauses are non-finite predications (infinitive, gerund, or participle core, each with its own
explicit or implicit subject) set off by a pause and related to the main clause by subordination without
any nexo at all — a form of secondary predication with circumstantial function/meaning.

- **Infinitive absolutes**, typically preceded by *al* (a + el), mostly signal immediate anteriority
  (*Al golpear el jugador el balón, la pierna se le dobló*); the locutions *nada más* and *al poco de*
  carry the same immediate-anteriority value (*Nada más comer, salimos a dar un paseo*). When such a
  clause is the term of a preposition, the CC function belongs to the whole prepositional construction,
  not the bare clause (*Tras haberlo visto, salió disparada hacia su casa*).
- **Gerund absolutes** signal anteriority (more often with compound gerunds: *Habiendo sido explicada la
  lección, el profesor se marchó*) or simultaneity within a durative process (simple gerunds:
  *Caminando Juan por la calle, se oyó una explosión*); preceded by *en*, the meaning narrows to
  immediate anteriority (*En llegando a mi casa, descansaré*).
- **Participle absolutes** indicate immediate anteriority (*Terminada la clase, los alumnos salieron al
  recreo*); the subject can migrate into the main clause when coreferential (*Enterado de la situación,
  el jugador no quiso darle importancia*). Reinforcing adverbs *apenas*/*una vez* strengthen the
  anteriority reading (*Apenas terminado el partido, cogieron el autobús*); *después*/*luego* instead
  make the participle clause their own modifier/complement rather than reinforcing it directly.

**Other non-clausal temporal expressions (3.3.15.2):** bare prepositional constructions with temporal
sense that are NOT formally clauses at all (*De mayor, seré arquitecto*; *Desde niño, me gustó el
cine*), and reinforced adverbs/adverbial constructions forming secondary temporal predications (*Ya en
Madrid, comimos*; *Una vez allí, desayunamos*).

#### 3.3.16–17 — Causal clauses: enunciado vs. enunciación; sustantivas vs. non-sustantivas; intensives (pp. 352–357)

Causal clauses signal cause/motive/reason and always function as CC of a verb or of another clause.
Closed nexo list: *porque, como, pues, puesto que, ya que, dado que, comoquiera que, toda vez que*.

- **Causales del enunciado** give the reason for the main clause's event, normally postposed (*El suelo
  está húmedo porque ha llovido*).
- **Causales de la enunciación** give the reason the *speaker is saying* the main clause, answering "why
  do you say X" rather than "why did X happen" — these complement a broader, implicit speech-act frame
  rather than the main verb itself, and together with that implicit frame form a *conjunto oracional*
  (*Ha llovido, porque el suelo está húmedo* ≈ "it's evident that it rained, [I say this] because the
  ground is wet" — the causal doesn't explain the rain, it explains how the speaker knows).

With *porque* specifically, the book's preferred segmentation treats the clause as beginning at *que*
(i.e. *por* + *que*), since the *que*-initial sequence is itself noun-equivalent — `Estoy aquí porque
tengo hambre → ...por eso`.

**Causal clauses as término de preposición** (hence *sustantivas*, substitutable by noun/pronoun) occur
with locutions like *gracias a, a causa de, merced a, en vista de, por culpa de, debido a* plus *que*
(*He aprobado gracias a que me ayudasteis → Gracias a eso*), or with *por* + infinitive / *a fuerza de*
+ infinitive (*Me han suspendido por ponerme nervioso*). A second class functions **directly** as CC of
a verb or of the whole main clause and is **neither** sustantiva nor adverbial since it resists both
substitution tests (*Como me habéis ayudado, he aprobado*).

A single *conjunto oracional por subordinación causal* can itself contain a second, nested causal clause
that functions as plain CC of a verb within the main clause (*Ya que no me llaman, me voy porque tengo
que hacer la compra* — two independently-governed causal clauses stacked at different structural
levels).

**Intensive causals (3.3.17.2):** constructions with *tanto* (and variants) correlated with *como*
express causally-flavored intensity (*De tanto como he estudiado me duelen las cervicales*; equivalent
to *Por estudiar mucho, me duelen las cervicales*). Relative clauses complementing an adjective/adverb
preceded by *de* or *por* likewise carry intensive-causal value (*De bueno que es, todos abusan de él* ≈
*porque es muy bueno*; with the intensive relative sequence *lo que*: *No podemos salir de casa de lo
que llueve* ≈ *porque llueve mucho*; *Por lo lejos que vive, no voy a visitarlo*). Infinitive clauses
with *por*/*a* also carry plain causal value (*Por no estudiar, me suspendieron*; *Al no verlo, me
empecé a preocupar*). A causal clause can be introduced by bare *que* (no preposition) when set off by a
pause — in this case it is explicitly **not** sustantiva (*Me pongo el abrigo, que hace frío*).

#### 3.3.18 — Final (purpose) clauses (pp. 356–357)

Final clauses are explicitly classified by this grammar as **not adverbial** (cannot substitute with an
adverb) despite "other grammarians" treating them as such — flagged in its own ATENCIÓN box. They are
almost always noun clauses (substitutable by noun/pronoun) functioning as CC of the main verb, and
express finalidad/intención/propósito. Nexos: the prepositions *para, a, por*; the locutions *a fin de,
con vistas a, miras a, en orden a*. Final clauses take **subjunctive with que, or infinitive without any
nexo — never indicative**, stated as an absolute incompatibility rule. An ATENCIÓN box discusses whether
*a fin de que* should count as a fixed locución conjuntiva — the book leans against, on the grounds that
coordinated enunciados require repeating or dropping the *entire* sequence *para que*, not just *para*
(*Trabajo para que estéis cómodos y (para que) seáis felices* — dropping only *para* is ungrammatical).

Other patterns: bare *que* (no preposition) can act as a final nexo with an imperative main verb
(*Vuélvete, que te veamos* ≈ *...para que te veamos*) — in this case the clause is explicitly **not**
sustantiva, and forms a conjunto oracional with the main clause instead. Final value can also be carried
by a noun phrase headed by *fin, objeto, pretexto, intención, idea* + *de* + clause, in which case the
CC function belongs to the whole noun phrase, not the bare clause (*Me presenté en el colegio con el fin
de que me informaran*). Final clauses can depend on an implicit "decir" verb carrying a near-phatic
function (*Para que te enteres, ya soy director* ≈ *Te lo digo para que te enteres de que ya soy
director*) — labeled *finales de la enunciación*, paralleling the causal distinction above. A final
clause can also appear negated with no nexo at all, typically with *ser* in subjunctive or the *ir a +
infinitive* periphrasis (*Voy a quitar el coche, no sea que me multen*; *Se abrigó bien, no fuera a
enfriarse*).

**3.3.18.3 — subject coreference rule:** when the main clause and the final clause share the same
subject, the final clause defaults to the infinitive (*He venido (yo) para ayudaros (yo)*); when the
subjects differ, the subjunctive is used instead (*Trabajamos (nosotros) para que coman nuestros
hijos*) — though exceptions exist even without coreference (*Dame la mano (tú) para cruzar (yo) la
calle*).

#### 3.3.19 — Concessive clauses (pp. 358–359, continues past chunk end)

Like final clauses, concessive clauses are explicitly classified as **not adverbial** (cannot be
substituted by an adverb) in this grammar's own terms, despite other grammarians treating them as
adverbial — flagged in a dedicated ATENCIÓN box, paralleling 3.3.18's identical move for finals.
Concessive clauses always signal an obstacle/opposition/objection to what the main clause expresses,
*without that obstacle preventing the main clause's content from being true* — the core semantic
contrast with conditional clauses. They are subordinate to a "main" clause within a conjunto oracional.
Nexos: the conjunction *aunque*; the conjunctive adverb *así*; the locutions *si bien, por más que, y
eso que, bien que, aun cuando*.

Other concessive-meaning structures (3.3.19.2, within this chunk's page range):
- *A pesar de* / *pese a* + *que*-clause: structurally these ARE noun clauses (substitutable by
  noun/pronoun) inside a prepositional construction that itself functions as CC (*No lo hago, a pesar de
  que me lo han pedido → A pesar de eso*).
- *Además de / encima de / aparte de que* heading adverbial-group concessives, where one of the two
  clauses in the resulting sentence must carry negation (*Encima de que no comes, engordas*; *Encima de
  que comes, no engordas*).
- Relative clauses modifying the quantity adverbs *mucho, más, poco* preceded by *por* (*Por mucho que
  grites, no vas a conseguir nada*) or by *para* (*Para lo mucho que estudia, saca notas muy bajas*).
- The sequence *con* + *lo* + adjective/adverb + a relative clause (*Con lo listo que es, no logra
  aprobar*).
- *para* + infinitive (*Para tener tanto dinero, viaja poco*).
- *aun, hasta, incluso* + gerund (*Aun cenando poco, duermo mal*).
- Subjunctive verb forms in disjunctive coordination (*Quieras o no (quieras), iré a tu casa*).

**3.3.19.3 — non-clausal concessive segments:** fixed non-oracional expressions carrying concessive
force — *aun así, así y todo, a pesar de (pese a) todo, con todo y (con) eso* — and a bare adjective set
off by a pause and followed by *y* (*Herido, y logró llegar a casa*).

---


---

## Spanish — Established Vocabulary/Grammar: Gramática didáctica del español, Chunk F (PDF pp. 198–218 / printed pp. 394–435) — Fonética/Fonología (end) + Ortografía de las letras (start)

**Source:** Leonardo Gómez Torrego, *Gramática didáctica del español* (Ediciones SM, Brazilian-licensed
edition, São Paulo, 2005, ISBN 85-7675-066-X). PDF pages 198–218 of 272 total, vision-read (no text
layer — confirmed). Printed-page spread confirmed empirically: each PDF page = two printed pages
side by side (left + right). **Actual printed-page range covered: 394–435**, continuous and complete
within that span — no gaps, no out-of-order pages, printed numbers increase monotonically throughout.

**Dispatch scope note:** this is chunk F of 6 covering a deliberately sampled subset of this ~540-page
reference (orchestrator's full-book size assessment); this chunk's own assigned range was read
comprehensively, not further sub-sampled.

**Non-redundant-supplement note:** this is the first extraction from this book's phonetics/orthography
material (chapters 04.1 "Fonética y Fonología" tail end, and 05.1 "Ortografía de las letras" start).
Spanish's existing 15 base `established/` files (001–015) are pedagogical/conversational grammars with
essentially no phonetics/orthography depth, so this entire chunk's content is new — no redundancy check
was needed against prior files; this was confirmed true in practice (no overlapping content found).

**Content breakdown:**
- Printed pp. 394–409: tail end of Fonética y Fonología chapter (04.1) — consonantal/vocalic
  allophones (§9), phonetic/phonological transcription (§10), the syllable (§11), diphthongs/
  triphthongs/hiatos (§12), syllabification rules (§13), stress/accent (§14), intonation (§15–16).
- Printed p. 410: blank (verso of §16 end).
- Printed p. 411: end-of-chapter drill exercises for Fonética y Fonología (11 numbered exercises,
  no new content — **skipped per coverage rule**, these are drills referencing material already
  captured above, not new vocabulary/grammar).
- Printed p. 412: blank page (faint illegible bleed-through of the facing exercises page — a print
  artifact, not new content).
- Printed p. 413: chapter-5 title page ("Ortografía") — no extractable content.
- Printed p. 414: blank (chapter divider verso).
- Printed p. 415: **print artifact — a faint, nearly-illegible duplicate/ghost of page 416's content**
  (verified by re-rendering at 300dpi with contrast boost: text matches page 416's "Desajustes entre
  fonemas y letras" section word-for-word, same marginal annotations, same column layout). This is a
  scanning/printing double-exposure, not independent content — **not re-extracted separately**, since
  page 416 (read cleanly) already supplies this content in full.
- Printed pp. 416–435: start of Ortografía chapter (05.1) — causes of spelling errors (§1), the
  letter *h* (§2: pronunciation/position/origin/lexical families/useful rules), homonymous/homophone
  pairs with and without *h* (§3–4), other *h*-initial words (§5), words with intercalated *-h-* (§6),
  the letters *b*, *v*, *w* general considerations (§7), orthography of *b* (§8), orthography of *v*
  (§9, continues past my range), homonymous/homophone pairs with *b* and *v* (§10, starts near my
  range's end).

**Marginalia check:** no handwritten marginalia (pen/pencil marks, underlining, owner stamps) found
anywhere in this range — this copy's scan is clean of reader annotation in these pages. The only
scan artifacts are the faint-page-415-ghost noted above and minor light bleed-through visible at the
margins of a few other pages (416, 425, 434–435) that does not obscure any printed content.

**Vision Reading Confidence:** `verified` throughout except where noted per-row — every IPA
transcription symbol, diacritic, and word was cross-checked against repeated appearances of the same
forms across multiple pages/sections (e.g., *habría/abría*, *grabar/gravar* pairs appear with full
worked examples; phonetic symbols like [β], [ɣ], [θ] etc. were cross-verified against the book's own
IPA-adjacent notation key established earlier in the chapter, referenced via the `4.1|2` style
in-text pointers this book uses throughout).

---

### Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| nada | nothing | pronoun | core | — | contemporary (source published 2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates alveolar [n] allophone (word-initial position) |
| cana | grey hair | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates alveolar [n] (between vowels) |
| insípido | insipid, bland | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates alveolar [n] (before alveolar consonants) |
| envidia | envy | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates labialized [m] allophone of /n/ before /b/ |
| ampolla | blister; light bulb | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates labialized [m] allophone |
| anfibio | amphibian | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates labiodentalized [ɱ] allophone of /n/ before /f/ |
| anzuelo | fishhook | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates interdentalized allophone of /n/ before /θ/ |
| antes | before | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates dentalized allophone of /n/ before /t/,/d/ |
| andas | (you) walk | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates dentalized allophone of /n/ |
| ancho | wide, broad | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates palatalized allophone of /n/ before /tʃ/ |
| cónyuge | spouse | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates palatalized allophone of /n/ before /ʝ/ |
| ancla | anchor | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates velarized allophone of /n/ before /k/ |
| hongo | mushroom; fungus | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates velarized allophone of /n/ before /g/ |
| ángel | angel | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates velarized allophone of /n/ before /x/ |
| alto | tall; stop | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates dentalized allophone of /l/ before dental consonant |
| toldo | awning | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates dentalized [l] allophone |
| alzo | (I) raise | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates interdentalized allophone of /l/ before /θ/ |
| colcha | bedspread | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates palatalized allophone of /l/ before palatal consonant |
| pala | shovel | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.394; illustrates default alveolar [l] (elsewhere) |
| peine | comb | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.395; illustrates [i̯] semivowel (2nd element of decreasing diphthong) |
| buey | ox | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.395; illustrates [i̯] semivowel (3rd element of triphthong) |
| limpiéis | (you-pl) clean (subj.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.395; illustrates [j] semiconsonant in triphthong |
| causa | cause | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.395; illustrates [u̯] semivowel (decreasing diphthong) |
| guau | woof (onomatopoeia) | interjection | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.395; illustrates [u̯] semivowel (3rd element of triphthong) |
| puerta | door | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.395; illustrates [w] semiconsonant (1st element of diphthong) |
| averiguáis | (you-pl) find out | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.395; illustrates [w] semiconsonant in triphthong |
| banana | banana | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.395; ATENCIÓN box — illustrates vowel nasalization [ã] between nasal consonants |
| emanar | to emanate | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.395; illustrates vowel nasalization [ẽ]/[ã] |
| agua | water | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.398; illustrates a syllable formed by a vowel+consonant group as a single sound unit |
| payaso | clown | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.398; open-syllable (ends in vowel) example |
| ceniza | ash | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.398; open-syllable example |
| cacharro | piece of junk; pot/pan | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.398; open-syllable example |
| calentar | to heat up | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.398; open-syllable example |
| angustia | anguish | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.398; open-syllable example |
| instrucción | instruction | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.398/402; closed(trabada)-syllable example; also illustrates ns+consonant 3-consonant split rule |
| malestar | malaise, discomfort | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; closed-syllable example |
| aptitud | aptitude | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; closed-syllable example |
| transformar | to transform | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; closed-syllable example |
| descuido | carelessness, oversight | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; closed-syllable example |
| cansancio | tiredness, fatigue | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; closed-syllable example |
| accción/acción | action | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; ATENCIÓN box — double "cc" splits across syllables, first [k]/[g], second [θ]: ac-ción → [akθjón] |
| examen | exam | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; ATENCIÓN — letter x = /ks/, first syllable w/ x before consonant is always trabada |
| éxtasis | ecstasy | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; same x=/ks/ rule |
| éxodo | exodus | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; x between vowels splits k/s across syllables: é-xo-do |
| expectante | expectant | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; x before consonant stays in one syllable: eks-pek-tán-te |
| héroe | hero | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399/407; h is silent & doesn't count for syllable count: hé-ro-e |
| cohesión | cohesion | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; silent intervocalic h doesn't block syllable count: ko-e-sjón |
| inhumar | to inter, bury | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; silent h; morpheme breakdown given: prefix in- + root hum- + suffix -ar |
| inhibir | to inhibit | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.399; silent h; morpheme breakdown: prefix in- + root hib- + suffix -ir |
| sal | salt; go out (imperative) | noun/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.404; example of a monosyllabic word |
| solo | alone; only | adjective/adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.405; example of a bisyllabic (2-syllable) word |
| mampara | screen, room divider | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.405; example of a trisyllabic (3-syllable) word |
| entrégalo | hand it over (imperative+clitic) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.405; example of a cuatrisílaba (4-syllable) word |
| recoger | to pick up, collect | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.405; example of palabra aguda (stress on last syllable) |
| sale | (he/she) goes out; leaves | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.405; example of palabra llana/paroxítona (stress on penultimate syllable) |
| dímelo | tell it to me (imperative+clitics) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.405; example of palabra esdrújula (stress on antepenultimate syllable) |
| cantábamelo | you were singing it to me (imperfect+clitics) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.405; example of palabra sobresdrújula (stress before antepenultimate syllable) |
| imponente | imposing, impressive | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.405; illustrates expressive/emphatic double-stress in emphatic speech |
| salió | (he/she) left/went out | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; diptongo example (sa-lió) |
| veinte | twenty | numeral | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; decreasing diphthong example: vein-te → [béi̯nte] |
| raudo | swift, fast | adjective | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; decreasing diphthong example: rau-do → [ráu̯do] |
| averigüéis | (you-pl) find out (subj.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; triphthong example: a-ve-ri-güéis |
| atestigüéis | (you-pl) bear witness (subj.) | verb form | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; triphthong example, tilde falls on nucleus: a-tes-ti-güéis → [atestiɣwéi̯s] |
| acuciáis | (you-pl) press/urge | verb form | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; triphthong example: a-cu-ciáis → [akuθjái̯s] |
| boina | beret | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; decreasing-diphthong example |
| soy | (I) am | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; decreasing-diphthong example |
| náusea | nausea | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; decreasing-diphthong example |
| cien | one hundred | numeral | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; increasing-diphthong example |
| ciento | one hundred (full form) | numeral | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; increasing-diphthong example |
| pues | well, so, then | conjunction/discourse marker | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; increasing-diphthong example |
| puesto | put, placed; job/position; stall | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; increasing-diphthong example |
| viudo | widower | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; two-closed-vowel diphthong, 2nd vowel is nucleus: viu-do → [bjúdo] |
| cuidar | to take care of | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.400; two-closed-vowel diphthong: cui-da → [kwída] |
| caoba | mahogany | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example (two open vowels a-o) |
| creo | (I) believe/think | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example |
| tía | aunt | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example (closed-stressed-vowel + open) |
| laúd | lute | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example |
| leer | to read | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example (two open vowels e-e) |
| tebeo | comic book (Sp.) | noun | regional | — | contemporary (2005) | Spain | national | grammar_reference | n/a | verified | p.401; hiato example, two open vowels |
| beodo | drunk, inebriated | adjective | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example |
| meollo | marrow; crux/gist | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example (and separately listed on p.427 as an -h-less exception) |
| tío | uncle | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example (closed-stressed i + open o) |
| púa | thorn, spike; (guitar) pick | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example |
| río | river | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example |
| pie | foot | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401/404; hiato example; also used earlier (p.395) to show tilde placement distinguishes pie/pié/pié meanings |
| tahúr | gambler, cardsharp | noun | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401/403; hiato example (open a + closed-stressed u); also noted p.403 as of uncertain etymology despite its h |
| raíl | rail (railway) | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example (open a + closed-stressed i) |
| reíd | read! (vosotros imperative) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example |
| Raúl | Raúl (proper name) | proper noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example |
| tiíta | little aunt (diminutive) | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example, two closed vowels i-i |
| diurno | diurnal, daytime | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example, two closed vowels i-u |
| huid | flee! (vosotros imperative) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; hiato example, two closed vowels u-i |
| Joaquín | Joaquín (proper name) | proper noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; ATENCIÓN — atonic-hiato-to-diphthong drift in casual speech: Jo-a-quín → Joa-quín → colloquial *[xwakín] |
| aéreo | aerial, air- (adj.) | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; same drift phenomenon: a-é-re-o → a-é-reo → colloquial *[aérjo] |
| geranio | geranium | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; ultracorrection error example: hypercorrect *ge-rá-ne-o for correct ge-ra-nio |
| espurio | spurious, illegitimate | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; ultracorrection error example: hypercorrect *es-pú-re-o for correct es-pu-rio |
| jesuita | Jesuit | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; dialect-variable diphthong/hiato: [xe-swí-ta] or [xe-su-í-ta] |
| austriaco | Austrian | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; -iaco words show dialect-variable diphthong/hiato: [aus-trjá-ko] or [aus-trí-a-ko] |
| cardiaco | cardiac | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; same -iaco pattern: [kar-djá-ko] or [kar-dí-a-ko] |
| período | period, era | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; dialect-variable diphthong/hiato: [pe-rjó-do] or [pe-rí-o-do] |
| cruel | cruel | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.401; dialect-variable diphthong/hiato: [krwél] or [kru-él] |
| primicia | scoop (news); first fruits | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; pr-inseparable-group syllabification example |
| abrigo | coat; shelter | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; br-inseparable-group example |
| frito | fried | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; fr-inseparable-group example |
| congrio | conger eel | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; gr-inseparable-group example |
| aeroplano | airplane (dated term) | noun | archaic | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; pl-inseparable-group example |
| blando | soft | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; bl-inseparable-group example |
| aflígir/afligir | to afflict, distress | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | plausible_unverified | p.402; fl-inseparable-group example (á-fli-gir) |
| ácrata | anarchist | adjective/noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; kl/cr-inseparable-group example |
| subrayar | to underline | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; exception: b+r splits across syllables after sub-/ob-/ab- prefixes |
| subrepticio | surreptitious | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; same prefix-exception pattern |
| oblongo | oblong | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; same prefix-exception pattern (ob-lon-go) |
| sublime/subliminal | subliminal | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; same prefix-exception pattern (sub-li-mi-nal) |
| abrogar | to abrogate, repeal | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; same prefix-exception pattern (ab-ro-gar) |
| obliterar | to obliterate | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; same prefix-exception pattern (ob-li-te-rar) |
| atrás | behind, back | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; tr-inseparable-group example |
| adrede | on purpose, deliberately | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; dr-inseparable-group example |
| trago | swig, swallow | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; tr-inseparable-group example |
| atlas | atlas | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; tl split across syllables in Peninsular Spanish (at-las); single-syllable a-tlas in Canary Islands/Hispanic America |
| atleta | athlete | noun | core | — | contemporary (2005) | Spain | national | grammar_reference | n/a | verified | p.402; same Peninsular tl-split pattern (at-le-ta vs. Canarian/Hispanoamerican a-tle-ta) |
| atlético | athletic | adjective | core | — | contemporary (2005) | Spain | national | grammar_reference | n/a | verified | p.402; same regional tl pattern |
| adlátere | hanger-on, sidekick | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; dl-split example, same regional pattern as tl |
| consonante | consonant | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; example of two non-special consonants splitting across syllables |
| inviértelo | invert it (imperative+clitic) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; same split-consonant pattern |
| lección | lesson | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; same split-consonant pattern (double c = /kθ/) |
| psicología | psychology | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; word-initial consonant cluster stays together: psi-co-lo-gí-a |
| mnemotécnico | mnemonic | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; initial-cluster example: mne-mo-téc-ni-co |
| gnomo | gnome | noun | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; initial-cluster example: gno-mo |
| contrafernar/contrafraternar | (archaic; to fraternize against) | verb | archaic | — | contemporary (2005) | — | — | grammar_reference | n/a | low_confidence | p.402; 3-consonant-with-liquid example: con-fra-ter-nar — faint print, cross-check recommended |
| comprobar | to verify, check | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; 3-consonant-with-liquid example |
| hambre | hunger | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.402; 3-consonant-with-liquid example |
| hamster/hámster | hamster | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.403; loanword, 3-consonant cluster without liquid stays together: hams-ter |
| istmo | isthmus | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.403; exception to the 3-consonant rule: ist-mo |
| gángster | gangster | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.403; loanword with a true 3-consonant single syllable |
| áureo | golden | adjective | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.403; hiato-vowels-split-syllables example |
| heroico | heroic | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.403; hiato example |
| hegeliano | Hegelian | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; one of two words whose initial h- is actually aspirated [hº] (loanword from a foreign h-aspirating language) |
| hitleriano | Hitlerian, of/relating to Hitler | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; same aspirated-h loanword pattern |
| harto | fed up; (dialectal) very | adjective/adverb | core | — | contemporary (2005) | Extremadura/Andalucía/Canarias/Antillas | regional | grammar_reference | n/a | verified | p.418; regional aspirated h- from Latin f-, found in popular speech of Extremadura, Andalucía, Canarias, Antilles |
| hondo | deep | adjective | core | — | contemporary (2005) | Extremadura/Andalucía/Canarias/Antillas | regional | grammar_reference | n/a | verified | p.418; same regional aspirated-h pattern |
| hastío | boredom, weariness | noun | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/424; h at word start before vowel; also listed p.424 in h- lexical family (hastío, hastiar) |
| hechizo | spell, enchantment | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; h at word start before vowel |
| hilo | thread | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/425; h at word start; root of the hilar family noted p.425 (hilar, deshilar, hilacho, hiladillo, hilandera, hilandería, hilatura, deshilachar, hilera, sobrehilar, hilvanar, hilván) |
| hola | hello | interjection | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/423; h- initial; homophone pair with ola 'wave' (p.423) |
| huida | flight, escape | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; h- initial before diphthong |
| exhausto | exhausted | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/426; intercalated -h- after consonant; also in exhaustivo family p.426 |
| inhóspito | inhospitable | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/426; intercalated -h- after consonant; also listed p.426 among -h- intercalada error-prone words |
| deshidratar | to dehydrate | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; intercalated -h- after consonant |
| vahído | fainting spell, dizzy spell | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/426; intercalated -h- between vowels; also listed p.426 among error-prone -h- intercalada words |
| vaho | vapor, steam, breath-fog | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/426; intercalated -h- between vowels |
| desahuciar | to evict; to give up hope on (medically) | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/426; intercalated -h- between vowels; noun form desahucio also listed p.426 |
| hombre | man | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; h from Latin hominem, example of h descending from Latin h- |
| hombro | shoulder | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; h from Latin humerum |
| hambre | hunger | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; h from Latin f- (famen > hambre) |
| humo | smoke | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/419; h from Latin f- (fumum > humo); family distinguished p.419 ATENCIÓN from the humus 'earth' family (humilde/inhumar/exhumar) |
| hermano | brother | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; h of uncertain origin — doesn't correspond to either h- or f- in Latin germanum |
| huevo | egg | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418/419; h of uncertain origin (Latin ovum); family listed p.419: óvulo, ovario, ovíparo, ovalado, oval, ovoide |
| vahído | fainting spell | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; h of uncertain origin (Latin vagum) |
| tahúr | gambler, cardsharp | noun | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.418; explicitly noted as of unknown/uncertain etymology despite its h |
| rehacer | to redo, remake | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; lexical family with h: hacer→rehacer→deshacer→hecho |
| deshacer | to undo, unmake | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; same hacer-family chain; also central to the deshecho/desecho homonym-pair discussion (p.420) |
| hecho | fact; done/made (past part.) | noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419/420; end of hacer-family chain; homonym-pair target vs. echo (p.420) |
| huésped | guest | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; lexical family: huésped→hospedaje→hospital→inhóspito |
| hospedaje | lodging, accommodation | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; same huésped-family chain |
| hospital | hospital | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; same huésped-family chain |
| humus | humus (soil) | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; lexical family: humus→humilde→inhumar→exhumar, from Latin humus 'earth' |
| humilde | humble | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; humus-family chain |
| exhumar | to exhume | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; humus-family chain |
| hueco | hole, gap; hollow | noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; exception to h-family-consistency rule: hueco→oquedad (oquedad has no h) |
| oquedad | hollowness, cavity | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; h-less exception paired with hueco |
| huelo | (I) smell | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; exception: huelo/hueles/huele have h but oler/olor/olemos/oléis/olamos do not |
| oler | to smell | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; h-less counterpart in the huelo exception family |
| huérfano | orphan | noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; exception: huérfano→orfandad, orfanato (no h) |
| orfandad | orphanhood | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; h-less exception paired with huérfano |
| orfanato | orphanage | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; h-less exception paired with huérfano |
| Huesca | Huesca (city, Spain) | proper noun | core | — | contemporary (2005) | Spain | regional | grammar_reference | n/a | verified | p.419; exception: Huesca→oscense (demonym has no h) |
| oscense | of/from Huesca (demonym) | adjective | core | — | contemporary (2005) | Spain | regional | grammar_reference | n/a | verified | p.419; h-less exception paired with Huesca |
| hueso | bone | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.419; exception family: hueso→óseo, osamenta, osario, osificar (all h-less) |
| echo | (I) throw/pour (verb echar, 1sg pres.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.420; homophone pair with hecho; sin-h form of verb echar |
| deshecho | undone, unmade (past part. of deshacer) | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.420; homophone pair with desecho; con-h form |
| desecho | I discard (verb desechar, 1sg); also noun 'waste/discard' | verb form/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.420; homophone pair with deshecho; sin-h form, both verbal and nominal senses |
| desechar | to discard, reject | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.420; prefixed derivative of echar, written without h throughout its paradigm |
| hojear | to leaf through (a book) | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.420; homophone pair with ojear; derives from hoja 'leaf/page' |
| ojear | to glance at, eye quickly | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.420; homophone pair with hojear; derives from ojo 'eye' |
| hoja | leaf; page; blade | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.420; root of the hojalata/hojarasca/hojaldre/hojuela family (all with h) |
| ojo | eye | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.420; root of the ojal/ojera/ojeada/ojeo/ojeriza/ojete family (all without h) |
| ha | has/have (haber, 3sg pres., auxiliary) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.421; homophone trio ha/a/ah; auxiliary in pretérito perfecto and haber de + infinitive periphrasis |
| a | to, at (preposition) | preposition | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.421; homophone trio ha/a/ah |
| ah | ah! (interjection) | interjection | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.421; homophone trio ha/a/ah |
| haya | (that) there be/have (haber, pres. subj.); also 'beech tree' | verb form/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.421; homophone pair haya/aya — both verbal (haber subj.) and nominal ('beech') senses |
| aya | nanny, governess | noun | archaic | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.421; homophone pair with haya; dated/literary term for 'nanny' |
| rehusar | to refuse, decline | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.422; homophone pair rehusar/reusar ('refuse' vs 'reuse') |
| reusar | to reuse | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.422; homophone pair with rehusar |
| herrar | to shoe (a horse) | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.422; homophone pair herrar/errar |
| errar | to err, be mistaken; to wander | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.422; homophone pair with herrar |
| habría | would have (haber, conditional) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.422; homophone pair habría/abría |
| abría | (he/she/I) was opening (abrir, imperfect) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.422; homophone pair with habría |
| honda | deep (fem.); sling (weapon) | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.422; homophone pair honda/onda (fem. of hondo, or 'sling') |
| onda | wave | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.422; homophone pair with honda |
| había | there was/were; had (haber, imperfect) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair había/avía |
| avía | (he/she) readies/prepares (aviar, 3sg pres.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair with había |
| hizo | (he/she) did/made (hacer, preterite) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair hizo/izo |
| izo | (I) hoist/raise (izar, 1sg pres.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair with hizo |
| ¡hala! | wow!/come on! (interjection) | interjection | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair ¡hala!/ala |
| ala | wing | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair with ¡hala! |
| hasta | until, up to (preposition) | preposition | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair hasta/asta |
| asta | horn (of an animal); flagpole/shaft | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair with hasta |
| huso | spindle (for spinning) | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair huso/uso |
| uso | use (noun); (I) use (usar, 1sg pres.) | noun/verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair with huso |
| hato | small herd; bundle of belongings | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair hato/ato |
| ato | (I) tie (atar, 1sg pres.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair with hato |
| hora | hour | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair hora/ora |
| ora | (he/she) prays (orar, 3sg pres.); or...or (conjunction) | verb form/conjunction | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair with hora |
| ¡hola! | hello! | interjection | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair ¡hola!/ola |
| ola | wave (sea) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.423; homophone pair with ¡hola! |
| hincapié / hincar | emphasis (hacer hincapié = 'to emphasize') / to drive in, stick in | noun/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial lexical family |
| halago, halagar, halagador, halagüeño | flattery / to flatter / flattering / promising-sounding | noun/verb/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial family; distinguished from the h-less verb alagar 'to flood/fill with puddles' |
| alagar | to flood, fill with puddles | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; explicitly distinguished (no h) from the halago/halagar family |
| hastío, hastiar | boredom, weariness / to bore, weary | noun/verb | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial family |
| hedor, hediondo, heder, hediondez | stench / foul-smelling / to stink / foulness | noun/adjective/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial family |
| hegemonía, hegemónico | hegemony / hegemonic | noun/adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial family |
| hocico, hocicudo, hozar | snout / big-snouted / to root around (pig) | noun/adjective/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial family |
| hogar, hoguera, hogareño, hogaza | home, hearth / bonfire / home-loving / large loaf | noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial family |
| horca, horquilla | gallows; pitchfork / hairpin, forked stick | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial family |
| hostil, hostilidad, hostilizar, hueste | hostile / hostility / to harass / army, host | adjective/noun/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial family |
| hoyo, hoya, hoyuelo | hole, pit / large pit/valley / dimple | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; h-initial family; ATENCIÓN distinguishes hoya ('large hollow in the earth') from olla ('cooking pot', unrelated, no h) |
| olla | (cooking) pot | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; explicitly distinguished (no h) from hoya in the ATENCIÓN box |
| hado | fate, destiny | noun | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; error-prone h- word |
| halo | halo | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; error-prone h- word |
| hamaca | hammock | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; error-prone h- word |
| hampa | criminal underworld | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; error-prone h- word |
| hebilla | buckle | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; error-prone h- word |
| hecatombe | hecatomb, disaster | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; error-prone h- word |
| hez (heces) | dregs; (pl.) feces | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.424; error-prone h- word |
| hechura | craftsmanship, making | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; h- family word (from hacer) |
| henchir | to fill, stuff | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hilaridad | hilarity | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hinojo | fennel; (archaic, de hinojos) kneeling | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hirsuto | hirsute, bristly | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hito | milestone, landmark | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hollín | soot | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hortera, horterada | tacky/tasteless (person); tacky thing/act | adjective/noun | colloquial | — | contemporary (2005) | Spain | national | grammar_reference | n/a | verified | p.425; error-prone h- word, colloquial Peninsular register |
| hosco | sullen, surly | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hostigar | to harass, pester | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hoz | sickle | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hucha | piggy bank, savings box | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| huracán | hurricane | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| huraño | unsociable, shy | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hurgar | to poke, rummage | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| hurtar | to steal, pilfer | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; error-prone h- word |
| ilación | coherence, logical connection | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; ATENCIÓN — explicitly NO h despite surface resemblance to the hilo/hilar family; unrelated word |
| ilativo | illative (expresses logical connection) | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.425; ATENCIÓN — explicitly NO h, paired with ilación |
| adherir, adherente, adherencia, adhesivo, adhesión, inherente, inherencia, coherente, coherencia, cohesión, cohesionar | to adhere / adherent / adherence / adhesive / adhesion / inherent / inherence / coherent / coherence / cohesion / to bring together | verb/adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; -h- intercalada lexical family (single shared root pattern across several prefixed forms) |
| exhalar, exhalación, inhalar, inhalación | to exhale / exhalation / to inhale / inhalation | verb/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; -h- intercalada family |
| exhortar, exhortación, exhortativo | to exhort / exhortation / exhortative | verb/noun/adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; -h- intercalada family |
| inhibir, inhibición, exhibir, exhibición, exhibicionismo, exhibicionista, cohibir, prohibir, prohibición, prohibitivo | to inhibit / inhibition / to exhibit / exhibition / exhibitionism / exhibitionist / to restrain (oneself) / to prohibit / prohibition / prohibitive | verb/noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; large -h- intercalada family sharing the -hib-/-hab- root pattern |
| vehículo, vehemente, vehemencia | vehicle / vehement / vehemence | noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; -h- intercalada family |
| exuberante | exuberant | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; ATENCIÓN — explicitly does NOT take intercalated -h- despite its shape, unlike the exhalar/exhibir family |
| transeúnte | passer-by, pedestrian | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; ATENCIÓN — explicitly no -h- |
| incoar | to initiate (a legal/formal process) | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; ATENCIÓN — explicitly no -h- |
| coercitivo | coercive | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; ATENCIÓN — explicitly no -h- |
| coartar | to restrict, curtail | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; ATENCIÓN — explicitly no -h- |
| coacción | coercion | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; ATENCIÓN — explicitly no -h- |
| ahínco | eagerness, zeal | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| ahuyentar | to scare off, drive away | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| alcahuete | procurer, go-between (often pejorative) | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| alhaja | jewel | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| almohada | pillow | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| anhelar, anhelante, anhelo | to yearn for / yearning (adj.) / yearning (noun) | verb/adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada family |
| bohemio | bohemian | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| cacahuete | peanut | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| cohete | rocket; firework | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| desahuciar, desahucio | to evict/give up hope on / eviction | verb/noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word (cross-listed with p.418's vahído/vaho group) |
| enhebrar | to thread (a needle) | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| enhiesto | upright, erect (literary) | adjective | literary | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| moho, enmohecer | mold, mildew / to go moldy | noun/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| retahíla | string, series (of things) | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| trashumante, trashumancia | transhumant (seasonally migratory, of livestock) / transhumance | adjective/noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word, pastoral/technical register |
| zaherir | to hurt (with cruel words), taunt | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.426; error-prone -h- intercalada word |
| acera / hacera | sidewalk | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted h/no-h spelling alternation; acera is the preferred DRAE form |
| ¡ah! / ¡ha! | ah! | interjection | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| albahaca / albaca | basil | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation; albahaca preferred |
| alhelí / alelí | wallflower (flower) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| armonía / harmonía | harmony | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation; armonía preferred |
| arpa / harpa | harp | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| arpía / harpía | harpy; shrewish woman | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| arpillera / harpillera | burlap, sackcloth | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| ¡arre! / ¡harre! | giddy-up! | interjection | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| arrear / harrear | to drive on (animals); to hurry along | verb | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| arriero / harriero | muleteer | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| ¡eh! / ¡he! | hey! | interjection | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| ¡hala! / ¡alá! | come on!/wow! | interjection | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation, distinct from the ¡hala!/ala homophone pair on p.423 |
| hexagonal / exagonal | hexagonal | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation; hexagonal preferred |
| hexágono / exágono | hexagon | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| hogaño / ogaño | nowadays (archaic/dialectal) | adverb | archaic | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation, dated usage |
| reprender / reprehender | to reprimand, scold | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation; reprender preferred |
| sabiondo / sabihondo | know-it-all | noun/adjective | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| ¡uf! / ¡huf! | ugh!/phew! | interjection | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| urraca / hurraca | magpie | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation; urraca preferred |
| aprehender | to apprehend, capture; to come to know | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; synonym of aprender ('to learn') ONLY in the 'come to know' sense; for 'seize/catch' or 'confiscate contraband' senses only aprehender is used, never aprender |
| hatajo / atajo | small herd (of livestock); group of people/things (often pejorative) | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; hatajo and atajo are interchangeable in the 'small group' sense; only atajo (no h) is correct for 'shortcut/path' |
| atajo | shortcut, short path | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; exclusively h-less when meaning 'shortcut/path'; see hatajo entry for the overlapping sense |
| hierba / yerba | grass, herb | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation (yerba more common in parts of Latin America, though book doesn't mark region explicitly) |
| hiedra / yedra | ivy | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.427; RAE-admitted alternation |
| wolframio | tungsten (wolfram) | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; w pronounced [b] in words fully nativized into Spanish: [bolfrámjo] |
| wagneriano | Wagnerian | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; w→[b] nativized pronunciation: [bagnerjáno] |
| whisky | whisky | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; w pronounced as semiconsonant [w] in some English loanwords: [wíski] |
| washingtoniano | Washingtonian | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; w→[w] semiconsonant: [wasintonjáno] |
| váter | toilet (from English "water") | noun | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; RAE-adapted spelling, w respelled as v: water→váter |
| darviniano | Darwinian (RAE-adapted spelling) | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; RAE-adapted spelling: darwiniano→darviniano |
| Wenceslao | Wenceslaus (proper name, German origin) | proper noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; w→[b] in German-origin proper names: [benθesláo] |
| Wamba | Wamba (Visigothic king's name) | proper noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; w→[b] in German-origin proper names: [bámba] |
| Wellington | Wellington (proper name, English origin) | proper noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; w→[w] semiconsonant in English-origin proper names: [wélinton] |
| Washington | Washington (proper name, English origin) | proper noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; w→[w]: [wásinton] |
| absolver | to acquit; to absolve | verb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v word (distinguished from confusable absorber, see ATENCIÓN p.431) |
| adverbio | adverb | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v word |
| benévolo, benevolencia, benevolente, benévolamente | benevolent / benevolence / benevolent (var.) / benevolently | adjective/noun/adverb | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v family |
| bóveda | vault (architecture) | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v word |
| bovino | bovine | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v word |
| bravo, bravucón, bravata, bravura | brave; fierce / blusterer, braggart / bravado / bravery | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v family |
| breve, breviario, abreviar, abreviatura | brief / breviary / to abbreviate / abbreviation | adjective/noun/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v family |
| bulevar | boulevard | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v word (loanword) |
| herbívoro | herbivore | noun/adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; from hierba+-voro; error-prone b/v word; cross-ref -voro/-vora family p.432 |
| objetivo, objetividad | objective (adj./noun) / objectivity | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v family |
| observar, observación, observador | to observe / observation / observer | verb/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.428; error-prone b/v family |
| obvio, obviedad | obvious / obviousness | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v family |
| reverberar, reverberación | to reverberate / reverberation | verb/noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v family |
| subjetivo | subjective | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v word |
| subjuntivo | subjunctive | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v word |
| sublevar, sublevación | to rise up, rebel / uprising | verb/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v family |
| vagabundo | vagabond, tramp | noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v word |
| verbena | summer street party/festival; verbena (plant) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v word |
| verbo | verb | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v word |
| vestíbulo | vestibule, hallway, foyer | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v word |
| víbora | viper | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v word |
| vibrar, vibración, vibrátil | to vibrate / vibration / vibratile | verb/noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v family |
| vocabulario | vocabulary | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.429; error-prone b/v word |
| escribir, percibir, concebir | to write / to perceive / to conceive | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; -bir verbs always take b (except hervir/servir/vivir and compounds) |
| hervir, servir, vivir | to boil / to serve / to live | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; the three -bir-ending exceptions that take v, not b |
| atribuir, distribuir | to attribute / to distribute | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; -buir verbs always take b |
| meditabundo | meditative, pensive | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; -bundo ending always takes b |
| posibilidad | possibility | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; -bilidad ending takes b, except movilidad/civilidad |
| movilidad, civilidad | mobility / civility | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; exceptions to the -bilidad→b rule (these take v: movi-v-ilidad root, civi-v-ilidad) |
| absolución, objeción, suburbano | absolution / objection / suburban | noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; words beginning with prefixes ab-/ob-/sub- take b |
| abalanzarse | to lunge, pounce | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; error-prone b word |
| abeja | bee | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; error-prone b word |
| absorbente, absorber, sorber, sorbete, sorbo | absorbent / to absorb / to sip, sup / sorbet / a sip | adjective/verb/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; error-prone b family; absorber is explicitly distinguished from the unrelated verb absolver (ATENCIÓN p.431) |
| abulia, abúlico | apathy, lack of willpower / apathetic | noun/adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.430; error-prone b family |
| baldío | fallow, uncultivated; futile | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| barbecho | fallow land | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| barbudo | bearded, heavily-bearded | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| bayeta | cleaning cloth, dishrag | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| bayonesa | bayonnaise pastry (sweet pastry type) | noun | regional | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| bayoneta | bayonet | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| corroborar, corroboración | to corroborate / corroboration | verb/noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b family |
| chabola | shack, shanty | noun | colloquial | — | contemporary (2005) | Spain | national | grammar_reference | n/a | verified | p.431; error-prone b word, Peninsular colloquial register |
| deber | to owe; must/should (modal) | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| débil, debilidad | weak / weakness | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b family |
| hábil, habilidad | skillful / skill, ability | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b family |
| mobiliario | furniture | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| pabilo / pábilo, despabilar | candle wick / to trim a wick; to wake up, liven up | noun/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word with alternate stress-spelling pabilo/pábilo |
| pábulo | fuel (figurative — "dar pábulo a" = to fuel/encourage rumors) | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| plebe | common people, plebs | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| probar, aprobar | to try, test; to prove / to pass (an exam); to approve | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b family |
| sílaba, silábico | syllable / syllabic | noun/adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b family |
| suburbio | suburb, slum outskirts | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| tibio | lukewarm | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b word |
| titubeo, titubear | hesitation / to hesitate, waver | noun/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.431; error-prone b family |
| advenedizo | upstart, parvenu | noun/adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; ad-/sub- prefix + /b/ phoneme takes v |
| subvalorar | to undervalue | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; same ad-/sub-+/b/ rule |
| doceava | one twelfth | adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; -ava ending takes v |
| suave | soft, smooth, gentle | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; -ave ending takes v |
| octavo | eighth | adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; -avo ending takes v |
| motivo | motive, reason | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; -ivo ending takes v |
| objetivo | objective | noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; -ivo ending takes v |
| cautivo | captive | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; -ivo ending takes v |
| estribo | stirrup | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; explicit exception to the -ivo/-bo→v rule (takes b) |
| tuve, tuviste, tuvo | I had / you had / he-she had (tener, preterite) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; preterite forms ending -uve always take v, except haber |
| anduve, anduviste, anduvo | I walked / you walked / he-she walked (andar, preterite) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; same -uve preterite rule |
| hube, hubiste, hubo | I had / you had / he-she had (haber, preterite) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; explicit exception — haber's -ube preterite takes b, not v |
| tuviera, tuviere | I/he-she had (tener, past/future subj.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; same v-pattern extends to imperfect/future subjunctive |
| anduviera, anduviere | I/he-she walked (andar, past/future subj.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; same v-pattern |
| hubiera, hubiere | I/he-she had (haber, past/future subj.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; haber exception continues into subjunctive (b, not v) |
| voy, vas, vaya | I go / you go / that he-she go (ir, present/subj.) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; ir forms with /b/ phoneme take v, except imperfect indicative |
| iba, ibas | I was going / you were going (ir, imperfect) | verb form | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; explicit exception — ir's imperfect indicative takes b, not v |
| vicerrector, vicealmirante, vicesecretario | vice-rector / vice-admiral / vice-secretary | noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; vice- prefix always takes v |
| omnívoro, carnívora, herbívoro | omnivore / carnivorous (fem.) / herbivore | noun/adjective | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; -voro/-vora ending always takes v |
| absolver, resolver, disolver | to acquit/absolve / to resolve / to dissolve | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; error-prone v family |
| anverso, reverso, revés, envés | obverse (face of a coin) / reverse / wrong side; setback / underside (of a leaf) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; error-prone v family |
| avalancha | avalanche | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; error-prone v word |
| avispa, avispero | wasp / wasp's nest; (figurative) hornet's nest situation | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; error-prone v family |
| avutarda | great bustard (bird) | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; error-prone v word |
| cavidad | cavity | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.432; error-prone v word |
| cavilar, cavilación | to ponder, brood / brooding, deep thought | verb/noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| convalidar, convalidación | to validate (credits/degrees); to ratify / validation | verb/noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| converger, diverger | to converge / to diverge | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| convidar, convite | to invite (to a meal/event) / invitation, treat | verb/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| convocar, revocar, invocar, desconvocar, vocación | to convene; to summon / to revoke / to invoke / to uncall (a meeting/strike) / vocation | verb/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| depravar, depravación, depravado | to corrupt, deprave / depravity / depraved | verb/noun/adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| devastar, devastación | to devastate / devastation | verb/noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| evadir, evasión, evasivo | to evade / evasion / evasive | verb/noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| invernar | to hibernate; to winter (somewhere) | verb | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v word |
| jovial, jovialidad | jovial / joviality | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| novel, novato, novatada, novedad, novedoso, innovar, innovación, renovar, renovación | novice (adj.) / novice (noun) / hazing / novelty / novel, new / to innovate / innovation / to renew / renewal | adjective/noun/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; large error-prone v family |
| párvulo, parvulario | small child, toddler / preschool, kindergarten | noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| precaver, precavido | to guard against, take precautions / cautious | verb/adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| unívoco, equívoco | unambiguous, univocal / ambiguous; mistake | adjective/noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| vagar, vago, vaguedad, vacación, extravagante | to wander / lazy; vague / vagueness / vacation | verb/adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| vaivén | swaying, back-and-forth motion | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v word |
| válvula | valve | noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v word |
| vaticinar, vaticinio | to prophesy, predict / prophecy, prediction | verb/noun | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| vendaval | strong wind, gale | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v word |
| ventisca | blizzard, snowstorm | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v word |
| verruga | wart | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v word |
| vespertino, víspera | evening (adj.); evening edition (newspaper) / eve, day before | adjective/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| viceversa | vice versa | adverb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v word |
| viscoso, viscosidad | viscous / viscosity | adjective/noun | technical | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| visera | visor, peak (of a cap) | noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v word |
| voluble | fickle, changeable | adjective | formal | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v word |
| voraz, vorágine, voracidad, devorar | voracious / maelstrom, vortex / voracity / to devour | adjective/noun/verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.433; error-prone v family |
| grabar, grabado, grabación, grabador | to record; to engrave / recording (noun); engraved / recording (process) / recorder, engraver | verb/noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.434; homophone pair grabar/gravar; family entirely with b |
| gravar, gravamen, grave, gravitar, gravoso, gravedad, gravidez, ingravidez, desgravar | to tax, burden / tax, encumbrance / serious; heavy / to gravitate / burdensome / gravity; seriousness / pregnancy / weightlessness / to deduct, tax-exempt | verb/noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.434; homophone pair with grabar; family entirely with v |
| rebelarse, rebelde, rebeldía, rebelión, belicoso, beligerante, beligerancia | to rebel / rebel, rebellious / rebelliousness / rebellion / belligerent, warlike / belligerent (adj.) / belligerence | verb/noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.434; homophone pair rebelarse/revelar; family from Latin bellum 'war', entirely with b |
| revelar, revelación, revelador, velar, velo, veleta, velero | to reveal; to develop (film) / revelation / revealing (adj./noun, e.g. photo developer) / to veil; to keep watch / veil / weathervane / sailboat | verb/noun/adjective | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.434; homophone pair with rebelarse; family from Latin velum 'veil/sail/curtain', entirely with v |
| desvelar, velar ('estar sin dormir'), velada, velador | to keep (someone) awake; to reveal (fig.) / to stay awake / evening gathering, soirée / night-watchman; small round table | verb/noun | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.434; ATENCIÓN — separate family from Latin vigiliam 'vigil', also with v; velar here is a homonym (not homophone) of the 'to veil' sense above |
| haber | to have (auxiliary); there to be; must/have-to (periphrasis) | verb | core | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.435; distinguished from the homophonous construction "a ver"; main/auxiliary verb uses illustrated in detail |
| a ver | let's see (lit. "to see") | discourse marker/phrase | colloquial | — | contemporary (2005) | — | — | grammar_reference | n/a | verified | p.435; homophone of haber; grammaticalized into appellative ("a ver si os calláis") and phatic ("vamos a ver, ¿cómo te llamas?") discourse-marker uses |

### Grammar points

#### Allophones of /n/ (p.394)

/n/ has seven contextual realizations in Spanish, each conditioned by what follows: alveolar [n]
word-initially, between vowels, or before other alveolar consonants (*nada, cana, insípido*);
labialized [m] before labial /p/, /b/, /m/ (*envidia, ampolla*); labiodentalized [ɱ] before /f/
(*anfibio*); interdentalized before /θ/ (*anzuelo*); dentalized before /t/,/d/ (*antes, andas*);
palatalized before palatal /tʃ/,/ʝ/ (*ancho, cónyuge*); and velarized before /k/,/g/,/x/ (*ancla,
hongo, ángel*). The underlying phoneme is a single /n/; the allophone is purely a function of the
following segment's place of articulation (regressive place assimilation).

#### Allophones of /l/ (p.394)

/l/ has four contextual allophones: dentalized before a dental consonant (*alto, toldo*);
interdentalized before /θ/ (*alzo*); palatalized before a palatal consonant (*colcha*); and plain
alveolar [l] elsewhere, the default/unmarked case (*pala*).

#### Allophones of the vocalic phonemes /i/ and /u/ (p.395)

Unlike consonants, vowel allophones aren't described in fine-grained detail by this source — only
the semivocalic and semiconsonantal realizations of /i/ and /u/ are singled out. /i/ surfaces as
semivowel [i̯] as the second element of a decreasing diphthong or third element of a triphthong
(*peine, buey*), and as semiconsonant [j] as the first element of an increasing diphthong or in a
triphthong (*pie, limpiéis*). /u/ parallels this: semivowel [u̯] as second element of a decreasing
diphthong or third of a triphthong (*causa, guau*), semiconsonant [w] as first element of an
increasing diphthong or in a triphthong (*puerta, averiguáis*).

#### Vowel nasalization and consonantal y/u (p.395, ATENCIÓN)

When a vowel sits between two nasal consonants, or between a pause and a nasal consonant, it
nasalizes (marked with a tilde: [banãna], [ẽmãnár]). Separately, the conjunction *y* ('and') has
three distinct phonetic realizations depending on context: as [i] between consonants (*cantar i
reír*), as [ʝ] between a consonant and a vowel or between two vowels (*temór i ódjo* → [temóɾ‿i ódʝo],
*mjédo i ódjo*), and as [i̯] between a vowel and a consonant (*kárne i̯ peskádo*). The conjunction *u*
('or', used before o-/ho-) is realized as [w]: *sjéte u óčo* → [sjete w óčo].

#### Phonetic vs. phonological transcription (pp.396–397)

Phonetic transcription reproduces contextual allophones (the norma/realized sounds), taking into
account both the word's own context and the wider discourse — e.g. the same /n/ phoneme surfaces as
[m] both word-internally (*envidia*) and across a word boundary in connected speech (*un vaso* →
[úmbáso]); the same applies to the fricative [ð̞] allophone of /d/ between vowels, whether word-
internal (*amado*) or across a boundary (*lo demás* → [lo ðemás]). Phonological transcription, by
contrast, reproduces only phonemes and archiphonemes (written with the corresponding capital letter),
never contextual variants. Archiphonemes mark positions of phonemic neutralization: **B** = neutral­
ization of /p/–/b/ before a non-liquid consonant; **R** = neutralization of /r/–/r̄/ in word-final
position; **N** = neutralization of /n/–/m/ before a consonant. In both transcription types, every
tonic (stressed) vowel must be marked with a tilde, since stress is phonologically contrastive in
Spanish (*pie* [pjé] vs. *pie* [píe] vs. *pié* [pié] are all distinct). Vertical bars in either
transcription type mark pauses.

#### The syllable (p.398)

A syllable is a non-minimal phonetic unit of the speech chain, without meaning of its own. It
consists of one sound or a group of sounds, built around a central element or **núcleo** (nucleus)
which in Spanish is always a vowel; consonantal sounds may flank the nucleus before and/or after as
**márgenes silábicos** (syllabic margins). Every syllable passes through three phases — initial,
central (nucleus), final — though a single-sound syllable condenses all three into one.

#### Tonic and atonic vowels (p.398)

The syllabic nucleus is characterized by degree of intensity, sonority, aperture, muscular tension,
and perceptibility. The **tonic vowel** is the nucleus with the greatest intensity/clearest
articulation within a word or phonic group (e.g. the first *a* in *hábito*, the *e* in *andén*); all
other nuclei are **atonic vowels** (lower intensity, less articulatorily distinct). Syllables
containing the tonic vowel are tonic syllables; the rest are atonic syllables.

#### Open (abiertas) vs. closed/trabada (trabadas) syllables (p.399)

A syllable ending in a vowel is **abierta** (open) — e.g. *pa-ya-so, ce-ni-za, ca-cha-rro*. A
syllable ending in one or more consonants is **trabada** (closed) — e.g. *ins-truc-ción, ma-les-tar,
ap-ti-tud*.

#### ATENCIÓN — double cc, the letter x, and silent h in syllabification (p.399)

Three special cases affect syllable counting/division: (1) When a word contains a double *cc*, the
two letters belong to different syllables — the first realizes [k] (or voiced [g]), the second
realizes [θ] (e.g. *ac-ción* → [akθjón] or [agθjón]). (2) The letter *x* represents two phonemes,
/k/+/s/; consequently the first syllable of any word containing *x* is always trabada, especially
when *x* precedes a consonant (*examen* → [ek-sá-men], *éxtasis* → [éks-ta-sis]); when *x* falls
between vowels, /k/ and /s/ split across two syllables (*éxodo* → [ék-so-do]), but when *x* precedes
a consonant both phonemes stay in the same (trabada) syllable (*expectante* → [eks-pek-tán-te]). (3)
The letter *h* is never pronounced in Spanish and consequently never counts for syllable division —
*héroe* → [é-ro-e], *cohesión* → [ko-e-sjón], *inhumar* → [i-nu-már], *inhibir* → [i-ni-bír]. This
graphic/phonetic division into syllables must not be confused with division into morphemes (minimal
meaningful units): *in-hum-ar* = prefix + root + suffix; *in-hib-ir* = prefix + root + suffix.

#### Diphthongs and triphthongs (p.400)

A **diptongo** is the union of two vowels within a single syllable; a **triptongo**, three vowels
within a single syllable. Diphthongs form from an open vowel (*a, e, o*) plus a closed vowel (*i,
u*), or the reverse — the closed element is realized as a semivowel ([i̯], [u̯]) when it follows the
open vowel (**diptongo decreciente**, "decreasing diphthong": *pei-nen, cau-sa, boi-na, soy,
náu-sea* — articulators move from open to closed), and as a semiconsonant ([j], [w]) when it precedes
the open vowel (**diptongo creciente**, "increasing diphthong": *cien, cien-to, pues, pues-to* —
articulators move from closed to open). When both vowels in a diphthong are closed (*i+u* or *u+i*),
the nucleus is always the *second* vowel, and the first is a semiconsonant: *viu-do* → [bjúdo],
*cui-da* → [kwída]. Consequently, any written tilde on a diphthong must fall on the true nucleus. In
a triphthong, the nucleus is always the middle vowel, which is always open (*e* or *a*): *a-ves-ti-
güéis* → [atestiɣwéi̯s], *a-cu-ciáis* → [akuθjái̯s]; a triphthong's tilde likewise falls on this
nucleus.

#### Hiatos (p.401)

A **hiato** is formed by two contiguous vowels belonging to *different* syllables, pronounced as two
separate articulatory pulses rather than fused into one syllable. Four classes exist, by which vowel
types combine: two open vowels (*te-be-o, be-o-do, ca-o-ba, me-o-llo*); a closed, stressed vowel
followed by an open vowel (*tí-o, pú-a, rí-o, pí-e*); an open vowel followed by a closed, stressed
vowel (*ta-húr, ra-íl, re-íd, Ra-úl*); or two closed vowels where the second is stressed (*ti-í-ta,
di-ur-no, hu-id*). The *h* never counts toward hiato status either, being a purely phonetic
(pronunciation-level) phenomenon, like diphthongs/triphthongs, rather than a graphic one. In
spontaneous colloquial speech, atonic hiatos formed from two open vowels tend to collapse into
diphthongs (*Jo-a-quín* → *Joa-quín* → colloquial *[xwakín]*; *a-é-re-o* → *a-é-reo* → colloquial
*[aérjo]*); the avoidance of this tendency sometimes produces hypercorrection (ultracorrección)
errors in the opposite direction (*\*ge-rá-ne-o* for correct *ge-ra-nio*; *\*es-pú-re-o* for correct
*es-pu-rio*). In a smaller set of words, the diphthong/hiato choice is genuinely speaker- or
region-dependent, with no single correct answer: the *ui* sequence in words like *jesuita*
([xe-swí-ta] or [xe-su-í-ta]), words ending in *-iaco* (*austriaco, cardiaco*: [-trjáko] or
[-trí-a-ko]), and isolated words like *período* and *cruel*.

#### Syllabification rules in Spanish (pp.402–403)

A full rule set for dividing Spanish words into syllables: (1) A single consonant between two vowels
groups with the *second* vowel (*ca-se-ta, va-ya-mos*). (2) The sequences *pr, br, fr, gr, kr/cr, pl,
bl, fl, gl, kl/cl* (stop or /f/ + liquid /l/ or /r/) are inseparable groups that stay together in one
syllable (*pri-mi-cia, a-bri-go, fri-to, con-grio, a-e-ro-pla-no, blan-do, a-fli-gir, á-cra-ta*) — with
an exception: words prefixed with *sub-, ob-, ab-* split the prefix-final *b* from a following *r* or
*l* (*sub-ra-yar, sub-rep-ti-cio, ob-lon-go, sub-li-mi-nal, ab-ro-gar, ob-li-te-rar*). (3) *tr* and
*dr* are likewise always inseparable (*a-trás, a-dre-de, tra-go*), but *tl* and *dl* usually split
into different syllables in Peninsular speech (*at-las, at-le-ta, ad-lá-te-re*) while staying together
in one syllable in the Canary Islands and Hispanic America (*a-tlas, a-tle-ta, a-tlé-ti-co*) — an
explicit regional/dialectal split the source itself marks. (4) Any other two-consonant sequence not
covered above splits across syllables, one consonant each (*con-so-nan-te, in-viér-te-lo, lec-ción*).
(5) When a consonant cluster is word-initial (and therefore has no vowel to its left), both
consonants stay together in the same syllable (*psi-co-lo-gí-a, mne-mo-téc-ni-co, gno-mo*) — though
the general pronunciation tendency is to simplify/reduce such clusters to just the second consonant.
(6) Three consonants together, with the last being a liquid (*l, r*): the first consonant splits off
into the preceding syllable, the remaining two (stop+liquid) stay together with what follows
(*con-fra-ter-nar, com-pro-bar, ham-bre*). (7) Three consonants together, with the last *not* a
liquid: the first two group into the preceding syllable, the third starts a new syllable — this
always involves the specific clusters *ns, bs, ks(x), ds,* or *rs* + consonant (*ins-pec-ción,
abs-tra-er, éks-ta-sis, ads-cri-to, pers-pec-ti-va*). (8) Other three-consonant groupings occur only
in loanwords (*hams-ter*), with rare exceptions like *ist-mo*; a genuine three-consonant single
syllable also occurs in loanwords (*gángs-ter*). (9) Vowels in hiato always belong to different
syllables (*áu-re-o, hé-ro-e, he-roi-co, ha-bí-a*); vowels in diphthong always belong to the same
syllable (*pei-nen, pio-jo, a-cen-tú-o, sa-lió*).

#### Tonic (palabras tónicas) vs. atonic (palabras átonas) words (p.404)

A word is **tónica** if it contains a tonic (stressed) syllable, **átona** if it contains none — in
general, words are tonic or atonic only *in connected discourse*; in isolation, every word is tonic.
As a rule, content-word classes (nouns, adjectives, non-apocopated determiners, verbs, most adverbs,
interjections) and certain pronouns (personal *yo, tú, mí, ti, sí, él,* etc.; interrogative/
exclamative *quién, qué, cuál*, etc.) are tonic. Function-word classes (articles, most prepositions —
except *según*, which is tonic —, conjunctions, apocopated possessives *mi, mis, tu, tus, su, sus*,
relative *que, quien, cuanto*, etc., and object clitics *me, te, se, le, les, las, los, lo, nos, os*)
are normally atonic. Certain normally-atonic words can become tonic under expressive emphasis
(*¡Mi madre!, ¡Es tan rico!*), and conversely certain normally-tonic words become atonic in specific
constructions: nouns/adjectives used as address-titles (*señor Juan, don Pedro, santo Tomás*) or as
the first element of a compound proper name (*Juan José, José María*); the first cardinal number of a
compound numeral (*dos mil, veinte mil seiscientos*); certain vocative-preceding elements (*buen
hombre, amigo mío, tío tonto*) and fixed combinations (*patas abajo, cuesta arriba, guardia civil*);
*cual* with modal value (*caminaba cual serpiente*); and the possessives *nuestro/vuestro* (and their
variants) when used as pre-nominal determiners, though they're tonic as post-nominal modifiers
(*nuestros hijos* vs. *los hijos nuestros*). Adverbs ending in *-mente* uniquely carry two tonic
syllables — the adjective's own stress plus *mente*'s (*verosímilmente*).

#### Classification of words by syllable count and stress position (p.405)

By number of syllables: monosílabas (one syllable, *sal*), bisílabas (two, *so-lo*), trisílabas
(three, *mam-pa-ra*), cuatrisílabas (four, *en-tré-ga-lo*), and so on. By the position of the tonic
syllable: **agudas** (oxítonas) — stress on the last syllable (*re-co-GER*); **llanas** (paroxítonas)
— stress on the penultimate syllable (*SA-le*); **esdrújulas** (proparoxítonas) — stress on the
antepenultimate syllable (*DÍ-me-lo*); **sobresdrújulas** — stress even earlier than the
antepenultimate (*CAN-tá-ba-me-lo*).

#### Expressive/affected accent (p.405)

Spanish tonic words (aside from *-mente* adverbs) normally carry a single tonic syllable, but in
spoken usage speakers may add a second tonic syllable for expressiveness or emphasis (*imponente* →
normally one tonic syllable, *-NEN-*; emphatically, two). In affected speech, normally-atonic
syllables/words can likewise become tonic (*Les digo, señores, que MI responsabilidad EN ese acto es
enorme* — bolded elements tonic only under affectation).

#### Intonation: concept and functional value (p.406)

An **enunciado** (utterance) is the minimal communicative unit, always framed by major pauses. Beyond
its phonemes, syllables, morphemes, words, and syntactic groups, every utterance is accompanied by a
melody produced by variation in vocal-cord tension — this melody is **entonación** (intonation).
Intonation is a genuinely significant feature, moving between the phonic plane (pitch, intensity,
duration) and the language's own significative plane, since it signifies by itself: it is precisely
what lets a hearer know whether the speaker intends assertion, question, exclamation, command, etc.,
on top of other situational/individual nuances. These meanings belong to the concept of **modalidad**
(modality) — intonation expresses assertive, interrogative, and exclamative modality (*Ha llegado tu
primo.* / *¿Ha llegado tu primo?* / *¡Ha llegado tu primo!*); in writing, interrogative and
exclamative modality are marked with question/exclamation marks.

#### The melodic curve (curva melódica) and its three phases (p.406)

The melody accompanying an utterance/phonic group is expressed as a **curva melódica** (melodic
curve) or sequence of pitches, with three phases: **fase inicial** (initial phase), from the start of
the utterance to the first tonic element, during which vocal cords tense and pitch rises; **fase
media** (medial phase), which holds roughly level with little oscillation; and **fase final** (final
phase), beginning at the utterance's last tonic element and running to its end.

#### Tonemas (p.407)

Of the melodic curve's three phases, the truly significant/pertinent one is the final phase; its
rising or falling inflection is called a **tonema**. Spanish distinguishes three fundamental tonemas
and two subvarieties. **Cadencia** (falling inflection) marks the end of an assertive utterance, a
partial interrogative utterance, or an exclamative utterance. **Anticadencia** (rising inflection)
marks the end of a total (yes/no) interrogative utterance. **Suspensión** (no inflection, neither
rising nor falling) marks an interruption, appearing in incomplete utterances or parenthetical
asides/incises. Within an utterance, segments set off by minor pauses (usually a comma) can end in
one of two tonema subvarieties: **semicadencia** (falling, but less steeply than full cadencia) or
**semianticadencia** (rising, but less steeply than full anticadencia).

#### Intonation schemes by modality (pp.408–409)

Peninsular Spanish has characteristic entonativos schemes per modality (broadly shared with, but not
identical to, Canarian/Hispanic-American schemes, an explicit regional caveat). **Modalidad
asertiva**: pitch rises from the initial phase to the first tonic syllable, holds level through the
medial phase to the last tonic syllable, then descends in cadencia to the end. **Modalidad
interrogativa**: for partial (wh-)questions, parallels the assertive pattern but the final descent
starts from the medial phase itself (the interrogative pronoun/adverb itself carries the
"questioning" function, so the tonema doesn't need to rise) — sometimes with a slight final rise after
the medial-phase descent, or even a circumflex-shaped final phase; for total (yes/no) questions, the
final inflection is anticadencia (rising) from the last stressed syllable onward. **Modalidad
exclamativa**: pitch rises in the initial phase to a greater degree than in assertive utterances, then
descends abruptly to a cadencia — the overall curve is highly variable given the wide range of
possible emotional states behind an exclamation.

#### Grupos fónicos (phonic groups) (p.409)

A **grupo fónico** is a portion of discourse bounded by pauses and belonging to a single utterance. An
utterance with no internal pauses is itself a single phonic group; but a longer utterance can contain
multiple phonic groups, each with its own partial melodic curve, normally ending in semianticadencia,
suspensión, or semicadencia (e.g. *El otro día, [semianticadencia] al salir de casa, [suspensión] me
encontré con tu padre. [cadencia]*).

#### Causes of orthographic errors with letters (pp.416–417)

Spelling mistakes with individual letters trace to several distinct causes. **Phoneme/letter
mismatch** (desajuste): Spanish has more letters than phonemes in several cases, so one phoneme maps
to multiple possible letters — /b/ → *b, v, w*; /θ/ → *c, z*; /g/ → *g, gu*; /x/ → *j, g*; /k/ → *c,
qu, k*; /n/ → *n, m* (in context); /r̄/ → *r, rr*; /i/ (as semiconsonant) → *i, y*. Conversely, some
letters correspond to no phoneme at all: *h* represents no sound in Spanish; the *u* in the groups
*gue, gui, qui, que* is likewise silent. The letter *x* represents two phonemes, /k/+/s/, though the
/k/ often drops in casual speech before a following consonant (*éxtasis* → [éstasis]).
**Neutralización de fonemas** (phoneme neutralization) causes confusion between *y* and *ll* among
yeísta speakers who no longer distinguish /ʝ/ and /ʎ/ (*cayó* vs. *calló*); between *s* and *c/z*
among seseo/ceceo speakers who neutralize /s/ and /θ/; between word/syllable-final *-d* and *-z*
(*adquirir, tenaz, salud*); and between word/syllable-final *-c* and *-z* (*actitud, azteca*).
Spontaneous casual speech also commonly drops the first consonant of a cluster, and this gets
reflected in spelling errors (*\*circustancia* for *circunstancia*, *\*trásfuga* for *tránsfuga*,
*\*infración* for *infracción*, *\*dición* for *dicción*). **Ultracorrección** (hypercorrection) causes
errors where speakers "correct" something that wasn't actually wrong (*\*geráneo* for *geranio*,
*\*inflacción* for *inflación*, *\*translado* for *traslado*, *\*espúreo* for *espurio*).
**Reproducción de la conversación** causes errors from writing exactly what casual pronunciation
sounds like, rather than the standard spelling (*\*Juaquín* for *Joaquín*, *\*güevo* for *huevo*,
*\*yelo* for *hielo*, *\*alante* for *adelante*).

#### The letter h: pronunciation, position, origin (pp.418–419)

*H* represents no phoneme or sound in standard Spanish, with one narrow exception: word-initial *h-*
in a handful of words borrowed from h-aspirating languages is pronounced as an aspiration (*hegeliano*
→ [h°egeljáno], *hitleriano* → [h°itleriáno]). Separately — an explicit regional/dialectal annotation
— in some dialect zones (Extremadura, Andalucía, Canarias, the Antilles), word-initial *h-* that
descends from Latin *f-* is aspirated in popular speech (*harto* → [h°árto], *hondo* → [h°óndo]); in
all other cases *h* is a fully silent/mute consonant. Positionally, *h* can appear word-initially
before any vowel (*hastío, hechizo, hilo, hola, huida*), word-internally as *h intercalada* either
after a consonant (*exhausto, inhóspito, deshidratar*) or between vowels (*vahído, vaho, desahuciar*),
or word-finally, but only in a closed set of interjections (*¡ah!, ¡oh!, ¡bah!, ¡eh!*). Etymologically,
most Spanish words with *h* inherited it from Latin words that already had an *h* (*hominem* >
*hombre*, *humerum* > *hombro*), or from Latin words with an initial *f-* (*famen* > *hambre*, *fumum*
> *humo*); a smaller residual group has an *h* that corresponds to neither source — of uncertain
origin (*hermano* < *germanum*, *huevo* < *ovum*, *vahído* < *vagum*, *tahúr*, explicitly noted as of
unclear etymology).

#### Lexical families with h, and their exceptions (p.419)

As a general rule, if one member of a lexical family has *h-*, the rest of the family does too
(*hacer→rehacer→deshacer→hecho*; *huésped→hospedaje→hospital→inhóspito*; *humus→humilde→inhumar→
exhumar*). But this general rule has multiple genuine exceptions where a derived/related word drops
the *h*: *hueco→oquedad*; *huelo/hueles/huele* (with h) vs. *oler, olor, olemos, oléis, olamos*
(without h); *huérfano→orfandad, orfanato*; *Huesca→oscense*; *hueso→óseo, osamenta, osario,
osificar*; *huevo→óvulo, ovario, ovíparo, ovalado, oval, ovoide*. A separate ATENCIÓN note warns that
the *humilde/inhumar/exhumar* family (from Latin *humus* 'earth') must not be confused with the
unrelated *humo/humareda/humear/ahumar* family (from Latin *fumus* 'smoke') — both have h, but for
different etymological reasons and are not the same lexical family.

#### Useful rules for writing h (p.419)

All forms of the verbs *haber, hacer, hallar, hablar/habitar* (and their prefixed compounds —
*deshacer, rehacer, deshabitar*) are written with h. All words beginning with *hia-* (*hiato*),
*hie-* (*hierático, hierro*), *hue-* (*hueco, huevo*), or *hui-* (*huida, huía*) are written with h.
Words built from Greek compositional elements take h: *hagio-* 'holy' (*hagiografía*), *hecto-*
'hundred' (*hectómetro*), *hemi-* 'half' (*hemisferio*), *hemo-/hemato-* 'blood' (*hematíes*),
*hetero-* 'different' (*heterosexual*), *hidr-* 'water' (*hidrosoluble*), *hiper-* 'superiority'
(*hipermercado*), *hipo-* 'horse' (*hipódromo*), *homo-* 'equal' (*homosexual*).

#### Homonymous/homophone pairs with and without h (pp.420–423)

This source works through an extensive, explicitly comparative list of Spanish word pairs that are
pronounced identically but spelled differently depending on the presence/absence of *h* — each pair
given with its distinguishing grammatical identity and a short illustrative sentence: *hecho/echo*
(hacer-participle+noun vs. echar-1sg), *deshecho/desecho* (deshacer-participle vs. desechar-1sg
+noun), *hojear/ojear* (from *hoja* vs. from *ojo*), *ha/a/ah* (haber-3sg vs. preposition vs.
interjection), *haya/aya* (haber-subjunctive/noun 'beech' vs. noun 'nanny'), *rehusar/reusar*,
*herrar/errar*, *habría/abría*, *honda/onda*, *había/avía*, *hizo/izo*, *¡hala!/ala*, *hasta/asta*,
*huso/uso*, *hato/ato*, *hora/ora*, *¡hola!/ola*. A recurring structural pattern across many pairs:
the *h*-bearing member is a form of a high-frequency irregular verb (*haber, hacer*) or a noun from
an h-initial lexical family, while the h-less member is either an unrelated homophonous root
(*echar, atar, usar, orar*) or a 1st/3rd-person present verb form that happens to coincide
phonetically.

#### Other h-initial lexical families and error-prone words (pp.424–425)

A further set of h-initial lexical families is listed, each illustrated with a short example
sentence: *hincapié/hincar*, *halago/halagar/halagador/halagüeño* (explicitly distinguished from the
unrelated, h-less verb *alagar* 'to flood'), *hastío/hastiar*, *hedor/hediondo/heder/hediondez*,
*hegemonía/hegemónico*, *hocico/hocicudo/hozar*, *hogar/hoguera/hogareño/hogaza*, *horca/horquilla*,
*hostil/hostilidad/hostilizar/hueste*, *hoyo/hoya/hoyuelo* (with an explicit ATENCIÓN distinguishing
*hoya* 'large hollow in the earth' from *olla* 'cooking pot' — unrelated, no h). A supplementary list
of frequently-misspelled h-initial words follows with no further grouping logic beyond "words that
cause trouble": *hado, halo, hamaca, hampa, hebilla, hecatombe, hez, hechura, henchir, hilaridad,
hinojo, hirsuto, hito, hollín, hortera/horterada, hosco, hostigar, hoz, hucha, huracán, huraño,
hurgar, hurtar*. A final ATENCIÓN explicitly excludes *ilación* 'coherence' and *ilativo* from the
*hilo/hilar* family (*hilar, deshilar, hilacho, hiladillo, hilandera, hilandería, hilatura,
deshilachar, hilera, sobrehilar, hilvanar, hilván*) despite the surface resemblance — *ilación/
ilativo* are unrelated and take no h.

#### Intercalated -h- (-h- intercalada) lexical families and exceptions (pp.426–427)

A set of lexical families sharing intercalated *-h-*: *adherir/adherente/adherencia/adhesivo/
adhesión/inherente/inherencia/coherente/coherencia/cohesión/cohesionar*; *exhalar/exhalación/
inhalar/inhalación*; *exhausto/exhaustivo*; *exhortar/exhortación/exhortativo*; *inhibir/inhibición/
exhibir/exhibición/exhibicionismo/exhibicionista/cohibir/prohibir/prohibición/prohibitivo*;
*vehículo/vehemente/vehemencia*. A further list of individually error-prone -h--intercalada words
follows (not organized by shared family): *ahínco, ahuyentar, alcahuete, alhaja, almohada,
anhelar/anhelante/anhelo, bohemio, cacahuete, cohete, desahuciar/desahucio, enhebrar, enhiesto,
moho/enmohecer, retahíla, trashumante/trashumancia, zaherir*. An explicit ATENCIÓN warns that despite
superficial resemblance, *exuberante* and *transeúnte* take **no** intercalated h, nor do *incoar,
coercitivo, coartar, coacción, meollo, toalla*.

#### RAE-admitted alternate spellings with/without h (p.427)

A distinct class from true homophone-pairs: words where the RAE itself sanctions *either* spelling,
with or without h, though one variant (listed first in each pair) is preferred — *acera/hacera, ¡ah!/
¡ha!, albahaca/albaca, alhelí/alelí, armonía/harmonía, arpa/harpa, arpía/harpía, arpillera/
harpillera, ¡arre!/¡harre!, arrear/harrear, arriero/harriero, ¡eh!/¡he!, ¡hala!/¡alá!, hexagonal/
exagonal, hexágono/exágono, hogaño/ogaño, reprender/reprehender, sabiondo/sabihondo, ¡uf!/¡huf!,
urraca/hurraca*. A set of further observations on individual words with conditional spelling rules:
*aprehender* is a synonym of *aprender* ('to learn') only in the sense of 'coming to know'; for
'seizing/capturing (esp. contraband)' only *aprehender* is correct, never *aprender*. *Hatajo* is a
synonym of *atajo* specifically in the senses 'small herd of livestock' and 'group of people/things'
(*atajo de vacas* or *hatajo de vacas*), but only *atajo* (no h) is correct when it means 'shortcut' or
'path that shortens a route'. *Hierba/yerba* and *hiedra/yedra* are both RAE-admitted free variants.

#### General considerations on b, v, w (p.428)

The letters *b*, *v*, and *w* all represent the same single phoneme, /b/ — *b* in *bala* and *v* in
*velo* are pronounced identically — and this phonemic merger is precisely why b/v spelling errors are
so common. *W* is used only in foreign-origin words. In words fully nativized into Spanish, *w*
represents the bilabial voiced stop [b] (*wolframio* → [bolfrámjo], *wagneriano* → [bagnerjáno]); in
other, especially English-origin, words it's pronounced as the semiconsonant [w] (*whisky* → [wíski],
*washingtoniano* → [wasintonjáno]). The RAE has also adapted *w* to *v* orthographically in some
words (*water*→*váter*, *darwiniano*→*darviniano*). In proper names, *w* is pronounced [b] in German-
origin names (*Wenceslao*→[benθesláo], *Wamba*→[bámba]) but as semiconsonant [w] in English-origin
names (*Wellington*→[wélinton], *Washington*→[wásinton]) — an explicit etymology-conditioned
pronunciation split.

#### Orthographic rules for the letter b (p.430)

Written with *b*: all verbs ending in *-bir*, in every form, except *hervir, servir, vivir* and their
compounds (which take *v*) — *escribir, percibir, concebir*. The verbs *deber, saber, caber,* and
*haber* in every form where the /b/ phoneme appears (*sabía, debió, hubo*). All verbs ending in
*-buir*, in every form (*atribuir, atribuyó, distribuyera*). All imperfect-indicative forms of
1st-conjugation (-ar) verbs, and of the irregular verb *ir* in that same tense (*cantabais, saltaban,
iba, iban*). Whenever /b/ precedes the consonants *l* or *r* (*blusa, blanco, breve, bruto*). All
words beginning with the syllables *bu-, bur-, bus-* (*butano, burdel, buscar*). Words ending in
*-bundo* and *-bilidad* (*meditabundo, posibilidad*) — with the explicit exceptions *movilidad,
civilidad* (which take v). Words beginning with the prefixes *ab-, ob-, sub-* (*absolución, objeción,
suburbano*).

#### Orthographic rules for the letter v (p.432)

Written with *v*: words beginning with the prefixes *ad-* and *sub-* when followed by the /b/ phoneme
(*advenedizo, subvalorar*). Adjectives/determiners ending in *-ava, -ave, -avo, -eva, -eve, -evo,
-iva, -ivo* (*doceava, suave, octavo*), and nouns ending in *-ivo*, with exceptions like *estribo*
(*motivo, objetivo, cautivo*). All preterite-indefinido forms ending in *-uve*, in every form, except
*haber* (*tuve/tuviste/tuvo, anduve/anduviste/anduvo* — but *hube/hubiste/hubo* with b); the same v
extends into the corresponding imperfect/future subjunctive (*tuviera/tuviere,
anduviera/anduviere* — but *hubiera/hubiere* with b). All forms of the verb *ir* in which the /b/
phoneme appears, except the imperfect indicative (*voy, vas, vaya* — but *iba, ibas, iba* with b).
Words with the prefix *vice-* (*vicerrector, vicealmirante, vicesecretario*). Words ending in *-voro*
and *-vora* (*omnívoro, carnívora, herbívoro*).

#### Homonymous/homophone pairs with b and v (pp.434–435)

A further set of explicitly worked b/v minimal pairs, each with its full derivational family: *grabar*
('to record/engrave', entirely b-spelled family: *grabado, grabación, grabador*) vs. *gravar* ('to tax
burden with a levy', entirely v-spelled family: *gravamen, grave, gravitar, gravoso, gravedad,
gravidez, ingravidez, desgravar*); *rebelarse* ('to rebel', from Latin *bellum* 'war', b-spelled
family: *rebelde, rebeldía, rebelión, belicoso, beligerante, beligerancia*) vs. *revelar* ('to reveal;
to develop film', from Latin *velum* 'veil/curtain', v-spelled family: *revelación, revelador, velar,
velo, veleta, velero*) — with a further ATENCIÓN noting a *third*, unrelated *desvelar/velar* family
(from Latin *vigiliam* 'vigil', meaning 'to keep someone awake' / 'to stay awake', also v-spelled:
*velada, velador*) that is a homonym, not just homophone, of the *revelar*-family *velar* ('to veil').

#### Haber vs. a ver (p.435)

Distinguished not as two homonymous *words* but as a verb (*haber*, infinitive) homophonous with a
preposition+infinitive construction (*a ver*, 'to see'). *Haber* functions as the main verb of a
periphrasis (*puede haber, tiene que haber, ha de haber*), as the auxiliary of a compound infinitive
or of the *haber que + infinitive* periphrasis (*Me gustaría haber ido contigo*; *Va a haber que
expulsarlo*), or as a full/plain verb (*Parece haber poca gente*). *A ver* is literally preposition *a*
+ infinitive *ver*, which can retain its literal 'sight' meaning (*Voy a ver a mi hermana*) or — more
commonly — appear fully grammaticalized (its original literal meaning bleached out) with an appellative
or phatic/attention-getting discourse value (*A ver si os calláis*; *Vamos a ver, ¿cómo te llamas?*).
An ATENCIÓN box further notes that in the chained periphrasis *va a haber que ir a su casa*, the first
*haber* is the main verb of the *ir a + infinitivo* periphrasis while simultaneously functioning as the
auxiliary of the embedded *haber que + infinitivo* periphrasis — and that the preposition *a* in *va a
haber que...* must never be dropped in writing (*\*va haber que*), even though in pronunciation it
merges into a single long [a]: [baβérke].

---


---


## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
