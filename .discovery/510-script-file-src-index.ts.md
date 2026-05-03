File: script/src/index.ts

ASCII Tree:

├── [import] { $ } from "bun"
├── [import] semver from "semver"
├── [import] path from "path"
├── [export] const rootPkgPath, rootPkg, CHANNEL, VERSION, CHANNEL constants
├── [export] const Script

Description
- Entry point of the script package performing version/channel computation for releases.

Data Flow
- Derives CHANNEL and VERSION by inspecting root package.json and Bun version, then outputs Script metadata.

Side Effects
- Logs to console the computed Script metadata.
