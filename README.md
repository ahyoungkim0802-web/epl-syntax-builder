# EPL Syntax 강의 생성기

영어 본문 → 청크 단위 직독직해 분석 + 인강 녹음용 스크립트 자동 생성

## 배포
1. Cloudflare Worker 생성 → `worker.js` 코드 붙여넣기
2. Worker Secret에 `ANTHROPIC_API_KEY` 등록
3. Worker URL 복사 → `index.html`의 `WORKER_URL` 상수에 입력
4. GitHub Pages: Settings → Pages → main branch → 배포

## 기술 스택
- 단일 HTML (빌드 도구 없음)
- Anthropic Claude API (Cloudflare Worker 경유)
- GitHub Pages 정적 배포

## EPL 영어학원
Empower · Practice · Literacy
