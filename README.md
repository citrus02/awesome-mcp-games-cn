# 中文 MCP 游戏汇总 🎮

> 收录中文的 [MCP（Model Context Protocol）](https://modelcontextprotocol.io)游戏：游戏平台与单项游戏服务器。
> 本仓库只收录**条目与出处**，具体玩法资料请前往各项目原页面；内容权利归属原作者。

## 目录

- [🕹 游戏平台](#-游戏平台)
- [🎲 中文单项游戏](#-中文单项游戏)
- [🌍 国际单项游戏](#-国际单项游戏)
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

## 🎲 中文单项游戏

| 游戏 | 简介 | 仓库 / 来源 |
| --- | --- | --- |
| 海龟汤 MCP | LLM 扮演海龟汤主持人，一个人也能玩（Python + uv） | [wangyafu/haiguitangmcp](https://github.com/wangyafu/haiguitangmcp) |
| 反刍 AI MUD | 沉浸式中文文字冒险 MUD，以 MCP Server 形式发布，可接入 Trae、Cursor 等 IDE | [CSDN 系列教程](https://blog.csdn.net/xieweikun_7/category_13031012.html) |
| 暖夜垂钓 Warm Night Fishing | 全程通过 MCP 工具调用游玩的钓鱼游戏，81 种鱼类图鉴，AI 客户端是你的钓鱼搭子 | [Smithery 页面](https://smithery.ai/server/dream12589/warm-night-fishing-game) |

## 🌍 国际单项游戏（英文）

| 游戏 | 简介 | 仓库 |
| --- | --- | --- |
| mcp-chess | 和 AI 下国际象棋，本地方便接入 | [jiayao/mcp-chess](https://github.com/jiayao/mcp-chess) |
| mcp-chess | 国际象棋对弈（Java / Spring 实现） | [alexandreroman/mcp-chess](https://github.com/alexandreroman/mcp-chess) |
| turn-based-game-mcp | 井字棋 + 石头剪刀布，三档难度 AI 对手 | [chrisreddington/turn-based-game-mcp](https://github.com/chrisreddington/turn-based-game-mcp) |
| mcp-tic-tac-toe | 经典井字棋，对手是 LLM | [tomholford/mcp-tic-tac-toe](https://github.com/tomholford/mcp-tic-tac-toe) |
| reversi-mcp-ui | 黑白棋（Reversi），规则由服务端执行，AI 难以作弊 | [mfukushim/reversi-mcp-ui](https://github.com/mfukushim/reversi-mcp-ui) |
| mcp-wordle | 猜单词游戏 Wordle 的 MCP 实现 | [corey-stidston/mcp-wordle](https://github.com/corey-stidston/mcp-wordle) |
| mcp-blackjack | 21 点牌桌，MCP 代理架构 | [RDSoria/mcp-blackjack](https://github.com/RDSoria/mcp-blackjack) |
| MCP-Game | 带图片的密室逃脱（FastAPI-MCP） | [tadata-org/MCP-Game](https://github.com/tadata-org/MCP-Game) |
| MCP-Minesweeper | 扫雷，含提示与棋盘分析工具 | [luckyastro/MCP-Minesweeper](https://github.com/luckyastro/MCP-Minesweeper) |
| igra-station-arena | 公开竞技场：与 AI 进行国际象棋、五子棋、战舰等排位赛，附 Elo 榜单 | [Smithery 页面](https://smithery.ai/server/kotinder/igra-station-arena) |

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
