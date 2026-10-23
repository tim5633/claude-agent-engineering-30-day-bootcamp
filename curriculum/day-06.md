# Day 06 — MCP Tools & Trust Boundaries

**2026-10-31 · 5 hours** · [Home](../README.md) · [繁體中文 ↓](#traditional-chinese)

## Learning outcomes

Understand MCP tool schemas, trust boundaries, credentials and server-side authorization.

**Course material:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) (authorized curriculum only), [Claude docs](https://docs.anthropic.com/). **Deep-dive reference:** [MCP Tools & Trust Boundaries](../docs/ai-sandbox-security.md).

## Daily 5-hour learning and implementation plan

| Time | Required action | Deliverable |
|---|---|---|
| 00:00–01:30 | Understand MCP tool schemas, trust boundaries, credentials and server-side authorization. | Concept notes + trust-boundary sketch |
| 01:30–03:00 | Create a read-only document-search MCP tool for synthetic data. | Working implementation / design artifact |
| 03:00–04:30 | Add schema validation, path allowlisting, tool error handling and no-secrets logging. | Unit / integration / security tests |
| 04:30–05:00 | Test malformed tool requests and denied file paths in an isolated fixture. | ADR + trace/eval evidence + English explanation |

## Definition of done

**MCP rejects malformed or unauthorized requests at the tool boundary, not via prompt instructions.**

- [ ] Relevant concepts and official reading completed
- [ ] Capstone implementation and positive/negative tests completed
- [ ] Evidence and architecture decision committed
- [ ] Explain trade-offs without step-by-step assistance

---

<a id="traditional-chinese"></a>

# Day 06 — MCP 工具與信任邊界

**2026-10-31 · 5 小時** · [首頁](../README.md)

## 今日能力目標

理解 MCP 工具 Schema、信任邊界、憑證與伺服器端授權。

**指定教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/)（依帳號內授權課程）、[Claude 官方文件](https://docs.anthropic.com/)；深入參考 [MCP 工具與信任邊界](../docs/ai-sandbox-security.md)。

## 每日五小時實作時間線

| 時段 | 指定學習／實作任務 | 產出 |
|---|---|---|
| 00:00–01:30 | 理解 MCP 工具 Schema、信任邊界、憑證與伺服器端授權。 | 概念筆記與信任邊界圖 |
| 01:30–03:00 | 以合成資料建立唯讀文件搜尋 MCP 工具。 | 可執行實作／架構交付 |
| 03:00–04:30 | 加入輸入驗證、路徑白名單、錯誤處理及避免記錄 Secrets。 | 單元、整合與安全測試 |
| 04:30–05:00 | 在隔離測試資料中測試無效工具輸入及未授權路徑。 | ADR、Trace／Eval 證據及英文解說 |

## 驗收標準

**MCP 在工具層拒絕無效或未授權請求，而非只靠 Prompt。**

- [ ] 完成課程、概念整理與閱讀
- [ ] 完成 Capstone 實作與正反測試
- [ ] 上傳可驗證成果、測試與技術取捨
- [ ] 不依賴逐步教學解釋整體設計
