# Mapping Group 115
Files: 14

**packages/plugin/sst-env.d.ts/**
- `sst-env.d.ts` →  (10 ln)  [typescript]
  → Imports: sst
  → imports: sst

**packages/plugin/tsconfig.json/**
- `tsconfig.json` →  (13 ln)  [config]

**packages/script/package.json/**
- `package.json` →  (15 ln)  [json]

**packages/script/src/**
- `index.ts` → Script (77 ln)  [typescript]
  → Imports: bun
  → imports: bun, semver, path

**packages/script/sst-env.d.ts/**
- `sst-env.d.ts` →  (10 ln)  [typescript]
  → Imports: sst
  → imports: sst

**packages/script/tsconfig.json/**
- `tsconfig.json` →  (8 ln)  [config]

**packages/sdk/.gitignore/**
- `.gitignore` →  (10 ln)  [file]

**packages/sdk/js/**
- `example.ts` →  (56 ln)  [typescript]
  → Imports: @opencode-ai/sdk
  → imports: @opencode-ai/sdk, bun
- `package.json` →  (34 ln)  [json]
- `build.ts` →  (52 ln)  [typescript]
  → Imports: url
  → imports: url, bun, path
- `publish.ts` →  (45 ln)  [typescript]
  → Imports: @opencode-ai/script
  → imports: @opencode-ai/script, bun, url
- `client.ts` → createOpencodeClient (55 ln)  [typescript]
  → Imports: ./gen/client/client.gen.js
  → imports: ./gen/client/client.gen.js, ./gen/client/types.gen.js, ./gen/sdk.gen.js
- `client.gen.ts` → client (22 ln)  [typescript]
  → The `createClientConfig()` function will be called on client initialization and the returned object will become the client's initial configuration.
  → imports: ./types.gen.js, ./client/index.js
- `client.gen.ts` → createClient (212 ln)  [typescript]
  → Imports: ../core/serverSentEvents.gen.js
  → imports: ../core/serverSentEvents.gen.js, ./types.gen.js, ./utils.gen.js

---
Generated: 2026-05-04 02:45:04Z
