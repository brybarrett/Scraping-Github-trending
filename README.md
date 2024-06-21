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
| [LibreChat](https://github.com/danny-avila/LibreChat) | Enhanced ChatGPT Clone: Features OpenAI, Assistants API, Azure, Groq, GPT-4 Vision, Mistral, Bing, Anthropic, OpenRouter, Vertex AI, Gemini, AI model switching, message search, langchain, DALL-E-3, ChatGPT Plugins, OpenAI Functions, Secure Multi-User System, Presets, completely open-source for self-hosting. More features in development |
| [Open-Sora](https://github.com/hpcaitech/Open-Sora) | Open-Sora: Democratizing Efficient Video Production for All |
| [rustdesk](https://github.com/rustdesk/rustdesk) | An open-source remote desktop, and alternative to TeamViewer. |
| [omnivore](https://github.com/omnivore-app/omnivore) | Omnivore is a complete, open source read-it-later solution for people who like reading. |
| [supersonic](https://github.com/tencentmusic/supersonic) | SuperSonic is the next-generation BI platform that integrates Chat BI (powered by LLM) and Headless BI (powered by semantic layer) paradigms. |
| [aimoneyhunter](https://github.com/bleedline/aimoneyhunter) | ai副业赚钱大集合，教你如何利用ai做一些副业项目，赚取更多额外收益。The Ultimate Guide to Making Money with AI Side Hustles: Learn how to leverage AI for some cool side gigs and rake in some extra cash. Check out the English version for more insights. |
| [1brc](https://github.com/gunnarmorling/1brc) | 1️⃣🐝🏎️ The One Billion Row Challenge -- A fun exploration of how quickly 1B rows from a text file can be aggregated with Java |
| [project-based-learning](https://github.com/practical-tutorials/project-based-learning) | Curated list of project-based tutorials |
| [MaxKB](https://github.com/1Panel-dev/MaxKB) | 🚀 基于 LLM 大语言模型的知识库问答系统。开箱即用，支持快速嵌入到第三方业务系统，1Panel 官方出品。 |
| [tensorflow](https://github.com/tensorflow/tensorflow) | An Open Source Machine Learning Framework for Everyone |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [mi-gpt](https://github.com/idootop/mi-gpt) | 🏠 将小爱音箱接入 ChatGPT 和豆包，改造成你的专属语音助手。 |
| [coolify](https://github.com/coollabsio/coolify) | An open-source & self-hostable Heroku / Netlify / Vercel alternative. |
| [transformers.js](https://github.com/xenova/transformers.js) | State-of-the-art Machine Learning for the web. Run 🤗 Transformers directly in your browser, with no need for a server! |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | The most powerful and modular stable diffusion GUI, api and backend with a graph/nodes interface. |
| [LazyVim](https://github.com/LazyVim/LazyVim) | Neovim config for the lazy |
| [aider](https://github.com/paul-gauthier/aider) | aider is AI pair programming in your terminal |
| [immich](https://github.com/immich-app/immich) | High performance self-hosted photo and video management solution. |
| [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh) | The most customisable and low-latency cross platform/shell prompt renderer |
| [dspy](https://github.com/stanfordnlp/dspy) | DSPy: The framework for programming—not prompting—foundation models |
| [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | Master programming by recreating your favorite technologies from scratch. |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [fabric](https://github.com/danielmiessler/fabric) | fabric is an open-source framework for augmenting humans using AI. It provides a modular framework for solving specific problems using a crowdsourced set of AI prompts that can be used anywhere. |
| [MiniCPM-V](https://github.com/OpenBMB/MiniCPM-V) | MiniCPM-Llama3-V 2.5: A GPT-4V Level Multimodal LLM on Your Phone |
| [LazyVim](https://github.com/LazyVim/LazyVim) | Neovim config for the lazy |
| [coolify](https://github.com/coollabsio/coolify) | An open-source & self-hostable Heroku / Netlify / Vercel alternative. |
| [java-design-patterns](https://github.com/iluwatar/java-design-patterns) | Design patterns implemented in Java |
| [bulletproof-react](https://github.com/alan2207/bulletproof-react) | 🛡️ ⚛️ A simple, scalable, and powerful architecture for building production ready React applications. |
| [EasySpider](https://github.com/NaiboWang/EasySpider) | A visual no-code/code-free web crawler/spider易采集：一个可视化浏览器自动化测试/数据采集/爬虫软件，可以无代码图形化的设计和执行爬虫任务。别名：ServiceWrapper面向Web应用的智能化服务封装系统。 |
| [cognita](https://github.com/truefoundry/cognita) | RAG (Retrieval Augmented Generation) Framework for building modular, open source applications for production by TrueFoundry |
| [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | Master programming by recreating your favorite technologies from scratch. |
| [nocobase](https://github.com/nocobase/nocobase) | NocoBase is a scalability-first, open-source no-code/low-code platform for building business applications and enterprise solutions. |
<!-- END OF MONTHLY_TOP10_REPOS -->
