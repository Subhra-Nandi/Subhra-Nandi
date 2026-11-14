<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0a2e,45:4b1d7a,100:b86fd6&height=210&section=header&text=Subhra%20Nandi&fontSize=62&fontColor=f5d6fa&fontAlignY=36&desc=AI%20%C3%97%20Systems%20Engineering%20%C2%B7%20Open%20Source%20%C2%B7%20Robotics&descSize=17&descAlignY=58&animation=fadeIn" width="100%" alt="Subhra Nandi"/>

<a href="https://github.com/Subhra-Nandi">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=900&color=D8A0F8&center=true&vCenter=true&width=640&lines=Building+AI+systems+that+are+safe+by+design;LLM+infra+%C2%B7+RAG+%C2%B7+Agentic+commerce;Open-source+contributor+%E2%80%94+hushh-research+%C2%B7+GSSoC+'26;Preparing+for+GSoC+2027" alt="Typing intro"/>
</a>

</div>

## About Me

I'm a third-year B.Tech student in **AI & Robotics** at the University of Engineering and Management, Kolkata (GPA 8.17, graduating 2028). I build software where AI meets systems engineering: LLM infrastructure, retrieval pipelines, agentic workflows and geospatial applications.

I care most about the engineering around the model. That means concurrency and correctness (atomic Redis operations, row-level locking, async pipelines), performance work backed by real measurements, and deterministic safeguards that keep probabilistic models away from decisions they shouldn't make on their own. Most of my experience comes from open source and hackathons, where I've learned to ship working systems under real constraints.

Away from the keyboard, you'll usually find me on a badminton court.

## Get in Touch

I'm open to internships, open-source collaboration and hackathon teams. Email is the fastest way to reach me.

<p>
  <a href="mailto:subhranandi20@gmail.com"><img src="https://img.shields.io/badge/Email-subhranandi20%40gmail.com-1a0a2e?style=for-the-badge&logo=gmail&logoColor=d8a0f8&labelColor=2d1060" alt="Email"/></a>
  <a href="https://linkedin.com/in/subhra-nandi"><img src="https://img.shields.io/badge/LinkedIn-subhra--nandi-1a0a2e?style=for-the-badge&logo=linkedin&logoColor=d8a0f8&labelColor=2d1060" alt="LinkedIn"/></a>
  <a href="https://subhra-nandi.github.io/my_portfolio/"><img src="https://img.shields.io/badge/Portfolio-subhra--nandi.github.io-1a0a2e?style=for-the-badge&logo=githubpages&logoColor=d8a0f8&labelColor=2d1060" alt="Portfolio"/></a>
</p>

## Progress Log

| Track | Where I am | Next milestone |
|:--|:--|:--|
| **Open Source** | Merged PRs in `hushh-labs/hushh-research`, peaking at **weekly rank #8 of ~5–6k contributors**; took part in **GSSoC '26** | **GSoC 2027** |
| **DSA** | **300+ LeetCode** problems in C++, currently in the DP phase | Finish DP, then move to Codeforces |
| **Codeforces** | Started as a beginner | **Expert (1600) by Jan 31, 2027**, Master long-term |
| **CodeChef** | Just getting started | **4★ by end of Jan 2027** |
| **Full-stack** | Next.js + FastAPI in production projects; MERN sprint underway | SDE / full-stack internship |
| **Hackathons** | Razorpay Buildathon · Hack2Skill · AWS Bharat Builds · Amazon ML Challenge · SIH 2026 (THERMIS) | Keep shipping |

<details>
<summary><b>Roadmap checklist</b></summary>
<br/>

- [x] First RAG project (Tesla 10-K chatbot)
- [x] Deployed a production-style LLM proxy (LLM-Shield)
- [x] Merged PRs into a large open-source codebase (hushh-research)
- [x] GirlScript Summer of Code '26
- [x] 300+ LeetCode problems
- [x] Portfolio site live
- [ ] Finish the LeetCode DP phase
- [ ] Codeforces Expert (1600)
- [ ] CodeChef 4★
- [ ] Finish the MERN sprint
- [ ] GSoC 2027

</details>

## Featured Work

<table>
<tr>
<td width="50%" valign="top">

### [APEX-Commerce](https://github.com/Subhra-Nandi/apex-commerce)
<sub>Razorpay Buildathon · Agentic Commerce</sub>

Middleware between autonomous AI buyer agents and merchants: machine-readable catalogs, margin-aware negotiation, and a **deterministic policy enclave**. *The AI proposes the price; non-LLM code decides whether it can be charged.*

`Next.js 15` `FastAPI` `Claude` `Gemini` `Neon Postgres`

</td>
<td width="50%" valign="top">

### [PIVOT](https://github.com/Subhra-Nandi/PIVOT)
<sub>Hack2Skill · Industrial Commerce · Team DevCore</sub>

Turns messy supplier PDFs and listings into commerce-ready product data. Every field is **cited, grounded and conflict-checked**, with a 4-provider LLM fallback chain and **228 passing tests**.

`FastAPI` `React + Vite` `OpenRouter` `Railway` · [**Live demo**](https://pivot-seven-eta.vercel.app/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [LLM-Shield](https://github.com/Subhra-Nandi/llm-shield)
<sub>LLM infrastructure</sub>

A drop-in, OpenAI-compatible proxy with a semantic cache, PII redaction, two-stage prompt-injection detection (regex in under 1 ms, then DeBERTa-v3), token-bucket rate limiting, failover and Prometheus metrics.

`FastAPI` `Redis` `Presidio` `Postgres` `Docker` · [**Live demo**](https://llm-shield-five.vercel.app)

</td>
<td width="50%" valign="top">

### [NGO Resource Allocation](https://github.com/Subhra-Nandi/ngo-resource-allocation-system)
<sub>Disaster response · Geospatial AI</sub>

Connects people in crisis to the nearest NGO with stock available. Takes text, voice or photo requests through AI validation gates, uses **PostGIS** for nearest-depot search, and **row-level locking** to prevent double dispatch.

`FastAPI` `Next.js 14` `PostGIS` `GPT-4o`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AIRA](https://github.com/Subhra-Nandi/aira-platform)
<sub>Multi-agent research platform</sub>

Research, Analysis and Coding agents work from a single prompt. They search the live web and return startup ideas, market insights or working code tailored to a founder profile.

`FastAPI` `Pydantic` `LLM agents` `n8n`

</td>
<td width="50%" valign="top">

### [Vaani](https://github.com/Subhra-Nandi/vaani)
<sub>Voice AI</sub>

A Hindi voice assistant for re-engaging students. Whisper STT → state-machine dialogue → LLM objection handling → Coqui TTS, with Redis session memory.

`Whisper` `Coqui TTS` `Ollama` `Redis` `FastAPI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Light-Seeking Car](https://github.com/Subhra-Nandi/light-seeking-car)
<sub>Robotics</sub>

Colour and light detection on a **Jetson** sends commands over serial to an **Arduino** that drives the car.

`Python` `Jetson` `Arduino` `C++`

</td>
<td width="50%" valign="top">

### [Tesla 10-K RAG](https://github.com/Subhra-Nandi/tesla-rag)
<sub>Where it all started</sub>

My first project: a RAG chatbot over Tesla's 10-K report, using embeddings search, retrieved context and Gemini answers.

`LangChain` `Pinecone` `Gemini` `HuggingFace`

</td>
</tr>
</table>

## Tech Stack

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=py,cpp,java,ts,js,c&theme=dark" alt="Languages"/>

**Backend · Frontend · Data**<br/>
<img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,react,nextjs,tailwind,postgres,mongodb,redis&theme=dark" alt="Backend and frontend"/>

**ML · Robotics · DevOps**<br/>
<img src="https://skillicons.dev/icons?i=pytorch,sklearn,arduino,docker,githubactions,vercel,linux,git,postman&theme=dark" alt="ML and DevOps"/>

**AI tooling**<br/>
<img src="https://img.shields.io/badge/LangChain-1a0a2e?style=flat-square&logo=langchain&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/Hugging_Face-1a0a2e?style=flat-square&logo=huggingface&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/OpenAI-1a0a2e?style=flat-square&logo=openai&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/Claude-1a0a2e?style=flat-square&logo=anthropic&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/Gemini-1a0a2e?style=flat-square&logo=googlegemini&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/Pinecone-1a0a2e?style=flat-square&logo=pinecone&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/ChromaDB-1a0a2e?style=flat-square&logo=databricks&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/PostGIS-1a0a2e?style=flat-square&logo=postgresql&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/CatBoost-1a0a2e?style=flat-square&logo=python&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/n8n-1a0a2e?style=flat-square&logo=n8n&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/Railway-1a0a2e?style=flat-square&logo=railway&logoColor=d8a0f8"/>
<img src="https://img.shields.io/badge/Neon-1a0a2e?style=flat-square&logo=neon&logoColor=d8a0f8"/>

</div>

## GitHub Stats

<div align="center">

<!-- Generated every 12 hours by .github/workflows/profile-cards.yml -->
<img width="100%" src="./profile-summary-card-output/dracula/0-profile-details.svg" alt="Contribution activity"/>

<img width="49%" src="./profile-summary-card-output/dracula/3-stats.svg" alt="GitHub stats"/>
<img width="49%" src="./profile-summary-card-output/dracula/2-most-commit-language.svg" alt="Top languages by commit"/>

<img width="49%" src="./profile-summary-card-output/dracula/1-repos-per-language.svg" alt="Repos per language"/>
<img width="49%" src="./profile-summary-card-output/dracula/4-productive-time.svg" alt="Productive time"/>

<img src="https://streak-stats.demolab.com/?user=Subhra-Nandi&hide_border=true&background=1a0a2e&ring=9b55c4&fire=d8a0f8&currStreakLabel=d8a0f8&sideLabels=c898e8&currStreakNum=f5d6fa&sideNums=f5d6fa&dates=8a6aa8&stroke=4b1d7a" alt="Streak"/>

</div>

<div align="center">

<sub><i>Build systems that think, scale, and solve.</i></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:b86fd6,55:4b1d7a,100:1a0a2e&height=110&section=footer" width="100%"/>

</div>
