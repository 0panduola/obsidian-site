---
title: Markdown 与双链
tags:
  - 指南
  - markdown
---

# Markdown 与双链

## 双向链接

用 `[[笔记名]]` 链接其他笔记，Quartz 会生成反向链接和图谱关系：

- [[getting-started]]
- [[workflow]]

也可以带显示文字：`[[getting-started|开始阅读]]`。

## Callout

> [!note]
> 这是一条普通提示。

> [!warning] 注意
> Callout 支持折叠、图标和自定义标题。

## 代码

```python
def greet(name: str) -> str:
    return f"Hello, {name}!"
```

## 表格

| 功能 | 状态 |
| --- | --- |
| 双链 | 已开启 |
| 搜索 | 已开启 |
| 图谱 | 已开启 |

## 数学公式

行内公式 $E = mc^2$，块级公式：

$$
\int_{-\infty}^{\infty} e^{-x^2} \, dx = \sqrt{\pi}
$$
