# PromptReps：激发大型语言模型的潜能，为零样本文档检索任务生成既密集又稀疏的表示方法。

发布时间：2024年04月29日

`LLM应用` `文档检索`

> PromptReps: Prompting Large Language Models to Generate Dense and Sparse Representations for Zero-Shot Document Retrieval

# 摘要

> 目前，大型语言模型（LLMs）在零样本文档排序的应用主要有两种策略：一是无需额外训练的基于提示的重新排序方法，尽管它因计算成本高而只适用于有限的候选文档集；二是能够遍历整个文档库的无监督对比训练密集检索方法，但这需要大量成对文本数据进行训练。本文提出了一种名为PromptReps的新方法，它融合了上述两种方法的优势——既无需训练又能全面检索文档库。该方法通过提示引导LLM生成查询和文档的表示，以便于高效检索。具体而言，我们让LLM用一个词来表示一段文本，然后利用该词的隐藏状态及其对应的预测下一个词的logits，构建一个混合型的文档检索系统。这一系统结合了LLM生成的密集文本嵌入和稀疏词袋模型。我们在BEIR零样本文档检索数据集上的实验评估显示，这种基于提示的LLM检索方法在检索效果上能与那些利用大量无监督数据训练的顶尖LLM嵌入方法相媲美，甚至在采用更大模型时更胜一筹。

> The current use of large language models (LLMs) for zero-shot document ranking follows one of two ways: 1) prompt-based re-ranking methods, which require no further training but are feasible for only re-ranking a handful of candidate documents due to the associated computational costs; and 2) unsupervised contrastive trained dense retrieval methods, which can retrieve relevant documents from the entire corpus but require a large amount of paired text data for contrastive training. In this paper, we propose PromptReps, which combines the advantages of both categories: no need for training and the ability to retrieve from the whole corpus. Our method only requires prompts to guide an LLM to generate query and document representations for effective document retrieval. Specifically, we prompt the LLMs to represent a given text using a single word, and then use the last token's hidden states and the corresponding logits associated to the prediction of the next token to construct a hybrid document retrieval system. The retrieval system harnesses both dense text embedding and sparse bag-of-words representations given by the LLM. Our experimental evaluation on the BEIR zero-shot document retrieval datasets illustrates that this simple prompt-based LLM retrieval method can achieve a similar or higher retrieval effectiveness than state-of-the-art LLM embedding methods that are trained with large amounts of unsupervised data, especially when using a larger LLM.

[Arxiv](https://arxiv.org/abs/2404.18424)