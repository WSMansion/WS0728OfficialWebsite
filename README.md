# 茜楠公馆 · ws0728.top

茜楠公馆工作室官网，记录我们共同创造的每一步。

## 项目结构

```
├── index.html          # 主页面
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── main.js         # 交互逻辑
├── assets/
│   └── images/         # 图片资源（需要自行添加）
└── README.md
```

## 如何使用

1. 直接用浏览器打开 `index.html` 即可预览
2. 部署到任意静态网站托管平台（如 Vercel、Netlify、GitHub Pages、Cloudflare Pages）

## 自定义内容

### 替换画廊图片

将甘丸的画作放入 `assets/images/` 文件夹，然后在 `index.html` 中将画廊区域的 `<div class="gallery-placeholder">` 替换为 `<img>` 标签。

### 修改时间线

在 `index.html` 的时间线区域（`#timeline`）添加或修改里程碑事件。

### 修改项目信息

在 `index.html` 的项目区域（`#projects`）更新围棋教练和吱星的介绍文字和链接。

## 技术栈

- 纯 HTML / CSS / JavaScript，无框架依赖
- Google Fonts（Noto Serif SC + Noto Sans SC）
- CSS Grid + Flexbox 响应式布局
- IntersectionObserver 滚动动画
- 全站响应式，适配桌面端和移动端
