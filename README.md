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
| [rainfrog](https://github.com/achristmascarl/rainfrog) | 🐸 a database management tui for postgres |
| [DevOps-Bash-tools](https://github.com/HariSekhon/DevOps-Bash-tools) | 1000+ DevOps Bash Scripts - AWS, GCP, Kubernetes, Docker, CI/CD, APIs, SQL, PostgreSQL, MySQL, Hive, Impala, Kafka, Hadoop, Jenkins, GitHub, GitLab, BitBucket, Azure DevOps, TeamCity, Spotify, MP3, LDAP, Code/Build Linting, pkg mgmt for Linux, Mac, Python, Perl, Ruby, NodeJS, Golang, Advanced dotfiles: .bashrc, .vimrc, .gitconfig, .screenrc, tmux.. |
| [bootstrap](https://github.com/twbs/bootstrap) | The most popular HTML, CSS, and JavaScript framework for developing responsive, mobile first projects on the web. |
| [supervision](https://github.com/roboflow/supervision) | We write your reusable computer vision tools. 💜 |
| [folly](https://github.com/facebook/folly) | An open-source C++ library developed and used at Facebook. |
| [GDevelop](https://github.com/4ian/GDevelop) | 🎮 Open-source, cross-platform 2D/3D/multiplayer game engine designed for everyone. |
| [paimon](https://github.com/apache/paimon) | Apache Paimon is a lake format that enables building a Realtime Lakehouse Architecture with Flink and Spark for both streaming and batch operations. |
| [localstack](https://github.com/localstack/localstack) | 💻 A fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline |
| [unstract](https://github.com/Zipstack/unstract) | No-code LLM Platform to launch APIs and ETL Pipelines to structure unstructured documents |
| [cupy](https://github.com/cupy/cupy) | NumPy & SciPy for GPU |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [fish-speech](https://github.com/fishaudio/fish-speech) | Brand new TTS solution |
| [ecapture](https://github.com/gojue/ecapture) | Capturing SSL/TLS plaintext without a CA certificate using eBPF. Supported on Linux/Android kernels for amd64/arm64. |
| [paper-qa](https://github.com/Future-House/paper-qa) | High accuracy RAG for answering questions from scientific documents with citations |
| [ImHex](https://github.com/WerWolv/ImHex) | 🔍 A Hex Editor for Reverse Engineers, Programmers and people who value their retinas when working at 3 AM. |
| [Follow](https://github.com/RSSNext/Follow) | 🧡 Next generation information browser. |
| [duckstation](https://github.com/stenzek/duckstation) | Fast PlayStation 1 emulator for x86-64/AArch32/AArch64/RV64 |
| [expert_readed_books](https://github.com/0voice/expert_readed_books) | 2021年最新总结，推荐工程师合适读本，计算机科学，软件技术，创业，思想类，数学类，人物传记书籍 |
| [core](https://github.com/home-assistant/core) | 🏡 Open source home automation that puts local control and privacy first. |
| [super-productivity](https://github.com/johannesjo/super-productivity) | Super Productivity is an advanced todo list app with integrated Timeboxing and time tracking capabilities. It also comes with integrations for Jira, Gitlab, GitHub and Open Project. |
| [supervision](https://github.com/roboflow/supervision) | We write your reusable computer vision tools. 💜 |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [ecapture](https://github.com/gojue/ecapture) | Capturing SSL/TLS plaintext without a CA certificate using eBPF. Supported on Linux/Android kernels for amd64/arm64. |
| [Follow](https://github.com/RSSNext/Follow) | 🧡 Next generation information browser. |
| [courses](https://github.com/anthropics/courses) | Anthropic's educational courses |
| [firecrawl](https://github.com/mendableai/firecrawl) | 🔥 Turn entire websites into LLM-ready markdown or structured data. Scrape, crawl and extract with a single API. |
| [Docker-OSX](https://github.com/sickcodes/Docker-OSX) | Run macOS VM in a Docker! Run near native OSX-KVM in Docker! X11 Forwarding! CI/CD for OS X Security Research! Docker mac Containers. |
| [sherlock](https://github.com/sherlock-project/sherlock) | Hunt down social media accounts by username across social networks |
| [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) | Bring projects, wikis, and teams together with AI. AppFlowy is an AI collaborative workspace where you achieve more without losing control of your data. The best open source alternative to Notion. |
| [nocodb](https://github.com/nocodb/nocodb) | 🔥 🔥 🔥 Open Source Airtable Alternative |
| [linutil](https://github.com/ChrisTitusTech/linutil) | Chris Titus Tech's Linux Toolbox - Linutil is a distro-agnostic toolbox designed to simplify everyday Linux tasks. |
| [erpnext](https://github.com/frappe/erpnext) | Free and Open Source Enterprise Resource Planning (ERP) |
<!-- END OF MONTHLY_TOP10_REPOS -->
