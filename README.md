# 프라임경영인증연구원 — 홈페이지 프로토타입

공유·리뷰용 정적 프로토타입. 실제 운영 전 피드백 수렴 목적.

## 파일 구성

| 파일 | 설명 |
|------|------|
| `index.html` | 데스크톱 웹사이트 (전체 22페이지) |
| `mobile.html` | 모바일 앱 스타일 (하단 탭바·드로어·바텀시트) |

모바일 기기로 `index.html` 접속 시 `mobile.html`로 자동 전환. `?desktop=1` 쿼리를 붙이면 모바일에서도 데스크톱 뷰로 강제 전환.

## 공유 URL 예시 (GitHub Pages)

```
https://{GitHub_사용자명}.github.io/{저장소명}/
```

## 배포 절차

1. GitHub 저장소 생성
2. 이 폴더 전체를 푸시
3. `Settings → Pages → Source: Deploy from a branch`
4. `Branch: main` · `Folder: / (root)` 선택
5. 저장 후 1~2분 대기 → URL 발급

## 기술 스택

- **프레임워크 없음** — 순수 정적 HTML
- **TailwindCSS CDN** — 빌드 불필요
- **Pretendard Variable** — 한글 최적화 웹폰트
- **Vanilla JS** — 페이지 전환·드로어·바텀시트·디바이스 감지

## 로컬 미리보기

브라우저로 `index.html` 또는 `mobile.html` 더블클릭.

## 편집 가이드

| 대상 | 위치 |
|------|------|
| 컨텐츠·문구 | 각 HTML 내 `<section id="...">` 블록 |
| 브랜드 컬러 | `<script>tailwind.config</script>` > `colors` |
| 폰트 크기 | `fontSize` 설정 (index) / 인라인 클래스 (mobile) |
| 네비게이션 | `<header>` (desktop) / `<nav class="...bottom...">` (mobile) |

## 반영 예정 (TBD 표시)

- 대표 사진 · 학력 · 경력 · 자격
- 사무실 주소 · 전화 · 이메일 · 사업자등록번호
- 실제 고객사 후기
- 확정 컨설팅 비용 구간
- 실제 로고 이미지

---

© 2026 PRIME Management Certification Institute.
