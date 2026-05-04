# Mapping Group 085
Files: 14

**packages/opencode/src/**
- `image-generation.ts` → imageGenerationArgsSchema (114 ln)  [typescript]
  → Background type for the generated image. Default is 'auto'. /
  → imports: @ai-sdk/provider-utils, zod/v4
- `local-shell.ts` → localShellInputSchema (64 ln)  [typescript]
  → Execute a shell command on the server. /
  → imports: @ai-sdk/provider-utils, zod/v4
- `web-search-preview.ts` → webSearchPreviewArgsSchema (103 ln)  [typescript]
  → Search context size to use for the web search. - high: Most comprehensive context, highest cost, slower response - medium: Balanced context, cost, and latency (default)
  → imports: @ai-sdk/provider-utils, zod/v4
- `web-search.ts` → webSearchArgsSchema (102 ln)  [typescript]
  → Filters for the search. /
  → imports: @ai-sdk/provider-utils, zod/v4
- `transform.ts` → message (1200 ln)  [typescript]
  → Imports: ai
  → imports: ai, remeda, @ai-sdk/provider
- `index.ts` → Info (368 ln)  [typescript]
  → Imports: @/bus/bus-event
  → imports: @/bus/bus-event, @/bus, @/config/config
- `input.ts` → handlePtyInput (24 ln)  [typescript]
  → Imports: effect
  → imports: effect
- `pty.bun.ts` → spawn (26 ln)  [typescript]
  → Imports: bun-pty
  → imports: bun-pty, ./pty
- `pty.node.ts` → spawn (27 ln)  [typescript]
  → Imports: ./pty
  → imports: ./pty
- `pty.ts` →  (25 ln)  [typescript]
- `schema.ts` → PtyID (16 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/id/id, @/util/effect-zod
- `index.ts` → Answer (229 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/bus, @/bus/bus-event
- `schema.ts` →  (16 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/id/id, @/util/effect-zod
- `adapter.bun.ts` → adapter (44 ln)  [typescript]
  → Imports: hono
  → imports: hono, hono/bun, ./adapter

---
Generated: 2026-05-04 02:45:04Z
