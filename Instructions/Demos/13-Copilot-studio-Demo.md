---
demo:
  title: 使用 Copilot Studio 构建智能体
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

---

# 使用 Copilot 对话助手构建和发布智能体

本演示将逐步展示如何通过 Copilot 对话助手在 Copilot Studio 中构建虚拟助手，并将其发布到 Microsoft 365 Copilot。

## 演示设置

要完成这些演示，你需要下载以下文件：

- [**Delivery Drone Press Release.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Press_Release.docx)
- [**Delivery Drone Troubleshooting.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Troubleshooting.docx)
- [**Delivery Drone SOP.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_SOP.docx)
- [**Upselling Opportunities.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Upselling_Opportunities.docx)
- [**Delivery Drone FAQ.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_FAQ.docx)

> 提示****：在进行演示之前，你可以在演示环境中创建一个 SharePoint 站点，用于存储所有相关文件，以便快速访问。 或者，你也可以将文件存储在本地，并在提示中通过 / 直接引用这些文件****。

## 讲座要点

通过 Copilot Studio，我们可以构建自定义助手，这些工具可根据特定项目、部门或知识库的需求进行定制。 我们可以为这些自定义助手赋予专属特性，设定其边界，并向它们导入特定文档，以此确保其响应既高质量，又有事实依据。

在此演示中，我们将为“ReleCloud 无人机配送项目”创建一个虚拟助手。 该助手将掌握我们已上传的所有信息，并协助解答团队成员的疑问，从而节省时间、提升工作效率。

## 演示步骤

### 步骤 1 - 导航到 Copilot Studio

1. 转到“[https://m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat)”，在右侧滑轨中选择“创建智能体”****。

    ![显示创建智能体链接的屏幕截图。](../Prompts/media/create-agent.png)

1. 使用你的凭据登录。

### 步骤 2 - 定义智能体

1. 出现提示时添加以下描述：

    ```text
    You're a virtual project manager assistant for our drone delivery project. You know everything about the project from the documents we've shared with you, and are happy to help team members get the information they need.
    ```

   ![显示“描述”功能的屏幕截图。](../Prompts/Media/create-agent-through-describe.png)

1. 为助手命名：

    ```text
    Drone Delivery Assistant
    ```

1. 如果系统提示进行确认：

    ```text
    Yes, thank you
    ```

1. 如果系统提示你要避免的内容或需强调的内容：

    ```text
    Please be clear and concise and avoid long answers. Where possible, refer primarily to the knowledge shared with you. If you don't know the answer, refer them to the drone delivery project manager.
    ```

1. 如果系统提示你设置语气风格：

    ```text
    Friendly and professional
    ```

> **重要提示：** 根据你的环境不同，系统可能不会提示你选择所有这些选项。 如果未收到相关提示，你可在 Copilot Studio 内，通过“配置”选项卡添加这些信息****。

### 步骤 3：配置智能体

1. 单击“配置”以打开智能体编辑器****。
1. 查看并根据需要更新“说明”部分****：

    ```text
    Your name is Drone Delivery Project Manager Assistant. You serve as a virtual project manager for the ReleCloud drone delivery project, with comprehensive knowledge from shared documents. Be clear and concise, avoiding long answers. If the answer is unknown, refer to the drone delivery project manager.
    ```

1. 向下滚动到“知识”部分，单击“按名称搜索或输入 URL”文本按钮********。 选择“文件”，并将以下文档添加到智能体的知识库****：

    - **Delivery Drone Press Release.docx**
    - **Delivery Drone Troubleshooting.docx**
    - **Delivery Drone SOP.docx**
    - **Upselling Opportunities.docx**
    - **Delivery Drone FAQ.docx**

        ![显示“知识源”的屏幕截图。](../Prompts/Media/knowledge-sources.png)

### 步骤 4 - 测试智能体

在右侧测试窗格中，尝试提出以下几个问题：

- `Tell me about the ReleCloud Delivery Drone.`
- `How do I fix the drone error code D-101?`
- `What are the upsell opportunities for ReleCloud?`
- `What’s the duration of Phase 1 of the delivery drone project?`

> **重要提示：**  智能体处理文档并给出准确答案可能需要一定时间。 如果收到错误消息，请等待几分钟后重试。

> 提示****：当智能体上线后，你还可以通过 Microsoft Teams 对其进行测试。

### 步骤 5 - 发布和共享

1. 单击“创建”以发布智能体****。
1. 选择“更改共享设置”，然后选择“组织中的任何人”********。
1. 复制共享链接并将其粘贴到 Teams 聊天中，以便轻松访问。

智能体上线后，你可以在 Teams 聊天中与它互动，也可以通过 @mentions 与它互动。

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
