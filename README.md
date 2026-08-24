# 👋 Hi, I'm Israel Ayongwa

> 🚀 Senior Cloud & AI Platform Engineer | Azure Infrastructure | IaC & DevOps Automation | Agentic AI | Serverless & App Platforms

---

## 🧩 About Me

I'm a **Senior Cloud & AI Platform Engineer** with 10+ years of experience designing, automating, and operating secure Azure environments for enterprise clients across **oil & gas, government, finance, public sector, insurance, healthcare, and marketing**.

My career has been built in the **consulting space** — which means I've had to earn trust fast, adapt to diverse client environments, and deliver production-grade outcomes across a wide variety of sectors and organizational maturity levels. From CAF-aligned Azure Landing Zones for federal agencies to private-endpoint-secured AI Foundry platforms for agricultural multinationals, I bring deep Azure infrastructure expertise paired with a strong automation-first engineering mindset.

I specialize in:
- **Azure cloud infrastructure** — compute, networking, storage, PaaS, VNet, NSG, Private Endpoints, App Gateway, Azure Front Door, WAF
- **Infrastructure-as-Code** — Terraform (HCL, CDKTF TypeScript), Bicep, ARM across multi-environment pipelines
- **AI platform engineering** — Azure AI Foundry, Azure OpenAI (GPT-4.1/5), RAG pipelines, Microsoft Copilot Studio, and responsible AI governance
- **Serverless & M365 automation** — Azure Functions, Microsoft Graph, Azure Automation Runbooks, Power Automate, SharePoint integration
- **Identity & zero-trust security** — Microsoft Entra ID, Conditional Access, RBAC, Managed Identities, Key Vault, secretless auth patterns
- **CI/CD & DevOps** — Azure DevOps Pipelines, GitHub Actions, Azure Deployment Stacks, multi-stage gated pipelines

I'm also an active community contributor at **KubeSkills** and mentor aspiring IT professionals at the **Newcomers Centre, Canada**.

---

## 🔭 Current & Recent Projects

### 🤖 SEO Request Automation Engine — Azure Functions + AI Foundry (American Family Care)
Designed and shipped a serverless Azure enrichment engine that automates SEO request triage — a scheduled Azure Function reads a SharePoint/Excel tracker, auto-fetches Google Search Console, GA4, and DataForSEO metrics per row, scores each request using **GPT-5 on Azure AI Foundry** with a written priority rationale, and writes results back into the same sheet. Coordinator enters 6 columns; the engine fills the other 11.
- Engineered a **secretless, managed-identity security model** (Key Vault, app-only Graph Sites.Selected, zero API keys in code)
- Authored **Azure Automation Runbooks** to instrument an end-to-end data lineage and audit trail — every metric in the tracker is auditable back to its source API call
- Migrated CI/CD from GitHub Actions into the client's Azure DevOps org — four pipelines covering CI quality gates, gated infra deploy with what-if approval, packaged code deploy, and on-demand run
- Diagnosed and resolved live production failures via **Application Insights / KQL**

### 💬 Azure AI Foundry Policy Assistant — RAG Chatbot (American Family Care)
Built a production-grade **GPT-5-powered RAG policy assistant** on the client's Azure tenant — grounding answers in a real policy corpus using **Azure AI Search** (hybrid keyword + vector + semantic reranking), with inline citation rendering and server-side prompt-injection protection.
- Vue 3 + TypeScript SPA on **Azure Static Web Apps** with Azure Functions (Node 24, ESM v4) backend
- Custom **Node/TypeScript ingestion pipeline** for chunking, embedding, and index upsert
- Single idempotent **Bicep template** provisioning the entire stack end-to-end
- GitHub Actions CI with ESLint, strict TypeScript, and ≥80% Vitest coverage

### 🏗️ Enterprise AI Foundry Framework — Corteva & Vylor Spin-Co
Designed and delivered an **enterprise-grade, network-isolated Azure AI Foundry platform** as modular Bicep IaC — private endpoints throughout, zero public internet exposure of AI model endpoints, VNet-integrated APIM gateway with model-aware routing, and multi-vendor model catalog (OpenAI, Microsoft, xAI, Anthropic) across multiple Foundry regions with active/passive failover.
- Subscription-scope Bicep orchestrator across multiple resource groups from a single deployment
- **Model-aware APIM routing** with per-model backend pools, circuit breakers, and retry logic
- Comprehensive **Responsible AI content-filter** (prompt shields, protected material, jailbreak detection)
- **Templatized for M&A spin-off** (Vylor) — same IaC re-parameterized for a new corporate entity
- Azure DevOps pipeline using **Azure Deployment Stacks** with Validate → What-If → Deploy staged workflow

### ☁️ Azure Landing Zone Implementations — Federal & Enterprise Clients
CAF-aligned Landing Zone implementations for public sector and enterprise clients across Canada — gap analysis, architecture diagrams, ALZ playbooks for multi-region onboarding, and reusable Terraform modules and Bicep templates for guardrails, policy, and governance.

### 📊 Lumina Data Platform — Azure Databricks Integration
Automated resource provisioning workflow via a Self-Serve Portal backed by Terraform CI/CD pipelines; reusable Terraform modules for TFE workspace provisioning; Databricks log ingestion to **Log Analytics** visualized in **Grafana dashboards** with Python Functions and KQL alerts.

---

## 🎯 Core Competencies

| Domain | Technologies & Skills |
|---|---|
| **Azure Infrastructure** | Compute · Networking · Storage · PaaS · VNet · NSG · Private Endpoints · Private Link · Hub-Spoke · App Gateway · Azure Front Door · WAF |
| **IaC & Automation** | Terraform (HCL, CDKTF TypeScript) · Bicep · ARM · Azure Automation Runbooks · Power Automate · PowerShell · Bash · Python |
| **CI/CD & DevOps** | Azure DevOps Pipelines · GitHub Actions · Azure Deployment Stacks · Multi-stage gated pipelines · Validate/What-If/Deploy |
| **AI & Copilot Platforms** | Azure AI Foundry · Azure OpenAI (GPT-4.1/5) · Microsoft Copilot Studio · RAG / AI Search · Document Intelligence · GitHub Copilot · Claude.ai |
| **Serverless & App Platforms** | Azure Functions · Azure Static Web Apps · Azure App Service · Logic Apps · Microsoft Graph · SharePoint / M365 Automation |
| **Identity & Security** | Microsoft Entra ID · Conditional Access · RBAC · Managed Identities · Key Vault · WAF · Zero Trust · Secretless Auth |
| **Monitoring & Observability** | Azure Monitor · Log Analytics · KQL · Application Insights · Grafana · Data Lineage & Audit Trails |
| **Containers & Runtimes** | Docker · AKS · Azure Container Registry · Node.js · Python |
| **Data Platforms** | Azure Databricks · Delta Lake · Microsoft Fabric · Azure Data Factory · Synapse |

---

## 🧰 Technical Stack

<p align="center">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/azure/azure.png" height="45" alt="Azure" title="Azure" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/terraform/terraform.png" height="45" alt="Terraform" title="Terraform" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/github-actions/github-actions.png" height="45" alt="GitHub Actions" title="GitHub Actions" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/docker/docker.png" height="45" alt="Docker" title="Docker" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/kubernetes/kubernetes.png" height="45" alt="Kubernetes" title="Kubernetes" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/python/python.png" height="45" alt="Python" title="Python" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/databricks/databricks.png" height="45" alt="Databricks" title="Databricks" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/visual-studio-code/visual-studio-code.png" height="45" alt="VS Code" title="VS Code" />
</p>

---

## 🏆 Certifications

| Certification | Issuer |
|---|---|
| Azure Solutions Architect Expert (AZ-305) | Microsoft |
| Azure DevOps Engineer Expert (AZ-400) | Microsoft |
| Azure Administrator Associate (AZ-104) | Microsoft |
| Azure Security Technologies (AZ-500) | Microsoft |
| Azure AI Fundamentals (AI-900) | Microsoft |
| Azure Data Fundamentals (DP-900) | Microsoft |
| Microsoft Fabric Analytics Engineer Associate | Microsoft |
| GitHub Copilot Certification | GitHub |
| HashiCorp Certified: Terraform Associate | HashiCorp |
| SAIT — Database Administration & Networking | SAIT |

<details>
<summary>📜 View My Certification Snapshot</summary>
<p align="center">
  <img src="https://user-images.githubusercontent.com/54389703/144715523-81e604b0-19de-4448-90e9-34c29083ab87.png" width="70%" alt="Certifications Snapshot" />
</p>
</details>

---

## 📈 GitHub Stats & Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=iayongwa&show_icons=true&count_private=true&theme=transparent" height="165" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=iayongwa&theme=transparent" height="165" />
</p>

<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=iayongwa&theme=flat&margin-w=5" alt="GitHub Trophies" />
  </a>
</p>

---

## 🌍 Industry Experience

`Oil & Gas` &nbsp;·&nbsp; `Federal & Provincial Government` &nbsp;·&nbsp; `Finance` &nbsp;·&nbsp; `Insurance` &nbsp;·&nbsp; `Healthcare` &nbsp;·&nbsp; `Agriculture` &nbsp;·&nbsp; `Public Sector` &nbsp;·&nbsp; `Marketing Automation` &nbsp;·&nbsp; `Transport`

---

## 📫 Connect with Me

<p align="center">
  <a href="https://github.com/iayongwa" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-iayongwa-181717?style=for-the-badge&logo=github" />
  </a>
  &nbsp;
  <a href="https://twitter.com/iayongwa" target="_blank">
    <img src="https://img.shields.io/twitter/follow/iayongwa?style=for-the-badge&logo=twitter&color=1DA1F2" />
  </a>
</p>

- 🌐 **Open to:** Senior Cloud Engineer · AI Platform Engineer · Cloud Architect · DevOps Lead roles
- 📍 **Location:** British Columbia, Canada (Remote)

---

⚡ *Fun fact:* Before becoming a cloud engineer, I was a part-time DJ. 🎧

*"I build the Azure infrastructure that AI, security, and data platforms run on — and I automate everything in between."*

✨ From [@iayongwa](https://github.com/iayongwa)
