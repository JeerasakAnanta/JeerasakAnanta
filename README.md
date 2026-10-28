<div align="center">

# Hi there, I'm **Jeerasak Ananta** 👋

### Software Engineer · HomeLab Enthusiast

Building production RAG chatbots, LLM automation and self-hosted infrastructure.

[![Download CV](https://img.shields.io/badge/Download_CV-PDF_·_2_pages-D14836?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/JeerasakAnanta/JeerasakAnanta/raw/main/docs/cv_jeerasak.pdf)
[![View CV](https://img.shields.io/badge/View_CV-Online-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/JeerasakAnanta/JeerasakAnanta/blob/main/docs/cv_jeerasak.pdf)

<sub>Updated Oct 2026 · English · A4 · [LaTeX source](docs/cv_jeerasak.tex)</sub>

[About](#-about-me) · [Experience](#-experience) · [Projects](#-featured-projects) · [Tech Stack](#%EF%B8%8F-tech-stack) · [Achievements](#-achievements) · [Contact](#-connect-with-me)

</div>

---

## 🧑‍💻 About Me

Backend AI Engineer with 3 years of hands-on experience building production RAG chatbots, LLM-powered automation and internal enterprise systems in banking, healthcare and HR. Strong in Python/FastAPI, LangChain/LangGraph, vector search (Qdrant) and GitLab CI/CD with Docker. Guest lecturer on RAG systems.

```python
class JeerasakAnanta:
    name       = "Jeerasak Ananta (Game 🎮)"
    role       = "Backend AI Engineer @ BAAC"
    education  = "B.Sc. Computer Science — RMUTL Nan (GPA: 3.97)"
    location   = "Bangkok, Thailand 🇹🇭"
    languages  = ["Thai (native)", "English (basic conversational)"]

    focus = [
        "🤖 Advanced RAG & LLM Applications",
        "⚙️ Workflow Automation AI",
        "🧩 MLOps & Self-hosted Systems",
        "☁️ Cloud Infrastructure Deployment",
    ]
```

---

## 💼 Experience

| Role                                | Company                                                           | Duration            |
| ----------------------------------- | ----------------------------------------------------------------- | ------------------- |
| Backend AI Engineer                 | Bank for Agriculture and Agricultural Co-operatives (BAAC), Head Office | May 2026 – Present  |
| Software Engineer (Automation)      | Freewill Solutions Co., Ltd.                                      | Oct 2025 – Apr 2026 |
| Developer (Research Assistant)      | RMUTL Nan                                                         | Oct 2024 – Sep 2025 |
| LLM Developer (Co-op Internship)    | BAAC Head Office                                                  | Jun 2024 – Sep 2024 |
| Teaching Assistant (Part-time)      | RMUTL Nan                                                         | Jun 2023 – Oct 2025 |

<details open>
<summary><b>Backend AI Engineer @ BAAC</b> — highlights</summary>

- Develop **BAAC Hermes**, an internal RAG chatbot (LangGraph, Qdrant, BGE-M3, Typhoon2, FastAPI) with **RBAC** and **LLM guardrails** so answers respect document access rights
- Build and maintain **OmniMail Gateway**, a centralized email service shared by multiple internal systems
- Build **HR Engine API** (FastAPI, MongoDB/Beanie) with Docling-based PDF extraction for HR documents
- Contribute to **HR Allocate**, a multi-step employee transfer and approval system (Next.js, Express, MongoDB) with audit logging and iAuthenX SSO, designed for PDPA compliance
- Integrate an AI-based OCR service and OAuth 2.0 into the **Employee Welfare Reimbursement System**
- Maintain **GitLab CI/CD** for several services: Docker builds, Harbor image vulnerability scanning, tag-triggered deployments on self-managed runners
- Harden Express services (CORS and security headers) and refactor core request-management components

</details>

<details>
<summary><b>Software Engineer (Automation) @ Freewill Solutions</b> — highlights</summary>

- Designed automated HR workflows with **n8n** and **Dify**, using LLMs to screen and rank candidates and cut manual screening time
- Wrote JavaScript nodes connecting external APIs, webhooks and business logic inside n8n
- Built CI/CD pipelines for continuous deployment of automation workflows

</details>

---

## 🚀 Featured Projects

| Project | What it does | Stack |
| ------- | ------------ | ----- |
| 🧠 **BAAC Hermes** | Internal RAG chatbot with RBAC and LLM guardrails so answers respect document access rights. | `LangGraph` `Qdrant` `BGE-M3` `Typhoon2` `FastAPI` |
| 🧑‍💼 **HR Allocate** | Multi-step employee transfer and approval system with audit logging and SSO, designed for PDPA compliance. | `Next.js` `Express` `MongoDB` |
| 🏦 **LannaFinChat** — AI Financial Assistant | RAG chatbot for the RMUTL Finance Dept. Answers reimbursement and policy questions via LINE with semantic search over policy documents. | `Python` `LangChain` `Qdrant` `Next.js` `LINE API` |
| 🏥 **NCD Public Health LINE Chatbot** | LINE bot for community health volunteers at Nan Hospital to record and update patient data, reducing rural paperwork. | `FastAPI` `LangChain` `PostgreSQL` `LINE Bot` |
| 📊 **Customer Analysis Platform** | Analytics platform for SMEs with natural-language querying of sales data and insights pushed through LINE OA. | `Next.js` `FastAPI` `LangChain` `OpenAI` `PostgreSQL` `LINE OA` |
| 🎟️ **OCR Lottery Verification** — [GitHub](https://github.com/JeerasakAnanta/redcross_lottery_nan) | Mobile web app that verifies Red Cross Nan lottery tickets via camera OCR, with manual-entry fallback and server-side cross-checking. | `FastAPI` `EasyOCR` `PostgreSQL` |
| 🤖 **BAAC LLM-RAG Chatbot** | RAG chatbot for the BAAC credit department answering financial-policy and loan questions, fine-tuned on financial domain data, delivered via LINE Messaging API. | `FastAPI` `LangChain` `OpenAI` `LINE API` |
| 🧑‍🏫 **Guest Lecturer — AI Inventor Program** (2024) | Full-day training on RAG systems, vector databases and practical LLM integration. | `RAG` `Vector DB` `LLM` |

---

## 🛠️ Tech Stack

| Area                 | Tools                                                                                          |
| -------------------- | ---------------------------------------------------------------------------------------------- |
| **Languages**        | Python · JavaScript · TypeScript · Java · Bash                                                 |
| **AI / LLM**         | OpenAI · LangChain · LangGraph · LlamaIndex · Qdrant · Hugging Face · Unsloth · Ollama · PyTorch · TensorFlow · RAG · LLM fine-tuning · guardrails |
| **Backend**          | FastAPI · Node.js / Express · REST APIs                                                        |
| **Frontend**         | Next.js · React · Tailwind CSS                                                                 |
| **Data**             | PostgreSQL · MySQL · MongoDB · Redis · MinIO · Airflow                                         |
| **DevOps & Infra**   | Docker · GitLab CI/CD · GitHub Actions · Jenkins · Harbor · NGINX · Terraform · k6 · Linux     |
| **Cloud & Self-hosted** | AWS · DigitalOcean · Vercel · Cloudflare · Proxmox · Grafana                                |
| **Automation**       | n8n · Dify                                                                                     |

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,ts,nextjs,react,tailwind,postgres,mongodb,redis,docker,linux,nginx,terraform,githubactions,gitlab,aws,git&perline=9" alt="Skill icons: Python, FastAPI, TypeScript, Next.js, React, Tailwind CSS, PostgreSQL, MongoDB, Redis, Docker, Linux, NGINX, Terraform, GitHub Actions, GitLab, AWS, Git" />
</div>

---

## 🏆 Achievements

- 🥇 **Winner** — C/C++ Programming Competition (Nan)
- 🥈 **Runner-Up** — C/C++ Programming Competition (Lampang)
- 💻 **Winner** — RMUTL Mini Hackathon (Chiang Mai)
- 🧠 **Participant** — 26th National Software Contest (NSC 2023, Chiang Mai)
- 🤖 **SuperAI Engineer Season 4** — AI Developer Track

---

## 📜 Certifications

| Badge | Certification                                 | Year |
| ----- | --------------------------------------------- | ---- |
| ☁️    | AWS re/Start Graduate                         | 2025 |
| 🧠    | Super AI Engineer — Season 4                  | 2024 |
| 🤖    | AI Beginner & AI Engineer (AIAT)              | 2024 |
| 🛡️    | SC-200: Microsoft Security Operations Analyst | 2024 |

---

## 📊 GitHub Stats

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=JeerasakAnanta&theme=tokyonight&hide_border=true)

</div>

---

## 📩 Connect with Me

<div align="center">

[![Email](https://img.shields.io/badge/Email-jeerasakananta@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jeerasakananta@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jeerasakananta-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeerasakananta/)
[![Portfolio](https://img.shields.io/badge/Portfolio-jeerasakananta.dev-00D9FF?style=for-the-badge&logo=vercel&logoColor=white)](https://www.jeerasakananta.dev)
[![Medium](https://img.shields.io/badge/Medium-@jeerasakananta-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@jeerasakananta_1762)

</div>

---

<div align="center">

💪 **STAY HARD. KEEP BUILDING.**

</div>
