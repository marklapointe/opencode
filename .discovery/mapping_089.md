# Mapping Group 089
Files: 14

**packages/opencode/src/**
- `file.ts` → fileHandlers (54 ln)  [typescript]
  → Imports: @/file
  → imports: @/file, @/file/ripgrep, effect
- `global.ts` → globalHandlers (156 ln)  [typescript]
  → Imports: @/config/config
  → imports: @/config/config, @/bus/global, @/installation
- `instance.ts` → instanceHandlers (79 ln)  [typescript]
  → Imports: @/agent/agent
  → imports: @/agent/agent, @/command, @/format
- `mcp.ts` → mcpHandlers (68 ln)  [typescript]
  → Imports: @/mcp
  → imports: @/mcp, effect, effect/unstable/httpapi
- `permission.ts` → permissionHandlers (29 ln)  [typescript]
  → Imports: @/permission
  → imports: @/permission, @/permission/schema, effect
- `project.ts` → projectHandlers (46 ln)  [typescript]
  → Imports: @/effect/app-runtime
  → imports: @/effect/app-runtime, @/project/bootstrap, @/project/project
- `provider.ts` → providerHandlers (89 ln)  [typescript]
  → Imports: @/provider/auth
  → imports: @/provider/auth, @/config/config, @/provider/models
- `pty.ts` → ptyHandlers (121 ln)  [typescript]
  → Imports: @/pty
  → imports: @/pty, @/pty/schema, @/pty/input
- `question.ts` → questionHandlers (33 ln)  [typescript]
  → Imports: @/question
  → imports: @/question, @/question/schema, effect
- `session.ts` → sessionHandlers (388 ln)  [typescript]
  → Imports: @/effect/instance-ref
  → imports: @/effect/instance-ref, @/agent/agent, @/bus
- `sync.ts` → syncHandlers (77 ln)  [typescript]
  → Imports: @/control-plane/workspace
  → imports: @/control-plane/workspace, @/storage/db, @/sync
- `tui.ts` → tuiHandlers (135 ln)  [typescript]
  → Imports: @/bus
  → imports: @/bus, @/cli/cmd/tui/event, @/session/session.sql
- `workspace.ts` → workspaceHandlers (61 ln)  [typescript]
  → Imports: @/control-plane/adapters
  → imports: @/control-plane/adapters, @/control-plane/workspace, effect
- `lifecycle.ts` → markInstanceForDisposal (63 ln)  [typescript]
  → Imports: @/control-plane/schema
  → imports: @/control-plane/schema, @/control-plane/workspace-context, @/effect/instance-ref

---
Generated: 2026-05-04 02:45:04Z
