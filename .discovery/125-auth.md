125-auth.md

Directory: src/auth/

Overview: Auth subsystem provides provider-based authentication configuration and per-provider credentials management via a pluggable interface.

- index.ts
  - Exports: OAUTH_DUMMY_KEY constant; Auth.Info schema; AuthError; Service interface; layer; defaultLayer; export * as Auth from "."
  - Role: Defines authentication models for OAuth, API keys, and well-known tokens; provides a runtime service to access and mutate credentials

- The file demonstrates a self-export pattern: export * as Auth from "." to expose the Auth namespace

- Key concepts:
  - Oauth, Api, WellKnown classes with discriminated union for Auth.Info
  - AuthError tagged error and resolution logic
  - Service with methods: get, all, set, remove

End of 125-auth.md
