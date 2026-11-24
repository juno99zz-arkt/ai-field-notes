# AI Field Notes (`ai-field-notes`)

초심자의 눈으로, 매주 하나씩 AI를 깊이 들여다본 기록입니다.

- 사이트: https://juno99zz-arkt.github.io/ai-field-notes/
- `index.html` — 노트 목록 (`reports/manifest.json`을 읽어 카드로 표시)
- `reports/_template.html` — 리포트 양식
- `reports/*.html` — 발행된 노트

## 발행 흐름
1. 매주 일요일 20:00, Claude 예약 작업이 주제 후보 5개를 제안
2. 고른 주제를 `/field-notes 3번` 또는 `/field-notes <주제>`로 지시
3. 리포트 작성 → `reports/`에 추가, `manifest.json` 갱신 → push → GitHub Pages 반영
