# Distributed Systems with Docker & Kubernetes — course site

This repo serves the built course site via GitHub Pages, deployed from the
`gh-pages` branch (published there by the private src repo on every content
change).

This `main` branch holds nothing but `.github/workflows/pages.yml` — the
deploy workflow that publishes `gh-pages`'s content. It lives here,
deliberately not on `gh-pages`, because that branch is fully replaced by
every deploy.

**Live site:** https://schoolofdevops.github.io/k8s-distributed-systems/
