# Blog Content

此仓库存放博客内容，作为 [blog-theme](https://github.com/yourusername/blog-theme) 的 git submodule 使用。

## 📁 目录结构

```
content/
├── blog/              # 博文 Markdown 文件
│   ├── hello-world.md
│   └── ...
├── friends.toml       # 友链数据
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

编辑 `friends.toml`：

```toml
[example-blog] # id, can't be the same as others
name = "Example Blog" # display name
url = "https://example.com" # link url
# avatar should be an image url, svg/png/jpg/jpeg are all supported
avatar = "https://api.dicebear.com/7.x/avataaars/svg?seed=example"
description = "这是一个示例友链 - An example friend link" # display description
```

## 📄 许可

内容版权归作者所有，采用 CC BY-NC-SA 4.0 许可协议。
