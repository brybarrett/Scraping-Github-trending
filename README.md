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
| [DragGAN](https://github.com/XingangPan/DragGAN) | Official Code for DragGAN (SIGGRAPH 2023) |
| [ChatGLM2-6B](https://github.com/THUDM/ChatGLM2-6B) | ChatGLM2-6B: An Open Bilingual Chat LLM | 开源双语对话语言模型 |
| [embedchain](https://github.com/embedchain/embedchain) | Framework to easily create LLM powered bots over any dataset. |
| [InjectLib](https://github.com/QiuChenlyOpenSource/InjectLib) | 基于Ruby编写的命令行注入版本 |
| [chathn](https://github.com/steven-tey/chathn) | Chat with Hacker News using natural language. Built with OpenAI Functions and Vercel AI SDK. |
| [papers-we-love](https://github.com/papers-we-love/papers-we-love) | Papers from the computer science community to read and discuss. |
| [Chat2DB](https://github.com/chat2db/Chat2DB) | 🔥 🔥 🔥 An intelligent and versatile general-purpose SQL client and reporting tool for databases which integrates ChatGPT capabilities.(智能的通用数据库SQL客户端和报表工具) |
| [exllama](https://github.com/turboderp/exllama) | A more memory-efficient rewrite of the HF transformers implementation of Llama for use with quantized weights. |
| [FastSAM](https://github.com/CASIA-IVA-Lab/FastSAM) | Fast Segment Anything |
| [telegram-groups](https://github.com/alexbei/telegram-groups) | 经过精心筛选，从5000+个电报群组/频道/机器人中挑选出的优质推荐！如果您有更多值得推荐的电报群组/频道/机器人，欢迎在issue中留言或提交pull requests。感谢您的关注！ |
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
| [AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | 12 Weeks, 24 Lessons, AI for All! |
| [ecoute](https://github.com/SevaSk/ecoute) | Ecoute is a live transcription tool that provides real-time transcripts for both the user's microphone input (You) and the user's speakers output (Speaker) in a textbox. It also generates a suggested response using OpenAI's GPT-3.5 for the user to say based on the live transcription of the conversation. |
| [gpt4free-ts](https://github.com/xiangsx/gpt4free-ts) | Providing a free OpenAI GPT-4 API ! This is a replication project for the typescript version of xtekky/gpt4free |
| [plane](https://github.com/makeplane/plane) | 🔥 🔥 🔥 Open Source JIRA, Linear and Height Alternative. Plane helps you track your issues, epics, and product roadmaps in the simplest way possible. |
| [Chat2DB](https://github.com/alibaba/Chat2DB) | 🔥 🔥 🔥 An intelligent and versatile general-purpose SQL client and reporting tool for databases which integrates ChatGPT capabilities.(智能的通用数据库SQL客户端和报表工具) |
| [tinygrad](https://github.com/geohot/tinygrad) | You like pytorch? You like micrograd? You love tinygrad! ❤️ |
| [qlora](https://github.com/artidoro/qlora) | QLoRA: Efficient Finetuning of Quantized LLMs |
| [invidious](https://github.com/iv-org/invidious) | Invidious is an alternative front-end to YouTube |
| [pandora](https://github.com/pengzhile/pandora) | 潘多拉，一个让你呼吸顺畅的ChatGPT。Pandora, a ChatGPT that helps you breathe smoothly. |
| [DeepFaceLive](https://github.com/iperov/DeepFaceLive) | Real-time face swap for PC streaming or video calls |
<!-- END OF MONTHLY_TOP10_REPOS -->
