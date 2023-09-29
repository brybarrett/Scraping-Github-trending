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
| [javascript](https://github.com/airbnb/javascript) | JavaScript Style Guide |
| [PowerToys](https://github.com/microsoft/PowerToys) | Windows system utilities to maximize productivity |
| [ColossalAI](https://github.com/hpcaitech/ColossalAI) | Making large AI models cheaper, faster and more accessible |
| [abp](https://github.com/abpframework/abp) | Open Source Web Application Framework for ASP.NET Core. Offers an opinionated architecture to build enterprise software solutions with best practices on top of the .NET and the ASP.NET Core platforms. Provides the fundamental infrastructure, production-ready startup templates, application modules, UI themes, tooling, guides and documentation. |
| [maui](https://github.com/dotnet/maui) | .NET MAUI is the .NET Multi-platform App UI, a framework for building native device applications spanning mobile, tablet, and desktop. |
| [datalens](https://github.com/datalens-tech/datalens) | A modern, scalable analytics system |
| [coding-interview-university](https://github.com/jwasham/coding-interview-university) | A complete computer science study plan to become a software engineer. |
| [autogen](https://github.com/microsoft/autogen) | Enable Next-Gen Large Language Model Applications. Join our Discord: https://discord.gg/pAbnFJrkgZ |
| [tiny-engine](https://github.com/opentiny/tiny-engine) | TinyEngine是一个低代码引擎，基于这个引擎可以构建或者开发出不同领域的低代码平台。 |
| [ollama](https://github.com/jmorganca/ollama) | Get up and running with Llama 2 and other large language models locally |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [agents](https://github.com/aiwaves-cn/agents) | An Open-source Framework for Autonomous Language Agents |
| [godot](https://github.com/godotengine/godot) | Godot Engine – Multi-platform 2D and 3D game engine |
| [pandora](https://github.com/zhile-io/pandora) | 潘多拉，一个让你呼吸顺畅的ChatGPT。Pandora, a ChatGPT client that lets you breathe freely. |
| [opentofu](https://github.com/opentofu/opentofu) | OpenTofu lets you declaratively manage your cloud infrastructure. |
| [TTS](https://github.com/coqui-ai/TTS) | 🐸💬 - a deep learning toolkit for Text-to-Speech, battle-tested in research and production |
| [plane](https://github.com/makeplane/plane) | 🔥 🔥 🔥 Open Source JIRA, Linear and Height Alternative. Plane helps you track your issues, epics, and product roadmaps in the simplest way possible. |
| [AgentVerse](https://github.com/OpenBMB/AgentVerse) | 🤖 AgentVerse 🪐 provides a flexible framework that simplifies the process of building custom multi-agent environments for large language models (LLMs). |
| [memos](https://github.com/usememos/memos) | A privacy-first, lightweight note-taking service. Easily capture and share your great thoughts |
| [bevy](https://github.com/bevyengine/bevy) | A refreshingly simple data-driven game engine built in Rust |
| [hysteria](https://github.com/apernet/hysteria) | Hysteria is a powerful, lightning fast and censorship resistant proxy. |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [bun](https://github.com/oven-sh/bun) | Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one |
| [hello-algo](https://github.com/krahets/hello-algo) | 《Hello 算法》：动画图解、一键运行的数据结构与算法教程，支持 Java, C++, Python, Go, JS, TS, C#, Swift, Rust, Dart, Zig 等语言。 |
| [gpt-pilot](https://github.com/Pythagora-io/gpt-pilot) | Dev tool that writes scalable apps from scratch while the developer oversees the implementation |
| [godot](https://github.com/godotengine/godot) | Godot Engine – Multi-platform 2D and 3D game engine |
| [codellama](https://github.com/facebookresearch/codellama) | Inference code for CodeLlama models |
| [facefusion](https://github.com/facefusion/facefusion) | Next generation face swapper and enhancer |
| [awesome-english-ebooks](https://github.com/hehonghui/awesome-english-ebooks) | 经济学人(含音频)、纽约客、卫报、连线、大西洋月刊等英语杂志免费下载,支持epub、mobi、pdf格式, 每周更新 |
| [TTS](https://github.com/coqui-ai/TTS) | 🐸💬 - a deep learning toolkit for Text-to-Speech, battle-tested in research and production |
| [gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting) | Original reference implementation of "3D Gaussian Splatting for Real-Time Radiance Field Rendering" |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | Focus on prompting and generating |
<!-- END OF MONTHLY_TOP10_REPOS -->
