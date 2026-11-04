# Norwegian — Book Triage Catalog

**Triage complete, 2026-11-03.** First-ever triage for Norwegian in this project, done per the
`TepenianLanguage` handoff (Norwegian is a "second-era" / Tepenian-stage contributing-language
candidate, associated domain idea "technical studies," grouped with Scandinavian languages
generally). **Triage only — no extraction dispatched, nothing written to `established/`.**

**Location:** `/media/kuroskalacs/Home-Theater/w-lang/Norwegian/` (external drive, confirmed
mounted) — **109 files, 3.0GB.** This is the only location for Norwegian: already confirmed absent
from `source_reference/languages/` and from the two in-repo unsorted stashes (`lang transfer bay/`,
`xx--stash/`) before this triage began, so no second sweep was needed.

**Raw harvest data:** `.triage_raw.tsv` (101 rows covering every PDF/DJVU: folder, file, size_mb,
pages, text_layer, plus an md5 column used for the duplicate check below).

**How titles were identified:** every title was confirmed from its own title/copyright page, not
guessed from the filename — text-layer files via `pdftotext`, image-only PDFs via `pdftoppm`, and
the DJVUs via `ddjvu`. Roughly 40 of the 101 files were individually rendered and read (not just
pattern-matched from filename/series), because this stash turned out to need it far more than most:
a large block of Norwegian-medium immigrant-course material whose medium isn't obvious from the
title alone, and a folder of reading books that turned out to be mostly a different language
entirely (§2). Checked for duplicates by filename **and** md5 — no duplicate files found anywhere
in the harvest (every md5 and every filename is unique).

---

## Headline numbers

| | |
|---|---|
| Total files harvested | **109** (101 PDF/DJVU + 7 JPG + 1 MP3) |
| Text layer present (of 101) | **23** |
| Vision-read required (of 101) | **78 (77%)** |
| **Excluded — wrong metalanguage/audience** | **22** |
| **Excluded — wrong language entirely (Faroese, not Norwegian)** | **10** — see §2, the biggest finding here |
| **Excluded — out of scope (pure tourism)** | **1** |
| **Flagged for your ruling — Norwegian/German/Portuguese-medium-of-Norwegian** | **41** — see §5 |
| **Clearly in scope, no ruling needed (English-medium + native-language reading)** | **27** |
| Non-content assets (not extraction targets) | 7 JPGs (5 inventory screenshots + 2 stock photos) |
| Audio (not extraction target) | 1 MP3 (Berlitz companion) |
| Packed archives not yet opened | none found |
| Bulk usage-corpus material (newspapers/magazines) | none found |
| Frequency dictionary/list found | **none** |
| Duplicate files (by filename or md5) | **none** |

Check: 22 + 1 + 10 + 41 + 27 = 101 net PDF/DJVU files. ✓

This is a vision-dominated stash — 77% of the 101 PDF/DJVU files need vision reading, in the same
range as German (62% of real candidates) and Cantonese (73%), driven mostly by the large
old-scan-heavy immigrant-course block in §5.

---

## 1. EXCLUDE — wrong metalanguage/audience (22 files)

Confirmed by Cyrillic/Czech/Polish/Serbian title text, by direct `pdftotext`/render content checks,
or by the targeted-audience language named in the file itself:

| File | Medium | Confirmation |
|---|---|---|
| `01 Audio Courses, Textbooks/22 Norština nejen pro samouky.djvu` | Czech | "Norština" = "Norwegian" in Czech; "...not only for self-learners" |
| `01 Audio Courses, Textbooks/22 Norština nejen pro samouky Klič+Slovník.djvu` | Czech | companion key/vocabulary volume, same course |
| `01 Audio Courses, Textbooks/22 Norština nejen pro samouky Klič+Slovník.pdf` | Czech | same, alternate scan format |
| `01 Audio Courses, Textbooks/22 Norština nejen pro samouky.pdf` | Czech | same, alternate scan format |
| `01 Audio Courses, Textbooks/23 Norweski dla początkujących.pdf` | Polish | **Rendered/read**: "Serdecznie witamy na kursie języka norweskiego dla początkujących" = "Welcome to the Norwegian course for beginners" |
| `01 Audio Courses, Textbooks/24 Norveški audio kurs sa integrisanim audiom.pdf` | Serbian/Croatian/Bosnian | **Rendered/read**: Latin-script Serbo-Croatian phrases ("Dobro jutro," "Doviđenja") paired with Norwegian |
| `01 Audio Courses, Textbooks/25 Учебник норвежского языка.djvu` | Russian | "Textbook of the Norwegian language" |
| `01 Audio Courses, Textbooks/26 Норвежский язык Практический курс.djvu` | Russian | "Norwegian language. Practical course" |
| `01 Audio Courses, Textbooks/27 Учебник норвежского языка. Вводный курс.pdf` | Russian | "...Introductory course" |
| `01 Audio Courses, Textbooks/27 Учебник норвежского языка для второго года обучения.pdf` | Russian | "...for the second year of study" |
| `01 Audio Courses, Textbooks/27 Учебник норвежского языка для первого года обучения Основной курс.pdf` | Russian | "...for the first year of study, main course" |
| `01 Audio Courses, Textbooks/28 Практический курс норвежского языка.djvu` | Russian | "Practical course of the Norwegian language" |
| `03 Dictionaries, Vocabulary, Phrasebooks/03 Berlitz Норвежский разговорник и словарь.pdf` | Russian | Cyrillic title, "Norwegian phrasebook and dictionary" |
| `03 Dictionaries, Vocabulary, Phrasebooks/04 Kauderwelsch Norwegisch Wort für Wort.pdf` | German | **Rendered/read**: German-medium pronunciation notes ("wie in Bär," "wie ei in Bein") — Kauderwelsch is a German phrasebook series, not a dedicated reference grammar, so this is a straightforward exclude rather than a flagged grammar (see §5's scope note) |
| `03 Dictionaries, Vocabulary, Phrasebooks/10 Stor Norsk-Russisk Ordbok Bind I.pdf` | Russian-targeted | "Big Norwegian-Russian Dictionary," vol. I |
| `03 Dictionaries, Vocabulary, Phrasebooks/10 Stor Norsk-Russisk Ordbok Bind II.pdf` | Russian-targeted | same, vol. II |
| `03 Dictionaries, Vocabulary, Phrasebooks/11 Ny Stor Russisk-Norsk Ordbok.djvu` | Russian-targeted | "New Big Russian-Norwegian Dictionary" |
| `03 Dictionaries, Vocabulary, Phrasebooks/12 Norsk-Vietnamesisk Ordbok.pdf` | Vietnamese-targeted | "Norwegian-Vietnamese Dictionary" |
| `03 Dictionaries, Vocabulary, Phrasebooks/14 Rysk-Svensk Parlor.djvu` | **Not Norwegian at all** | **Rendered/read**: title page reads "Русско-шведский разговорник / Rysk-svensk parlör" — a Russian-Swedish phrasebook (Moscow, "Русский язык," 1991). Has nothing to do with Norwegian; almost certainly a misfiled copy of the same book excluded in this project's Swedish triage (`05.Rysk-Svensk Parlor.djvu`, also a Russian-Swedish phrasebook) that ended up in the wrong folder on the source drive. Excluded on two independent grounds: wrong language and wrong metalanguage. |
| `01 Audio Courses, Textbooks/18 På vei Ordliste Norsk-Russisk.pdf` | Russian-targeted companion | **Read via `pdftotext`**: "norsk - russisk," "Oversatt til russisk av Language Power Centre" — a Russian-targeted wordlist bundled inside the otherwise Norwegian-medium *På vei* course (kept, flagged — see §5). Same "wrong-audience companion hiding inside an otherwise-fine course folder" pattern seen in German's Moment Mal/Themen Aktuell and Swedish's På svenska! |
| `01 Audio Courses, Textbooks/19 Stein på stein Ordliste Norsk-Russisk.pdf` | Russian-targeted companion | Same pattern, *Stein på stein* course, same publisher/series, same translator credit |
| `05 Society, Culture, Tourism/Фьорды Норвегии Путеводитель.pdf` | Russian | "Fjords of Norway: Guidebook" — excluded on two grounds, wrong metalanguage and tourism (see §3) |

---

## 2. EXCLUDE — wrong language entirely: this is mostly Faroese, not Norwegian (10 files)

**The single biggest finding in this triage.** The `04 Reading Books` folder contains 15 files, and
**10 of them are Faroese, not Norwegian** — a different North Germanic language spoken on the Faroe
Islands, written with its own letters (ð, the digraph pattern "**X og aðrar søgur**" = "X and other
stories," vs. Norwegian's "og andre historier/fortellinger"). Every one of the 10 was individually
rendered and read, not inferred from the filename:

| File | Confirmation |
|---|---|
| `Ábal og adrar sogur.pdf` | **Rendered**: "Sverre Patursson — Ábal og aðrar søgur," published by "Ung" |
| `Duruta og adrar sogur.pdf` | **Rendered**: "Hans A. Djurhuus — Duruta og aðrar søgur" — Djurhuus is a classic Faroese poet |
| `Eftir natungum.pdf` | **Rendered**: "Steinbjørn B. Jakobsen — Eftir nátungum" |
| `Frost rosan og adrar sogur.pdf` | **Rendered**: "FROST rósan — og aðrar søgur" |
| `Grannaklandur.pdf` | **Rendered**: "Jørgen M. Olsen — Grannaklandur," published by "Føroya Skúlabókagrunnur" ("Faroese School Book Foundation"), Tórshavn (the Faroese capital), 1977 |
| `Harry Potter og vitramannasteinurin.pdf` | **Rendered (cover)**: the Faroese translation of *Harry Potter and the Philosopher's Stone* — "vitramannasteinurin" is Faroese for "the philosopher's stone," not the Norwegian title. A full copyrighted contemporary novel besides. |
| `Heimakrakan og adrar sogur.pdf` | **Rendered**: "Heimakrákan og aðrar søgur," by Ása Ellefsen, Doris Hansen, Annika Højgaard, Sigrun Nolsøe (Nolsøe is a classic Faroese surname) |
| `Mia og Eyd.pdf` | **Rendered**: "Steinbjørn B. Jacobsen — Mia og Eyð," illustrated by Zacharias Heinesen |
| `Rakul og adrar sogur.pdf` | **Rendered**: "Regin í Líð — Rakul og aðrar søgur," published by "Ung" |
| `Vinir i foroyum.pdf` | **Rendered**: "Jytte Jordal — Vinir í Føroyum" ("Friends in the Faroe Islands") |

Faroese is not a language this project is currently working on, so this isn't a metalanguage
problem — it's the wrong target language outright. **Not excluded on a silent guess**: all 10 were
visually confirmed via rendered title/cover pages, and the pattern (author nationality, publisher,
the ð/ø letters, the "aðrar søgur" phrase) is consistent and unambiguous across all of them. Worth
flagging to whoever eventually scopes Faroese, if it's ever a candidate language for this project —
this is a small, ready-made, already-triaged starter stash (mostly short illustrated short-story
collections plus one translated novel).

**Genuinely Norwegian, kept** from the same folder (5 files, see §4): `Framtidslandet.pdf`,
`Jomfruen på Glassberget og andre eventyr.djvu`, `Kurt blir grusom.pdf`, `Norske folke-eventyr vol.
I.pdf`, `Norske folke-eventyr vol. II.pdf` — each individually rendered and confirmed Norwegian
(Bokmål spelling, Norwegian publishers, Norwegian authors Erlend Loe and Asbjørnsen/Moe).

---

## 3. EXCLUDE — out of scope, pure tourism (1 file)

- **`05 Society, Culture, Tourism/Norway (DK Eyewitness Travel Guides).pdf`** (306p, TEXT) —
  confirmed standard commercial travel guide, no language-pedagogical content. Same standing
  exclusion as every prior language's Frommer's/DK Eyewitness titles. **Kept, not excluded:**
  `Historical Dictionary of Norway.pdf` — confirmed academic reference (Historical Dictionaries of
  Europe series, no. 62, by Jan Sjåvik), not a tourism guide (see §4).
- The Russian-medium `Фьорды Норвегии Путеводитель.pdf` is also pure tourism content, but it's
  counted once, under §1 (wrong metalanguage), not counted twice.

---

## 4. Non-content assets (7 files, not extraction targets)

- **5 "Book List" JPGs** (`00 Book List/01.JPG`–`05.JPG`) — **read directly**: screenshots of the
  original collector's own folder listing (filenames with icons), not book content. One screenshot
  (`05.JPG`) shows a `Norwegian Folk Music` folder in the original inventory that isn't present in
  what actually made it onto this drive — noted for completeness, nothing to act on.
- **2 standalone stock photos** in `05 Society, Culture, Tourism/`: `Norwegian Shaman Wearing a
  Traditional Dress.JPG`, `Winter in Norway.JPG` — decorative images, no text content.
- **1 MP3** (`03 Dictionaries, Vocabulary, Phrasebooks/01 Berlitz Language 30 Norwegian Phrase
  Dictionary and Study Guide` audio companion) — counted only, not an extraction target, per this
  project's standing audio convention. Notably, the "Book List" screenshots show that most of the
  numbered course items originally had a matching "...Audio" companion file in the collector's own
  listing, but only this one MP3 actually made it onto the drive — the rest were apparently not
  copied into this harvest.

---

## 5. FLAGGED FOR YOUR RULING — Norwegian/German/Portuguese-medium-of-Norwegian (41 files)

Same open question this project has hit for every Scandinavian-family language so far (Swedish's
§5, closest sibling): this is real, substantial reference and course material, but its explanatory
apparatus is written in a language other than English — overwhelmingly **Norwegian itself** (the
NFU/SFI-style immigrant-course tradition — *Norsk for utlendinger*, "Norwegian for foreigners" —
explanatory text, instructions, and grammar notes in Norwegian, for learners already living in
Norway), plus a small side-group of **German-medium** and **Portuguese-medium** reference grammars
of Norwegian. Per the task's standing instruction, a non-English-medium *grammar* of the language is
never silently excluded or silently kept — it gets flagged here instead, same as every other
Norwegian/German/Portuguese-medium item in this section. **Not excluded, not kept — a decision is
needed.**

### 5a. Course series (20 files, all Norwegian-medium, confirmed by direct content read)

The VOX/Cappelen "Norsk og samfunnskunnskap for voksne innvandrere" ("Norwegian and social studies
for adult immigrants") course ladder and its companions — **every title below was confirmed
Norwegian-medium by rendering or `pdftotext`-reading actual lesson content, not just the cover**:

- **Norsk for utlendinger** 1 + Arbeidsbok, 2 + Arbeidsbok (4 files) — **rendered**, monolingual
  Norwegian lesson content ("Leksjon 2," exercises entirely in Norwegian)
- **Klar For Norge 1** (1 file) — **rendered**: "Norsk med samfunnskunnskap for voksne innvandrere,"
  by Aud Jahren, Helga Solstad & Eva Høgberg
- **Norsk på en-to-tre Tekstbok** (1 file) — **rendered**: near-monolingual Norwegian with occasional
  English glosses on exercise instructions only
- **Ny i Norge** — Tekstbok (1990), Arbeidsbok (1990), Arbeidsbok (2003), Øvinger i
  lytteforståelse (2003) (4 files, two editions present) — **rendered**: continuous Norwegian prose
- **Bo i Norge** (1 file) — **rendered**: continuous Norwegian prose (a personal letter as sample text)
- **På vei** — Arbeidsbok, Lærerens bok, Tekstbok (3 files; its Russian-targeted wordlist companion
  is excluded, §1) — **`pdftotext`-read**: "Norsk og samfunnskunnskap for voksne innvandrere,"
  Cappelen, confirmed Norwegian-medium throughout
- **Stein på stein** — Arbeidsbok, Tekstbok (B&W), Tekstbok (Color) (3 files; its Russian-targeted
  wordlist companion is excluded, §1) — same series, same confirmation; **the B&W (154p, no text
  layer) and Color (151p, TEXT) Tekstbok are not byte-identical and have different page counts —
  verify which scan is the better dispatch source before extraction**, same "duplicate-edition, not
  duplicate-file" caution as Swedish's Nya mål pairs
- **Her på berget** — Arbeidsbok, Tekstbok (2 files) — **`pdftotext`-read**: explicitly described in
  its own foreword as the next level up from På vei and Stein på stein, "nivå B2, Spor 3"
- **Sånn kan du si det: Norske uttrykksmåter i forskjellige situasjoner** ("That's How You Can Say
  It: Norwegian Expressions in Different Situations") — **rendered**: monolingual Norwegian
  expression/idiom tables with formal/informal register notes — **a flagship slang/idiom candidate**

### 5b. Standalone grammar & reference works (17 files)

**Norwegian-medium** (confirmed by direct content read in every case):
- **`12 Norsk Referansegrammatikk.pdf`** (629p) — **rendered and confirmed**: this is Jan Terje
  Faarlund, Svein Lie & Kjell Ivar Vannebo's *Norsk referansegrammatikk* (1997) — **the major
  academic reference grammar of the Norwegian language**, comparable in stature to German's Duden or
  Swedish's own major reference works. By far the single highest-value title in this flagged group if
  the ruling favors inclusion.
- **`15 Norsk morfologi.djvu`** — **rendered and confirmed Nynorsk-medium** (not just Bokmål): "Norsk
  morfologi tek sikte på å gje ei systematisk framstilling..." — a serious academic morphology
  reference, written in Nynorsk
- **`17 Nynorsk grammatikk.pdf`** and **`18 Nynorsk for studentar.pdf`** — **both confirmed Nynorsk-
  medium and Nynorsk-specific** (not just about Nynorsk, but written in it) — see the Bokmål/Nynorsk
  note below
- `03 Preposisjoner og Partikler i Norsk.pdf` (Åse-Berit og Rolf Strandskogen) — **`pdftotext`-read**,
  Norwegian-medium
- `06 Enkel norsk grammatikk.PDF` (Liv Astrid Greftegreff) — **rendered**, Norwegian-medium foreword
- `07 Oppslagsbok.pdf` (also by Liv Astrid Greftegreff — same author as `06`) — **rendered**,
  Norwegian-medium foreword
- `08 Noen emner i norsk for utlendinger.pdf` (TAPIR Forlag, NTNU's academic press) — **rendered**,
  Norwegian-medium ("Innhold kassetter" cassette contents page)
- `09 Ordets rette plass: Ordstilling i norsk.pdf` (John Megaard) — **`pdftotext`-read**, Norwegian-
  medium, explicitly "Øvelser i norsk som andrespråk" ("exercises in Norwegian as a second language")
- `10 Spørsmål om grammatikk.pdf` — **rendered**, Norwegian-medium foreword
- `11 Håndbok i grammatikk og språkbruk (Norsk for innvandrere).pdf` (Eva Høgberg) — **`pdftotext`-
  read**, explicitly "Norsk for innvandrere" ("Norwegian for immigrants")
- `14 Norsk språklydlære med øvelser.pdf` (Ingebjørg Skaug) — **rendered**, Norwegian-medium phonetics
  text with IPA notation
- `16 Å lykkes med norsk språk (språkhistorie, norrønt og målføre).pdf` — **rendered**, Norwegian-
  medium; covers language history, Old Norse ("norrønt"), and **dialects ("målføre")** specifically —
  see the dialect note below

**German-medium** (confirmed by direct content read):
- `04 Langenscheidts Praktische Grammatik Norwegisch.pdf` — **rendered**: German grammatical
  terminology throughout ("Pronomen," "Possessivpronomen," "Relativpronomen")
- `05 Praktische Grammatik der norwegischen Sprache.pdf` — **rendered**: same, German TOC
- `05 Übungsbuch zur norwegischen Grammatik.pdf` — **rendered**: German-Norwegian bilingual exercise
  book (translate German sentences into Norwegian and back), companion workbook to the item above

**Portuguese-medium** (confirmed by direct content read):
- `02 Gramatica Essencial de Noruegues.pdf` — **`pdftotext`-read**: "Norueguês: Uma Gramática
  Essencial," the Portuguese translation (Routledge, 1995) of the same Åse-Berit & Rolf Strandskogen
  grammar whose **English** Routledge edition (`02 Norwegian An Essential Grammar.pdf`, 104p) and
  **original Norwegian/English-translated Oris Forlag 1986 edition** (`02 Practical Norwegian
  Grammar.pdf`, 201p, translated by Barbara White) are both already kept in §4 below as in-scope —
  i.e. this is a non-English-medium *third copy* of a grammar this project already has in English.
  Flagged per the standing rule rather than silently dropped, but its practical value is lower than
  the other items in this section given the redundancy.

### 5c. Dictionary/phrasebook items (4 files, Norwegian-medium, confirmed by direct content read)

- **`06 Hva vi sier - og hva vi mener. Uttrykksmåter og arbeidspråk.pdf`** ("What We Say — and What
  We Mean: Expressions and Working Language") — **rendered and confirmed**: a monolingual Norwegian
  idiom/expression reference with paired "uttrykksmåte"/"forklaring" (expression/explanation) tables
  — **a flagship slang/idiom candidate**
- **`07 Katta i sekken og andre uttrykk. Bruk, bakgrunn, betydning.pdf`** ("The Cat in the Bag and
  Other Expressions: Use, Background, Meaning") — **rendered and confirmed**: a genuine monolingual
  Norwegian idiom dictionary, alphabetized by key word, each entry with definition, usage examples,
  and etymology (e.g. "alfa og omega," "gå amok") — same structure as Swedish's flagged *Svenska
  idiom*, and **a second flagship slang/idiom candidate**
- **`05 Telefonsamtaler på norsk.pdf`** ("Telephone Conversations in Norwegian") — **`pdftotext`-
  read**, Norwegian-medium specialized phrasebook
- **`13 Norske synonymer: blå ordbok.pdf`** ("Norwegian Synonyms: the Blue Dictionary") — **rendered
  and confirmed**: monolingual Norwegian synonym dictionary (Kunnskapsforlaget/Aschehoug/Gyldendal)

**Three separate flagship-category idiom/expression titles sit in this flagged group** (`Sånn kan du
si det` in §5a, plus the two above) — the largest number of independent slang/idiom candidates found
for any language in this project to date, all of them gated on the same medium ruling.

---

## 6. What's clearly in scope — no ruling needed (27 files)

**Reference grammars (English-medium, confirmed):**
`01 Norwegian Verbs and Essentials of Grammar.pdf` (89p, vision), `02 Norwegian An Essential
Grammar.pdf` (104p, vision, Routledge — **rendered**: "Norwegian: a practical grammar... translated
by Barbara White," Strandskogen), `02 Practical Norwegian Grammar.pdf` (201p, vision — **rendered and
confirmed**: the original 1986 Oris Forlag edition of the same Strandskogen work, spiral-bound,
translated by Barbara White — **these two are almost certainly the same underlying work in two
different-length English editions**, not two independent books; dispatch one as primary and treat
the other as a cross-check/fallback rather than extracting both as if independent), `13 The Phonology
of Norwegian.pdf` (383p, TEXT — the standard Gjert Kristoffersen/Oxford academic reference).

**Dictionaries (English-medium, confirmed):**
`01 Berlitz Language 30 Norwegian Phrase Dictionary and Study Guide.pdf` (29p, vision — **rendered**,
confirmed English-medium, companion to the one kept MP3), `08 Norwegian-English Dictionary.pdf`
(506p, vision — **rendered and confirmed**: this is Einar Haugen's *Norsk-Engelsk Ordbok*, a major
scholarly bilingual dictionary explicitly covering **both Bokmål and Nynorsk** with a historical and
grammatical introduction, Universitetsforlaget/University of Wisconsin Press — the flagship
dictionary in this stash), `09 Engelsk-Norsk Ordbok.pdf` (1337p, TEXT but poor-quality OCR —
bilingual English-Norwegian, largest dictionary in the stash).

**Courses (English-medium):**
`01 Teach Yourself Norwegian Conversation.pdf` (20p, vision), `01 Teach Yourself Speak Norwegian with
Confidence.pdf` (68p, vision), `02 Teach Yourself Norwegian.pdf` (129p, vision), `03 Colloquial
Norwegian (Digital).pdf` (294p, TEXT) and `(Scans).pdf` (147p, vision — **same title, different page
counts; not byte-identical — verify before picking one as the dispatch source, prefer the TEXT-layer
Digital copy**), `04 Norwegian in Three Months.pdf` (117p, vision), `05 Norwegian in 10 Minutes a
Day.pdf` (69p, vision), `06 Norwegian I Compact Reading Booklet.pdf` (12p, vision) + `07 Norwegian I
Comprehensive Reading Booklet.pdf` (20p, vision — companion pair), `08 Linguaphone Norsk Kurs.pdf`
(81p, vision) + `08 Linguaphone Norsk Kurs Handbook.pdf` (97p, vision — **rendered and confirmed
as a matched set**: the Kurs itself is monolingual Norwegian lesson/dialogue text, but its companion
Handbook is confirmed English-medium throughout, explicitly written for English-speaking American
learners ("the act of decoding graphic material...", discussion of US regional accents) — the pair
functions as a single English-medium course, same two-volume pattern as Assimil-style sets elsewhere
in this project), `09 Instant Norwegian.pdf` (44p, vision), `10 Norwegian a book on Self-instruction
in the Norwegian Bokmål.pdf` (147p, vision — **rendered and confirmed**: English-medium throughout,
explicitly written for teaching Norwegian in Los Angeles classrooms), `14 Så snakker vi Norsk:
Norwegian Level One.pdf` (97p, TEXT — **rendered and confirmed**: English-medium, its own
introduction states the authors "have been teaching Norwegian in Los Angeles, California").

**Native Norwegian-language reading material** (the text itself needs to be Norwegian — this is
source/usage material, not instructional apparatus, so the §5 medium question doesn't apply the same
way):
- **`Norske folke-eventyr vol. I.pdf`** and **`vol. II.pdf`** — **rendered and confirmed**:
  Asbjørnsen og Moe's classic 19th-century Norwegian folktale collection
- **`Jomfruen på Glassberget og andre eventyr.djvu`** — **rendered and confirmed**: "The Princess on
  the Glass Mountain and Other Fairy Tales," same Asbjørnsen/Moe tradition, Bokmål
- **`Kurt blir grusom.pdf`** — **rendered and confirmed**: Erlend Loe's contemporary "Kurt" series —
  a well-known living Norwegian novelist
- **`Framtidslandet.pdf`** — **rendered and confirmed**: a Norwegian-medium Advent-calendar
  storybook (IKO-Forlaget, 1999), confirmed via its own "Kjære leser!" ("Dear reader!") preface

**Culture/history reference (English-medium, academic):**
`Historical Dictionary of Norway.pdf` (305p, TEXT — Historical Dictionaries of Europe series, no.
62, by Jan Sjåvik, same series convention as this project's other Historical Dictionary entries).

---

## 7. Priority tiers (for the unambiguous English-medium + native-literature pool, 27 files — excludes §5's 41 flagged files)

**Tier 1 — reference grammars & academic linguistics:** `01 Norwegian Verbs and Essentials of
Grammar`, `02 Norwegian An Essential Grammar`, `02 Practical Norwegian Grammar` (treat as one
dispatch target per the note in §6 — same underlying work, two editions), `13 The Phonology of
Norwegian` (TEXT, cheapest and highest-value single title in this tier).

**Tier 2 — vocab/dictionary/idiom/slang:** `08 Norwegian-English Dictionary` (Haugen, flagship —
vision but worth it), `09 Engelsk-Norsk Ordbok` (TEXT, largest), `01 Berlitz Language 30 Norwegian
Phrase Dictionary and Study Guide`. **No English-medium slang/idiom-specific title exists in this
tier** — all three of this stash's flagship idiom/expression candidates (`Hva vi sier`, `Katta i
sekken`, `Sånn kan du si det`) are Norwegian-medium and sit in §5c/§5a instead, pending the medium
ruling. If that ruling favors inclusion, `Katta i sekken` (a genuine alphabetized idiom dictionary
with etymology) should lead this tier outright.

**Tier 3 — verbs & reading/writing skill-building:** `06 Norwegian I Compact Reading Booklet` + `07
Norwegian I Comprehensive Reading Booklet` (the only dedicated reading-skill-building pair in the
unambiguous pool; no standalone verb-conjugation reference was found outside the grammar titles in
Tier 1).

**Tier 4 — course series (lowest priority, highest cost):** `01`/`01` Teach Yourself Norwegian
Conversation + Speak Norwegian with Confidence, `02 Teach Yourself Norwegian`, `03 Colloquial
Norwegian`, `04 Norwegian in Three Months`, `05 Norwegian in 10 Minutes a Day`, `08 Linguaphone Norsk
Kurs` + Handbook, `09 Instant Norwegian`, `10 Norwegian a book on Self-instruction...`, `14 Så
snakker vi Norsk`. 11 files, almost entirely vision-only — the single biggest cost driver in the
unambiguous pool.

**Tier 5 — graded readers / native literature:** `Norske folke-eventyr` vol. I/II, `Jomfruen på
Glassberget og andre eventyr`, `Kurt blir grusom`, `Framtidslandet`.

**Unranked — culture/history reference:** `Historical Dictionary of Norway` (TEXT, cheap, academic;
doesn't fit the five-tier spec cleanly, same treatment as other languages' Historical Dictionary
entries in this project).

---

## 8. Bokmål vs. Nynorsk note

Every English-medium title in §6 (Tier 1–4) teaches **Bokmål**, the more common of Norway's two
official written standards — none of them is Nynorsk-specific. The **only** Nynorsk material
anywhere in this stash sits inside the flagged §5b group: `17 Nynorsk grammatikk.pdf` and `18
Nynorsk for studentar.pdf` are both explicitly Nynorsk-specific **and** Nynorsk-medium (not just
about Nynorsk — written in it), and `15 Norsk morfologi.djvu` (the academic morphology reference) is
also Nynorsk-medium despite covering the language generally. If the §5 Norwegian-medium ruling goes
against extraction, this project would end up with **zero** Nynorsk-standard material at all, only
Bokmål — worth flagging explicitly as a sub-decision if Nynorsk coverage matters for the Tepenian
handoff's purposes.

---

## 9. Extraction notes

- **78 of 101 net PDF/DJVU files need vision reading (77%)** — budget accordingly if extraction is
  authorized; in the same range as German (62% of real candidates) and Cantonese (73%).
- **The §5 Norwegian/German/Portuguese-medium ruling covers the largest single block of content in
  this stash — 41 of 101 files, over 40%** — larger in both count and proportion than Swedish's
  equivalent §5 (37 of 104, ~36%), and notably contains **three independent flagship slang/idiom
  candidates** rather than Swedish's one. Recommend resolving this before any Norwegian extraction
  wave is planned, since it changes both the wave structure and which title would lead Tier 2.
- **`02 Norwegian An Essential Grammar` and `02 Practical Norwegian Grammar` are almost certainly the
  same underlying Strandskogen work in two English editions** (1986 Oris original, 201p vs. a later,
  shorter Routledge edition, 104p) — plus a Portuguese third copy flagged in §5b. Dispatch one as
  primary, not both as independent titles.
- **`19 Stein på Stein Tekstbok (B&W)` vs `(Color)` and `03 Colloquial Norwegian (Digital)` vs
  `(Scans)` are same-title, different-scan pairs, not byte-identical** — spot-check both before
  committing to one as the dispatch source, same discipline as every prior language's duplicate-scan
  pairs.
- **The entire `04 Reading Books` folder needs re-auditing by whoever eventually scopes Faroese
  material for this project** — 10 of its 15 files (§2) are a ready-made, already-identified Faroese
  stash, not Norwegian.
- No frequency dictionary or frequency list was found anywhere in this single-location harvest for
  Norwegian.
- Scratch render files used for this triage (cover/content-page renders for every file marked
  "rendered" above) have been deleted per the project's disk-space instruction; nothing was written
  to the external drive.
