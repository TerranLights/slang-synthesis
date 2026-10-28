# English — Established Vocabulary/Grammar: CMOS Ch. 8, "Names and Terms," pt. 5 (§§8.99–8.124: Religious Jurisdictions through Plant Hybrids)

**Source:** *The Chicago Manual of Style*, 16th edition (University of Chicago Press, 2010), Chapter
8, "Names and Terms," PDF pp. 1103–1128 (sections 8.99 through 8.124).

**Coverage note:** This chunk covers the back half of the "Religious Names and Terms" subsection
(§§8.99–8.110: jurisdictions, buildings, councils/synods, scriptures, bible names/versions/books/
sections, prayers/creeds, religious events/concepts, afterlife terms, services/rites, objects), the
full "Military Terms" subsection (§§8.111–8.114: forces/armies, wars/revolutions, battles/campaigns,
medals/awards), the "Names of Ships and Other Vehicles" subsection (§§8.115–8.117: named vessels,
other vehicle names, pronouns for vessels), and the opening of "Scientific Terminology" (§§8.118–
8.124: additional resources pointer, genus/specific-epithet binomials, genus abbreviation, subspecies/
varieties, unspecified species, author names, plant hybrids). This is CMOS ch. 8's fifth part; prior
parts (pt. 1–4, not yet landed as of this dispatch) cover earlier chapter-8 territory, and the
remainder of "Scientific Terminology" plus "Names of Other Groups and Formulations" fall into later
parts. Every numbered rule in the assigned range is captured, along with every distinct illustrative
term the source lists under it — this chapter is a capitalization/register style guide, not a
vocabulary-teaching text, so its "vocabulary" consists of the specific proper nouns and generic
counterpart terms used to illustrate each capitalization rule (grouped into one table row per rule's
example set, following the convention set by `017_cmos_ch07_spelling_compounds_pt01.md`). The source
has a genuine clean text layer; no vision-reading was required and no handwritten marginalia was
present. Per dispatch instruction, Attested Era is "contemporary (source published 2010)" and Attested
Region "American English (United States)" throughout (book-level attribution, not per-word).

**Mojibake gotcha confirmed on this chunk, per the known-issue warning:** two Sanskrit-derived terms
in §8.102 render with corrupted diacritics — "Bhagavad GÄ«tÄ" and "MahÄbhÄrata." Decoded: the source's
real diacritic characters (ī = U+012B, ā = U+0101) are UTF-8-encoded as the two-byte sequences `C4 AB`
and `C4 81`; a Latin-1/Windows-1252 misread of those bytes renders `C4 AB` as "Ä«" (matches what
appears) and `C4 81` as a bare "Ä" with the second byte (0x81, an unprintable C1 control position in
Latin-1/cp1252) silently dropped from the rendered text — which exactly matches the visible garbling
(a trailing "Ä" with no visible second glyph). Corrected forms used below: **Gītā**, **Mahābhārata**.
A third instance appears in §8.124: the plant-hybrid multiplication sign is rendered as "Ã—" in the
extracted text — U+00D7 (×) is UTF-8-encoded as `C3 97`, and a Windows-1252 misread of those bytes
renders `C3 97` as "Ã" + "—" (em dash, cp1252 position 0x97), matching "Ã—" exactly; corrected form
used below: **×**. All three decodes are cross-verified against the source's own explicit prose (e.g.
§8.124 literally states the symbol is "a multiplication sign (×; *not* the letter x)"), so confidence
in each correction is high — these are Notes-column corrections to a text-layer encoding artifact, not
Vision Reading Confidence issues (the source had a real text layer throughout; Vision Reading
Confidence is `n/a` for every row). A fourth, non-lexical instance was spotted in the page sidebar
navigation only (§8.118's running header rendered as "Scientific styleâ€"additional resources," where
em dash U+2014 → UTF-8 `E2 80 94` → cp1252 misread "â€"" ) — not extracted as vocabulary since it is
chapter-navigation chrome, not source prose, but noted here as a second confirming instance of the
same mojibake mechanism within this chunk.

---

## Vocabulary

Illustrative example terms from the chapter, grouped by the rule they demonstrate. All entries: Usage
Tier `core` unless noted (register-neutral proper-noun/generic-term capitalization examples), Attested
Era `contemporary (source published 2010)`, Attested Region `American English (United States)`,
Geographic Scope `national` unless the term is itself a specific local/transnational institution (then
noted), Source Type `grammar_reference`, Transcription Confidence `n/a`, Vision Reading Confidence
`n/a`.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| the Archdiocese of Chicago / the archdiocese; the Eastern Diocese of the Armenian Church; the Fifty-Seventh Street Meeting / the (Quaker) meeting; the Holy See; the Missouri Synod / the synod | official division names within organized religions, capitalized; generic term used alone, lowercased | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.99 |
| Babri Mosque / the mosque; Bethany Evangelical Lutheran Church / the church; Temple Emanuel / the temple / the synagogue; Nichiren Buddhist Temple / the temple | names of buildings where religious congregations meet, capitalized; generic term alone, lowercased | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.100 |
| the Council of Chalcedon (*or* the Fourth Ecumenical Council); the General Convention (Episcopal); the Second Vatican Council / Vatican II; the Synod of Whitby | accepted names of historic councils and official names of modern counterparts, capitalized | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.101 |
| the Bhagavad Gita (*or* Bhagavad Gītā); the Bible / biblical; the Book of Common Prayer; the Dead Sea Scrolls; the Hebrew Bible; Koran / Koranic (*or, less commonly,* Qur'an / Qur'anic); the Mahabharata (*or* Mahābhārata); Mishnah / Mishnaic; Sunna; Talmud / Talmudic; Tripitaka; the Upanishads; the Vedas / Vedic; *but* sutra(s) | names of scriptures and other highly revered religious works, capitalized but not usually italicized (except when used as a published-work title); the generic "sutra(s)" stays lowercase | proper noun / adjective | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.102; Gītā/Mahābhārata mojibake-corrected per coverage note above, decode cross-verified against §8.124's explicit multiplication-sign gloss |
| the Authorized Version (*or* the King James Version); the Breeches (*or* Geneva) Bible; Codex Sinaiticus; Complutensian Polyglot Bible; the Holy Bible; Holy Writ (sometimes used figuratively); the New English Bible; the New Jerusalem Bible; the New Revised Standard Version; Peshitta; the Psalter (*but* a psalter); the Septuagint; the Vulgate; *but* scripture(s) / scriptural | other names and versions of the Hebrew/Christian bibles, usually capitalized but not italicized; generic "scripture(s)/scriptural" lowercased | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.103 |
| Genesis / the book of Genesis; Job / the book of Job; 2 Chronicles / the second book of the Chronicles; Psalms (*but* a psalm); John / the Gospel according to John; Acts / the Acts of the Apostles; 1 Corinthians / the First Epistle to the Corinthians | names of individual Bible books, capitalized but never italicized; "book" usually lowercased, "gospel"/"epistle" usually capitalized (all three may be treated alike if used together with frequency) | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.104; see also cross-referenced §§9.27, 10.45–51 |
| the Hebrew scriptures (*or* the Old Testament); the Christian scriptures (*or* the New Testament); the Apocrypha / Apocryphal (*or, generically,* apocryphal); the Epistles / the pastoral Epistles; the Gospels / the synoptic Gospels; the Pentateuch (*or* the Torah) / Pentateuchal; Hagiographa (*or* Ketuvim) / hagiographic | names of major sections of the Bible, usually capitalized but not italicized | proper noun / adjective | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.105 |
| the Decalogue / the Ten Commandments / the first commandment; Kaddish / to say Kaddish; the Lord's Prayer / the Our Father; Luther's Ninety-Five Theses; the Nicene Creed / the creed; Salat al-Fajr; the Sermon on the Mount; the Shema; *but* the doxology, the parable of the prodigal son, the miracle of the loaves and fishes, the star of Bethlehem | named prayers, canticles, creeds, and scriptural terms of special importance, usually capitalized; parables and miracles usually lowercased | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.106 |
| the Creation; the Crucifixion; the Diaspora; the Exodus; the Fall; the Second Coming; *but* creation myths (generic), crucifixion (generic, as a Roman execution method) | religious events/concepts of major theological importance, often capitalized; generic/non-specific use lowercased | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.107, first half |
| atonement; dharma; original sin; resurrection | doctrines and principles, usually lowercased | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.107, second half |
| heaven; hell; limbo; nirvana; outer darkness; paradise; the pearly gates; purgatory; *but* Eden, Elysium, Hades, Olympus | terms for divine dwelling places/ideal states/places of divine punishment, usually lowercased (though often capitalized in purely religious context); named mythological/specific afterlife-places capitalized | noun / proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.108; cross-referenced to §8.49 |
| baptism; bar mitzvah; bat mitzvah; confirmation; morning prayer / matins; the seder; the sun dance; vespers | names of religious services and rites, usually lowercased (may be capitalized in strictly religious contexts; consult Webster's if in doubt) | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.109, first half |
| the Eucharist; Holy Communion; Mass / to attend Mass / High Mass / Low Mass; *but* three masses are offered daily (generic plural) | terms denoting the Eucharistic sacrament specifically, traditionally capitalized (though may be lowercased in nonreligious contexts); generic plural "masses" lowercased | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.109, second half |
| altar; ark; chalice and paten; mandala; mezuzah; rosary; sacred pipe; sanctuary; stations of the cross | objects of religious use/significance, usually lowercased (especially in nonreligious contexts) | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.110 |
| the Allies (World Wars I and II) / the Allied forces; American Expeditionary Force / the AEF; Army Corps of Engineers / the corps; Army of Northern Virginia / the army; Army of the Potomac; Army Special Forces; the Axis powers (World War II); Canadian Forces (unified 1968); the Central powers (World War I); Combined Chiefs of Staff (World War II) | titles of armies/navies/air forces/fleets/regiments/battalions/companies/corps, capitalized; unofficial but well-known names (e.g. Green Berets) also capitalized; "army"/"navy" etc. lowercased standalone, collective-plural, or not part of an official title | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.111, group 1 of 3; see also §8.18 |
| Confederate army (American Civil War); Continental navy (American Revolution); Eighth Air Force / the air force; Fifth Army / the army; First Battalion, 178th Infantry / the battalion / the 178th; French Foreign Legion; Green Berets; Joint Chiefs of Staff; the Luftwaffe / the German air force; National Guard | continuation of military-force naming examples (capitalized official titles; lowercased generic/standalone forms) | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.111, group 2 of 3 |
| Pacific Fleet (US, World War II); the Red Army (Russian, World War II) / Russian army; the Resistance / the French Resistance / a resistance movement; Rough Riders; Royal Air Force / RAF / British air force; Royal Canadian Mounted Police / the Mounties / a Mountie; Royal Navy / the British navy; Royal Scots Fusiliers / the fusiliers; Seventh Fleet / the fleet; Thirty-Third Infantry Division / the Thirty-Third Division / the division; Union army (American Civil War); United States (*or* US) Army / the army; United States Coast Guard / the Coast Guard (*or* the coast guard); United States Marine Corps / the Marine Corps (*or* the marine corps) / the US Marines / a marine; United States Navy / the navy; United States Army Signal Corps / the Signal Corps (*or* the signal corps) | continuation of military-force naming examples, concluding the §8.111 list; includes cross-reference notes that Royal Canadian Air Force and Royal Canadian Navy are historical names subsumed by Canadian Forces after 1968 | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.111, group 3 of 3 |
| American Civil War / the War between the States; American Revolution / American War of Independence / the revolution (sometimes capitalized) / the Revolutionary War; the Crusades / the Sixth Crusade / a crusader; French Revolution / the Revolution of 1789 / the Revolution (usually capitalized to distinguish from the revolutions of 1830/1848) / revolutionary France; Great Sioux War / the Sioux war; Gulf War; Korean War / the war; Mexican Revolution / the revolution; Napoleonic Wars; Norman Conquest / the conquest of England; the revolution(s) of 1848; Russian Revolution / the revolution; Seven Years' War; Shays's Rebellion; Six-Day War; Spanish-American War; Spanish Civil War; Vietnam War; War of 1812; Whiskey Rebellion; World War I / the First World War / the Great War / the war; World War II / the Second World War / World Wars I and II / the First and Second World Wars / the two world wars | names of most major wars and revolutions, capitalized; generic terms (the war, the revolution) usually lowercased when standing alone | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.112 |
| Battle of Britain; Battle of the Bulge (*or* Battle of the Ardennes); Battle of Bunker Hill / Bunker Hill / the battle; *but* battle of Vimy Ridge (lowercase, more generic description); the European theater of operations / ETO; Mexican border campaign; Operation Devil Siphon; third battle of Ypres; Vicksburg Campaign; western front (World War I) | names of major battles/campaigns that have entered general usage, capitalized; more generic battle descriptions capitalize only the proper name within them | proper noun / common noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.113; CMOS directs readers to an encyclopedia for battle names not covered here |
| Congressional Medal of Honor / Medal of Honor; Croix de Guerre (sometimes lowercased); Distinguished Flying Cross / DFC; Distinguished Service Order / DSO; Purple Heart; Silver Star; Victoria Cross / VC | specific names of military medals and awards, capitalized | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.114; cross-referenced to §8.82 for civil awards |
| Mars global surveyor / Mars polar lander; *Phoenix* Mars lander / *Phoenix*; the space shuttle *Discovery*; the *Spirit of St. Louis*; HMS *Frolic* / the British ship *Frolic*; SS *United States* / the *United States*; USS *SC-530* / the US ship *SC-530*; USS *Enterprise* (CVN-65) | names of specific ships and other named vessels, capitalized and italicized (the name itself, not the vessel-type word or USS/HMS-style abbreviation, which are set roman); hull numbers included at first mention when needed to distinguish same-named vessels | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.115; "ship" itself (or other vessel-type word) is not used directly after USS/HMS-style abbreviations; cross-referenced to Eric Wertheim's *The Naval Institute Guide to Combat Fleets of the World* |
| Acela Express; Boeing 747; Concorde; Metroliner; Project Apollo; Toyota Prius | names of aircraft makes/classes, automobile/vehicle models, trains/train runs, and space programs, capitalized but not italicized | proper noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.116 |
| it / its (preferred over she / her) | preferred neuter pronoun for referring to a vessel | pronoun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.117; cross-referenced to §§5.41, 8.76 |
| *Scientific Style and Format*; the *International Code of Botanical Nomenclature* / ICBN; the *International Code of Zoological Nomenclature* / ICZN | authoritative style resources for scientific nomenclature, cited as the ultimate authorities (note: virology and some other fields follow slightly different rules) | proper noun (title/abbreviation) | technical | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.118 |
| *Smilodon*; *Rosa caroliniana*, *Styrax californica* (species reflecting locale of first specimens); the pike, *Esox lucius*; the grass snake *Natrix natrix*; *Basiliscus*, *Crotaphytus* (lizard genera, bipedal specialists) | Latin binomial names of plant/animal species — genus (generic name) capitalized, species (specific name/specific epithet) lowercased even if a proper adjective — both elements italicized; not to be confused with (non-italicized) phyla/order names | proper noun (scientific name) | technical.biology | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.119; cross-referenced to §8.125 |
| *Callisaurus draconoides* / *C. draconoides*; *Uma scoparia*; *Populus tremuloides* ("quaking" aspen) / *P. deltoides* (cottonwood); *Cyclamen coum*, *C. hederifolium*, *C. persicum*; *Corylus avellana* and *Corokia cotoneaster* (doubled abbreviation *CC.* when both species listed together) | abbreviation of a genus name to a single capital letter after first use; doubled abbreviation when two-plus species of the same genus are listed together, though repeating the full abbreviation per species is also common; full names retained if differing genera share the same first letter | proper noun (scientific name, abbreviated) | technical.biology | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.120 |
| *Noctilio labialis labialis* (*or* *Noctilio l. labialis*); *Trogon collaris puella*; *Buxus microphylla* var. *japonica*; *Hydrangea anomala* subsp. *petiolaris*; *Rhododendron arboreum* f. *album* | zoological subspecific name/epithet (trinomial, fully italicized, first repeated element abbreviable if identical to the species name); horticultural subspecies/variety/form abbreviations "subsp." ("ssp."), "var.," "f." (not italicized) inserted before the relevant epithet | proper noun (scientific name) | technical.biology | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.121; cross-referenced to §8.122 |
| *Rhododendron* spp.; *Rosa rugosa* var.; *Viola* sp. | abbreviations "sp." (singular) and "var." indicating an unknown/unspecified species or variety; plural "spp." refers to a group of species; abbreviations themselves not italicized | proper noun (scientific name, abbreviated) | technical.biology | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.122 |
| *Diaemus youngi cypselinus* Thomas; *Euchistenes hartii* (Thomas); *Felis leo* Scop.; *Molossus coibensis* J. A. Allen; *Quercus alba* L. | name of the person (often abbreviated) who proposed a specific epithet, added after the binomial/trinomial, never italicized; a capital "L." stands for Linnaeus; a parenthesized author name indicates the species was later reassigned to a different genus than the one the author originally used | proper noun (author citation) | technical.biology | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.123 |
| *Magnolia denudata* × *M. liliiflora* (crossing of species); *Magnolia* ×*soulangeana* (hybrid name) | crossing of two plant species indicated by a multiplication sign (×, *not* the letter x), spaced on each side for a cross notation; older primary-hybrid naming places the sign immediately before the hybrid's specific epithet, with a space only before it | proper noun (scientific name, hybrid) | technical.biology | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §8.124; "×" mojibake-corrected from extracted "Ã—" per coverage note above |

## Grammar points

### §8.99 Religious jurisdictions
Official division names within organized religions (archdioceses, dioceses, meetings, synods, the
Holy See) are capitalized; the generic term used alone (the archdiocese, the meeting, the synod) is
lowercased. P. 1103.

### §8.100 Buildings
Names of specific buildings where religious congregations meet are capitalized; the generic term used
alone (the mosque, the church, the temple, the synagogue) is lowercased. P. 1104.

### §8.101 Councils, synods, and the like
The accepted historical names and official modern names of religious councils/synods are capitalized,
regardless of whether the historic or modern name is used. P. 1105.

### §8.102 Scriptures
Names of scriptures and other highly revered religious/philosophical works are capitalized but not
usually italicized — the exception is when the name is used as the title of a specific published
edition. A short list of generic terms for sacred texts (e.g. "sutra(s)") stays lowercase even though
the named scriptures themselves are capitalized. Pp. 1105–1106. See the coverage note above for the
two mojibake-corrected diacritic terms in this section (Gītā, Mahābhārata).

### §8.103 Other names and versions for bibles
Alternate historical names and specific published versions of the Hebrew/Christian bibles (the
Authorized Version, the Vulgate, Codex Sinaiticus, etc.) are usually capitalized but not italicized.
The generic "scripture(s)/scriptural" remains lowercase even in a biblical context. P. 1107.

### §8.104 Books of the Bible
Individual book names (Genesis, Job, Psalms, Acts, etc.) are capitalized but never italicized. The
word "book" is usually lowercased when paired with a book name ("the book of Genesis"), while "gospel"
and "epistle" are usually capitalized in the same construction ("the Gospel according to John," "the
First Epistle to the Corinthians") — but in a work using all three terms with real frequency, Chicago
allows treating them alike (all lowercased or all capitalized) for consistency. P. 1108.

### §8.105 Sections of the Bible
Names of major Bible sections/subdivisions (the Old/New Testament, the Apocrypha, the Epistles, the
Gospels, the Pentateuch/Torah, Hagiographa/Ketuvim) are usually capitalized but not italicized; their
adjectival forms (apocryphal, hagiographic) are lowercased. P. 1109.

### §8.106 Prayers, creeds, and such
Named prayers, canticles, creeds, and scriptural terms of special theological importance (the
Decalogue, the Lord's Prayer, the Nicene Creed, the Sermon on the Mount, named prayer-rituals like
Salat al-Fajr and Kaddish) are usually capitalized. Parables and miracles, by contrast, are usually
lowercased even when referring to a specific, well-known one (the parable of the prodigal son, the
miracle of the loaves and fishes) — as is "the doxology." P. 1110.

### §8.107 Religious events and concepts
Events and concepts of major theological importance (the Creation, the Crucifixion, the Exodus, the
Second Coming) are often capitalized; the same word used generically or non-specifically (crucifixion
as a form of Roman execution, "creation myths" generally) is lowercased. Doctrines and principles as a
category (atonement, dharma, original sin, resurrection) are usually lowercased even when referring to
a specific tradition's version of the concept. P. 1111.

### §8.108 Heaven, hell, and so on
General terms for divine dwelling places, ideal states, and places of divine punishment (heaven, hell,
nirvana, purgatory, the pearly gates) are usually lowercased, though they may be capitalized in a
purely religious context. Named mythological/specific places (Eden, Elysium, Hades, Olympus) remain
capitalized as proper nouns regardless of context. P. 1112. Cross-referenced to §8.49.

### §8.109 Services and rites
Names of religious services and rites (baptism, bar/bat mitzvah, confirmation, the seder, vespers) are
usually lowercased, though they may be capitalized in strictly religious contexts (consult Webster's
if in doubt). Terms specifically denoting the Eucharistic sacrament (the Eucharist, Holy Communion,
Mass) are a traditionally capitalized exception, though they too may be lowercased in nonreligious
contexts — note the contrast between "to attend Mass" (capitalized, specific-rite sense) and "three
masses are offered daily" (lowercased, generic-countable sense). P. 1113.

### §8.110 Objects
Objects of religious use or significance (altar, ark, mezuzah, rosary, stations of the cross) are
usually lowercased, especially in nonreligious contexts. P. 1114.

### §8.111 Armies, battalions, and such
Titles of armies, navies, air forces, fleets, regiments, battalions, companies, and corps are
capitalized when they are official or well-known unofficial titles (e.g. Green Berets). The generic
words "army" and "navy" (and similar) are lowercased when standing alone, used collectively in the
plural, or not part of an official title — a distinction CMOS notes is often disregarded in official
or promotional contexts, where the generic form is routinely capitalized anyway. Pp. 1115–1116. Cross-
referenced to §8.18.

### §8.112 Wars and revolutions
Names of most major wars and revolutions are capitalized (American Civil War, World War II, the
Crusades). The generic terms ("the war," "the revolution") are usually lowercased when used alone to
refer back to an already-named conflict, though some sources note the generic term is "sometimes
capitalized" in practice (e.g. "the revolution" for the American Revolution). P. 1117.

### §8.113 Battles and campaigns
Names of some major battles/campaigns that have entered general usage are capitalized outright (Battle
of Britain, Battle of the Bulge). In other, more generic descriptions of lesser-known engagements, only
the proper name within the description is capitalized ("battle of Vimy Ridge," "third battle of
Ypres") — the word "battle" itself stays lowercase in that construction. For names not covered, CMOS
directs the reader to consult an encyclopedia. P. 1118.

### §8.114 Medals and awards
Specific names of military medals and decorations (Medal of Honor, Purple Heart, Victoria Cross) are
capitalized. Croix de Guerre is noted as sometimes lowercased in practice despite being a specific
award name. P. 1119. Cross-referenced to §8.82 for civilian/civil awards.

### §8.115 Ships and other named vessels
Names of specific ships and other vessels are both capitalized and italicized. When an abbreviation
like USS (United States ship) or HMS (Her/His Majesty's ship) precedes the name, the word "ship" (or
other vessel-type word) should not also be used — the abbreviations themselves are not italicized.
Every US Navy ship is assigned a hull number (a letter-type code plus serial number, formally
implemented in 1920); where necessary to distinguish between same-named vessels (e.g. in a work on
naval history), the hull number should be included at first mention — smaller, individually numbered
but unnamed vessels (landing craft, submarine chasers) are identified by number alone. Pp. 1120–1121.
Cross-referenced to Eric Wertheim's *The Naval Institute Guide to Combat Fleets of the World*
(bibliog. 5).

### §8.116 Other vehicle names
Names of aircraft makes/classes, automobile and other vehicle models, train names/runs, and space
programs are capitalized but not italicized (contrast with ship names in §8.115, which are both). P.
1122.

### §8.117 Pronouns referring to vessels
When a pronoun refers to a vessel, the neuter "it"/"its" is preferred over the traditional feminine
"she"/"her." P. 1123. Cross-referenced to §§5.41, 8.76.

### §8.118 Scientific style — additional resources
The chapter's scientific-terminology guidance offers only general rules; detailed guidance should be
sought in *Scientific Style and Format* (bibliog. 1.1). The ultimate governing authorities are the
*International Code of Botanical Nomenclature* (ICBN) for the botanical examples that follow and the
*International Code of Zoological Nomenclature* (ICZN, see bibliog. 5) for zoological ones. Some
fields (virology is named specifically) follow somewhat different rules, and writers/editors should
defer to a given field's own established practice. P. 1124.

### §8.119 Genus and specific epithet
In lists or running text, the Latin binomial names of plant and animal species are italicized. Each
binomial consists of a genus name (also called the generic name), which is capitalized, and a species
name (also called the specific name or specific epithet), which is lowercased even when it is itself a
proper adjective (e.g. a locale-derived species epithet like *caroliniana* or *californica*). This
should not be confused with the (non-italicized) names of higher taxonomic divisions — phyla, orders,
and the like, covered later at §8.125. P. 1125.

### §8.120 Abbreviation of genus name
After its first full use, a genus name may be abbreviated to a single capital letter (e.g. *Callisaurus
draconoides* → *C. draconoides*). When two or more species of the same genus are listed together, the
abbreviation may be doubled to indicate the plural before the first species (though repeating the
single-letter abbreviation before each species individually is more common in practice). If species of
different genera that happen to begin with the same letter are discussed in the same context, using the
bare abbreviation may be inappropriate/ambiguous and the fuller form should be retained. P. 1126.

### §8.121 Subspecies and varieties
A subspecific zoological name or epithet, when used, follows the binomial species name and is also
italicized, forming a trinomial; if the subspecific epithet repeats the species name, the first
occurrence may be abbreviated (*Noctilio l. labialis*). In horticultural usage, the (non-italicized)
abbreviations "subsp." (or "ssp."), "var.," and "f." are inserted before the subspecific epithet,
variety name, or form name respectively. P. 1127. Cross-referenced to §8.122.

### §8.122 Unspecified species and varieties
The (non-italicized) abbreviations "sp." and "var.," used without a following element, indicate that
the species or variety is unknown or deliberately left unspecified. The plural form "spp." refers to a
group of species collectively. P. 1128, first half.

### §8.123 Author names
The name of the person who originally proposed a specific epithet may optionally be added after the
binomial/trinomial — often itself abbreviated — and is never italicized. A bare capital "L." is the
conventional abbreviation standing specifically for Linnaeus. When the author name appears in
parentheses, this indicates the author described the species but under a different genus assignment
than the one now used (i.e. the species was later moved to its current genus by someone else). P. 1128,
second half.

### §8.124 Plant hybrids
The crossing of two plant species is indicated by a true multiplication sign (×, U+00D7) — explicitly
*not* the letter "x" — placed between the two species names with a space on each side. Many older
primary plant-hybrid names instead place the multiplication sign immediately before the hybrid's own
specific epithet, with a space only before the sign (and none after, since it is fused to the epithet).
P. 1128, end of chunk. See the coverage note above for this section's mojibake-corrected multiplication
sign.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`.
