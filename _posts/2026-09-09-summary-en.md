---
layout: default
title: "Horizon Summary: 2026-09-09 (EN)"
date: 2026-09-09
lang: en
---

> From 43 items, 11 important content pieces were selected

---

**Technology News**
1. [OpenAI claims Lean-checked AI proof resolves Navier-Stokes millennium problem](#item-tech-news-1) ⭐️ 10.0/10
2. [AlphaGenome Atlas Maps Every Possible Human DNA Letter Change](#item-tech-news-2) ⭐️ 9.0/10
3. [Buckmaster statement in OpenAI/Anthropic Navier-Stokes dispute](#item-tech-news-3) ⭐️ 8.0/10
4. [Terence Tao Warns AI Could Exhaust Open Math Problems](#item-tech-news-4) ⭐️ 8.0/10
5. [OpenAI&\#x27;s ChatGPT Images 2.5 Adds Precision and Speed](#item-tech-news-5) ⭐️ 8.0/10
6. [NeurIPS position-paper track desk-rejected 178 papers via flawed AI detector](#item-tech-news-6) ⭐️ 8.0/10
7. [ASML and TSMC shift High NA EUV to 12-inch photomasks](#item-tech-news-7) ⭐️ 8.0/10
8. [Muse – Meta’s personal AI agent](#item-tech-news-8) ⭐️ 7.0/10
9. [Qwen3.8 27B: 4-bit quantization holds quality, 1-bit collapses](#item-tech-news-9) ⭐️ 7.0/10

**Financial News**
1. [Crypto platforms lose over $3.63 billion to cyberattacks despite security audits](#item-finance-news-1) ⭐️ 7.0/10
2. [Shanghai to Fully Reimburse Covered Maternity Medical Costs From Oct 1](#item-finance-news-2) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [OpenAI claims Lean-checked AI proof resolves Navier-Stokes millennium problem](https://openai.com/index/navier-stokes-solution/) ⭐️ 10.0/10

OpenAI announced that an internal AI system has produced a proof of the Navier-Stokes existence and smoothness problem, one of the Clay Millennium Prize Problems, concluding that initially smooth fluid dynamics can develop a singularity in finite time. The company is sharing both a paper and a Lean formal verification of the result; the work reportedly involved about 10,000 parallel agents, 2.7 million messages, and roughly 130 billion output tokens. OpenAI says it will not seek the Millennium Prize. OpenAI initially believed Anthropic&\#x27;s Levent Alpöge and New York University&\#x27;s Tristan Buckmaster had independently solved the same problem and proposed a joint announcement, but later learned their work concerned the forced Euler equations and acknowledged the pair&\#x27;s priority. The announcement is notable for using AI and formal verification at unprecedented scale on a major open problem, although the proof still awaits independent mathematical review.

telegram · zaihuapd · Sep 9, 00:00

**「Background」** The Navier-Stokes existence and smoothness problem is one of the seven $1 million Millennium Prize Problems established by the Clay Mathematics Institute. It asks whether smooth initial conditions for the equations describing fluid motion always evolve into smooth solutions for all time, or whether singularities can form. Lean is an interactive proof assistant that mechanically verifies mathematical arguments, so OpenAI&\#x27;s claim pairs a conventional proof narrative with machine-checked formalization.

**「Impact」** If the claim is correct, it establishes a finite-time blow-up result for the Navier-Stokes equations and provides a high-profile demonstration that AI-generated mathematics can be paired with full formal verification. Until independent review confirms both the mathematical argument and the match between the paper and the Lean code, the concrete near-term effect is an urgent verification effort around a strongly disputed Millennium Prize claim.

**「Community Discussion」** Community reactions combined admiration with suspicion. Terence Tao said the episode illustrates that even the rumor of someone working on a problem can trigger a &\#x27;massive amount of AI-powered effort&\#x27; to flatten it before the original research reaches its full potential; Hacker News commenters also alleged that the proof may have relied on Buckmaster and Alpöge&\#x27;s actual work and prompts, while another noted the &\#x27;astounding&\#x27; claim that an internal model trained for less than two weeks is more than twice as capable in mathematics as Astra.

**Tags**: `#OpenAI`, `#Navier-Stokes`, `#formal verification`, `#AI for mathematics`, `#fluid dynamics`

---

<a id="item-tech-news-2"></a>
### [AlphaGenome Atlas Maps Every Possible Human DNA Letter Change](https://blog.google/innovation-and-ai/models-and-research/google-deepmind/alphagenome-atlas/) ⭐️ 9.0/10

Google DeepMind has introduced AlphaGenome Atlas, a predictive map of every possible single-letter DNA change in the human genome. The tool is positioned as a high-resolution resource for studying both coding and non-coding DNA, making it broadly relevant to genetics and biomedical research. The Atlas is available online through a DeepMind science page, and early access appears to require only a brief affiliation form. This release extends DeepMind&\#x27;s AI-for-science portfolio with a genome-scale predictive resource, although the supplied material does not detail the underlying model or validation metrics.

hackernews · utiiiD · Sep 8, 14:55 · [Discussion](https://news.ycombinator.com/item?id=49611251)

**「Background」** Single nucleotide variants are DNA changes in which one letter of the genetic code is swapped for another, and most occur in non-coding regions where they can influence gene regulation rather than directly altering proteins. AlphaGenome is Google DeepMind&\#x27;s unifying model for deciphering DNA function, and AlphaGenome Atlas is the resulting database that pre-calculates the regulatory impact of all 9 billion possible single-letter changes in the human genome, released as a 1-petabyte dataset alongside the AlphaGenome Variant Impact \(AVI\) score.

**「Impact」** AlphaGenome Atlas gives researchers direct access to precomputed molecular predictions and AVI scores for 9 billion single-nucleotide variants, which can streamline variant interpretation and disease-focused genetics research by removing the need to run large prediction models themselves. The impact is most concrete for scientists studying non-coding DNA, where experimental interpretation remains difficult, though the practical value still depends on independent validation of the model&\#x27;s accuracy.

**「Community discussion」** Commenters raised questions about whether the Atlas accounts for promoter sequences and whether it can be applied to personal 23andMe genome data to find pathogenic mutations. Others noted that access was straightforward after entering no affiliation, shared introductory videos, and expressed cautious interest in how persistent DeepMind biology models beyond AlphaFold will prove to be.

<details><summary>References</summary>
<ul>
<li><a href="https://deepmind.google/blog/alphagenome-atlas-a-predictive-map-of-every-possible-dna-letter-change-in-the-human-genome/">AlphaGenome Atlas: Molecular predictions for 9 Billion human ...</a></li>
<li><a href="https://deepmind.google.com/science/alphagenome/atlas">AlphaGenome - deepmind.google.com</a></li>
<li><a href="https://deepmind.google/blog/alphagenome-atlas-a-predictive-map-of-every-possible-dna-letter-change-in-the-human-genome/">AlphaGenome Atlas : Molecular predictions for... — Google DeepMind</a></li>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/google-deepmind/alphagenome-atlas/">Introducing AlphaGenome Atlas</a></li>
<li><a href="https://www.scientificamerican.com/article/new-google-deepmind-alphagenome-atlas-could-transform-our-understanding-of-genetic-diseases/">New Google DeepMind atlas could transform our... | Scientific American</a></li>

</ul>
</details>

**Tags**: `#artificial-intelligence`, `#genomics`, `#deepmind`, `#biotech`, `#scientific-research`

---

<a id="item-tech-news-3"></a>
### [Buckmaster statement in OpenAI/Anthropic Navier-Stokes dispute](https://cims.nyu.edu/~tristanb/statement.pdf) ⭐️ 8.0/10

A statement by mathematician Tristan Buckmaster, hosted on New York University&\#x27;s CIMS site, is at the center of a controversy involving OpenAI and Anthropic over Navier-Stokes-related research. Community comments describe an Aug. 15 result by Buckmaster and Levent Alpöge making progress on finite-time blowup with smooth forcing for incompressible porous media, Boussinesq, and 3D incompressible Euler, while noting they did not prove the $1 million Millennium Prize problem but reportedly claimed a proof for a similar non-Millennium Navier-Stokes problem that could help lead the way. Alpöge reportedly works at Anthropic, and one comment quotes OpenAI saying it &quot;cannot rule out that de-identified data derived from their usage of our products helped improve our models.&quot; Another comment quotes Buckmaster describing declined offers and a career-related threat when he said he would go public, with the commenter asserting that OpenAI &quot;looked at user data, stole world class researchers&\#x27; work, and then tried to threaten those researchers.&quot; The attached PDF is characterized as a statement rather than a technical preprint, and its full contents were not available in the supplied item.

hackernews · procedurecall · Sep 8, 05:42 · [Discussion](https://news.ycombinator.com/item?id=49605915)

**「Background」** The Navier-Stokes equations model fluid flow, and one of the Clay Millennium Prize problems asks whether smooth solutions can persist forever from smooth initial data or whether singularities, called blowup, can form in finite time. Tristan Buckmaster of NYU and Levent Alpöge of Anthropic posted preprints proving finite-time blowup for related but not identical systems—incompressible porous media, 2D Boussinesq, and 3D incompressible Euler—under smooth external forcing. That distinction matters because proved blowup for forced variants does not settle the unforced Clay problem, though OpenAI later claimed an AI-assisted approach to the full Navier-Stokes problem, prompting the controversy around Buckmaster&\#x27;s statement.

**「Community discussion」** Commenters largely treat the episode as a misconduct story: one says OpenAI &quot;looked at user data, stole world class researchers&\#x27; work, and then tried to threaten those researchers,&quot; and another quotes Buckmaster recounting a threat that going public would ruin his career. A more measured comment notes OpenAI&\#x27;s own admission leaves ambiguity about whether Buckmaster&\#x27;s work influenced model training and compares the situation to long-standing academic competition.

<details><summary>References</summary>
<ul>
<li><a href="https://thenextweb.com/news/openai-navier-stokes-claim-verification-credit">The mathematicians published machine-checkable proofs. OpenAI ...</a></li>
<li><a href="https://gadgetsnow.indiatimes.com/tech-news/navier-stokes-holds-as-openai-and-anthropic-staff-clash/articleshow/133935320.cms">Navier - Stokes Holds As OpenAI And Anthropic Staff Clash</a></li>
<li><a href="https://qz.com/openai-ai-navier-stokes-millennium-prize-math-090826">OpenAI AI solves Navier - Stokes Millennium Prize Problem</a></li>

</ul>
</details>

**Tags**: `#Navier-Stokes`, `#AI research`, `#research integrity`, `#OpenAI`, `#mathematics`

---

<a id="item-tech-news-4"></a>
### [Terence Tao Warns AI Could Exhaust Open Math Problems](https://simonwillison.net/2026/Sep/9/terence-tao/) ⭐️ 8.0/10

Terence Tao, posting on Mathstodon, said he recently argued that the supply of good, fruitful open problems in mathematics is now being mined in a non-renewable fashion and could become scarce. He observed that even the rumor of someone working on a problem can trigger a massive amount of AI-powered effort to solve it before the original research project reaches its full potential. Tao warns that the resulting incentives may push researchers to stop sharing promising research directions with the broader community, reversing centuries of open-science tradition and causing serious long-term damage to the field. The remarks were shared by Simon Willison under tags including AI ethics, mathematics, and open science.

rss · Simon Willison · Sep 9, 00:20

**「Background」** Terence Tao is a Fields Medal-winning mathematician known for contributions across many areas including fluid dynamics and number theory. In mathematics, open problems have traditionally been shared openly and may remain unsolved for decades; Tao has recently called for rethinking mathematical practice as AI tools reshape how quickly problems can be tackled.

<details><summary>References</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=HUkBz-cdB-k">Terence Tao : Hardest Problems in Mathematics, Physics... - YouTube</a></li>
<li><a href="https://www.newscientist.com/article/2583307-why-mathematician-terence-tao-thinks-ai-must-spark-a-rapid-revolution/">Why mathematician Terence Tao thinks AI must spark... | New Scientist</a></li>

</ul>
</details>

**Tags**: `#ai-ethics`, `#mathematics`, `#open-science`, `#research-incentives`, `#artificial-intelligence`

---

<a id="item-tech-news-5"></a>
### [OpenAI&\#x27;s ChatGPT Images 2.5 Adds Precision and Speed](https://simonwillison.net/2026/Sep/8/introducing-chatgpt-images-25/) ⭐️ 8.0/10

OpenAI has announced ChatGPT Images 2.5, an update to its widely used image generation models, which have generated more than 3 billion images across ChatGPT and the GPT-Image API according to OpenAI. The release improves instruction following across multiple turns, generates images faster, and better preserves subjects in reference photos. It introduces two new API model IDs: gpt-image-2.5-sunburst, recommended for editing precision, and gpt-image-2.5-flare, for fast, high-quality everyday image generation. Developer Simon Willison promptly updated his openai\_image.py CLI tool to accept one or more reference images, demonstrating the workflow by adding a raccoon scientist to an existing chart.

rss · Simon Willison · Sep 8, 22:46

**「Background」** OpenAI&\#x27;s GPT-Image models already supported text-to-image generation and image editing through the API, but capabilities such as maintaining a subject across edits and following detailed multi-turn instructions were more limited. This update refines those abilities while also differentiating model choices for precision-focused editing versus speed-oriented generation.

**「Impact」** Developers and API users can now select gpt-image-2.5-sunburst for reference-based editing tasks that demand subject preservation and gpt-image-2.5-flare for faster everyday generation, with community tooling already updated to pass reference images into these new models.

**Tags**: `#OpenAI`, `#image generation`, `#AI models`, `#API`

---

<a id="item-tech-news-6"></a>
### [NeurIPS position-paper track desk-rejected 178 papers via flawed AI detector](https://www.reddit.com/r/MachineLearning/comments/1wakf62/neurips_deskrejected_178_papers_for_being/) ⭐️ 8.0/10

NeurIPS&\#x27;s Position Paper Track used the proprietary Pangram AI detector to desk-reject 178 submissions, reported as 18.4% of the track, without human review or an appeal process. The post reports that Pangram&\#x27;s default setting flagged nearly half of all submissions as 90-100% AI and that organizers reduced the text-window size until the flag rate fell to 12.7%; 22 papers were rejected specifically because they scored above 0.5 while their authors denied AI use. Independent tests using the same detector flagged recent papers by the three track chairs at 24-69%, meaning the chairs would have been at risk under their own enforcement thresholds. No demographic calibration data was provided, and the author cites a Stanford finding that 61.22% of human-written TOEFL essays are falsely flagged as AI, suggesting disproportionate risk for ESL researchers. The author states that rejected papers are not blacklisted and can be resubmitted to ICLR or ICML.

reddit · r/MachineLearning · /u/tughanbulut · Sep 8, 10:19

**「Background」** NeurIPS is a top-tier machine-learning conference, and its Position Paper Track solicits submissions that argue for new directions rather than presenting fully evaluated empirical results. AI-generated-text detectors score how closely prose matches typical large-language-model output, but they are known to produce false positives on formal or non-native English writing, which is why the TOEFL false-positive rate cited here is relevant. Desk rejection normally filters out clearly ineligible submissions before full review, but this case replaced that human screening with an opaque algorithmic score.

**「Impact」** The most concrete harm is that 178 authors lost an unreviewed chance at NeurIPS, while ESL researchers were especially exposed because high AI scores were treated as evidence that authors had lied about AI use. Rejected authors are reportedly not blacklisted and can still resubmit their work to ICLR or ICML.

**Tags**: `#NeurIPS`, `#AI detection`, `#research ethics`, `#ML conference`, `#publication policy`

---

<a id="item-tech-news-7"></a>
### [ASML and TSMC shift High NA EUV to 12-inch photomasks](https://www.nrc.nl/nieuws/2026/09/08/asml-gaat-samenwerken-met-taiwanese-chipgigant-tsmc-om-zijn-nieuwste-chipmachines-te-upgraden-a4936073) ⭐️ 8.0/10

ASML and TSMC announced on Sept. 7 an industry collaboration to move High NA EUV lithography from today&\#x27;s 6-inch photomasks to a 12-inch format, aiming for higher scanner productivity, lower chip manufacturing costs, and fewer stitching constraints. The roadmap targets a 12-inch photomask pilot production line in 2031 and the use of these systems for leading-edge high-volume manufacturing in 2033. TSMC separately plans to use High NA EUV at scale for advanced-node manufacturing starting in 2030, meaning its initial High NA adoption would still rely on the existing 6-inch mask generation. The announcement provides one of the first concrete schedules from the two companies for the industry&\#x27;s expected transition to larger EUV photomasks.

telegram · zaihuapd · Sep 8, 06:55

**「Background」** High NA EUV is the next generation of extreme ultraviolet lithography, which uses 13.5nm wavelength light to pattern chip features. ASML is the main supplier of EUV and High NA EUV machines, and TSMC is a leading chip manufacturer. Current EUV and High NA systems use 6-inch photomasks, but High NA imaging requires smaller fields and more stitching. Moving to 12-inch photomasks would enable larger patterns, improve productivity, and reduce manufacturing cost. The companies announced this industry-wide transition on September 7, 2026, ahead of the SPIE Bacus Conference, aiming for a pilot line in 2031 and production tools with advanced nodes in 2033.

<details><summary>References</summary>
<ul>
<li><a href="https://www.asml.com/en/news/press-releases/2026/tsmc-and-asml-announce-industry-transition-to-large-format-photomasks-for-high-na-euv">TSMC and ASML Announce Initiative to Pioneer Industry ...</a></li>
<li><a href="https://tbreak.com/tsmc-asml-12-inch-photomasks-euv/">TSMC and ASML target 12-inch photomasks for High NA EUV</a></li>
<li><a href="https://www.electronicsweekly.com/news/business/asml-and-tsmc-to-lead-transition-to-12-inch-photomasks-for-high-na-euv-2026-09/">ASML and TSMC to lead transition to 12-inch photomasks for ...</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#EUV lithography`, `#ASML`, `#TSMC`, `#hardware`

---

<a id="item-tech-news-8"></a>
### [Muse – Meta’s personal AI agent](https://ai.meta.com/muse/) ⭐️ 7.0/10

Meta has introduced Muse, a personal AI agent, with a landing page at https://ai.meta.com/muse/. The announcement is significant given Meta&\#x27;s scale and reach in the consumer technology space, though the supplied page contains little technical detail about the agent&\#x27;s capabilities. This move highlights Meta&\#x27;s push toward mainstream AI assistants integrated with its platforms. No specific model, version, or availability details are present in the item.

hackernews · yks · Sep 8, 19:25 · [Discussion](https://news.ycombinator.com/item?id=49615537)

**「Background」** Meta announced Muse, its personal AI agent, in September 2026 as a first step toward what it calls personal superintelligence. It is rolling out in the US on iOS, Android, and muse.ai, and is built on the latest generation of models developed under Meta&\#x27;s chief AI officer Alexandr Wang. The announcement emphasized safety and privacy alongside the agent&\#x27;s capabilities.

**「Community Discussion」** Commenters are split: some argue Meta is aiming at &\#x27;normie-tier&\#x27; users and can win with its large existing base, while others say they would never trust Meta with a personal agent and would rather build their own. Additional comments mention using Muse to extract Facebook group comments as JSON and cite Meta&\#x27;s layered prompt-injection defenses as a security focus.

<details><summary>References</summary>
<ul>
<li><a href="https://about.fb.com/news/2026/09/introducing-muse-personal-ai-agent/">Introducing Muse : The World’s First Personal AI Agent Built for...</a></li>
<li><a href="https://www.axios.com/2026/09/08/meta-debuts-muse-personal-ai-agent">Meta debuts Muse personal AI agent</a></li>
<li><a href="https://www.bnnbloomberg.ca/business/company-news/2026/09/08/meta-launches-personal-ai-agent-muse-emphasizes-safety-and-privacy/">Meta launches Muse , personal AI agent emphasizing safety &amp; privacy</a></li>

</ul>
</details>

**Tags**: `#Meta`, `#AI agents`, `#consumer AI`, `#prompt injection`, `#technology industry`

---

<a id="item-tech-news-9"></a>
### [Qwen3.8 27B: 4-bit quantization holds quality, 1-bit collapses](https://quesma.com/blog/qwen38-27b-quantizations-benchmarked/) ⭐️ 7.0/10

A benchmark of Qwen3.8 27B quantizations, published by quesma.com, found that 4-bit versions preserve model quality nearly as well as higher-bit versions, while 1-bit quantizations severely degrade performance. The results are relevant for AI engineers deciding how aggressively to compress the model for memory-constrained deployment. The benchmark report uses Wilson 95% confidence intervals that it describes as conservative for run-to-run noise, though this interpretation has been challenged by commenters. Overall, the findings suggest 4-bit is a practical quantization point for Qwen3.8 27B, while 1-bit represents a quality cliff.

hackernews · stared · Sep 8, 14:49 · [Discussion](https://news.ycombinator.com/item?id=49611128)

**「Background」** Quantization is a lossy compression technique that reduces the memory needed to store and run a large language model, such as representing weights with fewer bits per parameter. For a 27B-parameter model, 4-bit quantization can substantially lower memory requirements while preserving most benchmark quality, but extremely aggressive 1-bit quantization can push quality down to around random chance, sometimes making longer reasoning counterproductive. The Qwen3.8 27B model discussed here is available as GGUF quantizations from Unsloth on Hugging Face, and previous Quesma benchmarks already ran extensive token generation and GPU time to compare these formats.

**「Community Discussion」** Commenters questioned the statistical use of Wilson confidence intervals for run-to-run noise and suggested that Qwen3.8 27B may compensate for lower quantizations by generating longer thinking traces. They also called for additional benchmarks covering KV-cache quantization and the missing Q3 quality knee relevant to sub-16GB GPUs, while one newcomer asked about safe local execution methods.

<details><summary>References</summary>
<ul>
<li><a href="https://quesma.com/blog/qwen38-27b-quantizations-benchmarked/">Benchmarking Qwen3.8 27B quantizations: 4-bit holds up, 1-bit collapses - Quesma Blog</a></li>
<li><a href="https://northflank.com/blog/qwen3-8-27b-performance-benchmarks-gpu-requirements-and-how-to-run-it">Qwen3.8-27B: Performance, benchmarks, GPU requirements &amp; how to run it | Blog — Northflank</a></li>
<li><a href="https://quesma.com/blog/qwen-quantization-quality/">Do Qwen3.6 27B quantizations break the pelican? - Quesma Blog</a></li>

</ul>
</details>

**Tags**: `#quantization`, `#LLM benchmarking`, `#Qwen`, `#model deployment`, `#AI inference`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Crypto platforms lose over $3.63 billion to cyberattacks despite security audits](https://www.cnbc.com/2026/09/08/crypto-platforms-lost-billions-to-cyberattacks-many-even-after-audits.html) ⭐️ 7.0/10

Cryptocurrency platforms lost more than $3.63 billion to cyberattacks between January 2025 and July 2026, according to crypto market data site CoinGecko. The report says about 88% of the stolen funds went to platforms that had completed independent security audits.

rss · CNBC Finance · Sep 8, 08:16

**「Background」** CoinGecko&\#x27;s report said most attacks targeted areas that standard security audits do not typically cover, such as stolen passkeys.

**Tags**: `#cryptocurrency`, `#cybersecurity`, `#market losses`, `#security audits`, `#hacking`

---

<a id="item-finance-news-2"></a>
### [Shanghai to Fully Reimburse Covered Maternity Medical Costs From Oct 1](https://mp.weixin.qq.com/s/jORA1qJsrSWa6VQaoM-b4Q) ⭐️ 7.0/10

Shanghai announced that from October 1 it will fully reimburse policy-covered maternity medical costs, so compliant childbirth care will no longer require personal out-of-pocket payments; insured workers will first draw on a 4,500-yuan prenatal allowance.

telegram · zaihuapd · Sep 8, 13:26

**「Background」** The policy also covers pregnant women on the resident medical insurance scheme and unemployed spouses of male employees covered by employee medical insurance, and applies at the same standards to births outside Shanghai.

**Tags**: `#Shanghai`, `#maternity insurance`, `#healthcare policy`, `#childbirth benefits`, `#social insurance`

---