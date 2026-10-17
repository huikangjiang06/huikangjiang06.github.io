# Huikang Jiang’s personal website

Personal academic website for https://huikangjiang06.github.io/, based on the current résumé. The HTML and CSS are maintained directly here.

## Files

- `index.html`: introduction, résumé content, contact links, and paper links.
- `styles.css`: responsive styling, including automatic dark mode.
- `assets/profile.jpg`: the user-supplied square photo, used without further image edits.
- `assets/huikang-jiang-cv.pdf`: English CV.
- `assets/huikang-jiang-cv-bilingual.pdf`: Chinese-first bilingual CV, linked from the website’s CV button.
- `.nojekyll`: serves the files as a plain static website on GitHub Pages.

No build step, packages, API keys, or external fonts are required.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open http://127.0.0.1:8765/.

## GitHub Pages

In the repository’s **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save. The site will be published at https://huikangjiang06.github.io/. Later pushes to `main` update the site automatically.

## Updating content

Edit `index.html` to change text or links. Replace the two PDFs in `assets/` when the résumé changes; keep their filenames so existing links continue to work. The current paper review status is copied from the résumé: ICLR 2027.

The profile photo is in `assets/profile.jpg`. Keep replacement photos square; the page displays the image with square corners at 208 × 208 pixels on desktop and 120 × 120 pixels on mobile.

Check the desktop and mobile layouts before committing and pushing edits.
