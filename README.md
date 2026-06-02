<div align="center">

# Ashish Choudhary

### I build AI systems that automate enterprise program delivery.

*Senior Delivery Manager · Technical Program Manager · GenAI Builder*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashish-choudhary-iim/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ashishchoudhary7722-ctrl)

</div>

---

## Who I Am

TPM with **5+ years** delivering **$1M–$5M enterprise programs** — Salesforce CRM, Commerce Cloud, Order-to-Cash.

The difference: I also **build the AI systems** that run those programs.

> Currently leading a **31-brand CRM migration** at Forsys Inc., managing 30+ engineers across Sales Cloud, Revenue Cloud, CPQ, CLM, and MuleSoft integrations.

---

## Start Here → Flagship Project

### [PM-Agents](https://github.com/ashishchoudhary7722-ctrl/Git/tree/master/pm-agents) — Multi-Agent AI System for TPM Automation

> **The problem:** TPMs spend 60–70% of their time on documents, status updates, and planning artifacts that follow predictable patterns.
> **My solution:** 3 specialized AI agents that automate all of it.

**Agent Architecture:**

```mermaid
graph TD
    U[User Message] --> F[Flask Backend]
    F --> TP[ThreadPoolExecutor - 3 parallel calls]
    TP --> A[Alpha\nDelivery & Sprint Manager]
    TP --> B[Beta\nStakeholder Communication]
    TP --> C[Casa\nRequirements & BA]
    A --> H[Shared Session History]
    B --> H
    C --> H
    H --> R[Single Combined Response]

    style A fill:#4f46e5,color:#fff
    style B fill:#0891b2,color:#fff
    style C fill:#059669,color:#fff
```

**Impact:**
- `60–70%` reduction in TPM documentation time
- L3/L4 breakdown, PRDs, RAID logs, sprint readiness — on demand
- Deployed on a live $5M+ Salesforce enterprise program

**Stack:** `Python` · `Flask` · `Anthropic Claude` · `ThreadPoolExecutor` · `Vanilla JS`

---

## How I Think About Systems

**LLM Orchestration (PM-Agents):**

```mermaid
sequenceDiagram
    participant User
    participant Flask
    participant Agents as 3 Agents (parallel)
    participant Claude as Anthropic Claude API

    User->>Flask: Message + session history
    Flask->>Agents: 3 simultaneous API calls
    Agents->>Claude: Specialized system prompts
    Claude-->>Agents: Domain-specific responses
    Agents-->>Flask: Alpha + Beta + Casa outputs
    Flask-->>User: Combined team response
```

**Enterprise Delivery Flow (what I manage):**

```mermaid
graph LR
    CRM[C-CRM\nCore CRM] --> BCRM[B-CRM\nBrand CRM]
    BCRM --> SOM[SOM\nOrder Mgmt]
    SOM --> SFCC[SFCC\nCommerce Cloud]
    MU[MuleSoft\nIntegration Layer] --> CRM & BCRM & SOM & SFCC

    style MU fill:#f59e0b,color:#fff
    style SFCC fill:#00A1E0,color:#fff
```

---

## Other Projects

### [Job Agent](https://github.com/ashishchoudhary7722-ctrl/Git/tree/master/job-agent) — Automated Job Outreach Pipeline

- End-to-end automation: searches, applies, and sends referral messages on LinkedIn + Naukri
- Attaches CV automatically — zero stored credentials (uses Chrome remote debugging)

`Python` · `Selenium` · `Chrome Remote Debugging`

---

## Tech Stack

**AI / LLM**

![Anthropic](https://img.shields.io/badge/Anthropic%20Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Enterprise Systems**

![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![MuleSoft](https://img.shields.io/badge/MuleSoft-00A1DF?style=flat-square&logo=mulesoft&logoColor=white)

**Engineering**

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

**Program Management**

![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)
![Miro](https://img.shields.io/badge/Miro-050038?style=flat-square&logo=miro&logoColor=yellow)

---

## Proof of Impact

| Program | Scale | Outcome |
|---|---|---|
| CRM Migration | 31 brands · 7M alumni | Multi-track delivery in progress |
| Salesforce Build | Sales Cloud + Revenue Cloud + CPQ | Zero production incidents |
| PM-Agents | Internal AI tooling | 60–70% TPM overhead cut |
| Capgemini PMO | €1.5M project · Heathrow + Coca-Cola | €30K/month savings · 10% efficiency gain |

---

## Certifications

![PMP](https://img.shields.io/badge/PMP-Project%20Management%20Professional-0052CC?style=flat-square)
![PSM](https://img.shields.io/badge/PSM%20I-Professional%20Scrum%20Master-87CEEB?style=flat-square)
![RCA](https://img.shields.io/badge/RCA%C2%AE-Revenue%20Cloud%20Associate%20%7C%20Salesforce-00A1E0?style=flat-square)
![Fit2Lead](https://img.shields.io/badge/Fit2Lead-FranklinCovey-FF6B35?style=flat-square)

---

## GitHub Stats

<div align="center">

![Ashish's GitHub Stats](https://github-readme-stats.vercel.app/api?username=ashishchoudhary7722-ctrl&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ashishchoudhary7722-ctrl&layout=compact&theme=default&hide_border=true)

</div>

---

<div align="center">

**Open to Senior TPM · Program Manager (AI) · Delivery Manager roles**

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashish-choudhary-iim/)

*"I don't just manage programs. I build the systems that run them."*

</div>
