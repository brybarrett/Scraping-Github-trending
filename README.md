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
| [llama-gpt](https://github.com/getumbrel/llama-gpt) | A self-hosted, offline, ChatGPT-like chatbot. Powered by Llama 2. 100% private, with no data leaving your device. |
| [CoDeF](https://github.com/qiuyu96/CoDeF) | Official PyTorch implementation of CoDeF: Content Deformation Fields for Temporally Consistent Video Processing |
| [stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp) | Stable Diffusion in pure C/C++ |
| [Python-100-Days](https://github.com/jackfrued/Python-100-Days) | Python - 100天从新手到大师 |
| [VPet](https://github.com/LorisYounger/VPet) | 虚拟桌宠模拟器 一个开源的桌宠软件, 可以内置到任何WPF应用程序 |
| [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) | Multi agent system for AI-driven software development. Convert natural language requirements into working software. Supports any development language and extends the existing base code. |
| [cal.com](https://github.com/calcom/cal.com) | Scheduling infrastructure for absolutely everyone. |
| [Grasscutter](https://github.com/Grasscutters/Grasscutter) | A server software reimplementation for a certain anime game. |
| [awesome-python](https://github.com/vinta/awesome-python) | A curated list of awesome Python frameworks, libraries, software and resources |
| [OldTweetDeck](https://github.com/dimdenGD/OldTweetDeck) | Returns old TweetDeck, for free! |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [generative_agents](https://github.com/joonspk-research/generative_agents) | Generative Agents: Interactive Simulacra of Human Behavior |
| [rift](https://github.com/morph-labs/rift) | Rift: an AI-native language server for your personal AI software engineer |
| [hackingtool](https://github.com/Z4nzu/hackingtool) | ALL IN ONE Hacking Tool For Hackers |
| [gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting) | Original reference implementation of "3D Gaussian Splatting for Real-Time Radiance Field Rendering" |
| [SpacetimeDB](https://github.com/clockworklabs/SpacetimeDB) | Multiplayer at the speed of light |
| [gpt-researcher](https://github.com/assafelovic/gpt-researcher) | GPT based autonomous agent that does online comprehensive research on any given topic |
| [quake2-rerelease-dll](https://github.com/id-Software/quake2-rerelease-dll) |  |
| [candle](https://github.com/huggingface/candle) | Minimalist ML framework for Rust |
| [themes](https://github.com/radix-ui/themes) | Radix Themes is an open-source component library optimized for fast development, easy maintenance, and accessibility. Maintained by @workos. |
| [1Panel](https://github.com/1Panel-dev/1Panel) | 🔥 🔥 🔥 现代化、开源的 Linux 服务器运维管理面板。 |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [MetaGPT](https://github.com/geekan/MetaGPT) | 🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo |
| [devops-exercises](https://github.com/bregman-arie/devops-exercises) | Linux, Jenkins, AWS, SRE, Prometheus, Docker, Python, Ansible, Git, Kubernetes, Terraform, OpenStack, SQL, NoSQL, Azure, GCP, DNS, Elastic, Network, Virtualization. DevOps Interview Questions |
| [TypeChat](https://github.com/microsoft/TypeChat) | TypeChat is a library that makes it easy to build natural language interfaces using types. |
| [ollama](https://github.com/jmorganca/ollama) | Get up and running with Llama 2 and other large language models locally |
| [Llama2-Chinese](https://github.com/FlagAlpha/Llama2-Chinese) | Llama中文社区，最好的中文Llama大模型，完全开源可商用 |
| [nextui](https://github.com/nextui-org/nextui) | 🚀 Beautiful, fast and modern React UI library. |
| [llama](https://github.com/facebookresearch/llama) | Inference code for LLaMA models |
| [ToolBench](https://github.com/OpenBMB/ToolBench) | An open platform for training, serving, and evaluating large language model for tool learning. |
| [ShortGPT](https://github.com/RayVentura/ShortGPT) | 🚀🎬 ShortGPT - Experimental AI framework for automated short/video content creation. |
| [web-check](https://github.com/Lissy93/web-check) | 🕵️‍♂️ All-in-one OSINT tool for analysing any website |
<!-- END OF MONTHLY_TOP10_REPOS -->
