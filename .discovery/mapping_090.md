# Mapping Group 090
Files: 14

**packages/opencode/src/**
- `authorization.ts` → authorizationRouterMiddleware (128 ln)  [typescript]
  → Imports: @/effect/config-service
  → imports: @/effect/config-service, effect, effect/unstable/http
- `instance-context.ts` → instanceContextLayer (55 ln)  [typescript]
  → Imports: @/effect/instance-ref
  → imports: @/effect/instance-ref, @/effect/app-runtime, @/project/bootstrap
- `proxy.ts` → websocket (86 ln)  [typescript]
  → Imports: @/server/proxy-util
  → imports: @/server/proxy-util, effect, effect/unstable/http
- `workspace-routing.ts` → workspaceRoutingLayer (228 ln)  [typescript]
  → Imports: @/control-plane/adapters
  → imports: @/control-plane/adapters, @/control-plane/schema, @/control-plane/types
- `public.ts` → PublicApi (505 ln)  [typescript]
  → Fix component schemas that are self-referencing `$ref`s — an Effect OpenAPI generation bug where annotated union arms that share AST nodes with other endpoints produce `{"$ref":"#/components/schemas/X
  → imports: effect/unstable/httpapi, ./api
- `server.ts` → createRoutes (198 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect/unstable/httpapi, effect/unstable/http
- `index.ts` → InstanceRoutes (278 ln)  [typescript]
  → Imports: hono-openapi
  → imports: hono-openapi, hono, hono/ws
- `mcp.ts` → McpRoutes (277 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono-openapi, zod
- `middleware.ts` → InstanceMiddleware (35 ln)  [typescript]
  → Imports: hono
  → imports: hono, @/project/instance, @/project/bootstrap
- `permission.ts` → PermissionRoutes (73 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono-openapi, zod
- `project.ts` → ProjectRoutes (122 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono-openapi, hono-openapi
- `provider.ts` → ProviderRoutes (158 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono-openapi, zod
- `pty.ts` → PtyRoutes (276 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono-openapi, hono/ws
- `question.ts` → QuestionRoutes (111 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono-openapi, hono-openapi

---
Generated: 2026-05-04 02:45:04Z
