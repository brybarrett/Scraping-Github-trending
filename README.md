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
| [swarm](https://github.com/openai/swarm) | Educational framework exploring ergonomic, lightweight multi-agent orchestration. Managed by OpenAI Solution team. |
| [manim](https://github.com/3b1b/manim) | Animation engine for explanatory math videos |
| [manim](https://github.com/ManimCommunity/manim) | A community-maintained Python framework for creating mathematical animations. |
| [twenty](https://github.com/twentyhq/twenty) | Building a modern alternative to Salesforce, powered by the community. |
| [unkey](https://github.com/unkeyed/unkey) | Open source API management platform |
| [videos](https://github.com/3b1b/videos) | Code for the manim-generated scenes used in 3blue1brown videos |
| [hanko](https://github.com/teamhanko/hanko) | Authentication and User Management solution for developers. Open source alternative to Clerk & Auth0. |
| [papermark](https://github.com/mfts/papermark) | Papermark is the open-source DocSend alternative with built-in analytics and custom domains. |
| [platform](https://github.com/hcengineering/platform) | Huly — All-in-One Project Management Platform (alternative to Linear, Jira, Slack, Notion, Motion) |
| [hello-algo](https://github.com/krahets/hello-algo) | 《Hello 算法》：动画图解、一键运行的数据结构与算法教程。支持 Python, Java, C++, C, C#, JS, Go, Swift, Rust, Ruby, Kotlin, TS, Dart 代码。简体版和繁体版同步更新，English version ongoing |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [Python](https://github.com/TheAlgorithms/Python) | All Algorithms implemented in Python |
| [zapret](https://github.com/bol-van/zapret) | DPI bypass multi platform |
| [agents](https://github.com/livekit/agents) | Build real-time multimodal AI applications 🤖🎙️📹 |
| [Telegram-iOS](https://github.com/TelegramMessenger/Telegram-iOS) | Telegram-iOS |
| [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) | GoodbyeDPI — Deep Packet Inspection circumvention utility (for Windows) |
| [generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | 21 Lessons, Get Started Building with Generative AI 🔗 https://microsoft.github.io/generative-ai-for-beginners/ |
| [Java](https://github.com/TheAlgorithms/Java) | All Algorithms implemented in Java |
| [vnpy](https://github.com/vnpy/vnpy) | 基于Python的开源量化交易平台开发框架 |
| [gpt-pilot](https://github.com/Pythagora-io/gpt-pilot) | The first real AI developer |
| [rolldown](https://github.com/rolldown/rolldown) | Fast Rust bundler for JavaScript/TypeScript with Rollup-compatible API. |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [llama-stack](https://github.com/meta-llama/llama-stack) | Model components of the Llama Stack APIs |
| [crawl4ai](https://github.com/unclecode/crawl4ai) | 🔥🕷️ Crawl4AI: Open-source LLM Friendly Web Crawler & Scrapper |
| [Python](https://github.com/TheAlgorithms/Python) | All Algorithms implemented in Python |
| [Pake](https://github.com/tw93/Pake) | 🤱🏻 Turn any webpage into a desktop app with Rust. 🤱🏻 利用 Rust 轻松构建轻量级多端桌面应用 |
| [kestra](https://github.com/kestra-io/kestra) | ⚡ Workflow Automation Platform. Orchestrate & Schedule code in any language, run anywhere, 500+ plugins. Alternative to Zapier, Rundeck, Camunda, Airflow... |
| [dice](https://github.com/DiceDB/dice) | DiceDB is a redis-compliant, in-memory, real-time, and reactive database optimized for modern hardware and for building and scaling truly real-time applications. |
| [supervision](https://github.com/roboflow/supervision) | We write your reusable computer vision tools. 💜 |
| [anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook) | A collection of notebooks/recipes showcasing some fun and effective ways of using Claude. |
| [fish-speech](https://github.com/fishaudio/fish-speech) | Brand new TTS solution |
| [ecapture](https://github.com/gojue/ecapture) | Capturing SSL/TLS plaintext without a CA certificate using eBPF. Supported on Linux/Android kernels for amd64/arm64. |
<!-- END OF MONTHLY_TOP10_REPOS -->
