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
| [alphacep/vosk-api](https://github.com/alphacep/vosk-api) | Offline speech recognition API for Android, iOS, Raspberry Pi and servers with Python, Java, C# and Node |
| [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero) | TensorZero creates a feedback loop for optimizing LLM applications — turning production data into smarter, faster, and cheaper models. |
| [XTLS/Xray-core](https://github.com/XTLS/Xray-core) | Xray, Penetrates Everything. Also the best v2ray-core. Where the magic happens. An open platform for various uses. |
| [topoteretes/cognee](https://github.com/topoteretes/cognee) | Memory for AI Agents in 5 lines of code |
| [eyaltoledano/claude-task-master](https://github.com/eyaltoledano/claude-task-master) | An AI-powered task-management system you can drop into Cursor, Lovable, Windsurf, Roo, and others. |
| [NirDiamant/RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques) | This repository showcases various advanced techniques for Retrieval-Augmented Generation (RAG) systems. RAG systems combine information retrieval with generative models to provide accurate and contextually rich responses. |
| [eythaann/Seelen-UI](https://github.com/eythaann/Seelen-UI) | The Fully Customizable Desktop Environment for Windows 10/11. |
| [zijie0/HumanSystemOptimization](https://github.com/zijie0/HumanSystemOptimization) | 健康学习到150岁 - 人体系统调优不完全指南 |
| [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | 🐙 Guides, papers, lecture, notebooks and resources for prompt engineering |
| [PathOfBuildingCommunity/PathOfBuilding](https://github.com/PathOfBuildingCommunity/PathOfBuilding) | Offline build planner for Path of Exile. |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [onlook-dev/onlook](https://github.com/onlook-dev/onlook) | The Cursor for Designers • An Open-Source Visual Vibecoding Editor • Visually build, style, and edit your React App with AI |
| [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader) | A high-performance algorithmic trading platform and event-driven backtester |
| [frdel/agent-zero](https://github.com/frdel/agent-zero) | Agent Zero AI framework |
| [anthropics/prompt-eng-interactive-tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) | Anthropic's Interactive Prompt Engineering Tutorial |
| [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero) | TensorZero creates a feedback loop for optimizing LLM applications — turning production data into smarter, faster, and cheaper models. |
| [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app) | 📨 The ultimate social media scheduling tool, with a bunch of AI 🤖 |
| [netbirdio/netbird](https://github.com/netbirdio/netbird) | Connect your devices into a secure WireGuard®-based overlay network with SSO, MFA and granular access controls. |
| [datawhalechina/self-llm](https://github.com/datawhalechina/self-llm) | 《开源大模型食用指南》针对中国宝宝量身打造的基于Linux环境快速微调（全参数/Lora）、部署国内外开源大模型（LLM）/多模态大模型（MLLM）教程 |
| [anthropics/courses](https://github.com/anthropics/courses) | Anthropic's educational courses |
| [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) | Learn how to design large-scale systems. Prep for the system design interview. Includes Anki flashcards. |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [Fosowl/agenticSeek](https://github.com/Fosowl/agenticSeek) | Fully Local Manus AI. No APIs, No $200 monthly bills. Enjoy an autonomous agent that thinks, browses the web, and code for the sole cost of electricity. 🔔 Official updates only via twitter @Martin993886460. Any other account is fake. |
| [xming521/WeClone](https://github.com/xming521/WeClone) | 🚀 One-stop solution for creating your digital avatar from chat history 💡 Fine-tune LLMs with your chat logs to capture your unique style, then bind to a chatbot to bring your digital self to life. 从聊天记录创造数字分身的一站式解决方案 |
| [onlook-dev/onlook](https://github.com/onlook-dev/onlook) | The Cursor for Designers • An Open-Source Visual Vibecoding Editor • Visually build, style, and edit your React App with AI |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | Memory for AI Agents; SOTA in AI Agent Memory; Announcing OpenMemory MCP - local and secure memory management. |
| [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) | AI's query engine - Platform for building AI that can answer questions over large scale federated data. - The only MCP Server you'll ever need |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM. |
| [microsoft/qlib](https://github.com/microsoft/qlib) | Qlib is an AI-oriented Quant investment platform that aims to use AI tech to empower Quant Research, from exploring ideas to implementing productions. Qlib supports diverse ML modeling paradigms, including supervised learning, market dynamics modeling, and RL, and is now equipped withhttps://github.com/microsoft/RD-Agentto automate R&D process. |
| [public-apis/public-apis](https://github.com/public-apis/public-apis) | A collective list of free APIs |
| [voideditor/void](https://github.com/voideditor/void) |  |
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | An AI Hedge Fund Team |
<!-- END OF MONTHLY_TOP10_REPOS -->
