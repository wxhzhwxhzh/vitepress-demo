# Markdown 扩展示例

本页面展示了 VitePress 提供的部分内置 Markdown 扩展功能。

## 语法高亮

VitePress 的语法高亮功能由 [Shiki](https://github.com/shikijs/shiki) 提供，还支持行高亮等附加功能：

**输入**

````md
```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
````

**输出**

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

## 自定义容器

**输入**

```md
::: info
这是一个信息框。
:::

::: tip
这是一个提示框。
:::

::: warning
这是一个警告框。
:::

::: danger
这是一个危险警告框。
:::

::: details
这是一个详情块。
:::
```

**输出**

::: info
这是一个信息框。
:::

::: tip
这是一个提示框。
:::

::: warning
这是一个警告框。
:::

::: danger
这是一个危险警告框。
:::

::: details
这是一个详情块。
:::

## 更多内容

查看文档以获取 [完整的 Markdown 扩展列表](https://vitepress.dev/guide/markdown)。