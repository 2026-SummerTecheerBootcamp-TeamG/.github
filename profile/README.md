<div align="center">

# TripCanvas

### 2026 Techeer Summer BootCamp — TEAM G

**AI 여행 플래너 에이전트**

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

**Service URL**
https://www.tripcanvas.cloud/

**Medium**
https://medium.com/@1231435e/trip-canvas-a978aac9cc4b?postPublishedType=repub

<br/>

# Demo

<br/>



### 온보딩 페이지
<img width="1228" height="2748" alt="image" src="https://github.com/user-attachments/assets/62b768b8-a663-4d01-9cc6-55aca13bbc3d" />
<img width="1228" height="991" alt="image" src="https://github.com/user-attachments/assets/08e6d70a-0715-408a-88f9-6be6a522a1b5" />
<img width="1228" height="991" alt="image" src="https://github.com/user-attachments/assets/9f5834cc-f563-4ddb-9103-d5541cc50ec9" />

<br/>

### 여행 계획 요청 (자연어 입력)
<img width="1228" height="960" alt="image" src="https://github.com/user-attachments/assets/de609f4a-0e22-471d-80f6-8bf28861dada" />

<br/>

### 일정 생성 결과
<img width="1228" height="3147" alt="image" src="https://github.com/user-attachments/assets/4cf79525-cf5e-413a-ac38-5ba8ad3d8a01" />
<img width="1219" height="991" alt="image" src="https://github.com/user-attachments/assets/c3de2306-2634-43af-ac6e-457eb53c9d79" />
<img width="1210" height="990" alt="image" src="https://github.com/user-attachments/assets/26ad0527-7e46-42e3-be94-77e4969e3b54" />

<br/>

### 대화형 일정 수정
<img width="1228" height="3004" alt="image" src="https://github.com/user-attachments/assets/29af2dff-b4a0-479e-bcfc-2ba0ac14393f" />

<br/>

### 마이페이지
<img width="1228" height="1368" alt="image" src="https://github.com/user-attachments/assets/a486bb0d-56d2-4e98-8f05-496d8b906b8a" />
<img width="1228" height="2841" alt="image" src="https://github.com/user-attachments/assets/a287bb76-7158-48de-9fe8-290b0aec8333" />
<img width="1219" height="989" alt="image" src="https://github.com/user-attachments/assets/0a73b174-4243-44be-83ac-5edd7782a3e5" />
<img width="1216" height="989" alt="image" src="https://github.com/user-attachments/assets/a4ec8ee7-416f-459e-9f21-fca5ca565998" />

<br/>
<br/>

# API
<img width="1463" height="1966" alt="image" src="https://github.com/user-attachments/assets/b75296d2-25a4-461e-8a2d-f30d96ccdfab" />

<br/>
<br/>

# System Architecture
<img width="1236" height="837" alt="image" src="https://github.com/user-attachments/assets/93ee7ddb-138b-456d-8fc8-65e37caf2158" />

<br/>
<br/>

# ERD
<img width="1581" height="708" alt="image" src="https://github.com/user-attachments/assets/ef38a474-998a-4ebb-8440-2c358e48301b" />

<br/>
<br/>

# Tech Stack

| Field | Technology |
|---|---|
| **Frontend** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) |
| **Backend** | ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![Django REST](https://img.shields.io/badge/Django_REST_Framework-A30000?style=for-the-badge&logo=django&logoColor=white) ![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white) ![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Amazon RDS](https://img.shields.io/badge/Amazon_RDS-527FFF?style=for-the-badge) |
| **AI / External API** | ![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white) ![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white) ![LiteAPI](https://img.shields.io/badge/LiteAPI-6C63FF?style=for-the-badge) ![SerpApi](https://img.shields.io/badge/SerpApi-000000?style=for-the-badge) |
| **DevOps / Infra** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge) ![Amazon EC2](https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) |
| **Monitoring** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F5DC00?style=for-the-badge&logo=grafana&logoColor=black) ![cAdvisor](https://img.shields.io/badge/cAdvisor-425066?style=for-the-badge) |
| **ETC** | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white) |

<br/>

# Monitoring

### Prometheus & Grafana
**Django Metrics**
<img width="1919" height="990" alt="image" src="https://github.com/user-attachments/assets/b805417f-6a42-4c74-81b2-380bbe536ad9" />

**Celery Worker Metrics**
<img width="1919" height="988" alt="image" src="https://github.com/user-attachments/assets/8ae6409c-2422-4ab9-a4f4-da363150d3eb" />

**Operating Dashboard**
<img width="1919" height="987" alt="image" src="https://github.com/user-attachments/assets/8ef02124-29df-409e-a227-b8c8ca3c8ec6" />

<br/>

# Member

| Name | 이윤서 | 이예빈 | 김형수 | 민재헌 |
| --- | --- | --- | --- | --- |
| **Profile** | <img src="https://ca.slack-edge.com/T0BDGGPG7V3-U0BD8M7T1LP-e4e7a9f12c60-512" width="100" height="100" /> | <img src="https://ca.slack-edge.com/T0BDGGPG7V3-U0BDRV5DR4Z-e140a3a94114-512" width="100" height="100" /> | <img src="https://ca.slack-edge.com/T0BDGGPG7V3-U0BDN37QH5L-5d3a783c73af-512" width="100" height="100" /> | <img src="https://ca.slack-edge.com/T0BDGGPG7V3-U0BDS53JKLH-f383936e2d3f-512" width="100" height="100" /> |
| **Role** | Full-Stack | Full-Stack | Full-Stack | Full-Stack, DevOps |
| **GitHub** | [@LeeYunseo04](https://github.com/LeeYunseo04) | [@yeab-in](https://github.com/yeab-in) | [@12314352](https://github.com/12314352) | [@CPRNDL](https://github.com/CPRNDL) |

