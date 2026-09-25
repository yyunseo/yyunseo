# 안녕하세요, 윤서입니다 👋

사용자의 관점에서 문제를 바라보고, **서비스의 전체 흐름을 이해하며 개발하는 엔지니어**입니다.

백엔드 API 개발을 시작으로 AI 서비스, 검색 시스템, 데이터 파이프라인, 클라우드 인프라까지 경험을 넓혀 왔습니다.  
하나의 기능을 구현하는 데 그치지 않고 **사용자 요청이 Frontend → Backend → AI/Search → Database → Infrastructure로 어떻게 이어지는지**를 이해하고, 각 구성 요소가 어떻게 맞물려야 하는지 고민합니다.

새로운 기술이나 익숙하지 않은 코드도 먼저 전체 구조와 흐름을 파악한 뒤 필요한 부분을 하나씩 배우며 해결해 나가는 편입니다.

## Experience

- `2026.08 ~` 🏢 (주)이노그리드 AI 클라우드 연구팀 인턴 

## Education

- `2021.03 ~ 2027.02`🎓 한성대학교 컴퓨터공학부 학사 

## Activities

- 📚 한성대학교 학술동아리 DC&M
- 🏆 2026 한이음 드림업

## Certification

- `2026` 📜 정보처리기사 (Engineer Information Processing), 한국산업인력공단 (Human Resources Development Service of Korea)

## Projects

### 🕸️ BizNode — Knowledge Graph 기반 투자 인사이트 워크스페이스

`2026.06 – 2026.09` · 2026 한이음 드림업 · AI / Data

[Organization](https://github.com/Biz-Node)

기업 공시 데이터를 수집·정제하고 Knowledge Graph와 검색·Agent를 통해 기업 간 관계와 투자 정보를 탐색하는 시스템입니다.

- OpenDART 데이터 수집 → XML 파싱 → 정제·정규화 → Neo4j 적재 파이프라인 구현
- Entity Resolution과 Query Routing을 포함한 검색 레이어 설계
- 관계 검색과 의미 검색을 분리하고 RRF 기반 결과 랭킹 구성
- 한국어 기업명 앵커 추출 및 Workspace 문맥을 활용한 검색 개선
- `/retrieve` / `/ask` API와 근거·인용을 포함한 Agent 흐름 구현
- 검색 평가셋, grounding 검사, 관측 로그 및 회귀 테스트 구성

`Python` `FastAPI` `LangGraph` `Neo4j` `PostgreSQL` `ChromaDB`

### 📚 Ban-Olim — 독서·학습 지원 플랫폼

`2026.02 – 2026.06` · Capstone Project

[Organization](https://github.com/Ban-Olim)

문장 이해와 어휘 학습을 지원하는 교육 플랫폼으로, Backend · AI Service · Infrastructure를 함께 개발했습니다.

- Spring Boot 기반 학습 API 및 FastAPI AI 서비스 연동
- 문장분해 문제 생성 및 LLM 기반 응답 검증
- PostgreSQL 기반 교육 데이터 처리 및 문제 저장
- ElevenLabs TTS 및 AWS S3 음성 데이터 연동
- Docker Compose · Nginx · HTTPS · GitHub Actions 기반 배포 구성
- CI/CD와 서비스 간 환경변수 및 API 연동 관리

`Java` `Spring Boot` `JPA` `FastAPI` `PostgreSQL` `AWS` `Docker` `Nginx` `GitHub Actions`

### 🔎 Jibijoa — 자연어 기반 패널 검색 엔진

`2025.10 – 2025.11` · Pre-Capstone Project

[Repository](https://github.com/capstone-Jibijoa/backend) · [Personal Mirror](https://github.com/yyunseo/backend)

자연어 질문을 정형 조건과 의미적 조건으로 분리해 패널·설문 데이터를 검색하고 분석하는 시스템입니다.

- LLM 기반 자연어 질의 구조화 및 Semantic Routing
- PostgreSQL 후보 필터링 + Qdrant Vector Search + Reranking
- Fuzzy Matching 및 부정 조건 필터링
- 다중 테이블 검색 및 결과 중복 제거
- 검색 결과 기반 통계와 LLM Insight 생성

`Python` `FastAPI` `PostgreSQL` `Qdrant` `LangChain` `Claude`

## Skills

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Backend

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)

### AI & Search

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-5B5BD6?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square)

### Cloud & DevOps

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Currently Learning

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=20232A)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![OpenStack](https://img.shields.io/badge/OpenStack-ED1944?style=flat-square&logo=openstack&logoColor=white)

## What I Care About

**See the whole system.**  
기능 하나보다 그 기능이 서비스 전체에서 어떤 역할을 하는지 먼저 생각합니다.

**Learn what I need.**  
모르는 기술이나 코드를 피하기보다 구조를 파악하고 필요한 만큼 빠르게 학습합니다.

**Build with responsibility.**  
구현에서 끝내지 않고 API 계약, 데이터 흐름, 배포, 로그와 테스트까지 연결해서 확인합니다.

**Stay close to the user.**  
기술 자체보다 사용자가 실제로 어떤 결과를 필요로 하는지에서 문제를 정의하려고 합니다.
