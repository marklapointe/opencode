# Mapping Group 095
Files: 14

**packages/opencode/src/**
- `question.ts` → Parameters (44 ln)  [typescript]
  → Imports: effect
  → imports: effect, ../question, ./question.txt
- `read.ts` → Parameters (343 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/util/schema, fs
- `registry.ts` → layer (347 ln)  [typescript]
  → Imports: ./plan
  → imports: ./plan, @/session/session, ./question
- `schema.ts` → ToolID (16 ln)  [typescript]
  → Imports: effect
  → imports: effect, @/id/id, @/util/effect-zod
- `skill.ts` → Parameters (75 ln)  [typescript]
  → Imports: path
  → imports: path, url, effect
- `task.ts` → Parameters (180 ln)  [typescript]
  → Imports: ./task.txt
  → imports: ./task.txt, @/session/session, ../session/schema
- `todo.ts` → Parameters (57 ln)  [typescript]
  → Imports: effect
  → imports: effect, ./todowrite.txt, ../session/todo
- `tool.ts` → define (162 ln)  [typescript]
  → Imports: effect
  → imports: effect, ../session/message-v2, ../permission
- `truncate.ts` → MAX_LINES (160 ln)  [typescript]
  → Returns output unchanged when it fits within the limits, otherwise writes the full text to the truncation directory and returns a preview plus a hint to inspect the saved file. /
  → imports: @effect/platform-node, effect, path
- `truncation-dir.ts` → TRUNCATION_DIR (4 ln)  [typescript]
  → Imports: path
  → imports: path, @opencode-ai/core/global
- `webfetch.ts` → Parameters (199 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect/unstable/http, turndown
- `websearch.ts` → Parameters (71 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect/unstable/http, ./websearch.txt
- `write.ts` → Parameters (104 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect, @/lsp/lsp
- `abort.ts` → abortAfter (35 ln)  [typescript]
  → Creates an AbortController that automatically aborts after a timeout.  Uses bind() instead of arrow functions to avoid capturing the surrounding

---
Generated: 2026-05-04 02:45:04Z
