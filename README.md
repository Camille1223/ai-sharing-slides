# AI in Your Hands — Finance Team Sharing Session
# AI 就在你手中 — Finance 团队内部分享

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-indigo?style=flat-square&logo=github)](https://camille1223.github.io/ai-sharing-slides/)
[![Slides](https://img.shields.io/badge/Slides-21%20页-7858FF?style=flat-square)](https://camille1223.github.io/ai-sharing-slides/)

> 一场关于 Claude、Claude Code、MCP 与 Skill 的内部分享演讲稿（HTML 格式，21 张 slides）。
>
> An internal sharing session on Claude, Claude Code, MCP and Skills — delivered as a self-contained HTML presentation (21 slides).

**Live Demo → [camille1223.github.io/ai-sharing-slides](https://camille1223.github.io/ai-sharing-slides/)**

---

## 演讲大纲 · Talk Outline

### 01 · 核心概念 Core Concepts

**中文**
- 什么是 Claude？——打工仔比喻：AI 大脑，随叫随到
- 什么是 MCP？——手的比喻：让 Claude 伸手触及真实系统（SAP、GitHub、Outlook）
- 什么是 Skill？——工具的比喻：手里拿的工具不同，效果就不同
- 什么是 Claude Code？——协调一切的 Agent：大脑 + 手 + 工具
- 什么是 Token？——AI 的货币，每个字都要花钱
- 什么是 Agent？——不只回答，还会主动行动的 AI

**English**
- What is Claude? — The "worker on demand" analogy: brilliant AI brain, always available
- What is MCP? — The "hands" analogy: lets the worker reach into real systems (SAP, GitHub, Outlook)
- What is Skill? — The "tools" analogy: different tools in those hands produce different results
- What is Claude Code? — The agent that orchestrates brain + hands + tools
- What is Token? — The "currency" of AI; every word sent or received has a cost
- What is Agent? — An AI that doesn't just answer, it *acts*

---

### 02 · Claude 模型对比 Claude Models

**中文**
- **Haiku** — 最快最轻量，适合简单重复任务
- **Sonnet** — 均衡之选，日常编码和文档处理
- **Opus ★ 推荐** — 最强最准确，复杂推理、长任务首选；Finance 工作用这个

**English**
- **Haiku** — Fastest, lightest; great for simple repetitive tasks
- **Sonnet** — Balanced everyday model; good for most coding and document work
- **Opus ★ Recommended** — Most powerful and accurate; best for complex reasoning, long tasks; use this for Finance work

---

### 03 · VS Code vs Terminal

**中文**
- VS Code：图形界面，文件树可见，适合新手
- Terminal ★ 个人偏好：原始、纯粹、无干扰；输入 `/` 唤起所有指令，像素游戏的感觉

**English**
- VS Code: GUI-friendly, file explorer visible; easier for beginners
- Terminal ★ Personal pick: raw, distraction-free; type `/` to invoke any skill instantly; feels like a pixel RPG

---

### 04 · 安装与上手 Getting Started

**中文**
- 观看安装演示视频（SAP SharePoint）
- 遇到问题联系 **Kristian Schier**，或在 Teams 群里提问

**English**
- Watch the installation walkthrough video on SAP SharePoint
- Reach out to **Kristian Schier** or post in the Teams group chat for help

---

### 05 · Skills 实战 Skills in Practice

**中文**
- **/brainstorming ★** — 我最常用的 Skill，开始任何项目前先用它让 Claude 采访你、梳理需求
- **/grillme** — 让 Claude 从各个角度挑战你的想法，压力测试
- **/frontend-design** — 生成精美 UI，一个斜杠命令让界面天壤之别（附 before/after 对比图）

**English**
- **/brainstorming ★** — My #1 daily driver; Claude interviews you to clarify scope before writing a single line of code
- **/grillme** — Claude challenges your idea from every angle; great for stress-testing plans
- **/frontend-design** — Generates polished UI; see the before/after comparison in the deck

---

### 06 · SAP 内部 MCP SAP Internal MCP

**中文**
- 连接 Claude Code 与 SAP 内部平台
- 安装仓库：[github.tools.sap/GC-CA-AI-Incubation/super-gc-saper](https://github.tools.sap/GC-CA-AI-Incubation/super-gc-saper)
- 装上之后 Claude 可以直接在终端里操作 SAP 内部系统

**English**
- Bridges Claude Code with SAP's internal tools and platforms
- Install from: [github.tools.sap/GC-CA-AI-Incubation/super-gc-saper](https://github.tools.sap/GC-CA-AI-Incubation/super-gc-saper)
- Once installed, Claude can interact with SAP-internal systems directly from your terminal

---

### 07 · GitHub 社区 GitHub Community

**中文**
- 自建项目：用 Claude Code 做工具，推到 GitHub，分享链接就能用
- Fork 改造：克隆别人的项目，改成自己的
- 发现与学习：浏览开源 AI 工具，免费、开放、随用随取

**English**
- Build your own: use Claude Code, push to GitHub, share a link — no IT deployment needed
- Fork & customize: clone a community project and make it yours in minutes
- Discover & learn: browse thousands of open-source AI tools, all free

---

### 08 · 我的项目 My Projects

#### 付款通知生成器 Payment Notice Generator

**中文**
- 起因：发票组每次手工做付款通知，模板固定但重复劳动多
- 方案：网页工具，拖入 `.docx` 模板 + Excel 数据，一键批量生成 Word + PDF 压缩包
- 部署：GitHub Pages（前端免费） + Render（后端 PDF 转换免费）
- 链接：[camille1223.github.io/Payment-Notice-Tool](https://camille1223.github.io/Payment-Notice-Tool/)

**English**
- Pain point: invoice team manually producing payment notices — fixed template, repetitive work
- Solution: web tool — drag in `.docx` template + Excel data → one click → ZIP with all Word + PDF files
- Deployed on GitHub Pages (free frontend) + Render (free backend for PDF conversion)
- Link: [camille1223.github.io/Payment-Notice-Tool](https://camille1223.github.io/Payment-Notice-Tool/)

#### 失败的项目 · The Lesson: Fake Copilot

**中文**
- 想法：很多同事还在排队等 Copilot，于是做了一个 Office.js 插件版 Claude，实现 80% 的 Copilot 功能
- 结局：代码写好、安装包就位，但 SAP IT 封锁了所有 Office 插件 sideload 通道，无法安装，以失败告终
- 教训：AI 能做任何东西，公司权限才是真正的墙；先查权限，再投入开发

**English**
- Idea: built a "Fake Copilot" — an Office.js add-in powered by Claude delivering ~80% of Copilot's features, free for everyone
- Outcome: code ready, install package ready — but SAP IT blocks all three Office add-in sideload channels; could not install on any SAP laptop
- Lesson: AI can build anything; corporate permissions are real walls. Always check before you invest in the build.

---

### 09 · 部署与复用 Deploy & Reuse

**中文**
- **GitHub Pages** — 前端免费托管，分享链接即可使用
- **Render** — 后端免费云托管，一次设置，永久运行
- 一次性投入，长期回报：第一次建好之后，所有人直接点 Live Demo 就能用

**English**
- **GitHub Pages** — Free frontend hosting; share the link, anyone can use it instantly
- **Render** — Free backend cloud hosting; one-time setup, runs forever
- One-time investment, long-term payoff: build once, the whole team benefits always

---

### 10 · AI 大时代愿景 The Bigger Picture — All In on AI

**中文**
- All-in AI 时代，最有价值的是**创意和想法**，AI 负责执行
- 未来可能：批量提 ticket、自动生成周报、智能对账、一键审计追踪
- 一位同事说："一个个提 ticket 太麻烦了" —— 这正是 AI 能解决的问题
- 瓶颈不再是技术能力，而是**权限和想象力**

**English**
- In an AI-first world, **creativity and ideas** are the most valuable asset; AI handles execution
- What could be next: batch ticket creation, auto weekly reports, smart invoice reconciliation, one-click audit trail
- A colleague once said: "Creating tickets one by one is so tedious…" — that's exactly the problem AI solves
- The bottleneck is no longer technical ability — it's **permission and imagination**

---

### 11 · 这个 Slides 是怎么做的 How This Deck Was Made

**中文**
| 工具 | 用途 |
|------|------|
| **Claude Code** | 整个演讲稿在 Claude Code 对话中生成 |
| **/sap-slides Skill** | SAP 品牌 slides 技能，Indigo 调色板，20+ 布局，自动动画 |
| **Playwright MCP** | 浏览器自动化，before/after 截图全自动完成，无需手动操作 |
| **Python Generator** | Python 脚本组装 HTML，logo 与截图 base64 内嵌，零运行时依赖 |
| **终端对话** | 无 Figma，无 PowerPoint，全程用自然语言在终端里描述需求 |

> 这个 deck 本身就是它介绍的工具的 live demo。

**English**
| Tool | Role |
|------|------|
| **Claude Code** | Entire presentation designed and written inside Claude Code via conversation |
| **/sap-slides Skill** | SAP-branded slides skill; Indigo palette, 20+ layouts, animation patterns |
| **Playwright MCP** | Browser automation; before/after screenshots captured with zero manual steps |
| **Python Generator** | Python script assembles final HTML; SAP logo + screenshots embedded as base64 |
| **Terminal conversation** | No Figma, no PowerPoint; every decision made in plain language in the terminal |

> This deck is itself a live demo. The same tools described in these slides were used to *create* these slides.

---

### 12 · Q&A

**中文**
- 你最想先做什么？
- 没有任何问题是太基础的！

**English**
- What would *you* like to build first?
- No question is too basic — ask away!

---

## 技术栈 · Tech Stack

- **HTML / CSS / JS** — 单文件，零依赖，内联所有资源
- **SAP 72 Font** — SAP 官方字体
- **Space Grotesk** — 标题展示字体
- **Indigo Palette** — `#5D36FF` / `#7858FF` / `#B894FF` / `#E2D8FF`
- **IntersectionObserver** — 进入视口触发逐帧动画
- **Base64 Embedding** — SAP logo 与截图内嵌，无外部请求

## 使用方法 · How to Use

```bash
# 直接双击 index.html 或用任意浏览器打开
# Just open index.html in any browser

# 键盘导航 / Keyboard navigation:
→ / Space    下一张 / Next slide
←            上一张 / Previous slide
Escape       幻灯片导航总览 / Slide overview
Home / End   第一张 / 最后一张
```

## 许可证 · License

MIT
