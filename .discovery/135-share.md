135-share.md

Directory: src/share/

Overview: Sharing subsystem enabling session/data sharing across clients via links, including a ShareNext manager and SQL-backed storage table for shares.

- share.sql.ts
  - Exports: SessionShareTable schema for sharing tokens and URLs

- share-next.ts
  - Exports: ShareNext.Service with init/url/request/create/remove flow; wiring to Account, Bus, Config, HttpClient, Provider, Session, etc.
  - Role: Manages share lifecycle, queueing and syncing of session data; supports legacy/console API paths
- The module uses runtime DI, HTTP transports, and a local/global state to coordinate share lifecycles and remote synchronization.

- It also exposes a defaultLayer that wires into Bus, Account, Config, and other subsystems.

End of 135-share.md
