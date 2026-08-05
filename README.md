# 김준섭 | Agentic Software Engineer

> AI 에이전트가 일관된 규칙과 검증 절차 안에서  
> 안정적으로 개발할 수 있는 시스템을 설계합니다.

안녕하세요. AI 코딩 에이전트에서 반복되는 맥락 유실, 품질의 불확실성, 의도하지 않은 코드 변경과 유지보수 문제를 하네스로 줄여가는 Agentic Software Engineer 김준섭입니다.

역할별 에이전트, 지속 지침, 재사용 가능한 스킬, 실행 훅과 검증 게이트를 활용해 에이전트가 충분한 맥락과 제한된 권한 안에서 작업하고, 결과를 명확한 기준으로 검증할 수 있는 개발 환경을 만들고 있습니다. 이를 통해 한 명의 개발자가 Android·Backend·Web·배포까지 더 넓은 범위를 안정적으로 다룰 수 있도록 합니다.

영상처리·Windows 프로그램·웹·백엔드·서버 운영을 경험했으며, 서로 다른 요구사항을 실제로 동작하는 프로그램으로 연결해왔습니다. 겉모습만 완성된 프로그램보다 실제 문제를 해결하는 소프트웨어를 만들고자 합니다.


---

## Current Work

### EMS Platform

현장 대원이 사용하는 Android 앱, 관리자용 Web, FastAPI 백엔드와 배포 환경을 통합한 응급의료 현장 대응 플랫폼입니다.

응급 이벤트 발생부터 출동, 병원 이송, 생체징후와 디바이스 상태 관리, 외부 시스템 연동까지 하나의 흐름으로 처리합니다.

한 명의 개발자로서 에이전틱 엔지니어링을 활용해 Android·Backend·Web 전반의 기능 개발과 시스템 통합, 검증, 배포·운영을 수행했습니다. 여러 기술 영역을 일관된 기준으로 관리하기 위해 프로젝트 전용 에이전틱 개발 하네스를 설계했습니다.

**My Role & Responsibilities**

- Kotlin 기반 현장 대응 Android 앱 개발
- FastAPI·PostgreSQL 기반 백엔드 API와 실시간 상태 처리 개발
- Android 앱과 Backend 간 인증 및 데이터 계약 연동
- React·TypeScript 기반 관리자 Web 기능 개발 및 연동
- 응급 이벤트, 출동 단계, 차량·디바이스와 외부 시스템의 데이터 흐름 통합
- Docker·Jenkins 기반 빌드·배포 자동화
- 헬스체크, 장애 알림과 배포·운영 이력 관리
- Android·Backend·Web 간 통합 테스트와 운영 환경 검증

**Agentic Engineering**

- Android·Backend·Web 전문 서브에이전트와 읽기 전용 리뷰 에이전트의 역할·권한 분리
- 루트·서브프로젝트별 지속 지침과 작업별 스킬을 통한 아키텍처·진행 맥락 관리
- 단계별 위임, worktree 격리와 실행 훅을 통한 병렬 작업 및 변경 범위 통제
- 빌드·테스트·Contract Gate·독립 리뷰를 연결한 검증 흐름 구축

---

### [SageTaechang](https://github.com/JakeKim4926/SageTaechang)

인쇄·문서 업무에서 반복되는 엑셀 확인, 단가 조회, 문서 생성과 파일 검수를 하나의 작업 흐름으로 통합한 Windows 업무 자동화 프로그램입니다.

실제 고객사의 업무 절차와 요구사항을 분석하고, 프로그램 설계부터 구현, 검증과 배포까지 전체 개발 과정을 담당했습니다.

**My Role & Responsibilities**

- 반복 업무와 수작업 검수 구간 식별
- C++20·MFC 기반 Windows 애플리케이션 설계 및 개발
- UI, 비즈니스 로직과 데이터 접근 계층 분리
- SQLite 기반 단가·사용자·정렬 기준 데이터 관리
- PowerShell과 Office 연동을 활용한 Excel·문서 자동화
- 미수금 내역서·납품서·견적서 생성 기능 개발
- 기존 업무 데이터와 프로그램 결과의 정합성 검증
- 사용자 피드백을 반영한 기능 개선과 배포

---

## Technologies

- **Agentic Development** — Claude Code
- **Languages** — C++ · C# · Python · Java · Kotlin · TypeScript
- **Frameworks & Platforms** — MFC · Win32 · .NET Desktop · Android · FastAPI · Spring Boot · React · Vue
- **Data & Infrastructure** — PostgreSQL · MySQL · SQLite · Docker · Jenkins · Linux
- **Computer Vision** — OpenCV

---

## How I Engineer with Agents

> 목표·계약 정의 → 역할별 서브에이전트 구현 → 자동 검증  
> → 읽기 전용 리뷰 → 배포·운영 결과 환류

에이전트에게 더 많은 자율성을 주기보다 역할·맥락·권한과 검증의 경계를 먼저 설계합니다.

- **맥락 유실 방지** — `CLAUDE.md`에 공통 규칙과 아키텍처를 고정하고, 스킬에 적용 조건·기준 문서·실행 절차와 검증 방법을 담아 각 서브에이전트에 작업에 필요한 맥락을 전달합니다.
- **품질의 비결정성 방지** —  에이전트의 결과가 매번 동일하지 않다는 점을 전제로, 빌드·테스트·계약 검증과 독립적인 코드 리뷰를 완료 기준에 포함합니다.
- **코드 파괴 방지** — 메인 에이전트가 작업을 Android·Backend·Web 단위로 나누어 전문 서브에이전트에 위임하고, 각 에이전트의 담당 경로와 도구 권한을 제한합니다. 사전 실행 훅과 Git 훅으로 작업 범위 밖의 수정과 위험한 변경을 검사합니다.
- **유지보수성 확보** — 작업 과정에서 확정된 아키텍처와 규칙을 재사용 스킬과 지속적으로 갱신되는 체크리스트로 관리하고, 문서 동기화·이슈·기술부채 기록에 검증 및 운영 결과를 반영합니다.

---

## Algorithm Practice

- [Algorithm_CPP](https://github.com/JakeKim4926/Algorithm_CPP) — C++ 기반 알고리즘과 자료구조 문제 풀이
- [Algorithm](https://github.com/JakeKim4926/Algorithm) — Java 기반 알고리즘 문제 풀이 기록

---

> 사람에게 실제로 도움이 되는 기술을 만드는 것,  
> 그것이 제가 추구하는 개발입니다.
