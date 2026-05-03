110-agent.md

Module: Agent subsystem (packages/opencode/src/agent/)

Summary
- The Agent module implements the core agent lifecycle, configuration, and generation logic. It defines an Agent Service with a layered Dependency Injection pattern via Effect v4, and exposes a defaultLayer that wires Config, Auth, Plugin, Provider, Skill, and others into a runtime guest environment.

Exports and entry points (high level)
- agent.ts: Exports Info type, Interface, and a Service that uses Context.Service. It defines a Layer (layer) that constructs a complex state machine for agents, including a large default agent registry (build, plan, general, explore, etc.). It returns a Service interface with get, list, defaultAgent, and generate methods.
- defaultLayer: Combines multiple Service layers to provide a fully wired Agent runtime.
- export * as Agent from "./agent" (re-export pattern at the bottom of the file)

Key constructs observed in code
- Self-contained Info schema describing agent configuration (name, mode, permissions, prompts, etc.).
- Layer-based composition: builds an initial state with defaults, permissions, and whitelisted directories; then exposes get/list/defaultAgent/generate APIs.
- generate(input): uses a configured provider language, prompts the AI to generate an agent configuration, handles OpenAI oauth vs non-oauth paths, and supports streaming via streamObject when necessary.
- Exports a service that can be consumed by other modules (e.g., provider, config, skill, etc.).

Notable patterns and patterns to map later
- The module uses Effect.gen, Layer, and Context from the Effect library, and relies on other DI services via yield* to fetch Config, Auth, Plugin, Skill, Provider, etc.
- It demonstrates a large data-driven defaults map for built-in agents and programmatic customization for user-defined agents.
- It ends with: export defaultLayer = layer.pipe(...) and a re-export of Agent namespace: export * as Agent from "./agent".

Representative code points (from agent.ts)
- Info schema, Interface with get/list/defaultAgent/generate, and a large Layer.effect that wires builder state and exports a Service instance.
- The generate path calls the AI to generate a new agent configuration JSON, with a strict schema and validation via zod. It then constructs a new agent descriptor with fields like identifier, whenToUse, systemPrompt.

End of 110-agent.md
