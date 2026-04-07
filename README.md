# Support site (GitHub Pages)

Static pages for **Currency Conversion** apps by **Dmitriy Andrianov** — usable as the **Support URL**, **Privacy Policy URL**, and **Terms** link for App Store Connect and future apps in the same product line.

## Files

| File | Purpose |
|------|--------|
| `index.html` | Universal support hub |
| `privacy.html` | Privacy Policy (third parties, U.S. children’s privacy, state rights) |
| `terms.html` | Terms of Use (USA, liability, purchases) |
| `styles.css` | Shared styling |

Contact on all pages: **andrianventures@gmail.com**.

## Publish on GitHub Pages

1. Push the repo (including `docs/app-site/`).

2. **Settings → Pages** → Deploy from branch → **`/docs`**.

3. With files under `docs/app-site/`, public URLs look like:
   - `https://<username>.github.io/<repo>/app-site/`
   - Support: same path; Privacy: `.../privacy.html`; Terms: `.../terms.html`

4. Wait for the first deploy; confirm `styles.css` loads (same folder as HTML).

### Shorter URL (no `/app-site/`)

Move the four files into `docs/` root, or use a dedicated `username.github.io` repository.

## App Store Connect

- **Support URL:** live `index.html` URL (or folder URL with trailing slash).
- **Privacy Policy URL:** `privacy.html` when Apple or your questionnaire asks for a public policy.
- **Marketing URL:** optional.

## Local preview

From `docs/app-site`:

```bash
npx --yes serve .
```
