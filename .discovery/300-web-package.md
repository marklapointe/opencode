Project: packages/web (Astro + Starlight docs site)

Description: Exhaustive tree-view map of all source files, docs content, config, and integrations. This file is the root for the web package discovery and will be split into multiple sections if needed to stay under line limits.

Data Flow Overview:
- Astro config wires the site, adapters, and plugins to build the documentation site.
- Docs content under src/content/docs are exposed as routes via Astro pages.
- i18n and locales drive multilingual docs rendering through Starlight + the docs theme.
- Styles and assets are imported by components/global layout and content markup.
- Cloudflare adapter handles deployment specifics for hosting the docs site.

Directory Map (excerpts, with key files described):

├── [config] astro.config.mjs → Astro configuration with Starlight, SolidJS, and Cloudflare adapter. Sets base to /docs, includes customCss, and defines the docs sidebar and plugins.
├── [config] config.mjs → Central runtime configuration for docs site (url, github, headerLinks, etc.).
├── [config] package.json? (build tooling manifests) → project metadata and scripts for building docs site.
├── [dir] src/
│   ├── [dir] assets/ → static assets (lander screenshots, logos, icons) used by docs UI.
│   ├── [dir] content/ → content assets for docs site (docs, translations, etc.).
│   │   ├── [dir] docs/ → markdown/mdx docs in multiple locales. These files render as docs pages in the site.
│   │   │   ├── [tr] /[path].mdx → Turkish docs for various topics.
│   │   │   ├── [other-locale] … → localized versions of docs content.
│   │   ├── [dir] i18n/ → locale JSON/translation sources for docs content.
│   │   │   ├── en.json, zh-CN.json, etc.
│   ├── [file] i18n/locales.ts → Type definitions and locale mappings for docs rendering.
│   ├── [file] src/styles/custom.css → Global styles for doc site. Imported by astro.config.mjs.
│   ├── [file] src/assets/logo-*.svg → Branding assets used by layout header.
│   └── [dir] content/docs/ → collection of md/mdx docs used to generate routes.
├── [file] README.md → Documentation for the web package itself (how to run/build docs).
└── [dir] package-lock.json / pnpm-lock.yaml? → dependency lock files (if present).

Notes on cross-package dependencies:
- web depends on opencode docs theme and Starlight integration for multilingual docs and theming.
- It also consumes the backend content config via config.mjs for endpoint references.
- The Cloudflare adapter is tuned for deployment; no runtime changes to docs content are required.

For each file, a dedicated per-file ASCII map is generated in subsequent sections of this discovery file. This root entry serves as the anchor for those mappings and cross-package references.

Description, Data Flow, Side Effects:
- Description: The docs site compiles markdown/mdx into static routes, enriched with i18n, theming, and a navigation sidebar.
- Data Flow: Docs MDX -> Astro routing -> Starlight components (Tabs, etc.) -> Generated HTML.
- Side Effects: Build-time transform of markdown to HTML; no runtime network calls from docs pages beyond asset loading.

Cross-Package Dependencies:
- web -> config.mjs (site URLs, GitHub, etc.).
- web -> src/content/docs/* for routing content.
- web -> /docs/ assets used in UI components.

End of root web-package discovery. Detailed per-file maps follow in additional sections.
