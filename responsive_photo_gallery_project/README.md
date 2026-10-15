# Field Notes — Responsive Photo Gallery

A mobile-first, static HTML/CSS project prepared for the Coursera *Advanced Styling with Responsive Design* final Photo Gallery assignment.

## Files
- `index.html` — semantic, validator-friendly page; all gallery items have alt text.
- `style.css` — mobile-first grid and the four required media queries.
- `images/` — nine original local SVG illustrations, so the gallery does not depend on external image URLs.

## Requirements implemented
- Mobile: one column with a 10px grid gap; no mobile-specific media query.
- Tablet (`min-width: 772px`): two columns, circular images, final figure spans both columns.
- Large screen (`min-width: 992px`): keeps the inherited two-column grid; every third figure spans both columns; image border radius removed. No `max-width` CSS property is used.
- Reduced motion: disables smooth scrolling and minimizes transitions/animations.
- Dark preference: dark cards, light-yellow text, black borders.
- New alt text and new paragraph content throughout.

## Preview locally
Open `index.html` in a browser. Keep the `images` folder beside it and `style.css` in the same folder.

## Publish on GitHub Pages
1. Create a **public** repository on GitHub, for example `responsive-photo-gallery`.
2. Upload `index.html`, `style.css`, and the entire `images` folder into the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then choose `main` and `/(root)`, and save.
5. Wait for GitHub Pages to publish. The public URL normally follows `https://YOUR-USERNAME.github.io/responsive-photo-gallery/`.
6. Open that URL in a private/incognito window and test the page before submitting it.

The URL above is a pattern, not a published address. A real public URL is generated only after the files are uploaded to a hosting account.
