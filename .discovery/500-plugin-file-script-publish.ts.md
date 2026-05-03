File: plugin/script/publish.ts

ASCII Tree:

├── [import] { Script } from "@opencode-ai/script"
├── [import] { $ } from "bun"
├── [import] { fileURLToPath } from "url"
├── [export] async function published(name: string, version: string)
├── [export] async function main(): Promise<void>

Description
- Script to publish plugin package to npm after building dist outputs.

Data Flow
- Reads package.json, builds TS, updates exports, and invokes npm/publish commands.

Side Effects
- Writes package.json and runs bun/pm pack and npm publish as side effects.
