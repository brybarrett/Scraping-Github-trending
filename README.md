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
| [fabric](https://github.com/danielmiessler/fabric) | fabric is an open-source framework for augmenting humans using AI. |
| [excelCPU](https://github.com/InkboxSoftware/excelCPU) | 16-bit CPU for Excel, and related files |
| [LLaVA](https://github.com/haotian-liu/LLaVA) | [NeurIPS'23 Oral] Visual Instruction Tuning (LLaVA) built towards GPT-4V level capabilities and beyond. |
| [my-tv](https://github.com/lizongying/my-tv) | 我的电视 电视直播软件，安装即可使用 |
| [InstantID](https://github.com/InstantID/InstantID) | InstantID : Zero-shot Identity-Preserving Generation in Seconds 🔥 |
| [daily-code](https://github.com/code100x/daily-code) |  |
| [YOLO-World](https://github.com/AILab-CVC/YOLO-World) | Real-Time Open-Vocabulary Object Detection |
| [mlflow](https://github.com/mlflow/mlflow) | Open source platform for the machine learning lifecycle |
| [runner-images](https://github.com/actions/runner-images) | GitHub Actions runner images |
| [namada](https://github.com/anoma/namada) | Rust implementation of Namada, a Proof-of-Stake L1 for interchain asset-agnostic privacy |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch) | Implementing a ChatGPT-like LLM from scratch, step by step |
| [zed](https://github.com/zed-industries/zed) | Code at the speed of thought – Zed is a high-performance, multiplayer code editor from the creators of Atom and Tree-sitter. |
| [codellama](https://github.com/facebookresearch/codellama) | Inference code for CodeLlama models |
| [moondream](https://github.com/vikhyat/moondream) | tiny vision language model |
| [google-indexing-script](https://github.com/goenning/google-indexing-script) | Script to get your site indexed on Google in less than 48 hours |
| [palworld-server-docker](https://github.com/thijsvanloef/palworld-server-docker) | A Docker Container to easily run a Palworld dedicated server. |
| [palworld-save-tools](https://github.com/cheahjs/palworld-save-tools) | Tools for converting Palworld .sav files to JSON and back |
| [my-tv](https://github.com/lizongying/my-tv) | 我的电视 电视直播软件，安装即可使用 |
| [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) | 1 min voice data can also be used to train a good TTS model! (few shot voice cloning) |
| [InstantID](https://github.com/InstantID/InstantID) | InstantID : Zero-shot Identity-Preserving Generation in Seconds 🔥 |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [crewAI](https://github.com/joaomdmoura/crewAI) | Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly, tackling complex tasks. |
| [data-engineering-zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) | Free Data Engineering course! |
| [everyone-can-use-english](https://github.com/xiaolai/everyone-can-use-english) | 人人都能用英语 |
| [spotube](https://github.com/KRTirtho/spotube) | 🎧 Open source Spotify client that doesn't require Premium nor uses Electron! Available for both desktop & mobile! |
| [chatbot-ui](https://github.com/mckaywrigley/chatbot-ui) | The open-source AI chat app for everyone. |
| [jan](https://github.com/janhq/jan) | Jan is an open source alternative to ChatGPT that runs 100% offline on your computer |
| [1brc](https://github.com/gunnarmorling/1brc) | 1️⃣🐝🏎️ The One Billion Row Challenge -- A fun exploration of how quickly 1B rows from a text file can be aggregated with Java |
| [llm-course](https://github.com/mlabonne/llm-course) | Course to get into Large Language Models (LLMs) with roadmaps and Colab notebooks. |
| [ui](https://github.com/shadcn-ui/ui) | Beautifully designed components that you can copy and paste into your apps. Accessible. Customizable. Open Source. |
| [refine](https://github.com/refinedev/refine) | A React Framework for building internal tools, admin panels, dashboards & B2B apps with unmatched flexibility. |
<!-- END OF MONTHLY_TOP10_REPOS -->
