# Hungarian Slang Corpus — Magyar Szlengszótár, printed pages 180–269 (representative sample)

**Source:** *Magyar Szlengszótár* ("Hungarian Slang Dictionary"), a standalone Hungarian slang
dictionary. `source_reference/languages/Hungarian/Magyar Szlengszótár.pdf` — PDF pages 91–135 of
170 total, no text layer (vision-read; scanned with ACDSee, scan-metadata `CreationDate` 2015).
Publication year of the underlying book itself was not confirmed in this excerpt (no colophon/
title page in the assigned range) — see Attested Era note below. This fills the gap between
`01_szlengszotar_dictionary_pp90-179.md` (printed pp. 90–179) and `03_szlengszotar_dictionary_pp270-336.md`
(printed pp. 270–336) — **this file's landing completes full alphabet-range (A–Z) representative-sample
coverage of the entire dictionary's main alphabetized body** (pp. 1–336, aside from
`02_szlengszotar_kovecses_A-E_sample.md`'s earlier front-of-book sample).

**PDF-page-to-printed-page mapping.** Confirmed empirically by sibling chunks and reconfirmed here
by directly reading the printed page-number headers on every sampled image: `printed_page_left =
2×PDF_page − 2`, `printed_page_right = 2×PDF_page − 1`. PDF page 91 → printed pp. 180–181
(confirmed: page header reads "180 | literre" on the left leaf, "lötyögés | 181" on the right).
PDF page 135 → printed pp. 268–269 (confirmed: page header reads "268 | sziszegő"). **This file's
assigned PDF range 91–135 therefore covers printed pages 180–269 (90 printed pages)**, spanning
the dictionary's alphabetical range from **l- (literre/ló-)** through **sz- (sziszegő/szkárpi)** —
i.e., the letters l, m, n, ny, o, ó, ö, ő, p, r, s continuing into sz, matching up cleanly with
`01`'s endpoint at "link" (p.179) and `03`'s continuation of the sz– tail from p.270 onward.

## Coverage decision — representative sample, explicitly not exhaustive

**First inspected the format before committing to a strategy**, consistent with `01`'s and `03`'s
approach. Same dense 4-columns-per-spread format (2 columns per printed page, one PDF image = one
two-page spread), bracketed Hungarian-language gloss, optional register tag (`durva` "coarse,"
`tabu` "taboo/vulgar," `ironikus` "ironic"), numbered sense-lists for polysemous headwords, and
often a short italic example sentence. Rough count from the sampled spreads: **on the order of
70–100 distinct headwords per two-page spread** (denser than `01`'s estimate in places, e.g. the
`segg-`/`szar-` compound clusters run especially thick), which across 45 assigned PDF pages (90
printed pages) implies **several thousand entries total** in the full assigned range — far too many
for exhaustive transcription.

**Sampling strategy actually used — two-tier, matching `01`/`03`:**
1. **Spread-level sampling.** 9 spreads were selected at even intervals across the full 45-PDF-page
   range (PDF pages 91, 96, 102, 108, 114, 120, 126, 132, 135), chosen to track the alphabet
   progression from the range's start to its exact end rather than cluster anywhere. This yields
   coverage of headwords spanning **l- → m- → n- → ö- (letter-divider) → p- → s- (letter-divider)
   → sz-**, confirmed directly from the images (a decorative "Ö·Ő" letter-divider page appeared at
   printed p.226, and a decorative "S" letter-divider page appeared at printed p.250 — both
   confirmed real printed section markers, not marginalia).
2. **Within-spread selection.** Within each sampled spread, entries were selected rather than
   transcribed in full — prioritizing headwords that (a) illustrate a distinct slang-formation
   mechanism (metaphor, euphemism, simile-template, compounding, polysemy chains), (b) carry the
   source's own `durva`/`tabu` register tag, or (c) are otherwise semantically self-contained.
   Long numbered polysemy chains (e.g. "szar" with 9 numbered senses, "elszáll" with 3) were
   thinned to their most distinct/illustrative senses rather than fully enumerated. Both the left
   and right printed page of most sampled spreads were read (not just one side) because several
   spreads turned out to contain a single coherent formation-pattern cluster spanning both pages
   (the `mint` simile-template page 202–203, the `segg-` compound cluster page 250–251, the `szar-`
   cluster page 262–263) that would have been cut awkwardly by a one-side-only rule.

**Result: 118 entries** extracted from 9 spreads (18 printed pages, 6 of which were read on both
left+right sides) out of the 90 printed pages in the assigned range — roughly a 20% page sample,
itself only partially transcribed per spread. This is intentionally a *representative* sample of
this source's texture and slang-formation patterns, not a corpus-complete extraction, matching the
discipline of `01` and `03`.

## Vision-reading notes

All 9 sampled spreads were clean, uniformly typeset commercial-print scans — clear black-on-white
text, consistent font throughout. A previous owner's handling is visible only as page-corner
scuffing/binding-shadow at the image edges (gutter shadow, decorative endpaper doodles in the
photographed margin outside the printed page area) — no handwritten marginalia, underlining, or
reader annotation was found overlapping the printed dictionary text on any sampled page, so no
marginalia-guard exclusions were needed. Print was legible at 150dpi rendering (rendered slightly
higher-resolution than `01`'s 100dpi pass, then cropped to isolate each printed page from its
two-page-spread PDF image) on every sampled page; no faded or obscured regions were encountered.
Given this, **Vision Reading Confidence is `plausible_unverified` throughout** (read with high
confidence from clear print, but not independently cross-checked against a second source) rather
than `verified`. No entries required `low_confidence` flagging.

## Copyright discipline applied

Per spec, this file does **not** bulk-reproduce the dictionary's own illustrative example
sentences. Glosses below are paraphrased translations of the source's own bracketed Hungarian
definitions (not verbatim quotes of the definitions, and not the example sentences). A handful of
entries' `Notes` column mentions what kind of example the source gives without quoting it.

## Register-tag mapping

Following the mapping already established in `01`/`03` and
`../../datasets/Hungarian/established/009_szolasok_kozmondasok_part1.md`: source `durva` ("coarse")
and `tabu` ("taboo") tags → Usage Tier `taboo`. Untagged entries are Usage Tier `slang` (every
headword here is drawn from a slang-specific dictionary). `ironikus` ("ironic") is recorded in
Notes as a tone marker rather than a separate Usage Tier.

## Morphological typology note

Hungarian is agglutinative; as with `01`/`03`, most entries here are multi-word idiomatic verb
phrases and fixed expressions (e.g. `összehoz vkit vkivel`, `nem lehet levakarni vkit`), not
single agglutinated word-forms needing a morpheme-breakdown row. Some headwords are compact
derived forms with transparent structure (prefix/verb + suffix, e.g. `megbugyáz(ik)`,
`szívóskodik`) that don't need a breakdown to clarify. One structurally notable cluster this range
surfaces well: **the `meg-` perfective-prefix verb series** (pp.190–191) and the **`össze-`
"together" prefix-verb series** (pp.226–227) both show the same base-verb-plus-productive-prefix
pattern at high density — dozens of headwords in a row sharing the same bound prefix morpheme
attached to otherwise-ordinary verbs, several of which pick up a slang sense only in the prefixed
form (e.g. `megcuccol vkivel` "moves in with someone," from `cucc` "stuff/things" + `-ol` verbalizer
+ `meg-` perfective, not a generic sense of the bare root alone).

## Standout slang-formation patterns for Phase 3

- **Simile-template productivity (`mint` "like/as," p.202–203).** A single two-column page is
  almost entirely a run of `mint + NP` similes that all cash out to one of two meanings —
  intensifying "very much" (`mint a mák` "like poppy seed," `mint a kínaiak` "like the Chinese," =
  "a huge amount") or "fast/suddenly" (`mint a villám` "like lightning," `mint pók a falon` "like a
  spider on the wall"). This is a highly productive open-class template: the book lists at least 20
  distinct filler nouns/phrases for the same two semantic slots, several of them taboo-register
  (`mint pinán a szőr` lit. "like hair on a vagina," `mint szaron a légy` lit. "like flies on shit")
  functioning as crude intensifiers alongside tamer ones (`mint a villám`). Directly comparable to
  a slang-derivation type worth flagging for the conlang: **simile-slot productivity**, where a
  fixed syntactic frame accepts an open, register-graded list of fillers for the same core meaning.
- **Compound-cluster density around taboo body-part nouns (`segg-` "butt," p.250–251;
  `szar-` "shit," p.262–263).** Both nouns anchor dense runs of compounds/collocations (`seggbe
  rúg` "kick in the butt," `seggfej` "buttface"=idiot, `seggnyaló` "ass-licker"=flatterer,
  `seggrészeg` "butt-drunk"=very drunk; `szarrágó` "shit-chewer"=miser, `szarul érzi magát`
  "feels shitty"=very sick, `szarrá ver` "beats to shit"=beats badly). These read as **productive
  compounding hubs**: one taboo noun functions almost like a bound intensifier/pejorative
  morpheme once it enters compound position, generating dozens of derived senses spanning
  insults, physical states, and emphatic idioms — the same "hub noun as morphology-adjacent
  productivity engine" pattern worth testing in the derived conlang's own taboo vocabulary.
- **Numbered polysemy chains as a source-native productivity signal.** Headwords like `szar`
  (9 numbered senses: excrement → nothing → worthless thing → hated person → hard task → hard
  situation → annoying thing → grime → broken/malfunctioning) and `elszáll` (in `01`: ejaculates /
  high on drugs / device crashes) show the same base lexeme radiating across unrelated semantic
  domains via metaphor chains. The dictionary's own numbering convention is a ready-made map of
  which senses the source editors judged as one lexical item's productive extensions versus a
  separate homonym.
- **Letter-divider decorative pages confirm chapter/section structure**, not content — the "Ö·Ő"
  divider (p.[226 recto], between n- and p- material) and "S" divider (p.[250 recto], between r-
  and sz- material) are large centered-typography section markers with no headwords of their own,
  consistent with `03`'s note about this book's consistent internal navigation aids.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| literre van hitelesítve, vhány | "certified for X liters" — describes how much someone can drink and hold their liquor | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Measurement-unit metaphor for drinking capacity. |
| ló | 1) a foolish/stupid person 2) an inadequate grade (school) | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Lit. "horse" — animal-as-insult metaphor. |
| lóbaszó | 1) a man with a large penis 2) a physically large person | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Tagged tabu. Lit. "horse-f*cker." |
| lóbél/lóbelű | a gluttonous/big-eating person | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Lit. "horse-gut." |
| lócitrom | horse dung (lit. "horse lemon") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Euphemistic fruit metaphor for excrement. |
| lódít | lies | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. |
| lófasz a seggedbe! | a harsh rejection formula (abbreviated "LFS" = "elefes" in speech) | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Tagged tabu. Notable for having its own spoken-abbreviation slang form. |
| lófasz(t)! | rejection of a statement/request/suggestion | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Lit. "horse-penis" as an intensified "nothing/no way." |
| lóg | 1) skips work 2) skips school 3) rides without a ticket 4) is uncertain/questionable (of something) 5) is about to be hanged (by rope) | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Five numbered senses, all "hanging/dangling" as base image. |
| lóg egy deszkája | is mildly crazy/insane (lit. "one of his boards is hanging loose") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Loose-plank sanity metaphor. |
| lóg (együtt) vkivel | is courting/wooing someone | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. |
| lógós | work-shy, truant | adj/noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. |
| lóhúgy | bad/cheap beer (lit. "horse urine") | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Tagged durva. |
| lompos | a large penis | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. |
| lópikula | 1) a small amount of money 2) nothing at all | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Tagged durva. |
| lopott pina mindig jobb, a | "someone else's sexual partner always seems more attractive than one's own" | proverb-like idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.180. Tagged tabu. Grass-is-greener proverb pattern applied to a crude domain. |
| lordok háza | 1) a "everyone stands" dive bar 2) a homeless shelter | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Lit. "House of Lords" — ironic aristocratic-institution name for its opposite. |
| lószart! | rejection of speech, "unacceptable to the listener" | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Tagged durva. Lit. "horse-shit!" |
| lotyó | 1) a disliked/objectionable woman 2) a promiscuous woman/girl | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. |
| lovaglás | sex performed sitting astride a partner | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Lit. "horseback riding." |
| lovak közé csap | 1) accelerates a vehicle 2) starts some activity intensely, dives into something | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Lit. "whips among the horses." |
| lóvá tesz | deceives, cons | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Lit. "turns into a horse" — animal-transformation deception metaphor. |
| lóvé/lovetta | money | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Widely-known Hungarian slang term for money, related to Romani "love." |
| lóvés | rich, moneyed | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Derived from "lóvé" above. |
| lő | 1) has sex (of a man) 2) injects intravenous drugs into oneself | verb | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Lit. "shoots/fires" — violence-as-sex and violence-as-injection dual metaphor. |
| lőcs | 1) a large penis 2) a leg 3) a shapeless, thick leg | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. |
| lőcsgéza | an uncultured/uncouth person | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. |
| lőddle magad! | a call to stop talking (sense 1) or stop an activity (sense 2) | interjection | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Lit. "shoot yourself down!" — aggressive dismissal formula. |
| lök | 1) talks 2) plays billiards 3) has sex | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Three unrelated senses on one motion-verb base ("pushes/shoves"). |
| löket | 1) sexual intercourse 2) nonsense, foolishness 3) a drug dose to be injected 4) "let's have a drink!" | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Four numbered senses radiating from "a push/thrust." |
| lökhárító | a woman's breasts (lit. "bumper/fender") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Vehicle-part-as-body-part metaphor. |
| löki a (nagy/link/rabló/rossz/süket) dumát | 1) talks nonsense, rambles 2) talks emptily, chatters | idiom (templatic) | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. Source itself gives a bracketed adjective slot (nagy/link/rabló/rossz/süket = big/shady/thieving/bad/deaf) plus a noun-object slot (dumát/púdert/rizsát/sódert/stószt/szöveget/vakert, all near-synonyms for "empty talk") — a two-slot templatic idiom, notable as an explicit open-slot construction the source itself documents. |
| lökött | 1) mildly crazy 2) stupid 3) odd, eccentric | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. |
| lőre | poor-quality wine | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. |
| lötyögés | dance/dancing (informal) | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.181. |
| még a vécéajtó(t) is | "even more than is decent/expected" (of someone excessively acquisitive) | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.190. Lit. "even the bathroom door too" — hyperbolic-greed idiom. |
| megáll az ész(, és visszafordul)! | expression of surprise ("mind = blown") | interjection | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.190. Lit. "the mind stops (and turns back)!" |
| megáll benne a húgy/trágya | 1) gets scared 2) is very surprised/shocked | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.190. Tagged durva. Bodily-fluid-freezing fear metaphor. |
| megbaszhatod a vmidet! | "you won't get far with that!" (dismissive) | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.190. |
| megbaszik vkit | 1) has sex with someone 2) punishes someone 3) fails/flunks someone | verb phrase | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.190. Three numbered senses; tagged tabu; source gives a dialogue example about exam results. |
| megbaszná a legyet is röptében | describes an extremely sexually eager man (lit. "would f*ck even a fly in flight") | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.190. Tagged tabu. Hyperbolic indiscriminate-lust idiom. |
| megbikáz | 1) jump-starts a car with another battery 2) strikes the ball hard (sports) | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.190. Lit. root relates to "bika" (bull) — virility/force metaphor extended to mechanical and sporting force. |
| megbuggyan | goes crazy, loses it | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.190. |
| megbukik | 1) gets caught by police 2) is exposed as two-faced 3) goes bankrupt 4) fails, doesn't succeed | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.190. Four numbered senses on one "fails/falls" base verb. |
| megcuccol vkivel | moves in with someone (cohabits) | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.191. From "cucc" (stuff/belongings) + verbalizer + perfective "meg-" prefix — moving one's stuff in as metonymy for cohabiting. |
| megcsíp | 1) catches/apprehends someone 2) acquires something (good find) | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.191. Source gives an example about finding a good used-market deal. |
| megdöglik vkiért/vmiért | is infatuated with, is really into someone/something | verb phrase | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.191. Tagged durva. Lit. "dies for" — mortality-as-intense-affection. |
| megdumálja a fejét | deceives/sweet-talks someone into something | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.191. |
| még egy ilyen humor, s fejeden a dudor/még egy ilyen húzás, s fejeden a zúzás! | a rhyming threat of violence | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.191. Two rhyming variants given as one entry; "humor/dudor" (humor/bump) and "húzás/zúzás" (move/bruise) rhyme pairs — verse-like threat formula. |
| megél a saját hátán is | describes a self-sufficient prostitute (lit. "makes a living on her own back too") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.191. |
| megeszem a kalapomat, ha... | expression of certainty ("I'll eat my hat if...") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.191. Direct structural parallel to the English idiom "I'll eat my hat." |
| mint a huzat! | 1) emphatic agreement 2) emphasizes speed | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Lit. "like a draft (of air)!" Part of the productive "mint X" simile-template cluster (see Standout patterns note). |
| mint akit seggbe lőtt az ármány/seggbe lőttek | emphasizes speed | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Tagged durva. Simile-template cluster. |
| mint a mák | very many/a lot | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Lit. "like poppy seed." Simile-template cluster. |
| mint a rosseb | emphasizes "very" | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Tagged durva. Simile-template cluster. |
| mint a töketlen kutya | describes frantic, erratic running/movement | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Lit. "like a castrated dog." Tagged durva. Source gives an example about someone running around frantically. |
| mint a villám | emphasizes speed | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Lit. "like lightning." The tamest/most transparent member of the simile-template cluster. |
| mint fing a gatyában/gólyafos a levegőben | describes erratic, back-and-forth, intense movement | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Tagged durva. Two crude variant images given as one entry. |
| mint pinán a szőr | very many/a lot | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Tagged durva. Simile-template cluster, crude-register filler. |
| mint pók a falon | describes erratic, intense, back-and-forth movement | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Lit. "like a spider on the wall." Source gives an example about someone running around frantically. |
| mint szaron a légy | very many/a lot | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Lit. "like flies on shit." Tagged durva. Simile-template cluster, crude-register filler. |
| mint zöldbab a konzervben | very many/a lot (crowded) | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.202. Lit. "like green beans in a can." Source gives an example about a crowded train. |
| mit bámulsz(, egyet fingok, elájulsz)? | aggressive challenge to someone staring | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.203. Tagged durva; rhyming threat-formula, similar structure to the "humor/dudor" rhyme on p.191. |
| mit nézőL? Nem vagy te intéző! | rebuke to someone staring, "mind your own business" | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.203. Rhyming rebuke ("néző"/"intéző"). |
| móka | 1) a swindle 2) a crime 3) a boring thing 4) an event/activity 5) a joke | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.203. Five numbered senses on the same base noun (standard Hungarian "móka" = fun/joke), showing considerable semantic drift into crime/tedium senses beyond the neutral root. |
| mocsárjáró | high-heeled/high-platform women's shoes | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.203. Lit. "swamp-walker" — functional-metaphor naming from the shoe's exaggerated height. |
| nem lehet levakarni vkit | describes someone who won't stop clinging/imposing on another person | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.214. Lit. "can't be scraped off." |
| nem mai csirke | an aging woman | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.214. Lit. "not today's chicken." |
| nem piskóta | 1) a criminal/gangster 2) (as praise) impressive, tough 3) not an easy task | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.214. Lit. "not sponge cake" — three numbered senses via "not a soft/easy thing." |
| nem rúg labdába | 1) doesn't affect someone/something 2) has no chance | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.214. Lit. "doesn't kick the ball" — sports-derived idiom for irrelevance/futility. |
| nem szívbajos | brave, reckless | adj | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.214. Lit. "not heart-diseased." |
| nem tetszik a pofám? | a challenge to a fight | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.215. Tagged durva. Lit. "you don't like my face?" |
| nem venni észre a farkát/pöcsét | describes someone very conceited/cocky (lit. "can't notice one's own [penis]") | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.215. Tagged durva. |
| nem vagy átlátszó! | rebuke expressing indignation at not being able to see past/around someone | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.215. Lit. "you're not transparent!" |
| nepper | 1) someone engaged in black-market dealing 2) a fence (receiver of stolen goods) 3) a tout drumming up buyers 4) a drug dealer | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.215. Four numbered senses, all shady-transaction roles. |
| népi rágógumi | television (lit. "the people's chewing gum") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.215. Mass-media-as-addictive-mindless-substance metaphor. |
| ne szólj bele, nem telefon! | rebuke to someone interrupting/interjecting | interjection | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.215. Lit. "don't speak into it, it's not a telephone!" — wordplay on "belesz(ó)l" (interrupt) vs. speaking into a phone. |
| öcsémfacsiga! | expression of frustration/bad luck | interjection | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.226 area ("Ö·Ő" letter-divider spread). Lit. roughly "little-brother-pretzel!" — nonsense-compound exclamation. |
| ő a Jani! | a disapproving comment about someone acting conceited/showy | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.226 area. Uses a common given name ("Jani" = Johnny) as a stock type for a braggart. |
| ökör | 1) a stupid person 2) an unlikeable person | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.226 area. Tagged durva. Lit. "ox." |
| örül, hogy luk van a seggén | describes someone easily satisfied with little (lit. "glad there's a hole in his butt") | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.227. Tagged durva. |
| őrültekháza | a place of great chaos/disorder (lit. "madhouse") | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.227. |
| öreg | 1) father 2) an ironic/angry or condescending address term (younger man) 3) same, for an older man 4) a discharged/veteran soldier | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.226 area. Lit. "old" — polysemous kinship/address term, four numbered senses. |
| összebarmol | botches, does poorly/carelessly | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.227. Part of the productive "össze-" ("together") prefix-verb series — see Morphological typology note. |
| összeboronál vkit vkivel | introduces/sets up a man and a woman | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.227. "össze-" series. |
| összecsókolózik vkivel | crashes into someone/something with a vehicle (lit. "kisses with") | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.227. "össze-" series; ironic euphemism turning a tender verb into a collision idiom. |
| összecsukja az autót | causes serious damage to one's own car in a crash | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.227. Lit. "folds up the car" — near-synonym pair with "összehajtogatja a kocsit" below. |
| összefossa magát | gets scared | verb phrase | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.227. Tagged durva. |
| összehajtogatja a kocsit | causes serious damage to one's own car in a crash | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.227. Lit. "folds the car up" — near-synonym of "összecsukja az autót." |
| pörget vkivel | courts/woos someone | verb phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.238 area. Lit. "spins with." |
| pörög | 1) is in a good mood, active 2) behaves restlessly/agitatedly under drug influence 3) dances 4) is in a sexual relationship with someone 5) is drunk | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.239. Lit. "spins/whirls" — five numbered senses radiating from a spinning-motion base. |
| potyázik | 1) enjoys freeloading, obtains things free 2) borrows/asks for things 3) begs 4) gropes for sexual purposes 5) uses a service for free 6) rides public transit without paying 7) benefits from a goalkeeper's/defense's mistake (sports) | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.238. Seven numbered senses — an unusually long polysemy chain on a "freeloading" base. |
| prosztinger/prosztó | an uncultured/uncouth person | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.239. Two variant forms of one entry. |
| puding | 1) a soft/spoiled, effeminate man or boy 2) a coward | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.239. Lit. "pudding" — texture-as-character metaphor (softness = weakness). |
| segg | 1) buttocks 2) vagina 3) a stupid/unlikeable person | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.251. Tagged durva. Hub noun anchoring the dense "segg-" compound cluster (see Standout patterns note). |
| seggbe rúglak! | a threat of violence | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.251. Tagged durva. |
| segged ne nyaljam ki?, a | sarcastic rebuke to someone with excessive/unreasonable demands or expectations | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.251. Tagged tabu, tagged ironikus by source (irony noted as its own tone marker per the register-tag mapping). |
| segget csinál a szájából | fails to keep a promise (lit. "makes his mouth into a butt") | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.251. Tagged durva. |
| seggfej | 1) a stupid person 2) an unlikeable person | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.251. Tagged durva. "segg-" cluster. Source gives an example calling a specific person this insult. |
| seggig ér a homloka/seggkopasz | bald | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.251. Tagged durva. "segg-" cluster; hyperbolic "forehead reaches to the butt" image for baldness. |
| seggnyaló | a flatterer, sycophant | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.251. Tagged durva. "segg-" cluster; direct structural/semantic parallel to English "ass-kisser." |
| seggpicsa részeg (lesz) | becomes extremely drunk | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.251. Tagged tabu. "segg-" cluster; compound intensifier stacking two taboo body-part nouns before "drunk." |
| sejhajon billentelek! | a threat of violence (kicking in the buttocks) | interjection | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.251. |
| szar | (9 numbered senses) 1) excrement 2) nothing 3) a bad/worthless/shoddy thing 4) a disliked/hated person 5) a hard/unpleasant task 6) a hard/unpleasant situation 7) an annoying/irritating thing 8) grime/muck 9) broken/malfunctioning | noun/adj | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.262. Tagged durva. Hub noun anchoring the "szar-" cluster — the longest numbered polysemy chain observed in this sample (see Standout patterns note). |
| szarba lép/nyúl | becomes wealthy, has good luck | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.262. Tagged durva. Ironic reversal — "stepping in shit" as good luck, inverting the literal image (folk-superstition inversion, cf. English "stepping in it" for the opposite sense — worth flagging as a case where Hungarian and English similes on the same referent invert polarity). |
| szarér(t)-húgyér(t) | 1) for nothing, for free (labor exploited) 2) very cheaply | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.262. Tagged durva. Lit. "for shit, for piss" — rhyming vulgar minimizer pair. |
| szarrágó | a stingy/miserly person | noun | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.263. Tagged durva. Lit. "shit-chewer." "szar-" cluster. |
| szarul érzi magát | is very sick/unwell | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.263. Tagged durva. Adverbial derivative of "szar," "szar-" cluster. |
| szarrá ver | 1) beats severely 2) defeats decisively, outclasses | verb phrase | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.263. Tagged durva. Lit. "beats into shit" — "szar-" cluster, translative-case intensifier construction (X-rá ver = "beats [someone] into [state] X"). |
| szart nem/nincs!, a | a furious rejection of a demand/request, "you'll get nothing" | interjection | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.263. Tagged durva. Source gives a dialogue example about a debt request being refused. |
| szárazpipás | someone who abstains from alcohol | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.262. |
| szár(az) baszás | necking/making out fully clothed, without actual intercourse | idiom | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.262. Tagged tabu. Lit. "dry f*cking." |
| sziszegő szappan | deodorant (lit. "hissing soap") | idiom | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.268. Function-by-sound-effect metaphor (referencing spray/aerosol hiss). |
| szittyózik | 1) drinks alcohol regularly/habitually 2) drinks heavily on one occasion | verb | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.268. |
| szív | 1) drinks alcohol regularly/habitually 2) snorts cocaine 3) inhales glue/solvent 4) performs oral sex on a man 5) has bad luck, gets into trouble | verb | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.268. Lit. "sucks/inhales" — five numbered senses spanning drinking/drugs/sex/misfortune on one intake-motion base verb, directly parallel in structure to "elszáll" (p.91, file 01) and "lő"/"lök" above. |
| szivarozik | performs oral sex on a man | verb | taboo | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.268. Derived from "szivar" (cigar) — shape-based phallic-object euphemism. |
| szívdöglesztő hapsi | a man who is (sexually) very attractive | noun phrase | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.268. Lit. "heart-killing guy." |
| szívódj fel! | 1) "go away!" (dismissal) 2) rejection of someone/something 3) "stop that!" | interjection | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.268. Lit. "absorb/dissolve yourself!" |
| szkanderezés | arm wrestling (lit. describes the competition where one arm-wrestler tries to pin the other's arm down) | noun | slang | — | contemporary (source scanned 2015) | — | — | dictionary | n/a | plausible_unverified | p.268. Loanword adaptation (from English "(arm-)scander/scander" via a borrowed sporting term), morphologically integrated with the standard -ezés verbal-noun suffix. |
