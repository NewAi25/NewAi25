# Hi, I'm Manisha 👋

### Infrastructure & Cloud Security Engineer · Co-Founder & CTO @ Oz Lunara · AI evals

I own infrastructure end to end: AWS, EKS, Terraform, CI/CD and security. I also build and check AI evaluations.

- 🛠 Co-Founder & CTO at [Oz Lunara](https://app.ozlunara.com/), a cloud and AI security platform (private beta)
- 🤖 AI Platform Engineer (contract) at Nodex8.ai, building Ask Claris, a guarded NL-to-SQL governance copilot
- 🧪 Built [DeskBench](https://github.com/NewAi25/deskbench), a benchmark for AI reliability on messy office work
- 🐄 Sentient Futures Project Incubator mentee, working on AI × animal welfare ([plf-audit](https://github.com/NewAi25/plf-audit))
- 🌍 Based in Kolkata, working remote, open to relocating

## 🧰 Stack

**Cloud:** AWS (EKS, ECS Fargate, IAM, Cognito, VPC, WAF, CloudFront, RDS) · Azure
**IaC:** Terraform · Pulumi · CloudFormation · Helm
**Containers:** Docker · Kubernetes (EKS) · Ingress
**CI/CD:** GitHub Actions · GitOps · Jenkins · SonarQube
**Security:** least-privilege IAM · Postgres RLS · secrets (SSM) · OPA policy gates · audit logging
**Code:** Python · SQL · TypeScript · Bash · HCL
**AI:** LLM APIs (Anthropic, Bedrock) · RAG · evals · MCP · Claude Code

## 💼 Experience

**Co-Founder & CTO** · *Oz Lunara* · Apr 2026 – now
Multi-tenant cloud security posture platform (React, Supabase/Postgres, ~184 edge functions) with RLS everywhere and per-org encrypted credentials. Built a 7-layer policy and audit pipeline and Belay, a guardrail that blocks dangerous AI-agent actions.

**AI Platform Engineer (contract)** · *Nodex8.ai* · Jun 2026 – now
Built Ask Claris: SELECT-only guard, schema allowlist, PII masking, full query audit trail, 12/12 acceptance suite. Merged 14+ ML pipeline outputs into one 5-schema database with 16 quality checks.

**Sole DevOps Engineer (contract)** · *BawaHealth, HIPAA health tech* · Sep 2025 – Apr 2026
Production AWS from scratch with Terraform. 10+ GitHub Actions pipelines (deploys ~45 min → under 1 min), SSM secrets, CloudWatch/SNS alerting, 5 critical incidents fixed solo.

**DevOps Engineer (contract)** · *Ndel Technologies, PCI-DSS fintech* · Sep 2025 – Apr 2026
PCI-aligned AWS (private VPC, least-privilege IAM, RBAC, WAF) with Terraform; 8+ multi-repo pipelines with environment gates and rollback.

**Community Lead** · *Infracodebase* · Jan 2026 – Apr 2026
Ran enterprise Terraform and CI/CD training; published 13 AWS infrastructure workspaces (see below), including a zero-trust EKS landing zone.

**Cloud & DevOps Intern** · *Trainso (Microsoft CSP)* · Apr 2025 – Sep 2025
Secure Azure networking, Terraform, App Service deployments; wrote 70+ infra recipes and 30+ workflow guides.

## 🏆 Numbers

- 18 CI/CD pipelines shipped across two startup clients
- Deploys cut from ~45 min to under 1 min
- Docker images 1.34 GB → 263 MB
- $0 cloud spend for 5+ months, then under $50/month
- 300K+ LinkedIn impressions, 135K+ members reached, 4,100+ followers

## 📌 Featured projects

| Project | What it is |
|---|---|
| [deskbench](https://github.com/NewAi25/deskbench) | AI reliability benchmark; LLM judge checked against 100% human grading (r = 0.694) |
| [plf-audit](https://github.com/NewAi25/plf-audit) | Draft welfare audit standard for precision livestock farming (Sentient Futures) |
| [rag-pipeline](https://github.com/NewAi25/rag-pipeline) | RAG pipeline with eval harness; recall 91.7% → 100%, MRR 0.944 |
| [Eks-Terraform-Helm-Ingress-LB](https://github.com/NewAi25/Eks-Terraform-Helm-Ingress-LB) | EKS with Terraform, Helm and NGINX ingress |
| [system-design-ai-era-7-days](https://github.com/NewAi25/system-design-ai-era-7-days) | 7-day system design course for the AI era |
| [devops-day0-roadmap](https://github.com/NewAi25/devops-day0-roadmap) | Beginner DevOps roadmap with hands-on recipes |

## ☁️ AWS infrastructure workspaces

Terraform and CloudFormation workspaces from my Infracodebase work, each with a README and architecture diagram.

| Repo | What it is |
|---|---|
| [eks-infra](https://github.com/NewAi25/eks-infra) | Modular Terraform for an enterprise EKS landing zone (dev/prod) |
| [eks-terraform-windows-nodes](https://github.com/NewAi25/eks-terraform-windows-nodes) | EKS cluster, Windows EC2 management host and ingress-nginx |
| [blog-microservice-aws](https://github.com/NewAi25/blog-microservice-aws) | Microservices blog platform on EKS with RDS and GitHub Actions |
| [aws-backend-infra](https://github.com/NewAi25/aws-backend-infra) | Backend platform: ECS Fargate, RDS PostgreSQL, CloudFront and WAF |
| [backend-infrastructure-aws](https://github.com/NewAi25/backend-infrastructure-aws) | Containerised Node.js API on ECS Fargate with RDS, WAF and Route 53 |
| [incident-investigator-serverless](https://github.com/NewAi25/incident-investigator-serverless) | Serverless incident investigator: Step Functions, Lambda workers, Bedrock advisory |
| [aws-incident-investigator](https://github.com/NewAi25/aws-incident-investigator) | Incident investigation PoC with security remediations and compliance report |
| [aws-rds-terraform](https://github.com/NewAi25/aws-rds-terraform) | Production RDS PostgreSQL with encryption, Performance Insights and monitoring |
| [trans-s3](https://github.com/NewAi25/trans-s3) | HIPAA-aligned S3 landing zone for healthcare transcripts with cross-account IAM |
| [transcription-s3](https://github.com/NewAi25/transcription-s3) | Secure transcript ingestion on S3 with KMS and audit logging |
| [frontend-infra-aws](https://github.com/NewAi25/frontend-infra-aws) | Security-hardened static hosting: S3, CloudFront OAC, ACM, Route 53 |
| [lovable-app-infra](https://github.com/NewAi25/lovable-app-infra) | Hosting a Lovable (Vite + React) app on S3 + CloudFront, Amplify build spec |
| [aws-amplify-hosting](https://github.com/NewAi25/aws-amplify-hosting) | Postmortem diagram: from broken static hosting to a working Amplify setup |

## 🎓 Education

B.Tech, Electronics & Communication Engineering · IEM Kolkata · 2016–2019
AI safety: Sentient Futures Project Incubator · BlueDot AGI Strategy course

## 📫 Connect

[LinkedIn](https://linkedin.com/in/manishasarkar-devops) · [Oz Lunara](https://app.ozlunara.com/) · [DeskBench site](https://newai25.github.io/deskbench/site)
