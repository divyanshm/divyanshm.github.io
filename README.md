# divyanshm.github.io

A minimal Markdown blog built with [Astro](https://astro.build/) and deployed
to GitHub Pages.

## Write a post

Add a Markdown file under `src/content/blog/`:

```md
---
title: Post title
description: A short summary.
published: 2026-08-18
tags:
  - example
---

Start writing here.
```

Set `draft: true` in the frontmatter to keep a post out of the site and RSS
feed.

Career posts belong under `src/content/blog/career/`. Copy and rename
`_template.md`, then set `draft: false` when the post is ready. Published posts
in that folder automatically appear on the `/career` page.

## Run locally

Install Node.js 22 or newer, then run:

```sh
npm install
npm run dev
```

Open `http://localhost:4321`.

## Publish

1. Create a public GitHub repository named `divyanshm.github.io`.
2. Push this project to its `main` branch.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, select **GitHub Actions** as the source.

Every push to `main` will publish the site to
<https://divyanshm.github.io>.
