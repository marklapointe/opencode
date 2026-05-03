145-installation.md

Directory: src/installation/

Overview: Installation manager for runtime opencode, handling version detection, upgrades via multiple package managers, and upgrade policy.

- index.ts
  - Exports: Installation.Service, layer, latest/method/upgrade; export * as Installation from "."
  - Role: Central installation orchestration, including upgrade strategy and source of truth for the current version
- Other: Constants like USER_AGENT, isPreview, isLocal, UpgradeFailedError
- The module uses HTTP, CrossSpawnSpawner, and a runtime to fetch latest versions and perform upgrades

- End of 145-installation.md
