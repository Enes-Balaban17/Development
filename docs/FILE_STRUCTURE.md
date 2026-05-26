# File Structure Plan

This document defines the planned file structure before implementation starts.

## SSG / Framework Decision

First version decision:

- Do not use Gatsby for the first version.
- Do not use React, Vite, Astro, Next.js, or another SSG in the first version.
- Build the first version with static HTML, CSS, and JavaScript.
- Host the website with GitHub Pages.

Reasoning:

- The first version should stay simple and easy to maintain.
- The project is currently a personal portfolio with static pages.
- Notes and Projects can be managed as static HTML pages at first.
- A static structure is enough for the first release.
- A framework can be added later after the content and design are stable.

Future upgrade option:

- If Notes, Projects, Resume, Minigames, and Illustrations grow significantly, migrate to a lightweight SSG such as Astro or Eleventy.
- Gatsby is not preferred for the first version because it adds unnecessary complexity for this stage.

## Final First Version Structure

```txt
portfolio-website/
│
├── index.html
├── notes.html
├── projects.html
├── skills.html
├── about.html
├── resume.html
├── minigames.html
├── illustrations.html
│
├── README.md
├── LICENSE
├── .gitignore
│
├── assets/
│   ├── icons/
│   │   ├── assembly.svg
│   │   ├── c.svg
│   │   ├── cpp.svg
│   │   ├── csharp.svg
│   │   ├── java.svg
│   │   ├── kotlin.svg
│   │   ├── react.svg
│   │   ├── html.svg
│   │   ├── css.svg
│   │   ├── javascript.svg
│   │   ├── typescript.svg
│   │   ├── terminal.svg
│   │   ├── blender.svg
│   │   ├── sql.svg
│   │   └── oracle-db.svg
│   │
│   ├── images/
│   │   ├── gba-icon.png or gba-icon.svg
│   │   ├── enescot.png
│   │   └── profile/optional
│   │
│   ├── cv/
│   │   └── Enes_Balaban_CV.pdf optional
│   │
│   └── screenshots/
│
├── css/
│   └── style.css
│
├── js/
│   └── main.js
│
└── docs/
    ├── SITE_PLAN.md
    ├── DESIGN_SYSTEM.md
    ├── SKILLS_PLAN.md
    ├── ICON_SOURCES.md
    └── FILE_STRUCTURE.md
```

## Page Responsibilities

### `index.html`

Home page with the left sidebar, main hero/about intro, and hero mascot.

Includes:

- Sidebar
- Sidebar short About Me block
- About Me / Hero intro
- Hero mascot image from `assets/images/enescot.png`
- Vertical links to Notes, Projects, About Me
- Contact block in sidebar

### `about.html`

Full About Me page.

Includes:

- About Me introduction
- Contact
- Certificates & Completed Educations
- What I'm Doing Right Now
- Tools
- Hardware
- Miscellaneous links

### `notes.html`

Notes archive page.

Includes:

- Year in Review notes
- Events attended
- Completed projects
- Completed educations
- Short development notes
- Search input if needed

### `projects.html`

Projects archive page.

Includes:

- Year-based project list
- Project descriptions
- Demo / Source / Details links
- Optional project status labels

### `skills.html`

Skills grid page.

Includes:

- 3-column icon grid on desktop
- SVG icons from `assets/icons/`
- Responsive layout

### `resume.html`

Web version of the resume/CV.

PDF CV can also be linked from here later.

### `minigames.html`

Page for small games and experiments.

### `illustrations.html`

Page for illustration/design work.

## Shared Components in Static HTML

Since the first version will not use a framework, the sidebar will be repeated in each HTML file.

This is acceptable for the first version because the website is small.

Future improvement:

- Move repeated layout into a component system if the site migrates to Astro, Eleventy, React, or another SSG/framework.

## CSS Plan

All first-version styling will be in:

```txt
css/style.css
```

Main CSS sections:

- CSS variables
- Base styles
- Sidebar layout
- Main content layout
- Typography
- Links/buttons
- Cards
- Skills grid
- Hero mascot
- Archive lists
- Theme styles
- Responsive styles

## JavaScript Plan

All first-version JavaScript will be in:

```txt
js/main.js
```

Initial JavaScript responsibilities:

- Dark/light theme toggle
- Save selected theme to localStorage
- Optional search/filter for Notes and Projects later

## Deployment Plan

First version deployment:

- Use GitHub Pages
- Deploy from the `main` branch
- Root directory deployment

No build command is needed for the first static version.
