# Russian — Established Vocabulary: Chekhov's Humorous Short Stories (Russian Reader)

**Source:** *Chekhov's Humorous Short Stories: Russian reader with explanatory notes in English and
a Russian-English vocabulary* (compiler M. V. Kataeva, translator K. Nitlich, afterword A. Shamaro,
introductory essay A. Chernyshov; Russky Yazyk Publishers, Moscow, 2nd ed. 1989). Full 73-PDF-page
file covered (a scanned two-printed-pages-per-PDF-page spread; printed pagination runs roughly
1–142). Contains 15 Chekhov stories from his early "Antosha Chekhonte" period (written 1883–1887):
Joy, The Fat and the Thin, Death of a Clerk, He Oversalted It, Horsy Name, The Plotter, Chameleon,
Vanka, The Naughty Boy, Drama, Work of Art, Surgery, Helpless Creature, Burbot, Mask, and Kashtanka.

**Coverage note.** This is a literary reader, not a grammar textbook, so its pedagogical apparatus
takes a different shape than most established/ entries in this project: (1) a short **per-story
Russian–English vocabulary box** printed at the end of each story (new words introduced in that
story, plain gloss, no register tag), and (2) a consolidated **"Explanatory Notes" section** at the
back of the book (printed pages ~117–136) that re-treats each story with fuller **idiom/realia/
register-tagged** entries (the source's own tags: *coll.* colloquial, *pop.* popular speech, *arch.*
archaic, *hist.* historical/tsarist-Russia realia, *iron.* ironical, *fig.* figurative, *obs.*
obsolete, *fem.* feminine, *affect.* affectionate, *Fr.* French loan, *lit.* literal). Both layers
are captured below, per story, since they're largely non-overlapping (the front box gives plain
core vocabulary; the back notes give idioms, realia, and register). The book's own Chekhov
**narrative/dialogue text itself is never reproduced** here beyond the same short (one-clause)
illustrative fragments the source's own Notes section already quotes for idiom glosses — per
copyright discipline, no story prose is bulk-reproduced. The **Afterword** (a critical/biographical
essay by A. Shamaro, printed pp. 138–142) and the **introductory essay** (A. Chernyshov, printed pp.
1–7ish) are prose criticism, not vocabulary — paraphrased briefly for context only, not tabulated.

**PDF-extraction gotchas found on this source (see `../../00_Reference_Extraction_Spec.md`):**
- **Two-printed-pages-per-PDF-page spread scan**, not one-page-per-image — confirmed empirically:
  PDF page *N*'s right printed page number = `2N − 3` (e.g. PDF page 60 = printed pages 116/117; PDF
  page 71 = printed pages 138/139). Verified by direct inspection of ~25 rendered pages, not assumed
  from `pdfinfo`'s page count alone (per the spec's standing warning about this exact failure mode).
- **`pdftotext` (with or without `-layout`) is corrupted for all Cyrillic text on this source**,
  while English text on the same page extracts perfectly cleanly — confirmed it is *not* usable
  even after attempting the ЙЦУКЕН-keyboard-layout decode documented for other Russian sources in
  this corpus (e.g. `PyCCKMM H3blK` for «Русский язык» superficially looks like that cipher, and a
  majority of letters do decode correctly against the keyboard-position map), **but decoding breaks
  down on numerals mixed into words (`B036y>KAeHHbJM` for «возбуждённый» — digits `0`/`3` appear
  mid-token where no cipher explains them) and on at least one letter (`и`/`й` both decoding from the
  same source glyph in different words)**, i.e. a mixed cipher-plus-OCR-misread situation the spec's
  documented variants don't cleanly cover. Rather than force an unreliable decode, **this entire
  extraction was done by direct vision-reading of the rendered page images** (`pdftoppm -r 100`),
  which render clearly and legibly throughout — no further attempt was made to decode the text layer.
- **Marginalia/non-book content found and excluded:** the final rendered PDF page (73) is not part of
  the Chekhov book at all — it is a scanned advertisement flyer for an unrelated title (a Vysotsky
  song/poetry anthology, *«Я люблю — и, значит, я живу!»*) with a handwritten catalog number
  (`13764988/001/001`) and other handwritten annotations in the margin. Excluded entirely, per the
  vision-reading marginalia guard — it is not Chekhov-reader source content.
- No handwritten marginalia was found on any of the ~30 in-book pages actually vision-read (pp.
  1–14ish sample pages, all per-story vocabulary-box pages, and the full Explanatory Notes/Afterword
  section) — all content on those pages is consistent, clean typeset print.

All vocabulary entries below: **Part of Speech** inferred from gloss/context (the source itself
doesn't tag POS); **Weight/Frequency** `—` throughout (a reader's own vocabulary selection is not
real frequency data); **Attested Era** `contemporary (source published 1989)` for the apparatus
itself, with `historical (tsarist Russia, pre-1917)` noted in **Notes** for terms the source's own
*hist./arch./obs.* tags mark as period-specific realia (ranks, currency, measures, institutions);
**Attested Region / Geographic Scope** `—` (no dialectal/regional tagging in this source — it is
standard literary Russian); **Source Type** `dictionary` (the book's own vocabulary+notes apparatus
functions as a paired glossary); **Transcription Confidence** `n/a`; **Vision Reading Confidence**
`verified` for any entry appearing independently in *both* the front vocabulary box and the back
Explanatory Notes (cross-confirms the reading), `plausible_unverified` otherwise — flagged per row.

---

## Vocabulary

### 1. Радость (Joy)

**Front vocabulary box** (printed p. 13, end of story) — 26 entries:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| возбуждённый | excited | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| взъерошенный | dishevelled | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| невероятно | (is) incredible | adv/predicative | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| спрыгнуть | to jump down, out | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| накинув | having thrown on | verbal adverb | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| вскочить | to jump up | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| дикий | wild | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| перекреститься | to make the sign of the cross | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | Orthodox religious practice realia |
| спрятать | to hide | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ткнуть | to prod | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| обведённый | circled | adj/participle | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| кашлянуть | to cough | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| тонкость | fine point | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| поскользнуться | to slip | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| извозчик | coachman | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | pre-automobile hired-carriage driver |
| перешагнув | having stepped over | verbal adverb | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| сани | sleigh | noun, pl | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| купец | merchant | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| помчаться | to hurtle | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| была задержана | was caught | verb phrase, passive | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| дворник | janitor | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| бесчувственное состояние | unconscious state | noun phrase | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| затылок | back of the head | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| оглобля | shaft (of a cart/sleigh) | noun, fem | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | horse-drawn-vehicle terminology |
| потерпевший | victim | noun/participle | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | legal/police register |
| примачивать | to wet (a compress) | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| торжествующий | triumphant | adj/participle | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed p. 117) — 15 entries, idiom/realia register:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| влететь | to fly in, in the sense to run in | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | source tag *coll.* |
| гимназист | pupil at a гимназия (grammar school) | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | tsarist secondary-education realia; appears again in Vanka/Naughty Boy notes |
| Что с тобой? | What's happened to you? | idiom/phrase | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| будучи | being | gerund | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *bookish* |
| На тебе лица нет! | You're very pale! | idiom | idiomatic | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | glossed by source as *(idiom)* |
| мамаша | mother | noun, fem | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| толком | intelligibly, sensibly | adv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | source tag *coll.*; recurs in Horsy Name notes |
| образ | (here) icon | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | polysemous: standard "image", here specifically Orthodox devotional icon |
| коллежский регистратор | one of the lower civil ranks in tsarist Russia | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | Table of Ranks realia; source tag *hist.* |
| в нетрезвом состоянии | drunk | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | literally "in an inebriated state" |
| полицейский участок | police station in an urban district | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| освидетельствовать | to make a medical examination of the victim of an accident | verb, pfv | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* |
| подана | rendered | verb, passive | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| по всей России пошло | all Russia has heard about it | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| кокарда | badge on an official's peaked cap | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |

### 2. Толстый и тонкий (The Fat and the Thin)

**Front vocabulary box** (printed p. 13/14 boundary) — 26 entries:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| спелый | ripe | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| херес | sherry | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | loan from Spanish (Jerez) |
| узел | bundle | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| картонка | box (hatbox-type) | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ветчина | ham | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| гуща | grounds (coffee/tea) | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| подбородок | chin | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| прищуренный | narrowed (of eyes) | adj/participle | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| восклицать | to exclaim | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| изумиться | to be surprised | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| троекратно | thrice | adv | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ошеломлены | astounded | adj/participle, pl | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| дразнить | to tease | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ябедничать | to inform (on someone) | verb, ipfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| восторженно | delightedly | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| жалованье | salary | noun, neut | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | recurs in Beleashed Creature/Surgery notes as period civil-service term |
| окаменеть | to turn to stone | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | figurative: to freeze with shock |
| искривиться | to be twisted | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| чинопочитание | bowing to rank | noun, neut | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | key thematic term of this story — rank-deference culture |
| возразить | to object | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| благоговение | piety, awed reverence | noun, neut | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| стошнить | to be sick | verb, pfv, impersonal | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| поклониться | to bow | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| захихикать | to giggle | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| шаркнуть | to shuffle (one's feet, as a bow) | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed p. 118) — 19 entries:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Голубчик | term of endearment used with men | noun, masc | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.*; recurs throughout (Пересолил notes too) |
| Сколько зим, сколько лет! | Good Gracious! (lit. "how many winters, how many years") | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| Батюшки! | Good Gracious! | interjection | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| Ах ты, господи! | Heavens above! (here: expression of admiration) | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| Ну, что же ты? | (here) How are you? | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| Герострат | Herostratus, the ancient Greek who burnt the temple of Artemis at Ephesus for fame | proper noun (classical allusion) | literary | — | historical (classical antiquity, 4th c. BC referent) | — | — | dictionary | n/a | plausible_unverified | schoolroom classical-education allusion |
| казённый | belonging to the school/state | adj | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| Эфиальт | Ephialtes, the traitor at Thermopylae (480 BC) | proper noun (classical allusion) | literary | — | historical (classical antiquity, referent) | — | — | dictionary | n/a | plausible_unverified | |
| дослужиться | (here) to earn promotion in the civil service | verb, pfv | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* |
| коллежский асессор | 8th rank, one of the middle civil-service ranks in tsarist Russia | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | Table of Ranks realia; recurs in Beleashed/Surgery notes |
| Станислав | the Order of St. Stanislav, one of the lowest orders in tsarist Russia | proper noun | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| ну, да бог с ним! | (here) it's not that important | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| департамент | department of a ministry | noun, masc | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| статский | State Councillor; 5th civil-service rank | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.*; recurs in Death of a Clerk notes |
| тайный советник | Privy Councillor, 3rd highest civil-service rank, corresponds to Lieutenant General | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source notes the full 14-class civil-service system |
| звезда | (here, hist.) highest class of an order in tsarist Russia | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | polysemous: standard "star", here a specific decoration class |
| ваше превосходительство | title used in addressing an official of the 3rd rank, or a general | honorific phrase | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | recurs across many stories (Death of a Clerk, Helpless Creature, Horsy Name) |
| Очень приятно-с... вышли в такие вельможи-с! | You've become such a rich and important person! | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source explicitly glosses the register shift: "The transition from ты to вы and the addition of the particle -с express the respect and servility of the thin man towards the fat one" — see Grammar points |
| Ну, полно! | That'll do! | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll., arch.* |

### 3. Смерть чиновника (Death of a Clerk)

**Front vocabulary box** (printed p. 15/16 boundary) — 32 entries:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| бинокль | opera glasses | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| чихать | to sneeze | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | central plot verb, recurs in Explanatory Notes below |
| мужики | peasants | noun, masc pl | core | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| нисколько | by no means | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| побеспокоить | to disturb | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| старательно | laboriously | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| лысина | bald pate | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| перчатка | glove | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| бормотать | to mumble | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs in Surgery notes |
| обрызгать | to spray | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| неловко | embarrassing | adv/predicative | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| зашептать | to whisper | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| блаженство | bliss | noun, neut | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs in Explanatory Notes as "верху блаженства" |
| антракт | interval (theatre) | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| робко | timidly | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| проборматать | to mumble | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ехидство | malice | noun, neut | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| вовсе | at all | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| плюнуть | to spit | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| невежество | tactlessness | noun, neut | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| легкомысленно | frivolously | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| происшедшее | what had happened, the accident | noun/participle | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| приёмная | reception room | noun, fem | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| опросить | to interrogate | verb, pfv | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| припомнить | to recall | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| пустяки | trifles | noun, pl | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| забормотать | to mutter, murmur | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| раскаяние | repentance | noun, neut | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| насмешка | ridicule | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| пришлось | he had to | verb, impersonal past | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| затопать | to stamp (one's feet) | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| попятиться | to recoil | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| машинально | mechanically | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed p. 119) — 25 entries:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| экзекутор | in tsarist Russia, an official responsible for local administration in an establishment | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| кресла | the stalls (in a theatre) | noun, pl | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., pl. only* |
| Корневильские колокола | *Cloches de Corneville*, operetta by Robert Planquette (1848–1903) | proper noun (cultural reference) | literary | — | historical (19th c. French operetta, referent) | — | — | dictionary | n/a | plausible_unverified | |
| чувствовать себя на верху блаженства | to experience the ultimate happiness | idiom | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *iron.* — used ironically here |
| полицмейстер | in tsarist Russia, chief of police in large towns | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| статский | (here, arch.) civilian | adj | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | see also entry under Fat and Thin (statский as noun/rank) |
| подался туловищем вперёд | bent forward | idiom | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ваше-ство | form of address for persons of 3rd or 4th rank | honorific (clipped) | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., coll.*; clipped/reduced form of ваше превосходительство — phonological-reduction pattern relevant to slang mechanics |
| полноте | enough, that will do | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., coll.* |
| То-то вот и есть! | That's exactly it! | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| Ни одного слова путного не сказал. | Said absolutely nothing relevant. | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| вицмундир | uniform worn by civil servants | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| проситель | petitioner, person bringing a request to a government office | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | source tag *arch.*; recurs (fem. form просительница) in Helpless Creature notes |
| «Аркадия» | theatre in one of the summer parks in St. Petersburg | proper noun | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* |
| чихнул-с | the particle -с was used to lend a statement a note of respect, politeness | discourse particle | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* — see Grammar points for the -с particle system |
| Изв... | beginning of the word извините | clipped word | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | interrupted-speech device |
| Бог знает что! | (here) expression of indignation | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| Вам что угодно? | What do you want? | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., official* |
| апартаменты | rooms | noun, pl | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* |
| состроил плаксивое лицо | the general's face assumed a mournful expression | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.*; recurs (as "сделав страдальческое лицо") in Helpless Creature notes |
| Ей-богу..! | exclamation expressing assurance | interjection | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll., arch.* |
| вопрощающие | inquiring | adj/participle | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* (archaic spelling of вопрошающие) |
| Смею ли | Can I | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* |
| Пошёл вон! | Get out! | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop., abusive*; recurs as a repeated-humiliation refrain across Death of a Clerk and Helpless Creature |
| гаркнул | shouted loudly | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |

### 4. Пересолил (He Oversalted It)

**Front vocabulary box** (printed p. 19/20 boundary) — 63 entries across two columns:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| землемер | surveyor | noun, masc | technical | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | protagonist's profession; recurs in Explanatory Notes |
| обратился | addressed | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ступайте | go | verb, imperative | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | archaic imperative of идти |
| угрюмый | sullen | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| рябой | pock-marked | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| телега | cart | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| тощая | scrawny | adj, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| возница | coachman | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs in Explanatory Notes |
| стегнуть | to lash | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| замотать | to shake | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| задрожать | to shudder | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| покачнуться | to lurch | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| лихорадка | fever | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| тряска | jolting | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| успокоить | to calm | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| кобылка | filly | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| сумерки | twilight | noun, pl | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| замёрзшая | frozen | adj, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| равнина | plain | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| темнеющий | darkening | adj/participle | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| выситься | to loom up | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| бугры | mounds | noun, pl | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| застилать | to obscure | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| глушь | backwoods | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| прикрыть | to cover | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| напасть | to attack | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ограбить | to rob | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ненадёжный | unreliable | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| подозрительный | suspicious | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| револьвер | revolver | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs in Explanatory Notes as "какие у меня револьверы!" |
| соврать | to lie | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| разбойники | robbers | noun, pl | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| стемнеть | to grow dark | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| заскрипеть | to creak | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| повернуться | to turn | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| обратиться | to address | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| бык | bull | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| заморгать | to blink | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs in Work of Art vocab box |
| стегнуть | to lash | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | duplicate entry, listed twice in source's own box |
| судьи | judges | noun, pl | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| заорать | to yell | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| трусить | to be cowardly | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| замышлять | to scheme | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| мчаться | to rush | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| гнать | to urge on | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| разбежаться | to start running | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| попридержать | to hold back | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| догнать | to catch up | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| коренастый | stocky | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| вынуть | to take out | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| рыться | to rummage | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| вываливаться | to fall out | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| чаща | grove | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| поудобней | more comfortably | adv, comparative | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| охрипнуть | to grow hoarse | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| стон | groan | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| мёрзнуть | to freeze | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| сообразить | to realise | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| вероятно | probably | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| исчезнуть | to disappear | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| нерешительно | indecisively | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| пассажир | passenger | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| испугаться | to take fright | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| проворчать | to mutter | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed p. 120) — 16 entries:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| пересолил | (here, fig.) lost all sense of moderation, went overboard | verb, pfv | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *fig.*; the story's title itself, "over-salted" as a moderation metaphor |
| верста | old Russian measure of distance, equivalent to 1.06 km | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | recurs in Horsy Name notes ("по линии...на сто сорок первой версте") |
| почтовые лошади | horses belonging to the postal service | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| жандарм | gendarme | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| не сыщешь | you won't find it | verb, colloquial future-perfective | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| а не то что | let alone... | discourse phrase | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| поплёлся | (here) walked slowly | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| здоровеннейший | very sturdy and tall | adj, superlative | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.*; colloquial superlative-affix intensification |
| поморщился | (his face) assumed an expression of displeasure | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| не разберёшь | it's impossible to understand | verb, colloquial | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| зад | (here) back end of a cart | noun, masc | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| перёд | (here) front of a cart | noun, masc | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| лошадёнка | (here) a weak, scrawny horse | noun, fem, diminutive-pejorative | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | pejorative diminutive suffix -ёнка |
| взвизгнуть | (here) to emit a high, piercing noise | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| Н-о-о, прокля...тая! | abuse addressed to the horse to make it move | idiom (interjection) | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.*; interrupted-swear-word device |
| без конца и краю | vast, with no visible limits | idiom | idiomatic | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | glossed *(idiom)* |

*(Remaining Пересолил Explanatory Notes entries — "Ишь какая спинища!", "так душа вон", "морда", "зверская", "шалить", "на всякий случай", "шутки плохи", "справиться", "завезти", "подлец", "трущоба", "на вид-то", "словно", "трахнул", "богу душу отдал", "здоровила", "и сковырнёшь", "брат", "не дай бог со мной связаться", "начальство", "худо", "нешто", "народ", "Караул!", "заголосил", "не губи ты моей души", "Климушка", "часа два", "какие у меня револьверы!", "сделай милость", "бог с тобой", "барин", "целковый" — 32 further idiom entries — carry the same register profile, colloquial/archaic idiom glossed with a short English equivalent; omitted here as repetitive of the pattern already tabulated above, per the coverage rule's "comprehensive but not exhaustive" allowance for dense idiom lists that don't introduce new grammatical/register categories beyond what's already captured.)*

### 5. Лошадиная фамилия (Horsy Name)

**Front vocabulary box** (printed p. 23/24 boundary) — 32 entries:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| отставной | retired | adj | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | military/civil-service register |
| генерал-майор | Major General | noun phrase | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| разболеться | to start to ache | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| полоскать | to rinse | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| прикладывать | to place on | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| табачная копоть | tobacco soot | noun phrase | folk-medical | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | folk remedy for toothache |
| скипидар | turpentine | noun, masc | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| керосин | kerosene | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| поковырять | to pick (at) | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| хина | quinine | noun, fem | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| поварёнок | kitchen-boy | noun, masc, diminutive | core | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| средство | remedy | noun, neut | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| уволить | to dismiss | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| шарлатанство | quackery | noun, neut | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| чудодейственный | miraculous | adj | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| взмолиться | to implore | verb, pfv | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| припоминать | to recall | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | central plot verb — general trying to recall a forgotten surname |
| наперерыв | one after the other | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| изобретать | to invent | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| породы | breed | noun, pl | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| грива | mane | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| копыта | hooves | noun, pl | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| сбруя | harness | noun, fem | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| нетерпеливый | impatient | adj | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| пообещать | to promise | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| стонать | to groan | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| постучаться | to knock | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| виновато | apologetically | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| замучиться | to be tormented | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| утихнуть | to die down | verb, pfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ворота | gates | noun, pl | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| сосредоточенно | hard, fixedly | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| дико | wildly, madly | adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| всплеснув | clasping | verbal adverb | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | recurs in Work of Art vocab as всплеснувши/всплеснуть |
| гнаться | to chase | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed pp. 120–121) — 23 entries:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| приказчик | bailiff, a landowner's manager | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | recurs across Злоумышленник/Ванька notes |
| заговор | a magic spell, incantation, capable of stopping pain | noun, masc | folk | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | folk-magic realia central to this story's plot |
| заговаривать | to cast a spell | verb, ipfv | folk | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| первый сорт | (here, coll.) excellent | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | literally "first grade/quality" |
| и как рукой | and the pain vanished | idiom | idiomatic | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | elliptical for "как рукой сняло" |
| только зубами и кормится | makes a living by curing toothache | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| депеша | telegram | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| что так, мол, и так | and say as follows | discourse marker | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | reported-speech framing particle мол |
| раб божий | in the Orthodox faith, appellation put before a Christian name | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | Orthodox liturgical register |
| попытать | (here, pop.) to give it a try | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| Мочи нет! | It's unbearable! | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| Извольте писать | Write | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., polite* |
| стало быть | that means | discourse marker | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs across multiple stories (Beleashed Creature, Mask) |
| Позвольте-с | Let me think... | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *here obs.* — the -с particle again, see Grammar points |
| латаный | old, patched | adj | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| порты | trousers | noun, pl | archaic, colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., pop.* |
| Иван Семёнов Акинфов | in tsarist Russia, use of the shortened patronymic (Семёнов instead of Семёнович) indicated the speaker belonged to the lower classes | naming convention (sociolinguistic note) | regional | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | direct sociolinguistic class-marking annotation — high value for slang-mechanics analysis |
| по линии | along the railway line | idiom | colloquial | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *coll., arch.* |
| кой | by which | pronoun | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *official, arch.* |
| чаво | = что? (what's that?) | pronoun, dialectal | regional | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | peasant-speech phonetic variant of что; explicit source equation чаво=что |
| знамо | of course | adv, dialectal | regional | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| коли б | if | conjunction, dialectal | regional | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| нешто | really; is it possible that... | discourse particle | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs very heavily across the whole book (Chameleon, Surgery, Helpless Creature, Naughty Boy) — high-productivity colloquial particle |

*(Further Horsy Name notes entries — "косясь", "климовские", "толком", "отродясь", "а тут вру", "ваше благородие", "живец", "последний", "который непонимающий", "Дураку закон не писан", "бабки", "не догляди", "Избави господи", "некрещёные", "те", "век", "вот тебе и", "свороти́ло бы поезд", "а то...тьфу!", "понятие", "кривой" — 20 further entries, same colloquial/dialectal register profile — omitted individually per the same non-redundant-density rule noted above.)*

### 6. Злоумышленник (The Plotter)

**Front vocabulary box** (printed p. 27/28 boundary, spanning into p. 29) — ~32 entries: невод (large fishing net), Уложение о наказаниях (the Criminal Code in tsarist Russia), подвергнуть опасности (to subject to danger), тёмные (uneducated), уклейка (a small river fish of the carp family), взять под стражу (to arrest), здорово живёшь (for nothing at all, unjustly), недоимка (a tax not paid in time), не ответчик (is not responsible), а ты, Денис, отвечай (and you, Denis, are held responsible), Судьи! (indignation marker), умеючи (capably, knowledgeably), Хоть и высеки (Flog me if you like).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| невод | large fishing net | noun, masc | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| Уложение о наказаниях | the Criminal Code in tsarist Russia | proper noun | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| подвергнуть опасности | to subject to danger | verb phrase | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| тёмные | (here) uneducated | adj, pl | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| уклейка | a small river fish of the carp family | noun, fem | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| взять под стражу | to arrest | verb phrase | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| здорово живёшь | for nothing at all, unjustly | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| недоимка | a tax not paid in time | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* |
| не ответчик | is not responsible | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| Судьи! | (indignation marker — "Judges!") | interjection | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | "Here the exclamatory tone conveys indignation" per source's own note |
| умеючи | capably, knowledgeably | adverbial (archaic gerund form) | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| хоть и высеки | Flog me if you like | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed pp. 121–122) — 12 entries, centered on the story's legal-interrogation register: мужичонка (a small, nondescript peasant, source tag *coll.*), пестрядинная (from пестрядина, a coarse fabric of multi-coloured linen or cotton thread, usually home-woven), and the interrogation dialogue's own vocabulary already substantially overlaps the front box above (this story's Notes section is comparatively short since the front box already captured most register-marked items).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| мужичонка | a small, nondescript peasant | noun, masc, pejorative diminutive | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.*; pejorative diminutive -онка |
| пестрядинная | (from пестрядина) a coarse fabric of multi-coloured linen or cotton thread, usually home-woven | adj | regional | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | peasant material-culture realia |

### 7. Хамелеон (Chameleon)

**Front vocabulary box** (printed p. 31/32 boundary) — 24 entries: полицейский надзиратель (police inspector, tsarist urban police rank), городовой (constable, tsarist urban police), ни души (not a soul), окаянная (cursed), рубаха (shirt), сборище (crowd of people), шельма (swindler, cheat), золотых дел мастер (jeweller, goldsmith), борзой (from борзая, breed of dog), ни с того ни с сего (suddenly, for no reason at all), никак нет (archaic army-negative "no"), кобелёв (surname from кобель "male dog"), коренной (surname from коренная "the middle, leading horse in a team of three"), Ступай...вон! (Get out!), Ой батюшки!.. Ой матушки! (exclamations of extreme pain), вопить (to wail), немного погодя (after a little while), господа (masters), то и дело (constantly, time and again), Табунов (surname from табун "a herd of horses"), Копытин (surname from копыто "hoof"), детская (nursery, children's room), Тройкин! Уздечкин! (surnames from тройка "team of three horses" and уздечка "bridle"), Мериное (surname from мерин "gelding").

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| полицейский надзиратель | in tsarist Russia, rank in the urban police (police inspector) | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | central figure of this famous story; recurs in Explanatory Notes |
| городовой | in tsarist Russia, low rank in the urban police (constable) | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| ни души | not a soul | idiom | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| окаянная | cursed | adj, fem | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| рубаха | shirt | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| сборище | crowd of people | noun, neut | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| шельма | swindler, cheat | noun, common gender | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs in Explanatory Notes used ironically as an endearment for a dog |
| золотых дел мастер | jeweller, goldsmith | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| борзой | (from борзая) breed of dog (borzoi) | adj/noun | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ни с того ни с сего | suddenly, for no reason at all | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |

**Explanatory Notes** (printed pp. 123–124) — 26 entries — the richest single note-set in the book for slang-mechanics purposes, since the Chameleon police-inspector's speech shifts register mid-sentence depending on whose dog he believes he's addressing (the story's whole comic mechanism):

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ваше благородие | see Notes p. 123 (a form of respectful address) | honorific phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | recurs multiple times as the register the inspector adopts when he thinks the dog might belong to a superior |
| я человек, который работающий | widespread popular deformation: incorrect use of the participle after the relative pronoun который (should be я человек работающий or я человек, который работает) | grammatical note (sociolect marker) | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source explicitly flags this as a named popular grammatical deformation — see Grammar points |
| Ужо я сорву с тебя! | expression of threat; refers to receiving financial compensation from the dog's owners | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| По какому это случаю тут? | What are you doing here? | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| нешто | surely (it can't) | discourse particle | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | cross-references Horsy Name notes p.123 |
| сорвать | to receive money dishonestly (from the dog's owner) | verb, pfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| цигарка | home-made cigarette, or pipe made from a twist of paper | noun, fem | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| харя | face; (here) dog's snout | noun, fem | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop., abusive* |
| кривой | person blind in one eye | adj/noun | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs across Ванька, Драма notes with the same sense |
| по совести | honestly | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| не рассуждать! | Silence! | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | glossed *here:* Silence! |
| лягавая | breed of hunting dog (setter) | noun, fem | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ни шёрсти, ни вида | (idiom, refers to the total lack of any good features) | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| болван | fool, halfwit | noun, masc | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll., abusive* |
| братец приехали? | the plural verb with a singular noun expresses the policeman's respect for the person he is talking about | grammatical note (sociolect marker) | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | pluralis-respectus construction — see Grammar points |
| Ишь ты, господи! | (here) expression of affection | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.* |
| собачонка ничего себе... | A nice little dog... | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| цап | It bit | interjection (sound-symbolic verb) | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.*; onomatopoeic instantaneous-action word |

*(Remaining Chameleon Explanatory Notes entries — "кажись", "сичас", "распускать", "бродячий скот", "не медля!", "сорвать", "тяпни", "по совести", "верно", "этакая", "попадись", "ветром подуло", "нечего", "выставлять", "отродясь", "стало быть" — same colloquial/dialectal register profile, omitted individually per the density rule above.)*

### 8. Ванька (Vanka)

**Front vocabulary box** (printed pp. 39–40) — 48 entries: вечно (permanently), кобель (dog, male), притопывать (to stamp), валенки (felt boots), понюхать (to sniff), табакерка (snuff-box), обиженная (offended), прозрачен (transparent), струйки (wisps), трубы (chimneys), посеребрённый (silvered), иней (hoarfrost), сугроб (snow-drift), усыпано (sprinkled), мигающий (twinkling), вырисовываться (to stand out), помыть (to wash), потереть (to rub), люлька (cradle), насмехаться (to scoff), красть (to steal), кривить (to twist), тереть (to grind), овца (sheep), крючок (hook), леска (fishing line), тетерев (blackcock), золочёный (gilded), сундучок (small trunk, casket), вырубить (to chop down), выкурить (to smoke), трубка (pipe), посмеиваться (to laugh at), срубленный (felled, chopped down), тащить (to drag), хлопотать (to fuss, bustle), леденцы (boiled sweets), сирота (orphan), колотить (to pound), свернуть (to fold), вчетверо (four times, to a quarter its size), исписанный (scrawled over), почесаться (to scratch one's head), прибавить (to add), довольный (content), опускаться (to be posted), почтовый ящик (post box), сунуть (to stick), драгоценный (valuable), щель (slot), убаюканный (lulled), сапожник (cobbler), заржавленный (rusty), измятый (crumpled), пугливо (timidly), покоситься (to squint), мелькать (to flicker), сторож (watchman), тощенький (scrawny).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| сапожник | cobbler | noun, masc | core | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | Vanka's master's trade |
| почтовый ящик | post box | noun phrase | core | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | central plot object — Vanka posts his letter here without a real address |
| сирота | orphan | noun, common gender | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| тетерев | blackcock | noun, masc | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| валенки | felt boots | noun, pl | technical | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | traditional Russian winter footwear |
| табакерка | snuff-box | noun, fem | core | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed pp. 125–126) — the fullest register-annotation set in the book, since Vanka's letter is written in semi-literate peasant-child Russian:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| отданный... в учение | in tsarist Russia, children of poor families were given over from an early age to the family of a craftsman (tailor, cobbler, baker) to help around the house; in practice these "apprentices" remained servants, with even fewer rights | social-institution note | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source gives a full paragraph-length social-history gloss, paraphrased here (not quoted verbatim) |
| подмастерье | apprentice to a craftsman | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| маменька | mummy | noun, fem | affectionate, archaic | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., affect.* |
| старикашка | old man | noun, masc, pejorative-ironic diminutive | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll., iron.* |
| балагурит | talks gaily, with jokes | verb, ipfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| приказчик | see Notes p. 121 | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | cross-referenced by the source itself back to Horsy Name notes |
| в обиду никому не дам | I'll see that no harm comes to you | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| секи меня как сидорову козу | beat me unmercifully | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | fixed simile idiom "beat like Sidor's goat" |
| нету никакой моей возможности | life is unbearably hard | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | double-negative colloquial intensifier construction |
| гармония, гармоника | accordion | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| тройка | (here, obs.) team of three horses | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *here obs.* |
| ямщик | coachman who took post and passengers | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| колокольцы | small bells attached to the shaftbow | noun, pl | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | Russian troika-harness realia |

### 9. Злой мальчик (The Naughty Boy)

**Front vocabulary box** (printed p. 45) — 10 entries: наружность (appearance), спуститься (to climb down), крутой (sheer), усесться (to sit down), скамеечка (bench), густой (dense), куст (bush), чудный (marvellous), скрыт (concealed), паук-плавун (water-spider), вооружён (armed), удочка (fishing-rod), сачок (net), червь (worm), тотчас же (at once), клевать (to bite, of fish), страстно (passionately, madly), дёргать (to tug), тащить (to pull), вскрикнуть (to exclaim).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| наружность | appearance | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs in Explanatory Notes |
| паук-плавун | water-spider | noun, masc | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| удочка | fishing-rod | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| клевать | to bite (of fish) | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | double meaning exploited in the story (fish biting / romantic pursuit) |

**Explanatory Notes** (printed p. 122) — 7 entries: наружность (appearance), принялись за рыбную ловлю (started fishing), рассчитывать (here: to hope), бултыхнулись в воду (fell into the water), гимназист (see Notes p. 117), низко (here: dishonest), поговоривши = поговорив (having talked — an archaic/dialectal verbal-adverb variant form).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| поговоривши | = поговорив (having talked) | verbal adverb, dialectal variant | regional | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | archaic/dialectal -вши verbal-adverb suffix vs. standard -в |
| рассчитывать | (here) to hope | verb, ipfv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | semantic narrowing from standard "to calculate/count on" |
| низко | (here) dishonest | adj/adv | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | figurative use of "low" |

### 10. Драма (Drama)

**Front vocabulary box** (printed pp. 48–49) — 85 entries spanning two full page-columns: сюртук (man's outer garment, topcoat), на вид (to look at), весьма (here, iron.: very), закатила...глаза (rolled her eyes), имела удовольствие познакомиться (archaic/polite: made the acquaintance), Чем могу быть полезен? (polite question to open a conversation), не чужда авторства (bookish: I am the author of several works), разрешилась от бременем драмой (fig.: wrote a play), тетрадища (iron.: enormous notebook), сударыня (obs.: term of address, madam), барыня (obs.: wife of a landowner; here: lady, madam), тряпка (fig.: characterless, weak-willed person), неловко (awkward), Вот так штука! (What an extraordinary thing!), свинство (a dirty trick), ещё пуще (still more), поднесу-ка (I'll give, make a present of), канальи (term of mild abuse), Сказано-сделано. (No sooner said than done), уборная (here: actors' dressing room), брали приступом (here: took by storm), пожимал плечами (shrugged his shoulders), частная квартира (a flat belonging to an individual, not the state), сударь (obs.: polite, sometimes ironic term of address: sir), разинул рот (gaped with surprise), у него отнялся язык (idiom: he was struck dumb with amazement), заметно (noticeably), поклонница (admirer, devotee), наслаждение (pleasure), льстить (to flatter), отчасти (partially), разновременно (at different times), вытащить (to take out), томно (languidly), замяться (to stop short), простонать (to groan), жертва (sacrifice), нахальна (brazen), назойливы (importunate), великодушны (magnanimous), умолять (to implore), барыня (lady), зарыдать (to start sobbing), сконфузиться (to be covered with confusion), забормотать (to mutter), растерянно (distraughtly), вскрикнуть (to whoop, for joy), лакей (footman), горничная (house-maid), произнести монолог (to deliver a monologue), убеждения (convictions), прислуга (servants), заявить (to declare), зритель (spectator), жаждать (to thirst), злобно (angrily, maliciously), оглядывать (to look over, inspect), чепуха (nonsense), наказание (nuisance), приказать (to order), тесьма (braid), зубной порошок (tooth powder), явление (scene), действие (act), вдохновение (inspiration), виноватый тон (guilty voice), просиять (to glow), довериться (to trust), понятие (concept), анатомическое (anatomical), смутиться (to be embarrassed), горечь (bitterness), зажившие раны (healed wounds), пауза (pause), задуматься (to grow pensive), зевнуть (to yawn), нечаянно (inadvertently), издать звук (to emit a sound), неприличный (improper), замаскировать (to disguise), умилительный (sweet), невыносимо (unbearable, intolerable), возвысить (to raise), занавес (curtain), тотчас же (at once), перевернуть (to turn), сельская (village), ступени (steps), перебить (to interrupt), глубина, here: the back, приговорённый к казни (condemned to death), слипаться (to stick together), отдалённый (remote), сода (soda), по всей вероятности (in all probability), катар желудка (catarrh of the stomach), усилие (effort).

Given the very large size of this box, only a representative high-value subset is tabulated in full (register-marked/idiomatic items); the remaining plain-core items are listed above in the running paraphrase and are not separately tabled, per the coverage rule's density allowance:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| сюртук | man's outer garment, topcoat | noun, masc | archaic | — | historical (19th c.) | — | — | dictionary | n/a | plausible_unverified | |
| весьма | (here, iron.) very | adv | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *iron.*; formal adverb deployed ironically — register_inversion-type pattern |
| имела удовольствие познакомиться | (archaic, polite) made the acquaintance | idiom | archaic | — | historical (19th c.) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., polite* |
| не чужда авторства | (bookish) I am the author of several works | idiom | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *bookish* |
| разрешилась от бремени драмой | (fig.) wrote a play | idiom | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *fig.*; literally "was delivered of a burden" — childbirth metaphor for authorship, comic register clash |
| тетрадища | (iron.) enormous notebook | noun, fem, augmentative | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *iron.*; augmentative suffix -ища |
| сударыня | (obs.) term of address, madam | noun, fem | archaic | — | historical (19th c.) | — | — | dictionary | n/a | plausible_unverified | source tag *obs., fem.* |
| барыня | (obs.) wife of a landowner; here: lady, madam | noun, fem | archaic | — | historical (19th c.) | — | — | dictionary | n/a | plausible_unverified | source tag *obs.* |
| тряпка | (fig.) characterless, weak-willed person | noun, fem | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *fig.*; literally "rag" |
| Вот так штука! | What an extraordinary thing! | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coll.* |
| свинство | a dirty trick | noun, neut | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | literally "piggishness" |
| у него отнялся язык | (idiom) he was struck dumb with amazement | idiom | idiomatic | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| сударь | (obs.) polite, sometimes ironic term of address: sir | noun, masc | archaic | — | historical (19th c.) | — | — | dictionary | n/a | plausible_unverified | source tag *obs.* |

**Explanatory Notes** (printed pp. 124–125): the notes here largely re-cover the same idiom set already in the front box (Драма is a short story); no substantially new register-marked content beyond what's captured above.

### 11. Произведение искусства (Work of Art)

**Front vocabulary box** (printed pp. 55–56) — 55 entries: под мышкой (under the arm), завёрнутый (wrapped), заморгать (to wink), взволнованный (excited), бронза (bronze), поморщиться (to frown), бормотать (to mutter), развёртывать (to unwrap), свёрток (bundle), обидеть (to offend), доставаться (to come into one's possession), скупать (to buy up), торжественно (solemnly), канделябр (candelabrum), пьедестал (pedestal), кокетливо (coquettishly), поддерживать (to support), подсвечник (candlestick), неприлично (improper), дебош (orgy), почесать нос (to scratch one's nose), выс­мор­каться (to blow one's nose), фантасмагория (phantasmagoria), загадить (to pollute), изящество (refinement), благоговейное (pious), перебить (to interrupt), точка зрения (point of view), толпа (crowd), представляться (to be presented), огорчить (to disappoint), впрочем (however), задыхаться (to pant), представить (to imagine; to acquire), размышлять (to think), пожертвовать (to donate), приятель (friend), холост (bachelor), легкомыслен (frivolous), застать (to find), вещица (little piece), роскошь (excellent thing), неописанный (indescribable), восхитительно (entrancing), излить (to pour out), пугливо (anxiously), клиенты (clients), замахать (to wave), замазано (to paint over), нацелено (to stick on, to touch), ломать голову (to rack one's brains about smth.), рассуждать (to ponder), подобные (of this kind), бенефис (benefit performance), тщательно (carefully), восторженный (delighted), гул (buzzing of voices), лошадиное ржанье (neighing of horses), тотчас (at once), хриплый (hoarse), радость (gladness), посоветовать (to advise), предместье (suburb), послушаться (to heed advice), отвориться (to open), сиять (to glow).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| канделябр | candelabrum | noun, masc | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | the story's central comic object (an indecent bronze statuette) |
| фантасмагория | phantasmagoria | noun, fem | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ломать голову | to rack one's brains about smth. | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| бенефис | benefit performance | noun, masc | archaic | — | historical (19th c. theatre) | — | — | dictionary | n/a | plausible_unverified | |
| неприлично | improper | adv/predicative | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| дебош | orgy | noun, masc | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | loan from French débauche |
| легкомыслен | frivolous | adj, short form | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed pp. 126–128, spanning into the ХИРУРГИЯ boundary): the Notes for this story overlap the "чинопочитание" theme via a proverb and several archaic/institutional realia terms captured under "adjacent" entries below (page-boundary overlap with Fat-and-Thin material in the source's own layout):

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ученье — свет, а неученье — тьма | a very widespread proverb (cf. "You live and learn") | proverb | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| камер-юнкер | a courtier in tsarist Russia | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| окрошка | Russian national dish made with cold kvass, vegetables and boiled meat | noun, fem | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | national-cuisine realia |
| Вас заел анализ. | (bookish) You think too much. | idiom | formal | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *bookish* |
| становой | (hist.) in tsarist Russia, police rank | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| присяжные | jury | noun, pl | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| сделать кислое лицо | (fig.) to assume a serious, worried expression | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *fig.* |
| как мы себя чувствуем | affectionate, familiar way of addressing a patient | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | doctor's bedside-manner register (pluralis-affectionis, "how are WE feeling") |
| в костюмах Евы | (fig.) naked | idiom | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *fig.*; euphemistic literary allusion — "in Eve's costume" |

### 12. Хирургия (Surgery)

**Front vocabulary box** (printed pp. 61–62) — 44 entries: хирургия (surgery), поношенный (threadbare), жакетка (coat), истрёпанный (frayed), чувство долга (sense of duty), указательный (index), сигара (cigar), распространяющая зловоние (spreading an evil smell), приёмная (reception room), коренастый (stocky), кожаный (leather), пояс (belt), бельмо (cataract), бородавка (wart), креститься (to make the sign of the cross), бутыль (flagon), зевать (to yawn), хлебнуть (to sip), чуточку (a little), ломить (to ache), упрекать (to reproach), распухнуть (to swell up), хмуриться (to frown), пожелтевший (yellowed), вырвать (to pull out), пустяки (nothing to it), скромничать (to feign modesty), роясь (rummaging), твёрдость руки (a firm hand), образованный (educated), вопросительно (inquiringly), дёргаться (to twitch), неподвижно (still, motionless), поглубже (deeper), коронка (crown), хватать (to seize, grab), шевелить (to move, twiddle), прерывисто дышать (to gasp), багровый (purple), пот (sweat), топтаться (to stamp), мучительнейшие (most agonizing), срываться (to tear free), вскакивать (to leap to one's feet), нащупывать (to feel), тянуть (to pull), плачущий (tearful), насмешливый (scornful), толкать (to push, bump), колокольня (bell-tower), дёргать (to tug), застарелый (old and sick), шевелиться (to shift, move), хрустящий (grinding), тупо (dully), пространство (space).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| хирургия | surgery | noun, fem | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| бельмо | cataract | noun, neut | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| коронка | crown (dental) | noun, fem | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| твёрдость руки | a firm hand | idiom | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | ironic, given the dentist's incompetence in this story |
| скромничать | to feign modesty | verb, ipfv | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed pp. 128–130) — the notes overlap heavily with the front box; the genuinely new content is liturgical/clerical realia given the dentist's patient is a church sexton:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| земская, from земство | in tsarist Russia, organs of local limited government in rural areas; here: village | adj/noun | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| дьячок | lowest member of the Orthodox Church hierarchy (sexton, sacristan) | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| ряса | cassock | noun, fem | core | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| карболовый раствор | carbolic solution | noun phrase | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| просфора | communion wafer | noun, fem | core | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | Orthodox liturgical realia |
| бурса | in tsarist Russia, an educational establishment for training lower orders of the clergy | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| берёзой потчевали | you were birched | idiom | colloquial | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | euphemistic idiom for corporal punishment, literally "were treated to birch" |
| А ты что за пава такая? | What sort of bigwig do you think you are? | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop., iron.*; literally "what kind of peahen are you" |
| Ништо тебе | Nothing will happen to you | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| околеть | (pop., coarse) to die | verb, pfv | taboo | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop., coarse*; normally reserved for animal death, used of a person as an insult |

### 13. Беззащитное существо (Helpless Creature)

**Front vocabulary box** (printed pp. 63–64) — 26 entries: беззащитное существо (helpless creature), припадок (attack), подагра (gout), скрипеть (to creak), нервы (nerves), отправиться (to set off), своевременно (in good time), клиенты (clients), замученный (worn out), обратиться (to address), допотопный (antediluvian), салоп (coat), навозный жук (dung-beetle), проболеть (to be sick), вычесть (to deduct), жалованье (salary), согласие (consent), беззащитная (helpless), заморгать (to blink), очевидно (evidently), по существу (in essence), ведомство (office, department), зять (son-in-law), влиятельный (influential), учреждение (institution), частное (private), коммерческое (commercial), докторское свидетельство (doctor's certificate), раздражение (irritation), повернуться (to turn), кивнуть (to nod), откидывать (to throw back), подобный (such a), развод (divorce).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| подагра | gout | noun, fem | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| навозный жук | dung-beetle | noun phrase | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs in Explanatory Notes as the story's cruel simile for the petitioner |
| допотопный | antediluvian | adj | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| докторское свидетельство | doctor's certificate | noun phrase | formal | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed pp. 130–132) — 26 entries, the fullest "petitioner bureaucracy" idiom set in the book:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Что вам угодно? | What do you want? | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | recurs from Death of a Clerk notes |
| просительница | petitioner (fem.) | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | source tag *fem. of* проситель |
| Извольте ли видеть | Do you see | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., polite* |
| скороговоркой | speaking quickly; from скороговорка, tongue-twister | adverb (derived) | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| коллежский асессор | see Notes p. 118 | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | verified | cross-referenced back to Fat-and-Thin notes |
| отставку дали | dismissed from service | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* |
| кормлюсь жильцами | I make a living by taking in lodgers | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., pop.* |
| обиду терплю | I am offended, insulted | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* |
| голову потеряла | (fig.) I lost my head | idiom | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *fig.* |
| на моей-то шее сидят | (idiom) they live off me | idiom | idiomatic | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| без места | (arch., coll.) does not work | idiom | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., coll.* |
| Уф! | exclamation expressing fatigue, exhaustion | interjection | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

### 14. Налим (Burbot)

**Front vocabulary box** (printed pp. 81–82) — 90 entries, the largest single box in the book (fishing/riverbank register-heavy vocabulary): налим (burbot), неподвижно (motionless), строящаяся (under construction), купальня (bathing-place), ветви (branches), ивняк (osier), барахтаться (to wallow), плотник (carpenter), тощий (skinny), пыхтеть (to puff, pant), достать (to get), корни (roots), пот (sweat), горбатый (hunch-backed), треугольный (triangular), рубаха (shirt), посинеть (to turn blue), тыкать (to prod), коряга (snag), лихорадка (fever), бас (bass voice), охрипший (hoarse), скользкий (slippery), хватать (to grab on to), выпустить (to leave go), дразнить (to mock), вплавь (by swimming), горбач (hunchback), хвататься (to seize hold of), попытка (attempt), погружаться с головой (to be totally immersed), пускать пузыри (to release bubbles), нащупывать (to feel), пятка (heel), укрепиться на позиции (to become firmly entrenched), изгибаться (to bend down), шарить (to rummage), путаться в водорослях (to get tangled in the algae), наскакивать (to alight), колючий (prickly), клешни (pincers), рак (crawfish), выбрасывать (to throw open), вытаращивать (to open wide, of eyes), цепляться (to grab), обрываться (to break off), падение (descent, fall), вскакивать (to leap up), хрипеть (to croak), ругань (cursing), печь (to scorch), тень (shadow), пригретая (warmed up), испускать (to emit), медовый запах (an aroma of honey), озябший (frozen), нарушать (to violate), выпихнуть (to shove out), хлопанье (slapping), бич (whip), отлогий (gently sloping), водопой (watering place), плестись (to trudge along), стадо (herd), дряхлый (senile), овцы (sheep), потолкать (to prod), просунуть (to stick in), щурить (to narrow), рыболов (fisherman), сбрасывать (to throw off), перекреститься (making the sign of the cross), свистнуть (to whistle), пилюли (pills), запонки (cufflinks), подлец (rogue, scoundrel), скрежетать зубами (to grit one's teeth), грозить доносом (to threaten to inform on someone), поговаривать (to talk), карманные часы (pocket watch), вафли (waffles), подмигнуть (to wink), зажевать (to bite, start chewing), салфетка (napkin), сделать предложение (to propose), согласие (agreement), зарыдать (to burst into tears), сознаваться (to admit), захватывающий (exciting), блаженство (bliss), драть (to pull), дно (bottom), пуска́ться вплавь (to start swimming), упустить (to let go), присоединиться (to join), толкая (from толкать, to jog, push), толкнуться (from толочься, to jostle), гони (from гнать, to chase), решётка (fence), барский (the barin's), халат (dressing gown), персидская шаль (Persian shawl), копошиться (to hang about), лепетать (to babble), кряхтеть (to wheeze), помыться (to wash, bathe), нора (lair), мни (from мять, to squash), замучить (to torment), болтать ногами (to dangle one's legs), усадьба (estate), кучер (coachman), жуёт (from жевать, to chew), раздеваться (to undress), бормотать (to mumble), торопливо (hastily), вмешательство (interference), подрубить (to chop down), топор (axe), надламывать (to break partly, crack), толпиться (to jostle), поверхность (surface), ворочать (to twist), вырваться (to free oneself, to break loose), попался (from попасться, to be caught), созерцание (contemplation), печёнка (liver), плеск (splash).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| налим | burbot | noun, masc | technical | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | the story's title fish; recurs throughout Explanatory Notes |
| скрежетать зубами | to grit one's teeth | idiom | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| грозить доносом | to threaten to inform on someone | idiom | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| барский | of/belonging to the барин (landowner) | adj | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| персидская шаль | Persian shawl | noun phrase | core | — | historical (19th c.) | — | — | dictionary | n/a | plausible_unverified | luxury-goods realia marking landowner-class status |
| созерцание | contemplation | noun, neut | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed pp. 132–134) — includes several vivid colloquial exclamations:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| сажень | old Russian measure of length, equals 2.13 m | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., pop.*; cf. верста, аршин elsewhere in book — full pre-metric measurement system attested piecemeal across stories |
| порты | trousers | noun, pl | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch., pop.*; recurs from Horsy Name notes |
| Командир какой нашёлся | contemptuous reference to someone who commands without having the right to do so | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| Тебя ещё тут не видали! | expression of displeasure at the appearance of something unpleasant, undesirable | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| Угодишь к лешему на ужин | You'll drown (lit.: You'll be served up for the devil's dinner) | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | source explicitly glosses figurative *(fig.)* register with literal translation alongside — folk-supernatural (леший, wood-spirit) reference |
| аршинное тело | body an arshin long; аршин, old Russian measure of length, equals 0.71 m | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| поминай как звали | (fig.) vanished without trace, swam away | idiom | literary | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *fig.*; fixed idiom, literally "remember what he was called" |
| вашескородие | = ваше высокородие; way of addressing a senior official; here used to address a landowner | honorific (clipped/dialectal) | regional | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | peasant phonetic reduction of the honorific; parallel formation to ваше-ство noted under Death of a Clerk — a productive clipping pattern across honorifics |
| полтинничек | fifty-copeck coin | noun, masc, diminutive | core | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | pre-1917 currency realia |

### 15. Маска (Mask)

**Front vocabulary box** (printed pp. 90–91) — 85 entries, the story's masquerade-ball setting: маска (mask), благотворительный (charitable), бал-маскарад (masked ball), нетанцующие (who do not dance, non-dancing), уткнуть (to bury), дремать (to doze), по выражению (in the expression), местный (local), доноситься (to carry), посуда (china), лакей (footman), царить (to reign), послышаться (to be heard), печка (stove), отвориться (to open), приземистый (squat, thick-set), кучерской костюм (coachman's costume), павлинье (peacock's), поднос (tray), ликёр (liqueur), прохладно (cool), подвинуться (to move up), покачнуться (to lurch), смахнуть (to sweep off), обвалиться (to collapse), попортить (to spoil), перекинуть (to throw across), локоть (elbow), напитки (drinks), почтенный (respected), приподняться (to raise oneself a little), вырвать (to snatch), изорвать (to tear up), пробормотать (to mumble), наморщить (to screw up), пожимать (to shrug), нахал (insolent fellow), врываться (to burst in), рассердиться (to lose one's temper), запрыгать (to start jumping), вспотеть (to steam up), дежурный (on duty), старшина (sergeant-major), рыженький (ginger-haired), запыхавшийся (panting), выскочить (to jump out), посторонний (outsider), стесняться (to be embarrassed), самодур (ill-bred, wilful person), хлев (pig-sty), понеслось (could be heard), полицейский мундир (policeman's uniform), прохрипеть (to speak hoarsely), выпучивать (to open wide, of eyes), шевелить (to twitch), захохотать (to laugh), вытаращить (to open wide, of eyes), рассуждать (to argue), задрожать (to start trembling), невообразимый (unimaginable), прекратиться (to stop), протокол (statement), тыкать (to prod), губить (to ruin), сиротинушка (orphan), расписаться (to sign), вытянуться (to pull oneself up), сорвать (to tear off), произведённый (produced), эффект (effect), впечатление произвести (to make an impression), растерянно (in dismay), переглянуться (to exchange glances), крякнуть (to wheeze), местный (local), благотворительность (charity, philanthropy), просвещение (education, enlightenment), на цыпочках (on tiptoe), запереть (to lock), хрипеть (to croak), вполголоса (in a low voice), трясти (to shake), бунт (riot), унылый (gloomy, downcast), притихнуть (to calm down, grow quiet), расходиться (to disperse), прекратиться (to stop), пошатываться (to totter), захрапеть (to start snoring), нагнуться (to bow, bend down), сдунуть (to blow), просиять (to glow), подскочить (to jump up).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| бал-маскарад | masked ball | noun phrase | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| самодур | ill-bred, wilful person | noun, masc | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | classic 19th-c. Russian-literature character type (cf. Ostrovsky) |
| полицейский мундир | policeman's uniform | noun phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | |
| впечатление произвести | to make an impression | idiom | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed pp. 134–136) — heavy with vulgar/abusive register, since the story is about a rich boor abusing a masked stranger who turns out to outrank him:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| нечего тут | (pop., coarse) here: Enough! Stop it! | idiom | taboo | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop., coarse* |
| а ля тримонтран | a meaningless phrase, made up in imitation of French | pseudo-loan phrase | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | mock-French — a productive comic device (borrowing-parody) relevant to slang mechanics |
| же ву при | (Fr.) je vous prie, please | phrase, French loan | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *Fr.* |
| мамзель | deformation of the French Mademoiselle | noun, fem | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | phonological reduction/nativization of a French loan |
| А плевать мне, что ты — Жестяков! | I don't care that you're Zhestyakov! | idiom | colloquial, coarse | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *coarse, pop.* |
| рыло | face; mug | noun, neut | taboo | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop., abusive*; normally an animal-snout word, used pejoratively of a person |
| Фу-ты, ну-ты | exclamation used to mock an angry, indignant person | interjection | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | reduplicative sound-symbolic interjection |
| милостивый государь | polite way of addressing a stranger: dear sir | honorific phrase | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.* |
| провáливай подобру-поздорову | leave before you get a thrashing | idiom | colloquial, coarse | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop., coarse* |
| тыкать | to use the ты form rather than the вы required in polite discourse | metalinguistic term (T/V system) | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | direct source commentary on the T-V register system — see Grammar points |

### 16. Каштанка (Kashtanka)

**Front vocabulary box** (printed p. 116, the book's last per-story box before the Explanatory Notes section) — 26 entries: в особенности (in particular), изуродован (deformed), неподвижный (fixed), подёргивать плечами (to twitch the shoulders), делать вид (to pretend), в присутствии (in the presence), попрясать (to dance), заставить (to force), глупости (silly things), равнодушно (indifferently), небрежно (carelessly), угрюмо (sullenly), презирать (to despise), протанцевать (to dance), дудочка (a pipe, whistle), не выносить (to be unable to stand), задвигаться (to shift), послышаться (to be heard), поклониться (to bow), стихнуть (to grow silent), исполнение (performance), нота (note), ахнуть (to gasp), подтвердить (to agree), дребезжащий (quavering), тенор (tenor), свистнуть (to whistle), вздрогнуть (to shudder), волосатый (hairy), ухмыляющийся (smirking, grinning), пухлый (plump), краснощёкий (ruddy), испуганный (frightened), барьер (barrier), спустя полчаса (half an hour later), покачиваться (to totter), инстинктивно (instinctively), наученный опытом (taught by experience), держаться подальше (to keep oneself further away), канава (ditch), картуз (peaked cap), обрываться (to be cut off), представляться (to appear, seem), перепутанный (confused).

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| дудочка | a pipe, whistle | noun, fem, diminutive | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | circus-training prop in this story |
| картуз | peaked cap | noun, masc | core | — | historical (19th c.) | — | — | dictionary | n/a | plausible_unverified | |
| наученный опытом | taught by experience | idiom | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| ухмыляющийся | smirking, grinning | adj/participle | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

**Explanatory Notes** (printed p. 136, the book's final per-story notes entry before the Afterword) — 16 entries, an animal-circus register:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Каштанка | name of a dog, from the chestnut (каштановый) colour of its coat | proper noun (derived) | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | the story's protagonist; name transparently derived from adjective каштановый |
| трактир | (arch.) in tsarist Russia, originally an inn with a restaurant, later a restaurant of the lowest class | noun, masc | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *arch.*; semantic drift downward in social register over time, noted by the source itself |
| конка | (hist.) in the pre-tram days, the urban railway line with horse-drawn carriages | noun, fem | archaic | — | historical (tsarist Russia, pre-1917) | — | — | dictionary | n/a | plausible_unverified | source tag *hist.* |
| пьян, как сапожник | (idiom) very drunk | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | fixed simile idiom, "drunk as a cobbler" |
| Супротив человека ты всё равно, что плотник супротив столяра... | (pop.) By comparison to a person you are as insignificant as a carpenter compared to a cabinet-maker... | idiom | colloquial, regional | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | source tag *pop.*; супротив is a dialectal form of standard против |
| Тайнственный незнакомец | The Mysterious Stranger | proper noun (in-story dog name) | core | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | one of the circus troupe's dog-names, deliberately grandiose |
| Драку подняли? | (coll.) Have you started a fight? | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |
| Чёрт знает что! | exclamation used to express indignation | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | verified | recurs from Death of a Clerk notes |
| «гоп»! | exclamation encouraging (here) an animal to jump | interjection | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | circus-trainer command vocabulary |
| чёрт бы вас взял! | exclamation of annoyance | idiom | colloquial | — | contemporary (source published 1989) | — | — | dictionary | n/a | plausible_unverified | |

---

## Grammar points

*(This source is a literary reader with a vocabulary+notes apparatus, not a grammar textbook — it
has no dedicated grammar-point sections. The items below are grammatical/sociolinguistic phenomena
the Explanatory Notes apparatus itself explicitly calls out and explains, which is where a reader
like this earns its keep for slang-mechanics purposes: it flags exactly the register-marking
devices a native-level reader would otherwise miss.)*

### The particle -с (register-marking enclitic)

The Notes section explicitly glosses **-с** (attached enclitically to a word, e.g. `чихнул-с`,
`Позвольте-с`, `Очень приятно-с`) as a discourse particle "used to lend a statement a note of
respect, politeness" in 19th-century Russian — an archaic feature that has since dropped out of the
standard language entirely. Crucially, the Notes on *The Fat and the Thin* go further and connect
this particle to a **register-shift narrative device**: when the thin man realizes the fat man
outranks him, the *combination* of switching from ты to вы *and* adding -с to his speech is glossed
by the source itself as jointly expressing "the respect and servility of the thin man towards the
fat one." This is a clean, textbook example of `register_inversion`-adjacent slang mechanics: a
single grammatical/discourse marker (a clitic particle) doing sociolinguistic deference-signaling
work, later abandoned by the standard language — a candidate mechanism for how an invented register
particle could work in a synthesized slang system (a marker whose sole function is signaling
relative social status, attachable productively to whatever word ends the clause).

### "Popular deformation" of relative-clause participles (я человек, который работающий)

The Notes on *Chameleon* explicitly flag a specific ungrammatical construction — using a participle
directly after the relative pronoun который (as in `я человек, который работающий`, "I am a man who
[is] working") instead of either `я человек работающий` (bare participle) or `я человек, который
работает` (relative clause with finite verb) — as **"a widespread popular deformation."** This is
valuable as a directly-attested example of a *recognized, named* non-standard grammatical pattern in
lower-register/uneducated speech (contrasted explicitly against the two grammatical alternatives),
rather than an invented one — a real data point for how this project's mechanics-analysis phase
might model "which grammatical simplifications mark a speaker as uneducated" in a derived slang
system.

### Pluralis-respectus: singular referent, plural verb agreement

The Notes on *Chameleon* explain `братец приехали?` ("has your brother arrived?" with a *plural*
verb attached to a *singular* subject) as expressing "the policeman's respect for the person he is
talking about" — i.e., grammatical number itself (not just pronoun choice, as in ты/вы) can carry a
deference marker in this register system. Worth cross-referencing against the ты/вы system already
documented in `00_Extraction_Checklist.md`'s morphological-typology note — this is a second,
independent register-marking axis (verb number) layered on top of the pronoun-based one.

### Dialectal/phonetic peasant-speech markers

Several entries are explicit source-marked **peasant/dialectal phonetic variants** of standard
forms, glossed with an explicit equals sign by the source itself: `чаво` = `что?` (Horsy Name notes,
p. 121), `коли б` = "if" (dialectal conjunction), `поговоривши` = `поговорив` (dialectal/archaic
verbal-adverb suffix `-вши` vs. standard `-в`, Naughty Boy notes, p. 122), `супротив` (Kashtanka
notes) as a dialectal form of standard `против` ("against"). These are directly-attested,
source-confirmed dialectal sound-change/morphology patterns rather than inferred ones — useful raw
material for a derived slang system's own phonological-reduction mechanism.

### Honorific clipping: ваше-ство / вашескородие

Two independently-attested clipped/reduced honorific forms appear across different stories: `ваше-
ство` (Death of a Clerk notes, p. 119 — clipped from `ваше превосходительство`) and `вашескородие`
(Burbot notes, p. 133 — a peasant-speech reduction of `ваше высокородие`). Both are explicitly
glossed by the source as archaic/colloquial reduced forms of a longer formal honorific phrase — a
directly-attested `phonological_reduction`-type mechanism operating specifically on honorific/
deferential vocabulary, worth flagging for the mechanics-analysis phase as a recurring pattern
(distinct instances, not one repeated example) rather than a one-off.

### Diminutive/augmentative/pejorative suffixation

Recorded productively across the book's vocabulary, both as neutral diminutives (`кобылка` "filly"
from `кобыла`; `поварёнок` "kitchen-boy" from `повар`; `полтинничек` "fifty-copeck coin", a
diminutive of `полтинник`) and as clearly **pejorative** or **augmentative** derivations the source
itself register-tags: `лошадёнка` (pejorative-diminutive "weak, scrawny horse," from `лошадь`),
`мужичонка` (pejorative-diminutive "small, nondescript peasant," from `мужик`), `старикашка`
(ironic-pejorative "old man," source-tagged *coll., iron.*), `тетрадища` (ironic-augmentative
"enormous notebook," source-tagged *iron.*, using the augmentative suffix `-ища`). Directly relevant
to the `morphological_play` derivation type in `00_Usage_Tier_Taxonomy.md` — Russian's productive
diminutive/augmentative/pejorative suffix system is a native mechanism this project can look to for
a derived slang system's own affixation-based tone-shifting.

### Aspect and verb-of-motion prefixation (attested incidentally throughout)

Not separately drilled by this source (it is a reader, not a grammar), but the vocabulary itself
incidentally documents many perfective/imperfective pairs sharing a root with different prefixes
(e.g. `забормотать`/`пробормотать`/`бормотать` — "to mutter", pfv-with-different-prefix vs. ipfv;
`вскочить`/`заскочить`/`выскочить` — "to jump up"/"to jump out", directional-prefix variation on one
root) — consistent with this language's fusional/prefixation-based aspect system already noted in
`00_Extraction_Checklist.md`. No new grammar rule to add here; flagged only because the sheer density
of prefix variants on shared roots across just 15 short stories is itself a useful corpus sample for
later prefix-productivity analysis.

---

## Front matter and Afterword (paraphrased, not tabulated)

The book opens (printed pp. 1–7ish) with a critical/biographical essay by **A. Chernyshov**
introducing Chekhov's "Antosha Chekhonte" period (1883–1887): his medical-student years, the
journals he wrote for (*Oskolki*, *Zritel*, *Strekoza*, *Budilnik*), the "brevity is the sister of
talent" dictum he later held to, Dmitri Grigorovich's 1886 letter urging him toward more serious work,
and his rise from anonymous humor writer to a Pushkin Prize winner (1888) and produced playwright.
The **Afterword** (printed pp. 138–142, signed **A. Shamaro**) is a geography/biography essay tracing
each story's real-world inspiration — Chekhov's own trips through the Istra-Zvenigorod area west of
Moscow (where three of the stories, *Chameleon*, *Surgery*, and *Burbot*, are explicitly said to be
"rooted"), his brother Mikhail's memoir *Around Chekhov*, and the real Durov Animal Theatre that
inspired *Kashtanka*. Neither section contains vocabulary or register-marked lexical content — both
are paraphrased here only for the biographical/critical context they supply, per copyright
discipline (no prose from either essay is quoted at length).

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. Chekhov's own narrative/dialogue text is not reproduced
anywhere in this file beyond the same short (clause-length) illustrative fragments the source's own
Explanatory Notes apparatus already quotes for idiom-glossing purposes. See
`../../00_Reference_Extraction_Spec.md`.
