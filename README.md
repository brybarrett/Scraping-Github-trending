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
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | 😎 Awesome lists about all kinds of interesting topics |
| [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) | Collection of awesome LLM apps with AI Agents and RAG using OpenAI, Anthropic, Gemini and opensource models. |
| [alphacep/vosk-api](https://github.com/alphacep/vosk-api) | Offline speech recognition API for Android, iOS, Raspberry Pi and servers with Python, Java, C# and Node |
| [jwohlwend/boltz](https://github.com/jwohlwend/boltz) | Official repository for the Boltz biomolecular interaction models |
| [jdepoix/youtube-transcript-api](https://github.com/jdepoix/youtube-transcript-api) | This is a python API which allows you to get the transcript/subtitles for a given YouTube video. It also works for automatically generated subtitles and it does not require an API key nor a headless browser, like other selenium based solutions do! |
| [zijie0/HumanSystemOptimization](https://github.com/zijie0/HumanSystemOptimization) | 健康学习到150岁 - 人体系统调优不完全指南 |
| [datawhalechina/self-llm](https://github.com/datawhalechina/self-llm) | 《开源大模型食用指南》针对中国宝宝量身打造的基于Linux环境快速微调（全参数/Lora）、部署国内外开源大模型（LLM）/多模态大模型（MLLM）教程 |
| [juspay/hyperswitch](https://github.com/juspay/hyperswitch) | An open source payments switch written in Rust to make payments fast, reliable and affordable |
| [OpenBMB/MiniCPM](https://github.com/OpenBMB/MiniCPM) | MiniCPM4: Ultra-Efficient LLMs on End Devices, achieving 5+ speedup on typical end-side chips |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero) | TensorZero creates a feedback loop for optimizing LLM applications — turning production data into smarter, faster, and cheaper models. |
| [frdel/agent-zero](https://github.com/frdel/agent-zero) | Agent Zero AI framework |
| [onlook-dev/onlook](https://github.com/onlook-dev/onlook) | The Cursor for Designers • An Open-Source Visual Vibecoding Editor • Visually build, style, and edit your React App with AI |
| [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader) | A high-performance algorithmic trading platform and event-driven backtester |
| [netbirdio/netbird](https://github.com/netbirdio/netbird) | Connect your devices into a secure WireGuard®-based overlay network with SSO, MFA and granular access controls. |
| [anthropics/prompt-eng-interactive-tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) | Anthropic's Interactive Prompt Engineering Tutorial |
| [datawhalechina/self-llm](https://github.com/datawhalechina/self-llm) | 《开源大模型食用指南》针对中国宝宝量身打造的基于Linux环境快速微调（全参数/Lora）、部署国内外开源大模型（LLM）/多模态大模型（MLLM）教程 |
| [eyaltoledano/claude-task-master](https://github.com/eyaltoledano/claude-task-master) | An AI-powered task-management system you can drop into Cursor, Lovable, Windsurf, Roo, and others. |
| [XTLS/Xray-core](https://github.com/XTLS/Xray-core) | Xray, Penetrates Everything. Also the best v2ray-core. Where the magic happens. An open platform for various uses. |
| [Anduin2017/HowToCook](https://github.com/Anduin2017/HowToCook) | 程序员在家做饭方法指南。Programmer's guide about how to cook at home (Simplified Chinese only). |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook) | 所有小初高、大学PDF教材。 |
| [Fosowl/agenticSeek](https://github.com/Fosowl/agenticSeek) | Fully Local Manus AI. No APIs, No $200 monthly bills. Enjoy an autonomous agent that thinks, browses the web, and code for the sole cost of electricity. 🔔 Official updates only via twitter @Martin993886460. Any other account is fake. |
| [onlook-dev/onlook](https://github.com/onlook-dev/onlook) | The Cursor for Designers • An Open-Source Visual Vibecoding Editor • Visually build, style, and edit your React App with AI |
| [microsoft/qlib](https://github.com/microsoft/qlib) | Qlib is an AI-oriented Quant investment platform that aims to use AI tech to empower Quant Research, from exploring ideas to implementing productions. Qlib supports diverse ML modeling paradigms, including supervised learning, market dynamics modeling, and RL, and is now equipped withhttps://github.com/microsoft/RD-Agentto automate R&D process. |
| [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) | AI's query engine - Platform for building AI that can answer questions over large scale federated data. - The only MCP Server you'll ever need |
| [xming521/WeClone](https://github.com/xming521/WeClone) | 🚀 One-stop solution for creating your digital avatar from chat history 💡 Fine-tune LLMs with your chat logs to capture your unique style, then bind to a chatbot to bring your digital self to life. 从聊天记录创造数字分身的一站式解决方案 |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | Memory for AI Agents; SOTA in AI Agent Memory; Announcing OpenMemory MCP - local and secure memory management. |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands. |
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | An AI Hedge Fund Team |
| [anthropics/courses](https://github.com/anthropics/courses) | Anthropic's educational courses |
<!-- END OF MONTHLY_TOP10_REPOS -->
