# Day 16 — Harness State, Checkpoints & Human Approval

**2026-11-10 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Integrated learning and practice

**Official learning:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) relevant authorized modules; [technical documentation](https://docs.anthropic.com/); [deep-dive reference](../docs/agent-harness-engineering.md).

| Time | Assignment | Evidence |
|---|---|---|
| 00:00–01:30 | Learn session persistence, checkpoints, approval gates and idempotency | Notes and design sketch |
| 01:30–03:00 | Implement resumable agent state with a human approval checkpoint | Working implementation |
| 03:00–04:30 | Inject process failure before and after a sensitive tool action | Tested failure scenarios |
| 04:30–05:00 | Test that resume never duplicates consequential side effects | ADR, commit and English summary |

**Acceptance:** An interrupted task resumes safely with an auditable approval.

- [ ] Course and concepts
- [ ] Functioning implementation and negative tests
- [ ] Committed evidence and documented trade-offs

---

<a id="traditional-chinese"></a>

# Day 16 — Harness 狀態、Checkpoint 與人工核准

**2026-11-10 · 5 小時** · [首頁](../README.md)

## 融合式學習與實作

**教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) 帳號內授權課程、[官方文件](https://docs.anthropic.com/)、[深入參考](../docs/agent-harness-engineering.md)。

| 時段 | 當天學習與實作 | 產出 |
|---|---|---|
| 00:00–01:30 | 學習 Session 保存、Checkpoint、人工核准與冪等性 | 觀念與架構筆記 |
| 01:30–03:00 | 建立有人工核准關卡的可恢復 Agent 狀態 | 可執行成果 |
| 03:00–04:30 | 在高風險工具執行前後模擬當機 | 錯誤情境與測試 |
| 04:30–05:00 | 確認 Resume 不會重複執行有副作用的動作 | ADR、Commit 和英文說明 |

**驗收：** 當機後安全恢復，並保留人工核准紀錄。

- [ ] 完成概念與課程
- [ ] 實作功能及反向測試
- [ ] 提交成果與設計取捨
