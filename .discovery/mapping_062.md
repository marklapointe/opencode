# Mapping Group 062
Files: 14

**packages/opencode/specs/**
- `instance-context.md` →  (309 ln)  [docs]
- `loose-ends.md` →  (34 ln)  [docs]
- `migration.md` →  (299 ln)  [docs]
- `routes.md` →  (64 ln)  [docs]
- `schema.md` →  (399 ln)  [docs]
- `server-package.md` →  (668 ln)  [docs]
- `tools.md` →  (90 ln)  [docs]
- `tui-plugins.md` →  (433 ln)  [docs]
- `api.ts` →  (67 ln)  [typescript]
  → Imports: @opencode-ai/core
  → imports: @opencode-ai/core, @opencode-ai/core/tools
- `keymappings.md` →  (10 ln)  [docs]
- `message-shape.md` →  (136 ln)  [docs]

**packages/opencode/src/**
- `account.sql.ts` → AccountTable (39 ln)  [typescript]
  → Imports: drizzle-orm/sqlite-core
  → imports: drizzle-orm/sqlite-core, ./schema, ../storage/schema.sql
- `account.ts` → layer (456 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect/unstable/http, @/util/effect-http-client
- `repo.ts` → layer (166 ln)  [typescript]
  → Imports: drizzle-orm
  → imports: drizzle-orm, effect, @/storage/db

---
Generated: 2026-05-04 02:45:04Z
