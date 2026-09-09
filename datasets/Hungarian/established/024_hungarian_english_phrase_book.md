# Hungarian — Established Vocabulary/Phrases: Hungarian-English Phrase Book (Davies)

**Source:** William Davies, *Magyar-Angol Társalgás / Hungarian-English Phrasebook* (Lexika
Tankönyvkiadó, Hungary; ISBN 963-7693-96-3; publication year not visible anywhere in the scanned
front/back matter — the copyright/imprint page carries only the ISBN, ordering code "LX-0018," and
the printer's name, no date), "30 Hungarian-English Phrase Book.pdf", all 161 PDF pages (printed
pages 1-161; the book's own pagination and PDF pagination coincide — no offset needed, verified
against the book's own Table of Contents, which is reproduced on the final PDF pages and gives page
numbers matching what appears printed at the top of each page). Organized topically (a
conversation/situation phrasebook, not a grammar course): General Expressions, The Family, The
Home, Eating, Services, Shopping, Health, Sport, The Weather, Travel, At a Hotel, Holidays-Camping,
Culture, Spare Time/Leisure, Sightseeing, and a closing Weights-and-Measures/reference section.

**Source-quality note — corrupted OCR text layer, not a clean one.** The dispatch for this
extraction described the text layer as "clean text, confirmed," but direct inspection shows this is
**not** the case: `pdftotext` pulls real, searchable text (there genuinely is a text layer, this is
not a vision-only scan), but the underlying OCR pass (this is a Canon-scanner-sourced PDF per its
`Creator` metadata) is **lossy, not a clean 1:1 font-substitution cipher** of the kind documented
elsewhere in this project's PDF-extraction gotchas. Hungarian's accented vowels (á, é, í, ó, ö, ő, ú,
ü, ű) collapse inconsistently onto plain digits and letters — most commonly "6" standing in for
*any* of é/á/ó/ő depending on the word (e.g. `R6g nem l6ttuk egym6st` for `Rég nem láttuk egymást`,
where the same glyph "6" represents both é and á in the same short sentence) — and ordinary Latin
letters get swapped too (`rn`↔`m`, `ii`↔`ű`/`ü`, `fi`↔various, `w`/`vv` artifacts, digit/letter
confusion). This is genuine OCR garbling of an old scan, not a decodable cipher, so **every phrase
in this file was reconstructed to standard Hungarian orthography** by cross-referencing the garbled
Hungarian against its parallel English gloss (always present, since this is a bilingual phrasebook)
and against known Hungarian vocabulary/grammar from this project's other established Hungarian
files. Confidence in each reconstruction is flagged per-row in the **Vision Reading Confidence**
column (repurposed here for OCR-reconstruction confidence, since the underlying mechanism — read
questionable source glyphs, cross-check against context, flag remaining doubt — is the same one that
column exists for): `verified` for extremely common, unambiguous phrases; `plausible_unverified` for
the majority, reconstructed with reasonable confidence from context but not independently
cross-checked against a second source; `low_confidence` reserved for the handful of rows flagged
below where a specific word's exact accentuation remains genuinely uncertain. **Transcription
Confidence is `n/a`** throughout (this field applies to subtitle/transcript sources, not reference
books, per the spec).

**Coverage note — representative sampling, not exhaustive transcription.** A 161-page phrasebook
with ~40 topical subsections contains on the order of several thousand individual phrase-pairs —
comparable in density to the numbers/frequency-table case the extraction spec calls out for
sampling rather than full transcription. Combined with the OCR-reconstruction overhead above
(every single phrase requires manual reconstruction, not a mechanical table read), full transcription
was not attempted. Instead, **8-15 representative phrases were pulled from each major topical
section**, prioritizing: (a) phrases distinct from what prior Hungarian `established/` files
(FSI Basic Course, Rounds' grammar) have already captured, (b) phrases carrying genuine
colloquial/idiomatic register distinct from neutral phrasebook "core," and (c) phrases illustrating
this book's own register/politeness system in use. Sections sampled: General Expressions
(Greetings, Understanding Each Other, Introducing People, Farewells, Arrangements, Invitations, Good
Wishes, Thanking People, Expressing Pleasure/Surprise, Opinions, Agreeing/Consenting, Disagreement,
Doubt/Worry/Surprise, Apologies/Regrets, Asking Questions), The Family, The Home, Eating (Breakfast,
Lunch, Evening Meal, At the Restaurant), Shopping (General Expressions), Health (General
Expressions, At the Doctor's), The Weather, Travelling by Rail, At a Hotel, Spare Time/Leisure (At
the Cinema, At the Theatre, Concerts and Operas), and Sightseeing. Sections not sampled directly
(Services/Laundry/Hairdresser, the food/clothing shopping sub-lists, Sport, City Transport, the
Border/Car/Garage sub-sections, Culture/Education, Radio/TV) were skipped for this pass given the
sheer volume of remaining topical ground and the effort already spent reconstructing OCR — a future
supplementary pass could mine these.

**Relationship to prior Hungarian `established/` files:** this is the first phrasebook-genre source
extracted for Hungarian (prior files are grammar references and a 1962 audio-lingual course). Its
value is almost entirely in **social/pragmatic register phrases** — politeness formulas, set
expressions for agreeing/disagreeing/apologizing, idiomatic exclamations — that a grammar reference
does not systematically cover. Overlap with the FSI course's `maga`/`ön`/`te` formality system exists
but this book's phrases are consistently `ön`/polite-register (3rd-person verb agreement), reflecting
a phrasebook's default assumption of a foreign tourist addressing strangers politely; no informal
`te`-register phrase was found except the two exclamatory farewells noted below.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Jó napot! | Good morning!/Good afternoon! | interjection | core | — | contemporary (source: Lexika Kiadó phrasebook, undated printing) | — | — | dictionary | n/a | verified | p. 5, Greetings. |
| Szia!/Szevasz! | Hello!/Bye-bye! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 5, Greetings — explicitly the informal counterpart to `Jó napot`, used with peers/friends; reappears as a Farewells entry (p. 9) meaning "Bye!" |
| Örülök, hogy látom. | Nice to see you. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 5. OCR: "Ortiltrt, hory ldtlak/liitom." |
| Rég nem láttuk egymást. | I haven't seen you for ages. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 5. Idiomatic time-expression, not a literal word-for-word translation of the English. |
| Hogy van?/Hogy vagy? | How are you? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 5; `van` = polite/`ön`, `vagy` = familiar/`te`, both given side by side. |
| Köszönöm, jól. | I'm fine, thank you. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 5. |
| Megvagyok. | Not too bad. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 5 — a hedged, understated answer to "how are you," more casual than `Köszönöm, jól`. |
| Mi újság? | What's the news?/What's up? | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 5. OCR "Mi 6jsdg?" — idiomatic greeting-question, not literal. |
| Beszél angolul? | Do you speak English? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 6, Understanding Each Other. |
| Igen, egy keveset. | Yes, a little. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 6. |
| Nem értettem. | I didn't understand/get that. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 6. |
| Beszéljen kérem lassabban! | Could you speak more slowly, please? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 6. |
| Tessék? (Hogy mondja?) | Sorry, what was that? | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 6/25 (recurs). `Tessék?` alone as a request-to-repeat is a very common colloquial reflex, distinct from `tessék` the offering/politeness particle already noted in the FSI file. |
| Mit jelent ez magyarul? | What's that in Hungarian? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 6. |
| Bocsásson meg a rossz kiejtésemet. | I apologise for my bad pronunciation. | phrase | formal | — | contemporary | — | — | dictionary | n/a | low_confidence | p. 7; OCR badly garbled ("Bocs6ssameg a rossz kieitF semet"), reconstruction plausible but the exact suffix on `kiejtésemet` not independently cross-checked. |
| Engedje meg, hogy bemutatkozzam. | May I introduce myself. | phrase | formal | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 8, Introducing People. |
| A nevem N. | My name is N. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 8. |
| Örülök, hogy megismertem. | Nice to meet you. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 8. |
| Melyik országból jött? | Where are you from? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 8. |
| Régi ismerősök vagyunk. | We have known each other for a long time. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 8. |
| Elnézést kérek. | Excuse me! | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 8. |
| Viszontlátásra! | Goodbye! | interjection | core | — | contemporary | — | — | dictionary | n/a | verified | p. 9, Farewells. |
| Jó utat! | Have a nice journey! | interjection | core | — | contemporary | — | — | dictionary | n/a | verified | p. 9. |
| Mennem kell. | I've got to go now. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 9. |
| Sietek. | I'm in a hurry. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 9. |
| Még nincs olyan késő. | It's not that late. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 9 — conversational pushback phrase used when someone claims they must leave. |
| Ne felejtsen el bennünket! | Don't forget us! | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 10. |
| Jöjjön el máskor is! | Come again! | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 10. |
| N-nel van megbeszélésem. | I have an appointment with N. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 10, Arrangements. |
| Hol találkozunk? És mikor? | Where shall we meet? And when? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 10. |
| Ráér ma délután? | Are you free this afternoon? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 12. |
| Kár! | What a pity! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | verified | p. 12; recurs throughout the book as a stock exclamation of mild disappointment (`De kár!`, `Milyen kár!`). |
| Szeretném meghívni a születésnapomra. | I'd like to invite you to my birthday party. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 12, Invitations. |
| Nagyon örülnék. | I'd love to! | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 12. |
| Nem rossz ötlet! | Good idea!/Not a bad idea! | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 12; also recurs in Agreeing (p. 18) as a stock approval phrase. |
| Már egy órája várok itt! | I've been waiting for you for an hour! | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | low_confidence | p. 13; complaining-register phrase, exact preposition/case ending on "itt" not fully cross-checked against OCR. |
| Jó pihenést! | Have a nice holiday. | interjection | core | — | contemporary | — | — | dictionary | n/a | verified | p. 13, Good Wishes. |
| Sok sikert kívánunk! | Good luck! | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 13. |
| Boldog születésnapot! | Happy birthday! | interjection | core | — | contemporary | — | — | dictionary | n/a | verified | p. 13. |
| Gratulálok! | Congratulations! | interjection | core | — | contemporary | — | — | dictionary | n/a | verified | p. 14. |
| Boldog új évet! | Happy New Year! | interjection | core | — | contemporary | — | — | dictionary | n/a | verified | p. 14. |
| Egészségére! | Cheers! | interjection | core | — | contemporary | — | — | dictionary | n/a | verified | p. 14 — toast phrase, lit. "to your health." |
| Igyunk a barátságunkra! | Here's to our friendship! | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 14 — a toast formula. |
| Mielőbbi gyógyulást! | Get well soon! | interjection | core | — | contemporary | — | — | dictionary | n/a | verified | p. 14. |
| Köszönöm szépen. | Thank you very much. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 14, Thanking People. |
| Nagyon hálás vagyok Önnek. | I am very grateful to you. | phrase | formal | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 15. |
| Nincs mit. | That's all right./Don't mention it. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | verified | p. 15 — standard response to thanks, distinct register from the fuller `Szóra sem érdemes`. |
| Szóra sem érdemes. | That's all right./Not worth mentioning. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 15. |
| Nagyon örülök! | I'm really pleased! | interjection | core | — | contemporary | — | — | dictionary | n/a | verified | p. 15, Expressing Pleasure and Surprise. |
| Pompás ajándék! | It's a wonderful present! | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 15; `pompás` recurs as a favorite intensifier throughout the book ("pompás idő," "pompás specialitás"). |
| Ez aztán meglepetés! | This is a real surprise! | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 15. |
| Csodálatos! | Marvellous!/Fantastic! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | verified | p. 15. |
| Mi a véleménye? | What's your opinion? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 16, Opinions-Viewpoints. |
| Mit gondol? | What do you think? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 16. |
| Véleményem szerint... | I think.../In my opinion... | phrase (fragment) | core | — | contemporary | — | — | dictionary | n/a | verified | p. 16. |
| Igaza van. | You're right. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 16. |
| Igen, így van. | Yes, that's right. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 17, Agreeing-Consenting. |
| Csakugyan!/Szavamra! | Indeed! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 17 — `Szavamra!` is a mildly archaic-flavored colloquial exclamation ("on my word!"). |
| Rendben. | All right! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | verified | p. 18. |
| Miért ne? | Why not? | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | verified | p. 18. |
| Nem mondok nemet. | I wouldn't say no. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 18 — idiomatic hedge, not a literal negation. |
| Számíthat rám. | You can count on me. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 19. |
| Köszönöm, nem. | No, thank you. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 19-20, Disagreement. |
| Ostobaság!/Hülyeség! | Nonsense! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 21 — flagged as colloquial/mildly blunt register; `hülyeség` skews toward informal-to-brusque, stronger than a neutral "that's wrong." |
| Micsoda szemtelenség! | What impertinence! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 21. |
| Szó sincs róla. | Not in the least. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | verified | p. 21/22 — idiomatic set phrase, recurs in both Disagreement and Doubt sections. |
| Ki van zárva. | That's out of the question. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | verified | p. 21 — idiom, lit. "it's locked out." |
| (Nekem) Mindegy. | It's all the same to me. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | verified | p. 21. |
| Semmi közöd hozzá. | It's none of your business. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | low_confidence | p. 21; OCR "Semmi kiSzehozz6" — reconstruction plausible via the English gloss but exact possessive-suffix form not independently confirmed. |
| Ez hihetetlen! | This is unbelievable! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | verified | p. 22, Doubt-Worry-Surprise. |
| Micsoda véletlen! | What a strange coincidence! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 22. |
| Nem találok szavakat! | I'm amazed! | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 22 — idiom, lit. "I can't find words." |
| Micsoda pech! | How unfortunate! | interjection | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 24 — `pech` is a German-loanword colloquialism ("bad luck"), notably informal register for a phrasebook. |
| Bocsánatot kérek. | I'm sorry/I apologize. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 23, Apologies-Regrets-Condolences. |
| Elnézést kérek a késésért. | Sorry I'm late. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 23. |
| Ez az én hibám volt. | The mistake was mine. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 23. |
| Bárcsak ne tettem volna. | I wish I hadn't done it. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 23 — conditional-mood regret construction. |
| Őszinte részvétem. | My condolences. | phrase | formal | — | contemporary | — | — | dictionary | n/a | verified | p. 24. |
| Ki az? | Who's there?/Who's that? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 24, Asking Questions-Enquiring. |
| Mi történt? | What happened? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 24. |
| Hogy jutok a pályaudvarra? | How can I get to the station? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 25. |
| Hol van a bejárat? | Where is the entrance? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 25. |
| Hogy hívják? | What's your name? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 36, The Family. |
| Van testvére? | Do you have any brothers or sisters? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 36. |
| Nős?/Férjnél van? | Are you married? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 36; gendered forms given separately (`Nős?` to a man, `Férjnél van?` to a woman). |
| Van gyereke? | Do you have any children? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 36. |
| Egy fiunk és egy lányunk van. | We have a son and a daughter. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 36. |
| A fiaim ikrek. | My sons are twins. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 37. |
| Özvegy. | Widow(ed). | adjective/noun | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 37. |
| Agglegény. | Bachelor. | noun | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 37. |
| Szerelmes vagyok. | I'm in love. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 38. |
| Szeretlek. | I love you. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 38. |
| Beleszerettem. | I've fallen in love. | verb (1sg past, reflexive-directional) | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 38; `bele-` "into" + `szeret-` "love" — a productive verbal-prefix pattern. |
| Jól néz ki. | S/he looks good/pretty. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 38 — casual appearance-commentary idiom, `néz ki` "looks (like)." |
| Gyászol. | S/he is mourning. | verb (3sg) | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 39. |
| Menyasszony vagyok./Vőlegény vagyok. | I'm engaged (to be married). | phrase | core | — | contemporary | — | — | dictionary | n/a | low_confidence | p. 38; OCR heavily garbled here ("Menyasszonyv agyok./ Y 6le- geny vagyoK"), gendered forms (bride-to-be/groom-to-be) reconstructed from context, exact word split not fully verified. |
| Hol lakik? | Where do you live? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 40, The Home. |
| Hányadik emeleten lakik? | Which floor do you live on? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 40. |
| A házunk egy nagyon csendes utcában van. | Our house is in a very quiet street. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 41. |
| Ad ki szobákat? | Do you rent out rooms? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 41. |
| Mekkora a havi bér? | What's the monthly rent? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 41. |
| Fáradjon be! | Come in! | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 41; polite imperative of `fáradni` used as a set "please come in" formula, distinct from a bare imperative. |
| Foglaljon helyet! | Sit down!/Take a seat! | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 41; recurs from FSI's `helyet foglalni` idiom, here as a polite imperative. |
| Szeretnénk reggelizni. | We'd like to have breakfast. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 53, Breakfast. |
| Nagyon finom. | It's very nice./It's delicious. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 54. |
| Túl magas a vérnyomásom. | My blood pressure is too high. | phrase | core | — | contemporary | — | — | dictionary | n/a | low_confidence | p. 54; OCR badly scrambled ("Tril magas a v6rnyom6som"), reconstruction fairly confident given the clear English gloss but not independently cross-checked. |
| Nagyon jó illata van a sültnek. | The meat smells good. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 55, Lunch. |
| Mindig teszek fokhagymát a salátába. | I always put garlic in the salad. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 55. |
| Az ebéd nagyon ízlett. | I really enjoyed the meal. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 55. |
| Ön kitűnő szakács(nő). | You're an excellent cook. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 55; gendered noun-suffix `-nő` given for a female cook. |
| Hol lehet jót és olcsón enni? | Do you know a good, cheap place to eat? | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 56, At the Restaurant — idiomatic, lit. "where can one eat well and cheaply." |
| Éhes lettem./Megéheztem. | I've become hungry./I am quite hungry. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 56; two near-synonymous set phrases given side by side. |
| Bevásárolni akar menni? | Do you want to do some shopping? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 67, Shopping — General Expressions. |
| Ma sok mindent kell beszereznem. | I have to buy lots of things today. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 67. |
| Mit óhajt?/Mit parancsol? | What are you looking for?/What would you like? | phrase | formal | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 68 — shop-assistant's polite opener; `parancsol` recurs from the FSI file's Unit 1 vocabulary as a polite "wish/want" verb. |
| Még nem döntöttem. | I haven't decided yet. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 68. |
| Még keresgélek. | I'm still looking (around). | verb (1sg, frequentative) | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 68; `keres-` "seek" + frequentative `-gél` — mildly informal browsing-register phrase, distinct from the plain `keresni`. |
| Ez túl drága. | This is too expensive. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 68. |
| Nincs valami olcsóbb? | Have you got something less expensive? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 69. |
| Mibe kerül? | How much is it? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 69. |
| Készpénzzel fizetek. | I'll pay cash. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 69. |
| Beteg vagyok. | I'm ill. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 100, Health — General Expressions. |
| Orvosra van szükségem. | I need a doctor. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 100. |
| Hívja gyorsan a mentőt! | Call the ambulance quickly! | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 100. |
| Mik a panaszai? | What's the problem?/What are your symptoms? | phrase | formal | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 101, At the Doctor's — doctor's own set question. |
| Magas lázam van. | I have a high temperature. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 101. |
| Megfáztam. | I've caught a cold. | verb (1sg past) | core | — | contemporary | — | — | dictionary | n/a | verified | p. 101. |
| Azt hiszem, influenzás vagyok. | I think I've got flu. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 101. |
| Fáj a fejem. | I've got a headache. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 101. |
| Hidegrázásom van./Ráz a hideg. | I'm shivering. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 101; two synonymous phrasings given, the second (`Ráz a hideg`, lit. "the cold is shaking me") notably more idiomatic/colloquial than the first. |
| Elrontottam a gyomrom. | I've got an upset stomach. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 102. |
| Cukorbeteg vagyok. | I'm diabetic. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 102. |
| Fogytam. | I've lost weight. | verb (1sg past) | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 102. |
| Milyen az idő ma reggel? | What's the weather like this morning? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 112, The Weather. |
| Ma pompás idő van. | It's a lovely day. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 112. |
| Esik. | It's raining. | verb (3sg) | core | — | contemporary | — | — | dictionary | n/a | verified | p. 112. |
| Zuhog./Ömlik. | It's pouring down. | verb (3sg) | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 112; two intensified near-synonyms for heavy rain, notably more colorful/informal than plain `esik`. |
| Dörgött és villámlott. | There was thunder and lightning. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 113. |
| Igazi felhőszakadás volt. | It was a real downpour. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 113 — `igazi` "real/genuine" as an intensifier is a colloquial emphasis pattern. |
| Melyik pályaudvarról megy a vonat X-be? | From which station do trains go to X? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 118, Travelling by Rail. |
| Félek, hogy lekésem a vonatot. | I'm worried about missing the train. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 118. |
| Egy retúrt kérek X-be. | I'd like a return to X. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 119. |
| Késik a vonat? | Is the train late? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 120. |
| Elvesztettem a menetjegyemet. | I've lost my ticket. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 120. |
| Szabad/Foglalt ez a hely? | Is this seat free/taken? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 120. |
| Zsúfolt a vonat. | The train is crowded. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 120. |
| Egy kétágyas fürdőszobás szobát szeretnék foglaltatni. | I'd like to book a double room with bathroom. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 136, At a Hotel. |
| Nem szeretnék utcára néző szobát. | I don't like rooms facing the street. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 136. |
| Sajnálom, a szálloda tele van. | I'm afraid the hotel is full. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 136. |
| Mibe kerül ez a szoba? | How much is this room? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 136. |
| A reggeli benne van az árban? | Does the price include breakfast? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 136. |
| Van postám? | Are there any letters for me? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 137. |
| Éjszakánként fázom. | I'm cold at night. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 138. |
| Készítse el kérem a számlát! | Can I have the bill, please? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 138. |
| Ébresszen fel kérem hatkor! | I'd like you to wake me up at six. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 138. |
| Moziba akarok menni. | I want to go to the cinema. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 145, At the Cinema. |
| Ennek a filmnek nagy sikere van. | This film is very popular. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 145. |
| Nehéz rá jegyet kapni. | It's difficult to get tickets for it. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 145 — idiomatic, lit. "difficult to get a ticket onto it." |
| Ki a rendező? | Who's the director? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 145. |
| Szinkronizált a film. | The film is dubbed. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 145. |
| Ma minden jegy elkelt. | It's sold out for today. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 146, At the Theatre — idiomatic, lit. "every ticket has sold today." |
| Több mint egy órát álltam sorban. | I was in the queue for more than an hour. | phrase | colloquial | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 147 — everyday complaint idiom, `sorban állni` "to stand in a queue." |
| Sok tapsot kapott. | He received great applause. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 147. |
| Nagyon szeretem a zenét. | I love music. | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 148, Concerts and Operas. |
| Ki vezényel? | Who's the conductor? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 148. |
| Szerveznének nekünk egy városnézést? | Could you organize a sightseeing tour for us? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 152, Sightseeing. |
| Mi érdekli Önöket legjobban? | What are you interested in most? | phrase | formal | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 153. |
| Megnézhetnénk a Várat. | We could visit the Castle. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 153; refers to Budapest's Castle Hill/Buda Castle. |
| Ezt a templomot nemrég restaurálták. | This church has recently been renovated. | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 153. |
| Szabad fényképezni? | Can I take photographs here? | phrase | core | — | contemporary | — | — | dictionary | n/a | verified | p. 154. |
| Milyen stílusban épült a kastély? | In which style was the mansion built? | phrase | core | — | contemporary | — | — | dictionary | n/a | plausible_unverified | p. 154. |

---

## Notable patterns (in lieu of Grammar points — this is a phrasebook, not a grammar reference)

**Register system in practice.** Nearly every phrase in this book defaults to the polite `Ön`/3rd-
person-verb register (consistent with a foreign-tourist phrasebook's assumption that the speaker is
addressing strangers). The rare exceptions are worth flagging precisely because they're rare: the
Greetings section explicitly pairs `Jó napot!`/formal with `Szia!`/`Szevasz!` as its informal
counterpart (p. 5), and the Farewells section repeats the same pairing (p. 9) — both times presented
as a register *choice* the phrasebook is teaching the user to recognize, not just one entry among
many. `Hogy van?`/`Hogy vagy?` (p. 5) is likewise given as an explicit formal/informal minimal pair.

**Colloquial exclamations cluster in the Disagreement/Doubt/Surprise sections.** The most
recognizably informal-register vocabulary in this entire book is concentrated in `Elutasítás`
(Disagreement), `Kétely-Aggály-Csodálkozás` (Doubt-Worry-Surprise), and `Öröm-Meglepetés`
(Expressing Pleasure and Surprise) — `Ostobaság!`/`Hülyeség!`, `Micsoda pech!`, `Ki van zárva`, `Szó
sincs róla`, `Ez hihetetlen!`. This tracks with a general pattern this project has seen before:
emotionally charged registers (surprise, refusal, complaint) pull speakers toward less formal
vocabulary even in an otherwise formal-register source, because the pragmatic function (venting,
emphasis) resists the flattening effect of politeness register.

**Loanword flagged: `pech`.** `Micsoda pech!` ("How unfortunate!", p. 24) uses `pech`, a direct
German loanword (*Pech*, "bad luck," lit. "pitch/tar") fully nativized into colloquial Hungarian.
Worth flagging for the mechanics-analysis phase as an example of German-contact vocabulary surviving
in casual/idiomatic Hungarian registers specifically (it does not appear in either of the two prior
Hungarian reference-grammar extractions' core vocabulary).

**Idiom clusters worth flagging for slang-synthesis mechanics.** Several phrases are non-
compositional/idiomatic rather than literal, which the mechanics-analysis phase may find useful as
source material for how Hungarian slang tends to form via fixed-phrase idiom rather than single-word
coinage: `Szó sincs róla` (lit. "there's not even a word about it" = "not in the least"), `Ki van
zárva` (lit. "it's locked out" = "out of the question"), `Nem találok szavakat!` (lit. "I can't find
words" = "I'm amazed"), `Ráz a hideg` (lit. "the cold is shaking me" = "I'm shivering"), `Ma minden
jegy elkelt` (lit. "every ticket has sold today" = "it's sold out").

---

## Output files note

This file (`024_hungarian_english_phrase_book.md`) should be added as a new row in
`Hungarian/00_Extraction_Checklist.md`'s `## Output files` table by a subsequent serialized pass, per
the extraction spec's guidance on checklist updates above n=3 concurrency (not performed here to
avoid a solo-subagent race with any concurrently running sibling).
