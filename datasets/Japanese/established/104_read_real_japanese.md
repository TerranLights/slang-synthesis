# Japanese — Established Vocabulary/Grammar: "Read Real Japanese" family — Index

This is an index/pointer file, not a standalone extraction. It covers three distinct scanned
sources from `source_reference/languages/Japanese/06.Children's Books, Readers/Japanese Readers/`
that share overlapping titles and a common Kodansha-style annotation convention (語/vocabulary,
動/verb-derivation, 注/usage-note boxes), which made an explicit duplicate check necessary before
extraction. Each book's own extraction lives in its own sibling file:

| File | Book | Editor/Author | Publisher, Year | Stories | Source format |
|---|---|---|---|---|---|
| `104b_read_real_japanese_fiction_emmerich.md` | *Read Real Japanese: Fiction — Short Stories by Contemporary Writers* | ed. Michael Emmerich, narrated Matsunaga Reiko | Kodansha International, 2008 | 6 | Scanned PDF, 103 pp., no text layer |
| `104c_read_real_japanese_allyouneed_ashby.md` | *Read Real Japanese: All You Need to Enjoy Eight Contemporary Writers* | Janet Ashby | Kodansha International, 2003 reissue (orig. 1991, Power Japanese series, plain title *Read Real Japanese*) | 8 | Scanned DJVU, 156 bundled pp., no text layer |
| `104d_reading_japanese_with_a_smile_gally.md` | *Reading Japanese with a Smile: Nine Stories from a Japanese Weekly Magazine for Intermediate Learners* | Tom Gally | Japan & Stuff Press, 2007 (revised/expanded from Gally's 1997 Kodansha book *Strange but True: A True-Life Japanese Reader*) | 9 | Scanned PDF, 91 pp., no text layer |

## Duplicate check — resolved, all three are genuinely distinct books

Before dispatching extraction, title/colophon pages were directly rendered and visually compared
for all three sources, because two of them share the literal phrase "Read Real Japanese" and all
three use the same 語/動/注 annotation layout:

- **Emmerich's *Fiction*** (2008) and **Ashby's *All You Need*** (1991/2003) are unrelated books
  published 17+ years apart by different editors, with completely different story lists (Emmerich:
  Kawakami Hiromi, Otsuichi, Kitamura Kaoru, Ishii Shinji, Yoshimoto Banana, Tawada Yōko; Ashby:
  Mori Yōko, Sakamoto Ryūichi, Tawara Machi, Nejime Shōichi, Sakura Momoko, Itō Seikō, Yoshimoto
  Banana, Murakami Haruki). The shared title is coincidental/homage, not a reissue relationship.
  Confirmed via each book's own title page (Emmerich: Kodansha International, "Fiction" tag,
  narrated-by credit; Ashby: stark black cover, "All You Need to Enjoy Eight Contemporary Writers"
  subtitle, 2003 colophon explicitly naming its own 1991 predecessor — *not* Emmerich's book).
- **Gally's *Reading Japanese with a Smile*** is unrelated to both — different author, sourced from
  a weekly magazine column rather than literary anthologies, confirmed via its own title page and
  Contents page (9 chapters, all titled after *Shūkan Asahi* "Dekigotology" column stories, none
  overlapping the other two books' story lists).

No content was skipped as redundant between these three — each was extracted independently in
full per the structure above.

## Shared extraction notes across all three

- **None of the three sources have a usable text layer** — confirmed via `pdftotext`/`pdffonts`
  (zero output, zero embedded fonts) for the two PDFs, and via `djvutxt` (zero output, no `TXTa`
  chunk) for the Ashby DJVU. All three were extracted **100% by vision-reading** rendered page
  images; `Transcription Confidence` is `n/a` throughout, `Vision Reading Confidence` is populated
  per-row on the project's standard three-tier scale.
- **Coverage is representative sampling, not exhaustive**, per the project's standing rule for
  oversized image-only sources (per-source size: 103–156 scanned pages each, ×3 books). Each
  story/chapter was sampled with 2–6 pages/spreads prioritizing the densest annotation apparatus,
  not full-text transcription. See each sibling file's own coverage note for its exact per-story/
  per-chapter page list.
- **New page-order gotcha confirmed on the Gally source** (`104d`): its PDF's physical scan order
  is non-monotonic at the scale of a large contiguous block, not a single displaced leaf — the
  entire back third of the book (chapters 7–9) appears near the front of the PDF file, before the
  book's own front matter and chapters 1–6. Fully mapped and documented in `104d`'s own coverage
  note, as a second confirmed instance of the non-monotonic-page-order pattern first found on
  Japanese's *Zakennayo!* (see `00_Reference_Extraction_Spec.md`).
- **No handwritten marginalia was found in any of the three sources.** Some pages carry printed
  institutional library-ownership stamps in the margin (St. Petersburg College Library, Eckerd
  College Library) — these are not reader marginalia and were excluded from extraction as
  non-content, not flagged as a confidence concern.
- **Register note:** Gally's source (magazine-column-derived, true-crime/gossip "Dekigotology"
  content) skews noticeably more colloquial/taboo than the two literary anthologies — confirmed
  slang/taboo vocabulary (e.g. ホテトル, ノーパン健康法) and multiple colloquial contraction
  patterns (でしょ, -ちゃう, -してる) not typical of a standard graded reader.

## Combined totals (representative-sample scope, not full-book totals)

- Vocabulary rows: 34 (Emmerich) + 71 (Ashby) + 41 (Gally) = **146 rows**
- Grammar-point subsections: 8 (Emmerich) + 9 (Ashby) + 15 (Gally) = **32 subsections**
- Stories/chapters covered: 6 + 8 + 9 = **23 of 23** (all stories in all three books sampled;
  none skipped)
