# 프라임경영인증연구원 — 홈페이지 프로토타입

공유·리뷰용 정적 프로토타입. 실제 운영 전 피드백 수렴 목적.

## 파일 구성

| 파일 | 설명 |
|------|------|
| `index.html` | **모바일 버전** (GitHub Pages 루트로 서빙됨) |
| `desktop.html` | 데스크톱 참고본 |

## 공유 URL

```
https://rnwhgowh2-commits.github.io/iso_mobile_v2/
```

모바일 기기에서는 네이티브 앱처럼 풀스크린으로, PC에서는 폰 프레임 안에 모바일 UI가 표시됩니다.

## 기술 스택

- 순수 정적 HTML (빌드 불필요)
- TailwindCSS CDN
- Pretendard Variable 웹폰트
- Vanilla JS (페이지 전환·드로어·바텀시트)

## 로컬 미리보기

브라우저로 `index.html` 또는 `desktop.html` 더블클릭.

## 편집 가이드

| 대상 | 위치 |
|------|------|
| 컨텐츠·문구 | 각 HTML 내 `<section id="...">` 블록 |
| 브랜드 컬러 | `<script>tailwind.config</script>` > `colors` |
| 네비게이션 | `<header>` / `<nav class="...bottom...">` |

## 반영 예정 (TBD)

- 대표 사진 · 학력 · 경력 · 자격
- 사무실 주소 · 전화 · 이메일 · 사업자등록번호
- 실제 고객사 후기
- 확정 컨설팅 비용 구간
- 실제 로고 이미지

---

© 2026 PRIME Management Certification Institute.
