File: packages/console/app/src/style/token/color.css

Tree:
- [type] :root → defines CSS custom properties for light/dark themes
- [variable] --color-bg → background color
- [variable] --color-text → primary text color
- [variable] --color-accent → primary action color
- [variable] --color-border, --color-border-muted → borders
- [variable] color palette for success/warning/danger
- [media] @media (prefers-color-scheme: dark) → dark theme overrides

Description:
- Centralized color tokens used by the app's theme system.

Data Flow:
- Other CSS files reference these CSS vars for consistent styling.

Side Effects:
- Affects theming; runtime style resolution depends on user/system color scheme.
