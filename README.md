# Myoungju KO
---
<p align="center"> <b>경희대학교 컴퓨터공학과</b><br> 좋아하는 걸 만드는 마음엔 끝이 없으니까<br>벼락치기용 타이머, 서브컬처 일정 플랫폼처럼 제가 필요했던 것들을 직접 만들어 왔습니다.
지금은 만든 서비스가 더 많은 사람에게 닿고, 그 반응으로 다시 나아지는 과정까지 해 보고 싶습니다.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-Express-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Naver%20Cloud-03C75A?style=flat-square&logo=naver&logoColor=white" />
</p>

---

## 🔎 Featured Projects

### 🎤 MIROYIRO — J-POP·애니 일정·소식 알림 플랫폼 (개발팀장, 2026)
대한민국에서 일본 대중문화(J-POP, 애니메이션)에 대한 관심을 한곳에서 해소하는 플랫폼. *좋아하는 마음에는 끝이 없으니까!* ([인스타그램](https://www.instagram.com/miro_yiro/)) 타 학교 연합 팀(개발 2명)에서 개발팀장을 맡아 FastAPI 수집 서버와 운영용 관리 화면을 Claude Code로 구현했습니다.

- **수집 대상**: KOPIS · 애니시아 · TMDB · X · 애니메이트 · 애니플러스 · 라프텔
- **검증**: 실패 케이스를 먼저 정하고 일부러 버그를 넣어 테스트가 깨지는지 확인. 이 과정에서 TMDB API 키가 요청 로그에 남는 문제를 찾아 수정
- **비용 방어**: X API는 월 예산이 설정되지 않으면 요청하지 않도록 차단
- **수치**: 자동 테스트 212개 통과(2026-11-27), 실사이트 3곳 31건 수집 확인(2026-11-11)
- **스택**: FastAPI · Spring Boot · PostgreSQL · Docker Compose
- **진행 상황**: 수집 서버를 미니 PC에 Docker Compose로 배포하는 중(11/27~29). 가동 시작 시각·소스별 수집 건수는 확인되는 대로 갱신. 메인 서버는 별도로 배포 예정
- **링크**: [BE](https://github.com/miroyiro/mryr_be) · [FE](https://github.com/miroyiro/mryr_fe) (수집 서버는 팀 private 레포)

### ⚡ zeus-on — 그룹 벼락치기 타이머
마감이 있는 일을 끝내도록 돕는 그룹 타이머. 방치하면 '벼락'이 쌓이고, 그룹이 끝나면 벼락이 가장 많은 사람이 벌칙자로 뽑힙니다. 예술디자인대학 학생 포함 6명이 GitHub PR로 협업했습니다.

- **맡은 일**: 타이머·포인트·인증 서버(Express, Prisma, Firebase Auth)와 Flutter 타이머 화면, 배포
- **검증**: 앱이 완성되기 전에 *사용자 2명이 그룹을 만들고 완료하기까지*의 시나리오를 문서로 작성해 Postman으로 검증하고, 이 과정에서 찾은 라우트·로직 오류를 수정
- **배포**: GCP에 배포해 GDG on Campus GCP 스터디 대회 **3위** → 백엔드를 AWS Lambda + Neon(PostgreSQL)으로 재배포 중
- **스택**: Flutter · Node.js/Express · Prisma · PostgreSQL · Firebase Auth/FCM · Docker
- **링크**: [backend](https://github.com/sopetherock/backend) · [frontend](https://github.com/sopetherock/frontend)

---

## 🛠 Tech Stack

| 구분 | 기술 |
|---|---|
| **Language** | Java, Python, JavaScript |
| **Backend** | Spring Boot (JPA), FastAPI, Express (Prisma) |
| **Database** | MySQL, PostgreSQL |
| **Cloud / Infra** | AWS (EC2, S3, CloudFront, Lambda, Bedrock) · GCP (Cloud Run, GKE) · Naver Cloud (LB, Auto Scaling) |
| **DevOps** | Docker, Kubernetes (GKE), GitHub Actions |
| **Test / Monitoring** | JUnit5, pytest, Testcontainers, k6, Prometheus, Grafana |
| **Collaboration** | Git, Notion |

---

## 🏆 Awards & Education

| 구분 | 내용 | 시기 |
|---|---|---|
| 🥇 수상 | GDG on Campus 경희대 동아리 프로젝트 발표 **1위** (JANDI) | 2025 |
| 🥉 수상 | GDG on Campus 경희대 GCP 스터디 대회 **3위** (zeus-on) | 2025 |
| 🎓 교육 | SK AI Data Academy 1기 초급·중급 수료 | 2024 |
| 🎓 교육 | 네이버클라우드 클라우드 Literacy 과정 (수강 중) | 2026 |
| 👥 동아리 | GDG on Campus 경희대 — GCP·쿠버네티스 스터디 | 2025~2026 |
| 👥 동아리 | AWS Cloud Clubs 경희대 — AWS 세션, Java Spring 스터디 | 2026~ |

---

## 📅 Projects by Year

### 2026 · 3학년

| 프로젝트 | 설명 | 스택 | 레포 |
|---|---|---|---|
| **MIROYIRO** (타 학교 연합, 개발팀장) | J-POP·애니 일정·소식 알림 플랫폼. FastAPI 수집 서버와 운영용 관리 화면을 Claude Code로 구현. 실패 케이스를 먼저 정하고 버그를 넣어 테스트로 검증(212개 통과), TMDB 키 로그 노출 수정, X는 예산이 없으면 수집 차단 *(수집 서버 미니 PC 배포 진행 중)* | FastAPI, Spring Boot, PostgreSQL, Docker | [BE](https://github.com/miroyiro/mryr_be) · [FE](https://github.com/miroyiro/mryr_fe) |
| **수강신청 교환마켓** (네이버클라우드 클라우드 Literacy 과정 3조) | 수강 강의 맞교환 모의 서비스. 매칭·동시성 담당: 좌석은 낙관적 락 + UNIQUE, 세션 매칭은 비관적 락(ID 오름차순 잠금으로 순환 대기 제거). 동시 매칭 요청 20건에서 성공 **3건 → 20건**, 대가로 p95 **약 2.5배**. GitHub Actions 셀프호스티드 러너로 **SSH 22번 인바운드 없이** NCP LB + Auto Scaling 그룹에 배포 | Spring Boot, MySQL, Flyway, Testcontainers, k6, NCP | [BE](https://github.com/ncp-03/sugang_exchange_be) · [FE](https://github.com/ncp-03/front-khu-mock-sugang-v4) |
| **haruman** (ACC 전체 세션 팀6) | 대여 플랫폼. 채팅·인증·알림·AI 추천(Bedrock, 5초 타임아웃 폴백) 백엔드 담당, k6·Prometheus·Grafana 모니터링 | Node.js, AWS (EC2, Bedrock, CloudFront, S3) | [team6](https://github.com/aws-cloud-clubs/2026-khu-project-team6) |
| **Goodz** (ACC Spring 스터디 팀2) | 굿즈 판매 매장 지도 서비스. 상품 상세의 판매 매장 목록 N+1 해결(`JOIN FETCH`, 매장 20곳 기준 쿼리 **21번 → 1번**, 테스트로 검증), `X-Request-Id` MDC 로깅 필터, 전역 예외 처리 | Spring Boot, JPA | [2026-spring-team2](https://github.com/jdk829355/2026-spring-team2) · [ACC-springStudy](https://github.com/kwang-i-coder/ACC-springStudy) |
| **kitPass** | 유니폼 최저가 크롤링 서버 | Python, EC2 | [kitPass_crawling](https://github.com/myoungjugo/kitPass_crawling) |
| **JANDI 2차** | 디자이너·기획자·프론트 합류 후 리팩토링 및 기능 추가 *(팀 사정으로 중단)* | FastAPI | [jandi-be](https://github.com/JandiProject/jandi-be) · [jandi-fe](https://github.com/JandiProject/jandi-fe) |
| **알고리즘 스터디** | 교내 알고리즘 스터디 풀이 기록 | Python | [algorithm_study](https://github.com/myoungjugo/algorithm_study) |
| 오픈소스 | ZeroMQ 문서 fork | — | [zeromq.org](https://github.com/myoungjugo/zeromq.org) |

### 2025 · 2학년

| 프로젝트 | 설명 | 스택 | 레포 |
|---|---|---|---|
| **JANDI** (GDG, 🥇 1위) | 블로그 관리 플랫폼. 인증(로그인·이메일 인증)과 RabbitMQ 기반 메일 서버 담당 | FastAPI, PostgreSQL, RabbitMQ, GKE | [jandi-be](https://github.com/JandiProject/jandi-be) · [trend_analysis](https://github.com/JandiProject/trend_analysis) · [25-26_PT_team2_BE](https://github.com/kwang-i-coder/25-26_PT_team2_BE) |
| **zeus-on** (🥉 GCP 스터디 3위) | 그룹 벼락치기 타이머 앱. 타이머·포인트·인증 서버와 Flutter 타이머 화면 담당, 2명 그룹 시나리오를 Postman으로 검증하며 오류 수정. 예술디자인대학 학생과 협업, Docker → GCP 배포, AWS Lambda로 재배포 *(리팩토링 진행 중)* | Express, Prisma, PostgreSQL, Firebase, Flutter, GCP, AWS Lambda | [backend](https://github.com/sopetherock/backend) · [frontend](https://github.com/sopetherock/frontend) |
| **FastAPI / Node.js 스터디** | 프레임워크 학습 기록 | FastAPI, Node.js | [fast-api-study](https://github.com/myoungjugo/fast-api-study) · [node.js_study](https://github.com/myoungjugo/node.js_study) |
| **크롤링 학습** | 웹 크롤링 기초 | Python | [crawling](https://github.com/myoungjugo/crawling) |
| **daily_commit** | 커밋 습관 만들기 | — | [daily_commit](https://github.com/myoungjugo/daily_commit) |

### 2024 · 1학년

| 프로젝트 | 설명 | 스택 | 레포 |
|---|---|---|---|
| **쉐어잇** (디자인적 사고, A+) | 자취생 식재료 공동구매 사이트. 프론트엔드 담당, 팀 프로젝트 만점 | HTML, CSS | [share_eat_project](https://github.com/sangyeong01/share_eat_project) |

---

## 📫 Contact

- Email: ddingjuko@gmail.com
- GitHub: [@myoungjugo](https://github.com/myoungjugo)

---
