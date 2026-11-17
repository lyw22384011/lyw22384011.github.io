# lyw22384011.github.io

## Adding a blog post

1. Create a Markdown file in `_posts/` named `YYYY-MM-DD-short-title.md`. The date and slug form part of the article's URL.
2. Add the front matter below and write the article in Markdown. Use the article's language for its title, summary, and back-link label.
3. Commit the file to the publishing branch when it is ready. GitHub Pages builds the article and adds it to `/blog/` in reverse chronological order.

```markdown
---
title: My post title
lang: en
language_label: English
description: A short summary for the blog list.
back_label: All posts
---
Write the post here.
```
