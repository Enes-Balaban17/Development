# Skills Page Plan

This document defines the visual and content plan for the Skills section/page.

## Inspiration

The Skills section will be inspired by the visual feeling of Tania Rascia's Deep Dives section: clean icon cards, short labels, simple grid layout, and readable spacing.

The reference implementation uses a `cards` grid and individual `card` links for highlighted Deep Dive items. Each card contains a small thumbnail/icon and a title, which creates a compact visual index. This portfolio will follow that visual direction with skill cards instead of tutorial cards.

## Main Layout

```txt
🧰 Skills

Technologies, languages, and tools I use while building software projects.

[Icon Card] C
[Icon Card] C++
[Icon Card] C#

[Icon Card] Java
[Icon Card] Kotlin
[Icon Card] Assembly

[Icon Card] React
[Icon Card] HTML
[Icon Card] CSS

[Icon Card] JavaScript
[Icon Card] TypeScript
[Icon Card] Terminal

[Icon Card] Blender
[Icon Card] SQL
[Icon Card] Oracle DB
```

## Grid Decision

The Skills section will use a single aesthetic grid.

Grid rules:

- 3 cards per row on desktop.
- After 3 cards, the next skill goes to the next row.
- C, C++, and C# will be placed on the same row.
- Java, Kotlin, and Assembly will be placed on the same row.
- 2 cards per row can be used on tablets if needed.
- 1 card per row can be used on mobile screens.
- Cards should stay compact, similar to the Deep Dives reference.

## Skill List

Final skills to show:

- C
- C++
- C#
- Java
- Kotlin
- Assembly
- React
- HTML
- CSS
- JavaScript
- TypeScript
- Terminal
- Blender
- SQL
- Oracle DB

## Visual Style

Each skill should be shown as a small rectangular card.

Card structure:

```txt
[SVG/Icon] Skill Name
```

Design decisions:

- Use a grid layout.
- Keep cards compact and minimal.
- Use an SVG/icon library.
- Avoid large descriptions inside cards.
- The section should look closer to a visual index than a resume skill table.
- Dark/light theme colors should adapt with the rest of the site.

## Icon Source Plan

Primary reference:

- Tania Rascia website repository: `taniarascia/taniarascia.com`

The reference site uses image thumbnails/icons inside card-style elements for the Deep Dives section. During the build phase, icons will be searched from the reference repository first.

If some icons cannot be found in the reference repository, they will be completed during the website implementation phase with a suitable SVG/icon library.

Possible fallback icon sources:

- Simple Icons
- Devicon
- Local SVG files in `assets/icons/`
- Custom minimal SVG icons

## Suggested Icon Direction

Possible icon ideas:

- C: C language icon
- C++: C++ language icon
- C#: C# language icon
- Java: Java icon
- Kotlin: Kotlin icon
- Assembly: chip / low-level icon
- React: React atom icon
- HTML: HTML5 icon
- CSS: CSS3 icon
- JavaScript: JS icon
- TypeScript: TS icon
- Terminal: terminal prompt icon
- Blender: Blender icon
- SQL: database icon
- Oracle DB: Oracle/database icon

## Category Option

The first version will not use grouped categories. All skills will be shown in one visual grid.

If the grid becomes crowded in a future version, skills can be grouped like this:

```txt
Programming Languages
C, C++, C#, Java, Kotlin, Assembly, JavaScript, TypeScript

Frontend
React, HTML, CSS

Database
SQL, Oracle DB

Tools
Terminal, Blender
```

## First Version Decision

For the first version, use one visual grid similar to the Deep Dives reference.

No detailed descriptions are needed in the first version. The focus is visual clarity.
