136-permission.md

Directory: src/permission/

Overview: Permission system for runtime tool access, with evaluation rules, requests, approvals, and bus events.

- index.ts
  - Exports: Action, Rule, Ruleset, Request, Reply, ReplyBody, ReplyInput, AskInput, Event, Interface, Service, layer
  - Role: Central permission engine that evaluates tool usage, asks users for consent, stores approvals, and publishes permission events
- schema.ts
  - Exports: permission schemas re-exported to enable strong typing across modules
- arity.ts, evaluate.ts
  - Roles: helpers for permission evaluation and composing rulesets
- The module demonstrates an explicit evaluation flow and a simple ask/reply protocol.

- Export pattern: export * as Permission from "." used to namespace the permission module

End of 136-permission.md
