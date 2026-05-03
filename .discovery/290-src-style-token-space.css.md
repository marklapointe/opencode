File: packages/console/app/src/style/token/space.css

Tree:
- [type] body → defines a large set of CSS custom properties for spacing and radii
- [variable] --space-<n> → spacing scale (px/rem values)
- [variable] --border-radius-<size> → border radii scale

Description:
- Centralizes layout spacing tokens used by components.

Data Flow:
- Consumed by components to ensure consistent margins/padding and border radii.

Side Effects:
- Visual impact only; no runtime logic.
