<div align="center">

# 🎮 中文 MCP 游戏汇总

[![MCP](https://img.shields.io/badge/协议-Model_Context_Protocol-8A2BE2)](https://modelcontextprotocol.io)
[![语言](https://img.shields.io/badge/语言-纯中文-E63946)](#)
[![单项](https://img.shields.io/badge/单项游戏-2-2A9D8F)](#-单项游戏)
[![围观](https://img.shields.io/badge/围观项目-1-E9C46A)](#-围观区看-ai-玩)

**在对话框里玩游戏：接入 MCP 服务器，AI 就是你的主持人、对手和搭子**

[🎲 单项游戏](#-单项游戏) · [🎬 围观区](#-围观区看-ai-玩) · [🔌 如何接入](#-如何接入) · [🤝 贡献](#-贡献)

</div>

---

## 🎲 单项游戏

> 一个服务器，一款游戏

| 游戏 | 简介 | 仓库 / 来源 |
|:---|:---|:---|
| 🐢 **海龟汤 MCP** | LLM 扮演海龟汤主持人，一个人也能玩（Python + uv） | [wangyafu/haiguitangmcp](https://github.com/wangyafu/haiguitangmcp) |
| 🎣 **暖夜垂钓** | 全程通过 MCP 工具调用游玩的钓鱼游戏，81 种鱼类图鉴，AI 客户端是你的钓鱼搭子 | [Smithery 页面](https://smithery.ai/server/dream12589/warm-night-fishing-game) |

---

## 🎬 围观区：看 AI 玩

> AI 当玩家，人类吃瓜

| 项目 | 简介 | 仓库 |
|:---|:---|:---|
| 🐺 **AI-Werewolf** | 6 个不同性格的 AI 玩狼人杀互骗互刀，网页观战（中文项目） | [monad-developers/AI-Werewolf](https://github.com/monad-developers/AI-Werewolf) |

> 围观型的中文项目目前全网只找到这一个。文明 6、杀戮尖塔 2、Minecraft 等游戏本体虽有官方中文，但对应的 MCP 项目（civ6-mcp、STS2MCP 等）均为英文社区作品，暂不收录。

---

## 🔌 如何接入

任意支持 MCP 的客户端（ZCode、Claude、Cursor、Trae、Cherry Studio 等）都可以：

- **远程平台**：在平台网页注册后获取专属 MCP 地址（Token 形式），把地址填进客户端的 MCP 配置即可；
- **本地服务器**（如 haiguitangmcp）：按其仓库 README 安装依赖、配置 `mcpServers` 本地命令后启动。

```json
{
  "mcpServers": {
    "远程平台示例": { "url": "https://…" },
    "本地服务器示例": { "command": "…", "args": ["…"] }
  }
}
```

---

## 🤝 贡献

发现新的中文 MCP 游戏？欢迎按 [CONTRIBUTING.md](CONTRIBUTING.md) 的收录标准提交，一起把目录补全。

---

## 📄 免责声明

- 本仓库仅为目录索引，不托管任何游戏；各游戏的权利归属其署名作者；
- 收录不代表作者与本仓库互相认可，条目信息以各项目原页面为准。

---

<div align="center">

**[⬆ 回到顶部](#-中文-mcp-游戏汇总)**

<sub>中文 MCP 游戏汇总 · 用对话，玩游戏</sub>

</div>
