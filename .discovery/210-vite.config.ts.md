File: packages/console/app/vite.config.ts

Tree:
- [import] { defineConfig, PluginOption } from "vite" → imports Vite API and type
- [import] { solidStart } from "@solidjs/start/config" → SolidStart integration for Vite
- [import] { nitro } from "nitro/vite" → Nitro integration for serverless/cloudflare
- [config] export default defineConfig({ ... }) → Vite config wrapper
- [config] plugins: [ ... ] → array of plugin invocations
- [function] solidStart({ middleware: "./src/middleware.ts" }) as PluginOption → configures SolidStart middleware path
- [function] nitro({ compatibilityDate: "2024-09-19", preset: "cloudflare_module", cloudflare: { nodeCompat: true } }) → Nitro wrapper for Cloudflare module env
- [config] server: { allowedHosts: true } → dev server hostname allowances
- [config] build: { rollupOptions: { external: ["cloudflare:workers"] }, minify: false } → build customization
- [side-effect] This file wires SolidStart with Nitro for Cloudflare deployment and sets server/build options

Description:
- Establishes Vite config for a SolidStart app served via Nitro with Cloudflare presets. It marks cloudflare workers as external, preventing bundling, and disables minification for development parity.

Data Flow:
- During dev/build, Vite loads this config to assemble the server bundle, plugin hooks, and build pipeline. SolidStart adds middleware, Nitro handles serverless deployment, and Cloudflare preset optimizes runtime for CF workers.

Side Effects:
- Configures global server options and externalizes CF Workers via Nitro. Affects dev server routing and production deploy footprint.
