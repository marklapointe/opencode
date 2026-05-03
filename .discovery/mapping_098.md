# Mapping Group 098
Files: 14

## File Tree
**packages/sdk/js/**
  - `types.gen.ts` →  (3904 ln)  [typescript]
    → Brief description of the task /
  - `index.ts` → createOpencode (21 ln)  [typescript]
    → Imports: ./client.js
  - `process.ts` → stop (31 ln)  [typescript]
    → Imports: node:child_process
  - `server.ts` → createOpencodeServer (134 ln)  [typescript]
    → Imports: cross-spawn
  - `client.ts` → createOpencodeClient + type Config as OpencodeClientConfig, OpencodeClient (88 ln)  [typescript]
    → Imports: ./gen/client/client.gen.js
  - `data.ts` → message (32 ln)  [typescript]
    → Imports: ./client.js
  - `client.gen.ts` → createClient (285 ln)  [typescript]
    → Imports: ../core/serverSentEvents.gen.js
  - `index.ts` → formDataBodySerializer, jsonBodySerializer, urlSearchParamsBodySerializer, , buildClientParams (25 ln)  [typescript]
  - `types.gen.ts` → MethodFn (202 ln)  [typescript]
    → Base URL for all requests made by this client. /
  - `utils.gen.ts` → createQuerySerializer (289 ln)  [typescript]
    → Infers parseAs value from provided Content-Type header. /
  - `client.gen.ts` → client (18 ln)  [typescript]
    → The `createClientConfig()` function will be called on client initialization and the returned object will become the client's initial configuration.
  - `auth.gen.ts` → getAuthToken (41 ln)  [typescript]
    → Which part of the request do we use to send the auth?  @default 'header'
  - `bodySerializer.gen.ts` → formDataBodySerializer (82 ln)  [typescript]
    → Per-parameter serialization overrides. When provided, these settings override the global array/object settings for specific parameter names. /
  - `params.gen.ts` → buildClientParams (169 ln)  [typescript]
    → Field name. This is the name we want the user to see and use. /

---
Generated: 2026-05-03 15:01:00
