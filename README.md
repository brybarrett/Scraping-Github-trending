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
| [microsoft/BitNet](https://github.com/microsoft/BitNet) | Official inference framework for 1-bit LLMs |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | Memory for AI Agents; SOTA in AI Agent Memory; Announcing OpenMemory MCP - local and secure memory management. |
| [airweave-ai/airweave](https://github.com/airweave-ai/airweave) | Airweave lets agents search any app |
| [alibaba/spring-ai-alibaba](https://github.com/alibaba/spring-ai-alibaba) | Agentic AI Framework for Java Developers |
| [openai/simple-evals](https://github.com/openai/simple-evals) |  |
| [ossu/computer-science](https://github.com/ossu/computer-science) | 🎓 Path to a free self-taught education in Computer Science! |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM. |
| [xming521/WeClone](https://github.com/xming521/WeClone) | 🚀从聊天记录创造数字分身的一站式解决方案💡 使用聊天记录微调大语言模型，让大模型有“那味儿”，并绑定到聊天机器人，实现自己的数字分身。 数字克隆/数字分身/数字永生/LLM/聊天机器人/LoRA |
| [i-am-alice/3rd-devs](https://github.com/i-am-alice/3rd-devs) |  |
| [ahmedkhaleel2004/gitdiagram](https://github.com/ahmedkhaleel2004/gitdiagram) | Free, simple, fast interactive diagrams for any GitHub repository |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM. |
| [voideditor/void](https://github.com/voideditor/void) |  |
| [GoogleCloudPlatform/kubectl-ai](https://github.com/GoogleCloudPlatform/kubectl-ai) | AI powered Kubernetes Assistant |
| [Lightricks/LTX-Video](https://github.com/Lightricks/LTX-Video) | Official repository for LTX-Video |
| [Blaizzy/mlx-audio](https://github.com/Blaizzy/mlx-audio) | A text-to-speech (TTS), speech-to-text (STT) and speech-to-speech (STS) library built on Apple's MLX framework, providing efficient speech analysis on Apple Silicon. |
| [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird) | Truly independent web browser |
| [MODSetter/SurfSense](https://github.com/MODSetter/SurfSense) | Open Source Alternative to NotebookLM / Perplexity / Glean, connected to external sources such as search engines (Tavily, Linkup), Slack, Linear, Notion, YouTube, GitHub and more. |
| [zed-industries/zed](https://github.com/zed-industries/zed) | Code at the speed of thought – Zed is a high-performance, multiplayer code editor from the creators of Atom and Tree-sitter. |
| [ruanyf/weekly](https://github.com/ruanyf/weekly) | 科技爱好者周刊，每周五发布 |
| [modular/modular](https://github.com/modular/modular) | The Modular Platform (includes MAX & Mojo) |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam) | real time face swap and one-click video deepfake with only a single image |
| [jujumilk3/leaked-system-prompts](https://github.com/jujumilk3/leaked-system-prompts) | Collection of leaked system prompts |
| [CVEProject/cvelistV5](https://github.com/CVEProject/cvelistV5) | CVE cache of the official CVE List in CVE JSON 5 format |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM. |
| [kamranahmedse/developer-roadmap](https://github.com/kamranahmedse/developer-roadmap) | Interactive roadmaps, guides and other educational content to help developers grow in their careers. |
| [getzep/graphiti](https://github.com/getzep/graphiti) | Build Real-Time Knowledge Graphs for AI Agents |
| [microsoft/markitdown](https://github.com/microsoft/markitdown) | Python tool for converting files and office documents to Markdown. |
| [QwenLM/Qwen3](https://github.com/QwenLM/Qwen3) | Qwen3 is the large language model series developed by Qwen team, Alibaba Cloud. |
| [simular-ai/Agent-S](https://github.com/simular-ai/Agent-S) | Agent S: an open agentic framework that uses computers like a human |
| [jlowin/fastmcp](https://github.com/jlowin/fastmcp) | 🚀 The fast, Pythonic way to build MCP servers and clients |
<!-- END OF MONTHLY_TOP10_REPOS -->
