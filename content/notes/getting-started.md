---
title: 快速开始
tags:
  - 指南
---

# 快速开始

## 目录结构

```
obsidian-site/
├── content/          # Obsidian vault，笔记都放这里
│   ├── index.md
│   └── notes/
├── quartz.config.yaml # 站点配置
└── .github/workflows/ # 自动部署
```

## 本地预览

```shell
npm install
npx quartz build --serve
```

打开 <http://localhost:8080> 查看效果。

## 发布

修改笔记后提交并推送：

```shell
git add .
git commit -m "更新笔记"
git push
```

GitHub Actions 会自动构建并部署到 Pages。

返回 [[index|首页]]。
