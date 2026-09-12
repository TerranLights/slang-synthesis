# Russian — *Using Russian: A Guide to Contemporary Usage* (Part 3 of 3)

**Source:** Derek Offord and Natalia Gogolitsyna, *Using Russian: A Guide to Contemporary Usage*,
Cambridge University Press (LaTeX-typeset edition, PDF metadata dated 2005/2008). This is the
**register flagship source** for Russian — it is one of the few sources in this corpus with an
explicit, book-internal register-tagging system (R1 = colloquial/informal, R2 = neutral/standard,
R3 = formal/literary/official, with sub-tags R3a/R3b/R3c for finer official/bureaucratic/rhetorical
shades; D = dialectal).

**Pages covered:** printed pages 325–454 (PDF pages 361–490 of the source file), i.e. the tail of
§9.6 (Verb forms) through the end of Chapter 12 (Stress). This is the last content chunk of the
book: pages 491–529 (PDF) are the book's own back-matter index ("Index of Russian words, phrases
and affixes") and were correctly excluded — confirmed by direct inspection of PDF pages 491–499,
which show alphabetized word/page-number index entries, not prose content.

**Sibling files:** established/022 covers pages 1–180, established/023 covers pages 181–360. This
file picks up immediately after 023 with no page-range overlap.

## Coverage-scope note (read before the tables below)

This chunk is unusually information-dense — 130 PDF pages spanning verb morphology, the entire
prepositions chapter (valency + English-to-Russian rendering), the entire syntax chapter (16
subsections, 11.1–11.16), and the entire stress chapter (12.1–12.5). Two copyright-discipline and
coverage-rule considerations shaped how this was extracted:

1. **Chapter 10.4 ("Rendering of English prepositions in Russian")** and **Chapter 12 ("Stress")**
   are each, in effect, one long structured vocabulary/example box per English preposition or per
   stress-pattern class — exactly the kind of "vocabulary box... reproduced verbatim" the spec's
   copyright-discipline rule forbids bulk-copying. Both chapters were therefore extracted as
   **grammar points** (paraphrased rule + a handful of illustrative example words/phrases each,
   not the source's full example list), rather than as one vocabulary-table row per example.
2. Everything that functions as genuinely new, distinct **lexical inventory** — the prepositions
   themselves (with case government), the verb+preposition idiom lists (10.3), the case-governing
   verb lists (11.1.5/11.1.8/11.1.10), the short-form-only adjectives (11.3), the collective
   numerals/number-nouns (11.4), the 14 verb-of-motion pairs (11.7), and the conjunctions (11.12)
   — **is** captured in full in the Vocabulary table below, since these are compact, finite,
   genuinely enumerable lists (not repeated drills).
3. **Every explicit R1/R2/R3(/D) register annotation found in this page range is captured**,
   either as its own vocabulary row or flagged in the Notes column of the row it attaches to — this
   was treated as the highest-priority content per the coverage rule, given this book's register
   focus.

No handwritten marginalia was encountered; the PDF has a genuine text layer throughout this range.

### PDF-extraction gotcha found and fixed: Latin-glyph substitution cipher for Cyrillic а/е

This source's PDF font renders **only** two Cyrillic letters — а (U+0430) and е (U+0435) — as their
visually-identical Latin lookalikes (Latin `a` U+0061, Latin `e` U+0065) under `pdftotext`, while
every other Cyrillic letter in the same words extracts correctly as native Cyrillic. E.g. raw
`pdftotext -layout` output gives "бeжи́шь" (with Latin `e`) for what is actually бежи́шь (native
Cyrillic е), and "дaшь" for дашь. This is a narrower variant of the "fixed font-substitution cipher"
pattern already documented in `00_Reference_Extraction_Spec.md` for other Cyrillic PDFs in this
corpus — here the substitution affects exactly two letters rather than the whole alphabet. It was
confirmed character-by-character (codepoint inspection) against several dozen words before
trusting it, and mechanically corrected by replacing Latin `a`/`e` with Cyrillic а/е **only inside
tokens that already contain at least one native Cyrillic letter**, leaving genuine English words
and glosses untouched. All Cyrillic in this file has been corrected accordingly.

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| **Prepositions — accusative-governing (10.1.2)** | | | | | | | | | | | |
| в/во | into, to, in (movement); at a time/age; on a weekday; dimension; pattern | preposition + acc | core | — | contemporary (source publ. 2005) | — | — | grammar_reference | n/a | n/a | also governs prep. case (locative) |
| за | behind/beyond (movement); for (exchange); during; after/over an age; distance in space/time | preposition + acc | core | — | contemporary | — | — | grammar_reference | n/a | n/a | also governs instr. |
| на | on to (movement); to certain nouns (10.1.6); for a period; for a purpose; by a margin | preposition + acc | core | — | contemporary | — | — | grammar_reference | n/a | n/a | also governs prep. |
| о | against, in contact with (о́ ка́мень) | preposition + acc | core | — | contemporary | — | — | grammar_reference | n/a | n/a | also governs prep. |
| по | up to a point in space/time (стоя́ть по ше́ю) | preposition + acc | core | — | contemporary | — | — | grammar_reference | n/a | n/a | primarily a dative preposition |
| под | under (movement); towards/just before (temporal); to a sound; in imitation of | preposition + acc | core | — | contemporary | — | — | grammar_reference | n/a | n/a | also governs instr. |
| про | about/concerning (R1); + себя́ = to oneself | preposition + acc | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 tag in source |
| с | approximately, about (measurement/time) | preposition + acc | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | this usage marked R1-flavoured by source; с primarily governs gen./instr. |
| сквозь | through (difficult passage) | preposition + acc | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| через | across/through/over; in (time from now); via; through an intermediary; every other (alternation) | preposition + acc | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| **Prepositions — genitive-governing (10.1.3)** | | | | | | | | | | | |
| без | without; minutes before the hour | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ввиду́ | in view of | preposition + gen | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | source notes "rather formal" |
| вдоль | along (adhering to a line) | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| вместо | instead of, in place of | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | not to be confused with вме́сте, together |
| вне | outside (as opposed to inside) | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | narrower than Eng. "outside" |
| внутри́ | inside (location) | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | itself a prepositional-case form |
| внутрь | inside (movement) | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | itself an accusative-case form |
| во́зле | by, near | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| вокру́г | round | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| впереди́ | in front of, ahead of | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| всле́дствие | because of, owing to | preposition + gen | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| для | for (benefit/purpose) | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | narrower than Eng. "for" |
| до | before/until (temporal); up to/as far as (spatial) | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| из | out of (movement); origin/material; a proportion out of a whole; resulting from an experience | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| из-за | out from behind; because of (unfavourable cause) | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| из-под | out from under; the purpose an object was designed for | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| кро́ме | except, apart from | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ме́жду | between | preposition + gen/instr | core | — | contemporary | — | — | grammar_reference | n/a | n/a | genitive only in a few fixed phrases; otherwise instr. |
| ми́мо | past | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| напро́тив | opposite | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| насчёт | about, as regards | preposition + gen | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| о́коло | near, by; around/about/approximately | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| от (ото) | away from; distance; source; letter date; purpose; countering sth; caused-by; emotional-state cause | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| относи́тельно | concerning | preposition + gen | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | source: "formal, used mainly in R3" |
| поми́мо | besides, apart from | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по́сле | after | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| посреди́ | in the middle of | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| посре́дством | by means of, by dint of | preposition + gen | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| про́тив | against | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| путём | by means of, by dint of | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ра́ди | for the sake of | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| с (со) | off/down from; since; from (result); with (basis); from (grief) | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | also governs acc./instr. |
| сверх | on top of, over and above | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| свы́ше | over, more than (numerical) | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| среди́ | among, amid | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| у | by (near); at (chez); possession (У нас есть...); +pronoun in R1 for "my"; pain/discomfort; dispossession | preposition + gen | core | — | contemporary | — | — | grammar_reference | n/a | n/a | one usage explicitly marked R1 |
| **Prepositions — dative-governing (10.1.4)** | | | | | | | | | | | |
| благодаря́ | thanks to | preposition + dat | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| вопреки́ | despite, contrary to | preposition + dat | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| к (ко) | towards/up to (spatial); by/towards (temporal); attitude-marking; misc. fixed phrases | preposition + dat | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по | along/down; round about; according to; by means of communication; in the field of; on weekdays (regular); distributively; "for" (в inconsistency) | preposition + dat | core | — | contemporary | — | — | grammar_reference | n/a | n/a | commonest dative preposition |
| подо́бно | like, similar to | preposition + dat | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| согла́сно | in accordance with | preposition + dat | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | source: "official in tone, characteristic of R3b" |
| **Prepositions — instrumental-governing (10.1.5)** | | | | | | | | | | | |
| за | behind, beyond; at/over (за столо́м) | preposition + instr | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ме́жду | between | preposition + instr | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| над (надо) | over, above, on top of | preposition + instr | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пе́ред (передо) | in front of/before (spatial); before (temporal, esp. shortly before) | preposition + instr | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| под (подо) | under/below (location); with a certain dressing (culinary); in the region of; "of" in battle names | preposition + instr | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| с (со) | with (accompaniment); inclusive "and" (мы с бра́том); "what's the matter with..."; with passage of time | preposition + instr | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| **Prepositions — prepositional/locative-governing (10.1.6)** | | | | | | | | | | | |
| в (во) | in/at (location); distance; time (month/year/decade/etc.); half past; describing attire | preposition + prep | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| на | on/in/at (location incl. many "event" nouns — ве́чер, вокза́л, заво́д, ле́кция, etc.); compass points/islands/former-USSR mountain regions; transport-associated activity nouns | preposition + prep | core | — | contemporary | — | — | grammar_reference | n/a | n/a | full noun list at 10.1.6 is a closed, memorizable set |
| о (об, обо) | about, concerning; describing properties (rare) | preposition + prep | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по | after/on completion of (mostly with verbal nouns) | preposition + prep | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | source: "literary or official, confined to R3, esp. R3b" |
| при | at the time of; adjacent/attached to; in the presence of; given the availability of; while (R3, ~ gerund) | preposition + prep | core | — | contemporary | — | — | grammar_reference | n/a | n/a | one sub-sense explicitly marked R3 |
| **Prepositional phrases based on nouns (10.2, official register)** | | | | | | | | | | | |
| в де́ле + gen | in the matter of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | source groups all 10.2 items as "feature of the official register" |
| в отли́чие от + gen | unlike, in contrast to | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| в отноше́нии + gen | in respect of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| в связи́ с + instr | in connection with | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| в си́лу + gen | by virtue of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| в соотве́тствии с + instr | in accordance with | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| в тече́ние + gen | in the course of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| в це́лях + gen | with the object of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| за счёт + gen | at the expense of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| на основа́нии + gen | on the basis of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по ли́нии + gen | through the channel of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по направле́нию к + dat | in the direction of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по отноше́нию к + dat | with respect to | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по причи́не + gen | by reason of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по слу́чаю + gen | by reason of | prepositional phrase | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| **Verb + preposition idioms (10.3)** | | | | | | | | | | | |
| ве́рить/пове́рить в | to believe in | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| вме́шиваться/вмеша́ться в | to interfere, intervene in | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| вторга́ться/вто́ргнуться в | to invade | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| игра́ть в | to play (game/sport) | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cf. игра́ть на = play instrument |
| одева́ть(ся)/оде́ть(ся) в | to dress (oneself) in | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| поступа́ть/поступи́ть в | to enter (an institution) | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| превраща́ть(ся)/преврати́ть(ся) в | to turn/be turned into | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| стреля́ть в | to shoot at (fixed target) | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cf. стреля́ть по = moving target |
| брать/взять за́ руку | to take sb by the hand | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | idiom, "taking hold of" group |
| держа́ться за | to hold on to | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| хвата́ть/схвати́ть за ши́ворот | to seize by the scruff of the neck | verb + prep(acc) | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| боро́ться за | to fight/struggle for | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| заступа́ться/заступи́ться за | to stand up/plead/intercede for sb | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пить/вы́пить за | to drink to (sb's health) | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| сража́ться/срази́ться за | to fight for | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| гляде́ть/погляде́ть на | to look at | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| дели́ть/раздели́ть на | to divide into | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| жа́ловаться/пожа́ловаться на | to complain of | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| наде́яться на | to hope for, count/rely on | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| напада́ть/напа́сть на | to attack, fall upon | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| отвеча́ть/отве́тить на | to reply to | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| полага́ться/положи́ться на | to count/rely on | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| серди́ться/рассерди́ться на | to be angry/cross with | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| смотре́ть/посмотре́ть на | to look at | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| соглаша́ться/согласи́ться на | to agree to (a plan; ≠ agree with a person) | verb + prep(acc) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| состоя́ть из | to consist of | verb + prep(gen) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| стреля́ть из | to shoot, fire (a weapon) | verb + prep(gen) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| отка́зываться/отказа́ться от | to refuse, decline, turn down | verb + prep(gen) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| отлича́ться/отличи́ться от | to differ from | verb + prep(gen) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| страда́ть от | to suffer from (temporary/slight) | verb + prep(gen) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cf. страда́ть + instr for chronic condition |
| начина́ть(ся)/нача́ть(ся) с | to begin with sth | verb + prep(gen) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| сбива́ть/сбить спесь с | to take sb down a peg | verb + prep(gen) | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | idiom |
| относи́ться/отнести́сь к | to relate to, have an attitude to | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| подходи́ть/подойти́ к | to approach, match, suit | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| приближа́ться/прибли́зиться к | to approach, draw near to | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| привлека́ть/привле́чь к | to attract to | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| привыка́ть/привы́кнуть к | to get used/grow accustomed to | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| прилипа́ть/прили́пнуть к | to stick/adhere to | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| прислоня́ться/прислони́ться к | to lean against | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| присоединя́ться/присоедини́ться к | to join | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| стреми́ться к | to strive towards, aspire to | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| скуча́ть по | to miss sb/sth | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| стреля́ть по | to shoot at (moving/random target) | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cf. стреля́ть в = fixed target |
| суди́ть по | to judge by sth | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| тоскова́ть по | to long for sb/sth | verb + prep(dat) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| идти́/пойти́ за | to go for, fetch | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| наблюда́ть за | to supervise | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| надзира́ть за | to supervise | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| присма́тривать/присмотре́ть за | to look after, keep an eye on | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| следи́ть за | to track, shadow, follow, keep an eye on | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| сле́довать/после́довать за | to go after, follow | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cf. сле́довать + dat = follow/emulate |
| уха́живать за | to court, look after, tend to | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| возвыша́ться/возвы́ситься над | to tower over | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| госпо́дствовать над | to dominate, tower above | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| издева́ться над | to mock | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| рабо́тать над | to work at/on | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| смея́ться над | to laugh at | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| извиня́ться/извини́ться пе́ред | to apologise to | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| преклоня́ться/преклони́ться пе́ред | to admire, worship | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| встреча́ться/встре́титься с | to meet (by arrangement) | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| здоро́ваться/поздоро́ваться с | to greet, say hello to | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| знако́миться/познако́миться с | to meet, get acquainted with | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| проща́ться/попроща́ться с | to say goodbye to | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| расстава́ться/расста́ться с | to part with | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| сове́товаться/посове́товаться с | to consult | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ссо́риться/поссо́риться с | to quarrel with | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ста́лкиваться/столкну́ться с | to collide with, run into | verb + prep(instr) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| нужда́ться в | to need, be in need of | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| обвиня́ть/обвини́ть в | to accuse of | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| признава́ться/призна́ться в | to confess, own up to | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| сомнева́ться в | to doubt, question | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| убежда́ть(ся)/убеди́ть(ся) в | to convince/be convinced of | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| уверя́ть/уве́рить в | to assure of | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| уча́ствовать в | to participate, take part in | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| жени́ться на | to get married to (man marrying woman) | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| остана́вливаться/останови́ться на | to dwell on (topic) | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ска́зываться/сказа́ться на | to tell on, have an effect on | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| жале́ть о | to regret, be sorry about | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| забо́титься/позабо́титься о | to worry about | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| мечта́ть о | to dream about | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| расска́зывать/рассказа́ть о | to recount, relate, tell | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| сообща́ть/сообщи́ть о | to inform about | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| узнава́ть/узна́ть о | to find out about, discover | verb + prep(prep) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| **Verbs governing the genitive (11.1.5)** | | | | | | | | | | | |
| боя́ться | to fear, be afraid of | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | R1 note: may take acc. of an animate noun in R1 |
| избега́ть/избежа́ть | to avoid | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| опаса́ться | to fear, shun, avoid | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пуга́ться/испуга́ться | to be afraid of | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| стесня́ться/постесня́ться | to be shy of | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| стыди́ться/постыди́ться | to be ashamed of | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| алка́ть | to hunger for, crave | verb | literary | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag; impf. only |
| держа́ться | to keep to, hold on to | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| добива́ться/доби́ться | to strive for / to get, procure | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | aspect pair differs in meaning |
| достига́ть/дости́гнуть | to attain, achieve | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| заслу́живать | to deserve | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| каса́ться/косну́ться | to touch, concern | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| лиша́ть/лиши́ть | to deprive sb of sth | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| лиша́ться/лиши́ться | to lose, be deprived of | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| слу́шаться/послу́шаться | to obey | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | R1 note: may take acc. of animate object |
| сто́ить | to be worth | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | takes acc. when meaning "to cost" |
| дожида́ться/дожда́ться | to wait until | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | gen. or acc. — gen. tends abstract/general object |
| ждать/подожда́ть | to wait for, expect | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| иска́ть | to look for, seek | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ожида́ть | to expect | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| проси́ть/попроси́ть | to ask for | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| тре́бовать/потре́бовать | to require, need | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| хоте́ть/захоте́ть | to want | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| **Verbs governing the dative (11.1.8)** | | | | | | | | | | | |
| вреди́ть/повреди́ть | to injure, harm, hurt | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | поврежда́ть/повреди́ть (damage/injure) takes acc. instead |
| грози́ть | to threaten | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | impf. only |
| запреща́ть/запрети́ть | to forbid, prohibit | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | takes acc. when the thing (not person) is forbidden |
| изменя́ть/измени́ть | to betray | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | takes acc. when meaning "to change, alter" |
| меша́ть/помеша́ть | to prevent, hinder, bother, disturb | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| позволя́ть/позво́лить | to allow, permit | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| помога́ть/помо́чь | to help | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| препя́тствовать/воспрепя́тствовать | to obstruct | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| противоре́чить | to contradict | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | impf. only |
| разреша́ть/разреши́ть | to allow, permit | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | takes acc. when the thing is allowed |
| служи́ть/послужи́ть | to serve | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| сове́товать/посове́товать | to advise | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| сопротивля́ться | to resist | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | impf. only |
| спосо́бствовать/поспосо́бствовать | to assist, promote, contribute to | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ве́рить/пове́рить | to believe, give credence to | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | ве́рить в + acc = believe in |
| зави́довать/позави́довать | to envy | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cannot take direct obj. of thing envied, unlike Eng. |
| изумля́ться/изуми́ться | to be astonished at | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ра́доваться/обра́доваться | to rejoice at, be gladdened by | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| сочу́вствовать | to sympathise with | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | impf. only |
| удивля́ться/удиви́ться | to be surprised at | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| веле́ть | to order, command | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | impf. and pf. |
| звони́ть/позвони́ть | to ring, telephone | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| льстить/польсти́ть | to flatter | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | reflexive-pronoun idiom takes acc. instead |
| повинова́ться | to obey | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | impf.; also pf. in past tense |
| подража́ть | to imitate | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | impf. only |
| прика́зывать/приказа́ть | to order | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| принадлежа́ть | to belong to | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | + к + dat when meaning "be a member of" |
| сле́довать/после́довать | to follow (in sense of emulate) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | "go after" sense takes за + instr instead |
| соотве́тствовать | to correspond to | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | impf. only |
| учи́ть/научи́ть | to teach | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | dative = subject taught; cf. изуча́ть/изучи́ть (acc.) = to study |
| учи́ться/научи́ться | to learn (a subject) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| рад/ра́да/ра́ды | glad | short-form-only adjective | core | — | contemporary | — | — | grammar_reference | n/a | n/a | takes dative complement |
| **Verbs governing the instrumental (11.1.10)** | | | | | | | | | | | |
| владе́ть | to command, master, own | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | no pf. by nature |
| дирижи́ровать | to conduct (orchestra) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| заве́довать | to be in charge of, manage, run | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| кома́ндовать | to command (armed forces) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| облада́ть | to possess | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по́льзоваться/воспо́льзоваться | to use, make use of, enjoy | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | cf. испо́льзовать (no pf) = takes acc. |
| пра́вить | to govern, rule, drive (vehicle) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| располага́ть | to have at one's disposal | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| распоряжа́ться/распоряди́ться | to manage, deal with | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| руководи́ть | to manage, direct | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| управля́ть | to govern, rule, drive (vehicle) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| восхища́ться/восхити́ться | to admire (be impressed by) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| горди́ться | to be proud of | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | no pf. |
| дорожи́ть | to value, prize | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | no pf. |
| интересова́ться/заинтересова́ться | to be interested in | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| любова́ться/полюбова́ться | to admire (enjoy looking at) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| наслажда́ться/наслади́ться | to enjoy | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пренебрега́ть/пренебре́чь | to ignore, neglect | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| увлека́ться/увле́чься | to be fond of, be carried away by, obsessed with | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| хва́статься/похва́статься | to boast of | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| бряца́ть це́пью | to rattle/clank a chain | verb + instr idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | body-movement idiom set |
| виля́ть/вильну́ть хвосто́м | to wag its tail | verb + instr idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| кача́ть/покача́ть голово́й | to shake one's head | verb + instr idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| кива́ть/кивну́ть голово́й | to nod one's head | verb + instr idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| маха́ть/махну́ть руко́й | to wave one's hand | verb + instr idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пожима́ть/пожа́ть плеча́ми | to shrug one's shoulders | verb + instr idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | acc. used if the body part belongs to someone else |
| то́пать/то́пнуть ного́й | to stamp one's foot | verb + instr idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| хло́пать/хло́пнуть две́рью | to slam a door | verb + instr idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| дыша́ть | to breathe | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | no pf. |
| же́ртвовать/поже́ртвовать | to sacrifice | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| занима́ться/заня́ться | to be engaged/occupied with, study | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| злоупотребля́ть/злоупотреби́ть | to abuse | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| па́хнуть | to smell of (impersonal) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | impf. only |
| рискова́ть | to risk, hazard | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | no pf. |
| страда́ть | to suffer from (chronic, + instr) | verb | core | — | contemporary | — | — | grammar_reference | n/a | n/a | no pf.; contrast страда́ть от = temporary |
| **Short-form-only predicative adjectives (11.3)** | | | | | | | | | | | |
| винова́т/-а/-о/-ы | guilty | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| гото́в/-а/-о/-ы | ready | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| далёк/далека́/далеко́/далеки́ | far, distant | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| дово́лен/дово́льна/-о/-ы | satisfied with | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| до́лжен/должна́/-о/-ы | bound to, must | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| досто́ин/досто́йна/-о/-ы | worthy of | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| наме́рен/-а/-о/-ы | intending to | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ну́жен/нужна́/ну́жно/нужны́ | necessary | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| похо́ж/похо́жа/-е/-и | like, similar | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| прав/права́/пра́во/пра́вы | right | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| свобо́ден/свобо́дна/-о/-ы | free | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| скло́нен/скло́нна/-о/-ы | inclined to | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| согла́сен/согла́сна/-о/-ы | agreeable to | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| спосо́бен/спосо́бна/-о/-ы | capable of | adjective (short-only) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| **Collective numerals and number-nouns (11.4.5, 11.4.13)** | | | | | | | | | | | |
| дво́е | two (collective, of people/pluralia-tantum nouns) | numeral | core | — | contemporary | — | — | grammar_reference | n/a | n/a | во́сьмеро, де́вятеро, де́сятеро obsolete per source |
| тро́е | three (collective) | numeral | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| че́тверо | four (collective) | numeral | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пя́теро | five (collective) | numeral | core (dated) | — | contemporary | — | — | grammar_reference | n/a | n/a | source: no longer commonly used in all contexts |
| ше́стеро | six (collective) | numeral | core (dated) | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| се́меро | seven (collective) | numeral | core (dated) | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| дво́йка | a two (digit/tram no./card/lowest-pass school mark) | noun, f. | core | — | contemporary | — | — | grammar_reference | n/a | n/a | number-noun set, 11.4.13 |
| тро́йка | a three; also a three-horse carriage | noun, f. | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| четвёрка | a four | noun, f. | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пятёрка | a five (top school mark) | noun, f. | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| шестёрка | a six | noun, f. | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| семёрка | a seven (e.g. of cards) | noun, f. | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| восьмёрка | a eight; also an eight (rowing) | noun, f. | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| девя́тка | a nine | noun, f. | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| деся́тка | a ten | noun, f. | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| **Verbs of motion — the 14 imperfective indeterminate/determinate pairs (11.7)** | | | | | | | | | | | |
| ходи́ть / идти́ | to walk, go on foot | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | indeterminate/multidirectional vs. determinate/unidirectional |
| е́здить / е́хать | to travel, go by transport | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| бе́гать / бежа́ть | to run | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| лета́ть / лете́ть | to fly | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пла́вать / плыть | to swim, float, sail | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по́лзать / ползти́ | to crawl | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| носи́ть / нести́ | to carry (by hand) | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| води́ть / вести́ | to take, lead | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| вози́ть / везти́ | to take (by transport), convey | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ла́зить / лезть | to climb | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| гоня́ть / гнать | to drive, pursue | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| ката́ть / кати́ть | to roll, push | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| таска́ть / тащи́ть | to pull | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| броди́ть / брести́ | to wander, amble | verb (motion pair) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | брести́ can connote slowness/difficulty |
| **Conjunctions (11.12) — including explicit register tags** | | | | | | | | | | | |
| и | and | coordinating conjunction | core | — | contemporary | — | — | grammar_reference | n/a | n/a | omissible in lists in sedate narrative style |
| а | but/and (contrastive) | coordinating conjunction | core | — | contemporary | — | — | grammar_reference | n/a | n/a | stronger opposition than но |
| но | but | coordinating conjunction | core | — | contemporary | — | — | grammar_reference | n/a | n/a | weaker, limiting sense vs. а |
| и́ли | or | coordinating conjunction | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| да | and (N. dialect) | coordinating conjunction | colloquial.regional | — | contemporary | Northern Russia (dialect) | regional | grammar_reference | n/a | n/a | explicit R1, "esp. in N dialects" |
| да и | and besides, and what is more | coordinating conjunction | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 |
| а то | otherwise, or else | coordinating conjunction | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 |
| ли́бо | or | coordinating conjunction | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 |
| потому́ что | because | subordinating conjunction (causal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| так как | since, as | subordinating conjunction (causal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| по́сле того́, как | after | subordinating conjunction (temporal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | contrast preposition по́сле |
| пока́ | while | subordinating conjunction (temporal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пока́ не | until | subordinating conjunction (temporal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | followed by perfective verb |
| с тех пор, как | since | subordinating conjunction (temporal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| как то́лько | as soon as | subordinating conjunction (temporal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| едва́ | no sooner...than | subordinating conjunction (temporal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| пре́жде чем | before | subordinating conjunction (temporal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| до того́, как | before | subordinating conjunction (temporal) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| что́бы | so that, in order that | subordinating conjunction (purposive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | past tense if different subjects, infin. if same |
| так что | so that (resultative) | subordinating conjunction (resultative) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| до того́... что | to such an extent that | subordinating conjunction (resultative) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| хотя́ | although | subordinating conjunction (concessive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| тогда́ как | whereas | subordinating conjunction (concessive) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| е́сли | if | subordinating conjunction (conditional) | core | — | contemporary | — | — | grammar_reference | n/a | n/a | |
| раз | if | subordinating conjunction | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 tag |
| благодаря́ тому́, что | thanks to the fact that | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| в связи́ с тем, что | in connection with the fact that | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| в си́лу того́, что | by virtue of the fact that | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| ввиду́ того́, что | in view of the fact that | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| всле́дствие того́, что | owing to the fact that | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| и́бо | for | subordinating conjunction | literary | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag; illustrative Tolstoi quote in source |
| невзира́я на то, что | in spite of the fact that | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| по ме́ре того́, как | in proportion as | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| посто́льку, поско́льку | insofar as, to the extent that | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| при усло́вии, что | on condition that | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| с тем что́бы | with a view to (doing) | subordinating conjunction | formal | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 tag |
| бу́де / да́бы | if, provided that (= что́бы) | subordinating conjunction | archaic | — | contemporary | N. dialects (бу́де) | regional | grammar_reference | n/a | n/a | source: obsolete/dialectal |
| доко́ле (доко́ль) | as long as, until | subordinating conjunction | archaic | — | contemporary | — | — | grammar_reference | n/a | n/a | obsolete in modern literary language |
| е́жели | if (= е́сли) | subordinating conjunction | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | possible in R1 |
| ко́ли | if | subordinating conjunction | colloquial.regional | — | contemporary | — | regional | grammar_reference | n/a | n/a | possible in R1, esp. dialect |
| коль ско́ро | so long as | subordinating conjunction | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | possible in R1 |
| пока́мест | while (= пока́) | subordinating conjunction | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | possible in R1 |
| **Other explicit register-tagged items encountered in running text (R1/R3, not already listed above)** | | | | | | | | | | | |
| алка́ть | to hunger for, crave | verb | literary | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3; duplicate cross-ref of 11.1.5 entry above |
| без-вести (пропа́сть бе́з вести) | to go missing (in action) | idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | stress-attracting preposition idiom, 12.2.5 |
| зазнава́ться/зазна́ться | to get above oneself | verb | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 (10.4, ABOVE) |
| отню´дь не | by no means | adverbial phrase | literary | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R3 (10.4, BY) |
| потихо́ньку | on the quiet, quietly | adverb | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 (10.4, ON) |
| спя́тить с ума́ | to go off one's rocker | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 (10.4, OFF) |
| со ску́ки (от зло́сти) | out of boredom / out of spite | idiom | colloquial/core | — | contemporary | — | — | grammar_reference | n/a | n/a | c + gen for cause explicitly marked R1; от зло́сти marked R2 |
| на ста́рости лет | in one's old age | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 (10.4, IN) |
| по-мо́ему | in my opinion | adverb | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1/2 (10.4, IN) |
| взять у кого́-н почита́ть | to borrow (a book) off sb | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 (10.4, OFF) |
| c неде́лю | about a week | idiom (approximation) | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 (10.4, ABOUT); с + acc for approximation |
| из-за + от + gen (из/от жа́лости) | out of pity | idiom | core | — | contemporary | — | — | grammar_reference | n/a | n/a | из and от both possible |
| -ка (particle) | softening particle attached to imperative | particle | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 (11.5.6); e.g. иди́-ка |
| Bам письмо́ | There's a letter for you | idiom | colloquial | — | contemporary | — | — | grammar_reference | n/a | n/a | explicit R1 (10.4, FOR) |

---

## Grammar points

### §9.6.10 Formation of the past tense
Russian past tense has only four forms (m/f/n/pl), distinguished by gender/number, not person.
Masculine ends in -л or another hard consonant; f/n/pl add -ла/-ло/-ли to the masculine stem. Nine
sub-patterns are given depending on infinitive shape: vowel+ть→-л/-ла/-ло/-ли (чита́ть→чита́л);
-зти́/-зть verbs lose -ти́/-ть (везти́→вёз); -сти́ verbs with б/с-stems use the present/future
consonant (грести́→грёб); -сть/-сти́ verbs with д/т-stems replace the consonant with -л
(вести́→вёл); -чь verbs use the 1sg present-tense velar (бере́чь→берёг); идти́ is suppletive
(шёл/шла/шло/шли); -ере́ть verbs lose final -е́ть (умере́ть→у́мер); some stressed -нуть verbs lose
the suffix in the masculine form only (dropping it entirely is now more common; retaining it "has
an archaic flavour" — an explicit archaic-register note); ошиби́ться/ушиби́ться are irregular.

### §9.6.11 Formation of the imperative
Formed from the 3pl present/future stem: -й after a vowel; -и after a single consonant with
end-stressed 1sg (or after 2+ consonants regardless of stress); -ь after a single consonant with
stem-stressed 1sg. A handful of common verbs (monosyllabic -ить verbs, 1B verbs in -ава́ть,
е́хать/пое́хать, дать, есть, лечь) have irregular imperatives. Notably, the source gives an
explicit table of verbs with **distinct R2/3 vs. R1/D imperative forms** (e.g. вы́йти → standard
вы́йди vs. colloquial/dialectal вы́дь; пойти́ → standard пойди́ vs. colloquial поди́) — a direct
register-contrast data point. The reflexive particle -ся reduces to -сь after -и and after -те.

### §9.7.1–9.7.6 Formation of gerunds and participles
Imperfective gerunds: replace the last two letters of 3pl present with -я (-a after hushing
consonants); many verb classes (1B in -зать/-сать, monosyllables in -ить, verbs in -чь/-нуть, and
some miscellaneous common verbs) cannot form one directly and borrow from a cognate 1A verb
instead. Perfective gerunds: usually replace masculine past-tense -л with -в (rarely -вши, which
"has an archaic flavour" and may occur in R1/D); a few classes use -ши or a future-stem + -я.
Present active participles (imperfective verbs only) replace 3pl -т with -щий. Past active
participles (either aspect) replace masculine past -л with -вший, or add -ший directly to a
non-л consonant ending. Present passive participles (imperfective transitive verbs only) add -ый
to the 1pl form. Past passive participles (perfective transitive verbs only) take one of three
endings depending on infinitive shape: -тый (several monosyllabic/other classes), -нный (-ать/-ять
infinitives), or -енный/-ённый (consonant-stem 1B and non-ать second-conjugation verbs, stress
position deciding the ё vs. е spelling). All these participle types decline like adjectives in
long form and have short forms distinguishing gender/number when used predicatively.

### Chapter 10 — Prepositions (§10.1–10.3)
§10.1 catalogues **valency** — which case(s) each Russian preposition governs, natively organized
by case (10.1.1 nominative-looking forms in fixed idioms; 10.1.2 accusative; 10.1.3 genitive;
10.1.4 dative; 10.1.5 instrumental; 10.1.6 prepositional/locative). Several prepositions govern
more than one case with different meanings depending on case (за, на, о, по, под, с all recur
across multiple case-sections). §10.1.6's "на + certain nouns" list (ве́чер, вокза́л, заво́д,
ле́кция, etc. — nouns where на rather than в is idiomatically required for "at/in") is a closed,
memorizable exception set the book flags explicitly as a common English-speaker error trap; it
also notes the historical shift of Ukraine from на-governed (as a region) to в-governed (as an
independent state), an explicit socio-political usage note. §10.2 lists prepositional phrases built
on nouns (в связи́ с, в тече́ние, etc.) explicitly as **"a feature of the official register."** §10.3
catalogues common verb+preposition idiom combinations by the case the preposition governs — see
Vocabulary table above for the full lists.

§10.4 ("Rendering of English prepositions in Russian") is organized alphabetically by English
preposition (ABOUT through WITH) and for each one gives the Russian equivalent(s) by sub-sense,
often with an explicit register tag on a particular equivalent (e.g. про + acc for "about" is
tagged R1; относи́тельно + gen is tagged R3/R3b; согла́сно + dat for "according to" is tagged R3;
c + acc for approximation, e.g. c неде́лю, "about a week," is tagged R1; по-мо́ему for "in my
opinion" is tagged R1/2; отню́дь не for "by no means" is tagged R3). This section functions as a
large mapping table rather than a vocabulary list per se — its individual register-tagged
equivalents are captured as their own rows in the Vocabulary table above rather than reproduced
sentence-by-sentence.

### Chapter 11 — Syntax
**§11.1 Use of the cases.** Nominative marks the subject and (when the verb "to be" is unstated,
i.e. present tense) the predicate nominal. Accusative is the primary direct-object case, and also
expresses duration/distance/price/weight without a preposition. **§11.1.3** explains the
animate-direct-object rule: many animate nouns (across genders/numbers, with an exhaustive
type-by-type breakdown) take a genitive-form direct object instead of accusative, to disambiguate
subject from object given Russian's free word order (worked example: "Ива́н уби́л брат" would be
ambiguous without the marking) — the book notes usage is less clear-cut for "low forms of life"
(bacteria, larvae, embryos), which are usually treated as inanimate in everyday speech but may be
animate in scientific register. Genitive (§11.1.4) expresses possession, quantity, partitive
sense, absence (нет/не́ было/не бу́дет), sufficiency (хвата́ть/недостава́ть), and follows most
cardinal numerals. §11.1.5 lists verbs governing the genitive directly (fear/avoidance verbs, plus
miscellaneous verbs — see Vocabulary table); several allow either genitive or accusative with an
abstract/concrete distinction in meaning. §11.1.6 is a long, nuanced treatment of genitive vs.
accusative direct object under negation — genitive preferred for intensified negation, total
absence, set phrases, verbs of perception, negated gerunds/participles, or when the object is э́то;
accusative preferred for double negatives, instrumental-predicate-qualified objects, non-verb
negation, concrete/specific objects, or feminine/Sasha-type animate nouns — explicitly flagged as
an area where "even native speakers may not agree." Dative (§11.1.7–11.1.8) expresses the indirect
object, the logical subject of impersonal expressions (мо́жно, на́до, нельзя́, жаль, пора́) and of
many impersonal verbs (каза́ться, нра́виться, удава́ться, etc.), and age. §11.1.8 lists
dative-governing verbs in three groups (advantage/hindrance/permission; attitude; miscellaneous),
each with detailed footnotes on aspect-dependent case alternations. Instrumental (§11.1.9–11.1.10)
expresses agent/instrument, what something is endowed with, manner adverbials, temporal point, and
(§11.1.10) is required after быть in most tenses/moods except the present (nominative there) —
a long note explains that the temporary/permanent-state distinction some grammarians draw is safe
to ignore, since instrumental is now always acceptable with быть.

**§11.2 Use of pronouns.** Кото́рый as relative pronoun takes its case from its role in its own
clause, not from the antecedent. Како́й has largely displaced кото́рый as the interrogative "which,"
except in fixed time expressions (Кото́рый час?). Negative pronouns (никто́, ничто́, etc.) require
the negative particle не before the verb; a distinct paradigm (не́чего/не́кого/не́когда/не́где/
не́куда) renders "to have nothing/no one/no time/nowhere to." §11.2.5 draws a careful distinction
between -то (speaker knows something happened but not the details) and -нибу́дь (an element of
choice among alternatives; occurs with future tense, past-tense-with-choice contexts, and
uncertainty adverbs); -ли́бо is glossed as "a more bookish alternative to -нибу́дь [that] now sounds
somewhat dated" — an explicit register/currency judgment. §11.2.6 explains свой: it marks
possession by the subject of its own clause regardless of person, cannot refer to the subject
itself or to a subject in a different clause, with three explicit exceptions (set phrases,
impersonal dative-subject constructions, and y + gen "to have" constructions).

**§11.3 Use of short adjectives.** Short forms are obligatory when predicative (verb "to be"
intervenes between subject and adjective); long forms are used elsewhere regardless of word order.
Even predicatively, usage is fluid: short forms are strongly preferred when a complement follows,
when the subject is то/э́то/что/всё/etc., when the subject is generalized by вся́кий/ка́ждый/любо́й/
etc., when the adjective is participle-derived, when excessive-degree adjectives like вели́к/мал/
до́рог are meant, or in philosophical/scientific generalizations; long forms are preferred to
particularize, in y+gen constructions, or to denote a permanent state contrasted with a temporary
one (Oна́ – больна́я "she is an invalid" vs. Oна́ больна́ "she is ill").

**§11.4 Use of numerals.** A long, detailed treatment: оди́н agrees like an adjective and even
appears in compound numbers ending in "one" (два́дцать одна́ кни́га); два/три/четы́ре/о́ба/полтора́
govern genitive singular when the numeral itself is nominative/accusative, higher numerals (пять+,
ты́сяча, миллио́н) govern genitive plural; adjectives following два/три/четы́ре are genitive plural
for m/n nouns but nominative/accusative plural for feminine nouns (with the older genitive-plural
pattern for feminines flagged as archaic but common in classical literature). When the numeral
itself is oblique, everything conforms to that case in R2/3 (§11.4.3), though R1 may leave only key
components of a compound number declined. §11.4.4 gives detailed guidance on genitive vs.
accusative for animate direct objects after два/три/четы́ре specifically (genitive more correct,
especially for masculine/person nouns; genitive stilted for feminine animal nouns; accusative
default once part of a larger compound, especially in R1). §11.4.5 covers the collective numerals
дво́е–се́меро (their use with groups of people, families, and pluralia-tantum nouns). §11.4.6–13
cover approximation devices, subject-verb number agreement, the special year/people words after
numerals (год/лет; челове́к/люде́й — with a semantic note that люде́й "focuses on the group" while
челове́к counts individuals), distributive по-constructions, telling time, dates, distance
expressions, and the special number-nouns (дво́йка–деся́тка).

**§11.5 Use of aspects.** Basic distinction: imperfective for incomplete/repeated/concurrent
action, perfective for a single completed action presented as a totality (rarely present tense).
§11.5.2 gives a paired list of adverbials that favor one aspect or the other (see Vocabulary-
adjacent content — treated as a grammar illustration, not a vocab table row, since these are common
adverbs already presumed known). §11.5.3 systematically maps imperfective/perfective indicative
forms onto English tense equivalents across present/future/past, including the important
"attempt vs. achievement" nuance in the past tense (e.g. сдава́ть/сдать экза́мен = "to sit" vs.
"to pass" an exam) and a note that ви́деть/слы́шать (imperfective) can mean "to be able to see/hear."
§11.5.4 lists verbs requiring an imperfective infinitive complement (нача́ть, продолжа́ть,
ко́нчить, привы́кнуть, etc.) vs. those requiring perfective (забы́ть, реши́ть, успе́ть, etc.).
§11.5.5 covers aspect under negation (imperfective past = "never happened at all" vs. perfective
past = "didn't happen on this occasion"; imperfective infinitive required after prohibition,
dissuasion, negative advice, decisions-not-to). §11.5.6 covers aspect in the imperative:
imperfective sounds more like an invitation/request, perfective more like a command; the particle
-ка softens an imperative and is explicitly marked R1.

**§11.7 Use of verbs of motion.** The 14 canonical indeterminate/determinate pairs (see Vocabulary
table) — идти́-type verbs denote movement in one general direction toward a goal; ходи́ть-type
verbs cover repeated/habitual action, round trips (synonymous with быть in this sense), movement
in various directions, and movement in the abstract/general sense (e.g. learning to walk).

**§11.8 Use of reflexive verbs.** Covers: verbs that are inherently reflexive with no obvious
reflexive meaning (боя́ться, горди́ться, etc.); the reflexive particle detransitivizing an
otherwise-transitive verb pair (возвраща́ть/возвраща́ться, etc. — 11 pairs given); reciprocal
action (встреча́ться, обнима́ться, целова́ться); characteristic/habitual action with animals
(Крапи́ва жжётся, "nettles sting"); impersonal reflexive constructions describing physical/mental
state (Mне хо́чется, "I feel like"); passive-sense reflexives with inanimate subjects — explicitly
noted as belonging "mainly to R2/3"; and reflexive+prefix combinations.

**§11.9 The conditional mood** distinguishes real conditionals (a verb tense per clause matching
actual past/present/future meaning) from hypothetical conditionals (past-tense verb + бы in both
clauses, translatable to any time frame depending on context); a future tense is obligatory in the
е́сли-clause of a real conditional when the event is still to come.

**§11.10 The subjunctive mood** is formed identically (past tense + бы), used in concessive clauses
(pronoun + бы + ни + past-tense verb, or pronoun + ни + verb), exhortation, wishing (что́бы + past
tense), commanding/permitting (что́бы after such verbs, though R1/R2 prefer a simpler infinitive
construction), fearing (R2/3 uses a negative subjunctive; R1/2 uses a future-tense construction —
an explicit register contrast), and after negated ду́мать/знать.

**§11.11 Use of gerunds and participles.** Imperfective gerunds describe simultaneous action;
perfective gerunds describe prior, completed action; gerunds require same-subject as the main
clause. A note states gerund use "is largely confined to R3" outside a few fixed idioms
(пра́вду говоря́, су́дя по, сиде́ть сложа́ ру́ки). Active participles are semantically equivalent to
кото́рый + finite verb but "confined to R3" except where they've become fixed adjectives/nouns
(бы́вший, куря́щий). Present passive participles occur mainly in R3a/R3b written registers. Past
passive participles are widely used in speech, but R1/R2 tend to avoid them in favor of an
unspecified third-person-plural active construction (paralleling French on/German man) — another
explicit register-contrast point.

**§11.12 Conjunctions.** Coordinating conjunctions (и, а, но, и́ли) dominate in R1, where
subordinating conjunctions "play a lesser role"; а signals stronger opposition than но. §11.12.1(b)
identifies coordinating conjunctions belonging specifically to R1 (да, да и, а то, ли́бо — see
Vocabulary table). §11.12.2 gives the standard causal/temporal/purposive/resultative/concessive/
conditional subordinating conjunctions (all register-neutral, usable in all registers, though more
frequent in R3 overall). §11.12.3 is an explicit two-part register catalogue: (a) conjunctions
"still used but... mainly in R1 or R3" (раз tagged R1; nine compound R3 conjunctions — see
Vocabulary table), and (b) conjunctions "considered obsolete in the modern literary language" but
persisting in classical literature or R1/dialect (бу́де, да́бы, доко́ле, е́жели, ко́ли, коль ско́ро,
пока́мест) — a directly usable historical/currency stratification for slang-synthesis purposes.

**§11.13 Syntactic features of colloquial speech** is an explicit, dedicated R1-syntax catalogue:
(a) ellipsis, especially of motion verbs (Bы ко мне? "Are you coming to see me?"); (b) two verbs in
the same form combined to show an accompanying state (Oна́ сиде́ла шила́, "she sat sewing"); (c)
verb repetition for protracted action (Éхали, е́хали...); (d) same-root verb pairs split by не for
emphatic fullness (ра́дуется не нара́дуется); (e) a взять-construction for sudden volition (Oн
взял да убежа́л, "he was up and off"); (f) то́лько и де́лает/зна́ет, что for single exclusive
action; (g) знай (себе́) for persistent action against obstacles; (h) смотри́(те) + negative
imperative meaning "mind you don't." This entire section is a directly relevant model for
constructing an in-universe colloquial-register grammar layer.

**§11.14 Word order.** Word order is grammatically freer than English (inflection carries the
relational load) but not random: neutral order follows subject-verb-object; the sentence-final
position carries the "new" information the speaker wants to foreground (но́вое и да́нное) while
earlier material is given/known — directly correlated with subject-verb inversion in existence/
occurrence/natural-event statements (идёт снег, Прошли́ го́ды) and after place-adverbials, question
words, and reported speech. Object pronouns and impersonal-construction "possessor" objects tend to
precede the verb; infinitives normally follow their governing verb; attributive adjectives normally
precede their noun (but may follow in menus/catalogues); adverbs normally precede their verb (except
language-naming adverbs like по-ру́сски, which follow). §11.14(d) explicitly notes that "expressive
registers, e.g. R1, R3c and the language of belles-lettres" achieve emphasis by violating all the
above neutral-order rules — another explicit register/word-order correlation.

**§11.15 Punctuation.** Full stop, question mark, semicolon, and colon function much as in English.
The comma is obligatory in several contexts where English usage is looser: before coordinating
conjunctions joining clauses (unless same subject + и), at every main/subordinate clause boundary,
around gerund/participle phrases, around parenthetical words, and around comparative phrases. The
dash marks omitted copulas (rendering English "to be" in the present tense), introduces/closes
direct speech, signals an unexpected turn, and can pair up to bracket a parenthetical remark more
emphatically than commas. The exclamation mark is used more widely than in English (greetings,
congratulations, letter salutations, interjections). Guillemets («») are the traditional quotation
mark, though English-style quotation marks have spread with personal-computer use. Omission dots
mark an incomplete or hesitant thought and are explicitly noted as unlikely in R3a/R3b but frequent
"in the written form of the colloquial language and... the language of the internet."

**§11.16 Use of capital letters.** Capitals are used far more sparingly than in English: no capital
for weekdays/months/nationalities/religions/languages; only the first word of an institution/
publication title is capitalized; in place-names, the generic term (мо́ре, о́стров, у́лица, etc.) is
lower-case while the proper name/adjective is capitalized, with some fixed exceptions (Cоединённые
Шта́ты Aме́рики, Cеверный по́люс).

### Chapter 12 — Stress
**§12.1** frames Russian stress as strong (a mis-stressed word may go unrecognized) and
homograph-distinguishing (ве́сти/вести́, мо́ю/мою́, пла́чу/плачу́, сло́ва/слова́); e→ё under stress
and ё→e when stress is lost (вы́шел vs. пошёл) recur as a running theme through the chapter.

**§12.2 Stress in nouns**, organized by gender, sets out closed pattern-classes for which nouns have
fixed stress vs. which shift, and where the shift falls (end-stress after the initial form; end-
stress in plural only; end-stress in oblique-plural only). Each subsection (12.2.1.1–12.2.5, and
parallel feminine 12.2.2.1–12.2.2.3 and neuter 12.2.3.1–12.2.3.5 sections) gives a small paradigm
table plus a list of similarly-behaving nouns, explicit exceptions, and irregular plurals (у́хо→у́ши,
не́бо→небеса́, and др.). §12.2.4 covers the special stressed locative endings -у́/-и́ after в/на for
some monosyllabic nouns (в шкафу́, в крови́). §12.2.5 is a distinct, useful sub-pattern: certain
monosyllabic preposition+noun combinations shift stress onto the *preposition itself* (за́ год,
на́ ночь, по́д гору, etc.) — a closed, enumerable idiom set.

**§12.3 Stress in adjectives.** Long-form adjectives have fixed stress throughout their declension.
Adjectives with suffixes -ичный/-альный/-онный and the four participial-origin suffixes -учий/
-ючий/-ачий/-ячий are always penultimate-stressed; -ический adjectives are always antepenultimate-
stressed. Disyllabic (and some trisyllabic, к-stem) adjectives shift stress to the ending in the
short feminine form (ва́жный→важна́); short comparatives stress the first syllable of the -ее
ending; superlatives are usually penultimate-stressed.

**§12.4 Stress in verbs**, simpler than nominal stress overall, covers first-conjugation verbs
(stress fixed on the same vowel throughout for 1A verbs and vowel-stem 1B verbs; three distinct
sub-patterns for consonant-stem 1B verbs depending on whether the ending is unstressed, stressed,
or stressed-only-in-1sg), second-conjugation verbs (three parallel patterns: end-stress throughout,
stem-stress throughout, or shift from ending to stem after 1sg), past-tense stress (usually matches
the infinitive; -ти́/-ечь verbs shift stress onto the f/n/pl endings; a few monosyllabic verbs shift
in the feminine form only; -мере́ть/-нять-type verbs shift onto the ending in feminine but onto the
prefix elsewhere), and gerund/participle stress rules for each of the six participle/gerund types,
each tied back to a specific verb form (3pl present, 1sg present, infinitive, or masculine past)
that supplies the stress position. §12.4.5 notes miscellaneous points: the negative particle не
attracts stress before был/бы́ло/бы́ли; the prefix вы́- is always stressed in perfective verbs.

**§12.5 Variation in stress** is a substantive sociolinguistic-register section in its own right:
it documents real instability/variation in stress for monosyllabic-basic-verb+prefix past tenses
(при́был/прибы́л, etc. — noting the prefix-stressed variant is now less common), stress
variation in R1 specifically (feminine past-tense stem-stress instead of standard end-stress —
бра́ла, нача́ла, etc. — and neuter past-tense end-stress instead of standard stem-stress); an
explicit socio-political stress-diffusion case study (non-standard за́нять/на́чать/при́нять/
углу́бить infinitive stress spreading via broadcast media because of Gorbachёv's Stavropol regional
speech); alternative noun/adjective stress variants (укра́инский, це́ну→цену́, etc.); a
suffix-attracting-stress drift in -ение nouns (наме́рение→намере́ние); and finally an explicit
sociolect note — ко́мпас is stressed компа́с "in the speech of seamen," шофёр may become шо́фер for
"drivers," and Academician Vinográdov reportedly used киломе́тр in an academic setting but
кило́метр "if he was talking to his chauffeur" — a vivid, directly citable illustration of
register/sociolect-conditioned phonological variation.

---

## Cross-reference notes for future mechanics analysis (`analysis/`)

- **§11.12.3 and §11.13** together form the single richest register-contrast dataset in this whole
  chunk: a paired list of "same meaning, different register" conjunctions/constructions, plus a
  dedicated catalogue of R1-only syntactic constructions. Strongly recommended as primary source
  material for any future `analysis/` file on register-marking mechanisms in Russian.
- **§12.5**'s sociolect-stress examples (ко́мпас/компа́с, шофёр/шо́фер, киломе́тр/кило́метр) are a
  ready-made real-world model for "profession/social-group marks itself via a predictable phonological
  shift, not a separate lexicon" — directly relevant to conlang slang-synthesis mechanics.
- The **Latin a/e substitution cipher** documented above should be checked against any *other* PDF
  from this same Offord/Gogolitsyna source (there may be a companion exercise volume) before
  assuming a different, unverified cipher.
