---
layout: default
title: "Horizon Summary: 2026-07-11 (ZH)"
date: 2026-07-11
lang: zh
---

> 从 117 条内容中筛选出 18 条重要资讯。

---

1. [中国首个全国产算力十万卡 AI 集群落成](#item-1) ⭐️ 9.0/10
2. [ClickHouse 利用 SO_REUSEPORT 和 Peering 将 PgBouncer 吞吐量提升 4 倍](#item-2) ⭐️ 8.0/10
3. [推荐在 SQLite 中使用 STRICT 表以保证数据完整性](#item-3) ⭐️ 8.0/10
4. [Colibrì概念验证仅用 25GB 内存运行 1.5TB 前沿 AI 模型](#item-4) ⭐️ 8.0/10
5. [苹果起诉 OpenAI 涉嫌窃取商业机密](#item-5) ⭐️ 7.0/10
6. [Nvidia 隐藏 GPU 热点传感器可通过内部 MODS 工具访问](#item-6) ⭐️ 7.0/10
7. [SK 海力士 CEO 预测内存短缺 2027 年达峰，将持续至 2030 年](#item-7) ⭐️ 7.0/10
8. [虚假 Go DNS 扫描工具通过 200 多个 GitHub 仓库传播恶意软件](#item-8) ⭐️ 7.0/10
9. [MoE 模型的真正价值在于路由质量，而非仅活跃参数](#item-9) ⭐️ 7.0/10
10. [四张 RTX 5060 Ti 显卡用于 Qwen3.6-27B 代码生成基准测试](#item-10) ⭐️ 7.0/10
11. [RTX 5090 与改版水冷 RTX 6000 PRO MaxQ 多功耗性能对比](#item-11) ⭐️ 7.0/10
12. [定制 CUDA 引擎在 RTX 5060 Ti 上以 50+ tok/s 运行 Qwen3-30B-A3B](#item-12) ⭐️ 7.0/10
13. [针对 536 万专利记录的 SQLite/FTS5 扩展实践教训](#item-13) ⭐️ 7.0/10
14. [Meta 自研 AI 芯片将于九月投产](#item-14) ⭐️ 7.0/10
15. [加密行业加速推进抗量子安全措施](#item-15) ⭐️ 7.0/10
16. [AI 消耗全球内存供应，苹果将付出代价？](#item-16) ⭐️ 7.0/10
17. [Airbnb 分享 Kubernetes 动态配置 Sidecar Sitar-agent 的架构](#item-17) ⭐️ 6.0/10
18. [AIC 推出配备 32 盘位 E3 SSD 的 JBOF，支持 BlueField-4 DPU 键值缓存](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [中国首个全国产算力十万卡 AI 集群落成](https://www.qbitai.com/2026/07/447902.html) ⭐️ 9.0/10

中国首个十万卡 AI 计算集群——位于郑州的曙光 8000（登峰）超级集群正式落成，该集群完全采用国产加速芯片，已支持 300 余项应用。 这一里程碑标志着中国在 AI 基础设施自主可控方面的重大进展，减少了对英伟达等外国芯片的依赖，并增强了训练大规模 AI 模型的竞争力。 该集群覆盖从 FP64 到 INT8 的全精度范围，支持多种计算任务；已跑通 300 余项应用，表明其已具备生产环境部署能力。

rss · 量子位 · 7月11日 10:07

**背景**: 十万卡 AI 集群是一种超大规模超级计算机，如 xAI 的 Colossus 使用 Nvidia H100 GPU。FP64（双精度浮点）用于高精度科学计算，INT8（8 位整数）则支持高效的 AI 推理。曙光 8000 是中国首个完全采用国产加速芯片的十万卡集群，体现了中国在半导体自主方面的持续努力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Colossus_(data_center)">Colossus (data center) - Wikipedia</a></li>
<li><a href="https://www.chinadaily.com.cn/a/202607/10/WS6a508b1da310986e2b4649a7.html">China's first homegrown 100,000-card AI supercluster goes live in Zhengzhou - Chinadaily.com.cn</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#HPC`, `#domestic chips`, `#China`, `#large-scale computing`

---

<a id="item-2"></a>
## [ClickHouse 利用 SO_REUSEPORT 和 Peering 将 PgBouncer 吞吐量提升 4 倍](https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres) ⭐️ 8.0/10

ClickHouse 详述了他们如何利用 Linux 内核的 SO_REUSEPORT 套接字选项并实现进程 peering 来协调，从而为其托管 PostgreSQL 服务将 PgBouncer 的吞吐量提升了四倍。 这种方法克服了连接池中常见的单进程瓶颈，无需架构变更即可为高流量 PostgreSQL 部署实现更高的并发性和效率。 自 Linux 3.9 起可用的 SO_REUSEPORT 允许多个 PgBouncer 进程监听同一端口，由内核分配传入连接。Peering 使进程能将查询取消等操作转发到正确的会话所有者，确保行为正确。

hackernews · saisrirampur · 7月11日 15:28 · [社区讨论](https://news.ycombinator.com/item?id=48872874)

**背景**: PgBouncer 是 PostgreSQL 的一个轻量级连接池，通常限于单个进程，存在可扩展性瓶颈。SO_REUSEPORT 是一个套接字选项，允许多个套接字绑定到同一地址和端口，由内核在它们之间负载均衡连接。进程 peering 指这些并行进程相互通信的能力，例如将查询取消请求转发到适当的后端。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/how-modern-kernels-handle-massive-traffic-use-jisan-ahmed-ghg1c">How Modern Kernels Handle Massive Traffic : the use of...</a></li>
<li><a href="https://oxnz.github.io/2016/02/04/web-dev/">Web Development | Tech Stack</a></li>

</ul>
</details>

**社区讨论**: 社区反应积极，有人推荐了 Odyssey 和 pgdog 等本身具备可扩展性的替代连接池。也有人询问 peering 是否为 PgBouncer 的内置功能且易于配置，并分享了诸如在 Kubernetes 中运行多个实例的实用变通方法。

**标签**: `#PgBouncer`, `#PostgreSQL`, `#scaling`, `#connection-pooling`, `#infrastructure`

---

<a id="item-3"></a>
## [推荐在 SQLite 中使用 STRICT 表以保证数据完整性](https://evanhahn.com/prefer-strict-tables-in-sqlite/) ⭐️ 8.0/10

一篇技术文章提倡使用 SQLite 3.37.0 引入的 STRICT 表来强制数据类型，避免模式漂移。 在数据库层面强制数据类型有助于提升数据完整性，减少因模式漂移引发的错误，尤其当 SQLite 数据库被多个应用共享或需长期可靠运行时，这至关重要。 STRICT 表通过在 CREATE TABLE 语句的表名后添加 STRICT 关键字创建，会拒绝与声明类型不匹配的值。但目前不支持 DATE 等数据类型，且转换现有表时需谨慎处理。

hackernews · ingve · 7月11日 17:33 · [社区讨论](https://news.ycombinator.com/item?id=48873940)

**背景**: SQLite 传统上采用动态类型系统，列类型仅为建议，任何类型的数据都可存入任意列。这种灵活性可能导致模式漂移——即预期模式与数据逐渐偏离。为满足对严格数据验证的需求，SQLite 开发者从 2021 年 11 月发布的 3.37.0 版本开始引入 STRICT 表功能，允许按表启用严格类型强制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sqlite.org/stricttables.html">STRICT Tables</a></li>
<li><a href="https://antonz.org/sqlite-strict-tables/">STRICT tables in SQLite</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认为严格类型有益，一些人呼吁将 STRICT 设为默认模式。他们指出 STRICT 表缺少 DATE 类型是一个缺陷。也有人强调 SQLite 的灵活性对嵌入式单应用场景很有用，但一致认为严格类型能防止数据库演变的隐蔽错误。

**标签**: `#SQLite`, `#database`, `#schema`, `#data integrity`, `#strict typing`

---

<a id="item-4"></a>
## [Colibrì概念验证仅用 25GB 内存运行 1.5TB 前沿 AI 模型](https://www.tomshardware.com/tech-industry/artificial-intelligence/colibri-proof-of-concept-gains-frontier-level-1-5-tb-ai-model-novel-approach-runs-on-only-25gb-of-ram-and-shows-promise-for-local-ai-setups) ⭐️ 8.0/10

名为 Colibrì的概念验证展示了在仅配备 25GB 内存和普通 CPU 的系统上运行 1.5TB 前沿 AI 模型的能力，其通过从存储中分片加载模型来实现。 这一突破可能使大型 AI 模型能在消费级硬件上运行，实现隐私保护、离线使用和低成本部署，从而可能重塑边缘 AI 和个人助理领域。 该技术可能通过从磁盘以小批量方式流式传输模型权重，实现纯 CPU 推理，但作为概念验证，其性能和可靠性可能存在局限。

rss · Tom's Hardware · 7月11日 11:30

**背景**: 前沿 AI 模型通常超过 1TB，需要多块大显存高端 GPU 进行推理。Colibrì利用速度较慢但容量充足的系统内存和存储进行流式加载，类似于内存映射文件或数据库分页技术，从而将强大模型带入无需昂贵加速器的普通硬件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/colibri-proof-of-concept-gains-frontier-level-1-5-tb-ai-model-novel-approach-runs-on-only-25gb-of-ram-and-shows-promise-for-local-ai-setups">Colibrì proof - of - concept gains frontier-level 1.5-TB AI model — novel...</a></li>
<li><a href="https://savedelete.com/news/colibri-ai-model-25gb-ram/">Colibrì proof - of - concept runs frontier-level 1.5-TB AI — SaveDelete</a></li>

</ul>
</details>

**标签**: `#AI`, `#model compression`, `#local AI`, `#efficient inference`, `#proof-of-concept`

---

<a id="item-5"></a>
## [苹果起诉 OpenAI 涉嫌窃取商业机密](https://www.infoq.cn/article/Rzh9umgPl90MgGolBcWm?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

苹果对 OpenAI 提起诉讼，指控其盗用与人工智能相关的商业机密。 该诉讼凸显了人工智能行业日益紧张的知识产权局势，可能为专有数据和训练方法的处理树立先例。 这份长达 41 页的法律文件表明指控范围广泛，但涉嫌的商业机密具体细节尚未公开。

rss · InfoQ 中国 · 7月11日 17:00

**背景**: 商业机密是能带来竞争优势的保密商业信息，例如专有算法或训练技术。大型科技公司严密保护此类机密，而印度的开源 AI 运动（如 IndicTrans2 项目）则提供了协作开发的替代模式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/analytics-india-magazine_indias-open-source-ai-ecosystem-is-exploding-activity-7401965936100098048-y9Cb">India 's AI Ecosystem Booms with IndicTrans2, IndicBERT... | LinkedIn</a></li>

</ul>
</details>

**社区讨论**: 网友调侃道：“早知道就等印度开源了”，反映出对专有 AI 的怀疑，并凸显了开源替代方案的吸引力。

**标签**: `#Apple`, `#OpenAI`, `#lawsuit`, `#trade secrets`, `#AI`

---

<a id="item-6"></a>
## [Nvidia 隐藏 GPU 热点传感器可通过内部 MODS 工具访问](https://www.tomshardware.com/pc-components/gpus/hotspot-temperature-sensor-on-nvidias-blackwell-gaming-gpus-is-still-accessible-if-you-have-access-to-nvidias-internal-mods-tool-nvidia-rtx-5070-ti-caught-throttling-at-107-c-over-poor-tim-application) ⭐️ 7.0/10

Nvidia 在 RTX 50 系列 GPU 中隐藏了热点温度传感器，但该传感器仍可通过 Nvidia 内部模块化诊断软件(MODS)访问。来自 RTX 5070 Ti 的数据显示，因导热界面材料(TIM)涂布不佳，显卡在 107°C 时出现热节流。 这一发现引发了对 Nvidia 向消费者隐藏关键温度数据决策的透明度担忧，可能掩盖了过热问题。这可能影响 RTX 50 系列 GPU 用户的超频和寿命监控。 热点传感器只能通过非公开的专有 MODS 工具读取，限制了广泛验证。节流事件与 TIM 涂布不佳直接相关，表明存在制造或装配质量问题。

rss · Tom's Hardware · 7月11日 16:18

**背景**: Nvidia 的 MODS(模块化诊断软件)是用于 GPU 内存和硬件诊断的内部工具，通常仅供板卡合作伙伴和测试实验室使用。导热界面材料(TIM)，如导热膏，填充 GPU 芯片与散热器之间的微观缝隙以改善热传递。热点温度是 GPU 芯片上的最高温度，监控它有助于识别散热缺陷。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://repair.wiki/w/Nvidia_GPU_Memory_Testing_Guide">Nvidia GPU Memory Testing Guide - Repair Wiki</a></li>
<li><a href="https://rkblog.dev/posts/pc-hardware/nvidia-modular-diagnostic-software-mods/">Nvidia Modular diagnostic software - MODS</a></li>

</ul>
</details>

**标签**: `#Nvidia`, `#RTX 50`, `#GPU throttling`, `#thermal management`, `#hardware monitoring`

---

<a id="item-7"></a>
## [SK 海力士 CEO 预测内存短缺 2027 年达峰，将持续至 2030 年](https://www.tomshardware.com/pc-components/dram/sk-hynix-says-2027-will-be-the-worst-year-for-memory-shortage-forecasts-crunch-to-last-until-2030-ceo-shares-grim-outlook-on-the-day-sk-hynix-gets-listed-on-nasdaq) ⭐️ 7.0/10

SK 海力士 CEO 郭鲁正宣布，全球内存芯片短缺将加剧并在 2027 年达到顶峰，供应紧张预计持续到 2030 年。 这一预警意味着内存芯片将长期面临高价格和供应限制，影响消费电子、数据中心等多个领域，并可能促使行业整合或加速产能投资。 郭鲁正明确将 2027 年定为短缺最严重的一年，2030 年后才会缓解。这一表态恰逢 SK 海力士在纳斯达克上市当日，凸显了其市场信心。

rss · Tom's Hardware · 7月11日 13:00

**背景**: 半导体行业经常出现周期性的供需失衡。SK 海力士是全球最大的内存芯片制造商之一，与三星、美光并列。近年全球疫情和贸易摩擦已严重挤压芯片供应链。该预测表明，来自 AI、云计算和 5G 等领域的结构性需求将在未来多年超过产能。

**标签**: `#memory shortage`, `#semiconductor industry`, `#supply chain`, `#RAM`, `#SK Hynix`

---

<a id="item-8"></a>
## [虚假 Go DNS 扫描工具通过 200 多个 GitHub 仓库传播恶意软件](https://www.tomshardware.com/tech-industry/cyber-security/fake-go-dns-scanner-published-700-malicious-versions-before-researchers-traced-it-to-222-github-repos) ⭐️ 7.0/10

一场伪装成 Go DNS 扫描工具的恶意软件活动自 2024 年 1 月 24 日以来活跃，通过 200 多个 GitHub 仓库传播，并发布了 700 多个恶意模块，累计超过 1,200 个版本。 这是一次针对 Go 生态系统的供应链攻击，可能危害将这些恶意模块集成到项目中的开发者，导致大规模安全漏洞。 攻击涉及一个假冒的“Go DNS scanner”软件包；该活动被称为“Operation Muck and Load”，自今年 1 月开始，首个版本于 1 月 24 日发布，已累计超过 1,200 个版本。

rss · Tom's Hardware · 7月11日 11:00

**背景**: Go 生态系统依赖于通过 GitHub 等仓库共享的模块。在供应链攻击中，恶意行为者将有害代码注入看似合法的软件包，进而感染集成这些软件包的项目。

**标签**: `#cybersecurity`, `#Go`, `#supply-chain-attack`, `#malware`, `#GitHub`

---

<a id="item-9"></a>
## [MoE 模型的真正价值在于路由质量，而非仅活跃参数](https://www.reddit.com/r/LocalLLaMA/comments/1utkqfg/why_are_moe_models_so_belittled/) ⭐️ 7.0/10

一位 Reddit 用户质疑了关于 MoE 模型仅根据活跃参数量评价其能力的常见认知，认为路由器的有效性在决定其真实能力方面起着关键作用。 这个观点很重要，因为它指出了评估 MoE 模型时可能存在的误判，这可能影响模型选择和研究方向，促使人们关注路由器设计。 MoE 模型通过路由器每词元仅激活部分参数，但总参数量存储了专门知识；路由器的质量决定了这些知识被利用的效率。

reddit · r/LocalLLaMA · /u/ParaboloidalCrest · 7月11日 13:52

**背景**: MoE（混合专家）是一种神经网络架构，包含多个专门化的子模型（专家）和一个路由器，路由器动态选择每个输入词元应激活哪些专家。这使得模型能够扩展到数十亿参数，同时保持每词元的计算成本相对较低，因为每次只有一部分参数被激活。对 MoE 模型的一个常见批评是，它们常依据活跃参数量进行基准测试，忽略了所有专家中存储的广泛知识，以及路由机制在有效利用这些知识方面的关键作用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mixture-of-experts">A Visual Guide to Mixture of Experts ( MoE )</a></li>
<li><a href="https://silkeplessers.github.io/genai/transformers/2025/12/18/Mixture_of_Experts.html">Introduction to Mixture - of - Experts | Architecting the future</a></li>

</ul>
</details>

**标签**: `#Mixture of Experts`, `#MoE`, `#Large Language Models`, `#Model Evaluation`, `#LocalLLaMA`

---

<a id="item-10"></a>
## [四张 RTX 5060 Ti 显卡用于 Qwen3.6-27B 代码生成基准测试](https://www.reddit.com/r/LocalLLaMA/comments/1uturng/i_benched_quad_5060tis_for_code_generation_with/) ⭐️ 7.0/10

一位用户对四块 NVIDIA RTX 5060 Ti 显卡运行 Qwen3.6-27B 模型进行代码生成基准测试，表明该配置在预算友好价位下性能出色。 这为注重成本的开发者提供了实用的硬件方案，以约 3000 美元的成本即可享受顶尖的代码生成能力，有望扩大在独立开发者和小型企业中的普及。 该配置利用 PCIe 分叉为每张卡提供 x4 通道，以 Q8 量化运行 Qwen3.6-27B，配合 FP16 KV 缓存和推测解码（MTP），四卡总空闲功耗仅 14–16W。

reddit · r/LocalLLaMA · /u/starkruzr · 7月11日 20:28

**背景**: Qwen3.6-27B 是阿里巴巴于 2026 年 4 月发布的 270 亿参数稠密语言模型，代码生成能力强大。运行大模型并保持完整上下文和高精度需要大量显存，通常需多显卡配置。RTX 5060 Ti 是一款配备 16GB 显存的中端 Blackwell 显卡，四卡并行成为内存密集型推理的可行方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/unsloth/Qwen3.6-27B">unsloth/ Qwen 3 . 6 - 27 B · Hugging Face</a></li>
<li><a href="https://medium.com/@antalpha.ai/qwen3-6-27b-the-27-billion-parameter-model-beating-397-billion-parameter-giants-ce7f13f8283a">Qwen 3 . 6 – 27 B : The 27-Billion Parameter Model Beating... | Medium</a></li>

</ul>
</details>

**标签**: `#LLM benchmark`, `#code generation`, `#Qwen`, `#LocalLLaMA`, `#hardware`

---

<a id="item-11"></a>
## [RTX 5090 与改版水冷 RTX 6000 PRO MaxQ 多功耗性能对比](https://www.reddit.com/r/LocalLLaMA/comments/1utvbey/performance_comparison_on_full_compute/) ⭐️ 7.0/10

一位用户对 RTX 6000 PRO MaxQ 进行 shunt mod 改造使其功耗上限提升至 600W，并加装水冷，然后与 RTX 5090 在 300–600W 不同功耗下进行 AI 图像生成（Anima）和大语言模型推理的性能对比测试。 此项测试为本地大模型及 AI 爱好者展示了通过极限硬件改造能获得多大性能提升，并探讨了在计算密集型任务中 RTX 6000 PRO 是否可作为 RTX 5090 的替代方案，体现了专业级 GPU 的体质筛选与功耗管理的潜力。 shunt mod 通过焊接一颗 R002 电阻让显卡误认为功耗减半，从而解锁 600W 上限。在 Anima 测试中，600W 的 6000 PRO MaxQ 比同功耗的 5090 快 12.8%。测试均进行了降压超频，并对比了 300W、400W、475W 等不同功耗。租用的 WS 版使用不同 PyTorch 版本；LLM 测试仅在本地 GPU 上进行。

reddit · r/LocalLLaMA · /u/panchovix · 7月11日 20:49

**背景**: shunt mod（分流改造）是通过增加电阻改变电流检测电路，从而欺骗 GPU 突破功耗限制的硬件修改，常用于绕过厂商的功耗墙。MaxQ 通常指低功耗高效能版本显卡，但此卡被强行拉升至两倍额定功耗。水冷散热用于压制因功耗大增而产生的巨大热量，而特挑核心体质使其能在高功耗下维持高频运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tomshardware.com/pc-components/gpus/geforce-rtx-5090-laptop-gpu-shunt-mod-increases-performance-by-up-to-40-percent-175-tgp-boosted-to-250w-to-unlock-extra-performance">GeForce RTX 5090 Laptop GPU shunt mod ... | Tom's Hardware</a></li>
<li><a href="https://www.pcworld.com/article/2854038/this-nvidia-rtx-laptop-mod-unlocks-amazing-performance-dont-do-it.html">This Nvidia RTX laptop mod unlocks amazing performance. | PCWorld</a></li>
<li><a href="https://www.nvidia.com/en-us/geforce/gaming-laptops/max-q-technologies/">Max - Q Technologies for Laptops | NVIDIA</a></li>

</ul>
</details>

**标签**: `#GPU benchmarking`, `#local LLM`, `#NVIDIA`, `#hardware modding`, `#AI performance`

---

<a id="item-12"></a>
## [定制 CUDA 引擎在 RTX 5060 Ti 上以 50+ tok/s 运行 Qwen3-30B-A3B](https://www.reddit.com/r/LocalLLaMA/comments/1utefpr/running_qwen3_30b_a3b_at_50_toks_on_rtx_5060_ti/) ⭐️ 7.0/10

开发者创建了一个名为“garlic-inference”的定制 CUDA 和 C++推理引擎，在配备 16 GB VRAM 的 RTX 5060 Ti 上使用 float8 量化运行 Qwen3-30B-A3B 模型，速度达 50 至 54 tokens/秒，比流行的 llama.cpp 框架快 50%。 该成果表明，通过优化的推理软件，大型混合专家模型可以在消费级 GPU 上高效运行，使个人和小型企业更容易获得私密、低成本且节能的本地 AI 推理能力。 加速效果源于融合了 NeurIPS、ICML 和 EuroSys 最新论文中的先进技术，该引擎已在 GitHub 上开源。Qwen3-30B-A3B 是一个混合专家模型，总参数 305 亿，但每次仅激活 33 亿，包含 128 个专家（每个 token 激活 8 个），支持 13.1 万 token 上下文。

reddit · r/LocalLLaMA · /u/Azazelionide · 7月11日 08:29

**背景**: Qwen3-30B-A3B 是阿里 Qwen 系列的大型语言模型，采用混合专家架构，每个 token 仅激活部分参数以降低计算需求。Float8 量化进一步压缩模型，减少内存占用并加快推理速度。llama.cpp 是一个广泛使用的开源框架，用于在 CPU 和 GPU 上运行大语言模型，但可能未充分利用特定硬件的优化潜力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://langdb.ai/app/models/qwen3-30b-a3b/">qwen 3 - 30 b - a 3 b by deepinfra | AI Model Pricing... | LangDB</a></li>
<li><a href="https://learn-pytorch.oneoffcoder.com/quantization.html">8 . Quantization — PyTorch, No Tears 0.0.1 documentation</a></li>

</ul>
</details>

**标签**: `#local-llm`, `#inference-optimization`, `#qwen`, `#cuda`, `#moe`

---

<a id="item-13"></a>
## [针对 536 万专利记录的 SQLite/FTS5 扩展实践教训](https://www.reddit.com/r/LocalLLaMA/comments/1utl6r5/followup_what_i_learned_scaling_a_sqlitefts5/) ⭐️ 7.0/10

一篇后续文章分享了将 SQLite/FTS5 专利数据库从 350 万条记录扩展到 536 万条记录的具体性能优化经验。主要发现包括批量导入后运行 ANALYZE 的关键作用、宽行 UPDATE 的高昂代价，以及在大数据集上 BM25 查询中 AND 优于 OR 的策略。 这些可操作的经验直接惠及构建本地 LLM 数据管道和管理大型 SQLite 数据库的开发人员，提供了切实可行的技术，可以大幅提升查询速度和效率。 ANALYZE 将 1.08 亿行引用表上的相关 EXISTS 查询从 34 秒降至 0.16 秒。宽行（平均 19KB）使得 UPDATE 重写整个 119GB 的表，因此建议使用侧表加 JOIN。在线数据库上的 BM25 搜索时间：AND 短语 0.27 秒，AND 所有词 0.48 秒，OR 0.70 秒。

reddit · r/LocalLLaMA · /u/Impressive_Tower_550 · 7月11日 14:11

**背景**: SQLite 是一款广泛用于本地应用的轻量级嵌入式数据库。FTS5 是其全文搜索扩展，支持高级排名算法如 BM25，该算法平衡了词频和文档长度归一化。ANALYZE 命令收集表和索引的统计信息，使查询规划器能够选择高效的执行路径。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sqlite.org/lang_analyze.html">ANALYZE</a></li>
<li><a href="https://pub.aimind.so/understanding-the-bm25-ranking-algorithm-19f6d45c6ce">Understanding the BM 25 Ranking Algorithm | by Everton... | AI Mind</a></li>

</ul>
</details>

**标签**: `#sqlite`, `#fts5`, `#full-text-search`, `#performance-tuning`, `#data-engineering`

---

<a id="item-14"></a>
## [Meta 自研 AI 芯片将于九月投产](https://finance.yahoo.com/technology/ai/articles/mark-zuckerberg-turning-meta-bigger-030100431.html) ⭐️ 7.0/10

Meta 最新的自研 AI 芯片将于 2025 年 9 月投产，这标志着该公司在为 AI 工作负载设计自有芯片方面迈出了重要一步。 此举减少了 Meta 对 Nvidia 等外部芯片供应商的依赖，使公司能够更好地控制其 AI 基础设施，并有可能在规模化时降低成本。 该芯片预计将部署在 Meta 的数据中心用于 AI 训练和推理，但具体的技术规格尚未公开。

openbb · AAPL · 7月11日 03:01

**背景**: Meta 一直在扩展其硬件能力以支持庞大的 AI 投资，加入了谷歌和亚马逊等科技巨头自研芯片的行列。Meta 此前推出的 AI 加速器系列名为 MTIA，主要面向推理任务，旨在与现有的商用 GPU 互补。

**标签**: `#AI`, `#chips`, `#Meta`, `#hardware`, `#semiconductors`

---

<a id="item-15"></a>
## [加密行业加速推进抗量子安全措施](https://finance.yahoo.com/markets/crypto/articles/crypto-industry-steps-quantum-security-130000468.html) ⭐️ 7.0/10

加密货币行业正加大力度部署抗量子密码算法，以应对量子计算带来的日益增长的风险，并遵循美国国家标准与技术研究院（NIST）最新发布的后量子密码学标准。 这至关重要，因为量子计算机利用 Shor 算法可能破解保障区块链安全的公钥加密，威胁数字资产；主动迁移至量子安全系统对确保长期韧性和信任不可或缺。 NIST 首批三项后量子标准（用于密钥建立的 CRYSTALS-Kyber，以及用于数字签名的 CRYSTALS-Dilithium 和 SPHINCS+）正被区块链项目探索采用，但迁移过程复杂，且需防范‘先收集后解密’的长期威胁。

openbb · AAPL · 7月11日 13:00

**背景**: 后量子密码学旨在开发能抵御量子攻击的算法。现有公钥系统依赖的大数分解和离散对数难题，可被量子 Shor 算法高效破解。尽管对称密码受影响较小，但‘先收集后解密’的风险迫使业界及时迁移，NIST 等机构已推出相关标准以推动升级。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography</a></li>
<li><a href="https://www.nist.gov/pqc">Now is the time to migrate to new post- quantum encryp</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#cryptography`, `#cryptocurrency`, `#security`, `#encryption`

---

<a id="item-16"></a>
## [AI 消耗全球内存供应，苹果将付出代价？](https://finance.yahoo.com/technology/ai/articles/ai-consuming-world-memory-supply-133942301.html) ⭐️ 7.0/10

文章指出人工智能对存储芯片的巨大需求正在导致全球供应紧张和价格上涨，并分析了这可能如何影响苹果。 存储短缺可能推高消费电子品的成本，拖慢 AI 创新，并威胁依赖廉价内存的苹果等大公司的盈利能力，影响其 iPhone、Mac 及 AI 服务。 关键因素包括 AI 加速器对高带宽内存（HBM）的需求激增，三星、SK 海力士等供应商的产能有限，以及苹果在设备和终端 AI 处理中对 DRAM 和 NAND 的依赖。

openbb · AAPL · 7月11日 15:04

**背景**: AI 大模型训练和推理需要大量高速内存，推动了 HBM 的需求。苹果自研芯片采用统一内存架构，依赖 LPDDR DRAM。供应紧张可能迫使苹果提高硬件价格或承受较低利润率，并可能阻碍其在设备端运行 AI 模型的努力。

**标签**: `#AI`, `#memory`, `#Apple`, `#supply chain`, `#hardware`

---

<a id="item-17"></a>
## [Airbnb 分享 Kubernetes 动态配置 Sidecar Sitar-agent 的架构](https://www.infoq.cn/article/fO5byVPuZwwlBPosijBV?utm_source=rss&utm_medium=article) ⭐️ 6.0/10

Airbnb 发布了 Sitar-agent 的架构细节，这是一个 Kubernetes sidecar，无需重新部署服务即可实现动态配置更新。 该方法减少了微服务的部署摩擦和停机时间，为大规模 Kubernetes 环境中的动态配置管理提供了可复用的模式。 Sitar-agent 以数秒为间隔（并加入抖动）持续轮询中心化的 Sitar 服务，以获取已订阅组的配置更改。

rss · InfoQ 中国 · 7月11日 09:00

**背景**: Sidecar 是在同一 Kubernetes Pod 中与应用程序容器并行的辅助容器，通常提供共享功能。动态配置系统允许运维人员在不重启服务的情况下修改应用行为。Airbnb 内部的 Sitar 配置系统负责管理这些配置，而 Sitar-agent 作为 sidecar 将配置应用到运行中的服务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/airbnb-engineering/sitar-agent-building-a-reliable-dynamic-configuration-sidecar-at-scale-b7e00c152068">Sitar - agent : Building a reliable dynamic configuration sidecar... | Medium</a></li>
<li><a href="https://www.infoq.com/news/2026/07/sitar-agent-sidecar-config/">Airbnb Shares Architecture behind Sitar - Agent Dynamic... - InfoQ</a></li>

</ul>
</details>

**标签**: `#Kubernetes`, `#sidecar`, `#dynamic configuration`, `#Airbnb`, `#microservices`

---

<a id="item-18"></a>
## [AIC 推出配备 32 盘位 E3 SSD 的 JBOF，支持 BlueField-4 DPU 键值缓存](https://www.servethehome.com/aic-gets-flashy-with-32-ssd-bay-jbof-server-for-key-value-caching/) ⭐️ 6.0/10

AIC 展示了型号为 F2032-01-G6 的 2U JBOF 服务器，可容纳 32 个 E3 SSD，当与 NVIDIA BlueField-4 DPU 配对时，可用作键值缓存设备。 该产品通过利用 DPU 卸载来降低延迟并提高效率，满足了数据中心对高性能缓存日益增长的需求，尤其是在 AI 和大规模应用领域。 该系统目标定位于未来的 NVIDIA Rubin Vera GPU 架构，但未披露具体的性能数据或上市日期。采用 E3 SSD 表明其注重高密度、低功耗存储。

rss · ServeTheHome · 7月11日 17:00

**背景**: JBOF 是“Just a Bunch of Flash”的缩写，指一种容纳 SSD 的存储机箱，连接到计算元件进行处理。E3 SSD 遵循 EDSFF E3 外形规格，这是一种新的企业级 SSD 标准，在紧凑的设计中提供高性能和大容量。BlueField-4 是 NVIDIA 的下一代数据处理单元，继 BlueField-3 之后，旨在从 CPU 和 GPU 卸载网络、存储和安全任务。“Rubin Vera 时代”指的是 NVIDIA 未来的 GPU（Rubin）和 CPU（Vera）架构，预计将为下一代 AI 工作负载提供动力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/anschel_boom-nvidia-just-unleashed-bluefield-activity-7389201582661373952-dLBX">Boom! NVIDIA just unleashed BlueField - 4 — a DPU delivering...</a></li>

</ul>
</details>

**标签**: `#hardware`, `#storage`, `#key-value-caching`, `#DPU`, `#server`

---