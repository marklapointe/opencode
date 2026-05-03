# Mapping Group 088
Files: 14

## File Tree
**packages/opencode/src/**
  - `sql.d.ts` →  (4 ln)  [typescript]
    → const content: string
  - `event.sql.ts` → EventSequenceTable (16 ln)  [typescript]
    → Imports: drizzle-orm/sqlite-core
  - `index.ts` → reset (387 ln)  [typescript]
    → Imports: zod
  - `schema.ts` → EventID (13 ln)  [typescript]
    → Imports: effect
  - `temporary.ts` →  (33 ln)  [typescript]
    → Imports: yargs
  - `session-entry-stepper.ts` → memory (261 ln)  [typescript]
    → Imports: immer
  - `session-entry.ts` → ID (220 ln)  [typescript]
    → Imports: effect
  - `session-event.ts` →  (458 ln)  [typescript]
    → Imports: @/id/id
  - `session.ts` → ID (69 ln)  [typescript]
    → Imports: effect

**packages/opencode/sst-env.d.ts/**
  - `sst-env.d.ts` →  (10 ln)  [typescript]

**packages/opencode/test/**
  - `repo.test.ts` →  (352 ln)  [typescript]
    → Imports: bun:test
  - `service.test.ts` →  (456 ln)  [typescript]
    → Imports: bun:test
  - `agent-interface.test.ts` → _AssertAgentImplementsACPAgent (51 ln)  [typescript]
    → Type-level test: This line will fail to compile if ACP.Agent doesn't properly implement the ACPAgent interface.
  - `event-subscription.test.ts` → SessionUpdateParams (725 ln)  [typescript]
    → Imports: bun:test

---
Generated: 2026-05-03 15:01:00
