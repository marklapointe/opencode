# Mapping Group 118
Files: 14

**packages/sdk/js/**
- `serverSentEvents.gen.ts` → createSseClient (239 ln)  [typescript]
  → Fetch API implementation. You can use this option to provide a custom fetch instance.
  → imports: ./types.gen.js
- `types.gen.ts` →  (86 ln)  [typescript]
  → Returns the final request URL. /
  → imports: ./auth.gen.js, ./bodySerializer.gen.js
- `utils.gen.ts` → getValidRequestBody (137 ln)  [typescript]
  → Imports: ./bodySerializer.gen.js
  → imports: ./bodySerializer.gen.js, ./pathSerializer.gen.js
- `sdk.gen.ts` → HeyApiClient (4497 ln)  [typescript]
  → You can provide a client instance returned by `createClient()` instead of individual options. This might be also useful if you want to implement a custom client.
  → imports: ./client.gen.js, ./client/index.js, ./types.gen.js
- `types.gen.ts` →  (5546 ln)  [typescript]
  → Startup script to run when creating a new workspace (worktree) /
- `index.ts` → createOpencode (23 ln)  [typescript]
  → Imports: ./client.js
  → imports: ./client.js, ./server.js, ./server.js
- `server.ts` → createOpencodeServer (134 ln)  [typescript]
  → Imports: cross-spawn
  → imports: cross-spawn, ./gen/types.gen.js, ../process.js
- `sst-env.d.ts` →  (10 ln)  [typescript]
  → Imports: sst
  → imports: sst
- `tsconfig.json` →  (14 ln)  [config]

**packages/sdk/openapi.json/**
- `openapi.json` →  (13688 ln)  [json]

**packages/slack/.env.example/**
- `.env.example` →  (3 ln)  [file]

**packages/slack/.gitignore/**
- `.gitignore` →  (4 ln)  [file]

**packages/slack/README.md/**
- `README.md` →  (27 ln)  [docs]

**packages/slack/package.json/**
- `package.json` →  (19 ln)  [json]

---
Generated: 2026-05-04 02:45:04Z
