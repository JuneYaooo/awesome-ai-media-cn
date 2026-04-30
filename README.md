# Awesome AI Media 中文版 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> AI 视频制作与自媒体运营工具精选合集 — 涵盖一键生成、文生视频、多平台分发、字幕翻译等开源项目，每周更新。

[English](https://github.com/JuneYaooo/awesome-ai-media) | [中文](README.md)

![Stars](https://img.shields.io/github/stars/JuneYaooo/awesome-ai-media-cn?style=social)
![Last Commit](https://img.shields.io/github/last-commit/JuneYaooo/awesome-ai-media-cn)
![License](https://img.shields.io/badge/license-CC0--1.0-blue)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)](CONTRIBUTING.md)

## 目录

- [一键视频生成](#一键视频生成)
- [AI 文生视频模型](#ai-文生视频模型)
- [自媒体运营工具](#自媒体运营工具)
- [社媒爬虫与竞品分析](#社媒爬虫与竞品分析)
- [字幕与本地化](#字幕与本地化)
- [AI 短剧生成](#ai-短剧生成)
- [AI 视频分析与笔记](#ai-视频分析与笔记)
- [AI 数字人](#ai-数字人)
- [编程式视频制作](#编程式视频制作)
- [视频编辑库](#视频编辑库)
- [常见问题](#常见问题)

---

## 一键视频生成

| 项目 | Stars | 说明 |
|------|-------|------|
| [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | ![](https://img.shields.io/github/stars/harry0703/MoneyPrinterTurbo?style=flat-square) | 一键 AI 短视频生成器 — 自动脚本、配音、字幕、剪辑，支持多种大模型 |
| [MoneyPrinter](https://github.com/FujiwaraChoki/MoneyPrinter) | ![](https://img.shields.io/github/stars/FujiwaraChoki/MoneyPrinter?style=flat-square) | 自动化 YouTube Shorts / TikTok 视频创建 |
| [ShortGPT](https://github.com/RayVentura/ShortGPT) | ![](https://img.shields.io/github/stars/RayVentura/ShortGPT?style=flat-square) | 短视频全流程自动化 AI 框架 |
| [RedditVideoMakerBot](https://github.com/elebumm/RedditVideoMakerBot) | ![](https://img.shields.io/github/stars/elebumm/RedditVideoMakerBot?style=flat-square) | Reddit 帖子自动转 TikTok/Shorts 风格解说视频 |
| [NarratoAI](https://github.com/linyqh/NarratoAI) | ![](https://img.shields.io/github/stars/linyqh/NarratoAI?style=flat-square) | AI 一键解说并剪辑视频 — 自动脚本、配音、成片 |
| [MoneyPrinterPlus](https://github.com/ddean2009/MoneyPrinterPlus) | ![](https://img.shields.io/github/stars/ddean2009/MoneyPrinterPlus?style=flat-square) | AI 一键批量生成各类短视频，支持多平台和多种大模型 |
| [Pixelle-Video](https://github.com/AIDC-AI/Pixelle-Video) | ![](https://img.shields.io/github/stars/AIDC-AI/Pixelle-Video?style=flat-square) | AI 全自动短视频引擎 — 端到端生成流水线 |
| [short-video-factory](https://github.com/YILS-LIN/short-video-factory) | ![](https://img.shields.io/github/stars/YILS-LIN/short-video-factory?style=flat-square) | 一键生成产品营销短视频 |
| [Video-Materials-AutoGEN-Workstation](https://github.com/Norsico/Video-Materials-AutoGEN-Workstation) | ![](https://img.shields.io/github/stars/Norsico/Video-Materials-AutoGEN-Workstation?style=flat-square) | 短视频生成工作站 — 自动素材搜集与合成 |
| [OpenMontage](https://github.com/calesthio/OpenMontage) | ![](https://img.shields.io/github/stars/calesthio/OpenMontage?style=flat-square) | 开源 Agent 视频生产系统 —— 从调研、脚本、素材生成到时间线剪辑和成片渲染，全流程自动化 |
| [Seedance 2.0 Web](https://github.com/wwwzhouhui/seedance2.0) | ![](https://img.shields.io/github/stars/wwwzhouhui/seedance2.0?style=flat-square) | 基于即梦 / CapCut Dreamina 的 AI 视频生成 Web 应用 —— 支持多图参考、双模型/多画幅/4-15 秒时长、Cookie 导入和 Docker 一键部署 |
| [AIGC-Claw](https://github.com/HITsz-TMG/AIGC-Claw) | ![](https://img.shields.io/github/stars/HITsz-TMG/AIGC-Claw?style=flat-square) | AI 导演式视频生成系统 —— 从一句想法自动拆解到剧本、角色/场景设计、分镜、参考图、视频生成和后期剪辑，支持 Web / 微信 / 飞书协作 |
| [CaroCut](https://github.com/bilibili/carocut) | ![](https://img.shields.io/github/stars/bilibili/carocut?style=flat-square) | B 站开源的多 Agent 视频制作系统，基于 OpenCode AI SDK 和 Remotion，将 PDF、图片、文本自动转成专业视频 |
| [CutDeck](https://github.com/Agions/CutDeck) | ![](https://img.shields.io/github/stars/Agions/CutDeck?style=flat-square) | 开源 AI 视频剪辑工具，自动从长视频拆出短爆款片段，支持多画幅导出、本地 Whisper 字幕和 Rust 渲染管线 |
| [MoneyPrinterAICreate](https://github.com/q1uki/MoneyPrinterAICreate) | ![](https://img.shields.io/github/stars/q1uki/MoneyPrinterAICreate?style=flat-square) | 基于 MoneyPrinterTurbo 的短视频生成增强版 —— 接入通义万相 Wan2.1 文/图生视频素材，支持分镜与提示词可编辑，自动拼接字幕、配音和配乐成片。 |
| [KaiyanAI / KaiyanTool](https://github.com/xiashao/KaiyanTool) | ![](https://img.shields.io/github/stars/xiashao/KaiyanTool?style=flat-square) | 面向影视创作者的一站式 AI 创作平台 —— 从剧本、分镜到图像/视频生成全流程打通，支持多模型、桌面端 Tauri 应用和较完整的工程化文档。 |
| [Voxplore](https://github.com/Agions/Voxplore) | ![](https://img.shields.io/github/stars/Agions/Voxplore?style=flat-square) | AI 第一人称视频解说工具 —— 批量上传素材后自动分组、抽取片段、生成配音和字幕，适合短剧、影视混剪和 vlog 叙事化改写。 |
| [AI Video Workstation / auto_video_maker](https://github.com/rancho-houyaohui/auto_video_maker) | ![](https://img.shields.io/github/stars/rancho-houyaohui/auto_video_maker?style=flat-square) | 本地大模型驱动的视频生产工作站 —— 自动拆分分镜、匹配素材、生成 TTS/音效/字幕，并提供 Web UI 做逐镜头精修与渲染。 |

## AI 文生视频模型

| 项目 | Stars | 说明 |
|------|-------|------|
| [Open-Sora](https://github.com/hpcaitech/Open-Sora) | ![](https://img.shields.io/github/stars/hpcaitech/Open-Sora?style=flat-square) | 开源 Sora 复现 — 高质量文本生成视频 |
| [Wan2.1](https://github.com/Wan-Video/Wan2.1) | ![](https://img.shields.io/github/stars/Wan-Video/Wan2.1?style=flat-square) | 阿里开源视频生成套件 — 文/图生视频，1.3B-14B 参数，中英双语 |
| [FramePack](https://github.com/lllyasviel/FramePack) | ![](https://img.shields.io/github/stars/lllyasviel/FramePack?style=flat-square) | ControlNet 作者新作 — 固定显存生成任意长度视频，消费级显卡可跑 |
| [CogVideo](https://github.com/THUDM/CogVideo) | ![](https://img.shields.io/github/stars/THUDM/CogVideo?style=flat-square) | 清华文生视频扩散模型 — 2B/5B 参数版本 |
| [HunyuanVideo](https://github.com/Tencent/HunyuanVideo) | ![](https://img.shields.io/github/stars/Tencent/HunyuanVideo?style=flat-square) | 腾讯开源大规模视频生成模型 |
| [HunyuanVideo-1.5](https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5) | ![](https://img.shields.io/github/stars/Tencent-Hunyuan/HunyuanVideo-1.5?style=flat-square) | 腾讯轻量级视频生成模型 —— 8.3B 参数、消费级显卡可跑，开源权重、训练/推理代码、ComfyUI 支持和中英提示词手册 |
| [AnimateDiff](https://github.com/guoyww/AnimateDiff) | ![](https://img.shields.io/github/stars/guoyww/AnimateDiff?style=flat-square) | 将个性化文生图模型转为视频动画 |

## 自媒体运营工具

| 项目 | Stars | 可用性 | 说明 |
|------|-------|--------|------|
| [Postiz](https://github.com/gitroomhq/postiz-app) | ![](https://img.shields.io/github/stars/gitroomhq/postiz-app?style=flat-square) | ⚠️ 部分可用 | 开源社媒管理平台 — Buffer/Hootsuite 替代品，支持定时发布和 AI 内容生成 |
| [social-auto-upload](https://github.com/dreammis/social-auto-upload) | ![](https://img.shields.io/github/stars/dreammis/social-auto-upload?style=flat-square) | ✅ 直接可用 | 视频一键多平台分发 — 抖音/TikTok/B站/快手/小红书/视频号 |
| [matrix](https://github.com/kebenxiaoming/matrix) | ![](https://img.shields.io/github/stars/kebenxiaoming/matrix?style=flat-square) | ✅ 直接可用 | 基于 Playwright 的短视频矩阵分发脚本系统，可自动发布到抖音、视频号、小红书、快手等平台，并支持登录态与发布队列管理。 |
| [video-mover](https://github.com/toki-plus/video-mover) | ![](https://img.shields.io/github/stars/toki-plus/video-mover?style=flat-square) | ✅ 直接可用 | 全自动短视频搬运工具 — 支持多平台视频下载与发布 |
| [BrightBean Studio](https://github.com/brightbeanxyz/brightbean-studio) | ![](https://img.shields.io/github/stars/brightbeanxyz/brightbean-studio?style=flat-square) | ⚠️ 部分可用 | 自托管社媒管理平台 —— 面向创作者/代理机构，支持排期、审批、发布、分析和多工作区协作 |
| [YTB2BILI](https://github.com/difyz9/ytb2bili) | ![](https://img.shields.io/github/stars/difyz9/ytb2bili?style=flat-square) | ✅ 直接可用 | YouTube/TikTok 到 B 站的全自动搬运流水线 —— 下载、Whisper 字幕、AI 翻译、元数据生成、定时发布一条龙 |
| [PostBot](https://github.com/gitcoffee-os/postbot) | ![](https://img.shields.io/github/stars/gitcoffee-os/postbot?style=flat-square) | ✅ 直接可用 | 多平台内容同步分发工具 —— 文章、笔记、图片、视频、音频一键发布到主流中文和国际平台 |
| [Wechatsync](https://github.com/wechatsync/Wechatsync) | ![](https://img.shields.io/github/stars/wechatsync/Wechatsync?style=flat-square) | ✅ 直接可用 | 文章多平台同步助手 —— 支持公众号、知乎、掘金、CSDN、WordPress 等渠道的一次编辑、多端分发 |
| [biliup](https://github.com/biliup/biliup) | ![](https://img.shields.io/github/stars/biliup/biliup?style=flat-square) | ✅ 直接可用 | 直播录制与投稿自动化工具 —— 支持 B 站投稿、直播录制、视频下载和跨平台内容搬运 |
| [SyncCaster](https://github.com/RyanYipeng/SyncCaster) | ![](https://img.shields.io/github/stars/RyanYipeng/SyncCaster?style=flat-square) | ✅ 直接可用 | Chrome 多平台内容分发扩展 —— 采集或撰写文章后统一转 Markdown，并自动同步到知乎、掘金、CSDN、公众号等 |
| [AIWriteX](https://github.com/iniwap/AIWriteX) | ![](https://img.shields.io/github/stars/iniwap/AIWriteX?style=flat-square) | ✅ 直接可用 | 公众号多智能体内容生产平台 —— 热点聚合、选题、采集、去 AI 味改写、排版、配图与自动发布一体化，并支持小红书/百家号/抖音等多平台改写分发 |
| [SynapseAutomation](https://github.com/Laihiujin/SYNAPSEAUTOMATION) | ![](https://img.shields.io/github/stars/Laihiujin/SYNAPSEAUTOMATION?style=flat-square) | ✅ 直接可用 | AI 矩阵投放/分发中台 —— 多账号多素材多平台排期、发布、监控和数据回收闭环，覆盖抖音/小红书/快手/视频号/B 站 |
| [RedBox](https://github.com/Jamailar/RedBox) | ![](https://img.shields.io/github/stars/Jamailar/RedBox?style=flat-square) | ✅ 直接可用 | 面向小红书创作者的 AI 工作台 —— 支持内容采集入库、随机漫步选题、稿件管理、AI 生图/生视频、封面生成和 RedClaw 自动化执行 |
| [Cyber Collector](https://t.me/cybercollectorbot) | — | ✅ 直接可用 | 免费 Telegram 下载机器人 —— 支持 TikTok（无水印）、Instagram Reels/Stories、YouTube+Shorts、X/Twitter、Facebook 视频下载，无需注册，无广告。[官网](https://cybercollector.hitkey.io) |

## 社媒爬虫与竞品分析

| 项目 | Stars | 可用性 | 说明 |
|------|-------|--------|------|
| [MediaCrawler](https://github.com/NanmiCoder/MediaCrawler) | ![](https://img.shields.io/github/stars/NanmiCoder/MediaCrawler?style=flat-square) | ✅ 直接可用 | 小红书/抖音/快手/B站/微博爬虫 — 竞品分析利器 |
| [douyin](https://github.com/erma0/douyin) | ![](https://img.shields.io/github/stars/erma0/douyin?style=flat-square) | ✅ 直接可用 | 抖音开源爬虫与下载工具 —— 账号主页、话题、合集、作品、关注/粉丝等公开数据采集，提供 GUI / Web / CLI / REST API |
| [xhs](https://github.com/ReaJason/xhs) | ![](https://img.shields.io/github/stars/ReaJason/xhs?style=flat-square) | ✅ 直接可用 | 小红书 Web API 封装与爬取工具链 —— 适合做内容抓取、账号分析和数据采集 |
| [bilibili-comment-crawler](https://github.com/1dyer/bilibili-comment-crawler) | ![](https://img.shields.io/github/stars/1dyer/bilibili-comment-crawler?style=flat-square) | ✅ 直接可用 | B 站评论抓取工具 —— 支持一级评论、二级回复和 CSV 导出，适合舆情与选题分析 |
| [TikHub API Python SDK](https://github.com/TikHub/TikHub-API-Python-SDK) | ![](https://img.shields.io/github/stars/TikHub/TikHub-API-Python-SDK?style=flat-square) | ⚠️ 部分可用 | TikHub 官方 Python SDK，统一封装抖音、小红书、B站、微博、YouTube 等 16+ 平台数据接口，适合做选题分析、竞品监测、达人研究和 AI 训练数据采集。 |

## 字幕与本地化

| 项目 | Stars | 可用性 | 说明 |
|------|-------|--------|------|
| [VideoLingo](https://github.com/Huanshere/VideoLingo) | ![](https://img.shields.io/github/stars/Huanshere/VideoLingo?style=flat-square) | ✅ 直接可用 | 视频翻译一条龙 — Netflix 级字幕切分、AI 翻译、配音对齐 |
| [KrillinAI](https://github.com/krillinai/KrillinAI) | ![](https://img.shields.io/github/stars/krillinai/KrillinAI?style=flat-square) | ✅ 直接可用 | AI 视频翻译配音工具 — 多语言支持 |
| [PotPlayer_ChatGPT_Translate](https://github.com/Felix3322/PotPlayer_ChatGPT_Translate) | ![](https://img.shields.io/github/stars/Felix3322/PotPlayer_ChatGPT_Translate?style=flat-square) | ✅ 直接可用 | PotPlayer 实时字幕翻译插件 —— 接入 OpenAI 兼容接口，支持观看视频时即时翻译字幕 |
| [video-subtitle-remover](https://github.com/YaoFANGUK/video-subtitle-remover) | ![](https://img.shields.io/github/stars/YaoFANGUK/video-subtitle-remover?style=flat-square) | ✅ 直接可用 | AI 视频硬字幕去除 / 文本水印去除 |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | ![](https://img.shields.io/github/stars/SYSTRAN/faster-whisper?style=flat-square) | ✅ 直接可用 | Whisper 4x 加速版 — 自动生成字幕/文字稿 |
| [whisper.cpp](https://github.com/ggerganov/whisper.cpp) | ![](https://img.shields.io/github/stars/ggerganov/whisper.cpp?style=flat-square) | ✅ 直接可用 | C/C++ 高性能 Whisper — 支持 CPU 和 Apple Silicon 本地运行 |
| [VideoCaptioner](https://github.com/WEIFENG2333/VideoCaptioner) | ![](https://img.shields.io/github/stars/WEIFENG2333/VideoCaptioner?style=flat-square) | ✅ 直接可用 | 基于 LLM 的字幕工作台 —— 语音识别、断句优化、字幕校正、翻译、烧录，提供 GUI/CLI 和测试 |
| [Open-Lyrics](https://github.com/zh-plus/Open-Lyrics) | ![](https://img.shields.io/github/stars/zh-plus/Open-Lyrics?style=flat-square) | ✅ 直接可用 | Whisper + LLM 字幕流水线 —— 转录、翻译、润色为 `.lrc`，支持双语字幕、术语表、音频预处理和 PyPI 安装 |
| [MioSub](https://github.com/corvo007/MioSub) | ![](https://img.shields.io/github/stars/corvo007/MioSub?style=flat-square) | ✅ 直接可用 | 全自动字幕工作台：下载、转录、翻译、对齐、压制一条龙，支持音视频双场景、CTC 对齐、桌面应用和在线文档，适合字幕组与出海内容团队。 |

## AI 短剧生成

| 项目 | Stars | 可用性 | 说明 |
|------|-------|--------|------|
| [huobao-drama](https://github.com/chatfire-AI/huobao-drama) | ![](https://img.shields.io/github/stars/chatfire-AI/huobao-drama?style=flat-square) | ✅ 直接可用 | 火宝短剧 — 一句话生成完整短剧 |
| [Toonflow-app](https://github.com/HBAI-Ltd/Toonflow-app) | ![](https://img.shields.io/github/stars/HBAI-Ltd/Toonflow-app?style=flat-square) | ✅ 直接可用 | AI 短剧漫剧生成工具 |
| [ArcReel](https://github.com/ArcReel/ArcReel) | ![](https://img.shields.io/github/stars/ArcReel/ArcReel?style=flat-square) | ⚠️ 部分可用 | 开源 AI 视频工作台 —— 从小说/创意到脚本、分镜、素材和短视频，全程由 Agent 编排 |
| [LocalMiniDrama](https://github.com/xuanyustudio/LocalMiniDrama) | ![](https://img.shields.io/github/stars/xuanyustudio/LocalMiniDrama?style=flat-square) | ✅ 直接可用 | 本地 AI 短剧/漫剧生成工具 —— 下载即用、数据不出本机、支持接入自有模型 API |
| [AI_novel](https://github.com/tyxben/AI_novel) | ![](https://img.shields.io/github/stars/tyxben/AI_novel?style=flat-square) | ✅ 直接可用 | 小说推文自动化平台 —— 将长篇小说一键转成适合抖音/小红书的有声短视频，支持 CLI / Web UI / MCP |
| [FastMovieAI](https://github.com/xhadmincn/FastMovieAI) | ![](https://img.shields.io/github/stars/xhadmincn/FastMovieAI?style=flat-square) | ✅ 直接可用 | 开源短剧/短视频创作平台 —— 前后端分离，覆盖脚本、素材、生成、支付和内容管理等完整链路 |
| [AI-NovelFlow](https://github.com/qzw881130/AI-NovelFlow) | ![](https://img.shields.io/github/stars/qzw881130/AI-NovelFlow?style=flat-square) | ✅ 直接可用 | 小说转视频平台，覆盖角色/场景/道具解析、分镜生成、配音与视频合成，并支持多语言界面与自定义 ComfyUI 工作流 |

## AI 视频分析与笔记

| 项目 | Stars | 可用性 | 说明 |
|------|-------|--------|------|
| [BibiGPT-v1](https://github.com/JimmyLv/BibiGPT-v1) | ![](https://img.shields.io/github/stars/JimmyLv/BibiGPT-v1?style=flat-square) | ⚠️ 部分可用 | AI 视频一键总结 — 支持 B站、YouTube、播客等 |
| [BiliNote](https://github.com/JefferyHcool/BiliNote) | ![](https://img.shields.io/github/stars/JefferyHcool/BiliNote?style=flat-square) | ✅ 直接可用 | AI 视频笔记生成 — B站等平台视频自动提取笔记 |
| [AI-Media2Doc](https://github.com/hanshuaikang/AI-Media2Doc) | ![](https://img.shields.io/github/stars/hanshuaikang/AI-Media2Doc?style=flat-square) | ✅ 直接可用 | 一键把音视频转成小红书/公众号/知识笔记/思维导图/总结/字幕，并支持智能截图插图 |

## AI 数字人

| 项目 | Stars | 可用性 | 说明 |
|------|-------|--------|------|
| [aigcpanel](https://github.com/modstart-lib/aigcpanel) | ![](https://img.shields.io/github/stars/modstart-lib/aigcpanel?style=flat-square) | ✅ 直接可用 | AIGC 数字人系统 — AI 虚拟主播 / 数字分身 |

## 编程式视频制作

| 项目 | Stars | 说明 |
|------|-------|------|
| [Remotion](https://github.com/remotion-dev/remotion) | ![](https://img.shields.io/github/stars/remotion-dev/remotion?style=flat-square) | 用 React 写视频 — 支持服务端渲染和 AWS Lambda 批量生成 |

## 视频编辑库

| 项目 | Stars | 说明 |
|------|-------|------|
| [MoviePy](https://github.com/Zulko/moviepy) | ![](https://img.shields.io/github/stars/Zulko/moviepy?style=flat-square) | Python 视频编辑库 — 剪切、合成、特效、文字叠加 |
| [ffmpeg-python](https://github.com/kkroening/ffmpeg-python) | ![](https://img.shields.io/github/stars/kkroening/ffmpeg-python?style=flat-square) | FFmpeg 的 Python 封装 — 视频/音频处理流水线 |

---

## 常见问题

### 最好的开源一键视频生成工具是什么？

**MoneyPrinterTurbo**（20k+ stars）是目前最流行、维护最活跃的方案。它覆盖完整流水线：LLM 生成脚本 → TTS 配音 → 字幕生成 → 素材搜索 → 视频合成。

### 最好的开源文生视频模型是什么？

研究级质量首推 **Wan2.1**（阿里，20k+ stars）和 **Open-Sora**（22k+ stars）。消费级显卡用户推荐 **FramePack**，支持固定显存生成任意长度视频。

### 如何实现视频多平台一键分发？

**social-auto-upload** 支持抖音、TikTok、B站、快手、小红书、视频号等主流平台的自动上传，自动填充标题、描述和标签。

---

## 贡献

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
