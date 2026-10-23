# Day 19 — Harness Tracing, Observability & Cost

**2026-11-13 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Assigned Partner Academy lesson and direct reading links

**Partner Academy:** [Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations) (verified public landing page; sign in for lessons).

1. [Agent eval methodology](https://www.anthropic.com/research/demystifying-evals-for-ai-agents)
2. [Tool context management](https://platform.claude.com/docs/en/agents-and-tools/tool-use/manage-tool-context)
3. [Prompt caching for tools](https://platform.claude.com/docs/en/agents-and-tools/tool-use/tool-use-with-prompt-caching)

**Read and understand:** Study trace propagation, task costs, errors, token metrics and cache trade-offs.

**Hands-on assignment:** Correlate tool actions, sandbox denials and eval outcomes in a monitoring report.

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

## 今日 Partner Academy 課程與直達教材

**Partner Academy：** [Production Engineering, Evals & Security](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)（已確認公開課程入口；登入後查看內部單元）。

1. [Agent eval methodology](https://www.anthropic.com/research/demystifying-evals-for-ai-agents)
2. [Tool context management](https://platform.claude.com/docs/en/agents-and-tools/tool-use/manage-tool-context)
3. [Prompt caching for tools](https://platform.claude.com/docs/en/agents-and-tools/tool-use/tool-use-with-prompt-caching)

**閱讀目標：** Study trace propagation, task costs, errors, token metrics and cache trade-offs。

**對應實作：** Correlate tool actions, sandbox denials and eval outcomes in a monitoring report。

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
