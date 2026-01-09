# CAE Website

This is the website for the City Analytics Exchange. It's created with Zola and deployed to GitHub Pages via GitHub Actions.

## Writing a new post

### Clone this git repository

Then start writing!

### Draft it

Create a new markdown file in the `/content/` directory. You can copy this for starters and modify it (from the original "Welcome" post):

```
+++
title = "Welcome to the City Analytics Exchange Blog"
date = 2026-01-09
description = "City Analytics Exchange has a website"

[taxonomies]
categories = ["Announcements"]
tags = ["welcome", "community"]

[extra]
author = "Sam"
+++

CAE has existed for a few years on Slack and (barely) LinkedIn. Let's try a website for a more public, stable, open presence! I'd love to hear ideas from members about how to use this space.
```

### Review it

Install Zola - it's a single binary file, [here are instructions for any operating system](https://www.getzola.org/documentation/getting-started/installation/) - and then in this repo's main directory, run `zola serve`. You should then be able to browse to `127.0.0.1:1111` on your local machine and see your post.

Edit until you are satisfied.

### Ship it

Create a new branch in the repo and submit a pull request to this repo with your post. Sam will merge it and the site will rebuild with your post!