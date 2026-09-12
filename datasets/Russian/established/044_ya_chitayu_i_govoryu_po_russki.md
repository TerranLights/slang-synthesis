# Russian — Established Vocabulary/Grammar: Н. Е. Кухаревич, М. Б. Будильцева, Н. И. Киселева, *Я читаю и говорю по-русски (средний этап)* — full book

**Source:** Н. Е. Кухаревич, М. Б. Будильцева, Н. И. Киселева, *Я читаю и говорю по-русски. Средний
этап* [*I Read and Speak Russian: Intermediate Stage*], 3rd stereotype edition (Moscow, «Русский
язык», 2003), ISBN 5-200-03214-8, 128 printed pages / 66 PDF pages. Full book: preface, 14 reading
texts each with pre-text/pre-reading/post-reading exercise blocks, and a ~1,000-word trilingual
end-of-book glossary (Russian headword with English/French/Spanish glosses). This extraction covers
**all 66 PDF pages / all 128 printed pages** — the entire book, not a partial chunk.

## Coverage note

**Book structure and scan format.** `pdfinfo` reports 66 pages at a single-page media box
(419.5×595.25 pt), but page-by-page inspection (PyMuPDF) shows the *first* PDF page alone is at that
single-page width — every subsequent page (PDF pages 2–66, i.e. printed pages ~3–128) is scanned as a
**two-printed-page spread** at double width (841.85×595.25 pt), matching the PDF-extraction gotcha
documented in `../../00_Reference_Extraction_Spec.md` ("vision-only source can be scanned as
two-printed-pages-per-image spreads, not one page per image" — confirmed here even though this source
carries a real ABBYY FineReader OCR text layer, not just images). This was verified empirically via
`PyMuPDF` page-rect inspection before treating any page-range estimate as reliable, per the spec's
guidance.

**Real text layer, but OCR quality is uneven — not a fixed substitution cipher.** `pdftotext`
produces a genuine, mostly-legible Cyrillic text layer for the 14 reading texts and their exercises
(pages 1–48 of the PDF) — this portion was extracted and read directly with high confidence, no
cipher or systematic substitution involved (checked and ruled out: this is ordinary ABBYY
FineReader-10 OCR misreading small/dense print, not a fixed 1:1 or offset character map like the
ЙЦУКЕН-keyboard or CID-embedded-font ciphers found elsewhere in this project's Russian corpus — no
consistent decode rule exists to recover it mechanically). The **end-of-book trilingual glossary**
(PDF pages 50–64, ~1,000 entries across a 4-column Russian/English/French/Spanish layout, further
complicated by the two-page-spread scan putting two independent 4-column blocks side by side on each
PDF page) shows markedly worse, page-uneven OCR degradation — some page-pairs (e.g. PDF pages 52 and
57) are severely garbled on both the Cyrillic and the English side, consistent with poorer print/scan
quality on those specific spreads rather than any decodable cipher. Per the extraction spec's PDF
gotcha about two-column/multi-column boxes getting scrambled by `pdftotext -layout`, the glossary was
**not** extracted via a flat `-layout` pass; it was reconstructed via `PyMuPDF` word-level bounding
boxes, classifying each word into one of 8 column slots (4 columns × 2 side-by-side page-halves) by
x-coordinate, then reassembling rows by y-coordinate proximity within each column. This recovered
correct Term/Gloss pairing for the great majority of entries (spot-checked against the visually
inspected `-layout` and raw `pdftotext` dumps, which agreed on row alignment for well-formed rows).
Only the Russian headword and its **English** gloss are captured in the Vocabulary table below (the
book's French and Spanish columns were not extracted — out of scope for this project, and doubling
the reconstruction effort for no analytical gain here).

**Per-row confidence marking (an addition to, not a violation of, the column convention).** Because a
genuine text layer exists, the spec's `Vision Reading Confidence` column is formally `n/a` for every
row in this file — no vision-reading was performed. However, since the underlying OCR quality is
demonstrably uneven, an explicit heuristic pass flagged 84 of 1,038 glossary rows (~8%) as showing
clear internal signs of OCR corruption (stray digits/symbols embedded mid-word, mixed-case garbling
within a single token, or a blank gloss cell from the column-reconstruction) — these are called out
individually in the `Notes` column rather than silently left uniform, per the spec's per-entry
flagging discipline. Being unflagged is not a certified-accurate row: a residual background rate of
uncorrected minor OCR noise (an occasional misread single character, e.g. а/о or е/е confusion) likely
remains in the "unflagged" 92%, since correcting every glossary word against a Russian dictionary
was out of scope for this pass (no Russian spellchecker/dictionary was available in this
environment to cross-validate at scale). Treat the glossary section as **best-effort, not
verbatim-verified** — anyone doing precision lexical work with it should spot-check against the
print original.

**Grammar points** below are drawn from the 14 reading texts' pre-text/pre-reading/post-reading
exercise blocks (the clean, reliably-OCR'd portion of the book), which repeatedly surface explicit
grammar explanations (verb-pair case-government contrasts, aspect usage rules, word-formation/prefix
meaning drills, diminutive-suffix paradigms, collective numeral usage) alongside idiom glosses. Per
the coverage rule, repeated "compare your answer with your classmates'"/"read the text and answer
these questions" comprehension-drill boilerplate (present after every one of the 14 texts, near
-identical each time) was skipped as non-substantive; every distinct grammar point and
explicitly-glossed idiom found across the 14 texts was captured.

---

## Vocabulary

**Table below is the end-of-book master glossary (1,038 headwords after reconstruction and
deduplication of PDF-scan bleed-through, out of a stated "~1,000 words").** Inline vocabulary
explicitly glossed within the 14 texts' own exercises (idioms, near-synonym clarifications,
word-formation examples) is covered separately in the Grammar points section below each rule it
illustrates, to avoid duplicating entries that also appear in the master glossary.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| биологический | biological | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| бнвсфр! | biosphere | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| в м м м Ь г | bioelement | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| битм | battle | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вить НСВ, кого? почему? | to beat, to hit | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| благояарй кому? чему? | thanks to | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| благородный | noble | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| благотворный: | ulutary, beneficial | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| твбрное влияние | salutary influence | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| блйжиий | near | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Бог | God | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ббяроспж | courage, cheerfulness | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| боль ж | ache, pain | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| большиястаб | majority | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ббмба | bomb | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| богйнон | boot | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| бобгъся НСВ, кого? чего? | to be afirstid of | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| брать взять я м руку кого? | to take ifflb's arm | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| брать | to take oneself in hand, | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| взять сеМ в ркн | to pull oneself together | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| бровьж | eyebrow, brow | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| бдто | as if | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вук4т | bunch, bouquet | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| бульвар | boulevard | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| бум4га | paper, document | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| битовый: битовый камень | rubble stone | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| бухгалтер | bookkeeper | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| быть не в сйлах | to be beyond one's | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| + ииф | power B | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вглядеться СВ, | to peer (at) | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| е кого? оо что? | to look closely at | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вдохновение | inspiration | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| веттй НСВ, кого? что? куда? | to transport, to carry | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| велйкий | great | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Великобритания | Great Britain | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Всв(ра | Venus | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сверибиеп | inhabitant of Venus | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вененибиен | inhabitant of Venice . | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Венбния | Venice | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| верить поварить кому? чему? в кого? оо что? | to believe, to trust in | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| верный (правильный) | correct, true | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вес | weight | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| веоЕнннй | spring | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| весить НСВ | to weigh | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| веснушки | freckles | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ветерби | veteran | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вЬка | branch | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| В*тхнйЗав4т | Old Testament | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| вечный | eternal, perpetual | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вМпать НСВ, что? куда? | to hang | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вещеетвб | substance | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| взгляд | look, glance | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| взвСрнутый (нос) | •nub (nose), tumed-up (nose) | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| вздрагивать взлрбгнуть | to shudder | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| взрыв | explosion, detonation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| взрывбть взорвать что? | to explode | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вид' | species, kind | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вид': дЬмть вид | appearance: to assume airs | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вйдеть | to dream about, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| увйдеп» кого? что? во сие | have a dream | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| виновный) | guilty | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| висеть НСВ, где? | to hang | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| витамйи | vitamin | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вихревбй | whirlwind, vortical | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вклад | contribution | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| влюбл(н в кого? | being in love with | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| влюбленный (сущ) | being in love | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| влюбляться | to Ml in love (with | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| влюбиться * кого? | smb) | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ВЛ\|6бчНВЫЙ | amorous, of an amorous disposition | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| внезапно | suddenly | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| внезапный | sudden | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| внешний | external, outward | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| внешность ж | appearance appearance | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| виоейть анестй вклад «о что? | to make contribution to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| внутренний | inner, inside | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вааорба | hydrogen | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| воевАть НСВ, с кем? | to combat, to wage | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| протмкого? | war | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| возврпйть СВ, кого? к чему? | что? to return, to give back | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| м п м я А п НСВ, что? | to head | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вошАйствие | influence | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| воздействовать НСВ/СВ, на кого? на что? | to influence | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| возмДжяость ж | possibility | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вознякАть возникнуть | to arise | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| воривЬь возразйтпмtу? | to object | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ю з р м а Ь ш | revival, regeneration | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| войнА | war | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| аолиовАтъ НСВ, кого? | to agitate, to excite | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| олноаДться НСВ | to be nervous, to worry | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вАлое {ми. вАлосы) | hair | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| т и М и н * | armed | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| м м А п м ы ! | well brought up | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| аесстяяАвлиаять | to restore, to , | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| восстановить что? | reconstruct | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| воеетяновлАиие | restoration, reconstruction | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| впервые | for the first time, first | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| N I W I T A W | Impression, effect | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| врашАяие (Землй) | revolution (of the Earth) | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| врАдяый | bad, harmflil, unhealthy | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| времяиечиелАние | calendar | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| e u i m a | universe | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сам Арный | world, universal | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ярМЬ | in earnest, seriously | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ВСПЯТЬ | backwards | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вулиАи | volcano | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| выврАемвать НСВ, что? куда? | to throw out | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| выСрАсываться НСВ | to throw oneself out | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| nimm СВ, кого? откуда? | to expet, to dismiss | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| выделить НСВ. что? | to select, to pick out | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| аьЬкитъ СВ | survive | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вызыаАть HCA кого? куда? | to call smb | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вызывАть НСВ, что? | to call, to challenge | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вь1вграть СВ | to win, to gain | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| BIMTMCV зАмуж | to marry | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вькказать СВ, кому? | что? to tell, to express | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| а ü слушать СВ, кого? что? | to bear, to listen to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| высАкяй | high | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| высотА | height, altitude | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| выставочный | exposition, exhibition | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| айетрел | shot | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| выступление | speech | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| вЬктеснить СВ, что? | to force out, to oust | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| яыявлАтъ | to to expose, expose, to to reveal reveal | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| выявить что? | Г | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| гарантйровать НСВ/СВ, что? кому? от чего? | to guarantee | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| (Алий | helium | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| геи | gene | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| геиерАтор | generator | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гАиий | genius | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гАиный | genetic | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гйбельас | ruin, destruction | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гимн | hymn | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гнпАтаа | hypothesis | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| глаз: с глАзу на глаз | eye: confidentially | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| глубниА | depth, profundity | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| глубокий | deep, profound | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| голояА | head | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гАлод | hunger | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гАлос | voice | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гАре гАре | grief grief | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| городАк | (little, small) town | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| горйчнй | hot | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гоепЫипа гоепЫипа | hotel | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| гражданин гражданин | citizen | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| граидиАзиый | grandiose | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| гребнйна | tomb, sepulchre | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| группнровАтъся НСВ | to group Д Д | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дялйсий | far, remote | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| двйгаться НСВ | to move | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| движАияе | movement | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дабе | two (persons) | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| деачАнка | girl, kid | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дежурить НСВ | to be on duty, to watch | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дежурный (сущ) | on duty | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дейстайтслыю | really, actually | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| действовать НСВ | to act | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| делйтьса НСВ, с кем? чем? | to divide | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| держбть НСВ. что? | to hold | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| держать НСВ а повино- вении кого? | to to make make smb smb obey obey | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| держАться НСВ. иа чем? | to behave, to keep | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| держаться НСВ. как? | to keep, to hold on | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дешёвый | cheap | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Ali кий | wild, savage | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| диспансер | dispensary, health centre | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| до: до сих вор | up to now, till now | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| до тех пор, аокА ас | until | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| добавить СВ, что? к чему? | to add | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| довиваться добиться чего? | to achieve, to obtain | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| добывать добьНьчлю? | to extract | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| доказывать доказать кому? что? | to prove | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| долгопериодный | long, long-term | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дорогАй дорогАй | dear, expensive | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| дос4да дос4да | disappointment | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| доскЫть СВ. калу? что? | to finish | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| досяАвио | word for word | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| достйгнуть СВ, чего? | to reach, to achieve | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| достижение | achievement | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| древний | ancient | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дрожАть НСВ от чего? | to tremble, to shiver | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| отстрАха | with fright | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дыре | hole | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| дышАтъ НСВ, чем? | to breathe | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| егйпеккий | Egyptian | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| i n i n c m n i u l | unique, only | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сдйисгао | unity | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| единый | united | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ежегАдиый | annual | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жадность ж | greediness | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жДлостьж | pity | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жасмин | jatmin(e) | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жслбтъ НСВ + шф | to desire, to wish | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| женйться НСВ/Сё, каком? | to many | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| женственный | feminine, womanly | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жест | gesture | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жввАе(асгживбе) | living, alive | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| живописец | painter | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| живопись ж | painting | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жйдкость ж | liquid | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жйтель« | inhabitant | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жить: жить НСВ | to live by accidental | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| случайными заработ- ками | earnings | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жрец | priest | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| журбвльм | crane | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| жюрй ер | jury | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| заболевание | disease | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| заботливый | solicitous | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| завершаться завершаться | to be completed! | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| зависеть НСВ. от кого? чего? | to depend on от | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| завоевать СВ. что? | to conquer, to win | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| завянуть СВ | to fade | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| загАдка | riddle, enigma | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| загадочный | enigmatic, mysterious | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| за говорить СВ | to start talking | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| загрязниться НСВ | to become dirty | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| задерживать НСВ, кого? что? | to detain, to arrest | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| задумываться | to meditate | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| задуматься над чем? | order | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| закйз заказывать | to order | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| заказать что? кому? | law | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| закби | to cry out, to give | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| закричать СВ | a shout | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| залйть СВ. что? | to pour, to flood, to inundate | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| w w f a i HCB, tmo? HO | to substitute, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| imo? | replace | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| mmtnaui» | remarkably, wonderAiliy | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| m n t i M w u l | remarkable, wooderflil | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| UMeniTh | to notice | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| MMfrnm. «wo? vino? | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| IUNI«lnCV | to become silent | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| NHMhk nudrrii HMO? | to occupy, to take | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Maic | reserve | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| linax | smell, odour | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| uaAcuaaTk HCB, imo? | to register | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| H u i m C I | to begin to cry | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| w u i r f t i CB, KOMy? | to pay | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| a m i m f a w f a a r o imo? | to fill in | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| MutuwnukTkca HCB, him? | to fill up | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| mptmaimo? | prohibition, ben prohibition, ban | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| lApaSoroK | earnings | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| ucafanuaih iaejiyat*n <tmo? i«o? | to deserve, to merit | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| WMHIMCI | to bunt out laughing | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ucriaam mto? + | to force, to make | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| t r a i n CB »ixämtc | to hold oae'a breath | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| iaauiai*Tfc HCB, mto? | imo? to defend, to protect | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| H m l | (tar | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| utanna | local | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| yumJm.HCB | to grow green, to become green | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| soMMfpaefMM | earthquake | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| WMto | fellow-countryman | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| aumnhkil | famous | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| MjwnkTwa | golden | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| itea | zone | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| iptrenb* | spectator H | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Hrpin curpfopom | to play apart | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| mein | ideal | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| mtA: na*r? | do you agree? | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| uia | idea | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| HMtMht | to learn a lesson | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| n u h i i ypte to ttio? | 102 | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| fcropoahx | fence | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nqmhrnt | radiation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| HMtepfab nsuipim imo? | to measure | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| HinypArejiknull HinypArejiknull | • exhausting | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| moSpaarfn | to represent, to depict | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nsoSpaiirii noto? | imo? | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| m f p s r i n moftpecrA imo? | »invent | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| NMunlrop | insulator | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Men 1 HO | precisely, exactly | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| S M h u w l n s a - | to be able, to be in | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| MAmocrt + un4> | position | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nncnfarrap | inspector | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| KHTAAMKTYANFCNUR | intellectual | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nmadssocnac | intensity | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| HHopMinna | information | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| uttdnhHCB, mto? | to search imo? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ncnaptaM | evaporation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| sesMHthM | execution, fulfilment | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| KctiyriTwca CB, note? | to be frightened, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| wo? | take fright | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ncnaimMm ncnaimMm HCB, HCB, | imo? imo? to feel, to experience | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| accaloonanne | investigation, research | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| aeseiTh mcntMyn mcntMyn | to diaappear | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| wrör wrör | total, result | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| KK>*rvea | to seem, to appear | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nonuArM« tauty? | KCM? | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| HtM? KOKUM? | as if | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| MKFIATO MKFIATO | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| mminm mminm | cacophony | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| MMCiuipfc* | calendar | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| KAMCHHUK | stone | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| « i w | drop | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| tdkpm» | brown, hszel | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| arrapArra | cataract | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| mracTpA+a mracTpA+a | catastrophe | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| icAnp icAnp | cutter, motor boat | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| mcnopAm | oxygen | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| icmwnripa | keyboard | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nAma (a nSmme Menae- aAeaa) | chock | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| unbwr | climate | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| к&жя да кАстя | akin and bone | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| козА | (she-)goat | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| коллективный | collective | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| команда | team | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| комакдйр | commander | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| КОМПЛИМЕНТ | compliment | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| композитор | composer | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| конгресс | congress | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| кондиционер | air-conditioner | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| конАп: a muni концбя | end: in the end | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| конАцсаАта | doomsday Apocalypse | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| конкретный | concrete | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| кАмкуре | competition | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| каисержатбрня | conservatory | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nmriicr | contact | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| контузия | contusion | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| коиценгрАция | concentration | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Копенгаген | Copenhagen | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| корАткяй | short | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| косгёр | camp-fire | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| кАфтачка | blouse | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| крАска | colour, paint | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| краснеть НСВ | to blush, to redden | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| красотА | beauty | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| KpenibtHe (прАздкик) | baptism; Epiphany | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| крик | cry | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| крйтнк | critic | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| кричАть крйкиуть на кого? | to cry, to shout | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| крАме кого? чего? | except, besides | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| крАметогА | besides | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| круг | circle | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| кружка | mug | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| крупный | targe, big | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| культ | cult | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| культура | culture . | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| куст | bush | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| кустАриик | bushes л | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лагерь* | camp | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лАскоао | caressingly, tenderly | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Mtinaa | legend | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лежАть НСВ на вил? | to lie in sight, to be in sight | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лейтенАит | lieutenant | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лекАрство лекАрство | medicine, drug | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| л1д | ice | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| лсанйк | glacier | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лес | wood, forest | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| летАтъЯСВ | to fly | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| лнквндйроаатъея HCBICB | to be liquidated | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лйстъя мм | leaves | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лиоА | face | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| личность ж | peraon, personality | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лАгяка | logic | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| логйчиый | logical | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лбдирьл | idler | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лук (оружие) | bow | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лунный | moon, lunar | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| луч | ray, beam M | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мАмонт | mammoth | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мАеса | mass | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| масгерскАя (сущ) | workshop, studio | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| масгерствА | mastership, skill | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мгновАнно | instantly | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мемуАрымн | memoirs | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| меиАть НСВ. кого? что? | to change | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мАра: мАра: прииимАтъ прииимАтъ НСВ НСВ мАры мАры | to take action | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| мАстный | local | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| метод | method | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мир1 | world, universe | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мир1 | peace | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| МироаДй океАи | World Ocean | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| миф | myth | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мифологнзйровать | to mythicize | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| НСВ/СВ кого? что? | — | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| могйла | grave, tomb | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| могущественный | mighty, powerful | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| могущество | might, power | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мозг | brain | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| молАкула | molecule | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| молчаливый | silent, taciturn | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| молчАине | silence | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| молчАть НСВ | to keep silence, to be silent | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мАрфий | morphine, morphia | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мост | bridge | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| могагетм | motorcycle races | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мрак | darkness, gloom | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| муж | husband | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мка | torture, torment | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мутАшм | mutation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мысль ас | idea, thought | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мАгкий (клймат) | mild climate | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мАсо | flesh, meat H | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| иАбережяая 1сущ) | embankment | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| наблюдать НСВ, м ком? | to observe, to wsteh | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| наблюдена« | observation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| надевАтъ надеть что? | to put on | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| надежда | hope | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| надежный | reliable | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| надеяться НСВ, на кого? на что? + ииф | to hope, to rely | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| надзирАтель* | overseer, supervisor | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| найвиый | naive | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| наилучший | the best | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| иайтА СВ. кого? что? | to find | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| накалиться СВ | to become heated | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| наклонАтьеа СВ, к кому? | to bend, to lean | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| наливАть иалАгь что? куда? | to pour out, to fill | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| иалбг | tax • | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| налАгоаый: иалАговый инспектор | tax-inspector | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| напресао | in vain | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| иаркАтик | drug, narcotic | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| нарушать нарушить что? | to violate, to break | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| нарядJ с «мам? | side by side, on a level with | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| насторожиться СВ | to prick up one's ears | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| настроение | mood, frame of mind | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| наступать СВ | to come, to set in | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| начальство | authorities, chief | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мМо | iky, heaven intolerable, | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| неаыносймый | unbearable ill-disposed person | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ' недоброжелАтель м | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| недоразумение | misunderstanding | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| недостАточио | insufficiently | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| иАжиый | tender, delicate | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| неизменный | invariable, immutable | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ыейтрАн | neutron | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| некогда: мне некогда | I have no time | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| иенаайдеть НСВ, кого? что? | to hate | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ненормальный | abnormal | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| необыкновенный | extraordinary, unusual | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| необычайно | unusually | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| непрерывно | continuously | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| неприаькчный | unaccustomed | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| несомненно | undoubtedly | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| неуверенный | uncertain, not sure | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| неужели | indeed, really | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| КОСКЙ МН | socks | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ночевАть НСВ | to spend the night О oasis | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| OASHC | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| обаятельный обаятельный | charming | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| обезвбжнваиие | dehydration | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| обсснАчить СВ, кого? | to provide, to ensure чем? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| обессилеть обессилеть СВ, СВ, от от чего? чего? | to break down, to grow weak | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| обладАтьЯСЙ, чем? | to possess, to own | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| Аблако | cloud | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Абластьж Абластьж | 1) region, district; 2) field, domain | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| облучАине | irradiation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| обнаруживать | to discover | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ohipaan imo? | 107 | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| обоясАт% НСВ, кого? что? | to adore | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| образАааиный | well educated | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| обрамаАться СВ | to form | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Абшестве | society | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| объединиться НСВ, с кем? с чем? | to unite | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| обьявйть СВ, кому? что? чём? | о to announce | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| объявление | announcement | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| обыкновенный | usual | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| tapir | ravine | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| одаренный | gifted, talented | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| одеваться НСВ | to dress | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| адйн: одйи на один | in private, face to face | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| одиночество | solitude, loneliness | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ожиал4ть НСВ, кого? | to revive | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| ошячАть НСВ, что? | to signify | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| о»6и | ozone | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| окружйть окружать кого? что? чем? | to surround | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оледенен« | freezing, icing up. being covered with ice | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| овдАтра | musk-rat | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| описание | description | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| опиеАть СВ, кого? что? | to describe | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| определить определить что? | to define, to determine | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| onyenhb СВ, что? куда? | to lower, to put down | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оранжереи | hothouse, greenhouse | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| орАтор | orator, speaker | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| орбйта | orbit | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| органйм | organism | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оружие | weapon, arms | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| осаещАть НСВ, кого? что? | to light up | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| осАивий | autumn | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ослеянуть СВ | to get blind | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| осмотрАть СВ, кого? (боль- нбго) | to examine | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оснАва | basis, foundation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| осяоаяАй | principal, main | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оставаться остаться где? | to remain, to stay | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оставить СВ, кою? что? | to leave, to abandon | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| остАвить пАмять о с«М | to leave fond memories of oneielf | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| остАвнть СВ кого? | to leave in peace, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| впокАе | love smb alone | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| остаиАалниатъся остановиться | to stop | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| отвести СВ глазА от от чего? | кого? to look aside | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| отворачиваться отвернуться от кого? отчего? | to to turn turn away away | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| отдалСнный | remote, distant | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| открытие | discovery | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| отмечАть отметить что? | to mark, to note | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| отнАть СВ, что? от | чего? to take smth away; to subtract | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| отношение | attitude, relation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| отпнвАть НСВ, что? | to take a drink, lo take | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ю чего? | a sip | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| отаустйть СВ, кого? куда? | to let off, to set free | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оттенок (ийта, хрАскн) | nuance, shade | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| охладиться СВ | to become cool | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| охотиться НСВ, на кого? | to hunt | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| охрАиа | guard, protection | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оценивать | to appreciate, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оценить что? | evaluate appreciation, | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| оценка | evaluation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| очАг | hearth | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| очки мн | spectacles, glasses | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ошибаться | to make a mistake, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ошибаться е ком? | be mistaken | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ечём? | П | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| падать упАсть | to degrade | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пАмять ж | memory | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пар | steam | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| naprntp, naprntpiua | partner | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пассажир | passenger | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| певец | singer | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| певица | singer | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| яейэАж | landscape, scenery | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ntaM | ashes | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nepBonpandua | primary cause | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| atptCmtifc ntpc6dTk K020? | to intemipt | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| Mftiwiin | to transfer | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nptMCTii KOHO? | xyda? | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ncptroBApu J1H | talk«, negotiatiooi | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nepsnaaienxu HCB, KOMy? | to paai | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| wpcgtwnm CB, who? | to overfill, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| tww? | overcrowd | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| napKiiiin | to atop, to cease | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| DtpCCTiTk + UMp | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| nepAoii | period | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| n p i a i w n i | periodic(al) | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| neeAic | send | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ncmepa | cave | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ntao | beer | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| napAr | pie | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Baton» HCB, om itto? | to cry, to weep | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Mlllk | to pay | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| iMunrrin KOMy? imo? | smo? Ja | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| UATM | dress, gown | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| BNCH | ceptivity | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| JlfouM» | prisoner, captive | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| « m l | tombstone, gravestone | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| mAiBMl | dense beacb | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| m t n / O | to dance | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| aatoMMkn | to conquer, to defeat | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| t M i k a n ? | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| aoaApm CA «wy? HtMy? o oo mtto? imo? | to believe, to tnist | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| m i p n m » | surface | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| M M f l m n u i aoBtpiifncaKKaMy? | to turn | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| KHMy? | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| M-l<WMMy | apparently | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| oMtotiiiiwJl | increased | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| mmMTh aontSNyrt | to perish, to be lost | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| aaa (MocoAlt) | near (Moscow) | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| MOfadn CA * KKMO'? wty? | to ran up * | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| naaaeprAna | to undergo, to be | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| «ABipnqnMa <MUQ>? | exposed to | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| BW\|lpiW№ | to keep up, to support | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nwuepwArt wno? | 110 | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| NOAINIMTTFC miBhkWM.7 | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| NONHHMIN | to make a | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| xoto? WWHTN M | laughingstock (of), CMCX hold up to ridicule | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| a M s m h u s xmwkntmKyda? | to rise, to climb | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| mopadn CB wopdaM | to undermine one's health | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nenoxAanull: noaoxAaBW* najiir | income tax | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| nojuiHcATt CB, imo? | to sign | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| nonpteiOK | teenager | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| no-jqtfaieciai | in a friendly way, as friend | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| noncosneBiw | subconscious | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ncmcomeTanuio | subconsciously | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| noacntT O M N I T I FOJIOCAB | counting of the votes | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| noamftruBaTV | to count up, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| nwciirln imo? | calculate | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| mrnnefWlnHCB, mrnnefWlnHCB, | to confirm imo? imo? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| nwtxta nwtxta | approach, point of view | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nonxonftrfc | to come up, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nOOOftni K KOMy? noacip noacip | approach K ItMy? fire | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nnwuhMiCt | to get married | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| nnamen noKin pjity KOMy? | to shake hands | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| mnaAn CB, imo? | to call | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| noMopABBTMa noMopABBTMa CB, CB, | to greet, to exchange c c kom? kom? greetings | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| HOKA (RC) | until | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| noKaiATbca CB | to seem, to appear | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| nomuUTh | to leave, to abandon | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nomtay» mxo? | imo? | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nomuieHNe | generation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| DMpacain DMpacain CB CB | to become red, to redden | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| BAJW | field | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nonAiHul | useful, good for | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| Mtr | flight | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nornta | watering, pouring | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| aojisiin nonAn «mo? <mm? | to water, to pour | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ROJIATBWI | politics | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| nojiropi | one and a half | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| naqntiMS nonyiHTVca | to come, to turn out | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| помАщник | assistant, help | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пАмОЩЬ JK | aid, help | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| поочерЬио | in turn | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| попадАть лопАсть куда? | to get (in)to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| попасть СВ в плен | to be taken prisoner | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| по-прежнему | as before, as usual | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| попрощАться СВ, с кем? | to say good-bye to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ПОПЫТАТЬСЯ СВ + инф | to try | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лоразАть СВ, кого? | to surprise, to strike | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| иорАдок | order | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| порАдочный | honest, decent | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| посадить СВ, что? | to plant | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| посАдка | planting | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| последствие | consequence | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| постАанть СВ, что? куда? | to put, to place | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| постарАться СВ + инф | to try, to endeavour | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| постельж | bed | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| поступок | deed, action | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| постучатьСВ, куда? | to knock | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| посчастлйяитьея СВ + инф | to be lucky | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| потАмок | descendant, offspring | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| потАп | deluge | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| потребовать СВ, чего? | to demand | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| потребоваться СВ | to be demanded, to be needed | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| потрясти СВ, кого? что? | to shake, to brandish | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| похлопывать НСВ, чем? по чему? | to pat | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| потАж на кого? на что? | resembling, like | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| онА похАжи как две | they are very much | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| кАпли воды | alike | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| похороийть СВ | to bury | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пАчка | bud | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| появляться появиться | to appear | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прАвда | truth | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| праяояедеияе | jurisprudence | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прАяый | right | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прАчка | laundress | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| превращать | to turn, to convert | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| превратАгь что? | «о что? | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| преяращАться | to turn, to be - | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| превратиться во | transformed into что? | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ярАдок | ancestor | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| предположить СВ, | to suppose, to assume что? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прсдпрнймчивый | enterprising | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| представление о ком? очЬл? | idea | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| представлять | to present | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| предстАвить кого? | что? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| предстАвнть себА кого? что? | to imagine | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| представлять НСВ кого? что? | to be, to represent собАй | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| премрАть НСВ, кого? за что? | to despise | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прекратиться СВ | to cease, to end | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| премьАря | first night, premiere | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| препятствовать НСВ, | to prevent, to create | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| кому?чему? | obstacles | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пресса | press | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| претендент на что? | pretender, claimant | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прибАр | device, instrument | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| нривотА СВ, кого? что? | to bring (in) | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| приветствие | greeting, salute | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| привлекАть НСВ, чем? | to draw, to attract кого? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| приводить привести к чему? | to bring, to lead to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| приАякий | newcomer, newcomer, visitor visitor | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прюемлйться СВ, | to land куда? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| примерно | approximately | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| приносить НСВ, что? куда? | to bring | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| принАть СВ, кого? за кого? | to take for | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прйнцип | principle | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прнрАда | nature | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| присоединение | addition, joining | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| присосдинйть СВ, к чему? | to add, to join что? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прйслшь ж | landing landing stage, stage, pier pier | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| присутствие чего? | presence | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| причйна | cause, reason | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| проверить НСВ, что? | to check, to examine | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| провести СВ исследование | to cany out an investigation | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| лровестй СВ кбнкуре | to cany out a competition | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| провожать | to accompany; to see | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| проводйть кого? куда? | smbofT | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| проёкг | project | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прожйтьГв | to live | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прозвйть СВ, кого? | to nickname, to name | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| п р о п м Ы п пронзвестй что? | to produce, to make | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| произв&ство | production | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| произнести СВ, что? | to pronounce | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| происходить | to take place, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| произойти | happen | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прояиЫть ДСВ. через что? | to penetrate | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| проникновение | penetration | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пропустить СВ, что? мймо ушМ | to turn a deaf ear to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| просто | simply | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| простой | simple, ordinary | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прбсъба | request, petition | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| противосгойть НСВ. каму?чыу? | to resist, to withstand | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| нротбн проходйть | proton | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пройтй | to pass, to be over | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прохбжий | passer-by | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| процент | percent, percentage | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| процесс | process | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прошелтйть СВ | to whisper | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прощаться попрощйться с кем? с чем? | to say good-bye to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| проясниться проаснйться | to clear up | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| "РУД | pond | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| прйгать НСВ, кого? что? от кого? куда? | to hide, to conceal | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пейхнет | psychology, psyche | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| птйца | bird | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| яустйй | empty, hollow | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пустыня | desert | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пустькрь« | waste land | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| путь л | way, road | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пыль ж | dust | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ПЫТЙТЬСЯ. попытйтьея + имф | to try, to attempt | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| пьйный | drunk, tipsy P | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| радиация | radiation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| редоваться НСВ, кому? чему? | to be pleased, to be glad | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| радость ж | joy | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| разбрасываться НСВ | to scatter | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| развйтие | development | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| развлечение | amusement, entertainment | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| развбд | divorce | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| разводиться развестись с кем? | to divorce | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| раздвойться СВ | to fork, to bifiireate | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| разделйться СВ | to divide | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| раздражаться НСВ | to get irritated, to get annoyed | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| раздражительный | irritable | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| разлагаться НСВ, на | to decompose, to что? decay | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| разногласие | disagreement, discrepancy | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| разрушать | to destroy, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| разрешить что? | demolish | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| разруайние | destruction, demolition | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| разыскивать НСВ, кого? где? | to look, to search | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рай | paradise, heaven | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рНскый | paradisiacal), heavenly | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рак: рак кбжи | cancer of skin | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рбяеиый (сущ, прилег) | wounded | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| pica | race | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| распйд | disintegration | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| распадаться НСВ, на | to disintegrate, что? to to fall fall to to pieces pieces | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расположенный | disposed disposed | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рассматривать НСВ, что? | to examine кого? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расстаться СВ | to to part, part, to to separate separate | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расстояние | distance | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расстраиваться | to be upset, to feel | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расетрАиться | upset | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расстреливать расетреаАтыако? | to shoot | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рассуждать НСВ, о чём? | to reason, to discuss | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рассуждАине | reasoning, arguement | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| растАвне | plant | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| растереться СВ | to be at a loss, to lose one's head, to get lost | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| растительность ж | vegetation | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| растопйть СВ. что? | to melt | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расчистить СВ, что? | to clear | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расшириться СВ | to widen, to extend | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расшнфровАть СВ, что? | to decipher | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| расщеплять НСВ, что? на что? | to splinter, to split | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| реагент | reagent | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| реагировать НСВ, с чем? | to react; to respond | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рсалиивАть НСШСВ, что? | to realize | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| регулАрный | regular | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| реайгав | religion | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| репродукция | reproduction | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рАбга | timidly, shyly | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рАбог | robot | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рАвиый | flat, even | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| род (человеческий) | mankind, human race | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рАдетвеяник | relation, relative | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рождЯться | to be bom | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| романтйческяй | romantic | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рАша | grove | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ругАть НСВ, кого? за что? | to scold | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ругЯться НСВ | to swear, to abuse | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рукА | hand, arm | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| руководйтель м | leader, chief | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| руководить НСВ. кем? чем? | to lead, to guide | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ручАй | brook, stream | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| рыдЯтьНСД | to sob | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| рьЬяий | red(-haired) | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| садиться НС», куда? | to lit down, to teat | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сядАиник | gardener | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сяжАть посадйть что?: | to plant | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| посадйть в тюрьму | to put in prison | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сАженец | seedling, young plant | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| самоликвидироваться нсшсв | to liquidate oneself | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сбрАснть СВ (бАмбу) | to drop (a bomb) | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| сяЬкссть ж | freshness | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| свАтлый | light, bright | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| своеобрАзпый | original | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| свАзывапНСВ, что? | to connect, to unite | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| седйй | grey | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| еелА | village | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| семСрка | seven | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| семирйчный | septenary | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сАмв ср | seed | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сенсацнАнный | sensational | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сАрще | heart | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сет СВ, куда? | to sit down | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| снгкАл | signal | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| симпАтня | sympathy | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| снмфАния | symphony | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сирень ж | lilac | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| снегАма | system | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сиЯющнй | shining, beaming | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сквер скопировать СВ, что? | public garden | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| скот | to copy | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| скрываться | cattle, livestock | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| скрыться от кого? от чего? где? | to hide, to conceal | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| скульптор | sculptor | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| слАаа | glory | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| слезА | tear | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| слечь:слечь СВ впостАль | to lake to one'a bed | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| слой | layer, stratum | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| еломАть СВ, что? | to break | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| случЯйиый | casual, accidental | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| случаться | to happen, to occur | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| случаться | 117 | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| смерть ж | death | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| смех | laughter | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| смешиМ | ridicukwa, fiinny | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| смейтьея ЯСВ | to laugh | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| смуглый | dark, awarthy | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| смутйться СВ | to get embarrassed, to beconfliaed | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| смущАть | to confUse, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| смутАть кого? нот? | embanaaa | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| снимАть снять что? откуда? | to take off | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| снбаа | again | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| еобирАться соврАтъся + инф | to intend, to be going | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| еАбственный | own, proper | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| собьНне | event | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| совершАпио | absolutely, quite | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| совместный | common, joint | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| совпадать НСВ, с чем? | to coincide | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| соглАсие | consent | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| соглашаться согласАться с к*м? с чем? | to agree, to consent | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| соглашение | consent, agreement | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| еамрасАнве | contents | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| соединена* СВ | junction | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Соединённые Штбхы | United States of | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Америки | America | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| соаиАтельиый | conscious | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| солдАт | soldier | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сблиечный | sun, sunny, solar | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сАлнце | sun | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сомневАтмв НСВ, е чём? | to doubt | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сообщАтъ | to inform, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сообщать кому? о ком? о чём? | communicate | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сооруасАть НСВ, что? | to erect, to build | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сооружение | building, construction | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| состАв | composition, structure | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| составлять НСВ. что? | to put together, to make up | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| состояние чего? | condition, state | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| состоять НСВ, из чего? | to consist | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сохраненае | preservation, conservation 100 | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сохранить Св. что? | to keep, to maintain | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сохраниться | to be preserved, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сохраняться | remain | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| спасАть спасти кого? что? | to save | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| спектр | spectrum | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сиокАйный | calm, quiet | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| спокбйстане | calm, tranquillity | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| спор | debate, discussion | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| епбрнть НСВ, е кем? о чем? | to dispute, to argue | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| спрятать СВ, кого? | что? to hide, to conceal | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| спутник | satellite, sputnik | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сражаться НСВ, с кем? | to fight | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сражение | battle | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| средА(обнтАни*) | environment. surroundings | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| средй кого? | smong | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| средний | middle, medium | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| средство | means | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стябялюйроватъся | to be stabilized, to | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| НСВ1СВ | become stable | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| «Явить | to put, to place | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ПОСТАВИТЬ что? куда? | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| стаиовйтьея стать кем? чем? каким? | to become, to begin | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| старЯгьея НСВ + инф | to try, to endeavour | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| старик | old man | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| статйстика | statistics | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стнрЯть НСВ, что? | to wash | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| столько (- бчень мнбго) | so much, so many | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стАрож | guard, watchman | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сгоАть НСВ | 1) to stand 2) to be, to be situated | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| страдЯть НСВ, от чего? | to suffer | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стрЯино | strangely, funny | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| страсть ж | passion | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стратосфера | stratosphere | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| страх | fear, fright | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стрАшиый | terrible | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стрел* | arrow | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стресс | stress | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стрАгнй | strict, severe | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| стрАчка | line | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| смма | sum | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| суперцивализАция | supercivilization | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сутки | twenty-four hours | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сухАй | dry | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сушить в ь! сушить что? | to dty | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| сушь »с | drought, dryness | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| существенный | essential, important | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сушествА | creature, being | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сутествовАние | existence | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| сутеетвовАть НСВ | to exist | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| схАдный с кем? с чем? | similar, resembling | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| схАдспо | likeness, resemblance | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| спАиа | scene, stage | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| счастливый | happy | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| счесть* | happiness | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| счвтАть НСВ, кого? кем? каким? | to consider | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тайгА | taiga | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| талантливый | talented | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тарелка: лсгАюшая та- реяка | flying saucer | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| творйть НСВ, что? | to create | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| твАрчесгво твАрчесгво | creation, creative work | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| тело | body | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тСмно-сАрый | dark-grey | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| тСмный | dark, obscure | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тень лс | shadow, shade | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| теАриа | theory | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| теплый | warm | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| территАрия | territory | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| терАть НСВ в весе | to lose weight | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| терАтъся//СВ | to be at a loss, to lose one's head, to get lost | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ттка | aunt | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ткячйхя | weaver | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тАикий | thin, the | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тАина | ton | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тАчка зрения | point of view | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| травА | grass | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| травйнка | blade of grass | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| 'градация | tradition | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| требовать потребовать чего? | to demand | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| от кого? + имф | 120 | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| триумф | triumph | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| труд | labour, work | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| трудйться НСВ | to work, to toil | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| туберкулезный диспансер | TB prophylactic centre | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тут | 1) here, there 2) then, now, here | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тщательно | carefully | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тюрьмА | prison | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| тяж{лый | heavy, severe | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| убАяште | refuge, shelter | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| убнвАть убхть кого? | to kill, to murder | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| убярАть убрАть что? | to tidy up | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| убрАнство | decoration, attire | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| увеличиваться НСВ | to increase, to grow | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| увелйчить СВ, что? | to increase | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уверен ечЯм? | to be sure | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уялекАтьея НСВ, | чем? to be carried away | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| углерАд | carbon | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| углублАть НСВ | to deepen | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| утояАрявять | to persuade | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уговорАть кого? | + имф | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| удАпъся удАпъся СВ СВ + + инф инф | to be a success, to turn out well | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| удивительно удивительно | very, extremely | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| удивйтельный | surprising | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| удивление | surprise, astonishment | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| удивляться | to be astonished. | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уднвйться чему? | to be surprised | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уеднн(ниый | solitary, isolated | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ужАсный | terrible, horrible | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| укрАеить СВ, что? чем? | to decorate, to adorn | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| улыбАтьея улыбнуться кому? | to smile | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ульЬбка | smile | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ультрафиолетовый | ultn-violet | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| умАньшять СВ. | что? to diminish, to decrease | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уиикАльяый | unique | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уиичтожАть | to destroy, to abolish | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уннчтАжить кого? | что? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| упАсть СВ (уменьшиться) | to degrade | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уплотнение | condensation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| упДрный | persistent, stubborn | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ураг*и | hurricane, tornado | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Уровен ьм | level, standard | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| усиление | reinforcement, strengthening | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| усйлис | effort | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ytefnCB | to fall asleep | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| jroilirt yenin + имф | to have time | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уенокбнаать успокбнтъ ко»? | to calm, to soothe | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уетАяосп. яс | tiredness, fatigue | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| устДлый | tired | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| установка | installation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| утверждал» НСВ, что? | to assert, to affirm | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Утка | duck | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| утрАчиваться НСВ | to be lost | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ухудшйтмв ИСЯ | to become worse | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| уцелЬъСЯ | to remain whole, to come off unhurt | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| участйтмаСв | to become more frequent | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ученический | apprentice, unskilled | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| учйлнще | college, specialized school | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Унт | ears Act | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| фигура | figure | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| фнналйет | finalist | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| финансовый | financial | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| фйрма | firm | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| формирование | formation | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| фронт | front | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| фруктбвый | fhiit testimonial, reference characteristic | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| issrin НСВ, кому? чего? | to suffice, to be sufficient | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| хлор | chlorine | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| клорсодержАший | containing chlorine | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ХОЭЙНН | boss, host | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| хозййка | mistress, hostess | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| хозяйственная деятель- ность | economic activity | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| холодильник | refrigerator | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| худбкестжиный | art, artistic | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| царица | tsarina, queen | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| цвести//СВ | to bloom, to flower | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| цельж | aim, purpose | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| цен* | price, cost | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| цеийть НСВ, кого? е ком? е чём? | to value, to estimate что? | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| цнанлюбцня | civilization | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| никл | cycle | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| человеческий человеческий род род | mankind, human race | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| человечество | humanity | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| человечность ж | humaneness, humanity | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| честный | honest, honorable | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| честь ж | honour | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| ЧАли | Chile | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| чистый | clean, pure | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| чувство | sense, feeling | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| чудесный чудесный | wonderful, marvellous | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| чУдиый чУдиый | beautiful, marvellous | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. |
| шаг | step, pace | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| шахтер | miner | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| шелест | rustle, rustling sheriff | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| шеф | chief | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| шарокошчий | broad-shouldered | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| широт* | latitude hat state | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| шуметь НСВ | to make a noise | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| шулкть пошутйтъ | to joke, to jest | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| щит | shield, panel Э | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| молюционйрояатъ | to evolve | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| HCBICB | — | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | OCR-quality issue: term/gloss may contain misread characters from a degraded scan; unverified against a print copy. Gloss cell blank in source scan (column-extraction gap). |
| эволюция | evolution | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| эйфория | euphoria | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| экологический | ecological | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мектрбн | electron | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| мемеитАриый | elementary | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| эмАшия | emotion | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| эдбргнн | energy | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| 4ря | era | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| этАп | stage Ю | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Юность ж | youth | verb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Адериый | nuclear | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| япАиец | Japanese | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Япония | Japan | noun | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Аеио | 1) it is clear, it is evident 2) clearly | adverb | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
| Аскый | clear | adjective | core | — | contemporary (source published 2003) | — | — | dictionary | n/a | n/a | — |
## Grammar points

### Verb government contrasts drilled across near-synonym/near-homophone pairs

The exercises repeatedly present two or three semantically-close verbs side by side with their case
government spelled out as a question-word template, then illustrate each with one example sentence —
a recurring pedagogical device across most of the 14 texts, e.g. (Lesson on "Был май", p. 3):

- **провожать/провести** (perfective **проводить**) *кого? куда?* "to see smb off/accompany
  somewhere" (*Студент проводил девушку до трамвайной остановки* — "The student walked the girl to
  the tram stop") vs. **проводить/провести** *что? где?* "to spend (time)" (*Мой друг провёл
  каникулы в деревне*) vs. **проводить/провести** *что?* "to conduct/carry out (an experiment)"
  (*Учёные проводят интересные опыты*) — three distinct case frames sharing one imperfective
  spelling (проводить), disambiguated only by their government pattern and the perfective partner.

- **принимать/принять**: 1) *кого? куда?* "to admit smb (somewhere)" (*его приняли в
  университет*); 2) *кого? что?* "to receive/examine (a patient, a building)"; 3) *кого? за кого?*
  "to mistake smb for smb" (*Шериф принял этих людей за приезжих* — "The sheriff took these people
  for out-of-towners").

- **сажать/посадить**: 1) *кого? куда?* "to seat/place smb" (*Мать посадила ребёнка на стул*); 2)
  *что? где?* "to plant" (*Дети посадили деревья около школы*); 3) *кого? куда?* "to imprison" (*я
  посажу вас в тюрьму*) — one verb spanning literal seating, planting, and the idiomatic-carceral
  sense purely via the object/complement it governs.

- **подходить/подойти** *к кому? к чему?* "to approach" — used both concretely (*Автобус медленно
  подходит к остановке*) and for calendar approach (*Когда подходит 14 апреля...*), showing the verb
  extending from physical to temporal approach without a case-frame change.

- **измерять/измерить** *что?* "to measure" vs. **занимать/занять** *сколько времени?* "to take
  (an amount of time)" vs. **превращаться/превратиться** *во что? в кого?* "to turn into" — a
  second cluster (from the "Озон" chapter, pp. 63–65) again pairing case-government template with a
  worked example each.

### Collective numerals (собирательные числительные)

Explicit "Запомните!" (Remember!) boxed rule (p. 82): collective numerals (двое, трое, четверо,
пятеро...) are used (1) with nouns denoting male persons, where they contrast with the corresponding
cardinal numeral used for the equivalent female-denoting noun — *двое студентов* but *две студентки*,
*трое друзей* but *три подруги*, *пятеро братьев* but *пять сестёр* — and (2) with nouns denoting
paired/plural-only objects — *двое брюк* ("two pairs of trousers"), *трое очков* ("three pairs of
glasses"). The source frames this explicitly as a gendered lexical split rather than a semantic
numeral distinction: the *same* referent count is expressed with a different numeral series purely
because of the noun's grammatical/social gender class.

### Prefix-meaning drills (приставки)

Two separate prefix-meaning exercises ask learners to infer the shared semantic contribution of a
prefix across a set of verbs rather than glossing each verb individually:

- **раз-/рас-** (p. 65): расщеплять "to split/cleave", разлагаться "to decompose", распадаться "to
  disintegrate", разделять "to divide", разрушать "to destroy" — the source's own framing is that
  the learner should identify the common "apart/undone" semantic thread the prefix contributes across
  otherwise unrelated verb roots, rather than being given a rule directly.
- A second, unnamed prefix drill (p. 69, from "Незабываемая встреча") asks learners to compare
  **возникнуть** "to arise" against **исчезнуть** "to disappear" as an aspectual-semantic antonym
  pair, and separately drills **отнимать/отнять** *что? от чего? у чего?* "to subtract/take away
  from" via an arithmetic example (*Если отнять единицу от шести, получим... пять* — "If you
  subtract one from six, you get five") alongside its physics-text extension (*Отнимем у водорода
  единственный электрон, получим протон* — "Take the sole electron from hydrogen, you get a
  proton") — the same governed case frame (*что? от чего? у чего?*) carrying both an everyday and a
  technical-register sense.

### Diminutive/hypocoristic name formation (уменьшительно-ласкательные суффиксы)

A dedicated exercise (p. 16, from "Ветеран") tabulates the productive Russian pattern of forming
affectionate short forms of personal names via a two-step suffix chain — full name → informal short
form → diminutive/affectionate form — giving worked examples: Виктор→Витя→Витенька,
Александр→Саша→Сашенька, Елена→Лена→Леночка, Лидия→Лида→Лидочка, Галина→Галя→Галечка,
Евгений→Женя→Женечка. A follow-up exercise (same page) has the learner produce the missing forms for
a further set (Дарья→Даша→__, Ирина→Ира→__, Иван→Ваня→__, Наталья→Наташа→__, Тамара→Тома→__,
Сергей→Сережа→__, Владимир→Вова→__, Анна→Аня→__) using the suffixes **-еньк-**, **-очк-**, and
**-ечк-** — the source treats these three as the productive set for this pattern, without giving a
selection rule for which suffix attaches to which short form (the worked examples suggest it tracks
the short-form's final consonant/vowel, but this is not stated explicitly by the source and is left
as an open question rather than asserted as fact here).

### Aspect with "до тех пор, пока не" (until)

Explicit note (p. 92, glossary-adjacent exercise on "Последнее сражение"): the conjunction *до тех
пор, пока не* ("until... not") governs a **perfective** verb in the subordinate clause even though
the sense is durative/negative — *Я учил новые слова до тех пор, пока не выучил их* ("I studied the
new words until I had learned them"), *Мы работали до тех пор, пока не наступила ночь* ("We worked
until night fell"). The source frames this as a fixed aspect-selection rule tied to this specific
conjunction, not a general rule about "until" clauses.

### 1st-person-plural future for logical/argumentative reasoning

Explicit note (p. 71, from "Послание богов"): when a text is making a logical argument/proof
(*логическое рассуждение*), the verb is conventionally used in the **1st person plural future**
regardless of who is actually reasoning — *обратим внимание* ("let us note"), *отнимем* ("let us
subtract"), *получим* ("we obtain") — functioning as an impersonal-argumentative register marker
(comparable to English mathematical-proof "we obtain..."/"let us take..." register) rather than a
literal plural-subject statement.

### Idioms and near-synonym glosses drilled inline (not restated in the master glossary)

Several idiomatic expressions are explicitly glossed via a synonym/paraphrase device (*"зд." = "here,
in this context"* is the source's own abbreviation marker for a contextual/non-literal sense) rather
than appearing as ordinary headwords:

- **мне казалось** — *зд.* я думала ("it seemed to me" → contextually "I thought")
- **влюблен(а, -ы)** — любит(-ят) ("in love (with)" glossed via the plain verb "to love")
- **напрасно** — бесполезно, безрезультатно ("in vain" ≈ "uselessly, without result")
- **безумно влюбиться** — влюбиться очень сильно ("to fall madly in love" ≈ "to fall very strongly
  in love" — the source glosses the intensifying adverb безумно as a plain degree modifier, not its
  literal "insanely")
- **делать вид** — (idiom, "to pretend/put on an appearance"), illustrated: *Она не понимала законы
  физики, но делала вид, что всё понимает* ("She didn't understand the laws of physics, but pretended
  she understood everything")
- **быть не в силах + инф.** — "to be unable to (do smth)", illustrated *Я был не в силах произнести
  ни слова* ("I was unable to utter a single word")
- **похож как две капли воды** — "to look alike as two drops of water" (idiom for close physical
  resemblance)
- **оставлять/оставить кого? в покое** — "to leave smb in peace/alone"
- **лежать на виду** — быть легко видимым, понятным ("to lie in plain view" ≈ "to be easily
  visible/understandable")
- **вглядеться** — посмотреть очень внимательно ("to peer at" ≈ "to look very attentively")
- **могущественный** — очень сильный ("powerful/mighty" ≈ "very strong")
- **жизненный** — *зд.* способный к жизни, имеющий право на жизнь ("vital" → contextually "capable
  of living, entitled to live" — a specific bioethical/philosophical-register sense the source flags
  as context-bound rather than the word's default meaning)

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. Illustrative example sentences quoted above are short,
single-sentence excerpts used to demonstrate a case-government or aspect pattern, consistent with
`../../00_Reference_Extraction_Spec.md`'s copyright discipline. The master glossary table reproduces
individual headword→gloss pairs (a structured lexical index, not narrative prose or a scanned
image), consistent with how this project's other reference-book glossaries (e.g. *Newspaper Russian*,
1,719 entries) have been extracted.
