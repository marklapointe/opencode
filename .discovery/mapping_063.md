# Mapping Group 063
Files: 14

**packages/opencode/src/**
- `schema.ts` → AccountID (99 ln)  [typescript]
  → Imports: effect
  → imports: effect
- `url.ts` → normalizeServerUrl (8 ln)  [typescript]
  → export const normalizeServerUrl = (input: string): string => {
- `README.md` →  (174 ln)  [docs]
- `agent.ts` → init (1838 ln)  [typescript]
  → Imports: @agentclientprotocol/sdk
  → imports: @agentclientprotocol/sdk, url, @/util/filesystem
- `session.ts` →  (116 ln)  [typescript]
  → Imports: @agentclientprotocol/sdk
  → imports: @agentclientprotocol/sdk, ./types, @opencode-ai/sdk/v2
- `types.ts` →  (24 ln)  [typescript]
  → Imports: @agentclientprotocol/sdk
  → imports: @agentclientprotocol/sdk, @opencode-ai/sdk/v2, ../provider/schema
- `agent.ts` → Info (413 ln)  [typescript]
  → Imports: @/config/config
  → imports: @/config/config, zod, @/provider/provider
- `audio.d.ts` →  (4 ln)  [typescript]
  → const file: string
- `index.ts` → OAUTH_DUMMY_KEY (98 ln)  [typescript]
  → Imports: path
  → imports: path, effect, @/util/effect-zod
- `bus-event.ts` → define (49 ln)  [typescript]
  → Imports: zod
  → imports: zod, effect, @/util/effect-zod
- `global.ts` → GlobalBus (12 ln)  [typescript]
  → Imports: events
  → imports: events
- `index.ts` → publish (188 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/effect/bridge, ./bus-event
- `bootstrap.ts` → bootstrap (18 ln)  [typescript]
  → Imports: @/effect/app-runtime
  → imports: @/effect/app-runtime, ../project/bootstrap, ../project/instance
- `account.ts` → formatAccountLabel (258 ln)  [typescript]
  → Imports: ./cmd
  → imports: ./cmd, effect, ../ui

---
Generated: 2026-05-04 02:45:04Z
