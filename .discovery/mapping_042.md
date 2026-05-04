# Mapping Group 042
Files: 14

**packages/console/core/**
- `billing.sql.ts` → BlackPlans (145 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types, ./workspace.sql
- `ip.sql.ts` → IpTable (42 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types
- `key.sql.ts` → KeyTable (16 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types, ./workspace.sql
- `model.sql.ts` → ModelTable (13 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types, ./workspace.sql
- `provider.sql.ts` → ProviderTable (14 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types, ./workspace.sql
- `user.sql.ts` → UserRole (29 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types, ./workspace.sql
- `workspace.sql.ts` → workspaceIndexes (21 ln)  [typescript]
  → Imports: drizzle-orm/mysql-core
  → imports: drizzle-orm/mysql-core, ../drizzle/types
- `subscription.ts` →  (153 ln)  [typescript]
  → Imports: zod
  → imports: zod, ./util/fn, ./util/price
- `user.ts` →  (226 ln)  [typescript]
  → Imports: zod
  → imports: zod, drizzle-orm, ./util/fn
- `date.ts` → getWeekBounds (38 ln)  [typescript]
  → export function getWeekBounds(date: Date) {
- `env.cloudflare.ts` →  (1 ln)  [typescript]
- `fn.ts` → fn (11 ln)  [typescript]
  → Imports: zod
  → imports: zod
- `log.ts` →  (55 ln)  [typescript]
  → Imports: ../context
  → imports: ../context
- `memo.ts` → memo (18 ln)  [typescript]
  → export function memo<T>(fn: () => T, cleanup?: (input: T) => Promise<void>) {

---
Generated: 2026-05-04 02:45:04Z
