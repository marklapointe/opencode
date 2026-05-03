124-project.md

Directory: src/project/

Overview: Core project management domain. Exposes Project service for loading, updating, listing projects, and interacting with version control (git) surfaces and workspace state.

- bootstrap.ts
  - Exports: InstanceBootstrap (Effect) that boots bootstrapped services, initializations, and preloads several components.
  - Role: Orchestrates startup bootstrap of project subsystem during workspace init

- project.ts
  - Exports: Info type (Project Info), Event (Updated), Layer: Service with fromDirectory, discover, list, get, update, initGit, setInitialized, sandboxes, addSandbox, removeSandbox
  - Role: Main business logic for project lifecycle, discovery, and Git integration

- vcs.ts
  - Exports: Info, FileDiff, Interface, Service, events, and Layer for VCS integration (git status/diff)
  - Role: Encapsulates Git-based project state and diffs

- project.sql.ts
  - (SQL schema for Project table) describes database structure used by Drizzle ORM

- schema.ts
  - Re-exports: ProjectTable and related types from project.sql
- instance.ts
  - (Project instance manager) ties into workspace/project lifecycle
- (Additional: project.bootstrap imports many runtime modules and wires DI)

- Virtual API pattern: The module follows Effect-based DI with Layer wiring and uses export * as Project from "./project" at bottom

End of 124-project.md
