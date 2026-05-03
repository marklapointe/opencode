OpenCode opencode tool subsystem discovery - directory: src/tool

Overview: The tool subsystem contains the core framework for defining ad-hoc commands used by the CLI and automation. It heavily relies on Effect v4 for composition and provides a domain for creating reusable, parameterized tools.

Files (selected important ones):
├── [export] BashTool (exported in bash.ts) – a concrete tool that executes shell commands via a Bash-like interface with streaming output.
├── [export] Tool (from tool.ts) – core tool-building primitives and the define wrapper used to create new tools.
├── [export] Parameters (in bash.ts) – the schema describing command parameters (command, timeout, workdir, description).
├── [export] Run/Plan/Write utilities (truncate.ts, truncate API) – output truncation and long-running IO helpers.
├── [export] other core utilities (read.ts, write.ts, glob.ts, lsp.ts, websearch.ts, webfetch.ts, registry.ts, task.ts, schema.ts).

Core behavior notes (high level):
- define(...) creates an Effect-driven tool descriptor with schema-based parameter parsing and a wrap() closure that handles argument decoding, tracing, and truncation.
- BashTool demonstrates a complex command runner that parses commands with Tree-sitter, expands variables, streams output, and enforces timeouts and cancellation.
- The Tool namespace is exported for consumers to access helper components and common types.

Cross-module references and imports:
- bash.ts imports Config, Shell, Truncate, Plugin, and others to wire runtime behavior. See 190-effect.md for core Effect primitives and 330 BashTool usage.
- utils such as websearch.ts and webfetch.ts rely on web fetch utilities and patterns for external data access.

Notes on discovery linking:
- This document links to the per-file discovery entries below whenever they exist. If a file becomes long, split its tree across additional 100-XX files as needed (per the root discovery rules).

Related modules:
- 100-account-01.md for a view of how a module can be composed with Tool-level integration
- Other per-file maps will be added under 110- sub-nodes as they are created.
