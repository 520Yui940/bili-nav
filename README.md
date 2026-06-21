# 💥 昔涟导航 · FadingNav ✨

> 「一个 HTML 文件，干掉所有框架。」  
> 190 次 commit · 6 个月淬炼 · 从 Prompt 到 Pixel，构筑粉色极简宇宙。  
> 由 **DeepSeek 架构** × **GLM-4.6 优化** × **@520Yui940 手工调教** 完成。

---

![HTML5](https://img.shields.io/badge/HTML5-100%25-orange?style=flat-square)
![Zero_Build_Tools](https://img.shields.io/badge/Zero_Build_Tools-Yes-success?style=flat-square)
![No_NPM](https://img.shields.io/badge/No_NPM-CDN_Only-blueviolet?style=flat-square)
![Design](https://img.shields.io/badge/Design-Pink_Aesthetic-ffb3ca?style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Pages-Deployed-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Forever_WIP-yellow?style=flat-square)

**在线体验**：[GitHub Pages 🚀](https://520yui940.github.io/bili-nav)  
**国内镜像**：[Cloudflare ⚡](https://bili-nav.pages.dev)  
**Star 项目**：[🌸 bili-nav on GitHub](https://github.com/520Yui940/bili-nav)

---

## 🧠 架构一览

- 📁 **bili-nav/**
  - `index.html` — 主文件（集成交互逻辑、样式与功能）
  - `sw.js` — Service Worker 离线缓存（规划中，尚未接入主页面）
  - `manifest.json` — PWA Manifest 配置（规划中）
  - `assets/` — 图标与静态资源
  - `cloudflare-worker/` — 边缘部署脚本（点击统计 API + 降级缓存层）

---

## 🧩 技术核心 · 一张 HTML 的全栈解构

| 模块 | 技术方案 | 描述 |
|------|-----------|------|
| 🔍 搜索引擎 | 原生 JS + 字符串匹配 | 支持名称/描述检索，输入即时过滤 |
| 💾 收藏系统 | LocalStorage | 持久保存用户收藏，按 URL 去重 |
| 🌗 主题切换 | CSS 变量 + class 切换 | 明暗模式手动切换，状态本地记忆 |
| 📦 PWA 支持 | manifest.json（待接入） | 离线缓存功能规划中，敬请期待 |
| ☁️ Workers 加速 | Cloudflare Worker | 全局点击统计，自带防刷与本地降级 |
| ⚙️ 动态接口 | fetch + 本地降级 | Worker 请求失败时自动切换 localStorage 统计 |

---

## ⚡ 性能现状

| 项目 | 数值 | 备注 |
|------|------|------|
| 文件体积 | 70.93 KB（未压缩） | 单文件，无构建产物 |
| 渲染阻塞 | ~2.8s | 待优化：CDN 脚本加 defer |
| 缓存优化空间 | ~813 KiB | 待优化：背景图迁移自建仓库 |
| 依赖数量 | 2 个外部 CDN | Font Awesome + QRCode.js |

> 没有构建工具，没有框架，连带没有过度优化——能跑，在持续缝缝补补。

---

## 🚀 一键启动

```bash
# 下载 index.html → 双击打开 → 即可使用
# 或部署到任意静态托管（GitHub Pages / Vercel / Cloudflare）
```

---

## 🐛 已知问题 / TODO

- [ ] 背景图体积过大，待迁移到自建仓库并压缩
- [ ] CDN 脚本未做异步加载，影响首屏渲染速度
- [ ] PWA 离线能力尚未真正接入（manifest 和 sw.js 还在"摸鱼"阶段）
- [ ] 部分网站 favicon 直连不稳定，考虑换聚合接口
- [ ] 公告弹窗内容偶尔会忘记更新（看到一堆 Ciallo 不要慌，那是上次没写完）

---

## 💌 关于这个项目

一个人用 AI agent 写出来的玩具导航站，没什么用户，主要是写给自己玩、自己用。  
如果你也在路上看到了这个仓库——欢迎随便看看，别太当真，这里所有的"性能 A+"都是愿望，不是事实，但愿望也很重要。

