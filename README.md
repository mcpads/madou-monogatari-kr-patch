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
3. [Madou Monogatari I (Mega Drive) KR v1.1.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20I%20(Mega%20Drive)%20KR%20v1.1.0.bps)를 다운로드합니다
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

#### KR 패치 파일 — Madou Monogatari I (Mega Drive) KR v1.1.0.bps

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `2144DF1C`                                                         |
| MD5      | `6bd05b456034cd40bbafc4ae60df4988`                                 |
| SHA-1    | `8e2b543712c48f6ea3056c7c2072fb8b42376376`                         |
| SHA-256  | `b0dcc79b75109b9aaf468c00770979175a6b4421ad09ae9447b2256572af0163` |
| 크기     | 347,834 bytes (340 KB)                                             |

#### KR 패치 적용 후 — Madou Monogatari I (Mega Drive) KR v1.1.0.md

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `6DB99815`                                                         |
| MD5      | `d5426e9d33b45c3acec7d944b3dbd185`                                 |
| SHA-1    | `83119da230d1abdc7897e89d152c6c177e734154`                         |
| SHA-256  | `cbf77f12ab1784ca589230485eb259818708cacd502975de49232e6efa2c3810` |
| 크기     | 4,194,304 bytes (4 MB)                                             |

### 패치 정보

- 영어판 v1.1 번역 패치 롬([LIPEMCO! Translations](https://www.romhacking.net/translations/5388/)) 위에 적용
- 한글 폰트: [Neo둥근모](https://neodgm.dalgona.dev/) 16px 비트맵
- [패쳐 코드베이스](https://github.com/mcpads/md-madou-kr-patcher)

### 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **QA**: mcpads
- **한글 번역**: Claude Code (Opus 4.6 및 Haiku 4.5)
- **영어 번역 (베이스)**: [LIPEMCO! Translations](https://stargood.org/trans/lipemco.php)
- **원작**: Compile (1996)
- **폰트**: Neo둥근모

### 마도물어 하나마루 대유치원아 (SNES)

슈퍼 패미컴 **마도물어 하나마루 대유치원아** 한글 번역 패치입니다.

참고: [마도물어 하나마루 대유치원아](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4%20%ED%95%98%EB%82%98%EB%A7%88%EB%A3%A8%20%EB%8C%80%EC%9C%A0%EC%B9%98%EC%9B%90%EC%95%84)

![snes-madou-screenshot1](/img/snes-madou-screenshot-1.png)

![snes-madou-screenshot2](/img/snes-madou-screenshot-2.png)

![snes-madou-screenshot3](/img/snes-madou-screenshot-3.png)

### 적용 방법

1. **일본판 원본 ROM**을 준비합니다 (아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari - Hanamaru Daiyouchienji (KR v1.2.0).bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20-%20Hanamaru%20Daiyouchienji%20(KR%20v1.2.0).bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) 등 BPS 패처로 원본 ROM에 한글 패치를 적용합니다

### 체크섬

#### 원본 ROM — Madou Monogatari - Hanamaru Daiyouchienji (Japan).sfc

| 알고리즘 | 해시                                                             |
| -------- | ---------------------------------------------------------------- |
| CRC32    | 1354E81E                                                         |
| MD5      | 11b40949b167ee0ed6d7abb9ea32a81f                                 |
| SHA-1    | 164d51ce6cf2228a399ba11fc1f5803cace53cb7                         |
| SHA-256  | 72e7ff7857f577809b585f67f9c6b2211e6648c4f86519fc6c66e3f4bfd49f59 |
| 크기     | 2,097,152 bytes (2 MB)                                           |

#### KR 패치 파일 — Madou Monogatari - Hanamaru Daiyouchienji (KR v1.2.0).bps

| 알고리즘 | 해시                                                             |
| -------- | ---------------------------------------------------------------- |
| CRC32    | 2144DF1C                                                         |
| MD5      | 13aad306931a87455cc6e4926b923e57                                 |
| SHA-1    | 4e4fbb776fb2d156eaaf3342eecb057e014c55be                         |
| SHA-256  | 938418adf05bb4756185358ac28ce7c58ad7155d12f6d19f6ba30b3f0e785d9e |
| 크기     | 191,682 bytes (187 KB)                                           |

#### KR 패치 적용 후 — Madou Monogatari - Hanamaru Daiyouchienji (KR v1.2.0).sfc

| 알고리즘 | 해시                                                             |
| -------- | ---------------------------------------------------------------- |
| CRC32    | AC5B2918                                                         |
| MD5      | f546a6a65b8a43a0fcfda00cb361b28a                                 |
| SHA-1    | c7460447bcd64c2273c6a35055177c3b4e653813                         |
| SHA-256  | f762dc057d64093aec2f6906d657911ff2638d5734a8b51d7b9ca54575a30c5f |
| 크기     | 2,097,152 bytes (2 MB)                                           |

### 패치 정보

- 한글 폰트: [Galmuri](https://github.com/quiple/galmuri) 12px 및 [Dalmoori](https://github.com/RanolP/dalmoori-font) 8px 비트맵
- [패쳐 코드베이스](https://github.com/mcpads/sfc-madou-kr-patcher)

### 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **한글 번역**: Claude Code (Opus 4.6 및 Haiku 4.5), Codex (GPT 5.3 codex)
- **QA**: mcpads
- **원작**: Compile (1996)

## 마도물어 (세가 새턴) — 베타

> 이 패치는 선공개용 베타 버전입니다. 미번역 요소, 몇몇 버그가 존재할 수 있으며, 번역 역시 변경될 수 있습니다.

세가 새턴 **마도물어 (Madou Monogatari)** 한글 번역 패치입니다.

참고: [마도물어(세가 새턴) - 나무위키](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4(%EC%84%B8%EA%B0%80%20%EC%83%88%ED%84%B4))

![ss-madou-screenshot1](/img/ss-madou-screenshot-1.png)

![ss-madou-screenshot2](/img/ss-madou-screenshot-2.png)

### 적용 방법

1. **일본판 원본 ROM**을 준비합니다 (BIN/CUE 형식, 아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari (Sega Saturn) KR v0.1.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20(Sega%20Saturn)%20KR%20v0.1.0.bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) 등 BPS 패처로 원본 BIN 파일에 한글 패치를 적용합니다

### 체크섬

#### 원본 ROM — Madou_Monogatari_JAP.bin (T-6607G V1.003)

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `BBC3E5FA`                                                         |
| MD5      | `fbc3ec7db5ca799ad30c5c772ff2b682`                                 |
| SHA-1    | `a3a4a727c91aa7c2eec8795457459bf6f1297721`                         |
| SHA-256  | `c2f174280295ea3e992cfd8bfc04b474caf4ee017c3c4aa8896b85e3ff96e904` |
| 크기     | 146,661,312 bytes (140 MB, BIN/CUE Track 01)                       |

#### KR 패치 파일 — Madou Monogatari (Sega Saturn) KR v0.1.0.bps

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `2144DF1C`                                                         |
| MD5      | `09a179a8091f70a213212e8364002377`                                 |
| SHA-1    | `82a9ab5288ec7c5b2fdbb2b0224b6aed77fb1fce`                         |
| SHA-256  | `accce6ee1c8a4d9c58e592b72038d709a8cb88ca6cc5aa013d4c2bf188650701` |
| 크기     | 4,450,090 bytes (4.2 MB)                                           |

#### KR 패치 적용 후 — Madou Monogatari (Sega Saturn) KR v0.1.0.bin

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `68327959`                                                         |
| MD5      | `8ab6772e208c95a96a175c8306ec5bc9`                                 |
| SHA-1    | `9631c16827038396faf8b3c49b883569e96e3380`                         |
| SHA-256  | `2551afccf0fc993ee7e3e49e51095f4334927a53207cf3f6506103c1efce18aa` |
| 크기     | 146,661,312 bytes (140 MB)                                         |

### 패치 정보

- 베타 버전: 시나리오/이벤트 대사 초벌 번역 상태, **시스템 UI는 미번역**, 버그 존재 가능성
- 한글 폰트: [Galmuri](https://github.com/quiple/galmuri) 12px 비트맵 (대화), [MaplestoryBold](https://maplestory.nexon.com/Media/Font) 14px (프롤로그)

### 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **한글 번역**: Claude Code (Opus 4.6 및 Haiku 4.5)
- **QA**: mcpads
- **원작**: Compile (1998)
- **폰트**: Galmuri, MaplestoryBold

## 번역 예정 작품

### 마도물어 (게임기어판)

시리즈 4개 (1, 2, 3, A) 동시 진행 중입니다.

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [ ] 한글 폰트 통합 및 적용: 진행중
- [ ] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 슈퍼 나조 뿌요 1 (SNES)

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [ ] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 슈퍼 나조 뿌요 2 (SNES)

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [ ] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

## 이슈 제보 및 피드백

어색한 번역, 번역 오타, 심각한 그래픽 깨짐, 게임 멈춤 등의 문제는 아래 방법으로 제보해 주세요.

- **GitHub Issue**: [이슈 트래커 링크]에 새 이슈를 등록해 주세요.
- **제보 시 포함할 내용**:
  - 문제가 발생한 위치 (예: 층 3층 상점 안)
  - 문제 현상 (예: 특정 아이템 사용 시 멈춤)
  - 사용 중인 에뮬레이터 및 버전
  - (가능하다면) 스크린샷이나 세이브 파일

## 업데이트 기록

| 버전   | 날짜       | 대상                         | 내용                                                                |
| ------ | ---------- | ---------------------------- | ------------------------------------------------------------------- |
| v1.0.0 | 2026-02-16 | 마도물어 I (MD)              | 최초 배포                                                           |
| v0.1.0 | 2026-02-24 | 마도물어 하나마루 대유치원아 | 베타 버전 배포                                                      |
| v1.0.0 | 2026-02-26 | 마도물어 하나마루 대유치원아 | 최초 배포                                                           |
| v1.1.0 | 2026-03-01 | 마도물어 하나마루 대유치원아 | 버그 수정 (대사 잘림, 대사 오표시, 상점 매진, 선택지 하이라이트 등) |
| v1.1.0 | 2026-03-06 | 마도물어 I (MD)              | 번역 다수 수정, 층 표시 수정, 텍스트 잘림 수정                      |
| v1.2.0 | 2026-03-07 | 마도물어 하나마루 대유치원아 | 몇몇 번역 관련 버그 패치                                            |
| v0.1.0 | 2026-03-07 | 마도물어 (세가 새턴)         | 베타 배포 (시스템 UI 미번역)                                        |

## 라이선스

- 본 패치 파일은 개인적, 비상업적 용도로 제공됩니다. 원작 게임의 저작권은 해당 권리자에게 있습니다.
- 본 한글패치 파일 자체를 제작자에 허가없이 타 사이트에 재배포하지 말아 주시고, 재배포를 원하실 경우 패치원본 게시물의 링크를 공유해 주시기 바랍니다.
- 본 한글패치 파일을 이용하여 금전적 이득을 취하는 모든 행위를 일절 금합니다. 해당 행위로 발생하는 모든 책임은 이용 당사자에게 있으며, 패치 제작자는 어떠한 책임도 지지 않습니다.
