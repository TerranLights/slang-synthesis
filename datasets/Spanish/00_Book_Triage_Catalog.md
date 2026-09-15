# Spanish — Reference Material Triage Catalog

**Status: full triage complete, 2026-09-14.** Spanish is one of the 43 Inner Tepenia GDD
Gini-index high-priority languages (Spain, Mexico, Argentina, Chile, Uruguay — 5 nations,
context-only figures, no dominance hierarchy among them) — see `../../LANGUAGE_INDEX.md`.
`source_reference/languages/Spanish/` is ~189MB, a much smaller and cleaner corpus than
Russian/Hungarian/Korean — 133 real PDF files (mostly small lesson transcripts) + 1 EPUB, no
audio/video.

**Tooling note:** the `Learning.Spanish.Like.Crazy.All.3.Levels/` subfolder holds ~140 individual
lesson-transcript PDFs across Level I/II/III sub-subfolders — use full relative paths, not
basenames, when dispatching.

---

## Scope filtering — excluded entirely

- **Misfiled non-Spanish material**: `Practice Makes Perfect Complete Japanese Grammar.pdf` — a
  Japanese grammar book sitting in the Spanish folder by mistake. Not extracted.
- **Non-content junk files**: `TutsGalaxy.com.txt`, `Downloaded from TutsGalaxy.com.txt`,
  `Download more courses.url` — torrent-site artifacts, not reference material.
- **Empty course folder**: `Michel Thomas - Spanish/` (6 numbered subfolders, all genuinely
  empty — an audio-only course whose audio was apparently never present or already removed).
- **Duplicate formats of the same book**: `Madrigal's Magic Key to Spanish.pdf` and
  `Madrigals-Magic-Key-to-Spanish.pdf` are byte-identical (confirmed via matching file size,
  5,417,836 bytes) — extract once. `Madrigals-Magic-Key-to-Spanish.epub` is the same book in a
  different format — not extracted separately.

## In-scope material — grouped by text-layer status

### Group A — Clean text layer (Wave 1)

**Standalone grammar/vocabulary references:**

| File | Pages | Notes |
|---|---|---|
| `Colloquial Spanish of Latin America The Complete Course for Beginners (2nd Ed) [2002].pdf` | 168 | Standard course |
| `Colloquial Spanish of Latin America 2 The Next Step (1st Ed) [2004].pdf` | 190 | Sequel course |
| `Madrigal's Magic Key to Spanish.pdf` | 740 | Whimsical mnemonic-based grammar/vocabulary book — large, unusual pedagogical approach |
| `Practice Makes Perfect - Basic Spanish Grammar.pdf` | 273 | Core grammar |
| `Practice Makes Perfect Advanced Spanish Grammar.pdf` | 210 | Advanced grammar — likely least redundant with Basic |
| `Practice Makes Perfect - Spanish Irregular Verbs.pdf` | 127 | Verb specialist reference |
| `Practice Makes Perfect - Spanish Verb Tenses.pdf` | 354 | Verb specialist reference |
| `Practice Makes Perfect - Spanish Vocabulary (Malestrom).pdf` | 450 | Vocabulary reference |

**`Learning.Spanish.Like.Crazy.All.3.Levels/` — course transcripts (all confirmed clean text):**

- **Level I**: 32 numbered lesson transcripts + `Insultos_01.pdf` + `insultosvulgares.pdf`
  (explicit insult/vulgar-language lessons — directly on-mission for slang work) + `readme.pdf`.
- **Level II**: lessons 31-60 (non-sequential numbering, "_trans" suffix) + 10 bonus lessons
  (a-j) + **2 bonus SLANG lessons** (`Spanish_level2_Bonus_Slang_Lesson_a_trans.pdf`,
  `..._b_trans.pdf`) — high-priority register content.
- **Level III**: lessons 61-80 + 4 bonus lessons (A-D) + 3 instructor-notes files.

This is a real, structured beginner-to-advanced course with **explicit slang and insult-focused
lessons built into its own curriculum** — the single highest-priority register source in this
corpus, comparable to how Streetwise Russian or Using Korean functioned for prior languages.

### Group B — No text layer at all (Wave 2, vision-reading)

| File | Pages | Notes |
|---|---|---|
| `Easy Spanish Step-by-Step.pdf` | 322 | Standard course, scanned |
| `Practice Makes Perfect - Complete Spanish Grammar.pdf` | 386 | Likely a combined Basic+Advanced omnibus — apply non-redundant-supplement pattern against those two once extracted |
| `Schaum's Outline of Spanish Grammar.pdf` | 217 | Reference grammar, scanned |

Confirmed via `pdftotext` sampling at pages 20/100/200/300 for each (0 chars at every sampled
page) — genuine scanned image-only PDFs, not a decodable cipher case (Latin-script scans don't
carry the Cyrillic-style font-cipher risk found in Russian/Korean, but still need the standard
vision-reading guard for handwritten marginalia).

---

## Recommended Phase 1 extraction priority order

**Wave 1 — clean text (11 distinct sources: 8 standalone + 3 Learning Spanish Like Crazy levels):**
Prioritize the Learning Spanish Like Crazy slang/insult lessons and the Practice Makes Perfect
specialist references first; Madrigal's Magic Key (740p) may need splitting into 2-3 chunks given
its length.

**Wave 2 — vision-reading (3 sources):** Easy Spanish Step-by-Step, Practice Makes Perfect Complete
Spanish Grammar (apply non-redundant-supplement against Basic+Advanced), Schaum's Outline of
Spanish Grammar.

## Morphological typology (preliminary, per Phase 0 convention)

**Spanish: fusional (inflectional)**, with a two-gender (masculine/feminine) noun system and a
verb-conjugation system marking person, number, tense, mood, and aspect through suffixation on a
verb stem — comparable to Russian's fusional case system in spirit (single endings fuse multiple
grammatical categories) but with no case marking on nouns at all (case survives only in pronoun
forms). The ser/estar copula split and the tú/vos/usted register system (usage varies
significantly by nation among the 5 GINI-represented Spanish-speaking countries) are the
register-relevant structural features most likely to matter for slang-mechanics work. Register
expressed primarily through pronoun choice (tú/vos/usted, and vosotros/ustedes regionally) plus
lexical choice, not dedicated honorific morphology. Will be refined with a real morpheme breakdown
once the first grammar extraction lands.
