137-account.md

Directory: src/account/

Overview: Account management subsystem with OAuth/device code login flows, token refresh, and account/org state handling.

- account.ts
  - Exports: AccountInfo types, Account Service Layer, token/login/poll flows, and exports * as Account from "." namespace
  - Role: Handles user accounts, tokens, and org assignments; performs login via device flow and token refresh
- account.sql.ts, url.ts, repo.ts, schema.ts
  - Roles: SQL schema for accounts and persistence, URL normalization, repository logic, and domain types
- The module demonstrates a combination of HTTP client flows and local storage through a repository

- The kit shows DI usage with a layered approach.

End of 137-account.md
