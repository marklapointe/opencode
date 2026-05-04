# Mapping Group 086
Files: 14

**packages/opencode/src/**
- `adapter.node.ts` → adapter (73 ln)  [typescript]
  → Imports: @hono/node-server
  → imports: @hono/node-server, @hono/node-ws, hono
- `adapter.ts` →  (26 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono/ws
- `backend.ts` → select (32 ln)  [typescript]
  → Imports: @opencode-ai/core/flag/flag
  → imports: @opencode-ai/core/flag/flag, @opencode-ai/core/installation/version
- `cors.ts` → isAllowedCorsOrigin (14 ln)  [typescript]
  → const opencodeOrigin = /^https:\/\/([a-z0-9-]+\.)*opencode\.ai$/
- `error.ts` → errors (36 ln)  [typescript]
  → Imports: hono-openapi
  → imports: hono-openapi, zod, @/storage/storage
- `event.ts` → Event (7 ln)  [typescript]
  → Imports: @/bus/bus-event
  → imports: @/bus/bus-event, effect
- `fence.ts` → load (90 ln)  [typescript]
  → Imports: hono
  → imports: hono, @/storage/db, drizzle-orm
- `mdns.ts` → publish (60 ln)  [typescript]
  → Imports: bonjour-service
  → imports: bonjour-service
- `middleware.ts` → LoggerMiddleware (86 ln)  [typescript]
  → Imports: @/provider/provider
  → imports: @/provider/provider, @opencode-ai/core/util/error, @/storage/storage
- `projectors.ts` → initProjectors (28 ln)  [typescript]
  → Imports: ../session/projectors
  → imports: ../session/projectors, @/sync, @/session/session
- `proxy-util.ts` → headers (48 ln)  [typescript]
  → const hop = new Set([
- `proxy.ts` → httpEffect (149 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono/ws, @/control-plane/schema
- `index.ts` → ControlPlaneRoutes (160 ln)  [typescript]
  → Imports: @/auth
  → imports: @/auth, @/effect/app-runtime, effect
- `workspace.ts` → WorkspaceRoutes (210 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono-openapi, zod

---
Generated: 2026-05-04 02:45:04Z
