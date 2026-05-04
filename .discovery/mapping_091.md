# Mapping Group 091
Files: 14

**packages/opencode/src/**
- `session.ts` → SessionRoutes (1124 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono/streaming, hono-openapi
- `sync.ts` → SyncRoutes (152 ln)  [typescript]
  → Imports: zod
  → imports: zod, hono, hono-openapi
- `trace.ts` → paramToAttributeKey (59 ln)  [typescript]
  → Imports: hono
  → imports: hono, effect, @/effect/app-runtime
- `tui.ts` → nextTuiRequest (399 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono-openapi, effect
- `ui.ts` → serveUI (127 ln)  [typescript]
  → Imports: @opencode-ai/core/flag/flag
  → imports: @opencode-ai/core/flag/flag, @opencode-ai/core/filesystem, effect
- `server.ts` → Legacy (195 ln)  [typescript]
  → Imports: hono-openapi
  → imports: hono-openapi, hono, #hono
- `workspace.ts` → isLocalWorkspaceRoute (130 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono/ws, @/control-plane/adapters
- `compaction.ts` → isOverflow (630 ln)  [typescript]
  → Imports: @/bus/bus-event
  → imports: @/bus/bus-event, @/bus, ./schema
- `instruction.ts` → loaded (232 ln)  [typescript]
  → Imports: path
  → imports: path, effect, effect/unstable/http
- `llm.ts` → hasToolCalls (469 ln)  [typescript]
  → Imports: @/provider/provider
  → imports: @/provider/provider, effect, ai
- `message-v2.ts` → toModelMessages (1221 ln)  [typescript]
  → Imports: @/bus/bus-event
  → imports: @/bus/bus-event, ./schema, zod
- `message.ts` → OutputLengthError (192 ln)  [typescript]
  → Imports: effect
  → imports: effect, ./schema, ../provider/schema
- `overflow.ts` → usable (26 ln)  [typescript]
  → Imports: @/config/config
  → imports: @/config/config, @/provider/provider, @/provider/transform
- `processor.ts` → layer (619 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/agent/agent, @/bus

---
Generated: 2026-05-04 02:45:04Z
