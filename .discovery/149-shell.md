149-shell.md

Directory: src/shell/

Overview: Shell helper utilities with recognition of default shells, login shells, and a list API for available shells.

- shell.ts
  - Exports: Item type, functions list(), login(), name(), login, posix, ps, etc.; preferred/acceptable wrappers
- index.ts
  - Exports: Shell namespace alias; export * as Shell from "."
- The module includes meta data for a variety of shells and resolves an appropriate login shell to spawn commands.

End of 149-shell.md
