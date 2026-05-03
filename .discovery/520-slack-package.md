Title: Slack Package Discovery (520)

Directory Tree (exhaustive for this package):

├── [dir] src
│   └── [file] index.ts → Slack bot logic and event handling
├── [file] tsconfig.json
├── [file] sst-env.d.ts
├── [file] .env.example
├── [file] package.json
├── [file] README.md
├── [file] .gitignore

Links to sub-file discovery:
- src/index.ts → 520-slack-file-src-index.ts.md
- tsconfig.json → 520-slack-file-tsconfig.json.md
- sst-env.d.ts → 520-slack-file-sst-env.d.ts.md
- .env.example → 520-slack-file-env-example.md
- package.json → 520-slack-file-package.json.md
- README.md → 520-slack-file-README.md.md
- .gitignore → 520-slack-file-gitignore.md

Description
- Slack integration for opencode that orchestrates sessions through Slack messages and events.

Data Flow
- Listens to Slack events, creates opencode sessions, and streams results back into Slack threads.

Side Effects
- Interacts with Slack API; logs to console during startup and message handling.
