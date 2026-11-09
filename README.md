## Hi, I'm Irfan 👋

**AI & Backend Engineer** · I build AI applications in **Python** and backend systems in **Java / Spring Boot** that are measured, tested, and deployed.

- 🤖 Building **LLM applications**: LangGraph agents, RAG, evaluation harnesses, and guardrails
- ☕ Designing **backend services** with Spring Boot: concurrency, security, transactions, events
- 🧪 I measure what I build: evals, tests, CI, and honest numbers
- 🎯 Open to **AI Engineer · SDE-1 · Backend Developer** roles · Bengaluru, Chennai, Hyderabad · open to relocation

### 🚀 Featured projects

#### [Cartograph](https://github.com/Irfan240305/Cartograph) · AI code-intelligence platform · [Live demo](https://cartographweb2026.z1.web.core.windows.net)
Ask questions about any GitHub repository and get answers grounded in its actual code, with cited source files.
- **LangGraph** multi-agent workflow: a tool-using agent for small questions, a planner → explorers → synthesizer pipeline for multi-file ones
- **Hybrid RAG**: pgvector semantic + PostgreSQL full-text search, merged with Reciprocal Rank Fusion
- **47-question evaluation harness:** answer fact coverage **74.7% → 82.9%**, guardrail pass rate **100%**, median latency **12.6 s → 7.4 s**
- Layered guardrails · 52 automated tests in **CI** · deployed on **Azure** · MCP server for Claude Desktop

#### [OmniReserve](https://github.com/Irfan240305/Omnireserve_Project) · Concurrent seat-reservation backend
A Spring Boot booking backend that stays correct when many users book the same seat at once.
- Prevents double-booking with **optimistic locking (`@Version`) + Spring Retry**, verified by a concurrency test
- **Spring Security + JWT** role-based authorization · async booking events · Factory/Strategy/Observer patterns
- **Gemini-powered** natural-language booking · Dockerized with MySQL

### 🛠 Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=py,fastapi,java,spring,postgres,mysql,docker,azure,githubactions,react,git,postman" />
</p>

| | |
|---|---|
| **AI & LLM** | LangGraph · LangChain · RAG · embeddings · LLM evaluation · guardrails |
| **Languages** | Python · Java · SQL · JavaScript |
| **Backend** | FastAPI · Spring Boot · Spring Security · Spring Data JPA · Hibernate · REST · JWT |
| **Data** | PostgreSQL · pgvector · MySQL · MongoDB |
| **DevOps** | Docker · GitHub Actions · Azure · Git · Maven |

### 🔗 Connect with me

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/irfan-ahmed-9539a3255)
[<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />](mailto:irfanubaidhu@gmail.com)
[<img src="https://img.shields.io/badge/Cartograph-Live_Demo-2EA44F?style=for-the-badge" />](https://cartographweb2026.z1.web.core.windows.net)
