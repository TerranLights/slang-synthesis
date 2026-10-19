# Korean — Reference Material Triage Catalog

**Status: full triage complete, 2026-09-09.** Korean is one of the 43 Inner Tepenia GDD
Gini-index high-priority languages (South Korea, ~26M effective) — see `../../LANGUAGE_INDEX.md`.
`source_reference/languages/Korean/` is ~532 MB, 17 real files (16 PDFs + 1 DJVU) across a mix of
top-level files and 3 subfolders, all text-oriented (no audio/video — this folder never had any).

**Tooling note:** several files sit inside subfolders (`Colloquial Korean/`, `Teach Yourself
Korean/`, `The Sounds of Korean - A Pronunciation Guide/`) rather than at the top level — use
`find -printf '%p'` (full relative path), not just `%f` (basename), or numbered-prefix files
inside subfolders get misattributed to the wrong title.

---

## Full file list — triaged

| File | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `04.Basic Korean a grammar and workbook.pdf` | 257 | **Yes** (clean) | **Highest** | Core grammar reference, first of what looks like a graded series (Basic → Intermediate → Continuing, numbered 04/05/07 in this collection). First extraction target. |
| `05.Intermediate Korean a grammar and workbook.pdf` | 289 | **Yes** (clean) | **Highest** | Direct sequel to Basic Korean, same series. |
| `07.Continuing Korean.pdf` | 451 | **Yes** (clean) | High | Third/continuing volume in the same graded series — largest of the three. |
| `11.Using Korean a guide to contemporary use.pdf` | 337 | **Yes** (clean) | **High — register focus** | Title itself signals contemporary/colloquial usage — directly matches this project's stated preference for register-diverse chapters over pure foundational grammar. |
| `12.The Korean language structure use and context.pdf` | 202 | **Yes** (clean) | High | Linguistic-description volume — likely strong for typology profile and structural analysis beyond a teaching grammar. |
| `10.Intermediate college Korean.pdf` | 376 | **Yes** (clean) | Medium-high | Another intermediate-level textbook — likely redundant with Basic/Intermediate Korean's core grammar; apply the non-redundant-supplement pattern. |
| `0.1The Sounds of Korean A Pronunciation Guide.pdf` (in `The Sounds of Korean - A Pronunciation Guide/`) | 141 | **Yes** (clean) | Medium-high | Dedicated phonology reference — pairs with the typology profile the way Siptár & Törkenczy's *Phonology of Hungarian* did for Hungarian. |
| `Teach Yourself Korean.pdf` (in `Teach Yourself Korean/`) | 139 | **Yes** (clean) | Medium-high | Full course, same title-type that worked well for both SCB and Hungarian. A companion 2-page scan (`Pages 110-111 224-225.pdf`, same folder) has no text layer — check whether it's patching pages the main scan is missing/damaged, extract those 2 pages via vision if so. |
| `0.2Korean Through English 1.pdf` | 144 | **Yes** (clean) | Medium | Course book. |
| `0.3Active Korean 1.pdf` | 151 | **Yes** (clean) | Medium | Course book. |
| `15.In Flight Korean.pdf` | 20 | **Yes** (clean) | Low | Very short phrasebook — low yield, quick to finish regardless. |
| `Colloquial Korean.pdf` (in `Colloquial Korean/`) | 143 | No | Medium — vision-read | Course book; a second, apparently different/updated edition sits alongside it (see below) — check for redundancy before extracting both in full. |
| `Colloquial Korean the complete course for beginners.pdf` (in `Colloquial Korean/`) | 289 | No | Medium — vision-read | Longer than the other "Colloquial Korean" file in the same folder — likely a full edition vs. an abridged/older one. Triage which is primary before dispatch. |
| `13.Korean grammar for international learners.pdf` | 230 | No | **High — vision-read** | A dedicated grammar reference despite lacking a text layer; worth the vision-reading cost. |
| `09.Living Language Korean Course.pdf` | 125 | No | Medium — vision-read | Course book. |
| `06.Elementary korean.djvu` | 429 | No | Medium — vision-read | Large course/textbook; djvu, needs `djvutxt`/image-rendering pipeline like SCB and Hungarian's djvu sources. |
| `14.A Korean-English dictionary.pdf` | 962 | No | Medium — vision-read, **sample not exhaustive** | Largest file in the folder by far (222 MB, 962 pages). A pure dictionary — same treatment as Hungarian's *Magyar Szlengszótár* and *Magyar szólások és közmondások*: representative sampling across the alphabet, not full transcription. Dictionary content (not grammar) — flag whether any of it is genuinely slang/informal register once sampled, in which case route it to `language_corpus/Korean/` per the Phase 1/Phase 3 content-type boundary rule. |

**Two apparent duplicate/overlapping titles found, same as prior languages' triage passes:**
- Two "Colloquial Korean" editions in the same subfolder (143pp vs. 289pp) — resolve which is
  primary vs. superseded/abridged before dispatching both.
- The Basic/Intermediate/Continuing Korean trio and Intermediate College Korean likely overlap
  substantially in core-grammar territory — apply the non-redundant-supplement dispatch pattern
  once 2+ of these are extracted, per `../00_Reference_Extraction_Spec.md`.

## OCR/scan status

**6 of 17 files (~35%) have no usable text layer** — lower than SCB's ~56% and Hungarian's ~50%,
but still a substantial minority, consistent with this being the norm rather than the exception
across languages (see `ROADMAP.md` Phase 1).

## Morphological typology (preliminary, per Phase 0 convention)

**Korean: agglutinative.** Grammatical relationships (case, topic-marking, honorifics, tense,
mood, connectives) are marked by stacking particles/suffixes onto a noun or verb stem, broadly
comparable to Hungarian/Japanese/Turkish rather than to English's more isolating/analytic pattern.
Korean additionally has an unusually elaborate **speech-level/honorific system** woven into verb
endings themselves (not just vocabulary choice, as in many European languages) — this is likely to
be a major source of register-relevant slang findings once extraction begins, the same way
Hungarian's te/maga/ön system and Hangul's own agglutinative suffix-stacking mechanisms turned out
to be. Will be refined with a real morpheme breakdown once the first grammar extraction lands.

## Recommended Phase 1 extraction priority order

**Wave 1 — core grammar + register-focused, clean text:**
1. `04.Basic Korean a grammar and workbook.pdf`
2. `05.Intermediate Korean a grammar and workbook.pdf`
3. `07.Continuing Korean.pdf`
4. `11.Using Korean a guide to contemporary use.pdf`
5. `12.The Korean language structure use and context.pdf`

**Wave 2 — remaining clean-text supplements:**
6. `10.Intermediate college Korean.pdf` (non-redundant supplement against Wave 1)
7. `The Sounds of Korean - A Pronunciation Guide/0.1...pdf`
8. `Teach Yourself Korean/Teach Yourself Korean.pdf` (+ the 2-page patch scan)
9. `0.2Korean Through English 1.pdf`
10. `0.3Active Korean 1.pdf`
11. `15.In Flight Korean.pdf`

**Wave 3 — vision-reading:**
12. `13.Korean grammar for international learners.pdf` (highest-value vision-read target — a real
    grammar reference)
13. `Colloquial Korean/` — both editions, resolve redundancy first
14. `09.Living Language Korean Course.pdf`
15. `06.Elementary korean.djvu`
16. `14.A Korean-English dictionary.pdf` (sampled, not exhaustive)

---

## Supplementary stash triage (external drive, 2026-10-19)

**Status: triage complete, extraction not yet dispatched.** A much larger Korean folder (85 files,
3.0GB) was found on the external drive at `/media/kuroskalacs/Home-Theater/w-lang/Korean/`,
organized into 6 category subfolders (Beginners Courses, Intermediate-Advanced Courses, Grammar/
Workbooks/Usage, Dictionaries/Phrasebooks/Vocabulary, Culture/Society/History/Tourism, Video
Courses+Misc) — considerably richer than the original 17-file/532MB corpus already extracted.
Every title checked against the existing `established/` corpus before being marked new.

### Confirmed duplicates of already-extracted sources (skip)

Active Korean 1, Colloquial Korean (both editions), Elementary Korean, Korean Through English 1,
Living Language Korean Course, Teach Yourself Korean, The Sounds of Korean, Basic Korean A Grammar
and Workbook, Intermediate Korean A Grammar and Workbook, Korean Grammar for International
Learners, Using Korean A Guide to Contemporary Usage, The Korean Language Structure Use and
Context, A Korean-English dictionary, In-Flight Korean, Continuing Korean.

**Possible duplicate, needs direct comparison before dispatch**: `Intermediate College Korean.pdf`
(this copy) — the already-extracted copy has a known non-blocking gap (pp.225-376 never covered,
per the Korean Phase 1 completion note) and the same font-cipher-corrupted text layer as before.
Worth checking whether this copy is identical or a cleaner scan before deciding whether it can
close that gap.

### Excluded — wrong metalanguage

El Coreano Basico (Spanish), Manuel De Coréen Volume 1 + both .flac audio files (French), 7
Russian-medium titles under Beginners Courses (Корейский язык Вводный курс / Вон Гван edition /
Начальный курс разговорной речи / Основной курс / Начальный курс корейского языка / Пособие по
корейскому языку для начинающих / Учебник корейского языка Начальный курс), 8 more Russian-medium
titles under Intermediate-Advanced Courses (Uchebnik Koreyskogo Dialoga 1 &amp; 2, Китайские
иероглифы в корейском языке, Корейский язык Курс для продолжающих [both formats], Корейский язык
средний/углубленный уровень, Пособие по переводу, Учебник по иероглифике), Grammaire coréenne
(French), Grammar of Standard Korean (Korean-medium — no English metalanguage), Корейский язык.
Учебное пособие (Russian), Berlitz Корейский разговорник и словарь (Russian), Корейские народные
сказки (Russian-medium duplicate of the English Korean Folk Tales). **Frequently Used Korean
Dialogues 2000 Sentences.pdf** confirmed Chinese-medium (CIP cataloging data, 图书在版编目) despite
its English-sounding filename — excluded on the same grounds.

### Excluded — out of scope (not language-pedagogical/reference, or pure book-list photos)

`00 Book List/` (6 JPG photos of a physical shelf/book list — not extractable content). A Brief
History of Korea, A History of Korea From Antiquity to the Present, An Illustrated Guide to Korean
Mythology, Foods of Korea, Frommer's South Korea Travel Guide, North Korea through the Looking
Glass, The Rough Guide to Seoul (pure history/tourism, no language content). 7 Harry Potter books
in Korean translation (fiction in translation, excluded per this project's standing fiction-
exclusion convention — though flagged as a possible future representative-sample register source
if ever revisited, same way Advanced Tagalog Reader's real magazine articles were used).

### New, in-scope sources (not yet dispatched)

**Flagship finds:**
- **`Dirty Korean Everyday Slang.pdf`** (177pp, clean text) — flagship slang source, direct Korean
  counterpart to Dirty Japanese.
- **`Making Out in Korean.pdf`** (51pp, no text layer) — flagship slang source, direct Korean
  counterpart to Making Out In Japanese/Tagalog.
- **`Let's Learn Korean (Northern Dialect).pdf`** (462pp, no text layer) — a genuine North Korean/
  Northern-dialect regional-variety source, parallel in kind to Japanese's Kinki dialect dictionary
  flagship find.
- **`Korean Honorifics and Politeness in Second Language Learning.pdf`** (329pp, clean text, Lucien
  Brown) — directly register/politeness-focused academic work, high value for slang mechanics.

**Flagship course series** (clean text throughout):
- Integrated Korean Beginning Level 1 &amp; 2 Textbooks (331pp, 348pp) — a well-regarded university-
  press series, genuinely new.
- Korean Level 1 &amp; 2 (Seoul National University Language Education Institute) (306pp, 184pp) +
  Korean Course Seoul University Vol. 2/3/4 (319pp, 348pp, 381pp, clean Hangul text confirmed) — a
  6-volume flagship SNU series spanning beginning through advanced.
- My Korean 1 &amp; 2 (471pp, 509pp, clean text) — large beginner course pair.
- DLI Korean Headstart (490pp) + DLI Korean Headstart Cultural Notes (42pp) — parallel in kind to
  the Tagalog/Japanese Headstart course+cultural-notes pairs already extracted for those languages.
- Korean Advanced Course Volumes I &amp; II (Defense Language Institute) (191pp, 84pp, no text layer).
- College Korean (380pp, Rogers/You/Richards — confirmed genuinely distinct from Intermediate
  College Korean via author/title comparison, not a duplicate).

**Other new, moderate-value sources**: Beginner's Korean (262pp), Essential Korean (118pp) +
Essential Korean CD contents (4pp, low-value track list), Hanyang Korean 1 Grammar &amp; Patterns
(24pp) + Textbook (252pp) + Writing Practice (129pp, likely mostly drill), Korean for Dummies
(387pp, clean text) + Cheat Sheet (2pp, low value), Modern Conversational Korean (378pp, clean
text), Pathfinder in Korean Beginning Student Book (159pp) + Workbook (179pp, clean text) + Low
Intermediate Student Book (210pp) + Workbook (252pp, both DJVU, no text layer), H.B. Lee's Korean
Grammar (117pp), Korean (London Oriental and African Language Library, 266pp) + The Korean
Language (Cambridge Language Surveys, 462pp) — two more academic linguistic-description volumes,
parallel to the already-extracted "The Korean Language Structure Use and Context," likely
substantial non-redundant-supplement candidates given the typically-thin overlap this project has
found between parallel academic grammars. Tense and Aspect in Korean (194pp), A Korean Grammar on
Semantic-Pragmatic Principles (284pp), A History of the Korean Language (348pp, clean text —
typology-grounding value), Collins Korean Phrasebook (129pp), Easy to Learn Korean Language (53pp),
Lonely Planet Korean Phrasebook (308pp, clean text — check for a slang/colloquialism callout
section the way Japanese's Rough Guide phrasebook had one).

**Possible real content, unverified**: `Korean 5 to 12 Integrated Resource Package.pdf` (277pp,
clean text) — a Canadian (British Columbia) K-12 curriculum document; may be administrative/
pedagogy-planning prose rather than a language reference itself, needs a direct look before
committing to extract.

### Recommended next step

This is a substantial new batch (~25 genuinely new sources, two of them flagship slang finds) —
large enough to warrant its own dispatch wave(s) once the user confirms whether to proceed into
extraction now or hold here. Not yet dispatched as of this triage pass.
