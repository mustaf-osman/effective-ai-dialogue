# effective-ai-dialogue

高效 AI 对话与提问：**CONTEXT 骨架**、**反问式学习**、**反向思维（反证 / 事前验尸）**、**红队**、可复制模板。  
适用于 ChatGPT、Claude、Gemini、Cursor 及任意对话式大模型。

## 文件说明

| 文件 | 用途 |
|------|------|
| [SKILL.md](SKILL.md) | Cursor **Agent Skill**（含 YAML 头，供 Cursor 挂载） |
| [universal-prompt-pack.md](universal-prompt-pack.md) | **通用版**：无 Cursor 专用格式，整份复制到「自定义指令 / 首条消息 / system prompt」 |

## 快速使用（非 Cursor）

1. 打开 `universal-prompt-pack.md`  
2. 复制 **「助手行为约定」** 或整份文档  
3. 粘贴到所使用 AI 产品的自定义说明或新会话第一条消息  

## Cursor 使用

将本仓库克隆或复制到个人技能目录，例如：

- Windows: `%USERPROFILE%\.cursor\skills\effective-ai-dialogue\`
- macOS/Linux: `~/.cursor/skills/effective-ai-dialogue/`

确保目录内包含 `SKILL.md`。

## 发布到你自己的 GitHub

在 [GitHub](https://github.com/new) 新建仓库（例如名称为 `effective-ai-dialogue`），**不要**勾选添加 README / .gitignore / License（本地已有）。

在本目录执行（把 `YOUR_USERNAME` 换成你的 GitHub 用户名）：

```bash
git remote add origin https://github.com/YOUR_USERNAME/effective-ai-dialogue.git
git push -u origin main
```

若使用 SSH：

```bash
git remote add origin git@github.com:YOUR_USERNAME/effective-ai-dialogue.git
git push -u origin main
```

首次推送需在 GitHub 登录或配置 [Personal Access Token](https://github.com/settings/tokens)。

## 许可证

MIT License — 可自由复制、修改与商用，保留版权声明即可。
