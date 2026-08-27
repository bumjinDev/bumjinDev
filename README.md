<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E34C26,10:DA5B0B,30:C6538C,75:3572A5,100:A371F7&height=100&section=header&text=&fontSize=0" width="100%"/>

<div align="center">

### 인증·배포·캐싱 구조를 중심으로 백엔드 시스템 전반을 직접 설계하고 운영한 프로젝트 중심 개발자입니다.

<p align="left">
  Spring Boot 기반 프로젝트들을 통해 인증, 캐싱, 배포, 무중단 운영에 이르는 백엔드 전반의 핵심 기술을 설계하고 구현했습니다. JWT, Redis, Jenkins, Docker, AWS 등 실무 중심 기술을 통합 적용하여, 단순한 기능 구현을 넘어 실사용 가능한 시스템 구조와 서비스 수준 인프라를 구축하는 데 집중하였습니다.
</p>

---

### 프로젝트

| 구분 | 제목 | 기간 | 개요 | 역할 | 기술 |
|--|--|--|--|--|--|
| 메인 | [**WHEREHOUSE**](https://github.com/bumjinDev/wherehouse_SpringBoot) | `2023.09 ~ 2025.03` | <sub>**서울시 1인가구를 위한 주거지 추천 서비스**<br>• **검색** — Redis Sorted Set 기반 CQRS 실시간 검색 엔진<br>• **추천** — 2단계 Fallback 로직 + 리뷰 하이브리드 점수 통합<br>• **성능** — CompletableFuture 병렬화로 응답 72.3% 단축, N+1을 IN절 청킹으로 개선(V$SQL 정량 분석), OOM 방지 Slice 청크 처리<br>• **인증·배포** — JWT 인증/인가, Jenkins+Docker CI/CD, AWS 배포</sub> | <sub>Spring Boot 백엔드 아키텍처 설계, CQRS + Redis 추천 시스템 구현, JWT 인증/인가, 데이터 파이프라인, 성능 최적화 전체 (3인 팀)</sub> | ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) |
| 메인 | [**ExerciseManagement**](https://github.com/bumjinDev/ExerciseManagement) | `2026.06 ~ 2026.08` | <sub>**기기로 측정 안 되는 운동을 사진+팀원 확인으로 검증하는 팀 대항 챌린지 서비스**<br>• **검증 2계층** — 시스템이 거를 것(같은 사진 재사용·사진 메타데이터·인증 횟수)과 사람이 볼 것(팀원 확인)을 분리<br>• **팀 편성** — 팀끼리 실력은 비슷하게, 팀 안은 고르게 맞추는 자동 배정(같은 입력이면 항상 같은 결과)<br>• **정산** — 예치금 이동을 원장에 쌓고, 금액 검산 + 중복 실행 차단(멱등)으로 이중 지급 방지<br>• **인증·인가** — JWT 무상태 로그인 + "그 챌린지 참가자인가·같은 팀인가" 관계 기반 권한<br>• **그 외** — 제약 있는/없는 DDL 두 벌로 동시성 방어선 비교, 요구사항·설계 명세서 쓰고 구현</sub> | <sub>기획·요구사항/설계 명세·구현·시나리오 테스트 1인 풀사이클, Postman 55개 요청 전 구간 검증</sub> | ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) |
| 토이 | [**ChatService**](https://github.com/bumjinDev/ChatService) | `2025.04.18 ~ 2025.07.29` | <sub>'ChatProgram' 프로젝트 리펙토링 및 고도화</sub> | <sub>'ChatProgram' 프로젝트 내 비동기 처리 등 개선 작업 수행</sub> | ![WebSocket](https://img.shields.io/badge/WebSocket-20232A?style=flat-square&logo=websocket&logoColor=white) ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) |
| 토이 | [**ChatProgram**](https://github.com/bumjinDev/ChatProgram) | `2024.06.25 ~ 2024.07.06` | <sub>WebSocket 기반 1:N 실시간 채팅 시스템. HTML + Spring Framework 기반으로 채팅방 생성 및 메시지 라우팅 기능 구현</sub> | <sub>세션 ID 추적, 메시지 브로드캐스트, 채팅방 등록/해제 로직 직접 설계</sub> | ![WebSocket](https://img.shields.io/badge/WebSocket-20232A?style=flat-square&logo=websocket&logoColor=white) ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) |


---

### 보유 기술

#### OS / ENV
<img src="https://img.shields.io/badge/Windows%2011-0079D5?style=flat-square&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />

#### LANGUAGE
<img src="https://img.shields.io/badge/Java-%23ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" />

#### FRAMEWORK / LIBRARY
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />

#### DATABASE
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white" />

#### SECURITY / AUTH
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
<img src="https://img.shields.io/badge/HTTPS-0096D6?style=flat-square&logo=letsencrypt&logoColor=white" />

#### CI / CD / INFRA
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

---

<div align="center">
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img src="https://github-readme-stats.vercel.app/api?username=bumjinDev&show_icons=true&theme=material-palenight&hide_border=true&bg_color=20232a&icon_color=58A6FF&text_color=fff&title_color=58A6FF&count_private=true" width="49%" />
</a>
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bumjinDev&layout=compact&theme=material-palenight&hide_border=true&bg_color=20232a&icon_color=58A6FF&text_color=fff&title_color=58A6FF&count_private=true" width="49%" />
</a>
</div>

<div align="center">
<a href="https://github.com/ashutosh00710/github-readme-activity-graph">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=bumjinDev&theme=react-dark&bg_color=20232a&hide_border=true&line=58A6FF&color=58A6FF" width="94%"/>
</a>
</div>

<img src="https://github.com/bumjinDev/bumjinDev/blob/output/github-snake-dark.svg" width="100%">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:E34C26,10:DA5B0B,30:C6538C,75:3572A5,100:A371F7&height=40&section=footer&text=&fontSize=0" width="100%"/>
