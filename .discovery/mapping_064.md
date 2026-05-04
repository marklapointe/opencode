# Mapping Group 064
Files: 14

**packages/opencode/src/**
- `acp.ts` → AcpCommand (70 ln)  [typescript]
  → Imports: ../bootstrap
  → imports: ../bootstrap, ./cmd, @agentclientprotocol/sdk
- `agent.ts` → AgentCommand (264 ln)  [typescript]
  → Imports: ./cmd
  → imports: ./cmd, @/effect/app-runtime, ../ui
- `cmd.ts` → cmd (7 ln)  [typescript]
  → Imports: yargs
  → imports: yargs
- `db.ts` → DbCommand (120 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, child_process, @/storage/db
- `agent.ts` → AgentCommand (192 ln)  [typescript]
  → Imports: os
  → imports: os, path, effect
- `config.ts` →  (17 ln)  [config]
- `file.ts` → FileCommand (100 ln)  [typescript]
  → Imports: os
  → imports: os, @/effect/app-runtime, ../../../file
- `index.ts` → DebugCommand (50 ln)  [typescript]
  → Imports: @opencode-ai/core/global
  → imports: @opencode-ai/core/global, ../../bootstrap, ../cmd
- `lsp.ts` → LSPCommand (60 ln)  [typescript]
  → Imports: @/lsp/lsp
  → imports: @/lsp/lsp, ../../../effect/app-runtime, effect
- `ripgrep.ts` → RipgrepCommand (105 ln)  [typescript]
  → Imports: os
  → imports: os, effect, ../../../effect/app-runtime
- `scrap.ts` → ScrapCommand (16 ln)  [typescript]
  → Imports: os
  → imports: os, @/project/project, ../cmd
- `skill.ts` → SkillCommand (23 ln)  [typescript]
  → Imports: os
  → imports: os, effect, @/effect/app-runtime
- `snapshot.ts` → SnapshotCommand (53 ln)  [typescript]
  → Imports: @/effect/app-runtime
  → imports: @/effect/app-runtime, ../../../snapshot, ../../bootstrap
- `startup.ts` → StartupCommand (11 ln)  [typescript]
  → Imports: os
  → imports: os, ../cmd

---
Generated: 2026-05-04 02:45:04Z
