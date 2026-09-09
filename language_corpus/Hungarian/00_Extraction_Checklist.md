# Hungarian Slang Corpus — Extraction Checklist

**When filling in `Hungarian` below: use the folder-safe name (matching the actual
`language_corpus/<Language>/` directory name, e.g. `Serbian_Croatian_Bosnian`) in every file path,
and the natural display name (e.g. "Serbian/Croatian/Bosnian") in prose only. A naive
find-and-replace of `Hungarian` with the display name will corrupt any path containing it —
confirmed as a real bug during the first test run, see
`../../methodology-observations/serbian_croatian_bosnian_test_run.md`.

**Purpose:** collect a real, sourced corpus of Hungarian slang (contemporary and/or historical,
note which) to ground later mechanics analysis (`datasets/Hungarian/`) and eventual synthesis
work for the sci-fi setting. Source reference grammar/vocabulary for Hungarian, if any, lives in
`source_reference/languages/Hungarian/`.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` collected and written into its output file · `[ ]` not yet done.

---

## Output files

| File | Contents |
|---|---|
| `01_szlengszotar_dictionary_pp90-179.md` | 196-entry representative sample from *Magyar Szlengszótár* (dedicated Hungarian slang dictionary), vision-read from `source_reference/languages/Hungarian/Magyar Szlengszótár.pdf` PDF pages 46–90 (= printed pages 90–179, alphabetical range el- through link). Source has no text layer; two printed pages per scanned PDF image, offset confirmed empirically. Not exhaustive — spread-level + within-spread sampling documented in the file's own coverage-decision note; full dictionary alphabet range (a–z) is much larger than this one chunk. |
| `02_szlengszotar_kovecses_A-E_sample.md` | ~130-entry representative sample from the same *Magyar Szlengszótár* (Kövecses Zoltán, 2nd ed. 2009), vision-read from PDF pages 1–45 (= printed front matter pp. 1–25 + dictionary pp. 30–89, alphabetical range A through early E — 7 spread-level samples: ad–akkor, banyakocsi–bazíroz, belepkézik–benzintyúk, bogyózik–brahi, csárázás–csipkedi, döglik–durranás, eliszkol–elmegy). Same no-text-layer / two-printed-pages-per-scan situation as `01`; page-mapping formula re-derived and confirmed independently (printed page = 2×PDF page − 2/−1). Not exhaustive, same sampling discipline as `01`. Together with `01`, gives continuous A-through-"link" coverage across PDF pages 1–90 of 170; PDF pages 91–170 still unread. Includes a dedicated Morphological notes section (denominal verbing, root-family radiation, taboo-root compounding) and a standout-patterns section for Phase 3 (productive dismissal-formula slot-filler, rhyming euphemistic substitution, semantic bleaching of violent/mortality roots into intensifiers). |
| `03_szlengszotar_dictionary_pp270-336.md` | Representative sample from *Magyar Szlengszótár*, vision-read from PDF pages 136–170 of 170 (the final chunk of the book) = printed pp. 270–336, through the book's last printed content page. Same page-mapping formula as `01`/`02`. Standout findings: two ethnonym-based slurs flagged explicitly as offensive attested source material (not neutral data), a `zsír-`/`háj-` ("fat/grease/lard") root radiating into at least 3 distinct target meanings (fatness, wealth, quality-intensification) — confirmed as a recurring cross-book pattern alongside `02`'s root-radiation finding — and continued productivity of the `-zik/-ázik/-ozik` denominal-verbing suffix at the alphabet's tail, consistent with `02`'s finding from the A-E range. |
| `04_szlengszotar_dictionary_pp180-269.md` | 118-entry representative sample from *Magyar Szlengszótár*, vision-read from PDF pages 91–135 of 170 (= printed pp. 180–269, alphabetical range l- through sz-, i.e. literre/ló- through sziszegő/szkárpi). Fills the gap between `01` and `03` — **with this file's landing, the dictionary's main alphabetized body (pp. 1–336) has full A–Z representative-sample coverage across `01`+`02`+`03`+`04`.** Same page-mapping formula and sampling discipline as `01`–`03` (9 even-interval spreads, both leaves read where a formation-pattern cluster spanned the spread). Standout findings: a highly productive open-slot `mint X` ("like X") simile-template cluster for "very much"/"fast" (p.202–203, ~10 distinct fillers spanning tame-to-taboo register); dense compound-cluster productivity around the taboo hub nouns `segg-` ("butt," p.250–251) and `szar-` ("shit," p.262–263), each generating dozens of insults/idioms/intensifiers off one root; the `szar` headword's 9-numbered-sense polysemy chain, the longest observed in this project's Hungarian sampling so far; and the `meg-`/`össze-` perfective/completive verb-prefix series (p.190–191, p.226–227) showing the same base-verb-plus-productive-bound-prefix pattern at high density. |

**Scale warning:** given how much raw material this project draws on, don't let corpus content
accumulate into one or two giant files. Split by whatever axis makes sense (register, domain/
subculture, era, source) and start a new numbered file (`01_`, `02_`, ...) once an existing one
gets unwieldy to read/diff — same discipline as the sharded JSONs in `datasets/Hungarian/`. Fill
this table in as files are created, one row per file.

---

## Sources consulted

- [x] *Magyar Szlengszótár* (Hungarian slang dictionary, `source_reference/languages/Hungarian/`)
      — vision-read, no text layer, 170 PDF pages total. **Now fully sampled end-to-end**: PDF
      pages 1–45 (printed front matter + dictionary pp. 30–89, A through early E) →
      `02_szlengszotar_kovecses_A-E_sample.md` (~130 entries); PDF pages 46–90 (printed pp. 90–179,
      el- through link) → `01_szlengszotar_dictionary_pp90-179.md` (196 entries); PDF pages 91–135
      (printed pp. 180–269, l- through sz-) → `04_szlengszotar_dictionary_pp180-269.md`
      (118 entries); PDF pages 136–170 (printed pp. 270–336, the book's tail, including the
      Szinonimamutató synonym-index section) → `03_szlengszotar_dictionary_pp270-336.md`. All four
      files document the same empirically-confirmed page-mapping formula (printed page = 2×PDF
      page − 2/−1). Each is a *representative sample* per its own coverage-decision note, not an
      exhaustive transcription — a future pass could still deepen coverage within any already-
      sampled range if that becomes a priority, but the full alphabet (A–Z) now has at least one
      representative sample per letter.
- [ ] *(other web source, forum, corpus database, etc. — one bullet per source, note what was
      found and what's still unread, same discipline as a book checklist)*

**Subtitles & transcripts are a valid and valuable source** — real spoken usage, often the only
place certain slang shows up at all. **But see
[`00_Source_Reliability_Guide.md`](../00_Source_Reliability_Guide.md) before pulling from one**:
AI-auto-generated captions can be confidently wrong about slang specifically, since the
transcription model may have no lexical prior for the term at all. Every entry sourced from a
subtitle/transcript needs a `source_type` and, if AI-generated, a `transcription_confidence` flag
— this is not optional and the flag must survive into `datasets/Hungarian/` downstream, not get
dropped during summarization.

## Scope notes

*(Contemporary vs. historical slang? Regional/dialect variation? Specific subcultures or domains
of interest for this project? Note constraints here as they're decided.)*

**Note era/region when a source actually supports it.** A term perfectly natural in one decade can
be alien in another (1960s slang vs. 1790s), and slang can be sharply localized within a single
language (Quebec City French vs. Marseille French; Shenzhen Mandarin vs. Singaporean Mandarin).
When collecting, jot down the source's own date/place context if it has one — this feeds the
`attested_era`/`attested_region` fields in `datasets/Hungarian/`'s structured shards later. **Not
required** — most sources won't support it, and a guessed date/place is worse than none. See
[`../datasets/00_Historical_and_Geographic_Context_Guide.md`](../../datasets/00_Historical_and_Geographic_Context_Guide.md).

## Graphify

This language gets its own graph, scoped to `language_corpus/Hungarian/` (separate from
`datasets/Hungarian/`'s own graph, which additionally covers the sharded JSONs there). Run
`/graphify language_corpus/Hungarian` once there's enough written here to be worth graphing —
no need to do this before any content exists. Watch for graphify's own size warnings (2M words /
500 files) as a signal this language's corpus itself needs further splitting.

## Suggested next-session order

1. *(fill in)*
