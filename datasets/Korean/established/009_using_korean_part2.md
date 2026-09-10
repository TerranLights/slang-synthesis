# Korean — Established Vocabulary/Grammar: Using Korean, Part 2 (Sound Symbolism cont. through Complex Sentences)

**Source:** Miho Choo and Hye-Young Kwak, *Using Korean: A Guide to Contemporary Usage* (Cambridge
University Press, 2008), PDF pages 171-337 of 337 (printed pages 159-325, plus the English/Korean
indices at the very end). This is the second half of the book; a sibling chunk covers PDF pages
1-170 (printed pages 1-158, through mid-Chapter 13). Covers the remainder of **Chapter 13 (Sound
symbolism)**, **Chapter 14 (Numbers)**, and all of **Part II: Grammar** — **Chapters 15-22** (Verb
types, Tense and aspect, Modality, Negation, Particles, Comparison, Conjunctives, Complex
sentences). The English and Korean indices (PDF pages 330-337) are reference apparatus, not source
content, and are not extracted.

**A note on this book's title:** *Using Korean: A Guide to Contemporary Usage* is explicitly
register-focused, and this chunk continues that emphasis — Chapter 13 (Sound symbolism) and
Chapter 14 (Numbers) are drawn almost entirely from colloquial spoken registers, and several
grammar chapters (15, 19 in particular) repeatedly flag `[familiar/casual]`, `[formal/written]`, or
similar explicit register annotations inline. Every such explicit annotation the source itself
marks is preserved in the Notes column or grammar-point text below, per the coverage rule's
mandate to never skip explicit dialectal/register tags.

**Vision-reading / font-corruption note (a new PDF extraction gotcha, not previously seen in this
project):** this PDF has a genuine text layer (`pdftotext` reports real text, `pdfinfo`/`pdffonts`
show embedded fonts), but the Hangul in the Chapter 13-14 portion of this range (PDF pages 171-192,
printed pages 159-180) is rendered through a CID font (`Batang-Identity-H`) with **no usable
ToUnicode mapping** — `pdftotext` silently emits *wrong but internally consistent* Unicode
codepoints for every Hangul character in that range (English text on the same pages extracts
perfectly). This is not the "fixed decodable substitution cipher" gotcha from the Serbian/
Croatian/Bosnian run — the corruption could not be decoded algorithmically. Instead, every PDF page
in the assigned range was rendered to a 200dpi PNG and re-read with Tesseract OCR (`kor` trained
model, `tessdata_best`), which reads the same glyphs correctly since it works from the rendered
glyph shapes rather than the broken CID-to-Unicode map. Every Korean term below that came from a
page in this corrupted range was cross-checked against its own English gloss (already reliable via
`pdftotext`) for semantic sense, and most also self-confirmed by recurring legibly on 2+ pages.
**From PDF page ~195 onward (Chapter 15 on), the book's own text layer is clean** — `pdftotext`
extracts correct Hangul directly, matching a spot-check against OCR — so no vision-reading caveat
applies to Chapters 15-22 (Vision Reading Confidence `n/a` throughout, same as a normal clean-text
extraction).

**Coverage note.** Every grammar point (every numbered subsection 13.3.2 through 22.4) is covered.
Vocabulary is comprehensive but not exhaustive per the spec's coverage rule: the sound-symbolism
mimetic/onomatopoeic inventory (13.3-13.4) is treated as a genuine closed-ish vocabulary set (each
item is a distinct lexeme, not a repeated drill) and extracted in full; the numbers/counters chapter
(14) likewise extracts the full counter inventory as each counter is a distinct classifier lexeme;
for the grammar chapters (15-22), vocabulary tables extract the paradigm-defining example words
(verb pairs, particle sets, idiomatic fixed expressions the book itself calls out) rather than every
incidental noun inside a worked example sentence, per the "skip repeated drills" rule.

---

## Vocabulary

### 13.3.1 Impressions of appearance (cont., p. 159) — mimetic/descriptive adjectives

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 오똑하다 | be pointy/prominent (nose) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159; OCR-recovered (see coverage note above), cross-checked against gloss "high nose." |
| 우락부락하다 | be rough/tough-looking | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |
| 울긋불긋하다 | be colorful/variegated (foliage) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |
| 울퉁불퉁하다 | be bumpy/uneven | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |
| 주렁주렁 | (hanging) in heavy clusters | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159, with 달리다 "hang." |
| 꼬불꼬불하다 | be winding/zigzag | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |
| 차곡차곡 | neatly, in order | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159, with 개다 "fold." |
| 치렁치렁하다 | be draped/dangling long | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |
| 팽팽하다 / 탱탱하다 | be taut/firm | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159, near-synonym pair contrasted with 쪼글쪼글하다 below. |
| 쪼글쪼글하다 | be wrinkled/shriveled | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |
| 펑펑 | (falling) heavily/torrentially | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159, with 쏟아지다 "pour down" (snow). |
| 뚱뚱하다 | be fat | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |
| 포동포동하다 | be chubby/plump | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159; used affectionately of a baby in context. |
| 헐렁헐렁하다 | be loose/baggy | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |
| 호리호리하다 | be slender | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |
| 홀쭉하다 | be gaunt/thinned down | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159 (홀쭉해졌네요 — after illness/weight loss). |
| 희끗희끗하다 | be graying (hair) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 159. |

### 13.3.2 Impressions of behavior/motion/manner (p. 160-162)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 고분고분 | obediently, compliantly | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 굽실거리다 | fawn/bow repeatedly, kowtow | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160, in context of brown-nosing a superior. |
| 기웃거리다 | snoop/peek around | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 깜빡하다 | forget momentarily, blank out | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | plausible_unverified | p. 160 (아차, 깜빡했다 "oops, I forgot"); one nearby line in the OCR pass was too garbled to cross-check twice, though this token itself matches the printed gloss "blinked/forgot." |
| 꼬장꼬장하다 | be stiff/rigid (personality), unbending | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 꼼지락거리다 | fidget, move sluggishly | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 꾸벅꾸벅 (졸다) | (doze) nodding off | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 꿈틀꿈틀하다 | wriggle/writhe | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160, of a worm. |
| 끄덕끄덕하다 | nod (the head) repeatedly | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 덜렁대다 | be careless/clumsy in manner | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 덥석 (받다) | (accept) eagerly/greedily | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | plausible_unverified | p. 160; OCR line partly garbled, reading inferred mainly from gloss "snatch it so quickly." |
| 데굴데굴 (구르다) | (roll) tumbling over and over | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 동동 (구르다) | (stamp feet) impatiently/urgently | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 두리번거리다 | look around restlessly/searchingly | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 나긋나긋하다 | be soft/gentle-mannered | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160, contrasted with 뚱하다 below. |
| 뚱하다 | be sullen/taciturn | descriptive verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 160. |
| 모락모락 (나다) | (rise) gently in wisps (steam) | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161, from a baked sweet potato. |
| 무럭무럭 (자라다) | (grow) vigorously | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 반짝가수 | flash-in-the-pan singer, one-hit wonder | noun (compound) | slang | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. Compound of 반짝 (mimetic, "flash/glitter briefly") + 가수 "singer" — a genuinely slangy coinage, not just a descriptive adverb; flagged as directly relevant to slang word-formation. |
| 반짝세일 | flash sale, surprise one-day sale | noun (compound) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. Same 반짝- prefix pattern as 반짝가수 above — recurring productive slang-adjacent compounding. |
| 벌렁 (자빠지다) | (fall) flat on one's back | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 벌벌 (떨다) | (tremble) violently (fear) | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 부들부들 (떨다) | (shake) uncontrollably (anger) | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 부슬부슬 (오다) | (rain) in a light drizzle | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 비실비실하다 | be listless/weak, mope around | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 비틀비틀하다 | stagger/wobble | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161, of impaired driving. |
| 빠릿빠릿하다 | be quick/alert (opp. of sluggish) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161, negated in context ("no such quickness"). |
| 느려 터지다 | be painfully/extremely slow | verb (idiom) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161; -터지다 as an intensifying suffix-like usage, worth flagging for morphological-play analysis later. |
| 뻐끔뻐끔 (피우다) | (smoke) puffing repeatedly | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 입도 뻥끗하지 마 | don't breathe a word (idiom) | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 뾰로통하다 | be sulky/pouting | descriptive verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | low_confidence | p. 161; OCR rendered this as "쁘로통해서," which does not parse as a real Korean stem — reconstructed as 뾰로통하다 based on the English gloss "sulking and pouting," but the OCR reading itself does not confirm the initial syllable cleanly. |
| 살금살금 | stealthily, tip-toeing | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 살살 (달래다) | (soothe) gently | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 윽박지르다 | scold/browbeat harshly | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | plausible_unverified | p. 161; OCR shows "옥박지르면," reconstructed as the standard verb 윽박지르다 based on context ("harshly scold a crying child"). |
| 솔솔 (불다) | (blow) gently (breeze) | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 스르르 (감기다) | (close) slowly (eyes) | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 161. |
| 슬슬 | slowly, gradually, casually | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 시시콜콜 | in trivial/exhaustive detail | mimetic adverb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 싹싹 (먹어 치우다) | (eat) completely, leaving nothing | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | plausible_unverified | p. 162; OCR shows "짝짝" both times it occurs on this page, but 싹싹 is the standard form matching "leave nothing/eat it all"; treated as an OCR ㅅ/ㅉ confusion. |
| 싹싹하다 | be affable/pleasant (of a person) | descriptive verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | plausible_unverified | p. 162, of restaurant staff; same ㅅ/ㅉ OCR ambiguity as above. |
| 아장아장 (걷다) | (walk) toddling | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162, of a baby. |
| 안절부절못하다 | be restless/fidgety (idiom) | verb (idiom) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 어물어물하다 | be evasive, hem and haw | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 어영부영하다 | idle away time, drift aimlessly | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 얼렁뚱땅 (넘어가다) | fudge/gloss over vaguely (idiom) | mimetic adverb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 엉금엉금 (기다) | (crawl) slowly/laboriously | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162, of a bad back. |
| 오들오들 (떨다) | (shiver) from cold | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 우물쭈물하다 | hem and haw, hesitate indecisively | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 차근차근 | step-by-step, calmly and methodically | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 허둥대다 | be flustered, fluster about | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 찔찔매다 | struggle helplessly, be at one's wit's end | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162, of students overwhelmed by a hard test. |
| 팔짝팔짝 (뛰다) | (jump) up and down (anger) | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 162. |
| 해롱해롱하다 | act tipsy/silly (drunk) | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163. |
| 허겁지겁 | in a great hurry/hastily | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163. |
| 허둥지둥하다 | be in a fluster, scramble around | verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163. |
| 허우적대다 | flail/splash about | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163, of a drowning person. |
| 헐레벌떡 (뛰다) | (dash) breathlessly | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163. |
| 활활 (타다) | (burn) blazing | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163. |
| 후닥닥 (뛰어나가다) | (dash out) abruptly | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163. |
| 후들후들 (떨다) | (shiver/tremble) from illness | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163. |
| 훌훌 (털다) | (shake off) casually/completely | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163, of worries. |
| 휘청거리다 | stagger/totter | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163, of tired legs. |
| 흔들흔들하다 | wobble/shake loosely | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163, of a loose tooth. |
| 흥청망청 (쓰다) | (spend) squandering recklessly | mimetic adverb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163, of money. |
| 힐끗힐끗 (곁눈질하다) | glance sideways repeatedly | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163. |

### 13.4.1 Expressions denoting feeling (p. 163-165)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 가물가물하다 | be hazy/faint (memory) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163. |
| 간질간질하다 | be itchy/tingly | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 163, of ears (superstition: someone is talking about you). |
| 근질근질하다 | be itching (to do something) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 느글느글하다 | be nauseous/queasy | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164, after eating raw fish. |
| 꼬들꼬들하다 | be firm/dry (of cooked rice, not soft) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 두근두근 (뛰다) | (pound) with excitement (heart) | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 따끈따끈하다 | be piping hot | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164, of soup. |
| 뜨끔하다 | feel a stinging twinge (of guilt) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 띵하다 | be dull/throbbing (headache) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 말똥말똥하다 | be wide awake/alert (eyes) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 매슥거리다 | feel nauseous | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164, of motion sickness. |
| 바짝바짝 (타다) | (burn/parch) intensely (thirst) | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 싱숭생숭하다 | be restless/scattered (mind) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 아찔하다 | feel dizzy/faint (from shock) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164, "I almost died" context. |
| 알쏭달쏭하다 / 아리송하다 | be vague/perplexing | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164, near-synonym pair given together in the source. |
| 어질어질하다 | be dizzy, head spinning | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 얼얼하다 | be numb (from anesthetic) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 욱신욱신 (쑤시다) | throb repeatedly with pain | mimetic adverb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164, after carrying heavy things. |
| 으슬으슬하다 | have chills (cold/fever) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 164. |
| 지끈지끈하다 | have a throbbing headache | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165. |
| 짜릿하다 | be thrilling, give a tingling sensation | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165, of a moving film. |
| 화끈거리다 | burn/flush (embarrassment) | verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165. |

### 13.4.2 Expressions denoting touch (p. 165)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 까칠까칠하다 | be rough/dry (skin) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165, winter skin. |
| 말랑말랑하다 | be soft/squishy | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165, contrasted with 딱딱하다 below. |
| 딱딱하다 | be hard/stiff | descriptive verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165. |
| 반들반들하다 | be shiny/glossy | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165, of a well-kept car. |
| 번들번들하다 | be greasy/shiny (oily skin) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165. |
| 보들보들하다 | be soft/silky (skin) | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165. |
| 빤질빤질하다 | be slick/smooth-looking, superficially polished | descriptive verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | low_confidence | p. 165; OCR shows "빠르르하게," which is not a standard form — reconstructed as 빤질빤질하다 based on the gloss "sleek-looking face... superficial playgirl," but not independently confirmed. |
| 뻣뻣하다 | be stiff (not soft/pliable) | descriptive verb | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165, of leather. |
| 쫄깃쫄깃하다 | be chewy | descriptive verb | colloquial.mimetic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 165, of rice cake. |

### 14.1-14.2 Number systems (p. 166-167)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 하나/둘/셋/넷/다섯 | one/two/three/four/five (native) | numeral | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 166. Full native series 1-10, 20-99 in the grammar point below. |
| 한/두/세/네/스무 (+counter) | one/two/three/four/twenty (bound pre-counter forms) | numeral (bound form) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 166; see morpheme note below — native numerals 1-4 and 20 change shape before a counter. |
| 일/이/삼/사/오 | one/two/three/four/five (Sino-Korean) | numeral | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 167. Full Sino-Korean series 1-10, 20-99, plus 백/천/만/억/조 "hundred/thousand/ten-thousand/hundred-million/trillion" below. |
| 조/억/만 | trillion-equivalent / hundred-million / ten-thousand (Korean 4-digit grouping units) | noun (numeral classifier) | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 167; Korean groups large numbers in 4-digit units, not 3-digit units like English — a structurally significant contrast, not just vocabulary. |

> **한 (개)** = 하나 (one, native numeral, citation form) → 한 (bound form obligatorily used
> directly before a counter) — 하나/둘/셋/넷/스물 alternate to 한/두/세/네/스무 before a counter
> (14.1.1 note, p. 166); 다섯-아흔 do not change shape. This alternation is itself a small,
> productive morphological rule, not a set of separate lexical items.

### 14.2.2 Sino-Korean ordinal counters (p. 168) — sample of counter-specific ordinal readings

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 제- | ordinal prefix ("the Nth") | prefix | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168; explicitly marked by the source as usually **omitted outside formal writing** — a direct formal/colloquial register contrast. |
| 등 | rank/place (e.g., top score) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168. |
| 급 | class/grade (e.g., hotel rating) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168. |
| 단 | rank/level (martial arts) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168, T'aekwondo rank. |
| 대 | ordinal "-th" (presidents, etc.) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168. |
| 회 | inning/episode | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168, baseball/drama. |
| 차 | round/turn | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168, exam/party rounds. |
| 층 | floor (of a building) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168. |
| 학년 | grade/year (in school) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168. |
| 집 | volume/edition (of an album) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168. |
| 세 | generation (nth-generation immigrant) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 168. |

### 14.3.1 Counters/classifiers (p. 170-172) — full inventory given by the source

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 명 | counter for people | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 170. |
| 갑/보루 | counter: pack / carton (cigarettes) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 개 | counter for generic 3-D objects (default classifier) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 권 | counter for bound material (books, magazines) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 그루 | counter for trees | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 대 | counter for machines/large appliances | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172; note this 대 is a distinct homograph from the ordinal 대 above and the rib-bone counter 대 below. |
| 대 / 개비 | counter for tiny slender objects (cigarettes, matches) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 매 | counter for sheets of paper [formal/written] | counter | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172; explicitly noted as unusual in taking Sino-Korean numbers directly. |
| 벌 | counter for clothes/silverware sets | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 부 | counter for periodicals/multi-page documents | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 송이/다발 | counter for stems/bouquets (flowers) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 자루 | counter for long slender objects (pencils) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 장 | counter for thin flat objects | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 점 | counter for pieces of art | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 채 | counter for buildings | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 척 | counter for ships | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 첩 | counter for packs of herbal medicine | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 켤레 | counter for pairs (shoes, socks, gloves) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 통 | counter for letters in an envelope | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 172. |
| 그릇/공기 | counter for a bowl (of soup/rice) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173, food-specific counters. |
| 단 | counter for a bunch of vegetables | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 모 | counter for tofu/jelly cakes | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 모금 | counter for a sip/puff | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 분 | counter for a serving | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173; homograph of the honorific person-counter 분 below — Sino-Korean numbers are used for this serving-counter sense specifically. |
| 송이 | counter for grapes/small round fruit | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 숟갈/젓갈 | counter for a spoonful/chopstickful | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 알 | counter for small round-shaped things (grapes, eggs) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 잔 | counter for liquid in a glass/cup | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 컵 | counter for liquid in a cup/glass | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 접시 | counter for a dish (of food) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 쪽 | counter for a small slice (apple, garlic) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 통 | counter for round-shaped fruit (watermelon, garlic bulb) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173; homograph of the letter-counter 통 above — same shape, distinct sense. |
| 포기 | counter for a head of cabbage | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 분 | honorific counter for people (vs. 명) | counter | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173, of guests — register-marked polite alternative to 명. |
| 쌍 | counter for a couple/pair (people) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 마리 | counter for animals/fish/birds | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 173. |
| 건 | counter for agenda items/incidents/bills | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 174. |
| 곡 | counter for pieces of music | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 174. |
| 대 | counter for injections/beatings | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 174; a third homograph of 대 alongside the machine-counter and ordinal-counter senses above. |
| 통 | counter for phone calls/rolls of film | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 174; yet another 통 homograph (letters / round fruit / phone calls). |
| 편 | counter for movies/musicals/poems | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 174. |
| 가지 | counter for sorts/kinds | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 174. |

> **Morphological note — counter homography:** 대, 통, and 분 each recur across this inventory as
> distinct counters with unrelated meanings depending on what's being counted (대: machines vs.
> tiny slender objects vs. injections vs. ordinal position; 통: letters vs. round fruit vs. phone
> calls; 분: servings vs. honorific people-counter). This is a genuine case where the same surface
> "word" is not one lexical item — the classifier system distinguishes senses purely by what noun
> co-occurs with it, not by any change in the counter's own form.

### 14.3.2-14.3.6 Measurement, time, arithmetic, money vocabulary (p. 174-179) — key terms

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 평 | traditional area unit (≈35.57 sq. ft.) | counter/noun | archaic | — | contemporary (source published 2008), but the unit itself predates 2007 | — | Korea | grammar_reference | n/a | verified | p. 174-175. Officially prohibited in real-estate/commercial use as of July 2007 in favor of 제곱미터 — a genuine historical/regulatory usage-shift the source itself dates precisely; see grammar point below. |
| 근 | traditional weight unit (600 g) | counter/noun | archaic | — | contemporary (source published 2008), unit predates 2007 | — | Korea | grammar_reference | n/a | verified | p. 175; also officially phased out in 2007 in favor of 그램/킬로그램. |
| 관 | traditional weight unit (3.75 kg) | counter/noun | archaic | — | contemporary (source published 2008), unit predates 2007 | — | Korea | grammar_reference | n/a | verified | p. 175; also phased out in 2007. |
| 돈 | traditional weight unit for gold (3.76 g) | counter/noun | archaic | — | contemporary (source published 2008), unit predates 2007 | — | Korea | grammar_reference | n/a | verified | p. 175; also phased out in 2007. |
| 자 | traditional length unit (≈30.3 cm) | counter/noun | archaic | — | contemporary (source published 2008) | — | Korea | grammar_reference | n/a | verified | p. 174. |
| 뼘 | a hand-span's length (idiomatic measure) | noun | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 174. |
| 치 | a traditional small unit, only surviving in idioms | noun | archaic | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 174, "한 치의 양보도 없다" (not an inch of concession). |
| 말 / 되 | traditional volume units (1 말 = 10 되 ≈ 4 gallons) | counter/noun | archaic | — | contemporary (source published 2008) | — | Korea | grammar_reference | n/a | verified | p. 174, noted as no longer commonly used. |
| 양력 / 음력 | solar calendar / lunar calendar | noun | core | — | contemporary (source published 2008) | — | Korea | grammar_reference | n/a | verified | p. 176; 음력 governs holidays like 추석 and 구정. |
| 만- | prefix marking "international/Western age" (vs. Korean age) | prefix | core | — | contemporary (source published 2008) | — | Korea | grammar_reference | n/a | verified | p. 176; Korean-age/Western-age is a real, systematic cultural-numeric distinction. |
| 반 | half | numeral fraction term | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 177 (분수/소수 section). |
| 구구단 | multiplication table | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 177. |
| 배 | -fold, "times as much" (multiplier) | counter | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 177, native numbers used with 배 (두배, 열배); Sino-Korean used once fractional/≥20. |
| 서너 | three or four (approximate quantity) | numeral (approximative) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 178. |
| 너덧 | four or five (approximate quantity) | numeral (approximative) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 178. |
| 단독주택 | single-family (detached) house | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 178, illustrating the 단- "single/one and only" prefix. |
| 단층집 | single-story house | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 178. |
| 단칸방 | small single room | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 178. |
| 수- | prefix: "several/many" (수천 번, 수십 개) | prefix | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 179. |
| 과반수/대다수 | majority | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 179. |
| 극소수 | a tiny minority | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 179. |
| 소수민족 | ethnic minority | noun | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 179. |
| -들 | plural marker suffix (optional, animate-leaning) | suffix | core | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 180 (14.4.3); attaches to nouns, adverbs, even verb stems in casual imperatives (놀러들 와라). |
| 등 | "etc." (formal enumerator) | suffix/noun | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | verified | p. 180, explicitly marked [formal/written] by the source. |

---

## Grammar points

### 13.3.1-13.3.2 Impressions of appearance / behavior-motion-manner (cont., p. 159-163)

Continues the mimetic-vocabulary chapter begun before this chunk's start: Korean has a very large,
productive inventory of reduplicated (and some non-reduplicated) mimetic adverbs and descriptive
verbs that vividly depict visual appearance (13.3.1) and behavior/motion/manner (13.3.2). These are
not marginal or archaic — the book's own example sentences are conversational and contemporary
throughout, and several items double as slang-adjacent coinages (see 반짝가수, 반짝세일 above,
both built on the mimetic root 반짝 "flash/glitter briefly"). This is a genuinely productive
word-formation pattern worth flagging for later `morphological_play`/`sound_symbolism` mechanics
analysis: reduplication (X X) is itself a marked, meaningful morphological operation in Korean,
distinct from ordinary agglutinative suffixing.

### 13.4.1-13.4.2 Expressions denoting feeling and touch (p. 163-165)

The same mimetic/reduplicative pattern extended to internal bodily/emotional sensations (13.4.1:
itching, nausea, dizziness, pain, guilt) and tactile sensations (13.4.2: texture, dryness,
greasiness, stiffness). Structurally identical to 13.3 — same C(V)C(V) reduplication template,
same -하다/-거리다/-대다 verbalizing suffixes — just a different semantic domain. Treated together
here as one continuous phenomenon (sound symbolism generally) rather than as separate grammar
mechanisms.

### 14.1 Native Korean numbers (p. 166)

Two fully parallel numeral systems coexist in Korean: **native Korean** numbers, which only go up
to 99, and **Sino-Korean** numbers (borrowed from Chinese), which can express arbitrarily large
values. Native cardinal numbers 1-4 and 20 (하나, 둘, 셋, 넷, 스물) take a bound alternate shape
(한, 두, 세, 네, 스무) obligatorily before a counter — this is a small closed morphological
alternation, not free variation. Native ordinal numbers are formed by suffixing **-째** to the
cardinal (둘째/두째, 셋째/세째...), with 첫째 "first" as the sole suppletive exception, and when a
counter is present -째 attaches after the counter, not the number (사과 세 개째 "the third apple").

### 14.2 Sino-Korean numbers (p. 167-170)

Sino-Korean numbers group into **4-digit** units (만/억/조 = ten-thousand/hundred-million/trillion)
rather than English's 3-digit grouping (thousand/million/billion), even though Arabic-numeral
writing still uses English-style 3-digit comma grouping — this creates a genuine parsing mismatch
between how a number is written and how it's read aloud in Korean, which the book illustrates with
a worked 13-digit example. Sino-Korean ordinal numbers use the prefix **제-**, which the book notes
is *usually dropped outside formal writing* — a clean formal/colloquial register contrast baked
directly into ordinal-number morphology.

### 14.3 Native versus Sino-Korean numbers: division of labor (p. 169-180)

The book frames this as the chapter's real payoff: the two numeral systems are not interchangeable
free variants but have a fairly strict division of labor by function, occasionally producing sharp
meaning contrasts when both types can combine with the same counter (**한 페이지** "one page" vs.
**일 페이지** "page 1"; **두 과** "two lessons" vs. **이 과** "lesson 2" — quantity vs. ordinal
position). A rarer case pits native vs. Sino-Korean forms against each other as a **register**
contrast rather than a meaning contrast: 사진 두 장 (colloquial) vs. 사진 2매 (written/formal) for
"two photos," 스무 살 (colloquial) vs. 20세 (written/formal) for "20 years old" — the same referent,
distinguished purely by speech style.

- **14.3.1 Counting/classifiers:** Korean numbers virtually always co-occur with a counter/
  classifier indicating the semantic type of what's being counted (see the counter-homography note
  above the counter vocabulary table). Large native-number counts default to counting in twos
  (둘, 넷, 여섯...) by convention. Sino-Korean numbers increasingly take over for round multiples of
  ten (20+), even where a native form exists.
- **14.3.2 Units of measurement:** Sino-Korean numbers are used throughout the metric system and
  most American-derived units (인치 "inch"). A small set of **traditional Korean units** (평, 근,
  관, 돈) were **officially prohibited in commercial/legal use as of July 2007** in favor of metric
  equivalents — a precisely-dated real regulatory event the book documents (see the archaic-tier
  vocabulary rows above), though the traditional units persist in everyday speech.
- **14.3.3 Time, date, age:** Hours use native numbers, minutes/seconds/dates/years use Sino-Korean
  — famously mixed within a single time expression (7시 20분 [일곱 시 이십 분], native hour + Sino
  minute). Korean age counts a person as 1 year old at birth and increments at New Year's, not on
  the birthday; **만-** marks the Western/international-age system used for legal purposes, and the
  book notes this creates a 1-2 year gap between the two systems for the same person.
- **14.3.4 Arithmetic and fractions:** Sino-Korean numbers for formal arithmetic, fractions,
  decimals, and the multiplication table (구구단); native numbers for informal small-quantity
  subtraction in speech (다섯에서 셋을 빼면 둘이다).
- **14.3.5 Money:** Sino-Korean numbers throughout; the archaic unit 푼 survives only in the fixed
  idiom 한 푼도 없다 "I'm penniless."
- **14.3.6 Transportation numbering:** Sino-Korean numbers for subway lines/bus numbers.

### 14.4 Expressions of quantity (p. 178-180)

- **14.4.1 Approximate quantities:** formed by juxtaposing two adjacent native numbers (서너 "3-4,"
  너댓"4-5") or by attaching quantity-approximating particles/words (정도, -쯤, -가량, -안팎으로) to
  a Sino-Korean numeral.
- **14.4.2 Non-numerical quantity expressions:** the productive prefixes **단-** "single/only one"
  (단독주택, 단층집, 단칸방) and **수-** "several/many" (수천 번, 수십 개), plus a set of quantity
  nouns/adverbs for proportional quantity: 대부분 "most," 일부 "some," 반 "half," 과반수/대다수
  "majority," 극소수/소수 "minority," 딱 "just/exactly," X 미만/이하/이상 "less than / not more
  than / more than X."
- **14.4.3 Markers of plurality:** reduplicating an interrogative pronoun to mean "all the various
  X" (누구누구 "who all," 뭐뭐 "what all," 어디어디 "what all places," 언제언제 "which days");
  the general plural suffix **-들** (which, unusually, can attach even to an adverb or a verb form
  in casual commands: 놀러들 와라 "come play, all of you"); and the formal enumerator **등** "etc.,"
  explicitly marked [formal/written] by the source, contrasting with the casual reduplication
  strategies just described.

### 15.1 Action verbs versus descriptive verbs (p. 183-186)

Korean's verb category is broader than English's — it includes both **action verbs** (동사, denote
events: 자다 "sleep," 먹다 "eat") and **descriptive verbs** (형용사, denote states: 재미있다 "be
fun," 맑다 "be clear" — functionally like English adjectives but grammatically verbs, since they
inflect for tense). The two subclasses are distinguished by two morphological tests:
- **Present tense:** action verbs take -ㄴ/는다 (잔다, 먹는다); descriptive verbs take bare -다
  (재미있다, 맑다) with no present-tense suffix.
- **Adnominal (noun-modifying) present form:** action verbs (and 있다/없다 compounds) take -는
  (자는, 먹는, 재미있는); descriptive verbs take -ㄴ/은 (한산한, 맑은).

A small set of words straddle both categories with a meaning shift (크다 "be tall" [descriptive] vs.
"grow" [action]; 늦다 "be late" [descriptive] vs. "be running late/getting later" [action]).

**15.1.2 Converting descriptive verbs to action verbs:**
- **-어지다** turns a state into a *change of state* (짧다→짧아지다 "get short(er)," 까맣다→까매지다
  "get/turn black").
- **-어하다** turns an inner psychological state into its *external manifestation* (좋다→좋아하다
  "like," 반갑다→반가워하다 "act/seem glad"). With a first-person subject either form can describe
  one's own feelings (정말 부럽다 / 얼마나 부러워하는지), but for a command or a third-person
  subject only the -어하다 action-verb form is grammatical (너무 섭섭해하지 마세요, never
  *너무 섭섭하지 마세요 in that sense). The book also draws out a fine-grained contrast between
  `X가 좋아요` (ambiguous between "X is good" and "I like X," and usable for one-off/temporary
  feelings — 날씨가 좋아요 works looking at today's sky) versus `X를 좋아해요` (unambiguously "I
  like X" as a general, standing preference — 날씨를 좋아해요 alone sounds odd, but 비오는 날씨를
  좋아해요 "I like rainy weather [generally]" is fine).

### 15.2 Intransitive versus transitive verbs (p. 186-198)

Unlike English, where many verbs freely alternate between intransitive and transitive use (door
opens / he opens the door), Korean mostly requires **two distinct verb forms**. 15.2.1 gives the
few genuine same-form alternators (움직이다, 멈추다) versus the much more common two-form pattern
(줄다/줄이다 "decrease," 붙다/붙이다 "attach," 끓다/끓이다 "boil," 녹다/녹이다 "melt," 얼다/얼리다
"freeze," 타다/태우다 "burn," 깨다/깨우다 "wake up," 열리다/열다 "open," 닫히다/닫다 "close").
15.2.2 covers a **noun + 되다/나다 (intransitive) vs. noun + 하다/내다 (transitive)** compounding
pattern productive across many Sino-Korean nouns (시작 "start" → 시작되다/시작하다; 겁 "fear" →
겁나다/겁내다, usable with or without a particle: 겁나다 or 겁이 나다).

### 15.3 Special sub-types of intransitive verbs (p. 188-198)

- **15.3.1 -이/히/기/리 intransitives:** derive an intransitive/passive counterpart from a
  transitive verb (덮다→덮이다, 잠그다→잠기다, 묻다→묻히다, 안다→안기다, 듣다→들리다). Three
  distinct uses: (a) **passive** (청소년들이 이 책을 읽습니다 → 이 책이 청소년들에게 읽힙니다),
  with the "by"-phrase marked -에게/한테 (animate) or -에 (inanimate), switching to the more formal
  -에 의해(서) when -에게/한테 would be ambiguous with "to"; (b) an **adversity passive** allowing
  a -을/를-marked noun even in passive voice (소매치기한테 지갑을 털렸어요 "I got robbed of my
  wallet"); (c) a **potential/uncontrollable** sense, always present tense, meaning something
  happens beyond the subject's control (눈이 자�다 감긴다 "my eyes keep involuntarily closing," 밥이
  안 먹혀요 "I can't manage to eat"). A long list of **idiosyncratic fixed expressions** with no
  transitive counterpart is given (기가 막힌다 "I'm speechless," 교통이 막힌다 "traffic is jammed,"
  얹혀살다 "live as a parasite," 쪽 팔린다 "it's embarrassing" — explicitly marked
  **[familiar/casual]** by the source, a directly flagged register annotation).
- **15.3.2 지다 intransitives:** 지다 attached to a transitive verb stem (쏟다→쏟아지다, 찢다→
  찢어지다, 세우다→세워지다) forms the same three uses as -이/히/기/리 above (passive, e.g.
  허물다→허물어졌다; potential/uncontrollable, e.g. 접시가 잘 깨진다 "the dish breaks easily"; and
  idiosyncratic fixed forms, e.g. 발랑 까졌다 "she's wild/brash," 잠이 쏟아진다 "overwhelming
  drowsiness"). A handful of verbs can form their intransitive either way (찢기다/찢어지다,
  믿기다/믿어지다).
- **15.3.3 되다 intransitives:** Sino-Korean noun + 하다 (transitive) alternates with noun + 되다
  (intransitive/passive): 해결하다/해결되다, 사용하다/사용되다. Same passive and
  potential/uncontrollable uses as above (긴장되는데요 "I'm getting nervous," 기대됩니다 "I'm
  looking forward to it").
- **15.3.4 Other special intransitives:** noun + 당하다 "suffer/undergo" forms compounds with an
  inherently negative passive sense (강간당하다, 배반당하다, 무시당하다, 왕따당하다 "be
  ostracized/bullied" — this last one worth flagging as a real contemporary social-register term);
  noun + 받다 "receive" forms a positive-or-neutral passive sense (사랑받다, 칭찬받다, 존경받다,
  처벌받다). 속다 "be deceived" and 맞다 "get hit" are lexically passive with no suffix at all.

### 15.4 Special sub-types of transitive verbs (p. 194-198)

- **15.4.1 -이/히/기/리/우/구/추 causatives:** the widened suffix set derives a transitive/
  causative verb from an intransitive one (울다→울리다 "make cry," 서다→세우다 "make stand/
  establish/pull over" — note the meaning can shift substantially, not just add an object). When
  the base verb is already transitive, the same suffixes add a causee (indirect object): 먹다→먹이다
  "feed X to Y," 입다→입히다 "dress Y in X," 신다→신기다 "put X on Y's feet." Two use-types are
  distinguished: causing *someone* to do something (승진하려고 웃사람들한테 돈을 먹였대요("bribed")
  vs. causing *something* to happen, which shades into ordinary transitivity (요가에 재미를
  붙였어요 "took an interest in yoga"). A long idiosyncratic-fixed-expression list follows (본때를
  보여 주다 "teach a lesson," 이름을 날리다 "win fame," 입을 맞추다 "kiss" / "coordinate a
  story/alibi" — genuinely idiomatic, worth flagging for later idiom-based slang analysis).
- **15.4.2 -게 하다 causatives:** fully productive with any verb, expressing "make/let someone do
  X" (하다 can be replaced by 만들다 for "make" specifically). Tends to express *less direct*
  causation than the -이/히/기/리/우/구/추 forms where both exist (먹이다 "feed [directly]" vs. 먹게
  하다 "make/let eat [less direct]"), and the -이/히/기/리 forms often lexicalize into idioms that
  can't alternate with -게 하다 at all (맛이 죽인다 "it has a killer taste" — not causative in any
  real sense any more).
- **15.4.3 시키다 causatives:** for a specific closed set of (mostly Sino-Korean) nouns, 시키다
  substitutes for 하다 to add causative meaning (경쟁하다→경쟁시키다 "make compete," 소개하다→
  소개시키다 "have someone introduce themselves"). The book lists the noun set explicitly: 공부,
  구경, 긴장, 노래, 승진, 연습, 일, 해산, 확신.
- **15.4.4 -뜨리다 intensified transitives:** attaches to a small set of -지다 intransitives to
  form their transitive/causative counterpart with an added intensifying nuance (부서지다→
  부서뜨리다, 떨어지다→떨어뜨리다, 퍼지다→퍼뜨리다). 깨다 and 깨(뜨리)다 are both already
  transitive "break" — here -뜨리다 is purely intensifying, not causative-forming.

### 16.1 Tense and aspect on sentence-final verbs (p. 199-211)

- **16.1.1 Basic form:** present state for descriptive verbs (bare -다); for action verbs the same
  bare/-ㄴ/는다 form covers present, habitual, "past continuing to present," future, and in-progress
  readings depending on context (다음 주에 출장간다 "I'm going on a business trip next week").
- **16.1.2 -어/아 있다:** continuing present state resulting from a completed action, restricted to
  a small set of intransitive action verbs with definite endpoints (열려 있다 "is [left] open," 깨어
  있다 "is [still] awake"); honorific subject swaps 있다→계시다.
- **16.1.3 -고 있다:** action-in-progress, usable with any action verb. With verbs of wearing/
  contact it's ambiguous between ongoing donning and an already-complete "is wearing" state
  (disambiguate with -고 있는 중이다 for strictly ongoing); with cognition verbs it denotes a
  resulting mental state (깨닫고 있다 "realizes"). Notably, 있다 can be swapped for the demeaning
  fixed forms **앉아 있다** / **자빠졌다** ("sitting on one's ass" / "lying around") to editorialize
  disapproval of the subject's behavior (티브이만 보고 자빠졌어 "he's doing nothing but watching TV
  all day") — a register-loaded construction worth flagging directly for slang/insult mechanics.
  Contrast: -어 있다 = continuing *state* (학교에 와 있다 "is at school"), -고 있다 = continuing
  *action* (학교에 오고 있다 "is on the way to school").
- **16.1.4 -었/았/ㅆ:** the "past tense" suffix. For descriptive verbs it's simply past state, with
  the special verb 멀다 ("be far") notably ambiguous between past and *non-past* readings
  (도착하려면 아직 멀었니? "are we far from there [now]?"). For action verbs, -었 covers both a
  genuine past action and (very commonly) a completed action whose *resulting present state* is the
  actual point (감기 걸렸어요 "I have a cold," not just "I caught one"; 화났니? "are you angry?").
  A large worked list of such dual-reading verbs is given (전화벨, 옷, 고기, 라면, 이, 얼굴, 장미,
  부인, 눈, 귀 — states of dress/decay/ripening/age/swelling/blindness/deafness). To specify an
  unambiguous *past-but-over* state, a second -었 is required (-었었, see 16.1.5); to report a past
  state neutrally without committing to the present, -었더라 is used instead (16.1.6).
- **16.1.5 -었었:** for descriptive verbs, a subtle "more distant past" nuance over plain -었. For
  action verbs, the contrast sharpens into two real uses: (a) a genuinely more remote past relative
  to another past reference point (전에 잠깐 만났었어요 "I had met him before"), or (b) explicit
  **discontinuation** of a state that once held but no longer does (신혼여행 갔었습니다 "they went on
  their honeymoon [and are back]" vs. 신혼여행 갔습니다 "[and are still gone]"; 결혼을 했었습니다 "I
  was married before [not now]" vs. 결혼을 했습니다 "I'm married").
- **16.1.6 -더/-었더:** a retrospective-report ending for something perceived, noticed, or heard
  secondhand — **spoken register only**, never occurring in the formal 합니다 style (the archaic
  -ㅂ/읍디다 variant is explicitly flagged by the source as old-fashioned, "used only among old
  folks"). Register paradigm across 해요/반말 and statement/question is given in a table (해요
  statement: -더라구요/-데요/-던데요; 반말 statement: -더라/-데/-던데; 해요 question: -던가요; 반말
  question: -디/-던). Pragmatically restricted: **not used for long-known facts about oneself or
  close family** (우리 엄마는 요리를 잘 하시더라 sounds wrong — you'd know this too well to "notice"
  it), but perfectly fine for reporting one's *own* momentary feelings/reactions from a first-person
  vantage (기가 막혀서 말이 안 나오더라 "I found myself speechless"). -었더 (vs. plain -더|) adds
  that the reported action/process was already complete at observation time (비 왔더라 "I noticed
  it had rained" vs. 비 오더라 "I noticed it was raining") and, unlike -더, never occurs on
  descriptive verbs in sentence-final position.
- **16.1.7 -을/-겠 future forms:** not pure future tense but intention/conjecture forms that
  indirectly evoke futurity: -을래(요) "I'm going to / are you going to," -을게(요) "I will / let me"
  (promissory, oriented to the listener's concern), -을까(요) "shall I/we...I wonder," -었을까(요)
  "I wonder whether...-ed," -을 거/-겠 "will," -었을 거/-었겠 (conjecture about a past event). The
  promissory -을게요 vs. plan-stating -을 거예요 contrast is explicitly about **register/social
  framing**: -을게요 when the listener has a personal stake in your intention (전화할게요 to someone
  waiting for your call; 담배 끊을게 to a worried spouse) vs. -을 거예요/거야 as a neutral statement
  of plan to anyone else.
- **16.1.8 -을 거 vs. -겠 (conjecture):** -을 거 = conjecture from knowledge/evidence/reasoning;
  -겠 = conjecture from feeling/impression/circumstantial cue. -겠 is also the register-marked
  choice for expressing **sympathy/concern** (피곤하시겠어요 "you must be tired [I feel for you]"
  vs. neutral 피곤하실 거예요 "you'll be tired").
- **16.1.9 -겠-only uses (no -을 거 equivalent):** a cluster of **courteous/formulaic register**
  functions unique to -겠— polite requests (좀 앉으시겠습니까?), polite promises (다시 전화
  드리겠습니다), fixed courteous formulas (처음 뵙겠습니다 "how do you do," 실례하겠습니다 "excuse
  me [entering]," 그럼 이만 줄이겠습니다 "let me stop here" in letter-closings), and the register of
  **formal broadcast/announcement reports** (weather forecasts, MC announcements at a ceremony) —
  plus ability/possibility conjecture (이 거 다 먹겠니?) and a set of **hyperbolic idiomatic fixed
  expressions** built on -겠 (졸려 죽겠다/미치겠다 "dying/going crazy from sleepiness," 배꼽
  빠지겠다 "my belly-button's going to fall out [from laughing]," 상다리 부러지겠다 "the table legs
  will break [so much food]," 해가 서쪽에서 뜨겠다 "the sun will rise in the west [something
  unexpected happened]," 귀청 떨어지겠다 "my eardrums will fall out [too loud]," 땅 꺼지겠다 "the
  ground will cave in [from your sighing]" — a genuinely productive hyperbole-via-겠 slang/register
  pattern worth flagging for later mechanics analysis).

### 16.2 Tense and aspect on non-final verbs (p. 211-218)

- **16.2.1 Conjunctive constructions:** an inner (non-final) clause's verb may either omit its own
  tense marking and rely entirely on the sentence-final verb for interpretation, or carry its own
  independent tense — and which choice is made can *change the meaning*: 학교에 갔다가 서점에
  들렀어 (went to school, then later dropped by a bookstore) vs. 학교에 가다가 서점에 들렀어 ("on
  the way to school" — dropped by before arriving) — same conjunctive suffix, tense marking (or its
  absence) on the inner verb is the only difference.
- **16.2.2 Adnominal constructions:** the noun-modifying suffixes carry real tense/aspect content
  in their own right (full cross-reference to Ch. 22.2): **-는** (action/있다-없다 verbs: present/
  simultaneous — plus a set of fixed collocations: 쉬는 시간, 먹는 물, 택시타는 곳); **-은/ㄴ**
  (descriptive verbs: present state; most action verbs: past/prior-to-main-clause; process verbs:
  present state from completion — 살찐 고양이, 잘 익은 복숭아; wearing/contact verbs: worn state —
  안경 낀 학생); **-던/-었던** (descriptive: continued-then-changed state vs. past-point state, only
  subtly distinct; action: past habit/suspended action vs. completed-action-from-retrospect — the
  book gives near-minimal pairs like 살던/살았던 집, 친구들과 만나던/만났던 까페 where -던 implies a
  repeated/ongoing past and -었던 a single completed past instance; note also that both -던 and
  -었던 collapse to a pure habitual reading whenever the verb co-occurs with **즐겨** "enjoy[ing]");
  **-을/ㄹ** (future relative to the main clause — plus fixed collocations 볼 일, 먹을 거, 잘 시간;
  and intention/conjecture uses); **-었을** (conjecture about an unverified past event; and the
  -을 때 vs. -었을 때 "when" contrast — simultaneous-with vs. completed-prior-to the main clause
  event).

### 16.3 More aspect-related auxiliary-verb constructions (p. 214-218)

A compact catalog of auxiliary-verb aspect markers, each given with its core gloss: **-기 시작하다**
"begin"; **-게 되다** / **-어지다** "become/come to" (게 되다 for a change in circumstance/
relationship, 어지다 for a gradual change in a quality); **-어 가다** "gradually, present→future"
vs. **-어 오다** "gradually, past→present" (같은 direction-of-time contrast on the same gradual-change
notion); **-고 나다** "have finished [X, then...]"; **-고 말다** "finally end up doing [often
regrettably]"; **-어 내다** "manage to complete [difficult X]"; **-어 치우다** "get rid of X
completely/dismissively"; **-어 버리다** "do X completely, to one's regret or relief" (valence-
neutral — can be relief or regret depending on context); **-어 놓다** vs. **-어 두다** (both
"complete X and keep the resulting state" — 놓다 emphasizes the completion itself, 두다 the
deliberate/purposeful retention of the result; some collocations take only one or the other: 물어뜯어
놓다 "chew up" only takes 놓다 since there's no state being purposefully preserved, while 내버려
두다 "leave alone" only takes 두다 since the point is deliberate ongoing inaction); **-어 보다**
"try [doing] X" and the related **-는/은 적이 있다/없다** "have/have no experience of X-ing" (일 can
substitute for 적) with an emphatic superlative variant **-어 본 역사가 없다** "have never in my
life X-ed" (literally "have no history of having X-ed" — a hyperbolic intensification of the plain
experiential form, worth flagging alongside the -겠 hyperboles in 16.1.9 as another register-marked
exaggeration strategy); **-곤 하다** "usually do, used to" (habitual) and **-어 버릇하다** "make a
habit of X-ing"; **-어 대다** and **-어 쌓다**, both "do X repeatedly/excessively," with a mildly
critical/exasperated coloring in the example sentences given (조르다 "pester" + 어 대다; 울다 "cry"
+ 어 쌓다).

### 17.1 Requests, suggestions, permission, and prohibition (p. 219-221)

A graded inventory of request-strength forms: **-어(라)** (bare command); **(좀) -어 줘** "please...
for me"; **-면 한다/고맙겠다/감사하겠습니다** "it would be nice if"; **(좀) -어 줄래/주시겠어요?**
"would you...for me"; **(좀) -어 주실 수 있을까요?** "would it be possible to." Suggestions:
**-는 게 어때?** "how about," **-지 그래?** "why don't you," **-을 필요/거 없다** "no need to,"
**-면 된다** "all you need is to," **-도록 해** "make sure that," **-을 것** (written instructions
only, e.g. signage: 신분증을 반드시 지참할 것). Permission: **-어도 된다/괜찮다** "may/can" —
explicitly contrasted with **-면 된다**, which the book flags as a common English-speaker mistake
when asking permission (화장실 가도 돼요? "may I go to the bathroom?" is correct; 화장실 가면
돼요? is not permission-asking, it's asking for instructions/confirmation of a required condition,
e.g. 시청가려면 여기서 좌회전 하시면 됩니다 "to get to city hall, turn left here"). Also
**-면 안 돼?** "would it not be okay if," **-을 수 있을까?** "will it be possible." Prohibition:
**-지 마** "don't," **-면 안 된다** "must not," **-어선 안 된다** "should not" (slightly more formal
than -면 안 된다), **-을 수 없다** "not allowed to."

### 17.2 Obligation, ability, and possibility (p. 222-224)

Obligation: **-어야 한다/된다** "must/have to"; **-지 않으면 안 된다** "must" (double-negative
construction); **-지 않을 수가 없다** "have no choice but to"; **-는/을 수밖에 없다** "have no
choice but to." Ability: **-을 수 있다** "can"; **못-** "cannot" (the book flags that inability is
normally expressed with 못-, reserving -을 수 없다 for prohibition/impossibility rather than
personal inability — a meaningful distinction easy for learners to blur); **-을 줄 안다/모른다**
"know how to" (skill/know-how, distinct from bare capability). Possibility: **-수(가) 있다/없다**
"there is/isn't a possibility"; **-지도 모른다** "may/might"; **-리가 없다** "cannot be, no way"
(strong denial of possibility, e.g. 그럴 리가 없어 "no way").

### 17.3 Regret, desire, and doubt (p. 224-227)

Regret: **-었어야 한다/된다** "should have"; **-을걸 (그랬다)** "I wish I had" (first-person
regret); **-지 (그랬어)** "I wish you had" (second-person reproach); **-면 -었을텐데** "would have
...if"; **-는 건데** "should have" (self-directed); **-게 아닌데** "shouldn't have." Desire:
**-고 싶다/고 싶어한다** "would like to/want" (1st person vs. 3rd person subject use, echoing the
descriptive-vs-action-verb psychological-state contrast from 15.1.2); **-었으면 좋겠다/한다** "it
would be nice if." Doubt: **-을라고?** expresses strong rhetorical doubt/incredulity (설마
지금까지 안 먹었을라고? "surely they must have eaten by now").

### 17.4 Degree (p. 225-226)

"Nearly/almost": **-을 뻔했다** "almost happened [and didn't]"; **-을락 말락 한다** "on the verge
of happening"; **-다시피 됐다** "became close to [a state]"; **-다시피 한다** "almost as if
[habitually]." "Deserving quality": **-을 만하다** "worth X-ing / good enough to X" (요즘 볼 만한
영화 "a movie worth seeing lately").

### 17.5 Evidentiality (p. 226-230)

A systematic inventory of how a speaker signals the *source* and *certainty* of a claim, organized
by increasing assertiveness:
- **17.5.1 Hearsay ("they say..."):** **-댄다, -다더라(구요), -답니다** — the speaker explicitly
  disclaims responsibility for the truth of secondhand information.
- **17.5.2 "Seems like/I think" (least assertive guesses):** **-거 같다** (by far the most common,
  colloquial default); **-듯 하다/싶다** (less common, more literary/written); **-지 싶다, -을까
  싶다**.
- **17.5.3 "Looks like/appears" (evidence-based impressions):** **-나 보다/-은가 보다** (with a
  present-tense split: action verbs take -나 보다, descriptive verbs take -은가 보다, but both
  collapse to -나 보다 in the past tense); **-어 보인다** (immediate sensory impression, descriptive
  verbs only); **-게 생겼다** (subjective judgment, often about an unwelcome forecast: 밤새우게
  생겼네요 "looks like we'll be up all night"); **-모양이다** (indirect evidence/hearsay-adjacent);
  **-겠다** (cross-referenced to 16.1.8's conjecture use).
- **17.5.4 "Almost certain/probably" (most assertive):** **-을 거다, -을텐데, -을 걸** (this last
  one specifically noted as taking a *rising intonation*).
- **17.5.5** The book provides a full cross-tabulation of all the above forms against both an action
  verb (비 오다 "rain") and a descriptive verb (아프다 "hurt") — a genuinely systematic paradigm
  worth treating as the chapter's key reference table for any evidentiality-based slang/register
  mechanics analysis later (e.g. a sci-fi conlang wanting its own evidentiality gradient modeled on
  a real precedent).

### 17.6 Special verb-endings expressing the speaker's attitude (p. 230-232)

Explicitly framed by the source as **colloquial-speech-specific** sentence-final endings — dense
register-relevant material:
- **17.6.1 Explanatory/emphatic — -는/은 거다:** an extremely common colloquial pattern with three
  distinct pragmatic effects: (a) inviting the listener into an implied unstated backstory (정말
  괜찮은 거예요? "are you REALLY alright? [because if not...]"); (b) dramatic storytelling framing,
  often narrating past events in present tense to draw the listener in (수업시간에 졸고 있는데
  선생님이 딱 보고 계시는 거야"and there was the teacher looking right at me!") — the related
  **-는/은 거 있지** variant does the same dramatic-reveal work (모두 내 얼굴만 쳐다보는 거 있죠
  "everyone was staring at me, can you believe it"); (c) making an ongoing/verifiable situation
  concrete and clear (여기서 뭐 하는 거야? "what are you doing here [right now, that I can see]").
  Related emphatic/quoting patterns: **-다는 거 아니니?** (dramatic reveal of surprising news);
  **-단/냔/잔/란 말이다, -다/냐/자/라구요, -다/냐/자/라니까, -다/냐/자/라니?** (built on the
  quoted-clause pattern, cross-referenced to 22.1, used to repeat/re-assert something already said,
  often with mounting exasperation — illustrated with a full back-and-forth dialogue example showing
  -다니까 "I told you," -라구 "I said, stop it," and -라니? "'nagging'?! [indignant echo question]").
- **17.6.2 Exclamatory and beyond** — a full set of colloquial sentence-final exclamatory particles,
  each with a distinct pragmatic flavor: **-네** (spontaneous emotional reaction to noticing
  something); **-데** (general exclamation, e.g. admiring a hat: 잘 어울리는데!); **-구나/-군요**
  (first realization, "oh, I see"); **-다** (an exclamation with *no addressee intended* — purely
  expressive, e.g. 저 강아지 너무 귀엽다! said to no one in particular); **-구만** (casually noting
  something unexpected); **-담/는담** (lightly complaining/expressing dissatisfaction — 뭘 그렇게
  꾸물거린담? "why's she dawdling so much"); **-을라** (a warning carrying endearing concern, e.g.
  to a child: 비 맞을라 "you'll get rained on"). This whole inventory of sentence-final
  attitude-markers is exactly the kind of fine-grained register/tone system a synthesized slang
  register would need its own analog of — flagged here as high-value for later mechanics work.

### 18.1 How to negate statements and questions (p. 233-236)

- **18.1.1 Short vs. long negation:** Korean has two competing negation strategies for most verbs
  — **short negation** (안/못 placed before the verb) and **long negation** (-지 않다/못하다
  suffixed to the verb). A three-way table (action verb 가다, descriptive verb 비싸다, copula
  이다) shows the copula only allows short negation, and only with 안 (spelling changes to 아니:
  책이에요 → 책이 아니에요). **This is an explicit register contrast, not free variation**: short
  negation is described as "more direct and therefore more colloquial," long negation as "less
  direct... more frequently used in formal writing." A practical wrinkle: long negation tends to
  sound more natural for verbs of 3+ syllables (아름답지 않다 rather than *안 아름답다), while short
  negation persists as the natural choice for certain very frequent multisyllable verbs regardless
  (안 좋아한다, 안 어울린다).
- **18.1.2 안 vs. 못 semantics:** 안 = "don't intend to / does not / is not" (volitional/simple
  negation); 못 = inability or "definitely not/impossible." 못 is not normally used with descriptive
  verbs, but when it is (in long negation, -지 못하다), it specifically registers **the speaker's
  dissatisfaction** with a lack of a desirable quality (똑똑하지 못하다 "she's [regrettably] not
  smart," 정직하지 못하다 "not honest"). A colloquial contraction -하지→-치 is noted for frequent
  items (똑똑치 못하다, 만만치 않다 "no easy matter"). The bare descriptive verb 못하다 itself means
  "be inferior to" (동생이 형만 못하다 "the younger brother isn't as good as the older one").
- **18.1.3 Fixed-negative-choice idioms:** a long list of expressions where the negative form is
  frozen and not freely substitutable, several genuinely slang/insult-register: 못생기다 "be
  bad-looking," 못나다 "be a fool" (이런 못난 자식 "you fool"), 되지 못하다/못되다/못돼 먹었다/
  돼먹지 못했다 (four near-synonymous insult forms all meaning roughly "be a rotten
  person/bastard" — worth flagging as a cluster of insult-register fixed forms all built on
  negated 되다/나다), 못 쓰다 "shouldn't (say/do)," 못 살다 "be poor," 맥을 못 추다 "be unable to
  resist." Also the "not X but Y" pattern (가수가 아니고/아니라 배우다) and "neither X nor Y"
  (가수도 아니고 영화배우도 아냐; 오(지)도 가(지)도 못해 "stuck, unable to move either way").
- **18.1.4 Negating complex verb constructions:** compound verb+verb sequences (먹어 보다, 좋아
  보이다) negate as a single unit at the second verb (못 먹어 봤어 / 먹어 보지 못했어); bound-noun +
  verb compounds (약하다, 깨끗하다) likewise negate as one unit; but free-standing-noun + verb
  compounds (배고프다, 축구하다) negate as **two separate units**, with 안/못 able to insert between
  the noun and the verb (배 안 고파, 축구 못 한다) — a real, testable morphological-boundary
  diagnostic (bound vs. free noun component) hiding inside ordinary negation behavior.
- **18.1.5 Negative Sino-Korean prefixes:** 금- [禁] (금연 "no smoking"), 몰- [沒] (몰염치하다 "be
  shameless"), 무- [無] (무면허 "unlicensed," 무인도 "deserted island"), 미- [未] (미혼
  "unmarried," 미성년자 "minor"), 부-/불- [不] (부적합하다 "inappropriate," 불평등하다 "unequal" —
  note the same hanja 不 surfaces as either 부- or 불- depending on the following sound), 비- [非]
  (비무장지대 "DMZ," 비경제적이다 "uneconomical"). Six distinct negative-prefix morphemes, all from
  Sino-Korean, forming a productive derivational layer distinct from native 안/못 negation.

### 18.2 How to negate commands and proposals (p. 236)

**-지 말다** is the dedicated negator for imperatives/propositive sentences (걱정하지 말아요/마
"don't worry"; 담배꽁초를 버리지 맙시다 "let's not litter cigarette butts"). 말다 is irregular and
also extends beyond pure command/proposal negation into several other patterns: -지 말아야겠다 "I
think I shouldn't," -지 말았으면 좋겠다 "I hope [it] won't," -다 말고 "in the middle of X-ing
[and stopping]," -든지 말든지 "whether or not," -을까 말까 "vacillating over whether to," -나
마나 "no use [X-ing]."

### 18.3 Negative form, but positive/emphatic meaning (p. 237-238)

Several fixed patterns are **morphologically negative but pragmatically not negating anything** —
a genuine form/function mismatch worth flagging for slang-mechanics work, since this is exactly the
kind of surface-vs-pragmatic gap slang formation likes to exploit:
- **-잖아(요)** "you know" — historically a contraction of -지 않아, but functions to seek
  agreement/confirmation, not to negate (전화 왔잖아 "there was a call, you know"); can carry an
  **exasperated, assertive tone** when the speaker is annoyed (참견하지 말라 그랬잖아 "I TOLD you to
  mind your business").
- **-어야 되는 거 아니니** "you know [you should]" — a strong reminder/reproach form, same
  negative-question-but-not-really-negative shape.
- **그렇게...-을 수가 없다** "extremely..." (그렇게 바싹 말랐을 수가 없어 = "she's WAY too skinny" —
  literally "there's no way she could be that skinny," pragmatically an intensifier).
- **얼마나...-는/은지 모른다** "extremely..." (얼마나 바빴는지 몰라요 = "I was SO busy" — literally
  "I don't know how busy I was").
- **-기 짝이 없다** "extremely... [negative conditions only]" (미안하기 짝이 없다 "I'm terribly
  sorry").
- **True double negation** (two real negatives cancelling to a positive, as in English): 없는 게
  없어요 "they have everything" (lit. "there's nothing that's missing"); 하지 않을 수 없다 "I have
  to do it"; 가지 않으면 안 돼 "I have to go."

### 18.4 Expressions that require negative verbs (p. 238-239)

A long inventory of adverbs/expressions that are **grammatically dependent on a negative verb** —
they cannot occur with an affirmative verb at all (a negative-polarity-item pattern, structurally
comparable to English "at all," "whatsoever," "any"): 전혀 "not at all," 도무지/도저히 "not
possibly," 좀처럼 "hardly ever," 통/영 "not at all/whatsoever," 여간...게 아니다 "extremely [lit.
'not ordinarily']," 이만저만...게 아니다 "to an indescribable degree," 이루 다 (말로 표현할 수
없다) "cannot possibly [describe in words]," 꼼짝 (못 하다) "can't budge," 조금도 "not even a
little," 추호도 "not in the least," 채 (끝나기도 전에) "before even," 겨우...밖에 "no more than,"
듣(지)도 보(지)도 못하다 "never heard nor seen [of]." Several of these (여간, 이만저만, 추호도) are
themselves genuinely literary/heightened register — worth flagging alongside 18.3's
negative-form-positive-meaning patterns as another place where Korean negation morphology does
pragmatic work well beyond simple truth-negation.

### 19.1 Omission of particles (p. 240)

Particles may be dropped when their information is inferable from context, most freely on -이/가,
-을/를, and -의. **This is explicitly a colloquial-speech phenomenon** — the source states particles
"should be retained in any kind of writing" since they carry the work pauses/intonation do in
speech, and demonstrates with a side-by-side sentence (마이클과 동규는... 대사관에 갔다, written,
full particles vs. 마이클하고 동규, ... 대사관 갔다, spoken, particles dropped) — a clean, explicit
register contrast baked directly into a "basic" grammar point. Even in speech, particle omission
degrades for long/multi-clause sentences, where the particles are needed for "rhythmic balance."

### 19.2 -이/가 (p. 241-244)

Primarily the subject marker, split into two uses: (a) a **neutral, unfocused** subject (commonly
omissible, especially when the referent is a person inferable from context) vs. (b) a
**focused/exclusive** subject ("this and only this," carrying high pitch, never omissible: 제가
죄송하죠 "*I'm* the one who's sorry"). -이/가 also marks several non-subject roles: the noun before
되다/아니다 (X가 Y가 되다/아니다); the direct object of 있다/없다/필요하다; the direct object of
certain psychological descriptive verbs (무서워요, 부러워요, 좋더라 taking -이/가 rather than
-을/를 — switching to an action-verb form like 무서워하다 switches the particle back to -을/를,
directly echoing 15.1.2's descriptive/action-verb contrast); focused possessors (동생이 집이 더
크다 "the YOUNGER BROTHER's house is bigger"); and emphatic negation (신경쓰고 싶지가 않아 "I
really don't want to worry about it"). A distinct **name particle -이** attaches to a Korean given
name ending in a consonant when addressing a child, close friend, or younger sibling (미선이,
석훈이) — explicitly noted as never used with foreign names.

### 19.3 -은/는 (p. 243-247)

Flagged by the source as **notoriously difficult for English speakers**. Two basic functions:
marking a **topic** (what the sentence is about) or marking **contrast**. Off the front of the
sentence, -은/는 is *always* contrastive; at the front, it's ambiguous between topic and contrast
depending on context and pitch (worked example: 공부는 성아가 잘한다 can mean either "as for
studying [topic], Sung-ah is good at it" or "STUDYING [contrastive, not other things] is what
Sung-ah is good at" — and if the noun is *not* sentence-initial, only the contrastive reading
survives). Topic-uses include stage-setting, presenting old/given information, making generic
statements, and topic-shifting. The book's summary table crisply cross-tabulates focus against both
-이/가 and -은/는: unfocused -이/가 = neutral subject, focused -이/가 = exclusive; unfocused -은/는
= topic, focused -은/는 = contrast. Contrastive -은/는 can attach (often contracted) to almost any
sentence position, not just the subject (좋긴 좋다 "it IS good [but...]," 도와는 줄게 "I WILL help
[but...]").

### 19.4 -을/를 (p. 245-249)

Primarily the direct object marker, notably including several Korean transitive-verb objects that
correspond to a prepositional phrase in English (대학을 졸업하다 "graduate FROM college," 친구를
기다리다 "wait FOR a friend"). Non-direct-object uses: destination (in place of -에); purpose of
movement; a property-describing noun (차를 외제를 사다 "bought a car, a FOREIGN one" — in place of
-로); indirect object for added exclusiveness (in place of -에게/한테); duration; quantity; and
**emphatic negation**, where -를 contracts to **-질** (다리가 움직이질 않아 "my legs won't move at
all") — the source flags this contraction as reserved for casual speech, "typically very
colloquial," even though contraction is normally a writing-avoided phenomenon (cross-referenced to
Ch. 8). A closed set of **formal/written fixed expressions** built on -을/를 is given (오늘 자정을
기해서... "as of tonight at midnight...").

### 19.5 -도 (p. 247-249)

Expresses "also/even/indeed," incompatible with -이/가 or -을/를 but stackable with most other
particles. Senses: "also" (그 영화도 봤다); "even" (밥은 커녕 물도 못 먹었어요 "I didn't even have
water" — combining with the 은/는커녕 pattern from 19.17); "indeed" (사람도 많더라 "there really
were a lot of people"); and "not only X but also Y / neither X nor Y" (놀기도 잘 놀고 공부도
열심히 해요). Several idiomatic -도 collocations shade into fixed-expression territory (벼룩이도
낯이 있지 "even a flea has shame," i.e. "have you no shame").

### 19.6 -의 (p. 249-250)

The genitive/possessive linking particle (남편의 직장동료 "husband's colleague"), also usable for
non-possessive association (연상의 여인 "an older woman [as romantic partner]"). **-의 is regularly
dropped inside compound nouns**, even in formal writing (한국문화, not *한국의문화). It must be
retained in a set of fixed formal expressions (천고마비의 계절 "the season of high sky and fat
horses [autumn]," 표현의 자유 "freedom of speech"), after another particle (자식으로서의 도리
"one's duty as a child"), and before -와/과 coordination (너와 나의 차이점 "the difference between
you and me").

### 19.7 -에 (p. 250-253)

One of the most frequent particles, centered on location in space/time. Spatial uses: static
location (학교 근처에 살아요); destination (학교에 갔다— note 뛰다/걷다 "run/walk" instead require
-까지, not -에, for a destination); inanimate recipient (화초에 물을 주다 "water the plant" — for
an *animate* recipient, -에게/한테 is required instead, cross-referenced to 19.9); abstract point
(성공은 노력에 달려있다 "success depends on effort"); and addition/enumeration. A colloquial
variant **-에다(가)** intensifies/emphasizes the recipient (차에다 갖다 놓자). Temporal/causal/
distributive uses: time/age (칠십에 돌아가셨어요 "died at 70"); cause/means (더위에 지쳤어 "worn
out BY the heat," 술에 취했다 "drunk FROM alcohol"); and per/for ratios (하루에 일 분씩 "one
minute PER day," 세 마리에 만원 "10,000 for three [fish]"). A set of fixed
preposition-like collocations follows: 에 대해서, 에 관해, 에 관한 한, 에 따라, 에 따르면, 에
비하면, 에 의하면, 에 불과하다, 에 지나지 않다, 에 있어서 — several explicitly marked
[written/formal].

### 19.8 -에서 (p. 253-254)

Marks a starting point (concrete or abstract) or the **location where an activity takes place**
(as opposed to -에's location of mere existence/arrival). The key contrast: -에 = static
existence/endpoint of motion (자리에 앉으세요 "be seated"), -에서 = the site *inside which an
activity happens* (자리에서 떠들지 마세요 "don't make noise while seated [i.e. don't DO the noise
here]"). For a handful of verbs (살다 "live," 묵다 "stay," 모이다 "gather"), -에 and -에서 are
interchangeable with negligible difference.

### 19.9 -에게(서)/한테(서) (p. 254-256)

Marks "to/from someone," contrasting with -에's "to/at a place." **-에게(서) is written/formal;
-한테(서) is colloquial** — an explicit, clean register pair, paralleling -와/과 (formal) vs.
-하고 (colloquial) in 19.11. The honorific animate-recipient form is **-께** (used, notably, only
alongside -에게 in letter-opening address lines: 김교수님께 "Dear Professor Kim"). A distinct
"telling"-verb-only particle **-더러/보고** marks an intended message recipient in colloquial
quoted speech (엄마더러 직접 오시라고 해 "tell Mom to come herself"). Adding -서 to -에게/한테
flips "to someone" into "from someone," with the direction usually resolved by context rather than
the (optional) -서 itself.

### 19.10 -(으)로 (p. 256-260)

A highly polyfunctional particle. Core senses: direction (오른쪽으로 가세요 — note -로 is required
over -에 whenever the destination isn't a precise point: 아파트로 이사갔다 is fine, *아파트에
이사갔다 is not); change/transformation (영어로 번역하다 "translate INTO English"); choice among
options (일회용으로 사자 "let's buy the disposable one"); "as (a role)" (선교사로 5년간 있었다 "was
[there] AS a missionary" — echoing X를 좋아하다-style role/identity framing); means/instrument
(젓가락으로 먹다 "eat WITH chopsticks," 카드로 지불하다 "pay BY card"); cause/source (과로로
쓰러지다 "collapse FROM overwork," 도박으로 망하다 "ruined BY gambling"); time ("변화 시시각각으로"
"minute by minute"); and manner (정식으로 인사드리다 "formally introduce"). A cluster of
**written/formal fixed collocations** is explicitly flagged: 언니로서 (in the role of), 태풍으로
인해 [written/formal], 사고로 말미암아 [written/formal], X로 하여금 Y [written/formal].

### 19.11 -와/과, -하고, -(이)랑 (p. 257-260)

Three near-synonymous coordination/accompaniment particles differing sharply in **register**:
**-와/과 is written/formal**, **-하고 is colloquial** (the pairing directly parallels -에게 vs.
-한테 in 19.9), and **-(이)랑 has an even more spoken/casual flavor** than -하고. Coordinates nouns
("and": 갈비와 빈대떡) and expresses accompaniment ("with," but also translatable as "to," "from,"
"into," or nothing at all depending on the verb: 남편하고 이혼하다 "divorce FROM one's husband,"
남자친구하고 헤어지다 "break up WITH a boyfriend"). A crucial semantic contrast is drawn between
-에게/한테 (**one-way** relationship: 남편한테 전화했어요 "I called my husband [one-directional]")
and -와/과/하고/랑 (**reciprocal** relationship: 남편하고 전화했어요 "my husband and I talked [both
ways]") — a genuinely useful grammatical diagnostic for relationship symmetry. A set of
formal-register fixed collocations built specifically on -와/과 (not the colloquial variants) is
given: -와 더불어, -와 다름이 없다, -와 마찬가지로, -와 반대로, -와 같이, -와 동시에.

### 19.12 -만, -뿐, -밖에 (p. 260-262)

Three "only/just" particles with different distributions. **-만**: general "only/just," and
separately (with time expressions) "after an interval of" (오랜만이에요, 십 년 만에 왔어요), and
sentence-finally as a conjunctive "but" (주제넘습니다만... "I may be out of line, but..."). **-뿐**:
"only," typically in the patterns X뿐이다, X뿐(만) 아니다 "not only X," X뿐더러 "not only X but
also." **-밖에**: "(nothing) but," **obligatorily paired with a negative verb**, and carrying an
implication that some expectation is unmet (맥주 한 잔밖에 못 마셔요 "I can only drink one beer [and
that's disappointing/limiting]"). The -만 vs. -밖에 contrast is pragmatic, not just syntactic:
-만 suits a *willing* limited choice, -밖에 (+ negative) suits an *unwilling/reluctant* one (건강
생각해서 한 잔만 마셨어 "I had only one, mindfully" vs. 술이 모자라서 한 잔밖에 못 마셨어 "I could
only have one because there wasn't enough"). -밖에 is required (not -만) for "all I have/all
that's left" readings; -만 is required (not -밖에) in commands/proposals, since -밖에 cannot occur
without a negative main verb.

### 19.13 -부터 (p. 262-263)

"Starting from/beginning with" — for both abstract sequence-starting-points (기초부터 확실히
다지세요 "get a firm grasp of basics FIRST") and combined with -(에)서 or -(으)로 for a starting
location (도서관에서부터, 집을 처음서부터). Contrasted with -에서, which also means "from" but
cannot express "first/since" senses that -부터 can, and is not interchangeable with -부터 except
when an endpoint is separately marked by -까지.

### 19.14 -까지 (p. 263-265)

"To/until" (endpoint in time or space: 오전 8시부터 오후 5시까지); "and even" (listing something
additional/surprising: 세탁기, 냉장고, 그리고 침대까지 새로 샀다); "even/as far as" (in a
concessive/rhetorical sense: 대학까지 졸업하고 어떻게 그렇게 무식할 수가 있어요? "how can you be
so ignorant, even after graduating college"). Unlike -조차/-마저 (19.15), -까지 is usable for both
desirable and undesirable situations.

### 19.15 -조차, -마저 (p. 264-265)

Both mean "even," similar to -까지, but **restricted to undesirable/negative situations** (unlike
-까지, which has no such restriction). Distinguished from each other: **-조차** = "even the most
basic/expected thing" (이름조차도 기억이 안 나요 "I can't even remember her NAME [the most basic
fact]"); **-마저** (like -까지) = "even the last [thing remaining]" (심지어 그는 양심마저
팔아버렸다 "he sold out even his CONSCIENCE [the last thing left]"). All three (-조차/-마저/-까지)
are interchangeable for a general undesirable situation (운동은커녕 밥 먹을 시간조차/마저/까지
없어요).

### 19.16 -(이)나 (p. 265-267)

A richly polyfunctional particle: "the best of the remaining choices" / "might as well" (빵이나
먹지 뭘 밥을 해요? "why don't we just eat bread instead" — a resigned/settling-for-less nuance);
emphasis on a quantity *more than expected* (일곱 병이나 마셨어요 "drank as many as SEVEN
bottles!"), intensified further by **-씩이나** (천 불씩이나 해요? "that expensive, a whole
$1,000?!"), which can also be used sarcastically for something surprisingly excessive regardless of
quantity (선물씩이나... "[you didn't need] a whole GIFT..."); approximation in questions (몇
명이나 돼요? "about how many are there?"); the indefinite-pronoun-forming suffix (누구나, 언제나,
아무나, 아무거나"anyone/anytime/anything at all"); and "(either) X or Y" (태권도나 합기도를
배워봐라), cross-referenced to the conjunctive -으나 in 21.1.3, with the more formal register
equivalent 또는 noted for written language.

### 19.17 Miscellaneous other particles (p. 266-268)

A closed-list roundup: **-씩** "each/apiece" (날마다 8시간씩 일합니다); **-마다** "each/every"
(다섯 시간마다 한 알씩 "one pill every five hours"); **-들** the (semantically often optional)
plural marker, obligatory alongside a demonstrative (그 사람들) unless a plural numeral is present
(그 두 학생), and — notably — attachable even to adverbs, connectives, or a sentence-final verb to
mark plurality of the subject rather than the noun itself (왜들 안 와요? "why don't you all come?,"
literally the plurality marked on "why"); **-끼리** "among/by themselves [exclusively, within a
group]" (우리끼리 얘긴데 "just between us," 가족끼리만 모이다 "just family members getting
together"); **-(이)야** "if it be [X specifically]" (닭 한 마리쯤이야 혼자 먹을 수 있지 "if it's
just one chicken, sure, I can finish it myself"); its intensified form **-(이)야말로** "indeed;
be THE one" (그 사람이야말로 우리 부서에 꼭 필요한 인물이지 "he really is indispensable"); **-은/
는커녕** "far from; let alone" (반에서 일등은커녕 10등 안에도 못 들겠다 "far from being top of the
class, I doubt I'll even be top ten" — interchangeable with 말할 것도 없고/고사하고); **-따라** "of
all times/occasions" (그날따라 사람이 너무 많았어요 "of all days, it was crowded THAT day"); and
**-깨나**, explicitly marked **[spoken/colloquial]**, "quite a bit of" often with a mildly
disapproving edge (고집깨나 세다 "quite stubborn," 돈깨나 있는 사람 "someone with a fair bit of
money [said slightly begrudgingly]").

### 20.1 Chapter 20 vocabulary — register-tagged comparison idioms (p. 269-274)

Chapter 20 is unusually rich in **explicit inline register tags** the source itself marks — exactly
the kind of annotation the coverage rule says must never be skipped. Captured here as vocabulary
rather than folded into prose, since each is a distinct fixed idiom.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 코딱지만하다 | be tiny, like a booger | descriptive verb (idiom) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 269; explicitly marked **[familiar/casual]** by the source. |
| 비까비까하다 | be neck-and-neck, evenly matched | descriptive verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 272; explicitly listed under "Spoken/colloquial expressions." |
| 그게 그거다 / 거기서 거기다 | be about the same, six of one half dozen of the other | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 272. |
| 그만그만하다 | be about the same (of ability/quality) | descriptive verb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 272. |
| 아버지를 쏙 빼다 / 빼다 박다 | be a carbon copy of (one's father) | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 274; explicitly marked **[spoken/colloquial]**. |
| 훨 | way (more), much more (contracted 훨씬) | adverb | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 273; explicitly marked **[spoken/colloquial]**. |
| 백배 (더) | 100 times more, way more | adverb (idiom) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 273; explicitly marked **[spoken/colloquial]**. |
| 한층 (더) | a level more, considerably more | adverb | formal | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 273; explicitly marked **[written/formal]** — direct register-pair with 훨/백배 above. |
| 게임이 안 되다 | be no match for, not even in the same league | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 286; explicitly marked **[spoken/colloquial]**. |
| 쨉도 안 되다 | be nowhere close (in a matchup) | idiom | slang | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 286; explicitly marked **[familiar/casual]** — from English loanword "jab" (boxing), a genuine slang coinage worth flagging for loanword-based slang mechanics. |
| 꿀리다 | have to yield/concede (to someone) | verb (idiom) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 286; explicitly marked **[male speech]** — a real gendered-register tag, rare and valuable to capture. |
| 왔다 | (something is) the best, "it's arrived" [i.e. peaked] | interjection/idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 287, 스트레스 푸는 데는 노래방이 왔다지 "nothing beats karaoke for stress relief"; explicitly marked **[spoken/colloquial]**. |
| 짱이다 | be the best, be awesome | descriptive verb (idiom) | slang | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 287; explicitly marked **[slangy]** by the source itself — one of only a small number of items in this whole book the source calls slang outright, making it a high-confidence anchor term for later slang mechanics work. |

### 20.1 How to express equality and similarity (p. 269-274)

A rich inventory of figurative/exaggerated comparison patterns: **-만하다** "be as big/small as"
(콩알만하다 "tiny as a bean"); **-만큼** "as much as" (노력한 만큼 성적을 받다 "get credit in
proportion to effort"); **-정도** "to the extent that" (인사불성이 될 정도로 마셨다 "drank to the
point of unconsciousness"); **-같다/-같이/-같은** "be/like X," productively combined with vivid
similes many of which are effectively fixed idioms (물에 빠진 생쥐 같다 "like a drenched mouse,"
살얼음판을 걷는 것 같다 "like walking on thin ice," 감쪽같다 "as good as new," 꿀 먹은 벙어리같이
"like a mute who ate honey [i.e. won't say a word]," 잠꼬대 같은 소리 "nonsense talk [lit.
sleep-talk-like]"); **-듯 하다/-듯(이)** "as if/as often as" with several proverb-like fixed forms
(거짓말을 밥 먹듯 한다 "lies as often as he eats," 돈을 물 쓰듯 쓰다 "spends money like water,"
가물에 콩 나듯 "as rare as beans sprouting in a drought," 다람쥐 쳇바퀴 돌듯 "like a squirrel on a
wheel [stuck in a rut]"); **-처럼** "like/as" (벌떼처럼 몰려들다 "swarm in like bees"). Same-ness is
expressed with 같다/똑같다/진배없다/다름없다; similarity has a genuine **register split** the
source lays out explicitly: written/formal similarity vocabulary (유사하다, 방불케 하다, 쌍벽을
이루다, 견줄 만하다, 어깨를 겨루다/나란히 하다) vs. spoken/colloquial equivalents (흡사하다,
비슷하다, 비까비까하다, 그게 그거다, 그만그만하다, 맞먹다) vs. a further set of purely idiomatic
near-synonym expressions (막상막하, 피장파장, 대동소이하다, 오십보백보, 도토리 키재기 "acorns
comparing height [i.e. a contest among equally-mediocre options]"). Resemblance in appearance gets
its own idiom set (꼭 닮다; 쏙 빼다/빼다 박다, explicitly [spoken/colloquial]). "No less than": 못지
않다, 한 치도 기울지 않다.

### 20.2 How to express differences (p. 273-276)

Basic comparatives: 더/덜 "more/less," 훨씬 (더) "much more" — with the **contracted colloquial
form 훨** and the **hyperbolic colloquial 백배 (더)** "100 times more" explicitly contrasted against
the **formal 한층 (더)** register equivalent (a clean three-way register ladder worth flagging: 더
< 훨씬(더)/훨[colloq.]/백배[colloq., hyperbolic] vs. 한층[formal]). Comparative particle -보다
"than"; the "rather X than Y" pattern -느니 (차라리)... (자유 없이 사느니 차라리 죽는 게 낫다 "I'd
rather die than live without freedom" — hyperbolic register again); 낫다 "be better" vs. 못하다 "be
not as good as" (사람이 짐승만도 못하다 "worse than a beast"); -에 비해/비하면 "compared to."
A large idiom cluster for **"can't compare/beyond comparison/no match"**: 비교가 안 되다, X에 댈
게 아니다, 상대/게임/쨉이 안 되다 (register-graded as shown in the vocabulary table above),
어림도 없다, 이상형 근처도 못 가다, 저리가라다/아무것도 아니다, 뺨치다 "put to shame [lit. slap
the cheek of]." "Be inferior to": 아직 멀었다, 한참 밀리다, 기울다/빠지다, 딸리다, and the
male-speech-tagged 꿀리다 (see vocabulary table).

### 20.3 How to express superlatives (p. 274-275)

The -est: 제일/가장 + adjective (가장 아름다운 산 "the most beautiful mountain," 가장 explicitly
tagged [written/formal] in the source's own example). Two superlative-forming prefixes: **최-** 最
(Sino-Korean, productive with many Sino-Korean roots: 최신유행, 최대의 효과, 최악의 경우) and
**맨-** (native Korean, combining with a few location/sequence nouns: 맨 처음, 맨 나중, 맨 아래, 맨
오른쪽) — a clean native-vs-Sino-Korean superlative-affix contrast structurally parallel to the
particle-choice contrasts seen elsewhere in the book. A rich set of **indirect superlative idioms**
follows, escalating toward outright slang by the chapter's end: 누구보다도 성실하다, 타의 추종을
불허하다 "brook no rival," 둘째가라면 서럽다 "would be offended to be called second," 따라올
자가 없다, 독보적인 존재, 꽃중의 꽃, 둘도 없는 친구, 그만이다 "is simply the best," and finally
왔다/짱이다 (see vocabulary table) — the chapter's own progression from formal written idiom
through spoken idiom down to explicit slang is itself a small worked example of a register
gradient, useful groundwork for later slang-mechanics analysis.

### 20.4 How to express proportions and gradation (p. 275)

**-에 따라** "in proportion to/accordingly" (능력에 따라 대우를 받는다 "treated according to
ability"). **(-면) -을수록 (더)** "the more..., the more..." (생각하면 생각할수록 약이 올라요 "the
more I think about it, the more exasperated I get") — a fully productive correlative-comparative
construction, structurally parallel to English "the X-er, the Y-er."

### 21.0 Chapter 21 vocabulary — idiom/register highlights (p. 276-310)

Chapter 21 is almost entirely conjunctive-suffix morphology (dozens of connectives, each a
grammatical morpheme rather than a lexical item), so most of the chapter's genuine "vocabulary" is
the large stock of **body/hyperbole idioms** it uses as worked examples — several are distinctly
colloquial/slangy fixed forms worth capturing directly.

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| -(이)고 나발이고 | "and whatever [dismissively]" | conjunctive idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 288; explicitly marked **[familiar/casual]**. |
| -(이)랄지 | "or whatever, say" | conjunctive idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 290; explicitly marked **[spoken/colloquial]**. |
| 손이 발이 되도록 (빌다) | beg abjectly ("until hands become feet") | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 292; one of a cluster of body-part hyperbole idioms built on the -게/-도록 "to the point that" pattern (also 코가 비뚤어지게 마셨다 "drank till the nose twisted," 눈이 빠지게 기다렸다 "waited till eyes popped out," 뼈 빠지게 일했다 "worked to the bone," 귀에 못이 박히다 "said till a nail's driven into the ear," 혀가 닳도록 "till the tongue wore out"). |
| -어 봤자 | "even if [X], no use" | conjunctive idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 308; explicitly marked **[spoken/colloquial]**; source's own idiom-in-idiom example: 뛰어봤자 벼룩이죠 "no matter how far he jumps, he's still just a flea." |
| -거늘 | "when even X... [rhetorical]" | conjunctive | literary | — | contemporary (source published 2008) | — | archaic/literary register | grammar_reference | n/a | n/a | p. 309; explicitly marked **[literary/old-fashioned]** — a genuinely archaic-register connective still functional in rhetorical/moralizing speech. |
| 손에 장을 지지다 | "I'd be a monkey's uncle [if that were true]" | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 305, a vivid self-deprecating wager idiom (literally "I'd fry soy sauce in my hand"). |

### 21.1 Combination of equal-status clauses (p. 276-280)

Register is a running theme throughout this coordination-conjunctive section: **-고** (descriptive
verbs, neutral "and") vs. **-(으)며** [explicitly formal/written]. A family of "and whatever
else"/enumeration patterns escalates in casualness: -(이)고...-(이)고 (neutral), -(이)고
나발이고 [familiar/casual, dismissive], -(이)고 뭐고 / -(이)다 뭐다 / -(이)며...-(이)며 (roughly
neutral-colloquial), -(이)니...-(이)니, -느니...-느니 (attaches to the quoted-report ending
-다/냐/라/자, cross-referencing Ch. 22.1), -(으)락...-(으)락. "Or"-coordination: -거나; -(으)나
(자나 깨나 "whether asleep or awake"); -든가; -든(지); -다든지; **-(이)랄지** [spoken/colloquial];
-(이)니; -(이)랑. "Not only...but also": -도...-고...-도; -을 뿐더러/뿐(만) 아니라; -거니와/
(으)려니와; -만...-게 아니라; and the fixed pair (-이)자/(-이)요 ("both X and Y," 시인이요
학자다 "she's both a poet and a scholar").

### 21.2 Combination of unequal-status clauses (p. 291-310)

A long catalog of subordinating conjunctive suffixes, organized by semantic function — the sheer
number of distinct forms per function (often 3-5 near-synonyms differing mainly in register or a
fine shade of meaning) is itself the chapter's key takeaway, directly relevant to any slang-register
modeling that wants a comparably dense connective system:

- **21.2.1 Background:** -는데/은데 (draw listener interest / set up an inference, extremely
  common in speech); -니까/-었더니 (discovery, first-person-oriented, -었더니 for states not
  self-caused); -은 즉, -건대 (formal reporting/asserting).
- **21.2.2 Simultaneity:** -(으)면서 (shared-subject "while," -으며 as the less common/less
  colloquial variant); -을 때/-을 적에 "when"; -동안(에)/-사이(에) "during" (동안 = any duration,
  사이 = typically brief); -중에/-도중에 "in the middle of" (도중에 emphasizes interruption); -어서
  (age/time-point framing, e.g. 젊어서는... "back when [I/she] was young"); **-시** [explicitly
  written/formal, attaches to Sino-Korean nouns — safety-signage register: 도난 사고 발생 시 "in
  the event of theft"].
- **21.2.3 Sequentiality:** -고 (simple sequence) vs. **-어(서)** (overlapping sequence sharing an
  object/location/participant — a genuinely non-trivial grammatical distinction the book works
  through with minimal pairs: 도서관에 가고 친구 만났어 "went to the library AND [separately] met a
  friend" vs. 도서관에 가서 친구 만났어 "went to the library AND MET the friend THERE"; -어서 can
  colloquially expand to -어 가지고/갖고); -어다(가) (object carried from one place to another);
  -자마자/-기가 무섭게 "as soon as" (the latter more vivid: "before the fear even settled"); -는
  즉시/-는 대로 "immediately upon"; -는 순간 "the moment that"; -다(가) (shift/change mid-action);
  -었다(가) (shift after completing an action); -다...-다 하다 (repeated alternation, e.g. 왔다
  갔다 하다 "go back and forth").
- **21.2.4 Before/after/until:** -기 (직)전 "just before"; -은 다음/-은 후/-은 뒤 "after," with an
  explicit **three-way register note**: 다음 is the most common in speech, 후 sounds formal, 뒤 is
  typically used in weather forecasts/recipes; -을 때까지 "until"; -기까지 "up to the point of
  [achieving something, implying great effort]."
- **21.2.5 Cause/reason:** -어서 and -니까, contrasted at length — both interchangeable for a
  straightforward causal link, but only -니까 is usable when the reason justifies a
  command/proposal or is discovered spontaneously by the speaker, while only -어서 suits a
  completely established/expected causal relation and appears in fixed courtesy expressions (늦어서
  죄송합니다 "sorry for being late"). Also -기 때문에 (strong focus on the reason, cannot precede a
  command); -기에/-길래 (-길래 more colloquial); -어 가지고/갖고 and -는 바람에 (an unexpected
  negative event as the cause); **-(으)므로** [explicitly formal/written, seen on award
  certificates]; -느라(고) ("busy doing X [as the reason for a side effect]"); -다고 (quoted-reason
  framing); -을까봐 "for fear that."
- **21.2.6 Intention/purpose:** -(으)려고 (with casual contracted variants -을려고/-을라고,
  cross-referenced to Ch. 8.3); -(으)러 (must be followed by a verb of coming/going, except with
  뭐 하러); **-기 위하여/위해** [formal/written]; **-고자** [formal/written]; **-차** [formal/
  written, attaches to Sino-Korean nouns]; -을까 한다 "thinking about doing"; -을까 보다 (similar);
  -을 겸 "for the dual purpose of"; -을 생각/-을 작정/-을 셈 "planning to."
- **21.2.7 Purpose/result:** -게 vs. -도록 (near-interchangeable, -도록 slightly more formal;
  cross-referenced to 10.4.3 and 17.1.2) — the "result" use is illustrated entirely with **fixed
  hyperbolic body-idiom expressions** (see vocabulary table above), a genuinely productive
  "verb-until-body-part-does-something-extreme" intensification template worth flagging for
  hyperbole-based slang mechanics.
- **21.2.8 Condition:** -(으)면 "if"; -(으)면...-을텐데/(으)련만 "would have, if only"; -었더라면/
  -었던들 "if [X] had happened" (counterfactual); -다면 "if [it were the case that]"; -거든 (used
  with a command/proposal); -어야(만) "only if"; -는 한 "as long as"; -을 경우 "in case."
- **21.2.9 Concession ("even if/though"):** -어도 (-이라도 for the copula); -더라도/-을지라도; -고도;
  -어서라도 "even if it means [doing something extra]"; -는데도/은데도, -음에도 (불구하고) "in
  spite of"; -어야(rhetorical "even if X, how much could it really be?" — 멀어야 얼마나 멀겠어요?);
  **-어 봤자** [spoken/colloquial, see vocabulary table]; -은들 (rhetorical, similar force);
  -기로서니; -을망정/-을지언정 "even if it means [doing something drastic]"; -(으)나마 "though only
  [a little]"; -(으)면...-었지 (defiant "even if X, so be it" pattern); **-거늘** [literary/
  old-fashioned, see vocabulary table].
- **21.2.10 Contrast:** -지만 "but"; **-(으)나** [formal/written variant of -지만]; -는데/은데
  (mild implicit contrast); -건만 (similar, more literary-leaning per its examples); -(으)면서
  "while, at the same time [contrastively]"; -되 "may X, but..."; -는 게 (regret/excuse framing:
  "meant to X, but..."); **-는/은 반면에** [formal/written]; **-것과는 달리, -것과는 대조적으로**
  [formal/written].

### 22.0 Chapter 22 vocabulary — idioms and special bound nouns (p. 311-329)

| Term | Gloss | Part of Speech | Usage Tier | Weight/Frequency | Attested Era | Attested Region | Geographic Scope | Source Type | Transcription Confidence | Vision Reading Confidence | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 뭐니 뭐니해도 | "whatever anyone says," "say what you will" | idiom (fixed direct quote) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 299. |
| 이래라 저래라 (하다) | be bossy, order people around ("do this, do that") | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 299. |
| 나 몰라라 하다 | act like it's none of one's business | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 299. |
| 이왕 온 김에 | "now that we're here / while we're at it" | fixed pattern (bound noun 김) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 322; 김 is one of several semantically-vague bound nouns (에 that combine with adnominal clauses to form idiom-adjacent grammatical patterns. |
| 굶어 죽으란 법은 없다 | "we won't starve" (things will work out) | idiom (bound noun 법) | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 322. |
| 난다 긴다 하는 사람 | an extremely competent/high-flying person | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 324, literally "a person who flies and crawls [does everything impressively]." |
| 내노라하는 집안 | an influential/prominent family | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 324. |
| 하늘에 별따기 | (be as hard as) "picking a star from the sky," i.e. impossible | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 328. |
| 땅짚고 헤엄치기 | "a piece of cake" (lit. swimming while touching the ground) | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 328. |
| 옆구리 찔러 절받기 | fishing for compliments (forcing someone to flatter you) | idiom | colloquial | — | contemporary (source published 2008) | — | — | grammar_reference | n/a | n/a | p. 328, synonym 엎드려 절받기 also given. |

### 22.1 Quoted/reported clauses (p. 299-307)

**Direct quotes** use -하고 (onomatopoeia, or speech/thought generally) or -라고 (speech/thought),
with several quoted fixed expressions given (뭐니 뭐니해도, 이래라 저래라 하다, 나 몰라라 하다 —
see vocabulary table). **Indirect quotes** use a dedicated **report style** distinct from both plain
written style and casual speech style — its own paradigm, differing from casual speech in two
systematic ways: questions allow only -냐 (not -니), and commands use -(으)라 (not -어/아라). The
book gives a full conjugation table for how every original-sentence style (합니다/해요/해/한다,
statement/question/command/proposal) collapses into this single report style, with -었 always
preserved but -겠/-을 freely alternating. **-고 했다** marks written/formal/neutral reported speech;
**(-고) 그랬다** marks spoken/colloquial reported speech — a direct register pair. A special
sub-rule governs quoting the verb **주다** "give/do for": when the requester is also the beneficiary,
주다-commands are quoted as **주십사(고)** (honorific) or **달라고** (plain) rather than the expected
주라고; when the beneficiary is a third party, ordinary 주라(고) is used — a genuine
benefactive-alignment distinction hiding inside quotation grammar. **22.1.4** notes indirect quotes
can be followed by any saying/thinking verb (우기다 "insist," 맹세하다 "vow," 신신당부하다
"repeatedly implore," 재촉하다 "press/rush") or even directly by another clause. **22.1.5** covers
the highly productive **colloquial quotative contraction** (-ㄴ다고 하- / -ㄴ다고 그러- collapsing
into a single suffix per speech style: 간다ㅂ니다→간답니다, 간다ㄴ다→간단다, etc.) — this reduced
form conveys hearsay without needing to name the source, and the emphatic variant **-단다/(이)란다**
means "I'm telling you / you know" (어제는... 잠만 잤단다). This reduced quotative form only works
for the speaker's own report — relaying someone else's request to a third party still requires an
explicit quoting verb. **22.1.6** notes a quote can be truncated to bare -고 for confirmation
questions (언제 오신다고(요)? "sorry, when did you say you're coming?") and that quotes commonly
feed directly into a conjunctive suffix, e.g. **-다면서/(이)라면서** "I heard that...,right?" for
confirming secondhand information.

### 22.2 Adnominal clauses (p. 308-312)

Adnominal (noun-modifying) clauses always precede the noun they describe, however long, and a
single noun can carry more than one adnominal clause. **22.2.1** classifies adnominal-clause-taking
nouns by type: ordinary nouns (no English-preposition equivalent survives in the Korean structure:
비밀을 털어 놓을 친구 "a friend [to whom] one can confide secrets"); general-class nouns (거/것 for
a concrete thing, 일 for an abstract thing, 데/곳 for a place — 곳 noted as more formal than 데; 거/것
itself is genuinely ambiguous between "a concrete thing" and "the fact that," per the book's own
minimal-pair example); summarizing/classifying nouns (게 "the fact/habit of," 확률 "probability,"
경향 "tendency," 점 "point/aspect"); result nouns (소리 "sound of," 냄새 "smell of," 자국 "mark/scar
from"); and a rich set of **special (mostly bound) nouns** whose meaning the book itself flags as
"often difficult to identify," each locking into its own idiom-adjacent construction: 김 ("while
[doing something] anyway"), 대로 ("just as/according to"), 대신 ("instead of"), 따름 ("nothing but,
merely"), 마당 ("given the situation that..."), 무렵 ("around the time of"), 바 ("that which; the
matter of," in formal 들리는 바에 의하면/말씀드린 바와 같이), 법 ("the rule/reason that," 굶어
죽으란 법은 없다, see vocabulary table), 족족 ("every single time"), 지 ("since [an event]"), 지경
("to the point of"), 참 ("just about to / right when"), 채 ("with X still in a state, e.g. clothed"),
척/체 ("pretending to"), 턱 ("[no] reason to"), 통 ("amid the commotion of"). **22.2.2** covers
adnominal clauses built on a preceding quote (사실, 소문, 말, 소리 + quoted content + adnominal
suffix) — used to frame something as fact, rumor, unfulfilled promise, advice, or shocking news, and
also to quote a proverb (cross-referenced to 12.1.4) or add rhetorical emphasis (그 사람 만나기
싫단 말야 "I'm telling you I don't want to meet him"). A closed set of quote-derived fixed
expressions closes the section: 이렇다 할 직업이 없다, 하면 된다는 신념, 난다 긴다 하는 사람, 내노라
하는 집안 (see vocabulary table).

### 22.3 -지 clauses (p. 312-315)

**-지 clauses** (adnominal suffix + -지) express embedded questions/uncertainty, typically followed
by 알다/모르다/물어보다. **22.3.1** works through the full paradigm across action verbs, descriptive
verbs, and the copula, across every tense/aspect combination (-는지/-았는지/-았었는지/-을지/
-았을지, plus the more literary -(었)던지 for a strong "so...that" reading — 어찌나/얼마나...-던지
"so much that..." — and -지도 모른다 "might be possible," cross-referenced to 17.2.3). **22.3.2**
shows -지 clauses feeding into verbs beyond just know/not-know (맞추다 "guess," 기억나다
"remember," 조사하다 "investigate," 망설이다 "hesitate"), sometimes with the following verb dropped
entirely to form a gentle indirect question (요즘 어떻게 지내시는지요? "how are you these days?"),
and combining with particle phrases like -에 대해(서)/관해(서). -지 can alternate with **-줄** when
the following verb is specifically 알다/모르다 (몇 살인지/몇 살인줄 알아요?) — and critically, 알다
after a -지 clause is genuinely **ambiguous between "know" and "think"** (여행간지 알고 있었어 "I
knew you'd gone on a trip" vs. 여행간지 알았는데 집에 있었네 "I THOUGHT you'd gone, but you were
home" — the same surface form supporting both a factive and a non-factive reading, cross-referenced
back to 16.1.2's note on this same ambiguity).

### 22.4 Nominalization (p. 315-317)

Two competing nominalizing suffixes, split by **register**: **-음/-ㅁ** (formal/written flavor,
used for abstract propositions or completed actions/states: 소중함, 무죄임이 판명됐다) is the
default for **abbreviated notice-board/brochure/formal-letter-closing style** (연령제한 없음 "no
age restriction," 가정교사 구함 "tutor wanted," 서하늘 올림 "respectfully, [name]" as a letter
closing) — several -음 constructions can alternate with a more colloquial -거/것-based adnominal
paraphrase (그 사람이 무죄임이 판명됐다 → 그 사람이 무죄인 것이 판명됐다). **-기** (more common in
colloquial Korean) nominalizes an act/fact while retaining its actional/stative feel, and anchors a
large stock of fixed collocations and idioms, several proverb-like (하늘에 별따기, 땅짚고 헤엄치기,
옆구리 찔러 절받기 — see vocabulary table; 지각하기 일쑤다 "is always tardy," 생각하기 나름이다 "it
depends how you think about it"). Like -음, some -기 nominalizations can be replaced by a -거/것
adnominal paraphrase with no meaning change (놀기가 어렵다 ↔ 노는 게 어렵다), but **not all** — the
book closes the entire grammar section with a minimal-pair set showing -기 and -는 것 diverging in
subtle but real ways (고기가 먹기(가) 좋다 "this meat is easy to eat" vs. 고기 먹는 게 좋다 "I like
eating meat [as an activity]" — a different claim entirely) and cases where only one of the two
forms is grammatical at all (비오기(가) 쉬워 "it's likely to rain" has no -는 것 counterpart; 걸어
가는 게 낫겠다 "better to walk" has no -기 counterpart) — underscoring, as a fitting close to the
whole grammar half of the book, that Korean's two nominalization strategies are genuinely
non-interchangeable general-purpose tools, not free stylistic variants.

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.

---

## Coverage status of this file

**Complete.** This file covers the entire assigned range: PDF pages 171-329 (Chapter 13.3.1
continued through the end of Chapter 22, the book's final grammar chapter). PDF pages 330-337
(English index, Korean index) are reference apparatus only and were not extracted, per the coverage
rule — an index entry is a pointer into the book's own text, not itself grammar/vocabulary content.
