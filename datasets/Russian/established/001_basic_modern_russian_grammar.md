# Russian — Established Vocabulary/Grammar: Part 1, "The Gender Agreement of Russian Nouns in the Singular"

**Source:** Eugenia Nekrasova, *A Basic Modern Russian Grammar* ("Russian Fresh from Russia"),
eBook edition, © Eugenia Nekrasova 1997 / Graphic Design & eBook publisher Dmitry Pobedimsky 2002,
ISBN 5-85550-119-1. Print edition (Finnish translation) "A Basic Modern Russian Grammar" —
380 pages, Gummerus, Helsinki, Finland, 1998. This extraction covers **Part 1** ("The Gender
Agreement of Russian Nouns in the Singular"), source pages 1-12 (PDF pages 4-15 of 195).

**Coverage note:** every grammar point and every distinct vocabulary item from Part 1. This
source has a genuine PDF text layer (not vision-read), but its Cyrillic renders through a fixed
1:1 character-substitution cipher rather than a directly readable encoding — see the "PDF
extraction gotcha" note below. Repeated drill sentences reusing the same noun set across genders
(e.g. "Это мой дом / Это моё место / Это моя машина" repeated with different pronouns) are
condensed into a single representative example per grammar point rather than transcribed in
full, per the coverage rule. No handwritten marginalia was present; this is a clean digital-native
PDF (PageMaker 6.52 / Distiller 5.0), not a scan.

**PDF extraction gotcha (new pattern for this project, worth flagging for future Russian
sources):** this PDF's Cyrillic text is not corrupted OCR garbage — `pdftotext`/PyMuPDF both
produce a real, consistent text layer, but the embedded font's byte codes for Cyrillic letters
were assigned to their **Windows-1251 codepoints while the extraction tooling (lacking a usable
ToUnicode CMap) decodes those bytes as Latin-1/Windows-1252 instead.** The result is legible
"look-alike" Latin/symbol soup (e.g. `äîì` for "дом", `Âîò` for "Вот") that decodes perfectly by
re-encoding the extracted string as Latin-1 bytes and re-decoding those bytes as `cp1251`
(`text.encode('latin-1').decode('cp1251')`), verified against dozens of independently-recognizable
words (дом, друг, машина, Волга, Россия, etc.) before being trusted. A **second, book-specific
layer** sits on top of this: stress-marked (stressed-syllable) vowels use seven additional glyphs
that don't follow cp1251 at all — a custom, non-standard one-off substitution seemingly specific
to this font's stress-accent glyphs, decoded by cross-referencing known city/word forms (e.g.
"Мисс`˜`ри" only makes sense as "Миссури" stressed on -у, "Б`˜`ак`˜`у" cross-checked similarly):

| Corrupted glyph | Correct letter (stressed) |
|---|---|
| `‹` (U+2039) | о |
| `‚` (U+201A) | а |
| `‰` (U+2030) | и |
| `ˆ` (U+02C6) | е |
| `˜` (U+02DC) | у |
| `µ` (U+00B5) | я |
| `¬` (U+00AC) | э |

Because the vocabulary in this book is not stress-annotated in the tables below (stress marks are
dropped in favor of the plain dictionary form — the mark only mattered for pronunciation drilling,
not lexical identity), this cipher only affected page-by-page prose reading, not the final table
content. Both layers cross-checked cleanly across the whole 195-page extraction; no low-confidence
residue remained after decoding (all instances resolved, verified against context).

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| дом | house | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | ends in consonant → Masculine |
| друг | friend | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| музей | museum | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| человек | man, person | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| город | city | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| мама | mama, mommy | noun (F) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -а ending → Feminine |
| машина | car | noun (F) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| статья | article | noun (F) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -ья ending → Feminine |
| неделя | week | noun (F) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| фамилия | surname | noun (F) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -ия ending → Feminine |
| папа | father, dad | noun (M, "natural masculine") | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -а ending but Masculine agreement (denotes a male) |
| дедушка | grandfather | noun (M, "natural masculine") | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| мужчина | man | noun (M, "natural masculine") | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| дядя | uncle | noun (M, "natural masculine") | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| место | seat, place | noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -о ending → Neuter |
| море | sea | noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| купе | (train) compartment | noun (N, indeclinable) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | foreign origin, indeclinable |
| здание | building | noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| телевидение | television | noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| здоровье | health | noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| время | time | noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | listed as an exception among -мя neuters |
| имя | name (given name) | noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| интервью | interview | noun (N, indeclinable) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| меню | menu | noun (N, indeclinable) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| жюри | jury | noun (N, indeclinable) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| такси | taxi, cab | noun (N, indeclinable) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| гость | guest | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | soft-sign noun, Masculine because it denotes a person |
| водитель | driver | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| учитель | teacher | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| писатель | writer | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| царь | Tsar | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| король | king | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| вратарь | goalkeeper | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| январь | January | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | month names in -ь are always Masculine |
| февраль | February | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| мать | mother | noun (F, soft-sign, "natural feminine") | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| дочь | daughter | noun (F, soft-sign, "natural feminine") | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| жизнь | life | noun (F, soft-sign, -знь) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -знь/-сть/-сь soft-sign nouns are Feminine |
| новость | news | noun (F, soft-sign, -сть) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| подпись | signature | noun (F, soft-sign, -сь) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| Волга | Volga (river) | proper noun (F) | core | — | contemporary (source published 1997) | — | national | grammar_reference | n/a | n/a | |
| Россия | Russia | proper noun (F) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | |
| Китай | China | proper noun (M) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | fits the -consonant Masculine pattern |
| Баку | Baku | proper noun (M, indeclinable) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | doesn't fit native endings; gender assigned by the "generic" word (город, "city" → M) |
| Сочи | Sochi | proper noun (M, indeclinable) | core | — | contemporary (source published 1997) | — | national | grammar_reference | n/a | n/a | |
| Тбилиси | Tbilisi | proper noun (M, indeclinable) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | |
| Хельсинки | Helsinki | proper noun (M, indeclinable) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | |
| Миссури | Missouri | proper noun (F, indeclinable) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | associated with generic "река" (river, F) |
| Таити | Tahiti | proper noun (M, indeclinable) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | |
| Токио | Tokyo | proper noun (M, indeclinable) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | associated with "город," Masculine |
| Онтарио | Ontario | proper noun (N, indeclinable) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | associated with "озеро" (lake, N) |
| Финляндия | Finland | proper noun (F) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | |
| Приморье | Primorye | proper noun (N) | core | — | contemporary (source published 1997) | — | regional | grammar_reference | n/a | n/a | |
| шоссе | highway | noun (N, indeclinable, foreign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| радио | radio (set) | noun (N, indeclinable, foreign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| метро | subway | noun (N, indeclinable, foreign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| кино | movies, cinema | noun (N, indeclinable, foreign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| ателье | studio, dress shop | noun (N, indeclinable, foreign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| кафе | café | noun (N, indeclinable, foreign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| бюро | office, bureau | noun (N, indeclinable, foreign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| пальто | overcoat | noun (N, indeclinable, foreign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| кофе | coffee | noun (M, indeclinable, foreign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | flagged exception: foreign-indeclinable but Masculine, not Neuter like the rest of the group |
| новый | new | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | regular -ый adjective |
| большой | big, large | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -ой type |
| хороший | good | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -ий type |
| плохой | bad | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| дорогой | expensive, dear | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| русский | Russian | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| английский | English | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| маленький | small, little | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| последний | last | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | soft-stem -ний type (irregular Neuter/Feminine endings) |
| свежий | fresh | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -жий soft-stem type |
| горячий | hot | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -чий soft-stem type |
| настоящий | present, real | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | -щий soft-stem type |
| ранний | early | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| поздний | late | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| финский | Finnish | adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| учёный | scientist | adjectival noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | adjective-form noun from omission of "человек" |
| безработный | unemployed (person) | adjectival noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| столовая | dining room | adjectival noun (F) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | from omission of "комната" (room) |
| ванная | bathroom | adjectival noun (F) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| набережная | embankment | adjectival noun (F) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | from omission of "улица" (street) |
| второе | second course (of a meal) | adjectival noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | from omission of "блюдо" (dish, course) |
| горячее | main/hot course | adjectival noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| мороженое | ice cream | adjectival noun (N) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| этот/эта/это | this (M/F/N) | demonstrative pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | proximal demonstrative, gender-agreeing |
| тот/та/то | that (M/F/N) | demonstrative pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | distal demonstrative |
| такой/такая/такое | such a, this kind of | demonstrative/qualitative pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | also used in expressive exclamations ("Сегодня такой ветер!") |
| такой же | the same kind of | qualitative pronoun phrase | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| самый | the very, most | intensifying pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | combines with long adjectives for superlatives |
| тот самый | the very same (one mentioned before) | pronoun phrase | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| какой/какая/какое | what, which, what kind of | interrogative/exclamatory pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | also used exclamatorily ("Какой сильный ветер!" — "What a heavy wind!") |
| чей/чья/чьё | whose | interrogative pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| сам/сама/само | -self (emphatic) | emphatic pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | can characterize both nouns and personal pronouns |
| весь/вся/всё | all, the whole | pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| один/одна/одно | one, a | cardinal numeral | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | agrees in gender like an adjective, unlike the other cardinal numerals |
| он/она/оно | he/it, she/it, it | personal pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | replaces nouns by their established gender |
| мой/моя/моё | my | possessive pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| твой/твоя/твоё | your (ты-form, singular/informal) | possessive pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| наш/наша/наше | our | possessive pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| ваш/ваша/ваше | your (вы-form, plural/formal) | possessive pronoun | core | formal (вы-register) | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | book explicitly ties ваш to the вы T–V register, твой to ты |
| его | his | possessive pronoun (invariable) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | doesn't change by gender of the possessed noun |
| её | her | possessive pronoun (invariable) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| их | their | possessive pronoun (invariable) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| диктор | announcer | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | profession nouns default Masculine regardless of referent's sex |
| директор | director | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| председатель | chairman/chair | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| профессор | professor | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| повар | cook | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| инженер | engineer | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| бухгалтер | bookkeeper/accountant | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| тренер | trainer/coach | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| экскурсовод | (tour) guide | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| режиссёр | film/theater director | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| фотограф | photographer | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| редактор | editor | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| врач | doctor | noun (M, profession) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | book's worked example: "хороший врач" ("good doctor") stays Masculine whether the doctor referred to (он/она) is male or female |

## Grammar points

### Agreement vs. Governing; three types of Agreement (p.1)
Russian words relate to each other via two mechanisms: **Agreement** (matching gender/number/
person) and **Government** (a word requiring a specific case on its dependent, covered later in
Part 6). Agreement itself splits into Gender, Number, and Person agreement; Part 1 covers Gender
Agreement in the singular specifically — between a noun and the "characterizing words" that
precede it in a noun phrase (long adjectives, adjectival/possessive/demonstrative pronouns,
ordinal numerals, the numeral "one," long participles), plus a fifth agreement type between a
noun/personal pronoun and a short participle/short adjective or a past-tense verb.

### How to establish the gender of a noun from its ending (pp.2-4)
Russian nouns are Masculine, Feminine, or Neuter, and for the large majority the dictionary
(Nominative singular) ending predicts the gender: **consonant or -й → Masculine** (дом, друг,
музей); **-а/-я/-ья/-ия → Feminine** (мама, машина, статья, фамилия); **-о/-е/-ье/-ие → Neuter**
(место, здание, время). The rule has principled exceptions: a small set of -а/-я nouns denoting
male people ("natural masculines" — папа, дедушка, дядя, мужчина) take Masculine agreement
despite the Feminine-looking ending, because Russian gender-agreement for person-denoting nouns
tracks the referent's actual sex, not the surface ending, when the two conflict.

### Soft-sign (-ь) nouns: gender must be learned per word (pp.3-4)
Nouns ending in the soft sign -ь don't predict gender from spelling alone and can be either
Masculine or Feminine; the source gives two decidable sub-rules — nouns denoting male people are
Masculine (гость, водитель, царь), and month names ending in -ь are always Masculine (январь,
февраль) — plus two lexicalized Feminine sub-patterns: "natural feminines" (мать, дочь) and nouns
ending specifically in -знь/-сть/-сь (жизнь, новость, подпись). Beyond these patterns, gender
must simply be looked up per word.

### Replacing nouns by personal pronouns (p.3)
он/она/оно (he-it/she-it/it) substitute for a noun according to its established grammatical
gender, not natural sex — a Neuter noun like место ("seat") is replaced by оно even though a seat
has no natural gender.

### Gender of place names and foreign indeclinable nouns (pp.4-5)
Place names split into two groups: those whose ending formally matches the native Russian
gender-marking system (assigned gender by that ending, e.g. Волга → F, Китай → M), and those that
don't fit any native ending pattern at all (Баку, Сочи, Тбилиси, Хельсинки, Миссури, Таити,
Токио, Онтарио) — these are assigned gender by association with their "generic" category word
(город "city" → M, страна/республика-type → F, озеро "lake" → N), not by their surface form.
Separately, a broader class of foreign-origin indeclinable common nouns (шоссе, радио, метро,
кино, такси, ателье, кафе, бюро, купе, интервью, пальто) are uniformly Neuter — **with the single
flagged exception of кофе ("coffee"), which the source explicitly notes is Masculine** despite
belonging to the same indeclinable-foreign class ("горячий кофе," not *"горячее кофе").

### Adjective gender agreement and the three masculine adjective-ending classes (pp.5-7)
Adjectives are cited in dictionaries in the Masculine form, with three possible masculine
endings — **-ый** (новый, известный), **-ой** (большой, плохой, дорогой), **-ий** (русский,
английский, хороший, маленький, последний). To form Feminine, replace the masculine ending with
**-ая** (новая, большая). To form Neuter, replace with **-ое** (новое, большое, плохое) — **except**
for a subclass of -ий adjectives whose stem ends in -ний/-жий/-ший/-чий/-щий (последний, свежий,
хороший, горячий, настоящий), which take **-ее** instead (последнее, свежее, горячее). A further
irregularity: adjectives in -ний specifically (последний, ранний, поздний) take **-яя**, not -ая,
in the Feminine (последняя, поздняя), unlike ordinary -ий adjectives like русский/финский/
маленький which take regular -ая/-ое (русская, русское).

### Adjectival nouns (pp.6-7)
An "adjectival noun" is a word with adjective morphology functioning as a noun, arising from
omitting an implied noun (e.g. столовая ← "столовая комната," "dining room"; второе ← "второе
блюдо," "second course"). These still qualify like ordinary nouns and take further adjectives
according to their own established gender (большая столовая, "large dining room").

### Possessive pronouns as characterizing words; твой vs. ваш and the T–V distinction (pp.7-8)
мой/моя/моё (my), твой/твоя/твоё (your, informal — tied to ты), наш/наша/наше (our), and
ваш/ваша/ваше (your, formal/plural — tied to вы) all agree in gender with the noun they modify.
его (his), её (her), and их (their) are grammatically invariant — they never change form
regardless of the possessed noun's gender, unlike the other possessives.

### это as a characterizing demonstrative vs. это as an invariant "this is" (p.8)
The source explicitly distinguishes two uses of это: as a gender-agreeing characterizing word
(этот/эта/это, "this," varying by the following noun's gender) versus a fixed, non-agreeing use
meaning "this is / that is / these are / those are" (Это мой дом — "This is my house" — где это
stays это regardless of дом being Masculine). This is flagged by the source as a common learner
confusion point ("Notice!").

### Demonstrative/qualitative/intensifying pronoun set: этот, тот, такой, такой же, самый, тот самый (pp.9-10)
этот = "this" (proximal); тот = "that" (distal, a specific object meant); такой = "such a / this
kind of," also used in exclamatory sentences ("Сегодня такой ветер!" — "It's so windy today!");
такой же = "the same kind as"; самый = "the very / most," combining with long adjectives to form
superlatives (самый большой дом, "the biggest house"); тот самый = "the very same (one already
mentioned)."

### Interrogative pronouns какой and чей (p.11)
какой/какое/какая = "what/which/what kind of," used both as a true interrogative ("Какой у вас
телефон?" — literally "what kind of phone," idiomatically "what's your phone number?") and
exclamatorily ("Какой он человек!" — "What kind of person is he!"). чей/чьё/чья = "whose,"
asking about ownership.

### Emphatic сам, totality весь, and the numeral один as a gender-agreeing characterizing word (p.12)
сам/сама/само ("-self") is an emphatic pronoun that can characterize both nouns and personal
pronouns (он сам, "he himself"). весь/вся/всё means "all/the whole." один/одна/одно ("one/a") is
unusual among cardinal numerals in that it agrees in gender like an adjective (один дом, одна
машина, одно место) — a property the source flags as distinguishing it from higher cardinal
numerals, which don't agree this way (developed further in Part 3+).

### Profession nouns are grammatically Masculine regardless of the referent's sex (p.12)
A closed list of profession/role nouns ending in a consonant or soft sign (диктор, директор,
учитель, председатель, профессор, повар, инженер, бухгалтер, тренер, экскурсовод, режиссёр,
фотограф, редактор, врач) are **exclusively Masculine in form because these occupational roles
were historically male-dominated** — any characterizing adjective stays Masculine even when the
sentence's own subject pronoun is she (Она — хороший врач, "She is a good doctor," not
*хорошая врач*). This is presented as a fixed exception to ordinary sex-tracking gender
agreement, distinct from the "natural masculine" pattern covered earlier in this Part.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `datasets/00_Reference_Extraction_Spec.md`.
