# ttukttak-assets

앱인토스 미니앱들의 **공개 정적 에셋** 저장소 — 공유(OG) 배너 등 외부 서버(카톡 등)가
직접 fetch해야 하는 이미지를 프로젝트별 폴더로 관리한다.

## 사용 규약
- 폴더 = 프로젝트: `ttukttak/`, `goldvines/`, `luckyslot/` …
- OG 배너 규격: **정확히 1200×600** (토스 공유 링크 요구사항), https 절대경로만 허용
- raw URL 패턴:
  `https://raw.githubusercontent.com/YDINP/ttukttak-assets/main/<프로젝트>/<파일>`
- ⚠️ 메신저(카톡 등)는 링크별 미리보기를 캐시함 — 이미지 교체 시 **파일명을 바꿔** 올릴 것

## 현재 에셋
| 프로젝트 | 파일 | 용도 |
|---|---|---|
| ttukttak | og-1200x600.png | 공유 링크 OG 배너 (getTossShareLink ogImageUrl) |
| goldvines | og-1200x600.png | 공유 링크 OG 배너 |
