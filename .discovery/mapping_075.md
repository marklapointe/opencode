# Mapping Group 075
Files: 14

**packages/opencode/src/**
- `link.tsx` → Link (28 ln)  [typescript]
  → Link component that renders clickable hyperlinks. Clicking anywhere on the link text opens the URL in the default browser. /
  → imports: solid-js, @opentui/core, open
- `spinner.ts` → deriveTrailColors (368 ln)  [typescript]
  → Derives a gradient of tail colors from a single bright color using alpha falloff @param brightColor The brightest color (center/head of the scanner) @param steps Number of gradient steps (default: 6)
  → imports: @opentui/core, @opentui/core, opentui-spinner
- `toast.tsx` → Toast (102 ln)  [typescript]
  → Imports: solid-js
  → imports: solid-js, solid-js/store, @tui/context/theme
- `clipboard.ts` → read (205 ln)  [typescript]
  → Writes text to clipboard via OSC 52 escape sequence. This allows clipboard operations to work over SSH by having the terminal emulator handle the clipboard locally.
  → imports: os, ../../../../util/lazy.js, os
- `editor.ts` → open (37 ln)  [typescript]
  → Imports: @/util/defer
  → imports: @/util/defer, node:fs/promises, node:os
- `model.ts` → index (23 ln)  [typescript]
  → Imports: @opencode-ai/sdk/v2
  → imports: @opencode-ai/sdk/v2
- `provider-origin.ts` → isConsoleManagedProvider (7 ln)  [typescript]
  → const contains = (consoleManagedProviders: string[] | ReadonlySet<string>, providerID: string) =>
- `revert-diff.ts` → getRevertDiffFiles (18 ln)  [typescript]
  → Imports: diff
  → imports: diff
- `scroll.ts` → getScrollAcceleration (23 ln)  [typescript]
  → Imports: @opentui/core
  → imports: @opentui/core, @/cli/cmd/tui/config/tui
- `selection.ts` → copy (25 ln)  [typescript]
  → show: (input: { message: string; variant: "info" | "success" | "warning" | "error" }) => void
- `signal.ts` → createDebouncedSignal (41 ln)  [typescript]
  → Imports: solid-js
  → imports: solid-js, @solid-primitives/scheduled
- `sound.ts` → start (156 ln)  [typescript]
  → Imports: cli-sound
  → imports: cli-sound, node:fs, node:os
- `transcript.ts` → formatTranscript (112 ln)  [typescript]
  → Imports: @opencode-ai/sdk/v2
  → imports: @opencode-ai/sdk/v2, @/util/locale
- `validate-session.ts` → validateSession (24 ln)  [typescript]
  → Imports: @opencode-ai/sdk/v2
  → imports: @opencode-ai/sdk/v2, @/session/schema

---
Generated: 2026-05-04 02:45:04Z
