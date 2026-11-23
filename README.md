Projects and Experiments
简体中文

My goal is to match compute to the task. I start with rules, retrieval, or smaller models for well-defined steps and reserve more capable models for complex reasoning, multimodal understanding, and synthesis. I compare quality, latency, and cost to decide where extra compute is worth spending.
Model efficiency and multimodal agents
- Teacher–Student Chinese Sentiment Analysis · Used teacher-generated labels to fine-tune a 4B student with LoRA. On 200 human-labeled held-out reviews, the student reached 0.771 macro-F1, compared with 0.764 for the teacher and 0.565 for TF-IDF + LinearSVC. Its estimated API cost was about one-sixth of the teacher’s.
- Cross-Platform Social Agent · Connects WeChat, QQ, Bilibili, and Douyin to a shared agent core. Separate components handle conversation, task coordination, and multimodal perception, with shared memory that records where and when information came from.
- Multimodal Game Agent · Combines local detection, OCR, and a vision-language model to extract structured state, then uses a finite-state machine and action validation. The loop has been tested in simulation. End-to-end device validation is pending.
AI and systems security
- AI-Assisted Cryptographic Code Auditor · Combines Semgrep rules and a fine-tuned model to flag cryptographic misuse in Python, map findings to CWEs, and generate a structured report. The repository documents six rounds of evaluation, including precision and false positives.
- Prompt Injection Defense Evaluation · Evaluates LLM defenses with 60 bilingual test cases, separating actual disclosure, text echoed in refusals, and benign requests that were incorrectly blocked. Supports live API and offline mock runs.
- LinkGuard Defense Simulation · A paper-based simulation of a state-aware defense that detects suspicious link following while allowing benign file operations.
Research tools and reference implementations
- Paper Library · Knowledge Vector Library · A bilingual paper index and research web app, plus a retrieval engine with incremental ingestion, source metadata, and hybrid keyword–vector search.
- Concept Lab · Runnable experiments in computer science, machine learning, and AI infrastructure, including CPU demonstrations of decoding, batching, and KV-cache costs.
- Cryptographic Algorithm Implementations · C implementations of AES, SM3, SM4, RSA, and ElGamal with correctness tests, benchmarks, and lab notes.
- DSH Fairy Mode · A DeepSeek Harness extension based on an upstream project, with an appearance toggle, persona controls, reference prompts, web search, and optional read-aloud.
简体中文
我希望让每一份算力都匹配它要完成的任务，把好钢用在刀刃上。

任务边界清楚时，我优先考虑规则、检索和轻量模型。遇到复杂推理、跨模态理解或需要综合判断的环节，再调用更强的模型。我希望用同一组评测比较结果质量、延迟和成本，判断哪些地方值得投入更多算力。
模型选型与多模态智能体
- 中文情感分析蒸馏 · 用教师大模型标注中文评论，再通过 LoRA 微调 4B 学生模型。在同一组 200 条人工标注的留出样本上，学生模型的 macro-F1 为 0.771，教师为 0.764，TF-IDF + LinearSVC 基线为 0.565。学生的估算 API 成本约为教师的 1/6。
- 跨平台社交智能体 · 把微信、QQ、B 站和抖音接到同一个智能体核心。对话、任务编排和图像、音频、视频理解由不同组件承担，共享记忆保留信息的来源与时间。
- 多模态游戏智能体 · 用本地视觉检测、OCR 和视觉大模型把画面转成结构化状态，再用状态机规划并校验动作。目前已在模拟环境中跑通闭环，真机端到端验证仍待完成。
AI 安全与系统防御
- AI 辅助密码代码审计 · 用 Semgrep 规则和微调模型查找 Python 代码中的密码误用，按 CWE 归类并生成结构化报告。仓库记录了六轮实验，以及各轮在精度和误报方面的表现。
- 提示注入防护评测 · 用 60 条中英双语用例评估 LLM 防护，分别记录实际泄露、拒答中的文本复述和正常请求的误拦截。支持真实 API 评测和离线模拟。
- LinkGuard 防护机制模拟 · 基于论文实现的模拟项目，在虚拟文件系统中演示状态感知防护如何识别异常链接跟随行为，并放行正常文件操作。
研究工具与基础实现
- 论文文库 · 知识向量库 · 论文文库提供双语论文索引和研究分析界面。向量库负责把文档增量入库，保留可追溯的来源，并结合关键词和向量检索。
- Concept Lab · 把计算机基础、机器学习、深度学习和 AI 基础设施写成可运行的小实验，包括在 CPU 上演示解码、批处理和 KV 缓存的资源开销。
- 密码算法实现与性能分析 · 用 C 实现 AES、SM3、SM4、RSA 和 ElGamal，附正确性测试、性能基准和实验手册。
- DSH Fairy Mode · 基于上游项目开发的 DeepSeek Harness 扩展。我增加了界面装饰开关、聊天语气控制、语录参考、联网检索和可选朗读。## Hi there 👋

<!--
**kungaocode/kungaocode** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
