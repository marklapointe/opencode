# Mapping Group 096
Files: 14

**packages/opencode/src/**
- `archive.ts` → extractZip (17 ln)  [typescript]
  → Imports: path
  → imports: path
- `bom.ts` → split (31 ln)  [typescript]
  → Imports: effect
  → imports: effect, @opencode-ai/core/filesystem
- `color.ts` → isValidHex (19 ln)  [typescript]
  → export function isValidHex(hex?: string): hex is string {
- `data-url.ts` → decodeDataUrl (9 ln)  [typescript]
  → export function decodeDataUrl(url: string) {
- `defer.ts` → defer (10 ln)  [typescript]
  → export function defer(fn: () => void | Promise<void>): AsyncDisposable & Disposable {
- `effect-http-client.ts` → withTransientReadRetry (11 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect/unstable/http
- `effect-zod.ts` → zod (370 ln)  [typescript]
  → Annotation key for providing a hand-crafted Zod schema that the walker should use instead of re-deriving from the AST.  Attach it via `Schema.String.annotate({ [ZodOverride]: z.string().startsWith("pe
  → imports: effect, zod
- `error.ts` → errorFormat (82 ln)  [typescript]
  → Imports: ./record
  → imports: ./record
- `filesystem.ts` → exists (245 ln)  [typescript]
  → On Windows, normalize a path to its canonical casing using the filesystem. This is needed because Windows paths are case-insensitive but LSP servers may return paths with different casing than what we
  → imports: fs/promises, fs, fs
- `fn.ts` → fn (21 ln)  [typescript]
  → Imports: zod
  → imports: zod
- `format.ts` → formatDuration (20 ln)  [typescript]
  → export function formatDuration(secs: number) {
- `iife.ts` → iife (3 ln)  [typescript]
  → export function iife<T>(fn: () => T) {
- `keybind.ts` → match (103 ln)  [typescript]
  → Keybind info derived from OpenTUI's ParsedKey with our custom `leader` field. This ensures type compatibility and catches missing fields at compile time. /
  → imports: remeda, @opentui/core
- `lazy.ts` → lazy (18 ln)  [typescript]
  → export function lazy<T>(fn: () => T) {

---
Generated: 2026-05-04 02:45:04Z
