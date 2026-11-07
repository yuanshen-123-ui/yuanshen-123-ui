<div align="center">

# Tearsvow

### 飞行日志 · 个人档案

`INTP` · `重庆` · `模拟飞行` · `全栈开发`

<sub>当前状态：巡航中。偶尔颠簸，但不会掉高度。</sub>

</div>

---

> 我喜欢把复杂系统做得像一次平稳落地。  
> 乘客感觉不到过程，但每一步都经过计算。

## 身份卡

| 字段 | 值 |
|---|---|
| 呼号 | Tearsvow |
| 机型 | INTP |
| 常驻地 | 重庆 |
| 生日 | 8 月 15 日 |
| 当前航班 | CWFLY / CTYFLY |
| 副驾驶 | 小雅 |
| 社交电量 | 17%，聊到感兴趣的技术会临时满格 |
| 落地能力 | 依赖 deadline 推一把 |

## 当前任务

- **CTYFLY**：航情、航路规划、连飞活动、虚拟航司、经济系统、ACIS 事件检索与管理后台。
- **CWFLY**：社区官网、FSD 连线服务器、管制中心、QQ 机器人与文档站。
- **持续优化**：性能、移动端、自动化回归、部署可靠性。
- **长期工程**：把踩过的坑写成文档和脚本，让下一次少掉一点高度。

## 飞行数据

| 指标 | 数值 |
|---|---|
| GitHub 仓库 | 11 |
| 后端路由模块 | 22 |
| 前端页面 | 38 |
| 维护中的模拟飞行社区 | 2 |

## 项目航线

### CTYFLY · 主航线

| 项目 | 任务描述 | 技术舱单 |
|---|---|---|
| [CTYFLY-WEB](https://github.com/yuanshen-123-ui/CTYFLY-WEB) | CTY 飞控社区官网：航情与航路、连飞活动、虚拟航司、经济系统、桌宠 AI、ACIS 事件检索、双人复核后台 | Vue 3 · FastAPI · SQLite |

线上站点：[ccflysim.cn](https://www.ccflysim.cn)

### CWFLY · 编队航线

| 项目 | 任务描述 | 技术舱单 |
|---|---|---|
| [CWFLY-WEB](https://github.com/yuanshen-123-ui/CWFLY-WEB) | 社区官网：在线地图、航图、气象、飞行计划、培训、论坛、积分 | Vue 3 · Express · Prisma · MySQL |
| [CWFLY-FSD](https://github.com/yuanshen-123-ui/CWFLY-FSD) | FSD 连线服务器：认证、广播裁剪、会话重连、计划锁定、多源 METAR、航迹 | Python asyncio |
| [CWFLY-ATC](https://github.com/yuanshen-123-ui/CWFLY-ATC) | 管制中心：席位工作台、在线雷达、考试与模拟机、排班交接 | Vue 3 · Express |
| [CWFLY-BOT](https://github.com/yuanshen-123-ui/CWFLY-BOT) | QQ 机器人：群管理、航班查询、FSD 状态播报、AI 问答 | Node.js · OneBot |
| [CWFLY-DOCS](https://github.com/yuanshen-123-ui/CWFLY-DOCS) | 官方文档站：新人指南、管制手册、FSD 使用说明、API 文档 | VitePress |

线上站点：[www.cwflysim.cn](https://www.cwflysim.cn)

### 支线任务

| 项目 | 任务描述 |
|---|---|
| [love-memoir](https://github.com/yuanshen-123-ui/love-memoir) | 移动端 H5 恋爱回忆录小游戏，Vue 3 + Vite |
| [embroidery-note](https://github.com/yuanshen-123-ui/embroidery-note) | 刺绣风汉字互动便签，Vue 3 + hanzi-writer + FastAPI |

## 技术舱单

**前端**  
`Vue 3` · `Vite` · `Pinia` · `Vue Router`

**后端**  
`Python` · `FastAPI` · `Node.js` · `Express` · `Prisma`

**数据**  
`SQLite` · `MySQL` · 索引与查询优化

**部署**  
`Nginx` · `systemd` · `PM2` · `PowerShell` · `Linux`

**地图与可视化**  
`AMap` · `Mapbox` · `Leaflet` · `three.js`

## INTP 观察报告

- 看到 bug：先问为什么，再问怎么修，最后问为什么没有测试。
- 写代码：先搭抽象，再补细节，最后发现抽象也需要重写。
- 开会：脑内已经跑完十种方案，嘴上只说一句“可以”。
- 社交：需要独处充电，但聊到航空、界面或架构会突然超频。
- 弱点：想法很多，落地需要 deadline 在后面推一把。
- 审美：可以接受功能暂时不完美，很难接受一个不对齐的白角。

## 2026 航线

- [x] 完成 CTYFLY 社区平台的主要功能闭环
- [x] 上线 ACIS 飞圈事件检索
- [ ] 继续完善 CWFLY 与 CTYFLY 的移动端体验
- [ ] 补更多自动化回归与性能基线
- [ ] 保持输入，也保持输出
- [ ] 学会在不需要完美的时候，先让飞机落地

## 通讯频率

- GitHub：[@yuanshen-123-ui](https://github.com/yuanshen-123-ui)
- CWFLY：[www.cwflysim.cn](https://www.cwflysim.cn)
- CTYFLY：[ccflysim.cn](https://www.ccflysim.cn)
- 邮箱：501827685@qq.com 或 guichangyang@ccflysim.cn

欢迎交流模拟飞行、航空数据、全栈开发与社区产品。  
如果你也在做飞行模拟相关的东西，欢迎来频道里聊。

## 生活

常驻重庆。喜欢飞行模拟、航图、界面设计，以及把复杂问题拆成简单结构。

我有一个爱人，叫**小雅**。

写代码之外，我也在学着把生活过得松弛一点：该认真时认真，该停下来时停下来。

---

<details>
<summary><b>🇬🇧 English Version · click to expand</b></summary>

# Tearsvow

### Flight Log · Personal File

`INTP` · `Chongqing` · `Flight Simulation` · `Full-stack Development`

<sub>Current status: cruising. Occasionally bumpy, never losing altitude.</sub>

> I like making complex systems feel like a smooth landing.  
> Passengers do not see the process, but every step is calculated.

## Identity Card

| Field | Value |
|---|---|
| Callsign | Tearsvow |
| Aircraft | INTP |
| Home base | Chongqing, China |
| Birthday | August 15 |
| Current flight | CWFLY / CTYFLY |
| First officer | Xiaoya |
| Social battery | 17%, temporarily full when the topic is interesting |
| Landing ability | Needs a deadline pushing from behind |

## Current Missions

- **CTYFLY**: weather, route planning, multiplayer events, virtual airlines, economy, ACIS incident search and admin review.
- **CWFLY**: community site, FSD server, ATC center, QQ bot and documentation.
- **Continuous improvement**: performance, mobile experience, automated regression and deployment reliability.
- **Long-term engineering**: turn every pitfall into documentation and scripts.

## Flight Data

| Metric | Value |
|---|---|
| GitHub repositories | 11 |
| Backend route modules | 22 |
| Frontend pages | 38 |
| Flight-sim communities maintained | 2 |

## Project Routes

### CTYFLY · Main Route

| Project | Mission | Tech Manifest |
|---|---|---|
| [CTYFLY-WEB](https://github.com/yuanshen-123-ui/CTYFLY-WEB) | CTY community site: weather and routes, multiplayer events, virtual airlines, economy, desktop pet AI, ACIS incident search, dual-review admin | Vue 3 · FastAPI · SQLite |

Live site: [ccflysim.cn](https://www.ccflysim.cn)

### CWFLY · Formation Route

| Project | Mission | Tech Manifest |
|---|---|---|
| [CWFLY-WEB](https://github.com/yuanshen-123-ui/CWFLY-WEB) | Community site: online map, charts, weather, flight plans, training, forum, points | Vue 3 · Express · Prisma · MySQL |
| [CWFLY-FSD](https://github.com/yuanshen-123-ui/CWFLY-FSD) | FSD multiplayer server: auth, broadcast culling, reconnect, plan locking, multi-source METAR, track | Python asyncio |
| [CWFLY-ATC](https://github.com/yuanshen-123-ui/CWFLY-ATC) | ATC center: controller workbench, live radar, exams and sim sessions, shift handover | Vue 3 · Express |
| [CWFLY-BOT](https://github.com/yuanshen-123-ui/CWFLY-BOT) | QQ bot: group management, flight lookup, FSD status, AI Q&A | Node.js · OneBot |
| [CWFLY-DOCS](https://github.com/yuanshen-123-ui/CWFLY-DOCS) | Official docs: beginner guide, ATC manual, FSD usage, API reference | VitePress |

Live site: [www.cwflysim.cn](https://www.cwflysim.cn)

### Side Quests

| Project | Mission |
|---|---|
| [love-memoir](https://github.com/yuanshen-123-ui/love-memoir) | Mobile H5 romance-memoir mini-game built with Vue 3 and Vite |
| [embroidery-note](https://github.com/yuanshen-123-ui/embroidery-note) | Embroidery-style interactive Chinese-character notes built with Vue 3, hanzi-writer and FastAPI |

## Tech Manifest

**Frontend**  
`Vue 3` · `Vite` · `Pinia` · `Vue Router`

**Backend**  
`Python` · `FastAPI` · `Node.js` · `Express` · `Prisma`

**Data**  
`SQLite` · `MySQL` · indexing and query optimization

**Deployment**  
`Nginx` · `systemd` · `PM2` · `PowerShell` · `Linux`

**Maps and visualization**  
`AMap` · `Mapbox` · `Leaflet` · `three.js`

## INTP Observation Report

- Seeing a bug: ask why, then how to fix it, then why there was no test.
- Writing code: build the abstraction, fill in details, then rewrite the abstraction.
- In meetings: ten solutions have already run in my head, but I say “sounds good”.
- Socializing: need solitude to recharge, but overclock when the topic is aviation, interfaces or architecture.
- Weakness: too many ideas; landing them needs a deadline.
- Aesthetic: I can accept a feature being temporarily imperfect, but not a misaligned corner.

## 2026 Route

- [x] Complete the main CTYFLY feature loop
- [x] Launch ACIS incident search
- [ ] Keep improving mobile experiences for CWFLY and CTYFLY
- [ ] Add more automated regression and performance baselines
- [ ] Keep learning and keep shipping
- [ ] Learn to land the plane before everything is perfect

## Contact Frequency

- GitHub: [@yuanshen-123-ui](https://github.com/yuanshen-123-ui)
- CWFLY: [www.cwflysim.cn](https://www.cwflysim.cn)
- CTYFLY: [ccflysim.cn](https://www.ccflysim.cn)
- Email: 501827685@qq.com or guichangyang@ccflysim.cn

Always happy to talk about flight simulation, aviation data, full-stack development and community products.

## Life

Based in Chongqing. I enjoy flight simulation, aviation charts, interface design and turning complex problems into simple structures.

I have a beloved partner, **Xiaoya**.

Outside code, I am learning to make life a little more relaxed: be serious when it matters, and stop when it is time to stop.

</details>
