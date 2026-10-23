# Day 11 — Agent SDK vs Custom Harness

**2026-11-05 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Assigned lessons & direct learning links

**Partner Academy course:** [Production-Grade Prompting, Agents & Tool Use](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations) (company login; locate the named lesson inside the prep path).

1. [Claude Agent SDK overview](https://platform.claude.com/docs/en/agent-sdk/overview)
2. [Agent harness guide](../docs/agent-harness-engineering.md)

**Study objectives:** Study SDK sessions, permission handling and event streaming.

**Required lab:** Rebuild Day 10 harness using Agent SDK and compare behavior.

## Integrated learning and practice

**Official learning:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) relevant authorized modules; [technical documentation](https://docs.anthropic.com/); [deep-dive reference](../docs/agent-harness-engineering.md).

| Time | Assignment | Evidence |
|---|---|---|
| 00:00–01:30 | Study Agent SDK sessions, tools, permissions and execution events | Notes and design sketch |
| 01:30–03:00 | Rebuild Day 10 bounded tool loop with Agent SDK | Working implementation |
| 03:00–04:30 | Compare cancellation, cost, error recovery and permissions with the custom harness | Tested failure scenarios |
| 04:30–05:00 | Write an architecture decision and verify both against the same tests | ADR, commit and English summary |

**Acceptance:** Both variants pass the same task and failure tests.

- [ ] Course and concepts
- [ ] Functioning implementation and negative tests
- [ ] Committed evidence and documented trade-offs

---

<a id="traditional-chinese"></a>

# Day 11 — Agent SDK 與手寫 Harness 比較

**2026-11-05 · 5 小時** · [首頁](../README.md)

## 今日指定課程與直達資源

**Partner Academy：** [Production-Grade Prompting, Agents & Tool Use](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)（使用公司帳號登入並選擇課程內的指定主題）。

1. [Claude Agent SDK overview](https://platform.claude.com/docs/en/agent-sdk/overview)
2. [Agent harness guide](../docs/agent-harness-engineering.md)

**學習重點：** Study SDK sessions, permission handling and event streaming。

**實作成果：** Rebuild Day 10 harness using Agent SDK and compare behavior。

## 融合式學習與實作

**教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) 帳號內授權課程、[官方文件](https://docs.anthropic.com/)、[深入參考](../docs/agent-harness-engineering.md)。

| 時段 | 當天學習與實作 | 產出 |
|---|---|---|
| 00:00–01:30 | 學習 Agent SDK Sessions、Tools、Permissions 及執行事件 | 觀念與架構筆記 |
| 01:30–03:00 | 使用 Agent SDK 重構 Day 10 有界工具循環 | 可執行成果 |
| 03:00–04:30 | 比較兩種 Harness 的取消、成本、錯誤恢復與權限差異 | 錯誤情境與測試 |
| 04:30–05:00 | 記錄選型理由並讓兩種方案通過同一組測試 | ADR、Commit 和英文說明 |

**驗收：** 兩個版本都通過相同任務及故障測試。

- [ ] 完成概念與課程
- [ ] 實作功能及反向測試
- [ ] 提交成果與設計取捨
