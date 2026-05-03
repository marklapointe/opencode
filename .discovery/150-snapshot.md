150-snapshot.md

Directory: src/snapshot/

Overview: Snapshot management for code/state, including patch/diff generation, apply/restore of repository snapshots, and history tracking.

- index.ts
  - Exports: Snapshot.Service, Snapshot.layer, Patch, FileDiff, FileDiff, History-related types
- snapshot/index.ts
  - Role: Implements the snapshot engine to track changes, store diffs, and apply/rollback patches
- Other: patch.ts defines patchable hunks; content readers/writers for diff content

- It uses a git backend, path hashing, and a stateful runtime to manage snapshots per workspace and worktree

End of 150-snapshot.md
