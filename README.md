# 마도물어 시리즈 한글 번역 프로젝트

컴파일사의 RPG 마도물어(魔導物語) 시리즈의 한글 번역 패치를 배포하는 프로젝트입니다.

Claude Code를 활용하여 리버싱/번역하고, 사람이 기초 검수를 진행한 프로젝트입니다.

더 많은 게임의 번역에 대한 기여를 위해, 모든 패치에 사용된 코드는 기기별로 공개됩니다.

> 자매 프로젝트 - [뿌요뿌요 시리즈 한글 번역 프로젝트](https://github.com/mcpads/puyo-puyo-kr-patch)

## 마도물어 I — 메가드라이브

세가 메가드라이브(Genesis) **마도물어 I (魔導物語 I)** 한글 번역 패치입니다. (타이틀 화면 제외)

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

마도물어 **세가 새턴판** 한글 번역 패치입니다.

참고: [마도물어(세가 새턴) - 나무위키](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4(%EC%84%B8%EA%B0%80%20%EC%83%88%ED%84%B4))

![ss-madou-screenshot1](/img/ss-madou-screenshot-1.png)

![ss-madou-screenshot2](/img/ss-madou-screenshot-2.png)

### 적용 방법 (J)

1. **원본 ROM**을 준비합니다 (BIN/CUE 형식, 아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari (Sega Saturn) KR v1.1.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20(Sega%20Saturn)%20KR%20v1.1.0.bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) 등 BPS 패처로 원본 BIN 파일에 한글 패치를 적용합니다

### 적용 방법 (U)

1. **원본 ROM**을 준비합니다 (BIN/CUE 형식, 아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari (U) (Sega Saturn) KR v1.1.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20(U)%20(Sega%20Saturn)%20KR%20v1.1.0.bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) 등 BPS 패처로 원본 BIN 파일에 한글 패치를 적용합니다

### 체크섬 (J)

#### 원본 ROM — Madou Monogatari (J).bin (T-6607G V1.003)

| 알고리즘 | 해시                                         |
| -------- | -------------------------------------------- |
| CRC32    | `BBC3E5FA`                                   |
| MD5      | `fbc3ec7db5ca799ad30c5c772ff2b682`           |
| SHA-1    | `a3a4a727c91aa7c2eec8795457459bf6f1297721`   |
| 크기     | 146,661,312 bytes (140 MB, BIN/CUE Track 01) |

#### KR 패치 파일 — Madou Monogatari (Sega Saturn) KR v1.1.0.bps

| 알고리즘 | 해시                                       |
| -------- | ------------------------------------------ |
| CRC32    | `2144DF1C`                                 |
| MD5      | `fa90c33ffe9926f3f86deb72886fe264`         |
| SHA-1    | `22228645347b98245a984c03b931351680c21f1b` |
| 크기     | 4,467,371 bytes (4.3 MB)                   |

#### KR 패치 적용 후 — Madou Monogatari (Sega Saturn) KR v1.1.0.bin

| 알고리즘 | 해시                               |
| -------- | ---------------------------------- |
| CRC32    | `7CC56BE7`                         |
| MD5      | `ac09a9d667e529423722fa3dc1534136` |
| 크기     | 146,661,312 bytes (140 MB)         |

### 체크섬 (U)

#### 원본 ROM — Madou Monogatari (U).bin (T-6607G V1.003)

| 알고리즘 | 해시                                         |
| -------- | -------------------------------------------- |
| CRC32    | `C616ED2D`                                   |
| MD5      | `de1e8fb1b4d0901efd2aee5b09d0fcf9`           |
| SHA-1    | `e60b8ff5d9acc3366a36b1101013f529f722942d`   |
| 크기     | 146,308,512 bytes (139 MB, BIN/CUE Track 01) |

#### KR 패치 파일 — Madou Monogatari (U) (Sega Saturn) KR v1.1.0.bps

| 알고리즘 | 해시                                       |
| -------- | ------------------------------------------ |
| CRC32    | `2144DF1C`                                 |
| MD5      | `51f004ebe89918dad1f2bd6b3627d1c4`         |
| SHA-1    | `d896b48211b4a0c5720c898e1787271961d6c2c7` |
| 크기     | 4,467,523 bytes (4.3 MB)                   |

#### KR 패치 적용 후 — Madou Monogatari (U) (Sega Saturn) KR v1.1.0.bin

| 알고리즘 | 해시                               |
| -------- | ---------------------------------- |
| CRC32    | `36BFE518`                         |
| MD5      | `504782a25083d31a3c4de34fdf2b7391` |
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

## 와쿠와쿠 뿌요뿌요 던전 (세가 새턴)

**와쿠와쿠 뿌요뿌요 던전 (わくわくぷよぷよダンジョン) 세가 새턴 판** 한글 번역 PoC 패치입니다.

> **이 패치는 선공개용 베타 버전으로 아직 번역 등의 검수가 끝나지 않은 상태입니다. 미번역 요소, 게임 진행에 차질이 생기는 버그가 존재할 수 있으며, 번역 및 그래픽 요소가 대량으로 변경될 수 있습니다.**

참고: [와쿠와쿠 뿌요뿌요 던전 - 나무위키](https://namu.wiki/w/%EC%99%80%EC%BF%A0%EC%99%80%EC%BF%A0%20%EB%BF%8C%EC%9A%94%EB%BF%8C%EC%9A%94%20%EB%8D%98%EC%A0%84)

![ss-waku-puyo-screenshot-1](/img/ss-waku-puyo-screenshot-1.png)

![ss-waku-puyo-screenshot-2](/img/ss-waku-puyo-screenshot-2.png)

![ss-waku-puyo-screenshot-3](/img/ss-waku-puyo-screenshot-3.png)

### 적용 방법

1. **원본 ROM**을 준비합니다 (BIN/CUE 형식, 아래 체크섬으로 올바른 파일인지 확인)
2. [Waku Waku Puyo Puyo Dungeon (Sega Saturn) KR v0.1.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Waku%20Waku%20Puyo%20Puyo%20Dungeon%20(Sega%20Saturn)%20KR%20v0.1.0.bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://www.smwcentral.net/?p=section&a=details&id=11474) 등 BPS 패처로 원본 BIN 파일(Track 1)에 한글 패치를 적용합니다

### 체크섬

#### 원본 ROM — Waku Waku Puyo Puyo Dungeon (Japan) (4M) (Track 1).bin (T-6608G V1.001)

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `B8D1E870`                                                         |
| MD5      | `567e6dfc4776c7cf3e417d5c98f34dbf`                                 |
| SHA-1    | `e0af339ab1985b33560937fa69f01a1d19c61242`                         |
| SHA-256  | `3edd5058cce6c6d36b69813a8d207d15fece8b79f3b5638522325fe3fa839f69` |
| 크기     | 89,848,752 bytes (85 MB, BIN/CUE Track 01)                         |

#### KR 패치 파일 — Waku Waku Puyo Puyo Dungeon (Sega Saturn) KR v0.1.0.bps

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `2144DF1C`                                                         |
| MD5      | `04d234fc35521d298b3651ae99d26769`                                 |
| SHA-1    | `bee25c10f178e96dd54da0acf16f16e0e7216af9`                         |
| SHA-256  | `d52356493df0b5157bfa42ee1406132029913f37225169ce1394b61eef2f9ee4` |
| 크기     | 904,207 bytes (883 KB)                                             |

#### KR 패치 적용 후 — Waku Waku Puyo Puyo Dungeon (Sega Saturn) KR v0.1.0.bin

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `C2746A48`                                                         |
| MD5      | `13b66f0fe4db438261bb56cda82d7e83`                                 |
| SHA-1    | `a2c221b2606deebaee0a9db327cfa57622fd7b1b`                         |
| SHA-256  | `5d818052aec3c2535f2c2fbf695c6f397f08ae18386544e78aca072058595213` |
| 크기     | 89,848,752 bytes (85 MB)                                           |

### 패치 정보

- 시나리오/이벤트 대사 초벌 번역, 시스템 UI 한글화
- 한글 폰트: [MaplestoryLight](https://maplestory.nexon.com/Media/Font), [MaplestoryBold](https://maplestory.nexon.com/Media/Font), [Galmuri](https://github.com/quiple/galmuri), [Dalmoori](https://github.com/RanolP/dalmoori-font)
- [패쳐 코드베이스](https://github.com/mcpads/ss-waku-puyo-kr-patcher)

### 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **한글 번역**: Claude Code (Opus 4.6 및 Sonnet 4.6), Codex (GPT 5.4)
- **QA**: mcpads
- **원작**: Compile (1998)

## 마도물어 I — 게임기어 (베타)

세가 게임기어 **마도물어 I (魔導物語 I - 3つの魔導球)** 한글 번역 패치입니다.

> ⚠️ **베타 배포 (v0.1.0)**: 게임 전반은 정상 플레이 가능하나 최종 인게임 검수가 진행 중입니다. 어색한 번역·표기·그래픽 문제는 제보해 주세요.

참고: [마도물어 I - 나무위키](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4#s-3)

![gg-madou1-screenshot1](/img/gg-madou1-screenshot-1.png)

![gg-madou1-screenshot2](/img/gg-madou1-screenshot-2.png)

### 적용 방법

1. **일본판 원본 ROM**을 준비합니다 (아래 체크섬으로 올바른 파일인지 확인)
2. 게임기어 영문 번역 패치([romhacking.net](https://www.romhacking.net/))를 원본 ROM에 적용해 아래 **ENG 패치 ROM** 체크섬(English v1.0, Hardware Fix)과 일치시킵니다
3. [Madou Monogatari I (Game Gear) KR v0.1.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20I%20(Game%20Gear)%20KR%20v0.1.0.bps)를 다운로드합니다
4. [Floating IPS (Flips)](https://github.com/Alcaro/Flips) 등 BPS 패처로 영어판 ROM에 한글 패치를 적용합니다

### 체크섬

#### 원본 ROM — Madou Monogatari I - 3-Tsu no Madoukyuu (Japan).gg

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `00C34D94`                                                         |
| MD5      | `abca338c5f08d06526d09b70588add2c`                                 |
| SHA-1    | `5ccd474cefcb8e086e2e1f77c0fdd5c1d2bf82e7`                         |
| SHA-256  | `4a87f02f358688bc7680d0d34f527e10a087fec95dbf7ed131241d8ffe4c0654` |
| 크기     | 524,288 bytes (512 KB)                                             |

#### ENG 패치 ROM — Madou Monogatari I (English v1.0) [Hardware Fix].gg

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `D9088BE1`                                                         |
| MD5      | `7319150b85d69519c0ff299d5c65999d`                                 |
| SHA-1    | `52dbfd0550f97c35848d48a2ca6a8d030cef2af3`                         |
| SHA-256  | `41be5b13ef7eb3ff9811606965066fc3994ddf470f7e2cb91555db37abac280c` |
| 크기     | 1,048,576 bytes (1 MB)                                             |

#### KR 패치 파일 — Madou Monogatari I (Game Gear) KR v0.1.0.bps

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `2144DF1C`                                                         |
| MD5      | `47ae166705562fb0b59561ea39b3a8e3`                                 |
| SHA-1    | `11a7d0989c067381ca4d774fb2f231a94fcc3127`                         |
| SHA-256  | `c5aa78871a5e92309ce25d6ca7dc4a6b53219ade8ea59be3cff38b95c30883f5` |
| 크기     | 54,398 bytes (53 KB)                                               |

#### KR 패치 적용 후 — Madou Monogatari I (Game Gear) KR v0.1.0.gg

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `8529734B`                                                         |
| MD5      | `209909228fdb3a46003813dd3ecbf27e`                                 |
| SHA-1    | `5928d2146110e75ab37d3db06f8a246fde984939`                         |
| SHA-256  | `79e9ae808a2466a39cde644045adc9b1a91cf4badb58c4927df5ca9199514b0e` |
| 크기     | 1,048,576 bytes (1 MB)                                             |

### 진행 상황

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [x] 시스템 UI
- [x] 시스템 안정성
- [ ] 플레이 테스트 및 최종 인게임 검수 (진행 중)

### 패치 정보

- 시나리오/이벤트 대사 번역, 시스템 UI 한글화
- 영어판 번역 패치 롬(English v1.0, Hardware Fix) 위에 적용
- 한글 폰트: [Dalmoori](https://github.com/RanolP/dalmoori-font) 8px 비트맵

### 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **한글 번역**: Claude Code (Opus 4.8)
- **QA**: mcpads
- **영어 번역 (베이스)**: 게임기어 영문 번역 패치 (English v1.0, Hardware Fix)
- **원작**: Compile (1993)

## 마도물어 II — 게임기어 (베타)

세가 게임기어 **마도물어 II - 아르르 16세 (魔導物語 II - アルル16才)** 한글 번역 패치입니다.

> ⚠️ **베타 배포 (v0.1.0)**: 게임 전반은 정상 플레이 가능하나 최종 인게임 검수가 진행 중입니다. 어색한 번역·표기·그래픽 문제는 제보해 주세요.

참고: [마도물어 - 나무위키](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4)

![gg-madou2-screenshot-1](/img/gg-madou2-screenshot-1.png)

![gg-madou2-screenshot-2](/img/gg-madou2-screenshot-2.png)

### 적용 방법

1. **일본판 원본 ROM**을 준비합니다 (아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari II (Game Gear) KR v0.1.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20II%20(Game%20Gear)%20KR%20v0.1.0.bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://github.com/Alcaro/Flips) 등 BPS 패처로 **일본판 원본 ROM**에 한글 패치를 직접 적용합니다

### 체크섬

#### 원본 ROM — Madou Monogatari II - Arle 16-Sai (Japan).gg

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `12EB2287`                                                         |
| MD5      | `81a57f26b7a1ccaa21bf7678b3596cb2`                                 |
| SHA-1    | `deead79fa4cb2e87652a9c8a76f2a7174f48f37a`                         |
| SHA-256  | `9da7d65d1772ae9b5fa71cee68b19f78bfc4848451ad6bbb5662498b2dbb997a` |
| 크기     | 524,288 bytes (512 KB)                                             |

#### KR 패치 파일 — Madou Monogatari II (Game Gear) KR v0.1.0.bps

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `2144DF1C`                                                         |
| MD5      | `e5fc03b1e3f9aee9efef0279b0813a44`                                 |
| SHA-1    | `123ef779e8834a5dd2cca900d3cc5d574fc45aba`                         |
| SHA-256  | `cd0fa730d9213c7f80b37dfb955bbf86f711b4c53ff7373565bd4aa120fd4724` |
| 크기     | 526,503 bytes (514 KB)                                             |

#### KR 패치 적용 후 — Madou Monogatari II (Game Gear) KR v0.1.0.gg

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `DB1F8194`                                                         |
| MD5      | `d87a9a228273c6bd8b0da782bbeb2f8e`                                 |
| SHA-1    | `b3c4d7c57fd1f9ce10e3561fd382464180fff6c7`                         |
| SHA-256  | `91970e5ade3656664033650824e6cc61494c1d4e908622a51a023c7855588da4` |
| 크기     | 1,048,576 bytes (1 MB)                                             |

### 진행 상황

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출 및 확장 뱅크 재배치
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 렌더러 훅
- [x] 시스템 UI
- [x] 시스템 안정성
- [ ] 플레이 테스트 및 최종 인게임 검수 (진행 중)

### 패치 정보

- 시나리오/이벤트 대사 번역, 시스템 UI 한글화
- 한글 폰트: [Dalmoori](https://github.com/RanolP/dalmoori-font) 8px 비트맵

### 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **한글 번역**: Claude Code (Opus 4.8)
- **QA**: mcpads
- **원작**: Compile (1994)

## 마도물어 III — 게임기어 (베타)

세가 게임기어 **마도물어 III - 궁극의 여왕님 (魔導物語 III - 究極の女王様)** 한글 번역 패치입니다.

> ⚠️ **베타 배포 (v0.1.0)**: 게임 전반은 정상 플레이 가능하나 최종 인게임 검수가 진행 중입니다. 어색한 번역·표기·그래픽 문제는 제보해 주세요.

참고: [마도물어 - 나무위키](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4)

![gg-madou3-screenshot-1](/img/gg-madou3-screenshot-1.png)

### 적용 방법

1. **일본판 원본 ROM**을 준비합니다 (아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari III (Game Gear) KR v0.1.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20III%20(Game%20Gear)%20KR%20v0.1.0.bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://github.com/Alcaro/Flips) 등 BPS 패처로 **일본판 원본 ROM**에 한글 패치를 직접 적용합니다

### 체크섬

#### 원본 ROM — Madou Monogatari III - Kyuukyoku Joou-sama (Japan).gg

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `0A634D79`                                                         |
| MD5      | `b8b5305ec2f68d7bb3c9f622a13eba7c`                                 |
| SHA-1    | `dd590c9086161b1f97573c48720c32cc5506dabc`                         |
| SHA-256  | `a02710b5cbf71e49a3aaa18c1e28be769bb634139fd987101c448575467f8ca3` |
| 크기     | 524,288 bytes (512 KB)                                             |

#### KR 패치 파일 — Madou Monogatari III (Game Gear) KR v0.1.0.bps

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `2144DF1C`                                                         |
| MD5      | `463b00a65eefc0a52e6b69017703091a`                                 |
| SHA-1    | `b0d56d7917b22a294f42032ddb2029b3f80c8926`                         |
| SHA-256  | `62203cae2c958f35731d03337a2fe20833844437370b4a69b3fab47115edd981` |
| 크기     | 526,244 bytes (514 KB)                                             |

#### KR 패치 적용 후 — Madou Monogatari III (Game Gear) KR v0.1.0.gg

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `76AE7609`                                                         |
| MD5      | `c365ff7a14da95ad206101f640e63441`                                 |
| SHA-1    | `e28a58a9b09c90a3dd9de0ea4422566d110f701f`                         |
| SHA-256  | `8fe5571ca714904f3909a60e38466884e83f93e4bc5233475a27469d61f20a88` |
| 크기     | 1,048,576 bytes (1 MB)                                             |

### 진행 상황

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출 및 확장 뱅크 재배치
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 렌더러 훅
- [x] 시스템 UI
- [x] 시스템 안정성
- [ ] 플레이 테스트 및 최종 인게임 검수 (진행 중)

### 패치 정보

- 시나리오/이벤트 대사 번역, 시스템 UI 한글화
- 한글 폰트: [Dalmoori](https://github.com/RanolP/dalmoori-font) 8px 비트맵

### 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **한글 번역**: Claude Code (Opus 4.8)
- **QA**: mcpads
- **원작**: Compile (1994)

## 번역 예정 작품

### 와쿠와쿠 뿌요뿌요 던전 - 완전판 (PS1)

진행 중입니다.

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [x] 시스템 UI
- [x] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 마도물어 A (게임기어)

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [x] 시스템 UI
- [x] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 마도물어 (PCE-CD)

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [x] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 마도물어 1-2-3 (PC-98)

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [ ] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

### 마도물어 A-R-S (PC-98)

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 적용
- [ ] 시스템 UI
- [ ] 시스템 안정성
- [ ] 플레이 테스트 및 최종 검수

## 이슈 제보 및 피드백

어색한 번역, 번역 오타, 심각한 그래픽 깨짐, 게임 멈춤 등의 문제는 아래 방법으로 제보해 주세요.

- **GitHub Issue**: [이슈 트래커 링크](https://github.com/mcpads/madou-monogatari-kr-patch/issues)에 새 이슈를 등록해 주세요.
- **제보 시 포함할 내용**:
  - 문제가 발생한 위치 (예: 층 3층 상점 안)
  - 문제 현상 (예: 특정 아이템 사용 시 멈춤)
  - 사용 중인 에뮬레이터 및 버전
  - (가능하다면) 스크린샷이나 세이브 파일

## 업데이트 기록

| 버전   | 날짜       | 대상                               | 내용                                                                |
| ------ | ---------- | ---------------------------------- | ------------------------------------------------------------------- |
| v1.0.0 | 2026-02-16 | 마도물어 I (MD)                    | 최초 배포                                                           |
| v0.1.0 | 2026-02-24 | 마도물어 하나마루 대유치원아       | 베타 버전 배포                                                      |
| v1.0.0 | 2026-02-26 | 마도물어 하나마루 대유치원아       | 최초 배포                                                           |
| v1.1.0 | 2026-03-01 | 마도물어 하나마루 대유치원아       | 버그 수정 (대사 잘림, 대사 오표시, 상점 매진, 선택지 하이라이트 등) |
| v1.1.0 | 2026-03-06 | 마도물어 I (MD)                    | 번역 다수 수정, 층 표시 수정, 텍스트 잘림 수정                      |
| v1.2.0 | 2026-03-07 | 마도물어 하나마루 대유치원아       | 몇몇 번역 관련 버그 패치                                            |
| v0.1.0 | 2026-03-07 | 마도물어 (세가 새턴)               | 베타 배포 (시스템 UI 미번역)                                        |
| v0.2.0 | 2026-03-08 | 마도물어 (세가 새턴)               | 베타 배포 (번역 교정, 추가 UI 한글화)                               |
| v0.3.0 | 2026-03-08 | 마도물어 (세가 새턴)               | 뿌요카드 버그 수정                                                  |
| v1.3.0 | 2026-03-09 | 마도물어 하나마루 대유치원아       | 몇몇 미번역 오류 수정                                               |
| v0.4.0 | 2026-03-11 | 마도물어 (세가 새턴)               | 시스템 UI 추가 번역                                                 |
| v1.0.0 | 2026-03-17 | 마도물어 (세가 새턴)               | 정식 배포                                                           |
| v0.1.0 | 2026-03-24 | 와쿠와쿠 뿌요뿌요 던전 (세가 새턴) | 베타 배포                                                           |
| v1.1.0 | 2026-07-05 | 마도물어 (세가 새턴)               | 선택지 진행 불가 및 텍스트 오버플로우 수정                          |
| v0.1.0 | 2026-07-08 | 마도물어 I (게임기어)              | 베타 배포                                                          |
| v0.1.0 | 2026-07-08 | 마도물어 II (게임기어)              | 베타 배포                                                          |
| v0.1.0 | 2026-07-08 | 마도물어 III (게임기어)              | 베타 배포                                                          |

## 라이선스

- 본 패치 파일은 개인적, 비상업적 용도로 제공됩니다. 원작 게임의 저작권은 해당 권리자에게 있습니다.
- 본 한글패치 파일 자체를 제작자에 허가없이 타 사이트에 재배포하지 말아 주시고, 재배포를 원하실 경우 패치원본 게시물의 링크를 공유해 주시기 바랍니다.
- 본 한글패치 파일을 이용하여 금전적 이득을 취하는 모든 행위를 일절 금합니다. 해당 행위로 발생하는 모든 책임은 이용 당사자에게 있으며, 패치 제작자는 어떠한 책임도 지지 않습니다.
