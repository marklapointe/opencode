File: plugin/src/shell.ts

ASCII Tree:

├── [export] type ShellFunction
├── [export] type ShellExpression
├── [export] interface BunShell
├── [export] interface BunShellPromise
├── [export] BunShellOutput
├── [export] BunShellError

Description
- Defines the BunShell interface and related types used to spawn and interact with shell processes.

Data Flow
- Shell is instantiated by the plugin to execute commands and capture outputs.

Side Effects
- None shown in type definitions; runtime may perform I/O when instantiated.
