# STRUCTURE · sowk-sample

```
sowk-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = sowk-sample → sowk-sample.lgt3232.workers.dev
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ sw-intertight.woff2        영문 (Inter Tight 400–700, 쓰는 글자만)
├─ sw-pretendard.woff2        한글 (Pretendard 400–600, 쓰는 글자만)
├─ sw-figure.svg              로고 두 사람 그림 (잉크 #151515, potrace 벡터)
├─ sw-figure-w.svg            같은 그림 밝은 색 (밤 섹션)
├─ sw-hero.webp               히어로 (원형 테이블 햇살)
├─ sw-latte / sw-dessert / sw-wine .webp          Menu 카드 3장
├─ sw-window / sw-sofa / sw-shelf / sw-sun / sw-table / sw-mat .webp   Space 6장
├─ sw-dusk.webp               After dark (밤 전면 유리)
├─ sw-ext.webp                Visit 외관 (밤 코너)
├─ favicon.png · og-sowk.jpg
├─ img/                       다올 제공 원본 49장 (배포 제외 · 블로그 워터마크 · 사람 · 다른 브랜드 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#about` → `#menu` → `#space` → After dark(`.night`) → `#visit` → 푸터 + 모바일 `.quick`(nav).

## 링크 한곳 정리
- 네이버 지도 길찾기 `map.naver.com/p/entry/place/2002921080`: 헤더 · 히어로 · 오시는 길 · 하단 바
- 인스타 `https://www.instagram.com/sowkcoffee/`: 히어로 · 밤 섹션 · 오시는 길 · 푸터 · 하단 바
- 전화 `tel:050714111680`: 오시는 길 · 푸터 · 하단 바

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 영문은 Inter Tight, 한글은 Pretendard 서브셋에 들어감.
