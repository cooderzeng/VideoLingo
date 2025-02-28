<div align="center">

# 🌉 VideoLingo: 连接世界的每一帧
![Python](https://img.shields.io/badge/python-v3.12-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![GitHub stars](https://img.shields.io/github/stars/Huanshere/VideoLingo.svg)

[**中文**](README.md) | [**English**](README.en.md)

[**b站演示**](https://www.bilibili.com/video/BV1QsYXeGEPP/)

**QQ群：875297969**

</div>


## 🌟 能做什么

-  🍖 全自动视频搬运工，生成 Netflix 品质的字幕！

- 🎤 克隆自己的声音进行配音!

- ✨ 在 streamlit 中点击-完成！

> 看看效果吧！💪

https://github.com/user-attachments/assets/0f5d5878-bfa5-41e4-ade1-d2b81d925a7d

> 还可以用GPT-SoVITS配上自己的声音！

https://github.com/user-attachments/assets/e9833df3-236c-46da-ba6c-a9636947c48b

## 特点

- 使用 NLP 和 LLM 进行字幕分割

- 智能术语知识库，实现上下文感知翻译

- 三步翻译过程：直接翻译 - 反思 - 改进

- 精确的单词级字幕对齐

- 极低成本：仅需 0.1 元即可创作 5 分钟的跨语言字幕

- GPT-SoVits 高质量的个性化配音

- 开发者友好：逐步结构化文件，便于自定义 : [英文文档](./docs/README_guide_en.md) | [中文文档](./docs/README_guide_zh.md)（待更新）

## 硬件要求

- 在 Mac M1 Pro 16G 及 Windows RTX4060 上测试通过

## 如何使用

1. 下载一键启动包：[点击这里](https://pan.baidu.com/s/1bL2zorbs4OpzKC1Ctlh3JQ?pwd=6969)（仅限 Windows 未广泛测试，Mac 用户请从源码安装）

2. 配置 `config.py` 中的 api_key

3. 点击 `一键启动.bat` 启动 Streamlit！

<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/user-attachments/assets/4c41b498-574d-457b-80de-fefbede731e1" alt="Demo 1" width="45%" />
  <img src="https://github.com/user-attachments/assets/210ba9e6-1f8a-41d7-a8d5-d0d6fd96deea" alt="Demo 2" width="45%" />
</div>


## 安装

1. 克隆仓库：
   ```bash
   git clone https://github.com/Huanshere/VideoLingo.git
   cd VideoLingo
   ```

2. 设置并激活 Conda 虚拟环境：
   ```bash
   conda create -n videolingo python=3.12.0
   conda activate videolingo
   ```

3. 配置 `config.py`

4. 执行安装脚本：
   ```bash
   python install.py
   ```

5. 🎉启动streamlt!
   ```bash
   streamlit run st.py
   ```


## 🙏 致谢

感谢以下开源项目的贡献:

- [whisper](https://github.com/openai/whisper): OpenAI的开源自动语音识别系统
- [whisper-timestamped](https://github.com/linto-ai/whisper-timestamped): 为Whisper添加时间戳功能的扩展
- [yt-dlp](https://github.com/yt-dlp/yt-dlp): 用于下载YouTube视频和其他网站内容的命令行工具
- [GPT-SoVITS](https://github.com/RVC-Project/GPT-SoVITS) & [GPT-SoVITS-Inference](https://github.com/X-T-E-R/GPT-SoVITS-Inference): 基于GPT和SoVITS的语音合成系统及推理库
- [FFmpeg](https://github.com/FFmpeg/FFmpeg): 用于处理多媒体内容的完整��平台解决方案
- [Ultimate Vocal Remover GUI v5 (UVR5)](https://github.com/Anjok07/ultimatevocalremovergui): 用于分离音乐中的人声和伴奏的工具
- [json_repair](https://github.com/mangiucugna/json_repair): 超无敌的 修复解析 gpt 的 json 输出的库，无缝替代 json.loads
## Star 历史

[![Star 历史图表](https://api.star-history.com/svg?repos=Huanshere/VideoLingo&type=Timeline)](https://star-history.com/#Huanshere/VideoLingo)