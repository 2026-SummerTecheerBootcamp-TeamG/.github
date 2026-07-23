<div align="center">

# TripCanvas

### 2026 Techeer Summer BootCamp — TEAM G

**MCP 기반 AI 여행 플래너 에이전트**

<!-- TODO: 온보딩/메인 화면 GIF 또는 대표 배너 이미지 1장 -->
<!-- <img src="배너.gif" width="80%" /> -->

</div>

<br/>

# Introduction

> **"일본 후쿠오카 3박4일, 성인 1명, 쇼핑 중심으로 예산 80만 원"** — 한 문장이면 충분합니다.

**TripCanvas**는 자연어 요청 하나로 항공권 · 숙소 · 일정을 한 번에 설계해 주는 AI 여행 플래너입니다.
Claude가 MCP를 통해 여러 여행 서비스를 도구처럼 연결하고,
역할별 에이전트가 협업하여 맞춤형 여행 일정을 완성합니다.

### 핵심 기능

- **자연어 → 여행 계획**: 목적지 · 기간 · 테마 · 예산을 문장에서 파싱해 구조화
- **항공 에이전트**: 예산 내 최적 항공편 탐색 (Google Flights)
- **숙소 에이전트**: 위치 · 가격 기반 호텔 후보 추천 (LiteAPI)
- **일정 에이전트**: 동선을 고려한 일자별 방문 순서 최적화 (Google Places)
- **대화형 수정**: "둘째 날 일정 좀 여유롭게 바꿔줘" — 대화로 일정 편집

<!-- TODO: 배포 URL 생기면 여기에 -->
**Service**: https://www.tripcanvas.cloud/
<!-- TODO: Medium/기술 블로그 회고 글 링크 -->
**Medium**: https://medium.com/@1231435e/trip-canvas-a978aac9cc4b?postPublishedType=repub

<br/>

# Demo

<!-- TODO: 전체 데모 영상 — YouTube 링크 또는 GIF
     YouTube면: [![Demo Video](썸네일URL)](유튜브URL) -->

### 메인 페이지

<!-- TODO: 스크린샷 2~3장 (가로로 나란히 두려면 <img width="32%"> 반복) -->

### 여행 계획 요청 (자연어 입력)

<!-- TODO: 스크린샷 -->

### 일정 생성 결과

<!-- TODO: 스크린샷 -->

### 대화형 일정 수정

<!-- TODO: 스크린샷 -->

<br/>

# API

<!-- TODO: Swagger/API 명세 캡처 이미지 2~4장 -->

<br/>

# System Architecture

<!-- TODO: 아키텍처 다이어그램 1장 -->

<br/>

# ERD

<!-- TODO: ERD 이미지 1장 -->

<br/>

# Tech Stack

| Field | Technology |
|---|---|
| **Frontend** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) |
| **Backend** | ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![Django REST](https://img.shields.io/badge/Django_REST_Framework-A30000?style=for-the-badge&logo=django&logoColor=white) ![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white) ![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Amazon RDS](https://img.shields.io/badge/Amazon_RDS-527FFF?style=for-the-badge) |
| **AI / External API** | ![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white) ![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white) ![LiteAPI](https://img.shields.io/badge/LiteAPI-6C63FF?style=for-the-badge) ![SerpApi](https://img.shields.io/badge/SerpApi-000000?style=for-the-badge) |
| **DevOps / Infra** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge) ![Amazon EC2](https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) |
| **Monitoring** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F5DC00?style=for-the-badge&logo=grafana&logoColor=black) ![Jaeger](https://img.shields.io/badge/Jaeger-66CFE3?style=for-the-badge&logo=jaeger&logoColor=black) ![cAdvisor](https://img.shields.io/badge/cAdvisor-425066?style=for-the-badge) |
| **ETC** | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white) |

<br/>

# Monitoring

### Prometheus & Grafana

<!-- TODO: Django Metrics 대시보드 캡처 -->

<!-- TODO: Celery Worker Metrics 대시보드 캡처 -->

### Jaeger (Distributed Tracing)

<!-- TODO: 에이전트 파이프라인 trace 캡처 — 우리 프로젝트 차별점이라 섹션 분리 -->

<br/>

# Member

<!-- TODO: 인원수에 맞게 열 추가/삭제. 프로필 사진은 GitHub 아바타 URL 쓰면 편함:
     https://github.com/깃허브아이디.png -->

| Name | 이름1 | 이름2 | 이름3 | 이름4 | 이름5 | 이름6 |
| --- | --- | --- | --- | --- | --- | --- |
| **Profile** | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> |
| **Role** | Backend | Backend | Frontend | Frontend | DevOps | Leader |
| **GitHub** | [@id1](https://github.com/) | [@id2](https://github.com/) | [@id3](https://github.com/) | [@id4](https://github.com/) | [@id5](https://github.com/) | [@id6](https://github.com/) |

