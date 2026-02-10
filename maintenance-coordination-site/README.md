# Maintenance Coordination Site

Static GitHub Pages (Jekyll) site for multi-complex maintenance coordination in South Africa.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Site runs at `http://127.0.0.1:4000`.

## Data-driven complexes

Edit `_data/complexes.yml` to manage complex metadata and intake links.

## Deployment

GitHub Actions deploys the site to GitHub Pages on pushes to `main`.
