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
| [dio-lab-open-source](https://github.com/elidianaandrade/dio-lab-open-source) | Repositório do lab Contribuindo em um Projeto Open Source no GitHub da Digital Innovation One. |
| [ml-fastvit](https://github.com/apple/ml-fastvit) | This repository contains the official implementation of the research paper, "FastViT: A Fast Hybrid Vision Transformer using Structural Reparameterization" |
| [canal](https://github.com/alibaba/canal) | 阿里巴巴 MySQL binlog 增量订阅&消费组件 |
| [VPet](https://github.com/LorisYounger/VPet) | 虚拟桌宠模拟器 一个开源的桌宠软件, 可以内置到任何WPF应用程序 |
| [si](https://github.com/systeminit/si) | The System Initiative software |
| [ubicloud](https://github.com/ubicloud/ubicloud) | Open, free, and portable cloud. Elastic compute, block storage (non replicated), and virtual networking services in public alpha. |
| [biomes-game](https://github.com/ill-inc/biomes-game) | Biomes is an open source sandbox MMORPG built for the web using web technologies such as Next.js, Typescript, React and WebAssembly. |
| [1Panel](https://github.com/1Panel-dev/1Panel) | 🔥 🔥 🔥 现代化、开源的 Linux 服务器运维管理面板。 |
| [KeymouseGo](https://github.com/taojy123/KeymouseGo) | 类似按键精灵的鼠标键盘录制和自动化操作 模拟点击和键入 | automate mouse clicks and keyboard input |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [MetaGPT](https://github.com/geekan/MetaGPT) | 🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo |
| [azurechatgpt](https://github.com/microsoft/azurechatgpt) | 🤖 Azure ChatGPT: Private & secure ChatGPT for internal enterprise use 💼 |
| [nextui](https://github.com/nextui-org/nextui) | 🚀 Beautiful, fast and modern React UI library. |
| [Qwen-7B](https://github.com/QwenLM/Qwen-7B) | The official repo of Qwen-7B (通义千问-7B) chat & pretrained large language model proposed by Alibaba Cloud. |
| [dioxus](https://github.com/DioxusLabs/dioxus) | Fullstack GUI library for desktop, web, mobile, and more. |
| [audiocraft](https://github.com/facebookresearch/audiocraft) | Audiocraft is a library for audio processing and generation with deep learning. It features the state-of-the-art EnCodec audio compressor / tokenizer, along with MusicGen, a simple and controllable music generation LM with textual and melodic conditioning. |
| [commerce](https://github.com/vercel/commerce) | Next.js Commerce |
| [FastGPT](https://github.com/labring/FastGPT) | FastGPT is a knowledge-based question answering system based on the LLM language model, providing out-of-the-box capabilities for data processing, model invocation, and more. It also allows for complex question answering scenarios through visual workflow orchestration using Flow! |
| [one-api](https://github.com/songquanpeng/one-api) | OpenAI 接口管理 & 分发系统，支持 Azure、Anthropic Claude、Google PaLM 2、智谱 ChatGLM、百度文心一言、讯飞星火认知以及阿里通义千问，可用于二次分发管理 key，仅单可执行文件，已打包好 Docker 镜像，一键部署，开箱即用. OpenAI key management & redistribution system, using a single API for all LLMs, and features an English UI. |
| [web-check](https://github.com/Lissy93/web-check) | 🌐 All-in-one OSINT tool for analysing any website |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [llama](https://github.com/facebookresearch/llama) | Inference code for LLaMA models |
| [MetaGPT](https://github.com/geekan/MetaGPT) | 🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo |
| [devops-exercises](https://github.com/bregman-arie/devops-exercises) | Linux, Jenkins, AWS, SRE, Prometheus, Docker, Python, Ansible, Git, Kubernetes, Terraform, OpenStack, SQL, NoSQL, Azure, GCP, DNS, Elastic, Network, Virtualization. DevOps Interview Questions |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | A powerful and modular stable diffusion GUI with a graph/nodes interface. |
| [nextui](https://github.com/nextui-org/nextui) | 🚀 Beautiful, fast and modern React UI library. |
| [free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 📚 Freely available programming books |
| [generative-models](https://github.com/Stability-AI/generative-models) | Generative Models by Stability AI |
| [livewire](https://github.com/livewire/livewire) | A full-stack framework for Laravel that takes the pain out of building dynamic UIs. |
| [ToolBench](https://github.com/OpenBMB/ToolBench) | An open platform for training, serving, and evaluating large language model for tool learning. |
| [The-Art-of-Linear-Algebra](https://github.com/kenjihiranabe/The-Art-of-Linear-Algebra) | Graphic notes on Gilbert Strang's "Linear Algebra for Everyone" |
<!-- END OF MONTHLY_TOP10_REPOS -->
