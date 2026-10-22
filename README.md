# konstinik.github.io

Source of my personal academic homepage, live at <https://konstinik.github.io>.
Built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Viewing the site locally

Prerequisites: Ruby 3.3, Bundler, and the gems from `Gemfile` (run `bundle install` once if they are missing).

From the repository root:

```bash
bundle exec jekyll serve --livereload
```

Then open <http://127.0.0.1:4000/>. Jekyll rebuilds on every saved change and, with `--livereload`,
refreshes the browser automatically. Stop the server with Ctrl+C.

Notes:

- Changes to `_config.yml` are not picked up by the watcher; restart the server after editing it.
- If port 4000 is already in use, an old server is still running: `pkill -f "jekyll serve"`.
- To build without serving (output goes to `_site/`, which is git-ignored): `bundle exec jekyll build`.

## Where the content lives

| Path | Contents |
|---|---|
| `_data/profile.yml` | Name, positions, bio, research interests, contact links |
| `_data/authors.yml` | Co-author links; marks my own name in bold |
| `_data/navigation.yml` | Navigation bar entries |
| `_data/display.yml` | Which homepage sections are shown, footer text |
| `_publications/` | One file per paper |
| `_news/` | One file per news item |
| `_showcase/` | One file per showcase entry |
| `assets/` | Images, CSS, and other static files |

## Deployment

Pushing to `main` triggers the GitHub Pages build. There is no manual deploy step.

## Credits

Based on the [academic-homepage](https://github.com/luost26/academic-homepage) template by Shitong Luo (MIT License, see `LICENSE`).
