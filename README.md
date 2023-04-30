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
| [gpt4free](https://github.com/xtekky/gpt4free) | decentralising the Ai Industry, just some language model api's... |
| [AudioGPT](https://github.com/AIGC-Audio/AudioGPT) | AudioGPT: Understanding and Generating Speech, Music, Sound, and Talking Head |
| [thinkgpt](https://github.com/alaeddine-13/thinkgpt) | Agent techniques to augment your LLM and push it beyong its limits |
| [IF](https://github.com/deep-floyd/IF) |  |
| [NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | NeMo Guardrails is an open-source toolkit for easily adding programmable guardrails to LLM-based conversational systems. |
| [LocalAI](https://github.com/go-skynet/LocalAI) | 🤖 Self-hosted, community-driven simple local OpenAI-compatible API written in go. Can be used as a drop-in replacement for OpenAI, running on CPU with consumer-grade hardware. API for ggml compatible models, for instance: llama.cpp, alpaca.cpp, gpt4all.cpp, vicuna, koala, gpt4all-j, cerebras |
| [LLMsPracticalGuide](https://github.com/Mooler0410/LLMsPracticalGuide) |  |
| [Track-Anything](https://github.com/gaomingqi/Track-Anything) | Track-Anything is a flexible and interactive tool for video object tracking and segmentation, based on Segment Anything, XMem, and E2FGVI. |
| [Free-AUTO-GPT-with-NO-API](https://github.com/IntelligenzaArtificiale/Free-AUTO-GPT-with-NO-API) | Free AUTOGPT with NO API is a repository that offers a simple version of Autogpt, an autonomous AI agent capable of performing tasks independently. Unlike other versions, our implementation does not rely on any paid OpenAI API, making it accessible to anyone. |
| [jarvis](https://github.com/Priler/jarvis) | Voice assistant made as an experiment using neural networks for things like STT/TTS/Wake Word/NLU etc. |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [ColossalAI](https://github.com/hpcaitech/ColossalAI) | Making big AI models cheaper, easier, and more scalable |
| [EdgeGPT](https://github.com/acheong08/EdgeGPT) | Reverse engineered API of Microsoft's Bing Chat |
| [lowcode-engine](https://github.com/alibaba/lowcode-engine) | An enterprise-class low-code technology stack with scale-out design / 一套面向扩展设计的企业级低代码技术体系 |
| [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) | This repo includes ChatGPT prompt curation to use ChatGPT better. |
| [coreutils](https://github.com/uutils/coreutils) | Cross-platform Rust rewrite of the GNU coreutils |
| [node-chatgpt-api](https://github.com/waylaidwanderer/node-chatgpt-api) | A ChatGPT implementation with support for Bing's GPT-4 version of ChatGPT, plus the official ChatGPT model via OpenAI's API. Available as a Node.js module, REST API server, and CLI app. |
| [ChatGPT](https://github.com/acheong08/ChatGPT) | Reverse engineered ChatGPT API |
| [NvChad](https://github.com/NvChad/NvChad) | An attempt to make neovim cli functional like an IDE while being very beautiful, blazing fast startuptime |
| [mm-cot](https://github.com/amazon-science/mm-cot) | Official implementation for "Multimodal Chain-of-Thought Reasoning in Language Models" (stay tuned and more will be updated) |
| [wechat-chatgpt](https://github.com/fuergaosi233/wechat-chatgpt) | Use ChatGPT On Wechat via wechaty |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [instruct-pix2pix](https://github.com/timothybrooks/instruct-pix2pix) | None |
| [Open-Assistant](https://github.com/LAION-AI/Open-Assistant) | OpenAssistant is a chat-based assistant that understands tasks, can interact with third-party systems, and retrieve information dynamically to do so. |
| [ChatGPT](https://github.com/lencx/ChatGPT) | 🔮 ChatGPT Desktop Application (Mac, Windows and Linux) |
| [ColossalAI](https://github.com/hpcaitech/ColossalAI) | Making big AI models cheaper, easier, and more scalable |
| [nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero) | Neural Networks: Zero to Hero |
| [nuxt](https://github.com/nuxt/nuxt) | Nuxt is an intuitive and extendable way to create type-safe, performant and production-grade full-stack web apps and websites with Vue 3. |
| [LazyVim](https://github.com/LazyVim/LazyVim) | Neovim config for the lazy |
| [ChatGPT](https://github.com/acheong08/ChatGPT) | Reverse engineered ChatGPT API |
| [ChatGPT-wechat-bot](https://github.com/AutumnWhj/ChatGPT-wechat-bot) | ChatGPT for wechat https://github.com/AutumnWhj/ChatGPT-wechat-bot |
| [damus](https://github.com/damus-io/damus) | iOS nostr client |
<!-- END OF MONTHLY_TOP10_REPOS -->
