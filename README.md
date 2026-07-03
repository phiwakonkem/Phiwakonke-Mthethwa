# Tesla Clone

A static front-end clone of the Tesla homepage, built as a CSS layout practice project during the Zaio Web Development bootcamp. Focused on replicating Tesla's navigation bar and Model 3 hero section using plain HTML and CSS — no frameworks, no build tools.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

> 📚 **Learning project** — built to practice flexbox layout, responsive nav design, and pixel-matching an existing site. Not affiliated with or endorsed by Tesla, Inc.; images and branding belong to Tesla and are used here for non-commercial, educational recreation only.

---

## What's Inside

- A fixed top navigation bar (logo, nav links, icon buttons) built with Flexbox
- A full-bleed hero section for the Model 3, with "Order Now" and "Demo Drive" call-to-action buttons
- Google Fonts (`Roboto`) and Material Icons integration
- Tesla's official homepage imagery (Model 3/S/X/Y/Cybertruck cards) used as local static assets

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (Flexbox) |
| Fonts/Icons | Google Fonts (Roboto), Material Icons |

No JavaScript, package manager, or build step is used — this is a pure HTML/CSS static site.

## Project Structure

```
Tesla-Clone/
└── Zaio-Tesla 2/
    ├── index.html      # Page markup: nav + hero section
    ├── styles.css       # All styling
    └── Assets/            # Tesla homepage imagery (avif) + logo
```

## Getting Started

### Prerequisites

- A modern web browser
- (Optional) [VS Code](https://code.visualstudio.com/) with the **Live Server** extension for auto-reload while editing

### Run it locally

No installation or dependencies required — it's static HTML/CSS.

1. Clone the repository:

```bash
git clone https://github.com/phiwakonkem/Tesla-Clone.git
cd "Tesla-Clone/Zaio-Tesla 2"
```

2. Open `index.html` directly in your browser:

```bash
# macOS
open index.html

# Windows (PowerShell)
start index.html

# Linux
xdg-open index.html
```

Or, for live-reload while editing, right-click `index.html` in VS Code and choose **"Open with Live Server."**

## Notes

- The folder name `Zaio-Tesla 2` (with a space) is kept as-is from the original bootcamp submission — if you rename it, update any relative paths in `index.html` accordingly.
- This project currently covers the nav bar and hero section only; the rest of the Tesla homepage (footer, additional model cards, energy section) was not built out.

## Roadmap

- [ ] Build out the remaining homepage sections (model cards grid, footer)
- [ ] Add responsive breakpoints for mobile/tablet
- [ ] Add subtle scroll/hover animations to match the real site

## Author

**Phiwakonke Mthethwa**
Full-Stack Developer, Centurion, South Africa

- GitHub: [@phiwakonkem](https://github.com/phiwakonkem)
- LinkedIn: [phiwakonke-mthethwa](https://www.linkedin.com/in/phiwakonke-mthethwa-97aa74331)
- Email: phiwakonkem@gmail.com
