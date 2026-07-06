<h1 align="center">Walz Ogundiran</h1>

<p align="center">
  <em>Senior SRE & Platform Engineer — Kubernetes Observability, AI-assisted Tooling & Cloud Operations</em><br/>
  <sub>Oxford, United Kingdom</sub>
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

5 years in site reliability and platform engineering, working on a production platform that
serves enterprise customers across Europe, the Americas, and Asia-Pacific.

I build tooling that makes Kubernetes observable and incidents shorter. My current focus is
AI-assisted SRE tooling — deterministic CLI tools an agent can reason over (via MCP),
never guessing at cluster state.

---

### What I'm building

| Project | Description | Status |
|---------|-------------|--------|
| **[kubectl-sentinel](https://github.com/GreenerPlatform/kubectl-sentinel)** | Kubernetes health snapshot across 15 dimensions, severity-ranked, with a fix command on every finding. JSON / text / HTML. Works in CI. | ![active](https://img.shields.io/badge/status-active-brightgreen?style=flat-square) |
| **[incident-triage](https://github.com/GreenerPlatform/incident-triage)** | Alert → root cause → causation chain → prioritized fix plan. Deterministic correlation engine. Python, stdlib only. | ![active](https://img.shields.io/badge/status-active-brightgreen?style=flat-square) |
| **[greenerplatform-mcp](https://github.com/GreenerPlatform/greenerplatform-mcp)** | MCP server exposing both tools to any AI agent (Cursor, Claude, VS Code). Vendor-neutral. | ![active](https://img.shields.io/badge/status-active-brightgreen?style=flat-square) |

---

### Writing

**[AI Reliability Principles](https://www.linkedin.com/company/ai-reliability-principles/)** — a growing series on making AI dependable enough to trust with real operational decisions. It starts with deterministic-first — establish the facts, then let capable models reason over them — and adds principles as the work teaches them.

- Latest: [*Your AI is smart. Reliability needs it to be consistent.*](https://olawaleogundiran.medium.com/your-ai-is-smart-reliability-needs-it-to-be-consistent-496910033f0f) on Medium
- Follow the series on [LinkedIn](https://www.linkedin.com/company/ai-reliability-principles/) · all posts on [Medium](https://olawaleogundiran.medium.com)

---

### Open Source Contributions

| Project | Contribution | Status |
|---------|-------------|--------|
| **[percona-server-mongodb-operator](https://github.com/percona/percona-server-mongodb-operator/pull/2415)** | Inject a writable `/tmp` emptyDir for the mongod and backup-agent containers so `readOnlyRootFilesystem: true` works without CrashLoopBackOff. Version-gated, unit-tested. Addresses [#1793](https://github.com/percona/percona-server-mongodb-operator/issues/1793). | ![merged](https://img.shields.io/badge/PR-merged-8957e5?style=flat-square&logo=github&logoColor=white) |

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

- **The dual-layer pattern** — a deterministic CLI layer that runs in CI with no internet, paired with an AI reasoning layer that explains *why*. Separating them gives you both portability and intelligence.
- **Severity as an exit code** — `0/1/2` makes health checkers CI-composable. Think of them as HTTP status codes for shell tools.
- **Classify before you recommend** — OOMKill does not mean "raise the limit". The root cause determines the fix.
- **Evidence before reasoning** — the AI is only as trustworthy as the facts under it. Establish cluster state deterministically first, then let the model reason within those bounds.

→ [GreenRanger-IT/learning-journal](https://github.com/GreenRanger-IT/learning-journal) — architecture decisions and engineering thinking from building production SRE tooling

---

<p align="center">
  <em>Building open-source reliability tooling for Kubernetes — deterministic diagnostics an AI agent can trust. Open to collaborating on observability, incident response, and platform engineering.</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/olawale-philips-ogundiran/">
    <img src="https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>
