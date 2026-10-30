<h1 align="center">Hi 👋, I'm Divya Goyal</h1>
<h3 align="center">AI/ML Engineer · Agentic AI, RAG & Production GenAI</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/divyagoyalds/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://divyagoyal6224-portfolio-website.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:divyagoyal6224@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://twitter.com/divyagoyalbg"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X / Twitter" /></a>
</p>

<p align="center"> <img src="https://komarev.com/ghpvc/?username=divyagoyal002&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" /> </p>

---

### 🧠 About me

- 🤖 AI/ML Engineer at **Onetab Generative AI**, building production agentic AI for a regulated fintech platform (US investment advisory firms)
- 🧩 I design **multi-agent systems**, **RAG pipelines** and **Python microservices** that connect LLMs to real business APIs
- 🎙️ I've shipped **real-time multilingual voice agents** (English / Hindi / Telugu) on the OpenAI Realtime API
- 📈 I care about AI that holds up in production: guardrails, evals, tracing and cost monitoring with **Langfuse**
- 🎓 Integrated M.Tech in AI & Data Science, DAVV Indore · GATE DA 2025 qualified
- 👩‍🏫 Mentored 8 AI/ML interns through to shipping production components

---

### ⭐ Featured project

### [Merchant Ops Copilot](https://github.com/Divyagoyal002/merchant-ops-copilot) · [Live demo](https://merchant-ops-copilot.onrender.com)

A Hindi/English ops agent for Razorpay merchants. Ask *"Why did yesterday's settlement come in low?"* or *"ऑर्डर 1058 का पूरा पैसा वापस कर दो"* and it answers from payments, orders, refunds and settlements through the **official Razorpay MCP server**.

- 🧭 **LangGraph agent** with a review → approval → execute path; refunds and payment links are drafted, but nothing moves until the merchant clicks **Approve** (`interrupt()` + checkpointer)
- 🔒 **Layered guardrails:** the model only gets 10 allowlisted read-only tools, proposals are validated in code, idempotency keys prevent double refunds, test keys only
- 📬 **Daily health digest** in Hindi or English: failure rate, top failure reasons, refund spikes
- 🧪 **Evals in CI:** 31 cases across English, Hindi and Hinglish, including prompt-injection attempts; the build fails on any unapproved execution
- 🆓 Runs on free tiers: open-weight models on Groq, Gradio on Render, Langfuse tracing, GitHub Actions

`LangGraph` `MCP` `Groq` `Gradio` `Langfuse` `GitHub Actions` `Render`

---

### 💼 Professional work

*Built at Onetab Generative AI for the company and its clients, so the code is private.*

**TACTIVE: agentic AI platform for US investment advisory firms**
A planning agent routes each query to 5 specialized retrieval agents (financials, CRM, documents, portfolio, compliance), with 22 REST APIs as agent tools and a unified Redis vector store.
`⚡ search latency ~500ms → <100ms` · `🧹 duplicated tool code ~1,500 → ~200 lines` · `🛡️ SEC/FINRA compliance agent with audit trails`

**Multilingual AI voice agent for Stock2Track (client project)**
Real-time English/Hindi/Telugu phone agent on the OpenAI Realtime API with function-calling tools, plus a post-call agent writing schema-constrained JSON into the client's CRM.
`📞 55% demo-booking conversion on qualified calls`

**Priya: bilingual AI sales agent**
Outbound voice agent with a deterministic control-tag protocol, so call actions (hangup, callback, demo booked) run in backend code, not model text.

**OneCode: AI web app generator**
Prompt-to-Next.js and screenshot-to-HTML/CSS on the Claude API, with an intent classifier for edits and a self-correcting build-fix loop.
`⏱️ ~30% faster development`

---

### 🏆 Hackathons

**Crewzy: AI workforce platform** · IIT Indore E-Summit Hackathon (Mappls-sponsored)
Natural-language-to-MongoDB query agent with an LLM authorization check, plus embedding- and distance-based task assignment.

**AI timetable generator** · Smart India Hackathon 2025
Constraint-based scheduling agent: 80% faster scheduling and 85% fewer conflicts than manual timetabling.

---

### 🛠️ Tech stack

**Agentic AI & LLMs**
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square" alt="CrewAI" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure OpenAI" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square" alt="Groq" />
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square" alt="Langfuse" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
</p>

**Backend & languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Gradio-F97316?style=flat-square&logo=gradio&logoColor=white" alt="Gradio" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" alt="Render" />
</p>

**Data, databases & vector search**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" alt="FAISS" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks" />
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Apache Spark" />
</p>

**Machine learning**
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
</p>

---

### 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=divyagoyal002&show_icons=true&locale=en" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=divyagoyal002&show_icons=true&locale=en&layout=compact" alt="Top languages" />
</p>

---

<p align="center"><i>Open to AI/ML engineering roles · Let's build agents that actually ship 🚀</i></p>
