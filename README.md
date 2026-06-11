# 🤖 Automation Portfolio

<div align="center">

![N8N](https://img.shields.io/badge/N8N-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Automações em produção · IA integrada**

</div>

---

> ⚠️ **Nota sobre confidencialidade:** Os arquivos JSON dos workflows não estão incluídos por questões de propriedade intelectual. A documentação cobre arquitetura, lógica, integrações e resultados de cada projeto.

---

## 📋 Sobre Mim

Construo sistemas de automação que substituem trabalho manual por processos inteligentes e confiáveis. Foco em entender o problema de negócio e projetar workflows que funcionam em produção — com tratamento de erro, controle de estado e lógica que aguenta volume real.

---

## 🗂️ Projetos

### 🏢 Comercial

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [🤖 Agente BDR com IA](https://github.com/guilhermesl44/n8n-agente-bdr-ia) | Analisa site + Instagram de leads e envia mensagens de prospecção hiper-personalizadas via WhatsApp | N8N · GPT-4o-mini · Evolution API · Google Sheets | ⭐⭐ |
| [🔍 Raspagem de Leads Frios](https://github.com/guilhermesl44/n8n-raspagem-leads) | Busca leads no Google/Maps via IA e valida automaticamente se o WhatsApp existe antes de salvar | N8N · GPT-4o-mini · SERPER API · Evolution API · Google Sheets | ⭐⭐ |
| [📲 WhatsApp Lead Parser](https://github.com/guilhermesl44/n8n-whatsapp-lead-parser) | Converte conversas de WhatsApp em leads estruturados no HubSpot — buffer Redis, regex com validação algorítmica, suporte a áudio/imagem e escalada para humano | N8N · Evolution API · Redis · OpenAI · HubSpot | ⭐⭐⭐ |

### 🤝 Customer Success

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [🚨 Follow-up de Clientes Críticos](https://github.com/guilhermesl44/n8n-followup-criticos) | Detecta semanalmente clientes com status CRÍTICO na implantação e envia mensagens de suporte personalizadas por IA | N8N · GPT-4o-mini · Evolution API · API Interna | ⭐ ⭐|

### 💰 Financeiro

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [⚠️ Cobrança de Atrasados](https://github.com/guilhermesl44/n8n-cobranca-atrasados) | Identifica clientes inadimplentes e dispara régua de cobrança com 2ª via em PDF via email | N8N · Banco Inter API · Google Sheets · Gmail | ⭐⭐⭐⭐ |
| [💳 Emissão de Boletos](https://github.com/guilhermesl44/n8n-emissao-boletos) | Ciclo completo de cobrança recorrente: geração, envio, callbacks e atualização de status em tempo real | N8N · Banco Inter API · Redis · Google Sheets · Gmail | ⭐⭐⭐⭐⭐ |
| [🔄 Sincronização de Cobranças](https://github.com/guilhermesl44/n8n-sincronizacao-cobrancas) | Sincroniza todas as cobranças do banco diariamente no Sheets — base para dashboards financeiros | N8N · Banco Inter API · Google Sheets | ⭐⭐⭐⭐ |

### 🛒 E-commerce

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [💳 Checkout Gateway](https://github.com/guilhermesl44/n8n-checkout-asaas) | Mini gateway completo: checkout com PIX + cartão, captura progressiva de leads e recuperação de carrinho abandonado | N8N · Asaas API · Google Sheets · Gmail · HTML/JS | ⭐⭐⭐⭐⭐ |

### 🔧 Infraestrutura

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [🔥 WhatsApp Chip Warming](https://github.com/guilhermesl44/n8n-whatsapp-chip-warming) | Aquece chips WhatsApp novos simulando conversas orgânicas e serve como simulador de cenários para testes de automações de atendimento — interface web completa servida pelo próprio n8n | N8N · Evolution API · Redis · HTML/JS | ⭐⭐⭐⭐⭐ |

### 🎥 Criação de Conteúdo

| Projeto | O que faz | Stack | Complexidade |
|---------|-----------|-------|:---:|
| [🧠 YouTube Trends Research System](https://github.com/guilhermesl44/youtube-trends-research-system) | Pipeline IA que analisa tendências do YouTube e gera ideias completas de conteúdo — título, roteiro e thumbnail | N8N · GPT-4o · YouTube · Google Sheets | ⭐⭐⭐⭐⭐ |

---

## 📊 Resultados & Métricas

| Projeto | Resultado-chave |
|---------|----------------|
| 🤖 Agente BDR com IA | Prospecção 100% automatizada — mensagem personalizada por IA em ~30s por lead |
| 🔍 Raspagem de Leads Frios | Validação automática de WhatsApp antes do cadastro — zero números inválidos na fila |
| 📲 WhatsApp Lead Parser | ~80% dos leads cadastrados no HubSpot sem intervenção humana — regex resolve dados estruturados sem custo de IA |
| 🚨 Follow-up de Clientes Críticos | 100% dos clientes CRÍTICO contatados toda segunda-feira às 09:30, sem exceção |
| ⚠️ Cobrança de Atrasados | Follow-up de inadimplência 100% automático — 2ª via em PDF gerada e enviada por email |
| 💳 Emissão de Boletos | Geração e envio de boletos 100% automático — zero intervenção manual na operação recorrente |
| 🔄 Sincronização de Cobranças | Planilha atualizada diariamente às 08:10 — 120 dias de histórico sem limite de volume |
| 💳 Checkout Gateway | PIX + cartão em produção — captura de lead desde o 1º campo, recuperação automática de carrinho |
| 🔥 Chip Warming | Interface web + loop autônomo no ar — chips aquecendo com cadência aleatória e alternância de remetente |
| 🧠 YouTube Trends System | Pipeline completo: de dados brutos do YouTube a título + roteiro + thumbnail prontos |

---

## 🛠️ Stack Técnica

| Tecnologia | Uso |
|-----------|-----|
| **N8N** | Plataforma de orquestração de todos os workflows |
| **OpenAI  / Anthropic** | Agentes de IA para análise, personalização e geração de conteúdo |
| **Evolution API** | Envio e validação de mensagens via WhatsApp |
| **Banco Inter API** | Geração de boletos, callbacks de pagamento, PDF de cobranças |
| **Asaas API** | PIX dinâmico, cobrança de cartão, consulta de status de pagamento |
| **HubSpot CRM** | Upsert de contatos e deals via API |
| **Redis** | Cache de tokens OAuth2 e buffer de mensagens por conversa |
| **Google Sheets** | Hub de dados, filas de leads e base para dashboards |
| **SERPER API** | Buscas inteligentes no Google Search e Google Maps |
| **Gmail API** | Envio de emails com templates HTML e anexos |
| **JavaScript** | Regex com validação algorítmica, delays aleatórios, manipulação de dados |

---

## 🏗️ Padrões de Arquitetura Aplicados

- **Chain of AI Agents** — múltiplos agentes em sequência, onde o output de um alimenta o próximo
- **ETL com controle de estado** — Extract → Transform (IA) → Load, com deduplicação automática
- **OAuth2 com token caching** — Redis elimina latência de re-autenticação em integrações bancárias
- **Webhook handling** — callbacks assíncronos atualizam estado em tempo real
- **Humanização de automações** — delays aleatórios e mensagens únicas que simulam comportamento humano
- **Status-based automation** — ações condicionais baseadas no estado do dado (CRÍTICO, ATRASADO, etc.)
- **Progressive lead capture** — upsert por email enriquece a mesma linha a cada evento do usuário
- **Inactivity buffer pattern** — Redis acumula mensagens por conversa; processamento dispara só quando a conversa esfria
- **SPA embutida em webhook** — interface web completa servida como string no Response Body, sem infraestrutura de front-end separada

---

## 📬 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-silva-50376a1b6/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&to=guisilva28oliveira@gmail.com)

---

<div align="center">
<sub>Todos os workflows estão em produção · 2026</sub>
</div>
