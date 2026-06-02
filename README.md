<div align="center">

# Ashish Choudhary

### I build AI systems that automate enterprise program delivery.

*Senior Delivery Manager · Technical Program Manager · GenAI Builder*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashish-choudhary-iim/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ashishchoudhary7722-ctrl)

</div>

---

## What I Do

I'm a TPM with **5+ years** delivering $1M–$5M enterprise programs — Salesforce CRM, Commerce Cloud, and Order-to-Cash platforms.

The difference: I also **build the AI tools** that run those programs.

> Currently leading a **31-brand CRM migration** at Forsys Inc., managing 30+ engineers across Sales Cloud, Revenue Cloud, CPQ, CLM, and MuleSoft — while building internal AI systems to automate delivery workflows.

---

## Flagship Project

### [PM-Agents](https://github.com/ashishchoudhary7722-ctrl/Git/tree/master/pm-agents) — Multi-Agent AI System for TPM Automation

> The problem: TPMs spend 60–70% of their time on documents, status updates, and planning artifacts that follow predictable patterns. I automated them.

**What it does:**

| Agent | Role |
|---|---|
| **Alpha** | Sprint management, delivery tracking, go-live readiness |
| **Beta** | Stakeholder comms, exec summaries, steering committee updates |
| **Casa** | Requirements, user stories, acceptance criteria, PRDs |

**How it works:**

```
User Message
    │
    ▼
┌─────────────────────────────────────────┐
│           Flask Backend                  │
│   ThreadPoolExecutor (3 parallel calls) │
└────┬──────────────┬──────────────┬──────┘
     │              │              │
     ▼              ▼              ▼
  Alpha           Beta           Casa
(Delivery)     (Comms)       (Requirements)
     │              │              │
     └──────────────┴──────────────┘
                    │
              Shared session
              history context
                    │
                    ▼
           Single chat response
```

**Impact:**
- 60–70% reduction in manual TPM documentation time
- Instant L3/L4 work breakdown from a single prompt
- PRDs, RAID logs, sprint readiness — on demand
- Deployed on live Salesforce program data

**Stack:** `Python` · `Flask` · `Anthropic Claude` · `ThreadPoolExecutor` · `Vanilla JS`

---

## Other Projects

### [Job Agent](https://github.com/ashishchoudhary7722-ctrl/Git/tree/master/job-agent) — Automated Job Outreach Pipeline

End-to-end job application automation:
- Searches and applies on LinkedIn Easy Apply + Naukri + company portals
- Sends personalized referral messages to LinkedIn connections with CV attached
- Attaches to your existing logged-in Chrome — zero stored credentials

**Stack:** `Python` · `Selenium` · `Chrome Remote Debugging` · `CSV logging`

---

## Engineering Depth

**How I think about systems:**

```
Enterprise Program Data
        │
        ▼
┌───────────────────┐
│   LLM Agents      │  ← Prompt engineering + role specialization
│   (Claude API)    │
└────────┬──────────┘
         │ Structured output
         ▼
┌───────────────────┐
│  Shared Context   │  ← Session history, cross-agent awareness
│     Store         │
└────────┬──────────┘
         │
         ▼
┌───────────────────┐
│  Flask REST API   │  ← /chat, /clear, session management
└────────┬──────────┘
         │
         ▼
┌───────────────────┐
│   Web UI          │  ← Real-time multi-agent responses
└───────────────────┘
```

**On the delivery side:**

```
Program Scope
    │
    ├── L1: Epic / Feature
    ├── L2: Module / Track
    ├── L3: Story / Task      ← PM-Agents automates this
    └── L4: Sub-task / AC     ← PM-Agents automates this

Cross-system flow I manage:
C-CRM → B-CRM → SOM → SFCC/CloudCraze (MuleSoft integration layer)
```

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
| CRM Migration | 31 brands, 7M alumni | Ongoing — multi-track delivery |
| Salesforce Build | Sales Cloud + Revenue Cloud + CPQ | Zero production incidents |
| PM-Agents | Internal AI tooling | 60–70% TPM overhead reduction |
| Capgemini PMO | €1.5M project | €30K/month savings, 10% efficiency gain |

---

## Certifications

![PMP](https://img.shields.io/badge/PMP-Project%20Management%20Professional-blue?style=flat-square)
![PSM](https://img.shields.io/badge/PSM%20I-Professional%20Scrum%20Master-lightblue?style=flat-square)
![RCA](https://img.shields.io/badge/RCA%C2%AE-Revenue%20Cloud%20Associate%20%7C%20Salesforce-00A1E0?style=flat-square)
![PMP](https://img.shields.io/badge/Fit2Lead-FranklinCovey-orange?style=flat-square)

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
