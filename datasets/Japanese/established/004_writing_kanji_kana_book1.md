# Japanese — Established Vocabulary/Grammar: Writing System Foundation (Source note + scope)

**Source:** `source_reference/languages/Japanese/02.Japanese Writing System/A guide to writing
Kanji and Kana Book 1.pdf` (320 pages, no text layer, vision-read via rendered page images).

## Important finding: this PDF duplicates another already-extracted source

Direct inspection (vision-reading pages spread across the full 320-page range, then cross-checking
against sibling extraction files already present in this folder) established that **this specific
PDF file bundles two entirely different Tuttle Language Library books together**, not one:

1. **PDF pages 1–~118: a full, duplicate copy of Kenneth G. Henshall & Tetsuo Takagaki's *A Guide
   to Learning Hiragana and Katakana* (Tuttle, 1990, ISBN 0-8048-1633-8)** — same title page,
   copyright page, table of contents, "An Explanation of Kana" essay, and the same per-symbol
   kana-teaching pages (each kana paired with its historical "parent" kanji and cross-reference
   number, e.g. ち → 知, つ → 川, な → 奈, に → 仁, の → 乃, は → 波, を → 遠, ん → 尤) as the
   **already-extracted, standalone copy of this same book** at
   `001_guide_to_hiragana_katakana.md` / `001b` / `001c` / `001d` (extracted from the separate,
   clean, 119-page `A Guide to learning Hiragana and Katakana.pdf` file in the same source folder).
   Confirmed by direct string comparison: identical cross-reference kanji, identical example
   vocabulary (にし "west", アルバイト "part-time job", まどぎわぞく "staff passed over for
   promotion", etc.) appear verbatim in both this PDF and the already-completed 001-series files.
   **This content is not re-extracted here — see the 001-series files, which cover it in full
   (all 119 pages) and correctly, rather than the partial/redundant sample an earlier pass of this
   file attempted.**
2. **PDF pages ~119–320: the actual, correctly-titled *A Guide to Writing Kanji & Kana: Book 1* by
   Wolfgang Hadamitzky and Mark Spahn (Tuttle, ISBN 0-8048-1685-9)** — the book this filename and
   both covers (front, PDF p. 1; back, PDF p. 320) genuinely describe. This portion is **unique**
   to this PDF (no sibling file extracts it) and is the real content of this dispatch. It consists
   of a standalone, numbered kanji-entry section — confirmed entries #131 through at least #758
   across roughly 200 pages, each with stroke order, radical codes, readings, meaning, and 4–5
   compound-word examples. **Extracted in `004c_writing_kanji_kana_book1.md`.**

**How the duplication was caught:** an earlier pass of this dispatch (before this revision)
vision-read a handful of the kana-teaching pages in this PDF without yet knowing a clean,
standalone copy of that same book existed elsewhere in the source folder, and began extracting it
as if it were new Hadamitzky/Spahn content. Checking this folder's existing files before finalizing
output (per the check-first duplicate-prevention discipline in `00_Reference_Extraction_Spec.md`)
caught the overlap. **Lesson for future dispatches on this corpus:** before vision-reading a
merged-looking PDF, grep this `established/` folder for distinctive strings from the pages you're
about to transcribe — a scanned source can duplicate another source's content wholesale, not just
show the handwritten-marginalia or font-cipher risks the spec already calls out.

**Vision-reading guard note (applies to the unique Hadamitzky/Spahn portion in `004c`):** no
handwritten marginalia was found. Several kanji-entry pages show a faint gray "ghost" kanji
silhouette bleeding through from the facing page of the physical scan into blank practice-writing
cells — print show-through, not a reader's marks, and excluded from extraction.

---

## What to read instead of this file

- Henshall & Takagaki's *A Guide to Learning Hiragana and Katakana* (kana theory, full 46-symbol
  hiragana + katakana inventories, all drilled vocabulary, Final Review section): see
  `001_guide_to_hiragana_katakana.md`, `001b_guide_to_hiragana_katakana_katakana.md`,
  `001c_guide_to_hiragana_katakana_hiragana_vocab.md`,
  `001d_guide_to_hiragana_katakana_final_review.md`.
- Hadamitzky & Spahn's *A Guide to Writing Kanji & Kana: Book 1* (the unique content of this PDF):
  see `004c_writing_kanji_kana_book1.md`.

This file intentionally carries no vocabulary/grammar tables of its own, to avoid duplicating the
001-series content with a lower-quality partial re-extraction.
