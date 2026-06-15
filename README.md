# wu-lichao.github.io

Source for my personal academic website, built with Jekyll and a small custom theme.

## Local development

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Structure

- `_config.yml` — site title, author/contact info, navigation links
- `index.md` — home page (bio, news, awards, experience, research areas)
- `publications.md`, `teaching.md`, `service.md`, `positions.md`, `cv.md`, `blog.md` — site pages
- `_teaching/` — one file per course, listed on the Teaching page
- `_posts/` — blog posts, listed on the Blog page
- `_layouts/`, `_includes/`, `assets/css/style.css` — layout and styling

To add your CV, place a PDF at `assets/files/cv.pdf`.
