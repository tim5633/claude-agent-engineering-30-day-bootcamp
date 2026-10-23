# Day 20 — Sandboxed Agent Runtime & CI/CD

**2026-11-14 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Assigned Partner Academy lesson and direct reading links

**Partner Academy:** [Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations) (verified public landing page; sign in for lessons).

1. [Claude Code GitHub Actions](https://code.claude.com/docs/en/github-actions)
2. [Claude Code sandboxing](https://code.claude.com/docs/en/sandboxing)
3. [Sandbox deployment considerations](../docs/ai-sandbox-security.md)

**Read and understand:** Study CI, deployment stages, secrets, restricted workers, rollback and health checks.

**Hands-on assignment:** Deploy staging Agent API and enforce sandbox/permission checks in CI.

## Integrated learning and practice

**Official learning:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) relevant authorized modules; [technical documentation](https://docs.anthropic.com/); [deep-dive reference](../docs/ai-sandbox-security.md).

| Time | Assignment | Evidence |
|---|---|---|
| 00:00–01:30 | Design separate application and untrusted execution boundaries | Notes and design sketch |
| 01:30–03:00 | Containerize the API; run untrusted tasks in ephemeral restricted workers | Working implementation |
| 03:00–04:30 | Add CI tests for permission denial, harness limits and eval regression | Tested failure scenarios |
| 04:30–05:00 | Deploy staging with logs, resource caps, secrets isolation and rollback | ADR, commit and English summary |

**Acceptance:** Staging passes controls while worker cannot access application secrets.

- [ ] Course and concepts
- [ ] Functioning implementation and negative tests
- [ ] Committed evidence and documented trade-offs

---

<a id="traditional-chinese"></a>

# Day 20 — Sandbox 化 Agent Runtime 與 CI/CD

**2026-11-14 · 5 小時** · [首頁](../README.md)

## 今日 Partner Academy 課程與直達教材

**Partner Academy：** [Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)（已確認公開課程入口；登入後查看內部單元）。

1. [Claude Code GitHub Actions](https://code.claude.com/docs/en/github-actions)
2. [Claude Code sandboxing](https://code.claude.com/docs/en/sandboxing)
3. [Sandbox deployment considerations](../docs/ai-sandbox-security.md)

**閱讀目標：** Study CI, deployment stages, secrets, restricted workers, rollback and health checks。

**對應實作：** Deploy staging Agent API and enforce sandbox/permission checks in CI。

## 融合式學習與實作

**教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) 帳號內授權課程、[官方文件](https://docs.anthropic.com/)、[深入參考](../docs/ai-sandbox-security.md)。

| 時段 | 當天學習與實作 | 產出 |
|---|---|---|
| 00:00–01:30 | 設計應用服務與非可信任執行的隔離邊界 | 觀念與架構筆記 |
| 01:30–03:00 | 容器化 API，以受限臨時 Worker 執行不可信任任務 | 可執行成果 |
| 03:00–04:30 | 在 CI 加入拒絕授權、Harness 限制及 Eval 回歸測試 | 錯誤情境與測試 |
| 04:30–05:00 | 部署 Staging、資源限制、Secrets 隔離與 Rollback | ADR、Commit 和英文說明 |

**驗收：** Staging 通過測試，Worker 無法讀取應用密鑰。

- [ ] 完成概念與課程
- [ ] 實作功能及反向測試
- [ ] 提交成果與設計取捨
