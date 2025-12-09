# PaperFlow
🌊 PaperFlow | 沉浸式双语文献阅读流生成器。基于 MinerU 解析布局 + Ai 智能修复断句。一键将 PDF 转换为优雅的双语对照 HTML，完美保留公式与图表。
Tags: pdf-translator deepseek immersive-reading academic-tools python
<div align="center">
  <h1>🌊 PaperFlow</h1>
  <h3>沉浸式双语文献阅读流生成器</h3>
  <p>
    PaperFlow 旨在解决科研人员阅读 PDF 文献时的排版破碎与翻译生硬问题。<br>
    它不是一个简单的翻译器，它重塑了你的阅读体验。
  </p>

  <a href="https://github.com/你的用户名/PaperFlow/releases">
    <img src="https://img.shields.io/github/v/release/你的用户名/PaperFlow?color=blue&style=flat-square" alt="Release">
  </a>
  <img src="https://img.shields.io/badge/Platform-Windows-blue?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/License-Freeware-green?style=flat-square" alt="License">
</div>

---

## 🧐 为什么开发 PaperFlow？

作为物理系学生，我受够了传统 PDF 翻译工具的痛点：
* ❌ **断句灾难：** PDF 的硬回车导致翻译结果支离破碎。
* ❌ **公式乱码：** $E=mc^2$ 变成乱码，图表位置错乱。
* ❌ **视线跳跃：** 在翻译软件和原文之间反复横跳，打断心流。

**PaperFlow 的解决方案：**
利用 **MinerU** 强大的布局解析能力，结合 **DeepSeek** 的上下文理解能力，将 PDF 重构为**“优雅的 HTML 双语流”**。

![软件运行截图](./assets/screenshot_main.png)
*(建议在此处放一张：软件界面 + 生成后的 HTML 网页效果对比图)*

## ✨ 核心特性

* **🧠 智能断句修复：** 哪怕 PDF 排版再烂，内置算法也能自动识别段落逻辑，让 DeepSeek 读懂完整的句子。
* **📐 完美布局还原：** 基于视觉的解析引擎，保留所有 LaTeX 公式、图表、代码块，不错位、不乱码。
* **📖 沉浸式双语：** 英文在上，中文在下（灰度显示），单栏流式布局，像读博客一样读论文。
* **📦 单文件封装：** 生成的 `.html` 文件内置了 CSS 和图片（Base64），无需联网，发给手机/平板也能直接看。
* **🔒 数据隐私：** **BYOK 模式** (Bring Your Own Key)。软件运行在本地，直接与 DeepSeek API 通信，不经过任何第三方服务器。

## 🚀 快速开始

### 1. 下载软件
请前往右侧的 [Releases 页面](https://github.com/你的用户名/PaperFlow/releases) 下载最新的 `PaperFlow.exe`。
*(注意：目前仅支持 Windows 10/11 系统)*

### 2. 获取 API Key
本软件依赖 DeepSeek 的模型能力，你需要自备 API Key（价格极低，翻译一篇顶刊通常不到 0.5 元）。
* 前往 [DeepSeek 开放平台](https://platform.deepseek.com/) 申请 Key。

### 3. 运行转换
1.  双击运行 `PaperFlow.exe`。
2.  粘贴你的 API Key。
3.  拖入 PDF 文件，点击“开始转换”。
4.  等待进度条跑完，同目录下会生成一份 `_bilingual.html` 文件。

> **⚠️ 关于杀毒软件误报：**
> 由于本软件由 Python 打包且未购买昂贵的数字签名，Windows Defender 或 360 可能会误报病毒。
> **这是正常现象**。请选择“信任此文件”或暂时关闭杀毒软件。如果您担心安全性，可以先在沙箱环境中运行。

## 🛠️ 关于源代码与开源

**当前状态：🔒 Closed Source Alpha (闭源公测)**

PaperFlow 目前处于早期 MVP 验证阶段，且使用了 Nuitka 编译以保护核心断句算法。
* **为什么不开源？** 项目包含部分尚未整理的实验性逻辑，待代码重构并剥离敏感配置后，未来会考虑逐步开源核心模块。
* **是免费的吗？** 是的，软件本身完全免费（Freeware），你只需要支付 DeepSeek 的 API 费用。

## 💬 反馈与交流

这是一个由个人开发者（物理系本科生）维护的项目，难免有 Bug。
* **Bug 反馈：** 请直接在 [Issues](https://github.com/你的用户名/PaperFlow/issues) 区提交。
* **功能建议：** 欢迎提出你想要的排版样式或功能！

---

<p align="center">
  Made with ❤️ by Lyu Zeren & Antigravity
</p>
