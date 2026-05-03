134-sync.md

Directory: src/sync/

Overview: Sync subsystem for event-sourced state replay and projection, bridging projectors with bus events. It includes a SyncEvent runtime, registry, and tooling for replaying events with optional bus publishing for compatibility.

- index.ts
  - Exports: SyncEvent surface (definition, run, replay, etc.) and a registry of event definitions
  - Role: Core entry for syncing events and projectors; implements versioned event typing and replay flow
- event.sql.ts, schema.ts
  - Role: SQL schema definitions for storing sync event metadata and event shapes
- README.md
  - Description: Documentation for the SyncEvent system, examples, and usage notes
- The module heavily uses the Effect library, Layer composition, and a micro runtime (makeRuntime) to coordinate event replay and projection.

End of 134-sync.md
