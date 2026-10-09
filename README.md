# one-minute-sam-altman

为 ADHD 大脑设计的一分钟学习法 × [Sam Altman 博客](https://blog.samaltman.com/)（Posthaven 托管，121 篇，2013–2026）的精读笔记与语料。

## 内容

- **`GEMS.md`** — 金句集：按主题整理，每条链回原文
- **`LESSONS.md`** — 逐条精读（中文讲解）：原文 + 翻译 + 解读 + 怎么用，每条 1 分钟读完
- **`posts.json`** — 全量语料：121 篇文章的标题、URL、发布日期和 HTML 正文

## 数据来源

内容镜像自公开 Atom feed（`https://blog.samaltman.com/posts.atom`）及各文章页面。语料结构：

```json
[{ "title": "...", "url": "...", "published": "YYYY-MM-DD", "content": "<html>", "content_len": 1234 }]
```

博客原文版权归 Sam Altman 所有，本仓仅作阅读/研究辅助。

---

English: [README.en.md](README.en.md)
