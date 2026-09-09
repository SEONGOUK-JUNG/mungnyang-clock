# 멍냥시계 (Mungnyang Clock)

강아지·고양이 캐릭터가 사료 알갱이 분침을 한 알씩 밀어 시간을 맞추고, 밥·산책 시간을 챙겨 주는 반려동물 시계.
화상디자인 등록출원 30-2026-0034331 (2026-09-08, 정성욱). 무단 복제·모방 금지.

- `index.html` — PC용 소개 페이지 (아이폰 틀 안에 앱 표시), 좁은 화면은 `/app` 으로 이동
- `app.html` — 앱 본체 (단일 파일, 서버 없음)
- `privacy.html`, `support.html`, `manifest.json`, `icons/`
- 배포: Cloudflare Workers 정적 자산 → https://mungnyang-clock.koreagwangju.workers.dev  (`wrangler deploy`)

원본 생성 스크립트는 `Desktop\멍냥시계\build_merged.py` (별도 보관).
