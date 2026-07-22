---
layout: default
title: Clash for Windows 最终版备份
description: Clash for Windows v0.20.39 官方最后一版备份下载与使用指南，含汉化补丁说明。
---

# Clash for Windows · 最终版存档

> 本仓库是对 **Clash for Windows 官方最后一个版本（v0.20.39）** 的独立备份，原项目已停止维护。  
> 所有文件均来自 `cb4da11` 提交构建，仅供学习与存档。

## 🔗 快速导航

- 📦 [查看所有平台下载](#-各平台下载)  
- 📖 [使用教程](#-使用教程)  
- 🌐 [简体中文汉化说明](#-汉化补丁)  
- 📚 详细文档请访问 [Wiki](https://github.com/Clashforwinodws/Clash-for-Winodows/wiki)  
- 🌍 在线浏览本页面：[独立站点](https://clashforwinodws.github.io/Clash-for-Winodows/)

---

## 📥 各平台下载

下方提供 v0.20.39 版本的安装包与便携包，点击对应名称即可下载。  
所有下载均跳转至本仓库的 [Releases 页面](https://github.com/Clashforwinodws/Clash-for-Winodows/releases/tag/v0.20.39)。

| 操作系统 | 安装包 / 便携包 |
|----------|----------------|
| **Windows** | [Clash.for.Windows.Setup.0.20.39.exe](https://github.com/Clashforwinodws/Clash-for-Winodows/releases/download/v0.20.39/Clash.for.Windows.Setup.0.20.39.exe) <br> [Clash.for.Windows.Setup.0.20.39.ia32.exe](https://github.com/Clashforwinodws/Clash-for-Winodows/releases/download/v0.20.39/Clash.for.Windows.Setup.0.20.39.ia32.exe) <br> [Clash.for.Windows.0.20.39-win.7z](https://github.com/Clashforwinodws/Clash-for-Winodows/releases/download/v0.20.39/Clash.for.Windows.0.20.39-win.7z) |
| **macOS** | [Clash.for.Windows.0.20.39.dmg](https://github.com/Clashforwinodws/Clash-for-Winodows/releases/download/v0.20.39/Clash.for.Windows.0.20.39.dmg) <br> [Clash.for.Windows.0.20.39-arm64.dmg](https://github.com/Clashforwinodws/Clash-for-Winodows/releases/download/v0.20.39/Clash.for.Windows.0.20.39-arm64.dmg) |
| **Linux** | [Clash.for.Windows.0.20.39-x64-linux.tar.gz](https://github.com/Clashforwinodws/Clash-for-Winodows/releases/download/v0.20.39/Clash.for.Windows.0.20.39-x64-linux.tar.gz) <br> [Clash.for.Windows.0.20.39-arm64-linux.tar.gz](https://github.com/Clashforwinodws/Clash-for-Winodows/releases/download/v0.20.39/Clash.for.Windows.0.20.39-arm64-linux.tar.gz) |

> ⚡ 需要节点订阅？可以自行搜索“clash 免费节点”，但请务必注意网络安全。

---

## 🧭 使用教程

### 基本步骤
1. 根据你的系统下载上方对应的安装包或压缩包。
2. 安装（或解压）后，首次启动 **Clash for Windows**。
3. 在 `Profiles` 界面输入你的订阅链接，点击下载。
4. 切换到 `Proxies` 页面，选择合适的节点。
5. 开启 `System Proxy` 或设置浏览器代理即可上网。

### 配置文件说明
- 默认配置目录为 `%USERPROFILE%\.config\clash`。
- 你可以直接编辑 `config.yaml` 或通过界面导入。
- 规则、策略组等高级用法请查阅 [Wiki 文档](https://github.com/Clashforwinodws/Clash-for-Winodows/wiki)。

---

## 🌏 汉化补丁

我们提供了一个第三方的界面汉化补丁 `app.asar`，可以让英文界面显示为中文。

### 使用方法
1. **完全退出 Clash for Windows**（系统托盘也要退出）。
2. 下载补丁文件：  
   - [📥 下载 app.asar （汉化补丁）](https://github.com/Clashforwinodws/Clash-for-Winodows/releases/download/v0.20.39/app.asar)  
   - 或使用本仓库根目录下的 `app.7z` 解压得到 `app.asar`。
3. 找到 Clash for Windows 的安装目录，进入 `resources` 文件夹。  
   - Windows 默认路径：`Clash.for.Windows-0.20.39-win/resources`
4. 将下载的 `app.asar` 替换掉该文件夹内的同名文件。
5. 重新启动程序，界面即变为中文。

> ⚠️ 注意：补丁仅适用于 v0.20.39 版本，如果后续有其他衍生版本，请勿混用。

---

## 📜 说明

- 本仓库及页面仅提供 **原版文件存档**，不包含任何修改或恶意代码。
- 原项目地址已不可访问，此处为社区维护的备份资源，与原始开发者无关。
- 若对使用有疑问，请优先查阅 [Wiki](https://github.com/Clashforwinodws/Clash-for-Winodows/wiki)。

---

*最后更新：2026年7月 · 基于原发布版 `cb4da11`*
