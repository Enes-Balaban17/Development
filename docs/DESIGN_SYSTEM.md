# Design System Plan

This document defines the first visual design decisions for the portfolio website.

## Layout

The website will use a left sidebar layout inspired by Tania Rascia's website.

Desktop layout:

```txt
[Sidebar] [Main Content]
```

Sidebar identity row:

```txt
[Small Game Boy Advance icon] Enes Balaban [Light/Dark Theme Toggle]
```

Sidebar navigation:

```txt
About Me
Notes
Projects
Skills

Contact
Email signup
LinkedIn
```

## Page Width

Main content should stay readable and not become too wide.

Planned values:

- Sidebar width: 240px - 280px
- Main content max-width: 760px - 900px
- Main content padding: comfortable spacing on desktop, smaller spacing on mobile

## Theme

The website will support dark and light themes.

Dark theme direction:

- Background: near-black / dark gray
- Sidebar: slightly different dark tone
- Text: off-white
- Muted text: gray
- Borders: subtle dark gray
- Cards: dark gray with thin border

Light theme direction:

- Background: off-white
- Sidebar: very light gray
- Text: dark gray / near-black
- Muted text: medium gray
- Borders: light gray
- Cards: white or very light gray with thin border

## Accent Color

The accent color will be used for links, active navigation items, and small highlights.

Initial accent direction:

- Blue / cyan accent similar to clean developer websites

Possible accent examples:

```txt
#38bdf8
#60a5fa
#7dd3fc
```

## Typography

The typography should be simple, readable, and developer-portfolio friendly.

First version options:

- System font stack
- Inter-like sans-serif style

Planned default:

```css
font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
```

## Cards

Skill cards and project-related cards should stay minimal.

Card rules:

- Thin border
- Small border radius
- Compact padding
- Icon on the left, text on the right
- Hover effect can slightly change border or background
- No heavy shadows in the first version

Skill card layout:

```txt
[Icon] Skill Name
```

Skills grid:

- 3 cards per row on desktop
- 2 cards per row on tablet if needed
- 1 card per row on mobile

## Links and Buttons

Links should be simple text links, not large heavy buttons.

Rules:

- Accent color for links
- Underline or color change on hover
- Active sidebar item should be visually clear
- Main action links should remain vertical

## Divider Lines

Divider lines will be used to create the clean archive-like feeling.

Use cases:

- Between sidebar sections
- Between content sections
- Between archive/list items when needed

## Mobile Behavior

On mobile screens:

- Sidebar should move above the content or collapse into a compact top area.
- Navigation links should remain easy to tap.
- Skills grid should become one column.
- Main content should have comfortable side padding.

## First Version Design Goal

The first version should feel:

- Minimal
- Dark-theme friendly
- Developer-focused
- Clean and readable
- Inspired by Tania Rascia's layout, but customized for Enes Balaban's personal portfolio
