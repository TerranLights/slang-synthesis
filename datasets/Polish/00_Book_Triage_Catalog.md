# Polish — Book Triage Catalog

**Triage complete, 2026-11-03.** First-ever triage for Polish in this project, per the
`TepenianLanguage` handoff. **Triage only — no extraction dispatched.** Done last and in batches by
subfolder, per the handoff's own instruction given this is the largest language in the batch.

**Locations:**
- External drive: `/media/kuroskalacs/Home-Theater/w-lang/Polish and Ukrainian/` — two packs,
  **1,015 files total**: `Polish and Ukrainian Language Learning Pack (Updated)` (609 files) and
  `(Vol. 2)` (406 files)
- `/home/kuroskalacs/Documents/Doll-Fi/media/y-files/language-stash/Polish/` — 2 files (*Colloquial
  Polish*, Mazur; *Polish: A Comprehensive Grammar*, Sadowska — both named directly in the handoff)

**Raw harvest data:** `.triage_raw.tsv` (280 rows covering every Polish-relevant text-bearing file
across both packs — see §0 for how this scope was carved out of the 1,015).

---

## 0. How the 1,015 files were scoped down to 280 triaged this pass

Both packs are internally organized by content type, with Ukrainian (and in Vol. 2, Belarusian)
already segregated into their own named subfolders — this made it possible to separate Polish
triage work from the explicitly-out-of-scope Ukrainian/Belarusian material cleanly, rather than
needing to identify language file-by-file across all 1,015:

| Folder | Files | Size | Treatment |
|---|---|---|---|
| Updated/01 Beginners Courses | 30 | 1,303MB | Triaged |
| Updated/02 Intermediate-Advanced Courses | 8 | 410MB | Triaged |
| Updated/03 Reference Grammars and Workbooks | 12 | 279MB | Triaged |
| Updated/05 Phrasebooks, Dictionaries | 11 | 140MB | Triaged |
| Updated/04 Audio and Reading Books | 222 (135 text-bearing + 87 audio) | 1,312MB | Text-bearing files triaged; audio counted only |
| Updated/06 Video Courses+Miscellaneous | 132 (53 text-bearing + rest audio/video) | 4,373MB | Text-bearing files triaged; audio/video counted only |
| Updated/00 Book List | 8 | 1MB | Cover-photo JPGs, not triaged individually |
| Vol.2/01 Polish | 32 (29 text-bearing) | 700MB | Text-bearing files triaged |
| Vol.2/04 Language Learning Torrents | 137 | 13MB | Almost entirely `.torrent` pointer files (133 of 137), not real content — not triaged |
| Updated/08 Music+Lyrics | 149 | 763MB | **Pure audio/images (73 jpg, 68 mp3, 8 flac) — zero PDF/text content, not triaged at all** |
| **Updated/07 Ukrainian** | **37** | **951MB** | **Out of scope per handoff — counted only, see §6** |
| **Vol.2/02 Ukrainian** | **226** | **1,818MB** | **Out of scope per handoff — counted only, see §6** |
| **Vol.2/03 Belarusian** | **11** | **261MB** | **Not on the handoff's language list at all — counted only, see §6, same as Ukrainian** |

**280 Polish-relevant text-bearing files were harvested and triaged** (the sum of the "Triaged" rows
above). This catalog covers all 280, plus the 2 y-files.

---

## Headline numbers (of the 280 harvested + 2 y-files = 282)

| | |
|---|---|
| **Wrong language entirely — Czech, not Polish** (a mislabeled subfolder — see §1, the single biggest finding in this catalog) | **87** |
| **Corrupted/junk duplicate files** (identical broken content, 30 copies) | **30** |
| **Wrong language entirely — Upper Sorbian, Belarusian** (2 more non-Polish West Slavic items found loose in the misc folder) | **2** |
| **Excluded — wrong metalanguage or audience** | **~22** |
| **Flagged — translated commercial/copyrighted fiction** (not reference material; a scope decision, not a triage exclusion) | **~20 titles** |
| **Flagged for your ruling — Polish-medium-of-Polish** | **~24** |
| **Clearly in-scope English-medium candidates** | **~95** |

(Counts above "~" are close, hand-verified-at-scale estimates rather than machine-exact — this is
by far the largest single-batch triage done in this project; a few borderline items may shift
category on closer inspection without changing the overall picture.)

---

## 1. The biggest finding — an entire Czech-language subfolder mislabeled as Polish (87 files)

**`Updated/04 Audio and Reading Books/Knihy Odvahy a Dobrodruzstvi (CZ)/`** — 87 files, all
confirmed Czech-medium via text-layer snippets: publisher "STÁTNÍ NAKLADATELSTVÍ DĚTSKÉ KNIHY
PRAHA" (the Czech State Children's Book Publishing House), series title "Knihy Odvahy a
Dobrodružství" ("Books of Courage and Adventure," a real mid-20th-century Czech children's-
adventure book series), and consistently Czech orthography/diacritics throughout every sampled
snippet. The "(CZ)" in the folder name is the collector's own correct label — but this sits nested
inside a folder named "Audio and **Reading Books**" with no further language flag, so it's easy to
mistake for Polish material. **Not one of the seven handoff languages — entirely out of scope**,
parallel to the mislabeled Faroese folder found in Norwegian's triage. Contents are translated
Western adventure/children's classics (Cooper, Stevenson, Dumas, Sabatini, Verne-adjacent titles,
etc.) plus original Czech authors — not individually catalogued given the volume and total
irrelevance to Polish.

**Two more non-Polish West Slavic/Slavic items found loose, both excluded:**
- `Updated/06 Video Courses+Miscellaneous/Учебник верхнелужицкого языка.djvu` — a Russian-medium
  textbook of **Upper Sorbian**, a West Slavic minority language of Germany, related to but
  distinct from Polish. Flagging per the handoff's explicit ask to note any Czech/Slovak/other
  West Slavic titles encountered.
- `Updated/06 Video Courses+Miscellaneous/Базовый курс классического белорусского языка.djvu` — a
  Russian-medium **Belarusian** course, sitting outside the dedicated Belarusian subfolder (§6).

---

## 2. Corrupted/junk files — not real content (30 files)

**`Updated/06 Video Courses+Miscellaneous/05 Польская матрица/`** — 30 `.txt` files
(`01pl.txt` through `30pl.txt`). Every single one contains **identical** content — the opening of
*The Rough Guide to Poland* — regardless of filename. This is not 30 distinct documents; it looks
like a broken or abandoned batch-OCR/extraction experiment by whoever originally assembled this
stash ("Польская матрица" = "Polish matrix"). Not real content, not triaged further, not an
extraction target.

---

## 3. EXCLUDE — wrong metalanguage or wrong audience (~22 files)

| File | Issue |
|---|---|
| `01/24 Практический курс польского языка` | Russian |
| `01/28 ЕШКО Польский для начинающих` | Russian |
| `01/27 Самоучитель польского языка` | Russian |
| `01/23 Польский с Нуля` | Russian |
| `01/29 Курс польского языка учебник` | Russian |
| `01/26 Hugo Polish in 3 months (Russian)` | Russian (marked in its own filename) |
| `01/14 Czesc Jak sie Masz — Polones para Iniciantes` | Portuguese |
| `01/22 Mowie Po Polsku — Učebnice Poľštiny` | Czech (the subtitle itself is Czech for "Polish textbook") |
| `03/10 Современный польский язык` | Russian |
| `05/11 Praktyczny słownik polsko-rosyjsko-ukraiński` | Non-English (Polish-Russian-Ukrainian) |
| `05/10 Ukrainian-Polish Polish-Ukrainian Dictionary` | Non-English |
| `05/06 Rozmówki Polsko-Portugalskie` | Non-English (Polish-Portuguese) |
| `05/12 Czesko-polski słownik tematyczny` | Non-English (Polish-Czech) |
| `V01/17 История и диалектология польского языка` | Russian |
| `V01/15 Польский язык. Учебник` | Russian |
| `V01/05 Польська мова за 4 тижні` | Ukrainian |
| `V01/07 Le Polonais de poche` | French |
| `V01/16 Польский язык. Учебник для высших учебных заведений` | Russian |
| `V01/23 Польша (Журнал Золотой глобус)` | Russian (travel magazine) |
| `V01/09 Практический курс польского языка (2-е изд.)` | Russian |
| `V01/22 Polsko-Niemiecki Słownik Tematyczny` | Non-English (Polish-German) |
| `V01/04 Livret de l'enregistrement et corrigés des exercices` | French (companion booklet to the `04 Dzień Dobry!` course, kept separately — §5) |

Also pure-tourism exclusions from `06 Video Courses+Miscellaneous`:
`The Rough Guide to Poland.pdf`, `Poland (Eyewitness Travel Guides).pdf`, `Cracow (Eyewitness
Travel Guides).pdf` — standard commercial guides.

---

## 4. FLAGGED — translated commercial/copyrighted fiction (a scope decision, ~20 titles)

A large and notable chunk of `04 Audio and Reading Books` and `Vol.2/01 Polish` is **Polish
translations of contemporary or still-copyrighted Western commercial fiction**, not reference
material. None of this was opened beyond a title/author identification pass. Distinct from the
public-domain classics and native-Polish literature kept in §5:

- **Harry Potter** — the complete 7-book series (Rowling), Polish translation
- **The Lord of the Rings** — all 3 volumes (Tolkien), Polish translation (Maria Skibniewska)
- **Twilight saga** — 4 books (Stephenie Meyer) + a near-duplicate standalone copy of *New Moon*
  (different page count, not byte-verified — check before treating as redundant)
- **Dragonlance** — the Chronicles trilogy + the Legends trilogy (Weis & Hickman), Polish translation
- **The Legend of Drizzt** — 6 books (R.A. Salvatore), Polish translation
- **Ender's Game series** — 3 books (Orson Scott Card), Polish translation
- **Fifty Shades of Grey** (E L James), Polish translation — flagging distinctly since it's adult
  content, not the children's/YA fiction dominating the rest of this list
- **The Boy in the Striped Pyjamas** (John Boyne), Polish translation
- **The Chronicles of Narnia** (opens with *The Lion, the Witch and the Wardrobe*, C.S. Lewis),
  Polish translation
- **The Moomins** — at least 5 Tove Jansson titles, Polish translation (Jansson died 2001 — still
  well within copyright)

Same standing treatment as Swedish's Jeffrey Archer novel and Harry Potter `.doc` — worth a
conscious decision, not default extraction, given active copyright on nearly all of these.

**Kept as in-scope, not flagged here** (public domain or genuinely Polish-original):
*Pinokio* (Collodi, 19th c., public domain), Perrault's *Czerwony Kapturek i Inne Bajki* (public
domain fairy tales), *Baśnie fińskie* (Finnish folk tales, likely public domain), the Brothers
Grimm fairy tales — and especially **`Król Maciuś Pierwszy` by Janusz Korczak** — a genuinely
**Polish-original** literary classic (not a translation; Korczak, d. 1942, wrote it in Polish in
1923), a strong native-literature candidate. **`A Chrestomathy of Polish Literature.pdf`** needs a
closer look before either keeping or excluding — its sampled text-layer snippet showed unrelated
Belarusian-law-institute content, suggesting either a mismatched/corrupted PDF or a cover-page
artifact; verify before use.

---

## 5. FLAGGED FOR YOUR RULING — Polish-medium-of-Polish (~24 files)

**RULING RECEIVED, 2026-11-04** (per `TepenianLanguage/handoffs_to_slang_synthesis/
2026-11-04_native_medium_ruling.md`, citing `TepenianLanguage/DECISIONS.md` D-25 Books written in
the target languages: usage study): *"Books written in target languages are to be used for
studying how the languages are used in practice."* These ~24 files are now **in scope as usage
material** — the ruling answers the medium question but not the mechanics: it does not say
when/how to extract them, nor whether output belongs in `established/` or `language_corpus/`
(this project's usage-corpus vs. reference-corpus distinction). **Do not extract on this ruling
alone — wait for the next explicit instruction.**

Same recurring pattern as every other language in this batch — real Polish-as-a-foreign-language
course/reference material written in Polish rather than English:

**Course series:** `Hurra Po Polsku` 1, 2, and 3 (+ Tests, Podręcznik Studenta, Zeszyt Ćwiczeń —
the level-3 volumes), `Czesc, Jak sie Masz` I/II (unmarked-medium copies, distinct from the
English-paired "A Polish Language Textbook" edition kept in §5's English pool), `Dzień Dobry!`,
`Milo mi Panią Poznać`, `Jezyk Polski w 4 Tygodnie`, `Zaczynam Mówić Po Polsku`, `Uczymy się
Polskiego — Teksty` (pdf + djvu), `Juz Mówię Po Polsku`, `Kiedyś wrócisz tu...` (I+II combined
volume, plus a possibly-related single-volume copy in Vol.2 — verify relationship), `Z polskim na
ty` (pdf + djvu), `Teraz Polski — Gry i ćwiczenia komunikacyjne`, `Mały Leonardo 8 — Język polski`,
`Język polski dla cudzoziemców. Ćwiczenia dla początkujących`.

**Grammar/reference (Polish-medium):** `Czas na Czasownik` (verb exercises), `Ortografia na Bardzo
Dobry` (orthography), `Przygoda z Gramatyka`, `Gramatyka w Szkole Podstawowej`, `Gramatyka Języka
Polskiego w ćwiczeniach`, `Wstęp do językoznawstwa` ("Introduction to linguistics" — academic),
`Wykłady z polskiej składni` ("Lectures on Polish syntax" — academic, likely high value if
included), `Metodyka Nauczania Języków Obcych` (foreign-language-teaching methodology, a different
kind of text than direct Polish content).

**Official certification materials:** `Tests B1.pdf` (confirmed Polish-medium, the official State
Commission B1 certification sample test) and the **16-file `04 ROZUMIENIE ZE SLUCHU` set**
(`Updated/06 Video Courses+Miscellaneous/`) — small B1-level listening-comprehension exercises with
transcripts and answer keys, genuinely useful graded material if the medium ruling favors
inclusion.

---

## 5a. Addendum (2026-11-03, later pass) — flagship slang candidate found in §5's pool

**`02 Kto Czyta - Nie Bladzi`** (`Updated/02 Intermediate-Advanced Courses/`), already counted in
§5's Polish-medium-of-Polish flagged group above, contains a chapter explicitly titled **"Język
młodzieży"** ("Youth language") with a sub-section **"Wypasiony słownik najmłodszej polszczyzny"**
(literally "tricked-out dictionary of the youngest generation's Polish") — a genuine youth-slang
glossary. This is Polish's flagship slang candidate (no other title in this harvest carries a
dedicated slang/argot section) — flagging it prominently here since §5 doesn't otherwise call out
individual titles' content, and this one matters disproportionately given how few of this
project's "flagged for ruling" piles turn out to contain a real slang payload. Still bound by the
same Polish-medium-of-itself ruling as the rest of §5 — not independently resolved by this note.

---

## 6. Ukrainian and Belarusian material — counted only, per the handoff

| Location | Files | Size |
|---|---|---|
| `Updated/07 Ukrainian` | 37 | 951MB |
| `Vol.2/02 Ukrainian` | 226 | 1,818MB |
| **Ukrainian total** | **263** | **~2.77GB** |
| `Vol.2/03 Belarusian` (not on the handoff's language list at all) | 11 | 261MB |

Not triaged in any depth — listed here for your later decision, per the handoff's explicit
instruction. Belarusian is included on the same "counted, not triaged" basis since it showed up
unprompted in the same shared folder.

---

## 7. What's clearly in scope (~95 files) — category overview

**Reference grammars (English-medium) — this is Polish's strongest category by far:**
`01 Polish Verbs and Essentials of Grammar.pdf` (TEXT, Oscar E. Swan), `02 A Grammar of
Contemporary Polish.pdf` (TEXT, Oscar E. Swan — a major standard reference), `04 Intermediate
Polish — A Grammar and Workbook.pdf` (TEXT), `03 Polish: An Essential Grammar.pdf`, `08 Gramática
Polaca.pdf` (note: Spanish-medium title but worth a closer check — possibly still useful given its
likely EN/ES-parallel structure, not independently confirmed), `09 Grammatik des Polnischen.pdf`
(German-medium, **exclude** — flagging the contradiction: this is in the Reference Grammars folder
but is German-medium like the Kauderwelsch titles elsewhere; move to §3's exclusion list), and the
y-files' **`Polish: A Comprehensive Grammar` (Sadowska)** — TEXT, a major modern reference, named
directly in the handoff.

**Dictionaries/phrasebooks (English-medium):**
`09 A Learner's Polish-English Dictionary.pdf` (TEXT, Oscar E. Swan), `08 Polish-English
Dictionary.pdf` (TEXT, Swan), `07 Polish Lexical Minimum.pdf` (TEXT, Swan — companion glossary to
*First-Year Polish*), `03 English-Polish Phrase Guide.pdf` (TEXT, Swan), `02 In-Flight Polish —
Learn Before You Land.pdf` (TEXT), `01 The Rough Guide Phrasebook Polish.pdf` (TEXT), `04
Kauderwelsch Polnisch Wort für Wort.pdf` — **note: this one is German-medium like all the other
Kauderwelsch titles in this project; move to §3, it was initially miscategorized by folder
location**, `21 Słownik Angielsko-Polski.pdf` and `21 Słownik Polsko-Angielski.pdf` (TEXT, the
EN↔PL pair from Vol.2).

**Courses (English-medium):**
`02 Teach Yourself Polish Conversation.pdf` (TEXT), `01 Teach Yourself One-Day Polish.pdf` (TEXT),
`03 Teach Yourself Polish 2003.pdf` (TEXT), `04 Teach Yourself Polish 1997.djvu`, `05 Teach
Yourself Polish 1948.pdf` (a historic edition), `11 Easy Learning Polish.pdf` (TEXT, Collins), `06
Colloquial Polish.pdf` — **likely the same book as the y-files' `Colloquial Polish` (Mazur)**, same
page count (169p); verify before treating as independently new, `13 Polish I — Reading Booklet.pdf`,
`07 Beginning Polish.pdf`, `10 Beginner's Polish.pdf`, `08 First-Year Polish.pdf` (TEXT, Oscar E.
Swan, University of Pittsburgh — a flagship academic course), `06 Polish Advanced Course.pdf` (TEXT,
Michel Thomas Method), `09 Czesc, Jak sie Masz — A Polish Language Textbook.pdf` (English-subtitled
edition — kept here rather than §5; note a second copy with a different page count exists, verify
relationship), `17 Uczmy się Polskiego 1 — Let's Learn Polish.pdf` (English-subtitled, same
ambiguity noted), `Hurra Po Polsku 3` test/textbook volumes that have English-adjacent certification
framing, `Polish Advanced Course.pdf`.

**Academic/sociolinguistic reference (English-medium):**
`The Phonology of Polish.pdf` (TEXT, same "World's Languages Phonology" series used throughout this
project).

**Native-language reading material / literature (in scope on its own terms, not needing the §5
medium ruling the way instructional material does):**
`Król Maciuś Pierwszy` (Korczak, genuinely Polish-original, flagged above in §4 as the standout),
the public-domain fairy-tale collections also noted in §4.

---

## 8. Extraction notes

- **This was the largest single triage in this project to date — 282 files examined (280 harvested
  + 2 y-files) out of the 1,015-file raw stash**, with the Ukrainian/Belarusian two-thirds of the
  raw count correctly set aside per the handoff rather than triaged.
- **The accidental Czech-language discovery (87 files) is the single most consequential finding** —
  it means the "04 Audio and Reading Books" folder name is not a reliable guide to either language
  or content type; don't assume the rest of that folder is uniformly Polish without the same
  per-file check already done here.
- Two titles were miscategorized by their folder location rather than their actual medium
  (`09 Grammatik des Polnischen` and `04 Kauderwelsch Polnisch Wort für Wort`, both German, both
  sitting in otherwise-legitimate reference folders) — a reminder that folder placement in this
  stash is not fully reliable, consistent with the Czech-folder finding.
- No frequency dictionary or frequency list was found for Polish.
- Given the scale, a handful of borderline/ambiguous items (noted inline above, e.g. the
  English-subtitled "Polish Language Textbook" editions, the `Kiedyś wrócisz tu` volume
  relationship, `A Chrestomathy of Polish Literature`) would benefit from a second look before
  dispatch — flagged rather than guessed.
- No rendering was needed anywhere in this pass; every identification came from filenames (heavily
  informative here, since most titles are themselves in Polish, Czech, or Russian) and text-layer
  snippets.

## 9. Not yet checked

Same open item as every other language in this batch: the two unsorted SSD folders
(`lang transfer bay/`, `xx--stash/`) haven't been searched for Polish material yet.
