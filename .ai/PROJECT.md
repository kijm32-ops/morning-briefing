# Project

## Purpose

매일의 모닝 브리핑과 보고서를 발행한 결과물을 담는 저장소다. 커밋 이력은 `report: ... 모닝 브리핑 발행`, `index: ... 갱신`, `world-briefing: ... 최신 브리핑 발행` 형태의 자동 발행이다. 이 저장소는 공개(public)다.

## Architecture

- Frontend: `docs/` 디렉터리 (파일 형식은 확인하지 않았다)
- Backend: 없음
- Database: 없음

## Important directories

- `docs/` — 발행 결과물로 보인다

## Environments

### Development

- 없음. 코드와 빌드 설정이 없다.

### Production / Deployment target

- GitHub Pages 사용 여부는 확인하지 않았다.

## Invariants

- 발행 결과물은 외부 자동화가 commit한다. 자동 발행 commit의 이력을 다시 쓰거나 형식을 바꾸지 않는다.
- 환자 정보, 계정 비밀값, API 키를 올리지 않는다. 공개 저장소다.
- 발행된 파일의 위치와 형식은 외부 자동화가 기대할 수 있다. 요청 없이 바꾸지 않는다.
