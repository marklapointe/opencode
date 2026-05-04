# Mapping Group 076
Files: 14

**packages/opencode/src/**
- `win32.ts` → win32DisableProcessedInput (130 ln)  [typescript]
  → Clear ENABLE_PROCESSED_INPUT on the console stdin handle. /
  → imports: bun:ffi, node:tty
- `worker.ts` → rpc (104 ln)  [typescript]
  → Imports: @/installation
  → imports: @/installation, @/server/server, @/project/instance
- `uninstall.ts` → UninstallCommand (353 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, ../ui, ../../installation
- `upgrade.ts` → UpgradeCommand (74 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, ../ui, ../../installation
- `web.ts` → WebCommand (81 ln)  [typescript]
  → Imports: ../../server/server
  → imports: ../../server/server, ../ui, ./cmd
- `prompt.ts` → intro (25 ln)  [typescript]
  → Imports: effect
  → imports: effect
- `error.ts` → FormatError (82 ln)  [typescript]
  → Imports: @opencode-ai/core/util/error
  → imports: @opencode-ai/core/util/error, @/util/error
- `heap.ts` → start (59 ln)  [typescript]
  → Imports: path
  → imports: path, node:v8, @opencode-ai/core/flag/flag
- `logo.ts` → logo (11 ln)  [typescript]
  → export const logo = {
- `network.ts` → withNetworkOptions (62 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, @/config/config, @/effect/app-runtime
- `ui.ts` → println (133 ln)  [typescript]
  → Imports: zod
  → imports: zod, os, @opencode-ai/core/util/error
- `upgrade.ts` → upgrade (33 ln)  [typescript]
  → Imports: @/bus
  → imports: @/bus, @/config/config, @/effect/app-runtime
- `index.ts` → hints (187 ln)  [typescript]
  → Imports: @/bus/bus-event
  → imports: @/bus/bus-event, @/effect/instance-state, @/effect/bridge
- `agent.ts` →  (175 ln)  [config]

---
Generated: 2026-05-04 02:45:04Z
