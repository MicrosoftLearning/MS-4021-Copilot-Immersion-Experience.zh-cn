---
task:
  title: 沉浸式体验 - 智能体（业务用户）
---

## 沉浸式体验 - 智能体（业务用户）

通过设计一个简单的基于检索的智能体，了解 Microsoft 365 Copilot 和 Copilot Studio 如何帮助你解决日常工作中的高效工作难题****。 此简化的练习将引导你完成以下步骤：识别一个常见问题、探索 AI 可提供的帮助，以及创建一个简单的智能体进行测试。  

你将执行三个任务：

- 识别一个高效工作痛点  
- 了解 AI 在检索与整理方面可提供的帮助  
- 在 Copilot Studio 中生成和测试简单的智能体  

> **注意：** 已提供示例提示帮助你快速上手，你可根据自身情况灵活调整，使其更贴合你的实际需求。  
>
> 如果你需要协助生成或优化提示，可尝试使用提示指导智能体。该智能体能够提供提示建议、优化提示质量并评估提示效果，帮助你通过 Copilot 获得更优结果<a href="https://appsource.microsoft.com/en-us/product/office/WA200007578" target="_blank"></a>。

### 任务 1：识别一个高效工作难题  

请思考你日常工作中一个常见的问题 - 某个会拖慢你工作进度、或是让信息查找或整理变得更困难的问题。 你可以独立思考，也可以将 Copilot 对话助手作为合作伙伴，帮助激发思路并梳理常见痛点。

示例：

- 查找最新版本的文档  
- 从多个电子邮件或聊天中收集更新  
- 记住过去项目或会议中的详细信息  

**步骤：**  

- 打开新的浏览器选项卡并导航到 [m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat)。 

- 确保 Copilot 对话助手中已选择“工作模式”选项卡********。  

   ![显示 Copilot 对话助手中的“工作模式”选项卡的屏幕截图。](../Prompts/Media/work-mode.png)  

    示例提示：****

    ```text
    Summarize the top challenges I face in my daily work, based on recent emails, chats, and documents. Show results in a simple list with: 
    
    - Title (short label for the issue) 
    - Description (1–2 sentences) 
    ```  

### 任务 2：使用研究助手探索 AI 解决方案思路  

使用研究助手智能体探索 Copilot 或其他智能体如何为你所选定的挑战提供帮助。

**步骤：**  

- 在“Copilot 对话助手”菜单中，展开“智能体”并选择“研究助手”********。  

   ![显示在 M365 Copilot 菜单中选中“研究助手”的屏幕截图。](../Prompts/Media/researcher.png)  

- 尝试如下所示的示例提示：  

   ```text
   Explore possible AI solutions to help with [insert productivity issue]. Focus on retrieval-based approaches using Focus on retrieval-based approaches using Microsoft Copilot or Copilot Studio agents. Summarize two or three ways an agent could help me find, organize, or summarize information more efficiently.
   ```  

    > 提示****：请将重点放在实用的日常用例上 - 例如快速调取文档，或是从多个来源汇总最新信息。  

### 任务 3：生成并测试你的智能体  

现在，在 Copilot Studio 中创建一个简单的检索型智能体，以解决你所面临的挑战****。  

**步骤：**  

1. 在 “Copilot 对话助手”菜单中，选择“创建智能体”********。

   ![显示创建智能体链接的屏幕截图。](../Prompts/Media/create-agent.png)  

1. 在“描述”选项卡中，起草智能体的角色。 例如：  

   ```text
   You’re a virtual assistant that helps me with [key task]. Be concise and always reference my recent files or resources when possible.
   ```  

   ![显示描述智能体的屏幕截图，其中填充了示例提示。](../Prompts/Media/create-agent-through-describe.png)  

1. 选择“配置”选项卡并添加一个知识源（例如“我的电子邮件”或“我的 Teams 聊天和会议）************。

    ![显示代理生成器中知识源部分的屏幕截图。](../Prompts/Media/knowledge-sources.png)

1. 使用“测试”窗格测试你的智能体，并根据需要进行优化****。  
1. 选择“创建”，发布你的智能体并开始使用****。  

> 提示****：即便只是一个非常简单的智能体（例如能帮你查找近期项目文件的智能体），也能在你的日常工作中展现出检索功能的强大作用。
