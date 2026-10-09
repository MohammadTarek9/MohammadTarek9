# Hi, I'm Mohammad Tarek 👋

**AI Systems Engineer** · Computer Engineering student (Ain Shams University × University of East London, dual degree, class of 2027) · Cairo, Egypt

I build production AI systems end to end: RAG and knowledge-graph pipelines, multi-provider LLM backends, agentic workflows, and the infrastructure that ships them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammad-tarek-302277315/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:medoabdeen73@gmail.com)

> [!NOTE]
> **Most of my work isn't visible here.** The bulk of my professional code lives in private repositories on company-managed GitHub and GitLab accounts, so this profile shows only a small part of what I build. Happy to walk through architecture and code samples in an interview.

---

## 🔧 What I've built

**ContentMorph** · [contentmorph.ai](https://contentmorph.ai/) · *BIAMI.io*\
Sole engineer on a SaaS that turns one source (blog URL, YouTube video, PDF, transcript…) into publish-ready content for 125+ channels in a single API call. I took it from an empty repo to a live, paid production service in 6 weeks.
- A distributed pipeline of six independently scaling workers (text, image, video, PDF, audio, cron)
- A multi-provider AI layer over 5+ vendors with circuit breakers, fallback chains and live cost metering
- Usage-based Stripe billing, a ~3,300-test backend suite, and end-to-end DevOps

**10XFactory** · *BIAMI.io*\
An orchestration platform for AI coding agents (Claude Code, Codex) across multi-repo projects. It has isolated task workspaces, verification gates that block unchecked work, and audit trails for agent activity.

**Enterprise Agentic GraphRAG** · *Valeo*\
An agentic RAG chatbot over millions of engineering work items. It uses a JSON-LD knowledge-graph pipeline, Gemini CLI subagents with custom MCP tools to build graphs from heterogeneous documents, and hybrid vector + graph retrieval.

**LLM Evaluation & Security Testing** · *Siemens EDA*\
250+ LLM security test cases, automated evaluation of fine-tuned LLMs with Langfuse, a REST → gRPC migration, and an LLM mock server for repeatable testing.

## 🔬 Research

**Egyptian Arabic Retrieval Benchmark** · *with NVIDIA mentors*\
The first retrieval benchmark for Egyptian Arabic, evaluating how embedding and reranking models (including NVIDIA Nemotron) handle dialect queries compared with Modern Standard Arabic.

**Graduation project:** a Sovereign Multilingual RAG system for Egyptian Arabic dialects.

## 📂 Public projects

- **Research Paper Intelligence Engine:** multi-document RAG with hybrid retrieval (Pinecone + BM25 + RRF), LangChain ReAct agents and citation-aware answers
- **Distributed LLM Inference Engine:** LLM + RAG serving with Nginx load balancing, Qdrant retrieval and Dockerized services

## 🧰 Tech stack

**Languages:** Python · TypeScript · JavaScript · C++ · C · Java · Bash\
**AI / LLM:** RAG · Knowledge Graphs · Agents & MCP · LangChain · LoRA fine-tuning · Langfuse · PyTorch\
**Data:** PostgreSQL · Redis · Qdrant · Pinecone · FAISS · ChromaDB · MongoDB\
**Backend & Infra:** FastAPI · Node.js · gRPC · Docker · Nginx · APISIX · AWS · Cloudflare R2 · Linux\
**Frontend:** React · TanStack Query · Tailwind CSS\
**Tools:** Git · GitHub · GitLab · Artifactory · CMake · Conan · Jira · ClickUp · Claude Code · Codex · Gemini CLI

---

💬 Open to AI / ML systems engineering roles. Reach me on [LinkedIn](https://www.linkedin.com/in/mohammad-tarek-302277315/) or by [email](mailto:medoabdeen73@gmail.com).
