# Akash Ghosh — Portfolio

A modern, dynamic portfolio website built with vanilla HTML, CSS, and JavaScript. No frameworks, no build step — just clean code that loads fast and looks great.

🔗 **Live Demo**: [akashg94.github.io/potfollioExample](https://akashg94.github.io/potfollioExample)

## ✨ Features

- 🎨 **Custom Design** — Distinctive visual identity with thoughtful color choices
- 🌗 **Dark/Light Mode** — Theme toggle with localStorage persistence
- 🎯 **Interactive Particle Background** — Animated network on the hero
- ✏️ **Custom Cursor** — Smooth follower cursor with hover states
- 📜 **Scroll Animations** — Elegant reveal effects using Intersection Observer
- 🔢 **Animated Counters** — Stats count up when scrolled into view
- 🔄 **Rotating Text** — Dynamic hero subtitle
- 🗂️ **Filterable Projects** — Filter projects by category
- 📱 **Fully Responsive** — Mobile-first design that works on all devices
- ⚡ **Performance Optimized** — No frameworks, no bloat
- ♿ **Accessible** — Semantic HTML, keyboard navigation, reduced-motion support

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** — No frameworks, no dependencies
- **Google Fonts** — Space Grotesk, Inter, JetBrains Mono

## 📁 Project Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styles (themed with CSS variables)
├── script.js       # Interactivity and animations
└── README.md       # This file
```

## 🚀 Deployment to GitHub Pages

### Option 1: Replace your existing portfolio repo

1. Clone your existing portfolio repo:
   ```bash
   git clone https://github.com/akashg94/potfollioExample.git
   cd potfollioExample
   ```

2. Replace the old files with these new ones (`index.html`, `styles.css`, `script.js`).

3. Commit and push:
   ```bash
   git add .
   git commit -m "Redesign: modern dynamic portfolio"
   git push origin main
   ```

4. Enable GitHub Pages:
   - Go to your repo on GitHub → **Settings** → **Pages**
   - Source: `Deploy from a branch`
   - Branch: `main` / root
   - Click **Save**

5. Your site will be live at: `https://akashg94.github.io/potfollioExample/`

### Option 2: Create a clean new repo

For a cleaner URL like `akashg94.github.io`:

1. Create a new repo named exactly `akashg94.github.io`
2. Upload these three files
3. Your site goes live at `https://akashg94.github.io` automatically

## ✏️ Customization Guide

### Change Colors
All colors are CSS variables at the top of `styles.css`. Edit these to rebrand:
```css
:root {
    --accent: #0066CC;          /* Primary blue */
    --accent-light: #3B82F6;    /* Lighter blue */
    --highlight: #FBBF24;       /* Gold accent */
    --success: #10B981;         /* Green */
    /* ...more in styles.css */
}
```

### Update Content
- **Hero**: Edit lines in `index.html` under `<section class="hero">`
- **Rotating words**: Update the `words` array in `script.js`
- **Projects**: Add/edit `<article class="project-card">` blocks
- **Experience**: Add/edit `<div class="timeline-item">` blocks

### Add a New Project
Copy this template into the `.projects-grid` section:
```html
<article class="project-card reveal" data-category="fullstack">
    <div class="project-num">07</div>
    <div class="project-icon" style="--icon-color: #YOUR_COLOR;">
        <!-- SVG icon here -->
    </div>
    <h3 class="project-title">Project Name</h3>
    <p class="project-desc">Description here.</p>
    <div class="project-tech">
        <span>Tech1</span><span>Tech2</span>
    </div>
    <a href="GITHUB_URL" target="_blank" class="project-link">
        <span>View on GitHub</span>
    </a>
</article>
```

Categories: `fullstack`, `ml`, `cloud`, `database`

## 📝 License

MIT — feel free to use this as inspiration for your own portfolio.

---

**Built with ☕ in New York City by Akash Ghosh**
