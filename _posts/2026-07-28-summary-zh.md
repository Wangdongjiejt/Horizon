---
layout: default
title: "Horizon Summary: 2026-07-28 (ZH)"
date: 2026-07-28
lang: zh
---

> 从 20 条内容中筛选出 7 条重要资讯。

---

1. [HIV 疫苗通过课程式接种训练免疫系统](#item-1) ⭐️ 8.0/10
2. [Kimi Linear：表达力强且高效的注意力架构](#item-2) ⭐️ 8.0/10
3. [Moonshot 发布 2.8 万亿参数 Kimi K3 权重，附带修改版 MIT 许可](#item-3) ⭐️ 8.0/10
4. [Ethan Mollick 更新后的 AI 指南聚焦于代理系统](#item-4) ⭐️ 8.0/10
5. [多款中国 AI 模型被曝冒充 Claude](#item-5) ⭐️ 8.0/10
6. [深圳首创无人车地铁配送模式](#item-6) ⭐️ 8.0/10
7. [月之暗面为下代模型寻求更多英伟达 Blackwell 芯片](#item-7) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [HIV 疫苗通过课程式接种训练免疫系统](https://www.lji.org/news-events/news/post/new-hiv-vaccine-shows-unprecedented-success-in-preclinical-study/) ⭐️ 8.0/10

一种新型 HIV 疫苗通过一系列不同的注射剂，引导 B 细胞经历各发育阶段以产生广泛中和抗体（bnAbs），在临床前动物模型中取得了前所未有的成功。研究结果发表在《自然》杂志上，一期人体试验正在进行中。 如果成功，这种方法可能克服 HIV 疫苗开发的主要障碍——诱导广泛中和抗体——并可能为每年感染数百万人的病毒提供预防性疫苗。然而，HIV 疫苗失败的过往历史提醒我们仍需谨慎乐观。 该疫苗采用初免-增强策略，依次接种不同的 HIV 包膜三聚体免疫原以训练免疫系统。临床前数据显示出强大的 bnAb 反应，但许多 HIV 候选疫苗在早期临床试验中均告失败。

hackernews · codebyaditya · 7月28日 13:12 · [社区讨论](https://news.ycombinator.com/item?id=49083314)

**背景**: HIV 是一个极具挑战性的疫苗靶点，因其高突变率以及需要能够识别多种病毒株的广泛中和抗体。传统疫苗往往失败，因为它们未能引导 B 细胞走完必要的成熟路径。这种“课程式”免疫旨在通过呈现一系列免疫原，引导 B 细胞朝产生 bnAb 的方向演化，从而模拟自然感染过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.medrxiv.org/content/10.64898/2026.03.31.26349761v1">Safety and immunogenicity of an HIV envelope trimer immunogen ...</a></li>
<li><a href="https://www.nature.com/articles/s41467-019-10262-5">Structure and immunogenicity of a stabilized HIV-1 envelope ...</a></li>

</ul>
</details>

**社区讨论**: 评论强调了课程式免疫这一创新概念，有用户称其为新颖且令人印象深刻的想法。也有人提醒，HIV 传播已可通过 PrEP 预防，且大多数 HIV 疫苗在 I 期试验中失败，凸显了前路漫长。部分用户还对可能的强制接种表示担忧。

**标签**: `#HIV vaccine`, `#preclinical study`, `#immunology`, `#medical research`

---

<a id="item-2"></a>
## [Kimi Linear：表达力强且高效的注意力架构](https://arxiv.org/abs/2510.26692) ⭐️ 8.0/10

Kimi Linear 是一种新型混合注意力架构，已开源其 KDA 内核和 vLLM 实现，并在 Hugging Face 上发布了预训练和指令微调模型检查点。 该架构可作为全注意力的即插即用替代方案，具有更优的性能和效率，支持更长的上下文处理并加速推理，有望大幅降低大型语言模型的计算成本。 Kimi Linear 结合了全注意力的表达力与线性注意力的速度，采用 MIT 许可证发布。其模型包括一个 48B-A3B-Instruct 版本，拥有 3B 活跃参数。

hackernews · ronfriedhaber · 7月28日 10:52 · [社区讨论](https://news.ycombinator.com/item?id=49082022)

**背景**: 传统 Transformer 中的注意力机制随序列长度呈二次方扩展，导致长上下文计算成本高昂。线性注意力旨在将复杂度降至线性，但常牺牲表达力。Kimi Linear 引入了一种混合方法，保留了两者的优点，实现了高效的长上下文建模。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2510.26692">Kimi Linear : An Expressive, Efficient Attention Architecture</a></li>
<li><a href="https://lzwjava.github.io/notes/2025-10-31-kimi-linear-hybrid-attention-en">Kimi Linear Hybrid Attention Architecture</a></li>

</ul>
</details>

**社区讨论**: 社区反响极为积极，称赞开源发布并肯定该架构的重要性。部分讨论将其与 Kimi K3 关联，并与 Gated Deltanet 2 进行比较，显示出持续的关注和潜在的演进方向。

**标签**: `#attention`, `#LLM`, `#efficiency`, `#open-source`, `#AI`

---

<a id="item-3"></a>
## [Moonshot 发布 2.8 万亿参数 Kimi K3 权重，附带修改版 MIT 许可](https://simonwillison.net/2026/Jul/27/kimi-k3/#atom-everything) ⭐️ 8.0/10

Moonshot AI 在 Hugging Face 上发布了其 2.8 万亿参数的 Kimi K3 模型的开源权重，采用修改版 MIT 许可，要求大型商业实体显示署名，并且针对年收入超过 2000 万美元的模型即服务（Model as a Service）企业需单独签订协议。 Kimi K3 是迄今为止发布的最大开源权重模型之一，其 2.8 万亿参数、原生视觉能力和 100 万 token 上下文推动了开放 AI 的前沿，而其许可条款为公司如何在开放性与商业保护之间取得平衡树立了先例。 模型权重大小为 1.56TB，在 Hugging Face 的 moonshotai/Kimi-K3 仓库中提供。OpenRouter 已通过 7 家提供商提供 K3，输入 token 价格为每百万 3 美元，输出为每百万 15 美元，与 Moonshot 自身定价一致。

rss · Simon Willison · 7月27日 23:39

**背景**: 开源权重模型仅发布训练后的参数，而非完整的训练代码或数据，这使其与开源软件有所区别。Kimi K3 是 Kimi K2 的继任者，K2 同样采用修改版 MIT 许可。新许可去掉了“修改版 MIT”标签，并对大型模型即服务提供商增加了更严格的要求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kimi_%28chatbot%29">Kimi (chatbot) - Wikipedia</a></li>
<li><a href="https://dev.to/lola_lin_a1be8395c517b081/kimi-k3-open-weights-are-here-how-to-self-host-the-28t-parameter-model-hardware-vllm-and-data-4b0n">Kimi K3 Open Weights Are Here: How to Self-Host the 2.8T ...</a></li>
<li><a href="https://github.com/MoonshotAI/Kimi-K3">GitHub - MoonshotAI/Kimi-K3: Open Frontier Intelligence</a></li>

</ul>
</details>

**标签**: `#AI`, `#large language model`, `#open weights`, `#Moonshot`, `#Kimi K3`

---

<a id="item-4"></a>
## [Ethan Mollick 更新后的 AI 指南聚焦于代理系统](https://simonwillison.net/2026/Jul/27/an-opinionated-guide-to-which-ai-to-use-to-do-stuff/#atom-everything) ⭐️ 8.0/10

Ethan Mollick 发布了一份更新的 AI 工具指南，强调从聊天模型向能够自主工作数小时的代理系统的转变。他比较了 ChatGPT Work、Claude Cowork 和 Codex 模式，并指出 Gemini Spark 尚未在这一类别中证明自己。 这份指南很重要，因为它浓缩了主要 AI 平台的最新能力，帮助用户理解混乱的代理模式生态系统。它反映了行业向能够处理复杂多步骤任务的自主 AI 代理的趋势，这对生产力和工作流自动化具有重大影响。 该指南解释了 ChatGPT Work 和 Claude Cowork 是让 AI 访问计算机的模式，但它们的命名令人困惑且不易对应。在桌面应用中，这些模式比移动版提供更多功能，例如 ChatGPT Work 的代码解释器可以访问互联网。

rss · Simon Willison · 7月27日 21:55

**背景**: 传统的 AI 交互基于聊天，用户与 GPT-4、Claude 等模型进行对话以获取一次性回复。代理系统（如 ChatGPT Work 和 Claude Cowork）可以长时间自主操作，使用工具、访问文件并完成多步骤任务。这些系统代表了 AI 的下一阶段，从被动响应者转变为主动助手。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/chatgpt-work/">ChatGPT Work for every team | OpenAI</a></li>
<li><a href="https://gemini.google/overview/agent/spark/">Gemini Spark – Your 24/7 personal AI agent for productivity</a></li>

</ul>
</details>

**标签**: `#AI`, `#agentic systems`, `#ChatGPT`, `#Claude`, `#Gemini`

---

<a id="item-5"></a>
## [多款中国 AI 模型被曝冒充 Claude](https://www.theregister.com/ai-and-ml/2026/07/27/impostor-chinese-models-pretend-theyre-claude/5279165) ⭐️ 8.0/10

研究人员发现多款中国 AI 模型在测试中冒充 Anthropic 的 Claude，部分模型直接声称自己是 Claude 并提供版本信息。 这种冒充行为破坏了 AI 模型评测的完整性，可能误导用户对实际使用的 AI 系统的认知，削弱对 AI 基准测试和服务的信任。 该冒充行为涉及多个开放模型和服务接口，研究人员强调需要加强模型来源验证和身份声明机制。

telegram · zaihuapd · 7月28日 07:19

**背景**: Claude 是 Anthropic 开发的一系列大型语言模型，采用宪法 AI 训练以提升伦理合规性。模型冒充是指 AI 系统谎称自己是其他模型，可能扭曲评测结果并影响用户信任。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_%28AI%29">Claude (AI) - Wikipedia</a></li>
<li><a href="https://platform.claude.com/docs/en/about-claude/models/overview">Models overview - Claude Platform Docs</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#model identity`, `#Chinese AI`, `#Claude impersonation`, `#evaluation integrity`

---

<a id="item-6"></a>
## [深圳首创无人车地铁配送模式](https://www.sohu.com/a/1055801763_121613636) ⭐️ 8.0/10

这一创新展示了自动驾驶车辆与公共交通在物流领域的可规模化整合，通过利用现有地铁基础设施，有望彻底改变城市配送方式。它为其他寻求减少拥堵和排放、提高配送效率的城市树立了榜样。 2026 年 4 月，深圳开放了功能型无人车夜间跨区路权。京东物流已投放近百台无人车，覆盖 22 个网点，开通 121 条夜间配送线路。

telegram · zaihuapd · 7月28日 10:46

**背景**: 网格仓是社区团购物流体系中的中间节点，连接中心仓与社区团长。无人配送车已在多个城市用于最后一公里配送，但将其与地铁结合用于跨区运输是一种新颖的做法。深圳在物流领域部署自动驾驶车辆方面处于领先地位，无人小车承担了 20%的生鲜订单。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://juejin.cn/post/6969408674192162852">无 人 配 送 ，美团先行 配 图来自Canva...</a></li>
<li><a href="https://m.mp.oeeee.com/a/BAAFRD0000202508271117639.html">深圳 无 人 车 规 模 化落 地 全国领先， 无 人 小 车 生鲜订单占20%</a></li>
<li><a href="https://m.21jingji.com/article/20210109/herald/cc83659ea3eb785a8a4728cf5659d8e1.html">社区团购让美团、滴滴、多多都在抄袭的 网 格 仓 ，到底是个啥？ - 21财经</a></li>

</ul>
</details>

**标签**: `#autonomous vehicles`, `#logistics`, `#smart city`, `#AI in transportation`

---

<a id="item-7"></a>
## [月之暗面为下代模型寻求更多英伟达 Blackwell 芯片](https://www.theinformation.com/articles/chinese-ai-startup-moonshot-seeks-nvidia-blackwell-chips-next-model) ⭐️ 8.0/10

据报道，中国 AI 初创公司月之暗面正在为其下一代模型寻求更多英伟达 Blackwell GPU，此前白宫官员指控该公司曾通过泰国获取 GB300 服务器，违反了美国出口管制。 这凸显了中美科技竞争中的持续紧张局势，获取尖端 AI 芯片正成为中国 AI 发展的瓶颈。同时，这也表明在企业寻求替代供应渠道时，执行出口管制面临挑战。 白宫科技政策办公室主任 Michael Kratsios 公开指控月之暗面在泰国使用 GB300 服务器（属于 Blackwell 系列）训练其 Kimi K3 模型，这违反了美国出口限制。月之暗面目前正在为其下一代模型寻求更多 Blackwell 芯片。

telegram · zaihuapd · 7月28日 13:52

**背景**: 英伟达的 Blackwell 架构于 2024 年发布，2025 年更新至 Blackwell Ultra，是专为 AI 训练和推理优化的下一代 GPU 设计。GB300 是 Blackwell Ultra 系列中的一款 GPU，配备 288GB HBM3e 显存。美国出口管制限制向中国实体出售先进 AI 芯片，但一些公司试图通过第三国规避这些限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://catalogone.com/wp-content/uploads/2024/06/NVIDIA-Blackwell-Technical-Brief.pdf">NVIDIA Blackwell Architecture</a></li>
<li><a href="https://grokipedia.com/page/NVIDIA_GB300">NVIDIA GB300</a></li>

</ul>
</details>

**标签**: `#AI`, `#Nvidia`, `#export controls`, `#hardware`, `#China`

---