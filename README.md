# JSForm Website

Low-maintenance public website for JSForm, prepared for GitHub Pages.

## Design

- Static HTML and CSS only
- No build step, package manager, analytics, cookies, remote fonts, or third-party scripts
- Responsive desktop and mobile layouts
- GitHub Pages deployment through GitHub Actions

## Preview locally

Open `index.html` directly, or serve this directory with any static web server.

## Publish with GitHub Pages

1. Create a public GitHub repository for this website.
2. Add that repository as the Git remote and push the `main` branch.
3. In **Settings -> Pages**, select **GitHub Actions** as the source.
4. The included workflow publishes the static files after every push to `main`.
5. GitHub provides a temporary `github.io` address. A recovered custom domain can be attached later.

## Publication maintenance

- Review the four approved School Bus Routes screenshots whenever the sample interface changes.
- Update the release link, checksum, and version copy for every published release.
- Update the absolute Open Graph URL if a custom domain replaces GitHub Pages.

## Files

- `index.html` - main project site
- `support.html` - support-reporting guidance
- `security.html` - private vulnerability reporting guidance
- `privacy.html` - website privacy statement
- `assets/social-preview.png` - JSForm link-preview artwork
- `assets/favicon.ico` and companion PNG files - browser and device icons
- `.github/workflows/pages.yml` - GitHub Pages deployment

## License

The copied JSForm project license is included in `LICENSE`. Website prose and artwork licensing should be finalized before third-party reuse is invited.
