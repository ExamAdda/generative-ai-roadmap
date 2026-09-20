# Generative AI Roadmap: Beginner to Production

> A practical, project-based path to master Generative AI, Large Language Models (LLMs), RAG, AI agents, fine-tuning, multimodal AI, evaluation, safety, and production deployment.


[![Made by ExamAdda](https://img.shields.io/badge/Made%20by-ExamAdda-6d28d9)](https://examadda.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

[![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-7C3AED)](https://tech.examadda.org/genai/roadmap)
[![Learning](https://img.shields.io/badge/Learning-Articles%20%7C%20Videos%20%7C%20Practice-2563EB)](https://tech.examadda.org/genai)
[![Projects](https://img.shields.io/badge/Projects-10%2B-059669)](#portfolio-projects)
[![Interview](https://img.shields.io/badge/Interview-Preparation-F59E0B)](INTERVIEWS.md)

## Quick Links

- [Complete Learning Path](#complete-learning-path)
- [Portfolio Projects](#portfolio-projects)
- [Suggested Study Plan](#suggested-study-plan)
- [Interview Preparation](INTERVIEWS.md)
- [Contributing Guide](CONTRIBUTING.md)
- [License](LICENSE)

## What You Will Learn

- Understand AI, ML, deep learning, transformers, and LLM fundamentals.
- Build reliable prompts, structured outputs, and tool-calling workflows.
- Create semantic search and production-ready RAG applications.
- Design single-agent and multi-agent systems with memory and guardrails.
- Fine-tune, evaluate, secure, deploy, monitor, and optimize GenAI systems.
- Build a portfolio of real-world projects and prepare for GenAI interviews.

Use this page as the main roadmap, then jump to the linked interview guide, contribution guide, and ExamAdda tutorials when you need deeper practice.

## Complete Learning Path

```mermaid
flowchart TD
    A["1. Foundations"] --> B["2. ML and Deep Learning"]
    B --> C["3. Transformers and LLMs"]
    C --> D["4. Prompt Engineering"]
    D --> E["5. Embeddings and Vector Search"]
    E --> F["6. RAG Systems"]
    F --> G["7. AI Agents and Frameworks"]
    G --> H["8. Fine-Tuning and Alignment"]
    H --> I["9. Multimodal AI"]
    I --> J["10. Evaluation, Safety and LLMOps"]
    J --> K["11. Production Projects and Interviews"]

    classDef foundation fill:#DBEAFE,stroke:#2563EB,color:#172554,stroke-width:2px;
    classDef core fill:#EDE9FE,stroke:#7C3AED,color:#2E1065,stroke-width:2px;
    classDef build fill:#D1FAE5,stroke:#059669,color:#022C22,stroke-width:2px;
    classDef advanced fill:#FEF3C7,stroke:#D97706,color:#451A03,stroke-width:2px;
    classDef career fill:#FFE4E6,stroke:#E11D48,color:#4C0519,stroke-width:2px;

    class A,B foundation;
    class C,D,E core;
    class F,G build;
    class H,I,J advanced;
    class K career;
```

> Follow the phases in order. Complete at least one practice task and one project checkpoint before advancing.



### Basic GenAI

- [Roadmap](https://tech.examadda.org/genai/roadmap)
- [Beginner Interview Questions](https://tech.examadda.org/genai/beginner-interview-questions)
- [Intermediate Interview Questions](https://tech.examadda.org/genai/intermediate-interview-questions)
- [Advanced Interview Questions](https://tech.examadda.org/genai/advanced-interview-questions)
- [Scenario-Based Interview Questions](https://tech.examadda.org/genai/scenario-based-interview-questions)
- [Introduction of AI](https://tech.examadda.org/genai/introduction-to-artificial-intelligence)
- [Introduction of GenAI](https://tech.examadda.org/genai/introduction-to-generative-ai)
- [History of GenAI](https://tech.examadda.org/genai/history-of-generative-ai-1)

- ML in GenAI

  - [Introduction of ML](https://tech.examadda.org/genai/introduction-to-machine-learning-1)
  - [Supervised Learning](https://tech.examadda.org/genai/supervised-learning-1)
  - [Unsupervised Learning](https://tech.examadda.org/genai/unsupervised-learning)
  - [Reinforcement Learning](https://tech.examadda.org/genai/reinforcement-learning)
  - [Overfitting & Underfitting](https://tech.examadda.org/genai/overfitting-and-underfitting)
  - [Model Evaluation Basics](https://tech.examadda.org/genai/model-evaluation-basics)
  
- Deep Learning in GenAI

  - [Introduction to Deep Learning](https://tech.examadda.org/genai/introduction-to-deep-learning)
  - [Neural Networks](https://tech.examadda.org/genai/neural-networks)
  - [Activation Functions](https://tech.examadda.org/genai/activation-functions-in-neural-networks)
  - [Loss Functions](https://tech.examadda.org/genai/loss-functions-in-deep-learning)
  - [CNN, RNN & LSTM](https://tech.examadda.org/genai/cnn-rnn-and-lstm)

- Generative AI Models

  - [Autoencoders](https://tech.examadda.org/genai/autoencoders)
  - [Variational Autoencoders (VAE)](https://tech.examadda.org/genai/variational-autoencoders-vae)
  - [GANs (Generative Adversarial Networks)](https://tech.examadda.org/genai/generative-adversarial-networks-gans)
  - [Diffusion Models](https://tech.examadda.org/genai/diffusion-models)
  - [Model Comparison](https://tech.examadda.org/genai/generative-ai-model-comparison)

- Core GenAI

  - [Parameters & Model Size](https://tech.examadda.org/genai/parameters-and-model-size)
  - [Training vs Inference](https://tech.examadda.org/genai/training-vs-inference-in-generative-ai)
  - [Fine-Tuning Basics](https://tech.examadda.org/genai/fine-tuning-basics)
  - [GPU & Compute Fundamentals](https://tech.examadda.org/genai/gpu-and-compute-fundamentals)

- GenAI Tools & Ecosystem

  - [PyTorch](https://tech.examadda.org/genai/pytorch-for-generative-ai)
  - [TensorFlow](https://tech.examadda.org/genai/tensorflow-for-generative-ai)
  - [Hugging Face](https://tech.examadda.org/genai/hugging-face-for-generative-ai)
  - [Model Hubs & Datasets](https://tech.examadda.org/genai/model-hubs-and-datasets)

---

### LLM

- [Introduction of LLM](https://tech.examadda.org/genai/introduction-to-large-language-models)
- [Model Parameters](https://tech.examadda.org/genai/model-parameters)
- [Scaling Laws](https://tech.examadda.org/genai/scaling-laws)
- [Context Window](https://tech.examadda.org/genai/context-window)
- [Tokens](https://tech.examadda.org/genai/tokens)
- [Tokenizers](https://tech.examadda.org/genai/tokenizers)
- [Split into Tokens](https://tech.examadda.org/genai/split-into-tokens)

- Output Controls

  - [Temperature](https://tech.examadda.org/genai/temperature)
  - [Top-P](https://tech.examadda.org/genai/top-p-sampling)
  - [Top-K](https://tech.examadda.org/genai/top-k-sampling)
  - [Max Tokens](https://tech.examadda.org/genai/max-tokens)

- LLM Behavior

  - [Hallucinations](https://tech.examadda.org/genai/hallucinations-in-llms)
  - [Emergent Abilities](https://tech.examadda.org/genai/emergent-abilities-in-llms)
  - [Reasoning Limitations](https://tech.examadda.org/genai/reasoning-limitations-in-llms)

- Popular Models

  - [GPT](https://tech.examadda.org/genai/gpt)
  - [Claude](https://tech.examadda.org/genai/claude)
  - [Llama](https://tech.examadda.org/genai/llama)
  - [DeepSeek](https://tech.examadda.org/genai/deepseek)
  - [Open-source Models](https://tech.examadda.org/genai/open-source-llms)

---

### Transformer Models

- [Limitations of RNN/LSTM](https://tech.examadda.org/genai/limitations-of-rnn-and-lstm)
- [Transformer Architecture](https://tech.examadda.org/genai/transformer-architecture)
- [Attention Is All You Need](https://tech.examadda.org/genai/attention-is-all-you-need)
- [Tokens & Embeddings](https://tech.examadda.org/genai/tokens-and-embeddings)
- [Positional Encoding](https://tech.examadda.org/genai/positional-encoding)
- [Encoder & Decoder](https://tech.examadda.org/genai/encoder-and-decoder)

- Transformer Block

  - [Feed Forward Network (FFN)](https://tech.examadda.org/genai/feed-forward-network-ffn)
  - [Residual Connections](https://tech.examadda.org/genai/residual-connections)
  - [Layer Normalization](https://tech.examadda.org/genai/layer-normalization)

- Transformer Variants

  - [BERT (Encoder)](https://tech.examadda.org/genai/bert-encoder)
  - [GPT (Decoder)](https://tech.examadda.org/genai/gpt-decoder)
  - [T5 (Encoder–Decoder)](https://tech.examadda.org/genai/t5-encoder-decoder)

- Attention Mechanism

  - [Self-Attention](https://tech.examadda.org/genai/self-attention)
  - [Query, Key, Value (QKV)](https://tech.examadda.org/genai/query-key-value)
  - [Multi-Head Attention](https://tech.examadda.org/genai/multi-head-attention)
  - [Cross-Attention](https://tech.examadda.org/genai/cross-attention)

- [Next Token Prediction](https://tech.examadda.org/genai/next-token-prediction)

---

### Prompt Engineering

- [Introduction of Prompt](https://tech.examadda.org/genai/introduction-to-prompts)
- [System Prompt](https://tech.examadda.org/genai/system-prompt)
- [User Prompt](https://tech.examadda.org/genai/user-prompt)
- [Assistant Prompt](https://tech.examadda.org/genai/assistant-prompt)
- [Prompt Templates](https://tech.examadda.org/genai/prompt-templates)
- [Best Practices (Context, Constraints, Guardrails)](https://tech.examadda.org/genai/prompt-engineering-best-practices)

- Core Techniques

  - [Zero-Shot](https://tech.examadda.org/genai/zero-shot-prompting)
  - [One-Shot](https://tech.examadda.org/genai/one-shot-prompting)
  - [Few-Shot](https://tech.examadda.org/genai/few-shot-prompting)
  - [Role Prompting](https://tech.examadda.org/genai/role-prompting)
  - [Chain of Thought](https://tech.examadda.org/genai/chain-of-thought-prompting)
  - [Self-Consistency](https://tech.examadda.org/genai/self-consistency-prompting)
  - [ReAct](https://tech.examadda.org/genai/react-prompting)

- Structured Outputs

  - [JSON Output](https://tech.examadda.org/genai/json-output-prompting)
  - [Function Calling](https://tech.examadda.org/genai/function-calling)
  - [Tool Calling](https://tech.examadda.org/genai/tool-calling)

---

### Embeddings

- [Introduction of Embeddings](https://tech.examadda.org/genai/introduction-to-embeddings)
- [Text to Vectors](https://tech.examadda.org/genai/text-to-vectors)
- [Semantic Similarity](https://tech.examadda.org/genai/semantic-similarity)
- [Cosine Similarity](https://tech.examadda.org/genai/cosine-similarity)
- [Euclidean Distance](https://tech.examadda.org/genai/euclidean-distance)

- Embedding Models

  - [OpenAI Embeddings](https://tech.examadda.org/genai/openai-embeddings)
  - [Sentence Transformers](https://tech.examadda.org/genai/sentence-transformers)
  - [BGE Models](https://tech.examadda.org/genai/bge-models)
  - [E5 Models](https://tech.examadda.org/genai/e5-models)

---

### Vector Databases

- [Introduction of Vector Database](https://tech.examadda.org/genai/introduction-to-vector-databases)
- [Storing Embeddings](https://tech.examadda.org/genai/storing-embeddings)
- [Metadata Storage](https://tech.examadda.org/genai/metadata-storage)
- [Collections & Namespaces](https://tech.examadda.org/genai/collections-and-namespaces)
- [Similarity Search](https://tech.examadda.org/genai/similarity-search)
- [K-Nearest Neighbors (KNN)](https://tech.examadda.org/genai/k-nearest-neighbors)
- [Top-K Retrieval](https://tech.examadda.org/genai/top-k-retrieval)
- [ANN Search](https://tech.examadda.org/genai/approximate-nearest-neighbor-ann-search)

- Vector Databases

  - [Chroma](https://tech.examadda.org/genai/chroma-vector-database)
  - [FAISS](https://tech.examadda.org/genai/faiss-facebook-ai-similarity-search)
  - [Pinecone](https://tech.examadda.org/genai/pinecone-vector-database)
  - [Weaviate](https://tech.examadda.org/genai/weaviate-vector-database)

- Retrieval Optimization

  - [Metadata Filtering](https://tech.examadda.org/genai/metadata-filtering)
  - [Hybrid Search](https://tech.examadda.org/genai/hybrid-search)
  - [Reranking](https://tech.examadda.org/genai/reranking)
  - [Caching](https://tech.examadda.org/genai/caching-vector-databases)

---

### RAG

- [Introduction to RAG](https://tech.examadda.org/genai/introduction-to-rag)
- [RAG Architecture](https://tech.examadda.org/genai/rag-architecture)

- RAG Pipeline

  - [Document Loading](https://tech.examadda.org/genai/document-loading)
  - [Chunking](https://tech.examadda.org/genai/document-chunking)
  - [Embedding](https://tech.examadda.org/genai/embeddings-1)
  - [Storing](https://tech.examadda.org/genai/storing-embeddings-1)

- [Vector Search](https://tech.examadda.org/genai/vector-search-in-rag)
- [Hybrid Search](https://tech.examadda.org/genai/hybrid-search-in-rag)
- [Reranking](https://tech.examadda.org/genai/reranking-in-rag)
- [Parent-Child Retrieval](https://tech.examadda.org/genai/parent-child-retrieval)
- [Multi-Query Retrieval](https://tech.examadda.org/genai/multi-query-retrieval)
- [Graph RAG](https://tech.examadda.org/genai/graph-rag)

- Evaluation

  - [Recall](https://tech.examadda.org/genai/recall-rag)
  - [Precision](https://tech.examadda.org/genai/precision-rag)
  - [Faithfulness](https://tech.examadda.org/genai/faithfulness-rag)

---

### AI Agents

- [Introduction of AI Agent](https://tech.examadda.org/genai/introduction-to-ai-agents)
- [Planning](https://tech.examadda.org/genai/planning-ai-agents)
- [Memory](https://tech.examadda.org/genai/memory-ai-agents)
- [Reasoning](https://tech.examadda.org/genai/reasoning-ai-agents)
- [Tools](https://tech.examadda.org/genai/tools-ai-agents)

- Agent Patterns

  - [ReAct](https://tech.examadda.org/genai/react-agent-pattern)
  - [Plan & Execute](https://tech.examadda.org/genai/plan-and-execute-agent-pattern)
  - [Reflection](https://tech.examadda.org/genai/reflection-agent-pattern)

- Tool Usage

  - [Function Calling](https://tech.examadda.org/genai/function-calling-1)
  - [APIs](https://tech.examadda.org/genai/apis-in-ai-agents)
  - [Code Execution](https://tech.examadda.org/genai/code-execution-in-ai-agents)

- Multi-Agent Systems

  - [Agent Communication](https://tech.examadda.org/genai/agent-communication-in-ai-agents)
  - [Agent Collaboration](https://tech.examadda.org/genai/agent-collaboration-in-ai-agents)
  - [Task Delegation](https://tech.examadda.org/genai/task-delegation-in-ai-agents)
  - [Agent Orchestration](https://tech.examadda.org/genai/agent-orchestration-in-ai-agents)

---

### Agent Frameworks

- LangChain

  - [Introduction to LangChain](https://tech.examadda.org/genai/introduction-to-langchain)
  - [Tools](https://tech.examadda.org/genai/tools-in-langchain)
  - [Memory](https://tech.examadda.org/genai/langchain-memory)
  - [Retrievers](https://tech.examadda.org/genai/langchain-retrievers)
  - [Agents](https://tech.examadda.org/genai/langchain-agents)

- LlamaIndex

  - [Introduction to LlamaIndex](https://tech.examadda.org/genai/introduction-to-llamaindex)
  - [Indexing](https://tech.examadda.org/genai/llamaindex-indexing)
  - [Query Engines](https://tech.examadda.org/genai/llamaindex-query-engines)
  - [RAG Pipelines](https://tech.examadda.org/genai/llamaindex-rag-pipelines)

- LangGraph

  - [Introduction to LangGraph](https://tech.examadda.org/genai/introduction-to-langgraph)
  - [State Management](https://tech.examadda.org/genai/langgraph-state-management)
  - [Workflow Design](https://tech.examadda.org/genai/langgraph-workflow-design)
  - [Human-in-the-Loop](https://tech.examadda.org/genai/langgraph-human-in-the-loop)

---

### Fine-Tuning

- [Introduction to Tuning](https://tech.examadda.org/genai/introduction-to-tuning)

- Tuning Types

  - [Full Fine-Tuning](https://tech.examadda.org/genai/full-fine-tuning)
  - [Instruction Tuning](https://tech.examadda.org/genai/instruction-tuning)

- PEFT

  - [PEFT (Parameter-Efficient Fine-Tuning)](https://tech.examadda.org/genai/lora-low-rank-adaptation)

- [Data Collection](https://tech.examadda.org/genai/data-collection-for-fine-tuning)
- [Data Formatting](https://tech.examadda.org/genai/data-formatting-for-fine-tuning)
- [Benchmarks](https://tech.examadda.org/genai/benchmarks-for-fine-tuning)
- [Model Comparison](https://tech.examadda.org/genai/model-comparison)

---

### Multimodal AI

- [Introduction to Multimodal AI](https://tech.examadda.org/genai/introduction-to-multimodal-ai)
- [Multimodal LLM](https://tech.examadda.org/genai/multimodal-large-language-models)

- Modalities

  - [Text](https://tech.examadda.org/genai/text-modality)
  - [Image](https://tech.examadda.org/genai/image-modality)
  - [Audio](https://tech.examadda.org/genai/audio-modality)

---

## Portfolio Projects

| Level | Project | Core skills | Deliverables |
|:---:|---|---|---|
| 🟢 Beginner | AI text summarizer | Prompting, APIs, structured output | App, README, test cases |
| 🟢 Beginner | Resume feedback assistant | Prompt design, schemas, guardrails | Web UI, scoring rubric |
| 🟡 Intermediate | Semantic search engine | Embeddings, vector database, filters | Search API, evaluation set |
| 🟡 Intermediate | Chat with PDFs | Chunking, RAG, citations, history | Full-stack RAG application |
| 🟡 Intermediate | SQL analytics assistant | Tool calling, validation, permissions | Read-only database agent |
| 🟠 Advanced | Customer-support copilot | Hybrid retrieval, reranking, escalation | Production-style service |
| 🟠 Advanced | Multi-agent research system | Planning, tools, delegation, state | Traced agent workflow |
| 🔴 Expert | Domain-tuned LLM | Dataset design, LoRA/QLoRA, evaluation | Adapter, model card, benchmark |
| 🔴 Expert | Multimodal document analyst | OCR, vision-language model, RAG | Document processing platform |
| 🔴 Expert | Production GenAI platform | Gateway, evaluation, safety, LLMOps | Deployed, monitored capstone |

## Interview Preparation

For a focused interview path, use the companion [GenAI interview preparation guide](INTERVIEWS.md).

| Level | Resource | Recommended stage |
|:---:|---|---|
| 🟢 Beginner | [Beginner GenAI Interview Questions](https://tech.examadda.org/genai/beginner-interview-questions) | After Phase 3 |
| 🟡 Intermediate | [Intermediate GenAI Interview Questions](https://tech.examadda.org/genai/intermediate-interview-questions) | After Phase 6 |
| 🔴 Advanced | [Advanced GenAI Interview Questions](https://tech.examadda.org/genai/advanced-interview-questions) | After Phase 10 |
| 🟣 Scenario-based | [Scenario-Based GenAI Interview Questions](https://tech.examadda.org/genai/scenario-based-interview-questions) | During capstone preparation |

Focus on explaining trade-offs: model selection, prompting vs RAG vs fine-tuning, chunking strategy, retrieval quality, hallucination control, evaluation, latency, security, and cost.

## Suggested Study Plan

| Track | Duration | Weekly commitment | Best for |
|---|:---:|:---:|---|
| Fast track | 12 weeks | 15–20 hours | Developers building GenAI apps quickly |
| Balanced | 20 weeks | 8–12 hours | Working professionals |
| In-depth | 32 weeks | 5–8 hours | Learners including ML theory and fine-tuning |

### 20-Week Balanced Plan

| Weeks | Focus | Milestone |
|:---:|---|---|
| 1–2 | Foundations, ML and deep learning | Neural-network mini project |
| 3–5 | Transformers, LLMs and prompting | Structured-output application |
| 6–7 | Embeddings and vector databases | Semantic search engine |
| 8–10 | RAG and evaluation | RAG app with citations |
| 11–13 | Agents and frameworks | Tool-using agent |
| 14–15 | Fine-tuning and alignment | LoRA experiment |
| 16–17 | Multimodal AI | Multimodal mini project |
| 18–19 | Safety, evaluation and LLMOps | Production readiness report |
| 20 | Capstone and interview revision | Demo, README and case study |

## ✅ Completion Checklist

- [ ] Finish every core article and video lesson.
- [ ] Score at least 80% in phase quizzes.
- [ ] Complete practice exercises without copying the solution.
- [ ] Build at least three mini projects and one production-style capstone.
- [ ] Add evaluation datasets, automated tests, security controls, and cost metrics.
- [ ] Publish clear READMEs with architecture, setup, trade-offs, results, and demos.
- [ ] Revise beginner, intermediate, advanced, and scenario-based interview questions.

## Resource Link Convention

Replace these placeholders as content becomes available:

- `ARTICLE_URL` — detailed ExamAdda tutorial.
- `VIDEO_URL` — complete video lesson or solution.
- `PRACTICE_URL` — hands-on lab or coding exercise.
- `QUIZ_URL` — topic assessment.
- `REVISION_URL` — notes, flashcards, or cheat sheet.
- `PROJECT_URL` — guided project, starter repository, or solution.

---

## Learn with ExamAdda

- [Explore Generative AI Tutorials](https://tech.examadda.org/genai)
- [Open the Interactive GenAI Roadmap](https://tech.examadda.org/genai/roadmap)
- [View ExamAdda on GitHub](https://github.com/ExamAdda)
- [Explore ExamAdda Premium](https://examadda.org/premium)

> Learn the concept, watch the implementation, practise it yourself, build a project, evaluate the result, and then explain the trade-offs.


## Contributing

Corrections, explanations, test cases and implementations are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## About ExamAdda

[ExamAdda](https://examadda.org) is an all-in-one platform for mastering DSA, system design, development skills, and coding interviews through structured courses, hands-on practice, company-wise questions, and mock interviews.

**Learn smarter. Practice consistently. Crack top tech interviews.**

[Start Learning](https://tech.examadda.org/) • [Explore Courses](https://tech.examadda.org/courses/) • [Unlock ExamAdda Premium](https://examadda.org/premium)

## License

This repository is available under the [MIT License](LICENSE).
