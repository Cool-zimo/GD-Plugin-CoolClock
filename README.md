# GD-Plugin-CoolClock

GitHub Drive 第三方插件示例 - 炫酷时钟

## 这是什么？

这是一个 [GitHub Drive](https://cool-zimo.github.io/github_drive) 的第三方插件，演示了众筹式插件生态。

任何开发者都可以创建名为 `GD-Plugin-xxx` 的仓库，在 GitHub Drive 的「插件广场 → 发现插件」中被搜索到。

## 如何开发自己的插件

1. 创建名为 `GD-Plugin-{你的插件名}` 的公开仓库
2. 在根目录创建 `plugin.json`：
```json
{
  "id": "your-plugin-id",
  "name": "插件名称",
  "description": "插件描述",
  "author": "你的名字",
  "version": "1.0.0",
  "icon": "🧩",
  "type": "plugin",
  "file": "index.html"
}
```
3. 创建插件 HTML 文件（如 `index.html`）
4. 推送后，在 GitHub Drive 插件广场的「发现插件」Tab 中即可搜到

## 插件 API

通过 postMessage 与 GitHub Drive 交互，详见[官方文档](https://cool-zimo.github.io/github_drive_documentation/docs/plugin-development.html)。
