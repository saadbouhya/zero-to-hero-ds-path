# Data Scientist / AI Engineer — Roadmap 

## Phase 1: Mathematical Foundations (Months 1-3)

### Linear Algebra — `Critical`

- [ ] Vectors, matrices, operations, rank, determinants — *MIT 18.06 (Gilbert Strang) — YouTube*
- [ ] Eigenvalues, eigenvectors, eigendecomposition — *Mathematics for ML — Ch. 2-4 (free PDF)*
- [ ] SVD — understand it geometrically and computationally — *3Blue1Brown — Essence of Linear Algebra*
- [ ] PCA — derive from scratch using SVD — *Implement PCA from scratch in NumPy*
- [ ] Matrix calculus (Jacobians, Hessians) — *Mathematics for ML — Ch. 5*

### Probability & Statistics — `Critical`

- [ ] Probability distributions, Bayes theorem, conditional prob — *MIT 6.041 (Tsitsiklis) or StatQuest YouTube*
- [ ] Maximum Likelihood Estimation — derive for Gaussian, Bernoulli — *Mathematics for ML — Ch. 8-9*
- [ ] Bayesian inference — priors, posteriors, MAP estimation — *Implement MLE/MAP from scratch*
- [ ] Hypothesis testing, confidence intervals, p-values — *All of Statistics — Wasserman (Ch. 1-12)*
- [ ] Information theory: entropy, KL divergence, cross-entropy — *Elements of Information Theory (Ch. 1-2)*

### Optimization — `Critical`

- [ ] Gradient descent — derive, implement, visualize convergence — *Boyd — Convex Optimization (Ch. 1-4, free)*
- [ ] SGD, momentum, Adam — understand why each was invented — *Implement SGD + Adam from scratch*
- [ ] Convexity, Lagrange multipliers, constrained optimization — *Mathematics for ML — Ch. 7*

---

## Phase 2: ML Fundamentals — Deep Understanding (Months 2-4)

### Core ML Theory — `Critical`

- [ ] Bias-variance tradeoff — intuition, not just the formula — *Stanford CS229 lectures (YouTube)*
- [ ] Regularization: L1 vs L2 — geometric and probabilistic view — *CS229 lecture notes*
- [ ] Derive linear regression from scratch (OLS, gradient descent) — *Implement from scratch in NumPy*
- [ ] Derive logistic regression from scratch — *Implement from scratch in NumPy*
- [ ] SVMs — max margin, kernel trick, dual formulation — *CS229 lecture notes + Patrick Winston MIT lecture*
- [ ] Decision trees, Random Forests, boosting (XGBoost/LightGBM) — *Hands-On ML — Géron (Ch. 6-7)*

### Evaluation & Methodology — `Critical`

- [ ] Metrics: accuracy, precision, recall, F1, PR-AUC, ROC-AUC — *Implement PR-AUC calculation from scratch*
- [ ] When to use which metric — imbalanced classes, ranking, etc. — *Applied Predictive Modeling — Kuhn & Johnson*
- [ ] Cross-validation: k-fold, stratified, time-series split, grouped — *sklearn docs + implement time series CV*
- [ ] Feature engineering: when it matters more than model choice — *Kaggle notebooks from top competitions*
- [ ] Feature selection: filter, wrapper, embedded methods — *Hands-On ML — Géron (Ch. 2)*

### Unsupervised Learning — `High`

- [ ] Clustering: K-means, DBSCAN, hierarchical — when to use each — *CS229 unsupervised learning lectures*
- [ ] Dimensionality reduction: PCA, t-SNE, UMAP — *Implement PCA, understand t-SNE perplexity*
- [ ] Anomaly detection methods — *Hands-On ML — Géron (Ch. 9)*

---

## Phase 3: Deep Learning — From Scratch (Months 4-7)

### Neural Network Foundations — `Critical`

- [ ] Backpropagation — derive mathematically, implement from scratch — *Karpathy — Neural Networks: Zero to Hero (video 1-2)*
- [ ] Build a neural network from scratch (no PyTorch) — *micrograd then makemore (Karpathy series)*
- [ ] Activation functions: ReLU, GELU, sigmoid — why each exists — *Deep Learning — Goodfellow et al. (Ch. 6)*
- [ ] Batch norm, layer norm, dropout — what they do and why — *Original papers + implement in PyTorch*
- [ ] Weight initialization (Xavier, He) — why it matters — *Deep Learning — Goodfellow et al. (Ch. 8)*

### CNNs and RNNs — `High`

- [ ] Convolutions — implement a conv layer from scratch — *CS231n (Stanford) — lectures + assignments*
- [ ] RNNs, LSTMs, GRUs — vanishing gradient problem — *Karpathy — The Unreasonable Effectiveness of RNNs*
- [ ] Sequence-to-sequence models and attention (pre-Transformer) — *Illustrated Guide to Attention (Jay Alammar)*

### Transformers — The Core Architecture — `Critical`

- [ ] Self-attention mechanism — derive and implement from scratch — *Attention Is All You Need paper*
- [ ] Multi-head attention, positional encoding, feed-forward layers — *Karpathy — Let's build GPT (video)*
- [ ] Build a GPT from scratch (character-level language model) — *nanoGPT (Karpathy) — implement yourself*
- [ ] BERT vs GPT: encoder vs decoder, MLM vs autoregressive — *Jay Alammar — Illustrated BERT/GPT*
- [ ] Layer norm placement (pre vs post), KV cache for inference — *Annotated Transformer (Harvard NLP)*

### Modern Deep Learning — `High`

- [ ] LoRA, QLoRA — parameter-efficient fine-tuning — *Original LoRA paper + HuggingFace PEFT docs*
- [ ] RLHF, DPO — alignment techniques — *InstructGPT paper + Anthropic RLHF paper*
- [ ] Mixture of Experts (MoE) architecture — *Switch Transformer paper*
- [ ] Quantization: GPTQ, AWQ, GGUF — inference optimization — *HuggingFace quantization docs*
- [ ] Diffusion models (optional, if interested in multimodal) — *Lilian Weng — What are Diffusion Models?*

---

## Phase 4: LLMs & AI Engineering (Months 6-9)

### RAG Systems — `Critical`

- [ ] Chunking strategies: fixed, semantic, recursive — *LangChain/LlamaIndex docs + experiment*
- [ ] Embedding models: comparison, fine-tuning for domain — *MTEB leaderboard + sentence-transformers*
- [ ] Vector databases: FAISS, Qdrant, Pinecone — tradeoffs — *Build a RAG system from scratch (no framework)*
- [ ] Retrieval evaluation: MRR, NDCG, recall@k — *Implement retrieval evaluation pipeline*
- [ ] Reranking: cross-encoders, ColBERT — *Experiment with rerankers on your RAG system*
- [ ] Advanced RAG: HyDE, multi-query, agentic retrieval — *Research papers + LlamaIndex advanced guides*

### LLM Fine-tuning & Evaluation — `Critical`

- [ ] Dataset curation — quality over quantity — *Alpaca / LIMA papers on data quality*
- [ ] Fine-tuning with LoRA on a real task — *HuggingFace TRL + your own dataset*
- [ ] Evaluation beyond vibes: LLM-as-judge, human eval protocols — *LMSYS Chatbot Arena methodology*
- [ ] Prompt engineering — systematic, not ad hoc — *Anthropic prompt engineering guide*

### Agents & Tool Use — `High`

- [ ] Agent architectures: ReAct, Plan-and-Execute, multi-agent — *LangGraph docs + build a real agent*
- [ ] Tool use / function calling with LLMs — *OpenAI / Anthropic function calling docs*
- [ ] Evaluation and reliability of agent systems — *Agent evaluation frameworks*

---

## Phase 5: Systems & Engineering (Months 5-9)

### Production Python — `Critical`

- [ ] Fluent Python (Ramalho) — Part I, III, V — *Read + implement examples*
- [ ] Architecture Patterns with Python (Percival & Gregory) — *Apply to a real project*
- [ ] Type hints, pydantic, dataclasses — clean data modeling — *Refactor existing project code*
- [ ] Testing: pytest, fixtures, mocking, TDD basics — *Write tests for one of your projects*
- [ ] Async Python: asyncio, aiohttp basics — *Python docs + Real Python tutorials*

### ML Infrastructure — `High`

- [ ] Docker — containerize an ML model for serving — *Docker docs + build a serving container*
- [ ] CI/CD for ML projects (GitHub Actions / Azure DevOps) — *Set up a pipeline for one project*
- [ ] Model serving: FastAPI, TorchServe, or vLLM — *Build and deploy a model API*
- [ ] Experiment tracking: MLflow or Weights & Biases — *Integrate into a training pipeline*
- [ ] Cloud: AWS SageMaker or GCP Vertex AI basics — *Deploy a model to one cloud platform*

### ML System Design — `Critical`

- [ ] Designing Machine Learning Systems — Chip Huyen (full book) — *Read cover to cover*
- [ ] Feature stores, online vs offline serving — *Chip Huyen book + Feast docs*
- [ ] Model monitoring, data drift, concept drift — *Evidently AI / WhyLabs docs*
- [ ] Practice system design: recommendation, search ranking, fraud — *ML System Design Interview — Alex Xu*

---

## Phase 6: Interview Preparation (Months 9-12)

### Coding Interviews (LeetCode) — `Critical`

- [ ] Arrays & strings — two pointers, sliding window — *Neetcode 150*
- [ ] Hash maps and sets — *Neetcode 150*
- [ ] Trees and graphs — BFS, DFS, topological sort — *Neetcode 150*
- [ ] Dynamic programming — 1D, 2D, common patterns — *Neetcode 150*
- [ ] Binary search, stack, heap, linked lists — *Neetcode 150*
- [ ] Mock interviews — timed, whiteboard-style — *Pramp / interviewing.io (free mock interviews)*

### ML Theory Interviews — `Critical`

- [ ] Explain gradient descent from scratch — *Practice whiteboard explanations*
- [ ] Walk through backprop for a simple network — *Practice on paper*
- [ ] Explain Transformer attention mechanism — *Practice 5-min explanation*
- [ ] Bias-variance, overfitting diagnosis and remedies — *Prep 2-3 case examples from your work*
- [ ] Loss functions: when to use MSE, cross-entropy, focal loss — *Derive each from first principles*

### ML System Design Interviews — `Critical`

- [ ] Design a recommendation system end-to-end — *ML System Design Interview — Alex Xu*
- [ ] Design a search ranking system — *Practice with a friend or mock interview*
- [ ] Design a fraud detection system — *Practice with a friend or mock interview*
- [ ] Design an NLP classification pipeline at scale — *Use your Spendlytics experience as basis*

### Behavioral Interviews — `High`

- [ ] Prepare 5-6 STAR stories from your projects — *Focus on: ambiguity, failure, impact, conflict*
- [ ] Why this company? Why this role? (for each target) — *Research each company's ML blog and papers*
- [ ] Questions to ask interviewers — *Prepare 3-4 thoughtful questions per company*

---

## Phase 7: Portfolio & Visibility (Ongoing)

### Portfolio Projects — `Critical`

- [ ] Write up Spendlytics (architecture, tradeoffs, results) — *Technical blog post or GitHub README*
- [ ] Build one end-to-end project outside work (open source) — *Choose: forecasting, RAG system, or agent*
- [ ] Contribute to an open source ML library (even small PRs) — *HuggingFace, LangChain, or scikit-learn*

### Technical Writing & Visibility — `High`

- [ ] Start a technical blog (even 1 post/month) — *Write about what you learn, not what you know*
- [ ] Share on LinkedIn / Twitter with substance — *Not hype — real insights from your work*
- [ ] Build a clean GitHub profile with pinned repos — *README files, clean code, documentation*
