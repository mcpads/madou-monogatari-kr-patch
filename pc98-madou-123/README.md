# 마도물어 1-2-3 (PC-98) 한글 패치

PC-98용 합본 재발매판 *마도물어 1-2-3*에 적용하는 한글 번역 패치입니다.

![PC-98 마도전기 1-2-3 한글 타이틀 화면](../img/pc98-madou-123-title-runtime.png)

> 이 패치는 베타 버전입니다. 번역과 전체 진행 검수가 끝나지 않았으며, 미번역 요소나 진행에 영향을 주는 문제가 남아 있을 수 있습니다. 문제를 발견하면 편·장면·사용한 에뮬레이터와 함께 제보해 주세요.

## 배포 형식

이 패치는 원본 디스크나 패치 완료 디스크를 포함하지 않습니다. 각 원본 HDM에 적용하는 BPS 파일 여섯 개로 배포합니다.

Data 디스크에는 패치를 적용하지 않습니다. 후반부와 엔딩에서 요구하면 원본을 그대로 사용합니다.

| 대상 | BPS | BPS SHA-256 | 적용 후 HDM SHA-256 |
| --- | --- | --- | --- |
| 1편 System | [다운로드](<Madou Monogatari 1-2-3 (PC-98) KR v0.1.0 - Game 1 System.bps>) | `3eea352b2c064c6f910e70646920f6f3c33fef2917a04f9267efa16540326f18` | `b77268ec3c45fcefc0e0131df0d51d0dd067d1713068242fa373798752681af2` |
| 1편 Sampling | [다운로드](<Madou Monogatari 1-2-3 (PC-98) KR v0.1.0 - Game 1 Sampling.bps>) | `a0fe5b56dd519a568f2dc94700785f57dd6e277f55eb0fe82be4df536a9fe682` | `d8c56c87b1fc0a491e2774b7a39f7028ac2d1ef03e37507dd4318955cc92902d` |
| 2편 System | [다운로드](<Madou Monogatari 1-2-3 (PC-98) KR v0.1.0 - Game 2 System.bps>) | `324874b5017c5ec254be0c2db2fd6cb94df50c73234644b30e1aa854e73d1978` | `7a40885023d0cad364c37655eb5a20808a02c0f58e46726d4771dbe6209eb283` |
| 2편 Sampling | [다운로드](<Madou Monogatari 1-2-3 (PC-98) KR v0.1.0 - Game 2 Sampling.bps>) | `9aec1c7bab4e23cd59480540dbdf2875ace30d4ecd77746e4be3ae15433590f7` | `44992499eb2fb282d8a3c90228a9c8630a3b9d9c88cb849e2b4e24b3bdb4c964` |
| 3편 System | [다운로드](<Madou Monogatari 1-2-3 (PC-98) KR v0.1.0 - Game 3 System.bps>) | `b5915c6aac3e4d5919093f15d9cf63525d2d4c795c44e266897c37a579664b56` | `8953a9dc0059519355236fbec85d22610aa6726564061df7da8f7e24ceadce84` |
| 3편 Sampling | [다운로드](<Madou Monogatari 1-2-3 (PC-98) KR v0.1.0 - Game 3 Sampling.bps>) | `b3c5b86d8765f48e542949c1b685d38701a4507a86cbf243cca624acf33e5d42` | `91513825a5890f9b925935dd72f6b80024be54f339d9b8f374f16ca08dd2bf03` |

## 지원 원본

합본 재발매판의 헤더 없는 System·Sampling HDM 여섯 장만 패치 입력으로 지원합니다. 파일명은 달라도 되지만 크기와 SHA-256이 모두 일치해야 합니다. `.hdi` 하드디스크 이미지나 D88 변환본은 지원하지 않습니다.

모든 패치 입력 HDM의 크기는 `1,261,568`바이트입니다.

| 디스크 | SHA-256 |
| --- | --- |
| 1편 System | `1a56a5a798f61caf1d9307746be3db67c5f0df74d49add7fd1ea9fc9deb59922` |
| 1편 Sampling | `afeda1b9319a03091079a6045ff0f23dbe6cb1ea4752fb619c69420f4b8ee661` |
| 2편 System | `daaa02c7fdce3a7121a1e5b36e9a316460482992a7a15247f67a533c759b9aed` |
| 2편 Sampling | `b1152cae40f580a91cc9fae3316e28e3cfccdbd5ed071ea083c481684a9ac440` |
| 3편 System | `7fbd6492ab8dbd3ba09f6bcb4f0a363474b3465f9f4d13ff6dd8922119243d88` |
| 3편 Sampling | `8fd0bd0cc3be6716c32554c5ba8c01ff6f0e72cd4d90b56efa67c8e31a7fdecb` |

## 적용 방법

1. 패치할 원본 HDM 여섯 장을 별도 위치에 백업합니다.
2. [Floating IPS](https://www.smwcentral.net/?p=section&a=details&id=11474) 등 BPS 패처를 준비합니다.
3. 각 편의 System 원본에는 같은 편의 System BPS를 적용하고, Sampling 원본에는 같은 편의 Sampling BPS를 적용합니다.
4. 원본과 구분되는 새 파일명으로 결과를 저장합니다. 원본 디스크에 직접 덮어쓰지 마세요.
5. BPS 패처가 원본 불일치를 보고하면 적용을 중단하고 위 SHA-256을 다시 확인합니다.
6. 배포본에 적힌 적용 후 SHA-256과 결과가 일치하는지 확인한 뒤 실행합니다.

한 편의 System과 다른 편의 Sampling을 섞거나, 서로 다른 패치 버전의 디스크를 함께 사용하지 마세요.

## 실행 방법

HDM과 PC-98의 두 플로피 드라이브를 지원하는 에뮬레이터가 필요합니다.

| 드라이브 | 넣을 디스크 |
| --- | --- |
| FDD1 | 플레이할 편의 패치된 System |
| FDD2 | 같은 편의 패치된 Sampling |

두 디스크를 넣은 상태에서 PC-98을 시작하거나 리셋합니다.

진행 후반부나 엔딩에서 Data 디스크를 요구하면 FDD1의 System은 그대로 두고, FDD2의 Sampling을 원본 Data 디스크로 교체합니다.

## 문제 제보

문제는 [GitHub Issues](https://github.com/mcpads/madou-monogatari-kr-patch/issues)에 제보해 주세요. 다음 정보를 함께 남기면 확인에 도움이 됩니다.

- 플레이한 편과 문제가 발생한 장면
- 사용한 패치 버전
- 에뮬레이터 이름과 버전
- 재현 순서
- 가능하면 스크린샷과 세이브 파일

[전체 마도물어 한글 패치 목록으로 돌아가기](../)
