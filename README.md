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
| [aidea](https://github.com/mylxsw/aidea) | AIdea 是一款支持 GPT 以及国产大语言模型通义千问、文心一言等，支持 Stable Diffusion 文生图、图生图、 SDXL1.0、超分辨率、图片上色的全能型 APP。 |
| [nougat](https://github.com/facebookresearch/nougat) | Implementation of Nougat Neural Optical Understanding for Academic Documents |
| [magic-edit](https://github.com/magic-research/magic-edit) | MagicEdit: High-Fidelity Temporally Coherent Video Editing |
| [AspNetCoreDiagnosticScenarios](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios) | This repository has examples of broken patterns in ASP.NET Core applications |
| [ntfy](https://github.com/binwiederhier/ntfy) | Send push notifications to your phone or desktop using PUT/POST |
| [rust-course](https://github.com/sunface/rust-course) | “连续六年成为全世界最受喜爱的语言，无 GC 也无需手动内存管理、极高的性能和安全性、过程/OO/函数式编程、优秀的包管理、JS 未来基石" — 工作之余的第二语言来试试 Rust 吧。<<Rust语言圣经>>拥有全面且深入的讲解、生动贴切的示例、德芙般丝滑的内容，甚至还有JS程序员关注的 WASM 和 Deno 等专题。这可能是目前最用心的 Rust 中文学习教程 / Book |
| [public-apis](https://github.com/public-apis/public-apis) | A collective list of free APIs |
| [VcenterKit](https://github.com/W01fh4cker/VcenterKit) | Vcenter综合渗透利用工具包 | Vcenter Comprehensive Penetration and Exploitation Toolkit |
| [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter) | The image prompt adapter is designed to enable a pretrained text-to-image diffusion model to generate images with image prompt. |
| [HelloGitHub](https://github.com/521xueweihan/HelloGitHub) | 分享 GitHub 上有趣、入门级的开源项目。Share interesting, entry-level open source projects on GitHub. |
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
| [MetaGPT](https://github.com/geekan/MetaGPT) | 🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo |
| [ToolBench](https://github.com/OpenBMB/ToolBench) | An open platform for training, serving, and evaluating large language model for tool learning. |
| [awesome-english-ebooks](https://github.com/hehonghui/awesome-english-ebooks) | 经济学人(含音频)、纽约客、卫报、连线、大西洋月刊等英语杂志免费下载,支持epub、mobi、pdf格式, 每周更新 |
| [nextui](https://github.com/nextui-org/nextui) | 🚀 Beautiful, fast and modern React UI library. |
| [gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting) | Original reference implementation of "3D Gaussian Splatting for Real-Time Radiance Field Rendering" |
| [sweep](https://github.com/sweepai/sweep) | Sweep: AI-powered Junior Developer for small features and bug fixes. |
| [one-api](https://github.com/songquanpeng/one-api) | OpenAI 接口管理 & 分发系统，支持 Azure、Anthropic Claude、Google PaLM 2、智谱 ChatGLM、百度文心一言、讯飞星火认知、阿里通义千问以及 360 智脑，可用于二次分发管理 key，仅单可执行文件，已打包好 Docker 镜像，一键部署，开箱即用. OpenAI key management & redistribution system, using a single API for all LLMs, and features an English UI. |
| [FastGPT](https://github.com/labring/FastGPT) | FastGPT is a knowledge-based question answering system built on the LLM. It offers out-of-the-box data processing and model invocation capabilities. Moreover, it allows for workflow orchestration through Flow visualization, thereby enabling complex question and answer scenarios! |
| [Python](https://github.com/TheAlgorithms/Python) | All Algorithms implemented in Python |
| [rift](https://github.com/morph-labs/rift) | Rift: an AI-native language server for your personal AI software engineer |
<!-- END OF MONTHLY_TOP10_REPOS -->
