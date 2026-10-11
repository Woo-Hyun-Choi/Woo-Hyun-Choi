<div align="center">

# 최우현 · Woo Hyun Choi

**Frontend Developer · Infrastructure & Operations**

React로 화면을 만들고, 배포와 운영까지 이어갑니다.

[Personal GitHub](https://github.com/Woo-Hyun-Choi) · [Work GitHub](https://github.com/woohyun-choi) · [Blog](https://porbrothers.tistory.com/)

</div>

## About

에너지 서비스의 프론트엔드 개발과 고객사별 배포를 맡아왔으며, 현재는 온프레미스·클라우드 환경의 서버 구축과 운영을 담당하고 있습니다. 제조·재고 관리 서비스의 프론트엔드 유지보수도 병행하고 있습니다.

고객의 업무 절차를 이해하고 화면과 기능에 반영하는 일을 해왔습니다. 직접 개발한 기능뿐 아니라 다른 팀의 작업도 함께 조율하며, 현장에서 동작을 확인하고 운영에 반영하는 과정까지 경험했습니다.

- **Frontend** — React·TypeScript 기반 업무 화면, API 연동, 대시보드 성능 개선
- **Delivery & Operations** — 고객사별 웹 배포, Linux 서비스 구성, 운영 점검과 로그 관리
- **Collaboration** — Figma·Zeplin 디자인 협업, 요구사항 구체화, 개발 일정 조율과 결과 검증

## Toolbox

<p>
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=222222" />
  <img alt="Less" src="https://img.shields.io/badge/Less-1D365D?style=flat-square&logo=less&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=222222" />
  <img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
</p>

| 영역 | 실무에서 다룬 기술과 도구 |
| --- | --- |
| 웹 개발 | React, JavaScript, TypeScript, HTML, CSS, Less |
| 서버·클라우드 | Linux (Ubuntu·RHEL), AWS, NCP, systemd |
| 서비스·배포 | Nginx, HAProxy, Tomcat, SSH·SCP |
| 데이터 조회 | MySQL, MongoDB |
| 협업 | GitHub, Jira, Slack, Figma, Zeplin |

## Selected Experience

### 에너지 플랫폼 · 대시보드 개발과 성능 개선

React 기반 통합관리·VPP·ESS 정보연계 대시보드와 RTU 관리 등 업무 화면을 개발하고 유지보수했습니다. 실시간 현황표와 단말이력 등 운영 화면도 개선했습니다.

4인 공동 개발로 기존 대시보드를 React로 전환했습니다. 이후 초기 조회 범위, 비필수 데이터의 조회 순서, 병렬 요청과 렌더링 흐름을 개선했습니다.

| 단계 | 초기 로딩 시간 |
| --- | --- |
| 기존 V1 | 60초 이상 |
| React로 동일 구조 전환 | 33–36초 |
| 추가 최적화 | 약 12초 |

당시 실서비스 로딩 경험에 근거한 비교이며, 동일 조건으로 통제한 벤치마크는 아닙니다.

### 웹사이트 · 디자인 시안에서 실제 서비스까지

중부발전 홍보용 서비스에서 프로젝트 투입 인력 3인 중 랜딩·모니터링·고객지원 화면 구현을 담당했습니다. 수익배분 게이지, 사업 소개, FAQ 등 서비스 안내 화면을 구성하고 API·차트를 연동했습니다.

사내 디자이너와 Figma·Zeplin으로 시안을 확인하며 React·Less로 화면과 스타일을 구현했습니다. 자사 홈페이지 리뉴얼에서는 프론트엔드 전체를 담당했습니다.

### 제조·재고 관리 · 기존 서비스의 입력 흐름 개선

개인 외주로 운영 중인 제조·재고 관리 서비스의 프론트엔드 유지보수를 맡고 있습니다.

- **복합 입력 UI** — 초·중·종 검사 양식과 결과지의 구성을 개선하고, 같은 검사 데이터를 행·열 방향으로 전환해 입력하도록 수정했습니다.
- **데이터 연결과 호환** — 입출고 화면 간 데이터 전달·저장 오류를 수정하고, 기존 데이터도 수정할 수 있도록 입력 처리와 검증을 보완했습니다.
- **조회 흐름** — 검색어·날짜·페이지를 URL과 동기화해 화면 이동 후에도 조회 조건을 유지하고, 다운로드 범위를 조회 의도에 맞게 정리했습니다.

### 폐쇄망 구축 · 서비스 배포와 운영

본사 RHEL 7 환경의 프로세스·서비스 설정을 분석해 RHEL 8 기반 폐쇄망 DR 환경을 구축했습니다. 설치 패키지의 의존성 오류를 해결하고, 서비스 기동부터 수집 데이터의 화면 반영까지 확인했습니다.

고객사별 웹 배포와 온프레미스·클라우드 운영을 이어가며, OS 이전, NAS 기반 로그 관리와 로테이션 정비, 정기 점검 및 구축·운영 문서 작성도 담당했습니다.

### 고객 요구사항 조율과 기존 기능 개선

고객 요구를 현재 구현과 비교해 수정 항목과 완료 기준으로 정리하고, 담당 개발자와 범위·일정을 조율했습니다. 제어시험에서는 기존에 구현된 기능의 시간 계산과 타임라인 표시를 수정하고 고객 시험으로 동작을 검증했습니다.

## Career

| 기간 | 역할 |
| --- | --- |
| 2025.06 – 현재 | 인코어드 테크놀로지스 · 인프라 구축 및 운영 |
| 2021.12 – 2025.06 | 인코어드 테크놀로지스 · React 프론트엔드 개발 및 고객사별 배포 |
| 2026 – 현재 | 개인 외주 · 제조·재고 관리 서비스 프론트엔드 유지보수 |

## Accounts & Projects

업무용 개발 활동은 **[@woohyun-choi](https://github.com/woohyun-choi)** 계정에서 진행해왔습니다. 회사 프로젝트의 소스 코드는 비공개 저장소에서 관리하며, 이 프로필에는 담당 역할과 경험을 요약했습니다.

개인 계정의 기존 공개 저장소에는 React Native와 Android를 학습하며 작성한 예제·실습 프로젝트가 포함되어 있습니다.
