# 발표자료 모음

팀 발표자료를 모아 GitHub Pages로 배포하는 정적 사이트입니다.

🔗 **https://frontleejonghun.github.io/jiktong-html/**

## 구성

| 경로 | 내용 |
| --- | --- |
| `/` | 발표자료 목록 (랜딩) |
| `/jiktong/` | 직통 (直·通) — 직군과 직통으로 통한다 · AX Project Team 03 |
| `/knowbis/` | 노비스 (Knowbis) — 전사 월간리뷰 |
| `/piewatch/` | PieWatch 🐶 — 우리 서버를 지켜보는 강아지 |

각 발표자료는 `<디렉토리>/index.html` 단일 정적 파일이며 별도 빌드가 없습니다.

## 조작 (직통 덱)

| 키 | 동작 |
| --- | --- |
| `←` / `→` | 이전 / 다음 슬라이드 |
| `Space` | 다음 슬라이드 |
| `Home` / `End` | 처음 / 마지막 슬라이드 |
| 화면 좌/우 클릭 | 이전 / 다음 슬라이드 |

## 배포

`main` 브랜치 루트(`/`)를 GitHub Pages가 그대로 서빙합니다. `main`에 push하면 자동 반영됩니다. (`.nojekyll`로 Jekyll 처리는 비활성화)
