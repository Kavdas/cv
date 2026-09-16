# Nurdaulet Sadvakas — CV

**System Administrator · AI / Backend Developer** — Astana, Kazakhstan

> I keep infrastructure running — and build the AI assistants that run on top of it.

### 🔗 Live CV (bilingual EN / RU, switchable)

- **English:** https://kavdas.github.io/cv/?lang=en
- **Русский:** https://kavdas.github.io/cv/?lang=ru
- PDF: [English](Nurdaulet_Sadvakas_CV_EN.pdf) · [Русский](Nurdaulet_Sadvakas_CV_RU.pdf)

The page is a single self-contained `index.html` — no build step, no dependencies, works offline.

---

## What I do

System administrator with current, hands-on responsibility for Windows and Linux
infrastructure, Active Directory and Group Policy, network equipment, and the Bitrix24
CRM / internal business systems a sales team runs on — backed by a formal foundation in
cybersecurity and backend development. In parallel I ship production AI assistants:
Retrieval-Augmented Generation over PostgreSQL / pgvector, the Claude API, and Telegram
bots on aiogram.

**Two tracks, run together:**

| Systems & infrastructure | Applied AI & backend |
|---|---|
| Windows Server / Linux administration | RAG pipelines: chunking, embeddings, pgvector |
| Active Directory, Group Policy (GPO) | Claude API answer synthesis & prompting |
| Network equipment, TCP/IP, monitoring | Telegram bots on aiogram 3, FastAPI services |
| Backup & recovery verification | PostgreSQL, Alembic, Docker Compose delivery |
| Bitrix24 CRM & internal business systems | |

## Experience

- **Melody House LLP** — System Administrator · *Jul 2026 – present*
  Server infrastructure (Windows Server / Linux), Active Directory & GPO, network equipment
  and TCP/IP, backup & recovery, user support and technical documentation.
- **BIart (BI Education)** — Internal Systems & Automation · *2026 – ongoing*
  Bitrix24 CRM configuration (deal cards, pipeline stages, deal-flow rules); support of the
  internal sales-accounting system («Учётка»); designing and building the school's WordPress
  site; built and run the BIart Support Bot; documented the company's sales & operations
  processes end to end.
- **BI Education** — Full-stack Developer, Internship (AITANYM project) · *Mar – Aug 2026*
  Frontend & backend for an educational video platform; Python / Manim video pipeline; QA;
  outreach to partner schools. *Strong written reference available.*
- **Qazaq Cyber Sport Federation** — Frontend Developer, Internship · *2024 & 2025*
  Maintained and modernized the federation's WordPress site — theme templates, custom
  CSS / JS, PHP, responsiveness, redesign.

## Selected projects

### BIart Support Bot — internal employee-support assistant on Telegram
Answers staff questions about Bitrix24 and the internal accounting system from a knowledge
base, and hands off to a live operator when it can't. *(Private repository — internal tool.)*
`Python` · `aiogram 3` · `PostgreSQL / pgvector` · `Claude API` · `Alembic` · `Docker` · `pytest`
- RAG over a Markdown knowledge base: chunking, embeddings, pgvector similarity search
- Answer synthesis with the Claude API; graded modes (relay-only → quote → full AI answers)
- Role model (employee / operator / admin), operator case workflow, admin statistics
- Menu generated from knowledge-base front-matter; Docker Compose deployment

### AITANYM — educational video pipeline (BI Education)
`Python` · `Manim` · `REST APIs` · `SQL`
Python / Manim scripts rendering lesson videos for Kazakhstani schools; a streamlined
production workflow adopted across the team; QA of the delivery website.

### Softly — personal finance tracker *(technical showcase)*
`Go` · `PostgreSQL` · `PWA` · `Docker` · `IMAP`
Turns bank notifications and statements (Kaspi, Freedom, Halyk…) into categorized analytics.
Free-text notification parser (RU / KZ / translit / EN), statement import (CSV / XLSX / PDF)
with deduplication, a rules engine with 20+ categories, month-end forecasting, offline PWA.

### BIart — school website
**Live demo: [kavdas.github.io/biart-demo](https://kavdas.github.io/biart-demo/)**
`WordPress` · `PHP` · `JavaScript` · `Docker (wp-env)`
Custom WordPress block theme built from the school's brand book, in two languages (RU / KZ) —
native blocks only, self-hosted brand fonts, hand-built photo carousel, a custom oEmbed
integration (Yandex Maps), and a review wall sourced from the school's real listings (2GIS).
Security hardening (CSP, locked headers, XML-RPC disabled) and SEO (JSON-LD, Open Graph, hreflang).

### Sift — self-hosted log triage
**Code: [github.com/Kavdas/sift](https://github.com/Kavdas/sift)**
`Python` · `FastAPI` · `SQLAlchemy (async)` · `SQLite` · `Claude API` · `pytest` · `CI/CD`
A portfolio project built to show systems administration and applied AI as one artifact:
mines templates out of raw logs (online Drain algorithm), catches what's statistically
unusual with four independent detectors, correlates findings into incidents, and writes the
on-call brief — via 16 heuristic playbooks or an LLM, with log content always treated as
untrusted input. Desktop mode with a tray icon; 267 tests, ruff + mypy clean, CI on GitHub
Actions. Now also watches this portfolio's own production service, the BIart Support Bot.

### QCSF — official website
`WordPress` · `PHP` · `HTML` · `CSS` · `JavaScript`
Two internships (2024–2025) maintaining and modernizing the federation's WordPress site —
theme templates, custom CSS / JS, PHP, responsiveness, redesign.

## Skills

`Windows Server` `Active Directory` `Group Policy` `Linux` `TCP/IP` `Networking`
`Backup & recovery` `Monitoring & logging` · `Bitrix24` `CRM administration`
`Process documentation` · `Python` `FastAPI` `Flask` `REST API` `RAG` `pgvector`
`Claude API` `aiogram 3` `Go (basics)` · `PostgreSQL` `SQLite` `SQLAlchemy (async)` `Alembic` ·
`HTML` `CSS` `JavaScript` `WordPress` `PHP` `PWA` · `Docker` `Docker Compose` `Git`
`pytest` `CI/CD (GitHub Actions)` · `Network security` `Malware analysis` `Threat detection`
`Secure programming`

**Education:** B.Sc. Cybersecurity — Astana IT University (2022–2025)
**Languages:** English B2 · Russian native · Kazakh native

## Contact

- Email: nurdaulet.sadvakas@gmail.com
- GitHub: [github.com/Kavdas](https://github.com/Kavdas)
- LinkedIn: [linkedin.com/in/nurdaulet-sadvakas](https://www.linkedin.com/in/nurdaulet-sadvakas-21a6902b0/)

---

<sub>RU: интерактивное резюме с переключением EN/RU — https://kavdas.github.io/cv/ · PDF-версии в этом репозитории.</sub>
