# Mapping Group 074
Files: 14

## File Tree
**packages/opencode/src/**
  - `todo.ts` → Parameters (57 ln)  [typescript]
    → Imports: effect
  - `tool.ts` → define (162 ln)  [typescript]
    → Imports: effect
  - `truncate.ts` → MAX_LINES (160 ln)  [typescript]
    → Returns output unchanged when it fits within the limits, otherwise writes the full text to the truncation directory and returns a preview plus a hint
  - `truncation-dir.ts` → TRUNCATION_DIR (4 ln)  [typescript]
    → Imports: path
  - `webfetch.ts` → Parameters (199 ln)  [typescript]
    → Imports: effect
  - `websearch.ts` → Parameters (71 ln)  [typescript]
    → Imports: effect
  - `write.ts` → Parameters (104 ln)  [typescript]
    → Imports: effect
  - `abort.ts` → abortAfter (35 ln)  [typescript]
    → Creates an AbortController that automatically aborts after a timeout.  Uses bind() instead of arrow functions to avoid capturing the surrounding
  - `archive.ts` → extractZip (17 ln)  [typescript]
    → Imports: path
  - `bom.ts` → split (31 ln)  [typescript]
    → Imports: effect
  - `color.ts` → isValidHex (19 ln)  [typescript]
    → export function isValidHex(hex?: string): hex is string {
  - `data-url.ts` → decodeDataUrl (9 ln)  [typescript]
    → export function decodeDataUrl(url: string) {
  - `defer.ts` → defer (10 ln)  [typescript]
    → export function defer(fn: () => void | Promise<void>): AsyncDisposable & Disposable {
  - `effect-http-client.ts` → withTransientReadRetry (11 ln)  [typescript]
    → Imports: effect

---
Generated: 2026-05-03 15:01:00
