<h1 align="center">Walz Ogundiran</h1>

<p align="center">
  <em>Senior SRE & Platform Engineer — Kubernetes Observability, AI-assisted Tooling & Cloud Operations</em><br/>
  <sub>Abingdon-on-Thames, United Kingdom</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/olawale-philips-ogundiran/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/GKE-4285F4?style=flat-square&logo=google-cloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/AKS-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
</p>

---

5 years in site reliability and platform engineering, working on the platform that runs
seismic interpretation and subsurface planning tools for energy companies in production across
Europe, the Americas, and Asia-Pacific.

I build tooling that makes Kubernetes observable and incidents shorter. My current focus is
AI-assisted SRE tooling — deterministic CLI tools paired with Claude Code reasoning skills.

---

### What I'm building

| Project | Description | Status |
|---------|-------------|--------|
| **[kubectl-sentinel](https://github.com/GreenerPlatform/kubectl-sentinel)** | 10-section Kubernetes health checker. Nodes, pods, workloads, probes, services, HPAs, PVCs. Structured JSON + HTML output. Works in CI. | Coming soon |
| **[incident-triage](https://github.com/GreenerPlatform/incident-triage)** | PagerDuty alert → root cause → causation chain → fix plan. Deterministic correlation engine. Python stdlib only. | Coming soon |

---

### Domain Expertise

```
Kubernetes Observability    ██████████████████░░   Prometheus, Thanos, Grafana, Kiali, Istio
Incident Response           █████████████████░░░   PagerDuty, causation chains, root cause classification
Platform Automation         ████████████████░░░░   Helm, ArgoCD, CI/CD pipelines, tenant provisioning
Cloud Operations            ██████████████░░░░░░   GCP, Azure, multi-region, cost optimisation
Security & Compliance       ████████████░░░░░░░░   RBAC, TLS, pod security, secrets hygiene
AI-assisted Tooling         ████████████░░░░░░░░   Dual-layer CLI + LLM reasoning pattern (building)
```

---

### What I've learnt building production SRE tooling

- **The dual-layer pattern** — a deterministic CLI layer that works at 3am in CI, paired with an AI reasoning layer that explains *why*. Separating them gives you both portability and intelligence.
- **Severity as an exit code** — `0/1/2` makes health checkers CI-composable. Think of them as HTTP status codes for shell tools.
- **Classify before you recommend** — OOMKill does not mean "raise the limit". The root cause determines the fix.
- **Building for the 3am reader** — every design decision in an ops tool should be made as if the reader has been awake for 3 hours and needs to act in 5 minutes.

→ [GreenerPlatform/learning-journal](https://github.com/GreenerPlatform/learning-journal) — architecture decisions and engineering thinking from building production SRE tooling

---

<p align="center">
  <em>Working toward CKA → CKS → CNCF contributor. Open to collaborating on Kubernetes observability and platform engineering tooling.</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/olawale-philips-ogundiran/">
    <img src="https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>
