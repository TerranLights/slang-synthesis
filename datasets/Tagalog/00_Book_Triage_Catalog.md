# Tagalog — Reference Material Triage Catalog

**Status: full triage complete, 2026-10-18.** Source folder is
`/media/kuroskalacs/Home-Theater/w-lang/Tagalog (Filipino)/` (an external-drive stash, not yet
copied into this project's `source_reference/` tree — see note below). 25 real files, ~303MB.
Tagalog is directly relevant to both this project and the user's parallel "Tepenian Hawaiian"
pidgin-synthesis work, alongside Korean, Latin American/Mexican Spanish, and Ilocano.

**Location note:** this corpus currently lives on the external drive path above, not under this
repo's own `source_reference/languages/Tagalog/`. Before Phase 1 extraction begins, it should be
copied into this project's standard source-material location (matching every other language's
layout) — flagging this now so it isn't forgotten at extraction time.

## Scope filtering — excluded entirely

- **Non-English-metalanguage material**: `07 Учебник тагальского языка.djvu` (Russian-medium
  Tagalog textbook), `10 Kauderwelsch Tagalog für Globetrotter.pdf` (German-medium phrasebook,
  confirmed German series by title), `15 Тагальский язык.djvu` (Russian-medium).
- **Non-English bilingual dictionary**: `16 Тагальско-русский словарь.djvu`/`.pdf`
  (Tagalog-Russian, no English side) — both the DJVU and PDF copies excluded.
- **Travel guide**: `19 The Rough Guide to The Philippines.pdf` (579pp, clean text, standard
  travel-guide content).
- **Wrong-metalanguage fiction**: `21 Умная Марсела - Филиппинские народные сказки.djvu`
  (Russian-medium Philippine folk tales — excluded on both metalanguage and raw-fiction grounds).
- **Confirmed duplicate-format files** (keep the listed primary, skip the rest):
  - `02 Teach Yourself Tagalog.pdf` (185pp) is the primary — `02 Teach Yourself Tagalog Part
    1.djvu` (112pp) + `Part 2.djvu` (73pp) sum to the identical 185 total pages, confirming the
    same book split across two DJVU files; skip both DJVUs.
  - `04 Headstart for the Philippines.pdf` (294pp, **clean text layer**) is the primary — the
    same-titled `.djvu` (294pp, no text layer) is a duplicate scan; skip the DJVU.
  - `09 Making Out in Tagalog.pdf` (91pp) is the primary — the same-titled `.djvu` (91pp) is a
    duplicate; skip the DJVU.

## In-scope material — grouped by text-layer status

### Group A — Clean text layer (Wave 1)

| File | Pages | Notes |
|---|---|---|
| `04 Headstart for the Philippines.pdf` | 294 | FSI-style course, clean text confirmed |
| `13 Tagalog Grammar.pdf` | 115 | Clean text, genuine grammar reference |
| `14 Tagalog (The World's Major Languages).pdf` | 23 | Academic linguistics chapter excerpt, clean text — typology-grounding value |
| `17 Diccionario Ingles-Español-Tagalog Part I/II/III.pdf` | 628+655+706=1,989 | Trilingual (English-Spanish-Tagalog) dictionary, clean text, antique style (headwords like "Aboard," "Abolish"). Kept in scope despite the Spanish middle column since English is genuinely present — **flag for REPRESENTATIVE SAMPLING** given the scale (~2,000 pages combined) |
| `18 The Philippines (Language and National Identity in Asia).pdf` | 14 | Sociolinguistics/language-policy excerpt, clean text — parallel to Hungarian's contact-outside-Hungary precedent |

### Group B — No text layer / corrupted (Wave 2, vision-reading)

| File | Pages | Notes |
|---|---|---|
| `01 Basic Tagalog for Foreigners and Non-Tagalogs.pdf` | 239 | No text layer |
| `02 Teach Yourself Tagalog.pdf` | 185 | Font-cipher-corrupted text layer (scrambled symbols) — vision-read regardless of the garbled layer |
| `03 Living Language Tagalog Complete Course.pdf` | 129 | No text layer |
| `04 Headstart for the Philippines Cultural Notes.pdf` | 39 | No text layer — companion booklet to the main Headstart course above |
| `06 Filipino Basic Course.pdf` | 745 | No text layer — **large course, flag for REPRESENTATIVE SAMPLING** given the scale |
| `08 Ngumiti ka naman! Tagalog with Humor - Language and Culture through Cartoons.pdf` | 172 | No text layer — cartoon/humor-based, likely register-rich |
| `09 Making Out in Tagalog.pdf` | 91 | No text layer — **flagship slang source**, directly analogous to this project's "Making Out In [Language]" slang-flagship finds in Japanese |
| `11 VocabuLearn Tagalog Level 1.pdf` | 23 | No text layer, short vocabulary-drill booklet |
| `12 Advanced Tagalog Reader.pdf` | 471 | No text layer — **large reader, flag for REPRESENTATIVE SAMPLING** |

## Recommended Phase 1 extraction priority order

**Wave 1 (5 clean-text sources):** prioritize `13 Tagalog Grammar` and `14 Tagalog (The World's
Major Languages)` first (core grammar + typology grounding), then `04 Headstart for the
Philippines` (full course), then representatively sample the large `17 Diccionario` trilingual
dictionary.

**Wave 2 (9 vision-read sources):** prioritize `09 Making Out in Tagalog` (flagship slang source)
and `08 Ngumiti ka naman!` (humor/register source) first, then the standard courses (`01`, `02`,
`03`, `04 Cultural Notes`, `11`), then representatively sample the two oversized sources (`06
Filipino Basic Course` at 745pp, `12 Advanced Tagalog Reader` at 471pp).

## Morphological typology (preliminary, per Phase 0 convention)

**Tagalog: Austronesian, with a non-concatenative, verb-centered morphosyntactic system built
around a productive affix-and-focus (voice/trigger) system** — a genuinely new typological case
for this project. Unlike every Indo-European/Uralic/Altaic/Japonic language extracted so far,
Tagalog's grammatical relations are marked through a system of verbal affixes (the "trigger" or
"focus" system: agent-trigger, object-trigger, locative-trigger, etc.) that determine which
argument is grammatically prominent, rather than through case marking or fixed word order alone.
Reduplication is a productive morphological process (for aspect, intensity, and plurality). Heavy
Spanish-loanword stratum (centuries of Spanish colonial contact) plus a growing English-loanword
stratum (post-1898 American administration) — both strata are likely to be directly relevant to
register/slang analysis, parallel to how loanword strata have proven revealing in Japanese
(katakana-marked loanwords) and other languages in this project. Will be refined further once
extraction lands at scale.
