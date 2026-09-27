# Aptlantis QBasic

Aptlantis QBasic is a dark SiYuan theme derived from the Aptlantis QBasic palette, combining deep midnight-blue structural tones with electric blue, cyan, and magenta accents.

The workspace uses deep navy and obsidian surfaces (`#091222`, `#060C1B`, `#010102`) for a calm, high-contrast reading canvas. Accents are mapped to distinct interface roles: bright and cobalt blues for primary focus, navigation, and scrollbars; vibrant magenta for secondary interactions, keywords, and callouts; warm cream for links and titles; and icy cyan for strings and inline highlights. Panels, toolbars, breadcrumbs, tables, menus, and the editor retain clear structural hierarchy across light and dark display contexts.

## Source Material

- Color specification: `palette.toml` (processed via `siyuan-theme-builder`)
- Color spaces: OKLCH perceptual color definitions with sRGB hex fallbacks for broad compatibility.

The syntax palette translates the palette hues directly into SiYuan's native Highlight.js roles instead of introducing a competing JavaScript highlighter.

## Package Files

- `theme.json`: SiYuan package metadata
- `theme.css`: reference colors, semantic roles, SiYuan variables, and component styling
- `icon.png`: marketplace icon
- `preview.png`: marketplace preview
- `README.md`: theme documentation
- `License`: licensing terms

## Semantic Anchors

- App background / chassis: `#091222`
- Editor surface: `#060C1B`
- Panels, menus & dialogs: `#010102`
- Raised surface: `#001766`
- Structural border: `#706B71` / `#33528C`
- Primary blue: `#0672CC`
- Secondary / error magenta: `#CD5DE6`
- Warning / bright blue: `#0A92EE`
- Scrollbar / data cyan: `#4FADF8`
- Link / function cream: `#F7EBD1`
- String icy cyan: `#C7F8FC`
- Reading text: `#FDFDFC`
- Soft text: `#B3ACAF`
- Muted text: `#8F8B91`

## Design Rule

Deep navy and dark neutrals carry structure; saturated blues and crisp magenta accents communicate state, interactive cues, and editorial meaning. Aptlantis QBasic is intentionally a single dark theme.

## Compatibility

The theme follows the SiYuan 3.7+ / 3.8+ theme-variable and selector contract and uses only `theme.css`; the deprecated `theme.js` entry point is not included. Restart SiYuan after replacing an installed copy because the kernel may cache theme assets.
