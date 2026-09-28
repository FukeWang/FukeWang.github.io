# fukewang.github.io

Personal academic website of Fuke Wang, built with [al-folio](https://github.com/alshedivat/al-folio) and hosted on GitHub Pages.

## Editing content

| What                  | Where                                        |
| --------------------- | -------------------------------------------- |
| Homepage / bio        | `_pages/about.md`                            |
| Publications          | `_bibliography/papers.bib` (BibTeX)          |
| News                  | `_news/`                                     |
| Blog posts            | `_posts/YYYY-MM-DD-title.md`                 |
| Projects              | `_projects/`                                 |
| Teaching              | `_teachings/`                                |
| Contact & socials     | `_data/socials.yml`                          |
| Site settings         | `_config.yml`                                |

## Local preview

```bash
docker-compose up -d   # then open http://localhost:8080
docker-compose down    # stop
```

## Deployment

Pushing to `main` automatically rebuilds the site via GitHub Actions
(`.github/workflows/deploy.yml`) and publishes it to the `gh-pages` branch,
which GitHub Pages serves at https://fukewang.github.io.

## License

Theme: [al-folio](https://github.com/alshedivat/al-folio) (MIT). Site content: © Fuke Wang.