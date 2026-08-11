## Hi there 👋

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6C3CE8,50:7B4FEA,100:4C6FFF&height=220&section=header&text=KWON%20GAYEONG&fontSize=46&fontColor=FFFFFF&fontAlignY=35&desc=AI%20%2F%20DATA%20%2F%20AGENT%20ENGINEER&descAlignY=56&descSize=18&animation=fadeIn"/>

<img
  src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3000&pause=1000&color=9C7CF4&center=true&vCenter=true&width=850&lines=Building+AI+systems+that+work+in+real+workflows.;Data+Pipeline+%C2%B7+RAG+%C2%B7+LLM+%C2%B7+Multi-Agent;From+problem+definition+to+working+systems."
/>

<br/>

<img src="https://img.shields.io/badge/Myongji%20University-Student-6C3CE8?style=flat-square"/>
<img src="https://img.shields.io/badge/Focus-AI%20%7C%20Data%20%7C%20Agent-7B4FEA?style=flat-square"/>
<img src="https://img.shields.io/badge/Seoul-Korea-4C6FFF?style=flat-square"/>

<br/><br/>

<a href="mailto:ooo7852@mju.ac.kr">
  <img src="https://img.shields.io/badge/Email-Contact%20Me-6C3CE8?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/Gayoung03">
  <img src="https://img.shields.io/badge/GitHub-Gayoung03-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Gayoung03&label=PROFILE+VIEWS&color=7B4FEA&style=flat-square"/>
<img src="https://img.shields.io/github/followers/Gayoung03?label=FOLLOWERS&style=flat-square&color=6C3CE8"/>

</div>

---

## About Me

> **문제를 먼저 정의하고, 기준을 세운 뒤, 데이터와 AI가 실제 흐름 안에서 작동하도록 연결합니다.**

I build AI systems by defining the problem first, establishing reliable data and evaluation criteria, and connecting **data pipelines, ML models, LLMs, RAG, and Agents** into working product flows.

Rather than stopping at model outputs, I focus on the entire process:

- defining reliable **data standards**
- building **data collection and preprocessing pipelines**
- designing **LLM prompts and evaluation criteria**
- connecting AI functionality to **real user workflows**
- automating recurring processes
- validating whether systems work outside the local development environment

```yaml
name: Kwon Gayeong
github: Gayoung03
university: Myongji University

focus:
  - Data Pipeline
  - LLM / RAG
  - AI Agent
  - Machine Learning
  - Workflow Automation

working_style:
  - Define the criteria first
  - Build reproducible pipelines
  - Make AI outputs reviewable
  - Connect models to real workflows
```

---

## Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,typescript,javascript"/>
</p>

### AI / Data

`Python` `Pandas` `NumPy` `Scikit-learn`  
`LightGBM` `ARIMA` `SHAP`  
`OpenAI API` `LangChain` `LangGraph` `CrewAI`  
`RAG` `LLM Judge` `Prompt Engineering`

### Backend & Database

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,django,mongodb"/>
</p>

`MongoDB Atlas Vector Search`

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,typescript"/>
</p>

### Cloud / DevOps / Tooling

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,git,github,githubactions"/>
</p>

`Apache Airflow` `pytest` `Streamlit`

---

## AI / ML Expertise

| Domain | Focus | Experience |
|---|---|---|
| **Data Engineering** | Data Collection & Cleaning | Multi-source data collection, preprocessing, schema alignment and time-series consistency |
| **Machine Learning** | Prediction & Explainability | LightGBM, ARIMA, Scikit-learn, SHAP |
| **LLM Engineering** | Prompt & Evaluation | Prompt design, LLM Judge, domain-specific evaluation criteria |
| **RAG** | Retrieval Pipeline | MongoDB Atlas Vector Search, LangChain, OpenAI |
| **AI Agents** | Multi-Agent Workflow | CrewAI, LangGraph, task-oriented Agent orchestration |
| **Automation** | Data Pipeline | Airflow-based recurring collection and ingestion workflows |
| **Product Integration** | AI → Service | React, Django and FastAPI integration with AI features |

---

# Featured Projects

<details>
<summary><b>01. 꽃보다 특허 — AI Patent Writing Platform</b></summary>

<br/>

> 전문 도메인 문서를 LLM Agent가 생성하고 검수하도록 설계한 AI 특허 작성 플랫폼

| | |
|---|---|
| **Role** | Frontend / AI Agent Integration |
| **Stack** | React, Django, FastAPI, LangGraph, OpenAI, pytest, Docker |
| **Deployment** | AWS EC2 |
| **CI/CD** | GitHub Actions |
| **Focus** | Patent specification generation, claim examination, LLM evaluation |
| **Validation** | Patent attorney feedback |
| **Repository** | [SKN25-FINAL-3Team](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN25-FINAL-3Team) |

### Problem

특허 명세서와 청구항은 단순히 자연스러운 문장을 생성하는 것만으로 품질을 판단하기 어려운 전문 도메인 문서였습니다.

### What I Did

- 실제 특허 문서를 검토하여 명세서의 공통 구조와 필수 요소 정리
- 생성된 결과와 실제 특허 문서를 **LLM Judge**로 비교
- 비교 결과를 기반으로 프롬프트 개선
- 명세서 Agent와 React 화면 연동
- 청구항 단독 심사 기능 구현
- 사용자 편의 기능 구현
- `pytest` 기반 기능 검증
- AWS EC2 배포 및 GitHub Actions 연결

### Result

실제 서비스 형태로 배포 및 시연했으며, 변리사 피드백을 통해 전체 프로세스의 가능성과 분야 확장 및 Agent 고도화 방향을 확인했습니다.

</details>

---

<details>
<summary><b>02. 지방소멸 레이더 — Regional Extinction Risk Prediction</b></summary>

<br/>

> 분산된 국가 데이터를 통합해 지역별 소멸 위험과 주요 영향 요인을 예측한 ML 프로젝트

| | |
|---|---|
| **Role** | PM, Planning, Data Collection, Preprocessing, ML |
| **Scale** | 69 variables |
| **Stack** | Python, Pandas, ARIMA, LightGBM, SHAP, Streamlit |
| **Score** | **97 / 100** |
| **Repository** | [SKN25-2nd-2Team](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN25-2nd-2Team) |

### Problem

국가 데이터가 여러 기관에 분산되어 있었으며 기관별 컬럼명, 단위, 행정구역 기준이 달라 시계열 데이터의 정합성을 맞추는 것이 주요 문제였습니다.

### What I Did

- 지방소멸 문제를 데이터 기반 예측 과제로 기획
- PM으로서 팀 역할 및 우선순위 조정
- 데이터 수집·정제 기준 설계
- 행정구역 변경 사례를 선행 연구 기반으로 정리
- ARIMA 기반 독립변수 시계열 예측
- LightGBM 기반 소멸 위험 예측
- SHAP 기반 지역별 주요 영향 요인 분석

### Result

**평가 점수 97/100**을 기록했으며, 69개 변수 구성과 ARIMA · LightGBM · SHAP을 결합한 예측 및 설명 구조가 긍정적으로 평가되었습니다.

</details>

---

<details>
<summary><b>03. AI 냉털봇 — Recipe RAG & ETL Automation</b></summary>

<br/>

> 레시피 데이터를 자동으로 수집·적재하고 Vector Search와 LLM을 이용해 추천하는 RAG 서비스

| | |
|---|---|
| **Role** | RAG Pipeline / Data ETL Automation |
| **Stack** | Airflow, MongoDB Atlas, FastAPI, LangChain, OpenAI |
| **Data** | 56K+ base recipe data |
| **Automation** | Weekly recipe synchronization |
| **Repository** | [SKN25-3rd-3Team](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN25-3rd-3Team) |

### Problem

최신 레시피를 지속적으로 반영하기 위해 신규 데이터를 중복 없이 수집하고 MongoDB에 적재하는 자동화 구조가 필요했습니다.

기존 ETL 코드는 터미널에서는 동작했지만 Airflow 환경에서는 종료되지 않는 문제가 있었습니다.

### What I Did

- 신규 레시피 데이터 크롤링
- 기존 MongoDB 데이터와 중복 여부 확인
- MongoDB Atlas Vector DB 적재
- RAG 검색 파이프라인 구현
- 무한 루프 기반 실행 방식을 Airflow Scheduler 구조로 변경
- `.env` 상대 경로 의존성을 환경 변수 방식으로 변경
- PythonOperator 기반 DAG 구성

### Result

신규 레시피가 정해진 주기에 따라 자동 수집되고 MongoDB에 적재되는 **주간 데이터 동기화 파이프라인**을 구축했습니다.

</details>

---

<details>
<summary><b>04. Nickel SCM — Multi-Agent Decision Support System</b></summary>

<br/>

> 제조업 니켈 구매·재고·통관·물류·품질·재무 프로세스를 여러 AI Agent로 연결한 의사결정 지원 시스템

| | |
|---|---|
| **Role** | Agent Architecture, Inventory Agent, Data Pipeline, Prompt Design |
| **Agents** | **8 specialized agents** |
| **Stack** | Streamlit, Scikit-learn, SHAP, OpenAI API, ChromaDB, LangChain |
| **Recognition** | Myongji University AI Capstone Portfolio Competition — Grand Prize |
| **Repository** | [nickel-scm-multi-agent](https://github.com/Gayoung03/nickel-scm-multi-agent) |

### Problem

구매, 재고, 통관, 물류, 품질, 재무 등 여러 단계가 연결되는 제조업 SCM 프로세스를 하나의 AI 시스템으로 구성해야 했습니다.

### What I Did

- 사용자 요청에 따라 여러 Agent가 동작하도록 연결 구조 설계
- 재고 확인 Agent 구현
- 니켈 관련 데이터 수집 및 정제
- Agent별 프롬프트 설계
- 제조업 현직자 자문 반영
- 특정 기업에 종속되지 않는 ERP형 확장 구조 제안
- ML 가격 예측과 Agent 기반 의사결정 흐름 연결

### Result

가격 예측부터 재고 확인, 통관 RAG, 최종 의사결정 리포트까지 이어지는 **8-Agent Workflow**를 완성했습니다.

> This project was further developed into a journal paper published in the Journal of Korean Institute of Information Technology.

</details>

---

# Research & Publications

### Multi-AI Agent Framework for Nickel Procurement Decision Support

**멀티 AI 에이전트 기반 니켈 조달 의사결정지원시스템 프레임워크 설계 및 개발**

- **Authors:** 김선오 · 유지현 · 권가영
- **Journal:** 한국정보기술학회논문지
- **Volume / Issue:** 24(7)
- **Published:** July 2026
- **Pages:** 287–298
- **Type:** KCI-listed Journal Article
- **Focus:** Multi-Agent System · Nickel Procurement · Decision Support · Supply Chain Management

[![DBpia](https://img.shields.io/badge/DBpia-View%20Paper-6C3CE8?style=for-the-badge)](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12921490)

---

# Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🥇 **최우수상** | 명지대학교 AI 캡스톤디자인 포트폴리오 경진대회 · **2025.12.15** |
| 🥉 **동상** | 2026 한국디지털콘텐츠학회 하계종합학술대회 대학생 논문경진대회 · **2026.07.03** |

</div>

> **Note:** 한국디지털콘텐츠학회 대학생 논문경진대회 동상은 위 한국정보기술학회 게재 논문과 별개의 연구 성과입니다.

---

# Certifications

### Data

<img src="https://img.shields.io/badge/ADsP-Data%20Analysis%20Semi--Professional-6C3CE8?style=for-the-badge"/>

### Programming

<img src="https://img.shields.io/badge/PCCE-Level%203-7B4FEA?style=for-the-badge"/>

### Office / Productivity

<img src="https://img.shields.io/badge/Computer%20Specialist-Level%202-4C6FFF?style=for-the-badge"/>

---

# GitHub Analytics

<div align="center">

<img
  height="170"
  src="https://github-readme-stats.vercel.app/api?username=Gayoung03&show_icons=true&hide_border=true&theme=tokyonight&rank_icon=github"
/>

<img
  height="170"
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gayoung03&layout=compact&hide_border=true&theme=tokyonight"
/>

</div>

<br/>

<div align="center">

<img
  src="https://streak-stats.demolab.com?user=Gayoung03&theme=tokyonight&hide_border=true"
/>

</div>

---

# GitHub Trophies

<div align="center">

<img
  src="https://github-profile-trophy.vercel.app/?username=Gayoung03&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=6"
/>

</div>

---

# Contribution Activity

<div align="center">

<img
  src="https://github-readme-activity-graph.vercel.app/graph?username=Gayoung03&theme=tokyo-night&hide_border=true&area=true"
/>

</div>

---

# Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Gayoung03/Gayoung03/output/github-contribution-grid-snake-dark.svg" />

</div>

---

# Current Focus

```yaml
learning:
  - Advanced Agent Orchestration
  - RAG Evaluation
  - Production AI Systems

building:
  - AI Agent Workflows
  - Data Automation Pipelines
  - LLM-based Products

exploring:
  - Multi-Agent Systems
  - Reliable LLM Evaluation
  - Workflow Automation

open_to:
  - AI Engineering
  - Data Engineering
  - AI Agent Projects
  - Research Collaboration
```

---

# Connect

<div align="center">

### Let's build AI systems that work beyond the demo.

<a href="mailto:ooo7852@mju.ac.kr">
  <img src="https://img.shields.io/badge/Gmail-ooo7852%40mju.ac.kr-6C3CE8?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/Gayoung03">
  <img src="https://img.shields.io/badge/GitHub-Gayoung03-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

<br/>

<div align="center">

> **Define the problem. Set the criteria. Build until it works.**

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4C6FFF,50:7B4FEA,100:6C3CE8&height=120&section=footer"/>
