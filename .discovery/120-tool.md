120-tool.md

Directory: src/tool/

ASCII Tree (representing major files and their exported shapes)

- truncation-dir.ts
  - Exports: TRUNCATION_DIR (const) – path for tool output cache

- truncate.ts
  - Exports: MAX_LINES, MAX_BYTES, DIR, GLOB, Result (union), Interface, Service, layer, defaultLayer
  - Role: Core service to cap tool output length and manage a retention queue

- write.ts
  - Exports: WriteTool, Parameters
  - Role: Writes content to disk with diff, LSP touch/diagnostics, and file watcher updates

- webfetch.ts
  - Exports: WebFetchTool, Parameters
  - Role: Fetches a URL, supports formats, handles content-type and HTML/text extraction

- websearch.ts
  - Exports: WebSearchTool, Parameters
  - Role: Web search integration via EXA/MCP, returns structured results

- webfetch.txt, websearch.txt, write.txt, task.txt, skill.txt, etc.
  - Descriptive help texts used in runtime tool descriptions

- tool.ts
  - Exports: Tool, ToolRegistry surface, core Tool definition primitives
  - Role: Base concept for building tool instances used by runtime

- registry.ts
  - Exports: ToolRegistry, layer (composition of builtin tools and plugin tools)
  - Role: Builds available/tools for a given provider/model/agent

- question.ts
  - Exports: QuestionTool

- task.ts
  - Exports: TaskTool
  - Role: Creates tasks that spawn subagents and track task state

- read.ts
  - Exports: ReadTool

- write, patch, glob, grep, lsp, plan, etc. (several more modules)

-  Additional files ending with .txt provide tool descriptions used at runtime

Notes:
- This file provides a quick tour; each real file contains complex implementation details such as Effect-based services, DI layers, and runtime wiring. See individual modules for exact behavior.

End of 120-tool.md
