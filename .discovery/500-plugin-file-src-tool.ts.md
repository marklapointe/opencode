File: plugin/src/tool.ts

ASCII Tree:

├── [import] { z } from "zod"
├── [import] { Effect } from "effect"
├── [export] type ToolContext
├── [export] type ToolResult
├── [export] function tool<Args extends z.ZodRawShape>(input: { description: string; args: Args; execute: (args: z.infer<z.ZodObject<Args>>, context: ToolContext) => Promise<ToolResult> }): { /* ... */ }
├── [export] const tool: <Args extends z.ZodRawShape>(...) => { ... as defined }
├── [export] type ToolDefinition

Description
- Utility to declare server-side tools that plugins can expose to the host.

Data Flow
- Tool definitions declare arguments, validation and execution logic.

Side Effects
- None at declaration time; tools may execute in response to user actions.
