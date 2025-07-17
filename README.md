# UnityAITeam Framework

🎮 **专门为Unity游戏开发设计的多AI智能体协作框架**

## 项目概述

UnityAITeam是一个专门针对Unity游戏开发的AI协作框架，支持多个AI智能体在同一上下文下协作完成复杂的Unity游戏开发任务。

### 核心特性

- 🤖 **多AI智能体协作**: 支持5个专业AI智能体同时协作
- 🎨 **专业分工**: 游戏剧本、美术、场景设计、音频、特效专业团队
- 🔗 **Unity深度集成**: 基于UnityMCP工具直接操作Unity项目
- 📐 **6层架构**: 从UI到Unity集成的完整技术栈
- 🛠️ **基于AutoGen + CrewAI**: 混合架构设计

### 技术架构

```
L6: 用户交互层 (UI Layer)
L5: 工作流编排层 (Orchestration Layer)
L4: 知识管理层 (Knowledge Layer)
L3: 智能体协作层 (Agent Layer)
L2: 统一工具接口层 (Tool Interface Layer)
L1: Unity集成层 (Unity Integration Layer)
```

### 专业AI智能体

1. **游戏剧本智能体** - 故事情节、角色对话、任务设计
2. **美术智能体** - 视觉设计、UI/UX、材质纹理
3. **场景设计智能体** - 关卡设计、环境构建、物理设置
4. **音频智能体** - 背景音乐、音效、音频处理
5. **特效智能体** - 视觉特效、粒子系统、动画

## 快速开始

### 环境要求

- Unity 2022.3 LTS 或更高版本
- .NET 8.0
- Windows 10/11
- 支持的AI模型（OpenAI GPT、Anthropic Claude等）

### 安装

1. **下载框架**
   ```bash
   git clone https://github.com/JACKJOKE555/UnityAITeam-Framework.git
   cd UnityAITeam-Framework
   ```

2. **配置环境**
   - 安装Unity 2022.3 LTS
   - 配置AI模型API密钥
   - 安装.NET 8.0 SDK

3. **编译项目**
   ```bash
   dotnet build UnityAITeam.sln
   ```

### 5分钟体验

1. 启动UnityAITeam框架
2. 连接到Unity项目
3. 输入任务："为这个游戏创建一个森林场景，包含背景音乐和粒子特效"
4. 观察5个AI智能体协作完成任务

## 技术栈

- **框架**: AutoGen + CrewAI 混合架构
- **开发语言**: C# (.NET 8.0)
- **Unity集成**: UnityMCP工具
- **UI框架**: WPF + Material Design
- **AI模型**: 支持多种LLM (GPT-4, Claude等)

## 许可证

本项目采用MIT许可证。详见 [LICENSE](LICENSE) 文件。

## 联系我们

- 📧 邮箱: linjunjie2013@outlook.com
- 🐛 问题反馈: [GitHub Issues](https://github.com/JACKJOKE555/UnityAITeam-Framework/issues)
- 💡 功能建议: [GitHub Discussions](https://github.com/JACKJOKE555/UnityAITeam-Framework/discussions)

---

⭐ 如果这个项目对您有帮助，请给我们一个Star！

🎮 让AI团队助力您的Unity游戏开发之旅！