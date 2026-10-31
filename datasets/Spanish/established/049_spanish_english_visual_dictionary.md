# Spanish — Established Vocabulary/Register: Spanish-English Visual Dictionary (substantial sample)

**Source:** *Spanish-English Visual Dictionary* (DK-style bilingual picture dictionary format), DjVu
file, 142 scanned page-images, 19.5 MB. No text layer at all (`djvutxt` returns zero bytes output —
confirmed empty) — every page is a photographed/scanned spread with text baked into the image, so this
file was extracted entirely by **vision reading**, not OCR/`pdftotext`. Pages were converted from DjVu
to JPEG via `ddjvu -format=ppm` piped through Python/Pillow (no `ddjvu` PNG option exists; `pnmtopng`/
`imagemagick` were not installed on this system, so Pillow was used instead). Each of the 142 DjVu
"pages" is actually a **two-page printed spread** (confirmed by the printed page numbers visible in
each image, e.g. DjVu page 1 shows printed pp. 12-13, DjVu page 142 shows printed pp. 322-323) — so the
physical book runs to roughly 320+ pages, organized into topic chapters: **La Gente/People** (body,
face, family, relationships, life events), **La Apariencia/Appearance** (clothing, accessories, hair,
beauty), **La Salud/Health**, **La Casa/Home** (rooms, furniture, garden, cleaning), **Los Servicios/
Services** (bank, shopping), **Las Compras/Shopping**, **Los Alimentos/Food** (extensive — meat,
vegetables, grains, dairy, delicatessen), **Comer Fuera/Eating Out**, **El Trabajo/Work** (construction,
media), **El Transporte/Transportation** (cars, roads), **Los Deportes/Sports** (soccer, horseback
riding, skiing), **El Ocio/Leisure** (beach, home entertainment, arts and crafts, music), **El Medio
Ambiente/Environment** (weather, animals, town), and **Los Datos/Reference** (numbers, maps, useful
phrases, antonyms).

**Methodology — substantial (not literally exhaustive) sampling.** Per the task's own framing, a
visual dictionary is much smaller in scope than the two full prose dictionaries sampled alongside it
(047, 048), so this extraction goes considerably further toward full coverage: **45 of the 142 page-
spreads were read in full (≈32%)**, deliberately chosen to touch every one of the book's 13 topic
chapters rather than clustering in one area, with the heaviest sampling in the chapters that turned
out (on first inspection) to carry the densest register/dialect content — clothing, food, and
transportation. The remaining ~97 page-spreads were not read; most are additional sub-topics within
the same chapters already sampled (more animal types, more sports, more clothing categories, more
foods) and would likely yield more instances of the same structural pattern described below rather
than a qualitatively new finding. All labels transcribed were read directly off clear, high-resolution
printed captions — no handwriting, no degraded scan quality — so **Vision Reading Confidence is
`verified` throughout**, with `Transcription Confidence: n/a` (this file used no OCR/text-layer
extraction at any point, per the project's convention for vision-only sources).

## Flagship structural finding: the book's built-in Mexico/Spain register-and-dialect marking system

**This is by far the most important finding from this source, and the reason this book earns fuller
coverage than its page count alone would justify.** Throughout the entire dictionary, a large fraction
of entries are printed as a **primary term plus a parenthetical alternate marked with a small superscript
"C"** — e.g. *el carro (**C**el coche)* "car," *la papa (**C**la patata)* "potato," *estacionar
(**C**aparcar)* "to park," *los pants (**C**el chándal)* "warm-up suit," *la chamarra (**C**la
cazadora)* "windbreaker." The pattern is completely consistent: **the primary (unmarked) term is the
Mexican-Spanish usage this edition is written in, and the "C"-marked term is the Peninsular/Castilian
Spanish equivalent.** This was not stated in any legend this extraction could locate (the book's own
front-matter/key page, if it exists, falls on a printed page earlier than page 12, which is not
present in this particular DjVu scan — scanning starts directly at p.12) — the "C = Castilian Spain"
reading is the extractor's own inference from the pattern itself, which is unambiguous once ~20+ pairs
are compared (*estacionar/aparcar*, *manejar/conducir*, *tránsito/tráfico*, *reservación/reserva* [see
048's front matter too], *el coche* always being the Spain alternate, never the Mexican primary, etc.)
and matches well-known, independently-attested Mexico/Spain lexical splits.

This makes the book functionally **a large, systematically-structured bidialectal glossary disguised
as a picture dictionary** — far higher register/dialect-mapping value per page than either prose
dictionary sampled in this wave, which is why the extraction below leans so heavily on capturing these
pairs. Density varies sharply by semantic domain: **clothing (pp. 30-41) and food (pp. 118-157) are
saturated** — the large majority of items on those pages carry a "C" alternate — while **anatomy/
biology, numbers, and world-map reference pages carry almost none** (lexical variation is lowest where
the vocabulary is most technical/Latinate and highest where it's everyday material culture:
clothes, food, cars, housing).

**Non-redundancy check:** Spanish's established/ corpus already documents vosotros/ustedes and a
handful of Spain-vs-LatAm swaps (001 Colloquial Spanish Latin America). Nothing existing comes close
to the systematic, large-scale Mexico/Spain doublet list below — this is new, high-density regional
lexical-variation content for the project.

## Extraction table

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| el carro / el coche | car | noun (m) | core, regional doublet | high | contemporary | México (primary term) / Spain (alt) | transnational | grammar_reference | n/a | verified | Flagship doublet; book's own section title "el carro (C el coche) 2," p.200. |
| la papa / la patata | potato | noun (f) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.124; also "las papas/patatas fritas" (potato chips) p.151. |
| el jitomate / el tomate | tomato | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | Recurs at least 3x in the book (pp.124,142,156) always with the same pairing. |
| estacionar / aparcar | to park | verb | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.195, 200; repeated across car/road pages. |
| manejar / conducir | to drive | verb | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.195. |
| el tránsito / el tráfico | traffic | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.194; note "el tráfico" is itself reused as primary for "traffic jam" alt "el atasco de tráfico" p.195 — same root word shifts role. |
| los pants / el chándal | warm-up/track suit | noun | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.31,33. |
| la chamarra / la cazadora / el chaquetón | windbreaker / parka | noun (f) | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | Same primary Mexican word "chamarra" maps to two different Spain alternates depending on garment style (pp.31,33). |
| el saco / la chaqueta | jacket/blazer | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | pp.32,34; "saco" also used generically for "pants" pairing confusion in source layout on p.32 — flagged as a possible scan-layout ambiguity. |
| los tenis / las zapatillas deportivas | sneakers | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.31,37. |
| el suéter / el jersey | sweater | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.33. |
| la piyama / el pijama | pajamas | noun (f) | core, regional doublet (spelling variant too) | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.33; note the spelling itself shifts (piyama vs pijama), not just word choice. |
| el brassiere / el sujetador | bra | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.35. |
| las pantaletas / las bragas | underpants (women's) | noun | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.35. |
| los boxers / los calzoncillos de pata | boxer shorts | noun | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.33. |
| la bolsa / el bolso | bag / handbag | noun (f) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | pp.36-37; recurs for both "shoulder bag" and "handbag" senses. |
| el arete / el pendiente | earring | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.36. |
| las mancuernillas / el gemelo | cufflink | noun | regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.36. |
| la estilista / la peluquera | hairdresser | noun (f) | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.38. |
| el peluquero / el barbero | barber | noun (m) | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.39. |
| güero / rubio | blonde | adj. | colloquial, regional doublet | moderate | contemporary | México (colloquial) / Spain (neutral) | transnational | grammar_reference | n/a | verified | p.39; "güero" is specifically a Mexican colloquialism for light-haired/light-skinned, not just a dialectal synonym — one of the few pairs where the Mexican term is the more informal-register one. |
| alaciar / alisar | to straighten (hair) | verb | regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.39. |
| el delineador / el lápiz de ojos | eyeliner | noun (m) | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.40. |
| el rubor / el colorete | blusher | noun (m) | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.40. |
| el ataque cardíaco / el infarto de miocardio | heart attack | noun (m) | core/medical, regional doublet | high | contemporary | México (everyday) / Spain (also more clinical-sounding) | transnational | grammar_reference | n/a | verified | p.44. |
| la migraña / la jaqueca | migraine | noun (f) | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.44; "jaqueca" also carries a mildly old-fashioned flavor independent of region. |
| el doctor / el médico | doctor | noun (m) | core, register-leaning doublet | high | contemporary | México (everyday) / Spain | transnational | grammar_reference | n/a | verified | p.45; "médico" is the more formal/clinical register term across all Spanish, not purely regional — a case where the book's binary Mexico/Spain framing may be oversimplifying what's really a register distinction. |
| los lentes obscuros / las gafas de sol | sunglasses | noun | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.51,264; "lentes" vs. "gafas" is one of the most productive doublet roots in the book, recurring for "glasses," "sunglasses," "goggles," etc. |
| los pupilentes / las lentillas | contact lenses | noun | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.51. |
| el departamento / el piso | apartment | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.58; same root pair recurs at p.298 for "apartment block." |
| la cochera / el garaje | garage | noun (f) | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.58. |
| el elevador / el ascensor | elevator | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.59,104; recurs identically in both the home and shopping-mall chapters. |
| el tapete / el felpudo / la moqueta | doormat / carpet | noun (m) | regional doublet, polysemous | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | "el tapete" maps to two different Spain words depending on sense (doormat p.59 vs. wall-to-wall carpet p.71) — same Mexican word, Spain disambiguates with two different words. |
| la cobija / la manta | blanket | noun (f) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.70-71. |
| la lavandería / el lavadero | utility/laundry room | noun (f) | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.76. |
| el trapeador / la fregona | mop | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.77. |
| fregar / pasar la bayeta | to wipe | verb | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.77; note "fregar" itself is a classic Mexican "to annoy/bother" slang verb in other contexts, not surfaced by this source. |
| tapizar / empapelar | to wallpaper | verb | regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.82. |
| el overol / el mono | coveralls | noun (m) | regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.83. |
| el azadón / la azada | hoe | noun (m) | regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.88. |
| la podadora / el cortacésped | lawnmower | noun (f) | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.88. |
| el sobregiro / el descubierto | line of credit (bank) | noun (m) | formal/technical, regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.96. |
| el contador / el contable | accountant | noun (m) | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.97. |
| el vendedor / el dependiente | sales clerk | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.104. |
| los baños / los aseos | restroom | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.104. |
| el primer piso / la primera planta | second floor | noun phrase | technical/false-friend doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.104; genuine false-friend trap — "primer piso" literally means "first floor" but in context of a multi-story mall layout the book glosses it as "second floor" (ground-floor-numbering convention mismatch), worth flagging for learners separately from pure vocabulary swaps. |
| los abarrotes / el supermercado | groceries/grocery store | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.105. |
| la florería / la floristería | florist | noun (f) | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.110. |
| el tocino / el bacon | bacon | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.118; Spain's "bacon" is itself an English loanword, unlike most of this list's native-vocabulary pairs. |
| la carne molida / la carne picada | ground beef | noun (f) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.119. |
| el ganso / la oca | goose | noun (m) | regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.119; same "oca" root resurfaces at p.137 for "goose egg" (de oca). |
| el camote / el boniato | sweet potato | noun (m) | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.125. |
| la calabacita / el calabacín | zucchini | noun (f) | regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.125. |
| los frijoles y los chícharos / las alubias y los guisantes | beans and peas | noun phrase | core, regional doublet (section title) | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.130; whole section header is doubled, not just individual items — shows how systematic the split is for legumes specifically. |
| la leche descremada / la leche desnatada | fat-free milk | noun phrase | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.136. |
| la crema / la nata | cream | noun (f) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.136; root of several further doublets (crema batida/nata montada "whipped cream," crema ácida/nata agria "sour cream"). |
| la malteada / el batido | milkshake | noun (f) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.137. |
| el jugo / el zumo | juice | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.156; among the best-known Mexico/Spain food-word splits. |
| el chocolate caliente / el cacao | hot chocolate | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.156. |
| los waffles / los gofres | waffles | noun | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.157. |
| la avena / las gachas de avena | oatmeal | noun (f) | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.157. |
| el huevo estrellado / el huevo frito | fried egg | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.157. |
| la llave de cerveza / el grifo de cerveza | beer tap | noun (f) | regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.150. |
| la cuba libre / el ron con cola | rum and coke | noun (f) | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.150; "cuba libre" is itself a widely pan-Hispanic cocktail name — book presents it as the Mexican-primary term regardless. |
| la silla / el taburete | bar stool | noun (f) | regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.150. |
| el destapador / el abrebotellas | bottle opener | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.150. |
| la botana / los aperitivos | bar snacks | noun (f) | core, regional doublet (section title) | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.151; "botana" is a very characteristically Mexican word for snacks/appetizers. |
| las nueces de la India / los anacardos | cashews | noun | regional doublet | low | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.151. |
| el reflector / el foco | (studio) light / spotlight | noun (m) | core, regional doublet, recurs across domains | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | Recurs at p.45 (dentist's reflector lamp), p.178 (TV studio light), p.259 (concert spotlight) — same Mexico/Spain pair reused across three unrelated chapters, showing "foco" is a systematic Spain equivalent across all "light fixture" senses of "reflector." |
| el teleprompter / el autocue | teleprompter | noun (m) | technical, regional doublet | low | contemporary | México (English loanword) / Spain (English loanword, different one) | transnational | grammar_reference | n/a | verified | p.178; notable because BOTH variants are English loanwords, just different English words borrowed in each region. |
| el DJ / el pinchadiscos | DJ | noun (m) | colloquial, regional doublet | moderate | contemporary | México (English loanword) / Spain (native coinage) | transnational | grammar_reference | n/a | verified | p.179; Spain's "pinchadiscos" (lit. "record-pricker/spinner") is a native-Spanish coinage competing with the English loanword used in Mexico. |
| las caricaturas / los dibujos animados | cartoon | noun (f) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.178; "caricaturas" could cause confusion since in most Spanish it means "caricature/political cartoon," not animated cartoons — a false-friend-adjacent regionalism. |
| el claxon / la bocina | car horn | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.200; note "bocina" elsewhere in the same book (p.258,268) means "speaker" not "horn" — same word, different device, depending on context/region, a genuine ambiguity risk. |
| el tablero / el salpicadero | dashboard | noun (m) | core, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.200. |
| la bolsa de aire / el airbag | airbag | noun (f) | core, regional doublet (one native, one loanword) | high | contemporary | México (native coinage) / Spain (English loanword) | transnational | grammar_reference | n/a | verified | p.201; unusual direction — here the Mexican term is the native coinage and the Spain term is the English borrowing, reversed from the teleprompter/DJ pattern above. |
| patear / chutar | to kick (soccer) | verb | colloquial/sports, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.222; "chutar" is itself from English "to shoot." |
| el tiro de esquina / el córner | corner kick | noun (m) | sports, regional doublet | high | contemporary | México (native) / Spain (English loanword) | transnational | grammar_reference | n/a | verified | p.223. |
| el tiempo extra / la prórroga | extra time (sports) | noun (m) | sports, regional doublet | moderate | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.223. |
| el salvavidas / el socorrista | lifeguard | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.264. |
| el traje de baño / el bañador | swimsuit | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.265. |
| asolear(se) / tomar el sol | to sunbathe | verb | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.264; "asolearse" is a single-verb Mexican coinage vs. Spain's multi-word fixed phrase. |
| el control remoto / el mando a distancia | remote control | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.269. |
| los audífonos / los auriculares | headphones | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.269. |
| el pegamento / la cola | glue | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.275. |
| el guajolote / el pavo | turkey | noun (m) | core, regional doublet (inconsistently applied) | high | contemporary | México (náhuatl-derived) / Spain | transnational | grammar_reference | n/a | verified | p.293; flagged inconsistency — the book uses unmarked "el pavo" with no alternate at p.119 (meat section) but doubles it as "guajolote (C pavo)" at p.293 (live-animal section), suggesting the editorial doubling wasn't applied with full consistency throughout. |
| la banqueta / la acera | sidewalk | noun (f) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.298. |
| el estacionamiento / el aparcamiento | parking lot | noun (m) | core, regional doublet | high | contemporary | México / Spain | transnational | grammar_reference | n/a | verified | p.298; same "aparcar" root as the verb doublet above. |
| el pavo real (standalone, no C-alt given) | peacock | noun (m) | core, non-doublet (comparison case) | high | contemporary | — | Pan-Hispanic | grammar_reference | n/a | verified | p.293; included as a deliberate contrast — animal names in the "reptiles/birds 2" chapter carry almost no regional doubling, unlike clothing/food, supporting the domain-density observation in the Flagship Finding above. |
| el cerebro, el hígado, el riñón, el corazón (standalone set) | brain, liver, kidney, heart | noun (m) | technical/anatomical, non-doublet | high | contemporary | — | Pan-Hispanic | grammar_reference | n/a | verified | p.18-19; representative sample confirming anatomy vocabulary is essentially un-doubled throughout — technical/Latinate register resists the Mexico/Spain split seen in everyday material-culture vocabulary. |
