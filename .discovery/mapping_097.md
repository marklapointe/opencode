# Mapping Group 097
Files: 14

## File Tree
**packages/sdk/js/**
  - `client.gen.ts` → createClient (212 ln)  [typescript]
    → Imports: ../core/serverSentEvents.gen.js
  - `index.ts` → formDataBodySerializer, jsonBodySerializer, urlSearchParamsBodySerializer, , buildClientParams (25 ln)  [typescript]
  - `types.gen.ts` → MethodFnBase (222 ln)  [typescript]
    → Base URL for all requests made by this client. /
  - `utils.gen.ts` → createQuerySerializer (287 ln)  [typescript]
    → Infers parseAs value from provided Content-Type header. /
  - `client.gen.ts` → client (22 ln)  [typescript]
    → The `createClientConfig()` function will be called on client initialization and the returned object will become the client's initial configuration.
  - `auth.gen.ts` → getAuthToken (41 ln)  [typescript]
    → Which part of the request do we use to send the auth?  @default 'header'
  - `bodySerializer.gen.ts` → formDataBodySerializer (74 ln)  [typescript]
    → Imports: ./pathSerializer.gen.js
  - `params.gen.ts` → buildClientParams (144 ln)  [typescript]
    → Field name. This is the name we want the user to see and use. /
  - `pathSerializer.gen.ts` → separatorArrayExplode (167 ln)  [typescript]
    → @default true /
  - `queryKeySerializer.gen.ts` → queryKeyJsonReplacer (111 ln)  [typescript]
    → JSON-friendly union that mirrors what Pinia Colada can hash. /
  - `serverSentEvents.gen.ts` → createSseClient (210 ln)  [typescript]
    → Callback invoked when a network or parsing error occurs during streaming.  This option applies only if the endpoint returns a stream of events.
  - `types.gen.ts` → IsExactlyNeverOrNeverUndefined (91 ln)  [typescript]
    → Returns the final request URL. /
  - `utils.gen.ts` → PATH_PARAM_RE (109 ln)  [typescript]
    → Imports: ./bodySerializer.gen.js
  - `sdk.gen.ts` → _HeyApiClient (1197 ln)  [typescript]
    → You can provide a client instance returned by `createClient()` instead of individual options. This might be also useful if you want to implement a cus

---
Generated: 2026-05-03 15:01:00
