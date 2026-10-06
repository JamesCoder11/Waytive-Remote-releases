# Waytive Remote

공식 설치 파일과 Sparkle 업데이트 피드를 제공하는 **배포 전용 저장소**입니다. 애플리케이션 소스 코드는 이 저장소에 포함하지 않습니다.

## 다운로드

- [최신 릴리스](https://github.com/JamesCoder11/Waytive-Remote-releases/releases/latest)
- 지원 환경: Apple Silicon Mac, macOS 14 이상
- 설치: ZIP을 풀고 `Waytive Remote.app`을 응용 프로그램 폴더로 옮깁니다.

현재 원격 기능은 같은 네트워크 또는 도달 가능한 VPN 주소의 Mac 간 연결을 위한 개발 프리뷰입니다. 인터넷 중계와 Windows 지원은 아직 제공하지 않습니다.

## 인앱 업데이트

앱 메뉴에서 **업데이트 확인…**을 누릅니다. 연결 중인 원격 세션이 있으면 먼저 종료해 주세요. 공개 ZIP은 Developer ID 서명과 Apple 공증을 거치고, 업데이트 아카이브는 Sparkle EdDSA 서명으로 검증합니다.

피드: https://raw.githubusercontent.com/JamesCoder11/Waytive-Remote-releases/main/appcast.xml

0.1.0 및 이전 피드 주소를 사용한 0.1.1은 새 배포본으로 한 번 수동 교체해야 합니다. 0.1.2부터 이 GitHub 피드를 사용합니다.

## 보안

기기 등록 링크에는 접속 권한이 포함되므로 공개 이슈에 올리지 마세요. 업데이트 서명 개인 키와 사용자 기기 키는 이 저장소에 포함하지 않습니다.

Copyright 2026. Waytive All rights reserved.
