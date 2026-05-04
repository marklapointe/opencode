# Mapping Group 117
Files: 14

**packages/sdk/js/**
- `process.ts` → stop (31 ln)  [typescript]
  → Imports: node:child_process
  → imports: node:child_process
- `server.ts` → createOpencodeServer (134 ln)  [typescript]
  → Imports: cross-spawn
  → imports: cross-spawn, ./gen/types.gen.js, ./process.js
- `client.ts` → createOpencodeClient (88 ln)  [typescript]
  → Imports: ./gen/client/client.gen.js
  → imports: ./gen/client/client.gen.js, ./gen/client/types.gen.js, ./gen/sdk.gen.js
- `data.ts` → message (32 ln)  [typescript]
  → Imports: ./client.js
  → imports: ./client.js
- `client.gen.ts` → client (18 ln)  [typescript]
  → The `createClientConfig()` function will be called on client initialization and the returned object will become the client's initial configuration.
  → imports: ./client/index.js, ./types.gen.js
- `client.gen.ts` → createClient (285 ln)  [typescript]
  → Imports: ../core/serverSentEvents.gen.js
  → imports: ../core/serverSentEvents.gen.js, ../core/types.gen.js, ../core/utils.gen.js
- `index.ts` →  (25 ln)  [typescript]
- `types.gen.ts` →  (202 ln)  [typescript]
  → Base URL for all requests made by this client. /
  → imports: ../core/auth.gen.js, ../core/serverSentEvents.gen.js, ../core/types.gen.js
- `utils.gen.ts` → createQuerySerializer (289 ln)  [typescript]
  → Infers parseAs value from provided Content-Type header. /
  → imports: ../core/auth.gen.js, ../core/bodySerializer.gen.js, ../core/bodySerializer.gen.js
- `auth.gen.ts` → getAuthToken (41 ln)  [typescript]
  → Which part of the request do we use to send the auth?  @default 'header'
- `bodySerializer.gen.ts` → formDataBodySerializer (82 ln)  [typescript]
  → Per-parameter serialization overrides. When provided, these settings override the global array/object settings for specific parameter names. /
  → imports: ./pathSerializer.gen.js
- `params.gen.ts` → buildClientParams (169 ln)  [typescript]
  → Field name. This is the name we want the user to see and use. /
- `pathSerializer.gen.ts` → separatorArrayExplode (167 ln)  [typescript]
  → @default true /
- `queryKeySerializer.gen.ts` → queryKeyJsonReplacer (111 ln)  [typescript]
  → JSON-friendly union that mirrors what Pinia Colada can hash. /

---
Generated: 2026-05-04 02:45:04Z
