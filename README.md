<div align="center">

<img src="./assets/banner.svg" alt="Vijayakumar S, AI/ML Engineer. Language models, speech, retrieval and agents, built to run in production." width="100%"/>

<p>
<a href="mailto:vijay.aieng@gmail.com"><img src="https://img.shields.io/badge/Email-vijay.aieng@gmail.com-1D4ED8?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/vijay-aieng/"><img src="https://img.shields.io/badge/LinkedIn-vijay--aieng-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://vijayai.site"><img src="https://img.shields.io/badge/Portfolio-vijayai.site-0E7490?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://github.com/VijayAIeng"><img src="https://img.shields.io/badge/GitHub-VijayAIeng-334155?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

</div>

---

<img src="./assets/h-about.svg" alt="About" width="100%"/>

I am an AI Engineer. I build models and LLMs and take them all the way to production. I work mostly on speech and language models, from the architecture and the data to training, fine-tuning and serving.

On the speech side, I have worked on zero-shot voice cloning and voice conversion. I contributed DIS-vector embeddings for voice conversion and EMOD for emotion extraction, and I worked with Transformer and VAE based architectures. I have fine-tuned VITS, XTTS and Whisper, and I handle the TTS data preparation and training as well.

On the language side, I have built Transformers and Mixture of Experts from scratch, and I work on fine-tuning and prompt engineering to get models ready for real products.

I work at Tapaya Technologies LLP, where I build Brahm Studio, an AI website builder for React sites with a design canvas and tool-using agents. I care most about the parts people skip: clean tool contracts, safe permissions, evaluation numbers, and recovery when something fails.

---

<img src="./assets/h-highlights.svg" alt="Highlights" width="100%"/>

| Metric | Result |
|---|---|
| Voice pipeline latency | Under 500 ms |
| Infrastructure cost | 30% lower after GPU batching and quantization |
| Retrieval scale | More than 1 million documents |
| Research | Presented at LIMMITS 2024 and 2025 |

---

<img src="./assets/h-models.svg" alt="What I Do With Models" width="100%"/>

| Area | What I work on | Tools |
|---|---|---|
| ![Language models](https://img.shields.io/badge/Language_models-1D4ED8?style=flat-square) | Fine-tuning with SFT, LoRA, QLoRA, PEFT and DPO. Evaluation. Tool calling and structured output. | PyTorch, Hugging Face Transformers |
| ![Inference and serving](https://img.shields.io/badge/Inference_and_serving-0E7490?style=flat-square) | KV cache, batching, quantization, speculative decoding. Lower latency and lower cost per request. | vLLM, Ollama, ONNX, TensorRT, DeepSpeed |
| ![Speech](https://img.shields.io/badge/Speech-4338CA?style=flat-square) | Speech recognition, text to speech, multilingual voice cloning. | Whisper, wav2vec 2.0, XTTS-v2, StyleTTS2, VITS |
| ![Retrieval](https://img.shields.io/badge/Retrieval-047857?style=flat-square) | Chunking, embeddings, hybrid search, reranking, graph retrieval. | BGE-M3, Weaviate, Qdrant, FAISS, Neo4j |
| ![Agents](https://img.shields.io/badge/Agents-1D4ED8?style=flat-square) | Tool-using workflows with memory, step limits and review. | LangGraph, LangChain, CrewAI, MCP |
| ![Model operations](https://img.shields.io/badge/Model_operations-334155?style=flat-square) | Experiment tracking, evaluation, CI/CD, monitoring. | MLflow, Docker, Kubernetes, FastAPI |

---

<img src="./assets/h-current.svg" alt="Current Work: Brahm Studio" width="100%"/>

Brahm Studio is an AI website builder for React. A chat assistant, a visual design canvas and tool-using agents work together on the same page. You can describe a page and let the model build it, or edit it by hand on the canvas, and both stay in sync. The implementation is confidential, so I can only share the overview.

**My part**

- End-to-end work across the interface, the agent layer and the backend.
- Designing how an agent receives context, chooses tools and recovers from errors.
- Streaming results live so the product feels fast.
- Safety by design: clear permissions, hard limits and one-click undo for AI changes.

---

<img src="./assets/h-experience.svg" alt="Experience" width="100%"/>

<img src="./assets/role-ai.svg" alt="AI / ML Engineer, Tapaya Technologies LLP, Remote, India, Jul 2024 to Present" width="100%"/>

- **Brahm Studio:** React website builder with a design canvas and tool-using agents.
- **Conversational voice AI:** Streaming pipeline with Whisper, Llama 3 and XTTS-v2 over WebSockets and Kubernetes. Reached sub-500 ms latency and cut infrastructure cost by 30% with GPU batching and quantization.
- **Enterprise retrieval:** Hybrid search with BGE-M3, Weaviate and Neo4j over more than one million documents.
- **Agent workflows:** LangGraph and CrewAI workflows with persistent context and multi-step tasks.
- **Speech research:** Shabdh, a multilingual zero-shot voice cloning project, presented at LIMMITS'24 and LIMMITS'25.

<img src="./assets/role-ml.svg" alt="Machine Learning Engineer Intern, Tapaya Technologies LLP, Oct 2023 to Jun 2024" width="100%"/>

- Fine-tuned speech recognition and synthesis models on multilingual audio with LoRA and PEFT.
- Used MLflow and CI/CD for evaluation and tracking.
- Reached an 18% word error rate on one ASR project.

<img src="./assets/role-ds.svg" alt="Data Scientist Intern, Simplilearn, India, Nov 2022 to Sep 2023" width="100%"/>

- Built and evaluated classification, regression and NLP models, and summarized results for decisions.

---

<img src="./assets/h-projects.svg" alt="Selected Projects" width="100%"/>

| Project | What it is | Stack |
|---|---|---|
| **Shabdh** | Multilingual zero-shot voice cloning | PyTorch, XTTS-v2, ASR, TTS |
| **EMOD** | Expressive speech synthesis | PyTorch, StyleTTS2 |
| **Enterprise RAG Platform** | Hybrid retrieval over a large document collection | LangChain, Weaviate, Neo4j |
| **Streaming Conversational Agent** | Real-time voice agent | FastAPI, LangGraph, WebSockets |

---

<img src="./assets/h-building.svg" alt="Currently Building" width="100%"/>

These are personal projects I am working on to go deeper into models. They are in progress.

- **VIJI-LLM:** My own conversational language model, built as a modular Python project: data preparation, tokenizer, model layers, training, evaluation, inference and fine-tuning.
- **Text-to-image model:** A latent diffusion transformer (DiT) sized for laptops and phones, trained on a MacBook.
- **Agent framework:** A small Python framework with an Agent, Task and Crew style API, running on local models.

---

<img src="./assets/h-how.svg" alt="How I Work" width="100%"/>

- I write the output contract first, then generate code.
- I test failure paths first: bad input, dropped streams, hostile paths.
- I keep secrets out of prompts and code, and ship an example env file.
- I build the thinnest working slice, then widen it.
- I always measure before and after a change, so I know the number.

---

<img src="./assets/h-skills.svg" alt="Technical Skills" width="100%"/>

| Category | Skills |
|---|---|
| ![LLMs and GenAI](https://img.shields.io/badge/LLMs_and_GenAI-1D4ED8?style=flat-square) | Transformers, prompt design, structured output, tool calling, LoRA, QLoRA, PEFT, vLLM, Ollama |
| ![Agents and MCP](https://img.shields.io/badge/Agents_and_MCP-1D4ED8?style=flat-square) | LangGraph, LangChain, LlamaIndex, CrewAI, AutoGen, MCP servers and clients, JSON-RPC 2.0, NDJSON, SSE |
| ![RAG and Search](https://img.shields.io/badge/RAG_and_Search-047857?style=flat-square) | Chunking, embeddings, hybrid search, reranking, FAISS, Qdrant, Weaviate, ChromaDB, Elasticsearch, Neo4j |
| ![Speech AI](https://img.shields.io/badge/Speech_AI-4338CA?style=flat-square) | ASR, TTS, Whisper, wav2vec 2.0, XTTS-v2, StyleTTS2, VITS, Bark, voice cloning |
| ![ML and DL](https://img.shields.io/badge/ML_and_DL-4338CA?style=flat-square) | Python, NumPy, pandas, scikit-learn, PyTorch, TensorFlow, Hugging Face, OpenCV, CLIP, YOLO |
| ![Model operations](https://img.shields.io/badge/Model_operations-0E7490?style=flat-square) | MLflow, ONNX, TensorRT, DeepSpeed, quantization, evaluation, experiment tracking |
| ![Backend and data](https://img.shields.io/badge/Backend_and_data-334155?style=flat-square) | FastAPI, REST, WebSockets, PostgreSQL, Redis, MongoDB, SQL, async processing |
| ![Cloud and infra](https://img.shields.io/badge/Cloud_and_infra-0E7490?style=flat-square) | Docker, Kubernetes, AWS, GCP, CI/CD, GPU workloads, monitoring |
| ![Application](https://img.shields.io/badge/Application-334155?style=flat-square) | TypeScript, React, Next.js |

---

<img src="./assets/h-education.svg" alt="Education" width="100%"/>

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

<img src="./assets/h-contact.svg" alt="Let's talk" width="100%"/>

<p>
<a href="mailto:vijay.aieng@gmail.com"><img src="https://img.shields.io/badge/Email-vijay.aieng@gmail.com-1D4ED8?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/vijay-aieng/"><img src="https://img.shields.io/badge/LinkedIn-vijay--aieng-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://vijayai.site"><img src="https://img.shields.io/badge/Portfolio-vijayai.site-0E7490?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://github.com/VijayAIeng"><img src="https://img.shields.io/badge/GitHub-VijayAIeng-334155?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

</div>
