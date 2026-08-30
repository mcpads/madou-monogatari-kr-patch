# 마도물어 1-2-3 (PC-98) 한글 패치

PC-98용 합본 재발매판 *마도물어 1-2-3*에 적용하는 한글 번역 패치입니다.

![PC-98 마도전기 1-2-3 한글 타이틀 화면](../img/pc98-madou-123-title-runtime.png)

> 이 패치는 베타 버전입니다. 번역과 전체 진행 검수가 끝나지 않았으며, 미번역 요소나 진행에 영향을 주는 문제가 남아 있을 수 있습니다. 문제를 발견하면 편·장면·사용한 에뮬레이터와 함께 제보해 주세요.

## 배포 파일

| 다운로드 | SHA-256 |
| --- | --- |
| [Madou Monogatari 1-2-3 (PC-98) KR v0.1.0.zip](<https://raw.githubusercontent.com/mcpads/madou-monogatari-kr-patch/main/pc98-madou-123/Madou%20Monogatari%201-2-3%20(PC-98)%20KR%20v0.1.0.zip>) | `d8ae46c03007be3d4a87a052cecf577f3ff5c46963b1b2633e65c65da201ba68` |

패치 세트 ZIP은 압축을 풀지 않고 웹 패처에서 그대로 선택합니다.

Data 디스크에는 패치를 적용하지 않습니다. 후반부와 엔딩에서 요구하면 원본을 그대로 사용합니다.

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
2. 위의 패치 세트 ZIP을 다운로드합니다.
3. [RetroGame Patcher](https://patcher.retrogame.cloud/)를 엽니다.
4. 패치 세트 ZIP을 먼저 선택한 다음 원본 HDM 여섯 장을 선택합니다. 여러 장을 한 번에 선택하거나 빠진 디스크를 나중에 추가해도 됩니다.
5. 여섯 원본이 모두 인식되면 **검사하고 적용하기**를 누릅니다.
6. 적용이 끝나면 완성된 System·Sampling HDM 여섯 장을 내려받습니다.

파일명과 선택 순서는 상관없으며, 패처가 SHA-256으로 각 디스크를 대응합니다. 패치 ZIP과 원본·결과 HDM은 서버로 전송되지 않고 브라우저 안에서 처리됩니다.

[웹 패처 소스 코드](https://github.com/mcpads/retro-patcher)

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
