# Blog Content

此仓库存放博客内容，作为 [blog-theme](https://github.com/yourusername/blog-theme) 的 git submodule 使用。

## 📁 目录结构

```
content/
├── blog/              # 博文 Markdown 文件
│   ├── hello-world.md
│   └── ...
├── friends.json       # 友链数据
└── about.md          # 关于页面内容
```

## 📝 博文格式

```markdown
---
title: "文章标题"
description: "文章描述"
pubDate: 2024-01-15
tags: ["标签1", "标签2"]
author: "作者名"
draft: false          # true 表示草稿，不会发布
cover: "/images/cover.jpg"  # 可选，封面图
---

文章正文内容...
```

## 🔗 友链格式

编辑 `friends.json`：

```json
[
  {
    "id": "unique-id",
    "name": "友站名称",
    "url": "https://friend.site",
    "avatar": "https://avatar.url",
    "description": "友站描述"
  }
]
```

## 📄 许可

内容版权归作者所有，采用 CC BY-NC-SA 4.0 许可协议。
