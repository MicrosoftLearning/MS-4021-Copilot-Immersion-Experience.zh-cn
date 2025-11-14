---
demo:
  title: 研究助手和分析助手演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 研究助手和分析助手演示

此演示重点介绍如何使用“研究助手”和“分析助手”这两个内置于 Copilot 应用的专家级智能体。  

- 研究助手可以帮助你处理多步骤的研究任务，将 Web 数据与你公司的文件和知识相结合****。  
- 分析助手具备专业数据科学家的思维能力，能够执行高级数据分析与 Python 代码运行 - 即便你不懂编程也可使用****。  

## 演示设置

为完成这些演示，你需要下载[研究助手和分析助手演示 - 内容包](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/refs/heads/master/ResourceFiles/Researcher_and_Analyst_Demo_Content_Pack.zip)，该内容包包含所有必需的文件和资源。  

> 提示****：在进行演示之前，你可以在演示环境中创建一个 SharePoint 站点，用于存储所有相关文件，以便快速访问。 或者，你也可以将文件存储在本地，并在提示中通过/ 直接引用这些文件****。  

要访问这些智能体，请执行以下操作：  

- 从[m365.cloud.microsoft](https://m365.cloud.microsoft) 打开 Copilot 应用****。  
- ******** 从导航窗格中选择“研究助手”或“分析助手”。  

> **注意：** 你需要将研究助手和分析助手指向企业内部文件（存储于 SharePoint 或 OneDrive），以获取有事实依据的见解。

---

## 讲座要点

- 研究助手犹如高薪顾问：它能够整合内部文件、竞争对手情报与 Web 资源，生成结构清晰且引用规范的交付成果****。  
- 分析助手如同随时待命的数据科学家：它能构建模型、运行 Python 代码，并即时可视化趋势****。  
- 这两款智能体均以透明方式阐释其推理逻辑，以便你能够验证结果的准确性。  
- 二者协同加速战略工作 - 无论是营销计划、客户细分还是财务预测 - 都能助你满怀信心地推进各项事务。  

---

## 演示步骤

### 研究助手：制定市场营销计划

> **重要提示：** 步骤 1 至步骤 4 应在培训开始时完成（如第 5 张幻灯片所示），以便为研究助手留出充足时间来完成首个提示。

1. **** 从导航窗格中打开“研究助手”。  

    ![显示在 M365 Copilot 菜单中选中“研究助手”的屏幕截图。](../Prompts/Media/researcher.png)  

1. 输入以下提示：

    ```text
    Create a marketing plan for our newest SprintCycle EV charger launch. 
    Emphasize its AI-powered adaptive charging, modular design, and biometric access control. 
    Make sure to include recommendations on the right digital channels and content strategy. 
    Include insights from competitors and our past GTM campaigns.
    ```

1. 使用`/`（指向 SharePoint/OneDrive）附加参考文件：  

   - **/SprintCycle Charger Product Launch.docx**  
   - （可选）**/Contoso - PedalPerks GTM Plan.docx****  

1. 选择**提交**。  

研究助手能够：  

- 整合来自内部文件与 Web 的见解。  
- 制定一份包含渠道及内容策略建议的市场营销计划。  
- 标注来源，以便核查其工作准确性。  

> **注意：** 研究助手将展示其推理路径（“思维链”），并可在需要时调用其他智能体。  

### 分析助手：客户细分与财务建模

**注意：****** 此演示不适用于内容的执行版，请转而进行 Copilot studio 演示。

1. **** 从导航窗格中打开“分析助手”。

    ![显示 M365 Copilot 菜单中“分析助手”已选中的屏幕截图。](../Prompts/Media/analyst.png)  

1. 输入以下提示：

    ```text
    Find the right customer segment and demographic to sell our new EV charger, 
    include a graph to show how this will maximize our market opportunity.
    ```

1. 使用+ 附加以下文件****：  

   - **BoulderEV ebike Internal Market Forecast.xlsx**  

    ![显示在分析助手中附加文件的屏幕截图。](../Prompts/Media/Analyst-Attach-Files.png)  

1. 单击“提交”****。  

分析助手可以：  

- 分析数据集。  
- 识别高价值客户细分。  
- 提供可视化分析以备份各项建议。  

### 其他分析助手场景

你可运行这些额外提示以获取多样化输出。 每个提示都遵循相同模式：**提示 → 附加文件 → 提交 → 查看结果。**

- **财务预测**  

    ```text
    Build a 5-year financial projection from this data along with a graph to view revenue growth over time.
    ```  

    文件：**BoulderEV ebike Internal Market Forecast.xlsx**  

- **销售业绩**  

    ```text
    Analyze sales volume across locations to identify our highest and lowest performing stores, 
    along with a visualization of the best-selling products.
    ```  

    文件：**BoulderEV ebike Internal Market Forecast.xlsx**  

- **营销活动成效**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  

    文件：**BoulderEV ebike Internal Market Forecast.xlsx**  

## 核心要点

- 研究助手****：凭借高质量研究加速策略和规划进程。  
- 分析助手****：运用先进分析方法与可视化效果交付数据驱动的见解。  

研究助手与分析助手相结合可缩短从问题到见解的过程，将数周的工作压缩到几分钟内完成****。  

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
