---
demo:
  title: IT 演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# IT 演示

**应用场景**：  

作为 IT 基础结构管理员，你计划在企业网络中安装新的网络安全产品。

## 演示设置

可在[此处](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)的 MS-4021 GitHub 存储库中找到示例文档：

此演示所需的特定文件包括：

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **备注：** 下载这些文件后，最多可能需要 10 分钟才能同步到 OneDrive。 要避免演示期间出现延迟，请确保提前下载这些文件并同步到 OneDrive 中。 如果文件不可用，请打开文档并复制共享文件链接，以在演示中使用。

## 演示

### Copilot 对话助手

首先，要求 Copilot 创建项目实现计划。

1. 打开浏览器并导航到 [M365copilot.com](https://m365copilot.com/)。

1. 确保已选择“Web 模式”。

    ![显示 Web 模式选项卡的屏幕截图。](../Prompts/Media/web-mode.png)

1. 在提示窗口中，键入以下内容：

    ```text
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

    > **备注：** 基于角色的提示有助于 Copilot 理解用户的责任和上下文，提高输出的相关性和针对性。

1. 现在，我们将要求 Copilot 向项目计划添加新部分以完善项目计划：

    输入以下提示：

    ```text
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

1. 最后，让 Copilot 将建议的项目计划输出到 Word 文档：

    输入以下提示：

    ```text
    Please export the project plan to a Word document.
    ```

1. 选择 Copilot 提供给新创建文件的链接，将其下载到“下载”文件夹。 将文件移动到 OneDrive 文件夹并打开它。 从文档复制共享 URL（如果出现提示，请启用“自动保存”并选择 OneDrive 帐户）。

    ![共享链接。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Word 中的 Copilot

我们现在将要求 Copilot 阐述这些策略，并起草有关如何实现这些策略的建议。

1. 打开 Word（在浏览器或桌面应用程序中）。

1. 在“你希望 Copilot 起草什么？”提示框中，键入以下内容：****

    ```text
    Using the Contoso [/CipherGuard Product Specification.docx] and the 'Project Implementation Plan' template provided in [paste in link to Project_Implementation_Plan.docx], draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    > **备注：** 括号指示正在引用文档。
    > 1. CipherGuard Product Specification.docx = [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)
    > 1. Project Implementation Plan.docx = 使用上一个演示中复制的链接。
    > 引用文档时，可以直接粘贴链接或引用文件名（如果在 OneDrive 中可用）。

1. 选择“**保留**”，或者（如果时间允许）演示如何使用 Copilot 调整文档。

1. 完成后，将文档另存为 **Contoso_Project_Plan.docx** 并复制共享 URL（如果出现提示，请启用“自动保存”并选择 OneDrive 帐户）。

    ![共享链接。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### PowerPoint 中的 Copilot

现在，我们将使用 Copilot 基于实现 Contoso CipherGuard 产品的新建议生成 PowerPoint 演示文稿。

1. 从浏览器 [PowerPoint.new](https://PowerPoint.new) 启动 Microsoft PowerPoint，或使用桌面应用程序。

1. 打开新的空白演示文稿。

1. 在 Copilot 窗格中，选择“基于文件创建演示文稿”提示。

1. 粘贴 **Contoso_Project_Plan.docx** 文档的共享链接，然后选择“**发送**”。

    完整的提示应类似于 ：

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

1. Copilot 开始基于项目计划生成幻灯片，并提供大纲以及演讲者备注、图像、幻灯片版式和常规敏感度标签等功能。

    > **备注：** 生成幻灯片最多可能需要两分钟，具体取决于文档的复杂程度和幻灯片数。

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
