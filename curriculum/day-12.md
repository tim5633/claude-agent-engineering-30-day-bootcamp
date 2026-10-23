# Day 12 — Secure MCP & Tool Execution

**2026-11-06 · 5 hours** · [Home](../README.md) · [繁體中文 ↓](#traditional-chinese)

## Assigned lessons & direct learning links

**Partner Academy course:** [Claude Code, MCP & Integration](https://anthropic-partners.skilljar.com/claude-code-mcp-integration) (company login; locate the named lesson inside the prep path).

1. [MCP official specification and guides](https://modelcontextprotocol.io/introduction)
2. [Claude Code MCP docs](https://code.claude.com/docs/en/mcp)
3. [Sandbox security reference](../docs/ai-sandbox-security.md)

**Study objectives:** Study credential scopes, untrusted tool results and tool-side authorization.

**Required lab:** Implement validated read-only finance SQL and documents MCP tools.

## Learning outcomes

Review MCP tool authorization, credentials, untrusted results and input boundaries.

**Course material:** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/) (authorized curriculum only), [Claude docs](https://docs.anthropic.com/). **Deep-dive reference:** [Secure MCP & Tool Execution](../docs/ai-sandbox-security.md).

## Daily 5-hour learning and implementation plan

| Time | Required action | Deliverable |
|---|---|---|
| 00:00–01:30 | Review MCP tool authorization, credentials, untrusted results and input boundaries. | Concept notes + trust-boundary sketch |
| 01:30–03:00 | Create finance SQL and document MCP tools backed only by synthetic data. | Working implementation / design artifact |
| 03:00–04:30 | Apply read-only roles, parameterized queries, validation and per-tool auth checks. | Unit / integration / security tests |
| 04:30–05:00 | Test denied writes, invalid input, malicious document content and redacted logs. | ADR + trace/eval evidence + English explanation |

## Definition of done

**Write attempts fail at database/tool authorization even if the model requests them.**

- [ ] Relevant concepts and official reading completed
- [ ] Capstone implementation and positive/negative tests completed
- [ ] Evidence and architecture decision committed
- [ ] Explain trade-offs without step-by-step assistance

---

<a id="traditional-chinese"></a>

# Day 12 — 安全 MCP 與工具執行

**2026-11-06 · 5 小時** · [首頁](../README.md)

## 今日指定課程與直達資源

**Partner Academy：** [Claude Code, MCP & Integration](https://anthropic-partners.skilljar.com/claude-code-mcp-integration)（使用公司帳號登入並選擇課程內的指定主題）。

1. [MCP official specification and guides](https://modelcontextprotocol.io/introduction)
2. [Claude Code MCP docs](https://code.claude.com/docs/en/mcp)
3. [Sandbox security reference](../docs/ai-sandbox-security.md)

**學習重點：** Study credential scopes, untrusted tool results and tool-side authorization。

**實作成果：** Implement validated read-only finance SQL and documents MCP tools。

## 今日能力目標

理解 MCP Tool 授權、憑證、非可信任結果與輸入邊界。

**指定教材：** [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/)（依帳號內授權課程）、[Claude 官方文件](https://docs.anthropic.com/)；深入參考 [安全 MCP 與工具執行](../docs/ai-sandbox-security.md)。

## 每日五小時實作時間線

| 時段 | 指定學習／實作任務 | 產出 |
|---|---|---|
| 00:00–01:30 | 理解 MCP Tool 授權、憑證、非可信任結果與輸入邊界。 | 概念筆記與信任邊界圖 |
| 01:30–03:00 | 使用合成資料建立財務 SQL 和文件 MCP 工具。 | 可執行實作／架構交付 |
| 03:00–04:30 | 採用唯讀角色、參數化查詢、輸入驗證與工具級授權。 | 單元、整合與安全測試 |
| 04:30–05:00 | 測試拒絕寫入、無效參數、惡意文件與不洩漏密鑰的日誌。 | ADR、Trace／Eval 證據及英文解說 |

## 驗收標準

**即使模型請求資料庫寫入，也會在工具／資料庫授權層遭到拒絕。**

- [ ] 完成課程、概念整理與閱讀
- [ ] 完成 Capstone 實作與正反測試
- [ ] 上傳可驗證成果、測試與技術取捨
- [ ] 不依賴逐步教學解釋整體設計
