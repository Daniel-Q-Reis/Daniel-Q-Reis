<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=4000&pause=1000&color=3B82F6&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Daniel+Reis;Full-Cycle+Engineer;Go+%E2%80%A2+Python+%E2%80%A2+React;Building+Production-Grade+Systems" alt="Typing SVG" />
</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/danielqreis)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://danielqreis.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:danielqreis@gmail.com)

`Brazil (UTC-3)` • `International Contractor (W-8BEN)` • `EN/PT/ES`
</div>

---

##  About Me
**Backend Engineer** capable of delivering full-stack solutions in **Go**, **Python (Django)**, and **React/TypeScript** with a focus on **Clean Architecture**, **Domain-Driven Design**, and **cloud-native systems**.

* **Engineering Mindset**: Background in Operations & Quality Engineering — analytical thinking and systematic problem-solving now applied to software architecture.
* **Rapid Progression**: Built **12+ projects** in 2025, demonstrating a fast transition from fundamentals to enterprise-level distributed systems.
* **Quality First**: Intensive hands-on training focused on observability, scalability, and production-grade reliability.

---

## Featured Project: HealthCore API
[![HealthCore API](https://github.com/Daniel-Q-Reis/HealthCoreAPI/blob/main/frontend/public/images/project/landingpage5173.png?raw=true)](https://github.com/Daniel-Q-Reis/HealthCoreAPI)
**Enterprise Hospital Management Platform** — Production healthcare system with HIPAA-aligned architecture  
*Django + Go + React/TypeScript · PostgreSQL · Redis · Kafka · MongoDB · Terraform · Azure*

###  System Architecture
```mermaid
graph LR
    User[React/TS Frontend] --> API[Django DRF - Modular Monolith]
    API --> DB_SQL[(PostgreSQL)]
    API --> Cache[(Redis)]
    API -- Async Events --> KAFKA{Apache Kafka}
    KAFKA --> GO_SVC[Go Audit Microservice]
    GO_SVC --> DB_NOSQL[(MongoDB)]
    
    style API fill:#092e20,stroke:#3b82f6,color:#fff
    style GO_SVC fill:#00add8,stroke:#3b82f6,color:#fff
    style KAFKA fill:#231f20,stroke:#fff,color:#fff
```

 **[Live Demo](https://app.danielqreis.com/dqr-health)** ·  **[For Developers](https://app.danielqreis.com/dqr-health/developers)** — API Docs, Metrics & Endpoints
[![GitHub](https://img.shields.io/badge/GitHub-Source-181717?style=flat-square&logo=github)](https://github.com/Daniel-Q-Reis/HealthCoreAPI)
[![Showcase](https://img.shields.io/badge/Full_Showcase-blue?style=flat-square)](https://github.com/Daniel-Q-Reis/HealthCoreAPI/blob/main/SHOWCASE.md)
[![CI](https://img.shields.io/github/actions/workflow/status/Daniel-Q-Reis/HealthCoreAPI/ci.yml?style=flat-square&label=CI)](https://github.com/Daniel-Q-Reis/HealthCoreAPI/actions)
### Key Achievements
| Area | Highlights |
|------|------------|
| **Architecture** | Modular Monolith · 12 DDD Bounded Contexts · FHIR/HL7 Aligned · 23 ADRs |
| **Polyglot Services** | Go 1.24 Audit Microservice · gRPC (Protocol Buffers) · <100ms latency |
| **Frontend** | React 18 + TypeScript · Feature-Sliced Design · 25+ UI Components · Dark Mode |
| **Infrastructure** | Terraform IaC · Azure Container Apps · Custom Domains · SSL/HTTPS · OAuth 2.0 |
| **Performance** | 85% p99 reduction (180ms → 26ms) via N+1 elimination · Kafka event monitoring |
| **Quality** | 283 tests · 90%+ coverage · MyPy strict (0 errors) · 100K+ lines of code |
| **Observability** | Prometheus · Grafana Dashboards · Azure Application Insights · Structured Logging |
| **Resilience** | Circuit Breaker (PyBreaker) · Idempotency Middleware · Retry Logic |
| **AI Integration** | Gemini 2.5 (drug analysis) · GPT-4 (health recommendations) |
---

## 📂 Other Notable Projects
* **[DrugStore API](https://github.com/Daniel-Q-Reis/drugstore_api)**: Pharmacy SaaS • Python/Django • AWS (EC2, RDS, S3) • Chart.js Analytics.
* **[Social API](https://github.com/Daniel-Q-Reis/social_api)**: Social Network Backend • Go • PostgreSQL • Clean Architecture • JWT/RBAC.
* **[Goroutines Study](https://github.com/Daniel-Q-Reis/GoroutinesFromBeginningToAdvanced)**: Go Concurrency Deep Dive — Built without AI for deep understanding.

---
## Tech Stack
### Languages & Frameworks
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=google&logoColor=white)
### Databases & Messaging
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
### Cloud & DevOps
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
### Architecture Patterns
`Clean Architecture` · `Hexagonal (Ports & Adapters)` · `Domain-Driven Design` · `Feature-Sliced Design` · `Event-Driven` · `Microservices` · `Modular Monolith`
---
## GitHub Stats
![Daniel's GitHub stats](https://github-readme-stats.vercel.app/api?username=Daniel-Q-Reis&show_icons=true&theme=tokyonight&hide_border=true)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Daniel-Q-Reis&theme=tokyonight&hide_border=true)
---
## Currently
- Open to **Full-Cycle/Backend Engineer** opportunities (Remote, international contractor)
- Deepening expertise in **query optimization**, **CI/CD pipelines**, and **test automation**
- Reach me: [danielqreis@gmail.com](mailto:danielqreis@gmail.com)
---
> *"Production-grade mindset. Enterprise architecture skills. Ready to contribute."*
