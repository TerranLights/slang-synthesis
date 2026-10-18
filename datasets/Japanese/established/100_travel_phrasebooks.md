# Japanese — Established Vocabulary/Grammar: Travel Phrasebooks (Rough Guide)

**Source:** T. Yahata Hyland & Kumi Liley (compiled by Lexus), *The Rough Guide Japanese
Phrasebook* (updated edition, Rough Guides Ltd, 2006; first published 1998, revised 2001), 308pp.
Sections sampled: Basic Phrases (pp. 8–12), Scenarios 1–16 (pp. 13–28), Japanese→English
dictionary opening "Colloquialisms" box (pp. 176–177) and a representative dictionary page range
(pp. 178–180), Japanese→English: Signs and Notices (pp. 214–216), Menu Reader: Food (pp. 237–240),
How the Language Works: Masculine and Feminine Forms of Speech and Counting (pp. 284–287).

**Coverage note:** This is a 308-page general travel phrasebook-dictionary (mostly an A–Z double
dictionary plus topical sign/menu glossaries), not a grammar textbook — per the extraction spec's
"representative sampling" guidance for this genre, this file samples across the book's topical
sections rather than transcribing the full dictionary, with one deliberate exception: **the book's
own self-described "slang and colloquialisms" section is extracted in full** (it is short — ~25
terms — and the book's own introduction flags it as the highest-value content for this project's
purposes: *"a dictionary ... of all the words and phrases you're likely to hear (starting with a
section of slang and colloquialisms)"*, p. 5).

**PDF extraction note (text layer, partial kanji loss):** `pdftotext` produces a clean, complete
text layer for all romaji transliteration and English gloss text throughout the book. However, the
embedded CJK rendering fonts used for the printed kanji/kana forms (`EOROIT+DIN-*` family, per
`pdffonts`) are CID Type 0C fonts **with no ToUnicode mapping** (`uni` column reads "no") — these
decode as meaningless glyph-box sequences (e.g. `xyz{|`) rather than real kanji, a different
failure mode from a 1:1 substitution cipher: there is nothing to decode, just no usable mapping.
Per the spec's CID-font guidance, this was treated as non-recoverable via text extraction for the
general dictionary and Signs/Menu Reader sections, so those entries below give **romaji + English
gloss only**, with kanji/kana marked unavailable. The **Scenarios section** (pp. 13–28) uses a
different, correctly-mapped font for its small vocabulary-box kanji, so those entries do carry
genuine kanji/kana. No vision-reading was performed on this source (not needed — the romaji/English
content fully serves the vocabulary-extraction purpose even where kanji isn't recoverable
text-layer); `Vision Reading Confidence` is therefore `n/a` throughout.

---

## Vocabulary

### Basic Phrases (pp. 8–9)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| hai | yes | interjection | core | — | contemporary (source published 2006) | — | — | dictionary | n/a | n/a | — |
| ie | no | interjection | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| oke | OK | interjection | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | loanword from English "OK" |
| sayonara | goodbye (formal) | interjection | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| dewa mata | goodbye (informal) | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| ja ne | goodbye (between friends) | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| ja, mata! | see you later! | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kon·nichi wa | hello | interjection | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| moshi-moshi | hello (on phone) | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | phone-specific greeting |
| ohayo gozaimasu | good morning | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | polite register |
| komban wa | good evening | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| osaki ni | good night (when leaving) | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | lit. "ahead of you" |
| oyasuminasai | good night (when going to bed) | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| onegai shimasu | please (requesting something) | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| arigato | thank you | interjection | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| honto ni arigato gozaimasu | thank you very much | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| ie kek·ko desu | no, thank you | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| do itashimashite | don't mention it | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| hajimemashite | how do you do? / nice to meet you | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| ogenki desu ka? | how are you? | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| okagesama de | I'm fine, thanks | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | lit. "thanks to you" |
| shitsurei shimasu | excuse me (to get past) | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| chot·to sumimasen! | excuse me! (to get attention) | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| gomen·nasai | excuse me/sorry | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| nante imashita ka? | sorry?/pardon me? | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| naruhodo | I see/I understand | interjection | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| wakarimasen | I don't understand | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| Eigo o hanasemasu ka? | do you speak English? | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| nihon·go wa hanasemasen | I don't speak Japanese | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| mot·to yuk·kuri hanashite kuremasen ka? | could you speak more slowly? | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| mo ichido it·te kuremasen ka? | could you repeat that? | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |

### Scenario vocab boxes (pp. 13–28) — kanji present where source renders correctly

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ginkō kōza (口座) | bank account | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 2: Banks |
| kōza bangō (口座番号) | account number | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| tesūryō (手数料) | commission (fee) | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| tōza yokin (当座預金) | current account | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| chochik(u) yokin (貯蓄預金) | savings account | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| shiten kōdo (支店コード) | sort code | noun | technical.finance | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| shawā | shower | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 3: Booking a room; loanword |
| furo tsuki / furo nashi | with/without bathroom | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| renta kā | rented car | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 4: Car hire; loanword |
| sōkō kyori wa musēgen | unlimited mileage | phrase | technical | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| hoken komi | insurance included | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| intānet·to kafe | Internet café | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 5: Communications; loanword |
| kētai (denwa) | mobile phone | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| rogu in | to log on | verb phrase | technical | — | contemporary (2006) | — | — | dictionary | n/a | n/a | loanword "log in" |
| dochira no hōgaku? | which direction? | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 6: Directions |
| futatsume no shingō o hidari | left at the second traffic lights | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| jiko | accident | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 7: Emergencies |
| kyūkyūsha | ambulance | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| taishikan | embassy | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| tasukete! | help! | interjection | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kon·nichiwa, o genki desu ka? | hi, how're you doing? | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 8: Friends |
| waruku arimasen | not bad | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| saikō | the best / awesome | adjective | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | exclamatory use, reinforcing it in Menu Reader as "excellent!" too |
| īne, ikimashō | cool, let's go | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| jyā ne | see you (casual) | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | casual variant of "ja ne" seen in Basic Phrases |
| kōsēbus·shitsu | antibiotics | noun | technical.medical | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 9: Health |
| byōki | ill | adjective | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| yak·kyoku | pharmacy | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| ikutsu ka no kotoba | a few words | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 10: Language difficulties |
| tsūyaku | interpreter | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kōkūbin | airmail | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 12: Post offices |
| kokunai (国内) | domestic | adjective | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kaigai/kokusai (海外/国際) | international | adjective | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kyokudome yūbin (局留め郵便) | poste restante | noun | technical | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kanjō gaki | bill | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 13: Restaurants |
| kono tochi no mēbutsu | it's a local speciality | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| saikō! totemo oishikat·ta desu! | excellent!, very nice! | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| o shiharai (お支払い) | cash desk | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 14: Shopping |
| bāgen sēru (バーゲンセール) | sale | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | loanword "bargain sale" |
| torikaeru (取り替える) | to exchange | verb | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| gaido tsuki no tsuā | guided tour | noun phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 15: Sightseeing |
| manseki desu | it's fully booked | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| norikaeru | to change trains | verb | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | Scenario 16: Trains |
| Shinkansen wa tokubetsu ryōkin | there's a supplement for the Bullet Train | phrase | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| saisyūdensha | last train | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |

### Colloquialisms (slang section, Japanese→English dictionary opening, pp. 176–177) — FULL EXTRACTION

The source's own header note (paraphrased): these are words you may well hear; the stronger ones
should not be used unless you're sure of your audience.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| aho! | fool! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | mild insult |
| baka! | you fool!, stupid bastard! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | book flags intensity variance |
| bakamitai | stupid | adjective | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| bakayaro! | damn fool! | interjection | taboo | — | contemporary (2006) | — | — | dictionary | n/a | n/a | book's "stronger" category |
| bijin | beautiful woman | noun | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| charinko | bicycle | noun | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| chikusho! | damn!, hell! | interjection | taboo | — | contemporary (2006) | — | — | dictionary | n/a | n/a | literally "beast" — taboo-avoidance/animal-based swearing |
| chot·to! | hey! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| damare! | shut up! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| domo | thanks; hi | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | clipped from "domo arigato" |
| gaijin | foreigner | noun | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | book presents as colloquial (vs. formal "gaikokujin") |
| ja ne | bye, cheerio | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | overlaps Basic Phrases entry |
| kak·ko i | trendy; cool; handsome | adjective | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kireru | blow one's top | verb | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | lit. "to cut/snap" |
| konoyaro! | damn fool! | interjection | taboo | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kuso! | shit! | interjection | taboo | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| maji de | honestly; really | adverb | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| mansatsu | ten-thousand yen note | noun | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| mashi | better | adjective | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| meshi | meal | noun | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | casual vs. core "gohan" |
| shinjiran·nai | unbelievable | adjective | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| subarashi! | fantastic! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| sugoi! | great!, super!; well done! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| tondemo nai! | no way! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| urusai! | shut up! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | lit. "noisy" |
| uso! | that's a lie! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| usotsuki! | liar! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| yada! | no!; yuk! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| yokat·ta! | good! | interjection | slang | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |

### Dictionary sample (Japanese→English, pp. 178–180, letters A–C) — representative

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ani | brother (one's own: older) | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| ane | sister (one's own: older) | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| abek·ku | lovers, a couple | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | loanword from French "avec" |
| at·chi e it·te! | go away! | phrase | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| arukoru-nuki (no) | non-alcoholic | adjective | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| baka (na) | silly; stupid | adjective | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | core/milder sense vs. the slang-box exclamatory forms |
| bakageta | ridiculous | adjective | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| boku (ga) | I (familiar, male) | pronoun | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | register note: marked "(fam, m)" in source |
| bimbo | poor | adjective | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| bunraku | traditional puppet theatre | noun | technical | — | contemporary (2006) | — | — | dictionary | n/a | n/a | cultural term |
| -chan | diminutive/familiar suffix | suffix | colloquial | — | contemporary (2006) | — | — | dictionary | n/a | n/a | added to child's name or between friends/family per source note |
| chuko (no) | second-hand | adjective | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |

### Signs and Notices sample (General Signs, pp. 214–215) — representative

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| otona | adult | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | kanji unrecoverable (CID font gap), romaji only |
| kodomo | child | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kiken | danger | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| nomimizu | drinking water | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| okotowari | ... forbidden | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | sign/notice register |
| an·nai | information | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| shibafu ni hairanaide kudasai | keep off the grass | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| tachiiri-kinshi | keep out | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kin·en | no smoking | phrase | formal | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| kuko | airport | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| Zen-Nik·ku | All Nippon Airways | proper noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | brand name |
| menzei-ten | duty-free shop | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |

### Menu Reader: Food sample (pp. 237–239) — representative

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| chawan | bowl | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | kanji unrecoverable (CID font gap) |
| hashi | chopsticks | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| chahan | fried rice | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| shoyu | soy sauce | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| teishoku | set meal | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| higawari-teishoku | set meal of the day | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| tonkatsu-teishoku | set meal with pork cutlet | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| tofu | bean curd | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |
| sukiyaki | beef and vegetables cooked with soy sauce at the table | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | dish name |
| tep·pan·yaki | beef and vegetables grilled at the table | noun | core | — | contemporary (2006) | — | — | dictionary | n/a | n/a | — |

---

## Grammar points

### Masculine and Feminine Forms of Speech (p. 284–285)

The source describes a historically stronger, now-softened but still real gendered split in
Japanese speech registers. Men traditionally spoke in a more even tone and used sentence-final
particles `yo`/`zo` for emphasis; women traditionally used a more lilting tone and the particle
`wa` for the same emphatic function, e.g. *boku wa Eigo ga hanaseru yo/zo!* ("I can speak
English!", said by a man) vs. *watashi wa okoto ga hikeru wa!* ("I can play the Japanese harp!",
said by a woman). Women also make heavier use of the polite prefixes `o-`/`go-` (e.g. `denwa` vs.
`odenwa` for "telephone") and of emotional interjections like `kawai!` ("cute!") and `suteki!`
("marvellous!"); women tend to say `ma!`/`ara!` on surprise where men say `ya!`/`o!`. This is a
directly register/gender-marked vocabulary split — directly relevant to this project's usage-tier
and derivation-mechanism tracking, since it shows the standard language itself encoding a
register axis that slang formation could plausibly invert or exaggerate later.

### Counting — dual numeral system (p. 285–287)

Japanese has two parallel sets of cardinal numbers 1–10: a native set (`hitotsu`, `futatsu`,
`mit·tsu` ... `to`) and a Sino-Japanese borrowed set (`ichi`, `ni`, `san` ... `ju`). The native set
is used for counting general objects without a classifier; the Sino-Japanese set is used with
time/quantity expressions and with numeral classifiers (`-dai` for machines/vehicles, `-hai` for
glassfuls, `-hiki` for animals, `-hon` for cylindrical objects, `-ko` for small round objects,
`-mai` for flat/thin objects, `-nin` for people, `-satsu` for books, `-tsu` for letters). Three
numbers (4, 7, 9) have alternative pronunciations depending on context (`yon`/`shi`,
`nana`/`shichi`, `kyu`/`ku`), with certain fixed time expressions requiring one specific variant
(e.g. `yoji` "four o'clock", not `*shiji`).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. The full-transcription exception taken above (the
Colloquialisms slang box) is a short (~25-term), purely factual glossary list, consistent with
this project's "extract every distinct vocabulary item" coverage rule for flagged
dialectal/register content, not a reproduction of protected prose. See `00_Reference_Extraction_Spec.md`.
