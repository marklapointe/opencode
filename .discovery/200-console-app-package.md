Package discovery: packages/console/app

- Path: packages/console/app/
  - vite.config.ts
  - tsconfig.json
  - .gitignore
  - package.json
  - src/
    - style/
      - reset.css
      - base.css
      - index.css
      - token/
        - color.css
        - font.css
        - space.css
    - routes/
      - zen/
        - util/
          - stickyProviderTracker.ts
          - trialLimiter.ts
          - provider/
            - provider.ts
            - openai-compatible.ts
            - openai.ts
        - v1/
          - responses.ts
          - models.ts
        - index.tsx
      - workspace/
        - common.tsx
        - index.tsx
        - workspace-picker.tsx
      - legal/
        - terms-of-service/index.tsx
        - privacy-policy/index.tsx
      - index.tsx
      - … (additional route files in src/routes)
    - middleware.ts
    - lib/
      - changelog.ts
      - github.ts
      - language.ts
      - salesforce.ts
      - form-error.ts
    - i18n/
      - en.ts
      - fr.ts
      - de.ts
      - ja.ts
      - index.ts
    - entry-server.tsx
    - global.d.ts
    - config.ts
    - component/legal.tsx
    - api/enterprise.ts
    - sitemap generation script (script/)

Notes:
- This root map provides a coarse directory tree with links to major source groups. Each file is intended to be mapped in subsequent 2XX discovery files (e.g., 210-<slug>.md) with an ASCII tree describing imports/exports, components, routes, hooks, stores, and styles.
- Cross-package dependencies observed in package.json: @opencode-ai/console-core, @opencode-ai/ui, @opencode-ai/console-mail, @opencode-ai/console-resource, plus Stripe and Nitro/Vite tooling.
- This document is the primary entry describing location and scope of the console app package.

Description, Data Flow, and Side Effects sections are provided per-file in subsequent documents (MUST DO steps).

Generated: initial package root mapping. Will be extended with per-file trees in 210/220/230-series files as we read each file.
