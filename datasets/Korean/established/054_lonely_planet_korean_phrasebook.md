# Korean — Established Vocabulary/Grammar: Lonely Planet Korean Phrasebook (non-redundant supplement)

**Source:** Minkyoung Kim & Jonathan Hilts-Park, *Korean phrasebook* (Lonely Planet, 3rd edition,
2002), selected sections across pp. 73-89 (Getting Around), 101-108 (Post Office/Telecommunications),
116-120 (Nightclubs & Bars / Dating & Romance), 143-156 (Drugs, Shopping, Souvenirs, Clothing),
157-178 (Food), 233-238 (Emergencies / Dealing with the Police).

**Non-redundant-supplement scope note.** This is the 55th Korean reference book extracted for this
project (established/001-053, 067-069 already landed). Lonely Planet's core phrasebook content —
basic greetings, civilities, numbers, pronouns, question words, days/months, family terms — overlaps
almost completely with material already captured many times over (confirmed by grep check against
all existing `established/*.md` files before extraction: core greetings/numbers/basic-grammar
sections were skipped wholesale as redundant). **Kept:** travel-domain vocabulary that checked as
genuinely absent from the existing corpus — public-transport taxonomy (bus/train/taxi types unique
to Korea's system), car/road vocabulary, the "Dealing with the Police" crime/charge vocabulary set
(a distinctive, comprehensive list not found in any prior Korean extraction), drug-related vocabulary,
souvenir/handicraft terms, a handful of social-register terms (forms of address, taxi-sharing
culture), and clearly-legible Korean dish names. **Skipped as redundant:** Pronunciation/Hangul
chapter (already covered extensively by 013, 018-019 and others), core grammar (particles, verbs,
adjectives — covered by numerous prior files), basic greetings/civilities, numbers, days/months,
accommodation booking phrases (generic hotel-register phrases with no new vocabulary), and most of
Interests & Activities (sports/hobbies vocabulary with no regional or register distinction).

**No dedicated slang/colloquialism callout box was found** (unlike the Rough Guide Japanese
phrasebook's informal-language sidebar) — this phrasebook instead distributes register/politeness
notes throughout as small boxed asides (e.g. "HELLO-YO? IT'S ME-YO!" on the -yo politeness particle,
"ANNYONG ANY OL' TIME" on the single time-of-day-neutral greeting). These are folded into the Grammar
points section below as cultural/register notes rather than true grammar rules, since the format
matches this book's established style. The Dating & Romance chapter's "Classic Pick-Up Lines" and
"Classic Rejections" subsections are colloquial in register but their vocabulary and phrase content
overlap heavily with existing dating/romance phrasebook coverage (042, 045) — spot-checked and judged
not worth a separate table.

**Text-layer gotcha found (new, not previously documented for Korean).** `pdfinfo` reports a real
text layer (`pdftotext` extracts cleanly), but this PDF's `Creator`/`Producer` metadata
(`PFU ScanSnap Manager 4.0.19` / `Adobe PDF Scan Library 2.2`) reveals it is a **scanned-then-OCR'd**
book, not a digitally-typeset one with embedded text. The OCR engine was evidently not tuned for
Hangul: embedded Korean-script (Hangul) snippets consistently misrecognize as nonsense Latin
letters/punctuation/symbols (e.g. the word for "part-time job" renders as `(!!!£?)` and "aunt"
(ajumoni) renders as a string of unrelated glyphs), while the surrounding English prose and all
*romanized* Korean (the book's actual phrasebook entries, e.g. `annyong haseyo`, `kalbi`) come
through correctly. This is **not a decodable fixed-offset or 1:1 substitution cipher** like the
Hangul-codepoint-shift gotcha documented elsewhere in Korean's extraction history — it is genuine
OCR misrecognition of an unfamiliar script, non-recoverable via any fixed mapping. Practical effect:
every vocabulary entry below is captured via its correct romanization and English gloss (both
reliable), but the **native Hangul spelling is omitted** rather than reproduced from the corrupted
text layer — flagged per-row in the Notes column rather than guessed. A handful of pages in the
Typical Korean Dishes section (roughly printed pp. 166-167) show much heavier OCR degradation,
garbling even the English prose into near-unreadable fragments — those specific dish entries were
excluded entirely rather than guessed at; only dishes with fully legible romanization + gloss were
kept.

---

## Vocabulary: Public Transport (Bus/Train/Taxi/Subway/Car/Bicycle)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| shinae bosu | regular metropolitan bus (city-to-city-district routes) | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.73; one of 5 named Korean bus-type categories; Hangul omitted (OCR-corrupted, see coverage note) |
| chwasok bosu | first-class/express metropolitan bus (same routes as shinae bosu, pricier, incl. airport runs) | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.73; Hangul omitted |
| maul bosu | cheap local-neighborhood bus | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.73; lit. "village bus"; Hangul omitted |
| kosok bosu | long-distance inter-city bus | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.73; lit. "high-speed bus"; Hangul omitted |
| chik aeng bosu | rural inter-town bus (stops at local stops between major towns) | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.73; Hangul omitted |
| saemaul-ho | express train class (fewer stops, most expensive/comfortable) | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.79; one of 3 named Korean train classes; Hangul omitted |
| mugunghwa-ho | mid-tier train class (more stops than saemaul-ho, cheaper) | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.79; named after Korea's national flower; Hangul omitted |
| t'ong-il-ho | slowest/cheapest train class (stops at most stations) | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.79; Hangul omitted |
| chihachol | subway | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.82; Hangul omitted |
| chihachol noson | subway line | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.82; Hangul omitted |
| p'yo chapan-gi | ticket vending machine | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.82; Hangul omitted |
| mobom t'aekshi | deluxe/model taxi (pricier than regular taxi) | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.83; one of 3 named Korean taxi types; Hangul partially legible in source as 모범 택시 per romanization but excluded per coverage policy |
| chombo t'aekshi | "jumbo taxi" (minivan taxi, >4 passengers) | noun | technical.transport | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.83; loanword "jumbo" + t'aekshi "taxi"; Hangul omitted |
| hapsung | taxi-sharing / picking up an additional fare en route | noun | colloquial | — | contemporary (source published 2002) | South Korea | national | dictionary | n/a | n/a | p.83 boxed cultural note "TAXI TACTICS"; technically illegal but common practice — a passing taxi already carrying a fare may still stop for a shouted destination going the same direction |
| hoesa ch'a | make (of car) | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.86 ("What make is it?" context); Hangul omitted |
| chuch'a | parking | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.86; Hangul omitted |
| kosoktoro | expressway | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.86; Hangul omitted |
| chajon-go | bicycle | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.89; Hangul omitted |

## Vocabulary: Emergencies & Dealing with the Police

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| pachulso | police substation | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.235; Hangul omitted (OCR-corrupted) |
| pangbom-ch'oso | neighborhood police box | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.235; smaller than a full police station; Hangul omitted |
| kyongch'also | police station | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.235, also p.237 charge-vocabulary list; Hangul omitted |
| kyongch'algwan | police officer | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.237; Hangul omitted |
| taesagwan | embassy | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236-237; Hangul omitted |
| yongsagwan | consulate | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236-237; Hangul omitted |
| pyonhosa | lawyer | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236-237; Hangul omitted |
| honbyong | military police | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.237; Hangul omitted |
| ch'epo | arrest | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.237; Hangul omitted |
| yujoe | guilty | adjective | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.237; Hangul omitted |
| mujoe | not guilty | adjective | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.237; Hangul omitted |
| kyodoso | prison | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.237; Hangul omitted |
| chaep'an | trial | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.237; Hangul omitted |
| polgum | fine (payment) | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.237; Hangul omitted |
| panjongbu haeng-wi | anti-government activity (charge) | noun phrase | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236 "THEY MAY SAY ... you'll be charged with" list; Hangul omitted |
| p'ok'aeng | assault (charge) | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; also used earlier as "I've been assaulted" (p'ok'aeng dang haessumnida); Hangul omitted |
| shiwi | demonstrating (charge) | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; Hangul omitted |
| umju unjon | drink driving (charge) | noun phrase | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; Hangul omitted |
| mugi sojijoe | possession of a weapon (charge) | noun phrase | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; Hangul omitted |
| pulbop ch'imip | illegal entry (charge) | noun phrase | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; Hangul omitted |
| sarin | murder (charge) | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; Hangul omitted |
| pulbop ch'eryu | overstaying your visa (charge) | noun phrase | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; directly relevant to the book's traveler audience; Hangul omitted |
| chuch'a wiban | parking violation (charge) | noun phrase | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; Hangul omitted |
| kukka poanbop wiban | violation of national security law (charge) | noun phrase | technical.legal | — | contemporary (source published 2002) | South Korea | national | dictionary | n/a | n/a | p.236; references South Korea's National Security Act specifically |
| kanggan | rape (charge) | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; also used earlier as "I've been raped" (kanggan dang haessumnida); Hangul omitted |
| choltto | theft/shoplifting (charge) | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; Hangul omitted |
| kyot'ong wiban | traffic violation (charge) | noun phrase | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; Hangul omitted |
| pulbomnodong | working without a permit (charge) | noun | technical.legal | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.236; Hangul omitted |
| todugiya | "Thief!" | interjection | colloquial | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.234 emergency-shout list, alongside puriya "Fire!" and kuman haseyo "Stop!"; Hangul omitted |

## Vocabulary: Drugs

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| hiroppong | methamphetamine | noun | technical.drugs | — | contemporary (source published 2002) | South Korea | national | dictionary | n/a | n/a | p.144; book identifies it as "a small but persistent problem," the main illegal drug named; loanword from Japanese "hiropon"; Hangul omitted |
| taemach'o | marijuana | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.144 ("I smoke marijuana occasionally"); Hangul omitted |
| mayak | illegal drug(s) (generic) | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.144 ("I don't take drugs" = chon mayak anhamnida); Hangul omitted |
| hwan-gakche | acid (LSD) | noun | slang | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.144 drug-vocabulary list; Hangul omitted |
| kok'ain | cocaine | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.144; transliterated loanword; Hangul omitted |
| mayak chungdok | drug addiction | noun phrase | technical.drugs | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.144; Hangul omitted |
| mayangmilmaeja | drug dealer | noun | technical.drugs | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.144; Hangul omitted |
| kwada t'uyo | heroin overdose (injection-related) | noun phrase | technical.drugs | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.144; source lists this alongside "kwada pogyong" as a pair glossed jointly as "overdose"; the heroin entry itself is also listed separately in the same box — exact 1:1 term-gloss mapping in this specific box is ambiguous in the raw extraction, flagged rather than guessed | 

## Vocabulary: Souvenirs & Handicrafts

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| harubang | stone "grandfather" statue (Jeju-do souvenir) | noun | regional | — | contemporary (source published 2002) | Jeju-do | regional | dictionary | n/a | n/a | p.148; Jeju-do-specific; Hangul omitted |
| insamch'a | ginseng tea | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.148; Hangul omitted |
| insamju | ginseng wine | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.148; Hangul omitted |
| sugong yep'um | handicraft (general) | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.148; Hangul omitted |
| hanji kong-yep'um | handicrafts made of traditional (hanji) paper | noun phrase | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.148; Hangul omitted |
| najon ch'ilgi | lacquerware products (mother-of-pearl inlay) | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.148; Hangul omitted |
| soye chakp'um | calligraphy (work) | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.148; Hangul omitted |
| mokkong yep'um | woodcarved figure | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.148; Hangul omitted |

## Vocabulary: Typical Korean Dishes (clearly-legible entries only)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| kalbi | pork or beef ribs, Korean barbecue style | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; classic dish, cooked tableside, eaten wrapped in lettuce; Hangul omitted |
| kalbitchim | steamed ribs | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; Hangul omitted |
| pulgogi | marinated barbecued beef | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; source notes it as "a favourite food when people go out to drink"; Hangul omitted |
| samgyopsal | fried pork belly slices | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; source notes it's often eaten with soju; Hangul omitted |
| sanjok | Korean-style shish kebab (skewered marinated meat) | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; Hangul omitted |
| k'ongnamulguk | bean sprout soup | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; Hangul omitted |
| kimch'i tchigae | kimchi stew | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; source calls it "Korea's version of bachelor food"; Hangul omitted |
| mae-unt'ang | spicy fish soup | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; name literally means "spicy soup"; Hangul omitted |
| manduguk | stuffed dumpling soup | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; Hangul omitted |
| miyokkuk | seaweed soup | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; source notes it's a favorite breakfast and traditional birthday dish; Hangul omitted |
| samgyet'ang | boiled chicken stuffed with ginseng | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; eaten for energy, often with ginseng wine; Hangul omitted |
| sollongtang | beef and noodles in hot beef-bone broth | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; favorite lunch dish; Hangul omitted |
| sundubu | spicy soft-tofu stew | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; served still boiling in its cooking pot; Hangul omitted |
| t'angsuyuk | sweet and sour pork | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165; Hangul omitted |
| toenjang tchigae | soybean-paste (miso-style) stew | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.165-166; source compares toenjang to Japanese miso but "more pungent"; Hangul omitted |
| chapch'ae | Chinese-style glass noodles with vegetables | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.166; Hangul omitted |
| k'alguksu | thick noodles in anchovy broth | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.166; Hangul omitted |
| makkuksu | vegetable noodles in chicken broth | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.166; Hangul omitted |
| naengmyon | spicy cold noodles in broth | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.166; summer favorite; also called mul naengmyon ("water cold noodles"); Hangul omitted |
| pokkumbap | fried rice | noun | core | — | contemporary (source published 2002) | — | — | dictionary | n/a | n/a | p.167; recovered from a heavily OCR-degraded page region — gloss and romanization both independently legible despite surrounding garbling; Hangul omitted |

**Excluded due to OCR degradation:** several additional dish entries on the same page range
(approx. printed pp. 166-167, including what context suggests are bibimbap, a stuffed-noodle dish,
dduk-bokki-adjacent rice-cake entries, saengsonhoe "sliced raw fish/sashimi," a simmered-fish dish,
and a broiled/salted fish dish) were visible only as fragmentary, badly garbled OCR text — both the
romanization and the English gloss were too corrupted to extract with confidence. Per this project's
"default to the riskier assumption when uncertain" discipline, these were excluded rather than
guessed at. A future vision-reading pass over just that page range (printed pp. 166-167) could
likely recover them cleanly if this gap is worth closing later.

## Grammar points

### The -yo politeness particle as a mandatory default

The book's boxed note "HELLO-YO? IT'S ME-YO!" (p.107) frames the `-yo` (요) sentence-final particle
not just as one register option among several, but as something a speaker should include by default
in virtually all speech to adults who aren't close friends, younger family, or clearly junior in
status — omitting it is described as risking being heard as an insult, even in a one-word reply.
This frames `-yo` less as a discrete politeness level and more as an "always-on unless you have a
specific reason to drop it" default — complements, rather than duplicates, the more systematic
honorific-level paradigms already captured from 018-019 and 031.

### Single time-of-day-neutral greeting

A short cultural note (p.116, "ANNYONG ANY OL' TIME") observes that Korean has only one general
greeting, annyong haseyo (안녕하세요), used at all times of day — unlike English's morning/afternoon/
evening-specific greetings. Minor but genuinely distinct from prior Korean extractions' greeting
coverage, which focused on formality-level variation rather than this time-of-day-neutrality point.

### Forms of address: generational/relative terms extending to strangers

p.59-61 describes Koreans' tendency to address unfamiliar people using kinship-style terms scaled by
apparent age/status rather than a fixed second-person pronoun: ajumoni/ajumma ("aunt"/"auntie," for
an older woman), ajoshi ("uncle," for an older man), halmoni/haraboji ("grandmother"/"grandfather,"
for elderly people), and sonsaengnim/sonbaenim (lit. "higher person") as safe generic terms of
respect when a visitor's exact relative status is unclear. The book also notes agashi (lit.
"husband's younger sister," for a young woman) has fallen out of favor as presumptuous/dated, and
that young people increasingly default to the attention-getting phrase yogiyo! ("over here," with a
polite ending) rather than any kinship term at all when calling a server in a restaurant — flagged by
the source as a real, if subtle, register/generational shift, not just a fixed rule.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
