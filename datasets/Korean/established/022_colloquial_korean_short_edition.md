# Korean — Established Vocabulary/Grammar: *Colloquial Korean* (alternate scan) — redundancy finding, no new extraction

**Source nominally assigned:** In-Seok Kim, *Colloquial Korean* (Routledge, first published 1996),
`source_reference/languages/Korean/Colloquial Korean/Colloquial Korean.pdf`, all 143 PDF pages
(scanned as two-printed-pages-per-image spreads — see finding below).

**Sibling source being compared against:** In-Seok Kim, *Colloquial Korean: The Complete Course for
Beginners*, `.../Colloquial Korean the complete course for beginners.pdf`, 289 PDF pages (one printed
page per image), independently dispatched in parallel as `established/020`-`021`.

## Relationship between the two files — confirmed identical edition, not a different edition

Per the spec's non-redundant-supplement dispatch pattern, this book was sampled against its sibling
before extracting anything. The sampling was conclusive, not just suggestive:

- **Front matter is page-for-page identical.** Both PDFs' title pages read "Colloquial Korean / The
  Complete Course for Beginners / In-Seok Kim / Routledge." Both copyright pages read identically:
  "First published 1996 by Routledge... © 1996 In-Seok Kim... Illustrations by Rebecca Moy... Typeset
  in Times by Graphicraft Typesetters Ltd, Hong Kong... Printed and bound in Great Britain by St
  Edmundsbury Press Ltd" with the same four ISBNs (`0-415-10804-7` Book / `0-415-10805-5` Cassettes /
  `0-415-28691-3` CDs / `0-415-30628-0` combined course).
- **Table of contents is identical**, same 20 lesson titles/page numbers (Lesson 1 "인사/Greetings"
  p. 27 through Lesson 20 "병원에서/At the hospital" p. 212), same back-matter section list (Key to
  exercises, Korean–English glossary, English–Korean glossary, Glossary of terms used, Grammar
  index p. 275).
- **Body content matches verbatim at a spot-checked page.** The short-edition scan's printed pp.
  28–29 (Lesson 1 vocabulary box + "Addressing Korean adults" section) and the complete-course scan's
  equivalent printed pages contain the same vocabulary list, the same job-title honorific examples
  (선생님/교수님/의사 선생님/박사님 etc.), and the same prose wording.
- **Back cover is identical**, including ISBN `0-415-10804-7`, the same cover-photo credit
  (Bomunsa Temple, Songmo Island, © Catherine Karnow/CORBIS), and the same marketing copy.

**Conclusion: this is not a second/different edition — it is a second scan of the exact same 1996
Routledge print run**, digitized twice by different people/processes. There is no genuinely new or
different content to extract from it relative to the complete-course scan; every vocabulary item,
grammar point, dialogue, and register annotation it contains is also present, page-for-page, in
`established/020`–`021`'s source PDF.

## PDF-scan gotcha worth flagging for future dispatches

This file's assigned PDF (`Colloquial Korean.pdf`, `pdfinfo` reports 143 pages, `Page size: 367.44 x
302.16 pts`, `Producer: libtiff / tiff2pdf`) packs **two printed pages per PDF page** as a landscape
spread (confirmed directly: PDF page ~18 shows printed pages "28" and "29" side by side in one
image). The sibling PDF (`Colloquial Korean the complete course for beginners.pdf`, 289 pages, A4
portrait, `Producer: iText`) is one printed page per PDF page. 143 × 2 ≈ 286, consistent with the
complete-course PDF's 289 pages once front-matter/blank-page padding is accounted for. This is the
same "two-printed-pages-per-scan-image" pattern already documented in
`00_Reference_Extraction_Spec.md` for *Colloquial Serbian* — confirmed recurring on a second,
unrelated language/publisher pairing. Unlike the Serbian case, here it didn't cause a page-range
mis-estimate (this book turned out to be a pure duplicate, so no page range needed to be located at
all) — but it's worth noting as a second confirmed instance of the pattern for whoever plans the next
vision-reading dispatch off this same source folder.

## What was extracted vs. skipped

**Skipped entirely, as fully redundant:** all 20 lessons' vocabulary tables, all grammar-point
writeups, all dialogues, the Introduction (Hangul/sounds), and the back-matter glossaries/grammar
index — all of this is being captured in full from the complete-course scan (`established/020`-`021`)
and re-extracting it here from a lower-resolution duplicate scan of the identical text would add zero
new information while doubling the vocabulary-table row count for no analytical benefit.

**Extracted:** nothing beyond this redundancy finding itself. No vocabulary table follows because
there is no non-redundant vocabulary to report — every term in this book is already scheduled for
capture via the sibling dispatch.

**Note for the orchestrator:** if `established/020`-`021` turn out, once landed, to have been unable
to read a specific page cleanly (faded scan, binding-gutter shadow, or similar vision-reading
difficulty), this file's source PDF is a legitimate independent second copy that could be checked as
a cross-reference for that specific page — the two scans are different physical/digital copies of the
same print, so a defect in one is not guaranteed to recur in the other. That would be a targeted,
page-specific follow-up, not a reason to re-run this dispatch wholesale.

## Vocabulary

*(none — see "What was extracted vs. skipped" above)*

## Grammar points

*(none — see "What was extracted vs. skipped" above)*
