---
title:  4.读书报告
showTOC: true
---

## 1. 提交读书报告的时间

- 每周日晚 23:59:59 之前提交下周两篇论文的读书报告。

## 2. 准备和提交相关材料

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

## 3. 撰写读书报告

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

- 应包含[阅读文献](../2-literature_read) 部分提到的内容；
- 其他任何你觉得有必要说的信息；
- 在提供本次阅读的文献、读书报告中的其他文献时都应遵循 [APA7th](../Source_Files/APA7th.pdf) 格式

![图1](../Supporting_Information/Table-8-1-Basic-In-Text-Citation-Styles.png)

(3) 支持资料：

- 在正文中添加原始论文链接：\
    `[论文原文](../Source_Files/APA7th.pdf)`
- 在正文中使用支持资料：\
    `![APA7th](../Supporting_Information/Table-8-1-Basic-In-Text-Citation-Styles.png)`