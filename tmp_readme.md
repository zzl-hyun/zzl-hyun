<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,45:1F6FEB,100:7C3AED&height=220&section=header&text=KIHYEON&fontSize=68&fontColor=FFFFFF&fontAlignY=36&desc=FORWARD%20DEPLOYED%20ENGINEER%20%C2%B7%20BACKEND%20%C2%B7%20AI%20SYSTEMS&descAlignY=57&descSize=17&animation=fadeIn)

### 현장의 문제를 정의하고, 데이터와 AI를 연결해 작동하는 시스템으로 만듭니다.

백엔드 엔지니어링을 기반으로 문서 처리·실시간 통신·추천·업무 자동화 문제를 해결해 왔습니다.  
문제를 발견하고 요구사항을 구조화한 뒤, 빠르게 구현하고 운영 가능한 흐름으로 다듬는 일을 좋아합니다.

<a href="https://github.com/zzl-hyun?tab=repositories"><img src="https://img.shields.io/badge/Explore-My_Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="repositories" /></a>
<a href="mailto:kimgihyun877@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_Talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>

</div>

## How I work

`현장 문제 발견` → `요구사항·데이터 구조화` → `백엔드·AI 시스템 구현` → `운영 흐름 개선`

- 기능보다 먼저 사용자의 병목과 실패 조건을 정의합니다.
- 긴 작업, 비동기 처리, 실시간 갱신처럼 시스템의 경계를 명확하게 설계합니다.
- AI를 단독 기능이 아니라 기존 서비스와 연결되어 실제로 작동하는 파이프라인으로 구현합니다.
- 반복되는 문제는 자동화하고, 동시성·정합성·배포까지 운영 관점에서 점검합니다.

## Selected case studies

### Paper Summarizer — 긴 논문을 읽고 이해하는 비용 줄이기

> LLM 기반 논문 요약·시각화 플랫폼

| Problem | System | My contribution |
|---|---|---|
| 문서 처리와 AI 요약은 실행 시간이 길고 실패 지점도 달라 하나의 요청 흐름으로 다루기 어렵습니다. | 백엔드와 AI 워커의 책임을 분리하고 콜백으로 결과를 연결하는 비동기 처리 구조를 구성했습니다. | 콜백 연동을 구현하고 Gemini/OpenAI 요약 워커를 개선했습니다. |

`Spring Boot` `Java` `Python` `Gemini` `OpenAI` `AI Pipeline`

[Backend →](https://github.com/joomidang/paper-summarizer-backend) · [Summary Worker →](https://github.com/joomidang/paper-summarizer-summry-worker)

---

### GMG — 모두가 가능한 약속을 찾는 조율 비용 줄이기

> 참여자의 비선호 시간과 장소 조건을 함께 계산하는 약속 조율 서비스

| Problem | System | My contribution |
|---|---|---|
| 여러 참여자의 시간·장소 비선호를 사람이 직접 비교하면 조율 비용이 커지고 동시 참여 시 데이터 충돌도 발생할 수 있습니다. | 30분 단위 히트맵과 장소 추천을 계산하고, Kakao/Google Maps의 영업시간 데이터를 결합했습니다. 트랜잭션 커밋 이후 SSE로 결과를 갱신합니다. | 시간표 조회·수정, 동시 참여 레이스 컨디션 방지, 히트맵 집계 정합성을 개선했습니다. |

`Java 21` `Spring Boot 3.5` `JPA` `Flyway` `MySQL` `SSE`

[Backend →](https://github.com/project-GMG/backend)

<p align="center">
  <img src="https://github.com/user-attachments/assets/dee88061-eac3-4951-af87-b50f977f68a8" height="220" alt="GMG 모임 생성 화면" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/6ad969e7-7bc0-4a60-98ef-6e38032f51a6" height="220" alt="GMG 일정 조율 화면" />
</p>

---

### GameCast — 플레이 순간을 실시간 콘텐츠로 연결하기

> 게임 플레이, 녹화, AI 하이라이트 생성을 연결하는 미디어 서버

| Problem | System | My contribution |
|---|---|---|
| 실시간 플레이 연결부터 녹화 파일 저장, AI 하이라이트 결과 수신까지 서로 다른 처리 흐름을 하나의 서비스 경험으로 연결해야 합니다. | Socket.IO/WebRTC 시그널링과 녹화 흐름을 구성하고, S3 미디어 파이프라인에 AI 하이라이트 콜백을 연결했습니다. | 룸·영상·WebRTC 서비스와 하이라이트 콜백을 구현하고 Docker/AWS CI/CD 흐름을 구축했습니다. |

`TypeScript` `Express` `WebRTC` `Socket.IO` `S3` `Docker` `AWS`

[Server →](https://github.com/UMC-GameCast/gamecast-server)

<p align="center">
  <img src="./assets/GameCast/game-room.jpg" width="49%" alt="GameCast 게임방 준비 화면" />
  <img src="./assets/GameCast/highlight-editor.jpg" width="49%" alt="GameCast 하이라이트 자막 편집 화면" />
</p>

## Tools built from everyday friction

작은 불편도 반복되면 문제로 정의하고 직접 자동화합니다.

| Project | Problem → Solution | Built with |
|---|---|---|
| [🧾 Automatic Settlement](https://github.com/zzl-hyun/Automatic-settlement) | 반복되는 모임 정산 → 참여자별 N빵과 최종 송금 내역 자동 계산 | `Vanilla JS` `localStorage` |
| [🎵 Taskbar Music Widget](https://github.com/zzl-hyun/TaskbarMusicWidget) | 음악 탭을 찾는 번거로움 → 작업표시줄에서 재생·곡 정보·앱별 음량 제어 | `.NET 8` `WPF` `NAudio` |
| [⚡ Taskbar Speed Control](https://github.com/zzl-hyun/TaskbarSpeedControl) | 고정된 Windows 작업표시줄 동작 → 자동 숨김 속도와 프레임 제어 | `C#` `C++` `WinAPI` |

## Engineering foundation

| Area | Stack |
|---|---|
| Backend | `Java` `Spring Boot` `Python` `TypeScript` `Node.js` `Express` |
| Data | `MySQL` `Redis` `JPA` `Flyway` |
| AI systems | `OpenAI` `Gemini` `LLM Worker` `Callback Pipeline` |
| Infra & delivery | `Docker` `Nginx` `AWS` `GitHub Actions` `Gradle` `Git` |

## Evidence

<div align="center">
  <img src="https://img.shields.io/badge/Paper_Summarizer-107_commits-7C3AED?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Paper Summarizer 107 commits" />
  <img src="https://img.shields.io/badge/GameCast-136_commits-D817B8?style=for-the-badge&logo=webrtc&logoColor=white" alt="GameCast 136 commits" />
  <img src="https://img.shields.io/badge/GMG-24_commits-111111?style=for-the-badge&logo=springboot&logoColor=white" alt="GMG 24 commits" />

  <br/><br/>

  <img width="90%" src="./assets/metrics-languages.svg" alt="Languages activity based on authored commits" />
</div>

<div align="center">

### Define the problem. Build the system. Measure what changed.

<sub>Backend engineering for AI-powered, data-informed products.</sub>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,55:1F6FEB,100:0D1117&height=110&section=footer)

</div>
