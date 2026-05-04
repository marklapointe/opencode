# Mapping Group 083
Files: 14

**packages/opencode/src/**
- `schema.ts` → ProjectID (15 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/util/effect-zod, @/util/schema
- `vcs.ts` → Mode (226 ln)  [typescript]
  → Imports: effect
  → imports: effect, diff, path
- `auth.ts` → Methods (228 ln)  [typescript]
  → Imports: @opencode-ai/plugin
  → imports: @opencode-ai/plugin, @/auth, @/effect/instance-state
- `error.ts` → parseStreamError (203 ln)  [typescript]
  → Imports: ai
  → imports: ai, http, @/util/iife
- `models.ts` → get (176 ln)  [typescript]
  → Imports: @opencode-ai/core/global
  → imports: @opencode-ai/core/global, path, effect
- `provider.ts` → defaultModelIDs (1756 ln)  [typescript]
  → Imports: os
  → imports: os, fuzzysort, @/config/config
- `schema.ts` → ProviderID (36 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/util/effect-zod, @/util/schema
- `README.md` →  (5 ln)  [docs]
- `convert-to-openai-compatible-chat-messages.ts` → convertToOpenAICompatibleChatMessages (170 ln)  [typescript]
  → Imports: @ai-sdk/provider
  → imports: @ai-sdk/provider, ./openai-compatible-api-types, @ai-sdk/provider-utils
- `get-response-metadata.ts` → getResponseMetadata (15 ln)  [typescript]
  → export function getResponseMetadata({
- `map-openai-compatible-finish-reason.ts` → mapOpenAICompatibleFinishReason (19 ln)  [typescript]
  → Imports: @ai-sdk/provider
  → imports: @ai-sdk/provider
- `openai-compatible-api-types.ts` →  (64 ln)  [typescript]
  → Imports: @ai-sdk/provider
  → imports: @ai-sdk/provider
- `openai-compatible-chat-language-model.ts` →  (815 ln)  [typescript]
  → Whether the model supports structured outputs. /
  → imports: @ai-sdk/provider, @ai-sdk/provider-utils, zod/v4
- `openai-compatible-chat-options.ts` → openaiCompatibleProviderOptions (28 ln)  [typescript]
  → A unique identifier representing your end-user, which can help the provider to monitor and detect abuse. /
  → imports: zod/v4

---
Generated: 2026-05-04 02:45:04Z
