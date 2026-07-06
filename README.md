# Prototypes

这个仓库用于存放产品 HTML 原型页面，方便后续接入 Vercel / GitHub Pages，并嵌入飞书文档。

## 目录约定

- `/index.html`：统一原型目录首页
- `/<prototype-name>/index.html`：单个原型的入口页面
- 每个原型保持独立目录，后续可以继续放置图片、数据文件、拆分页面或导出的高保真 HTML

## 当前原型

| 业务域 | 原型 | 状态 | 路径 |
| --- | --- | --- | --- |
| 监控告警 | 告警分析大屏 | 可演示 | `alert-dashboard/index.html` |
| Agent 管控 | Agent 管控台 | 设计中 | `agent-control/index.html` |

## 推荐使用方式

1. 将本仓库导入 Vercel
2. 使用 Vercel 自动部署
3. 将部署后的 URL 通过飞书文档的「嵌入网页 / Embed」组件插入文档

## 新增原型方式

1. 新建目录，例如 `new-prototype/index.html`
2. 在 `/index.html` 的原型列表里新增一张入口卡片
3. 在本 README 的「当前原型」表格中补充业务域、名称、状态和路径
