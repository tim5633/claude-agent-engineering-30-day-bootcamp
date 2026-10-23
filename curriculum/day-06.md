# Day 06 — MCP Server & Enterprise Tool Design

**2026-10-31 · 5 hours** · [Home](../README.md) · [繁體中文](#traditional-chinese)

## Daily certification learning card

- **Open company course:** [Anthropic Partner Academy — Developer: Claude Code, MCP & Integration](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses) (company sign-in).
- **Study section:** **MCP tools, schemas, auth boundaries** (daily topic focus, not a claim about exact private lesson title).
- **Do this lab:** Implement read-only document MCP and schema-validation negative tests..
- **Maps to:** **CCDV-F, CCAR-F**; cross-check the current [official exam guide](https://anthropic-partners.skilljar.com/page/partner-certifications).
- **Proof:** lesson notes, working code, negative test, and exam-domain checklist.

## Assigned Accenture / Anthropic Partner Academy courses

**Official Partner training:** [Developer: Claude Code, MCP & Integration (MCP); Partner Claude Code Badge](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations). The course title is official; subsections in parentheses indicate which portion to focus on today, not separate certified course titles.

**Certification blueprint mapping:** CCDV-F: MCP integration; CCAR-F: Tool Design & MCP Integration (18%).

**Read these exact references:**
1. [en/mcp](https://code.claude.com/docs/en/mcp)
2. [modelcontextprotocol.io/introduction](https://modelcontextprotocol.io/introduction)

## Daily schedule (5 hours)

| Time | Specific learning task | Evidence |
|---|---|---|
| 0:00–1:30 | Study transports, tool schema, resources, prompts, server-side auth and least privilege. Complete the corresponding named Partner course lesson and read linked docs. | Concept notes and 5 recall questions |
| 1:30–3:00 | Guided lab: Implement read-only document MCP and schema-validation negative tests. | Working feature / config |
| 3:00–4:30 | Closed-book: reproduce and extend the lab; add negative tests and failure handling. | Tests, traces, Git commit |
| 4:30–5:00 | Map takeaways to CCDV-F: MCP integration; CCAR-F: Tool Design & MCP Integration (18%); explain trade-offs in English. | Exam domain notes + ADR |

## Passing criteria

- [ ] Completed today's named academy lesson(s) and official readings
- [ ] Built and tested the exact daily lab with at least one negative test
- [ ] Can explain the exam domain without notes or copied exam questions
- [ ] Committed results and recorded weaknesses

---

<a id="traditional-chinese"></a>

# Day 06 — MCP Server 與企業工具設計

**2026-10-31 · 5 小時** · [首頁](../README.md)

## 每日認證學習卡

- **公司課程：** [Anthropic Partner Academy — Developer: Claude Code, MCP & Integration](https://anthropic-partners.skilljar.com/page/claude-certification-exam-prep-courses)（公司帳號登入）。
- **指定 Section：** **MCP tools, schemas, auth boundaries**（指定主題，不冒充已核實的內部 Lesson 名稱）。
- **Lab：** Implement read-only document MCP and schema-validation negative tests.。
- **對應認證：** **CCDV-F, CCAR-F**，請對照[官方考綱](https://anthropic-partners.skilljar.com/page/partner-certifications)。
- **驗收：** 課程筆記、程式、反向測試與考綱 Checklist。

## 公司 Anthropic Partner Academy 指定課程

**官方課程：** [Developer: Claude Code, MCP & Integration (MCP); Partner Claude Code Badge](https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations)。括號中的「part」是今天的建議閱讀範圍，不是額外捏造的官方課程名稱。

**對應認證考綱：** CCDV-F: MCP integration; CCAR-F: Tool Design & MCP Integration (18%)。

**指定文件直達連結：**
1. [en/mcp](https://code.claude.com/docs/en/mcp)
2. [modelcontextprotocol.io/introduction](https://modelcontextprotocol.io/introduction)

## 每天五小時詳細安排

| 時段 | 必學／必做內容 | 當日交付 |
|---|---|---|
| 00:00–01:30 | 學習 MCP Transport、Tool Schema、Resources、Prompts 及伺服器端授權。完成當日公司課程與官方文件。 | 概念筆記＋5 題自我測驗 |
| 01:30–03:00 | 實作：建立唯讀文件 MCP 與參數錯誤／越權測試。 | 可執行功能／設定 |
| 03:00–04:30 | 不看教程自行重做與擴充，並加入至少一個負面／故障測試。 | 測試、Trace、Commit |
| 04:30–05:00 | 把知識對回 CCDV-F: MCP integration; CCAR-F: Tool Design & MCP Integration (18%)，英文解釋技術取捨。 | 考綱筆記與 ADR |

## 驗收

- [ ] 完成公司指定課程與連結文件
- [ ] 完成每日實作並測試失敗情境
- [ ] 不看筆記也能解釋對應考試領域
- [ ] 提交 Git Commit 與學習缺口記錄
