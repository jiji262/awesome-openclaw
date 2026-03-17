# Awesome OpenClaw

简体中文 | [English](README.md)

> 持续整理的 OpenClaw 生态地图：官方仓库、旧名谱系项目、自托管部署路径、
> 管理面板、消息渠道集成、记忆系统、安全工具，以及明确支持 OpenClaw 的
> 开源项目。

更新于 `2026-03-17`。

OpenClaw 这条产品线已经经历过多次命名演进：
`OpenClaw -> Moltbot -> Clawdbot`。这个列表不会只盯着最新名字，而是尽量把
整条谱系里仍然有价值的项目保留下来。

## 这个列表收什么

- OpenClaw 官方和一方生态仓库
- 社区维护的安装器、客户端、控制台、渠道插件
- 仍然有参考价值的 `Clawdbot / Moltbot` 老项目
- 明确写着支持 OpenClaw 的开源工具
- OpenClaw 用户真实会拿来对比的相邻替代方案

## 这个列表不打算做什么

- 不做“搜到 `openclaw` 就全收录”的仓库大杂烩
- 不收明显空壳、测试、个人工作区仓库
- 不收只是顺带提到 OpenClaw 的泛 AI 工具

## 收录原则

1. 仓库必须和 OpenClaw、Clawdbot、Moltbot 有明确关系。
2. 名称、描述、topics 或 README 内容必须能支撑这个关系。
3. 活跃度和 star 只帮助排序，不单独决定是否收录。
4. 跨工具项目只有在明确支持 OpenClaw 时才会进入主列表。

## 快速导航

- 想先看官方真相源？从 [官方生态](#官方生态) 开始。
- 想自托管、打包、部署、加固？看 [安装、部署与运维](#安装部署与运维)。
- 想找 GUI、面板、桌面端或 Web 客户端？看 [客户端、面板与 UI](#客户端面板与-ui)。
- 想接飞书、微信、钉钉、Slack、短信一类渠道？看 [渠道与集成](#渠道与集成)。
- 想找技能、记忆、路由、可复用底座？看 [扩展与基础构件](#扩展与基础构件)。
- 想先看教程、书、awesome 列表？看 [学习资源](#学习资源)。

## 分类索引

- [最近新增](#最近新增)
- [官方生态](#官方生态)
- [安装、部署与运维](#安装部署与运维)
- [客户端、面板与 UI](#客户端面板与-ui)
- [渠道与集成](#渠道与集成)
- [扩展与基础构件](#扩展与基础构件)
- [学习资源](#学习资源)
- [替代方案](#替代方案)
- [贡献方式](#贡献方式)

## 最近新增

- [openclaw/openclaw-windows-node](https://github.com/openclaw/openclaw-windows-node) - 官方 Windows 伴随套件，覆盖托盘应用与 PowerToys 命令面板。
- [xmanrui/OpenClaw-bot-review](https://github.com/xmanrui/OpenClaw-bot-review) - 面向 Bot、模型、会话、网关状态的高信号仪表盘。
- [yuga-hashimoto/openclaw-assistant](https://github.com/yuga-hashimoto/openclaw-assistant) - 专为 OpenClaw 打造的 Android 自托管语音助手。
- [centminmod/explain-openclaw](https://github.com/centminmod/explain-openclaw) - 覆盖入门、架构、部署、安全的综合说明文档。
- [jgamblin/OpenClawCVEs](https://github.com/jgamblin/OpenClawCVEs) - 自动追踪 OpenClaw 安全公告与 CVE 的仓库。
- [markus-lassfolk/openclaw-hybrid-memory](https://github.com/markus-lassfolk/openclaw-hybrid-memory) - 带结构化召回与搜索能力的持久化混合记忆扩展。

## 官方生态

- [openclaw/openclaw](https://github.com/openclaw/openclaw) - OpenClaw 核心仓库。
- [openclaw/openclaw.ai](https://github.com/openclaw/openclaw.ai) - 官方网站源码。
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - 官方技能目录后端。
- [openclaw/skills](https://github.com/openclaw/skills) - 历史技能版本归档。
- [openclaw/nix-openclaw](https://github.com/openclaw/nix-openclaw) - Nix 打包方案。
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - Homebrew 分发渠道。
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - 偏运维和加固的 Ansible 安装路径。
- [openclaw/lobster](https://github.com/openclaw/lobster) - 面向 OpenClaw 自动化的工作流 shell。
- [openclaw/acpx](https://github.com/openclaw/acpx) - ACP 会话的无头 CLI。
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - OpenClaw 环境的基础设施和主机模块。
- [openclaw/casa](https://github.com/openclaw/casa) - 官方组织下的 home base 暴露项目，服务于 Clawdbot 谱系。
- [openclaw/openclaw-windows-node](https://github.com/openclaw/openclaw-windows-node) - 官方 Windows 托盘应用、共享网关库与 PowerToys 命令面板扩展。
- [openclaw/clawgo](https://github.com/openclaw/clawgo) - 面向 Raspberry Pi 与 Linux 语音事件流的官方极简 Go 节点。
- [openclaw/multipass](https://github.com/openclaw/multipass) - 用于稳定测试 OpenClaw 消息渠道的官方 CLI。
- [openclaw/trust](https://github.com/openclaw/trust) - OpenClaw 官方威胁模型与安全项目信息。
- [openclaw/caclawphony](https://github.com/openclaw/caclawphony) - OpenClaw 官方维护者使用的 PR 分诊、评审、合并自动化流水线。
- [openclaw/community](https://github.com/openclaw/community) - 官方社区规范和文档。

## 安装、部署与运维

### 部署与打包

- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - 一键安装器。
- [phioranex/openclaw-docker](https://github.com/phioranex/openclaw-docker) - 预构建 Docker 镜像和安装脚本。
- [CrocSwap/clawdbot-docker](https://github.com/CrocSwap/clawdbot-docker) - 更强调容器隔离的 Clawdbot 运行封装。
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - 基于 Cloudflare Workers 的运行路径。
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - 适合 Coolify 类环境的 Docker 打包。
- [feiskyer/openclaw-kubernetes](https://github.com/feiskyer/openclaw-kubernetes) - 面向 Moltbot 和 Clawdbot 老谱系的 Helm 与 Kubernetes 部署路径。
- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - 明确支持 OpenClaw 部署的热门自托管面板。
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - Coolify 模板。
- [joshavant/clawbox](https://github.com/joshavant/clawbox) - 预置好的 macOS VM。
- [androidmalware/OpenClaw_Termux](https://github.com/androidmalware/OpenClaw_Termux) - Android 加 Termux 安装路径。
- [mithun50/openclaw-termux](https://github.com/mithun50/openclaw-termux) - Android App 与 Termux 双路径方案。
- [AidanPark/openclaw-android](https://github.com/AidanPark/openclaw-android) - Android 同质化部署方案。
- [rohanarun/phoneclaw](https://github.com/rohanarun/phoneclaw) - 直接跑在 Android 手机上的 OpenClaw 风格自动化。
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - 面向手机运行环境的 OpenClaw 调整。
- [kentcdodds/flying-jarvis](https://github.com/kentcdodds/flying-jarvis) - Clawdbot 时代的 Fly.io 部署变体。
- [sebastianvkl/pizero-openclaw](https://github.com/sebastianvkl/pizero-openclaw) - Raspberry Pi Zero 部署路径。
- [anomixer/openclaw-setup](https://github.com/anomixer/openclaw-setup) - 持续更新的 OpenClaw 加 Ollama 安装指南，覆盖 Windows 原生与 WSL2。

### 安全、监控与备份

- [slowmist/openclaw-security-practice-guide](https://github.com/slowmist/openclaw-security-practice-guide) - 面向 OpenClaw 本体的安全实践指南。
- [LeoYeAI/openclaw-guardian](https://github.com/LeoYeAI/openclaw-guardian) - Watchdog 与自愈封装。
- [LeoYeAI/openclaw-backup](https://github.com/LeoYeAI/openclaw-backup) - 备份与恢复工具。
- [kappa9999/ClawShield](https://github.com/kappa9999/ClawShield) - 面向 OpenClaw 和 Moltbot 的安全预检与护栏。
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) - 面向 OpenClaw 和 NanoClaw 的安全技能套件。
- [backslash-security/Claw-Hunter](https://github.com/backslash-security/Claw-Hunter) - 终端设备层面的检测与审计脚本。
- [JaydenBeard/clawguard](https://github.com/JaydenBeard/clawguard) - 带 kill switch 思路的监控面板。
- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - 面向 Clawdbot 部署的实时成本与 token 可视化。
- [TheSethRose/Clawdbot-Security-Check](https://github.com/TheSethRose/Clawdbot-Security-Check) - 面向自查的安全知识技能。
- [vignesh07/clawdbot-formal-models](https://github.com/vignesh07/clawdbot-formal-models) - Clawdbot 谱系的形式化安全建模仓库。
- [jgamblin/OpenClawCVEs](https://github.com/jgamblin/OpenClawCVEs) - 按小时更新的 OpenClaw 安全公告、CVE 与发布状态追踪器。
- [merciagents/riphook](https://github.com/merciagents/riphook) - 可用于 OpenClaw 工作流的确定性安全层。

## 客户端、面板与 UI

- [abhi1693/openclaw-mission-control](https://github.com/abhi1693/openclaw-mission-control) - OpenClaw 任务总控面板。
- [Temaki-AI/clawd-control](https://github.com/Temaki-AI/clawd-control) - 面向 Clawdbot 和 OpenClaw 机群的实时控制台。
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - 干净的 Web 运维界面。
- [mudrii/openclaw-dashboard](https://github.com/mudrii/openclaw-dashboard) - 轻量命令中心。
- [qingchencloud/clawpanel](https://github.com/qingchencloud/clawpanel) - 可视化管理面板，强调安装、诊断、修复。
- [miaoxworld/openclaw-manager](https://github.com/miaoxworld/openclaw-manager) - 基于 Tauri 的桌面管理器。
- [Peiiii/openclaw-manager](https://github.com/Peiiii/openclaw-manager) - GUI 化的 OpenClaw 安装与配置工具。
- [ValueCell-ai/ClawX](https://github.com/ValueCell-ai/ClawX) - OpenClaw 图形界面桌面客户端。
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - OpenClaw Web 客户端。
- [xmanrui/OpenClaw-bot-review](https://github.com/xmanrui/OpenClaw-bot-review) - 面向 Bot、Agent、模型、会话与 token 用量的本地仪表盘。
- [yuga-hashimoto/openclaw-assistant](https://github.com/yuga-hashimoto/openclaw-assistant) - 带唤醒词、系统集成与 Wear OS 支持的 Android 语音助手。
- [xigpz/openclaw-console](https://github.com/xigpz/openclaw-console) - Rust 加 React 的可视化后台，覆盖模型、Skills 与网关配置。
- [magimetal/moltbot-menubar](https://github.com/magimetal/moltbot-menubar) - macOS 菜单栏里的启动、停止、重启控制器。
- [leveragedrobot/raycast-moltbot](https://github.com/leveragedrobot/raycast-moltbot) - 面向 Raycast 的 Moltbot 快捷启动扩展。
- [askmojo/moltcraft](https://github.com/askmojo/moltcraft) - 等距像素风 Moltbot 可视化面板。
- [Curbob/LobsterBoard](https://github.com/Curbob/LobsterBoard) - 可搭配 OpenClaw 的自托管看板构建器。
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - 面向 Moltbot 工作流的 chat-to-task 看板控制台。
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - OpenClaw 代理实时伴随监控面板。
- [gbessoni/molteye](https://github.com/gbessoni/molteye) - 观察 Moltbot、Claude、Cursor 等桌面 Agent 行为的可观测工具。
- [WW-AI-Lab/openclaw-office](https://github.com/WW-AI-Lab/openclaw-office) - 数字办公室风格的多 Agent 可视化界面。
- [ringhyacinth/Star-Office-UI](https://github.com/ringhyacinth/Star-Office-UI) - 像素风 OpenClaw 工作空间。

## 渠道与集成

- [BytePioneer-AI/openclaw-china](https://github.com/BytePioneer-AI/openclaw-china) - 中国 IM 平台整合包。
- [AlexAnys/openclaw-feishu](https://github.com/AlexAnys/openclaw-feishu) - 飞书和 Lark 使用与排障指南。
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - 强调免公网服务的飞书桥接方案。
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - 高信号飞书渠道插件。
- [DingTalk-Real-AI/dingtalk-openclaw-connector](https://github.com/DingTalk-Real-AI/dingtalk-openclaw-connector) - 支持流式卡片的钉钉连接器。
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - 老谱系下的钉钉频道插件。
- [freestylefly/openclaw-wechat](https://github.com/freestylefly/openclaw-wechat) - 个人微信桥接方案。
- [dingxiang-me/OpenClaw-Wechat](https://github.com/dingxiang-me/OpenClaw-Wechat) - 微信和企微联通方案，控制面更丰富。
- [sunnoy/openclaw-plugin-wecom](https://github.com/sunnoy/openclaw-plugin-wecom) - 企业微信插件。
- [toboto/openclaw-wecom-channel](https://github.com/toboto/openclaw-wecom-channel) - 适配新版 Plugin SDK 的企微渠道插件。
- [constansino/openclaw_qq](https://github.com/constansino/openclaw_qq) - QQ 扩展。
- [danbao/openclaw-ringcentral](https://github.com/danbao/openclaw-ringcentral) - RingCentral Team Messaging 渠道插件。
- [tornado1014/clawdbot-kakaotalk](https://github.com/tornado1014/clawdbot-kakaotalk) - KakaoTalk 渠道集成。
- [nickvasilescu/clawdbot-channel-linq](https://github.com/nickvasilescu/clawdbot-channel-linq) - iMessage、RCS、SMS 桥接。
- [kesslerio/phone-agent-moltbot-skill](https://github.com/kesslerio/phone-agent-moltbot-skill) - 用 Twilio、Deepgram、OpenAI、ElevenLabs 打通实时电话 Agent 的语音渠道扩展。
- [VizuaraAILabs/Slack-ClawdBot](https://github.com/VizuaraAILabs/Slack-ClawdBot) - 早期 ClawdBot Slack 集成。
- [oujingzhou/openmozi](https://github.com/oujingzhou/openmozi) - 支持飞书、钉钉、QQ、企微的轻量 OpenClaw 风格栈。

## 扩展与基础构件

### 记忆、上下文与知识系统

- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - 面向主动型代理的长期记忆引擎。
- [EverMind-AI/EverMemOS](https://github.com/EverMind-AI/EverMemOS) - 面向多平台 OpenClaw 代理的长期记忆层。
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - 明确支持 OpenClaw 的 Memory OS。
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - MemOS 云插件版。
- [win4r/memory-lancedb-pro](https://github.com/win4r/memory-lancedb-pro) - LanceDB 增强记忆后端。
- [volcengine/OpenViking](https://github.com/volcengine/OpenViking) - 面向 Agent 的上下文数据库。
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - 长期记忆扩展。
- [zilliztech/memsearch](https://github.com/zilliztech/memsearch) - 受 OpenClaw 工作流启发的 Markdown-first 记忆系统。
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - 也支持 OpenClaw 插件路径的长期记忆系统。
- [Dataojitori/nocturne_memory](https://github.com/Dataojitori/nocturne_memory) - 可回滚的结构化长期记忆服务。
- [rockywuest/bookend-skill](https://github.com/rockywuest/bookend-skill) - 面向 Clawdbot 和 Moltbot 的结构化记忆技能。
- [48Nauts-Operator/moltbot-memory-local](https://github.com/48Nauts-Operator/moltbot-memory-local) - SQLite 加本地 embedding 的隐私优先记忆插件。
- [markus-lassfolk/openclaw-hybrid-memory](https://github.com/markus-lassfolk/openclaw-hybrid-memory) - 集成 SQLite、向量召回、自动捕获与 TTL 衰减的混合记忆扩展。
- [astonysh/OpenClaw-DeepReeder](https://github.com/astonysh/OpenClaw-DeepReeder) - 面向网页和内容的知识导入工具。
- [ZeroPointRepo/youtube-skills](https://github.com/ZeroPointRepo/youtube-skills) - 适合 OpenClaw 做知识导入的 YouTube transcript 技能。

### 工具链与 OpenClaw 兼容生态

- [mnfst/manifest](https://github.com/mnfst/manifest) - OpenClaw 的路由与可观测性工具。
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - 面向 OpenClaw 的模型路由层。
- [refly-ai/refly](https://github.com/refly-ai/refly) - 明确覆盖 Clawdbot 与相关 agent 生态的开源技能构建器。
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - 面向 Clawdbot、Claude Code、Codex 的跨 agent 技能集合。
- [neonone123/moltdirectory](https://github.com/neonone123/moltdirectory) - Moltbot 技能、persona、logic 模块的开源目录站。
- [Nateliason/send-to-openclaw](https://github.com/Nateliason/send-to-openclaw) - 把网页内容经 webhook 直接送进 Clawdbot 的 Chrome 扩展。
- [VsevolodUstinov/openclaw-skill-claude-code](https://github.com/VsevolodUstinov/openclaw-skill-claude-code) - 在 OpenClaw 中跑 Claude Code 任务的技能。
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - 基于 MCP 把 Claude Code 接回 OpenClaw 的技能。
- [win4r/claude-code-clawdbot-skill](https://github.com/win4r/claude-code-clawdbot-skill) - 老谱系命名下的 Claude Code 技能。
- [rohunvora/x-research-skill](https://github.com/rohunvora/x-research-skill) - 支持 OpenClaw 的 X 和 Twitter 调研技能。
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - 带 OpenClaw 适配的 token 统计 CLI。
- [davepoon/buildwithclaude](https://github.com/davepoon/buildwithclaude) - 同时覆盖 OpenClaw 的跨生态技能和插件市场。
- [runkids/skillshare](https://github.com/runkids/skillshare) - 支持 OpenClaw 的跨工具技能同步。
- [farion1231/cc-switch](https://github.com/farion1231/cc-switch) - 支持 OpenClaw 的多 Agent 桌面启动器。
- [itshaungmu/AgentHub](https://github.com/itshaungmu/AgentHub) - 面向 OpenClaw 风格 Agent 的打包、发布、安装开源市场。
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - 明确兼容 OpenClaw 的 Cowork 壳层。
- [AstrBotDevs/AstrBot](https://github.com/AstrBotDevs/AstrBot) - 经常与 OpenClaw 对比的 IM Bot 平台。
- [langbot-app/LangBot](https://github.com/langbot-app/LangBot) - 覆盖多平台渠道的 Bot 平台，也显式提到 OpenClaw 谱系。
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - 标明可用于 OpenClaw 的代理层。

### 领域包与实验项目

- [FreedomIntelligence/OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) - 医疗场景技能库。
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - Home Assistant 路线。
- [rookiestar28/ComfyUI-OpenClaw](https://github.com/rookiestar28/ComfyUI-OpenClaw) - 受 OpenClaw 启发的内容生产工作流。
- [Gen-Verse/OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) - 强化学习实验方向。
- [calebwin/pgclaw](https://github.com/calebwin/pgclaw) - 用 Postgres SQL 复刻 Clawdbot 核心思路的实验项目。
- [Intent-Lab/VisionClaw](https://github.com/Intent-Lab/VisionClaw) - 语音加视觉伴侣层。
- [white0dew/XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills) - 支持 OpenClaw 的小红书技能集。
- [Xiangyu-CAS/xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill) - 面向 OpenClaw 的小红书运营技能。
- [voocel/openclaw-mini](https://github.com/voocel/openclaw-mini) - OpenClaw 核心思路的极简复现。

## 学习资源

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - 以真实用例为核心的高质量列表。
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - 目前最强的技能索引之一。
- [SamurAIGPT/awesome-openclaw](https://github.com/SamurAIGPT/awesome-openclaw) - 覆盖面较广的通用 awesome 列表。
- [vincentkoc/awesome-openclaw](https://github.com/vincentkoc/awesome-openclaw) - 多语言、多类别的 OpenClaw awesome 列表。
- [centminmod/explain-openclaw](https://github.com/centminmod/explain-openclaw) - 集成入门、技术架构、部署和安全资料的文档仓库。
- [xschen-beb/awesome-openclaw-projects](https://github.com/xschen-beb/awesome-openclaw-projects) - 用表格和指标组织的 OpenClaw 生态索引。
- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - OpenClaw、Clawdbot、Moltbot 三套命名合流的中文化发行版与教程包。
- [L-LesterYu/OpenClaw-hot-skills-zh](https://github.com/L-LesterYu/OpenClaw-hot-skills-zh) - 对 ClawHub 热门技能做中文翻译和使用说明的仓库。
- [AlexAnys/awesome-openclaw-usecases-zh](https://github.com/AlexAnys/awesome-openclaw-usecases-zh) - 中文用例大全，偏本地化场景。
- [clawdbot-ai/awesome-openclaw-skills-zh](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) - 中文技能索引。
- [xianyu110/awesome-openclaw-tutorial](https://github.com/xianyu110/awesome-openclaw-tutorial) - 中文教程聚合。
- [mengjian-github/openclaw101](https://github.com/mengjian-github/openclaw101) - 新手友好的学习入口。
- [0xtresser/OpenClaw-Book](https://github.com/0xtresser/OpenClaw-Book) - 书籍式入门资料。
- [yeuxuan/openclaw-docs](https://github.com/yeuxuan/openclaw-docs) - 中文文档站和源码剖析。
- [xianyu110/clawbot](https://github.com/xianyu110/clawbot) - Clawdbot 谱系的安装与中转指南。
- [shareAI-lab/claw0](https://github.com/shareAI-lab/claw0) - 从 0 到 1 学 OpenClaw。
- [buainoai/awesome-clawdbot-skills](https://github.com/buainoai/awesome-clawdbot-skills) - 老命名体系下的技能精选。
- [EvoLinkAI/awesome-openclaw-usecases-moltbook](https://github.com/EvoLinkAI/awesome-openclaw-usecases-moltbook) - 与 Moltbook 社区联动的用例集合。

## 替代方案

这些项目值得关注，但不属于 OpenClaw 官方核心生态。

- [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) - 偏安全与容器化的替代方案。
- [nearai/ironclaw](https://github.com/nearai/ironclaw) - 强调隐私和安全的 Rust 重写版本。
- [zeroclaw-labs/zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) - Rust 路线的自治助手基础设施。
- [smallnest/goclaw](https://github.com/smallnest/goclaw) - Go 版 OpenClaw 风格框架。
- [alibaba/hiclaw](https://github.com/alibaba/hiclaw) - 偏团队协作的 Agent 系统。
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - 更轻量的 OpenClaw 风格助手。
- [memovai/mimiclaw](https://github.com/memovai/mimiclaw) - 偏硬件路线的 OpenClaw 灵感系统。
- [ComposioHQ/secure-openclaw](https://github.com/ComposioHQ/secure-openclaw) - 安全导向的 fork 或变体。
- [poco-ai/poco-agent](https://github.com/poco-ai/poco-agent) - 更强调 UI 和沙箱运行时的替代方案。
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - 打安全与稳定牌的 Rust 替代系统。
- [getclawe/clawe](https://github.com/getclawe/clawe) - 更偏协作编排层的替代思路。

## 贡献方式

欢迎 PR，但请优先保证信噪比。

建议提交的项目应该：

- 和 OpenClaw、Moltbot、Clawdbot 有明确关系
- 仍在维护，或即便不活跃也具有谱系解释价值
- 比现有重复项更强
- 对构建者、运维者或重度用户有实际帮助

建议不要提交：

- 0 信息量的个人测试仓库
- 仅顺带提到 OpenClaw 的泛 AI 工具
- 纯 exploit 仓库
