<!-- ppt-master-schema: design-spec/v1 -->
# Russian Tea Culture - Design Spec

## I. Project Information

| Item | Value |
| --- | --- |
| Project Name | russian_tea_ppt169_20261124 (러시아의 차 문화 / Чайная культура России) |
| Canvas Format | PPT 16:9 (1280×720) |
| Page Count | 9 |
| Primary Language | ko |
| Target Audience | Professor and classmates in a Korean university class; Korean-speaking, little prior knowledge of Russia |
| Communication Intent | Introduce Russian tea culture — history, what tea is drunk, the samovar, tea as communication — with slides supporting a live spoken talk rather than replacing it |
| Desired Audience Outcome | Listeners remember: tea came via China and Mongolia (1638); Russians drink black tea with jam, lemon, honey; the samovar keeps water hot, so tea time is long; «Давай попьём чаю» means "let's meet and talk" |
| Core Message / Ask / Action | In Russia a cup of tea is a reason to meet and become closer |
| Delivery Context | Presenter-led live talk in a university classroom, shown from PowerPoint on a Windows PC; a video about the samovar is shown at slide 5 (inserted later by the presenter or dropped) |
| Artifact Afterlife | Presenter edits the PPTX herself afterwards; may submit it to the professor |
| Reading Mode | presentation |
| Content Strategy | Revision 2 (user): less text per slide; Korean titles numbered 01–05 as in 목차; separate final 감사합니다 slide. Slides carry short Korean phrases and keywords condensed from the presenter's script, with Russian words as accents (Самовар, Тула, «Давай попьём чаю»); facts only from the script; the full Korean script goes verbatim into speaker notes |
| Design Style | Direction 1 "Folk classic", revised to a light theme: cream paper field, red-beige Pavlovo Posad floral border stripes, vintage watercolor-gouache AI illustrations in thin gold frames, few words per slide, Korean numbered section titles |
| AI Image Acquisition Path | api |
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

### AI Image Strategy

- **Image Rendering**: custom
- **Image Rendering Behavior**: Light vintage watercolor-gouache illustration on warm cream paper; soft painted edges fading into the background, deep red Pavlovo Posad roses with sage-green leaves and gold accents, polished brass and rose-painted porcelain, airy storybook warmth; no text in images.
- **Visual**: isolated vignettes and light paper backgrounds with red-beige shawl border stripes
- **Mood**: a cosy Russian tea table in a vintage illustrated gift book

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
| bg_border.png | 2752x1536 | 16:9 | Cover and conclusion background with shawl stripes | Background | Full-bleed background | adaptive | ai | Generated | Cream paper with Pavlovo Posad stripes at both edges | none | hero_page |
| bg_content.png | 2752x1536 | 16:9 | Content and section background | Background | Full-bleed background | adaptive | ai | Generated | Cream paper, one shawl stripe on the left, rose spray top right | none | local |
| cover_samovar.png | 2400x1792 | 4:3 | Cover hero still life | Illustration | Framed arch picture beside the title | adaptive | ai | Generated | Samovar, rose teapot, baranki, jam, shawl | none | hero_page |
| toc_teapot.png | 1792x2400 | 3:4 | Contents accent | Illustration | Framed tall picture beside the list | adaptive | ai | Generated | Rose teapot and cups | none | local |
| p03_caravan.png | 2400x1792 | 4:3 | History scene | Illustration | Framed picture beside the timeline | adaptive | ai | Generated | Tea caravan of camels toward a Russian town | none | local |
| p04_tea_table.png | 2400x1792 | 4:3 | Tea habits still life | Illustration | Framed picture beside the table | adaptive | ai | Generated | Tea glass in podstakannik, lemon, jam, honey | none | local |
| p05_samovar.png | 1792x2400 | 3:4 | Samovar portrait | Illustration | Framed arch picture | adaptive | ai | Generated | Single brass Tula samovar | none | local |
| p06_tea_party.png | 2400x1792 | 4:3 | Hospitality scene | Illustration | Framed picture above the quote band | adaptive | ai | Generated | Family tea party around a samovar | none | local |
| p07_cups.png | 2752x1536 | 16:9 | Shared tea cultures | Illustration | Wide framed picture | adaptive | ai | Generated | Six different tea vessels in a semicircle | none | local |
| p09_thanks.png | 2752x1536 | 16:9 | Thank-you background | Background | Full-bleed background | adaptive | ai | Generated | Cream paper, shawl corners, steaming cup | none | hero_page |

## IX. Content Outline

### Part 1: Opening

#### Slide 01 - Cover

- **Audience move**: Unaware of the topic → curious about Russian tea culture
- **Relationships**: none
- **Cover impact**: Hook — the illustrated samovar tea table
- **Title**: 러시아의 차 문화
- **Core message**: Russian tea culture, presented by 추빌리나 알렉산드라
- **Content**: Title 러시아의 차 문화 · subtitle Чайная культура России · name 추빌리나 알렉산드라
- **Images**: bg_border.png full-bleed; cover_samovar.png framed beside the title

#### Slide 02 - Contents

- **Audience move**: No map of the talk → knows the five numbered sections
- **Relationships**: order — 01 → 02 → 03 → 04 → 05
- **Title**: 목차
- **Core message**: Five sections from history to tea between people
- **Content**: 01 러시아 차 문화의 역사 · 02 어떤 차를 마실까? · 03 사모바르와 전통 · 04 차를 통한 소통과 환대 · 05 구소련 국가들의 차 문화
- **Images**: bg_content.png full-bleed; toc_teapot.png framed

### Part 2: Sections

#### Slide 03 - 01 History

- **Audience move**: Assumes tea is native → sees it arrived via China and Mongolia and spread to everyone
- **Relationships**: order — 중국 · 몽골 → 1638 gift of Altyn Khan → 18–19th centuries for everyone
- **Title**: 01 러시아 차 문화의 역사
- **Core message**: Tea came through China and Mongolia and became everyone's drink
- **Content**: 중국 · 몽골 · 1638 알틴 칸의 선물 · 18–19세기 모두의 음료로
- **Images**: bg_content.png; p03_caravan.png framed

#### Slide 04 - 02 What tea

- **Audience move**: Does not know Russian habits → names black tea, its time and companions
- **Relationships**: contrast — morning coffee vs tea after meals; membership — lemon, honey, jam
- **Title**: 02 어떤 차를 마실까?
- **Core message**: Black tea after meals, with lemon, honey or jam
- **Content**: Table — 아침: 커피 / 식사 후: 홍차 / 함께: 레몬 · 꿀 · 잼 · Note — 감기 → 라즈베리 잼
- **Visualization**: tea-habits table (table/record_table), columns 언제 / 무엇을
- **Native-ready**: tea-habits=yes
- **Images**: bg_content.png; p04_tea_table.png framed

#### Slide 05 - 03 Samovar

- **Audience move**: Never saw a samovar → knows what it does and why tea time is long
- **Relationships**: link — keeps water hot → long tea time; order — 우랄 → 툴라; membership — strong brew + hot water
- **Title**: 03 사모바르와 전통
- **Core message**: The samovar keeps water hot, so tea time becomes long conversation
- **Content**: 물을 오래 뜨겁게 · 우랄 → 툴라 · 진한 차 + 뜨거운 물 · video frame 영상
- **Images**: bg_content.png; p05_samovar.png framed

#### Slide 06 - 04 Hospitality

- **Audience move**: Sees tea as a drink → sees it as an invitation to meet
- **Relationships**: link — 손님 → 차와 바란키 → 환영; «Давай попьём чаю» → 만나서 이야기하자
- **Title**: 04 차를 통한 소통과 환대
- **Core message**: Offering tea means welcome and conversation
- **Content**: 손님 → 차와 바란키 → 환영 · quote «Давай попьём чаю» = 차 한잔하자
- **Images**: bg_content.png; p06_tea_party.png framed

#### Slide 07 - 05 Former USSR

- **Audience move**: Thinks it is uniquely Russian → sees a shared culture with local differences
- **Relationships**: membership — many former USSR countries; overlap — gathering and talking over tea
- **Title**: 05 구소련 국가들의 차 문화
- **Core message**: Many former USSR countries share tea culture, traditions differ
- **Content**: 나라마다 다른 전통 · 공통점: 함께 모여 이야기
- **Images**: bg_content.png; p07_cups.png framed

### Part 3: Closing

#### Slide 08 - Conclusion

- **Audience move**: Has heard the parts → holds one takeaway
- **Relationships**: membership — 역사, 일상, 소통 lead to the takeaway
- **Closing impact**: Takeaway — 차 한잔 = 가까워지는 기회
- **Title**: 마무리
- **Core message**: In Russia, a cup of tea is a chance to become closer
- **Content**: 역사 · 일상 · 소통 · takeaway 차 한잔 = 만나서 가까워지는 기회
- **Images**: bg_border.png full-bleed

#### Slide 09 - Thank you

- **Audience move**: Talk ends → warm close
- **Relationships**: none
- **Title**: 감사합니다
- **Core message**: Thank you for listening
- **Content**: 감사합니다 · Спасибо за внимание · 추빌리나 알렉산드라
- **Images**: p09_thanks.png full-bleed

## X. Speaker Notes Requirements

- **Generation**: enabled
- **Filename**: match each SVG filename under `notes/`
- **Content**: Source sources/russian_tea_presentation.md — the presenter's Korean script, one segment per slide; preserve verbatim (Korean text only; the Russian translation is not copied)
- **Total duration**: about 6–7 minutes
- **Notes style**: conversational, presenter's own words
- **Presentation purpose**: Introduce Russian tea culture to a Korean university class with slides supporting the live talk
