File: packages/console/app/src/style/base.css

Tree:
- [config] Root typography and color baseline for the app
- [block] html → line-height: 1; background and text color via CSS variables
- [block] body → font-family via CSS variable
- [block] .sr-only → accessibility helper class for screen-reader only content

Description:
- Establishes core typographic and color defaults used by components and routes.

Data Flow:
- Styles get injected by Vite; CSS variables allow theme-friendly theming across the app.

Side Effects:
- No runtime logic; affects visual rendering and accessibility helpers.
