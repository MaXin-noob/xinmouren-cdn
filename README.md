# xinmouren-cdn

个人静态资源仓库 · 通过 jsDelivr CDN 提供免费直链托管。

## 使用方式

上传文件后，按下面格式拼直链：

```
https://cdn.jsdelivr.net/gh/MaXin-noob/xinmouren-cdn@main/<路径>
```

## 目录约定

**核心规则：每一类用途的图片单独新建一个目录存放，不同用途不要混在一起。**

- 每新增一种用途，就新建一个目录，而不是往已有目录里塞。
- 目录名用「用途」命名，全小写，例如 `icons/`、`blog/`、`game/`。
- 同一用途下资源较多时，可再按具体对象建子目录，例如 `icons/github-mcp/`。

| 目录 | 用途 |
|---|---|
| `ts/` | TeamSpeak 服务器横幅、图标 |
| `blog/` | 博客配图、封面 |
| `icons/<名称>/` | 各类图标，按用途再分子目录（如 `icons/github-mcp/`） |
| `misc/` | 实在无明确归属时的兜底目录 |

## 命名规范

- 全小写 + 连字符或下划线，例如 `ts/banner-5x1.jpg`
- **不要用中文、空格**，否则 URL 变成一串 `%E5%A4%A7` 很难看
- 换图后想强制刷新 CDN 缓存：https://www.jsdelivr.com/tools/purge

## 当前资源

| 路径 | 说明 |
|---|---|
| `ts/banner.jpg` | 大伙的秘密基地 · 完整横幅 1536×1024（204KB，推荐） |
| `ts/banner-5x1.jpg` | 同上 · 5:1 裁切版 1536×307（141KB，适配 TS 横幅位） |
| `ts/banner.png` | 同上 · 原图留档 1536×1024（1.9MB） |
| `icons/github-mcp/icon.png` | GitHub MCP 技能图标 · 1024×1024 |

TS 直链示例：

```
https://cdn.jsdelivr.net/gh/MaXin-noob/xinmouren-cdn@main/ts/banner.jpg
```
