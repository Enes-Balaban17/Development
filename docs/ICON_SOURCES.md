# Icon Sources Report

This document records the current status of the skill icons used in the portfolio website.

## Reference Repository Checked

Primary reference:

- `taniarascia/taniarascia.com`

Findings:

- The reference site uses a card-based layout for its Deep Dives section.
- The Deep Dives cards use thumbnails/icons inside compact card elements.
- The useful reference found for layout is `src/pages/index.js`, where the Deep Dives section renders a `cards` container and individual `card card-highlight` items.
- The repository was useful for understanding card structure and visual direction.
- Direct reusable skill-specific icons for this portfolio's exact stack were not found through available repository search.

## Icons Added to This Repository

Current icon folder:

```txt
assets/icons/
```

Added custom SVG icons:

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

## Icons Not Found Directly in the Reference Repository

The following skill-specific icons were not found as directly reusable assets in the reference repository search:

- Assembly
- C
- C++
- C#
- Java
- Kotlin
- React
- HTML
- CSS
- JavaScript
- TypeScript
- Terminal
- Blender
- SQL
- Oracle DB

## Current Decision

Since direct reusable skill icons were not found in the reference repository, custom minimal SVG icons were added to `assets/icons/` for the first version.

During the implementation phase, these icons can be replaced or improved with a proper SVG/icon library if needed.

Possible future icon sources:

- Simple Icons
- Devicon
- Local custom SVG files
- Manually designed minimal SVG icons
