# LLM-driven-Social-Bot

### [1] Shangbin Feng, Herun Wan, Ningnan Wang, Zhaoxuan Tan, Minnan Luo, Yulia Tsvetkov (2024, ACL)

**[What Does the Bot Say? Opportunities and Risks of Large Language Models in Social Media Bot Detection](https://aclanthology.org/2024.acl-long.196/)**

This work investigates both the opportunities and risks of LLMs in social bot detection. It proposes a mixture-of-heterogeneous-experts framework for LLM-based bot detection, while showing that LLM-guided manipulation of textual and structured user information can substantially reduce the effectiveness and reliability of existing bot detectors.

### [2] Boyu Qiao, Kun Li, Wei Zhou, Shilong Li, Qianqian Lu, Songlin Hu (2025, AAAI)

**[BotSim: LLM-Powered Malicious Social Botnet Simulation](https://ojs.aaai.org/index.php/AAAI/article/view/33575)**

This work introduces BotSim, an LLM-powered simulation framework for modeling malicious social botnets in a dynamic social environment. LLM-driven agents autonomously generate posts, comments, and social interactions, and the resulting BotSim-24 benchmark demonstrates that detectors effective on traditional bot datasets perform worse on LLM-driven bots.

### [3] Lynnette Hui Xian Ng, Kathleen M. Carley (2025, SBP-BRiMS)

**[Are LLM-Powered Social Media Bots Realistic?](https://arxiv.org/abs/2508.00998)**

This work investigates whether LLM-powered social media bots can realistically reproduce the linguistic and network characteristics of real social media users. The authors generate bot personas, posts, and interactions and compare the resulting synthetic networks with empirical bot and human networks, revealing systematic differences that have implications for both bot generation and detection.

### [4] Fanqi Kong, Xiaoyuan Zhang, Xinyu Chen, Yaodong Yang, Song-Chun Zhu, Xue Feng (2025, EMNLP)

**[Enhancing LLM-Based Social Bot via an Adversarial Learning Framework](https://aclanthology.org/2025.emnlp-main.1185/)**

This work introduces EvoBot, an evolving LLM-based social bot that learns to generate increasingly human-like behavior through an adversarial learning framework. EvoBot is initialized with supervised fine-tuning and iteratively optimized with direct preference optimization using feedback from a co-adapting detector, enabling the bot to adapt to user profiles, social context, and detection strategies.

### [5] Lynnette Hui Xian Ng, Kathleen M. Carley (2025, arXiv)

**[The Dual Personas of Social Media Bots](https://arxiv.org/abs/2504.12498)**

This work studies the diverse personas exhibited by social media bots and introduces fifteen bot personas based on content and behavioral characteristics. It further highlights the dual-use nature of bots, arguing that bots should be characterized by how they are employed rather than being universally treated as malicious agents.

### [6] Lynnette Hui Xian Ng, Kathleen M. Carley (2025, Scientific Reports)

**[A Global Comparison of Social Media Bot and Human Characteristics](https://www.nature.com/articles/s41598-025-96372-1)**

This work systematically compares social media bots and humans across linguistic, behavioral, and network characteristics. The findings show that bots and humans exhibit distinct communication and interaction patterns, demonstrating that effective bot analysis should consider not only content but also behavioral and social-network signals.

### [7] Jinglong Duan, Weihua Li, Quan Bai, Minh Nguyen, Xiaodan Wang, Jianhua Jiang (2025, IEEE Transactions on Computational Social Systems)

**[LLM-BotGuard: A Novel Framework for Detecting LLM-Driven Bots With Mixture of Experts and Graph Neural Networks](https://doi.org/10.1109/TCSS.2025.3545822)**

This work proposes LLM-BotGuard, a framework that combines pattern-informed feature extraction, mixture-of-experts learning, and graph neural networks to detect LLM-driven bots. It jointly captures distinctive bot features and social structural information, demonstrating the importance of integrating heterogeneous behavioral and network signals for LLM-driven bot detection.

### [8] Jinglong Duan, Shiqing Wu, Weihua Li, Quan Bai, Minh Nguyen, Jianhua Jiang (2026, Information Fusion)

**[BotDMM: Dual-Channel Multi-Modal Learning for LLM-Driven Bot Detection on Social Media](https://doi.org/10.1016/j.inffus.2025.103758)**

This work proposes a temporal dual-channel multimodal framework that separately models user content and social structure for LLM-driven bot detection. It captures temporal changes in tweets, semantic structures, and social relations, while using self-supervised learning to distinguish humans, traditional bots, and LLM-driven bots.

### [9] Da Li, LiYan Shen, Qinglei Guo, ChenYang Zhang, Jun Li, WenTao Jiang, MingXin Yu (2025, Neurocomputing)

**[BotLGT: Social Bot Detection Based on LLM and Graph Transformer](https://doi.org/10.1016/j.neucom.2025.131453)**

This work proposes BotLGT, a language-guided graph transformer that integrates LLM-derived semantic representations with graph structural information for social bot detection. It further introduces motif-enhanced structural encoding and kernel-based linear attention to capture higher-order social patterns while improving scalability.

### [10] Yuxin Zhang, Kai Qiao, Shuhao Shi, Jiaxin Liu, Zihao Liu, Jian Chen, Lei Li, Bin Yan (2026, Journal of King Saud University Computer and Information Sciences)

**[BotEvo: LLM-Driven Social Bot Detection via Behavioral Evolution Modeling and Cross-Modal Fusion](https://doi.org/10.1007/s44443-026-00814-3)**

This work proposes BotEvo, a detection framework that explicitly models the behavioral evolution of LLM-driven social bots. It combines dynamic post weighting, text-behavior-sentiment fusion, and adaptive threshold optimization to capture temporal behavioral signatures and improve detection across LLM-driven and traditional bot datasets.

### [11] Nof Orenstein, Yoni Birman (2026, arXiv)

**[Breaking and Defending LLM-Powered Social Media Bot Detection Systems](https://arxiv.org/abs/2608.15893)**

This work investigates adversarial attacks against LLM-powered social bot detection systems and demonstrates that semantic and contextual attacks can substantially degrade detector performance. It further proposes a multi-LLM defense architecture, framing LLM-based bot detection as an evolving arms race between adaptive attacks and robust detection systems.

### [12] Kaixuan Liu, Guojun Xiong, Weinan Zhang, Shengpu Tang (2026, arXiv)

**[Social Networks of LLM Agents](https://arxiv.org/abs/2607.03695)**

This work studies how information and beliefs propagate through networks of LLM agents. It proposes **SNLA**, which models effective social influence by jointly considering network position and limited attention. The paper theoretically characterizes the transition between herding and wisdom-of-crowds behavior, showing that network topology alone is insufficient to explain collective behavior and that agents' attention patterns substantially affect social influence and collective outcomes.

---

### [13] Zhongyi Qiu, Hanjia Lyu, Wei Xiong, Jiebo Luo (2025, arXiv)

**[Can LLMs Simulate Social Media Engagement? A Study on Action-Guided Response Generation](https://arxiv.org/abs/2502.12073)**

This work investigates whether LLMs can simulate users' social-media engagement behavior. Instead of directly generating responses, it first predicts the user's likely engagement action, such as retweeting, quoting, or rewriting, and then generates content conditioned on the predicted action. The results show that modeling **social actions separately from textual content** can improve the simulation of social-media responses, highlighting that realistic social behavior cannot be reduced to text generation alone.

---

### [14] Xintao Wang, Jian Yang, Weiyuan Li, Rui Xie, Jen-tse Huang, Jun Gao, Shuai Huang, Yueping Kang, Liyuan Gou, Hongwei Feng, Yanghua Xiao (2026)

**[HUMANLLM: Benchmarking and Reinforcing LLM Anthropomorphism via Human Cognitive Patterns](https://arxiv.org/abs/2601.10198)**

This work studies whether LLMs can exhibit human-like behavior by modeling underlying cognitive and psychological patterns rather than merely imitating surface-level language. It constructs a large collection of human cognitive and behavioral patterns from academic literature and evaluates LLMs across individual and multi-pattern scenarios. The results show that larger LLMs do not necessarily produce more human-like behavior, suggesting that authentic social behavior requires explicit modeling of interacting behavioral and cognitive mechanisms.

---

### [15] Changgeon Ko, Jisu Shin, Hoyun Song, Huije Lee, Eui Jun Hwang, Jong C. Park (2026)

**[Social Dynamics as Critical Vulnerabilities that Undermine Objective Decision-Making in LLM Collectives](https://aclanthology.org/2026.acl-long.1756/)**

This work investigates how social dynamics influence decision-making among LLM agents in multi-agent environments. It systematically studies phenomena including **social conformity, perceived expertise, dominant-speaker effects, and rhetorical persuasion**, showing that social context can substantially alter agents' decisions even when the underlying evidence remains unchanged. The findings demonstrate that LLM-agent behavior is strongly conditioned by interactions with other agents and by the structure of the surrounding social environment.

---

### [16] D. Xue, J. Cui, S. Qian, C. Hu, C. Xu (2026)

**[SoMe: A Realistic Benchmark for LLM-based Social Media Agents](https://ojs.aaai.org/index.php/AAAI/article/view/37113)**

This work introduces **SoMe**, a benchmark for evaluating LLM-based social-media agents in realistic environments. The benchmark contains multiple social-media tasks covering content understanding, user understanding, complex decision-making, and tool-assisted interactions, together with millions of social-media posts and thousands of user profiles. The study evaluates mainstream LLM agents and finds that current systems still struggle with realistic social-media tasks, highlighting the gap between general language capabilities and genuine social intelligence.

---

### [17] Jinghua Piao, Yuwei Yan, Jun Zhang, Nian Li, Junbo Yan, Xiaochong Lan, Zhihong Lu, Zhiheng Zheng, Jing Yi Wang, Di Zhou, Chen Gao, Fengli Xu, Fang Zhang, Ke Rong, Jun Su, Yong Li (2026)

**[AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society](https://arxiv.org/abs/2502.08691)**

This work presents **AgentSociety**, a large-scale simulation platform for studying human behavior and social phenomena with LLM-driven generative agents. The framework integrates agent memory, motivation, emotion, cognition, planning, and social interaction and supports simulations involving thousands of agents and millions of interactions. The platform enables studies of social polarization, information propagation, policy interventions, and external shocks, demonstrating the potential of LLM agents as computational models for large-scale social simulation.

---

### [18] Aleksandar Tomašević, Darja Cvetković, Sara Major, Slobodan Maletić, Miroslav Anđelković, Ana Vranić, Boris Stupovski, Dušan Vudragović, Aleksandar Bogojević, Marija Mitrović Dankulov, et al. (2026)

**[Towards Operational Validation of LLM-Agent Social Simulations: A Replicated Study of a Reddit-like Technology Forum](https://link.springer.com/article/10.1140/epjds/s13688-026-00674-x)**

This work addresses the challenge of validating whether LLM-agent social simulations realistically reproduce human social behavior. The authors conduct repeated long-term simulations of a Reddit-like technology forum and compare the generated activity and interaction patterns with real-world social-media data. The evaluation considers activity patterns, network structure, toxicity, topical coverage, and stylistic convergence, showing that although LLM simulations can reproduce some macroscopic properties of online communities, substantial discrepancies remain in interaction volume, thread structure, toxicity, and repeated social interactions.

---

### [19] Ljubiša Bojić, Alexander Felfernig, Bojana Dinić, Velibor Ilić, Achim Rettinger, Vera Mevorah, Damian Trilling, et al. (2026)

**[Persona-prompted LLM agents achieve modest but genuine prediction of human social media reactions](https://www.nature.com/articles/s41598-026-66277-8)**

This work evaluates whether persona-prompted LLM agents can predict how individual users react to social-media content. Using a large-scale evaluation involving more than 120,000 agent-persona combinations, the study finds that LLM agents contain genuine predictive information about human reactions but remain inferior to conventional machine-learning baselines on some metrics. The findings suggest that **persona prompting alone is insufficient for accurately modeling individualized social behavior**, motivating richer models that incorporate social context, memory, interaction history, and behavioral dynamics.

---

### [20] Philipp J. Schneider, Lin Tian, Marian-Andrei Rizoiu (2025/2026)

**[Learning to Make Friends: Coaching LLM Agents toward Emergent Social Ties](https://arxiv.org/abs/2510.19299)**

This work studies whether LLM agents can learn behaviors that lead to emergent social relationships. Agents repeatedly interact with one another and receive behavioral coaching signals covering social interaction, information seeking, self-presentation, coordination, and emotional support. Through in-context behavioral adaptation, agents develop persistent interaction patterns and emergent social ties, demonstrating that social relationships can arise from repeated adaptive interactions between LLM agents.

---

### [21] Jiaxing Zheng, Changqing Li, Peng Wu, Li Pan (2026)

**[RoleSimLLM: Towards Large-scale and Comprehensive Social Propagation Simulation via Role-based LLM-driven Agents](https://www.sciencedirect.com/science/article/pii/S0306457326000804)**

This work proposes **RoleSimLLM**, a role-based framework for large-scale social propagation simulation with LLM-driven agents. Instead of independently simulating every individual user, the framework models behavioral distributions at the level of social roles and combines them with dynamic graph neighborhoods through a graph-based interaction module. Experiments on large-scale social-media data demonstrate that role-based simulation can reduce computational costs while preserving microscopic behavioral patterns and macroscopic propagation dynamics.

---

### [22] Yunyao Zhang, Zikai Song, Hang Zhou, Wenfeng Ren, Yi-Ping Phoebe Chen, Junqing Yu, Wei Yang (2025)

**[GA-S³: Comprehensive Social Network Simulation with Group Agents](https://aclanthology.org/2025.findings-acl.468/)**

**Venue:** Findings of the Association for Computational Linguistics: ACL 2025, pp. 8950–8970

This work proposes **GA-S³**, a comprehensive social-network simulation system based on LLM-driven **Group Agents**. Instead of simulating billions of individual users separately, Group Agents represent collections of users with similar behavioral characteristics, substantially improving simulation scalability. The framework consists of hierarchical group generation, decision-reasoning, and action modules, where group profiles are dynamically generated according to environmental events and agents update their memory, emotions, attitudes, and behaviors during simulation. The authors further construct a social-network benchmark from popular online events in 2024 and demonstrate that GA-S³ can reproduce realistic social-network dynamics at substantially lower computational cost.

---

### [23] Gian Marco Orlando, Valerio La Gatta, Diego Russo, Vincenzo Moscato (2025)

**[Can Generative Agent-Based Modeling Replicate the Friendship Paradox in Social Media Simulations?](https://dl.acm.org/doi/10.1145/3717867.3717895)**

**Venue:** Proceedings of the 17th ACM Web Science Conference 2025 (WebSci 2025), pp. 510–515

This work investigates whether **Generative Agent-Based Modeling (GABM)** can reproduce global network-level phenomena observed in real social media. The authors construct LLM-driven generative agents with distinct personalities and interests and evaluate whether the **Friendship Paradox** emerges naturally in simulated social networks. Experiments using Twitter data related to the 2020 US election and the QAnon conspiracy show that the friendship paradox emerges without explicitly programming the agents with this behavioral rule. The simulations also reproduce hierarchical network structures in which agents preferentially connect with users exhibiting higher activity or influence, demonstrating that LLM-based agents can generate non-trivial emergent network phenomena.

---

### [24] Bincheng Gu, Min Gao, Junliang Yu, Zongwei Wang, Zhiyi Liu, Kai Shu, Hongyu Zhang (2026)

**[Ahead of the Spread: Agent-Driven Virtual Propagation for Early Fake News Detection](https://arxiv.org/abs/2601.02750)**

**Venue:** arXiv / CoRR, 2026

This work proposes **AVOID (Agent-driven Virtual prOpagatIon for early fake news Detection)**, which reformulates early fake-news detection as an **evidence-generation problem**. Instead of waiting for real propagation signals that may not yet exist, the framework uses LLM-powered agents with differentiated roles and data-driven personas to simulate plausible early-stage information diffusion. The generated virtual propagation trajectories provide complementary social evidence for fake-news detection, while a denoising-guided fusion mechanism aligns simulated propagation with the semantics of the original content. The work demonstrates that LLM-driven social simulation can be used not only to reproduce social behavior but also to generate otherwise unavailable social-network evidence for downstream prediction tasks.

---

### [25] Jiarui Ji, Runlin Lei, Xuchen Pan, Zhewei Wei, Hao Sun, Yankai Lin, Xu Chen, Yongzheng Yang, Yaliang Li, Bolin Ding, Ji-Rong Wen (2026)

**[Leveraging LLM-based Agents for Social Science Research: Insights from Citation Network Simulations](https://www.nature.com/articles/s41599-025-06193-w)**

**Venue:** Humanities and Social Sciences Communications, Vol. 13, Article 127, 2026

This work introduces **CiteAgent**, an LLM-agent-based framework for simulating the evolution of citation networks. The framework models authors and papers as interacting entities and uses LLM agents to simulate behaviors such as author selection, paper creation, and citation decisions. CiteAgent successfully reproduces several empirical properties of real citation networks, including **power-law degree distributions, citation distortion, and shrinking network diameter**. The authors further use the simulated networks to establish LLM-based survey and laboratory experiments for social-science research, demonstrating how LLM agents can be used as computational subjects for studying social and scientific behaviors.

---

### [26] Insaf Kraidia, Iyas Qaddara, Alhanof Almutairi, Nada Alzaben, Samir Brahim Belhouari (2026)

**[When Collaboration Fails: Persuasion Driven Adversarial Influence in Multi Agent Large Language Model Debate](https://www.nature.com/articles/s41598-026-42705-7)**

**Venue:** Scientific Reports, Vol. 16, Article 11640, 2026

This work investigates **persuasion-driven adversarial behavior** in multi-agent LLM systems. It demonstrates that a strategically designed adversarial agent can manipulate cooperative agents through coherent, confident, and misleading natural-language arguments without modifying model parameters or using traditional prompt or token attacks. Experiments show that a single adversarial agent can reduce collective accuracy by approximately 10–40% and substantially increase consensus on incorrect answers. The study further finds that techniques such as Best-of-N optimization and RAG can unintentionally amplify persuasive attacks by increasing the perceived credibility of misleading arguments. The work highlights that **social influence and persuasion should be treated as explicit behavioral mechanisms and potential vulnerabilities in LLM-agent societies**.

---

### [27] Erica Coppolillo, Federico Cinus, Marco Minici, Francesco Bonchi, Giuseppe Manco (2025)

**[Engagement-Driven Content Generation with Large Language Models](https://dl.acm.org/doi/10.1145/3711896.3736932)**

**Venue:** Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2025), Vol. 2, pp. 369–379

This work studies whether LLMs can learn to generate content that **maximizes social-media engagement within an entire network**, rather than optimizing only for one-to-one interactions. It proposes a reinforcement-learning framework in which an LLM generates content, injects it into a simulated social network, and receives a reward determined by an engagement model that captures network-level propagation and interaction. The learning process adapts to the underlying opinion distribution and network conditions while treating the engagement model as a plug-and-play component. This work is particularly relevant because it explicitly formulates an LLM's content-generation process as a **policy optimized through feedback from a social environment**.

---

### [28] Zhongyi Qiu, Hanjia Lyu, Wei Xiong, Jiebo Luo (2025)

**[Can LLMs Simulate Social Media Engagement? A Study on Action-Guided Response Generation](https://arxiv.org/abs/2502.12073)**

**Venue:** arXiv / CoRR, 2025

This work investigates whether LLMs can simulate individual users' social-media engagement behavior. The proposed framework first predicts a user's likely engagement action—**retweet, quote, or rewrite**—and then generates a response conditioned on the predicted action. The authors evaluate GPT-4o-mini, o1-mini, and DeepSeek-R1 and find that zero-shot LLMs underperform BERT in engagement-action prediction, while few-shot prompting improves the semantic alignment of generated responses with real user posts. The study emphasizes that realistic social-media simulation requires modeling **behavioral actions in addition to textual content**.

> **Duplicate of [13].** The link provided here is the arXiv version of the same paper already listed as [13]. It should not be counted as a new paper in the final bibliography.

---

### [29] Nils Schwager, Simon Münker, Alistair Plum, Achim Rettinger (2026)

**[Towards Simulating Social Media Users with LLMs: Evaluating the Operational Validity of Conditioned Comment Prediction](https://aclanthology.org/2026.wassa-1.16/)**

**Venue:** The Proceedings of the 15th Workshop on Computational Approaches to Subjectivity, Sentiment & Social Media Analysis (WASSA 2026), pp. 208–221

This work proposes **Conditioned Comment Prediction (CCP)** as an operational framework for evaluating whether LLMs can realistically simulate individual social-media users. Instead of relying only on persona descriptions, the framework asks an LLM to predict how a specific user would respond to a given stimulus and compares the generated response with the user's authentic digital traces. Experiments with Llama-3.1, Qwen3, and Ministral across English, German, and Luxembourgish show an important **form–content decoupling**: supervised fine-tuning can improve surface-level properties such as length and syntax while degrading semantic grounding. The authors further find that explicit generated biographies become less useful after fine-tuning because models can infer user characteristics directly from behavioral histories. The work therefore argues that **authentic behavioral traces may be more informative than manually constructed personas for high-fidelity social-agent simulation**.

---
