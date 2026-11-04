# Portuguese — Book Triage Catalog

**Triage complete, 2026-11-03.** First-ever triage for Portuguese in this project, per the
`TepenianLanguage` handoff: Portuguese was just added (2026-11-03) to the "second-era"
(Tepenian-stage) contributing-language roster specifically because of Brazil's documented
presence in the setting near the Palmer Peninsula — **Brazil, not Portugal**, is the reason
Portuguese is on the list. That handoff asked for **triage only, no extraction**.

**This triage has a different shape from every prior language in this project.** Malay/Indonesian
and Serbian/Croatian/Bosnian needed a split into separate *languages*. Portuguese is **one
language with two standardized varieties**, and the user's explicit ask for this pass was to go
beyond the collector's folder-level split and **flag content at a finer grain wherever the source
material itself calls out a Brazil-vs-Portugal contrast** — vocabulary, grammar points (*tu* vs
*você*, clitic placement, tense preferences), pronunciation, orthography (pre/post *Acordo
Ortográfico*), anything a book's own text marks as "Brazilian usage" vs "European/Portugal usage"
vs universal. §7 below is the heart of this pass and is explicitly preliminary/partial, not full
extraction.

**Location:** External drive `/media/kuroskalacs/Home-Theater/w-lang/Portuguese/` (confirmed
mounted) — **3.5GB, 167 files total**, already split by the collector into two subfolders:
`Brazilian Portuguese/` (73 files) and `European Portuguese/` (94 files). Confirmed absent from
`source_reference/languages/` and from both in-repo unsorted stashes (`lang transfer bay/`,
`xx--stash/LibGen Lang/`).

**Raw harvest data:** `.triage_raw.tsv` (167 rows: folder, file, size_mb, pages, text_layer, md5,
variety). `variety` is `Brazilian`/`European`/`Both`/`Unclear`/`N/A` (non-content) for every row —
assigned from the file's own confirmed title/content, not the folder it happened to sit in (several
files are tagged against their folder — see the misfile and "supplement" notes below).

**How titles and varieties were identified:** every title was confirmed from its own title or
copyright page — text-layer PDFs via `pdftotext` (all 76 TEXT-layer files had their first few pages
extracted and read), and **all 75 renderable vision-only files individually rendered**
(`pdftoppm` for PDFs, `ddjvu` + PIL for DJVU/DJV) and read visually. One file
(`00 Talking Brazilian A Brazilian Portuguese Pronunciation Workbook.pdf`, Brazilian folder) is
**corrupted** — its byte stream opens with ~500 bytes of `0xFF` padding instead of a `%PDF` header,
and `pdftoppm`, `mutool`, and `ghostscript` all fail to recover a readable page; it could not be
rendered or title-verified beyond its filename and needs re-acquisition before it can be used.
**Checked for duplicates by md5 across all 167 files, including across the two subfolders**: found
**3 exact cross-folder duplicates** (same book, byte-identical, filed once in each folder) — see §6.

---

## Headline numbers

| | Brazilian folder | European folder | Total |
|---|---|---|---|
| Files harvested | **73** | **94** | **167** |
| Non-content assets | 9 | 6 | 15 |
| Corrupted (unreadable) | 1 | 0 | 1 |
| Wrong-direction (Portuguese-medium dict *of English*, not *of* Portuguese) | 1 | 0 | 1 |
| Excluded — wrong metalanguage | 12 | 32 | 44 |
| Excluded — pure tourism (English-medium DK/Frommer's/Rough Guide/Hunter) | 5 | 10 | 15 |
| **Flagged for ruling — Portuguese-medium-of-itself / native-medium literature** | **19** | **27** | **46** |
| Clearly in scope, no ruling needed (English-medium or bilingual-with-English) | 26 | 19 | 45 |

| | |
|---|---|
| Text layer present (of 152 PDF/DJVU) | **76 (50%)** |
| Vision-read required (of 152 PDF/DJVU) | **76 (50%)** — 75 individually rendered and read; 1 corrupted, unrenderable |
| Non-PDF/DJVU files | 14 JPG (11 Book List screenshots + 3 album-art images) + 1 near-empty `.doc` |
| Exact duplicate files (by md5, including cross-folder) | **3** — see §6 |
| Packed archives not yet opened | none found |
| Bulk usage-corpus material | none found (see §5) |
| Frequency dictionary found | **yes — flagged, not moved** (see §6) |
| Flagship slang/colloquial title | **found — *Dirty Portuguese: Everyday Slang*, Brazilian-specific** (see §6) |
| Single most important title for this task's regional-contrast ask | ***Using Portuguese: A Guide to Contemporary Usage*** — explicitly "covers both the Brazilian and the European varieties... and differentiates clearly between them"; in scope, duplicated in both folders (see §6, §7) |

Check: 15 (non-content) + 1 (corrupted) + 1 (wrong-direction) + 44 (metalanguage) + 15 (tourism) +
46 (flagged) + 45 (in-scope) = 167 ✓

---

## 1. EXCLUDE — wrong metalanguage (44 files)

This project's extraction is English-medium. All 44 are confirmed by rendered title/content pages
or `pdftotext`, not inferred from filename.

**Russian-medium (31 files — by far the largest group, almost entirely in the European folder):**
course textbooks (`02 Manual de Portugues Curso Basico`, `03 Portugues para Principiantes`,
`04 Португальский язык для начинающих`, `10 Berlitz Basic Portuguese Course` ×2 formats,
`14 Португальский за три месяца`, `16 Langenscheidt Самоучитель`, `17 Portugues Curso Avancado`
×2 formats, `24 Продвинутый этап`, `25 Деловой португальский`, `26 Основы экономических
отношений`, `27 Практическое пособие по переводу`), grammar/verb references (`07 Справочник по
грамматике`, `08 Грамматика португальского языка`, `10 Справочник по глаголам`, `11 100
неправильных глаголов`), a reader (`04 Рассказы на португальском` — see §7 for its notable
`bras.`/`port.` register-tagging convention, excluded on metalanguage grounds only), phrasebooks/
dictionaries (`05 Berlitz разговорник и словарь`, `06 Русско-португальский разговорник` (DK),
`07 Шпаргалка для путешественника`, `08 Я еду в отпуск`, `09 Речевой этикет`, `12 Учебный
русско-португальский словарь`), tourism (`04 Исторический путеводитель`, `08 Пти Фюте`, `09/17/18`
*Золотой глобус* magazine issues), plus 2 in the Brazilian folder: `05 Бразилия (Золотой глобус)`
and `07 Living Language Visa to Brazil.pdf` — **this last one is a genuine misfile**: its rendered
cover reads "Виза в ПОРТУГАЛИЮ" (**Visa to Portugal**, not Brazil) despite the English filename;
tagged `European` in the TSV and flagged here as a collector-side mix-up, not just a metalanguage
exclusion.

**German-medium (4 files):** `06 Kauderwelsch Brasilianisch Wort für Wort` (Brazilian folder),
`15 Einführung in die portugiesische Sprachwissenschaft` (European folder — a serious academic
linguistics intro, Endruschat & Schmidt-Radefeldt, same "legitimate reference, wrong metalanguage"
pattern this project hits often), and two items physically filed in the Brazilian folder's own
`European Portuguese Supplement/` subfolder (see §3 note): `Kauderwelsch Portugiesisch Wort für
Wort` and `KulturSchock Portugal`.

**French-medium (4 files, all Brazilian folder):** `14 40 Leçons pour Parler Portugais`,
`15 Le Brésilien tout de suite`, `08 Vocabulaire portugais. Portugal et Brésil` (explicitly
contrastive — see §7 near-miss note), and `Contos e Crónicas de Expressão Portuguesa` (a
Portugal–Brasil–África anthology, Pocket/Langues pour tous, French-medium introductions).

**Spanish-medium (1 file):** `12 Larousse Verbos Portugueses — Guía Práctica` (Brazilian folder;
"82 modelos de conjugación del portugués de Brasil" — genuinely Brazilian-focused content, wrong
metalanguage only).

**Polish-medium (2 files):** `13 Jezyk portugalski dla początkujących` ("wersja brazylijska" on its
own cover — Brazilian folder) and `10 Rozmówki Polsko-Portugalskie` (European folder).

**Dutch-medium (1 file):** `03 Kosmos Mini Woordenboek Portugees-Nederlands` (European folder).

**Croatian-medium (1 file):** `Osnove Gramatike Portugalskoga Jezika` (Nikica Talan, Školska
knjiga, Zagreb) — filed in the Brazilian folder's `European Portuguese Supplement/` subfolder (see
§3).

---

## 2. EXCLUDE — pure tourism (15 files, English-medium)

Standard DK Eyewitness / Frommer's / Rough Guide / Hunter pattern, same standing exclusion as every
other language in this project.

**Brazilian folder (5):** `03 Brazil (DK Eyewitness Travel Guides)`, `04 Frommer's Brazil`,
`06 The Rough Guide to Rio de Janeiro`, `07 Rio de Janeiro (DK Eyewitness Top 10)`, `08 Rio & the
Best of Brazil (Hunter Travel Guides)`.

**European folder (10):** `05 Portugal (DK Eyewitness Travel Guides)`, `06 The Rough Guide to
Portugal`, `07 Frommer's Portugal`, `10 Lisbon (DK Eyewitness Travel Guides)`, `11 Lisbon (DK
Eyewitness Top 10)`, `12 Rough Guides Directions Lisbon`, `13 Algarve (DK Eyewitness Top 10)`,
`14 Rough Guides Directions Algarve`, `15 Madeira (DK Eyewitness Top 10)`, `16 Rough Guides
Directions Madeira`.

**Not excluded as tourism** (kept as culture/history background, per this project's standing
distinction between guidebooks and country-profile/historical works): `01 Brazil (Modern World
Nations)`, `02 A Brief History of Brazil`, `09 The Hidden History of Capoeira` (Brazilian);
`02 Portugal (Modern World Nations)`, `03 A History of Portugal and the Portuguese Empire` (Vol. 1
and 2, A.R. Disney, Cambridge), `01 CultureShock! Portugal` (Volker Poelzl) (European).

**Font-cipher gotcha, confirmed in-scope despite garbled `pdftotext` output:** `04 The Rough Guide
Portuguese Phrasebook.pdf` and `06 The Rough Guide to Portugal.pdf` both extract as encoded
gibberish via `pdftotext` (same embedded-font-remapping issue this project has hit in prior
languages) but render cleanly and confirm as genuine English-medium Rough Guide titles — note for
any future extraction pass.

---

## 3. One wrong-direction exclusion (1 file)

`11 The New (Portuguese) Dictionary of American Idioms.pdf` (Brazilian folder) — rendered/read via
`pdftotext`: "Novo Dicionário de Expressões Idiomáticas Americanas," Luiz Lugani Gomes — this is a
**Portuguese-medium dictionary of English/American idioms**, built to help Brazilian readers learn
English idioms, not a resource about Portuguese. Excluded as the wrong direction for this project's
pipeline, distinct from the metalanguage exclusions above.

---

## 4. Non-content assets (15 files) and the "European Portuguese Supplement" quirk

- **11 Book List screenshots** (`00 Book List/01.JPG`–`05.JPG` in the Brazilian folder, `01.JPG`–
  `06.JPG` in the European folder) — the collector's own folder-listing screenshots, read directly;
  confirm the drives' numbering schemes.
- **3 small JPG images** in the Brazilian folder's `05 Miscellaneous/` (`Tiê - A bailarina e o
  astronauta.JPG`, `Tiê - Passarinho.JPG`, `Tiê - Sweet jardim.JPG`) — appear to be album-cover art
  for Tiê, a Brazilian singer; no accompanying audio files exist anywhere in this harvest. Not
  extraction targets.
- **1 near-empty `.doc`**: `11 Portuguese (Brazilian) III Booklet.doc` — checked via file metadata:
  1 page, 2 words, 14 characters. Same "placeholder file" pattern seen in other languages' triages
  in this project.
- **The Brazilian folder contains its own `05 Miscellaneous/European Portuguese Supplement/`
  subfolder (4 files)** — the collector deliberately filed four **European**-variety items inside
  the Brazilian folder as a cross-reference supplement: `Kauderwelsch Portugiesisch Wort für Wort`
  (German, excluded), `KulturSchock Portugal` (German, excluded), `Osnove Gramatike Portugalskoga
  Jezika` (Croatian, excluded), and `Teach Yourself Portuguese.pdf` (English-medium, **in scope,
  tagged `European` in the TSV despite its physical location**). This is a deliberate collector
  choice, not a misfile — flagged here so any future wave dispatch doesn't accidentally treat these
  four as Brazilian just because of their folder path. (Compare the genuine misfile at §1: `07
  Living Language Visa to Brazil.pdf`, which really is just wrongly titled/placed.)

---

## 5. Packed archives and bulk usage-corpus material

**Neither found.** No `.rar`/`.zip` archives anywhere in this harvest. No magazine-run or
newspaper-archive-scale usage corpus either — the closest thing to an authentic-text usage source
is the three Stephenie Meyer *Twilight*-series Brazilian-Portuguese translations (`Crepúsculo`,
`Lua Nova`, `Eclipse` — Editora Intrínseca, Rio de Janeiro), which are Portuguese-medium popular YA
fiction and are flagged for ruling in §6 rather than treated as a corpus (3 novels is not "bulk").

---

## 6. What's clearly in scope — category overview (45 files, no ruling needed)

### 6a. Grammars & linguistic reference

- **`11`/`13 Using Portuguese: A Guide to Contemporary Usage`** (duplicated byte-identically in both
  folders, md5 `4d480f6691a7110693925e7ad264f973`) — **the single most important title in this
  harvest for this task's purpose.** Its own back-cover text states: *"It covers both the Brazilian
  and the European varieties of the language, and differentiates clearly between them."* Tagged
  `Both`. See §7.
- **`A Frequency Dictionary of Portuguese`** (duplicated byte-identically in both folders, md5
  `8950cc4db2a2f2743cfa39f3223a661d`) — **flagged per the project's frequency-dictionary rule, not
  moved.** Built on "a 20-million-word corpus evenly divided between spoken, fiction and non-fiction
  texts from both Portugal and Brazil." Tagged `Both`.
- **`09 501 Portuguese Verbs Fully Conjugated in All the Tenses`** (Nitti & Ferreira, Barron's,
  European folder) — cover art shows the Portugal flag *and* the Brazil flag side by side; tagged
  `Both`, a plausible source of explicit dual-norm conjugation contrasts if extracted.
  `14 Portuguese: A Linguistic Introduction` (European folder) — "includes a chapter on Portuguese
  in Brazil, where approximately 80% of Portuguese speakers live" and explicitly covers "dialect
  variation and language planning"; tagged `Both`.
- **`02 Essential Portuguese Grammar`** (Dover, Alexander da R. Prista) and `05 Portuguese: An
  Essential Grammar` (2nd ed., European folder, Routledge) — both English-medium, general
  references; variety not conclusively determined from the title page alone, tagged by folder
  default but flagged here as uncertain (Prista's especially — classic, pre-dates the modern
  Brazilian/European-split emphasis).
- `04 Portuguese Grammar: A Complete, Concise and Practical Reference` (Sonia Celegatti Althoff,
  Brazilian-authored) and `06 Modern Brazilian Portuguese Grammar: A Practical Guide` and `08 A
  Grammar of Spoken Brazilian Portuguese` (Earl W. Thomas, Vanderbilt UP, 1974) — all confirmed
  Brazilian.
- `01 Teach Yourself Portuguese Grammar` (Sue Tyson-Ward) — exists as 3 files (a DJVU duplicated
  byte-identically across both folders, md5 `456656ad96267598cd9f8ab4f95f88d9`, plus a separate TEXT
  PDF scan in the European folder) — general title, variety tagged `Unclear` pending a closer read;
  the same author also wrote the confirmed-Brazilian `04 Brazilian Portuguese: A Complete Course for
  Beginners`, so this grammar's own variety commitment is worth settling before dispatch.

### 6b. Courses (English-medium, no ruling needed)

**Brazilian:** `02 Colloquial Portuguese of Brazil` + `17 Colloquial Portuguese of Brazil 2`
(Routledge, two-volume series), `03 Portuguese For Dummies`, `04 Brazilian Portuguese: A Complete
Course for Beginners` (Teach Yourself, Sue Tyson-Ward), `09`/`10 Portuguese (Brazilian) I/II Reading
Booklet` (DLI-style), `12 Ultimate Portuguese Beginner-Intermediate` (Living Language),
`16 Pois não: Brazilian Portuguese Course for Spanish Speakers` (University of Texas Press —
confirmed **trilingual English/Portuguese/Spanish** per its own Library of Congress data, not
Spanish-only; kept in scope), `19 Para a Frente! An Intermediate Course in Portuguese` (Larry D.
King & Margarita Suñer), `20 Crônicas Brasileiras: Nova Fase` (University of Florida Center for
Latin American Studies — English editorial apparatus around Portuguese readings).

**European:** `30`/`31 Portugal: Língua e Cultura` (Textbook + Writing/Lab Manual, Tom Lathrop &
Eduardo M. Dias, LinguaText — American-authored, English-medium), `34 Colloquial Portuguese: The
Complete Course for Beginners` (João Sampaio & Barbara McIntyre) and `13 Colloquial Portuguese
(1974)` (Maria Emília de Alvelos Naar) — **two genuinely different editions of the Routledge
European-Portuguese Colloquial title, not duplicates**, `41 Teach Yourself Instant Portuguese`
(Elisabeth Smith), and `European Portuguese Supplement/Teach Yourself Portuguese.pdf` (the general,
older Teach Yourself title, physically filed in the Brazilian folder — see §4).

### 6c. Vocabulary, dictionaries & phrasebooks

**Brazilian:** `02 Portuguese Phrases for Dummies`, `03 Say It Right in Brazilian Portuguese`,
`04 In-Flight Portuguese` (Living Language).

**European:** `02 Portuguese-English Visual Bilingual Dictionary` (DK), `04 The Rough Guide
Portuguese Phrasebook` (font-cipher gotcha, see §2).

### 6d. Slang / colloquial — the flagship category for this project's purposes

**`05 Dirty Portuguese: Everyday Slang`** (Brazilian folder, Ulysses Press "Dirty [Language]"
series) — confirmed via its own text: a *gíria* crib sheet explicitly for "street cred in Brazil,"
with casual/explicit vocabulary and usage warnings. **This is the clear flagship slang title for
Portuguese, and it is Brazilian-specific**, not pan-Portuguese — a useful data point in itself, that
the one dedicated slang resource in this entire 167-file harvest commits to the Brazilian variety.
**No equivalent dedicated European-Portuguese slang/calão dictionary was found anywhere in this
harvest** — a real, flaggable gap for the European side specifically (compare the thin partial
evidence in §7c instead).

### 6e. Culture, society & history (background, not tourism)

`01 Brazil (Modern World Nations)`, `02 A Brief History of Brazil`, `09 The Hidden History of
Capoeira` (Brazilian); `01 CultureShock! Portugal`, `02 Portugal (Modern World Nations)`, `03 A
History of Portugal and the Portuguese Empire` Vol. 1 & 2 (European).

### 6f. Bilingual/parallel-text reading material

`01 Onde a Terra Acaba: Colectânea de Contos Portugueses / From the Edge: Portuguese Short Stories`
(European folder) — genuine Portuguese/English parallel text, ULICES/CEAUL, Lisbon.

---

## 7. Regional variation observed in this stash (preliminary, partial — the heart of this pass)

This is a first-pass harvest of what the stash's own title pages, front matter, and spot-checked
content already surface — **not** full extraction. It is organized into the three buckets the user
asked for. Citations point to the specific book each observation came from.

### 7a. Features the source material itself marks as pan-Portuguese / universal

- **`A Frequency Dictionary of Portuguese`** builds its 5,000-word frequency list from "a
  20-million-word corpus evenly divided between spoken, fiction and non-fiction texts **from both
  Portugal and Brazil**" — the whole premise of the book is a word-frequency core common to both
  national standards, by construction. (Both folders, md5-identical.)
- **`09 501 Portuguese Verbs Fully Conjugated in All the Tenses`** presents its conjugation tables
  under a single cover bearing both the Portugal and Brazil flags, implying the conjugation
  paradigms themselves are treated as shared — any verb-form *divergence* it documents (if any)
  would need to be checked at extraction time, not assumed from the cover alone.

### 7b. Features marked European/Portugal-specific

- **`O Essencial sobre a História do Português`** (Esperança Cardeira, Lisbon: Caminho) frames the
  entire history of the language from "Português Antigo" through "Português Clássico e Moderno" as
  a continuous European national-language narrative — the standard European-Portuguese framing of
  linguistic history, in contrast to Brazilian-authored grammars' framing below. Portuguese-medium —
  flagged for ruling in §6 context, not yet extracted.
- The sheer existence of **separate, dedicated European-Portuguese editions** of major course
  series (`Colloquial Portuguese` vs `Colloquial Portuguese of Brazil`; the Lisbon-produced
  `Português XXI`, `Português sem Fronteiras`, `Navegar em Português`, `Aprender Português`,
  `Gramática Activa` series, all Portuguese-medium, all Lisboa/Porto/Coimbra-published) is itself
  structural evidence that European Portuguese is treated by publishers as needing its own
  self-contained teaching apparatus, distinct from Brazilian materials — worth confirming with real
  content-level examples once any of these are ruled in and extracted.

### 7c. Features marked Brazilian-specific

- **`Dirty Portuguese: Everyday Slang`** is explicitly and exclusively framed around Brazilian
  *gíria* — "street cred in Brazil," casual terms the book itself warns are inappropriate outside
  informal settings "with your friends." This is the strongest single piece of register-specific
  evidence in the whole harvest (see §6d).
- **`07 Moderna Gramática Portuguesa`** (Evanildo Bechara, 37th ed.) identifies its own author on
  the title page as "Representante brasileiro do novo Acordo Ortográfico" (the Brazilian
  representative to the new Orthographic Agreement) — ties the 1990 Acordo Ortográfico reform
  explicitly to Brazilian academic representation. Portuguese-medium, flagged for ruling.
- **`12 Guia Prático da Nova Ortografia do Português`** (Douglas Tufano) states its own purpose on
  the cover as "Saiba o que mudou **na ortografia brasileira**" (learn what changed in **Brazilian**
  spelling) — frames the same Acordo Ortográfico reform from the Brazilian side specifically, a
  useful counterpart to the European framing in 7b above. Portuguese-medium, flagged for ruling.
- **`09 Língua Viva`** and **`10 Nossa Língua — Falando e Escrevendo Corretamente`** are both
  explicitly framed around "a linguagem do brasileiro" (the language of the Brazilian) — contemporary
  usage-advice columns/workbooks addressed specifically to Brazilian readers' own usage questions,
  not a general Portuguese-language audience. Portuguese-medium, flagged for ruling.

### 7d. Near-miss observations (excluded on metalanguage grounds, but worth recording)

- **`08 Vocabulaire portugais. Portugal et Brésil`** (French-medium, Brazilian folder) is explicitly
  structured as a **Portugal-vs-Brésil contrastive vocabulary** by its own title — exactly the kind
  of source this task is looking for, but inaccessible to this project's English-medium pipeline.
- **`04 Рассказы на португальском`** (Russian-medium reader, European folder) uses a visible
  abbreviation apparatus distinguishing **`bras.` (brasileiro)** from **`port.` (português)**
  throughout its vocabulary glosses, alongside register tags like `cal.` (calão/slang), `fam.`
  (familiar), `pop.` (popular) and `gír.` (gíria) — a working example of a source explicitly
  tagging words as Brazilian- vs Portugal-specific at the lexical-entry level, excluded here only
  for its Russian metalanguage.
- **`12 Guia Prático de Verbos com Preposições`** (Portuguese-medium, European folder, Lidel) lists
  `cal. = calão` (slang) in its own abbreviation key alongside `fam.`, `pop.`, `prov.` — register
  tagging is present even in this flagged-for-ruling title, worth checking at extraction time for
  whether it also tags regional (Brazil/Portugal) usage, not just register.

**Open question for the user:** the strongest actually-in-scope resource for a rigorous Brazil-vs-
Portugal contrast is `Using Portuguese: A Guide to Contemporary Usage` (§6a) — if this triage's
flagged-for-ruling group (§6a/§7b/§7c above, mostly Portuguese-medium-of-itself titles) is approved
for extraction, several of the strongest regional-contrast sources in this harvest are in that group
specifically because of the "non-English-medium-of-itself is flagged, not auto-excluded" rule.

---

## 8. Flagged for your ruling — Portuguese-medium-of-itself / native-medium literature (46 files)

Per the task's explicit instruction, a Portuguese-medium reference work of Portuguese itself (or
native-medium Portuguese-language literature) is never silently excluded or silently kept. **Not
excluded, not kept — a decision is needed**, the same recurring open question this project has hit
for nearly every language triaged so far.

### 8a. Brazilian folder (19 files)

**Course series (Portuguese-medium, 10 files):** `01 Falar Ler Escrever Português` (Caderno de
Exercícios + Livro do Aluno, EPU), `05 Português Básico para Estrangeiros` (+ Manual do Professor,
Rejane de Oliveira Slade), `06`/`18 Novo Avenida Brasil 1 & 2` (EPU), `07 Bem-Vindo!` (Caderno de
Exercícios + Livro do Aluno, each in both DJVU and PDF format — 4 files, SBS Editora, bilingual
PT/EN title but Portuguese-medium lesson content per spot-check).

**Grammar/usage (Portuguese-medium, 5 files):** `03 Minimanual Compacto de Gramática`, `07 Moderna
Gramática Portuguesa` (Bechara — see §7c), `09 Língua Viva`, `10 Nossa Língua` (see §7c),
`13 Verbos: Guia Prático de Conjugação e Concordância`.

**Orthography (Portuguese-medium, 1 file):** `12 Guia Prático da Nova Ortografia do Português`
(Tufano — see §7c).

**Native-medium popular fiction (3 files):** Stephenie Meyer's *Crepúsculo*, *Lua Nova*, *Eclipse*
(Brazilian-Portuguese translations, Editora Intrínseca, Rio de Janeiro) — contemporary informal
register, potentially useful as a small usage sample if ever ruled in.

### 8b. European folder (27 files)

**Course series (Portuguese-medium, 14 files):** `06 Aprender Português 1`, `07`/`19`/`20 Português
XXI 1/2/3` (Caderno de Exercícios + Livro do Aluno for levels 1 and 2 — 4 files; level 3's Caderno
is **only "Unidade 1," a partial single-unit excerpt, not the full exercise book** — flag this
before any dispatch — + Livro do Aluno, 2 more files = 6 total for XXI across all levels),
`08`/`21`/`22 Português sem Fronteiras 1/2/3`, `09`/`23 Navegar em Português 1 & 2` (Caderno +
Livro do Aluno each, 4 files).

**Grammar/usage (Portuguese-medium, 6 files):** `02`/`03 Gramática Activa 1 & 2` (CIAL/Lidel),
`04 Qual é a Dúvida? Explicações e Exercícios de Gramática`, `06 Gramática de Português para
Estrangeiros` (Lígia Arruda, Porto Editora), `12 Guia Prático de Verbos com Preposições` (see §7d
for its slang-tagging convention), `16 O Essencial sobre a História do Português` (see §7b).

**Native-medium literature (7 files):** `02 Antologia da Ficção Portuguesa Contemporânea` and
`03 Antologia do Conto Português Contemporâneo` (Instituto de Cultura Portuguesa anthologies, no
foreign-language apparatus), `06 Luís de Camões — Os Lusíadas` (Instituto Camões critical edition of
the national epic), `07 Sophia de Mello Breyner Andresen — Contos Exemplares`, `09 Alice Vieira —
Os Olhos de Ana Marta` and `10 O Primeiro Livro do Diário de Sofia` (native-medium YA fiction),
`12 Hans Christian Andersen — A Sereiazinha` (Portuguese translation of "The Little Mermaid").

---

## 9. Priority tiers

### Tier 1 — reference grammars & academic linguistics

`Using Portuguese: A Guide to Contemporary Usage` (Both — the flagship regional-contrast title),
`Portuguese: A Linguistic Introduction` (Both), `09 A Grammar of Spoken Brazilian Portuguese`
(Thomas), `06 Modern Brazilian Portuguese Grammar`, `04 Portuguese Grammar: A Complete, Concise and
Practical Reference` (Althoff), `02 Essential Portuguese Grammar` (Dover/Prista), `05 Portuguese: An
Essential Grammar` (European), `01 Teach Yourself Portuguese Grammar` (variety TBD). If ruled in:
`16 O Essencial sobre a História do Português`, `07 Moderna Gramática Portuguesa` (Bechara),
`06 Gramática de Português para Estrangeiros` (Arruda), `02`/`03 Gramática Activa 1 & 2`.

### Tier 2 — vocab/dictionary/idiom/slang (flagship category)

**`05 Dirty Portuguese: Everyday Slang`** (Brazilian — the clear flagship, see §6d), `A Frequency
Dictionary of Portuguese` (Both, also flagged separately per the project's frequency-list rule),
`09 501 Portuguese Verbs` (Both), `02 Portuguese-English Visual Bilingual Dictionary`,
`02 Portuguese Phrases for Dummies`, `03 Say It Right in Brazilian Portuguese`, `04 In-Flight
Portuguese`, `04 The Rough Guide Portuguese Phrasebook`. If ruled in: `12 Guia Prático de Verbos com
Preposições` (notable slang-register tagging, §7d). **No dedicated European-Portuguese slang/calão
title exists anywhere in this harvest** — a real gap on the European side specifically.

### Tier 3 — verbs & reading/writing skills

`13 Verbos: Guia Prático de Conjugação e Concordância` (if ruled in). Otherwise thin outside the
Tier 1 grammars and Tier 2 verb-conjugation titles.

### Tier 4 — course series (lowest priority, highest cost)

`04 Brazilian Portuguese: A Complete Course for Beginners`, `02`/`17 Colloquial Portuguese of
Brazil` 1 & 2, `03 Portuguese For Dummies`, `09`/`10 Portuguese (Brazilian) I/II Reading Booklet`,
`12 Ultimate Portuguese Beginner-Intermediate`, `16 Pois não`, `19 Para a Frente!`,
`20 Crônicas Brasileiras` (Brazilian); `34 Colloquial Portuguese: The Complete Course for
Beginners`, `13 Colloquial Portuguese (1974)`, `30`/`31 Portugal: Língua e Cultura`, `41 Teach
Yourself Instant Portuguese`, `European Portuguese Supplement/Teach Yourself Portuguese` (European).
If ruled in, this tier would roughly double in size with the Portuguese-medium course series listed
in §8.

### Tier 5 — graded readers

`01 Onde a Terra Acaba` (bilingual parallel text, European — the only genuinely in-scope reader
without a ruling question). If ruled in: the native-medium literature group in §8b (7 titles).

### Not fitting the 5-tier scheme — culture/history/society

`01 Brazil (Modern World Nations)`, `02 A Brief History of Brazil`, `09 The Hidden History of
Capoeira` (Brazilian); `01 CultureShock! Portugal`, `02 Portugal (Modern World Nations)`,
`03 A History of Portugal and the Portuguese Empire` Vol. 1 & 2 (European).

---

## 10. Extraction notes

- **§7 is the deliverable this task was really about** — it is explicitly a first-pass, preliminary
  harvest of regional-contrast evidence already visible at the triage/category-overview level, not
  full extraction. The single most valuable asset for deepening it is `Using Portuguese: A Guide to
  Contemporary Usage`, which is already in scope and needs no ruling.
- **3 exact cross-folder md5 duplicates** confirm the collector's split is mostly clean but not
  perfect: `A Frequency Dictionary of Portuguese`, `Using Portuguese: A Guide to Contemporary
  Usage`, and `Teach Yourself Portuguese Grammar` (DJVU) all exist as byte-identical copies in both
  folders — correctly tagged `Both`/`Unclear` rather than arbitrarily assigned to one variety.
- **One genuine misfile found**: `07 Living Language Visa to Brazil.pdf` (Brazilian folder) is
  actually "Visa to Portugal" per its own Russian-medium cover — tagged `European` in the TSV despite
  its filename and folder.
- **One deliberate non-misfile cross-reference found**: the Brazilian folder's own `European
  Portuguese Supplement/` subfolder (4 files) — not an error, but all 4 are tagged by their actual
  content variety, not their physical folder.
- **46 files (46 of 167 = 28%) are flagged for ruling** — a Portuguese-medium-of-itself course,
  grammar, or native-medium literary text. This is a much larger flagged group than any prior
  language's single-digit rulings, because Portuguese has a far richer stash of self-contained
  Portuguese-medium pedagogical series (`Português XXI`, `Português sem Fronteiras`, `Navegar em
  Português`, `Bem-Vindo!`, `Novo Avenida Brasil`, `Gramática Activa`, etc.) than any language
  triaged in this project so far. Several of the strongest §7 regional-contrast candidates sit in
  this flagged group specifically.
- **`20 Português XXI 3 — Caderno de Exercícios — Unidade 1.pdf` is a partial file** — only one unit
  of the exercise book, not the complete Caderno de Exercícios 3. Flag before any dispatch.
- **One file is corrupted and unreadable**: `00 Talking Brazilian A Brazilian Portuguese
  Pronunciation Workbook.pdf` — opens with ~500 bytes of `0xFF` padding instead of a valid `%PDF`
  header; `pdftoppm`, `mutool`, and `ghostscript` all failed to recover it. Needs re-acquisition.
- **Font-cipher gotcha** (same pattern seen in prior languages' CJK and European triages): `04 The
  Rough Guide Portuguese Phrasebook.pdf` and `06 The Rough Guide to Portugal.pdf` both have garbled
  `pdftotext` output from remapped embedded fonts but render and read cleanly — confirmed
  English-medium by rendering, not by `pdftotext`.
- **A Frequency Dictionary of Portuguese is flagged per the project's standing frequency-dictionary
  rule** — reported here, not moved; the separate frequency-dictionaries collection at
  `/home/kuroskalacs/Documents/Doll-Fi/media/y-files/frequency_dictionaries/` should be checked for
  whether it already has a copy.
- **No packed archives and no bulk usage-corpus material exist anywhere in this harvest** — the
  three Twilight-series Portuguese translations are the closest thing to an authentic-text sample,
  and at 3 novels don't rise to "bulk."
- **No wrong-target-language contamination was found** — unlike Malay/Indonesian's Javanese mix-up
  or Kazakh's Kyrgyz/Karakalpak check, every file confirmed Portuguese-subject-matter is genuinely
  about Portuguese (Brazilian or European), with no third Lusophone variety (Angolan, Mozambican,
  etc.) material misfiled in — though `Contos e Crónicas de Expressão Portuguesa` (excluded,
  French-medium) does anthologize Angolan and other African Lusophone writers alongside Portuguese
  and Brazilian ones, worth knowing about if African Portuguese ever becomes a priority.
- Scratch render files (title/content-page renders for all 75 renderable vision-only files, the
  `pdftotext` title-page extractions for all 76 TEXT-layer files, the md5-duplicate analysis, and
  the corrupted-file repair attempts) have been deleted from the scratchpad per the project's
  disk-space instruction; nothing was written to the external drive.
