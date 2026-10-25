# Liam 的工具板

我用 AI 做的小工具總入口：https://mmllpp772.github.io/

## 加新工具
打開 `index.html`，在 `TOOLS` 清單加一筆：

```js
{ name: "工具名稱", repo: "repo-名稱", shelf: "分類", icon: "tool",
  desc: "一句話說明。", tags: ["關鍵字"], added: "2026-10-25" },
```

`shelf` 可以用現有分類或新寫一個；`icon` 可用 scissors、cat、globe、city、factory、tool。
