# Russian — Established Grammar/Vocabulary: A Comprehensive Russian Grammar, Part 1 (pp. 1–320)

**Source:** Terence Wade, *A Comprehensive Russian Grammar*, 3rd Edition (revised and updated by
David Gillespie), Wiley-Blackwell, 2011 (1st ed. 1992, 2nd ed. 2000). Covers PDF pages 1–320 of
`source_reference/languages/Russian/Russian Grammar books/A Comprehensive Russian Grammar.pdf`
— front matter, Preface(s), Acknowledgements, Abbreviations, the "Introduction" chapter (Cyrillic
alphabet, IPA, Pronunciation, Orthography, Word Division, Punctuation), and the grammar chapters
**The Noun** (word formation, gender, declension, case usage, diminutives/augmentatives), **The
Pronoun**, **The Adjective** (long form, short form, comparative, superlative), **The Numeral**
(cardinal, collective, indefinite, ordinal, special functions), and the opening of **The Verb**
(conjugation §§212–234, and Aspect §§235–254, cut off mid-list of perfective-prefix meanings at
the exact page-320 boundary — the PDF page range assigned to this subagent). A second subagent
covers PDF pages 321–632 (remainder of Aspect through the end of the book) in a separate file; do
not duplicate that range here.

This is the first reference book extracted for Russian (Wave 1), so nothing here is a
"non-redundant supplement" pass — full coverage applies per `00_Reference_Extraction_Spec.md`.

## Coverage note

This source is a **reference grammar**, not a lesson-based teaching textbook — it has no discrete
"vocabulary lists" separate from its grammar exposition. Its "vocabulary" consists of the
individual lexical items used throughout as illustrative examples of declension classes, gender
categories, word-formation suffixes, case government, etc. Given the coverage rule's
"comprehensive but not exhaustive" principle (skip repeated drills that don't introduce new
information), the Vocabulary table below is a **representative cross-section**, not a literal
transcription of every one of the many hundreds of individual example words in sections like §29
(noun suffixation, ~50 suffixes × 3–5 examples each) or §148–153 (adjective-formation suffixes) —
those sections are pattern catalogues where later examples under the same rule are functionally
equivalent to "repeated drills." Every **grammar point** (every numbered section, §1–§254, so far
as reached) is covered in the Grammar Points section below, paraphrased with page citations; no
grammar point is skipped. Distinct explicit dialectal/regional annotations, register labels, and
usage-tier notes the source itself marks (colloquial vs. literary vs. bookish vs. substandard,
etc.) are captured in the Notes column and in the grammar-point write-ups.

### PDF-extraction gotcha found and worked around

This PDF has a genuine text layer (`pdftotext` succeeds, is fast, and the English glosses/prose are
100% clean), but **the source's own stress-accent diacritics on Cyrillic vowels are corrupted by
`pdftotext`** — not via a fixed 1:1 substitution cipher (the kind previously seen and successfully
decoded for other Cyrillic sources in this project), but via an **unstable, position-dependent
substitution**: a stressed vowel is sometimes silently dropped (e.g. printed "самый" extracts as
"смый"), sometimes replaced by an unrelated Latin/punctuation glyph (e.g. "?", "9", "<", ">", "B",
"M", "&", "3", "6" appear standing in for a missing stressed а/о/е/и/у/ю at various points), and the
specific substitute glyph is not consistent per-vowel across the file (unlike the Korean numeric-
offset cipher or the fixed Cyrillic-to-Latin substitution cipher documented in the extraction spec
— this is closer to a font-subsetting/ToUnicode gap specific to the accent-bearing glyph variants
the book uses to mark stress, not to the base Cyrillic letters themselves). Confirmed by
cross-referencing dozens of corrupted forms against their English glosses and standard dictionary
spelling. **Every Cyrillic word quoted below has been reconstructed to standard modern Russian
orthography** by cross-referencing the corrupted extraction against (a) the parallel English gloss
supplied by the source on the same line, (b) ordinary lexical knowledge of the word, and (c), where
relevant, other unstressed occurrences of the same word elsewhere on the page. This is a text-layer
artifact affecting only the *stress-diacritic* rendering, not genuine OCR/vision-reading, so
Transcription/Vision-Reading Confidence is marked `n/a` throughout per spec (real text layer, no
vision-reading involved) — but the reconstruction itself should be treated as `plausible_unverified`
for any single word if used for downstream synthesis work requiring exact stress-mark placement;
stress-mark *position* itself (which syllable is stressed) is generally NOT recoverable from this
corruption and is omitted below unless the source's prose explicitly states it in words (e.g. "end
stress", "stem stress"). No handwritten marginalia was encountered — this is a clean digital-born
PDF (iText-produced), not a scan, so the vision-reading guard does not apply.

---

## Vocabulary

*(Representative cross-section — see Coverage note above. "Source Type" is `grammar_reference`
throughout; "Attested Era" is `contemporary (source published 2011)` throughout per the
extraction-spec rule that a book's publication date licenses this coarse, whole-book value;
"Transcription Confidence" is `n/a` throughout (not a subtitle/transcript source); "Vision Reading
Confidence" is `n/a` throughout (real text layer, no vision-reading needed) — these four columns
are omitted per-row below and stated once here to avoid repeating identical values ~150 times; the
table itself carries only the columns that vary.)*

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Region | Geographic Scope | Notes |
|---|---|---|---|---|---|---|---|
| экстрасенс | psychic | noun | colloquial | — | — | — | §7; example of retained hard consonant before е in loanwords |
| Интернет | Internet | noun | core | — | — | — | §7 note; neologism cited as an addition to the 2nd edition |
| принтер | printer | noun | technical | — | — | — | §7 |
| ГАИ | State Vehicle Inspectorate (alphabetism) | noun (indeclinable/f.) | technical | — | — | — | §40; alphabetism, feminine via central-noun gender |
| ООН | UNO (alphabetism) | noun (indeclinable/n.) | core | — | — | — | §40; retains gender of Организация (f., exceptionally undeclined) |
| МГУ | Moscow State University (alphabetism) | noun (indeclinable/m.) | core | — | — | — | §40 |
| ВИЧ | HIV | noun | technical | — | — | — | §40; masculine, currently undeclined |
| СНГ | Commonwealth of Independent States | noun (indeclinable/n.) | core | — | — | — | §40 |
| колхоз | collective farm | noun | historical/core | — | Soviet-era | national | §41; "stump compound" from коллективное хозяйство |
| собес | social security (office) | noun | colloquial | — | — | — | §41; stump compound |
| терàкт | terrorist outrage | noun | core.journalistic | — | — | — | §41 |
| штаб-квартира | headquarters | noun | core | — | — | — | §42; compound hyphenated noun, f. |
| смарт-карта | smart card | noun | technical | — | — | — | §42; recent compound |
| ЖЭК | housing office (alphabetism) | noun | colloquial | — | — | — | §40(3); gender differs by register (f. written / m. colloquial) |
| бомж | homeless person | noun | colloquial | — | — | — | §39; acronym from "без определённого места жительства" |
| вуз | institution of higher education | noun | core | — | — | — | §39; acronym |
| лазер | laser | noun | technical | — | — | — | §39 note; loan acronym |
| папарацци | paparazzi | noun (indeclinable, pl. only) | colloquial | — | — | — | §36(3); neologism added in 2nd ed. |
| флоппи | floppy disk | noun (indeclinable) | technical | — | — | — | §36(2), 2nd-ed. neologism |
| кофе | coffee | noun (indeclinable, m.) | core | — | — | — | §36 note (a); exceptional masculine gender among indeclinables |
| тайфун | typhoon | noun | core | — | — | — | cited under animal/place-name gender discussion |
| цунами | tsunami | noun (indeclinable, f./alt. n.) | core | — | — | — | §36(2); takes gender of волна |
| хиппи | hippy | noun (indeclinable, common gender) | colloquial | — | — | — | §36(3) |
| атташе | attaché | noun (indeclinable, m.) | formal | — | — | — | §36(3) |
| дума | Duma | noun | core.political | — | Russia | national | §17 note; capitalization discussed |
| Российская Федерация | Russian Federation | proper noun | formal | — | — | national | §17(3) |
| перестройка | restructuring | noun | core.political | — | Soviet/post-Soviet | national | §156(2) example |
| гласность | openness/glasnost | noun | core.political | — | Soviet/post-Soviet | national | cited in §36 context of neologisms |
| завкафедрой | head of university department (stump compound) | noun (common gender) | colloquial | — | — | — | §41; common-gender stump compound |
| дедовщина | army brutality, hazing | noun | colloquial.pejorative | — | Russia | national | §29(48); marked as historically/socially loaded |
| ежовщина | the Yezhov terror (1937–38) | noun | historical | — | USSR | national | §29(48); named historical-period noun |
| ждановщина | the Zhdanov repression (1946–48) | noun | historical | — | USSR | national | §29(48) |
| интердевочка | hard-currency prostitute | noun | slang | — | Soviet/post-Soviet | national | §28(3); listed under loan-prefix inter- |
| алкать | to crave | verb, impf. | archaic/literary | — | — | — | §217 note; irregular stem-stress-throughout verb |
| колебаться | to hesitate | verb, impf. | core | — | — | — | §217; stem-stress-throughout exception |
| дежурство | being on duty | noun | core | — | — | — | §29(38) verbal-noun example |
| диссидент | dissident | — | — | — | — | — | not directly glossed in range; noted for later cross-check |
| перестройка | see above | | | | | | |
| воевать | to wage war | verb, impf. | literary | — | — | — | §215(3) irregular conjugation example |
| жевать | to chew | verb, impf. | core | — | — | — | §215(3) |
| клевать | to peck | verb, impf. | core | — | — | — | §215(3) |
| дояр/доярка | milkman/milkmaid | noun | core | — | — | — | §43(4); gender-differentiation-through-suffix example, now largely superseded by оператор |
| секретарша | (female) secretary/typist | noun | colloquial | — | — | — | §29(46), §43(2); -ша marks lower prestige/wife-of-X sense |
| учительница | (female) teacher | noun | core | — | — | — | §43(2) note; учитель usable for either sex, more prestigious |
| ГЭС | hydroelectric power station (alphabetism) | noun (indeclinable, f.) | technical | — | — | — | §40(1)(ii) |
| ТЭЦ | thermal power station (alphabetism) | noun | technical | — | — | — | §40(1)(ii) |
| дом | house | noun, m. | core | — | — | — | §31(1); paradigm noun, 1st declension hard-ending |
| завод | factory | noun, m. | core | — | — | — | §51(1); full paradigm given |
| студент | student | noun, m. animate | core | — | — | — | §51(1); animate paradigm noun |
| музей | museum | noun, m. | core | — | — | — | §51(2)(i); soft-ending -й paradigm |
| герой | hero | noun, m. animate | core | — | — | — | §51(2)(i) |
| портфель | briefcase | noun, m. | core | — | — | — | §51(2)(ii); soft-sign paradigm |
| тесть | father-in-law (wife's father) | noun, m. animate | core | — | — | — | §33(2)(i), §51(2)(ii); masculine soft-sign exception |
| дочь | daughter | noun, f. | core | — | — | — | §33(1)(i), §63(2); irregular declension |
| мать | mother | noun, f. | core | — | — | — | §33(1)(i), §63(2) |
| путь | way, path | noun, m. (feminine-pattern declension) | core | — | — | — | §66; masculine agreement despite feminine-type endings |
| дитя | child (archaic/literary) | noun, n. | archaic/literary | — | — | — | §67; largely replaced by ребёнок |
| дети | children | noun, pl. (irreg.) | core | — | — | — | §68 |
| люди | people | noun, pl. (irreg.) | core | — | — | — | §68 |
| время | time | noun, n. (-мя type) | core | — | — | — | §64; declension paradigm |
| имя | (first) name | noun, n. (-мя type) | core | — | — | — | §64; declension paradigm |
| ноль/нуль | zero, nought | numeral/noun | core (nuance split colloquial/technical) | — | — | — | §192; two forms stylistically differentiated |
| один/одна/одно/одни | one | numeral | core | — | — | — | §193; full paradigm and idiomatic senses |
| оба/обе | both | numeral | core | — | — | — | §194(3), §191(5) |
| тысяча | thousand | numeral/noun | core | — | — | — | §197 |
| миллион | million | numeral/noun | core | — | — | — | §191(10) |
| сорок | forty | numeral | core | — | — | — | §191(8); irregular declension (one oblique ending only) |
| полтора/полторы | one and a half | numeral | core | — | — | — | §191(3), §194(1) |
| ста́рший | elder, senior | adjective (comparative-function) | core | — | — | — | §178; one-word comparative, animate-only usage |
| лу́чший | better, best | adjective (comparative/superlative) | core | — | — | — | §178, §185(3) note |
| самый | the most / the very | pronoun/particle | core | — | — | — | §131(2), §185; superlative and emphatic-locative uses |
| сей | this (archaic) | demonstrative pronoun | archaic/literary | — | — | — | §125 note (a), §129(1); used mainly in set phrases or for irony |
| экий | what a (colloquial) | demonstrative pronoun | colloquial | — | — | — | §125 note (b), §129(2) |
| никто | no one | negative pronoun | core | — | — | — | §133–134 |
| кто-то | someone (definite, unspecified identity) | indefinite pronoun | core | — | — | — | §138(1); aspectual/semantic contrast with -нибудь |
| кто-нибудь | someone/anyone (indefinite, unselected) | indefinite pronoun | core | — | — | — | §138(2) |
| кое-кто | one or two people | indefinite pronoun | colloquial | — | — | — | §139 |
| друг друга | each other | reciprocal pronoun | core | — | — | — | §143(3) |
| самый | see above | | | | | | |
| хороший | good | adjective | core | — | — | — | §146(4); mixed-declension paradigm |
| большой | big | adjective | core | — | — | — | §146(5); paradigm, stressed ending type |
| последний | last | adjective | core | — | — | — | §147; soft-ending adjective paradigm |
| волчий | wolf's | possessive adjective | core | — | — | — | §151(1); animal-possessive type |
| мамин | Mum's | possessive adjective | colloquial/familial | — | — | — | §151(2); family-circle possessive type |
| новенький | nice and new | diminutive adjective | colloquial | — | — | — | §152 |
| дороговатый | rather dear | diminutive adjective | colloquial | — | — | — | §153 |
| хаки | khaki | adjective (indeclinable) | core | — | — | — | §154(1) |
| мини (юбка мини) | mini(skirt) | adjective (indeclinable) | colloquial | — | — | — | §154(2)(ii) |
| важный | important | adjective | core | — | — | — | §161(1); buffer-vowel short-form paradigm |
| умный | clever | adjective | core | — | — | — | §161(3); irregular buffer vowel -ё- |
| большой/больше | big/bigger | adjective/comparative | core | — | — | — | §178, §180(2) |
| хуже | worse | comparative adverb/adjective | core | — | — | — | §180(3) |
| высочайший | the highest, most exalted | superlative adjective | literary | — | — | — | §187(3) |
| наиболее | the most (bookish) | superlative particle | formal/literary | — | — | — | §188 |
| преспокойный | as cool as a cucumber | adjective (colloquial superlative) | colloquial | — | — | — | §189(2) |
| ноль-ноль | (time) "hundred hours"/exactly | numeral phrase | technical | — | — | — | §192(2)(c) |
| столько...сколько | as much...as | correlative numeral pair | core | — | — | — | §201(3) |
| двое, трое, четверо | collective numerals 2, 3, 4 | numeral | core | — | — | — | §200 |
| пятеро | collective numeral 5 | numeral | core | — | — | — | §200(1) |
| десяток | a ten (quantitative noun) | noun | colloquial | — | — | — | §209(2) |
| пятёрка | "a five" (mark/group/etc.) | noun | colloquial | — | — | — | §209(1) |
| знать | to know | verb, impf. | core | — | — | — | §215(1); paradigm verb, vowel-stem 1st conj. |
| давать | to give | verb, impf. | core | — | — | — | §215(2); -авать paradigm |
| голосовать | to vote | verb, impf. | core.political | — | — | — | §215(3); -овать paradigm |
| бить | to strike/hit | verb, impf. | core | — | — | — | §215(5); zero-vowel present stem |
| ждать | to wait | verb, impf. | core | — | — | — | §216(1)(i); consonant-stem paradigm |
| гнать | to drive (herd/chase) | verb, impf. | core | — | — | — | §216(1)(ii), §221(3)(ii); mobile-stress example |
| писать | to write | verb, impf. | core | — | — | — | §217; consonant-mutation paradigm (пишу/пишешь) |
| искать | to seek | verb, impf. | core | — | — | — | §217; ск:щ mutation paradigm |
| печь | to bake | verb, impf. | core | — | — | — | §218(3); к-stem -чь paradigm |
| мочь | to be able | verb, impf. | core | — | — | — | §218(3), §224–225; irregular, no impf. future |
| бежать | to run | verb, impf./pf.(in "to escape" sense) | core | — | — | — | §224, §237(3) note; irregular conjugation |
| есть | to eat | verb, impf. | core | — | — | — | §224, §225(5), §229(2); irregular, кушать preferred in imper. |
| хотеть | to want | verb, impf. | core | — | — | — | §224, §225(7); irregular, mixed conjugation |
| дать | to give | verb, pf. | core | — | — | — | §224; irregular |
| быть | to be | verb, impf. | core | — | — | — | §226; no present tense; irregular past/future |
| читать/прочитать | to read (impf./pf.) | verb pair | core | — | — | — | §239(4); neutral perfective-by-prefixation example |
| писать/написать | to write (impf./pf.) | verb pair | core | — | — | — | §239–240; central aspect-pair example |
| заболеть | to fall ill (inceptive) | verb, pf. | core | — | — | — | §242(1); за- inceptive prefix |
| закурить | to light up (a cigarette) | verb, pf. | colloquial | — | — | — | §242(1) |
| крикнуть | to shout (semelfactive) | verb, pf. | core | — | — | — | §242(2); -ну- instantaneous suffix |
| поговорить | to have a chat | verb, pf. | colloquial | — | — | — | §242(3); по- limited-duration prefix |
| завязать/завязывать | to tie/be tying (pf./impf.) | verb pair | core | — | — | — | §238(2)(i), §244(4); secondary-imperfective example |
| переписывать/переписать | to copy (impf./pf.) | verb pair | core | — | — | — | §243(1); classic -ыв- secondary imperfective |
| поблёскивать | to glint (intermittently) | verb, impf. only | literary | — | — | — | §249(2); no perfective, iterative по- + -ива- |

**Morpheme breakdown (fusional forms only; per project convention this book's own suffix
catalogues already supply the morpheme-level analysis — a small illustrative sample is given here
rather than repeating every suffix table entry as a separate breakdown, consistent with the
Coverage note above).**

> **безбилетник** = без- (without) + билет (ticket) + -ник (agent/practitioner suffix) —
> illustrative of §28's productive prefix-plus-suffix noun-formation pattern (за-, без-, etc. +
> nominal root + agentive suffix), demonstrating that Russian nominal derivation regularly stacks
> a prefix and a suffix around a root rather than treating the derived noun as atomic. (Constructed
> from the productive pattern shown in §28/§29 rather than quoted verbatim from a single source
> example, since the source's own examples of this exact stack were not present verbatim in this
> page range — flagged as `plausible_unverified` accordingly.)

> **завкафедрой** = за- (clipped from "заведующий", "in charge of") + в- + кафедрой (instr. of
> кафедра, "university department") — a "stump compound" (§41) fusing a truncated participle with
> an inflected noun; common-gender, agreeing with the sex of the person it denotes.

> **проследить → прослеживать** = про- (prefix, "through/trace") + след- (root, "track/trace") +
> -и- (2nd-conj. thematic vowel, perfective) → secondary imperfective inserts -ива- + consonant
> mutation д→ж: про-слеж-ива-ть (§247) — illustrates the systematic secondary-imperfective suffix
> insertion (-ива-/-ыва-) plus regular consonant mutation that recurs across dozens of verb pairs
> in §244–250; the mechanism, not just the pair, is the generalizable point for later
> mechanics-analysis work.

## Grammar points

### Introduction: the Cyrillic alphabet and transliteration systems (§1–2)

The Russian Cyrillic alphabet has 33 letters (20 consonants, 10 vowels, semi-vowel й, hard sign ъ,
soft sign ь). The book lists three transliteration systems (ISO, British Standards Institution —
used throughout this Grammar — and Library of Congress) side by side, and gives the IPA symbols
used in its own phonetic transcriptions (p. 1–3).

### Pronunciation (§3–15)

- **Stressed vowels** (§3): а, э, у, о, ы each have articulatory descriptions relative to English
  equivalents; я/е/ё/ю are "iotated" variants of а/э/о/у.
- **Unstressed vowels** (§4): о and а reduce to [ʌ] in pre-tonic position and to [ə] elsewhere; е
  and я reduce to [(j)ɪ] pre-tonically; э reduces to [ɪ].
- **Hard and soft consonants** (§5): ж, ц, ш are always hard; ч, щ are always soft; all others can
  be either, conditioned by the following vowel or a following soft sign.
- **Double palatalization/regressive softening** (§6): certain adjacent-soft-consonant clusters
  (е.g. оттепель) undergo regressive softening; some words allow either single or double
  palatalization.
- **Non-palatalization in loanwords** (§7): т, д and other consonants stay hard before е in many
  loanwords (термос, антенна, интернет), a systematic loanword-phonology exception.
- **Hard sign / soft sign** (§8): the hard sign ъ marks a hiatus after a hard-final prefix before
  я/е/ё/ю; a soft sign in the same position marks a soft consonant + [j] glide.
- **Reflexive suffix -ся/-сь pronunciation** (§9): pronounced [sʲ] after a vowel, variably [sə]/[sʲə]
  in verb forms depending on person/mood.
- **Effect of a soft consonant on the preceding vowel** (§10): э/е, я, ё, ю and а/о/ы are all
  articulated differently before a following soft consonant.
- **Voiced/unvoiced consonants** (§11): six voiced/unvoiced pairs; final devoicing; regressive
  assimilation of voicing across consonant clusters and word boundaries (including
  preposition+noun boundaries); notes on г pronounced [x] in a small closed set (лёгкий, мягкий,
  Бог) and хг as [h] uniquely in бухгалтер.
- **Pronunciation of -чн-** (§12): pronounced [ʃn] in a lexically-specific set (конечно, скучно,
  patronymics in -ична), [tʃn] in "more learned" words, variable in a couple of items.
- **Consonants omitted in pronunciation** (§13): a lexically specific list of 3+-consonant clusters
  that drop a consonant (здравствуйте, поздно, сердце, счастливый, etc.).
- **Double consonants** (§14): pronounced double across a prefix/stem boundary, variably within a
  stem, single word-finally.
- **Stress** (§15): Russian stress is free (can fall on any syllable) and can be the sole marker
  distinguishing otherwise-identical words (о́рган vs. орга́н) or, rarely, alternate freely with no
  meaning change (творо́г/тво́рог). Secondary stress occurs in some compounds, especially newer or
  foreign-prefixed ones; stress marks in ordinary printed Russian appear only to resolve ambiguity,
  mark archaisms, render professional/dialect/slang words, or serve verse rhythm — an explicit
  register-marking use of the stress-mark convention itself.

### Orthography (§16–17)

- **Spelling rules 1–5** (§16): (1) ы→и, я→а, ю→у after ж/ч/ш/щ/г/к/х; (2) unstressed о→е after
  ж/ч/ш/щ/ц; (3) initial и→ы after a consonant-final prefix; (4) з/с alternation in prefixes
  (без-/бес- etc.) conditioned by the voicing of the following consonant; (5) buffer -о- inserted
  in certain consonant-final prefixes (подо-, ото-, разо-, со-). These five rules are referenced
  constantly throughout the rest of the book's declension/conjugation tables.
- **Capitalization in titles and names** (§17): only the first word of most institutional/title
  names is capitalized (Всемирная федерация профсоюзов); geographical generic terms are lower-case
  with the specific name capitalized (озеро Байкал) unless used non-literally; some titles
  (international bodies, state names) capitalize every word; unofficial/foreign-parliament titles
  are fully lower-case; nationality/place-of-origin nouns and their adjectives are lower-case
  except within titles; celestial-body senses of земля/луна/солнце are capitalized; deity names are
  capitalized, with a small-letter default for a generic/plural/figurative "бог".

### Word Division and Punctuation (§18–26)

- **Syllabic division** (§18): syllable boundaries follow a sonority hierarchy (vowel > sonant
  р/л/м/н > other consonant); non-initial syllables cannot begin with sonant+noise-consonant.
- **Line-end splitting** (§19): follows syllabic division plus morphological considerations
  (don't split off a bare vowel; don't separate a hard/soft sign or й from its neighboring letter).
- **Punctuation overview** (§20–26): Russian punctuation is applied more rigorously than English,
  especially for the comma (marking off nearly every subordinate clause, participial/gerundial
  phrase, parenthetical, and item in a list — §22–23), for the colon (introducing lists,
  elaborations, direct speech, quotations — §24), for the semicolon (separating extensive
  comma-internally-punctuated clauses), and for the dash (replacing "to be" between subject and
  predicate nouns, marking ellipsis, substituting for comma/colon/parentheses in various contexts —
  §24). Direct speech is punctuated either with a colon + new-line dash, or a colon + guillemets
  («»), or flanking dashes if the reporting verb follows the speech (§25). Suspension points (...)
  mark hesitation or an unfinished statement (§26).

### The Noun — Word Formation (§27–29)

- **Compounding** (§27): Russian nouns compound from noun/adjective/numeral/adverb first
  components and noun/verbal-origin second components, usually linked by infix -о- (or -е- after a
  soft/sibilant-final first component); a productive sub-pattern pairs indigenous suffixes (-вед,
  -вод) with international ones (-граф, -лог, -ман, -тека, -фил, -фоб) for person/place compounds.
- **Prefixation** (§28): two prefix sets are distinguished — one shared with verbs (в-, вз-/вс-,
  воз-/вос-, вы-, до-, за-, из-/ис-, на-, над-, недо-, о-/об-, от-, пере-, под-, пре-, пред-, при-,
  про-, раз-/рас-, с-, у-), each with the specific meaning-variants tabulated; and a second,
  mostly-loan set used chiefly with nouns/adjectives (а-, анти-, архи-, без-/бес-, вице-, гипер-,
  де-, дез-, дис-, интер-, квази-, контр-, между-, микро-, не-, нео-, по-, под-, после-, пост-,
  пра-, преди-, про-, противо-, псевдо-, ре-, само-, сверх-, суб-, супер-, ультра-, чрез-/чрес-,
  экс-, экстра-), grouped by semantic category (excess, negation, time, opposition/support, sham).
- **Suffixation** (§29): the book catalogues 52 noun-forming suffixes across major semantic classes
  — abstract qualities/feelings (-ба, -ие/-ье, -изм, -ость/-есть, -ота, -ствие, -ство, -сть),
  actions/verbal nouns (-ация/-изация, -ка, -ние, -ок, -ство, -тие), animate agents/nationals/
  practitioners (-ак/-як, -анин/-янин, -арь, -ач, -ец, -ик, -ист, -ник, -ок, -тель, -ун, -щик/-чик),
  collectives (-ство, -ура), objects/implements (-ик, -ка, -ло, -ник, -ок, -тель, -щик/-чик), places
  (-ище, -ня, -ье), and dimension/quantity (-ина, -ство), plus a set of highly specific suffixes
  (young-of-animal -ёнок/-онок, berry -ика, meat-type -ина, remnant -ки, container -ница,
  patronymic -ович/-евич/-ич, sound -от, medical-condition -ота/-уха). Velar consonants (г, к, х)
  and ц regularly mutate before many of these suffixes (г:ж, к:ч, х:ш, ц:ч), and the book gives the
  specific mutation pattern for each suffix that triggers it. This is the single densest section in
  the assigned range — dozens of suffixes each with 3–6 example nouns — and is the source of most
  vocabulary-table entries above being drawn selectively rather than exhaustively.

### The Noun — Gender (§30–45)

Russian distinguishes grammatical gender (by noun ending) from natural gender (by sex of referent),
plus a "common gender" category (nouns in -а/-я, e.g. сирота, пьяница, which take masculine or
feminine agreement depending on the referent's sex, §35). Masculine (§31) includes all hard-
consonant and -й nouns plus a closed set of "natural masculines" in -а/-я (дедушка, дядя, papa,
etc.) and most soft-sign nouns fitting specific patterns (§33). Feminine (§32) is most nouns in
-а/-я plus roughly three-quarters of soft-sign nouns, with the source giving detailed sub-rules for
which soft-sign endings are reliably feminine vs. masculine (§33) — e.g. all nouns in -жь/-чь/-шь/
-щь/-знь/-мь/-пь/-фь are feminine, but nouns in -дь have a closed list of masculine exceptions
(вождь, гвоздь, дождь, лебедь, медведь etc.). Neuter (§34) covers -о/-е/-ё nouns and the -мя class.
Indeclinable loanwords (§36) take neuter gender by default (mostly), but the "generic principle"
(the gender of the semantically parent Russian noun) can override this for animals, place names,
and other categories — а productive, rule-governed system covered in detail across §36–45,
including gender assignment for acronyms/alphabetisms (§39–40, largely by final-letter form or by
the gender of the underlying phrase's head noun, with documented cases of gender drift over time,
e.g. МИД shifting from neuter to masculine, ТАСС from neuter to masculine), stump compounds (§41),
hyphenated compounds (§42), and the systematic use of derivational suffixes to mark male/female
counterparts in professions and nationalities (§43), including sociolinguistic commentary on when
a feminine occupational suffix (e.g. -ша) carries a "wife of X" or lower-prestige connotation versus
being the neutral choice, and when the masculine form is used for referents of either sex (§44).
Animal-name gender (§45) ranges from fully non-differentiated (ёж, кит) through partly
differentiated (волк/волчица) to fully three-way differentiated for major farm/domestic species
(гусь/гусак/гусыня; лошадь/жеребец/кобыла; собака/кобель/сука).

### The Noun — Declension (§46–76)

Nouns decline in one of three patterns (§46): first declension (most masculine and neuter nouns),
second declension (most feminine nouns in -а/-я, some masculine/common-gender), third declension
(all feminine soft-sign nouns). §47 sets out the animate accusative=genitive rule for masculine
singular and all-gender plural animate nouns, including its extension to figurative animates
(болван, дуб used of people), folk-dance names, book titles, and playing-card/chess/billiards
terms — and its non-application to collective nouns (народ, полк, скот) and to труп (vs. animate
мертвец/покойник). §48–49 catalogue singularia tantum (qualities, collectives, substances, certain
natural-phenomena intensives) and pluralia tantum (брюки, ножницы, деньги, etc., with their
genitive-plural formation patterns). §50 gives the master declension-endings chart. §51–63 give
full declension paradigms and stress patterns for every subclass: first-declension masculine hard-
and soft-ending nouns, the fleeting vowel (§52), the partitive genitive in -у/-ю (§53, restricted to
count/mass nouns denoting measurable quantities and shrinking in productivity per the source's own
note), the locative in stressed -у/-ю (§54, contrastive with -е depending on preposition and
literalness of the "location" sense), irregular masculine plurals in -а/-я́ and -ья (§55), nouns
whose genitive plural equals the nominative singular (§56, covering footwear, several
nationalities, military ranks, units of measurement, and — colloquially only — fruit names), three
stress-pattern types across declension (§57), neuter declension in -о/-е/-мя/-ие (§58–60, 64–65),
irregular nouns путь, дитя, дети/люди (§66–68), and declension of first names, surnames, place
names, and alphabetisms (§69–73, including detailed rules on which surname endings decline,
partial adjective-like declension of -ов/-ин surnames, and non-declension of many town names in
-ово/-ино to avoid ambiguity with related -ов/-ин forms). §74 covers hyphenated noun co-ordinates
(which element(s) decline depending on relative semantic weight). §75 covers predicate-number
agreement with collective-noun subjects like ряд and большинство (singular by default, plural when
followed by an animate genitive plural and an active verb). §76 covers "the singular-for-shared-
body-part" construction (Все повернули голову) and its emerging colloquial plural alternative.

### The Noun — Case Usage (§77–103)

The **nominative** (§77) marks the subject, appears after это/вот, in possessive у-constructions, in
чем-comparisons, generalizing как-constructions, definitions, and apposition. The **vocative**
(§78) survives only as truncated familiar forms (мам!, Вань!) and fossilized ecclesiastical
exclamations. The **accusative** (§79) marks the direct object, appears in certain impersonal
constructions, and denotes duration/repetition/cost/weight. The **genitive** covers possession,
relationship, whole-to-part, agent/object of a nominalized action, descriptive attributes,
comparison, and the object of жаль (§80); quantity words (§81); the partitive genitive proper,
restricted to perfective-verb objects in most cases (§83) and its -у/-ю variant (§84, in decline in
modern usage per the source); genitive-in-у set phrases (§85); genitive-with-negation constructions
(нет, не было, не будет, and negated verbs of existence/perception, §86) and the genitive/accusative
choice after negated transitive verbs generally, with a long list of conditioning factors — word
order, specificity, animacy, presence of an intervening infinitive (§87); and an extensive
categorized list of verbs governing the genitive (§88: asking/waiting/seeking, fearing/avoiding,
depriving, conformity/non-conformity). The **dative** marks the indirect object (§89) and is
governed by verbs of assistance/hindrance, attitude, and other specific meanings (§90), by a closed
set of adjectives (§91), by impersonal constructions of mood/state (§92), and functions as logical
subject of an infinitive (§93). The **instrumental** covers function/means (§94), body-part
movement (§95), passive agent (§96), adverbial time/manner/space expressions (§97), similarity
(§98), a further categorized verb list (§99: use/control, attitude, reciprocal action), a closed
adjective set (§100), dimension (§101), and — at length — predicate usage with быть/явиться, with
detailed rules distinguishing permanent-state nominative predicates from temporary-state
instrumental predicates, and its use after verbs of seeming/becoming/being considered (§102).
Apposition (§103) requires case agreement across co-referential nouns/pronouns/modifiers.

### The Noun — Diminutives and Augmentatives (§104–109)

Diminutive suffixes denote smallness but frequently also carry affection, disparagement, or irony
depending on context — a genuinely register-marking morphological system, not merely a size marker.
Masculine diminutives use -ец, -ик, -ок/-ёк/-ек, -чик (§105); feminine use -ица, -ка (§106); neuter
use -ико, -ко, -цо/-це/-ецо (§107); further suffixes -ашка, -ишко/-ишка, -онка/-ёнка, -ушка/-юшка,
-енька/-онька, -ышек/-ышко add further disparagement/affection nuance (§108). Augmentatives in
-ина, -ище/-ища denote largeness and can carry their own emotive colouring (§109).

### The Pronoun (§110–143)

Personal pronouns (§110) decline irregularly and take initial н- after most prepositions but not
after certain derivative prepositions (благодаря, навстречу, вопреки, согласно, внутри — a genuinely
useful, source-marked exception list). §111 covers preference for personal/reflexive over possessive
pronouns with body parts and clothing. §112–116 cover это-constructions, я/ты/вы register selection
(a socially significant T–V system explicitly discussed as varying by age, status, and setting —
§115), and third-person pronoun functions including with verbs of yearning governed by по. The
reflexive pronoun себя (§117) has no nominative, refers to the subject of the nearest verb/adjective
regardless of person/number/gender, and its scope in two-verb sentences is a documented source of
genuine ambiguity requiring paraphrase to resolve. Possessive pronouns мой/твой/наш/ваш decline
adjectivally (§118); the third-person possessives его/её/их are invariable and never take н- (§119).
The reflexive possessive свой (§120) is the default for a first/second-person subject's possessions
and is *obligatory* for unambiguous reference to a third-person subject's own possessions,
distinguished carefully from его/её/их, including across an intervening subordinate clause and in
two-verb sentences where свой tracks the nearer verb's subject. §121–123 give full declension and
usage of кто/что/какой/который/чей as interrogatives and relatives, including a careful semantic
distinction between который (a specific referent) and какой (a class/type of referent), and the
что-clause/то-что-clause linking construction. §124 covers secondary/idiomatic uses of кто/что in
exclamations and concessive constructions. §125–132 cover demonstrative (этот/тот/сей/экий) and
determinative (сам/самый/весь/всякий/каждый/любой/всяческий) pronouns, including their nuanced
semantic contrasts (всякий = "all kinds of," каждый = "each individually," любой = "any, freely
selectable"). §133–142 cover the negative pronoun series (никто/ничто/никакой/ничей, §134–136), the
distinctive "potential negative" construction не́кого/не́чего + infinitive with dative logical
subject (§137), and the indefinite-pronoun particle system -то/-нибудь/-либо (§138) with a precise
aspectual-style semantic contrast (-то = a definite but unknown-to-speaker referent; -нибудь = a
genuinely unselected/hypothetical referent, hence its affinity for questions, futures, imperatives,
and conditionals; -либо = a more bookish synonym of -нибудь with a stronger "any whatsoever" force),
plus кое- compounds (§139) and the archaic/bookish некто/нечто/некоторый/некий series (§140–142).
§143 covers other parts of speech functioning pronominally (данный, один in its "a certain"/"the
same" senses, and the reciprocal друг друга).

### The Adjective (§144–189)

Adjectives are attributive or predicative and mostly have parallel long and short forms (§144).
Long-form declension is hard-ending (§145), "mixed" (velar/sibilant/ц-final stems, governed by the
spelling rules, §146), or soft-ending (a closed ~40-item set in -ний plus карий, §147). §148
catalogues the three main noun-to-adjective suffixes (-н-, -ск-, -ов-/-ев-) with their productive
domains (people/places/nationalities/organizations/months for -ск-; trees/fruits/metals/colours/
animals/materials for -ов-/-ев-) and documents systematic velar/ц/л mutation before -н-. §149 lists
adjectival endings with specific derivational meanings (-ивый/-ливый/-чивый for characteristics,
-мый for potential/"-ble" qualities, -атый/-астый/-истый for possession/abundance of a feature).
§150–151 cover doublet adjectives from one noun and the two possessive-adjective types (влчий-type
from animal names with consonant mutation; мамин-type suffixed with -ин/-нин/-ов, used within the
family circle and from first-name diminutives). §152–154 cover diminutive adjectives in
-енький/-онький (smallness plus emotive nuance) and -оватый/-еватый (incompleteness/approximation,
not universally formable), and indeclinable (mostly loan) adjectives for colours, food/drink,
clothing styles, and languages. §155–158 cover attributive and predicative long-form usage
(including the mandatory instrumental-case agreement pattern with быть in conditional/subjunctive/
infinitive/imperative contexts, and after verbs of seeming/looking/considering), singular/plural
agreement across coordinated nouns, and adjectival nouns (nouns with adjective morphology,
subclassified by what "understood" noun they historically replace — столовая, часовой, животное,
etc.). §159–175 give the short form's derivation (dropping the full ending), the closed classes of
adjectives that lack short forms entirely (colours except синий, -ский adjectives, most -ний
adjectives, ordinal numerals, materials, time/place adjectives, влчий-type possessives) or only in
certain senses, the three buffer vowels (-е-, -о-, -ё-) inserted in the masculine short form, several
irregular short forms (велик, достоин, искренен, мал, синь, солон), stress patterns, and — at
length — the core semantic distinction between long-form (permanent/inherent) and short-form
(temporary/circumstance-delimited) predicative adjectives, including the rule that any oblique-case,
prepositional-phrase, subordinate-clause, or infinitival "delimiter" of the adjective's meaning
forces the short form (§170–173), and short-form usage in generalized proverbs/sayings (§174).
§176–184 detail the comparative degree: the productive analytic более-comparative (agreeing in
gender/number/case, §177); six suppletive one-word comparatives (лучше, хуже, старше, младше,
больше, меньше, §178); the productive synthetic predicative comparative in -ее/-ей (§179); a closed
set of comparatives in bare unstressed -е with regular final-consonant mutation (д:ж, г:ж, к:ч, з:ж,
с:ш, ск:щ, ст:щ, т:ч, х:ш — §180) plus irregular -ше forms; comparative syntax for "than" (чем vs.
genitive-of-comparison, restricted to nominative-case first terms), quantified difference (на +
accusative), multiples (в + accusative), the "the more...the better" чем...тем construction, "much
more" intensifiers, "as...as possible" (как можно + comparative), and repeated comparatives (§182);
colloquial attributive use of the short comparative, especially по-prefixed forms (§183); and other
functions (introductory-word use, adverbial use, impersonal use — §184). §185–189 cover the
superlative: the productive самый + long adjective (§185); highly lexicalized высший/низший
(§186); a synthetic superlative in -ейший/-айший with velar/х mutation, used for true superlatives
or for mere intensifiers depending on context (§187); the bookish наиболее/наименее (§188); and
newspaper-style наибольший/наивысший/наилучший/наименьший plus the colloquial пре- superlative
prefix (§189).

### The Numeral (§190–211)

§190–199 cover the cardinal numeral series (with detailed notes on the internal morphology of
11–19 and the compound-numeral formation pattern), full declension paradigms for every numeral
class (191), the stylistic split between ноль and нуль (§192), the numeral один's full agreement
behavior including its use with plural-only nouns and its "alone/only/a certain/the same" secondary
meanings (§193), the genitive-singular-government pattern of полтора/два-три-четыре/оба (§194) and
genitive-plural government of 5–999 (§195), oblique-case agreement of declined numerals with plural
nouns (§196), the special quantity-noun behavior of тысяча/миллион/миллиард (§197), declension of
compound numerals — full literary declension of every component vs. colloquial declension of only
the final (or first-and-final) component(s) (§198), numerals used as indeclinable "labels" in
addresses, model/flight/ticket numbers (§199). §200 covers the collective-numeral series (двое,
трое, четверо...десятеро) and its four distinct usage domains — plural-only nouns, masculine
animate nouns/nouns in -а with an emphasis on group cohesion (contrasted with the individualizing
force of cardinals), дети/ребята/внуки/близнецы, and absolute number-of-people usage without an
accompanying noun — with an explicit note that collectives with feminine animate nouns are
substandard. §201 covers indefinite numerals (мало, много, немало, немного, несколько, сколько,
столько) including their declension behavior and the distinct genitive-plural noun они take with
человек vs. людей. §202 is a substantial discussion of subject-verb agreement with numeral-headed
subjects, identifying word order, the semantic class of the predicate verb (state/passive vs.
active), demonstrative/relative-clause modification, and emphasis-on-individual-action as the
governing factors. §203–204 cover ordinal-numeral formation and usage (pages, chapters, TV
channels, clothing sizes, and the productive по + comparative-adjective construction used where
English would extend an ordinal with a superlative). §205–211 cover fractions/decimals (comma as
decimal point), the productive пол- "half" prefix and its oblique-case behavior, telling time (both
"о'clock" systems and the distinctive "minutes of the next hour" / "without X minutes" constructions
either side of the half-hour), giving the date, expressing age, quantitative nouns (единица through
десятка as a marking scale, playing-card/bus-number labels, and пяток/десяток/сотня as informal
counting units), numerals in the four arithmetic operations, and numeral components of compound
nouns/adjectives (двух-/тре-/четверо- etc., with special forms for 1, 90, 100, 1000).

### The Verb — Conjugation (§212–234)

Every verb has an infinitive-preterite stem and a present-future stem (§212), which may coincide or
differ; the present-future stem is derived by stripping the last two letters of the 3rd-person
plural. Two conjugation patterns exist (§213): first (-е-) and second (-и-/-я-), each with its own
ending set, subject to the о/е-after-sibilant and у/а-after-sibilant spelling rules. §214–219 give
exhaustive first-conjugation subclasses: vowel stems (-ать/-ять including -авать/-овать/-евать
subtypes, -еть, -ить, -ыть, -уть — §215); consonant stems with mobile vowels, inserted -в-/-д-/-м-/
-н-, or lost mobile vowels (§216); the large "second consonant-stem" class of -ать verbs with
consonant mutation throughout conjugation and a stress shift off the first-person singular (writing,
seeking, weeping, moving, hiding, cutting, etc. — §217, with an extensive irregular-verb list);
verbs in -ти/-сть/-зть/-чь subclassified by stem-final consonant, each with full paradigms (§218);
and a summary of which verb classes undergo the ending-to-stem stress shift (§219). §220–223 give
second-conjugation present-future stems and endings, the large sound-verb subclass in -еть/-ать
with sibilant/hushing stems, systematic first-person-singular consonant mutation (б:бл, в:вл, д:ж,
з:ж, с:ш, т:ч, ст:щ, ф:фл, м:мл, п:пл — §222), and stress-shift patterns with a substantial
alphabetical list of affected verbs (§223). §224–225 cover fully irregular verbs (бежать, есть,
хотеть, дать, чтить) and verbs with gaps in their conjugation (no 1st-person singular for
победить/убедить/затмить/очутиться/чудить; no 1st/2nd person at all for звучать/значить/означать/
течь; register-restricted есть/кушать; a hearsay-only слыхать). §226 is a detailed treatment of
the copula: быть has no present tense (with a dash sometimes used for emphasis or in definitions);
есть survives as an emphatic/existential/defining copula; явля́ться is the formal/journalistic
"to be" of definitions; more specific verbs (сидеть, служить, состоять, etc.) frequently substitute
for a generic "to be" in context; бывать marks habituality/frequency. §227–229 cover imperative
formation (in -й, -и, or -ь depending on stress pattern and stem-final consonant count), imperative
stress placement (matching the first-person singular), and verbs with no or a dispreferred
imperative (видеть, слышать; кушать preferred over ешь!). §230–234 cover past-tense formation
(-л + gender/number endings), the closed classes of verbs with NO -л in the masculine past
(-ереть verbs, optional -ну- verbs of change-of-state, -ти/-зть/-чь verbs, -шибить compounds),
mobile stress in the past tense (a substantial list of monosyllabic verbs and their prefixed
derivatives with end-stressed feminine, or end-stressed feminine/neuter/plural, past forms — of
particular note, all -ти verbs and most -чь verbs shift stress this way), future-tense formation
(the periphrastic imperfective future with быть + infinitive vs. simple conjugation of a perfective
verb for the perfective future), and the buffer vowel -о- inserted in various perfective conjugated
forms after a consonant-final prefix.

### The Verb — Aspect, introductory sections (§235–254, through the page-320 cut-off)

§235 introduces the aspect system as the dominant organizing feature of the Russian verb: most
verbs have paired imperfective/perfective forms differentiated by prefixation, internal
modification, suppletion (говорить/сказать), or — rarely — stress alone (насыпа́ть/насы́пать); both
aspects appear in past, future, imperative, and infinitive, but only the imperfective has a present
tense, giving most verbs five finite forms total. The core semantic split: imperfective focuses on
an action in progress or its frequency; perfective emphasizes successful completion/result, and can
also mark attempted-vs.-achieved action (уговаривал "tried to persuade" vs. уговорил "succeeded in
persuading"). §236 lists substantial closed classes of imperfective-only verbs (states: зависеть,
находиться, нуждаться, принадлежать, стоить, etc.) and perfective-only verbs (mostly denoting
sudden/precipitate action: очутиться, грянуть, хлынуть). §237 covers bi-aspectual verbs (one form
serving both aspects, common in -овать/-изировать loans), with context/adverbs required to
disambiguate tense reference, and some bi-aspectuals that have since acquired an alternative,
aspect-specific perfective (проинструктировать, скоординировать). §238 gives the two formation
mechanisms (prefixation to perfectivize; internal modification/suffix-insertion or a conjugation-
class switch for other pairs) in overview; §239–240 detail prefixal perfectivization, noting that
most prefixes are semantically "neutral" (aspect-only) when forming the primary/neutral perfective
of a given verb, while further prefixes on the same root create new perfectives with genuinely new
meanings (§239(4)'s table of writeть → на-писать as the neutral perfective, contrasted with §244's
за-писать/пере-писать/под-писать as new-meaning perfectives each requiring their own secondary
imperfective). §241 notes a small residual semantic split even within an aspect pair (видеть/увидеть
carrying "to associate with" vs. "to catch sight of" depending on tense). §242 catalogues perfective
submeanings beyond simple result: inceptive (за-, §242(1)), instantaneous/semelfactive (often
-ну-, §242(2)), and limited-duration (по-, §242(3), which can also override a verb's "neutral"
perfective to add a limited-duration reading: пописа́ть "to write for a while" vs. написа́ть).
§243–248 detail internal-modification aspect-pair formation in depth: secondary imperfectives of
first-conjugation-derived perfectives via inserted -ыв-/-ив- with predictable stress shift and
vowel mutation (е→ё, о→а under stress — §244–245); the same process for second-conjugation-derived
perfectives, with the parallel consonant mutations from §222 recurring here (§246–247, including
a documented literary/colloquial stylistic split for a subset of о/а-alternating forms); and a
distinct -ва- infixation pattern (with the inserted consonant often matching the stem verb's own
1st-person-singular mutation) for secondary imperfectives of monosyllabic-root compounds (§248).
§249 covers three specific non-standard imperfective submeanings carried by пере-, по-, and при-
prefixed forms: reciprocal/joint action (переписываться "to correspond"), intermittent repetition
of a short action (посвистывать "to whistle every now and then" — mutation е:ё/о:а again), and
accompanying action (припевать "to sing along") — all three subclasses noted as lacking
perfectives. §250 details the very productive first-conjugation-imperfective/second-conjugation-
perfective aspect-pair pattern with its own consonant-mutation table (paralleling §222/§247) and
stress-pattern note (imperfective end-stressed, perfective stem-stressed, in many pairs). §251
lists suppletive (different-root) aspect pairs (бить/ударить, брать/взять, говорить/сказать,
класть/положить, ловить/поймать). §252 lists verbs reflexive in the imperfective only (ложиться/
лечь, садиться/сесть, становиться/стать, and лопаться/лопнуть, рушиться/рухнуть). §253 explains
the -кладывать/-лагать split among -ложить compounds as a literal/abstract semantic split
(прокладывать дорогу "to lay a road" vs. предлагать "to propose"), with pairs like вкладывать
(literal insertion) vs. влагать (figurative, "to put one's heart into") sharing a perfective
(вложить) but keeping distinct imperfectives. §254 begins a systematic prefix-by-prefix catalogue
of verbal-prefix meanings, each tied to an approximate prepositional equivalent (в- ≈ в + acc.
"into"; вы- ≈ из + gen. "out of"; до- ≈ до + gen. "as far as"; за- ≈ за + acc. "behind"; из- ≈ из +
gen. "out of"; на- ≈ на + acc. "on to"; от- ≈ от + gen. "detaching"; пере- ≈ через + acc. "across";
под- ≈ к + dat. "approach" / под + acc. "under"; при- ≈ к + dat. "attaching"; с- ≈ с + gen. "down
from" / с + instr. "together with"); the extraction for this file cuts off mid-entry for prefix
вы- (its third sub-meaning, "exhaustiveness of action," example выска́зываться, is truncated at the
exact PDF-page-320 boundary) — **the continuation of §254 and the entire remainder of the Aspect
chapter and book is covered by the sibling subagent's file for pp. 321–632.**

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`. All illustrative
sentences quoted above are the short, singular examples the source itself uses to demonstrate one
specific rule, not bulk-copied passages; longer literary quotations embedded in the source (marked
with an author's name, e.g. "(Rasputin)", "(Trifonov)") were paraphrased rather than reproduced
wherever more than one sentence would otherwise have been quoted verbatim.
