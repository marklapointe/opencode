# Mapping Group 020
Files: 14

**packages/app/src/**
- `session-title.ts` → sessionTitle (7 ln)  [typescript]
  → const pattern = /^(New session|Child session) - \d{4}-\d{2}-\d{2}T\d{2}:\d{2}:\d{2}\.\d{3}Z$/
- `solid-dnd.tsx` → getDraggableId (49 ln)  [typescript]
  → Imports: @thisbeyond/solid-dnd
  → imports: @thisbeyond/solid-dnd, @thisbeyond/solid-dnd, solid-js
- `sound.ts` → soundSrc (102 ln)  [typescript]
  → let files: Record<string, () => Promise<string>> | undefined
- `terminal-writer.test.ts` →  (64 ln)  [test]
- `terminal-writer.ts` → terminalWriter (65 ln)  [typescript]
  → export function terminalWriter(
- `time.ts` → getRelativeTime (22 ln)  [typescript]
  → type Translate = (key: TimeKey, params?: Record<string, string | number>) => string
- `uuid.test.ts` →  (78 ln)  [test]
- `uuid.ts` → uuid (12 ln)  [typescript]
  → const fallback = () => Math.random().toString(16).slice(2)
- `worktree.test.ts` →  (46 ln)  [test]
- `worktree.ts` → Worktree (73 ln)  [typescript]
  → const normalize = (directory: string) => directory.replace(/[\\/]+$/, "")

**packages/app/sst-env.d.ts/**
- `sst-env.d.ts` →  (10 ln)  [typescript]
  → Imports: sst
  → imports: sst

**packages/app/tsconfig.json/**
- `tsconfig.json` →  (26 ln)  [config]

**packages/app/vite.config.ts/**
- `vite.config.ts` →  (33 ln)  [config]

**packages/app/vite.js/**
- `vite.js` →  (38 ln)  [javascript]
  → @type {import("vite").PluginOption} /
  → imports: node:fs, vite-plugin-solid, @tailwindcss/vite

---
Generated: 2026-05-04 02:45:04Z
