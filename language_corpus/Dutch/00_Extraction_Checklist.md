# Dutch Slang Corpus — Extraction Checklist

**When filling in `Dutch` below: use the folder-safe name (matching the actual
`language_corpus/<Language>/` directory name, e.g. `Serbian_Croatian_Bosnian`) in every file path,
and the natural display name (e.g. "Serbian/Croatian/Bosnian") in prose only. A naive
find-and-replace of `Dutch` with the display name will corrupt any path containing it —
confirmed as a real bug during the first test run, see
`../../methodology-observations/serbian_croatian_bosnian_test_run.md`.

**Purpose:** collect a real, sourced corpus of Dutch slang (contemporary and/or historical,
note which) to ground later mechanics analysis (`datasets/Dutch/`) and eventual synthesis
work for the sci-fi setting. Source reference grammar/vocabulary for Dutch, if any, lives in
`source_reference/languages/Dutch/`.

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
gets unwieldy to read/diff — same discipline as the sharded JSONs in `datasets/Dutch/`. Fill
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
— this is not optional and the flag must survive into `datasets/Dutch/` downstream, not get
dropped during summarization.

## Scope notes

*(Contemporary vs. historical slang? Regional/dialect variation? Specific subcultures or domains
of interest for this project? Note constraints here as they're decided.)*

**Note era/region when a source actually supports it.** A term perfectly natural in one decade can
be alien in another (1960s slang vs. 1790s), and slang can be sharply localized within a single
language (Quebec City French vs. Marseille French; Shenzhen Mandarin vs. Singaporean Mandarin).
When collecting, jot down the source's own date/place context if it has one — this feeds the
`attested_era`/`attested_region` fields in `datasets/Dutch/`'s structured shards later. **Not
required** — most sources won't support it, and a guessed date/place is worse than none. See
[`../datasets/00_Historical_and_Geographic_Context_Guide.md`](../../datasets/00_Historical_and_Geographic_Context_Guide.md).

## Graphify

This language gets its own graph, scoped to `language_corpus/Dutch/` (separate from
`datasets/Dutch/`'s own graph, which additionally covers the sharded JSONs there). Run
`/graphify language_corpus/Dutch` once there's enough written here to be worth graphing —
no need to do this before any content exists. Watch for graphify's own size warnings (2M words /
500 files) as a signal this language's corpus itself needs further splitting.

## Suggested next-session order

1. *(fill in)*
