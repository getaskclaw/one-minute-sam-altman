# one-minute-sam-altman

A one-minute learning method designed for ADHD brains × notes and data from [blog.samaltman.com](https://blog.samaltman.com) — Sam Altman's personal blog (Posthaven-hosted, 121 posts, 2013–2026).

## Contents

- **`GEMS.md`** — curated quotes, organized by theme, each linked to its source post
- **`LESSONS.md`** — 逐条精读（中文讲解）：原文 + 翻译 + 解读 + 怎么用 — each entry readable in one minute
- **`posts.json`** — full corpus: title, URL, publish date, and HTML content for all 121 posts

## Data source

Content mirrored from the public Atom feed (`https://blog.samaltman.com/posts.atom`) and post pages. Corpus structure:

```json
[{ "title": "...", "url": "...", "published": "YYYY-MM-DD", "content": "<html>", "content_len": 1234 }]
```

Blog content copyright Sam Altman. This repo is a reading/research aid.
