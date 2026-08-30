# {{Language}} Slang Corpus — Extraction Checklist

**Purpose:** collect a real, sourced corpus of {{Language}} slang (contemporary and/or historical,
note which) to ground later mechanics analysis (`datasets/{{Language}}/`) and eventual synthesis
work for the sci-fi setting. Source reference grammar/vocabulary for {{Language}}, if any, lives in
`source_reference/languages/{{Language}}/`.

**This is research only — nothing here is canon** until worked into actual setting material by
explicit decision.

**Status legend:** `[x]` collected and written into its output file · `[ ]` not yet done.

---

## Output files

| File | Contents |
|---|---|

**Scale warning:** given how much raw material this project draws on, don't let corpus content
accumulate into one or two giant files. Split by whatever axis makes sense (register, domain/
subculture, era, source) and start a new numbered file (`01_`, `02_`, ...) once an existing one
gets unwieldy to read/diff — same discipline as the sharded JSONs in `datasets/{{Language}}/`. Fill
this table in as files are created, one row per file.

---

## Sources consulted

- [ ] *(web source, forum, dictionary, corpus database, etc. — one bullet per source, note what
      was found and what's still unread, same discipline as a book checklist)*

**Subtitles & transcripts are a valid and valuable source** — real spoken usage, often the only
place certain slang shows up at all. **But see
[`00_Source_Reliability_Guide.md`](../00_Source_Reliability_Guide.md) before pulling from one**:
AI-auto-generated captions can be confidently wrong about slang specifically, since the
transcription model may have no lexical prior for the term at all. Every entry sourced from a
subtitle/transcript needs a `source_type` and, if AI-generated, a `transcription_confidence` flag
— this is not optional and the flag must survive into `datasets/{{Language}}/` downstream, not get
dropped during summarization.

## Scope notes

*(Contemporary vs. historical slang? Regional/dialect variation? Specific subcultures or domains
of interest for this project? Note constraints here as they're decided.)*

## Graphify

This language gets its own graph, scoped to `language_corpus/{{Language}}/` (separate from
`datasets/{{Language}}/`'s own graph, which additionally covers the sharded JSONs there). Run
`/graphify language_corpus/{{Language}}` once there's enough written here to be worth graphing —
no need to do this before any content exists. Watch for graphify's own size warnings (2M words /
500 files) as a signal this language's corpus itself needs further splitting.

## Suggested next-session order

1. *(fill in)*
