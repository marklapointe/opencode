Root File: plugin/src/index.ts

ASCII Tree (high-level map):

├── [import] from "@opencode-ai/sdk"
├── [import] from "@opencode-ai/sdk/v2"
├── [import] from "./shell.js"
├── [import] from "./tool.js"
├── [export] from "./tool.js"
├── [export] type PluginInput
├── [export] type PluginOptions
├── [export] type Config
├── [export] type Plugin
├── [export] type PluginModule
├── [export] interface Hooks

Description
- Core types and surface area exposed by the plugin package. Bridges plugin runtime with the host and other packages.

Data Flow
- Exposes Plugin and Hooks types used to register plugins, configure credentials, and handle tool integrations.

Side Effects
- No runtime side effects; this is metadata about code structure.
