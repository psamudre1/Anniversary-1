# Anniversary Website Skeleton

A clean, single-page **skeleton** for an anniversary website.

This project intentionally includes only structure, layout, styling, and placeholders so personal content can be added later without redesigning the page.

## Project Files

- `index.html` — semantic single-page layout and section placeholders.
- `styles.css` — mobile-first design system and section styling.
- `script.js` — minimal extension hook for future dynamic content.

## Page Structure

1. **Hero**
   - Placeholder title and subtitle.
   - Includes comments for future metadata fields (title/tone).

2. **Timeline**
   - Vertical timeline skeleton with placeholder date/title/description items.
   - Includes comments for future generation from markdown or JSON.

3. **Gallery**
   - Responsive grid of neutral placeholder blocks (no real images).
   - Includes comments describing image path + caption mapping.

4. **Notes / Reasons**
   - Card-based placeholders with bullet lists.
   - Includes comment for markdown-driven content.

5. **Letter**
   - Centered styled card with placeholder paragraph text.
   - Includes comment for verbatim rendering from a file.

6. **Links / Extras**
   - Placeholder, non-functional links.
   - Includes comment for future playlist/map/extra URLs.

7. **Footer**
   - Minimal sign-off placeholder.

## Future Content Locations

Recommended structure for adding real assets and copy later:

- `/content/site.json` — page-level metadata (hero title/subtitle/tone).
- `/content/timeline.json` or `/content/timeline.md` — timeline milestones.
- `/content/reasons.md` — notes/reasons content.
- `/content/letter.md` — full letter text to render verbatim.
- `/content/links.json` — external links for extras.
- `/content/gallery.json` — image-caption mapping metadata.
- `/photos/` — image files used in the gallery.

## Local Preview

Because this is a static site, you can preview it with any local server.

### Option A: Python

```bash
python3 -m http.server 8000
```

Then open: `http://localhost:8000`

### Option B: VS Code Live Server

- Open the folder in VS Code.
- Start **Live Server** on `index.html`.

## Later Deployment

### GitHub Pages

1. Push this repository to GitHub.
2. In repository settings, enable **Pages**.
3. Select the root branch as the source.
4. Save and wait for the generated URL.

### Netlify

1. Create a new site from this repository.
2. Build command: *(none required for static files)*.
3. Publish directory: repository root (`.`).
4. Deploy and use the generated site URL.

---

This scaffold is designed to be easy to extend while keeping a calm, elegant base style.
