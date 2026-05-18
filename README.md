# 🤖 AI Group Chat

> 让多个AI在同一个聊天室里"吵架"的Web应用

[![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5)](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4-blue?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

***

## 🎬 这是什么？

一个**单文件HTML应用**，让你可以同时与多个AI厂商的模型进行群聊。

想象一下：让GPT、Claude、Kimi、DeepSeek等坐在同一个聊天室里讨论问题，会碰撞出什么样的火花？💥

***

## ✨ 核心功能

### 🤖 AI 管理

| 功能 | 说明 |
|------|------|
| 💬 **多AI群聊** | 同时接入10+厂商，一键群发消息 |
| @️ **点名发言** | 输入 `@` 指定某个AI单独回应 |
| 🧠 **双模式切换** | 上下文联动 / 独立观点 两种模式 |
| ⚙️ **自定义配置** | 支持温度、Max Tokens、系统提示词设置 |
| 🔌 **API端点自定义** | 支持自定义API地址，兼容第三方代理 |

### 📊 数据统计

| 功能 | 说明 |
|------|------|
| 📊 **Token统计** | 实时追踪每个AI的消耗 |
| 💰 **费用估算** | 显示各厂商Token使用统计 |
| ⏱️ **讨论计时** | 自动记录讨论时长 |

### 💾 数据管理

| 功能 | 说明 |
|------|------|
| 📤 **导出记录** | 支持 Markdown / JSON / TXT 三种格式 |
| 🗑️ **清空记录** | 一键清空聊天记录和Token统计 |
| 💾 **本地存储** | 配置自动保存到浏览器本地 |

### 🎨 界面交互

| 功能 | 说明 |
|------|------|
| 🎨 **精美UI** | 暗色主题 + 毛玻璃效果 |
| 📱 **响应式设计** | 适配桌面和移动设备 |
| ⌨️ **快捷操作** | 支持@快捷键、回车发送 |
| 👤 **头像标识** | 每个AI都有独特的头像和颜色标识 |

***

## 🚀 快速开始

```bash
# 1. 克隆仓库
git clone https://github.com/zhy-ocean/ai-group-chat.git

# 2. 直接用浏览器打开
cd ai-group-chat
start ai-group-chat.html
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

|                                            厂商                                            | 特点    |
| :--------------------------------------------------------------------------------------: | :---- |
|    ![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai\&logoColor=white)    | 全能型选手 |
| ![Claude](https://img.shields.io/badge/Anthropic-D97757?logo=anthropic\&logoColor=white) | 编程推理强 |
|    ![Google](https://img.shields.io/badge/Gemini-4285F4?logo=google\&logoColor=white)    | 速度快   |
|   ![Moonshot](https://img.shields.io/badge/Kimi-8B5CF6?logo=moonshot\&logoColor=white)   | 长上下文  |
| ![DeepSeek](https://img.shields.io/badge/DeepSeek-00A1E0?logo=deepseek\&logoColor=white) | 推理专用  |
|                                           智谱AI                                           | 国产旗舰  |
|                                            豆包                                            | 字节出品  |
|                                          MiniMax                                         | 多语言强  |
|                                           通义千问                                           | 阿里出品  |

</div>

***

## 📖 使用技巧

### 💡 @点名功能

在输入框输入 `@` 会弹出AI列表，选择后只有该AI会回应。

**使用场景：**
- 想让特定AI补充观点
- 对比不同AI对同一问题的回答
- 控制讨论节奏，避免所有AI同时回复

### 🔄 模式切换

| 模式 | 适用场景 | 说明 |
|------|---------|------|
| **上下文联动** | 深度讨论、头脑风暴 | AI能看到完整对话历史，回答更有连贯性 |
| **独立观点** | 收集不同看法、对比测试 | AI只根据当前问题回答，观点更独立 |

### ⚙️ 参数调优

**温度 (Temperature)**
- `0.0-0.3`：更确定、更保守的回答
- `0.4-0.7`：平衡创造性和准确性（推荐）
- `0.8-1.0`：更有创意、更多样化的回答

**Max Tokens**
- 控制AI回复的最大长度
- 简单问题：1024-2048
- 复杂分析：4096-8192

### 🎯 高级玩法

**1. AI辩论赛**
- 添加多个AI，设置不同立场
- 使用上下文联动模式
- 让AI就某个话题展开辩论

**2. 代码评审**
- 添加擅长编程的AI（Claude、GPT-4）
- 粘贴代码，让AI从不同角度评审
- 对比各AI的优化建议

**3. 创意写作**
- 让不同AI续写同一个故事开头
- 使用独立观点模式
- 收集多样化的创意方向

**4. 知识验证**
- 向多个AI提问同一事实性问题
- 对比答案的一致性和准确性
- 识别可能的幻觉信息

### 📤 导出记录

点击右上角导出按钮，可选择：

| 格式 | 适用场景 | 特点 |
|------|---------|------|
| `Markdown` | 发布博客、文档存档 | 格式美观，支持标题、代码块 |
| `JSON` | 数据分析、程序处理 | 结构化数据，便于二次开发 |
| `TXT` | 简单备份、快速查看 | 纯文本，兼容性最好 |

### 💾 数据备份

- 配置自动保存在浏览器本地存储
- 清除浏览器数据会导致配置丢失
- 建议定期导出重要聊天记录

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

Made with ❤️ by [zhy-ocean](https://github.com/zhy-ocean)

⭐ 如果这个项目对你有帮助，请给个Star！

</div>
