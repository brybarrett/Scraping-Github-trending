# 定时抓取Github Trending里的数据

作为一个间歇性“松鼠症”患者，有时候会花几个小时逛Github Trending，生怕漏掉什么重要的东西，说到底是心理作用罢了。

而这个Github Trend爬虫，就是我给自己开的一味药，都收集起来，就不怕漏掉啥了（虽然这个逻辑经不起推敲，不过确实部署这个爬虫之后，我再也没有逛过Github Trend）

* 基于[Github Actions](https://docs.github.com/en/actions)的爬虫
* 使用[click](https://github.com/pallets/click)实现了命令行参数
* 使用[Crontab Guru](https://crontab.guru/)来设置定时参数

# Repos
## 今日TOP10 
<!-- START OF DAILY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [MobileSAM](https://github.com/ChaoningZhang/MobileSAM) | This is the offiicial code for Faster Segment Anything (MobileSAM) project that makes SAM lightweight |
| [freegpt-webui](https://github.com/ramonvc/freegpt-webui) | GPT 3.5/4 with a Chat Web UI. No API key required. |
| [ChatGLM2-6B](https://github.com/THUDM/ChatGLM2-6B) | ChatGLM2-6B: An Open Bilingual Chat LLM | 开源双语对话语言模型 |
| [PowerShell](https://github.com/PowerShell/PowerShell) | PowerShell for every system! |
| [DragGAN](https://github.com/XingangPan/DragGAN) | Official Code for DragGAN (SIGGRAPH 2023) |
| [ChatGLM-Efficient-Tuning](https://github.com/hiyouga/ChatGLM-Efficient-Tuning) | Fine-tuning ChatGLM-6B with PEFT | 基于 PEFT 的高效 ChatGLM 微调 |
| [folly](https://github.com/facebook/folly) | An open-source C++ library developed and used at Facebook. |
| [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B) | ChatGLM-6B: An Open Bilingual Dialogue Language Model | 开源双语对话语言模型 |
| [project-based-learning](https://github.com/practical-tutorials/project-based-learning) | Curated list of project-based tutorials |
| [javascript-design-patterns-for-humans](https://github.com/sohamkamani/javascript-design-patterns-for-humans) | An ultra-simplified explanation of design patterns implemented in javascript |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [gpt-engineer](https://github.com/AntonOsika/gpt-engineer) | Specify what you want it to build, the AI asks for clarification, and then builds it. |
| [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | Data-Centric FinGPT. Open-source for open finance! Revolutionize 🔥 We'll soon release the trained model. |
| [ai](https://github.com/vercel-labs/ai) | Build AI-powered applications with React, Svelte, and Vue |
| [OpenLLM](https://github.com/bentoml/OpenLLM) | An open platform for operating large language models (LLMs) in production. Fine-tune, serve, deploy, and monitor any LLMs with ease. |
| [Chat2DB](https://github.com/alibaba/Chat2DB) | 🔥 🔥 🔥 An intelligent and versatile general-purpose SQL client and reporting tool for databases which integrates ChatGPT capabilities.(智能的通用数据库SQL客户端和报表工具) |
| [CodeEdit](https://github.com/CodeEditApp/CodeEdit) | CodeEdit App for macOS – Elevate your code editing experience. Open source, free forever. |
| [WizardLM](https://github.com/nlpxucan/WizardLM) | Family of instruction-following LLMs powered by Evol-Instruct: WizardLM, WizardCoder |
| [LLaMA-Efficient-Tuning](https://github.com/hiyouga/LLaMA-Efficient-Tuning) | Fine-tuning LLaMA with PEFT (PT+SFT+RLHF with QLoRA) |
| [desktop](https://github.com/desktop/desktop) | Focus on what matters instead of fighting with Git. |
| [lemmy](https://github.com/LemmyNet/lemmy) | 🐀 A link aggregator and forum for the fediverse |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) | <⚡️> SuperAGI - A dev-first open source autonomous AI agent framework. Enabling developers to build, manage & run useful autonomous agents quickly and reliably. |
| [gpt4free-ts](https://github.com/xiangsx/gpt4free-ts) | Providing a free OpenAI GPT-4 API ! This is a replication project for the typescript version of xtekky/gpt4free |
| [localGPT](https://github.com/PromtEngineer/localGPT) | Chat with your documents on your local device using GPT models. No data leaves your device and 100% private. |
| [Chat2DB](https://github.com/alibaba/Chat2DB) | 🔥 🔥 🔥 An intelligent and versatile general-purpose SQL client and reporting tool for databases which integrates ChatGPT capabilities.(智能的通用数据库SQL客户端和报表工具) |
| [roop](https://github.com/s0md3v/roop) | one-click deepfake (face swap) |
| [go-proxy-bingai](https://github.com/adams549659584/go-proxy-bingai) | 用 Vue3 和 Go 搭建的微软 New Bing 演示站点，拥有一致的 UI 体验，支持 ChatGPT 提示词，国内可用。 |
| [invidious](https://github.com/iv-org/invidious) | Invidious is an alternative front-end to YouTube |
| [spacedrive](https://github.com/spacedriveapp/spacedrive) | Spacedrive is an open source cross-platform file explorer, powered by a virtual distributed filesystem written in Rust. |
| [dm-ticket](https://github.com/ClassmateLin/dm-ticket) | 大麦网自动购票, 支持docker一键部署。Damai automatically purchases tickets, running in docker container. |
| [ggml](https://github.com/ggerganov/ggml) | Tensor library for machine learning |
<!-- END OF MONTHLY_TOP10_REPOS -->
