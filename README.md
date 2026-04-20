# Grumpy Hippo's blog

Personal site built with [Jekyll](https://jekyllrb.com/) and the [Minima](https://github.com/jekyll/minima) theme, published with [GitHub Pages](https://pages.github.com/).

**Live site:** [https://ning-tan.github.io/grumpyhippo/](https://ning-tan.github.io/grumpyhippo/)

## Edit content

- **Site settings:** `_config.yml` (title, description, `url` / `baseurl` for GitHub Pages).
- **Home page:** `index.md`
- **Posts:** add Markdown files under `_posts/` using the `YYYY-MM-DD-title.md` naming convention.

If this repository is forked or the GitHub username or repo name changes, update `url` and `baseurl` in `_config.yml` so links and assets resolve correctly.

## Run locally

Requires [Ruby](https://www.ruby-lang.org/) and [Bundler](https://bundler.io/).

```bash
bundle install
bundle exec jekyll serve
```

Then open the URL Jekyll prints (usually `http://127.0.0.1:4000/grumpyhippo/` — include `baseurl` when serving locally).

---

© 2026 Grumpy Hippo
