# Korean — Established Reference: *A Korean-English Dictionary* (Martin/Lee/Chang), sampled, part 4 of 4 (final quarter)

**Source:** Samuel E. Martin, Yang Ha Lee, and Sung-Un Chang, *A Korean-English Dictionary* (Yale
University Press, begun 1953 as a Yale research project, first edition; per the book's own
Introduction, pp. vi–vii), PDF pages 721–962 of 962 (the final quarter of the book, through the
literal end of the file — printed pages ~1420 through 1902, entries 저(리)- through 힝힝).

**This is a large general-purpose bilingual dictionary — deliberately sampled, not exhaustive.**
Per dispatch instructions, this file represents **10 sampled spreads at roughly even intervals**
across the assigned range (PDF pp. 721, 748, 775, 802, 829, 856, 883, 910, 937, 962 — printed pp.
1420–1421, 1474–1475, 1528–1529, 1582–1583, 1636–1637, 1690–1691, 1744–1745, 1798–1799, 1852–1853,
and 1902), not a continuous or complete read of ~480 printed pages. Within each sampled spread,
entries were chosen for register annotation, morphological/phonaesthetic interest, or otherwise
notable content — the great majority of ordinary headwords on each page are **not** transcribed,
per the copyright-discipline and coverage-sampling instructions for this dispatch. Do not treat
this file as a survey of everything in pages 721–962; treat it as an evidence sample plus a
structural/mechanism finding (see below).

**No back-matter appendix found.** PDF page 962 (printed p. 1902) is the literal final page of the
book — the last entry is 힝힝 *hing-hing* ("clearing one's nose repeatedly"), immediately followed
by the end of the file (`pdfinfo` confirms 962 total pages). There is no grammar summary, radical
index, or other back-matter appendix appended after the dictionary body in this range; the main
alphabetical entry list simply ends where the alphabet ends (ㅎ).

**Vision-reading gotcha (a new variant for this project): two printed pages per PDF page, i.e. the
same "spread" gotcha flagged in `00_Reference_Extraction_Spec.md`, confirmed again here.** Every
PDF page in this range renders as a two-page spread (odd/even printed-page pair) with the printed
page number and running headword visible in the top corners of each half — verified directly by
inspection rather than assumed. Empirically-derived offset for this range: `printed_left_page =
2 × (PDF_page − 721) + 1420` (verified at all 10 sampled points, including both endpoints).

**Vision-reading confidence.** All 10 sampled spreads are genuinely typeset, high-quality print —
this book's own production notes (p. vi) describe extensive scholarly proofing, and the scan
quality confirms it: no scan artifacts, no ambiguous glyphs, and **no handwritten marginalia found
anywhere in the sampled range** (checked per the spec's marginalia guard on every spread read).
All entries below are marked Vision Reading Confidence `verified` — Yale-romanized headwords are
printed in bold Latin type alongside the Hangul, giving an internal cross-check on every single
entry (the two scripts must agree), which is stronger corroboration than most vision-read sources
in this project have had available.

**Notable structural finding — the dictionary's own phonetic-symbolism marking system.** The book's
Introduction (p. vi, §3 Coverage) states explicitly: *"We have tried to give a somewhat more
extensive coverage of features of phonetic symbolism than that found in other dictionaries; entries
are cross-referenced as 'heavy' and 'light' isotopes when vowel quality is exploited, as 'intensive'
and 'para-intensive' when consonant strengthening is involved."* This is fully confirmed by the
sampled spreads: dozens of expressive/mimetic (onomatopoeic and phenomimetic) word-pairs are
explicitly cross-tagged `LIGHT ISOTOPE ↔`/`HEAVY ISOTOPE ↔` a paired form differing only in vowel
quality (bright/front vowel = "light," dark/back vowel = "heavy," tracking size/intensity/delicacy —
e.g. 탈싹 *thalssak* LIGHT ISOTOPE ↔ 털썩 *thelssek* HEAVY ISOTOPE, "plop, with a thud"; 화끈 *hwa-kkun*
LIGHT ISOTOPE ↔ 후근- *hwu-kun*, "sudden flash of heat" vs. a duller/heavier version; 히히 *hi-hi*
HEAVY ISOTOPE ↔ 해해 *hay-hay*, two registers of quiet/offhanded laughter), plus a separate
`PARA-INTENSIVE <` tag marking consonant-strengthened intensive derivations (e.g. 펄 *phel*
PARA-INTENSIVE < 벌 *pel*; 펑 *pheng* PARA-INTENSIVE < 뻥 *ppeng*). **This directly connects to two
already-extracted Korean sources' sound-symbolism material** — `established/013`'s Ch. 4/5 vowel-
harmony and prosody findings, and `established/008`'s §13.1–13.3 vowel/consonant phonaesthetic
system — but this dictionary is a far larger, systematically-tagged corpus of the actual word pairs
those chapters only characterized in the abstract. **Flagged as a high-value target for a future
dedicated mechanism-analysis pass** (`analysis/`) rather than extracted in bulk here, since doing it
justice would mean harvesting hundreds of isotope pairs across the whole alphabet, not a handful
from a 10-spread sample — but the pattern itself, and a representative set of pairs, is captured
below.

**Slang/informal-register clustering flagged for `language_corpus/Korean/`.** One entry sampled,
지랄 *cilal* (p. 1528, "an epileptic fit... [FIG.] acts unreasonably, behaves rampageously, makes a
fuss, makes a scene, goes crazy, has a fit, gets hysterical"), is the historical/clinical sense
underlying a very well-known modern Korean slang/taboo interjection (지랄 as "bullshit!"/"cut the
crap!"/"knock it off") — not itself extracted as slang here (this 1967 dictionary only records the
older clinical/figurative sense, not the modern interjection), but flagged as a concrete etymological
throughline worth checking against `language_corpus/Korean/` if/when that corpus covers modern taboo
interjections. Similarly 화냥(-년) *hwanyang(-nyen)* ("a loose woman, a whore," p. 1852) carries the
dictionary's own etymological query `[? < var. 화랑 'Sin.la warrior']` linking a taboo/derogatory term
to the Silla-era *hwarang* warrior-caste name — a genuine, source-stated folk-etymology worth noting
for any future register/taboo-vocabulary mechanism analysis.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 저리(低利) 저리 celi | low interest, a low rate of interest | noun | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1420. Sino-Korean compound: 低 "low" + 利 "interest/profit." |
| 저-자(-者) ce ca | that person, that fellow, that guy over there | cpd noun (pre-n. + n.) | slang | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1421. Explicitly tagged `[DEROGATORY]` in source. |
| 저열(低劣) cēyel | vulgarity, baseness; is base, vulgar | noun/adj-n. | taboo | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1420. |
| 저쑵다 cesswupta | bows to a divinity | verb | archaic | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1420. Explicitly tagged `[? ARCHAIC]` in source. |
| 저씃다 cesswusta | = 저쑵다 | verb | regional | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1420. Explicitly tagged `[? DIAL.]` in source. |
| 조용-하다 co'yong hata | is quiet, still, silent, tranquil, calm, secluded | adjective | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1474. |
| 조오 coo | (contracted/informal question or statement form of 좋다 "be good") | verb form | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1474. Explicitly tagged `AUTHORITATIVE question/statement` — a distinct register the dictionary uses for blunt/superior-to-inferior speech forms. |
| 조작- cocak | showing off; toddling | mimetic root | slang | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1474. Tagged `LIGHT ISOTOPE → 주적- cwucek (showing off; toddling): XX, XXh=Xk` — a light/heavy vowel-symbolism pair (see coverage note above). |
| 조잔- cocan | snacking between meals | mimetic root | slang | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1474. Tagged `LIGHT ISOTOPE ↔ 주전- cwucen: XX, XXh=Xk, X-puli`. |
| 지딱- cittak | hurriedly and at random, recklessly | adverb | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1528. |
| 지도리 citoli | hinge(s) | noun | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1528. Etymology given: `< 지돌이 'carry-turn' der. n.` — a transparent deverbal compound. |
| 지랄 cilal | an epileptic fit; [FIG.] acts unreasonably, behaves rampageously, makes a fuss, makes a scene, goes crazy, has a fit, gets hysterical | noun/verb (idiom) | taboo | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1528. `LIGHT ISOTOPE 재랄`. See coverage note above — clinical/older figurative sense of a term whose modern reflex is a common taboo interjection; not itself extracted as slang here. |
| 지랄-병 cilalq pyeng | epilepsy | cpd noun | technical.medical | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1528. 지랄 "fit" + 병 "disease." |
| 지랄-쟁이 cilal ca(y)ngi | an epileptic; [FIG.] a capricious, unreliable, irresponsible person | cpd noun | taboo | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1528. 지랄 + agentive/pejorative suffix -쟁이. |
| 지독-하다(至毒-) citok hata | is vicious, vitriolic, atrocious, spiteful, ferocious; severe, terrible, extreme, hard, tough, unflinching, dogged, thick-skinned | adjective | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1528. |
| 처먹다 che mekta | eats greedily, digs in, shoves down, devours | verb (bnd adv. + vt.) | taboo | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1582. Explicitly tagged `[VULGAR, DEROGATORY]` in source — 처- is a pejorative-intensifying prefix on 먹다 "eat." |
| 처먹이다 che mek.ita | feeds immoderately, stuffs (a child with sweets) | verb (bnd adv. + vc.) | taboo | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1582. Explicitly tagged `[VULGAR, DEROGATORY]` in source. |
| 처신-없다(處身-) chēsin ēps.ta | is undignified, ungentlemanly, unbecoming | adjective (n. + qvi.) | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1582. |
| 처신-사납다(處身-) chēsin sanapta | is disreputable, discreditable, scandalous, outrageous | adjective | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1583. |
| 축-처지다 chwuk che-cita | droops or sags low, hangs down low | verb (adv. + cpd vi.) | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1637. |
| 축-축 chwuk-chwuk | all drooping low, hanging down low, all sagging low | adverb | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1636. `HEAVY ISOTOPE ↔ 촉촉-` — light/heavy vowel-symbolism pair. |
| 춘기(春機) chwunki | sexual desire; sexual awakening, puberty; "the age of hebetic irregularities" | noun | technical.medical | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1637. Euphemistic Sino-Korean compound: 春 "spring" + 機 "mechanism/opportunity"; source glosses onset of puberty as 발동 "sexual awakening" and 발동-기 "the period of puberty." |
| 탈 thal | a hitch, a snag, a failure, trouble, a mishap; a mask | bound noun | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1690. Source's own etymological note: "[Meaning and pronunciation peculiar to Korea.]" — flagged by the dictionary itself as a Sino-Korean character (脫) used with a Korea-specific extended sense beyond its literal Chinese meaning. |
| 탈-쓰다² thāl-ssuta² | is the very image of, is an exact likeness (replica) of | verb (idiom) | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1691. Figurative idiom built on 탈 "mask" + 쓰다 "wear": "she is the spit and image of her mother." |
| 탈락- thallak | keeps slapping, slipping | mimetic root | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1690. `LIGHT ISOTOPE ↔ 털럭-`. |
| 탈싹 thalssak | with a plop, with a thud | adverb | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1691. `LIGHT ISOTOPE ↔ 털썩`. |
| 탈영(脫營) thal.yeng | desertion from the barracks (or encampment); being AWOL | noun | technical | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1691. |
| 펄떡- phelttek | palpitate, throb; struggle, jump; coming in and going out all the time | mimetic root | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1744. `HEAVY ISOTOPE ↔ 팔딱- phalttak`, further tagged `PARA-INTENSIVE`; cf. 풀떡-/벌떡-. |
| 펑펑 pheng-pheng | with explosion after explosion; popping and popping; gurgling and gurgling; plunging or plopping repeatedly | adverb | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1744. `HEAVY ISOTOPE < 뻥뻥 (PARA-INTENSIVE)` — the base 뻥 that this derives from is the same root behind modern slang 뻥 "a lie, a bluff." |
| 편(便) phyen | a side, a direction; a party, a faction; a means, a way; a chance, an opportunity | bound noun/postnoun | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1745. |
| 편-갈리다(便-) phyen kallita | gets divided into two parties (teams) | verb (n. + vp.) | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1745. |
| 한잡-인(閑雜人) hancap-in | an intruder, an outsider | noun | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1798. |
| 한테 hanthey | to, at, for, by (a person) | particle | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1799. Explicitly tagged `[COLLOQ.] = 에게 eykey`; survives as the ordinary modern spoken dative/locative particle for animate nouns. |
| 한테로 hanthey lo | toward (a person) | particle (pcle + pcle) | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1799. Explicitly tagged `[COLLOQ.] = 에게로`. |
| 한테서 hanthey se | from (a person) | particle (pcle + pcle) | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1799. Explicitly tagged `[COLLOQ.] = 에게서`. |
| 한풀-꺾이다 han-phul kkekk.ita | is taken down a peg (or two); is crestfallen, down-in-the-mouth | verb (idiom) | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1799. Literally "one starch removed" — idiom built on 한 "one" + 풀 "starch" + 꺾이다 "gets broken/bent." |
| 한풀이-하다(恨-) hān-phul.i hata | vents spite over, satisfies a grudge, revenges oneself for, pays off old scores, takes out (one's) anger | verb | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1799. Built on 한(恨) "han, resentment/grief" + 풀이 "un-knotting, resolving" — the lexicalized verb form of the well-known Korean cultural concept *han*. |
| 화(禍) hwā | an evil, a curse, a misfortune, a disaster, a calamity, a woe | noun | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1852. Idiom cited: "Misfortune never comes single. One misfortune rides upon another's back. It never rains but it pours." |
| 화끈 hwa-kkun | with a sudden flash of heat, with a throb (a glow, a flush) | adverb | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1852. `LIGHT ISOTOPE ↔ 후근-`. |
| 화끈-거리다 hwa-kkun kelita | feels hot, burns, glows, flushes, throbs with heat | verb | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1852. |
| 화-나다(火-) hwā nata | gets angry, enraged, indignant, infuriated, gets mad | verb (n. + vi.) | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1853. 화 "anger/fire" + 나다 "arises." |
| 화냥(-년) hwanyang(-nyen) | a loose woman, a whore | noun | taboo | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1853. Source's own etymological query: `[? < var. 화랑 'Sin.la warrior']` — see coverage note above. |
| 화냥-질 hwanyang cil | a woman's adultery | cpd noun | taboo | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1853. 화냥 + pejorative-activity suffix -질; cf. 서방-질 sepang cil "(a man's) adultery" cited alongside it in the source. |
| 히히 hi-hi | (an offhanded or quiet laugh) | interjection | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1901 (spread adjacent to the p. 1902 endpoint sample). `HEAVY ISOTOPE ↔ 해해 hay-hay`. |
| 힘 him | strength, energy, force, vigor, power, might, capability, courage | noun | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1901. Final headword-family of the dictionary; extensive polysemy list in source (physical strength through influence/authority through courage/nerve). |
| 힘-차다 him chata | is full of strength, is powerful, energetic, forceful | adjective (n. + adj.) | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1902. |
| 힘-겨룸 him kyelwum | a contest of strength | cpd noun | core | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1901. |
| 힝 hing | (the sound of) clearing one's nose | interjection | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1902. |
| 힝힝 hing-hing | clearing one's nose repeatedly | adverb | colloquial | — | contemporary (source published 1967) | — | — | dictionary | n/a | verified | p. 1902. **The literal final entry of the dictionary** — last headword on the last page (PDF p. 962 of 962). |

---

## Grammar points

### The dictionary's phonetic-symbolism annotation system (LIGHT/HEAVY ISOTOPE, INTENSIVE/PARA-INTENSIVE)

Per the source's own Introduction (p. vi, §3), this dictionary systematically cross-references
expressive/mimetic word pairs that differ by a single sound-symbolic dimension:

- **"Isotope" pairs (vowel quality):** a `LIGHT ISOTOPE` form uses a bright/front vowel and denotes
  a smaller, lighter, or more delicate version of the sensation/action; its paired `HEAVY ISOTOPE`
  form substitutes a dark/back vowel and denotes a bigger, heavier, or more intense version of the
  same root sensation/action. Every sampled instance (조작-/주적-, 조잔-/주전-, 탈락-/털럭-, 탈싹/
  털썩, 축축/촉촉, 화끈/후근-, 히히/해해, 펄떡-/팔딱-) is cross-tagged explicitly in the entry
  itself, not left implicit.
- **"Intensive"/"para-intensive" pairs (consonant strengthening):** a base form's initial consonant
  is "strengthened" (typically plain → tensed or aspirated) to derive a more forceful/emphatic
  variant — e.g. 펄 *phel* is tagged `PARA-INTENSIVE < 벌 pel`, and 펑 *pheng* is tagged
  `PARA-INTENSIVE < 뻥 ppeng`.
- This is presented by the dictionary's own authors as a deliberately fuller treatment of Korean
  sound symbolism than other dictionaries of its era attempted — consistent with, and considerably
  more systematic than, the vowel/consonant phonaesthetic material already captured from
  `established/008` (*Using Korean*, §13.1–13.3) and `established/013` (*The Sounds of Korean*,
  Ch. 4–5 adjustment processes and prosody). A future `analysis/` mechanism pass on Korean
  sound-symbolic vocabulary should treat this dictionary as its primary raw-data source, given the
  sheer number of explicitly pre-tagged pairs available across the full alphabet (only a small
  sample of which could be captured in this 10-spread pass).

### Register/formality tags used throughout this dictionary

Distinct from the vocabulary-table `Usage Tier` column (which this file maps onto the project's own
shared taxonomy), the dictionary carries its own bracketed register labels directly in entries —
confirmed present in the sampled spreads: `[VULGAR, DEROGATORY]`, `[DEROGATORY]`, `[FIG.]`,
`[COLLOQ.]`, `[? DIAL.]`, `[? ARCHAIC]`, `AUTHORITATIVE` (for blunt/superior-register question or
statement forms), `honorific`/`HONORIFIC`, and `SAME`/`SYN.`/`CF.` cross-reference tags (not
register markers, but frequent enough to note as the dictionary's citation convention). These were
preserved verbatim in the Notes column above wherever a sampled entry carried one, per the coverage
rule's instruction to never silently drop an explicit register/dialectal annotation the source
itself marks.

### Etymological self-annotation

The dictionary flags several entries as having a meaning "peculiar to Korea" for a given Chinese
character (e.g. 탈 *thal*, p. 1690) — i.e., cases where a Sino-Korean bound form's Korean sense has
drifted from or extended beyond its literal Chinese-character meaning. This is a useful, source-
native signal for any future work distinguishing borrowed/Sino-Korean vocabulary that behaves as a
transparent calque from vocabulary that has been reanalyzed/relexicalized within Korean itself.
