---
layout: default
title: "Horizon Summary: 2026-06-24 (ZH)"
date: 2026-06-24
lang: zh
---

> 从 199 条内容中筛选出 34 条重要资讯。

---

1. [ATHENA：LLM 智能体自主设计数值算法](#item-1) ⭐️ 9.0/10
2. [国产 Arm 超算“线光”登顶全球 Top500，成为最快超算](#item-2) ⭐️ 9.0/10
3. [OpenAI 与 Broadcom 推出 Jalapeño：一款光罩尺寸的 AI 推理专用芯片](#item-3) ⭐️ 9.0/10
4. [SK 海力士提交纳斯达克上市申请 拟筹资 290 亿美元投入 AI 内存](#item-4) ⭐️ 9.0/10
5. [Qwen-AgentWorld-35B-A3B：3B 激活参数的 MoE 世界模型](#item-5) ⭐️ 9.0/10
6. [PR 垃圾信息：现代版的早期电子邮件垃圾](#item-6) ⭐️ 8.0/10
7. [约翰·卡马克反思 id Software 早期错误](#item-7) ⭐️ 8.0/10
8. [Nub：通过预加载钩子为 Node.js 提供类 Bun 工具包](#item-8) ⭐️ 8.0/10
9. [LLM 智能体社会中的涌现式关系秩序：从集体情感到权威分层](#item-9) ⭐️ 8.0/10
10. [Maestro Order：模型无关的编排框架](#item-10) ⭐️ 8.0/10
11. [论文提出真正 AI 主体性需内部化结构](#item-11) ⭐️ 8.0/10
12. [Agon：基于提示经济的自主跨学科研究系统](#item-12) ⭐️ 8.0/10
13. [CORE-Bench：面向计算可重复性的 AI 代理基准测试](#item-13) ⭐️ 8.0/10
14. [Debate2Create: 多智能体 LLM 辩论驱动的机器人协同设计](#item-14) ⭐️ 8.0/10
15. [HIL-ResRL：即插即用的真机 RL 微调，1 小时成功率破 95%](#item-15) ⭐️ 8.0/10
16. [华为天才少年一作，港大 MaRS Lab 获 IEEE TRO 最佳论文奖](#item-16) ⭐️ 8.0/10
17. [Claude Code 重大升级，Karpathy 称其为 LLM 第三次变革](#item-17) ⭐️ 8.0/10
18. [高通在 2026 投资者日发布 Dragonfly C1000 CPU 及 AI 加速器](#item-18) ⭐️ 8.0/10
19. [Meta 因员工击键数据泄露暂停 AI 培训](#item-19) ⭐️ 8.0/10
20. [Gefen：可无缝替换 AdamW 并宣称训练内存降低 8 倍](#item-20) ⭐️ 8.0/10
21. [用户通过模型修改将 GLM-5.2 在 GH200 上的推理速度提升 20 倍](#item-21) ⭐️ 8.0/10
22. [开源浏览器扩展在 WebGPU 上本地运行 SDXL](#item-22) ⭐️ 8.0/10
23. [Bunny DNS 免费了：无限查询，最多 500 个域名](#item-23) ⭐️ 7.0/10
24. [谷歌在 Gemini 3.5 Flash 中推出计算机使用功能](#item-24) ⭐️ 7.0/10
25. [NVIDIA 45°C 液冷设计使数据中心用水量接近零](#item-25) ⭐️ 7.0/10
26. [大语言模型生成的求职申请使候选人失去个性](#item-26) ⭐️ 7.0/10
27. [自主飞行器在去中心化 AAM 走廊中实现自组织](#item-27) ⭐️ 7.0/10
28. [动态规划生成一致旅行时间的活动日程](#item-28) ⭐️ 7.0/10
29. [工程可靠自主系统：挑战与解决方案](#item-29) ⭐️ 7.0/10
30. [申通安能真金白银下单，公路货运物理 AI 首闭环](#item-30) ⭐️ 7.0/10
31. [企业 AI Agent 为何止步原型阶段？AWS 强调 Agent 工程是关键](#item-31) ⭐️ 7.0/10
32. [Anthropic 揭示 Claude 如何构建自身执行框架](#item-32) ⭐️ 7.0/10
33. [高通从智能座舱转向物理 AI](#item-33) ⭐️ 6.0/10
34. [Spring 生态系统增量版本更新及 Spring AI 2.0 正式发布](#item-34) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [ATHENA：LLM 智能体自主设计数值算法](https://arxiv.org/abs/2512.03476) ⭐️ 9.0/10

ATHENA 引入了一个智能体框架，利用大语言模型自主设计、验证并迭代优化复杂的科学数值算法，其精度达到甚至超越了专家编写的方案。 通过自动将物理概念转化为可靠代码，ATHENA 消除了计算科学中的一个主要瓶颈，有望加速所有依赖模拟的学科研究。 该框架将科学推理建模为上下文赌博机过程，并利用专家衍生的概念脚手架将高层策略与数值实现解耦，从而能够对病态问题做出有原则的诊断和修复。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**背景**: 智能体 AI 是指 AI 代理可以在既定约束下自主追求目标并采取行动的系统。上下文赌博机是一种机器学习框架，其中代理在每次决策时结合上下文信息从多个选项（臂）中选择，以平衡探索与利用，逐步优化收益。概念脚手架是一种将高层抽象知识结构化以指导底层实现的技术，此处用于连接数学思想与代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agentic_AI">Agentic AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Contextual_bandit_algorithm">Contextual bandit algorithm</a></li>

</ul>
</details>

**标签**: `#Agentic AI`, `#Scientific Computing`, `#LLM`, `#Numerical Algorithms`, `#AI for Science`

---

<a id="item-2"></a>
## [国产 Arm 超算“线光”登顶全球 Top500，成为最快超算](https://www.servethehome.com/arm-cpus-take-number-1-in-latest-top500-list-with-chinese-lineshine/) ⭐️ 9.0/10

中国的线光（LineShine）超算基于 Arm 架构，仅使用 CPU，在 LINPACK 基准测试中达到了 2.198 exaflops，登顶 2026 年 6 月 TOP500 排行榜。 这标志着一个范式转变：仅使用 CPU 的 Arm 系统重新夺回榜首，挑战了 GPU 加速架构的主导地位，凸显了 Arm 在高性能计算中日益增长的作用。 线光部署在深圳国家超级计算中心，不依赖 GPU 加速器，完全依靠 Arm CPU 在 LINPACK 基准测试中取得此性能。

rss · ServeTheHome · 6月24日 03:46

**背景**: TOP500 列表每年发布两次，根据 LINPACK 基准测试对全球最强超算进行排名，该测试通过求解稠密线性方程组来衡量浮点计算能力。Arm 架构传统上在移动设备中占主导地位，因其能效和可扩展性而越来越多地被用于高性能计算。中国此前曾凭借神威·太湖之光等系统占据榜首。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/TOP500_Supercomputer_Sites">TOP500 Supercomputer Sites</a></li>
<li><a href="https://en.wikipedia.org/wiki/LineShine_(supercomputer)">LineShine ( supercomputer ) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/LINPACK_benchmarks">LINPACK benchmarks</a></li>

</ul>
</details>

**标签**: `#supercomputers`, `#Arm architecture`, `#HPC`, `#Top500`, `#China`

---

<a id="item-3"></a>
## [OpenAI 与 Broadcom 推出 Jalapeño：一款光罩尺寸的 AI 推理专用芯片](https://www.tomshardware.com/tech-industry/artificial-intelligence/broadcom-and-openai-unveil-custom-built-jalapeno-inference-processor-openais-first-chip-is-a-massive-reticle-sized-asic-built-in-an-ultra-fast-nine-month-development-cycle) ⭐️ 9.0/10

OpenAI 与 Broadcom 推出了 Jalapeño，这是一款专为大语言模型推理设计的定制化光罩尺寸 ASIC，从设计到生产仅用了 9 个月时间。据报道，其每瓦性能显著优于当前最先进的解决方案。 这是 OpenAI 的首款定制芯片，标志着其向自研芯片的战略转变，以减少对通用 GPU 的依赖并可能降低推理成本。宣称的效率提升可能加速 AI 部署并重塑 AI 硬件竞争格局。 该芯片为光罩尺寸的 ASIC，即采用最大光刻视场尺寸，约为 26 毫米×33 毫米。工程样片在 GPT-5.3-Codex-Spark 上运行，早期测试显示其每瓦性能领先，并且 Broadcom CEO 声称相比典型 AI GPU 可节省约 50%的成本。

rss · Tom's Hardware · 6月24日 18:50

**背景**: ASIC 是一种为特定应用定制的芯片，与通用处理器不同。“光罩尺寸”指的是在单次光刻曝光步骤中可制造的最大芯片尺寸，能在单个晶粒上最大化晶体管数量。Jalapeño 专为大语言模型推理优化，其效率对成本和可扩展性至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip</a></li>
<li><a href="https://www.cnbc.com/2026/06/24/openai-and-broadcom-reveal-jalapeno-first-ai-chip-in-partnership.html">OpenAI and Broadcom reveal Jalapeno, first AI chip in ... - CNBC</a></li>
<li><a href="https://en.wikipedia.org/wiki/Photomask">Photomask - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 部分评论者对 AI 加速芯片设计的说法持怀疑态度，认为这可能是营销噱头。其他评论指出台积电负责制造该芯片，并对将模型权重直接嵌入硅片的激进设计表达了兴趣。一条评论强调了 Broadcom CEO 声称的对比 GPU 节省 50%成本的优势。

**标签**: `#AI`, `#inference`, `#ASIC`, `#OpenAI`, `#Broadcom`

---

<a id="item-4"></a>
## [SK 海力士提交纳斯达克上市申请 拟筹资 290 亿美元投入 AI 内存](https://www.tomshardware.com/tech-industry/sk-hynix-files-to-raise-up-to-29-billion-in-nasdaq-listing) ⭐️ 9.0/10

SK 海力士已提交证券登记声明，计划通过纳斯达克上市发行美国存托凭证（ADR），筹资最高 290 亿美元，这是韩国史上最大规模的融资，资金将用于建设先进 AI 内存工厂和订购 EUV 光刻设备。 此次上市凸显了 AI 驱动的高带宽内存（HBM）需求激增，将使 SK 海力士能够利用 EUV 技术大幅扩大产能，巩固其在 AI 半导体竞赛中相较于竞争对手的地位。 该申请拟通过 ADR 筹集最高 45.45 万亿韩元（约合 290 亿美元），全部资金将用于建设先进 AI 内存工厂和购买 EUV 设备；目前尚未公布发行股数和定价等详情。

rss · Tom's Hardware · 6月24日 12:42

**背景**: 极紫外（EUV）光刻是一种先进芯片制造技术，使用 13.5 纳米波长的光来制作最细微的电路图案，对于生产先进内存和逻辑芯片至关重要。高带宽内存（HBM）是一种 3D 堆叠式 DRAM，与传统内存相比带宽更高、功耗更低，是 AI 和高性能计算的关键组件。SK 海力士是 HBM 的主要供应商，AI 应用的激增引发了对 HBM 的空前需求，进而挤压了通用内存的产能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EUV_lithography">EUV lithography</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory</a></li>

</ul>
</details>

**标签**: `#AI hardware`, `#semiconductors`, `#memory`, `#Nasdaq listing`, `#EUV lithography`

---

<a id="item-5"></a>
## [Qwen-AgentWorld-35B-A3B：3B 激活参数的 MoE 世界模型](https://www.reddit.com/r/LocalLLaMA/comments/1ue5149/qwenagentworld35ba3b_a_3bactive_moe_trained_to/) ⭐️ 9.0/10

Qwen 团队发布了 Qwen-AgentWorld-35B-A3B，这是一个 35B 参数的 MoE 模型，每 token 仅激活 3B 参数，旨在预测智能体在 MCP、终端、软件工程、Android、Web、操作系统、GUI 等七个交互域中执行动作后环境的响应。 它作为语言世界模型，可在不运行真实工具的情况下模拟环境，实现更便宜、更安全的智能体训练、离线评估和合成轨迹生成。 该模型以动作历史和新动作为输入，预测下一个观察状态；每 token 3B 的激活参数使其在高吞吐量模拟时计算高效，并兼容消费级硬件。

reddit · r/LocalLLaMA · /u/nikhilprasanth · 6月24日 05:52

**背景**: MoE（专家混合）模型包含大量专门子网络，但每个 token 只激活一小部分，在总参数量巨大的同时降低推理成本。AI 中的世界模型学习模拟环境，常用于强化学习的规划。MCP（模型上下文协议）是 Anthropic 开发的开放标准，用于连接 AI 应用与外部工具和数据源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://sumguy.com/moe-mixture-of-experts-self-hosters/">Mixture of Experts (MoE) for Self-Hosters... | SumGuy's Ramblings</a></li>
<li><a href="https://openreview.net/forum?id=7orD38wzdi">Ego-centric Learning of Communicative World Models ... | OpenReview</a></li>

</ul>
</details>

**标签**: `#world-models`, `#agent-simulation`, `#mixture-of-experts`, `#reinforcement-learning`, `#qwen`

---

<a id="item-6"></a>
## [PR 垃圾信息：现代版的早期电子邮件垃圾](https://www.greptile.com/blog/prs-on-openclaw) ⭐️ 8.0/10

Hacker News 上的讨论指出了 GitHub 上的 Pull Request 垃圾信息与 2000 年代初电子邮件垃圾危机之间的相似之处，维护者们分享了缓解策略，如要求非文字验证和利用 GitHub 新推出的可配置 PR 限制。 这突显了 AI 生成的垃圾信息在开源社区日益严重的威胁，可能压垮维护者并降低代码质量，凸显了对社区驱动解决方案的需求。 与电子邮件不同，GitHub 上的 PR 垃圾信息无法依赖组织级别的信誉；GitHub 最近增加了可配置的 PR 限制以提供帮助。一些项目要求新贡献者在合并前以非文字形式与维护者会面，还提出了使用代币积分进行捐赠的想法。

hackernews · dakshgupta · 6月24日 14:32 · [社区讨论](https://news.ycombinator.com/item?id=48660579)

**背景**: Pull Request 垃圾信息指的是向 GitHub 上的开源仓库提交的未经请求、通常是自动化或低质量的贡献。这类似于 2000 年代初的电子邮件垃圾危机，当时收件箱被不需要的信息淹没，后来才开发出有效的过滤器。随着 AI 工具使生成看似真实的代码变得更容易，维护者面临着类似的挑战，需要从真正的贡献中过滤掉这些噪音。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/topics/spam-filtering?l=javascript">spam - filtering · GitHub Topics · GitHub</a></li>
<li><a href="https://docs.bswen.com/blog/2026-03-20-ai-tools-review-filter-pull-requests/">How to Use AI Tools to Review and Filter Pull Requests | BSWEN</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出了 PR 垃圾信息与电子邮件垃圾的异同。一些用户指出发送者信誉模型不适用于以个人为中心的 GitHub 平台。其他人分享了缓解策略，比如要求与维护者会面或使用 GitHub 新的 PR 限制功能。少数人提出了新颖的方法，如基于代币的捐赠。

**标签**: `#open-source`, `#spam`, `#pull-requests`, `#maintainers`, `#github`

---

<a id="item-7"></a>
## [约翰·卡马克反思 id Software 早期错误](https://twitter.com/ID_AA_Carmack/status/2069799283369345247) ⭐️ 8.0/10

id Software 联合创始人约翰·卡马克坦诚回顾了早期职业生涯的错误，承认自己曾过度逼迫团队，没有意识到成熟公司需要更多缓冲，这导致在《雷神之锤》开发后团队精疲力竭。 卡马克的反思为传奇游戏开发者提供了珍贵的领导智慧，凸显了技术雄心与团队福祉之间的紧张关系，这对许多科技初创公司都有借鉴意义。 他特别指出，初代《雷神之锤》尽管地位崇高，但由于不可持续的工作节奏，“掏空了 id Software”，但他认为这款游戏付出的代价是值得的。

hackernews · shadowtree · 6月24日 15:56 · [社区讨论](https://news.ycombinator.com/item?id=48661825)

**背景**: id Software 在上世纪 90 年代凭借《毁灭战士》和《雷神之锤》等第一人称射击游戏彻底改变了游戏行业。约翰·卡马克是这些突破性 3D 引擎背后的技术天才。那个时代的“加班”文化常常意味着极端的工作时长，而卡马克现在对此感到后悔。

**社区讨论**: 评论大多赞同卡马克的自我批评，一些用户提到桑迪·彼得森也回忆过类似情况，并讨论《雷神之锤》的影响是否足以证明公司内部压力的合理性。其他人则反思了《毁灭战士 3》后 id 影响力似乎下降的现象。

**标签**: `#game development`, `#software engineering`, `#leadership`, `#tech history`, `#lessons learned`

---

<a id="item-8"></a>
## [Nub：通过预加载钩子为 Node.js 提供类 Bun 工具包](https://github.com/nubjs/nub) ⭐️ 8.0/10

Nub 引入了一个轻量级工具包，通过预加载钩子和 oxc 转译器为标准 Node.js 添加了 TypeScript 转译、ESM 支持和 polyfill，提供了类似 Bun 的开发体验，而无需分叉运行时。 它将 Bun 一站式方法的便利性和速度带到了庞大的 Node.js 生态系统中，可能简化工具链并降低开发者的迁移障碍。 Nub 利用 Node.js 的 --require 预加载钩子注入基于 oxc 的转译器（作为 Node-API 插件）和模块解析钩子，透明地处理 TypeScript、ESM 以及 Worker 和 Temporal 等 polyfill，同时使用 Node 自身的运行时。

hackernews · colinmcd · 6月24日 14:14 · [社区讨论](https://news.ycombinator.com/item?id=48660267)

**背景**: Bun 是一个快速的一体化 JavaScript 运行时，以其内置的 TypeScript 支持、打包器和测试运行器而闻名。Oxc（氧化编译器）是一组用 Rust 编写的高性能 JavaScript 工具，常用于快速转译。Node.js 通过 --require（预加载）钩子和 module.registerHooks API 提供模块自定义功能，使 Nub 这类工具能够在不修改 Node 本身的情况下扩展其能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>
<li><a href="https://github.com/oxc-project/oxc">GitHub - oxc-project/oxc: A collection of high-performance JavaScript tools.</a></li>
<li><a href="https://nodejs.org/api/module.html">Modules: `node:module` API | Node.js v26.3.1 Documentation</a></li>

</ul>
</details>

**社区讨论**: 社区反应积极，赞扬了这个想法以及增强而非替代 Node.js 的方法。有人提到了创建者的可信度（Zod 的 Colin McDonnell）。也存在关于 --require 与 --import 在 ESM 支持方面细微差别的技术询问，但同时也报告了在 monorepo 中成功采用，零问题且性能极快。

**标签**: `#nodejs`, `#javascript`, `#tooling`, `#typescript`, `#runtime`

---

<a id="item-9"></a>
## [LLM 智能体社会中的涌现式关系秩序：从集体情感到权威分层](https://arxiv.org/abs/2606.23764) ⭐️ 8.0/10

一个多智能体框架，其中由情感、道德和信念驱动的 LLM 智能体自发呈现出类似中国乡土社会的差序格局社会模式。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**标签**: `#multi-agent systems`, `#large language models`, `#social simulation`, `#emergent behavior`, `#sociological theory`

---

<a id="item-10"></a>
## [Maestro Order：模型无关的编排框架](https://arxiv.org/abs/2606.23983) ⭐️ 8.0/10

研究人员提出了 Maestro Order，一种模型无关的编排框架，通过分解、集成、验证和递归四种结构原语以及一个成本感知控制器来组合模型，从而提升可靠性。它将任何模型视为黑盒求解器，并动态分配验证和投票以在每单位成本下最大化可靠性，缓解幻觉问题。 该方法通过系统化且成本有效的方式提升可靠性，无需重新训练模型，解决了大语言模型的幻觉关键问题。它可能对各行业的生产级机器学习流程产生重大影响，使不可靠组件也能构成可信赖的 AI 系统。 成本感知控制器基于边际可靠性分配计算资源，在仿真中实现了可靠性的几何级提升（例如，两道验证门从 0.55 提升至 0.98，四道提升至 0.999）。系统具有确定性、可观测性和容错性，但分解可能造成误差累积，验证器也可能被投机攻击。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**背景**: 大语言模型常产生看似自信但错误的输出，即幻觉。编排框架协调多个模型或组件，以更可靠地解决问题。成本感知推理优化计算资源分配，在成本和准确性之间取得平衡。验证系统使用独立模型检查输出，以降低错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2606.23983">Maestro Order: A Model - Agnostic Orchestration Harness</a></li>
<li><a href="https://www.emergentmind.com/topics/weighted-ensembles-of-verifiers">Weighted Ensembles of Verifiers - emergentmind.com</a></li>

</ul>
</details>

**标签**: `#orchestration`, `#reliability`, `#large-language-models`, `#hallucination-mitigation`, `#budget-aware-inference`

---

<a id="item-11"></a>
## [论文提出真正 AI 主体性需内部化结构](https://arxiv.org/abs/2606.23991) ⭐️ 8.0/10

论文认为 AI 系统的真正主体性需要将目标、身份、决策、自我调节和学习结构内部化，而非依赖外部框架，并提出了通用智能体的目标-身份-配置器(GIC)架构。 这一区分直面当前对‘代理式’AI 的炒作和关于机器自主性的生存担忧，为构建更安全、更自主的系统提供了概念基础，并澄清了真正该担忧什么。 它区分了依赖工程化工作流的‘代理式’系统和具备内源能力的‘自主式’系统，并详述了 GIC 架构的组件：层次化目标分解、身份演化、基于世界模型的模拟推理、习得的自我调节和自主式学习。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**背景**: 基于大语言模型的系统被标榜为编程代理、AI 合作科学家等，模糊了自动化与真正主体性的界限。笛卡尔将主体性视为独立思想的哲学以及科幻作品中的自主存在为本文提供了概念背景。论文旨在为系统设计和生存风险评估澄清这一界限。

**标签**: `#AI agents`, `#agency`, `#LLM systems`, `#theory`, `#conceptual analysis`

---

<a id="item-12"></a>
## [Agon：基于提示经济的自主跨学科研究系统](https://arxiv.org/abs/2606.24177) ⭐️ 8.0/10

研究人员推出了 Agon，一个利用大语言模型驱动的提示经济循环进行大规模跨领域自主研究的研究协调系统，无需人工编写实验代码，并将观察到的失败按严重性、可修复性、可见性和能力归因进行分类。 Agon 将研究瓶颈从产生成果转移到验证声明，实现了可扩展的自动化，同时让人类科学家保持决策参与，有潜力加速跨学科的科学发现。 Agon 基于六条设计原则：提示经济、面向未来、最小化提示、跨学科、大规模并行和零代码。在 444 次循环中，它仅使用小的起始主题且无需人工编写实验代码，揭示出的失败模式被分类为系统可见可修复的类型和需要人类判断的类型。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**背景**: 提示经济指高效使用大语言模型提示，在迭代循环中设计和重用提示，以最大化研究产出并最小化计算成本。自主研究协调系统旨在自动化从假说生成到实验和分析的科研流程。Agon 在这些概念基础上通过实现大规模并行和跨领域操作，应对将机器可解决失败与需人类判断的失败区分开来的关键挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2606.24177v1">Agon: An Autonomous Large-Scale Omnidisciplinary Research ...</a></li>
<li><a href="https://www.machinebrief.com/news/when-machines-produce-humans-decide-the-agon-experiment-k67t">When Machines Produce, Humans Decide: The Agon Experiment</a></li>

</ul>
</details>

**标签**: `#AI Research`, `#Large Language Models`, `#Autonomous Science`, `#Research Automation`, `#Prompt Economy`

---

<a id="item-13"></a>
## [CORE-Bench：面向计算可重复性的 AI 代理基准测试](https://arxiv.org/abs/2409.11363) ⭐️ 8.0/10

研究人员推出了 CORE-Bench，这是一个包含 270 个任务、源自 90 篇论文的基准测试，覆盖计算机科学、社会科学和医学领域，旨在评估 AI 代理在计算可重复性上的表现，任务包括纯语言和视觉语言类型。表现最好的代理（基于 GPT-4o）在最难任务上准确率仅 21%，显示仍有巨大提升空间。 计算可重复性——使用提供的代码和数据验证已发表结果——是科学可信度的基石，但常被忽视。该基准为开发能自动执行可重复性检查、提升研究诚信的 AI 代理设立了标准，并最终可能帮助代理开展原创研究。 CORE-Bench 包含三个难度级别、270 个任务，源自 90 篇论文，横跨计算机科学、社会科学和医学。任务类型包括纯语言和视觉语言，并提供了一个快速、可并行的评估系统。测试了基于 AutoGPT 和定制 CORE-Agent 的基线，底层模型为 GPT-4o 或 GPT-4o-mini；最佳组合在最难级别上仅达 21%准确率，视觉语言任务上表现更低。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**背景**: 计算可重复性旨在确保他人能利用提供的代码和数据复现研究结果，这在各学科中日益受到关注。能够处理多步骤任务的 AI 代理（如 AutoGPT）正在兴起，需要基准来衡量其在真实世界挑战上的进展。视觉语言任务要求代理同时理解图像（如图表、图形）和文本，比纯文本理解更复杂。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://lakens.github.io/statistical_inferences/14-computationalreproducibility.html">14 Computational Reproducibility – Improving Your Statistical...</a></li>
<li><a href="https://hal.science/hal-04649287v1/document">Computational Reproducibility</a></li>
<li><a href="https://arxiv.org/abs/2304.00685">[2304.00685] Vision-Language Models for Vision Tasks: A Survey</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#benchmark`, `#computational reproducibility`, `#scientific research`, `#NLP/vision-language tasks`

---

<a id="item-14"></a>
## [Debate2Create: 多智能体 LLM 辩论驱动的机器人协同设计](https://arxiv.org/abs/2510.25850) ⭐️ 8.0/10

Debate2Create 提出了一种多智能体 LLM 框架，通过基于物理的结构化辩论来联合优化机器人形态与奖励函数，在 MuJoCo 运动基准测试中取得了最高分，其中 Ant 任务提升高达 3.2 倍，Swimmer 任务提升近 9 倍。 这表明结构化的 LLM 辩论能够自动化机器人协同设计这一传统上需要大量专家迭代的过程，有望加速开发更强大、更高效的机器人，应用于多种场景。 D2C 采用设计智能体与控制智能体在“正题-反题-合题”循环中辩论，并由 LLM 裁判根据 MuJoCo 模拟提供多目标反馈。迭代辩论相比零样本生成有 18%–35% 的性能提升，且学到的奖励在 5 项任务中有 4 项可迁移到默认形态。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**背景**: 多智能体 LLM 辩论是指多个具有不同视角的语言模型智能体通过讨论来改进解决方案的模式。MuJoCo 是一种广泛应用于机器人学和强化学习研究的物理模拟器。机器人协同设计是指同时优化机器人的物理结构和控制策略，由于二者相互依赖，这是一个复杂的优化问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://notes.muthu.co/2025/12/improving-decisions-through-multi-agent-debate-and-deliberation/">Improving Decisions Through Multi - Agent Debate and Deliberation</a></li>
<li><a href="https://en.wikipedia.org/wiki/MuJoCo">MuJoCo - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2506.00276">[2506.00276] RoboMoRe: LLM-based Robot Co-design via Joint ... Debate2Create: Robot Co-design via Multi-Agent LLM Debate Co-designing hardware and control for robot hands - Science Robot Co-design: Beyond the Monotone Case - IEEE Xplore Social Robot Co-Design Canvases: A Participatory Design ... GitHub - Yuxing-Wang-THU/SurveyBrainBody: Embodied Co-Design ... Efficient co-adaptation of humanoid robot design and ...</a></li>

</ul>
</details>

**标签**: `#LLM`, `#multi-agent`, `#robot-co-design`, `#debate`, `#MuJoCo`

---

<a id="item-15"></a>
## [HIL-ResRL：即插即用的真机 RL 微调，1 小时成功率破 95%](https://www.qbitai.com/2026/06/438166.html) ⭐️ 8.0/10

研究人员开发了 HIL-ResRL，一个模型无关且即插即用的微调适配器，用于视觉-语言-动作（VLA）模型。它采用人在回路的残差强化学习实现真机微调，仅需一小时，成功率就超过 95%。 这一突破大大降低了在真机上部署 VLA 模型的门槛，使得无需大量数据收集或重新训练即可快速适应新任务和环境。它有望加速通用机器人策略在工业和研究中的实际应用。 HIL-ResRL 适配器兼容通用视觉运动策略和 VLA 模型，微调通过在真机操作中的人类纠错完成。在真机交互一小时内成功率超过 95%，展示了卓越的样本效率。

rss · 量子位 · 6月24日 10:38

**背景**: 视觉-语言-动作（VLA）模型整合了视觉感知、语言理解和动作生成，用于机器人任务，但在真机上部署时因领域差距常导致性能下降。传统微调需要大量数据且耗时。强化学习（RL）通过试错进行适配，但真实世界的 RL 因数据收集缓慢和安全问题而充满挑战。HIL-ResRL 通过将人类纠错与残差强化学习相结合，实现了高效的机上学习，解决了这些问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2606.22860v1">HiL-ResRL: A Model-Agnostic Finetuning Adapter via Human-in ...</a></li>
<li><a href="https://www.themoonlight.io/en/review/hil-resrl-a-model-agnostic-finetuning-adapter-via-human-in-the-loop-residual-reinforcement-learning">[Literature Review] HiL-ResRL: A Model-Agnostic Finetuning Adapter ...</a></li>
<li><a href="https://learnopencv.com/vision-language-action-models-lerobot-policy/">Vision Language Action Models ( VLA ) & Policies for Robots</a></li>

</ul>
</details>

**标签**: `#reinforcement learning`, `#robotics`, `#fine-tuning`, `#VLA`, `#human-in-the-loop`

---

<a id="item-16"></a>
## [华为天才少年一作，港大 MaRS Lab 获 IEEE TRO 最佳论文奖](https://www.qbitai.com/2026/06/437833.html) ⭐️ 8.0/10

由华为天才少年担任第一作者的香港大学 MaRS Lab 论文获得了 IEEE TRO 傅京孙纪念最佳论文奖。其开源项目在 GitHub 上已获得 4200 颗星。 获得顶级机器人期刊 IEEE TRO 的最佳论文奖凸显了该研究的技术创新性。GitHub 上 4200 颗星则验证了其实际应用价值和社区认可。 论文第一作者为华为‘天才少年’计划成员，该计划汇聚顶尖青年人才。虽然未提供具体技术细节，但获奖和开源热度暗示其在机器人感知或规划方面做出了贡献。

rss · 量子位 · 6月24日 05:30

**背景**: IEEE Transactions on Robotics (TRO) 是机器人领域最权威的期刊之一。傅京孙纪念最佳论文奖旨在表彰 TRO 上发表的卓越论文。华为‘天才少年’计划以高薪招募全球顶尖青年人才以推动创新。港大 MaRS Lab 专注于机器人与自主系统研究。

**标签**: `#robotics`, `#award`, `#open-source`, `#IEEE TRO`, `#computer-vision`

---

<a id="item-17"></a>
## [Claude Code 重大升级，Karpathy 称其为 LLM 第三次变革](https://www.qbitai.com/2026/06/437734.html) ⭐️ 8.0/10

Anthropic 的 Claude Code 编程智能体迎来重大升级，一家公司报告称其 65%的产品代码由 AI 生成。Andrej Karpathy 称赞这是大语言模型的第三次变革。 这标志着 AI 辅助编码从辅助转向主要代码编写角色的转折点，可能重塑软件开发效率和人类工程师的角色。 升级后的 Claude Code 集成在终端、IDE 和浏览器中，支持自然语言驱动的编码、调试和发布。65%的代码贡献数字来自一家未具名公司，展示了规模化落地的实际效果。

rss · 量子位 · 6月24日 03:56

**背景**: Claude Code 是 Anthropic 推出的 AI 软件开发智能体，能读取代码库、编辑文件并执行命令。前特斯拉 AI 总监 Andrej Karpathy 长期倡导“软件 3.0”，认为大语言模型将成为新的编程范式。“第三次变革”可能指 LLM 从聊天机器人（第一次）到智能体（第二次），再到主要代码生成器（第三次）的演进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1931717705397957349">“钢铁侠战衣”已就位：Andrej Karpathy演讲全解，揭秘“LLM操作系统”与软件3.0新纪元 - 知乎</a></li>

</ul>
</details>

**标签**: `#Claude Code`, `#LLM transformation`, `#AI-assisted coding`, `#Karpathy`, `#software engineering`

---

<a id="item-18"></a>
## [高通在 2026 投资者日发布 Dragonfly C1000 CPU 及 AI 加速器](https://www.servethehome.com/qualcomm-investor-day-2026-data-center-announcements-cpus-ai-accelerators-and-more/) ⭐️ 8.0/10

高通在 2026 投资者日发布了其 Dragonfly C1000 数据中心 CPU、AI 加速器以及一种专有的高带宽计算内存（HBM 的替代方案）。公司还透露 Meta 将在其下一代服务器集群中使用 Dragonfly C1000 处理器，计划于 2026 年下半年投产。 这标志着高通大举进军数据中心市场，挑战英特尔和 AMD 等现有厂商，可能加速 Arm 架构服务器 CPU 的采用。与 Meta 的合作验证了该技术，并可能推动其在 AI 工作负载中的广泛采用。 Dragonfly C1000 采用小芯片设计，针对功耗效率和 AI 代理负载进行了优化。高通的高带宽计算内存旨在提供 HBM 的替代方案，但具体的性能细节尚未披露。

rss · ServeTheHome · 6月24日 19:22

**背景**: 高通是一家以移动处理器闻名的领先半导体公司，但其此前曾尝试以 Centriq ARM 芯片进入数据中心市场。高带宽内存（HBM）是一种广泛用于 AI 加速器的高性能三维堆叠 DRAM；高通的‘高带宽计算’似乎是类似 HBM 的定制内存解决方案。数据中心市场目前由英特尔至强和 AMD EPYC 处理器主导，而针对 AI 优化的硬件需求日益增长。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.yahoo.com/technology/articles/qualcomm-unveils-dragonfly-cpu-signs-202746549.html">Qualcomm unveils Dragonfly CPU, signs Meta as first data center ...</a></li>
<li><a href="https://www.lightreading.com/data-centers/qualcomm-meta-ink-data-center-cpu-deal">Qualcomm, Meta ink data center CPU deal - Light Reading</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>

</ul>
</details>

**标签**: `#hardware`, `#data center`, `#CPUs`, `#AI accelerators`, `#Qualcomm`

---

<a id="item-19"></a>
## [Meta 因员工击键数据泄露暂停 AI 培训](https://www.tomshardware.com/tech-industry/big-tech/meta-pauses-mandatory-ai-training-program-that-tracked-employee-keystrokes-after-internal-data-leak-exposed-sensitive-staff-information-company-wide-employees-express-frustration-over-poor-handling-of-data) ⭐️ 8.0/10

Meta 暂停了一项强制性的 AI 培训项目，该项目监控员工击键和对话，此前发生内部数据泄露，导致敏感信息在全公司范围内暴露。 该事件凸显了员工监控和数据处理不当带来的严重隐私风险，可能削弱信任并引起监管机构对大型科技公司的关注。 该项目追踪了击键、转录文本和绩效指标；泄露导致这些数据被其他员工获取，引发了对 Meta 数据管理做法的不满。

rss · Tom's Hardware · 6月24日 09:30

**背景**: 科技公司常收集员工数据以改进内部系统，但缺乏严格保护措施的强制监控可能适得其反。此事凸显了工作场所生产力追踪与隐私权之间的持续紧张关系，尤其在 AI 训练需要更多数据的情况下。

**标签**: `#Tech Industry`, `#AI Training`, `#Employee Privacy`, `#Data Leak`, `#Meta`

---

<a id="item-20"></a>
## [Gefen：可无缝替换 AdamW 并宣称训练内存降低 8 倍](https://www.reddit.com/r/LocalLLaMA/comments/1uep96s/gefen_is_a_dropin_replacement_for_the_adamw/) ⭐️ 8.0/10

Gefen 是一个新优化器，作为 AdamW 的直接替代品推出，据称可将训练内存使用量降低 8 倍，相关论文和 GitHub 仓库已公开。 这种内存降低能大幅减少训练大型神经网络所需的硬件资源，使尖端模型训练更易获取、更具成本效益，尤其适合 GPU 内存有限的用户。 论文可在 arXiv（2606.13894）查阅，代码托管在 GitHub 的 ndvbd/Gefen 仓库中。作为直接替代品，只需极少的代码改动即可采用。

reddit · r/LocalLLaMA · /u/indicava · 6月24日 20:39

**背景**: AdamW 是深度学习中广泛使用的优化器，它改进了 Adam 算法，将权重衰减与梯度更新解耦。它是许多框架中训练大型模型（如 Transformer）的默认优化器。然而，标准 AdamW 会为每个参数存储动量和二阶矩估计，这些状态约占参数量两倍的内存。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Adam_(optimizer)">Adam (optimizer)</a></li>
<li><a href="https://optimization.cbe.cornell.edu/index.php?title=AdamW">AdamW - Cornell University Computational Optimization Open Textbook - Optimization Wiki</a></li>

</ul>
</details>

**标签**: `#optimizer`, `#deep learning`, `#memory efficiency`, `#AdamW`, `#training`

---

<a id="item-21"></a>
## [用户通过模型修改将 GLM-5.2 在 GH200 上的推理速度提升 20 倍](https://www.reddit.com/r/LocalLLaMA/comments/1uedlas/i_did_some_model_hacks_and_got_glm52_from_about/) ⭐️ 8.0/10

一位用户将 Z.ai 的 GLM-5.2 模型的 AWQ 量化版本与 FP8 多 token 预测头相结合，在双 H100 Grace Hopper 系统上将推理速度从约 2.5 tokens/秒提升至超过 50 tokens/秒。 这展示了对本地大语言模型推理的一次显著且实用的优化，表明通过巧妙结合量化与多 token 预测，可以在高端硬件上实现数量级的速度提升。 通过将“zai/GLM-5.2-FP8”仓库中的 FP8 多 token 预测头嫁接到“CyanKiwi/GLM-5.2-AWQ”的量化权重上，然后修补 vLLM 以适配这些更改，实现了加速。最佳情况下，4 倍并发达到 55 tok/s，单流推理达到 45 tok/s。

reddit · r/LocalLLaMA · /u/Reddactor · 6月24日 13:30

**背景**: 多 token 预测（MTP）通过训练独立的输出头同时预测多个未来 token，提高了样本效率和推理速度。FP8 量化使用 8 位浮点格式减小模型大小和内存带宽，并在 Nvidia Hopper GPU 上获得原生加速。AWQ（激活感知权重量化）是一种基于激活幅度保护重要权重的量化方法。所提到的 GH200 系统将 Nvidia Grace CPU 与 Hopper H100 GPU 以及大容量统一内存相结合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2404.19737">[2404.19737] Better & Faster Large Language Models via Multi-token Prediction</a></li>
<li><a href="https://grokipedia.com/page/FP8_Quantization">FP8 Quantization</a></li>
<li><a href="https://unsloth.ai/docs/models/glm-5.2">Run the new GLM - 5 . 2 model by Z.ai on local hardware!</a></li>

</ul>
</details>

**标签**: `#local-llm`, `#inference-optimization`, `#model-quantization`, `#multi-token-prediction`, `#hardware-hacking`

---

<a id="item-22"></a>
## [开源浏览器扩展在 WebGPU 上本地运行 SDXL](https://www.reddit.com/r/LocalLLaMA/comments/1uemzsb/sdxl_running_locally_in_the_browser_on_webgpu/) ⭐️ 8.0/10

一个新的开源浏览器扩展通过 WebGPU 实现了无外部依赖的 SDXL-Lightning 本地图像生成。无需复杂安装，支持 Chrome 和 Firefox，加载 ONNX 模型后完全离线运行在用户 GPU 上。 这通过消除安装障碍，大幅降低了非技术用户使用高质量 AI 图像生成的门槛。同时展示了 WebGPU 在浏览器中运行繁重 AI 工作负载的能力，可能催生更多本地优先的 AI 工具。 该扩展使用 ONNX 转换的文本编码器、UNet 和 VAE 运行 SDXL-Lightning，支持 fp16 版（约 7GB 存储，需 8GB 显存）和 4 位量化版（约 3.6GB 存储，需 4-5GB 显存）。需要 Chrome/Edge 122+或最新 Firefox，在 M4 MacBook Pro 上每张图耗时 50-60 秒。GPU 进程中同步着色器编译导致加载和生成时界面短暂冻结。

reddit · r/LocalLLaMA · /u/xoqq · 6月24日 19:15

**背景**: Stable Diffusion XL（SDXL）是 2023 年 7 月发布的文本到图像潜在扩散模型，以生成 1024x1024 的高分辨率、更逼真图像而闻名。WebGPU 是现代浏览器 API，通过底层 Vulkan、Metal 或 Direct3D 提供高效 GPU 访问，可直接在浏览器中进行高性能图形和计算。ONNX 是开放神经网络交换格式，允许机器学习模型在不同框架和运行时之间迁移。该扩展将 SDXL 组件转为 ONNX 图并在 WebGPU 上执行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0">stabilityai/stable-diffusion-xl-base-1.0 · Hugging Face</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API">WebGPU API - MDN Web Docs - Mozilla</a></li>
<li><a href="https://onnx.ai/">ONNX | Home</a></li>

</ul>
</details>

**标签**: `#WebGPU`, `#SDXL`, `#browser-extension`, `#local-ai`, `#image-generation`

---

<a id="item-23"></a>
## [Bunny DNS 免费了：无限查询，最多 500 个域名](https://bunny.net/blog/were-making-bunny-dns-free/) ⭐️ 7.0/10

Bunny 已取消所有 DNS 查询费用，现为每个账户提供最多 500 个域名的免费 DNS 托管，无查询限制，且包含智能记录和健康监控等全部功能。 此举使 Bunny 成为一个有竞争力的免费 DNS 提供商，特别是作为 Cloudflare 的欧盟替代方案，回应了对欧洲技术独立和减少依赖美国基础设施的日益增长的需求。 免费套餐支持最多 500 个域名，包含脚本和监控等高级功能，且无按请求计费。但消费上限仅适用于 Bunny CDN，其他产品不支持，引发了对其成本可预测性的担忧。

hackernews · dabinat · 6月24日 08:50 · [社区讨论](https://news.ycombinator.com/item?id=48657030)

**背景**: Bunny 是一家欧洲 CDN 和 DNS 提供商，以其高性能边缘网络和可脚本化的 DNS 记录闻名。其 DNS 服务与 Cloudflare 和 Amazon Route 53 竞争，近期欧美地缘政治紧张加剧了人们对欧洲替代方案的兴趣。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bunny.net/dns/">Bunny DNS | The #1 Scriptable DNS Platform | bunny .net</a></li>
<li><a href="https://euroalternative.eu/bunny-dns">Bunny DNS : European Alternative to Amazon Route 53 and...</a></li>

</ul>
</details>

**社区讨论**: 评论中有人支持欧盟本土的 Cloudflare 替代方案，但也担心爬虫流量导致的意外费用，以及除 CDN 外其他产品缺乏消费上限。有人称赞 Bunny 的自然增长和对可持续发展的专注，而非追逐投资驱动的扩张。

**标签**: `#DNS`, `#CDN`, `#Cloudflare Alternative`, `#EU Tech`, `#Free Service`

---

<a id="item-24"></a>
## [谷歌在 Gemini 3.5 Flash 中推出计算机使用功能](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/) ⭐️ 7.0/10

谷歌已将计算机使用功能作为原生工具集成到 Gemini 3.5 Flash 中，此前该功能仅作为独立模型提供，现在用户可在 Flash 模型内直接执行智能体计算机任务。 该集成将计算机控制能力引入广泛使用的快速模型，有望实现更高效的数字任务自动化。但早期社区反馈对其可靠性和基于截图的交互方式表示怀疑。 Gemini 3.5 Flash 的计算机使用功能通过截图并解读屏幕内容来决定操作，一些开发者认为该方法不如使用无障碍树或直接调用网站 API 可靠。社区反馈还指出护栏限制过严以及多次纠正后任务仍失败的缺陷。

hackernews · swolpers · 6月24日 17:21 · [社区讨论](https://news.ycombinator.com/item?id=48662999)

**背景**: 计算机使用是指 AI 模型能够与计算机界面交互（例如点击按钮、输入文本和导航应用程序）以自动完成任务。Gemini 3.5 Flash 是谷歌推出的一个快速、低成本的大语言模型，针对智能体工作负载进行了优化。该功能基于截图交互范式，即模型观察屏幕图像并输出操作，而非直接访问底层程序结构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/">Introducing computer use in Gemini 3 . 5 Flash</a></li>
<li><a href="https://deepmind.google/models/gemini/flash/">Gemini 3 . 5 Flash — Google DeepMind</a></li>
<li><a href="https://medium.com/@ThinkingLoop/when-one-pixel-breaks-the-agent-f5dfdf573731">When One Pixel Breaks the Agent. Why screenshot -driven... | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区反馈普遍持怀疑态度：用户反映 Gemini 在简单数据提取任务中放弃操作、缺少 MCP 支持并造成挫折感。许多人质疑基于截图的交互方法，认为无障碍树或 API 逆向工程等替代方案更稳健且成本更低。部分用户还批评模型的护栏限制过于严格。

**标签**: `#AI`, `#Gemini`, `#Computer Use`, `#Google`, `#LLM Agents`

---

<a id="item-25"></a>
## [NVIDIA 45°C 液冷设计使数据中心用水量接近零](https://blogs.nvidia.com/blog/liquid-cooling-ai-factories/) ⭐️ 7.0/10

NVIDIA 为其 AI 数据中心推出了新型液冷架构，冷却液温度可高达 45°C，大幅减少用水量，并能将废热用于区域供暖。 这一进展能大幅减少耗电 AI 数据中心的环境影响，通过削减用水量并为附近社区提供免费热源，应对关键的可持续性挑战。 该直接接触式芯片液冷系统使用 45°C 的温冷却液，无需耗能巨大的制冷机。这使得用水量接近零，并使废热可用于区域供暖，但夏季热再利用可能需要额外方案。

hackernews · nitin_flanker · 6月24日 14:10 · [社区讨论](https://news.ycombinator.com/item?id=48660178)

**背景**: 数据中心传统上依赖消耗大量水的空调或蒸发冷却系统。液冷更高效但通常使用冷水，需要制冷机。区域供暖是一种向建筑分配热能的集中系统；利用数据中心废热可减少对化石燃料的依赖。NASA 的 Ames 中心此前为超级计算机展示了高温水冷却。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/District_heating">District heating</a></li>
<li><a href="https://www.guru3d.com/story/nvidia-unveils-liquid-cooling-design-for-ai-data-centers/">NVIDIA Unveils 45 ° C Liquid Cooling Design for AI Data Centers</a></li>

</ul>
</details>

**社区讨论**: 社区评论对创新性有所质疑，指出液冷和温水冷却已有先例。但对区域供暖的协同效应充满热情，这可能惠及当地社区。也有人质疑数据中心为何要耗水，强调蒸发方法的浪费。

**标签**: `#data centers`, `#cooling`, `#energy efficiency`, `#liquid cooling`, `#sustainability`

---

<a id="item-26"></a>
## [大语言模型生成的求职申请使候选人失去个性](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 7.0/10

Tom MacWright 指出，近几个月来，求职申请、作品集网站和 GitHub 项目越来越普遍地由大语言模型（LLM）协助或完全生成。 这一趋势可能损害招聘，使雇主无法评估真实的技能和个性，掩盖对团队适配和信任至关重要的真实人类特质。 MacWright 强调，就连 GitHub 提交消息也是 LLM 生成的，没有留下候选人实际想法或沟通风格的任何痕迹。

rss · Simon Willison · 6月24日 18:13

**背景**: 像 GPT-4 这样的大语言模型能够生成类似人类的文本和代码，求职者越来越多地使用它们来制作精美的申请材料。Tom MacWright 是一位软件开发者兼博主，以对网络技术和开源领域的见解而闻名。这一观察凸显了人工智能生成内容在职业场景下损害真实性的担忧。

**标签**: `#careers`, `#ai`, `#hiring`, `#llm`, `#authenticity`

---

<a id="item-27"></a>
## [自主飞行器在去中心化 AAM 走廊中实现自组织](https://arxiv.org/abs/2606.23832) ⭐️ 7.0/10

与以往观点相反，本文证明自主固定翼飞行器仅通过局部信息就能学会自组织，在没有集中式交通管理的情况下高效穿越 AAM 走廊。 这挑战了 AAM 走廊运营必须依赖集中控制才高效的观点，有望为城市空中交通和无人机物流系统带来更简单、更可扩展的空域管理方案。 在去中心化环境下，飞行器在 94%以上的时间内保持在走廊边界内，在低、中交通密度时只需很少的战术干预来保持间隔，但在高密度时干预频率增加。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**背景**: 先进空中交通（AAM）设想利用电动垂直起降飞行器（eVTOL）和小型自主无人机在城市与区域间运送乘客和货物。走廊即空中预定义航道，类似于天空中的高速公路，用于安全组织高密度交通。传统空中交通管理依赖集中控制，但去中心化方案可降低基础设施成本并提升系统韧性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.23832">Decentralized Coordination of Autonomous Traffic Through ...</a></li>
<li><a href="https://www.nasa.gov/mission/advanced-air-mobility/">Advanced Air Mobility - NASA</a></li>

</ul>
</details>

**标签**: `#Advanced Air Mobility`, `#decentralized coordination`, `#autonomous traffic`, `#air corridors`, `#self-organization`

---

<a id="item-28"></a>
## [动态规划生成一致旅行时间的活动日程](https://arxiv.org/abs/2606.24566) ⭐️ 7.0/10

本文提出一种基于动态规划的框架，通过迭代分配活动地点和模拟旅行时间，在哑数据实验中相比初迭将旅行时间差异减少了 52.2%。 真实的个人活动日程对流行病学、城市规划和政策设计中的智能体模拟至关重要。该框架通过更好地匹配调查数据，提升了日程的真实性，有望提高相关模型的准确性。 该方法采用动态规划迭代优化活动地点分配，目前仅在哑数据上验证。在实际数据集上的进一步测试仍是确认其实用性的必要条件。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**背景**: 基于活动的移动性建模通过生成个人日常日程来预测出行行为和评估规划方案。旅行调查提供活动序列和旅行时间数据，但由于人类移动的复杂性，生成与调查一致的合成日程一直是个难题。动态规划是一种通过分解子问题求解复杂优化问题的方法，本文将其用于迭代分配活动地点，使模拟旅行时间与调查数据对齐。该方法依赖公开的人口和调查数据来生成日程，同时规避了真实轨迹数据的隐私限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2606.24566">Generating Realistic Individual Activity Schedules via Activity ...</a></li>

</ul>
</details>

**标签**: `#mobility modeling`, `#activity scheduling`, `#dynamic programming`, `#agent-based simulation`, `#urban planning`

---

<a id="item-29"></a>
## [工程可靠自主系统：挑战与解决方案](https://arxiv.org/abs/2606.23760) ⭐️ 7.0/10

ERAS 研讨会报告基于 2024 年 6 月举行的洛伦兹中心研讨会讨论，提出了自主系统在验证、确认和软件架构方面的挑战目录与解决路线图。 该报告很重要，因为它整合了跨学科的见解，并提供了一条战略路线图，以加速形式化方法和可靠工程实践在自主系统中的采用，对学术界和工业界均有影响。 研讨会聚焦三个领域：验证与确认技术、真实世界系统工程以及安全软件架构。报告指出，一些学术技术已能解决部分挑战，但在实践中未被充分使用，而其他挑战仍待解决。

rss · arXiv Multi-Agent Systems · 6月24日 04:00

**背景**: 形式化方法是用于规约、验证和分析系统的数学严谨技术，有助于提高可靠性。FMAS 研讨会系列专注于自主系统的形式化验证，而 AREA 汇聚了智能体与机器人社区，共同应对验证与确认挑战。这些社区联合在洛伦兹中心组织了 ERAS 研讨会。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Formal_methods">Formal methods</a></li>
<li><a href="https://fmasworkshop.github.io/">International Workshop on Formal Methods for Autonomous Systems</a></li>
<li><a href="https://areaworkshop.github.io/AREA2024/">AREA 2024</a></li>

</ul>
</details>

**标签**: `#autonomous systems`, `#formal methods`, `#verification`, `#reliability`, `#workshop`

---

<a id="item-30"></a>
## [申通安能真金白银下单，公路货运物理 AI 首闭环](https://www.qbitai.com/2026/06/437853.html) ⭐️ 7.0/10

中国物流公司申通安能用真金白银下单了公路货运的物理 AI 服务，标志着这个万亿美元市场中首个验证的商业闭环交易。 这表明公路货运中的物理 AI 正从试点走向实际营收，加速行业采用并验证了自主物流的商业可行性。 文章未披露订单的具体性质或技术供应商，但暗示这是一套将数字 AI 与物理卡车操作相结合的端到端自主货运服务。

rss · 量子位 · 6月24日 06:06

**背景**: 物理 AI 指直接控制物理机械的 AI 系统，弥合软件建议与现实行动之间的鸿沟。在公路货运中，它涉及无需人工干预即可导航、装卸货物的自动驾驶卡车。该市场估值万亿美元，全球企业竞相实现可靠安全的自主运营。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/physical-ai-here-europe-might-actually-win-time-hage-guralnik-7uc8e">Physical AI Is Here - And Europe Might Actually Win This Time</a></li>
<li><a href="https://logisticsviewpoints.com/2026/04/14/autonomous-trucking-is-fragmenting-into-distinct-market-entry-models/">Autonomous Trucking Is Fragmenting Into Distinct Market Entry Models - Logistics Viewpoints</a></li>

</ul>
</details>

**标签**: `#physical AI`, `#autonomous freight`, `#logistics`, `#commercialization`, `#road freight`

---

<a id="item-31"></a>
## [企业 AI Agent 为何止步原型阶段？AWS 强调 Agent 工程是关键](https://www.infoq.cn/article/zod9SeNbe75T8YtrIcEC?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

亚马逊云科技储瑞松指出，大量企业 AI Agent 止步于原型阶段，并强调 Agent 工程是关键缺失环节。 这揭示了企业 AI 采纳的主要瓶颈：缺乏扎实的 Agent 工程，再好的原型也无法创造真实商业价值，浪费资源并延缓创新。 Agent 工程包括设计 ReAct、Plan-and-Execute 等稳健模式，优化多 Agent 协作，并理解流程驱动（如 Dify、Coze）与 AI 原生 Agent 方法的区别。

rss · InfoQ 中国 · 6月24日 17:22

**背景**: AI Agent 是基于大语言模型的自主系统，能够感知、推理和行动。原型演示可能成功，但生产环境需应对真实复杂性：可靠性、工具集成、错误恢复及多步规划。Agent 工程是构建可扩展、生产就绪型 Agent 系统的学科。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.zhihu.com/question/1936375725931361485">怎么成为一个 ai agent 工程师？ - 知乎</a></li>
<li><a href="https://github.com/datawhalechina/hello-agents">GitHub - datawhalechina/hello-agents: 《从零开始构建智能体》——从...</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Enterprise AI`, `#Prototype Failure`, `#Agent Engineering`, `#Cloud Architecture`

---

<a id="item-32"></a>
## [Anthropic 揭示 Claude 如何构建自身执行框架](https://www.infoq.cn/article/DYIUw7abCW7ZYI1OER9i?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

Anthropic 近日发布技术解读，阐述了其 AI 模型 Claude 如何自主构建执行框架，从而实现复杂任务的动态规划与自主执行。 这一能力标志着 AI 智能体向自主设计并执行工作流迈出了重要一步，有望提升企业及研究场景中的效率，减少人工干预。 虽未公开完整技术细节，但相关解读可能涉及 Claude 如何利用思维链推理、工具调用协议和动态代码生成等技术，实时适应新任务。

rss · InfoQ 中国 · 6月24日 16:16

**背景**: 在 AI 系统中，执行框架指管理任务执行方式的软件层，包括工具编排、代码执行和资源分配。Claude 等现代大语言模型已具备使用外部工具和 API 的能力，但通常需要预定义执行流程。AI 自建执行框架则让模型能够自主设计并实现其操作流程，常通过递归自我改进或自动规划实现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/institute/recursive-self-improvement">When AI builds itself - Anthropic</a></li>
<li><a href="https://butschster.medium.com/building-self-evolving-ai-systems-exploring-the-architecture-a63912fd72c4">Building self-evolving AI systems: exploring the architecture</a></li>

</ul>
</details>

**标签**: `#Anthropic`, `#Claude`, `#AI Execution Framework`, `#Self-building Systems`, `#Machine Learning`

---

<a id="item-33"></a>
## [高通从智能座舱转向物理 AI](https://www.qbitai.com/2026/06/432494.html) ⭐️ 6.0/10

据报道，高通正在从主导智能座舱芯片市场转向追求广泛的物理 AI，重点放在无处不在的低功耗计算上，而非追求最高性能。 这一转变可能显著影响边缘 AI 和物联网领域，使高通能够将 AI 嵌入无数日常设备，并可能重塑芯片行业的竞争格局。 该战略强调低功耗、始终在线的设备端 AI 推理，但报道未披露具体产品或技术规格。

rss · 量子位 · 6月24日 00:26

**背景**: 高通长期以来是汽车芯片领域的领导者，尤其在车载信息娱乐和智能座舱解决方案方面。物理 AI 是指与现实世界交互的 AI 系统，使自主机器能够感知并执行复杂动作。这一举措与边缘 AI 趋势一致，即在设备端而非云端处理数据，以减少延迟并增强隐私。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/glossary/generative-physical-ai/">What is Physical AI? | NVIDIA Glossary</a></li>
<li><a href="https://grokipedia.com/page/Physical_AI">Physical AI</a></li>

</ul>
</details>

**标签**: `#Qualcomm`, `#physical AI`, `#smart cockpit`, `#chip strategy`, `#edge computing`

---

<a id="item-34"></a>
## [Spring 生态系统增量版本更新及 Spring AI 2.0 正式发布](https://www.infoq.cn/article/Jpi5XBmoO8smLYSyaD9t?utm_source=rss&utm_medium=article) ⭐️ 6.0/10

Spring 生态系统发布了 Spring Boot、Spring Security、Spring Integration 和 Spring Modulith 的增量版本，同时 Spring AI 2.0 已正式发布。 Spring AI 2.0 的正式发布是将 AI 功能整合到 Spring 生态系统中的一个里程碑，使开发者能够使用熟悉的模式构建 AI 驱动的应用；增量更新则确保了广泛使用的项目的持续稳定和改进。 新闻未提供具体版本号或特性细节，仅指出这些增量发布和 Spring AI 2.0；但网络资料显示 Spring AI 提供了适合 Spring 的 AI 工程 API，Spring Modulith 有助于构建模块化单体应用。

rss · InfoQ 中国 · 6月24日 11:11

**背景**: Spring Boot 是广泛使用的独立应用开发框架；Spring Security 处理认证和授权；Spring Integration 支持企业集成模式；Spring Modulith 帮助构建模块化单体应用；Spring AI 是将 AI 集成引入 Spring 的新框架。这些项目构成了 Spring 生态系统的基础工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://spring.io/projects/spring-modulith/">Spring Modulith</a></li>
<li><a href="https://docs.spring.io/spring-modulith/reference/index.html">Spring Modulith</a></li>
<li><a href="https://spring.io/projects/spring-ai/">Spring AI</a></li>

</ul>
</details>

**标签**: `#Spring`, `#Java`, `#Release`, `#AI`, `#Framework`

---