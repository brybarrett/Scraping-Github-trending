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
| [CVEProject/cvelistV5](https://github.com/CVEProject/cvelistV5) | CVE cache of the official CVE List in CVE JSON 5 format |
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | An AI Hedge Fund Team |
| [Anduin2017/HowToCook](https://github.com/Anduin2017/HowToCook) | 程序员在家做饭方法指南。Programmer's guide about how to cook at home (Simplified Chinese only). |
| [NirDiamant/RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques) | This repository showcases various advanced techniques for Retrieval-Augmented Generation (RAG) systems. RAG systems combine information retrieval with generative models to provide accurate and contextually rich responses. |
| [vanna-ai/vanna](https://github.com/vanna-ai/vanna) | 🤖 Chat with your SQL database 📊. Accurate Text-to-SQL Generation via LLMs using RAG 🔄. |
| [svcvit/Awesome-Dify-Workflow](https://github.com/svcvit/Awesome-Dify-Workflow) | 分享一些好用的 Dify DSL 工作流程，自用、学习两相宜。 Sharing some Dify workflows. |
| [SigmaHQ/sigma](https://github.com/SigmaHQ/sigma) | Main Sigma Rule Repository |
| [docmost/docmost](https://github.com/docmost/docmost) | Docmost is an open-source collaborative wiki and documentation software. It is an open-source alternative to Confluence and Notion. |
| [midday-ai/midday](https://github.com/midday-ai/midday) | Invoicing, Time tracking, File reconciliation, Storage, Financial Overview & your own Assistant made for Freelancers |
| [SimplifyJobs/New-Grad-Positions](https://github.com/SimplifyJobs/New-Grad-Positions) | A collection of full time roles in SWE, Quant, and PM for new grads. |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [yeongpin/cursor-free-vip](https://github.com/yeongpin/cursor-free-vip) | [Support 0.48.x]（Reset Cursor AI MachineID & Bypass Higher Token Limit） Cursor Ai ，自动重置机器ID ， 免费升级使用Pro功能: You've reached your trial request limit. / Too many free trial accounts used on this machine. Please upgrade to pro. We have this limit in place to prevent abuse. Please let us know if you believe this is a mistake. |
| [krillinai/KrillinAI](https://github.com/krillinai/KrillinAI) | A video translation and dubbing tool powered by LLMs, offering professional-grade translations and one-click full-process deployment. It can generate content optimized for platforms like YouTube，TikTok, and Shorts. 基于AI大模型的视频翻译和配音工具，专业级翻译，一键部署全流程，可以生成适配抖音，小红书，哔哩哔哩，视频号，TikTok，Youtube Shorts等形态的内容 |
| [CVEProject/cvelistV5](https://github.com/CVEProject/cvelistV5) | CVE cache of the official CVE List in CVE JSON 5 format |
| [Zackriya-Solutions/meeting-minutes](https://github.com/Zackriya-Solutions/meeting-minutes) | A free and open source, self hosted Ai based live meeting note taker and minutes summary generator that can completely run in your Local device (Mac OS and windows OS Support added. Working on adding linux support soon)https://meetily.zackriya.com/ |
| [vercel/ai-chatbot](https://github.com/vercel/ai-chatbot) | A full-featured, hackable Next.js AI chatbot built by Vercel |
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | An AI Hedge Fund Team |
| [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) | 10 Lessons to Get Started Building AI Agents |
| [maybe-finance/maybe](https://github.com/maybe-finance/maybe) | The OS for your personal finances |
| [funstory-ai/BabelDOC](https://github.com/funstory-ai/BabelDOC) | Yet Another Document Translator |
| [kestra-io/kestra](https://github.com/kestra-io/kestra) | ⚡ Workflow Automation Platform. Orchestrate & Schedule code in any language, run anywhere, 600+ plugins. Alternative to Airflow, VMware vRealize Automation, Rundeck... |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [yeongpin/cursor-free-vip](https://github.com/yeongpin/cursor-free-vip) | [Support 0.48.x]（Reset Cursor AI MachineID & Bypass Higher Token Limit） Cursor Ai ，自动重置机器ID ， 免费升级使用Pro功能: You've reached your trial request limit. / Too many free trial accounts used on this machine. Please upgrade to pro. We have this limit in place to prevent abuse. Please let us know if you believe this is a mistake. |
| [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | A collection of MCP servers. |
| [ahmedkhaleel2004/gitdiagram](https://github.com/ahmedkhaleel2004/gitdiagram) | Free, simple, fast interactive diagrams for any GitHub repository |
| [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) | 10 Lessons to Get Started Building AI Agents |
| [th-ch/youtube-music](https://github.com/th-ch/youtube-music) | YouTube Music Desktop App bundled with custom plugins (and built-in ad blocker / downloader) |
| [ageerle/ruoyi-ai](https://github.com/ageerle/ruoyi-ai) | RuoYi AI 是一个全栈式 AI 开发平台，旨在帮助开发者快速构建和部署个性化的 AI 应用。 |
| [hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam) | real time face swap and one-click video deepfake with only a single image |
| [ourongxing/newsnow](https://github.com/ourongxing/newsnow) | Elegant reading of real-time and hottest news |
| [n8n-io/n8n](https://github.com/n8n-io/n8n) | Fair-code workflow automation platform with native AI capabilities. Combine visual building with custom code, self-host or cloud, 400+ integrations. |
| [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) | Collection of awesome LLM apps with AI Agents and RAG using OpenAI, Anthropic, Gemini and opensource models. |
<!-- END OF MONTHLY_TOP10_REPOS -->
