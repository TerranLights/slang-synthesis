# Serbian/Croatian/Bosnian Slang Corpus — Extraction Checklist

**This is the pipeline's first test-run language — tentative status.** Per the developer's
sequencing decision (deferred, see
`../../methodology-observations/serbian_croatian_bosnian_test_run.md`), **Phase 2 (this file's own
scope, web research) has not started yet** — Phase 1 reference extraction
(`datasets/Serbian_Croatian_Bosnian/`) is still in progress. This checklist is scaffolded now so the
folder structure exists, not because collection has begun.

**Purpose:** collect a real, sourced corpus of Serbian/Croatian/Bosnian slang (contemporary and/or
historical, note which) to ground later mechanics analysis
(`datasets/Serbian_Croatian_Bosnian/`) and eventual synthesis work for the sci-fi setting. Source
reference grammar/vocabulary for Serbian/Croatian/Bosnian, if any, lives in
`source_reference/languages/Serbian, Croatian, Bosnian/`.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` collected and written into its output file · `[ ]` not yet done.

---

## Output files

| File | Contents |
|---|---|
| *(none yet — Phase 2 not started)* | |

**Scale warning:** given how much raw material this project draws on, don't let corpus content
accumulate into one or two giant files. Split by whatever axis makes sense (register, domain/
subculture, era, source) and start a new numbered file (`01_`, `02_`, ...) once an existing one gets
unwieldy to read/diff — same discipline used in `datasets/Serbian_Croatian_Bosnian/`. Fill this
table in as files are created, one row per file.

---

## Sources consulted

- [ ] *(web source, forum, dictionary, corpus database, etc. — one bullet per source, note what
      was found and what's still unread, same discipline as a book checklist)*

**Subtitles & transcripts are a valid and valuable source** — real spoken usage, often the only
place certain slang shows up at all. **But see
[`../00_Source_Reliability_Guide.md`](../00_Source_Reliability_Guide.md) before pulling from one**:
AI-auto-generated captions can be confidently wrong about slang specifically, since the
transcription model may have no lexical prior for the term at all. Every entry sourced from a
subtitle/transcript needs a `Source Type` and, if AI-generated, a `Transcription Confidence` flag —
this is not optional and the flag must survive into `datasets/Serbian_Croatian_Bosnian/` downstream,
not get dropped during summarization.

## Scope notes

*(Contemporary vs. historical slang? Regional/dialect variation? Specific subcultures or domains of
interest for this project? Note constraints here as they're decided.)*

**Note era/region when a source actually supports it.** A term perfectly natural in one decade can
be alien in another (1960s slang vs. 1790s), and slang can be sharply localized within a single
language (Quebec City French vs. Marseille French; Shenzhen Mandarin vs. Singaporean Mandarin).
When collecting, jot down the source's own date/place context if it has one — this feeds the
`Attested Era`/`Attested Region` columns in `datasets/Serbian_Croatian_Bosnian/`'s Markdown tables
later. **Not required** — most sources won't support it, and a guessed date/place is worse than
none. See
[`../../datasets/00_Historical_and_Geographic_Context_Guide.md`](../../datasets/00_Historical_and_Geographic_Context_Guide.md).

## Graphify

This language gets its own graph, scoped to `language_corpus/Serbian_Croatian_Bosnian/` (separate
from `datasets/Serbian_Croatian_Bosnian/`'s own graph). Not yet run — no content exists here yet.

## Suggested next-session order

1. *(fill in once Phase 2 begins, gated on Phase 1 reference extraction reaching a reasonable
   state)*
