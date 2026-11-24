# auction_get_list_release

GV Car List 앱(`gvr.exe`)의 **배포(릴리스) 전용 저장소**입니다.
소스 코드는 비공개 저장소 `auction_get_list` 에 있고, 이곳에는 **빌드 산출물만** 올립니다.

## 구성

| 파일 | 설명 |
|---|---|
| `gvr.exe` | 최신 포터블 실행 파일 |
| `version.json` | 버전 매니페스트(버전·다운로드 URL·sha256·변경내역) — 앱 자동 업데이트가 이 파일을 확인 |

## 다운로드

- 최신 실행 파일: <https://github.com/wbslog/auction_get_list_release/raw/main/gvr.exe>
- 버전 정보: <https://github.com/wbslog/auction_get_list_release/raw/main/version.json>

## 배포 방법(관리자)

소스 저장소에서 `npm run dist` 로 `dist/gvr.exe` 를 빌드한 뒤, 이 저장소에
`gvr.exe` 를 갱신하고 `version.json` 의 `version`·`sha256`·`releaseDate`·`notes` 를
올려 커밋/푸시하면 됩니다. (자동화 스크립트는 소스 저장소 참고)

## 현재 버전

- **1.0.0** (2026-11-24)
