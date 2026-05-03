File: slack/src/index.ts

ASCII Tree:

├── [import] { App } from "@slack/bolt"
├── [import] { createOpencode, type ToolPart } from "@opencode-ai/sdk"
├── [export] default App instance and event loop

Description
- Slack bot entrypoint integrating with Slack Bolt, creating opencode sessions on demand.

Data Flow
- Subscribes to events, handles messages, and forwards to opencode; then returns results back to Slack.

Side Effects
- Connects to Slack API, runs continuous event loop.
