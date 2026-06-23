# Dharshan // Single SVG README Preview

This is a preview document showcasing the single SVG README design.

## Live SVG Render

![Dharshan's Single SVG README](./assets/readme-single.svg)

---

## How it works

1. **Theme-Awareness**: The SVG uses `@media (prefers-color-scheme: dark)` media queries to read the viewer's GitHub appearance preferences and dynamically switch between cold luxury off-black (`#09090b`) and off-white (`#fafafa`) canvas backgrounds, text colors, and code highlighting blocks.
2. **Animation**: Built-in CSS keyframes handle micro-motions, such as the pulsing compiler optimization state indicator node.
3. **Typography**: Uses system-native monospace stacks (`JetBrains Mono`, `Geist Mono`, `SFMono-Regular`, `Consolas`) to render sharp, readable code and text outputs without external web font dependencies (which GitHub blocks due to CSP).
4. **Layout**: Uses absolute coordinate alignments for maximum compatibility across all markdown renders (including mobile devices and browsers with incomplete `<foreignObject>` implementations).
