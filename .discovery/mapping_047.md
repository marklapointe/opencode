# Mapping Group 047
Files: 14

## File Tree
**packages/opencode/src/**
  - `clipboard.ts` → read (205 ln)  [typescript]
    → Writes text to clipboard via OSC 52 escape sequence. This allows clipboard operations to work over SSH by having the terminal emulator handle the clip
  - `editor.ts` → open (37 ln)  [typescript]
    → Imports: @/util/defer
  - `model.ts` → index (23 ln)  [typescript]
    → Imports: @opencode-ai/sdk/v2
  - `provider-origin.ts` → isConsoleManagedProvider (7 ln)  [typescript]
    → const contains = (consoleManagedProviders: string[] | ReadonlySet<string>, providerID: string) =>
  - `revert-diff.ts` → getRevertDiffFiles (18 ln)  [typescript]
    → Imports: diff
  - `scroll.ts` → getScrollAcceleration (23 ln)  [typescript]
    → Imports: @opentui/core
  - `selection.ts` → copy (25 ln)  [typescript]
    → show: (input: { message: string; variant: "info" | "success" | "warning" | "error" }) => void
  - `signal.ts` → createDebouncedSignal (41 ln)  [typescript]
    → Imports: solid-js
  - `sound.ts` → start (156 ln)  [typescript]
    → Imports: cli-sound
  - `transcript.ts` → formatTranscript (112 ln)  [typescript]
    → Imports: @opencode-ai/sdk/v2
  - `validate-session.ts` → validateSession (24 ln)  [typescript]
    → Imports: @opencode-ai/sdk/v2
  - `win32.ts` → win32DisableProcessedInput (130 ln)  [typescript]
    → Clear ENABLE_PROCESSED_INPUT on the console stdin handle. /
  - `worker.ts` → rpc (104 ln)  [typescript]
    → Imports: @/installation
  - `uninstall.ts` → UninstallCommand (353 ln)  [typescript]
    → Imports: yargs

---
Generated: 2026-05-03 15:01:00
