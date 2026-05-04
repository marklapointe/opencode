# Mapping Group 017
Files: 14

**packages/app/src/**
- `helpers.ts` → getSessionKey (194 ln)  [typescript]
  → Imports: solid-js
  → imports: solid-js, solid-js/store, @solid-primitives/event-listener
- `message-gesture.test.ts` →  (62 ln)  [test]
- `message-gesture.ts` → normalizeWheelDelta (21 ln)  [typescript]
  → export const normalizeWheelDelta = (input: { deltaY: number; deltaMode: number; rootHeight: number }) => {
- `message-id-from-hash.ts` → messageIdFromHash (6 ln)  [typescript]
  → export const messageIdFromHash = (hash: string) => {
- `message-timeline.tsx` → MessageTimeline (1118 ln)  [typescript]
  → Defer-mounts small timeline windows so revealing older turns does not block first paint with a large DOM mount.
  → imports: solid-js, solid-js/store, @solidjs/router
- `review-tab.tsx` → SessionReviewTab (170 ln)  [typescript]
  → Imports: solid-js
  → imports: solid-js, @solid-primitives/event-listener, @opencode-ai/sdk/v2
- `session-layout.ts` → useSessionKey (20 ln)  [typescript]
  → Imports: @solidjs/router
  → imports: @solidjs/router, solid-js, @/context/layout
- `session-model-helpers.test.ts` →  (52 ln)  [test]
- `session-model-helpers.ts` → resetSessionModel (16 ln)  [typescript]
  → Imports: @opencode-ai/sdk/v2
  → imports: @opencode-ai/sdk/v2
- `session-side-panel.tsx` → SessionSidePanel (453 ln)  [typescript]
  → Imports: solid-js
  → imports: solid-js, solid-js/store, @solid-primitives/media
- `terminal-label.ts` → terminalTabLabel (16 ln)  [typescript]
  → Imports: @/context/terminal-title
  → imports: @/context/terminal-title
- `terminal-panel.test.ts` →  (25 ln)  [test]
- `terminal-panel.tsx` → TerminalPanel (317 ln)  [typescript]
  → Imports: solid-js
  → imports: solid-js, solid-js/store, @solid-primitives/event-listener
- `use-session-commands.tsx` → useSessionCommands (587 ln)  [typescript]
  → Imports: @solidjs/router
  → imports: @solidjs/router, @/context/command, @opencode-ai/ui/context/dialog

---
Generated: 2026-05-04 02:45:04Z
