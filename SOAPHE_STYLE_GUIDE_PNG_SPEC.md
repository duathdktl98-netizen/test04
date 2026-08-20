# SOAPHE Style Guide — Love.md Reference-driven PNG 제작 명세

## 0. 작업 목표와 우선순위

첨부된 `AI ACE CBT Learning UI Kit` 13장의 **문서 양식과 정보 구조**는 유지하되, 시각 스타일은 SOAPHE의 기존 브랜드 콘셉트가 아니라 `Love.md`의 8개 레퍼런스 프로젝트에서 가져온다.

우선순위:

1. 첨부 양식의 페이지 구성 유지
2. `Love.md` 레퍼런스의 시각 스타일 적용
3. SOAPHE는 결과물에 표시되는 브랜드명과 예시 콘텐츠로만 사용

컬러, 서체, 모서리, 카드, 이미지 처리, 그래픽 장식, 인터랙션은 SOAPHE의 기존 `온기·머무름·빈티지·유기적 곡선`과 무관하게 결정한다. 결과는 **13개의 독립 PNG**로 제작한다.

---

## 1. 필수 참고 자료

### 1.1 양식 참고

처음 첨부된 13개 JPG에서는 다음만 참고한다.

- 제목 위치와 크기
- 제목 아래 한국어 설명
- `PROPERTY`, `VARIANTS`, `ACCESSIBILITY` 안내
- 토큰과 Variant 나열 방식
- 샘플 패널 구성
- 페이지 여백과 정렬

AI ACE CBT의 네이비·블루 팔레트와 학습 서비스 콘텐츠는 복제하지 않는다.

### 1.2 스타일 참고

`Love.md`의 링크를 실제로 열어 확인한다.

| 레퍼런스 | 가져올 특징 | 주 적용 위치 |
|---|---|---|
| New Works — UI Interaction | 큰 제품 이미지, 절제된 내비게이션, 대형 타이포 | Cover, Typography, Gallery |
| Permanent Collection | 에디토리얼 그리드, 얇은 선, 넓은 여백, 비대칭 이미지 | Getting Started, Grid, Card |
| RentEase | 명확한 위계, 오렌지 포인트, 정돈된 상태 | Button, Badge, Option |
| AgridFlow | 라임·그린 포인트, 모듈형 카드, 정보 그룹화 | Colors, Card, Navigation |
| Zolve | 화이트 베이스, 선명한 그린, 부드러운 3D | Colors, Image, Badge |
| Swipe Drinks | 밝은 포인트, 모바일 친화 컨트롤, 플레이풀한 라운드 | Option, Mobile Navigation |
| Sisense | 딥 네이비·블랙, 코발트 포인트, 명확한 상태 | Cover, Effects, States |
| OmniRoom | 대형 공간 이미지, 강한 크롭, 3D 프레젠테이션 | Image, Gallery |

### 1.3 통합 스타일

8개 스타일을 페이지별로 따로 복제하지 말고 하나의 시스템으로 통합한다.

- Editorial tech
- Bold grotesk typography
- Neutral canvas
- High-contrast accent
- Modular cards
- Asymmetric composition
- Large image crop
- Clear interaction states
- Minimal line icons
- Soft 3D product imagery

충돌 시 우선순위:

1. New Works + Permanent Collection의 에디토리얼 구조
2. AgridFlow + Zolve + Sisense의 UI 체계
3. RentEase + Swipe Drinks의 포인트 컬러와 컨트롤
4. OmniRoom의 대형 공간 이미지와 3D 표현

금지:

- 웜 아이보리·브라운·더스티 로즈 중심 감성 팔레트
- SOAPHE 로고의 유기적 곡선을 반복 장식으로 사용
- 베이지 감성 브랜드 스타일
- 레퍼런스의 실제 로고·제품 사진·UI 화면 복사
- 한 화면에 모든 포인트 컬러를 동시에 사용

---

## 2. 전체 비주얼 시스템

### 2.1 컬러

뉴트럴 베이스에 고채도 포인트를 사용한다.

| Token | HEX | 역할 |
|---|---:|---|
| neutral/0 | `#FFFFFF` | Surface |
| neutral/50 | `#F5F6F2` | Canvas |
| neutral/100 | `#ECEEE8` | Subtle panel |
| neutral/300 | `#C8CDC4` | Border |
| neutral/600 | `#697069` | Secondary text |
| ink/900 | `#111411` | Primary text |
| navy/900 | `#111A33` | Inverse background |
| lime/400 | `#C9F24B` | Primary accent |
| green/600 | `#197A55` | Success / active |
| cobalt/500 | `#4C62FF` | Focus / information |
| orange/500 | `#FF7A3D` | Highlight / warning |
| pink/400 | `#FF9AB8` | Secondary accent |
| red/500 | `#E3483E` | Error / sold out |

권장 비율: Neutral 75% / Ink·Navy 15% / 주 Accent 8% / 보조 Accent 2%. 한 페이지의 주 Accent는 하나만 선택한다.

### 2.2 타이포

- 큰 제목: 굵고 압축감 있는 Grotesk Sans
- UI 본문: Regular 또는 Medium Sans
- 작은 메타와 토큰명: Mono 또는 좁은 Sans
- 세리프 사용 금지
- Display는 좁은 자간, Label은 약간 넓은 자간
- 영문 대문자와 큰 줄바꿈을 적극 활용

권장 대체 서체:

- Display: `Inter Tight`, `Archivo`, `Manrope`
- Body/UI: `Pretendard`, `Inter`, `Noto Sans KR`
- Meta: `IBM Plex Mono`, `Roboto Mono`

### 2.3 형태와 효과

- 에디토리얼 이미지: radius 0~8px
- UI 카드: radius 16px
- 강조 카드·모바일 패널: radius 24~32px
- Badge·소형 컨트롤: full pill
- 얇은 보더와 명도 대비를 우선하고 그림자는 Floating 요소에만 사용
- 1.5~2px 선형 아이콘과 화살표 사용

### 2.4 이미지

- 큰 이미지 크롭, 단순 배경 위 제품, 대형 공간 이미지
- 3D 렌더와 고해상도 스튜디오 이미지를 혼합
- 이미지 위 작은 숫자·좌표·메타·얇은 선 사용
- 사각형, 풀 블리드, 비대칭 크롭 혼합
- 이미지가 없으면 회색 박스가 아니라 중립적인 3D 오브젝트 플레이스홀더 제작

---

## 3. 첨부 양식 공통 규칙

### 출력

- 01 Cover: `1280 × 720px`
- 02 Getting Started: `1280 × 520px`
- 03~13: 폭 `1152px` 고정, 높이는 페이지별 권장값
- `sRGB`, 1배율, 불투명 배경 PNG

### 03~13 정보 순서

1. 좌측 상단 영문 제목
2. 한국어 설명
3. `PROPERTY`, `VARIANTS`, `ACCESSIBILITY` 안내
4. 토큰 또는 컴포넌트 샘플 패널

### 공통 여백

- 외곽: 좌우 32px, 상단 36~40px, 하단 32px 이상
- 제목→설명 24px
- 설명→속성 24~32px
- 속성→샘플 44~56px
- 샘플 패널 패딩 32px 이상
- 페이지 외곽 radius 약 24px

### 배경

- 기본 페이지 `neutral/50`
- 샘플 패널 `neutral/0` 또는 `neutral/100`
- 강조 패널 `ink/900` 또는 `navy/900`
- 패널 보더 `neutral/300` 1px

---

# 01. Cover

- 파일명: `01.SOAPHE_Cover.png`
- 크기: `1280 × 720px`

첨부 표지처럼 중앙 캡슐, 2행 제목, 설명, 구분선, 하단 키워드 구조를 유지한다.

```text
REFERENCE-DRIVEN UI KIT · VERSION 1.0

SOAPHE
Brand & Web UI Kit

Editorial commerce experience built from curated UI references
Foundations · Components · Product Experience

Design Tokens · Modular UI · Responsive Web · Interaction States
```

스타일:

- Sisense의 다크 대비 + New Works의 절제된 대형 타이포
- `navy/900` 배경, `lime/400` 캡슐과 포인트
- 굵은 Grotesk 제목
- 한쪽에 Cobalt 또는 Lime 직사각형 블록을 크게 잘라 배치
- 감성 문구와 유기적 곡선 금지

---

# 02. Getting Started

- 파일명: `02.SOAPHE_Getting_Started.png`
- 크기: `1280 × 520px`

제목: `Getting Started`

설명: `토큰을 선택하고 컴포넌트 인스턴스를 조합한 뒤, 에디토리얼 제품 화면과 반응형 패턴으로 확장합니다.`

카드 3개:

1. **Build Foundations** — `Neutral base·Bold type·Accent color·Grid 토큰을 먼저 선택하고 Semantic Token을 사용합니다.`
2. **Compose Components** — `Button·Badge·Option·Card를 모듈처럼 배치하고 Variants로 상태를 전환합니다.`
3. **Create Experience** — `대형 이미지와 명확한 위계를 결합해 Desktop·Tablet·Mobile 경험을 완성합니다.`

Permanent Collection의 여백과 SaaS 레퍼런스의 모듈형 카드를 결합한다. 카드 radius 16px, 보더 1px, 그림자 없음. 카드별 상단 라인은 Lime / Cobalt / Orange로 구분한다.

---

# 03. Colors

- 파일명: `03.SOAPHE_Foundations_Colors.png`
- 권장 크기: `1152 × 1420px`

설명: `Neutral palette는 콘텐츠의 기반이며, Accent와 Semantic Color는 행동·상태·정보 위계를 명확하게 표시합니다.`

## Primitives · Value

첨부 양식처럼 5열 컬러 칩으로 표시한다.

- neutral/0, 50, 100, 300, 600
- ink/900, navy/900
- lime/100, 400, 700
- green/100, 600, 800
- cobalt/100, 500, 700
- orange/100, 500, 700
- pink/100, 400, 700
- red/100, 500, 700

각 칩에 토큰명, HEX, CSS 변수를 표시한다.

## Semantic Color

- bg/canvas, surface, subtle, inverse, accent, selected, disabled
- text/primary, secondary, muted, inverse, on-accent, disabled
- border/default, strong, focus
- action/primary, primary-hover, secondary
- status/success, warning, error

하단에 Lime CTA / Cobalt Focus / Orange Warning / Red Error 샘플을 배치한다.

---

# 04. Typography

- 파일명: `04.SOAPHE_Foundations_Typography.png`
- 권장 크기: `1152 × 1660px`

설명: `대형 Grotesk Display와 정밀한 UI 본문의 대비를 사용해 에디토리얼 인상과 명확한 정보를 함께 전달합니다.`

첨부 양식처럼 각 스타일을 흰색 카드에 세로로 나열한다.

샘플:

- Display: `OBJECTS FOR A NEW ROUTINE.`
- Heading: `기능과 형태가 만나는 새로운 일상`
- Body: `제품의 특징과 사용 정보를 명확한 위계로 전달합니다.`
- Label: `EXPLORE COLLECTION`

| Style | Desktop | Mobile | Weight |
|---|---|---|---|
| Display/XL | 72/76 | 44/48 | Grotesk Bold |
| Display/Large | 56/62 | 38/44 | Grotesk Bold |
| Heading/1 | 40/48 | 32/40 | Sans SemiBold |
| Heading/2 | 32/40 | 26/34 | Sans SemiBold |
| Heading/3 | 24/32 | 22/30 | Sans Medium |
| Title/Large | 20/28 | 19/27 | Sans SemiBold |
| Title/Medium | 18/26 | 17/25 | Sans Medium |
| Body/Large | 16/26 | 16/26 | Sans Regular |
| Body/Medium | 14/22 | 14/22 | Sans Regular |
| Body/Small | 13/20 | 13/20 | Sans Regular |
| Label/Large | 13/18 | 13/18 | Sans SemiBold |
| Label/Medium | 12/16 | 12/16 | Sans Medium |
| Meta/Mono | 11/16 | 11/16 | Mono Medium |

---

# 05. Spacing & Grid

- 파일명: `05.SOAPHE_Foundations_Spacing_Grid.png`
- 권장 크기: `1152 × 1320px`

설명: `8px 기반 간격과 반응형 그리드로 에디토리얼 여백과 모듈형 UI 밀도를 함께 관리합니다.`

## Spacing scale

`0 / 4 / 8 / 12 / 16 / 24 / 32 / 40 / 48 / 64 / 80 / 120 / 160`

막대는 Lime 또는 Cobalt로 표시한다.

## Control & touch

- small 36px
- medium 44px
- large 52px
- touch minimum 44px

## Responsive grid

- Desktop: 12 columns / max 1440px / margin 64px / gutter 24px
- Tablet: 8 columns / margin 32px / gutter 20px
- Mobile: 4 columns / margin 20px / gutter 16px

하단 미니 레이아웃: Full bleed image / 7:5 asymmetric split / Modular card grid.

---

# 06. Radius & Effects

- 파일명: `06.SOAPHE_Foundations_Radius_Effects.png`
- 권장 크기: `1152 × 680px`

설명: `Editorial surface와 UI component에 서로 다른 곡률을 적용하고 그림자는 떠 있는 요소에만 사용합니다.`

Radius: `0 / 4 / 8 / 16 / 24 / 32 / full`

Effects:

- Shadow/Card · y 2 / blur 8 / opacity 5%
- Shadow/Floating · y 10 / blur 28 / opacity 12%
- Shadow/Overlay · y 20 / blur 48 / opacity 18%
- Neutral Border 1px
- Cobalt Focus Ring 2px
- Dark Image Gradient Overlay

Editorial image는 radius 0~8, UI card는 16, Mobile floating panel은 24~32를 사용한다.

---

# 07. Image Direction

- 파일명: `07.SOAPHE_Foundations_Image_Direction.png`
- 권장 크기: `1152 × 1120px`

설명: `대형 크롭·스튜디오 제품 이미지·공간 이미지·3D 오브젝트를 조합해 제품을 에디토리얼하게 보여줍니다.`

속성: `CATEGORIES Studio / Space / Detail / 3D / Context · RATIO 1:1 / 4:5 / 3:2 / 16:9 / Full bleed`

6개 샘플:

1. Studio Object — 단색 배경 위 큰 제품
2. Full-bleed Space — 화면을 채우는 공간
3. Material Detail — 강하게 크롭한 질감
4. Soft 3D — Zolve·OmniRoom 참고
5. Context Shot — 제품과 사용자의 관계
6. Graphic Crop — 이미지 위 숫자·라인·메타

흑백 또는 저채도 이미지 위에 Lime·Cobalt·Pink 블록을 제한적으로 겹친다. 실제 레퍼런스 이미지는 복사하지 않는다.

Good: 큰 피사체, 명확한 초점, 과감한 여백, 정보 대비  
Avoid: 작은 이미지 반복, 감성 소품 과다, 베이지 필터, 모두 같은 비율

---

# 08. Button

- 파일명: `08.SOAPHE_Components_Button.png`
- 권장 크기: `1152 × 780px`

설명: `강한 색 대비와 명확한 상태 변화로 주요 행동의 위계를 빠르게 인식하도록 설계합니다.`

`PROPERTY Label / Icon · VARIANTS Size / Style / State / Width · ACCESSIBILITY Focus 2px, 최소 높이 44px`

- Size: Small / Medium / Large
- Style: Primary / Dark / Secondary / Ghost
- State: Default / Hover / Pressed / Focus / Disabled
- Width: Hug / Fill

스타일:

- Primary: Lime + Ink
- Dark: Ink + White
- Secondary: White + Ink 1px border
- Ghost: transparent + text + arrow
- Focus: Cobalt 2px ring

샘플: `EXPLORE COLLECTION`, `VIEW DETAILS`, `ADD TO CART`, `NEXT`.

첨부 Button 페이지처럼 State를 열, Style과 Size를 행으로 배열한다.

---

# 09. Badge & Tag

- 파일명: `09.SOAPHE_Components_Badge_Tag.png`
- 권장 크기: `1152 × 580px`

설명: `상태·카테고리·필터 정보를 고채도 포인트와 짧은 레이블로 구분합니다.`

`PROPERTY Label / Dot / Icon · VARIANTS Size / Type / Tone / State`

Tone: Neutral / Lime / Cobalt / Orange / Pink / Error

샘플: `NEW`, `BEST`, `LIMITED`, `IN STOCK`, `SOLD OUT`, `OBJECT`, `SPACE`, `EDITORIAL`.

첨부 Badge 페이지처럼 Small과 Medium 두 행, Tone을 열로 표시한다.

---

# 10. Product Option

- 파일명: `10.SOAPHE_Components_Product_Option.png`
- 권장 크기: `1152 × 980px`

설명: `텍스트·컬러·썸네일 선택지를 하나의 구조로 관리하고 선택·품절·포커스 상태를 명확하게 구분합니다.`

`PROPERTY Label / Swatch / Thumbnail / Meta · VARIANTS Type / State · 최소 높이 56px · Focus 2px`

State를 첨부 Quiz Option처럼 세로로 나열한다.

1. Default
2. Hover
3. Focus
4. Selected
5. Disabled
6. Sold Out

Type: Text Option / Color Swatch / Thumbnail Option / Compact Chip.

- Selected: Ink + White 또는 Lime + Ink
- Hover: Neutral 100
- Focus: Cobalt ring
- Sold Out: 낮은 명도 + 취소선 + SOLD OUT
- 기본 radius 12~16px, Compact Chip만 pill

Swipe Drinks의 모바일 친화성, RentEase의 위계, AgridFlow의 상태 구분을 결합한다.

---

# 11. Product Card

- 파일명: `11.SOAPHE_Components_Product_Card.png`
- 권장 크기: `1152 × 1080px`

설명: `큰 이미지와 간결한 정보 블록을 결합하고 Editorial·Product·Feature·Dark Card로 확장합니다.`

`VARIANTS Type / State / Image Ratio / Theme · PROPERTY Image / Badge / Title / Meta / Action`

첨부 Card 페이지처럼 2열 × 2행으로 배치한다.

1. Product — 4:5 이미지, Category, Name, Price, Arrow
2. Editorial — 3:2 또는 Full-bleed, 큰 제목, Issue number, Meta
3. Feature — Lime 또는 Cobalt 배경, 3D Object, 핵심 문장
4. Dark — Navy/Ink 배경, White text, 고채도 포인트

State: Default / Hover / Focus / Disabled. Hover는 이미지 1.03배 확대와 화살표 4px 이동만 사용한다.

---

# 12. Navigation

- 파일명: `12.SOAPHE_Components_Navigation.png`
- 권장 크기: `1152 × 980px`

설명: `단순한 메뉴 구조, 선명한 Active 상태, 반응형 전환으로 콘텐츠 중심 탐색을 지원합니다.`

`VARIANTS Device / State / Theme · PROPERTY Logo / Menu / Utility / Badge · ACCESSIBILITY Keyboard focus`

## Desktop Header

Logo / Collection / Objects / Spaces / Journal / Search / Cart  
State: Default / Hover / Active / Scrolled

## Dropdown

- 텍스트 메뉴 2열
- 오른쪽 Feature 이미지 1개
- 작은 Index 또는 Meta
- Lime 또는 Cobalt 포인트 라인

## Mobile

- Menu / Logo / Cart
- Full-screen open menu
- 큰 메뉴 번호
- 최소 터치 44px

## Local Navigation

Category Tabs / Breadcrumb / Pagination.

New Works의 헤더, Permanent Collection의 에디토리얼 메뉴, SaaS 레퍼런스의 Active 상태를 결합한다.

---

# 13. Media Gallery

- 파일명: `13.SOAPHE_Components_Media_Gallery.png`
- 권장 크기: `1152 × 1040px`

설명: `대형 미디어와 최소 컨트롤을 결합해 제품·공간·디테일 콘텐츠를 에디토리얼하게 탐색하도록 합니다.`

`VARIANTS Device / Layout / State / Theme · PROPERTY Media / Thumbnail / Index / Caption / Control`

## Desktop

- 비대칭 7:5 Split Layout
- 큰 대표 이미지 + 작은 보조 이미지
- Index `01 / 06`
- Prev / Next / Expand
- Caption + Category

## Category

`ALL / PRODUCT / SPACE / DETAIL / PROCESS / 3D`

## Mobile

- 대표 이미지 1개
- 가로 스와이프
- 분수형 인디케이터
- 하단 캡션
- 가로 썸네일

New Works의 대형 제품 이미지와 OmniRoom의 공간 프레젠테이션을 참고한다. Selected Thumbnail은 Lime 보더 또는 Index로 표시한다. 자동 재생 금지, 버튼 44px 이상, 키보드 조작을 지원한다.

---

## 4. 구현 및 PNG 생성

1. `soaphe-style-guide/` 폴더를 만든다.
2. HTML/CSS 또는 가장 안정적인 방식으로 13개 페이지를 구현한다.
3. 공통 토큰과 레이아웃은 하나의 스타일 파일에서 관리한다.
4. 각 페이지를 독립 렌더링 가능하게 한다.
5. Playwright 또는 동등한 방식으로 캡처한다.
6. PNG는 `soaphe-style-guide/png/`에 저장한다.
7. 구현 소스도 유지한다.

### 출력 파일

```text
01.SOAPHE_Cover.png
02.SOAPHE_Getting_Started.png
03.SOAPHE_Foundations_Colors.png
04.SOAPHE_Foundations_Typography.png
05.SOAPHE_Foundations_Spacing_Grid.png
06.SOAPHE_Foundations_Radius_Effects.png
07.SOAPHE_Foundations_Image_Direction.png
08.SOAPHE_Components_Button.png
09.SOAPHE_Components_Badge_Tag.png
10.SOAPHE_Components_Product_Option.png
11.SOAPHE_Components_Product_Card.png
12.SOAPHE_Components_Navigation.png
13.SOAPHE_Components_Media_Gallery.png
```

### 제작 규칙

- 브라우저 UI·스크롤바가 보이지 않게 한다.
- 제목 → 설명 → 속성 → 샘플 순서를 유지한다.
- 한 페이지의 주 Accent는 하나만 사용한다.
- 8개 특징을 하나의 시스템으로 통합한다.
- 레퍼런스의 이미지·로고·UI를 복사하지 않는다.
- SOAPHE의 기존 웜 브라운 팔레트와 유기적 장식을 사용하지 않는다.
- 이미지가 없으면 중립 3D 플레이스홀더를 직접 만든다.
- 각 PNG를 실제로 열어 시각 검수한다.

---

## 5. 최종 검수

- [ ] PNG 13개 생성
- [ ] 파일명이 01~13 순서로 정확함
- [ ] Cover 1280×720px
- [ ] Getting Started 1280px 폭
- [ ] 나머지 1152px 폭
- [ ] 첨부 양식의 정보 구조 유지
- [ ] SOAPHE 기존 감성 팔레트 미사용
- [ ] Neutral + Ink + High-chroma Accent 체계 일관
- [ ] Grotesk Display와 UI Text 대비 명확
- [ ] Editorial grid + Modular card 적용
- [ ] 한 페이지에 Accent 과다 혼합 없음
- [ ] Hover / Focus / Selected / Disabled 구분
- [ ] 레퍼런스 저작물 복사 없음
- [ ] 텍스트 잘림·오탈자 없음
- [ ] 모든 PNG 육안 검수 완료

## 6. 완료 보고

1. PNG 13개 경로
2. 구현 소스 경로
3. 사용 서체와 대체 서체
4. 페이지별 주 Accent
5. 페이지별 핵심 참고 레퍼런스
6. 명세 변경 사항과 이유
7. 시각 검수 결과와 제한 사항
