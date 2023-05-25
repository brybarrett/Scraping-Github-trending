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
| [fairseq](https://github.com/facebookresearch/fairseq) | Facebook AI Research Sequence-to-Sequence Toolkit written in Python. |
| [DragGAN](https://github.com/JiauZhang/DragGAN) | Implementation of DragGAN: Interactive Point-based Manipulation on the Generative Image Manifold |
| [comprehensive-rust](https://github.com/google/comprehensive-rust) | This is the Rust course used by the Android team at Google. It provides you the material to quickly teach Rust to everyone. |
| [EasySpider](https://github.com/NaiboWang/EasySpider) | A visual no-code/code-free web crawler/spider一个可视化爬虫软件，可以无代码图形化设计和执行的爬虫任务 |
| [voice-changer](https://github.com/w-okada/voice-changer) | リアルタイムボイスチェンジャー Realtime Voice Changer |
| [DragGAN](https://github.com/Zeqiang-Lai/DragGAN) | Workable implementation of "Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold" |
| [LaWGPT](https://github.com/pengxiao-song/LaWGPT) | 🎉 Repo for LaWGPT, Chinese-Llama tuned with Chinese Legal knowledge. 基于中文法律知识的大语言模型 |
| [tree-of-thoughts](https://github.com/kyegomez/tree-of-thoughts) | Plug in and Play Implementation of Tree of Thoughts: Deliberate Problem Solving with Large Language Models that Elevates Model Reasoning by atleast 70% |
| [next-enterprise](https://github.com/Blazity/next-enterprise) | 💼 An enterprise-grade Next.js boilerplate for high-performance, maintainable apps. Packed with features like Tailwind CSS, TypeScript, ESLint, Prettier, testing tools, and more to accelerate your development. |
| [joshuto](https://github.com/kamiyaa/joshuto) | ranger-like terminal file manager written in Rust |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [privateGPT](https://github.com/imartinez/privateGPT) | Interact privately with your documents using the power of GPT, 100% privately, no data leaks |
| [plugins-quickstart](https://github.com/openai/plugins-quickstart) | Get a ChatGPT plugin up and running in under 5 minutes! |
| [mlops-zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) | Free MLOps course from DataTalks.Club |
| [FlipperAmiibo](https://github.com/Gioman101/FlipperAmiibo) | Made to be used with Flipper just drag the folder into NFC |
| [LocalAI](https://github.com/go-skynet/LocalAI) | 🤖 Self-hosted, community-driven, local OpenAI-compatible API. Drop-in replacement for OpenAI running LLMs on consumer-grade hardware. No GPU required. LocalAI is a RESTful API to run ggml compatible models: llama.cpp, alpaca.cpp, gpt4all.cpp, rwkv.cpp, whisper.cpp, vicuna, koala, gpt4all-j, cerebras and many others! |
| [yuzu](https://github.com/yuzu-emu/yuzu) | Nintendo Switch Emulator |
| [epic-stack](https://github.com/epicweb-dev/epic-stack) | This is a Remix Stack with the foundational things setup and configured for you to hit the ground running on your next EPIC idea. |
| [Bard](https://github.com/acheong08/Bard) | Python SDK/API for reverse engineered Google Bard |
| [yuzu-mainline](https://github.com/yuzu-emu/yuzu-mainline) |  |
| [Digital_Life_Server](https://github.com/zixiiu/Digital_Life_Server) | Yet another voice assistant, but alive. |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [gpt4free](https://github.com/xtekky/gpt4free) | decentralising the Ai Industry, just some language model api's... |
| [bark](https://github.com/suno-ai/bark) | 🔊 Text-Prompted Generative Audio Model |
| [MOSS](https://github.com/OpenLMLab/MOSS) | An open-source tool-augmented conversational language model from Fudan University |
| [Flowise](https://github.com/FlowiseAI/Flowise) | Drag & drop UI to build your customized LLM flow using LangchainJS |
| [Ryujinx](https://github.com/Ryujinx/Ryujinx) | Experimental Nintendo Switch Emulator written in C# |
| [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork) | so-vits-svc fork with realtime support, improved interface and more features. |
| [plugins-quickstart](https://github.com/openai/plugins-quickstart) | Get a ChatGPT plugin up and running in under 5 minutes! |
| [pandora](https://github.com/pengzhile/pandora) | 潘多拉，一个让你呼吸顺畅的ChatGPT。Pandora, a ChatGPT that helps you breathe smoothly. |
| [WebGPT](https://github.com/0hq/WebGPT) | Run GPT model on the browser with WebGPU. An implementation of GPT inference in less than ~1500 lines of vanilla Javascript. |
| [so-vits-svc](https://github.com/svc-develop-team/so-vits-svc) | SoftVC VITS Singing Voice Conversion |
<!-- END OF MONTHLY_TOP10_REPOS -->
