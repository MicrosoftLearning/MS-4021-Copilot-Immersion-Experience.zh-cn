---
demo:
  title: 财务演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 财务演示

**应用场景**：  

你是 Contoso 的财务分析师，负责评估电动汽车充电行业的销售业绩和市场定位。 目标是分析销售数据、生成见解并为团队准备摘要。

## 演示设置

可在[此处](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)的 MS-4021 GitHub 存储库中找到示例文档：

此演示所需的特定文件包括：

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

### Excel 中的 Copilot  

使用 Excel 中的 Copilot 分析销售数据、识别关键趋势和计算财务指标。

1. 启动 Excel 并打开文件  

1. 在 Excel 中打开 EV_Charger_Sales_Analysis_v1.xlsx****（在浏览器或桌面应用程序中）。  

1. 导航到 **“按产品划分的销售额”** 选项卡。  

1. 从 Excel 功能区中选择“Copilot”，然后选择“应用技能”以打开 Copilot 窗格。********

1. 输入以下提示，使用 Copilot 对表进行排序：  

    ```text
    Sort the table by date in descending order, from the most recent to the oldest entry.
    ```  

    - Copilot 对表进行排序并更新数据集。  
    - 排序后选择 **“应用”**。  

1. 插入“总收入”列  

    在 Copilot 窗格中使用以下提示：  

    ```text
    Add a new column named 'Total Revenue'. Populate it by multiplying 'Units Sold' by 'Product Price' for each row.
    ```  

    - Copilot 新建列并应用公式。  
    - 选择 **“插入列”**。  

1. 生成 2024 年销售摘要表  

    在 Copilot 窗格中，输入以下提示：  

    ```text
    Create a summary table for total sales in 2024. The table should include Product ID, total units sold, and total revenue.
    ```  

    - Copilot 将生成摘要表。  
    - 选择 **“添加到新的数据表”** 以单独存储表。  
    - 确保表仅包含 **2024 年数据**。  
    - 导航回 **“按产品划分的销售额”** 选项卡，或在 Copilot 的最后一个回复下选择 **“返回数据”**。  

1. 确定畅销产品  

    在 Copilot 窗格中，输入以下提示：  

    ```text
    Identify the product ID with the highest total revenue in 2024. Provide both total revenue and total units sold for better comparison.
    ```  

    - Copilot 分析数据集并提供最畅销的产品。
    - 导航回 **“按产品划分的销售额”** 选项卡，或在 Copilot 的最后一个回复下选择 **“返回数据”**。  

1. 按收入对客户进行排序

    - 导航到 Excel 中的 **“客户”** 工作表。

    在 Copilot 窗格中，输入以下提示：  

    ```text
    Sort the 'Customers' tab by annual revenue in descending order.
    ```  

    - Copilot 按**年收入**对客户进行排序。  
    - 排序后选择 **“应用”**。  

1. 计算每个客户的平均收入

    输入以下提示：  

    ```text
    Calculate the average revenue per customer.
    ```  

    - Copilot 计算平均值并添加结果。  
    - 选择 **“插入行”** 存储平均收入值。  

1. 使用 Most Power 查找行业  

    在 Copilot 窗格中，输入以下提示：  

    ```text
    Analyze the data to determine which industry has the highest total power consumption. Provide the industry name and total power usage.
    ```  

    - Copilot 处理数据并返回功耗最高的行业。

1. 保存文档。 从文档复制共享 URL（如果出现提示，请启用“自动保存”并选择 OneDrive 帐户）。

    ![共享链接。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot 对话助手

使用 Copilot Chat 将财务业绩与行业基准和竞争对手进行比较。

1. 打开浏览器并导航到 [M365copilot.com](https://m365copilot.com/)。

1. 确保已选择“Web 模式”。

    ![显示 Web 模式选项卡的屏幕截图。](../Prompts/Media/web-mode.png)

1. 在提示窗口中，键入以下内容：

    ```text
    Our total revenue for [EV chargers] exceeded $50,000,000 for firth half of 2024. Compare this to the industry average and provide insights on whether we are above or below industry standards. If possible, include market share estimates and trends
    ```

1. 现在要求 Copilot Chat 将此与竞争对手进行比较：

    ```text
    Summarize the key financial statements of two major competitors in the [EV charging] industry. Include revenue, net profit, and any other relevant financial insights. If available, provide comparisons to our financial performance.
    ```

1. 最后，要求 Copilot 将迄今为止的聊天历史记录导出到 Word 文档：

    ```text
    Export this conversation, including financial insights, to a Word document for further review.
    ```

1. 选择要下载的链接文件，然后打开文档。

1. 选择**启用编辑**。

1. 该文件的标题应类似于“**Charging_industry_Financial_Summary.docx**”。 从文档复制共享 URL（如果出现提示，请启用“自动保存”并选择 OneDrive 帐户）。

    ![共享链接。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Word 中的 Copilot

使用 Word 中的 Copilot 将财务见解汇总成电子邮件发送给团队。

1. 打开新的 Word 文档（在浏览器或桌面应用程序中）。

1. 在“**描述要写入的内容**”提示框中，键入以下内容：

    ```text
    Draft an email to my team summarizing the key insights from [Charging_industry_Financial_Summary.docx].
    ```

    > **备注：** 附加在上一任务中创建的 Charging_industry_Financial_Summary.docx 文件，或直接将共享链接粘贴到提示中，以确保 Copilot 有权访问相关内容。

1. 查看 Copilot 的输出。 选择“**保留**”之前，请询问 Copilot 以优化回复：

    ```text
    Shorten this email draft
    ```

1. 其他可选优化：

    - 要求 Copilot 对部分内容重新措辞，使其语气更加专业。
    - 使用其他部分展开。
    - 使其不那么正式

1. 完成后，可以选择“**保留**”

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
