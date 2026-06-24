# Naseeb Sultan — Portfolio Website

## File Structure
```
portfolio/
├── index.html       ← Main HTML file (open this in browser)
├── style.css        ← All styles & animations
├── script.js        ← Particles, typewriter, scroll effects
├── images/
│   └── profile.jpeg ← Your profile photo
└── README.md
```

## How to use
1. Extract all files keeping the folder structure
2. Open `index.html` in any modern browser
3. To host online: upload to GitHub Pages, Netlify, or Vercel

## GitHub Pages
This site is plain HTML/CSS/JS (not Jekyll). Deploy it with the included workflow:

1. In the repo, go to **Settings → Pages**
2. Under **Build and deployment**, set **Source** to **GitHub Actions** (not “Deploy from branch” with the `/docs` folder)
3. Push to `main` — the workflow in `.github/workflows/pages.yml` publishes the site root as static files

If Pages was previously set to the `/docs` folder, that caused Jekyll build failures because this repo has no `docs/` directory and no Jekyll files. The `.nojekyll` file at the repo root also tells GitHub not to run Jekyll when publishing from a branch.

## To replace photo
Drop your photo into the `images/` folder and rename it `profile.jpeg`
