+++
title = "Hello, World"
date = 2025-01-01
+++

This garden is a folder of Markdown, a config file, and nothing else. No
JavaScript, no theme marketplace, no build cache to debug at midnight.

## A small beginning

Write a post, give it a title and a date, and ByggLeaf will place it in the
article stream in reverse chronological order. Links, assets, and pages all
use the `baseurl` from `byggleaf.toml`.

> A digital garden should feel like paper, not like a dashboard.

A few things worth knowing:

- `content/posts/` is for dated writing.
- `content/about/index.md` is a hidden page linked only from the navbar.
- `content/statement/index.md` is a hidden page not linked from anywhere.
- `assets/img/` is copied to `public/assets/img/` untouched.

When you are ready, edit `byggleaf.toml`, run `byggleaf build`, and serve the
result with `byggleaf serve`.
