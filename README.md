# BlackScooter Portfolio

개인 포트폴리오 웹사이트 저장소입니다.  
Astro 기반이며, 주요 콘텐츠는 `cv.json`에서 관리합니다.

## Stack

- Astro
- TypeScript
- Tailwind CSS

## 로컬 실행

```bash
pnpm install
pnpm run dev
```

기본 주소: `http://localhost:4321`

## 빌드

```bash
pnpm run build
```

## 콘텐츠 수정

- 기본 프로필/경력/기술스택: `cv.json`
- 레이아웃/메타 태그: `src/layouts/`
- 섹션 UI: `src/components/sections/`
