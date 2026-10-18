# Codezen's Vlog

Live at **https://codezenblog.github.io/**

Anyone can read it. Only people with write access to this repo can post, so right now that's just you.

## Add a new post

Make a new file in `_posts/` named `YYYY-MM-DD-your-title.md`, for example `_posts/2026-10-20-my-first-shipping-day.md`:

```markdown
---
layout: post
title: My first shipping day
description: One-line summary shown on the homepage.
tags: [building]
youtube: dQw4w9WgXcQ        # optional: the ID from a YouTube link
# video: /assets/videos/day1.mp4   # optional: or a video file in this repo
# image: /assets/images/cover.jpg  # optional: cover image
---

Write the post here in **Markdown**.
```

Commit it, and the site rebuilds in about a minute.

**From your phone or browser:** open the repo on github.com, go to `_posts`, then **Add file → Create new file**, paste the template, and commit.

**From your computer:**

```bash
git add _posts && git commit -m "New post" && git push
```

## Images and videos

- Put images in `assets/images/` and use them in a post with `![alt text]({{ site.baseurl }}/assets/images/photo.jpg)`.
- For videos, use `youtube:` in the front matter. GitHub limits files to 100 MB, so hosting video on YouTube works better than committing it.

## Unpublish a post

Delete its file from `_posts/`, or add `published: false` to its front matter.
