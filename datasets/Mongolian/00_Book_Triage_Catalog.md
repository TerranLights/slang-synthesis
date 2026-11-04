# Mongolian — Book Triage Catalog

**Triage complete, 2026-11-03.** First-ever full-scope triage for Mongolian in this project, per the
`TepenianLanguage` handoff (Mongolian is a "second-era"/Tepenian-stage contributing-language
candidate with a documented Federation presence, Ariun Nuur, but no specific domain idea assigned
yet). **Triage only — no extraction dispatched, nothing written to `established/`.**

**This supersedes a prior same-day draft** that already existed at this path before this pass (also
dated 2026-11-03, 15.8KB). That draft covered three of the four required locations (external drive,
in-repo `source_reference/languages/Mongolian/`, and the 3 handoff-named loose files) but **never
covered the fourth location** — the 7 scholarly papers loose in `xx--stash/LibGen Lang/` — and used a
deduplicated-row TSV schema instead of the one-row-per-file schema this pass's instructions require.
This version covers all four locations with a full per-file harvest, and corrects two findings from
the prior draft (§2, §5).

**Locations (all four confirmed):**
1. External drive: `/media/kuroskalacs/Home-Theater/w-lang/Mongolian/` (confirmed mounted) — 44 files, 1.2GB
2. In-repo: `source_reference/languages/Mongolian/` and its 6 subfolders (`Routledge Colloquial
   Mongolian/`, `07.Mongolian/`, `Glossika Mongolian. Complete Fluency Course - 2015/`, `Modern
   Mongolian - A Coursebook/`, `immediate urgency/`, `Mongolian Language Learning Pack (Updated)/`) —
   203 files, 4.5GB
3. 3 loose handoff-named files directly in `source_reference/languages/`: *An Elementary Mongolian
   Grammar* (Elliott), *Ocean of Milk, Ocean of Blood* (King), *Secret History of the Mongols*
4. 7 scholarly papers loose in `source_reference/languages/xx--stash/LibGen Lang/` — **an 8th file
   was found loose in the same location during the scan** (`Vowel-harmony-and-disharmony-in-Tuvan-
   and-Tofa.pdf`), not part of the handoff's named 7 — see §3.

**Raw harvest data:** `.triage_raw.tsv` — **258 rows, one per raw file** (folder, file, size_mb,
pages, text_layer, md5), covering every file in all four locations.

**Methodology:** every PDF/DJVU got an md5 hash, a `pdfinfo`/`djvused` page count, and a text-layer
probe (`pdftotext`/`djvutxt` on the first 1-3 pages). Titles for files with a text layer were
confirmed from the extracted title-page text itself. **Every vision-only file with a generic or
ambiguous filename was individually rendered** (`pdftoppm`) and read — this caught one medium
correction and one wrong-audience correction the prior draft missed (§2, §5). Duplicates were checked
by md5 across all 258 files, not by filename or by location.

---

## This stash is extraordinarily duplicate-heavy — the key finding before any content triage

**258 total files across all four locations collapse to only 103 unique files by md5 hash — a 60%
duplication rate.** The in-repo `Mongolian Language Learning Pack (Updated)/` subfolder (81 files) is
almost entirely a byte-identical copy of everything else already sitting in the parent SSD folder and
its `07.Mongolian/` subfolder — **35 unique files appear on both the external drive and the SSD**, and
2 of the 7 named scholarly papers turned out to be byte-identical duplicates of files already present
on the external drive and SSD (`13 The Phonology of Mongolian.pdf` and `37 Encyclopedia of Mongolia
and The Mongol Empire.pdf` — see §3). Any wave planning must dispatch against the **103-unique-file
set**, not the 258-file raw count, or the same content gets extracted many times over.

---

## Headline numbers

| | |
|---|---|
| Total files harvested (all 4 locations, incl. duplicates) | **258** |
| **Unique files by md5** | **103** |
| Of which duplicated between EXTERNAL and SSD | **35** |
| **Excluded — wrong metalanguage** | **16** (Russian ×11, German ×2, French ×1, Italian ×1, Japanese ×1) |
| **Excluded — wrong audience** (non-English MN-ZH / MN-ZH-TIB bilingual-trilingual, no English) | **5** |
| **Flagged — related-but-distinct Mongolic/Turkic languages**, not Khalkha Mongolian | **9** |
| **Excluded — pure tourism** (English-medium, beyond the 1 already counted as Russian) | **1** |
| **Flagged — non-English-medium-of-itself**, needs your ruling | **2** |
| Non-content assets (cover-list JPG, 2 unrelated PNGs) | **3** |
| **Clearly in-scope candidates for Phase 1** | **67** |
| Of which text layer present | **34 (51%)** |
| Of which vision-read required | **32 (48%)** |
| Of which epub (format TBD) | **1** |
| Total pages, in-scope unique files | **≈25,150** |
| Total size, in-scope unique files | **≈1.31 GB** |
| Frequency list found | **1** (Russian-medium, excluded from extraction, reported per standing instruction) |
| Flagship slang/colloquial-register title | **none found — see §6** |

Check: 16 + 5 + 9 + 1 + 2 + 3 + 67 = 103 unique files. ✓

---

## 1. EXCLUDE — wrong metalanguage (16 unique files)

**Russian-medium (11 files)**, all on the external drive, confirmed via Cyrillic title text:

| File | Note |
|---|---|
| `08 Учебник монгольского языка для иностранцев.pdf` | "Textbook of the Mongolian Language for Foreigners" |
| `30 Монголия (Пти Фюте).pdf` | Petit Futé travel guide, Russian edition — **also pure tourism**, double-excluded |
| `43 Оюун тулхюур...бурятскому языку.djvu` | Russian-medium **and about Buryat**, not Khalkha Mongolian — doubly out of scope |
| `05 Учебник монгольского языка.pdf` | Russian |
| `22 Большой современный русско-монгольский - монгольско-русский словарь.pdf` | Russian-Mongolian dictionary |
| `06 Современный монгольский язык.djvu` | Russian |
| `07 Учебник монгольского языка (1952).pdf` | Russian, Soviet-era |
| `28 Введение в старописьменный монгольский язык.pdf` | Russian |
| `Mongolian (Khalkha); Грамматика современного монгольского языка - Фонетика и Морфология (Todaeva).pdf` | Russian |
| `Mongolian (Classical); Грамматика Письменно-Монгольского Языка (Poppe) (1937).pdf` | Russian — **note:** Poppe also has an English-medium *Grammar of Written Mongolian* in this stash (kept, §6) — same author, different-language editions, not a duplicate |
| `18 4000 наиболее употребительных слов и словосочетаний.pdf` | Russian-Mongolian — **also the frequency list found in this harvest**, see note below |

**German-medium (2 files):** `17 Kauderwelsch Mongolisch Wort für Wort.pdf` (same Reise Know-How
series excluded for the same reason in this project's other triages); `Mongolian (Classical);
Grammatik der Mongolischen Sprache (Schmidt) (1831).pdf`.

**French-medium (1 file):** `Mongolian (Classical); Grammaire de la Langue Mongole Écrite
(Hambis).pdf`.

**Italian-medium (1 file):** `Mongolian (Khalkha); Introduzione alla Lingua Mongola (Molomjamts &
Csillaghy).pdf`.

**Japanese-medium (1 file, newly found via location 4 — not caught by the prior draft since it never
scanned this location):** `Mengwen-Daogang-arranged-by-romanized-Mongolian-words-with-Chinese-and-
Manchu.pdf` (609p, TEXT) — rendered/confirmed: a Japanese-language academic monograph (Center for
Northeast Asian Studies, Tohoku University) presenting a romanized-Mongolian-word index cross-
referenced against Chinese and Manchu readings. The body text is Japanese prose with romanized
Mongolian examples embedded, not an English or Mongolian-medium work.

**Frequency list found:** `18 4000 наиболее употребительных слов и словосочетаний.pdf` ("4,000 most
commonly used words and phrases," Russian-Mongolian) — excluded from extraction on metalanguage
grounds above, flagged here specifically per your standing instruction. Report to
`/home/kuroskalacs/Documents/Doll-Fi/media/y-files/frequency_dictionaries/`, not moved.

---

## 2. EXCLUDE — wrong audience, non-English bilingual/trilingual (5 unique files)

Not excluded for lacking linguistic value — each contains real Mongolian lexical data — just paired
with Chinese and/or Tibetan rather than English:

| File | Pages | Note |
|---|---|---|
| `23 Mongolian-Chinese Dictionary.pdf` | 1,557 | MN-ZH, no English |
| `Han-Mongolian-Dictionary.pdf` | 1,954 | "Han" = Chinese, no English |
| `34 Adventures of Kofiko (Bilingual Edition Mongolian-Chinese).pdf` | 378 | children's book, MN-ZH |
| `Chinese-Tibetan-Mongolian-Buddhist-Dictionary-.pdf` | 1,257 | **Rendered/confirmed** — title page reads "汉藏蒙对照佛教词典" ("Chinese-Tibetan-Mongolian Comparative Buddhist Dictionary"), trilingual Buddhist terminology, no English |
| `Mongolian-Children-s-book.pdf` | 378 | **Rendered — the one wrong-audience correction to the prior draft** (which left this file in its "unconfirmed, needs a closer check" bucket). Cover art is a Journey-to-the-West-style action comic with a vertical-Mongolian-script title; page 2 is a 2003 group photo captioned in Chinese referencing an academic conference in China. This is a Mongolian-script children's comic produced in Inner Mongolia with Chinese captions — belongs here, not in the unconfirmed bucket. |

**Kept, not excluded here** — these are English-inclusive trilingual works, correctly distinguished
from the above: `24 English-Mongolian-Chinese Dictionary.pdf` / `English-Chinese-Mongolian-Script-
Dictionary.pdf`, `20 Mongolian-English-Chinese Dictionary.pdf` / `Mongolian-Script-Chinese-English-
Dictionary.pdf` and its duplicate-content twin `Mongolian-English-Chinese-dictionary-Монгол-англи-
хятад-толь.pdf` (same page count, different md5 — different scan, not a duplicate file) — all three
groups explicitly include English in the dictionary, so they're kept in §6.

---

## 3. The 7 named scholarly papers + 1 unexpected 8th file (location 4)

Per-file disposition for `xx--stash/LibGen Lang/` — **this location was not covered by the prior
draft at all**:

| File | Pages | Disposition |
|---|---|---|
| `Mengwen-Daogang-arranged-by-romanized-Mongolian-words-with-Chinese-and-Manchu.pdf` | 609 | **EXCLUDE — Japanese-medium** (§1) |
| `Fortune-and-the-Cursed-The-Sliding-Scale-of-Time-in-Mongolian-Divination.pdf` | 284 | **In scope** — English academic paper on Mongolian divination/time concepts, kept in §6 |
| `The-Vajrabhairava-tantras-Tibetan-and-Mongolian-texts-with-introduction-translation-and-notes.pdf` | 413 | **In scope** — English introduction/translation/notes around Tibetan and Mongolian Buddhist tantra texts, kept in §6 |
| `Encyclopedia-of-Mongolian-and-the-Mongol-Empire.pdf` | 689 | **Duplicate, not new content** — byte-identical (md5 match) to `37 Encyclopedia of Mongolia and The Mongol Empire.pdf`, already present on both the external drive and the SSD pack folder |
| `Vowel-harmony-in-Khalkha-Mongolian-Yaka-Finnish-and-Hungarian.pdf` | 22 | **In scope** — Khalkha Mongolian is a direct subject, kept in §6 |
| `Jan-Olof Svantesson...The Phonology of Mongolian...pdf` | 335 | **Duplicate, not new content** — byte-identical to `13 The Phonology of Mongolian.pdf`, already present on the external drive and SSD |
| `Inclusive-exclusive-distinctions-in-Sive-spoken-Manchu-and-Khalkha-Mongolian.pdf` | 16 | **In scope** — Khalkha Mongolian is a direct subject, kept in §6 |
| `Vowel-harmony-and-disharmony-in-Tuvan-and-Tofa.pdf` (the unexpected 8th file) | 15 | **FLAG — wrong-language contamination.** Not one of the 7 named items; sitting loose in the same folder. Tuvan and Tofa are both Turkic Siberian languages, not Mongolic — this paper has no direct Mongolian-language content (unlike the Khakas/Tuvan loanword papers in §4, which specifically study Mongolic loanwords *in* those languages). |

**Net new content from this location: 4 files** (Fortune-and-the-Cursed, Vajrabhairava-tantras,
Vowel-harmony-Khalkha/Yaka/Finnish/Hungarian, Inclusive-exclusive-Sive/Khalkha) — 2 of the named 7
were duplicates already covered in locations 1-2, and the 8th file found is wrong-language
contamination.

---

## 4. FLAGGED — related-but-distinct Mongolic/Turkic languages, not Khalkha Mongolian (9 files)

Linguistically adjacent but not the target language — flagged for a scope decision, not silently
merged or dropped:

**Mongolic minority languages of China** (related to, but distinct from, Khalkha Mongolian):
`41 A Grammar of Mangghuer.pdf`, `42 Mangghuer Folktale Reader.pdf` (Mangghuer/Monguor);
`Hui-loanwords-in-Dongxiang-Mongolian.pdf` (Dongxiang — a comparative paper on Hui loanwords, not
Dongxiang-language material itself); `Dagur-Mongolian-Grammar-Texts-and-Lexicon.pdf`,
`Dagur-vocabulary-with-written-Mongolian-and-written-Manchu-indices.pdf` (Dagur — the latter is also
a Japanese-medium CNEAS publication, doubly out of scope); `Written-Mongolian-index-to-the-Shera-Y-
gur-vocabulary.djvu` (Shira Yugur).

**Turkic languages with Mongolic-loanword content** (comparative-linguistics papers, not Mongolian-
language material): `Long-and-short-vowels-in-Khakas-reflexes-of-the-Mongolian-VCV-sequence.pdf`
(Khakas), `Long-vowels-in-Mongolic-loanwords-in-Tuvan.pdf` (Tuvan).

**Pure contamination, not even comparative** (§3): `Vowel-harmony-and-disharmony-in-Tuvan-and-
Tofa.pdf`.

---

## 5. EXCLUDE — pure tourism, English-medium (1 file beyond the Russian one in §1)

- **`31 Discover Mongolia.pdf`** (36p, TEXT) — rendered/confirmed via `pdftotext`: table of contents
  reads "Traveling Around Mongolia," "Ulaanbaatar Capital City," "Useful Phone Numbers," "Travel
  Companies," "Tourist Map of UB & Mongolia" — a travel magazine/guide, no language-learning content.

---

## 6. FLAGGED FOR YOUR RULING — non-English-medium-of-itself (2 files)

**RULING RECEIVED, 2026-11-04** (per `TepenianLanguage/handoffs_to_slang_synthesis/
2026-11-04_native_medium_ruling.md`, citing `TepenianLanguage/DECISIONS.md` D-25 Books written in
the target languages: usage study): *"Books written in target languages are to be used for
studying how the languages are used in practice."* Both of these files are now **in scope as
usage material** — the ruling answers the medium question but not the mechanics: it does not say
when/how to extract them, nor whether output belongs in `established/` or `language_corpus/`
(this project's usage-corpus vs. reference-corpus distinction). **Do not extract on this ruling
alone — wait for the next explicit instruction.**

The recurring open category this project flags rather than silently excludes or keeps — a
non-English-medium reference/resource of the language itself:

- **`09 Mongolian Workbook for Foreigners.pdf`** (293p, TEXT) — **rendered and confirmed**: cover
  reads "ТОГМИДЫН УРАНЧИМЭГ — MONGOLIAN LANGUAGE EXERCISES (For foreigners) — МОНГОЛ ХЭЛЗҮЙН
  ДАСГАЛУУД — гадаадынханд зориулав — УЛААНБААТАР. 2002." This is a Mongolian-Cyrillic-medium
  grammar-exercise workbook by Togmidyn Uranchimeg (Ulaanbaatar, 2002) — despite the English half-
  title sticker on the cover, the content itself is Mongolian-medium, not English-medium.
- **`Mongolian-book.pdf`** (398p, vision) — **rendered**: a book printed entirely in traditional
  vertical Mongolian script (not Cyrillic), with a back-cover price tag dated 2009. No Latin-script
  title, author, or publisher visible on the cover or next page — title and content genuinely
  unidentified without a vertical-script reader. Could be literature, scripture, or a reference work;
  flagged rather than guessed at.

**No Mongolian-medium-of-Mongolian title was silently kept or silently dropped** — both go here for
your decision.

---

## 7. Non-content assets (3 unique files)

- `00 Book List.JPG` — collector's own folder-listing screenshot (present on both the external drive
  and in the SSD pack subfolder — same file, not independent).
- Two unrelated `.png` images sitting loose in the SSD folder and its pack-subfolder copy:
  `Mongolian Imperial Guard definitely 23472055...png` and `Mongolian-Finnish warriors saving Evropa
  23732421...png` — collector's own meme/wallpaper images, no language content.

---

## 8. Not scheduled — packed archives

**None found.** No `.rar`/`.zip` archives exist anywhere in this harvest, unlike several prior
languages' stashes in this project.

---

## 9. Bulk usage-corpus material

**None found.** No magazine runs, newspaper archives, or other periodical collections exist in this
harvest — unlike German's `Der Weg` or Russian's magazine collections. Nothing to exclude from the
per-file count on this basis.

---

## 10. What's clearly in scope (67 unique files) — category overview

### 10a. Flagship reference grammars

**D.Tserenpil & R.Kullmann's *Mongolian Grammar*, Fourth Revised Edition** — exists as 2 scans of the
same edition (`10.Mongolian Grammar.pdf` / `Mongolian-Grammar.pdf`, TEXT, 469p — **prefer this copy**
— and `11 Mongolian Grammar (Fourth Revised Edition).pdf`, vision, 473p), plus 2 further vision scans
(`Mongolian Grammar (Kullmann & Tserenpil).pdf` and `Mongolian-Grammar-Монгол-Хэлз-й.pdf`, both 236p)
that appear to be a **shorter, different edition** by the same authors — confirm which edition(s) you
want before dispatch, same open question the prior draft also flagged.

Also: **Janhunen's *Mongolian*** (`Mongolian (Janhunen).pdf` / `Mongolian.pdf`, TEXT, 336p, London
Oriental and African Language Library) — a serious academic reference grammar, do not judge this file
by its generic filename. **Poppe's *Grammar of Written Mongolian*** (English, `Grammar-of-Written-
Mongolian.pdf`, 218p, vision) — distinct from his excluded 1937 Russian edition (§1). *An Elementary
Mongolian Grammar* (Elliott — handoff-named loose file, TEXT, 345p). `10 Mongolian Grammar Textbook`
(Baatarsukh, TEXT, 162p) + its likely epub duplicate `Mongolian-Grammar-Textbook-.epub` (not
independently content-verified).

**Classical/literary Mongolian cluster:** *A Grammar of the Mongol Language* (Chinggaltai, **rendered
and confirmed** — Frederick Ungar Publishing Co., New York, 175p, vision); *An Introduction to
Classical (Literary) Mongolian* (Grønbech & Krueger, **rendered and confirmed** — Otto Harrassowitz,
Wiesbaden, 1955, 113p, vision); *Classical Mongolian* (Sárközi, LINCOM Europa "Languages of the
World/Materials" series — same series used for Cantonese's Killingley reference, 38p, vision);
`Introduction-to-classical-literary-Mongolian.pdf` (56p, vision) — **a shorter, distinct work from the
Grønbech & Krueger title** (different page count, different md5) — don't conflate the two despite the
similar names. `Mongolian (Khalkha); Khalkha (Svantesson).pdf` (23p, TEXT) — a dedicated chapter on
the Khalkha dialect specifically.

### 10b. Dictionaries (English-medium or English-inclusive)

`Mongolian-English dictionary - Charles Bawden [2010].pdf` (TEXT, 603p — a major standard reference),
`19 Mongolian-English Dictionary.pdf` (vision, 1,226p), `21 A Spoken Mongol-English Dictionary.pdf`
(vision, 568p), `25 Dictionary of Mongolian Phrases.pdf` / its identically-hashed renamed twin
`Mongolian-Dictionary-of-Idioms.pdf` (**byte-identical — one file under two names, not two
dictionaries**, vision, 1,391p), `26 Blue Mongolian Dictionary Complete.pdf` (**3,166 pages — the
single largest file in this entire harvest**, vision, will need heavy representative sampling),
`Mongolian-Etymological-Dictionary.pdf` (Rajki, TEXT, 87p), `20 Mongolian-English-Chinese
Dictionary.pdf` / `Mongolian-Script-Chinese-English-Dictionary.pdf` (vision, 1,022p, English-
inclusive) and its duplicate-content twin `Mongolian-English-Chinese-dictionary-Монгол-англи-хятад-
толь.pdf` (same page count, different md5 — confirm which scan before dispatch), `24 English-
Mongolian-Chinese Dictionary.pdf` / `English-Chinese-Mongolian-Script-Dictionary.pdf` (vision, 1,262p,
English-inclusive), `16 Mongolian Phrasebook with Comprehensive Dictionary.pdf` (vision, 108p),
`Амар-Байна-уу...A Student Guide to Khalkha Mongolian Pronunciation.pdf` (vision, 90p, bilingual
MN/EN).

### 10c. Idiom / colloquial / slang — the flagship category for this project's purposes

**No dedicated slang dictionary or informal-register title exists anywhere in this 103-file unique
harvest — a real gap, parallel to Malay's gap in this project's most recent prior triage.** The
closest analog is `25 Dictionary of Mongolian Phrases` / `Mongolian-Dictionary-of-Idioms` (§10b) — an
idiom/phrase dictionary, not a slang dictionary specifically. The two "Colloquial Mongolian" course
titles (§10e) are structured language courses in the Routledge/Charles-University sense of
"colloquial" (conversational register, not slang), not slang/idiom reference works. **Flag this gap
explicitly if the Tepenian handoff cares about Mongolian slang coverage specifically** — this stash
does not supply it.

### 10d. Verbs & grammar-adjacent academic papers

`40 Studies on Mongolian Verb Morphology.pdf` (TEXT, 285p, U. Toronto PhD thesis),
`The-Past-Tenses-of-the-Mongolian-Verb-Meaning-and-Use.pdf` (TEXT, 259p),
`Tense-mood-and-aspect-in-Mongolian.pdf` (vision, 10p),
`Sentential-negative-markers-as-pro-forms-of-negative-sentences-in-modern-Mongolian.pdf` (TEXT, 7p),
`Acoustic-analysis-on-the-palatalized-vowels-of-modern-Mongolian.pdf` (TEXT, 4p),
`Practical-Mongolian-sentences-Mongol-bichig-with-English-translation-.pdf` (Sino-Platonic Papers,
TEXT, 127p — reading/writing-skills adjacent, covers traditional Mongol bichig script).

### 10e. Course series — two genuinely distinct "Colloquial Mongolian" lineages, don't conflate them

- **Routledge's *Colloquial Mongolian: The Complete Course for Beginners*** (Alan J.K. Sanders &
  Jantsangiyn Bat-Ireedui) — `02 Colloquial Mongolian The Complete Course for Beginners.pdf` (vision,
  171p — **10 copies**, the single most-duplicated file in the stash).
- **A separate course also titled "Colloquial Mongolian," by different authors** (Jugderiin
  Lubsangdorji & Jaroslav Vacek, Charles University Prague): *An Introductory Intensive Course*,
  volumes I and II plus a vocabulary supplement. The external-drive/root-level copies
  (`03 Colloquial Mongolian An Introductory Intensive Course I/II.pdf`) are vision-only; **TEXT-layer
  duplicates of the same content exist** under `Routledge Colloquial Mongolian/Colloquial-Mongolian-
  an-introductory-intensive-course-vol-1.pdf` and the `-Supplement-with-vocabulary-vol-2.pdf` —
  **prefer the TEXT copies**.
- Also: `01 Modern Mongolian A Course-Book.pdf` (vision, 269p — 7 copies, plus one SSD-only
  near-duplicate scan, not byte-identical); `04 Modern Mongolian A Primer and Reader.pdf` (Bosson,
  TEXT, 265p, American Council of Learned Societies — **prefer this copy**; a second SSD-only scan,
  `Modern-Mongolian-A-Primer-and-Reader.pdf`, is only 134 pages — **rendered and confirmed the same
  Bosson title via its cover**, so this is a partial/incomplete scan of the same book, not a different
  work — treat as redundant, not independent content); `09 Mongolian Workbook for Foreigners.pdf`
  (flagged, §6); `12 Mongolian Language Handbook.pdf` (vision, 190p); `Mongolian-Language-for-
  Beginners.pdf` and `Mongolian-Language-for-Intermediate-Students.pdf` (SSD-only, vision);
  `English-Mongolian-Phrase-Book.pdf` (vision, 83p); `15 Mongolian Phrasebook (Vertical Script).pdf`
  (TEXT, 33p, Lonely Planet — covers the traditional vertical script); the **Glossika Mongolian
  Complete Fluency Course** (levels 1-3, SSD-only, all TEXT, Michael Campbell's series — same
  publisher pattern as this project's Swedish triage).

### 10f. Academic/sociolinguistic reference, culture & specialist academic papers (own subcategory)

**Major reference volumes:** `14 The Mongolic Languages.pdf` (TEXT, 464p, Janhunen ed. — a major
comparative reference), `37 Encyclopedia of Mongolia and The Mongol Empire.pdf` (TEXT, 689p — present
in 3 of the 4 locations, see §3), `13 The Phonology of Mongolian.pdf` (TEXT, 335p, Svantesson et al.,
Oxford "Phonology of the World's Languages" series — same series used elsewhere in this project,
present in 3 of the 4 locations, see §3), `27 Summary of the Mongolian Orthography Rules.pdf` (TEXT,
46p), `32 Culture and Customs of Mongolia.pdf` (TEXT, 205p, Greenwood series), `36 Empire of the
Mongols (Great Empires of the Past).pdf` (TEXT, 161p), `35 Mongolian Nomadic Culture Its Sources.pdf`
(vision, 592p), `39 Introduction to Altaic Philology.pdf` (vision, 534p), `38 Introduction to
Mongolian Comparative Studies.pdf` (vision, 300p).

**Specialist academic papers (short journal-length works, own subcategory per the 7-loose-papers
scope note)** — genuinely useful for grammar-logic and comparative work despite not being
general-audience learning material:
- `Fortune-and-the-Cursed-The-Sliding-Scale-of-Time-in-Mongolian-Divination.pdf` (TEXT, 284p) —
  Mongolian divination and time-concepts, culture/folk-religion focus.
- `The-Vajrabhairava-tantras-Tibetan-and-Mongolian-texts-with-introduction-translation-and-notes.pdf`
  (TEXT, 413p) — English introduction/translation/notes around primary Tibetan and Mongolian Buddhist
  tantra texts.
- `Vowel-harmony-in-Khalkha-Mongolian-Yaka-Finnish-and-Hungarian.pdf` (vision, 22p) — focused
  cross-linguistic phonology paper with Khalkha Mongolian as a direct subject.
- `Inclusive-exclusive-distinctions-in-Sive-spoken-Manchu-and-Khalkha-Mongolian.pdf` (TEXT, 16p) —
  focused morphosyntax paper, Khalkha Mongolian as a direct subject.
- `Divine-knowledge-Buddhist-mathematics-according-to-Antoine-Mostaert-s-Manual-of-Mongolian-
  Astrology-and-Divination-.pdf` (TEXT, **2,244 pages** — a large PhD thesis, will need
  representative-sampling treatment despite being a single "paper"-category item).
- `Mongolian-oral-epic-poetry-an-overview.pdf` (TEXT, 15p, Chao Gejin) and `The-present-state-of-the-
  Mongolian-epic-and-some-topics-for-future-research.pdf` (TEXT, 14p, Walther Heissig) — both on
  Mongolian oral-epic tradition specifically.

### 10g. Culture / literature / history

`33 Mongolian Folktales and Legends.pdf` (TEXT, 71p, translated folklore collection), and the two
remaining handoff-named loose files: **`Secret History of the Mongols`** (TEXT, 292p — the classical
13th-century epic chronicle, translated by Igor de Rachewiltz — genuinely major source material) and
**`Ocean of Milk, Ocean of Blood`** (TEXT, 298p, Matthew King — an academic monograph on a Mongolian
Buddhist monk in the Qing-era ruins; this reads as a historical/anthropological monograph rather than
a language-learning resource, as the handoff itself anticipated, but it is English-medium prose with
genuine cultural/historical content, kept in scope rather than excluded).

**On the two monograph-style loose files' standalone linguistic value:** neither *Ocean of Milk, Ocean
of Blood* nor *Secret History of the Mongols* functions as a grammar, dictionary, or phrasebook — both
are read-only historical/literary sources. *Secret History* is the far stronger candidate of the two
for extraction value: it's the single most important work of classical Mongolian literature, likely to
contain period vocabulary, proper names, and narrative register worth capturing. *Ocean of Milk, Ocean
of Blood* is a modern academic monograph *about* a Mongolian monk, written by an English-language
historian — valuable as cultural/historical context but with much lower linguistic-extraction density
than the rest of this stash; treat as a lower-priority background source, not a core Phase 1 target.

### 10h. Graded readers — gap

**None found.** No dedicated Mongolian-language graded-reader series or leveled-reading collection
exists anywhere in this harvest (the excluded `42 Mangghuer Folktale Reader.pdf`, §4, is Mangghuer,
not Khalkha Mongolian). `33 Mongolian Folktales and Legends` (§10g) is translated literature, not a
pedagogically graded reader. Flag this gap explicitly, same status as Malay's empty Tier 5 in this
project's most recent prior triage.

---

## 11. Priority tiers

### TIER 1 — reference grammars & academic linguistics (highest value)

Tserenpil & Kullmann's *Mongolian Grammar* (both editions, confirm which you want), Janhunen's
*Mongolian*, Poppe's *Grammar of Written Mongolian*, Elliott's *An Elementary Mongolian Grammar*,
Baatarsukh's *Mongolian Grammar Textbook* (+ epub), the classical-Mongolian cluster (Chinggaltai,
Grønbech & Krueger, Sárközi, `Introduction-to-classical-literary-Mongolian`), the Khalkha dialect
chapter (Svantesson), `14 The Mongolic Languages`, `13 The Phonology of Mongolian`, `27 Summary of
the Mongolian Orthography Rules`, `39 Introduction to Altaic Philology`, `38 Introduction to Mongolian
Comparative Studies`, and the specialist academic papers in §10f. ~22 files, roughly even TEXT/vision
split. This is where grammar-logic work should start.

### TIER 2 — vocabulary, dictionary, idiom & slang (fills the slang-synthesis need, partially)

Bawden's *Mongolian-English Dictionary*, `19 Mongolian-English Dictionary`, `21 A Spoken
Mongol-English Dictionary`, `25 Dictionary of Mongolian Phrases`/`Mongolian-Dictionary-of-Idioms`
(closest thing to a flagship — no true slang dictionary exists, §10c), `26 Blue Mongolian Dictionary
Complete` (needs heavy sampling), `Mongolian-Etymological-Dictionary`, the two English-inclusive
trilingual dictionary pairs, `16 Mongolian Phrasebook with Comprehensive Dictionary`, the Khalkha
pronunciation guide. ~11 files, mostly vision.

### TIER 3 — verbs & reading/writing skill-building

`Studies on Mongolian Verb Morphology`, `The-Past-Tenses-of-the-Mongolian-Verb`, `Tense-mood-and-
aspect-in-Mongolian`, `Sentential-negative-markers`, `Acoustic-analysis-on-the-palatalized-vowels`,
`Practical-Mongolian-sentences-Mongol-bichig-with-English-translation`. ~6 files, mostly TEXT,
cheapest tier.

### TIER 4 — course series (lowest priority, highest cost)

Both "Colloquial Mongolian" lineages (confirm which to prioritize — Routledge's has 10 duplicate
copies, the Lubsangdorji/Vacek TEXT copies are cheaper to process), `01 Modern Mongolian A
Course-Book`, `04 Modern Mongolian A Primer and Reader` (prefer the 265p TEXT copy over the 134p
partial scan), `09 Mongolian Workbook for Foreigners` (pending your §6 ruling), `12 Mongolian
Language Handbook`, `Mongolian-Language-for-Beginners`/`-Intermediate-Students`, the 3-level Glossika
course, `English-Mongolian-Phrase-Book`, `15 Mongolian Phrasebook (Vertical Script)`. ~14 files,
majority vision, several multi-copy duplicate clusters to resolve before dispatch.

### TIER 5 — graded readers

**Empty — no dedicated graded-reader material exists for Mongolian in this harvest** (§10h).

### Not fitting the 5-tier scheme — culture/literature/history (3 files)

`33 Mongolian Folktales and Legends`, `Secret History of the Mongols` (high extraction value, §10g),
`Ocean of Milk, Ocean of Blood` (lower extraction density, background/context value only, §10g).

---

## 12. Extraction notes

- **60% duplication rate (258 raw → 103 unique) is the dominant fact about this stash** — dispatch
  against the unique set only.
- **Confirm which edition(s) of the Tserenpil/Kullmann grammar and which "Colloquial Mongolian" course
  lineage you want** before dispatch (§10a, §10e) — the two biggest duplicate-cluster ambiguities,
  same open question the prior draft also raised.
- **§6's two files need an explicit ruling** before either extraction or exclusion — one confirmed
  Mongolian-Cyrillic workbook, one confirmed traditional-vertical-script book of unidentified content.
- **`26 Blue Mongolian Dictionary Complete.pdf` at 3,166 pages** and **`Divine-knowledge...Mostaert's
  Manual of Mongolian Astrology and Divination.pdf` at 2,244 pages** will need this project's
  representative-sampling convention more aggressively than almost anything else triaged in this
  project so far — these are the two largest files in the harvest after the excluded trilingual
  dictionaries.
- **No flagship slang/colloquial-register title exists** (§10c) — a real, flaggable gap if Mongolian
  slang coverage matters to the Tepenian handoff, parallel to the Malay gap found in this project's
  most recent prior triage.
- **No graded-reader material exists** (§10h) — Tier 5 is empty.
- **2 of the 7 named scholarly papers turned out to be exact duplicates** of files already present on
  the external drive and SSD (§3) — only 4 of the 7 (+the unexpected 8th, which is contamination, not
  content) supplied genuinely new material.
- Vision-read proportion within the in-scope set is roughly even (34 TEXT / 32 vision / 1 epub,
  ~48% vision) — moderate, nowhere near as vision-dominated as this project's German or Cantonese
  triages.
- Scratch render files (title-page renders for the handful of generic-filenamed vision-only PDFs, the
  raw TSV, the md5-grouping table) have been deleted from the scratchpad per the project's
  disk-space instruction; nothing was written to the external drive or `source_reference/`.
