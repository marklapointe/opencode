# Mapping Group 096
Files: 14

## File Tree
**packages/plugin/src/**
  - `example-workspace.ts` → FolderWorkspacePlugin (34 ln)  [typescript]
    → Imports: @opencode-ai/plugin
  - `example.ts` → ExamplePlugin (18 ln)  [typescript]
    → Imports: ./index.js
  - `index.ts` → Rule (333 ln)  [typescript]
    → Imports: @opencode-ai/sdk
  - `shell.ts` →  (136 ln)  [typescript]
    → Perform bash-like brace expansion on the given pattern. @param pattern - Brace pattern to expand /
  - `tool.ts` → tool (41 ln)  [typescript]
    → Current project directory for this session. Prefer this over process.cwd() when resolving relative paths. /
  - `tui.ts` → TuiConfigView (501 ln)  [typescript]
    → Imports: @opencode-ai/sdk/v2

**packages/script/src/**
  - `index.ts` → Script (77 ln)  [typescript]
    → Imports: bun

**packages/sdk/js/**
  - `client.ts` → createOpencodeClient + type Config as OpencodeClientConfig, OpencodeClient (55 ln)  [typescript]
    → Imports: ./gen/client/client.gen.js

**packages/storybook/sst-env.d.ts/**
  - `sst-env.d.ts` →  (10 ln)  [typescript]

**packages/ui/script/**
  - `tailwind.ts` →  (23 ln)  [typescript]
    → const colors = await Bun.file(import.meta.dir + "/colors.txt").text()

**packages/ui/src/**
  - `custom-elements.d.ts` →  (17 ln)  [typescript]
    → TypeScript declaration for the <diffs-container> custom element. This tells TypeScript that <diffs-container> is a valid JSX element in SolidJS. Requi

**packages/ui/sst-env.d.ts/**
  - `sst-env.d.ts` →  (10 ln)  [typescript]

**packages/ui/vite.config.ts/**
  - `vite.config.ts` →  (59 ln)  [typescript]
    → Imports: vite

**packages/web/sst-env.d.ts/**
  - `sst-env.d.ts` →  (10 ln)  [typescript]

---
Generated: 2026-05-03 15:01:00
