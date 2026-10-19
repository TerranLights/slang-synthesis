# Japanese — Established Vocabulary/Grammar: Kinki (Kansai) Dialect Dictionary

**Source:** D.C. Palter & Kaoru Horiuchi Slotsve, *The Dialects and Culture of the Kinki Region —
Kinki Japanese* (Tuttle Publishing, 1st ed. 1995, 3rd printing 2002). Extraction covers the book's
back-matter **Dictionary** appendix (printed pages 147–171; alphabetical a–z, headword *hagaii*
歯痒い "frustrating" confirmed present as flagged in triage). A companion file, `109b`, covers the
book's "Kinki Variation," "Kinki Cuisine," and Kyoto/Osaka/Kobe comparative-grammar chapters (pages
46–54, 118–122), which carry genuinely different content (explicit per-city/per-prefecture regional
annotation and food vocabulary) not duplicated in this Dictionary appendix.

**Source file:** `source_reference/languages/Japanese/09.Miscellaneous/The dialects and culture of
the Kinki region - Kinki Japanese.pdf` (173 PDF pages, Adobe Acrobat Paper Capture OCR, 1995/2002
Tuttle scan).

**PDF-extraction gotcha — garbled-but-real text layer (new pattern for this project):** `pdftotext`
on this source produces a real, complete text layer — not empty, not a font-substitution cipher —
but the OCR software (Adobe Acrobat Paper Capture Plug-in) segmented nearly every English word at
essentially per-character granularity across separate lines (e.g. "frustrating" renders across ~6
line-break fragments: "f/rust/rati/ng"). This is distinct from every garbling pattern previously
catalogued in `00_Reference_Extraction_Spec.md` (not a cipher, not column-interleaving, not
raster-image text) — it is a genuine OCR word-segmentation failure that nonetheless preserves every
character in document order, so the text is fully recoverable by reading fragments back together
in sequence. Critically, **Japanese kana/kanji in this same scan were NOT subject to the same
character-splitting** — Japanese text renders cleanly on its own lines — which made cross-checking
every reconstructed English gloss against its adjacent, legible Japanese form straightforward and
reliable. A small number of passages (noted below) also show stray OCR noise substituted into
running text (random digits, CJK-unrelated glyphs, half-width kana appearing mid-word) — these were
treated as noise to be stripped during reconstruction, not as content.

**Coverage note:** every distinct dictionary headword in the appendix (a→z, ahoaho through zukkoi)
is extracted below — this is a genuinely exhaustive single-source glossary, not a sample. Each
entry includes the book's own example sentence (Kinki form + standard-Japanese-register English
translation) where the dictionary itself supplies one; entries that are purely cross-references
("→ see word N") or bare gloss-only (no example sentence in the source) are marked as such — nothing
was invented to fill in a missing example. One short passage (the Kyoto honorific-suffix discussion
immediately after the Kobe/Kansai regional note, deep in `109b`'s source range, not reproduced here)
was too corrupted by stray OCR noise (non-decodable symbol/digit substitution mid-sentence) to
reconstruct with confidence and was excluded rather than guessed at — flagged per the vision-reading
guard's "default to the riskier assumption" principle, even though this is a text-layer source, not
a vision-read one. No handwritten marginalia of any kind was found anywhere in this source (clean
institutional/commercial scan).

**Redundancy note:** this book's chapters 1, 4, 7, and 10 ("Fifteen Words Needed to Survive in
Kansai," "Fifteen More Words Needed to Survive," "Fifteen More Kinki Words," "Final Fifteen Words
to Master Kinki Speech," 60 numbered vocabulary items total across the four chapters) were checked
against this Dictionary appendix and found to be **near-total content overlap by design** — the
Dictionary's own entries cross-reference those chapters by number (e.g. "hagaii... (See 32)"), and
the appendix's terser dictionary-style entries capture the same headword/gloss/example-sentence
content, often with the identical example sentence reused verbatim. Rather than fully re-extracting
all four chapters' narrative presentation (which would duplicate this table almost entirely), this
dispatch extracted the Dictionary directly as the single most information-dense consolidated source.
No content unique to those four chapters (beyond what the Dictionary itself captures) was identified
during this pass.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ahoaho 阿呆・アホ | fool, stupid, foolish | adjective/noun | regional | — | contemporary (source published 1995) | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard baka 馬鹿 |
| akan あかん | no, no good, bad, useless, impossible; also used as a bare expletive | adjective/interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard dame 駄目 |
| akko あっこ | over there | pronoun/adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard asoko あそこ; example: "うちとこ、あっこやねん" ("My place is over there") |
| anta/ansan/antahan あんた・あんさん・あんたはん | you (contraction of anata) | pronoun | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kimi 君; example: "あんたには関係ないわ" ("That's none of your business") |
| arahen あらへん | doesn't exist, not there | verb (negative existential) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard nai 無い; example: "ご飯もうあらへんわ" ("There's no more rice left") |
| benkyosuru 勉強する | to discount a price | verb | regional.idiom | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | notable semantic shift from standard "to study" — Kansai merchant-speak idiom; cf. makeru 負ける |
| bochi-bochi ぼちぼち | so-so, not bad, not good; stock reply to "how's business?" | adjective/interjection | regional | — | contemporary | Kinki/Kansai (esp. Osaka) | regional | dictionary | n/a | n/a | often paired with dialogue "もうかりまっか?" (how's business?) → "まあ、ぼちぼちでんな" |
| chau ちゃう | no, wrong, different; also sentence-ending meaning "isn't that right?" | adjective/sentence-ending particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard chigau 違う; alt form anjai じゃない? |
| chocho/choi/chochocho ちょい・ちょお・ちょ | contraction of chotto (a little, hold on) | adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "ちょい待って" ("Hold on a second") |
| dabo ダボ | asshole (fighting word) | noun/taboo | regional.taboo | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | contraction of doaho どアホ |
| de で | exclamatory sentence ending | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard yo よ, zo ぞ |
| dekka でっか | contraction of desuka | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard desuka ですか |
| denna でんな | contraction of desuna/desune | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "今日、ほんまに暑いでんな" ("It's really hot today") |
| do- どー | prefix adding emphasis to nouns/adjectives | prefix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | — |
| donai どない | how is it? | interrogative/adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard do どう; example: "この靴、どない?" ("How do I look in these shoes?") |
| donaishitan どないしたん | what's wrong? what happened? | interrogative phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard doshitano どうしたの; example: "昨日、どないしたん?" |
| donaisho どないしょ | what should I/we do? | interrogative phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard doshiyo どうしよう; example re: "締め切りまで3日しかあれへん。どないしょ。" |
| donaisuru どないする | what are you/we going to do? | interrogative phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard dosuru どうする |
| donaiyatta どないやった | how was it? | interrogative phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard doyatta どうやった; example: "映画、どないやった?" |
| donkusai 鈍臭い | dim-witted, stupid | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard nibui 鈍い; related clipped form donkusa- w/ vowel lengthening |
| doshitan どしたん | contraction of doshitano | interrogative phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard doshita どうした |
| doshomonai どうしょうもない | hopeless, impossible, give up | adjective phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard shoganai しょうがない; example: "雨やから、どうしょうもない" |
| doya どや | what do you think? how is that? | interrogative | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | contraction of douya どうや |
| e ええ | good, that's enough | adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ii いい, yoi 良い |
| ekakkoshii ええ格好しい | person who puts on airs, pretentious | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | — |
| egui えぐい | disgusting, nauseating | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example re: ice cream color: "このアイスクリームの色、えぐいなあ" |
| erai えらい | very; tiring; magnificent (context-dependent) | adverb/adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. hijoni 非常に/totemo とても (very); taihen 大変/shindoi しんどい (tiring); rippa 立派 (magnificent) — a single headword covering three distinct standard-Japanese glosses by context |
| gametsui がめつい | greedy | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard yokubari 欲張り |
| gana がな | sentence-ending intensifier | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "がっこ行かんとあかんがな" ("You absolutely have to go to school") |
| geiko 芸子 | exclusive Kyoto term for geisha (or geisha generally) | noun | regional.technical | — | contemporary | Kyoto (Kinki) | local | dictionary | n/a | n/a | — |
| geinin 芸人 | professional entertainer/comedian | noun | core | — | contemporary | Kinki/Kansai | national | dictionary | n/a | n/a | included for cultural context (comedy culture entry) |
| gera ゲラ | person who laughs hard easily | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard waraijogo 笑い上戸 |
| Gion 祇園 | traditional district near Kawaramachi in Kyoto, famous for geiko | proper noun | regional | — | contemporary | Kyoto (Kinki) | local | dictionary | n/a | n/a | — |
| goneru ごねる | to whine, to complain | verb | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "なんぼごねても飴あげへんで" |
| gossan/gossosan/gottsuosan ごっさん・ごっそさん・ごっつおさん | thanks for the food | interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard gochisosamadeshita 御馳走様でした; gossan and gossosan are listed as further-clipped cross-references to gottsuosan |
| gottsui ごっつい | very; big | adverb/adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 17 |
| gyosan 仰山 | a lot, many | adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard takusan 沢山; cross-referenced to chapter item 39 |
| hagaii 歯痒い | frustrating | adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | **flagship triage headword.** Contraction of hagayui 歯がゆい, literally "itchy tooth" — you know pulling the tooth would only make things worse, so you just feel frustrated; most commonly used of a person who, out of ineptitude or other reasons, fails to act when they clearly could; example dialogue (Kensuke/Kyota) included in source, not reproduced verbatim here per copyright discipline — paraphrased above |
| -han ーはん | Mr./Ms. (honorific suffix) | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -san ーさん |
| Hanshin 阪神 | Hanshin Tigers (baseball team); Hanshin Railway; Hanshin Department Store; Osaka–Kobe region; Hanshin horse racing track in Takarazuka | proper noun | core | — | contemporary | Osaka–Kobe (Kinki) | regional | dictionary | n/a | n/a | polysemous proper noun with 5 distinct referents listed by the source itself |
| -haru ーはる | honorific verb conjugation | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard onasaru なさる |
| hayo はよ | early, quickly | adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard hayaku 早く／速く; example: "この仕事、はよせなあかんねん" |
| -hen ーへん | negative verb conjugation | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -nai ーない |
| hokasu ほかす | to throw away | verb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard suteru 捨てる |
| hona/honara ほな・ほなら | in that case, if so, then; see you later | conjunction/interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | — |
| honde ほんで | then, after that, and | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sorede それで／sorekara それから; example re: Osaka→Kyoto→Shiga trip |
| hondemo ほんでも | but, nevertheless | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard soredemo それでも; example: "ほんでも好きやねん" |
| honja ほんじゃ | see you later, goodbye; in that case | interjection/conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard soreja それじゃ |
| honma ほんま | really | adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard honto 本当; one of the dialect's best-known markers |
| honnara ほんなら | in that case, if so, then | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sorenara それなら |
| horu ほる | to throw away | verb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard suteru 捨てる; example re: pitcher throwing fast: "あのピッチャーごっつ速い玉ほるで" |
| ichamon いちゃもん | complaint, whine | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard monku 文句; example: "いちいち、いちゃもん付けんとって" |
| ichibiri いちびり | dolt, clown | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ochoshimono お調子者 |
| ichibiru いちびる | to clown around, to act stupid | verb | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | verb form of ichibiri |
| ikezu いけず | mean, nasty | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ijiwaru 意地悪 |
| ikkomo いっこも | not even a little bit, not at all (precedes negative verb/adjective) | adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard zenzen 全然; example: "この漫画、いっこもおもろない" |
| iko 行こ | let's go | verb (volitional, clipped) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard iko 行こう; example: "明日難波行こ" |
| irau いらう | to touch, to meddle with | verb | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ijiru いじる／sawaru 触る |
| irachi いらち | irritable person | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | — |
| itchan いっちゃん | number one, most | adverb | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ichiban 一番; example: "いっちゃんアホ" ("stupidest") |
| itchomae いっちょまえ | self-important | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ichininmae 一人前; example re: kid in a suit looking full of himself |
| jibun 自分 | you | pronoun | regional.idiom | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | semantic-shift pronoun use (standard "oneself/myself" → Kansai second-person); cf. anata あなた; example: "自分、関東煮好き?" |
| kaina かいな | sarcastic sentence ending; also expresses doubt/demand | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | — |
| kakko かっこ | appearance, shape | noun | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kakko 格好; example: "今日、きれいな格好してるやん" |
| kamahen/kamehen かまへん・かめへん | don't mind, it's fine | adjective/interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kamawanai 構わない |
| kanawan かなわん | troubled, stuck; can't win against someone/something | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kanawanai かなわない |
| kanninsuru/kanisuru 堪忍する・かにする | excuse me, have patience with me | verb phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kanbensuru 勘弁する |
| Kansai 関西 | same as Kinki; same as Kei-Han-Shin | proper noun | core | — | contemporary | Kinki | regional | dictionary | n/a | n/a | — |
| kate かて | even if, even though (particle) | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard mo も／temo ーても／demo でも／desae でさえ |
| katsu-katsu かつかつ | barely surviving, barely in time | adverb | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard giri-giri ぎりぎり; example re: barely scraping by financially this month |
| Kawaramachi 河原町 | main shopping/entertainment district of central Kyoto | proper noun | core | — | contemporary | Kyoto (Kinki) | local | dictionary | n/a | n/a | — |
| Kei-Han-Shin 京阪神 | tri-city region of Kyoto, Osaka, and Kobe | proper noun | core | — | contemporary | Kinki | regional | dictionary | n/a | n/a | — |
| kehen/kiihen/kiihin けえへん・きいへん・きいひん | don't come | verb (negative) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard konai 来ない; example: "今晩、こっちけえへんか?" |
| kettai けったい | strange, unusual, comical | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard hen 変／myo 妙; example: "そりゃ、けったいなこっちゃなあ" |
| Kinki 近畿 | southern half of Honshu, incl. Osaka-fu, Kyoto-fu, Mie-ken, Shiga-ken, Hyogo-ken, Nara-ken, Wakayama-ken | proper noun | core | — | contemporary | Kinki | regional | dictionary | n/a | n/a | the region-defining headword itself |
| Kita キタ | Osaka region around Umeda and Osaka Station | proper noun | core | — | contemporary | Osaka (Kinki) | local | dictionary | n/a | n/a | — |
| koeru 肥える | to gain weight | verb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard futoru 太る; example: "最近、また肥えてん" |
| koeteru 肥えてる | fat, overweight | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard futotteiru 太っている; example re: calling one's boss fat (bluntly) |
| kokeru こける | to fall down, fall over, trip | verb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard taoreru 倒れる／korobu 転ぶ; example re: daughter falling and hurting herself |
| kora/korya こら・こりゃ | contraction of kono-wa/korewa ("this is...") | demonstrative contraction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "こら、あかんで" |
| kosobai こそばい | ticklish | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kusugutai くすぐったい |
| kotcha こっちゃ | thing, event (contraction of kono-koto-ya) | noun phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kotoda ことだ; example: "何のこっちゃ" ("What the heck is that?") |
| Koshien 甲子園 | baseball stadium where the Tigers play; national HS baseball tournament; town in Nishinomiya | proper noun | core | — | contemporary | Nishinomiya (Kinki) | local | dictionary | n/a | n/a | — |
| kote こうて | buy (verb, -te form) | verb form | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard katte 買って; example: "ぎょうさんこうてしもた" |
| kota こうた | bought | verb (past) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard katta 買った |
| -mahen ーまへん | semi-polite negative verb conjugation | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -masen ーません |
| maido 毎度 | hello | interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | — |
| maiko 舞子 | girl training to become a geiko | noun | regional.technical | — | contemporary | Kyoto (Kinki) | local | dictionary | n/a | n/a | — |
| makashi/makashitoki 任し・任しとき | leave it to him/her; I'll take care of it | verb phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example re: leaving a job to a junior employee |
| makeru 負ける | to discount a price | verb | regional.idiom | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 36; same semantic-shift idiom as benkyosuru above |
| -makka ーまっか | contraction of -masuka | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -masuka ーますか; example re: asking if mother is home |
| manzai 漫才 | stand-up comedy | noun | core | — | contemporary | Kinki/Kansai (strongly associated) | national | dictionary | n/a | n/a | culturally associated with Osaka comedy tradition |
| manzai-shi 漫才師 | stand-up comedian | noun | core | — | contemporary | Kinki/Kansai (strongly associated) | national | dictionary | n/a | n/a | — |
| massara 真っ新 | brand-new | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "その服、まっさらちゃう?" |
| -masse ーまっせ | polite emphatic sentence ending | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -masuyo ーますよ; example re: warning someone they'll be late |
| mecha めちゃ | very; also reckless/disorganized | adverb/adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sugoku 凄く (very); mecha-kucha めちゃくちゃ (reckless) |
| megeru めげる | to break | verb | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kowareru 壊れる; example re: a broken bicycle |
| metcha めっちゃ | very | adverb | regional.slang | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sugoku 凄く; variant of mecha, now widely diffused into pan-Japanese youth slang |
| -mi/-imi ーみい・み | -te form marker, used like "mite" | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard mite みて |
| Minami ミナミ | Osaka region near Namba Station | proper noun | core | — | contemporary | Osaka (Kinki) | local | dictionary | n/a | n/a | — |
| mokkai もっかい | once more, again | adverb | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | contraction of mou-ikkai もう一回; example: "もっかい住所教えて" |
| -mon ーもん | contraction of mono (thing) | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "漬もん、食うか?" (offering pickled vegetables) |
| -mota ーもた | contraction of -shimota (= -shimatta) | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 14 |
| morota もろた | received | verb (past) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard moratta もらった; example re: who gave the candy |
| mokarimakka/mokattemakka もうかりまっか・もうかってまっか | how are you? how's business? | greeting phrase | regional | — | contemporary | Kinki/Kansai (esp. Osaka) | regional | dictionary | n/a | n/a | cross-referenced to chapter item 19; classic Osaka merchant greeting, paired with bochi-bochi as the stock reply |
| mota もうた | received (alt. form) | verb (past) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard moratta もらった — listed as a secondary headword alongside morota |
| mucha むちゃ | reckless, disorganized (= mecha) | adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. mucha-kucha むちゃくちゃ |
| mutcha むっちゃ | very | adverb | regional.slang | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sugoku 凄く; variant of mecha/metcha |
| -n ーん | negative verb conjugation | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -nai ーない |
| -n ーん (sentence-ending) | question sentence-ending particle; contraction of no | suffix/particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "明日、ゴルフ行くん?" |
| nan/naa な・なあ | sentence ending | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ne ね; cross-referenced to chapter item 28 |
| nan なん | sentence ending; contraction of nano | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "それ何なん?" |
| nanbo なんぼ | how much | interrogative | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ikura 幾ら |
| nangi 難儀 | difficult, annoying | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard muzukashii 難しい／mendokusai 面倒臭い |
| Naniwa なにわ | old name for Osaka | proper noun | regional.archaic | — | contemporary | Osaka (Kinki) | local | dictionary | n/a | n/a | historical place name, still used evocatively |
| nanmo 何も | nothing (precedes negative verb/adjective) | pronoun | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "冷蔵庫ん中、なんも残ってへん" |
| nanya 何や | (= nanka, "something/what") | pronoun | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example re: a manager being inexplicably in a bad mood |
| naosu なおす | to clean up, put away | verb | regional.idiom | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | notable semantic shift from standard "to fix/repair" to "to put away"; cf. katazukeru 片付ける |
| nen ねん | neutral sentence ending | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 13 |
| neya ねや | sentence ending for question or statement | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard noda のだ／no の; example: "何してんねや?" |
| non のん | possessive conjunction; particle for recurring events; question sentence ending | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | triple-function particle — cf. nomono のもの／no の; mono もの／koto こと; no? の? |
| nukasu ぬかす | to say (vulgar register) | verb | regional.taboo | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard iu 言う; example: "何アホな事ぬかしとんじゃ?" |
| nukui 温い | warm | adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard atatakai 暖かい |
| obahan おばはん | middle-aged lady | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard obasan おばさん |
| ochokuru おちょくる | to tease, make fun of | verb | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard karakau からかう; example re: always being teased |
| okini 大きに | thank you | interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard arigato ありがとう; cross-referenced to chapter item 9 |
| omoroi おもろい | interesting | adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard omoshiroi 面白い; cross-referenced to chapter item 20 |
| oru おる | to exist | verb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard iru いる; cross-referenced to chapter item 10 |
| ossan おっさん | middle-aged man | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ojisan おじさん; example re: a drunk man |
| otchan おっちゃん | middle-aged man | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ojisan おじさん; example re: a produce vendor giving discounts |
| ota おうた | met | verb (past) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard atta 会った／合った; example re: meeting a celebrity on a plane |
| pachiru/pakuru ぱちる・ぱくる | to steal | verb | regional.slang | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard nusumu 盗む; bare gloss, no example sentence in source |
| -ra ーら | plural-pronoun-forming suffix | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -tachi 達; cross-referenced to chapter item 43 |
| Rokko 六甲 | Mt. Rokko | proper noun | core | — | contemporary | Kinki (Kobe area) | local | dictionary | n/a | n/a | — |
| Rokko Oroshi 六甲颪 | Hanshin Tigers fight song; wind blowing down from Mt. Rokko | proper noun | core | — | contemporary | Kinki (Kobe area) | local | dictionary | n/a | n/a | — |
| sainara さいなら | goodbye | interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sayonara さようなら |
| sakaini さかいに | because, for that reason | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kara から／node ので; example: "ほな、また来るさかいに" |
| -san ーさん | honorific greeting suffix | suffix | core | — | contemporary | Kinki/Kansai | national | dictionary | n/a | n/a | cross-referenced to chapter item 29; included as the dictionary's own entry despite being pan-Japanese, because the source frames it under its honorific/greeting-suffix family |
| Sannomiya 三宮 | downtown area of Kobe; main train station in Kobe | proper noun | core | — | contemporary | Kobe (Kinki) | local | dictionary | n/a | n/a | — |
| sara 新(さら) | new | adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard atarashii 新しい |
| sarappin/sarapin 新品 | new goods or product | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example re: selling new stuff at a flea market |
| sehen せえへん | don't do | verb (negative) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard shinai しない; example: "昨日何もせえへんかった" |
| sen せん | don't | verb (negative) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard shinai しない; example re: "心配せんかて、大丈夫や" |
| sesshona 殺生な | don't kill me, have mercy on me | interjection phrase | regional.idiom | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | literally "cruel/brutal" (殺生); idiomatic plea; example re: a borrowed 30,000-yen debt |
| seya せや | that's right | interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard so そう |
| seyakara せやから | that's why | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sodakara そうだから |
| seyakedo せやけど | (= sodakedo, "but that's so") | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | bare gloss, no example in source |
| seyattara せやったら | (same as soyattara) | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced variant of soyattara |
| shanai しゃあない | it can't be helped, hopeless | adjective phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard shikataganai 仕方がない; one of the dialect's signature phrases |
| shibaku しばく | to punch; also generic "to do" | verb | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. naguru 殴る (punch) / suru する (do) |
| shii しい | do it (imperative) | verb (imperative) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard shinasai しなさい; example: "はよ宿題しい" |
| shiihin しいひん | don't do (= sehen) | verb (negative) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard shinai しない |
| shimota しもた | (= shimatta) | verb (past, regret marker) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 14 |
| shindoi しんどい | tiring, hard | adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 21; widely diffused beyond Kansai in modern colloquial Japanese |
| shitente してんて | I heard... happened | verb phrase (reportative) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | contraction of shitanyate; cf. standard shitandatte したんだって; example re: a coworker changing jobs |
| shitatte したって | please do it for him/her | verb phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard shiteagete してあげて; example: "電話したって" |
| sho/shiyo しょ・しよ | (= shiyo, "let's do") | verb (volitional) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "そうしょ" |
| shomonai/shomonai しょうもない・しょもない | uninteresting, trifling | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 52 |
| sonai そない | so much, too much; in that manner | adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sonnani そんなに／sonoyoni そのように; example re: not needing to criticize so much |
| sonnara そんなら | in that case | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 18 |
| sonnan そんなん | that is | demonstrative phrase | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sonnano そんなの／sonnakoto そんな事; example: "そんなん、ずっこいわ" |
| sora/sorya そら・そりゃ | contraction of sono-wa/korewa | demonstrative contraction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "そら、あかんわ" |
| soya/soya そうや・そや | (= soda, "that's right") | interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | — |
| soyattara/soyattara そうやったら・そやったら | in that case | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sodattara そうだったら／soredattara それだったら |
| sukiyanaa/sukkyanaa/sukiyanen/sukkyanen 好きゃなあ・好っきゃなあ・好きやねん・好っきやねん | like | adjective (expressive) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 22; a cluster of four emphatic variants of one headword |
| sunmahen/sumahen/sunmasen/suman すんまへん・すまへん・すんません・すまん | excuse me | interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard sumimasen すみません; example re: apologizing |
| Taigasu タイガース | Hanshin Tigers | proper noun | core | — | contemporary | Kinki (Hanshin area) | regional | dictionary | n/a | n/a | — |
| takoute たこうて | tall, high, expensive | adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard takakute 高くて; example re: steak being too expensive to eat often |
| -tan ーたん | past-tense verb-ending variant | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -ta ーた; example: "何したん?" |
| tanomu 頼む | please, I'm counting on you | verb/interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard onegaishimasu お願いします; cross-referenced to chapter item 38 |
| -tari/-tore ーたり・ーたれ | please do this for him/her | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | contraction of -shiteyari; cross-referenced to chapter item 44 |
| -taro/-taro ーたる・ーたろ | I'll do it for him/her/you | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | contraction of -shiteyaru; cross-referenced to chapter item 44 |
| -tatte ーたって | please do it for him/her | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -teagete ーてあげて; example: "食事作ったって" |
| -tena/-tena/-teya ーてえな・ーてえなあ・ーてえや | casual request | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | attaches to verb -te form; example: "店、手伝ってえな" |
| -ten ーてん | past-tense verb conjugation | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -tanda ーたんだ; cross-referenced to chapter item 45 |
| -tennen ーてんねん | progressive ("-ing") verb conjugation | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -teiru ーている／-teru ーてる; cross-referenced to chapter item 45 |
| tereko てれこ | mixed up, in the wrong order | adjective/noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard tagaichigai 互い違い; example re: misordered documents |
| -toki ーとき | do it (imperative) | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | contraction of -te oki; cf. standard -nasai ーなさい; example: "お父さんに謝っとき!" |
| -toko ーとこ | contraction of -te oko (volitional "let's... in advance") | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -teoku ーておく; example re: deciding to skip drinks tonight |
| -ton ーとん | progressive verb conjugation | suffix | regional | — | contemporary | Kinki/Kansai (esp. Kobe) | regional | dictionary | n/a | n/a | cf. standard -teiru ーている; example: "何食べとん?" |
| Tora-kichi 虎キチ | devoted Hanshin Tigers fan | noun | regional.colloquial | — | contemporary | Kinki (Hanshin area) | regional | dictionary | n/a | n/a | kichi derives from kichigai 気違い ("crazy [about]") |
| -toru ーとる | progressive verb conjugation | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -teiru ーている／-teru ーてる; example: "何しとるん?" |
| -totte ーとって | contraction of -toite | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -teoite ーておいて; example re: asking someone to record on the VCR |
| tsubureru 潰れる | to break | verb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard kowareru 壊れる; example re: a busted mechanical pencil |
| tsukote/tsukote っこうて・っこて | to use (-te form of tsukau) | verb form | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard tsukatte 使って |
| uchi うち | I | pronoun | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard watashi 私; one of the dialect's best-known first-person pronouns, esp. among women |
| uchira うちら | we, our | pronoun | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard watashitachi 私達 |
| umai 旨い | delicious | adjective | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard oishii 美味しい; example re: a good restaurant |
| uttoshii 欝陶しい | gloomy, dreary | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 23 |
| wa わ | neutral sentence ending | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard yo よ; cross-referenced to chapter item 30; notably used by both men and women in Kansai (unlike the feminine-coded standard-Japanese wa) |
| waya わや | screw-up, ruined | noun/adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard mecha-kucha めちゃくちゃ; example re: ruining a kimono in the rain |
| ya や | (= da, copula) | copula | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 15; the single most defining Kansai-ben feature (ya replacing standard da) |
| yakedo やけど | (= dakedo, "but") | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | — |
| yan やん | sentence ending | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard jan じゃん／janaino じゃないの; example: "あの人、かっこええやん" |
| -yan ーやん | suffix attached to names between friends | suffix | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard -kun 君; same morpheme attested productively in example dialogue elsewhere in the book (Shige-yan) |
| yanai やない | (= janai, "isn't it") | copula (negative) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "あの店、閉まってるんやない?" |
| yanka やんか | (= janaika, "isn't it, though") | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example re: not being able to drive |
| yanke やんけ | (= janaika) | particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "簡単やんけ!" ("It's easy, I'm telling you!") |
| yarashii やらしい | vulgar, disgusting | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard iyarashii 嫌らしい |
| yaro やろ | (= daro, "probably/right?") | copula (conjectural) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example: "明日、野球するやろ?" |
| yaru やる | give | verb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard ageru あげる; cross-referenced to chapter item 54 |
| yate やて | I heard that...; I'm sure that... | sentence-ending particle | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard datte だって／dayo だよ |
| yatcha やっちゃ | person, thing | noun | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard yatsuda 奴だ |
| yatta やった | (= datta, "it was") | copula (past) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example re: asking how yesterday's game went |
| yattara やったら | (= dattara, "if it is/was") | conjunction | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | example re: canceling a camping trip if it rains |
| yossha よっしゃ | yes, okay, great | interjection | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cross-referenced to chapter item 55 |
| yo よう | very, much, often, well | adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard yoku よく; cross-referenced to chapter item 24 |
| yoke ようけ | a lot, many | adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard takusan 沢山; cross-referenced to chapter item 39 |
| yosan ようさん | a lot, many | adverb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard takusan 沢山; cross-referenced to chapter item 39; a doublet of yoke |
| yuu/yuu 言う・ゆう | to speak | verb | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard iu 言う; cross-referenced to chapter item 25 |
| yuta 言うた | said | verb (past) | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard itta 言った; example re: whether the manager said something |
| yute 言うて | to say (-te form) | verb form | regional | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard itte 言って; cross-referenced to chapter item 25 |
| zukkoi ずっこい | cunning, sneaky | adjective | regional.colloquial | — | contemporary | Kinki/Kansai | regional | dictionary | n/a | n/a | cf. standard zurui ずるい／warugashikoi 悪賢い; final headword of the Dictionary appendix |

---

## Grammar points

### The `-haru`/`-han` honorific layer as a distinct politeness system from standard Japanese

Several dictionary entries above (`-haru`, `-han`) point to a systematic Kansai-ben honorific
layer that runs in parallel to, but is not identical with, standard Japanese keigo. `-haru` attaches
to verbs and functions similarly to standard `-nasaru`, while `-han` is a Mr./Ms. suffix comparable
to `-san`. The companion file `109b` documents in more depth how this system's register varies
sharply by city (near-universal everyday use in Kyoto vs. markedly less frequent honorific framing
in Osaka), which the Dictionary appendix itself does not capture (it records the form, not its
regional frequency).

### Productive politeness-stripping/clipping pattern across negative and past-tense suffixes

A recurring structural pattern across many entries above (`-hen`/`-n` negatives; `-ta`/`-tan`/`-ten`
pasts; `-mahen`/`-masse` semi-polite forms) is that Kansai-ben systematically derives its own
suffix paradigm from standard Japanese `-nai`/`-ta`/`-masu` forms via sound change and clipping,
rather than through unrelated vocabulary — e.g., `-hen` as an eroded descendant of `-nai`'s negative
function, `-ton`/`-toru`/`-tennen` as parallel progressive-aspect markers built on `-teiru`/`-teru`.
This is consistent with the general finding (confirmed across the Dictionary's suffix entries) that
Kansai-ben's grammar diverges from standard Japanese mainly through phonological reduction and
suffix-paradigm substitution, not through an unrelated grammatical substrate.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. Example sentences
above are reproduced individually (single short sentences) as illustrative evidence per entry,
consistent with the spec's "a short illustrative quote... is fine" allowance; the book's longer
multi-line example dialogues and all explanatory prose are paraphrased, not quoted.
