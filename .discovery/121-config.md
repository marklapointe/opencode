121-config.md

Directory: src/config/

Overview: Config module provides runtime schemas and self-exported config namespaces via export * as X from "./X" patterns.

- server.ts
  - Exports: Server schema (port, hostname, mdns, mdnsDomain, cors) and a ConfigServer namespace export
  - Role: Validates server configuration and exposes a typed schema

- paths.ts
  - Exports: ConfigPaths namespace (import/export); functions files(), directories(), fileInDirectory(), readFile()
  - Role: Utilities for discovering and reading config files across standard paths

- provider.ts
  - Exports: Info schema for provider, Model schema, ConfigProvider namespace
  - Role: Declarative provider config surface and model schema shape

- skills.ts
  - Exports: Ability to model skill loading/registration in config
  - Role: Declarative mapping for skills integration

- permission.ts
  - Exports: Permission rulesets and helpers used by agents/tools

- variable.ts
  - Exports: environment/config variables wrappers

- plugin.ts, formatter.ts, command.ts, error.ts, config.ts, layout.ts, keybinds.ts, model-id.ts, lsp.ts, console-state.ts, mcp.ts, markdown.ts, entry-name.ts, managed.ts, parse.ts, agent.ts
  - Roles: Various config blocks that wire runtime behavior and validation rules for modules

- Exports self-export pattern usage:
  - Many modules follow the project guidance: export * as ConfigServer from "./server" etc., to enable namespace-style imports without barrels.

End of 121-config.md
