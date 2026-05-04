# Mapping Group 041
Files: 14

**packages/console/core/**
- `aws.ts` →  (65 ln)  [typescript]
  → Imports: zod
  → imports: zod, @opencode-ai/console-resource, aws4fetch
- `billing.ts` →  (556 ln)  [typescript]
  → Imports: stripe
  → imports: stripe, ./drizzle, ./schema/billing.sql
- `black.ts` →  (40 ln)  [typescript]
  → Imports: zod
  → imports: zod, ./util/fn, @opencode-ai/console-resource
- `context.ts` →  (21 ln)  [typescript]
  → Imports: node:async_hooks
  → imports: node:async_hooks
- `index.ts` →  (85 ln)  [typescript]
  → Imports: drizzle-orm/planetscale-serverless
  → imports: drizzle-orm/planetscale-serverless, @opencode-ai/console-resource, @planetscale/database
- `types.ts` → ulid (33 ln)  [typescript]
  → Imports: drizzle-orm
  → imports: drizzle-orm, drizzle-orm/mysql-core
- `identifier.ts` →  (32 ln)  [typescript]
  → Imports: ulid
  → imports: ulid, zod
- `key.ts` →  (92 ln)  [typescript]
  → Imports: zod
  → imports: zod, ./util/fn, ./actor
- `lite.ts` →  (20 ln)  [typescript]
  → Imports: zod
  → imports: zod, ./util/fn, @opencode-ai/console-resource
- `model.ts` →  (228 ln)  [typescript]
  → Imports: zod
  → imports: zod, drizzle-orm, ./drizzle
- `provider.ts` →  (57 ln)  [typescript]
  → Imports: zod
  → imports: zod, ./util/fn, ./actor
- `account.sql.ts` → AccountTable (11 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types
- `auth.sql.ts` → AuthProvider (20 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types
- `benchmark.sql.ts` → BenchmarkTable (14 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types

---
Generated: 2026-05-04 02:45:04Z
