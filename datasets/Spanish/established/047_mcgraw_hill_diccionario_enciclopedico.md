# Spanish — Established Vocabulary/Register: Diccionario Enciclopédico McGraw-Hill Ilustrado (representative sample)

**Source:** *Diccionario Enciclopédico McGraw-Hill Ilustrado* (McGraw-Hill, PDF-XChange Viewer
metadata dated 2010), 1,831 pages, 144 MB. A general-purpose Spanish encyclopedic dictionary
combining normal lexical entries with geographic/biographical encyclopedia entries (countries get
flag/data boxes, famous people get birth-death capsule biographies). File has a genuine, clean text
layer (Acrobat 4.0 Import Plug-in; `pdftotext` reads it directly, no OCR/vision needed) — but the
source PDF is laid out in two columns with inline photo captions and sidebar infoboxes, which makes
`pdftotext`'s linear text stream interleave column A/column B and caption text mid-entry. This is
cosmetic noise in the raw extraction, not a transcription-confidence problem for the entries actually
selected below — every entry transcribed here was cross-checked against its surrounding context to
confirm the headword-definition pairing is correct despite the interleaving.

**Methodology — representative sampling, not exhaustive transcription.** Per this project's standing
convention for very large reference dictionaries (same approach used for Korean's 962pp dictionary
and the Hawaiian dictionary's 3,695pp), this ~1,831-page encyclopedic dictionary was **not**
transcribed exhaustively. Instead:

1. First read the dictionary's own abbreviation key (**ABREVIATURAS**, pp. v–vi+) to identify its
   register/dialect-tagging system (see below).
2. Pulled `pdftotext` samples from 16 page-pairs spread across the page range, landing in 11 different
   alphabetic sections: **pp. 60-61, 110-111 (A)**; **200-201 (A/AT-)**; **340-341, 480-481 (C)**;
   **620-621 (D)**; **760-761 (E)**; **900-901 (G)**; **1040-1041 (K)**; **1180-1181 (M)**;
   **1320-1321 (O)**; **1390-1391 (P)**; **1460-1461 (G, second pass)**; **1600-1601 (S)**;
   **1740-1741 (T)**; **1800-1801 (V)**. That is 32 of 1,831 pages (~1.7%), deliberately spread
   end-to-end across the alphabet rather than clustered at the front.
3. Within each sample, prioritized entries carrying the dictionary's own register/dialect abbreviation
   tags (`fam.`, `fig.`, `fig. y fam.`, `desp.`, `p. us.`, `desus.`, country/region codes), entries
   explicitly flagged **"Barbarismo"** (non-standard), fixed idiomatic sub-entries (the `–` dash
   convention for phrasal sub-senses), and entries showing distinctive morphology (loanwords from
   Nahuatl/Quechua/Aimara/Arabic/Greek, derivational suffix chains, polysemous regional splits).
   Plain unmarked encyclopedic/scientific/geographic entries (the bulk of the page count — country
   data-boxes, biographies, taxonomic/chemistry definitions) were skipped as out of scope for this
   project's register-mapping goal.
4. Result: **~90 hand-selected representative entries** out of an estimated 40,000+ headwords in the
   full work. This is intentionally a *qualitative* sample of the dictionary's register/dialect
   annotation system, not a frequency-weighted or statistically representative one.

**The dictionary's own abbreviation key (p. vi, "ABREVIATURAS"):** confirms this is a Pan-Hispanic
dictionary with explicit register and dialect tagging — `fam.` = familiar (colloquial), `fig.` =
figurado, `desp.` = despectivo (derogatory), `p. us.` = poco usado (rare/dated), `desus.` = desusado
(obsolete), `vulg.` = vulgar, `coloq.` = coloquial, plus a long list of country/region abbreviations
(`Amér.` = América generically, `Amér. Merid.` = South America, `Amér. Central`, `Méx.`, `Arg.`,
`Chile`, `Perú`, `Col.`, `Venez.`, `Cuba`, `Bol.`, `Ecuad.`, `Guat.`, `P. Rico`, `Dom.`, `Ant.`
[Antilles], `El Sal.`, `C. Rica`, etc.). The dictionary also uses a `–` (dash) convention under a
headword to introduce fixed phrasal/compound sub-senses (e.g. `CABEZA — de puente`, `CLORURO — sódico`).

**Non-redundancy check:** This language's established/ corpus already has extensive general grammar
and vocabulary coverage (Practice Makes Perfect series, Learning Spanish Like Crazy, Easy Spanish
Step-by-Step, etc.) and register-focused coverage of idioms/blunders (033, 034 business). Nothing
below duplicates that — every entry here is either a regionally-marked colloquialism/dialectalism, an
explicit register-tagged (fam./fig./desp.) sense, or a distinctive-morphology item (loanword,
derivational chain, "barbarismo" non-standard form) not previously captured for Spanish.

## Flagship findings

- **GUATA — five unrelated regional meanings for one word.** Standard sense "thick sheet of cotton
  wadding/batting" (used as stuffing), but: fam. **Chile** "barriga, panza" (belly — a very common
  colloquial body-part term); **Venez.** "serpiente" (snake); **Bol.** "cordel" (cord/string);
  **Cuba** "engaño" (a trick/con). A single headword with five mutually unintelligible regional senses
  is about as extreme a case of dialectal semantic divergence as this project has found in any
  language's dictionaries so far.
- **DESTUSAR — regional semantic drift from a literal agricultural action to slang "steal/gossip."**
  Amér. Central y Col. "quitar la tusa (husk) al maíz" (to husk corn, literal) → Cuba "recortar las
  crines de un caballo" (to trim a horse's mane, extended literal) → **Guat. "robar" / "murmurar"**
  (to steal / to gossip, fully figurative slang). A clean three-step metaphorical chain from a single
  rural-agricultural root verb.
- **MESTRO — explicitly labeled "Barbarismo por maestro"** (Chile, Col., Méx.): the dictionary flags
  this directly as a stigmatized non-standard variant of *maestro*, not a neutral regionalism — useful
  as a rare example of a prescriptive dictionary explicitly marking a form as "wrong" rather than
  dialectal.
- **ATARANTAR — same verb, opposite-feeling regional meanings.** Col. y Chile "atropellarse,
  precipitarse" (to rush/hurry) vs. Guat. y Méx. "saciarse de comer... apresuradamente" (to stuff
  oneself hastily) — same root sense of hasty/frenzied action, diverging by region into "haste" vs.
  "overeating."
- **PERDONAVIDAS** (fig. y fam., "fanfarrón" = braggart/bully) — a vivid compound idiom literally
  "forgiver of lives," i.e. someone who swaggers around as if they hold power of life and death over
  others.

## Extraction table

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ahorita | right now, this very moment | adv. | colloquial | high (everyday) | contemporary (source 2010) | Latin America | transnational | grammar_reference | verified | n/a | Marked `fam.`; diminutive of *ahora*; classic LatAm colloquialism, much rarer in Spain. |
| ahogo (regional sense) | asthma | noun (m) | colloquial | moderate | contemporary | Amér. (generic) | transnational | grammar_reference | verified | n/a | Standard senses are "suffocation; anguish, distress"; `Amér.` tags the extended "asma" sense. |
| ahijar (fig. sense) | to falsely attribute (a work) to someone | verb | figurative | — | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Literal sense "to adopt (someone's child)"; `fig.` extension to false authorship-claims. |
| aikido | aikido (martial art) | noun (m) | neutral/loanword | — | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Unassimilated Japanese loanword, spelled as in Spanish phonology. |
| airbag | airbag | noun (m) | neutral/loanword | — | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | English loanword, written identically; entry notes it's "voz ing." |
| aine | loan (of money/goods repaid double) among Quechua/Aimara communities | noun (m) | regional/cultural | low (specialized) | contemporary | Bolivia | national | grammar_reference | verified | n/a | From Aimara *ayne*; a named reciprocal-credit custom, not just a generic word for "loan." |
| amiguero | sociable, makes friends easily | adj. | colloquial | moderate | contemporary | Arg., Bol., Ecuad., Méx., Perú | multi-national | grammar_reference | verified | n/a | Derivational: *amigo* + *-ero*; widespread LatAm regionalism, absent from this sense in Spain. |
| ameritar | to merit, deserve; to incur | verb | colloquial/regional | high | contemporary | Amér. (generic) | transnational | grammar_reference | verified | n/a | Classic Latin-Americanism vs. Peninsular preference for *merecer*. |
| ameyal | spring, well (next to a pond) | noun (m) | regional | low | contemporary | México | national | grammar_reference | verified | n/a | Nahuatl-derived term. |
| amilanar | to frighten badly, intimidate | verb | figurative | — | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fig.`: "aturdir a uno a base de miedo." |
| perdonavidas | braggart, bully | noun (com.) | colloquial/figurative | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fig. y fam.`; compound "life-forgiver" idiom for a swaggering bully. |
| ponerse perdido | to get filthy, covered in dirt | phrase | colloquial/figurative | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Explicitly tagged `frs.` (frase) `fig. y fam.` in the dictionary's own system. |
| perecear | to put something off out of laziness | verb | colloquial | low | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fam.`; derivational from *pereza* ("laziness") + verbal suffix. |
| cabeza de turco | scapegoat | idiom (noun phrase) | idiom | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Dash sub-entry under CABO/CABEZA; literally "Turk's head." |
| cabeza de puente | bridgehead (also figurative: foothold/entry point) | idiom (noun phrase) | idiom/technical | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Military term with figurative extension to any "base of penetration" into new territory. |
| cabildear | to lobby, politick | verb | neutral | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | "Gestionar con actividad y maña para influir en las decisiones de un órgano de gobierno." |
| cabildante | city councilman | noun (m) | regional | moderate | contemporary | Amér. Merid. | regional | grammar_reference | verified | n/a | Regional synonym for standard *concejal*. |
| cabinera | flight attendant | noun (f) | regional | moderate | contemporary | Colombia | national | grammar_reference | verified | n/a | Regional synonym for *azafata/aeromoza*. |
| closet | built-in closet; also euphemism for bathroom | noun (m) | colloquial/regional | high | contemporary | Amér. (generic) | transnational | grammar_reference | verified | n/a | English loanword; second sense "cuarto de baño, servicio" is a notable bathroom euphemism. |
| cloche | clutch (of a vehicle) | noun (m) | regional/loanword | moderate | contemporary | Col., El Sal., P. Rico, Dom. | multi-national | grammar_reference | verified | n/a | Regionalized form of English "clutch"; standard term is *embrague*. |
| clerico | sangria-like wine-and-fruit drink | noun (m) | regional | moderate | contemporary | Argentina | national | grammar_reference | verified | n/a | From English "claret cup" per the entry's own etymology. |
| cabra (regional sense) | loaded/rigged die | noun (f) | slang | low | contemporary | Col., Cuba | multi-national | grammar_reference | verified | n/a | Standard sense is "goat"; gambling slang sense is region-specific. |
| cabezota / cabezudo | stubborn, obstinate person; big-headed | adj./noun | colloquial | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fam.`/`fig. y fam.`; *cabezudo* also names the giant-head carnival/parade figure in Spain and parts of LatAm. |
| cabizbajo | crestfallen, downcast (lit. "head-low") | adj. | neutral | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Compound: *cabeza* + *bajo*. |
| desuellacaras | incompetent barber; shameless person | noun (m/com.) | colloquial/figurative | low | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fig. y fam.`; vivid compound literally "face-flayer." |
| destusar | to husk corn / to trim a horse's mane / to steal, to gossip | verb | regional, divergent | moderate | contemporary | Amér. Central, Col. (husk); Cuba (trim mane); Guat. (steal/gossip) | multi-national | grammar_reference | verified | n/a | Flagship find: single verb, three-step metaphorical drift from literal agriculture to slang. |
| destutanar | to remove bone marrow; to exhaust oneself | verb | regional/figurative | low | contemporary | Col., Chile | multi-national | grammar_reference | verified | n/a | `fig.`: "desvivirse, consumirse." |
| desuñar (prnl.) | to work very hard at something difficult (lit. "to tear one's nails off") | verb (reflexive) | colloquial/figurative | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fig. y fam.`; vivid body-idiom for strenuous manual effort. |
| ate | sweet fruit paste (candy) | noun (m) | regional | moderate | contemporary | México | national | grammar_reference | verified | n/a | Culturally specific foodstuff term. |
| atecomate | water-drinking vessel | noun (m) | regional | low | contemporary | México | national | grammar_reference | verified | n/a | Nahuatl-derived. |
| atejo | bundle; mess, jam (predicament) | noun (m) | regional | low | contemporary | Colombia | national | grammar_reference | verified | n/a | "Lío" carries both the literal "bundle" and figurative "trouble" senses. |
| atembar | to stun, daze | verb | regional | low | contemporary | Colombia | national | grammar_reference | verified | n/a | |
| atendido (regional sense) | attentive, considerate | adj. | regional | moderate | contemporary | Col., Méx., Venez. | multi-national | grammar_reference | verified | n/a | Standard Spanish *atendido* is just the past participle "attended to"; regional sense shifts to an active personality trait. |
| atarantar | to rush/hurry; to stuff oneself hastily | verb (reflexive) | regional, divergent | moderate | contemporary | Col., Chile (hurry); Guat., Méx. (overeat) | multi-national | grammar_reference | verified | n/a | Flagship find: same root sense ("frenzied action"), opposite regional specializations. |
| atarragar | to stuff oneself with food | verb (reflexive) | colloquial/regional | low | contemporary | Méx., Col., Venez. | multi-national | grammar_reference | verified | n/a | |
| atascadero | a stuck/stalled process, obstacle to progress | noun (m) | figurative | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fig.` extension of literal "mudhole where carts get stuck." |
| atalaya (fig. sense) | vantage point from which to judge the truth | noun (f) | figurative | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Literal "watchtower"; figurative sense is a common rhetorical usage. |
| ataraxia | ataraxia (philosophical tranquility) | noun (f) | formal/loanword | low | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Greek-derived philosophical term, tagged `Fil.` |
| atarjea | small masonry water channel | noun (f) | regional/technical | low | contemporary | México | national | grammar_reference | verified | n/a | |
| ataque masivo | (computing) denial-of-service style mass attack on a server | noun phrase | technical neologism | — | contemporary (2010 or later) | — | Pan-Hispanic | grammar_reference | verified | n/a | Tagged `Inf.`; shows the dictionary tracking a 21st-c. computing-slang coinage. |
| atavismo | atavism (reversion to ancestral traits/habits) | noun (m) | formal | — | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Both `fig.` (cultural) and `Biol.` (genetic) senses given. |
| desurtido | out of stock, unstocked | adj. | regional | low | contemporary | Arg., Perú, Venez. | multi-national | grammar_reference | verified | n/a | |
| desuso (legal sense) | desuetude (tacit repeal of a law through non-observance) | noun (m) | formal/technical | — | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Tagged `Der.` (law). |
| guata | cotton wadding; belly (Chile, fam.); snake (Venez.); cord (Bol.); a trick/con (Cuba) | noun (f) | regional, highly divergent | moderate | contemporary | Chile; Venezuela; Bolivia; Cuba | multi-national | grammar_reference | verified | n/a | Flagship find: five mutually unrelated regional senses for one headword. |
| guasa | mockery, joking around; (fam.) insipidness/lack of charm | noun (f) | colloquial | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | From Greek *gausse* ("burla") per the entry; two senses split by register tag. |
| guasearse | to joke around, mock | verb (reflexive) | colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Derived from *guasa*. |
| guasón, -ona | joker, prankster | noun/adj. | colloquial | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fam.`; derivational *guasa* + *-ón*. |
| guasada | rude act, vulgarity | noun (f) | colloquial/regional | moderate | contemporary | Argentina | national | grammar_reference | verified | n/a | |
| guasería | rude/boorish act | noun (f) | colloquial/regional | moderate | contemporary | Arg., Chile | multi-national | grammar_reference | verified | n/a | Related to *guaso* (rustic/country person). |
| guasamaco | uncouth, rustic | adj. | colloquial/regional | low | contemporary | Chile | national | grammar_reference | verified | n/a | |
| guaso, -sa | rural/country person (Chile); crude, uncouth | noun/adj. | regional, pejorative-leaning | moderate | contemporary | Chile (person); Amér. (fig. pejorative) | multi-national | grammar_reference | verified | n/a | Quechua-derived per the entry's own etymology (*Voz quechua*); figurative extension is mildly derogatory. |
| guasca | leather/cord strap used as whip or rein | noun (f) | regional | moderate | contemporary | Amér. Merid., Antilles | multi-national | grammar_reference | verified | n/a | Quechua loanword. |
| guasasa | small gnat/midge | noun (f) | regional | low | contemporary | Cuba | national | grammar_reference | verified | n/a | |
| guasima | tree with light but resistant wood | noun (f) | regional | low | contemporary | Cuba, P. Rico | multi-national | grammar_reference | verified | n/a | |
| guaren | large rat | noun (m) | regional | low | contemporary | Chile | national | grammar_reference | verified | n/a | |
| guariba | howler monkey | noun (m) | regional | moderate | contemporary | Amér. Merid. | regional | grammar_reference | verified | n/a | |
| guarisapo | tadpole | noun (m) | regional | moderate | contemporary | Chile | national | grammar_reference | verified | n/a | Regional synonym for standard *renacuajo*. |
| guaro (regional sense) | parrot | noun (m) | regional | moderate | contemporary | Venez., Amér. Central | multi-national | grammar_reference | verified | n/a | Note: this entry gives "parrot"; *guaro* is independently well-known elsewhere as a term for cheap cane liquor — a notable case where this dictionary's sense diverges from the common slang meaning known from other sources. |
| guataca | short hoe (farm tool) | noun (f) | regional | moderate | contemporary | Cuba | national | grammar_reference | verified | n/a | |
| guardavalla | goalkeeper (soccer) | noun (m) | regional/sports | moderate | contemporary | — | Pan-Hispanic (LatAm-leaning) | grammar_reference | verified | n/a | Regional alternative to *portero/arquero*. |
| guardarropía | wardrobe/costume department (theater) | noun (f) | neutral/technical | low | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | |
| kimona | kimono | noun (f) | regional/loanword | low | contemporary | Cuba | national | grammar_reference | verified | n/a | Hispanicized phonetic spelling of "quimono/kimono." |
| kirieleisón | funeral dirge/chant | noun (m) | colloquial | low | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fam.` extension of the liturgical "Kyrie eleison." |
| kilotón | kiloton (explosive-yield unit) | noun (f) | technical | — | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | |
| mesón (regional sense) | shop counter | noun (m) | regional | moderate | contemporary | Chile | national | grammar_reference | verified | n/a | Standard Spanish *mesón* means "inn/tavern" — a striking regional semantic shift to "counter." |
| mestro, -tra | (non-standard form of "maestro," teacher) | noun | stigmatized/"barbarismo" | low | contemporary | Chile, Col., México | multi-national | grammar_reference | verified | n/a | Flagship find: the dictionary explicitly labels this "Barbarismo por maestro" — a rare prescriptive, not merely dialectal, flag. |
| mesticia | sadness, affliction | noun (f) | archaic | low | contemporary (archaic term) | — | Pan-Hispanic | grammar_reference | verified | n/a | Tagged `p. us.` (poco usado, rarely used today). |
| mesonaje | place with many inns/lodging houses | noun (m) | archaic | low | contemporary (archaic term) | — | Pan-Hispanic | grammar_reference | verified | n/a | Tagged `p. us.` |
| mester de clerecía | medieval clerical narrative-poetry tradition | noun phrase | historical/literary | — | medieval (as referent); contemporary (dictionary entry) | Spain | national | grammar_reference | verified | n/a | Contrasted in the same entry with *mester de juglaría* (minstrel tradition). |
| mesta | historical sheep-herders' association/guild | noun (f) | historical | — | medieval–early modern (as referent) | Spain | national | grammar_reference | verified | n/a | From Latin *mixta*. |
| sarazo, -za | half-ripe (said of corn) | adj. | regional/agricultural | moderate | contemporary | Amér. (generic) | transnational | grammar_reference | verified | n/a | |
| sargentona | mannish, bossy woman | noun (f) | derogatory/colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Tagged `fam. desp.` — a clean example of the dictionary's combined familiar+derogatory register stack. |
| sariga | opossum | noun (f) | regional | low | contemporary | Bol., Perú | multi-national | grammar_reference | verified | n/a | Regional synonym for standard *zarigüeya*. |
| sarita | flat straw hat | noun (f) | regional, eponymous | low | contemporary | Perú | national | grammar_reference | verified | n/a | Derived from the given name "Sarita" — an eponym-to-common-noun shift. |
| tronío | arrogance, ostentatious display | noun (m) | colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fam.` |
| trompetilla | small horn/ear-trumpet (dim. of trumpet) | noun (f) | neutral | low | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Diminutive morphology: *trompeta* + *-illa*. |
| tronzo, -za | (of a horse) having a particular gait defect | adj. | archaic/technical | low | contemporary (archaic term) | — | Pan-Hispanic | grammar_reference | verified | n/a | Tagged `p. us.` |
| vomitona | a big bout of vomiting | noun (f) | colloquial | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fam.`; augmentative morphology: *vómito* + *-ona*. |
| vulpino, -na | foxlike, cunning | adj. | formal/figurative | low | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | `fig.` extension of the literal "pertaining to foxes" (from Latin *vulpinus*). |
| atar (fig. sense) | to be stuck, unable to find a way out of a jam | verb (reflexive, fig.) | figurative | moderate | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | "No encontrar el modo de salir o escapar de un negocio, lío o apuro." |
| atenerse | to abide by, go by (consequences, rules) | verb (reflexive) | neutral | high | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Common fixed construction: *atenerse a las consecuencias*. |
| cable — coaxial / óptico | coaxial cable / optical (fiber-optic) cable | noun phrases | technical | — | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Dash sub-entries under CABLE showing the dictionary's compound-term convention. |
| kilovatio-hora | kilowatt-hour | noun phrase | technical | — | contemporary | — | Pan-Hispanic | grammar_reference | verified | n/a | Dash sub-entry under KILOVATIO. |
