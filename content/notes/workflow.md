---
title: 写作工作流
tags:
  - 指南
---

# 写作工作流

1. 用 Obsidian 打开 `C:\obsidian-site\content` 作为 vault
2. 新建笔记，使用 `[[双链]]` 关联已有内容
3. 本地 `npx quartz build --serve` 预览
4. 确认无误后 `git push`
5. GitHub Actions 自动部署

> [!tip] 图片
> 把图片放在 `content/` 内，用相对路径或 `![[图片名.png]]` 引用，构建时会一起发布。

相关：[[markdown-guide]]、[[getting-started]]。
