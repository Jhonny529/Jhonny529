<div align="center">
  <img alt="" width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=70&color=gradient&reversal=true" />
</div>

<h2 align="center">Jhonny Arturo Sanes Valdivia</h2>
<h4 align="center">Co-Founder & CTO at Arxatec · Backend Engineer · Software Architecture · Cloud & DevOps</h4>

<p align="center">
  I build scalable backend systems, APIs, and production-ready platforms with a strong focus on architecture, maintainability, and operational reliability.
</p>

<p align="center">
  <a href="https://jhonny-portfolio-seven.vercel.app/">
    <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/jhonny-sanes/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" />
  </a>
  <a href="https://github.com/Jhonny529">
    <img alt="GitHub" src="https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:jhonny-529@outlook.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge" />
  </a>
</p>

---

## About me

- Backend engineer focused on scalable APIs, maintainable systems, and production-ready services.
- Co-Founder & CTO at Arxatec, leading backend architecture, infrastructure decisions, and technical execution.
- Comfortable working across system design, cloud-connected workflows, reverse proxies, Docker-based environments, and service integrations.
- Interested in building software that is clear, scalable, secure, and operationally reliable.

---

## What I'm building

**Arxatec** — a legal-tech platform for Peru: a corpus of public legal documents plus an
AI assistant for lawyers. I own the backend, the data plane, and the infrastructure
underneath. Three services, talking to each other through explicit contracts:

| Service | What it does | Stack |
| --- | --- | --- |
| **Product API** | Cases, calendar, documents, chat, finances and billing. 16 modules, 400+ HTTP slices, ~6,800 unit tests, 7 CI gates. | Node · TypeScript · Express 5 · Prisma · PostgreSQL · Redis · BullMQ · Socket.IO |
| **RAG microservice** | Ingests documents from S3, chunks them, generates embeddings and indexes them in Qdrant to answer with traceable legal context. | Python · FastAPI · LangChain · Qdrant |
| **Legal data pipeline** | Scraper for Peru's public legal sources: 33 sources in 21 modules, resumable by ledger and checkpoint, with OCR fallback for scanned PDFs. | TypeScript · Puppeteer · Tesseract OCR |

Also: credit-based billing across two payment providers, per-model token accounting for
AI usage, and deployment on VPS with Docker, Nginx and pm2.

> Arxatec repositories are private. The [portfolio](https://jhonny-portfolio-seven.vercel.app/) has the long version.

---

## How I work

- **Documentation is never assumed current** — it gets checked against the code before
  anything is built on top of it, and what drifted gets fixed in the same change.
- **A dated session record**: every audit or decision lands in a folder for that day,
  declaring the commit it was verified against. Without the commit, a record is an opinion.
- **Mechanical verification before anything is called done** — lint, types, tests, build.
  Nothing closes on visual inspection.
- **A branch and a pull request per unit of work.** Never a direct push to main.

---

## Core stack

### Backend

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-222222?style=for-the-badge&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Data & Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-FF6B6B?style=for-the-badge&logo=qdrant&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### Cloud & Tools

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### Environment

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Arch Linux](https://img.shields.io/badge/Arch%20Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)
![Hyprland](https://img.shields.io/badge/Hyprland-58E1FF?style=for-the-badge&logo=hyprland&logoColor=black)

---

## Current focus

- Backend platforms and multi-service architectures
- Scalable APIs, service integration, and explicit contracts between them
- Data and ingestion pipelines with vector search
- Production-ready infrastructure and technical leadership

---

<div align="center">
  <sub>Open to meaningful backend, architecture, and infrastructure challenges.</sub>
</div>
