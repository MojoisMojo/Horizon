---
layout: default
title: "Horizon Summary: 2026-10-05 (ZH)"
date: 2026-10-05
lang: zh
---

> 从 67 条内容中筛选出 13 条重要资讯。

---

**科技新闻**
1. [开放团队多智能体强化学习中的周转正交信用分配方法](#item-tech-news-1) ⭐️ 8.0/10
2. [ELMS：通过 LLM 代理实现循环评估的蒙特卡洛树搜索用于蛋白质设计中的模体支架构建](#item-tech-news-2) ⭐️ 8.0/10
3. [FinNextAssist：面向专业金融分析的深度研究助手框架](#item-tech-news-3) ⭐️ 8.0/10
4. [MACTS-EM: 多智能体协作时间序列预测框架](#item-tech-news-4) ⭐️ 8.0/10
5. [MIRROR：LLM 多智能体通信中的多路径共识完整性机制](#item-tech-news-5) ⭐️ 8.0/10
6. [WebUIProof：一种面向 WebUI 代码生成器的执行导向基准测试](#item-tech-news-6) ⭐️ 8.0/10
7. [LLM 代理中的信念形成与复杂传染性群体动态研究](#item-tech-news-7) ⭐️ 8.0/10
8. [月球表面的行踪追踪：识别拜占庭探测车的新方法](#item-tech-news-8) ⭐️ 8.0/10
9. [排列鲁棒性不足：多智能体 Transformer 策略中的动作坍缩问题](#item-tech-news-9) ⭐️ 8.0/10
10. [SceneFactory-3D：提升自动驾驶安全评估的物理基础驾驶模拟器](#item-tech-news-10) ⭐️ 8.0/10
11. [Cloudflare 优化 1.1.1.1 DNS 服务，内存占用减少 100TB](#item-tech-news-11) ⭐️ 8.0/10
12. [将 Stockfish 价值函数蒸馏到 ResNet/ViT 模型，39 亿棋局数据集发布](#item-tech-news-12) ⭐️ 8.0/10
13. [Yandex Music 使用单一 Transformer 替代多个模型](#item-tech-news-13) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [开放团队多智能体强化学习中的周转正交信用分配方法](https://arxiv.org/abs/2610.02847) ⭐️ 8.0/10

该论文提出了 Turnover-Orthogonal Credit Assignment \(TOCA\)，一种用于开放团队多智能体强化学习的信用分配方法，旨在区分行动效果与团队成员变化（周转）效果。TOCA 通过将行动效果、纯周转效果以及行动与周转的交互作用分离，解决了在动态团队环境中标准集中式批评者和共享优势常将这些因素混合的问题。实验表明，在高周转率的动态环境中，TOCA 及其变体 TOCA-β在性能上优于传统的事件感知 MAPPO 风格批评者，特别是在仅涉及替换的 Dynamic Spread 基准测试中表现最佳。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「开放团队多智能体强化学习中的信用分配问题」** 开放团队多智能体强化学习研究的是在合作系统中，智能体可能在单次任务期间加入、离开或被替换的场景。在这种情况下，团队的整体回报变化不仅源于智能体采取的有用动作，还与当前活跃的智能体数量变化有关。传统的集中式批评者和共享优势机制通常将这两种效应合并为一个标量信用信号，导致存活智能体可能因外部的团队变动事件而被错误地奖励或惩罚。

**「TOCA 提高了动态合作团队中鲁棒学习的性能」** TOCA 在动态合作团队中通过明确区分行动效果和周转效果，显著提升了团队回报，特别是在高周转率的替换型 Dynamic Spread 基准测试中，TOCA-β 实现了最佳平均回报。实验表明，移除交互信用会显著损害性能，说明该方法对高方差控制环境中的鲁棒学习具有重要价值。

**「社区讨论」** 目前尚无社区评论可供参考。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://papers.cool/arxiv/2610.02847">Turnover-Orthogonal Credit Assignment for Open-Team Multi ...</a></li>
<li><a href="https://mlinfo.vercel.app/article/arxiv-2610.02847">Turnover-Orthogonal Credit Assignment for Open-Team Multi ...</a></li>
<li><a href="https://arxiv.org/abs/2610.02847">[2610.02847] Turnover - Orthogonal Credit Assignment for...</a></li>

</ul>
</details>

**标签**: `#multi-agent-reinforcement-learning`, `#credit-assignment`, `#open-team-systems`, `#ai-research`, `#machine-learning`

---

<a id="item-tech-news-2"></a>
### [ELMS：通过 LLM 代理实现循环评估的蒙特卡洛树搜索用于蛋白质设计中的模体支架构建](https://arxiv.org/abs/2610.02924) ⭐️ 8.0/10

研究人员提出了一种名为 ELMS 的新框架，该框架通过在循环中整合大型语言模型（LLM）代理和蒙特卡洛树搜索（MCTS）来改进蛋白质设计中的模体支架构建。ELMS 能够有效利用结构反馈，将评估结果转化为具体的修改策略，从而提高设计的成功率。在标准的 GeomMotif 协议下，ELMS 在单模体任务中成功率达到 86.41%，在双模体任务中达到 84.57%，显著优于之前的最佳基线方法。在 MotifBench 数据集上，ELMS 在 100 候选序列的搜索预算下平均解决 26.7/30 个任务（88.89%任务成功率），而最佳基线仅能解决 16.0/30 个任务（53.33%任务成功率）。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「蛋白质设计中的结构反馈利用方法」** 在蛋白质设计中，传统的 motif scaffolding 系统通常采用生成-筛选范式，即独立生成候选蛋白质并使用结构评估进行最终筛选或排序。这种范式未能充分利用评估反馈，因为失败的预测可能包含关于设计是否需要修复 motif 几何结构、全局折叠性或其他结构约束的特定信息。ELMS（Evidence-based LLM-guided Monte Carlo Search）是一种新的框架，通过将评估反馈转化为有针对性的设计行动，改进了这一过程。

**「影响」** ELMS 框架显著提升了蛋白质设计中模体支架构建的成功率，为 AI 驱动的蛋白质工程提供了更高效的迭代设计方法。

**「社区讨论」** 目前尚无社区评论可供参考。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=GrtWwD8pPWY">Framework for conditional diffusion models with applications in motif ...</a></li>
<li><a href="https://arxiv.org/html/2509.15796v2">Monte Carlo Tree Diffusion with Multiple Experts for Protein Design</a></li>
<li><a href="https://github.com/ai4s-research/awesome-ai-for-science">GitHub - ai4s-research/awesome-ai-for-science: A curated list of...</a></li>

</ul>
</details>

**标签**: `#protein design`, `#AI in biology`, `#Monte Carlo methods`, `#LLM integration`, `#machine learning`

---

<a id="item-tech-news-3"></a>
### [FinNextAssist：面向专业金融分析的深度研究助手框架](https://arxiv.org/abs/2610.03174) ⭐️ 8.0/10

FinNextAssist 是一个面向专业金融分析的端到端深度研究框架，整合了异构数据源并引入了专门的子代理以处理复杂任务。该框架将研究过程分解为四个阶段：任务规划者、证据编译器、推理引擎和报告组装器，并提出了两个轻量级子代理：TabAgent 用于跨市场金融表格理解，HeteroAgent 用于跨模态异构金融数据解释。实验表明，FinNextAssist 在 FinDeepResearch、Finance Agent Benchmark 和 FinTMMBench-Web 等基准测试中显著优于现有的强大专有和开源深度研究代理。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「FinNextAssist 的背景」** FinNextAssist 是一个面向专业金融分析的端到端深度研究框架，旨在解决现有深度研究（DR）代理在处理异构金融数据时面临的挑战。该框架基于三个核心要求：整合权威且多样化的金融数据源、使用专门的分析工具和技能，以及为领域特定子任务分配专用子代理。FinNextAssist 将研究过程分解为四个阶段：任务规划者、证据编译器、推理引擎和报告组装器，并引入了两个轻量级子代理：TabAgent 用于跨市场金融表格理解，HeteroAgent 用于跨模态异构金融数据解释。

**「FinNextAssist 在金融分析中的显著性能提升」** FinNextAssist 在 FinDeepResearch、Finance Agent Benchmark 和 FinTMMBench-Web 等多个金融分析基准测试中，显著优于现有的强专有和开源 DR 代理，验证了其在专业金融分析中的有效性。其组件的消融研究也表明，每个子模块在不同市场和语言环境下均对整体性能有重要贡献。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2610.03174">[2610.03174] FinNextAssist: Towards Professional Financial ...</a></li>
<li><a href="https://www.themoonlight.io/de/review/finnextassist-towards-professional-financial-deep-research-assistant">[Papierüberprüfung] FinNextAssist: Towards Professional ...</a></li>
<li><a href="https://www.emergentmind.com/papers/2510.13936">FinDeepResearch : Deep Financial Analysis Agents</a></li>
<li><a href="https://arxiv.org/abs/2610.03174">[2610.03174] FinNextAssist: Towards Professional Financial ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#machine learning`, `#software engineering`, `#financial analysis`, `#research frameworks`

---

<a id="item-tech-news-4"></a>
### [MACTS-EM: 多智能体协作时间序列预测框架](https://arxiv.org/abs/2610.02255) ⭐️ 8.0/10

MACTS-EM 引入了一种多智能体协作框架，用于时间序列预测，结合了专门化智能体、涌现记忆机制和对抗鲁棒性，以应对复杂现象。该框架包括领域专门化预测智能体、元认知层、跨领域模式转移的涌现记忆机制、多模态上下文整合以及对抗鲁棒性组件。在金融、气候、能源和疫情传播等领域的评估显示，MACTS-EM 在大多数场景中优于现有方法，预测准确率提升 8-12%，零样本迁移能力提高 22-27%，在制度转变期间的韧性增强 16-21%，并在分布变化后恢复速度加快 15-18%。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「MACTS-EM 的背景」** MACTS-EM 是一种多智能体协作的时间序列预测框架，旨在解决复杂现象如跨领域知识迁移和多模态数据整合等挑战。该框架结合了专门化的预测智能体、元认知层、涌现记忆机制、多模态上下文整合以及对抗性鲁棒性组件，以提升预测性能。其设计灵感来源于分布式多智能体系统中涌现记忆的特性，通过智能体间的协作与信息共享，实现更准确和适应性强的预测。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://papers.cool/arxiv/2610.02255">MACTS-EM: Multi-Agent Collaborative Time Series Forecasting ...</a></li>
<li><a href="https://arxiv.org/abs/2512.10166">Emergent Collective Memory in Decentralized Multi-Agent AI ... IEEE Xplore Multiagent Systems - arXiv.org Agentic Systems in Time Series - emergentmind.com Predictive deep reinforcement learning with multi-agent ...</a></li>
<li><a href="https://arxiv.org/list/cs.MA/recent">Multiagent Systems - arXiv.org</a></li>

</ul>
</details>

**标签**: `#time\_series\_forecasting`, `#multi\_agent\_systems`, `#machine\_learning`, `#ai\_research`, `#forecasting`

---

<a id="item-tech-news-5"></a>
### [MIRROR：LLM 多智能体通信中的多路径共识完整性机制](https://arxiv.org/abs/2610.02349) ⭐️ 8.0/10

MIRROR 是一种新的通信层完整性机制，旨在解决 LLM 多智能体系统中的 Agent-in-the-Middle（AiTM）攻击问题。该机制通过在 k 条逻辑路径上复制单一规范化的负载，并仅在严格多数路径报告相同摘要时接受消息，从而提高通信安全性。MIRROR 使用无密钥哈希，因此无法独立验证消息的真实性，但依赖于诚实路径占多数的假设。在多个基准测试和实际部署中，MIRROR 在阈值 alpha &lt; 0.5 时将攻击成功率（ASR）降低至 0%，而 LLM-as-a-Judge 则需要更高的计算成本且可能误判良性输出。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「背景信息」** MIRROR 是一种针对大型语言模型多智能体系统（LLM-MAS）的通信层完整性机制，旨在解决 Agent-in-the-Middle（AiTM）攻击问题。这种攻击通过拦截和篡改智能体之间的消息来破坏通信，而不影响智能体本身。现有防御方法依赖语义验证或传输层加密，但存在局限性，例如语义验证可能误判合法输出，而传输层加密在合法中间人终止 TLS 时无法提供保护。

**「MIRROR 显著提升 LLM 多智能体通信安全性」** MIRROR 通过在多路径中验证消息的完整性，将 Agent-in-the-Middle 攻击的成功率降低至 0%，在低于 alpha=0.5 的路由妥协阈值下实现了高安全性。其性能表现优于 LLM-as-a-Judge，仅需 1 倍 LLM token 成本即可达到完全防御效果。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2502.14847">[2502.14847] Red-Teaming LLM Multi-Agent Systems via ... Red-Teaming LLM Multi-Agent Systems via Communication Attacks Agent-in-the-Middle Attack | LLM Security Database Agent-in-the-Middle (AiTM) Attack - emergentmind.com Red-Teaming LLM Multi-Agent Systems via Communication Attacks Red-Teaming LLM Multi-Agent Systems via Communication Attacks Paper-Notes-en/docs/ACL2025/llm_nlp/red-teaming_llm_multi ...</a></li>
<li><a href="https://arxiv.org/abs/2610.02349">MIRROR: Multipath Quorum Integrity for LLM Multi-Agent ...</a></li>
<li><a href="https://agentcommunicationprotocol.dev/">Welcome - Agent Communication Protocol</a></li>
<li><a href="https://appinventiv.com/blog/ai-agent-communication-protocols/">AI Agent Protocols : MCP, A2A, ACP &amp; More Explained</a></li>
<li><a href="https://www.linkedin.com/posts/piyushagarwal9_agenticai-ai-agentprotocols-activity-7366467929850241026-D1d1">How Agent Communication Protocols shape the future of Agentic AI</a></li>

</ul>
</details>

**标签**: `#AI`, `#security`, `#distributed systems`, `#multi-agent systems`, `#communication protocols`

---

<a id="item-tech-news-6"></a>
### [WebUIProof：一种面向 WebUI 代码生成器的执行导向基准测试](https://arxiv.org/abs/2610.02617) ⭐️ 8.0/10

WebUIProof 是一种新的基准测试，通过结构化规范和可执行的交互测试来评估 WebUI 代码生成器，重点关注功能正确性。与以往主要依赖自由提示和静态检查（如构建成功、截图）的基准测试不同，WebUIProof 引入了 UI-agent 执行框架，能够在无头浏览器中运行交互测试，采用迭代的计划-行动-观察循环。研究者评估了八种商业大语言模型（LLMs），发现即使页面渲染成功，交互需求的实现仍存在频繁失败，尤其是在 3D 模拟界面中。此外，WebUIProof 还展示了 UI-agent 框架可以提供结果级别的训练信号，通过从可执行交互测试中提取强化学习奖励，训练更紧凑的模型（如 Qwen2.5 14B 和 MIMO 7B）可提高功能完成度并减少构建失败。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「背景」** WebUI 代码生成器是用于自动生成用户界面代码的工具，广泛应用于现代软件开发中。然而，现有评估方法多依赖静态检查，如构建成功或截图，无法有效验证代码在用户交互中的功能正确性。WebUIProof 的提出旨在填补这一空白，通过引入可执行的交互测试来更全面地评估生成代码的可靠性。

**「影响」** WebUIProof 为 WebUI 代码生成器的评估提供了更准确的方法，有助于开发者识别和修复交互测试中的功能缺陷，特别是在 3D 模拟界面等复杂场景中，显著提升了生成代码的可靠性。

**标签**: `#software engineering`, `#AI systems`, `#benchmarking`, `#web development`, `#interactive systems`

---

<a id="item-tech-news-7"></a>
### [LLM 代理中的信念形成与复杂传染性群体动态研究](https://arxiv.org/abs/2610.02654) ⭐️ 8.0/10

该论文通过实证方法研究了语言模型代理中的信念采纳机制，发现信念采纳概率呈现 S 型曲线，这一特性与复杂传染性相关。采纳阈值受到三个因素的影响：主张的可信度、来源的可靠性以及代理自身的倾向性。研究还指出，在集群网络中信念传播比在随机网络中更显著，系统表现出分叉级联窗口和自持的滞后共识，使得共识更难被移除而非建立。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「社会传染模型的背景」** 社会传染模型通常假设个体如何采纳信念并由此推导群体行为。然而，本文通过实证研究测量语言模型代理中的信念采纳，量化了代理在给定多少同行支持某一主张时采纳该主张的概率。研究发现，这种采纳核函数呈现 S 型曲线，这是复杂传染的典型特征，其阈值受主张的可信度、来源的可靠性以及代理自身的倾向性影响。

**「LLM 代理系统中信念形成与传播的复杂动态影响」** 该研究发现，在 LLM 代理系统中，信念的传播表现出复杂传染特性，共识一旦形成将远比建立更难消除。这种自持的滞后共识现象可能对多智能体系统的稳定性和决策过程产生深远影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.researchgate.net/publication/276851952_Dynamics_of_social_contagions_with_limited_contact_capacity">(PDF) Dynamics of social contagions with limited contact capacity</a></li>
<li><a href="https://www.academia.edu/85286153/Co_diffusion_of_social_contagions">(PDF) Co-diffusion of social contagions</a></li>
<li><a href="https://www.frontiersin.org/journals/physics/articles/10.3389/fphy.2022.1019118/full">Frontiers | Social contagion influenced by active-passive psychology...</a></li>
<li><a href="https://www.emergentmind.com/topics/cross-modal-contagion">Cross-Modal Contagion Mechanisms</a></li>
<li><a href="https://www.aimodels.fyi/papers/arxiv/social-learning-complex-contagion">Social learning with complex contagion | AI Research Paper Details</a></li>
<li><a href="https://mirofish.homes/blog/simple-vs-complex-contagion-in-ai-simulations">Simple vs. Complex Contagion in AI Simulations | MiroFish</a></li>
<li><a href="https://arxiv.org/abs/2610.02654">[2610.02654] Coherence-Driven Belief Formation and Population...</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Social Contagion`, `#LLM Agents`, `#Complex Systems`

---

<a id="item-tech-news-8"></a>
### [月球表面的行踪追踪：识别拜占庭探测车的新方法](https://arxiv.org/abs/2610.02694) ⭐️ 8.0/10

该研究提出了一种针对非合作行星探测车的法医轨迹分析新方法，旨在检测并缓解拜占庭代理（提供错误测量数据的探测车）带来的影响。由于在行星表面任务中，连续的实地可观测性很少见，因此需要通过稀疏的遥测数据（包括里程计、姿态先验和相对探测车检测）来重建探测车轨迹。该方法通过评估候选可信探测车子集的内部和边界相对检测的统计一致性，来识别拜占庭探测车，并仅使用可信代理的测量数据进行轨迹估计。实验结果表明，该方法在合成模拟和真实行星类轨迹数据中，能够显著提高轨迹估计的准确性，优于现有的鲁棒姿态图优化方法。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「行星探测器的轨迹分析与拜占庭故障检测」** 该研究聚焦于行星探测器的轨迹分析，特别是在存在拜占庭故障探测器的情况下。拜占庭故障是指探测器可能故意或错误地提供虚假测量数据，从而影响轨迹的准确性。传统的异常值鲁棒姿态图优化方法在面对这类故障时存在局限，因为拜占庭探测器可以生成内部一致且数量足够的测量数据，使真实数据看起来像是异常值。

**「该方法提升多探测器任务中轨迹估计的准确性」** 该研究提出的方法在合成模拟和真实行星类轨迹数据中显著提高了轨迹估计的准确性，能够有效识别提供错误测量的拜占庭探测器，从而增强多探测器任务中操作安全性和系统可靠性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0304397524005097">A further study on weak Byzantine gathering of mobile agents☆</a></li>
<li><a href="https://www.researchgate.net/publication/316785019_50_years_of_rovers_for_planetary_exploration_A_review_for_future_directions">50 years of rovers for planetary exploration: A review for ...</a></li>
<li><a href="https://journals.sagepub.com/doi/pdf/10.5772/5809">Space Robotics: Part 3: Robotic Rovers for Planetary Exploration</a></li>
<li><a href="https://link.springer.com/article/10.1134/S1054661825700610">Semantic Segmentation in Obstacle Detection for Rover ...</a></li>
<li><a href="https://arxiv.org/pdf/2209.09786">An Outlier Exposure Approach to Improve Visual Anomaly ...</a></li>
<li><a href="https://link.springer.com/article/10.1134/S1054661825700567">Obstacle Detection for Rover Navigation Using Semantic ...</a></li>

</ul>
</details>

**标签**: `#planetary exploration`, `#rover navigation`, `#outlier detection`, `#AI systems`, `#software engineering`

---

<a id="item-tech-news-9"></a>
### [排列鲁棒性不足：多智能体 Transformer 策略中的动作坍缩问题](https://arxiv.org/abs/2610.02848) ⭐️ 8.0/10

该论文探讨了多智能体 Transformer 策略中排列鲁棒性的局限性，并引入了动作坍缩诊断方法以更准确地评估策略行为。研究发现，仅依靠低排列误差可能无法反映策略的真实性能，因为所有智能体可能选择相同动作，导致看似鲁棒的策略实际上缺乏多样性。论文提出应结合排列一致性指标和动作坍缩诊断，包括动作多样性、相同动作比例和最大动作频率，来全面评估多智能体策略。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「多智能体 Transformer 策略的背景」** 多智能体系统中，Transformer 策略因其自注意力机制能够建模智能体间的交互而受到关注。然而，由于多智能体团队本质上是无序的，而 Transformer 通常以有序的 token 序列处理智能体，这种不匹配可能导致策略行为的偏差。研究指出，仅依赖低排列错误可能无法准确反映策略的鲁棒性，因为所有智能体选择相同动作时，策略可能看似稳健，但实际上存在动作坍缩的问题。

**「影响」** 多智能体 Transformer 策略的开发者需要重新考虑评估方法，以确保策略不仅在排列鲁棒性上表现良好，还能维持多样化的行为，避免动作坍缩问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2610.02848">Permutation Robustness Is Not Enough: Action Collapse in...</a></li>
<li><a href="https://arxiv.org/abs/2610.02848">[2610.02848] Permutation Robustness Is Not Enough: Action ...</a></li>

</ul>
</details>

**标签**: `#multi-agent systems`, `#transformer policies`, `#reinforcement learning`, `#AI research`, `#equivariance`

---

<a id="item-tech-news-10"></a>
### [SceneFactory-3D：提升自动驾驶安全评估的物理基础驾驶模拟器](https://arxiv.org/abs/2610.02874) ⭐️ 8.0/10

SceneFactory-3D 是一种新型的物理基础驾驶模拟器，通过引入真实的轮胎-路面相互作用和环境条件，提升自动驾驶系统的安全评估能力。该模拟器利用 GPU 批处理技术，能够在多个平行世界中运行匹配的物理反事实场景，从而更准确地评估道路条件变化对车辆执行和交通传播的影响。研究通过在 21 种摩擦和坡度条件下，对 1,024 个匹配的 12 车辆世界进行实验，发现当摩擦从 1.0 降至 0.18 时，学习策略车辆安全通过工作区的比例下降了 6 到 90 个百分点，而经典规划器则下降了 18 到 19 个百分点。代码已开源，可在 https://github.com/SmallWorldLab/SceneFactory\_3D 获取。

rss · arXiv Multi-Agent Systems · 10月5日 04:00

**「SceneFactory-3D 的背景」** SceneFactory-3D 是一种新型的物理驱动的多智能体驾驶模拟器，旨在通过引入真实的轮胎与路面相互作用以及环境条件，提升自动驾驶系统的安全性评估能力。该模拟器利用 GPU 批处理技术，能够在多个独立的物理世界中并行运行，从而更准确地模拟不同路面条件对车辆行为的影响。

**「SceneFactory-3D 的影响」** SceneFactory-3D 通过引入物理基础的轮胎-路面交互和环境条件，显著提升了自动驾驶系统在复杂路况下的安全评估能力，特别是在低摩擦条件下，车辆安全通过工作区的比例下降了 6 到 90 个百分点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2610.02874">SceneFactory - 3 D : Lifting 2D Traffic Scenes into 3 D Physical ...</a></li>
<li><a href="https://arxiv.org/html/2610.02874">SceneFactory - 3 D : Lifting 2D Traffic Scenes into 3 D Physical ...</a></li>

</ul>
</details>

**标签**: `#autonomous vehicles`, `#physics simulation`, `#AI safety`, `#driving simulators`, `#machine learning`

---

<a id="item-tech-news-11"></a>
### [Cloudflare 优化 1.1.1.1 DNS 服务，内存占用减少 100TB](https://www.infoq.cn/article/XWJ8G6GaFmNL74xpSgjU?utm_source=rss&amp;utm_medium=article) ⭐️ 8.0/10

Cloudflare 将其 1.1.1.1 DNS 服务的内存占用减少了 100TB，展示了其在云基础设施和网络优化方面的技术进步。这一改进有助于提升系统性能和可扩展性，同时降低了运营成本。该优化是通过改进缓存机制和资源管理实现的，具体技术细节未公开，但已知其对服务的稳定性和效率有积极影响。

rss · InfoQ 中国 · 10月5日 10:00

**「背景信息」** 1.1.1.1 是 Cloudflare 提供的一个公共 DNS 服务，以其速度快和隐私保护著称。DNS 缓存是该服务的重要组成部分，用于存储域名解析结果以提高响应速度。随着用户数量的增长，缓存的内存占用成为影响服务性能和成本的关键因素。

**「影响」** 这一优化显著降低了 Cloudflare 的运营成本，并提升了 1.1.1.1 DNS 服务的性能和可扩展性，使更多用户能够受益于高效且安全的域名解析体验。

**标签**: `#cloud computing`, `#network optimization`, `#DNS`, `#infrastructure`, `#performance`

---

<a id="item-tech-news-12"></a>
### [将 Stockfish 价值函数蒸馏到 ResNet/ViT 模型，39 亿棋局数据集发布](https://www.reddit.com/r/MachineLearning/comments/1wxz5qq/distilling_stockfish_on_a_billion_positions_full/) ⭐️ 8.0/10

该项目将 Stockfish 的价值函数蒸馏到一个结合 ResNet 和 ViT 的神经网络模型中，使用了来自 Gigafish 数据集的 10 亿棋局位置。该数据集包含 37 个月的 Lichess 对局，总共有 39 亿个棋局位置，可供研究者使用。作者发现，在保持搜索深度不变的情况下，结合 CNN 和 ViT 的模型在训练初期表现更优，最终取得了更好的效果。

reddit · r/MachineLearning · /u/microscope1024 · 10月5日 04:11

**「项目背景」** 该项目通过使用来自 Lichess 的 37 个月游戏数据，构建了一个包含 39 亿个棋局位置的 Gigafish 数据集，并从中提取了 10 亿个位置用于训练。研究者尝试将 Stockfish 的评估函数蒸馏到一个结合卷积神经网络（CNN）和视觉变换器（ViT）的模型中，以在深度受限搜索中更快地逼近完整的搜索树。CNN 在训练初期表现出更强的几何归纳偏置，而 ViT 在后期训练中提供了更好的性能。

**「该研究对 Stockfish 的评估函数进行蒸馏，可能提升棋类 AI 的效率」** 该项目通过将 Stockfish 的评估函数蒸馏到 ResNet/ViT 模型中，利用 10 亿棋局位置数据，可能为棋类 AI 提供更高效的评估方法。结合 CNN 和 ViT 的优势，该模型在保持搜索深度不变的情况下，有望比 Stockfish 的 NNUE 模型更快地理解棋盘状态。

**「社区讨论」** 目前没有相关的社区评论可供参考。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.lukesalamone.com/posts/distilling-stockfish/">Distilling Stockfish with One Billion Positions :: Luke Salamone&#x27;s Blog</a></li>
<li><a href="https://chessprogramming.org/Stockfish_NNUE">Stockfish NNUE - Chess Programming Wiki</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#neural networks`, `#chess ai`, `#deep learning`, `#dataset`

---

<a id="item-tech-news-13"></a>
### [Yandex Music 使用单一 Transformer 替代多个模型](https://www.reddit.com/r/MachineLearning/comments/1wy4qxm/sona_one_transformer_replaced_our_15_candidate/) ⭐️ 8.0/10

Yandex Music 的 Sona 模型在 A/B 测试中替代了 15 个以上的候选生成器、预排序模型和排序模型，通过历史压缩技术实现了效率提升，同时保持了较高的推荐质量。该模型能够处理最多 8,192 个事件，并采用历史压缩方法将推理成本降低约一半。在最终的 A/B 测试中，Sona 在 7 天内使活跃用户增长 4.53%，总收听时间增长 6.30%，且结果在统计学上显著。

reddit · r/MachineLearning · /u/SettingAccording8986 · 10月5日 10:07

**「推荐系统与 Transformer 模型」** 推荐系统通常依赖多个模型来生成候选项目、预排序和最终排序。Transformer 模型因其强大的序列建模能力被广泛应用于自然语言处理和推荐系统。历史压缩是一种优化技术，通过减少模型需要处理的数据量来降低计算成本。

**「效率与性能提升」** Sona 在 A/B 测试中显著提升了活跃用户和总收听时间，表明其在实际应用中具有较高的效率和性能。然而，其目录覆盖率低于原有系统，需要进一步研究原因。

**标签**: `#recommendation-systems`, `#transformers`, `#machine-learning`, `#ai-research`, `#production-models`

---