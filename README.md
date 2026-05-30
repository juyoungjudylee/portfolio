# 이주영 HR Portfolio — Hexo + GitHub Pages

이 저장소는 Hexo 기반 GitHub Pages 포트폴리오입니다.

## 로컬 실행

```bash
npm install
npm run server
```

브라우저에서 `http://localhost:4000/portfolio/` 또는 안내되는 로컬 주소를 확인하세요.

## 배포

GitHub 저장소의 `Settings > Pages`에서 Source를 `GitHub Actions`로 설정한 뒤,
`main` 브랜치에 push하면 `.github/workflows/pages.yml`이 자동으로 사이트를 빌드하고 배포합니다.

배포 주소:

```text
https://juyoungjudylee.github.io/portfolio/
```

## 수정 위치

메인 포트폴리오 HTML:

```text
themes/juyoung/layout/index.ejs
```

사이트 설정:

```text
_config.yml
```
