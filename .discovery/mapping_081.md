# Mapping Group 081
Files: 14

**packages/opencode/src/**
- `language.ts` → LANGUAGE_EXTENSIONS (121 ln)  [typescript]
  → export const LANGUAGE_EXTENSIONS: Record<string, string> = {
- `launch.ts` → spawn (21 ln)  [typescript]
  → Imports: child_process
  → imports: child_process, @/util/process
- `lsp.ts` → Event (522 ln)  [typescript]
  → Imports: @/bus/bus-event
  → imports: @/bus/bus-event, @/bus, path
- `server.ts` → Deno (2064 ln)  [typescript]
  → Imports: child_process
  → imports: child_process, path, os
- `auth.ts` → Tokens (144 ln)  [typescript]
  → Imports: path
  → imports: path, zod, @opencode-ai/core/global
- `index.ts` → Resource (931 ln)  [typescript]
  → Connect a client via the given transport with resource safety: on failure the transport is closed; on success the caller owns it. /
  → imports: ai, @modelcontextprotocol/sdk/client/index.js, @modelcontextprotocol/sdk/client/streamableHttp.js
- `oauth-callback.ts` → ensureRunning (232 ln)  [typescript]
  → Imports: net
  → imports: net, http, ./oauth-provider
- `oauth-provider.ts` → parseRedirectUri (214 ln)  [typescript]
  → Parse a redirect URI to extract port and path for the callback server. Returns defaults if the URI can't be parsed. /
  → imports: @modelcontextprotocol/sdk/client/auth.js, @modelcontextprotocol/sdk/shared/auth.js, effect
- `node.ts` →  (6 ln)  [typescript]
- `index.ts` → parsePatch (684 ln)  [typescript]
  → Imports: zod
  → imports: zod, fs
- `arity.ts` → prefix (163 ln)  [typescript]
  → export function prefix(tokens: string[]) {
- `evaluate.ts` → evaluate (15 ln)  [typescript]
  → Imports: @/util/wildcard
  → imports: @/util/wildcard
- `index.ts` → evaluate (325 ln)  [typescript]
  → Imports: @/bus
  → imports: @/bus, @/bus/bus-event, @/config/permission
- `schema.ts` →  (16 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/id/id, @/util/effect-zod

---
Generated: 2026-05-04 02:45:04Z
