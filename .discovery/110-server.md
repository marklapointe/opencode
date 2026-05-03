110-server.md

Module: Core HTTP server (packages/opencode/src/server/)

Summary
- The server module is the runtime surface for the back-end REST/WS API built on top of the Hono framework. It wires the backend selection, applies middleware, registers routes, and can generate an OpenAPI spec for the exposed API.

Exports and entry points (high level)
- server.ts: Exports Default, openapi(), listen(), Legacy(), and a small internal create() flow. It also re-exports its internal server surface via a final line export * as Server from "./server" which points to a submodule in this folder.
- adapter.node.ts: Bun/Node adapter for running Hono-based apps with Node.js, exposes adapter and createFetch helpers.
- mdns.ts: Simple mDNS publishing utility used to advertise the HTTP service on the local network.
- middleware.ts: Central middleware definitions including Auth, Logger, CORS, Compression, and Error handling.
- projectors.ts: Initialization glue for any server-side projectors used by the runtime.
- routes/ui.ts: UI proxy/routes that either serve embedded UI assets or proxy to a remote upstream UI.
- routes/global.ts: Global routes that are mounted on the root path and handle system-wide endpoints.
- routes/instance/*: Instance-scoped routes for workspace context, including HTTP API handlers for various resources.
- workspace.ts: Context wiring for workspace-scoped logic and routing for the main server.
- backend.ts: Core runtime backend selector and related helpers used to switch between hono-based and effect-based HTTP layers.
- routes/control/*. ts: Control-plane related routes for the admin/control plane surface.
-cors.ts: CORS options typing and helpers used by the HTTP surface.

Architecture notes (based on static analysis)
- The module uses Hono to build the HTTP app, then uses an adapter to expose either a Hono-based surface or an Effect-based surface via a runtime chooser.
- It enables OpenAPI generation via hono-openapi in openapi().
- It supports mDNS advertisement when mdnsDomain is provided and the port is bound to a non-loopback hostname.
- A layered approach is used: Default, create, and Legacy paths to bootstrap different runtimes.

Key imports (examples)
- Import patterns show a mix of:
  - External: hono, hono-openapi, node-ws, node-wsSocket, bonjour-service
  - Internal: ./mdns, ./middleware, ./routes, ./workspace, ./backend, ./cors

Social/structure notes: The server ends with a re-export of its submodule: export * as Server from "./server".

File-level mapping and references (selected files)
- packages/opencode/src/server/server.ts — main server bootstrap and route wiring (see OpenAPI and listen entry points).
- packages/opencode/src/server/adapter.node.ts — Bun/Node adapter implementing listen and createFetch.
- packages/opencode/src/server/mdns.ts — mDNS advertisement helpers.
- packages/opencode/src/server/middleware.ts — composition of Auth, Logger, CORS, Compression and Error handling middlewares.
- packages/opencode/src/server/routes/ui.ts — UI proxy/serving logic, including embedded UI support and upstream proxying.

How to extend discovery (pattern used)
- To extend this file, add new discovered submodules under packages/opencode/src/server/ and create a corresponding .discovery/110-<name>.md documenting the new module. Then reference it from 100-opencode-root.md.

End of 110-server.md
