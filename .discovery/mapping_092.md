# Mapping Group 092
Files: 14

**packages/opencode/src/**
- `projectors.ts` → toPartialRow (139 ln)  [typescript]
  → Imports: @/storage/storage
  → imports: @/storage/storage, drizzle-orm, drizzle-orm
- `prompt.ts` → createStructuredOutputTool (1784 ln)  [typescript]
  → Imports: path
  → imports: path, os, zod
- `retry.ts` → delay (125 ln)  [typescript]
  → Imports: @opencode-ai/core/util/error
  → imports: @opencode-ai/core/util/error, effect, ./message-v2
- `revert.ts` → RevertInput (164 ln)  [typescript]
  → Imports: effect
  → imports: effect, ../bus, ../snapshot
- `run-state.ts` → layer (110 ln)  [typescript]
  → Imports: @/effect/instance-state
  → imports: @/effect/instance-state, @/effect/runner, effect
- `schema.ts` → SessionID (35 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/id/id, @/util/effect-zod
- `session.sql.ts` → SessionTable (124 ln)  [typescript]
  → Imports: drizzle-orm/sqlite-core
  → imports: drizzle-orm/sqlite-core, ../project/project.sql, ./message-v2
- `session.ts` → isDefaultTitle (902 ln)  [typescript]
  → Imports: @opencode-ai/core/util/slug
  → imports: @opencode-ai/core/util/slug, path, @/bus/bus-event
- `status.ts` → Info (88 ln)  [typescript]
  → Imports: @/bus/bus-event
  → imports: @/bus/bus-event, @/bus, @/effect/instance-state
- `summary.ts` → layer (165 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/bus, @/snapshot
- `system.ts` → provider (84 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/effect/instance-state, ./prompt/anthropic.txt
- `todo.ts` → Info (86 ln)  [typescript]
  → Imports: @/bus/bus-event
  → imports: @/bus/bus-event, @/bus, ./schema
- `session.ts` → layer (59 ln)  [typescript]
  → Imports: @/session/session
  → imports: @/session/session, @/session/schema, @/sync
- `share-next.ts` → layer (376 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect/unstable/http, @/account/account

---
Generated: 2026-05-04 02:45:04Z
