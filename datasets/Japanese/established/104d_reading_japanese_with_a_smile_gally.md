# Japanese — Established Vocabulary/Grammar: *Reading Japanese with a Smile: Nine Stories from a Japanese Weekly Magazine for Intermediate Learners*

**Source:** Tom Gally, *Reading Japanese with a Smile: Nine Stories from a Japanese Weekly
Magazine for Intermediate Learners* (Japan & Stuff Press, 2007) — a revised/expanded edition of
Gally's 1997 Kodansha International book *Strange but True: A True-Life Japanese Reader* (chapter
9 is new to the 2007 edition). Source Japanese text is drawn from the "Dekigotology"
(デキゴトロジー) column in the weekly magazine *Shūkan Asahi* 週刊朝日, ca. early 1990s. Scanned,
image-only PDF, 91 PDF pages, no text layer (confirmed via `pdftotext`/`pdffonts`: zero output,
zero embedded fonts), 100% vision-read.

**Duplicate check:** already confirmed by the dispatching orchestrator as genuinely distinct from
the two "Read Real Japanese" titles in the same source folder (different author, different
magazine-sourced content, confirmed via this book's own title page and Contents page). Not
re-verified here.

## Coverage note — confirmed non-monotonic PDF page order (new gotcha instance)

**This PDF's physical scan order does not track printed-page order**, confirming a second instance
of the gotcha first documented for Japanese's *Zakennayo!* source (see
`00_Reference_Extraction_Spec.md`'s "PDF extraction gotchas" section). Empirically mapped PDF page
→ printed page correspondences found during this extraction:

| PDF page | Printed page(s) | Content |
|---|---|---|
| 1 | (unnumbered) | Title page |
| 2 | 134–135 | Chapter 7 annotations (7a–7b) |
| 5 | 140–141 | Chapter 7 annotations (7h–7j) |
| 8 | 146–147 | Chapter 8 story opening |
| 10 | 150–151 | Chapter 8 annotations (8a–8b) |
| 25 | 160–161 | Chapter 8 annotations (8n–8p) |
| 28 | 166–167 | Chapter 9 story opening |
| 32 | 174–175 | Chapter 9 annotations (9e–9g) |
| 36 | 182 | Chapter 9 annotations (9q, final) + Author's Profile |
| 38 | Contents (end) / 7 | Table of Contents + Introduction start |
| 39 | 8–9 | Introduction (methodology) |
| 42 | 14–15 | Chapter 1 story opening |
| 44 | 18–19 | Chapter 1 annotations (1a–1b) |
| 50 | 30–31 | Chapter 1 annotations (1q–1t, near end) |
| 43 | 36–37 | Chapter 2 story, near end |
| 47 | 44–45 | Chapter 2 annotations (2i–2k) |
| 58 | 66–67 | Chapter 3 annotations (3i–3j) |
| 60 | 70–71 | Chapter 3 annotations (3m–3n) |
| 66 | 82–83 | Chapter 4 annotations (4f–4g) |
| 70 | 90–91 | Chapter 4 annotations (4p) |
| 77 | 104–105 | Chapter 5 annotations (5j–5l) |
| 75 | 100–101 | Chapter 5 annotations (5d–5f) |
| 81 | 112–113 | Chapter 6 story opening |
| 84 | 118–119 | Chapter 6 annotations (6d–6f) |
| 85 | 120–121 | Chapter 6 annotations (6g–6i) |

The net effect: **the physical binding places the book's own final third (chapters 7–9, printed
pages ~130–182, plus the back-matter Author's Profile) at the very front of the PDF (pages 1–37)**,
before the front matter (Contents/Introduction, PDF pages 38–39) and before chapters 1–6, which
then run in their normal printed order across PDF pages ~40–91. Unlike the single-page *Zakennayo!*
case (one page bound out of sequence), this is a **large contiguous block (~37 PDF pages) displaced
to the front of the file**, not a single misplaced leaf — a new variant of the non-monotonic-order
gotcha worth distinguishing from the original single-page case for future readers. Confirmed by
reading the visible printed-page footer numbers directly; no fixed PDF-page-to-printed-page
arithmetic held, consistent with the dispatch brief's warning.

**Vision-reading guard:** no handwritten marginalia was found on any page vision-read for this
extraction — all content extracted below is genuinely typeset/printed source material. (A few pages
carry a faint vertical library-stamp watermark reading "ECKERD COLLEGE LIBRARY, ST. PETERSBURG, FL
33733" in the left margin — this is a library ownership stamp, not reader marginalia, and was
excluded from extraction as non-content either way.)

**Coverage strategy:** representative sampling per the dispatch brief (book is too large for
exhaustive page-by-page coverage). For each of the 9 chapters, 1–3 densely-annotated page-spreads
were vision-read (a mix of each chapter's opening boxes and later boxes), yielding a representative
sample of the chapter's vocabulary, verb-form derivations, and grammar/usage notes rather than
full-chapter transcription. English-side facing-page translations were read for comprehension only
and are not transcribed below (copyright discipline).

**Register skew:** per the dispatch brief, this source trends more colloquial/slang than a typical
literary reader, since its content is drawn from a tabloid-style weekly-magazine human-interest
column. Confirmed in practice — several chapters' content includes explicit euphemism/slang
(ホテトル "call girl," ピンクチラシ "sex-service flyer," ノーパン健康法 "no-underwear health
regimen," パンチパーマ "yakuza punch perm"), sentence-final colloquial contractions (でしょ, じゃ,
し), and annotated informal-speech patterns not typical of a textbook-style grammar reference.

**Attested Era (whole-source default):** contemporary (source published 2007; original magazine
column early 1990s). **Source Type (whole-source default):** `grammar_reference`. **Transcription
Confidence (whole-source default):** `n/a` (no text layer, source is 100% vision-read).

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 出来心（デキ心） dekigokoro | a sudden (usually bad) impulse | noun | colloquial | — | contemporary (source published 2007) | — | — | grammar_reference | n/a | verified | Ch.1 title. Katakana substituted for the usual kanji 出来心 as a playful emphasis device — a register-marking orthographic choice, not a different word. p.18. |
| 誠意 seii | honesty; sincerity | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Ch.1 title word. p.18. |
| 姑 shūtome | mother-in-law | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Noted as NOT among the 1,945 government-recommended 常用漢字 jōyō kanji — i.e. outside the "general use" list, though common in print. p.18-19. |
| 梅雨 tsuyu | the rainy season (all of Japan except Hokkaido, ~June) | noun | core | — | contemporary | national (excl. Hokkaido) | national | grammar_reference | n/a | verified | p.18-19. |
| 大感激 daikangeki | greatly moved; deeply touched | noun/na-adj | core | — | contemporary | — | — | grammar_reference | n/a | verified | 大- prefix "greatly" + 感激 "be moved." Ch.1, box 1q, p.30. |
| 吹聴して回る fuichō shite mawaru | to proclaim; spread the word (to one person after another) | verb phrase | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | 吹聴する "announce/spread news" + 回る emphasizing person-to-person repetition. Ch.1, box 1r, p.30. |
| 遭う au | to encounter (usually something unfortunate) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | One of three homophonous/near-homophonous verbs written differently by sense: 会う "meet/rendezvous," 合う "match/align," 遭う "encounter by chance, usually unfortunate." Ch.2, box 2i, p.44. |
| バレる bareru | to be revealed/found out (of a lie, secret, etc.) | verb | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Used of discovered lies/conspiracies/secrets. Ch.2, box 2k, p.45. |
| 間もなく ma mo naku | without even an interval; very soon | adverb/idiom | core | — | contemporary | — | — | grammar_reference | n/a | verified | Literally "without even an interval." Ch.2, box 2k, p.45. |
| 浮気 uwaki | infidelity; affair | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Ch.3 central plot term (journal concealing an affair). p.66-67, 70-71. |
| ゾクゾクしちゃう zokuzoku shichau | to shiver with excitement | verb (colloquial contraction) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | ぞくぞくする + してしまう contracted to -しちゃう, a common spoken contraction. Ch.3, box 3m, p.70. |
| ガラス張り garasubari | (metaphor) visible/exposed to the public | noun/idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Literally "lined with glass (visible from outside)." Extended sense: information openly known. Ch.3, box 3n, p.70-71. |
| フィクションってことになってるし fikushon tte koto ni natte iru shi | it's supposed to be fiction (and so on) | phrase | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Contraction of ...ということになっている + sentence-final listing-particle し. Ch.3, box 3n, p.71. |
| パンチパーマ panchi pāma | "punch perm" — a tightly permed hairstyle associated with yakuza | noun | slang | — | contemporary | — | — | grammar_reference | n/a | verified | Explicit cultural note: used to signal gangster/yakuza affiliation visually. Ch.4, box 4f, p.82. |
| お帰りなさいませっ okaerinasaimasett | Welcome home! (extra-polite, clipped) | interjection | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Especially polite version of standard お帰りなさい; small っ marks an abrupt glottal-stop halt, here suggesting tough yakuza-flavored speech. Ch.4, box 4g, p.83. |
| ノイローゼ noirōze | nervous breakdown; neurosis | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Loanword from German *Neurose* (cognate with English "neurosis"); more formal synonym 神経症 shinkeishō given. Ch.4, box 4p, p.90-91. |
| 寸前 sunzen | just before; on the verge of | suffix | core | — | contemporary | — | — | grammar_reference | n/a | verified | Productive suffix, also seen in 出発寸前 "just before departing," ゴール寸前 "just before the goal." Ch.4, box 4p, p.90-91. |
| 困る komaru | to be at a loss; uncertain how to deal with (an undesirable situation) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Ch.4, box 4p, p.90. |
| 洋式便座を拭う濡れナプキン yōshiki benza o nuguu nure-napukin | moistened wipes for Western-style toilet seats | noun phrase | technical | — | contemporary | national | national | grammar_reference | n/a | verified | Noted as a retail-marketed product ("市販されている"). Ch.5, box 5d, p.100. |
| 拭き拭きする fukifuki suru | to wipe repeatedly/vigorously | verb (reduplicated) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Reduplication of 拭く "wipe," noted as having "a somewhat childish ring." Ch.5, box 5d, p.100. |
| 念を入れる nen o ireru | to be careful | idiom | core | — | contemporary | — | — | grammar_reference | n/a | verified | 念 = "thought/feeling." Ch.5, box 5f, p.101. |
| 散らばり放題 chirabari hōdai | scattered about with total abandon | noun phrase | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | -放題 suffix after a verb's -masu stem = "doing X with complete freedom" (also やり放題 "do whatever you want," 食べ放題 "all you can eat"). Ch.5, box 5j, p.104. |
| 洋服 yōfuku | Western-style clothing | noun | core | — | contemporary | — | — | grammar_reference | n/a | verified | Contrasted with 和服 wafuku "Japanese-style clothing." Ch.5, box 5j, p.104. |
| 何げなく nanigenaku | casually; without any particular concern | adverb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Ch.5, box 5l, p.105. |
| ダメ dame | forbidden; no good; worthless | na-adjective | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Katakana substitution for emphasis (standard forms だめ/駄目). Ch.6, before 6g, p.120. |
| お目め o-meme | eyes (child-directed/baby talk) | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Explicitly glossed as "a word used only by or to small children." Related baby-talk set given: お手て otete "hand," わんわん wanwan "dog," ぶうぶう būbū "automobile." Ch.6, box 6g, p.120. |
| 整形してる seikei shiteru | has had plastic surgery (colloquial -ている contraction) | verb phrase | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | 整形している contracted to -してる, spoken register. 整形 can refer to any body-reshaping surgery/treatment. Ch.6, box 6h, p.120. |
| 二重／一重 futae / hitoe (mabuta) | double-fold / single-fold eyelid | noun | technical | — | contemporary | — | — | grammar_reference | n/a | verified | Cultural note: most East Asians naturally have 一重瞼 "single eyelids"; some Japanese undergo surgery for a fold. Ch.6, box 6h-6i, p.120-121. |
| 情操教育 jōsō kyōiku | moral and aesthetic education (for a child) | noun phrase | formal | — | contemporary | — | — | grammar_reference | n/a | verified | Used sarcastically in-text (marked with quotation marks in the source) to describe a mother's rather petty running commentary. Ch.6, box 6d, p.118. |
| 付き合っちゃ tsukiatcha | (don't) be friends with/spend time with | verb (contracted, word-order inverted) | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Standard order would be あんな子と付き合ってはダメよ; the sentence as spoken reverses clause order and contracts 付き合っては→付き合っちゃ, a natural-speech pattern explicitly flagged by the source as "reversed." A man would instead say ダメ (without よ). Ch.6, box 6f, p.119. |
| バン国 Bankoku | "the country of Ban" (a mishearing of バンコク "Bangkok") | proper noun (eggcorn) | slang | — | contemporary | — | — | grammar_reference | n/a | verified | Ch.7 title concept — an explicit misinterpretation/mishearing joke running through the whole chapter. p.134. |
| コネ社員 kone shain | an employee hired through personal connections | noun phrase | slang | — | contemporary | — | — | grammar_reference | n/a | verified | コネ is an abbreviation of コネクション "connection." Typically the child of a former colleague/executive. p.134. |
| 無知蒙昧 muchi-mōmai | utter/profound ignorance | noun (yojijukugo) | formal | — | contemporary | — | — | grammar_reference | n/a | verified | 無知 "no knowledge" + 蒙昧 "darkness; ignorance" — a four-character compound, ch.7 title. p.134. |
| 一般職 ／ 総合職 ippanshoku / sōgōshoku | support-track (non-promotable) vs. career-track employee tiers | noun pair | technical | — | contemporary | national | national | grammar_reference | n/a | verified | Sociolinguistically loaded Japanese corporate-employment terms; 一般職 disproportionately applied to women. p.135. |
| えっと ētto / だって datte | contrastive/surprise interjections | interjection | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | えっ(と) shortened from ええ, shows surprise; だって used in speech to assert a fact contradicting another's statement/assumption. Ch.7, boxes 7h-7j, p.140-141. |
| お坊っちゃま o-botchama | rich, coddled young man (extra-polite/mocking) | noun | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Child-language-derived politeness escalation: ちゃん (child form) → さん → even-politer さま; here used with mild sarcasm of an adult. Ch.8, box 8a, p.150. |
| 飲尿健康法 innyō kenkōhō | urine-drinking health method | noun phrase | slang | — | contemporary | national | national | grammar_reference | n/a | verified | Explicit cultural note: a fringe-but-real alternative-health practice among a minority of Japanese, advocated by a few doctors, not widely followed. p.150. |
| 憂鬱 yūutsu | depression; melancholy | noun/na-adj | core | — | contemporary | — | — | grammar_reference | n/a | verified | Ch.8 title word; flagged by the source as a kanji worth learning to impress people (alt. form 鬱). p.150. |
| ノーパン健康法 nōpan kenkōhō | "no-underwear health method" | noun phrase | taboo | — | contemporary | — | — | grammar_reference | n/a | verified | パン abbreviates パンツ "underpants"/panty. Ch.8, box 8n, p.160. |
| ホテトル嬢 hoteturu-jō | call girl (lit. "hotel-call woman") | noun | taboo | — | contemporary | national | national | grammar_reference | n/a | verified | Ch.9 title term for a call-girl/escort service worker. p.166. |
| ピンクチラシ pinku chirashi | advertising flyer for a sex-related business | noun phrase | taboo | — | contemporary | national | national | grammar_reference | n/a | verified | ピンク "pink" = euphemism for sex-related; チラシ = small printed ad flyer, often posted by public phones or left in mailboxes. Ch.9, box 9e, p.174. |
| しっぽをつかむ shippo o tsukamu | to reveal a person's weaknesses or secrets | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | verified | Literally "to grab by the tail." Ch.9, box 9q, p.182. |
| 聞き出す kikidasu | to extract information (from someone reluctant to reveal it) | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Ch.9, box 9q, p.182. |
| 帰郷する kikyō suru | to return to one's home town | verb | core | — | contemporary | — | — | grammar_reference | n/a | verified | Ch.9, box 9q, p.182. |

## Grammar points

### にする "to decide on/choose" (Ch.7)
The にする pattern marks a choice among options — e.g. タイにしたの? "did you decide on
Thailand?" (box 7h, p.140).

### Sentence-final explanatory/question の with disambiguating punctuation (Ch.7)
A sentence ending in の in informal women's speech can be either an explanatory statement or a
question depending on falling vs. rising intonation, which written text cannot show directly;
Gally notes that in this source, a question mark is used whenever the context alone wouldn't
disambiguate (question marks are otherwise not standard in Japanese except where ambiguity is
possible — e.g. sentences that don't end in か or an interrogative pronoun). Box 7h, p.140.

### だって as a contrastive-assertion particle (Ch.7)
だって in speech asserts a fact that contradicts what someone else just said or assumed — distinct
from だって as "even" elsewhere. Box 7h, p.140.

### っ marking abrupt glottal-stop emphasis (Ch.4, Ch.7)
A small っ not pronounced as a doubled consonant ("t"/"tsu") but instead marking a sudden halting
of the voice — used for emotional emphasis/abruptness in speech (e.g. えっ, お帰りなさいませっ). Seen
in ch.7 (box 7h) and ch.4 (box 4g, p.83) in a tough/yakuza-flavored greeting.

### パン- abbreviation of パンツ (Ch.8)
ノーパン abbreviates パンツ "underpants/panties" to パン, a clipping pattern. Box 8n, p.160.

### Sentence-final こと as command/prohibition (Ch.8)
こと at the end of a sentence indicates a strong command or prohibition, frequently seen on public
signs (e.g. タバコを吸わないこと "No Smoking"). Box 8p, p.161.

### 末 sue "after an extended period/process" (Ch.8)
末 after a duration phrase (e.g. 三日間悩んだ末 "after three days of agonizing") means "at the end
of" that period or process. Box 8o, p.160.

### -放題 hōdai "doing X without restraint" (Ch.5)
Attached to a verb's -masu stem, -放題 indicates an action performed with complete freedom/no
limits: 散らばり放題 "scattered everywhere," やり放題 "do whatever you want," 食べ放題
"all-you-can-eat." Box 5j, p.104.

### Reduplication for a "childish"/repetitive register (Ch.5, Ch.6)
拭き拭きする (reduplicated 拭く "wipe") is noted as carrying "a somewhat childish ring" through
reduplication — paralleling the baby-talk vocabulary set in ch.6 (お目め, お手て, わんわん,
ぶうぶう), which productively uses reduplicated/simplified forms for child-directed speech. Ch.5
box 5d (p.100); ch.6 box 6g (p.120).

### ならぬ — literary negative suffix (Ch.6)
はならぬ is the literary/written-register form of はならない "must not," built on the archaic
negative suffix ぬ in place of colloquial ない. Seen in indirect-speech narration of a parent's
intention (遅れてはならぬ). Box before 6d, p.118.

### でしょ as a contracted spoken form of でしょう (Ch.6)
でしょ is an abbreviated, informal spoken form of でしょう, the volitional/presumptive form of the
copula だ, used in casual confirmation-seeking statements (砂をかけてるでしょ "she's throwing
sand, isn't she"). Box 6e, p.118.

### Clause-final し for nonexhaustive listing (Ch.3)
The clause-ending particle し means roughly "too; in addition," used when listing examples or
reasons that lead to a conclusion without necessarily being an exhaustive list. Confirmed across
two separate boxes (3i, p.66 and 3n, p.71) — "two more examples appear in 3n," per the source's
own cross-reference.

### Scrambled/inverted colloquial word order for emphasis (Ch.6)
A quoted line of speech (あんな子と付き合っちゃ, box 6f, p.119) reverses the standard clause order
of あんな子と付き合ってはダメよ ("don't be friends with a girl like that") — the source explicitly
flags this inversion as a natural colloquial-speech pattern, not an error, alongside the
contraction of ～ては to ～ちゃ.

### 遭う／合う／会う — one verb, three kanji by sense (Ch.2)
The verb /au/ is written differently depending on meaning: 会う for "meet/rendezvous with (a
person)," 合う for "match/align," and 遭う for "encounter by chance" — the last typically reserved
for unfortunate chance encounters. Box 2i, p.44.

### こそ concessive "even though only..." (Ch.8, noted from earlier chapter content read during
scanning)
大学こそ二流だが ("though it's only a second-tier university...") uses こそ to concede a limiting
fact before pivoting to a contrasting point — not tabulated as a vocabulary row since it was only
briefly observed in passing text, but worth flagging as a grammar pattern present in this source's
register of casual asides. p.146.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. English-side facing-page translations were read for
comprehension only and are not reproduced here. See `../../00_Reference_Extraction_Spec.md`.
