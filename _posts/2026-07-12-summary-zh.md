---
layout: default
title: "Horizon Summary: 2026-07-12 (ZH)"
date: 2026-07-12
lang: zh
---

> 从 108 条内容中筛选出 15 条重要资讯。

---

1. [Chromium 148 使 Math.tanh 成为操作系统指纹](#item-1) ⭐️ 8.0/10
2. [Claude Code 预提示消耗 33k tokens，OpenCode 仅 7k](#item-2) ⭐️ 8.0/10
3. [通过现代编程代理构建新旧应用](#item-3) ⭐️ 8.0/10
4. [George Hotz 认为前沿 AI 实验室被过度炒作且估值过高](#item-4) ⭐️ 8.0/10
5. [Hunyuan3D 模型 MLX 移植版实现苹果设备上快速本地图像转 3D](#item-5) ⭐️ 8.0/10
6. [苹果起诉 OpenAI 窃取商业机密，称涉事‘各层级’](#item-6) ⭐️ 8.0/10
7. [面向 llama.cpp GGUF 模型的交互式雅可比透镜可视化与实时操控工具](#item-7) ⭐️ 8.0/10
8. [在 Qwen3-4B 上跨 7 个数据集评估 Anthropic J-Space 幻觉检测](#item-8) ⭐️ 8.0/10
9. [LARP：严肃创始人的营收基础设施](#item-9) ⭐️ 7.0/10
10. [博客文章类比电影 CGI 转向与编程中 LLM 的采用](#item-10) ⭐️ 7.0/10
11. [英伟达 RTX Spark 真机亮相 Bilibili World，运行 1200 亿参数大模型](#item-11) ⭐️ 7.0/10
12. [AICon 深圳分享 Qwen 模型线性注意力高性能优化实践](#item-12) ⭐️ 7.0/10
13. [爱尔兰数据中心耗电达全国 23%](#item-13) ⭐️ 7.0/10
14. [具身数据行业融资 44.7 亿，近百玩家涌入，商业化待解](#item-14) ⭐️ 6.0/10
15. [FCC 批准轨道太空镜，首批测试卫星今年发射](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Chromium 148 使 Math.tanh 成为操作系统指纹](https://scrapfly.dev/posts/browser-math-os-fingerprint/) ⭐️ 8.0/10

在 Chromium 148 版本中，Math.tanh 函数的实现因操作系统不同而产生细微差异，使得网站能够据此识别底层操作系统。 这个新的指纹识别途径使得追踪服务和反机器人系统能够在用户代理伪装的情况下依然识别操作系统，进一步侵蚀浏览器隐私并增加规避检测的难度。 指纹基于不同系统 libm 库中 Math.tanh 输出的舍入差异；它还可能泄露浏览器版本范围。最近的 glibc 版本使用了正确舍入的 tanh 函数，其输出值与旧版本不同，因此该指纹并非固定不变。

hackernews · joahnn_s · 7月12日 21:12 · [社区讨论](https://news.ycombinator.com/item?id=48884853)

**背景**: 浏览器指纹采集各种细微的配置差异。Math.tanh 是计算双曲正切的 JavaScript 函数，其计算通常委托给操作系统的数学库。不同的操作系统分发版使用不同的数学库，精度存在差异，导致最低有效位上有微小差异。这项技术能够揭示用户的真实操作系统，即使用户试图隐藏。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://scrapfly.dev/posts/browser-math-os-fingerprint/">Your Browser Does Math Differently on Every OS , and Anti-Bot...</a></li>
<li><a href="https://news.ycombinator.com/item?id=48884853">Since Chronium 148, Math . tanh is now fingerprintable... | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 评论者指出该技术还能用于浏览器版本指纹识别，并批评了发布公司的动机。其他人则强调正确舍入数学函数的进展有望消除此类途径，并指出更新后的 glibc 已改变了 tanh 的输出。

**标签**: `#browser fingerprinting`, `#privacy`, `#JavaScript`, `#operating systems`, `#security`

---

<a id="item-2"></a>
## [Claude Code 预提示消耗 33k tokens，OpenCode 仅 7k](https://systima.ai/blog/claude-code-vs-opencode-token-overhead) ⭐️ 8.0/10

Systima 的一项实证研究发现，Anthropic 的 Claude Code 在读取用户提示之前会发送约 33,000 个 token，而开源代理 OpenCode 仅发送 7,000 个 token，原因在于缓存效率低下和更高的 harness 开销。 这种 token 低效导致使用 Claude Code 的开发者的 API 成本显著增加，使得 OpenCode 成为更具成本效益的选择；这也引发了对供应商锁定和专有编码代理透明度的质疑。 该研究记录了编码代理与 API 端点之间的所有请求；文中提到的一个局限是未控制任务复杂度，作者计划增加更深入的任务和定性结果对比。

hackernews · systima · 7月12日 18:25 · [社区讨论](https://news.ycombinator.com/item?id=48883275)

**背景**: Claude Code 是 Anthropic 的专有终端 AI 编码代理，而 OpenCode 是一个开源替代方案。这两种工具都使用大型语言模型 API，并在用户提示前添加系统指令、工具、对话历史和其他开销（称为 'harness'）。Token 开销指的就是这些预先发送的 token，直接影响 API 成本。高效缓存可以减少重复开销，但本研究表明，两个代理在开销管理上存在显著差异。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://grokipedia.com/page/OpenCode">OpenCode</a></li>

</ul>
</details>

**社区讨论**: 社区评论怀疑 Anthropic 故意增加 token 使用以增加收入，有报告称子代理快速消耗预算，甚至简单的提示也会触发数十次工具调用。一些用户已转向 OpenCode 或 Codex 等替代品，原因是透明度和成本更优。作者承认反馈，并将更新帖子以包含更详细的对比。

**标签**: `#coding-agents`, `#token-efficiency`, `#claude`, `#cost-optimization`, `#empirical-analysis`

---

<a id="item-3"></a>
## [通过现代编程代理构建新旧应用](https://terrytao.wordpress.com/2026/07/11/old-and-new-apps-via-modern-coding-agents/) ⭐️ 8.0/10

菲尔兹奖得主陶哲轩成功利用基于大语言模型的编程代理，移植了二十多个旧的数学小程序，并创建了新的交互式可视化。整个过程效率极高，仅引入一个轻微漏洞，代理还发现了原始代码中的两个漏洞。 这表明像是数学家这样的非程序员也能利用 LLM 编程代理，构建交互式工具，从而在学术界普及软件创造。这也凸显了这些工具在非关键任务中的可靠性，有可能彻底改变教育资源。 陶哲轩将超过 20 个旧的数学小程序（原为 Java）移植到现代网络技术，仅出现一个轻微的拖拽处理错误，代理还发现了原始代码中的两个未知漏洞。他强调这些可视化并非研究论文的关键部分，因此使用 LLM 生成代码的风险是可以接受的。

hackernews · subset · 7月12日 11:09 · [社区讨论](https://news.ycombinator.com/item?id=48880170)

**背景**: 陶哲轩是享誉全球的数学家，菲尔兹奖得主，以其在调和分析和偏微分方程等领域的工作闻名。基于大语言模型的现代编程代理能将自然语言指令转化为可用代码，极大降低了软件开发门槛。过去，构建交互式数学演示需要大量编程工作，这使得许多学者望而却步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://terrytao.wordpress.com/2026/07/11/old-and-new-apps-via-modern-coding-agents/">Old and new apps, via modern coding agents | What's new</a></li>
<li><a href="https://www.augmentcode.com/tools/8-top-ai-coding-assistants-and-their-best-use-cases">8 Best AI Coding Assistants [Updated May 2026] | Augment Code</a></li>

</ul>
</details>

**社区讨论**: 社区普遍持热情态度，注意到 LLM 对软件创造的普及效应（recursivedoubts 分享了教学受益实例）。多位评论者认为这反映出定制软件的巨大潜在需求（semiquaver）。但也有人呼应陶哲轩的谨慎，指出 LLM 生成的代码并非完全可靠，最适合非关键任务（wffurr）。

**标签**: `#LLM`, `#coding-agents`, `#mathematics`, `#visualization`, `#education`

---

<a id="item-4"></a>
## [George Hotz 认为前沿 AI 实验室被过度炒作且估值过高](https://geohot.github.io//blog/jekyll/update/2026/07/12/i-love-llms.html) ⭐️ 8.0/10

George Hotz 发表博客文章，认为前沿 AI 实验室被过度炒作且估值过高，因为它们将无法捕获其 AI 模型创造的价值。 这位知名黑客的批评挑战了估值数十亿美元的 AI 实验室背后的经济假设，促使重新评估闭源模型，并推动向开源和定制软件的转变。 Hotz 的核心论点是，尽管 AI 将创造巨大价值，但竞争和开源替代方案将阻止前沿实验室捕获这些价值。社区回应强调 LLM 使高度个性化的一次性软件成为可能，但可能会碎片化开源协作。

hackernews · therepanic · 7月12日 18:31 · [社区讨论](https://news.ycombinator.com/item?id=48883343)

**背景**: 像 OpenAI、Anthropic 和 DeepMind 这样的前沿 AI 实验室开发尖端大型语言模型（LLM），为 ChatGPT 等应用提供动力。高估值基于这些模型将产生巨大经济回报的预期，但怀疑者认为商品化和开源竞争可能会限制利润捕获。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Most_prestigious_AI_research_labs">Most prestigious AI research labs</a></li>

</ul>
</details>

**社区讨论**: 评论者大多同意价值捕获论点，分享了使用 LLM 构建私有定制软件的实例。一些人担忧易于复刻会碎片化开源社区，而另一些人指出当前模型输出质量仍参差不齐。

**标签**: `#AI`, `#LLMs`, `#valuation`, `#open source`, `#hype`

---

<a id="item-5"></a>
## [Hunyuan3D 模型 MLX 移植版实现苹果设备上快速本地图像转 3D](https://www.reddit.com/r/LocalLLaMA/comments/1uuga40/local_image_to_3d_2gb_ram_20s_apple_silicon_iphone/) ⭐️ 8.0/10

开源应用 Modelr 以及腾讯 Hunyuan3D-Paint 和 Hunyuan3D-Shape 的 MLX 移植版已发布，可在苹果芯片和 iPhone 上实现本地图像转 3D 生成。量化后的小型模型能在 20 秒以内、低于 2GB 内存的条件下运行。 这使消费者级苹果设备能够高效、保护隐私地直接生成本地 3D 资产，无需依赖云端，降低了独立开发者和创作者的门槛。同时也展示了 MLX 框架在移动和桌面设备上以更低开销运行复杂 AI 任务的潜力。 在 M4 Max 上用 FP16 精度，小型形状模型需约 20.9 秒和约 5.6GB 峰值内存，而大型 PBR 纹理模型则需 344 秒和约 39GB 内存。量化（Q4/Q8）使 iPhone 运行成为可能，但 PBR 管线仍占用较多资源。

reddit · r/LocalLLaMA · /u/arduinoRPi4 · 7月12日 14:00

**背景**: MLX 是苹果为苹果芯片优化的开源数组框架，提供 Python、C++和 Swift 接口用于机器学习。Hunyuan3D 是腾讯的大规模 3D 生成系统，可从图像创建带纹理的 3D 资产。该移植版利用 MLX 避免了 PyTorch 的开销，在 Mac 和 iPhone 上实现了轻量级本地推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/ml-explore/mlx">GitHub - ml-explore/mlx: MLX: An array framework for Apple silicon · GitHub</a></li>
<li><a href="https://github.com/Tencent-Hunyuan/Hunyuan3D-2">GitHub - Tencent-Hunyuan/Hunyuan3D-2: High-Resolution 3D Assets Generation with Large Scale Hunyuan3D Diffusion Models. · GitHub</a></li>

</ul>
</details>

**标签**: `#image-to-3d`, `#mlx`, `#apple-silicon`, `#local-ai`, `#3d-generation`

---

<a id="item-6"></a>
## [苹果起诉 OpenAI 窃取商业机密，称涉事‘各层级’](https://www.reddit.com/r/LocalLLaMA/comments/1uus189/apple_sues_openai_alleging_trade_secret_theft/) ⭐️ 8.0/10

苹果已对 OpenAI 提起诉讼，指控其系统性窃取商业机密，据称该计划涉及公司的“各个层级”。 这起法律纠纷可能对人工智能开发中的知识产权产生重大影响，或影响大型科技公司之间的合作与竞争格局。 目前可获取的信息未说明被指窃取的具体商业机密内容、计划性质或诉讼提交的法院。

reddit · r/LocalLLaMA · /u/fallingdowndizzyvr · 7月12日 21:25

**背景**: 苹果和 OpenAI 都是人工智能行业的重要参与者。苹果对其 AI 项目保密极为严格，OpenAI 则以 GPT-4 等模型及多家公司合作闻名。科技领域的商业机密诉讼常涉及前员工或合作伙伴被指控滥用机密信息。

**标签**: `#AI`, `#legal`, `#Apple`, `#OpenAI`, `#trade secrets`

---

<a id="item-7"></a>
## [面向 llama.cpp GGUF 模型的交互式雅可比透镜可视化与实时操控工具](https://www.reddit.com/r/LocalLLaMA/comments/1uu32z6/interactive_jacobianlens_visualizer_and_live/) ⭐️ 8.0/10

新开源工具 jlens-gguf 为运行在 llama.cpp 上的 GGUF 模型提供了交互式的雅可比透镜特征可视化与实时操控功能，其灵感来自 Anthropic 的研究，是首个专为此类模型设计的工具。 该工具填补了本地大语言模型实验的空白，将先进的可解释性和模型操控技术带入流行的 llama.cpp 生态，使研究者和爱好者无需云服务即可探索和控制模型行为。 原生 GGUF 服务器支持内部状态观测及 j-space 的替换/消融/操控，而外部 llama-server 模型仅可被观测。透镜的内存开销约为模型大小的 1/8，因此 160GB 模型需约 20GB 额外内存。

reddit · r/LocalLLaMA · /u/Responsible_Fig_1271 · 7月12日 02:37

**背景**: 雅可比透镜是一种可解释性技术，利用模型的雅可比矩阵识别可能影响后续 token 的内部特征，从而揭示隐式表示。GGUF 是 llama.cpp 使用的二进制模型文件格式，可在消费级硬件上实现快速高效推理。llama.cpp 是一个广泛使用的 C++库，用于在本地运行大语言模型，而操控/消融则指通过改变内部激活值来修改模型输出或消除不期望的行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/anthropics/jacobian-lens">GitHub - anthropics/jacobian-lens: Companion code for the global workspace interpretability paper · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/GGUF">GGUF - Wikipedia</a></li>

</ul>
</details>

**标签**: `#jacobian-lens`, `#llama.cpp`, `#model-interpretability`, `#gguf`, `#steering`

---

<a id="item-8"></a>
## [在 Qwen3-4B 上跨 7 个数据集评估 Anthropic J-Space 幻觉检测](https://www.reddit.com/r/LocalLLaMA/comments/1uu61wb/i_mapped_anthropics_jspace_hallucination_signal/) ⭐️ 8.0/10

一位 Reddit 用户在 Qwen3-4B 上对七个数据集实证评估了 Anthropic 的 J-Space 熵方法，证明它能在输出 logprobs 失效时成功检测高置信度错误，但也揭示了在 TruthfulQA 和数学任务上的关键失效。 该评估明确了 J-Space 在事实检索任务中提升幻觉检测效果的具体条件，为部署更可靠的模型安全措施提供了实用见解，并指出了阻碍更广泛应用的局限性。 实验使用 Qwen3-4B 的 L30-L34 层，在约 11,400 个样本上测试。J-Space 在捕获自信的事实错误方面表现出色（PopQA 上以 5%路由预算达到 100%精确率），但在 TruthfulQA（“安全”象限下仍有 84.9%错误率）和数学推理上完全失效，因为计算引起的内在噪声导致静态阈值无法迁移。

reddit · r/LocalLLaMA · /u/dasjomsyeet · 7月12日 05:06

**背景**: Anthropic 的“Global Workspaces”论文提出了 J-Space，通过衡量模型深层内部激活的熵（“工作空间噪声”）来检测幻觉。标准幻觉检测方法通常依赖输出标记概率（logprobs），但当模型自信犯错时可能漏检。J-Space 通过分析内部不确定性来捕捉这类高置信度错误，有望为安全部署提供补充信号。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen</a></li>

</ul>
</details>

**标签**: `#hallucination-detection`, `#J-Space`, `#entropy`, `#model-interpretability`, `#Qwen3-4B`

---

<a id="item-9"></a>
## [LARP：严肃创始人的营收基础设施](https://www.larp.website/) ⭐️ 7.0/10

一个名为 LARP 的讽刺网站上线，戏仿 Y Combinator 初创企业的营收模式，即客户主要来自同一批或近期批次的其它公司。 该讽刺作品揭示了一种可疑的创业做法，促使人们反思真正的产品市场契合度，以及建立在封闭生态交易上的营收可持续性。 该网站纯属虚构，但其设计和文案极具说服力，以至于一些读者直到最后一段才确定这是一个玩笑。

hackernews · BerislavLopac · 7月12日 16:56 · [社区讨论](https://news.ycombinator.com/item?id=48882569)

**背景**: Y Combinator 是一家著名的创业加速器。在其孵化批次中，公司间经常相互购买服务，形成一种可能人为夸大营收数字的封闭循环。LARP 一词原意为真人角色扮演，此处暗指创始人只是在扮演成功企业。

**社区讨论**: 社区反应既好笑又认可，许多人指出这种做法很常见。有人承认一开始分不清网站是真是假，凸显了该讽刺作品的精准到位。还有评论者开玩笑说给自己的朋友估值 1.2 万亿美元。

**标签**: `#satire`, `#startups`, `#venture-capital`, `#humor`, `#parody`

---

<a id="item-10"></a>
## [博客文章类比电影 CGI 转向与编程中 LLM 的采用](https://fabiensanglard.net/extinct/index.html) ⭐️ 7.0/10

一篇题为《你不是说灭绝了吗？》的博客文章将电影行业从实物特效向 CGI 的过渡与软件开发中大型语言模型（LLM）的日益使用进行类比，认为拒绝采用 AI 工具的开发者可能在生产力上落后。 这一类比突显了软件工程中的关键争论：通过 LLM 追求生产力可能贬低熟练技艺和长期代码质量，这与电影行业最初 CGI 泛滥导致实物特效艺术家被取代、后因缺乏真实感而遭抵制的现象相似。 文章声称手工编写每一行代码不再是常态，LLM 能辅助生成测试，但评论者指出 LLM 代码常需反复审查以达到手工质量，且生成的测试可能遗漏预期行为。评论还将电影类比延伸，指出 CGI 因数字特效公司未成立工会而贬低了微缩模型和布景设计劳动的价值。

hackernews · zdw · 7月12日 15:17 · [社区讨论](https://news.ycombinator.com/item?id=48881830)

**背景**: 大型语言模型（LLM）是通过海量文本训练、能生成代码和自然语言的人工智能。CGI（计算机生成图像）从 20 世纪 90 年代起取代了许多电影实物特效，提供了新视觉可能，但常牺牲微缩模型和电子动画的真实触感。电影行业对 CGI 的过度依赖近来引发视觉疲劳和劳工问题的批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>
<li><a href="https://www.studiobinder.com/blog/what-is-cgi-meaning-definition/">What is CGI ? How CGI Works in Movies and Animation</a></li>

</ul>
</details>

**社区讨论**: 评论者大多质疑这一前提，认为产出量对程序员并非有意义的指标，使用 LLM 经常导致质量下降而需返工。一些人将其与电影行业剥削未成立工会的特效劳动力及回归实物特效的趋势类比，暗示软件行业可能经历类似周期。其他人指出，即使 LLM 能提高某些任务的效率，人工仔细审查仍然至关重要。

**标签**: `#LLMs`, `#software-engineering`, `#productivity`, `#analogy`, `#CGI`

---

<a id="item-11"></a>
## [英伟达 RTX Spark 真机亮相 Bilibili World，运行 1200 亿参数大模型](https://www.qbitai.com/2026/07/447981.html) ⭐️ 7.0/10

在 Bilibili World 上，一台搭载英伟达 RTX Spark 芯片的笔记本公开展示，现场本地运行了 1200 亿参数的大语言模型。 这标志着边缘 AI 的重大进展，表明消费级笔记本已能在本地运行超大规模模型，无需依赖云端，有望催生新的实际 AI 应用。 RTX Spark 芯片集成了 20 核 Arm 架构 Grace CPU 和 Blackwell RTX GPU，采用统一内存，专为 Windows on Arm 笔记本设计。演示中未公开 1200 亿参数模型的性能数据。

rss · 量子位 · 7月12日 01:37

**背景**: 英伟达于 2026 年 5 月 31 日发布了 RTX Spark 超级芯片，面向 Windows 笔记本，将 CPU 与 GPU 封装在一起，用于 AI、游戏和创作任务。这顺应了将高性能 AI 推向边缘设备的混合架构潮流，其统一内存设计能高效处理大模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nvidia_RTX_Spark">Nvidia RTX Spark</a></li>

</ul>
</details>

**标签**: `#NVIDIA`, `#Super Chip`, `#Large Language Model`, `#Edge AI`, `#Laptop`

---

<a id="item-12"></a>
## [AICon 深圳分享 Qwen 模型线性注意力高性能优化实践](https://www.infoq.cn/article/wg5h3JBMvs5ZkoP0azha?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

在 AICon 深圳的一次演讲中，介绍了针对 Qwen 系列语言模型的线性注意力机制的高性能优化技术，旨在提升长上下文处理的效率。 线性注意力将计算复杂度从序列长度的平方降低到线性，这对于扩展大语言模型处理更长上下文的能力至关重要；为 Qwen 模型优化线性注意力可以实现更高效的部署并降低推理成本。 该演讲可能涵盖了如 Triton 内核优化或使用 Flash Linear Attention 库的实现；线性注意力通过重新构造自注意力计算来提升效率，但可能涉及准确性或内存方面的权衡。

rss · InfoQ 中国 · 7月12日 10:00

**背景**: 线性注意力是标准自注意力的一种替代方案，通过重新安排计算顺序（如使用核函数技术）将 O(n^2)的时间和内存复杂度降低到 O(n)。Qwen 模型系列由阿里巴巴开发，是一组基于类似 Llama 的解码器架构的强大开源大语言模型。优化注意力机制对于高效地服务长上下文模型至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Flash_Linear_Attention">Flash Linear Attention</a></li>
<li><a href="https://medium.com/data-science/linear-attention-is-all-you-need-5fa9c845c1b5">Linear Attention Is All You Need. Self- attention at a fraction... | Medium</a></li>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Linear Attention`, `#Model Optimization`, `#Qwen`, `#Deep Learning`, `#High Performance Computing`

---

<a id="item-13"></a>
## [爱尔兰数据中心耗电达全国 23%](https://www.tomshardware.com/tech-industry/data-centers/irelands-data-centers-consumed-nearly-as-much-electricity-as-every-home-in-the-country-combined-in-2025-server-farms-gulped-23-percent-of-national-power-despite-years-of-grid-restrictions) ⭐️ 7.0/10

2025 年，爱尔兰的数据中心消耗了全国 23%的电力，较前一年增长 10%，尽管现有的电网连接限制仍然存在。 这一激增凸显了数字基础设施扩张与气候目标之间的紧张关系，一个小国的电网难以满足需求，可能推高电价和碳排放。 数据中心的用电量几乎相当于爱尔兰所有家庭用电量的总和，尽管 2021 年都柏林地区已暂停新的电网接入，但年增长率依然达到 10%，这表明现有设施的使用强度在增加。

rss · Tom's Hardware · 7月12日 15:12

**背景**: 爱尔兰因其低企业税率和凉爽气候（降低冷却成本）而成为数据中心枢纽。谷歌、微软、亚马逊等大型科技公司在此运营大型服务器农场，服务欧洲用户。然而，该国电网规模相对较小，使得数据中心的高能耗影响尤为显著。不断增长的用电量对爱尔兰 2030 年碳排放减半的目标构成挑战，并引发了关于电网扩建和可再生能源投资的政策辩论。

**社区讨论**: 评论者对此严重性存在争议：一些人指出加州的数据中心能耗是爱尔兰的四倍，但人口多得多，认为人均数据并不极端；其他人批评了文章的编辑语气，并主张建设一个核反应堆即可完全满足爱尔兰数据中心的电力需求；本地声音还强调在商业负荷增长的情况下，居民电费居高不下。

**标签**: `#Data Centers`, `#Energy Consumption`, `#Ireland`, `#Sustainability`, `#Infrastructure`

---

<a id="item-14"></a>
## [具身数据行业融资 44.7 亿，近百玩家涌入，商业化待解](https://www.qbitai.com/2026/07/447914.html) ⭐️ 6.0/10

不完全统计显示，国内具身智能数据领域已有 97 家玩家，其中 70 家做数据采集，27 家做数据基础设施，一年内融资总额达 44.7 亿元人民币。 融资热潮表明投资人对具身智能信心十足，但文章质疑企业是否能真正通过“卖数据”盈利，凸显了商业化关键挑战。 该统计为不完全统计，实际数量可能更多；许多数据基础设施玩家原是 AI 数据标注公司，如海天瑞声、数据堂。

rss · 量子位 · 7月12日 01:14

**背景**: 具身智能指能通过身体与环境交互的 AI 系统，如机器人，其训练需要大量数据，催生了对专业数据采集和基础设施的需求。近期投资激增反映了行业对具身智能在机器人、自动驾驶等领域潜力的期待。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.marsbit.co/20260712102912558212.html">news.marsbit.co/20260712102912558212.html</a></li>
<li><a href="http://www.broadview.com.cn/article/420497">被众多AI大佬看好的 具 身 智 能 到底是什么？ 它凭什么成为下一个AI...</a></li>

</ul>
</details>

**标签**: `#Embodied AI`, `#Data Market`, `#Robotics`, `#Financing`

---

<a id="item-15"></a>
## [FCC 批准轨道太空镜，首批测试卫星今年发射](https://www.tomshardware.com/tech-industry/fcc-approves-orbital-space-mirrors-first-test-satellites-will-launch-this-year-large-spacecraft-reflects-sunlight-to-earths-surface-for-construction-sites-search-and-rescue-lighting-and-more) ⭐️ 6.0/10

初创公司 Reflect Orbital 获得 FCC 批准，将发射名为 EARENDIL-1 的试验卫星，测试一面 60×60 英尺的镜子将阳光反射到地球表面用于夜间照明等应用，预计今年四月发射。 该技术可为建筑工地、搜救和能源等领域提供夜间按需照明，但科学家警告它可能导致光污染并影响天文观测。 镜面尺寸为 60×60 英尺（18×18 米），该公司计划部署多达 4000 面此类镜子。FCC 表示其审查仅限于无线电频谱问题，环境和天文方面的担忧不在其管辖范围内。

rss · Tom's Hardware · 7月12日 12:20

**背景**: 利用太空镜照亮地球的概念最早由 Hermann Oberth 在 20 世纪 20 年代提出。Reflect Orbital 是首家获得监管测试批准的初创公司。FCC 的主要职责是管理射频干扰，而非评估更广泛的环境影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Space_mirror">Space mirror - Wikipedia</a></li>
<li><a href="https://www.space.com/space-exploration/satellites/this-companys-plan-to-launch-4-000-massive-space-mirrors-has-scientists-alarmed-from-an-astronomical-perspective-thats-pretty-catastrophic">Company's plan to launch 4,000 massive space mirrors alarms scientists | Space</a></li>

</ul>
</details>

**标签**: `#space technology`, `#FCC`, `#satellites`, `#orbital mirrors`, `#lighting`

---