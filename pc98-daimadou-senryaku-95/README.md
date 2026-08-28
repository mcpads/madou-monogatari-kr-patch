# 대마도전략물어'95 — PC-98 (베타)

[전체 마도물어 한글 패치 목록으로 돌아가기](../README.md)

Disc Station Vol. 08 수록작 《대마도전략물어'95》의 PC-98 한글 번역 베타 패치입니다.

> ⚠️ **베타 배포 (v0.1.0)**: 번역과 그래픽은 이후 배포에서 변경될 수 있습니다.

![PC-98 대마도전략물어'95 한글 타이틀 화면](../img/pc98-daimadou-senryaku-95-title-runtime.png)

## 배포 파일

원하는 아르르 그래픽에 따라 두 패키지 중 하나를 사용합니다.

| 판본 | 설명 | 다운로드 | SHA-256 |
| --- | --- | --- | --- |
| 커스텀 아르르 | 새로 제작한 아르르 그래픽을 사용합니다. | [다운로드](<Daimadou Senryaku Monogatari '95 (PC-98) KR v0.1.0 Custom Arle.zip>) | `85afb099975fa093e16823a574d7c6324d131a02411b89942e94e03c46e27980` |
| 원본 아르르 | 원작의 아르르 그래픽을 유지합니다. | [다운로드](<Daimadou Senryaku Monogatari '95 (PC-98) KR v0.1.0 Original Arle.zip>) | `ca702fd148f782488759aa231629b4c5ea618f0eeea7fcd8e152971cb6b1a042` |

두 패키지 모두 한글 번역을 포함합니다. 패치 ZIP은 압축을 풀지 않고 웹 패처에서 그대로 선택합니다.

## 지원 원본

Disc Station Vol. 08 Disk 1의 헤더 없는 원본 HDM을 지원합니다.

| 항목 | 값 |
| --- | --- |
| 크기 | 1,261,568 bytes |
| SHA-256 | `b2ade325198210914e1cd1a6add3724fb4de1a1c5e5f8f617acfe7999234c122` |

파일명이 달라도 크기와 SHA-256이 일치하면 사용할 수 있습니다.

## 적용 방법

1. 원본 HDM을 별도 위치에 백업합니다.
2. 위의 패치 ZIP 중 하나를 다운로드합니다.
3. [RetroGame Patcher](https://patcher.retrogame.cloud/)를 엽니다.
4. 패치 ZIP을 먼저 선택한 다음 원본 HDM을 선택합니다.
5. **검사하고 적용하기**를 누르고, 검사가 끝나면 완성된 HDM을 내려받습니다.

패치 ZIP과 원본·결과 HDM은 서버로 전송되지 않고 브라우저 안에서 처리됩니다.

## 패치 정보

- 원본에서 필요한 게임 파일을 읽고 파일별 BPS를 적용해 독립 실행 HDM을 만듭니다.
- [웹 패처 소스 코드](https://github.com/mcpads/pc98-fat12-patcher-tool)
