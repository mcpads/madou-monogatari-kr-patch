# 마도물어 시리즈 한글 번역 프로젝트

컴파일사의 RPG 마도물어(Madou Monogatari) 시리즈의 한글 번역 패치를 배포하는 프로젝트입니다.

Claude Code를 활용하여 리버싱/번역하고, 사람이 기초 검수를 진행한 프로젝트입니다.

## 마도물어 I — 메가드라이브

세가 메가드라이브(Genesis) **마도물어 I (Madou Monogatari I)** 한글 번역 패치입니다. (타이틀 화면 제외)

참고: [마도물어 I - 나무위키](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4#s-3)

![md-madou-screenshot1](/img/md-madou-screenshot-1.png)

![md-madou-screenshot2](/img/md-madou-screenshot-2.png)

### 적용 방법

1. **일본판 원본 ROM**을 준비합니다 (아래 체크섬으로 올바른 파일인지 확인)
2. [LIPEMCO! 영어 번역 패치 (IPS)](https://www.romhacking.net/translations/5388/)를 다운로드하여 원본 ROM에 적용합니다
3. [Madou Monogatari I (Mega Drive) KR v1.0.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20I%20(Mega%20Drive)%20KR%20v1.0.0.bps)를 다운로드합니다
4. [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) 등 BPS 패처로 영어판 ROM에 한글 패치를 적용합니다

### 체크섬

#### 원본 ROM - Madou Monogatari I (Japan).md

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `DD82C401`                                                         |
| MD5      | `41B8BA3569E3F4F98155DEA64318D223`                                 |
| SHA-1    | `143456600E44F543796CF6ADE77830115A8F2F99`                         |
| SHA-256  | `61d1dec319afb1380dfbee0cdb42e6e64ab180941b0d533d8deed9efa502f83c` |
| 크기     | 2,097,152 bytes (2 MB)                                             |

#### ENG 패치 ROM — Madou Monogatari I (English v1.1).md

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `FAC8D75D`                                                         |
| MD5      | `c2b120a54f1309cd64090da815b13b0c`                                 |
| SHA-1    | `2cb8d4c82025dc9d1ea548a2ea4da994061b4f50`                         |
| SHA-256  | `13375d3fd1587525086fc8c0ca8408185733f258ca30f22abcbeab9f44fae05b` |
| 크기     | 4,194,304 bytes (4 MB)                                             |

#### KR 패치 파일 — Madou Monogatari I (Mega Drive) KR v1.0.0.bps

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `2144DF1C`                                                         |
| MD5      | `83eeabd5a483b7e2876db43a6e5a40e5`                                 |
| SHA-1    | `6e7e25279580c0e2d37e7ea1935c1afb5d92a1fa`                         |
| SHA-256  | `f098b7d1b654fa8cc68d453af1a391e1520d9a1d1c9b4818d5a6fc634317c7ab` |
| 크기     | 350,754 bytes (342 KB)                                             |

#### KR 패치 적용 후 — Madou Monogatari I (Mega Drive) KR v1.0.0.md

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `0A4C79EB`                                                         |
| MD5      | `b6c8301b629fa9933aa6453d658a1943`                                 |
| SHA-1    | `ce75a14af0d636151bbeca74db5626c5bc87dc47`                         |
| SHA-256  | `f28d8fd71d6f3eef296b2c2cf6d4ae1ae9c42966d86c62f67c781efecf73e9e0` |
| 크기     | 4,194,304 bytes (4 MB)                                             |

### 패치 정보

- 영어판 v1.1 번역 패치 롬([LIPEMCO! Translations](https://www.romhacking.net/translations/5388/)) 위에 적용
- 한글 폰트: [Neo둥근모](https://neodgm.dalgona.dev/) 16px 비트맵

### 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **QA**: mcpads
- **한글 번역**: Claude Code
- **영어 번역 (베이스)**: [LIPEMCO! Translations](https://stargood.org/trans/lipemco.php)
- **원작**: Compile (1996)
- **폰트**: Neo둥근모

## 번역 예정 작품

### 마도물어 하나마루 대유치원아 (SNES)

참고: [마도물어 하나마루 대유치원아](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4%20%ED%95%98%EB%82%98%EB%A7%88%EB%A3%A8%20%EB%8C%80%EC%9C%A0%EC%B9%98%EC%9B%90%EC%95%84)

![snes-madou-screenshot1](/img/snes-madou-screenshot-1.png)

![snes-madou-screenshot2](/img/snes-madou-screenshot-2.png)

![snes-madou-screenshot3](/img/snes-madou-screenshot-3.png)

현재 시나리오 및 대사, 대부분의 시스템 UI가 번역 완료되었었고, 세세한 부분들에 대한 수정 및 최종 번역 검수 작업 진행 중입니다.

- [x] 시나리오 및 이벤트 대사: 100%
- [x] 아이템 및 마법 명칭: 100%
- [ ] 시스템 안정성: 검수 중 (약 90%)
- [x] 시스템 UI (옵션, 스탯창, 월드맵 등): 100%
- [ ] 최종 번역 검수 및 마이너 이슈 수정: 진행 중

### 마도물어 (게임기어판)

- 시리즈 4개 (1, 2, 3, A) 동시 진행 중입니다.
- 2, 3, A는 번역 작업은 끝났으며, 한글 폰트 및 크기 최적화 작업중입니다.

### 슈퍼 나조 뿌요 1, 2 (SNES)

- 작업 예정입니다.

## 이슈 제보 및 피드백

어색한 번역, 번역 오타, 심각한 그래픽 깨짐, 게임 멈춤 등의 문제는 아래 방법으로 제보해 주세요.

- **GitHub Issue**: [이슈 트래커 링크]에 새 이슈를 등록해 주세요.
- **제보 시 포함할 내용**:
  - 문제가 발생한 위치 (예: 층 3층 상점 안)
  - 문제 현상 (예: 특정 아이템 사용 시 멈춤)
  - 사용 중인 에뮬레이터 및 버전
  - (가능하다면) 스크린샷이나 세이브 파일

## 업데이트 기록

| 버전   | 날짜       | 대상            | 내용      |
| ------ | ---------- | --------------- | --------- |
| v1.0.0 | 2026-02-16 | 마도물어 I (MD) | 최초 배포 |

## 라이선스

본 패치 파일은 개인적, 비상업적 용도로 제공됩니다. 원작 게임의 저작권은 해당 권리자에게 있습니다.
