# lzn87.github.io

Personal website of Zhaonan Li, served by GitHub Pages (Jekyll) at https://lzn87.github.io/.
The layout is adapted from [Jon Barron's website](https://jonbarron.info/) via a Jekyll Now fork.

## Updating

- **Publication**: add `_posts/YYYY-MM-DD-<slug>.markdown` with `categories: [research]` and the
  front matter fields `title`, `authors`, `venue`, and optionally `highlight` (red badge, e.g. `Oral`),
  `status: review` (lists it under "Under Review & Preprints"), `image`, `paper`, `arxiv`, `code`,
  `dataset`, `note`. Entries are sorted by the file date, newest first. Do not use a future date:
  Jekyll skips future posts.
- **News**: add `_posts/YYYY-MM-DD-news-<slug>.markdown` with `layout: post`, `categories: news` and
  one line of Markdown as the body. The page shows the newest 8.
- **Images**: put thumbnails in `images/` at about 640 px wide (JPEG) to keep the page light.
- Pushing to `master` publishes the site.
