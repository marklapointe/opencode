# Mapping Group 079
Files: 14

**packages/opencode/src/**
- `workspace-context.ts` → WorkspaceContext (26 ln)  [typescript]
  → Imports: @/util/local-context
  → imports: @/util/local-context, ../control-plane/schema
- `workspace.sql.ts` → WorkspaceTable (17 ln)  [typescript]
  → Imports: drizzle-orm/sqlite-core
  → imports: drizzle-orm/sqlite-core, ../project/project.sql, ../project/schema
- `workspace.ts` → Info (875 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect/unstable/http, @/storage/db
- `app-runtime.ts` → AppLayer (125 ln)  [typescript]
  → Imports: effect
  → imports: effect, ./run-service, @opencode-ai/core/filesystem
- `bootstrap-runtime.ts` → BootstrapLayer (29 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/plugin, @/lsp/lsp
- `bridge.ts` → make (59 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/control-plane/workspace-context, @/project/instance
- `config-service.ts` →  (67 ln)  [config]
- `instance-ref.ts` → InstanceRef (11 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/project/instance, @/control-plane/schema
- `instance-registry.ts` → registerDisposer (12 ln)  [typescript]
  → const disposers = new Set<(directory: string) => Promise<void>>()
- `instance-state.ts` → bind (83 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/project/instance, @/util/local-context
- `run-service.ts` → attachWith (52 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/project/instance, @/util/local-context
- `runner.ts` → make (222 ln)  [typescript]
  → Imports: effect
  → imports: effect
- `service-use.ts` → serviceUse (38 ln)  [typescript]
  → Imports: effect
  → imports: effect
- `index.ts` → layer (37 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/effect/instance-state

---
Generated: 2026-05-04 02:45:04Z
