File: plugin/src/example-workspace.ts

ASCII Tree:

├── [import] { Plugin } from "./index.js"
├── [import] { mkdir, rm } from "node:fs/promises"
├── [export] const FolderWorkspacePlugin: Plugin

Description
- Workspace adapter example registering a local filesystem workspace adapter.

Data Flow
- Demonstrates how to configure and register a workspace adapter for folder workspaces.

Side Effects
- Creates/removes temporary folders as part of workspace lifecycle.
