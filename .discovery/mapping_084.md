# Mapping Group 084
Files: 14

**packages/opencode/src/**
- `openai-compatible-metadata-extractor.ts` →  (44 ln)  [typescript]
  → /
  → imports: @ai-sdk/provider
- `openai-compatible-prepare-tools.ts` → prepareTools (83 ln)  [typescript]
  → Imports: @ai-sdk/provider
  → imports: @ai-sdk/provider
- `copilot-provider.ts` → createOpenaiCompatible (100 ln)  [typescript]
  → API key for authenticating requests. /
  → imports: @ai-sdk/provider, @ai-sdk/provider-utils, ./chat/openai-compatible-chat-language-model
- `openai-compatible-error.ts` → openaiCompatibleErrorDataSchema (27 ln)  [typescript]
  → Imports: zod/v4
  → imports: zod/v4
- `convert-to-openai-responses-input.ts` → convertToOpenAIResponsesInput (335 ln)  [typescript]
  → Check if a string is a file ID based on the given prefixes Returns false if prefixes is undefined (disables file ID detection) /
  → imports: @ai-sdk/provider, @ai-sdk/provider-utils, zod/v4
- `map-openai-responses-finish-reason.ts` → mapOpenAIResponseFinishReason (22 ln)  [typescript]
  → Imports: @ai-sdk/provider
  → imports: @ai-sdk/provider
- `openai-config.ts` →  (18 ln)  [config]
- `openai-error.ts` → openaiErrorDataSchema (22 ln)  [typescript]
  → Imports: zod/v4
  → imports: zod/v4, @ai-sdk/provider-utils
- `openai-responses-api-types.ts` →  (214 ln)  [typescript]
  → A filter used to compare a specified attribute key to a given value using a defined comparison operation. /
  → imports: @ai-sdk/provider
- `openai-responses-language-model.ts` →  (1770 ln)  [typescript]
  → `top_logprobs` request body argument can be set to an integer between 0 and 20 specifying the number of most likely tokens to return at each token position, each with an associated log probability.
  → imports: @ai-sdk/provider, @ai-sdk/provider-utils, zod/v4
- `openai-responses-prepare-tools.ts` → prepareResponsesTools (173 ln)  [typescript]
  → Imports: @ai-sdk/provider
  → imports: @ai-sdk/provider, ./tool/code-interpreter, ./tool/file-search
- `openai-responses-settings.ts` →  (1 ln)  [typescript]
- `code-interpreter.ts` → codeInterpreterInputSchema (87 ln)  [typescript]
  → The code interpreter container. Can be a container ID or an object that specifies uploaded file IDs to make available to your code.
  → imports: @ai-sdk/provider-utils, zod/v4
- `file-search.ts` → fileSearchArgsSchema (127 ln)  [typescript]
  → The search query to execute. /
  → imports: @ai-sdk/provider-utils, ../openai-responses-api-types, zod/v4

---
Generated: 2026-05-04 02:45:04Z
