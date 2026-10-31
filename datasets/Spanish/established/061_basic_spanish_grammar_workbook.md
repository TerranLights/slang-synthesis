# Spanish — Established Vocabulary/Grammar: Basic Spanish: A Grammar and Workbook (non-redundant supplement, minimal)

**Source:** María Victoria García, *Basic Spanish: A Grammar and Workbook*, Routledge, 2nd edition.
172 PDF pages, real text layer confirmed via `pdftotext` sample checks (pages 10, body units) — no
vision-reading needed.

## Non-redundant-supplement scope decision

This is an absolute-beginner grammar workbook (20 units: nouns/articles, numbers/dates, present
tense regular/irregular verbs, interrogatives, negatives, adjectives/adverbs, ser/estar,
demonstratives, comparatives/superlatives, object pronouns, gustar, radical-changing verbs, reflexive
verbs, present continuous, possessives, preterite, imperfect, perfect/pluperfect, future). Its scope
is essentially a subset of 005 (*Practice Makes Perfect Basic Spanish Grammar*)'s 50 lessons, which
already cover every one of these topics in comparable or greater depth with its own worked examples.
**This book introduces no new grammar mechanic, no new core vocabulary tier, and no systematic
dialectal annotation scheme** (unlike 016's `(M)` tags or 015's `[B/C/S]`-equivalent markers) — its
occasional Spain-vs-Latin-America notes are scattered one-offs in the answer key and exercises, not a
structured comparative apparatus.

**What was kept and why** (the only genuinely new item found after scanning the full text for
dialect/register markers): a specific possessive-vs-reflexive-article contrast with body parts
(Unit 17 answer key) not previously captured in this corpus's leísmo/possessive coverage.

**What was skipped as redundant:**
- All 20 units' core grammar mechanics (fully covered by 005/006/007/014/015, etc. — see this
  corpus's extensive existing verb-paradigm, pronoun, and ser/estar coverage).
- The leísmo note (Unit 11, p. ~79-80: "more common in Spain, particularly central Spain, than in
  Latin America") — already thoroughly documented in 015 (Schaum's, Ch. 6, p. 134).
- The pronunciation/stress front matter (pp. ix-xiii) — covered by 009/009b-d and others.
- **The 20 end-of-unit "Cultural brief" reading passages** (one per unit: greetings/farewells,
  Spanish fiestas, the Spanish family, the 19 comunidades autónomas, Spanish work schedules, Spanish
  stereotypes [siesta myth], Barcelona, Extremadura, Panama, the Real Academia, Argentina, Spanish
  likes/dislikes, Chile, Costa Rica, immigration and racism in Spain, Ecuador, Camilo José Cela,
  Bolivia, El Quijote, Uruguay). These are general-knowledge country/culture overviews at a very
  basic reading level, not slang/register-annotated vocabulary content, and this exact territory
  (country profiles, Spanish institutions, literary figures) is already covered in more depth
  elsewhere in this corpus (030 Cambridge Companion to Spanish Culture, 031 Cambridge Companion to
  Latin American Culture, 032 Spanish-Speaking World, 038 Speak the Culture Spain, 025 History of the
  Spanish Language). Skipped wholesale as out-of-scope redundant cultural filler rather than
  padded into the vocabulary table.

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| se rompió la pierna (Peninsular) vs. se rompió su pierna (Latin American) | he/she broke his/her leg | reflexive verb construction | regional | — | contemporary (source published, 2nd edition) | Peninsular Spain vs. Latin America | national/transnational | grammar_reference | verified | n/a | Unit 17 (preterite tense) answer key, exercise 4 item 4, with the book's own explicit parenthetical note: "'su pierna' is used in Latin American Spanish, not in Peninsular Spanish." A specific, source-confirmed grammatical (not merely lexical) Peninsular/LatAm contrast — Peninsular Spanish defaults to the definite article (la pierna) with reflexive body-part verbs where possession is understood from context, while the book attests Latin American usage instead using the explicit possessive adjective (su pierna) in the same construction. Not previously captured in this corpus's existing leísmo/possessive-system coverage. |

## Grammar points

### Possessive adjective vs. definite article with reflexive body-part verbs (Unit 17 answer key)

Spanish generally avoids a possessive adjective with body parts when the possessor is already clear
from a reflexive or indirect-object construction (se rompió la pierna = "he broke his leg," literally
"he broke to-himself the leg") — this general rule itself is implicit background knowledge in most
grammars in this corpus. What this book adds that's genuinely new is a **specific, explicitly
source-attested exception**: it flags "se rompió su pierna" as the Latin American variant of the
same sentence, meaning at least some Latin American usage keeps the possessive adjective in this
construction where Peninsular usage drops it for the article. This is a narrow, concrete data point
(one verb, one body part, in an answer key aside) rather than a systematic rule the book develops
further — flagged here as worth cross-checking against a native-speaker query or a larger corpus
before treating it as a general Peninsular/LatAm pattern rather than a possibly idiolectal/regional
one-off.

---

## PDF extraction notes

- **Real text layer confirmed, no vision-reading needed.** `pdftotext -layout` across the whole
  172-page book produced clean, directly usable text throughout.
- No font-substitution cipher, multi-column scrambling, or non-monotonic page ordering observed.
- A full-text scan for dialect/register markers (`latin america`, `peninsular`, `coloquial`, `vulgar`,
  `argot`, `jerga`, `slang`, `dialect`, `register`, `regional`) surfaced only the leísmo note (already
  redundant, see above) and the possessive/reflexive note captured above — confirming this book's
  comparative-dialect content is genuinely thin relative to books like 016 or 015.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of exercise blocks,
answer-key lists, or Cultural Brief reading passages. See `00_Reference_Extraction_Spec.md`. The one
quoted sentence pair above is a short illustrative example drawn from the book's own answer key, not
a reproduction of a larger passage.
