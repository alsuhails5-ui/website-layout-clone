# NOVA — Website Layout Clone

A responsive creative-studio homepage built from scratch for the **#evn-lf26-web-dev2** Website Layout Clone challenge.

## Features

- Modern, original creative-agency homepage concept
- CSS Grid for page sections, cards and project layouts
- Flexbox for navigation, buttons, card content and footer alignment
- Responsive desktop, tablet and mobile breakpoints
- Hover transitions on links, buttons, cards and project tiles
- Mobile navigation toggle with accessible expanded state
- CSS-built hero artwork and project visuals (no image assets required)
- Semantic HTML and reduced-motion support

## Run locally

No framework or package installation is required.

1. Extract the project ZIP.
2. Open `index.html` in a browser, or use VS Code Live Server.
3. Replace `alsuhails@mulearn` in `index.html` with your actual μID.

## Project structure

```text
website-layout-clone/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Layout techniques used

- CSS Grid: hero composition, intro content, services and selected-work cards.
- Flexbox: announcement strip, navigation, action groups, service cards and footer.
- Media queries: tablet at 900px and mobile at 650px.
- Hover effects: button lift, card lift, arrow rotation and link color transitions.

## Test responsive views

In Chrome DevTools, test at:
- Desktop: 1440px
- Tablet: 768px
- Mobile: 375px

Check the mobile menu, section stacking, text wrapping and horizontal overflow.

## Deploy with GitHub and Vercel

### GitHub

Create a new public repository, e.g. `website-layout-clone`, then run these commands from this project folder:

```bash
git init
git add .
git commit -m "Build responsive website layout clone"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/website-layout-clone.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

### Vercel

1. Visit https://vercel.com/new and import the GitHub repository.
2. Keep the framework preset as **Other** (static HTML/CSS/JS).
3. Leave build command and output directory blank if prompted; the root `index.html` is served as a static site.
4. Deploy and test the generated `.vercel.app` URL.

Alternative: GitHub Pages can host this static site directly from the repository.

## Submission

```text
#evn-lf26-web-dev2

Cloned a modern homepage layout using CSS! Built it with Flexbox and Grid, made it responsive with media queries, and added hover effects.

GitHub Repository: https://github.com/YOUR_USERNAME/website-layout-clone
Hosted Website: https://YOUR-DEPLOYED-SITE.vercel.app
```

Replace the example URLs with your actual published links before submission.
