---
layout: default
title: "Horizon Summary: 2026-09-23 (ZH)"
date: 2026-09-23
lang: zh
---

> 从 198 条内容中筛选出 15 条重要资讯。

---

**科技新闻**
1. [llm 0.36 版本更新：新增 OpenAI 模型及插件兼容性改进](#item-tech-news-1) ⭐️ 8.0/10
2. [AI 代理群体中的间接倾覆机制：一种新的安全风险](#item-tech-news-2) ⭐️ 8.0/10
3. [基于 LLM 的多智能体系统中关于气候变化行动的立场临界点研究](#item-tech-news-3) ⭐️ 8.0/10
4. [执行溯源如何帮助代理记忆检索](#item-tech-news-4) ⭐️ 8.0/10
5. [面向痴呆护理的受监管 AI 代理协调架构与安全合约](#item-tech-news-5) ⭐️ 8.0/10
6. [校准不等于验证：面向混合智能体的可证伪性感知路由方法](#item-tech-news-6) ⭐️ 8.0/10
7. [MATES：通过观察转换学习多智能体交互以利用预训练单智能体策略](#item-tech-news-7) ⭐️ 8.0/10
8. [Fusion-MoA：通过融合模型实现集体智能的新运行时系统](#item-tech-news-8) ⭐️ 8.0/10
9. [行为不足以判断：LLM 社会中社会规范形成的机制评估](#item-tech-news-9) ⭐️ 8.0/10
10. [Qwen-Audio-Agent 技术报告](#item-tech-news-10) ⭐️ 8.0/10
11. [全拜占庭容错多智能体强化学习方法 FRAC-MARL 提出](#item-tech-news-11) ⭐️ 8.0/10
12. [PrismAlign 重新定义文档结构化提取的精度上限](#item-tech-news-12) ⭐️ 8.0/10
13. [Shopify 放弃 React Native，转向 Swift 和 Kotlin](#item-tech-news-13) ⭐️ 8.0/10
14. [Pinterest 放弃 HNSW，转向量化 SPANN 提升向量搜索效率](#item-tech-news-14) ⭐️ 8.0/10

**财经新闻**
1. [亚马逊 AWS 订单积压达 4960 亿美元，云业务利润率升至 39%](#item-finance-news-1) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [llm 0.36 版本更新：新增 OpenAI 模型及插件兼容性改进](https://simonwillison.net/2026/Sep/22/llm/) ⭐️ 8.0/10

llm 0.36 版本新增了对 OpenAI 的 GPT-6 Sol 和 GPT-6 Luna 模型的支持，并改进了插件在对话处理中的兼容性。该版本还引入了对 Markdown 输出中推理追踪的封装功能，以及来自五位新贡献者的 bug 修复。这些更新有助于开发者更灵活地使用模型插件，并提升调试体验。

rss · Simon Willison · 9月22日 18:48

**「背景信息」** llm 是一个用于与大型语言模型（LLM）交互的开源工具，支持多种模型和插件。OpenAI 的 GPT-6 Sol 和 GPT-6 Luna 是较新的模型，提供不同的功能和性能优化。插件兼容性改进旨在让开发者更方便地集成和使用这些模型。

**「影响」** llm 0.36 的更新使开发者能够使用新的 OpenAI 模型，并通过插件声明模型是否支持对话，从而避免不兼容的错误。这提升了工具的灵活性和用户体验。

**「社区讨论」** 目前没有社区评论可供参考。

**标签**: `#software-engineering`, `#ai`, `#machine-learning`, `#open-source`, `#tooling`

---

<a id="item-tech-news-2"></a>
### [AI 代理群体中的间接倾覆机制：一种新的安全风险](https://arxiv.org/abs/2609.25194) ⭐️ 8.0/10

该研究探讨了 AI 代理群体中的间接倾覆机制，揭示了在大规模部署生成式 AI 代理时，安全不仅依赖于技术防护和个体模型设计，还取决于群体如何处理信息、优先行动和应对不确定性。研究指出，传统的关键质量动态框架可能低估了系统脆弱性，因为它将问题简化为单一的倾覆点，而忽略了通过中间过渡状态进行间接影响的更有效途径。通过实验和分析框架，研究绘制了协调均衡之间的关键质量阈值，并将其视为可导航的景观，表明间接倾覆可以降低所需少数群体的比例，绕过多数群体要求，并使某些转变无法通过直接挑战实现。研究强调，均衡的抗干预能力并非固有属性，而是其与替代状态竞争关系的结构特征，因此保护 AI 代理群体需要同时考虑社会景观、个体能力和技术交互渠道。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「AI 代理群体中的间接倾覆机制」** 该研究探讨了 AI 代理群体中间接倾覆机制，指出协调均衡虽然有助于代理间的协作，但也可能形成社会攻击面。传统方法通过直接竞争来评估系统脆弱性，但本文强调间接倾覆路径可能更高效，且不同均衡之间的竞争关系决定了系统的稳定性。此外，研究还提到 LLM 代理群体在大规模部署中会自发形成共享惯例，这表明此类动态在 AI 系统中具有广泛适用性。

**「间接引导对 AI 代理群体安全构成新威胁」** 该研究揭示了 AI 代理群体中间接引导机制的存在，表明恶意行为者可以通过非直接竞争的方式更高效地改变集体行为，从而降低颠覆系统所需的少数群体比例。这种间接引导方式可能绕过多数群体的约束，使某些状态转换变得不可访问，增加了系统在大规模部署时的安全风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2609.25194">Indirect tipping: a social attack surface in AI agent populations</a></li>
<li><a href="https://arxiv.org/abs/2609.25194">[2609.25194] Indirect tipping: a social attack surface in AI agent populations</a></li>
<li><a href="https://arxiv.org/html/2608.07810">Mobility, Memory, and Network Structure in Agent-Based Models of Convention Tipping and Convergence</a></li>
<li><a href="https://research.nvidia.com/publication/2026-03_architecting-secure-ai-agents-perspectives-system-level-defenses-against">Architecting Secure AI Agents: Perspectives on System-Level ...</a></li>
<li><a href="https://afadeev.substack.com/p/hidden-instructions-in-trusted-data">Hidden Instructions in Trusted Data: Indirect Prompt ...</a></li>
<li><a href="https://developer.nvidia.com/blog/mitigating-indirect-agents-md-injection-attacks-in-agentic-environments/">Mitigating Indirect AGENTS.md Injection Attacks in Agentic ...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#agent dynamics`, `#collective behavior`, `#security`, `#machine learning`

---

<a id="item-tech-news-3"></a>
### [基于 LLM 的多智能体系统中关于气候变化行动的立场临界点研究](https://arxiv.org/abs/2609.25432) ⭐️ 8.0/10

该论文探讨了基于大型语言模型（LLM）的多智能体系统中关于气候变化行动的社会临界点，揭示了 AI 如何模拟和影响公众意见。研究通过监测多轮对话中智能体在两个维度（对气候行动紧迫性的信念强度和对现有机构的信任度）的立场距离，以及使用潜在狄利克雷分布（LDA）建模的讨论主题模式，量化了立场变化。研究结果表明，在这种简单的模型中确实会发生关于气候变化立场的显著突变。此外，论文还强调了防止 LLM 偏见干扰对话动态，并在面对这些偏见时保持智能体个性和互动记忆的重要性。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「社会临界点与多智能体系统的研究背景」** 社会临界点是指小的个体行为变化可能引发大规模社会转变的现象，这种现象在气候变化讨论中尤为重要。多智能体系统（ABM）被用于模拟和研究这些动态，因为它可以系统地探索干预措施的影响。此外，多智能体网络中的偏见放大效应也已被研究，其中某些智能体持有固定观点，而另一些则会逐步调整意见。

**「LLM-ABM 研究对气候行动社会干预设计的影响」** 该研究揭示了 LLM 驱动的多智能体系统在模拟社会动态时能够识别气候行动立场的突变点，这为设计实际的气候干预措施提供了新的方法论支持。研究强调了防止 LLM 偏见干扰对话动态的重要性，以及保持智能体个性和互动记忆的必要性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/rachael-shwom_scientists-question-use-of-tipping-point-activity-7269933568817029120-Ey3a">I first wrote a paper about tipping elements with Bob Kopp in 2018...</a></li>
<li><a href="https://arxiv.org/html/2609.18306">Bias Amplification in Multi - Agent Network: How Biased Agents Shape...</a></li>
<li><a href="https://theconversation.com/climate-change-can-drive-social-tipping-points-for-better-or-for-worse-210641">Climate change can drive social tipping points – for better or for worse</a></li>
<li><a href="https://arxiv.org/html/2609.25432v1">Tipping Points in LLM-Based Multi-Agent Systems: Stance on Climate Change Action - arXiv</a></li>
<li><a href="https://www.nature.com/articles/s44168-026-00375-1">On using large language models to support social research for climate action - Nature</a></li>
<li><a href="https://www.preprints.org/manuscript/202606.1832">Multi-Agent Social Simulation: Protocolizing LLM-Driven Agent-Based Modeling as a Quantitative Research Method - Preprints.org</a></li>

</ul>
</details>

**标签**: `#AI`, `#multi-agent systems`, `#climate change`, `#LLM`, `#social dynamics`

---

<a id="item-tech-news-4"></a>
### [执行溯源如何帮助代理记忆检索](https://arxiv.org/abs/2609.25913) ⭐️ 8.0/10

这项研究提出了一种改进代理记忆检索的方法，通过将检索问题建模为预算证据完成，并使用源对齐的溯源单元结合残差 R-GCN 模型。传统检索方法使用固定长度的标记窗口和固定-k 指标，无法判断完整证据集是否适合上下文。该方法在 1,207 条执行相关的 ISETrace 轨迹上评估了 2,000 个基于跨度的记忆查询，结果显示源对齐的溯源单元在 Full Support@2048 指标上比固定 512 标记窗口提升了 19.07 分，并且在四种固定块大小上仍高出 11.96 分。此外，图传播在保持候选和种子分数不变的情况下，进一步提升了 4.55 分，表明其对跨事件证据的集中作用。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「背景信息」** 该研究提出了一种改进语言代理记忆检索的新方法，通过将记忆检索问题建模为预算证据完成，并利用源对齐的来源单元与残差 R-GCN 模型进行优化。传统方法通常使用固定长度的标记窗口和固定-k 指标，这些方法无法有效评估完整证据集是否适合上下文。相比之下，该方法通过构建源对齐的来源单元，并在类型化的来源边基础上应用残差 R-GCN 模型，以提升检索效果。

**「执行溯源对代理记忆检索的提升效果」** 该研究通过将代理记忆检索问题转化为预算证据完成任务，并结合源对齐的溯源单元与残差 R-GCN 模型，显著提升了检索性能。实验结果显示，在 2,000 个基于跨度的记忆查询中，使用源对齐的候选单元使 Full Support@2048 指标比固定 512 标记窗口提升了 19.07 分，并且在四种固定块大小的平铺检索中仍保持 11.96 分的优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dev.to/memtensor/agent-memory-is-not-rag-a-2026-production-field-guide-35ih">Agent Memory Is Not RAG: A 2026 Production... - DEV Community</a></li>
<li><a href="https://cohorte.co/blog/ai-agent-memory-architecture-governed-writes">AI Agent Memory Architecture: Governed Writes, Not Storage</a></li>
<li><a href="https://agentpatterns.ai/verification/">Verification: Testing, Evals, and Guardrails for Agents - AgentPatterns.ai</a></li>
<li><a href="https://cohere.com/blog/data-provenance">A Business Guide to Data Provenance - Cohere</a></li>
<li><a href="https://elevateconsult.com/insights/finalizing-the-data-provenance-strategy-for-ai-data-governance/">AI Data Provenance Strategy: Finalizing in 2026 - Elevate Consult</a></li>
<li><a href="https://www.longtermwiki.com/wiki/E597">AI Content Provenance Tracing - Longterm Wiki</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S003132032501310X">RA-GCN: Residual attention based graph convolutional network ...</a></li>

</ul>
</details>

**标签**: `#AI research`, `#agent memory`, `#retrieval systems`, `#provenance`, `#language models`

---

<a id="item-tech-news-5"></a>
### [面向痴呆护理的受监管 AI 代理协调架构与安全合约](https://arxiv.org/abs/2609.25956) ⭐️ 8.0/10

该论文介绍了 GCAC 架构，这是一种面向痴呆护理的受监管 AI 代理协调系统，强调通过系统方法实现安全、责任和工作流程验证。GCAC 通过类型化的事件-记忆-决策-行动-结果合约，将观察、受监管记忆、规划、确定性政策执行、执行和结果监控分离。参考框架评估了 18 个基于证据的追踪，涵盖缺失记录、药物冲突、护理人员报告、服务失败、同意变更、过时状态、重复事件、不可信文本和疑似急性神经变化等场景。GCAC 满足所有 18 个合约预言，没有违反政策的工具调用，并正确保留义务、拒绝过时状态、创建人工交接并记录工作流程关闭。事件阈值和无状态规划器控制分别满足 2/18 和 1/18 个预言。组件消融实验将失败归因于移除的记忆、政策或版本控制功能。研究结果证明了架构符合性，而非临床有效性，并展示了代理系统如何在保持人类对关键护理决策的权威性的同时，自动化协调、路由、文档记录和后续跟进。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「背景介绍」** 该论文提出了一种名为 GCAC 的架构，用于在社区痴呆护理工作中实现受控的 AI 代理协调。GCAC 通过将护理协调失败的证据和政策义务转化为可追溯的系统需求，强调了安全、责任和工作流验证的重要性。研究还指出，当前的数字痴呆护理解决方案大多局限于单层功能，缺乏跨层协调的实证支持。

**「GCAC 架构在痴呆护理中的影响」** GCAC 架构通过系统方法解决了痴呆护理中跨设备互操作性、责任归属和治理的关键问题，确保了所有 18 个合同预言的满足，且未违反任何政策工具调用。该架构能够自动化协调、路由、记录和跟进流程，同时保留人类对关键护理决策的权威。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.25956">[2609.25956] Governed AI-Agent Coordination for Dementia Care: Architecture, Safety Contracts, and Evidence-Derived Workflow Verification</a></li>
<li><a href="https://arxiv.org/html/2609.25956">Governed AI-Agent Coordination for Dementia Care: Architecture, Safety Contracts, and Evidence-Derived Workflow Verification</a></li>
<li><a href="https://pubmed.ncbi.nlm.nih.gov/42602204/">Bridging the islands of innovation: A machine-assisted Semantic-Bibliometric review and conceptual roadmap for closed-loop digital dementia care - PubMed</a></li>
<li><a href="https://arxiv.org/abs/2609.25956">Governed AI-Agent Coordination for Dementia Care ...</a></li>

</ul>
</details>

**标签**: `#AI systems`, `#agent coordination`, `#healthcare AI`, `#software engineering`, `#safety contracts`

---

<a id="item-tech-news-6"></a>
### [校准不等于验证：面向混合智能体的可证伪性感知路由方法](https://arxiv.org/abs/2609.25959) ⭐️ 8.0/10

C-MoA 和 CONTRA-MoA 是一种新的方法，用于通过符合性过滤和反事实可证伪性增强异构多智能体系统中的事实性。C-MoA 通过将智能体间的语义支持转化为声明级别的非符合性得分，并在示例级别校准保留阈值，实现无分布假设的领域内事实性控制。C-MoA 在长文本生成中显著提升了保留声明的精确度（从 0.41 提高到 0.75），并能在不同领域间迁移而无需重新校准。然而，它在短文本回答中的表现不佳，因为共识成本较低且得分接近随机。CONTRA-MoA 在验证者具备领域知识时能有效减少错误医疗声明，精确度达到 0.940，而仅依赖记忆的验证者则效果有限（AUC 0.531 和 0.511）。此外，简单的最大融合方法会降低工作共识信号（从 0.687 降至 0.652）。该方法的核心信息是：基于共识的符合性校准能提供可靠且可迁移的事实性控制，而超越共识则需要具备领域知识的验证者、可用性感知信号和稳健的融合机制。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「背景信息」** 多智能体语言系统通常将共识视为正确性的证据，但异构智能体可能共同重复不支持的主张或遗漏正确的专业事实。C-MoA 和 CONTRA-MoA 是新的方法，通过利用符合性过滤和反事实可证伪性来增强事实性。这些方法旨在解决多智能体系统中事实性控制的问题，特别是在不同领域和任务中保持可靠性和可转移性。

**「新方法提升多智能体系统事实性控制的可靠性与可迁移性」** C-MoA 和 CONTRA-MoA 通过引入基于共识的校准机制和反事实可证性策略，显著提升了多智能体系统在长文本生成中的事实性控制效果，将保留声明的精确度从 0.41 提高到 0.75，并在医疗领域验证了其有效性。然而，这些方法在短文本回答任务中表现不佳，依赖于领域知识的验证者才能有效提升事实性控制的精度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2403.16871">[2403.16871] Conformal Off-Policy Prediction for Multi-Agent Systems - arXiv</a></li>
<li><a href="https://www.linkedin.com/posts/jae-oh-woo-45666829_from-debate-to-decision-conformal-social-activity-7453807339666837504-CWNj">Conformal Prediction for Multi-Agent Systems with AWS and HSBC ...</a></li>
<li><a href="https://arxiv.org/abs/2511.11567">[2511.11567] Who Moved My Distribution? Conformal Prediction for Interactive Multi-Agent Systems - arXiv</a></li>
<li><a href="https://www.emergentmind.com/topics/factuality-controlled-generation-fcg">Factuality - Controlled Generation</a></li>
<li><a href="https://gogloby.com/insights/ai-guardrails/">What Are AI Guardrails? LLM Safety Controls , Examples... | GoGloby</a></li>
<li><a href="https://www.alphaxiv.org/abs/2606.08831v1">Inference-Time Conformal Reasoning with Valid Factuality Control for...</a></li>

</ul>
</details>

**标签**: `#multi-agent systems`, `#AI systems`, `#factuality control`, `#conformal prediction`, `#software engineering`

---

<a id="item-tech-news-7"></a>
### [MATES：通过观察转换学习多智能体交互以利用预训练单智能体策略](https://arxiv.org/abs/2609.26010) ⭐️ 8.0/10

MATES 是一种新的框架，使多智能体系统能够使用预训练的单智能体策略，通过转换观察来保留任务特定信息并识别邻居。该方法在不更新单智能体策略的情况下，学习一个小型适配器，将多智能体观察转换为单智能体策略所需的格式，从而诱导适合共享环境的动作。MATES 保持预训练策略的内部架构不变，并保留底层多智能体强化学习算法的目标和更新过程。在终身路径规划、导航和协作发现任务中，使用基于策略的算法和离策略算法进行评估，结果显示 MATES 仅优化 3.5-7.3% 的参数，同时在所有评估设置中持续优于从头训练的多智能体强化学习方法。它接近完整微调的性能，与基于演示的基线保持竞争力，并在训练时未遇到的团队规模下仍能保持强大的任务表现。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「多智能体系统中单智能体策略的适应性框架」** MATES 是一种输入端适应框架，旨在使多智能体系统能够利用预训练的单智能体策略。该框架通过转换观测数据，保留单任务信息并暴露可识别的邻居信息，从而在不修改单智能体策略的情况下，使智能体适应多智能体环境。这种设计允许在多智能体任务中仅优化少量参数，同时保持策略的性能。

**「MATES 对软件工程和 AI 系统协作的影响」** MATES 通过将单智能体策略适配到多智能体环境，显著减少了训练参数数量，提升了多智能体系统的效率，这可能推动 AI 在软件工程中的应用，如动态适应和协作任务优化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2609.26010">MATES: Learning Multi-Agent Interactions by Transforming Observations for Frozen Single-Agent Policies</a></li>
<li><a href="https://arxiv.org/abs/2609.26010">[2609.26010] MATES: Learning Multi-Agent Interactions by Transforming Observations for Frozen Single-Agent Policies</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0893608026002170">Efficient multi-agent policy adaptation with Bayesian policy ...</a></li>
<li><a href="https://dl.acm.org/doi/10.1145/3715111">Software Engineering by and for Humans in an AI Era - ACM Digital Library</a></li>
<li><a href="https://www.bu.edu/eng/2026/02/04/what-is-software-engineering-for-artificial-intelligence/">Integrating Software Engineering and Artificial Intelligence: What to Expect from Tomorrow&#x27;s Intelligence Systems | College of Engineering - Boston University</a></li>
<li><a href="https://nhsjs.com/2025/the-augmentative-role-of-ai-in-software-engineering-a-global-expert-survey/">The Augmentative Role of AI in Software Engineering: A Global Expert Survey - NHSJS</a></li>

</ul>
</details>

**标签**: `#multi-agent systems`, `#reinforcement learning`, `#AI research`, `#software engineering`, `#machine learning`

---

<a id="item-tech-news-8"></a>
### [Fusion-MoA：通过融合模型实现集体智能的新运行时系统](https://arxiv.org/abs/2609.26080) ⭐️ 8.0/10

Fusion-MoA 是一种新的运行时系统，允许异构模型作为单一的 OpenAI 兼容模型协同工作，从而实现集体智能。该系统通过版本化的 Profile 控制成员资格和证据接纳，使读取-only Analysts 贡献有限的证据，而唯一的 Executor 保留最终答案和工具的权威。在评估中，一个包含八个 Cell 和三个谱系的部署在固定 HMMT P1-P10 切片上解决了 8/10 个问题，而最强的单个 Cell 仅解决 6/10 个问题。此外，所有工具操作都可追溯到一个 Executor，且没有 Analyst 操作或绕过效应。六个多 Cell 被提升，一个不兼容的候选者被本地回滚，同时服务保持可用。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「Fusion-MoA 的背景」** Fusion-MoA 是一种新的运行时系统，它允许异构模型以单一 OpenAI 兼容模型的形式运行，从而实现集体智能。该系统通过版本化的 Profile 控制成员资格和证据接纳，并区分只读 Analysts 和唯一 Executor，以确保模型的稳定性和可控性。

**「Fusion-MoA 的影响」** Fusion-MoA 通过将异构模型作为单一 OpenAI 兼容模型运行，显著提升了多模型系统的协作能力，使八个单元在三个谱系中解决了 8/10 的问题，优于最强个体单元的 6/10。该系统在保持服务可用性的同时，实现了模型成员的动态调整，包括六次晋升和一次不兼容候选者的本地回滚。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.26080">[2609.26080] The Fleet Is the Model : Engineering Collective ...</a></li>
<li><a href="https://arxiv.org/abs/2609.26080">[2609.26080] The Fleet Is the Model : Engineering Collective ...</a></li>

</ul>
</details>

**标签**: `#AI systems`, `#multi-agent frameworks`, `#model serving`, `#software engineering`, `#collective intelligence`

---

<a id="item-tech-news-9"></a>
### [行为不足以判断：LLM 社会中社会规范形成的机制评估](https://arxiv.org/abs/2609.26481) ⭐️ 8.0/10

该研究提出了一种基于机制的评估框架，用于分析大型语言模型（LLM）社会中的社会规范形成，强调仅通过行为观察无法准确识别社会规范，而需结合实证和规范性期望。研究通过受控的机制消融实验，测试了期望提取对合作行为的影响，并区分了社会学习和网络群体形成中的社会选择两种核心机制。实验还评估了这些机制在对抗性干扰下的稳定性，发现期望提取能提升合作贡献，而社会学习有助于行为稳定，社会选择则能可靠识别合作者但对行为强化作用有限。研究结果表明，相似的合作结果可能源于不同的社会过程，该框架使设计者能够更系统地选择维持合作的社会机制。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「背景信息」** 社会规范的形成通常涉及群体成员的共同期望和行为模式，而非单一行为结果。在多智能体系统中，以往研究多依赖行为收敛作为规范形成的证据，但忽略了期望和激励因素的作用。该研究旨在填补这一方法论空白，通过引入机制评估框架，更全面地理解规范形成过程。

**「影响」** 该研究为多智能体系统的设计者提供了更系统的评估工具，使他们能够识别和选择维持合作的关键社会机制，从而提升系统在复杂环境中的稳定性与适应性。

**标签**: `#AI research`, `#multi-agent systems`, `#social norms`, `#LLM societies`, `#evaluation framework`

---

<a id="item-tech-news-10"></a>
### [Qwen-Audio-Agent 技术报告](https://arxiv.org/abs/2609.25195) ⭐️ 8.0/10

Qwen-Audio-Agent 提出了一种新的音频代理系统架构，实现了无缝的全双工语音交互和异步任务执行。该架构通过前台后台设计，使对话管理与任务执行能够协同工作，提高了任务成功率和执行效率。在内部的智能驾驶舱基准测试中，混合执行模式的任务成功率达到 91.04%，相比直接调用和完全委托模式分别提升了 18.65%和 10.35%。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「技术背景」** 音频代理系统是结合语音交互与任务执行的软件架构，用于处理语音输入并执行相关操作。全双工语音交互允许同时进行语音输入和输出，而异步任务执行则支持在后台处理复杂任务而不中断对话。Qwen-Audio-Agent 通过前台后台分离的设计，优化了这两者的协同工作。

**「技术影响」** Qwen-Audio-Agent 的混合执行模式显著提升了任务成功率和执行效率，尤其适用于需要同时处理多步骤任务和即时操作的场景。其架构设计为音频代理系统提供了新的解决方案，有助于推动语音交互技术在智能驾驶舱、桌面助手和语音客服等领域的应用。

**标签**: `#audio-processing`, `#agent-architecture`, `#voice-interaction`, `#asynchronous-tasks`, `#software-engineering`

---

<a id="item-tech-news-11"></a>
### [全拜占庭容错多智能体强化学习方法 FRAC-MARL 提出](https://arxiv.org/abs/2609.25701) ⭐️ 8.0/10

研究人员提出了一种新的分布式多智能体强化学习方法 FRAC-MARL，旨在确保在通信网络中遭遇拜占庭攻击时仍能实现参数收敛。该方法通过利用两跳消息中的冗余信息来识别可靠消息，从而在存在拜占庭边缘攻击的情况下，使智能体的参数几乎肯定地收敛到与无攻击情况相同的极限点。研究假设价值函数和团队奖励函数为线性参数化，并在时变通信图中证明了其收敛性。此外，研究还引入了一种新的拓扑条件，用于构建满足收敛要求的网络，并证明该条件可在多项式时间内验证。最后，该方法在合作多机器人编队控制任务中进行了演示。

rss · arXiv Multi-Agent Systems · 9月23日 04:00

**「背景信息」** 该研究聚焦于分布式系统中的拜占庭容错多智能体强化学习（AC-MARL），其中现有方法仅能保证参数收敛到无攻击情况下的邻域范围，导致性能下降。为了解决这一问题，作者提出了 FRAC-MARL，一种去中心化方法，通过利用两跳消息的冗余性来识别可靠信息。该方法在价值函数和团队奖励函数的线性参数化条件下，针对拜占庭边攻击（即攻击行为局限于通信层）进行了理论分析。

**「影响」** FRAC-MARL 方法为分布式系统中的多智能体强化学习提供了更强的拜占庭容错能力，有助于提升在对抗性通信环境下的系统稳定性和性能。

**「社区讨论」** 目前没有社区评论可供参考。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.25701">[2609.25701] Fully Byzantine-Resilient Multi-Agent Reinforcement Learning</a></li>
<li><a href="https://arxiv.org/html/2609.25701">Fully Byzantine-Resilient Multi-Agent Reinforcement Learning</a></li>

</ul>
</details>

**标签**: `#multi-agent reinforcement learning`, `#byzantine resilience`, `#distributed systems`, `#ai research`, `#theoretical guarantees`

---

<a id="item-tech-news-12"></a>
### [PrismAlign 重新定义文档结构化提取的精度上限](https://www.infoq.cn/article/ytHwXAq6vHzUm23RNYhk?utm_source=rss&amp;utm_medium=article) ⭐️ 8.0/10

PrismAlign 通过引入多视角立体对齐方法，显著提升了文档结构化提取的准确性和效率，标志着该领域的重要进展。该技术突破解决了传统单目感知方法在处理复杂文档结构时的局限性，为文档处理和信息检索提供了更可靠的基础。其创新性在于将多个视角的信息进行对齐，从而更全面地理解文档内容，提高结构化提取的精度上限。

rss · InfoQ 中国 · 9月23日 22:51

**「技术背景」** 文档结构化提取是将非结构化文本转化为结构化数据的过程，传统方法通常依赖单目感知，即仅从单一视角（如页面布局或文本内容）进行分析。然而，这种方法在处理多语言、多格式或复杂排版的文档时存在局限。PrismAlign 的出现，为这一领域带来了新的解决方案。

**「影响」** PrismAlign 的应用将显著提升文档处理系统的准确性和效率，尤其在处理多语言、多格式文档时表现更优。这将对依赖结构化数据的行业，如金融、法律和学术研究，产生深远影响。

**标签**: `#document processing`, `#AI systems`, `#natural language processing`, `#software engineering`, `#machine learning`

---

<a id="item-tech-news-13"></a>
### [Shopify 放弃 React Native，转向 Swift 和 Kotlin](https://www.infoq.cn/article/2FFH5EHF2SMusaYQhjlX?utm_source=rss&amp;utm_medium=article) ⭐️ 8.0/10

Shopify 正从 React Native 转向 Swift 和 Kotlin 进行跨平台开发，这标志着行业技术策略的重大转变。这一决策反映了对性能、控制力和长期维护的重视，可能影响其他公司对跨平台开发框架的选择。Shopify 的这一变化表明，尽管 React Native 在跨平台开发中具有优势，但其在某些场景下可能无法满足企业级应用的需求。

rss · InfoQ 中国 · 9月23日 17:00

**「Shopify 技术战略调整背景」** Shopify 是一家在电子商务领域具有重要影响力的公司，此前曾采用 React Native 进行跨平台移动应用开发。然而，近期 Shopify 宣布放弃 React Native，转而使用 Swift 和 Kotlin 重新开发其核心应用，这一决策反映了其对技术策略的调整。

**「Shopify 的技术调整对跨平台开发生态产生深远影响」** Shopify 放弃 React Native 转而采用 Swift 和 Kotlin 进行跨平台开发，标志着 AI 技术进步改变了移动开发的权衡方式。这一决策凸显了原生开发在利用平台特性和工具链方面的优势，可能促使更多企业重新评估跨平台框架的适用性。

**「社区讨论」** 目前没有社区评论可供参考。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.com/news/2026/09/shopify-drops-react-native/">Shopify Drops React Native for Swift and Kotlin as AI Changes Cross-Platform Development Tradeoffs - InfoQ</a></li>
<li><a href="https://www.reddit.com/r/programming/comments/1wd7wmu/shopify_is_moving_from_react_native_back_to_swift/">Shopify is moving from React Native back to Swift and Kotlin : r/programming - Reddit</a></li>
<li><a href="https://www.infoq.com/news/2026/09/shopify-drops-react-native/?amp;utm_source=infoq&amp;amp;utm_medium=feed&amp;amp;utm_term=global">Shopify Drops React Native for Swift and Kotlin as AI Changes Cross-Platform Development Tradeoffs - InfoQ</a></li>

</ul>
</details>

**标签**: `#AI`, `#software engineering`, `#cross-platform development`, `#Shopify`, `#technology industry`

---

<a id="item-tech-news-14"></a>
### [Pinterest 放弃 HNSW，转向量化 SPANN 提升向量搜索效率](https://www.infoq.cn/article/rB0WGcG9iLIRH3xZojY5?utm_source=rss&amp;utm_medium=article) ⭐️ 8.0/10

Pinterest 正从 HNSW 向量化搜索算法转向量化 SPANN 算法，以提高搜索效率和可扩展性。这一变化对 AI 和计算机系统有重要影响，特别是在处理数百亿向量时，SPANN 能够更有效地管理内存和计算资源。该技术调整旨在优化大规模向量搜索的性能，同时降低系统对硬件资源的需求。

rss · InfoQ 中国 · 9月23日 11:22

**「HNSW 与 SPANN 的背景」** HNSW（Hierarchical Navigable Small Worlds）是一种用于高精度向量搜索的算法，适用于大规模数据集，但其高内存占用限制了扩展性。SPANN（Simple Approximate Nearest Neighbor for Navigable Networks）则是一种基于倒排索引的高效向量搜索系统，能够在大规模数据集上实现较低的内存消耗和较高的搜索性能。Pinterest 因数据量增长，决定从 HNSW 转向 SPANN 以提升系统的可扩展性和效率。

**「Pinterest 转向量化 SPANN 提升向量搜索效率」** Pinterest 通过将向量搜索系统从 HNSW 切换为量化 SPANN，显著降低了内存使用量，同时保持了高召回率，从而提升了大规模数据下的搜索效率和可扩展性。这一技术调整对依赖向量搜索的 AI 系统和计算机系统开发者具有重要影响。

**「社区讨论」** 目前没有社区评论可供参考。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2021/11/SPANN_finalversion1.pdf">SPANN: Highly-efﬁcient Billion-scale Approximate Nearest ...</a></li>
<li><a href="https://www.sysdesai.com/news/Mma1ZfxQGY0y">Scaling Pinterest&#x27;s Manas Platform: From HNSW to Quantized ...</a></li>
<li><a href="https://www.infoq.com/news/2026/09/pinterest-search/">From Memory-Hungry HNSW to Quantized SPANN : The... - InfoQ</a></li>

</ul>
</details>

**标签**: `#AI systems`, `#vector search`, `#search technology`, `#computer systems`, `#open source`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [亚马逊 AWS 订单积压达 4960 亿美元，云业务利润率升至 39%](https://finance.yahoo.com/markets/stocks/articles/amazons-aws-backlog-climbed-496-173300632.html) ⭐️ 8.0/10

亚马逊 AWS 的订单积压增至 4960 亿美元，云业务利润率达到 39%，显示市场需求强劲但可能引发市场猜测。

openbb · AAPL · 9月23日 17:33

**「AWS backlog 和利润率背景」** 亚马逊的 AWS 业务在第二季度的剩余履约义务（即已签约但未确认收入的合同）达到 4960 亿美元，同比增长显著。AWS 的运营利润率升至 39%，远高于亚马逊其他业务部门，贡献了公司 60%的运营利润。

**「AWS backlog increase may influence Amazon&\#x27;s stock valuation」** The $496 billion AWS backlog suggests strong future revenue potential, which could affect Amazon&\#x27;s stock valuation by highlighting its cloud computing growth engine with a 39% operating margin.

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.fool.com/investing/2026/09/23/amazons-aws-backlog-climbed-to-496-billion-as-clou/">Amazon&#x27;s AWS Backlog Climbed to $496 Billion as Its Cloud Margin Reached 39%. The Stock Is Primed to Skyrocket as a Result. | The Motley Fool</a></li>
<li><a href="https://www.techtimes.com/articles/322572/20260731/aws-backlog-hits-496b-amazon-raises-ai-spend-220b-capacity-runs-short.htm">AWS Backlog Hits $496B as Amazon Raises AI Spend to $220B and Capacity Runs Short</a></li>
<li><a href="https://financebuzz.com/news/amazons-aws-record-profit-margin">Amazon&#x27;s AWS Business Just Hit a Record Profit Margin | FinanceBuzz</a></li>
<li><a href="https://www.fool.com/investing/2026/08/20/amazons-aws-backlog-just-hit-496-billion-is-the/">Amazon &#x27; s AWS Backlog Just Hit $496 Billion: Is the Stock ...</a></li>
<li><a href="https://www.tipranks.com/stocks/amzn/stock-analysis">Amazon (AMZN) AI Stock Analysis | Smart Price... - TipRanks.com</a></li>

</ul>
</details>

**标签**: `#cloud-computing`, `#aws`, `#stock-performance`, `#financial-metrics`, `#market-speculation`

---