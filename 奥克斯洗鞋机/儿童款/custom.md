---
title: 自定义语法
head:
  - - meta
    - name: description
      content: 自定义 Markdown 语法
  - - meta
    - name: keywords
      content: markdown custom
---

# {{ $frontmatter.title }}

## 信息框

```md
::: tip 使用 TIPS 代替
提示信息
:::

::: info
信息消息
:::

::: warning
警告消息
:::

::: danger
危险消息
:::

::: details Details
详细信息
:::
```

效果如下：

::: tip 使用 TIPS 代替
提示内容
:::

::: info
INFO 消息
:::

::: warning
WARNING 消息 <a>a 链接</a>
:::

::: danger
123
:::

::: details Details
详细信息
:::
