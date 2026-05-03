Title: Script Package Discovery (510)

Directory Tree (exhaustive for this package):

├── [dir] src
│   ├── [file] index.ts → Script entrypoint aggregating channel/version logic
├── [file] tsconfig.json
├── [file] sst-env.d.ts
├── [file] package.json

Links to sub-file discovery:
- src/index.ts → 510-script-file-src-index.ts.md
- tsconfig.json → 510-script-file-tsconfig.json.md
- sst-env.d.ts → 510-script-file-sst-env.d.ts.md
- package.json → 510-script-file-package.json.md

Description
- Centralized script for versioning and channel management of OpenCode releases.

Data Flow
- Reads root package.json to determine bun version compatibility and computes version/channel based on env vars and git state.

Side Effects
- Console.log of Script summary.
