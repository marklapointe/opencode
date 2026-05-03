File: packages/console/app/package.json

Tree:
- [type] "module" → module type for ESM
- [property] name: "@opencode-ai/console-app" → package name
- [property] version: "1.14.31" → version
- [property] scripts → development/build commands
- [script] dev: "vite dev --host 0.0.0.0" → dev server
- [script] dev:remote → remote dev environment bootstrap
- [script] build → sitemap, vite build, and schema generation
- [script] start → vite start
- [property] dependencies → runtime dependencies including console-core, console-mail, console-resource, ui, Stripe, Nitro, SolidJS, etc.
- [property] devDependencies → TypeScript/native-preview, webgpu types, wrangler, etc.
- [property] engines → Node >= 22

Description:
- Central manifest for the console app; defines dev/build scripts and package dependencies across the OpenCode monorepo workspace.

Data Flow:
- Build and tooling behavior is driven by these scripts; workspace: references indicate cross-package dependencies resolved at install time.

Side Effects:
- Affects how the app is built, started, and deployed; no runtime logic inferred here beyond script orchestration.
