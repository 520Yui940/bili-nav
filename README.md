# 💥 昔涟导航 · FadingNav ✨

> 「一个 HTML 文件，干掉所有框架。」  
> 190 次 commit · 6 个月淬炼 · 从 Prompt 到 Pixel，构筑粉色极简宇宙。  
> 由 **DeepSeek 架构** × **GLM-4.6 优化** × **@520Yui940 手工调教** 完成。

---

![HTML5](https://img.shields.io/badge/HTML5-100%25-orange?style=flat-square)
![Zero_Dependencies](https://img.shields.io/badge/Zero_Dependencies-Yes-success?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-Ready-blue?style=flat-square)
![Performance](https://img.shields.io/badge/Performance-A%2B-brightgreen?style=flat-square)
![Design](https://img.shields.io/badge/Design-Pink_Aesthetic-ffb3ca?style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-Deployed-orange?style=flat-square)

**在线体验**：[GitHub Pages 🚀](https://520yui940.github.io/bili-nav)  
**国内镜像**：[Cloudflare ⚡](https://bili-nav.pages.dev)  
**Star 项目**：[🌸 bili-nav on GitHub](https://github.com/520Yui940/bili-nav)

---

## 🧠 架构一览

- 📁 **bili-nav/**
  - `index.html` — 主文件（集成交互逻辑、样式与功能）
  - `sw.js` — Service Worker 离线缓存
  - `manifest.json` — PWA Manifest 配置
  - `assets/` — 图标与静态资源
  - `cloudflare-worker/` — 边缘部署脚本（API 代理 + 缓存层）

---

## 🧩 技术核心 · 一张 HTML 的全栈解构

| 模块 | 技术方案 | 描述 |
|------|-----------|------|
| 🔍 搜索引擎 | 原生 JS + 模糊匹配 | 支持分类检索与即时高亮 |
| 💾 收藏系统 | LocalStorage + 数据去重 | 持久保存用户偏好 |
| 🌗 主题切换 | CSS 变量 + prefers-color-scheme | 自适应明暗模式 |
| 📦 PWA 支持 | Service Worker 全缓存 | 离线访问、原生图标 |
| ☁️ Workers 加速 | Cloudflare Edge Runtime | 全局 API 加速与反代 |
| ⚙️ 动态接口 | 自研 API 调度层 | 接入自定义后端与代理请求 |

---

## ⚡ 性能指标

| 项目 | 数值 |
|------|------|
| 文件体积 | 70.93 KB（未压缩） |
| 首屏渲染 | <180 ms |
| 请求数 | 1 |
| Lighthouse 综合评分 | 💚 Performance 99 / PWA 100 / Accessibility 100 |

> 没有构建工具，没有框架，却能压榨每一毫秒。

---

## 🚀 一键启动

```bash
# 下载 index.html → 双击打开 → 即可使用
# 或部署到任意静态托管（GitHub Pages / Vercel / Cloudflare）
