<h1 align="center">Weiyu Ma · 马纬彧</h1>

<p align="center">
  <b>Agentic RL · Game AI · World Model</b><br/>
  Former StarCraft II pro (KR Grandmaster) turned AI researcher
</p>

<p align="center">
  <a href="https://weiyu.page"><img src="https://img.shields.io/badge/Homepage-weiyu.page-3fd2ff?style=flat-square" alt="Homepage"/></a>
  <a href="https://scholar.google.com/citations?user=_waWSjEAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-Weiyu%20Ma-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="mailto:sc2meisah@gmail.com"><img src="https://img.shields.io/badge/Email-sc2meisah%40gmail.com-555?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

> [!TIP]
> **Open to work** — looking for research or engineering roles in Agentic RL, LLM/VLM agents and game AI. Reach me at **sc2meisah@gmail.com**.
>
> **正在求职**：Agentic RL、LLM/VLM Agent 与游戏 AI 方向的研究 / 算法岗位，欢迎邮件联系。

My research asks how AI can perceive, decide and keep learning from interaction the way people do. I use games and multi-step agent tasks as testbeds for LLM/VLM agents, Agentic RL, world models and multi-agent decision-making.

## Selected work

| Work | What it is | Venue | Links |
|---|---|---|---|
| ⭐ **LLM Play SC2** (TextStarCraft II) | **The world's first work to put LLMs in charge of real-time decision-making in a complex environment** — pioneering LLM research on complex real-time decision-making, with StarCraft II as the benchmark. 10+ LLMs benchmarked; >50% win rate vs. Harder (Lv5) AI | NeurIPS 2024 | [Paper](https://arxiv.org/abs/2312.11865) · [Code](https://github.com/sc2musa/Large-Language-Models-play-StarCraftII) |
| **AVA** | **The world's first VLM-based multi-agent system for complex real-time decision-making** — VLM micro from raw frames; CCF-A | ACL 2026 Findings | [Paper](https://aclanthology.org/2026.findings-acl.208/) · [Code](https://github.com/camel-ai/VLM-Play-StarCraft2) |
| **EvoCurr** | **The world's first recursive self-improvement (RSI) in complex decision-making** — 72 h unattended self-evolution; 100% win rate with 100+ units, beyond human Grandmasters | EMNLP 2026 Findings | [Paper](https://arxiv.org/abs/2508.09586) · [Code](https://github.com/anchicken/EvoCurr) |
| **LLM-SMAC** | **The world's first Agentic RL in complex multi-agent decision-making (StarCraft II)** — far deeper multi-turn interaction than Search-R1-style tool use; 7B model beats DeepSeek-V3 | AAMAS 2026 | [Paper](https://arxiv.org/abs/2410.16024) · [Code](https://github.com/devindeng94/LLM-SMAC) |
| **FreshPER** | **The world's first general replay-buffer framework for LLM post-training** — NQ Search +20 pts, Sokoban +39 pts, MathVista +15 pts (absolute) | Under review | [Paper](https://arxiv.org/abs/2604.16918) · [Code](https://github.com/Vision-CAIR/Freshness-Aware-PER) |
| **JEV-Star** | **SOTA for direct LLM control of StarCraft II** — 9/10 real-time wins vs. Lv7, the strongest non-cheating AI | Preprint 2026 | [Paper](https://github.com/sc2musa/Jev_Star/blob/main/paper/JEV-Star.pdf) · [Code](https://github.com/sc2musa/Jev_Star) |
| **eSports World Model Dataset** | The world's first open-source, multi-game dataset for long-horizon, multi-agent world modeling in eSports — complete matches with synchronized per-player views (SC2 / Dota 2 / CS2) | Released 2026.10 | [Dataset](https://www.modelscope.cn/datasets/meisah111/Esports_world_model_datasets) · [Code](https://github.com/sc2musa/esports-worldmodel-datasets) |

More papers, projects and demos → **[weiyu.page](https://weiyu.page)**

---

## 中文简介

我关注一个核心问题：**如何让 AI 像人一样感知、决策，并从交互中持续学习**。我以游戏和多步智能体任务为试验场，研究 LLM/VLM Agent、Agentic RL、World Model 与多智能体决策。本科期间是星际争霸 II 职业选手（韩服宗师）。

**代表作**

- ⭐ **LLM Play SC2**（TextStarCraft II，NeurIPS 2024，引用 170+）：**全球首个将大模型用于复杂场景实时决策的工作**，开创了以星际争霸 II 为标杆的大模型复杂实时决策方向；系统评测 10+ 主流大模型，对战困难（Lv5）AI 胜率 >50%
- **AVA**（ACL 2026 Findings）：**全球首个基于 VLM 的多智能体复杂实时决策系统**，CCF-A
- **EvoCurr**（EMNLP 2026 Findings）：**全球首个在复杂决策场景实现递归自我改进（RSI）的工作**，无人干预自主进化 72 小时，百余单位协同 100% 胜率、超越人类宗师
- **LLM-SMAC**（AAMAS 2026）：**全球首个在星际争霸 II 这类复杂多智能体决策场景下的 Agentic RL 工作**，多轮交互深度远超 Search-R1 类工作，7B 模型超越 DeepSeek-V3
- **FreshPER**：**全球首个通用的大模型后训练经验回放（Replay Buffer）框架**，NQ Search、Sokoban、MathVista 分别提升 20、39、15 个百分点
- **JEV-Star**：**大模型直接决策在星际争霸 II 上的 SOTA**，实时对战最高非作弊难度 Lv7 AI 10 局 9 胜
- **电子竞技世界模型数据集**：全球首个开源的多游戏、长时程、多智能体电竞世界模型数据集，以完整对局为单位提供逐玩家同步视角

完整论文、项目与演示视频见个人主页：**[weiyu.page](https://weiyu.page)**
