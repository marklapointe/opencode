File: packages/console/app/src/style/reset.css

Tree:
- [file] reset.css → CSS reset rules for layout consistency
- [block] * and *::before, *::after → box-sizing: border-box
- [block] body → typography defaults (line-height, font-smoothing)
- [block] img, picture, video, canvas, svg → ensure responsive media sizing
- [block] input, button, textarea, select → font inheritance
- [block] headings and paragraphs → text wrapping behavior
- [block] #root, #__next → create a root stacking context

Description:
- Global CSS reset and baseline styles for predictable rendering across routes/components.

Data Flow:
- Styles loaded by Vite/SolidStart app; influences rendering across the TUI web app.

Side Effects:
- Affects visual consistency and accessibility defaults; no runtime logic changes.
