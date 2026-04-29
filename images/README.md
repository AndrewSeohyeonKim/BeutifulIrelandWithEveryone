# 📸 코스별 대표 장소 사진 폴더

각 destination별로 폴더가 나뉘어 있어요. 사진을 넣을 때는 **정확한 파일명**으로 저장해야 자동으로 홈페이지에 표시됩니다.

## 📁 폴더 구조 (16개 destination)

```
images/
├── newgrange/        ← 뉴그레인지 + 드록헤다 (120km)
├── wicklow/          ← 위클로 국립공원 (150km) ✓ 사진 일부 입수
├── mullingar/        ← 멀링거 (180km)
├── kilkenny/         ← 킬케니 (230km)
├── belfast/          ← 벨파스트 (340km)
├── waterford/        ← 워터포드 (340km)
├── limerick/         ← 리머릭 + 카셸 (380km)
├── galway/           ← 골웨이 시티 (420km)
├── sligo/            ← 슬라이고 (460km)
├── cork/             ← 코크 (시내·코브·킨세일·웨스트코크) (480km)
├── connemara/        ← 코네마라 + 카일모어 (480km)
├── causeway/         ← 자이언트 코즈웨이 (500km)
├── mayo/             ← 메이요 (아킬·다운패트릭·녹) (530km)
├── moher/            ← 모허 + 버렌 (540km)
├── donegal/          ← 도니골 (남부·북부·데리) (600km)
└── kerry/            ← 케리 (킬러니+딩글) (750km)
```

## 📷 위클로 (Wicklow) — 11곳 · 필요 파일 목록 ✓ 사진 받음

`images/wicklow/` 안에 아래 파일명으로 저장:

| 순서 | 파일명 | 장소 |
|---|---|---|
| 1 | `brittas-bay.jpg` | 브리타스 베이 |
| 2 | `rapeseed.jpg` | 유채꽃 들판 (4~5월 한정) |
| 3 | `kilmacurragh.jpg` | 킬마커러 국립식물원 |
| 4 | `sally-gap.jpg` | 샐리 갭 |
| 5 | `avoca-mills.jpg` | 에이보카 밀 |
| 6 | `lough-tay.jpg` | 러프 테이 전망대 |
| 7 | `powerscourt-waterfall.jpg` | 파워스코트 폭포 |
| 8 | `powerscourt-estate.jpg` | 파워스코트 정원 |
| 9 | `glendalough.jpg` | 글렌달록 호수 |
| 10 | `glendalough-monastic.jpg` | 글렌달록 수도원 유적 |
| 11 | `johnnie-fox.jpg` | 조니 폭스 펍 |

## 💡 사진 가이드

- **권장 비율:** 4:3 (가로:세로) — 카드가 4:3으로 표시됨
- **권장 크기:** 가로 800~1200px 정도 (너무 크면 페이지가 무거워짐)
- **확장자:** `.jpg` 권장 (`.png`, `.webp` 도 가능하지만 코드 수정 필요)
- **파일명:** 소문자 + 하이픈(-) 사용 · 한글·공백·특수문자 X

## 🆕 사진이 없는 곳은?

자동으로 "📷 사진 준비 중" 플레이스홀더가 표시되며, 어떤 파일명으로 저장해야 하는지 알려줍니다. 천천히 채워나가면 됩니다.

각 destination의 `places: []` 배열을 채울 때마다 필요한 파일명이 자동으로 결정됩니다.
