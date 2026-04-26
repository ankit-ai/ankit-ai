### Hello, I am Ankit! 👋

- 🔭 I’m an Applied Science Leader at Amazon working on **multimodal large language models** — post-training, alignment, and agentic retrieval for foundation models that reason across text, image, and structured data. My focus is turning frontier research on reasoning, grounding, and tool use into production systems that hold up at scale.

- 💬 My mission is to build AI systems that solve high-impact problems for people around the world and make everyday life easier.

- 🌱 I have served as a consultant and course facilitator for Stanford's XCS221 (Principles of AI) and XCS224U (Natural Language Understanding) professional courses.

- 👯 I mentor, coach, and collaborate with builders working on frontier AI. If you have an idea that lines up with what I work on, feel free to reach out.

- 📫 You can reach me at: ankitrchadha at gmail

- ⚡ Finding me on the internet:
  - [linkedin.com/in/ankitrc](https://www.linkedin.com/in/ankitrc)
  - [Google Scholar](https://scholar.google.com/citations?user=hcslcm0AAAAJ)

---

### What I work on

- **Multimodal foundation models**: unified reasoning over text, image, and structured inputs; grounding and cross-modal alignment
- **Post-training & alignment**: SFT, preference optimization (RLHF / DPO), RLVR-style verifiable rewards, and reasoning-focused fine-tuning
- **Agentic systems**: tool use, deep research agents, long-horizon planning, and multi-step task execution
- **Retrieval-augmented generation**: grounded reasoning with citations, faithfulness, and hallucination control at production scale
- **Memory-augmented LLMs**: retrieval-based and graph-structured long-term memory for multi-turn continuity and personalization
- **Long-context reasoning and evaluation**: factuality, faithfulness, and release gates for frontier GenAI systems

---

### Speaking engagements

Open to talks at conferences, workshops, podcasts, and university lectures on multimodal LLMs, post-training and alignment, agentic architectures, grounded RAG, and scaling applied research orgs. To invite me to a talk, panel, or guest lecture, reach out at **ankitrchadha at gmail** or via [LinkedIn](https://www.linkedin.com/in/ankitrc).

---

### Recent research

- **Memory Graph-Empowered Plan Generation for Agentic LLMs** (under review, ACL 2026). Augments agentic plan generation with a structured memory graph so LLM agents can reuse prior planning knowledge rather than re-deriving solutions from scratch. Targets multi-step task execution where procedural continuity across tasks matters.

- **[APEX-MEM: Agentic Semi-Structured Memory with Temporal Reasoning for Long-Term Conversational AI](https://arxiv.org/abs/2604.14362)** (2026). A property-graph memory system with append-only event storage and a multi-tool retrieval agent that resolves conflicting information at query time. Reaches 88.88% on LOCOMO-QA and 86.2% on LongMemEval, outperforming prior session-aware memory systems.

- **[APEX-EM: Non-Parametric Online Learning for Autonomous Agents via Structured Procedural-Episodic Experience Replay](https://arxiv.org/abs/2603.29093)** (2026). A frozen-backbone online learning framework where LLM agents accumulate structured procedural traces and retrieve them via semantic, structural-signature, and plan-graph matching. Hits 89.6% on KGQAGen-10k (+48.3pp over no-memory) and 83.3% on BigCodeBench (+29.4pp), beating MemRL under matched conditions.

- **[Controlled Text Generation with Hidden Representation Transformations (CHRT)](https://aclanthology.org/2023.findings-acl.602/)** (Findings of ACL 2023). Steers LLM output for detoxification, sentiment, and simplification by learning contrastive transformations on hidden states, with multi-attribute control and only 0.01s of added inference latency. Beats seven baselines while preserving linguistic quality.

- **[Cross-Lingual Knowledge Distillation for Answer Sentence Selection in Low-Resource Languages](https://aclanthology.org/2023.findings-acl.885/)** (Findings of ACL 2023). Distills a strong English AS2 teacher into students for low-resource languages, along with two new benchmarks (Xtr-WikiQA across 9 languages, TyDi-AS2 across 8 typologically diverse languages). Matches or beats supervised fine-tuning without labeled target-language data.

- **Question-Context Alignment and Answer-Context Dependencies for Effective Answer Sentence Selection** (INTERSPEECH 2023). Improves answer sentence selection by explicitly modeling question-context alignment alongside answer-context dependencies, rather than treating them in isolation. Yields consistent gains across QA benchmarks.

- **Efficient Fine-tuning Large Language Models for Knowledge-Aware Response Planning** (ECML PKDD 2023). Proposes a lightweight fine-tuning recipe that injects knowledge awareness into LLM-based response planners without full-model tuning. Preserves downstream quality while cutting compute cost relative to dense fine-tuning baselines.

- **[Training Mixed-Domain Translation Models via Federated Learning](https://aclanthology.org/2022.naacl-main.186/)** (NAACL 2022). Shows that federated aggregation can fuse NMT engines trained on different domains and match centralized baselines. Introduces a bandwidth-aware parameter-selection technique to cut communication cost for large translation models.

- **[WDRASS: A Web-scale Dataset for Document Retrieval and Answer Sentence Selection](papers/wdrass-cikm-2022.pdf)** (CIKM 2022). Releases a web-scale dataset and benchmark that couples document retrieval with answer sentence selection in a single pipeline. Enables training and evaluation of end-to-end open-domain QA systems at realistic scale.

- **[Communication-Efficient Federated Learning for Neural Machine Translation](https://assets.amazon.science/77/b5/8fc4062040378b5112c36b44d7e7/communication-efficient-federated-learning-for-neural-machine-translation.pdf)** (NeurIPS 2021 workshop). Adapts FL to NMT by identifying and exchanging only impactful parameters during aggregation. Reduces communication overhead while preserving translation quality across clients.
