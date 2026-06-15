# wu-lichao.github.io

Personal homepage — a single static `index.html`. No Jekyll, no Ruby, no build step.

## Files
- `index.html` — the whole site (all styles are inline).
- `images/my_photo.jpg` — profile photo. Replace this file to change the photo.
- `404.html` — fallback page for unknown URLs.

## Deploy
GitHub Pages serves these files directly. Just commit and push to the
default branch; the site is live at https://wu-lichao.github.io/ within a minute.
No GitHub Actions build is required.

## Edit
Open `index.html`, change the text, commit. Common edits:
- **Add a paper** — copy one `<li class="pub">…</li>` block in the Publications
  section and change the title, link, and authors. Wrap your own name in
  `<span class="me">Lichao Wu</span>` to bold it.
- **Add a news / service / activity item** — copy one `<li>` in that section.
- **Colours & fonts** — the CSS variables at the top of the `<style>` block.
