<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:326CE5,100:6DB33F&height=180&section=header&text=dlwldP&fontSize=50&fontColor=ffffff&fontAlignY=35" alt="header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=326CE5&center=true&vCenter=true&width=520&lines=Backend+%26+Cloud+Infra+Developer;Spring+Boot+%7C+Kubernetes+%7C+AWS;From+API+to+Deployment+%26+Operations" alt="Typing SVG" />
</p>

## 👀 소개
**백엔드부터 배포·운영까지 다루는 개발자입니다.**

* ⚙️ **백엔드** — Spring Boot, ASP.NET Core 기반 API · 서비스 개발
* ☁️ **인프라** — Kubernetes, Harbor, VMware, VDI, Linux 등 컨테이너 · 가상화 환경 구축과 운영
* 🏢 **현재** — ERP 개발
* 🌱 **집중하는 것** — 백엔드 + 클라우드 인프라
* 🌐 **포트폴리오** — https://dlwldp.github.io

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

### 💸 [AWS 얼마야?](https://github.com/dlwldP/Awscal) — 초보자용 AWS 비용 계산기 `2026.10`
> "하고 싶은 것"을 고르면 필요한 AWS 구성과 예상 월 비용을 비교해줍니다. · [바로 써보기](https://dlwldp.github.io/Awscal/)
* 목적별 템플릿 5종 × 규모 프리셋 3종 × 리전 6곳, 구성안 2~3개를 항목별 금액과 함께 비교
* **숨은 비용 경고**: 퍼블릭 IPv4, NAT Gateway, 데이터 전송, 상시 실행, Multi-AZ 등 초보자가 놓치는 과금 항목을 알려줌
* EC2·RDS·Lambda·S3 등 16종 서비스를 직접 담아 계산하는 계산기, 사용 시간·옵션 조정 지원
* **AWS Price List API로 주 1회 가격 자동 갱신**: 수집 → 테스트 → 커밋 → 재배포를 GitHub Actions로 자동화하고, 실패하면 기존 가격 유지
* 서버 없이 순수 HTML/JS로 만들어 GitHub Pages에 배포(테스트 통과 시에만 배포)
* `JavaScript` `Python` `GitHub Actions` `GitHub Pages`

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

## ✍️ Latest Blog Posts
<!-- BLOG-POST-LIST:START -->
- [오픽 2주 준비로 IH 받은 후기 &lpar;공부법 + 시험장 팁&rpar;](https://velog.io/@jiye_1124/%EC%98%A4%ED%94%BD-2%EC%A3%BC-%EC%A4%80%EB%B9%84%EB%A1%9C-IH-%EB%B0%9B%EC%9D%80-%ED%9B%84%EA%B8%B0-%EA%B3%B5%EB%B6%80%EB%B2%95-%EC%8B%9C%ED%97%98%EC%9E%A5-%ED%8C%81)
- [&quot;2026년 10월, 지금 나는 어디쯤 와 있을까&quot;](https://velog.io/@jiye_1124/2026%EB%85%84-10%EC%9B%94-%EC%A7%80%EA%B8%88-%EB%82%98%EB%8A%94-%EC%96%B4%EB%94%94%EC%AF%A4-%EC%99%80-%EC%9E%88%EC%9D%84%EA%B9%8C)
- [AI 뭐 써? 2편 — 개발자용으로 넓히고, AI에게 데이터를 맡기기 전에 정한 것들](https://velog.io/@jiye_1124/AI-%EB%AD%90-%EC%8D%A8-2%ED%8E%B8-%EA%B0%9C%EB%B0%9C%EC%9E%90%EC%9A%A9%EC%9C%BC%EB%A1%9C-%EB%84%93%ED%9E%88%EA%B3%A0-AI%EC%97%90%EA%B2%8C-%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC-%EB%A7%A1%EA%B8%B0%EA%B8%B0-%EC%A0%84%EC%97%90-%EC%A0%95%ED%95%9C-%EA%B2%83%EB%93%A4)
- [AI 뭐 써? — 목적을 고르면 AI 툴 2~3개를 추천해주는 사이트를 만들며](https://velog.io/@jiye_1124/AI-%EB%AD%90-%EC%8D%A8-%EB%AA%A9%EC%A0%81%EC%9D%84-%EA%B3%A0%EB%A5%B4%EB%A9%B4-AI-%ED%88%B4-23%EA%B0%9C%EB%A5%BC-%EC%B6%94%EC%B2%9C%ED%95%B4%EC%A3%BC%EB%8A%94-%EC%82%AC%EC%9D%B4%ED%8A%B8%EB%A5%BC-%EB%A7%8C%EB%93%A4%EB%A9%B0)
- [# &quot;AWS 얼마야?&quot; 2편 — 기능을 더하다가, 덜어내는 법을 배웠다](https://velog.io/@jiye_1124/AWS-%EC%96%BC%EB%A7%88%EC%95%BC-2%ED%8E%B8-%EA%B8%B0%EB%8A%A5%EC%9D%84-%EB%8D%94%ED%95%98%EB%8B%A4%EA%B0%80-%EB%8D%9C%EC%96%B4%EB%82%B4%EB%8A%94-%EB%B2%95%EC%9D%84-%EB%B0%B0%EC%9B%A0%EB%8B%A4)
<!-- BLOG-POST-LIST:END -->

➡️ [더 많은 글 보기](https://velog.io/@jiye_1124/posts)

<br/>

## 📊 GitHub 통계
![Top Langs](https://raw.githubusercontent.com/dlwldP/dlwldP/main/profile-summary-card-output/default/1-repos-per-language.svg)
![GitHub stats](https://raw.githubusercontent.com/dlwldP/dlwldP/main/profile-summary-card-output/default/3-stats.svg)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dlwldP/dlwldP/output/github-snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/dlwldP/dlwldP/output/github-snake.svg" />
</picture>

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

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6DB33F,100:326CE5&height=120&section=footer" alt="footer" />
</p>
