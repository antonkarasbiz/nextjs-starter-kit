# Next.js starter kit

Production-oriented starter for Next.js (App Router and Pages Router), Tailwind CSS 4, and TypeScript. The kit prioritizes typed data access, auth, testing, and operational defaults so a new product can move from clone to deploy without restitching tooling.

## Overview

This repository is the TypeScript / Next.js foundation in the [antonkarasbiz](https://github.com/antonkarasbiz) full-stack practice. It is suitable for SaaS dashboards, marketing-plus-app hybrids, and AI-assisted product surfaces that need a serious baseline.

## Capabilities

- Next.js with TypeScript and Tailwind CSS 4
- Clerk authentication
- Drizzle ORM for PostgreSQL, SQLite, and MySQL
- Local database via PGlite; production-ready Neon path
- Sentry error monitoring and LogTape logging
- Arcjet bot detection, rate limiting, and attack protection
- Vitest, Testing Library, and Playwright
- Storybook, i18n, ESLint / Prettier / Lefthook / Commitlint
- VS Code defaults aligned with the toolchain

## Scripts

```bash
npm install
npm run dev          # Next.js + local PGlite
npm run build
npm run start
npm test             # Vitest
npm run test:e2e     # Playwright
npm run storybook
npm run db:studio
```

Copy environment examples before the first run. Clerk, database, and monitoring keys stay out of git.

## Project role

Clone, rename, and strip unused integrations. Keep auth, database, and test pipelines unless the product explicitly does not need them.

## License

MIT. Based on the widely used Next.js boilerplate lineage (Ixartz and related tooling). Sponsor and vendor badges from the upstream README are not part of this account’s brand.

## Maintainer

[Anton Karas](https://github.com/antonkarasbiz) — full-stack, blockchain, and AI engineering.
