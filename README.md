### 启动
pnpm run docs:dev
pnpm vitepress dev docs

### 链接到非 VitePress 页面
```markdown
[Link to pure.html](/pure.html){target="_self"}
```

> 在 Markdown 链接中，base 会自动添加到 URL 前面。这意味着，如果想链接到 base 之外的页面，则链接中需要类似 ../../pure.html 的内容（由浏览器相对于当前页面解析）。或者，可以直接使用锚标记语法：
> ```html
> <a href="/pure.html" target="_self">Link to pure.html</a>
> ```



