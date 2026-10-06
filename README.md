# xinmouren-cdn

个人静态资源仓库 · 通过 jsDelivr CDN 提供免费直链托管。

## 使用方式

上传文件后，按下面格式拼直链：

```
https://cdn.jsdelivr.net/gh/MaXin-noob/xinmouren-cdn@main/<路径>
```

## 目录约定

| 目录 | 用途 |
|---|---|
| `ts/` | TeamSpeak 服务器横幅、图标 |
| `blog/` | 博客配图、封面 |
| `misc/` | 其他零散资源 |

新增分类时照着上面的风格建目录即可，例如 `projects/`、`game/`。

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

TS 直链示例：

```
https://cdn.jsdelivr.net/gh/MaXin-noob/xinmouren-cdn@main/ts/banner.jpg
```
