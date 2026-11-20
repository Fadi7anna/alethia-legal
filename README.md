# alethia legal website

A lightweight public legal-information website for alethia, a first-party automation application for authorized Facebook Page and, where configured, Instagram publishing workflows.

## Files

- `index.html` — legal information portal
- `privacy.html` — privacy policy
- `terms.html` — terms of service
- `data-deletion.html` — instructions to disconnect Meta access and request deletion of applicable local records
- `assets/style.css` — shared responsive styling
- `.nojekyll` — tells GitHub Pages to serve the static files without Jekyll processing

## Public URLs

- Home: https://fadi7anna.github.io/alethia-legal/
- Privacy policy: https://fadi7anna.github.io/alethia-legal/privacy.html
- Terms of service: https://fadi7anna.github.io/alethia-legal/terms.html
- Data deletion: https://fadi7anna.github.io/alethia-legal/data-deletion.html

These URLs are available after GitHub Pages is enabled and the deployment completes.

## Deployment

The intended GitHub Pages source is the `main` branch and repository root (`/(root)`).

To enable or verify it:

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. Wait for the Pages deployment workflow to finish and confirm the site responds over HTTPS at the URLs above.

GitHub Pages for this public repository is available without a custom build step. The `.nojekyll` file keeps the static site independent of Jekyll.

## Maintenance

- Keep the privacy policy aligned with the data the application actually processes and where it is stored. Do not add unverified security, retention, or deletion claims.
- Update the effective date in all legal documents when their substantive terms change.
- If the app’s Meta permissions, connected platforms, local ledger, or deletion process changes, review the privacy and deletion documents and update Meta Developer settings as needed.
- Keep credentials, access tokens, app secrets, local configuration, reports, and publishing ledgers out of this public repository.
- The published issue page is a public contact route. Do not request sensitive details in public; arrange a private follow-up channel where needed.

## Local review

Open `index.html` in a browser to preview the site. The pages use semantic HTML, one shared stylesheet, no JavaScript, no analytics, and no external assets.
