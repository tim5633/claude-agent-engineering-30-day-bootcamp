# Day 17 — Sandbox Isolation & Prompt Injection

**2026-11-11 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Assigned Partner Academy lesson and direct reading links

**Partner Academy:** [Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations) (verified public landing page; sign in for lessons).

1. [Claude Code sandboxing](https://code.claude.com/docs/en/sandboxing)
2. [AI Sandbox security lab](../docs/ai-sandbox-security.md)
3. [Risk and secure deployment](https://platform.claude.com/docs/en/managed-agents/secure-deployment-risks)

**Read and understand:** Learn non-root containers, no-secret mounts, restricted network egress and untrusted document threats.

**Hands-on assignment:** Test boundary enforcement for files, outbound connections and injected SQL instructions.

## Integrated learning and practice

**Official learning:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) relevant authorized modules; [technical documentation](https://docs.anthropic.com/); [deep-dive reference](../docs/ai-sandbox-security.md).

| Time | Assignment | Evidence |
|---|---|---|
| 00:00–01:30 | Threat-model untrusted files, injected tool results and secret leakage | Notes and design sketch |
| 01:30–03:00 | Build a disposable non-root container with read-only mounts and restricted egress | Working implementation |
| 03:00–04:30 | Test file isolation, denied network requests and malicious document instructions | Tested failure scenarios |
| 04:30–05:00 | Document OS-level vs model-level enforcement and residual risks | ADR, commit and English summary |

**Acceptance:** Denied access is enforced outside the model, with repeatable test evidence.

- [ ] Course and concepts
- [ ] Functioning implementation and negative tests
- [ ] Committed evidence and documented trade-offs

---

<a id="traditional-chinese"></a>

# Day 17 — Sandbox 隔離與 Prompt Injection

**2026-11-11 · 5 小時** · [首頁](../README.md)

## 今日 Partner Academy 課程與直達教材

**Partner Academy：** [Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)（已確認公開課程入口；登入後查看內部單元）。

1. [Claude Code sandboxing](https://code.claude.com/docs/en/sandboxing)
2. [AI Sandbox security lab](../docs/ai-sandbox-security.md)
3. [Risk and secure deployment](https://platform.claude.com/docs/en/managed-agents/secure-deployment-risks)

**閱讀目標：** Learn non-root containers, no-secret mounts, restricted network egress and untrusted document threats。

**對應實作：** Test boundary enforcement for files, outbound connections and injected SQL instructions。

## 融合式學習與實作

**教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) 帳號內授權課程、[官方文件](https://docs.anthropic.com/)、[深入參考](../docs/ai-sandbox-security.md)。

| 時段 | 當天學習與實作 | 產出 |
|---|---|---|
| 00:00–01:30 | 為非可信任文件、工具回傳和密鑰外洩建模 | 觀念與架構筆記 |
| 01:30–03:00 | 建立非 Root 臨時容器、唯讀掛載及受限網路出口 | 可執行成果 |
| 03:00–04:30 | 驗證檔案隔離、阻擋外連與惡意文件指令 | 錯誤情境與測試 |
| 04:30–05:00 | 區分 OS 隔離與模型拒絕，記錄殘餘風險 | ADR、Commit 和英文說明 |

**驗收：** 拒絕存取由模型外的權限層強制執行。

- [ ] 完成概念與課程
- [ ] 實作功能及反向測試
- [ ] 提交成果與設計取捨
