# Mapping Group 082
Files: 14

**packages/opencode/src/**
- `azure.ts` → AzureAuthPlugin (26 ln)  [typescript]
  → Imports: @opencode-ai/plugin
  → imports: @opencode-ai/plugin
- `cloudflare.ts` → CloudflareWorkersAuthPlugin (76 ln)  [typescript]
  → Imports: @opencode-ai/plugin
  → imports: @opencode-ai/plugin
- `codex.ts` → parseJwtClaims (615 ln)  [typescript]
  → Imports: @opencode-ai/plugin
  → imports: @opencode-ai/plugin, ../installation, @opencode-ai/core/installation/version
- `copilot.ts` → CopilotAuthPlugin (394 ln)  [typescript]
  → Imports: @opencode-ai/plugin
  → imports: @opencode-ai/plugin, @opencode-ai/sdk/v2, @opencode-ai/core/installation/version
- `models.ts` → get (195 ln)  [typescript]
  → Imports: zod
  → imports: zod, @opencode-ai/sdk/v2
- `index.ts` → layer (291 ln)  [typescript]
  → Imports: @opencode-ai/plugin
  → imports: @opencode-ai/plugin, @/config/config, ../bus
- `install.ts` → installPlugin (439 ln)  [typescript]
  → Imports: path
  → imports: path, jsonc-parser, @opencode-ai/core/global
- `loader.ts` →  (216 ln)  [typescript]
  → Imports: ./shared
  → imports: ./shared, @/config/plugin, @opencode-ai/core/installation/version
- `meta.ts` → touchMany (188 ln)  [typescript]
  → Imports: path
  → imports: path, url, @opencode-ai/core/flag/flag
- `shared.ts` → isDeprecatedPlugin (323 ln)  [typescript]
  → Imports: path
  → imports: path, url, npm-package-arg
- `bootstrap.ts` → InstanceBootstrap (44 ln)  [typescript]
  → Imports: ../plugin
  → imports: ../plugin, ../format, @/lsp/lsp
- `instance.ts` → Instance (190 ln)  [typescript]
  → Check if a path is within the project boundary. Returns true if path is inside Instance.directory OR Instance.worktree. Paths within the worktree but outside the working directory should not trigger e
  → imports: @/bus/global, @/effect/instance-registry, @/effect/run-service
- `project.sql.ts` → ProjectTable (17 ln)  [typescript]
  → Imports: drizzle-orm/sqlite-core
  → imports: drizzle-orm/sqlite-core, ../storage/schema.sql, ./schema
- `project.ts` → fromRow (513 ln)  [typescript]
  → Imports: zod
  → imports: zod, drizzle-orm, @/storage/db

---
Generated: 2026-05-04 02:45:04Z
