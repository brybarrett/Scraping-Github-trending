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
| [gitbutler](https://github.com/gitbutlerapp/gitbutler) | The GitButler version control client, backed by Git, powered by Tauri/Rust/Svelte |
| [hurl](https://github.com/Orange-OpenSource/hurl) | Hurl, run and test HTTP requests with plain text. |
| [sudo](https://github.com/microsoft/sudo) | It's sudo, for Windows |
| [oblivion](https://github.com/bepass-org/oblivion) | Unofficial warp client for android |
| [llrt](https://github.com/awslabs/llrt) | LLRT (Low Latency Runtime) is an experimental, lightweight JavaScript runtime designed to address the growing demand for fast and efficient Serverless applications. |
| [LLM-Finetuning](https://github.com/ashishpatel26/LLM-Finetuning) | LLM Finetuning with peft |
| [pkl](https://github.com/apple/pkl) | A configuration as code language with rich validation and tooling. |
| [nushell](https://github.com/nushell/nushell) | A new type of shell |
| [awesome-tunneling](https://github.com/anderspitman/awesome-tunneling) | List of ngrok/Cloudflare Tunnel alternatives and other tunneling software and services. Focus on self-hosting. |
| [phidata](https://github.com/phidatahq/phidata) | Build AI Assistants using function calling |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [my-tv](https://github.com/lizongying/my-tv) | 我的电视 电视直播软件，安装即可使用 |
| [OLMo](https://github.com/allenai/OLMo) | Modeling, training, eval, and inference code for OLMo |
| [maybe](https://github.com/maybe-finance/maybe) | The OS for your personal finances |
| [MiniCPM](https://github.com/OpenBMB/MiniCPM) | MiniCPM-2B: An end-side LLM outperforms Llama2-13B. |
| [memos](https://github.com/usememos/memos) | An open source, lightweight note-taking service. Easily capture and share your great thoughts. |
| [fabric](https://github.com/danielmiessler/fabric) | fabric is an open-source framework for augmenting humans using AI. |
| [seaweedfs](https://github.com/seaweedfs/seaweedfs) | SeaweedFS is a fast distributed storage system for blobs, objects, files, and data lake, for billions of files! Blob store has O(1) disk seek, cloud tiering. Filer supports Cloud Drive, cross-DC active-active replication, Kubernetes, POSIX FUSE mount, S3 API, S3 Gateway, Hadoop, WebDAV, encryption, Erasure Coding. |
| [plura-production](https://github.com/webprodigies/plura-production) |  |
| [serenity](https://github.com/SerenityOS/serenity) | The Serenity Operating System 🐞 |
| [netbox](https://github.com/netbox-community/netbox) | The premier source of truth powering network automation. Open source under Apache 2. Public demo: https://demo.netbox.dev |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [raddebugger](https://github.com/EpicGames/raddebugger) | A native, user-mode, multi-process, graphical debugger. |
| [spotube](https://github.com/KRTirtho/spotube) | 🎧 Open source Spotify client that doesn't require Premium nor uses Electron! Available for both desktop & mobile! |
| [everyone-can-use-english](https://github.com/xiaolai/everyone-can-use-english) | 人人都能用英语 |
| [data-engineering-zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) | Free Data Engineering course! |
| [dspy](https://github.com/stanfordnlp/dspy) | DSPy: The framework for programming—not prompting—foundation models |
| [memos](https://github.com/usememos/memos) | An open source, lightweight note-taking service. Easily capture and share your great thoughts. |
| [crewAI](https://github.com/joaomdmoura/crewAI) | Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly, tackling complex tasks. |
| [extensions](https://github.com/keiyoushi/extensions) | Source extensions for the Mihon/Tachiyomi app. |
| [LibreChat](https://github.com/danny-avila/LibreChat) | Enhanced ChatGPT Clone: Features OpenAI, GPT-4 Vision, Mistral, Bing, Anthropic, OpenRouter, Google Gemini, AI model switching, message search, langchain, DALL-E-3, ChatGPT Plugins, OpenAI Functions, Secure Multi-User System, Presets, completely open-source for self-hosting. More features in development |
| [free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 📚 Freely available programming books |
<!-- END OF MONTHLY_TOP10_REPOS -->
