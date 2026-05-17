# 🤖 AI Group Chat

> 让多个AI在同一个聊天室里"吵架"的Web应用

[![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5)](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4-blue?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

***

## 🎬 这是什么？

一个**单文件HTML应用**，让你可以同时与多个AI厂商的模型进行群聊。

想象一下：让GPT-4、Claude、Kimi、DeepSeek坐在同一个聊天室里讨论问题，会碰撞出什么样的火花？💥

***

## ✨ 核心功能

| 功能             | 说明                       |
| -------------- | ------------------------ |
| 💬 **多AI群聊**   | 同时接入10+厂商，一键群发消息         |
| @️ **点名发言**    | 输入 `@` 指定某个AI单独回应        |
| 🧠 **双模式切换**   | 上下文联动 / 独立观点 两种模式        |
| 📊 **Token统计** | 实时追踪每个AI的消耗              |
| 📤 **导出记录**    | 支持 Markdown / JSON / TXT |
| 🎨 **精美UI**    | 暗色主题 + 毛玻璃效果             |

***

## 🚀 快速开始

```bash
# 1. 克隆仓库
git clone https://github.com/zhyace0/ai-group-chat.git

# 2. 直接用浏览器打开
cd ai-group-chat
start AI群聊plus-max-pro-06.html
```

或者直接把HTML文件拖到浏览器里打开即可！

***

## 🔧 配置AI

1. 点击左侧 **"+ 添加AI"**
2. 选择厂商（OpenAI / Claude / Kimi / ...）
3. 粘贴你的 **API Key**
4. 选择要使用的**模型**
5. 点击 **"激活"** 启用该AI

> 💡 **提示**：可以同时添加多个不同厂商的AI，实现"AI群聊"

***

## 🏢 支持的AI厂商

<div align="center">

|                                            厂商                                            | 旗舰模型              | 特点    |
| :--------------------------------------------------------------------------------------: | :---------------- | :---- |
|    ![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai\&logoColor=white)    | GPT-4.1           | 全能型选手 |
| ![Claude](https://img.shields.io/badge/Anthropic-D97757?logo=anthropic\&logoColor=white) | Claude 3.7 Sonnet | 编程推理强 |
|    ![Google](https://img.shields.io/badge/Gemini-4285F4?logo=google\&logoColor=white)    | Gemini 2.0 Flash  | 速度快   |
|   ![Moonshot](https://img.shields.io/badge/Kimi-8B5CF6?logo=moonshot\&logoColor=white)   | Kimi K2.5         | 长上下文  |
| ![DeepSeek](https://img.shields.io/badge/DeepSeek-00A1E0?logo=deepseek\&logoColor=white) | DeepSeek R1       | 推理专用  |
|                                           智谱AI                                           | GLM-4.7           | 国产旗舰  |
|                                            豆包                                            | Doubao-1.5 Pro    | 字节出品  |
|                                          MiniMax                                         | MiniMax-M2.1      | 多语言强  |
|                                           通义千问                                           | Qwen Max          | 阿里出品  |
|                                           Azure                                          | GPT-4             | 企业级   |

</div>

***

## 📖 使用技巧

### 💡 @点名功能

在输入框输入 `@` 会弹出AI列表，选择后只有该AI会回应。

### 🔄 模式切换

- **上下文联动**：AI能看到之前的对话，适合深度讨论
- **独立观点**：AI只回答当前问题，适合收集不同观点

### 📤 导出记录

点击右上角导出按钮，可选择：

- `Markdown` - 带格式的文档
- `JSON` - 结构化数据
- `TXT` - 纯文本

***

## ⚠️ 安全提醒

- 🔐 **API Key 仅在本地使用**，不会上传到任何服务器
- 🚫 **不要将包含API Key的文件提交到GitHub**
- 💾 建议定期备份聊天记录

***

## 🛠️ 技术栈

- **前端**：原生 HTML5 + Tailwind CSS (CDN)
- **图标**：Font Awesome 6
- **无后端**：纯前端实现，API直连厂商

***

## 📝 更新日志

### v1.0 (2025-05)

- ✅ 支持10+主流AI厂商
- ✅ 群聊 & @点名功能
- ✅ Token统计 & 记录导出
- ✅ 响应式暗色UI

***

## 🤝 贡献

欢迎提交 Issue 和 PR！

***

<div align="center">

Made with ❤️ by [zhyaceo](https://github.com/zhyace0)

⭐ 如果这个项目对你有帮助，请给个Star！

</div>
