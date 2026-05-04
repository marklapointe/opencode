# Mapping Group 045
Files: 14

**packages/containers/tsconfig.json/**
- `tsconfig.json` →  (8 ln)  [config]

**packages/core/package.json/**
- `package.json` →  (50 ln)  [json]

**packages/core/src/**
- `cross-spawn-spawner.ts` → make (505 ln)  [typescript]
  → Imports: @effect/platform-node
  → imports: @effect/platform-node, effect/unstable/process/ChildProcessSpawner, effect/unstable/process/ChildProcessSpawner
- `logger.ts` → logger (73 ln)  [typescript]
  → Imports: effect
  → imports: effect
- `memo-map.ts` → memoMap (3 ln)  [typescript]
  → Imports: effect
  → imports: effect
- `observability.ts` → resource (107 ln)  [typescript]
  → Imports: effect
  → imports: effect, effect/unstable/http, effect/unstable/observability
- `runtime.ts` → makeRuntime (21 ln)  [typescript]
  → Imports: effect
  → imports: effect, ./memo-map, ./observability
- `filesystem.ts` →  (236 ln)  [typescript]
  → Imports: @effect/platform-node
  → imports: @effect/platform-node, path, fs
- `flag.ts` → Flag (107 ln)  [typescript]
  → Imports: effect
  → imports: effect
- `global.ts` → make (80 ln)  [typescript]
  → Imports: path
  → imports: path, fs/promises, xdg-basedir
- `version.ts` → InstallationVersion (8 ln)  [typescript]
  → const OPENCODE_VERSION: string
- `npm-config.ts` →  (40 ln)  [config]
- `npm.ts` → sanitize (271 ln)  [typescript]
  → Imports: path
  → imports: path, npm-package-arg, effect
- `array.ts` → findLast (10 ln)  [typescript]
  → export function findLast<T>(

---
Generated: 2026-05-04 02:45:04Z
