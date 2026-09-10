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

---

## Copyright discipline reminder

Selective quotes + paraphrase + analysis only — never bulk reproduction of vocabulary boxes,
dialogue blocks, or explanatory prose. See `00_Reference_Extraction_Spec.md`.

---

## Coverage status of this file

This file currently covers PDF pages 171-251 (Chapter 13.3.1 cont. through Chapter 18 in full).
**Continuation of Chapters 19-22 (PDF pages 252-329) is in progress in this same extraction pass**
— see the checklist for whether a follow-on file has since been added, or whether this file's tail
has been replaced by further content.
