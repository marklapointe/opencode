# Mapping Group 032
Files: 14

**packages/console/app/**
- `messages.ts` → POST (12 ln)  [typescript]
  → Imports: @solidjs/start/server
  → imports: @solidjs/start/server, ~/routes/zen/util/handler
- `models.ts` → OPTIONS (12 ln)  [typescript]
  → Imports: @solidjs/start/server
  → imports: @solidjs/start/server, @opencode-ai/console-core/model.js, ../../util/modelsHandler
- `index.css` →  (867 ln)  [stylesheet]
- `index.tsx` →  (336 ln)  [typescript]
  → Imports: @solidjs/router
  → imports: @solidjs/router, @solidjs/meta, ../../asset/zen-ornate-light.svg
- `dataDumper.ts` → createDataDumper (44 ln)  [typescript]
  → Imports: @opencode-ai/console-resource
  → imports: @opencode-ai/console-resource
- `error.ts` → LimitError (16 ln)  [typescript]
- `handler.ts` → handler (1104 ln)  [typescript]
  → Imports: @solidjs/start/server
  → imports: @solidjs/start/server, @opencode-ai/console-core/drizzle/index.js, @opencode-ai/console-core/schema/key.sql.js
- `ipRateLimiter.ts` → createRateLimiter (70 ln)  [typescript]
  → Imports: @opencode-ai/console-core/drizzle/index.js
  → imports: @opencode-ai/console-core/drizzle/index.js, @opencode-ai/console-core/schema/ip.sql.js, ./error
- `keyRateLimiter.ts` → createRateLimiter (39 ln)  [typescript]
  → Imports: @opencode-ai/console-core/drizzle/index.js
  → imports: @opencode-ai/console-core/drizzle/index.js, @opencode-ai/console-core/schema/ip.sql.js, ./error
- `logger.ts` → logger (12 ln)  [typescript]
  → Imports: @opencode-ai/console-resource
  → imports: @opencode-ai/console-resource
- `modelTpmLimiter.ts` → createModelTpmLimiter (47 ln)  [typescript]
  → Imports: @opencode-ai/console-core/drizzle/index.js
  → imports: @opencode-ai/console-core/drizzle/index.js, @opencode-ai/console-core/schema/ip.sql.js, ./provider/provider
- `modelsHandler.ts` → buildOptionsResponse (31 ln)  [typescript]
  → export async function buildOptionsResponse() {
- `anthropic.ts` → fromAnthropicRequest (759 ln)  [typescript]
  → Imports: @smithy/eventstream-codec
  → imports: @smithy/eventstream-codec, ./provider, @smithy/util-utf8
- `google.ts` → googleHelper (75 ln)  [typescript]
  → Imports: ./provider
  → imports: ./provider

---
Generated: 2026-05-04 02:45:04Z
