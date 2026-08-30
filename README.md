# slang-synthesis
a centralized repo for collecting, analyzing, and re-synthesizing slang from across languages

## Project Purpose

This repo supports a sci-fi universe by deriving plausible in-universe slang for its
fictional languages and cultures, grounded in how slang actually forms in real human
languages rather than invented arbitrarily.

The pipeline:

1. **Reference** — `source_reference/` holds a large, growing local library of standard
   language reference material (grammars, vocabulary, dictionaries) per real-world
   language. It's gitignored since it will grow into many gigabytes of PDFs/djvu.
2. **Corpus collection** — extensive research collecting a corpus of actual slang for
   each respective real-world language, landing in `language_corpus/`.
3. **Analysis** — full analysis of the mechanics of how slang forms and works on a
   per-language basis (semantic shift, phonological reduction, borrowing, taboo
   inversion, etc.), landing in `datasets/`.
4. **Synthesis** — that analysis feeds into synthesizing invented slang for the sci-fi
   universe's constructed languages/cultures, grounded in real linguistic mechanics.
