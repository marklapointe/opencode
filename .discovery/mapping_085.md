# Mapping Group 085
Files: 14

## File Tree
**packages/opencode/script/**
  - `trace-imports.ts` →  (153 ln)  [typescript]
    → Imports: path
  - `upgrade-opentui.ts` →  (64 ln)  [typescript]
    → Imports: node:path

**packages/opencode/specs/**
  - `api.ts` →  (67 ln)  [typescript]
    → Imports: @opencode-ai/core

**packages/opencode/src/**
  - `account.sql.ts` → AccountTable (39 ln)  [typescript]
    → Imports: drizzle-orm/sqlite-core
  - `account.ts` → layer + AccountID, type AccountError, AccountRepoError, AccountServiceError, AccountTransportError (456 ln)  [typescript]
    → Imports: effect
  - `repo.ts` → layer (166 ln)  [typescript]
    → Imports: drizzle-orm
  - `schema.ts` → AccountID (99 ln)  [typescript]
    → Imports: effect
  - `url.ts` → normalizeServerUrl (8 ln)  [typescript]
    → export const normalizeServerUrl = (input: string): string => {
  - `agent.ts` → init (1838 ln)  [typescript]
    → Imports: @agentclientprotocol/sdk
  - `session.ts` →  (116 ln)  [typescript]
    → Imports: @agentclientprotocol/sdk
  - `types.ts` →  (24 ln)  [typescript]
    → Imports: @agentclientprotocol/sdk
  - `agent.ts` → Info (413 ln)  [typescript]
    → Imports: @/config/config
  - `audio.d.ts` →  (4 ln)  [typescript]
    → const file: string
  - `index.ts` → hints (187 ln)  [typescript]
    → Imports: @/bus/bus-event

---
Generated: 2026-05-03 15:01:00
