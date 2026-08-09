---
layout: default
title: "Horizon Summary: 2026-08-09 (ZH)"
date: 2026-08-09
lang: zh
---

> 从 102 条内容中筛选出 8 条重要资讯。

---

1. [数学家发现：任意阶的幻六边形均存在](#item-1) ⭐️ 9.0/10
2. [GPT-5.6 与 Fable 合作解开 25 年未解数学难题](#item-2) ⭐️ 9.0/10
3. [OpenAI 向 10 亿用户免费推出 GPT-5.6](#item-3) ⭐️ 9.0/10
4. [Os8088：用 8086 汇编手写、为 IBM XT 打造的类 Mac 图形系统](#item-4) ⭐️ 8.0/10
5. [Shopify 用 MySQL 取代 Redis 做库存预留并成功扩展](#item-5) ⭐️ 8.0/10
6. [亚马逊得州 7.65GW 燃气电厂或成美国最大碳排放源](#item-6) ⭐️ 8.0/10
7. [苹果测试中国长鑫存储内存芯片，用于 iPhone 和 MacBook](#item-7) ⭐️ 8.0/10
8. [Moonshot AI 2.8 万亿参数模型登顶重大编程基准](#item-8) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [数学家发现：任意阶的幻六边形均存在](https://gukov.dev/math/2026/08/02/new-magic-hexagons.html) ⭐️ 9.0/10

Gukov 于 2026 年 8 月 2 日发表了一篇新文章，利用优雅的势场方法和交互式可视化，构造出任意阶 n 的幻六边形。关键见解是允许连续整数从 1 以外的某个数开始，从而为所有阶数生成有效的幻六边形。 这一结果挑战了长期以来“幻六边形仅存在于 1 阶和 3 阶”的认知，这一限制自 19 世纪以来就为人所知。它为组合数学和趣味数学开辟了新方向，势场方法也可能为构造其他幻方配置提供通用框架。 文章引入一种势场构造方法，将连续整数填入 n 阶六边形网格，使三条轴方向上的所有行之和等于同一个幻常数。构造似乎允许起始数不为 1，这才使得所有阶数都能实现；文章还带有交互式演示，便于读者探索不同阶数。

hackernews · gukoff · 8月9日 07:19 · [社区讨论](https://news.ycombinator.com/item?id=49229174)

**背景**: n 阶幻六边形是指在一个中心六边形图案中（每条边有 n 个格子）填入数字，使得三个方向上每一行的数字之和都等于同一个幻常数。正规幻六边形使用从 1 到 3n² − 3n + 1 的连续整数；长期已知正规幻六边形仅存在于 n = 1（平凡）和 n = 3，且 3 阶解（数字 1–19，幻和为 38）在旋转和反射意义下唯一，最早由 Ernst von Haselberg 于 1887 年提出。这篇文章通过允许连续整数从任意整数开始推广了定义，并利用势场（势函数）方法构造出所有阶数的解。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Magic_hexagon">Magic hexagon</a></li>
<li><a href="https://encyclopediaofmath.org/wiki/Potential_field">Potential field - Encyclopedia of Mathematics</a></li>

</ul>
</details>

**社区讨论**: 评论者总体上非常热情，称赞势场方法的优雅、交互式可视化以及文章的可读性。技术讨论集中在：在放宽的定义下 2 阶是否真的可解、势场能有多平滑（例如 Lipschitz 连续程度），以及该方法能否推广到矩形网格；还有人开玩笑说“六边形是最好的多边形（hexagons are the bestagons）”。

**标签**: `#mathematics`, `#magic-hexagons`, `#combinatorics`, `#interactive-visualization`, `#research`

---

<a id="item-2"></a>
## [GPT-5.6 与 Fable 合作解开 25 年未解数学难题](https://www.qbitai.com/2026/08/468913.html) ⭐️ 9.0/10

量子位报道称，OpenAI 的 GPT-5.6 与 Anthropic 的 Fable 模型联手解决了一道悬置 25 年的数学难题。该难题的作者从读博期间就开始研究，经过 17 年努力，最终被 AI 解开。 这一里程碑表明，先进 AI 模型能够跨实验室协作攻克长期未解的难题。它标志着 AI 辅助数学发现的转变，可能加速研究进程，并改变数学家处理未解问题的方式。 量子位的文章未提及该数学难题的具体内容，因此具体猜想尚未公开。值得注意的是，此前不久 Claude Fable 5 刚刚推翻了 87 年历史的 Jacobian 猜想，反映出 AI 解决重大数学问题的趋势正在加强。

rss · 量子位 · 8月9日 09:16

**背景**: GPT-5.6 是 OpenAI 于 2026 年 7 月 9 日发布的大语言模型，提供 Luna、Terra、Sol 三个版本。Anthropic 的“Fable”（即 Claude Fable 5）近期因找到 Jacobian 猜想的反例而成为新闻焦点，该猜想已开放 87 年。AI 系统正越来越多地攻克开放数学问题，但结果通常仍需人类数学家验证。这一报道表明，不同公司的模型可以在此类任务上协作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.6">GPT-5.6 - Wikipedia</a></li>
<li><a href="https://www.sciencedaily.com/releases/2026/08/260804034634.htm">Claude Fable 5 AI finds a tiny formula that topples an 87-year-old math conjecture | ScienceDaily</a></li>

</ul>
</details>

**标签**: `#AI`, `#mathematics`, `#GPT-5.6`, `#Fable`, `#breakthrough`

---

<a id="item-3"></a>
## [OpenAI 向 10 亿用户免费推出 GPT-5.6](https://www.infoq.cn/article/RXRuR3TN9msNMAUWRtCl?utm_source=rss&utm_medium=article) ⭐️ 9.0/10

据报道，OpenAI 发布了 GPT-5.6，这是一个全新的三档 AI 模型系列，并免费向大约 10 亿用户开放。6 月 26 日的发布推出了三个模型，分别名为 Sol、Terra 和 Luna。 这将是开创性的举措，可能是前沿 AI 模型规模最大的一次免费推送，影响开发者、企业和普通用户。它可能加剧 AI 实验室之间的竞争，并大规模加速先进推理和智能体编码能力的采用。 GPT-5.6 被定位为 OpenAI 最新的模型系列，适用于前沿智能体编码、高级推理和可扩展的生产工作流。Sol、Terra 和 Luna 这三个模型主要在智能水平、速度和成本上有所不同，用户可以选择合适的平衡点。

rss · InfoQ 中国 · 8月9日 10:23

**背景**: GPT-5.6 延续了 OpenAI 不断迭代发布 GPT 系列的模式，每一代都承诺更强的推理能力和更广的适用性。将这样的模型免费提供给 10 亿用户将是一种前所未有的分发策略，可能通过面向消费者的产品和合作伙伴来实现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wud.no/en/blogg/gpt-5-6-sol-terra-luna-for-bedrifter">GPT - 5 . 6 explained: Sol, Terra and Luna for businesses</a></li>
<li><a href="https://www.cometapi.com/models/openai/gpt-5-6/">GPT 5 . 6 API - Access OpenAI GPT 5 . 6 at Best Price | CometAPI</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#GPT-5.6`, `#AI`, `#LLM`, `#Release`

---

<a id="item-4"></a>
## [Os8088：用 8086 汇编手写、为 IBM XT 打造的类 Mac 图形系统](https://os8088.com/) ⭐️ 8.0/10

Os8088 是一款面向 IBM PC/XT 级机器的图形化类 Mac 操作系统，完全用实模式 8086 汇编编写，并借助 AI 模型 Claude 辅助开发。项目提供可启动软盘镜像，内核仅有 52,718 字节，软件盘上带有扫雷、记事本、录音机和钢琴等应用。 它证明了在 1980 年代 IBM XT 的 1 MB 实模式环境中，依然可以实现具有现代感的图形桌面，重新引发了人们对早期 PC 操作系统设计的兴趣。同时，由于作者借助 Claude 编写底层汇编代码，它也引发了关于 AI 辅助编程的热烈讨论。 Os8088 运行在实模式下，使用 20 位分段寻址、总容量 1 MB 的地址空间，并已在真实硬件上验证可运行。当前版本支持 FAT12/FAT16 软盘、移植应用和游戏、Sound Blaster 声卡，作者表示硬盘支持即将到来。

hackernews · jggonz · 8月8日 23:37 · [社区讨论](https://news.ycombinator.com/item?id=49226923)

**背景**: IBM PC/XT（型号 5160，1983 年发布）是以 Intel 8088 CPU 为核心的早期 IBM 个人电脑。在实模式下，x86 处理器使用 20 位分段地址空间，总共只能寻址 1 MB 内存，并可直接访问硬件；因此不用 C 语言和运行时库、纯用汇编编写操作系统难度极高。该项目也让人联想到 Visi On——一个早于 Macintosh 的 IBM PC 商用图形界面。作者借助大语言模型生成汇编代码，使这个项目既是复古计算成就，也是 AI 辅助编程的一个典型样本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Real_mode">Real mode - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/IBM_XT">IBM XT</a></li>
<li><a href="https://os8088.com/download/">Download os8088 -- 360KB and 1.44MB Boot Floppies</a></li>

</ul>
</details>

**社区讨论**: 评论者提到了 Visi On 等历史先例，并调侃说这才是 IBM 本可以推出的系统；有人打趣道这更像是“手写提示词”而非“手写代码”，还有人指出 HN 上大家一边用 AI 写代码一边贬低 AI 生成项目的矛盾。作者本人也补充了技术细节，还有评论认为在 System 1 风格桌面上跑带斜面按钮的扫雷看起来非常“赛博诡异”，但又令人着迷。

**标签**: `#retrocomputing`, `#operating-systems`, `#assembly`, `#AI-assisted-coding`, `#IBM-PC`

---

<a id="item-5"></a>
## [Shopify 用 MySQL 取代 Redis 做库存预留并成功扩展](https://shopify.engineering/scaling-inventory-reservations) ⭐️ 8.0/10

Shopify 用 MySQL 取代了 Redis 来做库存预留，采用“每个可售单元一行”的架构，并将每个商品/地点的行数上限设为 1000 行。这一改动让预留操作无需额外维护 Redis 集群即可扩展。 这个案例很重要，因为它展示了一家大型电商平台在关键的高并发操作上从 Redis 迁移到 MySQL，挑战了“必须用 Redis”的惯性思维。它还证明了一种更简单的架构在闪购等场景下也能避免超卖并实现扩展。 该方案为每个可售单元建立一行而不是用数量列，预留时在一个事务内移动行。为避免高数量商品需要扫描几十万行，Shopify 维护一个每个商品/地点最多 1000 行的有界行池，并通过补充流程来补满。

hackernews · adletbalzhanov · 8月8日 22:32 · [社区讨论](https://news.ycombinator.com/item?id=49226536)

**背景**: 库存预留是指在结账时暂时把库存锁定给某个顾客，避免两个买家同时买到最后一件商品。Redis 因速度快常被用来实现这种计数器，但也引入了额外的一套分布式系统。Shopify 的做法改用 MySQL 的事务性行锁，说明设计良好的关系型表结构也能应对闪购级别的高并发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/evan-king-40072280_there-is-no-better-way-to-learn-system-design-activity-7487535757910306817-HWZL">Shopify 's Inventory Reservation System at Scale | LinkedIn</a></li>
<li><a href="https://dasroot.net/posts/2026/06/replacing-redis-mysql-scaling-inventory-reservations-skip-locked/">Replacing Redis with MySQL: Scaling Inventory Reservations ...</a></li>
<li><a href="https://ecommercefastlane.com/ar/we-replaced-redis-with-mysql-for-inventory-reservations-and-it-scaled-2026-shopify/">We Replaced Redis With MySQL For Inventory Reservations —and It...</a></li>

</ul>
</details>

**社区讨论**: 评论者对这篇博客的质量持怀疑态度，有人直言“明显是 LLM 写的”，并表示这影响了他们对 Shopify 工程师的信心。还有一些评论讨论了使用持久化工作流或更简单预留方案的替代设计，另有人抱怨 Shopify 的“Shop”物流追踪应用会分享数据。整体上，讨论既包含技术批评，也包含对内容真实性的担忧。

**标签**: `#MySQL`, `#Redis`, `#scaling`, `#inventory`, `#architecture`

---

<a id="item-6"></a>
## [亚马逊得州 7.65GW 燃气电厂或成美国最大碳排放源](https://www.tomshardware.com/tech-industry/data-centers/amazons-new-7-65gw-texas-ai-data-center-power-plant-could-become-the-largest-source-of-co2-pollution-in-the-us-custom-35-turbine-gas-plant-authorized-to-emit-33-million-tons-of-annual-greenhouse-gases) ⭐️ 8.0/10

亚马逊正在得克萨斯州建设一座 7.65GW 的天然气发电厂，为新的 AI 数据中心供电，其许可允许每年排放高达 3300 万吨二氧化碳。这可能使其成为美国最大的二氧化碳污染源。 这突显了 AI 基础设施在空前规模上的巨大能源需求和环境足迹。同时也开创了一个令人担忧的先例：科技巨头可能依赖化石燃料来满足 AI 的电力需求，从而可能削弱气候承诺。 该电厂将使用 35 台定制燃气轮机，发电能力高达 7.65GW。许可允许每年排放 3300 万吨二氧化碳，超过许多州全年的排放总量。

rss · Tom's Hardware · 8月9日 12:40

**背景**: 随着 AI 工作负载增长，数据中心需要大量电力，导致企业自建专用发电厂。天然气是化石燃料，燃烧时会产生大量二氧化碳。该项目反映了 AI 进步与环境可持续性之间的紧张关系。

**标签**: `#AI infrastructure`, `#environmental impact`, `#data centers`, `#energy`, `#sustainability`

---

<a id="item-7"></a>
## [苹果测试中国长鑫存储内存芯片，用于 iPhone 和 MacBook](https://finance.yahoo.com/technology/articles/apple-tests-chinas-cxmt-memory-120655649.html) ⭐️ 8.0/10

据《华尔街日报》报道，苹果正在测试中国长鑫存储（CXMT）的 DRAM 芯片，考虑在未来的 iPhone 和 MacBook 中使用。这标志着苹果首次评估中国供应商为其核心设备提供内存芯片。 如果苹果采用长鑫存储的内存，将标志着全球半导体供应链的重大转变，可能减少苹果对三星和 SK 海力士的依赖。这也具有地缘政治意义，在美国出口管制背景下可能有助于中国内存产业的合法化。 长鑫存储是中国最大的 DRAM 制造商，全球第四大，生产 LPDDR4、DDR4 以及更新的 DDR5 内存。据称测试仍处于早期阶段，大规模采用面临质量、良率和监管方面的挑战。

openbb · AAPL · 8月9日 12:06

**背景**: 长鑫存储是一家成立于 2016 年的中国半导体公司，专注于 DRAM 芯片的设计、制造与销售，产品应用于手机、PC、服务器等。截至 2025 至 2026 年初，其每季度产量约 72 万片晶圆，并计划通过 IPO 募集资金用于先进 DRAM 研发。苹果目前的内存主要供应商为三星、SK 海力士和美光；在中美科技紧张局势下引入中国供应商将是一项显著的供应链多元化举措。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ChangXin_Memory_Technologies">ChangXin Memory Technologies</a></li>
<li><a href="https://www.cxmt.com/en/">ABOUT CXMT - CXMT</a></li>

</ul>
</details>

**标签**: `#hardware`, `#supply-chain`, `#Apple`, `#semiconductors`, `#memory`

---

<a id="item-8"></a>
## [Moonshot AI 2.8 万亿参数模型登顶重大编程基准](https://finance.yahoo.com/technology/ai/articles/moonshot-ais-2-8-trillion-052000925.html) ⭐️ 8.0/10

根据近期新闻，Moonshot AI 的 2.8 万亿参数大语言模型成为首个在重大编程基准测试中登顶的中国模型。这一成就标志着全球 AI 竞赛中的一个重要里程碑。 这一里程碑表明，中国 AI 模型现在能够在严格的编程评估中与西方同行竞争，不仅在规模上，而且在实用能力上。它可能会改变对中国 AI 实力的看法，并加剧中美 AI 实验室之间的竞争态势。 该模型拥有 2.8 万亿参数，使其成为迄今报道的最大型语言模型之一。现有摘要未披露具体的编程基准和确切评估分数，模型的正式名称也未得到确认。

openbb · AAPL · 8月9日 05:20

**背景**: Moonshot AI 是一家总部位于北京的人工智能公司，由清华大学校友杨植麟、周昕宇和吴宇鑫于 2023 年 3 月创立，被视为中国‘AI Tigers’之一。大型语言模型通常通过 SWE-bench 和 LiveCodeBench 等编程基准来评估，这些基准考验其解决真实编程问题的能力。参数数量是衡量模型规模的常用指标，但效率和训练数据质量同样重要。这一成就凸显了中国 AI 实验室在追赶美国同行方面的快速进展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Moonshot_AI">Moonshot AI - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI`, `#coding benchmark`, `#Moonshot AI`, `#large language models`, `#China`

---