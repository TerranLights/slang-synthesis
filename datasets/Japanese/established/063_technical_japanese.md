# Japanese — Established Vocabulary/Grammar: Technical/Scientific Register (Wave 3, Audio Courses/Textbooks)

**Source:** Representative sampling across three combined volumes (1,364 pages total):
- Edward E. Daub, R. Byron Bird, Nobuo Inoue, *Comprehending Technical Japanese* (University of
  Wisconsin Press / University of Tokyo Press, 1975, 2nd printing 1982), 438 pages, DJVU — sampled
  Preface, Explanatory Notes, Lesson 2 kanji list + reading selection (p. 2 of Lesson 2), Lesson 2
  Explanatory Notes + Construction Examples + start of Supplementary Readings.
- James L. Davis, *Intermediate Technical Japanese, Volume 1: Readings and Grammatical Patterns*
  (University of Wisconsin Press, 2002), 494 pages, PDF — sampled Preface, Explanatory Notes,
  Lesson 0 (all 10 grammar points, pp. 1-6), Lesson 1 grammatical patterns 1.1-1.15 (pp. 9-13) and
  kanji/vocabulary page (p. 7), plus single representative kanji/vocabulary pages from Lesson 4
  (Computer Science I, p. 45), Lesson 19 (Electricity I, p. 231), and Lesson 30 (Polymers I, p. 343).
- James L. Davis, *Intermediate Technical Japanese, Volume 2: Glossary* (University of Wisconsin
  Press, 2002), 432 pages, PDF — sampled Table of Contents and one representative glossary page
  (p. 4, keyed to Lesson 0 grammatical patterns 0.7/0.8).

**Coverage note — representative sampling, not exhaustive.** Per the dispatch instructions, this is
TECHNICAL/scientific-register Japanese across a combined 1,364-page, 3-book corpus — low slang
yield expected but useful for grammar patterns and formal/technical-vs-colloquial register contrast.
Given the scale, this file extracts representative content rather than every page: **all 10 of
Lesson 0's verb-form grammar points** (these recur throughout the whole three-book corpus and are
foundational), **all 15 of Lesson 1's grammatical patterns** (representative of the pattern-teaching
format used in Lessons 1-9 of Vol. 1), and **vocabulary sampled from one kanji-list page per
several widely-separated topic lessons** (Mathematics, Computer Science, Electricity, Polymers) in
Vol. 1, plus a Vol. 2 glossary sample and a *Comprehending Technical Japanese* lesson sample, chosen
to span the different disciplines and decades these books cover (1975 vs. 2002) rather than
exhaustively transcribing all ~100 grammatical patterns and 600+ kanji entries across both authors'
full lesson sequences. No grammatical pattern or vocabulary item found in the sampled pages was
skipped; patterns/kanji in unsampled lessons were not reached.

**PDF/DJVU text-layer gotcha confirmed on all three sources (as flagged in the dispatch):** both
`pdftotext` (on the two Davis PDFs) and `djvutxt` (on the Daub/Bird/Inoue DJVU) cleanly extract
English prose, romaji, and page numbers, but kanji and kana glyphs decode as unrelated stray Latin
characters, punctuation, and symbols — a garbled, non-decodable OCR artifact rather than a fixed
1:1 substitution cipher (quick spot-checks found no consistent character-level mapping). This
matches the DJVU/garbled-OCR case in the extraction spec's PDF gotcha list, not the fixed-offset
CJK cipher case. **Grammar-point explanatory prose (fully in English) was extracted directly from
the text layer; all actual Japanese terms/kanji in this file were recovered by vision-reading
rendered page images** (kanji list pages are typeset in a large, clean, single-font layout — no
marginalia or handwriting was found on any vision-read page in this sample). Reading-selection/essay
body text (continuous Japanese prose, as opposed to kanji-list vocabulary and English grammar
explanations) was not vision-read at this sampling scale — it was deemed lower yield per page than
the kanji-list vocabulary and English-language grammar explanations, given this is non-slang
technical register. A full-corpus pass would need per-page vision-reading of the essay text.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 数学 (すうがく, suugaku) | mathematics | noun | technical | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Compound of 学 (ガク "learning"/まな(ぶ) "to learn"); Vol. 1 Lesson 1 kanji list, p. 7. |
| 論理学 (ろんりがく, ronrigaku) | logic | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 学 kanji entry, p. 7. |
| 集合 (しゅうごう, shuugou) | set, collection | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 合 kanji entry (ガツ/ゴウ; あ(う) "to fit" {vi}, あ(わせる) "to join together" {vt}), p. 7. |
| 場合 (ばあい, baai) | instance, case | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 合 kanji entry, p. 7. |
| 無限集合 (むげんしゅうごう, mugen-shuugou) | infinite set | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 限 kanji entry (ゲン/かぎ(る) "to limit, restrict"), p. 7. |
| 有限集合 (ゆうげんしゅうごう, yuugen-shuugou) | finite set | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 限 entry, p. 7. |
| 性質 (せいしつ, seishitsu) | property, characteristic | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 質 kanji entry (シチ "hostage, pawn" / シツ "matter, substance"), p. 7. |
| 品質 (ひんしつ, hinshitsu) | quality | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 質 entry, p. 7. |
| 実験 (じっけん, jikken) | experiment, trial | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 実 kanji entry (ジツ "substance, truth"; み "fruit", みの(る) "to bear fruit"), p. 7; independently reconfirmed via *Comprehending Technical Japanese* reading-selection vocabulary list ("jikken" = experiment), p. 2 of Lesson 2 — convergent cross-source confirmation. |
| 実数 (じっすう, jissuu) | real number | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 実 entry, p. 7. |
| 空集合 (くうしゅうごう, kuu-shuugou) | empty set | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 集 kanji entry (シュウ "collection, gathering"; あつ(まる) "to assemble" {vi}, あつ(める) "to collect" {vt}), p. 7. |
| 集団 (しゅうだん, shuudan) | group, collection | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 集 entry, p. 7. |
| 安定性 (あんていせい, anteisei) | stability | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 性 kanji entry (ショウ "disposition, nature" / セイ "attribute, gender, nature"), p. 7. |
| 特性 (とくせい, tokusei) | characteristic | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 性 entry, p. 7. |
| 化学 (かがく, kagaku) | chemistry | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 化 kanji entry (カ "influence, suffix for change"/ケ "changing"; ば(かす) "to bewitch" {vt}, ば(ける) "to appear in disguise" {vi}); Vol. 1 Lesson 4 (Computer Science I), p. 45. |
| 機械語 (きかいご, kikaigo) | machine language | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 械 kanji entry (カイ "instrument, machine"), p. 45. |
| 機能 (きのう, kinou) | function | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 機 kanji entry (キ "airplane, machine, opportunity"; はた "loom"), p. 45. |
| 権利 (けんり, kenri) | right, privilege | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 権 kanji entry (ケン/ゴン "authority, power, right"), p. 45. |
| 特権命令 (とっけんめいれい, tokken-meirei) | privileged instruction | noun | technical.computer_science | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 権 entry, p. 45. |
| 確率的誤差 (かくりつてきごさ, kakuritsuteki-gosa) | random error | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 誤 kanji entry (ゴ "error, mistake"; あやま(る) "to be mistaken" {vi}/"to make a mistake" {vt}), p. 45. |
| 丸め誤差 (まるめごさ, marume-gosa) | rounding error | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 誤 entry, p. 45. |
| データ構造 (データこうぞう, deeta-kouzou) | data structure | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 構 kanji entry (コウ "building, posture"; かま(う) "to care about/mind" {vt}, かま(える) "to assume an attitude/build" {vt}), p. 45. |
| 暗号化 (あんごうか, angouka) | encryption, encipherment | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 号 kanji entry (ゴウ "number, title"), p. 45. |
| 周縁 (しゅうえん, shuuen) | periphery, border, fringe | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 縁 kanji entry (エン "affinity, connection, destiny, fate, relation"; ふち "brink, edge, rim, border"); Vol. 1 Lesson 19 (Electricity I), p. 231. |
| 絶縁体 (ぜつえんたい, zetsuentai) | insulator | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 縁 entry, p. 231. |
| 電荷 (でんか, denka) | electric charge | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 荷 kanji entry (カ "load"; に "baggage, cargo, load", にな(う) "to bear/carry"), p. 231. |
| 負荷 (ふか, fuka) | load | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 荷 entry, p. 231. |
| 殻電子 (かくでんし, kaku-denshi) | shell electron | noun | technical.physics | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 殻 kanji entry (カク "husk, hull, shell"; から "earth's crust, hull, husk, shell"), p. 231. |
| 内殻 (ないかく, naikaku) | inner shell | noun | technical.physics | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 殻 entry, p. 231. |
| 自然言語 (しぜんげんご, shizen-gengo) | natural language | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 自 kanji entry (シ/ジ "oneself"; みずか(ら) "(by) oneself, personally"), p. 231. |
| 自動制御 (じどうせいぎょ, jidou-seigyo) | automatic control | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 自 entry, p. 231. |
| 難易 (なんい, nan'i) | (relative) difficulty | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 易 kanji entry (イ "ease"; エキ "divination, fortunetelling"; やさ(しい) "easy, simple"); Vol. 1 Lesson 30 (Polymers I), p. 343. |
| 容易な (よういな, youi-na) | easy, simple | な-adjective | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 易 entry, p. 343. |
| 活性化 (かっせいか, kasseika) | activation | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 活 kanji entry (カツ "being helped, living, resuscitation"), p. 343. |
| 側鎖 (そくさ, sokusa) | side chain | noun | technical.chemistry | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 鎖 kanji entry (サ "chain, connection, irons"; くさり "chain, connection, irons"), p. 343. |
| 連鎖反応 (れんさはんのう, rensa-hannou) | chain reaction | noun | technical.chemistry | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 鎖 entry, p. 343. |
| 潤滑剤 (じゅんかつざい, junkatsuzai) | lubricant | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 剤 kanji entry (ザイ "dose, drug, medicine"), p. 343. |
| 重合体 (じゅうごうたい, juugoutai) | polymer | noun | technical.chemistry | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | 重 kanji entry (ジュウ/チョウ "-fold, heavy, nest of boxes, piled up"; え "-fold, ply"; おも(い) "heavy, important, massive, serious"; かさ(なる)/かさ(ねる)), p. 343. |
| 重力 (じゅうりょく, juuryoku) | gravity, gravitational force | noun | technical.physics | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Same 重 entry, p. 343. |
| のに | in order to, although | conjunctive particle | technical | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Vol. 2 glossary, p. 4, keyed to pattern 0.7/0.8 — a grammatical function word rather than a kanji compound, listed without kanji/reading column since it's already kana. |
| たとえば | for example | adverb | core | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Vol. 2 glossary, p. 4. |
| 電気回路 (でんきかいろ, denki-kairo) | electric circuit | noun | technical | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Vol. 2 glossary, p. 4. |
| 漸化式 (ぜんかしき, zenkashiki) | recurrence formula | noun | technical.mathematics | — | contemporary (2002) | — | — | grammar_reference | n/a | verified | Vol. 2 glossary, p. 4. |
| 得る (える, eru) | to get, receive, acquire | verb | core | — | contemporary (source published 1975/1982) | — | — | grammar_reference | n/a | verified | *Comprehending Technical Japanese*, Lesson 2 kanji list — kanji 得 (TOKU/e(ru)), frequency rank 850 (ON)/1622 (KUN); reading-selection vocabulary list confirms romaji "eru" and English gloss. This book is unusual in giving a numeric kanji-frequency rank per reading — a genuine frequency-dictionary-style datum (see Notes on Weight/Frequency column use below). |
| ならば (naraba) | if it is... | conditional particle | technical | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | Lesson 2 reading-selection vocabulary list, p. 2 of Lesson 2. Cross-validates the independently-inferred pattern 1.11 なら(ば) in Davis Vol. 1 (see Grammar points below) — same conditional shortened-copula form confirmed across two independently-authored technical-Japanese textbooks 27 years apart. |
| ただし (tadashi) | here; however, provided that | conjunction | technical | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | *Comprehending Technical Japanese*, Lesson 2 Explanatory Notes (note 8): flagged as a word that, immediately after an equation in scientific text, "almost always may be translated as 'here'." Directly cross-validates Davis Vol. 1 pattern 1.9's independently-derived ただ/ただし gloss. |
| 和 (わ, wa) | sum | noun | technical.mathematics | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | Lesson 2 Explanatory Notes, "elementary mathematical operations" list. |
| 差 (さ, sa) | difference | noun | technical.mathematics | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | Same list. Note: distinct sense from Vol. 1's 差 kanji entry (サ "difference, variation"; さ(す) "to carry on the shoulder/put up an umbrella/stretch out a hand") seen on the Electricity I page — same kanji, broader KUN-reading sense set given there. |
| 積 (せき, seki) | product | noun | technical.mathematics | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | Same list. |
| 商 (しょう, shou) | quotient | noun | technical.mathematics | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | Same list. |
| 足す (たす, tasu) | to add | verb | technical.mathematics | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | Verb paired with 和 in the same Explanatory Notes list. |
| 引く (ひく, hiku) | to subtract | verb | technical.mathematics | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | Verb paired with 差. |
| 掛ける (かける, kakeru) | to multiply | verb | technical.mathematics | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | Verb paired with 積. |
| 割る (わる, waru) | to divide | verb | technical.mathematics | — | contemporary (1975/1982) | — | — | grammar_reference | n/a | verified | Verb paired with 商. |

**Note on the Weight/Frequency column.** *Comprehending Technical Japanese* (1975/1982) is unusual
among this sample in printing two numeric ranks per kanji directly in its kanji-list tables — one
for the ON reading, one for the KUN reading (e.g. 得: TOKU=850, e(ru)=1622) — which the book's own
front matter (Appendix A, "Kanji Frequency Lists," not itself sampled here) identifies as a real
frequency-dictionary-derived rank, not a pedagogical lesson-ordering artifact. This is the kind of
source that could legitimately populate the Weight/Frequency column per the extraction spec's rule
(a genuine frequency dictionary, as opposed to lesson order) — left as `—` above only because this
sampling pass did not cross-reference Appendix A's full rank table; a future full extraction of this
specific book could use it.

## Grammar points

### Lesson 0 (Davis Vol. 1, pp. 1-6): Review of Japanese Verb Forms

The book frames Japanese predicates as falling into three closing types: an い-adjective, a verb
(either an "ru"-verb or an "xu"-verb, using the book's own shorthand for the final-mora category),
or the copula (affirmative ～である or similar, negative ～で（は）ない). "Predicate" is used
collectively for all three. All Japanese verbs belong to the "ru" or "xu" category, with four
verbs (来る "kuru," する "suru," and two others referenced only by their irregular forms) treated
as irregular exceptions whose irregular forms are called out individually rather than assumed.

#### 0.1 Connective form (gerund)
Formed by replacing the final た/だ of the past-affirmative form with て/で (e.g., くる → きて
pattern). Negative connective form: final ない → なくて. Used to link clauses and as the base for
other special patterns discussed later in the book.

#### 0.2 Conjunctive form (infinitive/-masu stem)
Formed by dropping the final る from an ru-verb's present/future affirmative form, or changing the
final -u to -i for an xu-verb. Irregular: 来る → 来, する → し. Negative conjunctive form: final
ない → なく. Also used to link clauses; the book notes the conjunctive form often signals a
*greater* degree of independence between linked clauses than the connective form does.

#### 0.3 Passive verb
Formed by replacing る with られる (ru-verb) or xu with xa+れる (xu-verb); irregular 来る→来られる,
する→される. All passive verbs are themselves treated as ru-verbs for further conjugation. Used
for grammatical passive voice, and — the book flags this as a register note — "generally in
conversation," to raise politeness level, i.e. the passive form doubles as a colloquial politeness
strategy distinct from its literal passive-voice use.

#### 0.4 Potential verb
Formed by replacing る with られる (ru-verb) or xu with xe+る (xu-verb); irregular 来る→来られる,
する→できる. Indicates an action is (or isn't) possible. Note: for an ru-verb, the potential form
is identical in shape to the passive form (0.3) — ambiguity must be resolved from context.

#### 0.5 Connective form + いる
A verb's connective-affirmative form followed by いる indicates a continuing action or continuing
resultant state. Given examples (paraphrased, not direct quotes of the garbled source examples):
"has gone and is still there," "has come and is still here," "has become [and still is]." Also
notes that in written Japanese, a passive verb's connective form + いる is typically best rendered
in English as "is + past participle" (e.g. "is written," "is called"/"is known as"). Cross-
references pattern 4.6 for the connective form + おく combination.

#### 0.6 Provisional form
Formed by replacing る with れば (ru-verb) or xu with xe+ば (xu-verb); negative: final ない → なけれ
ば. Expresses an "if" conditional when the desired outcome is clearly understood and will be
realized provided a stated condition is met.

#### 0.7 Causative verb
Formed by replacing る with させる (ru-verb) or xu with xa+せる (xu-verb); irregular 来る→来させる,
する→させる. All causative verbs behave as ru-verbs thereafter. Indicates someone/something
causing or allowing someone/something else to carry out an action.

#### 0.8 Representative form (frequentative)
Formed by adding り to the past-affirmative form. Most frequently appears in the doubled pattern
V1たり V2たりする (or ...たりする), expressing a representative, non-exhaustive sample of actions
or states ("does things like V1 or V2"). Occasionally only one or three verbs appear in this
pattern rather than the canonical two.

#### 0.9 Tentative form (volitional)
Formed by replacing る with よう (ru-verb) or xu with xo+う (xu-verb); irregular 来る→来よう,
する→しよう. At the end of a sentence describing human action, expresses the speaker's will/
intention ("let's..."/"we shall..."); elsewhere expresses hesitation or uncertainty ("probably,"
"perhaps," "maybe"). Combined with ...とする, indicates either an (often unsuccessful) attempt to
carry out the action, or that the action is about to occur — context must disambiguate.

#### 0.10 Desiderative form
Formed by adding たい to the conjunctive-affirmative form (0.2); expresses the speaker's/writer's
wish to perform an action ("I/we wish to..."/"would like to..."). The desiderative form itself
conjugates as an い-adjective thereafter (e.g. negative: final い → くない).

### Lesson 1 (Davis Vol. 1, pp. 9-13): Grammatical Patterns 1.1-1.15

Fifteen patterns accompanying the Lesson 1 (Mathematics I) reading selections; paraphrased from
clean English explanatory prose (the source's own illustrative example sentences are kanji-garbled
in the text layer and were not vision-read at this sampling scale, so are omitted rather than
quoted unreliably).

- **1.1 (noun) という [to iu]** — "to name, to call, to know as." The book notes that when used
  simply as "noun という," it often just focuses the reader's attention on a technical term and
  need not be translated at all.
- **1.2 また [mata] and または [mata wa]** — また opens a sentence to add supporting/reinforcing
  information ("furthermore," "moreover," "in addition"). または sits between two nouns/noun
  phrases as a near-equivalent of logical "or," translatable as "and" or "or" depending on context.
- **1.3 に対して/に対し/に対する [ni taishite/ni taishi/ni taisuru]** — "with respect to, with
  regard to, for..." に対する modifies a following noun; に対して and に対し modify a following verb.
- **1.4 なる [naru] and 成り立つ [naritatsu]** — Two verbs built from the same two kanji, where the
  ON-reading verb (なる as 成る, paired with する) is more formal and the KUN-reading verb is more
  colloquial — an explicit register contrast the book calls out directly. Both cover four senses:
  "to be formed/organized/composed" (organizational), "to be realized/materialize/come into being"
  (abstract concept taking form), concluding/signing an agreement, and "to be valid/hold true" — the
  last sense was historically associated only with 成り立つ but is now used with both, and is
  especially common in technical Japanese.
- **1.5 により [ni yori]/によって [ni yotte]/による [ni yoru]** — "depending upon, due to, by means
  of." により/による modify a following noun; によって modifies a following verb.
- **1.6 において [ni oite]/につき [ni tsuki]** — "in, for, regarding." における modifies a noun;
  において modifies a verb. Noted as essentially equivalent in written Japanese to the double
  particle では, but more formal in tone — another explicit formal/informal register contrast.
- **1.7 あるいは [aruiwa]** — sits between two nouns/noun phrases to present them as unweighted
  alternatives; almost always translates as "or."
- **1.8 すべて [subete] and すべての [subete no]** — すべて alone can be a noun ("all, everything,
  the whole") or an adverb ("entirely, wholly, completely"); すべての modifies a following noun
  ("all of," "every," "the entire"). Context, not form, disambiguates noun vs. adverb use.
- **1.9 ただ [tada] and ただし [tadashi]** — ただの means "ordinary, hardly worth mentioning"; ただ
  alone can mean "free (of charge)" in recognizable contexts, but usually functions as an adverb
  ("only," "solely," "but," "however," "merely," "simply"). ただし means "however" or "provided
  that," though "here"/"in this case" is often the better translation when the writer is adding
  supplementary or expectation-contrary information. (Independently cross-validated by
  *Comprehending Technical Japanese*'s explicit note on ただし — see Vocabulary table.)
- **1.10 からなる [kara naru]** — "is composed of..., consists of..."
- **1.11 ならば [naraba]** — a shortened form of the provisional form of のである; "if" after a
  predicate, "if it is/if they are" after a noun. (Independently cross-validated by
  *Comprehending Technical Japanese*'s Lesson 2 vocabulary list — see Vocabulary table — a genuine
  convergent finding across two independently-authored technical-Japanese textbooks 27 years apart.)
- **1.12 かならず...で/かならずしも...でない [kanarazu/kanarazu shimo]** — かならず + affirmative
  predicate = "always/necessarily"; かならずしも + negative predicate = "not always/not
  necessarily."
- **1.13 かつ [katsu]** — comparable to また (1.2) but always sits between two nouns/noun phrases;
  closely matches logical "and," often "furthermore/moreover/in addition."
- **1.14 および [oyobi]** — links two nouns or symbols (either may carry its own modifier); means
  "and," but usage is limited — および cannot link two full clauses the way a conjunction would.
- **1.15 (heading garbled in text layer — likely いかなる...でも/いずれの [ikanaru.../izure no]
  "no matter what/which, any")** — used with a negated or universally-quantified predicate to
  express "no matter which X" / "any X whatsoever"; the sampled example context discusses a Cauchy
  sequence definition ("for any ε > 0...").

### Register contrast note (from *Comprehending Technical Japanese* Preface, p. 1, 1975/1982)

The authors state directly that modern technical/scientific written Japanese is "considerably more
direct in grammar and style" than literary or spoken Japanese, and that large portions of general
Japanese grammar are "entirely absent" from the technical register: humble and honorific verbs,
irregular counters, kinship-term vocabulary, the giving/receiving verb system (あげる/くれる/もらう
and their honorific forms), polite-request formulas, and the full greetings/apology hierarchy.
Causatives, desideratives, alternative forms, and the -masu conjugation are also described as
infrequent in this register (contrast with Davis's Lesson 0, above, which still teaches these forms
because Davis's corpus includes example/explanatory sentences, not just bare technical prose). This
is a direct, source-stated formal/technical-vs-colloquial register-contrast finding of exactly the
kind the extraction spec flags as high-value — technical Japanese is described by its own authors as
grammatically *reduced* relative to colloquial/literary Japanese, with the learning burden shifted
almost entirely onto kanji recognition rather than grammatical complexity.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. All grammar-
point explanations above are paraphrased from the sources' English prose; no garbled/vision-unread
Japanese example sentences were quoted. Vocabulary entries reproduce individual words/compounds
(standard dictionary-style short items), not bulk vocabulary-box transcription.
