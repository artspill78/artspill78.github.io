# Setup

This repository is a GitHub Pages user site. Because it's named
`artspill78.github.io`, GitHub Pages serves it automatically from the
`main` branch — no build step or configuration is required to go live.

## Local development

1. Clone the repo:
   ```
   git clone https://github.com/artspill78/artspill78.github.io.git
   cd artspill78.github.io
   ```
2. Preview the site locally with any static file server, for example:
   ```
   python3 -m http.server 8000
   ```
   Then open `http://localhost:8000` in a browser.

   If the site uses Jekyll (GitHub Pages' default static site generator),
   install Ruby and Bundler, add a `Gemfile` with the `github-pages` gem,
   run `bundle install`, and serve with `bundle exec jekyll serve` instead.

## Deployment

Pushing to the `main` branch publishes the site automatically at
https://artspill78.github.io/. No CI/CD configuration is needed — GitHub
Pages rebuilds and deploys on every push.

## Custom domain (optional)

To use a custom domain, add a `CNAME` file to the repository root
containing the domain name, and configure the domain's DNS to point at
GitHub Pages per GitHub's documentation.
