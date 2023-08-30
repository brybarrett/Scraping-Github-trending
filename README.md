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
| [polkadot-sdk](https://github.com/paritytech/polkadot-sdk) | The Parity Polkadot Blockchain SDK |
| [awesome-english-ebooks](https://github.com/hehonghui/awesome-english-ebooks) | 经济学人(含音频)、纽约客、卫报、连线、大西洋月刊等英语杂志免费下载,支持epub、mobi、pdf格式, 每周更新 |
| [VALL-E-X](https://github.com/Plachtaa/VALL-E-X) | An open source implementation of Microsoft's VALL-E X zero-shot TTS model. Demo is available in https://plachtaa.github.io |
| [Python](https://github.com/TheAlgorithms/Python) | All Algorithms implemented in Python |
| [CVE-2023-38831-winrar-exploit](https://github.com/b1tg/CVE-2023-38831-winrar-exploit) | CVE-2023-38831 winrar exploit generator |
| [Magisk](https://github.com/topjohnwu/Magisk) | The Magic Mask for Android |
| [WizardLM](https://github.com/nlpxucan/WizardLM) | Family of instruction-following LLMs powered by Evol-Instruct: WizardLM, WizardCoder and WizardMath |
| [wipeout-rewrite](https://github.com/phoboslab/wipeout-rewrite) |  |
| [continue](https://github.com/continuedev/continue) | ⏩ the open-source copilot chat for software development—bring the power of ChatGPT to VS Code |
| [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat) | The communications platform that puts data protection first. |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [llama-gpt](https://github.com/getumbrel/llama-gpt) | A self-hosted, offline, ChatGPT-like chatbot. Powered by Llama 2. 100% private, with no data leaving your device. |
| [gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting) | Original reference implementation of "3D Gaussian Splatting for Real-Time Radiance Field Rendering" |
| [biomes-game](https://github.com/ill-inc/biomes-game) | Biomes is an open source sandbox MMORPG built for the web using web technologies such as Next.js, Typescript, React and WebAssembly. |
| [AnimatedDrawings](https://github.com/facebookresearch/AnimatedDrawings) | Code to accompany "A Method for Animating Children's Drawings of the Human Figure" |
| [VPet](https://github.com/LorisYounger/VPet) | 虚拟桌宠模拟器 一个开源的桌宠软件, 可以内置到任何WPF应用程序 |
| [awesome-english-ebooks](https://github.com/hehonghui/awesome-english-ebooks) | 经济学人(含音频)、纽约客、卫报、连线、大西洋月刊等英语杂志免费下载,支持epub、mobi、pdf格式, 每周更新 |
| [SwifterSwift](https://github.com/SwifterSwift/SwifterSwift) | A handy collection of more than 500 native Swift extensions to boost your productivity. |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | Focus on prompting and generating |
| [rinha-de-backend-2023-q3](https://github.com/zanfranceschi/rinha-de-backend-2023-q3) | Rinha de Backend - Edição 2023 Q3 |
| [whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js) | A WhatsApp client library for NodeJS that connects through the WhatsApp Web browser app |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [devops-exercises](https://github.com/bregman-arie/devops-exercises) | Linux, Jenkins, AWS, SRE, Prometheus, Docker, Python, Ansible, Git, Kubernetes, Terraform, OpenStack, SQL, NoSQL, Azure, GCP, DNS, Elastic, Network, Virtualization. DevOps Interview Questions |
| [MetaGPT](https://github.com/geekan/MetaGPT) | 🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo |
| [nextui](https://github.com/nextui-org/nextui) | 🚀 Beautiful, fast and modern React UI library. |
| [gorilla](https://github.com/ShishirPatil/gorilla) | Gorilla: An API store for LLMs |
| [CodeGeeX2](https://github.com/THUDM/CodeGeeX2) | CodeGeeX2: A More Powerful Multilingual Code Generation Model |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | A powerful and modular stable diffusion GUI with a graph/nodes interface. |
| [gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting) | Original reference implementation of "3D Gaussian Splatting for Real-Time Radiance Field Rendering" |
| [audiocraft](https://github.com/facebookresearch/audiocraft) | Audiocraft is a library for audio processing and generation with deep learning. It features the state-of-the-art EnCodec audio compressor / tokenizer, along with MusicGen, a simple and controllable music generation LM with textual and melodic conditioning. |
| [one-api](https://github.com/songquanpeng/one-api) | OpenAI 接口管理 & 分发系统，支持 Azure、Anthropic Claude、Google PaLM 2、智谱 ChatGLM、百度文心一言、讯飞星火认知、阿里通义千问以及 360 智脑，可用于二次分发管理 key，仅单可执行文件，已打包好 Docker 镜像，一键部署，开箱即用. OpenAI key management & redistribution system, using a single API for all LLMs, and features an English UI. |
| [Python](https://github.com/TheAlgorithms/Python) | All Algorithms implemented in Python |
<!-- END OF MONTHLY_TOP10_REPOS -->
