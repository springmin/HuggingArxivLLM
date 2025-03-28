# 利用检索增强技术进行结构化生成：将商业文档信息提取视为工具运用
发布时间：2024年05月30日

`RAG`
> Retrieval Augmented Structured Generation: Business Document Information Extraction As Tool Use
>
> 商业文档信息提取（BDIE）旨在将杂乱无章的信息（如原始文本、扫描文档）转化为下游系统可用的结构化数据。该领域主要涉及两大任务：关键信息提取（KIE）和行项目识别（LIR）。本文提出，BDIE应视为一个工具使用问题，其中工具即下游系统。我们创新性地提出了检索增强结构化生成（RASG）框架，该框架在BDIE的KIE和LIR任务上均取得了顶尖成果。本文的贡献可归纳为三点：(1) 通过对比测试，我们发现配备RASG的大型语言模型（LLMs）在BDIE任务上已超越或至少与未配备RASG的顶级多模态模型（LMMs）持平。(2) 我们提出了一种更贴合实际应用的新型行项目识别度量——通用行项目识别度量（GLIRM），相较于现有度量更为实用。(3) 我们开发了一种无需视觉编码器的启发式算法，用于精确计算行项目和表格的边界框。最终，我们认为，尽管LMMs在某些情况下可能略有优势，但在实际应用和BDIE的限制下，LLMs结合RASG通常表现更佳。
>
> https://arxiv.org/abs/2405.20245

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.20245/rasg-v2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.20245](https://arxiv.org/abs/2405.20245)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886