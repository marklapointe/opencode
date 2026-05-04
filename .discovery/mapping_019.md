# Mapping Group 019
Files: 14

**packages/app/src/**
- `persist.test.ts` →  (167 ln)  [test]
- `persist.ts` → removePersisted (611 ln)  [typescript]
  → Imports: @/context/platform
  → imports: @/context/platform, @solid-primitives/storage, @opencode-ai/core/util/encode
- `prompt.test.ts` →  (44 ln)  [test]
- `prompt.ts` → extractPromptFromParts (203 ln)  [typescript]
  → Extract prompt content from message parts for restoring into the prompt input. This is used by undo to restore the original user prompt. /
  → imports: @opencode-ai/sdk/v2, @/context/prompt
- `runtime-adapters.test.ts` →  (64 ln)  [test]
- `runtime-adapters.ts` → isDisposable (39 ln)  [typescript]
  → const isRecord = (value: unknown): value is RecordValue => {
- `same.ts` → same (6 ln)  [typescript]
  → export function same<T>(a: readonly T[] | undefined, b: readonly T[] | undefined) {
- `scoped-cache.test.ts` →  (69 ln)  [test]
- `scoped-cache.ts` → createScopedCache (104 ln)  [typescript]
  → dispose?: (value: T, key: string) => void
- `server-errors.test.ts` →  (131 ln)  [test]
- `server-errors.ts` → formatServerError (80 ln)  [typescript]
- `server-health.test.ts` →  (123 ln)  [test]
- `server-health.ts` → checkServerHealth (113 ln)  [typescript]
  → Imports: @/context/platform
  → imports: @/context/platform, @/context/server, ./server
- `server.ts` → createSdkForServer (25 ln)  [typescript]
  → Imports: @opencode-ai/sdk/v2/client
  → imports: @opencode-ai/sdk/v2/client, @/context/server

---
Generated: 2026-05-04 02:45:04Z
