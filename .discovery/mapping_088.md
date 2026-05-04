# Mapping Group 088
Files: 14

**packages/opencode/src/**
- `mcp.ts` → AddPayload (145 ln)  [typescript]
  → Imports: @/mcp
  → imports: @/mcp, @/config/mcp, effect
- `metadata.ts` → described (18 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect/unstable/httpapi
- `permission.ts` → PermissionApi (58 ln)  [typescript]
  → Imports: @/permission
  → imports: @/permission, @/permission/schema, effect
- `project.ts` → ProjectApi (77 ln)  [typescript]
  → Imports: @/project/project
  → imports: @/project/project, @/project/schema, effect
- `provider.ts` → ProviderApi (76 ln)  [typescript]
  → Imports: @/provider/auth
  → imports: @/provider/auth, @/provider/provider, @/provider/schema
- `pty.ts` → Params (127 ln)  [typescript]
  → Imports: @/pty
  → imports: @/pty, @/pty/schema, effect
- `question.ts` → QuestionApi (70 ln)  [typescript]
  → Imports: @/question
  → imports: @/question, @/question/schema, effect
- `session.ts` → ListQuery (429 ln)  [typescript]
  → Imports: @/permission
  → imports: @/permission, @/permission/schema, @/provider/schema
- `sync.ts` → ReplayEvent (92 ln)  [typescript]
  → Imports: @/util/schema
  → imports: @/util/schema, effect, effect/unstable/httpapi
- `tui.ts` → CommandPayload (197 ln)  [typescript]
  → Imports: @/cli/cmd/tui/event
  → imports: @/cli/cmd/tui/event, effect, effect/unstable/httpapi
- `workspace.ts` → CreatePayload (103 ln)  [typescript]
  → Imports: @/control-plane/workspace
  → imports: @/control-plane/workspace, @/control-plane/types, @/util/schema
- `config.ts` →  (34 ln)  [config]
- `control.ts` → controlHandlers (34 ln)  [typescript]
  → Imports: @/auth
  → imports: @/auth, @/provider/schema, effect
- `experimental.ts` → experimentalHandlers (155 ln)  [typescript]
  → Imports: @/account/account
  → imports: @/account/account, @/agent/agent, @/config/config

---
Generated: 2026-05-04 02:45:04Z
