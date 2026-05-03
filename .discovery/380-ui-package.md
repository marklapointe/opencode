Project: packages/ui (Shared UI component library)

Description: Exhaustive tree-view map of all primitives, components, and styling strategies. This is the root for the UI package discovery.

Data Flow Overview:
- UI components export primitive building blocks (buttons, inputs, icons, typography).
- The library provides context providers (theme, i18n, dialog, file, marked) used by the app and docs.
- Styling: Tailwind-derived utility classes and CSS Modules/CSS-in-JS depending on component.
- Icons under assets/icons are used for visual elements across the app/UI.

Directory Map (excerpts, with key files described):

├── [dir] src/
│   ├── [dir] components/ → Shared UI components (Button, Input, Card, Modal, etc.).
│   │   ├── [file] Button.tsx → Accessible button primitive with variants. Props interface defines label, onClick, variant.
│   │   ├── [file] TextInput.tsx → Text input primitive with label, placeholder and validation hooks.
│   │   └── …
│   ├── [dir] context/ → Context providers used by app (Theme, I18n, Dialog, File, Marked).
│   │   ├── [file] theme.ts → Theme context and mode switching (light/dark).
│   │   ├── [file] language.ts → Localization hooks and dictionaries.
│   │   └── …
│   ├── [file] file.tsx → File viewer/handler primitive used by editor-like components.
│   ├── [file] index.tsx → Barrel export aggregating components and contexts for consumption by apps.
│   └── [dir] icons/ → Icon components/paths used across UI building blocks.
├── [file] package.json → Library metadata and build/test scripts.
├── [dir] assets/ → Logo, icons, and fonts used by docs and demos.
├── [dir] styles/ → Global styles and CSS utilities for the UI library.
└── [file] README.md → Overview and usage guidance for the shared UI components.

Notes on cross-package dependencies:
- UI is consumed by packages/app and docs in web for consistent visuals and behavior.
- It integrates with the app via context providers (Theme, Language, Dialog, File, Marked).

End of root ui-package discovery. Detailed per-file maps follow in later sections.
