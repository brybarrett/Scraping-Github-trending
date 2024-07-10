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
| [public-apis](https://github.com/public-apis/public-apis) | A collective list of free APIs |
| [CopilotKit](https://github.com/CopilotKit/CopilotKit) | A framework for building custom AI Copilots 🤖 in-app AI chatbots, in-app AI Agents, & AI-powered Textareas. |
| [hugo-book](https://github.com/alex-shpak/hugo-book) | Hugo documentation theme as simple as plain book |
| [system-design-primer](https://github.com/donnemartin/system-design-primer) | Learn how to design large-scale systems. Prep for the system design interview. Includes Anki flashcards. |
| [coding-interview-university](https://github.com/jwasham/coding-interview-university) | A complete computer science study plan to become a software engineer. |
| [project-based-learning](https://github.com/practical-tutorials/project-based-learning) | Curated list of project-based tutorials |
| [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | Master programming by recreating your favorite technologies from scratch. |
| [simplebank](https://github.com/techschool/simplebank) | Backend master class: build a simple bank service in Go |
| [vllm](https://github.com/vllm-project/vllm) | A high-throughput and memory-efficient inference and serving engine for LLMs |
| [vanna](https://github.com/vanna-ai/vanna) | 🤖 Chat with your SQL database 📊. Accurate Text-to-SQL Generation via LLMs using RAG 🔄. |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [ImHex](https://github.com/WerWolv/ImHex) | 🔍 A Hex Editor for Reverse Engineers, Programmers and people who value their retinas when working at 3 AM. |
| [gs-quant](https://github.com/goldmansachs/gs-quant) | Python toolkit for quantitative finance |
| [30-Days-Of-Python](https://github.com/Asabeneh/30-Days-Of-Python) | 30 days of Python programming challenge is a step-by-step guide to learn the Python programming language in 30 days. This challenge may take more than100 days, follow your own pace. These videos may help too: https://www.youtube.com/channel/UC7PNRuno1rzYPb1xLa4yktw |
| [fish-speech](https://github.com/fishaudio/fish-speech) | Brand new TTS solution |
| [generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | 18 Lessons, Get Started Building with Generative AI 🔗 https://microsoft.github.io/generative-ai-for-beginners/ |
| [whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js) | A WhatsApp client library for NodeJS that connects through the WhatsApp Web browser app |
| [serenity](https://github.com/SerenityOS/serenity) | The Serenity Operating System 🐞 |
| [theia](https://github.com/eclipse-theia/theia) | Eclipse Theia is a cloud & desktop IDE framework implemented in TypeScript. |
| [EasySpider](https://github.com/NaiboWang/EasySpider) | A visual no-code/code-free web crawler/spider易采集：一个可视化浏览器自动化测试/数据采集/爬虫软件，可以无代码图形化的设计和执行爬虫任务。别名：ServiceWrapper面向Web应用的智能化服务封装系统。 |
| [gpt4all](https://github.com/nomic-ai/gpt4all) | GPT4All: Chat with Local LLMs on Any Device |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [ImHex](https://github.com/WerWolv/ImHex) | 🔍 A Hex Editor for Reverse Engineers, Programmers and people who value their retinas when working at 3 AM. |
| [mi-gpt](https://github.com/idootop/mi-gpt) | 🏠 将小爱音箱接入 ChatGPT 和豆包，改造成你的专属语音助手。 |
| [generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | 18 Lessons, Get Started Building with Generative AI 🔗 https://microsoft.github.io/generative-ai-for-beginners/ |
| [coolify](https://github.com/coollabsio/coolify) | An open-source & self-hostable Heroku / Netlify / Vercel alternative. |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | The most powerful and modular stable diffusion GUI, api and backend with a graph/nodes interface. |
| [HowToCook](https://github.com/Anduin2017/HowToCook) | 程序员在家做饭方法指南。Programmer's guide about how to cook at home (Simplified Chinese only). |
| [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | Master programming by recreating your favorite technologies from scratch. |
| [30-Days-Of-Python](https://github.com/Asabeneh/30-Days-Of-Python) | 30 days of Python programming challenge is a step-by-step guide to learn the Python programming language in 30 days. This challenge may take more than100 days, follow your own pace. These videos may help too: https://www.youtube.com/channel/UC7PNRuno1rzYPb1xLa4yktw |
| [StableSwarmUI](https://github.com/Stability-AI/StableSwarmUI) | StableSwarmUI, A Modular Stable Diffusion Web-User-Interface, with an emphasis on making powertools easily accessible, high performance, and extensibility. |
| [Open-Sora](https://github.com/hpcaitech/Open-Sora) | Open-Sora: Democratizing Efficient Video Production for All |
<!-- END OF MONTHLY_TOP10_REPOS -->
