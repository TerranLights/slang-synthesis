# English Slang Mechanics — Extraction Checklist

**Purpose:** analyze the actual mechanics of how English slang forms and works, using the
corpus collected in `language_corpus/English/` and the grammar/vocabulary reference in
`source_reference/languages/English Grammar Ebook collection/` and
`source_reference/languages/Old English Language Learning Pack/`. Findings here are what eventual
synthesis work (deriving Modern Hawaiian's English substrate, and this project's own slang-synthesis
work) will be grounded in.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` analyzed and written into its output file · `[ ]` not yet done.

**Driving context:** English became first-priority in this project because the sibling
`TepenianHawaiian` repo is synthesizing a constructed language ("Modern Hawaiian") that starts as a
pidgin of English, Japanese, and Tagalog. See `00_Book_Triage_Catalog.md` for the full triage
history, and the developer's own 2026-10-27 `foremost primary resources/` addition (*The Chicago
Manual of Style*, 16th ed.; *New Oxford Style Manual*) — both now Tier 0 / Wave 0 in that catalog,
with a full chapter-to-page map confirmed and the extraction scope (language-content chapters only,
not the production-mechanics chapters) settled by developer decision the same day.

---

## Morphological typology

**English: predominantly isolating/analytic**, in sharp contrast to every agglutinative language
this project has extracted so far (Korean, Hungarian, Japanese, Tagalog's non-concatenative trigger
system). Grammatical relationships are carried mostly by word order, auxiliary verbs, and a small
closed set of inflectional suffixes (plural `-s`, past tense `-ed`, possessive `-'s`, progressive
`-ing`, comparative `-er`/`-est`) rather than by stacking bound morphemes onto a stem. This matters
directly for the Hawaiian-pidgin sibling project: a pidgin typically strips away the donor
languages' morphology toward a simpler, more isolating grammar — English's own already-low
morphological complexity likely makes it the structurally simplest of the three donor languages to
absorb into a pidgin base. No morpheme-breakdown convention is needed for most English vocabulary
extraction; reserve it for genuinely compound/derived forms where an atomic gloss would hide real
structure (e.g. un-believ-able, un-friend-ly). See `00_Book_Triage_Catalog.md` for the full note.

---

## Output files — Markdown, sharded by numbered file, not JSON

| Directory | Contents | Numbering |
|---|---|---|
| `established/` | The real English baseline — vocabulary/grammar tables extracted per chapter/section, per `../00_Reference_Extraction_Spec.md` | `001_<label>.md`, `002_<label>.md`, ... |
| `analysis/` | Mechanics findings, one file per mechanism (or closely related group) | `001_<mechanism>.md`, ... |
| `synthesized/` | Derived in-universe slang output | `001_<batch>.md`, ... |

**No `_index.json` manifest to maintain** — this checklist's own `## Output files` table is the
human-readable index. **Per `00_Reference_Extraction_Spec.md`'s concurrency rules: above n=3
concurrent subagents, the checklist update is serialized by the orchestrator after a wave lands, not
done per-subagent.** Individual extraction subagents in this language's Wave 0 were explicitly told
to skip touching this file.

Fill this table in as files are created:

| File | Contents |
|---|---|
| `001_cmos_ch05_grammar_and_usage_pt01.md` | CMOS ch.5 Grammar and Usage (Garner), §5.1–5.19, pp.516–539: intro, parts of speech, nouns through genitive case |
| `002_cmos_ch05_grammar_and_usage_pt02.md` | CMOS ch.5, §5.20–5.43, pp.540–563: noun functional variation, pronouns through personal-pronoun declension |
| `003_cmos_ch05_grammar_and_usage_pt03.md` | CMOS ch.5, §5.44–5.67, pp.564–587: pronoun case/forms, relative pronouns, indefinite pronouns, adjectives |
| `004_cmos_ch05_grammar_and_usage_pt04.md` | CMOS ch.5, §5.68–5.91, pp.588–611: articles, adjective position/degrees, participial/coordinate/phrasal adjectives |
| `005_cmos_ch05_grammar_and_usage_pt05.md` | CMOS ch.5, §5.92–5.115, pp.612–635: adjective-to-other-POS, verbs (transitivity, voice, infinitives, participles, gerunds) |
| `006_cmos_ch05_grammar_and_usage_pt06.md` | CMOS ch.5, §5.116–5.139, pp.636–659: verb mood/tense/agreement, conjugation (incl. AmE/BrE -ed/-t split) |
| `007_cmos_ch05_grammar_and_usage_pt07.md` | CMOS ch.5, §5.140–5.163, pp.660–683: modal/auxiliary verbs, adverbs |
| `008_cmos_ch05_grammar_and_usage_pt08.md` | CMOS ch.5, §5.164–5.187, pp.684–707: adverb tail, prepositions (incl. "like" as colloquial conjunction) |
| `009_cmos_ch05_grammar_and_usage_pt09.md` | CMOS ch.5, §5.188–5.210, pp.708–731: prepositions close, conjunctions, interjections open |
| `010_cmos_ch05_grammar_and_usage_pt10.md` | CMOS ch.5, §5.211–5.220 (glossary a–intensive), pp.732–755: interjections close, usage glossary begins |
| `011_cmos_ch05_grammar_and_usage_pt11.md` | CMOS ch.5, §5.220 (glossary intensive–you're)–5.230, pp.756–774: usage glossary close, bias-free language |
| `012_cmos_ch06_punctuation_pt01.md` | CMOS ch.6 Punctuation, §6.1–6.24, pp.775–801: overview through commas w/ parenthetical elements (BrE quotation-style note) |
| `013_cmos_ch06_punctuation_pt02.md` | CMOS ch.6, §6.25–6.51, pp.802–828: comma rules |
| `014_cmos_ch06_punctuation_pt03.md` | CMOS ch.6, §6.52–6.78, pp.829–855: semicolons, colons, question/exclamation marks, dashes open |
| `015_cmos_ch06_punctuation_pt04.md` | CMOS ch.6, §6.79–6.105, pp.856–882: dashes, parentheses, brackets, slashes open |
| `016_cmos_ch06_punctuation_pt05.md` | CMOS ch.6, §6.106–6.126 + Table 6.1, pp.883–905: slashes, quotation marks, apostrophes, lists |
| `017_cmos_ch07_spelling_compounds_pt01.md` | CMOS ch.7 Spelling/Compounds, §7.1–7.22, pp.906–929: plurals, possessives open |
| `018_cmos_ch07_spelling_compounds_pt02.md` | CMOS ch.7, §7.23–7.46, pp.930–953: possessives close, contractions, interjections, word division, ligatures |

| `019_cmos_ch07_spelling_compounds_pt03.md` | CMOS ch.7, §7.47–7.70, pp.954–977: italics/caps/quotation-mark rules, foreign words, letter names, musical notation |
| `020_cmos_ch07_spelling_compounds_pt04.md` | CMOS ch.7, §7.71–7.85, pp.978–998: music dynamics, computer terms, compounds/hyphenation (end of ch.7) |
| `021_cmos_ch08_names_terms_pt01.md` | CMOS ch.8 Names and Terms, §8.1–8.21, pp.999–1024: overview, personal names, titles/offices open |
| `022_cmos_ch08_names_terms_pt02.md` | CMOS ch.8, §8.22–8.47, pp.1025–1050: titles/honorifics/epithets, kinship/ethnic/class terms, place-name conventions |
| `023_cmos_ch08_names_terms_pt03.md` | CMOS ch.8, §8.48–8.73, pp.1051–1076: political/topographical divisions, derived-from-proper-names words, orgs, historical periods open |
| `024_cmos_ch08_names_terms_pt04.md` | CMOS ch.8, §8.74–8.98, pp.1077–1102: historical events, cultural movements, academic subjects, calendar, religious names open |
| `025_cmos_ch08_names_terms_pt05.md` | CMOS ch.8, §8.99–8.124, pp.1103–1128: religious terms close, military terms, ship names, scientific terminology open |
| `026_cmos_ch08_names_terms_pt06.md` | CMOS ch.8, §8.125–8.150, pp.1129–1154: scientific terminology (biology/genetics/geology/astronomy/medicine/physics/chemistry) |
| `027_cmos_ch08_names_terms_pt07.md` | CMOS ch.8, §8.151–8.176, pp.1155–1180: scientific terminology close, brand names/trademarks, titles of works open |
| `028_cmos_ch08_names_terms_pt08.md` | CMOS ch.8, §8.177–8.197, pp.1181–1201: titles of works close (end of ch.8) |
| `029_cmos_ch09_numbers_pt01.md` | CMOS ch.9 Numbers, §9.1–9.21, pp.1202–1224: overview, SI/scientific notation, money open |
| `030_cmos_ch09_numbers_pt02.md` | CMOS ch.9, §9.22–9.44, pp.1225–1247: currency, dates, time of day, numbers with proper names |
| `031_cmos_ch09_numbers_pt03.md` | CMOS ch.9, §9.45–9.66 + Table 9.1, pp.1248–1270: remainder of ch.9 (end of ch.9) |
| `032_cmos_ch10_abbreviations_pt01.md` | CMOS ch.10 Abbreviations, §10.1–10.20, pp.1271–1292: overview, military ranks, titles, academic degrees open |
| `033_cmos_ch10_abbreviations_pt02.md` | CMOS ch.10, §10.21–10.40, pp.1293–1314: firms/agencies, US states/Canadian provinces, countries, months |
| `034_cmos_ch10_abbreviations_pt03.md` | CMOS ch.10, §10.41–10.54, pp.1315–1336: days/time zones, scholarly/biblical/technical abbreviations, SI units open |
| `035_cmos_ch10_abbreviations_pt04.md` | CMOS ch.10, §10.55–10.72, pp.1337–1358: SI units close, astronomy, chemical elements, US customary units (end of ch.10) |
| `036_cmos_ch11_foreign_languages_pt01.md` | CMOS ch.11 Foreign Languages, §11.1–11.20, pp.1359–1382: overview, titles/proper names, Latin-alphabet languages open |

| `037_cmos_ch11_foreign_languages_pt02.md` | CMOS ch.11, §11.21–11.44, pp.1383–1406: Czech/Danish/Dutch/Finnish special chars, full French |
| `038_cmos_ch11_foreign_languages_pt03.md` | CMOS ch.11, §11.45–11.68, pp.1407–1430: German, Hungarian, Italian, Latin, Norwegian, Polish open |
| `039_cmos_ch11_foreign_languages_pt04.md` | CMOS ch.11, §11.69–11.92, pp.1431–1454: Polish close, Portuguese, Romanian, Serbian/Montenegrin, Spanish, Swedish, Turkish/Azeri, transliteration-languages open |
| `040_cmos_ch11_foreign_languages_pt05.md` | CMOS ch.11, §11.93–11.116, pp.1455–1478: transliteration rules, Arabic, Chinese/Japanese, Hebrew open |
| `041_cmos_ch11_foreign_languages_pt06.md` | CMOS ch.11, §11.117–11.140, pp.1479–1502: Hebrew close, Russian, South Asian, Classical Greek open |
| `042_cmos_ch11_foreign_languages_pt07.md` | CMOS ch.11, §11.141–11.154 + Tables 11.1–11.5, pp.1503–1523: Greek close, Old/Middle English, ASL (end of ch.11) |
| `043_cmos_ch13_quotations_dialogue_pt01.md` | CMOS ch.13 Quotations and Dialogue, §13.1–13.25, pp.1605–1631: overview, permissible changes, quotations-in-text, poetry open |
| `044_cmos_ch13_quotations_dialogue_pt02.md` | CMOS ch.13, §13.26–13.52, pp.1632–1658: poetry close, speech/dialogue/conversation, ellipsis mechanics open |
| `045_cmos_ch13_quotations_dialogue_pt03.md` | CMOS ch.13, §13.53–13.79, pp.1659–1685: ellipses, interpolations, citing sources, foreign-language quotations (end of ch.13 — last CMOS chunk) |
| `046_oxford_ch21_us_british_english.md` | Oxford ch.21 **US and British English**, pp.425–440: flagship AmE/BrE contrast chapter, 5 tables + full grammatical/syntactic catalog, every entry individually region-tagged |
| `047_oxford_ch03_spelling_hyphenation.md` | Oxford ch.3 Spelling and Hyphenation, pp.66–86: British spelling rules, inflection, hyphenation, word division |
| `048_oxford_ch04_punctuation.md` | Oxford ch.4 Punctuation, pp.87–111: full punctuation system, non-redundant supplement to CMOS ch.6 |
| `049_oxford_ch05_capitalization.md` | Oxford ch.5 Capitalization, pp.112–124: full chapter, first British-English source in this language's corpus |
| `050_oxford_ch06_names.md` | Oxford ch.6 Names, pp.125–144: personal names (UK peerage, 13-language naming survey), place names, postal conventions |
| `051_oxford_ch09_quotations_direct_speech.md` | Oxford ch.9 Quotations and Direct Speech, pp.178–191: explicit AmE/BrE quotation-mark-order and terminal-punctuation contrast |
| `052_oxford_ch10_abbreviations_symbols.md` | Oxford ch.10 Abbreviations and Symbols, pp.192–203: non-redundant supplement to CMOS ch.10 |
| `053_oxford_ch11_numbers_dates.md` | Oxford ch.11 Numbers and Dates, pp.204–222: full chapter, cross-referenced against CMOS ch.9 |
| `054_oxford_ch12_languages_pt01.md` | Oxford ch.12 Languages, §12.1–12.8.7, pp.223–246: Arabic, Chinese, Dutch/Afrikaans, French, Gaelic/Irish/Scots Gaelic, German, Greek open |
| `055_oxford_ch12_languages_pt02.md` | Oxford ch.12, §12.8 close–12.20 (partial), pp.247–270: Greek close, Hebrew, Italian, Japanese, Latin, Old/Middle English, Portuguese, Russian, Scandinavian, Slavonic languages, Spanish, Welsh, Yiddish opens (cut off mid-section — see known gap below) |

**Wave 0 status: COMPLETE — all 55/55 chunks landed, 2026-10-27.** CMOS pp.516–1685 (chs.5–11,
13) and New Oxford Style Manual's language-content chapters (ch.21, chs.3–6, 9–12) are now fully
extracted into `established/`. 18,386 lines total.

**Known non-blocking gap** (same honest-partial-completion discipline as every other language in
this project): Oxford ch.12 "Languages" §12.20 (Yiddish) is cut off mid-paragraph at the end of
chunk 055's assigned page range (p.270); chapter 13 ("Law and Legal References," out of scope)
begins shortly after. The gap is at most a few pages of one language's entry in a chapter that's
already a non-structural reinforcement reference for this project's purposes — not prioritized for
a follow-up dispatch unless a future need specifically wants it.

**Waves A and B status: COMPLETE, 2026-10-27.** All 35 items of the original pre-Wave-0 plan are
now done except item 2 (`057`, excluded — see below). 259 files total in `established/`. Full
per-file breakdown lives in each book's own files' coverage notes and in
`00_RESUME_HERE.md`'s now-historical Wave A/B tables; this table summarizes by source book rather
than by every numbered part, since several books split into 7-19 parts each.

| File prefix | Source | Parts | Notes |
|---|---|---|---|
| `056` | Cambridge Grammar In Use (Murphy, UK ed., .doc) | 29 | British English; genuinely non-redundant vs. CMOS/Oxford (usage-choice teaching, not structural definition) |
| `057` | ~~Comprehensive Grammar[A4].pdf~~ | — | **EXCLUDED** — misfiled Yip & Rimmington *Chinese: A Comprehensive Grammar*, not English. See note below. |
| `058` | Function-based Grammar Vol I (Givón) | 3 | theoretical/functional grammar, disjoint from CMOS/Oxford |
| `059` | Function-based Grammar Vol II (Givón) | 3 | continues Vol I; disjoint syntactic territory (complementation, voice, relativization, focus, speech acts) |
| `060` | When Bad Grammar Happens to Good People | 14 | 175 numbered usage errors; several live register-change case studies flagged |
| `061` | Beyond Snobbery | 1 | short register-attitude essay |
| `062` | Grammar for the Utterly Confused | 1 | same author as `064`; heavily trimmed as redundant |
| `063` | Grammar Workbook for Dummies | 6 | includes a dedicated 2006 slang-register chapter |
| `064` | Complete Idiot's Guide to Grammar & Style | 2 | flagged 3 future slang-dictionary acquisition leads (Chapman, Partridge, DARE) |
| `065` | Grammar and Usage for Better Writing | 2 | heavily trimmed as redundant; paragraph-rhetoric content kept in full |
| `066` | New Grammar Practice (pre-int) | 7 | foundational; one source-PDF page-17 gap noted |
| `067` | Basic English Grammar Bk1+Bk2 (Azar) | 2 | explicitly American; novel content despite beginner level (direct/indirect speech system) |
| `068` | Grammar in Use, US ed. (Murphy, vision) | 9 | scan contains only reference pages, not exercise pages (gotcha) |
| `069` | Grammar Practice Upper-Intermediate (vision) | 11 | clean scan, no marginalia |
| `070` | Essential Grammar Supplementary Exercises (vision) | 1 | near-zero open-class vocabulary; topic-map style extraction |
| `071` | Longman Grammar Practice Intermediate (vision) | 19 | resumed after a usage-limit interruption; 3 pages confirmed corrupted/unrenderable by 4 tools, documented not silently skipped |
| `072` | History of English: A Student's Guide (Singh) | 5 | Singlish morphosyntax case study (flagship) |
| `073` | The English Language: A Historical Introduction (Barber/Beal/Shaw) | 9 | 5-way Luke 15 comparative passage; Nigerian Pidgin specimen |
| `074` | The Germanic Languages (Routledge) | 3 | ch.18 "Germanic Creoles" — pidgin/creole lexicon-building mechanics, directly relevant to slang-synthesis and Hawaiian work |
| `075` | The Syntax of Early English | 3 | V2 loss, OV→VO, grammaticalization (*have to*, Jespersen's Cycle) |
| `076` | Beginning Old English | 13 | þ/ð/Þ cipher confirmed book-wide (þ→ƒ, ð→ê, Þ→∏); 4 full OE primary texts (Cynewulf and Cyneheard, Beowulf extract, full Battle of Maldon, full Dream of the Rood) + paradigm-table appendix |
| `077` | Old English: A Linguistic Introduction (Hogg) | 4 | þ/ð cipher does NOT recur here; dialect-labeled primary texts (Northumbrian/Mercian/Kentish/WS) |
| `078` | Reading Old English Texts | 2 | oral-formulaic theory, Kuhn's First Law; no cipher found |
| `079` | An Introduction to Old English (Hogg) | 7 | first OE grammar extraction at dispatch time (076 hadn't landed yet); context-dependent þ/ð garble (new cipher variant) |
| `080` | A Critical Companion to Beowulf | 3 | compounding as primary poetic word-formation engine (103 compounds, 5 roots) |
| `081` | Old English Literature: A Short Introduction (Donoghue) | 2 | Northumbrian Cædmon's Hymn + Ruthwell Cross excerpts |
| `082` | The Poetics of Old English (Beechy) | 1 | quantified register case study (*folde* vs. *eorðe*, 257 attestations) |
| `083` | From Old English to Standard English | 11 | **flagship**: 9-way Matthew 26:69-75 comparison OE→ModE→Bislama (real pidgin) |
| `084` | An Old English Grammar (Quirk & Wrenn) | 7 | dense classical reference grammar; two-pages-per-scan-spread gotcha |
| `085` | Old English and Its Closest Relatives (Robinson) | 4 | comparative classification; "that" < paratactic demonstrative reanalysis |
| `086` | Teach Yourself Old English (Atherton) | 8 | Old Norse loanwords organized by semantic domain |
| `087` | Beowulf (Black Cat, graded reader) | 1 | low-yield as expected; a few genuine OE items + kenning/alliteration notes |
| `088` | The Grammar of English Grammars (Goold Brown, 1851) | 10 | 19th-c. American prescriptive grammar; Brown's own 1851 "improper"/slang term list |
| `089` | A Concise Anglo-Saxon Dictionary | 1 | dictionary-scale, sampled not exhaustive; explicit OE dialect markers (N/M/A/NG) |
| `090` | A Guide to Old English (Mitchell & Robinson, via embedded .doc images) | 1 | recovered via byte-level JPEG extraction from a "textless" .doc; first real OE teaching-grammar baseline |

## `057` — excluded, not extracted

`Comprehensive Grammar[A4].pdf`, named in the original 2026-10-26 triage as an English functional
grammar, is actually **Yip & Rimmington's *Chinese: A Comprehensive Grammar*** (Routledge), misfiled
in the `English Grammar Ebook collection` folder — its chapter titles pattern-match English grammar
terminology, but the content is Mandarin grammar written in English. Not extracted as English. Open
decision: leave excluded, relocate the file to a Mandarin source folder, or extract it separately as
Chinese if this project ever does deeper Mandarin work. `00_Book_Triage_Catalog.md`'s Wave 1 list
still needs a correcting note.

## Next steps

1. Run `/graphify datasets/English` for the first time.
2. Decide `057`'s disposition (above).
3. Per [[hawaiian_language_priorities]], consider Ilocano/Cantonese next (both triaged 2026-10-26,
   neither extracted).

**Gotcha confirmed repeatedly across this wave, worth promoting to `00_Reference_Extraction_Spec.md`:**
this CMOS PDF consistently renders non-ASCII characters as UTF-8-bytes-read-as-Latin-1 mojibake
(e.g. "MahÃbhÄrata" for "Mahābhārata", "Ã—" for "×", "Â£"/"â‚¬" for "£"/"€") — confirmed independently
across at least 15 of the 36 chunks so far, always recoverable by cross-referencing the source's own
surrounding context (a spelled-out form, a known proper name, a visible numeral). A small number of
individual characters were flagged `low_confidence` rather than guessed when context didn't resolve
them cleanly. Distinct from the already-documented cp1251-as-latin1 Cyrillic variant — same
underlying mechanism (UTF-8 bytes decoded as a single-byte charset) but on UTF-8 source text, not
Windows-1251 source text.

---

## Field/column conventions

Same shared conventions as every other language in this project — see
`../00_Reference_Extraction_Spec.md` (coverage rule, copyright discipline, output format, column
rules), `../00_Usage_Tier_Taxonomy.md`, `../00_Historical_and_Geographic_Context_Guide.md`, and
`../00_Word_Concept_and_Morphological_Typology_Guide.md`.

## Graphify

Not yet run for this language — defer until Wave 0 (and any later waves) land. **Mandatory: `cd` into
`datasets/English/` first, never run from the repo root.** Individual extraction subagents must
never run `graphify` themselves (confirmed repeat-risk bug — see `../00_Reference_Extraction_Spec.md`).

## Mechanisms examined

- [ ] *(none yet — extraction in progress)*

## Suggested next-session order

1. Finish Wave 0 extraction (CMOS + New Oxford Style Manual language-content chapters).
2. Serialize this checklist's Output files table once Wave 0 lands.
3. Proceed to Wave 1 (the original `secondary resources/` 21-file set, per `00_Book_Triage_Catalog.md`).
