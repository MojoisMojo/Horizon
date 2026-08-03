---
layout: default
title: "Horizon Summary: 2026-08-03 (ZH)"
date: 2026-08-03
lang: zh
---

> 从 99 条内容中筛选出 6 条重要资讯。

---

1. [Karpathy 的鹈鹕引发 AI 基准争论](#item-1) ⭐️ 8.0/10
2. [SwiftUI 七年后的回顾](#item-2) ⭐️ 8.0/10
3. [疑似伊朗网络攻击波及美国供水设施](#item-3) ⭐️ 8.0/10
4. [Dasharo 将开源固件带到 AM5](#item-4) ⭐️ 8.0/10
5. [CausalVLBench 评测视觉因果推理](#item-5) ⭐️ 8.0/10
6. [大型科技公司的两万亿美元 AI 重置](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Karpathy 的鹈鹕引发 AI 基准争论](https://twitter.com/karpathy/status/2083749667410727319) ⭐️ 8.0/10

Hacker News 上正在讨论 Karpathy 的鹈鹕演示，它展示的是一个不完美的生成式 3D 输出，而不是一个打磨完成的最终作品。讨论的重点是，这类演示是否可以作为衡量模型对物理世界理解程度的有意义基准。 这场讨论反映出 AI 评估的一个更大转变：不再只看视觉效果是否精致，而是看模型生成的内容是否符合真实世界的结构和物理规律。这对开发生成模型、3D 工具和代码生成系统的人都很重要，因为它指向了一类新的能力评测方式。 几位评论者指出，这个演示并未附带提示词，因此很难复现。也有人认为，这个结果主要说明模型擅长生成 three.js 代码，而不能直接证明它具备更广泛的世界模型理解能力。

hackernews · delichon · 8月2日 04:05 · [社区讨论](https://news.ycombinator.com/item?id=49140998)

**背景**: 生成式 3D 演示通常处在提示词、代码生成和渲染的交叉点上，因此最终画面既可能反映模型能力，也可能反映搭建方式的质量。在 AI 评估中，基准测试是一种用于标准化比较系统的方法，评论者正在讨论：一个不完美但能暴露物理规律理解程度的演示，是否比更好看的纯图像输出更适合作为基准。这个话题也与如何衡量生成模型的物理推理能力有关。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://physics-iq.github.io/">Physics-IQ Benchmark: Do generative video models understand physical principles?</a></li>
<li><a href="https://news.ycombinator.com/item?id=48947717">Kimi K3, and what we can still learn from the pelican benchmark | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 整体情绪是热烈但分歧明显：有人认为成品看起来糟并不是缺点，恰恰说明它能暴露模型更深层的局限；也有人更关注可复现性和提示词是否公开。还有较为怀疑的观点认为，这个演示可能主要体现的是针对 three.js 的定向训练，而不是通用推理能力的重大突破。

**标签**: `#AI evaluation`, `#generative models`, `#3D graphics`, `#LLM code generation`, `#Hacker News`

---

<a id="item-2"></a>
## [SwiftUI 七年后的回顾](https://ykvm.com/2026/07/swiftui-a-story-of-mediocrity/) ⭐️ 8.0/10

一场 Hacker News 讨论在 SwiftUI 诞生七年后重新审视它，并质疑它是否兑现了作为苹果现代原生 UI 框架的承诺。讨论的焦点是它的声明式模型、生产可用性，以及它能否取代 UIKit 和 AppKit 等旧的苹果 UI 技术栈。 SwiftUI 代表了苹果在 iOS 和 macOS 界面开发上的主要方向，因此它的成熟度会影响团队如何设计应用架构以及制定长期平台策略。这个讨论之所以重要，是因为它反映了整个行业更广泛的问题：声明式 UI 框架是否真的更适合通用原生应用。 评论强调了一种常见的混合做法：开发者会用 SwiftUI 搭建大部分界面，但在需要它处理不好的能力时，仍会下沉到 UIKit、Metal 或 Core Animation。苹果文档将 SwiftUI 描述为声明式框架，内置状态管理和数据流机制，会在底层数据变化时自动更新视图。

hackernews · mpweiher · 8月2日 18:59 · [社区讨论](https://news.ycombinator.com/item?id=49147263)

**背景**: SwiftUI 是苹果用于用代码声明应用界面的框架，而不是像传统方式那样手动编排每一次界面更新。在声明式框架中，开发者描述界面应该长什么样，以及它如何依赖数据，框架再负责计算如何刷新屏幕。UIKit 和 AppKit 是更早的苹果 UI 框架，通常被视为 SwiftUI 试图替代或补充的命令式基线。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.apple.com/documentation/swiftui">SwiftUI | Apple Developer Documentation</a></li>
<li><a href="https://developer.apple.com/documentation/swiftui/managing-user-interface-state">Managing user interface state | Apple Developer Documentation</a></li>
<li><a href="https://en.wikipedia.org/wiki/SwiftUI">SwiftUI - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 这场讨论整体上偏怀疑，但观点并不完全一致；一些评论者认为 SwiftUI 仍然显得不完整，或者不如苹果更早的框架。也有人认为，只要把它作为分层技术栈的一部分务实使用，它就已经可以用于生产；而批评者则质疑，纯声明式、响应式 UI 是否真的适合作为通用原生应用的基础模型。

**标签**: `#SwiftUI`, `#iOS development`, `#UI frameworks`, `#declarative programming`, `#software architecture`

---

<a id="item-3"></a>
## [疑似伊朗网络攻击波及美国供水设施](https://www.tomshardware.com/tech-industry/cyber-security/iran-suspected-of-conducting-cyberattacks-on-us-water-suppliers-in-45-municipalities-small-towns-mostly-targeted-with-utilities-switching-to-manual-control) ⭐️ 8.0/10

美国 45 个市镇的供水设施据称遭到疑似与伊朗有关的网络攻击。虽然系统仍在运行，但一些公用事业单位已切换到手动控制，以降低对供水安全的风险。 供水系统属于关键基础设施，即使是有限的入侵也可能迫使运营方放弃自动化并增加运行风险。此事也表明，国家级威胁不仅会影响大城市或大型公用事业单位，小型市镇同样可能成为目标。 受影响的系统很可能是用于管理水处理和供水分配的 ICS/SCADA 环境，因此切换到手动控制是常见的遏制措施。报道并未称供水已中断，只是表示在遭受网络攻击后，运营方采取了预防性措施。

rss · Tom's Hardware · 8月2日 13:10

**背景**: ICS 和 SCADA 系统是用于自动化工业过程的控制技术，常见于水处理厂等设施。 在供水行业中，这些系统负责监测和控制水泵、阀门、化学投加以及其他维持供水安全与稳定的操作。 当运营方切换到手动控制时，更多依赖人工巡检和本地流程，而不是远程自动化。 国家级攻击者通常被视为关键基础设施的持续威胁，因此供水设施一直是高度受关注的目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.fortinet.com/resources/cyberglossary/ics-scada">ICS SCADA: Strengthening OT Security | Fortinet</a></li>
<li><a href="https://www.cisa.gov/topics/cyber-threats-and-advisories/nation-state-cyber-actors">Nation-State Threats | Cybersecurity and Infrastructure ...</a></li>
<li><a href="https://blog.isa.org/best-practices-water-wastewater-process-control-systems-cybersecurity-security">What Is a Good Security Approach to Water and Wastewater Process Control Systems?</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#critical infrastructure`, `#water utilities`, `#nation-state attacks`, `#ICS/SCADA`

---

<a id="item-4"></a>
## [Dasharo 将开源固件带到 AM5](https://www.tomshardware.com/pc-components/motherboards/first-open-source-firmware-for-am5-officially-launches-dasharo-v0-9-0-brings-coreboot-and-opensil-to-zen-4-apus-on-msi-b850) ⭐️ 8.0/10

3mdeb 已为 MSI B850-P WiFi 发布 Dasharo v0.9.0，标志着 AM5 平台首次正式推出开源固件。此次发布把 coreboot 与 AMD openSIL 结合起来，并支持该主板上的 Zen 4 APU。 这对现代 AMD 桌面平台上的开放固件来说是一个重要里程碑，因为它表明 coreboot 和 openSIL 已经可以在 AM5 硬件上协同使用。对于系统装机者、研究人员以及希望获得比传统 BIOS/UEFI 更强可审计性和控制权的用户来说，这可能很有意义。 这次公告具体针对 MSI B850-P WiFi，因此它并不是整个 AM5 平台的全面铺开，而是一个主板级别的里程碑。文中提到的支持对象是 Zen 4 APU，这说明虽然平台意义很大，但实际覆盖范围仍然有限。

rss · Tom's Hardware · 8月2日 12:10

**背景**: coreboot 是一个开源固件项目，它先初始化硬件，再把启动流程交给操作系统，从而替代传统的专有 BIOS/UEFI 固件。AMD openSIL 是 AMD 的开放式芯片初始化库，旨在作为主机固件的一部分参与早期启动过程。AM5 是 AMD 的桌面处理器插槽/平台，而 Zen 4 APU 则是把 CPU 核心与集成显卡结合在一起的 AMD 处理器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coreboot.org/">coreboot - Fast, secure and flexible Open Source firmware</a></li>
<li><a href="https://github.com/openSIL/openSIL">GitHub - openSIL/openSIL AMD openSIL "Open-Source" Firmware Lands On AM5 ... - Wccftech AMD's open-source openSIL firmware is being ported to Zen 5 ... AMD openSIL | Basic Input/Output GitHub - openSIL/amd_firmwares: Platform Initialization (PI ... First open-source firmware for AM5 officially launches ...</a></li>
<li><a href="https://www.amd.com/en/blogs/2023/empowering-the-industry-with-open-system-firmware-.html">Empowering The Industry with Open System Firmware – AMD openSIL</a></li>

</ul>
</details>

**标签**: `#open-source firmware`, `#coreboot`, `#AM5`, `#openSIL`, `#BIOS/UEFI`

---

<a id="item-5"></a>
## [CausalVLBench 评测视觉因果推理](https://www.reddit.com/r/MachineLearning/comments/1vdd7ty/r_causalvlbench_benchmarking_visual_causal/) ⭐️ 8.0/10

CausalVLBench 是一个新的基准，用于衡量大型视觉语言模型处理视觉因果推理的能力。该 Reddit 帖子以论文分享的形式介绍了这一基准，并引导读者查看原始研究。 视觉因果推理一直是多模态 AI 的薄弱环节，因此专门的基准可以让研究者更清晰地衡量进展。它也有助于更严格地比较模型，并判断视觉语言模型的改进是否真的转化为对图像中因果关系的更好理解。 这个基准专门聚焦于视觉因果推理，而不是泛化的视觉问答或宽泛的多模态推理。之所以重要，是因为先前研究已经指出，视觉表征学习中的因果推理仍缺少成熟的评测，而当关键线索隐藏在视觉细节中时，多模态因果推理会变得更难。

reddit · r/MachineLearning · /u/moschles · 8月2日 09:07

**背景**: 视觉语言模型是将图像理解与自然语言生成或推理结合起来的系统。这个领域中的基准非常重要，因为它们提供了标准化测试，用来比较模型在特定能力上的表现，例如组合推理或因果性。因果推理不仅要判断图像里有什么，还要判断什么导致了什么，这比简单识别更难。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://link.springer.com/article/10.1007/s11633-022-1362-z">Causal Reasoning Meets Visual Representation Learning: A Prospective Study | Machine Intelligence Research | Springer Nature Link</a></li>
<li><a href="https://arxiv.org/abs/2408.08105">Multimodal Causal Reasoning Benchmark: Challenging Vision Large ...</a></li>
<li><a href="https://antresearchnlp.github.io/vilabench/">ViLaBench - Vision-Language Model Benchmark</a></li>

</ul>
</details>

**标签**: `#vision-language models`, `#benchmarks`, `#causal reasoning`, `#multimodal AI`, `#machine learning research`

---

<a id="item-6"></a>
## [大型科技公司的两万亿美元 AI 重置](https://finance.yahoo.com/technology/ai/articles/big-tech-2-trillion-ai-183300493.html) ⭐️ 8.0/10

这篇文章称，约 2 万亿美元的 AI 投资洗牌正在重塑大型科技公司以及更广泛的 AI 市场。文章将这一时刻描述为一个重大转折点，而不只是单纯的支出扩张。 如果这轮洗牌继续下去，它可能决定哪些公司会掌控 AI 技术栈，从基础设施到平台再到应用层。这样一来，投资者、云服务商、AI 初创公司以及选择自建或采购 AI 服务的企业都会受到影响。 这种说法暗示，AI 行业正在进入整合阶段，只有最强的玩家才能承受如此大规模的资本支出。文章没有给出具体的技术产品细节，但它强调了市场结构、投资集中度，以及赢家可能会在当前的烧钱竞赛中逐步浮现。

openbb · AAPL · 8月2日 18:33

**背景**: 在科技报道中，“洗牌”通常指的是一个阶段：热度和高额支出让位于行业整合，较弱的参与者退出，较强的参与者获得更多份额。对于 AI 来说，大型科技公司的巨额资本开支往往投向数据中心、芯片和云基础设施，用于训练和运行大模型。由于这些投入非常昂贵，它们既会抬高小型竞争者的进入门槛，也会迫使市场去验证哪些 AI 产品能够产生持续需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ceo-worldwide.com/blog/the-coming-shakeout-in-ai-what-the-market-share-battle-means-for-business-leaders/">The Coming Shakeout in AI: What the Market Share Battle Means for ...</a></li>
<li><a href="https://tech-insider.org/big-tech-650-billion-ai-infrastructure-capex-2026/">Big Tech's $650B AI Capex Surge Reshaping the Economy [2026]</a></li>

</ul>
</details>

**标签**: `#AI`, `#Big Tech`, `#technology markets`, `#industry analysis`, `#investment`

---