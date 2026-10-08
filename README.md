# effective-ai-dialogue

高效 AI 对话与提问：**CONTEXT 骨架**、**反问式学习**、**反向思维（反证 / 事前验尸）**、**红队**、可复制模板。  
适用于 ChatGPT、Claude、Gemini、Cursor 及任意对话式大模型。

## 📖 文档导航

### 入门

| 文档 | 内容 |
|------|------|
| [提示词工程基础](docs/提示词工程基础.md) | 大白话讲清提示词的五要素、三个常见错误、两个杀手锏 |
| [实战对比案例](docs/实战对比案例.md) | 5 个场景的「坏提问 vs 好提问」对比，同样的需求不同的结果 |

### 工具

| 文档 | 内容 |
|------|------|
| [场景模板库](docs/场景模板库.md) | 编程 / 学习 / 写作 / 决策 / 分析 / 沟通 的复制即用模板 |
| [中文提问技巧](docs/中文提问技巧.md) | 中文特有的模糊问题、"说人话"的正确用法、模糊需求澄清法 |
| [通用提示词包](universal-prompt-pack.md) | 整份可复制的行为约定 + CONTEXT 骨架 + 模板集 |

### Skill 文件

| 文件 | 用途 |
|------|------|
| [SKILL.md](SKILL.md) | Cursor **Agent Skill**（含 YAML 头，供 Cursor 挂载） |

## 🚀 快速使用

### 非 Cursor 用户（ChatGPT / Claude / DeepSeek / Kimi...）

1. 打开 [universal-prompt-pack.md](universal-prompt-pack.md)
2. 复制 **「助手行为约定」** 或整份文档
3. 粘贴到产品的自定义说明，或新会话第一条消息

**建议先读** [提示词工程基础](docs/提示词工程基础.md)——10 分钟，之后你的提问质量会明显不同。

### Cursor 用户

把本仓库复制到技能目录：

- Windows: `%USERPROFILE%\.cursor\skills\effective-ai-dialogue\`
- macOS/Linux: `~/.cursor/skills/effective-ai-dialogue/`

确保目录内包含 `SKILL.md`。

## 💡 一句话核心

> **好提问 = 把"你以为对方知道"的都说出来 + 给判断标准 + 给例子。**

## 许可证

MIT License — 可自由复制、修改与商用，保留版权声明即可。
