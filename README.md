# DU FVG Sesamo Support Brochure

This repository contains a semantic, responsive, and accessibility-focused HTML + CSS website.

Included files:

- `index.html` — semantic page skeleton with landmarks, examples, and sample interactive elements.
- `styles.css` — mobile-first CSS, fluid typography, focus styles, and print rules.
- `ACCESSIBILITY.md` — checklist for accessibility testing.

SCSS source and compilation

- Primary SCSS source: `styles/styles.scss`.
- Compiled stylesheet (served by the site): `styles.css` at the project root.
- To compile locally with Dart Sass, run:

```bash
 sass styles/styles.scss styles.css
```

To watch SCSS for changes and automatically rebuild the CSS, run:

```bash
sass --watch styles/styles.scss:styles.css --no-source-map --style=compressed
```
