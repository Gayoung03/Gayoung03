## Hi there 👋

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0B6B3A,50:16A05D,100:7CB342&height=210&section=header&text=KWON%20GAYEONG&fontSize=42&fontColor=FFFFFF&fontAlignY=35&desc=AI%20%2F%20DATA%20%2F%20AGENT%20ENGINEER&descAlignY=56&descSize=16&animation=fadeIn"/>

<img
src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=1000&color=63D297&center=true&vCenter=true&width=850&lines=Building+AI+systems+that+work+in+real+workflows.;Data+Pipeline+%C2%B7+RAG+%C2%B7+LLM+%C2%B7+Multi-Agent;From+problem+definition+to+working+systems."
/>


<a href="mailto:ooo7852@mju.ac.kr">
  <img src="https://img.shields.io/badge/Email-Contact%20Me-0B6B3A?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/Gayoung03">
  <img src="https://img.shields.io/badge/GitHub-Gayoung03-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>


</div>

---

## 👩🏻‍💻 About Me

> #### **문제를 먼저 정의하고, 기준을 세운 뒤, 데이터와 AI가 실제 흐름 안에서 작동하도록 연결합니다.**

저는 단순히 모델을 구현하는 것보다
**문제 정의 → 데이터 구성 → 모델 및 LLM → 평가 → 서비스 흐름 연결**까지 이어지는 과정을 중요하게 생각합니다.

I build AI systems by defining the problem first, establishing reliable data and evaluation criteria, and connecting **data pipelines, ML models, LLMs, RAG, and Agents** into working product flows.

<br/>

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

## 🛠️ Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,typescript,javascript"/>
</p>

`Python` `TypeScript` `JavaScript`

<br/>

### AI / Machine Learning / Data

#### Data & ML

`Pandas` `NumPy` `Scikit-learn` `LightGBM` `ARIMA` `SHAP`

#### LLM & Agent

`OpenAI API` `LangChain` `LangGraph` `CrewAI`

#### AI Engineering

`RAG` `LLM Judge` `Prompt Engineering` `Vector Search`

<br/>

### Backend & Database

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,django,mongodb"/>
</p>

`FastAPI` `Django` `MongoDB` `MongoDB Atlas Vector Search`

<br/>

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,typescript"/>
</p>

`React` `TypeScript`

<br/>

### Cloud / DevOps / Tooling

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,git,github,githubactions"/>
</p>

`AWS` `Docker` `GitHub Actions` `Apache Airflow` `pytest` `Streamlit`

---

## 🚀 Featured Projects

<div align="center">

#### From **Data Pipeline** to **AI Agent Workflow**

</div>

---

<details>
<summary><h4>01. 꽃보다 특허 — AI Patent Writing Platform</h4></summary>

<br/>

> **전문 도메인 문서를 LLM Agent가 생성하고 검수하도록 설계한 AI 특허 작성 플랫폼**

#### At a Glance

|                |                                                                                    |
| -------------- | ---------------------------------------------------------------------------------- |
| **Role**       | Frontend / AI Agent Integration                                                    |
| **AI**         | LangGraph · OpenAI · LLM Judge                                                     |
| **Stack**      | React · Django · FastAPI · pytest · Docker                                         |
| **Deployment** | AWS EC2                                                                            |
| **CI/CD**      | GitHub Actions                                                                     |
| **Validation** | Patent Attorney Feedback                                                           |
| **Repository** | [SKN25-FINAL-3Team](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN25-FINAL-3Team) |

#### Problem

특허 명세서와 청구항은 단순히 자연스러운 문장을 생성하는 것만으로 품질을 판단하기 어려운 **전문 도메인 문서**입니다.

따라서 실제 특허 문서의 구조와 필수 요소를 분석하고, 생성 결과를 객관적으로 비교·검수할 수 있는 평가 흐름이 필요했습니다.

#### What I Did

* 실제 특허 문서를 분석하여 **명세서 공통 구조와 필수 요소 정의**
* 생성 결과와 실제 특허 문서를 **LLM Judge 기반으로 비교 평가**
* 평가 결과를 기반으로 프롬프트 반복 개선
* 명세서 Agent와 React UI 연동
* 청구항 단독 심사 기능 구현
* 사용자 편의 기능 구현
* `pytest` 기반 기능 검증
* AWS EC2 배포 및 GitHub Actions 연결

#### Result

> **LLM 생성 → 평가 → 사용자 검토까지 이어지는 특허 작성 Workflow 구현**

실제 서비스 형태로 배포 및 시연했으며,
**변리사 피드백**을 통해 전체 프로세스의 가능성과 다른 전문 분야로의 확장 가능성, Agent 고도화 방향을 확인했습니다.

</details>

---

<details>
<summary><h4>02. 지방소멸 레이더 — Regional Extinction Risk Prediction</h4></summary>

<br/>

> **분산된 국가 데이터를 통합해 지역별 소멸 위험과 주요 영향 요인을 예측한 ML 프로젝트**

#### At a Glance

|                    |                                                                                |
| ------------------ | ------------------------------------------------------------------------------ |
| **Role**           | PM · Planning · Data Collection · Preprocessing · ML                           |
| **Scale**          | **69 Variables**                                                               |
| **Model**          | ARIMA · LightGBM                                                               |
| **Explainability** | SHAP                                                                           |
| **Service**        | Streamlit                                                                      |
| **Score**          | **97 / 100**                                                                   |
| **Repository**     | [SKN25-2nd-2Team](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN25-2nd-2Team) |

#### Problem

국가 데이터가 여러 기관에 분산되어 있었으며 기관마다 컬럼명, 데이터 단위, 시계열 범위, 행정구역 기준이 달라 **데이터 정합성을 맞추는 작업 자체가 핵심 문제**였습니다.

#### What I Did

* 지방소멸 문제를 **데이터 기반 예측 과제**로 기획
* PM으로서 팀 역할 및 우선순위 조정
* **69개 변수** 데이터 수집 및 정제 기준 설계
* 행정구역 변경 사례를 선행 연구 기반으로 정리
* ARIMA 기반 독립변수 시계열 예측
* LightGBM 기반 지역별 소멸 위험 예측
* SHAP 기반 지역별 주요 영향 요인 분석

#### Result

> **69 Variables · ARIMA · LightGBM · SHAP → Score 97 / 100**

**평가 점수 97/100**을 기록했으며,
다양한 공공데이터를 하나의 분석 기준으로 통합하고 **예측 + 설명 가능한 ML 구조**로 연결한 점이 긍정적으로 평가되었습니다.

</details>

---

<details>
<summary><h4>03. AI 냉털봇 — Recipe RAG & ETL Automation</h4></summary>

<br/>

> **레시피 데이터를 자동 수집·적재하고 Vector Search와 LLM으로 추천하는 RAG 서비스**

#### At a Glance

|                |                                                                                |
| -------------- | ------------------------------------------------------------------------------ |
| **Role**       | RAG Pipeline · Data ETL Automation                                             |
| **Data**       | **56K+ Base Recipes**                                                          |
| **Automation** | **Weekly Recipe Synchronization**                                              |
| **Search**     | MongoDB Atlas Vector Search                                                    |
| **RAG**        | LangChain · OpenAI                                                             |
| **Pipeline**   | Apache Airflow                                                                 |
| **Repository** | [SKN25-3rd-3Team](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN25-3rd-3Team) |

#### Problem

최신 레시피를 지속적으로 반영하기 위해
**수집 → 중복 확인 → MongoDB 적재 → 검색**
과정을 반복 실행할 수 있는 자동화 구조가 필요했습니다.

또한 기존 ETL 코드는 터미널 환경에서는 정상적으로 실행됐지만, **Airflow 환경에서는 프로세스가 종료되지 않는 문제**가 있었습니다.

#### What I Did

* 신규 레시피 데이터 크롤링
* 기존 MongoDB 데이터와 중복 여부 확인
* MongoDB Atlas Vector DB 적재
* RAG 검색 파이프라인 구현
* 무한 루프 실행 구조를 **Airflow Scheduler 기반 구조로 변경**
* `.env` 상대 경로 의존성을 환경 변수 방식으로 변경
* PythonOperator 기반 DAG 구성

#### Result

> **56K+ Recipe Data → Automated Weekly ETL → Vector Search → RAG**

신규 레시피가 정해진 주기에 따라 자동 수집되고 MongoDB에 적재되는
**주간 데이터 동기화 파이프라인**을 구축했습니다.

</details>

---

<details>
<summary><h4>04. Nickel SCM — Multi-Agent Decision Support System</h4></summary>

<br/>

> **제조업 니켈 구매·재고·통관·물류·품질·재무 프로세스를 여러 AI Agent로 연결한 의사결정 지원 시스템**

#### At a Glance

|                 |                                                                               |
| --------------- | ----------------------------------------------------------------------------- |
| **Role**        | Agent Architecture · Inventory Agent · Data Pipeline · Prompt Design          |
| **Agents**      | **8 Specialized Agents**                                                      |
| **AI**          | OpenAI API · LangChain                                                        |
| **ML**          | Scikit-learn · SHAP                                                           |
| **Vector DB**   | ChromaDB                                                                      |
| **Recognition** | **Grand Prize — AI Capstone Portfolio Competition**                           |
| **Research**    | **KCI-listed Journal Article**                                                |
| **Repository**  | [nickel-scm-multi-agent](https://github.com/Gayoung03/nickel-scm-multi-agent) |

#### Problem

구매, 재고, 통관, 물류, 품질, 재무 등 여러 단계가 연결되는 제조업 SCM 프로세스를
**하나의 AI 시스템 안에서 유기적으로 연결**해야 했습니다.

단일 Agent가 모든 업무를 처리하는 방식보다, 각 업무를 전문 Agent로 분리하고 필요한 Agent가 협력하도록 만드는 구조가 필요했습니다.

#### What I Did

* 사용자 요청에 따라 여러 Agent가 동작하는 **Multi-Agent Architecture 설계**
* 재고 확인 Agent 구현
* 니켈 관련 데이터 수집 및 정제
* Agent별 역할과 프롬프트 설계
* 제조업 현직자 자문 반영
* 특정 기업에 종속되지 않는 ERP형 확장 구조 제안
* ML 가격 예측과 Agent 기반 의사결정 Workflow 연결

#### Result

> **8 Specialized Agents → Procurement Decision Workflow**

가격 예측부터
**재고 확인 → 통관 RAG → 물류 · 품질 · 재무 분석 → 최종 의사결정 리포트**
까지 이어지는 **8-Agent Workflow**를 완성했습니다.

이 프로젝트는 이후 연구로 확장되어
**한국정보기술학회논문지(KCI) 논문으로 게재**되었습니다.

</details>

---

## 📚 Research & Publications

### Multi-AI Agent Framework for Nickel Procurement Decision Support

#### 멀티 AI 에이전트 기반 니켈 조달 의사결정지원시스템 프레임워크 설계 및 개발

> **Multi-Agent System × Supply Chain Management × Decision Support**

|                    |                                                                  |
| ------------------ | ---------------------------------------------------------------- |
| **Journal**        | 한국정보기술학회논문지                                                      |
| **Volume / Issue** | **24(7)**                                                        |
| **Published**      | **July 2026**                                                    |
| **Pages**          | 287–298                                                          |
| **Type**           | **KCI-listed Journal Article**                                   |
| **Focus**          | Multi-Agent System · Nickel Procurement · Decision Support · SCM |

<br/>

[![DBpia](https://img.shields.io/badge/DBpia-View%20Paper-0B6B3A?style=for-the-badge)](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12921490)

---

## 🏆 Achievements

<div align="center">

| Recognition     | Details                                   |
| --------------- | ----------------------------------------- |
| 🥇**Grand Prize** | 명지대학교 AI 캡스톤디자인 포트폴리오 경진대회 · **2025**     |
| 🥉**Third Prize** | 한국디지털콘텐츠학회 하계종합학술대회 대학생 논문경진대회 · **2026** |

</div>

---

## 🐍 Contribution

<div align="center">

<img src="https://raw.githubusercontent.com/Gayoung03/Gayoung03/output/github-contribution-grid-snake-dark.svg" />

</div>

---

## 🎯 Current Focus

<div align="center">

#### Building AI systems that move beyond the demo.

</div>

<br/>

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

## 📬 Connect

<div align="center">

#### Let's build AI systems that work beyond the demo.

<br/>

<a href="mailto:ooo7852@mju.ac.kr">
  <img src="https://img.shields.io/badge/Gmail-ooo7852%40mju.ac.kr-0B6B3A?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/Gayoung03">
  <img src="https://img.shields.io/badge/GitHub-Gayoung03-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

#### Define the problem. Set the criteria. Build until it works.

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7CB342,50:16A05D,100:0B6B3A&height=110&section=footer"/>
