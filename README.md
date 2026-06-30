# Lucas Rios — Senior .NET & Cloud Engineer

**14+ years** building production systems in **.NET/C#** and **AWS** — from multi-tenant SaaS platforms to distributed event-driven architectures.

Currently focused on: serverless messaging systems, AWS Lambda pipelines, SQL Server performance at scale, and AI integration in backend services.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-cunha-rios/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:lucas.trr@hotmail.com)
![AWS](https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-orange?style=flat-square&logo=amazonaws)

---

## Featured Project

### [WhatsApp AWS Ecosystem](https://github.com/LucasRios/WhatsApp-AWS-Ecosystem)

Distributed WhatsApp messaging platform built on **AWS Lambda + SQS** — handles inbound webhook reception, credential management, multi-stage delivery, and full audit trail in SQL Server.

```
Meta API → LambdaSQSReceiver → SQS → LambdaGetMetaCredentials
        → SQS → LambdaSQSEnvio → LambdaSQSEnvioPostAPI → Meta API
                               → LambdaSQSEnvioSalvaRetorno → LambdaSQLWriter → RDS
```

6 independent Lambda functions, each with its own SQS trigger, DLQ, and IAM least-privilege policy.
Stage isolation means any function can fail, retry, and recover without cascading.

---

## Repositories

| Repo | What's inside |
|---|---|
| [WhatsApp-AWS-Ecosystem](https://github.com/LucasRios/WhatsApp-AWS-Ecosystem) | Distributed serverless messaging system — Lambda, SQS, Meta API, RDS |
| [AWS-Examples](https://github.com/LucasRios/AWS-Examples) | Lambda automation, EC2 lifecycle management, Security Group auto-update, Bedrock, email capture pipeline |
| [SQLServer-Examples](https://github.com/LucasRios/SQLServer-Examples) | CLR extensions, async procedures, HTTP calls from T-SQL, DBA performance scripts |
| [AI-Examples](https://github.com/LucasRios/AI-Examples) | OpenAI, Whisper, AWS Bedrock, generative pipelines, AI inside SQL Server |
| [DotNet-Utilities](https://github.com/LucasRios/DotNet-Utilities) | .NET console tools — AES-256 encryption, NF-e XML importer, system monitor, PowerPoint generator, Telegram bot, PDF/Base64 utilities |
| [Learning-Lab](https://github.com/LucasRios/Learning-Lab) | Structured notes and experiments — AWS, DevOps, AI, Data Science |
| [GestaoMax](https://github.com/LucasRios/GestaoMax) | Shared SQL utilities and GeoJSON assets for the GestaoMax multi-tenant SaaS platform |
| [Mapas](https://github.com/LucasRios/Mapas) | GeoJSON dataset of all 5,570 Brazilian municipalities — ready for Leaflet, Mapbox, Google Charts |
| [FIAP](https://github.com/LucasRios/FIAP) | Academic coursework — M.Sc. in Intelligence Technology and Digital Design (PUC-SP / FIAP) |

---

## Tech Stack

| Area | Technologies |
|---|---|
| **Backend** | .NET 8 / C#, Node.js, REST APIs, Microservices |
| **AWS** | Lambda, SQS, EC2, S3, IAM, Secrets Manager, CloudWatch, Bedrock |
| **Database** | SQL Server (T-SQL, CLR, performance tuning), Firebird, MySQL, Entity Framework |
| **AI** | OpenAI GPT, Whisper, AWS Bedrock, LLM integration, prompt engineering |
| **Frontend** | HTML5, CSS3, JavaScript, Google Charts, Maps API |
| **DevOps** | CI/CD, Git, Agile, Lean Startup |

---

## Impact

- **−40%** monthly AWS cost reduction through Savings Plans and architecture optimization
- **−50%** reduction in SQL Server performance bottlenecks through indexing and query tuning
- **99.9%** availability on high-volume B2B conversational platforms
- **8+ years** architecting multi-tenant SaaS with microservices

---

## Background

- **M.Sc. in Intelligence Technology and Digital Design** — PUC-SP
- **AWS Certified Cloud Practitioner**
- Expertise in Lean Startup and Technical Product Management

---

*Turning complex business requirements into resilient, cost-effective cloud solutions.*
