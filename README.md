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
| [clash-nyanpasu](https://github.com/keiko233/clash-nyanpasu) | Clash Nyanpasu! |
| [generative-models](https://github.com/Stability-AI/generative-models) | Generative Models by Stability AI |
| [leetcode](https://github.com/doocs/leetcode) | 🔥LeetCode solutions in any programming language | 多种编程语言实现 LeetCode、《剑指 Offer（第 2 版）》、《程序员面试金典（第 6 版）》题解 |
| [Python-100-Days](https://github.com/jackfrued/Python-100-Days) | Python - 100天从新手到大师 |
| [generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | 12 Lessons, Get Started Building with Generative AI 🔗 https://microsoft.github.io/generative-ai-for-beginners/ |
| [starrocks](https://github.com/StarRocks/starrocks) | StarRocks, a Linux Foundation project, is a next-generation sub-second MPP OLAP database for full analytics scenarios, including multi-dimensional analytics, real-time analytics, and ad-hoc queries. InfoWorld’s 2023 BOSSIE Award for best open source software. |
| [uptime-kuma](https://github.com/louislam/uptime-kuma) | A fancy self-hosted monitoring tool |
| [flowty-realtime-lcm-canvas](https://github.com/flowtyone/flowty-realtime-lcm-canvas) | A realtime sketch to image demo using LCM and the gradio library. |
| [GitHub-Chinese-Top-Charts](https://github.com/GrowingGit/GitHub-Chinese-Top-Charts) | 🇨🇳 GitHub中文排行榜，各语言分设「软件 | 资料」榜单，精准定位中文好项目。各取所需，高效学习。 |
| [live](https://github.com/fanmingming/live) | ✯ 一个国内可直连的直播源分享项目 ✯ 🔕 永久免费 直连访问 完整开源 不含广告 完善的台标 直播源支持IPv4/IPv6双栈访问 🔕 |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [screenshot-to-code](https://github.com/abi/screenshot-to-code) | Drop in a screenshot and convert it to clean HTML/Tailwind/JS code |
| [gpt-crawler](https://github.com/BuilderIO/gpt-crawler) | Crawl a site to generate knowledge files to create your own custom GPT from a URL |
| [generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | 12 Lessons, Get Started Building with Generative AI 🔗 https://microsoft.github.io/generative-ai-for-beginners/ |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | Focus on prompting and generating |
| [tldraw](https://github.com/tldraw/tldraw) | a very good whiteboard |
| [eShop](https://github.com/dotnet/eShop) | A reference .NET application implementing an eCommerce site |
| [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) | AppFlowy is an open-source alternative to Notion. You are in charge of your data and customizations. Built with Flutter and Rust. |
| [Inferno](https://github.com/twostraws/Inferno) | Metal shaders for SwiftUI. |
| [Docker-OSX](https://github.com/sickcodes/Docker-OSX) | Run macOS VM in a Docker! Run near native OSX-KVM in Docker! X11 Forwarding! CI/CD for OS X Security Research! Docker mac Containers. |
| [clash-rev](https://github.com/MerlinKodo/clash-rev) | Continuation of Clash core project |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [clash-verge](https://github.com/zzzgydi/clash-verge) | A Clash GUI based on tauri. Supports Windows, macOS and Linux. |
| [ChatGLM3](https://github.com/THUDM/ChatGLM3) | ChatGLM3 series: Open Bilingual Chat LLMs | 开源双语对话语言模型 |
| [ML-For-Beginners](https://github.com/microsoft/ML-For-Beginners) | 12 weeks, 26 lessons, 52 quizzes, classic Machine Learning for all |
| [sing-box](https://github.com/SagerNet/sing-box) | The universal proxy platform |
| [generative-models](https://github.com/Stability-AI/generative-models) | Generative Models by Stability AI |
| [AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | 12 Weeks, 24 Lessons, AI for All! |
| [v2rayN](https://github.com/2dust/v2rayN) | A GUI client for Windows, support Xray core and v2fly core and others |
| [Xray-core](https://github.com/XTLS/Xray-core) | Xray, Penetrates Everything. Also the best v2ray-core, with XTLS support. Fully compatible configuration. |
| [udlbook](https://github.com/udlbook/udlbook) | Understanding Deep Learning - Simon J.D. Prince |
| [whisper](https://github.com/openai/whisper) | Robust Speech Recognition via Large-Scale Weak Supervision |
<!-- END OF MONTHLY_TOP10_REPOS -->
