# 마도물어 II — 게임기어 (베타)

[전체 마도물어 한글 패치 목록으로 돌아가기](../README.md)

세가 게임기어 **마도물어 II - 아르르 16세 (魔導物語 II - アルル16才)** 한글 번역 패치입니다.

> ⚠️ **베타 배포 (v0.4.0)**: 게임 전반은 정상 플레이 가능하나 최종 인게임 검수가 진행 중입니다. 어색한 번역·표기·그래픽 문제는 제보해 주세요.

참고: [마도물어 - 나무위키](https://namu.wiki/w/%EB%A7%88%EB%8F%84%EB%AC%BC%EC%96%B4)

![gg-madou2-screenshot-1](../img/gg-madou2-screenshot-1.png)

![gg-madou2-screenshot-2](../img/gg-madou2-screenshot-2.png)

## 적용 방법

1. **일본판 원본 ROM**을 준비합니다 (아래 체크섬으로 올바른 파일인지 확인)
2. [Madou Monogatari II (Game Gear) KR v0.4.0.bps](https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/Madou%20Monogatari%20II%20(Game%20Gear)%20KR%20v0.4.0.bps)를 다운로드합니다
3. [Floating IPS (Flips)](https://github.com/Alcaro/Flips) 등 BPS 패처로 **일본판 원본 ROM**에 한글 패치를 직접 적용합니다

## 체크섬

### 원본 ROM — Madou Monogatari II - Arle 16-Sai (Japan).gg

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `12EB2287`                                                         |
| MD5      | `81a57f26b7a1ccaa21bf7678b3596cb2`                                 |
| SHA-1    | `deead79fa4cb2e87652a9c8a76f2a7174f48f37a`                         |
| SHA-256  | `9da7d65d1772ae9b5fa71cee68b19f78bfc4848451ad6bbb5662498b2dbb997a` |
| 크기     | 524,288 bytes (512 KB)                                             |

### KR 패치 파일 — Madou Monogatari II (Game Gear) KR v0.4.0.bps

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `2144DF1C`                                                         |
| MD5      | `ffb0fbb42165b73a964e33c269a83f1b`                                 |
| SHA-1    | `033e9a8d3937749df5c083a5576c0f8787bbe4d4`                         |
| SHA-256  | `e9b15b4ae79226a50f940dff0a1b5c7d2e00e942973735b627da2beeaa0c8630` |
| 크기     | 526,591 bytes (514 KB)                                             |

### KR 패치 적용 후 — Madou Monogatari II (Game Gear) KR v0.4.0.gg

| 알고리즘 | 해시                                                               |
| -------- | ------------------------------------------------------------------ |
| CRC32    | `B18BD6CE`                                                         |
| MD5      | `5709dfcf8d227dbc52c698176c7c772b`                                 |
| SHA-1    | `54decb713bbe1389308210be85985578fe0fbbdb`                         |
| SHA-256  | `b3a5c8f27611d098bab3375c28c2225890317411f29dcd494e4828c0695e718f` |
| 크기     | 1,048,576 bytes (1 MB)                                             |

## 진행 상황

- [x] 일본어 폰트 추출 및 테이블 완성
- [x] 시나리오 텍스트 추출 및 확장 뱅크 재배치
- [x] 시나리오 및 이벤트 대사 번역
- [x] 한글 폰트 통합 및 렌더러 훅
- [x] 시스템 UI
- [x] 시스템 안정성
- [ ] 플레이 테스트 및 최종 인게임 검수 (진행 중)

## 패치 정보

- 시나리오/이벤트 대사 번역, 시스템 UI 한글화
- 한글 폰트: [Dalmoori](https://github.com/RanolP/dalmoori-font) 8px 비트맵
- [패쳐 코드베이스](https://github.com/mcpads/gg-madou2-kr-patcher)

## 크레딧

- **패치 제작자**: mcpads
- **리버싱**: mcpads (with Claude Code)
- **한글 번역**: Claude Code (Opus 4.8)
- **QA**: mcpads
- **원작**: Compile (1994)
