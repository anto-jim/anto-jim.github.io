# anto-jim.github.io

Personal website of **Antonio Jiménez Godínez**, published at [anto-jim.dev](https://www.anto-jim.dev).

Hugo static site (English) with about, education, and experience sections, plus a downloadable résumé.

## Stack

- [Hugo](https://gohugo.io/) Extended
- Theme: [adritian-free-hugo-theme](https://github.com/zetxek/adritian-free-hugo-theme) (git submodule)
- Hosting: GitHub Pages (`Deploy Hugo site to Pages` workflow)

## Local development

```bash
git clone --recurse-submodules https://github.com/anto-jim/anto-jim.github.io.git
cd anto-jim.github.io
hugo server
```

If the theme directory is empty:

```bash
git submodule update --init --recursive
```

Production-style build:

```bash
hugo --gc --minify
```

Useful paths:

| Path | Purpose |
|------|---------|
| `hugo.toml` | Site config and menus |
| `data/homepage.yml` | Section toggles and education |
| `i18n/en.yaml` | Page copy |
| `content/experience/` | Job entries |
| `layouts/` | Theme overrides |
| `static/pdf/` | Résumé PDF |

## License

**Site code** in this repository (configuration, layouts, assets you added here) is released under the [MIT License](LICENSE). Copyright (c) 2024 Antonio Jiménez Godínez.

**Website content** — including biography text, photographs, and the résumé PDF — is **all rights reserved**. You may not reuse that material without permission.

**Theme:** [adritian-free-hugo-theme](https://github.com/zetxek/adritian-free-hugo-theme) is MIT-licensed by its authors (including copyright held by Radity and Adrián Moreno Peña). See the theme’s own `LICENSE` file in the submodule. That license covers the theme, not your personal content.
