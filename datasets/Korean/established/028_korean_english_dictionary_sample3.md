# Korean — Established Vocabulary: *A Korean-English Dictionary*, Sample 3 (PDF pp. 481–720)

**Source:** `source_reference/languages/Korean/14.A Korean-English dictionary.pdf`, PDF pages
481–720 of 962. Notation (Yale romanization, `bnd`/`cpd`/`inf.`/`-W-`/`-L-` stem-class markers, the
`HEAVY ISOTOPE`/`LIGHT ISOTOPE` sound-symbolism cross-reference system) strongly matches Samuel E.
Martin, Yang Ha Lee & Sung-Un Chang, *A Korean-English Dictionary* (Yale University Press, 1967) —
**this attribution is inferred from the dictionary's own distinctive apparatus, not confirmed
against a title page in this page range**; flagging as presumed rather than verified. This is a
large general-purpose bilingual dictionary (962 PDF pages), not a grammar-pedagogy source.

**Scope discipline — this is a deliberate sample, not exhaustive coverage.** This page range alone
holds many thousands of headwords; transcribing all of them would both violate the copyright
discipline (bulk reproduction of a dictionary) and bury genuinely useful signal in pedagogically
inert bulk-lexicon noise. Per the dispatch instructions, **8–10 representative two-page spreads
were sampled at roughly even intervals across the assigned range**, prioritizing entries carrying
an explicit register/usage annotation, an interesting morphological/compounding pattern, or a
notable sound-symbolic ("isotope") pairing — exactly the kind of entry this project's later
mechanics-analysis phase needs. This file is one of three parallel dictionary-sample dispatches
(sample 1 covering an earlier PDF-page range, sample 2 a middle range, this one the third
quarter) — no attempt was made to deduplicate against the other two samples' specific headwords,
since each covers a disjoint alphabetical range by construction (the dictionary is a single
continuously-alphabetized sequence).

**PDF/rendering gotcha confirmed for this file.** `pdftotext`/`pdffonts` report **no text layer at
all** for this range (confirmed via a blank `pdftotext -f 481 -l 482` extraction and an empty
`pdffonts` font table) — this is a pure image scan, not a font-substitution-cipher case. All
content below was vision-read from rendered page images (`pdftoppm -r 150 -png`).

**Page-offset gotcha, verified empirically before committing to the page range (per the spec's
warning about exactly this).** Each PDF page renders as **two printed dictionary pages side by
side** (a physical two-page spread scanned as one image), not one printed page per PDF page.
Verified via direct inspection at three points spanning the assigned range: PDF p. 481 → printed
pp. 940–941; PDF p. 600 → printed pp. 1178–1179; PDF p. 720 → printed pp. 1418–1419. This confirms
a consistent formula across the whole range: `left_printed_page = 940 + 2×(pdf_page − 481)`. The
9 spreads actually sampled and their printed-page/headword-range anchors: PDF 481 (940–941,
서풋…석음), PDF 510 (998–999, 수…수궁), PDF 540 (1058–1059, 실습…실패), PDF 570 (1118–1119,
양의…향-호), PDF 600 (1178–1179, 연화…열렬-히), PDF 630 (1238–1239, 우러-나오다…우비-칼), PDF 660
(1298–1299, -을 따름…-을-세), PDF 690 (1358–1359, 일임…일치), PDF 720 (1418–1419, 저³…저/뻬(르)령).

**Vision-reading confidence.** All 9 sampled spreads are genuinely typeset, print-quality
dictionary pages — dense but consistently set in the same font, no scan artifacts obscuring
legibility, and **no handwritten marginalia of any kind was found on any sampled page** (checked
per the spec's marginalia guard). All entries below are marked `verified`; a handful of very small
diacritic/romanization marks (macrons, breves) were read with high confidence given the
dictionary's internally consistent romanization system, but are not separately downgraded.

**Notable structural finding: the dictionary's own sound-symbolism ("isotope") apparatus.** Many
entries cross-reference a `HEAVY ISOTOPE ⟷` or `LIGHT ISOTOPE ⟷` counterpart — e.g. 우렁-우렁
`wuleng weleng` (HEAVY, "thundering, rumbling boom") cross-referenced against a lighter-vowel
counterpart, or 쓰기/싹 `ssek`/`ssak` pairs. This is the same *dark/bright vowel* and
*plain/tense/aspirated consonant* phonaesthetic system already documented from `Using Korean` ch.
13 (`established/008`) — this dictionary encodes it systematically, headword-by-headword, across
the entire lexicon, which is a much larger evidence base than the earlier textbook excerpt. Worth
returning to for the mechanics-analysis phase: this dictionary could supply a large corpus of
attested isotope pairs.

**Slang/informal-register clustering found — flagged, not moved.** Several sampled entries carry
explicit derogatory, jocular, dialectal, or "babyish/rustic" register tags that the dictionary
itself marks in small caps (`[DEROGATORY]`, `[JOCULAR]`, `[COLLOQ.]`, `[BABYISH OR RUSTIC]`,
`[DIAL.]`, `[ARCHAIC]`, `FAMILIAR`). These are exactly the kind of register-annotated content the
extraction spec flags as high-value and that may eventually belong in `language_corpus/Korean/` as
attested informal vocabulary — noted here for that future pass, not relocated as part of this
dispatch. See in particular 저-까짓/저-놈/저-따위 (derogatory demonstrative-noun cluster, p. 1418),
양-코/양-키 (jocular/loanword ethnic-nickname terms, p. 1119), and the `-을랑` particle explicitly
tagged `[BABYISH OR RUSTIC]` (p. 1298).

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 서풋(-서풋) | lightly, with a light-footed step | adverb | literary | — | — | — | — | dictionary | n/a | verified | p. 940. HEAVY ISOTOPE cross-ref to 사풋(-사풋); PARA-INTENSIVE of 서웆(-서웆). |
| 썩 | very much, greatly, exceedingly; right away | adverb | core | — | — | — | — | dictionary | n/a | verified | p. 940. HEAVY ISOTOPE ⟷ 싹 `ssak` (light counterpart, "with one clean stroke"). |
| 썩다 | rots, decays, corrupts | verb | core | — | — | — | — | dictionary | n/a | verified | p. 940. |
| 석-쇠 | grid-iron | noun (compound) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 941. Explicitly tagged `[COLLOQ.]` = 적-쇠 `cek soy`, its non-colloquial synonym — a rare same-page colloquial/standard synonym pair. |
| 썩어-빠지다 | rots completely, is utterly rotten | verb (compound, vi. + aux.) | core | — | — | — | — | dictionary | n/a | verified | p. 941. Stacked vi.+aux. construction; HEAVY ISOTOPE marked. |
| 석-굴 | a rocky cavern, a stone cave | noun (compound) | core | — | — | — | — | dictionary | n/a | verified | p. 940. Example cites 석굴-암 Sŏkkuram, the temple near Pulguk-sa in Kyŏngju. |
| -수 [Seoul] | authoritative indicative sentence-ending (dialectal/register variant) | suffix/particle | regional | — | — | Seoul | subnational | dictionary | n/a | verified | p. 998. Explicit usage note: "[Seoul] var. < -소"; used by seniors toward servants/family juniors, contrasts with plain-register -어/-다/-네 forms toward friends. Rare explicit sociolinguistic register note embedded directly in a dictionary entry. |
| 수고 | trouble, pains, efforts | noun | core | — | — | — | — | dictionary | n/a | verified | p. 998–999. Extensive idiom cluster: 수고-롭다 "is toilsome," 수고-스럽다 "is tiresome, painstaking." |
| 수군-거리다 | whispers | verb (reduplicative, sound-symbolic) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 999. HEAVY ISOTOPE ⟷ 소곤-거리다 (light counterpart, same meaning at a softer register). |
| 수꿀-하다 | 1. is shrinking with fear 2. is boiling up with many bubbles | adjective/verb | core | — | — | — | — | dictionary | n/a | verified | p. 999. Two unrelated senses under one headword. |
| 실-없다 | is untrustworthy, insincere, idle, vain, silly | adjective (compound, bnd n. + postnom.) | core | — | — | — | — | dictionary | n/a | verified | p. 1058. Literally "lacks substance" (실 substance + 없다 lack). |
| 실없-장이 | a silly fool, an unreliable/insincere person | noun (compound) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1058. 장이 agentive/characterizing suffix ("-er/one characterized by"), same suffix family as 장사-꾼-type agentives seen in `established/001`. |
| 실쭉-거리다 | distorts, moves at a bad angle, sulks | verb (reduplicative) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1059. HEAVY ISOTOPE ⟷ 샐쭉- (light counterpart). |
| 실컷 | to one's heart's content, as much as one likes, till one is sick of it | adverb | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1059. Etymology given: `< 실- + var. of 껏 "till loathed"`. Illustrative idiom retained per copyright discipline (single short example, not the full entry): "먹다 (마시다) eats (drinks) till it is coming out one's ears." |
| 양-코 | "foreigner's nose" = a large protruding nose | noun (compound) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1119. Explicitly tagged `[JOCULAR]`. |
| 양키 | a Yankee; an Occidental | noun (loanword) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1119. Marked `< E.` (English loan). |
| 양-주정 | drunken rowdiness in the Western style | noun (compound) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1118. 洋 "Western/foreign" + 酒酊 "drunken rowdiness" — the 洋 prefix productively derives a whole cluster of "Western-style X" nouns on this spread (양-취 feigned drunkenness, 양-탄자 rug, 양-치기 sheep-raising vs. homographic 양치 mouth-rinsing). |
| 양치 | rinsing the mouth, brushing one's teeth | noun/verb | core | — | — | — | — | dictionary | n/a | verified | p. 1119. Homograph collision with the unrelated 羊 "sheep"-derived compound 양-치기 "sheep-raising" on the same spread — a clean example of Sino-Korean vs. native-compound homography. |
| 열-기 | fever; enthusiasm, craze, fad, boom, rage | noun | core | — | — | — | — | dictionary | n/a | verified | p. 1178. Semantic range spans literal fever → metaphorical "craze" (e.g. 축구 열기 "football fever," 금광 열기 "gold fever"). |
| 열-광 | enthusiasm, frenzy, fanaticism, mania | noun | core | — | — | — | — | dictionary | n/a | verified | p. 1179. |
| 열-등 | inferiority, low class, backwardness | noun (compound-productive) | core | — | — | — | — | dictionary | n/a | verified | p. 1179. Productive as a modifier: 열등-품 "low-grade goods," 열등-국 "backward country," 열등-아 "backward child," 열등-감 "inferiority complex." |
| 열-데 | familiar retrospective assertive sentence-final particle | particle | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1179. Tagged `FAMILIAR retr. assert. < 열다`. |
| 우렁-우렁 | thundering, rumbling, booming | adverb (reduplicative, sound-symbolic) | literary | — | — | — | — | dictionary | n/a | verified | p. 1238. HEAVY ISOTOPE ⟷ 우렁-찬 "resounding, imposing"; part of the same isotope-pair family as 우렁-찬 "thundering voice / magnificent house." |
| 우물쩍-주물쩍 | vaguely, indistinctly, hesitantly, halfheartedly | adverb (reduplicative) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1239. = 우물-쭈물, glossed with the idiom "scamps one's work, does a job halfheartedly." |
| 우매 | stupidity and ignorance | noun | core | — | — | — | — | dictionary | n/a | verified | p. 1239. = 우미 (synonym cross-ref). |
| 우부 | a stupid fellow / a stupid (foolish) woman | noun | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1239. Two Sino-Korean compounds (愚夫/愚婦) sharing the 愚 "foolish" root, gendered forms listed as separate headwords. |
| 우려-먹다 | extorts, squeezes (money, etc. from someone) | verb (idiom) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1238. = 울그다/울쿠다; figurative extension of 우리다 "soaks out (flavor)." |
| -을랑 | topic-marking particle, "as for" | particle | regional | — | — | — | — | dictionary | n/a | verified | p. 1298. Explicitly tagged `[BABYISH OR RUSTIC]`. Alternant shape after vowels is -ㄹ랑. |
| -을레 | dialectal retrospective familiar assertive ending | particle | regional | — | — | — | — | dictionary | n/a | verified | p. 1298. Tagged `[DIAL.]` = 겠데 (standard equivalent). |
| -을러니 | dialectal sequential retrospective ending | particle | regional | — | — | — | — | dictionary | n/a | verified | p. 1298. Tagged `[DIAL.]` = -겠드니. |
| -을 상부르-하다 | it looks/seems to be (that) | verbal construction | regional | — | — | — | — | dictionary | n/a | verified | p. 1299. Tagged `[DIAL. — Siberian?]` — the dictionary's own uncertain regional attribution (querying whether this is a Koryo-saram/far-northern-diaspora form), retained verbatim as a hedge rather than resolved. |
| -을세 | familiar indicative assertive sentence-ender | particle | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1299. Two senses distinguished: plain assertion ("That's fine") vs. archaic-tagged conditional/apprehensive use. |
| 일찝다 | is annoying, irksome | adjective (-W- stem class) | core | — | — | — | — | dictionary | n/a | verified | p. 1358. |
| 일쭉-알쭉 | slipping/sliding easily this way and that (like fine-textured cloth) | adverb (reduplicative) | literary | — | — | — | — | dictionary | n/a | verified | p. 1359. |
| 일체-다부 | polyandry | noun (compound) | technical | — | — | — | — | dictionary | n/a | verified | p. 1359. Sino-Korean 一妻多夫 "one wife, many husbands"; cross-referenced against 일부-다처 (polygyny) elsewhere in the dictionary. |
| 저-까짓 | such a trifling, slight, worthless thing as that | pre-noun (bnd, usually pejorative) | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1418. Dictionary's own usage label: "(usually pejorative)." LIGHT ISOTOPE ⟷ 조-까짓. |
| 저-놈 | that damn guy/thing ("S.O.B.") | noun (compound) | taboo | — | — | — | — | dictionary | n/a | verified | p. 1419. Tagged `[DEROGATORY]`. |
| 저-따위 | that kind of, that sort of (person/thing) | pre-noun/noun | taboo | — | — | — | — | dictionary | n/a | verified | p. 1419. Tagged `[DEROGATORY]`. |
| 저런³ | interjection of surprise: "Oh dear! Goodness! My my!" | interjection | colloquial | — | — | — | — | dictionary | n/a | verified | p. 1419. Distinguished by superscript from two unrelated homographic headwords 저런¹ (adj. "like that") and 저런² (vi. mod. "having done that"). |

## Grammar points

### The dictionary's register/usage-label apparatus

Beyond the vocabulary itself, this dictionary's own small-caps bracketed labels are a
directly-reusable register taxonomy: `[DEROGATORY]`, `[JOCULAR]`, `[COLLOQ.]`, `[BABYISH OR
RUSTIC]`, `[DIAL.]`, `[ARCHAIC]`, and unbracketed `FAMILIAR`/`LIGHT ISOTOPE`/`HEAVY ISOTOPE`
notations attached directly to headwords. This is a finer-grained, entry-level register system than
any teaching-grammar source extracted so far in this project — worth treating as a candidate
register taxonomy cross-check against `00_Usage_Tier_Taxonomy.md` in a future dedicated pass, since
a dictionary this size could supply hundreds of pre-tagged register examples rather than the
handful found per teaching-grammar chapter.

### Sound-symbolic ("isotope") pairs as a productive derivational pattern

The HEAVY ISOTOPE/LIGHT ISOTOPE cross-reference system (e.g. 우렁-우렁 ⟷ its lighter-vowel
counterpart, 썩 ⟷ 싹, 실쭉- ⟷ 샐쭉-) documents, headword by headword, the same dark/bright-vowel
and plain/tense/aspirated-consonant phonaesthetic alternation already flagged from `Using Korean`
ch. 13 (`established/008`). Because this dictionary applies the label systematically across its
entire lexicon rather than in one illustrative textbook chapter, it is a much richer future data
source for this specific mechanism than anything sampled so far — flagged for the mechanics-analysis
phase, not analyzed in depth here (out of scope for a vocabulary-sampling dispatch).

### Homography between unrelated Sino-Korean and native compounds

Several sampled entries (양치 "mouth-rinsing" vs. 양-치기 "sheep-raising"; 실쭉- vs. unrelated
senses) illustrate that Korean's heavy reliance on a small CV-syllable inventory plus multiple
etymological strata (native / Sino-Korean / loanword) produces frequent homograph collisions that
are disambiguated only by context or hanja gloss — worth keeping in mind for any invented-slang
work that repurposes existing syllable shapes, since real Korean already tolerates a high
homography load.
