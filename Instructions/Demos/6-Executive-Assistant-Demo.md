---
demo:
  title: 行政助理演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 行政助理演示

**应用场景**：

你的任务是负责为高管汇总最新的财报电话会议记录。 此任务包括提取关键见解、创建执行摘要和准备后续会议。

## 演示设置

可在[此处](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)的 MS-4021 GitHub 存储库中找到示例文档：

此演示所需的特定文件包括：

- [Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx)

> **备注：** 下载这些文件后，最多可能需要 10 分钟才能同步到 OneDrive。 要避免演示期间出现延迟，请确保提前下载这些文件并同步到 OneDrive 中。 如果文件不可用，请打开文档并复制共享文件链接，以在演示中使用。

## 演示步骤

### Word 中的 Copilot

我们首先查看最新财报电话会议的记录，并为高管汇总关键点。

1. 在 Word 中选择并打开 **Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx** 文件（在浏览器或桌面应用程序中）。

    > **备注：** 可能需要快速滚动浏览文档以显示其大小，并且汇总此文档并非易事。

1. 从功能区选择“Copilot”图标：

    ![Word 中的 Copilot 图标。](../Demos/Media/Copilot-in-word-ribbon.png)

1. Copilot 窗格应打开。 在显示“+ 你希望 Copilot 起草什么？”的位置输入以下提示：****

    ```text
    Summarize the key points from the Microsoft FY24 Second Quarter Earnings Conference Call.
    ```

1. 假设你的高管想知道 Satya Nadella 在电话会议中讨论的具体内容。 使用以下提示：

    ```text
    Provide a brief summary of Satya Nadella's remarks during the earnings call.
    ```

   - 显示 Copilot 如何包括每个要点的引用，从而快速导航到特定部分。  
   - 单击一个引用以演示 Copilot 如何立即转到文档中的相关内容。

1. 要创建详细报告，请询问 Copilot：

    ```text
    Analyze the Microsoft FY24 Second Quarter Earnings Conference Call document to provide a comprehensive report that includes:
    - A summary of the key points from each speaker
    - Identification of the top three growth areas and their contributing factors.
    - A detailed breakdown of the financial performance, including revenue, operating income, and earnings per share.
    - Trends in AI adoption and its influence on Microsoft's business strategy.
    - A comparison of this quarter's performance with the same quarter last year, highlighting significant changes.
    - Key strategic initiatives and future outlook as discussed in the call.
    ```

    > **提示：** 提及此提示较为复杂，Copilot 可能需要一些时间来生成回复。

1. Copilot 完成分析后，选择“**复制**”图标保存结果以供下一步使用。

    ![复制结果。](../Demos/Media/Copilot-in-word-copy-results.png)

### Copilot 对话助手

Word 提供的报告是一个很好的起点，但现在我们希望使用 Copilot Chat 帮助我们创建执行摘要。

1. 打开浏览器并导航到 [M365copilot.com](https://m365copilot.com/)。

1. 确保已选择“**Web 模式**”。

    ![显示 Web 模式选项卡的屏幕截图。](../Prompts/Media/web-mode.png)

1. 按照以下提示将来自 Word 中的 Copilot 的回复粘贴到 Copilot Chat 中：

    ```text
    Based on the following information, provide an executive summary on the following information:

    [paste the Word output here]
    ```

    > **备注：** 清理复制内容中的任何无关文本，以确保清晰度。

1. 将摘要优化为简洁格式：

    ```text
    Summarize this executive summary into a more concise format by focusing on the most critical insights and metrics for each speaker. Use a structured format with headings and bullet points to improve readability. Export to a Word document.
    ```

   - 如果 Copilot 不导出文档，请重新表述请求：“将此摘要另存为 Word 文档”。

1. 完成执行摘要后，询问 Copilot：

    ```text
    Based on the summarized executive summary, generate 5-7 concise and impactful talking points my manager can use in their next leadership call. Focus on key achievements, growth areas, and strategic priorities.
    ```

### Outlook 中的 Copilot

在此演示中，我们将使用 Outlook 中的 Copilot 安排与高管开会，让他们快速了解第二季度财报电话会议期间发生的一切。

1. 打开浏览器并导航到 [outlook.office.com](https://outlook.office.com.com/)。

1. 在 Outlook 功能区中，选择“Copilot”图标以打开“Copilot”窗格。

1. 使用以下提示计划同步：

    ```text
    I need to schedule a 30-minute meeting with [/Pick a colleague] tomorrow afternoon to discuss the Second Quarter Earnings Conference Call. Can you suggest a time that works? If they are unavailable, provide an alternative.
    ```

1. Copilot 应建议会议的时间和日期。 此提示显示可以发送或编辑的日历项。 选择“编辑”  。

1. 切换到日程安排助理，以显示 Copilot 建议的时间适用于项目经理。 你们都应该有空。

1. 切换回“事件”选项卡，然后在事件正文中选择“**使用 Copilot 起草**”。

1. 在提示窗口中，键入以下内容：

    ```text
    I’m meeting with my boss to discuss key updates and strategic initiatives they missed from the Second Quarter Earnings Conference Call. Create an agenda to discuss financial performance, AI and technology integration, strategic acquisitions, productivity updates, and future outlook.
    ```

1. （可选）选择“**保留**”之前，可以要求 Copilot 延长、缩短时间或更改起草议程的语气。

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
