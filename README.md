# 라지공유오피스 (구미)

구평본점 · 형곡점 · 진평점 세 지점을 한 페이지로 소개하는 홍보 사이트.

- 단일 HTML 파일 (`index.html`). 사진과 지도는 webp base64로 파일 안에 들어 있어 외부 이미지 의존이 없다.
- 서체만 Google Fonts(Noto Serif KR · IBM Plex Sans KR)를 쓰고, 로드 실패 시 시스템 폰트로 떨어진다.
- 요금·시설 정보 출처는 각 지점 네이버 플레이스 등록 내용.
- 지도는 OpenStreetMap 타일을 받아 톤을 맞춰 렌더한 정적 이미지 (© OpenStreetMap contributors).

## 수정 방법

`index.html` 하나만 고치면 된다. 요금이 바뀌면 각 지점 `<table class="tbl">` 안의 금액과
`#offers` 섹션의 전용석·비상주 금액을 고친다.
