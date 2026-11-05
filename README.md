# BlockHeavy website

A buildless static holding page. Open `index.html` directly in a browser; no network connection or dependencies are required. Alternatively, from this directory run `python -m http.server 8000` and open http://localhost:8000/.

## Published site

- Primary site: https://blockheavy.co/
- The `www` address redirects to the primary site over HTTPS.
- Repository: https://github.com/Euuston/blockheavy-website
- GitHub Pages publishes from the `master` branch, repository root. The `CNAME` file records the custom domain.
- HTTPS is enforced by GitHub Pages.

To update the site, edit the static files, review and commit the changes, then push `master` to `origin`. GitHub Pages deploys the updated branch; check the deployment and live site after publishing.

Domain DNS and forwarding are managed separately at NameSilo. Review the existing records and forwarding configuration before making future changes, and preserve unrelated records.

References: [GitHub Pages publishing](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site), [custom domains](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site), and [HTTPS](https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https).
