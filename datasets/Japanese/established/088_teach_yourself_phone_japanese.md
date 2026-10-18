# Japanese — Established Vocabulary/Grammar: *Teach Yourself Phone Japanese* (complete short course)

**Source:** Haruko Laurie, *Teach Yourself Phone Japanese* (Teach Yourself series, audio-course
companion booklet), full 32-page PDF (`book.pdf`) — Calls 1–10 (dialogues), Listening skills:
survival phrases, Using the telephone in Japan (usage notes + topical vocabulary: telephones,
mobile phones, telephone numbers, in the office, in the hotel, in the restaurant, public
transport), Japanese–English glossary, English–Japanese glossary (pp. 2–59 of the printed book;
all 32 PDF pages).

**Coverage note:** This is a short, self-contained phrasebook companion to an audio course (not a
grammar textbook), so it was extracted close to exhaustively rather than sampled: every dialogue
line's content vocabulary, every topical-list entry, and the complete final alphabetical glossary
(which consolidates all vocabulary used across the ten calls and topical lists — cross-checked and
confirmed to be a near-total superset of the dialogue vocabulary, so the dialogues themselves are
represented here via illustrative phrases/register notes rather than a second full re-listing of
every word already captured in the glossary table). The Japanese–English and English–Japanese
glossaries at the back are mirror images of the same ~178-entry word list (one sorted by rōmaji,
one by English gloss); only the Japanese–English ordering is tabulated below to avoid duplicate
rows — cross-referenced against the English–Japanese glossary to confirm no entries differ between
the two.

**PDF extraction gotcha (new, worth flagging for future Japanese sources):** `pdfinfo` reports a
genuine text layer, and all rōmaji and English prose extract cleanly — but every native-script
(kana/kanji) glyph in this PDF decodes to unrelated, inconsistent Latin/symbol mojibake (e.g. the
glyphs for はい "hai" render as `I~L\`, for ありがとう render as `(li;I)tJ{C?`). This is **not** a
fixed 1:1 substitution cipher like the Cyrillic/Hangul cases documented in the extraction spec —
spot-checking the same kana across multiple pages shows no stable mapping, consistent with the
spec's "CID-embedded font with no usable ToUnicode mapping" case. Because the rōmaji transliteration
is present and fully legible for essentially every Japanese-language item in this book (a
pedagogical design choice — this is a phrasebook for an audio course, so every phrase is given in
rōmaji by design), full vision-reading of all 32 pages was judged not worth the cost for this
source specifically: native script is marked unrecoverable below rather than vision-read, and
`Term` uses rōmaji. A **column-layout gotcha was also encountered and resolved**: the default
`pdftotext` extraction (no `-layout`) scrambled the two-column Japanese–English/English–Japanese
glossary pages exactly as the spec's "two-column dictionary page" gotcha predicts (it emitted all
rōmaji terms, then all glyph-mojibake, then all English glosses as three separate same-order runs
rather than row-aligned tuples). Re-running `pdftotext -layout` on just the glossary pages (27–32)
recovered proper column alignment (rōmaji | mojibake script | gloss, side by side), and the ordering
was cross-checked against several entries whose meaning is independently confirmable from dialogue
context (e.g. `minshuku` → "B&B", confirmed against the "In the hotel" topical list earlier in the
book) — alignment confirmed correct throughout.

No marginalia issue applies — this source has a genuine text layer throughout (no vision-reading was
performed), so the vision-reading guard doesn't apply here.

---

## Vocabulary

Glossary is alphabetized by rōmaji. `Usage Tier` is `core` unless the source itself marks a
formal/informal/polite contrast (noted per row). Native script is uniformly unrecoverable (see
gotcha note above) and omitted from `Term`; where the book gives both a plain and polite/formal
variant of the same word, both are listed in one `Term` cell separated by `/`.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| aku | be free/vacant (of a seat, time) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| an'nai | information, guidance | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| arigatō / arigatō gozaimasu | thank you | interjection | colloquial / formal | — | — | — | — | grammar_reference | n/a | n/a | plain vs. polite-formal pair |
| aru | exist, have (inanimate) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| ashita | tomorrow | noun/adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| atarashii | new | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| atari | area, vicinity | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| ato de | later | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| azukaru | keep, hold (for someone) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| baikingu | buffet | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | from English "Viking" (buffet-style) |
| bangō | number | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| basho | place, location | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| basu | bus | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| basu / furo | bath | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword "basu" vs. native "furo" pair |
| basu-tsuki | with bath (room feature) | noun/compound | core | — | — | — | — | grammar_reference | n/a | n/a | basu + tsuki ("attached") |
| batterī / denchi | battery | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword vs. native pair |
| boku | I (informal, male) | pronoun | colloquial | — | — | — | — | grammar_reference | n/a | n/a | contrasts with watakushi/watashi below |
| chekku auto | checkout | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| chekkuin | check-in | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| chiisai | small | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| chikai uchi ni | soon, in the near future | adverbial phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| chikatetsu | underground, metro | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| chokutsū / daiaru-in | direct line | noun | core | — | — | — | — | grammar_reference | n/a | n/a | native vs. loanword ("dial-in") pair |
| chōshoku | breakfast | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| daburu | double (room) | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| daijōbu | OK, fine, all right | adjective/phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| denchi ga kireru | run out of battery, go flat | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| denchi o juden suru | charge a battery | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| densha | train | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| denwa | telephone | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| denwa ryōkin | telephone charge | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| denwachō | telephone directory | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| dō itashimashite | not at all, you're welcome | set phrase | formal | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| dochira / doko | where | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | dochira = more formal/indirect |
| dochira / dotchi | which (of two) | pronoun | formal / colloquial | — | — | — | — | grammar_reference | n/a | n/a | dotchi marked informal variant |
| doru | dollar | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| doyōbi / doyō | Saturday | noun | core | — | — | — | — | grammar_reference | n/a | n/a | full vs. clipped form |
| eigyō suru | run a business, be open (of a shop) | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| eki | station | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| en | yen | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| gaikoku | foreign (country) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| gaisen | outside line | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| genki | well, healthy, energetic | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| gogo | afternoon, p.m. | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| ha | tooth, teeth | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hai | yes (formal) | interjection | formal | — | — | — | — | grammar_reference | n/a | n/a | contrasts with "un" below |
| hairu | enter, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hajimemashite | how do you do (first meeting) | set phrase | formal | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hajimeru | start, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hajimete | for the first time | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| han | half past (time) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hanasu | speak, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| heya | room | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hidari | left (direction) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hidoi | terrible, bad | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hitoheya | one room | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hoka | other | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| hoteru | hotel | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| ii / yoi | good, convenient | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | colloquial vs. dictionary-form pair |
| ikaga / dō | how about | adverb | formal / core | — | — | — | — | grammar_reference | n/a | n/a | ikaga marked more polite |
| ikura | how much | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| ima kara | from now | adverbial phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| ima / tadaima | now | adverb | core / formal | — | — | — | — | grammar_reference | n/a | n/a | tadaima more formal/emphatic |
| ippaku | one night's stay | noun | core | — | — | — | — | grammar_reference | n/a | n/a | counter word for overnight stays |
| isogashii | busy | adjective | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| itadaku | receive, to (formal/humble) | verb | formal | — | — | — | — | grammar_reference | n/a | n/a | humble form; pairs with morau below |
| itamu | ache, hurt | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| iu | say, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| jūtai | traffic jam | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| jiko | accident | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| jitaku | home, one's own house | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| jitsu wa | to tell you the truth | discourse phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| juwaki | (telephone) receiver | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kaigi / mītingu | conference, meeting | noun | core | — | — | — | — | grammar_reference | n/a | n/a | native vs. loanword pair |
| kaigi-chū | in a meeting | noun/phrase | core | — | — | — | — | grammar_reference | n/a | n/a | -chū = "in the middle of" suffix |
| kaisatsuguchi | ticket barrier | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kaisha | company | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kakaru | take (time), to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kaku | write, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kamera | camera | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kanari | fairly, considerably | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kankō | tourism, sightseeing | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kara | from; because | particle/conjunction | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kasa | umbrella | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kauntā | counter (seating) | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kawaru | change, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kawase | (currency) exchange | noun | technical | — | — | — | — | grammar_reference | n/a | n/a | banking term, used for "Foreign Exchange Section" |
| kayōbi / kayō | Tuesday | noun | core | — | — | — | — | grammar_reference | n/a | n/a | full vs. clipped form |
| keitai denwa | mobile phone | noun/compound | core | — | — | — | — | grammar_reference | n/a | n/a | often clipped to just "keitai" — see note below |
| ki ga suru | have a feeling, to | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| ki o tsukeru | take care, to | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kin'en | non-smoking | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kōkanshu / operētā | (telephone) operator | noun | core | — | — | — | — | grammar_reference | n/a | n/a | native vs. loanword pair |
| kokusai denwa | international call | noun/compound | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kon'nichi wa | hello / good afternoon | set phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| konshū | this week | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| konshūmatsu | this weekend | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| koshō | breakdown, malfunction | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| koshō-chū | out of order | noun/phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kōtsū-kyoku | transport office | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kunibangō | country code | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kurejitto kādo | credit card | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kyū ni | suddenly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kyūka-chū | on holiday | noun/phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kyūkō | express (train) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kyaku | guest, customer | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kyanseru | cancellation | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| kyō / honjitsu | today | noun | core / formal | — | — | — | — | grammar_reference | n/a | n/a | honjitsu marked more formal |
| mama | so-so | adverb | colloquial | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| machiawaseru | meet up (at an arranged place/time), to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mada | still, not yet | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| made | until, up to | particle | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mado-gawa | window side | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mana mōdo | silent/manner mode | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | from English "manner mode" |
| mata | again | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| matsu | wait, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| me no mae | right in front of your eyes | noun phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| messēji / dengon | message | noun | core | — | — | — | — | grammar_reference | n/a | n/a | loanword vs. native pair |
| minami-guchi | south exit | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| min'na | everybody | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| minshuku | B&B, guesthouse | noun | core | — | — | — | — | grammar_reference | n/a | n/a | cross-checked against "In the hotel" topical list |
| miru | look, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mise | shop, restaurant | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mitsukaru | be found, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mō ichido | once more | adverbial phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mō sukoshi | a little more | adverbial phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mochiron | of course | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| modoru | return, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mokuyōbi / mokuyō | Thursday | noun | core | — | — | — | — | grammar_reference | n/a | n/a | full vs. clipped form |
| morau | receive, to (plain/informal) | verb | colloquial | — | — | — | — | grammar_reference | n/a | n/a | pairs with itadaku above |
| mōshiwake | excuse (as in "moshiwake gozaimasen") | noun | formal | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| mōsu | say, to (humble) | verb | formal | — | — | — | — | grammar_reference | n/a | n/a | humble register verb |
| motsu | hold, possess, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| namae | name | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| nanji | what time | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| nan'nichi | which day (of the month) | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| nareru | get used to, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| nishoku | two meals (breakfast+dinner) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | hotel-rate term |
| noru | ride, get on, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| o-daiji ni | take care! (said to someone unwell/leaving) | set phrase | formal | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| o-hanashi-chū | the line is engaged | set phrase | formal | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| o-ikura desu ka | how much is it? | set phrase | formal | — | — | — | — | grammar_reference | n/a | n/a | polite form of ikura |
| ōkina koe de hanasu | speak louder (lit. speak in a big voice) | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| okiwasureru | leave behind (by forgetting), to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | oku (put) + wasureru (forget) compound |
| o-koshi | your arrival (honorific) | noun | formal | — | — | — | — | grammar_reference | n/a | n/a | honorific o- + koshi |
| oku | put, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| okureru | delay, be late, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| omou | think, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| o-me ni kakaru | meet, to (polite/humble) | verb phrase | formal | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| o-negai | request | noun | formal | — | — | — | — | grammar_reference | n/a | n/a | see grammar point below — pervasive set phrase |
| onsen | hot spring | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| oritatami-gasa | folding umbrella | noun/compound | core | — | — | — | — | grammar_reference | n/a | n/a | see morpheme breakdown below |
| oshieru | teach, tell, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| owaru | finish, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| pondo | pound (currency) | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| rūmu chāji | room charge | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| rūmu nanbā | room number | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| rūmu sābisu | room service | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| renraku suru | contact, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| resutoran | restaurant | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| rusuban denwa / rusuden | answering machine | noun | core | — | — | — | — | grammar_reference | n/a | n/a | rusuden = common clipped form |
| ryōgae | (money) exchange | noun | core | — | — | — | — | grammar_reference | n/a | n/a | distinct from kawase (specifically currency/bank exchange) |
| ryokan | Japanese-style inn | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| ryokō | travel | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| sakki | just now, earlier on | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| sashiageru | give, to (polite) | verb | formal | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| sayōnara | goodbye | interjection | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| sei | fault | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| seki | seat | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| seki o hazusu | be away from one's desk | verb phrase | formal | — | — | — | — | grammar_reference | n/a | n/a | office-phone set phrase |
| senshū | last week | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| setsumei suru | explain, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| shi | city | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| shigai kyokuban | area code | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| shigai tsūwa | long-distance call | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| shigoto | work | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| shika | dentist | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| shikata ga nai | it can't be helped | set phrase | core | — | — | — | — | grammar_reference | n/a | n/a | very common set phrase |
| shinai tsūwa | local call | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| shinai / tonai (Tokyo only) | within city | noun | core / regional | — | — | Tokyo | local | grammar_reference | n/a | n/a | tonai is a Tokyo-specific variant form explicitly flagged by the source |
| shiru | know, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| shitei-seki | reserved seat | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| shōshō | a little, a moment | adverb | formal | — | — | — | — | grammar_reference | n/a | n/a | used in "shōshō o-machi kudasai" (please wait a moment) |
| shutchō-chū | on a business trip | noun/phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| subete | all | pronoun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| sudomari | room only (no meals) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| sugu | straight away | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| sukunakutomo | at least | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| sū | smoke, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| suwaru | sit down, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tabako | cigarette, smoking | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tanomu | request, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tēburu | table | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tōchaku | arrival | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| toiawase | enquiry | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| toiawaseru | make an enquiry, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| toire / o-tearai | toilet | noun | core / formal | — | — | — | — | grammar_reference | n/a | n/a | loanword vs. polite-euphemistic native pair |
| tokkyū | super express (train) | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tori ni iku | fetch, go to get, to | verb phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| toru | take (a reservation), to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tsūro-gawa | aisle side | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tsuin | twin (room) | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tsukareru | get tired, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tsukau | use, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tsuki | attached (with), suffix | suffix/noun | core | — | — | — | — | grammar_reference | n/a | n/a | used in basu-tsuki, chōshoku-tsuki etc. |
| tsuku | arrive, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tsunagu | put through (a call), to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| tsutaeru | pass on a message, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| ukagau | visit, to (formal/humble) | verb | formal | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| un | yes (informal) | interjection | colloquial | — | — | — | — | grammar_reference | n/a | n/a | contrasts with "hai" above |
| unchin | train fare | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| wakaru | understand, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| waribiki | discount | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| washitsu | Japanese-style room | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| watakushi / watashi | I (formal) | pronoun | formal | — | — | — | — | grammar_reference | n/a | n/a | contrasts with boku above |
| yūro | euro | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| yūsu hosuteru / yūsu | youth hostel | noun (loanword) | core | — | — | — | — | grammar_reference | n/a | n/a | full vs. clipped form |
| yakusoku | promise, arrangement | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| yasumi | break, holiday | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| yasumi nashi | without a break | noun phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| yōshitsu | western-style room | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| yotei | schedule | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| yoyaku | reservation | noun | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| yoyaku suru | reserve, to | verb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| yukkuri | slowly | adverb | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |
| zeikomi | inclusive of tax | adjective/phrase | core | — | — | — | — | grammar_reference | n/a | n/a | p.48 |

**Morpheme breakdown (rendaku/compounding examples).** Japanese is agglutinative in its verbal
morphology but largely compounding (not agglutinative) in its nominal morphology; a handful of
entries above are worth flagging because the atomic gloss hides a compositional pattern — rendaku
(sequential voicing), the recurring phenomenon where the initial consonant of a compound's second
element voices (k→g, t→d, s→z, h→b) when attached to a preceding element:

> **oritatami-gasa** = oritatami ("folding," from oru "to fold" + tatamu "to fold up") + kasa
> ("umbrella," voiced to -gasa under rendaku) — "folding umbrella." Same voicing pattern recurs in
> **basu-tsuki** / **chōshoku-tsuki** / **nishoku-tsuki**, where *tsuki* ("attached") stays
> unvoiced because it's the second element following a vowel-final loanword stem, not a native
> compound-internal position — contrast with compounds like **kaisatsu-guchi** ("ticket barrier" =
> kaisatsu "ticket inspection" + kuchi "mouth/opening," voiced to -guchi).
>
> **keitai denwa** = keitai ("portable, carry-on-person") + denwa ("telephone") — commonly clipped
> to just *keitai* in casual speech (noted directly in the source); the clipping itself is a
> register marker (full form more formal/written, clipped form more colloquial/spoken), the same
> clipping pattern as *yūsu hosuteru* → *yūsu* and *rusuban denwa* → *rusuden*.
>
> **shigai-tsūwa** = shigai ("outside the city," shi "city" + gai "outside") + tsūwa ("phone
> call") — "long-distance call," contrasted directly in the source with **shinai-tsūwa** (shi +
> nai "inside" + tsūwa) "local call" — a minimal city-inside/city-outside pair built from the same
> head noun, worth noting for any later cross-language register/compounding comparison.

---

## Grammar points

### Sentence-final "ga" as a politeness softener

The source explicitly calls out that many dialogue lines end in the particle *ga* without it being
translated as "but"/"and." When *ga* trails a sentence with nothing following, its function is to
leave something unstated (a question, a request, a qualification) implicit rather than spelling it
out directly — this is presented as a politeness strategy: naming the implication would be blunter,
leaving it unsaid is "gentler and hence more polite." Example given: someone answering the phone
with "Kinoshita desu ga" ("It's Kinoshita here, [but/and...]") leaves room for "Who's calling?" or
"How can I help you?" to follow without stating it. (p. 59)

### "o-negai shimasu" as an all-purpose request/acceptance formula

Flagged as one of the most frequent phrases across all ten calls. It is used both to *make* a
request and to *accept* an offer (of a seat, room, or appointment), and is translated differently
depending on context: "Will you please...," "Yes, please," "I'll take it," or simply "Thank you."
When making a request of someone, it is frequently paired with *yoroshiku* or *dōzo yoroshiku*.
(p. 59)

### Service-register set-phrase triad: kashikomarimashita / shōchi itashimashita / kekko desu

Three high-frequency hospitality/business-service phrases are explicitly glossed with their
pragmatic nuance, not just literal meaning:
- **kashikomarimashita** and **shōchi itashimashita** — said by an operator/receptionist/hotel
  staff member after being asked to pass on a message or accommodate a request; both mean
  "certainly" or "with pleasure," functioning as a formal acknowledgment-of-service phrase rather
  than a literal translation of their component words.
- **kekko desu** — flagged as genuinely ambiguous and context-dependent: when accepting an offered
  seat/table/date during a reservation, it means "I'll take it" / "That will be fine"; but as a
  bare response to an offer ("(Ie,) kekko desu"), it means the opposite — "No, thank you." The
  source explicitly warns these two readings are easy to confuse. (p. 59)

### "Shitsurei shimasu/itashimasu" vs. "Shitsurei shimashita" — goodbye vs. apology

A minimal pair distinguished purely by tense/aspect: the non-past forms (*shitsurei shimasu* /
*shitsurei itashimasu*) are used as a formal/business-register way to say "goodbye" on the phone,
especially to a senior/superior; the past form (*shitsurei shimashita*) instead means "sorry," in
the specific sense of apologizing for having been impolite. A distinct apology register is used for
having caused inconvenience or done something wrong: *gomen nasai* (to a friend, informal) vs.
*mōshiwake gozaimasen* (business/formal context). (p. 59)

### "Sassoku desu ga" — cutting past formalities to the business at hand

Used in work contexts to signal the speaker wants to move past preliminary pleasantries and get
straight to the point; literally "[I'm sorry] to hurry things along." (p. 59) This is a concrete
example of the register system interacting with discourse structure (an explicit "let's skip the
small talk" move encoded as its own formal set phrase) rather than purely lexical register.

### Telephone-number reading convention

Japanese telephone numbers are read digit-by-digit (not grouped/compounded like English "thirty-
four"), with a short pause marking grouping boundaries — e.g. `03 3678 4670` is read *zero-san*
[pause] *san-roku-nana-hachi* [pause] *yon-roku-nana-zero*. The pause can be replaced by the
particle *no* instead of an actual pause: *zero-san no san-roku-nana-hachi no yon-roku-nana-zero*.
(p. 54)

### International dialing and area-code nesting

To place an international call from Japan: dial `0033 010` + country code, or `001 010` + country
code. Area codes can nest in a way that isn't obvious from the number alone: `03` is specifically
the code for *central* Tokyo, but a number like `0423 69 9853` — with area code `0423` — is also
within Tokyo Prefecture, just not within the central-Tokyo area covered by plain `03`. (p. 54)

### Mobile phone etiquette norm

The source notes mobile phone use on Japanese public transport is strictly controlled by social
norm: passengers are expected to switch to silent/manner mode (*mana mōdo*) or power off entirely,
especially near priority seating for disabled passengers — the stated reason given is that mobile
signals are understood to risk interfering with pacemakers. (p. 50) This is a culturally-specific
register constraint worth flagging for any later register/pragmatics cross-language comparison
work.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
