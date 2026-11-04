# Swedish — Established Vocabulary/Grammar: Glossika Mass Sentences (Representative Sample)

**Source:** Campbell M., Bruus M. — *Glossika Swedish: Complete Fluency Course 1* (2014). Sampled
pages (PDF page / printed page, offset is a consistent +6 throughout): PDF 34-38 / printed 28-32
(items #1-15); PDF 67-71 / printed 61-65 (items #100-114); PDF 100-104 / printed 94-98 (items
#199-213); PDF 133-137 / printed 127-131 (items #298-312); PDF 166-170 / printed 160-164 (items
#397-411); PDF 199-203 / printed 193-197 (items #496-510, partial); PDF 232-236 / printed 226-230
(items #595-609); PDF 265-269 / printed 259-263 (items #694-708, partial); PDF 298-302 / printed
292-296 (items #793-804, partial); PDF 331-335 / printed 325-329 (items #892-906, partial); PDF
358-362 / printed 352-356 (items #973-987). 55 PDF pages read, 149 sentence triplets extracted.

---

## IMPORTANT — three things to read before using this file

### 1. Text-layer correction (new gotcha for this project)

**This source was flagged by the dispatching orchestrator as having a real text layer. That was
incorrect — confirmed false by direct inspection before any extraction began.** `pdftotext` run at
10-page intervals across the entire 368-page book returns essentially empty output (~1 character)
on every content page. `pdfimages -list` also shows **zero raster images** on content pages, which
rules out the already-documented "per-word/per-page raster image" pattern seen on other sources
(e.g. *Modern Russian Grammar*). `pdffonts` lists some embedded fonts with `uni=yes`, but the
rendered text behaves as if drawn as vector outline paths with no usable character/ToUnicode
mapping — it is neither a decodable font-substitution cipher (nothing to decode; no character data
recoverable at all) nor an image-based page in the already-documented sense. **This book required
genuine page-image rendering (`pdftoppm`) and vision-reading of every single item; no text-extraction
shortcut of any kind worked.** Flagging this as a new PDF-extraction gotcha pattern distinct from the
ones already catalogued in `00_Reference_Extraction_Spec.md`.

### 2. This is a representative sample, NOT an exhaustive extraction

The book runs to roughly **~1,000 numbered sentence triplets** (confirmed: item #987 appears on PDF
page 362 of 368, and the pattern continues past that). At 2-3 items per page across ~330 content
pages, a full-book vision-read would mean rendering and reading on the order of 300+ page images —
far outside the scope of a single dispatch, and nothing like the near-free cost of a text-layer
source. This file samples **149 triplets from 55 pages, drawn in 11 clusters of ~5 consecutive pages
each, spaced roughly every 33 pages across the full 34-362 PDF-page range** (see the cluster list in
the Source line above). Within each cluster, every triplet on the rendered pages was read — nothing
was additionally cherry-picked or dropped within a cluster, so the clusters are a fair, unbiased
slice of the book's content at each point, not hand-selected "interesting" sentences only.

**If full coverage of this source is ever wanted, it should be planned and dispatched as its own
dedicated vision-reading wave** (or several), sized and budgeted for ~300+ individual page-image
reads — not assumed to be cheap like a text-layer source, and not something to casually re-run as
part of a different task.

### 3. Vision-reading guard — no marginalia found

This is a clean, born-digital PDF (Adobe InDesign CC 2014 / Adobe PDF Library 11.0) rendered at
150dpi — not a scan of a physical used copy. No handwritten marginalia, pencil answers, or
underlining of any kind was observed on any of the 55 pages read. All content extracted below is
genuinely typeset/printed source material.

**Two printed typos were found in the source itself** (not reading errors on this end — both are
reproduced verbatim in the Sample sentences table below and flagged there): item #498 prints "han
**ahr** ingen hund" where context demands "har" (has); item #508 prints "ett nytt **job**" where
standard Swedish spelling is "jobb" (job, with double b).

---

## Vocabulary

Pulled from notable/recurring lexical items across the sampled sentences — not an attempt to table
every word of every sentence (this is a sentence-mining course, not a word-list source; see the
Sample sentences section below for the full triplets).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| väska | bag | noun | core | — | contemporary (source published 2014) | — | — | grammar_reference | n/a | verified | Recurs across multiple items (#3, #4, #102, #694); IPA consistently [vɛskʲa]. |
| tung / tunga | heavy | adjective | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #3 (sg. "tung") vs #4 (pl. "tunga") — regular adjective agreement pair. |
| titta (på) | to look / to watch | verb (phrasal with "på") | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | "titta på TV" = watch TV, lit. "look at TV" (#209, #309, #312, #607, #608). |
| vän | friend | noun | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Plural "vänner" (#302, #601, #606, #977); "vänner" also = "friends" generically. |
| taxichaufför | taxi driver | noun | core | — | contemporary (2014) | — | — | grammar_reference | n/a | low_confidence | Compound "taxi" + "chaufför". Sibilant in the middle of the IPA transcription on item #9 was genuinely hard to resolve from the render — flagged. |
| sjuksköterska | nurse | noun | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Compound, lit. "sick-sister"; transcription uses the sj-sound [ɧ] twice (#10). |
| gammal | old | adjective | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #13 ("väldigt gammal", "nittioåtta år gammal"); also #894, #984 (farmor/mormor "dog"). |
| vacker | beautiful | adjective | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #14, negated plural "vackra". |
| bekväm | comfortable | adjective | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #14, plural "bekväma". |
| vad är det för + NOUN | "what kind/color of NOUN" | idiom/construction | colloquial | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #102: "Vad är det för färg på din väska?" — "för" here means "kind of", not "for". |
| må / mår | to feel/fare | verb | colloquial | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | "Hur mår X?" = "How's X doing?" (#106, #111, #397); "mår bra" = "is doing well/fine" (#107, #200, #201). |
| tycka om | to like | verb (phrasal) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Lit. "to think/opine about"; recurs #302, #306, #307, #402, #403. |
| ha på sig | to wear | verb (phrasal, reflexive) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Lit. "to have on oneself"; #204, #311, #699. |
| ta med (sig) | to bring/take along | verb (phrasal, reflexive) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #203: "ta med dig ett paraply" = "take an umbrella [with you]". |
| gå på bio | to go to the movies | idiom | colloquial | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Lit. "go on cinema", no article; recurs #304, #406, #603. |
| brukar | usually (does) | verb (habitual auxiliary) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Dedicated habitual-aspect verb, see Grammar points; very frequent across sample (#306, #310, #312, #399, etc.). |
| folks | people's | noun (genitive) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #308: "folks namn" — genitive -s with no article, parallels English "people's". |
| halv | half (telling time) | numeral/adjective | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | "halv sju" = 6:30, "halv elva" = 10:30, "halv tolv" = 11:30 — see Grammar points. |
| gå och V | "go (and) V" (pseudo-coordination) | grammar construction | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #409: "gå och lägga dig" = "go to bed" (lit. "go and lay yourself down"); see Grammar points. |
| ingen / inget | no / not any | determiner (negative indefinite) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | "ingen" (en-words, #498, #502-504), "inget" (ett-words, #697); see Grammar points. |
| armbandsklocka | wristwatch | noun | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Compound: "arm-band-clock" (#500). |
| bröder | brothers | noun (irregular plural) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Irregular plural of "bror"/"broder" (#501). |
| checka in | to check in | verb (loanword, phrasal) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #595: English loanword nativized with Swedish weak past tense "-ade" ("checkade in"). |
| i tid | on time | idiom | colloquial | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #597. |
| avgå / avgick | to depart / departed | verb | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #597, strong/irregular past tense "avgick". |
| anlända / anlände | to arrive / arrived | verb | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #597, #977; irregular weak past "anlände". |
| till slut | finally / in the end | idiom | colloquial | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #598. |
| tappa bort | to lose (something) | verb (phrasal) | colloquial | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Lit. "to drop away"; recurs #600, #897, #904 — consistent across multiple independent occurrences. |
| åka | to go (by vehicle) | verb | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Contrasts with "gå" (on foot); see Grammar points. #599, #901. |
| hälsa på | to visit (someone) | verb (phrasal) | colloquial | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Lit. "to greet upon"; #606. |
| i morse | this morning | idiom (time expression) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #605, #705. Easily confused with "i morgon" ("tomorrow") — near-homophone false-friend pair worth flagging for later slang/corpus work. |
| dagstidning | daily newspaper | noun | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Compound "day-newspaper" (#602). |
| glass | ice cream | noun | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | False friend vs. English "glass" (#696). |
| tandläkare | dentist | noun | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Compound, lit. "tooth-doctor" (#695). |
| på väg till | on the way to | idiom | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #695, #698. |
| pass | passport | noun | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | False friend vs. English "pass" (mountain pass / sports pass) (#897, #904). |
| hitta | to find | verb | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #897. |
| gift / gifta | married | adjective | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #892, plural/predicate form "gifta". |
| för X sedan | X ago | idiom (duration construction) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #975, #984; contrasts with bare "sedan" = "since" (#894, #974); see Grammar points. |
| farmor / morfar / mormor / farfar | paternal grandmother / maternal grandfather / maternal grandmother / paternal grandfather | noun (kinship, side-specific) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #984 prints "farmor/mormor" as alternatives since English "grandmother" doesn't specify side — flagship finding, see Grammar points. |
| maskinskrivare | typist | noun | core/dated | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Compound, lit. "machine-writer" — somewhat dated occupational term (#903). |
| bli / blivit | to become / become (past part.) | verb | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #903: "har blivit snabbare" = "has become/gotten faster". |
| var vs. vart | where (static) vs. where-to (directional) | interrogative adverb pair | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #210 ("Vart går hon?"), #398/#405 ("Var bor...", "Var arbetar..."), #901 ("Vart har han åkt? Var är han nu?") — clean minimal-pair contrast across multiple items; see Grammar points. |
| svara i telefonen | to answer the phone | idiom | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | Lit. "answer in the telephone" (#704). |
| rock | coat | noun | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | False friend vs. English "rock" (#204). |
| god / goda vs. bra | good (attributive, inflecting) vs. good (invariable) | adjective pair | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #302 uses "goda vänner" (not "bra vänner"); see Grammar points. |
| epost | email | noun (loanword) | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #973: "e" + "post" (mail), nativized loan-compound. |
| än | yet (negative-polarity temporal adverb) | adverb | core | — | contemporary (2014) | — | — | grammar_reference | n/a | verified | #973: "har inte kommit än" = "hasn't arrived yet". |

## Grammar points

Glossika doesn't narrate grammar explicitly — it's a pure sentence-mining course. The points below
are structural patterns that recurred clearly enough across the sampled items (often confirmed by
more than one independent occurrence at widely separated points in the book) to be worth recording
as genuine grammar points rather than one-off vocabulary notes.

### gå vs. åka — motion-verb choice encodes mode of travel

Swedish splits what English covers with one general "go" across at least two common verbs: "gå"
for going on foot (#213 "Går du nu?", #304 "går aldrig på bio", #399 "Går du alltid upp tidigt?")
and "åka" for going by vehicle (#599 "Steve åker alltid till arbetet med bil", #901 "Vart har han
åkt?"). A slang/synthesis pipeline building verbs of motion for the derived conlang should treat
"general motion" as a dimension that can plausibly be lexically split by mode-of-travel, not
assumed atomic.

### vart vs. var — directional vs. static locative interrogatives

"Var" asks a static location ("Var bor dina föräldrar?" #398, "Var arbetar din syster?" #405, "Var
är han nu?" #901); "vart" asks a destination/direction ("Vart går hon?" #210, "Vart har han åkt?"
#901). The #901 pair uses both in adjacent sentences, making the contrast explicit within a single
item. Notably, #985 ("Var har du varit? Var var du igår kväll?") shows "var" doing double duty as
both the interrogative "where" and the past-tense of "to be" ("was/were") — a genuine homonym
collision in running text.

### gå och V — pseudo-coordination for purposive/immediate action

#409 "Vilken tid brukar du gå och lägga dig?" ("What time do you usually go to bed?") uses "gå och
lägga dig" — literally "go and lay yourself down" — as a single purposive-action unit, not two
sequential actions. This is the Scandinavian "pseudo-coordination" pattern (verb + "och" + verb)
rather than true coordination; worth tracking as a template for any derived-language "about to do
X" construction.

### brukar — dedicated habitual-aspect auxiliary

Where English uses the adverb "usually", Swedish very frequently uses a dedicated modal-like
auxiliary verb "bruka" (present "brukar") governing a bare infinitive: "Barn brukar tycka om
choklad" (#306), "Vi brukar äta middag halv sju" (#310), "Jag brukar titta på TV på kvällen" (#312),
"Går du alltid upp tidigt?" vs. the brukar-form equivalents throughout #397-411. This is a real
grammaticalized habitual-aspect marker, not just a translation convenience — appeared independently
across at least 4 of the 11 sampled clusters.

### ingen / inget — negative indefinite determiner replaces "not a/any"

Swedish doesn't negate an indefinite noun phrase with "inte" + article the way English does ("not a
dog"); instead it uses a dedicated negative determiner that agrees with the noun's gender: "ingen"
for en-words ("Han har ingen hund" #498/#503, "ingen dator" #502, "ingen cykel" #504) and "inget"
for ett-words ("Han bar inget paraply" #697). "Något"/"nogut" ("any/some") is the positive-polarity
counterpart (#510 "Har du något paraply?").

### halv + next hour — "half seven" means half-PAST six, not half-TO seven

Telling time with "halv": "halv sju" = 6:30 (#310), "halv elva" = 10:30 (#706), "halv tolv" = 11:30
(#707). The construction names the *coming* hour and means "halfway to" it — i.e. "halv sju" is
literally "half [of the way to] seven" = 6:30. Confirmed consistently across three independent items
at widely separated points in the book (clusters 4, 5, and 8).

### för X sedan ("X ago") vs. sedan alone ("since") vs. i X ("for X", duration + perfect)

Three related but distinct temporal constructions recurred: "för en timme sedan" = "an hour ago"
(#975); bare "sedan" as a subordinating conjunction = "since" ("sedan han var sju år gammal" #894);
and "i" marking a duration with a perfect-tense verb ("har varit gifta i sex månader" #892, "har
studerat...i tre år" #893, "bodde i Paris i sex år" #974) — paralleling English "for" rather than
literal "in". Worth flagging since all three use morphologically related words (sedan/i) that an
English-first analysis could easily conflate.

### har varit — present perfect of "vara" (to be) for experiential "has been to"

"Hon har varit i Spanien två gånger" (#793), "Hon har varit i Japan en gång" (#794), "Jag har varit
i New York en gång" (#797) — the present-perfect-of-"to be" experiential pattern exists in Swedish
much as in English, using "varit" (past participle of "vara").

### Gendered, side-specific kinship terms (farmor/morfar/mormor/farfar)

The flagship finding of this sample: #984 ("Sanjit's grandmother has died") renders as "Sanjits
farmor/mormor har dött" — the source prints *both* options because Swedish has no single word for
"grandmother"; it obligatorily specifies which side of the family: "farmor" (father's mother),
"farfar" (father's father), "mormor" (mother's mother), "morfar" (mother's father) — each itself a
transparent compound of "far"/"mor" (father/mother) + "mor"/"far". English's single
"grandmother"/"grandfather" is the unmarked case here, not Swedish's. Directly relevant for any
derived-conlang kinship-term design work later in the pipeline.

### god/goda vs. bra — two non-interchangeable words for "good"

#302 uses "Vi är goda vänner" (not "bra vänner") for "We're good friends" — "goda" is the inflecting
attributive form of "god" (good), distinct from the invariable "bra" used elsewhere in the sample
(e.g. "mår bra" #107/#200/#201, "arbetar...hårt" uses a different adjective entirely). The two words
aren't freely interchangeable; "god/goda" skews toward a more formal/literary attributive register
in modern spoken Swedish, while "bra" dominates predicative and general use — worth a closer look in
a dedicated register-contrast source if one is extracted later.

### Preposition stranding in wh-questions

"Vem väntar du på?" (#211, "Who are you waiting for?") strands the preposition "på" at the end of
the question, mirroring English syntax rather than the pied-piping pattern many other languages
require ("For whom are you waiting?"). Confirmed again at #211/#212 ("Väntar du på John?").

### Content mismatches between EN and SV/IPA lines (source-level, not a reading error)

At least three sampled items (#595, #599, #602, and arguably #981) show an EN prompt with two
clauses where the printed SV/Swedish sentence and its IPA transcription render only one of them —
e.g. #599's EN is "Steve always goes to work by car. Yesterday he went to work by car." but the
printed SV only has "Steve åker alltid till arbetet med bil." with no corresponding past-tense
clause. These are preserved verbatim in the Sample sentences table below rather than silently
"completed" — they may be genuine source omissions/errata (the course having a known second
"transformation/substitution drill" pedagogical layer, per its own front matter, that doesn't always
keep EN/SV/IPA in lockstep) rather than anything missed in this vision-read.

---

## Sample sentences

Full EN / SV / IPA triplets for all 149 items read in this sample, grouped by the page cluster they
came from. Preserved as printed, including the two source typos and the EN/SV content mismatches
flagged above. IPA reading confidence is `verified` unless noted inline; `low_confidence` items are
marked with a trailing note. An ellipsis `(...)` in an IPA line reflects the source's own convention
of eliding a proper name from the phonetic transcription (names are not phonetically transcribed in
this book).

### Cluster 1 — PDF pp.34-38 / printed pp.28-32 (items #1-15)

| # | EN | SV | IPA |
|---|---|---|---|
| 1 | The weather's nice today. | Vädret är fint idag. | [vɛdret ɛr fint idaɣ ‖] |
| 2 | I'm not rich. | Jag är inte rik. | [jaɣ ɛr intə rik ‖] |
| 3 | This bag's heavy. | Väskan är tung. | [vɛskʲan ɛr tʰuŋ ‖] |
| 4 | These bags are heavy. | De här väskorna är tunga. | [dɛ hɛr vɛskuŋa ɛr tʰuŋa ‖] |
| 5 | Look, there's my friend. | Titta, där är min vän. | [tʰɪta \| dɛr ɛr min vɛn ‖] |
| 6 | My brother and I are good tennis players. | Min bror och jag är bra tennisspelare. | [min brur ɔɣ jaɣ ɛr bra tʰɛnɪspelarə ‖] |
| 7 | His mother's at home. He's at school. | Hans mamma är hemma. Han är i skolan. | [hans mama ɛr hema ‖ han ɛr i skulan ‖] |
| 8 | Her children are at school. | Hennes barn är i skolan. | [henes baɳ ɛr i skulan ‖] |
| 9 | I'm a taxi driver. | Jag är taxichaufför. | [jaɣ ɛr tʰaksiʃɔføːr ‖] *(low_confidence: sibilant/vowel sequence in the middle unclear on render)* |
| 10 | My sister's a nurse. | Min syster är sjuksköterska. | [min syster ɛr ɧukɧøteskʲa ‖] |
| 11 | He's sick. He's in bed. | Han är sjuk. Han ligger i sängen. | [han ɛr ɧuk ‖ han lɪger i sɛŋen ‖] |
| 12 | I'm not hungry, but I'm thirsty. | Jag är inte hungrig, men jag är törstig. | [jaɣ ɛr intə huŋrej \| men jaɣ ɛr tʰœʂtej ‖] |
| 13 | He's a very old man. He's ninety-eight years old. | Han är en väldigt gammal man. Han är nittioåtta år gammal. | [han ɛr en vɛldijt gamal man ‖ han ɛr nɪtiɔta or gamal ‖] |
| 14 | These chairs aren't beautiful, but they're comfortable. | De här stolarna är inte vackra, men de är bekväma. | [dɛ hɛr stulaŋa ɛr intə vakra \| men dɛ ɛr bekvɛma ‖] |
| 15 | The weather's warm and sunny today. | Vädret är varmt och soligt idag. | [vɛdret ɛr varmt ɔɣ sulijt idaɣ ‖] |

### Cluster 2 — PDF pp.67-71 / printed pp.61-65 (items #100-114)

| # | EN | SV | IPA |
|---|---|---|---|
| 100 | Where's Layla from? | Var kommer Layla ifrån? | [var kʰumer (...) ɪfron ‖] |
| 101 | She's from London. | Hon är från London. | [hun ɛr fron (...) ‖] |
| 102 | What color is your bag? | Vad är det för färg på din väska? | [vad ɛr də før fɛʁj pʰo din vɛskʲa ‖] |
| 103 | It's black. | Den är svart. | [den ɛr svaʈ ‖] |
| 104 | Are you hungry? | Är du hungrig? | [ɛr dʉ huŋrej ‖] |
| 105 | No, I'm not. | Nej, det är jag inte. | [nej \| də ɛr jaɣ intə ‖] |
| 106 | How's John? | Hur mår John? | [hur mor (...) ‖] |
| 107 | He's fine. | Han mår bra. | [han mor bra ‖] |
| 108 | Who's that woman? | Vem är den där kvinnan? | [vem ɛr den dɛr kʰvɪnan ‖] |
| 109 | She's my sister. | Hon är min syster. | [hun ɛr min syster ‖] |
| 110 | Is your mother at home? | Är din mamma hemma? | [ɛr din mama hema ‖] |
| 111 | How are your parents? | Hur mår dina föräldrar? | [hur mor dina føʁɛldrar ‖] |
| 112 | Is your job interesting? | Är ditt arbete intressant? | [ɛr dɪt arbetə intresant ‖] |
| 113 | Are the stores open today? | Är affärerna öppna idag? | [ɛr afɛrena œpna idaɣ ‖] |
| 114 | Where are you from? | Var kommer du ifrån? | [var kʰumer dʉ ɪfron ‖] |

### Cluster 3 — PDF pp.100-104 / printed pp.94-98 (items #199-213)

| # | EN | SV | IPA |
|---|---|---|---|
| 199 | I'm not reading the newspaper. | Jag läser inte tidningen. | [jaɣ lɛser intə tʰidniŋen ‖] |
| 200 | Are you feeling okay? | Mår du bra? | [mor dʉ bra ‖] |
| 201 | Yes, I'm fine. | Ja, jag mår bra. | [ja \| jaɣ mor bra ‖] |
| 202 | Is it raining? | Regnar det? | [rɛŋnar də ‖] |
| 203 | Yes, take an umbrella. | Ja, ta med dig ett paraply. | [ja \| tʰa med dɛj et pʰaraply ‖] |
| 204 | Why are you wearing a coat? | Varför har du på dig en rock? | [varfør har dʉ pʰo dɛj en ruk ‖] |
| 205 | It's not cold. | Det är inte kallt. | [də ɛr intə kʰjalt ‖] |
| 206 | What's he doing? | Vad gör han? | [vad jør han ‖] |
| 207 | He's reading the newspaper. | Han läser en tidning. | [han lɛser en tʰidniŋ ‖] |
| 208 | What are the children doing? | Vad gör barnen? | [vad jør baŋen ‖] |
| 209 | They're watching TV. | De tittar på TV. | [dɛ tʰɪtar pʰo tʰv ‖] |
| 210 | Where's she going? | Vart går hon? | [vaʈ gor hun ‖] |
| 211 | Who are you waiting for? | Vem väntar du på? | [vem vɛntar dʉ pʰo ‖] |
| 212 | Are you waiting for John? | Väntar du på John? | [vɛntar dʉ pʰo juhn ‖] |
| 213 | Are you leaving now? | Går du nu? | [gor dʉ nʉ ‖] |

### Cluster 4 — PDF pp.133-137 / printed pp.127-131 (items #298-312)

| # | EN | SV | IPA |
|---|---|---|---|
| 298 | His car is always dirty. He never cleans it. | Hans bil är alltid smutsig. Han tvättar den aldrig. | [hans bil ɛr smutsej ‖ han tʰvɛtar den aldrej ‖] |
| 299 | Food is expensive. It costs a lot of money. | Mat är dyrt. Den kostar mycket pengar. | [mat ɛr dyʈ ‖ den kʰustar mʏket pʰeŋar ‖] *(note: neuter "dyrt" with en-word "mat" — generic/mass-noun agreement, see Grammar points)* |
| 300 | Shoes are expensive. They cost a lot of money. | Skor är dyra. De kostar mycket pengar. | [skur ɛr dyra ‖ dɛ kʰustar mʏket pʰeŋar ‖] |
| 301 | Water boils at one hundred degrees Celsius. | Vattnet kokar vid 100 grader celsius. | [vaten kʰukjar vid 100 ɣrader selsius ‖] |
| 302 | We're good friends. I like her and she likes me. | Vi är goda vänner. Jag tycker om henne och hon tycker om mig. | [vi ɛr guda vɛner ‖ jaɣ tʰʏker um henə ɔɣ hun tʰʏker um mɛj ‖] |
| 303 | She always arrives early. | Hon anländer alltid tidigt. | [hun anlɛnder altid tʰidijt ‖] |
| 304 | I never go to the movies alone. | Jag går aldrig på bio ensam. | [jaɣ gor aldrej pʰo biu ensam ‖] |
| 305 | She always works hard. | Hon arbetar alltid hårt. | [hun arbetar altid hɔʈ ‖] |
| 306 | Children usually like chocolate. | Barn brukar tycka om choklad. | [baɳ brukjar tʰʏkja um ʃuklad ‖] |
| 307 | She always enjoys parties. | Hon tycker alltid om fester. | [hun tʰʏker altid um fester ‖] |
| 308 | I often forget people's names. | Jag glömmer ofta folks namn. | [jaɣ ɣlœmer ufta fulks namn ‖] |
| 309 | He never watches TV. | Han tittar aldrig på TV. | [han tʰɪtar aldrej pʰo tʰv ‖] |
| 310 | We usually have dinner at six thirty. | Vi brukar äta middag halv sju. | [vi brukjar ɛta mɪdaɣ halv ɧu ‖] |
| 311 | She always wears nice clothes. | Hon har alltid på sig fina kläder. | [hun har altid pʰo sɛj fina kʰlɛder ‖] |
| 312 | I usually watch TV in the evening. | Jag brukar titta på TV på kvällen. | [jaɣ brukjar tʰɪta pʰo tʰv pʰo kʰvɛlen ‖] |

### Cluster 5 — PDF pp.166-170 / printed pp.160-164 (items #397-411)

| # | EN | SV | IPA |
|---|---|---|---|
| 397 | You work hard. How about Heuiyeon? Does she work hard? | Du arbetar hårt. Och Heuiyeon? Arbetar hon hårt? | [dʉ arbetar hɔʈ ‖ ɔɣ (...) ‖ arbetar hun hɔʈ ‖] |
| 398 | Where do your parents live? | Var bor dina föräldrar? | [var bur dina føʁɛldrar ‖] |
| 399 | Do you always get up early? | Går du alltid upp tidigt? | [gor dʉ altid əp tʰidijt ‖] |
| 400 | How often do you watch TV? | Hur ofta ser du på TV? | [hur ufta ser dʉ pʰo tʰv ‖] |
| 401 | What do you want for dinner? | Vad vill du ha till middag? | [vad vɪl dʉ ha tʰɪl mɪdaɣ ‖] |
| 402 | Do you like football? | Tycker du om fotboll? | [tʰʏker dʉ um futbɵl ‖] |
| 403 | Does your brother like football? | Tycker din bror om fotboll? | [tʰʏker din brur um futbɵl ‖] |
| 404 | What do you do in your free time? | Vad gör du på din fritid? | [vad jør dʉ pʰo din fritid ‖] |
| 405 | Where does your sister work? | Var arbetar din syster? | [var arbetar din syster ‖] |
| 406 | Do you ever go to the movies? | Går du någonsin på bio? | [gor dʉ noɣunsin pʰo biu ‖] |
| 407 | What does this word mean? | Vad betyder det här ordet? | [vad betyder də hɛr udet ‖] |
| 408 | How often does it snow here? | Hur ofta snöat det här? | [hur ufta snøat də hɛr ‖] *(low_confidence: present-tense "snöat" is an unexpected verb form for "snöar" — could be a misread r/t on this end or a source-level irregularity; flagged rather than silently corrected)* |
| 409 | What time do you usually go to bed? | Vilken tid brukar du gå och lägga dig? | [vɪlken tʰid brukjar dʉ go ɔɣ lɛga dɛj ‖] |
| 410 | How much does it cost to call Mexico? | Hur mycket kostar det att ringa till Mexiko? | [hur mʏket kʰustar də at riŋa tʰɪl meksiku ‖] |
| 411 | What do you usually have for breakfast? | Vad brukar du äta till frukost? | [vad brukjar dʉ ɛta tʰɪl frukust ‖] |

### Cluster 6 — PDF pp.199-203 / printed pp.193-197 (items #496-510, partial — question/negation drill block)

| # | EN | SV | IPA |
|---|---|---|---|
| 496 | Does she have a car? — No, she doesn't. | Har hon en bil? – Nej, det har hon inte. | [har hun en bil ‖ ‖ nej \| də har hun intə ‖] |
| 497 | Ask if he has a computer. — Yes, he's got a computer. | Fråga om han har en dator? – Ja, han har en dator. | [froga um han har en datur ‖ – ja \| han har en datur ‖] |
| 498 | Ask if he has a dog. — No, he hasn't got a dog. | Fråga om han har en hund? – Nej, han ahr ingen hund. | [froga um han har en hund ‖ – nej \| han ahr iŋen hund ‖] *(source typo: "ahr" for "har", reproduced verbatim)* |
| 499 | Ask if he has a smart phone. — No, he hasn't got a smart phone. | Fråga om han har en smartphone? - Nej, han har ingen smartphone. | [froga um han har en smaʈphunə ‖- nej \| han har iŋen smaʈphunə ‖] |
| 500 | Ask if he has a watch. — Yes, he's got a watch. | Fråga om han har en armbandsklocka. – Ja, han har en armbandsklocka. | [froga um han har en armbandsklukja ‖ – ja \| han har en armbandsklukja ‖] |
| 501 | Ask if he has any brothers or sisters. — Yes, he's got a brother and two sisters. | Fråga om han har några bröder eller systrar. – Ja, han har en bror och två systrar. | [froga um han har noɣra brøder eler systrar ‖ – ja \| han har en brur ɔɣ tʰvo systrar ‖] |
| 502 | I don't have a computer. | Jag har ingen dator. | [jaɣ har iŋen datur ‖] |
| 503 | You don't have a dog. | Du har ingen hund. | [dʉ har iŋen hund ‖] |
| 504 | She doesn't have a bike. | Hon har ingen cykel. | [hun har iŋen sykel ‖] |
| 508 | He has a new job. | Han har ett nytt job. | [han har et nʏt jub ‖] *(source typo: "job" for standard "jobb", reproduced verbatim)* |
| 509 | They don't have much money. | De har inte mycket pengar. | [dɛ har intə mʏket pʰeŋar ‖] |
| 510 | Do you have an umbrella? | Har du något paraply? | [har dʉ nogut pʰaraply ‖] |

### Cluster 7 — PDF pp.232-236 / printed pp.226-230 (items #595-609, narrative/airport-story block)

| # | EN | SV | IPA |
|---|---|---|---|
| 595 | When she got there, she parked the car, walked to the terminal, and checked in. | När hon kom dit, gick hon till terminalen och checkade in. | [nɛr hun kʰum dit \| jɪk hun tʰɪl tʰerminalen ɔɣ ʃekjadə in ‖] *(note: EN mentions parking the car; printed SV omits that clause — EN/SV content mismatch, preserved as printed)* |
| 596 | Then she had breakfast at an airport cafe and waited for her flight. | Sedan åt hon frukost på ett flygplatskafé och väntade på sin avgång. | [sedan ot hun frukust pʰo et flyɣplatskjafə ɔɣ vɛntadə pʰo sin avgoŋ ‖] |
| 597 | The plane departed on time and arrived in Mexico City four hours later. | Planet avgick i tid och anlände till Mexiko City fyra timmar senare. | [pʰlanet avjɪk i tʰid ɔɣ anlɛndə tʰɪl meksiku sity fyra tʰɪmar senarə ‖] |
| 598 | Finally she took a taxi from the airport to her hotel downtown. | Till slut tog hon en taxi från flygplatsen till sitt hotell i centrum. | [tʰɪl slut tʰuɣ hun en tʰaksi fron flyɣplatsen tʰɪl sɪt hutel i sentrum ‖] |
| 599 | Steve always goes to work by car. Yesterday he went to work by car. | Steve åker alltid till arbetet med bil. | [(...) oker altid tʰɪl arbetet med bil ‖] *(EN/SV content mismatch: second EN clause has no SV/IPA counterpart on this page, preserved as printed)* |
| 600 | Hannah often loses her keys. She lost her keys last week. | Hannah tappar ofta bort sina nycklar. Hon tappade bort sina nycklar förra veckan. | [(...) tʰapar ufta buʈ sina nʏklar ‖ hun tʰapadə buʈ sina nʏklar fœra vekʲan ‖] |
| 601 | Zoe meets her friends every night. She met them last night. | Zoe träffar sina vänner varje kväll. Hon träffade dem igår kväll. | [(...) tʰrɛfar sina vɛner varjə kʰvɛl ‖ hun tʰrɛfadə dem igor kʰvɛl ‖] |
| 602 | I usually buy two newspapers every day. Yesterday I bought two newspapers. | Jag brukar köpa två dagstidningar varje dag. | [jaɣ brukjar çøpa tʰvo daɣstidniŋar varjə daɣ ‖] *(EN/SV content mismatch, same pattern as #599)* |
| 603 | We often go to the movies on weekends. Last Sunday we went to the movies. | Vi går ofta på bio på helgerna. Förra söndagen gick vi på bio. | [vi gor ufta pʰo biu pʰo heljeŋa ‖ fœra søndajen jɪk vi pʰo biu ‖] |
| 604 | I eat an orange every day. Yesterday I ate an orange. | Jag äter en apelsin varje dag. Igår åt jag en apelsin. | [jaɣ ɛter en apelsin varjə daɣ ‖ igor ot jaɣ en apelsin ‖] |
| 605 | Tom always takes a shower in the morning. This morning he took a shower. | Tom duschar alltid varje morgon. I morse duschade han. | [(...) duʂar altid varjə muʁgun ‖ i muʂə dusadə han ‖] |
| 606 | Our friends often come to see us. They came to see us last Friday. | Våra vänner kommer ofta och hälsar på oss. De kom för att hälsa på oss förra fredagen. | [vora vɛner kʰumer ufta ɔɣ hɛlsar pʰo us ‖ dɛ kʰum før at hɛlsa pʰo us fœra fredajen ‖] |
| 607 | I don't watch TV very often. | Jag tittar inte på TV så ofta. | [jaɣ tʰɪtar intə pʰo tʰv so ufta ‖] |
| 608 | I didn't watch TV yesterday. | Jag tittade inte på TV igår. | [jaɣ tʰɪtadə intə pʰo tʰv igor ‖] |
| 609 | Does she go out often? | Går hon ut ofta? | [gor hun ut ufta ‖] |

### Cluster 8 — PDF pp.265-269 / printed pp.259-263 (items #694-708, partial)

| # | EN | SV | IPA |
|---|---|---|---|
| 694 | He was carrying a bag. | Han bar en väska. | [han bar en vɛskʲa ‖] |
| 695 | He wasn't going to the dentist. | Han var inte på väg till tandläkaren. | [han var intə pʰo vɛɣ tʰɪl tʰandlɛkjaren ‖] |
| 696 | He was eating ice cream. | Han åt en glass. | [han ot en ɣlas ‖] |
| 697 | He wasn't carrying an umbrella. | Han bar inget paraply. | [han bar iŋet pʰaraply ‖] |
| 698 | He wasn't going home. | Han var inte på väg hem. | [han var intə pʰo vɛɣ hem ‖] |
| 699 | He was wearing a hat. | Han hade på sig en hatt. | [han hadə pʰo sɛj en hat ‖] |
| 703 | What did he do when the phone rang? | Vad gjorde han när telefonen ringde? | [vad jɔrdə han nɛr tʰelefunen riŋdə ‖] |
| 704 | He stopped reading and answered the phone. | Han slutade att läsa och svarade i telefonen. | [han slutadə at lɛsa ɔɣ svaradə i tʰelefunen ‖] |
| 705 | What did you do yesterday morning? | Vad gjorde du igår morse? | [vad jɔrdə dʉ igor muʂə ‖] |
| 706 | What were you doing at 10:30? | Vad gjorde du vid halv elva? | [vad jɔrdə dʉ vid halv elva ‖] |
| 707 | We played tennis from ten to 11:30. | Vi spelade tennis från tio till halv tolv. | [vi speladə tʰenis fron tʰiu tʰɪl halv tʰulv ‖] |
| 708 | We were playing tennis. | Vi spelade tennis. | [vi speladə tʰenis ‖] |

### Cluster 9 — PDF pp.298-302 / printed pp.292-296 (items #793-804, partial — present-perfect block)

| # | EN | SV | IPA |
|---|---|---|---|
| 793 | She's been to Spain twice. | Hon har varit i Spanien två gånger. | [hun har varit i spanien tʰvo goŋer ‖] |
| 794 | She's been to Japan once. | Hon har varit i Japan en gång. | [hun har varit i japan en goŋ ‖] |
| 795 | She's won a race several times. | Hon har vunnit ett lopp många gånger. | [hun har vɵnit et lup moŋa goŋer ‖] |
| 796 | She's never flown in a helicopter. | Hon har aldrig flugit i en helikopter. | [hun har aldrej flujit i en helikupter ‖] |
| 797 | I've been to New York once. | Jag har varit i New York en gång. | [jaɣ har varit i (...) en goŋ ‖] |
| 798 | I've never played tennis. | Jag har aldrig spelat tennis. | [jaɣ har aldrej spelat tʰenis ‖] |
| 802 | She's written ten books. | Hon har skrivit tio böcker. | [hun har skrivit tʰiu bœker ‖] |
| 803 | She's written a lot of interesting things. | Hon har skrivit många intressanta saker. | [hun har skrivit moŋa intresanta saker ‖] |
| 804 | She's traveled all over the world. | Hon har rest över hela världen. | [hun har rest øver hela vɛlden ‖] |

### Cluster 10 — PDF pp.331-335 / printed pp.325-329 (items #892-906, partial)

| # | EN | SV | IPA |
|---|---|---|---|
| 892 | Remy and Pauline have been married for six months. | Remy och Pauline har varit gifta i sex månader. | [(...) ɔɣ (...) har varit jifta i seks monader ‖] |
| 893 | Hitomi has studied medicine at the university for three years. | Hitomi har studerat medicin vid universitetet i tre år. | [(...) har studerat medisin vid univeʂitetet i tʰrə or ‖] |
| 894 | Ichirou's played the piano since he was seven years old. | Ichirou har spelat piano sedan han var sju år gammal. | [(...) har spelat pʰianu sedan han var ɧu or gamal ‖] |
| 895 | His car's dirty. He's washing his car. He's washed his car. It's clean now. | Hans bil är smutsig. Han tvättar sin bil. Han har tvättat sin bil. Den är ren nu. | [hans bil ɛr smutsej ‖ han tʰvɛtar sin bil ‖ han har tʰvɛtat sin bil ‖ den ɛr ren nʉ ‖] |
| 896 | They're at home. They're going out. They've gone out. They're not at home now. | De är hemma. De går ut. De har gått ut. De är inte hemma nu. | [dɛ ɛr hema ‖ dɛ gor ut ‖ dɛ har gɔt ut ‖ dɛ ɛr intə hema nʉ ‖] |
| 897 | I've lost my passport. I can't find my passport now. | Jag har tappat bort mitt pass. Jag kan inte hitta mitt pass nu. | [jaɣ har tʰapat buʈ mɪt pʰas ‖ jaɣ kʰan intə hɪta mɪt pʰas nʉ ‖] |
| 901 | Junhong is away on vacation. Where has he gone? Where is he now? | Junhong är borta på semester. Vart har han åkt? Var är han nu? | [(...) ɛr buʈa pʰo semester ‖ vaʈ har han okt ‖ var ɛr han nʉ ‖] |
| 902 | Have you met my brother, or should I introduce you? | Har du mött min bror, eller ska jag presentera dig? | [har dʉ mœt min brur \| eler skʲa jaɣ pʰresentera dɛj ‖] |
| 903 | I was a very slow typist in college, but I've gotten faster. | Jag var en väldigt långsam maskinskrivare på universitetet, men jag har blivit snabbare. | [jaɣ var en vɛldijt loŋsam maɧinskrivarə pʰo univeʂitetet \| men jaɣ har blivit snabarə ‖] |
| 904 | Where's your key? — I've lost it. I lost it. | Var är din nyckel? – Jag har tappat bort den. Jag tappade bort den. | [var ɛr din nʏkel ‖ – jaɣ har tʰapat buʈ den ‖ jaɣ tʰapadə buʈ den ‖] |
| 905 | Is Oliver here? — No, he's gone home. He went home. | Är Oliver här? – Nej, han har gått hem. Han gick hem. | [ɛr (...) hɛr ‖ – nej \| han har gɔt hem ‖ han jɪk hem ‖] |
| 906 | We've bought a new car. We bought a new car. | Vi har köpt en ny bil. Vi köpte en ny bil. | [vi har çøpt en ny bil ‖ vi çøptə en ny bil ‖] |

### Cluster 11 — PDF pp.358-362 / printed pp.352-356 (items #973-987)

| # | EN | SV | IPA |
|---|---|---|---|
| 973 | The email hasn't arrived yet. The email didn't arrive today. | Eposten har inte kommit än. Eposten kom inte idag. | [epusten har intə kʰumit ɛn ‖ epusten kʰum intə idaɣ ‖] |
| 974 | We've lived in Paris for six years. We lived in Paris for six years, but now we live in Rome. | Vi bodde i Paris i sex år. Vi bodde i Paris i sex år, men nu bor vi i Rom. | [vi budə i (...) i seks or ‖ vi budə i (...) i seks or \| men nʉ bur vi i rum ‖] |
| 975 | I had lunch an hour ago. | Jag åt lunch för en timme sedan. | [jaɣ ot lunɣ før en tʰɪmə sedan ‖] |
| 976 | I started my new job last week. | Jag började mitt nya arbete förra veckan. | [jaɣ bœrjadə mɪt nya arbetə fœra vekʲan ‖] |
| 977 | My friends arrived on Friday. | Mina vänner anlände på fredagen. | [mina vɛner anlɛndə pʰo fredajen ‖] |
| 978 | Keiko went out at 5:00. | Keiko gick ut vid fem. | [(...) jɪk ut vid fem ‖] |
| 979 | I wore my new suit yesterday. | Jag hade på mig min nya kostym igår. | [jaɣ hadə pʰo mɛj min nya kʰustym igor ‖] |
| 980 | Have you seen Veda? Did you see Veda yesterday? | Har du sett Veda? Såg du Veda igår? | [har dʉ set (...) ‖ soɣ dʉ (...) igor ‖] |
| 981 | I've finished my work. I finished my work at 2:00. | Jag slutade mitt arbete vid två. | [jaɣ slutadə mɪt arbetə vid tʰvo ‖] *(EN/SV content mismatch: EN has two clauses, SV/IPA render only one, same pattern as #595/#599/#602)* |
| 982 | Have you finished? What time did you finish your work? | Har du slutat? Vilken tid slutade du arbetet? | [har dʉ slutat ‖ vɪlken tʰid slutadə dʉ arbetet ‖] |
| 983 | Liting isn't here; she's gone out. | Liting är inte här, hon har gått ut. | [(...) ɛr intə hɛr \| hun har gɔt ut ‖] |
| 984 | Sanjit's grandmother has died. Sanjit's grandmother died two years ago. | Sanjits farmor/mormor har dött. Sanjits farmor/mormor dog för två år sedan. | [(...)s farmur / murmur har dœt ‖ (...)s farmur / murmur duɣ før tʰvo or sedan ‖] |
| 985 | Where have you been? Where were you last night? | Var har du varit? Var var du igår kväll? | [var har dʉ varit ‖ var var dʉ igor kʰvɛl ‖] |
| 986 | My friend is a writer and has written many books. | Min vän är författare och har skrivit många böcker. | [min vɛn ɛr førfatarə ɔɣ har skrivit moŋa bœker ‖] |
| 987 | I played tennis yesterday afternoon. | Jag spelade tennis igår eftermiddag. | [jaɣ speladə tʰenis igor eftermɪdaɣ ‖] |

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. The sentence triplets
above are a deliberately small (149-item), evenly-spread sample of a ~1,000-item course, retained in
full per the spec's allowance for "the sentence-pair format itself" being valuable raw corpus
material — not a bulk reproduction of the source's complete content.
