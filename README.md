# Ha Minh Hieu — Academic Homepage

Personal academic website built with the **[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)** Jekyll theme (remote theme), hosted on GitHub Pages.

**Live:** https://langkhachhoha.github.io/Profile/

## Structure
- `_config.yml` — site + author profile + theme settings
- `_data/navigation.yml` — top nav (Publications, CV)
- `_pages/about.md` — home page (About / Research Interests / News)
- `_pages/publications.md` — publications list
- `cv.pdf` — CV (linked from the top nav; replace with your real file)
- `assets/images/bio-photo.jpeg` — profile photo

## How to edit
Edit the Markdown files in `_pages/` and the values in `_config.yml`, then commit & push to `main`. The site rebuilds and deploys automatically via `.github/workflows/jekyll.yml`.

## Local preview (optional)
```bash
bundle install
bundle exec jekyll serve
```
Then open http://localhost:4000/Profile/
