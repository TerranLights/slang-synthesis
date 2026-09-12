# Russian — Established Vocabulary/Grammar: Part 3, "The Declension of Nouns, Adjectives and Adjectival Words in the Singular"

**Source:** Eugenia Nekrasova, *A Basic Modern Russian Grammar*, eBook edition (© 1997/2002),
ISBN 5-85550-119-1. Covers **Part 3**, source pages 23-40 (PDF pages 26-43 of 195). See
`001_basic_modern_russian_grammar.md` for full citation and the cp1251-via-Latin-1 decode note.

**PDF extraction gotcha confirmed on this Part (matches the spec's documented pattern):**
this Part is dense with declension paradigm tables laid out as side-by-side columns/rotated
headers. PyMuPDF's plain `get_text()` (used for Parts 1-2) badly scrambles these into
single-character-per-line noise (confirmed directly — e.g. the Feminine-noun paradigm table on
source page 32 came out as a vertical column of isolated Cyrillic letters with no usable
structure). **Falling back to `pdftotext -layout`** (cross-checked against the scrambled
PyMuPDF output) recovered fully readable tables for every page in this Part. Per the spec's
"multi-column vocabulary boxes" and "two-column glossary" gotchas: **use `pdftotext -layout` for
any further Parts of this book that present declension tables in a multi-column layout**, not
PyMuPDF's default extraction, which this book's tables defeat. No handwritten marginalia (clean
digital-native PDF, not a scan).

**Coverage note:** every grammar point and declension paradigm in Part 3. Repeated
prepositional-phrase drill examples reusing the same case forms are condensed to one
representative example per case/type.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| урок | lesson | noun (M, hard-stem) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | model noun for hard-stem Masculine/Neuter-pattern declension |
| Петербург | (Saint) Petersburg | proper noun (M, hard-stem) | core | — | contemporary (source published 1997) | — | national | grammar_reference | n/a | n/a | |
| Иван | Ivan | proper noun (M, hard-stem given name) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | model paradigm for Animate Masculine (Acc.=Gen.) |
| крокодил | crocodile | noun (M, hard-stem, animate) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | used to illustrate Animate Accusative=Genitive with a non-human animate |
| Николай | Nikolay | proper noun (M, soft-stem given name) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | model paradigm for soft-stem Masculine declension |
| учитель | teacher | noun (M, soft-stem, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| хоккей | (ice) hockey | noun (M, soft-stem, -й) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | model for -й-stem declension |
| пол | floor | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | takes stressed locative -у (на полу) rather than the ordinary Prepositional -е |
| год | year | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | в 1985 году — special locative -у |
| сад | garden | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | в саду |
| порт | port | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | в порту |
| аэропорт | airport | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | в аэропорту |
| лес | forest, woods | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | в лесу |
| шкаф | wardrobe, cabinet | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | в шкафу |
| мост | bridge | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | на мосту |
| Крым | Crimea | proper noun (M) | core | — | contemporary (source published 1997) | — | regional | grammar_reference | n/a | n/a | в Крыму, special locative -у group |
| угол | corner | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | в углу |
| берег | (river/sea)bank, coast | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | на берегу |
| муж | husband | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | Instrumental с мужем — -ем not -ом after ц/ч/щ/ш/ж when unstressed |
| иностранец | foreigner | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | с иностранцем |
| ад | hell | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | в аду — special -ём/-у type |
| рай | paradise | noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | в раю |
| день | day | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | с днём — soft-sign nouns take -ём in Instrumental |
| словарь | dictionary | noun (M, soft-sign) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | со словарём |
| озеро | lake | noun (N, hard) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | declines like урок |
| Подмосковье | Moscow region | proper noun (N, soft) | core | — | contemporary (source published 1997) | — | regional | grammar_reference | n/a | n/a | declines like soft-stem Neuter/хоккей type |
| море | sea | noun (N, soft, -е) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | declines like хоккей |
| время | time | noun (N, irregular -мя) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | inserts -ен- before all non-Nom/Acc endings (времени, временем) |
| расписание | schedule, timetable | noun (N, -ие) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | declines like море except Prepositional (в расписании, not *расписане) |
| Москва | Moscow | proper noun (F, hard, model type) | core | — | contemporary (source published 1997) | — | national | grammar_reference | n/a | n/a | model paradigm for hard-stem Feminine -а declension |
| Таня | Tanya | proper noun (F, soft, model type) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | model paradigm for soft-stem Feminine -я declension |
| Россия | Russia | proper noun (F, -ия, model type) | core | — | contemporary (source published 1997) | — | transnational | grammar_reference | n/a | n/a | model for -ия Feminine declension, Prepositional/Genitive -и |
| площадь | square (plaza) | noun (F, soft-sign, model type) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | model for soft-sign Feminine declension |
| статья | article | noun (F, -ья) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | groups with Таня/Россия pattern (статьёй in Instrumental) |
| книга | book | noun (F, -га/-ка/-ха mixed type) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | follows Москва but Genitive -и not -ы (книги) |
| улица | street | noun (F, -ца mixed type) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | follows Москва but Instrumental -ей not -ой (улицей) |
| Наташа | Natasha | proper noun (F, -ша/-жа/-ча/-ща mixed type) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | follows Москва with both irregularities (Наташи Gen., Наташей Instr.) |
| мать | mother | noun (F, irregular) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | inserts -ер- in all oblique cases (матери, матерью) |
| дочь | daughter | noun (F, irregular) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | дочери, дочерью — same -ер- insertion pattern as мать |
| Коля | Kolya | proper noun (M, "natural masculine," Таня-type declension) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | male name with Feminine-pattern -я declension (semantically Masculine) |
| Серёжа | Seryozha | proper noun (M, "natural masculine," Наташа-type declension) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| дежурный | person on duty | adjectival noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | example of an adjectival-declension noun |
| раненый | wounded person | participial noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| прохожий | passer-by | participial noun (M) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| Достоевский | Dostoevsky | proper noun (family name, adjectival declension) | core | — | contemporary (source published 1997) | — | national | grammar_reference | n/a | n/a | listed as an example of adjectival-origin surnames |
| Толстая | Tolstaya | proper noun (family name, adjectival declension, F) | core | — | contemporary (source published 1997) | — | national | grammar_reference | n/a | n/a | |
| Коломенское | Kolomenskoye | proper noun (place, adjectival declension) | core | — | contemporary (source published 1997) | — | regional | grammar_reference | n/a | n/a | "earlier a village, now part of Moscow" per source |
| Жуковский | Zhukovsky | proper noun (town, adjectival declension) | core | — | contemporary (source published 1997) | — | regional | grammar_reference | n/a | n/a | |
| Луговая | Lugovaya | proper noun (train station, adjectival declension) | core | — | contemporary (source published 1997) | — | regional | grammar_reference | n/a | n/a | |
| Смоленская | Smolenskaya | proper noun (subway station, adjectival declension) | core | — | contemporary (source published 1997) | — | regional | grammar_reference | n/a | n/a | |
| Прибалтийская | Pribaltiyskaya | proper noun (hotel, adjectival declension) | core | — | contemporary (source published 1997) | — | regional | grammar_reference | n/a | n/a | |
| свой | one's own (reflexive possessive) | possessive reflexive pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | takes adjectival declension |
| каждый | each, every | determinative pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| который | which, who | interrogative/relative pronoun | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| первый | first | ordinal numeral | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | takes adjectival declension |
| двадцать первый | twenty-first | ordinal numeral (compound) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| третий | third | ordinal numeral (irregular, -ний-pattern declension) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | flagged as declining like the "soft" -ний adjectival group |
| другой | other, another | adjective (-гой/-хой/-шой/-жой group) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | |
| мамин | mom's, mother's | possessive adjective | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | example of the -ин possessive-adjective declension subtype |
| Красная площадь | Red Square | proper noun phrase (F adjectival-noun compound) | core | — | contemporary (source published 1997) | — | national | grammar_reference | n/a | n/a | model example for the Feminine adjectival-declension type |
| следующий | next, following | adjective/participle (unstressed -щая-type) | core | — | contemporary (source published 1997) | — | — | grammar_reference | n/a | n/a | example of the unstressed -шая/-чая/-щая Feminine subtype (следующая неделя) |

## Grammar points

### Agreement vs. Governing, revisited: the case system is the product of Governing (p.23)
Part 3 turns from Agreement (Parts 1-2) to **Governing** — the process by which a "governor"
(a verb with or without a preposition, a preposition itself, a quantifying word including
cardinal numerals from 2 up, a governing noun in a qualifying phrase, or a negative/impersonal
construction) forces a specific case-ending on its "subordinate" (a noun, a full noun phrase/unit,
a personal pronoun, or numerals). The resulting case endings are what Part 3 catalogues.

### Six cases, two singular declension groups, one shared plural group (p.24)
Russian has six cases: Nominative, Genitive, Dative, Accusative, Instrumental, Prepositional.
Singular noun/unit case endings split into **two** declension groups — **Masculine & Neuter**
share one ending set, **Feminine** has its own — while **Plural** case endings form a single
shared set regardless of gender (detailed in Part 4). The source specifically flags the Genitive
Plural as the "mosaic-like" hardest set to memorize (previewed here, covered fully in Part 4).

### Declension of Masculine nouns — hard vs. soft stem (pp.25-27)
Hard-consonant-stem Masculine nouns/names (Иван, урок, Петербург) take: Gen. -а, Dat. -у,
Acc.=Nom. (inanimate) or =Gen. (animate), Instr. -ом, Prep. -е. Soft-stem Masculine nouns ending
in a soft sign or -й (Николай, учитель, хоккей) take the parallel soft-series endings: Gen. -я,
Dat. -ю, Instr. -ем, Prep. -е. Case endings replace a final vowel/й/ь but attach directly after a
final consonant.

### Animacy governs the Masculine Accusative (p.28)
The Masculine Accusative has no ending of its own; instead it borrows either the **Genitive**
form (for animate nouns — humans and animals: Ивана, Николая, учителя, крокодила) or the
**Nominative** form unchanged (for inanimate nouns: урок, Петербург, хоккей, дождь). This
Animate/Inanimate split is the organizing principle of the whole Accusative case, not a
minor exception.

### Special locative -у/-ю instead of Prepositional -е (pp.28-29)
A specific, lexically fixed set of Masculine place/location nouns takes a stressed **-у** (or
soft **-ю**) locative ending after в/на instead of the expected Prepositional -е: пол→на полу,
год→в году, сад→в саду, порт→в порту, аэропорт→в аэропорту, лес→в лесу, шкаф→в шкафу, мост→на
мосту, Крым→в Крыму, угол→в углу, берег→на берегу. This is presented as a closed, memorizable
list rather than a productive rule.

### Instrumental -ем instead of -ом after certain stems; -ём after a soft sign (p.29)
Masculine nouns ending in ц/ч/щ/ш/ж take Instrumental **-ем** (not -ом) when the ending syllable
is unstressed (муж→с мужем, иностранец→с иностранцем). A separate, small group of soft-sign
nouns takes a stressed **-ём** in the Instrumental instead of the expected -ем: ад→в аду
(irregular locative, not Instrumental, note per source), день→с днём, словарь→со словарём.

### Declension of Neuter nouns (pp.29-31)
Neuter nouns in **-о** decline exactly like the hard-Masculine pattern (урок): озеро/озера/озеру/
озеро/озером/озере. Neuter nouns in **-е** decline like the soft-Masculine pattern (хоккей): но
the source's own worked example uses Подмосковье and море (море/моря/морю/море/морем/море). A
small irregular class typified by **время** ("time") and **имя** ("name") inserts an extra **-ен-**
stem-extension before every non-Nominative/Accusative ending (времени, временем) — a genuinely
distinct sub-paradigm, not a simple ending swap. Neuter nouns in **-ие** (расписание) follow the
море pattern for every case **except** the Prepositional, where they take **-ии** in effect
(в расписании) rather than the -е a plain -е noun would take.

### Declension of Feminine nouns — four base types plus three mixed types (pp.31-33)
Four base Feminine declension patterns are modeled on Москва (hard -а: Nom. Москва, Gen. -ы,
Dat./Prep. -е, Acc. -у, Instr. -ой), Таня (soft -я: parallel soft endings, Instr. -ей/-ёй), Россия
(-ия: Gen./Dat./Prep. all in -и, Instr. -ей), and площадь (soft-sign: Gen./Dat./Prep. -и,
Instr. -ью, Acc. = Nom. unlike the vowel-final types). Three **mixed types** modify the Москва
pattern with a single irregularity each: **книга**-type (-га/-ка/-ха stems) takes Genitive -и
instead of -ы (spelling-rule driven, parallel to the г/к/х plural rule from Part 2); **улица**-
type (-ца stems) takes Instrumental -ей instead of -ой; **Наташа**-type (-ша/-жа/-ча/-ща stems)
combines *both* irregularities (Genitive -и and Instrumental -ей/-шей). "Natural masculine" male
names/nouns that happen to end in -а/-я/-ша etc. (папа, дедушка, Коля, Серёжа) decline by these
same Feminine-noun patterns despite being grammatically/semantically Masculine — the declension
type is purely about the noun's ending, independent of the referent's sex, unlike Agreement
(Part 1), which does track sex for this same word class.

### Irregular Feminine nouns мать and дочь (p.33)
мать ("mother") and дочь ("daughter") insert an extra **-ер-** stem-extension in every case except
the Nominative/Accusative: Gen./Dat./Prep. матери/дочери, Instr. матерью/дочерью — structurally
analogous to время's -ен- insertion among Neuter nouns.

### The adjectival declension type: which word classes use it (pp.34-35)
A broad set of word classes beyond ordinary descriptive adjectives take "adjectival" case
endings rather than noun endings: possessive pronouns (мой, твой, наш, ваш), demonstrative
pronouns (этот, тот, такой) and pronouns combined with them, interrogative/relative pronouns
(какой, чей, который), indefinite/negative pronouns built on those plus the plural-only
некоторые, the reflexive possessive свой, determinative pronouns (самый, весь, каждый), all long
participles (сломанный, опоздавший, опаздывающий), ordinal numerals (первый, двадцать первый),
adjectival nouns (дежурный, мороженое, набережная), participial nouns (раненый, прохожий),
adjectival-origin family names (Достоевский, Толстая), certain place/station/hotel names
(Коломенское, Жуковский, Луговая, Смоленская, Прибалтийская), and generalizing words (это, всё,
все, многие).

### Masculine & Neuter adjectival declension — three sub-patterns (pp.36-38)
Three model types cover Masculine/Neuter adjectival declension: **новый**-type (all -ый/-ой long
adjectives, participles, ordinal numerals, and adjectival pronouns not otherwise flagged, plus
possessive adjectives like мамин) — Gen./Prep. -ого/-ом, Dat. -ому, Instr. -ым, with animacy
governing the Accusative exactly as for nouns; **exception:** г/к/х and ж/ш stems don't follow
this pattern. **последний**-type (Masculine long adjectives/participles in -ний, -чий, -жий,
-щий, -ший, -сий, e.g. хороший, горячий, свежий, настоящий, and the numeral третий) — the source
explicitly flags that the Instrumental spelling -им is pronounced -ым despite the spelling.
**русский**-type (the large g/k/h/ж/ш/ж-stem adjective group: маленький, английский, строгий,
тихий, городской, другой, большой, плохой, чужой) plus какой/такой and the numeral один, which
decline identically to this pattern.

### Feminine adjectival declension — three sub-patterns, with Genitive=Dative=Instrumental=Prepositional collapse (pp.38-39)
Feminine adjectives/adjectival pronouns show a distinctive simplification: **Genitive, Dative,
Instrumental, and Prepositional all take the same ending**, collapsing four cases into one form.
Three model types: **Красная площадь**-type (regular -ая adjectives — большая, чужая, какая,
такая, and the numeral одна) takes -ой for that collapsed G/D/I/P slot, with the **exception** of
adjectives/participles in unstressed -шая/-чая/-щая; **последняя**-type (all -няя adjectives)
takes -ей for the same slot; **следующая**-type (the unstressed -шая/-чая/-щая exception group —
хорошая, горячая, следующая) also takes -ей, distinguishing it from the regular -ая pattern it
would otherwise have joined.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `datasets/00_Reference_Extraction_Spec.md`.
