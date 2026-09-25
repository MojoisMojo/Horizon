---
layout: default
title: "Horizon Summary: 2026-09-25 (ZH)"
date: 2026-09-25
lang: zh
---

> 从 178 条内容中筛选出 16 条重要资讯。

---

**科技新闻**
1. [Go 引入平台无关的 SIMD 支持](#item-tech-news-1) ⭐️ 8.0/10
2. [John Gruber 谈 Muse：技术突破但存在用户安全风险](#item-tech-news-2) ⭐️ 8.0/10
3. [多智能体辩论在可解释交易中的应用：推理质量、共识与性能分析](#item-tech-news-3) ⭐️ 8.0/10
4. [REAT：一种用于多轮数学教学的反思经验增强辅导框架](#item-tech-news-4) ⭐️ 8.0/10
5. [PAWS：基于政策的代理世界模拟数据集](#item-tech-news-5) ⭐️ 8.0/10
6. [基于渐进技能发现的 LLM 代理访问控制框架：通过角色范围能力交付实现结构化治理](#item-tech-news-6) ⭐️ 8.0/10
7. [Codetta：高容量、无密钥且难以检测的多智能体共谋协议](#item-tech-news-7) ⭐️ 8.0/10
8. [AlphaDiverse: 提升 Alpha 因子挖掘的多样化研究代理框架](#item-tech-news-8) ⭐️ 8.0/10
9. [AI 主持访谈在市场调研与数字孪生校准中的应用研究](#item-tech-news-9) ⭐️ 8.0/10
10. [温度工程：为机器人群体设计战略行为多样性](#item-tech-news-10) ⭐️ 8.0/10
11. [LLM 代理多轮一致性评估：生存分析与失败理由分类](#item-tech-news-11) ⭐️ 8.0/10
12. [配对近似可能选择错误的多机器人计划](#item-tech-news-12) ⭐️ 8.0/10
13. [htmx 4.0 发布：采用 Fetch API 重写并引入 DOM Morphing Swap](#item-tech-news-13) ⭐️ 8.0/10
14. [NeurIPS 被拒后转投 ICLR：你实际采纳了多少审稿意见？](#item-tech-news-14) ⭐️ 8.0/10

**财经新闻**
1. [AMD 股价年涨幅达 189%，正式跻身千亿美元俱乐部](#item-finance-news-1) ⭐️ 8.0/10
2. [高盛上调 AMD 目标价至 720 美元，预计服务器 CPU 市场可增至 2110 亿美元](#item-finance-news-2) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Go 引入平台无关的 SIMD 支持](https://go.dev/blog/simd-experiment) ⭐️ 8.0/10

Go 语言引入了平台无关的 SIMD 支持，为计算密集型任务提供了潜在的性能提升，引发了社区对其实现和应用场景的兴趣。这一特性允许开发者在不依赖特定硬件架构的情况下编写 SIMD 代码，从而提高代码的可移植性和效率。该实验性功能可能对系统编程和人工智能领域产生重要影响，特别是在需要高性能计算的场景中。

hackernews · yurivish · 9月25日 11:47 · [社区讨论](https://news.ycombinator.com/item?id=49843269)

**「Go 1.27 的平台无关 SIMD 支持」** Go 1.27 引入了一个实验性的平台无关 SIMD API，旨在为现代处理器提供统一的 SIMD 操作接口。这一改进基于 Go 1.26 的架构相关 SIMD 支持，后者主要针对 amd64 架构，而 Go 1.27 扩展了该功能以支持 arm64。平台无关的 SIMD API 使得开发者能够更方便地利用不同处理器的 SIMD 能力，而无需针对特定架构编写代码。

**「Go 的平台无关 SIMD 支持对性能优化产生实际影响」** Go 1.27 引入的平台无关 SIMD 支持显著提升了计算密集型任务的性能，例如在加密、数据处理和 AI 领域，其性能可达到非 SIMD 代码的 5 倍以上。该功能通过隐藏不同架构（如 AMD64 的 AVX/AVX2/AVX512、NEON 和 WASM SIMD）之间的向量大小和指令差异，使代码在不同平台上都能运行并模拟不支持的操作。

**「社区反馈」** 社区成员对 Go 的平台无关 SIMD 支持表示积极评价，认为这有助于 Go 作为内存安全的高级系统语言的发展。一些开发者提到，这一特性使得支持像 SVE 和 RVV 这样的非固定向量架构变得更加容易，同时也有用户分享了在实际项目中使用 SIMD 提升性能的体验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://go.dev/blog/simd-experiment">Platform-independent SIMD in Go - The Go Programming Language</a></li>
<li><a href="https://www.phoronix.com/news/Go-SIMD-2026">Go&#x27;s Improving SIMD Support, Platform-Independent SIMD Interface - Phoronix</a></li>
<li><a href="https://daily.dev/posts/platform-independent-simd-in-go-ymat2hnb8">Platform-independent SIMD in Go | daily.dev</a></li>
<li><a href="https://go.dev/blog/simd-experiment">Platform-independent SIMD in Go - The Go Programming Language</a></li>
<li><a href="https://daily.dev/posts/platform-independent-simd-in-go-ymat2hnb8">Platform-independent SIMD in Go | daily.dev</a></li>
<li><a href="https://www.phoronix.com/news/Go-SIMD-2026">Go&#x27;s Improving SIMD Support, Platform-Independent SIMD Interface - Phoronix</a></li>

</ul>
</details>

**标签**: `#Go`, `#SIMD`, `#Performance`, `#AI`, `#Systems`

---

<a id="item-tech-news-2"></a>
### [John Gruber 谈 Muse：技术突破但存在用户安全风险](https://simonwillison.net/2026/Sep/25/john-gruber/) ⭐️ 8.0/10

John Gruber 在文章中引用了他对 Muse 的评价，指出 Muse 作为首个面向消费者的自主代理 AI 系统，在技术上具有突破性，每个用户都获得一个持久的 Linux 虚拟机运行在 Meta 的云上。然而，他也警告消费者可能不了解其潜在风险，特别是当 Muse 在 Mac 上运行时，其强大功能可能带来安全隐患。

rss · Simon Willison · 9月25日 17:22

**「Muse 的技术背景」** Muse 是 Meta 推出的一个自主代理 AI 系统，它为每个用户提供了独立的持久 Linux 虚拟机，使用户能够在云环境中运行 AI 代理。这种架构使得 Muse 在技术上具有独特性，同时因其易用性而受到关注。

**「用户安全意识的不足」** 消费者可能缺乏对 Muse 强大功能及其潜在风险的认识，这可能导致误用或安全问题。

**标签**: `#AI`, `#agentic systems`, `#open source`, `#consumer tech`, `#security`

---

<a id="item-tech-news-3"></a>
### [多智能体辩论在可解释交易中的应用：推理质量、共识与性能分析](https://arxiv.org/abs/2609.29701) ⭐️ 8.0/10

一项研究探讨了多智能体辩论框架在提升金融决策推理质量方面的应用，但发现推理质量的提升与经济结果之间没有显著相关性。该研究通过历史市场模拟中的投资组合分配实验，评估了推理质量的四个维度：逻辑有效性、证据支持、替代方案考虑和因果对齐，并与后续的金融表现进行比较。在 210 次受控运行中，推理质量与夏普比率（r = 0.07, p = 0.29）和总回报（r = 0.03, p = 0.70）均无明显关联。结构化提示使推理质量从约 0.72 提升至 0.84（+17.7%，Cohen&\#x27;s d 约 2.0），但这些提升并未持续转化为更高的回报。研究指出，智能体在辩论过程中可能因趋同而放弃独立观点，导致推理质量的下降。通过 Jensen-Shannon 散度干预保持分歧，可使夏普比率提升+0.14（p = 0.028）和 Sortino 比率提升+0.25（p = 0.026），而强制因果推理的干预则未改善财务表现。研究结果表明，多智能体辩论在保持独立信息信号而非单纯提升推理质量时最有价值。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「多智能体辩论框架在金融分析中的应用背景」** 多智能体辩论框架被用于提升金融决策中的推理质量，通过让专门的智能体提出、批评和修订投资决策来模拟市场环境。该方法在历史市场模拟中评估推理质量的四个维度：逻辑有效性、证据支持、替代方案考虑和因果对齐，并与下游的金融表现进行比较。然而，研究发现推理质量的提升并未带来经济结果的显著改善。

**「多智能体辩论对金融表现的影响有限」** 该研究发现，尽管多智能体辩论框架能提升投资决策的推理质量，但其与经济指标如夏普比率和总回报之间没有显著相关性。通过引入 Jensen-Shannon 散度干预，仅在一定程度上改善了夏普比率和 Sortino 比率，但强制因果推理的干预并未带来财务表现的提升。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2509.17395v1">FinDebate: Multi - Agent Collaborative Intelligence for Financial Analysis</a></li>
<li><a href="https://www.emergentmind.com/topics/multi-agent-debate-with-retrieval-augmented-madra">MADRA: Multi - Agent Debate with Retrieval</a></li>
<li><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6354961">Apex Quant: A Multi - Agent Debate Framework For... :: SSRN</a></li>
<li><a href="https://franknielsen.github.io/M-JS/Slides-GeneralizationJensenShannonDivergence.pdf">On the Jensen … Shannon Symmetrization of Distances Relying on...</a></li>
<li><a href="https://futureagi.com/glossary/jensen-shannon-divergence/">What Is Jensen - Shannon Divergence ? FutureAGI Guide (2026)</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7514974/">On the Jensen – Shannon Symmetrization of Distances Relying on...</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Financial Systems`, `#Explainable AI`, `#Multi-Agent Systems`

---

<a id="item-tech-news-4"></a>
### [REAT：一种用于多轮数学教学的反思经验增强辅导框架](https://arxiv.org/abs/2609.29804) ⭐️ 8.0/10

REAT 是一种新的辅导框架，通过经验蒸馏和实时检索增强大语言模型（LLMs）适应学生需求的能力。该框架结合了从历史对话中提取经验与实时适应性检索，解决了当前基于 LLM 的辅导系统在多轮互动中适应多样学生需求方面的不足。实验表明，该框架在复杂且得分较低的辅导场景中显著优于仅提示和监督微调（SFT）的基线方法。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「REAT 框架的背景」** REAT 是一种新的教学框架，旨在通过经验蒸馏和实时检索增强大型语言模型（LLMs）适应学生需求的能力。该框架结合了从历史对话中提取经验与实时适应性检索，以解决当前 LLM 教学系统在多轮互动中缺乏系统积累和重用教学经验的不足。与传统的提示方法或监督微调（SFT）相比，REAT 在复杂且低分的辅导场景中表现出显著的性能提升。

**「影响」** REAT 框架能够提升辅导系统在多轮数学教学中的适应性和效果，尤其对需要复杂指导的学生具有显著帮助。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2609.29804">REAT: A Reflective Experience-Augmented Tutoring Framework for Multi-turn Mathematical Instruction</a></li>
<li><a href="https://arxiv.org/abs/2609.29804">[2609.29804] REAT: A Reflective Experience-Augmented Tutoring Framework for Multi-turn Mathematical Instruction</a></li>

</ul>
</details>

**标签**: `#AI`, `#machine learning`, `#educational technology`, `#tutoring systems`, `#multi-agent systems`

---

<a id="item-tech-news-5"></a>
### [PAWS：基于政策的代理世界模拟数据集](https://arxiv.org/abs/2609.28547) ⭐️ 8.0/10

PAWS 是一个全新的数据集，用于通过时间对齐和语义细节连接政策干预、新闻和利益相关者行动，从而实现政策驱动的金融模拟。该数据集包含 36 个经过验证的美国金融和经济政策案例、12,727 条与政策相关的新闻记录以及 65,291 条基于来源的利益相关者行动。每个行动都与支持性新闻相关联，并通过多层事件框架表示，涵盖交互模式、金融行动类别和子类型、语义属性以及与外部分类法的条件映射。实体被解析为标准化的组织，行动与每日市场回报背景对齐，以支持政策代理模拟的回放。在 2,522 个分层行动样本上，独立的 AI 和人类评审员在交互模式上达成 89.4% 的初始共识，后续通过仲裁解决分歧。案例研究显示，PAWS 能够恢复 2008 年做空禁令和 2001 年小数点化政策的政策时间线和相关市场模式。回放研究进一步表明，高准确性可能掩盖未能检测到罕见利益相关者行动的问题，指出行动时间点和校准是核心挑战。PAWS 为评估基于历史的金融模拟中的代理影响、政策响应级联和行动结果对齐提供了可审计的基础。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「PAWS 数据集的背景」** PAWS 是一个用于政策驱动的金融和经济模拟的新数据集，它将政策干预、新闻和利益相关者行动与时间序列和语义信息相结合。该数据集包含 36 个经过验证的美国金融和经济政策案例、12,727 条与政策相关的新闻记录以及 65,291 条基于来源的利益相关者行动，旨在支持政策-智能体系统的开发和测试。

**「PAWS 对政策驱动的金融模拟研究具有重要影响」** PAWS 为政策驱动的金融和经济模拟提供了可审计的基础，使研究人员能够评估代理人的影响、政策响应级联效应以及行动与结果的对齐情况，特别是在历史数据背景下。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2609.28547v1">Policy - driven Agentic World Simulation</a></li>
<li><a href="https://crcs.seas.harvard.edu/conservation">Conservation | CRCS | Center for Research on Computation and Society</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Data Science`, `#Policy Simulation`, `#Financial Systems`

---

<a id="item-tech-news-6"></a>
### [基于渐进技能发现的 LLM 代理访问控制框架：通过角色范围能力交付实现结构化治理](https://arxiv.org/abs/2609.28693) ⭐️ 8.0/10

该论文提出了一种名为 skilder 的框架，用于在 LLM 代理中实现基于角色的能力交付，以增强企业环境中的治理和安全性。skilder 通过将能力打包成角色，即技能、工具和指令的集合，以及限制这些能力的边界，来解决 LLM 代理在面对大量企业工具时难以安全扩展的问题。该框架允许代理在任务开始时仅拥有最小的角色目录，通过学习任务所需的角色，从单一 MCP 服务器获取相应的技能、指令和工具。由于工具仅在学习的技能内部传递，同一服务器能够确定性地执行授权层，确保治理边界。实验评估显示，当模型完成发现并发出受治理的调用时，skilder 的模拟授权层有效防止了未经授权的工具调用或参数违规。此外，通过允许代理在任务过程中动态获取跨角色的能力，skilder 在保持问题解决灵活性的同时，提供了系统级别的强制性执行。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「LLM 代理的访问控制与治理挑战」** 在企业环境中，大型语言模型（LLM）代理在面对庞大的工具集时难以安全扩展。提供所有内部工具的访问权限会导致上下文窗口过大、工具选择下降以及严重的治理漏洞，因为系统策略仅通过提示定义，仍属于概率性建议而非强制约束。现有的缓解措施，如多代理领域委托，会分散审计日志并无法保证跨会话的策略合规性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.28693">[2609.28693] Progressive Skill Discovery as Access Control for Tool-Using LLM Agents: Structural Governance through Role-Scoped Capability Delivery</a></li>
<li><a href="https://arxiv.org/html/2609.28693">Progressive Skill Discovery as Access Control for Tool-Using LLM Agents: Structural Governance through Role-Scoped Capability Delivery</a></li>

</ul>
</details>

**标签**: `#LLM agents`, `#access control`, `#AI governance`, `#software engineering`, `#role-based systems`

---

<a id="item-tech-news-7"></a>
### [Codetta：高容量、无密钥且难以检测的多智能体共谋协议](https://arxiv.org/abs/2609.28900) ⭐️ 8.0/10

Codetta 引入了一种高容量、无密钥的隐写协议，用于在基于大语言模型（LLM）的系统中实现难以检测的多智能体共谋，解决了现实部署中的关键安全问题。该协议通过结合共享的公共模型、采样机制和自适应纠错码，能够在不对称设置下实现高容量的隐写通信，同时无需预共享密钥。实验结果显示，Codetta 的容量是现有最佳异步协议的 94 倍，其密钥交换机制在约 80,000 个可见标记下，失败概率最高为 4.1×10⁻³。这些结果表明，独立部署的智能体之间实现有效且难以检测的共谋正变得可行，因此审计必须超越对通信记录的检查。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「背景信息」** Codetta 是一种针对大型语言模型（LLM）多智能体系统的高容量、无密钥且难以检测的隐写协议，旨在解决智能体间隐蔽协作带来的安全问题。传统隐写技术通常依赖于预共享密钥，并且在异构环境中表现不佳，而 Codetta 通过公共模型估计通信信道、保留发送者输出分布的采样机制以及自适应纠错码，实现了在不对称设置下的高效协作。该协议还引入了一种隐写密钥交换机制，使独立部署的智能体能够在不暴露通信记录的情况下建立共享密钥。

**「Codetta 对独立部署代理间隐蔽合谋的影响」** Codetta 的实验结果表明，独立部署的代理之间实现有效不可检测的合谋已成为可能，这意味着审计工作必须超越单纯检查通信记录，转向对代理行为的综合分析。该协议通过去除预共享密钥并提升容量，为现实场景中的多代理系统安全带来了新的挑战。

**「社区讨论」** 目前没有社区评论可供参考。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.28900">[2609.28900] Codetta: High-Capacity, Keyless, and Undetectable Multi ...</a></li>
<li><a href="https://arxiv.org/abs/2609.28900">[2609.28900] Codetta: High-Capacity, Keyless, and Undetectable Multi-Agent Collusion</a></li>
<li><a href="https://arxiv.org/html/2609.28900">Codetta: High-Capacity, Keyless, and Undetectable Multi-Agent Collusion</a></li>

</ul>
</details>

**标签**: `#multi-agent systems`, `#steganography`, `#LLM security`, `#AI systems`, `#collusion detection`

---

<a id="item-tech-news-8"></a>
### [AlphaDiverse: 提升 Alpha 因子挖掘的多样化研究代理框架](https://arxiv.org/abs/2609.29014) ⭐️ 8.0/10

AlphaDiverse 是一个旨在提升 Alpha 因子挖掘的框架，通过整合多代理研究系统、多样化研究路径收集以及后训练技术来优化本地代理。该框架通过生成互补的计划组合并变化研究环境来收集多样化的研究路径，然后使用监督微调对本地 Planner 和 Realizer 代理进行预热。接着，提出联合 GRPO 方法，利用预测质量和贡献多样性对两者进行优化。研究反馈仅限于内部周期数据，而最终冻结模型则在外部周期数据上进行评估，以避免测试集调优。实验表明，AlphaDiverse 能够在四个中国股票宇宙中实现具有竞争力的预测与更广泛的探索。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「AlphaDiverse 框架的背景」** AlphaDiverse 是一个旨在提升 alpha 因子挖掘的框架，通过整合多智能体系统、多样化研究路径收集以及本地代理的后训练技术来解决现有基于大语言模型（LLM）的多智能体系统在成本、可用性和保密性方面的限制。该框架通过在不同研究环境中生成互补的计划组合，收集多样化的研究路径，并利用这些路径对本地 Planner 和 Realizer 代理进行监督微调。此外，它采用联合 GRPO 方法优化这两个代理，以提升预测质量和探索多样性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.29014">[2609.29014] AlphaDiverse: Post-Training Local Quantitative Research Agents for Diverse Exploration in Alpha Factor Mining</a></li>
<li><a href="https://arxiv.org/html/2609.29014">AlphaDiverse: Post-Training LocalQuantitative Research Agents for DiverseExploration in Alpha Factor Mining</a></li>
<li><a href="https://github.com/jjakimoto/research-issues/issues/1754">Latest: AlphaDiverse: Post-Training Local Quantitative Research Agents for Diverse Exploration in Alpha Factor Mining · Issue #1754 · jjakimoto/research-issues</a></li>

</ul>
</details>

**标签**: `#AI research`, `#machine learning`, `#alpha factor mining`, `#multi-agent systems`, `#optimization`

---

<a id="item-tech-news-9"></a>
### [AI 主持访谈在市场调研与数字孪生校准中的应用研究](https://arxiv.org/abs/2609.29143) ⭐️ 8.0/10

一项研究显示，AI 主持的访谈在市场调研和数字孪生校准中能够与人类主持的访谈或静态方法相媲美，甚至在某些方面表现更优。该研究通过与三个行业合作伙伴合作，进行了一项预注册的被试间研究（N = 317），比较了 AI 主持（N = 139）、人类主持（N = 24）和静态访谈（N = 154）的效果。结果显示，AI 主持的访谈在深度、主题覆盖范围以及在预算不变的情况下捕捉更多客户需求方面优于人类主持或静态访谈。然而，参与者在与真人交谈时表现出更高的情绪参与度。研究还发现，由 AI 主持访谈生成的数字孪生在预测消费者对六个实际营销刺激的反应方面优于仅基于人口统计的虚拟人物，但 AI 主持的访谈在定量预测方面并未优于静态访谈。预测误差与数字孪生和人类之间自我报告的思维风格差异以及训练数据和验证数据之间的差距有关。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「AI-moderated interviews 在市场研究和数字孪生校准中的应用背景」** AI-moderated interviews（AI 主持访谈）是一种新兴的市场研究方法，通过人工智能技术动态引导受访者表达其观点，从而获取更深入的消费者洞察。这种方法被用于构建消费者“数字孪生”，即对真实消费者行为和偏好的虚拟模拟。数字孪生在营销中被用来预测消费者对市场刺激的反应，例如品牌感知、产品偏好等，通过模拟消费者行为来优化营销策略和用户体验。

**「AI-moderated interviews 提升市场调研和数字孪生校准效果」** AI-moderated interviews 在市场调研中能够与人类访谈相媲美，甚至在预算不变的情况下捕捉更多客户需求，但人类访谈在情感参与度上更优。此外，AI 生成的数字孪生在预测消费者行为方面优于仅基于人口统计的 personas，但其预测精度仍不及静态访谈方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://getperspective.ai/blog/ai-moderated-interviews-how-they-work-when-to-use-them-and-what-they-replace">AI-Moderated Interviews: How They Work, When to Use Them, and What They Replace | Blog | Perspective AI</a></li>
<li><a href="https://researchworld.com/articles/8-ways-market-researchers-are-using-ai-moderated-interviews-aimis">8 Ways Market Researchers Are Using AI-Moderated Interviews (AIMIs) - Research World</a></li>
<li><a href="https://www.linkedin.com/pulse/digital-twin-marketing-future-customer-experience-zedexinfo-pvt-ltd-ufcqf">Digital Twin Marketing : The Future of Customer Experience</a></li>
<li><a href="https://www.qubitdots.com/blog/digital-twins-marketing-virtual-customers-insights/">Digital Twins in Marketing : How Virtual Customers Drive Real Results</a></li>
<li><a href="https://www.nexthorizon.net/digital-twins-in-marketing-creating-immersive-consumer-experiences/">Digital Twins in Marketing : Creating Immersive... | Next Horizon</a></li>
<li><a href="https://www.linkedin.com/pulse/harnessing-power-ai-digital-twins-lessons-from-singapores-babin-0bi3e">Harnessing the Power of AI and Digital Twins : Lessons from...</a></li>
<li><a href="https://tomchentw.github.io/xrossref/?harnessing-ai-for-predictive-customer-behavior-and-seamless-seo-alignment">Harnessing AI for Predictive Customer Behavior and Seamless SEO...</a></li>
<li><a href="https://insight7.io/identifying-product-pain-points-in-customer-calls-emails-and-interviews-with-ai/">Identifying Product Pain Points in Customer Calls, Emails, and...</a></li>

</ul>
</details>

**标签**: `#AI`, `#market research`, `#digital twins`, `#human-computer interaction`, `#machine learning`

---

<a id="item-tech-news-10"></a>
### [温度工程：为机器人群体设计战略行为多样性](https://arxiv.org/abs/2609.29423) ⭐️ 8.0/10

该论文提出了一种名为‘温度工程’的框架，旨在通过借鉴动物温度特质的概念，设计机器人群体的战略行为多样性。机器人群体通常因校准、电池状态、传感器漂移和磨损等因素而表现出行为分布，而非单一行为。论文将动物行为中的五个进化验证的温度轴（胆怯-大胆、探索-回避、活动性、攻击性和社交性）作为设计词汇，将其转化为连续的控制参数τ∈\[0,1\]，用于模块阈值、多智能体强化学习中的策略条件向量或基础模型规划器的约束。该框架通过三阶段工作流程将任务成功标准映射到相关轴上，规划τ分布的形状，并调整反应规范以指导温度如何响应环境线索。在去中心化系统中，温度分布作为规划器的输出，而在缺乏全局知识的群体中，它必须作为离线、前瞻性的设计输入。行为和平台的异质性因此成为共同设计变量，论文还提出了机器人特有的温度轴（自我模型可塑性、果断性、主动性与表达性）。研究表明，工程化的异质性在诸如聚集和探索等任务中优于同质群体，但确定何时以及多大程度的异质性能带来收益仍是该领域需要进一步研究的问题。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「生物启发的机器人群体行为设计框架」** 该论文提出了一种名为&\#x27;temperament engineering&\#x27;（情绪工程）的生物启发框架，用于设计机器人群体的战略行为多样性。它借鉴了动物情绪特质的五个进化验证轴（胆怯-大胆、探索-回避、活动性、攻击性和社交性），将这些特质转化为连续控制参数τ ∈ \[0,1\]，并将其应用于控制器之上，实现为模块阈值、多智能体强化学习中的策略调节向量或基础模型规划器的约束条件。

**「行为多样性提升机器人群体任务表现」** 该研究指出，通过设计机器人群体的行为多样性，可以在诸如聚集和探索等任务中显著超越同质化群体的表现。这种异质性使机器人能够根据环境线索调整行为，从而提高整体效率和适应性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2609.29423">[2609.29423] Temperament Engineering: Designing Strategic Behavioural ...</a></li>
<li><a href="https://paperreading.club/page?id=447861">Temperament Engineering: Designing Strategic Behavioural Diversity in ...</a></li>
<li><a href="https://www.researchgate.net/publication/376879073_Exploring_the_power_of_heterogeneous_UAV_swarms_through_reinforcement_learning">(PDF) Exploring the power of heterogeneous UAV swarms through...</a></li>
<li><a href="https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2024.1426282/full">Frontiers | Heterogeneous foraging swarms can be better</a></li>
<li><a href="https://www.academia.edu/84228077/Potential_of_Heterogeneity_in_Collective_Behaviors_A_Case_Study_on_Heterogeneous_Swarms">(PDF) Potential of Heterogeneity in Collective Behaviors: A Case...</a></li>

</ul>
</details>

**标签**: `#robotics`, `#multi-agent systems`, `#artificial intelligence`, `#swarm behavior`, `#control systems`

---

<a id="item-tech-news-11"></a>
### [LLM 代理多轮一致性评估：生存分析与失败理由分类](https://arxiv.org/abs/2609.29508) ⭐️ 8.0/10

该论文通过生存分析和失败理由分类方法，评估了大型语言模型（LLM）代理在多轮交互中的表现一致性。研究在一个受控的 20 步多代理环境中进行，模拟延迟满足实验，分析了不同社会可见性、人格压力和决策策略对失败风险的影响。研究共运行了 84,540 条轨迹，涵盖 8 个模型家族，并构建了一个包含 7 个类别的分类体系，基于 13,780 条决策轨迹进行失败理由分析。研究发现，早期失败更多由冲动驱动，而后期失败则更多与疲劳和成本效益分析相关，同时公共环境增加了规范导向的合理性说明。此外，研究还发现更长的决策过程与更高的内在理由矛盾率相关，这挑战了认为更多推理文本意味着更高一致性的假设。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「多轮一致性评估的背景」** 该研究通过生存分析和失败理由分类法，评估大型语言模型（LLM）代理在多轮交互中的时间一致性。研究设计了一个受延迟满足研究启发的 20 步控制实验，分析代理在不同社会可见性（私密 vs 公共）、人格压力和决策策略下的行为。通过 Kaplan-Meier 生存曲线和离散时间风险模型，量化了实验因素如何影响失败风险，并构建了一个基于 13,780 个决策轨迹的七类分类法，用于分析代理终止任务的语言模式和理由。

**「LLM 代理在多轮交互中的不一致性问题凸显」** 该研究揭示了 LLM 代理在多轮交互中可能表现出不一致行为，尤其是在长时间任务中容易出现承诺偏差和矛盾性推理，这可能影响其在实际应用中的可靠性。研究还指出，代理的决策理由会随时间变化，早期失败多由冲动驱动，而后期失败则更多与疲劳和成本效益分析相关。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2609.29508">Evaluation of Multi-Turn Consistency in LLM Agents : Survival ...</a></li>
<li><a href="https://openreview.net/forum?id=lGYJdWYUOf">Delay-of-Gratification as a Multi- Agent Survival ... | OpenReview</a></li>
<li><a href="https://www.tandfonline.com/doi/full/10.1080/17498430.2018.1450055">tandfonline.com/doi/full/10.1080/17498430.2018.1450055</a></li>
<li><a href="https://arxiv.org/html/2609.29508">Evaluation of Multi - Turn Consistency in LLM Agents : Survival...</a></li>

</ul>
</details>

**标签**: `#AI research`, `#machine learning`, `#LLM agents`, `#survival analysis`, `#decision-making`

---

<a id="item-tech-news-12"></a>
### [配对近似可能选择错误的多机器人计划](https://arxiv.org/abs/2609.29929) ⭐️ 8.0/10

该研究揭示了多机器人协调中配对近似方法可能导致计划选择次优的问题，其在覆盖性能上存在可衡量的遗憾。通过冻结多机器人轨迹来评估两种配对近似方法的计划选择遗憾，发现使用精确的二阶 Möbius 截断 $F\_2$ 替代精确覆盖函数 $F$ 时，在两个候选族中的七个地图中有六个地图的计划选择发生了变化，最大遗憾达到 0.337 的覆盖面积。改用等权重最小二乘二阶加性拟合 $G$ 虽然减少了遗憾，但仍会在每个族中的三个地图上改变选择。仅保留单个项的加性得分 $F\_1$ 在一个族中六个地图上选择了正确计划，在另一个族中四个地图上选择了正确计划，相比之下 $F\_2$ 只在一个地图上选择了正确计划。研究还指出，较低的平均重建误差并不保证较低的计划选择遗憾。

rss · arXiv Multi-Agent Systems · 9月25日 04:00

**「多机器人系统中配对近似方法的局限性」** 多机器人协调方法通常通过单个机器人和配对项来评估联合计划，忽略了涉及三个或更多机器人的项。该研究指出，使用配对近似方法进行计划选择可能导致次优结果，并在覆盖性能上产生可衡量的遗憾。

**「多机器人系统中成对近似可能导致计划选择错误」** 该研究指出，使用成对近似方法进行多机器人协调时，可能会导致选择次优的计划，从而在覆盖性能上产生高达 0.337 的可衡量遗憾。这种错误在两个候选家族中的四机器人计划上，特别是在 15 米候选生成范围内，有六分之七的地图会受到影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2609.29929">Pairwise Approximation Can Select the Wrong Multi - Robot Plan</a></li>
<li><a href="https://www.tandfonline.com/doi/full/10.1080/23311886.2019.1653531">tandfonline.com/doi/full/10.1080/23311886.2019.1653531</a></li>
<li><a href="https://www.researchgate.net/publication/336535056_Automated_Planning_for_Robotics">Automated Planning for Robotics</a></li>

</ul>
</details>

**标签**: `#multi-robot systems`, `#planning algorithms`, `#AI research`, `#robotics`, `#software engineering`

---

<a id="item-tech-news-13"></a>
### [htmx 4.0 发布：采用 Fetch API 重写并引入 DOM Morphing Swap](https://www.infoq.cn/article/kJ4EkjPLVTh9iT5yyXkM?utm_source=rss&amp;utm_medium=article) ⭐️ 8.0/10

htmx 4.0 已发布，采用 Fetch API 重写核心功能，引入内置的 DOM Morphing Swap 技术，并明确属性继承规则。这些改进提升了框架的性能、可预测性和一致性，对前端开发和动态网页交互有重要影响。开发者可以利用这些新特性更高效地构建响应式网页应用，同时减少对传统 AJAX 的依赖。

rss · InfoQ 中国 · 9月25日 14:18

**「htmx 的背景」** htmx 是一个用于简化动态网页交互的前端库，通过 HTML 属性实现与后端的通信。Fetch API 是现代浏览器中用于网络请求的原生 API，相较于传统的 XMLHttpRequest，它提供了更简洁、更强大的接口。DOM Morphing Swap 是一种用于动态更新页面内容的技术，能够保留页面状态并替换部分 DOM 元素。

**「对开发者的影响」** htmx 4.0 的发布使开发者能够更高效地构建动态网页，同时减少了对复杂 JavaScript 代码的依赖。由于引入了 Fetch API 和 DOM Morphing Swap，应用的性能和用户体验得到了显著提升。

**标签**: `#htmx`, `#前端开发`, `#Fetch API`, `#DOM Manipulation`, `#Web Framework`

---

<a id="item-tech-news-14"></a>
### [NeurIPS 被拒后转投 ICLR：你实际采纳了多少审稿意见？](https://www.reddit.com/r/MachineLearning/comments/1wpognv/neurips_reject_iclr_how_much_reviewer_feedback/) ⭐️ 8.0/10

一位研究者在 Reddit 上讨论了在 NeurIPS 被拒后转投 ICLR 时，实际采纳了多少审稿意见的问题。他关注的是如何处理审稿人对研究新颖性和重要性的批评，以及在截止日期临近的情况下如何应对压力。他询问了其他研究者是否尝试解决所有审稿意见，或者是否选择性地采纳了部分意见，并特别关注那些被质疑贡献度不足或研究意义不大的论文。

reddit · r/MachineLearning · /u/Practical-Buddy6323 · 9月25日 05:56

**「背景」** NeurIPS 和 ICLR 是人工智能和机器学习领域的重要学术会议，研究者通常在被 NeurIPS 拒稿后会考虑将论文转投其他会议，如 ICLR。审稿意见的采纳是学术出版过程中的关键环节，直接影响论文的修改质量和最终接受可能性。

**「影响」** 被 NeurIPS 拒稿的研究者在转投 ICLR 时，可能面临如何有效回应审稿意见的挑战，尤其是关于研究新颖性和重要性的批评，这可能影响论文的接受率和学术影响力。

**标签**: `#machine\_learning`, `#research`, `#academic\_publishing`, `#neurips`, `#iclr`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [AMD 股价年涨幅达 189%，正式跻身千亿美元俱乐部](https://finance.yahoo.com/markets/stocks/articles/189-date-number-pushed-amd-130027058.html) ⭐️ 8.0/10

AMD 股价年内上涨 189%，使其市值首次突破 1000 亿美元，标志着市场对其增长潜力的信心增强。

openbb · AMD · 9月25日 13:00

**「背景信息」** AMD 近年来在芯片技术领域取得显著进展，推动其股价持续上涨。

**标签**: `#stock\_price`, `#market\_performance`, `#company\_growth`, `#trillion\_dollar\_club`, `#AMD`

---

<a id="item-finance-news-2"></a>
### [高盛上调 AMD 目标价至 720 美元，预计服务器 CPU 市场可增至 2110 亿美元](https://finance.yahoo.com/markets/stocks/articles/bofa-raises-amd-target-720-151401054.html) ⭐️ 8.0/10

高盛将 AMD 的目标价上调至 720 美元，并预测到 2030 年服务器 CPU 市场总可寻址市场将增长至 2110 亿美元。

openbb · AMD · 9月25日 15:14

**「背景信息」** Bank of America 将 AMD 的目标股价上调至 720 美元，并预计到 2030 年服务器 CPU 市场总可寻址市场（TAM）将从之前的约 700 亿美元增至 2110 亿美元。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.investing.com/news/stock-market-news/bofa-raises-amd-target-to-720-sees-server-cpu-tam-tripling-to-211b-by-2030-4917753">investing.com/news/stock-market-news/bofa- raises - amd - target - to - 720 ...</a></li>
<li><a href="https://cryptopanic.com/news/33451359/AMD-Stock-Forecast-BofA-Sees-720-Target-AI-CPU-Market-Jumps-246">AMD Stock Forecast: BofA Sees $ 720 Target , AI CPU Market Jumps...</a></li>
<li><a href="https://www.thestreet.com/investing/stocks/bank-of-america-raises-amd-stock-price-target-for-2026">Bank of America revamps AMD stock price target for 2026 - TheStreet</a></li>

</ul>
</details>

**标签**: `#stock`, `#AMD`, `#target-price`, `#server-cpu`, `#market-growth`

---