<div align="center">

# 🗺️ TripCanvas

### 2026 Techeer Summer BootCamp — TEAM G

**MCP 기반 AI 여행 플래너 에이전트**

<!-- TODO: 온보딩/메인 화면 GIF 또는 대표 배너 이미지 1장 -->
<!-- <img src="배너.gif" width="80%" /> -->

</div>

<br/>

# 📖 Introduction

> **"일본 후쿠오카 3박4일, 성인 1명, 쇼핑 중심으로 예산 80만 원"** — 한 문장이면 충분합니다.

**TripCanvas**는 자연어 요청 하나로 항공권 · 숙소 · 일정을 한 번에 설계해 주는 AI 여행 플래너입니다.
Claude가 MCP를 통해 여러 여행 서비스를 도구처럼 연결하고,
역할별 에이전트가 협업하여 맞춤형 여행 일정을 완성합니다.

### ✨ 핵심 기능

- **자연어 → 여행 계획**: 목적지 · 기간 · 테마 · 예산을 문장에서 파싱해 구조화
- **항공 에이전트**: 예산 내 최적 항공편 탐색 (Google Flights)
- **숙소 에이전트**: 위치 · 가격 기반 호텔 후보 추천 (LiteAPI)
- **일정 에이전트**: 동선을 고려한 일자별 방문 순서 최적화 (Google Places)
- **대화형 수정**: "둘째 날 일정 좀 여유롭게 바꿔줘" — 대화로 일정 편집

<!-- TODO: 배포 URL 생기면 여기에 -->
🔗 **Service**: https://www.tripcanvas.cloud/
<!-- TODO: Medium/기술 블로그 회고 글 링크 -->
📝 **Medium**: https://medium.com/@1231435e/trip-canvas-a978aac9cc4b?postPublishedType=repub

<br/>

# 🎬 Demo

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

# 🔌 API

<!-- TODO: Swagger/API 명세 캡처 이미지 2~4장 -->

<br/>

# 🏗️ System Architecture

<!-- TODO: 아키텍처 다이어그램 1장 -->

<br/>

# 🗄️ ERD

<!-- TODO: ERD 이미지 1장 -->

<br/>

# 🛠️ Tech Stack

| 분야 | 기술 |
| --- | --- |
| **Frontend** | <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"> |
| **Backend** | <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"> <img src="https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white"> <img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white"> <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"> |
| **AI / Agent** | <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white"> <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"> |
| **External API** | <img src="https://img.shields.io/badge/Google%20Flights%20(SerpApi)-4285F4?style=for-the-badge&logo=google&logoColor=white"> <img src="https://img.shields.io/badge/LiteAPI-FF6C37?style=for-the-badge"> <img src="https://img.shields.io/badge/Google%20Places-34A853?style=for-the-badge&logo=googlemaps&logoColor=white"> |
| **Database** | <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white"> |
| **Async Task** | <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"> |
| **DevOps** | <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white"> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"> <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"> |
| **Monitoring** | <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"> <img src="https://img.shields.io/badge/Loki-F5A800?style=for-the-badge&logo=grafana&logoColor=white"> <img src="https://img.shields.io/badge/Jaeger-66CFE3?style=for-the-badge&logo=jaeger&logoColor=black"> |
| **ETC** | <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"> |

<br/>

# 📊 Monitoring

### Prometheus & Grafana

<!-- TODO: Django Metrics 대시보드 캡처 -->

<!-- TODO: Celery Worker Metrics 대시보드 캡처 -->

### Jaeger (Distributed Tracing)

<!-- TODO: 에이전트 파이프라인 trace 캡처 — 우리 프로젝트 차별점이라 섹션 분리 -->

<br/>

# 👥 Member

<!-- TODO: 인원수에 맞게 열 추가/삭제. 프로필 사진은 GitHub 아바타 URL 쓰면 편함:
     https://github.com/깃허브아이디.png -->

| Name | 이름1 | 이름2 | 이름3 | 이름4 | 이름5 | 이름6 |
| --- | --- | --- | --- | --- | --- | --- |
| **Profile** | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> | <img src="" width="100" height="100" /> |
| **Role** | Backend | Backend | Frontend | Frontend | DevOps | Leader |
| **GitHub** | [@id1](https://github.com/) | [@id2](https://github.com/) | [@id3](https://github.com/) | [@id4](https://github.com/) | [@id5](https://github.com/) | [@id6](https://github.com/) |

