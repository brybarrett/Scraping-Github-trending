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
| [web-check](https://github.com/Lissy93/web-check) | 🕵️‍♂️ All-in-one OSINT tool for analysing any website |
| [uikit](https://github.com/pmndrs/uikit) | 📱 user interfaces for react-three-fiber |
| [WARP-Clash-API](https://github.com/vvbbnn00/WARP-Clash-API) | 该项目可以让你通过订阅的方式使用Cloudflare WARP+，自动获取流量。This project enables you to use Cloudflare WARP+ through subscription, automatically acquiring traffic. |
| [OpenCodeInterpreter](https://github.com/OpenCodeInterpreter/OpenCodeInterpreter) |  |
| [movie-web](https://github.com/movie-web/movie-web) | A small web app for watching movies and shows easily |
| [AFFiNE](https://github.com/toeverything/AFFiNE) | There can be more than Notion and Miro. AFFiNE(pronounced [ə‘fain]) is a next-gen knowledge base that brings planning, sorting and creating all together. Privacy first, open-source, customizable and ready to use. |
| [crewAI](https://github.com/joaomdmoura/crewAI) | Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly, tackling complex tasks. |
| [public-apis](https://github.com/public-apis/public-apis) | A collective list of free APIs |
| [tigerbeetle](https://github.com/tigerbeetle/tigerbeetle) | The distributed financial transactions database designed for mission critical safety and performance. |
| [taiko-mono](https://github.com/taikoxyz/taiko-mono) | A decentralized, Ethereum-equivalent ZK-Rollup. 🥁 |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [magika](https://github.com/google/magika) | Detect file content types with deep learning |
| [sherlock](https://github.com/sherlock-project/sherlock) | 🔎 Hunt down social media accounts by username across social networks |
| [uv](https://github.com/astral-sh/uv) | An extremely fast Python package installer and resolver, written in Rust. |
| [lobe-chat](https://github.com/lobehub/lobe-chat) | 🤯 Lobe Chat - an open-source, modern-design ChatGPT/LLMs UI/Framework. Supports speech-synthesis, multi-modal, and extensible plugin system. One-click FREE deployment of your private ChatGPT/Gemini/Ollama chat application. |
| [gptscript](https://github.com/gptscript-ai/gptscript) | Develop LLM Apps in Natural Language |
| [Langchain-Chatchat](https://github.com/chatchat-space/Langchain-Chatchat) | Langchain-Chatchat（原Langchain-ChatGLM）基于 Langchain 与 ChatGLM 等语言模型的本地知识库问答 | Langchain-Chatchat (formerly langchain-ChatGLM), local knowledge based LLM (like ChatGLM) QA app with langchain |
| [gopeed](https://github.com/GopeedLab/gopeed) | A modern download manager that supports all platforms. Built with Golang and Flutter. |
| [provisions-data](https://github.com/starknet-io/provisions-data) | Lists of eligible identities for Starknet provisions. |
| [StableCascade](https://github.com/Stability-AI/StableCascade) | Official Code for Stable Cascade |
| [stable-diffusion-webui-forge](https://github.com/lllyasviel/stable-diffusion-webui-forge) |  |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [fabric](https://github.com/danielmiessler/fabric) | fabric is an open-source framework for augmenting humans using AI. It provides a modular framework for solving specific problems using a crowdsourced set of AI prompts that can be used anywhere. |
| [maybe](https://github.com/maybe-finance/maybe) | The OS for your personal finances |
| [excelCPU](https://github.com/InkboxSoftware/excelCPU) | 16-bit CPU for Excel, and related files |
| [sherlock](https://github.com/sherlock-project/sherlock) | 🔎 Hunt down social media accounts by username across social networks |
| [zed](https://github.com/zed-industries/zed) | Code at the speed of thought – Zed is a high-performance, multiplayer code editor from the creators of Atom and Tree-sitter. |
| [web-check](https://github.com/Lissy93/web-check) | 🕵️‍♂️ All-in-one OSINT tool for analysing any website |
| [open-saas](https://github.com/wasp-lang/open-saas) | A free, open-source SaaS app starter for React & Node.js with superpowers. Production-ready. Community-driven. |
| [campus-imaotai](https://github.com/oddfar/campus-imaotai) | i茅台app自动预约，每日自动预约，支持docker一键部署（本项目不提供成品，使用的是已淘汰的算法） |
| [dspy](https://github.com/stanfordnlp/dspy) | DSPy: The framework for programming—not prompting—foundation models |
| [memos](https://github.com/usememos/memos) | An open source, lightweight note-taking service. Easily capture and share your great thoughts. |
<!-- END OF MONTHLY_TOP10_REPOS -->
