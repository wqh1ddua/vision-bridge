# Vision Bridge · 视觉桥

[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-Commercial-red.svg)](LICENSE)

**给 DeepSeek 装上眼睛，让 AI 能看、能画、能拍视频。**

DeepSeek 是纯文本模型，天生"瞎"。Vision Bridge 通过云端视觉 AI + 本地备用引擎，给它接上截图识别、图片生成、视频生成全套能力。

> Give DeepSeek eyes, hands, and creativity — see screens, generate images, create videos.

---

## 💰 获取授权

**本软件为商业软件，不开源。个人学习免费，商业使用需授权。**

| 方式 | 联系方式 |
|------|------|
| 📧 邮箱 | wqh1ddua@gmail.com |
| 🐙 GitHub | [提交 Issue](https://github.com/wqh1ddua/vision-bridge/issues) |

---

## 🚀 能干什么

### 1. 视觉识别 — 让 DeepSeek "看见"

DeepSeek + Claude Code 组合下，DeepSeek 看不到任何画面。Vision Bridge 截取屏幕 → AI 识别 → 中文描述 → DeepSeek 读懂画面。

- 🪟 **智能截图**：自动激活目标窗口（前台/后台/最小化/隐藏/未启动 全搞定）
- 📋 **剪贴板识别**：微信 Alt+A 截图 → 一键识别
- 🎯 **像素级定位**：AI 网格定位 → 精确到 10px → 自动点击
- 🖥️ **桌面操控**：鼠标点击、键盘输入、窗口激活、滚动翻页
- 🔄 **自主循环**：AI 看 → 想 → 点 → 再看 → 闭环执行任务

### 2. 图片生成 — AI 画图

说一句话就出图，中文直接说。支持文生图、图生图、多尺寸输出。

### 3. 视频生成 — AI 拍视频

文字/图片 → 视频，原生音画同步（BGM、环境音、人声全自动）。支持文生视频、图生视频、关键帧动画，2-5 分钟出片。

---

## 🧠 技术架构

```
DeepSeek（纯文本，没眼睛）
        ↑
        读中文描述 / 收生成结果
        ↑
┌──────────────────────────┐
│      Vision Bridge        │
│                          │
│  👁 视觉识别 云端引擎     │  ← 截图 → 文字描述
│  🎨 图片生成 云端引擎     │  ← 文字 → 图片
│  🎬 视频生成 云端引擎     │  ← 文字/图片 → 视频（音画同步）
│  🖱 桌面操控 本地引擎     │  ← 键鼠/窗口控制
└──────────────────────────┘
        ↑
   云端主力 + 本地备用
```

双引擎保障：云端主力（免费、极速）+ 本地备用（离线可用）

---

## ❓ 常见问题

**Q: 为什么不用 Claude/GPT 的视觉能力？**

A: 它们自带视觉。Vision Bridge 专为 DeepSeek 这种纯文本模型设计——让便宜的模型也能"看"。

**Q: 和 Codex Computer Use 有什么区别？**

A: Codex 是桌面操控插件。Vision Bridge 的核心是**视觉桥接 + AI 内容生成**，桌面操控只是顺手的事。

**Q: 收费吗？**

A: 个人学习免费。商业使用（公司、集成到产品、为客户提供服务）需购买授权。联系作者获取报价。

**Q: 依赖什么？**

A: Python 3.10+、Windows（桌面操控部分）。视觉识别跨平台可用。需要注册免费的云端 AI 账号（我会帮你配置好）。

---

## ☕ 联系作者 / 获取授权

- 📧 邮箱：wqh1ddua@gmail.com
- 🐙 GitHub：[提交 Issue](https://github.com/wqh1ddua/vision-bridge/issues)
