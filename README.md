# Local Chess Coach v1.0

Windows x64와 Chrome에서 완료된 Chess.com 대국을 Stockfish로 분석하는 한국어 복기 도구입니다.

## 다운로드 및 설치

**[배포 ZIP 받기](local-chess-coach-v1.0.zip)** · **[Chrome 설치 안내](local-chess-coach-v1.0/INSTALL_KO.md)**

1. Chrome에 [Tampermonkey](https://www.tampermonkey.net/)를 설치합니다.
2. ZIP을 모두 압축 해제하고 **install.cmd**를 실행합니다.
3. 자동 복사된 내용을 Tampermonkey의 새 스크립트 편집기에 붙여넣고 저장합니다.

Node.js와 Stockfish는 설치 프로그램이 자동으로 다운로드합니다. 이후에는 **start-coach.cmd**만 실행하고 복기하는 동안 창을 열어 두세요.

[Stockfish 공식 다운로드 페이지](https://stockfishchess.org/download/)도 참고할 수 있습니다.

## 배포 파일

- `local-chess-coach-v1.0.zip`: 사용자에게 전달할 설치 패키지
- `local-chess-coach-v1.0.zip.sha256`: ZIP 무결성 확인용
- `local-chess-coach-v1.0/`: ZIP에 포함된 원본 파일과 설치·배포 안내

최근 20국 분석에서 오류 기보가 나와도 다음 기보로 계속 진행하는 수정이 포함되어 있습니다. 최대 20개의 분석 가능한 대국을 가져온 목록에서 찾으며, 목록이 부족하면 실제 완료 개수를 표시합니다.

[공개 배포 방법](local-chess-coach-v1.0/DISTRIBUTION_KO.md) · [기능 안내](local-chess-coach-v1.0/coach/README.md)

이 폴더에는 개인 인증 키와 분석 기록이 포함되지 않습니다. 설치 후 생성되는 개인 파일은 다시 배포하지 마세요. 공개 업로드는 아직 하지 않았습니다.
