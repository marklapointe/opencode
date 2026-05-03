Title: Plugin Package Discovery (500)

Directory Tree (exhaustive for this package):

├── [dir] src
│   ├── [file] index.ts → Maps core plugin API surface and exports
│   ├── [file] tui.ts → Type definitions for terminal UI plugin layer
│   ├── [file] shell.ts → BunShell API surface and utilities
│   ├── [file] example.ts → Example plugin implementing a tool
│   ├── [file] example-workspace.ts → Workspace adapter example
│   └── [file] tool.ts → Tool definition helper and schema
├── [file] tsconfig.json
├── [file] sst-env.d.ts
├── [file] package.json
├── [file] .gitignore
└── [dir] script
    └── [file] publish.ts

Links to sub-file discovery (one per file above):
- src/index.ts → 500-plugin-file-src-index.ts.md
- src/tui.ts → 500-plugin-file-src-tui.ts.md
- src/shell.ts → 500-plugin-file-src-shell.ts.md
- src/example.ts → 500-plugin-file-src-example.ts.md
- src/example-workspace.ts → 500-plugin-file-src-example-workspace.ts.md
- src/tool.ts → 500-plugin-file-src-tool.ts.md
- tsconfig.json → 500-plugin-file-tsconfig.json.md
- sst-env.d.ts → 500-plugin-file-sst-env.d.ts.md
- package.json → 500-plugin-file-package.json.md
- .gitignore → 500-plugin-file-gitignore.md
- script/publish.ts → 500-plugin-file-script-publish.ts.md

Description
- This root discovery file enumerates the plugin package and points to per-file discovery artifacts. It captures the plugin API surface exposed via src/index.ts and the auxiliary tool/shim definitions in src/tool.ts and related UI layer in src/tui.ts. Also references example plugins and workspace adapters.

Data Flow
- Index and types define the public contract consumed by the host and by other packages. The tool definitions are composed and surfaced via Plugin/PluginModule types.

Side Effects
- None at discovery time; this file only documents structure and references.
