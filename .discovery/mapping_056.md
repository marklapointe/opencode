# Mapping Group 056
Files: 14

## File Tree
**packages/opencode/src/**
  - `cors.ts` → isAllowedCorsOrigin (14 ln)  [typescript]
    → const opencodeOrigin = /^https:\/\/([a-z0-9-]+\.)*opencode\.ai$/
  - `error.ts` → errors (36 ln)  [typescript]
    → Imports: hono-openapi
  - `event.ts` → Event (7 ln)  [typescript]
    → Imports: @/bus/bus-event
  - `fence.ts` → load (90 ln)  [typescript]
    → Imports: hono
  - `mdns.ts` → publish (60 ln)  [typescript]
    → Imports: bonjour-service
  - `middleware.ts` → LoggerMiddleware (86 ln)  [typescript]
    → Imports: @/provider/provider
  - `projectors.ts` → initProjectors (28 ln)  [typescript]
    → Imports: ../session/projectors
  - `proxy-util.ts` → headers (48 ln)  [typescript]
    → const hop = new Set([
  - `proxy.ts` → httpEffect (149 ln)  [typescript]
    → Imports: hono
  - `index.ts` → ControlPlaneRoutes (160 ln)  [typescript]
    → Imports: @/auth
  - `workspace.ts` → WorkspaceRoutes (210 ln)  [typescript]
    → Imports: hono
  - `global.ts` → GlobalDisposedEvent (287 ln)  [typescript]
    → Imports: hono
  - `config.ts` → ConfigRoutes (89 ln)  [typescript]
    → Imports: hono
  - `event.ts` → EventRoutes (88 ln)  [typescript]
    → Imports: zod

---
Generated: 2026-05-03 15:01:00
