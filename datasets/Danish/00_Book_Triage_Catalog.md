# Danish — Book Triage Catalog

**Triage complete, 2026-11-03.** First-ever triage for Danish in this project, done per the
`TepenianLanguage` handoff (Danish is a "second-era" / Tepenian-stage contributing-language
candidate, associated domain idea "technical studies," grouped with Scandinavian languages
generally). **Triage only — no extraction dispatched, nothing written to `established/`.**

**Note on a prior draft:** a less-thorough catalog existed at this path before this pass (dated
earlier today). This version supersedes it — it renders every ambiguous vision-only title instead
of leaving one unconfirmed, and it catches a real miscategorization in the earlier draft: `04 Aktivt
dansk Grammatik og ordliste` (both the `.pdf` and `.djvu` copies) was filed there as Danish-medium
("Aktivt dansk course" group); it is actually **Russian-medium** (confirmed by rendering the title
page: "ДЛЯ НАЧИНАЮЩИХ / ГРАММАТИКА И СЛОВАРЬ-МИНИМУМ," by Lise Bostrup & Svetlana Vvedenskaja) and
belongs in the wrong-metalanguage exclusion group instead, not the Danish-medium ruling group. This
version also completes the two marginal-stash assessments the handoff asked for, which the prior
draft deferred.

**Locations:**
- External drive: `/media/kuroskalacs/Home-Theater/w-lang/Danish/` (confirmed mounted) — **39
  files, 855MB**
- In-repo: `source_reference/languages/Danish/` — **14 files, 151MB**

**Raw harvest data:** `.triage_raw.tsv` (53 rows: folder, file, size_mb, pages, text_layer, md5).

**How titles were identified:** every ambiguous title was confirmed from its own title/copyright
page — text-layer PDFs via `pdftotext`, vision-only PDFs via `pdftoppm`, and the one ambiguous DJVU
via `ddjvu`. All 12 vision-only PDF/DJVU files were individually rendered and read, not inferred
from filename. **Checked for duplicates by filename and md5**, including across the external drive
and the in-repo folder: **all 14 in-repo files are byte-identical (md5) duplicates of files already
on the external drive — zero net-new content from the in-repo copy.**

---

## Headline numbers

| | |
|---|---|
| Total files harvested (both locations, summed) | **53** (39 external + 14 in-repo) |
| **Net-unique files** (in-repo is a 100% duplicate subset) | **39** = 37 PDF/DJVU + 1 JPG (non-content) + 1 MP3 (audio) |
| Text layer present (of 37) | **25 (68%)** |
| Vision-read required (of 37) | **12 (32%)** |
| **Excluded — wrong metalanguage** | **9** (6 Russian + 1 German + 2 Icelandic) — see §1 |
| **Excluded — out of scope (pure tourism)** | **2** — see §2 |
| **Flagged for your ruling — Danish-medium-of-Danish** | **16** — see §5 |
| **Clearly in scope, no ruling needed** | **10** (9 English-medium + 1 native Danish literature) — see §6 |
| Non-content assets (not extraction targets) | 1 JPG (collector's own folder-listing screenshot) |
| Audio (not extraction target) | 1 MP3 (companion to Language 30 phrase dictionary) |
| Packed archives not yet opened | none found |
| Bulk usage-corpus material | none found |
| Frequency dictionary/list found | **none** |
| Duplicate files (external vs in-repo, by md5) | **14 — the entire in-repo folder** |
| Wrong-language-entirely contamination | **none found** (checked for Norwegian/Swedish/Faroese/Greenlandic/Icelandic misfiling — see §3; the two Icelandic-**medium** items in §1 are a metalanguage issue, not a wrong-target-language one, since both are genuinely about Danish) |
| **Flagship slang/colloquial title** | **none found** — see the note at the end of §5 |

Check: 9 + 2 + 16 + 10 = 37 net PDF/DJVU files. ✓

This is the **least vision-dependent Scandinavian-family stash triaged in this project so far** —
only 32% of the 37 PDF/DJVU files need vision reading, well below Norwegian (77%) and in a different
range entirely from this project's more typical vision-dominated stashes (German 62%, Cantonese
73%). Most of the vision-only files sit in the flagged Danish-medium group (§5), not the
clearly-in-scope pool.

---

## 1. EXCLUDE — wrong metalanguage (9 files)

**Russian-medium (6 files)** — confirmed by Cyrillic title text, either via `pdftotext` or by
rendering the cover:

| File | Confirmation |
|---|---|
| `03 Учебник датского языка.djvu` | Rendered cover: "УЧЕБНИК ДАТСКОГО ЯЗЫКА" — "Textbook of the Danish Language" |
| `03 Учебник датского языка.pdf` | Same book, alternate/larger scan (130.66MB vs 4.88MB for the djvu — not byte-identical, both 242 pages) |
| `04 Aktivt dansk Grammatik og ordliste.djvu` | **Rendered**: "AKTIVT DANSK / ДЛЯ НАЧИНАЮЩИХ / ГРАММАТИКА И СЛОВАРЬ-МИНИМУМ" ("for beginners — grammar and minimum vocabulary"), by Lise Bostrup & Svetlana Vvedenskaja, Alfabeta — a Russian-medium companion grammar/wordlist to the (Danish-medium, kept-and-flagged) *Aktivt Dansk* course, same "wrong-audience companion hiding inside an otherwise-fine course family" pattern this project has hit before (Norwegian's På vei/Stein på stein wordlists, German's Moment Mal/Themen Aktuell glossaries). **This is the one correction to the prior draft of this catalog — see the note above.** |
| `04 Aktivt dansk Grammatik og ordliste.pdf` | Same book, alternate scan, not byte-identical to the djvu (09b2cd62... vs 6223d259... md5) |
| `25 Dansk-russisk ordbog.djvu` | `pdftotext`-read: "Датско русский словарь" / "Dansk russisk ordbog" — bilingual Danish-Russian dictionary, by Lise Bostrup et al. |
| `26 Stor dansk-russisk ordbog.djvu` | `pdftotext`-read: "БОЛЬШОЙ ДАТСКО-РУССКИЙ СЛОВАРЬ / STOR DANSK-RUSSISK ORDBOG" — "Big Danish-Russian Dictionary," ~160,000 entries, Moscow, 2000 |

**German-medium (1 file):**
| `15 Kauderwelsch Dänisch Wort für Wort.PDF` | `pdftotext`-read: German-medium throughout ("Können Sie mir helfen?" presented as German-medium learner apparatus) — same Reise Know-How Kauderwelsch series excluded for the same reason in this project's Norwegian and Swedish triages |

**Icelandic-medium (2 files)** — both confirmed by rendering, both published by Iceland's national
educational-materials body for teaching Danish to Icelandic schoolchildren (Danish is a compulsory
subject in Icelandic schools):

| File | Confirmation |
|---|---|
| `19 Dejlige Danmark.pdf` | **Rendered**: title page reads "NÁMSGAGNASTOFNUN... Reykjavík," with an Icelandic-language credits block ("Ritstjóri," "Yfirlestur," "Öll réttindi áskilin") and an explicit Icelandic cross-reference ("Hlustunaræfingar á neti, sjá www.nams.is") |
| `18 Ekko hlustunaraefingar.pdf` | **Rendered**: "EKKO HLUSTUNARÆFINGAR / NÁMSGAGNASTOFNUN" — "hlustunaræfingar" ("listening exercises") is Icelandic, not Danish (Danish would be "lytteøvelser"); same publisher as above |

Both are duplicated byte-for-byte in the in-repo folder (`07.Dejlige Danmark.pdf`,
`08.Ekko hlustunaraefingar.pdf`) — excluded there too, not counted twice.

---

## 2. EXCLUDE — out of scope, pure tourism (2 files)

- **`27 Denmark (DK Eyewitness Travel Guides).pdf`** (330p, TEXT) — confirmed via `pdftotext`:
  "EYEWITNESS TRAVEL / DENMARK / CASTLES • RESTAURANTS / VIKING HERITAGE..." — standard commercial
  travel guide, same standing exclusion as every other language's DK Eyewitness titles in this
  project.
- **`28 Copenhagen (DK Eyewitness Top 10 Travel Guides).pdf`** (132p, TEXT) — confirmed: "Top 10
  copenhagen... EYEWitnESS tRAVEL" — same series, same exclusion.

---

## 3. Wrong-language-entirely contamination check (none found)

Per the standing instruction (Norwegian's sibling triage just caught a real Faroese-misfiled-as-
Norwegian case), every file in both Danish locations was checked for whether it's actually written
**about** or **in** a different North Germanic/Scandinavian-adjacent language misfiled as Danish.
**No such case was found here.** Every file confirmed Danish-subject-matter is genuinely about
Danish — the two Icelandic items in §1 are Icelandic-**medium** material that teaches Danish (the
target/subject language is still Danish, only the explanatory apparatus is Icelandic), which is a
metalanguage problem, not a wrong-target-language one, so they're grouped with the Russian- and
German-medium exclusions in §1 rather than here.

---

## 4. Non-content assets and audio (2 files, not extraction targets)

- **`00 Book list.JPG`** — **read directly**: a screenshot of the original collector's own folder
  listing (filenames with file-type icons), not book content. It confirms the external-drive numbering
  scheme (items 01–28) and shows several items that exist in the collector's original inventory but
  did **not** make it onto this drive: `12 Tekster og billeder` (a companion to `12 Jokeren`), `14
  Danish Compact Course`, and `17 Goethe Verlag Аудиокурс датского языка` (a Russian-medium Goethe-
  Verlag audio course — would have been excluded anyway). It also confirms most numbered items
  originally had a matching `...Audio` companion in the collector's listing, but only one (`13
  Language 30`'s MP3) actually made it onto the drive — same "most audio companions weren't copied
  over" pattern seen in Norwegian's Book List screenshots.
- **1 MP3** (`13 Language 30 - Danish - Phrase dictionary and study guide.mp3`) — counted only, not
  an extraction target, per this project's standing audio convention; companion to the kept phrase
  dictionary PDF.

---

## 5. FLAGGED FOR YOUR RULING — Danish-medium-of-Danish (16 files)

Same recurring open question this project has hit for every Scandinavian-family language so far
(Norwegian's §5, Swedish's §5, closest siblings): this is real, substantial course and reference
material, written **in Danish**, mostly explicitly for "dansk som andetsprog" ("Danish as a second
language") learners already living in Denmark — not English-medium. Per the task's standing
instruction, a non-English-medium grammar/course of the language is never silently excluded or
silently kept — it's flagged here instead. **Not excluded, not kept — a decision is needed.**

### 5a. Lisbet Thorborg pronunciation/spoken-language series (6 files, Forlaget Synope / Akademisk Forlag)

All confirmed Danish-medium by direct content read, forming a coherent graded series by the same
author:

- **`05 Dansk udtale for begyndere.pdf`** ("Danish Pronunciation for Beginners")
- **`06 Dansk udtale i 49 tekster.pdf`** ("Danish Pronunciation in 49 Texts") — `pdftotext`-read:
  "udgør et supplement til 'Dansk udtale i praksis'" (a supplement to a related title not present in
  this harvest)
- **`07 Dansk udtale øvebog.PDF`** + **`07 Dansk udtale øvebog.djvu`** (2 files, same title,
  different scans, not byte-identical — md5 `7ea90f5e...` vs `ed0c3cb8...`, same "duplicate-edition,
  not duplicate-file" caution as prior languages' scan pairs) — `pdftotext`-read: "beregnet for
  undervisningen i dansk som andet- og fremmedsprog" ("intended for teaching Danish as a second and
  foreign language")
- **`08 Dansk talesprog i praksis.pdf`** ("Spoken Danish in Practice") — `pdftotext`-read: "er
  beregnet for udlændinge, der ønsker at lære dansk" ("intended for foreigners who want to learn
  Danish")
- **`09 Ind i samtalen Dialoger i hverdagen.pdf`** ("Into the Conversation — Everyday Dialogues") —
  `pdftotext`-read: "beregnet for undervisningen i dansk som andetsprog"

### 5b. Kirsten Ahlburg's Parlør dansk pair (2 files, Special-pædagogisk forlag)

- **`11 Parlør dansk - at samtale på dansk.pdf`** ("Danish Phrasebook — to converse in Danish") —
  **read**: Danish-medium dialogues explicitly written for refugee/immigrant learners (sample
  dialogue: "Jeg kommer fra det tidligere Jugoslavien... der er krig i mit hjemland," "I was in
  Denmark for three months")
- **`11 Parlør dansk - at skrive på dansk.pdf`** ("...to write in Danish") — **read**: same series,
  companion volume, covers Danish personal-ID-number conventions and common Danish given/surnames

### 5c. Lise Bostrup's Aktivt/Intensivt dansk course (4 files, Alfabeta)

- **`04 Aktivt dansk.pdf`** — **rendered**: "AKTIVT DANSK — EN BEGYNDERBOG I DANSK FOR UDENLANDSKE
  STUDERENDE" ("ACTIVE DANISH — A Beginner's Book in Danish for Foreign Students")
- **`04 Intensivt dansk.pdf`** + **`04 Intensivt dansk.djvu`** (2 files, same title, different
  scans, not byte-identical — md5 `6ec3ef05...` vs `e73882f1...`) — **rendered**: "INTENSIVT DANSK —
  ØVEHÆFTE I DANSK TIL KLASSEUNDERVISNING OG SELVSTUDIUM MED FACIT" ("INTENSIVE DANISH — Danish
  exercise booklet for classroom teaching and self-study, with answer key"), companion to `Aktivt
  dansk` above, same author
- (Note: `04 Aktivt dansk Grammatik og ordliste`, same series' third component, is **Russian-medium**
  and sits in §1, not here — see the correction note at the top of this catalog)

### 5d. Standalone items (4 files)

- **`Dansk Øvelsesbog Grundkursus.pdf`** ("Danish Exercise Book, Basic Course") — **read**: Danish-
  medium topic-labeled workbook with blank lines for answers (Univerb Förlag AB). This is one
  component of a 4-file English-narrated audio-course bundle the collector's Book List labels "10
  Univerb Danish Basic Course" — see §6 for the other three (English-medium) components of the same
  bundle, which are not flagged. Content here is mostly topic headings and blanks rather than
  continuous Danish prose, but it's flagged for consistency with the standing rule.
- **`23 Dansk grammatik med øvelser.PDF`** ("Danish Grammar with Exercises," Christian Planck,
  1982/1999) — **read**: Danish-medium, companion grammar to a textbook ("FAMILIEN JENSEN") not
  present in this harvest; "forudsætter et vist elementært kendskab til grammatik" (assumes some
  elementary grammar knowledge)
- **`24 Dansk fonetik i teori og praksis.pdf`** ("Danish Phonetics in Theory and Practice," Jens
  Rasmussen) — **read**: Danish-medium academic phonetics text, explicitly addressed to "alle der
  underviser udlændinge i dansk" ("everyone who teaches Danish to foreigners") — likely the highest
  individual reference value in this flagged group if the ruling favors inclusion.
- **`12 Jokeren Begyndersystem i Dansk for Udlændinge.pdf`** ("Jokeren: Beginner System in Danish
  for Foreigners," Per Pinholt, Gyldendal) — **read**: full Danish-medium beginner course, 14
  lessons, dialogue-driven (characters Ole, Rita, Aldo, Lili).
- **`16 Telefonsamtaler på dansk.pdf`** ("Telephone Conversations in Danish") — **read**: Danish-
  medium specialized phrasebook; contains a small idiom/etymology aside ("Idiomer: slå på tråden,
  hænge i telefonen... Etymologi: Tele- kommer af græsk...") but is a phone-conversation guide, not
  a dedicated idiom dictionary.

**No standalone slang/idiom-dictionary title turned up anywhere in this stash** — unlike Norwegian
(three flagged idiom/expression dictionaries) or Swedish (one), Danish's flagged group skews toward
pronunciation, spoken-language pedagogy, and general course material rather than idiom collections.
`16 Telefonsamtaler på dansk`'s brief idiom aside is the closest thing to a flagship slang/colloquial
item in this entire harvest, and it's a minor aside inside a specialized phrasebook, not a dedicated
title. **Flag this gap explicitly** — if the Tepenian handoff cares about Danish slang/colloquial
coverage, this stash does not currently supply a dedicated source for it.

---

## 6. What's clearly in scope — no ruling needed (10 files)

**Reference grammars (English-medium, confirmed):**
- `21 Danish An Elementary Grammar and Reader.pdf` (159p, vision) — **rendered**: "DANISH / AN
  ELEMENTARY GRAMMAR AND READER," clean English title page.
- `22 Danish An Essential Grammar.pdf` (225p, TEXT, 1st edition — **rendered/read**: "DANISH: AN
  ESSENTIAL GRAMMAR," Robin Allan, Philip Holmes, Tom Lundskær-Nielsen, Routledge) **and** `22
  Danish An Essential Grammar 2nd edition.pdf` (285p, vision — **rendered**: same title, "2nd
  Edition," Tom Lundskær-Nielsen and Philip Holmes) — **two genuinely different editions of the same
  Routledge grammar, not duplicate files** (different page counts, different md5, slightly different
  author-order credit). Dispatch one as primary and treat the other as a cross-check/fallback rather
  than extracting both as independent titles, same discipline as Norwegian's Strandskogen pair.

**Dictionaries/phrasebooks (English-medium, confirmed):**
- `13 Language 30 - Danish - Phrase dictionary and study guide.pdf` (31p, vision) — standard
  Berlitz/Language 30 series, same as this project's other Language 30 titles; its MP3 companion is
  the one audio file that survived onto this drive (§4).

**Courses (English-medium, confirmed):**
- `01 Colloquial Danish.pdf` (294p, TEXT) — **rendered**: "Colloquial Danish / The Complete Course
  for Beginners," W. Glyn Jones and Kirsten Gade, standard Routledge Colloquial series (same
  franchise as Norwegian's and Swedish's Colloquial titles already in this project — not a slang
  dictionary despite the series name).
- `02 Teach Yourself Danish.pdf` (141p, TEXT) — standard Teach Yourself series.
- **The "Univerb Danish Basic Course" bundle** (the collector's Book List item 10; 3 of its 4 files
  are English-medium and kept here, the 4th is Danish-medium and flagged in §5d):
  - `Danish Course Book.pdf` (12p, vision — **rendered and confirmed**, resolving the prior draft's
    "unconfirmed" flag): an English-medium "how to use this audio course" instruction booklet
    (reading-lesson methodology) followed by graded Danish reading-lesson word/phrase lists ("Unit
    Two: hej, nej, sej, leg, jeg..." building to full sentences by "Unit Ten: Danmark er et dejligt
    land"). Genuine English-narrated, Danish-content course material — in scope.
  - `Mini Grammar Book English Danish.pdf` (23p, TEXT) — **rendered and confirmed**: "MINI GRAMMAR
    BOOK / ENGLISH / DANISH," Univerb; explicit preface: "englishspoken people can rest assured that
    acquiring a working knowledge of Danish is by all means possible... we wish you good luck as you
    set out" — a concise English-medium reference grammar of Danish (spelling/pronunciation, nouns,
    adjectives, adverbs, verbs, pronouns, prepositions).
  - `English Workbook Basic course.pdf` (68p, TEXT) — **rendered and confirmed**: a parallel
    English-phrase drilling workbook with blank lines (same topic list as the Danish-medium
    `Dansk Øvelsesbog Grundkursus` in §5d: greetings, numbers, time, travel topics, etc.) — **caveat:
    every page examined contains English phrases only, no Danish text at all**. It's the matched
    "source-language" half of the same bilingual two-workbook pair (the student presumably hears
    audio pairing an English phrase with its Danish equivalent, writing each into the matching
    workbook), so it's genuinely part of the in-scope bundle rather than a stray wrong-language file
    — but on its own it has **no extraction value for Danish**, unlike its `Dansk Øvelsesbog`
    counterpart. Worth noting so no one wastes a dispatch on it expecting Danish content.

**Native Danish-language literature** (the text itself needs to be Danish — source/usage material,
not instructional apparatus, so the §5 medium question doesn't apply the same way):
- `20 H.C. Andersen - Eventyr og historier.djvu` (912p, TEXT) — **rendered and confirmed**: H.C.
  Andersen's own fairy tales ("Eventyr og Historier"), with an introduction by Johannes Møllehave,
  Forlaget Sesam, 2004/2005 — the canonical native-Danish literary source, same category as
  Norwegian's Asbjørnsen og Moe or Swedish's Astrid Lindgren.

---

## 7. Priority tiers (for the unambiguous pool, 10 files — excludes §5's 16 flagged files)

**Tier 1 — reference grammars & academic linguistics:** `22 Danish An Essential Grammar` (TEXT,
treat as one dispatch target with its 2nd edition per the note in §6 — same underlying work, two
editions), `21 Danish An Elementary Grammar and Reader`, `Mini Grammar Book English Danish` (TEXT,
cheap, concise). If the §5 ruling favors inclusion, `24 Dansk fonetik i teori og praksis` would be
the strongest addition to this tier.

**Tier 2 — vocab/dictionary/idiom/slang:** `13 Language 30 - Danish - Phrase dictionary and study
guide`. **No dedicated slang/idiom-specific title exists anywhere in this harvest, flagged or
unflagged** — see the gap noted at the end of §5. This is the thinnest Tier 2 of any Scandinavian-
family language triaged in this project so far.

**Tier 3 — verbs & reading/writing skill-building:** `Danish Course Book` (the graded reading-lesson
component of the Univerb bundle) is the closest fit; no standalone verb-conjugation reference was
found outside the grammar titles in Tier 1.

**Tier 4 — course series (lowest priority, highest cost):** `01 Colloquial Danish`, `02 Teach
Yourself Danish`, `English Workbook Basic course` (low value on its own — see the caveat in §6).

**Tier 5 — graded readers / native literature:** `20 H.C. Andersen - Eventyr og historier`.

---

## 8. Extraction notes

- **Only 12 of 37 net-unique PDF/DJVU files need vision reading (32%)** — the lowest vision-
  dependency ratio of any Scandinavian-family language triaged in this project; budget accordingly
  if extraction is authorized.
- **The §5 Danish-medium ruling covers 16 of 37 files (43%)** — proportionally smaller than
  Norwegian's equivalent §5 (41 of 101, ~41% — comparable) but, unlike Norwegian/Swedish, **contains
  no flagship slang/idiom candidate at all.** Recommend resolving this before any Danish extraction
  wave is planned, since without it the unambiguous pool is only 10 files and has no dedicated
  vocabulary/slang source.
- **`22 Danish An Essential Grammar` and `22 Danish An Essential Grammar 2nd edition` are two real
  editions of the same book, not duplicate files** — dispatch one as primary.
- **`07 Dansk udtale øvebog` (PDF vs DJVU) and `04 Intensivt dansk` (PDF vs DJVU) are same-title,
  different-scan pairs, not byte-identical** — spot-check both before committing to one as the
  dispatch source, same discipline as every prior language's duplicate-scan pairs.
- **`04 Aktivt dansk Grammatik og ordliste` (both PDF and DJVU) is Russian-medium, not Danish-medium**
  — this is the one correction to the earlier draft of this catalog; it belongs in §1 (excluded),
  not §5 (flagged). Anyone who already saw the earlier draft should note this change.
- No frequency dictionary or frequency list was found anywhere in this harvest for Danish.
- Scratch render files used for this triage (cover/content-page renders for every vision-only file,
  plus the extracted Greenlandic xlsx and Scandinavian-folklore epub contents used for §9) have been
  deleted per the project's disk-space instruction; nothing was written to the external drive.

---

## 9. The two marginal unsorted-stash items

### 9a. `lang transfer bay/Greenlandic/Greenlandic_English_Danish.xlsx`

**Judgment: belongs filed under Greenlandic, not Danish — noted here, not catalogued as a Danish
source, nothing moved.**

Opened and inspected directly (xlsx shared-strings extraction, not assumed from the filename): this
is a large (~18,600-entry) trilingual glossary with four parallel columns — New-orthography
Greenlandic, Old-orthography Greenlandic, English, and Danish — sourced from the Oqaasileriffik
(Greenland Language Secretariat)'s online Greenlandic-English dictionary
(`oqaasileriffik.gl/en/resources/greenlandicenglishdictionary`), credited to Lise Bostrup, Alexander
Uskov, Svetlana Vvedenskaja, and Thomas Hartvig Larsen (the same Bostrup/Vvedenskaja team behind the
Russian-medium *Aktivt Dansk* grammar in §1 and the Danish-Russian dictionaries). Every Danish entry
in this sheet is a short single-word/phrase gloss that simply parallels the English gloss on the same
row (e.g. "Why; well!" / "ih! nå da") — there is no Danish content here that isn't already present
in English form in the same row, and no continuous Danish prose anywhere in the file. Danish is
structurally a third bridge column on a Greenlandic dictionary, not a standalone Danish resource —
it adds no extraction value for Danish specifically that the English column doesn't already provide.

### 9b. `xx--stash/LibGen Lang/Scandinavian-Folk-History-Including-Finnish-Origins-Ancient-Icelandic-Folklore-Popular-Danish-Tales.epub`

**Judgment: substantial enough to catalog as a real English-medium Danish-folklore candidate — the
"Danish Popular Tales" section specifically, not the whole book.**

Opened and inspected directly (epub unzipped, each section's text extracted and word-counted, not
assumed from the filename). The book has four real content sections plus a title page and index:
"An Analysis of Certain Finnish Origins" (~10,600 words — Finnish, out of scope), "The Oldest
Icelandic Folk-Lore" (~5,000 words — Icelandic, out of scope), an index (~400 words), and **"Danish
Popular Tales"** (~16,400 words) — **the single largest section in the book, roughly half its total
content**, not a minor appendix. Read directly: this section is "Danish Popular Tales, Translated
from the Danish of Professor Grundtvig by Miss Jane Mulley" — an English translation of Svend
Grundtvig's canonical 1876/1878 *Danske Folkeæventyr* (Danish Folk Tales), the foundational
19th-century scholarly collection of Danish oral folklore, prefaced with substantial biographical and
methodological context about Grundtvig's collection work. This is genuine, citable, English-medium
Danish folklore reference material — recommend cataloging the "Danish Popular Tales" section alone
as a Tier 5-equivalent (graded-reader/native-folklore-adjacent) candidate if this title is ever
pulled into a Danish extraction wave; the Finnish and Icelandic sections of the same epub are not
relevant to Danish and should not be dispatched alongside it.
