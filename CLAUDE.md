# JuliaLong Project

## Overview
A collection of interactive web-based sub-projects hosted on GitHub Pages.

## Tech Stack
- **HTML5** - Structure
- **CSS3** - Styling
- **Vanilla JavaScript** - No frameworks
- **Libraries** - Include via CDN in `<head>` when needed

## Project Structure
```
/
├── index.html          # Landing page with cards linking to sub-projects
├── vocab-test/         # Vocab Test sub-project
│   └── index.html
├── cats-game/          # Cats Game sub-project
│   └── index.html
└── CLAUDE.md
```

## Constraints
- **Flat file structure only** - Required for GitHub Pages hosting
- **No build tools** - No bundlers, transpilers, or package managers
- **No server-side code** - Static files only
- **No frameworks** - Vanilla JS only (React, Vue, Angular, etc. are not allowed)

## Sub-Projects
1. **Vocab Test** - `/vocab-test/`
2. **Cats Game** - `/cats-game/`

More sub-projects will be added over time.

## Adding New Sub-Projects
1. Create a new directory at the root level
2. Add an `index.html` file inside
3. Add a card linking to it on the landing page (`/index.html`)

## Development Guidelines
- Keep all assets (CSS, JS, images) within each sub-project folder or shared at root
- Use relative paths for internal links
- Libraries should be loaded from CDNs in the `<head>` section
- Each sub-project should be self-contained
