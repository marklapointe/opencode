146-patch.md

Directory: src/patch/

Overview: Patch application engine that parses patch text into hunks and applies to file system; supports add/delete/update operations with diff generation and BOM handling.

- index.ts
  - Exports: PatchSchema, ApplyPatchArgs, Hunk, ApplyPatchAction, Patch types; functions parsePatch and applyPatch
- Helper functions: parsePatchHeader, parseUpdateFileChunks, parseAddFileContent, deriveNewContentsFromChunks, applyHunksToFiles, generateUnifiedDiff
- The module implements a patch DSL to apply diffs to repository files; includes CLI-based and programmatic API surfaces

- It exports * as Patch from "." to provide a namespace for patch utilities

End of 146-patch.md
