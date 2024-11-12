
![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241111195916313-1994353186.png)


上周的热门开源项目，Star 数增长犹如坐上了火箭，一飞冲天。短短一周就飙升了 6k Star 的多格式文档解析和导出神器 Docling，支持库和命令行的使用方式。全新的可视化爬虫平台 Maxun，则在刚开源时便轻松斩获了 4k Star。而本地优先的个人理财工具 Actual，支持 Docker 自托管，让用户可以将数据掌握在自己手里。如果你在寻找机器学习的 Python 库，可以去 best\-of\-ml\-python 看一看，它涵盖了 34 个分类，共计 920 个优秀的机器学习 Python 库。


最后，免费的 Windows 应用卸载利器（Bulk\-Crap\-Uninstaller）和 B 站视频空降助手（BilibiliSponsorBlock），凭借着简单实用、开箱即用的特点，迅速赢得了广大用户的青睐。


* 本文目录
	+ 1\. 热门开源项目
		- 1\.1 多格式文档解析和导出工具：Docling
		- 1\.2 本地优先的个人理财工具：Actual
		- 1\.3 简单干净的 Hugo 主题：hugo\-PaperMod
		- 1\.4 开源的无代码网页数据提取平台：Maxun
		- 1\.5 顶级的机器学习 Python 库列表：best\-of\-ml\-python
	+ 2\. HelloGitHub 热评
		- 2\.1 B 站视频空降助手：BilibiliSponsorBlock
		- 2\.2 免费的 Windows 应用卸载神器：Bulk\-Crap\-Uninstaller
	+ 3\. 结尾


## 1\. 热门开源项目


### 1\.1 多格式文档解析和导出工具：Docling


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241111195943066-276162705.png)


**主语言：Python**，**Star：7\.9k**，**周增长：6k**


这是一个由 IBM 开源的 Python 工具，专门用于将各类文档转化为适合生成式 AI 使用的工具。它能够将 PDF、DOCX、PPTX、图片、HTML、Markdown 等多种流行文档格式，导出为 Markdown 和 JSON 格式，支持多种 OCR 引擎（PDF）、统一的文档对象（DoclingDocument），轻松集成检索增强生成（RAG）和问答应用，适用于需要将文档作为生成式 AI 模型输入的场景。



```
from docling.document_converter import DocumentConverter

source = "url"  # document per local path or URL
converter = DocumentConverter()
result = converter.convert(source)
print(result.document.export_to_markdown())  # output: "## Docling Technical Report[...]"

```


> GitHub 地址→[github.com/DS4SD/docling](https://github.com)


### 1\.2 本地优先的个人理财工具：Actual


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241111195947115-1079077373.png)


**主语言：TypeScript**，**Star：15k**，**周增长：600**


这是一款完全免费开源、本地优先的个人理财工具。它采用 Node.js 编写，拥有简洁的界面和直观的现金流报告，支持 Docker 自建、导入交易数据和多设备同步，以及可选的端到端加密功能，注重保护用户隐私和数据安全。



> GitHub 地址→[github.com/actualbudget/actual](https://github.com)


### 1\.3 简单干净的 Hugo 主题：hugo\-PaperMod


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241111195951121-1309469854.png)


**主语言：HTML**，**Star：10k**


这是一个快速、简洁、响应式的 Hugo 主题。它基于 hugo\-paper 开发，并在此基础上增加了更多功能和自定义选项，支持多语言、自动切换明暗主题、SEO 友好、社交媒体分享按钮、封面图片、导航栏等功能。此外，它还提供了常规、主页信息和个人资料三种模式，可用于快速构建不同风格的个人博客。



> GitHub 地址→[github.com/adityatelange/hugo\-PaperMod](https://github.com)


### 1\.4 开源的无代码网页数据提取平台：Maxun


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241111200001561-1236353302.gif)


**主语言：TypeScript**，**Star：4k**，**周增长：3k**


这是一款全新的无代码网页数据提取平台，无需编程即可轻松抓取网站的数据，支持列表/文本抓取、截图、自定义代理、自动处理分页和滚动等功能。作为一个新的开源项目，它的功能还在不停迭代，计划推比如适应网站布局变化和登录后数据提取等新功能。



> GitHub 地址→[github.com/getmaxun/maxun](https://github.com)


### 1\.5 顶级的机器学习 Python 库列表：best\-of\-ml\-python


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241111200009524-1007915868.png)


**主语言：Other**，**Star：17k**，**周增长：1\.2k**


该项目提供了一个高质量的机器学习 Python 库列表，包含超过 900 个开源项目，并按照项目质量评分进行排名，每周更新一次。所有开源项目被分成了 30 多个分类，包括机器学习框架、数据可视化、自然语言处理、OCR、模型序部署等，便于不同应用领域的开发者快速找到所需的机器学习工具和资源。



> GitHub 地址→[github.com/ml\-tooling/best\-of\-ml\-python](https://github.com)


## 2\. HelloGitHub 热评


在此章节中，我们将为大家介绍本周 HelloGitHub 网站上的热门开源项目，我们不仅希望您能从中收获开源神器和编程知识，更渴望“听”到您的声音。欢迎您与我们分享使用这些**开源项目的亲身体验和评价**，用最真实反馈为开源项目的作者注入动力。


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241111200017365-874137301.png)


### 2\.1 B 站视频空降助手：BilibiliSponsorBlock


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241111200020944-541171856.png)


**主语言：TypeScript**


这是一款能够自动跳过 B 站视频中恰饭片段和开场、结尾动画的浏览器插件，所有标注数据均由网友贡献，支持 Chrome、Edge 和 FireFox 浏览器。



> 项目详情→[hellogithub.com/repository/298fa9ba909c49428c1dc7f8c401bbbd](https://github.com):[悠兔机场](https://xinnongbo.com)


### 2\.2 免费的 Windows 应用卸载神器：Bulk\-Crap\-Uninstaller


![](https://img2024.cnblogs.com/blog/759200/202411/759200-20241111200025995-700394719.png)


**主语言：C\#**


这是一个用 C\# 开发的 Windows 软件卸载工具，能够快速删除大量不需要的应用程序。它完全免费、开箱即用，支持批量和强制卸载、清理残留文件、检测隐藏或受保护的已注册应用等功能。虽然面向 IT 专业人员设计，但其简单的默认设置，让任何人都能轻松上手。



> 项目详情→[hellogithub.com/repository/e5745984014e47f1a33648c0425256a0](https://github.com)


## 3\. 结尾


以上就是本期「GitHub 热点速览」的全部内容，希望你能够在这里找到自己感兴趣的开源项目，如果你有其他好玩、有趣的 GitHub 开源项目想要分享，欢迎来 [HelloGitHub](https://github.com) 与我们交流和讨论。


**往期回顾**


* [开源的 API 学习平台](https://github.com)
* [自建互联网档案馆](https://github.com)


