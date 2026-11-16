<div align="center">

# Vijayakumar S

### AI/ML Engineer

Language models, speech, retrieval and agents, built to run in production.

<p>
<a href="mailto:vijay.aieng@gmail.com"><img src="https://img.shields.io/badge/Email-vijay.aieng@gmail.com-1E293B?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/vijay-aieng/"><img src="https://img.shields.io/badge/LinkedIn-vijay--aieng-1E293B?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://vijayai.site"><img src="https://img.shields.io/badge/Portfolio-vijayai.site-1E293B?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://github.com/VijayAIeng"><img src="https://img.shields.io/badge/GitHub-VijayAIeng-1E293B?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

</div>

---

## About

I am an AI/ML Engineer. My work sits on the model side: fine-tuning, inference speed, retrieval quality and speech. I also build the services and agents around the models, so they keep working outside a notebook.

I work at Tapaya Technologies LLP, where I build **Brahm Studio**, an AI website builder for React sites. I care most about the parts people skip: clean tool contracts, safe permissions, evaluation numbers, and recovery when something fails.

I use AI coding assistants every day. They write the first draft, and I read it, run it and try to break it before I trust it. I do not merge code I cannot explain.

---

## Highlights

| Metric | Result |
|---|---|
| Voice pipeline latency | Under 500 ms |
| Infrastructure cost | 30% lower after GPU batching and quantization |
| Retrieval scale | More than 1 million documents |
| Research | Presented at LIMMITS 2024 and 2025 |

---

## What I Do With Models

| Area | What I work on | Tools |
|---|---|---|
| **Language models** | Fine-tuning with SFT, LoRA, QLoRA, PEFT and DPO. Evaluation. Tool calling and structured output. | PyTorch, Hugging Face Transformers |
| **Inference and serving** | KV cache, batching, quantization, speculative decoding. Lower latency and lower cost per request. | vLLM, Ollama, ONNX, TensorRT, DeepSpeed |
| **Speech** | Speech recognition, text to speech, multilingual voice cloning. | Whisper, wav2vec 2.0, XTTS-v2, StyleTTS2, VITS |
| **Retrieval** | Chunking, embeddings, hybrid search, reranking, graph retrieval. | BGE-M3, Weaviate, Qdrant, FAISS, Neo4j |
| **Agents** | Tool-using workflows with memory, step limits and review. | LangGraph, LangChain, CrewAI, MCP |
| **Model operations** | Experiment tracking, evaluation, CI/CD, monitoring. | MLflow, Docker, Kubernetes, FastAPI |

---

## Current Work: Brahm Studio

Brahm Studio is an AI website builder for React. A chat assistant, a visual design canvas and tool-using agents work together on the same page. You can describe a page and let the model build it, or edit it by hand on the canvas, and both stay in sync. The implementation is confidential, so I can only share the overview.

**My part**

- End-to-end work across the interface, the agent layer and the backend.
- Designing how an agent receives context, chooses tools and recovers from errors.
- Streaming results live so the product feels fast.
- Safety by design: clear permissions, hard limits and one-click undo for AI changes.

---

## How an Agent Works

An agent is a loop: read context, reason, call a tool, read the result, repeat until the task is done. I use MCP to expose tools in a standard way, so the host decides exactly what each tool can touch.

| Part | How I build it |
|---|---|
| **Tools** | Small and single-purpose, with JSON Schema inputs. Errors return as readable text so the model can recover. |
| **Context** | Large state is summarized and size-capped before it reaches the model. |
| **Streaming** | Typed events for text, tool calls, results and errors. |
| **Guardrails** | Step limits, abort control, path sandboxing, authentication, read-only modes. |
| **Review and undo** | Proposed changes pass a review step. AI edits are grouped and can be undone together. |

---

## Experience

### AI / ML Engineer
**Tapaya Technologies LLP** | Remote, India | Jul 2024 to Present

- **Brahm Studio:** React website builder with a design canvas and tool-using agents.
- **Conversational voice AI:** Streaming pipeline with Whisper, Llama 3 and XTTS-v2 over WebSockets and Kubernetes. Reached sub-500 ms latency and cut infrastructure cost by 30% with GPU batching and quantization.
- **Enterprise retrieval:** Hybrid search with BGE-M3, Weaviate and Neo4j over more than one million documents.
- **Agent workflows:** LangGraph and CrewAI workflows with persistent context and multi-step tasks.
- **Speech research:** Shabdh, a multilingual zero-shot voice cloning project, presented at LIMMITS'24 and LIMMITS'25.

### Machine Learning Engineer Intern
**Tapaya Technologies LLP** | Oct 2023 to Jun 2024

- Fine-tuned speech recognition and synthesis models on multilingual audio with LoRA and PEFT.
- Used MLflow and CI/CD for evaluation and tracking.
- Reached an 18% word error rate on one ASR project.

### Data Scientist Intern
**Simplilearn** | India | Nov 2022 to Sep 2023

- Built and evaluated classification, regression and NLP models, and summarized results for decisions.

---

## Selected Projects

| Project | What it is | Stack |
|---|---|---|
| **Shabdh** | Multilingual zero-shot voice cloning | PyTorch, XTTS-v2, ASR, TTS |
| **EMOD** | Expressive speech synthesis | PyTorch, StyleTTS2 |
| **Enterprise RAG Platform** | Hybrid retrieval over a large document collection | LangChain, Weaviate, Neo4j |
| **Streaming Conversational Agent** | Real-time voice agent | FastAPI, LangGraph, WebSockets |

---

## Currently Building

These are personal projects I am working on to go deeper into models. They are in progress.

- **VIJI-LLM:** My own conversational language model, built as a modular Python project: data preparation, tokenizer, model layers, training, evaluation, inference and fine-tuning.
- **Text-to-image model:** A latent diffusion transformer (DiT) sized for laptops and phones, trained on a MacBook.
- **Agent framework:** A small Python framework with an Agent, Task and Crew style API, running on local models.

---

## How I Work

- I write the output contract first, then generate code.
- I test failure paths first: bad input, dropped streams, hostile paths.
- I keep secrets out of prompts and code, and ship an example env file.
- I build the thinnest working slice, then widen it.
- I always measure before and after a change, so I know the number.

---

## Technical Skills

| Category | Skills |
|---|---|
| **LLMs and GenAI** | Transformers, prompt design, structured output, tool calling, LoRA, QLoRA, PEFT, vLLM, Ollama |
| **Agents and MCP** | LangGraph, LangChain, LlamaIndex, CrewAI, AutoGen, MCP servers and clients, JSON-RPC 2.0, NDJSON, SSE |
| **RAG and Search** | Chunking, embeddings, hybrid search, reranking, FAISS, Qdrant, Weaviate, ChromaDB, Elasticsearch, Neo4j |
| **Speech AI** | ASR, TTS, Whisper, wav2vec 2.0, XTTS-v2, StyleTTS2, VITS, Bark, voice cloning |
| **ML and DL** | Python, NumPy, pandas, scikit-learn, PyTorch, TensorFlow, Hugging Face, OpenCV, CLIP, YOLO |
| **Model operations** | MLflow, ONNX, TensorRT, DeepSpeed, quantization, evaluation, experiment tracking |
| **Backend and data** | FastAPI, REST, WebSockets, PostgreSQL, Redis, MongoDB, SQL, async processing |
| **Cloud and infra** | Docker, Kubernetes, AWS, GCP, CI/CD, GPU workloads, monitoring |
| **Application** | TypeScript, React, Next.js |

---

## Repositories

Learning and build repos, each with code, notes and setup steps.

| Repository | Covers |
|---|---|
| [LLMs from Scratch to Production](https://github.com/VijayAIeng/llms-from-scratch-to-production) | Pretraining, fine-tuning, evaluation, inference, deployment |
| [Transformers from Scratch](https://github.com/VijayAIeng/transformers-from-scratch) | Attention, positional encoding, full architecture |
| [LLM Fine-Tuning](https://github.com/VijayAIeng/llm-finetuning-from-scratch-to-production) | SFT, LoRA, QLoRA, PEFT, DPO |
| [LLM Inference](https://github.com/VijayAIeng/llm-inference-from-scratch-to-production) | KV cache, batching, quantization, speculative decoding |
| [Mixture of Experts from Scratch](https://github.com/VijayAIeng/moe-from-scratch) | Expert routing and sparse activation |
| [Distributed AI Training](https://github.com/VijayAIeng/distributed-ai-training-from-scratch) | DDP, FSDP, tensor and pipeline parallelism |
| [Agents from Scratch to Production](https://github.com/VijayAIeng/agents-from-scratch-to-production) | Planning, tools, memory, MCP, multi-agent workflows |
| [Complete RAG from Scratch to Production](https://github.com/VijayAIeng/Complete-rag-from-scratch-to-production) | Chunking, embeddings, hybrid search, reranking |
| [LLMOps](https://github.com/VijayAIeng/llmops-from-development-to-production) | Evaluation, tracing, monitoring |
| [AI Safety, Security and Guardrails](https://github.com/VijayAIeng/ai-safety-security-and-guardrails) | Prompt injection, jailbreaks, agent security |
| [Production AI Backend with FastAPI](https://github.com/VijayAIeng/production-ai-backend-with-fastapi) | Async APIs, authentication, streaming |
| [AI System Design](https://github.com/VijayAIeng/ai-system-design) | Architecture for LLM, RAG and agent systems |

---

## Education

**B.E. in Computer Science and Engineering**
Sasurie Academy of Engineering, Coimbatore | 2016 to 2020

**Courses and certifications**

- DeepLearning.AI, LLM Specialization
- LangChain, Application Development
- Hugging Face, NLP Course
- fast.ai, Practical Deep Learning
- AWS Cloud Practitioner, in progress

---

<div align="center">

### Let's talk

<p>
<a href="mailto:vijay.aieng@gmail.com"><img src="https://img.shields.io/badge/Email-vijay.aieng@gmail.com-1E293B?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/vijay-aieng/"><img src="https://img.shields.io/badge/LinkedIn-vijay--aieng-1E293B?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://vijayai.site"><img src="https://img.shields.io/badge/Portfolio-vijayai.site-1E293B?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://github.com/VijayAIeng"><img src="https://img.shields.io/badge/GitHub-VijayAIeng-1E293B?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

</div>
