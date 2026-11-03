# German — Book Triage Catalog

**Triage complete, 2026-11-01.** First-ever triage/entry for German in this project — no prior
`datasets/German/` folder existed before this pass, and no extraction has been scheduled yet. This
catalog covers investigation and inventory only; **no files have been dispatched for extraction.**

**Location:** `/media/kuroskalacs/Home-Theater/w-lang/German/` (external drive — confirm mounted)
**Raw harvest data:** `.triage_raw.tsv` (164 rows: folder, file, size_mb, pages, text_layer)

## Headline numbers

| | |
|---|---|
| Files harvested | **164** |
| **Excluded — wrong metalanguage / wrong audience** | **6** (4 harvested + 2 pre-filtered) |
| **Non-content assets** (cover scans, CD-sleeve photos, a trivial `.txt`) | **25** |
| **Real candidates for Phase 1** | **≈133** (51 TEXT + 82 vision) |
| Total pages (non-excluded) | **≈26,300** |
| Total size (non-excluded) | **≈7.7 GB** |
| Text layer present | 53 (1 of the raw 54 is the excluded Russian-medium book) |
| Vision-read required | 107 (3 of the raw 110 are excluded Russian glossaries; 25 more are non-content assets) |
| **Not scheduled** (`.rar` archives) | 3 |
| **Bulk usage-corpus, not individually catalogued** | ~50 issues (`Der Weg` magazine, 1999–2010) |

This is the most vision-read-dominated stash in the project to date on a real-content basis: of the
133 real candidates, **82 (62%)** need vision reading. For scale, that's worse than Spanish (64/144,
44%) and in the same range as Cantonese (73% non-text-layer).

---

## 1. EXCLUDE — wrong metalanguage / wrong audience (6 files)

**Confirmed Russian-medium or Russian-target, by a combined Cyrillic + Latin-script-marker sweep:**

| File | Pages | Reason |
|---|---|---|
| `02.Intermediate-Advanced Courses/Немецкий язык. Уровень совершенства.pdf` | 525 | Cyrillic title — "German language, level of perfection," a Russian-medium German course |
| `Deutch ohne Probleme (Russian)/deutch ohne probleme 1.djvu` | — | folder name flags Russian medium; confirmed via directory listing (2-file folder) |
| `Deutch ohne Probleme (Russian)/deutch ohne probleme 2.djvu` | — | same folder, same reason |
| `01.Courses for Beginners/Moment Mal/Glossar 1 Russisch.pdf` | 50 | German→**Russian** glossary — wrong target audience for this project |
| `01.Courses for Beginners/Moment Mal/Glossar 2 Russisch.pdf` | 50 | same reason, companion volume |
| `01.Courses for Beginners/Themen Aktuell 2/Glossar Deutsch-Russisch.pdf` | 66 | same reason |

**Kept — confirmed German-English or German-only, not wrong-audience:**
`Schritte_International_1_Glossar_English.pdf`, `Moment Mal/Glossar 3 Englisch.pdf`,
`Themen Aktuell 1 - Glossar.pdf` (multilingual, English included). These three looked at risk of the
same exclusion on first pass since they sit in the same series folders as the Russian glossaries —
spot-opened and confirmed fine.

**Methodological note:** this stash repeats the Spanish-stash lesson almost exactly — the wrong-
audience glossaries hide inside course-series subfolders (Moment Mal, Themen Aktuell) alongside
perfectly good English-facing material from the same series, not off in their own clearly-marked
folder (except for the one `(Russian)`-tagged folder). Check every glossary file in a multi-glossary
folder individually; don't assume a folder is "clean" or "contaminated" as a whole.

---

## 2. Not extraction targets — non-content assets (25 files)

These carry no extractable text and shouldn't be scheduled as vision-read targets even though most
show `NONE` in the text-layer column:

- **18 `.jpg` files** — physical book-cover photos and CD-sleeve scans, scattered through the
  Schritte International, Lagune, and Em neu subfolders (e.g. `1.jpg`, `2.jpg`, `Vorderseite.jpg`,
  `Ruckseite.jpg`, `CDoblozhka1.jpg`). Artifacts of how each course was scanned, not content.
- **6 tiny 2-page `-cover.pdf` files** — `Lagune-1-Arbeitsbuch-cover.pdf` and its five siblings.
  Cover scans saved as their own PDF rather than a JPG, same non-content status.
- **1 `CD.txt`** (`Themen Aktuell 3/CD.txt`) — verified: a UTF-16 CD-label string, not grammar
  content.

Also not relevant to Phase 1 text extraction: `Graded Readers for Learners/Der Tote im See Audio.flac`
(an audiobook companion file, not text).

---

## 3. Not scheduled — packed archives (3 files)

Same standing convention as every prior language's `.rar`/`.zip` handling — decide separately whether
to unpack, don't count toward this triage's totals:

- `04.Linguaphone Deutscher Kursus.rar`
- `39.Mitlesen Mitteilen Literarische Texte...rar`
- `03.Grammars+Workbooks/Fit fuers Goethe Zertifikat A2.rar`

---

## 4. Bulk usage-corpus material, not individually catalogued

`05.Graded Readers and Newspapers for Learners/` contains a **"Der Weg" magazine archive spanning
roughly 50 issues, 1999–2010** — a periodical for German learners. Following the precedent set by
Russian's magazine collections (and the project's general usage-corpus-vs-reference-corpus
distinction): this is **searched material, not an individual Phase 1 extraction target**. It was
excluded from the 164-file harvest for that reason and should be catalogued separately (as a corpus
to search against, not read cover-to-cover) if and when German usage-corpus work begins. The five
graded-reader *titles* also in that folder (`Brigitta`, `Der gestiefelte Kater`, `Tor ohne Grenzen`,
etc.) **are** individually catalogued below — they're discrete learner-reader books, not a periodical
run.

---

## 5. What this stash offers — category overview

German has **zero existing presence** in this project before this triage, so there's no "gap versus
an existing corpus" to measure against (unlike Spanish's new-stash triage). Instead, here's what the
~133 real candidates break down into by category:

- **Reference grammars** — root-level numbered files (00, 05, 12, 14, 17, 35–38) plus the 14-file
  `03.Grammars+Workbooks/` folder (7 of 14 with a text layer: PONS *Die grosse Grammatik Deutsch*,
  Collins *Easy Learning German Grammar*, Schaum's *Outline of German Grammar*, *A Practice Grammar
  of German*, Langenscheidt *Kurzgrammatik*, *Übungsgrammatik für Fortgeschrittene*, *Grammatik sehen
  Lösungsschlüssel*). **Flagship, vision-required:** *Hammer's German Grammar and Usage* (597 p) — the
  standard comprehensive reference grammar for German, same tier as Spanish's *Big Red Book* or
  Korean's major reference grammars.
- **Academic linguistics** — three similarly-titled but apparently **distinct** standard textbooks
  worth double-checking are not duplicates before extraction: *German: A Linguistic Introduction*
  (333 p), *The German Language: A Linguistic Introduction* (274 p), *The German Language Today: A
  Linguistic Introduction* (258 p). Also *The Structure of German* (347 p), *A History of German
  Literature* (698 p), *A History of the German Language Through Texts* (414 p), *The Cambridge
  Companion to Modern German Culture* (390 p), *A Companion to 20th Century German Literature*
  (335 p), *Geschichte der deutschen Sprache* (240 p). All text-layer except the two literature
  companions' bibliographic depth hasn't been spot-checked yet.
- **Vocabulary / thesaurus** — *Vocabulary for Learners of German: A Comprehensive Thesaurus* (536 p,
  TEXT), Langenscheidt *Basic German Vocabulary* (+ its vision-only `Ubungsbuch`), *Mastering German
  Vocabulary*, *Using German Synonyms* / *Dictionary of German Synonyms* (djvu, vision), Schaum's
  *Outline German Vocabulary*, two Practice Makes Perfect vocabulary volumes.
- **Dictionary** — *German Student Dictionary* (510 p, TEXT).
- **Idiom / colloquial / slang — the flagship category for this project's purposes:**
  **`04.Miscellenous/Dirty German Everyday Slang.pdf`** (178 p, vision) is the direct slang
  counterpart to Hungarian's and Spanish's named slang sources. Also *Cassell's Colloquial German: A
  Handbook of Idiomatic Usage* (89 p, vision), *Colloquial German* and *Colloquial German 2* (187 p
  TEXT / 118 p TEXT — note *Colloquial German 2* unusually has a text layer while *1* doesn't),
  *Perfect Phrases in German for Confident Travel* (177 p, TEXT).
- **Verbs** — *The Big Yellow Book of German Verbs* (706 p, TEXT), Practice Makes Perfect *Verb
  Tenses* / *Pronouns and Prepositions* / *Sentence Builder*.
- **Dialect** — *Schwyzertüütsch: Praktische Sprachlehre des Schweizerdeutschen* (Swiss German, 83 p,
  vision) — the one dialect-contrast title in the stash, parallel to Spanish's Rough Guide
  three-way split or Dutch's register ladders.
- **Reading/writing skills** — *Reading German History: A German Reading Course for Beginners*
  (161 p, TEXT), *Developing Writing Skills In German* (273 p, TEXT), *German Quickly: A Grammar for
  Reading German* (453 p, TEXT), *Schreiben in Alltag* (82 p, vision).
- **The multi-level course-series collection — by far the largest file count, almost entirely
  vision-only, and the single biggest cost driver in this stash.** Six separate course series, each
  spanning multiple levels and each level split into Kursbuch/Arbeitsbuch/Lehrerhandbuch/Glossar/
  Testheft parts:
  - **Lagune** (levels 1–3, 18 files incl. covers)
  - **Schritte International** (levels 1–6, ~20 files)
  - **Moment Mal** (levels 1–3, 15 files)
  - **Themen Aktuell** (levels 1–3, 15 files)
  - **Em neu 2008** (Hauptkurs / Abschlusskurs / Brückenkurs, 12 files)
  - Standalone intro courses: *Deutsch Heute*, *Neue Horizonte*, *Wie geht's*, *Routledge Intensive
    German Course*, and the three Teach Yourself titles (*German*, *Further German*, *Improve Your
    German*).
  This entire category is pedagogically redundant with itself (multiple competing beginner courses
  covering the same ground) and is almost all `Lehrerhandbuch`/`Arbeitsbuch` material — teacher's
  manuals and workbooks, lower linguistic-analysis value than a reference grammar or dictionary, and
  overwhelmingly vision-only. **Treat as lowest priority; representative-sample rather than extract
  every level of every series in full** (see Section 7).
- **Graded readers** — `05.Graded Readers and Newspapers for Learners/` (5 titles: *Das feuer Schiff*,
  *Das Mädchen mit dem die Kinder nicht verkehren durften*, *Brigitta*, *Der gestiefelte Kater*, *Tor
  ohne Grenzen*) plus the unprefixed `Graded Readers for Learners/` (15 titles, mostly short
  30–110 p mysteries/dramas, 2 with a text layer: *Ein Mann zu viel*, *Tödlicher Schnee*). Same
  pedagogically-controlled status as every other language's graded-reader folders — useful for
  level-tiered vocabulary, not usage evidence.

---

## 6. Priority tiers

### TIER 1 — reference grammars & academic linguistics (highest value)

Root-level numbered grammars + `03.Grammars+Workbooks/` + the linguistics/history titles. ~27 files,
majority TEXT. This is where the grammar-logic work should start — mirrors every prior language's
Tier 1. **Hammer's German Grammar and Usage** (597 p, vision) is the single highest-value individual
title despite needing vision reading — it's the comprehensive reference grammar equivalent to
Spanish's *Big Red Book* or Dutch's major reference.

### TIER 2 — vocabulary, dictionary, idiom & slang (fills the slang-synthesis need directly)

*Dirty German Everyday Slang* (flagship), the two Colloquial German volumes, Cassell's Colloquial
German, *Vocabulary for Learners of German*, German Student Dictionary, the synonym pair, *Perfect
Phrases in German for Confident Travel*, *Schwyzertüütsch* (dialect contrast). ~13 files, mixed
TEXT/vision.

### TIER 3 — verbs & reading/writing skill-building

*Big Yellow Book of German Verbs*, the three Practice Makes Perfect grammar-adjacent titles, *German
Quickly*, *Reading German History*, *Developing Writing Skills In German*, *Schreiben in Alltag*.
~8 files, mostly TEXT.

### TIER 4 — the multi-level course-series collection (lowest priority, highest cost)

Lagune, Schritte International, Moment Mal, Themen Aktuell, Em neu 2008, plus the standalone intro
courses and Teach Yourself titles. **~75 files, the large majority vision-only** — this is the
category to apply representative sampling or selective extraction to rather than extracting in full
(see Section 7). Pedagogically redundant across series; lowest research value per page of any
category here.

### TIER 5 — graded readers

20 titles across the two readers folders, almost all vision, almost all short (16–115 p). Lowest
priority, same status as every prior language's graded-reader tier.

---

## 7. Extraction notes

- **82 of 133 real-candidate files need vision reading (62%)** — the highest vision-dependency ratio
  of any language triaged in this project to date on a real-content basis. Budget accordingly; this
  is the single biggest cost driver, concentrated almost entirely in Tier 4.
- **Strongly recommend NOT extracting every level/part of every course series in Tier 4 in full.**
  Six series × 3-6 levels each × 4-5 parts (Kursbuch/Arbeitsbuch/Lehrerhandbuch/Glossar/Testheft) per
  level is ~75 files of largely redundant beginner-pedagogy content, almost all vision-only — exactly
  the kind of token-burn risk the user already flagged for Cantonese. Consider: extracting one
  complete series in full (e.g. Schritte International, which has the most levels and the most TEXT
  coverage) as the course-series representative, and sampling the Kursbuch only (skipping
  Lehrerhandbuch/Testheft) from the others.
- **The two DJVU files** (`Dictionary of German Synonyms.djvu`, `Langenscheidt Basic German
  Vocabulary Ubungsbuch.djvu`) need `ddjvu` rendering, consistent with every prior language's DJVU
  handling.
- **Verify the three similarly-titled linguistics textbooks are genuinely distinct works, not
  duplicate scans**, before scheduling all three (Section 5) — same caution Spanish's *Colloquial
  Spanish 2* vs *Colloquial Spanish of Latin America 2* near-miss taught.
- **`Colloquial German` (vol. 1, 187p) has no text layer while `Colloquial German 2` (118p) does** —
  an inconsistency worth spot-checking before assuming vol. 1 is simply a worse scan; it could also be
  a different edition/printing.
- No representative-sampling-sized single dictionary appears in this stash (German Student Dictionary
  at 510p is large but not in the 700-1800p range that triggered sampling for Korean/Spanish/
  Hawaiian) — full extraction is reasonable for every Tier 1-3 title.

## 8. Recommended wave structure

Not yet authorized — **triage only was requested.** For when extraction is approved:

1. **Wave 1 — Tier 1 reference grammars** (root numbered files + `03.Grammars+Workbooks`): ~27 files,
   majority TEXT, highest value, directly feeds grammar-logic work.
2. **Wave 2 — Tier 1 linguistics/history + Tier 2 vocabulary/dictionary/idiom/slang**: ~18 files,
   mixed TEXT/vision, includes the flagship *Dirty German Everyday Slang*.
3. **Wave 3 — Tier 3 verbs & reading/writing skills**: ~8 files, mostly TEXT, cheapest wave.
4. **Wave 4 — Tier 4 course series, representative subset only** (one full series + Kursbuch-only
   sampling from the rest, per Section 7) — scope this wave's exact file list at dispatch time, not
   now, since it depends on a scoping decision not yet made.
5. **Wave 5 — Tier 5 graded readers**: ~20 files, vision-heavy, lowest priority.

**Not scheduled:** the 3 `.rar` archives (Section 3); the ~50-issue `Der Weg` magazine archive
(Section 4, bulk usage-corpus material).
