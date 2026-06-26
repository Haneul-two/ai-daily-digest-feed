# ai-daily-digest-feed

매일 아침 생성되는 **AI 다이제스트**의 구조화 피드(공개).
모바일 리더 앱(`ai-digest-reader`)이 토큰 없이 이 repo의 raw JSON을 읽는다.

- `digest-latest.json` — 최신 다이제스트 (앱이 fetch하는 기본 파일)
- `archive/digest-YYYY-MM-DD.json` — 날짜별 보존본

스키마는 ai-digest-reader 스펙 §4를 따른다. 내용은 공개 뉴스 링크·요약뿐이며 민감정보를 담지 않는다.
발행 주체: `☀️ 매일 아침 AI 다이제스트` 클라우드 루틴.
