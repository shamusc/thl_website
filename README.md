# Turtle House Labs website

Source for the Turtle House Labs website. Built with [Hugo](https://gohugo.io/) using the [HugoBlox Research Group](https://github.com/HugoBlox/theme-research-group) starter, deployed to GitHub Pages.

## Site structure

| Path | What it controls |
|------|------------------|
| `config/_default/hugo.yaml` | Site title, base URL, output formats, taxonomies |
| `config/_default/params.yaml` | Appearance, SEO, header, footer, search, repository link |
| `config/_default/menus.yaml` | Top navigation |
| `config/_default/languages.yaml` | Site languages (single-language `en`) |
| `config/_default/module.yaml` | Hugo Modules imports (the theme is pulled from here, not vendored) |
| `content/_index.md` | Homepage landing page |
| `content/research/_index.md` | Research page |
| `content/projects/_index.md` | Projects page |
| `content/about/_index.md` | About / founder bio |
| `content/contact/index.md` | Contact page |
| `content/authors/admin/_index.md` | Primary user profile (Shamus Cooley) |
| `assets/media/` | Site imagery referenced by pages |
| `static/` | Files served at the site root (favicon, downloads, CNAME for custom domain) |
| `.github/workflows/publish.yaml` | GitHub Pages deployment via GitHub Actions |

## Local development

Requires Hugo **extended** v0.135.0 or newer and Go 1.15+ (Hugo Modules fetches the theme at build time).

```bash
hugo server -D
```

The site will be served at `http://localhost:1313/`.

## Deployment

The site deploys to GitHub Pages automatically on every push to `main` via `.github/workflows/publish.yaml`.

To set up GitHub Pages for the first time:

1. Push this repository to GitHub.
2. In the repo settings, go to **Pages** and set **Source** to **GitHub Actions**.
3. Push to `main`. The workflow will build the site and deploy it.
4. Once the default Pages URL works, configure a custom domain by:
   - Adding the domain in **Settings → Pages → Custom domain**.
   - Adding a `static/CNAME` file containing the domain.
   - Configuring DNS at the registrar.

## Updating site content

- **Edit text on a page:** open the relevant Markdown file under `content/`.
- **Add a navigation link:** edit `config/_default/menus.yaml`.
- **Change the site title or base URL:** edit `config/_default/hugo.yaml`.
- **Change the footer:** edit `footer.copyright.notice` in `config/_default/params.yaml`.

## License

Site content is © Turtle House Labs. The HugoBlox theme is MIT-licensed by George Cushen and is pulled in as a Hugo Module at build time (not vendored in this repository).
