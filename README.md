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
| [lobe-chat](https://github.com/lobehub/lobe-chat) | 🤯 Lobe Chat - an open-source, modern-design AI chat framework. Supports Multi AI Providers( OpenAI / Claude 3 / Gemini / Ollama / Azure / DeepSeek), Knowledge Base (file upload / knowledge management / RAG ), Multi-Modals (Vision/TTS/Plugins/Artifacts). One-click FREE deployment of your private ChatGPT/ Claude application. |
| [ladybird](https://github.com/LadybirdBrowser/ladybird) | Truly independent web browser |
| [stock](https://github.com/myhhub/stock) | stock股票.获取股票数据,计算股票指标,识别股票形态,综合选股,选股策略,股票验证回测,股票自动交易,支持PC及移动设备。 |
| [iptv-api](https://github.com/Guovin/iptv-api) | 📺IPTV电视直播源更新工具🚀：包含💰央视、📡卫视、☘️广东及各省份地方台、🌊港·澳·台、🎬电影、🎥咪咕、🏀体育、🪁动画、🎮游戏、🎵音乐、🏛经典剧场；支持自定义增加频道；支持组播源、酒店源、订阅源、关键字搜索；每天自动更新两次，结果可用于TVBox等播放软件；支持工作流、Docker(amd64/arm64/arm v7)、命令行、GUI运行方式 | IPTV live TV source update tool |
| [iptvnator](https://github.com/4gray/iptvnator) | 📺 Cross-platform IPTV player application with multiple features, such as support of m3u and m3u8 playlists, favorites, TV guide, TV archive/catchup and more. |
| [keep](https://github.com/keephq/keep) | The open-source alert management and AIOps platform |
| [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | Master programming by recreating your favorite technologies from scratch. |
| [prompt-eng-interactive-tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) | Anthropic's Interactive Prompt Engineering Tutorial |
| [HelloGitHub](https://github.com/521xueweihan/HelloGitHub) | 分享 GitHub 上有趣、入门级的开源项目。Share interesting, entry-level open source projects on GitHub. |
| [Best-websites-a-programmer-should-visit](https://github.com/sdmg15/Best-websites-a-programmer-should-visit) | 🔗 Some useful websites for programmers. |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [screenshot-to-code](https://github.com/abi/screenshot-to-code) | Drop in a screenshot and convert it to clean code (HTML/Tailwind/React/Vue) |
| [postiz-app](https://github.com/gitroomhq/postiz-app) | 📨 The ultimate social media scheduling tool, with a bunch of AI 🤖 |
| [flux](https://github.com/black-forest-labs/flux) | Official inference repo for FLUX.1 models |
| [lazydocker](https://github.com/jesseduffield/lazydocker) | The lazier way to manage everything docker |
| [atproto](https://github.com/bluesky-social/atproto) | Social networking technology created by Bluesky |
| [multi-agent-orchestrator](https://github.com/awslabs/multi-agent-orchestrator) | Flexible and powerful framework for managing multiple AI agents and handling complex conversations |
| [slang](https://github.com/shader-slang/slang) | Making it easier to work with shaders |
| [v2rayN](https://github.com/2dust/v2rayN) | A GUI client for Windows and Linux, support Xray core and others |
| [hello-algo](https://github.com/krahets/hello-algo) | 《Hello 算法》：动画图解、一键运行的数据结构与算法教程。支持 Python, Java, C++, C, C#, JS, Go, Swift, Rust, Ruby, Kotlin, TS, Dart 代码。简体版和繁体版同步更新，English version ongoing |
| [free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 📚 Freely available programming books |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [docling](https://github.com/DS4SD/docling) | Get your documents ready for gen AI |
| [windows](https://github.com/dockur/windows) | Windows inside a Docker container. |
| [screenshot-to-code](https://github.com/abi/screenshot-to-code) | Drop in a screenshot and convert it to clean code (HTML/Tailwind/React/Vue) |
| [eliza](https://github.com/ai16z/eliza) | Conversational Agent for Twitter and Discord |
| [MinerU](https://github.com/opendatalab/MinerU) | A high-quality tool for convert PDF to Markdown and JSON.一站式开源高质量数据提取工具，将PDF转换成Markdown和JSON格式。 |
| [ai-chatbot](https://github.com/vercel/ai-chatbot) | A full-featured, hackable Next.js AI chatbot built by Vercel |
| [twenty](https://github.com/twentyhq/twenty) | Building a modern alternative to Salesforce, powered by the community. |
| [freqtrade](https://github.com/freqtrade/freqtrade) | Free, open source crypto trading bot |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 🙌 OpenHands: Code Less, Make More |
| [khoj](https://github.com/khoj-ai/khoj) | Your AI second brain. Self-hostable. Get answers from the web or your docs. Build custom agents, schedule automations, do deep research. Turn any online or local LLM into your personal, autonomous AI (e.g gpt, claude, gemini, llama, qwen, mistral). |
<!-- END OF MONTHLY_TOP10_REPOS -->
