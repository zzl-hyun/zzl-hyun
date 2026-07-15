<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,45:1F6FEB,100:7C3AED&height=230&section=header&text=KIHYEON&fontSize=72&fontColor=FFFFFF&fontAlignY=36&desc=BACKEND%20ENGINEER%20%C2%B7%20SYSTEM%20BUILDER&descAlignY=57&descSize=18&animation=fadeIn)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=760&lines=Complexity+in%2C+simplicity+out.;AI+pipelines+%C2%B7+Real-time+systems+%C2%B7+Backend+architecture;%EB%8F%8C%EC%95%84%EA%B0%80%EB%8A%94+%EC%BD%94%EB%93%9C%EB%A5%BC+%EB%84%98%EC%96%B4%2C+%EC%9A%B4%EC%98%81%EB%90%98%EB%8A%94+%EC%8B%9C%EC%8A%A4%ED%85%9C%EC%9D%84+%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4.)](https://git.io/typing-svg)

<a href="https://github.com/zzl-hyun?tab=repositories"><img src="https://img.shields.io/badge/Explore-My_Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="repositories" /></a>
<a href="mailto:kimgihyun877@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_Talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
<a href="https://github.com/zzl-hyun?tab=followers"><img src="https://img.shields.io/github/followers/zzl-hyun?style=for-the-badge&logo=github&label=Follow&color=1F6FEB" alt="followers" /></a>
<img src="https://komarev.com/ghpvc/?username=zzl-hyun&style=for-the-badge&color=7C3AED&label=PROFILE+VIEWS" alt="profile views" />

</div>

## `> whoami`

```text
현실의 복잡한 문제를 명확한 도메인과 안정적인 API로 바꿉니다.
AI 작업 파이프라인부터 실시간 통신, 외부 API 연동까지
서비스의 흐름 전체를 이해하고 끝까지 구현하는 백엔드 개발자입니다.
```

- **Product-minded** — 기능의 개수보다 사용자의 병목을 먼저 찾습니다.
- **Architecture-aware** — 책임, 경계, 실패 지점을 설계에 드러냅니다.
- **Production-ready** — 비동기 처리, 실시간 갱신, 배포와 운영까지 고민합니다.

## Featured builds

<table>
<tr>
<td width="50%" valign="top">
<p align="center">
  <a href="https://github.com/joomidang"><img src="https://github.com/joomidang.png?size=160" width="82" alt="주미당 로고" /></a>
</p>
<h3 align="center">Paper Summarizer</h3>
<p><b>GPT 기반 논문 요약·시각화 플랫폼</b></p>
<p>문서 처리와 AI 요약 작업을 분리한 백엔드/워커 구조. 긴 작업의 경계를 나누고 서비스 간 흐름을 설계했습니다.</p>
<p><b>My Impact</b> · 공개 커밋 107회<br/>회원·인증 API와 배포/콜백 연동을 구현하고, Gemini/OpenAI 요약 워커를 개선했습니다.</p>
<p><code>Spring Boot</code> <code>Java</code> <code>Python</code> <code>AI Pipeline</code></p>
<a href="https://github.com/joomidang/paper-summarizer-backend">Backend →</a><br/>
<a href="https://github.com/joomidang/paper-summarizer-summry-worker">Summary Worker →</a>
</td>
<td width="50%" valign="top">
<p align="center">
  <a href="https://github.com/UMC-GameCast"><img src="https://github.com/UMC-GameCast.png?size=160" width="82" alt="GameCast 로고" /></a>
</p>
<h3 align="center">GameCast</h3>
<p><b>게임 플레이를 실시간으로 연결하는 미디어 서버</b></p>
<p>Socket.IO/WebRTC 시그널링, 녹화 흐름과 AI 하이라이트 콜백을 연결하고 S3 기반 미디어 파이프라인을 구축했습니다.</p>
<p><b>My Impact</b> · 공개 커밋 136회<br/>룸·영상·WebRTC 서비스와 하이라이트 콜백을 구현하고, Docker/AWS CI/CD 흐름을 구축했습니다.</p>
<p><code>TypeScript</code> <code>Express</code> <code>WebRTC</code> <code>Socket.IO</code></p>
<a href="https://github.com/UMC-GameCast/gamecast-server">Server →</a>
</td>
</tr>
<tr>
<td colspan="2" valign="top">
<p align="center">
  <a href="https://github.com/project-GMG"><img src="https://github.com/project-GMG.png?size=200" width="120" alt="GMG 가면가 로고" /></a>
</p>
<h3 align="center">GMG — 가면가</h3>
<p><b>비선호 데이터를 이용해 약속 조율 비용을 줄이는 서비스</b></p>
<p>30분 단위 히트맵과 장소 추천을 계산하고, 트랜잭션 커밋 이후 SSE로 결과를 갱신합니다. Kakao/Google Maps 데이터를 결합해 영업시간과 참여자 비선호까지 추천에 반영했습니다.</p>
<p><b>My Impact</b> · 공개 커밋 24회<br/>참여자 시간표 조회·수정, 동시 참여 레이스 컨디션 방지, 히트맵 집계 정합성을 개선했습니다.</p>
<p><code>Java 21</code> <code>Spring Boot 3.5</code> <code>JPA</code> <code>Flyway</code> <code>MySQL</code> <code>SSE</code></p>
<a href="https://github.com/project-GMG/backend">Backend →</a>
<br/><br/>
<p align="center">
  <img src="https://github.com/user-attachments/assets/dee88061-eac3-4951-af87-b50f977f68a8" height="300" alt="GMG 모임 생성 화면" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/6ad969e7-7bc0-4a60-98ef-6e38032f51a6" height="300" alt="GMG 일정 조율 화면" />
</p>
</td>
</tr>
</table>

<div align="center">
  <a href="https://github.com/joomidang/paper-summarizer-backend"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=joomidang&repo=paper-summarizer-backend&theme=github_dark&hide_border=true&border_radius=10" alt="Paper Summarizer backend" /></a>
  <a href="https://github.com/joomidang/paper-summarizer-summry-worker"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=joomidang&repo=paper-summarizer-summry-worker&theme=github_dark&hide_border=true&border_radius=10" alt="Paper Summarizer worker" /></a>
  <a href="https://github.com/UMC-GameCast/gamecast-server"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=UMC-GameCast&repo=gamecast-server&theme=github_dark&hide_border=true&border_radius=10" alt="GameCast server" /></a>
  <a href="https://github.com/project-GMG/backend"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=project-GMG&repo=backend&theme=github_dark&hide_border=true&border_radius=10" alt="GMG backend" /></a>
</div>

### Side quests

<sub>생활 속 작은 불편을 그냥 지나치지 않고 직접 도구로 해결합니다.</sub>

| Project | What it does | Built with |
|---|---|---|
| [🧾 Automatic Settlement](https://github.com/zzl-hyun/Automatic-settlement) | 참여자별 지출을 1/N로 나누고 최종 송금 내역을 계산하는 브라우저 가계부 | `Vanilla JS` `localStorage` |
| [🎵 Taskbar Music Widget](https://github.com/zzl-hyun/TaskbarMusicWidget) | Windows 작업표시줄에서 재생 제어·곡 정보·앱별 음량을 다루는 미니 위젯 | `.NET 8` `WPF` `NAudio` |
| [⚡ Taskbar Speed Control](https://github.com/zzl-hyun/TaskbarSpeedControl) | 작업표시줄 자동 숨김 속도와 프레임을 네이티브 훅으로 제어하는 유틸리티 | `C#` `C++` `WinAPI` |

## Engineering toolbox

<div align="center">

### Core

[![Core](https://skillicons.dev/icons?i=java,spring,py,ts,nodejs,express&theme=dark)](https://skillicons.dev)

### Data · Infra · Delivery

[![Infra](https://skillicons.dev/icons?i=mysql,redis,docker,nginx,aws,githubactions,gradle,git&theme=dark)](https://skillicons.dev)

</div>

```mermaid
flowchart LR
    A[Problem] --> B[Domain model]
    B --> C[API & async flow]
    C --> D[Data & external systems]
    D --> E[Deploy & observe]
    E -. feedback .-> A
```

<details>
<summary><b>What I care about when building</b></summary>
<br/>

| Area | Focus |
|---|---|
| API | 예측 가능한 계약, 일관된 오류 응답, 입력 경계 검증 |
| Data | 명시적인 트랜잭션 경계, 안전한 마이그레이션, 쿼리 비용 |
| Async | 재시도와 멱등성, 이벤트 발행 시점, 실패 격리 |
| Real-time | 연결 수명주기, heartbeat, 프록시 버퍼링, graceful cleanup |
| Delivery | 재현 가능한 빌드, 컨테이너화, 환경별 설정 분리 |

</details>

## Proof of work

<div align="center">
  <img src="https://img.shields.io/badge/Paper_Summarizer-107_commits-7C3AED?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Paper Summarizer 107 commits" />
  <img src="https://img.shields.io/badge/GameCast-136_commits-D817B8?style=for-the-badge&logo=webrtc&logoColor=white" alt="GameCast 136 commits" />
  <img src="https://img.shields.io/badge/GMG-24_commits-111111?style=for-the-badge&logo=springboot&logoColor=white" alt="GMG 24 commits" />
</div>

### Languages activity

<div align="center">
  <img width="90%" src="./assets/metrics-languages.svg" alt="Languages activity based on authored commits" />
</div>

### Isometric contribution calendar

<div align="center">
  <img width="90%" src="./assets/metrics-isocalendar.svg" alt="Full-year isometric commit calendar" />
</div>

<div align="center">

### Build clearly. Ship reliably. Improve continuously.

<sub>Thanks for stopping by — interesting systems are always worth a conversation.</sub>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,55:1F6FEB,100:0D1117&height=110&section=footer)

</div>
