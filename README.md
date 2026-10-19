# Obadiah Victory — Portfolio

A responsive, single-page portfolio for Obadiah Victory, frontend developer (HTML/CSS) and graphic designer. It uses semantic HTML, CSS, and a small JavaScript file for the accessible mobile menu. No build step or backend is required.

## Included files

- `index.html` — portfolio content and project links
- `styles.css` — responsive visual styling
- `script.js` — mobile navigation behavior
- `brand-mark.svg` — custom Victory monogram favicon

The asset references are relative, so the site can be hosted at a domain root or in a repository subdirectory such as GitHub Pages.

## Featured live projects

- Luma Store: `projects/luma-store/` (relative link; works inside this portfolio repository)
- Nexa Business: `projects/nexa-business/` (relative link; works inside this portfolio repository)
- Professional Portfolio: `projects/professional-portfolio/` (relative link; works inside this portfolio repository)

## Contact links

- Email: victoryobadiah741@gmail.com
- WhatsApp: https://wa.me/message/IOU53YGTMAOEF1
- GitHub: https://github.com/victoryfxtech
- LinkedIn: https://www.linkedin.com/in/obadiah-a-victory

## Preview locally

Open `index.html` in a browser, or serve this folder with a static HTTP server, for example:

```sh
python3 -m http.server 8000
```

To publish with GitHub Pages, upload these files to the repository root, then select the `main` branch and `/ (root)` under **Settings → Pages**.


## Added graphic design projects

The Selected Work section includes these three visual projects, with images stored locally in `assets/project-images/` so they work when the site is hosted:

- **AETHER — Technology Logo** (`assets/project-images/aether-logo.jpg`) — technology logo and identity concept.
- **Pulse Brand in Real Life** (`assets/project-images/pulse-brand-activation.png`) — brand activation and event collateral concept.
- **Karaoke Night Flyer** (`assets/project-images/karaoke-night-flyer.png`) — nightlife event campaign graphic.

The cards are part of `index.html` in the “Visual identity & campaign work” section. Upload the entire folder contents together; do not upload `index.html` alone, or the image assets will be missing.


## Clickable project websites

The portfolio includes the project folders for Nexa Business, Luma Store, and Professional Portfolio under `projects/`. Featured web project cards now open these bundled projects using relative links, so they work under a GitHub Pages project URL without relying on separate repositories. The AETHER logo, Pulse Brand activation, and Karaoke Night flyer each open a dedicated visual case-study page.

### Publish on GitHub Pages

1. Upload the contents of this ZIP to the root of `victoryfxtech/design-and-code-portfolio` (keep the `projects/` and `assets/` folders).
2. In GitHub, open **Settings → Pages** and publish from the `main` branch and `/ (root)`.
3. Once published, the web project URLs will be `https://victoryfxtech.github.io/design-and-code-portfolio/projects/nexa-business/`, `.../projects/luma-store/`, and `.../projects/professional-portfolio/`. The three graphic case studies will be under `.../projects/aether-logo/`, `.../projects/pulse-brand/`, and `.../projects/karaoke-night/`.

These are GitHub Pages paths and will become live after the updated files are committed and Pages finishes deploying; they are not independently verified as live before deployment.

## GitHub Pages 404 checklist

- Keep `index.html`, `styles.css`, `script.js`, and `brand-mark.svg` at the repository root. Do not upload only the ZIP file or place all files inside an extra enclosing folder.
- In the repository, open **Settings → Pages** and select **Deploy from a branch**, branch `main`, folder `/(root)`, then save.
- Confirm the repository name in the browser address exactly matches the URL path. For a project repository named `obadiah-vicotry-portfolio`, the URL is `https://victoryfxtech.github.io/obadiah-vicotry-portfolio/` (repository spelling matters).
- Wait for the Pages deployment to finish in the **Actions** tab. Then open the URL shown under **Settings → Pages**.
- A `404.html` page is included for unknown paths, but it does not replace the required root `index.html` or fix incorrect repository/Pages settings.
