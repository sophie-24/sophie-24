<h1 align="center">Kyuri Kim</h1>

<p align="center">
  <b>Spring Boot와 FastAPI로 설계하고, 배포와 운영까지 책임지는 백엔드 엔지니어</b><br/>
  <sub>"왜 이 데이터가 이렇게 흐르는가", "어디에서 시스템이 느려지는가"를 근거로 확인하며 개발합니다.</sub>
</p>

<p align="center">
  <a href="https://bit.ly/gyuri_portfolio"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=notion&logoColor=white" /></a>
  <a href="https://velog.io/@gyuri0504/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=velog&logoColor=white" /></a>
  <a href="mailto:sophia.gyuri@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

<br/>

## 🏆 Awards

| 대회 | 성과 | 규모 |
|---|---|---|
| **서울 AI 해커톤** <sub>서울AI재단 × AWS</sub> | 🥇 **서울 AI재단 이사장상** | 122팀 → 본선 20팀 |
| **데이터안심구역 활용 공동 경진대회** <sub>과기정통부 · 국토교통부</sub> | 🥈 **우수상** | 138팀 → 17팀 선정 · **17팀 중 유일한 1인 개발** |
| **SOPKATHON** <sub>SOPT</sub> | 🥇 **대상** | 1박 2일 해커톤 |
| **SOPT APPJAM** <sub>SOPT</sub> | 🥇 **대상** | 2주 합숙 · 앱 출시 목표로 스프린트 진행 중 |

<br/>

## 📋 About Me

- 🎓 **동국대학교 컴퓨터공학** 전공 재학
- ⚙️ **Spring Boot**와 **FastAPI** 양쪽으로 서비스를 설계하고 배포까지 해왔습니다. 도메인과 팀 상황에 맞는 스택을 고르는 판단 자체를 중요하게 생각합니다.
- 📊 API를 붙여 빠르게 띄우는 것을 넘어, **데이터가 생성·저장·가공되어 사용자 가치로 이어지는 흐름**을 설계하고 싶습니다.
- 🛡️ **AI를 신뢰할 수 없는 컴포넌트로 취급합니다.** LLM은 후보 생성에 쓰고, 완료·안전·판정 조건은 결정론적 상태와 검증된 데이터로 분리합니다.
- 🤝 여러 프로젝트에서 **팀장 · 개발리드**를 맡았고, Android·기획·디자인 파트와 API 명세·데이터 형식을 조율하며 제품을 완성해 왔습니다.
- 📈 **측정하고 개선합니다.** 아래 프로젝트의 성과는 전부 개선 전후를 직접 계측한 수치입니다.

<br/>

## 🚀 Projects

| 프로젝트 | 소개 | 핵심 성과 | 기술 |
|---|---|---|---|
| **[HAPHAP](https://github.com/team-haphap/haphap-server)** <br/><sub>SOPT APPJAM · 2주 합숙</sub> | 채용 공고 전형 일정을 캘린더로 관리하는 모바일 서비스 백엔드 | **Blue/Green 무중단 배포 + 관측성 구축**<br/>명세·문서·코드 **3-way 검증으로 17개 API** 스키마 보강<br/>Redis `ZINCRBY` 원자 연산으로 락 없는 조회수 집계 | `Java 21` `Spring Boot 3.5` `PostgreSQL` `Redis` `Docker` `Nginx` `Prometheus` `Grafana` |
| **[Tubify](https://github.com/sophie-24/SWproject-Team2-m)** <br/><sub>개발리드 · Chrome Web Store 출시</sub> | 유튜브 영상을 교차 분석해 광고성 콘텐츠를 걸러내고 개인화 뉴스레터를 발송하는 멀티에이전트 서비스 | **분석 응답 6초 → 2초 (66%↓)**<br/>프롬프트 토큰 **40% 절감**<br/>Shared Cache로 LLM 호출 **토픽당 7회 → 1회**<br/>외부 API 차단 시 대기 **25초 → 1.5초** | `FastAPI` `PostgreSQL` `Redis` `asyncpg` `Gemini` `Chrome Extension` |
| **[청심환](https://github.com/dong-k-k/server)** <br/><sub>KB 국민은행 AI Challenge</sub> | 수출입 중소기업의 환노출 위험을 진단하고 헤지 전략·금융상품을 추천하는 서비스 | **AI 실패 시 ECOS 실데이터 통계 폴백**으로 무중단 진단<br/>추천 근거를 LLM이 아닌 **검증된 구조화 데이터**에서만 생성<br/>3레포 API 계약 분리로 **2주 내 병렬 개발·배포 완료** | `FastAPI` `PostgreSQL` `pgvector` `SQLAlchemy(async)` `Docker` `Playwright` |
| **[EVI 대시보드](https://github.com/sophie-24/2025data_EVI)** <br/><sub>1인 개발 · 우수상</sub> | 전력·금융·인구·기후 데이터를 결합해 행정동별 에너지 빈곤 위험을 지수화한 복지 의사결정 시스템 | **정책 시뮬레이션 10초 → 0.2초**<br/>KEPCO API 캐시 히트 **2초 → 0.05초**<br/>PCA 다중공선성 보정 + 도메인 가중치로 **Z3 0점 산출 문제 해결** | `FastAPI` `MySQL` `Redis` `scikit-learn` `PCA` `Isolation Forest` `React` `D3.js` |
| **[RePlanet](https://github.com/sophie-24/seoul-25-ht-RePlanet)** <br/><sub>팀장 · 이사장상</sub> | GPS·공공데이터로 친환경 이동을 자동 인식하고 AI 코칭으로 탄소 절감을 유도하는 플랫폼 | **교통수단 분류 정확도 60% → 87%**<br/>RAG 기반 정책 Q&A **정확도 85%**<br/>원본/정제 분리 ETL로 데이터 추적성 확보 | `FastAPI` `MySQL` `Redis` `AWS Bedrock` `Claude 3.5` `RandomForest` |
| **[D-Log](https://github.com/sophie-24/Coss_IOT_2026)** <br/><sub>IoT-COSS 개발자 챌린지</sub> | IoT 센서와 AI 소음 분류로 층간소음을 객관화하고 법적 기준 증거 리포트를 생성하는 시스템 | **소음 분류 확신도 30% → 75%**<br/>외부 소음 필터링 **80% 이상**<br/>oneM2M ACP로 세대 간 원본 데이터 접근 제한 | `FastAPI` `YAMNet` `LSTM` `TensorFlow` `PyTorch` `oneM2M/Mobius` |
| **[GemPT](https://github.com/2025-X-Thon-Team2/2025-X-Thon-Team2_kongjjagkongjjagdugeundugeun)** <br/><sub>개발리드 · X-Thon</sub> | GPT를 해결자, Gemini를 검증자로 분리해 최대 5라운드 교차검증하는 학습 답안 검증 서비스 | **신뢰도 알고리즘 정확도 66% → 89%** (Pytest)<br/>EMA 기반 종료 조건으로 **무한 토론 차단**<br/>미합의 상태와 판단 근거를 사용자에게 투명 공개 | `FastAPI` `GPT-4o` `Gemini` `Pillow` `Pytest` |
| **[Blur](https://github.com/SOPT-all/38-SOPKATHON-SERVER-ANDROID3)** <br/><sub>SOPKATHON 대상 · 1박 2일</sub> | 익명 고민 카드가 공감을 받으면 자동 소각되는 감정 해소 플랫폼 | **1박 2일 MVP에도 Blue/Green 배포 적용**<br/>자동 소각 UX 엣지 케이스를 서버 관점에서 발견해 **기획 정책 수정 주도** | `Java` `Spring Boot` `JPA` `MySQL` `EC2` `Nginx` `GitHub Actions` |

### 🔬 Currently In Progress

| 프로젝트 | 내용 |
|---|---|
| **상담 음성데이터 AI 기술 검증 (POC)** <sub>한국사회보장정보원 산학협력</sub> | '25년 상담데이터 34만 건(1,121GB) 중 10만 건 학습 / 10만 건 검증 · Whisper STT 파인튜닝 · **CER 기준 정확도 95% 목표** · 가명처리 선행 |
| **CoELA 기반 다중 로봇 협력 시스템** <sub>동국대 개별연구</sub> | GPT-4/VirtualHome 의존 구조를 AI2-THOR + 소형 오픈모델로 이식 · 상태 필터링과 결정론적 완료 가드로 **20스텝 미검증 종료 → 6스텝 검증 종료** |
| **ReviewTrace** <sub>개인 사이드 프로젝트</sub> | PR 리뷰 댓글에서 기술 부채 신호를 수집·분류·추적 |

<br/>

## 🛠 Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java%2021-007396?style=flat-square&logo=openjdk&logoColor=white)
![SpringBoot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![SpringSecurity](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA%20/%20QueryDSL-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy%20(async)-D71F27?style=flat-square&logo=sqlalchemy&logoColor=white)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
<sub>· `pg_trgm` `pgvector` `Flyway` `Alembic`</sub>

**Infra & CI/CD**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHubActions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
<sub>· `EC2` `RDS` `S3` `Bedrock` `Lightsail` · Blue/Green 무중단 배포</sub>

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
<sub>· `Micrometer` `MDC 구조화 로깅` `Dozzle`</sub>

**AI & Data**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
<sub>· `Gemini` `GPT-4o` `AWS Bedrock(Claude)` `RAG` `YAMNet` `LSTM`</sub>

**Also** &nbsp;·&nbsp; `React` `Vue.js` `D3.js` `Tableau` `oneM2M/Mobius` `ESP32`

<br/>

## 💼 Experience

| 기간 | 활동 |
|---|---|
| 2026.03 ~ | **SOPT** 38기 Server 파트 <sub>전국 최대 규모 대학생 연합 IT 벤처 창업 동아리</sub> |
| 2026.05 ~ | **AWS Student Builder Group at DGU** 1기 <sub>동국대 최초 · 격주 Hands-On Lab</sub> |
| 2026 | **동국대학교 108 리더스** 20기 <sub>대학 대표 리더십 육성 프로그램</sub> |
| 2026.06 ~ | **한국사회보장정보원** 사회보장 AI 혁신 산학협력 프로젝트 |
| 2025.07 ~ 2025.08 | **BDA 부트캠프** 수료 및 데이터 분석 프로젝트 |
| 2025.03 ~ 2025.12 | **서울 AI메이커 자치단** 2기 <sub>시립서울청소년센터 · 청소년 AI 교육 프로그램 기획·운영</sub> |
| 2024.09 ~ 2024.11 | **구름 청소년 SW 동행 프로젝트** 청년 멘토 <sub>3개 고교 대상 SW·AI 멘토링</sub> |
| 2024.03 ~ 2025.12 | **컴퓨터공학과 학생회** 기획국 |

**Certificates** &nbsp;·&nbsp; ADsP (2025) &nbsp;|&nbsp; Microsoft Azure AI Fundamentals AI-900 (2026) &nbsp;|&nbsp; AICE Basic (2024)

<br/>

## ✍️ Writing

기술적 의사결정과 트러블슈팅 과정을 기록합니다 → **[velog.io/@gyuri0504](https://velog.io/@gyuri0504/posts)**

<!-- 아래 3줄에 대표 글 제목과 링크를 채워주세요 -->
- [SOPT 합동세미나 후기 | JPA 트러블 슈팅부터 CI/CD 배포 자동화까지](https://velog.io/@gyuri0504/%EC%B4%88%EB%B3%B4-%EC%84%9C%EB%B2%84-%EA%B0%9C%EB%B0%9C%EC%9E%90%EC%9D%98-%ED%95%A9%EB%8F%99%EC%84%B8%EB%AF%B8%EB%82%98-%ED%9B%84%EA%B8%B0..-JPA-%ED%8A%B8%EB%9F%AC%EB%B8%94-%EC%8A%88%ED%8C%85%EB%B6%80%ED%84%B0-CICD-%EB%B0%B0%ED%8F%AC-%EC%9E%90%EB%8F%99%ED%99%94%EA%B9%8C%EC%A7%80)
- [Team HAPHAP 서버 개발기 | @AuthenticationPrincipal 동작원리 찾아보](https://velog.io/@gyuri0504/Team-HAPHAP-%EC%84%9C%EB%B2%84-%EA%B0%9C%EB%B0%9C%EA%B8%B0-AuthenticationPrincipal-%EB%8F%99%EC%9E%91%EC%9B%90%EB%A6%AC-%EC%B0%BE%EC%95%84%EB%B3%B4%EA%B8%B0)
- [ASBG-DGU | End to End 패킷 흐름 살펴보기](https://velog.io/@gyuri0504/ASBG-DGU-6%EC%A3%BC%EC%B0%A8-%EC%84%B8%EC%85%98.-End-to-End-%ED%8C%A8%ED%82%B7-%ED%9D%90%EB%A6%84-%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0)

<br/>

## 📫 Contact

- 📮 **Email** — sophia.gyuri@gmail.com
- 📓 **Portfolio** — [웹 포트폴리오](https://gyuri-cloud.vercel.app/), [노션 포트폴리오](https://buly.kr/1RGkF2T)
- ✏️ **Blog** — [velog.io/@gyuri0504](https://velog.io/@gyuri0504/posts)

<br/>

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sophie-24/sophie-24/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sophie-24/sophie-24/output/github-contribution-grid-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/sophie-24/sophie-24/output/github-contribution-grid-snake.svg" />
  </picture>
</p>
