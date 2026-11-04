# Belarusian — Book Triage Catalog

**Triage complete, 2026-11-03.** First-ever triage for Belarusian in this project. Belarusian was
**not** on the original `TepenianLanguage` "second-era" handoff list — it turned up unprompted,
sitting inside the same external-drive folder used for the (in-scope) Polish/Ukrainian triage, exactly
as flagged in `datasets/Polish/00_Book_Triage_Catalog.md` §6 and §1 (one more loose Belarusian file
found outside the dedicated folder). Until this pass, Belarusian was one of only three languages in
this entire project with a confirmed **zero-material acquisition gap** (the other two: Czech, Slovak).
**Triage only — no extraction dispatched, nothing written to `established/`.**

## Headline answer: does this close the acquisition gap? — YES, partially

**This folder closes Belarusian's zero-material gap, but only partially.** Real, usable, non-excluded
English-medium material exists: a complete two-volume diaspora-published grammar course (*Fundamental
Byelorussian*, Books 1–2, Pashkievich/Adamovich, 782 pages combined) and a concise modern reference
grammar (*Fundamentals of Modern Belarusian*, Chris Marchant, 110 pages, text layer). That is a real
Tier 1/Tier 4 foundation — not nothing. **But the gap is not fully closed**: there is no English-medium
dictionary, no frequency list, and no dedicated slang/colloquial-register title anywhere in this
12-file harvest. The flagship slang category that this project specifically looks for is **empty** for
Belarusian. Treat this as "acquisition gap narrowed from zero to thin," not "solved."

**Locations (both confirmed):**
1. External drive: `/media/kuroskalacs/Home-Theater/w-lang/Polish and Ukrainian/Polish and Ukrainian
   Language Learning Pack (Vol. 2)/03 Belarusian/` (confirmed mounted) — 11 files, 261MB
2. External drive, loose file found via the sibling Polish triage: `.../Polish and Ukrainian Language
   Learning Pack (Updated)/06 Video Courses+Miscellaneous/Базовый курс классического белорусского
   языка.djvu` — 1 file, 5.11MB

**Raw harvest data:** `.triage_raw.tsv` — **12 rows, one per raw file** (folder, file, size_mb, pages,
text_layer, md5), covering both locations.

**Methodology:** every file got an md5 hash. PDFs got a `pdfinfo` page count and a `pdftotext`
text-layer probe on the first few pages; DJVUs got a `djvused` page count and a `djvutxt` text-layer
probe. Every file that returned no text layer (7 of 9 document files) was individually rendered —
`ddjvu -format=ppm` for DJVU (this environment's `ddjvu` has no native PNG support, so output was
piped through Python/Pillow for PNG conversion), `pdftoppm -png` for PDF — and the title page, verso,
and at least one interior content page were read visually to confirm actual publisher, author, and
instructional metalanguage, not inferred from filename or cover alone. The mp3+JPG pair was identified
by reading its JPG directly (a full lyrics sheet, not a book cover). Duplicates were checked by md5
across all 12 raw files.

---

## The loose 12th file is not independent content — it's a byte-identical duplicate

**`Базовый курс классического белорусского языка.djvu`** (the file named directly in this task,
found via the Polish triage's §1) has md5 `8703c79279629314b9761ec858bd3b1f` — **identical** to
`03 Гавары са мной па-беларуску.djvu` in the dedicated folder. These are not two different Russian-medium
courses; they are the exact same file saved under two different titles (one giving the Belarusian name,
one giving the Russian name of the same book — see §1 below for what it actually is). **The 12 raw
files harvested collapse to 11 unique files by md5** — a detail the Polish triage's brief description
("a Russian-medium Belarusian course") could not have caught without opening the file.

---

## Headline numbers

| | |
|---|---|
| Total files harvested (both locations, incl. duplicate) | **12** |
| **Unique files by md5** | **11** |
| Duplicate copies collapsed out | **1** (the loose file = `03`, byte-identical) |
| **Excluded — wrong metalanguage** | **5** (Russian ×2, German ×1, French ×1, Belarusian-Polish bilingual ×1) |
| **Flagged — Belarusian-medium-of-Belarusian**, needs your ruling | **1** |
| Non-content assets (audio + companion lyrics image) | **2** (1 mp3 + 1 JPG, 1 song) |
| Packed archives | **none found** |
| **Clearly in-scope English-medium candidates** | **3 raw files = 2 distinct titles** (the 2-volume *Fundamental Byelorussian* set + *Fundamentals of Modern Belarusian*) |
| Of which text layer present | **1 (*Fundamentals of Modern Belarusian*)** |
| Of which vision-read required | **2 (both *Fundamental Byelorussian* volumes)** |
| Total pages, in-scope files | **892** (347 + 435 + 110) |
| Total size, in-scope files | **≈190.2MB** |
| Frequency list found | **none** |
| Flagship slang/colloquial-register title | **not found — genuine gap, see §4** |
| Wrong-target-language contamination | **none found** — every file is genuinely about Belarusian |

Check: 5 + 1 + 2(non-content) + 3(in-scope raw) = 11 ✓

---

## 1. EXCLUDE — wrong metalanguage (5 unique files)

**Russian-medium (2 files):**

| File | Note |
|---|---|
| `03 Гавары са мной па-беларуску.djvu` (= the loose duplicate `Базовый курс классического белорусского языка.djvu`) | By Сяржук Аляксандраў & Галіна Мыцык, Minsk, 2000. The title page itself is bilingual — the Belarusian name "Гавары са мной па-беларуску" and the Russian name "Говори со мной по-белорусски" appear side by side, subtitled "Базавы курс клясычнае беларускае мовы / Базовый курс классического белорусского языка" ("Basic course of classical Belarusian"). **Rendered and confirmed**: the actual instructional prose (p.3, "Приглашение к белорусскому разговору" — "Invitation to Belarusian conversation") is written in Russian throughout — a Russian-medium conversational course built around a recurring cartoon-guide character ("Ясь"), 260 pages, 17 lessons. This resolves the task's open question about the loose file: it is not a separate course, it's this exact file under its Russian-language alternate title. |
| `04 Учебник белорусского языка Для самообразования.djvu` | By А.А. Крывіцкі (Krivitsky) & А.І. Падлужны (Podluzhny), Minsk, "Вышэйшая школа" (Vysheishaya Shkola), 1994 — "Textbook of the Belarusian Language for Self-Education." **Rendered and confirmed**: preface (p.3) is Russian-medium throughout, explicitly framing Belarusian's features "исходя из его отличий от русского литературного языка" ("based on its differences from the Russian literary language") — an academic self-study grammar for Russian speakers, 352 pages, 3 blocks (phonetics/orthography, morphology, syntax) plus a thematic Russian-Belarusian glossary. |

**German-medium (1 file):** `05 Kurze belarussische Grammatik in Tabellen.pdf` — **rendered title and
verso pages confirm**: "Kurze belarussische Grammatik in Tabellen für deutschsprachige Studenten"
("Concise Belarusian Grammar in Tables for German-speaking Students"), by Claudia Hurtig, Minsk,
"Technalohija," 2001 — 91 pages, a genuine German-medium pedagogical grammar reference (tabular format),
same "serious reference, wrong metalanguage" pattern as the Kazakh and Polish sibling triages hit.

**French-medium (1 file):** `06 Parlons Biélorussien Langue et culture.djvu` — **rendered and
confirmed**: by Virginie Symaniec & Alexandra Goujon, part of L'Harmattan's "Collection Parlons..."
series (directed by Michel Malherbe, the same series whose catalog page lists dozens of sibling
titles — *Parlons ukrainien*, *Parlons géorgien*, *Parlons mongol*, etc., confirming this is the
well-known real academic series, not a one-off). 371 pages, French-medium throughout. **Notably
substantive**: its opening "Avertissement" (p.7, rendered) discusses the post-1991 orthographic-reform
debate (*taraškievica* vs. the Soviet-era *narkamaŭka*) and the *trasianka* phenomenon (Belarusian-
Russian — and sometimes Belarusian-Russian-Polish or Belarusian-Russian-Lithuanian — code-mixing) in
real sociolinguistic depth. A genuinely rich language-and-culture reference, excluded purely on
metalanguage grounds, parallel to the Kazakh triage's French-medium INALCO manual.

**Belarusian-Polish bilingual, no English (1 file):** `08 Слоўнік для дзяцей Słownik dla dzieci.pdf` —
**rendered and confirmed**: by Валерыя Ждановіч (Valeryia Zhdanovich), a genuine **Belarusian-Polish /
Polish-Belarusian children's thematic dictionary** ("Слоўнік для дзяцей / Słownik dla dzieci,
беларуска-польскі / польска-беларускі, białorusko-polski / polsko-białoruski"), 288 pages, 1000 numbered
thematic entries across 17 topic chapters, with dual alphabetic indexes (Belarusian and Polish). The
"how to use this dictionary" instructions appear twice — once in Belarusian ("Дарагі чытач"), once in
Polish ("Drogi Czytelniku") — confirming the bilingual-but-not-English structure the filename's
odd Belarusian/Polish title mashup suggested. Excluded on metalanguage grounds like every other
non-English item here, but flagged distinctly since it's a real, well-constructed bilingual children's
lexicon, not junk.

**No frequency list or frequency dictionary was found anywhere in this harvest.**

---

## 2. FLAGGED FOR YOUR RULING — Belarusian-medium-of-Belarusian (1 file)

**RULING RECEIVED, 2026-11-04** (per `TepenianLanguage/handoffs_to_slang_synthesis/
2026-11-04_native_medium_ruling.md`, citing `TepenianLanguage/DECISIONS.md` D-25 Books written in
the target languages: usage study): *"Books written in target languages are to be used for
studying how the languages are used in practice."* This file is now **in scope as usage
material** — the ruling answers the medium question but not the mechanics: it does not say
when/how to extract it, nor whether output belongs in `established/` or `language_corpus/` (this
project's usage-corpus vs. reference-corpus distinction). **Do not extract on this ruling alone —
wait for the next explicit instruction.** (Worth noting: this would be the single extractable item
that could meaningfully grow Belarusian's still-thin corpus, per the earlier "narrowed from zero to
thin, not solved" assessment.)

Per the task's explicit carve-out, a non-English-medium resource of Belarusian itself is never silently
excluded or silently kept:

- **`02 Гаворым па-беларуску.pdf`** (236p, **text layer**) — **confirmed via `pdftotext`**: "ГАВОРЫМ
  ПА-БЕЛАРУСКУ" ("We Speak Belarusian"), published by the Belarusian State University's Department of
  Modern Belarusian Language (Кафедра сучаснай беларускай мовы), Minsk, 1999, edited by Л.І. Сямешка,
  explicitly subtitled "Вучэбны дапаможнік па беларускай мове для замежных навучэнцаў" ("A textbook of
  the Belarusian language for foreign students"). **The full table of contents (rendered via
  `pdftotext` on pages 4–8) is entirely Belarusian-medium** — topic headers, grammar-point labels, text
  titles, dialogue labels are all in Belarusian, with no English or Russian metalanguage apparatus
  visible anywhere in the TOC. This is a real university-published course explicitly designed for
  foreign learners (likely assuming some prior Slavic-language competence, e.g., international/exchange
  students who already know Russian), but it teaches entirely in the target language rather than through
  English or any other bridge language. Genuinely substantial (236 pages, 5 thematic units covering
  city/transport, shopping, and more per the rendered TOC) — flagged for your ruling rather than silently
  excluded or silently kept, per the task's explicit instruction.

---

## 3. Non-content assets (2 files, 1 song)

- **`09 Дзеці паўночнага ветру.mp3`** + **`09 Дзеці паўночнага ветру.JPG`** — **the JPG was read
  directly and turns out to be a full lyrics sheet, not a book cover.** "Дзеці паўночнага ветру"
  ("Children of the North Wind") is a Belarusian-language song/poem — imagery of home, a grey stone
  dawn, forest and wolves, captivity and freedom, closing with "Блакітны прастор..." ("Blue expanse...").
  **This is not a companion to any book elsewhere in this harvest** — unlike the task's working
  hypothesis, nothing else in the folder shares this title or theme. It reads as a standalone folk/art
  song with its lyrics transcribed to an image file alongside the audio, not a language-course asset.
  Counted, not an extraction target, nothing moved.

---

## 4. Not scheduled — packed archives and bulk usage-corpus material

**Neither found.** No `.rar`/`.zip` archives exist anywhere in this harvest, and no magazine runs,
newspaper archives, or periodical collections exist either — all 11 unique files are discrete course
books, grammars, a dictionary, or a single song.

**No slang/colloquial-register title was found** — the closest thing in the entire harvest is
*Fundamentals of Modern Belarusian* (Chris Marchant) noting, as asides within its grammar exposition,
that certain constructions are "colloquial" or that gerunds "are not commonly used in colloquial
Belarusian" (confirmed via full-text grep) — real but incidental register commentary inside a grammar
reference, not a dedicated slang/idiom source. **This is a genuine, reportable gap**: unlike Kazakh's
sibling triage (which found a flagship *Colloquial Kazakh* course) or Polish's (which found a youth-slang
glossary chapter), Belarusian's harvest has nothing comparable.

---

## 5. What's clearly in scope (3 raw files = 2 distinct titles) — category overview

### 5a. Reference grammars (Tier 1)

- **`07 Fundamentals of Modern Belarusian.pdf`** (110p, **TEXT**) — by Chris Marchant. **Confirmed via
  `pdftotext`**: a 30-chapter English-medium grammar reference covering spelling rules, noun/adjective
  declension (including irregular plurals), personal/possessive/demonstrative/interrogative/relative
  pronouns, numerals, 1st/2nd-conjugation verbs, and more. Contains incidental colloquial-register and
  idiomatic-construction notes throughout (see §4) — the single most register-aware source in this
  harvest, though not a dedicated slang work.

### 5b. Course series (Tier 4)

- **`01 Fundamental Byelorussian Book 1.djvu`** (347p, vision) and **`01 Fundamental Byelorussian Book
  2.djvu`** (435p, vision) — by V. Pashkievich, edited by A. Adamovich, published by the Byelorussian-
  Canadian Coordinating Committee's Publishing Committee, Toronto (Book 1: 1974; Book 2: 1978), printed
  by Harmony Printing Ltd. **Both rendered and confirmed in depth**: the publisher's foreword (both
  volumes) explicitly states the goal of producing "a badly needed bilingual textbook of the Byelorussian
  language," funded in part by the Canadian federal government's Citizenship Branch. **A rendered
  interior lesson page (Book 1, p.2/Unit 1) confirms genuine English-medium instruction** — vocabulary
  glossed in parallel Belarusian/English columns, grammar explanations in English ("THE BYELORUSSIAN
  ALPHABET (NAMES of the LETTERS)," numbered rule explanations), and a later rendered page (Book 1, p.17,
  Unit 3) shows a full dialogue-plus-vocabulary lesson format with English glosses for every entry. This
  is a complete, serious, diaspora-published two-volume grammar-based course — the strongest single
  resource in this harvest and the backbone of the "gap partially closed" finding in the headline answer.
  No dictionary, phrasebook, slang reference, or graded reader exists elsewhere in this harvest to
  complement it.

### 5c. Vocabulary/dictionary, slang, verbs, reading/writing, graded readers — all empty (Tiers 2, 3, 5)

**No English-medium dictionary, no frequency list, no dedicated slang/idiom title, no standalone
verb-conjugation reference separate from the Tier 1 grammar, and no graded-reader/children's-literature
title exist anywhere in this harvest.** The one dictionary present (`08`, §1) is Belarusian-Polish, not
English; the one children's-literature-adjacent item (`09`, §3) is a single song, not a book or reader.
Flag these as clean, total gaps for Belarusian — more severe than most sibling languages' triages in
this project, which typically find at least one vocabulary or slang title even when thin.

---

## 6. Priority tiers

### TIER 1 — reference grammars & academic linguistics (highest value)

*Fundamentals of Modern Belarusian* (Chris Marchant, TEXT, 110p) — the only item here, but a complete
30-chapter grammar with real register awareness.

### TIER 2 — vocabulary, dictionary, idiom & slang

**Empty.** No English-medium dictionary or slang/idiom source exists in this harvest (§5c). The sole
dictionary found (`08 Слоўнік для дзяцей`) is Belarusian-Polish and excluded on metalanguage grounds
(§1).

### TIER 3 — verbs & reading/writing skill-building

**Empty**, separate from what's embedded in the Tier 1 grammar and the Tier 4 course (§5c).

### TIER 4 — course series (lowest priority, highest cost)

*Fundamental Byelorussian* Books 1–2 (Pashkievich/Adamovich, vision, 782p combined) — the largest and
most substantial resource in the harvest by page count, a complete bilingual diaspora-published course.

### TIER 5 — graded readers

**Empty — no dedicated graded-reader or children's-literature material exists for Belarusian in this
harvest** (§5c).

---

## 7. Extraction notes

- **The loose 12th file named in this task's brief is not independent content.** It is byte-identical
  (md5 `8703c79279629314b9761ec858bd3b1f`) to `03 Гавары са мной па-беларуску.djvu` in the dedicated
  folder — the same Russian-medium course saved under its Belarusian-language title in one location and
  its Russian-language title in the other. 12 raw files collapse to **11 unique files**.
- **The zero-material gap is only partially closed.** Real English-medium material exists (*Fundamental
  Byelorussian* 2-volume set, *Fundamentals of Modern Belarusian*), but Tiers 2, 3, and 5 are all
  completely empty — no dictionary, no slang source, no frequency list, no graded reader. If a flagship
  slang/colloquial source matters for this project's purposes, Belarusian still needs a second
  acquisition pass elsewhere; this folder does not supply one.
- **One item needs an explicit ruling before either extraction or exclusion**: `02 Гаворым
  па-беларуску.pdf` (§2), a genuinely Belarusian-medium-of-Belarusian university textbook for foreign
  students, 236 pages, text layer present (so cheap to extract if ruled in-scope).
- **The mp3+JPG pair is a standalone song** ("Дзеці паўночнага ветру" / "Children of the North Wind"),
  not a companion to any book in this harvest, contrary to the task brief's working hypothesis — resolved
  by reading the JPG directly rather than inferring from filename adjacency.
- **No frequency list, no packed archives, and no bulk usage-corpus material exist anywhere in this
  harvest.**
- **No wrong-target-language contamination was found** — every file confirmed Belarusian-subject-matter
  is genuinely about Belarusian; nothing here turned out to be misfiled Russian, Ukrainian, or Polish
  material despite three of the five exclusions being in a non-Belarusian metalanguage.
- Scratch render files (title/content-page PPM/PNG renders for every vision-only file, raw harvest
  working notes) have been deleted from the scratchpad per the project's disk-space instruction; nothing
  was written to the external drive or `source_reference/`.
