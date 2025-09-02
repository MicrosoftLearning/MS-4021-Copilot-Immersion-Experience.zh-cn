---
demo:
  title: 市场营销演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 市场营销演示

**应用场景**：  

你在一家饮料公司从事营销工作，你的目标是分析市场趋势，创建营销分析，并开发新的社交媒体市场活动。

## 演示设置

可在[此处](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)的 MS-4021 GitHub 存储库中找到示例文档：

此演示所需的特定文件包括：

- [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Promotion_Plan_for_Chai_Tea_in_Latin_America.docx)

- [Mystic_Spice_Premium_Chai_Tea_product_description.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Mystic_Spice_Premium_Chai_Tea_product_description.docx)

- [Contoso_Chai_Tea_market_trends.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_market_trends.docx)

- [Contoso_Chai_Tea_social_marketing_trends.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_social_marketing_trends.xlsx)

> **备注：** 下载这些文件后，最多可能需要 10 分钟才能同步到 OneDrive。 要避免演示期间出现延迟，请确保提前下载这些文件并同步到 OneDrive 中。 如果文件不可用，请打开文档并复制共享文件链接，以在演示中使用。

## 演示

### Word 中的 Copilot

使用 Word 中的 Copilot 起草详细的市场分析报告，并集思广益，针对拉丁美洲市场量身定制有创意的市场营销活动方案。

1. 打开 Word（在浏览器或桌面应用程序中）。

1. 在“**描述要写入的内容**”提示框中，键入以下内容：

    ```text
    Create a Market Analysis report for Mystic Spice Premium Chai Tea using the attached files. Include the product description, market trend analysis, and a promotion plan for Latin America.

    [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx], [Mystic_Spice_Premium_Chai_Tea_product_description.docx], [Contoso_Chai_Tea_market_trends.docx]
    ```

    > **备注：** 括号指示正在引用文档。 引用文档时，可以直接粘贴共享链接，或者引用文件名（如果 OneDrive 中可用）。

1. 让 Copilot 创建一个新部分以添加社交媒体市场活动创意：

    输入以下提示：

    ```text
    Draft a new section for social media campaigns to promote Mystic Spice Premium Chai Tea. Include a brief description of 2-3 campaign ideas, each with a unique focus. For each campaign, provide a tagline that reflects its theme and resonates with our target audience of young professionals and tea enthusiasts.
    ```

1. 将此新文档另存为 **LATAM_Market_Analysis.docx**。

### Copilot 对话助手

使用 Copilot Chat 评估拟议社交媒体市场活动的有效性，并优化拉丁美洲市场中文化相关性策略。

1. 打开浏览器并导航到 [M365copilot.com](https://m365copilot.com/)。

1. 确保已选择“Web 模式”。

    ![显示 Web 模式选项卡的屏幕截图。](../Prompts/Media/web-mode.png)

1. 在提示窗口中，键入以下内容：

    ```text
    Review the social media campaigns outlined in the Market Analysis Report for Mystic Spice Premium Chai Tea.docx. Evaluate which campaign might resonate best with the LATAM market based on cultural relevance, target audience preferences, and alignment with regional trends. Provide reasons for your choice and suggest any adjustments to improve its impact.
    ```

    > **备注：** 暂时先不要提交提示。 移动到下一步以上传文件。

1. 选择“**添加内容**”并上传在上一个演示中保存到 OneDrive 的 **LATAM_Market_Analysis.docx**。 然后提交提示。

    ![添加内容 Copilot Chat。](../Demos/Media/add-content-copilot-chat.png)

1. Copilot 应推荐其中一个要关注的市场活动并提供改进建议。 在下一个提示中，我们希望 Copilot 为这个新创意建议一个市场营销活动口号：

    ```text
    Generate a catchy marketing slogan for the [Campaign name - e.g., 'Morning Motivation'] campaign that highlights its unique value proposition and resonates with the LATAM market. Ensure the slogan reflects a vibrant and culturally relevant tone that appeals to young professionals.
    ```

1. （可选）对于最后一个提示，可以要求 Copilot 为市场活动生成新视频：

    在 Copilot Chat 中，在右侧选择“**视觉资料创建器代理**”：

    ![视频创建器代理。](../Demos/Media/video-creator.png)

    然后，输入以下提示：

    ```text
    Create a captivating social media video for Mystic Spice Chai Tea that highlights its unique flavor and vibrant appeal. The video should feature eye-catching visuals, with colors, and themes that resonate with young professionals and tea enthusiasts.
    ```

### Excel 中的 Copilot

1. 确保已下载 [Contoso_Chai_Tea_market_trends_2023.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/Contoso_Chai_Tea_market_trends_2023.xlsx) 并在 Excel 中打开文档（Web 或桌面应用程序）。

1. 从功能区选择“**Copilot**”以打开 Copilot 窗格。

1. 在 Excel 中键入以下提示：

    ```text
    On average, how many sales do we get per social media campaign view?
    ```

1. 接下来，要求 Copilot 将销售额与社交媒体参与度进行比较：

    ```text
    Can you show a correlation between social media engagement and sales?
    ```

1. 接下来，键入以下提示：

    ```text
    How many social media campaign views did we have from September to December?
    ```

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
