# Polymaker Wiki Demo

本仓库为 **GitBook 专用内容**，用于在 [GitBook](https://www.gitbook.com/) 上搭建与 [wiki.polymaker.com - Profile/Preset Request](https://wiki.polymaker.com/polymaker-products/printer-profiles/profile-preset-request) 效果一致的站点，并内嵌 [Polymaker-Preset](https://polymaker3d.github.io/Polymaker-Preset/?theme=wiki) 打印预设下载页。

- **无本地构建**：不依赖 HonKit 或其它静态站生成器，内容由 GitBook 云产品直接渲染。
- **建站方式**：在 [gitbook.com](https://www.gitbook.com/) 创建 Space，通过 **Git Sync** 连接本仓库，或按 [建站方案.md](建站方案.md) 手动创建页面并添加 Embed a URL 块。

## 目录结构（GitBook 侧栏）

- **首页**：本页（README.md）
- **Polymaker Products → Printer Profiles → Profile/Preset Request**：与 wiki 对应页面，内含「Embed a URL」块，URL 为 `https://polymaker3d.github.io/Polymaker-Preset/?theme=wiki`

## 快速开始

1. 打开 [GitBook](https://www.gitbook.com/) 并登录。
2. 新建 Space，在 Space 设置中启用 **GitHub / GitLab Sync**，连接本仓库。
3. 发布后即可得到与 wiki 类似的站点，Profile/Preset Request 页面内嵌 Polymaker-Preset 下载页。

详见 [建站方案.md](建站方案.md)。
