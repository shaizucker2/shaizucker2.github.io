# Shai Zucker

Personal academic website: https://shaizucker2.github.io/

This is a lightweight static site served by GitHub Pages from the `main` branch, repository root. It does not require a build step, browser-side JavaScript, or external fonts.

## Files

- `index.html` — profile, research interests, publications, teaching, talks, and awards.
- `styles.css` — responsive layout and typography.
- `shai-zucker.jpg` — optimized profile photograph.
- `og.png` — image used when sharing the site.
- `.nojekyll` — serves the files directly without Jekyll processing.

## Updating

Edit `index.html` or `styles.css` in this repository and commit the changes to `main`. GitHub Pages will publish the update automatically.

When updating from the original local project, edit `app/page.tsx` or `app/globals.css`, run `npm run build:static`, and upload the resulting files from `dist/static/` to this repository.
