# Design System Plan

This document defines the final visual rules for the first implementation phase.

## Overall Direction

The site will use a minimal developer-portfolio layout with a fixed left sidebar on desktop and a compact top navigation on smaller screens.

The design should be text-first, warm in light mode, dark gray in dark mode, and comfortable to read.

## Layout Values

Use these values during implementation:

```txt
navbar height: 60px
footer height: 60px
content width: 760px
sidebar width: 260px
optional right/post sidebar width: 260px
main layout width: content width + optional right/post sidebar width
mobile/base padding: 1.5rem vertical and horizontal
tablet/desktop padding: 2rem vertical and horizontal
border radius: 6px
```

## Breakpoints

```txt
600px and above:
- increase layout padding to 2rem
- increase heading sizes

800px and above:
- use larger hero/page headings around 3rem

1020px and above:
- show left sidebar
- hide compact top navigation
- use two-column layout: 260px sidebar + main content

1360px and above:
- allow wider layout with optional right-side content area
```

## Sidebar

Sidebar behavior:

```txt
width: 260px
position: sticky on desktop
height: 100vh
scrollable if content overflows
border-right: 1px solid border color
hidden below 1020px
```

Sidebar identity row:

```txt
[Small Game Boy Advance icon] Enes Balaban [Light/Dark Theme Toggle]
```

Sidebar identity styling:

```txt
horizontal flex row
items centered vertically
0.75rem gap
site name font size: 18px
site name weight: 500
```

Sidebar section styling:

```txt
margin: 1.25rem
padding-bottom: 1.5rem
border-bottom: 1px solid border color
```

Sidebar navigation styling:

```txt
links are vertical
2px gap between nav links
font size: 16px
font weight: 500
padding: 4px 0.5rem
small negative horizontal margin for alignment
border radius: 6px
active link uses highlighted background and accent text
```

## Color Palette

Core dark gray palette:

```txt
gray-0  #fbfbfb
gray-1  #eeeeee
gray-2  #e4e4e7
gray-3  #d4d4d8
gray-4  #c8c8cf
gray-5  #a1a1a8
gray-6  #4e4e55
gray-7  #323239
gray-8  #25252b
gray-9  #1c1c20
gray-10 #1d1d22
gray-11 #16161a
gray-12 #0d0d11
```

Core warm light palette:

```txt
beige-0  #fdf9ee
beige-1  #f6f0df
beige-2  #eee8d5
beige-25 #e5dcbd
beige-3  #ded4b2
beige-4  #c6ba93
```

Accent palette:

```txt
yellow light/dark:   #ac7c14 / #fcdc97
green light/dark:    #2d922d / #92d192
pink light/dark:     #d33682 / #ff8ac0
lavender light/dark: #a455be / #d48ceb
blue light/dark:     #2f71b4 / #6ab0f3
```

First version accent:

```txt
pink
```

Main color mapping:

```txt
light background: beige-0
dark background: gray-9
light sidebar: beige-0
dark sidebar: gray-9
light card: beige-1
dark card: gray-8
light text: gray-8
dark text: gray-3
light emphasized text: gray-10
dark emphasized text: gray-0
light muted text: gray-6
dark muted text: gray-5
light border: beige-25
dark border: gray-7
light card border: beige-3
dark card border: gray-7
```

## Typography

Body font:

```txt
-apple-system, BlinkMacSystemFont, Avenir, Helvetica, Arial, sans-serif
```

Heading font:

```txt
Outfit, -apple-system, BlinkMacSystemFont, DM Sans, Avenir, Helvetica, Arial, sans-serif
```

Monospace font:

```txt
Menlo, Google Sans Code, monospace
```

Base heading sizes:

```txt
h1: 2.2rem
h2: 1.8rem
h3: 1.6rem
h4: 1.2rem
```

Larger screens:

```txt
h1: 2.8rem
h2: 2.3rem
h3: 1.9rem
h4: 1.5rem
hero/page h1: about 3rem
```

## Cards

Card rules:

```txt
border radius: 6px
thin border
compact padding
subtle hover background or border change
no heavy shadow in the first version
```

Skill cards:

```txt
[Icon] Skill Name
```

Skills grid:

```txt
3 cards per row on desktop
2 cards per row on tablet if needed
1 card per row on mobile
```

## Buttons and Links

Button rules:

```txt
inline-flex
center aligned
2px border
10px 14px padding
6px radius
font size 1rem
font weight 600
small button: 14px font, 0.5rem 0.75rem padding
extra small button: 11px font, 0.25rem 0.5rem padding
```

Link rules:

```txt
accent color for normal text links
active sidebar link is visually clear
hover state changes color or background subtly
```

## Archive Lists

Notes and Projects should use clean archive lists.

Rules:

```txt
group by year
use simple text links
keep generous spacing
avoid large image cards
support optional search input later
```

## Mobile Behavior

```txt
left sidebar hidden
compact top navigation shown
navigation remains readable and easy to tap
skills grid becomes one column
main content uses comfortable side padding
```

## Implementation Priority

1. CSS variables
2. Base typography
3. Sidebar layout
4. Main content layout
5. Cards and skill grid
6. Archive list styling
7. Theme toggle styling
8. Responsive styling
