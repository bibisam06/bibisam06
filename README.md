## Hi there, I'm 한비 👋

**LLM 기반 서비스를 개발하는 AI Engineer**를 목표로 공부하고 있어요.  

<br>

### 🛠 Tech Stack

**Language**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

**Backend · AI**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_API-191919?style=flat-square&logo=anthropic&logoColor=white)

**Infra · Observability**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

<br>

### 🚀 Featured Project

#### 🔍 [ops-rca-agent](https://github.com/bibisam06/ops-agent) — LLM 기반 컨테이너 장애 진단 에이전트 `진행 중`
> 컨테이너 장애를 재현하고, LLM이 Docker · Prometheus 지표를 **직접 조회한 근거로만** 원인을 진단하는 도구

- **프레임워크 없이 tool use 루프 직접 구현**: 실패 재시도, 최대 10턴 제한, 출력 형식(유형·근거·조치) 고정
- **장애 재현 환경**: Docker Compose + FastAPI · Prometheus · cAdvisor, chaos 엔드포인트로 CPU 과부하 · 메모리 누수 · 에러 급증 재현
- **CPU 사용률 직접 계산**: docker stats 원본 값에서 컨테이너 CPU 시간 변화량 ÷ 시스템 CPU 시간 변화량 × 코어 수
- **트러블슈팅**: async 부하가 이벤트 루프를 막아 `/metrics` 수집이 끊기던 문제 → 동기 함수로 분리해 스레드풀에서 실행

<br>

### 📂 Other Projects

| 프로젝트 | 설명 | 기술 |
|---|---|---|
| 🚗 [**라즈베리파이 자율주행 자동차**](https://github.com/bibisam06/tabby-autodrive-lab) | 초음파 센서 40ms 타임아웃 · 중앙값 필터 · 히스테리시스로 노이즈 제거, 카메라 노출 고정으로 조명 문제 해결 | Python, OpenCV, RPi.GPIO |
| 🐶 [**포프린트**](레포링크) 👈 | 반려견 건강관리 앱 · **스토어 출시** · FitBark OAuth 2.0 연동, AWS 배포 | Node.js, AWS |
| 💇 [**헤어 상담 예약 서비스**](레포링크) 👈 | 🏆 **블레이버스 해커톤 대상** · 예약 API · DB 설계, Swagger로 프론트와 병렬 개발 | Spring Boot, JPA |

<br>

### 🌱 Currently Learning

- 🤖 **LLM 에이전트 평가**: 자동 채점 파이프라인 구축 중
- 🔍 **Elasticsearch**: 검색 엔진 구조와 인덱싱
- 🧩 **알고리즘 (Java)**: 꾸준히 풀이 중

<br>

### 🏆 Problem Solving

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=bebee2020)](https://solved.ac/u/bebee2020) 👈

<br>

### 📫 Contact

[![Email](https://img.shields.io/badge/hb.jade00@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hb.jade00@gmail.com)
