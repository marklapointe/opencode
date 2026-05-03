File: packages/console/app/tsconfig.json

Tree:
- [config] { ... } → TS compiler options configuration
- [property] "$schema" → schema URL for TS config validation
- [property] compilerOptions → core TS options
- [option] target: "ESNext" → output language level
- [option] module: "ESNext" → module system for bundling
- [option] skipLibCheck: true → speed up type-check by skipping library checks
- [option] moduleResolution: "bundler" → module resolution strategy for bundlers
- [option] allowSyntheticDefaultImports: true → allow default imports from non-ES modules
- [option] esModuleInterop: true → compat with non-ES module default imports
- [option] jsx: "preserve" → preserve JSX in output
- [option] jsxImportSource: "solid-js" → JSX pragma source for SolidJS
- [option] allowJs: true → allow JS files to be compiled
- [option] strict: true → enable all strict type-checking options
- [option] noEmit: true → TS compiler does not emit JS files (useful for type-checking only)
- [option] types → ["vite/client", "@webgpu/types"] → ambient type declarations
- [option] isolatedModules: true → ensure each file can be transpiled independently
- [option] paths: { "~/*": ["./src/*"] } → path alias mapping

Description:
- This TS config sets up strict TypeScript checks with SolidJS JSX support and path aliasing for the app.

Data Flow:
- Used by TypeScript tooling (typecheck, IDEs) to resolve modules and types. Works with Vite build.

Side Effects:
- No runtime side effects; purely build/type-check configuration.
