---
title:  文献阅读基本要求
date:   2022-09-15
author: 战立侃
showDate: true
showTOC: true
---

### 1. 提交读书报告的时间

- 每周日晚 23:59:59 之前提交下周两篇论文的读书报告。

### 2. 追踪和浏览文献

- 定期浏览学术论文新闻快讯网站，如 [eurekalert](https://www.eurekalert.org) 和 [science daily](https://www.sciencedaily.com) 等。
- 定期浏览你感兴趣学者或研究机构的网站主页或社交媒体账号，如 twitter 和 Google Scholar 等等。
- 定期浏览重要综合性杂志的网站主页。实证类研究杂志如 [Nature](https://www.nature.com), [Science](https://www.sciencemag.org), [Neuron](https://www.cell.com/neuron/home), [Current Biology](https://www.cell.com/current-biology/home), [PNAS](https://www.pnas.org), [Nature Neuroscience](https://www.nature.com/neuro/), [Nature human behavior](https://www.nature.com/nathumbehav/) 等等；综述类研究杂志如 [Trends in Cognitive Sciences](https://www.cell.com/trends/cognitive-sciences/home), [Nature Reviews Neuroscience](https://www.nature.com/nrn/), [Nature Reviews Psychology](https://www.nature.com/nrpsychol/), [Annual review of psychology](https://www.annualreviews.org/journal/psych), [Behavioral and Brain Sciences](https://www.cambridge.org/core/journals/behavioral-and-brain-sciences), [Psychological Review](https://www.apa.org/pubs/journals/rev), [Psychological Bulletin](https://www.apa.org/pubs/journals/bul), [Neuroscience & Biobehavioral Reviews](https://www.sciencedirect.com/journal/neuroscience-and-biobehavioral-reviews) 等等。

### 3. 检索和筛选文献

- 利用文献搜索引擎和相关关键词进行搜索，主要文献搜索引擎为：[Web of Science](https://apps-webofknowledge-com-443.webvpn.blcu.edu.cn) （需要校园IP或VPN登入）。
- 输入关键词进行搜索，常见搜索范围文章标题（Title）、摘要（Abstract）、你的兴趣点 Topic（Title + Abstract + Key words）、或杂志名称（Publication Name）；并进一步界定检索的时间范围（Timespan，建议设定为近五年）、数据库（建议仅选择 SCI-EXPANDED 和 SSCI 两个数据库）等。
- 注意使用 Web of Science 的[搜索规则](https://images-webofknowledge-com-443.webvpn.blcu.edu.cn//WOKRS535R100/help/WOS/hs_search_rules.html)。常用[逻辑词](https://images-webofknowledge-com-443.webvpn.blcu.edu.cn//WOKRS535R100/help/WOS/hs_search_operators.html) 有：`NEAR/x`，`SAME`，`NOT`，`AND`，`OR`，以及圆括号 `()` 等；常用[替代符号](https://images-webofknowledge-com-443.webvpn.blcu.edu.cn//WOKRS535R100/help/WOS/hs_wildcards.html)有：`*`, `?` 和 `$` 等；
- 对搜索结果进行进一步筛选：文章领域类别（Web of Science Categories，建议用排除法，即 `Exclude` 很明显不是本学科领域的类别）、文档种类（Document Types, 建议只选择实证论文和综述两项）、论文语言（Languages，只选择英语），和文章的发表时间（Publication Years）。
- 按一定保准对搜索和筛选到的论文进行排序，如论文发表时间（Date）、被引用次数（Time Cited）、相关度（Relevance）等。 浏览感兴趣的文献，包括题目、关键字和摘要等，以及兴趣文献引用的其他文献和引用兴趣文献的其他文献。同等条件下，文献选择的另外一个参考标准是文章发表的杂志水平较高（影响因子较高或本领域内有较高的知名度）。

### 4. 下载文献和电子书

- 本周要报告的两篇文献可以通过文献浏览或文献检索其中一种方式确定。
- 文献确定后，用文献的 DOI 或题目到全文下载工具中下载文献全文，如 [http://sci-hub.se](http://sci-hub.se) 或 [https://sci-hub.st](https://sci-hub.st)
- 其他常见电子书可以从 [http://libgen.is](http://libgen.is) 搜索和下载。

### 5. 准备和提交相关材料

- 需要准备的材料：原始论文、支持资料、读书报告。

- 每个人在代码库的 `content/read/` 目录下都有一个以你自己名字命名的文件夹，如 `_introduction`。你需要把你的读书报告上传到该路径的根目录下。文件夹下还有（如果没有请自行创立）两个子文件夹 `Source_Files` 和 `Supporting_Information`，你需要把原始论文和支持资料（读书报告中用到的图和表）分别传到这两个文件夹里。
- 原始论文：如果你姓名的首字母为 `ZLK`, 你在 `2020-10-26` 提交了本周需要报告的第 `1` 篇文章，那么这篇文章的信息就是 `2020-10-26-ZLK1`。你需要把原始论文重新命名为 `2020-10-26-ZLK1.pdf` 并上传到 `Source_Files` 文件夹下。
- 支持资料（没有用到支持材料可以不上传）：如果你的读书报告包含了一些图片和表格，那么这些表格也应该遵循类似的逻辑，例如上述这篇文章的第一幅图就可以命名为 `2020-10-26-ZLK1-Fig-1.png`，以此类推。并把这些文件上传到 `Supporting_Information` 文件夹下。
- 读书报告：读书报告需要用 `markdown` 格式书写，每篇论文对应一个 `.md` 文档。每个文档以如下格式 `2020-10-26-ZLK1.md` 命名，并上传到以你名字命名的文件夹中。有关 `markdown` 文档格式的更多信息，请参看：[https://commonmark.org](https://commonmark.org)。

- 下面是 `_introduction` 文件夹目前的结构 (注：该文件夹下文件的命名格式没有遵循上述标准，但文件夹结构与上述描述是一致的。）

```bash
_introduction
├── Source_Files
│   └── APA7th.pdf
├── Supporting_Information
│   └── Table-8-1-Basic-In-Text-Citation-Styles.png
├── _index.md
└── read-tips.md
```

### 6. 撰写读书报告

- 注意：本部分讲的是 `markdown` 文档的基本格式。

(1) 表头 (front matter)

- 每个 `md` 文档必须有一个文档表头（front matter）。表头的开始和结尾由 “`---`”。该符号不能缺失，且必须独占一行。
- 理论上来讲，表头可以包含很多内容。但目前我们用到的是下面一些：
```md
---
title:  表达文章主旨；与论文题目一致或不一致均可
author: 你的中文名字
date:   提交本报告的日期，要用如下格式 2020-10-26
showDate: true #是否在文章列表和在正文中显示日期，并在正文中显示作者？
showTOC: true  #是否在在文章开头添加目录？
---
```

(2) 正文

- 论文信息：[APA7th](../Source_Files/APA7th.pdf) 格式。
- 研究背景：研究者为什么要开展这项研究？前人研究有什么不足（本研究要解决什么问题），这项研究是否真如作者所言的那么重要？
- 研究方法：被试、材料、任务、过程等。研究的自变量是什么？自变量的水平有什么？因变量是什么？因变量的类型是什么？问自己，“如果让你重复开展这项实验，你能否完成？如果不能完成，为什么？是你不明白方法的细节，还是文章对细节讲的不够清楚？”
- 数据分析：用了什么统计方法 （统计软件的介绍重要，但是具体的统计方法更重要，因为同一种方法可以在不同的统计软件或编程语言中实现）？为什么用这种方法？问自己，“如果把数据给你，你能不能重复这种分析过程？”
- 研究结果：得出了什么结论？用什么方法展示了这种结论？
- 讨论和拓展：记住，“没有一项研究是完美的”，文章是否真如作者所言解决了他们要解决的问题？解决文章提到的类似问题有什么其他替代方案？该研究方法是否可以用来研究其他问题？有哪些问题是文章没有解决的？有哪些方面和角度是可以进一步发展和研究的？
- 其他任何你觉得有必要说的信息。
- 报告中用到的其他参考文献。正文中提到参考文献，请遵循以下 APA 格式：

![图1](../Supporting_Information/Table-8-1-Basic-In-Text-Citation-Styles.png)

(3) 支持资料：

- 在正文中添加原始论文链接：\
    `[论文原文](../Source_Files/APA7th.pdf)`
- 在正文中使用支持资料：\
    `![APA7th](../Supporting_Information/Table-8-1-Basic-In-Text-Citation-Styles.png)`

### 7. 小组讨论

- 每周一到两次小组讨论。讨论内容可以是一篇读书报告或者是自己研究的进展报告。
- 无论是自己的研究报告还是读书报告，报告整体上都应该是一个有上下文逻辑关系的故事 (Story)。
- 在报告自己或别人研究时，应该尽量少用或不用 `代词`(如你、我、她)，而是用名词，因为代词含义具有歧义性。
- 听别人的报告：记住，“如果我没明白，一定是作者写的不清楚，而不是我的理解力有问题”。
- 关于提问题：聆听报告过程中提出合理的问题是对报告者的最大尊重，因为这说明你仔细听讲并且听懂了。

### 8. 后记

- 所以在学习过程中，记住《论语》的这句话：“学而不思则罔，思而不学则殆”。要多读书，但不要死读书，不要读死书，要勤于思考。