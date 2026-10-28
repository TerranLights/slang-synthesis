# Ilocano — Reference Material Triage Catalog

**Status: triage complete, 2026-10-26.** Source folder is
`/home/kuroskalacs/Documents/Doll-Fi/media/y-files/language-stash/Ilocano [Philippines]/` (an
external stash path, not yet copied into this project's `source_reference/` tree — per this
project's standing convention, source files are physically copied into
`source_reference/languages/Ilocano/` as part of or just before Phase 1 extraction, not during
triage; nothing was moved or copied during this pass). 3 real files, ~267MB combined.

**Why Ilocano, why now:** added to this project's roster because the sibling `TepenianHawaiian`
project (constructed-language synthesis of "Modern Hawaiian") requires Ilocano as a source
language alongside Tagalog — 2019-2023 Hawaii census data shows Ilocano speakers at home are
roughly as numerous as Tagalog speakers there. All extraction for `TepenianHawaiian`'s sources
happens in this repo, never in theirs. This catalog is the first step toward that; no extraction
has happened yet (Phase 0 triage only).

## The file-2-vs-file-3 question — resolved

**Verdict: files 2 and 3 are two different scans of the *same* published book** — *Ilocano
Dictionary and Grammar: Ilocano-English, English-Ilocano*, Carl Ralph Galvez Rubino, University of
Hawai'i Press (PALI Language Texts series, General Editor Byron W. Bender), © 2000. Confirmed by:

- **Identical title, author, and cover art.** File 3's rendered page 1 is a color photo of the
  physical book's dust jacket (market-scene painting, "Ilocano Dictionary and Grammar /
  Ilocano-English, English-Ilocano / Carl Ralph Galvez Rubino / PALI Language Texts"). File 2's
  text layer opens with the identical title/imprint/editor block and the same copyright page
  ("© 2000 University of Hawai'i Press").
- **Identical internal structure at matched locations.** File 2 PDF-page 50 (OCR text, roman
  numeral "xlviii") covers Grammar Outline §2.3 (nominal derivation, abstract-noun affixes). File
  3 PDF-page 50 (vision-rendered, roman numeral "liv") covers §3.2.2–4 (past demonstratives,
  future marker, adjectives) — same grammar-outline chapter, same section-numbering scheme, same
  prose style and example format, just offset by a few front-matter pages between the two scans.
- **Page-count difference (868 vs. 854, a 14-page gap) is scan-artifact, not edition
  difference.** File 2 is an Internet Archive scan (`Creator: Internet Archive (Scribe Version
  6.6)`) which characteristically bundles extra front/back pages (IA metadata, blank leaves,
  color-plate duplication). File 3 is a plain Adobe Acrobat image-conversion scan with no such
  IA scaffolding. No evidence of a genuinely different edition/printing (no distinct ISBN,
  copyright year, or preface text found at any sampled location).

**Practical implication for Phase 1:** treat file 2 and file 3 as **one source, two scans** —
extract from file 2 (the one with an actual text layer, however imperfect) as primary, and fall
back to file 3's clean page images only for individual pages where file 2's OCR is bad or a
diacritic is ambiguous. There is no reason to extract both in full.

**File 1 is NOT a third copy of this — it is a genuinely different, unrelated work.** "A
Reference Grammar of Ilocano" is Rubino's own 1997 PhD dissertation (University of California,
Santa Barbara, Department of Linguistics; UMI/ProQuest microfilm reproduction, UMI Number
9823418). Confirmed via its own title page, UMI boilerplate, and CV pages (rendered and
inspected directly): committee chaired by Marianne Mithun, with Susanna Cumming, Lawrence Reid,
Wallace Chafe, and Katia McClain; author's own CV page lists "A Reference Grammar of the Ilocano
language, UCSB Dissertation" and "A root based dictionary of the Ilocano language, UCSB ms." as
two *separate* works — i.e. the dissertation predates and is distinct from (likely an ancestor
of) the 2000 published dictionary+grammar book, not a duplicate of it. The dissertation uses
full interlinear morpheme glossing (e.g. `EXIST PL tree LIG PL-like thigh only ART trunk=3p`)
throughout, a level of grammatical formalism the published book's compact ~70-page "Grammar
Outline" front matter does not carry — genuinely complementary content, not redundant.

## In-scope material — grouped by text-layer status

| # | File | Pages | Text layer | Notes |
|---|---|---|---|---|
| 1 | `A reference grammar of Ilocano (Carl Ralph Galvez Rubino) (z-library.sk, 1lib.sk, z-lib.sk).pdf` | 549 | **None** (`pdffonts` reports zero fonts; `pdftotext` returns nothing on any sampled page) — pure image scan, UMI microfilm reproduction of a typewriter/laser-printed dissertation | 1997 UCSB PhD dissertation. Clean, legible scanned print (no visible degradation in sampled pages). Deep academic grammar with full interlinear glossing — phonology/morphology/syntax in far more formal detail than either of the other two files. Will need full vision-reading for extraction. |
| 2 | `Ilocano dictionary and grammar Ilocano-English, English-Ilocano (Rubino, Carl R. Galvez) (z-library.sk, 1lib.sk, z-lib.sk).pdf` | 868 | **Real, OCR-derived text layer** (`GlyphLessFont` CID TrueType, Internet Archive Scribe) — body text extracts cleanly and is directly usable; ornate/stylized title-page text OCRs poorly (garbled), body dictionary/grammar prose does not | **Primary source — Group A (clean-enough text, Wave 1).** 2000, University of Hawai'i Press, PALI Language Texts. Combined ~70-page grammar outline + large bidirectional (Ilocano-English, English-Ilocano) dictionary. Same book as file 3 (see verdict above); prefer this copy for extraction since it has usable text. |
| 3 | `Ilocano-English, English-Ilocano Dictionary and Grammar (Galvez Rubino C.R.) (z-library.sk, 1lib.sk, z-lib.sk).pdf` | 854 | **None** (`pdffonts` reports zero fonts) — pure image scan, Adobe Acrobat Image Conversion Plug-in | **Duplicate scan of file 2 — Group B, fallback only.** Same 2000 PALI book as file 2 (see verdict above). High page-image quality (full color cover scanned; larger file size, 186MB vs. file 2's 66MB) but no text layer at all — would require full vision-reading if used. Not recommended as a primary extraction target given file 2 already has usable text for the same content; keep on hand only for spot-checking specific pages where file 2's OCR is ambiguous. |

No garbled-but-present OCR distinct from "no text layer at all" was found on files 1/3 — both are
unambiguous `pdffonts`-confirmed pure image scans, not a font-substitution-cipher case.

## Hawaii-specific content — found; sibling project's "nothing found" no longer holds

The sibling `TepenianHawaiian` project had looked and found nothing Hawaii-specific in Ilocano
material. **That is no longer true once file 2's text is actually searched.** The 2000 PALI
dictionary (University of Hawai'i Press itself, naturally) contains genuine Hawaii-specific
sociolinguistic and lexical content:

- **Explicit demographic/sociolinguistic statement in the Introduction** (p. xii): "The largest
  concentrations of Ilocanos in the United States are in California, Alaska, and especially
  Hawai'i, where nearly one-fifth of the total population can claim Ilocano descent (Espiritu
  1977; Foronda 1978). In Hawai'i, Ilocano has been taught in the schools in bilingual education
  programs as the medium of instruction and in universities as a foreign language."
- **`Purgi: (Hawaii) n., a. (coll.) Portuguese, more formal term is portugés.`** — a
  Hawaii-tagged, explicitly colloquial ethnic-slang term for Portuguese, almost certainly a
  plantation-era-contact coinage (Portuguese laborers were a major 19th/early-20th-century
  Hawaii plantation demographic alongside Ilocano/Filipino workers). This is exactly the kind of
  "historical Hawaii plantation-era Ilocano usage" the task asked about, and the strongest single
  finding of this triage pass.
- **`kanaka: (Hawaiian use only) n. Native Hawaiian. (Hawayano, taga-Hawait)`** — a Hawaiian-origin
  loanword entered into the Ilocano lexicon with an explicit regional-use tag.
  `Aloha: (Hawai'i) interj. Hawaiian greeting of welcome or farewell.` is tagged the same way.
- **`Haway: n. Hawai'i. Hawayano. n., a. Hawaiian. (taga-Hawaii)`** — the native Ilocano terms for
  "Hawaii"/"Hawaiian," with a note that /h/ was "originally not a sound in the Ilocano language"
  (phonological-contact detail worth flagging for `TepenianHawaiian`'s phonology work, since it
  documents Ilocano borrowing a phoneme via Hawaii/English contact).
- **A worked Hawaii-set example sentence**: *Naar-aringanen ti ugali ditoy Hawaii* — "(Our) ways
  are already influenced and changed here in Hawai'i," under the entry for `aringan` ("to
  influence").
- The acknowledgments thank "the Ilokano department in Hawai'i: Josie Paz Clausen and Precy
  Espiritu," consistent with the book's institutional grounding in University of Hawai'i
  linguistics.

These are a small number of entries (4 explicitly `(Hawai'i)`/`(Hawaiian)`-tagged lexical items
plus one demographic paragraph and one example sentence) out of a ~400-page dictionary, not a
large seam — but they are real, previously-unfound Hawaii-specific material and should be
explicitly flagged for `TepenianHawaiian` once Phase 1 extraction of this book happens. File 1
(the dissertation) could not be checked for the same thing — it has no text layer at all, so this
would require a full vision read to confirm either way; flagged as an open item, not a "confirmed
absent."

## Recommended Phase 1 extraction priority order

1. **File 2** (`Ilocano dictionary and grammar...`, 868pp, text layer) — primary source, Group A.
   Covers both a grammar outline and a large bidirectional dictionary; the grammar outline alone
   is comparable in scope to a short reference grammar, and the dictionary is the largest
   single vocabulary source available for this language. Given the ~868-page scale, flag for
   **representative sampling or chunked wave-based dispatch** the same way Tagalog's oversized
   dictionary/reader sources were handled, rather than one flat extraction pass.
2. **File 1** (`A reference grammar of Ilocano`, 549pp, no text layer) — Group B, vision-reading
   required. Higher linguistic-formalism value (full interlinear glossing, deeper phonology/
   morphosyntax treatment) than file 2's grammar outline; worth prioritizing once vision-reading
   capacity is budgeted, not treated as a lower-value afterthought just because it needs OCR/
   vision rather than text extraction.
3. **File 3** — do not extract in full; same content as file 2. Hold in reserve only for spot
   verification of specific pages where file 2's OCR is unreliable.

## Morphological typology (preliminary, per Phase 0 convention)

**Ilocano: Austronesian (Philippine, Cordilleran branch), closely related to Tagalog but
genuinely distinct** — expect a similar non-concatenative, affix-and-focus (voice/trigger)
verbal morphosyntax to Tagalog's (per Tagalog's own typology note), but Ilocano is not simply
"Tagalog with different vocabulary": it has its own phoneme inventory (notably lacking native
/h/ per the `Haway` entry above, until loanword contact introduced it), its own case/article
system, and reduplication patterns (CVC-reduplication for distributive plurals is directly
attested in file 1's sampled pages — `baket → babbaket` "old ladies," etc.). Heavy Spanish
loanword stratum (`asiénda`, `purgante`, `kartera` — centuries of Spanish colonial contact,
parallel to Tagalog) plus the smaller but real Hawaii/English-contact stratum documented above.
Will be refined further once extraction lands at scale — defer to this language's own
`00_Extraction_Checklist.md` once created, per the general spec's instruction to check it before
treating any surface word as atomic.
