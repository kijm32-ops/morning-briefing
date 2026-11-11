# morning-briefing

매일 아침 자동 발행되는 브리핑의 게시 저장소입니다. `docs/` 폴더가 GitHub Pages로 서비스됩니다.

| 경로 | 내용 |
|---|---|
| `docs/index.html` | 모닝 경제지도 AI — 날짜별 리포트 목록 |
| `docs/reports/YYYY-MM-DD.html` | 그날의 마켓 브리핑 |
| `docs/world-briefing/index.html` | WORLD BRIEFING 최신호 (매일 덮어씀) |
| `docs/assets/` | 페이지에서 쓰는 이미지 |

## 주의

- 이 저장소의 HTML은 사람이 고치지 않습니다. 브리핑을 만드는 Apps Script가 GitHub API로 직접 커밋합니다. 손으로 고친 내용은 다음 발행 때 덮어써집니다.
- 생성 코드와 설정은 비공개 저장소 `briefing`에 있습니다. 페이지 모양이나 내용을 바꾸려면 그쪽을 고칩니다.
- 모든 페이지에는 `noindex`가 들어 있어 검색 엔진에 노출되지 않습니다.
