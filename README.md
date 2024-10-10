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
| [Hyprland](https://github.com/hyprwm/Hyprland) | Hyprland is an independent, highly customizable, dynamic tiling Wayland compositor that doesn't sacrifice on its looks. |
| [generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | 21 Lessons, Get Started Building with Generative AI 🔗 https://microsoft.github.io/generative-ai-for-beginners/ |
| [platform](https://github.com/hcengineering/platform) | Huly — All-in-One Project Management Platform (alternative to Linear, Jira, Slack, Notion, Motion) |
| [zapret](https://github.com/bol-van/zapret) | DPI bypass multi platform |
| [JeecgBoot](https://github.com/jeecgboot/JeecgBoot) | 🔥「企业级低代码平台」前后端分离架构SpringBoot 2.x/3.x，SpringCloud，Ant Design&Vue3，Mybatis，Shiro，JWT。强大的代码生成器让前后端代码一键生成，无需写任何代码! 引领新的开发模式OnlineCoding->代码生成->手工MERGE，帮助Java项目解决70%重复工作，让开发更关注业务，既能快速提高效率，帮助公司节省成本，同时又不失灵活性。 |
| [supervision](https://github.com/roboflow/supervision) | We write your reusable computer vision tools. 💜 |
| [awesome-remote-job](https://github.com/lukasz-madon/awesome-remote-job) | A curated list of awesome remote jobs and resources. Inspired by https://github.com/vinta/awesome-python |
| [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) | GoodbyeDPI — Deep Packet Inspection circumvention utility (for Windows) |
| [kotaemon](https://github.com/Cinnamon/kotaemon) | An open-source RAG-based tool for chatting with your documents. |
| [dbeaver](https://github.com/dbeaver/dbeaver) | Free universal database tool and SQL client |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [crawl4ai](https://github.com/unclecode/crawl4ai) | 🔥🕷️ Crawl4AI: Open-source LLM Friendly Web Crawler & Scrapper |
| [screenpipe](https://github.com/mediar-ai/screenpipe) | 24/7 local AI screen & mic recording. Build AI apps that have the full context. Works with Ollama. Alternative to Rewind.ai. Open. Secure. You own your data. Rust. |
| [kestra](https://github.com/kestra-io/kestra) | ⚡ Open-source workflow automation platform. Orchestrate any language using YAML, hundreds of integrations. Alternative to Airflow, n8n, RunDeck, Camunda, Jenkins... |
| [exo](https://github.com/exo-explore/exo) | Run your own AI cluster at home with everyday devices 📱💻 🖥️⌚ |
| [100-exercises-to-learn-rust](https://github.com/mainmatter/100-exercises-to-learn-rust) | A self-paced course to learn Rust, one exercise at a time. |
| [maybe](https://github.com/maybe-finance/maybe) | The OS for your personal finances |
| [llama-stack](https://github.com/meta-llama/llama-stack) | Model components of the Llama Stack APIs |
| [OpenBB](https://github.com/OpenBB-finance/OpenBB) | Investment Research for Everyone, Everywhere. |
| [immich](https://github.com/immich-app/immich) | High performance self-hosted photo and video management solution. |
| [Python](https://github.com/TheAlgorithms/Python) | All Algorithms implemented in Python |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [llama-stack](https://github.com/meta-llama/llama-stack) | Model components of the Llama Stack APIs |
| [Follow](https://github.com/RSSNext/Follow) | 🧡 Next generation information browser. |
| [screenpipe](https://github.com/mediar-ai/screenpipe) | 24/7 local AI screen & mic recording. Build AI apps that have the full context. Works with Ollama. Alternative to Rewind.ai. Open. Secure. You own your data. Rust. |
| [fish-speech](https://github.com/fishaudio/fish-speech) | Brand new TTS solution |
| [ecapture](https://github.com/gojue/ecapture) | Capturing SSL/TLS plaintext without a CA certificate using eBPF. Supported on Linux/Android kernels for amd64/arm64. |
| [dice](https://github.com/DiceDB/dice) | DiceDB is a redis-compliant, in-memory, real-time, and reactive database optimized for modern hardware and building and scaling truly real-time applications. |
| [Pake](https://github.com/tw93/Pake) | 🤱🏻 Turn any webpage into a desktop app with Rust. 🤱🏻 利用 Rust 轻松构建轻量级多端桌面应用 |
| [kestra](https://github.com/kestra-io/kestra) | ⚡ Open-source workflow automation platform. Orchestrate any language using YAML, hundreds of integrations. Alternative to Airflow, n8n, RunDeck, Camunda, Jenkins... |
| [100-exercises-to-learn-rust](https://github.com/mainmatter/100-exercises-to-learn-rust) | A self-paced course to learn Rust, one exercise at a time. |
| [anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook) | A collection of notebooks/recipes showcasing some fun and effective ways of using Claude. |
<!-- END OF MONTHLY_TOP10_REPOS -->
