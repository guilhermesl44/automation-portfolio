# 🤖 Automation Portfolio

<div align="center">

![N8N](https://img.shields.io/badge/N8N-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Automations in production · AI integrated**

</div>

---

> ⚠️ **Confidentiality note:** Workflow JSON files are not included for intellectual property reasons. Documentation covers architecture, logic, integrations, and results for each project.

---

## 📋 About Me

I build automation systems that replace manual work with reliable, AI-powered processes. My focus is on understanding the business problem and designing workflows that hold up in production — with error handling, state control, rate limiting, and logic that handles real volume.

---

## 🗂️ Projects

### 🏢 Commercial

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [🤖 AI BDR Agent](https://github.com/guilhermesl44/n8n-agente-bdr-ia) | Analyzes each lead's website + Instagram and sends hyper-personalized prospecting messages via WhatsApp | N8N · GPT-4o-mini · Evolution API · Google Sheets | ⭐⭐ |
| [🔍 Cold Lead Scraping](https://github.com/guilhermesl44/n8n-raspagem-leads) | Searches Google/Maps via AI and automatically validates WhatsApp numbers before saving leads | N8N · GPT-4o-mini · SERPER API · Evolution API · Google Sheets | ⭐⭐ |

### 🤝 Customer Success

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [🚨 Critical Customer Follow-up](https://github.com/guilhermesl44/n8n-followup-criticos) | Detects CRITICAL-status clients weekly during onboarding and sends AI-personalized WhatsApp support messages | N8N · GPT-4o-mini · Evolution API · Internal API | ⭐⭐ |

### 💰 Financial

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [⚠️ Overdue Invoice Follow-up](https://github.com/guilhermesl44/n8n-cobranca-atrasados) | Identifies overdue invoices daily and sends personalized email reminders with updated PDF attached | N8N · Banco Inter API · Google Sheets · Gmail | ⭐⭐⭐⭐ |
| [💳 Automated Billing System](https://github.com/guilhermesl44/n8n-emissao-boletos) | Full recurring billing cycle: generation, email delivery, real-time webhook callbacks, and status updates | N8N · Banco Inter API · Redis · Google Sheets · Gmail | ⭐⭐⭐⭐⭐ |
| [🔄 Billing Synchronization](https://github.com/guilhermesl44/n8n-sincronizacao-cobrancas) | Daily full sync of all bank invoices into Sheets — data foundation for financial dashboards | N8N · Banco Inter API · Google Sheets | ⭐⭐⭐⭐ |

### 🎥 Content Creation

| Project | What it does | Stack | Complexity |
|---------|-------------|-------|:---:|
| [🧠 YouTube Trends Research System](https://github.com/guilhermesl44/youtube-trends-research-system) | AI pipeline that analyzes YouTube trends and generates complete content ideas — title, script and thumbnail | N8N · GPT-4o · YouTube · Google Sheets | ⭐⭐⭐⭐⭐ |

---

## 📊 Results & Metrics

| Project | Key result |
|---------|-----------|
| 🤖 AI BDR Agent | Fully automated prospecting — AI-personalized message per lead in ~30s |
| 🔍 Cold Lead Scraping | Automatic WhatsApp validation before adding to queue — zero invalid numbers |
| 🚨 Critical Customer Follow-up | 100% of CRITICAL clients contacted every Monday at 9:30 AM, without exception |
| ⚠️ Overdue Invoice Follow-up | 100% automated overdue follow-up — updated PDF generated and emailed automatically |
| 💳 Automated Billing System | Invoice generation and delivery 100% automated — zero manual intervention for recurring billing |
| 🔄 Billing Synchronization | Spreadsheet updated daily at 8:10 AM — 120-day history with no volume limit |
| 🧠 YouTube Trends System | Full pipeline: from raw YouTube data to ready-to-use title + script + thumbnail |

---

## 🛠️ Tech Stack

| Technology | Use |
|-----------|-----|
| **N8N** | Orchestration platform for all workflows |
| **OpenAI GPT-4o / 4o-mini** | AI agents for analysis, personalization, and content generation |
| **Evolution API** | WhatsApp message sending and number validation |
| **Banco Inter API** | Bank slip generation, payment callbacks, invoice PDFs |
| **Redis** | OAuth2 token caching to avoid re-authentication |
| **Google Sheets** | Data hub, lead queues, and dashboard foundation |
| **SERPER API** | Intelligent searches on Google Search and Google Maps |
| **Gmail API** | HTML email sending with attachments |
| **JavaScript** | Custom expressions, random delays, data manipulation |

---

## 🏗️ Architecture Patterns Applied

- **Chain of AI Agents** — multiple agents in sequence, each output feeding the next
- **ETL with state control** — Extract → Transform (AI) → Load, with automatic deduplication
- **OAuth2 with token caching** — Redis eliminates re-authentication latency in banking integrations
- **Webhook handling** — async callbacks update state in real time
- **Humanized automation** — random delays and unique messages that simulate human behavior
- **Status-based automation** — conditional actions based on data state (CRITICAL, OVERDUE, etc.)

---

## 📬 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-silva-50376a1b6/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&to=guisilva28oliveira@gmail.com)

---

<div align="center">
<sub>All workflows are running in production · 2026</sub>
</div>
