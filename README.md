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
| [fish-speech](https://github.com/fishaudio/fish-speech) | SOTA Open Source TTS |
| [MegaParse](https://github.com/QuivrHQ/MegaParse) | File Parser optimised for LLM Ingestion with no loss 🧠 Parse PDFs, Docx, PPTx in a format that is ideal for LLMs. |
| [react](https://github.com/facebook/react) | The library for web and native user interfaces. |
| [cobalt](https://github.com/imputnet/cobalt) | best way to save what you love |
| [wvp-GB28181-pro](https://github.com/648540858/wvp-GB28181-pro) | WEB VIDEO PLATFORM是一个基于GB28181-2016标准实现的网络视频平台，支持NAT穿透，支持海康、大华、宇视等品牌的IPC、NVR、DVR接入。支持国标级联，支持rtsp/rtmp等视频流转发到国标平台，支持rtsp/rtmp等推流转发到国标平台。 |
| [github-pages](https://github.com/skills/github-pages) | Create a site or blog from your GitHub repositories with GitHub Pages. |
| [invoify](https://github.com/al1abb/invoify) | An invoice generator app built using Next.js, Typescript, and Shadcn |
| [copilot-codespaces-vscode](https://github.com/skills/copilot-codespaces-vscode) | Develop with AI-powered code suggestions using GitHub Copilot and VS Code |
| [json](https://github.com/nlohmann/json) | JSON for Modern C++ |
| [grpc-go](https://github.com/grpc/grpc-go) | The Go language implementation of gRPC. HTTP/2 based RPC |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [stock](https://github.com/myhhub/stock) | stock股票.获取股票数据,计算股票指标,识别股票形态,综合选股,选股策略,股票验证回测,股票自动交易,支持PC及移动设备。 |
| [ladybird](https://github.com/LadybirdBrowser/ladybird) | Truly independent web browser |
| [lobe-chat](https://github.com/lobehub/lobe-chat) | 🤯 Lobe Chat - an open-source, modern-design AI chat framework. Supports Multi AI Providers( OpenAI / Claude 3 / Gemini / Ollama / Qwen / DeepSeek), Knowledge Base (file upload / knowledge management / RAG ), Multi-Modals (Vision/TTS/Plugins/Artifacts). One-click FREE deployment of your private ChatGPT/ Claude application. |
| [react-scan](https://github.com/aidenybai/react-scan) | Scan for React performance issues and eliminate slow renders in your app |
| [fish-speech](https://github.com/fishaudio/fish-speech) | SOTA Open Source TTS |
| [keep](https://github.com/keephq/keep) | The open-source alert management and AIOps platform |
| [expert_readed_books](https://github.com/0voice/expert_readed_books) | 2021年最新总结，推荐工程师合适读本，计算机科学，软件技术，创业，思想类，数学类，人物传记书籍 |
| [iptv-api](https://github.com/Guovin/iptv-api) | 📺IPTV电视直播源更新工具🚀：✨央视、📡卫视、☘️广东及各省份地方台、🌊港·澳·台、🎬电影、🎥咪咕、🏀体育、🪁动画、🎮游戏、🎵音乐、🏛经典剧场；支持IPv4/IPv6；支持自定义增加频道；支持组播源、酒店源、订阅源、关键字搜索；每天自动更新两次，结果可用于TVBox等播放软件；支持工作流、Docker(amd64/arm64/arm v7)、命令行、GUI运行方式 | IPTV live TV source update tool |
| [spotube](https://github.com/KRTirtho/spotube) | 🎧 Open source Spotify client that doesn't require Premium nor uses Electron! Available for both desktop & mobile! |
| [crawl4ai](https://github.com/unclecode/crawl4ai) | 🔥🕷️ Crawl4AI: Crawl Smarter, Faster, Freely. For AI. |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [windows](https://github.com/dockur/windows) | Windows inside a Docker container. |
| [eliza](https://github.com/ai16z/eliza) | Autonomous agents for everyone |
| [screenshot-to-code](https://github.com/abi/screenshot-to-code) | Drop in a screenshot and convert it to clean code (HTML/Tailwind/React/Vue) |
| [MinerU](https://github.com/opendatalab/MinerU) | A high-quality tool for convert PDF to Markdown and JSON.一站式开源高质量数据提取工具，将PDF转换成Markdown和JSON格式。 |
| [freqtrade](https://github.com/freqtrade/freqtrade) | Free, open source crypto trading bot |
| [ai-chatbot](https://github.com/vercel/ai-chatbot) | A full-featured, hackable Next.js AI chatbot built by Vercel |
| [next-forge](https://github.com/haydenbleasel/next-forge) | Production-grade Turborepo template for Next.js apps. |
| [khoj](https://github.com/khoj-ai/khoj) | Your AI second brain. Self-hostable. Get answers from the web or your docs. Build custom agents, schedule automations, do deep research. Turn any online or local LLM into your personal, autonomous AI (e.g gpt, claude, gemini, llama, qwen, mistral). |
| [exo](https://github.com/exo-explore/exo) | Run your own AI cluster at home with everyday devices 📱💻 🖥️⌚ |
| [autogen](https://github.com/microsoft/autogen) | A programming framework for agentic AI 🤖 (PyPi: autogen-agentchat) |
<!-- END OF MONTHLY_TOP10_REPOS -->
