# Öusia

패션 매거진 Öusia 의 웹사이트. 정적 사이트(HTML 한 장 + 이미지)라 빌드 과정이 없다.

```
index.html   사이트 본체
img/         사진 137장
CNAME        연결할 도메인
404.html     없는 주소 → 첫 화면
.nojekyll    GitHub Pages 가 파일을 그대로 내보내게
```

GitHub Pages: Settings → Pages → Source `main` / `(root)`

## 구성

```
/          데스크톱 웹사이트
/app/      모바일 앱 버전 (사진은 /img 를 함께 쓴다)
/img/      사진 137장 — 양쪽이 공유
```

폰에서 `/` 로 들어오면 `/app/` 으로 보낸다 (netlify.toml). 주소를 직접 치면 양쪽 다 그대로 열린다.
