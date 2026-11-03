# Native-Speaker Queries — holding folder

Anything in the grammar-logic analysis that **only a native speaker can settle** gets parked here
instead of being guessed: grammaticality judgments on constructed sentences, prosody, marginal forms,
register/generational/dialect judgments, and cases where two rules predict different outputs.

## Structure — one folder per function, one small file per question

```
native_speaker_queries/
  README.md
  <function>/              e.g. wa_ga/, kosoado/, te_form/
    01_<topic>.md          ← one narrow question each, ~15–25 lines
    02_<topic>.md
    …
```

**Keep each file small enough to hand to one person without overwhelming them** — a few sentences
and one follow-up question, two to five minutes of their time. Do **not** bundle a whole function
into one document. Many small sheets can be distributed across several respondents, asked at
different times, or handed out one at a time as a conversation allows; a single long file gets
abandoned halfway and exhausts the one person willing to help.

Grouping also means a respondent who only knows about one thing — or only has five minutes — can
still contribute.

## The files are SPEAKER-FACING

**Examples, minimal context, and blank space for their notes. That is all.**

Do **not** put in these files:
- what the question is testing, or which theory each answer supports
- what the corpus or any source says
- methodology, reasoning, source disputes, or analysis of any kind

All of that goes in **`../observations.md`**. Analysis inside a query file also risks **leading the
respondent**, which contaminates the answer you are trying to collect.

## Format for an individual sheet

```markdown
# [Topic in the target language] / [Topic in English]

[One line: what you want them to do.]

**About you:** Where you're from: ＿＿＿＿ ｜ Age range: ＿＿＿＿ ｜ Date: ＿＿＿＿

---

*[One line of context, only if the sentences need it to make sense.]*

| # | [Language] | Your notes |
|---|------------|------------|
| a | …          |            |
| b | …          |            |

**[One plain follow-up question, if there is one.]**
```

Group near-identical sentences together — **the difference between them is usually the whole point**,
and a respondent who sees them side by side will comment on it unprompted.

## Discipline

- **Never fill in a judgment speculatively**, not even provisionally. An empty cell is information;
  a guessed cell is contamination that nothing downstream will flag.
- **Always capture region and age band.** Several findings in this project turn on dialect and
  generation. A judgment without that metadata is much less useful.
- **One speaker is an anecdote.** Where a judgment is load-bearing, seek more than one, and record
  disagreement rather than averaging it.
- **Keep the respondent's own wording.** Hedges like "I guess you could, but it sounds like a
  textbook" are often the most informative part.
- **Check the corpus first.** If a question is answerable by searching the extracted material, it
  does not belong here.
- **Record answers in a copy, not the blank.** Keep the blank sheet reusable for the next respondent;
  save returned sheets as e.g. `09_negation__<respondent>.md`.
