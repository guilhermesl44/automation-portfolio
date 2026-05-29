# 🤖 Automation Portfolio

<div align="center">

![N8N](https://img.shields.io/badge/N8N-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**6 automações em produção · 3 áreas de negócio · IA integrada**

</div>

---

> ⚠️ **Nota sobre confidencialidade:** Os arquivos JSON dos workflows não estão incluídos por questões de propriedade intelectual. A documentação cobre arquitetura, lógica, integrações e resultados de cada projeto.

---

## 📋 Sobre Mim

Especialista em automação de processos com N8N, focado em transformar tarefas manuais e repetitivas em sistemas inteligentes que escalam. Trabalho com IA generativa, integração de APIs e lógica condicional avançada para resolver problemas reais de negócio nas áreas Comercial, Customer Success e Financeiro.

**Habilidades principais:**
- Workflows complexos com múltiplos agentes de IA em cadeia
- Integração de APIs REST e WebHooks
- Automação de prospecção e follow-up via WhatsApp
- Processamento e validação de dados em escala
- Humanização de automações (delays adaptativos, personalização via IA)

---

## 🗂️ Projetos

### 🏢 Comercial

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [🤖 Agente BDR com IA](https://github.com/guilhermesl44/n8n-agente-bdr-ia) | Analisa site + Instagram de leads e envia mensagens de prospecção hiper-personalizadas via WhatsApp | N8N · GPT-4o-mini · Evolution API · Google Sheets | ⭐⭐ |
| [🔍 Raspagem de Leads Frios](https://github.com/guilhermesl44/n8n-raspagem-leads) | Busca leads no Google/Maps via IA e valida automaticamente se o WhatsApp existe antes de salvar | N8N · GPT-4o-mini · SERPER API · Evolution API · Google Sheets | ⭐⭐ |

### 🤝 Customer Success

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [🚨 Follow-up de Clientes Críticos](https://github.com/guilhermesl44/n8n-followup-criticos) | Detecta semanalmente clientes com status CRÍTICO na implantação e envia mensagens de suporte personalizadas por IA | N8N · GPT-4o-mini · Evolution API · API Interna | ⭐⭐ |

### 💰 Financeiro

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [💳 Cobrança de Atrasados](https://github.com/guilhermesl44/n8n-cobranca-atrasados) | Identifica clientes inadimplentes e dispara régua de cobrança automatizada via WhatsApp | N8N · Evolution API · API Interna | ⭐⭐ |
| [🧾 Emissão de Boletos](https://github.com/guilhermesl44/n8n-emissao-boletos) | Automatiza a geração e envio de boletos bancários integrado ao sistema de gestão | N8N · API Interna · Evolution API | ⭐⭐ |
| [🔄 Sincronização de Cobranças](https://github.com/guilhermesl44/n8n-sincronizacao-cobrancas) | Sincroniza dados de cobrança entre sistemas, eliminando atualizações manuais | N8N · API Interna · Google Sheets | ⭐⭐ |

### 🎥 Criação de Conteúdo

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [🧠 YouTube Trends Research System](https://github.com/guilhermesl44/youtube-trends-research-system) | Pipeline IA que analisa tendências do YouTube e gera ideias completas de conteúdo — título, roteiro e thumbnail | N8N · GPT-4o · YouTube · Google Sheets | ⭐⭐⭐⭐⭐ |

---

## 📊 Resultados & Métricas

### 🤖 Agente BDR com IA
- **Problema resolvido:** Prospecção manual = horas por lead + mensagens genéricas com baixa resposta
- **Resultado:** Mensagens personalizadas geradas em ~30s por lead; processo 100% automatizado
- **Escala:** Processa dezenas de leads por execução, sem intervenção manual
- **Diferencial:** Dois agentes de IA em cadeia (análise → criação) com delays humanizados de 10–15 min

### 🔍 Raspagem de Leads Frios
- **Problema resolvido:** Leads com WhatsApp inativo desperdiçavam tempo do time comercial
- **Resultado:** Validação automática elimina números inválidos antes de qualquer abordagem
- **Cobertura:** Busca simultânea em 2 fontes (web + Google Maps) por termo de pesquisa
- **Output:** Lista pronta e validada no Google Sheets, sem retrabalho

### 🚨 Follow-up de Clientes Críticos
- **Problema resolvido:** Equipe de CS não conseguia acompanhar todos os clientes em dificuldade
- **Resultado:** 100% dos clientes CRÍTICO recebem contato toda segunda-feira às 09:30, sem exceções
- **Personalização:** Cada mensagem gerada por IA com nome e contexto do cliente
- **Operação:** Notificação automática para a gestora ao concluir cada rodada

---

## 🛠️ Stack Técnica

| Tecnologia | Uso |
|-----------|-----|
| **N8N** | Plataforma de orquestração de todos os workflows |
| **OpenAI GPT-4o-mini** | Agentes de IA para análise, personalização e geração de mensagens |
| **Evolution API** | Envio e validação de mensagens via WhatsApp |
| **Google Sheets** | Gestão de filas de leads e armazenamento de resultados |
| **SERPER API** | Buscas inteligentes no Google Search e Google Maps |
| **APIs REST** | Integração com sistemas internos de gestão |
| **JavaScript** | Expressões customizadas, delays aleatórios, manipulação de dados |

---

## 🏗️ Padrões de Arquitetura Aplicados

- **Chain of AI Agents** — múltiplos agentes em sequência, onde o output de um alimenta o próximo
- **ETL com controle de estado** — Extract → Transform (IA) → Load, com deduplicação automática
- **Humanização de automações** — delays aleatórios e mensagens únicas que simulam comportamento humano
- **Processamento em lote com retry** — loops controlados com tratamento de erro sem parar o workflow
- **Status-based automation** — ações condicionais baseadas no estado do dado (CRÍTICO, HABILITADO, etc.)

---

## 📬 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-silva-50376a1b6/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&to=guisilva28oliveira@gmail.com)

---

<div align="center">
<sub>Todos os workflows estão em produção · 2025</sub>
</div>

