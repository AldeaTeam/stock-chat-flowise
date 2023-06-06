# stock-chat-flowise
An LLM-backed chatbot regarding stocks, implemented by Flowise and Langchain JS. 

# How to make an LLM-backed app in minutes?
This repo is about building an LLM-backed app with low-code frameworks like Flowise (written in typescript) and Langflow (in python),  from the perspective of absolute beginners.

## Flowise experiment
Step 0 - Get an openAI api (or other supported api)

### Option 1 -  Local setup & development
For mac users with anaconda for package management, check node and npm version first. Make sure the node version is above 18.15.0.
In the terminal: 
```
node --version 
npm -version 
```

Next, install Flowise and start it via your local port

```
npm install -g flowise

npx flowise start
```

#### Next - Start building your app locally as LEGO game

Open [http://localhost:3000](http://localhost:3000/) and you'll see a workbench with all components from LangChain! Start this LEGO-like coding game and build what you want! 😄
You can load the **json file** from an interested project and load it into your workbench so to replicate anyone's effort in a minute.


### Option 2 - Deploy Flowise  to the cloud (recommended)
The official document provides several ways to deploy your app.
- Render, Railway, Replit.
	- Easier to implement but the data will be lost once the app restarts.
- AWS, DigitalOcean, GCP. 
	- More reliable but can be technically challenging. 

Here we'll test the render option. 
[Follow the instruction of document](https://docs.flowiseai.com/deployment/render) and the reference video as below. 

After deployment, the rest of LEGO coding is similar as local development.

#### Note - App can be instantly used as API or embed in website 😍 
See the screenshots in demo folder.

## 文科小白都能立即上手的大模型应用框架！

非常欢迎参与本开源项目的贡献！

### 补充项目背景
首先感谢开源社区 DataWhale的用心组织~ 让纯文科出身的Sarai同学（本项目的第一位贡献者）也萌发了搭建大模型应用的热情。

项目最初目标是参考Finchat等应用搭建具备本地PDF总结问答、web搜索总结等功能的股票分析助手，可选用多种LLM模型或商业API。

社区课程中推荐的LangChain是一个强大的框架，其提供了一套工具、组件和接口，可简化创建由大型语言模型 (LLM) 支持的app开发过程，并集成额外的资源，例如 API 和数据库等。

虽然Langchain已经很方便了，但对于非程序员来说还是有些麻烦（和恐惧）。对于不熟悉代码和或没时间折腾各种框架的小伙伴来说，通过UI直观拖拽组件、输入关键参数就能实现零代码开发专属gpt应用的开源框架简直就是天赐神器！

这里我们重点探索尝试了基于Langchain框架的开源项目Flowise和Langflow。
其中Flowise是typescript写的，Langflow是python写的，基本使用颇为相似。


### 补充学习资料
国内这方面的资源貌似还不是很多，视频资料请参考油管：
-  [官方学习资料](https://docs.flowiseai.com/how-to-use)
- [利用LangChain + Flowise 极速搭建LLM应用！【中文字幕】](https://www.bilibili.com/video/BV11N411C78d/?share_source=copy_web&vd_source=c9c1f384e015f340e2b21e0e3db13eb8)，
- [原油管链接](https://youtu.be/EsI_7L0fzKk)
- [对比Flowise和LangFlow【【中文字幕】】]( https://www.bilibili.com/video/BV1tW4y1R7d9/?share_source=copy_web&vd_source=c9c1f384e015f340e2b21e0e3db13eb8), 
- [原油管链接](https://youtu.be/OLuqTPofJ9g)

### 开发计划（暂定）
后续在此基础上进一步探索基于Langchain的低代码框架的应用潜力和优缺点。
同时类似功能使用Langchain + Streamlit等框架重写并对比效果。
期待大佬去这里 [GitHub - AldeaTeam/stock-chat-gpt](https://github.com/AldeaTeam/stock-chat-gpt) 贡献代码~~

### 致谢
感谢本组成员的积极参与和献言献策~ 特别感谢： https://github.com/kuangjunwei1, https://github.com/EricJiang0423
