# Day 15 — Single vs Multi-Agent Harness Architecture

**2026-11-09 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Assigned lessons & direct learning links

**Partner Academy course:** [Production-Grade Prompting, Agents & Tool Use](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations) (company login; locate the named lesson inside the prep path).

1. [Claude Agent SDK](https://platform.claude.com/docs/en/agent-sdk/overview)
2. [Harness deep dive](../docs/agent-harness-engineering.md)

**Study objectives:** Compare one agent, deterministic workflows, routers and supervisors.

**Required lab:** Benchmark single-agent and multi-agent implementations on the same tasks.

## Integrated learning and practice

**Official learning:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) relevant authorized modules; [technical documentation](https://docs.anthropic.com/); [deep-dive reference](../docs/agent-harness-engineering.md).

| Time | Assignment | Evidence |
|---|---|---|
| 00:00–01:30 | Compare sequential pipelines, routers, planner agents and supervisors | Notes and design sketch |
| 01:30–03:00 | Build a simple single-agent baseline and one multi-agent alternative | Working implementation |
| 03:00–04:30 | Run the same tasks through both and record tool calls, success, spend and latency | Tested failure scenarios |
| 04:30–05:00 | Write an ADR selecting architecture by measured outcomes | ADR, commit and English summary |

**Acceptance:** Decision supported by reproducible evaluation and costs.

- [ ] Course and concepts
- [ ] Functioning implementation and negative tests
- [ ] Committed evidence and documented trade-offs

---

<a id="traditional-chinese"></a>

# Day 15 — 單 Agent 與 Multi-Agent Harness 架構

**2026-11-09 · 5 小時** · [首頁](../README.md)

## 今日指定課程與直達資源

**Partner Academy：** [Production-Grade Prompting, Agents & Tool Use](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)（使用公司帳號登入並選擇課程內的指定主題）。

1. [Claude Agent SDK](https://platform.claude.com/docs/en/agent-sdk/overview)
2. [Harness deep dive](../docs/agent-harness-engineering.md)

**學習重點：** Compare one agent, deterministic workflows, routers and supervisors。

**實作成果：** Benchmark single-agent and multi-agent implementations on the same tasks。

## 融合式學習與實作

**教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) 帳號內授權課程、[官方文件](https://docs.anthropic.com/)、[深入參考](../docs/agent-harness-engineering.md)。

| 時段 | 當天學習與實作 | 產出 |
|---|---|---|
| 00:00–01:30 | 比較序列流程、Router、Planner、Supervisor 與多 Agent | 觀念與架構筆記 |
| 01:30–03:00 | 建立單 Agent Baseline 及一個多 Agent 替代方案 | 可執行成果 |
| 03:00–04:30 | 讓兩種架構跑相同任務，記錄成功率、工具次數、費用與延遲 | 錯誤情境與測試 |
| 04:30–05:00 | 用實測證據撰寫架構決策 | ADR、Commit 和英文說明 |

**驗收：** 選型有可重現的品質與成本依據。

- [ ] 完成概念與課程
- [ ] 實作功能及反向測試
- [ ] 提交成果與設計取捨
