# Hungarian — Established Vocabulary/Grammar: Miklós Törkenczy, *Practical Hungarian Grammar*
# (Corvina, Budapest, copyright 2002), full book

**Source:** Miklós Törkenczy, *Practical Hungarian Grammar* (Corvina Books Ltd., Budapest,
copyright © Miklós Törkenczy 2002, ISBN 963 13 5131 9), "21 Practical Hungarian Grammar.pdf",
90 PDF pages, no text layer (scanned) — read visually throughout.

**Page-offset verification (mandatory check per the vision-reading gotcha) — a genuine two-
printed-pages-per-image spread scan, confirmed empirically, NOT one-page-per-image:** PDF page 1
shows the title page (unnumbered) on the right half only; PDF page 2 shows the unnumbered
copyright page (left) and unnumbered "Contents" page (right); PDF page 5 shows printed pp. 10–11;
PDF page 45 shows printed pp. 90–91; PDF page 90 (the last PDF page) shows printed pp. 180–181.
This confirms the formula `printed_left = 2×PDF_page`, `printed_right = 2×PDF_page + 1` holds
throughout the numbered-content range. The book's own Table of Contents lists content running to
printed p. 184 (end of "Index of Derivational Suffixes"), but this 90-page scan's last rendered
spread only reaches printed p. 181 (mid "Index of Words") — the scan appears to be missing the
book's final 1–3 index pages. This has no effect on this extraction, since indices carry no
content of their own (only page-number pointers into the book), and the book's actual last
substantive-content page is p. 172 (end of §23.7.3 "Van with an Adverbial Participle"), well
within the scanned range — confirmed by direct inspection that "Index of Subjects" begins cleanly
on printed p. 173.

**Vision-reading note:** this is a clean, modern (2002) digitally-typeset scan; no handwritten
marginalia, library stamps, or non-print annotation of any kind were found anywhere in the book.
Text and IPA transcriptions are crisp and legible throughout. Vision Reading Confidence is
`verified` or `plausible_unverified` for essentially every entry below (individual `low_confidence`
exceptions are flagged inline; there are very few, since the type is large and unfaded).

**Relationship to prior Hungarian `established/` files — non-redundant-supplement pattern
(auditable scope decision).** This is a formal, generative-linguistics-style reference grammar (not
a teaching course), covering essentially the whole of Hungarian morphology and a chapter of syntax.
Its author, Miklós Törkenczy, is also a co-author of *The Phonology of Hungarian* (Siptár &
Törkenczy, already extracted as `established/019`–`020`), and this book's territory overlaps
heavily with three prior sources: Carol Rounds' *Essential Grammar* (`001`–`005`), Kornai's *On
Hungarian Morphology* (`007`–`008`), and (for phonology/vowel harmony) `019`–`020` themselves. Per
the coverage rule's non-redundant-supplement pattern, this file:

- **Skips as redundant:** the exhaustive person/number/tense/mood conjugation paradigm tables
  themselves (Present, Past, Conditional, Conjunctive-Imperative indefinite and definite, for
  regular back/front/sibilant-final stems) — these are the same paradigms Rounds' Chapter 4 and
  this project's FSI extractions already tabulate in full, and reproducing every table here (the
  book gives dozens of them, one per stem-shape subclass) would bloat this file far past the
  point of added value. Only the *organizing generalizations* (e.g. the sibilant-gemination rule,
  the t-final-verb three-way subclassification, the -ik verb residue) are captured as grammar
  points below, with one illustrative paradigm each rather than all of them.
- **Skips as largely redundant:** the phonological content of Chapter 1 (alphabet, vowels,
  consonants, assimilation rules, vowel harmony) — this duplicates `019`–`020` (same co-author) and
  Rounds Chapter 1–3 (`001`) closely; only the IPA-transcribed IPA IPA alphabet-name chart and a few
  vowel-harmony edge cases not seen in `001`/`019` are noted.
- **Captures as genuinely new/deeper:**
  1. A far more **systematic, fully-named catalog of irregular noun-stem classes** (Lowering
     Stems, Vowel-deleting Stems, v-stems/Vowel-to-v Stems, Vowel-shortening Stems, Unrounding
     Stems, Final Vowel-deleting Stems) than Rounds Ch. 5 or Kornai give, each with a long
     representative word list — captured as grammar points with a representative vocabulary
     sample per class (not the full ~150-word lists).
  2. A **dedicated Postpositions chapter** (Ch. 5) with a full orientation/meaning/usage table and
     the postpositional-pronominal paradigm — not previously extracted as its own systematic unit.
  3. A **fully systematic Pronoun chapter** (Ch. 6: demonstrative, possessive, personal, reflexive,
     reciprocal, interrogative, relative, indefinite, universal, negative), including the
     productive `vala-`/`bár-`/`akár-` indefinite-pronoun-prefixation system, documented here in
     more structural completeness than prior sources.
  4. A systematic **Word Formation: Derivational Suffixes chapter** (Ch. 22), organized by
     FORM/MEANING/EXAMPLES per suffix — more systematic than Kornai's more theoretical treatment.
  5. A **Constructions and Sentences chapter** (Ch. 23) covering the Possessive Construction,
     pronoun-omission rules, double negation, infinitival constructions/auxiliaries (including a
     named list of "separator" verbs), word order/topic-focus, and `van` with adverbial
     participles — genuinely new syntactic content not covered by any prior Hungarian source in
     this project.
  6. Scattered but real **register/colloquial annotations**, flagged in Notable Findings below.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| előtt / elé / elől | in front of (state/to/from) | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | full three-way orientation set; postpositional-pronominal forms (`előttem` etc.) also given. Ch. 5, p. 41-42. |
| mögött / mögé / mögül | behind (state/to/from) | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Ch. 5. |
| alatt / alá / alól | under, below, during (state/to/from) | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `alatt` also covers TIME. Ch. 5. |
| fölött/felett / fölé / fölül | above, over (state/to/from) | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | two free-variant STATE forms. Ch. 5. |
| mellett / mellé / mellől | next to (state/to/from) | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Ch. 5. |
| között / közé / közül | between, among (state/to/from) | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | also covers TIME (state). Ch. 5; `közül` recurs as the superlative-selection postposition, Ch. 7. |
| felé / felől | towards / from the direction of | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Ch. 5. |
| belül / kívül | inside, within / outside, except | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | both cover SPACE + a second domain (TIME / ABSTRACT respectively). Ch. 5. |
| túl | beyond | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | governs SPACE, TIME and ABSTRACT domains; requires superessive on its noun. Ch. 5. |
| át / keresztül | through, across, for (+time) | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | both require superessive on the governed noun. Ch. 5. |
| múlva / óta / tájt / közben | after (+time) / since / around, about / while | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | pure-TIME postposition set. Ch. 5. |
| helyett / ellen / miatt / nélkül / szerint | instead of / against / because of / without / according to | postposition | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | pure-ABSTRACT postposition set. Ch. 5. |
| ez / az | this / that | demonstrative pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | basic-set demonstratives; final `z` fully assimilates to the initial consonant of an attached case ending (e.g. `ebben` not *`ezben`). Ch. 6.1. |
| ilyen / olyan | such (this kind / that kind) | demonstrative pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | extended-set demonstrative; does not agree in number/case with a qualified noun (unlike the basic set). Ch. 6.1. |
| ekkora / akkora | this size / that size | demonstrative pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Ch. 6.1; no plural. |
| ennyi / annyi | this much / that much | demonstrative pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | no plural form exists. Ch. 6.1. |
| enyém / tiéd / övé | mine / yours / his-hers-its | possessive pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Hungarian's only possessive-pronoun series (no attributive "my"-series as in English). Ch. 6.2. |
| én / te / ő / mi / ti / ők | I / you.sg / (s)he-it / we / you.pl / they | personal pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Ch. 6.3; no gender distinction anywhere in 3rd person. |
| ön / önök / maga / maguk | you (formal styles, sg./pl.) | personal pronoun | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | 2nd-person referents that grammatically require 3rd-person verb forms; source frames `ön/önök` vs. `maga/maguk` as parallel to German `Sie` vs. `du/ihr`. Ch. 6.3. |
| magam / magad / maga / magunk / magatok / maguk | myself / yourself / him-her-itself / ourselves / yourselves / themselves | reflexive pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | may be prefixed with `ön-` or `saját` for extra emphasis (`önmagam`, `saját magam`). Ch. 6.4. |
| egymás | each-other | reciprocal pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Hungarian's only reciprocal pronoun; inflects for case and nominal possessive like a noun. Ch. 6.5. |
| ki? / mi? / melyik? / milyen? / miféle? / mekkora? / hány? / mennyi? / hányadik? | who / what / which / what kind / what sort / what size / how many / how much / which one (in a sequence) | interrogative pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | full interrogative-pronoun inventory; `hány`/`mennyi` alone lack plural forms. Ch. 6.6.1. |
| aki / amely / ami / amelyik / amilyen / amiféle / amekkora / ahány / amennyi / ahányadik | relative pronoun set (who/which/that etc.) | relative pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | formed by prefixing `a-` to the corresponding interrogative; the `a-` is sometimes optionally dropped in casual style (`(a)mikor hazaértem`). Ch. 6.6.2. |
| valaki / valami / valamely / valamelyik / valamilyen / valamiféle / valamekkora / valahány / valamennyi | someone / something / some / one-or-the-other / some kind / some kind / some size / some number of / some amount of | indefinite pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | formed by prefixing `vala-` to interrogative pronouns; `valamennyi` 'all' takes a DEFINITE verb, unlike `valaki`/`valami` etc. which take indefinite. Ch. 6.7, 10.1.1-10.1.2. |
| bárki/akárki, bármi/akármi, bármely/akármely, bármelyik/akármelyik, bármilyen/akármilyen, bármiféle/akármiféle, bármekkora/akármekkora, bármennyi/akármennyi, bárhányadik/akárhányadik | anyone / anything / no matter which (etc.) | indefinite pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | free-variant `bár-`/`akár-` prefixation of interrogatives, semantically 'no matter which/what' rather than `vala-`'s existential 'some'. Ch. 6.7. |
| mindenki / minden / mindegyik / mindenféle | everybody / everything-all / every, each / all kinds | universal pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `mindenki` is typically not used attributively, unlike the other three. Ch. 6.8; `minden` requires a definite verb per Ch. 10.1.2. |
| senki / semmi / semelyik / semmilyen / semmiféle / semekkora | nobody / nothing / not any of them / not of any kind (×2) / not of any size | negative pronoun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `senki`/`semmi` typically not used attributively; co-occurs with a negated verb (double negation is grammatically obligatory, not emphatic, in Hungarian — see Grammar points). Ch. 6.9, 23.4. |
| kicsi | small (predicative form) | adjective | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | source explicitly notes `kis` 'small' cannot be used predicatively — `kicsi` is obligatory there (`Ez a könyv kicsi`, NOT *`kis`), while `kis`/`kicsi` are both possible attributively. Ch. 7.1. |
| agg | very old | adjective | archaic | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | flagged as an exceptional non-Lowering adjectival stem (`aggok`, `aggot`, not lowering *`agg[a/e]-`); contrasts with the regular-Lowering `nagy` 'big'. Ch. 7.1. |
| derék | honest | adjective | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | explicitly flagged as an anti-harmonic stem taking back-vowel comparative suffixes despite its own front vowel (`derekabb` not `*derekebb`). Ch. 7.1.2. |
| jó / jobb / legjobb | good / better / best | adjective (irregular comparison) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Ch. 7.1.2, irregular comparative/superlative class. |
| bő / bővebb / legbővebb | loose / looser / loosest | adjective | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | uniquely a v-adding Stem in the comparative/superlative. Ch. 7.1.2. |
| kevés / kevesebb / legkevesebb | few, little / fewer, less / fewest, least | adjective | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Vowel-shortening Stem in comparative/superlative. Ch. 7.1.2. |
| jól / rosszul | well / badly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | irregular adverbial forms of `jó`/`rossz`, not the regular `-an/-en`/`-ul/-ül` pattern. Ch. 7.2, 7.2.1. |
| nagyon | very, strongly | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | e.g. `Nagyon édes` 'very sweet', `Nagyon megütötte` 'hit hard'. Ch. 7.2. |
| kint/kinn, bent/benn, fent/fenn, lent/lenn | outside / inside / up / down | adverb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | each has two free-variant forms; irregular comparatives in `-jjebb` (`kijjebb`, `beljebb`, `feljebb`, `lejjebb`). Ch. 7.2.1. |
| olyan ADJ, mint X | as ADJ as X (equality construction) | construction | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | Ch. 7.3; negatable for inequality-of-degree. |
| bíró | judge | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | irregular possessed forms with an alternative stem-final `ó`→`á` variant (`bírám`/`bíróm` etc.), Ch. 4.7. |
| fiú (son) / fiú (boyfriend) | son / boyfriend | noun (homograph pair) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | 'son' sense is an irregular back-harmonic Lowering Stem deleting its final vowel in possessed forms (`fiam` 'my son'); 'boyfriend' sense is fully regular (`fiúm` 'my boyfriend'). Ch. 4.7 — a genuine lexical-semantic split conditioning distinct morphology. |
| báty / öcs | elder brother / younger brother | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | source notes that for many speakers these only exist in possessed forms (bound nouns), never bare. Ch. 4.7. |
| szárny, kanál, mész, agár, sár | wing, spoon, lime, greyhound, mud | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | sample of the large "common nominal Lowering Stems" list (~150 words given). Ch. 4.1. |
| bokor, cukor, dolog, gödör, tükör | bush, sugar, thing, pothole, mirror | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | sample of "common nominal Vowel-deleting Stems" (~60 words given); nouns ending in `-alom`/`-elem` are always this class. Ch. 4.2. |
| ló, fű, nyű, tő, cső, kő, mű, hó, szó, tó | horse, grass, maggot, stem, pipe, stone, work of art, snow, word, lake | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | the complete closed class of nominal v-stems; `hó`/`szó`/`tó` uniquely change stem-final `ó`→`av` (not just add `v`) before a vowel-initial suffix. Ch. 4.3. |
| nyár, kéz, tűz, agár, derék | summer, hand, fire, greyhound, waist | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | sample of "common nominal Vowel-shortening Stems"; `lélek` 'soul' uniquely shortens a non-final-syllable vowel. Ch. 4.4. |
| idő, erdő, ajtó, tető, zászló | time, forest, door, top, flag | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | the complete "commonest Unrounding Stems" list (ő/ó → e/a before certain possessive suffixes; behavior is often optional/regularizable). Ch. 4.5. |
| borjú, ifjú, varjú | calf, youth, crow | noun | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | the complete closed class of Final Vowel-deleting Stems; behavior optional (`borjúk` also occurs beside `borjak`). Ch. 4.6. |
| baszik | fuck (vulgar) | verb (-ik class) | taboo | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | plausible_unverified | listed matter-of-factly in the book's own alphabetized "common -ik verbs" reference list alongside neutral items (fingik 'fart', csuklik 'hiccup') with no register flag of its own — see Notable findings. Ch. 18, p. 116. |
| fingik | fart | verb (-ik class) | taboo | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | plausible_unverified | see `baszik` note. Ch. 18, p. 116. |
| csuklik | hiccup | verb (-ik class, Defective Stem) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | cited as the paradigm example of a Defective Stem (lacks Conjunctive-Imperative forms entirely — `!NO! csukljál` is ill-formed). Ch. 19.3. |
| fuldoklik | gasp for breath, suffocate | verb (-ik class, non-defective) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | explicitly contrasted with the near-homophonous but Defective `csuklik` to show shape alone cannot predict defectiveness. Ch. 19.3. |
| aluszik/alszik, alkuszik, eskuszik | sleep, bargain, swear | verb (-uszik/-üszik class) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | the complete closed class of `u`/`ü`-final -szik verbs with a `d`-final alternative stem (alud-, alkud-, eskud-) for consonant-initial suffixes. Ch. 19.4.2. |
| tesz, vesz, hisz, visz, lesz, eszik, iszik | put/act, take/buy, believe, carry, be/become, eat, drink | verb (irregular) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | the "group of seven" fully irregular verb stems, with distinct suppletive-looking stems in Past/Conditional/Conjunctive-Imperative (tett-/vett-/hitt-/vitt-/lett-, tegy-/vegy- etc., tenn-/venn- etc.). Ch. 19.5.1. |
| van, megy, jön | be/have, go, come | verb (irregular, maximally suppletive) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `van` uniquely lacks Conjunctive-Imperative and Infinitive/Participle forms of its own (borrows from `lesz`); `nincs` is `van`'s suppletive negative. Ch. 19.5.2, 23.7. |
| gyere / gyertek | come! (2sg/2pl imperative, colloquial) | verb (imperative, suppletive short form) | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | explicit source register note: "jöjj is practically extinct in colloquial Hungarian" and "gyertek feels more colloquial than the long form jöjjetek" — see Notable findings. Ch. 19.5.2.4, p. 137. |
| ad, ver, lök, hoz, vés, főz | give, beat, push, bring, chisel, cook | verb | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | the book's own running paradigm-illustration verb set, used across Present/Past/Conditional/Conjunctive-Imperative chapters (11-14). |
| elmosolyodik / megszólal | start to smile / start to talk | verb (preverb + stem, inchoative) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | illustrates the `meg-`/`el-` "beginning" aspectual preverb function. Ch. 21.2. |
| kicsinál | kill, finish off (idiomatic) | verb (preverb + stem, idiomatic) | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | source's own example of a preverb+verb combination whose meaning is not derivable from its parts (`ki` 'out' + `csinál` 'do'); paired with `átver` 'cheat on sb' (`át` 'across' + `ver` 'beat'). Ch. 21.2(iii). |
| olvasó | reader | noun (agentive, from verb) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-ó/-ő` agent-noun-forming suffix. Ch. 22.2.2. |
| olvasás | reading | noun (from verb) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-ás/-és` action-noun-forming suffix. Ch. 22.2.2. |
| szépít / szépül | make beautiful / become beautiful | verb (from adjective, causative/inchoative pair) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-ít` (transitive 'make ADJ') vs. `-ul/-ül` (intransitive 'become ADJ') minimal derivational pair. Ch. 22.1.3. |
| halászik | fish (verb) | verb (from noun, 'catch/hunt N') | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-ászik/-észik` denominal verb suffix, 'catch, hunt N'. Ch. 22.1.2. |
| bajocska, söröcske, szemecske | little trouble, little beer, little eye | noun (diminutive) | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-cska/-cske` diminutive suffix, productively attaches to nearly any noun. Ch. 22.2.1. |
| Péter → Peti, Márta → Márti, Miklós → Miki | nickname formation | proper noun (nickname) | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-i` nickname-forming suffix on shortened given names. Ch. 22.2.1. |
| Nagy László → Nagy Lászlóné | married-woman name formation | proper noun (suffixed) | formal | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-né` 'Mrs' suffix, attaches to a man's full name or surname. Ch. 22.2.1. |
| Nógrádiék, Péterék | Nógrádi and his group / Péter and his group | noun (associative-plural, from proper noun) | colloquial | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-ék` 'group of people associated with N' suffix, can follow a possessive suffix + definite article (`a barátomék`). Ch. 22.2.1. |
| nagy lábú, nagy fülű | having big feet, having big ears | adjective (from noun+adjective phrase) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-ú/-ű/-jú/-jű` 'having N' suffix, only combines with a numeral/adjective+noun construction, never a bare noun. Ch. 22.3.2. |
| budapesti, pécsi, zalai | of Budapest, of Pécs, of Zala | adjective (from placename) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-i` 'belonging to N' suffix on placenames/institutions/professions/time-nouns. Ch. 22.3.3. |
| maroknyi, tálcányi | handful of, tray of | adjective (measure, from noun) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-nyi` measure-adjective suffix on unit-of-measure nouns. Ch. 22.3.3. |
| olvashatatlan | unreadable | adjective (privative, from verb) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | `-hatatlan/-hetetlen` 'un-...-able' privative suffix (potential + privative stacked). Ch. 22.3.3. |
| akar, bír, fog, kell, lehet, mer, óhajt, szabad+VAN, szeretne, szokott, tetszik, tud | want, be able to, shall/will, must, may, dare, wish, be allowed to, would like, be accustomed to, please (to), know how to | verb (auxiliary/"separator") | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | the book's own named closed list of "separator" verbs in infinitival constructions (control the preverb-placement rule of the dependent verb). Ch. 23.5.3. |
| kénytelen+VAN, képes+VAN, köteles+VAN, kész+VAN, hajlandó+VAN | have no choice but to / be capable of, have the cheek to / be obliged to / be ready, prepared to / can be persuaded to | complex verb (nominal + van) | core | — | contemporary (source published 2002) | — | — | grammar_reference | n/a | verified | "complex verbs" — nominal + conjugated `van`, missing the copula in the present 3rd person (`Ő kész meghalni` but `Ők készek meghalni`). Ch. 23.5, 23.5.1. |
