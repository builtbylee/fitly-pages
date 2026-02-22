# Ryval Pages

Public-facing pages for the Ryval app (privacy policy, terms of service, support). Hosted via GitHub Pages.

## Live URLs

| Page | URL |
|------|-----|
| Home | https://builtbylee.github.io/ryval-pages/ |
| Privacy Policy | https://builtbylee.github.io/ryval-pages/privacy |
| Terms of Service | https://builtbylee.github.io/ryval-pages/terms |
| Support | https://builtbylee.github.io/ryval-pages/support |

## How to Edit

All content is in **Markdown** files at the repo root:

| File | Page |
|------|------|
| `index.html` | Home page |
| `privacy.md` | Privacy Policy |
| `terms.md` | Terms of Service |
| `support.md` | Support page |

To update a page:

1. Edit the file directly on GitHub (click the pencil icon) or locally.
2. Commit and push to `main`.
3. GitHub Pages rebuilds automatically. Changes are live within 1-2 minutes.

## Structure

```
_config.yml          # Jekyll site config
_layouts/default.html # Shared HTML layout (header, nav, footer)
assets/style.css     # Stylesheet (light/dark mode, mobile-friendly)
assets/icon-ryval.png # App icon (used as site favicon and hero)
index.html           # Home page
privacy.md           # Privacy Policy
terms.md             # Terms of Service
support.md           # Support page
```

## App Store Values

**Google Play Console:**
- Privacy Policy URL: `https://builtbylee.github.io/ryval-pages/privacy`
- Support URL: `https://builtbylee.github.io/ryval-pages/support`

**App Store Connect:**
- Privacy Policy URL: `https://builtbylee.github.io/ryval-pages/privacy`
- Support URL: `https://builtbylee.github.io/ryval-pages/support`
- Terms of Use URL (optional field): `https://builtbylee.github.io/ryval-pages/terms`

## Local Preview

```bash
# Requires Ruby and Jekyll
gem install bundler jekyll
bundle init
bundle add jekyll
bundle exec jekyll serve
# Open http://localhost:4000/ryval-pages/
```
