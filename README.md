# BlockHeavy website

A buildless static holding page. Open `index.html` directly in a browser; no network connection or dependencies are required. Alternatively, from this directory run `python -m http.server 8000` and open http://localhost:8000/.

## Future GitHub Pages deployment

These steps are for a future authorised migration; none have been performed.

1. Create a dedicated GitHub repository and push the approved files. The entry file `index.html` must be at the root of the selected publishing source.
2. In repository Settings → Pages, select deployment from a branch and choose the branch and root folder. Visit and verify the GitHub Pages URL provided in settings.
3. Before changing the domain, review NameSilo's existing DNS **and URL forwarding**, including email-related records, and plan the cutover. Verify the custom domain with GitHub and add it in Pages settings before changing DNS. Follow GitHub's current documentation for the applicable apex and `www` records; preserve email records.
4. Once DNS and certificate provisioning are complete, enable Enforce HTTPS when available. Verify both `blockheavy.co` and `www.blockheavy.co`, including redirects, HTTPS and the loaded site.

References: [Create a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site), [Manage a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site), and [Secure with HTTPS](https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https).
