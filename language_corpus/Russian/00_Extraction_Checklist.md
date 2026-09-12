# Russian Slang Corpus — Extraction Checklist

**Purpose:** collect a real, sourced corpus of Russian slang (contemporary and/or historical, note
which) to ground later mechanics analysis (`datasets/Russian/`) and eventual synthesis work for
the sci-fi setting. Source reference grammar/vocabulary for Russian lives in
`source_reference/languages/Russian/`; a large Phase 1 `established/` extraction is already well
underway there (numbered files 001–032+ as of this writing).

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` collected and written into its output file · `[ ]` not yet done.

---

## Output files

| File | Contents |
|---|---|
| `01_dermo_alphabetical_glossary.md` | Full transcription of *Dermo! The Real Russian Tolstoi Never Used* (Edward Topol, 2011)'s two closing glossary sections: "An Additional Alphabetical Glossary of Real Russian, Which Is Far from Complete" (printed pp. 124–138, ~230 entries A–Я) and "A Brief Glossary of Essential English Terms Accompanied by Russian Translations" (printed pp. 139–140, ~30 entries). Vision-read, no text layer. Essentially exhaustive for these two sections — the source itself is already curated/selective ("far from complete" per its own title), so this file captures effectively all of it rather than sampling. |
| `02_dermo_thematic_chapters.md` | Representative extraction from the book's ten thematic chapters (printed pp. 1–123): mat/oath structure and folklore (Ch. I–III), drinking slang (Ch. IV), computer/tech slang (Ch. V), love-making vocabulary (Ch. VI), business slang (Ch. VII), youth/general insults (Ch. VIII), and — captured in full detail — Chapter IX's жопа ("ass") idiom cluster and Chapter X's systematic хуй/пизда/ебать derivational-family tour, including the book's own "triple-decker profanity" combinatorial demonstration. Not exhaustive for Ch. I–VIII (dense running prose+drill format, not glossary format) — explicit sampling/coverage note inside the file. |

**Scale warning:** given how much raw material this project draws on, don't let corpus content
accumulate into one or two giant files. Split by whatever axis makes sense (register, domain/
subculture, era, source) and start a new numbered file (`01_`, `02_`, ...) once an existing one
gets unwieldy to read/diff.

---

## Sources consulted

- [x] *Dermo! The Real Russian Tolstoi Never Used* (Edward Topol, 2011) —
      `source_reference/languages/Russian/Russian Learning Pack [up-to-date as of 2012]/Vol 1 of 3/100.Dermo! The Real Russian Tolstoi Never Used.pdf`,
      160 PDF pages (printed pp. 1–140 + front/back matter). No text layer (scanned, one printed
      page per PDF-page image, offset: printed page = PDF page − 18, confirmed empirically across
      the whole book). Vision-read in full — every page rendered and read. This is a dedicated
      slang/profanity phrasebook-dictionary (essayistic commentary + word lists + idiom lists), not
      a grammar reference, hence routed here rather than to `datasets/Russian/established/`. See
      `01_` and `02_` above for what was captured from it.
- [ ] *(other web source, forum, corpus database, etc. — one bullet per source, note what was
      found and what's still unread, same discipline as a book checklist)*

**Subtitles & transcripts are a valid and valuable source** — real spoken usage, often the only
place certain slang shows up at all. **But see
[`00_Source_Reliability_Guide.md`](../00_Source_Reliability_Guide.md) before pulling from one**:
AI-auto-generated captions can be confidently wrong about slang specifically, since the
transcription model has no reliable prior for words it may never have encountered.
