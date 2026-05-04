# Mapping Group 078
Files: 14

**packages/opencode/src/**
- `paths.ts` →  (55 ln)  [config]
- `permission.ts` →  (70 ln)  [config]
- `plugin.ts` →  (88 ln)  [config]
- `provider.ts` →  (113 ln)  [config]
- `server.ts` →  (22 ln)  [config]
- `skills.ts` →  (16 ln)  [config]
- `variable.ts` →  (90 ln)  [config]
- `index.ts` → getAdapter (45 ln)  [typescript]
  → Imports: @/project/schema
  → imports: @/project/schema, ../types, ./worktree
- `worktree.ts` → WorktreeAdapter (54 ln)  [typescript]
  → Imports: effect
  → imports: effect, ../types
- `README.md` →  (19 ln)  [docs]
- `debug-workspace-plugin.ts` → DebugWorkspacePlugin (73 ln)  [typescript]
  → Imports: @opencode-ai/plugin
  → imports: @opencode-ai/plugin, node:fs/promises, node:crypto
- `schema.ts` → WorkspaceID (18 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/id/id, @/util/effect-zod
- `types.ts` → WorkspaceInfo (45 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/project/schema, ./schema
- `util.ts` → waitEvent (39 ln)  [typescript]
  → Imports: @/bus/global
  → imports: @/bus/global, effect

---
Generated: 2026-05-04 02:45:04Z
