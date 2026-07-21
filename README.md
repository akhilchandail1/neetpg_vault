# NEET Cheatsheets

A static, high-yield revision library for NEET 2026.

## What's included

- A responsive landing page with filters for all 19 cheatsheets
- Subject-specific cheatsheets with tabbed revision sections
- A browser-saved PYQ revision dashboard for subject and paper tracking
- A shared light, minimal visual theme across every page
- No build step, framework, or installation required

## Open locally

Open [index.html](index.html) in any modern browser.

For the most reliable local preview, run:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish

This project works directly with GitHub Pages, Netlify, or Vercel. Deploy the repository root as a static site; `index.html` is the homepage.

Before publishing, replace the placeholder GitHub URL in the footer of `index.html`:

```html
https://github.com/your-username/NEET-cheatsheets
```

## Structure

```text
index.html                  Landing page and cheatsheet directory
cheatsheet-theme.css        Shared visual theme for subject pages
pyq-dashboard.html          Personal NEET PG PYQ revision tracker
*_cheatsheet.html           Individual subject cheatsheets
```

## Suggested domain

`NEETvault.com` — check availability with your preferred domain registrar before registering it.

## Note

These notes are intended for revision support. Always cross-check important facts with current, authoritative medical references.
