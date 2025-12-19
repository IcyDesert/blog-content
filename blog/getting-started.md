---
title: "Getting Started - 开始使用"
description: "Learn how to use this blog framework. 学习如何使用这个博客框架。"
pubDate: 2025-12-18
tags: ["tutorial", "guide", "教程"]
---

# Getting Started 开始使用

本文将介绍如何使用这个博客框架。This article will introduce how to use this blog framework.

## 创建新文章 Creating New Posts

在 `src/data/blog/` 目录下创建新的 Markdown 文件：

Create a new Markdown file in the `src/data/blog/` directory:

```markdown
---
title: "Your Post Title"
description: "Your post description"
pubDate: 2025-12-19
tags: ["tag1", "tag2"]
author: "Your Name"
---

Your content here...
```

## Frontmatter 字段说明

| 字段 Field | 类型 Type | 必填 Required | 说明 Description |
|-----------|----------|--------------|-----------------|
| title | string | ✅ | 文章标题 |
| description | string | ✅ | 文章描述 |
| pubDate | date | ✅ | 发布日期 |
| tags | string[] | ❌ | 标签列表 |
| draft | boolean | ❌ | 是否为草稿 |
| cover | string | ❌ | 封面图片 |
| author | string | ❌ | 作者名称 |

## 自定义主题 Customizing Theme

编辑 `src/styles/global.css` 文件来自定义颜色和样式。

Edit the `src/styles/global.css` file to customize colors and styles.

Happy blogging! 祝写作愉快！
