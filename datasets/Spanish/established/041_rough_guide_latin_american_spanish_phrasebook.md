# Spanish — Established Vocabulary/Grammar: The Rough Guide Latin American Spanish Phrasebook

**Source:** *The Rough Guide Latin American Spanish Phrasebook* (Rough Guides, pan-regional Latin
America edition), 308 pages. PDF confirmed to have a genuine, clean text layer; `pdftotext -layout`
extracted cleanly (~13,900 lines / ~70,900 words), no OCR or vision-reading required. Minor
encoding artifacts (`Â€...` for ellipsis glyphs, and mangled TOC glyphs on a couple of lines) are
cosmetic only and do not affect headwords, glosses, or country tags.

**Structure:** identical to its siblings — Basic Phrases → English-Spanish dictionary →
Spanish-English dictionary (opens with a dedicated "Colloquial Spanish" slang list) → Menu Reader →
"How the Language Works" (grammar, including a dedicated voseo verb-paradigm section) →
Numbers/Conversion Tables. Unlike its two siblings, this book is explicitly pan-regional and tags
individual dictionary entries with a **country-abbreviation system** (reproduced below) wherever a
word, meaning, or pronunciation is specific to one country or sub-region rather than universal
across Spanish America — this internal tagging is this book's single highest-value feature for the
slang-synthesis project, since it is dialect-geography signal straight from the source rather than
something this extraction has to infer.

### Country-abbreviation key (reproduced from the book, p.272)

| Abbr. | Country/region | Abbr. | Country/region |
|---|---|---|---|
| Andes | Andes | Hond | Honduras |
| Arg | Argentina | Mex | Mexico |
| Bol | Bolivia | Nic | Nicaragua |
| CAm | Central America | Pan | Panama |
| Ch | Chile | Parag | Paraguay |
| Col | Colombia | Pe | Peru |
| CR | Costa Rica | PR | Puerto Rico |
| CSur | Southern Cone (Argentina, Chile, Paraguay, Uruguay) | Rpl | River Plate (Argentina, Uruguay) |
| Cu | Cuba | Salv | El Salvador |
| Ec | Ecuador | SAm | South America |
| Guat | Guatemala | Urug | Uruguay |
|  |  | Ven | Venezuela |

This project's `datasets/00_Historical_and_Geographic_Context_Guide.md` Attested Region/Geographic
Scope fields are filled below directly from these book-stated tags wherever given; rows with no
country tag in the source are left blank rather than guess-filled, per project convention.

## Cross-dialect comparison trio — read this note first

This file is one of three coded **consistently** so the same concept can be compared across Spain,
Mexico, and Latin America at a glance:
- **039** — The Rough Guide Spanish Phrasebook → Spain
- **040** — The Rough Guide Mexican Spanish Phrasebook → Mexico
- **041 (this file)** — The Rough Guide Latin American Spanish Phrasebook → pan-regional, internally
  country-tagged

The headline cross-book contrasts (full comparison table in 039; repeated here for standalone
reference):

| Concept | Spain (039) | Mexico (040) | Latin America (this file) |
|---|---|---|---|
| "swearword" (the noun) | palabrota | grosería | **grosería** (identical to Mexico) |
| answering the phone | ¿Dígame?/¿Diga? | ¿Bueno? | **¿Aló?** (SAm, book-tagged) |
| "to fuck" (taboo) | *not this verb* — coger = neutral | coger = taboo "to fuck" | **coger = taboo "to fuck"** (identical to Mexico) |
| flagship taboo "to fuck" verb | joder (excl. "fuck!") | chingar (flagship) | **chingar and tirar both attested** — this book's own list uses both roots |
| "zero" pronunciation | cero [thairo] (distinción) | cero [sairo] (seseo) | cero **[sairo]** (seseo, identical to Mexico) |
| 2nd-person plural | vosotros (fam) vs ustedes (pol) | ustedes only | **ustedes generally; vos (voseo) also productive** in the Rpl/Central America zone |

**Non-redundant-supplement note:** This project's 002 (*Colloquial Spanish 2*) already has a
flagship, fully-worked voseo section (the complete vos/sos present-indicative and imperative
paradigm, attested in Argentina/Uruguay/Paraguay/Chile + parts of Central America/southern Mexico).
This book's own "How the Language Works" section has a near-identical voseo paradigm (hablás/comés/
abrís, sos, etc.) — it is **not re-extracted here** to avoid duplicating 002's flagship coverage;
only the lexical/slang/country-tagged content that 002 does not cover is extracted below.

The standout finding unique to this book is that it exposes dialect variation **within** Latin
America itself, not just against Spain/Mexico — e.g. "boy" is chavo (Mex/Ven), chamaco
(CAm/Cuba/Mex), or pibe (Rpl) depending on country; "guagua" means "bus" in Cuba but "baby" in the
Andes/Chile — a genuine false-friend pair inside the same pan-regional label.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| grosería | swearword, oath | noun (f) | core | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical headword/gloss to Mexico's book (040); contrast Spain's "palabrota" (039) |
| aló | hello (phone greeting) | interjection | colloquial | — | contemporary | South America | regional | grammar_reference | n/a | n/a | book-tagged (SAm); contrast Spain's "¿Dígame?" (039) and Mexico's "¿Bueno?" (040, though "bueno" is also used as a phone greeting in parts of this book's own area) |
| coger | to fuck | verb (taboo) | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical taboo sense to Mexico's book (040); contrast Spain where this exact verb is neutral for "to catch/take" (039) |
| tirar | to fuck | verb (taboo) | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | second taboo root for the same sense alongside chingar/coger in this book's own colloquial list — no equivalent taboo sense for "tirar" attested in either Spain's or Mexico's lists here |
| cero [sairo] | zero | number | core | — | contemporary | — | transnational | grammar_reference | n/a | n/a | transliterated with "s" (seseo), identical to Mexico's book (040); contrast Spain's "[thairo]" (distinción), see 039 |
| vos / voseo paradigm | you (2nd sg. informal) + its verb conjugation | pronoun + verb forms | regional | — | contemporary | Argentina, Uruguay, Paraguay, parts of Central America (book's own "How the Language Works" voseo section) | regional | grammar_reference | n/a | n/a | NOT re-extracted here in grammatical depth — flagship coverage already exists in established/002; flagged only to note this book independently confirms the same regional footprint |
| ¿a quién carajos le importa? | who bloody cares? | idiom | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | from the book's dedicated "Colloquial Spanish" list, p.128 |
| ¡bien! | great! | interjection | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical slot-form "¡bien!" ("good!") also attested in Mexico's list (040) |
| boludo | dickhead | noun/insult (m) | taboo | — | contemporary | — (not country-tagged in this list; widely known elsewhere as a Río de la Plata/Argentine flagship term, but the book's own colloquial list gives no explicit country tag here, so left blank per non-guess-fill convention) | — | grammar_reference | n/a | n/a | no equivalent single-root term attested in Spain's or Mexico's lists |
| cabrón | bastard | noun/insult (m) | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical headword/gloss shared with Spain (039) and Mexico (040) |
| ¡cómo no! | of course | interjection | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | — |
| ¡carajo! | Christ!, shit! | interjection | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form also attested in Mexico's list (040); "carajo" also resurfaces inside Spain's "¡vete al carajo!" (039) |
| chingar | to fuck | verb (taboo) | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | same flagship Mexican-rooted taboo verb also appears in this pan-regional list, alongside the separate root "tirar" above — see 040 |
| ¡chinga tu madre! | fuck off! | interjection | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form also attested in Mexico's list (040) |
| ¿dónde carajos? | where the hell? | idiom | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | near-identical to Mexico's "¿dónde carajos? — where in hell?" (040); minor wording difference only |
| ¡hijo de la chingada! | son of a bitch! | interjection | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form also attested in Mexico's list (040) |
| ¡hijo de puta! | son of a bitch! | interjection | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form also attested in Spain's list (039); this book is the only one of the three to attest BOTH this and the chingada-rooted variant in the same list |
| ¡hijueputa! | son of a bitch! | interjection | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | phonologically contracted/elided form of "hijo de puta" (hijo+de+puta > hijueputa); a clean `phonological_reduction` example for this project's slang-mechanics analysis, with no contracted counterpart attested in Spain's or Mexico's lists |
| huevón | jerk! | interjection/insult (m) | taboo | — | contemporary | — (not country-tagged in this list; book's wider dictionary elsewhere associates huevón-family terms with Andean/Chilean usage, but no explicit tag given on this exact entry, so left blank) | — | grammar_reference | n/a | n/a | — |
| joder | to screw up | verb | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical milder verbal sense also attested in Mexico's list (040); contrast Spain where "¡joder!" is instead the strong taboo exclamation "fuck!" (039) |
| ¡la puta! | bloody hell! | interjection | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | — |
| ¡lárguese! | go away! | interjection | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form also attested in Mexico's list (040); contrast Spain's bare-imperative "¡largo!" (039) |
| ¡lo jodiste! | you screwed up! | idiom | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form also attested in Mexico's list (040) |
| maldita sea | damn! | interjection | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | — |
| marica, maricón | queer | noun/slur (m) | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical headword/gloss shared with Mexico's list (040); Spain's list instead presents it as the exclamation "¡maricón!" (039) |
| me pega la gana | I feel like it | idiom | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form also attested in Mexico's list (040) |
| ¡me importa un carajo! | I don't give a shit! | idiom | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | functional parallel to Spain's "¡me importa un bledo!" (milder register, 039) and Mexico's "me vale (madre)" (040) — three different idioms for the same "I don't care" function across the trio |
| ¡mierda! | shit! | interjection | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form attested in all three books — see 039/040 |
| ¡ni modo! | well, what can you do? | idiom | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form also attested in Mexico's list (040) |
| no me da la gana | I couldn't be bothered | idiom | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | near-opposite-polarity counterpart to Mexico's "me pega la gana" (I feel like it, 040) — same noun "la gana" with a different light verb (dar vs pegar) and negation |
| ¡oiga! | listen here!; excuse me! | interjection | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form also attested in Mexico's list (040) |
| ¡qué cagada! | what a fuck-up! | interjection | taboo | — | contemporary | — | transnational | grammar_reference | n/a | n/a | different root from Mexico's functional equivalent "¡qué chingadera!" (040) — same slot, different taboo etymology (caca/cagar vs chingar) |
| ¿qué hubo? | how's it going? | idiom | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | shorter cognate of Mexico's more elaborated "¿qué húbole?" (040) — same root (haber), different degree of colloquial suffixation |
| ¡qué va! | no way! | interjection | colloquial | — | contemporary | — | transnational | grammar_reference | n/a | n/a | identical form attested in all three books — see 039/040 |
| guagua | bus | noun (f) | regional | — | contemporary | Cuba | regional | grammar_reference | n/a | n/a | book-tagged (Cu); FALSE-FRIEND WITHIN LATIN AMERICA ITSELF — the same word "guagua" means "baby" in the Andes/Chile region per this book's own wider dictionary, a genuine intra-regional homonym worth flagging for slang-mechanics `semantic_shift` analysis |
| chavo | boy | noun (m) | colloquial | — | contemporary | Mexico, Venezuela | regional | grammar_reference | n/a | n/a | book-tagged (Mex, Ven); identical tagging to Mexico's own book (040) |
| chamaco | kid | noun (m) | colloquial | — | contemporary | Central America, Cuba, Mexico | regional | grammar_reference | n/a | n/a | book-tagged (CAm, Cu, Mex); identical tagging to Mexico's own book (040) |
| pibe | boy | noun (m) | colloquial | — | contemporary | Río de la Plata (Argentina, Uruguay) | regional | grammar_reference | n/a | n/a | book-tagged (Rpl); completes this book's 3-way internal regional map for "boy" alongside chavo (Mex/Ven) and chamaco (CAm/Cu/Mex) |
| mina | girl, woman | noun (f) | colloquial | — | contemporary | Argentina | regional | grammar_reference | n/a | n/a | book-tagged (Arg), from the "la mina" entries in the dictionary |
| yanqui | Yankee, American | noun/adjective | colloquial | — | contemporary | Argentina | regional | grammar_reference | n/a | n/a | book-tagged (Arg) |
| parcero | friend, buddy | noun (m) | colloquial | — | contemporary | Colombia | regional | grammar_reference | n/a | n/a | book-tagged (Col); flagship Colombian term of address |
| balurdo | uncool, naff | adjective | colloquial | — | contemporary | Central America, Venezuela | regional | grammar_reference | n/a | n/a | book-tagged (CAm, Ven) |
| bamba | fake | adjective | colloquial | — | contemporary | Peru | regional | grammar_reference | n/a | n/a | book-tagged (Pe) |
| banano | banana | noun (m) | regional | — | contemporary | Central America | regional | grammar_reference | n/a | n/a | book-tagged (CAm); contrast "banana" (f) tagged Peru/Río de la Plata in the same dictionary — a regional gender/lexeme split for the same fruit within Latin America |
| barata | cockroach | noun (f) | regional | — | contemporary | Chile | regional | grammar_reference | n/a | n/a | book-tagged (Ch); false-friend risk noted — "barata" elsewhere in Spanish generically means "cheap" (fem. of barato), unrelated sense |
| bárbaro | great, fantastic | adjective | colloquial | — | contemporary | Río de la Plata (Argentina, Uruguay) | regional | grammar_reference | n/a | n/a | book-tagged (Rpl); functional parallel to Spain's "guay" (039) and Mexico's "padre" (040) — three different lexical items for the same "cool/great" slot across the trio |
