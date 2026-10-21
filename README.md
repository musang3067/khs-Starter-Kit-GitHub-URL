# 개인 개발 블로그

Notion을 CMS로 활용한 개인 기술 블로그입니다. Notion 데이터베이스에 글을 작성하면 자동으로 웹 블로그에 반영됩니다.

## 주요 기능

- Notion 데이터베이스 기반 블로그 글 목록/상세 페이지
- 카테고리별 필터링
- 검색 기능
- 반응형 디자인

## 기술 스택

- **Frontend**: Next.js 15, TypeScript
- **CMS**: Notion API (`@notionhq/client`)
- **Styling**: Tailwind CSS, shadcn/ui
- **Icons**: Lucide React
- **Deployment**: Vercel

## 문서

- [PRD](./docs/PRD.md) — 프로젝트 요구사항 정의서

## 시작하기

```bash
npm install
npm run dev
```

`.env.local`에 Notion API 키와 데이터베이스 ID를 설정해야 합니다.
