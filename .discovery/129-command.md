129-command.md

Directory: src/command/

Overview: Command registry and templates used to drive the agent/workflow automation. Supports initializing and reviewing pipelines, as well as templates sourced from MCP prompts and skills.

- index.ts
  - Exports: Command.Info, Command.Service (DI), Command.Event; layer wiring; Default INIT/REVIEW commands; export * as Command from "."
  - Role: Builds a runtime namespace for command templates and simplifies triggering agent workflows
- template/*.txt
  - Descriptions/Content used as defaults for templates
- The module uses a heavy DI pattern via Effect, with dynamic command generation based on config (mcp prompts, skills) and a bootstrapped command set

- Core behavior: commands provide a way to drive agent workflows and trigger subtasks (init, review) in a controlled way

End of 129-command.md
