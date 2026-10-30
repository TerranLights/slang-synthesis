# Korean — Established Vocabulary/Grammar: Korean For Dummies (full book)

**Source:** Jungwook Hong and Wang Lee, *Korean For Dummies* (Wiley, 2008), 387pp — full-book
extraction covering all 20 chapters (Part I: Getting Started, pp.9-68; Part II: Korean in Action,
pp.71-188; Part III: Korean on the Go, pp.191-275; Part IV: The Part of Tens, pp.279-299) plus
Appendix A "Korean Verbs" (pp.303-305) and Appendix B "Mini-Dictionary" (pp.306-330). A companion
2-page *Korean For Dummies Cheat Sheet* PDF was also checked and found to be a condensed excerpt of
material already in the main book (basic phrases, numbers, days of the week) — nothing extracted
from it separately. Text layer verified clean throughout via `pdftotext`; **this book has no Hangul
text layer anywhere** — every Korean term is given only in the book's own romanization (Revised
Romanization convention) with an English gloss in parentheses, so there is no font-substitution-
cipher risk and no vision-reading was needed anywhere in this source.

**Coverage note — non-redundant-supplement dispatch (whole book).** This project already has 40
prior established Korean files covering grammar-course lessons, dictionaries, dialect sources, and
an academic honorifics monograph. Every chapter range below was checked against that existing corpus
before extraction (especially `001`-`002` basic grammar, `013` pronunciation, `018`-`019` grammar for
international learners, `026`-`029` dictionaries, `030` Dirty Korean, `031` the honorifics monograph,
`032` Making Out in Korean, `033` the northern-dialect course). Basic phonetics/grammar/numbers/the
4-level politeness framing (Chapters 1-2) turned out almost entirely redundant and were mostly
skipped. The book's real value for this project is concentrated in two places: **(a)** its domain/
scenario-organized vocabulary (Chapters 4-16) — something no prior established file replicates, since
this corpus's existing vocabulary otherwise comes from grammar-lesson ordering, dictionaries, or
slang/dialect sources, never a phrasebook-style domain organization (restaurant, shopping, bank,
hotel, hospital, etc.); and **(b)** its "Part of Tens" colloquial-idiom chapters (17-20), which
surfaced roughly 18 genuinely new slang/idiom items with rich register data. Each chapter range's
specific skip/keep reasoning is preserved in its own subsection below for auditability (this is a
merge of 7 separately-dispatched extraction passes — 6 by sub-agents restricted to scratch files, 1
[Chapters 17-20] done directly by the orchestrating agent — all reconciled and verified here by the
orchestrator before this file was written).

**Note on a stray duplicate scratch file.** During this dispatch, a scratch file named
`chunk_ch4-16.md` was found in the working scratch directory that was never requested by this
dispatch's orchestrator — its content fully overlapped the page range already covered, chapter by
chapter, by the four separately-dispatched chunks below (Ch.4-7, 8-10, 11-13, 14-16). It was excluded
from this merge entirely to avoid double-extraction; the four properly-scoped chunks are the sole
basis for the Chapters 4-16 content below.

---

## Vocabulary: Chapters 1-3 (Getting Down the Basics; Basic Grammar and Numbers; Introductions and Greetings)

**Skipped as fully redundant:** the vowel/consonant inventory and allophonic rules (`013` covers this
with real phonetic depth — laryngeal 3-way contrast, syllable-final neutralization, tensification);
the native-Korean and Sino-Korean number systems and counters 1-10/20 (`001` already tabulates these
fully, including the 5 irregular pre-counter forms); basic SOV word order, no-plural/no-gender/
no-agreement points, the subject/object/topic particle system, the dictionary-stem→-아/어요
conjugation rule, question formation by rising intonation, the 이/그/저 demonstrative triad, and the
4-level formal/informal/intimate/plain politeness framing (`031` already flags this as "the loose
4-level framing most textbooks give"); the big-to-small address-ordering principle (already in `001`);
the gendered older-sibling terms 형/누나/오빠/언니 (`030`-`032` already have these).

**Kept because genuinely new:** two loanword semantic-drift findings; a three-item honorific-noun
lexical-doublet set (food/name/home) distinct from the verb doublets `031` covers; a lexicalized
hierarchy idiom; a near-complete thanks/apology/goodbye register paradigm that, despite being
textbook-standard content, had **zero** prior formal-register capture anywhere in the 40 prior files;
the letter-spelling naming convention for introducing elders; a modest set of genuinely uncaptured
basic nouns used as the book's own pronunciation illustrations.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| chureoning (추리닝) | sweatpants/gym pants (NOT "training") | noun (loanword, semantic drift) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.1 "Puzzling English Words in Korean" sidebar, p.18; English "training" re-anchored to the gym-pants referent rather than the activity. |
| beella (빌라) | condominium/apartment complex (NOT a countryside villa) | noun (loanword, semantic drift) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Same sidebar, p.18; distinct from the already-documented paenti (panties) semantic-shift case in `032`. |
| jinji (진지) | "food/meal" (honorific) vs. plain bap (밥) | noun (honorific doublet) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.2 p.28; a common-noun honorific/plain doublet, distinct in kind from the verb doublets (먹다/드시다 etc.) already tabulated in `031`. |
| seongham / jonham (성함/존함) | "name" (honorific) vs. plain ireum (이름) | noun (honorific doublet) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.2 p.28; two honorific synonyms for the same plain noun. |
| daek (댁) | "home/house" (honorific) vs. plain jip (집) | noun (honorific doublet) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.2 p.28. |
| wi areaga itda (위아래가 있다) | "to have a top and bottom" — a group/relationship that properly observes seniority | idiom (set phrase) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.54. |
| wi areaga eopda (위아래가 없다) | "to have no top and bottom" — said of someone judged rude/disrespectful of seniority | idiom (set phrase) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.54; negative counterpart — a real social-sanction phrase, not merely descriptive. |
| gamsahamnida / gamsahaeyo (감사합니다/감사해요) | thank you (formal polite / informal polite) | phrase pair | formal/core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.63. |
| gomapseumnida / gomawoyo (고맙습니다/고마워요) | thank you (formal polite / informal polite, interchangeable with the pair above) | phrase pair | formal/core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.63. |
| singyeong sseo jusyeoseo... / jalhaejusyeoseo... (신경 써 주셔서.../잘해주셔서...) | "for caring..." / "for being so nice..." — dependent clauses, never used alone, chained before gamsahamnida/gomapseumnida | phrase fragments (formal) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.63. |
| joesonghamnida / joesonghaeyo (죄송합니다/죄송해요) | I'm sorry (formal/informal polite) — to strangers or people owed respect | phrase pair | formal/core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.63. |
| mianhamnida / mianhaeyo (미안합니다/미안해요) | I'm sorry (formal/informal polite) — interchangeable with the pair above | phrase pair | formal/core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.63. |
| pyekkichyeo deuryeoseo mianhamnida/joesonghamnida (폐끼쳐 드려서 미안합니다/죄송합니다) | "Sorry for causing such trouble" — formal only, book explicitly omits an informal-polite form | phrase | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.64. |
| joesonghamnidaman... / sillyehamnidaman... (죄송합니다만.../실례합니다만...) | "I'm sorry, but..." / "Excuse me, but..." — request-prefacing icebreaker, formal-polite recommended | phrase construction | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.61. |
| annyeonghi gyeseyo (안녕히 계세요) | goodbye, said BY the leaver TO the one staying (lit. "stay well") | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.65; flagged as the most common goodbye. |
| annyeonghi gaseyo (안녕히 가세요) | goodbye, said BY the one staying TO the leaver (lit. "go well") | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.65; mirror-image of the above — distinguishes speaker role, not just politeness. |
| jal isseyo / jal gaseyo (잘 있어요/잘 가요) | goodbye, informal-polite counterparts of gyeseyo/gaseyo (toward juniors/peers) | phrase | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.65. |
| daeume tto bwayo (다음에 또 봐요) | "see you again next time" — register-neutral | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.65. |
| annyeonghi jumuseyo (안녕히 주무세요) | "good night" (honorific) — restricted to someone sleeping at the same location, or called at their actual bedtime; NOT a general evening-parting phrase like English | phrase | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.65. |
| jaljayo (잘 자요) | "good night" (plain/casual), same same-location/bedtime restriction | phrase | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.65. |
| sugohaseyo (수고하세요) | "keep up the good work" — usable toward seniors or juniors, any time | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.65; compare the plain-register sugohaeyo/sugohasipsiyo pair from this same book's Chapter 20 (below). |
| [Name]-ja, [Name]-ja, [Name]-ja-simnida (spelling-out construction) | syllable-by-syllable name-spelling convention for stating a parent's/grandparent's name to another elder | grammar construction | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.59; e.g. for father Choe Nam Hyun: "uri abeoji jonhameun Choe-ja, Nam-ja, Hyun-ja-simnida." Avoids "presuming" to state the honored name outright. |
| kiga jageun / kiga keun (키가 작은/키가 큰) | short / tall (attributive, people-describing) | adjective phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.61; offered because pointing at people is rude in Korean culture. |
| angyeongeul sseun / angyeongeul an sseun (안경을 쓴/안경을 안 쓴) | wears glasses / doesn't wear glasses | verb phrase (attributive) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.61. |
| meoriga jjalbeun / meoriga gin (머리가 짧은/머리가 긴) | short-haired / long-haired | adjective phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.61. |
| chimdae / chitsol / angyeong / hwajangsil / geoul / uija / wiheom / babo / yokjo / hyusik (침대/칫솔/안경/화장실/거울/의자/위험/바보/욕조/휴식) | bed / toothbrush / eyeglasses / bathroom / mirror / chair / danger / dummy-fool (mild insult) / bathtub / rest | nouns | core (babo = colloquial) | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.1 pronunciation-illustration vocabulary (Tables 1-1/1-2), p.9-23; not found elsewhere in the corpus's established files. |
| chingu(deul) / haengdong (친구(들)/행동) | friend(s) / gesture(s)-action(s) | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.1 p.9; chingu reused as Ch.3's default "friend" in introductions (dongnyo "co-worker" substitutes in that slot). |
| byeolmalsseumeseyo (별말씀이세요) | "don't mention it" | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.1 Table 1-3; not found elsewhere via grep. |
| silyaehaeyo (실례해요) | "excuse me" (informal polite) | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.1 Table 1-3; informal-polite counterpart of the formal sillyehamnida above. |
| cheoeumboepgetseumnida (처음 뵙겠습니다) | "nice to meet you for the first time" (formal polite) — restricted to first meetings only | phrase | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.50. |
| mannaseo bangapseumnida (만나서 반갑습니다) | "it's a pleasure to meet you" (formal polite) — conventionally follows the phrase above | phrase | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.50. |
| oraeganmanineyo (오래간만이네요) | "long time no see" | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.50. |
| siksa hasyeoseoyo? (식사하셨어요?) | "Have you eaten?" — greeting-function question, not a literal invitation | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.50. |
| geudongan byeoril eopseusyeotjyo? (그동안 별일 없으셨죠?) | "Is everything all right?" (lit. "nothing bad has happened, right?") | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.3 p.50. |

### Grammar points

**Loanword semantic drift (two new cases).** *chureoning* ("training"→gym pants) and *beella*
("villa"→condo/apartment complex), Ch.1 p.18 — the same phenomenon already documented for *paenti*
in `032`, two new data points.

**Honorific common-noun doublets (new subclass).** `031`'s extraction focused on **verb** doublets
(먹다/드시다 etc.) and address/pronoun devices. This book's Ch.2 (p.28) adds a parallel **common-noun**
doublet set: 밥→진지 (food/meal), 이름→성함/존함 (name), 집→댁 (home) — framed by the book as optional
("you can get by without them"), i.e. lower-obligation than verb substitution.

**The hierarchy idiom 위아래가 있다/없다.** Ch.3 p.54 — a lexicalized "top and bottom" metaphor for
seniority-respecting behavior; the negation is a live social-sanction accusation, one level more
idiomatic than the Confucian-hierarchy discussion already in `010`/`031`.

**A near-complete thanks/apology/goodbye register paradigm.** Despite being basic content, a grep of
all 40 prior established files found **no prior formal-register capture** of the gamsahamnida/
gomapseumnida, joesonghamnida/mianhamnida, or annyeonghi gyeseyo/gaseyo pairs — closest prior touch
was `032`'s informal/slang register. Two structural points: (1) Korean's goodbye distinguishes
**speaker role** (leaver says gyeseyo "stay well" TO the stayer; stayer says gaseyo "go well" TO the
leaver) on top of politeness level — English collapses this; (2) annyeonghi jumuseyo/jaljayo ("good
night") are restricted to same-location/actual-bedtime use, unlike English's general evening-parting
sense.

**Letter-by-letter name-spelling convention for elders.** Ch.3 p.59 — spelling a parent's/
grandparent's name syllable-by-syllable with -자 appended, rather than saying it as a normal word,
when a junior must state it to another elder. Distinct from the big-to-small ordering convention in
`001`.

**Skipped as fully redundant (stated explicitly per spec).** Ch.1's vowel/consonant inventory (`013`
covers this with far more phonetic depth); Ch.2's number systems, counters, pronoun/particle
inventory, verb/adjective conjugation basics (`001`/`002`); the 4-level politeness framing and
big-to-small ordering (`031`/`001`); gendered sibling terms (`030`-`032`). Ch.2's ad-hoc English-
stem+하다 code-mixing illustration (p.34-35) is a looser variant of the already-documented productive
loanword-stem+하다 pattern in `023` — not given its own point since it adds no new mechanism.

---

## Vocabulary: Chapters 4-7 (Small Talk; Eating & Drinking; Shopping; Exploring the Town)

**Coverage note.** This book is organized by everyday scenario/topic rather than grammar lesson — a
different organizing axis from most prior sources. **Kept in full:** the weather-conditions and
colors tables (zero hits elsewhere), the residential/location-word tables, the full family/kinship
table (several terms add notes not seen in `031`'s more abstract kinship discussion), the Korean/US
clothing-size conversion table (unique to this source), the eight named gimchi varieties (prior files
mention gimchi only as an isolated example, never a systematic list), the bargaining/refund phrase
set, and several idiomatic conversational routines. **Skipped as redundant:** basic numbers and
Sino-Korean counting (`001`-`002`, `006`-`009`), the core honorific framing and most -(eu)si- subject-
honorific mechanics (`031`), and repeated "Fun & Games" drills (pure pedagogical padding).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| eodieseo osyeoseoyo? | Where are you from? (polite) | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.4 p.71; standard opener after introductions. |
| jeoneun ... eseo waseoyo | I'm from... | phrase template | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.4 p.72. |
| Country names (dogil, gana, hoju, ilbon, indo, itaeri, jungguk, kaenada, miguk, nyujillaendeu, peurangseu, rebanon, reosia, sseuwiseu, yeongguk) | Germany, Ghana, Australia, Japan, India, Italy, China, Canada, USA, New Zealand, France, Lebanon, Russia, Switzerland, England | nouns (proper) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 4-1, p.74; mostly transliterated loanwords. |
| do / si / gu / gun / dong / eup / myeon / ri / gwangyeoksi | province / city / district / county / neighborhood / town / township / village / metropolitan area | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 4-2, p.75; administrative hierarchy, large-to-small order (e.g. gangnamgu, sinsadong) — opposite of English place-name ordering. |
| bukjjok / namjjok / dongjjok / seojjok / wi / mit / yeop / gakkai / geuncheo / meolli | north / south / east / west / above / below / next to / nearby / in proximity / far | nouns/adverbs | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 4-3, p.76. |
| -i/-ga (with iseoyo) | subject particle used with "to exist/be located" | particle | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.76; -i after consonant-final, -ga after vowel-final host. |
| Family/kinship terms: gomo/imo/hyeongje/janyeo/ttal/abeoji/sonnyeo/chinharabeoji/oeharabeoji/chinhalmeoni/oehalmeoni/jobumonim/sonja/nampyeon/bakkatyangban/eomeoni/hyeong/oppa/nuna/eonni/bumonim/jamae/adeul/samchon/oesamchon/namdongsaeng/dongsaeng/yeodongsaeng | paternal/maternal aunt, brothers, children, daughter, father, granddaughter, paternal/maternal grandfather, paternal/maternal grandmother, grandparents, grandson, husband, husband (wife-to-husband, lit. "outside person"), mother, older brother (m./f. speaker), older sister (m./f. speaker), parents, sisters, son, paternal/maternal uncle, younger brother/sibling/sister | nouns (kinship) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 4-8, pp.87-88; paternal/maternal distinguished by root word, not prefix; sibling terms split by relative age AND speaker's own gender. bakkatyangban is a culturally loaded self-effacing wife-to-husband term. Fictive-kinship note: non-blood elders addressed as harabeoji/halmeoni, mother's friends sometimes called imo. |
| [relative] kkaeseo gyeseyo? / [relative] i/ga iseoyo? | "Do you have a [relative]?" — honorific vs. plain question form, keyed to whether the relative outranks the speaker | phrase template | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.89. |
| jeorang sagwillaeyo? | Do you want to go out with me? | phrase | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.4 "Words to Know" p.90; dating vocabulary (deiteu "date") not covered elsewhere. |
| yeollakcheoga eotteoke doesimnikka? / ...dwaeyo? | What is your contact information? (formal/informal pair) | phrase pair | formal/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.91; formal for a first-time stranger, informal once already acquainted — register keyed to acquaintance history, not just rank. |
| nalssiga eottaeyo? | What is the weather like? | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.4 p.80. |
| anjoayo/chuwoyo/deowoyo/geonjohaeyo/heuryeoyo/joayo/malgayo/mudeowoyo/nappayo/seonseonhaeyo/seupaeyo/siwonhaeyo/ttatteutaeyo | not good/cold/hot/dry/cloudy/good/clear/hot-humid/bad/cool-refreshing/humid/cool/warm | adjectives (weather) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 4-4, p.80-81; first systematic weather-adjective table in this corpus. siwonhaeyo here glossed narrowly as "cool" — contrast the richer catharsis sense of siwonhada in Ch.20 below. |
| bi(ga)/nun(i)/ubak(i) wayo/naeryeoyo | rain/snow/hail falls (two interchangeable verbs) | phrase construction | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.81. |
| bom/yeoreum/gaeul/gyeoul | spring/summer/fall/winter | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.81, 128. |
| irwol...sibiwol (months) | January...December | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.81-82; Sino-Korean-number + wol ("month"), e.g. sibirwol = November. |
| boda | than/compared to | particle | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.82-83; placeable at the START of the comparison ("compared to X, Y is...") as well as the more English-like post-posed position. |
| Occupations (23 items: hoegyesa/yorisa/daehaksaeng/keonseolteonteu/oegyogwan/uisa/pyeonjipja/seungmuwon/gongmuwon/daehakwonsaeng/godeunghaksaeng/jubu/byeonhosa/gijang/gyosu/peurogeuraemeo/gija/yeonguwon/gunin/haksaeng/seonsaeng/mujik/weiteo/jakga) | accountant/chef/college student/consultant/diplomat/doctor/editor/flight attendant/government official/grad student/high schooler/housewife/lawyer/pilot/professor/programmer/reporter/researcher/soldier/student/teacher/unemployed/waiter/writer | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 4-6, pp.83-84; fuller list than isolated prior examples. |
| Areas of study (-hak compounds: illyuhak/misulhak/keompyuteo gonghak/gyeongjehak/yeongmunhak/sahak/beopak/gyeongyeonghak/suhak/uihak/cheolhak/mullihak/sahoehak) | anthropology/art history/computer science/economics/English lit/history/law/management/math/medicine/philosophy/physics/sociology | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 4-7, p.85; transparent, productive -hak ("study of X") suffix. |
| chodeunghakgyo/junghakgyo/godeunghakgyo/daehakgyo (+hakbu/seoksagwajeong/baksagwajeong) | elementary/middle/high school/college (+undergrad/master's/PhD) | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.86-87; book flags US/Korea grade-numbering mismatch. |
| Culinary terms (keop/jeopshi/jaengban/gonggi/sogeum/seoltang/huchu/sikcho/chamgireum/pa/yangpa/gamja/gogi/sogogi/dakgogi/dwaejigogi/saengseon/gyeran/maneul/danggeun/dubu/mandu/subak/sagwa/orenji + loanwords seupageti/ppang/pija/saelleodeu/saendeuwichi/seuteikeu/tomato/beurokeolli/yangbaechu) | cup, plate, tray, bowl, salt, sugar, pepper, vinegar, sesame oil, green onion, onion, potato, meat, beef, chicken, pork, fish, egg, garlic, carrot, tofu, dumpling, watermelon, apple, orange + spaghetti/bread/pizza/salad/sandwich/steak/tomato/broccoli/cabbage | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 5-1, pp.96-97. |
| bap/banchan/jinji/siksa | meal/rice (plain)/side dishes/meal (honorific, elders-dignitaries)/meal (formal-respectful) | nouns | core/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.94-95; three-tier register system for "meal" (bap < siksa < jinji, the last pairing with honorific eating-verb deusida rather than plain meokda). |
| bap meogeoseoyo?/siksa hasyeosseoyo? | Have you eaten? (casual/formal-respectful) | phrase | core/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.94-95; a genuine greeting formula expressing consideration, with real social weight beyond small talk. |
| bae gopayo/mok mallayo | I'm hungry (lit. stomach yearns)/I'm thirsty (lit. throat parched) | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.95; same string with rising intonation = "Are you hungry?" — prosody alone carries the distinction. |
| unje hanbeon gachi siksa hapsida! | Let's get together for a meal sometime! | phrase (social formula) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.95; a commitment-free social nicety — removing unje/hanbeon/gachi turns bare siksa hapsida into an actual request. |
| sutgarak/sutgal/sujeo / jeotgarak/jeotgal | spoon / chopsticks | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.96; three free-variant forms for "spoon" alone. |
| jal meokgetseumnida / jal meogeotseumnida | "I will eat it well" (pre-meal) / "I have eaten it well" (post-meal compliment) | phrase pair (ritual) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.98; tense-contrasted phrase pair bracketing a meal. |
| gimchi varieties: tongbaechu gimchi/chonggak gimchi/oi sobaegi/baek gimchi/mul gimchi/dongchimi/bossam gimchi/kkakdugi | whole-cabbage/small-turnip/cucumber/"white" (no red pepper)/watery broth/watery radish/wrapped/diced-radish gimchi | nouns (culinary) | core | — | contemporary (source published 2008) | — | regional variation noted | grammar_reference | n/a | n/a | p.98-99; first systematic multi-variety gimchi list in the corpus. |
| bulgogi/dwaeji bulgogi/dak bulgogi | marinated beef ("fire meat")/marinated pork/marinated chicken | nouns (culinary) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.99; pork/chicken marinades run spicier than the sweet-savory beef version. |
| guk vs. jjigye | lighter clear-broth soup vs. thicker stew | nouns (culinary, contrastive) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.99-100; field test: soup spooned INTO rice = jjigye; rice dumped INTO soup = guk. |
| oraetdongan gidarisyeosseoyo?/onji eolma andoeyo/neujeoseo joesonghaeyo | Did you wait long?/No, I just arrived (polite fiction)/Sorry I'm late | phrase set (punctuality) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.100; "I just arrived" flagged as a polite fiction regardless of actual wait. |
| mat/aju/neomoo/eopseoyo/iseoyo/darayo/jjayo/syeoyo | flavor/very/really/(flavor) isn't there/is there/sweet/salty/sour | adjectives/nouns (taste) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 5-2, p.100-101; "flavor exists/doesn't exist" idiom for tasty/not tasty. |
| yeogiyo / sillyehamnida (summoning waitstaff) | "here!"/"over here" / excuse me | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.101. |
| jumun badajuseyo / gyesan haejuseyo | please take our order / check, please | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.101. |
| pojang macha | street-side food cart/stall (lit. "covered wagon") | noun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.102-103; narrow-menu, late-night, post-bar/club nightlife institution. |
| annyeonghi gyeseyo / annyeonghi gaseyo (restaurant-leaving reuse) | stay well / go well | phrase pair | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.103-104; distinct from sugo haseyo, specifically for service workers as you leave their establishment. |
| geonbae | cheers! (drinking toast) | interjection | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.107; paired with pouring/drinking-order etiquette (younger pours for elder with two-handed support, waits for elder's first sip, turns away to drink). |
| Drinks (sul/maekju/wain/yangju/wiseuki/bodeuka/soju/mul/keopi/uyu/juseu/sagwa juseu/orenji juseu/cha/nokcha/insamcha) | alcohol/beer/wine/foreign liquor/whiskey/vodka/soju/water/coffee/milk/juice/apple juice/orange juice/tea/green tea/ginseng tea | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 5-4, pp.107-108. |
| baekhwajeom/gage/sijang/byeoruk sijang | department store/small shop/market/flea market | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.111-112; myeongdong, dongdaemun sijang, namdaemun sijang, itaewon named as Seoul's major shopping districts. |
| gugyeonghareo wasseoyo | I'm just here to browse | phrase | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.114-115; signals to staff not to be disturbed. |
| ige/igeo vs. jeoge/jeogeo | this one / that one | pronouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.118. |
| ssada/bissada/joayo/anjoayo/nappayo | cheap-good bargain/expensive/good/not good/bad | adjectives | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.118-119; cultural note: Koreans say anjoayo rather than nappayo when disparaging a merchant's goods — nappayo flagged as an actual insult in that context. |
| ippeoyo/meosisseoyo | pretty (feminine/children's clothing) / handsome-fashionable (gender-neutral) | adjectives | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.119; gendered-register split for which compliment-adjective fits which clothing category. |
| Korean/US clothing-size conversion (underwear 75A-85B↔32A-36B; tops/bottoms 44/55/66/77 or 85-100↔XS-L or numeric; shoes 230-250↔US 6-8) | — | reference table (culturally load-bearing) | core | — | contemporary (source published 2008) | — | national | grammar_reference | n/a | n/a | p.120-121; unique to this source. |
| Colors (hayansaek/noransaek/juhwangsaek/ppalgansaek/choroksaek/parangsaek/borasaek/geomjeongsaek/bamsaek/hoesaek) | white/yellow/orange/red/green/blue/purple/black/brown/grey | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 6-1, p.119; first systematic color-term table in this corpus. |
| neomu bissayo/jom kkakkajuseyo | It's too expensive / please lower the price a bit (lit. "shave off a little") | phrase | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.123; open-air-market haggling formula — department stores have fixed prices. |
| banhwan haejuseyo | please give me a refund | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.123; refunds reliable at department stores, unlikely at open-air markets. |
| yoil/woryoil/hwayoil/suyoil/mogyoil/geumyoil/toyoil/iryoil | day of the week / Mon-Sun | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 7-1, p.125-126; shared -yoil suffix + day-specific prefix. |
| ju/juil/jumal/jeobeonju/jinanju/jeobeonjumal/jinanjumal/ibeonju/daeumju | week/weekday/weekend/last week (x2)/last weekend (x2)/this week/next week | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.125-126; Korean week starts Monday, ends Sunday. |
| si/boon/cho/ojeon/ohu | hour/minute/second/AM/PM | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.126. |
| hansi...yeoldusi (native-Korean clock hours 1-12) | 1 o'clock...12 o'clock | nouns (numeral+si) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 7-2, p.127; native-Korean (not Sino-Korean) numerals for clock hours. |
| oneul/eoje/naeil/jigeum/najunge/jom itdaga/eonje | today/yesterday/tomorrow/right now/later/in a little while/when | adverbs/pronouns (time) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.127. |
| hallyu | the "Korean Wave" (pop-culture export phenomenon) | noun (cultural keyword) | core | — | contemporary (source published 2008); term coined late-1990s/2000s | — | — | grammar_reference | n/a | n/a | p.130-131; named, emergent sociocultural phenomenon. |
| noraebang | karaoke room (lit. "song room") | noun (cultural institution) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.131-132; private per-group room, contrasted with Western bar karaoke; a near-universal stress-relief activity. |
| simsimhaeyo | I'm bored | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.133; triggers a "let's do something" social script. |
| eottaeyo? | How about it?/How is it?/What do you think? | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.135-136; all-purpose feedback-soliciting phrase. |
| gayo vs. gasijyo | "let's go" (everyday) vs. "let's go" (toward seniors) | phrase pair | core/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.135. |
| uri jip vs. jeohui jip | our house (plain) vs. our house (polite, toward senior/boss) | noun phrase pair | core/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.136; uri jibe nolleo oseyo ("come play at our house") — "PLAY" used idiomatically for any visit invitation. |
| doenjang jjigye/bibimbap/tteokbokgi | soybean-paste stew/mixed rice/stir-fried rice cakes in chili paste | nouns (culinary) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.137. |
| chwimi/jaemi | hobby/fun | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Opening of Ch.8's hobby list, p.139-140; captured again in the Ch.8-10 section below. |

### Grammar points

**Large-to-small place-name ordering.** Province/city, then district, then neighborhood — reverse of
English (Ch.4, p.73-75).

**Location/comparison particle pairs are register- and structure-sensitive.** The -i/-ga allomorphy
marks the located item before iseoyo; the comparative particle boda is grammatical either sentence-
initial ("compared to X...") or post-posed, English-style (Ch.4, p.76, 82-83).

**Three-tier register layering for ordinary nouns, not just verbs.** Most prior honorifics coverage
(`031`) focuses on honorific VERB substitution. This source shows the same plain/respectful/honorific
layering applied to a NOUN: "meal" has bap (plain), siksa (respectful/formal), and jinji (true
honorific, pairing obligatorily with deusida rather than plain meokda) (Ch.5, p.94-95).

**Politeness-register choice keyed to acquaintance history, not just social rank.** The formal/
informal choice for "what's your contact information?" is explicitly keyed to first-meeting vs.
repeat-encounter status — an acquaintance-duration rule layered on top of age/rank-based honorific
rules (Ch.4, p.91).

**Transparent compound numeral+classifier formation for months and clock-hours.** Months use
Sino-Korean-number+wol; clock hours in sample dialogues use native-Korean numeral roots+si — two
different numeral systems feeding the same template depending on which time-unit is counted (this
book doesn't make the distinction explicit itself; flagged here from comparing the two sets directly)
(Ch.4 p.81-82, Ch.7 p.127).

**Vagueness as a social-nicety strategy.** unje hanbeon gachi siksa hapsida! stacks three vague
qualifiers onto what would otherwise be a direct commitment-request — a politeness-via-vagueness
pragmatics point not previously captured in this corpus (Ch.5, p.95).

---

## Vocabulary: Chapters 8-10 (Recreation & Sports; Phone/Mail/Fax/Internet; Office & House)

**Coverage note.** Checked against `030` (yeoboseyo, PC-bang/gaming culture, drinking/pouring
etiquette, noraebang — the one file with real overlap hits) and `014` (also touches noraebang,
ondol). **Skipped as redundant:** the bare yeoboseyo gloss and PC-bang as an isolated cultural concept
(`030` already names both). **Kept because genuinely new/deeper:** the full formal-polite phone-call
phrase apparatus; the complete office-honorific presence-reporting pair (iseoyo/gyesimnida,
distinct from `031`'s more abstract treatment); the full business-title+-nim address system; the
business-dinner drinking-etiquette mechanics (`030` only has a bare geonbae-adjacent mention); the
housing-category table, bathroom-culture notes, cleaning/laundry vocabulary, sleepover etiquette; the
named seasonal-observation-activity compounds; the sports-naming set including ssireum and its
champion title; the PC-bang/gaming-culture prose discussion (well beyond `030`'s single-line mention).
Repeated "Fun & Games" drills skipped throughout.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Sports/hobbies (baegu/chaegikgi/chejo/chukgu/chwimi/deungsan/eumakdeutgi/geurimgeurigi/golpeu/gongwon/haendeubol/misik chukgu/nonggu/peullut yeonju/piano yeonju/sanchaek/sipjasu/suyeong/taegwondo/takgu/undong/yagu/ssireum) | volleyball/reading books/calisthenics/soccer/hobbies/mountain climbing/listening to music/drawing/golf/park/handball/American football/basketball/playing flute/playing piano/stroll/cross-stitch/swimming/taekwondo/table tennis/exercise/baseball/traditional Korean wrestling | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.8, pp.141-142; ssireum's champion title cheonhajangsa ("the strongest under heaven") is distinctive, not found elsewhere. |
| Nature vocabulary (pokpo/san/sup/sae/yasaeng dongmul/haebyeon/naksi/seom/baenori/bada/gang/hosu/deulpan/yeonmot) | waterfall/mountain/forest/bird/wildlife/beach/fishing/island/boating/sea/river/lake/field/pond | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.8, pp.143-144. |
| nagyeopgugyeong/nungugyeong/kkotgugyeong | "watching the leaves turn"/"watching the snow"/"watching the flowers" | nouns (compound, seasonal-activity) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.8 p.145; each names the ACTIVITY of observing a seasonal phenomenon as its own lexical compound — no English equivalent this systematic across three seasons. |
| hallyu (additional detail) | the "Korean Wave" | noun (cultural keyword) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.8 p.147-148; adds that Koreans/other Asians coined the term themselves, scope covers music/film/drama collectively. |
| PC bang/jungdok/geim/gyeonggi/jigeop | "PC room" (cyber café)/addiction/game(s)/tournament/career (professional gaming) | nouns | core/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.8 p.148-149; covers professional Starcraft leagues, gaming-addiction health risks, PC-bang ubiquity as youth hangout — beyond `030`'s bare mention. |
| yeoboseyo [name]eyo/ieyo | "Hello, this is [name]" — phone self-identification | phrase template | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.9 p.153; vowel-final name takes -eyo, consonant-final takes -ieyo. |
| sillyejiman nuguseyo?/jal andeullyeoyo/dasi malsseum hae juseyo/cheoncheonhi malsseumhae juseyo/joesonghaeyo, jega beonhoeul jalmot georeoseoyo | "Pardon, who is this?"/"I can't hear you well"/"please say that again"/"please speak slowly"/"sorry, wrong number" | phrases (telephone etiquette) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.9 p.152-153; full phone-trouble phrase set. |
| iseoyo/gyesimnida (telephone/office presence) | "[person] is here" — informal/formal honorific pair, reporting presence | phrase pair | core/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.9 p.154, reused Ch.10 p.169-171; gyesimnida for a higher-position/elder referent, iseoyo for peer/subordinate; negated pair eopseoyo/angyesimnida given symmetrically. A genuinely new PRESENCE-reporting honorific axis, distinct from verb-substitution/noun-doublet patterns in `031`. |
| jip/daeg (telephone-politeness reuse) | "house" (plain) vs. "house" (respectful, of/to a senior) | noun (honorific doublet, reused) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.9 p.159; same 집/댁 doublet as the Ch.1-3 chunk's daek, reapplied to the phone/home-addressing context. |
| [name]ssikkeseo jarie gyesimnikka?/angyesimnida | "Is [name] there?" (formal, business)/"[name] is not at his/her place" | phrase template | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.9 p.155-156; business-contact register, contrasted with casual home-calling. |
| meseji jeonhae deurilkkayo?/meseji namgyeodo doegetseumnikka?/jega jeonhwa haeseotdago jeonhaejusipsiyo | "Shall I take a message?"/"May I leave a message?"/"Please tell them I called" | phrases (business register) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.9 p.156-158; split by business vs. home-call context. |
| jiyeok beonho/hyudaepon/haendeupon | area code/cellphone (lit. "carry-around phone")/cellphone (lit. "hand phone") | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.9 p.152; two near-synonymous Konglish-descriptive compounds for "cellphone." |
| Mail/shipping (pyeonji/yeopseo/ucheguk/upyo/gajang ssan upyeon/gajang ppareun upyeon/hanggong upyeon/jisang upyeon/deunggi upyeon) | letter/postcard/post office/stamp/cheapest mail/fastest mail/air mail/surface mail/registered mail | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.9 p.159-160. |
| Office supplies/equipment (bolpen/chaek/gomubaendeu/gongchaek/hochikiseu/hyeonggwangpen/jongi/keullip/munseo/pyeonjibongtu/seoryu/seukachi teipeu/sseuregitong/syapeu/yeonpil/boksagi/peurinteo/peurojekteo) | ballpoint pen/books/rubber band/notebooks/stapler/highlighter/paper/clip/documents/envelope/papers/Scotch tape/wastebasket/mechanical pencils/pencils/copier/printer/projector | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Tables 10-1/10-2, pp.166-168. |
| Business titles (sajang/busajang/gwajang/bujang/chajang/daeri/timjang + -nim suffix) | president/vice president/section chief/department chair/vice chief/representative-assistant/team leader (+ honorific address suffix) | nouns (titles) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 p.170; never address a superior by first name — family/full name + title (+ -nim) only. |
| [noun]i/ga eodie itseumnikka? (formal register) | "Where is ___?" (formal-polite office register) | phrase template | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 p.166, 171-172; chapter deliberately uses formal-polite throughout office/business sections, contrasted with informal-polite elsewhere. |
| hoesik/cha (il cha/i cha) | company dinner/"round" (of drinking-socializing — first, second round) | nouns (business-culture) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 p.174-175; sequential "rounds" (dinner→bar→karaoke bar) as a named, countable social unit. |
| hanjan badeusijyo?/janeul dollinda | "Would you like a shot?"/"passing the shot glass" (communal drinking ritual) | phrase/noun (ritual) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 p.175; one glass shared/refilled, pour-cue gesture (right hand on glass, left propping the arm, swaying to signal wanting a pour). |
| Drinking etiquette toward seniors | two-handed pouring; receiving a shot with both hands from a senior; turning one's head away while drinking | grammar/cultural construction | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 p.175-176; procedural detail beyond `030`'s bare geonbae mention. |
| sureul anmasimnida/sureul deo mot masimnida | "I don't drink"/"I can't drink any more" (formal-polite refusals) | phrases | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 p.176; co-workers may not take no for an answer. |
| Housing categories (dandok jutaek/yeollip jutaek/apateu/wollum) | single-family house/row house/apartment/studio ("one-room") | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 10-3, p.176; first systematic housing-type table. |
| jongnyangje sseuregi bongtu/eumsingmul sseuregibongtu | government-mandated size-regulated trash bags / separate food-waste trash bags | nouns (regulatory) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 p.176 sidebar; Korea's mandatory pay-per-bag trash system. |
| Korean bathroom culture (no shower curtains, floor drainage, plastic slippers, bathtub rarely used, manual boiler activation) | — | cultural practice | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 pp.176-178; distinct from the shoes-off/ondol floor-heating note below (Chapters 17-20 section) — this is bathing/plumbing specifically. |
| Around-the-house vocabulary (daemun/hyeongwan/geosil/anbang/chimsil/seojae/bang/bueok/hwajangsil/beranda/changgo/byeokjang/otjang) | gate/entrance/living room/main (master) bedroom/bedroom/study/room/kitchen/bathroom/veranda/storage/wall closet/wardrobe closet | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 10-4, pp.177-178; first systematic room-vocabulary table. |
| annyeonghi jumuseyo/jal jayo (sleepover reuse) | "sleep well" (honorific) / "sleep well" (plain) | phrase pair | formal/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 p.184; same pair as the Chapters 17-20 annyeonghi jumuseyo/jaljayo, here in a houseguest context — confirms the same-location restriction applies broadly. |
| Cleaning/laundry vocabulary (cheongso/jeongni/seolgeoji/gomujanggap/haengju/geollae/rakseu/bitjaru/sseurebaji/daegeollae/meonji/ppallae/setakgi/geonjogi/sejae) | clean/organize/wash dishes/rubber gloves/dishcloth/floor rag/bleach/broom/dustpan/mop/dust/laundry/washing machine/dryer/detergent | nouns/verbs | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 10-5, pp.186-187; first systematic cleaning-vocabulary table. |
| ttureoppeong | makeshift "plunger" (lit. "thing that unclogs") | noun (ad-hoc descriptive compound) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.10 p.188; Korean has no dedicated word for "plunger" — described functionally, a productive descriptive-compounding strategy for a lexical gap. |

### Grammar points

**A second honorific-presence pair layered onto the workplace/telephone domain.** iseoyo/gyesimnida
("is here") and negatives eopseoyo/angyesimnida — a dedicated PRESENCE-reporting honorific pair keyed
to whether the referent outranks the asker, structurally distinct from honorific-verb-substitution
and honorific-noun-doublet patterns already in `031` and the Chapters 1-3 section — a third honorific
axis (Ch.9 p.154, Ch.10 p.169-171).

**Register-switching is explicit and chapter-scoped in this source.** The book explicitly tells the
reader it will use formal-polite throughout Ch.10's office/business sections, then explicitly
switches back to informal-polite for the houseguest section of the same chapter — an author-flagged,
section-scoped register switch worth noting as a presentational pattern (Ch.10 p.165-166, 175).

**"Rounds" (cha) as a countable social-drinking unit.** Each venue change in a business-dinner outing
is a numbered cha (il cha, i cha...) — a structural social concept with its own counting vocabulary
(Ch.10 p.174).

---

## Vocabulary: Chapters 11-13 (Money; Asking Directions; Staying at a Hotel)

**Coverage note.** Checked against distinctive terms (jjimjilbang, minbak, yeogwan, supyo, hyeongeum
jigeupgi, ondol, sinhodeung, jjok). **Skipped as redundant:** the bare ondol/ondolbang concept
(`014`), the bare jjimjilbang gloss with its 24-hour/~$10 note (`030` p.43) — kept only this book's
additional detail not in `030`. The single direction word tongjjok "east" trivially overlaps `033`,
but the full jjok-suffix direction table is new. **Kept in full as genuinely new:** the complete
Korean currency denomination system, the full formal/informal bank-ATM-payment phrase pairs, the
card-installment system (culturally distinct from US norms), the "leave a friend as collateral" idiom,
the i/ga-insertion locative-question rule, the distance/time mixed-numeral-system split, the
finger-pointing and perspective-taking direction-giving etiquette, the Namdaemun-gate-arson cultural/
historical aside, the full accommodation-type taxonomy, traditional-bedding vocabulary/etiquette, and
the hotel complaint/checkout phrase sets. Repeated "Fun & Games" drills skipped.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| don | money (general) | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.11 p.191 opener. |
| il won/sip won/osip won/baek won/obaek won/cheon won/ocheon won/man won | 1/10/50/100/500/1,000/5,000/10,000 won denominations | nouns (currency) | core | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | p.191-192; full physical-description + rough-USD-equivalent for each coin/bill; explicit cross-cultural size/color comparisons to US coins. |
| supyo/sipman won/osipman won/baekman won | bank-issued "special check" (pre-printed denomination) / its ~$100/$500/$1000 sub-denominations | nouns (financial instrument) | core | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | p.192; NOT like a US personal check — amount fixed at issuance by the bank; US personal checkbooks nearly unusable in Korea (p.201). |
| eunhaeng/hyeongeum/kadeu | bank/cash/credit card | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.191. |
| [number]beon sonnim [number]beon changguro osipsiyo | "Will customer number [N] please come to counter [N]?" (bank-teller formal register) | phrase template | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.192-193; bank tellers default to formal polite AND Sino-Korean numbers even though the customer may answer informally — an institutional-register asymmetry. |
| hwanjeoneul hago sipseumnida/hago sipeoyo | "I would like to exchange currency" (formal/informal pair) | phrase pair | formal/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.193. |
| dalleoreul wonhwaro bakkwo jusipsiyo/juseyo | "Please exchange dollars for won" (formal/informal pair) | phrase pair | formal/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.193. |
| dalleo dae wonhwa hwannyuri eotteoke doemnikka?/doeyo? | "What is the exchange rate for dollar to won?" (formal/informal pair) | phrase pair | formal/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.193; hwannyul "exchange rate" as a standalone item. |
| sasilttae/pasilttae | "when buying"/"when selling" (bank exchange-rate framing) | adverbs | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.194; banks quote a buy/sell spread using this pair. |
| hyeongeum jigeupgi/susuryo | ATM (lit. "cash withdrawal machine")/surcharge-fee | nouns | core | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | p.196; some ATMs show Korean-only menus; deposit/yes button conventionally top-right. |
| kadeureul neoheo jusipsiyo/bimilbeonhoreul imnyeok hasipsiyo | "Please insert your card"/"Please enter your 4-digit PIN" (ATM formal polite) | phrase | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.196-197; ATMs default to formal polite even though no human speaks — register extended to machine-generated speech. |
| ilsibullo haedeurilkkayo?/halburo haedeurilkkayo?/halburo myeot gaewollo haedeurilkkayo? | "Full amount at once?"/"...in installments?"/"How many monthly installments?" | phrase set | formal | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | p.199-200 sidebar; Korean card culture allows installments even for ordinary purchases like groceries, unlike US norms. |
| i kadeu badeuseyo?/i kadeuneunnyo? | "Do you take this card?"/"What about this card?" (fallback) | phrase pair | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.200. |
| i chingureul damboro matgyeonoko jamkkan don ppobeureo gatda olkkeyo | "I'll leave my friend here as collateral while I go withdraw some money" | phrase (idiom) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.200-201; a real usable phrase for a no-ATM/card-declined emergency. |
| jigap | wallet/purse | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.195; single word covers both referents, unlike English's two words. |
| eodi itjyo? (+-i/-ga insertion rule) | "Where is it?" — general locative question template | phrase template + particle rule | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.12 p.204-205; -i after consonant-final noun, -ga after vowel-final noun, before eodi itjyo?. |
| sillyehamnida/sillyehajiman | "excuse me" (standalone) / "excuse me, but..." (prefacing a request) | phrase pair | core/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.205; functional distinction, not free variants. |
| yeogiseo meongayo?/yeogiseo gakgaungayo? | "Is it far from here?"/"Is it near here?" | phrase pair | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.205-206. |
| jjok-suffix direction system (apjjok/dwijjok/bandaejjok/bukjjok/namjjok/dongjjok/seojjok/oenjjok/oreunjjok +ijjok/jeojjok) | front/back/opposite/north/south/east/west/left/right side (+"this way"/"that way") | nouns (productive suffix) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Table 12-1, p.207; full paradigm + "way" extension new; only dongjjok trivially overlaps `033`. |
| taeksi/beoseu/jihacheol | taxi/bus/subway | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.206. |
| yeogiseo eolmana meoreoyo?/yeogiseo eolmana gakkawoyo? | "How far is it from here?"/"How near is it from here?" | phrase pair | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.209; metric only, never miles; distances use Sino-Korean numerals, but walking-time estimates split hours (native-Korean) from minutes (Sino-Korean) — a third domain for the mixed-numeral-system pattern. |
| ape/dwie/golmok/sageori/sipjaro/sinhodeung/yeope | in front/behind/alley/4-way intersection/crossroad/traffic light/next-to | nouns (landmark vocabulary) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.206-211. |
| daeume | "afterward, and then" (sequencing connector) | adverb/connector | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.209-210; chains sequential direction steps. |
| namdaemun | "the South Gate" — historic Seoul landmark; destroyed by arson Feb 10, 2008 | proper noun (historical keyword) | core | — | contemporary as of 2008 publication | Seoul | local | grammar_reference | n/a | n/a | p.210-211; a dateable historical reference unique to this source. |
| (pointing etiquette) | pointing directly at a person is rude/accusatory; point with an open hand instead | cultural-pragmatic note | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.204-205. |
| (perspective-taking in directions) | Koreans conventionally gesture as if looking from the LISTENER's perspective, not their own | cultural-pragmatic note | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.210. |
| hotel/yeoinsuk/minbak/yeogwan/yuseuhoseutel | hotel/Korean motel/bed-and-breakfast/mid-tier motel/youth hostel | nouns (accommodation taxonomy) | core | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | Ch.13 p.215-219; full relative-tier taxonomy; yeogwan does not pluralize the way English adds "-s." |
| jjimjilbang (additional detail) | 24-hour sauna complex with hot/ice/fire rooms and heated sleeping floor | noun (cultural institution) | core | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | p.217-218; adds the ticket→shower→T-shirt/shorts→communal-room routine and the note that owners don't track overnight guests. |
| yo/ibul/ibuleul gaeda | thick folding floor mattress/blanket/"to fold the blanket" | nouns + set phrase | core | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | p.216; self-folding bedding framed as optional-but-impressive guest etiquette. |
| oncheon | natural hot spring | noun | core | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | p.216-217. |
| bangeul yeyakharyeogo haneundeyo/binbang iseoyo?/harutbame eolmaeyo? | "I want to reserve a room"/"Do you have vacancies?"/"How much for one night?" | phrase set | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.220-221. |
| kkaekkeutan/ssan/joeun/gakkaun | clean/cheap/nice/nearby | adjectives | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.219-220. |
| [item] jom gochyeo juseyo / [item]i/ga gojang naseoyo | "Please fix [item]"/"[item] is broken" | phrase templates | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.226-227; explicit animacy restriction — flagged inapplicable to a noisy human neighbor. |
| yeop bangi neomu sikkeureowoyo | "The next room is too loud" (correct noisy-neighbor phrasing) | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.227. |
| bangi neomu [deowoyo/chuwoyo/deoreowoyo/jagayo/sikkeureowoyo] | "The room is too [hot/cold/dirty/small/noisy]" | phrase template + adjectives | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.227-228. |
| badagi neomu tteugeowoyo/chagawoyo | "The floor is too hot"/"too cold" (ondol-specific) | phrase pair | core | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | p.228; floor temp independent of ambient air temp. |
| myeotsie bangeul biwoya doeyo?/gyesan halkkeyo/gyesanseoga jal mot doengeot gateunndeyo | "What time do I need to check out?"/"I'd like to pay the bill"/"I think there's a mistake on the bill" | phrase set | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p.228-229. |

### Grammar points

**The i/ga locative-question insertion rule.** Taught as the key to an open-ended "where is the
[noun]?" question family, not just an isolated rule (Ch.12, p.204-205).

**Institutional/machine register defaults to formal polite regardless of human presence.** Bank
tellers and ATM menu text both default to formal polite as institutional convention, extending the
honorific/politeness system (`031`) into a distinct institutional-context rule — notably applying even
to machine-generated text with no human interlocutor (Ch.11, p.192-193, 196-197).

**Mixed Sino-Korean/native-Korean numeral split, extended to walking-time distance estimates.**
Confirms and extends the split already flagged (months vs. clock-hours): metric distances use
Sino-Korean numerals, but the same distance expressed as walking/driving time splits hours
(native-Korean) from minutes (Sino-Korean) — the numeral system tracks the TIME-UNIT, not the general
domain (Ch.12, p.209).

**Animacy restriction on an otherwise general-purpose "is broken" complaint template.** [item]i/ga
gojang naseoyo generalizes to any noun, but is explicitly flagged wrong/absurd applied to a noisy
human neighbor despite being syntactically well-formed (Ch.13, p.226-227).

---

## Vocabulary: Chapters 14-16 (Transportation; Planning a Trip; Handling an Emergency)

**Coverage note.** Checked against prior established files and against the sibling Chapters 4-7
section (same book). **Skipped as redundant:** the seasons/months/days/clock-hours tables (already
captured from this same book's Ch.4/7 above — this chapter reprints them); saram sallyeo!/dowajuseyo
(`032` p.59, same gloss); chitsol/yeogweon (already in the Chapters 1-3 section); country-name entries
duplicating the Ch.4-7 table. **Kept because genuinely new:** the full systematic body-parts table (26
items — prior corpus hits are only crude/slang-register terms in `030`, never a systematic anatomical
list); the medical-ailments table (17 conditions) and medical/emergency terms table (14 items), zero
prior overlap; Eastern-medicine keywords (zero prior overlap anywhere); the full Korean national-
holidays table (10 holidays, prior files only name Chuseok/Seollal in passing); the Chinese zodiac
animal-year table (12 animals +-tti suffix, confirmed zero prior hits despite an initial false-positive
grep match); police/crime vocabulary and the emergency-call register; the delta of new country names
not already in the Ch.4-7 table; sightseeing-site vocabulary distinct from the Ch.4-7 shopping-
district set; the BBB interpretation hotline and Goodwill Guide tour service.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| gonghang/daejung gyotong | airport/public transportation | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.233-234. |
| yeogwon/yeohaeng gabang/yeohaeng iljeong | passport/travel bag/travel itinerary | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.234, check-in checklist. |
| baenang/jwaseok beonho/pyeon beonho/tongro/changmun | backpack/seat number/flight number/aisle/window | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 "Words to Know" p.237. |
| ipgukja simsadae/bija | Immigration/visa | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.238. |
| il gwangye/gwangwang/chinji bangmun | work-related/sightseeing/visiting family & friends | noun phrases (purpose-of-visit) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.238; the three standard answers to immigration's purpose-of-visit question. |
| son(eul deulda) | to raise one's hand (hailing a cab) | verb phrase (gesture) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.239. |
| jeo taeksi handaeman bulleo juseyo | Please call me a taxi | phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.239; for rural areas with no cab visible. |
| [place]-e deryeoda juseyo/[place]-kkaji ganeunde eolmaeyo? | Please take me to [place]/How much to go to [place]? | phrase templates | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.239-240. |
| gosok beoseu/sine beoseu/beoseu jeongnyujang | express bus/city bus/bus terminal | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.240; express buses only depart from a terminal, drivers don't give change. |
| chultoegeun sigan | rush hour (lit. "commute-to/from-work time") | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.241; the subway running late is a practical DUI-avoidance option after a noraebang night. |
| pyo/peulaetpom/pyundo/wangbokpyo/kaunteo | ticket/platform/one-way ticket/round-trip ticket/counter | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.14 p.244. |
| Argentina/Brazil/Egypt/Israel/Spain/Sweden/Taiwan/Vietnam (areujentina/beurajil/ijipteu/israural/seupein/seuweden/daeman/wollam) | — | nouns (proper, loanword country names) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.15 Table 15-5, p.258; delta against the Ch.4-7 country-name table. |
| -eseo (from)/-ro/-euro (to) | directional source/goal particles | particles | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.15 p.257-258; -ro after vowel-final place name, -euro after consonant-final. |
| bangmulgwan/geukjang/gongweon/gungjeon/haebyeon/jeol/misulgwan/san/singmulgwan | museum/theatre/park/palace/beach/temple/art gallery/mountain/botanical garden | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.15 Table 15-4, p.256; distinct from the Ch.4-7 shopping-district set. |
| Korean national holidays (New Year's Day, Seollal, Independence Movement Day, Buddha's Birthday, Children's Day, Memorial Day, Constitution Day, Liberation Day, Chuseok, National Foundation Day, Christmas) | — | reference table (dates + cultural descriptions) | core | — | contemporary (source published 2008); historical refs span 1919/1945/1948 and the legendary 2333 BCE founding date | — | national | grammar_reference | n/a | n/a | Ch.15 Table 15-2, p.252-254; first systematic holiday calendar in the corpus; several float on the lunar calendar. |
| olhae/jaknyeon/naenyeon/-nyeon | this year/last year/next year/"year" suffix | nouns/suffix | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.15 p.254; e.g. icheonpaillyeon = "2008." |
| Chinese zodiac animals +-tti suffix (baemtti/daktti/doejitti/gaetti/horangitti/juitti/maltti/sotti/tokkitti/yangtti/yongtti/wonsungitti) | Year of the Snake/Rooster/Pig/Dog/Tiger/Rat/Horse/Ox/Rabbit/Goat/Dragon/Monkey | nouns (productive suffix + root) | core | — | contemporary (source published 2008); 2008 = Year of the Rat | — | — | grammar_reference | n/a | n/a | Ch.15 Table 15-3, p.255; contrasted with the Western zodiac's monthly cycle; "taken less seriously than in the past" per the book. |
| myeotsieseo myeotsikkaji yeollyeo itnayo?/yeyak | From what time to what time are you open?/reservation | phrase/noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.15 p.255-256. |
| binu/bit/chiyak/hwajangpum/myeondogi/sajingi/shinbal/yangmal | soap/brush/toothpaste/makeup/razor/camera/shoes/socks | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.15 Table 15-6, p.259, packing-list vocabulary. |
| BBB (Before Babel Brigade) | volunteer phone-interpretation hotline — 2,400 volunteers, 17 languages, 1588-5644 | proper noun (service) | core | — | contemporary (source published 2008) | — | national | grammar_reference | n/a | n/a | Ch.15 p.259-260; distinct from the also-new Goodwill Guide free-tour/interpretation service (tongyeok, gongjja). |
| eunggeupsanghwang/keunil nasseoyo | emergency/"there's an emergency" (lit. "a big thing happened") | noun/phrase (idiom) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 p.263-264; literal-translation mismatch explicitly called out by the book. |
| somaechigi/kkangpae/doduk | pickpocket/thug/thief | nouns (crime) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 p.264; Korean police framed as generally very helpful/English-capable toward tourists. |
| pachulso/gyeongchalgwan/bogoseo | police station/police officer/(incident) report | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 p.264. |
| 119 (emergency number)/gyohwansu/banghyang/wichi | emergency dispatch number/operator/directions/location | proper noun/nouns | core | — | contemporary (source published 2008) | — | national | grammar_reference | n/a | n/a | Ch.16 p.264-265; book advises giving directions/location in Korean in case the operator doesn't speak English; stresses innaesim (patience). |
| gonggong jangso/yuwonji/keun baekhwajeom/yeogi bunsilmul bogwansiri iseyo? | public place/amusement park/large department store/"Is there a lost-and-found here?" | nouns/phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 p.266-267. |
| Basic body parts (bae/bal/balgarak/dari/deung/eokke/eolgul/gan/gaseum/geunyuk/gwi/ip/jang/ko/meori/mok/mom/nun/pal/pe/ppyeo/simjang/singyeong/son/songarak/wi) | stomach/foot/toe/leg/back/shoulder/face/liver/chest/muscle/ear/mouth/intestines/nose/head/neck/body/eye/arm/lung/bone/heart/nerves/hand/finger/stomach(organ) | nouns (anatomy) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 Table 16-1, p.270-271; first systematic anatomical table in the corpus. |
| Medical ailments (am/boktong/byeonbi/cheonshik/dokgam/dutong/gamgi/gohyeorap/gwanjeolyeom/A·B·C hyeong gannyeom/ijil/jeohyeorap/kolera/momsal/pyeryeom/seolsa/simjang mabi/yeol) | cancer/stomachache/constipation/asthma/flu/headache/cold/high blood pressure/arthritis/Hepatitis A·B·C/dysentery/low blood pressure/cholera/fatigue/pneumonia/diarrhea/heart attack/fever | nouns (medical) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 Table 16-2, p.271; zero prior overlap. |
| Medical/emergency terms (byeongwon/cheon/chim/eunggeupsil/gugeupcha/hangsaengje/hannyak/hyeorap/jusa/maekbak/ondogi/pi/susul/uisa/yak/yakguk/yaksa) | hospital/body temperature/acupuncture/emergency room/ambulance/antibiotics/herbal medicine/blood pressure/syringe/pulse/thermometer/blood/surgery/doctor/medicine/pharmacy/pharmacist | nouns (medical) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 Table 16-3, p.272-273. |
| chim/hanyak/buhang/ddeum | acupuncture/herbal remedies/cupping/moxibustion | nouns (Eastern-medicine cultural keywords) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 p.273; book frames dual Western/Eastern medical access as a point of pride. |
| gajik(ga-jok)/hwanja/jindan/simjeondo/ekseurei gigye | family/patient/diagnosis/EKG/X-ray machine | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 p.272-273; the book's own romanization "gajik" for 가족 is likely a typo (its own pronunciation guide gives "ga-jok") — flagged rather than silently corrected. |
| haru/hwe or beon/harue dubeon | a single day/"number of times" (two near-synonymous counters)/"twice daily" | nouns/phrase | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 p.274; dosage-instruction numeral+frequency-counter construction. |
| byeonhosa/daesagwan/yeongsagwan | lawyer/embassy/consulate | nouns | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.16 p.274-275; legal trouble framed as rare for tourists. |

### Grammar points

**Directional source/goal particles -eseo/-ro/-euro.** -eseo marks origin; the goal particle is -ro
after a vowel-final place name or -euro after a consonant-final one — the same allomorphy pattern
documented elsewhere, here applied to a travel-itinerary template (Ch.15, p.257-258).

**Body-part-pain construction extends the -i/-ga subject-particle allomorphy.** [body part]-i/-ga
apayo ("[part] hurts") — a new domain-specific application of an already-known particle rule, with the
explicit body-part+apeuda pairing new to this corpus (Ch.16, p.269).

**Numeral + frequency-counter (-hwe/-beon) for dosage instructions.** haru + number + hwe/beon
("X times a day") — a narrow, practically-motivated counter construction not previously captured,
since prior coverage focused on counters for people/objects rather than frequency (Ch.16, p.274).

---

## Vocabulary: Chapters 17-20 ("Part of Tens": quick-handle tips; things to avoid; favorite expressions; phrases that sound Korean)

**Coverage note.** Non-redundant-supplement check against `014_teach_yourself_korean.md`,
`030_dirty_korean_everyday_slang.md`, and `032_making_out_in_korean.md` (the only files with keyword
hits for ppalli/mollayo/gwaenchanayo/jugeullae). **Skipped as redundant:** the bare gloss of ppalli =
"quickly," mollayo = "don't know," gwaenchanayo = "it's okay," and the jugeullae "Do you want to die?"
My Sassy Girl note (`030` already has this almost verbatim). **Kept:** everything else — the book's
much richer example-sentence sets, register pairings (plain/informal-polite/formal-polite triplets),
and roughly 18 terms/expressions with zero prior overlap. **Chapter 17** ("Ten Ways to Get a Quick
Handle on Korean") is 100% non-linguistic resource/media advice (watch Korean movies/dramas, surf the
web, use a dictionary, make word lists, go to Korea) — zero vocabulary, zero grammar, skipped
entirely. **Chapter 18** ("Ten Things to Avoid Doing in Korea") is mostly non-lexical etiquette
(shoe removal, rice-bowl handling, seating hierarchy, PDA taboo), but contributes a handful of
genuinely new self-deprecation/humility set-phrases and cultural-lexical nouns, kept below; its
kkeseo/ssi self-reference-avoidance nuance is a new usage note on an already-tabulated particle
(-께서, in `031`) and is appended as a note rather than duplicated as a new row.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| animnida, animnida | "No, no, not at all" (self-deprecating compliment-deflection formula, said twice) | phrase | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.18 p.283. |
| maseun eopjiman / charingeon eopjiman / bujok hajiman | "although it doesn't taste good" / "although I haven't prepared anything much" / "although it has many shortcomings" (humble food-serving formulas) | phrases | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.18 p.283-284. |
| meoriga nappayo | "I'm not that smart" (self-deprecation) | phrase | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.18 p.284. |
| chaeksangdari | sitting cross-legged ("Indian style") on the floor | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.18 p.286; traditionally reserved for seniors/elders in formal gatherings — juniors knelt until told pyeonhage anjayo. |
| pyeonhage anjayo | "Please sit comfortably" (elder's formula releasing juniors from kneeling) | phrase | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.18 p.286. |
| sinbal an beoseodo doeyo / sinbal sineodo doeyo / sinbal sineodo gwaenchanayo | "You don't have to take your shoes off" / "You can wear your shoes" / "It's okay to wear your shoes" (three register variants waiving the shoes-off norm) | phrase set | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.18 p.286. |
| ondol | traditional floor-heating system (heated stone, now copper wire) | noun (cultural keyword) | core | — | contemporary (source published 2008) | South Korea | national | grammar_reference | n/a | n/a | Ch.18 p.285-286; explains the origin of the shoes-off/floor-sitting norm — distinct from the Ch.10 bathroom-plumbing note above. |
| jeongmal / jinjja / cham | "really" (jeongmal, jinjja) / "sure, really" (cham) | adverbs/interjections | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.19 p.289-290; jeongmal and jinjja usable standalone as full utterances ("Really."/"Really?"); cham intensifies an adjective (oneul nalssiga cham deopneyo "the weather is really hot today"). |
| a, geuraeyo / geuraeyo | backchanneling: "Ah, is that right?" / "That's right, exactly" | phrase pair | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.19 p.290-291; shows the listener is following along, NOT genuine questioning — the book names the sociolinguistic term "backchannelling" itself. |
| jamkkanmanyo / jamsimanyo | "one moment please" (jamsimanyo is the more formal of the pair) | phrase pair | core/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.19 p.291; jamsiman gidaryeo juseyo "Please wait one moment." |
| mwo haeyo / mwo haseyo | "What are you doing?/What's up?" (casual) / a slightly more formal variant | phrase pair | colloquial/core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.19 p.291. |
| joayo / joeuseyo | "good/Do you like it?" (plain) vs. the substitution required when addressing a senior with the same question | phrase pair | core/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.19 p.291-292. |
| jal doetneyo / jal doesseoyo (vs. bare doetneyo/doesseoyo) | "That turned out well" (positive) — WITHOUT jal in front, the same phrase means "that's enough" and reads as mildly negative/dismissive | phrase pair + trap | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.19 p.292; book flags this as an easy learner error — some people get offended if you drop jal when they offer you something. |
| jeoreon / ireon | exclamatory "Oh dear/oh my" (sympathetic reaction to someone else's misfortune) — homophonous with the demonstrative "like that"/"like this," disambiguated only by context | interjection/demonstrative (homophone pair) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.19 p.292; e.g. jeoreon ot hana juseyo "please give me clothes like that" vs. jeoreon, sarami dachyeotneyo "Oh dear, someone got hurt." |
| akkapda / akkawoyo / akkapnaeyo | "what a waste/that was close/what a pity" (plain vs. two informal-polite variants) | phrase (plain + 2 informal-polite forms) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.293-294; also used as a sportscasting "so close!" interjection; plain form most commonly used despite being "plain." |
| eojjeol su eopgun | "looks like I have no other choice" (resignation formula) | phrase | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.294. |
| geureonde itjanayo / geunde / itjana | "by the way, you know" discourse-marker cluster (geureonde contracts to geunde; itjanayo contracts to plain itjana) | discourse markers | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.294-295; used to open sentences and make them "sound natural." |
| jom | contraction of jogeum "a little"; functions as adverb ("a little") vs. as "please" when used adjectivally in a request | adverb/discourse particle | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.295; eumsigi jom maewoyo "the food is a little spicy" vs. yeogiseo gyesan jom haejuseyo "could you please take care of the bill." |
| jjajeungnanda / jjajeungnayo | "that's irritating/annoying" (plain, the form Koreans actually use) vs. an informal-polite form the book notes is NOT typically used | phrase pair (register-restricted) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.295; restricted almost entirely to self-talk/close friends — explicitly not for use near a boss. |
| jukgetda (idiom family): deowo jukgetda / pigonhae jukgetda / baebulleo jukgetda / massiseo jukgetda / jukgo sipda / ai ttaemune jukgetseyo | hyperbolic "I feel like dying" intensifier: so hot/tired/full I could die; tastes so good I want to kill myself; I want to die; "my kid is killing me" (informal polite) | phrase family (hyperbolic intensifier) | colloquial/taboo-adjacent | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.296-297; more productive than the parallel English "dying"/"to die for" idiom; jugeo/jugeullae? used as an idle, often-joking threat among close friends ONLY (My Sassy Girl reference, cf. `030`) — book explicitly warns never to joke with jukda toward a senior/older person. |
| kkeunnaejunda / kkeunnaejunaeyo | "that's awesome/amazing" (plain form dominant; informal-polite rarely used) | phrase pair (register-skewed) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.297; bunwigiga kkeunnaejunda "what an awesome atmosphere." |
| neukkihada / neukkihaeyo | primary sense "oily/greasy" (fast food, burgers); extended sense: a PERSON's behavior as unnaturally/uncomfortably smooth or overly charming, to the point of making onlookers queasy | adjective (polysemous, gendered extended sense) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.297-298; book explicitly states the extended sense is used ONLY to describe men, never women; closest English analogue offered is "saccharine." |
| siwonhada / siwonhaeyo | "cool, refreshing" literally (breeze, cold drink), extended to a broad "catharsis" sense (a long-awaited rainstorm, an uncongested drive, a shot of tequila, watching a disliked person get in trouble, scratching an itch, stretching, leaving a sauna, hot tea) | adjective (polysemous) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.298-299; book frames this as "like having a breeze lift your spirits" — contrast the narrower weather-only siwonhaeyo gloss in the Ch.4-7 section above. |
| sugohaeyo / sugohasipsiyo | "keep up the good work" (informal polite, for people you know well) vs. the formal-polite form required around seniors | phrase pair | core/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Ch.20 p.299; compare the register-neutral sugohaseyo drawn from this same book's Chapter 3 (see Chapters 1-3 section above). |

**kkeseo/ssi usage-note addendum (not a new row — append to existing `031` rows for -께서/-씨).** This
book explicitly warns never to use -께서 (kkeseo) or -씨 (ssi) when speaking of ONESELF — doing so reads
as sarcasm. Both apply to either gender; kkeseo specifically pairs with an action/statement by the
honored person (e.g. seonsaengnimkkeseo oneul jibe oseyo "The teacher is coming to the house today")
(Ch.18, p.285).

### Grammar points

**Productive plain/informal-polite/(formal-polite) idiom paradigm extends to highly colloquial/slang
predicates.** Nearly every expression above is shown in at least two register forms built on the same
predicate stem (jukgetda/jukgetseyo; akkapda/akkawoyo/akkapnaeyo; kkeunnaejunda/kkeunnaejunaeyo;
neukkihada/neukkihaeyo; siwonhada/siwonhaeyo; sugohaeyo/sugohasipsiyo; joayo/joeuseyo). This
demonstrates that the core honorific/politeness-register system (`031`) productively extends even to
slangy predicates, not just "dictionary" vocabulary — several forms (jjajeungnayo, kkeunnaejunaeyo)
are attested as grammatically well-formed but near-unused in practice, i.e. the morphological slot
exists but real usage skews heavily toward one register per item. This per-item register-skew pattern
on slang vocabulary specifically is new to this project's honorific documentation (Ch.19-20).

---

## Vocabulary: Appendix A (Korean Verbs) & Appendix B (Mini-Dictionary)

**Coverage note — near-total skip.** Appendix A is a flat alphabetical list of ~150 dictionary-form
verbs with a bare English gloss each — despite its title it does **not** mark irregular-conjugation
class membership at all (no ㅂ/ㄷ/ㅅ/ㅎ/르/ㄹ/으-irregular tagging, no conjugated forms shown).
`018_korean_grammar_intl_learners_part1.md` already gives a far deeper, systematically classed
irregular-verb catalogue with worked conjugation examples — **fully skipped**. Appendix B is a
~1,000-entry generic alphabetical Korean-English glossary, bare headword+romanization+gloss, no usage
notes, no example sentences, no register/regional tags — duplicating the function of `026`-`029`
almost entirely. **Fully skipped as bulk vocabulary**, per the spec's explicit allowance for a
near-empty table on a high-overlap chunk; bulk-copying ~1,000 generic entries would also violate the
copyright-discipline rule against reproducing a dictionary's content wholesale. **Kept — the only
genuinely new item class found:** a handful of homophone/polysemy notes where the book explicitly
flags that a single romanized form covers unrelated meanings "depending on context" — distinct from
`029`'s analogous note for a single polysemous *word family* (him "strength/power/courage"), these
are true homophone sets spanning unrelated etymological sources.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| dari (da-ree) | "leg" or "bridge" — unrelated referents, disambiguated only by context | noun (homophone pair) | core | — | contemporary (source published 2008) | — | — | dictionary | n/a | n/a | Appendix B, p.308. |
| il (il) | "a day," "work," or the number "one" — three unrelated senses, one romanized form | noun (homophone set) | core | — | contemporary (source published 2008) | — | — | dictionary | n/a | n/a | Appendix B, p.309. |
| jeol (juhl) | "a Buddhist temple" or "a formal [deep] bow" — unrelated referents | noun (homophone pair) | core | — | contemporary (source published 2008) | — | — | dictionary | n/a | n/a | Appendix B, p.309; the bow sense connects to the formal-greeting/hierarchy material already documented in `001` and this file's Chapters 1-3 section, though the book doesn't make that connection itself. |
| i (ee) | "two" or "tooth" — unrelated referents | noun (homophone pair) | core | — | contemporary (source published 2008) | — | — | dictionary | n/a | n/a | Appendix B, p.309. |
| jida (jee-da) | "to be defeated," "to fade," or "to cast a shadow" — three senses from one verb form | verb (homophone set) | core | — | contemporary (source published 2008) | — | — | dictionary | n/a | n/a | Appendix B, p.310. |
| jjada (jja-da) | "salty" (taste adjective) or "to squeeze/press/extract" (verb) — cross-category homophone | adjective/verb (homophone pair) | core | — | contemporary (source published 2008) | — | — | dictionary | n/a | n/a | Appendix B, p.310; notable for crossing a part-of-speech boundary, unlike the other pairs here. |
| ju (joo) | "main part," "vermillion," "a state/province," "a continent," "a stock/share," or "a week" — six-way homophone cluster | noun (homophone set) | core | — | contemporary (source published 2008) | — | — | dictionary | n/a | n/a | Appendix B, p.310; the largest single homophone cluster found in this appendix. |

*(No grammar points for this appendix — it contains no paradigm or explanation beyond the already-
far-better-documented irregular-verb material in `018`.)*

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes, dialogue
blocks, or explanatory prose. The appendix's ~150-entry verb list and ~1,000-entry mini-dictionary
were deliberately NOT bulk-copied, consistent with this rule and with the coverage rule's allowance
for a legitimately sparse table on a high-redundancy chunk. See `00_Reference_Extraction_Spec.md`.
