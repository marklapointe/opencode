# Mapping Group 065
Files: 14

**packages/opencode/src/**
- `export.ts` → ExportCommand (303 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, @/session/session, ../../session/message-v2
- `generate.ts` → GenerateCommand (61 ln)  [typescript]
  → Imports: ../../server/server
  → imports: ../../server/server, ../../server/routes/instance/httpapi/public, yargs
- `github.ts` → parseGitHubRemote (1649 ln)  [typescript]
  → Extracts displayable text from assistant response parts. Returns null for non-text responses (signals summary needed). Throws only for truly empty responses.
  → imports: path, child_process, @/util/filesystem
- `import.ts` → parseShareUrl (212 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, @opencode-ai/sdk/v2, @/session/session
- `mcp.ts` → McpCommand (798 ln)  [typescript]
  → Imports: ./cmd
  → imports: ./cmd, @modelcontextprotocol/sdk/client/index.js, @modelcontextprotocol/sdk/client/streamableHttp.js
- `models.ts` → ModelsCommand (88 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, ../../project/instance, @/provider/provider
- `plug.ts` → createPlugTask (233 ln)  [typescript]
  → Imports: @clack/prompts
  → imports: @clack/prompts, yargs, @/config/paths
- `pr.ts` → PrCommand (138 ln)  [typescript]
  → Imports: ../ui
  → imports: ../ui, ./cmd, @/effect/app-runtime
- `providers.ts` → resolvePluginProviders (526 ln)  [typescript]
  → Imports: ../../auth
  → imports: ../../auth, ../../effect/app-runtime, ./cmd
- `run.ts` → RunCommand (672 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, path, url
- `serve.ts` → ServeCommand (21 ln)  [typescript]
  → Imports: ../../server/server
  → imports: ../../server/server, ./cmd, ../network
- `session.ts` → SessionCommand (162 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, ./cmd, @/session/session
- `stats.ts` → aggregateSessionStats (413 ln)  [typescript]
  → Imports: yargs
  → imports: yargs, ./cmd, @/session/session
- `app.tsx` → tui (909 ln)  [typescript]
  → Imports: @opentui/solid
  → imports: @opentui/solid, @opentui/core, @tui/context/route

---
Generated: 2026-05-04 02:45:04Z
