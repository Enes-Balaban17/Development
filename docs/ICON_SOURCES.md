# Icon Sources Report

This document records the current status of the skill icons used in the portfolio website.

## Icon Folder

Current icon folder:

```txt
assets/icons/
```

## Icons Added to This Repository

Current local icon files:

- `assembly.svg`
- `c.svg`
- `cpp.svg`
- `csharp.svg`
- `java.svg`
- `kotlin.svg`
- `react.svg`
- `html.svg`
- `css.svg`
- `javascript.svg`
- `typescript.svg`
- `terminal.svg`
- `blender.svg`
- `sql.svg`
- `oracle-db.svg`

## Current Decision

The first version will use local SVG files from `assets/icons/`.

Some icons are custom minimal SVGs. Some icons are SVG wrappers containing embedded image data. This keeps the site independent from external image URLs during normal use.

During the implementation phase, icons can be replaced or improved while keeping the same file names.

## Possible Future Icon Sources

- Simple Icons
- Devicon
- Local custom SVG files
- Manually designed minimal SVG icons

## Implementation Notes

- Prefer local files over remote image links.
- Keep icon sizes visually consistent.
- Use the same card dimensions for all skill cards.
- Icons should adapt well to both dark and light themes.
- If an icon has poor contrast in one theme, replace it with a cleaner SVG.
