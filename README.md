# Stéphane Dedu

**Site Reliability Engineer** (apprentice) at Welcome to the Jungle, Paris
Master's student in Cloud & Infrastructure

I got into infrastructure from the application side. After a year shipping Python microservices to Kubernetes, I now work on reliability, platform tooling and Kubernetes security.

[sdedu.cloud](https://sdedu.cloud) · [Blog](https://sdedu.cloud/blog)

---

### Certifications

| Certification | Issuer | Issued |
|---|---|---|
| **CKS** – Certified Kubernetes Security Specialist | CNCF | Jul 2026 |
| **CKA** – Certified Kubernetes Administrator | The Linux Foundation | Mar 2026 |
| **AWS Certified Solutions Architect – Associate** | AWS | Jan 2026 |
| **HashiCorp Certified: Terraform Associate (004)** | HashiCorp | Jan 2026 |

### Stack

**Cloud & IaC:** AWS (EKS, ECS Fargate, RDS, VPC, IAM, Bedrock), Terraform
**Containers & orchestration:** Kubernetes, Helm, Docker
**K8s security:** NetworkPolicies, Seccomp, AppArmor, OPA Gatekeeper, Falco, Trivy, audit logging
**Observability:** Prometheus, Grafana, SLOs & error budgets
**CI/CD:** GitHub Actions
**Languages:** Python (FastAPI, Celery), TypeScript (NestJS, Express), Bash
**Data:** PostgreSQL (pgvector), Redis

### Featured work

**[vLLM-inference-EKS](https://github.com/Stephane-Dedu/vLLM-inference-EKS)** (in progress)
LLM inference on a GPU Kubernetes cluster on EKS, provisioned with Terraform. The repo covers SLOs, observability, load testing and chaos experiments.

**Fissure: production AWS architecture** (private code, [write-up](https://sdedu.cloud/blog))
I moved a mobile app backend from a single public EC2 instance to ECS Fargate behind an ALB, with RDS PostgreSQL Multi-AZ in private subnets, all defined in Terraform. Compute cost went from ~$30/month fixed to ~$8–15/month pay-per-use.

### Experience

- **SRE apprentice**, Welcome to the Jungle (Sep 2026 – present)
- **Backend & Agentic developer apprentice**, Swapn (Oct 2025 – Sep 2026): async FastAPI microservices (DDD, hexagonal architecture), PostgreSQL/pgvector, Redis, Celery, LLM agent tooling on AWS Bedrock. I deployed them to Kubernetes with Helm, CI/CD and Prometheus monitoring.
