## 컨벤져스에서 쓰는 법 (convengers 브랜치 안내)

디자인 비전문가가 PRD를 들고 오면 질문과 시안 비교로 취향을 뽑아 Figma 화면까지 만들고 검사하는 디자인 하네스입니다. 하네스톤 2회차 결과를 모은 본판입니다. 실제 파일은 `apps/harness/` 안에 있습니다.

1. `convengers/skills/oss-design-harness/` 를 키트의 `plugins/convengers/skills/` 로 복사합니다(LICENSE 파일도 같이 들어 있습니다).
2. `convengers/agents/` 의 세 에이전트(figma-builder, design-auditor, probe-renderer)를 키트의 `plugins/convengers/agents/` 로 복사합니다.
3. Figma MCP 연결이 있어야 화면 생성 단계가 돕니다. 없으면 HTML 시안 단계까지만 씁니다.
4. 검사 스크립트는 원본 `apps/harness/scripts/` 에 있습니다(파이썬).

주의: 옮긴 스킬 본문 안에서 서로를 부를 때는 원래 짧은 이름(`/update-docs`, `/brief` 같은)을 그대로 씁니다. 키트에서 이름 앞에 붙인 접두어와 안 맞으니, 키트에 넣을 때 본문의 호출 이름을 새 이름으로 맞춰야 바로 돕니다.

키트와 붙이는 자세한 자리는 [`convengers/연결.md`](convengers/연결.md) 에 적었습니다.

원저작: VIBE MAFIA CLUB (https://github.com/vibemafiaclub/oss-design-harness). 라이선스는 원본 LICENSE 파일(MIT) 그대로입니다. 원본에는 맨 위 README가 없어서 이 파일은 새로 만들었습니다. 원본 안내는 `apps/harness/README.md`, 라이선스는 `apps/harness/LICENSE` 에 그대로 있습니다.

---

