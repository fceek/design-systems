# Design System

## 1. Structure & Layout

- Density: Spacious — whitespace as the primary grouping mechanism
- Corners: Sharp by default; soft radii only where functional (pills, toggles)
- Section patterns: Single-plane — everything on one surface, no card stacks

## 2. Colour System

| Token    | Hex       | Role              |
|----------|-----------|-------------------|
| `forest` | `#1F533C` | Primary / dark    |
| `green`  | `#7CB342` | Accent / medium   |
| `lime`   | `#9BD75A` | Highlight         |
| `mint`   | `#E8F5E9` | Surface / light   |

- Mode: Light-only
- Accent strategy: Single accent (`green`), supported by `lime` highlight
- Background: White
- Foreground: Near-black

## 3. Typography

- Personality: Geometric / clean grotesque
- Families (use in harmony — mix freely to suit context):
  - Hanken Grotesk, Space Grotesk — titles, headings, short text
  - IBM Plex Sans, DM Sans — body text, longer passages
  - Google Code Sans — code
- Weight behaviour: Emphasis from weight + spacing, not decoration

## 4. Components & Surfaces

- Feel: Flat and outlined — no gradients, no 3D
- Surface depth: Matte / single-plane — everything on one surface
- Dividers: Hairline 1px rules, not elevation
- Elevation: None by default; only for true overlays (popover, tooltip, modal)
- Icons: From a proper icon library; simple, consistent, minimal chrome

## 5. Imagery, Iconography & Motion

- Motion: Subtle — should support hierarchy and orientation
- Icons: Must use a proper icon library (e.g. Lucide). Never use special characters or inline SVGs as icons

## 6. Rules & Constraints

### Musts

- Always light mode
- Always flat (no gradients, no 3D)
- Whitespace as primary grouping mechanism
- Hairline dividers for section separation

### Nevers

- Never use dark backgrounds or dark themes
- Never use shadows except on true overlays
- Never stack cards or create depth layers
- Never use gradients or 3D effects
- Never use special characters or inline SVGs as icons — must use a proper library

### Floor

- Maintain contrast accessibility
