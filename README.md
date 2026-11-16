<div align="center">

<img src="./assets/banner.svg" alt="Vijayakumar S, AI/ML Engineer | Generative AI | Agents and MCP | Production Systems" width="100%"/>

<p>
<a href="mailto:vijay.aieng@gmail.com"><img src="./assets/btn-email.svg" alt="Email: vijay.aieng@gmail.com" width="170"/></a>&nbsp;
<a href="https://www.linkedin.com/in/vijay-aieng/"><img src="./assets/btn-linkedin.svg" alt="LinkedIn: vijay-aieng" width="170"/></a>&nbsp;
<a href="https://vijayai.site"><img src="./assets/btn-portfolio.svg" alt="Portfolio: vijayai.site" width="170"/></a>&nbsp;
<a href="https://github.com/VijayAIeng"><img src="./assets/btn-github.svg" alt="GitHub: VijayAIeng" width="170"/></a>
</p>


</div>

<br/>

<img src="./assets/section-about.svg" alt="About" width="100%"/>

<br/>

Hi, I'm Vijay. I'm an AI/ML Engineer who works on language models, speech, retrieval and agents.

Right now I'm building **Brahm Studio**, an AI website builder for React sites. You can design a page by hand on a canvas, or ask an AI model to do it, and both work on the same page. My work is mostly the agent side: how the model gets context, which tools it can use, and what happens when something fails.

I like the boring parts of AI engineering the most. Clean tool contracts, safe permissions, streaming that does not break, and an undo button when the model gets it wrong.

I use AI coding assistants every day. They write the first draft, and I read it, run it, and break it before I trust it. I do not merge code I cannot explain.

<br/>

<img src="./assets/section-highlights.svg" alt="Highlights" width="100%"/>

<br/>

<img src="./assets/highlights.svg" alt="Sub-500 ms voice pipeline latency, 30% infrastructure cost reduction, more than one million documents in a retrieval workflow, research presented at LIMMITS in 2024 and 2025" width="100%"/>

<br/>

<img src="./assets/section-current.svg" alt="Featured Work: Brahm Studio" width="100%"/>

<br/>

<img src="./assets/studio-hero.svg" alt="Brahm Studio, an AI website builder with a design canvas" width="100%"/>

<br/>

Brahm Studio mixes three things in one place: a chat assistant, a visual design canvas, and tool-using agents. You type what you want, and you get a React page you can keep editing by hand. The code is confidential, so I can only share the big picture.

<img src="./assets/studio-highlights.svg" alt="Brahm Studio highlights: chat to page, visual editing, design and code together, agent-powered edits, grounded and live, safe by design" width="100%"/>

**What I do on it**

- Work across the UI, the agent layer and the backend.
- Design how an agent gets context, picks tools and recovers from errors.
- Keep it fast by streaming results live.
- Keep it safe with clear permissions, hard limits and one-click undo for AI changes.

<br/>

<img src="./assets/section-agents.svg" alt="Agents and MCP" width="100%"/>

<br/>

An agent is a loop: read context, think, call a tool, look at the result, repeat. MCP is how I give the model tools in a standard way, so the host decides exactly what each tool can touch.

<img src="./assets/agent-loop.svg" alt="Agent loop: gather context, reason, call tools through MCP, observe results, act or answer" width="100%"/>

| What | How I do it |
|---|---|
| **Tools** | Small, single-purpose, with JSON Schema inputs. Errors come back as readable text so the model can fix itself. |
| **Context** | Summarize big state and cap the size so the prompt never overflows. |
| **Streaming** | Typed events for text, tool calls, results and errors. |
| **Guardrails** | Step limits, abort control, path sandboxing, auth and read-only modes. |
| **Review and undo** | Changes go through a review step and AI edits can be undone in one action. |

<br/>

<img src="./assets/section-workflow.svg" alt="How I Work with AI in 2026" width="100%"/>

<br/>

<img src="./assets/workflow-steps.svg" alt="Six-step AI-assisted engineering workflow: frame, generate, read, run, harden, document" width="100%"/>

**My daily rules**

- Write the output contract first, then generate code.
- Ask the assistant for trade-offs, not only code.
- Test the failure paths first: bad input, dropped streams, hostile paths.
- Keep secrets out of prompts and code. Use env variables and an example file.
- Build the thinnest working slice first, then widen it.

<br/>

<img src="./assets/section-production.svg" alt="Production Engineering" width="100%"/>

<br/>

<img src="./assets/production-cards.svg" alt="Production engineering checklist: latency, cost, evaluation, observability, security, reliability" width="100%"/>

A demo works once. My "done" means a request can be traced end to end, failures show a clear error, every tool has limits, and I know my eval number before and after each change.

<br/>

<img src="./assets/section-focus.svg" alt="Focus Areas" width="100%"/>

<br/>

<img src="./assets/focus.svg" alt="Focus areas: LLMs and GenAI, Speech and Audio AI, RAG and Retrieval, Agents and MCP, Deep Learning, Deployment and MLOps" width="100%"/>

<br/>

<img src="./assets/section-experience.svg" alt="Experience" width="100%"/>

<br/>

<img src="./assets/role-ai-engineer.svg" alt="AI / ML Engineer, Tapaya Technologies LLP, Remote, India, Jul 2024 to Present" width="100%"/>

- **Brahm Studio:** React website builder with a design canvas and tool-using agents.
- **Voice AI:** Streaming pipeline with Whisper, Llama 3 and XTTS-v2 over WebSockets and Kubernetes. Sub-500 ms latency and 30% lower infra cost after GPU batching and quantization.
- **Enterprise retrieval:** Hybrid search with BGE-M3, Weaviate and Neo4j over a collection of more than one million documents.
- **Agent workflows:** LangGraph and CrewAI workflows with persistent context and multi-step tasks.
- **Research:** Shabdh, a multilingual zero-shot voice cloning project, presented at LIMMITS'24 and LIMMITS'25.

<img src="./assets/role-ml-intern.svg" alt="Machine Learning Engineer Intern, Tapaya Technologies LLP, Oct 2023 to Jun 2024" width="100%"/>

- Fine-tuned speech recognition and synthesis models with LoRA/PEFT on multilingual audio.
- Used MLflow and CI/CD for evaluation and tracking. Reached 18% word error rate on one ASR project.

<img src="./assets/role-ds-intern.svg" alt="Data Scientist Intern, Simplilearn, India, Nov 2022 to Sep 2023" width="100%"/>

- Built and evaluated classification, regression and NLP models.

<br/>

<img src="./assets/section-projects.svg" alt="Selected Projects" width="100%"/>

<br/>

<table>
<tr>
<td width="50%" valign="top"><img src="./assets/project-shabdh.svg" alt="Shabdh: Multilingual Voice Cloning. Technology: PyTorch, XTTS-v2, ASR, TTS" width="100%"/></td>
<td width="50%" valign="top"><img src="./assets/project-emod.svg" alt="EMOD: Expressive Speech. Technology: PyTorch, StyleTTS2" width="100%"/></td>
</tr>
<tr>
<td width="50%" valign="top"><img src="./assets/project-rag.svg" alt="Enterprise RAG Platform. Technology: LangChain, Weaviate, Neo4j" width="100%"/></td>
<td width="50%" valign="top"><img src="./assets/project-voice-agent.svg" alt="Streaming Conversational Agent. Technology: FastAPI, LangGraph, WebSockets" width="100%"/></td>
</tr>
</table>

<br/>

<img src="./assets/section-skills.svg" alt="Technical Skills" width="100%"/>

<br/>

<p><img src="./assets/skills-llm.svg" alt="LLMs and GenAI: Transformers, LLM application development, prompt design, structured output, tool calling, LoRA, QLoRA, PEFT, vLLM, Ollama" width="100%"/></p>
<p><img src="./assets/skills-agents.svg" alt="Agents and MCP: LangGraph, LangChain, LlamaIndex, CrewAI, AutoGen, MCP servers and clients, JSON-RPC 2.0, tool schemas, agent loops, streaming protocols (NDJSON, SSE), multi-step workflows" width="100%"/></p>
<p><img src="./assets/skills-rag.svg" alt="RAG and Search: chunking, embeddings, hybrid search, reranking, FAISS, Qdrant, Weaviate, ChromaDB, Elasticsearch, Neo4j" width="100%"/></p>
<p><img src="./assets/skills-speech.svg" alt="Speech AI: ASR, TTS, Whisper, wav2vec 2.0, XTTS-v2, StyleTTS2, VITS, Bark, voice cloning" width="100%"/></p>
<p><img src="./assets/skills-app.svg" alt="Application Development: TypeScript, React, Next.js" width="100%"/></p>
<p><img src="./assets/skills-backend.svg" alt="Backend and Data: FastAPI, REST APIs, WebSockets, PostgreSQL, Redis, MongoDB, SQL, asynchronous processing" width="100%"/></p>
<p><img src="./assets/skills-cloud.svg" alt="Cloud and Infra: Docker, Kubernetes, AWS, GCP, CI/CD, GPU workloads, deployment, monitoring" width="100%"/></p>

<br/>

<img src="./assets/section-repositories.svg" alt="Repository Directory" width="100%"/>

<br/>


<details>
<summary><strong>More repositories (ML, vision, data, infra)</strong></summary>

<br/>


</details>

<br/>

<img src="./assets/section-education.svg" alt="Education and Certifications" width="100%"/>

<br/>

**B.E. in Computer Science and Engineering**, Sasurie Academy of Engineering, Coimbatore, 2016 to 2020

- DeepLearning.AI, LLM Specialization
- LangChain, Application Development
- Hugging Face, NLP Course
- fast.ai, Practical Deep Learning
- AWS Cloud Practitioner, in progress

<br/>

<img src="./assets/section-contact.svg" alt="Contact" width="100%"/>

<br/>

<div align="center">

<p>
<a href="mailto:vijay.aieng@gmail.com"><img src="./assets/btn-email.svg" alt="Email: vijay.aieng@gmail.com" width="190"/></a>&nbsp;
<a href="https://www.linkedin.com/in/vijay-aieng/"><img src="./assets/btn-linkedin.svg" alt="LinkedIn: vijay-aieng" width="190"/></a>&nbsp;
<a href="https://vijayai.site"><img src="./assets/btn-portfolio.svg" alt="Portfolio: vijayai.site" width="190"/></a>&nbsp;
<a href="https://github.com/VijayAIeng"><img src="./assets/btn-github.svg" alt="GitHub: VijayAIeng" width="190"/></a>
</p>

</div>

<br/>

<img src="./assets/footer.svg" alt="AI engineering, from model experiments to deployed applications." width="100%"/>
