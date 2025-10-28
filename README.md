<h1 align="center">💥 昔涟导航 · FadingNav ✨</h1>

<p align="center">
  <em>「一个 HTML 文件，干掉所有框架。」</em><br>
  190 次 commit · 6 个月淬炼 · 从 Prompt 到 Pixel，构筑粉色极简宇宙。<br>
  由 <b>DeepSeek 架构</b> × <b>GLM-4.6 优化</b> × <b>@520Yui940 手工调教</b> 完成。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-100%25-orange?style=flat-square">
  <img src="https://img.shields.io/badge/Zero_Dependencies-Yes-success?style=flat-square">
  <img src="https://img.shields.io/badge/PWA-Ready-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Performance-A%2B-brightgreen?style=flat-square">
  <img src="https://img.shields.io/badge/Design-Pink_Aesthetic-ffb3ca?style=flat-square">
  <img src="https://img.shields.io/badge/Cloudflare_Workers-Deployed-orange?style=flat-square">
</p>

<p align="center">
  <a href="https://520yui940.github.io/bili-nav">🚀 在线体验</a> · 
  <a href="https://bili-nav.pages.dev">⚡ 国内镜像</a> · 
  <a href="https://github.com/520Yui940/bili-nav">🌸 Star 项目</a>
</p>

---

## 🧠 架构一览

📁 bili-nav ├─ index.html         # 主文件（集成交互逻辑、样式与功能） ├─ sw.js              # Service Worker 离线缓存 ├─ manifest.json      # PWA Manifest 配置 ├─ /assets            # 图标与静态资源 └─ cloudflare-worker  # 边缘部署脚本（API代理 + 缓存层）

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
| 文件体积 | 37.2 KB（未压缩） |
| 首屏渲染 | <180 ms |
| 请求数 | 1 |
| Lighthouse 综合评分 | 💚 Performance 99 / PWA 100 / Accessibility 100 |

> 没有构建工具，没有框架，却能压榨每一毫秒。

---

## 🚀 一键启动

```bash
# 下载 index.html → 双击打开 → 即可使用
# 或部署到任意静态托管（GitHub Pages / Vercel / Cloudflare）

☁️ Cloudflare Workers 版本部署示例

# wrangler.toml
name = "bili-nav"
main = "index.js"
compatibility_date = "2025-04-22"

# 命令
wrangler publish


---

💬 作者寄语

> “写这个项目时，我想证明一件事：
HTML + JS + CSS 本身就足够强大，不需要框架的赘肉。”
—— @520Yui940



每一行代码都为性能让路；
每一次渲染都在服务粉色的浪漫。
这是一次对「极简主义 × 高性能」的极限实验。


---

🌸 Highlights

🧱 零依赖纯前端架构

⚡ 超轻量原生性能

💗 毛玻璃 + 粉色美学设计

📦 全平台 PWA 支持

☁️ Cloudflare Workers 全球加速

🛠️ 完整前端存储与缓存机制



---

🪞 开发史记

2025.04.22：DeepSeek 三秒生成 MVP

同日 20+ 次 commit：暴力重构 + 调色修排版

6 个月 190 次迭代：添加暗黑 / 收藏 / 离线 / Workers

2025.10 至今：持续优化代码架构与渲染性能



---

🧩 延伸作品与经历

🎨 昔涟 UI System — 个人设计语言体系，聚焦粉色美学

☁️ Cloudflare Edge Deploy — 边缘计算与代理实现

🧠 DeepSeek × GLM 双 AI 协同开发流 — Prompt 驱动型项目生成与精修

💫 纯前端架构探索 — 验证零依赖的可维护性与扩展性



---

💗 最后

> 昔涟导航，不只是导航。
它是一次「技术 × 美学 × 自由」的融合实验。



<p align="center">
  <a href="https://github.com/520Yui940/bili-nav"><b>⭐ Star 一下，让粉色的信仰继续蔓延 🌸</b></a>
</p>

