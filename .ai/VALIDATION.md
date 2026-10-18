# Validation

코드와 빌드가 없는 발행 저장소다. 확인하지 않은 명령은 임의로 작성하지 않는다.

## Pre-check

- `git status`
- placeholder 검사: `<REQUIRED:`

## Backend

- 없음

## Frontend

- 없음. 필요하면 발행된 `docs/` 파일이 열리는지 직접 확인한다.

## Database

- 없음

## Final

- `git diff --check`
- `git diff`
- 자동 발행 파일이 예상 외로 바뀌지 않았는지 확인
