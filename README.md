# Open Hearts Club Website Preview v0.1

This package is designed for the existing `OpenHeartsClub-Website` GitHub repository and GitHub Pages.

## Publish with GitHub Pages

1. Back up or screenshot the current repository/site before replacing files.
2. In the `OpenHeartsClub-Website` repository, upload/copy the contents of this package into the repository root. Keep `index.html`, `CNAME`, `.nojekyll`, `css/`, `js/`, `images/`, and `pages/` at the root.
3. Commit the changes to `main` with a message such as `Website Preview v0.1 - First Public Expression`.
4. Open **Settings -> Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select branch **main** and folder **/(root)**, then Save.
5. GitHub will publish the branch. The first deployment can take several minutes. Verify the temporary GitHub Pages URL before changing DNS.
6. In **Settings -> Pages -> Custom domain**, enter `openheartsclub.org` and Save. The included `CNAME` file already contains `openheartsclub.org`.
7. At your domain registrar/DNS provider, configure the DNS records exactly as GitHub's current custom-domain instructions specify. Do not guess DNS values; use GitHub's live documentation/settings.
8. After DNS verification completes, enable **Enforce HTTPS** in GitHub Pages settings when available.
9. Test desktop/mobile navigation, every page, the logo, and HTTPS at `https://openheartsclub.org`.
10. Capture screenshots of the homepage and every major page and preserve them in the historical website archive as Website Preview v0.1.

## Important release notes

- This is a genuine first Website Preview, not a placeholder page.
- It does not claim that OHC is the “original,” “official,” or “only” Open Hearts Club.
- Do not use the ® symbol. Trademark legal clearance is still pending.
- The site contains a medical-information boundary notice and does not publish personal contact information.
- Broad paid promotion, major merchandise/signage purchases, and federal trademark filing should wait for counsel guidance.

## Updating the site

Edit the HTML/CSS files, commit to `main`, and GitHub Pages will republish from the configured source branch. Before each major version, preserve screenshots and a repository tag/release if desired.

Official GitHub documentation:
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## v0.1.1 path fix
This release replaces site-root absolute links (`/css/...`, `/pages/...`, `/images/...`)
with repository-relative links. This allows the preview to work both:
- at a GitHub Pages project URL such as `https://openheartsclub.github.io/OpenHeartsClub-Website/`
- and at the custom domain `https://openheartsclub.org/`
