# Through the Drafts — A Writing Portfolio

A single-page writing portfolio website built with HTML, CSS, and vanilla JavaScript. Designed to showcase a semester's worth of writing assignments, drafts, and reflections.

## 📁 Project Structure

```
portfolio-website/
├── index.html        # Main portfolio file (all HTML, CSS, and JS in one file)
└── README.md         # This file
```

## ✨ Features

- **Multi-page navigation** — Home, Assignments, and Reflection sections with smooth client-side routing
- **Assignment detail view** — Each assignment expands to show all draft stages with descriptions and file links
- **Reflection page** — Narrative sections covering process, growth, and goals
- **Responsive design** — Built with CSS Grid and `clamp()` for fluid typography
- **No dependencies** — Pure HTML/CSS/JS, no frameworks or build tools required

## 🚀 Getting Started

Since this is a single HTML file, no installation is needed.

**To view locally**, just open `index.html` in any modern browser:

```bash
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

**To host on GitHub Pages:**

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under *Source*, select **Deploy from a branch**
4. Choose `main` branch and `/ (root)`
5. Click **Save** — your site will be live at `https://yourusername.github.io/repo-name`

## 🎨 Customization

All content is editable directly in `index.html`. Key areas to update:

| What | Where in the file |
|---|---|
| Your name / portfolio title | `<title>` tag and `.hero-title` section |
| Hero intro text | `.hero-text` section |
| Assignment titles & descriptions | `const assignments = { ... }` in the `<script>` block |
| Draft stage descriptions | `stages: [ ... ]` arrays inside each assignment |
| File links for each draft | `file: "#"` — replace `#` with your file URL or path |
| Reflection text | `.reflection-section` divs in the HTML |
| Accent color | `--accent: #b85c38` in `:root` CSS variables |

## 🖼️ Design

- **Fonts:** [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (headings) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (body) via Google Fonts
- **Color palette:** Warm ink-and-paper tones with a terracotta accent
- **Layout:** CSS Grid hero, fixed nav, smooth scroll, hash-based routing

## 📄 License

Feel free to use and adapt this template for your own portfolio.
