# AvaMed slide deck

A small [Jekyll](https://jekyllrb.com/) site that renders a slideshow with
[reveal.js](https://revealjs.com/) (v3.9, vendored in `node_modules/`).

Originally created from GitHub's "Introduction to GitHub" Learning Lab
template; the course material has been removed.

## Adding slides

Each slide is a Markdown file in `_posts/`. Slides are shown in filename
order, so name them `0000-01-NN-<name>.md`:

```markdown
---
layout: slide
title: "Slide title"
---

Slide content in Markdown.
```

## Running locally

```sh
script/setup    # install gems
script/server   # serve at http://localhost:4000
```

## Publishing

Enable GitHub Pages for the `main` branch in the repository settings.

## History

AvaMed's earliest web presence on record is a WordPress.com site at
avamed.org, archived by the Wayback Machine in early 2016:
<https://web.archive.org/web/20160306102157/http://avamed.org/>
