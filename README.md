# Pratik Raj Portfolio

Single-page portfolio (HTML/CSS/JS + Three.js) for **https://ipratikkraj.github.io/Pratik-Portfolio/**.

## Deploy to GitHub Pages
1. Put everything in this folder at the **root** of the `Pratik-Portfolio` repository (`index.html`, `404.html`, `robots.txt`, `sitemap.xml`, `.nojekyll`, `assets/`).
2. Commit and push to `main`.
3. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)`**.
4. Wait a minute, then open the URL above.

## After it is live
- Test sharing previews: https://www.opengraph.xyz/ and the LinkedIn Post Inspector.
- Check structured data: https://search.google.com/test/rich-results
- Add the site in Google Search Console (URL-prefix property) and submit `sitemap.xml`.
- If you move to a custom domain, replace `https://ipratikkraj.github.io/Pratik-Portfolio/` in `index.html`, `robots.txt` and `sitemap.xml`.

## Notes
- Three.js r128 is bundled in `assets/vendor/`, so the site has no third-party script dependency. Fonts load from Google Fonts with system fallbacks.
- Images are WebP; the social preview is `assets/og-portfolio.jpg` (1200x630).
- Contact details, Instagram link and project URLs are edited directly in `index.html`.
