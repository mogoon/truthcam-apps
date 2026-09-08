# CLAUDE.md

이 파일은 Claude Code가 이 리포에서 작업할 때 참고하는 안내서다.

## Project Overview

TruthCam 데스크톱 앱(TruthScan, TruthDesk)의 배포/다운로드 안내용 리포다. 실제 소스 코드는 포함되어 있지 않으며, GitHub Releases 링크와 설치 가이드만 제공한다.

## Tech Stack

- Markdown 문서 (`README.md`)만 존재. 빌드 시스템 없음.

## Development Commands

- 별도 빌드/실행 커맨드 없음. 릴리스 아티팩트는 `mogoon/truthcam-apps` GitHub Releases에 업로드됨 (`truthscan-v*` 태그).

## Project Structure

- `README.md` — TruthScan/TruthDesk/TruthCam Mobile 다운로드 링크 및 플랫폼별 설치 안내 (한/영 병기)

## Notes for Claude

- 다운로드 링크와 버전 번호를 수정할 때는 실제로 릴리스된 태그(`truthscan-v0.1.2` 등)와 일치하는지 확인할 것.
- 실제 앱 코드는 `/Users/mogoon/workspace/truthscan`, `/Users/mogoon/workspace/truthdesk`에 있음.
- **이 리포는 배포 채널 전용** — 배포·릴리스 이슈만 여기서 다루고, 코드 수정은 TruthDesk / TruthScan 리포에서 함.
- 관련 프로젝트: TruthCam (`/Users/mogoon/workspace/truthcam`) — 백엔드/모바일 본체.
