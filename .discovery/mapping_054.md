# Mapping Group 054
Files: 14

## File Tree
**packages/opencode/src/**
  - `openai-compatible-prepare-tools.ts` → prepareTools (83 ln)  [typescript]
    → Imports: @ai-sdk/provider
  - `copilot-provider.ts` → createOpenaiCompatible (100 ln)  [typescript]
    → API key for authenticating requests. /
  - `openai-compatible-error.ts` → openaiCompatibleErrorDataSchema (27 ln)  [typescript]
    → Imports: zod/v4
  - `convert-to-openai-responses-input.ts` → convertToOpenAIResponsesInput (335 ln)  [typescript]
    → Check if a string is a file ID based on the given prefixes Returns false if prefixes is undefined (disables file ID detection) /
  - `map-openai-responses-finish-reason.ts` → mapOpenAIResponseFinishReason (22 ln)  [typescript]
    → Imports: @ai-sdk/provider
  - `openai-config.ts` →  (18 ln)  [typescript]
    → File ID prefixes used to identify file IDs in Responses API. When undefined, all file data is treated as base64 content.
  - `openai-error.ts` → openaiErrorDataSchema (22 ln)  [typescript]
    → Imports: zod/v4
  - `openai-responses-api-types.ts` →  (214 ln)  [typescript]
    → A filter used to compare a specified attribute key to a given value using a defined comparison operation. /
  - `openai-responses-language-model.ts` → ExtractByType (1770 ln)  [typescript]
    → `top_logprobs` request body argument can be set to an integer between 0 and 20 specifying the number of most likely tokens to return at each token pos
  - `openai-responses-prepare-tools.ts` → prepareResponsesTools (173 ln)  [typescript]
    → Imports: @ai-sdk/provider
  - `openai-responses-settings.ts` →  (1 ln)  [typescript]
  - `code-interpreter.ts` → codeInterpreterInputSchema (87 ln)  [typescript]
    → The code interpreter container. Can be a container ID or an object that specifies uploaded file IDs to make available to your code.
  - `file-search.ts` → fileSearchArgsSchema (127 ln)  [typescript]
    → The search query to execute. /
  - `image-generation.ts` → imageGenerationArgsSchema (114 ln)  [typescript]
    → Background type for the generated image. Default is 'auto'. /

---
Generated: 2026-05-03 15:01:00
