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
| [gpt-fast](https://github.com/pytorch-labs/gpt-fast) | Simple and efficient pytorch-native transformer text generation in <1000 LOC of python. |
| [WeChatMsg](https://github.com/LC044/WeChatMsg) | 提取微信聊天记录，将其导出成HTML、Word、CSV文档永久保存，对聊天记录进行分析生成年度聊天报告 |
| [visual_anagrams](https://github.com/dangeng/visual_anagrams) | Code for the paper "Visual Anagrams: Generating Multi-View Optical Illusions with Diffusion Models" |
| [TaskWeaver](https://github.com/microsoft/TaskWeaver) | A code-first agent framework for seamlessly planning and executing data analytics tasks. |
| [llamafile](https://github.com/Mozilla-Ocho/llamafile) | Distribute and run LLMs with a single file. |
| [materials_discovery](https://github.com/google-deepmind/materials_discovery) |  |
| [self-operating-computer](https://github.com/OthersideAI/self-operating-computer) | A framework to enable multimodal models to operate a computer. |
| [quivr](https://github.com/StanGirard/quivr) | Your GenAI Second Brain 🧠 A personal productivity assistant ⚡️🤖 Chat with your files (PDF, CSV, ...) & apps using GPT 3.5 / 4 turbo, Private, Anthropic, VertexAI, Ollama, LLMs, that you can share with users ! Local & Private alternative to OpenAI GPTs & ChatGPT |
| [AnimateAnyone](https://github.com/HumanAIGC/AnimateAnyone) | Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation |
| [seamless_communication](https://github.com/facebookresearch/seamless_communication) | Foundational Models for State-of-the-Art Speech and Text Translation |
<!-- END OF DAILY_TOP10_REPOS -->

## 本周TOP10
<!-- START OF WEEKLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [GPTs](https://github.com/linexjlin/GPTs) | leaked prompts of GPTs |
| [multipleWindow3dScene](https://github.com/bgstaal/multipleWindow3dScene) | A quick example of how one can "synchronize" a 3d scene across multiple windows using three.js and localStorage |
| [chatgpt_system_prompt](https://github.com/LouisShark/chatgpt_system_prompt) | store all agent's system prompt |
| [rags](https://github.com/run-llama/rags) | Build ChatGPT over your data, all with natural language |
| [generative-models](https://github.com/Stability-AI/generative-models) | Generative Models by Stability AI |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | Focus on prompting and generating |
| [deploy](https://github.com/pandora-next/deploy) | Pandora Cloud + Pandora Server + Shared Chat + BackendAPI Proxy + Chat2API = PandoraNext. New GPTs(Gizmo) UI, All in one! |
| [json](https://github.com/nlohmann/json) | JSON for Modern C++ |
| [GitHub-Chinese-Top-Charts](https://github.com/GrowingGit/GitHub-Chinese-Top-Charts) | 🇨🇳 GitHub中文排行榜，各语言分设「软件 | 资料」榜单，精准定位中文好项目。各取所需，高效学习。 |
| [clash-nyanpasu](https://github.com/keiko233/clash-nyanpasu) | Clash Nyanpasu! (∠・ω< )⌒☆​ |
<!-- END OF WEEKLY_TOP10_REPOS -->

## 本月TOP10
<!-- START OF MONTHLY_TOP10_REPOS -->
| 名字 | 简介 |
| :----: | :----: |
| [generative-models](https://github.com/Stability-AI/generative-models) | Generative Models by Stability AI |
| [ML-For-Beginners](https://github.com/microsoft/ML-For-Beginners) | 12 weeks, 26 lessons, 52 quizzes, classic Machine Learning for all |
| [AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | 12 Weeks, 24 Lessons, AI for All! |
| [atomicals-js](https://github.com/atomicals/atomicals-js) | Atomicals CLI and Javascript Library |
| [smallchat](https://github.com/antirez/smallchat) | A minimal programming example for a chat server |
| [udlbook](https://github.com/udlbook/udlbook) | Understanding Deep Learning - Simon J.D. Prince |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | Focus on prompting and generating |
| [openai-python](https://github.com/openai/openai-python) | The official Python library for the OpenAI API |
| [ollama](https://github.com/jmorganca/ollama) | Get up and running with Llama 2 and other large language models locally |
| [whisper](https://github.com/openai/whisper) | Robust Speech Recognition via Large-Scale Weak Supervision |
<!-- END OF MONTHLY_TOP10_REPOS -->
