100-opencode-root.md

Overview: Discovery map for the core OpenCode backend package located at packages/opencode/src. This entry file indexes the primary sub-modules we have begun mapping in this pass and provides links to their individual discovery documents.

- Server module: 110-server.md
- Agent module: 110-agent.md
- Provider module: 110-provider.md

Notes:
- This is an initial pass focusing on the most central modules (server, agent, provider). I will extend with additional sub-modules in subsequent iterations to cover the entire codebase as requested.
- Each discovered file is described with imports, exports, major constructs, and a domain-specific summary based on static analysis of the source.

Dependency graph (high level):
- Server wires the HTTP surface, routes, and middleware, and aggregates backend choices.
- Agent orchestrates AI agents, prompts, policies, and layer-based Effects composition.
- Provider implements pluggable AI providers, model loading, and capability discovery.

How to extend: add new 1XX discovery entries for additional top-level submodules and update this root file accordingly.

End of 100-opencode-root.md
