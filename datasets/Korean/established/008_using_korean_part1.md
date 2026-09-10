# Korean — Established Vocabulary/Grammar: *Using Korean: A Guide to Contemporary Usage* (Part 1)

**Source:** Miho Choo and Hye-Young Kwak, *Using Korean: A Guide to Contemporary Usage*
(Cambridge University Press, 2008), PDF pages 1–170 of 337 (printed pages ~ix–158). Covers
the entire **"Style and usage"** part (chs. 1–8: sentence endings, honorifics, address terms
and pronouns, daily-situation formulas, conversational bridges, softening strategies, local
dialects, written-vs-spoken language) and most of the **"Vocabulary"** part (chs. 9–13.3:
native/Sino-Korean/loan-word contrasts, word formation, vocabulary contrasts, proverbs,
idioms, and sound symbolism through §13.3 "Mimetic expressions," stopping mid-chapter 13
at printed p. 158). Chapter 13.4 ("Expressions denoting feeling and touch") and chapters
14–22 (numbers, verb types, tense/aspect, modality, negation, particles, comparison,
conjunctives, complex sentences) are **out of scope for this file** — reserved for the
"part 2" companion extraction covering PDF pages 171–337.

**Coverage note.** This book's own title and organization ("Style and usage" as its own
half, distinct from "Grammar") make it the strongest register/contemporary-usage source
found in Korean Wave 1 so far, exactly as flagged in the dispatch. Per the coverage rule,
every grammar point in this range is covered below, paraphrased with a short illustrative
example. For vocabulary, the spec's "every distinct item" rule is followed literally for
compact, closed-class register vocabulary (address terms, pronouns, discourse
markers/fillers/interjections, dialect forms, honorific-verb pairs, word-formation affixes,
verb-choice contrast sets). For the **proverb (12.1), idiom (12.2), and sound-symbolism
(13.2–13.3) inventories** — which run to several hundred entries and are essentially the
book's own curated phrasal corpus — a substantial representative sample is extracted
instead of the full inventory, per the spec's copyright discipline against bulk-reproducing
a vocabulary box; each subsection states approximately how many more entries the source
contains beyond what is reproduced here.

**PDF text-corruption finding — fixed font-substitution cipher (decoded).** `pdftotext`
extraction of this PDF renders **all Hangul from p. 32 onward** (chapter 3 on) as garbled,
unrelated Unicode glyphs spread across several unrelated blocks (CJK Ext-A, Latin Extended
Additional, Miscellaneous Symbols/Arrows, Enclosed Alphanumerics, etc.), while the
surrounding English text and pp. 1–31 Hangul extract cleanly. This is the "fixed
character-substitution cipher" gotcha flagged in `00_Reference_Extraction_Spec.md`, not
unreadable OCR garbage: every corrupted glyph's Unicode code point is exactly **+36266**
from the correct Hangul syllable's code point (confirmed against >20 known words, e.g.
㧊→이, Ṗ→가, 㦚→을). A decode script applying this fixed offset (with a small excluded set
of genuine smart-quote/punctuation code points that would otherwise be falsely shifted)
was run across the full PDF-pages-1–170 text dump and cleanly recovered the Hangul used
throughout this file. A handful of residual artifacts remain undecoded by this scheme
(page-break placeholder characters, a few stray control characters, and — in the §13.1
plain/tense/aspirated-consonant illustration only — a set of consonant-jamo letters that
render via a *different*, not-yet-reverse-engineered font substitution); these are noted
inline where they affect specific entries below rather than silently guessed at.

**Honorific/speech-level register — the book's central axis.** Nearly every section of
chs. 1–8 is organized around Korean's speech-level system (존댓말/formal vs. 반말/casual,
with the 합니다/해요/해/한다 four-way split) and the subject-honorific suffix -시, both
treated in far more socially-grounded, register-contrastive depth than typical foundational
grammars. This is flagged throughout the Grammar points section below rather than only in
one place, per the dispatch's instruction to prioritize register content strongly.

---

## Vocabulary

### 1. Address terms and pronouns (ch. 3)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 저기요 | excuse me (to a stranger, e.g. a server) | interjection/hedge | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Also 여기요 in a restaurant. Font-cipher decoded (p. 32). |
| 여보세요 | hello? (raising one's voice to be heard) | interjection | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 32. |
| 아가씨 | miss; young unmarried woman | noun (address term) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Book flags this as potentially offensive today due to association with bar hostesses/low-level clerks; many older married women prefer it to 아줌마. p. 33. |
| 아줌마/아주머니 | ma'am; married/older woman | noun (address term) | colloquial/core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 33. |
| 선생님 | teacher; sir/ma'am (any profession) | noun (address term) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Generic respectful address term, not limited to teachers. p. 33. |
| 사장님 | boss; sir/ma'am (business) | noun (address term) | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 33. |
| 총각 | young unmarried man | noun (address term) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 33. |
| 김씨 (성 + 씨) | Mr./Ms. Kim (menial-job address, or neutral family-name reference) | noun + suffix | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | -씨 register spans impersonal to romantic depending on combination with full/first name; see 10.4.4 below. |
| 야/얘 | hey (you) | interjection/pronoun-substitute | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Used for children/close friends of similar age or younger. |
| 나/우리 | I/we | pronoun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Used with close friends, children, students, siblings, liberal-family parents; also default writing pronoun. §3.2.1. |
| 저/저희 | I/we (humble) | pronoun | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Humble counterpart of 나/우리; obligatory with 합니다-style endings. §3.2.1. |
| 너/너희 | you (2nd person, informal) | pronoun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Restricted to children/extremely close same-age-or-younger friends/siblings. §3.2.2. |
| 당신 | you (2nd person, restricted) | pronoun | formal/literary | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Traditionally between spouses; in poems/song lyrics; formal-audience advertising/questionnaires; also a marker of disrespect when fighting (언제 봤다고 반말이야! parallel). §3.2.2. |
| 자기 | you/self (romantic partners, close female friends) | pronoun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Also used reflexively for third parties ("him/herself"). §3.2.2, §3.2.4. |
| 그, 그녀 | he, she (literary 3rd person) | pronoun | literary/formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Not a native, well-established 3rd-person pronoun category in spoken Korean; these forms are a calque under English/translation influence, restricted to formal writing/speech. §3.2.3. |
| 이/그/저 + 놈/년/자식/새끼 | this/that punk/bastard (angry) | pronoun-substitute | taboo | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Same demonstrative-plus-noun pattern used affectionately for children turns insulting with these nouns. §3.2.3. |
| 여러분 | ladies and gentlemen; everyone | pronoun | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Addressing a group. §3.2.2. |

**Morpheme breakdown note (agglutination).** Korean address/pronoun forms regularly stack
particles: e.g. 저는 = 저 (I, humble) + 는 (topic particle); 그쪽이 = 그쪽 (that side/you) +
이 (subject particle). These are simple one-particle attachments and are not broken out
row-by-row here — see the dedicated **Morpheme breakdown examples** subsection below for
fuller, multi-morpheme verb forms, which is where this book's agglutination is most
information-dense.

### 2. Honorific-verb pairs (ch. 2 — subject- and object-honorification)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 드시다/잡수시다 | to eat (honorific of 먹다) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 잡수시다 preferred by some senior speakers; 드시다 sufficient generally. §2.1.4. |
| 계시다 | to stay/be (honorific of 있다, existential) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Contrasts with 있으시다 'to have' (honorific of possessive 있다) — same surface verb, two different honorific counterparts depending on meaning. §2.1.5. |
| 주무시다 | to sleep (honorific of 자다) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §2.1.4. |
| 돌아가시다 | to pass away (honorific of 죽다) | verb | formal/euphemistic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Unlike English "pass away" (usable for anyone, even a child), 돌아가시다 is reserved for an older/socially superior person — both euphemistic AND deferential. §2.1.4, §9.1. |
| 편찮으시다/아프시다 | to be sick/hurt (honorific of 아프다) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 편찮으시다 for whole-body illness, 아프시다 for a specific body part. §2.1.4. |
| 뵙다 | to see/meet (humble, object-honorific of 보다) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Only for deliberate seeing, not accidental. §2.2. |
| 여쭙다/여쭤보다 | to ask (humble, object-honorific of 묻다/물어보다) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §2.2. |
| 모시고 (가다) | to accompany/take (humble, object-honorific of 데리고 가다) | verb phrase | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §2.2. |
| (해)드리다 | to do (something) for (humble, object-honorific of (해)주다) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 주다 used when recipient is speaker; 드리다 when recipient merits deference. §2.2. |
| 말씀드리다 | to tell/say (humble, object-honorific of 말하다) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §2.2. |
| 말씀 | words; what someone says (honorific noun for 말) | noun | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §2.3. |
| 진지 | (honorific noun for) meal/rice, for 밥 | noun | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §2.3. |
| 댁 | (honorific noun for) house, for 집 | noun | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Cannot refer to one's own home (so not usable for a parent's house if you live there). §2.3. |
| 연세 | age (honorific of 나이) | noun | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Reserved for people old enough that asking their 연세/생신 won't offend; asking a young-looking teacher's 연세 makes them feel old — book explicitly flags this as a common learner mistake. §2.3. |
| -께서 | subject particle (honorific of -이/가) | particle | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Declining/optional in contemporary use; -이/가 not impolite even for honored subjects in most settings. §2.4. |
| -께 | indirect-object particle (honorific of -한테/-에게) | particle | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Obligatory in personal letters to a deferred-to recipient (e.g. 김교수님께). §2.4. |

### 3. Discourse fillers and conversational bridges (ch. 5)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 그러니까/그러니깐 | so; let's see (filler) | discourse marker | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.1. |
| 그럼 | well; then | discourse marker | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.1. |
| (그) 왜…지(요)/잖아(요) | you know…(filler introducing shared knowledge) | discourse marker | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.1. |
| 글쎄(요) | well; let's see | discourse marker | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.1. |
| 뭐 | well; you know | discourse marker | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.1. |
| 있지(요)/있잖아(요) | well; excuse me (attention-getter) | discourse marker | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.1. |
| 저기(요)/저기 있잖아(요) | well; excuse me | discourse marker | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.1. |
| 어/에/음 | uh… | filler/hesitation sound | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.1. |
| 소문에 의하면 | according to rumor | transition expression | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.2. |
| 아시다시피/주지하는 바와 같이 | as you know/as is generally known | transition expression | core/formal (latter written) | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.2. |
| 어쨌든/좌우간/아무튼/어차피 | at any rate; anyway; no matter what | transition expression | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Near-synonym cluster; book gives distinct example sentences for each. §5.2. |
| 예를 들어(서)/예컨대 | for example | transition expression | core/formal (예컨대 written) | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.2. |
| 솔직히 (말씀드리자면)/(톡) 까 놓고 말해서 | frankly speaking | transition expression | formal / familiar-casual | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Register-contrastive pair for the same function. §5.2. |
| 더욱이/더구나/더군다나/게다가 | furthermore | transition expression | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.2. |
| 그럼에도 불구하고/그래도/그렇다 하더라도 | in spite of that; nevertheless | transition expression | formal / core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.2. |
| 이를테면/말하자면/이른바/소위 | in other words; so-called | transition expression | core / formal (이른바 written) | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.2. |
| 그러므로/고로 | therefore | transition expression | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.2. |
| 그러게 | that's why; so (what did I tell you) | discourse marker | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.2. |
| 아마/어쩌면/혹시/모르면 몰라도 | perhaps; maybe; in all likelihood | transition expression | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §5.2. |

### 4. Interjections (ch. 5.3)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 화이팅 | Go!/Fight! (cheering) | interjection | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Loanword-derived ("fighting"). |
| 건배/원샷/위하여 | cheers; bottoms up | interjection | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 원샷 < English "one shot." |
| 만세 | hurrah | interjection | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 설마/그럴리가 | no way; can't be | interjection | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 아참/아차 | oh dear (forgetting something) | interjection | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 어휴 | oh boy (frustration) | interjection | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 제기랄/젠장 | damn it; oh fuck | interjection | taboo | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Book explicitly glosses 제기랄 as "Oh fuck." |
| 아이고 | oh my (goodness) | interjection | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Also used for "oops." |
| (원) 세상에/(하느님) 맙소사 | Jesus Christ; oh lord | interjection | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 엄마(야) | oops! (startled) | interjection | colloquial/feminine | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Book marks as [feminine]. |
| 아야/아이쿠 | ouch | interjection | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 짠 | ta-dah | interjection | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 망할 놈/년, 미친 놈/년, 못된 놈/년 | what a bastard/bitch | interjection/insult | taboo | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 아휴/휴우 | whew; phew | interjection | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 어쩜 | wow, how (cool/great) | interjection | colloquial/feminine | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Book marks as [feminine]. |
| 아싸 | yeah! (triumph) | interjection | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 흥 | give me a break (scoffing) | interjection | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | |
| 체/치/피 | shhh; give me a break | interjection | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Near-synonymous scoffing sounds. |

### 5. Local dialect forms (ch. 7) — explicit dialectal annotation, high priority per spec

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 뭐여? / 안녕하세유? / 알것슈? | what?/hello?/get it? (Ch'ungch'ŏng forms) | regional variant phrase | regional | — | contemporary (source published 2008) | Ch'ungch'ŏng-do | South Korea | grammar_reference | n/a | n/a | Standard equivalents: 뭐야?/안녕하세요?/알겠어요? §7.1. |
| 그란디 / 그랑께(긍께) / 거시기 | but/so/that-thing (Chŏlla forms) | regional variant word | regional | — | contemporary (source published 2008) | Chŏlla-do | South Korea | grammar_reference | n/a | n/a | Standard: 그런데/그러니까/그것,저기. §7.2. |
| 반갑심니데이/고맙심니데이/욕봤심니데이 | nice to meet you/thanks/you worked hard (Kyŏngsang forms) | regional variant phrase | regional | — | contemporary (source published 2008) | Kyŏngsang-do | South Korea | grammar_reference | n/a | n/a | Kyŏngsang dialect is noted (with Hamgyŏng) as having lexical tone, unlike other Korean varieties. §7.3. |
| 어디 가노?/와 그라노?/뭐라카노? | where are you going?/why?/what is she saying? (Kyŏngsang) | regional variant phrase | regional | — | contemporary (source published 2008) | Kyŏngsang-do | South Korea | grammar_reference | n/a | n/a | Standard: 어디 가냐?/왜 그러니?/뭐라고 하니? §7.3. |
| 하르방/할망 | grandfather/grandmother (Cheju) | noun | regional | — | contemporary (source published 2008) | Cheju-do | South Korea | grammar_reference | n/a | n/a | Standard: 할아버지/할머니. §7.4. |
| 혼저 옵서예 | please come in (welcome) (Cheju) | phrase | regional | — | contemporary (source published 2008) | Cheju-do | South Korea | grammar_reference | n/a | n/a | Standard: 어서 오십시오. §7.4. |
| 아주바이/무시기 | mister/what (Hamgyŏng) | noun | regional | — | contemporary (source published 2008) | Hamgyŏng-do | North Korea | grammar_reference | n/a | n/a | Standard: 아저씨/무엇. Kyŏngsang and Hamgyŏng noted as the two tonal dialects. §7.5. |
| 덩거당 | (train) station (P'yŏng'an) | noun | regional | — | contemporary (source published 2008) | P'yŏng'an-do | North Korea | grammar_reference | n/a | n/a | Standard: 정거장. §7.6. |

### 6. Written-vs-spoken vocabulary/spelling contrasts (ch. 8)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 신장/체중 | height/weight (formal) vs. 키/몸무게 (spoken) | noun | formal vs. colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §8.2. |
| 신속한 | speedy (formal) vs. 빨리 (spoken) | adjective/adverb | formal vs. colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §8.2. |
| 검거되다 | to be arrested (formal) vs. 잡히다 (spoken) | verb | formal vs. colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §8.2. |
| 무척/대단히 | very (formal register) vs. 무지/되게/엄청 (colloquial) | adverb | formal vs. colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §8.2 — a clean register-intensity cluster, high value for slang-mechanics comparison. |
| 그거/이거/저거 [contracted: 거/이걸/걔/쟤] | that/this thing/that child, contracted spoken forms | pronoun (contracted) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §8.3.1 gives a large table of formal-vs-contracted spoken pairs (그 아이→걔, 저 아이→쟤, 무엇→뭐, 나의→내, 이야기→얘기, etc.); representative sample only, full table on pp. 80–81. |
| 숙맥 | foolish person | noun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | From §8.3.2's end-of-section glossary. |
| 뵈어요/뵈요/뵈워요 | (spelling uncertainty around) to see (humble) | verb form | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Book notes even native speakers are unsure of the correct spelling; 뵈어요 is official. §8.3.2. |

### 7. Native Korean vs. Sino-Korean vs. loan-word contrasts (ch. 9) — core register mechanism

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 엄마/아버지 | mom/dad (native, colloquial) vs. 모친/부친 (Sino-Korean, formal/impersonal) | noun | colloquial vs. formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §9.1 core example of the native-vs-Sino-Korean register split. |
| 맨날/더운물/찬물/키/몸무게/이(빨) | everyday/hot water/cold water/height/weight/tooth(colloquial: native) | noun | core/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Paired against Sino-Korean 매일/온수/냉수/신장/체중/치아 respectively; 이빨 marked familiar/casual, 인간 (person, Sino-Korean) can be derogatory. §9.1. |
| 사망하다/승천하다/작고하다/타계하다/별세하다 | to die (formal/Sino-Korean register cluster) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Contrasts with native 죽다 (neutral) and honorific 돌아가시다; none of the Sino-Korean forms would be used in casual personal talk about a stranger either — they're for impersonal formal registers specifically (news, writing). §9.1. |
| 목숨을 잃다/숨지다 | to die (native, euphemistic) | verb | core/euphemistic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §9.1. |
| 양도하다/기부하다/수여하다/하사하다/증정하다 | to give/donate/award/bestow/present (Sino-Korean formal register cluster) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | All contrast with native 주다/드리다; each is contextually specialized (land-title transfer, charity, awards ceremony, presidential gift, corporate promotion respectively). §9.1. |
| 고유어 | native Korean vocabulary | noun | technical.linguistics | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | ~35% of the lexicon per the book's own estimate. §9 intro. |
| 한자어 | Sino-Korean vocabulary | noun | technical.linguistics | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | ~60% of the lexicon; mostly borrowed pre-1945 and now perceived as fully "Korean." §9 intro. |
| 외래어 | (western) loan word | noun | technical.linguistics | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Pre-1945 western loans entered indirectly via Japanese; post-1945 direct borrowing, especially English, concentrated in advertising/entertainment/sports/business/engineering. §9 intro. |
| 춤/무용/댄스 | dance (native/Sino-Korean/loanword three-way cluster) | noun | core/formal/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §9.2 — loan words trend toward a "more modern version of the concept" than the native or Sino-Korean equivalent. |
| 가게/상점/마트 | store (native/Sino-Korean/loanword cluster) | noun | core/formal/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §9.2. |
| 빵 | bread | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Borrowed from Portuguese but fully nativized, unlike modern English loans — book's own example of the native/loan boundary being historically porous. §9.2. |
| 파킹/컨셉 | "parking"/"concept" (raw English loanwords, casual-only) | noun | slang/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Explicitly flagged as common among younger speakers casually but to be avoided in formal writing/speech — a direct register-tier marker for loanword slang. §9.2. |
| 린스/스킨/팝송/빌라/콘도/커닝/서비스/미팅/부킹/스킨십 | conditioner/toner/western pop song/townhouse/timeshare/exam-cheating/free-of-charge/blind date/club pairing-off/romantic touch | noun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | "Innovated" loanwords whose Korean meaning has drifted from the English source (false friends); full list in §9.2.1, pp. 90–91. |
| 백미러/핸드폰/에스라인/커트라인/골인/오픈게임/애프터 서비스/모닝콜 | rearview mirror/cell phone/curvaceous body/exam cutoff score/scoring a goal/preliminary game/after-sales service/wake-up call | noun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Novel English-loanword recombinations not used this way in English (Konglish compounds). §9.2.1. |
| 웰빙하다/오바하다/폼나다/펑크나다 | to live healthily/to overreact/to look stylish/(an appointment) to fall through | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Loan-noun + -하다/-나다 verbalization. §9.2.3. |
| 쿨하다/스마트하다/섹시하다/유머러스하다 | to be cool/smart/sexy/humorous | descriptive verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | English adjectives borrowed as nouns, verbalized with -하다. §9.2.3. |

### 8. Word-formation affixes (ch. 10) — the core generative machinery slang derivation will exploit

**Prefixes (§10.3)** — each entry is `prefix (hanja, gloss) — example1; example2`:

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가- (假) | temporary; fake | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 가건물 'temporary building'; 가석방 'parole.' |
| 급- (急) | sudden; urgent | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 급상승 'sudden rise'; 급회전 'sudden turn.' |
| 대- (大) | great; big; major (opp. 소 小) | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 대가족 'large family'; 대기업 'conglomerate.' |
| 대- (對) | with respect to; vis-à-vis | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Homophonous with the previous entry but a different hanja/meaning — 대미외교 'policy toward the U.S.' |
| 동- (同) | same | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 동시대 'same era'; 동업자 'business partner.' |
| 되- | again; back to source; in reverse | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 되묻다 'ask again'; 되팔다 'resell.' Native Korean, not Sino-Korean. |
| 무- (無) | not exist; have no… (opp. 유 有) | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 무면허 'unlicensed'; 무차별 'indiscrimination.' |
| 반- (反) | anti-; counter- | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 반사회적 'anti-social.' |
| 반- (半) | half; semi- | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Homophonous with previous; 반세기 'half a century.' |
| 부- (副) | vice-; deputy-; subsidiary | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 부사장 'vice-president.' |
| 부-/불- (不) | un-; not | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 부 before ㄷ/ㅈ, 불 elsewhere (exception: 부실). 부자연 'unnaturalness'; 불공정 'unfairness.' |
| 비- (非) | un-; not | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 비현실적 'unrealistic.' |
| 빗- | slanted | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Native Korean; 빗나가다 'go wide of the mark.' |
| 순- (純) | pure; net | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 순이익 'net profit.' |
| 악- (惡) | bad | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 악순환 'vicious cycle.' |
| 역- (逆) | reverse; counter | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 역효과 'contrary/adverse effect.' |
| 유- (有) | possessing (opp. 무 無) | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 유죄 'guilty'; 유명세 'price of fame.' |
| 재- (再) | re-; again | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 재개발 'redevelopment.' |
| 저- (低) | low (opp. 고 高) | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 저소득 'low income.' |
| 정- (正) | regular; full | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 정회원 'regular member.' |
| 짓- | randomly; roughly | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Native; 짓밟다 'trample.' |
| 처- | recklessly; at random | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Native; 처먹다 'eat greedily' — clearly slang-adjacent, contrasts starkly in register with plain 먹다. |
| 총- (總) | overall; total | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 총공격 'full-scale attack.' |
| 최- (最) | most; -est | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 최강 'strongest.' |
| 치- | upward | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Native; 치솟다 'rise suddenly and swiftly.' |
| 현- (現) | present; current | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 현정부 'current government.' |
| 휘- | round and round; recklessly | prefix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Native; 휘두르다 'brandish.' |

**Descriptive-verb-forming suffixes (§10.4.2):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| -답 | be like; be worthy of | suffix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 사람답다 'be humane'; 학자답다 'be scholarly.' |
| -맞 | give the impression of | suffix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 능글맞다 'be sly/sneaky'; 방정맞다 'be rash' — a productive, negatively-connoted register cluster. |
| -스럽 | be suggestive of | suffix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Highly productive: 자연스럽다, 만족스럽다, 퉁명스럽다. |
| -적 (的) | -ic; -al; -ive | suffix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Attaches to Sino-Korean roots that cannot combine with -하다; e.g. 엽기적 'bizarre/grotesque' — itself a slang-adjacent register item. |
| -롭 | be characterized by | suffix | technical.morphology | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 슬기롭다 'be wise'; 신비롭다 'be mysterious.' |

**Suffixes relating to people, often slang-forming (§10.4.5) — high priority for slang mechanics:**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| -내기 | person characterized/seen as | suffix | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 풋내기 'novice'; 여간내기 (=보통내기) used only in negated sentences: 보통내기가 아니다 'he's no ordinary person.' |
| -돌이 | males characterized/seen as | suffix | colloquial/slang | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | [spoken/colloquial] per source. 떡돌이, 곰돌이, 짠돌이 'stingy boy.' |
| -순이 | females characterized/seen as | suffix | colloquial/slang | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | [spoken/colloquial]. 똑순이 'smart girl'; 짠순이 'stingy girl' — gendered parallel to -돌이. |
| -족 (族) | tribe; group (of people who…) | suffix | colloquial/slang | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 올빼미족 'night owls'; 캥거루족 'grown children still living with parents' — a highly productive contemporary slang-forming suffix, directly relevant to slang mechanics. |
| -치 (痴) | imbecile | suffix | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 음치 'tone-deaf person'; 길치/방향치 'person with no sense of direction.' |
| -파 (派) | faction; clique | suffix | core/colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 기분파 'people who are very generous when in a good mood.' |

**Suffixes with an inherently negative/pejorative sense (§10.4.10) — directly slang-relevant:**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| -투성이 | covered/smeared with | suffix | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 오자투성이 'full of typos.' |
| -딱지 | (pejorative nominalizer) | suffix | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 소갈딱지(=소갈머리) always followed by 없다 'be stupid/thoughtless' or 좁다 'be narrow-minded' — a fixed-collocation slang idiom, not freely combinable. |
| -머리 | (pejorative nominalizer, esp. body/personality) | suffix | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 성질머리 'terrible temper'; 인정머리 'heart/compassion' (used negatively: 인정머리하곤… 'how heartless'). |
| -대가리 | (familiar/casual variant of 머리 'head', pejorative) | suffix | slang | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Always followed by 없다: 맛대가리 없다 'be damn tasteless'; 재미대가리 없다 'be bloody boring.' Explicitly the most casual/vulgar tier of this whole cluster. |

**Selected recently-created colloquial/slang expressions (§10.6) — the book's own explicit
youth-slang section, maximal priority:**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 공주병/왕자병 | "princess disease"/"prince disease" (self-obsessed vanity) | noun | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | -병 (disease) used metaphorically/productively as a slang-forming suffix for personality quirks. |
| 중딩/고딩/초딩/대딩 | middle/high/elementary/college student (clipped, casual) | noun | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | Clipped from 중학생 etc. by dropping -학생 → -딩; explicitly noted as popular among young people. |
| 직딩 | office worker (casual) | noun | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | Same -딩 pattern extended to 직장인. |
| 얼짱/몸짱/맘짱 | best face/best body/best character-"champ" | noun | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | -짱 is explicitly noted by the book as a productive suffix: 요리짱 'cooking champ,' 공부짱 'study champ.' |
| 짱 | awesome; the best | adjective/intensifier | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | 기분 짱이다 'I'm feeling awesome.' |
| 때리다 (slang sense) | to do/send (casually), e.g. 문자 때리다 'text someone' | verb | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | Literal sense 'to hit' extended metaphorically; 영화하나 때릴까? 'wanna hit a movie?' |
| 당근이지 | of course (slang) | phrase | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | 당근 'carrot' punningly repurposed for 당연 'of course.' |
| 썰렁하다 (slang sense) | to be cheesy/fall flat (of a joke) | descriptive verb | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | Literal sense 'to be chilly.' |
| 뚜껑 열리다 | to blow one's top (anger) | idiom/verb phrase | slang/familiar-casual | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | [familiar/casual] per source. |
| 씹히다 (slang sense) | to get (a message) ignored | verb | slang/familiar-casual | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | Literal 'to get chewed'; [familiar/casual] per source. |
| 쪽 주다/쪽 먹다/쪽 팔리다 | to embarrass/get embarrassed/be humiliated | idiom/verb phrase | slang/familiar-casual | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | [familiar/casual] per source; 노땅 'old geezer' in the same example is itself slang. |
| 안습이다 | how sad (internet slang, sarcastic) | phrase | slang | — | contemporary (source published 2008), internet register | — | — | grammar_reference | n/a | n/a | Clipped from 안구에 습기가 차다 'the pupil gets moist' — book's own worked example of internet-abbreviation word formation. |
| 갑툭튀 | popped out of the blue | phrase | slang | — | contemporary (source published 2008), internet register | — | — | grammar_reference | n/a | n/a | Clipped from 갑자기 툭 튀어나온… — acronym-like clipping of a full phrase into a 3-syllable unit, a distinct word-formation mechanism from the affixation above. |

**Selected general abbreviations (§10.5):**

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 알바 | part-time job | noun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | < 아르바이트 < German "Arbeit" — a double-clipped loanword. |
| 남친/여친 | boyfriend/girlfriend (clipped) | noun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | < 남자친구/여자친구. |
| 열공 | studying hard (clipped) | noun/verb-stem | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | < 열심히 공부하다 — retains first syllable of each word in the phrase, the same mechanism as 갑툭튀 above. |
| 리모컨/에어컨/디카/몰카/컴맹 | remote control/air conditioner/digital camera/hidden camera/computer illiterate | noun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Loanword-compound clippings. |

### 9. Vocabulary contrasts — verbs of wearing/taking off/playing/cleaning (ch. 11)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 입다 | to wear (torso clothing) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.1.1. |
| 신다 | to wear (footwear) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.1.1. |
| 쓰다 | to wear (on/over the head) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 안경, 모자, 가발, 가면, 우산 (an umbrella held over the head). §11.1.1. |
| 차다 | to wear (around wrist/ankle/waist) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 시계, 팔찌, 수갑, 기저귀. §11.1.1. |
| 걸치다 | to wear (draped over shoulders) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 숄, 카디건, 코트. §11.1.1. |
| 매다 | to wear (tied/buckled) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 넥타이, 벨트, 스카프. §11.1.2. |
| 끼다 | to wear (slipped on/squeezed into) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 반지, 장갑, 안경, 콘택트 렌즈. §11.1.2. |
| 걸다 | to wear (hung on) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 목걸이. §11.1.2. |
| 달다 / 부착하다 | to attach (wear); [formal variant] | verb | core / formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 이름표, 배지, 리본; 부착하다 is the written/formal register counterpart. §11.1.2. |
| 착용하다 | to wear (formal, esp. official/regulation attire) | verb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Formal-register umbrella verb replacing 입다/쓰다/달다 for uniforms, badges in official contexts. §11.1.2. |
| 벗다 | to take off (peeled/lifted off) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.2. |
| 빼다 | to take off (taken out, e.g. rings) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.2. |
| 풀다 | to take off (untied) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.2. |
| 떼다 | to take off (detached) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.2. |
| 놀다 | to play (recreationally, no purposeful activity) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Intransitive; explicitly NOT used for sports/games (exception: 윷놀다 'play yut sticks'). §11.3 — a key false-friend warning for English "play." |
| 치다 | to play (hitting: instruments/ball/cards) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 드럼, 기타, 피아노, 테니스, 골프, 화투. §11.3. |
| 켜다 | to play (plucking/bowing strings) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 바이올린, 첼로, 가야금. §11.3. |
| 불다 | to play (blowing wind instruments) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 플룻, 트럼펫, 나팔. §11.3. |
| 두다 | to play (placing pieces, board games) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | 바둑, 장기. §11.3. |
| 씻다/닦다 | to wash/clean (surface, with water/wiping) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.4. |
| 훔치다 | to clean (wiping/mopping horizontal surfaces) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.4. |
| 감다 | to wash (hair) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.4. |
| 세수하다/세차하다 | to wash one's face/to wash a car | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.4 — explicitly flags 얼굴을 청소하다 as a common learner error for "clean my face." |
| 청소하다/치우다 | to clean (sweeping/vacuuming/tidying) | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.4. |
| 빨다/세탁하다 | to wash (fabric, by hand/machine); [세탁하다 = professional/dry cleaning] | verb | core / formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.4. |
| 설거지하다 | to do the dishes | verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.4. |
| 세척하다 | to cleanse (with detergent/medically) | verb | formal/technical | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §11.4. |

### 10. Representative proverbs (ch. 12.1)

*The source lists roughly 60+ proverbs across three subsections (identical English
equivalents, approximate equivalents, Korea-specific). A representative sample of the
Korea-specific proverbs (§12.1.3), the ones with no direct English analog and therefore
highest value for understanding Korean-specific figurative/cultural mechanics, is given
below; §12.1.1–12.1.2 (proverbs with exact or approximate English equivalents) are
paraphrased rather than tabulated since their content overlaps heavily with universal
proverb concepts already covered by "gloss = English equivalent."*

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 개구리가 올챙이 적 생각 못한다 | an upstart forgets his origins [the frog forgets being a tadpole] | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 128. |
| 개천에서 용난다 | a pauper becomes a king [a dragon may come from a creek] | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 128. |
| 낫 놓고 기역자도 모른다 | (s)he is completely illiterate [looking at a scythe, doesn't recognize the letter ㄱ that it resembles] | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 128 — a proverb whose logic depends on Hangul letter-shape iconicity, a distinctly Korean-script-specific mechanism. |
| 믿는 도끼에 발등 찍힌다 | one gets stabbed in the back by someone one trusts | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 129. |
| 사촌이 땅을 사면 배 아프다 | one is jealous of one's cousin's success [stomach hurts when a cousin buys land] | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 129. |
| 원수는 외나무 다리에서 만난다 | enemies meet on a single-lane bridge (a cruel coincidence) | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 129. |
| 작은 고추가 맵다 | small people are tough and smart [small peppers are hot] | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 129. |
| 벼는 익을수록 고개를 숙이는 법이다 | truly great people are modest [the rice stalk droops as it ripens] | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 133 — quoted with the productive proverb-usage pattern -는 법이다. |
| 짚신도 제 짝이 있게 마련이다 | even straw shoes come in twos (everyone has their match) | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 134 — quoted with the productive pattern -게/기 마련이다. |
| 옷이 날개다 | clothes make the difference [clothes are wings] | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 134. |
| 제 눈에 안경 | beauty is in the eye of the beholder [it's a matter of one's own glasses] | proverb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 135. |

**Productive proverb-quoting grammar patterns (§12.1.4)** — how proverbs attach
grammatically to a surrounding sentence, a genuinely reusable mechanism worth capturing
as grammar rather than lexicon: `-다는데/-(이)라는데` ('they say that…, so…'),
`-다더니/-(이)라더니` ('didn't they say…? [and now this happened]'), `-다잖아/-(이)라잖아`
('you know they say…'), `-다고/-(이)라고` (quoting the proverb as the reason for
something), `…는 격이다` ('it's as if…'), `-는 법이다` ('it's always the case that…'),
`-게/기 마련이다` ('it's bound to be that…'), and `-게 생기다` ('it looks like…').
Each pattern lets a speaker invoke a proverb as grounds for a claim without fully quoting
or explaining it — directly relevant to how proverbial material could be repurposed as
in-universe slang shorthand.

### 11. Representative idioms (ch. 12.2)

*Idioms run to well over 100 entries across five subsections (four-syllable Sino-Korean
idioms, body-part idioms, animal idioms, other-figure idioms, figurative verb uses). A
representative sample follows; full inventory pp. 136–149.*

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 구사일생 | a narrow escape from death | idiom (4-syllable Sino-Korean) | formal/literary | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.1. |
| 금상첨화 | an added bonus [a flower on top of gold] | idiom (4-syllable Sino-Korean) | formal/literary | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.1. |
| 독불장군 | a loner who wants everything his own way | idiom (4-syllable Sino-Korean) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.1. |
| 동문서답 | a completely irrelevant answer [answering "west" when asked about "east"] | idiom (4-syllable Sino-Korean) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.1. |
| 오리무중 | utterly befuddled/in a fog | idiom (4-syllable Sino-Korean) | formal/literary | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.1. |
| 용두사미 | to fizzle out [dragon head becomes snake tail] | idiom (4-syllable Sino-Korean) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.1. |
| 일석이조 | killing two birds with one stone | idiom (4-syllable Sino-Korean) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.1. |
| 간이 콩알만해지다 | to be terrified [one's liver shrinks to the size of a bean] | idiom (body part: 간 'liver') | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.2 — Korean idiom uses 간 (liver) where English uses "heart" for the seat of courage/fear. |
| 간이 붓다 | to be reckless/crazy [one's liver swells] | idiom (body part: 간) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.2. |
| 귀가 가렵다 | one's ears are burning (someone is talking about you) | idiom (body part: 귀 'ear') | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.2. |
| 귀에 못이 박히다 | to have heard something so many times it's calloused into your ears | idiom (body part: 귀) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.2. |
| 눈에 밟히다 | to be unable to stop thinking about (someone/something left behind) | idiom (body part: 눈 'eye') | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.2. |
| 눈이 맞다 | to hit it off romantically [eyes meet] | idiom (body part: 눈) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.2. |
| 눈코 뜰 새 없다 | to be extremely busy [no time to open eyes or nose] | idiom (body part: 눈/코) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.2. |
| 뒤통수를 치다 | to stab someone in the back [hit the back of the head] | idiom (body part: 머리 'head') | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.2. |
| 손이 크다 | to be generous (with resources, esp. food) [hands are big] | idiom (body part: 손 'hand') | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.2. |
| 배 째다 (내 배 째쇼야) | I don't give a damn; "so-shoot-me" attitude [cut my belly open] | idiom (body part: 배 'belly') | slang/familiar-casual | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | [familiar/casual] per source; strongly slang-register, directly reusable. §12.2.2. |
| 황소고집 | stubborn as a mule [an ox's stubbornness] | idiom (animal: 소 'ox') | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.4. |
| 새 발의 피 (=조족지혈) | a drop in the bucket [blood on a bird's foot] | idiom (animal: 새 'bird') | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.4. |
| 꽃뱀(족) | gold-digger (woman) [flower snake] | idiom/slang noun (animal: 뱀 'snake') | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | Explicitly cross-referenced with -족 word formation above; directly slang. §12.2.4. |
| 물 건너 가다 | to totally fall through (of a plan) [water crosses] | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.5. |
| 바가지 쓰다/바가지 요금 | to get ripped off / inflated/rip-off pricing [wear a gourd-bowl] | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.5 — very commonly used, e.g. of tourist-trap pricing. |
| 바람 맞다 | to get stood up | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.5. |
| 바람을 피우다 | to have an affair [to fan wind] | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.5. |
| 왕싸가지 | a real bitch/jerk (rude person) | idiom/slang noun | slang/taboo | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | 왕- intensifying prefix + 싸가지 'manners'; explicitly rendered "bitch" in the book's own English gloss. §12.2.5. |
| 대박 | a huge hit/jackpot | slang noun/interjection | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | §12.2.5. |
| 한물가다 | to be all washed up (past one's prime) | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.5. |
| 형광등이다 | to be slow on the uptake [to be a fluorescent light] | idiom/slang | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | §12.2.5 — modern-technology-based idiom (fluorescent lights flicker/take time to turn on), a good example of a recently-coined figurative mechanism. |
| 에스라인이다 | to have an hourglass figure [to be S-line] | idiom/slang | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | Built directly on the loanword 에스라인 documented in §9.2.1 above — cross-reference showing loanword vocabulary feeding idiom formation. §12.2.6. |
| 딱지 떼다 | to get a (traffic) ticket | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §12.2.6. |
| 씹다 (뒤에서 씹다) | to talk trash about someone behind their back [to chew] | verb (figurative) | slang | — | contemporary (source published 2008), youth register | — | — | grammar_reference | n/a | n/a | §12.2.6 — same metaphor root (chewing) productively reused in §10.6's 씹히다 'to get ignored,' showing a recurring "chew/consume" slang metaphor family. |

### 12. Sound symbolism (ch. 13.1–13.3) — representative sample

*The book documents dozens of onomatopoeic (의성어) and mimetic (의태어) forms; a full
listing would reproduce most of two entire chapter sections verbatim. The system-level
mechanism (bright vs. dark vowel symbolism; plain vs. tense/aspirated consonant symbolism)
is the highest-value, most reusable content and is captured as a grammar point below.
Representative lexical items follow.*

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 보글보글 | bubbling (of a stew) | ideophone/adverb (의성어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.1. |
| 깜박이다/깜박이 | to blink; (car) turn-signal light | ideophone-derived verb/noun (의태어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.1. |
| 벌떡 | (getting up) with a swift, sudden motion | ideophone/adverb (의태어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Book notes it can only be followed by 일어나다-type verbs — sound-symbolic adverbs constrain/predict the following verb. §13.1. |
| 텅 | (being) utterly empty | ideophone/adverb (의태어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Predicts 비다 'be empty.' §13.1. |
| 쑥쑥 | growing by leaps and bounds | ideophone/adverb (의태어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Predicts 자라다/크다/올라가다. §13.1. |
| 뚝 | (something) suddenly stopping/dropping | ideophone/adverb (의태어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Frequently used verb-less, e.g. as a full command to a crying baby (뚝! 'stop!') or in headlines (전국기온 뚝 'nation's temp. drops'). §13.1. |
| 새콤하다 (bright) vs. 시큼하다 (dark) | tangy-and-pleasant vs. tangy-and-unpleasant (sourness) | descriptive verb (의정/의태어 pair) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Minimal bright/dark vowel pair illustrating the positive/negative connotation split. §13.1. |
| 반짝반짝 (bright) vs. 번쩍번쩍 (dark) | twinkling (gently) vs. flashing (harshly, e.g. lightning) | ideophone/adverb pair | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.1. |
| 촉촉하다 (bright) vs. 축축하다 (dark) | pleasantly moist vs. unpleasantly damp | descriptive verb pair | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.1. |
| 멍멍 | woof-woof (dog bark) | onomatopoeia (의성어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | Book explicitly flags cross-linguistic divergence in how animal sounds are perceived (vs. English "bow-wow"). §13.2.1. |
| 방글방글 | smiling brightly/sweetly (esp. a child) | mimetic expression (의태어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13 intro, contrasted with plainer 웃는 얼굴 'smiling face.' |
| 싱글벙글 | beaming; all-smiles | mimetic expression (의태어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13 intro. |
| 갈기갈기 | shredded into pieces | mimetic expression (의태어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.3.1 (appearance). |
| 뒤죽박죽 | topsy-turvy; in complete disarray | mimetic expression (의태어) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.3.1. |
| 들쑥날쑥하다 | to be jagged/uneven (e.g. crooked teeth) | mimetic expression (의태어) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.3.1. |
| 뒤룩뒤룩 | (getting) fatter and fatter | mimetic expression (의태어) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.3.1. |
| 바글바글하다 | to be bustling/crowded (with people) | mimetic expression (의태어) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.3.1. |
| 뻘뻘 (땀이 나다) | sweating profusely | mimetic expression (의태어) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.3.1. |
| 으리으리하다 | to be luxurious/opulent | mimetic expression (의태어) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.3.1. |
| 생글생글 | smiling pleasantly | mimetic expression (의태어) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.3.1. |
| 오동통하다 | to be plump/chubby (cutely, e.g. a child's cheeks) | mimetic expression (의태어) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | §13.3.1. |

---

## Grammar points

### Chapter 1 — Sentence endings (register/speech-level system; the book's central axis)

**1.1 Statements and questions.** Korean marks style through sentence-final verb endings
along two independent axes: 존댓말 (formal: 합니다/합니까-style and 해요-style) vs. 반말
(casual: 해-style and 한다/하니-style). The book is emphatic that 존댓말 is not simply
"polite" and 반말 is not simply "impolite" — either can be rude if mismatched to the
relationship (using 존댓말 with a close friend signals coldness/distance; using 반말 with
a stranger is offensive regardless of the stranger's age, except toward pre-adolescent
children). Choice depends jointly on speaker–hearer relationship *and* setting: even
romantic partners who normally use 반말 must switch to 존댓말 in a formal meeting.
합니다/합니까-style is near-exclusive in news broadcasts, ceremonies, job interviews, and
public announcements; 해요-style is the default for daily adult conversation and sounds
softer. -요 (또는 -이요 after a consonant) can be appended to almost any standalone
word/phrase to convert an otherwise casual utterance into formal register (책이요,
그럼요). 해-style is derived from 해요-style by dropping -요 (with an exception:
책이야/얼마야 rather than *책이에요 minus -요*). 하니-style questions are considered too
blunt toward parents/older siblings/senior friends even under 반말; 해-style questions
are preferred there instead. 한다-style also does double duty as the impersonal-writing
default (see ch. 8) and as an exclamatory form addressed to no one in particular (너무
안됐다 'that's so sad').

**1.2 Commands.** Four parallel formality tiers: -(으)시오 (now largely restricted to
written signs/instructions, e.g. 미시오/당기시오 'push/pull'), -(으)십시오 (high formality
regardless of addressee age/status — service industry, business letters), -(으)세요
(formal-but-personal, the most common polite command form), -어/아요 (used to non-older
adult acquaintances), and 해라 (casual, but avoided toward older siblings/parents even
under 반말 — 해 preferred there instead). Most descriptive verbs cannot be commands at all
(exceptions: 겸손해라 'be modest,' 건강하세요 'be healthy'); when they do take a command
ending they shift to exclamatory meaning (아이고 추워라! 'how cold!').

**1.3 Proposals.** Parallel four-tier system: 합시다(→십시다, elderly-male-only)/해요/
해/하자. 합시다 can sound blunt to someone just met even if same age/formality-tier;
it becomes highly formal instead when addressed to a general/anonymous audience (건강은
건강할 때 지킵시다 'let's protect our health while healthy,' in an ad). Most descriptive
verbs also lack proposal forms (exceptions: 솔직하자, 건강합시다).

**1.5–1.6 Written vs. spoken sentence-final endings.** 한다-style covers casual speech
*and* impersonal writing, but the two diverge for questions/commands: written impersonal
uses -는가/-(은)가 for questions (한글은 언제 만들어졌는가? — also usable to express
musing, like -나) and -(으)라 for commands (다음 물음에 답하라), vs. spoken casual
-니/-냐 and -어라/아라. Headlines/ads/want-ads often end in a bare noun or truncate to
sound like the casual 해-style (올 들어 가장 추워 'coldest this year'). None of the
written impersonal styles ever take the subject honorific -시 (tying directly into ch. 2
and ch. 9's register-vs-honorific interaction). Business letters are always formal; personal
letters can be either, per relationship.

**1.7 Minor/archaic styles.** A now largely-obsolete, "authoritarian-sounding" formal
register (하네/하나/하게/하세) survives among older male speakers of equal status, or
seniors to grown-up juniors (parent-in-law to son-in-law; older professor to student). -네
and -나 have been repurposed in contemporary speech for moderate exclamation/surprise and
wonderment respectively, independent of the archaic style. Several further archaic forms
(-소/-수 variant, -리다, -(으)마, -거라/-너라, -나이다/-느니라/-시옵소서) are placed on an
explicit formality/archaism gradient by the book, down to forms reserved purely for
historical dramas, poems/proverbs, and prayers.

### Chapter 2 — Honorifics

**2.1 Subject honorification (-시/으시).** Marks deference toward the *referent of the
subject*, triggered chiefly by the subject's age/social status, but is genuinely
relational, not absolute: no -시 for one's own mother in casual family talk, but -시
required when talking about her to someone outside the family; none needed for the
president of the country unless within earshot or in a formal setting; both parties use
-시 for each other when age and workplace rank conflict. -시 is never used in news
broadcasts or general-audience writing (this rule recurs across chs. 1, 2, 6, 8, 9 as a
structural register marker, not an isolated fact). §2.1.4 lists a small closed set of
suppletive (not just suffixed) subject-honorific verbs (드시다/잡수시다, 계시다/있으시다,
주무시다, 돌아가시다, 편찮으시다/아프시다) — see the Vocabulary table above. §2.1.5
resolves an important subject-identification trap: 있다/없다 is ambiguous between 'have'
(no honorific triggered by the possessed-noun's particle-marked NP, since the speaker or a
third party is the real subject) and 'stay/exist' (where the marked NP *is* the subject
and does trigger honorification) — 이모가 없어요 'I don't have an aunt' vs. 할머니가 안
계세요 'Grandmother isn't home.' §2.1.6 shows -시 placement in compound-verb constructions
is lexically governed, not fully predictable from position: sometimes both verbs take -시
(하실 수 있으세요?), sometimes only the first (가실 거예요?), sometimes only the second
(들어 오세요), and a verb's suppletive honorific form always wins regardless of position
(드셔 보세요, not *먹어 보세요 with -시 elsewhere).

**2.2 Object honorification.** A small closed set of "humble" verbs lower the speaker to
elevate the referent of the direct/indirect object (뵙다, 여쭙다/여쭤보다, 모시고 가다,
드리다, 말씀드리다, and 하다-compounds like 전화드리다/부탁드리다/축하드리다). These are
listed in the Vocabulary table above. Formal-occasion object honorification is expected
even toward a younger/socially-inferior addressee as a matter of courtesy (안내 말씀
드리겠습니다 in a public announcement; 잘 부탁드립니다 as a fixed self-introduction
closing formula).

**2.3 Honorific nouns.** A small closed set (말씀, 진지, 댁, 병환, 성함/존함, 자제분/자녀)
substitute for their plain counterparts when referring to things associated with an
esteemed person. Age-related honorific nouns (연세, 생신) are explicitly flagged as a
common learner trap: using them toward a not-actually-old teacher/addressee can insult by
implying they're old; indirect, euphemistic age-inquiry forms (몇 년생이세요?, 학번이
어떻게 되세요?) are the culturally safer default.

**2.4 Honorific particles.** -께서 (honorific subject particle, replacing -이/가) and -께
(honorific indirect-object particle, replacing -한테/-에게) are both described as
declining/optional in casual honorific contexts, but -께 remains obligatory in personal
letters to a deferred-to recipient.

**2.6 Non-use of honorifics in impersonal language.** News broadcasts and general-audience
writing use none of: -시, -님, honorific nouns, honorific particles, or object-honorific
verbs — because such language expresses *personal* respect, which has no addressee in
impersonal communication. Certain vocabulary items are swapped for register-neutral
counterparts in this register too (선생/선생님 → 교사/교원 for schoolteachers; 집/댁 →
자택; 데리고/모시고 가다 → 동반하고 가다) — this is the direct forerunner of ch. 9's
native/Sino-Korean register system.

### Chapter 3 — Address terms and pronouns

Address-term choice is governed jointly by the addressee's gender, relationship to the
speaker, and (apparent) relative age — described by the book as consequential enough to
affect careers and relationships if mishandled. Strangers are addressed via hedging
attention-getters (저기요, 저…) rather than a specific term when the appropriate term is
unclear. A large system of family-derived address terms (§3.1.2–3.1.3) is extended
metaphorically to non-family members to signal closeness (형/오빠/언니/누나 for close
older friends; 선배 for school seniors) — precisely the kind of extended-kinship-term
register mechanism a synthetic slang system could plausibly borrow or invert. Korean lacks
a robust true third-person pronoun category (§3.2.3): the default strategies are omission
(when topic continuity makes the referent recoverable), repeating the noun/title, or a
demonstrative-plus-noun periphrasis (이/그/저 + 사람/분/것/애/놈, graded from neutral to
insulting depending on the noun chosen) — 그/그녀 as a true 3rd-person pronoun is a
translation-induced innovation restricted to formal writing and song lyrics under English
influence. Reflexive-pronoun strategies (§3.2.4: 저/지, 자기, 자신, 자체, 당신) and
indefinite/interrogative-pronoun overlap (§3.2.5: 누구/누가, 뭐, 어디, 어떻게, 어느, 어떤,
몇 all double as "who/something/somewhere/somehow/some" depending on the attached
particle, e.g. -(이)나, -도, -든(지), -라도) round out the pronoun system.

### Chapter 4 — Language for daily situations

A catalogue of fixed formulaic expressions across greetings, leave-taking, giving
thanks, apologizing, "excuse me," condolences/encouragement, invitations, telephone
etiquette, and congratulations — each graded across formality tiers with worked
dialogue examples. Two register-contrast pairs are worth flagging as genuinely
grammar-like rules rather than mere vocabulary: (1) 죄송(/미안)합니다 vs. 실례합니다 as
two different pragmatic uses of "excuse me" — 죄송합니다 prefaces a favor-request (not a
true apology), while 실례합니다 is restricted to asking a personal question, entering
someone's space, or addressing a stranger, and can be swapped for 죄송합니다 only in its
favor-asking use; and (2) 미안합니다 vs. 죄송합니다 as an age/familiarity-graded pair
(미안합니다 to someone younger but not well known). The book flags 쏘리 (< English
"sorry") as the lightest possible apology register, restricted to 반말 relationships —
a loanword functioning as a register marker in its own right. It similarly flags
천만에요 (a literal calque of English "you're welcome") as artificial/rare in actual
Korea-based usage, used mainly by Koreans living abroad — an important false-friend
warning against assuming English-Korean politeness formulas map 1:1.

### Chapter 5 — Conversational bridges

Fillers (§5.1) let a speaker hold the floor while hesitating or signal upcoming
information without a full grammatical frame; see the Vocabulary table above for the
closed set. Transition expressions (§5.2) are graded by formality (많은 pairs are given
as formal-written vs. colloquial-spoken alternatives for the same logical relation, e.g.
그러므로/고로 [written] vs. 그래서 [spoken] for "therefore"). Interjections (§5.3) are
the most casual-register-bound category in the whole book, several explicitly marked
[feminine] or as strong profanity — this is some of the highest-value slang-adjacent
material in the entire extraction (see Vocabulary table above).

### Chapter 6 — Softening strategies

A cross-cutting pragmatic principle: directness is systematically avoided, especially in
commands/requests/questions, through several independent mechanisms. (1) **Questions
replace commands/proposals** (§6.1): 소금 좀 줘 → 소금 좀 줄래?/주시겠어요?, graded
softer as the question becomes more indirect (같이 갑시다 → 같이 가실까요? → 같이
가시겠어요?, most→least direct). The book warns explicitly that English "Would/Could
you…?" politeness patterns do NOT map onto Korean honorific question forms — the latter
remain inappropriate toward children/close friends regardless of how indirect the English
translation sounds. (2) **Special softening verbs** (§6.2): 주다 turns a command into a
favor-request (조용히 하십시오 → 좀 조용히 해 주시겠습니까?); 보다 turns an assertion
into a hedge/suggestion (저는 가겠습니다 → 저는 가 보겠습니다; 이제 그만 가 → 이제 그만
가 봐 turns a command into "why don't you..."); -게 되다 frames an event as outside the
speaker's control, reducing responsibility for both bad outcomes (약속을 어기게 됐어요)
and good ones the speaker doesn't want to seem to brag about (승진하게 됐습니다); 하다
substitutes for a more direct verb (뭐 드시겠어요? preferred over 뭐 먹고 싶으세요?); 그렇다
serves as a vague hedge avoiding an unpleasant specific (그 옷은 좀 그렇다 'those clothes
are... not quite'). (3) **Special softening endings** (§6.3): -데(요) (from 그런데) keeps
a statement open-ended/non-abrupt; -지(요)/죠 makes gentler questions/suggestions than
-요; -구(요) softens multi-part questions/commands; -나요/-(으)ㄴ가요 forms low-pressure
questions not strongly demanding an answer. (4) **Other lexical softeners** (§6.4):
어떻게-questions are gentler than 왜-questions (어떻게 오셨습니까? preferred to 왜
오셨습니까?); 좀 functions as an all-purpose imploring "please;" -고 해서 hedges by
avoiding pinpointing one single reason; -는/은 편이다 tones down a negative
characterization ("kind of…" rather than a flat assertion); -거 같다/-을까 하다/싶다
soften assertions of belief/intention.

### Chapter 7 — Local dialects (explicit regional annotation)

The book explicitly frames Standard Korean (표준말, educated Seoul speech) as its baseline
and treats non-standard dialects (사투리) as encounter-worthy but non-baseline. Six
dialects are each given worked example phrases against their Standard Korean equivalent:
Ch'ungch'ŏng, Chŏlla, Kyŏngsang, Cheju, Hamgyŏng, and P'yŏng'an. Kyŏngsang and Hamgyŏng are
explicitly noted as the two Korean dialects that retain lexical tone, unlike all other
varieties including Standard Korean — a genuinely notable typological fact, not just a
vocabulary difference. See the Vocabulary table above (§5) for the example forms
themselves, each tagged with Attested Region per the spec's regional-annotation
requirement.

### Chapter 8 — Written versus spoken language

A systematic three-way contrast (grammatical / vocabulary / spelling-pronunciation)
between written-or-formal and colloquial-spoken registers, treated as pervasive rather
than a handful of isolated facts: (1) different sentence-final endings (ch. 1, ch. 8.1.1);
(2) different case/adverbial particles, with particles more likely retained rather than
dropped in careful/formal registers (§8.1.2 — e.g. formal 회사가 파산했다고 한다 vs.
colloquial 회사 파산했댄다, with the subject particle -가 dropped in speech); (3) complete
absence of honorific marking in impersonal writing (§8.1.3, tying back to ch. 2.6); (4)
different pronoun choices (그는 누구인가? [written] vs. 그 사람은 누구입니까? [spoken]);
(5) different quoting-verb morphology in reported speech (위험하다고 한다 [written] vs.
위험하다 그런다/위험하댄다 [spoken] — previewing ch. 22's quotation grammar); (6)
systematically more Sino-Korean/technical vocabulary in writing (§8.2, direct predecessor
of ch. 9's whole register system); (7) a large, systematic set of spoken-only contractions
graded by "tolerability in writing" from mild (그러면→그럼) to essentially ungrammatical-
in-writing (그러니깐→그깐, 저희들→지들) (§8.3.1); and (8) systematic gaps between official
spelling and actual pronunciation (§8.3.2: 고/구 alternation, 어/으 alternation, tensification
of plain consonants in casual speech — 버스→뻐쓰, 잼→쨈 — and re-adapted loanword
pronunciations, e.g. 스웨터→세타, 팬티→빤쓰). This entire chapter is effectively a
register-contrast grammar in miniature and should be treated as core material for any
later slang-mechanics analysis of register-shifting as a productive process in Korean.

### Chapter 9 — Native and borrowed words

Korean vocabulary is roughly 35% native (고유어), 60% Sino-Korean (한자어, mostly
pre-1945 and now perceived as fully native), and a growing western-loanword layer
(외래어, historically filtered through Japanese before 1945, now borrowed directly and
concentrated in advertising/entertainment/sports/business/engineering). **The core
register mechanism**: when a native and a Sino-Korean word share a meaning, the native
word trends colloquial/personal and the Sino-Korean word trends formal/literary/technical
(엄마/아버지 vs. 모친/부친); the majority of written-material and news-broadcast/lecture/
ceremony vocabulary is Sino-Korean by default, independent of any specific word pair.
Occasionally the Sino-Korean word narrows to a specialized sense rather than simply
sounding more formal (손위/손아래 'someone older/younger' generically vs. 연상/연하
specifically for an older/younger romantic partner). Loan words layer a *third* register
tier on top of this native/Sino-Korean opposition, generally connoting a "more modern
version of the concept" (§9.2) — together this produces up to three-way lexical clusters
for a single concept (native/Sino-Korean/loanword), the single richest register-generating
mechanism identified in this book, and probably the most useful transferable mechanism for
constructing an invented slang system with realistic register stratification. §9.2.1–9.2.3
document loanword-specific phonological adaptation rules (f→ㅍ, j/z/s→ㅈ, l/r→ㄹ, sh/th→ㅅ,
v→ㅂ, consonant clusters broken up with 으, word-final s/z/ch get an epenthetic vowel,
p/t/k/g neutralize to unreleased ㅂ/ㅅ/ㄱ at the coda) and grammatical integration (loan
nouns verbalized with -하다/-나다; loan adjectives nominalized then verbalized with -하다).

### Chapter 10 — Word formation

The chapter catalogs Korean's synchronically-productive word-formation machinery in full:
**compounding** (§10.1: Sino-Korean root+root compounds, native+native compounds, and
hybrid loanword+Korean compounds; noun+verb compound verbs built on a small set of "pivot"
verbs like 하다/가다; verb+verb serial compounds linked by -어/아, -어다/아다, or -고, with
certain verbs — 갈-, 내-, 알- initially, 가다, 들다, 보다 finally — recurring as
productive "pivot" elements); **reduplication** (§10.2, marking emphasis/repetition/
alternation/plurality — cross-referenced to ch. 13's sound symbolism as a related but
distinct mechanism); **prefixation** (§10.3, mostly Sino-Korean-root prefixes carrying a
fixed semantic contribution, cataloged exhaustively above); **suffixation** (§10.4, by far
the most extensive subsection — noun-forming, descriptive-verb-forming, adverb-forming,
address-term suffixes, and semantically-organized suffix families for people, places,
classification, money, language/writing, negative-perception/pejorative meaning, and
quantity/approximation, cataloged in the Vocabulary table above); **abbreviation** (§10.5,
by final-truncation, initial-truncation, or first-syllable-retention across a whole
phrase); and **recently created expressions** (§10.6, the book's own explicit youth-slang
showcase, cataloged in full in the Vocabulary table above). This entire chapter is the
single most directly transferable content in the whole extraction for later slang-mechanics
analysis: it is, in effect, the standard language's own inventory of the productive
processes (compounding, reduplication, affixation, clipping) that Korean slang formation
routinely repurposes or extends (as ch. 10.6 itself demonstrates with -병, -짱, -딩, -족).

### Chapter 11 — Some vocabulary contrasts

Korean draws finer distinctions than English in several everyday semantic fields, chosen
by the book because they routinely trip up English-speaking learners: verbs of *wearing*
(chosen by body part covered: 입다/신다/쓰다/차다/걸치다; or by manner of attachment:
매다/끼다/걸다/달다/뿌리다/두르다/꽂다/하다, with 착용하다 as the formal-register umbrella
term), verbs of *taking off* (벗다/빼다/풀다/떼다, again by manner), verbs of *playing*
(치다/켜다/불다/두다/하다/놀다 depending on activity type — critically, 놀다 itself is
restricted to purposeless recreation and cannot describe sports/games participation, unlike
English "play"), and verbs of *cleaning* (씻다/닦다/훔치다/감다/세수하다/세차하다/청소하다/
치우다/빨다/세탁하다/설거지하다/세척하다, split by surface type, cleaning method, and
formality). Full contrast sets are given in the Vocabulary table above.

### Chapter 12 — Proverbs and idioms

Proverbs (12.1) are grouped by whether they have identical, approximate, or no English
equivalent, and the book documents (§12.1.4) a productive set of grammatical frames for
*quoting* a proverb as evidence within an ongoing sentence rather than reciting it as a
free-standing unit (-다는데, -다더니, -다잖아, -다고, …는 격이다, -는 법이다, -게/기
마련이다, -게 생기다) — captured in the Vocabulary table above. Idioms (12.2) are
organized into four-syllable Sino-Korean idioms (§12.2.1, often formal/literary in
register), body-part idioms (§12.2.2, by far the largest subsection — Korean systematically
uses 간 'liver' where English uses "heart" for courage/nerve, and a wide range of other
body-part-grounded figurative extensions), animal-based idioms (§12.2.4), idioms grounded
in miscellaneous other concrete imagery (§12.2.5, containing some of the most slang-adjacent
material in the whole book — 대박, 왕싸가지, 형광등이다, 바가지 쓰다), and figurative
extensions of ordinary verbs (§12.2.6, e.g. 씹다 'to chew' → 'to badmouth,' 뜨다 'to float'
→ 'to feel someone out'). These are the clearest evidence in the book that Korean slang
formation heavily recycles concrete, embodied, or animal-based imagery via metaphorical
extension rather than inventing wholly new roots.

### Chapter 13 (§13.1–13.3) — Sound symbolism

Korean's sound-symbolic (ideophone) system is described as substantially richer and more
grammatically integrated than English's: sound-symbolic forms function as adverbs or as
verbal/nominal stems taking -이, -이다, -하다, -대다, or -거리다, and a sound-symbolic
adverb frequently *predicts* (and can even fully replace, in headlines/ads) its following
verb — 벌떡 predicts 일어나다, 텅 predicts 비다, 쑥쑥 predicts 자라다/크다/올라가다. The
system has a genuine phonaesthetic grammar, not just an arbitrary lexicon: **vowel
symbolism** — "dark" vowels (어,에,여,우,위,유,워,웨,으,이,의) connote bigger/heavier/
slower/deeper and often negative; "bright" vowels (아,애,야,오,외,요,와,왜) connote
smaller/lighter/swifter/gentler and often positive — illustrated with minimal pairs
(새콤하다/시큼하다, 반짝반짝/번쩍번쩍, 촉촉하다/축축하다). **Consonant symbolism** —
plain consonants can be replaced by their tense or aspirated counterparts for emphasis:
tense consonants read as tight/crisp/intense, aspirated consonants as harsh (박박→빡빡→팍팍
'scrub harder and harder'). *(Note: the book's own printed table illustrating this specific
plain/tense/aspirated consonant triad uses a second, distinct font-substitution encoding not
covered by the +36266 Hangul-syllable-block cipher documented above — those specific jamo
characters could not be safely auto-decoded and are omitted from this file rather than
guessed; the descriptive prose around them decoded cleanly and is captured here in full.)*
The system divides into three types: 의성어 (onomatopoeia proper, sounds of nature),
의태어 (mimetic expressions of visual appearance/motion), and 의정어 (expressions of
feeling/touch, covered in §13.4 — out of scope for this file, reserved for part 2).

---

## Morpheme breakdown examples (agglutination)

Per the project's Korean morphological-typology note and `00_Word_Concept_and_Morphological_
Typology_Guide.md`, Korean word-forms stack case/topic particles, honorific suffixes, tense/
aspect markers, and sentence-final endings onto a single verb stem in a way that hides
real internal structure behind a single orthographic "word." A few representative complex
forms encountered repeatedly in this chunk:

- **가셨습니까?** 'Did (he/she, honored) go?' = 가- (go, stem) + -시- (subject honorific)
  + -었- (past tense) + -습니까 (formal-interrogative, 합니다-style question ending).
- **하시겠습니까?** 'Will you (honored) do it?' = 하- (do, stem) + -시- (subject honorific)
  + -겠- (future/intention/inference) + -습니까 (formal-interrogative ending).
- **드셔 보세요** 'Please try eating (it)' = 드시- (suppletive honorific of 먹다 'eat') +
  -어 (connective vowel) + 보- (auxiliary 'try') + -세요 (formal-but-personal command
  ending, itself analyzable as -시- honorific + -어요 combining to -세요).
  Notably the honorific -시- here appears on 드시다 (already lexically honorific) rather
  than being re-added to 보다, illustrating §2.1.6's "special honorific verb overrides
  normal -시-placement rules."
- **오셨습니까?** 'Did you (honored) come?' = 오- (come) + -시- (honorific) + -었- (past)
  + -습니까 (formal question ending) — contrasted throughout ch. 1–2 with the successively
  less formal 오셨어요? (오- + -시- + -었- + -어요) and 왔어? (오- + -았- + -어, no
  honorific, casual).
- **안녕하십니까?** 'How do you do? (highly formal)' = 안녕하- (be well/at peace, a
  Sino-Korean-root descriptive verb) + -시- (honorific, obligatory in this fixed greeting
  regardless of addressee's actual age/status per §2.1.1) + -ㅂ니까 (formal-interrogative
  ending).
- **말씀드리겠습니다** 'I will tell you (humbly)' = 말씀 (honorific noun 'words,' §2.3)
  + 드리- (humble/object-honorific verb replacing 하다 in this collocation, §2.2) + -겠-
  (intention) + -습니다 (formal-declarative ending).

These examples show the same grammatical "slot machine" (stem – honorific – tense/aspect –
sentence-final ending, with particles attaching to nominal elements separately) recurring
across every register level documented in chs. 1–2; a slang-mechanics pass on Korean should
expect any invented slang morphology to plug into this same slot structure rather than
inventing a wholly different agglutination template.
