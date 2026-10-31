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
| **English** | USA (~155M eff.), UK (~32M eff.), Canada (~20M eff.), Australia (~13M eff.), New Zealand (~2.6M eff.) | Present, **Phase 1 complete** (`datasets/English/`; 259 `established/` files) — driven by the sibling `TepenianHawaiian` project's need for English as a required structural donor (English/Japanese/Tagalog pidgin origin), this closes out all three required-core languages. Covers the Chicago Manual of Style (incl. Garner's Grammar and Usage chapter), New Oxford Style Manual (incl. the flagship US/British contrast chapter), the full original ESL collection, and the full Old English pack. First `/graphify` run complete: 3,517 nodes, 4,187 edges, 252 communities. One source (`Comprehensive Grammar[A4].pdf`) turned out to be a misfiled Chinese grammar and was excluded. | 🔴 **HIGH PRIORITY — tenth language to reach full Phase 1 completion** — five separate nations; expect real dialectal slang divergence (American/British/Canadian/Australian/NZ) worth tracking per-nation once corpus work begins |
| **German** | Germany (~46M eff.), Belgium (partial, ~6.4M eff., trilingual) | **Not present — gap.** No German-language reference material found in `source_reference/languages/`. | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Dutch** | Netherlands (~10M eff.), Belgium (partial, trilingual) | Present, **Phase 1 complete** (`Dutch`; ~813,000 words across 167 `established/` files; see `datasets/Dutch/`) | 🔴 **HIGH PRIORITY — sixth-furthest along of any GINI language** |
| **Swedish** | Sweden (~6M eff.) | Present (`Swedish`; +3.1G/126-file external-drive stash found 2026-10-26, untriaged — 5x the existing 620M corpus) | 🔴 **HIGH PRIORITY** |
| **Norwegian** | Norway (~3.3M eff.) | **Not yet in `source_reference/`** — but a 3.0G/109-file stash was found on the external drive 2026-10-26 (`w-lang/Norwegian/`); not staged or triaged. | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| Danish | — | Present (`Danish`; +855M/39-file external-drive stash found 2026-10-26, untriaged) | cataloged, not GINI-tagged |
| Icelandic | — | Present (`Icelandic`, `Icelandic-Faroese`; +795M/48-file external-drive stash found 2026-10-26, untriaged) | cataloged, not GINI-tagged |
| Old English | — (historical stage, not a living GINI nation) | Present (`Old English Language Learning Pack`) | cataloged, not GINI-tagged |

### Romance branch

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **French** | France (~35M eff.), Canada (partial), Belgium (partial, trilingual) | Present (`French Learning Books`) | 🔴 **HIGH PRIORITY** |
| **Italian** | Italy (~27M eff.) | Present (`Italian`) | 🔴 **HIGH PRIORITY** |
| **Spanish** | Spain (~20M eff.), Mexico (~18M eff.), Argentina (~6M eff.), Chile (~2.3M eff.), Uruguay (~0.6M eff.) | Present, **Phase 1 complete, full external-drive stash extraction finished 2026-10-30** (`Spanish`; ~1.36M words across 175 `established/` files; see `datasets/Spanish/`). The 16GB external-drive stash triaged 2026-10-25 (~123 net-new files) was fully extracted across 5 waves (S1 + 2-5), nearly tripling the corpus. Own `graphify-out/` fully rebuilt: 2,326 nodes, 2,596 edges, 255 communities. | 🔴 **HIGH PRIORITY — Phase 1 now complete across all 5 nations** — strong candidate for per-nation slang subdivision (Iberian vs. Mexican vs. Rioplatense vs. Chilean Spanish are famously divergent registers, confirmed repeatedly during extraction — e.g. *coger*/*concha*/*vosotros* regional splits) |
| **Portuguese** | Brazil (~17M eff.) | **Not yet in `source_reference/`** — but a 3.5G/167-file stash was found on the external drive 2026-10-26 (`w-lang/Portuguese/`); not staged or triaged. | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| **Romanian** | Romania (~4.5M eff.) | Present, **Phase 1 complete** (`Romanian`; ~251,000 words across 78 `established/` files, from the smallest corpus triaged yet; see `datasets/Romanian/`; `Romanian collection.zip.gz` — likely redundant, flagged in `language_corpus/00_Corpus_Collection_Index.md`) | 🔴 **HIGH PRIORITY — seventh-furthest along of any GINI language** |
| Catalan | — | **Not in `source_reference/`.** A 955M/41-file stash was found on the external drive 2026-10-26; not staged or triaged. | cataloged, not GINI-tagged |

### Slavic branch

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Russian** | Russia (~25M eff., or absent at some cities per the Davis/Zhongshan tier-inconsistency flagged above) | Present, **Phase 1 complete — largest corpus in the project** (`Russian`; ~1,360,000 words across 281 `established/` files, from a 204-file/3.6GB source corpus; see `datasets/Russian/`) | 🔴 **HIGH PRIORITY — fourth-furthest along of any GINI language** |
| **Polish** | Poland (~12M eff.; also political center of the Intermarium/Intermaria meta-nation bloc) | **Not yet in `source_reference/`** — but a combined 13G/1,015-file "Polish and Ukrainian" stash was found on the external drive 2026-10-26, not yet split by language, staged, or triaged. | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| **Czech** | Czech Republic (~5M eff.; among the highest per-capita robot-access rates of any nation per the source doc) | **Not present — gap.** Confirmed still absent from the external drive in the 2026-10-26 sweep too. | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Ukrainian** | Ukraine (~5M eff.) | **Not yet in `source_reference/`** — covered by the same combined "Polish and Ukrainian" external-drive stash noted above (13G/1,015 files, unsplit, untriaged). | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| **Serbian/Croatian/Bosnian** | Serbia (~1.2M eff.), Croatia (~1.3M eff.) | Present, **Phase 1 complete** (`Serbian, Croatian, Bosnian`; see `datasets/Serbian_Croatian_Bosnian/`). An undocumented 2.1G/82-file external-drive stash — 8x the extracted 264M corpus — was found 2026-10-26; not yet triaged. | 🔴 **HIGH PRIORITY — furthest along of any GINI language** |
| **Bulgarian** | Bulgaria (~1.2M eff.) | **Not yet in `source_reference/`** — but a 1.6G/53-file stash was found on the external drive 2026-10-26; not staged or triaged. | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| **Slovak** | Slovakia (~2.2M eff.) | **Not present — gap.** Confirmed still absent from the external drive in the 2026-10-26 sweep too. | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Belarusian** | Belarus (~1.5M eff.) | **Not present — gap.** Confirmed still absent from the external drive in the 2026-10-26 sweep too. | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Slovenian** | Slovenia (~1M eff.; "excellent rate, tiny population" per source) | Present (`Slovene (Slovenian Language) Learning Pack`). A same-size (1.1G/29-file) but **different edition** was found on the external drive 2026-10-26 — spot-checked by filename, it is not a duplicate; untriaged. | 🔴 **HIGH PRIORITY** |

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
| Irish | Present (`Irish`; +1.4G/45-file external-drive stash found 2026-10-26 under the name "Irish Gaelic (Gaeilge)", untriaged — 7x the existing 187M corpus) | cataloged, not GINI-tagged |

### Indo-Aryan branch (cataloged, not GINI-tagged — found externally only, 2026-10-26)

| Language | `source_reference/` status | Priority |
|---|---|---|
| Hindi-Urdu | **Not in `source_reference/`.** A 2.1G/76-file stash was found on the external drive 2026-10-26; not staged, triaged, or otherwise part of the project roster before now. | cataloged, not GINI-tagged |
| Nepali | **Not in `source_reference/`.** A 174M/20-file stash was found on the external drive 2026-10-26; not staged or triaged. | cataloged, not GINI-tagged |

---

## Uralic

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Finnish** | Finland (~3.3M eff.) | Present (`Finnish`) | 🔴 **HIGH PRIORITY** |
| **Estonian** | Estonia (~0.6M eff.; "highest effective conversion rate of any Intermarium member" per source) | Present (`Estonian`, ~1.3 GB) | 🔴 **HIGH PRIORITY** |
| **Hungarian** | Hungary (~3M eff.; core Intermarium member) | Present, **Phase 1 complete** (`Hungarian`; see `datasets/Hungarian/`). An undocumented 1.3G/68-file external-drive stash was found 2026-10-26; not yet triaged against the existing 2.6G/53-`established/`-file corpus. | 🔴 **HIGH PRIORITY — second-furthest along of any GINI language** |

---

## Japonic

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Japanese** | Japan (~65M eff.) | Present (`Japanese`) | 🔴 **HIGH PRIORITY** |

## Koreanic

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Korean** | South Korea (~26M eff.) | **Phase 1 complete, including the external-drive stash** (`Korean`; see `datasets/Korean/`). The 3.0G/109-file external-drive stash triaged 2026-10-19 was fully extracted 2026-10-29 across 6 dispatch waves (K1-K6): 69 `established/` files total, ~1,217,000 words (flagship finds: *Dirty Korean Everyday Slang*, *Making Out in Korean*, a North-Korean-dialect source with the 두음법칙 flagship contrast, a 1984 US-military-register DLI course). No known expansion pending. | ✅ **Phase 1 complete — no longer the open item** |

## Sino-Tibetan

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Mandarin** | China (~210M eff. — the largest effective pool of any nation in the census, noted for context only, not priority) | Present (`Mandarin`) | 🔴 **HIGH PRIORITY** |
| Cantonese | — (China's census entry maps to Mandarin as the national standard; Cantonese not separately broken out by the source doc) | Present, **triaged 2026-10-26** (`datasets/Cantonese/00_Book_Triage_Catalog.md`) combining the in-repo copy with the external-drive stash. The in-repo PDF is MD5-identical to the external drive's 1994 *Colloquial Cantonese* edition; a cleaner 2010 edition with a real text layer supersedes it. Only 4 of 15 in-scope titles have a text layer (~27%, the lowest of any language triaged so far) — this will be vision-reading-dominated. Flagship finds confirmed: *Cantonese: A Comprehensive Grammar* and *A Dictionary of Cantonese Slang*, both specifically wanted by the sibling `TepenianHawaiian` project as a reinforcement reference (D-13) even though Cantonese isn't a structural source for Modern Hawaiian. Not yet staged or extracted. | cataloged, not separately GINI-tagged — worth revisiting if the setting ever distinguishes a Cantonese-speaking sub-community from Mandarin-speaking China at a specific city |
| Tibetan | — | Present (`Tibetan`; +1.2G/40-file external-drive stash found 2026-10-26, untriaged) | cataloged, not GINI-tagged |

## Austronesian — one gap remains after the 2026-10-26 external-drive sweep

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Indonesian** | Indonesia (~16M eff.) | **Not yet in `source_reference/`** — but a combined 1.8G/60-file "Malay-Indonesian" stash was found on the external drive 2026-10-26, not yet split by language, staged, or triaged. | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| **Malay** | Malaysia (~5M eff.) | **Not yet in `source_reference/`** — covered by the same combined "Malay-Indonesian" external-drive stash noted above (unsplit, untriaged). | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| **Filipino/Tagalog** | Philippines (~5M eff.; "massive population base (110M) saves the effective number despite severe inequality" per source) | Present (`Tagalog`) — Phase 1 complete, 2026-10-19 | 🔴 **HIGH PRIORITY** — acquisition gap closed |
| Ilocano | — (not separately broken out in the GINI census; spoken by a large share of the real Philippine population alongside Tagalog) | **Phase 1 complete 2026-10-30** (`datasets/Ilocano/`) — two staged sources: Rubino's 1997 UCSB dissertation *A Reference Grammar of Ilocano* (549pp, no text layer, extracted in full across all 18 chapters) and Rubino's 2000 UH Press *Ilocano Dictionary and Grammar* (868pp; Grammar Outline extracted in full, Ilocano-English/English-Ilocano dictionary body representatively sampled). `established/` has 19 files, ~275,700 words. Own `graphify-out/` (first ever for this language). Flagship finds: the *maki-* comitative verb cluster (seven sub-derivations, no counterpart yet found in this project's Tagalog material); reduplication multiplexing five distinct grammatical jobs; fused ergative×absolutive pronoun portmanteaus; dual native/Spanish numeral system with borrowed Spanish gender agreement; explicit Hawaii-contact data (Ch.1's "one-fifth of Hawaii's population is Ilocano-descended" statement, dictionary entries *Aloha*/*Haway*/*kanaka*). A duplicate third scan (no text layer) was deliberately not extracted. See `datasets/Ilocano/00_Extraction_Checklist.md` and `00_RESUME_HERE.md` (incl. a full seam-boundary audit that caught and patched 8 one-page content gaps from an initial page-offset miscalculation). | foundation vocabulary for the sibling `TepenianHawaiian` project's Modern/Middle Hawaiian synthesis (D-12) — not GINI-tagged, acquisition gap now closed |
| **Hawaiian (ʻŌlelo Hawaiʻi)** | — (not a GINI census nation; real Hawaiʻi isn't an Inner Tepenia GDD nation) | **Phase 1 complete 2026-10-30** (`datasets/Hawaiian/`) — the user sourced Pukui & Elbert's *Hawaiian Dictionary* (Rev. & Enl. Ed. 1986, 3,695pp, clean text layer) and *Hawaiian Grammar* (1979/2001, 214pp, vision-read), closing a long-open acquisition gap. Grammar extracted in full (4 files); Dictionary representatively sampled (6 files, ~3,695pp is by far the largest dictionary this project has processed) plus front matter. `established/` has 11 files, ~96,000 words. Own `graphify-out/` (first ever for this language): 232 nodes, 271 edges, 31 communities, zero health-check issues. Flagship finds: the *kake* chiefly cryptolect; the dictionary's own canonical 11-item slang list, cross-confirmed by independent re-tags; named island/district insult epithets; the a/o possessive-class system with a real cross-chapter syntactic override. Appendix A/B (gods/demigods glossary, given names) confirmed genuinely absent from this digitized edition despite being listed in its own TOC. | foundation vocabulary for the sibling `TepenianHawaiian` project's Modern/Middle Hawaiian synthesis — not GINI-tagged, acquisition gap now closed |

## Kra-Dai — no longer a true gap after the 2026-10-26 external-drive sweep

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Thai** | Thailand (~8M eff.) | **Not yet in `source_reference/`** — but a combined 4.4G/103-file "Thai and Lao" stash was found on the external drive 2026-10-26; not staged or triaged. | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| Lao | — (not a GINI nation language) | Covered by the same combined "Thai and Lao" external stash above. | cataloged, not GINI-tagged |

## Austroasiatic — Vietnamese no longer a true gap; Khmer newly found

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Vietnamese** | Vietnam (~5M eff.) | **Not yet in `source_reference/`** — but a 1.3G/53-file stash was found on the external drive 2026-10-26; not staged or triaged. | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| Cambodian (Khmer) | — (not a GINI nation language) | **Not in `source_reference/`.** A 274M/25-file stash was found on the external drive 2026-10-26; not staged or triaged. | cataloged, not GINI-tagged |

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
| Arabic | **Not in `source_reference/`.** A 4.6G/189-file stash — the single largest newly-found language — was found on the external drive 2026-10-26; not staged or triaged. |

## Turkic (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Turkish | Present (`Turkish Language Learning Pack`) |
| Kazakh | Present (`Kazakh Language Learning Pack`, `Colloquial Kazakh`; +454M/40-file external-drive stash found 2026-10-26, untriaged) |

## Mongolic (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Mongolian | Present (`Mongolian`, `An Elementary Mongolian Grammar`, plus two historical/literary works — `Ocean of Milk, Ocean of Blood`, `Secret History of the Mongols` — that likely belong filed under this language, not as stray top-level files). +1.2G/44-file external-drive stash found 2026-10-26, untriaged. |

## Niger-Congo / other African (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Swahili | Present (`Swahili`) — but the in-repo folder is only 684K. A +381M/33-file external-drive stash found 2026-10-26 would be this language's first real corpus if triaged. |

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
| Basque (Euskara) | **Not in `source_reference/`.** A 58M/6-file stash was found on the external drive 2026-10-26; not staged or triaged. |

## Constructed (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Esperanto | Present (`Esperanto`) |

---

## External-drive sweep, 2026-10-26

**What happened:** a full inventory of the external drive at `/media/kuroskalacs/Home-Theater/
w-lang/` (27 top-level language folders, ~70GB total) turned up material for nearly every language
this file had marked as a pure acquisition gap, plus undocumented supplementary stashes for several
already-extracted or already-present languages, plus 6 languages never before in the project's
roster at all. Before this sweep, only Korean, Spanish, and Tagalog had documented triage notes
referencing this drive. **Finding material on the drive is not the same as staging or triaging
it** — every item below still needs the same Phase 0 triage pass (dedup check, metalanguage check,
text-layer check) before any extraction work can start. This file now distinguishes **"external
copy found, not staged"** from a true **"acquisition gap"** (zero material anywhere) — only the
latter still needs real ebook acquisition.

**Net effect on the acquisition-gap list:** of the original 14 zero-material languages, **9 are no
longer true gaps** — Portuguese, Norwegian, Polish, Ukrainian, Bulgarian, Indonesian, Malay, Thai,
and Vietnamese all have real stashes sitting on the drive (several combined across two languages in
one folder: "Polish and Ukrainian" 13G/1,015 files, "Malay-Indonesian" 1.8G/60 files, "Thai and Lao"
4.4G/103 files). Only **German, Czech, Slovak, and Belarusian** remain genuine acquisition gaps with
zero material found anywhere, plus the still-unresolved South Africa language-assignment question.

**Already-tracked languages with newly-found, undocumented supplementary stashes** (none yet
triaged against what's already in `source_reference/`, except Korean — see below): Serbian/
Croatian/Bosnian (2.1G/82 files — 8x the extracted 264M corpus), Hungarian (1.3G/68 files),
**Korean (3.0G/109 files — triaged 2026-10-19, fully extracted 2026-10-29 across Waves K1-K6; no
longer an open item)**, Spanish (16G, triaged 2026-10-25, extraction not dispatched), Swedish
(3.1G/126 files), Slovenian (1.1G/29 files, a different edition, not a duplicate), Cantonese,
Danish, Icelandic, Kazakh, Mongolian, Tibetan, Irish, and Swahili (whose 381M/33-file external
stash would be its *first* real corpus — the in-repo folder is only 684K).

**Six languages never before in this project's roster**, found only on the external drive: Arabic
(4.6G/189 files — the single largest), Hindi-Urdu (2.1G/76 files), Catalan (955M/41 files), Nepali
(174M/20 files), Cambodian/Khmer (274M/25 files), and Basque (58M/6 files). None map to a GINI
census nation currently.

## Summary: acquisition gaps among the 43 high-priority nations

**See `LANGUAGE_ACQUISITION_TODO.md`** for the languages still worth shopping for — though it should
be re-checked against the sweep above, since most of its former list now has a real external copy.

**Only 4 GINI-priority languages still have zero material found anywhere** and need real ebook
acquisition before their Phase 1 can even begin: German (Germany, Belgium's German-speaking
component), Czech (Czech Republic), Slovak (Slovakia), Belarusian (Belarus) — plus the unresolved
South Africa language-assignment question, uncounted since no single language has been identified
for it yet.

**9 more GINI-priority languages have a real external-drive copy, not yet staged or triaged**:
Portuguese, Norwegian, Polish, Ukrainian, Bulgarian, Indonesian, Malay, Thai, Vietnamese — see the
sweep section above for sizes.

**27 of the 43 nations already have usable `source_reference/` material** (18 distinct languages,
several covering multiple nations) and could start Phase 1 immediately once prioritized: English (USA, UK,
Canada, Australia, New Zealand — 5 nations), Dutch (Netherlands; also partially covers Belgium),
Swedish, French (France; also partially covers Canada and Belgium), Italian, Spanish (Spain,
Mexico, Argentina, Chile, Uruguay — 5 nations), Romanian, Russian, Serbian/Croatian/Bosnian (Serbia,
Croatia — 2 nations), Slovenian, Lithuanian, Latvian, Finnish, Estonian, Hungarian, Japanese,
Korean, Mandarin.

**Ten languages have already reached full Phase 1 completion** (in completion order): Serbian/
Croatian/Bosnian, Hungarian, Korean, Russian (by far the largest corpus of the ten), Spanish,
Dutch, Romanian (the smallest of the ten), Japanese, Tagalog, and English (2026-10-27/29) — see
`datasets/00_Analysis_Index.md` for current status of every language in progress. **Spanish is
still expanding**: it has a real external-drive stash that's triaged but not yet extracted, so its
"complete" describes its original corpus only, not its full available material. **Korean's known
external-drive stash was fully extracted 2026-10-29** (6 dispatch waves, K1-K6 — see
`datasets/Korean/00_RESUME_HERE.md` for the full account) — its "Expanding" tag has been dropped;
no known expansion pending for Korean specifically. English's own two foremost sources (Chicago
Manual of Style, New Oxford Style Manual) were extracted in full; the original ESL collection and
Old English pack are also fully done — no known expansion pending for English specifically.

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
