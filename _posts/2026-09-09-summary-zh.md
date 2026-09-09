---
layout: default
title: "Horizon Summary: 2026-09-09 (ZH)"
date: 2026-09-09
lang: zh
---

> 从 43 条内容中筛选出 11 条重要资讯。

---

**科技新闻**
1. [OpenAI 称用 AI 与 Lean 证明纳维–斯托克斯千禧难题](#item-tech-news-1) ⭐️ 10.0/10
2. [AlphaGenome Atlas：人类 DNA 全单碱基变化预测图谱](#item-tech-news-2) ⭐️ 9.0/10
3. [数学家指控 OpenAI 窃取纳维-斯托克斯研究思路](#item-tech-news-3) ⭐️ 8.0/10
4. [陶哲轩警告：AI 可能耗尽开放数学问题并损害开放科学](#item-tech-news-4) ⭐️ 8.0/10
5. [OpenAI 发布 ChatGPT Images 2.5 与两个新 API 模型](#item-tech-news-5) ⭐️ 8.0/10
6. [NeurIPS 用 AI 检测器误拒 178 篇论文](#item-tech-news-6) ⭐️ 8.0/10
7. [ASML 与台积电合作推进 High NA EUV 采用 12 英寸光掩模](#item-tech-news-7) ⭐️ 8.0/10
8. [Meta 发布个人 AI 智能体 Muse](#item-tech-news-8) ⭐️ 7.0/10
9. [Qwen3.8 27B 量化基准：4-bit 可用，1-bit 明显失效](#item-tech-news-9) ⭐️ 7.0/10

**财经新闻**
1. [报告：加密货币平台一年多损失超 36 亿美元，多数曾做安全审计](#item-finance-news-1) ⭐️ 7.0/10
2. [上海 10 月起生育医疗费用新政：参保职工合规费用不再需个人自付](#item-finance-news-2) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [OpenAI 称用 AI 与 Lean 证明纳维–斯托克斯千禧难题](https://openai.com/index/navier-stokes-solution/) ⭐️ 10.0/10

OpenAI 公布内部 AI 系统对纳维–斯托克斯存在性与光滑性问题（七大千禧年难题之一）的证明作答：光滑初始条件下的流体可在有限时间内形成奇点。OpenAI 称同时公开研究论文与 Lean 形式化验证，求解过程使用约 1 万个并行智能体、270 万条消息和约 1300 亿输出 token，并表示无意申领千禧年奖。公告还提到，OpenAI 起初以为 Anthropic 员工 Levent Alpöge 与纽约大学教授 Tristan Buckmaster 也解出同一问题并提出联合发布，后来才得知对方实际解决的是受迫欧拉方程，并承认对方是该方向的优先者。整个结果尚待数学界独立审查，属于重大且有争议的声明。

telegram · zaihuapd · 9月9日 00:00

**「背景」** 纳维–斯托克斯方程是描述牛顿流体运动的偏微分方程组；千禧年难题要求证明其三维光滑解在所有时间内都存在且保持光滑，或构造有限时间内爆发的反例。Lean 是可让计算机逐步校验推理的交互式定理证明器，因而“Lean 形式化验证”意味着关键证明步骤经过了机器自动检查。

**「影响」** 若证明在同行复核后成立，将冲击流体偏微分方程理论中关于奇点能否出现的长期结论，并成为 AI 辅助形式化数学的标志性案例；但目前外界只能依赖 OpenAI 的公开声明，实际影响仍取决于独立验证结果。

**「社区讨论」** 评论区更多在讨论争议与激励问题，而非证明内容本身：有评论引用陶哲轩的观察，担心“他人正在研究某问题”的传闻会引发大规模 AI 工程抢先完成，进而抑制研究人员公开分享方向；也有用户质疑该结果是否建立在他人已有工作和提示之上，并对“不到两周训练的内部模型在数学上两倍于 Astra”的说法表示难以置信。另有评论提醒，自然科学研究不是纯计算问题，物理世界的复杂度不能简单化为算力。

**标签**: `#OpenAI`, `#Navier-Stokes`, `#formal verification`, `#AI for mathematics`, `#fluid dynamics`

---

<a id="item-tech-news-2"></a>
### [AlphaGenome Atlas：人类 DNA 全单碱基变化预测图谱](https://blog.google/innovation-and-ai/models-and-research/google-deepmind/alphagenome-atlas/) ⭐️ 9.0/10

Google DeepMind 推出了 AlphaGenome Atlas，这是一张高分辨率预测图谱，覆盖人类基因组中每一个可能的单字母 DNA 变化（即所有可能的单碱基突变）。该图谱用于帮助研究者理解遗传变异如何影响基因表达与疾病风险，尤其涵盖了非编码 DNA 区域，因此具有重要的遗传学和生物医学研究价值。该工具已向科学界开放，可经 Google DeepMind 的专门网页访问。

hackernews · utiiiD · 9月8日 14:55 · [社区讨论](https://news.ycombinator.com/item?id=49611251)

**「背景」** AlphaGenome Atlas 是 Google DeepMind 发布的基因组学资源，基于 AlphaGenome AI 模型预计算人类基因组中所有约 90 亿种可能单核苷酸变异（SNV）的调控影响，数据规模达 1 PB。传统方法通常只关注编码区或已知致病位点，而该图谱覆盖包括非编码 DNA 在内的全基因组，并通过 AlphaGenome Variant Impact \(AVI\) 分数帮助研究者快速定位高影响变异。该发布延续了 AlphaFold 等 AI 驱动生物学工具的思路。

**「影响」** 由于 Google DeepMind 把约 90 亿个单核苷酸变异（SNV）的分子效应预测和 AVI 评分做成开放数据库，遗传学和基因组学研究者可以直接查询全基因组范围内的变异效应，而无需自行运行模型，这有望降低致病性变异筛选和遗传疾病研究的前期计算门槛。Scientific American 也指出，该数据库可能简化多种疾病的遗传学研究。

**「社区讨论」** 评论者中有人询问该图谱是否可用于 23andMe 基因组数据以发现致病突变，也有人提醒访问时无需填写机构隶属关系。另有讨论指出，DeepMind 此前的一些生物学模型并未在所有领域产生同等持久影响，并有人关注该图谱对启动子序列等调控区域的覆盖细节。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepmind.google/blog/alphagenome-atlas-a-predictive-map-of-every-possible-dna-letter-change-in-the-human-genome/">AlphaGenome Atlas: Molecular predictions for 9 Billion human ...</a></li>
<li><a href="https://deepmind.google.com/science/alphagenome/atlas">AlphaGenome - deepmind.google.com</a></li>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/google-deepmind/alphagenome-atlas/">AlphaGenome Atlas: a high-resolution map of human DNA</a></li>
<li><a href="https://deepmind.google/blog/alphagenome-atlas-a-predictive-map-of-every-possible-dna-letter-change-in-the-human-genome/">AlphaGenome Atlas : Molecular predictions for... — Google DeepMind</a></li>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/google-deepmind/alphagenome-atlas/">Introducing AlphaGenome Atlas</a></li>
<li><a href="https://www.scientificamerican.com/article/new-google-deepmind-alphagenome-atlas-could-transform-our-understanding-of-genetic-diseases/">New Google DeepMind atlas could transform our... | Scientific American</a></li>

</ul>
</details>

**标签**: `#artificial-intelligence`, `#genomics`, `#deepmind`, `#biotech`, `#scientific-research`

---

<a id="item-tech-news-3"></a>
### [数学家指控 OpenAI 窃取纳维-斯托克斯研究思路](https://cims.nyu.edu/~tristanb/statement.pdf) ⭐️ 8.0/10

数学家 Tristan Buckmaster 发布声明，指控 OpenAI 与 Anthropic 围绕纳维-斯托克斯问题研究存在不当行为；声明以 PDF 形式发布，具体内容未在条目中完整给出。根据社区转述，Buckmaster 与在 Anthropic 工作的 Levent Alpöge 于 8 月 15 日声称在不可压缩多孔介质、Boussinesq 与三维不可压缩欧拉方程的有限时间爆破等问题上取得进展，并称证明了与千禧年大奖问题相似但非千禧年版本的纳维-斯托克斯问题。OpenAI 承认无法排除用户使用其产品后产生的去标识化数据帮助改进模型，这成为争议核心。该事件牵涉顶尖数学家、主要 AI 实验室以及数学证明归属，引发关于 AI 研究完整性与职业威胁的广泛讨论。

hackernews · procedurecall · 9月8日 05:42 · [社区讨论](https://news.ycombinator.com/item?id=49605915)

**「背景」** Navier-Stokes 方程是描述流体运动的核心偏微分方程组；其三维情形下解是否会在有限时间内失去光滑性（即产生“有限时间爆破”）是 Clay 研究所悬赏百万美元的七个千禧年问题之一。2026 年 9 月，纽约大学数学家 Tristan Buckmaster 与 Anthropic 员工 Levent Alpöge 发布了与这一问题密切相关的预印本，证明了在光滑外力作用下，不可压缩多孔介质方程、二维 Boussinesq 系统以及三维不可压缩 Euler 方程可发生有限时间爆破。这些结果虽不直接等同于完整解决千禧年 Navier-Stokes 问题，但为相关途径提供了重要进展。OpenAI 随后表示，其相关努力始于 9 月 1 日，在听到一则传闻后与 Alpöge 和 Buckmaster 的工作联系起来，由此引发了两家 AI 实验室人员之间的争议。

**「影响」** 最直接的后果是 Buckmaster 和 Alpöge 的研究成果与职业处境被卷入 OpenAI/Anthropic 数据处理和模型训练的争议；在 OpenAI 自身也无法排除相关数据影响的情况下，研究者的优先权和学术声誉面临不确定性。具体影响仍需进一步证据才能判断。

**「社区讨论」** 评论普遍聚焦 OpenAI 关于“无法排除用户去标识化数据帮助改进模型”的表态，并质疑其是否使用了研究者的工作训练模型。多名评论者提到 OpenAI 曾以“毁掉职业”等话术施压，有人将此事视为学界长期竞争被 AI 放大，也有人认为这是对世界级研究者的窃取与威胁。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thenextweb.com/news/openai-navier-stokes-claim-verification-credit">The mathematicians published machine-checkable proofs. OpenAI ...</a></li>
<li><a href="https://gadgetsnow.indiatimes.com/tech-news/navier-stokes-holds-as-openai-and-anthropic-staff-clash/articleshow/133935320.cms">Navier - Stokes Holds As OpenAI And Anthropic Staff Clash</a></li>
<li><a href="https://qz.com/openai-ai-navier-stokes-millennium-prize-math-090826">OpenAI AI solves Navier - Stokes Millennium Prize Problem</a></li>

</ul>
</details>

**标签**: `#Navier-Stokes`, `#AI research`, `#research integrity`, `#OpenAI`, `#mathematics`

---

<a id="item-tech-news-4"></a>
### [陶哲轩警告：AI 可能耗尽开放数学问题并损害开放科学](https://simonwillison.net/2026/Sep/9/terence-tao/) ⭐️ 8.0/10

数学家陶哲轩（Terence Tao）在 Mathstodon 上发文警告，人工智能驱动的努力正在以不可再生的方式开采“良好且富有成果的开放问题”，可能导致这些问题变得稀缺。他指出，仅是某人正在研究某个问题的传闻，就可能触发大量 AI 辅助努力去“夷平”该问题，使其在原始研究项目充分发挥潜力之前就被解决。这样的激励机制可能促使研究者不再向更广泛社区分享有前景的研究方向，从而逆转长达数百年的开放科学传统，并对该领域的长期发展造成严重损害。这一评论并非新的技术成果，而是对 AI 时代研究文化与激励结构的警示。

rss · Simon Willison · 9月9日 00:20

**「背景」** 陶哲轩（Terence Tao）是著名数学家，曾获菲尔兹奖和数学突破奖，研究领域涵盖流体动力学、数学物理等。传统上，数学中的开放问题可以保持数十年甚至数百年未被解决，而研究者通常愿意公开分享有价值的研究方向，以促进合作和学科进步。他担心人工智能驱动的自动化研究可能改变这种长期形成的开放科学传统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=HUkBz-cdB-k">Terence Tao : Hardest Problems in Mathematics, Physics... - YouTube</a></li>
<li><a href="https://www.newscientist.com/article/2583307-why-mathematician-terence-tao-thinks-ai-must-spark-a-rapid-revolution/">Why mathematician Terence Tao thinks AI must spark... | New Scientist</a></li>

</ul>
</details>

**标签**: `#ai-ethics`, `#mathematics`, `#open-science`, `#research-incentives`, `#artificial-intelligence`

---

<a id="item-tech-news-5"></a>
### [OpenAI 发布 ChatGPT Images 2.5 与两个新 API 模型](https://simonwillison.net/2026/Sep/8/introducing-chatgpt-images-25/) ⭐️ 8.0/10

OpenAI 宣布推出 ChatGPT Images 2.5，称其图像生成模型已在 ChatGPT Images 和 API 的 GPT-Image 模型中被用于生成超过 30 亿张图像。此次更新提升了多轮对话中的指令遵循能力、响应速度，并更好地保留参考照片中的主体。API 中新增两个模型 ID：gpt-image-2.5-sunburst 和 gpt-image-2.5-flare，官方建议在编辑精度要求高的流程中使用 Sunburst，在快速高质量日常生成中使用 Flare。Simon Willison 已将其 openai\_image.py 命令行工具升级为支持传入一张或多张参考图像，并演示了利用 sunburst 模型在图表中添加卡通浣熊科学家的示例。

rss · Simon Willison · 9月8日 22:46

**「背景」** OpenAI 的图像生成模型此前通过 ChatGPT 和 API 提供通用功能，但用户在多次编辑、保持人物或物体一致性方面常遇到困难。此次 2.5 版本的核心改进正是围绕多轮指令理解、响应速度和参考图像主体保留展开，并通过两个新 API 模型 ID 提供不同优化方向的选项。

**「影响」** 依赖 OpenAI 图像 API 的开发者现在可以选用 gpt-image-2.5-sunburst 或 gpt-image-2.5-flare 来获得更强的指令跟随和参考图像主体保留能力，同时可通过传入参考图像实现更可控的图像编辑。官方尚未公布基准测试数据或具体性能对比，因此实际提升幅度仍有待验证。

**标签**: `#OpenAI`, `#image generation`, `#AI models`, `#API`

---

<a id="item-tech-news-6"></a>
### [NeurIPS 用 AI 检测器误拒 178 篇论文](https://www.reddit.com/r/MachineLearning/comments/1wakf62/neurips_deskrejected_178_papers_for_being/) ⭐️ 8.0/10

NeurIPS Position Paper Track 使用专有 AI 检测器 Pangram，在未经人工评审且没有申诉渠道的情况下，将 178 篇论文桌面拒稿，占该轨道投稿的 18.4%。独立研究者把三位轨道主席近期的论文送入同一检测器，结果显示 AI 标记率在 24% 到 69% 之间，意味着按该规则他们自己也面临拒稿风险。Pangram 最初标记了该轨道 42.7% 的投稿，组织者随后缩小文本窗口才将标记率降至 12.7%。22 篇论文因为检测得分高于 0.5 且作者否认使用 AI 而被拒，相当于用黑箱分数认定作者说谎。一项斯坦福研究显示 61.22% 的人类撰写的 TOEFL 作文会被误判为 AI，而 NeurIPS 未公布人口统计学校准数据，因此非英语母语研究者的风险尤其突出。

reddit · r/MachineLearning · /u/tughanbulut · 9月8日 10:19

**「背景」** NeurIPS 是机器学习领域的顶级会议，其 Position Paper Track 接收立场鲜明或综述性的观点论文。桌面拒稿是在送审前因不符合政策直接退回稿件，本次拒稿理由是“疑似 AI 生成”，而检测依赖商业黑箱工具 Pangram，且没有人工复核或申诉机制。AI 检测器通常基于文本统计特征打分，容易对结构规整的非母语英文产生误报。

**「影响」** 178 位被拒作者失去了本次 NeurIPS 的评审机会且无法申诉，但他们并未被列入黑名单，仍可将论文转投 ICLR 或 ICML；对于非英语母语研究者，本次政策可能造成系统性误拒，却缺乏公开的误报校准数据来保障公平。

**标签**: `#NeurIPS`, `#AI detection`, `#research ethics`, `#ML conference`, `#publication policy`

---

<a id="item-tech-news-7"></a>
### [ASML 与台积电合作推进 High NA EUV 采用 12 英寸光掩模](https://www.nrc.nl/nieuws/2026/09/08/asml-gaat-samenwerken-met-taiwanese-chipgigant-tsmc-om-zijn-nieuwste-chipmachines-te-upgraden-a4936073) ⭐️ 8.0/10

ASML 与台积电于 9 月 7 日宣布产业合作，推动 High NA EUV 光刻从现有 6 英寸光掩模转向 12 英寸规格，旨在提高设备生产率、降低芯片制造成本并减少拼接限制。计划于 2031 年建立 12 英寸光掩模试产线，2033 年将相关系统用于先进制程量产；台积电则拟自 2030 年起将 High NA 用于先进节点大规模制造。这一路线图将影响未来芯片制造的成本与生产效率，但商业化落地仍需多年。

telegram · zaihuapd · 9月8日 06:55

**「背景」** High NA EUV（高数值孔径极紫外光刻）是 ASML 面向新一代先进制程的光刻技术，但当前使用的 6 英寸光掩模限制了曝光面积和产率。光掩模是刻有电路图案的母版，EUV 设备通过它把图案转印到晶圆；改用 12 英寸大尺寸掩模可减少拼接、提高生产率并降低单位制造成本。为此，ASML 与台积电于 2026 年 9 月 7 日发起行业合作，目标是 2031 年建立试产线、2033 年用于先进节点量产，台积电并拟自 2030 年起将 High NA 用于大规模制造。

**「影响」** 对采用 High NA EUV 的芯片制造商而言，12 英寸光掩模的推进提供了明确的升级时间表，并有望带来生产率与成本优势，但实际量产影响要到 2030 年代初才会显现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.asml.com/en/news/press-releases/2026/tsmc-and-asml-announce-industry-transition-to-large-format-photomasks-for-high-na-euv">TSMC and ASML Announce Initiative to Pioneer Industry ...</a></li>
<li><a href="https://tbreak.com/tsmc-asml-12-inch-photomasks-euv/">TSMC and ASML target 12-inch photomasks for High NA EUV</a></li>
<li><a href="https://www.electronicsweekly.com/news/business/asml-and-tsmc-to-lead-transition-to-12-inch-photomasks-for-high-na-euv-2026-09/">ASML and TSMC to lead transition to 12-inch photomasks for ...</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#EUV lithography`, `#ASML`, `#TSMC`, `#hardware`

---

<a id="item-tech-news-8"></a>
### [Meta 发布个人 AI 智能体 Muse](https://ai.meta.com/muse/) ⭐️ 7.0/10

Meta 发布了名为 Muse 的个人 AI 智能体，官方入口为 ai.meta.com/muse。目前页面本身提供的技术细节有限，但在 Hacker News 引发热议。Meta AI 的 David Singleton 在 X 上介绍了其针对提示注入的分层防御设计，包括让模型学习识别与抵制提示注入、对来自不可信来源的内容做标记、通过确定性代码检查结果，以及在智能体无法触达的位置运行分类器。评论中有用户计划用它从 Facebook 群组抓取 JSON 数据，也有人表示不信任 Meta，宁愿自己构建智能体。总体而言，Muse 的定位、安全设计和隐私影响仍是社区关注的重点。

hackernews · yks · 9月8日 19:25 · [社区讨论](https://news.ycombinator.com/item?id=49615537)

**「背景」** Meta 于 2026 年 9 月发布了 Muse，号称“全球首款个人 AI 代理”，基于首席 AI 官 Alexandr Wang 领导下开发的最新模型构建，目前正在美国面向 iOS、Android 及 muse.ai 网页端逐步推出。Muse 被 Meta CEO 马克·扎克伯格视为长期开发的关键一步，强调安全与隐私，其安全设计包括分层防御提示注入：模型训练识别并抵抗注入、对不可信来源内容进行标记、确定性代码检查结果，以及在代理无法触及的位置运行分类器集成。

**「社区讨论」** Hacker News 评论普遍认为 Meta 意在争取普通大众用户，这与其庞大的现有用户基础相符。David Singleton 关于提示注入安全设计的帖子被引用，缓解了部分担忧；同时，有用户希望用 Muse 完成如抓取 Facebook 群组数据等实际任务，但另一些用户明确表示不愿将掌握大量个人数据的智能体交给 Meta，担心数据收集和隐私风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://about.fb.com/news/2026/09/introducing-muse-personal-ai-agent/">Introducing Muse : The World’s First Personal AI Agent Built for...</a></li>
<li><a href="https://www.axios.com/2026/09/08/meta-debuts-muse-personal-ai-agent">Meta debuts Muse personal AI agent</a></li>
<li><a href="https://www.bnnbloomberg.ca/business/company-news/2026/09/08/meta-launches-personal-ai-agent-muse-emphasizes-safety-and-privacy/">Meta launches Muse , personal AI agent emphasizing safety &amp; privacy</a></li>

</ul>
</details>

**标签**: `#Meta`, `#AI agents`, `#consumer AI`, `#prompt injection`, `#technology industry`

---

<a id="item-tech-news-9"></a>
### [Qwen3.8 27B 量化基准：4-bit 可用，1-bit 明显失效](https://quesma.com/blog/qwen38-27b-quantizations-benchmarked/) ⭐️ 7.0/10

针对 Qwen3.8 27B 的量化基准测试显示，模型在 4-bit 量化下仍能保持较好的任务质量，2-bit 水平出现一定下降，而 1-bit 量化会带来严重的性能退化。该测试为本地部署时选择量化等级提供了实际参考，表明在大多数使用场景中 4-bit 是在显存占用与模型质量之间较为稳妥的折衷。社区评论指出，文章将置信区间解释为运行波动的做法并不恰当，并猜测长思考模式可能部分抵消了量化造成的概率分布偏移。测试还缺少 Q3 中间档、KV cache 量化等对中端显卡和长上下文场景具有实际意义的数据。

hackernews · stared · 9月8日 14:49 · [社区讨论](https://news.ycombinator.com/item?id=49611128)

**「背景」** 模型量化是一种有损压缩技术，通过降低权重精度来减少显存占用和推理成本，通常可在部署时用 4-bit 等低比特版本运行原本较大的模型。Qwen3.8 27B 的 GGUF 量化版本由 Unsloth 发布在 Hugging Face 上，社区和评测文章常对比不同比特数下的质量损失。Quesma 的基准测试表明，该模型在 4-bit 附近质量基本保持，而 1-bit 量化会严重退化，例如在 GPQA Diamond 上接近随机水平。

**「影响」** 对于通过本地硬件部署 Qwen3.8 27B 的开发者，这项结果意味着 4-bit 量化是当前较合理的选择，而 1-bit 量化在实际使用中基本不具备可用性；不过该结论来自单一测试且其方法学受到社区质疑，决策时仍应结合自身任务验证。

**「社区讨论」** 社区评论大多认可 4-bit 与更高量化之间差距不大的现象，并推测模型通过延长思考时间来补偿量化误差；但也有用户批评作者把置信区间误当成运行波动，同时指出测试忽略了 Q3 档位和 KV cache 量化，以及不清楚是否适合在个人电脑上直接运行，希望看到针对中低端显卡和长上下文的补充实验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://quesma.com/blog/qwen38-27b-quantizations-benchmarked/">Benchmarking Qwen3.8 27B quantizations: 4-bit holds up, 1-bit collapses - Quesma Blog</a></li>
<li><a href="https://northflank.com/blog/qwen3-8-27b-performance-benchmarks-gpu-requirements-and-how-to-run-it">Qwen3.8-27B: Performance, benchmarks, GPU requirements &amp; how to run it | Blog — Northflank</a></li>

</ul>
</details>

**标签**: `#quantization`, `#LLM benchmarking`, `#Qwen`, `#model deployment`, `#AI inference`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [报告：加密货币平台一年多损失超 36 亿美元，多数曾做安全审计](https://www.cnbc.com/2026/09/08/crypto-platforms-lost-billions-to-cyberattacks-many-even-after-audits.html) ⭐️ 7.0/10

加密货币数据网站 CoinGecko 在 8 月 27 日发布的报告显示，2025 年 1 月至 2026 年 7 月，加密货币平台因网络攻击和私钥（资金访问口令）被盗共损失超过 36.3 亿美元；其中约 88%的被盗资金来自已完成独立安全审计的平台。约 60%的受影响平台也完成过审计，说明安全审计并未能防止多数攻击。

rss · CNBC Finance · 9月8日 08:16

**「背景」** 报告称，多数攻击发生在安全审计通常不覆盖的环节。Bybit 是损失最大的平台，2025 年 2 月遭窃 14 亿美元，区块链分析公司 Elliptic 认为该事件与朝鲜有关。

**标签**: `#cryptocurrency`, `#cybersecurity`, `#market losses`, `#security audits`, `#hacking`

---

<a id="item-finance-news-2"></a>
### [上海 10 月起生育医疗费用新政：参保职工合规费用不再需个人自付](https://mp.weixin.qq.com/s/jORA1qJsrSWa6VQaoM-b4Q) ⭐️ 7.0/10

上海宣布自 10 月 1 日起实施生育医疗费用新政，参保职工产前检查和住院分娩中政策范围内的合规费用将实现个人“无自付”；其中产前检查先使用每人 4500 元的补贴额度，额度用完后由生育保险全额支付。

telegram · zaihuapd · 9月8日 13:26

**「背景」** 新政也适用于参加居民医保的孕产妇和参加职工医保的男职工的未就业配偶，异地生育按相同标准结算；4500 元补贴如未用完，可在产后 42 天复查后申领余额。

**标签**: `#Shanghai`, `#maternity insurance`, `#healthcare policy`, `#childbirth benefits`, `#social insurance`

---