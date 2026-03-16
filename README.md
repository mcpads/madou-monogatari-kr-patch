# 마도물어 시리즈 한글 번역 프로젝트

컴파일사의 RPG 마도물어(Madou Monogatari) 시리즈의 한글 번역 패치를 배포하는 프로젝트입니다.

Claude Code를 활용하여 리버싱/번역하고, 사람이 기초 검수를 진행한 프로젝트입니다.

더 많은 게임의 번역에 대한 기여를 위해, 모든 패치에 사용된 코드는 기기별로 공개됩니다.

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

### 마도물어 하나마루 대유치원아 (SNES)

슈퍼 패미컴 **마도물어 하나마루 대유치원아** 한글 번역 패치입니다.

참고: [마도물어 하나마루 대유치원아](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4%20%ED%95%98%EB%82%98%EB%A7%88%EB%A3%A8%20%EB%8C%80%EC%9C%A0%EC%B9%98%EC%9B%90%EC%95%84)

![snes-madou-screenshot1](/img/snes-madou-screenshot-1.png)

![snes-madou-screenshot2](/img/snes-madou-screenshot-2.png)

![snes-madou-screenshot3](/img/snes-madou-screenshot-3.png)

### 적용 방법

1. **일본판 원본 ROM**을 준비합니다 (아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari - Hanamaru Daiyouchienji (KR v1.3.0).bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20-%20Hanamaru%20Daiyouchienji%20(KR%20v1.3.0).bps)를 다운로드합니다
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

#### KR 패치 파일 — Madou Monogatari - Hanamaru Daiyouchienji (KR v1.3.0).bps

| 알고리즘 | 해시                                                             |
| -------- | ---------------------------------------------------------------- |
| CRC32    | A200F55D                                                         |
| MD5      | ada0574945225eeac1dee1d71a326cee                                 |
| SHA-1    | 161bcb4f3850c5463b86419bb71777e602e60b33                         |
| SHA-256  | 0f9d50f805bc62cf5fdbd488f0f29fdef2dbf81aab22de5dade0fd56f4334ccb |
| 크기     | 186,198 bytes (181 KB)                                           |

#### KR 패치 적용 후 — Madou Monogatari - Hanamaru Daiyouchienji (KR v1.3.0).sfc

| 알고리즘 | 해시                                                             |
| -------- | ---------------------------------------------------------------- |
| CRC32    | 59799A04                                                         |
| MD5      | 6efe9262ee276a39871da42d0fa870fa                                 |
| SHA-1    | 5ffd25ea4bcfa71f9f443f60577f2eeffcaa293f                         |
| SHA-256  | adfc90212440ac642f774a4051ba3fb5d2312c6446387109d0c1f877715fc6c0 |
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

## 마도물어 (세가 새턴)

세가 새턴 **마도물어 (Madou Monogatari)** 한글 번역 패치입니다.

참고: [마도물어(세가 새턴) - 나무위키](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4(%EC%84%B8%EA%B0%80%20%EC%83%88%ED%84%B4))

![ss-madou-screenshot1](/img/ss-madou-screenshot-1.png)

![ss-madou-screenshot2](/img/ss-madou-screenshot-2.png)

### 적용 방법 (J)

1. **원본 ROM**을 준비합니다 (BIN/CUE 형식, 아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari (Sega Saturn) KR v1.0.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20(Sega%20Saturn)%20KR%20v1.0.0.bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) 등 BPS 패처로 원본 BIN 파일에 한글 패치를 적용합니다

### 적용 방법 (U)

1. **원본 ROM**을 준비합니다 (BIN/CUE 형식, 아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari (U) (Sega Saturn) KR v1.0.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20(U)%20(Sega%20Saturn)%20KR%20v1.0.0.bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) 등 BPS 패처로 원본 BIN 파일에 한글 패치를 적용합니다

### 체크섬 (J)

#### 원본 ROM — Madou Monogatari (J).bin (T-6607G V1.003)

| 알고리즘 | 해시                                         |
| -------- | -------------------------------------------- |
| CRC32    | `BBC3E5FA`                                   |
| MD5      | `fbc3ec7db5ca799ad30c5c772ff2b682`           |
| SHA-1    | `a3a4a727c91aa7c2eec8795457459bf6f1297721`   |
| 크기     | 146,661,312 bytes (140 MB, BIN/CUE Track 01) |

#### KR 패치 파일 — Madou Monogatari (Sega Saturn) KR v1.0.0.bps

| 알고리즘 | 해시                                       |
| -------- | ------------------------------------------ |
| CRC32    | `2144DF1C`                                 |
| MD5      | `67bdbba116b23d70595a7084a449f977`         |
| SHA-1    | `1d2ca16358b37d4e41648d1528208e8e90f2a5c6` |
| 크기     | 4,467,344 bytes (4.3 MB)                   |

#### KR 패치 적용 후 — Madou Monogatari (Sega Saturn) KR v1.0.0.bin

| 알고리즘 | 해시                               |
| -------- | ---------------------------------- |
| CRC32    | `85850FF0`                         |
| MD5      | `b6d81ebcb668b98eb4de5d8d942ffc98` |
| 크기     | 146,661,312 bytes (140 MB)         |

### 체크섬 (U)

#### 원본 ROM — Madou Monogatari (U).bin (T-6607G V1.003)

| 알고리즘 | 해시                                         |
| -------- | -------------------------------------------- |
| CRC32    | `C616ED2D`                                   |
| MD5      | `de1e8fb1b4d0901efd2aee5b09d0fcf9`           |
| SHA-1    | `e60b8ff5d9acc3366a36b1101013f529f722942d`   |
| 크기     | 146,308,512 bytes (139 MB, BIN/CUE Track 01) |

#### KR 패치 파일 — Madou Monogatari (U) (Sega Saturn) KR v1.0.0.bps

| 알고리즘 | 해시                                       |
| -------- | ------------------------------------------ |
| CRC32    | `2144DF1C`                                 |
| MD5      | `c7f4af8c858584ef67fb8d7ee11134c8`         |
| SHA-1    | `5f966d6f4289f1c1640cc7fa55b17f06bb65886e` |
| 크기     | 4,467,496 bytes (4.3 MB)                   |

#### KR 패치 적용 후 — Madou Monogatari (U) (Sega Saturn) KR v1.0.0.bin

| 알고리즘 | 해시                               |
| -------- | ---------------------------------- |
| CRC32    | `8F12747B`                         |
| MD5      | `644f970617b7260a68e79f7242a86832` |
| 크기     | 146,308,512 bytes (139 MB)         |

### 패치 정보

- 시나리오/이벤트 대사 번역, 시스템 UI 한글화
- 한글 폰트: [Galmuri](https://github.com/quiple/galmuri) (대화, 메뉴 탭), [MaplestoryBold](https://maplestory.nexon.com/Media/Font) (프롤로그, 레벨업), [Dalmoori](https://github.com/RanolP/dalmoori-font) (전투 UI)
- [패쳐 코드베이스](https://github.com/mcpads/ss-madou-kr-patcher)

### 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **한글 번역**: Claude Code (Opus 4.6 및 Haiku 4.5), Codex (GPT 5.3 codex)
- **QA**: mcpads
- **원작**: Compile (1998)

## 번역 예정 작품

### 뿌요뿌욘 (드림캐스트)

진행 중입니다.

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [ ] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 와쿠와쿠 뿌요뿌요 던전 (세가 새턴)

진행 중입니다.

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [ ] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 마도물어 (게임기어판)

시리즈 4개 (1, 2, 3, A) 동시 진행 중입니다.

> 한국어 통합시 폰트 가독성 문제로 지연 중입니다.

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [ ] 한글 폰트 통합 및 적용: 진행중
- [ ] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 슈퍼 나조 뿌요 1 (SNES)

진행 중입니다.

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [ ] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 슈퍼 나조 뿌요 2 (SNES)

진행 중입니다.

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
| v0.2.0 | 2026-03-08 | 마도물어 (세가 새턴)         | 베타 배포 (번역 교정, 추가 UI 한글화)                               |
| v0.3.0 | 2026-03-08 | 마도물어 (세가 새턴)         | 뿌요카드 버그 수정                                                  |
| v1.3.0 | 2026-03-09 | 마도물어 하나마루 대유치원아 | 몇몇 미번역 오류 수정                                               |
| v0.4.0 | 2026-03-11 | 마도물어 (세가 새턴)         | 시스템 UI 추가 번역                                                 |
| v1.0.0 | 2026-03-17 | 마도물어 (세가 새턴)         | 정식 배포                                                           |

## 라이선스

- 본 패치 파일은 개인적, 비상업적 용도로 제공됩니다. 원작 게임의 저작권은 해당 권리자에게 있습니다.
- 본 한글패치 파일 자체를 제작자에 허가없이 타 사이트에 재배포하지 말아 주시고, 재배포를 원하실 경우 패치원본 게시물의 링크를 공유해 주시기 바랍니다.
- 본 한글패치 파일을 이용하여 금전적 이득을 취하는 모든 행위를 일절 금합니다. 해당 행위로 발생하는 모든 책임은 이용 당사자에게 있으며, 패치 제작자는 어떠한 책임도 지지 않습니다.
