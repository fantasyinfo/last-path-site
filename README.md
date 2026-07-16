# Last Path

Official website for **Last Path** — a relaxing arrow-sliding puzzle game.

Slide. Think. Escape.

## Contents

- `index.html` — landing page (about, gameplay screenshots, puzzle shapes, features)
- `privacy.html` — Privacy Policy
- `terms.html` — Terms & Conditions
- `support.html` — Support / FAQ
- `style.css` — shared stylesheet for all pages
- `assets/screenshots/` — in-game screenshots used across the site

## Before you publish

1. **Google Play link** — every "Get it on Google Play" button currently
   points to `#`. Once the app is live, replace those `href="#"` values
   with your real Play Store listing URL (search for `href="#"` across the
   HTML files).
2. **Favicon** — `assets/favicon.png` is referenced but not included. Drop
   in a square PNG (512×512 recommended) at that path, or remove the
   `<link rel="icon">` tags if you'd rather skip it.
3. **Support email** — currently set to `shailisharmabrt@gmail.com` in
   `support.html`. Update if that changes.
4. **Developer name in Play Console** — make sure the name you enter in
   Google Play Console matches how you refer to yourself/your studio; the
   policy pages here intentionally avoid a specific developer/company name
   so you can add it wherever your listing requires it.

## Deploying with GitHub Pages

1. Push this repository to GitHub (public).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then **Save**.
5. Wait about a minute — GitHub will give you a URL like:

   ```
   https://<your-username>.github.io/last-path-site/
   ```

Use these URLs in the Google Play Console:

| Page          | URL                                                              |
|---------------|-------------------------------------------------------------------|
| Home          | `https://<your-username>.github.io/last-path-site/`              |
| Privacy       | `https://<your-username>.github.io/last-path-site/privacy.html`  |
| Terms         | `https://<your-username>.github.io/last-path-site/terms.html`    |
| Support       | `https://<your-username>.github.io/last-path-site/support.html`  |

## License

Site code is available under the MIT License — see `LICENSE`. Game assets
(screenshots, artwork) are © 2026 Last Path and not covered by that license.