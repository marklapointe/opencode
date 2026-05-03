110-provider.md

Module: Provider subsystem (packages/opencode/src/provider/)

Summary
- The Provider module implements a pluggable provider system for AI models. It wires a registry of provider backends (OpenAI, Anthropic, Vertex AI, Cohere, etc.), dynamic discovery, and model loading with theme-sensible defaults. It also integrates with Auth, Env, and Config layers to surface provider configuration.

Exports and entry points (high level)
- provider.ts: Exposes manager-like APIs for loading providers, mapping language models, and interacting with provider backends. It defines a bundling pattern for dynamic providers, and a set of built-in provider blueprints (openai, anthropic, azure, google, vertex, etc.).
- export * as Provider from "./provider" pattern is used (see bottom of file export).

Key constructs observed in code
- A large mapping of provider backends to dynamic import handlers (BUNDLED_PROVIDERS) to enable lazy-loading of provider SDKs.
- The provider supports autoload behavior for certain providers based on environment/config (e.g., OpenAI, Vertex, GitLab, etc.).
- The code contains helper utilities for loading models, handling env vars, and constructing provider options dynamically.
- It demonstrates complex interaction with the Effect library for dependency-injected runtime composition and per-provider state.

Patterns to note for future mapping
- Dynamic import of provider SDKs and runtime wiring through Effect layers.
- Each provider returns an object with autoload, options, and a getModel callback that loads a model by ID.
- The module uses many utilities for env/config, including iife helpers and a large, nested permission/feature flags system.

End of 110-provider.md
