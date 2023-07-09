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
| [noodle](https://github.com/ixahmedxi/noodle) | Open Source Education Platform |
| [InternLM](https://github.com/InternLM/InternLM) | InternLM has open-sourced a 7 billion parameter base model, a chat model tailored for practical scenarios and the training system. |
| [UV_K5_playground](https://github.com/piotr022/UV_K5_playground) |  |
| [MetaGPT](https://github.com/geekan/MetaGPT) | The Multi-Agent Meta Programming Framework: Given one line Requirement, return PRD, Design, Tasks, Repo | 多智能体元编程框架：给定老板需求，输出产品文档、架构设计、任务列表、代码 |
| [react-native](https://github.com/facebook/react-native) | A framework for building native applications using React |
| [quivr](https://github.com/StanGirard/quivr) | 🧠 Dump all your files and chat with it using your Generative AI Second Brain using LLMs ( GPT 3.5/4, Private, Anthropic, VertexAI ) & Embeddings 🧠 |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | A powerful and modular stable diffusion GUI with a graph/nodes interface. |
| [StackRot](https://github.com/lrh2000/StackRot) | CVE-2023-3269: Linux kernel privilege escalation vulnerability |
| [langchain](https://github.com/hwchase17/langchain) | ⚡ Building applications with LLMs through composability ⚡ |
| [system-design](https://github.com/karanpratapsingh/system-design) | Learn how to design systems at scale and prepare for system design interviews |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [tinygrad](https://github.com/tinygrad/tinygrad) | You like pytorch? You like micrograd? You love tinygrad! ❤️ |
| [Apollo-CustomApiCredentials](https://github.com/EthanArbuckle/Apollo-CustomApiCredentials) | Tweak to use your own reddit API credentials in Apollo |
| [background-removal-js](https://github.com/imgly/background-removal-js) | Remove backgrounds from images directly in the browser environment with ease and no additional costs or privacy concerns. Explore an interactive demo. |
| [mastodon](https://github.com/mastodon/mastodon) | Your self-hosted, globally interconnected microblogging community |
| [platforms](https://github.com/vercel/platforms) | A full-stack Next.js app with multi-tenancy and custom domain support. Built with Next.js App Router and the Vercel Domains API. |
| [MobileSAM](https://github.com/ChaoningZhang/MobileSAM) | This is the official code for MobileSAM project that makes SAM lightweight for mobile applications and beyond! |
| [Chat2DB](https://github.com/chat2db/Chat2DB) | 🔥 🔥 🔥 An intelligent and versatile general-purpose SQL client and reporting tool for databases which integrates ChatGPT capabilities.(智能的通用数据库SQL客户端和报表工具) |
| [system-design-primer](https://github.com/donnemartin/system-design-primer) | Learn how to design large-scale systems. Prep for the system design interview. Includes Anki flashcards. |
| [ChatGLM-Efficient-Tuning](https://github.com/hiyouga/ChatGLM-Efficient-Tuning) | Fine-tuning ChatGLM-6B with PEFT | 基于 PEFT 的高效 ChatGLM 微调 |
| [public-apis](https://github.com/public-apis/public-apis) | A collective list of free APIs |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | 12 Weeks, 24 Lessons, AI for All! |
| [ali-dbhub](https://github.com/alibaba/ali-dbhub) | 🔥 🔥 🔥 An intelligent and versatile general-purpose SQL client and reporting tool for databases which integrates ChatGPT capabilities.(智能的通用数据库SQL客户端和报表工具) |
| [gpt4free-ts](https://github.com/xiangsx/gpt4free-ts) | Providing a free OpenAI GPT-4 API ! This is a replication project for the typescript version of xtekky/gpt4free |
| [intel-one-mono](https://github.com/intel/intel-one-mono) | Intel One Mono font repository |
| [lemmy](https://github.com/LemmyNet/lemmy) | 🐀 A link aggregator and forum for the fediverse |
| [tinygrad](https://github.com/tinygrad/tinygrad) | You like pytorch? You like micrograd? You love tinygrad! ❤️ |
| [Whisky](https://github.com/IsaacMarovitz/Whisky) | A modern Wine wrapper for macOS built with SwiftUI |
| [svelte](https://github.com/sveltejs/svelte) | Cybernetically enhanced web apps |
| [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) | <⚡️> SuperAGI - A dev-first open source autonomous AI agent framework. Enabling developers to build, manage & run useful autonomous agents quickly and reliably. |
| [invidious](https://github.com/iv-org/invidious) | Invidious is an alternative front-end to YouTube |
<!-- END OF MONTHLY_TOP10_REPOS -->
