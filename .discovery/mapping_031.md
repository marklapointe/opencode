# Mapping Group 031
Files: 14

## File Tree
**packages/console/core/**
  - `user.ts` →  (226 ln)  [typescript]
    → Imports: zod
  - `date.ts` → getWeekBounds (38 ln)  [typescript]
    → export function getWeekBounds(date: Date) {
  - `env.cloudflare.ts` →  (1 ln)  [typescript]
  - `fn.ts` → fn (11 ln)  [typescript]
    → Imports: zod
  - `log.ts` →  (55 ln)  [typescript]
    → Imports: ../context
  - `memo.ts` → memo (18 ln)  [typescript]
    → export function memo<T>(fn: () => T, cleanup?: (input: T) => Promise<void>) {
  - `price.ts` → centsToMicroCents (7 ln)  [typescript]
    → export function centsToMicroCents(amount: number) {
  - `workspace.ts` →  (76 ln)  [typescript]
    → Imports: zod

**packages/containers/script/**
  - `build.ts` →  (77 ln)  [typescript]
    → Imports: bun

**packages/core/src/**
  - `cross-spawn-spawner.ts` → make (505 ln)  [typescript]
    → Imports: @effect/platform-node
  - `logger.ts` → logger (73 ln)  [typescript]
    → Imports: effect
  - `memo-map.ts` → memoMap (3 ln)  [typescript]
    → Imports: effect
  - `observability.ts` → resource (107 ln)  [typescript]
    → Imports: effect
  - `runtime.ts` → makeRuntime (21 ln)  [typescript]
    → Imports: effect

---
Generated: 2026-05-03 15:01:00
