My goal is to match computing power to the task. I use rules, search, or smaller models for straightforward steps and turn to stronger models for complex reasoning or tasks that combine text, images, audio, and video. I compare quality, speed, and cost to decide when the extra computing power is worth it.

Model efficiency and multimodal agents
- Teacher–Student Chinese Sentiment Analysis — Trained a smaller model to classify Chinese reviews using labels from a larger model. On the same human-labeled test set, the two performed similarly, and the smaller model had a lower estimated API cost.
- Cross-Platform Social Agent — Connects WeChat, QQ, Bilibili, and Douyin through a shared assistant that remembers where and when it learned something.
- Multimodal Game Agent — Reads game screens, plans actions, and checks them before execution. The workflow runs in simulation, with full device testing still pending.

AI and systems security
- AI-Assisted Cryptographic Code Auditor — Combines rules and a fine-tuned model to flag common mistakes in how Python code uses cryptography.
- Prompt Injection Defense Evaluation — Tests whether safeguards prevent information leaks while allowing normal requests through.
- LinkGuard Defense Simulation — Simulates a Windows file system defense that blocks suspicious link-following behavior while allowing normal file operations.

Research and learning tools
- Paper Library & Knowledge Vector Library — A bilingual paper index and a search engine that helps users find relevant passages and trace them back to their sources.
- Concept Lab — Small, runnable experiments for learning computer science, machine learning, and AI infrastructure.
- Cryptographic Algorithm Implementations — C implementations of common encryption and hashing algorithms, with tests and performance comparisons.
- DSH Fairy Mode — A DeepSeek Harness extension built on an existing project, with a switchable theme, chat styles, web search, and optional read-aloud.


  
我希望把算力用在最需要的地方。任务明确时，我优先用规则、检索或轻量模型。遇到复杂推理，或需要结合文字、图像、音频和视频理解的任务时，再调用更强的模型。我会比较效果、速度和成本，判断多花的算力是否值得。

模型选型与多模态智能体
- 中文情感分析蒸馏 · 用大模型标注中文评论，再训练小模型做情感分类。两者在同一批人工标注的测试样本上表现接近，小模型的估算调用成本更低。
- 跨平台社交智能体 · 将微信、QQ、B 站和抖音接入同一个助手，让它记住信息来自哪里、是什么时候获得的。
- 多模态游戏智能体 · 读取游戏画面，规划并校验动作。流程已在模拟环境中跑通，仍待完整的真机验证。

AI 安全与系统防御
- AI 辅助密码代码审计 · 结合规则和微调模型，查找 Python 代码中常见的密码算法误用。
- 提示注入防护评测 · 检查防护措施能否减少信息泄露，同时避免误拦截正常请求。
- LinkGuard 防护机制模拟 · 在模拟文件系统中演示 Windows 文件防护如何拦截异常链接访问并放行正常操作。

研究与学习工具
- 论文文库与知识向量库 · 提供双语论文索引，支持搜索文献片段并回查原文出处。
- Concept Lab · 用可运行的小实验学习计算机基础、机器学习和 AI 基础设施。
- 密码算法实现与性能分析 · 用 C 实现常见加密与哈希算法，附测试和性能对比。
- DSH Fairy Mode · 基于已有项目改编的 DeepSeek Harness 扩展，支持主题切换、聊天语气、联网搜索和朗读。
