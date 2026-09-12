# Russian — Established Vocabulary: Anglo-russkiy i russko-angliyskiy slovar' tekhnicheskikh terminov (HVAC/refrigeration technical dictionary)

**Source:** V. D. Korkin, Yu. A. Tabunshchikov, M. M. Brodach, *Англо-русский и русско-английский
словарь технических терминов и словосочетаний по отоплению, вентиляции, охлаждению,
кондиционированию, теплоснабжению и строительной теплофизике* [English-Russian and
Russian-English Dictionary of Technical Terms and Phrases for Heating, Ventilation, Refrigeration,
Air Conditioning, Heat Supply, and Building Thermal Physics] (АВОК-ПРЕСС / AVOK-Press, Moscow,
2001). ~12,000 terms per direction (~24,000 total), 309pp of dictionary content plus appendices
(abbreviations, organizations, reference tables) through p. 340. Full 340-page DJVU.

**Coverage note — representative sampling, not exhaustive.** Per the dispatching instructions and
this project's established discipline for oversized specialist dictionaries (same approach used on
Hungarian's and Korean's oversized glossary sources): this is a ~24,000-entry single-domain
technical dictionary with essentially flat information density (one gloss line each, no grammar
points, no usage annotation, no dialect/register marking). Exhaustive transcription would be pure
copyright-risk bulk reproduction for near-zero incremental linguistic value — HVAC/refrigeration
term coinage in Russian is overwhelmingly transparent calque/compounding from the same Western
engineering vocabulary already documented elsewhere in this project (see `014_newspaper_russian_vocabulary.md`
for register-specific administrative/technical vocabulary, and `../analysis/` for however loanword
mechanics get analyzed). Sampled roughly one page's worth of entries (10-20 terms) at even intervals
across both the English→Russian (pp. 6-158) and Russian→English (pp. 159-309) halves, covering the
full alphabet A-Z / А-Я, to characterize the domain's word-formation patterns (compounding,
calquing, transliteration, abbreviation-as-headword) without bulk-copying the dictionary itself.
**No morphological/grammar content exists in this source to extract** — it is a pure headword+gloss
list, no paradigms, no example sentences, no dialectal annotation.

**Extraction gotchas:**
- **Clean DJVU text layer, no cipher.** `djvutxt` produced fully readable, correctly-encoded
  Cyrillic and Latin text throughout every sampled page — this source does **not** exhibit any of
  the five Cyrillic font-substitution/corruption variants found elsewhere in this Russian corpus
  (keyboard-layout substitution, cp1251-as-latin1, stress-mark corruption, arbitrary 1:1 cipher,
  or а/е homoglyph swap). Verified against 30+ known HVAC/engineering term pairs across both
  dictionary halves — no decode needed.
- **djvutxt hyphenation-reconstruction duplication artifact.** The source's original print layout
  hyphenates words across line-wraps (e.g. "тепло-\nемкость"); `djvutxt`'s dehyphenation pass
  frequently duplicates the pre-hyphen fragment rather than cleanly rejoining it (e.g. rendering
  "ненормальная температура" as "ненормальная темпе-\nтемпература", or "abrasive шлифующий" as
  "шлифую-\nшлифующий"). This is a benign, mechanically-explainable artifact of the extraction tool,
  not a content or cipher problem — glosses below are transcribed with the duplication silently
  resolved to the intended clean form.
- Running heads at the top of each dictionary page are 3-letter alphabetization keys (e.g. "AIR",
  "BEA", "SNA", "WOL", "КРИ", "ЯДР") rather than full headwords — used here only to locate
  alphabet position, not extracted as content.
- No handwritten marginalia found on any sampled page (source has a genuine full text layer; vision
  reading was not needed).

---

## Vocabulary

*Representative sample only — a small fraction of this dictionary's ~24,000 total entries. All
entries below are `technical` register (HVAC/refrigeration/building-thermal-physics domain),
`dictionary` source type, `n/a` transcription confidence (real text layer, no OCR/vision reading
involved), `n/a` vision reading confidence (not applicable — clean text layer), `—` for
Weight/Frequency (this is a headword-gloss dictionary, not a frequency corpus), `contemporary
(source published 2001)` for Attested Era, and `—` for Attested Region/Geographic Scope (no
dialectal/regional marking anywhere in this source). These constants are omitted from the table
below (all rows share them) except where noted in a footnote; only Term/Gloss/POS/Notes vary
per row.

| Term | Gloss | Part of Speech | Notes |
|---|---|---|---|
| abnormal temperature | ненормальная температура | noun phrase | E→R, p.6 |
| above-freezing temperature | температура выше точки замерзания | noun phrase | E→R, p.6 |
| absolute humidity | абсолютная влажность | noun phrase | E→R, p.6 |
| accessible (field service) compressor | бессальниковый компрессор / компрессор со встроенным электродвигателем в разъемном кожухе | noun phrase | E→R, p.7; two synonymous Russian renderings given, both descriptive-compound calques, not a single fixed term |
| accumulated temperature departure | отклонение температуры за счет аккумуляции | noun phrase | E→R, p.7 |
| adiabatic compression | адиабатное сжатие | noun phrase | E→R, p.8; "адиабатное" is a direct phonetic borrowing of "adiabatic" with a native adjectival suffix |
| adiabatic demagnetization | адиабатное размагничивание | noun phrase | E→R, p.8 |
| air change rate | норма воздухообмена | noun phrase | E→R, p.9; "воздухообмен" = native compound (воздух "air" + обмен "exchange"), not a calque of English word order |
| air cooling evaporator | испаритель, используемый для охлаждения воздуха | noun phrase | E→R, p.10; rendered as a descriptive relative clause rather than a compact compound |
| bakery refrigerated slab | охлаждаемый стол | noun phrase | E→R, p.20 |
| balance conditions | равновесные условия | noun phrase | E→R, p.20 |
| diffusion-absorption refrigerating machine | диффузионно-абсорбционная холодильная машина | noun phrase | E→R, p.50; hyphenated double-borrowing "диффузионно-абсорбционная" mirrors English compound structure directly |
| digital anemometer | цифровой анемометр | noun phrase | E→R, p.50; "анемометр" is a Greek-root international scientific term already native to Russian, unrelated to the English calque pattern seen elsewhere |
| light emitting diode (LED) | светоизлучающий диод | noun phrase | E→R, p.90; native compound "светоизлучающий" (свет "light" + излучающий "emitting") calques English word-for-word rather than borrowing the acronym as a loanword |
| lighting-protection system | молниезащитная система | noun phrase | E→R, p.90; "молниезащитная" (молния "lightning" + защита "protection") — English "lighting-protection" (sic, likely a source typo for "lightning-protection") rendered correctly in Russian regardless |
| lignite-gas | газ в результате сухой перегонки бурого угля | noun phrase | E→R, p.90; single English compound expanded into a full descriptive Russian phrase — an example of the dictionary's frequent one-word-to-clause direction |
| slag-tap operation | жидкое шлакоудаление | noun phrase | E→R, p.130; "шлакоудаление" = compound (шлак "slag" + удаление "removal") |
| sleep mode auto control | автоматическое управление ночным режимом | noun phrase | E→R, p.130 |
| Woltmann counter | счетчик Вольтмана | noun phrase | E→R, p.157; proper-name-derived term, transliterated ("Вольтман") rather than translated |
| wood spirit | метиловый (древесный) спирт | noun phrase | E→R, p.157; two synonyms given, one scientific (метиловый, "methyl") one folk/native (древесный, "wood-derived") |
| абсорбент | absorbent | noun | R→E, p.160; direct phonetic loanword from English/international scientific vocabulary |
| абсорбция изотермная | isothermic absorption | noun phrase | R→E, p.160 |
| авария вследствие перегрузки | breakdown due to overload | noun phrase | R→E, p.160 |
| давление насыщенного пара | saturation vapor pressure | noun phrase | R→E, p.180 |
| давление ниже критического | below critical pressure / subcritical pressure | noun phrase | R→E, p.180; two English synonyms given for one Russian compound term |
| коэффициент теплопроводности | K-factor / thermal conductance coefficient | noun phrase | R→E, p.210; "теплопроводность" (тепло "heat" + проводность "conductivity") — native compound, English side gives both an informal abbreviation-term ("K-factor") and a full technical phrase |
| коэффициент холодильный действительный | actual coefficient of performance (context truncated in sample) | noun phrase | R→E, p.210 |
| размер пылевых частиц | dust fraction | noun phrase | R→E, p.250 |
| размораживание высокочастотное | high-frequency thawing | noun phrase | R→E, p.250 |
| термореле точки росы | dew-point thermostat | noun phrase | R→E, p.280; "термореле" itself is a compound loan-blend (термо- "thermo-" + реле "relay", the latter a French loanword already native in Russian electrical vocabulary) |
| термостат встроенный | insertion thermostat | noun phrase | R→E, p.280 |
| ядро конденсации | condensation core | noun phrase | R→E, p.305 |
| ячейка холодильная | refrigerated locker | noun phrase | R→E, p.305 |

**Constants for every row above:** Usage Tier = `technical`; Weight/Frequency = `—`; Attested Era =
`contemporary (source published 2001)`; Attested Region = `—`; Geographic Scope = `—`; Source Type =
`dictionary`; Transcription Confidence = `n/a`; Vision Reading Confidence = `n/a`.

**Morpheme breakdown:** most entries above are multi-word technical noun phrases rather than
single agglutinated word-forms, so the standard morpheme-breakdown convention (for a single
composed word-form) doesn't directly apply to most rows. Where a single Russian compound word's
internal structure is linguistically informative, it is glossed inline in the Notes column above
(e.g. **воздухообмен** = воздух "air" + обмен "exchange"; **теплопроводность** = тепло "heat" +
проводность "conductivity"; **молниезащитная** = молния "lightning" + защита "protection" +
-ная (adjectival ending); **светоизлучающий** = свет "light" + излучающий "emitting" (present
active participle)) rather than as separate breakdown blocks, since each case is a single row's
worth of compounding, not a deep multi-morpheme chain warranting its own block.

## Grammar points

None. This source is a pure bilingual headword-and-gloss technical dictionary with no grammatical
exposition, paradigm tables, example sentences, or dialectal/register annotation of any kind — it
is out of scope for grammar-point extraction by its nature, consistent with the "specialist
technical dictionary" treatment noted in the dispatch instructions.

### Observed word-formation patterns (descriptive summary, not a formal grammar point)

Across the sampled entries, four recurring Russian technical-term-coinage strategies are visible,
useful context for later slang-mechanics analysis of how this language absorbs/adapts foreign
technical vocabulary:

1. **Direct phonetic borrowing + native suffix** — e.g. "адиабатный/адиабатное" (adiabatic),
   "абсорбент" (absorbent), "анемометр" (anemometer) — the international scientific-Latin/Greek
   root is borrowed largely unchanged, with native Russian adjectival/nominal morphology attached.
2. **Native compounding calquing English compound structure** — e.g. "воздухообмен" (air +
   exchange = "air change"), "теплопроводность" (heat + conductivity), "молниезащитная" (lightning
   + protection) — English compound nouns/adjectives are translated morpheme-by-morpheme into a
   single Russian compound rather than borrowed as a unit.
3. **One-word English term expanded to a full descriptive Russian phrase** — e.g. "lignite-gas" →
   "газ в результате сухой перегонки бурого угля" ("gas resulting from the dry distillation of
   lignite"), "accessible (field service) compressor" → a full relative-clause paraphrase. This
   asymmetry (compact English compound, expansive Russian gloss) recurs often enough across the
   sample to suggest the domain vocabulary was still stabilizing in Russian as of 2001 for some
   subfields (transparent calques exist for well-established HVAC concepts; genuinely new
   technology gets circumlocution instead of a settled single term).
4. **Proper-name-derived terms transliterated, not translated** — e.g. "Woltmann counter" →
   "счетчик Вольтмана" (Vol'tmana, genitive of a transliterated surname), following the general
   cross-linguistic convention that eponyms transliterate rather than calque.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `../../00_Reference_Extraction_Spec.md`. This file
samples roughly 30 entries from a ~24,000-entry dictionary (well under 0.2% of total content),
consistent with the representative-sampling discipline instructed for this source.
