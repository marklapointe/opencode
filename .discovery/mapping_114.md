# Mapping Group 114
Files: 14

**packages/opencode/test/**
- `process.test.ts` →  (128 ln)  [test]
- `timeout.test.ts` →  (21 ln)  [test]
- `which.test.ts` →  (100 ln)  [test]
- `wildcard.test.ts` →  (90 ln)  [test]

**packages/opencode/tsconfig.json/**
- `tsconfig.json` →  (17 ln)  [config]

**packages/plugin/.gitignore/**
- `.gitignore` →  (1 ln)  [file]

**packages/plugin/package.json/**
- `package.json` →  (44 ln)  [json]

**packages/plugin/script/**
- `publish.ts` →  (38 ln)  [typescript]
  → Imports: @opencode-ai/script
  → imports: @opencode-ai/script, bun, url

**packages/plugin/src/**
- `example-workspace.ts` → FolderWorkspacePlugin (34 ln)  [typescript]
  → Imports: @opencode-ai/plugin
  → imports: @opencode-ai/plugin, node:fs/promises
- `example.ts` → ExamplePlugin (18 ln)  [typescript]
  → Imports: ./index.js
  → imports: ./index.js, ./tool.js
- `index.ts` →  (333 ln)  [typescript]
  → Imports: @opencode-ai/sdk
  → imports: @opencode-ai/sdk, @opencode-ai/sdk/v2, ./shell.js
- `shell.ts` →  (136 ln)  [typescript]
  → Perform bash-like brace expansion on the given pattern. @param pattern - Brace pattern to expand /
- `tool.ts` → tool (41 ln)  [typescript]
  → Current project directory for this session. Prefer this over process.cwd() when resolving relative paths. /
  → imports: zod, effect
- `tui.ts` →  (501 ln)  [typescript]
  → Imports: @opencode-ai/sdk/v2
  → imports: @opencode-ai/sdk/v2, @opentui/core, @opentui/solid

---
Generated: 2026-05-04 02:45:04Z
