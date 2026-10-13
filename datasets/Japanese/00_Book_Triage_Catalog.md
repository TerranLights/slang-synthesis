# Japanese — Reference Material Triage Catalog

**Status: full triage complete, 2026-10-13.** Source folder is
`source_reference/languages/Japanese/` (8.9GB, 619 files across 14 top-level folders + loose
files). **By far the largest corpus this project has triaged** — more than 2x Russian's previous
record (204 files/3.6GB). Surveyed via 7 parallel triage subagents, one per major section.

**Structural difference from every prior language:** almost nothing in this corpus has a usable
clean text layer. CJK script defeats OCR far more consistently than any Latin/Cyrillic-script
language this project has handled — the standard "Wave 1 clean-text / Wave 2 vision-read" split
used for every prior language doesn't map cleanly here, since the large majority of in-scope
material is image-only scans requiring vision-reading regardless of category. Waves below are
therefore organized by **content category**, not text-layer status; text-layer status is noted
per-item where it affects extraction approach.

**New font-cipher/corruption variants found (beyond Hungarian/Korean/Russian/Dutch/Romanian's
catalogued mechanisms), confirmed across multiple independent sources in this triage:**
1. **CJK-glyph-to-exotic-Unicode-block substitution** (embedded font with no ToUnicode map) —
   kana/kanji render as Samaritan, Hangul-Jamo-filler, or other exotic Unicode blocks while
   embedded romaji/English stays legible. Seen in: *Colloquial Japanese* (both the top-level
   Ogawa/Enokida copy and the separate Routledge copy — distinct books, same corruption type),
   *A Dictionary of Japanese Particles*, *Japanese: A Comprehensive Grammar*, *Writing E-mails in
   Japanese*, *Shin Nihongo no Kiso II Textbook* (text layer decodes to unrelated scrambled
   kanji/kana, not the rendered page content at all), the Hungarian-Japanese dictionary.
2. **"Let's learn Kanji" / "Let's learn more Kanji" DJVU pair** — kana/kanji OCR'd as
   Cyrillic-lookalike Latin glyphs (e.g. "Я", "ш").
3. **Character-by-character romaji splitting with particle substitution** — "All About Particles":
   Latin letters split one-per-line vertically; particles render as wrong glyphs (を→0).
4. **Clean-but-cosmetic-artifact variants**: "New Approach Japanese Intermediate 1" (text layer is
   only a forum watermark repeated per page, real content is image-only); "500 Essential Japanese
   Expressions" (Chinese scan-watermark text, same pattern).
5. **Remembering the Kanji 3**: mangled font-substitution glyph noise mixed with otherwise-readable
   English glosses (milder cosmetic case, usable with cleanup).

## Scope filtering — excluded entirely

- **Pure navigation, not content**: the entire `01.Book List/` folder (7 JPG file-explorer
  screenshots of the corpus's own subfolders — contributes nothing as reference material).
- **Non-English-metalanguage material**: *Japonés en viñetas* (Spanish-medium manga course),
  *Shin Nihongo no Kiso I*'s two Russian-medium companion volumes (grammar commentary + translation
  booklet), *Shin Nihongo no Kiso II*'s kanji workbook (confirmed Spanish-language edition despite
  sitting next to the English explanations file).
- **Non-English bilingual dictionaries**: *Magyar-Japán Szótár* (Hungarian-Japanese), *Elementary
  School Student's Kanji Dictionary* (fully monolingual Japanese, no English bridge).
- **Confirmed exact/duplicate-format files**: top-level `Heisig - Remembering The Kanji 1/2/3.pdf`
  (byte-identical to the copies inside `James Heisig/Remembering the Kanji/` — use the subfolder
  copies only); `Essential Japanese Expressions.pdf` = `Nihongo Hyogen Bunkei Jiten...pdf` (MD5-
  identical, keep one); the 3 VocabuLearn `.djvu` files (page-count-identical to their sibling
  `booklet N.pdf` files, same scanned booklets in a second container — keep the PDFs); `Bunka
  Nihongo Chuukyuu 1.djvu` (duplicate of the PDF in the same folder).
- **Pure answer-key/test-drill booklets with no explanatory content**: *Kanzen Master Bunpou
  3kyuu seikai* (6pp pure answer key), *Nihongo Nouryoku Shiken 1kyuu-2kyuu*'s reading-drill and
  answer-key pair (confirmed zero explanatory grammar, matching this project's standing
  test-drill-exclusion precedent) — contrast with *New JLPT N3 Taisaku-mondai*, which does carry
  real explanatory grammar boxes and stays in scope.
- **Travel guides, pure history/politics/sociology/mythology/film criticism**: the large majority
  of `08.Society,Culture,History,Tourism/` (Frommer's x2, Insight Guides, Lonely Planet x2,
  Culture Shock! Japan, Contemporary Japan, Introduction to Japanese Society, Japan: A Global
  Studies Handbook, Japanese Culture, japanese gods and myths, Japanese mythology A-Z, Japan Its
  History and Culture, Japan Through the Looking Glass, Modern Japan x2, Shinto, The Anime
  Encyclopedia, The Cambridge Companion to Modern Japanese Culture, The New Japan, The Samurai
  Sourcebook, Understanding Japanese Society, Understanding Manga and Anime, Anime from Akira to
  Howl's Moving Castle, Introduction to Japanese Horror Film, Comprendre le Japon [also wrong
  language]) and a handful from `09.Miscellaneous/` (A History of Japanese Literature, Folktales
  from the Japanese Countryside, Introduction to Academic Presentations, Japanese folk songs,
  Learning Japanese from Songs, Sing and Learn Japanese — all confirmed low-signal for this
  project's purposes).
- **No-content placeholder folders**: `06.../Light Novels (ranobe)/Sample Book Covers/` (10 cover
  thumbnails, zero actual book content); `Teach Yourself Instant Japanese/` (12 promotional JPGs,
  no actual book file); `Mastering Japanese by Ear Audio Cover.pdf` (thumbnail only).
- **Deferred per standing precedent**: `Glossika/` (3 phrase-drill volumes, furigana+IPA-annotated
  — genuinely clean quality, but deferred matching the Hungarian-triage Glossika precedent unless
  revisited later).

## In-scope material — grouped by category (waves below)

### Wave 1 — Writing System foundation (`02.Japanese Writing System/` + `James Heisig/`)

~25 files. Nearly all vision-read (image-only scans); a few have clean or lightly-corrupted text
layers (noted). This is foundational for Japanese's multi-script typology profile (hiragana/
katakana/kanji) and should be dispatched first/alongside Wave 2, since every other wave's
vocabulary entries will need to cite this system.

Highlights: both Heisig "Remembering the Kana" volumes, all 3 Heisig "Remembering the Kanji"
volumes (vol. 1 & 3 have clean text, vol. 2 is image-only), *A Guide to Reading and Writing
Japanese*, *Basic/Intermediate Kanji Book* series, *Kanji Pict-O-Graphix*, *Read Japanese Today*
(clean text), *Kanji in Context*, the Doraemon and Ryuugakusei native-curriculum kanji textbooks,
the font-cipher-corrupted "Let's learn Kanji"/"Let's learn more Kanji" pair, the Hiragana/Katakana
worksheet+answer-key pair (clean text).

### Wave 2 — Grammar, Workbooks, Usage (`04.Grammar, Workbooks, Usage/`)

42 of 44 files in scope (excludes the 1 pure answer-key booklet and 1 likely-pure-drill item
pending a spot-check). Nearly all vision-read. This is the core grammar-reference wave.

Highlights: the full *Dictionary of {Basic/Intermediate/Advanced} Japanese Grammar* trilogy,
*Japanese: A Comprehensive Grammar* (Routledge, font-cipher corrupted), *A Dictionary of Japanese
Particles* (font-cipher corrupted), *All About Particles*, *501 Japanese Verbs* (clean text), the
10-part *Nihongo Notes* situational-usage essay series, *Japanese Respect Language* (keigo/
politeness — high register value), the *Kanzen Master Bunpou* JLPT grammar series (N1/N2/N3, one
volume with clean text), *Making Sense of Japanese* (clean text) + its companion, *Nihongo bunkei
ziten* (sentence-pattern dictionary).

### Wave 3 — Audio Courses, Textbooks (`03.Audio Courses, Textbooks/`)

~65 files in scope (two triage passes, "part A" roughly A-J, "part B" roughly J-Z). Nearly all
vision-read; several font-cipher-corrupted (*Colloquial Japanese* 2nd Ed, *Genki II* — scrambled/
duplicated OCR rather than clean cipher, *Hugo Japanese in 3 Months* — Latin-glyph-index scramble,
*Shin Nihongo no Kiso II Textbook*). This is the largest single wave by file count — the biggest
flagship course titles (Genki, Nakama both editions, JBridge series, Japanese for Busy People,
Bunka Nihongo series, Mirai, Minna no Nihongo-adjacent titles) live here. Flag for de-dup
verification at extraction time: "chuukyuu kara manabu.pdf" vs. top-level "Chuukyuu kara manabu
nihongo.pdf"; the two "Busy People I Kana Workbook" files.

Register/slang-relevant highlight: *Nihongo Chuukyuu J301* has explicit colloquial-contraction
drills (てしまう→ちゃう) directly relevant to slang mechanics.

### Wave 4 — Vocabulary, Expressions, Idioms + Dictionaries, Phrasebooks
(`05.Vocabulary.../` + `07.Dictionaries.../`)

~25 files in scope. Two files are **oversized dictionaries flagged for REPRESENTATIVE SAMPLING, not
exhaustive extraction**: *NTC's New Japanese-English Character Dictionary* (2217pp) and *The
Kodansha Kanji Learners Dictionary* (1054pp) — both excellent quality, just too large.

**Flagship slang sources**: *Dirty Japanese Everyday Slang* and *Zakennayo! The real Japanese you
were never taught in school* — both romanized-dialogue-plus-English-translation format, directly
analogous to this project's other languages' slang-dictionary flagships. *Making Out In Japanese*
and *More Making Out In Japanese* (confirmed distinct content, not duplicates) are a second slang
pair. Also: *101 Japanese Idioms*, *A Handbook of Common Japanese Phrases*, *A Practical Guide to
Mimetic Expressions* (onomatopoeia — a genuine Japanese-typology feature worth documenting), *The
Complete Idiot's Guide to Conversational Japanese* (clean text, 433pp, large enough to extract in
full since it's conversational, not a pure dictionary).

### Wave 5 — Children's Books, Readers (`06.Children's Books, Readers/`) — tiered

This folder is actually 3 different tiers mislabeled under one name:
1. **4 substantial annotated literary readers** (115-354pp DJVUs: *Breaking into Japanese
   Literature*, *Exploring Japanese Literature*, *Read Real Japanese*, *Moons, Months and
   Seasons*) — genuinely glossed parallel-text intermediate/advanced readers (Mishima, Tanizaki,
   Kawabata). **Extract in full.**
2. **~28 short picture-book folk tales** (2 standalone PDFs + 11 "Favorite Stories" + 15
   graded-reader image-books across 3 level-packs, 8-24pp each, pure narrative, no learner
   annotation) — **representative sample only, ~4 titles** spanning the 3 graded-reader levels plus
   one Favorite Stories title, per the Russian Сказочник / Dutch fairy-tale precedent. Not
   exhaustive.
3. **"Light Novels (ranobe)"** — no actual content, 10 cover thumbnails only. Skip entirely.

### Wave 6 — Society/Culture gems + remaining course material

A small set of real finds hiding in otherwise-excluded folders, plus the remaining named top-level
folders:
- From `08.../`: *Japanese: A Story of Language and People* (misfiled sociolinguistics, 31pp),
  *Language and Society in Japan* (explicit sociolinguistics/script reference, 180pp), and two
  borderline-but-real register-adjacent works (*Different Games, Different Rules* — cross-cultural
  pragmatics; *Japan Pop!* — discusses character speech-style/register in anime/manga).
- From `09.../`: ***The dialects and culture of the Kinki region - Kinki Japanese*** — **high-value
  flagship dialect/slang find**, contains explicit dialect vocabulary entries with glosses (e.g.
  "hagaii" 歯痒い = frustrating) despite messy OCR spacing; *The Languages of Japan* (linguistics/
  dialect/typology reference, clean text); *Womansword: What Japanese Words Say about Women*
  (explicitly gendered vocabulary/register); *Writing E-mails in Japanese* (politeness/register,
  font-cipher corrupted); *Introduction to Japanese Pronunciation Theory and Practice* and
  *Pronounce It Perfectly in Japanese* (pronunciation references, vision-read).
- `Routledge Colloquial Japanese/Colloquial Japanese.pdf` (395pp, font-cipher corrupted — distinct
  book from the Ogawa/Enokida "Colloquial Japanese" in Wave 3, same corruption type).
- `TY Books/`: *Teach Yourself Japanese Complete Course* (183pp) + *Teach Yourself Phone Japanese*
  (32pp, font-cipher corrupted, colloquial phone-conversation register).
- Top-level loose: *4805312378 Basic Japanese Verbs.epub* (clean text, verb reference).

## Recommended Phase 1 extraction priority order

Given the unprecedented scale (≈180+ in-scope source files, nearly all requiring vision-reading),
this will be the largest Phase 1 push in the project's history — likely spanning many dispatch
waves across multiple operating-hours windows, comparable to or exceeding Russian's multi-session
push. Suggested order: **Wave 1** (writing-system foundation, needed for typology grounding) →
**Wave 2** (core grammar) → **Wave 4** (vocabulary/dictionaries, including the flagship slang
sources) → **Wave 3** (the large audio-course corpus) → **Wave 5** (tiered readers) → **Wave 6**
(remaining gems + course material).

## Morphological typology (preliminary, per Phase 0 convention)

**Japanese: agglutinative, with a unique multi-script writing system** (hiragana for native
grammar/function words, katakana for loanwords/emphasis, kanji for content morphemes, often mixed
within a single word) — the first language in this project where "word" boundaries in the writing
system itself don't map cleanly onto spoken-word boundaries (no spaces between words in standard
text), a genuinely new typological wrinkle for
`../00_Word_Concept_and_Morphological_Typology_Guide.md` to address. Verb/adjective conjugation is
heavily agglutinative (stacking tense/polarity/politeness/causative/passive suffixes onto a single
stem). A pervasive, grammaticalized honorific/politeness (keigo) register system — distinct in kind
from every prior language's register marking, since it's obligatorily grammatically marked rather
than optional lexical choice — will be a central finding once Wave 2/6 material lands. Will be
refined further once extraction lands at scale.
