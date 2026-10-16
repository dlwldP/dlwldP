## 👀 소개
* ⚙️ Spring Boot, ASP.NET Core 기반 백엔드 개발 경험
* ☁️ VDI, Kubernetes, Harbor, VMware, Linux 등 클라우드/가상화 인프라 경험
* 🧩 백엔드 · 프론트엔드(React) · AI 애플리케이션(LangChain/LangGraph, RAG, FastAPI) 개발 경험
* 🌱 백엔드 + 클라우드 인프라 공부 중

<br/>

## 💼 Experience
업데이트 예정

<br/>

## 🧱 기술

### 백엔드
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=OpenJDK&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=C-Sharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)

### 클라우드 · 인프라
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=Kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=VMware&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=AmazonAWS&logoColor=white)

### 프론트엔드 · 데이터
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white)
![MSSQL](https://img.shields.io/badge/MSSQL-CC2927?style=flat-square&logo=MicrosoftSQLServer&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=Oracle&logoColor=white)

<br/>

## 🚀 Projects

### 🔍 [KubeLens](https://github.com/dlwldP/KubeLens) — 자연어 Kubernetes 장애 진단 에이전트 `2026.10`
> "왜 이 파드가 계속 죽어?"라고 물으면, **조회만 해서** 근거가 붙은 원인 후보를 보여줍니다.
* **Read-only를 두 겹으로 보장** — 쓰기·Secret·exec 권한 없는 RBAC + get/list만 노출하는 도구 레이어, 쓰기 API 호출이 소스에 없는지 AST로 테스트
* **증거 없는 주장 금지** — 모든 원인 후보가 실제 도구 호출 ID를 인용해야 통과, 아니면 재생성
* **정확도를 측정 가능하게** — kind 클러스터에 장애 6종(CrashLoop, OOMKilled, ImagePull 등)을 재현하고 자동 채점하는 평가 하네스
* LLM 전달 전 토큰·키·JWT·PEM 마스킹(속성 기반 테스트로 검증), SSE 실시간 트레이스 UI
* `LangGraph` `FastAPI` `React` `kind` `GitHub Actions`

### 📈 [stock-monitor](https://github.com/dlwldP/stock-monitor) — 관심종목 알림 · 자산 대시보드 `2026.08`
* 6가지 알림 규칙(목표가·등락률·거래량 급증·신고가/신저가) → 디스코드/이메일/인앱 발송
* **Mock / 실 API 구현체 분리**로 키 없이도 전 기능 동작, 실계좌 연동까지 검증
* 캔들 차트를 라이브러리 없이 SVG로 직접 렌더링
* `Spring Boot` `Java` `증권사 Open API`

### 🚦 [Deploy-gate](https://github.com/dlwldP/Deploy-gate) — claims 기반 배포 승인 게이트 `2026.07 – 08`
* CI/CD 배포 직전에 호출되는 인가 서비스
* **저장소 write 권한 ≠ 배포 권한**으로 분리, 스택별 승인 단계 차등(즉시 / 1인 / 2인 승인)
* `Spring Boot` `Java`

### 🏠 SWYP 웹 13기 — 자취방 계약 체크리스트 서비스 `2026.03 – 05` · 팀 프로젝트
* Naver·Google **OAuth2 소셜 로그인**, JWT 발급·검증·갱신 담당
* AWS EC2 프로비저닝, Elastic IP·DNS 연동, local/prod 프로파일 분리로 배포 인프라 구성
* `Spring Boot` `AWS` · [서비스 바로가기](https://bangcheck.site)

<br/>

## 📊 GitHub 통계
![Top Langs](https://raw.githubusercontent.com/dlwldP/dlwldP/main/profile-summary-card-output/default/1-repos-per-language.svg)
![GitHub stats](https://raw.githubusercontent.com/dlwldP/dlwldP/main/profile-summary-card-output/default/3-stats.svg)

<br/>

## 📊 AI Token 사용량

<p align="center">
  <a href="https://tokscale.ai/u/dlwldP">
    <img src="https://tokscale.ai/api/badge/dlwldP/svg" alt="Tokscale Badge" />
  </a>
</p>

<br/>

## 📬 Contact
* 📧 이메일 — jiye7961@gmail.com
* 🌐 포트폴리오 — https://dlwldp.github.io
* 🎯 기술블로그 — https://velog.io/@jiye_1124/posts
