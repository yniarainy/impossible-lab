# 🔬 不可能实验室 · Impossible Lab

> *"在平行宇宙中，没有不可能的实验。"*

**不可能实验室** 是一个单页思想实验模拟器。选择现实中无法实现的物理假说，调整参数，AI 将推演实验结果，并自动生成仿 *Nature* 格式的学术论文。

🌐 **在线体验**：[yniarainy.github.io/impossible-lab](https://yniarainy.github.io/impossible-lab/)

---

## 🧪 三个思想实验

| 实验 | 参数 | 推演内容 |
|------|------|----------|
| 🟫 **立方体地球** | 边长 · 自转速度 · 地轴倾角 | 重力分布、大气流动、海洋形态、气候带、人类定居点、致命危险 |
| 🚲 **光速 30 km/h** | 车速 · 骑行距离 | 洛伦兹因子、时间膨胀、多普勒效应、长度收缩、日常怪象、文明形态 |
| 🧫 **培养皿文明** | 氧气浓度 · 温度 · 重力系数 | 原始汤、生命诞生、大氧化、智慧诞生、科技树、太空计划 |

---

## ✨ 功能

- 🎛️ **参数滑块** — 实时调节实验条件，所见即所得
- 🤖 **AI 推演** — 调用 DeepSeek V4（或任意兼容 OpenAI 接口的模型），输出结构化 JSON 结果
- 🎬 **阶段动画** — 每个推演阶段以卡片形式依次淡入，高潮发现带脉冲光效
- 📄 **Nature 论文生成** — 二次调用 AI，生成 Markdown 格式学术论文，双栏仿期刊排版
- 🌌 **深空视觉** — Canvas 星空背景、霓虹强调色、等宽字体、响应式设计
- 🔐 **隐私优先** — API Key 仅存储在用户浏览器 localStorage，不上传、不收集

---

## 🚀 使用方法

1. 打开网页，点击顶部 **⚙ 设置**
2. 填入你的 API 信息：
   - **Base URL**：`https://api.deepseek.com`（默认）
   - **API Key**：你的 DeepSeek Key
   - **模型**：`deepseek-v4-pro`（推荐）或 `deepseek-v4-flash`
3. 选择一个实验卡片，调整参数滑块
4. 点击 **🚀 运行实验**，等待 AI 推演
5. 实验完成后，点击 **📄 生成 Nature 论文** 查看学术论文

> 💡 兼容任何 OpenAI 接口格式的 API，如 OpenAI、DeepSeek、Ollama 等。

---

## 🛠️ 技术栈

| 层面 | 技术 |
|------|------|
| 前端框架 | 零依赖，原生 HTML/CSS/JS |
| AI 接口 | OpenAI-compatible Chat Completions API |
| 存储 | 浏览器 localStorage |
| 部署 | GitHub Pages（纯静态） |
| 字体 | Courier New · Georgia |

---

## 🔒 隐私说明

- **API Key 不会离开你的浏览器** — 所有 API 调用直接从你的浏览器发起
- **不依赖后端服务器** — 纯前端静态页面
- **代码开源可审计** — 所有逻辑在一个 `index.html` 文件中

---

## 📂 项目结构

```
impossible-lab/
├── docs/
│   └── index.html      # 完整的单文件应用
├── .gitignore
└── README.md
```

---

## 📜 License

MIT — 自由使用、修改、分发。

---

<p align="center">
  <sub>Made with 🌌 by Impossible Lab · Parallel Universe Research Institute · 2026</sub>
</p>
