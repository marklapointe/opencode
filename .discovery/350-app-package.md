Project: packages/app (SolidJS web app frontend)

Description: Exhaustive tree-view map of all source files, routes, components, stores, and tests. This is the root for the app package discovery.

Data Flow Overview:
- App shell provides global providers (Theme, Language, Query, etc.).
- Router configuration wires routes to pages and dynamic components.
- Stores/providers manage global state (server connections, settings, etc.).
- Playwright tests exercise E2E flows against the dev server and backend.
- Integrations: Sentry for error reporting, Tailwind for styling, TanStack Query for data fetching.

Directory Map (excerpts, with key files described):

├── [config] vite.config.ts → Vite config for the SolidJS app; includes plugins and server options.
├── [dir] src/
│   ├── [dir] context/ → React-like context/providers for app state (server, language, settings, etc.).
│   │   ├── [file] server.ts → Server state/type definitions and health checks.
│   │   ├── [file] language.ts → Localization utilities and locale handling.
│   │   ├── [file] command.ts → Command handling context for the prompt system.
│   │   └── … (additional providers)
│   ├── [dir] pages/ → Route components for the app (home, session, layout, etc.).
│   │   ├── [file] home.tsx → Home page component.
│   │   ├── [file] directory-layout.tsx → Directory view layout wrapper.
│   │   ├── [file] session.tsx → Session page with sub-routing.
│   │   └── [file] error.tsx → Global error page component.
│   ├── [dir] components/ → UI composition components for app pages.
│   │   ├── [file] header.tsx → Top navigation header.
│   │   ├── [file] prompt-input.tsx → Prompt input UI component.
│   │   └── …
│   ├── [file] entry.tsx → App bootstrap entry for rendering the app to DOM.
│   ├── [file] index.css → Global styles.
│   └── [dir] tests/ → Playwright end-to-end test suites and unit tests.
├── [file] package.json → NPM scripts for dev/build/test; tooling.
├── [file] README.md → App package overview and quick start.
└── [file] tsconfig.json → TypeScript configuration for SolidJS project.

Notes on cross-package dependencies:
- App relies on UI library components under packages/ui for shared UI primitives.
- It uses Vite + TailwindCSS for styling, and TanStack Query for data fetching/state.
- Playwright tests target the app and require a backend at 4096 by default as per docs.

End of root app-package discovery. Detailed per-file maps follow in subsequent sections.
