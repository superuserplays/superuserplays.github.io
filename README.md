# superuserplays

Game reviews and playthroughs blog. No ads, no fluff, no face cam.

Live at: https://superuserplays.github.io

## Stack

- [Hugo](https://gohugo.io/) — static site generator
- [Terminal theme](https://github.com/panr/hugo-theme-terminal) — base theme, heavily customized
- GitHub Pages — hosting
- GitHub Actions — automatic builds on push

## Structure

- `content/about.md` — about page
- `content/reviews/` — game reviews
- `content/playthroughs/` — playthrough series
- `content/_index.md` — homepage
- `layouts/partials/` — custom partials (hero, header, logo, menu)
- `layouts/partials/extended_head.html` — color overrides and custom CSS
- `static/` — favicon and static assets

## Adding content

Create a new markdown file in `content/reviews/` or `content/playthroughs/`:

    ---
    title: "Game Title — Review"
    date: YYYY-MM-DD
    ---

    Write your review here.

Push to main and GitHub Actions builds and deploys automatically.

## Theme

Dracula color palette. Fira Code font. Terminal aesthetic.
