---
title: 联机托管说明
permalink: index.html
layout: home
---

下面列出了每个演示的超链接。

## 演示

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| 演示 |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## 沉浸式体验的示例提示

#### [高管](https://learn.microsoft.com/en-us/training/modules/envision-new-ideas-with-microsoft-365-copilot/)（重定向到 Microsoft Learn）

#### [通信](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Communications-Prompts.html)

#### [HR](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/HR-Prompts.html)

#### [销售](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Sales-Prompts.html)

#### [IT](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/IT-Prompts.html)

#### [行政助理](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/EA-Prompts.html)

#### [业务经理](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Business-Manager-Prompts.html)

#### [Marketing](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Marketing-Prompts.html)

#### [操作](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Operations-Prompts.html)

#### [法律信息](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Legal-Prompts.html)

#### [Finance](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Finance-Prompts.html)

#### [代理 - 业务用户](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/EU-Agents.html)

#### [代理 - 高管](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Exec-Agents.html)