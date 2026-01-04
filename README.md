# Personal site · Associate Professor

This repository hosts a modern single-page profile for a computer science associate professor. It is meant to be deployed to GitHub Pages (`https://<your-handle>.github.io/`).

## Structure

- `index.html` — main content (hero, highlights, research summary, publications, contact).
- `styles.css` — theme with Playfair Display & Source Sans 3, responsive grid, and navigation styles.
- `docs/` — drop-in folder for course / tutorial / lab files (placeholder markdown files provided).
- `teaching.html` — dedicated page for the teaching portfolio (metrics, highlights, open courseware with filters/pagination).
- `blog.html` — simple blog/notes page showcasing featured articles and tag filters.
- `cv.html` — curriculum vitae page built with the same design system (sidebar summary, experience timeline, skills).
- `research.html` — detailed research axes and paginated publication list.

## Deploying to GitHub Pages

1. Create a repository named `<handle>.github.io` on GitHub.
2. Copy these files at the repository root (no subfolder needed).
3. Push to the `main` (or `master`) branch.
4. In the repository **Pages** settings, ensure the source is `main / root`.
5. Wait a few minutes, then browse to `https://<handle>.github.io/`.

## Quick customization

- Update the copy inside `index.html` with your own name, bio, research areas, and project links.
- Swap or add visuals/logos by importing assets and referencing them with `<img>` where needed.
- Adjust theme colors in `styles.css` by tweaking the custom properties (`--accent`, `--bg`, etc.).
- Replace the placeholder markdown files in `docs/` with PDFs or other teaching material and update the links in the “Open courseware” section.
- Swap the sample Unsplash URLs in the hero portrait or gallery with your own photos or team images.
- Populate `teaching.html` with your up-to-date modules and drop your PDF resume at `docs/cv.pdf` (or update the download link).
- Update `research.html` with additional publications (or research highlights) using the pagination structure provided.
- Update `blog.html` to add/remove posts and link each article to a PDF, GitHub repo, or publishing platform.
- Keep `cv.html` aligned with your current academic record (and update `docs/cv.pdf` if needed).

The site only relies on standard HTML/CSS, making hosting and maintenance straightforward.
