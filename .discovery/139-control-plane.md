139-control-plane.md

Directory: src/control-plane/

Overview: Control-plane scaffolding for workspace and project orchestration, including workspace contexts, adapters, and utilities.

- workspace.ts, workspace-context.ts, workspace.sql.ts
  - Roles: Manage workspaces, their SQL persistence, adapter wiring, and workspace synchronization
- adapters/index.ts, adapters/worktree.ts
  - Roles: Adapter system that provides per-workspace backend wiring and space handling
- types.ts, schema.ts, util.ts
  - Roles: Shared types and helper utilities used by the control-plane
- dev/ README and debug-workspace-plugin.ts show developer focused guidance and debugging tools

- The module demonstrates a layered DI approach, enabling server to switch between different adapters and workspace management strategies

End of 139-control-plane.md
