# xinmouren-cdn

个人静态资源仓库 · 通过 jsDelivr CDN 提供免费直链托管。

## 使用方式

上传文件后，按下面格式拼直链：

```
https://cdn.jsdelivr.net/gh/MaXin-noob/xinmouren-cdn@main/<路径>
```

## 目录约定

**核心规则：按用途分目录。一个用途一个顶层目录，不同用途的图片不混放；新增一种用途就新建一个目录。**

目录名直接用该用途的名称，例如：`TS`、`GitHub-MCP`、`blog`、`12306-mcp`。

| 目录 | 用途 |
|---|---|
| `ts/` | TeamSpeak 服务器横幅、图标 |
| `GitHub-MCP/` | GitHub MCP 相关图片 |
| `blog/` | 博客配图、封面 |

## 命名规范

- 目录名 = 用途名，直接写用途全称，例如 `GitHub-MCP`、`12306-mcp`
- 文件名建议全小写 + 连字符或下划线，例如 `ts/banner-5x1.jpg`
- **不要用中文、空格**，否则 URL 变成一串 `%E5%A4%A7` 很难看
- 换图后想强制刷新 CDN 缓存：https://www.jsdelivr.com/tools/purge

## 当前资源

| 路径 | 说明 |
|---|---|
| `ts/banner.jpg` | 大伙的秘密基地 · 完整横幅 1536×1024（204KB，推荐） |
| `ts/banner-5x1.jpg` | 同上 · 5:1 裁切版 1536×307（141KB，适配 TS 横幅位） |
| `ts/banner.png` | 同上 · 原图留档 1536×1024（1.9MB） |
| `GitHub-MCP/icon.png` | GitHub MCP 技能图标 · 1024×1024 |

TS 直链示例：

```
https://cdn.jsdelivr.net/gh/MaXin-noob/xinmouren-cdn@main/ts/banner.jpg
```
