# Junior Sarr — Portfolio

A minimal, professional portfolio site covering software development and cybersecurity projects.

## Files
- `index.html` — page structure and content
- `style.css` — all styling
- `script.js` — tiny script (just sets the footer year)
- `resume.pdf` — downloadable résumé, linked from the hero button and Contact section

## Deploying with GitHub Pages

1. Create a new GitHub repository (e.g. `junior-sarr.github.io` for a user site, or any name for a project site).
2. Add these three files to the repo root and commit/push them.
3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`, pick the `main` branch and `/ (root)` folder, then **Save**.
5. GitHub will give you a URL (usually `https://<username>.github.io/<repo-name>/`) — it can take a minute or two to go live.

## Notes
- Your phone number from the CV was left off the public site by default, for privacy. Add it to the `contact-list` in `index.html` if you'd like it shown.
- The hero card's "Fingerprint" value is a stylistic detail (not a real cryptographic hash) — feel free to edit or remove it.
- An **Experience** section (Ipoque GmbH, Lancaster University TA role) was added based on your CV. There's more in your CV (volunteering, leadership, hobbies) you could add later if you want a fuller picture.

## Editing content
Everything is in `index.html` — project cards, bio, and contact details are plain text/HTML, no build step required.
