<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0f0c29,50:302b63,100:0f3460&height=230&section=header&text=MUHAMMAD%20TASHIF&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=42&desc=building%20systems%20that%20think&descAlignY=62&descSize=17&descColor=00d9ff" width="100%"/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=18&pause=1400&color=00D9FF&center=true&vCenter=true&width=680&height=40&lines=Generative+AI+Engineer+%7C+Backend+Architect;Agentic+RAG+%C2%B7+LangGraph+%C2%B7+Knowledge+Graphs;Shipping%3A+TalentIQ+%E2%80%94+AI+Recruiting+SaaS" />

<br/>

<img src="https://img.shields.io/badge/open_to_work-0f3460?style=flat-square&labelColor=0f0c29&color=00d9ff"/>
<img src="https://img.shields.io/badge/HEC_top_performer-0f3460?style=flat-square&labelColor=0f0c29&color=8a2be2"/>
<img src="https://img.shields.io/badge/Lahore,_Pakistan-0f3460?style=flat-square&labelColor=0f0c29&color=00d9ff"/>
<img src="https://komarev.com/ghpvc/?username=TashifToor&style=flat-square&color=8a2be2&labelColor=0f0c29&label=visitors"/>

</div>

<br>

> I don't just call an LLM API and call it a day. I build the retrieval, memory, and agent orchestration around it — the unglamorous plumbing that decides whether an AI system survives contact with production. That's what I spend most of my time doing, from `TalentIQ`'s screening pipeline down to how a vector store gets indexed.

<br>

## System stack

I think in layers — here's roughly how a project of mine is put together:

```
┌──────────────────────────────────────────────────────────┐
│  FRONTEND        Next.js · React · Tailwind CSS           │
├──────────────────────────────────────────────────────────┤
│  API LAYER       FastAPI · Django · Django REST Framework │
├──────────────────────────────────────────────────────────┤
│  ORCHESTRATION   LangGraph agents · LangChain              │
├──────────────────────────────────────────────────────────┤
│  RETRIEVAL       FAISS · ChromaDB · Neo4j AuraDB (Graph)   │
├──────────────────────────────────────────────────────────┤
│  LLM LAYER       Groq LLaMA 3.3 70B · OpenAI API · Gemini  │
├──────────────────────────────────────────────────────────┤
│  DATA            PostgreSQL · MySQL · MongoDB · Redis      │
├──────────────────────────────────────────────────────────┤
│  INFRA           Docker · GitHub Actions · Celery          │
└──────────────────────────────────────────────────────────┘
```

<div align="center">

<sub>**Orchestration & Retrieval**</sub><br>
<img src="https://img.shields.io/badge/LangChain-0f0c29?style=flat-square&logo=langchain&logoColor=00d9ff"/>
<img src="https://img.shields.io/badge/LangGraph-0f0c29?style=flat-square&logoColor=00d9ff"/>
<img src="https://img.shields.io/badge/FAISS-0f0c29?style=flat-square&logo=meta&logoColor=00d9ff"/>
<img src="https://img.shields.io/badge/ChromaDB-0f0c29?style=flat-square&logoColor=00d9ff"/>
<img src="https://img.shields.io/badge/Neo4j_AuraDB-0f0c29?style=flat-square&logo=neo4j&logoColor=00d9ff"/>
<img src="https://img.shields.io/badge/Groq-0f0c29?style=flat-square&logo=groq&logoColor=00d9ff"/>
<img src="https://img.shields.io/badge/OpenAI_API-0f0c29?style=flat-square&logo=openai&logoColor=00d9ff"/>

<br><br>

<sub>**Backend & Data**</sub><br>
<img src="https://skillicons.dev/icons?i=fastapi,django,postgres,mysql,mongodb,redis&theme=dark"/>

<br><br>

<sub>**Frontend & Infra**</sub><br>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,js,docker,git,githubactions&theme=dark"/>

</div>

<br>

---

## Featured builds

**01 · TalentIQ** &nbsp;·&nbsp; *in development, MVP-stage*
Agentic HR recruiting SaaS. HR teams drown in unstructured resumes — LangGraph orchestrates the async screening pipeline, FAISS handles semantic candidate matching, Groq powers a real-time RAG chat over each candidate's profile.
`LangGraph` `FastAPI` `Celery/Redis` `FAISS` `Groq` `Next.js`

**02 · BizLedger**
Multi-tenant fintech SaaS, live-tested on 1,000+ real transactions. Invoicing, expense tracking, and role-based access built for teams that can't afford a bug in the billing logic.
`Django` `DRF` `PostgreSQL` `JWT` `React/Vite`

**03 · MediCare AI**
Medical RAG chatbot with 94% retrieval accuracy and hard anti-hallucination guardrails — because "confidently wrong" is not an option in healthcare. Sub-2s response time end to end.
`LangChain` `ChromaDB` `Groq` `FastAPI`

**04 · HadeesGPT**
Domain-specific RAG search over the Ibn Majah corpus — 92% query accuracy on a dataset where precision matters more than recall.
`LangChain` `ChromaDB` `Groq` `FastAPI`

<details>
<summary><b>Show more projects</b></summary>
<br>

| Project | Stack | Highlight |
|:--|:--|:--|
| AI CV Chatbot | LangChain · RAG · ChromaDB · Groq | Resume-grounded career Q&A, live on portfolio |
| Transaction Anomaly Detector | Isolation Forest · Scikit-learn | Real-time fraud signal detection |
| FastAPI Auth System | FastAPI · JWT · PostgreSQL | Full auth lifecycle with token refresh |
| Image Optimization API | FastAPI · Celery · Redis · Pillow | Async queue-based image pipeline |
| School Management System | Django · MySQL · Bootstrap | Academic portal — grades, fees, timetable |
| Gym Management Portal | Django · PostgreSQL · DRF | Membership, billing, trainer scheduling |

</details>

<br>

---

## Currently in progress

<div align="center">

<img src="https://img.shields.io/badge/TalentIQ-68%25-00d9ff?style=flat-square&labelColor=0f0c29"/>
<img src="https://img.shields.io/badge/LangGraph_workflows-65%25-00d9ff?style=flat-square&labelColor=0f0c29"/>
<img src="https://img.shields.io/badge/GraphRAG_%2F_Neo4j-46%25-8a2be2?style=flat-square&labelColor=0f0c29"/>
<img src="https://img.shields.io/badge/Cloud_deployment-35%25-8a2be2?style=flat-square&labelColor=0f0c29"/>
<img src="https://img.shields.io/badge/Fine--tuning_%2F_RLHF-22%25-ff6b6b?style=flat-square&labelColor=0f0c29"/>

</div>

<br>

---

## Career

```
2024 ─┬─ Python Backend Developer (Team Lead)   @ CodeCelix — Remote
      ├─ Freelance AI & Web Developer            @ Tashif Software  (ongoing)
2025 ─┼─ Associate AI Developer (Team Lead)      @ WorldWise Solutions — Remote
2026 ─┴─ Backend Developer                       @ M1 Solutions — Remote   ← current
```

🎓 BS.IT — University of the Punjab, Lahore

> 🏆 **Generative AI Application Developer — Top Performer**
> HEC · NCEAC · PakAngels · UETIANS Lahore Endowment Foundation — May 2026
>
> 🎓 **Web Developer Certification**
> CodeCelix — Nov 2024

<br>

---

<div align="center">

## Get in touch

<a href="https://github.com/TashifToor"><img src="https://img.shields.io/badge/GitHub-0f0c29?style=flat-square&logo=github&logoColor=00d9ff"/></a>
<a href="https://linkedin.com/in/tashiftoor"><img src="https://img.shields.io/badge/LinkedIn-0f0c29?style=flat-square&logo=linkedin&logoColor=00d9ff"/></a>
<a href="mailto:tashiftoor12345@gmail.com"><img src="https://img.shields.io/badge/Gmail-0f0c29?style=flat-square&logo=gmail&logoColor=00d9ff"/></a>
<a href="https://tashifeng.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0f0c29?style=flat-square&logo=vercel&logoColor=00d9ff"/></a>

<br><br>

<sub>open to remote roles · freelance · collaboration · open source</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f0c29,50:302b63,100:0f3460&height=4&width=1000" width="100%"/>
