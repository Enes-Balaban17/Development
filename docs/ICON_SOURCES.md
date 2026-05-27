# Icon Sources Report

This document records the current status of the icons used in the portfolio website.

## Icon Folder

Current icon folder:

```txt
assets/icons/
```

## Skill Icons Added to This Repository

Current local skill icon files:

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

## Theme Toggle Icons

Current local theme icon files:

- `theme-sun.svg`
- `theme-moon.svg`

Theme icon rules:

- Use the SVG files as inline icons or image icons inside the theme toggle button.
- Icons should inherit the current text color when possible.
- The icon should remain visible without showing a permanent square button frame.
- The square hover/focus frame should appear only on hover or keyboard focus.

## Homepage UI Icons

Current local homepage UI icon files:

- `folder-open.svg` for the About Me action button
- `email-newsletter.svg` for the Email Newsletter action button
- `notebook.svg` for the Notes preview heading
- `projects.svg` for the Projects preview heading

Homepage UI icon rules:

- Use these icons near text labels, not as standalone oversized graphics.
- Icons should be 20px - 24px.
- Icons should inherit the current text/accent color when possible.
- Keep icon spacing compact and aligned with the text baseline.

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
- Keep icon sizes visually consistent across the Skills grid.
- Use the same card dimensions for all skill cards.
- Icons should adapt well to both dark and light themes.
- If an icon has poor contrast in one theme, replace it with a cleaner SVG.
- Keep file names stable so existing HTML references do not break.
