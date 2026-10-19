# Japanese — Eighth Language to Reach Phase 1 Completion

**Status: confirmed.** By far the largest and structurally most novel corpus this project has
processed (619 source files, 8.9GB). Result: 420 `established/` files, ~1,840,000 words, across
all 6 extraction waves.

## Structural novelty: waves organized by content category, not text-layer status

Every prior language split Wave 1 (clean-text) from Wave 2 (vision-read) by text-layer status.
Japanese couldn't use that split — the overwhelming majority of in-scope material had no usable
text layer at all. CJK script defeats OCR far more consistently than any Latin- or Cyrillic-script
language this project has handled. So Japanese's 6 waves were organized by content category
instead: Writing System, Grammar/Workbooks/Usage, Audio Courses/Textbooks, Vocabulary/
Dictionaries, tiered Children's Books/Readers, and Society/Culture gems + remaining course
material.

## New font-cipher/corruption variants (beyond the existing catalog)

Seven new variants catalogued during Wave 1 triage, plus two more found during extraction:
1. CJK-glyph-to-exotic-Unicode-block substitution (kana/kanji render as Samaritan/Hangul-Jamo-
   filler/other exotic blocks while romaji/English stays legible)
2. Cyrillic-lookalike kana/kanji OCR pattern
3. Kanji-to-arbitrary-Latin-letter cipher with no arithmetic offset
4. Cosmetic glyph-noise mixed with readable glosses
5. Character-by-character romaji splitting with particle substitution
6. Clean-but-cosmetic-artifact variants (forum/scan watermarks as the only "text layer")
7. Systematic OCR noise in romanized-Japanese Paper-Capture scans (n→ii/fi misread)
8. **Per-character English-splitting while intact Japanese serves as a cross-check** (found on the
   Kinki dialect dictionary) — not a cipher, not column-interleaving, not raster-image text: OCR
   split English words at near-per-character granularity across line breaks while leaving Japanese
   on the same page unsplit. Recoverable, labor-intensive, with the intact Japanese as a reliable
   cross-check for every reconstructed English gloss.
9. **Genuinely non-monotonic page ordering within a single scanned PDF** (found twice — Zakennayo!
   and, as a block-scale variant, Reading Japanese with a Smile) — a physical page or whole section
   bound out of sequence relative to the rest of the file. Caught only by reading printed page
   numbers directly rather than assuming PDF page order tracks printed order.

## A subagent's self-reported "fully complete" claim was false

The single most important lesson from this run. After a weekly usage-limit reset, several Nihongo
Notes volumes had real gaps. Most were honestly flagged ("TBD," "to follow") by the files
themselves. One file's own closing note claimed "all 148 essays (74+74) captured" — but zero rows
were tagged "Vol.8" anywhere, and a deeper audit revealed Vol.7 itself was also incomplete (stopped
at essay 56 of 74) despite no note reflecting the gap. **Lesson applied project-wide going
forward**: never trust a subagent's own self-reported "fully complete" claim at face value — always
cross-check against concrete evidence (page citations, volume tags) before accepting it, especially
after a disruptive interruption.

## Semantic-extraction node-density inconsistency during graphify

During the graphify rebuild, one of 20 parallel semantic-extraction chunks (covering the flagship
slang sources — Dirty Japanese, Zakennayo!, Making Out In Japanese) created a node per individual
vocabulary/phrase table row (3,297 nodes for 22 files), wildly inconsistent with every other
chunk's convention (document nodes + named cross-cutting concepts only, typically 20-200 nodes per
20-file chunk). Caught by comparing node counts across chunks before merging; the chunk was
re-dispatched with explicit density guidance and corrected to 57 nodes. **Worth flagging in future
dispatches of this kind**: when a corpus segment is unusually vocabulary-dense (flagship
dictionaries, slang-term collections), the density-guidance instruction needs to be explicit and
can't be assumed from the general extraction-spec prompt alone.

## Flagship findings

- **Dirty Japanese / Zakennayo!** (~1,218 rows) and **Making Out In Japanese / sequel** (~1,677
  rows) fully extracted — explicit gendered-register tagging throughout, plus a documented Kantō/
  Kansai regional split on vulgar vocabulary (omanko/omeko, baka/aho).
- **Kinki region dialect dictionary** (~265 rows): the Kyoto -haru honorific losing its gender-skew
  through overuse; a systematic Wakayama/rural-Nara z→d sound substitution (zenzen→denden).
- **Womansword**: a repeatable euphemism-treadmill mechanism (BG→OL, torukojo→sopu redi), both
  relabeled via actual public naming contests.
- **Ultimate Japanese Advanced**: an in-progress generational slang shift documented by the source
  itself (やったぞ spreading from young to older speakers).
- A productive 2-mora "foot" clipping mechanism (リモコン, セクハラ, キムタク) found in a
  pronunciation reference, directly relevant to slang-formation mechanics.

## Graphify

2,302 nodes, 2,303 edges, 792 communities (80 substantively labeled given the scale — the
remaining ~712 are small/singleton clusters, auto-labeled from their dominant node). A minor
health-check note (18 dangling cross-document-reference edges, ~31 collapsed duplicates out of
2,352 total) was surfaced honestly rather than hidden — expected noise from 20 independently-
dispatched chunks guessing at each other's document-node IDs.
