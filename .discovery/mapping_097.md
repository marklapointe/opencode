# Mapping Group 097
Files: 14

**packages/opencode/src/**
- `local-context.ts` → create (25 ln)  [typescript]
  → Imports: async_hooks
  → imports: async_hooks
- `locale.ts` → titlecase (81 ln)  [typescript]
  → export function titlecase(str: string) {
- `lock.ts` → read (98 ln)  [typescript]
  → const locks = new Map<
- `media.ts` → isPdfAttachment (26 ln)  [typescript]
  → const startsWith = (bytes: Uint8Array, prefix: number[]) => prefix.every((value, index) => bytes[index] === value)
- `named-schema-error.ts` → namedSchemaError (61 ln)  [typescript]
  → Create a Schema-backed NamedError-shaped class.  Drop-in replacement for `NamedError.create(tag, zodShape)` but backed by
  → imports: effect, zod, @/util/effect-zod
- `network.ts` → online (9 ln)  [typescript]
  → export function online() {
- `process.ts` → spawn (176 ln)  [typescript]
  → Imports: child_process
  → imports: child_process, cross-spawn, node:stream/consumers
- `queue.ts` → work (32 ln)  [typescript]
  → private resolvers: ((value: T) => void)[] = []
- `record.ts` → isRecord (3 ln)  [typescript]
  → export function isRecord(value: unknown): value is Record<string, unknown> {
- `rpc.ts` → listen (66 ln)  [typescript]
  → [method: string]: (input: any) => any
- `schema.ts` → Newtype (108 ln)  [typescript]
  → Integer greater than zero. /
  → imports: effect, ./effect-zod
- `scrap.ts` → dummyFunction (10 ln)  [typescript]
  → export const foo: string = "42"
- `signal.ts` → signal (12 ln)  [typescript]
  → export function signal() {
- `timeout.ts` → withTimeout (13 ln)  [typescript]
  → export function withTimeout<T>(promise: Promise<T>, ms: number): Promise<T> {

---
Generated: 2026-05-04 02:45:04Z
