# kimwoobin.github.io

기술 블로그와 회고록을 위한 GitHub Pages 사이트입니다.

## 구조

- `_posts/`: 기술 블로그 글
- `_memoirs/`: 회고록 글
- `blog/index.html`: 기술 블로그 목록
- `memoirs/index.html`: 회고록 목록
- `about/index.html`: 소개 페이지
- `_layouts/`, `_includes/`: 공통 레이아웃
- `assets/css/style.css`: 사이트 스타일

## 글 작성

기술 글은 `_posts/YYYY-MM-DD-title.md` 형식으로 추가합니다.

```markdown
---
title: "글 제목"
date: 2026-05-09
description: "짧은 설명"
tags: [tag1, tag2]
---

본문을 작성합니다.
```

회고록은 `_memoirs/YYYY-MM-DD-title.md` 형식으로 추가합니다.

GitHub Pages에서 사용자 사이트로 운영하려면 저장소 이름을 `kimwoobin.github.io`로 맞추고 Pages 소스를 `main` 브랜치 루트로 설정하면 됩니다.
