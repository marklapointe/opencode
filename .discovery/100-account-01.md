OPENCode (Account module) discovery - file: src/account/account.ts

Imports (with pointers to discovery nodes):
├── [import] Cache, Clock, Duration, Effect, Layer, Option, Schema, SchemaGetter, Context from "effect" → .discovery/190-effect.md
├── [import] {
  FetchHttpClient,
  HttpClient,
  HttpClientError,
  HttpClientRequest,
  HttpClientResponse,
} from "effect/unstable/http" → .discovery/190-effect.md
├── [import] { withTransientReadRetry } from "@/util/effect-http-client" → .discovery/???.md
├── [import] { AccountRepo, type AccountRow } from "./repo" → .discovery/100-account-02.md
├── [import] { normalizeServerUrl } from "./url" → .discovery/100-account-03.md
├── [import] {
  type AccountError,
  AccessToken,
  AccountID,
  DeviceCode,
  Info,
  RefreshToken,
  AccountServiceError,
  AccountTransportError,
  Login,
  Org,
  OrgID,
  PollDenied,
  PollError,
  PollExpired,
  PollPending,
  type PollResult,
  PollSlow,
  PollSuccess,
  UserCode,
} from "./schema" → .discovery/100-account-04.md

Exports (re-exports and local exports):
├── [export] AccountID
├── [export] type AccountError
├── [export] AccountRepoError
├── [export] AccountServiceError
├── [export] AccountTransportError
├── [export] AccessToken
├── [export] RefreshToken
├── [export] DeviceCode
├── [export] UserCode
├── [export] Info
├── [export] Org
├── [export] OrgID
├── [export] Login
├── [export] PollSuccess
├── [export] PollPending
├── [export] PollSlow
├── [export] PollExpired
├── [export] PollDenied
├── [export] PollError
├── [export] PollResult
├── [export] interface AccountOrgs
├── [export] type ActiveOrg
├── [export] class Service
├── [export] const layer
├── [export] const defaultLayer
├── [export] * as Account from "./account" → .discovery/100-account-01.md (self-export namespace)

Self-export namespace pattern:
- The file ends with a self-export: export * as Account from "./account" which exposes a namespace named Account that contains all Account-related exports. This mirrors the multi-file namespace pattern used across the codebase for consistent imports.

Code semantics (high level):
- The module defines domain types for accounts, tokens, orgs, and OAuth device flow (DeviceCode/Login/PollX) used by the CLI and remote account services.
- The Service class provides the Account service surface; layer wires DB and HTTP clients and exposes API methods like active, list, login, poll, config, token.
- Exports re-export a large set of schema-defined types from ./schema for convenient imports.

Notes:
- This file heavily relies on Effect v4 primitives for composition and Layer wiring. See linked discovery for other core primitives such as Effect, Schema, and Layer.

Related modules:
- 100-account-02.md (repo.ts)
- 100-account-03.md (url.ts)
- 100-account-04.md (schema.ts)
