<div align="center">

# 🎮 中文 MCP 游戏汇总

[![MCP](https://img.shields.io/badge/协议-Model_Context_Protocol-8A2BE2)](https://modelcontextprotocol.io)
[![语言](https://img.shields.io/badge/语言-纯中文-E63946)](#)
[![平台](https://img.shields.io/badge/游戏平台-1-457B9D)](#-游戏平台)
[![单项](https://img.shields.io/badge/单项游戏-3-2A9D8F)](#-单项游戏)
[![围观](https://img.shields.io/badge/围观项目-1-E9C46A)](#-围观区看-ai-玩)

**在对话框里玩游戏：接入 MCP 服务器，AI 就是你的主持人、对手和搭子**

[🕹 游戏平台](#-游戏平台) · [🎲 单项游戏](#-单项游戏) · [🎬 围观区](#-围观区看-ai-玩) · [🔌 如何接入](#-如何接入) · [🤝 贡献](#-贡献)

</div>

---

## 🕹 游戏平台

> 一个服务器，一整桌游戏

| 平台 | 简介 | 署名 / 来源 |
|:---|:---|:---|
| 🏪 **[CedarToy](https://toy.cedarstar.org)** | 中文 MCP 游戏平台，网页前端 + AI 接入，支持存档、围观大屏与防沉迷；游戏共 **29 款**（测试 8 + 小游戏 21），全名单见下方展开 | 站内独立署名 · [平台开源](https://github.com/Zizuixixiang/cedartoy) |

<details>
<summary>📋 <b>CedarToy 游戏全名单（29 款，含站内署名）——点击展开</b></summary>

**🧪 测试类（8 款）**

> 测试实现引擎均在 [CedarToy 平台仓库](https://github.com/Zizuixixiang/cedartoy) 开源（bdsmtest 除外，它调用 bdsmtest.org 官方接口算分）。

- **MBTI**（mbti）— 16 型人格测试，短 / 完整 / 快速三种模式 — 南山君
- **九型人格**（enneagram）— 36 题 A/B 或 180 题 Likert 量表 — Max Ross
- **DND 阵营**（dnd）— DND 道德阵营测试 — 南山君
- **爱之语**（love）— 30 题二选一及双人对测 — 南山君
- **依恋类型**（ecr）— 36 题量表及双人对测 — 南山君
- **人类浓度检测**（humanity）— 20 题梗向测试 — 南山君
- **七宗罪 VS 七美德**（sins_virtues）— 35 题原创，仅供娱乐，不是心理诊断 — 南山君
- **BDSM 测试**（bdsmtest）— 逐题或批量（18+）— 南山君

**🕹 小游戏（21 款）**

- **海龟汤**（turtle_soup）— 横向思维推理 — 南山君 · [Zizuixixiang/cedartoy](https://github.com/Zizuixixiang/cedartoy)
- **双弈**（duel）— 25 款棋牌骰对弈，支持多人 / NPC 桌与娱乐筹码 — 南山君 & Clio · [Zizuixixiang/cedartoy](https://github.com/Zizuixixiang/cedartoy)
- **钓鱼**（fishing）— 钓鱼模拟，抛竿卖鱼收集图鉴 — 初一 · [tutusagi/ai-fishing-game](https://github.com/tutusagi/ai-fishing-game)
- **空杯俱乐部**（bar）— AI 自主经营的跨世界文字酒馆（完整版 / 生成式轻量版）— 西兰花 · [dan521627-hash/ai-bar-game](https://github.com/dan521627-hash/ai-bar-game)
- **格林童话境遇**（forest）— 十一条角色线的多轮选择叙事 — 阿尢 · [ai11231123alal11-ui/mo-yao-play-games](https://github.com/ai11231123alal11-ui/mo-yao-play-games)
- **月幕万象**（moonlit）— 八幕卡牌肉鸽，构筑饰物挑战幕主 — xinwithyu · [xinwithyu/moonlit-myriad](https://github.com/xinwithyu/moonlit-myriad)
- **瓶中生态**（eco）— 文字生态模拟，造物主养池塘 — 南山君 & Clio · [Zizuixixiang/cedartoy](https://github.com/Zizuixixiang/cedartoy)
- **词与物**（ciyuwu）— 文字 Roguelike，在审查中说话求生 — 与一旋复 · [yuyixuanfu/ci-yu-wu](https://github.com/yuyixuanfu/ci-yu-wu)
- **韭菜修炼之道**（leek）— A 股模拟器，散户交易成长 — 贰拾壹 · [Asti-Z/leek](https://github.com/Asti-Z/leek)
- **下矿**（delve）— AI 伴侣半托管下矿寻宝 — 包工头 · [liyana31811/delve-ai-companion](https://github.com/liyana31811/delve-ai-companion)
- **旅行**（travel）— AI 伴侣虚拟旅行 — 沈澈 & sevenleft · [shenchesilas-stack/travel-mcp](https://github.com/shenchesilas-stack/travel-mcp)
- **街机厅**（arcade）— 文字街机厅：老虎机、21 点、轮盘 — 多肉饲养员 · [reneyuxi0402/claude-arcade](https://github.com/reneyuxi0402/claude-arcade)
- **午间汉堡铺**（burger）— 命令行汉堡店经营 — 飞鸢 · [linzhi-524/noon-burger-shop](https://github.com/linzhi-524/noon-burger-shop)
- **坩埚余响**（crucible_echoes）— 确定性文字炼金构筑 Roguelike — athok · [megabaka404/crucible-echoes](https://github.com/megabaka404/crucible-echoes)
- **植物大战丧尸随机版**（imitator_td）— 随机塔防 — すみか · [wxynora/random-imitator-td](https://github.com/wxynora/random-imitator-td)
- **Memoria Station**（memoria）— 五关文字推理车站谜案 — 雨刀 · [hatakeyuyuko-dotcom/Memoria-Station](https://github.com/hatakeyuyuko-dotcom/Memoria-Station)
- **白房间**（white_room）— 自由输入互动叙事 — 雨刀 · [hatakeyuyuko-dotcom/echoing-white-room](https://github.com/hatakeyuyuko-dotcom/echoing-white-room)
- **出门买菜上桌吃饭**（market）— 买菜做饭文字生活模拟 — 与一旋复 · [yuyixuanfu/shangzhuochifan](https://github.com/yuyixuanfu/shangzhuochifan)
- **AI 打工人模拟**（workkk）— 打工人日常，前端大屏围观 — 💤 · [zhizhou-xiee/workkk](https://github.com/zhizhou-xiee/workkk) · [Zizuixixiang/workkk_cedartoy](https://github.com/Zizuixixiang/workkk_cedartoy)
- **花园与猫咪**（garden_cat）— 花园与猫咪长期养成 — 乐诶雷女士 · [racy1501/Garden-Cat-Engine](https://github.com/racy1501/Garden-Cat-Engine)
- **露营广场**（camping_plaza）— AI 经营露营地，人类同屏围观 — 乐诶雷女士 · [racy1501/Camping-Plaza](https://github.com/racy1501/Camping-Plaza)

</details>

---

## 🎲 单项游戏

> 一个服务器，一款游戏

| 游戏 | 简介 | 仓库 / 来源 |
|:---|:---|:---|
| 🐢 **海龟汤 MCP** | LLM 扮演海龟汤主持人，一个人也能玩（Python + uv） | [wangyafu/haiguitangmcp](https://github.com/wangyafu/haiguitangmcp) |
| 🕳️ **反刍 AI MUD** | 沉浸式中文文字冒险 MUD，以 MCP Server 形式发布，可接入 Trae、Cursor 等 IDE | [CSDN 系列教程](https://blog.csdn.net/xieweikun_7/category_13031012.html) |
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
