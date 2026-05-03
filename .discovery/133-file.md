133-file.md

Directory: src/file/

Overview: File system abstraction for OpenCode including a file browser, reading/writing files with patch previews, and diff generation.

- index.ts
  - Exports: File.Info, Node, Content, Event; Service with init/status/read/list/search; layer wiring
  - Role: Exposes a file management API for the current workspace including reading, listing, and patch diffs

- ripgrep.ts
  - Exports: Ripgrep.Service; helper for fast file search
- protected.ts, ignore.ts, watcher.ts
  - Roles: Protected names, ignore rules, and file watching logic for live updates
- Other: Node tree of  data structures for File.Content, File.Node, File.Info and events

- The module is heavily DI-driven with a central File.Service that scans workspace, reads git diff, and formats patch output

End of 133-file.md
