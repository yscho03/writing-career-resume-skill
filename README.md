# 취업·이직을 준비하는 모든 분들, 화이팅입니다!

> 오늘도 이력서 앞에서 고민하는 당신을 진심으로 응원합니다.

---

# 기술 경력서 Claude Skill (writing-career-resume)

경력기술서 · 이력서를 Markdown 포맷으로 작성해주는 Claude Code / Claude Agent Skill.

심사자가 한눈에 파악할 수 있도록 간결하고 임팩트 있는 문서를 생성한다.

## 미리보기

![writing-career-resume 출력 예시](https://raw.githubusercontent.com/yscho03/writing-career-resume-skill/main/docs/preview.jpg)

> 스킬로 생성한 경력기술서 샘플 (Markdown 렌더링 결과)

## 주요 기능

- 최신순 내림차순 경력 정렬
- 기간 옆에 총 기간 `(N개월/N년)` 자동 표기
- **성과(팀)** 와 **역할(개인)** 의 명확한 구분
- 개조식 문체 강제 (`~하였음`, `~처리함`)
- 기술 스택 중요도 순 정렬
- 지원 회사 자격요건/우대사항 맞춤 경력서 작성
- 작성 체크리스트로 품질 검증

## 설치

### Claude Code

`skills/writing-career-resume` 디렉토리를 Claude Code가 인식하는 스킬 경로에 복사한다.

**사용자 전역 스킬 (macOS / Linux):**

```bash
cp -r skills/writing-career-resume ~/.claude/skills/
```


**프로젝트 전용 스킬:**

프로젝트 루트의 `.claude/skills/` 디렉토리 아래에 복사한다.

```bash
mkdir -p .claude/skills
cp -r skills/writing-career-resume .claude/skills/
```

### 사용 방법

스킬 설치 후 Claude에게 자연어로 요청하면 자동으로 스킬이 호출된다.

예시 프롬프트:
- "경력기술서 써줘"
- "이력서 마크다운으로 작성해줘"
- "이 회사 자격요건에 맞춰 경력서 수정해줘"

## 디렉토리 구조

```
writing-career-resume-skill/
├── README.md
├── docs/
│   └── preview.jpg
└── skills/
    └── writing-career-resume/
        └── SKILL.md
```

## 저작권 및 라이선스

- **작성자**: 조연섭 (yscho03.developer@gmail.com)
- **블로그**: <https://yscho03.tistory.com>
- **Threads 원문 포스트**: <https://www.threads.com/@devninja03/post/DWQtpYXAers?xmt=AQF0mfwqBwbwQcVPLaYlAViPaXoCKCkbkS-vtZrMJguhuQ>

---
본 스킬은 **무료로 자유롭게 배포·수정·사용** 가능합니다. <br>
블로그, 사내 공유 등 어디든 자유롭게 배포 가능합니다. <br>
다만 위 Threads 원문과 원작자를 함께 명시해주시면 감사하겠습니다. <br>
