# 건축설계 · IngeTrazo 자동 업데이트

한국어 CAD 도면 편집기와 자재산출 도구의 Windows 업데이트 배포 저장소입니다.

## 자동 업데이트

프로그램은 아래 주소에서 새 버전을 확인합니다.

`https://github.com/Mrkim-pixel/architecture-ingetrazo-updates/releases/latest/download/architecture-ingetrazo-update.json`

- 하루 한 번 새 버전을 확인하고 백그라운드에서 다운로드합니다.
- SHA-256 검증 후, 작업 저장을 확인한 정상 종료 때 적용합니다.
- 사용자 도면·자재·견적·설정 및 Python/Qt 실행 환경은 교체하지 않습니다.
- 기존 architecture-updates v1.39.1 경로와 분리됩니다.

## 배포 파일 및 소스

[최신 릴리스](https://github.com/Mrkim-pixel/architecture-ingetrazo-updates/releases/latest)의 업데이트 ZIP과 JSON은 기존 설치 폴더용입니다. 새 PC 설치에 필요한 전체 Python/Qt 런타임은 포함하지 않습니다.

업데이트 ZIP에는 실제 Python·JavaScript·C# 소스, 빌드 스크립트, 기준 HTML, 한국어 번역표와 IngeTrazo 엔진 소스가 포함됩니다.

## 라이선스

IngeTrazo 및 파생 Python 통합 코드는 GPL-3.0-or-later입니다. 원본은 https://github.com/ingelibre/ingetrazo 이며 기준 커밋은 `50606992c052ef7e3e36832005e19d138eaac939`입니다. 원본 라이선스 및 개별 자산 고지도 ZIP에 포함합니다.

사용자 도면·현장 자료·가격 데이터·인증 정보는 업로드하지 않습니다.
