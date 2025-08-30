# Portfolio v2.0

This portfolio is built on the same core concepts and code I used when I first started learning web development, but much of it has been refactored and expanded as my skills have grown. It’s a simple, static site using plain HTML, CSS, and JavaScript, a great place to practice and revisit the fundamentals while keeping things clean and straightforward.

Visit the live site at [megankrenbrink.com](https://megankrenbrink.com)

— Megan Krenbrink

## Getting Started

### Prerequisites

- [Sass/SCSS](https://sass-lang.com/install) for stylesheet compilation

### Development Setup

1. Clone the repository

```bash
git clone https://github.com/megbort/portfolio-2.0.git
cd portfolio-2.0
```

2. Start the Sass watcher for automatic CSS compilation

```bash
sass --watch styles/main.scss:styles/main.css
```

3. Open `index.html` in your browser or use a local live server

## Tech Stack

- **Frontend**: HTML5, CSS3, SCSS (Sass)
- **JavaScript**: Vanilla JS + jQuery (minimal usage)
- **Icons**: SVG sprite system
- **Fonts**: Google Fonts (Overpass family)
- **Build**: Sass compiler

## Project Structure

```
portfolio-2.0/
├── index.html              # Homepage
├── project-*.html         # Project detail pages
├── assets/
│   ├── images/           # Photos, graphics, backgrounds
│   └── icons/            # SVG icon sprites
├── styles/
│   ├── main.scss        # Source styles (edit this)
│   ├── main.css         # Compiled CSS (auto-generated)
│   └── main.css.map     # Source map
└── .github/
    └── instructions/
        └── copilot.instructions.md  # AI assistant context
```
