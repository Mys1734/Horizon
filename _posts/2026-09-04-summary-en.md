---
layout: default
title: "Horizon Summary: 2026-09-04 (EN)"
date: 2026-09-04
lang: en
---

> From 35 items, 6 important content pieces were selected

---

**Technology News**
1. [OpenAI announces GPT-6 Astra with official system card](#item-tech-news-1) ⭐️ 9.0/10
2. [Porting a 1993 Amiga 68000 Game to Godot With an LLM](#item-tech-news-2) ⭐️ 8.0/10
3. [Audacity 4.0 arrives with new Qt6-based UI](#item-tech-news-3) ⭐️ 8.0/10
4. [US Government Supports OpenAI, Calling AI Training on Copyrighted Works Fair Use](#item-tech-news-4) ⭐️ 8.0/10

**Financial News**
1. [China Accuses G20 Partners of Protectionism Over Export Criticism](#item-finance-news-1) ⭐️ 8.0/10
2. [US considers new tariffs on imported chips to push semiconductor manufacturing back to America](#item-finance-news-2) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [OpenAI announces GPT-6 Astra with official system card](https://openai.com/index/gpt-6-astra/) ⭐️ 9.0/10

OpenAI has announced GPT-6 Astra, a major new version of its model, alongside an official system card published at deploymentsafety.openai.com/gpt-6-astra. The main announcement provides little technical detail and instead points to related community threads, including discussion of GPT-6 Astra&\#x27;s ARC-AGI-3 score and performance on the Artificial Analysis Coding Agent Index. The release represents a landmark major-version step for OpenAI&\#x27;s frontier model line and is the subject of active Hacker News discussion about benchmarks and reasoning harnesses.

hackernews · kibae · Sep 3, 18:41 · [Discussion](https://news.ycombinator.com/item?id=49554643)

**「Background」** OpenAI has released GPT-6 Astra, a major new model that it describes as “the world’s most intelligent and aligned model,” and company president Greg Brockman said the AGI era has started. This release follows OpenAI’s previous frontier models GPT-4 and GPT-5, and it is accompanied by an official system card detailing safety and deployment considerations. Independent coverage reports that OpenAI has begun rolling out the model to ChatGPT and Codex.

**「Community Discussion」** Hacker News commenters are split: some call the reported 99.9% ARC-AGI-3 score impressive but question comparing it with models benchmarked under a different harness, while others argue most non-ARC benchmarks look like modest point updates rather than proof of AGI. Separate criticisms target autonomous shopping demos and note that progress still resembles skill acquisition in François Chollet&\#x27;s sense.

<details><summary>References</summary>
<ul>
<li><a href="https://9to5mac.com/2026/09/03/openai-releasing-major-upgrade-to-chatgpt-and-codex-with-gpt-6-astra-details-here/">OpenAI releasing major upgrade to ChatGPT and Codex... - 9to5Mac</a></li>
<li><a href="https://tech-ish.com/2026/09/03/openai-gpt6-astra-agi-era-launch/">OpenAI launches GPT - 6 Astra and says we are now in the... - tech-ish</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#GPT-6`, `#AI models`, `#large language models`

---

<a id="item-tech-news-2"></a>
### [Porting a 1993 Amiga 68000 Game to Godot With an LLM](https://babyloniantwins.com/blog/porting-a-1993-amiga-game-to-godot/) ⭐️ 8.0/10

A developer published notes on porting the Amiga game he wrote in MC68000 assembly in Baghdad in 1993 to Godot, using the model he calls Claude Fable 5 during a July holiday; the initial port took one evening, while matching the feel and shipping took more weekends. His core verification was to have the model reassemble the code with vasm until producing a binary byte-identical to the original files, aside from a remaining 108-byte mismatch he has not personally verified. The explanation is that his original AsmOne workflow saved memory from a running game, making the shipped binaries a snapshot rather than clean assembler output. He is also releasing the original game for free.

hackernews · rabahs · Sep 3, 14:28 · [Discussion](https://news.ycombinator.com/item?id=49550375)

**「Background」** Classic Amiga games were often written entirely in Motorola 68000 assembly to squeeze performance out of limited hardware. Translating that low-level code to a modern engine such as Godot normally requires extensive manual reverse engineering, and this account demonstrates an LLM-assisted workflow for doing that while preserving the original game&\#x27;s behavior.

**「Impact」** For owners or creators of old self-written games, this provides a repeatable path to produce modern playable ports grounded in exact original binaries; the free release of the original also lets players compare the port against a preserved artifact.

**「Community Discussion」** Commenters shared related experiments, including one who converted a ZX81 memory dump to Go, and praised the pre-Internet assembly work, asking about the author&\#x27;s debugging process and whether &quot;Gods: Into the Wonderful&quot; was an inspiration. Others said they plan to use the same approach on a forgotten game and requested an engineering guide or more details about the tooling the LLM built.

**Tags**: `#LLM-assisted porting`, `#retrocomputing`, `#Amiga`, `#Godot`, `#68000 assembly`

---

<a id="item-tech-news-3"></a>
### [Audacity 4.0 arrives with new Qt6-based UI](https://github.com/audacity/audacity/releases/tag/Audacity-4.0.0) ⭐️ 8.0/10

Audacity 4.0, a major release of the widely used open-source audio editor, was published on GitHub and introduces a new Qt6-based interface. The release attracted substantial Hacker News attention, drawing 1035 points and 232 comments. One user who tried the beta reported that it felt much cleaner and fixed long-standing inconveniences such as clicking noise between clips and project-saving issues. However, other commenters say the release does not address technical problems they have with Linux audio integration, particularly around JACK and PipeWire. The project also continues to face wariness over its relationship with audio.com features.

hackernews · ClydeN · Sep 3, 10:53 · [Discussion](https://news.ycombinator.com/item?id=49548395)

**「Background」** Audacity is one of the most widely used open-source audio editors, but its previous major versions relied on the wxWidgets toolkit and an older, waveform-oriented editing workflow. Muse Group&\#x27;s stewardship of Audacity 3.x also generated community concern over optional telemetry and Audio.com cloud integration, prompting forks such as Tenacity and Sneedacity. Audacity 4.0 replaces wxWidgets with a Qt6 interface built on the framework shared with MuseScore Studio 4, introduces a clip-based editing model, and uses a new .aup4 project format while retaining compatibility with Audacity 3 projects.

**「Impact」** Users who upgrade to Audacity 4.0 will encounter a redesigned Qt6 interface, but at least some seasoned Linux users remain reluctant because their reported JACK/PipeWire workflow issues are still unresolved. The new release may draw in users looking for a fresher UI while failing to win back a vocal segment of the existing community.

**「Community Discussion」** Reaction is mixed: some point to videos explaining the new Qt6 UI and praise the beta experience, while others say Audacity 4.0 still lacks proper persistent JACK client support on Linux. Several commenters also raise continued privacy and trust concerns related to audio.com integrations and ask about alternative forks such as Tenacity and Sneedacity.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linuxcompatible.org/story/audacity-40-beta-4-ships-with-qt6-ui-windows-asio-and-legacy-imports">Audacity 4.0 Beta 4 Ships With Qt6 UI, Windows ASIO, and Legacy Imports</a></li>
<li><a href="https://www.linuxcompatible.org/story/audacity-400-released-complete-qt-rewrite-new-clip-editing-and-aup4-format">Audacity 4.0.0 Released: Complete Qt Rewrite, New Clip Editing, and .aup4 Format</a></li>

</ul>
</details>

**Tags**: `#audacity`, `#open-source`, `#audio-editing`, `#qt6`, `#release`

---

<a id="item-tech-news-4"></a>
### [US Government Supports OpenAI, Calling AI Training on Copyrighted Works Fair Use](https://www.reuters.com/legal/litigation/us-government-backs-openai-new-york-times-copyright-case-2026-09-02/) ⭐️ 8.0/10

The U.S. government filed an amicus brief in Manhattan federal court backing OpenAI in its copyright dispute with The New York Times and other media outlets, arguing that using copyrighted content to train large language models generally qualifies as fair use. This marks the first time the U.S. government has formally taken a position on an AI-training copyright case. The brief is not legally binding, but it could strengthen the defense of OpenAI and other technology companies in similar litigation. The New York Times criticized the government for siding with a few trillion-dollar AI companies at the expense of creators. The newspaper sued OpenAI and Microsoft in 2023, alleging they used millions of its articles without permission to train ChatGPT.

telegram · zaihuapd · Sep 3, 05:45

**「Background」** Fair use is a U.S. copyright doctrine that allows unlicensed use of protected works in certain circumstances, such as commentary, criticism, research, or transformative uses, based on factors like purpose, nature, amount used, and market impact. The New York Times&\#x27; 2023 lawsuit against OpenAI and Microsoft is part of broader litigation by authors and media companies over whether copying copyrighted material to train AI models should be considered fair use or infringement.

**「Impact」** The brief boosts OpenAI&\#x27;s legal position in the New York Times case and similar AI-training copyright disputes by putting the federal government&\#x27;s fair-use interpretation on the record, though judges are not bound by the administration&\#x27;s view.

**Tags**: `#AI`, `#copyright`, `#legal`, `#OpenAI`, `#fair use`

---

## Financial News

<a id="item-finance-news-1"></a>
### [China Accuses G20 Partners of Protectionism Over Export Criticism](https://www.cnbc.com/2026/09/03/china-g20-exports-trade.html) ⭐️ 8.0/10

China&\#x27;s Commerce Ministry accused other G20 members of “promoting protectionism” after they criticized economies that rely heavily on exports, saying such criticism is “an excuse to pressure and restrict China.” U.S. Treasury Secretary Scott Bessent had said 19 of the G20 members agreed to address export-driven “imbalances,” with China the only member to dissent.

rss · CNBC Finance · Sep 3, 11:12

**「Background」** The pushback came during a weekly press conference as China faces U.S. sanctions threats against entities helping Iran, French legislation aimed at low-priced Chinese e-commerce companies such as Temu, and EU pressure for &quot;concrete results&quot; in trade talks by October.

**「Impact」** China warned France to halt the e-commerce law or face “necessary measures,” and demanded the U.S. lift sanctions, signaling possible retaliation that could affect Chinese exporters and increase trade friction with the EU ahead of its October deadline.

**Tags**: `#China trade`, `#G20`, `#US-China relations`, `#EU tariffs`, `#sanctions`

---

<a id="item-finance-news-2"></a>
### [US considers new tariffs on imported chips to push semiconductor manufacturing back to America](https://www.bloomberg.com/news/videos/2026-09-03/trump-to-levy-more-chip-tariffs-to-boost-manufacturing-video) ⭐️ 7.0/10

US Commerce Secretary Howard Lutnick said the Trump administration is considering new tariffs on imported semiconductors — and possibly on products containing them, such as data center servers and consumer electronics — to encourage chip manufacturing in the US. The administration is also considering tariff relief for companies that build manufacturing capacity in America, but no final plan, tariff rates, or timeline have been announced.

telegram · zaihuapd · Sep 3, 07:00

**「Background」** The U.S. Commerce Department launched a Section 232 investigation into semiconductor imports in April 2025, and the Trump administration imposed 25% tariffs on a narrow range of advanced computing chips in January 2026. In August 2026, a separate 15% tariff on polysilicon and its derivatives was set, with minimum price floors to follow in December. The latest statements from Commerce Secretary Howard Lutnick indicate the administration is considering adding more semiconductor tariffs and is weighing exemptions for companies that build or expand U.S. manufacturing, but no final plan has been announced.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tariffs_in_the_second_Trump_administration">Tariffs in the second Trump administration - Wikipedia</a></li>
<li><a href="https://cryptobriefing.com/trump-tariffs-imported-semiconductors-2026/">Trump administration moves to expand tariffs on imported semiconductors</a></li>

</ul>
</details>

**Tags**: `#半导体关税`, `#美国贸易政策`, `#芯片供应链`, `#制造业回流`, `#AI芯片`

---