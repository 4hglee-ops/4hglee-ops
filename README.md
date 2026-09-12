<table>
<tr>
<td width="65%" valign="top">

# Hi, I'm Honggyu Lee 👋

AI · Data · Product를 연결해 **실제로 동작하는 서비스와 협업 도구**를 만들고 있습니다.

최근에는 단순히 AI 기능을 붙이는 것보다, **대화·결정·코드·프로젝트 상태를 근거(Evidence)와 함께 연결하고 AI가 안전하게 읽고 실행할 수 있는 구조**에 관심을 두고 있습니다.

- 🧠 **AI Application** — RAG · LLM workflow · MCP · Evidence-aware AI
- 🔌 **AI Collaboration Infrastructure** — OAuth · ACL · GitHub Projects · Discord Context
- 🛠️ **Product Engineering** — Next.js · React · TypeScript · FastAPI · Supabase · Vercel
- 📊 **Data / ML** — Python · SQL · scikit-learn · PyTorch · validation design

</td>
<td width="26%" align="center" valign="top">

<img src="./github_readme_profile.png" width="260" alt="Honggyu Lee" />

</td>
</tr>
</table>

---

## 🌌 Current Focus — AI가 팀의 상태와 근거를 이해하도록 만들기

### 🛡️ Gyuniverse GitHub Projects MCP `Open Source · MCP · TypeScript`

GitHub Projects v2를 ChatGPT·Claude 같은 AI에서 **조회·분석·안전하게 변경·검증·감사**할 수 있도록 연결하는 MCP 서버입니다.

- Viewer / Member / Admin + capability 기반 ACL
- OAuth · DCR · PKCE · owner / Project allowlist
- Status / Priority · relationship · bulk Preview → Approval → Apply
- mutation 후 re-read verification + durable audit
- Vercel + Upstash 기반 Remote MCP / GPT Actions
- 공개 전 Git history privacy·secret 검증 및 **249 / 249 regression tests** 통과

👉 [gyuniverse-github-projects-mcp](https://github.com/4hglee-ops/gyuniverse-github-projects-mcp)

### 💬 Gyuniverse Discord Bridge `Open Source · MCP · Read-only Context`

Discord 대화를 AI가 안전하게 읽고 검색하도록 연결해, 단순 요약이 아니라 **결정·진행상황·Blocker·변경사항을 근거 중심으로 해석**할 수 있도록 만든 Read-only Context Bridge입니다.

- Channel / Recent Message / History Search
- Team Context Snapshot · Decision / Brief / Delta
- Signed Team State Checkpoint + deterministic diff
- Remote MCP · OAuth DCR + PKCE · GPT Actions
- Discord write/edit/delete 기능은 의도적으로 제공하지 않음

👉 [gyuniverse-discord-bridge](https://github.com/4hglee-ops/gyuniverse-discord-bridge)

---

## 🚀 Product & Team Projects

### 🏛️ 나라장터 변경공고 대응형 입찰 제출 검증기 `Team Project · LLM/RAG · Collaboration Infrastructure`

기존 공고를 기준으로 준비한 자격판정·필수서류·제출 상태가 **변경공고 이후에도 유효한지 다시 검증**하고, 변경된 조건과 원문 근거를 연결하는 팀 프로젝트입니다.

- 변경공고 Version / Requirement Diff
- LLM/RAG Requirement Extraction · Evidence
- deterministic qualification rule + Ask-back
- Frontend ↔ Backend ↔ LLM/RAG 통합 기준선 운영
- GitHub Projects · Discord Bridge 등 협업 인프라 설계/운영

👉 [gyuniverse-hq/bid-change-validator](https://github.com/gyuniverse-hq/bid-change-validator)

### 🧠 CHANGELOG — Personal Evidence AI `Building · Personal · AI/Product`

AI 대화 · 문서 · GitHub에 흩어진 기록을 연결해 **무엇을 했는가뿐 아니라 왜 그렇게 판단했는가까지 복원**하는 Evidence 기반 개인 기록 시스템입니다.

- Discussion → Decision → Documentation → Implementation → Verification
- Semantic Evidence · Change Set · Relation Candidate
- 기록을 단순 보관하는 것을 넘어 관계·패턴·변화를 탐색하는 방향으로 확장 중

👉 [CHANGELOG Public Showcase](https://github.com/4hglee-ops/changelog-showcase)

### ✅ Flowin — AI-assisted Personal Work System `Building · Personal`

생각나는 내용을 Capture하고 AI로 정리해 **지금 무엇을 해야 하는지에 집중하도록 돕는 개인 작업 관리 시스템**입니다.

- Quick Capture → Inbox → AI 정리 → Today / Focus
- Next.js · TypeScript · Supabase · PostgreSQL
- 실제 사용 흐름을 기준으로 UX와 정보 구조를 반복 개선

👉 [Flowin Public Showcase](https://github.com/4hglee-ops/flowin-showcase)

---

## 📊 Selected Data / ML Projects

### ⚽ European Football Goal Prediction `Personal · ML/DL`

유럽 5대 리그 선수의 **다음 시즌 Big5 득점 수**를 예측하는 시계열 ML/DL 프로젝트입니다.

- Walk-forward · Nested HPO · Two-stage modeling
- 2025-26 Locked Test: **926 players · MAE 2.003**
- Big5 잔류 분류: **ROC-AUC 0.907 · Macro F1 0.814**

👉 [european-football-goal-prediction](https://github.com/4hglee-ops/european-football-goal-prediction)

### 🍽️ Yelp Reviewer Retention Ops `Team Project · Team Lead`

핵심 리뷰어의 다음 연도 **활동 유지·약화·중단을 예측하고 운영자의 다음 행동까지 연결**한 리텐션 운영 프로젝트입니다.

**My role** — 팀장 · 프로토타입 설계/구현 · 공통 데이터 규격/서비스 통합 · 운영 UI/UX 및 제품 문서 체계화

👉 [SKN34 2nd Team Project](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN34-2nd-5Team) · [Personal DL Experiment](https://github.com/4hglee-ops/yelp-retention-deep-learning)

### 🚗 Car-BTI `Team Project · Data / DB`

전국 자동차 등록 통계를 분석해 지역별 자동차 소비 성향을 시각화하고 차량 추천·뉴스·FAQ·AI 챗봇까지 연결한 팀 프로젝트입니다.

**My role** — 차량 등록 데이터 추출/전처리 · MySQL DB 설계/구축 · 지역별 차량 특성 통계 데이터 구성

👉 [SKN34 1st Team Project](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN34-1st-3Team) · [Car-BTI Data Pipeline](https://github.com/4hglee-ops/car-bti-data-pipeline)

### More

- **Titanic Survival Prediction** — Feature Engineering · leakage-safe validation · Decision Log  
  👉 [titanic-survival-prediction](https://github.com/4hglee-ops/titanic-survival-prediction)
- **Online Shoppers Conversion ML** — 쇼핑 세션 구매 전환 예측 · Streamlit 실험 대시보드  
  👉 [online-shoppers-conversion-ml](https://github.com/4hglee-ops/online-shoppers-conversion-ml)
- **Python Coding Test Study** — 직접 구현 → 반례 → 디버깅 → 리팩터링 중심 학습 기록  
  👉 [python](https://github.com/4hglee-ops/python)

---

## 🧭 What I'm Building & Learning

| Area | Current Focus |
| --- | --- |
| AI Product | RAG · Evidence retrieval · AI Copilot · evaluation |
| MCP / Integration | Remote MCP · OAuth · DCR · PKCE · GPT Actions · authorization |
| Product Engineering | Next.js · React · TypeScript · FastAPI · Supabase · Vercel |
| Data / ML | Classification · Regression · Feature Engineering · validation design |
| Collaboration | GitHub Projects · PR workflow · Discord context · decision / audit trail |
| Algorithm | Python · Programmers · problem solving |

---

## 🧰 Tech

**Language / Data**  
`Python` · `TypeScript` · `SQL` · `Pandas` · `NumPy`

**AI / ML**  
`scikit-learn` · `PyTorch` · `RAG` · `MCP`

**Product / Backend**  
`Next.js` · `React` · `FastAPI` · `Supabase` · `PostgreSQL` · `MySQL` · `SQLite`

**Infra / Workflow**  
`Git` · `GitHub` · `Vercel` · `Docker` · `Upstash` · `Jupyter Notebook` · `Streamlit`

---

## 📌 How I Work

```text
Problem / Idea
      ↓
Define what matters
      ↓
Design / Implement
      ↓
Connect the whole flow
      ↓
Test with real data or users
      ↓
Find failure cases
      ↓
Improve
      ↓
Document what changed and why
```

결과만 남기기보다 **왜 그렇게 설계했는지, 무엇이 실패했고 어떻게 개선했는지, 다음 판단에 어떤 근거를 남길지**를 중요하게 생각합니다.

---

### Keep building. Keep learning.
