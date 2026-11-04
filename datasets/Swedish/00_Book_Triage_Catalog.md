# Swedish — Book Triage Catalog

**Triage complete, 2026-11-03.** First-ever triage for Swedish in this project, done per the
`TepenianLanguage` handoff (`.../TepenianLanguage/handoffs_to_slang_synthesis/2026-11-03_later_stage_triage.md`).
**Triage only — no extraction dispatched.** Covers all four source locations in full: the external
drive, the SSD `source_reference/` copy, and the two previously-unsorted folders (`lang transfer
bay/Swedish/` and `xx--stash/LibGen--Sorted/Swedish/`) flagged as not-yet-checked in §9 of the first
pass — that sweep is now done, closing §9.

**Locations:**
- External drive: `/media/kuroskalacs/Home-Theater/w-lang/Swedish/` (confirmed mounted) — 126 files
- SSD: `source_reference/languages/Swedish/` (in this repo) — 20 files
- SSD unsorted: `source_reference/languages/lang transfer bay/Swedish/` — 7 files
- SSD unsorted: `source_reference/languages/xx--stash/LibGen--Sorted/Swedish/` — 3 files

**Raw harvest data:** `.triage_raw.tsv` (125 rows: location, folder, file, ext, size_mb, pages,
text_layer, first_page_snippet) — PDF/DJVU only; audio and the two `.doc` files are handled
separately below.

**How titles were identified:** for files with a text layer, the first 1-2 pages were read directly
(`pdftotext`). For image-only files, title was read from the filename plus genre/series context
(well-known publisher series: Teach Yourself, Colloquial, Routledge Essential Grammar, Barron's 201
Verbs, FSI, Berlitz, Living Language, Natur & Kultur's SFI course series) wherever that gave an
unambiguous, specific match. Where a title or its medium was genuinely in doubt, the title/copyright
page (or a representative content page) was rendered and read directly — done for *Swedish Fairy
Tales*, *The Svenssons*, *Шведский язык Ч.2 (Texts)*, and *Svenska idiom: 3.500 vardagsuttryck*,
each confirmed below.

---

## Headline numbers

| | |
|---|---|
| Files on the external drive | **126** (95 PDF/DJVU + 29 audio + 2 `.doc`) |
| Files on the SSD (`Swedish/`) | **20** (16 PDF + 4 DJVU) |
| Files in SSD unsorted (`lang transfer bay/Swedish/`) | **7** (all PDF) |
| Files in SSD unsorted (`xx--stash/LibGen--Sorted/Swedish/`) | **3** (all PDF) |
| **Total files harvested, all 4 locations** | **156** |
| **SSD files confirmed byte-identical (md5) to an external-drive file** | **17 — not counted again** |
| **`xx--stash` Glossika files confirmed byte-identical (md5) to the SSD Glossika copies** | **3 — not counted again** |
| **`lang transfer bay` Teach Yourself Swedish — confirmed same edition (Vera Croghan, 1995), different scan** | **1 — not counted again (see §4)** |
| **SSD/`lang transfer bay` files genuinely new** (Glossika Swedish 1-3 + 5 `lang transfer bay` titles) | **8** |
| **Net unique PDF/DJVU candidates before exclusions** | **104** |
| Text layer present | 31 |
| Vision-read required | 73 |
| **Excluded — wrong metalanguage/audience** | **16** (1 title present in 2 copies; includes the Old Swedish/German-medium Noreen grammar, see §1b) |
| **Excluded — out of scope** (translated-fiction anthology, pure tourism) | **4** |
| **Flagged for your ruling — Swedish-medium-of-Swedish** | **37** (not excluded, not extracted — see §5) |
| Non-PDF/DJVU documents found | 2 `.doc` files (one empty, one a full novel — see §4) |
| Audio files (not extraction targets) | 29 MP3s |

---

## 1. EXCLUDE — wrong metalanguage/audience (15 titles, 1 in two copies)

Confirmed by Cyrillic/non-English titles, or by reading the text-layer snippet directly:

| File | Medium | Confirmation |
|---|---|---|
| `07.Living Language - Виза в Швецию Аудиокурс шведского языка.pdf` | Russian | Cyrillic title |
| `05.Rysk-Svensk Parlor.djvu` | Russian/Swedish phrasebook, non-English | Title itself ("Rysk-Svensk" = Russian-Swedish) |
| `09.Berlitz. Шведский язык. Базовый курс.djvu` | Russian | Cyrillic title |
| `11.Шведский без репетитора.pdf` | Russian | Text-layer snippet, Russian author name |
| `12.Учебник шведского языка.djvu` | Russian | Cyrillic title |
| `15.Шведский язык Практический курс.pdf` | Russian | Cyrillic title |
| `14.Шведский язык. Самоучитель для начинающих.pdf` | Russian | Text-layer snippet, Cyrillic prose |
| `10.Разговорный шведский в диалогах.pdf` | Russian | Cyrillic title — **note:** easy to mistake for the genuine English-medium *Colloquial Swedish* titles by concept alone; it is not the same book |
| `06.På svenska! Studiehäfte (ryska).djvu` | Russian | "(ryska)" = "(Russian)" in the filename itself — the Russian-targeted edition of this course's study booklet, sitting alongside the course's otherwise-kept core volumes (see §5) |
| `05.Швеция (Журнал Золотой глобус).djvu` | Russian | Cyrillic title, travel magazine |
| `Шведский язык Ч.2 (Texts).pdf` (in `05 Reading Books/`) | Russian | **Rendered and confirmed**: Russian-medium reading texts with Russian footnoted commentary explaining the Swedish (e.g. a chapter titled "ТЕКСТЫ И КОММЕНТАРИИ") |
| `03.Kosmos Mini Woordenboek Zweeds-Nederlands Nederlands-Zweeds.pdf` | Dutch | Text-layer snippet, Dutch title |
| `04.Svensk grammatik på ryska.djvu` | Russian | Title itself — "Swedish grammar, in Russian" |
| `08.Schwedisch Lehrbuch - Hueber.pdf` | German | Title itself — "Schwedisch" = "Swedish" in German; Hueber is a German publisher |
| `10.Parlons suédois Langue, histoire et culture.pdf` (external) **and** `11.Parlons Suedois.pdf` (SSD, byte-identical copy) | French | Text-layer snippet, French prose ("La Suède (Sverige) est, par la taille...") |
| `lang transfer bay/Swedish/Old Swedish; Altschwedische Grammatik (Noreen) (1904).pdf` | German | Confirmed via rendered/extracted text: title page reads "ALTNORDISCHE GRAMMATIK II. ALTSCHWEDISCHE GRAMMATIK MIT EINSCHLUSS DES ALTGUTNISCHEN VON ADOLF NOREEN. HALLE. MAX NIEMEYER. 1904" — volume 8 of the German-language series *Sammlung kurzer Grammatiken germanischer Dialekte*. Entirely German-medium prose throughout the sampled pages. See §1b — also flagged separately for its historical-stage status. |

---

## 1b. Old Swedish — distinct historical stage, flagged separately (1 file)

**`Old Swedish; Altschwedische Grammatik (Noreen) (1904).pdf`** (676p, TEXT, 35MB) is Adolf Noreen's
*Altschwedische Grammatik mit Einschluss des Altgutnischen* ("Old Swedish Grammar, including Old
Gutnish") — a foundational historical-linguistics reference grammar of **Old Swedish** (the medieval
stage of the language, roughly 13th-16th century), not modern Swedish. Per this project's standing
rule for historical-stage material: **catalog it, but keep it out of every modern-Swedish count and
tier above** — it describes a different, earlier language stage, not a stylistic or dialectal variant
of the modern language the rest of this catalog covers.

It is excluded above on wrong-metalanguage grounds (German-medium, like the Hueber and Parlons
suédois exclusions in §1) — a double reason to exclude, not just one. If a future historical/diachronic
phase of this project wants Old Swedish material specifically, this is a real, substantial (676-page),
clean-text-layer candidate worth revisiting on its own terms rather than folded into the modern-Swedish
pool.

---

## 2. EXCLUDE — out of scope (4 files)

- **`Swedish Fairy Tales.pdf`** (in `05 Reading Books/`) — **rendered and confirmed**: Herman
  Hofberg's classic English-language translation anthology. This is English prose *about* Swedish
  folklore, not Swedish-language source text — wrong content type for this project's purposes
  despite sitting in the reading-material folder.
- `07.Frommer's Stockholm Day by Day.pdf`, `06.Stockholm (Eyewitness Travel Guides).pdf`,
  `04.Sweden (DK Eyewitness Travel Guide).pdf` — confirmed standard commercial travel guides (text
  layer spot-checked), no language-pedagogical content, same standing exclusion as other languages'
  Frommer's/DK Eyewitness titles. **Kept, not excluded:** `08.Historical Dictionary of Sweden.pdf`
  and `01.Culture and Customs of Sweden.pdf` — both confirmed academic reference works (Historical
  Dictionaries of Europe series; Greenwood's Culture and Customs series), not tourism guides.

---

## 3. Non-content documents and audio (not extraction targets)

- **`01 Beginners Courses/20.Swedish Compact Booklet.doc`** — checked via file metadata: 1 page, 1
  word, 7 characters. Effectively empty.
- **`05 Reading Books/Harry Potter och de Vises Sten.doc`** — checked via file metadata only (word
  count: 84,741 — consistent with the full novel's length, not excerpted). **This is the complete
  Swedish translation of a copyrighted novel still in print; out of scope, not opened further.** Its
  companion is a 14-part MP3 audiobook in the same folder (`Harry Potter och de Vises Sten Audio
  Book/`) — both are a matched audiobook+text set, neither a target.
- **29 MP3 files**, two sets: the Harry Potter audiobook above (14 parts, companion to the excluded
  `.doc`), and 15 standalone Swedish folk songs (`06 Culture, Travel Guides/Swedish Folk Songs/`,
  no companion text). Counted only, not extraction targets per the handoff's audio convention.

---

## 4. Same-title, different-format pairs — verify before dispatch

Checked by md5; **none of these are byte-identical** (unlike the SSD/external duplicates in §0),
so they are different scans of the same edition, not confirmed-redundant copies. Pick whichever
renders more cleanly as the dispatch source, keep the other as fallback, same discipline as
Cantonese's Comprehensive Grammar djvu/pdf twins:

| Title | Format A | Format B |
|---|---|---|
| Pictorial Swedish Dictionary | `.pdf`, 33p | `.djvu`, 33p |
| Teach Yourself Swedish | `.pdf`, 159p | `.djvu`, 159p |
| Nya mål 3 Lärobok | `.pdf`, 318p, TEXT | `.djvu`, 353p |
| Nya mål 3 Övningsbok | `.pdf`, 174p | `.djvu`, 192p |
| Svenska för Utländska Studenter | `.pdf`, 128p | `.djvu`, 131p |

**A third copy found in `lang transfer bay/Swedish/`:** `Swedish, Teach Yourself.pdf` (159p,
vision-required) is **not byte-identical** to either the external-drive `.pdf`/`.djvu` pair or to
the SSD's `05.Teach Yourself Swedish.pdf`, but a rendered title-page comparison confirms it is the
**same edition** — Vera Croghan's 1995/1996 *Teach Yourself Swedish* (Hodder Headline/NTC) — just a
third, lower-quality scan (carries a "print-driver.com UNREGISTERED VERSION" watermark stamp not
present on the other two scans). This is a **triplicate of the same edition across three scans, not
new content** — not counted toward the net-unique total. Distinct from
`Swedish, Teach Yourself (McClean) (1947).pdf` (335p) in the same `lang transfer bay` folder, which
**is** a genuinely different, older 1947 edition by R. J. McClean (confirmed via rendered title
page: "TEACH YOURSELF SWEDISH, A Grammar of the Modern Language, By R. J. McCLEAN... The English
Universities Press Ltd") — that one is new, in-scope content, added to Tier 3 below.

**The three `xx--stash/LibGen--Sorted/Swedish/Glossika-Swedish-Fluency-{1,2,3}.pdf` files are
byte-identical (md5) to the three already-catalogued SSD Glossika Swedish Complete Fluency Course
volumes** (`Campbell M., Bruus M. - Glossika Swedish...` levels 1-3) — exact duplicates, not new
content.

---

## 5. FLAGGED FOR YOUR RULING — Swedish-medium-of-Swedish (37 files)

**RULING RECEIVED, 2026-11-04** (per `TepenianLanguage/handoffs_to_slang_synthesis/
2026-11-04_native_medium_ruling.md`, citing `TepenianLanguage/DECISIONS.md` D-25 Books written in
the target languages: usage study): *"Books written in target languages are to be used for
studying how the languages are used in practice."* These 37 files are now **in scope as usage
material** — the ruling answers the medium question but not the mechanics. It does not say when
or how to extract them, nor whether the output belongs in `established/` or `language_corpus/`
(this project's usage-corpus vs. reference-corpus distinction, see
`usage_corpus_vs_reference_corpus` in project memory). **Do not extract on this ruling alone — wait
for the next explicit instruction.**

Per the handoff's explicit instruction, these are **not excluded and not kept by default** — they
are genuine Swedish-as-a-second-language course materials (the SFI — *Svenska för invandrare* —
tradition: explanatory apparatus, instructions, and grammar notes written **in Swedish**, for
learners already living in Sweden, not in English for an English-speaking learner abroad). They are
real, substantial, often excellent material — just a different intended audience than this project's
standing English-medium convention assumes. **A decision is needed on whether to extract them.**

**Course series (grouped by series, all Swedish-medium):**
- **Nya mål** 1/2/3 — Lärobok ("textbook") + Övningsbok ("workbook") per level, 2/3 also with a
  Facit ("answer key")
- **Mål 1**, **Mål 2**, **Mitt i mål** — the earlier version of the same course sequence
- **Rivstart A1+A2** — Textbok, Övningsbok, 2 Facit volumes, Hörförståelse ("listening
  comprehension" transcripts) — **and Rivstart B1+B2** — Textbok, Övningsbok
- **På svenska!** — Lärobok, Övningsbok, Facit (the Russian-targeted Studiehäfte companion is
  already excluded in §1) — **and its sequel Pa Svenska 2!**
- **Svenska för Utländska Studenter** ("Swedish for Foreign Students") + its Facit
- **Svenska Utifrån** ("Swedish from the Outside") + its pronunciation-guide companion
  (Uttalsanvisningar)
- **Text i fokus** 1/2 — a reading-focused course
- **Form i fokus** — Övningsbok i svensk grammatik, Del A/B/C — a grammar-exercise course

**Standalone grammar references (Swedish-medium):**
- **Funktionell Svensk Grammatik** (likely Maria Bolander — the OCR'd author name on the snippet is
  garbled, worth confirming before citing)
- **Deskriptiv Svensk Grammatik**

**Culture/civics texts (Swedish-medium):**
- **Bli bekant med Sverige** ("Get Acquainted with Sweden")
- **Det ska vi fira — Svenska Traditioner och Högtider** ("That We Shall Celebrate — Swedish
  Traditions and Holidays")

**The flagship slang/idiom candidate is also in this group:**
- **`Svenska idiom: 3.500 vardagsuttryck`** (Hans Luthman) — **rendered and confirmed**: a genuine,
  substantial monolingual Swedish idiom dictionary (alphabetized by key word, each entry with a
  Swedish-language gloss and an example sentence — not reproduced here). This is exactly the
  flagship-slang-category title the project wants most from a stash, but it is Swedish-medium, so
  it sits in this flagged group rather than Tier 1 below pending your ruling.

---

## 6. What's clearly in scope — category overview (no ruling needed)

**Reference grammars (English-medium):**
*Essential Swedish Grammar* (91p, vision), *Swedish: An Essential Grammar* (260p, TEXT, Holmes &
Hinchliffe, Routledge), *Essentials of Swedish Grammar: A Practical Guide* (157p, vision), *201
Swedish Verbs* (71p, vision). **Caution:** the first two of these have near-identical titles but are
different books by different publishers — confirmed distinct via their text-layer snippets, not
assumed.

**New from `lang transfer bay/Swedish/` (found in this pass, closing §9's gap):**
- ***Modern Swedish Grammar*** (Björkhagen, 1923, 208p, TEXT) — a classic English-medium reference
  grammar, confirmed via its preface ("Lecturer in Swedish, in the University of London"); historically
  significant as one of the earliest dedicated English-medium Swedish grammars.
- ***Swedish Grammar and Reader*** (Uppvall, 274p, TEXT) — Axel Johan Uppvall, Professor of
  Scandinavian Languages, University of Pennsylvania; combines a reference grammar with a graded
  reader section, English-medium, confirmed via its preface.
- ***Swedish*** (Andersson, 42p, TEXT) — a dense academic-linguistics chapter by Erik Andersson
  (confirmed English-medium; reads as a language-family-survey chapter, e.g. from a comparative
  Germanic-languages volume — length and register are consistent with that genre, not a standalone
  book), covering sociolinguistic distribution, dialects, and typology. Short but a genuine
  academic-linguistics addition, same category as German's *A History of the German Language* or
  Cantonese's *Language Relations in Guangzhou*.
- ***Teach Yourself Swedish*** (McClean, 1947, 335p, vision) — R. J. McClean's original 1947
  edition, confirmed via rendered title page ("A Grammar of the Modern Language," The English
  Universities Press Ltd) — a genuinely distinct, much older edition from the already-catalogued
  1995 Croghan edition, not a duplicate (see §4).
- ***Beginning Swedish*** (G. Johnson, University of Illinois, 1939, 298p, TEXT) — an English-medium
  lesson-based course "intended for elementary classes in high schools and colleges" (per its own
  preface), Google/HathiTrust-digitized, confirmed via its preface and Lesson I pronunciation content.

**Dictionaries/phrasebooks (English-medium):**
*Norstedts Lilla Engelska Ordbok* (EN-SV/SV-EN, 951p, vision), *Prismas Engelska Ordbok* (EN-SV/
SV-EN, 945p, vision, duplicated across both locations), *Pictorial Swedish Dictionary* (33p, vision,
format pair — see §4), *In-Flight Swedish* (20p, TEXT, a short phrasebook).

**Courses (English-medium):**
*Colloquial Swedish* 1996 and 2007 editions (both TEXT, the 2007 duplicated across both locations),
*Teach Yourself Swedish* (159p, vision, format pair), *Teach Yourself Speak Swedish with Confidence*
(+ its Booklet, TEXT), *Swedish Basic Course* (FSI, 703p, vision — the classic public-domain Foreign
Service Institute course), *Advanced Spoken Swedish* (85p, vision, likely the FSI companion
advanced-level course), *Beginner's Swedish* (136p, vision), and the **Glossika Swedish Complete
Fluency Course** (levels 1-3, SSD-only, 368p each, TEXT — a modern sentence-mining-style course, EN-SV
throughout).

**Culture/history reference (English-medium, academic):**
*Historical Dictionary of Sweden* (359p, TEXT), *Culture and Customs of Sweden* (221p, TEXT).

**Reading Books — Swedish-source literature (usage-corpus/graded-reader material, not instructional
apparatus, so the §5 medium question doesn't apply the same way — the text itself needs to be in
Swedish):**
- **9 Astrid Lindgren titles** — *Lillebror och Karlsson på taket*, *Karlsson på taket flyger igen*,
  *Karlsson på taket smyger igen*, *Pippi Långstrump går ombord*, *Kalle Blomkvist och Rasmus*,
  *Mästerdetektiven Blomkvist*, *Mästerdetektiven Blomkvist lever farligt*, *Emil i Lönneberga*,
  *Vi på Saltkråkan* — major, globally-recognized Swedish children's-literature author, native
  Swedish-language texts.
- *Mummintrollets första vinter* — a Moomin title; Tove Jansson wrote the originals in Swedish
  (she was a Finland-Swedish author), so this is native-language text, not a translation.
- *Johanna Holmström — Tvåsamhet* (contemporary Finland-Swedish author), *Tord Wallström — Då hon
  dog* (TEXT, native Swedish crime novel), *Rainer Alander — Små stycken av Stockholm* and *Mellan
  Stockholm och Åbo* (travel essays), *The Svenssons (Texts 1-22)* (**rendered and confirmed**:
  SFI-style graded reading texts about a family, Swedish-medium, genuinely a reader not a course).
- **`Jeffrey Archer — Till varje pris.djvu`** — a Swedish translation of a contemporary
  copyrighted commercial novel (not public domain, unlike the Lindgren/Jansson classics). Flagging
  this one specifically alongside the harder Harry Potter exclusion in §3 — lower priority, and
  worth a conscious decision rather than default inclusion, given its copyright status.

---

## 7. Priority tiers (for the unambiguous English-medium pool only — excludes §5's flagged group)

**Tier 1 — flagship:** none of the unambiguous English-medium titles are slang/colloquial-specific;
the actual flagship candidate (*Svenska idiom*) sits in §5 pending your ruling. If the Swedish-medium
question resolves toward extraction, that title should lead Tier 1 outright.

**Tier 2 — reference grammars + dictionaries:** *Swedish: An Essential Grammar* (TEXT, cheapest),
*Essential Swedish Grammar*, *Essentials of Swedish Grammar*, *201 Swedish Verbs*, the two EN-SV
general dictionaries, *Pictorial Swedish Dictionary*, plus three newly-found `lang transfer bay`
titles: ***Modern Swedish Grammar*** (Björkhagen 1923, TEXT), ***Swedish Grammar and Reader***
(Uppvall, TEXT), and ***Swedish*** (Andersson, 42p academic-linguistics chapter, TEXT, cheapest of
the three).

**Tier 3 — courses:** *Colloquial Swedish* (both editions), *Teach Yourself Swedish* (+ Confidence
title), *Swedish Basic Course* (FSI), *Advanced Spoken Swedish*, *Beginner's Swedish*, Glossika
levels 1-3, plus two newly-found `lang transfer bay` titles: ***Teach Yourself Swedish*** (McClean
1947 edition — distinct from the already-listed Croghan edition, vision) and ***Beginning Swedish***
(G. Johnson, 1939, TEXT).

**Tier 4 — culture/history:** *Historical Dictionary of Sweden*, *Culture and Customs of Sweden*.

**Tier 5 — graded readers / native literature:** the Astrid Lindgren set, Moomin, Holmström,
Wallström, Alander, *The Svenssons*. (Archer's translated novel held back per §6's copyright note
pending a decision.)

---

## 8. Extraction notes

- **73 of 104 net-unique files need vision reading (70%)** — budget accordingly if extraction is
  authorized; this is a vision-dominant stash (slightly improved from the first pass's 73% once the
  five new, mostly-TEXT `lang transfer bay` titles are folded in).
- The **5 duplicate-format pairs** in §4 are not byte-identical — spot-check both before committing
  to one as the dispatch source. The 3rd Teach Yourself Swedish scan found in `lang transfer bay`
  (§4) is a worse-quality triplicate of the same edition, not a new dispatch candidate.
- **The §5 Swedish-medium ruling affects the largest single block of content in this stash** (37 of
  104 files, over a third) — recommend resolving this before any Swedish extraction wave is planned,
  since it changes both the wave structure and which title leads Tier 1.
- No frequency dictionary or frequency list was found in any of the four locations for Swedish.
- **The Old Swedish (Noreen 1904) grammar (§1b) is worth flagging to whoever owns historical/
  diachronic language work** — it's a real, substantial, clean-text 676-page reference grammar of a
  genuinely different language stage, just excluded here on German-medium grounds and kept out of
  all modern-Swedish totals.
- Scratch render files used for this triage (title/sample pages, including the Teach Yourself
  edition-comparison renders) have been deleted per the handoff's disk-space instruction; nothing
  was written to the external drive or to `source_reference/`.

## 9. `lang transfer bay` and `xx--stash` sweep — CLOSED, 2026-11-03

The gap flagged in the first triage pass (§9 as originally written) is now closed: both
`source_reference/languages/lang transfer bay/Swedish/` (7 files) and
`source_reference/languages/xx--stash/LibGen--Sorted/Swedish/` (3 files) have been fully triaged.
Net result: **3 of the 10 files were exact or near-exact duplicates of already-catalogued material**
(the 3 `xx--stash` Glossika PDFs are byte-identical to the SSD copies; 1 `lang transfer bay` Teach
Yourself scan is a non-identical but same-edition triplicate — see §4), **1 is excluded** (the Old
Swedish/German-medium Noreen grammar, §1b), and **5 are genuinely new, in-scope English-medium
titles** added to Tiers 2-3 above (Björkhagen, Uppvall, Andersson, McClean 1947 Teach Yourself,
G. Johnson's Beginning Swedish). No slang/colloquial or Swedish-medium material was found in either
of these two folders.
