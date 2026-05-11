<div align="center">
  <img src="https://github.com/Harzva.png" alt="Harzva Avatar" width="112" height="112" style="border-radius: 50%;">

  <h1>Harzva — Make Coding Agents Cheaper</h1>

  <p>
    <a href="https://harzva.github.io/">
      <img src="https://img.shields.io/badge/Portfolio-harzva.github.io-111827?style=flat-square&logo=githubpages&logoColor=white" alt="Portfolio">
    </a>
    <a href="https://github.com/Harzva">
      <img src="https://img.shields.io/badge/GitHub-Harzva-111827?style=flat-square&logo=github&logoColor=white" alt="GitHub">
    </a>
    <a href="https://orcid.org/0009-0006-8057-2958">
      <img src="https://img.shields.io/badge/ORCID-0009--0006--8057--2958-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID">
    </a>
    <a href="mailto:626609967@qq.com">
      <img src="https://img.shields.io/badge/Email-626609967%40qq.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email">
    </a>
    <br>
    <img src="https://img.shields.io/badge/Token%20Saver-Prompt%20Cache%20%7C%20Trace%20Eval-10A37F?style=flat-square" alt="Token Saver">
    <img src="https://img.shields.io/badge/Engineering-Claude%20Code%20%7C%20MCP%20%7C%20Agent%20Harness-2563EB?style=flat-square" alt="Engineering">
    <img src="https://img.shields.io/badge/Research-Few--Shot%20%7C%20Zero--Shot%20%7C%20VLM-7C3AED?style=flat-square" alt="Research">
  </p>

  <p><strong>I work on making long-horizon coding agents cheaper by optimizing prompt-cache reuse at the harness level.</strong></p>
  <p><em>我最近主要做 AI coding agent 的 token 成本优化，同时继续关注视觉语言模型、少样本学习和 Claude Code 生态下的 Agent 工具链。</em></p>

  <p>
    <a href="https://harzva.github.io/">完整作品集</a> ·
    <a href="https://harzva.github.io/#projects">Agent 项目</a> ·
    <a href="https://harzva.github.io/#publications">论文详情</a> ·
    <a href="https://harzva.github.io/#articles">文章专题</a>
  </p>
</div>

---

## 适合谁看？

- **想快速了解我是谁？** 这里是 GitHub 入口名片，只保留最重要的信息。
- **想看完整作品集？** 访问 [harzva.github.io](https://harzva.github.io/)。
- **想看论文图表和详情？** 每篇论文都有独立页面和分析入口。
- **想看 Agent 工程项目？** 这里列出核心仓库，完整说明放在作品集网站。
- **想看 token saver 方向？** 我最近关注 make agents cheaper：通过 harness 层的 prompt cache 复用降低 uncached input 成本。
- **想看我的产品和工程思考？** 文章专题会持续记录 agentic engineering、案例分析和项目复盘。

---

## 入口导航

| 入口 | 内容 |
| :--- | :--- |
| [Portfolio](https://harzva.github.io/) | 完整作品集、论文、项目、文章和个人介绍 |
| [Agent Projects](https://harzva.github.io/#projects) | Claude Code 生态、MCP、多 Agent 编排、插件脚手架 |
| Token Saver | AI coding agent 的 token 成本优化、prompt cache 复用、trace 解析与 A/B 评估 |
| [Publications](https://harzva.github.io/#publications) | 论文详情页、关键图表、方法分析 |
| [Article Analysis](https://harzva.github.io/#articles) | 产品、增长、工程和分发相关案例分析 |
| [Agentic Engineering](https://harzva.github.io/#vibe) | 从 token 到产品、APP 即上下文工程、过程即内容等思考 |

---

## 当前方向

| Direction | Focus |
| :--- | :--- |
| Token Saver / Make Agents Cheaper | Prompt-cache reuse at the harness level, trace parsing, prompt layout optimization, A/B evaluation |
| AI Agent Infrastructure | Claude Code ecosystem, MCP, multi-agent orchestration, plugin scaffolds |
| Vision-Language Research | Few-shot learning, zero-shot learning, compositional generalization, multimodal prompts |
| Engineering Notes | Agentic engineering, product thinking, development process, case analysis |

我最近主要做 AI coding agent 的 token 成本优化。核心不是简单压缩上下文，而是研究 agent harness 里哪些内容稳定、哪些内容动态，并通过 prompt layout 调整、trace 解析和 A/B 评估，提高 prompt cache hit rate，减少实际付费的 uncached input，同时保持任务成功率。

---

## 核心项目

| Project | Description |
| :--- | :--- |
| [learn-likecc](https://github.com/Harzva/learn-likecc)<br>![stars](https://img.shields.io/github/stars/Harzva/learn-likecc?style=social) | Claude Code 逆向工程、source map 恢复、运行时分析与工作流重建 |
| [codex-managed-agent](https://github.com/Harzva/codex-managed-agent)<br>![stars](https://img.shields.io/github/stars/Harzva/codex-managed-agent?style=social) | 面向 Codex / coding agent 的多智能体管理实验，关注任务编排、状态管理和执行控制 |
| [keep-claude-cheaper](https://github.com/Harzva/keep-claude-cheaper)<br>![stars](https://img.shields.io/github/stars/Harzva/keep-claude-cheaper?style=social) | Token Saver 方向：研究 prompt-cache reuse、trace 解析和 harness 层成本优化 |
| [HyperMemory](https://github.com/Harzva/HyperMemory)<br>![stars](https://img.shields.io/github/stars/Harzva/HyperMemory?style=social) | Memory-enhanced AI knowledge system，连接 RAG、Agent、Wiki、GBrain 和层级记忆 |
| [ChinaAI-Roadmaps](https://github.com/Harzva/ChinaAI-Roadmaps)<br>![stars](https://img.shields.io/github/stars/Harzva/ChinaAI-Roadmaps?style=social) | 中国开源 / 开放权重大模型公司的技术路线整理：GLM、Kimi、DeepSeek、MiniMax |
| [LDC](https://github.com/Harzva/LDC)<br>![stars](https://img.shields.io/github/stars/Harzva/LDC?style=social) | CVPR 2025 论文 Logits DeConfusion with CLIP for Few-Shot Learning 的代码仓库 |

---

## 论文与研究

研究主题覆盖 Few-Shot Learning、Zero-Shot Learning、Vision-Language Models 和多模态理解。完整图表和方法分析放在作品集网站。

| # | Paper | Venue | Year |
| :--- | :--- | :--- | :--- |
| 01 | [G2D: Discriminative-Generative Collaborative Inference for Zero-Shot Image Classification](https://harzva.github.io/#/paper/g2d) | arXiv | 2025 |
| 02 | [Preserving Text Space Integrity for Robust Compositional Zero-Shot Learning via Mixture of Pretrained Experts](https://harzva.github.io/#/paper/mope) | Neurocomputing | 2025 |
| 03 | [Text Augmentation for Vision](https://harzva.github.io/#/paper/textaug) | Knowledge-Based Systems | 2026 |
| 04 | [Logits DeConfusion](https://harzva.github.io/#/paper/ldc) | CVPR | 2025 |
| 05 | [PromptVAD: Prompt-Based Video Anomaly Detection](https://harzva.github.io/#/paper/promptvad) | TNNLS | 2023 |
| 06 | [MinEnt: Minimum Entropy for Self-Supervised Representation Learning](https://harzva.github.io/#/paper/minent) | Pattern Recognition | 2023 |
| 07 | [LF2CS: Learning Features into Clustering Space for Few-Shot Image Classification](https://harzva.github.io/#/paper/lf2cs) | ECCV | 2022 |
| 08 | [Text Generation and Multi-Modal Knowledge Transfer for Few-Shot Object Detection](https://harzva.github.io/#/paper/mmkt) | Pattern Recognition | 2025 |
| 09 | [Augmentative Contrastive Learning for One-Shot Object Detection](https://harzva.github.io/#/paper/acl) | Neurocomputing | 2022 |
| 10 | [ViLT-CLIP: Video and Language Tuning CLIP with Multimodal Prompt Learning](https://harzva.github.io/#/paper/viltclip) | AAAI | 2024 |
| 11 | [LLM Knowledge-Driven Target Prototype Learning for Few-Shot Segmentation](https://harzva.github.io/#/paper/kdtpl) | Knowledge-Based Systems | 2025 |

---

## 文章与思考

- [Agentic Engineering 思考](https://harzva.github.io/#vibe)：从 token 到产品、APP 即上下文工程、过程即内容。
- [文章专题与案例分析](https://harzva.github.io/#articles)：产品、增长、工程和分发相关案例分析。
- [完整作品集](https://harzva.github.io/)：论文、项目、文章和个人状态集中展示。

---

## 技术栈

`Python` · `TypeScript` · `React` · `Node.js` · `PyTorch` · `Docker`

---

## 联系

- Portfolio: [https://harzva.github.io](https://harzva.github.io)
- GitHub: [@Harzva](https://github.com/Harzva)
- ORCID: [0009-0006-8057-2958](https://orcid.org/0009-0006-8057-2958)
- Email: [626609967@qq.com](mailto:626609967@qq.com)
