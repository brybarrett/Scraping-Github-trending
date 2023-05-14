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
| [privateGPT](https://github.com/imartinez/privateGPT) | Interact privately with your documents using the power of GPT, 100% privately, no data leaks |
| [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork) | so-vits-svc fork with realtime support, improved interface and more features. |
| [so-vits-svc](https://github.com/svc-develop-team/so-vits-svc) | SoftVC VITS Singing Voice Conversion |
| [semantic-kernel](https://github.com/microsoft/semantic-kernel) | Integrate cutting-edge LLM technology quickly and easily into your apps |
| [Huatuo-Llama-Med-Chinese](https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese) | Repo for HuaTuo (华驼), Llama-7B tuned with Chinese medical knowledge. 华驼模型仓库，基于中文医学知识的LLaMA模型指令微调 |
| [orillusion](https://github.com/Orillusion/orillusion) | Orillusion is a pure Web3D rendering engine which is fully developed based on the WebGPU standard. |
| [open-llms](https://github.com/eugeneyan/open-llms) | 🤖 A list of open LLMs available for commercial use. |
| [qdrant](https://github.com/qdrant/qdrant) | Qdrant - Vector Database for the next generation of AI applications. Also available in the cloud https://cloud.qdrant.io/ |
| [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere) | Atmosphère is a work-in-progress customized firmware for the Nintendo Switch. |
| [smartgpt](https://github.com/Cormanz/smartgpt) | A program that provides LLMs with the ability to complete complex tasks using plugins. |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [Ryujinx](https://github.com/Ryujinx/Ryujinx) | Experimental Nintendo Switch Emulator written in C# |
| [gpt4free](https://github.com/xtekky/gpt4free) | decentralising the Ai Industry, just some language model api's... |
| [mlc-llm](https://github.com/mlc-ai/mlc-llm) | Enable everyone to develop, optimize and deploy AI models natively on everyone's devices. |
| [PentestGPT](https://github.com/GreyDGL/PentestGPT) | A GPT-empowered penetration testing tool |
| [qdrant](https://github.com/qdrant/qdrant) | Qdrant - Vector Database for the next generation of AI applications. Also available in the cloud https://cloud.qdrant.io/ |
| [alpaca-lora](https://github.com/tloen/alpaca-lora) | Instruct-tune LLaMA on consumer hardware |
| [Flowise](https://github.com/FlowiseAI/Flowise) | Drag & drop UI to build your customized LLM flow using LangchainJS |
| [Auto-GPT-Plugins](https://github.com/Significant-Gravitas/Auto-GPT-Plugins) | Plugins for Auto-GPT |
| [qwik](https://github.com/BuilderIO/qwik) | Instant-loading web apps, without effort |
| [ord](https://github.com/casey/ord) | 👁‍🗨 Rare and exotic sats |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) | An experimental open-source attempt to make GPT-4 fully autonomous. |
| [AgentGPT](https://github.com/reworkd/AgentGPT) | 🤖 Assemble, configure, and deploy autonomous AI Agents in your browser. |
| [DeepSpeed](https://github.com/microsoft/DeepSpeed) | DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective. |
| [wolverine](https://github.com/biobootloader/wolverine) |  |
| [Open-Assistant](https://github.com/LAION-AI/Open-Assistant) | OpenAssistant is a chat-based assistant that understands tasks, can interact with third-party systems, and retrieve information dynamically to do so. |
| [babyagi](https://github.com/yoheinakajima/babyagi) |  |
| [taxonomy](https://github.com/shadcn/taxonomy) | An open source application built using the new router, server components and everything new in Next.js 13. |
| [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork) | so-vits-svc fork with realtime support, improved interface and more features. |
| [Ryujinx](https://github.com/Ryujinx/Ryujinx) | Experimental Nintendo Switch Emulator written in C# |
| [langchain-ChatGLM](https://github.com/imClumsyPanda/langchain-ChatGLM) | langchain-ChatGLM, local knowledge based ChatGLM with langchain ｜ 基于本地知识库的 ChatGLM 问答 |
<!-- END OF MONTHLY_TOP10_REPOS -->
