# Wander 🌍

一个轻量的 Google 街景探索工具。一个 HTML 文件，打开就用。

## 功能

- **自由探索** — 搜索地名或输入经纬度，跳到世界任何角落看街景
- **随机漫游** — 随机一个坐标，带你去没去过的地方
- **搜索地点** — 支持地名搜索和经纬度坐标（如 `40.4168, -3.7038`）
- **历史足迹** — 保存去过的地方，下次打开还在（localStorage）
- **GeoGuessr 模式** — 看街景猜位置的小游戏
- **键盘操作** — 方向键导航，Escape 返回

## 使用

1. 申请 [Google Maps API Key](https://developers.google.com/maps/documentation/javascript/get-api-key)（需要启用 Maps JavaScript API + Street View API）
2. 打开 `index.html`，把 API Key 填到第一行的 `GOOGLE_API_KEY` 变量里
3. 双击打开或部署到任意静态服务器

没有 API Key 也能用——地图和搜索功能正常，只是看不了街景（会显示 fallback 提示）。

## 技术栈

- 纯 HTML/CSS/JS，零依赖，单文件
- [Leaflet](https://leafletjs.com/) — 地图底图
- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript/) — 街景
- [Nominatim](https://nominatim.openstreetmap.org/) — 地名搜索（免费，不需要 key）

## 截图

（待补充）

## License

MIT
