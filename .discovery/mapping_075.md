# Mapping Group 075
Files: 14

## File Tree
**packages/opencode/src/**
  - `effect-zod.ts` → zod (370 ln)  [typescript]
    → Annotation key for providing a hand-crafted Zod schema that the walker should use instead of re-deriving from the AST.  Attach it via `Schema.String.a
  - `error.ts` → errorFormat (82 ln)  [typescript]
    → Imports: ./record
  - `filesystem.ts` → exists (245 ln)  [typescript]
    → On Windows, normalize a path to its canonical casing using the filesystem. This is needed because Windows paths are case-insensitive but LSP servers m
  - `fn.ts` → fn (21 ln)  [typescript]
    → Imports: zod
  - `format.ts` → formatDuration (20 ln)  [typescript]
    → export function formatDuration(secs: number) {
  - `iife.ts` → iife (3 ln)  [typescript]
    → export function iife<T>(fn: () => T) {
  - `keybind.ts` → match (103 ln)  [typescript]
    → Keybind info derived from OpenTUI's ParsedKey with our custom `leader` field. This ensures type compatibility and catches missing fields at compile ti
  - `lazy.ts` → lazy (18 ln)  [typescript]
    → export function lazy<T>(fn: () => T) {
  - `local-context.ts` → create (25 ln)  [typescript]
    → Imports: async_hooks
  - `locale.ts` → titlecase (81 ln)  [typescript]
    → export function titlecase(str: string) {
  - `lock.ts` → read (98 ln)  [typescript]
    → const locks = new Map<
  - `media.ts` → isPdfAttachment (26 ln)  [typescript]
    → const startsWith = (bytes: Uint8Array, prefix: number[]) => prefix.every((value, index) => bytes[index] === value)
  - `named-schema-error.ts` → namedSchemaError (61 ln)  [typescript]
    → Create a Schema-backed NamedError-shaped class.  Drop-in replacement for `NamedError.create(tag, zodShape)` but backed by
  - `network.ts` → online (9 ln)  [typescript]
    → export function online() {

---
Generated: 2026-05-03 15:01:00
