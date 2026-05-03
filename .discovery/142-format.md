142-format.md

Directory: src/format/

Overview: Code formatting orchestration with multiple formatters (gofmt, prettier, biome, etc.), orchestrated via DI and runtime checks to determine which formatter to apply per file.

- formatter.ts (not shown)
  - Role: Defines formatter interfaces and selection logic
- index.ts
  - Exports: Formatter Status, Format.Service with init/status/file; a default layer wiring to Config and CrossSpawnSpawner
- The code demonstrates dynamic enabling of formatters based on repository configuration and available binaries

End of 142-format.md
