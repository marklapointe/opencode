140-effect.md

Directory: src/effect/

Overview: Core Effect v4 based runtime and utilities including run service, bridge, instances, and bootstrap runtime.

- app-runtime.ts, bootstrap-runtime.ts
  - Roles: Setup runtime environment and bootstrapping of effects
- run-service.ts
  - Exports: makeRuntime, attach, attachWith
  - Role: Provides a tiny DI-friendly runtime for Effect-based services
- bridge.ts
  - Exports: Shape interface and make() runtime bridge to allow cross-context interactions
- instance-registry.ts, instance-ref.ts, instance-state.ts
  - Roles: Instance/state management for DI scopes and workspace instance
- other: effect/util, etc.

- The effect layer uses layered providers and observability integration to build a robust dependency graph for the monorepo.

End of 140-effect.md
