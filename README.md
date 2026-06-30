# Kush Man Shrestha — Personal Portfolio

A modern, responsive, dark-themed personal portfolio website for **Kush Man Shrestha**, Sr. QA Engineer & Agile Project Manager based in Kathmandu, Nepal.

## Project Structure

```
shresthakush.github.io/
├── index.html          # Single-page application (all sections)
├── css/
│   └── style.css       # All styles — dark theme, responsive, animations
├── js/
│   └── main.js         # Scroll effects, typed text, nav highlight, reveal
├── assets/
│   └── cv/
│       └── Kush_Man_Shrestha_CV.pdf   # ← Place your CV PDF here
└── README.md
```

## Sections

| Section    | Description                                      |
|------------|--------------------------------------------------|
| Home       | Hero with typed role animation and CTA buttons   |
| About      | Professional summary, quick info card, key stats |
| Skills     | Four categorised skill grids with tags           |
| Experience | Vertical timeline with all four roles            |
| Projects   | Cards for KFQ, MST, IVy, and WRL                 |
| Education  | MSc (2024) and BSc (2019) degree cards           |
| Contact    | Email, phone, and CV download cards              |

## Adding Your CV for Download

1. Copy your CV PDF into `assets/cv/` and name it exactly:
   ```
   Kush_Man_Shrestha_CV.pdf
   ```
2. The **Download CV** button in both the hero and the contact section will link to it automatically.

## Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** — no frameworks or dependencies
- **Google Fonts** — Inter + JetBrains Mono

## Deployment (GitHub Pages)

The site is deployed at: **https://shresthakush.github.io**

GitHub Pages serves `index.html` from the root of the `main` branch automatically.

## Local Preview

No build step required. Simply open `index.html` in any browser, or run a local server:

```bash
# Python 3
python3 -m http.server 8080

# Then open: http://localhost:8080
```
