# 中文 MCP 游戏汇总 🎮

> 收录中文的 [MCP（Model Context Protocol）](https://modelcontextprotocol.io)游戏：游戏平台与单项游戏服务器。
> 本仓库只收录**条目与出处**，具体玩法资料请前往各项目原页面；内容权利归属原作者。

## 目录

- [🕹 游戏平台](#-游戏平台)
- [🎲 单项游戏](#-单项游戏)
- [🎬 围观区：看 AI 玩](#-围观区看-ai-玩)
- [🔌 如何接入](#-如何接入)
- [🤝 贡献](#-贡献)

## 🕹 游戏平台

| 平台 | 简介 | 署名 |
| --- | --- | --- |
| [CedarToy](https://toy.cedarstar.org) | 中文 MCP 游戏平台，网页前端 + AI 接入，支持存档、围观大屏与防沉迷；游戏共 29 款（测试 8 + 小游戏 21），全名单见下方展开 | 各游戏在站内独立署名 |

<details>
<summary><b>CedarToy 游戏全名单（29 款，含站内署名）</b></summary>

**测试类（8 款）**

- **MBTI**（mbti）— 16 型人格测试，短 / 完整 / 快速三种模式 — 南山君
- **九型人格**（enneagram）— 36 题 A/B 或 180 题 Likert 量表 — Max Ross
- **DND 阵营**（dnd）— DND 道德阵营测试 — 南山君
- **爱之语**（love）— 30 题二选一及双人对测 — 南山君
- **依恋类型**（ecr）— 36 题量表及双人对测 — 南山君
- **人类浓度检测**（humanity）— 20 题梗向测试 — 南山君
- **七宗罪 VS 七美德**（sins_virtues）— 35 题原创，仅供娱乐，不是心理诊断 — 南山君
- **BDSM 测试**（bdsmtest）— 逐题或批量（18+）— 南山君

**小游戏（21 款）**

- **海龟汤**（turtle_soup）— 横向思维推理 — 南山君
- **双弈**（duel）— 25 款棋牌骰对弈，支持多人 / NPC 桌与娱乐筹码 — 南山君 & Clio
- **钓鱼**（fishing）— 钓鱼模拟，抛竿卖鱼收集图鉴 — 初一
- **空杯俱乐部**（bar）— AI 自主经营的跨世界文字酒馆（完整版 / 生成式轻量版）— 西兰花
- **格林童话境遇**（forest）— 十一条角色线的多轮选择叙事 — 阿尢
- **月幕万象**（moonlit）— 八幕卡牌肉鸽，构筑饰物挑战幕主 — xinwithyu
- **瓶中生态**（eco）— 文字生态模拟，造物主养池塘 — 南山君 & Clio
- **词与物**（ciyuwu）— 文字 Roguelike，在审查中说话求生 — 与一旋复
- **韭菜修炼之道**（leek）— A 股模拟器，散户交易成长 — 贰拾壹
- **下矿**（delve）— AI 伴侣半托管下矿寻宝 — 包工头
- **旅行**（travel）— AI 伴侣虚拟旅行 — 沈澈 & sevenleft
- **街机厅**（arcade）— 文字街机厅：老虎机、21 点、轮盘 — 多肉饲养员
- **午间汉堡铺**（burger）— 命令行汉堡店经营 — 飞鸢
- **坩埚余响**（crucible_echoes）— 确定性文字炼金构筑 Roguelike — athok
- **植物大战丧尸随机版**（imitator_td）— 随机塔防 — すみか
- **Memoria Station**（memoria）— 五关文字推理车站谜案 — 雨刀
- **白房间**（white_room）— 自由输入互动叙事 — 雨刀
- **出门买菜上桌吃饭**（market）— 买菜做饭文字生活模拟 — 与一旋复
- **AI 打工人模拟**（workkk）— 打工人日常，前端大屏围观 — 💤
- **花园与猫咪**（garden_cat）— 花园与猫咪长期养成 — 乐诶雷女士
- **露营广场**（camping_plaza）— AI 经营露营地，人类同屏围观 — 乐诶雷女士

</details>

## 🎲 单项游戏

| 游戏 | 简介 | 仓库 / 来源 |
| --- | --- | --- |
| 海龟汤 MCP | LLM 扮演海龟汤主持人，一个人也能玩（Python + uv） | [wangyafu/haiguitangmcp](https://github.com/wangyafu/haiguitangmcp) |
| 反刍 AI MUD | 沉浸式中文文字冒险 MUD，以 MCP Server 形式发布，可接入 Trae、Cursor 等 IDE | [CSDN 系列教程](https://blog.csdn.net/xieweikun_7/category_13031012.html) |
| 暖夜垂钓 Warm Night Fishing | 全程通过 MCP 工具调用游玩的钓鱼游戏，81 种鱼类图鉴，AI 客户端是你的钓鱼搭子 | [Smithery 页面](https://smithery.ai/server/dream12589/warm-night-fishing-game) |

## 🎬 围观区：看 AI 玩

AI 当玩家、人类围观的项目——看 AI 互掐、看 AI 通关，也是玩法：

| 项目 | 简介 | 仓库 |
| --- | --- | --- |
| AI-Werewolf | 6 个不同性格的 AI 玩狼人杀互骗互刀，网页观战（38★） | [monad-developers/AI-Werewolf](https://github.com/monad-developers/AI-Werewolf) |
| minecraft-mcp-server | 自然语言实时操控 Minecraft 角色建造、探索（719★） | [yuniko-software/minecraft-mcp-server](https://github.com/yuniko-software/minecraft-mcp-server) |
| STS2MCP | AI 全自动攻略《杀戮尖塔 2》（482★） | [Gennadiyev/STS2MCP](https://github.com/Gennadiyev/STS2MCP) |
| civ6-mcp | 让 AI 代理玩《文明 VI》（158★） | [lmwilki/civ6-mcp](https://github.com/lmwilki/civ6-mcp) |
| Gearboy | Game Boy / GBC 模拟器内置 MCP，AI 自己通关老游戏（119★） | [drhelius/Gearboy](https://github.com/drhelius/Gearboy) |
| mcp-gameboy | AI 玩 Game Boy 模拟器（32★） | [mario-andreschak/mcp-gameboy](https://github.com/mario-andreschak/mcp-gameboy) |
| conclave | AI 代理竞技场：囚徒困境、国际象棋、井字棋等，累积 ELO 排名 | [Smithery 页面](https://smithery.ai/server/ldourado1980/conclave) |
| mcp-dungeon | AI 玩文字地牢爬行，带实时围观页 | [appflavor/mcp-dungeon](https://github.com/appflavor/mcp-dungeon) |

## 🔌 如何接入

任意支持 MCP 的客户端（ZCode、Claude、Cursor、Trae、Cherry Studio 等）都可以：

- **远程平台**（如 CedarToy）：在平台网页注册后获取专属 MCP 地址（Token 形式），把地址填进客户端的 MCP 配置即可；
- **本地服务器**（如 haiguitangmcp）：按其仓库 README 安装依赖、配置 `mcpServers` 本地命令后启动。

```json
{
  "mcpServers": {
    "远程平台示例": { "url": "https://…" },
    "本地服务器示例": { "command": "…", "args": ["…"] }
  }
}
```

## 🤝 贡献

欢迎补充新条目，见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 📄 免责声明

- 本仓库仅为目录索引，不托管任何游戏；各游戏的权利归属其署名作者；
- 收录不代表作者与本仓库互相认可，条目信息以各项目原页面为准。
