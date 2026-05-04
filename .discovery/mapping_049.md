# Mapping Group 049
Files: 14

**packages/desktop-electron/scripts/**
- `predev.ts` →  (5 ln)  [typescript]
  → Imports: bun
  → imports: bun
- `prepare.ts` →  (9 ln)  [typescript]
  → Imports: @opencode-ai/script
  → imports: @opencode-ai/script
- `utils.ts` → resolveChannel (77 ln)  [typescript]
  → Imports: bun
  → imports: bun

**packages/desktop-electron/src/**
- `apps.ts` → checkAppExists (148 ln)  [typescript]
  → Imports: node:child_process
  → imports: node:child_process, node:fs, node:path
- `constants.ts` → CHANNEL (10 ln)  [typescript]
  → Imports: electron
  → imports: electron
- `env.d.ts` →  (29 ln)  [typescript]
  → export const listen: typeof import("../../../opencode/dist/types/src/node").Server.listen
- `index.ts` →  (452 ln)  [typescript]
  → Imports: node:crypto
  → imports: node:crypto, node:events, node:fs
- `ipc.ts` → registerIpcHandlers (204 ln)  [typescript]
  → Imports: node:child_process
  → imports: node:child_process, electron, electron
- `logging.ts` → initLogging (40 ln)  [typescript]
  → Imports: electron-log/main.js
  → imports: electron-log/main.js, node:fs, node:path
- `markdown.ts` → parseMarkdown (16 ln)  [typescript]
  → Imports: marked
  → imports: marked
- `menu.ts` → createMenu (136 ln)  [typescript]
  → Imports: electron
  → imports: electron, ./constants, ./windows
- `migrate.ts` → migrate (91 ln)  [typescript]
  → Imports: electron
  → imports: electron, electron-log/main.js, node:fs
- `server.ts` → getDefaultServerUrl (101 ln)  [typescript]
  → Imports: electron
  → imports: electron, ./constants, ./shell-env
- `shell-env.test.ts` →  (43 ln)  [test]

---
Generated: 2026-05-04 02:45:04Z
