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
| [quivr](https://github.com/StanGirard/quivr) | 🧠 Dump all your files and chat with it using your Generative AI Second Brain using LLMs ( GPT 3.5/4, Private, Anthropic, VertexAI ) & Embeddings 🧠 |
| [threads-net](https://github.com/dmytrostriletskyi/threads-net) | Unofficial and reverse-engineered Threads (threads.net) Python API wrapper. Supports read and write capabilities. |
| [LongNet](https://github.com/kyegomez/LongNet) | Implementation of plug in and play Attention from "LongNet: Scaling Transformers to 1,000,000,000 Tokens" |
| [igl](https://github.com/facebook/igl) | Intermediate Graphics Library (IGL) is a cross-platform library that commands the GPU. It provides a single low-level cross-platform interface on top of various graphics APIs (e.g. OpenGL, Metal and Vulkan). |
| [chatbox](https://github.com/Bin-Huang/chatbox) | Chatbox is a desktop app for GPT/LLM that supports Windows, Mac, Linux & Web Online |
| [threads-api](https://github.com/junhoyeo/threads-api) | Unofficial, Reverse-Engineered Node.js/TypeScript client for Meta's Threads. Supports Read and Write. Web UI Included. |
| [The-Art-of-Linear-Algebra](https://github.com/kenjihiranabe/The-Art-of-Linear-Algebra) | Graphic notes on Gilbert Strang's "Linear Algebra for Everyone" |
| [long_llama](https://github.com/CStanKonrad/long_llama) | LongLLaMA is a large language model capable of handling long contexts. It is based on OpenLLaMA and fine-tuned with the Focused Transformer (FoT) method. |
| [roop](https://github.com/s0md3v/roop) | one-click deepfake (face swap) |
| [kafka-in-production](https://github.com/dttung2905/kafka-in-production) | 📚 Tech blogs & talks by companies that run Kafka in production |
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
