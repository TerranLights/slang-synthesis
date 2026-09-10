# slang-synthesis
a centralized repo for collecting, analyzing, and re-synthesizing slang from across languages

## Project Purpose

This repo supports a sci-fi universe by deriving plausible in-universe slang for its
fictional languages and cultures, grounded in how slang actually forms in real human
languages rather than invented arbitrarily.

The pipeline:

1. **Reference extraction** — `source_reference/` holds a large, growing local library of
   standard language reference material (grammars, vocabulary, dictionaries) per real-world
   language, extracted into `datasets/<Language>/established/`. It's gitignored since it
   will grow into many gigabytes of PDFs/djvu.
2. **Web scraping (general, frequency-tagged)** — broad web collection of vocabulary and
   phrasing per language, tagged by frequency of use, with per-language scrape logs to
   prevent double-counting a source. Not yet built out.
3. **Slang corpus (curation)** — the raw scrape (plus any slang-dictionary-type material
   found directly in `source_reference/` during triage) gets filtered and curated into an
   actual sourced, tiered slang corpus, landing in `language_corpus/<Language>/`.
4. **Mechanics analysis** — full analysis of the mechanics of how slang forms and works on
   a per-language basis (semantic shift, phonological reduction, borrowing, taboo
   inversion, etc.), landing in `datasets/<Language>/analysis/`.
5. **Cross-language comparative pass** — once several languages have real analysis data,
   look across them for slang-formation patterns that recur vs. stay language-specific.
6. **Synthesis** — that analysis feeds into synthesizing invented slang for the sci-fi
   universe's constructed languages/cultures, grounded in real linguistic mechanics,
   landing in `datasets/<Language>/synthesized/`.

**See [`ROADMAP.md`](ROADMAP.md)** for how this gets sequenced in practice — the reference
material alone is 70GB+ across 40+ languages, so this isn't a "do it all at once" effort.

**See [`LANGUAGE_INDEX.md`](LANGUAGE_INDEX.md)** for the master roster of every language this
project covers or will cover, organized by language family, with the highest-priority
languages (the ones actually represented in the sci-fi setting's own worldbuilding census)
flagged.
