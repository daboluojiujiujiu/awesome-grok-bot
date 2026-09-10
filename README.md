# Awesome Grok Bot

精选 **Grok Bot** 玩法、插件、教程与案例。由「仓库管理员」Bot 每日自动维护。

> Grok Bot 是 xAI/SpaceXAI 与 Cursor 推出的常驻 AI 同事：每个 Bot 有自己的云电脑，关了笔记本也能继续干活。本列表**不是** grok.com 聊天、Grok Imagine，或 Grok 模型评测合集。非官方社区整理，与 xAI / Cursor 无隶属关系。

## 目录

- [官方资源](#官方资源)
- [教程与指南](#教程与指南)
- [实战案例](#实战案例)
- [技能 / 插件 / MCP](#技能--插件--mcp)
- [评测对比](#评测对比)
- [开源替代](#开源替代)
- [社区](#社区)
- [相关列表](#相关列表)
- [贡献](#贡献)

## 官方资源

- [Grok Bot Overview](https://docs.x.ai/grok-bot/overview) - xAI 官方总览：持久云电脑、Bot 协作与示范教学
- [Get started](https://docs.x.ai/grok-bot/get-started) - 安装桌面端、登录 Cursor、创建首个 Bot
- [Create and manage Bots](https://docs.x.ai/grok-bot/bots) - 命名、职责、复制/分享与记忆边界
- [Skills and routines](https://docs.x.ai/grok-bot/skills-routines-and-automations) - Skill、示范教学、定时/事件 Routine
- [Computer and apps](https://docs.x.ai/grok-bot/computer-and-apps) - 连接器、浏览器接管与账号级共享会话
- [Message and collaborate](https://docs.x.ai/grok-bot/chat-and-collaboration) - 群聊、@提及、Bot 间异步交接与线程/反应
- [Approvals, security, and privacy](https://docs.x.ai/grok-bot/approvals-security-and-privacy) - 审批边界、Auto Review、凭据交接
- [Grok Bot security](https://docs.x.ai/grok-bot/security) - 企业网络控制、Action Recording、按用户 Firecracker 隔离
- [Grok Bot security FAQ](https://docs.x.ai/grok-bot/security-faq) - 隔离边界、插件屏蔽≠浏览器屏蔽、Network Controls 范围
- [Grok Bot for mobile](https://docs.x.ai/grok-bot/mobile) - iOS / Android 官方文档与商店入口
- [Teams and enterprises](https://docs.x.ai/grok-bot/teams-and-enterprises) - 团队仪表盘与插件/MCP 策略
- [Settings and notifications](https://docs.x.ai/grok-bot/settings-and-notifications) - 时区、Auto-review、用量与 Team Setup
- [Frequently asked questions](https://docs.x.ai/grok-bot/faq) - 共享电脑边界、套餐与平台支持等常见问
- [Introducing Grok Bot](https://x.ai/news/introducing-grok-bot) - 2026-08-11 产品发布说明
- [Grok Bot is now included with more plans](https://x.ai/news/grok-bot-more-plans) - 套餐覆盖扩展说明
- [Designing Grok Bot for a world of persistent agents](https://x.ai/news/designing-grok-bot) - 2026-09-03 设计长文：名册、Presence、专属电脑与 Routines
- [Grok Bot for Enterprise](https://x.ai/news/grok-bot-for-enterprise) - 2026-09-03 企业版治理与审计
- [Setting Grok Bot loose on procurement](https://x.ai/news/grok-bot-procurement) - 2026-09-04 官方 Haggle 采购案例（证据链省下六位数）
- [Grok Bot product page](https://x.ai/bot) - 下载入口与 FAQ
- [Grok Bot Guides](https://x.ai/bot/guides) - 官方实践手册入口（多团队、移动端工作室、GTM、PM 等）
- [Grok Bot now works with X](https://x.ai/news/grok-bot-and-x) - 连接 X，搜索帖子与时间线
- [Grok Bot on the App Store](https://apps.apple.com/us/app/grok-bot/id6794501026) - iOS 正式商店页
- [Grok Bot on Google Play](https://play.google.com/store/apps/details?id=ai.x.grok.bot) - Android 正式商店页
- [Grok Bot is Now Live on Android](https://forum.cursor.com/t/grok-bot-is-now-live-on-android/170384) - 2026-09-02 Cursor 官方 Android 上线公告
- [Cursor: Getting started](https://cursor.com/help/grok-bot/getting-started) - Cursor 帮助中心上手与排障
- [Cursor: Connect plugins](https://cursor.com/help/grok-bot/connect-plugins) - Gmail/Notion/Slack 等；含 Zoom 4700 已知问题
- [Cursor: Recover computer data](https://cursor.com/help/grok-bot/computer-recovery) - 恢复优先于 Reset；聊天历史不在 box 上
- [Cursor: Plans and billing](https://cursor.com/help/grok-bot/plans) - 计划包含关系与周用量
- [Cursor Forum: Introducing Grok Bot](https://forum.cursor.com/t/introducing-grok-bot/168053) - 官方公告帖
- [xAI plugin marketplace](https://github.com/xai-org/plugin-marketplace) - 官方插件市场索引

## 教程与指南

- [What Is Grok Bot? Pricing and How It Works](https://skillselion.com/guides/what-is-grok-bot) - Bot / Computer / Skills / Plugins 边界拆解
- [The Ultimate Guide to Grok Bot](https://linas.substack.com/p/grok-bot-guide) - 搭建顺序、11 条可粘贴提示与 8 条端到端工作流
- [Mem0: Grok Bot setup walkthrough](https://mem0.ai/blog/grok-bot-guide) - 实机截图：公开检索 → Notion 授权 → 审批闸
- [DataCamp: Skills, Routines, and Approvals](https://www.datacamp.com/tutorial/grok-bot-tutorial) - 把学习 Scout 做成 Skill 再挂周更 Routine
- [MindStudio: Set up and first agents](https://www.mindstudio.ai/blog/grok-bot-setup-guide) - 安装到首个 Agent、插件共享与触发器
- [Composio: Guide to Grok Bot](https://composio.dev/content/guide-to-frok-bot) - 常驻同事、连接器优先与 Composio 插件接入
- [Composio: How to add MCP servers](https://composio.dev/content/how-to-add-mcp-servers-to-grok-bot) - 市场插件 vs 对话加自定义 remote/stdio MCP
- [Flavio Copes: deep dive](https://flaviocopes.com/grok-bot/) - 共享电脑、Skill→Routine、模板分享与 Stripe Link
- [Grok Bot handbook (grokbot.run)](https://grokbot.run/) - 英文上手：登录、首任务、隔离边界、Recover 优先
- [4Geeks: How to set up Grok Bot](https://4geeks.com/en/blog/ai-tools/how-to-set-up-grok-bot) - 十来分钟首装；GitHub 双路径与 X token 注意点
- [Grok Bot Guide: MCP, Setup & Automation](https://www.poster.ly/guides/grokbot-guide) - 远程 MCP、自定义连接器与自动化实践
- [How to Get Started with Grok Bot](https://debbie.codes/blog/how-to-get-started-with-grok-bot) - Debbie 上手与角色编排
- [Grok Bot Masterclass](https://www.dailydoseofds.com/p/grok-bot-masterclass/) - 录屏一次变成技能再挂到例行任务
- [Grok Bot Complete Guide](https://www.gauraw.com/grok-bot-complete-guide-ai-agent-team/) - 安全首装、角色契约与审批进阶
- [João Queirós: Always-On Agents, Routines, Limits](https://www.ai.joaoqueiros.com/blog/grok-bot-always-on-ai-agent-teams-routines-skills-security) - 共享电脑安全边界、Skill/Routine/Trigger 分层与七天试点
- [Grok Bot Architecture (pattern pack)](https://github.com/tiagovilasboas/grok-bot-architecture) - 幕僚→专家→连接器架构与 HITL ADR
- [LaoZhang: Getting Started](https://blog.laozhang.ai/en/posts/grok-bot-getting-started) - 安装登录、账户绑定与首份可核验 PDF 报告（2026-09-08 复核）
- [LaoZhang: X Connector Guide](https://blog.laozhang.ai/en/posts/grok-bot-tutorial) - 连接器≠插件：Connected / Equipped / Verified 三关验收
- [LaoZhang: Cloud Computer](https://blog.laozhang.ai/en/posts/grok-bot-cloud-computer) - 账号级共享电脑边界、接管密钥与审批闸
- [Learn Cursor: Skills & Routines](https://www.learncursor.dev/learn/cursor-agents/grok-bot-skills-routines) - Skill vs Routine、Teach a task、事件触发与可靠标准
- [Continuum: routines, skills, and schedules](https://continuumcode.ai/guides/grok-bot-routines/) - Skill vs Routine、示范录制上限与 20 条运行记录等未确认上限
- [Continuum: What is Grok Bot](https://continuumcode.ai/guides/what-is-grok-bot/) - 对照文档而非发布稿：共享电脑与营销口径差异
- [Continuum: How to use Grok Bot](https://continuumcode.ai/guides/how-to-use-grok-bot/) - 建 Bot、示范教学、挂日程与凭据交接
- [Grok Bot + GitHub tutorial app](https://github.com/GalacticOrgOfDev/grok-bot-github-tutorial) - 互动模块课：GitHub / Routines / Teams / Skills（含测验）
- [Connect GitHub to Grok Bot (Composio)](https://composio.dev/toolkits/github/framework/grok-bot) - 经 Composio 连接 GitHub
- [Connect Gmail to Grok Bot (Composio)](https://composio.dev/toolkits/gmail/framework/grok-bot) - 经 Composio 连接 Gmail
- [Blotato: Social media MCP for Grok Bot](https://www.blotato.com/ai-agent/grok-bot) - 自定义远程 MCP 发社媒
- [Customer.io plugin for Cursor / Grok Bot](https://docs.customer.io/ai/plugins/cursor-grok-bot/) - 官方 MCP+skills 插件说明

## 实战案例

- [Grokularity](https://grokularity.xyz) - 非程序员用 Bot 团队一日搭公司（[论坛帖](https://forum.cursor.com/t/grokularity-a-company-run-by-grok-bots/169471)）
- [10 Grok Bot Use Cases](https://www.bleap.finance/blog/grok-bot-use-cases) - 销售、招聘、QA 等业务场景
- [Grok Bot Explained + launch-week use cases](https://www.ayautomate.com/blog/grok-bot-xai-ai-agents-explained) - 上手截图与四类真实用例
- [OrgBots pack directory](https://forum.cursor.com/t/over-the-weekend-i-built-a-grok-bot-pack-directory-team-is-how-you-mix-your-own/170300) - 社区 Bot pack 目录与组队思路
- [Haggle procurement + template marketplace](https://runtimewire.com/article/grok-bot-template-marketplace-haggle-procurement-agent) - 模板市场（约 69 个公开 Bot）与采购砍价案例
- [Seven-Bot team from a phone (AI Maker)](https://aimaker.substack.com/p/grok-bot-ai-agent-team) - 七席位团队：社媒/幕僚/发票/研究/SEO，手机操控
- [Household Grok Bot swarm](https://github.com/ylgibby/grokbot-household-swarm) - 家庭场景专业 Bot 群写实笔记
- [vidya course-page calendar Bot](https://github.com/vinilpolepalli/vidya) - 每晚 diff 课程页截止日并校对 Google Calendar（学生挑战）
- [Real World Agents org chart](https://github.com/Ridarketh/-real-world-agents) - 按结果席位（非任务清单）组 Grok Bot 组织图
- [Hackathon Spec-to-Ship kit](https://github.com/Iron-Mark/Hackathon-Builder-Grok_Bot) - 五 Bot 小组从研究到公开仓库、无需人工路由
- [Hermes inside Grok Bot’s Linux box](https://github.com/carlosthiene/grok-bot-hermes) - 在账号云电脑装 Hermes + Telegram：两套常驻 agent 共用一台机

## 技能 / 插件 / MCP

- [xai-org/plugin-marketplace](https://github.com/xai-org/plugin-marketplace) - 官方 Grok Build 插件索引（SHA 钉扎）
- [obra/superpowers](https://github.com/obra/superpowers) - 计划→TDD→评审工作流技能包
- [useorgx/orgx-grokbot-plugin](https://github.com/useorgx/orgx-grokbot-plugin) - OrgX MCP 与专家 agent 包
- [mrlynn/grok-bot-plugin-example](https://github.com/mrlynn/grok-bot-plugin-example) - Rooms/lobby 技能与发布脚手架
- [rdmgator12/awesome-grok-bot-plugins](https://github.com/rdmgator12/awesome-grok-bot-plugins) - 219 条应用内 Marketplace 快照
- [mergisi/awesome-grokbot](https://github.com/mergisi/awesome-grokbot) - 可粘贴 Bot 配置与团队模板
- [lroolle/awesome-grokbot-templates](https://github.com/lroolle/awesome-grokbot-templates) - 公开 x.ai/bot 分享链接，按工种分组
- [DominikTobureto/awesome-grok-build](https://github.com/DominikTobureto/awesome-grok-build) - Grok Build 技能与 hooks 起步库
- [ScriptedAlchemy/grok-bot-cli](https://github.com/ScriptedAlchemy/grok-bot-cli) - 复用已登录桌面端：终端列出/创建/消息 Bot
- [Kargatharaakash/grok-bot-mcp](https://github.com/Kargatharaakash/grok-bot-mcp) - 本地 MCP：让其他 agent 创建/消息/搜历史/查用量
- [adam91holt/grokbot-sdk](https://github.com/adam91holt/grokbot-sdk) - TypeScript SDK：网关客户端 + sand-data 磁盘读取
- [bcharleson/grokbot-for-gtm](https://github.com/bcharleson/grokbot-for-gtm) - 出站 GTM 剧本与技能（Instantly / HeyReach 等）
- [lschwartz-hue/grokbot-gtm-agent-system](https://github.com/lschwartz-hue/grokbot-gtm-agent-system) - GTM 小队起步包：Task→Skill→Routine 晋升梯子
- [Lotus015/grokbot-telegram](https://github.com/Lotus015/grokbot-telegram) - Telegram Bot API + 用户账号双 MCP 插件
- [jeffhuber/linq-grokbot-text-channel](https://github.com/jeffhuber/linq-grokbot-text-channel) - Linq 短信 ↔ Grok Bot webhook 转发器
- [shrdgn/grokbot-skills](https://github.com/shrdgn/grokbot-skills) - 按类整理的可运行 SKILL.md 合集
- [SigiBaes/grok-bot-starter-pack](https://github.com/SigiBaes/grok-bot-starter-pack) - 可粘贴单职人设：线索回复 / 收件箱 / 找钱 / 内容侦察（默认只出草稿）
- [jcpsimmons/gbdl](https://github.com/jcpsimmons/gbdl) - GrokBot Definition Language：一文件 YAML-in-Markdown 保存多 Bot 编排
- [CitiZenSleuthX/ticker-wire-skill](https://github.com/CitiZenSleuthX/ticker-wire-skill) - Ticker Wire 股票新闻盯盘 Skill（`npx skills add`）
- [zhast/big-numbers-plugin](https://github.com/zhast/big-numbers-plugin) - Big Numbers 只读账户/流水 MCP 插件（OAuth，不转账）
- [Agensi Grok Skills Marketplace](https://www.agensi.io/grok-marketplace) - SKILL.md 浏览与安装
- [OnlyTerp/opengrok](https://github.com/OnlyTerp/opengrok) - 给现有 Grok Bot 换模型：证据化 wire map、LiquidGlass 观测台、云主机补丁
- [GriffMurder/taskbullet-cursor-plugin](https://github.com/GriffMurder/taskbullet-cursor-plugin) - TaskBullet Agent MCP：把未完成工作委派给人肉 VA
- [Firecrawl: Best Grok plugins](https://www.firecrawl.dev/blog/best-grok-plugins) - 插件 vs MCP 对比速览

## 评测对比

- [Grok Bot vs Hermes vs OpenClaw](https://vismountain.com/grok-bot-vs-hermes-agent-vs-openclaw/) - 托管云电脑 / 自托管 / 多通道选型
- [Alex Finn: Did Grok Bot Just Kill Hermes and OpenClaw?](https://moderncreator.app/2026-08-11-alex-finn-did-grok-bot-just-kill-hermes-and-openclaw) - 零配置 vs 开源一周实测
- [The New Stack: Security boundaries](https://thenewstack.io/ai-agent-security-boundaries/) - 账号级 vs 沙箱级边界
- [Vellum: Official Grok Bot breakdown](https://www.vellum.ai/blog/official-grok-bot-breakdown) - 定价、安全与替代品视角
- [4Geeks: cost and credential risks](https://4geeks.com/en/blog/ai-tools/what-is-grok-bot) - 共享电脑≠安全边界；Auto-review 仅尽力而为
- [9to5Mac: iPad + cheaper plan access](https://9to5mac.com/2026/09/04/spacexai-expands-grok-bot-to-ipad-as-access-expands-to-cheaper-plans/) - iPad/Android 与更低价套餐覆盖报道
- [RuntimeWire: server-synced memory scoop](https://runtimewire.com/article/grok-bot-is-building-server-synced-memory-for-its-ai-coworkers) - 扒包：服务端按 Bot 同步记忆接口已出现
- [Continuum: Grok Bot pricing](https://continuumcode.ai/guides/grok-bot-pricing/) - 套餐路径与未公开周额度/超额计价拆解
- [Continuum: Grok Bot review](https://continuumcode.ai/guides/grok-bot-review/) - Beta 实测：上手顺、共享电脑与无 dry-run 等结构性取舍
- [Continuum: security and compliance](https://continuumcode.ai/guides/grok-bot-security-compliance/) - 账号级共享电脑信任模型与合规缺口清单
- [Continuum: Grok Bot alternatives](https://continuumcode.ai/guides/grok-bot-alternatives/) - 托管云 / 自托管 / 本机工作台等八类对照

## 开源替代

- [OpenClaw](https://github.com/openclaw/openclaw) - 自托管多通道 agent 网关（[文档](https://docs.openclaw.ai)）
- [Hermes Agent](https://hermes-agent.nousresearch.com) - 自托管持久助手：记忆与自写技能
- [elie222/rakazo](https://github.com/elie222/rakazo) - 开源常驻队友平台：自带模型与沙箱，Web/桌面/移动
- [Blackman99/openbot](https://github.com/Blackman99/openbot) - 开源、模型无关的 Grok Bot 式多 LLM 编排
- [agent-plugins-spec](https://github.com/agentplugins/agent-plugins-spec) - 开放 Agent Plugins 规范
- [codeaashu/grokbot-shim](https://github.com/codeaashu/grokbot-shim) - 本地跑 Grok Bot UI：自带桌面 + 可换 Codex/OpenAI 兼容模型
- [HxHippy/grok-bot-arch](https://github.com/HxHippy/grok-bot-arch) - Arch 上从 Cursor 签名 apt 源安装官方 .deb
- [addidotlol/grok-rpm](https://github.com/addidotlol/grok-rpm) - 官方 .deb 转 RPM 的非官方 Fedora/RHEL dnf 源
- [nescafe2009/dsh-grokbot](https://github.com/nescafe2009/dsh-grokbot) - DeepSeek Harness 插件：Grok Bot 式命名团队与审批卡
- [abhaysudhir/ungrok](https://github.com/abhaysudhir/ungrok) - 可回滚 host 改装：把推理路由到自有 OpenAI 兼容端点
- [egorpol/grok-bot-appimage-updater](https://github.com/egorpol/grok-bot-appimage-updater) - 非官方：安装/更新官方 Linux AppImage（桌面集成与回滚）
- [Jabbslad/grok-bot-bin](https://github.com/Jabbslad/grok-bot-bin) - 非官方 Arch 包：把上游 .deb 打成 `.pkg.tar.zst`
- [CodeUpdaterBot/Hermes-Mobile-App](https://github.com/CodeUpdaterBot/Hermes-Mobile-App) - 开源 Hermes 手机端控制面（Tailscale 连本机宿主机）
- [mahojo99/autobase](https://github.com/mahojo99/autobase) - Grok Bot 启发的桌面编排：自带 Codex/Claude 订阅跑多 Bot

## 社区

- [Cursor Forum tag: grok-bot](https://forum.cursor.com/tag/grok-bot) - 官方论坛标签流
- [Learn Cursor: Security & privacy](https://www.learncursor.dev/learn/cursor-agents/grok-bot-security-privacy) - 共享电脑边界与审批注意点
- [Can't reach your computer（代理/TUN）](https://forum.cursor.com/t/grok-bot-windows-fresh-profile-setup-fails-with-can-t-reach-your-computer-after-backend-fix/170281) - Windows 直连绕过系统代理时改用 TUN
- [Bots vanished / backend outage（勿乱 Reset）](https://forum.cursor.com/t/grok-bot-all-bots-disappeared-after-alt-tab-during-setup-nothing-recovers-them/170971) - 2026-09-07～08 服务端故障：空名册时先别 Reset/Recover，等官方恢复

## 相关列表

- [RongleCat/awesome-grok-bot](https://github.com/RongleCat/awesome-grok-bot) - 铁柱 AGI 维护的双语精选（灵感来源）
- [ZeroPointRepo/awesome-grok-bot](https://github.com/ZeroPointRepo/awesome-grok-bot) - 上线初期目录
- [ZeroPointRepo/GrokBotDev](https://github.com/ZeroPointRepo/GrokBotDev) - 开放目录站点 grokbot.dev（PR 即写入）
- [UseGrokBot](https://usegrokbot.com) - 按身份/团队模板发现用例，约每 6 小时刷新
- [rdmgator12/awesome-grok-bot-plugins](https://github.com/rdmgator12/awesome-grok-bot-plugins) - 应用内插件快照列表
- [lroolle/awesome-grokbot-templates](https://github.com/lroolle/awesome-grokbot-templates) - 公开 Bot 模板分享链接合集
- [kydlikebtc/awesome-grokbot](https://github.com/kydlikebtc/awesome-grokbot) - 六百余条 x.ai/bot 分享目录（双语 + 站点）
- [majiayu000/awesome-grok-bot](https://github.com/majiayu000/awesome-grok-bot) - 公开 Bot 分享索引与核验标记
- [DominikTobureto/awesome-grok-build](https://github.com/DominikTobureto/awesome-grok-build) - Grok Build 技能 awesome
- [Anil-matcha/awesome-grok-bot](https://github.com/Anil-matcha/awesome-grok-bot) - 可粘贴 Bot 模板（生产力/销售/营销等）与创作者标注

## 贡献

见 [CONTRIBUTING.md](./CONTRIBUTING.md)。过期链接由仓库管理员自动清理。

---

维护者：Grok Bot「仓库管理员」· 首次播种：2026-09-06
