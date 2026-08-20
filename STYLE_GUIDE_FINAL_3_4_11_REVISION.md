# 스타일 가이드 3·4·11번 수정 제작 지침

## 0. 작업 목적

기존 스타일 가이드 13개 중 아래 **3개 페이지만 수정**한다.

- 3번 `COLORS`
- 4번 `TYPOGRAPHY`
- 11번 `PRODUCT CARD`

수정 스타일은 아래 다섯 사이트를 참고한다.

- 오늘의 인테리어 디자인: https://todayinterior.com/
- Saem.: https://saem.space/
- 숲소리: https://www.soopsori.co.kr/
- 무인양품 코리아: https://mujikorea.co.kr/
- 대혜건축: http://daehye.com/

기존 `Editorial Tech`, 형광 Lime·Cobalt 중심의 인상을 제거하고 다음 방향으로 수정한다.

```text
Natural Editorial Commerce
Neutral Base · Material Color · Calm Typography · Image-first Card
```

---

## 1. 절대 수정 범위

### 수정할 파일

| 번호 | 기존 참고 파일 | 새 출력 파일 |
|---:|---|---|
| 3 | `스타일 가이드_초안3.png` | `스타일 가이드_최종3.png` |
| 4 | `스타일 가이드_초안4.png` | `스타일 가이드_최종4.png` |
| 11 | `스타일 가이드_초안11.png` | `스타일 가이드_최종11.png` |

### 수정하지 않을 파일

아래 번호는 어떠한 경우에도 수정하지 않는다.

```text
1, 2, 5, 6, 7, 8, 9, 10, 12, 13
```

### 필수 금지 사항

- 기존 `스타일 가이드_초안3.png`, `스타일 가이드_초안4.png`, `스타일 가이드_초안11.png`를 덮어쓰지 않는다.
- 기존 초안 PNG를 삭제하거나 이름을 변경하지 않는다.
- 3·4·11번 이외의 PNG, HTML, 컴포넌트, 레이아웃을 수정하지 않는다.
- 공통 CSS나 공통 토큰을 직접 수정하여 다른 10개 페이지에 영향을 주지 않는다.
- 수정 스타일은 3·4·11번 페이지에만 적용되도록 페이지 전용 클래스나 별도 스타일 파일로 격리한다.
- 기존 소스가 하나의 공통 파일로 구성되어 있다면 먼저 3·4·11번용 복사본을 만들고 복사본만 수정한다.
- 작업 결과는 반드시 새 파일명으로 저장한다.

### 출력 위치

기존 초안 PNG와 동일한 폴더 또는 프로젝트의 최종 출력 폴더에 다음 이름으로 저장한다.

```text
스타일 가이드_최종3.png
스타일 가이드_최종4.png
스타일 가이드_최종11.png
```

`스타일 가이드_초안n.png` 형식이나 다른 임의 파일명으로 저장하지 않는다.

---

## 2. 공통으로 유지할 양식

내용과 스타일은 수정하지만 기존 스타일 가이드의 문서 양식은 유지한다.

1. 좌측 상단 영문 페이지 제목
2. 제목 아래 한글 설명
3. 설명 아래 영문 속성 요약
4. 하단의 토큰 또는 컴포넌트 샘플 영역
5. 좌측 정렬과 기존 외곽 여백
6. 기존 페이지 번호와 제목

### 캔버스 크기

기존 PNG와 동일한 크기로 제작한다.

- 3번: `1152 × 1420px`
- 4번: `1152 × 1660px`
- 11번: `1280 × 720px`

11번은 1280×720 안에서 모든 카드가 잘리지 않도록 카드 높이와 정보량을 조절한다. 스크롤 영역이나 캔버스 밖으로 잘린 카드를 만들지 않는다.

### 공통 시각 방향

- 배경: White 또는 Warm Light Gray
- 텍스트: Charcoal 중심
- 포인트: Olive 또는 Deep Red를 제한적으로 사용
- 이미지·제품·공간 정보가 UI 장식보다 먼저 보이게 한다.
- 라운드 박스와 그림자를 최소화한다.
- 형광 Lime, Cobalt, Pink, Orange 조합을 사용하지 않는다.
- Monospace는 스타일 사양 표기에만 사용한다.

---

## 3. 레퍼런스 적용 기준

### 오늘의 인테리어 디자인

가져올 특징:

- 화이트·아이보리·그레이지·다크 우드 기반
- 큰 공간 이미지와 넓은 여백
- 프로젝트명, 연도, Location, Size, Keyword 메타 정보
- 장식보다 사진과 프로젝트 설명을 우선하는 카드

### Saem.

가져올 특징:

- 짧은 영문 제목과 한국어 설명의 조합
- 번호·층·공간 유형을 활용한 에디토리얼 정보 구조
- 큰 사진과 절제된 텍스트
- 정적인 여백과 스토리 중심 카드

### 숲소리

가져올 특징:

- 원목과 자연 소재를 연상시키는 색
- 상품 이미지, 상품명, 가격, 할인, BEST·NEW 정보
- 상품 카드와 라이프스타일 콘텐츠 카드의 구분
- 자연스럽고 친근하지만 과하게 귀엽지 않은 표현

### 무인양품 코리아

가져올 특징:

- White·Light Gray 기반의 단순한 상품 그리드
- 상품 이미지, 상품명, 가격을 중심으로 한 최소 구조
- `SOLD OUT` 등 필요한 상태만 명확하게 표시
- 브랜드 Red를 제한적으로 사용
- 카드 외곽 장식보다 정렬과 여백으로 구분

### 대혜건축

가져올 특징:

- Charcoal·White 기반의 전문적인 공간 포트폴리오
- 큰 프로젝트 이미지
- 강한 영문 프로젝트 제목
- Interior·Exterior·Project 유형의 명확한 구분

---

# 4. 최종 3번 — COLORS

## 출력 파일

`스타일 가이드_최종3.png`

## 유지할 구조

- 기존 `COLORS` 제목 위치
- 설명과 속성 요약 위치
- `Primitives · Value`
- `Semantic Color Tokens`
- 하단 상태별 컬러 예시
- 5열 컬러 칩 구조

## 교체할 설명

```text
공간과 제품 이미지가 중심이 되도록 뉴트럴 컬러를 기반으로 구성하고,
자연 소재와 상태 정보를 위한 컬러를 제한적으로 사용합니다.
```

## 속성 요약

```text
NATURAL NEUTRALS · MATERIAL COLORS · RESTRAINED ACCENTS · SEMANTIC UI COLORS
```

## 제거할 컬러

- lime/100, lime/400, lime/700
- cobalt/100, cobalt/500, cobalt/700
- orange/100, orange/500, orange/700
- pink/100, pink/400, pink/700
- 형광색을 Primary Action으로 사용하는 구조

Red는 전부 제거하지 않고 `Sale`, `Notice`처럼 제한된 상태에만 사용한다.

## 새로운 Primitive Color

### Neutral

| Token | Value | 용도 |
|---|---:|---|
| white/0 | `#FFFFFF` | 기본 Surface |
| warm-gray/50 | `#F6F5F1` | Canvas |
| warm-gray/100 | `#ECEAE4` | Subtle Surface |
| warm-gray/200 | `#DDDAD2` | 구획 배경 |
| gray/400 | `#B9B6AE` | Border |
| gray/600 | `#706D67` | Secondary Text |
| charcoal/800 | `#363632` | Strong Text |
| black/900 | `#252522` | Primary Text |

### Material

| Token | Value | 용도 |
|---|---:|---|
| wood/100 | `#E6D6C0` | 밝은 원목 |
| wood/300 | `#D0B18E` | Natural Oak |
| wood/500 | `#AA805D` | Medium Wood |
| wood/700 | `#654A38` | Dark Wood |
| stone/200 | `#D7D3CB` | 밝은 석재 |
| stone/500 | `#8A8780` | Gray Stone |

### Restrained Accent

| Token | Value | 용도 |
|---|---:|---|
| olive/100 | `#E6E7DF` | Selected Background |
| olive/500 | `#70745F` | Natural Accent |
| forest/700 | `#31483A` | Strong Natural Accent |
| red/100 | `#F4E5E4` | Sale Background |
| red/700 | `#7F1D24` | Sale·Notice |

위 값은 스타일 방향을 고정하기 위한 기준값이다. 임의로 형광색이나 고채도 컬러를 추가하지 않는다.

## Semantic Color Tokens

다음 토큰을 컬러 칩으로 표시한다.

```text
color/bg/canvas
color/bg/surface
color/bg/subtle
color/bg/inverse

color/text/primary
color/text/secondary
color/text/muted
color/text/inverse

color/border/default
color/border/strong
color/border/focus

color/action/primary
color/action/primary-hover
color/action/secondary

color/state/selected
color/state/sale
color/state/sold-out
color/state/disabled
```

## 하단 Interaction Role

기존의 Lime·Cobalt·Orange·Red 예시를 다음 4개로 교체한다.

1. `Charcoal Primary Action`
2. `Olive Selected State`
3. `Deep Red Sale State`
4. `Gray Sold Out State`

## 검수 기준

- 포인트 컬러보다 Neutral과 Material 컬러의 비중이 높아야 한다.
- 모든 컬러 칩에 토큰명, HEX, CSS Variable을 표시한다.
- 텍스트와 배경의 접근성 대비를 확보한다.
- Cobalt Focus Ring을 그대로 남기지 않는다.

---

# 5. 최종 4번 — TYPOGRAPHY

## 출력 파일

`스타일 가이드_최종4.png`

## 유지할 구조

- 기존 `TYPOGRAPHY` 제목과 설명 위치
- 각 타입 스타일을 독립된 카드에 세로로 나열하는 방식
- 각 카드 하단의 Token / Font / Weight / Size / Line Height 정보
- Desktop과 Mobile 값 비교

## 교체할 설명

```text
공간과 브랜드 이야기는 절제된 Editorial Display로 표현하고,
제품 정보와 인터페이스는 가독성이 높은 Sans Serif로 구성합니다.
```

## 속성 요약

```text
EDITORIAL DISPLAY · READABLE KOREAN SANS · RESTRAINED WEIGHTS · CLEAR PRODUCT HIERARCHY
```

## 서체 체계

### Editorial Display

- 영문 우선: `Cormorant Garamond` 또는 `DM Serif Display`
- 한글 대응: `Noto Serif KR` 또는 `MaruBuri`
- 사용처: 히어로 문장, 공간 스토리, 프로젝트 제목
- 전체 텍스트의 약 10~15%에만 사용

### Commerce & UI Sans

- 한글·영문: `Pretendard`, 대체 `Noto Sans KR` 또는 `SUIT`
- 사용처: 제품명, 가격, 설명, 메뉴, 버튼, 배지
- 전체 텍스트의 약 85~90%에 사용

### Mono

- `IBM Plex Mono` 또는 기존 Mono
- 스타일 가이드의 토큰 사양 표기에만 사용
- 실제 제목, 가격, 제품 설명, 버튼에는 사용하지 않는다.

## Type Scale

| Token | Desktop | Mobile | Font / Weight | 사용처 |
|---|---:|---:|---|---|
| Display/Large | 56/68 | 40/50 | Serif Regular | Hero·공간 메시지 |
| Display/Medium | 44/56 | 34/44 | Serif Regular | 프로젝트 메시지 |
| Heading/1 | 40/52 | 32/42 | Sans Medium | 페이지 제목 |
| Heading/2 | 32/44 | 26/36 | Sans Medium | 섹션 제목 |
| Heading/3 | 24/34 | 22/32 | Sans Medium | 카드 그룹 제목 |
| Title/Large | 20/30 | 19/28 | Sans Medium | 제품·프로젝트명 |
| Title/Medium | 17/26 | 17/26 | Sans Medium | 카드 제목 |
| Body/Large | 16/28 | 16/26 | Sans Regular | 공간·브랜드 설명 |
| Body/Medium | 14/24 | 14/22 | Sans Regular | 제품 설명 |
| Body/Small | 13/20 | 13/20 | Sans Regular | 보조 정보 |
| Label/Large | 14/20 | 14/20 | Sans Medium | 버튼·탭 |
| Label/Small | 12/18 | 12/18 | Sans Medium | 배지·카테고리 |
| Caption | 11/17 | 11/17 | Sans Regular | 이미지 캡션·메타 |

## 샘플 문장

### Display/Large

```text
A QUIET OBJECT
FOR EVERYDAY LIFE
```

### Display/Medium

```text
공간에 자연스럽게 머무는 물건
```

### Heading

```text
재료의 질감과 쓰임을 담은 컬렉션
```

### Title

```text
오브제 트레이 세트
```

### Body

```text
재료의 질감과 사용 정보를 단정한 위계로 전달합니다.
```

### Label

```text
컬렉션 보기
```

### Caption

```text
COLLECTION 01 · NATURAL MATERIAL · 2026
```

## 제거할 표현

- `Inter Tight Bold 72px` 중심의 과도한 초대형 Display
- 모든 영문 Label의 강제 Uppercase
- 실제 콘텐츠에 반복 사용된 `JetBrains Mono`
- 제목마다 Bold 또는 Extra Bold 적용
- `OBJECTS FOR A NEW ROUTINE.` 문장 반복
- 각 타입 카드를 과하게 두꺼운 글자로 채우는 구성

## 검수 기준

- Display와 UI Sans의 역할 차이가 분명해야 한다.
- 한글 줄바꿈이 어색하지 않아야 한다.
- Body와 Caption의 가독성이 확보되어야 한다.
- 카드 안 텍스트가 세로 중앙에서 잘리거나 넘치지 않아야 한다.
- 기존 1152×1660 캔버스 안에서 전체 Type Scale이 모두 보여야 한다.

---

# 6. 최종 11번 — PRODUCT CARD

## 출력 파일

`스타일 가이드_최종11.png`

## 유지할 구조

- 기존 `PRODUCT CARD` 제목과 설명 위치
- 설명 아래 `VARIANTS`와 `PROPERTY` 요약
- 2열 × 2행, 총 4개 카드 비교 구조
- 카드 유형별 차이를 한 화면에서 비교하는 방식

## 교체할 설명

```text
상품·프로모션·공간 프로젝트·브랜드 이야기를 콘텐츠 목적에 맞는
이미지 비율과 정보 위계로 구분합니다.
```

## 속성 요약

```text
VARIANTS TYPE / IMAGE RATIO / DENSITY / STATE
PROPERTY IMAGE / CATEGORY / BADGE / TITLE / DESCRIPTION / METADATA / PRICE / ACTION
```

## 기존 카드 중 제거할 유형

- `Feature 3D Object`
- `Dark Theme Card`
- Lime 전체 배경 카드
- Navy 전체 배경 카드
- 형광 Badge와 Cobalt Action

## 새로운 카드 4종

### Card 01 — Standard Product

무인양품의 단순한 상품 카드 구성을 참고한다.

구성:

- 이미지 비율 `1:1` 또는 `4:5`
- 제품 이미지가 카드 면적의 약 70% 이상
- Category
- Product Name
- Price
- 선택적으로 Wishlist
- 카드 외곽 보더와 배경 박스 없음

예시:

```text
LIVING OBJECT
오브제 트레이 세트
48,000원
```

### Card 02 — Promotion Product

숲소리의 BEST·추천·할인 상품 표현을 참고한다.

구성:

- 제품 이미지
- `BEST`, `NEW`, `15%` 중 하나의 작은 Badge
- Product Name
- Original Price
- Sale Price
- Discount Rate
- 필요 시 Review Count

예시:

```text
BEST · 15%
오브제 트레이 세트
48,000원  40,800원
```

Deep Red는 할인율과 Sale Price에만 제한적으로 사용한다.

### Card 03 — Space / Project

오늘의 인테리어 디자인과 대혜건축의 프로젝트 카드 구성을 참고한다.

구성:

- 이미지 비율 `3:2` 또는 `4:3`
- Project Number / Year
- Project Name
- Location
- Size
- Keyword
- `View Project →`

예시:

```text
PROJECT 01 · 2026
A Quiet Bathroom

Location  Seoul
Size      8㎡
Keyword   Natural
```

### Card 04 — Editorial / Story

Saem.의 공간 스토리텔링을 참고한다.

구성:

- 이미지 비율 `4:5` 또는 `3:2`
- Story Number
- 짧은 영문 Title
- 한국어 설명 1~2줄
- `View Story →`
- 가격 없음

예시:

```text
STORY 02
The Quiet Routine

잠시 머물며 일상의 감각을 발견하는 시간.
View Story →
```

## Variant

```text
TYPE        Product / Promotion / Project / Editorial
IMAGE RATIO 1:1 / 4:5 / 3:2 / 4:3
DENSITY     Compact / Regular
STATE       Default / Hover / Sold Out / Sale
```

## 상태 표현

### Default

- 이미지와 정보만 표시
- 별도 Shadow 없음

### Hover

- 이미지 최대 1.02배 확대
- 화살표 또는 얇은 Underline 노출
- 카드가 위로 떠오르는 Shadow 효과 금지

### Sold Out

- 이미지 채도 또는 투명도 감소
- 이미지 상단에 `SOLD OUT`
- 가격과 Action 비활성화

### Sale

- Original Price 취소선
- Sale Price와 Discount Rate만 Deep Red
- 카드 전체를 Red로 채우지 않는다.

## 카드 형태

- 이미지 radius: `0~4px`
- 카드 외곽 radius: 없음 또는 최대 `4px`
- 카드 외곽 보더: 기본 상태 없음
- 정보 영역을 흰색 라운드 박스로 감싸지 않는다.
- 카드 구분은 Grid Gap과 여백으로 처리한다.
- 그림자 사용 금지
- 텍스트 좌측 정렬
- 제품과 공간 이미지가 UI보다 먼저 보여야 한다.

## 1280×720 배치 지침

- 상단 제목·설명·속성 영역의 높이를 기존과 유사하게 유지한다.
- 하단 4개 카드는 2열 × 2행으로 모두 캔버스 안에 표시한다.
- 각 카드의 높이는 약 `230~245px` 범위로 조절한다.
- 실제 이미지는 중립적인 이미지 플레이스홀더로 표시해도 되지만 기존 Grid Pattern과 형광 Badge는 사용하지 않는다.
- 카드 4번이 캔버스 아래로 잘리지 않도록 반드시 PNG 캡처 결과를 확인한다.

## 검수 기준

- 4개 카드가 모두 완전히 보여야 한다.
- 네 카드는 색상 테마가 아니라 콘텐츠 유형으로 구분되어야 한다.
- Product와 Promotion에는 가격이 있고 Project와 Editorial에는 가격이 없어야 한다.
- 형광 Lime·Cobalt·Orange·Pink가 남아 있지 않아야 한다.
- 무인양품식 최소 상품 카드와 공간 포트폴리오 카드의 차이가 명확해야 한다.

---

## 7. PNG 생성 및 저장 지침

1. 기존 초안 3·4·11번을 참고 자료로만 연다.
2. 기존 파일을 복제하거나 별도 페이지를 만들어 수정한다.
3. 수정된 페이지를 아래 이름으로 캡처한다.

```text
스타일 가이드_최종3.png
스타일 가이드_최종4.png
스타일 가이드_최종11.png
```

4. 기존 `스타일 가이드_초안3.png`, `스타일 가이드_초안4.png`, `스타일 가이드_초안11.png`는 그대로 보존한다.
5. 나머지 초안 10개는 열람만 가능하며 수정·재생성·이름 변경을 하지 않는다.
6. 캡처 전 브라우저 UI, 스크롤바, Focus Debug Outline을 제거한다.
7. 각 PNG를 실제로 열어 크기, 잘림, 오탈자를 검수한다.

---

## 8. 최종 체크리스트

### 범위

- [ ] 3·4·11번만 수정함
- [ ] 1·2·5·6·7·8·9·10·12·13번을 수정하지 않음
- [ ] 공통 CSS 변경으로 다른 페이지에 영향이 생기지 않음

### 저장

- [ ] 기존 초안 PNG를 덮어쓰지 않음
- [ ] 기존 초안 PNG를 삭제하지 않음
- [ ] `스타일 가이드_최종3.png` 생성
- [ ] `스타일 가이드_최종4.png` 생성
- [ ] `스타일 가이드_최종11.png` 생성
- [ ] 다른 임의 이름의 PNG를 만들지 않음

### 품질

- [ ] 최종3은 1152×1420px
- [ ] 최종4는 1152×1660px
- [ ] 최종11은 1280×720px
- [ ] 형광 Lime·Cobalt 중심 스타일이 제거됨
- [ ] Warm Neutral·Wood·Charcoal 체계가 적용됨
- [ ] Serif와 Sans의 역할이 구분됨
- [ ] Product Card 4개가 콘텐츠 유형별로 구분됨
- [ ] 최종11의 하단 카드가 잘리지 않음
- [ ] 텍스트 잘림과 오탈자가 없음

---

## 9. 완료 보고 형식

작업 완료 후 아래 항목만 보고한다.

```text
수정 완료 파일
1. 스타일 가이드_최종3.png
2. 스타일 가이드_최종4.png
3. 스타일 가이드_최종11.png

보존 확인
- 기존 초안 파일 덮어쓰기 없음
- 3·4·11번 이외 파일 변경 없음

검수 결과
- 파일별 해상도
- 텍스트 잘림 여부
- 최종11 카드 잘림 여부
```
