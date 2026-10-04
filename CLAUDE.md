# surf-the-world

"세상 읽기" 데일리 브리핑 사이트 저장소. GitHub Pages(Jekyll)로 배포된다.

- 브리핑을 쓰거나 고칠 때는 먼저 `BRIEFING_GUIDE.md`(형식과 규칙)와 `SOURCES.md`(출처 등급)를 읽고 그대로 따른다.
- 브리핑은 `_posts/YYYY-MM-DD-briefing.md`에 하루 한 편. 날짜는 한국 시간(Asia/Seoul) 기준.
- `tracking.md`(진행 중인 이슈)와 `glossary.md`(용어집)는 브리핑과 같은 커밋에서 갱신한다.
- `main`에 직접 커밋·푸시한다. 푸시하면 Pages가 자동으로 다시 빌드한다. 강제 푸시는 하지 않는다.
- 커밋은 저장소 주인 계정으로 남긴다. 커밋 전에 아래 두 줄을 실행하고, 커밋 메시지에 `Co-Authored-By`, `Claude-Session` 같은 Claude 표기 줄을 넣지 않는다.
  - `git config user.name "seongkyu-lim"`
  - `git config user.email "55138532+seongkyu-lim@users.noreply.github.com"`
- 공개 저장소다. 독자 개인의 정보(자산, 가족, 건강 등)는 어떤 파일에도 쓰지 않는다.
- `README.md`, `docs/`, `BRIEFING_GUIDE.md`, `SOURCES.md`는 사이트로 빌드되지 않는다. 이 파일들에는 Liquid 문법(`{{ }}`)을 써도 된다.
- 사이트 주소: https://seongkyu-lim.github.io/surf-the-world/
