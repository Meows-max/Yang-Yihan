# 杨依涵的知识博客

这是一个基于 Jekyll 的个人知识库 / 博客，托管于 GitHub Pages。

## 本地结构

```
.
├── _config.yml          # 站点配置（标题、作者、主题）
├── Gemfile              # Ruby 依赖声明（GitHub Pages 用）
├── index.md             # 首页
├── about.md             # 关于页
└── _posts/              # 文章目录
    └── 2026-10-18-welcome.md
```

## 写新文章的规则

- 文件放在 `_posts/` 下
- 文件名格式：`YYYY-MM-DD-英文短标题.md`
- 开头必须有 front matter：

```yaml
---
layout: post
title: "文章标题"
date: 2026-10-20 10:00:00 +0800
categories: 学习
---
```

## 访问地址

启用 GitHub Pages 后：<https://meows-max.github.io/Yangyihan/>
