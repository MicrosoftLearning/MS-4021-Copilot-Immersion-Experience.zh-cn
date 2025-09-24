---
demo:
  title: 人力资源演示
---

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 人力资源演示

**应用场景**：  

创建量身定制的职位描述、根据简历入围候选人以及起草符合团队要求的招聘策略，从而简化 UX 设计师团队的招聘流程

## 演示设置

可在[此处](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)的 MS-4021 GitHub 存储库中找到示例文档：

此演示所需的特定文件包括：

- [Design_Team_Responsibilities.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Graphic_Design_Institute_Design_Team_Responsibilities.docx)

- [Resume_Patti_Fernandez.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Patti_Fernandez.docx)

- [Resume_Nestor_Wilke.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Nestor_Wilke.docx)

- [Resume_Holly_Dickson.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Holly_Dickson.docx)

- [Resume_Alex_Wilber.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Alex_Wilber.docx)

> **备注：** 下载这些文件后，最多可能需要 10 分钟才能同步到 OneDrive。 要避免演示期间出现延迟，请确保提前下载这些文件并同步到 OneDrive 中。 如果文件不可用，请打开文档并复制共享文件链接，以在演示中使用。

## 演示

### Word 中的 Copilot

首先，要求 Word 中的 Copilot 生成职位描述。

1. 打开 Word（在浏览器或桌面应用程序中）。

1. 在“**描述要写入的内容**”提示框中，键入以下内容：

    ```text
    I'm the HR Manager at the Graphic Design Institute. We've currently started the hiring process for a new Senior Animation Designer. Please review the attached document outlining the job responsibilities for this role and generate a detailed job description based on this information.

    [copy link or reference file to Design_Team_Responsibilities.docx]
    ```

    > **备注：** 附加 Design_Team_Responsibilities.docx 文件或将共享链接直接粘贴到提示中，以确保 Copilot 有权访问相关内容。

1. 查看和完成职位描述后，将文档另存为 **GDI_Job_Description.docx** 并复制共享 URL 供后续步骤使用。 （如果出现提示，请启用“自动保存”并选择 OneDrive 帐户。）

    ![共享链接。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot 对话助手

接下来，我们将使用 Copilot Chat 将收到的简历与职位描述进行对比，并确定最佳候选人。

1. 打开浏览器并导航到 [M365copilot.com](https://m365copilot.com/)。

1. 确保已选择“工作”模式。

    ![显示 Web 模式选项卡的屏幕截图。](../Prompts/Media/work-mode.png)

1. 在提示窗口中，键入以下内容：

    ```text
    We are hiring for the position of Senior Animation Designer. Please analyze the attached resumes and compare them to the requirements outlined in the job description provided here: [paste link to GDI_Job_Description.docx]. Rank the candidates from most qualified to least qualified, based on their alignment with the role.

    [Resume - Patti Fernandez
    Resume - Nestor Wilke
    Resume - Holly Dickson
    Resume - Alex Wilber]
    ```

    > **备注：** 附加简历或将其上传到提示窗口。 或者，使用 OneDrive 中的共享链接或文件名引用每个文件。

1. （可选）可以要求 Copilot Chat 将其回复导出到 Word 文档以突出显示此功能。

### Outlook 中的 Copilot

最后，在 Outlook 中使用 Copilot 向招聘团队起草有关顶级候选人的电子邮件。

1. 打开 Outlook（在浏览器或桌面应用程序中）。

1. 选择“**新建电子邮件**”。

1. 在功能区中选择“Copilot”****。 从下拉菜单中，选择“**使用 Copilot 起草**”。

1. 在 **“您希望此电子邮件包含哪些内容？”** 提示窗口，键入以下内容：

    ```text
    Please draft an email to the hiring team to share that Nestor Wilke and Patti Fernandez align best with the Senior Animation Designer role based on their qualifications. Include a recommendation to schedule interviews for these candidates and request feedback on next steps.
    ```

[返回到索引](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
