# Nikita Malik Portfolio Website

A static academic portfolio website ready for GitHub Pages.

## Deployable Files

- `index.html` — main portfolio page, required at the repository root
- `styles.css` — site styling
- `images/` — profile, institution, and company images used by the page
- `Malik_Nikita_Resume_6.pdf` — resume PDF linked from the page
- `.nojekyll` — tells GitHub Pages to serve this as a plain static site
- `.gitignore` — excludes local-only files such as `.venv/`

## Local Preview

Open `index.html` in a browser or use a local file server.

Example:

```bash
cd '/Users/nikitamalik/Documents/Portfolio website'
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages Setup

Push this folder as the root of a GitHub repository. In the repository settings, go to `Pages`, choose `Deploy from a branch`, select `main`, and set the folder to `/root`.

The site will be available at:

```text
https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/
```

For a custom domain later, add the domain in GitHub Pages settings and configure DNS with your domain provider.
