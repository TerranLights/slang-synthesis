# Language Index

**Purpose.** A single master catalog of every real-world language this project has, is working on,
or will eventually work on — cutting across `source_reference/` (Phase 1 raw material),
`datasets/<Language>/` (Phase 1 extraction + Phase 4 analysis), and `language_corpus/<Language>/`
(Phase 3 slang corpus). `datasets/00_Analysis_Index.md` and `language_corpus/00_Corpus_Collection_
Index.md` track per-language *pipeline progress*; this file tracks the *language roster itself* —
what exists, what's missing, and which languages matter most to the actual sci-fi setting this
project ultimately serves.

Organized by **language family**. Within a family, each language lists the **nations** relevant to
it — since slang varies by country even within one language (Mexican Spanish vs. Argentine Spanish,
Brazilian vs. European Portuguese, American vs. British English) — and whether it's already
represented in `source_reference/languages/`.

---

## High-priority set: the Inner Tepenia GDD Gini-adjusted census

**These 43 nations are the languages actually represented in the sci-fi universe this project
ultimately serves** — pulled from the Inner Tepenia GDD repo's own worldbuilding census
(`Worldspace/Locations-and-Levels/Outside-World/Tepenian-Federation/Locations/Cities/
Upper_Earth_Immigration_Composition.md`, "Gini-adjusted effective exile populations" table, and
cross-checked against `National_Origin_Composition_Audit_2026-09-05.md`, which independently
confirms the same 43-nation count). Nations are ranked there by **Gini-adjusted effective exile
population** — GDP per capita as a proxy for who could historically access/support the setting's
"robot" technology, penalized by each nation's Gini (income-inequality) coefficient, since high
inequality shrinks the population fraction with meaningful access even in a high-GDP nation. This
determines which national-origin communities populate the setting's Antarctic exile cities and in
what proportion — i.e., these are the real-world cultures whose languages most directly need
in-universe slang derivations.

**Below, every language tied to at least one of these 43 nations is marked 🔴 HIGH PRIORITY** in its
family section, with the nation(s) and effective-population figures noted for context. This is a
floor, not a ceiling — **the project will extract, scrape, and analyze many other languages too**;
these 43 nations are simply the ones already known to matter most.

**No hierarchy of dominance among the 43.** The effective-population figures describe how many
people the setting's own worldbuilding census assigns to each national-origin community — they are
*not* a research-priority ranking. Mandarin (~210M effective) and Bulgarian (~1.2M effective) are
equally valid subjects of study; each language gets collected, analyzed, and mechanically
understood on its own terms, regardless of how many speakers it has. Population size is one
descriptive attribute among several, not a ranking axis — do not read "high priority" as "the
biggest ones matter most."

**⚠ Known caveat, inherited from the source docs and not yet resolved there:** the GDD's own audit
file found the same Davis/Zhongshan Russia-tier inconsistency recurring **33 times** across city
Specs files, and flagged it as unfixed ("nothing has been fixed — this file is the finding, not the
repair"). The 43-nation *roster* is stable (confirmed by two independent passes), but *which tier*
(Primary/Significant/Notable) a given nation lands in at a specific city may still be in flux
upstream. Treat the roster below as reliable; treat any specific city's tier assignment as
provisional if you ever need to cite one.

---

## Indo-European

### Germanic branch

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **English** | USA (~155M eff.), UK (~32M eff.), Canada (~20M eff.), Australia (~13M eff.), New Zealand (~2.6M eff.) | Present (`English Grammar Ebook collection`; `Old English Language Learning Pack` covers the historical stage only — modern reference exists separately) | 🔴 **HIGH PRIORITY** — five separate nations; expect real dialectal slang divergence (American/British/Canadian/Australian/NZ) worth tracking per-nation once corpus work begins |
| **German** | Germany (~46M eff.), Belgium (partial, ~6.4M eff., trilingual) | **Not present — gap.** No German-language reference material found in `source_reference/languages/`. | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Dutch** | Netherlands (~10M eff.), Belgium (partial, trilingual) | Present (`Dutch`; Phase 1 test-run in progress, see `methodology-observations/dutch_test_run.md`) | 🔴 **HIGH PRIORITY** |
| **Swedish** | Sweden (~6M eff.) | Present (`Swedish`) | 🔴 **HIGH PRIORITY** |
| **Norwegian** | Norway (~3.3M eff.) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| Danish | — | Present (`Danish`) | cataloged, not GINI-tagged |
| Icelandic | — | Present (`Icelandic`, `Icelandic-Faroese`) | cataloged, not GINI-tagged |
| Old English | — (historical stage, not a living GINI nation) | Present (`Old English Language Learning Pack`) | cataloged, not GINI-tagged |

### Romance branch

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **French** | France (~35M eff.), Canada (partial), Belgium (partial, trilingual) | Present (`French Learning Books`) | 🔴 **HIGH PRIORITY** |
| **Italian** | Italy (~27M eff.) | Present (`Italian`) | 🔴 **HIGH PRIORITY** |
| **Spanish** | Spain (~20M eff.), Mexico (~18M eff.), Argentina (~6M eff.), Chile (~2.3M eff.), Uruguay (~0.6M eff.) | Present (`Spanish`) | 🔴 **HIGH PRIORITY** — five nations; strong candidate for per-nation slang subdivision (Iberian vs. Mexican vs. Rioplatense vs. Chilean Spanish are famously divergent registers) |
| **Portuguese** | Brazil (~17M eff.) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Romanian** | Romania (~4.5M eff.) | Present (`Romanian`, plus `Romanian collection.zip.gz` — likely redundant, flagged in `language_corpus/00_Corpus_Collection_Index.md`) | 🔴 **HIGH PRIORITY** |

### Slavic branch

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Russian** | Russia (~25M eff., or absent at some cities per the Davis/Zhongshan tier-inconsistency flagged above) | Present (`Russian`) | 🔴 **HIGH PRIORITY** |
| **Polish** | Poland (~12M eff.; also political center of the Intermarium/Intermaria meta-nation bloc) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Czech** | Czech Republic (~5M eff.; among the highest per-capita robot-access rates of any nation per the source doc) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Ukrainian** | Ukraine (~5M eff.) | **Not present — gap** (only Russian exists; do not substitute one for the other). | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Serbian/Croatian/Bosnian** | Serbia (~1.2M eff.), Croatia (~1.3M eff.) | Present, **Phase 1 complete** (`Serbian, Croatian, Bosnian`; see `datasets/Serbian_Croatian_Bosnian/`) | 🔴 **HIGH PRIORITY — furthest along of any GINI language** |
| **Bulgarian** | Bulgaria (~1.2M eff.) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Slovak** | Slovakia (~2.2M eff.) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Belarusian** | Belarus (~1.5M eff.) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Slovenian** | Slovenia (~1M eff.; "excellent rate, tiny population" per source) | Present (`Slovene (Slovenian Language) Learning Pack`) | 🔴 **HIGH PRIORITY** |

### Baltic branch

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Lithuanian** | Lithuania (~1M eff.) | Present (`Lithuanian`) | 🔴 **HIGH PRIORITY** |
| **Latvian** | Latvia (~0.6M eff.) | Present (`Latvian Language Learning Pack (Updated)`) | 🔴 **HIGH PRIORITY** |

### Hellenic, Indo-Iranian, Celtic branches (cataloged, not GINI-tagged)

| Language | `source_reference/` status | Priority |
|---|---|---|
| Greek (Modern) | Present (`Greek`, `Modern Greek Language Learning Pack`, `TTC - Greek 101`) | cataloged, not GINI-tagged |
| Greek (Ancient) | Present (bundled with the above) | cataloged, not GINI-tagged |
| Persian | Present (`Persian`) | cataloged, not GINI-tagged |
| Kurdish | Present (`Kurdish`) | cataloged, not GINI-tagged |
| Sanskrit | Present (`Sanskrit Language Learning Pack`) | cataloged, not GINI-tagged |
| Avestan | Present, unsorted (`Teach Yourself Avesta...`) | cataloged, not GINI-tagged |
| Irish | Present (`Irish`) | cataloged, not GINI-tagged |

---

## Uralic

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Finnish** | Finland (~3.3M eff.) | Present (`Finnish`) | 🔴 **HIGH PRIORITY** |
| **Estonian** | Estonia (~0.6M eff.; "highest effective conversion rate of any Intermarium member" per source) | Present (`Estonian`, ~1.3 GB) | 🔴 **HIGH PRIORITY** |
| **Hungarian** | Hungary (~3M eff.; core Intermarium member) | Present, **Phase 1 complete** (`Hungarian`; see `datasets/Hungarian/`) | 🔴 **HIGH PRIORITY — second-furthest along of any GINI language** |

---

## Japonic

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Japanese** | Japan (~65M eff.) | Present (`Japanese`) | 🔴 **HIGH PRIORITY** |

## Koreanic

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Korean** | South Korea (~26M eff.) | Present (`Korean`) | 🔴 **HIGH PRIORITY** |

## Sino-Tibetan

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Mandarin** | China (~210M eff. — the largest effective pool of any nation in the census, noted for context only, not priority) | Present (`Mandarin`) | 🔴 **HIGH PRIORITY** |
| Cantonese | — (China's census entry maps to Mandarin as the national standard; Cantonese not separately broken out by the source doc) | Present (`Colloquial Cantonese The Complete Course for Beginners`) | cataloged, not separately GINI-tagged — worth revisiting if the setting ever distinguishes a Cantonese-speaking sub-community from Mandarin-speaking China at a specific city |
| Tibetan | — | Present (`Tibetan`) | cataloged, not GINI-tagged |

## Austronesian — all gaps

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Indonesian** | Indonesia (~16M eff.) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Malay** | Malaysia (~5M eff.) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Filipino/Tagalog** | Philippines (~5M eff.; "massive population base (110M) saves the effective number despite severe inequality" per source) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |

## Kra-Dai — gap

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Thai** | Thailand (~8M eff.) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |

## Austroasiatic — gap

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Vietnamese** | Vietnam (~5M eff.) | **Not present — gap.** | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |

## South Africa — open question, not yet assigned to a single language

South Africa (~3M eff., "extreme Gini (0.63) — severe reduction from 60M population" per source) has
**11 official languages** (English, Afrikaans, Zulu, Xhosa, and 7 others); the census source doesn't
specify which one(s) the setting's South African exile community would actually speak/carry as
slang-relevant. **Not resolved — needs a decision** (likely English and/or Afrikaans as the most
probable candidates for a robot-owning, historically privileged emigrant population under this
setting's own premise, but that's an inference, not a documented fact from the source). English is
already present in `source_reference/` and would partially cover this nation if that inference holds;
no Afrikaans/Zulu/Xhosa material currently exists.

🔴 **HIGH PRIORITY, LANGUAGE-ASSIGNMENT UNRESOLVED**

---

## Afroasiatic (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Hebrew | Present (`Hebrew`) |
| Akkadian (Assyro-Babylonian) | Present (`Akkadian`, `Akkadian (Assyro-Babylonian) Language Learning Pack`) |
| Middle Egyptian | Present (`Middle Egyptian`) |
| Classical Syriac | Present (`Classical Syriac`) |

## Turkic (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Turkish | Present (`Turkish Language Learning Pack`) |
| Kazakh | Present (`Kazakh Language Learning Pack`, `Colloquial Kazakh`) |

## Mongolic (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Mongolian | Present (`Mongolian`, `An Elementary Mongolian Grammar`, plus two historical/literary works — `Ocean of Milk, Ocean of Blood`, `Secret History of the Mongols` — that likely belong filed under this language, not as stray top-level files) |

## Niger-Congo / other African (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Swahili | Present (`Swahili`) |

## Dravidian (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Tamil | Present (`A Reference Grammar of Spoken Tamil`) |

## Uto-Aztecan (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Nahuatl | Present (`Libros Para Aprender Nahuatl`) |

## Quechuan (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Quechua | Present (`Quechua`) |

## Language isolate (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Sumerian | Present (`Sumerian Language Learning Pack`) |

## Constructed (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Esperanto | Present (`Esperanto`) |

---

## Summary: acquisition gaps among the 43 high-priority nations

**See `LANGUAGE_ACQUISITION_TODO.md`** for these 14 languages as an actionable shopping list (what
to look for), listed alphabetically — no dominance hierarchy among them.

**14 GINI-priority languages currently have zero `source_reference/` material** and need real ebook
acquisition before their Phase 1 can even begin — accounting for 16 of the 43 nations (Germany and
Belgium's German component share the German gap; South Africa's language is separately unresolved,
not counted in the 14):

German (Germany, Belgium's German-speaking component), Portuguese (Brazil), Norwegian (Norway),
Polish (Poland), Czech (Czech Republic), Ukrainian (Ukraine), Bulgarian (Bulgaria), Slovak
(Slovakia), Belarusian (Belarus), Indonesian (Indonesia), Malay (Malaysia), Filipino/Tagalog
(Philippines), Thai (Thailand), Vietnamese (Vietnam) — plus the unresolved South Africa
language-assignment question above (a 17th gap nation, uncounted in the 14 since no single
language has been identified for it yet).

**27 of the 43 nations already have usable reference material** (18 distinct languages, several
covering multiple nations) and could start Phase 1 immediately once prioritized: English (USA, UK,
Canada, Australia, New Zealand — 5 nations), Dutch (Netherlands; also partially covers Belgium),
Swedish, French (France; also partially covers Canada and Belgium), Italian, Spanish (Spain,
Mexico, Argentina, Chile, Uruguay — 5 nations), Romanian, Russian, Serbian/Croatian/Bosnian (Serbia,
Croatia — 2 nations), Slovenian, Lithuanian, Latvian, Finnish, Estonian, Hungarian, Japanese,
Korean, Mandarin.

**Two languages have already reached full Phase 1 completion**: Serbian/Croatian/Bosnian and
Hungarian — see `datasets/00_Analysis_Index.md` for current status of every language in progress.

---

## Maintenance rule

Update this file whenever: (a) a new language folder is added to `source_reference/languages/`,
(b) a language reaches a new Phase milestone worth noting here, or (c) the Inner Tepenia GDD
census itself changes (re-check `Upper_Earth_Immigration_Composition.md` and the audit file for
drift — the audit file's own "33 instances of tier inconsistency, unfixed" warning means the
upstream census could still change before this project needs to rely on a specific city's tier
assignment). This file is the language *roster*; `datasets/00_Analysis_Index.md` and
`language_corpus/00_Corpus_Collection_Index.md` remain the sources of truth for per-language
pipeline *progress*.
