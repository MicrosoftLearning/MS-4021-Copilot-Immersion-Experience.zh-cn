---
demo:
  title: 运营演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 运营演示

## 场景

你是 Contoso 的运营经理，负责供应商采购和项目执行。 目标是审查过去的 RFP、提取关键选择条件，并为即将推出的计划起草新的 RFP。

## 演示设置

可在[此处](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)的 MS-4021 GitHub 存储库中找到示例文档：

此演示所需的特定文件包括：

- [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

- [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

- [Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

> **备注：** 下载这些文件后，最多可能需要 10 分钟才能同步到 OneDrive。 要避免演示期间出现延迟，请确保提前下载这些文件并同步到 OneDrive 中。 如果文件不可用，请打开文档并复制共享文件链接，以在演示中使用。

## 演示

### Copilot in Word

首先，向 Word 中的 Copilot 询问一些有关“请求提案”(RFP) 文档的问题。

1. 打开 Word（在浏览器或桌面应用程序中）。
1
1. 打开以下文档：[Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

1. 选择 Word 功能区中的 Copilot 图标以打开聊天窗格。

    ![显示“工作模式”选项卡的屏幕截图。](../Demos/Media/copilot-ribbon-word.png)

1. 在“聊天”窗格中，选择或输入提示：

   ```text
   Summarize this document
   ```

1. 接下来，输入以下提示：

   ```text
   Analyze this document and generate a categorized list of required items needed to create an RFP.
   ```

1. 接下来，通过输入以下内容，要求 Copilot 创建 RFP 模板：

   ```text
   Analyze this document and create an RFP template based on the content.
   ```

    > **备注：** 无需复制生成的内容，因为在以下演示中我们将使用预先创建的模板文档。 但是，你可以展示如何复制 Copilot 的回复，或者将其插入文档中（如果与受众相关）。

### Copilot Chat

现在，我们已汇总 RFP 文档并创建 RFP 模板，接下来让我们使用 Copilot Chat 汇总新 RFP 的项目要求。

1. 打开浏览器并导航到 [M365copilot.com](https://m365copilot.com/)。  

1. 确保已选择“**Web 模式**”。

    ![显示 Web 模式选项卡的屏幕截图。](../Prompts/Media/web-mode.png)

1. 输入以下提示：

   ```text
   Summarize [Project_Guidelines_Contoso.docx] highlighting the key objectives, scope, implementation timeline, budget, compliance needs, and vendor selection criteria in a bulleted list.
   ```

    > **备注：** 括号指示正在引用文档。 使用链接：[Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

1. 接下来，要求 Copilot 提取供应商选择条件：

   ```text
   Extract and summarize the key vendor selection criteria from this document, including weight percentages and evaluation factors.
   ```

1. 然后，要求 Copilot 根据项目准则创建 RFP：

   ```text
   Using the project requirements outlined above, draft an RFP using the following template: [Contoso_RFP_Template.docx].
   ```

    > **备注：** 括号指示正在引用文档。

1. **将生成的 RFP 复制**到剪贴板，以便在后续演示中使用。

1. （可选）要求 Copilot 将生成的 RFP 导出到 Word 文档。

### Outlook 中的 Copilot

最后，使用 Outlook 中的 Copilot 向汇总 RFP 文档的潜在供应商起草电子邮件。

1. 打开 Outlook（在浏览器或桌面应用程序中）。

1. 选择“**新建电子邮件**”。

1. 在功能区中选择“Copilot”****。 从下拉菜单中，选择“**使用 Copilot 起草**”。

1. 在 **“您希望此电子邮件包含哪些内容？”** 提示窗口，键入：

   ```text
   Draft an email to potential suppliers summarizing the RFP below:

   [paste contents of RFP]
   ```

    > **备注：** 粘贴从上一个演示复制的 RFP 内容。

1. 生成草稿后，可以使用“**调整**”功能修改语气、长度或正式程度。

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
