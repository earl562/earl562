# Earl Perry

**Cloud Engineer · DevOps · Multi-Cloud Architect**

I build infrastructure that runs on AWS, GCP, and Azure — not because I was told to, but because understanding the same pattern across all three is what separates engineers who know a vendor's UI from engineers who understand cloud architecture.

---

## What I'm Building

### Multi-Cloud Engineer Portfolio
**5 production architectures × 3 clouds = 15 deployments**

Building the same infrastructure on AWS, GCP, and Azure, documenting what's identical, what differs, and the tradeoffs. Not a tutorial follow-along — a real engineering comparison.

```
Project 1 → HA Infrastructure (VPC, ASG, RDS, ALB)
Project 2 → Infrastructure as Code (Terraform modules, remote state, security scanning)
Project 3 → Containers + Kubernetes (EKS, GKE, AKS, Helm, Workload Identity)
Project 4 → Full CI/CD (GitHub Actions, keyless OIDC, Trivy, tfsec)
Project 5 → Observability (OpenTelemetry, Prometheus, Grafana, SLOs)
```

→ [View Portfolio](https://github.com/earlperry/cloudeng)

---

## Core Skills

```
IaC              Terraform, Pulumi, Ansible
Containers       Docker, Kubernetes, Helm, containerd
Clouds           AWS (EC2, EKS, RDS, ALB, IAM, CloudWatch)
                 GCP (GKE, Cloud SQL, Cloud Run, Cloud Monitoring)
                 Azure (AKS, Azure DB, App Gateway, Azure Monitor)
CI/CD            GitHub Actions, ArgoCD, keyless OIDC auth
Observability    OpenTelemetry, Prometheus, Grafana, distributed tracing
Networking       VPC design, subnets, NAT, load balancers, DNS, firewall rules
Security         IAM/RBAC, Security Groups, NSGs, Workload Identity, tfsec
Languages        Python, bash, HCL, Go (learning), YAML
```

---

## The Multi-Cloud Mindset

The thing I keep learning: **the patterns are portable, the syntax isn't**.

- Terraform `init → plan → apply` is identical on all three. Only the provider block changes.
- The Kubernetes API is the same on EKS, GKE, and AKS. `kubectl apply` works everywhere.
- OpenTelemetry instruments once and exports to CloudWatch, Cloud Monitoring, or Application Insights.
- Keyless OIDC auth from GitHub Actions works on all three — just different config.

When someone asks "do you know AWS or GCP?" — the real answer is: I know how load balancers work, how IAM works, how container orchestration works. The specific service name is a lookup.

---

## Projects

| Repo | Description | Stack |
|------|-------------|-------|
| [cloudeng](https://github.com/earlperry/cloudeng) | Multi-cloud portfolio: same architecture on AWS, GCP, Azure | Terraform, K8s, Docker, GitHub Actions, OpenTelemetry |
| [enclaiv](https://github.com/earlperry/enclaiv) | Open-source AI agent sandboxing platform | Rust, Python, Docker |

---

## Currently Learning

- GCP Professional Cloud Architect certification track
- AWS Solutions Architect Associate review
- Kubernetes CKA exam preparation
- Rust for systems-level tooling

---

## Approach

I build things to understand them, not to screenshot a dashboard.
Each project in this portfolio runs real Terraform against real cloud accounts,
generates real costs (kept under $150 total via free tiers + `terraform destroy`),
and produces documented comparisons that show engineering reasoning, not just code.

---

## Contact

[LinkedIn](https://linkedin.com/in/earlperry) · [Email](mailto:earl@wildhouse.dev)

*Open to cloud engineering, DevOps, SRE, and platform engineering roles.*
