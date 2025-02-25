---
demo:
  title: 销售演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 销售演示

**应用场景**：  

你在一家电动汽车充电公司从事销售工作，并正在为来年制定战略计划。

## 演示设置

可在[此处](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)的 MS-4021 GitHub 存储库中找到示例文档：

此演示所需的特定文件包括：

- [Charger_sales_report_2022-2024.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Charger_sales_report_2022-2024.xlsx)

> **备注：** 下载这些文件后，最多可能需要 10 分钟才能同步到 OneDrive。 要避免演示期间出现延迟，请确保提前下载这些文件并同步到 OneDrive 中。 如果文件不可用，请打开文档并复制共享文件链接，以在演示中使用。

## 演示

### Copilot Chat

1. 打开浏览器并导航到 [M365copilot.com](https://m365copilot.com/)。

1. 确保已选择 Web 模式。

    ![显示 Web 模式选项卡的屏幕截图。](../Prompts/Media/web-mode.png)

1. 首先，要求 Copilot 研究关键指标。 在 **Copilot Chat** 提示字段中输入：

    ```text
    What is the ratio of EV cars to EV chargers by region in the US for the past 3 years? Please show it in a table organized by region.
    ```

    ![显示 Copilot Chat 电动汽车充电器提示的屏幕截图。](../Demos/Media/copilot-chat-ev-charger-prompt.png)

1. 现在，让我们将国家发展趋势与公司的销售业绩进行比较。 你将上传提供的数据集，并要求 Copilot 可视化该数据：

    在提示字段中，键入：

    ```text
    I need to know the quarterly trends for each of our sales regions. Create a quarterly revenue line graph for the past 2 years based on:
    ```

    > **备注：** 暂时先不要提交提示。 移动到下一步以上传文件。

1. 选择“**添加内容**”并上传 [**Charger_sales_report_2022-2024.xlsx**](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/Resourcefiles/Charger_sales_report_2022-2024.xlsx)。 然后提交提示。

    ![添加内容 Copilot Chat。](../Demos/Media/add-content-copilot-chat.png)

1. 让我们更进一步，询问 Copilot 导出到 Word 文档的建议：

    在提示字段中，键入：

    ```text
    Based on the trend, suggest two ways I can increase EV charger sales in the Mountain and Midwest regions. Export the recommendations to a Word Document.
    ```

1. 选择 Copilot 为新 Word 文档提供的超链接以将其打开。

1. 打开后，选择“**启用编辑**”，然后打开“自动保存”。 出现提示时选择 OneDrive 帐户。


### Copilot in Word

我们现在将要求 Copilot 阐述这些策略，并起草有关如何实现这些策略的建议。

1. 如果根据上一个演示生成的 Word 文档应尚未打开，请将其打开（在浏览器或桌面应用程序中）。

1. 选择文档正文中的任意位置，然后选择 Copilot 图标。

    键入以下提示：

    ```text
    Draft a detailed proposal on how we could implement each of the strategies outlined in this document. Ensure the plan is actionable and includes resource requirements, timelines, and key stakeholders.
    ```

1. 选择“**保留**”，或者（如果时间允许）演示如何使用 Copilot 调整文档。

1. 完成后，将文档另存为 **EV Sales Proposal.docx**，并复制要在下一步中使用的共享 URL（启用“自动保存”并选择 OneDrive 帐户）。

    ![共享链接。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

    > **培训师提示：** 使用此步骤演示 Copilot 如何基于此前的输出，将想法细化为连贯的提案。

### PowerPoint 中的 Copilot

1. 从浏览器 [PowerPoint.new](https://PowerPoint.new) 启动 Microsoft PowerPoint，或使用桌面应用程序。

1. 打开新的空白演示文稿。

1. 在 Copilot 窗格中，选择“基于文件创建演示文稿”提示。

1. 将 **EV Sales Proposal.docx** 链接粘贴到“创建演示文稿依据”之后，然后选择“**发送**”。

    完整的提示应类似于 ：

    ```text
    Create a presentation from [Link to EV Sales Proposal.docx].
    ```

1. Copilot 开始基于电动汽车销售提案生成幻灯片，并提供大纲以及演讲者备注、图像、幻灯片版式和常规敏感度标签等功能。

    > **备注：** 生成幻灯片最多可能需要两分钟，具体取决于文档的复杂程度和幻灯片数。

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
