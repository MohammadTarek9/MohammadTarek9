# Hi, I'm Mohammad Tarek 👋

**AI / Software Engineer** · Computer Engineering student (Ain Shams University × University of East London, dual degree, class of 2027) · Cairo, Egypt

I build production AI systems end to end: RAG and knowledge-graph pipelines, multi-provider LLM backends, agentic workflows, and the infrastructure that ships them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammad-tarek-302277315/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:medoabdeen73@gmail.com)

> [!NOTE]
> **Most of my work isn't visible here.** The bulk of my professional code lives in private repositories on company-managed GitHub and GitLab accounts, so this profile shows only a small part of what I build. Happy to discuss architectures and code samples.

---

## 💼 Work Experience

### Software Engineer · [BIAMI.io](https://biami.io) · *Aug 2026 – Oct 2026*

**ContentMorph** · [contentmorph.ai](https://contentmorph.ai/)\
Sole engineer on a SaaS that turns one source (note, blog URL, YouTube video, transcript, PDF…) into publish-ready content for 125+ channels in a single API call, through a web app and a public API. I designed, built and deployed all of it: backend, web app, marketing site, infrastructure and billing.
- Took the product from an empty repo to a **live, paid production service in 6 weeks**
- A distributed pipeline of **six independently scaling workers** (text, image, video, PDF, audio, cron), so a slow video render never delays cheap text or image jobs
- A **multi-provider AI layer over 5+ vendors** (OpenAI, Anthropic, Gemini, ElevenLabs, xAI, FLUX) with circuit breakers, fallback chains, per-channel model overrides and live cost metering
- Cut AI cost by running **one comprehension pass per request** and reusing it across every channel instead of one LLM call per channel
- **Usage-based billing on Stripe** with prepaid credits, card management, live payments and transaction history
- A **~3,300-test backend suite** plus frontend unit and end-to-end tests
- Security: same-origin `__Host-` session cookies, layered CSRF and origin checks, API-key auth and rate limiting at the APISIX gateway
- Ran DevOps end to end: Dockerized dev and production VPS environments, gated releases and database migrations

`Python` `FastAPI` `PostgreSQL` `Redis/arq` `React` `TypeScript` `TanStack Query` `Tailwind` `Docker Compose` `nginx` `APISIX` `Stripe` `Cloudflare R2` `ffmpeg` `WeasyPrint`

**10XFactory**\
A platform that coordinates AI coding agents (Claude Code, Codex) across multi-repository projects, from planning to deployment, with human approval gates.
- Developed agent workflows for planning, implementation, testing and delivery, with **isolated task workspaces** (git worktrees) and verification before merge
- **Strengthened verification** so tasks can't pass without running their checks; made type checking and linting blocking checks
- Recorded per-check output, exit codes and run times so reviewers can **audit agent activity**
- Contributed to **release verification** that only deploys verified, human-merged revisions
- Wrote and maintained shell test suites for task isolation, hotfixes and deployment workflows

`Bash` `Node.js` `Git worktrees` `Docker Compose` `GitHub` `Claude Code` `Codex`

### AI Engineer · Valeo · *Jul 2026 – Aug 2026*

An agentic AI chatbot that helps employees search, track and navigate work items and technical documents across the organization.
- Built **knowledge-graph RAG** that models relationships between work items (requirements, design documents, test cases) for relationship-aware querying
- Built an automated preprocessing pipeline that cleans and structures **millions of work items** into **JSON-LD** for graph ingestion
- Designed an end-to-end agentic pipeline using **Gemini CLI subagents, custom MCP tools and Skills** to build unified knowledge graphs from PDF, CSV, XLSX, TXT and DOCX, combined with a vector database for hybrid retrieval
- Integrated the local and centralized versions of the tool behind one API, with no extra configuration for users
- Built an **MCP tool** that exposes the whole chatbot inside Gemini CLI
- Contributed to an organization-wide **on-premises LLM platform**: evaluating open-source models, deployment strategies and hardware options

`Python` `Gemini CLI` `MCP` `Knowledge Graphs` `JSON-LD` `Neo4j` `Vector DBs`

### Software QA Engineer · Siemens EDA · *Jul 2025 – Dec 2025*

- Built a **gRPC/Protobuf backend** for an internal AI testing framework, migrated from REST
- Designed and ran **250+ LLM security test cases** to benchmark model safety and prevent sensitive-data leakage
- Automated the evaluation pipeline for **two fine-tuned LLMs** and integrated **Langfuse** for logging and visualizing results
- Built an **LLM mock server** for isolated, repeatable testing of AI components
- Resolved **Conan C++ dependency issues** for a formal verification tool and built a GitLab-integrated **Artifactory cleanup tool**

`Python` `gRPC` `Protobuf` `Langfuse` `C++` `Conan` `CMake` `GitLab` `JFrog Artifactory`

## 🔬 Research

**Egyptian Arabic Retrieval Benchmark** · *with NVIDIA*\
The first retrieval benchmark for Egyptian Arabic, evaluating how embedding and reranking models (including NVIDIA Nemotron) handle dialect queries compared with Modern Standard Arabic.


## 📂 Selected Public projects

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

💬 Open to AI / Software Engineering Roles. Reach me on [LinkedIn](https://www.linkedin.com/in/mohammad-tarek-302277315/) or by [email](mailto:medoabdeen73@gmail.com).
