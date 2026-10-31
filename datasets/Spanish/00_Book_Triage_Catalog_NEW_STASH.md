# Spanish — Triage Catalog, NEW 16GB STASH (curated folders 01–09)

**Triage complete, 2026-10-25.** Covers the curated folders only. The `additional stash/` literature
and magazine material is **usage-corpus**, catalogued separately in `00_Usage_Corpus_Catalog.md` and
**not** for Phase 1 extraction.

**Location:** `/media/kuroskalacs/Home-Theater/w-lang/Spanish/` (external drive — confirm mounted)
**Raw harvest data:** `.triage_raw.tsv` (144 rows: folder, file, size_mb, pages, text_layer)

## Headline numbers

| | |
|---|---|
| Files in curated folders 01–09 | **144** (142 PDF + 2 DJVU) |
| Total pages | **34,861** |
| Text layer present | 78 |
| Vision-read required | 64 |
| Sparse text layer | 2 |
| **Excluded — wrong metalanguage** | **11** |
| **Excluded — already extracted** | **10** |
| **NET NEW for extraction** | **≈123 files** |

For scale: the existing 59-file Spanish corpus came from a ~189MB source folder. This is ~85× larger.

---

## 1. EXCLUDE — wrong metalanguage (11 files)

Russian-medium. Confirmed by a combined sweep over Cyrillic characters **and** Latin-script language
markers.

- `02.Beginner Courses/Español en 30 dias (Russian).djvu` — 151 p
- `02.Beginner Courses/Practical Course Spanish Grammar for Beginners (Russian).pdf` — 156 p
- `02.Beginner Courses/Spanish Language for Beginners (Russian).pdf` — 169 p
- `02.Beginner Courses/Spanish Language Intensive Course (Russian).djvu` — 144 p
- `02.Beginner Courses/Spanish Phonetics Introductory Course (Russian).djvu` — 90 p
- `02.Grammar Workbooks/Curso Practico Gramatica de Espanol + Exercises (Russian).pdf` — 641 p
- `05.Spanish Vocabulary/1500 Essential Spanish Words (Russian).pdf` — 34 p
- `06.Intermediate-Advanced Courses/Textbook of Spanish Practical Course Advanced Level (Russian).djvu`
- `08.Graded Readers for Learners/Golpe de Telefono испанские рассказы.pdf` — 49 p
- `08.Graded Readers for Learners/Испанский язык в текстах.pdf` — 209 p
- `09.Phrasebooks.../Русско-испанский разговорник.djvu` — 268 p

### Methodological note — this list took three passes to get right

1. **Cyrillic-in-filename** search → found 3 in curated folders. **Insufficient.**
2. **Latin-script "(Russian)" markers** → found 6 more. Only surfaced by dumping the full listing;
   a script-based search cannot see these.
3. **Combined `-P` sweep** → found 2 more still
   (`Practical Course Spanish Grammar for Beginners`, `Textbook of Spanish Practical Course Advanced
   Level`). One of these had been **mis-listed as a legitimate TEXT-layer file** in an earlier pass
   because the display truncated the filename before the "(Russian)" marker.

**Standing rule for every future stash:** filename-script detection alone is never sufficient. Also
grep Latin-script language markers, never truncate filenames when eyeballing a list, and remember the
Korean stash's third variant — an English-sounding title with **no marker at all** and non-target
metalanguage content, catchable only by opening the file. Spot-open anything high-value that survives
both automated checks.

---

## 2. EXCLUDE — already in the existing corpus (10 files)

Verified against `established/*.md` source headers.

| New-stash file | Already extracted as |
|---|---|
| `02.Beginner Courses/Learning Spanish Like Crazy Level 1.pdf` | Level I (Jackson et al.) |
| `02.Beginner Courses/Learning Spanish Like Crazy Level 2.pdf` | Bregstein/Bliss Level II |
| `02.Grammar Workbooks/Spanish Grammar (Schaum's outlines).pdf` | Jané & Silverstein, Schaum's |
| `02.Grammar Workbooks/Practice Makes Perfect Basic Spanish.pdf` | Richmond |
| `02.Grammar Workbooks/Practice Makes Perfect Complete Spanish Grammar.pdf` | Nissenberg |
| `02.Grammar Workbooks/Practice Makes Perfect Advanced Spanish Grammar.pdf` | Vallecillos |
| `04.Spanish Verbs/Practice Makes Perfect Spanish Verb Tenses.pdf` | Richmond, 2nd ed. |
| `04.Spanish Verbs/Practice Makes Perfect Spanish Irregular Verbs.pdf` | Vogt |
| `05.Spanish Vocabulary/Practice Makes Perfect Spanish Vocabulary.pdf` | Richmond |
| `06.Intermediate-Advanced Courses/Colloquial Spanish of Latin America 2.pdf` | Rodríguez-Saona, *The Next Step* |

**Near-misses kept as NEW — do not confuse:**
- `Practice Makes Perfect Spanish Sentence Builder` — *not* in the existing corpus
- `Colloquial Spanish 2` — peninsular; the extracted one is *Colloquial Spanish of **Latin America***

---

## 3. What the existing corpus lacks — drives the priority tiers below

The existing 59 files are almost entirely **self-teaching workbooks and audio-course transcripts**
(Practice Makes Perfect ×5, Learning Spanish Like Crazy ×3 levels, Madrigal, Easy Spanish
Step-by-Step). It contains **no**:

- reference grammars → new stash has **7**
- academic linguistics → new stash has **~8**
- dictionaries → new stash has **5**, two of them large
- graded readers → new stash has **~22**
- phrasebooks / idiom / slang material → new stash has **~19**
- dialect contrast → new stash has **three parallel Rough Guides** (Spain / Mexico / Latin America)

---

## 4. Priority tiers

### TIER 1 — fills a categorical gap (highest value)

**`03.Reference Grammars` — 6 net new, 2,119 p.** The single biggest gap. *A Student Grammar of
Spanish* (Cambridge, 354 p, TEXT), *Modern Spanish Grammar: A Practical Guide* (473 p, TEXT), *The
Big Red Book of Spanish Grammar* (514 p, TEXT), *Spanish: An Essential Grammar* (343 p, TEXT),
*Gramática Didáctica del Español* (272 p, **vision**), *Collins Easy Learning* (163 p, TEXT),
*Webster's New World Handbook* (387 p, **sparse**).

**`07.Intermediate Level Resources` — 16 files, 5,070 p, almost all TEXT.** *Not pedagogical
material* — these are **linguistics monographs**, a category the corpus has none of: *The Syntax of
Spanish* (299 p), *Introducción a la lingüística hispánica* (570 p), *A History of the Spanish
Language* (419 p DJVU + 361 p companion), *The Politics of Language in the Spanish-Speaking World*
(251 p), *The Spanish Language Today* (254 p), *Using Spanish: a guide to contemporary usage*
(503 p), two Cambridge Companions (Spanish / Latin American culture). **Triage separately from
teaching material** — these describe mechanisms rather than drilling forms, which is exactly what
the grammar-logic work needs and what textbooks are worst at.

**`09.Phrasebooks & Dictionaries` — 20 net new, 6,644 p.** Richest folder for the slang work:
*Spanish Among Amigos*, *Spanish in Your Face*, *Berlitz Hide This Spanish*, *The Big Red Book of
Spanish Idioms* (4,000 idioms, 401 p), *Hablar por los codos*, *The Ultimate Spanish Phrase Finder*
(960 p). **Plus the three-way dialect contrast**: Rough Guide **Spain** / **Mexican** / **Latin
American** phrasebooks, same publisher and format — a controlled comparison the corpus cannot
currently make.

### TIER 2 — substantial depth in an existing category

**`02.Grammar Workbooks` — 15 net new.** The complete **Uso de la Gramática Española** series
(Elemental / Intermedio + Key / Avanzado), *Gramática de Uso del Español A1–B2* (291 p), *Gramática
Nivel B2* (260 p), *Temas de Gramática con Ejercicios Prácticos (Nivel Superior)*, *A Spanish
Grammar Workbook* (Blackwell, 374 p), *Modern Spanish Grammar Workbook*, Basic/Intermediate
*Grammar and Workbook* pair.

**`04.Spanish Verbs` — 5 net new, 1,342 p.** *Webster's New World 575+ Spanish Verbs* (722 p),
*The Ultimate Spanish Verb Review and Practice*, *Spanish Verbs Made Simple(r)*, and — worth calling
out — **two books dedicated to the subjunctive** (*Practica Tu Español: El Subjuntivo*, *Tiempo para
Practicar el Indicativo y el Subjuntivo*). The existing corpus's flagship finding was that three
independent sources independently rediscovered the subjunctive as the central difficulty; these are
the first sources in the project devoted to it alone.

**`05.Spanish Vocabulary` — 8 net new, 3,249 p.** *Using Spanish Vocabulary* (797 p), *Using Spanish
Synonyms* (753 p), *Spanish Vocabulary: An Etymological Approach* (655 p — **etymology is a
Phase-5/6 asset**, nothing else in the project covers it), *Must-Know Spanish 4000 Words*,
*Vocabulario Activo* 1–2, *Uso Interactivo del Vocabulario*.

**`06.Intermediate-Advanced Courses` — 11 net new.** *Colloquial Spanish 2* (peninsular), *En Activo:
Practical Business Spanish*, *Español 2000 Nivel Medio*, *Prisma Progresa B1*, *Aula 4 B1*, *Punto
Final C1*, *El Punto en Cuestión*. **Note:** the big multi-level course archives (SUEÑA A1–C1,
En Acción 1–3, VEN 1–3, Linguaphone) are **still packed in .rar** and are not counted in the 144 —
unpacking them is a separate decision.

### TIER 3 — lower priority, but cheap

**`08.Graded Readers` — 22 net new, mostly 10–115 p each, mostly vision-required.** Graded fiction
written *for learners* — so pedagogically controlled rather than authentic. Useful for level-tiered
vocabulary, less so for usage evidence (the real usage corpus is the `additional stash/` literature).

**`02.Beginner Courses` — 18 net new.** Heavy overlap in function with the existing corpus. Pick
selectively: *Camino al Español* (451 p, comprehensive), *Spanish Demystified* (496 p), *Spanish for
Reading* (368 p — reading-specific, unusual angle), *Español En Vivo* (518 p DJVU).

---

## 5. Extraction notes

- **64 of 144 files need vision reading** — no text layer. Budget accordingly; this is the single
  biggest cost driver. The DJVU files (`Uso de la Gramática` ×2, `Español En Vivo`, `A History of the
  Spanish Language`, `Spanish-English Visual Dictionary`) need `ddjvu` rendering.
- **Apply the representative-sampling convention** (as used for Heisig / NTC / Kodansha) to:
  `Diccionario Enciclopédico McGraw-Hill` (**1,831 p**), `Diccionario de Sinónimos-Antónimos` (879 p),
  `The Ultimate Spanish Phrase Finder` (960 p), `Using Spanish Vocabulary` (797 p), `Using Spanish
  Synonyms` (753 p), `Webster's 575+ Verbs` (722 p).
- **`Uso de La Gramatica Espanola Intermedio Key.pdf` is 6 pages** — an answer key. Extract with its
  parent volume or not at all.
- **Scope check:** `08.Graded Readers/El Principito` and `La Celestina` are literature reissued as
  graded readers. Treat as reader material, not as usage corpus.

## 6. Recommended wave structure

1. **Wave 1 — Tier 1 reference grammars + linguistics** (`03` + `07`): ~22 files, ~7,200 p, mostly
   TEXT layer. Highest value per unit cost, and directly feeds the grammar-logic work.
2. **Wave 2 — phrasebooks, idioms, dialect contrast** (`09`): ~20 files. Feeds the slang work;
   extract the three Rough Guides *together* so the dialect comparison is coded consistently.
3. **Wave 3 — grammar workbooks + verbs** (`02.Grammar Workbooks` + `04`): ~20 files, heavier vision
   load.
4. **Wave 4 — vocabulary + intermediate courses** (`05` + `06`).
5. **Wave 5 — graded readers + beginner courses** (`08` + `02.Beginner`), selectively.

**Not scheduled:** the packed `.rar` multi-level course archives. Decide separately whether to unpack.
