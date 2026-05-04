# Mapping Group 121
Files: 14

**packages/ui/.gitignore/**
- `.gitignore` →  (26 ln)  [file]

**packages/ui/package.json/**
- `package.json` →  (76 ln)  [json]

**packages/ui/script/**
- `tailwind.ts` →  (23 ln)  [typescript]
  → const colors = await Bun.file(import.meta.dir + "/colors.txt").text()

**packages/ui/src/**
- `accordion.css` →  (123 ln)  [stylesheet]
- `accordion.stories.tsx` → Basic (149 ln)  [typescript]
  → Imports: solid-js
  → imports: solid-js, ../storybook/scaffold
- `accordion.tsx` → Accordion (92 ln)  [typescript]
  → Imports: @kobalte/core/accordion
  → imports: @kobalte/core/accordion, solid-js, solid-js
- `animated-number.css` →  (75 ln)  [stylesheet]
- `animated-number.tsx` → AnimatedNumber (109 ln)  [typescript]
  → Imports: solid-js
  → imports: solid-js, solid-js/store
- `app-icon.css` →  (5 ln)  [stylesheet]
- `app-icon.stories.tsx` → Basic (69 ln)  [typescript]
  → Imports: ./app-icons/types
  → imports: ./app-icons/types, ../storybook/scaffold
- `app-icon.tsx` → AppIcon (85 ln)  [typescript]
  → Imports: solid-js
  → imports: solid-js, solid-js, ./app-icons/types
- `types.ts` → iconNames (21 ln)  [typescript]
  → export const iconNames = [
- `apply-patch-file.test.ts` →  (43 ln)  [test]
- `apply-patch-file.ts` → patchFile (78 ln)  [typescript]
  → Imports: ./session-diff
  → imports: ./session-diff

---
Generated: 2026-05-04 02:45:04Z
