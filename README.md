# Awesome OpenClaw

[简体中文](README.zh-CN.md) | English

> A curated map of the OpenClaw ecosystem: official repos, legacy-name
> projects, self-hosting paths, dashboards, messaging integrations, memory
> systems, security tooling, and OpenClaw-compatible open source projects.

Reviewed on `2026-03-09`.

OpenClaw has already lived through multiple names and overlapping communities:
`OpenClaw -> Moltbot -> Clawdbot`. This list keeps useful repositories from
that full lineage instead of pretending only the latest name matters.

## What this list covers

- first-party OpenClaw repositories
- community-maintained installers, dashboards, clients, and connectors
- legacy-name projects that are still useful today
- OpenClaw-compatible open source tooling with explicit support
- adjacent alternatives that OpenClaw users will realistically compare against

## What this list does not try to be

- a complete dump of every GitHub repository containing `openclaw`
- a collection of empty placeholders, personal workspaces, or obvious test repos
- a generic AI tools directory where OpenClaw is only a passing mention

## Selection principles

1. A repository must be clearly relevant to OpenClaw, Clawdbot, or Moltbot.
2. Names, descriptions, topics, or README content must justify inclusion.
3. Activity and star count help ranking, but they are not the only rule.
4. Cross-tool projects belong here only if they explicitly support OpenClaw.

## Quick start

- Want the official source of truth? Start with [Official Ecosystem](#official-ecosystem).
- Want to self-host, package, or harden a deployment? Go to [Install, Deploy & Operate](#install-deploy--operate).
- Want a GUI, dashboard, or desktop/web client? Jump to [Clients, Dashboards & UI](#clients-dashboards--ui).
- Want Feishu, WeChat, DingTalk, Slack, or SMS-style channels? See [Channels & Integrations](#channels--integrations).
- Want skills, memory, routing, or reusable building blocks? Read [Extensions & Building Blocks](#extensions--building-blocks).
- Want books, tutorials, and awesome lists first? Go to [Learning Resources](#learning-resources).

## Category index

- [Official Ecosystem](#official-ecosystem)
- [Install, Deploy & Operate](#install-deploy--operate)
- [Clients, Dashboards & UI](#clients-dashboards--ui)
- [Channels & Integrations](#channels--integrations)
- [Extensions & Building Blocks](#extensions--building-blocks)
- [Learning Resources](#learning-resources)
- [Adjacent Alternatives](#adjacent-alternatives)
- [Contributing](#contributing)

## Official Ecosystem

- [openclaw/openclaw](https://github.com/openclaw/openclaw) - Core OpenClaw repository.
- [openclaw/openclaw.ai](https://github.com/openclaw/openclaw.ai) - Source for the official website.
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill directory backend.
- [openclaw/skills](https://github.com/openclaw/skills) - Archive of published skill versions.
- [openclaw/nix-openclaw](https://github.com/openclaw/nix-openclaw) - Nix packaging for OpenClaw.
- [openclaw/homebrew-tap](https://github.com/openclaw/homebrew-tap) - Homebrew distribution channel.
- [openclaw/openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Hardened Ansible install path.
- [openclaw/lobster](https://github.com/openclaw/lobster) - Workflow shell for OpenClaw-native automations.
- [openclaw/acpx](https://github.com/openclaw/acpx) - Headless CLI for ACP sessions.
- [openclaw/clawdinators](https://github.com/openclaw/clawdinators) - Infra and host modules for OpenClaw environments.
- [openclaw/casa](https://github.com/openclaw/casa) - Official home-base exposure project for the Clawdbot lineage.
- [openclaw/community](https://github.com/openclaw/community) - Official community policies and server docs.

## Install, Deploy & Operate

### Deployment and packaging

- [miaoxworld/OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - One-click installer.
- [phioranex/openclaw-docker](https://github.com/phioranex/openclaw-docker) - Pre-built Docker image and install scripts.
- [CrocSwap/clawdbot-docker](https://github.com/CrocSwap/clawdbot-docker) - Container-isolated Clawdbot runtime harness.
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) - Cloudflare Workers deployment path.
- [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - Docker packaging for Coolify-style environments.
- [feiskyer/openclaw-kubernetes](https://github.com/feiskyer/openclaw-kubernetes) - Helm chart and Kubernetes deployment path for the former Moltbot and Clawdbot lineage.
- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - Popular self-hosted panel with explicit OpenClaw deployment support.
- [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - Coolify template for OpenClaw.
- [joshavant/clawbox](https://github.com/joshavant/clawbox) - OpenClaw-ready macOS VMs.
- [androidmalware/OpenClaw_Termux](https://github.com/androidmalware/OpenClaw_Termux) - Android plus Termux installation route.
- [mithun50/openclaw-termux](https://github.com/mithun50/openclaw-termux) - Android app and Termux package route.
- [AidanPark/openclaw-android](https://github.com/AidanPark/openclaw-android) - Android homelab deployment with one-command setup.
- [rohanarun/phoneclaw](https://github.com/rohanarun/phoneclaw) - Run OpenClaw-style automation directly on Android phones.
- [marshallrichards/ClawPhone](https://github.com/marshallrichards/ClawPhone) - Smartphone-focused tweaks for OpenClaw.
- [kentcdodds/flying-jarvis](https://github.com/kentcdodds/flying-jarvis) - Fly.io deployment variant from the Clawdbot era.
- [sebastianvkl/pizero-openclaw](https://github.com/sebastianvkl/pizero-openclaw) - Raspberry Pi Zero deployment path.

### Security, monitoring, and backup

- [slowmist/openclaw-security-practice-guide](https://github.com/slowmist/openclaw-security-practice-guide) - Security hardening guide for OpenClaw itself.
- [LeoYeAI/openclaw-guardian](https://github.com/LeoYeAI/openclaw-guardian) - Watchdog and self-healing wrapper.
- [LeoYeAI/openclaw-backup](https://github.com/LeoYeAI/openclaw-backup) - Backup and restore tooling.
- [kappa9999/ClawShield](https://github.com/kappa9999/ClawShield) - Security preflight and guardrails for OpenClaw and Moltbot.
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) - Security skill suite for OpenClaw and NanoClaw agents.
- [backslash-security/Claw-Hunter](https://github.com/backslash-security/Claw-Hunter) - Device-level detection and monitoring scripts.
- [JaydenBeard/clawguard](https://github.com/JaydenBeard/clawguard) - Monitoring and kill-switch style dashboard.
- [bokonon23/clawdbot-cost-monitor](https://github.com/bokonon23/clawdbot-cost-monitor) - Real-time usage and cost visibility for Clawdbot deployments.
- [TheSethRose/Clawdbot-Security-Check](https://github.com/TheSethRose/Clawdbot-Security-Check) - Self-audit security knowledge skill.
- [vignesh07/clawdbot-formal-models](https://github.com/vignesh07/clawdbot-formal-models) - Formal security modeling for the Clawdbot lineage.
- [merciagents/riphook](https://github.com/merciagents/riphook) - Deterministic security layer compatible with OpenClaw workflows.

## Clients, Dashboards & UI

- [abhi1693/openclaw-mission-control](https://github.com/abhi1693/openclaw-mission-control) - OpenClaw mission-control dashboard.
- [Temaki-AI/clawd-control](https://github.com/Temaki-AI/clawd-control) - Fleet dashboard for Clawdbot and OpenClaw agents.
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) - Clean web operator console.
- [mudrii/openclaw-dashboard](https://github.com/mudrii/openclaw-dashboard) - Lightweight command center.
- [qingchencloud/clawpanel](https://github.com/qingchencloud/clawpanel) - Visual management panel with built-in assistant workflows.
- [miaoxworld/openclaw-manager](https://github.com/miaoxworld/openclaw-manager) - Tauri desktop manager for OpenClaw.
- [Peiiii/openclaw-manager](https://github.com/Peiiii/openclaw-manager) - GUI-based installation and configuration tool for OpenClaw.
- [ValueCell-ai/ClawX](https://github.com/ValueCell-ai/ClawX) - Desktop GUI for OpenClaw agents.
- [ibelick/webclaw](https://github.com/ibelick/webclaw) - Fast web client for OpenClaw.
- [magimetal/moltbot-menubar](https://github.com/magimetal/moltbot-menubar) - macOS menu bar controller for launch, stop, and restart.
- [leveragedrobot/raycast-moltbot](https://github.com/leveragedrobot/raycast-moltbot) - Raycast launcher extension for the legacy lineage.
- [askmojo/moltcraft](https://github.com/askmojo/moltcraft) - Isometric pixel-art dashboard for Moltbot-style agents.
- [Curbob/LobsterBoard](https://github.com/Curbob/LobsterBoard) - Self-hosted dashboard builder with OpenClaw-aware widgets.
- [rdsthomas/mission-control](https://github.com/rdsthomas/mission-control) - Kanban-style chat-to-task control surface for Moltbot workflows.
- [luccast/crabwalk](https://github.com/luccast/crabwalk) - Real-time companion monitor for OpenClaw agents.
- [gbessoni/molteye](https://github.com/gbessoni/molteye) - Desktop observability for Moltbot, Claude, Cursor, and related agents.
- [WW-AI-Lab/openclaw-office](https://github.com/WW-AI-Lab/openclaw-office) - Digital office metaphor for multi-agent visualization.
- [ringhyacinth/Star-Office-UI](https://github.com/ringhyacinth/Star-Office-UI) - Pixel-style visual workspace for OpenClaw teams.

## Channels & Integrations

- [BytePioneer-AI/openclaw-china](https://github.com/BytePioneer-AI/openclaw-china) - Bundle of China-focused OpenClaw integrations.
- [AlexAnys/openclaw-feishu](https://github.com/AlexAnys/openclaw-feishu) - Feishu and Lark guide and support repo.
- [AlexAnys/feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) - Feishu and Lark bridge with a no-public-server path.
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) - High-signal Feishu channel plugin.
- [DingTalk-Real-AI/dingtalk-openclaw-connector](https://github.com/DingTalk-Real-AI/dingtalk-openclaw-connector) - DingTalk connector with streaming cards.
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - DingTalk channel plugin for the legacy lineage.
- [freestylefly/openclaw-wechat](https://github.com/freestylefly/openclaw-wechat) - Community bridge for personal WeChat.
- [dingxiang-me/OpenClaw-Wechat](https://github.com/dingxiang-me/OpenClaw-Wechat) - WeChat and WeCom connector with richer controls.
- [sunnoy/openclaw-plugin-wecom](https://github.com/sunnoy/openclaw-plugin-wecom) - Enterprise WeChat plugin.
- [toboto/openclaw-wecom-channel](https://github.com/toboto/openclaw-wecom-channel) - WeCom plugin updated for the latest Plugin SDK compatibility.
- [constansino/openclaw_qq](https://github.com/constansino/openclaw_qq) - Standalone QQ extension.
- [danbao/openclaw-ringcentral](https://github.com/danbao/openclaw-ringcentral) - RingCentral Team Messaging channel plugin for the legacy lineage.
- [tornado1014/clawdbot-kakaotalk](https://github.com/tornado1014/clawdbot-kakaotalk) - KakaoTalk channel integration.
- [nickvasilescu/clawdbot-channel-linq](https://github.com/nickvasilescu/clawdbot-channel-linq) - iMessage, RCS, and SMS bridge.
- [kesslerio/phone-agent-moltbot-skill](https://github.com/kesslerio/phone-agent-moltbot-skill) - Voice and phone channel integration with Twilio, Deepgram, OpenAI, and ElevenLabs.
- [VizuaraAILabs/Slack-ClawdBot](https://github.com/VizuaraAILabs/Slack-ClawdBot) - Slack integration from the early ClawdBot era.
- [oujingzhou/openmozi](https://github.com/oujingzhou/openmozi) - Lightweight OpenClaw-style stack with Feishu, DingTalk, QQ, and WeCom support.

## Extensions & Building Blocks

### Memory, context, and knowledge systems

- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Long-term memory engine for proactive agents.
- [EverMind-AI/EverMemOS](https://github.com/EverMind-AI/EverMemOS) - Long-term memory layer for OpenClaw agents across platforms.
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - Memory OS with explicit OpenClaw support.
- [MemTensor/MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) - Cloud memory plugin for OpenClaw.
- [win4r/memory-lancedb-pro](https://github.com/win4r/memory-lancedb-pro) - Enhanced LanceDB memory backend.
- [volcengine/OpenViking](https://github.com/volcengine/OpenViking) - Context database for OpenClaw-style agents.
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - Long-term memory extension.
- [zilliztech/memsearch](https://github.com/zilliztech/memsearch) - Markdown-first memory system inspired by OpenClaw workflows.
- [oceanbase/powermem](https://github.com/oceanbase/powermem) - Long-term memory system that also supports the OpenClaw plugin path.
- [Dataojitori/nocturne_memory](https://github.com/Dataojitori/nocturne_memory) - Rollbackable, structured memory server positioned as an OpenClaw replacement layer.
- [rockywuest/bookend-skill](https://github.com/rockywuest/bookend-skill) - Structured memory skill for retaining long-running Clawdbot context.
- [48Nauts-Operator/moltbot-memory-local](https://github.com/48Nauts-Operator/moltbot-memory-local) - Privacy-first local memory plugin with SQLite and local embeddings.
- [astonysh/OpenClaw-DeepReeder](https://github.com/astonysh/OpenClaw-DeepReeder) - Web and content ingestion into long-term memory.
- [ZeroPointRepo/youtube-skills](https://github.com/ZeroPointRepo/youtube-skills) - Transcript and search skills useful for OpenClaw knowledge ingestion.

### Tooling and OpenClaw-compatible ecosystem

- [mnfst/manifest](https://github.com/mnfst/manifest) - Routing and observability for OpenClaw.
- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) - Model router built for OpenClaw.
- [refly-ai/refly](https://github.com/refly-ai/refly) - Open-source agent skills builder that explicitly targets Clawdbot and related agent ecosystems.
- [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - Cross-agent skills collection for Clawdbot, Claude Code, and Codex.
- [neonone123/moltdirectory](https://github.com/neonone123/moltdirectory) - Open-source marketplace for Moltbot skills and persona packs.
- [Nateliason/send-to-openclaw](https://github.com/Nateliason/send-to-openclaw) - Chrome extension that sends page content to Clawdbot via webhook.
- [VsevolodUstinov/openclaw-skill-claude-code](https://github.com/VsevolodUstinov/openclaw-skill-claude-code) - OpenClaw skill for Claude Code task execution.
- [Enderfga/openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) - MCP-based Claude Code integration skill for OpenClaw.
- [win4r/claude-code-clawdbot-skill](https://github.com/win4r/claude-code-clawdbot-skill) - Legacy-name skill for running Claude Code from agents.
- [rohunvora/x-research-skill](https://github.com/rohunvora/x-research-skill) - X and Twitter research skill compatible with OpenClaw.
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - Token tracking CLI with explicit OpenClaw support.
- [davepoon/buildwithclaude](https://github.com/davepoon/buildwithclaude) - Cross-ecosystem marketplace of skills and plugins that supports OpenClaw.
- [runkids/skillshare](https://github.com/runkids/skillshare) - Cross-tool skill sharing and sync, including OpenClaw.
- [farion1231/cc-switch](https://github.com/farion1231/cc-switch) - Desktop assistant launcher for multiple coding agents, including OpenClaw.
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - OpenClaw-compatible cowork shell.
- [AstrBotDevs/AstrBot](https://github.com/AstrBotDevs/AstrBot) - IM bot platform often compared against OpenClaw for channel coverage.
- [langbot-app/LangBot](https://github.com/langbot-app/LangBot) - Multi-platform bot platform with OpenClaw lineage references.
- [badrisnarayanan/antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - Proxy layer that advertises OpenClaw compatibility.

### Domain packs and experiments

- [FreedomIntelligence/OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) - Medical-focused skill library.
- [techartdev/OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - Home Assistant add-on path.
- [rookiestar28/ComfyUI-OpenClaw](https://github.com/rookiestar28/ComfyUI-OpenClaw) - Media-generation workflow inspired by OpenClaw.
- [Gen-Verse/OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) - RL-oriented training experiment.
- [calebwin/pgclaw](https://github.com/calebwin/pgclaw) - Experimental Postgres-native recreation of Clawdbot ideas.
- [Intent-Lab/VisionClaw](https://github.com/Intent-Lab/VisionClaw) - Voice-plus-vision companion layer.
- [white0dew/XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills) - Xiaohongshu automation skill pack that supports OpenClaw.
- [Xiangyu-CAS/xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill) - Xiaohongshu operations skill for OpenClaw and related toolchains.
- [voocel/openclaw-mini](https://github.com/voocel/openclaw-mini) - Minimal reconstruction of OpenClaw core ideas.

## Learning Resources

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Strongest use-cases-first collection.
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Large curated index of OpenClaw skills.
- [SamurAIGPT/awesome-openclaw](https://github.com/SamurAIGPT/awesome-openclaw) - Broad general-purpose awesome list.
- [vincentkoc/awesome-openclaw](https://github.com/vincentkoc/awesome-openclaw) - Multilingual awesome list with broader taxonomy.
- [1186258278/OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - Chinese-localized OpenClaw, Clawdbot, and Moltbot distribution with tutorials and troubleshooting notes.
- [AlexAnys/awesome-openclaw-usecases-zh](https://github.com/AlexAnys/awesome-openclaw-usecases-zh) - Chinese use-case collection with local-market focus.
- [clawdbot-ai/awesome-openclaw-skills-zh](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) - Chinese skill index.
- [xianyu110/awesome-openclaw-tutorial](https://github.com/xianyu110/awesome-openclaw-tutorial) - Chinese tutorial collection.
- [mengjian-github/openclaw101](https://github.com/mengjian-github/openclaw101) - Beginner-friendly learning hub.
- [0xtresser/OpenClaw-Book](https://github.com/0xtresser/OpenClaw-Book) - Book-style introduction.
- [yeuxuan/openclaw-docs](https://github.com/yeuxuan/openclaw-docs) - Chinese docs site and notes.
- [xianyu110/clawbot](https://github.com/xianyu110/clawbot) - Install and relay guide for the Clawdbot lineage.
- [shareAI-lab/claw0](https://github.com/shareAI-lab/claw0) - Learn OpenClaw from zero to one.
- [buainoai/awesome-clawdbot-skills](https://github.com/buainoai/awesome-clawdbot-skills) - Legacy-name skills collection.
- [EvoLinkAI/awesome-openclaw-usecases-moltbook](https://github.com/EvoLinkAI/awesome-openclaw-usecases-moltbook) - Use-case set connected to the Moltbook community.

## Adjacent Alternatives

These are worth watching, but they are not the OpenClaw core ecosystem.

- [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) - Container-first alternative with a security angle.
- [nearai/ironclaw](https://github.com/nearai/ironclaw) - Rust reimplementation focused on privacy and security.
- [zeroclaw-labs/zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) - Rust-based autonomous assistant infrastructure.
- [smallnest/goclaw](https://github.com/smallnest/goclaw) - Go-based OpenClaw-like framework.
- [alibaba/hiclaw](https://github.com/alibaba/hiclaw) - Team-based agent collaboration system.
- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - Ultra-light OpenClaw-style assistant.
- [memovai/mimiclaw](https://github.com/memovai/mimiclaw) - Hardware-first OpenClaw-inspired assistant OS.
- [ComposioHQ/secure-openclaw](https://github.com/ComposioHQ/secure-openclaw) - Security-focused fork or variant.
- [poco-ai/poco-agent](https://github.com/poco-ai/poco-agent) - UI-heavy alternative with a safer runtime pitch.
- [puremachinery/carapace](https://github.com/puremachinery/carapace) - Rust alternative positioned on security and stability.
- [getclawe/clawe](https://github.com/getclawe/clawe) - Coordination layer for OpenClaw-style agent teams.

## Contributing

Open a PR when a project is:

- clearly relevant to OpenClaw, Moltbot, or Clawdbot
- still maintained or historically important enough to explain the ecosystem
- better than an already listed duplicate
- useful to builders, operators, or advanced users

Please avoid:

- zero-context personal test repos
- generic AI lists with no explicit OpenClaw support
- exploit-only repositories
