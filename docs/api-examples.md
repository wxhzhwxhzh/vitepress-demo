---
outline: deep
---

# 运行时 API 示例

本页面演示了 VitePress 提供的部分运行时 API 的使用方法。

核心的 `useData()` API 可用于访问当前页面的站点数据、主题数据和页面数据。它在 `.md` 和 `.vue` 文件中均能正常工作：

```md
<script setup>
import { useData } from 'vitepress'

const { theme, page, frontmatter } = useData()
</script>

## 结果

### 主题数据
<pre>{{ theme }}</pre>

### 页面数据
<pre>{{ page }}</pre>

### 页面前端元数据
<pre>{{ frontmatter }}</pre>
```

<script setup>
import { useData } from 'vitepress'

const { site, theme, page, frontmatter } = useData()
</script>

## 结果

### 主题数据
<pre>{{ theme }}</pre>

### 页面数据
<pre>{{ page }}</pre>

### 页面前端元数据
<pre>{{ frontmatter }}</pre>

## 更多内容

查看文档以获取 [完整的运行时 API 列表](https://vitepress.dev/reference/runtime-api#usedata)。 