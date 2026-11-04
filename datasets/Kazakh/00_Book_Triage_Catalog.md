# Kazakh — Book Triage Catalog

**Triage complete, 2026-11-03.** First-ever triage for Kazakh in this project, per the
`TepenianLanguage` handoff (Kazakh is a "second-era"/Tepenian-stage contributing-language candidate
with a documented Federation presence, Mawson, Temirötkel, but no specific domain idea assigned yet —
"none yet" in the source doc). **Triage only — no extraction dispatched, nothing written to
`established/`.**

**Locations (all four confirmed):**
1. External drive: `/media/kuroskalacs/Home-Theater/w-lang/Kazakh/` (confirmed mounted) — 40 files, 454MB
2. In-repo: `source_reference/languages/Kazakh Language Learning Pack/` — 33 files, part of a combined
   541MB with location 3
3. In-repo: `source_reference/languages/Colloquial Kazakh/` — 3 files (2 PDFs + 1 `.torrent`), part of
   a combined 186MB-labeled pairing with location 2
4. In-repo unsorted: `source_reference/languages/lang transfer bay/Kazakh/` — 6 files

**Raw harvest data:** `.triage_raw.tsv` — **82 rows, one per raw file** (folder, file, size_mb, pages,
text_layer, md5), covering every file in all four locations.

**Methodology:** every PDF/DJVU got an md5 hash, a `pdfinfo`/`djvused` page count, and a text-layer
probe (`pdftotext`/`djvutxt` on the first few pages). Titles for files with a text layer were
confirmed from the extracted title-page text itself. **Every vision-only file was individually
rendered** (`pdftoppm` for PDFs; `ddjvu` piped through a PPM→PNG conversion step for DJVU, since this
environment's `ddjvu` build has no native PNG support) and read visually — title page plus at least
one interior content page, to confirm actual instructional metalanguage rather than trusting a cover
alone. Duplicates were checked by md5 across all 82 files, not by filename or location.

---

## This stash is duplicate-heavy, concentrated almost entirely in the in-repo Learning Pack

**82 total files across all four locations collapse to only 49 unique files by md5 hash — a 40%
duplication rate.** The in-repo `Kazakh Language Learning Pack/` folder (33 files) is almost entirely
a byte-identical copy of files already present on the external drive — of its 33 files, 24 are exact
duplicates of external-drive files, and most of the rest are alternate-named duplicates of a handful
of distinctive items (`Entire-Kazakh-Language-Manual.pdf` = `15 Kazakh Language Manual.pdf`;
`Kazakh-Language-Grammar-Texts-Vocabulary-.pdf` = `16 Kazakh Language Grammar, Texts, Vocabulary.pdf`;
`The-Kazakh-Phrasebook-.pdf` = `25 The Kazakh Phrasebook.pdf`). Any wave planning must dispatch
against the **49-unique-file set**, not the 82-file raw count.

**The two filename-suggested "(1)"-suffix pairs flagged in the handoff are both confirmed real
byte-identical duplicates by md5, not just similarly-named files:**
- `Kazakh Grammar with Affix List (Krippes) (1).pdf` and `Kazakh Grammar with Affix List
  (Krippes).pdf` — identical md5 `53894c34d7e8fe0473cef1bacabb384d`.
- `Kazakh Language (Akhmetova) (1).pdf` and `Kazakh Language (Akhmetova).pdf` — identical md5
  `d1643a9ad0457ee332104f3a1d7082c7`. **This pair is also byte-identical to two further files**
  elsewhere in the harvest: `16 Kazakh Language Grammar, Texts, Vocabulary.pdf` (external drive) and
  `Kazakh-Language-Grammar-Texts-Vocabulary-.pdf` (Learning Pack) — all four are the same 32-page
  Aijan Akhmetova work, the single most-duplicated file in this entire harvest (5 copies).

---

## Headline numbers

| | |
|---|---|
| Total files harvested (all 4 locations, incl. duplicates) | **82** |
| **Unique files by md5** | **49** |
| Duplicate copies collapsed out | **33 (40% duplication rate)** |
| **Excluded — wrong metalanguage** | **20** (Russian ×16, French ×1, German ×1, Turkish ×1, Ukrainian ×1) |
| **Flagged — Kazakh-medium-of-Kazakh**, needs your ruling | **1** |
| Non-content assets (`.torrent` file) | **1** |
| Packed archives not yet opened | **none found** |
| Bulk usage-corpus material | **none found** |
| **Clearly in-scope candidates for Phase 1** | **27 raw unique files = 23 distinct titles** (4 are duplicate-edition/alternate-scan pairs of the same underlying work, not independent content — see §6) |
| Of which text layer present | **15 (56%)** |
| Of which vision-read required | **12 (44%)** |
| Total pages, in-scope unique files | **≈5,220** |
| Total size, in-scope unique files | **≈432 MB** |
| Frequency list found | **none** |
| Flagship slang/colloquial-register title | **found** — *Colloquial Kazakh: The Complete Course for Beginners* (Routledge, Zaure Batayeva) — see §5 |
| Wrong-target-language contamination (Kyrgyz/Karakalpak/other Turkic misfiled as Kazakh) | **none found** |

Check: 20 + 1 + 1 + 27 = 49 ✓

---

## 1. EXCLUDE — wrong metalanguage (20 unique files)

**Russian-medium (16 files)** — every one individually confirmed by rendering its title page and at
least one interior content page (not inferred from the Cyrillic filename alone):

| File | Note |
|---|---|
| `05 Казахский язык. Учебник (Kazakh Language Textbook).djvu` | By К.М. Мусаев — rendered cover, Russian-medium textbook |
| `06 40 уроков казахского языка (40 Lessons of Kazakh).djvu` | By Хадиша Кожахметова — Russian-medium |
| `07 Казахский язык для всех (Kazakh for All).djvu` | By А.Ш. Бектурова & Ш.К. Бектуров — Russian-medium |
| `08 Изучаем казахский язык (We Learn Kazakh).djvu` | **Rendered interior page (p.8)** — purely Russian-medium grammar exposition, no English |
| `08 Изучаем казахский язык (We Learn Kazakh).pdf` | Same title, alternate file format (PDF vs DJVU), same page count (337p), different md5 — not byte-identical but the same underlying Russian-medium work |
| `09 Разговорный Казахский Легко (Colloquial Kazakh Made Easy).djvu` | By Романенко Е. — `djvutxt`-read: Russian-medium, "with exercises and answers." **The closest title to this project's flagship slang/colloquial category in the entire harvest, but excluded on metalanguage grounds** — see the note at the end of §5 |
| `10 Tilashar - Student's Book - Уроки Тiлашар.djvu` | Cover is bilingual Kazakh/Russian ("Методикалық құрал / Методическое пособие"), but **rendered interior page (p.6)** is purely Russian-medium alphabet/phonology instruction |
| `11 Изучаем казахский всей семьей.djvu` | By Р. Наурызбаева — cover bilingual KZ/RU, **rendered interior page (p.6)** shows Russian-medium instructional headers around Kazakh vocabulary (e.g. "Разучис стихотворение," "Словарь") |
| `12 Қазақ тiлi.pdf` | Cover reads "Учебное пособие для интенсивного обучения казахскому языку" — "Textbook for intensive teaching of the Kazakh language" — Russian-medium despite the Kazakh-script title |
| `18 Казахская грамматика для рускоязычных.djvu` | Title itself states the audience: "Kazakh Grammar for Russian-speakers" |
| `19 Грамматика казахского языка в таблицах и схемах.djv` | By Куликовская & Мусаева — "Grammar of the Kazakh language in tables and schemes, in comparison with Russian grammar" |
| `20 Руководство по изучению государственного языка.djvu` | By А. Белботаев & Ж. Буланбаева — **rendered interior page (p.5)** — Russian-medium academic grammar discussion (agglutination, vowel harmony), no English |
| `24 Руссско-казахский разговорник - бiрге сойлейiк.pdf` | "Говорим вместе / Бірге сөйлейік" — Russian-Kazakh only, no English. **Note:** a separate, English-inclusive trilingual edition of the same "Talking Together" phrasebook series exists and is kept in scope — see §5/§6, don't conflate the two |
| `28 Казахско-русский, русско-казахский словарь для учащихся и студентов.pdf` | 30,000-word Kazakh-Russian/Russian-Kazakh dictionary "for schoolchildren and students" — no English |
| `29 Большой казахско-русский, русско-казахский словарь.pdf` | By Қалдыбай Бектаев — "Big Kazakh-Russian, Russian-Kazakh Dictionary" — no English |
| `40 Бозинген Казахские народные сказки.djvu` | **Rendered copyright page** — "Перевод с казахского, издательство «Жалын», 1985" ("Translated from Kazakh, Zhalyn publishing house, 1985") — a Russian-medium translation of Kazakh folk tales |

**French-medium (1 file):** `04 Manuel de Qazaq Langue et Civilisation.pdf` — **rendered title page**:
"MANUEL DE QAZAQ / langue et civilisation," by Rémy Dor, INALCO (Institut National des Langues et
Civilisations Orientales), Paris — a serious academic French-medium manual, same "flip side of a
legitimate reference, wrong metalanguage" pattern this project has hit in other languages' triages.

**German-medium (1 file):** `26 Немiсше-қазақшa тiлашар - German-Kazakh Phrasebook.pdf` — **rendered
cover**: "Немісше-қазақша тілашар / Немецко-казахский разговорник," by Роза Қайырбаева, Нелли
Бондарчук, Женіс Бегімбетова — German-Kazakh phrasebook, no English.

**Turkish-medium (1 file):** `30 Түрікше-казақша сөздік.djvu` — **rendered cover**: "Түрікше-қазақша
сөздік," by Байниязов Аябек & Байниязова Жанар (editor Kenan Koç) — Turkish-Kazakh dictionary, no
English.

**Ukrainian-medium (1 file, a new wrong-metalanguage category for this project):** `39 Казахські
народні казки (Kazakh Folk Tales).djvu` — the external-drive filename itself uses the distinctively
**Ukrainian** spelling "Казахські" (Russian would be "Казахские"). **Rendered title page confirms**:
"КАЗАХСЬКІ НАРОДНІ КАЗКИ... Упорядкування та переклад з казахської ОЛЕКСАНДРА ПЕТЬКУНА... КИЇВ
«ВЕСЕЛКА» 1992" ("Kazakh Folk Tales... compiled and translated from Kazakh by Oleksandr Petkun...
Kyiv, Veselka, 1992") — a Ukrainian-medium translated folk-tale collection, distinct from the
Russian-medium `40 Бозинген` translation above (different translator, publisher, and metalanguage).

**No frequency list or frequency dictionary was found anywhere in this harvest** — unlike Mongolian's
sibling triage, which found one.

---

## 2. FLAGGED FOR YOUR RULING — Kazakh-medium-of-Kazakh (1 file)

Per the task's explicit carve-out, a non-English-medium resource of Kazakh itself is never silently
excluded or silently kept:

- **`13 Kazakh Tili 1.djvu`** (124p, vision) — **rendered and confirmed**: cover is a bright,
  cartoon-illustrated "ҚАЗАҚ ТІЛІ / 1" ("Kazakh Language / Grade 1") school textbook. **Rendered
  interior page (p.10)** shows a simple vocabulary/picture lesson ("Мынау — нан" / "This is bread,"
  "Мынау — ірімшік" / "This is cheese," etc.) with **no Russian or English translation apparatus
  anywhere on the page** — this reads as a native-speaker elementary-school primer for Kazakh
  schoolchildren learning their own language and literacy, not a foreign-language-teaching resource.
  Parallel in kind (though not in content) to Mongolian's flagged `09 Mongolian Workbook for
  Foreigners` and Danish's §5 group — genuinely Kazakh-medium, substantial (124 pages), and
  deliberately not excluded or kept without your decision.

---

## 3. Non-content assets (1 file)

- **`Kazakh Language Learning Pack.torrent`** (0.02MB) — a `.torrent` file sitting in the `Colloquial
  Kazakh/` folder, presumably the original download pointer for the Learning Pack folder itself. Not
  a content file, not an extraction target, nothing moved.

---

## 4. Not scheduled — packed archives and bulk usage-corpus material

**Neither found.** No `.rar`/`.zip` archives exist anywhere in this harvest, and no magazine runs,
newspaper archives, or other periodical collections exist either — this stash is entirely discrete
books, course materials, phrasebooks, dictionaries, and academic papers.

---

## 5. What's clearly in scope (27 raw unique files = 23 distinct titles) — category overview

### 5a. Reference grammars & academic linguistics (Tier 1 material)

- **Karl A. Krippes, *Kazakh Grammar with Affix List*** — exists as **2 non-byte-identical scans of
  the same work**: `17 Kazakh Grammar With Affix List.pdf` (46p, TEXT, external drive + Learning
  Pack) and `Kazakh-Grammar-With-Affix-List.pdf` (44p, TEXT, Learning Pack + both `lang transfer bay`
  Krippes copies). Same table of contents confirmed on both via `pdftotext` (vowel harmony, labial
  harmony, consonantal assimilation, colloquial-vs-written-Kazakh distinctions throughout) — **one
  underlying work, pick one scan as primary**.
- **Dávid Somfai Kara, *Kazak*** (LINCOM EUROPA, Languages of the World/Materials 417, 2002) — also 2
  scans of the same work: `21 Kazakh (Lincom Europa).pdf` (61p, vision, external drive + Learning
  Pack) and `Kazakh; Kazak (Kara).pdf` (61p, **TEXT**, `lang transfer bay`) — identical page count,
  same table of contents confirmed by `pdftotext` on the TEXT copy. **Prefer the TEXT copy** — same
  LINCOM Europa "Languages of the World/Materials" series this project has used as a reference-grammar
  source for other small/under-resourced languages.
- **Aijan Akhmetova, *Kazakh Language: Grammar, Texts, Vocabulary*** (32p, vision) — short but
  genuinely in-scope English-medium work; the single most-duplicated file in the harvest (5 copies
  across all three in-repo locations plus the external drive).
- *Functions of the So-called Passive Morpheme –(I)l– in Kazakh* (Dr. Fatma Şahan Güney, 15p, TEXT) —
  focused academic paper on Kazakh verbal morphology, comparative with other Turkic languages.
- ***Modality in Kazakh as Spoken in China*** (Aynur Abish, 280p, TEXT) — a 2014 Uppsala University
  PhD dissertation. **This is the one dialect-specific item in the harvest**: it studies Kazakh as
  spoken by the ethnic-Kazakh minority in China's Xinjiang region and Aksai, not the standard
  Kazakhstan variety — flag for context if dialect provenance matters to extraction.
- ***The Turkic Languages*** (Routledge Language Family Descriptions series, 251p, vision) — a major
  comparative reference covering the whole Turkic family including Kazakh; not Kazakh-specific but a
  serious linguistic-typology source.

### 5b. Vocabulary & dictionaries (Tier 2)

- **Two genuinely distinct Kazakh-English dictionaries, not duplicates of each other:**
  - `27 Kazakh-English Dictionary.pdf` (233p, vision) — "Қазақша-ағылшынша сөздік," Алматы,
    Дайк-Пресс — a modern commercial dictionary.
  - `Kazakh-English-dictionary.pdf` (87p, vision) — by Boris N. Shnitnikov, with a preface by Nicholas
    Poppe, Indiana University Publications Uralic and Altaic Series Vol. 28, Mouton & Co, 1966 — an
    older academic reference, smaller in page count but from a historically significant
    Uralic-Altaic-studies series.
- *Dictionary of the Turkic Languages* (Routledge, Kurtulus Öztopçu et al., 184p, TEXT) — a
  comparative English-medium dictionary spanning Azerbaijani, Kazakh, Kyrgyz, Tatar, Turkish,
  Turkmen, Uighur, and Uzbek — genuinely useful comparative lexical resource, not Kazakh-only.

### 5c. Slang / colloquial — the flagship category for this project's purposes

**Found, unlike several recent sibling triages in this project that came up empty here.**
*Colloquial Kazakh: The Complete Course for Beginners* (Routledge, Zaure Batayeva) — **2 scans of the
same work**: `Colloquial-Kazakh-the-complete-course-for-beginners.pdf` / `Colloquial Kazakh.pdf`
(165p, vision, clean scan — **prefer this copy**) and `Colloquial Kazаkh.pdf` (328p, vision; note the
filename uses a Cyrillic а homoglyph in "Kazаkh," not a typo-duplicate title — **rendered and
confirmed identical table of contents and CD-track listing** to the 165p copy, just a larger, noisier
scan of the same book, nearly double the page count likely from different page-splitting). Standard
Routledge Colloquial-series course, English-medium throughout, unit-by-unit conversational Kazakh.

**The near-miss, excluded on metalanguage grounds:** `09 Разговорный Казахский Легко` ("Colloquial
Kazakh Made Easy," Романенко Е.) is the closest-named alternative in the harvest but is Russian-medium
— see §1. **No English-medium dedicated slang/idiom dictionary** (as opposed to a general conversational
course) was found — the Routledge Colloquial title is the strongest available flagship candidate, but
it's a conversational course, not a slang-specific reference.

### 5d. Course series & phrasebooks (Tier 4)

- `03 Kazakh Familiarization Course.pdf` (278p, TEXT) — English-medium geography/culture-forward
  familiarization course, opens with Kazakhstan's provinces and geography.
- `15 Kazakh Language Manual.pdf` / `Entire-Kazakh-Language-Manual.pdf` (249p, TEXT) — Peace Corps
  Kazakhstan's "Kazakh Language Manual: Communication for Survival," edited by Michael Hancock, 2009.
- `23 Kazakh Language Course for Peace Corps Volunteers in Kazakhstan.pdf` (169p, vision) and its
  `lang transfer bay` twin `...(Alpysbaeva, Ismagulova & Turguzhanova).pdf` (168p, vision) — **2 scans
  of the same 1995 ERIC document** (ED 402 757), confirmed via the identical ERIC Document Resume page
  rendered from both — a distinct work from `15 Kazakh Language Manual` above (different Peace Corps
  course, different year, different authors), not a duplicate of it.
- `02 Kazakh Language Made Easy.djvu` (458p, vision) — by Н. Кубаева. **Notable finding**: despite a
  Russian-forward cover, the **rendered interior page (p.5)** shows genuine **parallel Russian/English
  side-by-side text** throughout its methodology preface — this is an English-inclusive trilingual
  (Kazakh target-language content with Russian+English parallel apparatus) work, not Russian-medium
  like its sibling titles in §1. Kept in scope on that basis; worth spot-checking at extraction time
  whether the English parallel-text convention continues past the preface into the lesson content
  itself.
- `01 Kazakh - Introduction.pdf` (2p, TEXT) — a short English-medium "Top 5 Reasons to Learn Kazakh"
  motivational flyer, DLIFLC-style.
- `24 Talking Together Russian-Kazakh-English Phrasebook.djvu` (242p, vision) — "Говорим вместе / Бірге
  сөйлейік / Talking Together," genuinely trilingual including English (confirmed via rendered cover)
  — distinct from the Russian-Kazakh-only edition of the same publisher series excluded in §1.
- `25 The Kazakh Phrasebook.pdf` / `The-Kazakh-Phrasebook-.pdf` (44p, vision) — by Aijan Akhmetova,
  Off the Beaten Path Phrasebooks series.

### 5e. Culture, history & society (own subcategory, not fitting the 5-tier scheme)

All English-medium, TEXT layer, confirmed via `pdftotext`:
- *The Kazakhs* (Studies of Nationalities series, Martha Brill Olcott, 410p) — a complete history from
  the mid-15th century to the post-Soviet present.
- *Kazakhstan: Ethnicity, Language and Power* (257p) — academic study of Kazakhstan's ethnic and
  political development.
- *Culture and Customs of the Central Asian Republics* (Rafis Abazov, Greenwood Press, 325p).
- *Central Asian Republics* (Nations in Transition series, Michael Kort, 209p).
- *The History of the Central Asian Republics* (Peter L. Roudik, Greenwood Press, 237p).
- *A History of Inner Asia* (Svat Soucek, 385p) — covers Uzbekistan, Kazakhstan, Kyrgyzstan,
  Tajikistan, Turkmenistan, Xinjiang, and Mongolia from the arrival of Islam onward.

### 5f. Graded readers — gap

**None found.** No dedicated graded-reader series or leveled-reading collection for Kazakh exists
anywhere in this harvest. The two folk-tale collections present (`39`, `40`) are both excluded on
metalanguage grounds (Ukrainian and Russian translations, respectively — §1), and the one
Kazakh-medium item (`13 Kazakh Tili 1`, §2) is a native-speaker school primer, not a graded reader
designed for foreign learners. Flag this gap explicitly — Tier 5 is empty, the same status several
other languages' triages in this project have hit.

### 5g. Verbs & reading/writing skill-building — thin

No standalone verb-conjugation reference or dedicated reading/writing skill-building title was found
separate from the general grammars in §5a. Treat Tier 3 as essentially empty for Kazakh.

---

## 6. Duplicate-edition pairs within the in-scope set — 4 pairs, not independent content

Four of the 27 in-scope raw unique files are alternate scans of a work already counted once elsewhere
in §5 — not byte-identical (different md5), but the same underlying title:

| Title | Scan A | Scan B |
|---|---|---|
| Krippes, *Kazakh Grammar with Affix List* | `17 Kazakh Grammar With Affix List.pdf` (46p, TEXT) | `Kazakh-Grammar-With-Affix-List.pdf` (44p, TEXT) |
| Kara, *Kazak* (LINCOM) | `21 Kazakh (Lincom Europa).pdf` (61p, vision) | `Kazakh; Kazak (Kara).pdf` (61p, **TEXT — prefer this one**) |
| Peace Corps *Kazakh Language Course* (ERIC ED 402 757) | `23 Kazakh Language Course for Peace Corps Volunteers in Kazakhstan.pdf` (169p, vision) | `...(Alpysbaeva, Ismagulova & Turguzhanova).pdf` (168p, vision) |
| *Colloquial Kazakh* (Routledge, Batayeva) | `Colloquial-Kazakh-the-complete-course-for-beginners.pdf` (165p, vision — **prefer this one**) | `Colloquial Kazаkh.pdf` (328p, vision, noisier scan) |

**27 raw unique files − 4 redundant alternate scans = 23 distinct dispatchable titles.**

---

## 7. Priority tiers

### TIER 1 — reference grammars & academic linguistics (highest value)

Krippes' *Kazakh Grammar with Affix List*, Kara's *Kazak* (LINCOM), Akhmetova's *Kazakh Language:
Grammar, Texts, Vocabulary*, the Güney passive-morpheme paper, Abish's *Modality in Kazakh as Spoken
in China* dissertation (note: China-dialect specific, §5a), *The Turkic Languages* (Routledge). ~6
distinct titles, majority TEXT.

### TIER 2 — vocabulary, dictionary, idiom & slang (fills the slang-synthesis need)

Both Kazakh-English dictionaries (Дайк-Пресс and Shnitnikov/Poppe), *Dictionary of the Turkic
Languages*, and the flagship **Colloquial Kazakh** (Routledge, Batayeva) — this project's recurring
slang/colloquial gap is genuinely filled for Kazakh, unlike several recent sibling triages. ~4
distinct titles, mostly vision.

### TIER 3 — verbs & reading/writing skill-building

**Essentially empty** — no standalone verb-conjugation reference or dedicated skill-building title
found separate from the Tier 1 grammars (§5g).

### TIER 4 — course series (lowest priority, highest cost)

Peace Corps *Kazakh Language Course* (2 scans), Peace Corps *Kazakh Language Manual*, *Kazakh
Familiarization Course*, *Kazakh Language Made Easy* (EN/RU bilingual, 458p — the single largest
in-scope course), the *Talking Together* trilingual phrasebook, Akhmetova's *Kazakh Phrasebook*, the
`01 Kazakh - Introduction` flyer. ~7 distinct titles, mixed TEXT/vision, the bulk of the in-scope page
count sits here.

### TIER 5 — graded readers

**Empty — no dedicated graded-reader material exists for Kazakh in this harvest** (§5f).

### Not fitting the 5-tier scheme — culture/history/society (6 files)

*The Kazakhs*, *Kazakhstan: Ethnicity, Language and Power*, *Culture and Customs of the Central Asian
Republics*, *Central Asian Republics*, *The History of the Central Asian Republics*, *A History of
Inner Asia* — all English-medium, TEXT layer, genuine background/context value (§5e).

---

## 8. Extraction notes

- **40% duplication rate (82 raw → 49 unique) is dominated by the in-repo Learning Pack folder being
  a near-complete subset of the external drive** — dispatch against the 49-unique-file set, and within
  that, against the **23-distinct-title set** once the 4 duplicate-edition pairs in §6 are resolved to
  one preferred scan each.
- **Both filename-suggested "(1)"-suffix pairs in `lang transfer bay/Kazakh/` are confirmed real
  byte-identical duplicates by md5** — not just similarly named files (per the task's explicit
  instruction not to assume this from the naming pattern alone).
- **§2's one Kazakh-medium file needs an explicit ruling** before either extraction or exclusion — a
  native-speaker Grade 1 school primer, not a foreign-language-teaching resource.
- **A genuine flagship slang/colloquial title exists**: Routledge's *Colloquial Kazakh* by Zaure
  Batayeva — prefer the cleaner 165-page scan over its 328-page noisier duplicate (§6).
- **`02 Kazakh Language Made Easy` is a notable trilingual (Kazakh/Russian/English) find** — confirm
  at extraction time whether the parallel-English-text convention observed in its preface continues
  through the full 458 pages.
- **One dialect-specific item was found**: Abish's *Modality in Kazakh as Spoken in China* studies the
  Xinjiang/China-Kazakh variety specifically, not the Kazakhstan standard — flag if dialect provenance
  matters for extraction scoping.
- **No frequency list, no packed archives, and no bulk usage-corpus material exist anywhere in this
  harvest** — nothing to report to the frequency-dictionaries folder this time, unlike Mongolian's
  sibling triage.
- **No wrong-target-language contamination was found** — every file confirmed Kazakh-subject-matter is
  genuinely about Kazakh; no misfiled Kyrgyz, Karakalpak, or other Turkic-language material turned up.
- **Tier 3 (verbs/reading-writing) and Tier 5 (graded readers) are both effectively empty** — real,
  flaggable gaps if either matters to the Tepenian handoff.
- Scratch render files (title/content-page renders for every vision-only file, the raw harvest TSV
  working copy, the md5-grouping analysis) have been deleted from the scratchpad per the project's
  disk-space instruction; nothing was written to the external drive or `source_reference/`.
