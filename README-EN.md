# 🤖 Automation Portfolio

<div align="center">

![N8N](https://img.shields.io/badge/N8N-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Production automations · Integrated AI**

</div>

---

> ⚠️ **Note on confidentiality:** Workflow JSON files are not included for intellectual property reasons. Documentation covers architecture, logic, integrations, and results for each project.

---

## 📋 About

I build automation systems that replace manual work with intelligent, reliable processes. I focus on understanding the business problem and designing workflows that hold up in production — with error handling, state control, and logic that handles real volume.

---

## 🗂️ Projects

### 🏢 Sales

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [🤖 AI BDR Agent](https://github.com/guilhermesl44/n8n-agente-bdr-ia) | Analyzes leads' websites and Instagram to send hyper-personalized prospecting messages via WhatsApp | N8N · GPT-4o-mini · Evolution API · Google Sheets | ⭐⭐ |
| [🔍 Cold Lead Scraper](https://github.com/guilhermesl44/n8n-raspagem-leads) | Finds leads on Google/Maps via AI and automatically validates if WhatsApp exists before saving | N8N · GPT-4o-mini · SERPER API · Evolution API · Google Sheets | ⭐⭐ |
| [🧲 WhatsApp Lead Parser](https://github.com/guilhermesl44/n8n-whatsapp-lead-parser) | Converts WhatsApp conversations into structured HubSpot leads — Redis buffer, algorithmic regex validation, audio/image support, and human escalation | N8N · Evolution API · Redis · OpenAI · HubSpot | ⭐⭐⭐⭐⭐ |

### 🤝 Customer Success

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [🚨 Critical Client Follow-up](https://github.com/guilhermesl44/n8n-followup-criticos) | Detects clients with CRITICAL onboarding status weekly and sends AI-personalized support messages | N8N · GPT-4o-mini · Evolution API · Internal API | ⭐⭐ |

### 💰 Finance

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [⚠️ Overdue Collections](https://github.com/guilhermesl44/n8n-cobranca-atrasados) | Identifies delinquent clients and triggers a collection sequence with PDF invoice via email | N8N · Banco Inter API · Google Sheets · Gmail | ⭐⭐⭐⭐ |
| [💳 Invoice Generation](https://github.com/guilhermesl44/n8n-emissao-boletos) | Full recurring billing cycle: generation, delivery, callbacks, and real-time status updates | N8N · Banco Inter API · Redis · Google Sheets · Gmail | ⭐⭐⭐⭐⭐ |
| [🔄 Charge Sync](https://github.com/guilhermesl44/n8n-sincronizacao-cobrancas) | Syncs all bank charges daily to Sheets — base layer for financial dashboards | N8N · Banco Inter API · Google Sheets | ⭐⭐⭐⭐ |

### 🛒 E-commerce

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [💳 Checkout Gateway](https://github.com/guilhermesl44/n8n-checkout-asaas) | Full mini-gateway: checkout with PIX + credit card, progressive lead capture, and abandoned cart recovery | N8N · Asaas API · Google Sheets · Gmail · HTML/JS | ⭐⭐⭐⭐⭐ |

### 🔧 Infrastructure

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [🔥 WhatsApp Chip Warming](https://github.com/guilhermesl44/n8n-whatsapp-chip-warming) | Warms new WhatsApp chips by simulating organic conversations and doubles as a scenario simulator for attendant automation testing — full web interface served by n8n itself | N8N · Evolution API · Redis · HTML/JS | ⭐⭐⭐⭐⭐ |

### 🎥 Content Creation

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [🧠 YouTube Trends Research System](https://github.com/guilhermesl44/youtube-trends-research-system) | AI pipeline that analyzes YouTube trends and generates complete content ideas — title, script, and thumbnail | N8N · GPT-4o · YouTube · Google Sheets | ⭐⭐⭐⭐⭐ |

---

## 📊 Results & Metrics

| Project | Key Result |
|---------|-----------|
| 🤖 AI BDR Agent | 100% automated prospecting — AI-personalized message in ~30s per lead |
| 🔍 Cold Lead Scraper | Automatic WhatsApp validation before saving — zero invalid numbers in the queue |
| 🧲 WhatsApp Lead Parser | ~80% of leads registered in HubSpot without human intervention — regex handles structured data at zero AI cost |
| 🚨 Critical Client Follow-up | 100% of CRITICAL clients contacted every Monday at 09:30, without exception |
| ⚠️ Overdue Collections | 100% automatic delinquency follow-up — PDF invoice generated and sent by email |
| 💳 Invoice Generation | 100% automatic invoice generation and delivery — zero manual intervention in recurring operations |
| 🔄 Charge Sync | Sheet updated daily at 08:10 — 120-day history with no volume limit |
| 💳 Checkout Gateway | PIX + card in production — lead captured from the 1st field, automatic cart recovery |
| 🔥 Chip Warming | Web interface + autonomous loop running — chips warming with random cadence and sender alternation |
| 🧠 YouTube Trends System | Full pipeline: from raw YouTube data to title + script + thumbnail ready to publish |

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| **N8N** | Orchestration platform for all workflows |
| **OpenAI GPT-4o / 4o-mini** | AI agents for analysis, personalization and content generation |
| **Evolution API** | WhatsApp message sending and validation |
| **Banco Inter API** | Invoice generation, payment callbacks, PDF billing |
| **Asaas API** | Dynamic PIX, card charges, payment status lookup |
| **HubSpot CRM** | Contact and deal upsert via API |
| **Redis** | OAuth2 token caching and per-conversation message buffering |
| **Google Sheets** | Data hub, lead queues, and dashboard base layer |
| **SERPER API** | Smart searches on Google Search and Google Maps |
| **Gmail API** | HTML email delivery with attachments |
| **JavaScript** | Regex with algorithmic validation, random delays, data manipulation |

---

## 🏗️ Architecture Patterns Applied

- **Chain of AI Agents** — multiple agents in sequence, each output feeding the next
- **Stateful ETL** — Extract → Transform (AI) → Load, with automatic deduplication
- **OAuth2 with token caching** — Redis eliminates re-authentication latency in banking integrations
- **Webhook handling** — async callbacks update state in real time
- **Humanized automations** — random delays and unique messages simulating human behavior
- **Status-based automation** — conditional actions based on data state (CRITICAL, OVERDUE, etc.)
- **Progressive lead capture** — email-based upsert enriches the same row at each user event
- **Inactivity buffer pattern** — Redis accumulates messages per conversation; processing triggers only when the conversation goes cold
- **SPA embedded in webhook** — complete web interface served as a string in the Response Body, no separate front-end infrastructure

---

## 📬 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-silva-50376a1b6/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&to=guisilva28oliveira@gmail.com)

---

<div align="center">
<sub>All workflows are in production · 2026</sub>
</div>
