# Thoughts

A small Jekyll site for short or long personal writing.

## Write a thought

Create a Markdown file in `_posts` named `YYYY-MM-DD-a-stable-slug.md`:

```markdown
---
date: 2026-09-06
title: "" # optional
tags:
  - privacy
---

Privacy isn't secrecy.

It's having something that belongs to you.
```

The filename slug becomes part of the permanent URL, so choose it carefully. To publish at `njmulsqb.github.io/thoughts/`, retain `baseurl: "/thoughts"` in `_config.yml`.

## Preview locally

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000/thoughts/`.

Dependencies are installed into `vendor/bundle` inside this project, as configured in `.bundle/config`. Do not use `sudo` for `bundle install` or Jekyll commands.
