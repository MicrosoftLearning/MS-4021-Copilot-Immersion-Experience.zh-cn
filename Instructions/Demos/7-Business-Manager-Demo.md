---
demo:
  title: 业务经理演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 业务经理演示

**应用场景**：

分析销售业绩和客户反馈以解决产品问题，然后与团队协作以规划改进。

## 演示设置

可在[此处](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)的 MS-4021 GitHub 存储库中找到示例文档：

此演示所需的特定文件包括：

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

> **备注：** 下载这些文件后，最多可能需要 10 分钟才能同步到 OneDrive。 要避免演示期间出现延迟，请确保提前下载这些文件并同步到 OneDrive 中。 如果文件不可用，请打开文档并复制共享文件链接，以在演示中使用。

## 演示步骤

### Excel 中的 Copilot

1. 启动 Excel（在浏览器或桌面应用程序中），并打开 **EV_Charger_Sales_Analysis_v1.xlsx** 文件。

1. 在 Excel 文件中，**导航到“按产品划分的销售额”选项卡**。

1. 使用 Copilot 计算每月收入：  

   首先，弄清楚哪个业务类别能带来最多收入。 此工作表包含三年的销售数据，其中数千行显示了按产品和月份划分的销售情况。 虽然这是一项常规任务，但如此大的数据量可能会难以处理。 可以让 Copilot 快速计算按产品划分的每月收入。

   使用以下提示：

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```

    - Copilot 知道如何执行此操作，以及跨选项卡引用哪些数据。
    - Copilot 针对如何计算这些数字制定计划，执行该计划并显示其计算过程，同时提示你提出问题或对其得出的解决方案进行迭代。
    - 选择“**+ 插入列**”，然后导航回“**按产品划分的销售额**”选项卡。

1. 通过在 Copilot 窗格中输入以下提示，使用 Copilot 分析收入：

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot 计算这些数字并创建可添加到工作簿的条形图。
    - 选择“**+ 添加到新工作表**”，然后导航回“**按产品划分的销售额**”选项卡。

1. 现在，通过输入以下提示，使用 Copilot 突出显示销售额低的产品：

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot 应用条件格式，帮助你识别性能上不符合标准的产品。

1. **导航到“评论”选项卡**以分析客户反馈。

1. 通过输入以下提示，要求 Copilot 总结最受关注的问题：

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot 分析反馈，并显示客户最关心的三大问题。 看起来充电速度是一个新出现的问题。

1. 接下来，通过输入以下提示突出显示提及充电速度的评论：

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot 将突出显示数据集中的所有相关评论。

### Copilot Chat

现在已经将充电速度慢确定为关键问题，我们将使用 **Copilot Chat** 进一步探索问题并识别潜在的解决方案。

1. 打开浏览器并导航到 [M365copilot.com](https://m365copilot.com/)。  

1. 确保已选择“**Web 模式**”。  

    ![显示 Web 模式选项卡的屏幕截图。](../Prompts/Media/web-mode.png)

1. 要研究此问题，请输入以下提示：
  
    ```text
    Research common issues with EV charger speeds and identify potential causes or solutions. Summarize findings in a format suitable for a business presentation. Highlight any relevant industry benchmarks or competitor data.
    ```

   - 根据需要查看 Copilot 的摘要，并请求提供其他上下文或最近的趋势。  

1. （可选）优化输出：
   - 向 Copilot 询问解决电动汽车充电器效率的最新趋势或技术：

    ```text
    What are the latest innovations or technologies addressing slow EV charger speeds in 2024?
    ```

   - 请求竞争对手见解：

    ```text
    Assuming competitors in the EV charging market are improving speed by 20% annually, suggest how we could position our CC-2001 and CC-2000 models to stay competitive.
    ```

1. 请求 Copilot 提出五个战略性问题，以询问电动汽车充电器的项目负责人：

    ```text
    Based on this information, suggest 5 strategic questions to ask the product team during our meeting tomorrow. Focus on identifying root causes, assessing risks, and brainstorming potential improvements.
    ```

### Outlook 中的 Copilot

在此演示中，我们将使用 Outlook 中的 Copilot 安排与负责电动汽车充电器生产线的项目负责人开会，讨论潜在的解决方案。

1. 打开浏览器并导航到 [outlook.office.com](https://outlook.office.com.com/)。

1. 在 Outlook 功能区中，选择“Copilot”图标以打开“Copilot”窗格。

1. 在提示窗口中，键入以下内容：

    ```text
    I need to schedule a meeting with [/Pick a colleague] tomorrow afternoon to discuss the EV charger issue reports. Can you suggest a time that works? If they are unavailable, please suggest an alternative time.
    ```

1. Copilot 应建议会议的时间和日期。 提示显示可以发送或编辑的日历项，选择“**编辑**”。

1. 切换到日程安排助理，以显示 Copilot 建议的时间适用于项目经理。 你们都应该有空。

1. 切换回“事件”选项卡，然后在事件正文中选择“**使用 Copilot 起草**”。

1. 在提示窗口中，键入以下内容：

    ```text
    Create an agenda for a meeting to discuss slow charging speeds with our CC-2001 and CC-2000 models. Include time for an introduction to the issue, a review of any available data or customer feedback, and a brainstorming session for potential solutions.  
    ```

1. （可选）选择“**保留**”之前，可以要求 Copilot 延长、缩短时间或更改起草议程的语气。

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
