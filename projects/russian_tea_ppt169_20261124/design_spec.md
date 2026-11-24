<!-- ppt-master-schema: design-spec/v1 -->
# Russian Tea Culture - Design Spec

## I. Project Information

| Item | Value |
| --- | --- |
| Project Name | russian_tea_ppt169_20261124 (러시아의 차 문화 / Чайная культура России) |
| Canvas Format | PPT 16:9 (1280×720) |
| Page Count | 8 |
| Primary Language | ko |
| Target Audience | Professor and classmates in a Korean university class; Korean-speaking, little prior knowledge of Russia |
| Communication Intent | Introduce Russian tea culture — history, what tea is drunk, the samovar, tea as communication — with slides supporting a live spoken talk rather than replacing it |
| Desired Audience Outcome | Listeners remember: tea came via China and Mongolia (1638); Russians drink black tea with jam, lemon, honey; the samovar keeps water hot, so tea time is long; «Давай попьём чаю» means "let's meet and talk" |
| Core Message / Ask / Action | In Russia a cup of tea is a reason to meet and become closer |
| Delivery Context | Presenter-led live talk in a university classroom, shown from PowerPoint on a Windows PC; a video about the samovar is shown at slide 5 (inserted later by the presenter or dropped) |
| Artifact Afterlife | Presenter edits the PPTX herself afterwards; may submit it to the professor |
| Reading Mode | presentation |
| Content Strategy | Slides carry short Korean phrases and keywords condensed from the presenter's script, with Russian words as accents (Самовар, Тула, «Давай попьём чаю»); facts only from the script; the full Korean script goes verbatim into speaker notes |
| Design Style | Direction 1 "Folk classic" — cream field, cherry-red and gold, Khokhloma/Zhostovo ornament bands and corners, symmetric festive compositions, native vector still-life illustrations |
| AI Image Acquisition Path | not applicable (first version uses native vector illustrations; AI or user photos may replace them in a later revision) |
| Generation Mode | continuous |
| Spec Refinement | disabled |
| Speaker Notes | enabled — final Stage-2 proactive policy (presenter's Korean script, verbatim) |
| Custom Animations | disabled — final Stage-2 proactive policy (page transition fade only) |
| Narration Audio | disabled — workflow default |
| Created Date | 2026-11-24 |

## II. Canvas Specification

| Property | Value |
| --- | --- |
| Format | PPT 16:9 |
| Dimensions | 1280 × 720 |
| viewBox | `0 0 1280 720` |
| Margins | 64 px sides (inside ornament bands), 56 px top and bottom |
| Content Area | x 64–1216, y 56–664 |

## III. Visual Theme

### Theme Style

- **Mode**: custom
- **Mode References**: narrative
- **Mode Behavior**: A gentle story arc from origin (how tea arrived) through everyday practice and the samovar ritual to the human meaning (hospitality, «Давай попьём чаю»), closing on the takeaway that tea brings people together; titles are short Korean beats, one idea per slide, explanation carried by the presenter and notes.
- **Visual style**: custom
- **Visual Style Behavior**: Russian folk-art festive classic — warm cream paper field framed by cherry-red ornament bands or corner flourishes in gold (Khokhloma berries, leaves, scroll vines drawn as native vector shapes); symmetric or calmly balanced compositions with generous whitespace; serif Korean titles in cherry red with small gold letter-spaced Russian kickers; flat vector still-life illustrations (brass samovar, porcelain cup and saucer, baranki, jam jar, lemon) in gouache-like flat fills with gold highlights; thin gold rules with a centred bead as dividers; no photographic realism, no glossy effects, at most a soft paper-tone shadow under objects.
- **Theme**: 러시아의 차 문화 as a festive folk tea table
- **Tone**: warm, welcoming, festive, scholarly-clear

### Color Scheme

| Role | HEX | Purpose |
| --- | --- | --- |
| Background | #FBF6EC | Cream paper field of every page |
| Secondary background | #F3E7D3 | Panels, table header band, illustration ground shadows |
| Primary | #8E1B24 | Titles, ornament bands, key numbers |
| Accent | #C79A3B | Gold ornament, rules, kickers, highlights |
| Secondary accent | #1F1A17 | Black-lacquer ornament details, strong contrast marks |
| Body text | #2B2220 | Body copy |
| Secondary text | #6E5E54 | Captions, annotations, Russian glosses |
| Divider | #E2D3B8 | Hairlines, table rules, panel borders |

## IV. Typography System

### Font Plan

| Role | Character (Reference) | Primary | English if non-English | Fallback tail |
| --- | --- | --- | --- | --- |
| Title | Korean serif (myeongjo) with classic Latin serif | Batang | Georgia | serif |
| Body | Clean Korean sans with humanist Latin sans | Malgun Gothic | Segoe UI | sans-serif |
| Display | Korean serif with lining-figure Latin serif for hero numerals | Batang | Times New Roman | serif |

- **Title stack**: Batang, Georgia, serif
- **Body stack**: Malgun Gothic, Segoe UI, sans-serif
- **Display stack**: Batang, Times New Roman, serif

### Font Size Hierarchy

| Purpose | Anchor Size (px) |
| --- | ---: |
| Body | 32 |
| Title | 56 |
| Subtitle | 40 |
| Annotation | 24 |
| Display | 104 |
| Kicker | 22 |
| Footnote | 18 |

- **Role rationale**: Display covers the cover title and hero numerals (1638, 18–19) and uses Times New Roman for lining figures (Georgia sets old-style figures); Kicker is the recurring small gold letter-spaced Russian label above titles; Footnote is the page number.

## V. Layout Principles

### Deck-wide Direction

- **Hierarchy direction**: Small gold Russian kicker → large cherry-red Korean title → one illustration or one structured visual → few short keyword lines
- **Composition tendency**: Calm, balanced halves (text side + illustration side) or centred focal compositions; one focal visual per page; ornament frames the page, never crowds content
- **Cross-page continuity**: Recurring Khokhloma ornament motif (bands on cover/closing, corner flourishes on content pages), gold bead divider under titles, page number at bottom centre; the samovar recurs as the deck's identity object
- **Spacing posture**: Open; breathing and anchor pages dominate, one denser page (P04 table)
- **Spacing anchors**: page margin 64 px; block gap 32 px; column gutter 48 px; corner radius 16 px; body leading 1.45

## VI. Icon Usage Specification

- **Primary bundled library**: none

| Icon Path | Suitable Scenarios |
| --- | --- |

## VII. Visualization Reference List

| Page | Family | Template | Usage |
| --- | --- | --- | --- |
| P04 | table | record_table | When Russians drink what, and what they add — a small editable record grid |

## VIII. Image Resource List

| Filename | Dimensions | Ratio | Purpose | Type | Image pattern | Crop Policy | Acquire Via | Status | Reference | text_policy | page_role |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

## IX. Content Outline

### Part 1: Opening

#### Slide 01 - Cover

- **Audience move**: Unaware of the topic → curious about Russian tea as more than a drink
- **Relationships**: none
- **Composition**: Text column left (kicker, two-line display title, gold divider, name); samovar still-life with cup and baranki right; cherry ornament bands on both side edges
- **Cover impact**: Hook — the samovar tea table as the image of Russian hospitality, with the line 차는 단순한 음료가 아닙니다
- **Title**: 러시아의 차 문화
- **Core message**: Russian tea culture, presented by 추빌리나 알렉산드라
- **Content**: Kicker ЧАЙНАЯ КУЛЬТУРА РОССИИ · Title 러시아의 차 문화 · Hook 차는 단순한 음료가 아닙니다 · Name 추빌리나 알렉산드라
- **Motion suggestion**: The samovar continues as the identity object on P05 (Morph candidate)

#### Slide 02 - Contents

- **Audience move**: No map of the talk → knows the five steps ahead
- **Relationships**: order — 역사 → 어떤 차 → 사모바르 → 소통과 환대 → 구소련 국가들
- **Composition**: Five numbered steps in one calm row or column, each with a small folk motif; title at top
- **Title**: 목차
- **Core message**: The talk moves from history to the meaning of tea between people
- **Content**: 01 러시아 차 문화의 역사 · 02 어떤 차를 마실까? · 03 사모바르와 전통 · 04 차를 통한 소통과 환대 · 05 구소련 국가들의 차 문화

### Part 2: History and practice

#### Slide 03 - History

- **Audience move**: Assumes tea is native to Russia → sees it arrived from China and Mongolia and spread from the rich to everyone
- **Relationships**: order — 중국·몽골 → 1638 gift from Altyn Khan to the tsar → expensive drink for the rich → trade develops → XVIII–XIX centuries spread to ordinary people → everyday drink
- **Composition**: Horizontal timeline with three stations; 1638 as a hero numeral
- **Title**: 러시아 차 문화의 역사
- **Core message**: Tea came through China and Mongolia and became an everyday drink
- **Content**: 중국·몽골을 통해 · 1638년 — 알틴 칸 → 바실리 스타르코프 → 차르 · 처음: 비싼 음료, 부유한 사람들 · 18–19세기: 일반 사람들에게 · 특별한 음료 → 일상적인 음료

#### Slide 04 - What tea Russians drink

- **Audience move**: Does not know Russian tea habits → can name black tea, its time of day, and its companions
- **Relationships**: contrast — morning coffee vs afternoon/after-meal tea; membership — sugar, lemon, honey, jam as additions; link — cold → hot tea with raspberry jam, honey, lemon
- **Composition**: Small editable table left; illustrated cues (cup of black tea, lemon, honey, jam jar) right; a small highlighted card for the cold remedy
- **Title**: 러시아 사람들은 어떤 차를 마실까?
- **Core message**: Black tea is the everyday favourite, drunk after meals with jam, lemon or honey
- **Content**: Table rows — 아침: 커피 / 오후·식사 후: 차 / 가장 인기: 홍차 (녹차·허브차도) / 함께: 설탕·레몬·꿀·잼 · Card — 감기에 걸렸을 때: 라즈베리 잼·꿀·레몬을 넣은 따뜻한 차
- **Visualization**: tea-habits table (table/record_table) — columns 언제 / 무엇을; rows as in Content
- **Native-ready**: tea-habits=yes

### Part 3: The samovar

#### Slide 05 - Samovar

- **Audience move**: Has never seen a samovar → understands what it does and why it made tea time long
- **Relationships**: link — samovar keeps water hot → people keep drinking → long conversations; order — Ural (early records) → Tula (famous production); membership — strong brew (заварка) + hot water from samovar = adjustable strength
- **Composition**: Large samovar illustration as focal; short definition beside it; a small formula strip 진한 차 + 뜨거운 물; a framed video placeholder area labelled for the presenter to replace or delete
- **Title**: 사모바르와 전통적인 차 문화
- **Core message**: The samovar keeps water hot for a long time, so tea time becomes long conversation
- **Content**: Kicker САМОВАР · 물을 끓이고 오랫동안 뜨겁게 유지하는 기구 · 우랄 → 툴라 (Тула) · 진한 차 + 뜨거운 물 = 농도 조절 · 오래 마시며 오래 이야기 · Video frame: 영상 — 사모바르는 어떻게 작동할까?
- **Motion suggestion**: Samovar continues from P01 as the identity object (Morph candidate)

### Part 4: Tea between people

#### Slide 06 - Communication and hospitality

- **Audience move**: Sees tea as a drink → sees it as an invitation to meet
- **Relationships**: link — guest arrives → tea with treats (cookies, bread, jam, baranki) → welcome; link — «Давай попьём чаю» → 차 한잔하자 → let's meet and talk
- **Composition**: Hero quote «Давай попьём чаю» large in the title serif with Korean meaning beneath; small table still-life (baranki, jam, cups) as supporting visual
- **Title**: 차를 통한 소통과 환대
- **Core message**: Offering tea means welcoming someone and inviting conversation
- **Content**: 손님이 오면 → 차 + 과자·빵·잼·바란키 · 서두르지 않는 시간 · Quote «Давай попьём чаю» = "차 한잔하자" → 만나서 이야기하자

#### Slide 07 - Former USSR countries

- **Audience move**: Thinks this is uniquely Russian → sees a shared tea culture across the former USSR with local differences
- **Relationships**: membership — many former USSR countries share tea in daily life and hospitality; contrast — ways and traditions differ; overlap — gathering and talking over tea is common
- **Composition**: Breathing page — a ring of several abstract cups around one central samovar or table, one short statement
- **Title**: 구소련 국가들의 차 문화
- **Core message**: Tea culture is shared across many former USSR countries, though traditions differ
- **Content**: 구소련의 여러 나라에서도 차는 일상과 환대의 중심 · 방법과 전통은 나라마다 다름 · 공통점: 함께 모여 이야기하는 시간

#### Slide 08 - Conclusion

- **Audience move**: Has heard the parts → holds one takeaway about tea and closeness
- **Relationships**: membership — three conclusions: 역사, 일상, 소통; link — they lead to the closing message
- **Composition**: Three small medallions (history, everyday, communication) above one centred takeaway line; ornament bands echo the cover; 감사합니다 as the final line
- **Closing impact**: Takeaway — 러시아에서 차 한잔은 사람들을 만나고 가까워지는 기회
- **Title**: 마무리
- **Core message**: In Russia, a cup of tea is a chance to meet and become closer
- **Content**: 역사 — 오랜 시간에 걸쳐 · 일상 — 매일의 음료 · 소통 — 함께 보내는 시간 · Takeaway 차 한잔 = 가까워지는 기회 · 감사합니다

## X. Speaker Notes Requirements

- **Generation**: enabled
- **Filename**: match each SVG filename under `notes/`
- **Content**: Source sources/russian_tea_presentation.md — the presenter's Korean script, one segment per slide; preserve verbatim (Korean text only; the Russian translation is not copied)
- **Total duration**: about 6–7 minutes
- **Notes style**: conversational, presenter's own words
- **Presentation purpose**: Introduce Russian tea culture to a Korean university class with slides supporting the live talk
