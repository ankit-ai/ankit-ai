### Hello, I am Ankit

I lead Applied Science and Engineering teams at Amazon AGI, turning research in foundation models and agents into systems that work at web scale. My work spans post-training and alignment, multimodal and grounded retrieval, agent memory, and evaluation. A recurring question connects it: how can an AI system find reliable evidence, reason over it, and retain useful experience? Previously I led deep learning work at Salesforce and worked at Apple and Samsung.

**Papers, with full abstracts and PDFs: [ankit-ai.github.io](https://ankit-ai.github.io/)**

- I work in Applied Science at Amazon on grounded reasoning for AI agents,
  agent memory, and web-scale retrieval across text, images and structured data.
- I have served as a consultant and course facilitator for Stanford's XCS221
  (Principles of AI), XCS224N and XCS224U (Natural Language Understanding).
- I mentor and collaborate with builders working on frontier AI. If you have an
  idea that lines up with what I work on, reach out.
- Reach me at ankitrchadha [at] gmail [dot] com

---

### What I work on

- **Agent memory.** Introduced typed procedural knowledge graphs for reusable agent experience and append-only property graph memory for temporal conversational reasoning.
- **How agents delegate.** Introduced adaptive routing between typed dependency graphs and natural-language handoffs for multi-agent LLM systems.
- **Web-scale question answering.** Built web-scale document retrieval, passage reranking, and answer sentence selection methods spanning thirty million documents and nine languages.
- **Learning from data that cannot move.** Developed mixed-domain neural machine translation and communication-efficient federated learning without pooling data across domains.
- **Steering what a model says.** Developed methods for controlling toxicity, sentiment, simplicity, and viewpoint through hidden-state transformations and attribute conditioning.

---

### Publications

Peer reviewed, most recent first. Every link opens the paper's own page with the
complete abstract, the key results, and the PDF.

- **[Routed Graph Handoff: Adaptive Format Selection for Multi-Agent LLM Delegation](https://ankit-ai.github.io/papers/routed-graph-handoff/)**. EMNLP 2026, accepted, to appear. An extra classifier call picks per task whether one AI agent sends work to another as a dependency graph or as prose, gaining 12.7 points on τ-retail and preventing a 14.6-point loss on AppWorld.
- **[APEX-MEM: Agentic Semi-Structured Memory with Temporal Reasoning for Long-Term Conversational AI](https://ankit-ai.github.io/papers/apex-mem-agentic-semi-structured-memory/)**. ACL 2026 (Main Conference, Long Papers). APEX-MEM uses an append-only property graph of temporally grounded, entity-centric events and a multi-tool retrieval agent to resolve evolving information at query time.
- **[APEX-EM: Non-Parametric Online Learning for Autonomous Agents via Structured Procedural-Episodic Experience Replay](https://ankit-ai.github.io/papers/apex-em-procedural-episodic-experience-replay/)**. EMNLP 2026, accepted, to appear. APEX-EM introduced procedural knowledge graphs for LLM agent memory: its typed Procedural Knowledge Graph stores complete solution traces and retrieves them by meaning, operation structure, and graph traversal, with no model retraining.
- **[Question-Context Alignment and Answer-Context Dependencies for Effective Answer Sentence Selection](https://ankit-ai.github.io/papers/question-context-alignment-answer-sentence-selection/)**. INTERSPEECH 2023. Instead of pasting neighboring sentences onto the question, this model matches question words to context words and builds a small sentence graph, raising top-1 answer accuracy on WikiQA from 68.09 to 74.16.
- **[Controlled Text Generation with Hidden Representation Transformations](https://ankit-ai.github.io/papers/controlled-text-generation-hidden-representation-transformations/)**. Findings of ACL 2023. CHRT steers a language model away from toxic or negative text by editing its internal number vectors, cutting toxicity from 0.827 to 0.085 while adding only 0.01 seconds per generation.
- **[Cross-Lingual Knowledge Distillation for Answer Sentence Selection in Low-Resource Languages](https://ankit-ai.github.io/papers/cross-lingual-knowledge-distillation-answer-sentence-selection/)**. Findings of ACL 2023. The paper trains answer-ranking models for languages with no labeled data by copying the soft scores of a strong English model, lifting Arabic accuracy on translated WikiQA from 64.2 to 76.3.
- **[Efficient Fine-Tuning Large Language Models for Knowledge-Aware Response Planning](https://ankit-ai.github.io/papers/efficient-fine-tuning-knowledge-aware-response-planning/)**. ECML PKDD 2023 (Research Track), LNAI 14170. The paper fine-tunes a question-answering model twice, once with retrieved web text and once without, so it can fall back on what it already knows; end-to-end accuracy rises 7.40% over a ranking baseline.
- **[WDRASS: A Web-scale Dataset for Document Retrieval and Answer Sentence Selection](https://ankit-ai.github.io/papers/wdrass-web-scale-document-retrieval-answer-sentence-selection/)**. CIKM 2022. WDRASS introduced a web-scale open-domain question answering dataset with 64,000 questions and 800,000+ labeled passages and sentences drawn from 30 million documents.
- **[Training Mixed-Domain Translation Models via Federated Learning](https://ankit-ai.github.io/papers/federated-learning-mixed-domain-translation/)**. NAACL 2022 (Main Conference). Five domain-specific translation models use federated learning to build a mixed-domain neural machine translation system without pooling their data, with a method for selecting impactful parameters to control communication bandwidth.
- **[Communication-Efficient Federated Learning for Neural Machine Translation](https://ankit-ai.github.io/papers/communication-efficient-federated-learning-nmt/)**. NeurIPS 2021 ENLSP Workshop. To train translation models across separate data owners, the authors share only a few small added "Controller" layers, cutting exchanged parameters about six times with average translation quality slightly above the matched baseline.

Preprints.

- **[ACM -- Attribute Conditioning for Abstractive Multi Document Summarization](https://ankit-ai.github.io/papers/attribute-conditioning-multi-document-summarization/)**. arXiv preprint. Adds a sentiment and polarity classifier to a news multi-document summarizer so it sticks to one viewpoint, raising the word-overlap ROUGE-1 score on MultiNews from 42.99 to 50.12 versus GraphSum.
- **[Deep Reinforced Self-Attention Masks for Abstractive Summarization (DR.SAS)](https://ankit-ai.github.io/papers/dr-sas-deep-reinforced-self-attention-masks/)**. arXiv preprint. Adds a reinforcement-learning agent that decides which input words a summarizer should ignore, raising the word-overlap score ROUGE-1 on CNN/Daily Mail news from 40.79 to 41.89 against fine-tuned UniLM.
- **[BERTQA -- Attention on Steroids](https://ankit-ai.github.io/papers/bertqa-attention-on-steroids/)**. arXiv preprint. Adds two extra attention layers to BERT so a question and its passage look at each other directly, which lifts SQuAD 2.0 dev F1 from 74.15 to 77.03 on the base model.

Earlier undergraduate work in signal processing, image processing and
steganography is listed on the [publications page](https://ankit-ai.github.io/publications/).

---

### Patents

- **[Natural language question answering](https://patents.google.com/patent/US12632478B1/en)**, US 12,632,478 B1. Amazon Technologies, Inc., granted 2026-05-19.
- **[Feedback-based multimodal fragment retrieval system](https://patents.google.com/patent/US12547623B1/en)**, US 12,547,623 B1. Amazon Technologies, Inc., granted 2026-02-10.

---

### Elsewhere

- [Google Scholar](https://scholar.google.com/citations?user=hcslcm0AAAAJ&view_op=list_works&sortby=pubdate)
- [LinkedIn](https://www.linkedin.com/in/ankitrc/)
- [ACL Anthology](https://aclanthology.org/people/ankit-chadha/)
- [Amazon Science](https://www.amazon.science/author/ankit-chadha)
- [X](https://x.com/ankitrchadha)

<!-- Generated by _build/make_profile_readme.py from _build/site.json,
     _build/papers.json and _build/content.json. Do not hand-edit: edit the
     JSON in the ankit-ai.github.io repo and regenerate, so the profile and
     the site never disagree. -->
