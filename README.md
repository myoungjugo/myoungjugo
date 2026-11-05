# Myoungju KO
---
<p align="center"> <b>경희대학교 컴퓨터공학과</b><br> 좋아하는 것을, 안정적으로 서비스하는 백엔드 개발자가 되고 싶습니다.</p>
  
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-Express-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Naver%20Cloud-03C75A?style=flat-square&logo=naver&logoColor=white" />
</p>

---

## 🛠 Tech Stack

| 구분 | 기술 |
|---|---|
| **Language** | Java, Python, JavaScript |
| **Backend** | Spring Boot (JPA), FastAPI, Express (Prisma) |
| **Database** | MySQL, PostgreSQL |
| **Cloud / Infra** | AWS (EC2, S3, CloudFront, Lambda, Bedrock) · GCP (Cloud Run, GKE) · Naver Cloud (LB, Auto Scaling) |
| **DevOps** | Docker, Kubernetes (kops, Helm), GitHub Actions |
| **Test / Monitoring** | JUnit5, Testcontainers, k6, Prometheus, Grafana |
| **Collaboration** | Git, Notion, Figma |

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
| **MIROYIRO** (타 학교 연합, 개발팀장) | 서브컬처 소식·일정 조회 플랫폼. 모놀리식으로 시작하되 모듈 경계를 나눈 구조 설계, 스크래핑 서버 분리 *(진행 중)* | Express, FastAPI, MySQL | [BE](https://github.com/miroyiro/mryr_be) · [FE](https://github.com/miroyiro/mryr_fe) |
| **수강신청 교환마켓** (NCP 부트캠프) | 수강 강의 맞교환 모의 서비스. 좌석은 낙관적 락 + UNIQUE, 세션 매칭은 비관적 락으로 레이어별 동시성 제어. Testcontainers 기반 동시성 테스트, GitHub Actions, NCP LB + Auto Scaling 배포 | Spring Boot, MySQL, Flyway, k6, NCP | [BE](https://github.com/ncp-03/sugang_exchange_be) · [FE](https://github.com/ncp-03/front-khu-mock-sugang-v7-ncp-3-) · [FE v4](https://github.com/ncp-03/front-khu-mock-sugang-v4) · [FE v3](https://github.com/ncp-03/front-khu-mock-sugang-v3) |
| **haruman** (ACC 전체 세션 팀6) | 대여 플랫폼. 채팅·인증·알림·AI 추천(Bedrock, 5초 타임아웃 폴백) 백엔드 담당, k6·Prometheus·Grafana 모니터링 | Node.js, AWS (EC2, Bedrock, CloudFront, S3) | [team6](https://github.com/aws-cloud-clubs/2026-khu-project-team6) · [haruman_be](https://github.com/myoungjugo/haruman_be) |
| **Goodz** (ACC Spring 스터디 팀2) | 굿즈 판매 매장 지도 서비스. 재고 조회 N+1 해결(`@EntityGraph`, `JOIN FETCH`), `X-Request-Id` MDC 로깅 필터, 전역 예외 처리 | Spring Boot, JPA | [2026-spring-team2](https://github.com/jdk829355/2026-spring-team2) · [ACC-springStudy](https://github.com/kwang-i-coder/ACC-springStudy) |
| **kitPass** | 유니폼 최저가 크롤링 서버 | Python, EC2 | [kitPass_crawling](https://github.com/myoungjugo/kitPass_crawling) |
| **JANDI 2차** | 디자이너·기획자·프론트 합류 후 리팩토링 및 기능 추가 *(팀 사정으로 중단)* | FastAPI | [jandi-be](https://github.com/JandiProject/jandi-be) · [jandi-fe](https://github.com/JandiProject/jandi-fe) |
| **알고리즘 스터디** | 교내 알고리즘 스터디 풀이 기록 | Python | [algorithm_study](https://github.com/myoungjugo/algorithm_study) |
| 오픈소스 | ZeroMQ 문서 fork | — | [zeromq.org](https://github.com/myoungjugo/zeromq.org) |

### 2025 · 2학년

| 프로젝트 | 설명 | 스택 | 레포 |
|---|---|---|---|
| **JANDI** (GDG, 🥇 1위) | 블로그 관리 플랫폼. 인증(로그인·이메일 인증)과 RabbitMQ 기반 메일 서버 담당 | FastAPI, PostgreSQL, RabbitMQ, GKE | [jandi-be](https://github.com/JandiProject/jandi-be) · [trend_analysis](https://github.com/JandiProject/trend_analysis) · [25-26_PT_team2_BE](https://github.com/kwang-i-coder/25-26_PT_team2_BE) |
| **zeus-on** (🥉 GCP 스터디 3위) | 그룹 공부시간 타이머 앱. 예술디자인대학 학생과 협업, Docker → Cloud Run·GKE 배포 *(리팩토링 진행 중)* | Express, Prisma, Firebase, GCP | [backend](https://github.com/sopetherock/backend) · [frontend](https://github.com/sopetherock/frontend) |
| **FastAPI / Node.js 스터디** | 프레임워크 학습 기록 | FastAPI, Node.js | [fast-api-study](https://github.com/myoungjugo/fast-api-study) · [node.js_study](https://github.com/myoungjugo/node.js_study) |
| **크롤링 학습** | 웹 크롤링 기초 | Python | [crawling](https://github.com/myoungjugo/crawling) |
| **daily_commit** | 커밋 습관 만들기 | — | [daily_commit](https://github.com/myoungjugo/daily_commit) |

### 2024 · 1학년

| 프로젝트 | 설명 | 스택 | 레포 |
|---|---|---|---|
| **쉐어잇** (디자인적 사고, A+) | 자취생 식재료 공동구매 사이트. 프론트엔드 담당, 팀 프로젝트 만점 | HTML, CSS | [share_eat_project](https://github.com/sangyeong01/share_eat_project) |
| 학원 인원체크 앱 | Linux 환경에서 aws-cli로 직접 배포 | AWS | — |

---

## 📫 Contact

- Email: ddingjuko@gmail.com
- GitHub: [@myoungjugo](https://github.com/myoungjugo)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=myoungjugo&show_icons=true&hide_border=true&count_private=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=myoungjugo&layout=compact&hide_border=true" height="150" />
</p>
