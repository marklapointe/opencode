# Mapping Group 116
Files: 14

**packages/sdk/js/**
- `index.ts` →  (25 ln)  [typescript]
- `types.gen.ts` →  (222 ln)  [typescript]
  → Base URL for all requests made by this client. /
  → imports: ../core/auth.gen.js, ../core/serverSentEvents.gen.js, ../core/types.gen.js
- `utils.gen.ts` → createQuerySerializer (287 ln)  [typescript]
  → Infers parseAs value from provided Content-Type header. /
  → imports: ../core/auth.gen.js, ../core/bodySerializer.gen.js, ../core/bodySerializer.gen.js
- `auth.gen.ts` → getAuthToken (41 ln)  [typescript]
  → Which part of the request do we use to send the auth?  @default 'header'
- `bodySerializer.gen.ts` → formDataBodySerializer (74 ln)  [typescript]
  → Imports: ./pathSerializer.gen.js
  → imports: ./pathSerializer.gen.js
- `params.gen.ts` → buildClientParams (144 ln)  [typescript]
  → Field name. This is the name we want the user to see and use. /
- `pathSerializer.gen.ts` → separatorArrayExplode (167 ln)  [typescript]
  → @default true /
- `queryKeySerializer.gen.ts` → queryKeyJsonReplacer (111 ln)  [typescript]
  → JSON-friendly union that mirrors what Pinia Colada can hash. /
- `serverSentEvents.gen.ts` → createSseClient (210 ln)  [typescript]
  → Callback invoked when a network or parsing error occurs during streaming.  This option applies only if the endpoint returns a stream of events.
  → imports: ./types.gen.js
- `types.gen.ts` →  (91 ln)  [typescript]
  → Returns the final request URL. /
  → imports: ./auth.gen.js, ./bodySerializer.gen.js
- `utils.gen.ts` → PATH_PARAM_RE (109 ln)  [typescript]
  → Imports: ./bodySerializer.gen.js
  → imports: ./bodySerializer.gen.js, ./pathSerializer.gen.js
- `sdk.gen.ts` → _HeyApiClient (1197 ln)  [typescript]
  → You can provide a client instance returned by `createClient()` instead of individual options. This might be also useful if you want to implement a custom client.
  → imports: ./client/index.js, ./types.gen.js, ./client.gen.js
- `types.gen.ts` →  (3904 ln)  [typescript]
  → Brief description of the task /
- `index.ts` → createOpencode (21 ln)  [typescript]
  → Imports: ./client.js
  → imports: ./client.js, ./server.js, ./server.js

---
Generated: 2026-05-04 02:45:04Z
