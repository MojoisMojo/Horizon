---
layout: default
title: "Horizon Summary: 2026-06-27 (ZH)"
date: 2026-06-27
lang: zh
---

> 从 129 条内容中筛选出 15 条重要资讯。

---

1. [GPT-5.6 发布，超越 Fable5 成为最强基座模型](#item-1) ⭐️ 9.0/10
2. [DeepSeek DSpark 推出投机解码加速大语言模型推理](#item-2) ⭐️ 8.0/10
3. [可疑的不连续性：激励与阈值导致的数据异常](#item-3) ⭐️ 8.0/10
4. [网络安全分析呼吁在 Mythos AI 炒作中保持冷静](#item-4) ⭐️ 8.0/10
5. [Gemma 2 9B FP8 基准测试：L4 上的预填充代价与 VRAM 现实](#item-5) ⭐️ 8.0/10
6. [台积电与 Amkor 在亚利桑那建立十年先进封装合作](#item-6) ⭐️ 8.0/10
7. [IP Crawl 曝光未加密摄像头，引发隐私担忧](#item-7) ⭐️ 7.0/10
8. [OpenRA：经典 RTS 游戏的现代化复兴](#item-8) ⭐️ 7.0/10
9. [TownSquare 为网站带来短暂无需账号的在线存在感](#item-9) ⭐️ 7.0/10
10. [新博客文章为实体媒体所有权辩护，DRM 问题引发热议](#item-10) ⭐️ 7.0/10
11. [微软报告：员工已准备好运用 AI，企业却跟不上](#item-11) ⭐️ 7.0/10
12. [MathFormer 测试符号数学是模式匹配而非推理](#item-12) ⭐️ 7.0/10
13. [杭州团队宣称实现全球首个端侧流式多模态 AI](#item-13) ⭐️ 6.0/10
14. [Ky 2.0 发布：重构钩子、改进超时与内置模式校验](#item-14) ⭐️ 6.0/10
15. [液冷 TE Connectivity 800V 直流母线及纬颖展台更多亮点](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [GPT-5.6 发布，超越 Fable5 成为最强基座模型](https://www.qbitai.com/2026/06/438895.html) ⭐️ 9.0/10

OpenAI 于 2026 年 6 月 26 日发布了包含三款模型的 GPT-5.6 系列，号称超越 Anthropic 的 Fable5，成为最强基座模型。 此次发布加剧了大语言模型领域的竞争，可能改变竞争格局，并提升了人工智能能力与安全性的标准。 该系列包含三个变体，其中 GPT-5.6 Sol 具备更强的编程、科学推理和网络安全能力，并配有先进的安全框架；初期发布范围有限，随后几周将逐步扩大开放。

rss · 量子位 · 6月27日 01:53

**背景**: GPT-5.6 是 OpenAI 的新一代大语言模型，而 Fable5 是 Anthropic 在几周前发布的 Mythos 级模型，专为复杂的自主编程设计。两者均代表人工智能的最前沿，其基准测试结果凸显了自然语言理解和生成能力的快速进步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.6">GPT-5.6</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT-5.6 Sol: a next-generation model | OpenAI</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>

</ul>
</details>

**标签**: `#AI`, `#GPT-5.6`, `#Large Language Models`, `#OpenAI`, `#Model Release`

---

<a id="item-2"></a>
## [DeepSeek DSpark 推出投机解码加速大语言模型推理](https://github.com/deepseek-ai/DeepSpec/blob/main/DSpark_paper.pdf) ⭐️ 8.0/10

DeepSeek 发布了 DSpark 论文及实现，采用投机解码技术，先由小型草稿模型预测多个词元，再由大型目标模型一次性验证，从而加速大语言模型推理。HuggingFace 上现已提供集成该技术的 DeepSeek-V4-Flash-DSpark 和 DeepSeek-V4-Pro-DSpark 模型。 该技术在保持输出质量的同时将吞吐量提升 51-400%，解决了大语言模型部署的核心延迟问题。这家中国实验室的开放研究凸显了 AI 创新透明化趋势，与部分西方实验室的封闭做法形成对比。 DSpark 属于 DeepSpec 开源代码库，并非新模型，而是一个可集成模块。它利用草稿模型生成候选词元序列，再通过拒绝采样验证，确保输出分布与原始目标模型完全一致。

hackernews · aurenvale · 6月27日 09:18 · [社区讨论](https://news.ycombinator.com/item?id=48696585)

**背景**: 投机解码是一种推理优化方法，通过小型草稿模型预测多个后续词元，再由大模型并行验证，通常可实现 2-3 倍加速。DeepSeek 的 DSpark 将此应用于 V4 模型，报告提速达 400%。DeepSpec 仓库则提供了训练和评估该类算法的完整工具链。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding</a></li>
<li><a href="https://www.explainx.ai/blog/deepseek-dspark-v4-speculative-decoding-deepspec-guide-2026">DeepSeek DSpark: V4 Speculative Decoding Guide 2026 ...</a></li>
<li><a href="https://github.com/deepseek-ai/DeepSpec/blob/main/DSpark_paper.pdf">DeepSpec/DSpark_paper.pdf at main · deepseek-ai/DeepSpec</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞 DeepSeek 不断突破并公开研究，有人指出中国实验室在 AI 创新中领先。用户对预置的 HuggingFace 模型感到兴奋，并表示计划将其用于本地推理，尤其是 2 位量化版本。还有些人将其与更封闭的美国实验室做法进行了对比，认为 DeepSeek 的做法更值得肯定。

**标签**: `#speculative-decoding`, `#LLM-inference`, `#DeepSeek`, `#open-source`, `#performance`

---

<a id="item-3"></a>
## [可疑的不连续性：激励与阈值导致的数据异常](https://danluu.com/discontinuities/) ⭐️ 8.0/10

丹·卢（Dan Luu）2020 年关于可疑数据不连续性的文章通过社区讨论重新引起关注，读者分享了马拉松成绩目标和税收悬崖效应等具体例子。 讨论揭示了任意阈值和激励结构如何系统性地扭曲数据，导致从税收政策到软件工程性能指标等多个领域得出误导性结论。 主要例子包括波兰语考试成绩在及格线上出现峰值、马拉松完赛时间在整数分钟目标前聚集，以及 AWS 延迟指标因工程师优化而在 P50 和 P90 目标附近出现人为聚集。

hackernews · tosh · 6月27日 13:32 · [社区讨论](https://news.ycombinator.com/item?id=48698151)

**背景**: 数据不连续性是指分布中突然的断裂或尖峰，偏离了预期的平滑模式。这些通常由人为阈值（例如考试 70 分及格）或激励结构（例如与特定指标挂钩的绩效奖金）引起。丹·卢的分析强调了这些人为因素如何损害统计数据的可靠性，这在教育、金融和软件性能监控等多个领域都是一个值得关注的问题。

**社区讨论**: 评论者热情地分享了个人轶事和额外例子，如马拉松完赛时间、英国税收悬崖、国际象棋评分聚集以及 AWS 延迟指标的人为操作，生动说明了任意阈值对行为和数据带来的广泛且有时滑稽的影响。

**标签**: `#data analysis`, `#statistics`, `#incentives`, `#thresholds`, `#community-discussion`

---

<a id="item-4"></a>
## [网络安全分析呼吁在 Mythos AI 炒作中保持冷静](https://cephalosec.com/blog/cybersecurity-in-the-post-mythos-era-keep-calm-and-carry-on/) ⭐️ 8.0/10

一篇题为《后 Mythos 时代的网络安全：保持冷静，继续前行》的博客文章发布，提供了冷静的视角，驳斥了围绕 Anthropic 的 Mythos 等 AI 漏洞检测模型的过度恐惧和行业炒作。 它为安全专业人士提供了必要的现实检验，鼓励理性评估而非耸人听闻，这可能影响组织如何分配资源，并避免被供应商的恐惧营销误导。 文章强调，大多数安全问题源于错误配置和不良实践，而非先进的 AI 攻击，并指出发现一个 BSD 漏洞需要巨大的人工努力，从而客观看待 Mythos 等模型的实际能力。

hackernews · Versipelle · 6月27日 14:23 · [社区讨论](https://news.ycombinator.com/item?id=48698559)

**背景**: Mythos 是 Anthropic 开发的大型语言模型，用于发现软件漏洞，由政府控制并附带安全限制发布，引发了兴奋和恐慌。网络安全行业经常放大新威胁以推动产品销售，而随着 LLMs 展现解决挑战的熟练度，CTF 竞赛正在演变。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mythos_(model)">Mythos (model)</a></li>
<li><a href="https://www.anthropic.com/claude/mythos">Claude Mythos \ Anthropic</a></li>

</ul>
</details>

**社区讨论**: 评论者大多支持冷静观点，指出在 Mythos 发布后供应商的恐惧营销立即开始。他们观察到，即使是 Deepseek V4 Flash 这样的开放模型也能发现漏洞，CTF 赛制必须改变，而 AI 对安全性的现实影响往往被夸大，相比之下日常的错误配置才是主要问题。

**标签**: `#cybersecurity`, `#ai`, `#llm`, `#vulnerability-detection`, `#industry-analysis`

---

<a id="item-5"></a>
## [Gemma 2 9B FP8 基准测试：L4 上的预填充代价与 VRAM 现实](https://www.reddit.com/r/MachineLearning/comments/1uhdxnb/benchmarking_selfhosted_gemma_2_9b_vs_frontier/) ⭐️ 8.0/10

对自托管 Gemma 2 9B 进行 FP8 量化的实证基准测试发现，由于反量化开销，长上下文提示的首 token 时间增加了 58%，但中等长度生成任务的端到端延迟降低了约 6%。 这挑战了 FP8 量化总能加速推理的普遍假设，凸显了 ML 从业者在自托管时必须考虑的交互相应延迟与吞吐量之间的关键权衡。 在搭载 vLLM 的 NVIDIA L4 GPU 上，FP8 将复杂提示的预填充 TTFT 从 866.93ms 增加到 1372.12ms，并在调度期间导致高达 1740.34ms 的尖峰；但中等长度序列的平均客户端总时间从 12,290.2ms 降至 11,526.2ms。

reddit · r/MachineLearning · /u/Ok_Waltz_5145 · 6月27日 21:05

**背景**: FP8 量化将模型权重从 16 位浮点压缩至 8 位，减少了内存带宽但增加了反量化开销。vLLM 是一个具有 PagedAttention 功能的开源 LLM 服务系统。NVIDIA L4 是一款 24GB 显存的通用数据中心 GPU。Gemma 2 9B 是谷歌开发的 90 亿参数语言模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/FP8_Quantization">FP8 Quantization</a></li>
<li><a href="https://en.wikipedia.org/wiki/VLLM">VLLM</a></li>
<li><a href="https://flopper.io/compare/nvidia-a30-24gb-vs-nvidia-l4-24gb">NVIDIA A30 vs NVIDIA L 4 - GPU Comparison | Flopper.io</a></li>

</ul>
</details>

**标签**: `#LLM inference`, `#quantization`, `#benchmarking`, `#vLLM`, `#self-hosting`

---

<a id="item-6"></a>
## [台积电与 Amkor 在亚利桑那建立十年先进封装合作](https://finance.yahoo.com/technology/articles/taiwan-semiconductor-tsm-amkor-amkr-161535396.html) ⭐️ 8.0/10

台积电与 Amkor 宣布建立为期十年的合作伙伴关系，将在亚利桑那州共同开发并运营先进半导体封装设施，以增强美国芯片制造能力。 此次合作通过扩大美国本土的先进封装产能，减少了对亚洲设施的依赖，并支持人工智能和高性能计算所需尖端芯片的生产，从而加强了美国半导体供应链的韧性。 先进封装涵盖 CoWoS 和 InFO 等技术，能够实现多芯片异构集成，对 AI 加速器至关重要；该合作旨在结合台积电的专业知识与 Amkor 的封测能力。

openbb · AMD · 6月27日 16:15

**背景**: 先进半导体封装是将多个组件（如逻辑芯片、存储器和传感器）集成到单个封装中以提升性能和效率的技术。台积电的 CoWoS（晶圆上芯片封装）和 InFO（集成扇出型封装）等技术是支持小芯片设计的关键，这对高功耗 AI 芯片至关重要。Amkor 作为领先的外包半导体封装和测试供应商，拥有丰富的封装经验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Advanced_packaging_(semiconductors)">Advanced packaging (semiconductors) - Wikipedia</a></li>
<li><a href="https://www.synopsys.com/glossary/what-is-advanced-semiconductor-packaging.html">What is Advanced Semiconductor Packaging? | Synopsys</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#advanced packaging`, `#TSMC`, `#Amkor`, `#manufacturing`

---

<a id="item-7"></a>
## [IP Crawl 曝光未加密摄像头，引发隐私担忧](https://ipcrawl.com/) ⭐️ 7.0/10

IP Crawl 网站发布了一个全球公开可访问的网络摄像头实时索引，揭示了无需认证即可轻易找到联网摄像头的情况。 该网站凸显了物联网设备普遍存在的安全漏洞，并引发了关于监控、隐私及未经同意聚合视频流的伦理争议。 该索引包含来自廉价中国品牌且使用默认设置的摄像头，涵盖公共与私人空间，查看无需登录或授权。

hackernews · arm32 · 6月27日 19:09 · [社区讨论](https://news.ycombinator.com/item?id=48700834)

**背景**: 许多 IP 摄像头出厂时带有默认密码且缺乏安全配置，易被 Shodan 等搜索引擎发现。用户常在不知情的情况下将私生活暴露于公网。类似的摄像头聚合工具至少自 2012 年就已存在，显示该问题由来已久。

**社区讨论**: 评论者对网站的窥探性质感到不适，比喻为用望远镜窥视邻居公寓。有人指出此类曝光历史悠久，并建议创建者应提醒受影响用户；一条评论提到其中一个摄像头正在监控非法大麻种植。

**标签**: `#webcams`, `#privacy`, `#security`, `#IoT`, `#surveillance`

---

<a id="item-8"></a>
## [OpenRA：经典 RTS 游戏的现代化复兴](https://www.openra.net/) ⭐️ 7.0/10

OpenRA 是一个备受推崇的开源引擎，可重建并现代化经典的即时战略游戏，如《红色警戒》、《命令与征服》和《沙丘 2000》，具备精炼的平衡性和现代便捷功能。 它让经典游戏在现代系统上得以保存，添加了各种提升体验的功能，并维持着活跃的多人游戏社区，抗衡了原发行商（如 EA）的忽视。 OpenRA 是一个使用 C# 和 SDL 从零开始实现的引擎，支持多个游戏的模组，并包含单位经验等级、地图编辑器、回放以及跨平台支持等现代功能。

hackernews · tosh · 6月27日 12:10 · [社区讨论](https://news.ycombinator.com/item?id=48697560)

**背景**: 像《命令与征服：红色警戒》这样的经典即时战略游戏由 Westwood Studios 在 20 世纪 90 年代开发，随后被电子艺界（EA）收购，但后者提供的官方支持甚少。OpenRA 作为一个社区驱动的项目应运而生，旨在对这些游戏进行逆向工程并加以现代化，提供了一个免费、开源的引擎和更新的游戏机制及多人游戏基础架构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.openra.net/">OpenRA - Classic strategy games rebuilt for the modern era</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调 OpenRA 相较于原版在游戏平衡上的显著改进，例如让盟军火炮能够远程压制苏联的特斯拉线圈，并盛赞其现代功能。不过，也有用户指出在线游戏的体验可能极具毒性，并对 EA 对该系列的处理方式表示失望。

**标签**: `#open-source`, `#game-development`, `#strategy-games`, `#retro-gaming`, `#gaming-community`

---

<a id="item-9"></a>
## [TownSquare 为网站带来短暂无需账号的在线存在感](https://cauenapier.com/blog/townsquare_release/) ⭐️ 7.0/10

TownSquare 是一个开源的 JavaScript 库，已正式发布，能让网站在无需用户账号且不保存聊天记录的情况下，添加实时短暂的在线存在感和聊天功能。 它复兴了早期网络那种自发、去中心化的互动方式，挑战主流的社交网络模式，并支持 indieweb 运动关于个人独立网站的愿景。 它基于 WebTorrent 构建，使用 WebRTC 实现浏览器间的点对点通信；没有账号、个人资料或永久聊天记录，消息只在用户在线时存在。

hackernews · eustoria · 6月27日 17:11 · [社区讨论](https://news.ycombinator.com/item?id=48699928)

**背景**: IndieWeb 是一个倡导个人网站和内容所有权而非企业平台的社区。WebTorrent 则利用 WebRTC 实现浏览器之间的直接点对点数据传输，无需中央服务器。TownSquare 将这些概念结合，让网站访客能短暂地看到彼此并聊天，重现早期互联网论坛和聊天室中那种‘偶遇’的感觉。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebTorrent">WebTorrent</a></li>
<li><a href="https://en.wikipedia.org/wiki/IndieWeb">IndieWeb</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：一些人称赞其怀旧、自发的体验，并看到了社群建设的潜力；另一些人则认为界面混乱、令人困惑，有用户提到小棍人移动过快。也有人指出类似的过往实验，并呼吁更多线下聚会工具。

**标签**: `#indieweb`, `#presence`, `#ephemeral-chat`, `#WebTorrent`, `#web-development`

---

<a id="item-10"></a>
## [新博客文章为实体媒体所有权辩护，DRM 问题引发热议](https://dervis.de/physical/) ⭐️ 7.0/10

一篇题为'实体媒体所有权的理由'的博客文章引发了关于数字权利、DRM 以及所有权与许可授权的激烈讨论。 这场争论凸显了消费者对可撤销数字购买的不满，在日益依赖订阅的媒体格局中，便利性与真实所有权之间的紧张关系日益加剧。 值得注意的例子包括 2019 年 Ultraviolet 数字锁柜的失败，以及索尼近日通知将在 2026 年从用户资料库中移除已购买的 Studio Canal 内容。

hackernews · cemdervis · 6月27日 11:32 · [社区讨论](https://news.ycombinator.com/item?id=48697335)

**背景**: DRM（数字版权管理）技术限制用户访问或分享数字内容的方式，通常强制执行许可条款而非所有权。历史上，UltraViolet 等计划试图创建跨平台数字版权柜，但最终关闭，导致用户无法访问购买的内容。这突显了依赖带 DRM 的数字媒体相比物理拷贝的风险，后者可以转售、分享或永久保存。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Digital_rights_management">Digital rights management - Wikipedia</a></li>
<li><a href="https://www.fortinet.com/resources/cyberglossary/digital-rights-management-drm">What Is DRM? Digital Rights Management Explained | Fortinet</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍支持所有权，但方法上存在分歧：一些人认为数字无 DRM 购买（如 GOG、Bandcamp）可以提供真正的所有权，而另一些人则主张由于许可复杂，盗版是实用的解决方案。Ultraviolet 关闭和索尼移除内容的事件被作为警示案例分享，加深了对数字'购买'的怀疑。

**标签**: `#physical-media`, `#digital-rights`, `#drm`, `#ownership`, `#piracy`

---

<a id="item-11"></a>
## [微软报告：员工已准备好运用 AI，企业却跟不上](https://www.qbitai.com/2026/06/439032.html) ⭐️ 7.0/10

微软年度 AI 职场报告显示，员工热情高涨并已准备好采用 AI 工具，但多数企业未能提供必要的基础设施、培训和战略方向。 这一差距凸显了数字化转型的关键瓶颈：即便有积极能干的员工，组织的惯性和资源不足仍可能阻碍 AI 大规模提升生产力。 这份长达 28 页的报告可能提供了关于采用率、企业面临的障碍以及缩小准备度差距的建议等数据。

rss · 量子位 · 6月27日 04:48

**标签**: `#AI`, `#workplace`, `#Microsoft`, `#report`, `#digital transformation`

---

<a id="item-12"></a>
## [MathFormer 测试符号数学是模式匹配而非推理](https://www.reddit.com/r/MachineLearning/comments/1uhatw8/mathformer_testing_whether_symbolic_math_is/) ⭐️ 7.0/10

一个仅 4 百万参数的序列到序列模型 MathFormer，在无数学知识训练下，于符号展开任务上达到了约 98.6%的准确率，表明其学习的是结构性标记转换而非数学推理。 这一发现支持了 LLM 的数学能力可能源于大规模模式匹配的假说，挑战了它们进行真正推理的观点，对 AI 可解释性和可信度有重要影响。 该模型通过在因式分解表达式上训练以预测展开形式，如 (7-3z)*(-5z-9) → 15z*2-8*z-63。它仅 4 百万参数，无内置数学知识，通过令牌级转换学习达到高准确率。

reddit · r/MachineLearning · /u/AlphaCode1 · 6月27日 18:57

**背景**: 符号展开是一种基本代数运算，将乘积的和转换为和之乘积，如 (x-2)*(x-4) 变为 x^2 - 6x + 8。Transformer 是一种使用自注意力机制处理序列的神经网络架构，擅长捕捉数据中的模式。MathFormer 的实验为关于大型语言模型是真正“推理”还是仅进行复杂的模式补全的持续辩论提供了新的视角。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Polynomial_expansion">Polynomial expansion - Wikipedia</a></li>

</ul>
</details>

**标签**: `#machine-learning`, `#symbolic-math`, `#reasoning`, `#transformers`, `#pattern-matching`

---

<a id="item-13"></a>
## [杭州团队宣称实现全球首个端侧流式多模态 AI](https://www.qbitai.com/2026/06/439236.html) ⭐️ 6.0/10

以 VLM-R1 闻名的杭州团队宣布推出全球首个端侧流式多模态 AI 系统，可在边缘设备上实现实时多模态处理。 这一突破将低延迟、保护隐私的多模态 AI 直接带到智能手机等终端设备上，有望变革移动应用、增强现实和机器人等领域。 该公告缺乏技术细节，但该团队此前发布了 VLM-R1——一个基于 R1 范式的通用大型视觉语言模型；新系统很可能在此基础上实现了设备端流式推理，但未公开基准测试或硬件要求。

rss · 量子位 · 6月27日 12:19

**背景**: VLM-R1 是 om-ai-lab 的一个项目，将 DeepSeek-R1 的强化学习技术应用于视觉语言模型，实现思维链推理。端侧多模态 AI 旨在直接在手机或 AR 眼镜等设备上运行模型，消除云端延迟并增强隐私。流式处理指以实时数据到达的方式进行处理。CVPR 是顶级计算机视觉会议，常展示此类进展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aiinovationhub.com/on-device-multimodal-ai-mobile-vision-2026/">On Device Multimodal AI: Mobile Vision Breakthrough</a></li>

</ul>
</details>

**标签**: `#multimodal-ai`, `#edge-computing`, `#computer-vision`, `#vlm`, `#cvpr`

---

<a id="item-14"></a>
## [Ky 2.0 发布：重构钩子、改进超时与内置模式校验](https://www.infoq.cn/article/v1wsHJd54imD1b4yUeYf?utm_source=rss&utm_medium=article) ⭐️ 6.0/10

Ky 2.0 引入了重构的钩子机制以实现更灵活的请求/响应拦截，改进了超时处理以更好地控制请求时长，并内置了 JSON Schema 校验以保证数据完整性。 这些改进通过简化认证、日志和数据校验等常见模式提升了开发体验，使 Ky 更具竞争力，更适用于生产环境中的现代 Web 应用。 重构后的钩子现在更易于组合和使用，超时处理支持每个请求独立的超时设置和更清晰的错误信息，内置的模式校验利用 JSON Schema 自动校验响应体。

rss · InfoQ 中国 · 6月27日 09:00

**背景**: Ky 是一个基于 Fetch API 的轻量级 JavaScript HTTP 客户端库，提供更简单直观的接口，并支持重试、进度跟踪和前缀 URL 等功能。它由知名开源开发者 Sindre Sorhus 创建。之前的版本已有钩子和超时支持，但 2.0 对这些功能进行了全面改进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://yaoweibin.cn/node-js-http-client-and-request-library">7 强大的 Node.js HTTP 客 户 端 和请求 库 ，作为开发者要了解 - 姚伟斌</a></li>

</ul>
</details>

**标签**: `#Ky`, `#HTTP client`, `#JavaScript`, `#Library release`, `#Web development`

---

<a id="item-15"></a>
## [液冷 TE Connectivity 800V 直流母线及纬颖展台更多亮点](https://www.servethehome.com/liquid-cooling-a-te-connectivity-800v-dc-busbar-and-more-from-the-wiwynn-booth/) ⭐️ 6.0/10

在纬颖展台上，TE Connectivity 展示了一款为下一代 AI 加速器设计的液冷 800V 直流母线，演示了配电组件如何也融入液冷技术。 随着 AI 数据中心向 800V 直流架构过渡，机架功率密度攀升至 50–200kW，液冷母线对于安全管理热量、提高能效并保障高功率加速器可靠运行至关重要。 TE 的液冷母线采用先进多通道冷却，直接在导体处带走热量，降低电阻，减少热应力，并削减数据中心冷却能耗。NVIDIA 的 800V 直流架构目标支持 1 兆瓦机架，消除多次交直流转换。

rss · ServeTheHome · 6月27日 02:18

**背景**: 传统数据中心采用交流配电并经过多次转换，造成能量损失。高功率 AI 加速器需要高效的直流供电。行业正向 800V 直流转变，以简化配电、减少铜材用量。母线液冷将热管理延伸到配电层，支撑更高的机架密度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.te.com/content/dam/te-com/documents/datacomm/global/orv3-liquid-cooled-busbar.pdf">ORv3 Liquid Cooled Vertical Busbar for Al Racks</a></li>
<li><a href="https://www.nvidia.com/en-us/data-center/technologies/800-vdc-architecture/">800 VDC Architecture for AI Data Centers | NVIDIA</a></li>
<li><a href="https://www.molex.com/en-us/products/connectors/high-power-solutions/busbars/liquid-cooled-busbar">Liquid Cooled Busbars | Molex</a></li>

</ul>
</details>

**标签**: `#liquid cooling`, `#data center`, `#AI hardware`, `#busbar`, `#Wiwynn`

---