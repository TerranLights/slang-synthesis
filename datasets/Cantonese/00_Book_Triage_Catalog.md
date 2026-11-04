# Cantonese — Reference Material Triage Catalog

**Status: full triage complete, 2026-10-26.** Cantonese combines a single in-repo title with a much
larger stash found on the external drive at `/media/kuroskalacs/Home-Theater/w-lang/Cantonese/` (21
physical files / 19 numbered titles, ~430MB) — the same two-source pattern as Korean's triage.

**Project-relevance note.** Cantonese is explicitly *not* a structural contributor to the sibling
`TepenianHawaiian` project's constructed "Modern Hawaiian" language (excluded there as a source due
to writing-system/tonal mismatch with the language's other substrate languages), but it *is* wanted
as an "auxiliary reinforcement reference" — its grammar material and especially its slang dictionary
are worth having extracted here, just not as load-bearing as English/Japanese/Tagalog. That project
specifically named two titles from this stash as what it wants: `07.Cantonese A Comprehensive
Grammar` and `09.A Dictionary of Cantonese Slang` — both confirmed present and real (see Priority
Tier 1 below). Treat this language as a real but secondary priority overall.

**Tooling note.** Several external-drive files exist in two formats under the same number prefix
(`.djvu` + `.pdf` for the same edition) — always disambiguate by full filename, not just the numeric
prefix, when dispatching.

---

## Full file list — triaged

### In-repo: `source_reference/languages/Colloquial Cantonese The Complete Course for Beginners/`

| File | Pages | Text layer? | Status |
|---|---|---|---|
| `Colloquial Cantonese.pdf` | 130 | No (image-only scan) | **Confirmed MD5-identical duplicate** of external drive's `02.Colloquial Cantonese 1994.pdf` (md5 `510dfea2…` matches exactly). |
| `Colloquial Cantonese/Book/001.jpg`–`130.jpg` | 130 JPGs | N/A (raw page images) | Same page images already bundled inside the PDF above — redundant with it, not a distinct source. |

**Verdict:** the in-repo copy is not a separate acquisition — it's the same 1994 Colloquial Cantonese
edition already present (twice, in two formats) on the external drive. See the duplicate-resolution
note under Priority Tier 3 below: the external drive's `03.Colloquial Cantonese 2010.pdf` (a later,
clean-text edition) supersedes this 1994 edition as the primary Colloquial-series extraction target.

### External drive: `/media/kuroskalacs/Home-Theater/w-lang/Cantonese/` (21 files)

| File | Pages | Text layer? | Priority | Notes |
|---|---|---|---|---|
| `07.Cantonese A Comprehensive Grammar.djvu` | 226 (djvu page units; each unit is a **2-printed-page spread** — confirmed by direct render, so ~450 actual printed pages) | No (pure JB2 bilevel scan) | **Flagship — Highest** | Matthews & Yip, *Cantonese: A Comprehensive Grammar* — confirmed via rendered sample (detailed phonology/tone-sandhi chapter with real Cantonese examples). Named directly by the sibling TepenianHawaiian project. Use this djvu copy as primary (see pdf twin below). |
| `07.Cantonese A Comprehensive Grammar.pdf` | 114 | No (effectively zero real text: 114 chars across the whole 114-page file; one stray embedded font is negligible) | Flagship — **redundant duplicate, lower fidelity** | Same book as the djvu above, but confirmed via render to pack **4 printed pages per PDF page** (a 2×2 grid), vs. the djvu's 2-per-image. Treat the djvu as the dispatch source; keep this PDF only as a fallback if djvu rendering has issues. |
| `09.A Dictionary of Cantonese Slang.pdf` | 509 | No (image-only scan, 204MB) | **Flagship — Highest** | Hutton & Bolton, *A Dictionary of Cantonese Slang: The Language of Hong Kong Movies, Street Gangs and City Life* — confirmed via rendered sample pages: rich entries with Yale romanization + Chinese characters + English gloss + usage notes + cited real-world examples, explicitly covering obscene/vulgar/triad-argot registers (preface states the aim explicitly: accessible to "social workers, police officers, film censors" as well as academics/learners). Named directly by the sibling TepenianHawaiian project. **Content-type note:** per this project's Phase 1/Phase 2 boundary rule (a slang dictionary sitting physically in `source_reference/` still belongs conceptually in `language_corpus/Cantonese/`), this should be routed there at extraction time, same as Hungarian's *Magyar Szlengszótár* and Korean's *A Korean-English Dictionary* register-tagged entries. Needs representative A–Z sampling, not full transcription (509 pages, same discipline as other oversized dictionaries). |
| `04.Basic Cantonese A Grammar and Workbook.pdf` | 184 | **Yes** (clean, 250,658 chars) | **High** | Routledge *Basic Cantonese: A Grammar and Workbook* — same series format as Korean's Basic/Intermediate pair. First clean-text extraction target. |
| `03.Colloquial Cantonese 2010.pdf` | 305 | **Yes** (clean) | **High** | A later, distinct edition of the Colloquial Cantonese course (confirmed not a duplicate of the 1994 edition — different page count, different front matter). Clean text layer makes this the primary Colloquial-series target over the 1994 edition. |
| `06.Cantonese - Languages of the World.pdf` | 29 | No (image-only) | **High** | Siew-Yue Killingley, *Cantonese*, LINCOM EUROPA "Languages of the World/Materials" 06, 1993. Confirmed via rendered sample: real academic grammar sketch (nominal morphology, classifiers, tone system) despite its short length — compact but genuinely dense typological reference, comparable in kind to Korean's dedicated phonology/structure volumes. |
| `05.Intermediate Cantonese A Grammar and Workbook.pdf` | 217 | No (effectively zero: 217 stray chars across 217 pages, despite being the direct sequel to `04` which has a full clean text layer) | Medium-high | Routledge *Intermediate Cantonese: A Grammar and Workbook*. Confirmed via render to be genuine typeset content (Unit 3, "Changed tones," real grammar explanation) — just scanned/flattened to images rather than true text, unlike its Basic-level companion. Vision-read required. |
| `01.Teach Yourself Cantonese.pdf` | 346 | No (image-only, confirmed via `pdffonts` — zero embedded fonts) | Medium-high | Full Teach Yourself course. Confirmed via rendered sample (Unit 4, "Shortcuts" section on colloquial phrase-clipping, e.g. `gàm-yaht jiu-jóu` → `gàm-jiu`) — genuinely register/colloquialism-relevant content, not just drills. |
| `11.Gateway to Cantonese.djvu` | 304 | No (pure JB2 bilevel scan, djvutxt returns empty) | **EXCLUDED — wrong metalanguage** | Despite the English filename, this is **广州话入门** ("Introduction to Cantonese"/Guǎngzhōuhuà Rùmén), a Chinese-medium textbook by Chén Huìyīng & Mǎ Wényì (Beijing Language and Culture University Press) — confirmed via direct render of the title page. Parallel to the Korean/Cantonese "English-sounding filename, non-English-medium content" gotcha already documented in this project. Not an extraction target. |
| `13.Language Relations in Guangzhou.pdf` | 140 | **Yes** (clean) | Medium — sociolinguistic | Alexander Gamst Page, NTNU (Trondheim) Master's thesis in Social Anthropology, 2011: *Language Relations in Guangzhou: The Intimate and Official Dimension of Linguistic Codes in Urban China*. Confirmed real academic sociolinguistic content (register/code-choice, not tourism) — checked on content, not excluded on title alone, per this project's standing "academic sociolinguistic work can outrank title-based dismissal" convention (parallel to Korean's honorifics/politeness book). |
| `12.Hong Kong (Language and National Identity in Asia).pdf` | 18 | **Yes** (clean) | Medium — sociolinguistic | Andrew Simpson's "Hong Kong" chapter from the edited volume *Language and National Identity in Asia* (OUP). Confirmed real content: discusses Hong Kong's Cantonese/English/Mandarin triglossia, mixed-code register, and identity — directly relevant to register/slang mechanics despite being short. Short but dense; quick to extract regardless of final wave placement. |
| `08.Lonely Planet Cantonese Phrasebook.pdf` | 160 | No (image-only) | Medium-low | Standard travel phrasebook. Confirmed via rendered sample: genuine vocab/phrase tables (romanization + Chinese characters + English), no dedicated slang/colloquialism callout section spotted on the sampled pages (unlike Japanese's Rough Guide phrasebook) — worth a quick full skim during extraction to confirm absence, but default expectation is standard low-yield phrasebook content. |
| `00.Cantonese I Reading Booklet.pdf` | 38 (mostly blank/image) | No (effectively zero: 60 chars total across the whole file) | Low | Pimsleur "Cantonese I" audio-course Supplemental Reading Booklet (Recorded Books / Seattle Public Library copy, cover confirmed via render). **Duplicate pair** with `00.Cantonese I Booklet.doc` below — same booklet, two file formats. |
| `00.Cantonese I Booklet.doc` | 14 (when converted to PDF via LibreOffice for inspection) | No (embedded JPEG scan inside the .doc container — confirmed via `strings`/JFIF signature; the file's own metadata claiming "2 words, 17 characters" is misleading, since nearly all content is a raster scan, not native text) | Low | Same Pimsleur Cantonese I Supplemental Reading Booklet as the PDF above — a duplicate in a different container format. Treat as one source, extract once (whichever format proves easier to render). |

**Excluded — wrong metalanguage**

- **`10.Modern Cantonese Fast Primer.pdf`** (209pp, image-only) — despite its English-sounding
  filename, the actual book is **《跟我学讲广州话：流行粤语快速入门》by 林怡君 (Lin Yijun)**, entirely
  simplified-Chinese/Mandarin-medium (explanatory prose, instructions, and section headers all in
  Chinese; Cantonese forms given only in romanization + Chinese characters, glossed into Mandarin, not
  English). Confirmed via rendered cover and interior sample pages. Directly parallel to Korean's
  *Frequently Used Korean Dialogues 2000 Sentences* finding in that language's own triage — an
  English-sounding filename with Chinese-medium interior content, excluded on the same grounds.
- **`17.Hong Kong Путеводитель.pdf`** (44pp, image-only) — confirmed Russian-medium via rendered
  sample (full Russian prose throughout, e.g. "Нельзя пропустить," "Стар Ферри"). Excludes on both
  wrong-metalanguage grounds **and** out-of-scope grounds (see below) — a double exclusion, same
  pattern as Korean's *Berlitz Корейский разговорник и словарь*.

**Excluded — out of scope (pure tourism, no language-pedagogical content)**

- `14.Frommer's Hong Kong.pdf` — clean text, confirmed standard commercial travel guide.
- `15.Hong Kong (DK Eyewitness Top 10 Travel Guides).pdf` (172pp) — clean text, confirmed standard
  "Top 10" tourist-attraction guide.
- `16.Rough Guides Directions Hong Kong & Macau.pdf` (208pp) — clean text, confirmed standard
  commercial travel guide.
- `17.Hong Kong Путеводитель.pdf` — see above (also wrong-metalanguage).

**Duplicates / overlapping titles resolved**

1. **The 1994 Colloquial Cantonese edition exists in three copies across two formats**: the in-repo
   `Colloquial Cantonese.pdf`, the external drive's `02.Colloquial Cantonese 1994.pdf` (MD5-identical
   to the in-repo copy — `510dfea214fe49281f810bbfefebf265`), and the external drive's
   `02.Colloquial Cantonese 1994.djvu` (same edition, DjVu format, djvutxt confirms no text layer
   either). None of the three has a usable text layer. The external drive's **`03.Colloquial
   Cantonese 2010.pdf`** is a genuinely later, different edition with a **clean text layer** — treat
   it as the primary Colloquial-series extraction target, and the 1994 edition (any of its three
   copies) as, at most, a non-redundant-supplement pass once `03` is done.
2. **`07.Cantonese A Comprehensive Grammar` exists in two formats** (djvu + pdf), same Matthews & Yip
   edition — not independently new content, but the two scans differ in fidelity (djvu: 2 printed
   pages per image; pdf: 4 printed pages per image, confirmed by direct render). Use the djvu as the
   dispatch source.
3. **`00.Cantonese I Booklet.doc` and `00.Cantonese I Reading Booklet.pdf`** are the same Pimsleur
   Cantonese I Supplemental Reading Booklet in two container formats (confirmed via rendered cover
   page on both — identical "RECORDED BOOKS PRESENTS / PIMSLEUR / CANTONESE / SUPPLEMENTAL READING
   BOOKLET" cover). Extract once.

## OCR/scan status

**Of the 15 in-scope, non-duplicate, non-excluded titles, only 4 have a usable text layer**
(`03.Colloquial Cantonese 2010`, `04.Basic Cantonese A Grammar and Workbook`, `12.Hong Kong —
Language and National Identity in Asia`, `13.Language Relations in Guangzhou`) — roughly **27%**,
a notably *lower* clean-text rate than Korean (~65%), Spanish, or Dutch, and closer to Serbian/
Croatian/Bosnian's ~44%. OCR/vision-reading capacity should be budgeted as the dominant mode for this
language's Phase 1, not an occasional exception. Two additional gotchas confirmed during this triage,
worth flagging per the spec's running gotcha list:

- **Same-series volumes can differ in scan quality.** `04.Basic Cantonese A Grammar and Workbook`
  (clean text) and `05.Intermediate Cantonese A Grammar and Workbook` (its direct sequel, same
  Routledge series) came from visibly different source scans — `05` has effectively zero extractable
  text despite being typeset content confirmed identical in kind to `04` via rendered sample. Don't
  assume a text-layer verdict transfers across volumes of the same series.
- **A single title can be scanned at two different "pages-per-image" densities across its own
  format variants.** `07.Cantonese A Comprehensive Grammar`'s djvu packs 2 printed pages per image;
  its pdf twin packs 4 (a 2×2 grid) — confirmed by rendering the same content region in both files.
  This is a new variant of the spec's existing "two-printed-pages-per-image spread" gotcha (previously
  only confirmed as 2-per-image on Serbian/Croatian/Bosnian's *Colloquial Serbian*) — verify the
  actual pages-per-image ratio empirically per file, don't assume 2 is the ceiling.

## Morphological typology (preliminary, per Phase 0 convention)

**Cantonese: analytic/isolating**, like Mandarin and unlike this project's agglutinative languages
(Korean, Hungarian, Japanese, Tagalog's non-concatenative system). Grammatical relationships are
carried by word order, particles, and a classifier system rather than by stacking morphemes onto a
stem — "word"-as-atomic-vocabulary-item is much less fraught here than for the agglutinative
languages already in this project, so the morpheme-breakdown convention from
`00_Word_Concept_and_Morphological_Typology_Guide.md` is expected to see light use. The defining
structural complexity instead sits in the **tone system** (6-9 citation tones depending on counting
convention, plus a genuinely lexical/non-regular tone-change process — confirmed directly in the
rendered Comprehensive Grammar sample, §1.4.2) and in a rich **register/code-mixing system**
(Cantonese/English/Mandarin triglossia in Hong Kong, per `12` and `13`) — this second axis is likely
the more direct feeder into slang mechanics once extraction begins.

## Recommended Phase 1 extraction priority order

**Tier 1 — Flagship (vision-read, highest value, named directly by the sibling project):**
1. `09.A Dictionary of Cantonese Slang.pdf` (Hutton & Bolton) — sampled, not exhaustive (509pp);
   route extracted content conceptually to `language_corpus/Cantonese/` per the Phase 1/2 boundary.
2. `07.Cantonese A Comprehensive Grammar.djvu` (Matthews & Yip) — use djvu, not the lower-fidelity pdf
   twin.

**Tier 2 — High priority, clean text:**
3. `04.Basic Cantonese A Grammar and Workbook.pdf`
4. `03.Colloquial Cantonese 2010.pdf` (primary Colloquial-series edition; supersedes the 1994 edition
   for full extraction)
5. `06.Cantonese - Languages of the World.pdf` (Killingley) — vision-read but short and dense

**Tier 3 — Medium-high, vision-read course/grammar supplements:**
6. `05.Intermediate Cantonese A Grammar and Workbook.pdf` (non-redundant supplement against `04`)
7. `01.Teach Yourself Cantonese.pdf`
8. ~~`11.Gateway to Cantonese.djvu`~~ — **EXCLUDED 2026-11-03**, confirmed Chinese-medium on render, see above

**Tier 4 — Medium, academic/sociolinguistic (clean text, register-relevant):**
9. `13.Language Relations in Guangzhou.pdf`
10. `12.Hong Kong (Language and National Identity in Asia).pdf` (short, quick win)

**Tier 5 — Low priority:**
11. `08.Lonely Planet Cantonese Phrasebook.pdf`
12. `00.Cantonese I Reading Booklet.pdf` / `00.Cantonese I Booklet.doc` (extract once, whichever
    format renders more easily)
13. 1994 Colloquial Cantonese edition (any of its three copies) — only as a non-redundant-supplement
    pass after `03`'s 2010 edition is done, since the two editions almost certainly share most content.

**Not for extraction (excluded):** `10.Modern Cantonese Fast Primer.pdf` (wrong metalanguage —
Chinese-medium), `14.Frommer's Hong Kong.pdf`, `15.Hong Kong (DK Eyewitness Top 10 Travel
Guides).pdf`, `16.Rough Guides Directions Hong Kong & Macau.pdf` (all out-of-scope tourism),
`17.Hong Kong Путеводитель.pdf` (wrong metalanguage — Russian — and out-of-scope tourism).

---

## Open items for a future extraction pass

- `11.Gateway to Cantonese.djvu` was confirmed as a genuine scanned course via `djvudump`/rendering
  pipeline checks but not yet sampled for actual content quality — do a content sample before
  dispatch, same as every other vision-only source.
- `08.Lonely Planet Cantonese Phrasebook.pdf` should get a full skim (not just the one sampled page)
  specifically checking for a slang/colloquialism callout section before being written off as
  low-value, per the Japanese Rough Guide precedent.
- No native-speaker query folder exists yet for Cantonese — create one if/when Phase 1 extraction
  begins, per the project's standing convention for prosody/judgment questions only a speaker can
  settle.
