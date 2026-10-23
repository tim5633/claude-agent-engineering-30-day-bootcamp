# Day 18 — Evaluation Harness & Outcome Graders

**2026-11-12 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Integrated learning and practice

**Official learning:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) relevant authorized modules; [technical documentation](https://docs.anthropic.com/); [deep-dive reference](../docs/evaluation-harness.md).

| Time | Assignment | Evidence |
|---|---|---|
| 00:00–01:30 | Define task success, citation validity, policy adherence and cost metrics | Notes and design sketch |
| 01:30–03:00 | Create 50 synthetic golden cases and resettable test fixtures | Working implementation |
| 03:00–04:30 | Build deterministic graders for SQL outcomes, citations and denied operations | Tested failure scenarios |
| 04:30–05:00 | Execute baseline and regression runs and analyze false positives | ADR, commit and English summary |

**Acceptance:** 50 reproducible evaluations score real tool outcomes, not just answer text.

- [ ] Course and concepts
- [ ] Functioning implementation and negative tests
- [ ] Committed evidence and documented trade-offs

---

<a id="traditional-chinese"></a>

# Day 18 — Evaluation Harness 與結果評分

**2026-11-12 · 5 小時** · [首頁](../README.md)

## 融合式學習與實作

**教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) 帳號內授權課程、[官方文件](https://docs.anthropic.com/)、[深入參考](../docs/evaluation-harness.md)。

| 時段 | 當天學習與實作 | 產出 |
|---|---|---|
| 00:00–01:30 | 定義任務成功、引用、授權與成本指標 | 觀念與架構筆記 |
| 01:30–03:00 | 建立 50 個合成 Golden Cases 和可重置 Fixture | 可執行成果 |
| 03:00–04:30 | 實作 SQL 結果、引用與越權操作的確定性評分器 | 錯誤情境與測試 |
| 04:30–05:00 | 執行 Baseline 與 Regression 並分析誤判 | ADR、Commit 和英文說明 |

**驗收：** 50 個可重現測試驗證實際工具結果，而非僅文字。

- [ ] 完成概念與課程
- [ ] 實作功能及反向測試
- [ ] 提交成果與設計取捨
