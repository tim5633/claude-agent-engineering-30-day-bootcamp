# Day 10 — Tool Calling & Bounded Agent Harness

**2026-11-04 · 5 hours** · [Home](../README.md) · [繁體中文 ↓](#traditional-chinese)

## Assigned lessons & direct learning links

**Partner Academy course:** [Production-Grade Prompting, Agents & Tool Use](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations) (company login; locate the named lesson inside the prep path).

1. [How tool use works](https://platform.claude.com/docs/en/agents-and-tools/tool-use/how-tool-use-works)
2. [Tool definitions](https://platform.claude.com/docs/en/agents-and-tools/tool-use/implement-tool-use)

**Study objectives:** Study tool schema contracts, request–execute–result cycle, budgets and termination.

**Required lab:** Implement a bounded Messages API Agent Harness with maximum steps and validated tools.

## Learning outcomes

Map the model→tool request→validation→execution→tool result→model loop.

**Course material:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) (authorized curriculum only), [Claude docs](https://docs.anthropic.com/). **Deep-dive reference:** [Tool Calling & Bounded Agent Harness](../docs/agent-harness-engineering.md).

## Daily 5-hour learning and implementation plan

| Time | Required action | Deliverable |
|---|---|---|
| 00:00–01:30 | Map the model→tool request→validation→execution→tool result→model loop. | Concept notes + trust-boundary sketch |
| 01:30–03:00 | Implement a hand-written Messages API agent harness with tool allowlists and input validation. | Working implementation / design artifact |
| 03:00–04:30 | Add max_steps, deadline, cancellation, bounded retries, token/cost tracking and trace IDs. | Unit / integration / security tests |
| 04:30–05:00 | Create tests for infinite-loop attempts, malformed tool calls and hard stops. | ADR + trace/eval evidence + English explanation |

## Definition of done

**Harness stops deterministically at configured limits, with trace and no unauthorized tool execution.**

- [ ] Relevant concepts and official reading completed
- [ ] Capstone implementation and positive/negative tests completed
- [ ] Evidence and architecture decision committed
- [ ] Explain trade-offs without step-by-step assistance

---

<a id="traditional-chinese"></a>

# Day 10 — Tool Calling 與有界 Agent Harness

**2026-11-04 · 5 小時** · [首頁](../README.md)

## 今日指定課程與直達資源

**Partner Academy：** [Production-Grade Prompting, Agents & Tool Use](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)（使用公司帳號登入並選擇課程內的指定主題）。

1. [How tool use works](https://platform.claude.com/docs/en/agents-and-tools/tool-use/how-tool-use-works)
2. [Tool definitions](https://platform.claude.com/docs/en/agents-and-tools/tool-use/implement-tool-use)

**學習重點：** Study tool schema contracts, request–execute–result cycle, budgets and termination。

**實作成果：** Implement a bounded Messages API Agent Harness with maximum steps and validated tools。

## 今日能力目標

理解模型請求工具、驗證、執行、回傳與下一輪推理的完整循環。

**指定教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/)（依帳號內授權課程）、[Claude 官方文件](https://docs.anthropic.com/)；深入參考 [Tool Calling 與有界 Agent Harness](../docs/agent-harness-engineering.md)。

## 每日五小時實作時間線

| 時段 | 指定學習／實作任務 | 產出 |
|---|---|---|
| 00:00–01:30 | 理解模型請求工具、驗證、執行、回傳與下一輪推理的完整循環。 | 概念筆記與信任邊界圖 |
| 01:30–03:00 | 使用 Messages API 手寫帶有工具白名單與 Schema 驗證的 Agent Harness。 | 可執行實作／架構交付 |
| 03:00–04:30 | 加入最大步數、期限、取消、有限重試、Token／成本記錄與 Trace ID。 | 單元、整合與安全測試 |
| 04:30–05:00 | 建立無限循環、無效工具參數及強制停止測試。 | ADR、Trace／Eval 證據及英文解說 |

## 驗收標準

**Harness 在設定上限時確實停止，有 Trace，且未授權工具無法執行。**

- [ ] 完成課程、概念整理與閱讀
- [ ] 完成 Capstone 實作與正反測試
- [ ] 上傳可驗證成果、測試與技術取捨
- [ ] 不依賴逐步教學解釋整體設計
