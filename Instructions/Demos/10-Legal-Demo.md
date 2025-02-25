---
demo:
  title: 法务演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 法务演示

**应用场景**：  

你是 Contoso 的法律顾问，负责评估公司的 AI 简历筛选软件是否符合欧盟 AI 法案。目标是研究法律风险，起草执行摘要，并向领导层传达建议。

## 演示设置

此演示不需要任何示例文档。

## 演示

### Copilot Chat

首先研究 AI 法案及其对 Contoso AI 招聘工具的潜在影响。

1. 打开浏览器并导航到 [M365copilot.com](https://m365copilot.com/)。

1. 确保已选择“**Web 模式**”。

    ![显示 Web 模式选项卡的屏幕截图。](../Prompts/Media/web-mode.png)

1. 在提示窗口中，键入以下内容：

    ```text
      Contoso is launching an AI Resume Screening Software to evaluate job applicants. As a legal advisor, I need to assess whether it complies with the EU Artificial Intelligence Act. Summarize key provisions related to AI in hiring, compliance requirements for high-risk systems, and potential legal risks.
    ```

1. 查看 Copilot 的回复，并记下相关法律风险和合规性要求。

1. 现在，我们将询问 Copilot 一系列后续问题，以收集更多信息：

    ```text
    Does the AI Act classify resume screening software as a high-risk AI system?
    ```

    ```text
    What are the key obligations for high-risk AI systems under the AI Act?
    ```

    ```text
    Are there any exemptions in the AI Act that could apply to Contoso’s system?
    ```

1. 现在，要求 Copilot 汇总到目前为止的所有信息：

    ```text
    Summarize all the information we've discussed into a structured list, ensuring no key details are missed. Then, export the summary to a Word document
    ```

1. 选择 Copilot 为新 Word 文档提供的超链接以将其打开。

1. 打开后，选择“**启用编辑**”，然后打开“自动保存”。 出现提示时选择 OneDrive 帐户。

1. 复制共享 URL 以供后续步骤使用。 （如果出现提示，请启用“自动保存”并选择 OneDrive 帐户。）

    ![共享链接。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in Word

现在，我们将起草执行摘要，概述法律风险和给 Contoso 领导层的建议。

1. 在浏览器或桌面应用程序中打开 Word 的新实例。

1. 在“**描述要写入的内容**”提示框中，键入以下内容：

    ```text
    Reference the following document [Link to exported Copilot Chat summary from the first task] and draft an executive summary outlining key legal risks, compliance requirements, and recommendations for Contoso’s AI Resume Screening Software.
    ```

    > **备注：** 附加文档或将共享链接直接粘贴到提示中，以确保 Copilot 可以访问相关内容。

1. 查看 Copilot 的输出。 选择“**保留**”之前，请询问 Copilot 以优化回复：

    ```text
    Add a section on the potential business impact of these compliance requirements.
    ```

1. 其他可选优化：

    - 要求 Copilot 对部分内容重新措辞，使其语气更加专业。
    - 如果摘要太长，则请求更短、更简洁的版本。
    - 使用其他部分展开。

1. 查看和完成文档后，**将生成的执行摘要复制**到剪贴板，以便在后续演示中使用。

### Outlook 中的 Copilot

最后，我们将起草电子邮件给 Contoso 领导层，汇总我们的调查结果和后续步骤。

1. 打开 Outlook（在浏览器或桌面应用程序中）。

1. 选择“**新建电子邮件**”。

1. 在功能区中选择“Copilot”****。 从下拉菜单中，选择“**使用 Copilot 起草**”。

1. 在 **“您希望此电子邮件包含哪些内容？”** 提示窗口，键入：

   ```text
    Draft an email to Contoso’s executive leadership summarizing our legal assessment of the AI Resume Screening Software under the EU AI Act. Use the following executive summary as a reference.

    [paste Executive Summary from the previous task]

    Conclude the email with a request for leadership’s input on the next steps, including a proposed compliance review meeting.
   ```

    > **备注：** 粘贴从上一个演示复制的“执行摘要”内容。

1. 生成草稿后，可以使用“**调整**”功能修改语气、长度或正式程度。

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
