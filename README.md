# MS Faria — personal portfolio

A single-page portfolio for **Mahbuba Sultana Faria (MS Faria)**, a BSc in Computer Science and Engineering undergraduate at Chittagong Independent University.

## Plan and design

- Introduce Faria with a clear name, student identity, and an original code illustration.
- Follow with an introduction, three CSE learning directions, and practical software-development principles.
- Use warm ivory, forest green, lime accents, generous spacing, and system fonts. All artwork is HTML/CSS; no image downloads or third-party services are required.
- Keep content responsive, keyboard accessible, and usable without JavaScript. Respect reduced-motion preferences.
- Present learning directions rather than unverified qualifications. No projects, contact addresses, social profiles, graduation dates, or achievements have been invented.

## Files

- `index.html` — all content, metadata, semantic sections, and native disclosure cards.
- `styles.css` — all styling, responsive layouts, and reduced-motion support.
- `script.js` — mobile navigation, current-section navigation state, and the footer year.
- `.nojekyll` — tells GitHub Pages to serve the static files directly.

Exactly one HTML, one CSS, and one JavaScript file. No framework, packages, build step, analytics, or external font requests.

## Preview locally

Open `index.html` directly in a browser, or run the following from this directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Visit `http://127.0.0.1:8000`. Stop the server with Ctrl+C.

## Publish manually to GitHub Pages

1. Put these files at the root of a GitHub repository and push them to the publishing branch (typically `main`).
2. In the repository's **Settings → Pages**, choose **Deploy from a branch**.
3. Select that branch and **/ (root)**, then save.
4. Open the URL GitHub displays after deployment completes.

The site uses relative asset paths and in-page anchors, so it supports both `username.github.io` and `username.github.io/repository/` without configuration. No deployment has been performed by this local build.

## Personalize before publishing

Review the first-person introduction and learning interests with Faria. Update content directly in `index.html`; adjust colors through the custom properties at the start of `styles.css`. Add verified projects and contact/social links when available. The current version deliberately has no nonfunctional contact form or placeholder project links.

## Quick manual checks

Check desktop and narrow mobile layouts; use Tab and Enter to navigate; open each learning card; exercise the mobile menu and Escape key; check the page without JavaScript; and confirm reduced-motion settings disable smooth scrolling.
