# AI 파고 아카이브 (`ai-pago-archive`)

한 주에 하나, AI 기술을 깊이 파고들어 쉽게 풀어 쓰는 주간 리포트 아카이브입니다.

- 사이트: https://juno99zz-arkt.github.io/ai-pago-archive/
- `index.html` — 아카이브 목록 (`reports/manifest.json`을 읽어 카드로 표시)
- `reports/_template.html` — 리포트 양식
- `reports/*.html` — 발행된 리포트

## 발행 흐름
1. 매주 일요일 20:00, Claude 예약 작업이 주제 후보 5개를 제안
2. 고른 주제를 `/ai-pago 3번` 또는 `/ai-pago <주제>`로 지시
3. 리포트 작성 → `reports/`에 추가, `manifest.json` 갱신 → push → GitHub Pages 반영
