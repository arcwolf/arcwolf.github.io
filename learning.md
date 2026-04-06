---
layout: page
# title: Seongcheol Baek
title: Project
---

<style>
.page h3 {
  font-style: italic;
}
</style>

2026.04.06 - 2026.04.06
: **Orchestration Engineering (SW 시스템 설계 관점)**
> #### 정의
> 여러 서비스/컴포넌트를 **의도된 실행 흐름으로 묶고 제어하는 설계 영역**  
> → 기능 구현이 아니라 **흐름 + 상태 + 제어 설계**
>
>
> #### 핵심 설계 요소
>
> ##### 1. Workflow (흐름)
> - 순차 / 병렬 / 조건 분기 / 반복
> - DAG 구조 권장
>
> ##### 2. State Management (상태)
> - 중간 결과 저장
> - 실패 시 재개 가능 여부
>
> ##### 3. Dependency Control (의존성)
> - 서비스 호출 순서 및 데이터 의존성 관리
> - 느슨한 결합 유지
>
> ##### 4. Error Handling
> - retry / fallback 전략
> - idempotency 보장
>
> ##### 5. Scheduling & Trigger
> - cron vs event-driven
> - latency / 비용 trade-off 고려
>
> ##### 6. Observability
> - 로그, 메트릭, 트레이싱
> - 실행 흐름 추적 필수
>
>
> #### 주요 패턴
>
> ##### 1. Centralized Orchestration
> - 중앙 컨트롤러가 흐름 제어
> - 장점: 명확, 디버깅 쉬움
> - 단점: SPOF
>
> ##### 2. Choreography (Event-driven)
> - 서비스가 이벤트 기반으로 자율 동작
> - 장점: 확장성, 느슨한 결합
> - 단점: 흐름 파악 어려움
>
> ##### 3. Hybrid
> - 중앙 제어 + 이벤트 혼합 (실무에서 가장 일반적)
>
>
> #### 설계 체크리스트
>
> - 전체 workflow를 한눈에 볼 수 있는가?
> - 실패 시 어디부터 재시작 가능한가?
> - 중복 실행에도 안전한가? (idempotent)
> - 병렬 처리 가능한 구조인가?
> - 서비스 간 결합도는 낮은가?
> - 불필요한 호출을 줄였는가?
>
>


### Linux
2026.03.24
: **WSL2** / 하이퍼바이저 (Hyper-V)
> <img src="{{ site.baseurl }}{{ site.figs.learning_wsl2_hyper-v-architecture_1 }}" />
[<a href="https://learn.microsoft.com/ko-kr/windows-server/virtualization/hyper-v/architecture" target="_blank">Link</a>]

2026.03.24
: **WSL2** / Linux GUI 앱에 대한 지원 설치
> <img src="{{ site.baseurl }}{{ site.figs.learning_wsl2_wsl-gui-screenshot_1 }}" />
[<a href="https://learn.microsoft.com/ko-kr/windows/wsl/tutorials/gui-apps" target="_blank">Link</a>]


### MICSELLANEOUS
2026.03.02
: **Computer Science** / Data Structure
> <img src="{{ site.baseurl }}{{ site.figs.project_prgm_dev_data_optimization_1 }}" />
[<a href="https://www.cs.umd.edu/class/spring2021/cmsc420-0101/Lects/lect02-basics.pdf" target="_blank">Source</a>]
