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
| **German** | Germany (~46M eff.), Belgium (partial, ~6.4M eff., trilingual) | **Not in `source_reference/`**, but **triaged 2026-11-01** (`datasets/German/00_Book_Triage_Catalog.md`) directly from the external drive (`w-lang/German/`, 8.3G/222 files harvested as 164 after dedup/exclusion). 164 harvested → 6 excluded (wrong metalanguage/audience), 25 non-content assets, 3 unopened archives, ~50 bulk-corpus magazine issues set aside, leaving **≈133 real Phase 1 candidates** (51 TEXT/82 vision — the most vision-dependent stash in the project at 62%). 5 priority tiers assigned; flagship slang title *Dirty German Everyday Slang* identified (Tier 2). **Not yet staged for extraction** — the user has not authorized extraction. | 🔴 **HIGH PRIORITY — triaged, extraction not yet authorized** |
| **Dutch** | Netherlands (~10M eff.), Belgium (partial, trilingual) | Present, **Phase 1 complete** (`Dutch`; ~813,000 words across 167 `established/` files; see `datasets/Dutch/`) | 🔴 **HIGH PRIORITY — sixth-furthest along of any GINI language** |
| **Swedish** | Sweden (~6M eff.) | **Phase 1 complete for the clearly-in-scope pool, 2026-11-04** (`datasets/Swedish/`; 44 `established/` files, ~335,000 words), extracted overnight at the user's explicit direction. The triage catalog's §5 pile of 37 Swedish-medium-of-Swedish files (incl. the flagship slang dictionary *Svenska idiom*) remains deliberately un-extracted pending the user's ruling. Own `graphify-out/`: 481 nodes, 111 communities, clean health check. | 🔴 **HIGH PRIORITY — 14th language to reach Phase 1** |
| **Norwegian** | Norway (~3.3M eff.) | **Phase 1 complete for the clearly-in-scope pool, 2026-11-04** (`datasets/Norwegian/`; 36 `established/` files, ~370,700 words), extracted overnight at the user's explicit direction. The triage catalog's §5 pile of 41 Norwegian/German/Portuguese-medium files — the highest-stakes flagged pile of any Scandinavian-family language, gating all 3 flagship slang/idiom dictionaries AND every Nynorsk-standard source in the corpus — remains deliberately un-extracted pending the user's ruling. A 10-file Faroese-misfiled-as-Norwegian contamination was caught and excluded at triage. Own `graphify-out/`: 313 nodes, 20 communities, clean health check. | 🔴 **HIGH PRIORITY — 15th language to reach Phase 1** |
| Danish | — | **Phase 1 complete for the clearly-in-scope pool, 2026-11-04** (`datasets/Danish/`; 9 `established/` files, ~150,600 words), extracted overnight at the user's explicit direction — the smallest and cleanest of the three Scandinavian languages extracted this session. The triage catalog's §5 pile of 16 Danish-medium-of-Danish files remains deliberately un-extracted pending the user's ruling; unlike Swedish/Norwegian it contains no flagship slang/idiom candidate at all. Own `graphify-out/`: 158 nodes, 120 communities, a perfectly clean health check (zero issues of any kind) — the cleanest graphify rebuild of any language in this project to date. | cataloged, not GINI-tagged — 16th language to reach Phase 1 |
| Icelandic | — | Present (`Icelandic`, `Icelandic-Faroese`; +795M/48-file external-drive stash found 2026-10-26, untriaged) | cataloged, not GINI-tagged |
| Old English | — (historical stage, not a living GINI nation) | Present (`Old English Language Learning Pack`) | cataloged, not GINI-tagged |

### Romance branch

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **French** | France (~35M eff.), Canada (partial), Belgium (partial, trilingual) | Present (`French Learning Books`) | 🔴 **HIGH PRIORITY** |
| **Italian** | Italy (~27M eff.) | Present (`Italian`) | 🔴 **HIGH PRIORITY** |
| **Spanish** | Spain (~20M eff.), Mexico (~18M eff.), Argentina (~6M eff.), Chile (~2.3M eff.), Uruguay (~0.6M eff.) | Present, **Phase 1 complete, full external-drive stash extraction finished 2026-10-30** (`Spanish`; ~1.36M words across 175 `established/` files; see `datasets/Spanish/`). The 16GB external-drive stash triaged 2026-10-25 (~123 net-new files) was fully extracted across 5 waves (S1 + 2-5), nearly tripling the corpus. Own `graphify-out/` fully rebuilt: 2,326 nodes, 2,596 edges, 255 communities. | 🔴 **HIGH PRIORITY — Phase 1 now complete across all 5 nations** — strong candidate for per-nation slang subdivision (Iberian vs. Mexican vs. Rioplatense vs. Chilean Spanish are famously divergent registers, confirmed repeatedly during extraction — e.g. *coger*/*concha*/*vosotros* regional splits) |
| **Portuguese** | Brazil (~17M eff.) | **Triaged 2026-11-03** (`datasets/Portuguese/00_Book_Triage_Catalog.md`), from the external drive, 167 files pre-split by the collector into `Brazilian Portuguese/` (73) and `European Portuguese/` (94). 46 files flagged for a ruling (Portuguese-medium-of-itself) — the largest such pile of any language in this batch; 45 clearly in scope, 50/50 text/vision. Flagship slang found (*Dirty Portuguese: Everyday Slang*, Brazilian-specific) — no European-Portuguese equivalent exists. A dedicated regional-variation review (pan-Portuguese vs. European-specific vs. Brazilian-specific features) is in the catalog's §7, per the user's explicit request; best lead is *Using Portuguese: A Guide to Contemporary Usage*, which already covers and differentiates both varieties throughout. Not staged for extraction. | 🔴 **HIGH PRIORITY — triaged, extraction not yet authorized** |
| **Romanian** | Romania (~4.5M eff.) | Present, **Phase 1 complete** (`Romanian`; ~251,000 words across 78 `established/` files, from the smallest corpus triaged yet; see `datasets/Romanian/`; `Romanian collection.zip.gz` — likely redundant, flagged in `language_corpus/00_Corpus_Collection_Index.md`) | 🔴 **HIGH PRIORITY — seventh-furthest along of any GINI language** |
| Catalan | — | **Not in `source_reference/`.** A 955M/41-file stash was found on the external drive 2026-10-26; not staged or triaged. | cataloged, not GINI-tagged |

### Slavic branch

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Russian** | Russia (~25M eff., or absent at some cities per the Davis/Zhongshan tier-inconsistency flagged above) | Present, **Phase 1 complete — largest corpus in the project** (`Russian`; ~1,360,000 words across 281 `established/` files, from a 204-file/3.6GB source corpus; see `datasets/Russian/`) | 🔴 **HIGH PRIORITY — fourth-furthest along of any GINI language** |
| **Polish** | Poland (~12M eff.; also political center of the Intermarium/Intermaria meta-nation bloc) | **Triaged 2026-11-03** (`datasets/Polish/00_Book_Triage_Catalog.md`), from the 13G/1,015-file combined "Polish and Ukrainian" external-drive stash — the largest single triage in this project to date (282 of the 1,015 files are Polish-relevant; Ukrainian/Belarusian were set aside, see their own entries). Caught a major contamination finding: an 87-file subfolder labeled as Polish reading material is actually **Czech** (a mislabeled series, excluded). ~95 files clearly in scope (strongest category: English-medium reference grammars); ~24 flagged for a ruling (Polish-medium-of-itself); ~20 titles are translated copyrighted fiction (Harry Potter, LOTR, etc., flagged as a scope decision, not reference material). Flagship slang found: a youth-slang glossary chapter inside an intermediate course (*Kto Czyta - Nie Bladzi*), Polish-medium. Not staged for extraction. | 🔴 **HIGH PRIORITY — triaged, extraction not yet authorized** |
| **Czech** | Czech Republic (~5M eff.; among the highest per-capita robot-access rates of any nation per the source doc) | **Not present — gap.** Confirmed still absent from the external drive in the 2026-10-26 sweep too. | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Ukrainian** | Ukraine (~5M eff.) | **Not yet in `source_reference/`** — covered by the same combined "Polish and Ukrainian" external-drive stash noted above. Counted (263 files, ~2.77GB across two subfolders) but deliberately **not triaged as a target**, per the sibling `TepenianLanguage` handoff's explicit instruction — Ukrainian isn't on that project's stage-2 roster. See `datasets/Polish/00_Book_Triage_Catalog.md` §6 for the count. | 🔴 **HIGH PRIORITY — external copy found, counted only, not triaged** |
| **Serbian/Croatian/Bosnian** | Serbia (~1.2M eff.), Croatia (~1.3M eff.) | Present, **Phase 1 complete** (`Serbian, Croatian, Bosnian`; see `datasets/Serbian_Croatian_Bosnian/`). An undocumented 2.1G/82-file external-drive stash — 8x the extracted 264M corpus — was found 2026-10-26; not yet triaged. | 🔴 **HIGH PRIORITY — furthest along of any GINI language** |
| **Bulgarian** | Bulgaria (~1.2M eff.) | **Not yet in `source_reference/`** — but a 1.6G/53-file stash was found on the external drive 2026-10-26; not staged or triaged. | 🔴 **HIGH PRIORITY — external copy found, not staged** |
| **Slovak** | Slovakia (~2.2M eff.) | **Not present — gap.** Confirmed still absent from the external drive in the 2026-10-26 sweep too. | 🔴 **HIGH PRIORITY, ACQUISITION GAP** |
| **Belarusian** | Belarus (~1.5M eff.) | **Narrowed from zero to thin, 2026-11-03.** Found unprompted sitting inside the external drive's combined "Polish and Ukrainian" folder (`Vol.2/03 Belarusian/`, not on anyone's original list) and triaged (`datasets/Belarusian/00_Book_Triage_Catalog.md`). 12 raw files → 11 unique → only **2 real English-medium candidates** (*Fundamental Byelorussian* Books 1-2, a diaspora-published bilingual course, 782pp vision-only; *Fundamentals of Modern Belarusian*, 110pp, text-layer). No slang/idiom title, no frequency list, no graded readers — Tiers 2/3/5 are all empty. 5 more files excluded (Russian/German/French-medium or non-English dictionary); 1 Belarusian-medium-of-itself textbook flagged for a ruling. **Not a full gap anymore, but still the thinnest corpus of any language in this project if extracted as-is.** | 🔴 **HIGH PRIORITY — thin material found, not staged** |
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
| Persian | Present (`Persian`, 2.2G/483 files in-repo) — **a second, undocumented 393M/15-file external-drive stash was found 2026-11-03** (added to the drive 2026-11-01, same batch as the German/Tajik/Arabic finds below), not staged or triaged against the in-repo corpus. Distinct titles: *Living Language Farsi*, two editions of *Teach Yourself Modern Persian* (1973/2004), *Colloquial Persian*, the *Lonely Planet Farsi Phrasebook*, a Defence Language Institute reader, and *Beginner's Dari Persian* (a related but distinct Persian variety, not yet otherwise in this roster) | cataloged, not GINI-tagged |
| Tajik | **Newly found, external drive only, 2026-11-03** (`w-lang/Tajik/`, 81M/6 files, added to the drive 2026-11-01) — never before in this project's roster. Six titles: *A Beginner's Guide To Tajiki*, *Tajik Persian Reference Grammar*, *Tajiki Reference Grammar for Beginners*, *Languages of the World - Tajik*, plus two editions (1989/1993) of a Russian-medium *Samouchitel Tadzhikskogo Yazyka* self-teacher. Not staged or triaged. Not a GINI census language. | cataloged, not GINI-tagged |
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
| Cantonese | — (China's census entry maps to Mandarin as the national standard; Cantonese not separately broken out by the source doc) | Present, **Phase 1 complete 2026-11-03** (`datasets/Cantonese/`; ~323,000 words across 60 `established/` files, incl. lettered sub-parts). Triaged 2026-10-26 combining the in-repo copy with the external-drive stash; Wave 1 ran in an earlier session, Waves 2-5 ran back-to-back in a single session at the user's explicit direction. Flagship sources *Cantonese: A Comprehensive Grammar* and *A Dictionary of Cantonese Slang* both specifically wanted by the sibling `TepenianHawaiian` project as a reinforcement reference (D-13) even though Cantonese isn't a structural source for Modern Hawaiian. Own `graphify-out/` (first ever for this language): 1,110 nodes, 1,168 edges, 142 communities, zero health-check issues — the cleanest of any language graphify rebuild in this project to date. | cataloged, not separately GINI-tagged — worth revisiting if the setting ever distinguishes a Cantonese-speaking sub-community from Mandarin-speaking China at a specific city |
| Tibetan | — | Present (`Tibetan`; +1.2G/40-file external-drive stash found 2026-10-26, untriaged) | cataloged, not GINI-tagged |

## Austronesian — one gap remains after the 2026-10-26 external-drive sweep

| Language | Nations | `source_reference/` status | Priority |
|---|---|---|---|
| **Indonesian** | Indonesia (~16M eff.) | **Triaged 2026-11-03** (`datasets/Malay_Indonesian/00_Book_Triage_Catalog.md`), from the combined 1.8G/60-file external-drive stash — split per-title by language, not just by folder. 43 of 60 files tagged Indonesian (+4 tagged Both). Flagship slang found: 3 strong candidates (*Informal Indonesian*, *Indonesian Idioms and Expressions*, *Colloquial Jakartan Indonesian*). A mislabeled title caught by rendering: "Modern Indonesian Literary Reader" is actually German-medium. Also found a 31-file in-repo audio-companion stash sitting under a generically-named folder. Not staged for extraction. | 🔴 **HIGH PRIORITY — triaged, extraction not yet authorized** |
| **Malay** | Malaysia (~5M eff.) | **Triaged 2026-11-03** (same pass/catalog as Indonesian above, `datasets/Malay_Indonesian/`). Only 11 of 60 files tagged Malay. **No dedicated slang, idiom, or dictionary title exists for Malay anywhere in this harvest** — a real, flagged gap, in stark contrast to Indonesian's three flagship slang candidates. Not staged for extraction. | 🔴 **HIGH PRIORITY — triaged, extraction not yet authorized** |
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
| Arabic | **Not in `source_reference/`.** A 4.6G/189-file stash — the single largest newly-found language — was found on the external drive 2026-10-26; not staged or triaged. **Grew substantially 2026-11-01 (confirmed on re-scan 2026-11-03): now 8.1G/217 files.** The collector restructured it with dialect-specific subfolders not implied by the original flat count — `07 Egyptian Arabic`, `08 Levantine and Iraqi Arabic`, `09 Arabic of the Arabian Peninsula`, `10 Maghrebi Arabic` — plus a graded-readers folder (incl. an Arabic translation of *Harry Potter and the Philosopher's Stone*) and a `11 Society, Culture, Tourism` folder. Still not staged or triaged. |

## Turkic (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Turkish | Present (`Turkish Language Learning Pack`) |
| Kazakh | **Triaged 2026-11-03** (`datasets/Kazakh/00_Book_Triage_Catalog.md`), combining the external drive (40 files), two in-repo folders (36 files), and the `lang transfer bay` unsorted stash (6 files). 82 raw files → 49 unique (40% duplication) → 27 files (23 titles) in scope, 15 text/12 vision. Flagship slang found (*Colloquial Kazakh: The Complete Course for Beginners*). Caught a new wrong-language contamination case for this project: a Ukrainian-medium Kazakh folk-tale collection. Not staged for extraction. |

## Mongolic (cataloged, not GINI-tagged)

| Language | `source_reference/` status |
|---|---|
| Mongolian | **Triaged 2026-11-03** (`datasets/Mongolian/00_Book_Triage_Catalog.md`) — the widest-scope triage in this batch, combining the external drive (44 files), the 203-file in-repo folder, 3 loose standalone files, and 7 scholarly papers scattered in an unsorted stash. 258 raw files → 103 unique by md5 (60% duplication rate) → 67 in-scope Phase 1 candidates (34 text/32 vision/1 epub). No flagship slang title and no graded readers exist at all — both flagged gaps. A frequency dictionary was found (Russian-medium, reported not moved). 2 files need a ruling (Mongolian-medium-of-itself). Not staged for extraction. |

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
4.4G/103 files). At the time of this sweep, **German, Czech, Slovak, and Belarusian** were believed
to be genuine acquisition gaps with zero material found anywhere, plus the still-unresolved South
Africa language-assignment question. **German was later found and fully triaged 2026-11-01 — see
"New external-drive addition batch" below** — leaving only Czech, Slovak, and Belarusian as true
zero-material gaps.

**Already-tracked languages with newly-found, undocumented supplementary stashes** (none yet
triaged against what's already in `source_reference/`, except Korean — see below): Serbian/
Croatian/Bosnian (2.1G/82 files — 8x the extracted 264M corpus), Hungarian (1.3G/68 files),
**Korean (3.0G/109 files — triaged 2026-10-19, fully extracted 2026-10-29 across Waves K1-K6; no
longer an open item)**, Spanish (16G, triaged 2026-10-25, extraction not dispatched), Swedish
(3.1G/126 files), Slovenian (1.1G/29 files, a different edition, not a duplicate), Cantonese,
Danish, Icelandic, Kazakh, Mongolian, Tibetan, Irish, and Swahili (whose 381M/33-file external
stash would be its *first* real corpus — the in-repo folder is only 684K).

**Six languages never before in this project's roster**, found only on the external drive: Arabic
(4.6G/189 files at the time — see the 2026-11-01 growth note below), Hindi-Urdu (2.1G/76 files),
Catalan (955M/41 files), Nepali (174M/20 files), Cambodian/Khmer (274M/25 files), and Basque
(58M/6 files). None map to a GINI census nation currently.

## New external-drive addition batch, 2026-11-01 (found on re-scan 2026-11-03)

A re-scan of the external drive and `source_reference/languages/`, prompted directly by the user,
turned up a single dated batch added to the drive **2026-11-01** touching four languages at once:

- **German** — a real **8.3G/222-file corpus**, confirmed absent from `source_reference/` itself.
  **Already fully triaged 2026-11-01** (`datasets/German/00_Book_Triage_Catalog.md`, harvested down
  to 164 files, ≈133 real Phase 1 candidates across 5 priority tiers) — the triage simply hadn't
  been reflected back into this file until this re-scan caught the discrepancy. Flagship slang title
  *Dirty German Everyday Slang* identified (Tier 2). **Not yet staged for extraction** — extraction
  itself has not been authorized by the user. See the Germanic-branch table above for the full note.
- **Tajik** — brand new to the roster, external drive only, 81M/6 files, not staged or triaged. See
  the Indo-Iranian table above for titles.
- **Persian** — a second, undocumented 393M/15-file external-drive stash, separate from the
  existing 2.2G/483-file in-repo corpus, not staged or triaged. See the Indo-Iranian table above for
  titles.
- **Arabic** — the already-tracked 4.6G/189-file external stash grew to **8.1G/217 files**,
  restructured with dialect-specific subfolders (Egyptian, Levantine/Iraqi, Arabian Peninsula,
  Maghrebi) plus a graded-readers and a society/culture/tourism folder, not staged or triaged. See
  the Afroasiatic table below for detail.

A full re-scan of every other external-drive folder and every in-repo `source_reference/languages/`
folder on 2026-11-03 found no other drift — everything else still matches its previously documented
size/file-count/status.

## Later-stage Tepenian Language triage request, 2026-11-03

**Handoff received from the sibling `TepenianLanguage` repo, and now COMPLETE (2026-11-03)**
(`TepenianLanguage/handoffs_to_slang_synthesis/2026-11-03_later_stage_triage.md`) — triage only (no
extraction) requested for the "Stage 2" (Tepenian-era) candidate languages: Swedish, Norwegian,
Danish, Malay-Indonesian, Mongolian, Kazakh, **Portuguese** (newly added to that repo's Stage 2
roster 2026-11-03, on Brazil's documented presence near the Palmer Peninsula), and Polish. All
seven now have a `datasets/<Language>/00_Book_Triage_Catalog.md` — Polish's had already been done
by a separate parallel session before this queue reached it (confirmed by independent
cross-check, one genuine new finding reconciled in rather than duplicating the work). Ukrainian
material inside the Polish folder was catalogued at summary level only, not triaged as a target,
per the handoff. **A bonus eighth language was found and triaged along the way**: a dedicated
`Belarusian/` subfolder turned up unprompted inside the same external-drive Polish/Ukrainian pack —
see the Slavic-branch table above, it narrows (but doesn't fully close) Belarusian's standing
zero-material acquisition gap. Explicitly out of scope for this round: Italian and Australian slang
(developer will source more later), Russian and German (already triaged/extracted), Czech (no book
stash, only an already-filed frequency dictionary). No extraction has been authorized for any of
these eight languages — triage only.

## Summary: acquisition gaps among the 43 high-priority nations

**See `LANGUAGE_ACQUISITION_TODO.md`** for the languages still worth shopping for — though it should
be re-checked against the sweep above, since most of its former list now has a real external copy.

**Only 2 GINI-priority languages still have zero material found anywhere** and need real ebook
acquisition before their Phase 1 can even begin: Czech (Czech Republic), Slovak (Slovakia) — plus
the unresolved South Africa language-assignment question, uncounted since no single language has
been identified for it yet. **Belarusian (Belarus) is no longer a pure zero-material gap** — see
its Slavic-branch table entry above — though its corpus is thin (2 titles, no slang, no graded
readers) if extracted as-is. **German is no longer in this list either — it's triaged**, see "New
external-drive addition batch" above.

**Among the remaining GINI-priority languages with a real external-drive copy: Swedish and
Norwegian have reached full Phase 1 completion (2026-11-04, overnight extraction)**; **German,
Portuguese, Indonesian (Indonesia), and Malay (Malaysia) have been triaged** (Malay/Indonesian
together, see the Austronesian table below) but not yet extracted. **Bulgarian, Ukrainian, Thai,
and Vietnamese still have a real copy sitting untriaged.** Outside the GINI roster entirely, this
same 2026-11-03 triage pass also covered Danish, Mongolian, Kazakh, Polish, and Belarusian (none
GINI-tagged) — Danish has since also reached full Phase 1 completion alongside Swedish and
Norwegian; Mongolian, Kazakh, Polish, and Belarusian remain triaged-only — see their own
branch-table entries above for detail.

**27 of the 43 nations already have usable `source_reference/` material** (18 distinct languages,
several covering multiple nations) and could start Phase 1 immediately once prioritized: English (USA, UK,
Canada, Australia, New Zealand — 5 nations), Dutch (Netherlands; also partially covers Belgium),
Swedish, French (France; also partially covers Canada and Belgium), Italian, Spanish (Spain,
Mexico, Argentina, Chile, Uruguay — 5 nations), Romanian, Russian, Serbian/Croatian/Bosnian (Serbia,
Croatia — 2 nations), Slovenian, Lithuanian, Latvian, Finnish, Estonian, Hungarian, Japanese,
Korean, Mandarin.

**Sixteen languages have already reached full Phase 1 completion** (in completion order): Serbian/
Croatian/Bosnian, Hungarian, Korean, Russian (by far the largest corpus of the sixteen), Spanish,
Dutch, Romanian (the smallest of the original ten), Japanese, Tagalog, English (2026-10-27/29),
Hawaiian, Ilocano (both 2026-10-30, closing acquisition gaps for the sibling `TepenianHawaiian`
project), Cantonese (2026-11-03, all four remaining waves run back-to-back in a single session
at the user's explicit direction), and Swedish, Norwegian, Danish (2026-11-04, all three extracted
overnight in one unattended session per the user's explicit "continue through without me"
instruction — each with a standing-ruling-pending pile of medium-of-itself source material left
deliberately un-extracted) — see `datasets/00_Analysis_Index.md` for current status of every
language in progress. **Spanish is
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
