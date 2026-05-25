# Site Plan

This document defines the first version of the portfolio website before coding starts.

## Main Sections

1. Sidebar / Navigation
2. About Me / Hero
3. Notes
4. Skills
5. Projects
6. Email Newsletter
7. Contact
8. Footer
9. About Me Page

## Layout / Sidebar Navigation

The website will use a left sidebar layout inspired by Tania Rascia's website.

The original content plan will stay the same, but it will be adapted into a sidebar-based layout.

Planned desktop layout:

```txt
┌──────────────────────────────┬───────────────────────────────────────────────┐
│ Sidebar                      │ Main Content                                  │
│                              │                                               │
│ [GBA icon] Enes Balaban [☀/☾]│ About Me / Notes / Projects / Skills pages   │
│                              │                                               │
│ About Me                     │                                               │
│ Notes                        │                                               │
│ Projects                     │                                               │
│ Skills                       │                                               │
│                              │                                               │
│ Contact                      │                                               │
│ Email signup                 │                                               │
│ LinkedIn                     │                                               │
└──────────────────────────────┴───────────────────────────────────────────────┘
```

Sidebar elements:

- Small Game Boy Advance style icon placed immediately to the left of the name
- Name: Enes Balaban
- Light/Dark theme toggle button placed immediately to the right of the name
- Main navigation links:
  - About Me
  - Notes
  - Projects
  - Skills
- Contact block:
  - Email signup
  - LinkedIn

Sidebar identity row:

```txt
[Small Game Boy Advance icon] Enes Balaban [Light/Dark Theme Toggle]
```

Mobile layout:

- Sidebar collapses or moves above the main content.
- Navigation remains simple and readable.
- Vertical link structure is preserved.

## About Me / Hero

The first main content block will use **About Me** as a side heading.

Final layout:

```txt
About Me

Hey, I'm Enes!

I'm a Computer Programming graduate and software developer.

This is my personal website. 🌐

📝 Notes

💻 Projects

⌨️ About Me

────────────────────────────────────────────────────────────────────────────

Contact

Email signup

LinkedIn
```

Important layout decision:

- Hero/action links must be placed vertically, not side by side.
- Contact items must also be placed vertically.
- There should be clear spacing between text blocks.
- A horizontal divider should separate the About/Hero action area from the Contact area.
- The desktop version will place navigation/contact items inside the left sidebar.

Final hero text:

```txt
Hey, I'm Enes!

I'm a Computer Programming graduate and software developer.

This is my personal website. 🌐
```

Primary vertical links:

- 📝 Notes
- 💻 Projects
- ⌨️ About Me

The **About Me** link will open the About Me page.

## About Me Page

The About Me page will be inspired by Tania Rascia's About Me page structure, but adapted for Enes Balaban's personal portfolio.

Reference structure observed:

- Main About Me heading
- Short personal introduction
- Contact section
- What I'm Doing Now section
- Tools section
- Hardware section
- Miscellaneous section

Planned page layout:

```txt
[Open folder icon] About Me

I'm Enes!

I'm a Computer Programming graduate from Ege University and a software developer based in Türkiye.

I use this website as my personal space for sharing my projects, notes, portfolio progress, and the things I learn while improving myself as a developer.

I'm open to project, internship, and collaboration opportunities where I can improve my skills and contribute to real-world software projects.

I'm interested in software development, data analysis, artificial intelligence, database systems, and web technologies.

Outside of software, I enjoy martial arts, especially Muay Thai, exploring hardware and electronic devices, playing tabletop RPGs, reading comics and fantasy books, researching history, watching documentaries, and nerding out about strategy games.

Contact

If you want to say hello, send me an email or connect via the socials.

- Email: balabanenes111@icloud.com
- Email Newsletter
- GitHub
- LinkedIn

Certificates & Completed Educations

- Ege University — Computer Programming
  Associate Degree / 2024 - 2026

- Data Analysis School — Artificial Intelligence Module
  Free online training program carried out under the auspices of the Council of Higher Education (YÖK), coordinated by Marmara University Population and Social Research Institute, with contributions from METU, ITU, and Boğaziçi University. The program focuses on combining theoretical knowledge and practical skills in data analysis, statistics, and artificial intelligence.
  2025 - 2026

- TUSAŞ LIFT UP — Industry-Oriented Undergraduate Graduation Projects Conference
  Certificate of Participation / 2024 - 2025

What I'm Doing Right Now

- Building my personal portfolio website
- Improving my GitHub profile
- Open to internship, project, and collaboration opportunities
- Improving myself in software development, data analysis, and artificial intelligence

Tools

This website is hosted with GitHub Pages and uses a static HTML, CSS, and JavaScript structure for the first version.

- Coding: Visual Studio Code, Visual Studio, IntelliJ IDEA, PyCharm, Arduino IDE
- Terminal: Linux Terminal, PowerShell ISE
- Notes & Planning: GitHub, GitHub Issues, Markdown
- Databases: SQL Server Management Studio, Oracle Database tools

Hardware

Technical specifications of the devices used for software development.

This section will not include drone hardware or project hardware. It will only include computers, peripherals, and devices used for coding, testing, design, and development work.

- Coding PC: Asus TUF Gaming F15
  - CPU:
  - Motherboard:
  - Memory:
  - Storage:
  - GPU:
- Side Monitor: TUF Gaming VG27AQ
- Keyboard: TUF F3
- Headphones: SteelSeries Arctis Nova 3

Miscellaneous

- Resume
- Minigames
- Illustrations
```

### Final About Me Introduction Text

```txt
I'm Enes!

I'm a Computer Programming graduate from Ege University and a software developer based in Türkiye.

I use this website as my personal space for sharing my projects, notes, portfolio progress, and the things I learn while improving myself as a developer.

I'm open to project, internship, and collaboration opportunities where I can improve my skills and contribute to real-world software projects.

I'm interested in software development, data analysis, artificial intelligence, database systems, and web technologies.

Outside of software, I enjoy martial arts, especially Muay Thai, exploring hardware and electronic devices, playing tabletop RPGs, reading comics and fantasy books, researching history, watching documentaries, and nerding out about strategy games.
```

### Certificates & Completed Educations Content

```txt
Certificates & Completed Educations

- Ege University — Computer Programming
  Associate Degree / 2024 - 2026

- Data Analysis School — Artificial Intelligence Module
  Free online training program carried out under the auspices of the Council of Higher Education (YÖK), coordinated by Marmara University Population and Social Research Institute, with contributions from METU, ITU, and Boğaziçi University. The program focuses on combining theoretical knowledge and practical skills in data analysis, statistics, and artificial intelligence.
  2025 - 2026

- TUSAŞ LIFT UP — Industry-Oriented Undergraduate Graduation Projects Conference
  Certificate of Participation / 2024 - 2025
```

Source notes for Data Analysis School description:

- Marmara University states that the program is carried out with the support of YÖK, coordinated by Marmara University Population and Social Research Institute, and supported by METU, ITU, and Boğaziçi University.
- YÖK describes the program as free, open to broad participation, and focused on data analysis, statistics, and artificial intelligence through online modules.

### What I'm Doing Right Now Content

```txt
What I'm Doing Right Now

- Building my personal portfolio website
- Improving my GitHub profile
- Open to internship, project, and collaboration opportunities
- Improving myself in software development, data analysis, and artificial intelligence
```

### Tools Content

```txt
Tools

This website is hosted with GitHub Pages and uses a static HTML, CSS, and JavaScript structure for the first version.

- Coding: Visual Studio Code, Visual Studio, IntelliJ IDEA, PyCharm, Arduino IDE
- Terminal: Linux Terminal, PowerShell ISE
- Notes & Planning: GitHub, GitHub Issues, Markdown
- Databases: SQL Server Management Studio, Oracle Database tools
```

### Hardware Content

```txt
Hardware

Technical specifications of the devices used for software development.

- Coding PC: Asus TUF Gaming F15
  - CPU:
  - Motherboard:
  - Memory:
  - Storage:
  - GPU:
- Side Monitor: TUF Gaming VG27AQ
- Keyboard: TUF F3
- Headphones: SteelSeries Arctis Nova 3
```

### About Me Page Headings

Main heading:

- 📂 About Me

Subheadings, slightly smaller than the main heading:

- Contact
- Certificates & Completed Educations
- What I'm Doing Right Now
- Tools
- Hardware
- Miscellaneous

### About Me Page Notes

- The page should be personal but still professional.
- Education details will be written here instead of creating a separate Education page.
- Experience section will not exist as a separate page or main section.
- CV and GitHub can be included in this page.
- The Hardware section will only include technical specifications of software development devices.
- The Hardware section will not include drone hardware, FPV parts, embedded systems, or project hardware.
- The Tools section will describe hosting/framework information first, then tool categories with marker dots.
- The Miscellaneous section can link to extra pages such as Resume, Minigames, and Illustrations.

## Notes Page

The website will not include a traditional blog. Instead, it will have a Notes section inspired by yearly note/archive pages.

The Notes page will be used for short personal and technical records such as:

- Year in Review notes
- Events attended
- Completed projects
- Completed courses or trainings
- Short development notes
- Learning logs
- Project planning notes
- Technical reminders
- GitHub portfolio progress notes

Planned Notes page layout:

```txt
📝 Notes

Short notes about my yearly progress, events, completed projects, completed educations, and development journey.

[Search notes input]

2026

Date        Note title
Date        Note title

2025

Date        Note title
Date        Note title

2024

Date        Note title
Date        Note title
```

Notes page design decisions:

- Notes will be grouped by year.
- Each note will have a date, title, and optional tag.
- Notes will be listed in a simple archive style.
- The page may include a search input like the reference design.
- Notes will be shorter and more personal than full blog posts.
- Possible tags: year-in-review, event, project, education, certificate, development, portfolio.

Example note titles:

- Year in Review: 2025 into 2026
- Starting My Portfolio Website
- Data Analysis School — Artificial Intelligence Module
- TUSAŞ LIFT UP Participation Notes
- Building My GitHub Profile
- Completed Projects in 2026

## Projects Page

The Projects page will be inspired by a minimal archive/list style. It will not use heavy project cards. Projects will be shown as a clean yearly list.

Planned Projects page layout:

```txt
💻 Projects

Selected software projects, experiments, and portfolio work.

[Search projects input]

2026

Project Name
Short project description.
Demo / Source

Project Name
Short project description.
Source

2025

Project Name
Short project description.
Demo / Source
```

Project item structure:

- Year
- Project name
- Short description
- Technologies used
- Demo link when available
- Source link
- Optional details link when needed

Link display rules:

- If a project has a live demo, show: Demo / Source
- If a project does not have a live demo, show only: Source
- If a project needs more explanation but no demo exists, show: Details / Source
- If a project is not public yet, show: In Progress or Private

Projects page design decisions:

- Projects will be grouped by year.
- Project links will stay simple and text-based.
- No large image cards in the first version.
- Demo and Source links will be placed under the project description.
- Some projects may not have a Demo link, so the layout must support optional links.
- Possible tags: web, database, ai, data-analysis, desktop, academic, hardware-related, portfolio.

Example project entries:

- Portfolio Website
  Personal portfolio website for sharing projects, notes, and development progress.
  Demo / Source

- Database Management Project
  Academic database project focused on schema design, relationships, and SQL queries.
  Source

- Dorian Face Recognition System
  Face recognition and monitoring system developed as a software-focused academic project.
  Details / Source

## Skills

The Skills section will be presented visually with icons or icon-like cards.

Planned categories:

- Programming Languages
- Web Development
- Database Systems
- Tools
- Artificial Intelligence & Data Analysis
- Hardware & Drone Projects

## Email Newsletter

The website should include an email newsletter style section.

Initial version:

- Newsletter form as a visual component
- Coming soon note
- Active email contact button

Future version:

- Connect to a newsletter service such as Buttondown, Substack, or Mailchimp

## Contact

Planned contact layout:

```txt
Contact

Email signup

LinkedIn
```

GitHub and CV will be placed inside or near the About Me section instead of the main contact area.

## Design Direction

- Minimal layout
- Left sidebar layout inspired by Tania Rascia's website
- Readable typography
- Dark and light theme support
- Small Game Boy Advance style identity icon placed directly next to the name
- Light/Dark theme toggle placed directly to the right of the name in the sidebar identity row
- Vertical action links instead of horizontal buttons
- Accent color selection if needed
- Clean spacing
- Responsive design
- Simple project and note lists
