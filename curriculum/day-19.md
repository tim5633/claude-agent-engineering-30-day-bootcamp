# Day 19 — Harness Tracing, Observability & Cost

**2026-11-13 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Integrated learning and practice

**Official learning:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) relevant authorized modules; [technical documentation](https://docs.anthropic.com/); [deep-dive reference](../docs/evaluation-harness.md).

| Time | Assignment | Evidence |
|---|---|---|
| 00:00–01:30 | Study correlated events across model, harness, tools, sandbox and graders | Notes and design sketch |
| 01:30–03:00 | Capture session and trace IDs, tool calls, token usage and latencies | Working implementation |
| 03:00–04:30 | Join failure traces to sandbox decisions and evaluation outcomes | Tested failure scenarios |
| 04:30–05:00 | Compare two settings on cost per task, accuracy and error rate | ADR, commit and English summary |

**Acceptance:** Every failing evaluation links to a trace and tool-level root cause.

- [ ] Course and concepts
- [ ] Functioning implementation and negative tests
- [ ] Committed evidence and documented trade-offs

---

<a id="traditional-chinese"></a>

# Day 19 — Harness 追蹤、可觀測性與成本

**2026-11-13 · 5 小時** · [首頁](../README.md)

## 融合式學習與實作

**教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) 帳號內授權課程、[官方文件](https://docs.anthropic.com/)、[深入參考](../docs/evaluation-harness.md)。

| 時段 | 當天學習與實作 | 產出 |
|---|---|---|
| 00:00–01:30 | 理解模型、Harness、Tools、Sandbox、評分器的關聯事件 | 觀念與架構筆記 |
| 01:30–03:00 | 收集 Session／Trace ID、工具呼叫、Token 與延遲 | 可執行成果 |
| 03:00–04:30 | 連結失敗 Trace、Sandbox 決策與評估結果 | 錯誤情境與測試 |
| 04:30–05:00 | 比較兩組設定的單任務成本、成功率與錯誤率 | ADR、Commit 和英文說明 |

**驗收：** 每筆失敗評估可追溯至具體工具及根因。

- [ ] 完成概念與課程
- [ ] 實作功能及反向測試
- [ ] 提交成果與設計取捨
