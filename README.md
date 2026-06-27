<div align="center">
  <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" height="200" />

  # Hi 👋, I'm Abdullah Ali Ahmed

  ### DevOps Engineer | AI Engineer | Cloud Infrastructure Specialist

  <p>
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=DevOps+%26+AI+Engineer+%40+JISR;Building+AI+Products+%26+Automation;Kubernetes+%7C+Terraform+%7C+Claude+Code;Multi-Cloud+(AWS+%7C+GCP+%7C+OCI)" alt="Typing SVG" />
  </p>

  📍 Riyadh, Saudi Arabia | 💼 DevOps & AI Engineer @ JISR

</div>

---

## 🚀 Production AI Projects

### 🦞 [ClaudeClaw on Railway](https://github.com/bllo-1/claudeclaw-railway)
**Autonomous AI Agent Infrastructure** | Production • 24/7 Operations

Production deployment of ClaudeClaw autonomous AI agent system running headless on Railway.

**Key Features:**
- Headless OAuth credential management with automatic token refresh
- Persistent state across redeploys via Railway volumes
- Web dashboard with Bearer token authentication
- Telegram bot integration for remote interactions
- Scheduled autonomous runs (cron-based)
- Health monitoring and auto-restart policies

**Stack:** Docker, Railway, Bun, Node.js, Claude Code CLI, Shell
**Deployment:** Railway PaaS with persistent volumes at `/data`

---

### 🤖 CircleAI Legal Platform
**AI-Powered Legal SaaS** | Production • [Live](https://law.circleai.sa)

AI-powered legal assistance platform serving the Saudi legal industry.

**Features:**
- AI legal document analysis
- Legal Q&A powered by Claude AI
- Production AI product serving real users

**Stack:** (Details pending - private repository)
**Market:** Saudi Arabia legal services

---

## 💼 Full-Stack Enterprise Applications

### 🏢 [JISR HR Intranet Portal](https://github.com/bllo-1/intranet-company)
**Enterprise Internal Portal** | Production @ JISR | Django + HTMX

Comprehensive Django-based intranet portal with employee management, policies, announcements, and JISR API integration.

**Key Features:**
- 👥 Employee directory with organizational charts
- 📋 Policy management with acknowledgment tracking
- 📢 Company-wide announcements system
- 📄 Document management with Supabase Storage
- 🔐 SAML 2.0 SSO with Google Workspace (@jisr.net domain-restricted)
- 📊 RESTful API with automated employee sync (6-hour Railway cronjobs)
- 🔒 Security: HTTPS enforced, HSTS headers, 35 automated tests (94% passing)

**Stack:**
- **Backend:** Django 4.2 (lightweight JSON APIs, no DRF)
- **Auth:** djangosaml2 + Google Workspace SAML 2.0
- **Database:** PostgreSQL (Railway)
- **Storage:** Supabase Storage
- **Frontend:** Tailwind CSS 3 + HTMX 1.9 (dynamic interactions)
- **Deployment:** Railway with automated CI/CD
- **Monitoring:** Rollbar, Structlog, psutil
- **Server:** Gunicorn + WhiteNoise

**Deployment:** Railway (staging + production environments)
**Testing:** TDD approach with 94% test coverage on critical paths

---

### 🎫 [Helpdesk Support System](https://github.com/bllo-1/helpdesk-support-frontend) | [Backend](https://github.com/bllo-1/helpdesk-support-backend)
**IT Support & Ticketing Platform** | In Development | React + Django

Full-stack ticketing and support management system for IT operations.

**Frontend Stack:**
- **Framework:** React 19 + TypeScript
- **Build:** Vite
- **Router:** TanStack Router
- **State:** TanStack Query
- **UI:** Tailwind CSS + shadcn/ui + Radix UI
- **Charts:** Recharts
- **Hosting:** Railway

**Backend Stack:**
- **Framework:** Django 5.1 + Django REST Framework
- **Database:** PostgreSQL
- **Cache:** Redis (Celery, Channels)
- **Auth:** djangosaml2 (SAML 2.0) + JWT
- **WebSocket:** Channels + Daphne (real-time updates)
- **Tasks:** Celery + Redis
- **Monitoring:** Sentry
- **Server:** Gunicorn + WhiteNoise
- **Hosting:** Railway

**Architecture:** Decoupled frontend/backend with RESTful API + WebSocket support

---

### 💰 [Spend Tracker](https://github.com/bllo-1/spend-tracker-frontend) | [Backend](https://github.com/bllo-1/spend-tracker-backend)
**AI-Powered Expense Management** | In Development | React + Django + Claude AI

Intelligent expense tracking and budget management with AI-powered invoice extraction.

**Frontend Stack:**
- **Framework:** React 19 + TypeScript
- **Build:** Vite
- **Router:** TanStack Router + TanStack Start
- **State:** TanStack Query + Zustand
- **UI:** Tailwind CSS + Radix UI + shadcn/ui
- **Charts:** Recharts
- **Forms:** React Hook Form + Zod validation
- **Hosting:** Cloudflare (via Vite plugin)

**Backend Stack:**
- **Framework:** Django 5.0 + Django REST Framework
- **Database:** PostgreSQL (Supabase)
- **Storage:** Supabase Storage
- **AI:** Claude AI (Anthropic) for OCR/invoice extraction
- **Tasks:** Celery + Redis (scheduled jobs)
- **Email:** Django Anymail
- **PDF:** ReportLab + WeasyPrint
- **Auth:** JWT (Simple JWT)
- **Server:** Gunicorn + WhiteNoise
- **Hosting:** Railway

**Key Features:**
- 🤖 AI-powered invoice extraction using Claude AI
- 📊 Budget tracking and calculations
- 📧 Email notifications
- 📄 PDF report generation
- ⏰ Scheduled background jobs with Celery
- 💾 File uploads to Supabase Storage

**Architecture:** Modern full-stack with AI integration for intelligent expense processing

---

### 🏠 Maladh Almuwatin Real Estate
**Corporate Real Estate Website** | In Development

Real estate company website.

**Stack:** (Details pending - analyzing repository)
**Type:** Corporate website

---

## 🔧 AI Engineering Operating System

**Personal Productivity System** | Active Development

Standardized AI workflows and automation for professional AI engineering.

**Components:**
- 📄 **CLAUDE.md** — Standard project documentation for Claude Code
- 📊 **STATE.md** — Real-time project state tracking
- 🔄 **LOOP.md** — Loop Engineering for automated maintenance
- 🛠️ **Custom MCP Servers** — Tool integration layer
- 📚 **Knowledge Base** — Centralized documentation and prompts

**Goal:** Make every project instantly understandable to Claude Code and automate repository maintenance.

---

## 🛠️ Tech Stack & Tools

### 🤖 AI & Automation
![Claude](https://img.shields.io/badge/Claude-6B46C1?style=for-the-badge&logo=anthropic&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-FF6B6B?style=for-the-badge&logo=robot&logoColor=white)

**AI Tools:** Claude Code, Claude API (Anthropic), Autonomous Agents, RAG Systems
**AI Workflows:** Prompt engineering, context engineering, multi-agent systems, OCR/document extraction
**MCP:** Model Context Protocol integration

### ☁️ Cloud Platforms
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

**GCP:** GKE, Cloud SQL, Compute Engine, VPC, Cloud Storage, Cloud Load Balancing, IAM
**AWS:** EKS, EC2, RDS, S3, WAF, IAM, Route53
**OCI:** Compute, Networking, Storage
**PaaS:** Railway (containerized deployments, cronjobs, volumes)
**BaaS:** Supabase (PostgreSQL, Storage, Auth)

### 🐳 Container & Orchestration
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)

**Kubernetes:** GKE, EKS, Deployments, Services, ConfigMaps, Secrets, RBAC, Network Policies
**Container Tools:** Docker, containerd, Docker Compose
**Package Management:** Helm Charts, Helm Repositories

### 🔄 CI/CD & GitOps
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**CI/CD:** GitHub Actions, ArgoCD, GitOps workflows
**Version Control:** Git, GitHub
**Deployment Strategies:** Blue-Green, Canary, Rolling Updates
**Loop Engineering:** Automated repository maintenance

### 🏗️ Infrastructure as Code
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

**IaC Tools:** Terraform, Terraform Modules, State Management
**Configuration:** YAML, HCL, JSON

### 📊 Monitoring & Observability
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)
![New Relic](https://img.shields.io/badge/New_Relic-008C99?style=for-the-badge&logo=new-relic&logoColor=white)

**Monitoring:** DataDog, New Relic, Rollbar, Sentry
**Logging:** Structlog, Django logging
**Metrics:** APM, Infrastructure Monitoring, psutil, Log Management
**Alerting:** Custom alerts, SLO/SLI tracking

### 🔐 Security & Secrets Management
![Vault](https://img.shields.io/badge/Vault-000000?style=for-the-badge&logo=vault&logoColor=white)

**Secrets Management:** HashiCorp Vault
**Access Management:** Teleport, IAM, RBAC
**Authentication:** SAML 2.0 SSO (djangosaml2), JWT
**Security:** Network Policies, Pod Security Standards, WAF, HSTS, secure cookies

### 💻 Programming & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Languages:** Python, JavaScript/TypeScript, Bash, SQL
**Python Frameworks:** Django, Django REST Framework, Celery, FastAPI
**JS Runtimes:** Node.js, Bun
**Frontend Frameworks:** React 19, Next.js, TanStack Router, Vite
**Testing:** pytest, Django test framework, TDD methodology

### 🗄️ Databases & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Relational:** PostgreSQL, Cloud SQL (via Supabase, Railway)
**Cache:** Redis (Celery broker, Channels layer)
**NoSQL:** MongoDB
**Database Tools:** pg_dump, pg_restore, Logical Replication, psycopg

### 🎨 Frontend & UI
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**UI Libraries:** Radix UI, shadcn/ui, HTMX
**Styling:** Tailwind CSS 3-4, CSS Modules
**State Management:** TanStack Query, Zustand
**Forms:** React Hook Form, Zod validation
**Charts:** Recharts

### 🌐 Networking & Load Balancing
**Networking:** VPC, Subnets, Firewall Rules, VPN, VPC Peering
**Load Balancing:** Cloud Load Balancer, NGINX, Ingress Controllers
**DNS:** Cloud DNS, Route53

### 🔧 Other Tools
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

**Operating Systems:** Linux (Ubuntu, Debian)
**IDEs:** VS Code, Claude Code, Vim
**Collaboration:** Slack, Confluence, Jira
**Version Control:** Git, GitHub

---

## 📈 Key Technical Achievements

### DevOps & Infrastructure
- 🏗️ Multi-region cloud infrastructure implementation
- 🚀 CI/CD pipeline optimization (45 min → 12 min)
- 💰 Cloud cost optimization (30% reduction)
- 📊 Comprehensive infrastructure monitoring and alerting
- 🔒 Enterprise security implementation (RBAC, Network Policies, Vault)
- 🤝 DevOps workflows coordination for 100+ developers

### AI Engineering & Full-Stack Development
- 🤖 Production deployment of autonomous AI agent (ClaudeClaw on Railway)
- 🦾 AI-powered SaaS products serving real users (CircleAI, Spend Tracker)
- 📚 Built AI Engineering Operating System with standardized workflows
- 🔄 Implementing Loop Engineering for automated repository maintenance
- 🛠️ AI-powered document extraction using Claude AI (OCR/invoice processing)
- 🏢 Enterprise Django applications with SAML 2.0 SSO (94% test coverage)
- ⚡ Modern full-stack architecture (React 19 + Django 5 + PostgreSQL)

---

## 🎯 Current Focus

**Building AI Products & Infrastructure:**
- 🧠 RAG Knowledge Assistant for document search
- 🔍 PR Review Agent with automated code analysis
- 📅 Daily Work Assistant with multi-source aggregation
- 🧪 AI Evaluation Lab for prompt/model quality testing

**Professional Development:**
- 📈 Senior AI Engineer track
- 🏗️ AI Product Engineering methodologies
- 🤝 Multi-agent system architecture
- 📊 AI observability and evaluation

---

## 🌟 Featured in

- 📰 [AWS Official Case Study](https://aws.amazon.com/solutions/case-studies/jisr-case-study/) - JISR Infrastructure Modernization

---

## 📫 Connect with Me

<p align="left">
<a href="https://www.linkedin.com/in/bllo1/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:bllo.work1@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://github.com/bllo-1" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
</p>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bllo-1&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bllo-1&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=bllo-1&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</div>

---

<div align="center">

  ### 💡 "Infrastructure as Code, AI as Partner, Excellence as Culture"

  ![Profile Views](https://komarev.com/ghpvc/?username=bllo-1&color=blue&style=for-the-badge)

</div>
