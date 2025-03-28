# SafePlan: 借助形式逻辑与链式推理，提升LLM驱动机器人任务规划的安全性

发布时间：2025年03月09日

`LLM应用` `机器人` `系统安全`

> SafePlan: Leveraging Formal Logic and Chain-of-Thought Reasoning for Enhanced Safety in LLM-based Robotic Task Planning

# 摘要

> 机器人研究领域正越来越多地借助大型语言模型（LLM）作为接口，实现任务指令接收、任务计划生成、团队协作以及任务分配。然而，尽管LLM的应用为机器人技术带来了诸多优势，但其广泛采用也引发了诸多安全问题，尤其是与执行恶意或不安全自然语言提示相关的风险。此外，确保LLM生成的任务计划、团队构成和任务分配结果得到充分审查、优化或拒绝，对于维护系统完整性至关重要。

本文中，我们推出了SafePlan——一个结合形式逻辑与链式推理器的多组件框架，旨在提升基于LLM的机器人系统的安全性。通过SafePlan的组件，包括提示合理性CoT推理器和不变式、前提条件及后置条件CoT推理器，我们对基于LLM的机器人系统生成的自然语言任务提示、任务计划和任务分配结果的安全性进行了深入评估，以此探究并提升系统安全性能。实验结果显示，相较于基线模型，SafePlan使有害任务提示的接受率降低了90.5%，同时仍保持对安全任务的合理接受度。

> Robotics researchers increasingly leverage large language models (LLM) in robotics systems, using them as interfaces to receive task commands, generate task plans, form team coalitions, and allocate tasks among multi-robot and human agents. However, despite their benefits, the growing adoption of LLM in robotics has raised several safety concerns, particularly regarding executing malicious or unsafe natural language prompts. In addition, ensuring that task plans, team formation, and task allocation outputs from LLMs are adequately examined, refined, or rejected is crucial for maintaining system integrity. In this paper, we introduce SafePlan, a multi-component framework that combines formal logic and chain-of-thought reasoners for enhancing the safety of LLM-based robotics systems. Using the components of SafePlan, including Prompt Sanity COT Reasoner and Invariant, Precondition, and Postcondition COT reasoners, we examined the safety of natural language task prompts, task plans, and task allocation outputs generated by LLM-based robotic systems as means of investigating and enhancing system safety profile. Our results show that SafePlan outperforms baseline models by leading to 90.5% reduction in harmful task prompt acceptance while still maintaining reasonable acceptance of safe tasks.

[Arxiv](https://arxiv.org/abs/2503.06892)