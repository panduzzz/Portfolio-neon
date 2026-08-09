# K Pavithra — Portfolio

## How to run
1. Unzip this folder.
2. Open it in VS Code.
3. Install the "Live Server" extension (if you don't have it).
4. Right-click `index.html` → **Open with Live Server**.

## What to edit
- **Projects** (`index.html`, `<section id="projects">`): replace the 3 placeholder
  `.project-card` blocks with your real projects — title, description, tech tags,
  and Live Demo / Source Code links.
- **Resume**: drop your resume PDF into `assets/` and name it `resume.pdf`
  (the Download CV button already points there), or update the `href` in the
  `.btn-primary` link in `index.html`.
- **Skills**: adjust the percentages in `<section id="skills">` — each bar has a
  `style="--w:XX%"` you can change, plus the label text next to it.
- **Colors**: all colors are defined once at the top of `style.css` under `:root`
  (e.g. `--violet`, `--blue`, `--bg`) — change them there to re-theme the whole site.
- **Hero image**: `assets/hero_character.png` is used in the hero. Swap in your own
  image with the same filename, or update the `src` in `index.html`.

## Structure
```
index.html   → page content/structure
style.css    → all styling (colors, layout, responsive rules)
script.js    → mobile menu, scroll-reveal animation, skill bar fill
assets/      → images (hero art, resume, etc.)
```
