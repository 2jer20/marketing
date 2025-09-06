# VibeMarketer (MVP)

Your AI Marketing Co-Founder.

## Setup

1. Install dependencies:

```bash
npm install
```

2. Copy env and fill values:

```bash
cp .env.example .env.local
```

3. Setup database and generate Prisma client:

```bash
npx prisma db push
```

4. Run dev server:

```bash
npm run dev
```

## Tech
- Next.js 14 (App Router), Tailwind, TypeScript
- NextAuth (Google), Prisma (Postgres/Neon)
- TanStack Query, Zod, RHF
- OpenAI (optional) 