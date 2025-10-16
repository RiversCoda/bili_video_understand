# 一个简单的不限量的AI总结b站视频详细工作流
## step1: 视频下载：BilibiliDown——视频下载工具（可以直接下载音频）
[https://github.com/nICEnnnnnnnLee/BilibiliDown](https://github.com/nICEnnnnnnnLee/BilibiliDown)

## step2: 语音转文字：AsrTools——AI视频语音提取文字
- 通过这个工具提取下载视频中的语音
[https://github.com/WEIFENG2333/AsrTools](https://github.com/WEIFENG2333/AsrTools)

## step3: AI总结文档
通过VSCode Copilot(agent)或Cursor(agent)或直接在各家LLM网页Gemini, GPT, Deepseek, 千问, 豆包...上进行视频内容总结。
可以参考如下prompt

**prompt:**
文档是来自视频提取音频识别的的文本内容，主题是XXX，请为我总结出一份提纲文档和一份。（文本由于是AI语音转录稿，如果存在一些语句不通顺或错别字，请修正）
--------------------------------
