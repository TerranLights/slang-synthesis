# Japanese — Established Vocabulary/Grammar: Making Sense of Japanese: What the Textbooks Don't Tell You (in progress)

**Source:** Jay Rubin, *Making Sense of Japanese: What the Textbooks Don't Tell You* (Kodansha
International, first edition 1998 as a retitling of the author's earlier *Gone Fishin'*, 1992;
this file extracts the 2002 first trade paperback printing, ISBN 4-7700-2802-4). 68 physical PDF
pages, each a two-printed-page spread (confirmed empirically: PDF page N reliably renders printed
pages 2N/2N+1, e.g. PDF page 12 = printed pp. 24–25) — the same page-spread-scan pattern flagged in
the extraction spec for *Colloquial Serbian*. No text layer (`pdfinfo` reports a real text layer but
`pdftotext` returns empty content); vision-read throughout via `pdftoppm -r 200`. Pages also carry a
90° page-rotation flag in the PDF metadata, correctly auto-corrected by `pdftoppm`. No handwritten
marginalia was found on any page read so far — the scan is a clean, unmarked copy.

**Correction to this dispatch's framing.** This book is **not** a companion volume to Cipris &
Hamano's *Making Sense of Japanese Grammar* (established/047, 047b) despite the near-identical main
title — confirmed from the book's own front matter (title page, copyright page, preface): the
author is **Jay Rubin** (Harvard professor of Japanese literature, Murakami Haruki's translator),
writing a personal, informal, non-linguist's essay collection on recurring usage problems, originally
published under the unrelated title *Gone Fishin'* (1992). The title similarity to 047/047b appears
to be coincidental (both books use "Making Sense of Japanese" as a marketing title from roughly the
same era, but are unrelated works by different authors/publishers — this one is Kodansha
International; 047/047b is University of Hawai'i Press). This file treats it as an independent
source and applies the non-redundant-supplement pattern against *all* prior Japanese `established/`
particle/grammar coverage (032, 034, 036/036b, 047/047b), not specifically against 047 alone.

**Coverage note.** The book is organized as a sequence of discursive essays (not a dictionary or
graded lesson sequence), each built around one recurring problem point for English-speaking
learners, frequently illustrated with the author's own invented example sentences and literary
citations (Murakami Haruki, Natsume Sōseki, newspaper Japanese). Per the coverage rule, the
introduction's polemical framing (arguing against the "Japanese is vague/mystical" myth) is
summarized only briefly — it is cultural argument, not grammar content — while every actual grammar
point in Parts One and Two is captured. Where this book's analysis duplicates ground already covered
by 032/034/036/047/047b (e.g. the basic function of *wa*/*ga*, directional giving-and-receiving
verbs, the causative), **vocabulary rows are kept sparse** and the Notes column flags specifically
what Rubin's own treatment adds that prior extractions didn't already capture — per the extraction
spec's non-redundant-supplement guidance. Rubin's own distinctive contribution is argumentative/
pedagogical framing (vivid English analogies, explicit myth-busting, invented minimal-pair examples)
rather than new descriptive facts about the particles themselves in most cases, so the **Grammar
points** section captures his specific analytical framing/examples rather than re-deriving facts
already on record.

**Copyright discipline:** paraphrased throughout; the book's own example sentences (both Rubin's
invented ones and his literary citations) are quoted only in short, single-line form.

*(This file is being written progressively; a sibling file `048b_...md` will be created if content
from later chapters needs to be split out. Status: pages 1–52 of 68 PDF images read so far (printed
pp. 1–105), covering front matter, Part One in full, and (Part Two) "The Explainers," "The Johnny
Carson Hodo," "Kanji" (off-topic, summarized briefly), "Shiru and Wakaru" in full, "Taming Tame" in
full, "Tsumori and the Vanishing Beefsteak" in full, and the start of "You Say Kimeru and I Say
Kimaru.")*

---

## Vocabulary

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| (zero pronoun) | Rubin's own term for the unmarked omission of a known subject/object | grammatical concept | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Rubin's central polemical claim in "The Myth of the Subjectless Sentence": Japanese has exactly one true pronoun, "zero" — overt pronoun-like words (*watashi*, *kare*, *kanojo*, etc.) are repurposed ordinary nouns (originally meaning "servant," "over there," etc.), not grammatical pronouns in the English sense, and are used only when genuine emphasis/contrast is needed, never as all-purpose repetition-avoiders the way English "he/she/it" are. He credits linguist Chris Brockett with noting that this idea had already been formalized elsewhere as a "rich theory of zero pronouns in government and binding theory." |
| wa | topic-marking particle | particle | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | "Wa and Ga: The Answers to Unasked Questions" — already well covered in 032/034/036/047 (Unit 16/18/20 in 047 gives the fresh-vs.-anchored-participant account). Rubin's own distinctive framing, not found in those: he models every *wa*/*ga* choice as implicitly answering a specific unasked question, and recommends the heuristic "ask yourself what question this sentence is the answer to" as a practical disambiguation tool. Minimal triple *Ikimashita* / *Watashi wa ikimashita* / *Watashi ga ikimashita* (all glossable as "I went" in isolation) are shown to answer three different implicit questions (neutral/unemphatic; "and you? what did *you* do"; "who went?") — the particle choice is driven by which question is being answered, not by any inherent correctness of one form over another ("no more inherently correct than 'a dog' is more correct than 'the dog'"). |
| anata / boku / kare / kanojo | 2nd/1st/3rd-person pseudo-pronouns | pronoun (repurposed noun) | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | See *(zero pronoun)* row — Rubin's point is that these words are not interchangeable all-purpose repetition-avoiders the way English pronouns are; overusing them (as some translators/learners do) produces stilted, unnatural Japanese. He cites Akutagawa Ryūnosuke's prose as a case where an author deliberately over-uses these forms to lend the Japanese text an exotic "foreign" flavor — evidence that native speakers perceive heavy pronoun use as marked/non-default. |

| yaru / ageru / sashiageru | "give" verbs, giving-away direction (ascending politeness) | verb | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Already covered in 047's benefactive row (Unit 31) and in 032/034/036. Rubin's distinctive framing: these three mean exactly the same thing ("give") and differ only in politeness level, but all three fix the *direction* of giving as away from the speaker (or speaker-aligned group), regardless of up/down hierarchy — "the crucial thing is the direction away," not who outranks whom. *Ageru* literally means "to raise up," reflecting (but not strictly requiring) the hierarchical assumption that the recipient outranks the giver. |
| kudasaru / kureru | "give" verbs, giving-toward-speaker direction | verb | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Rubin's distinctive point not found in prior extractions: *kudasai* (the common polite imperative "please") is grammatically the imperative of *kudasaru*, so asking someone *kudasai* literally commands them to perform the self-abasing "lower something down to me" verb — explaining why *kudasaru* use implicitly positions the asker as low/humble and the other person as elevated, the reverse of *ageru*'s implied hierarchy. The identity of the subject of *kureru*/*kudasaru* vs. *morau* constrains which questions are even grammatically askable: you can ask someone *Kaite kuremasu ka* ("will you write it for me") but never *Kaite moraimasu ka* ("am I going to get you to write it for me" — ungrammatical as a question since only the asker can initiate *morau*), though *Kaite moraemasu ka* ("can I get you to...") works since it questions *possibility*, not the asker's own future initiative. |
| morau / itadaku | "receive" verbs (itadaku = humbler register) | verb | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Already covered in 047 (benefactive row). Rubin's distinctive framing: unlike the two-directional giving verbs, receiving happens in only one direction ("I get from him"); there is no form for "he gets from me." His central practical rule for untangling -te morau/-te itadaku chains: always identify the subject of the *final* verb first (always "I," or a speaker-aligned party) — that established, the person performing the *-te*-form verb is necessarily the *other* party, since "you can't receive from yourself the doing of a verb." Demonstrates the kureru/morau viewpoint-contrast minimal pair: *Kaite kureta* ("He wrote it for me" — he initiated) vs. *Kaite moratta* ("I got him to write it for me" — I initiated the receiving, though he still does the actual writing). Flags the common student error of over-translating -te kureru/-te morau constructions into an English passive ("The dog was washed for me"), which "kills" the implied agent entirely and can even promote an object (the dog) to subject status in translation — a more severe version of the error already flagged for the plain passive in "The Myth of the Subjectless Sentence." |
| -(s)aseru (causative) | causative suffix ("make/let X do") | verb suffix | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Already covered in 047 (Unit 30/32, the double-o-constraint/participant-status account). Rubin's own distinctive point: the Japanese causative is systematically ambiguous between English "make" (force) and "let" (permit) — a distinction English *requires* a lexical choice for but Japanese grammar does not mark at all, which is why Japanese speakers of English often confuse "make" and "let." Demonstrates layered causative+directional chains (kakasete kureta/ageta/moratta — "he let me write it for him"-type readings) requiring the same final-verb-first parsing strategy as the plain directional verbs, now tracking up to three distinct participants (the causer, the one caused, and — if a directional auxiliary is present — the beneficiary). Worked real-text example: Watanabe Jun'ichi's angry *Sugu kakari o yonde kite yarasero* ("Go get the person in charge and make him do it!") — a blunt-imperative causative (*-ro* ending) addressed to an innkeeper, itself causing the innkeeper to cause a third party (the room clerk) to act, three distinct participants total; cites several actual overly-literal published mistranslations of comparable forms as cautionary examples (e.g. rendering *yarasero* as "do it" without recovering the embedded "make him" causative sense). A second real-text example: the office-sign cliché *Honjitsu wa yasumasete itadakimasu* ("We [humbly] take the liberty of resting today," i.e., "Closed today") is traced morpheme-by-morpheme as a causative (*yasumaseru*, "let/make rest") plus a maximally humble receiving auxiliary (*itadaku*), together literally meaning "[I] humbly receive [your] letting [me] rest" — offered as the single most outrageous-looking-but-perfectly-ordinary verb chain in colloquial/sign Japanese, and traced back to the author's own earlier book title *Gone Fishin'* as his go-to loose gloss for it. A third real-text example, *(o-ukagai sasete itadaku)* ("I will humbly call upon you again"), layers a humble verb (*ukagau*, "to humbly visit") + causative + *itadaku*, and is shown to generate a whole range of equally valid English paraphrases once the zero-pronoun participants are correctly tracked, from maximally literal ("I shall humbly receive from you your allowing me to humbly visit you") to maximally natural ("I will call upon you again if I may"). |
| -(r)areru (passive, incl. suffering/adversative passive) | passive suffix | verb suffix | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Partially covered in 047 (Unit 30, the affective/adversative passive). Rubin's distinctive contribution: a sharply worded methodological warning against "passivication" — his own coined term (credited to a student, John Briggs) for the error of translating an active Japanese verb into an English passive "to make the problem go away" when a student can't otherwise identify the verb's subject. Demonstrates with a careful English-internal primer on transitive/intransitive and active/passive first (only transitive verbs can passivize; "Laura was arrested" vs. "The police arrested Laura" vs. intransitive "Laura ran," which cannot passivize since it has no object to promote), establishing the general principle before applying it to Japanese. Separately names the Japanese "suffering" or "adversative" passive (*rareru*, formally identical to the ordinary passive) as the construction where the marked subject is not grammatically acted upon by the rest of the sentence at all, but merely stands in some affected relationship to an event — cautions that actual distress/suffering is not inherent to the form itself and is usually only conveyed by an added explicit complaint word (*komatta*, *hidoi me ni atta*), not by the passive morphology alone. Worked minimal triple distinguishes *Kaban o nusunda* (plain active, unnamed subject, "[X] stole the suitcase"), *Kaban ga nusumareta* (ordinary passive, named subject *kaban*, "The suitcase was stolen"), and *Kaban o nusumareta* (suffering passive — *kaban* stays marked as an object with *o*, so it cannot itself be the suffering subject; a zero-pronoun "I" is the actual *rareru*'d subject, yielding "I suffered someone's stealing my suitcase"/"My suitcase got stolen [on me]"). A real-text example from Murakami Haruki's "Tony Takitani" shows the suffering passive used with *no actual suffering implied* (*na o shirareta*, "[he] 'suffered' the knowing of his name," i.e. simply "was somewhat known"), reinforcing that the form's "suffering" label is a misnomer, not a semantic guarantee. |
| -(s)aseru + -(r)areru (passive-causative) | combined causative-passive suffix chain | verb suffix | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Not separately named in prior Japanese `established/` extractions. Rubin's framing: once the causative and the passive are each understood individually, the passive-causative is "easy" — it is near-always a first-person complaint that the speaker was forced by someone else to do something (*yameru* "to quit" → *yame-sase-rareta*, "I suffered X's forcing me to quit" = "I was made to quit"/"I was fired," optionally naming the forcer with *ni*: *Shachō ni yamesaserareta*, "I was made to quit by the president"). With a transitive base verb, the thing acted upon is tracked as a third zero-pronoun participant alongside the forced "I" and the forcer (*Toraserareta*, "I suffered X's forcing me to take it" = "I was made to take it"). |
| naoru / katazuku | intransitive "self-moving" verbs ("get well/fixed," "become straight/tidy") paired with transitive naosu/katazukeru | verb | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Not covered in prior established/ particle-dictionary extractions. Rubin's point: Japanese has many such intransitive/transitive verb pairs describing a change of state without any implied agent (*heya ga katazuku*, "the room becomes straight/tidy," with no reference to a tidier, not even a zero pronoun) — translating these naturally into English nonetheless forces a passive ("the room has been put in order," "it got fixed"/"it was repaired") purely as a translation expedient, not because the Japanese original is itself passive or implies an unnamed agent the way true passives do; flagged as a distinct, non-passive source of English-passive-shaped translations that a teacher should pre-empt before students conflate it with the genuine passive. |
| -te aru | resultant-state construction ("is in a state of having been X-ed") | grammatical construction | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Not covered in prior established/ extractions. Rubin's point: a transitive verb inflected with *-te aru* (*Mado ga/o shimete aru*, "the window is in a state of someone's having shut it") denotes a resultant state following a (usually human) agent's deliberate action, and is "virtually impossible not to passivize" in natural English translation ("the window has been shut") since English has no equivalent third category between active and passive — flagged as another case, like *naoru*/*katazuku*, where passivizing in translation is a legitimate expedient rather than the error "passivication" normally denotes, and recommends explicitly telling students this distinction rather than letting them treat all such passivized translations as interchangeable. |
| shizen kanō / jihatsu ukemi (natural potential / spontaneous passive) | grammatical concept — the potential/passive overlap zone for involuntary thoughts/perceptions | grammatical concept | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Not covered in prior established/ extractions — a genuinely distinct descriptive category from the ordinary potential or passive. Rubin's framing: certain potential-form verbs of thinking/feeling/perceiving (*kangaerareru*, *omowareru*, *omoeru*; the ko-/so-/a-demonstrative-adjacent *yō ni omoeru* "it seemed that...") describe a thought/perception as arising spontaneously/naturally in the speaker rather than being either a deliberate subjective act ("I think") or a true passive ("it was thought by me") — citing Anthony Alfonso's description of this as an "OBJECTIVE manner" of describing an involuntary mental event. Illustrated with a real literary example (Hoshino Tomoyuki-type narrator reminiscence in a story called "Man-Eating Cats": *tsuki no hikari o abite neko no me ga kirari to hikatta yō ni omoeta*, "the cat's eyes seemed to be flashing in the moonlight") where the natural-potential form conveys the narrator's own uncertainty about whether he really perceived what he describes, "floating somewhere between pure subjectivity and pure objectivity." Extends the same category to the potential-inflected *nakeru* ("to be moved/unable to help crying," from *naku* "to cry": *Nakete kichatta*, "I just couldn't help crying"), the fishing-specific *tsureru* (potential of *tsuru* "to fish": *Tsureta!*, "It has spontaneously caught itself on my line!" — contrasted explicitly with English anglers' conventional self-crediting phrasing, "I caught one!"), and the modest authorial convention *shōsetsu ga kaketa* ("the novel 'wrote itself,'" i.e. "was writable," never boastfully "I was able to write it"). The chapter closes with a full summary chart built around one transitive verb (*kaku*, "to write") showing all forms from this and the previous chapter side by side as complete, fully-participant-specified sentences (plain active *Kaita*; giving-direction *Kaite yatta/ageta*; receiving-direction *Kaite kureta/kudasatta*; causative *Kakaseta*; combined causative+directional forms; plain passive *Tegami ga kakareta*; suffering passive *Tegami o kakareta*; passive-causative *Kakaserareta*; resultant-state *Kaite atta*, explicitly labeled a "false passive"; and natural-potential *Kaketa*) — offered as a single compact reference table for distinguishing the whole family of forms by participant count and direction rather than by politeness level. |

| kara da | sentence-final "explainer" ("it's because...") | grammatical construction | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Not covered in prior established/ extractions (047's *-n-da*/*-n-da-kara* rows cover a related but distinct construction). Rubin's central claim: *kara da* (and its *wake da*/*no da* siblings) is not a minor tag-on but the true main clause/predicate of its sentence — grammatically, *kara* occupies the same slot as the B-noun in an *A wa B da* sentence, with everything preceding it functioning as a modifier of the implicit zero-pronoun subject "it"/"that" (referring back to a claim in the prior sentence, or to an objective situation visible to speaker and listener). Pairs naturally with a preceding *naze nara* ("why is this? it's because..."). Socially, *kara da* (and its kin) strongly implies the speaker is in the position of explaining/evaluating/preaching, presupposing the speaker has superior access to "objective reality" compared to the listener — frequent in moralizing or self-justifying essayistic prose (worked examples from Mishima Yukio's essays and autobiographical novel *Confessions of a Mask*, used as illustrations of a writer "always convinced of his rightness"). A key practical warning: Japanese paragraph breaks cannot be trusted to track logical units the way English ones do — a worked real-text example (Funahashi Seiichi, in an old Hibbett/Itasaka textbook) shows a paragraph opening with a bare *kara da* whose referent is not in its own paragraph at all but in the *previous* one, which a reader must backtrack to in order to recover the antecedent "it." |
| wake da / no da | sentence-final "explainers" ("that means...," "it's that...") | grammatical construction | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | 047/047b already cover *no-da*/*-n-da* (Units 63–64) under its "mutual-understanding-reinforcing" function; Rubin's distinctive addition here is the parallel with *wake da* and a sharper claim about what the *no* in *no da* actually is. He distinguishes *wake* (an ordinary, independent noun meaning "meaning, reason, grounds" per Kenkyūsha, as in *wake o hanasu*, "to explain") from *no* (not an independent noun but a grammaticalized element, probably historically derived from *mono* "thing") — despite this difference, *wake da* and *no da* are shown to be freely interchangeable in most contexts (worked near-identical paired examples from Kenkyūsha: *Warui imi de itta no de wa nai* / *Betsu-ni fukai imi ga atte sō itta wake de wa nai*, both glossing to "I didn't mean anything serious by it"). Explicit correction of a common mislabeling: *no da* should never be called an "extended predicate," as though it merely adds incidental information to an already-complete sentence — rather, by the time a sentence reaches its *no da*, the grammatical subject has *changed* to the zero-pronoun "it"/"that," with everything before *no* now functioning as a modifying clause. In spoken Japanese, contracted *n da*/*n desu* (or bare feminine-speech *no*) is distinguished from the "look back at what was just said" function: it instead points to a shared *objective situation* visible to both speaker and listener rather than literally to prior words — illustrated with Anthony Alfonso's minimal pair *Omoshiroi desu ka* (a neutral question about a book) vs. *Omoshiroi n desu ka* (asked of someone visibly absorbed/smiling, i.e. "is what's making you react like that interesting?") — the *n desu ka* version presupposes a shared observed situation the question is seeking to confirm/explain, not new information out of nowhere. |
| hodo / kurai (kurai) | quantitative/comparative nouns ("to the extent that," "as much as") | noun | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Not covered in prior established/ extractions. Rubin's own mnemonic device: the negative usage ("not as X as Y," *Kotoshi wa kyonen hodo samuku nai desu*, "This year is not as cold as last year") is easy for students, but the positive usage (an extreme-condition statement followed by *hodo*/*kurai* + a consequence, *Kyō wa benkyō ga dekinai hodo tsukareta*, "Today I'm so tired that I can't study") is comparatively hard to internalize — he credits his own recurring classroom device of citing Johnny Carson's *Tonight Show* monologue formula ("It was so hot that...," "It was so cold that...") as the clearest available model for the positive construction's rhetorical shape, lamenting that Carson's 1992 retirement removed a reliable illustrative source for new cohorts of students. Extended worked-example set (six positive-ending sentences, each decomposed via "How much/how X is it?" Carson-style follow-up questions: *yasumu hima ga nai hodo hatarakimasu*, "works so much he has no time to rest"; *kodomo de mo dekiru hodo yasashii*, "so easy a child can do it"; *yoru nemuru koto ga dekinai hodo shinpai shimashita*, "worried so much I couldn't sleep"; *ōbā mo iranai hodo atatakai*, "so warm you don't need an overcoat"; *nakitai hodo komatta*, "so upset I wanted to cry"; *tsukaikirenai hodo kane ga aru*, "so much money he can't possibly spend it all") and three negative-ending sentences similarly decomposed via "not as X as what?" (*mizu wa biiru hodo oishiku nai*, "water isn't as good as beer"; *migi no me wa hidari hodo akaku nai*, "the right eye isn't as red as the left"; *konshū no shiken wa senshū no hodo muzukashiku nai*, "this week's exam isn't as hard as last week's"). A final example, *sore hodo omoshiroku nai desu yo* ("It's not all that interesting"), shows *hodo* functioning idiomatically with no clear antecedent for *sore* at all, paralleling the vague English idiom "not all that interesting." |

| shiru | "to come to know" (not "to know") — "find out, learn" | verb | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Not covered in prior established/ particle-dictionary extractions. Rubin's central correction (opening with an anecdote about a fellow instructor's folk-etymology myth linking *shiru* to a taboo homophone for "backside," which he flags as false but was nonetheless once told to him in good faith): *shiru* does not mean static "to know" but inchoative "to come to know/find out/learn" — Japanese conceives "knowing" as a two-part event (finding something out, then retaining it), so the ordinary way to say "I know" is the progressive/resultative *shitte iru* ("I am in a state of having found out"), not bare *shiru*. The negative *shirimasen* ("I don't know") is unmarked/common despite looking like it should pattern with the rare bare-*shiru* positive, because saying "I haven't found out about it yet" (negative) is natural while a hypothetical *shitte imasen* ("I am not in a state of having found out") would sound like an oddly deliberate declaration of ongoing ignorance rather than a simple "I don't know." Grammatically straightforward otherwise: transitive, takes a direct object exactly like English "know" (*Ano hito o shitte imasu ka*, "Do you know him?"). |
| wakaru | "to be clear/understandable (to someone)" — never "to understand [something]" in the English transitive sense | verb | core | — | contemporary (source published 1998/2002) | — | — | grammar_reference | n/a | verified | Not covered in prior established/ extractions. Rubin's central correction: English "understand" is transitive ("I understand that"), tempting students to treat *wakaru* the same way (incorrectly producing *Watashi wa sore o wakaru*), but *wakaru* is intransitive from the thing-understood's point of view — things themselves "are clear" or "do wakaru," and a person to whom they are clear is usually marked with *ni* (sometimes contracted into a *wa*-marked topic, e.g. *Watashi wa wakaranai* as a contraction of *Watashi ni wa wakaranai*, "to me, it's not clear"). Recommends "I don't get that joke" over literal "that joke doesn't clarify itself to me" as a natural translation, while flagging that the even-more-literal rendering ("That joke doesn't make sense to me") is closer structurally. Notes a further wrinkle: the thing being (not) understood is not reliably marked with a "clean *ga*" the way a first model sentence might suggest — negative *wakaru* sentences often promote that element to *wa* instead (*Kare ni wa sono share wa wakaranakatta*, "The joke was lost on him") purely because negative sentences in Japanese generally want to throw emphasis forward onto the negated verb, a point Rubin cross-references to "Wa and Ga." Gives a worked set of Kenkyūsha-dictionary-sourced examples spanning the full range of participant-marking patterns (*Kimi ni wa koko no imi ga wakaru ka*, "full" model, both understander and understandee marked; *Watashi no iu koto ga wakarimasu ka*, "you" recovered from context; *Sonna koto wa watashi ni wa chinpun-kanpun de wakaranai*, "it's all Greek to me," with the understandee itself promoted to a *wa*-topic; *Kimi no iu imi wa wakatte iru*, "I know what you mean," using the resultative *wakatte iru* form paralleling *shitte iru*). |

## Grammar points

### Introduction — "Learning the Language of the Infinite"

Polemical framing chapter, not a grammar point proper: Rubin opens by quoting the "Japanese is the
language of the infinite" scene from James Clavell's novel *Shōgun* as representative of a
persistent Western (and sometimes Japanese-promoted) myth that Japanese is inherently vague,
mystical, or uniquely untranslatable — attributing this instead to (1) genuine but ordinary
structural differences from English (verb-final word order, pervasive subject/object omission when
recoverable from context) being mistaken for philosophical vagueness, and (2) Japanese *social norms*
sometimes requiring indirect/incomplete expression, which he distinguishes sharply from the
*language itself* being imprecise — a social-register effect, not a grammatical one. He cites the US
government's Foreign Service Institute language-difficulty rankings (Japanese/Chinese/Korean/Arabic
as "Class Four," requiring roughly 1,410 instructional hours vs. 750 for "Class One" languages like
French/Spanish) as evidence the language's real difficulty is structural distance from English, not
mysticism. States the book's purpose: to make the specific grammatical constructions that cause
students the most trouble (word order, particle choice, honorific/directional verb complexes)
graspable through precise English-language parallels rather than impressionistic "intuition," and
flags that Part One is a sequence of essays meant to be read in order (each assumes the previous),
while Part Two's shorter pieces can be read in any order.

### The Myth of the Subjectless Sentence

Rubin's central claim (see *(zero pronoun)* vocabulary row): the common textbook claim that Japanese
sentences "lack subjects" conflates two different things — a sentence *referring to* no agent/
experiencer (false; every predicate implies one) vs. a sentence not *overtly naming* that agent in
the sentence itself (true, and unremarkable — English does the same whenever a referent is already
established, e.g. "He mailed the check," which is equally "mysterious" to a true beginner who hasn't
been told who "he" is). Demonstrates with an extended worked passage (two men, a drunken misadventure
at the Seine) rewritten three ways: with every noun repeated in full (absurd), with English pronouns
restored (natural English), and with pronouns stripped entirely once the subject is established
(reads oddly in English but is exactly how the equivalent Japanese passage would be constructed) —
making the case concretely that omitting an already-known subject is a matter of economy, not
vagueness. Cites Okutsu Keiichirō (a Japanese linguist) and Eleanor Jorden's *Japanese: The Spoken
Language* in support. Crucial clarifying point: *subjects* (in the sense of "the entity the sentence
is about") never actually disappear from a Japanese sentence's meaning — only their *overt
mention* does; the verb itself (which "rarely" drops) is the most important cue to what's being
predicated of that unmentioned subject. Explicitly recommends extremely literal, non-passive-leaning
translation practice (never silently converting an active Japanese verb into a passive English one)
as a technique for forcing students to keep track of exactly how many distinct participants are
implied by a complex verb chain (his example: *Sugu kakari o yonde kite yarasero*, a multiply-nested
causative/directional construction glossed as requiring the translator to consciously count the
number of people involved).

### Wa and Ga: The Answers to Unasked Questions

See vocabulary row for *wa* above. Rubin frames the whole *wa*/*ga* system around a "Question Man"
analogy (Steve Allen's old talk-show bit of reading an "answer" aloud and then guessing the
unasked "question" it answers): any given Japanese sentence's particle choice reveals what implicit
question is being answered, and the practical heuristic for a learner is to reconstruct that implicit
question rather than memorize a flat rule about *wa* meaning "topic" and *ga* meaning "subject."
Worked minimal set: *Dō shimashita ka* ("What did you do?") answered neutrally with bare *Ikimashita*
("[I] went," no particle, no emphasis) vs. *Soshite, Yamamura-san wa? Dō shimashita ka* ("And you,
Mr. Yamamura? What did you do?") answered with *Watashi wa ikimashita* (*wa* marks contrastive
emphasis — "*me*, [in contrast to the previous person,] I went") vs. *Dare ga ikimashita ka* ("Who
went?") answered with *Watashi ga ikimashita* (*ga* marks the answered-for element itself — "*I*
went [not someone else]"). English speakers' habitual over-use of overt subject pronouns (saying "I
went" even when unemphatic) is attributed to English simply requiring an overt grammatical subject
in every finite clause, a requirement Japanese does not share — the practical teaching point being
that students should practice *not* reaching for *wa* or *ga* by default the way they reach for
English "I," and instead ask what question is implicitly being answered before choosing (or
omitting) a particle at all.

**Directional emphasis: *ga* emphasizes backward, *wa* emphasizes forward.** Rubin's own named
mnemonic for the pair: *ga* throws emphasis onto whatever immediately *precedes* it (hence
interrogatives like *dare*/*nani*/*dore* — themselves already the focus of a question — are never
followed by *wa*, only *ga*, since *wa* would misdirect emphasis onto what comes after an
interrogative instead of the interrogative itself), while *wa* throws its emphasis onto whatever
*follows* it, building rhetorical "suspense" toward the predicate (illustrated with Patrick Henry's
"I know not what course others may take, but as for me, give me liberty or give me death!" as an
English parallel of a topic-establishing "as for" clause followed by its rhetorical payoff). A
modifying clause softens *ga* to *no* for this same backward-emphasis reason (*Shimizu-san no
hirotta saifu wa koko ni arimasu*, "The wallet [that] Mr. Shimizu found is here," de-emphasizing
*Shimizu-san* since the clause's point is the wallet, not who found it) — *ga* is retained only when
the finder himself needs emphasis (*Shimizu-san ga hirotta...*, "The wallet *Mr. Shimizu* found..."). A
worked example from the *Encyclopedia Japonica*'s crucifixion entry shows how overlooking this
backward/forward-emphasis asymmetry produces a mistranslation: *Iesu Kirisuto no haritsuke ga yūmei
de aru* does not mean "the crucifixion of Jesus Christ is famous" (misreading *ga* as marking a broad
topic) but "[among crucifixions,] that of Jesus Christ [specifically] is the famous one" (*ga*
emphasizes the immediately preceding "Jesus Christ," not the general concept of crucifixion).

**Not a negative/positive split.** *Wa* appears to correlate with negative sentences and *ga* with
positive ones, but Rubin shows this is an artifact of *wa*'s single consistent function (differentiate
from alternatives, then emphasize what follows) rather than a dedicated negative-marking role:
*Ikitaku nai* ("I don't want to go," ga-type/neutral negative) vs. *Ikitaku wa nai* ("I don't want to
go [though I might like to hear how it turned out]," wa-type/differentiating negative) contrasts with
exactly parallel positive-sentence pairs like *Okane ga aru* ("I have money," neutral) vs. *Okane wa
aru* ("I *do* have money [but there's some other complication implied]"), and *Nihon-jin ni mo fuman
wa aru* ("Japanese people *do* have their discontents too") — a positive sentence with the same
differentiating *wa*.

**Parallel to English "the"/"a" (not just "as for").** Citing Basil Hall Chamberlain's 1888
observation (itself building on W. G. Aston's parallels between *wa* and certain Greek/French
constructions) and Anthony Alfonso's *Japanese Language Patterns*: *wa* and *ga* correspond fairly
closely to English "the" (definite, already-known referent) and "a" (indefinite, newly-introduced
referent) respectively — "the man" (*otoko wa...*, already known, about to receive new information)
vs. "a man" (*...otoko ga haitte kita*, "a man came in," a new entity entering the discourse). Rubin
notes both pairs are notoriously hard for learners in both directions (Japanese speakers of English
struggle permanently with "the"/"a" just as English speakers struggle with *wa*/*ga*), illustrating
with an anecdote about a Japanese employer who, learning that English "the" and "a" were "useless"
function words, suggested docking a per-word-paid translator's fee for every one used — the
translator's retort ("Better yet, *you* do the translations...") got him fired on the spot.

**The strongest claim: *wa* never marks a sentence's grammatical subject, only its topic — ever.**
Where *ga* always marks the grammatical subject of the verb/adjective it precedes, Rubin insists
(against looser textbook phrasing that "wa can mark the subject") that *wa* marks only the *topic of
discussion*, full stop, and that the real grammatical subject of the verb in a *wa*-topic sentence is
always the zero pronoun that silently follows. Demonstrates with *Watashi wa ikimashita*: the overt
subject-like appearance is a relic of childhood-grammar-lesson "double subjects" ("My uncle, he's a
nice man") — *watashi* sets the topic, and a silent/zero pronoun (not *watashi* itself) is the true
subject of *ikimashita*. Extends this to object-topic sentences (*Sono koto wa kyō hajimete
kikimashita*, "That matter, [I] heard about it today for the first time" — the object of *kikimashita*
is a zero pronoun standing for *sono koto*, not *sono koto* itself) and time/location-topic sentences
(Alfonso's *Aki wa sora ga kirei desu*, "As for autumn, the sky is clear," where *aki* is a time
topic, not a grammatical subject of anything). Crucial corollary: a *wa*-marked topic's underlying
grammatical role (subject, object, time, location, etc.) can only be identified retrospectively, once
the whole sentence has been read — *wa* itself gives zero advance notice of what role its topic will
turn out to play, unlike "the"/"a," whose referent's role is usually clear from surrounding English
syntax already in place. The famous textbook sentence *Zō wa hana ga nagai* ("As for elephants,
[their] trunks are long") is flagged as a "grammatical red herring" — a pedagogically manufactured
example (useful only for naming animal traits in a picture-book-style list) rather than a sentence a
real speaker would produce outside a classroom; genuinely natural double-*ga*-embedded *wa* sentences
do occur (*Aitsu wa atama ga amari yoku nai nee*, "That guy's not too bright, is he?"; *Oyaji wa atama
ga hagete kita*, "The old man's lost a lot of hair") but always presuppose a larger implied
context/discourse, never existing in a vacuum the way classroom drill sentences do.

**Another red herring: *Boku wa unagi da* ("I am an eel").** A sentence Japanese speakers themselves
enjoy as a joke about their own language. Resolved the same way: *boku* is the topic, not the subject
of *da*; the true (zero-pronoun) subject of *da* is "what I want to eat," recoverable only from a
context already established (e.g., a group ordering food) — "(as for) me, [what I want to eat] is
eel," not "I am an eel." Parallel simpler case: *Sore wa pen da*/*desu* ("That is a pen") is shown to
be an artificially complete classroom-drill sentence; a natural reply to "what is this?" is the
non-sentence fragment *Pen desu* ("[It's] a pen"), and *Sore wa pen desu* in real use means something
narrower — "That [specific object, as opposed to some other object in view] is a pen" (e.g. a
shop clerk correcting a customer pointing at the wrong item) — never a context-free ESL-drill
equivalence.

**Why a story's opening sentence can still use *wa* despite no prior context: the "known-context"
illusion.** A novel's first sentence is the one place a *wa*-topic appears to spring from nowhere, but
Rubin argues the author is *exploiting* wa's known-topic implication to manufacture an impression of
pre-existing reality — functionally identical to English "the" doing the same job at a narrative's
start (Henry James's *Portrait of a Lady*, "the hour dedicated to the ceremony known as afternoon
tea," or in medias res openings like Hemingway's "There were only two Americans stopping at the
hotel," where "the hotel" presumes a shared context the reader doesn't actually have yet). Contrasts
three Japanese novel-opening strategies: (1) Natsume Sōseki's *Mon* opens with a *wa*-marked named
character (*Sōsuke wa sakki kara engawa e zabuton o mochidashite...*, "Sōsuke had brought a cushion
onto the veranda...") — manufactured intimacy, exactly like "Buck did not read the newspapers"
opening Jack London's *The Call of the Wild*; (2) Sōseki's earlier *Sanshirō* opens instead with an
unnamed *ga*-marked-then-*wa*-marked entity ("He drifted off, and when he opened his eyes, THE
woman...") — the definite article/*wa* implying familiarity with an as-yet-unnamed character,
heightening literary immediacy; (3) traditional fairy-tale openings use *ga* for the very first
mention of characters (*Mukashi, aru tokoro ni, ojiisan to obaasan ga sunde imashita*, "Long ago, in a
certain place, there lived an old man and an old woman") since the storyteller's formula explicitly
establishes new entities rather than presupposing them, paralleling English "there lived a girl with
long, golden hair." A first-person narrator, by contrast, always introduces himself with *wa* from the
outset, since a narrating "I" never needs his own existence established. Two further literary examples
(from Murakami Haruki's 1985 novel and an unidentified work) show a *ga*-marked subject embedded
inside a *wa*-marked subordinate clause at a narrative's very opening — the *wa* here marks the
subordinate clause as a whole (e.g., "it was already after the beginning of August when Tomimori
brought the woman to the house"), not the narrative's protagonist, who is still freshly introduced via
*ga* within that clause.

**Summary principle.** Across every case — subjects, objects, time expressions, locations, story
openings — *wa* performs exactly one consistent double function: differentiating its marked topic from
other implied topics, and signaling that the important new information is about to follow. It places
no grammatical restriction whatsoever on what kind of information can follow, which is precisely why
its apparent "role" (subject-like, object-like, adverbial) can only be labeled after the fact.

### The Invisible Man's Family Reunion

Framing device: if the "invisible man" (zero pronoun) of the previous chapter married an "invisible
woman" and had descendants, their "family reunion" would be the full cast of directional-giving,
causative, passive, and combined verb forms — each of which hides one or more unnamed participants
that the learner must track by working backward from the final verb in the chain. See vocabulary
rows above for the specific verbs (*yaru*/*ageru*/*sashiageru*, *kudasaru*/*kureru*, *morau*/
*itadaku*, the causative, the passive). Rubin's single unifying methodological point across the whole
chapter: **always identify the subject of the grammatically final verb in the chain first**, since
that verb's own meaning (give vs. receive vs. cause vs. suffer) fixes who that final subject must be
("I" for *morau*/*itadaku*/*ageru*-type forms addressed by a speaker, "the other person" for
*kureru*/*kudasaru*), and only then work backward to recover who performs each earlier verb in the
chain. Flags four real (uncorrected) amateur mistranslations of a single causative-imperative sentence
collected from his own acquaintances, used as a cautionary gallery of what happens when a translator
loses track of the zero-pronoun participants (e.g. garbling a three-participant chain down to a
vague two-participant command). Gives worked real-text examples of up to three-participant causative
+ directional chains (see vocabulary rows for *-(s)aseru* and *-(r)areru*) and insists that even a
famously "impossible-looking" two-verb, zero-noun sentence like *Honjitsu wa yasumasete itadakimasu*
is fully decodable and unambiguous once each verb's fixed participant structure is applied — not
evidence of vagueness, but of maximal grammatical compression achieved precisely because the
participant structure is so rigidly fixed that no words are needed to spell it out.

### Passives, Passivication, and the Passive-Causative

See vocabulary rows for *-(r)areru*. Central methodological warning (see "passivication" vocabulary
row): translating an active Japanese verb into a passive English one to avoid the work of identifying
its subject is diagnosed as the single most damaging habit a Japanese-learner can develop, because it
discards the very information (who did what to whom) that must be tracked to handle more complex
verb chains later. Establishes from English-internal grammar first: only transitive verbs passivize
in English (worked examples: "Laura was arrested" / "The police arrested Laura" / intransitive "Laura
ran," which cannot passivize since "ran" takes no object to promote to subject); the chapter's stated
plan is to use this established English baseline before tackling how the Japanese passive differs
from it (covered in subsequent pages not yet read for this file). Distinguishes the ordinary passive
from the "suffering" or "adversative" passive (*rareru*, formally identical to the regular passive):
the suffering passive's marked subject is not necessarily the grammatical patient of the verb's action
at all, merely someone affected by/standing in relation to an event, and — contrary to its common
name — actual "suffering" is not inherent to the grammatical form itself; genuine distress is usually
signaled only by an added explicit complaint word (*komatta*, *hidoi me ni atta*), making the English
translation's apparent misery level dependent on these extra words, not on the passive morphology.
Worked minimal triple (see vocabulary row for *-(r)areru*) walks through *Kaban o nusunda* / *Kaban ga
nusumareta* / *Kaban o nusumareta*, and a comic dialogue ("Pardon me, officer, but I've just been
*rareru*'ed...") dramatizes why "I was stolen my suitcase" is a legitimately odd-sounding but fully
grammatical literal rendering once the suffering passive's actual subject (the victim, not the
suitcase) is correctly tracked. Recommends a specific teaching sequence: require students to translate
*everything* into active-voice English for as long as possible before the Japanese passive is
introduced at all (even already-passive-feeling verbs like *iu* "to call/be called," as in *Itō to iu
hito*, better rendered "a man by the name of Itō" than the passivized "a man who is called Itō") so
that the eventual introduction of the genuine Japanese passive doesn't compound an existing bad habit.
A famous real-world example: the Hiroshima atomic-bomb memorial inscription *Ayamachi wa
kurikaeshimasenu kara* ("...for [we/one] will not repeat the mistake") uses an unnamed zero-pronoun
subject whose referent (the controversial "we") was the subject of public debate when the monument
was unveiled — Rubin argues the common passivized English translation ("the mistake will not be
repeated") *weakens* the original specifically by erasing the demand for a responsible subject that
the active Japanese original (quietly) still carries.

Separately treats two look-alike-but-distinct constructions that also tend to get passivized in
translation without being true passives (see vocabulary rows for *naoru*/*katazuku* and *-te aru*):
intransitive "self-moving" verbs describing a change of state with literally no implied agent at all,
and the resultant-state *-te aru* construction, which describes a state following a deliberate human
action. Both are flagged as legitimate cases where passivizing the English translation is a practical
expedient (English simply lacks an equivalent third category), to be explicitly distinguished for
students from "passivication" proper — the latter being an avoidable translation error, not a
structural necessity.

### The Natural Potential

See vocabulary row for *shizen kanō*/*jihatsu ukemi*. Rubin explicitly revisits and partially revises
his own Introduction-chapter claim that Japanese has no genuine "twilight zone" of vagueness,
identifying the natural-potential/spontaneous-passive overlap as a real exception — not evidence that
Japanese itself is vague, but a specific, namable grammatical category occupying real middle ground
between fully subjective ("I think") and fully passive ("it was thought by me") framing of an
involuntary mental or perceptual event. See vocabulary row for worked examples (the "Man-Eating Cats"
moonlit-cat-eyes passage, *nakeru*, and the self-effacing fisherman's-catch framing). Quotes Anthony
Alfonso's *Japanese Language Patterns* describing this as an "OBJECTIVE manner" of describing
something that happens to or within a person rather than something the person deliberately does —
Rubin's own addition is to flag that essayists sometimes exploit the same form (*kangaerareru*,
*omowareru*) to present a personal opinion as if it were objectively arising common sense, "ducking
responsibility for [their] own ideas" by grammatical means.

### The Explainers: Kara Da, Wake Da, No Da

See vocabulary rows for *kara da* and *wake da*/*no da*. Opening frame (Part Two, "Out in Left
Field," begins here): despite the Japanese reputation as lovers of silence, Rubin argues they
"explain" constantly, often explaining a personal opinion in a form that grammatically presents it as
objective fact — these three sentence-final constructions are the main device for doing so. Unifying
analysis: all three function as the main predicate of their sentence, not as a minor appended tag —
"the *kara da* IS the sentence, and everything leading up to it is just a modifier," paralleling how a
bare *B da* functions as the predicate of an *A wa B da* sentence once *A wa* is dropped (worked
parallel: *Kore wa pen desu* → *Pen desu*, "it's a pen"). Demonstrated at length with real texts: a
Murakami Haruki short story about a vanished zoo elephant uses *naze nara... kara da* to explain, two
sentences later, why no witnesses saw the elephant after a certain hour; two Mishima Yukio essay
excerpts (including from *Confessions of a Mask*) are read as cumulative evidence of a writer
habitually asserting his own rightness via this construction; and a Funahashi Seiichi textbook passage
demonstrates the single biggest practical trap — a paragraph-opening *kara da* whose "it" refers back
across a paragraph break into the *previous* paragraph, teaching that Japanese paragraph divisions
cannot be trusted to track logical/argumentative units the way English ones generally do. Closing
point distinguishing written *no da* from spoken *n desu ka*: in running prose, *no da* typically
looks back at what was *said* in a preceding sentence, while in conversation, *n desu ka* instead
typically points to a shared *objective situation* observable by both speaker and listener (Alfonso's
*Omoshiroi n desu ka* example) — in both registers, treating *no da* as a mere "extended predicate"
tacked onto an unchanged sentence is flagged as the single most common analytical error, since the
sentence's grammatical subject has in fact already shifted to the implicit "it"/"that" by the time
*no* appears. Two further real-text examples extend the analysis: a prescriptive passage from a
Japanese high-school-abroad rulebook (*no deshitara*/*no de atte*/*no de wa arimasen*) is shown, via
back-translation against its plain, non-explanatory English original, to have been deliberately
"thickened" with explanatory *no da* forms by the Japanese translator — evidence that Japanese
expository/didactic prose reaches for overt explanatory marking in places English simply doesn't
bother to, not because Japanese *requires* it grammatically but because of a genre/register
convention; and an extended passage from Murakami Haruki's disappearing-elephant story is given in
both a maximally literal, explainer-preserving translation ("That is to say that...," "For that
reason...") and a smoothly idiomatic one with the explicit markers silently absorbed — demonstrating
that fluent translation routinely discards this surface feature entirely rather than attempting to
render each *no da* with its own English tag. Closing generalization: a fictional narrator who poses
as an essayist/anthologizer/clipping-collector (as in the elephant story) will show measurably more
*no da* usage than the same author's purely descriptive prose, because each *no da* is "a constant
reminder of the presence of the narrator: observing, questioning, judging, and often subtly hinting
that he or she knows more than we do."

### The Johnny Carson Hodo

See vocabulary row for *hodo*/*kurai*. Contrasts the easy-to-learn negative comparative use of
*hodo*/*kurai* ("not as X as Y") with the harder positive use (an extreme-condition clause followed
by *hodo*/*kurai* plus a resulting consequence clause), and recommends Johnny Carson's *Tonight Show*
monologue-style extreme-condition statements ("It was so hot that...") as the clearest available
teaching analogy for the positive construction's rhetorical shape — a problem Rubin says became
harder to teach once Carson retired from late-night television in 1992, since the show had reliably
supplied a fresh crop of ready-made parallel examples every season. The practical method, repeated
across the chapter's many worked examples (see vocabulary row): isolate the *hodo* clause and the
main clause separately, restate the main clause as a simple positive or negative statement on its
own, then ask the Carson-audience-style clarifying question ("How much/how X is it?" for positive
mains, "Not as X as what?" for negative mains) to recover exactly what work the *hodo* clause is
doing. A final example (*sore hodo omoshiroku nai desu yo*, "It's not all that interesting") shows the
construction can also function idiomatically with no recoverable antecedent at all, directly
paralleling the equally vague English idiom "not all that interesting."

### Kanji

A short, deliberately narrow chapter: Rubin explicitly declines to discuss kanji in any depth,
arguing (citing linguist George Sansom's 1930s observation that Japanese's phonology was unusually
well-suited to alphabetic writing, and calling the kanji-based writing system a historical accident
rather than a reflection of Japanese grammar, thought patterns, or worldview) that kanji are a
writing-system problem orthogonal to the grammar this book is about — "they are certainly not the
Japanese language" — and states this book will have nothing further to say about them. Included here
only because it is a real, if brief, chapter of the source; no grammar point is extracted from it per
the coverage rule, since it is explicitly framed by the author himself as off-topic.

### Shiru and Wakaru: To Know You Is Not Necessarily to Understand You

See vocabulary rows for *shiru* and *wakaru*. Opens with an anecdote debunking a folk-etymological
myth (a previous instructor's claim that *shitte iru* is preferred over bare *shiru* to avoid an
embarrassing homophone) as unfounded, used to set up the chapter's real explanation: *shiru* is
inchoative ("come to know/find out"), not stative "to know," so the ordinary present-tense "I know"
requires the resultative *shitte iru* form — a two-step conception of knowledge (finding out, then
retaining) distinct from English's single stative verb. The negative asymmetry (*shirimasen* common,
*shitte imasen* would sound like a deliberate statement of persistent ignorance) is explained as a
consequence of this same two-part structure, not an arbitrary exception. Devotes most of the chapter
to *wakaru*, diagnosed as harder for English speakers specifically because of "a combination of
back-translation and misunderstanding of *wa*": since English "understand" is transitive, students
default to marking the understood thing as a direct object (incorrect), when *wakaru* is actually
predicated of the thing being understood itself (which "is clear" or "does wakaru"), with the
understander (if mentioned) marked by *ni* — sometimes contracted into a *wa*-topic (*Watashi wa
wakaranai* ← *Watashi ni wa wakaranai*). Separately explains why the thing-understood is sometimes
marked with *ga* and sometimes with *wa* despite seemingly inconsistent dictionary examples: *wa*
becomes more natural in negative sentences because Japanese generally wants to throw forward emphasis
onto a negated verb, cross-referencing "Wa and Ga"'s backward/forward-emphasis analysis directly.
Closes by noting *wakatte iru* (the resultative form of *wakaru*, parallel to *shitte iru*) as the
natural way to say "I understand"/"I get it" in an ongoing sense, deferred to a later chapter for
fuller treatment.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.
