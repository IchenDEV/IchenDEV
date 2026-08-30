# idevlab/IchenDEV

hacker & creator

- 📝 博客: [blogs.idevlab.dev](https://blogs.idevlab.dev/)
- 🌐 主页: [www.idevlab.dev](https://www.idevlab.dev/)

## 🚀 最近在折腾的项目

### 🎮 AI 小游戏与应用

- 🎮 [AI 小游戏合集](https://github.com/IchenDEV/mini-game) - 五款独立浏览器小游戏的统一仓库，保留原项目历史，一次构建并发布到 GitHub Pages。
- 🏠 [room-design](https://github.com/IchenDEV/room-design) - 网页版室内设计工作台：2D 户型编辑、3D 实时渲染、第一人称漫游、家具素材库和 IndexedDB 自动保存。

### 🍎 macOS 与桌面应用

- 🎨 [豆皮](https://github.com/IchenDEV/doubao-skin) - 给 macOS 版「豆包」与「豆包工作」换主题的工具，包含原生客户端、在线主题库和可验证的主题包。
- 💻 [C2](https://github.com/IchenDEV/codeTwo) - 文档优先的 coding agent 工作台，用同一个 Rust 核心驱动桌面客户端、TUI 和远程 Web，并接入多种 coding CLI。
- 🪁 [Kite](https://github.com/IchenDEV/kite) - 面向 macOS 26+ 的原生多协议下载器，用 SwiftUI、AppKit 和只监听本机的 `aria2-next` sidecar 实现。
- 🐾 [PetX Desktop](https://github.com/IchenDEV/petx-desktop) - 一只本地优先的跨平台桌面伙伴，用 Tauri 和 PetX React 把陪伴、照料、关系记忆、宠物发现与本地导入放进透明桌面窗口。
- 🎙️ [Utter](https://github.com/IchenDEV/utter) - 把 AI 语音输入放进 macOS 菜单栏；按下说话、松开出字，支持本地推理、智能格式化和语音指令。
- 🧰 [SkillsUI](https://github.com/IchenDEV/skills-ui) - 给 `skills.sh` 做了个原生 macOS 管理器，浏览、安装、整理不同 coding agents 的技能包更顺手。
- 🔔 [Mind Keeper](https://github.com/IchenDEV/mind-keeper) - 一个 macOS 上的 AI 通知分拣助手，盯着通知中心、帮你判断轻重缓急，把该做的事从消息堆里捞出来。
- 🗂️ [F5](https://github.com/IchenDEV/f5) - 一个本地 AI 工作台，用来跟 coding agents 对话、查看任务进展，并把每段会话保存成磁盘上的 Markdown 文件。

### 🧩 Agent 基础设施

- 🔄 [AI-Native SDLC Skill](https://github.com/IchenDEV/sdlc-skill) - 把需求、上下文、执行、验证、审批和运维串成可连续推进的 Agent Skill，同时兼容 Codex 与 Claude Code。
- 🧰 [C2 Community Plugins](https://github.com/IchenDEV/c2-plugins) - C2 的社区插件目录，只保存经校验且锁定到不可变提交的目录条目。
- 🧩 [DSH Plugins](https://github.com/IchenDEV/dsh-plugins) - DeepSeek Harness 的仓外插件合集，覆盖飞书文档、iOS 模拟器、语音输入、Git worktree 等能力。
- 🛍️ [Agent Plugins Marketplace](https://github.com/IchenDEV/agent-plugin-mkt) - 一个开源 Agent 插件索引，自动发现并校验 Codex、Claude Code 和 Agent Plugins 仓库，同时提供 Web、REST API、MCP 与 agent-readable feeds。
- 🪄 [Prompt Optimizer](https://github.com/IchenDEV/prompt-optimizer-plugins) - 一套可移植的模型专用提示词优化技能，同一份插件可以跑在 Codex、Claude Code 和 Agent Plugins 客户端里。
- 🔗 [GB/Z 185 SDK](https://github.com/IchenDEV/gbz185-sdk) - 面向 GB/Z 185-2026 智能体互联标准的 TypeScript SDK 与参考运行时，覆盖身份、发现、交互、消息分发和工具调用。
- 🖼️ [PetX](https://github.com/IchenDEV/petx) - Codex pet spritesheet atlas 的渲染框架，把同一套动画资源接到 Web、Canvas 和不同前端框架里复用。
- 🔐 [Passka](https://github.com/IchenDEV/passka) - 想办法让 agent 用密钥这件事更靠谱：长期凭证留在 Keychain，agent 只拿短期 lease，访问全程可审计。
- ⚡ [agentalk](https://github.com/IchenDEV/agentalk) - 把 `curl` 那种直给手感带到 agent world，让 A2A 协议在终端里也变得顺手。
- ⛏️ [AI Mine](https://github.com/IchenDEV/aimine) - 一个 AI Agent 探索平台，把 RAG、知识图谱、记忆、技能和 MCP 串在一起，顺手拿来试 ReAct、Plan 和多专家协作这套玩法。
- 🧠 [mem-x](https://github.com/IchenDEV/mem-x) - 一个自进化的 AI 记忆系统，把会话记忆、短期记忆和长期记忆串起来，让 agent 不只是会回答，还能慢慢长出“记性”。
- 📁 [LarkFS](https://github.com/IchenDEV/larkfs) - 把飞书/Lark 变成本地文件系统，云端文档、消息和资源终于也能像文件一样被折腾。

### 🛠️ 开发者工具

- 🩺 [Codex Fix](https://github.com/IchenDEV/codex-fix) - 一个 macOS 上的 Codex 资源泄漏诊断与缓解工具；默认只读，任何文件或进程改动都需要显式确认。
- 🧮 [Oxlint Cognitive Complexity](https://github.com/IchenDEV/oxlint-plugin-cognitive-complexity) - 给 Oxlint 补上认知复杂度检查，能按阈值找出 JavaScript 和 TypeScript 里过度复杂的函数。

### 🏘️ 多 Agent 实验

- 🧑‍🤝‍🧑 [Town Sandbox](https://github.com/IchenDEV/town-sandbox) - 把一群 AI agents 丢进虚拟小镇里，让他们自己生活、工作、交易、聊天，顺手把整个过程可视化出来。
- 🏮 [圆桌 Skill 云](https://github.com/IchenDEV/roundtable-skill-cloud/tree/main) - 请不同人物视角同席开聊，既能辩论也能共创，最后再由主持人整理成一份结案。

### 🌌 体验实验

- 🌐 [idevlab Home Page](https://github.com/IchenDEV/home-page) - 终端风格的个人主页，用 Three.js 呈现 3D 交互，并每天同步 GitHub 项目、贡献、动态和博客文章。
- 🎙️ [VoiceCanvas](https://github.com/IchenDEV/voicecanvas) - 一个语音优先的图表工作台，把自然语言指令变成可验证的图结构更新，再用 Mermaid 画出来。
- 🎭 [Mindscape](https://github.com/IchenDEV/mindscape) - 一个虚拟世界，偏向氛围、情绪和交互体验，把抽象感受做成可以进入的数字场景。

### 🧠 知识与技能系统

- 📚 [页脉](https://github.com/IchenDEV/yemai) - 一个本地优先的 AI 阅读记忆书架，用语音、OCR 和知识连接保存每一次阅读。
- 🦸 [superman](https://github.com/IchenDEV/superman) - 一个持续扩建的视角型 Agent Skills 库，把顶级人物的思维方式蒸馏成能直接拿来用的认知插件。
- 📖 [cold-start-2-ai-book](https://github.com/IchenDEV/cold-start-2-ai-book) - 用 GPT 写一本书的实验，看模型能不能从冷启动一路写到一本可读的成稿。

## 📊 GitHub 概览

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img style="max-width: 48%;" src="https://github-readme-stats.vercel.app/api?username=IchenDEV&show_icons=true&count_private=true&hide=contribs" alt="GitHub Stats">
  <img style="max-width: 48%;" src="https://github-readme-stats.vercel.app/api/top-langs/?username=IchenDEV&layout=compact" alt="Most Used Language">
</a>

## 🗃️ 已归档项目

- 🎮 [best-game](https://github.com/IchenDEV/best-game)、[pubg-clone](https://github.com/IchenDEV/pubg-clone) 和 [pokemon-clone](https://github.com/IchenDEV/pokemon-clone) - 独立仓库已归档，代码与历史已合并到 [AI 小游戏合集](https://github.com/IchenDEV/mini-game)。
- 🎧 [Podcast Transcript Studio](https://github.com/IchenDEV/podcast-transcript-studio) - 本地优先的播客订阅、下载、转写与整理工具。

## 🛤 来时的路（Early Works）

- 🎮 [MinesweeperS](https://github.com/IchenDEV/MinesweeperS)（2017） — 最早上架到微软商店的桌面小游戏之一，作为我最早的产品化尝试之一。
- 🗂️ [ExplorerMax](https://github.com/IchenDEV/ExplorerMax)（2018） — 一款早期的文件资源浏览器，用于增强 Windows 文件管理体验。
- 🧰 [Dream_CPP](https://github.com/IchenDEV/Dream_CPP)（2018） — 基于 Windows UWP 的轻量级 C++ IDE，早期用于本地开发与学习实验。
- 🎲 [MTGameH5-Demo](https://github.com/IchenDEV/MTGameH5-Demo)（2020） — 养成类小游戏 Demo，偏前端产品玩法与交互的早期尝试。
- 🧠 [os-pintos](https://github.com/IchenDEV/os-pintos)（2020） — 操作系统课程设计项目，属于底层系统能力的早期沉淀。
- 💬 [JXH-QQBot](https://github.com/IchenDEV/JXH-QQBot)（2020） — 早期的 QQ 机器人实验，偏即时通讯场景下的交互与自动化探索。
- 💻 [XPS9570-OC](https://github.com/IchenDEV/XPS9570-OC)（2020） — Dell XPS 9570 的 OpenCore 配置。
- 🧪 [docker-pintos-m1](https://github.com/IchenDEV/docker-pintos-m1)（2020） — 配合课程作业的 Pintos 环境搭建，记录第一代 M1 macOS 下的特殊开发配置。
- ⚖️ [LarkDocAddon-PhoenixWrighAceAttorney](https://github.com/IchenDEV/LarkDocAddon-PhoenixWrighAceAttorney)（2023） — 飞书端的逆转裁判小游戏，能在飞书里直接玩。
