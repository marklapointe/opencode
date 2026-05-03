147-plugin.md

Directory: src/plugin/

Overview: Plugin system for extending OpenCode at runtime, including internal plugins, external plugin loading, and a plugin loader that provides a hook-based architecture.

- index.ts
  - Exports: Plugin.Service, layer, init, list, trigger, and export * as Plugin from "." namespace
- loader.ts, install.ts, shared.ts, meta.ts
  - Roles: Dynamic plugin loading, installation from npm or other registries, and shared utilities for plugin spec resolution
- internal plugins: codex.ts, github-copilot/copilot.ts, cloudflare/azure etc. (auth plugins and adapters)

- The module demonstrates a layered approach to wiring plugin servers and runtime integration with the opencode core.

- It exports * as Plugin from ".".

End of 147-plugin.md
