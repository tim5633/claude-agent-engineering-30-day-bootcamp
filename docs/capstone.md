# Enterprise Financial Research & Workflow Agent

Use synthetic/public financial data only.

```mermaid
flowchart TD
 U[Web UI] --> API[Authenticated API]
 API --> A[Claude Agent SDK]
 A --> D[Document MCP]
 A --> S[Financial SQL MCP]
 A --> H[Human approval]
 A --> O[Tracing and Evals]
```

- Week 1: Full-stack app and Claude Code engineering.
- Week 2: Messages API, Agent SDK, MCP, retrieval and citations.
- Week 3: >=50 eval cases, approval gates, security, monitoring and deployment.
- Week 4: HLD, ADR, TCO, client presentation and handover.

Definition of done: validated tools, server-side authorization, citations, regression evaluation, trace IDs, cost/latency, CI/CD, rollback and reproducible demo.
