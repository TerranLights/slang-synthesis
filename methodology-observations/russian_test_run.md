# Test Run: Russian — Methodology Observations

**Status: tentative** (per the standing policy in `00_Index.md` — not yet reviewed/confirmed).

**Context.** Russian is the fourth language to reach full Phase 1 completion, after Serbian/
Croatian/Bosnian, Hungarian, and Korean, and by a wide margin the largest single-language corpus
this project has processed (281 `established/` files, ~1,360,000 words, versus SCB's 850,000 as
the next-largest). It is one of the 43 Inner Tepenia GDD Gini-index high-priority languages. This
run spanned roughly 24 hours of near-continuous autonomous dispatch across multiple session/weekly
usage-limit resets, following the same full-triage-then-wave-extraction methodology validated on
prior languages, extended to a much larger scale than any prior run.

---

## Log

### 2026-09-12 — Full triage: the largest and most heterogeneous corpus yet

`source_reference/languages/Russian/` held 204 real files (~3.6GB) across a top-level "Russian
Grammar books" folder, a single top-level course book, and a 3-volume "Russian Learning Pack"
itself subdivided into further subfolders. Category-level scope filtering (rather than per-file,
given the scale) excluded non-English bilingual dictionaries/phrasebooks, non-English-metalanguage
courses (Spanish/Serbian/Slovak-medium), travel guides, history/culture/literature/poetry volumes,
test-only booklets, fiction/genre reading, and niche specialist jargon.

**~75% of files were scanned image-only with no text layer** — the highest proportion of any
language this project has triaged (SCB ~56%, Hungarian ~50%, Korean ~35%). This single fact drove
most of the run's later cost and duration: the large majority of extraction work required real
vision-reading, not fast `pdftotext` parsing.

### 2026-09-12 — Wave 1 & 2: 63 files, ~772,000 words from clean-text sources alone

Even restricted to the ~31 sources with a genuine text layer, Wave 1+2 alone already exceeded
Hungarian's and Korean's *entire* Phase 1 word counts. This is the first hard evidence in this
project that corpus *size* and corpus *OCR-cleanliness* are largely independent variables — a
large collection can still yield a fast, cheap Phase 1 pass if enough of it has real text layers.

**Five distinct Cyrillic PDF-corruption variants were found within Wave 1 alone** — more than any
prior language found across an entire run: a ЙЦУКЕН-keyboard-layout substitution cipher, a
cp1251-decoded-as-latin1 mojibake, stress-mark-only corruption (base letters fine, only the
pedagogical stress-accent glyph corrupted), a non-uniform-within-file arbitrary 1:1 cipher, and a
narrow single-letter-pair (а/e) homoglyph swap. A sixth (non-decodable, context-dependent
many-to-one OCR garbling on a DJVU) and later a seventh (target-language content embedded as
per-word/per-page *raster images* inside an otherwise-genuine text layer, distinct from any font
cipher) and an eighth (a possible keyboard-layout variant affecting only pedagogically-stressed
vowels mid-word) surfaced across Waves 2-3. All eight are now catalogued in
`datasets/00_Reference_Extraction_Spec.md` as a standing reference for any future Cyrillic-script
language. **The practical lesson reinforced repeatedly: never assume one source's cipher (or lack
of one) predicts another's, and verify 15-20+ known word/gloss pairs before trusting any decode.**

### 2026-09-12/13 — Wave 3: ~1 million words of vision-reading across ~45 prioritized sources

Wave 3 was dispatched in ~10 successive batches of 5-10 subagents each, working through the
prioritized backlog from the triage catalog (slang/register sources first, then remaining course
books and specialist grammars). By the end, every named source in the triage catalog had been at
least touched, with five explicitly-flagged, honestly-documented partial-coverage gaps left open
(large books where a subagent stopped at a clean chapter/unit boundary rather than rushing through
superficially) and a deliberate 3-of-20-volume representative sample of a folk-tale partwork series
(which turned out, on inspection, to be a translated international children's magazine, not a
native Russian folklore collection — a useful reminder that a source's folder name/context doesn't
guarantee its actual content type).

**The non-redundant-supplement pattern earned its keep at unprecedented scale.** By source #20+ in
this run, several general beginner/intermediate courses landed at genuinely **zero new vocabulary
rows** (`048` Living Russian Grammar, `085` Budem znakomy, `089` a Minsk beginner course) — not a
failure, but the expected and correctly-documented outcome once a language's core grammar has
already been covered by 15-20+ independent sources. This is the first time in the project that
"confirmed 100% redundant" became a routine, expected finding rather than a rare edge case,
validating the non-redundant-supplement pattern's design at real scale.

### 2026-09-12/13 — Two mass usage-limit disruptions handled cleanly

**Session-limit event (Wave 1 Batch B, 2 of 14 chunks affected):** one chunk (`020`) turned out
fully complete on disk despite its "failed" status tag; the other (`022`) was genuinely missing and
was cleanly redispatched. **Weekly-limit event (Wave 3 batch, 6 of 8 chunks affected):** the same
disk-state-verification-before-redispatch discipline correctly separated 3 chunks that were
actually complete from 3 with genuine, specific continuation points (confirmed via each partial
file's own closing "continued in..." language or lack thereof). **A third, smaller session-limit
event (2 of 5 chunks in a later batch)** was handled the same way. In every case, the fix was the
same: read the actual file content on disk (not just check existence) before deciding whether a
redispatch was needed, and if so, exactly where it should resume from. This is now a thoroughly
proven pattern across four languages' worth of extraction runs.

### 2026-09-13 — Graphify rebuild: largest graph yet, one fabricated edge caught and fixed

The full 281-file corpus (~1.36M words) was split into 13 semantic-extraction chunks of ~22 files
each — the largest chunk count this project has dispatched for a single graphify rebuild. Result:
769 nodes, 894 edges, 42 communities. The health-check diagnostic found **exactly one dangling-
endpoint edge out of 895** (0.1%) — a subagent had referenced a plausible-sounding node ID
(`established_090_rossiya_den_segodnyashniy_novorussky`) that was never actually created by any
chunk, likely because it expected a sibling chunk to cover that content and assumed the node would
exist. Per the "never fabricate cross-chunk edges" discipline, the edge was removed (not the node
invented) and the graph rebuilt clean. **This is the first time in four languages' worth of
graphify rebuilds that the health check actually caught something** — every prior rebuild (SCB,
Hungarian, Korean) came back clean on the first pass. Worth treating as confirmation that the
health-check step is pulling real weight, not just a formality, once real subagent-fabrication
mistakes are statistically likely to occur at this scale (13 chunks, ~770 nodes).

A second, purely cosmetic node-ID collision was also caught during merge (2 chunks independently
assigned similar IDs to what was actually the same physical book, "How to say about it" — flagged
by one subagent proactively before the merge even ran) — the deduplication step (which keeps the
first-seen node per unique ID) absorbed this without any further intervention needed, since the
two IDs were coincidentally identical rather than actually divergent in this case.

---

## Summary verdict for this test run

The full triage-then-wave-extraction-then-graphify pipeline scales to a corpus roughly 3x larger
than this project's previous largest run (SCB), including surviving three separate usage-limit
disruptions across a single continuous session, without losing data or silently under-reporting
partial coverage. The non-redundant-supplement pattern is now validated as sound at scale — later
sources in a large single-language corpus should be expected to yield diminishing new content, and
"confirmed zero new rows" is a correct, honest outcome rather than a sign something went wrong. The
graphify health-check step caught its first real fabricated edge in four language-scale rebuilds,
validating that step's ongoing value as corpus/chunk-count scale increases. The eight-strong
catalogue of Cyrillic-specific PDF-corruption variants is likely close to exhaustive for this
script/tooling combination and should transfer usefully to any future Cyrillic-script language
(Bulgarian, Ukrainian, Belarusian are all still in the acquisition-gap or not-yet-started list).
