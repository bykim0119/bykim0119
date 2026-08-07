## Hi, I'm Boyoon Kim👋
### AI / Agent Engineer

LLM Agent, AI 자동화, 실제 서비스에 적용되는 AI 시스템에 관심을 가지고 개발하고 있습니다.

단순히 모델을 호출하는 것을 넘어,  
AI가 **작업을 위임받고 실행하며 결과를 검증할 수 있는 시스템**을 만드는 것을 지향합니다.

---

## 🛠 주요 프로젝트

### [Hermes Agent Company](https://github.com/bykim0119/hermes-agent-company)

**Hermes Agent와 Codex CLI를 기반으로 구현한 코딩 서브에이전트 시스템**

- 장시간 코딩 작업을 독립적인 서브에이전트에 위임
- 작업 중에도 메인 Agent의 대화를 블로킹하지 않는 구조 구현
- 작업별 Discord Thread를 생성해 진행 상황과 결과 추적
- 여러 작업의 동시 실행, 작업 재개 및 취소 지원
- Planner / Coder / Reviewer / Tester 역할 기반 오케스트레이션 구조로 확장

`Python` `Hermes Agent` `Codex CLI` `Discord`

---

### 🎨 [ADGenService](https://github.com/bykim0119/ADGenService_team7)

**소상공인을 위한 AI 광고 생성 서비스**

- 제품 설명과 이미지를 기반으로 광고 이미지, 문구, 해시태그 생성
- FastAPI, Celery, Redis 기반 비동기 생성 파이프라인 구축
- GPT 요청 3개를 병렬화하여 평균 생성 시간을 약 **4초 단축**
- GKE 환경에서 Backend, Worker, Redis, GPU 기반 ComfyUI 서비스 배포

`FastAPI` `Celery` `Redis` `GKE` `SDXL` `GPT`

---
### 🔧 Hermes Agent 오픈소스 기여

**NousResearch/Hermes-Agent의 Discord 접근 제어 관련 버그 수정에 기여**

- `DISCORD_ALLOWED_USERS` 설정의 동작 불일치 발견
- OpenClaw → Hermes 설정 마이그레이션 과정에서 `"*"` 와일드카드가 정상적으로 처리되지 않는 원인 분석
- 수정안을 제출하고 Maintainer 피드백을 반영하여 개선
- 최종 수정 코드가 Hermes Agent 공식 프로젝트에 병합


## ⚙️ Tech Stacks

### AI / LLM

`Open AI API` · `RAG` · `PyTorch` · `LangGraph`

### Backend / Infrastructure

`Python` · `FastAPI` · `Docker` · `GKE` · `ComfyUI`

### Agent Development

`Hermes Agent` · `Codex CLI` · `Tool Use` · `Multi-Agent Orchestration`

### Collab Tools

`Github` · `Notion`

---

## Contact
bykim0119@gmail.com
