# English — Established Vocabulary/Grammar: Chapter 13, "Quotations and Dialogue," §13.26–13.52
(Part 2 of N)

**Source:** University of Chicago Press Staff (eds.), *The Chicago Manual of Style* (16th ed.,
2010), Chapter 13 "Quotations and Dialogue," online-edition section numbers §13.26 ("Quotation
marks in poems") through §13.52 ("Ellipses with other punctuation"). PDF pages 1632–1658 of the
"foremost primary resources" copy in `source_reference/languages/English Grammar Ebook
collection/`.

**Coverage note:** every grammar point and every distinct piece of editorial/typographic
terminology introduced across §13.26–13.52, plus every explicit register/dialect/cross-language
annotation the source itself marks (see §13.28 and §13.40 below — both flagged per the extraction
spec's coverage rule as directly relevant to this project's slang-synthesis purpose, since they
describe how different language communities punctuate spoken dialogue differently). Repeated
illustrative examples that don't introduce new rule content beyond what's already captured are
skipped — see `../../00_Reference_Extraction_Spec.md` for the full coverage rule. This chunk ends
at §13.52; §13.53 ("Deliberately incomplete sentence") onward falls on PDF page 1659, outside this
chunk's assigned range, and is reserved for a later `044_cmos_ch13_quotations_dialogue_ptNN` (or
`045_...`) part.

**Text layer / mojibake note:** this source has a real, genuine text layer throughout this range
(confirmed via `pdftotext`) — no vision-reading was required, so Vision Reading Confidence is `n/a`
for every entry. As previously confirmed across other chunks of this same book (per the extraction
spec's documented gotcha), this range shows the UTF-8-encoded-text-read-as-Latin-1 mojibake
pattern on two distinct occurrences:

- §13.28 and §13.29: `â€˜` appears four times in place of the left single quotation mark (`'`,
  U+2018) inside nested-quotation examples (e.g., raw `â€˜I mean what I say'` recovered as `'I
  mean what I say'`). Recovered with full confidence — context (a nested-quotation example
  explicitly about single/double quote nesting) makes the intended character unambiguous.
- §13.40: `Â« >>` appears in the phrase "the use of guillemets (Â« >>)". The `Â«` portion matches
  the confirmed mojibake pattern for `«` (U+00AB, left guillemet). The `>>` portion is a distinct,
  less-certain corruption — the two literal greater-than-sign characters do not match the usual
  mojibake pattern and most likely represent a mangled `»` (U+00BB, right guillemet) from the same
  HTML→PDF conversion pass. Recovered as `« »` based on the sentence's own explicit naming of
  "guillemets," which unambiguously identifies the intended punctuation pair — not marked
  `low_confidence` since the source text itself names the characters, removing real doubt about
  which glyphs were meant, even though the exact corruption mechanism for the `»` half is less
  clean than the already-documented `Â«`/`â€˜`-style cases.

No handwritten marginalia of any kind was present on any page in this range (not applicable here
regardless, since the source has a genuine text layer).

**Citation convention for this file:** matching the convention established in earlier
`established/` files for this source (e.g., `012_cmos_ch06_punctuation_pt01.md`), this source's
pages carry no printed page numbers of their own (16th edition online/reflowed layout,
cross-referenced internally by section number). Citations below use the source's own `§N.NN`
section numbers rather than guessed print-page numbers.

---

## Vocabulary

Chapter 13 is a style manual, not a language-pedagogy text, so its "vocabulary" in the sense this
project's extraction spec means is the chapter's own editorial/typographic terminology — the named
concepts it defines or relies on for presenting quotations and dialogue — rather than ordinary
English words drawn from its illustrative example sentences.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| clearing (quotation marks) | the former (now-abandoned) practice of placing a quotation mark outside a line of poetry's left alignment, as if the mark weren't there | noun phrase (named former practice) | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.26; explicitly flagged by the source as a "departure from its former practice" — the 16th edition no longer recommends it, instead aligning opening quotation marks with the rest of the excerpt's lines. |
| run-in (poetry quotation) | presenting two or more lines of poetry within running text (rather than as a set-off block), separated by a slash with a space on either side | noun phrase (named technique) | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.27; the slash gets one space on either side in general use, a thin space to an en space in printed/typeset works. Running in more than one stanza is to be avoided if at all possible (§13.32); when unavoidable, two slashes (`//`) mark the stanza break. |
| single/double quotation-mark nesting (US convention vs. UK convention) | the order in which single and double quotation marks alternate when a quotation contains a quotation within it | noun phrase (named system) | regional | — | contemporary (source published 2010) | American English (United States) — contrasted explicitly with United Kingdom English | national | grammar_reference | n/a | n/a | §13.28; **explicit regional annotation the source itself marks.** US/Chicago default: double marks outer, single marks for a nested quotation, double again for a quotation nested within that, and so on. Source states plainly: "The practice in the United Kingdom and elsewhere is often the reverse: single marks are used first, then double." When quoted material consists entirely of a quotation within a quotation, only one set of marks (usually double) is needed. |
| block quotation *(forward reference — fuller definition at §13.10, outside this chunk)* | quoted material set off from running text (typically by indentation/typeface), not enclosed in quotation marks itself, though quoted matter *within* it still takes double quotation marks as it would in running text | noun phrase | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.29; converting between run-in and block form requires adding/removing/altering quotation marks accordingly — an editor changing a run-in quotation to a block quotation must delete the run-in form's opening/closing marks and adjust any internal nested marks. |
| epigraph | a quotation used as an ornament preceding a text, rather than as illustration or documentation of a point in the text | noun | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.34; not enclosed in quotation marks. Receives distinctive typographic treatment like a block quotation (often smaller typeface, indented from right or left, sometimes italicized); its source line (also usually set on its own line) can vary in treatment, though consistency is expected across one work. Illustrative example given: an unmarked Sir Walter Scott couplet ("Oh, what a tangled web we weave, / When first we practice to deceive!") used as a chapter epigraph. |
| decorative initial ("drop cap" / "raised initial") | a large, stylized first letter opening a chapter or section, either dropped into the text block or raised above the line | noun phrase | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.35; when the first word of a chapter/section opening with one of these is itself a run-in quotation, the opening quotation mark is often simply omitted (worked example: `"OF THE MAKING OF MANY BOOKS there is no end," declared...'` printed with the "O" as the decorative initial and no visible opening quotation mark before it). If the mark is kept instead, it must match the regular text's size/vertical alignment, not the oversized initial's. |
| maxim / motto | a familiar saying, rule, or set expression, sometimes (not always) enclosed in quotation marks | noun | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.36; cross-references §6.51 and §8.197 for the quotation-mark treatment, and §6.52/§6.67 for questions that do *not* require quotation marks — both outside this chunk's page range, so not independently verified here. |
| direct discourse | speech or dialogue reproduced directly (as opposed to paraphrased) and traditionally enclosed in quotation marks | noun phrase | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.37; a speaker change is usually signaled by a new paragraph (illustrative excerpt quoted from *Huckleberry Finn*'s dialect-heavy dialogue). A single speech running longer than one paragraph needs an opening quotation mark at the start of each new paragraph but a closing mark only at the very end (same cross-paragraph rule as §13.30). |
| single-word speech | a bare single word functioning as a response or exclamation (e.g., *yes*, *no*, *where*, *how*, *why*) used outside direct discourse, and therefore left unmarked by quotation marks | noun phrase | core | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.38; contrast pair given: *Ezra always answered yes; he could never say no to a friend* (unmarked) vs. *"Yes," he replied weakly* (marked, because it's direct discourse). |
| suspension points | the same three-spaced-period mark as ellipsis points, but used to indicate faltering, fragmented, or interrupted speech (confusion, insecurity, a trailing-off) rather than omitted quoted material | noun phrase | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.39, §13.48; illustrative examples: *"I . . . I . . . that is, we . . . yes, *we* have made an awful blunder!"* and *"The ship . . . oh my God! . . . it's sinking!" cried Henrietta.* Abrupt interruptions or sudden changes of thought, by contrast, are usually marked with an em dash instead (see §6.84, outside this chunk). |
| em dash (as a dialogue marker, non-English convention) | in some languages, the em dash (rather than quotation marks) is the standard device used to present dialogue | noun phrase (cross-language typographic convention) | regional | — | contemporary (source published 2010) | *(unspecified — source says "in some languages" without naming a specific language or region)* | — | grammar_reference | n/a | n/a | §13.40; **explicit cross-language register/typography annotation**, flagged per the coverage rule as directly relevant to this project's purpose — different language communities mark reported/spoken dialogue with different conventions. Source does not name which languages use this convention here; cross-references §11.34, §11.52, §11.80, §11.121 (outside this chunk's page range) for specifics. |
| guillemets (« ») | angled double punctuation marks (« opening, » closing) used as an alternative to quotation marks for presenting dialogue in some languages | noun (borrowed French term, plural) | regional | — | contemporary (source published 2010) | *(unspecified — source says "some languages" without naming a specific language or region)* | — | grammar_reference | n/a | n/a | §13.40; **explicit cross-language register/typography annotation** (same flag as the em-dash entry above). Source text extracted as "Â« >>" — see this file's mojibake note above for the recovery of this as "« »". Cross-references §11.32, §11.44, §11.52, §11.79, §11.121 (outside this chunk's page range) for specifics on which languages/contexts use guillemets. |
| unspoken discourse (interior monologue) | thought, imagined dialogue, or other interior discourse, which the source allows to be enclosed in quotation marks *or not*, "according to the context or the writer's preference" | noun phrase | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.41; two contrasting illustrative examples given, one with marks (*"I don't care if we have offended Morgenstern," thought Vera*) and one without (*Why, we wondered, did we choose this route?*). A longer illustrative passage from James Joyce's *Ulysses* is cited (not reproduced in full here, per copyright discipline) as an example of interior monologue/stream of consciousness presented with no quotation marks at all. |
| indirect discourse | dialogue that is paraphrased rather than directly quoted | noun phrase | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.43; takes no quotation marks. Illustrative pair: *Tom told Huck they had to do it that way because the books said so.* / *Very well, you say, but is there no choice?* (the second example shows indirect discourse can still read conversationally without being direct quotation). |
| flush-and-hang (indention style) | a paragraph-indention style — the first line is set flush left and subsequent lines are indented (the style typically used for bibliographies and indexes) — also usable for presenting drama dialogue | noun phrase (named style) | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.44; the default for presenting a stage speaker's dialogue, since it makes the speaker's name visually distinct from the speech itself. Interview/discussion transcription (§13.46) may instead prefer ordinary paragraph indention if speaker turns are short and several speakers appear. |
| runover line (verse drama) | a line of dialogue (in quoted verse-drama excerpts) that continues beyond where a shared line of verse was split between two speakers | noun phrase | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.45; indented by one em or more from the line above, the same indention convention used for runover lines in poetry generally (§13.25). Worked example from *Hamlet*: a single line of verse shared between Barnardo and Marcellus, with Horatio's following speech runover-indented beneath it. |
| field notes (pseudonym convention) | unpublished field notes (an author's own, or a colleague's/assistant's), which — unlike published-interview transcriptions — need not be presented verbatim and should instead be edited for consistency with the surrounding text | noun phrase | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.47; otherwise-anonymous subjects/informants should generally be presented under pseudonyms even if the author holds signed releases, with a note appended to the text flagging that pseudonyms are in use. Editors are instructed to query authors if it's unclear whether appropriate anonymization provisions were made. |
| ellipsis / ellipsis points | the omission of a word, phrase, line, or paragraph (or more) from a quoted passage, Chicago-style indicated by three spaced periods | noun | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.48; distinguished by name only from suspension points (same mark, different function — see that entry above): "ellipsis points" for omitted quoted material, "suspension points" for interrupted/faltering speech. Must stay together on one line (via nonbreaking spaces) along with any following punctuation. Chicago will convert an author's single-glyph Unicode ellipsis character (U+2026) to spaced periods during editing. |
| four dots (convention) | the appearance of an ellipsis (three spaced periods) immediately preceded or followed by a retained sentence period, used when an omission follows (or is followed by) a complete grammatical sentence | noun phrase (named convention) | technical.editorial | — | contemporary (source published 2010) | American English (United States) | national | grammar_reference | n/a | n/a | §13.51; what precedes and (normally) what follows the four dots should each be a grammatically complete sentence as quoted. The first word after the ellipsis is capitalized if it begins a new grammatical sentence (bracketed if the work's style requires flagging editorial capitalization changes, per §13.16, outside this chunk). Worked example drawn from Emerson's essay "Politics." |

## Grammar points

### §13.26 — Quotation marks in poems

A departure from the 16th edition's prior practice: Chicago no longer recommends "clearing"
quotation marks at the start of a line of poetry (placing them outside the poem's left alignment as
if they weren't there). Opening quotation marks should instead be aligned with the rest of the
excerpt's lines, flush with the other text.

### §13.27 — Run-in poetry quotations

See the Vocabulary table's "run-in (poetry quotation)" entry. Running in more than one stanza
should be avoided if at all possible (§13.32).

### §13.28 — Quotations and "quotes within quotes"

See the Vocabulary table's nesting-convention entry above for the core US/UK contrast. Additional
rule: question marks and exclamation points belonging to the quoted material go just inside the set
of quotation marks ending the specific element they belong to (worked out in detail in the Alice/Mad
Hatter illustrative example). For the placement of commas, periods, and other terminal punctuation
relative to closing quotation marks generally, the source cross-references §6.9–11 (outside this
chunk).

### §13.29 — Quotation marks in block quotations

See the Vocabulary table's "block quotation" entry. The source works through converting the same
material between run-in and block form in both directions, underscoring that quotation marks must
be added, removed, or altered consistently each time.

### §13.30 — Quotation marks across paragraphs

When quoted material spans more than one paragraph and can't be set as a block quotation (strongly
preferred when possible — §13.10), an opening quotation mark is needed at the start of *each*
paragraph, but a closing mark only at the end of the *final* paragraph. Each successive paragraph
must begin on a new line, matching the original. The same rule governs dialogue when one speaker's
remarks run longer than a single paragraph.

### §13.31 — Quotations within quotations across paragraphs

When a run-in quoted passage itself contains an interior (nested) quotation running more than one
paragraph, a single quotation mark opens and closes the interior quotation, and both single and
double marks appear before each new paragraph belonging to it. If the interior quotation ends at the
same point as the outer one, the single closing mark precedes the double closing mark.

### §13.32 — Running in more than one stanza of poetry

A quotation spanning more than one stanza should, if at all possible, be presented as a block
extract (§13.23) rather than run in. If it must be run in, two slashes (`//`) mark the stanza break,
distinct from the single slash used between ordinary run-in lines (§13.27).

### §13.33 — Running in letters

A letter quoted in full should be set as a block quotation. If (undesirably) it must be run in
instead, opening quotation marks are needed before the first line (including the salutation) and
before each subsequent paragraph; a closing mark appears only after the final line (often the
signature) — the same cross-paragraph logic as §13.30.

### §13.34 — Epigraphs

See the Vocabulary table's "epigraph" entry above.

### §13.35 — Decorative initials ("drop caps" and raised initials)

See the Vocabulary table's "decorative initial" entry above.

### §13.36 — Maxims, questions, and the like

See the Vocabulary table's "maxim/motto" entry above — the fuller treatment of quotation-mark usage
for maxims/mottoes/rules, and of which questions need no quotation marks at all, sits in chapters 6
and 8, outside this chunk's page range.

### §13.37 — Direct discourse

See the Vocabulary table's "direct discourse" entry above.

### §13.38 — Single-word speech

See the Vocabulary table's "single-word speech" entry above.

### §13.39 — Faltering or interrupted speech

See the Vocabulary table's "suspension points" entry above.

### §13.40 — Alternatives to quotation marks

See the Vocabulary table's "em dash (as a dialogue marker, non-English convention)" and "guillemets"
entries above — both explicit cross-language typographic annotations.

### §13.41 — Unspoken discourse

See the Vocabulary table's "unspoken discourse (interior monologue)" entry above.

### §13.42 — Numerals in direct discourse

When quoting directly from spoken sources (interviews, speeches, film/play dialogue) or writing
direct discourse for fiction/drama, numbers that would otherwise be rendered as numerals can often
be spelled out instead — a matter of editorial discretion. Years, and trade names that happen to
include numerals, are usually still rendered as numerals regardless (worked contrast example: *"Do
you prefer shopping at 7-Eleven or Circle K?"* keeps the numeral in the trade name even in spoken
dialogue). Dialogue containing more than a few large numbers may be more practical to render with
numerals outright rather than spelling every one out.

### §13.43 — Indirect discourse

See the Vocabulary table's "indirect discourse" entry above.

### §13.44 — Drama

In plays, a speaker's name is usually set in a font distinct from the dialogue itself (small caps,
or all caps), with the dialogue left unmarked by quotation marks and typically set in flush-and-hang
style (see the Vocabulary table entry). Stage directions are usually italicized. Illustrative
examples quoted: a short *Ralph Roister Doister* exchange (*"R. Roister Doister. Except I have her
to my wife, I shall run mad. / M. Merygreeke. Nay, 'unwise' perhaps, but I warrant you for 'mad.'"*)
and a stage-direction-interleaved line from Wilde's *The Importance of Being Earnest*.

### §13.45 — Shared lines and runover lines in verse drama

See the Vocabulary table's "runover line (verse drama)" entry above.

### §13.46 — Discussions and interviews

Transcribing a discussion or interview is treated much like drama (§13.44). Interjections such as
"[laughs]" are italicized and bracketed (not parenthesized). Ordinary paragraph indention is usually
preferred over flush-and-hang for this case, though flush-and-hang may work better when several
speakers appear with relatively brief remarks (it makes the current speaker easier to identify at a
glance). Speaker names/labels are usually followed by a period, though a colon is an acceptable
alternative. An author's own previously-unpublished interview/discussion transcriptions can
generally be lightly edited (capitalization, spelling, minor grammatical slips) for readability; more
substantial alterations need to be explained in a note or preface. Previously *published*
transcriptions, by contrast, should be quoted exactly as they appear in their original source.

### §13.47 — Field notes

See the Vocabulary table's "field notes (pseudonym convention)" entry above.

### §13.48 — Ellipses defined

See the Vocabulary table's "ellipsis / ellipsis points" entry above. Omissions are made of material
judged irrelevant to the discussion at hand, or occasionally to adjust the grammar of the
surrounding sentence.

### §13.49 — Danger of skewing meaning

Because an elided quotation has been separated from its original context, particular care is needed
to ensure a deletion doesn't lose or misrepresent the sense of the original — a deletion must never
produce a statement alien to the source material, and ellipses should not be used to splice together
two statements that were far apart in the original. Accuracy of sense and emphasis must accompany
accuracy of transcription.

### §13.50 — When not to use ellipsis points

Ellipsis points are normally *not* used (1) before the first word of a quotation, even if the
original sentence's true beginning was omitted; or (2) after a quotation's last word, even if the
original sentence's true end was omitted — unless the sentence is quoted as deliberately incomplete
(§13.53, outside this chunk).

### §13.51 — Ellipses with periods

See the Vocabulary table's "four dots (convention)" entry above.

### §13.52 — Ellipses with other punctuation

Other original punctuation (comma, colon, semicolon, question mark, exclamation point) may precede
or follow three — never four — ellipsis points; whether to retain it depends on whether doing so
aids comprehension or is grammatically required. When the omission precedes a following mark of
punctuation, a nonbreaking space keeps that mark from accidentally carrying over to the start of a
new line (§13.48). Unlike with periods (§13.51), this before/after placement distinction is
genuinely visible with other punctuation marks, since (without bracket-based signaling, §13.56,
outside this chunk) the equivalent distinction with periods tends to go unnoticed by readers.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. Illustrative example sentences quoted above are the source's
own short, individual demonstrations of specific punctuation/dialogue rules (reproduced
individually, not as a bulk block); the longer Emerson "Politics" passage at §13.51 is reproduced
because the source's own worked example depends on showing the full original alongside its elided
version — this is the source's own short essay excerpt (a few sentences), not a bulk reproduction of
an extended work. See `00_Reference_Extraction_Spec.md`.
