---
name: planning-prd
description: 선택된 아이디어로 1-Pager PRD와 PRD 초안을 만든다(Step 8·9). "PRD", "기획서", "1-Pager", "MVP 정의", "제품 요구사항", "기능 스펙" 같은 요청에 사용한다.
---

# Step 8·9 — PRD

**역할: "SaaS PM 10년차"**

## 입력

선택된 아이디어 + 모든 이전 단계 결과. 하네스 실행 중이면 `01`~`04` 파일을 읽어 맥락(문제·페르소나·Journey·NSM·Aha·AARRR)을 모은다.

## 작업

### Step 8 — 1-Pager PRD

다음 템플릿으로 한 페이지 요약:

```markdown
# [서비스명] 1-Pager v0.1

## 작성자 · 날짜

1. 한 줄 요약
2. 문제 정의
3. 타깃 페르소나 · JTBD (이름 / 나이 / 직업 / JTBD 한 문장)
4. North Star Metric
5. Aha Moment
6. MVP 기능 (1~2개) (기능1 — 한 줄, 기능2 — 한 줄)
7. 안 할 것 (Out of Scope) (v2 이후 / v3 이후)
8. 성공 기준 (D7 잔존 _% / Aha _% / CSAT \_/5)
9. 열린 질문 3개
```

### Step 9 — PRD 초안

1-Pager를 펼친 상세 문서. 마크다운 + 표 적극 활용. 기능 요구사항 표 포함.

**제약 (반드시 지킴)**:

- 성공 기준은 **반드시 숫자**
- Out of Scope **최소 3개**
- 열린 질문 **3개**

**검증**: 마지막에 **불확실도 `★`~`★★★`**를 **각 섹션별로** 표시한다.

## 출력

1-Pager PRD + PRD 초안을 한 문서로.

**파일 저장**: 하네스 실행 중이면 `planning-output/YYYYMMDD-[slug]/05-prd.md` 에 저장. 복수 아이디어면 아이디어별 섹션 또는 별도 파일로 분리한다.
