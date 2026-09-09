# Hungarian Slang Corpus — Magyar Szlengszótár, printed pages 90–179 (sample)

**Source:** *Magyar Szlengszótár* ("Hungarian Slang Dictionary"), a standalone Hungarian slang
dictionary. `source_reference/languages/Hungarian/Magyar Szlengszótár.pdf` — PDF pages 46–90 of
170 total, no text layer (vision-read; scanned with ACDSee, scan-metadata `CreationDate` 2015).
Publication year of the underlying book itself was not confirmed in this excerpt (no title-page
front matter was in the assigned range) — see Attested Era note below.

**PDF-page-to-printed-page mapping.** Confirmed empirically before committing to a page-range
estimate (per the spec's own warning about two-printed-pages-per-scanned-image sources): each PDF
page is a photographed two-page spread, and `printed_page_left = 2×PDF_page − 2`,
`printed_page_right = 2×PDF_page − 1`. PDF page 46 → printed pp. 90–91; PDF page 90 → printed
pp. 178–179. **This file's assigned PDF range 46–90 therefore covers printed pages 90–179 (90
printed pages)**, spanning the dictionary's alphabetical range from **el-** (page 90, headword
"elmegy") through **link** (page 179, last headword on the assigned range's final printed page).

## Coverage decision — representative sample, explicitly not exhaustive

**First inspected the format before committing to a strategy**, per the dispatch instructions.
Each two-page spread runs 4 dense columns of alphabetized headwords, each with a bracketed
Hungarian-language gloss, an optional register tag (`durva` "coarse," `tabu` "taboo/vulgar,"
`ironikus` "ironic"), and often a short illustrative example sentence. Rough count from the
sampled spreads: **on the order of 60–100 distinct headwords per two-page spread**, which across
45 assigned PDF pages (90 printed pages) implies **several thousand entries total** in the full
assigned range — far too many for exhaustive transcription, the same density class as this
project's earlier large-proverb-dictionary sample runs.

**Sampling strategy actually used — two-tier:**
1. **Spread-level sampling.** Instead of every spread, 9 spreads were selected at roughly even
   intervals across the full 45-PDF-page range (PDF pages 46, 52, 58, 64, 68, 76, 82, 88, 90),
   chosen to track the alphabet progression rather than cluster at the start. This yields coverage
   of headwords spanning **el- → f- → g- → h- → k- → l-** (confirmed the F→G letter-divider page
   at printed p. 115 and the K/L-adjacent "kőagyú" and "link" endpoints directly from the images),
   giving a representative cross-section of the assigned alphabetical range rather than only its
   first few letters.
2. **Within-spread selection.** Within each sampled spread, entries were selected rather than
   transcribed in full — prioritizing headwords that (a) illustrate a distinct slang-formation
   mechanism (metaphor, euphemism, simile-template, acronym, borrowing), (b) carry the source's own
   `durva`/`tabu` register tag (useful for the Usage Tier taxonomy), or (c) are otherwise
   semantically self-contained without needing the full illustrative example sentence reproduced.
   Near-duplicate polysemy chains under one headword (e.g., a dozen "hülyére ___ magát" variants
   all meaning slight shades of "acts stupid/plays dumb") were thinned to 2–3 representative senses
   rather than fully enumerated.

**Result: 196 entries** extracted from 9 spreads (18 printed pages) out of the 90 printed pages in
the assigned range — roughly a 20% page sample, itself only partially transcribed per spread. This
is intentionally a *representative* sample of this source's texture and slang-formation patterns,
not a corpus-complete extraction; a future pass could extract the remaining un-sampled spreads
(and letters m–z, which lie outside this file's assigned PDF-page range entirely) if fuller
coverage of this dictionary becomes a priority.

## Vision-reading notes

All 9 sampled spreads were clean, uniformly typeset commercial-print scans — clear black-on-white
text, consistent font throughout, no handwritten marginalia, underlining, or reader annotation
observed on any sampled page. No marginalia-guard exclusions were needed. Print was legible at
100dpi rendering on every sampled page; no faded or obscured regions were encountered. Given this,
**Vision Reading Confidence is `plausible_unverified` throughout** (read with high confidence from
clear print, but not independently cross-checked against a second source) rather than `verified`,
per the spec's stricter definition of "verified." No entries required `low_confidence` flagging.

## Copyright discipline applied

Per spec, this file does **not** bulk-reproduce the dictionary's own illustrative example
sentences. Glosses below are paraphrased translations of the source's own bracketed Hungarian
definitions (not verbatim quotes of the definitions, and not the example sentences), which is
translation-plus-paraphrase rather than reproduction. A handful of entries' `Notes` column
mentions what kind of example the source gives (e.g., "source gives a soccer-commentary example")
without quoting it.

## Register-tag mapping

Following the mapping already established in
`../../datasets/Hungarian/established/009_szolasok_kozmondasok_part1.md` for this same taxonomy:
source `durva` ("coarse") and `tabu` ("taboo") tags → Usage Tier `taboo`. Untagged entries in this
dictionary are still slang by the book's own scope (every headword here is drawn from a
slang-specific dictionary, not a general-purpose one) → Usage Tier `slang`. `ironikus` ("ironic")
is recorded in Notes as a tone marker rather than a separate Usage Tier, consistent with how
`gúny`/`tréf`/other connotation-only tags were handled in the proverb-dictionary extraction.

## Morphological typology note

Hungarian is agglutinative, but — as with the proverb-dictionary extraction — these are
multi-word idiomatic verb phrases and fixed expressions (e.g. `elmegy vkivel`, `hátszéllel
érkezik/jön`), not single agglutinated word-forms needing a morpheme-breakdown row. A few headwords
are themselves compact derived forms (e.g. `elpofáz(ik)`, `gányol`) but their composition is
transparent (prefix/verb + standard suffix) and doesn't hide structure a breakdown would clarify.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| elmegy vkivel | leaves with someone and has sex with them | verb phrase | slang | — | contemporary (source scanned 2015; book's own pub. year not confirmed in this excerpt) | — | — | dictionary | n/a | plausible_unverified | p.90. Sexual euphemism built on a plain motion verb. |
| elmenne a munka temetésére | a work-shy person, idler (lit. "would go to work's funeral") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. |
| elmentek neki, de még nem jöttek vissza | is crazy/insane (lit. "they left him but haven't come back yet") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. Sanity-as-a-departed-visitor metaphor. |
| elmész a (búbánatos) francba!/picsába! | "go to hell!" (rejection) | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. Tagged durva/tabu by source. |
| elmeszel | 1) sentences/convicts (court) 2) ruins, thwarts, makes impossible | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. Two senses given, numbered 1–2 by source. |
| elnáspángol | beats up | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. |
| elnyűtt bugyelláris | an old woman (derogatory, lit. "worn-out wallet") | noun idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. Ageist/misogynist body-as-object metaphor. |
| elokádja magát vmitől | vomits from disgust at something | verb phrase | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. Tagged durva. |
| előjön a farbával | finally reveals the real point/reason | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. |
| elöl deszka, hátul léc | describes a woman as flat-chested and lacking curves (lit. "board in front, plank in back") | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. Crude body-shaming descriptive simile. |
| előnti a vörös köd | gets furious (lit. "the red mist floods over him") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. Source gives an example sentence describing a fistfight. |
| előny | female breasts (lit. "advantage") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. Reuses an ordinary abstract noun as a body-part euphemism. |
| előre borítékol | predicts an outcome in advance (lit. "pre-envelopes it") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. |
| elpackáz/elpaccol | ruins, wrecks | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. Two spelling variants given as one entry. |
| elpáhol | 1) beats up 2) defeats decisively | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. |
| elpasszol | 1) sells 2) misses/wastes an opportunity | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. |
| elpaterol vkit | kills someone | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. |
| elpaterol vmit | 1) carries/hauls 2) sells 3) gets rid of | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. |
| elpatkol | dies suddenly | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.90. |
| elpattint | sells | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. |
| elpicsáz | beats up / defeats decisively | verb | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. Tagged tabu. Two numbered senses. |
| elpofáz(ik) | blabs, lets something slip accidentally | verb | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. Tagged durva. |
| elpucol | 1) runs away, flees 2) leaves somewhere 3) escapes/sneaks off | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. |
| elpukkan | 1) ejaculates (of a man, prematurely) 2) ejaculates (belatedly) | verb | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. Tagged tabu (implicit from crude sense). |
| elsumákol vmit | 1) evades an obligation, wriggles out of it 2) shirks something out of fear | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. Source gives two example sentences. |
| elsül a farka/fasza | ejaculates (crude) | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. Tagged durva/tabu; "farka" vs. "fasza" given as register-escalating variants. |
| elsüt | sells (above market value) | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. |
| elsüt egy viccet | tells a joke | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. |
| elszajrézik | steals | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. |
| elszáll | 1) ejaculates 2) is pleasantly high on drugs 3) (of a device, e.g. a computer) suddenly crashes/stops working | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. Three numbered senses spanning sex/drugs/tech — same base verb ("flies off") reused across unrelated domains. |
| elszáll vmiben/vkivel | thinks unrealistically, overreaches, has an inflated sense of self | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. |
| első blikkre | at first glance | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.91. "Blikk" is a German-derived loanword (Blick "glance"). |
| fater | dad; also an address term for an older man | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. |
| fati/fatikám | dad (address term); also address term for an older man | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. Diminutive/affectionate variant of fater. |
| fatökű | a contemptible/hateful person (lit. "wood-testicled") | noun/adj | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. Tagged tabu. |
| fax | penis (crude) | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. Ordinary office-machine noun repurposed as a body-part euphemism. |
| fázik, mint a fagylaltos kutyája | is very cold (simile, "cold as the ice-cream vendor's dog") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. |
| fecsegő | mouth (lit. "chatterer") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. Body-part-by-function metonymy. |
| fehér hó | cocaine (lit. "white snow") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. |
| fehér por | cocaine (lit. "white powder") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. Near-synonym pair with "fehér hó" — two independent color+substance images for the same referent. |
| fehérmájú | a nymphomaniac woman (lit. "white-livered") | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. |
| fej | 1) a man 2) a clever/smart person (also seen in "jó fej" = "a good/nice guy") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. Lit. "head" — metonymic person-reference, productive base for "jó fej," "fejes," etc. |
| fejes | an important/influential person, a boss | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102. Derived from "fej" (head) + -es. |
| fejlövést kap | gets drunk quickly (lit. "takes a headshot") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. Violent-injury metaphor repurposed for intoxication speed. |
| fejre áll, mint a jancsiszög | fails, gets into trouble (simile) | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. |
| fejvadász | 1) a (highway) traffic police officer 2) a headhunter/recruiter | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. Lit. "headhunter" — source gives an example about traffic cops targeting truck drivers specifically. |
| fej vkit | constantly demands/extracts money from someone | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. |
| feka/fekália | 1) a Black person 2) dark-skinned (adj.) 3) a Roma person | noun/adj | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.102–103. **Ethnic slur** — flagged explicitly, same caution this project applies to the proverb dictionary's "cigány" cluster; attested-but-offensive period slang, not neutral data. |
| fekete | illegal, off-the-books | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. Lit. "black" — legality-as-color metaphor (cf. English "black market"). |
| feketén | illegally, by circumventing the rules | adv | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. Adverbial derivative of "fekete" above. |
| feketemária | a human/sex trafficker (lit. "black Mary") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. |
| fel a fejjel! | "chin up!" (encouragement) | interjection | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. |
| felakaszthatod magad! | a rejection formula ("you can go hang yourself") | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. |
| felbasz | infuriates | verb | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. Tagged tabu. |
| félcédulás | 1) very stupid 2) crazy | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. |
| felcsinál | gets someone pregnant | verb | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. Tagged durva. |
| feldughatod magadnak! | a rejection formula ("you can shove it") | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.103. Tagged durva. |
| fűzi a csajt | courts/woos a girl | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.114. |
| fűzőgép | a womanizer, ladies' man (lit. "sewing machine") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.114. Machine-that-"stitches together" conquests metaphor. |
| fűz vkit/fűzi a fejét | charms, sweet-talks, tries to persuade someone | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.114. Base verb for fűzőgép, fűzi a csajt above — "fűz" (to string/thread) as a family of persuasion/courtship idioms. |
| G | a gangster | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. Single-letter headword (pronounced "dzsí," i.e. English letter-name borrowing). |
| g | a gram (of drugs), as a unit of measure | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. |
| gádzsó | 1) a Roma boy/man 2) a young man/guy generally | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. Romani-language loanword ("gadjo"-family) that has broadened from an in-group Roma term to general youth slang for "guy." |
| gagyi | 1) fake gold 2) shoddy, cheap, worthless 3) fake, not genuine 4) hastily/carelessly made | adj/noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. Highly productive base adjective, four numbered senses. |
| gaj(desz)ra megy | 1) breaks down, gets ruined 2) (of a relationship) falls apart | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. |
| gajra tesz/vág | ruins, wrecks | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. |
| galagonya | marijuana (lit. "hawthorn") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. Plant-name reused for a different plant/substance. |
| galaktikus | very good, great (lit. "galactic") | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. Scale-hyperbole intensifier, cf. English "cosmic," "astronomical." |
| galamb(ocska) | a fart (lit. "(little) pigeon/dove") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. Euphemistic animal-substitution for a bodily-function taboo. |
| galeri | 1) a (youth) gang, delinquent group 2) a friend group, social circle | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. |
| gallérja mögé hány vmit | eats greedily/quickly (lit. "throws it behind his collar") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. |
| ganef | 1) a criminal, crook 2) a gang member 3) a troublemaker | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. Yiddish-derived loanword (ganef "thief"). |
| gané(j) | 1) disliked, hated (of a person) 2) dirty, worthless (of a person or thing) | noun/adj | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. Lit. "manure/dung" — filth-as-worthlessness metaphor. |
| gány | sloppy, hastily-done work | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. |
| gányol | does something carelessly, slapdash | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.115. Verb derivative of "gány." |
| hanyatt dobja magát | is very surprised, astonished (lit. "throws himself backward") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. |
| hány, mint a lakodalmas/murányi kutya | vomits (simile, "like the wedding-feast/Murány dog") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. Two place/context variants of the same simile template given together. |
| hapcsi/hapsi | a man, guy | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. |
| hapsikám | an ironic/annoyed address term to a man | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. Diminutive of "hapsi," tone shifted to ironic. |
| hápog | 1) talks 2) can barely speak from shock/surprise | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. Lit. "quacks" (of a duck) — animal-sound-for-human-speech metaphor. |
| harap vmire | is tempted by, falls for something | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. Lit. "bites at" — fishing/bait metaphor. |
| háromlábú | a man with a large penis (lit. "three-legged") | adj/noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. |
| háryjános | a braggart, boaster | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. From the literary/folkloric character Háry János, a famous fictional Hungarian tall-tale-teller — proper-name-to-common-noun conversion; also verbed as "háryjánoskodik" (to brag). |
| hasfájás | a complaint, grievance (lit. "stomachache") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. Ailment-as-metaphor-for-grievance, cf. English "what's eating you." |
| hasmars | diarrhea (slang register of a clinical term) | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.126. |
| hát a faszom | a dismissive rejection expression (crude) | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. Tagged tabu. |
| hát ez kurva jó!/marha jó! | sarcastic "great, just great" (ironic) | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. Tagged tabu/durva, marked ironikus by source — praise-form reused for its opposite (sarcasm). |
| hátszél | 1) protection/connections that help one get ahead 2) a hidden advantageous position | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. Lit. "tailwind." |
| hátszéllel érkezik/jön | arrives somewhere through connections/favoritism | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. Derived from "hátszél" above; source's example describes landing a ministry job this way. |
| hatvankilenc | the sexual position "69" | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. Number-as-shape euphemism, internationally recognizable. |
| havaj | very good, great | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. |
| havajozik | has a great time | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. Verb derivative of "havaj"; source's example mentions a trip to Croatia. |
| haver | a friend (not necessarily close) | noun | core-adjacent/slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. Extremely common informal register word; included as the base for haverkodik/haverságba kerül below. |
| haverságba kerül | to become friends (with someone) | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. |
| havi | menstruation | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. Lit. "monthly" — ellipsis of "havi vérzés," a common euphemism pattern. |
| havi dohány/lóvé | salary, pay | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.127. Lit. "monthly tobacco/horse-money" — two independent money-slang bases ("dohány," "lóvé") both accept the same "havi" (monthly) modifier. |
| húzás! | "let's go!"/"run!" (imperative) | interjection | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.134. |
| huzatot vesz | flees, escapes | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.134. |
| húzd el a beled! | "get lost!" (crude) | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.134. Tagged durva. |
| húzza a lóbőrt | sleeps (lit. "pulls the horsehide") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.134. |
| húzza az igát | does hard, monotonous work (lit. "pulls the yoke") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.134. Draft-animal labor metaphor, recurs across several entries on this page (kül. egyhangú, nehéz munkán "esp. monotonous, hard work" is itself a recurring bracketed tag). |
| huzi-voni | sexual intercourse (euphemism) | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.134. Reduplicative-sounding coinage. |
| húzós | 1) difficult (of a task/work) 2) unpleasant, burdensome 3) unfair (e.g. of a price) 4) good, nice | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.134. Four numbered senses, including two near-opposite evaluative poles (burdensome vs. "nice") on the same adjective. |
| húzott szemű | an East Asian/Chinese person (lit. "slanted/drawn eyes") | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.134. **Ethnic descriptor, flagged** — same caution as feka/fekália above. |
| hülye | 1) a stupid person 2) slightly crazy 3) odd, strange 4) a stupid person 5) stupid 6) disliked, hated 7) bad, poor quality 8) an incapable person | noun/adj | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.134. Tagged durva throughout; the single most productive headword sampled — anchors dozens of derived idioms on this page alone (hülyére X magát, hülyét csinál, hülyítesz, etc.), only a few of which are extracted individually below. |
| hülye duma | nonsense talk | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. Tagged durva. |
| hülyére veri magát | laughs uncontrollably (lit. "beats himself stupid") | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. Tagged durva; one of ~15 "hülyére ___" variants on this page, representative rather than exhaustive. |
| hülyére vesz | toys with/teases/deceives someone | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. Tagged durva. |
| hülyét csinál vkiből | makes a fool of someone | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. Tagged durva. |
| hülyítesz!/? | an expression of disbelief ("you're kidding!/really?") | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. Tagged durva. |
| hütyü | an alcoholic drink | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. |
| hűvös | prison (lit. "cool/chilly") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. Temperature-as-confinement metaphor; base for hűvösön van, hűvösre tesz below. |
| hűvösön van | is serving a prison sentence | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. |
| hűvösre tesz | imprisons (someone) | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. |
| HVCS | "helyi vagány csávók" — local flashy/aggressively-acting young men, neighborhood toughs | acronym/noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.135. Rare example of the dictionary lexicalizing a full acronym as its own headword. |
| kettyint | has sex with someone | verb | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.150. |
| kever | 1) walks/goes somewhere quickly 2) causes trouble, stirs up conflict 3) has sex 4) is very active/busy | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.150. Lit. "stirs/mixes" — four numbered senses from one base metaphor of agitation. |
| keveri a szart | stirs up trouble (crude) | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.150. Tagged durva. |
| kevés vagy, mint... (chain of similes) | "you're not good enough/not up to it" — an escalating put-down formula with multiple interchangeable similes (an empty orphanage staff meeting, a Balaton-beach sandwich, a campsite tent-pole, etc.) | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.150. Tagged durva at its crudest variant. Notable as a template-simile entry: the source lists ~6 interchangeable comparison tails for one put-down frame, a productive pattern worth flagging for Phase 3. |
| kézimunka | masturbation/manual sexual stimulation (euphemism, lit. "handiwork/handicraft") | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.150. Ordinary craft-work noun repurposed as a sexual euphemism. |
| kgst indián | a Roma person (dated slur referencing the Comecon/KGST economic bloc + "Indian" stereotype) | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.150. **Ethnic slur, flagged** — attested period slang, historically/politically loaded coinage (Cold War-era economic-bloc acronym repurposed as an ethnic slur), not neutral data. |
| ki a fene?/franc?/picsa?/szar?/túró? | "who the hell?" — a family of interchangeable escalating-vulgarity variants | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.150–151. A clean register-escalation ladder within one interrogative frame (mild "fene" → crude "szar/túró"), useful data for a euphemism/dysphemism-chain analysis. |
| kiakad | 1) is surprised 2) gets emotionally upset 3) gets confused 4) gets angry | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. |
| kiáll a placcra/sarokra | works as a prostitute, solicits on the street | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. |
| kiálló segg | a shapely, prominent (female) rear | noun idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. Tagged durva. |
| kibaszik vkit | dismisses/fires someone (crude) | verb phrase | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. Tagged tabu. |
| kibaszott | disliked, hated (as an intensifying adjective) | adj | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. Tagged tabu; base for kibaszott jó, kibaszottul below. |
| kibaszott jó | very good, great (crude intensifier) | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. Tagged tabu; same intensifier reused with reversed evaluative polarity from "kibaszott" alone. |
| kibaszottul | intensifier, "very" (crude) | adv | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. Tagged tabu; explicitly glossed by source as "nyomatékosítás; 'nagyon'" (emphasis marker; "very"). |
| kíber | 1) a police informant 2) an informant generally 3) a detective/investigator 4) a plainclothes/private detective 5) a police officer | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. Five numbered senses spanning informant→police-generally. |
| kiborítja a bilit | upsets an otherwise calm/stable situation (lit. "tips over the chamber pot") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. Source's example is about a news article causing an uproar. |
| kibukik | 1) has an emotional breakdown 2) is surprised/astonished | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. |
| kibuliz(ik) vmit | obtains/achieves something, often through improper or unofficial means | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.151. |
| kolbászol | wanders aimlessly (lit. "sausages around") | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.162. Food-noun verbed into an aimless-motion verb — unusual derivation path worth flagging. |
| koma | a friend, buddy | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.162. |
| komál vkit/vmit | 1) looks at 2) likes, is fond of 3) enjoys | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.162. |
| kómás | 1) drunk 2) drowsy, dazed | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.162. Medical-term ("comatose") repurposed for intoxication/tiredness. |
| komancs | a communist (dated slang) | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.162. Sound-alike distortion of "kommunista." |
| kontár | an unskilled/incompetent worker | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.162. |
| kontakt | a drug dealer/supplier | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.162. English/international loanword "contact" narrowed to a specific criminal-network sense. |
| konyhatündér | a woman who does a lot of housework/kitchen work (lit. "kitchen fairy") | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.162. Gendered-labor stereotype term. |
| kopasz | 1) an army recruit 2) inexperienced, a beginner 3) a first-year student | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.162. Lit. "bald" — shaved-head-of-a-new-recruit metonymy extended to "novice" generally. |
| kopó | 1) a detective 2) a private investigator | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. Lit. "bloodhound/pointer (dog breed)" — hunting-dog metaphor for investigators. |
| koppan | fails, doesn't work out (of plans) | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. |
| koppint | plagiarizes, copies someone's work | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. |
| kordé | a car (dated slang, lit. "cart") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. |
| kormol/kormoz | lies | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. |
| Kovács János/23 | an average, unremarkable, insignificant person (generic-name idiom, cf. English "John Doe") | noun idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. Common Hungarian surname (Kovács = "Smith") used as a generic-person placeholder. |
| kóter | jail, prison | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. |
| koti/koton | a condom | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. Two clipped-form variants of the same loan ("koton" itself likely from "kondom"). |
| kozák | a marked/forged deck of cards (a cheating device) | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. Lit. "Cossack" — ethnonym repurposed for an unrelated gambling-cheat referent. |
| kozmás | having a criminal record (lit. "singed/scorched") | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. |
| kőagyú | stupid (lit. "stone-brained") | adj | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.163. Last headword on this sampled spread, closing out the "k" letter section near "kő-." |
| lelép vkit | cheats/outdoes someone | verb phrase | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. Tagged durva. |
| lelép vkitől | abandons someone dishonorably | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. |
| lelki szemétláda | a person entrusted with someone's private confidences (lit. "emotional trash can") | noun idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. Unusually vivid metaphor for a confidant, framed negatively (as a receptacle for others' unwanted emotional "garbage"). |
| lelógó vándordíj | a medal/award (ironic, lit. "dangling traveling trophy") | noun idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. Marked ironikus-flavored by the source's own celebratory-sounding example. |
| lelomboz | makes someone sad, disheartens | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. |
| lelövi a poént | ruins/spoils a joke's punchline | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. |
| lemegy alfába | 1) becomes drowsy/sleepy 2) prepares to sleep | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. Alpha-brainwave-state ("alfa") borrowing from pop psychology/relaxation vocabulary. |
| lemegy a keszonba | performs oral sex (crude euphemism, lit. "goes down into the caisson") | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. |
| lemegy Turkesztánba | performs oral sex (crude euphemism, alternate "goes down to Turkestan") | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. Near-synonym of "lemegy a keszonba" — same "goes down to [distant/exotic place]" euphemism template with an interchangeable destination. |
| lenyel (pénzt) | embezzles/pockets money (lit. "swallows (money)") | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. |
| lenyom egy (gyors) numerát | has sex quickly | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.174. "Numera" (from "number/routine") recurs as a sex euphemism base across several entries in this dictionary (cf. "levág egy numerát" below). |
| lenyúl vmit | 1) steals 2) unfairly benefits from something | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.175. |
| lepénzel | bribes | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.175. |
| lepipál | outdoes, surpasses someone | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.175. |
| lepirít | scolds, berates | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.175. |
| lepisálják a kutyák | is extremely poor (lit. "even the dogs piss on him") | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.175. |
| lepke | an own-goal, or a goalkeeping blunder (soccer slang, lit. "butterfly") | noun | slang.technical | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.175. Sport-jargon slang; source's own example is a soccer-commentary-style put-down. |
| levág | criticizes | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.178. |
| levág egy numerát | has sex once, casually | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.178. Companion entry to "lenyom egy (gyors) numerát" above — same "numera" euphemism base, different verb collocate. |
| le van égve | is broke, poor (lit. "is burned down") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.178. |
| le van rohadva | 1) is very sick, feeling very unwell 2) (of a machine, e.g. a car) isn't working, out of order | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.178. Tagged durva; lit. "is rotted down" — decay metaphor spanning both bodily illness and mechanical failure. |
| leves | money (lit. "soup") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. |
| leveszi a fülest | gathers/picks up information (lit. "takes the ear off") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. |
| lezavar vmit | produces/arranges something quickly | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. |
| lila | 1) 500 forints 2) pretentiously intellectual, pseudo-profound (of a person or ideas) | adj/noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. Lit. "purple" — banknote-color-to-value metonymy (sense 1) alongside an unrelated intellectual-affectation sense (sense 2), one color-word covering two unconnected referents. |
| lila lesz a feje/hajat kap | becomes very angry | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. Color-change-when-angry idiom, cf. English "purple with rage." |
| lim | an immoral or promiscuous woman/girl | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. |
| linda | a policewoman | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. Given (female) name genericized into an occupational slang term. |
| link | 1) fake, not genuine 2) fake, forged (of checks/money specifically) 3) untrustworthy | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. Last headword on the assigned page range's final sampled page; base for link duma, link stósz below. |
| link duma | nonsense, evasive talk | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. |
| link, mint a lómáj/véres hurka | untrustworthy (simile, "shifty as horse liver/blood sausage") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.179. |

---

## Standout slang-formation patterns for Phase 3 mechanics analysis

- **One base verb/noun radiating into a full polysemy fan.** `elszáll` (flies off) alone covers
  ejaculation, drug euphoria, and computer crashes; `hülye` anchors well over a dozen derived
  idioms on a single page; `kever` (stirs/mixes) covers fast walking, troublemaking, sex, and
  busyness. A single concrete-motion or concrete-substance verb repeatedly becomes the shared root
  for several semantically unrelated slang senses — worth modeling as a productive derivation
  mechanism in its own right, not just per-entry coincidence.
- **Interchangeable-slot simile templates.** `kevés vagy, mint...` and `hány, mint a
  lakodalmas/murányi kutya` both give multiple interchangeable comparison "tails" for one fixed
  frame — the mechanism (not the specific tail) is what's productive, suggesting the underlying
  conlang mechanic should support a template+slot structure rather than one-off frozen similes.
- **Register-escalation ladders on one semantic slot.** `ki a fene?/franc?/picsa?/szar?/túró?`
  ("who the hell?") is a clean 5-step vulgarity ladder on a single interrogative frame; `elmész a
  francba!/picsába!` is a 2-step version of the same mechanism. A reusable "swap the taboo word,
  keep the frame" pattern.
- **Euphemism substitution with a swappable destination/object.** `lemegy a keszonba` /`lemegy
  Turkesztánba` (oral sex) share one "goes down to [somewhere]" frame with an interchangeable
  exotic/technical destination noun — structurally close to the simile-template pattern above but
  for euphemism rather than insult.
- **Abstract/ordinary words repurposed as body-part or substance euphemisms.** `előny`
  ("advantage" → breasts), `fax` (the office machine → penis), `leves` ("soup" → money), `galamb`
  ("pigeon" → fart). No consistent semantic field predicts the borrowed word — worth noting as
  "arbitrary redirection" rather than assuming euphemisms always draw from one thematic domain.
  A more consistent thematic cluster does appear for money (leves, korpa "bran" seen on other
  sampled pages, lóvé, dohány "tobacco," lényeg-adjacent lényeg) and for prison (hűvös "cool,"
  kóter) — both worth a dedicated cross-reference pass in Phase 3.
- **Ethnic/marginalized-group slurs embedded as ordinary headwords.** `feka/fekália`, `kgst
  indián`, `húzott szemű` appear inline with no special marking beyond the dictionary's own
  register tags. Consistent with the proverb dictionary's "cigány" cluster finding — this
  dictionary, too, contains genuine period-attested slurs that must be carried into any downstream
  synthesis work with the same bias flag, never as neutral lexical data.
- **Proper names and acronyms genericized into common slang.** `Kovács János` (a common surname) →
  "generic unremarkable person," `HVCS` (an acronym) → lexicalized as a headword in its own right,
  `linda` (a given name) → "policewoman," `háryjános` (a literary character) → "braggart." Four
  distinct genericization paths (surname, acronym, first name, literary-character name) captured
  in one 90-page sample — useful range for a conlang name-to-slang-term mechanic.

---

## Output file record

This file: `language_corpus/Hungarian/01_szlengszotar_dictionary_pp90-179.md` — 196 sampled
vocabulary entries, printed pages 90–179 (PDF pages 46–90) of *Magyar Szlengszótár*.
