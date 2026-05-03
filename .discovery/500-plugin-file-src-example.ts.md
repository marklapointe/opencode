File: plugin/src/example.ts

ASCII Tree:

├── [import] { Plugin } from "./index.js"
├── [import] { tool } from "./tool.js"
├── [export] const ExamplePlugin: Plugin

Description
- An example Plugin that exposes a sample tool named mytool for demonstration.

Data Flow
- Example plugin registers a tool and returns it via the plugin API surface.

Side Effects
- None beyond module evaluation; this is a small, demonstration plugin.
