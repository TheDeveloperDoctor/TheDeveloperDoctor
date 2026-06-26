<div align="center">

# Haris Ahmed

### AI & Full Stack Engineer

**Production LLM systems · Retrieval augmented generation · Agent orchestration · Monetized SaaS**

<a href="https://harisahmed.dev">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&repeat=true&width=720&height=42&lines=Production+LLM+Systems;Retrieval%2C+Agents%2C+and+SaaS;I+wrote+a+composable+agent+framework;From+research+to+real+products;Live+portfolio+at+harisahmed.dev" alt="Haris Ahmed, GenAI Engineer" />
</a>

<p>
  <a href="https://harisahmed.dev"><img src="https://img.shields.io/badge/🌐_harisahmed.dev-Live_Site-0D1117?style=for-the-badge&labelColor=58A6FF" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/haris-ahmed-genai/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:harisahmed510.00@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://pypi.org/project/weaveflow/"><img src="https://img.shields.io/badge/PyPI-weaveflow-3775A9?style=for-the-badge&logo=pypi&logoColor=white" alt="Weaveflow on PyPI" /></a>
</p>

*I am open to roles in AI and full stack engineering, and I am drawn to remote first teams, fast growing startups, and groups working at real scale.*

</div>

---

## 👋 About

I build and ship LLM systems that hold up in production. In practice that means retrieval pipelines with real recall and latency figures, orchestration across many agents, and SaaS platforms whose billing genuinely works, rather than polished demos.

My portfolio is not a description of my work. It is a live instance of it. The same retrieval, prompt injection defenses, and cost tracking patterns I build for production are running quietly at [harisahmed.dev](https://harisahmed.dev), and you are warmly welcome to look under the hood.

- 🛠️ Currently an Associate AI Engineer at [Vanar](https://vanarchain.com)
- 🧩 Author of [Weaveflow](https://pypi.org/project/weaveflow/), a composable agent framework on PyPI that carries no dependencies of its own
- 📍 Always glad to talk about GenAI and full stack work, with a soft spot for remote teams

---

## 🌐 The Portfolio Is the Proof

Please visit [harisahmed.dev](https://harisahmed.dev). The site is built from the very patterns I write for clients:

- **A chat assistant grounded in retrieval.** It streams its replies over SSE, remembers the conversation through TTL and LRU caches, and defends itself against prompt injection in two layers, a regex pass and an LLM classifier, both of which fail closed.
- **An admin command center.** It offers full CRUD, imports from GitHub with repo scans powered by an LLM, generates a résumé straight from YAML to PDF, and even submits job applications on its own.
- **A cost dashboard for every model call.** Each call records its tokens, its latency, and its cost in dollars to SQLite, all of which surface as live charts beside a feed of recent activity.
- **SEO written for generative engines.** The site is allowlisted for eighteen AI crawlers, among them GPTBot, ClaudeBot, PerplexityBot, and Google Extended.


---

## 🧪 Flagship Open Source

> One framework I wrote, with two substantial systems built on top of it.

### 🧩 [Weaveflow](https://pypi.org/project/weaveflow/), a Composable Agent Framework
Weaveflow is a Python framework that lets agents snap together the way USB devices do, regardless of which model, language, or host they happen to run on. Every agent exposes typed ports for its input and its output, and when two ports are close but not quite identical, the framework slips a transform in between so the handoff still succeeds. The core carries no dependencies of its own, thanks to duck typed bridges, so an existing LangChain, CrewAI, or plain Python agent wraps in a single line and never pulls those frameworks into your tree.



### 🌍 [Agent Simulation Society (ASS-Sim)](https://github.com/TheDeveloperDoctor/Agent-Simulation-Society), Emergent Behavior in Agent Societies
Think of this as a petri dish for societies of language models, built on Weaveflow. You can bring any number of autonomous citizen agents to life, each with its own goal and its own private memory, place them inside a shared game with rules, and step the whole population forward one tick at a time. Cooperation, deception, market efficiency, and quiet alliances then emerge as real numbers rather than anecdotes. Every run is reproducible from nothing more than a seed and a config file, the offline backend completes the full loop without a single API key, and three scenarios are ready to play from the start: a resource market, a multiparty negotiation, and a game of Werewolf.



### 🔬 [Adversarial Deep Research](https://github.com/TheDeveloperDoctor/Adversarial-Deep-Research), Research That Resists Hallucination
This is deep research that has to earn its conclusions, built on Weaveflow. It sends out web searchers and deep readers, then puts every fact on trial before a panel of skeptics whose sole task is to tear it down. A majority vote strikes any claim they cannot defend, well before it ever reaches the report. Trustworthiness here is structural rather than the product of a clever prompt. Every fact must carry a word for word source quote and a citation that survives review, the jurors are a deliberate blend of Claude, DeepSeek, Gemini, and GPT so that correlated mistakes cancel one another out, and any page fetched from the web is treated as untrusted, guarded against SSRF and sanitized for prompt injection.



---

## 💼 Selected Work at Vanar

| Project | What it does |
|---|---|
| **Hard Talk** | An AI simulation platform for the moments in corporate life where the stakes run highest. Adversarial personas interrupt and challenge your arguments as you make them and answer in under 300 milliseconds, which gives professionals a quiet place to rehearse investor pitches and media interviews before the real thing. |
| **Fitmeal Planner** | A meal planning experience that spans a full week, built in React and Next.js. People can revise their plans in plain language, and the system still honors every allergy and every calorie goal they have set. |
| **Inflectiv** | A public SaaS API gateway with custom rate limiting and documentation that generates itself through OpenAPI and Swagger. Behind it sit three access tiers, namely Free, Basic, and Pro, together with a Stripe billing system that meters usage on credits and tops balances up in real time. |
| **Unified Scraping Gateway** | Five scraping engines, namely Apify, Firecrawl, Crawlee, Playwright, and Scrapling, gathered behind a single REST API and protected by circuit breakers and retries with jitter. Each job is routed to the cheapest engine that can do the work, which brought scraping cost down by roughly 40 percent, and a ReAct extraction loop quietly discards any value it cannot trace back to its source. |
| **Generative Media Pipeline** | Automated video production that cut asset turnaround by close to 80 percent, built on Minimax and Remotion. |

---

## 🔧 Tech Stack

<div align="center">

**GenAI & LLM**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-2C7A7B?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)

**Infra & Payments**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

</div>

---

## 📁 More on GitHub

Beyond the flagship work above, my portfolio list gathers a few more projects I am fond of:

- **Mini RAG**, a small lab for comparing retrieval methods. It benchmarks naive cosine search, FAISS Flat, FAISS IVF, and a hybrid of BM25 and dense retrieval, and reports Recall at 5 and 10, MRR, and latency at the p50 and p95 marks.
- **SentinelLAN**, a network monitor with a little intelligence of its own. It watches a LAN for rogue devices, MAC spoofing, and exposed ports, then explains each threat in plain English over Telegram, and it deploys to a Raspberry Pi with a single Docker command.
- **CAP**, a gentle companion for client acquisition. It drafts outreach, cold messages, and follow ups, tracks every lead from draft to replied to won, and notices when a follow up has slipped past its date. It ships with more than 80 percent test coverage.

📂 **[Browse all portfolio projects →](https://github.com/stars/TheDeveloperDoctor/lists/portfolio-projects-100)**

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=TheDeveloperDoctor&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=3fb950&text_color=c9d1d9" alt="Haris Ahmed GitHub Stats" height="165" />
<img src="https://streak-stats.demolab.com?user=TheDeveloperDoctor&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=3fb950&currStreakLabel=58a6ff" alt="GitHub Streak" height="165" />

</div>

---

## 📫 Get in Touch

I am always happy to hear from people who are building thoughtful things. The surest way to reach me is by email, though LinkedIn works just as well, and you are welcome to wander through my portfolio whenever you like.

- 📧 harisahmed510.00@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/haris-ahmed-genai/)
- 🌐 [harisahmed.dev](https://harisahmed.dev)

<div align="center">

<sub>I care about software that keeps its footing once real people come to depend on it.</sub>

</div>
